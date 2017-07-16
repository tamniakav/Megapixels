# Megapixels
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Megapixels
{
    class Megapixels
    {
        static void Main(string[] args)
        {
            int width = int.Parse(Console.ReadLine());
            int height = int.Parse(Console.ReadLine());

            decimal imageSize = width * height;

            decimal imageMP = imageSize / 1000000.00m;

            Console.WriteLine($"{width}x{height} => {Math.Round(imageMP, 1)}MP");
        }
    }
}
