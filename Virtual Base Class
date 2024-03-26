#include <iostream>
using namespace std;

class A {
  public:
    A() // Constructor
    {
        cout << "Constructor A\n";
    }
};

class B: public virtual A {
};

class C: public virtual A {
};

class D: public B, public C {
};

int main() {
  D object; // Object creation of class D.

  return 0;
}
