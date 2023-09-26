using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace class007
{
internal class Program
{
static void Main(string[] args)
{

Console.WriteLine(Convert.ToInt32(Console.ReadLine(), 2));


Console.WriteLine(Convert.ToString(Convert.ToInt32(Console.ReadLine()), 2));


int N = Convert.ToInt32(Console.ReadLine());
int M = Convert.ToInt32(Console.ReadLine());
int T = Convert.ToInt32(Console.ReadLine());

M += T;
N += M / 60;
M = M % 60;
N = N % 24;

Console.WriteLine(N + ":" + M);

Console.ReadKey();


}
}


}
