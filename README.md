# unique_ptr
unique_ptr is a RAII class: It is my implementation.  &lt;p> Holds a pointer to managed object (template class) &lt;/p> &lt;p>Constructor copies a pointer&lt;/p> &lt;p>Destructor release memory&lt;/p> &lt;p>Copying is not allowed&lt;/p> &lt;p>Moving is allowed and it means:&lt;/p>  &lt;p>Copying original pointer to a new object&lt;/p>  &lt;p>Setting source pointer to nullptr&lt;/p> &lt;p>Member functions: operator*(), operator->(), get(), release(), reset()&lt;/p>