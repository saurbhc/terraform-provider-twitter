---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "twitter_tweet Resource - terraform-provider-twitter"
subcategory: ""
description: |-
  Tweet resource
---

# twitter_tweet (Resource)

Tweet resource

## Example Usage

```terraform
resource "twitter_tweet" "tweet" {
  text = "Hello from my Terraform provider"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `text` (String) Tweet text

### Read-Only

- `id` (Number) Tweet id
- `user_id` (Number) Tweet user id

