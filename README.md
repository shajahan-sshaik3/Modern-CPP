# Modern-CPP
This repo is for the essentials Modern concepts of C++.
1. Threads
        -Multithreading
        -Synchronization
        -Return values from the thread function(using promise and future)
   
2. C++ 11
       -Smart Pointers (unique_ptr, shared_ptr, weak_ptr) ->Deprecated the auto_ptr.
       -Keyword: ‘auto’ for dynamic type for the data types. (auto x = 5; // x is an int)
       -‘nullptr’ to initialize the null pointers. (int* p = nullptr;)
       -Move semantics ( move constructor, move assignment operator)
       -Thread library
       -Range based for loop (for(auto i:n){cout<<i<<endl;})
       -Lambda expressions ([](int a, int b){return a+b;})
       -‘final’ and ‘override’ (method declared as final can not be override by derived class. override specifier ensures that the function is virtual and is overriding a             -virtual function from a base class.)
       -‘delete’ and ‘default’ functions (void fun2()=delete; Base() = default;)
3. C++ 14
        -Digits separator (long a = 1'00'000;)
        -Generic lambdas (auto keyword introduced to support generic datatypes, [](int a, int b){return a+b;})
        -Return type deduction (auto keyword introduced to support deduce return type, auto f(int i){return i;})
        -Deprecated attribute ( indicate that a unit (function, class, etc.) is discouraged and likely yield compilation warnings. If a reason is provided, it will be         included in the warnings.)
        [[deprecated]]
        void old_method();
        [[deprecated("Use new_method instead")]]
        void legacy_method();

4. C++ 17
