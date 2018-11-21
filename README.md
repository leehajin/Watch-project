# Watch-project
#include <iostream>
#include <string>
using namespace std;
class Watch
{
public:
int hour;
int minute;
int second;
Watch(int h, int m, int s);
void getTime();
};
Watch::Watch (int h, int m, int s) {hour=h; minute=m; second=s; };
void Watch::getTime()
{cout << hour << endl;
cout<< minute <<endl;
cout<< second <<endl;
}
int main()
{class Watch *ABC = new Watch("5","50","55");
std::cout<<ABC->getTime()<<endl;
return 0;
}


