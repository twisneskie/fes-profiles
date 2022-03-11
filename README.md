# FES Test mdEditor Profiles and Schema

This repository is used for testing experimental mdEditor profile definitions and schema. Use care when implementing them in mdEditor as schema may be unstable. 

## Profile Definitions

Profile definitions are created for mdEditor users in order to create a more streamlined metadata creation process. Profiles control which fields and menus are displayed when editing metadata.

### Adding profile definitions to mdEditor
1. Go to Settings/Profiles.
2. Click the 'Manage Definitions' button.
3. Select 'Add Definition'.
4. Enter the URL for the profile.
5. If desired, enter an alias for the profile that will replace the profile name in the profile list.
6. Click 'Save Definition'.

### Stable profile links
FES Project: https://raw.githubusercontent.com/twisneskie/fes-profiles/main/fes-profiles/fes-proj-profile.json

FES Product: https://raw.githubusercontent.com/twisneskie/fes-profiles/main/fes-profiles/fes-prod-profile.json

## FES Schema

FES Schema are created to enforce program metadata content standards for the Fisheries and Aquatic Conservation and Ecological Services programs.

### Adding schema to mdEditor
1. Go to Settings/Validation.
2. Click the 'Add Schema' button.
3. Enter a title, URL, description, and record type for the schema.
4. Click 'Save Schema'.

### Stable schema links
FES Project: https://raw.githubusercontent.com/twisneskie/fes-profiles/main/fes-schema/fes-project-schema.json
Record type: Metadata

FES Product: https://raw.githubusercontent.com/twisneskie/fes-profiles/main/fes-schema/fes-product-schema.json
Record type: Metadata

## Creating Profiles with Validation Schema
1. Go to Settings/Profiles.
2. Click 'Add Profile'.
3. Enter a title, description (optional), then select the appropriate profile definition and schema(s).
4. Click 'Save Profile'.
