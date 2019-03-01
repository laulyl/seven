# seven


#dependency
id,
group_id,
artifact_id,
version,
scope


#dependency_group
id,
group_name,
description


#dependency_group_join
id,
dependency_group_id,
dependency_id


#public_class
id,
class_package,
class_type_name,
class_packge_position,jdk-lang,jdk-other,thirdpart
class_category, abstract-class,interface,clazz,void



#public_class_function
id,
public_class_id,
function_modifiers,
function_return_type_id,
function_return_type_source,
function_name,
function_comment


#public_class_function_generic
id,
public_class_function_id,
return_generic_type_id,
return_generic_type_source


#public_class_function_parameter
id,
public_class_function_id,
parameter_type_id,
parameter_type_source




#shema
id,
system_id,
schema_name,
connection_url,
connection_user_name,
connection_password,
connection_driver_class_name


#table_class
id,
schema_id,
table_name,
table_comment
class_package,
class_type_name,
class_chinese_named


#column_property
id,
table_class_id,
column_name,
column_comment,
column_data_type,
column_is_pk,
column_is_uk,
column_is_not_null,
column_is_auto_increament,
column_default_value,
property_name,
property_type_id,
property_chinese_named,
property_foreign_key,
property_is_allow_duplicate,
property_is_owner_id,
property_is_create_time,
property_is_update_time,
property_is_save_required,
property_validate_regex,
property_validate_message,
property_value_insert_type,


system
id,
system_name,
system_description


#project
id,
system_id,
project_name,
project_description,
dependency_id,
parent_id,


#project_dependency
id,
project_id,
dependency_group_id


#module
id,
project_id,
module_package
module_name


#module_class
id,
module_id,
class_package,
class_type_name,
generic_type_id,
generic_type_source,
extends_type_id,
extends_type_source,
class_comment,


#module_class_implement
id,
module_class_id,
implements_type_id,
implements_type_source



#class_field
id,
module_class_id,
field_type_id,
field_type_source,
filed_modfiers,
filed_name,
filed_comment,


#class_function
id,
module_class_id,
function_modifiers,
function_return_type_id,
function_return_type_source,
function_name,
function_comment


#class_function_generic
id,
class_function_id,
return_generic_type_id,
return_generic_type_source


#class_function_parameter
id,
class_function_id,
parameter_type_id,
parameter_type_source


#class_function_script
id,
class_function_id,
script_sort,
script_content














