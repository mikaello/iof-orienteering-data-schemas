# iof-orienteering-data-schemas

The official Internation Orienteering Federation DTDs and XSDs converted to other (unofficial) formats, including XSD, JSON Schema and GraphQL Schema.

## Contents

### Datastandard v2

See [official v2 repo](https://github.com/international-orienteering-federation/datastandard-v2) for original documents.

- [Official DTD](./IOFdata.dtd) for v2
- [Unoffical XSD](./iof_v2.xsd) for v2, converted from DTD to XSD with [trang.jar](https://relaxng.org/jclark/trang-manual.html) (see also [GitHub](https://github.com/relaxng/jing-trang))
- [Unofficial JSON Schema](./iof_v2_schema.json) for v2, converted from unofficial XSD with a custom Jackson JsonSchemaGenerator
- [Unofficial JSON Schema](./IOF_v2.json) for v2, converted from unofficial XSD with [jsonix-schema-compiler](https://github.com/highsource/jsonix-schema-compiler)
- [JSONIX mappings](./IOF_v2.js) for v2, generated from unofficial XSD with [jsonix-schema-compiler](https://github.com/highsource/jsonix-schema-compiler)

### Datastandard v3

See [official v3 repo](https://github.com/international-orienteering-federation/datastandard-v3) for original documents.

- [Official XSD](./IOF.xsd) for v3
- [Unofficial JSON Schema](./iof_v3_schema.json) for v3, converted from official XSD with a custom Jackson JsonSchemaGenerator
- [Unofficial JSON Schema](./IOF_v3.json) for v3, converted from official XSD with [jsonix-schema-compiler](https://github.com/highsource/jsonix-schema-compiler)
- [JSONIX mappings](./IOF_v3.js) for v3, generated from official XSD with [jsonix-schema-compiler](https://github.com/highsource/jsonix-schema-compiler)
