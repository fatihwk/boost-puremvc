


CC=g++
CXXFLAGS=
CFLAGS=-c -Wall -I../  -I/Users/kuiwong/boost
LDFLAGS=
SOURCES=puremvc.cpp
OBJECTS=$(SOURCES:.cpp=.o)
EXECUTABLE=test

all: $(SOURCES) $(EXECUTABLE)
	
$(EXECUTABLE): $(OBJECTS) 
	$(CC) $(LDFLAGS) $(OBJECTS) -o $@

.cpp.o:
	$(CC) $(CFLAGS) $< -o $@



#all: test
#
#test: puremvc.o 
#
#
#puremvc.o: puremvc.cpp ../interfaces/inotification.hpp \
#  ../interfaces/imediator.hpp ../interfaces/ifacade.hpp \
#  ../interfaces/inotifier.hpp ../interfaces/iproxy.hpp \
#  ../interfaces/icommand.hpp ../interfaces/icontroller.hpp \
#  ../core/view.hpp /Users/kuiwong/boost/boost/bind.hpp \
#  /Users/kuiwong/boost/boost/bind/bind.hpp \
#  /Users/kuiwong/boost/boost/config.hpp \
#  /Users/kuiwong/boost/boost/config/user.hpp \
#  /Users/kuiwong/boost/boost/config/select_compiler_config.hpp \
#  /Users/kuiwong/boost/boost/config/compiler/clang.hpp \
#  /Users/kuiwong/boost/boost/config/select_stdlib_config.hpp \
#  /Users/kuiwong/boost/boost/config/no_tr1/utility.hpp \
#  /Users/kuiwong/boost/boost/config/stdlib/libcpp.hpp \
#  /Users/kuiwong/boost/boost/config/select_platform_config.hpp \
#  /Users/kuiwong/boost/boost/config/platform/macos.hpp \
#  /Users/kuiwong/boost/boost/config/posix_features.hpp \
#  /Users/kuiwong/boost/boost/config/suffix.hpp \
#  /Users/kuiwong/boost/boost/ref.hpp \
#  /Users/kuiwong/boost/boost/utility/addressof.hpp \
#  /Users/kuiwong/boost/boost/detail/workaround.hpp \
#  /Users/kuiwong/boost/boost/mpl/bool.hpp \
#  /Users/kuiwong/boost/boost/mpl/bool_fwd.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/adl_barrier.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/adl.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/msvc.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/intel.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/gcc.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/workaround.hpp \
#  /Users/kuiwong/boost/boost/mpl/integral_c_tag.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/static_constant.hpp \
#  /Users/kuiwong/boost/boost/mem_fn.hpp \
#  /Users/kuiwong/boost/boost/bind/mem_fn.hpp \
#  /Users/kuiwong/boost/boost/get_pointer.hpp \
#  /Users/kuiwong/boost/boost/config/no_tr1/memory.hpp \
#  /Users/kuiwong/boost/boost/bind/mem_fn_template.hpp \
#  /Users/kuiwong/boost/boost/bind/mem_fn_cc.hpp \
#  /Users/kuiwong/boost/boost/type.hpp \
#  /Users/kuiwong/boost/boost/is_placeholder.hpp \
#  /Users/kuiwong/boost/boost/bind/arg.hpp \
#  /Users/kuiwong/boost/boost/visit_each.hpp \
#  /Users/kuiwong/boost/boost/bind/storage.hpp \
#  /Users/kuiwong/boost/boost/bind/bind_template.hpp \
#  /Users/kuiwong/boost/boost/bind/bind_cc.hpp \
#  /Users/kuiwong/boost/boost/bind/bind_mf_cc.hpp \
#  /Users/kuiwong/boost/boost/bind/bind_mf2_cc.hpp \
#  /Users/kuiwong/boost/boost/bind/placeholders.hpp \
#  ../core/../interfaces/iview.hpp ../interfaces/iobserver.hpp \
#  ../interfaces/notify_method.hpp \
#  /Users/kuiwong/boost/boost/function.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/iterate.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/iteration/iterate.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/arithmetic/dec.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/config/config.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/arithmetic/inc.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/array/elem.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/array/data.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/tuple/elem.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/cat.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/facilities/overload.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/variadic/size.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/tuple/rem.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/variadic/elem.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/array/size.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/slot/slot.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/slot/detail/def.hpp \
#  /Users/kuiwong/boost/boost/function/detail/prologue.hpp \
#  /Users/kuiwong/boost/boost/config/no_tr1/functional.hpp \
#  /Users/kuiwong/boost/boost/throw_exception.hpp \
#  /Users/kuiwong/boost/boost/function/function_base.hpp \
#  /Users/kuiwong/boost/boost/detail/sp_typeinfo.hpp \
#  /Users/kuiwong/boost/boost/assert.hpp \
#  /Users/kuiwong/boost/boost/integer.hpp \
#  /Users/kuiwong/boost/boost/integer_fwd.hpp \
#  /Users/kuiwong/boost/boost/limits.hpp \
#  /Users/kuiwong/boost/boost/cstdint.hpp \
#  /Users/kuiwong/boost/boost/integer_traits.hpp \
#  /Users/kuiwong/boost/boost/static_assert.hpp \
#  /Users/kuiwong/boost/boost/type_traits/has_trivial_copy.hpp \
#  /Users/kuiwong/boost/boost/type_traits/config.hpp \
#  /Users/kuiwong/boost/boost/type_traits/intrinsics.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_same.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/bool_trait_def.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/template_arity_spec.hpp \
#  /Users/kuiwong/boost/boost/mpl/int.hpp \
#  /Users/kuiwong/boost/boost/mpl/int_fwd.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/nttp_decl.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/nttp.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/integral_wrapper.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/static_cast.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/template_arity_fwd.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/preprocessor/params.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/preprocessor.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/comma_if.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/punctuation/comma_if.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/control/if.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/control/iif.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/logical/bool.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/facilities/empty.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/punctuation/comma.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/repeat.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/repetition/repeat.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/debug/error.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/detail/auto_rec.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/tuple/eat.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/inc.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/lambda.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/ttp.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/ctps.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/overload_resolution.hpp \
#  /Users/kuiwong/boost/boost/type_traits/integral_constant.hpp \
#  /Users/kuiwong/boost/boost/mpl/integral_c.hpp \
#  /Users/kuiwong/boost/boost/mpl/integral_c_fwd.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/lambda_support.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/bool_trait_undef.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_reference.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_lvalue_reference.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_rvalue_reference.hpp \
#  /Users/kuiwong/boost/boost/type_traits/ice.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/yes_no_type.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/ice_or.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/ice_and.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/ice_not.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/ice_eq.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_volatile.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/cv_traits_impl.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_abstract.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_pod.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_void.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_scalar.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_arithmetic.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_integral.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_float.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_enum.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_pointer.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_member_pointer.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_member_function_pointer.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/is_mem_fun_pointer_impl.hpp \
#  /Users/kuiwong/boost/boost/type_traits/remove_cv.hpp \
#  /Users/kuiwong/boost/boost/type_traits/broken_compiler_spec.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/type_trait_def.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/type_trait_undef.hpp \
#  /Users/kuiwong/boost/boost/type_traits/has_trivial_destructor.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_const.hpp \
#  /Users/kuiwong/boost/boost/type_traits/composite_traits.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_array.hpp \
#  /Users/kuiwong/boost/boost/type_traits/is_union.hpp \
#  /Users/kuiwong/boost/boost/mpl/if.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/value_wknd.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/integral.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/eti.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/na_spec.hpp \
#  /Users/kuiwong/boost/boost/mpl/lambda_fwd.hpp \
#  /Users/kuiwong/boost/boost/mpl/void_fwd.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/na.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/na_fwd.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/lambda_arity_param.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/arity.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/config/dtp.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/preprocessor/enum.hpp \
#  /Users/kuiwong/boost/boost/mpl/aux_/preprocessor/def_params_tail.hpp \
#  /Users/kuiwong/boost/boost/mpl/limits/arity.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/logical/and.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/logical/bitand.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/identity.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/facilities/identity.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/empty.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/arithmetic/add.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/control/while.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/list/fold_left.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/list/detail/fold_left.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/control/expr_iif.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/list/adt.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/detail/is_binary.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/detail/check.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/logical/compl.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/list/fold_right.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/list/detail/fold_right.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/list/reverse.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/control/detail/while.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/arithmetic/sub.hpp \
#  /Users/kuiwong/boost/boost/type_traits/alignment_of.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/size_t_trait_def.hpp \
#  /Users/kuiwong/boost/boost/mpl/size_t.hpp \
#  /Users/kuiwong/boost/boost/mpl/size_t_fwd.hpp \
#  /Users/kuiwong/boost/boost/type_traits/detail/size_t_trait_undef.hpp \
#  /Users/kuiwong/boost/boost/utility/enable_if.hpp \
#  /Users/kuiwong/boost/boost/function_equal.hpp \
#  /Users/kuiwong/boost/boost/function/function_fwd.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/enum.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/repetition/enum.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/enum_params.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/repetition/enum_params.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/iteration/detail/iter/forward1.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/iteration/detail/bounds/lower1.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/slot/detail/shared.hpp \
#  /Users/kuiwong/boost/boost/preprocessor/iteration/detail/bounds/upper1.hpp \
#  /Users/kuiwong/boost/boost/function/detail/function_iterate.hpp \
#  /Users/kuiwong/boost/boost/function/detail/maybe_include.hpp \
#  /Users/kuiwong/boost/boost/function/function_template.hpp \
#  /Users/kuiwong/boost/boost/detail/no_exceptions_support.hpp \
#  ../interfaces/notify_context.hpp \
#  ../core/../patterns/observer/obversver.hpp \
#  ../core/../patterns/mediator/mediator.hpp \
#  ../patterns/observer/notifier.hpp ../core/../utils/singlton.hpp \
#  ../core/model.hpp ../core/../interfaces/imodel.hpp \
#  ../core/controller.hpp ../patterns/facade/facade.hpp \
#  ../patterns/observer/notification.hpp \
#  ../patterns/observer/facade_holder.hpp ../patterns/proxy/proxy.hpp \
#  ../patterns/command/simple_command.hpp


clean : 
		rm -rf *.o 
