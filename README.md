## Install

```bash
npm install stylelint-config-punkave --save-dev
```
Add the following to `.stylelintrc` in root directory of project.

```json
{
  "extends": "stylelint-config-punkave"
}
```

## Changelog
### 1.1.2
- Updates `stylelint-order` due to vulnerability warnings.

### 1.1.0
- Rules eased, removing the font-weight rule due to our practice of using a Sass function for the property.

### 1.0.0
- Adds "declaration-strict-value," setting rules for variable use in specific properties.