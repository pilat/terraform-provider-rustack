---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "rustack_hypervisors Data Source - terraform-provider-rustack"
subcategory: ""
description: |-
  
---

# rustack_hypervisors (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **project_id** (String) id of the Project

### Optional

- **id** (String) The ID of this resource.

### Read-Only

- **hypervisors** (List of Object) (see [below for nested schema](#nestedatt--hypervisors))

<a id="nestedatt--hypervisors"></a>
### Nested Schema for `hypervisors`

Read-Only:

- **id** (String)
- **name** (String)
- **type** (String)

