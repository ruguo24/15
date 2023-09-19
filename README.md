# 15
#include <iostream>

using namespace std;

int main()
{    
    int z = 0;
    for(int i = 1, n=9; n > 0; n--,i=(i+1)*2,z=i) {
    }
    cout << z << endl;

    for(int i = 1, n=10; n > 0; n--,i=(i+1)*2) {
        z=i;
    }
    cout << z << endl;

    return 0;
}
