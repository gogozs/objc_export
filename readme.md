# export JSON Object to Objective-C object

## limitation
only handle one level export, nested object won't be exported
- "object": {} => id object

## usage
`ruby main.rb {CLASS_NAME} {input_json_path}`

default output dir is dir of `input_json_path`