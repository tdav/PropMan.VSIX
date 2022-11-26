# PropMap

        public long GroupId { get; set; }

            |

        long groupId;
        public long GroupId { get => groupId; set { SetPropertyValue<long>(nameof(GroupId), ref groupId, value); } }




Property Manipulation Utilities for encapsulating fields, converting auto-properties to full properties and back.

This is a source code and defect tracking repository only. For all binaries please visit the product [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=OlegShilo.PropMan) page.

You can find the extension binaries on the Releases page: https://github.com/oleg-shilo/PropMan.VSIX/releases
