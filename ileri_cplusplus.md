# Advanced C++

## copy elision
- temporary materialization 
- prvalue xvalue conversion
- unmaterialized object passing 
- return value optimization (rvo) & named return value optimization (nrvo)
- scenarios blocking copy elision 
- throwing by value 
- catching by value
- mandatory copy elision
- typical mistakes & misconceptions, guidelines

## move semantics
- basic features of move semantics
- std::move
- move semantics & special member functions
- how to use move semantics
- reference qualifiers & move semantics
- moved-from state
- move semantics & exception guarantees
- move only types
- move semantics in STL
- STL moving algorithms
- typical mistakes & misconceptions
- guidelines
- 
  ## perfect forwarding
- forwarding (universal) references
- forwarding reference vs R value reference
- std::forward
- auto && for perfect forwarding
- decltype(auto) and perfect returning
- deferred perfect_returning
- perfect forwarding of return values
- perfect forwarding in STL
- typical mistakes & misconceptions
- guidelines

## type deduction (C++11/14/17/20/23)
_auto type deduction_, _decltype specifier_, _decltype(auto)_, _trailing return type_, _auto return type_, _type deduction in lambda expressions_, _type deductions in function & class templates_

## constants & constant expressions
_constexpr variables_, _constexpr functions_, _constexpr constructors_, _literal types_, _consteval & immediate functions_, _constinit_, _constexpr virtual functions_, _constexpr lambda functions_, _user defined literals_

## generic programming

_template terminology_, 
_function templates_, 
_class templates_, 
_variable templates_, 
_alias templates_, 
_member templates_, 
_template parameters_, 
_type parameters_, 
_non-type parameters_, 
_auto non-type parameters_, 
_template template parameters_, 
_function templates & overloading_, 
_explicit specialization_, 
_partial specialization_, 
_template instantiation_, 
_template arguments_, 
_template argument deduction_, 
_dependent & non-dependent names_, templates & friendship, ctad , 
_meta functions and standard type_traits library_, 
_static_assert declarations_,
_std::type_identity_, 
_tag dispatch_, 
_if constexpr (static if)_, 
_variadic templates_, 
_sizeof... operator_, 
_pack expansion patterns_, 
_fold expressions_
_unary_fold_,
_binary_fold_
_sfinae_, 
_std::enable_if_, 
_std::void_t_, 
_std::declval_, 
_C++20/23 additions_



## concepts (C++20)
_constraints_, _requires clauses_, _requires expressions_, _type requirements_, _compound requirements_, _nested requirements_, _concepts_, _type constraints and auto_, _standard concepts_ 

## exception handling (advanced level)
_exception guarantees in details, noexcept specifier, noexcept operator, when to throw when to catch, what to throw what to catch, std::exception_ptr, std::nested_exception, std::rethrow_exception_, _polymorphic_exception_, _exception_dispatcher_

## lambda expressions C++11/14/17/20/23
_lambda expressions and type deductions_, 
_lambda expressions & constexpr_, 
_generalized lambda expressions_, 
_lambda init capture_, 
_lambda expressions & perfect forwarding_, 
_pack expansions in lambda expressions_, 
_lambda expressions & STL algorithms_, 
_recursive lambda_, 
_lambda expressions in member functions_, 
_lambda expressions for functional programming_, 
_lambda expressions in C++20/23_, 
_template parameter lists on lambdas (C++20)_, 
_new lambda captures (C++20)_, 
_lambda expressions in unevaluated context - C++20_, 
_lambda init capture pack expansions (C++20, 
_default constructible and assignable stateless lambdas (C++20)_, 
_multiple lambda_, 
_IIFE_, 
_lambda call once_, 
_type distinction through lambda_.

## spaceship operator (C++20) 
_comparison categories_, _strong ordering_, _weak ordering_, _partial ordering_, _spaceship operator in STL._

## std::format (C++20)
_std::format_, 
_std::format_to_, 
_std::format_to_n_, 
_std::formatted_size_, 
_std::print_

## C++ idioms and techniques
_ADL + fallback_, 
_attorney - client_, 
_biased distribution (std::discrete_distribution_), 
_clamp_,
_construction_tracker_
_copy & swap idiom_, 
_container idioms_, 
_exception dispatcher_, 
_factories_, 
_gather algorithm_, 
_guarded_suspension_, 
_hidden friends_, 
_IIFE (immediatly invoked lambda expression)_, 
_implementation class_, 
_local buffer optimization_, 
_memory ownership_, 
_mixin classes_, 
_named parameter_, 
_nifty_counter_,
_non virtual interface (NVI)_,
_pimpl & fast pimpl_, 
_positive lambda_, 
_propagate_const_, 
_proxy_, 
_raii_, 
_scope guards_, 
_reference counting_, 
_return_type_resolver_,
_scope_guard_
_slide algorithm_.
_strong types_, 
_swap functions_, 
_tag dispatch_, 
_thread_safe_interface_,
_type erasure_, 
_variant_overloader_,
_virtual constructor_, 
_virtual friend_

<!---
## compiler optimizations
_automatic vectorization_, _common subexpression elimination (CSE)_, _constant folding_, _constant propagation_, _dead code elimination_, _function inlining_, _interprocedural analysis and optimization_, _loop-invariant dode motion_, _loop inversion_, _loop unrolling_, _memory to register promotion_, _procedure integration_, _register allocation_      
--->                                                  
## std::regex
_regex grammer_, _std::basic_regex_, _std::sub_match_, _std::match_results_, _regex_match_, _regex_search_, _regex_replace_, _std::regex_iterator_, _std::regex_token_iterator_

## std::ranges (C++20)
_basics_, _range access_, _range primitives_, _range concepts_, _range_factories_, _range adaptors_

## coroutines (C++20)
_basics_, promise_type, awaitables and awaiters, _co_await_, _co_yield_, _co_return_, _promise_, _generators_, tasks, cooperative multitasking.

## new library components
_std::string_view_, 
_std::optional_, 
_std::variant_, 
_std::any_, 
_file_system_library_, 
_std::span (C++20)_, 
_std::expected(C++23)_, 
_std::mdspan(C++23)_, 
_std::print(C++23)_, 
_std::flat_set (C++23)_, 
_std::flat_map(C++23)_
 
## concurrency in C++
_std::thread_, 
_std::this_thread namespace_, 
_std::jthread (C++20)_, 
_std::stop_token_, 
_thread_local storage_, 
_std::async_, 
_mutex classes_, 
_race condition_ & data race, 
_std::lock_guard_, 
_std::unique_lock_, 
_std::scoped_lock_, 
_deadlocks_, 
_std::once_flag & std::call_once_, 
_std::future_, 
_std::promise_, 
_std::shared_future_, 
_std::packaged_task_, 
_std::condition_variable_, 
_std::atomic_, 
_thread pools_, 
_sequential consistency_,
_acquire release semantics_,
_std::counting_semaphore_,
_std::binary_semaphore_, 
_paralel STL algorithms_,
_concurrency idioms & techniques_. 
