## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BaseHarnessFilters } from '@angular/cdk/testing';
import { HarnessPredicate } from '@angular/cdk/testing';
import { _MatAutocompleteHarnessBase } from '@angular/material/autocomplete/testing';
import { MatLegacyOptgroupHarness } from '@angular/material/legacy-core/testing';
import { MatLegacyOptionHarness } from '@angular/material/legacy-core/testing';
import { OptgroupHarnessFilters } from '@angular/material/legacy-core/testing';
import { OptionHarnessFilters } from '@angular/material/legacy-core/testing';

// @public @deprecated
export interface LegacyAutocompleteHarnessFilters extends BaseHarnessFilters {
    value?: string | RegExp;
}

// @public @deprecated
export class MatLegacyAutocompleteHarness extends _MatAutocompleteHarnessBase<typeof MatLegacyOptionHarness, MatLegacyOptionHarness, OptionHarnessFilters, typeof MatLegacyOptgroupHarness, MatLegacyOptgroupHarness, OptgroupHarnessFilters> {
    static hostSelector: string;
    // (undocumented)
    protected _optionClass: typeof MatLegacyOptionHarness;
    // (undocumented)
    protected _optionGroupClass: typeof MatLegacyOptgroupHarness;
    // (undocumented)
    protected _prefix: string;
    static with(options?: LegacyAutocompleteHarnessFilters): HarnessPredicate<MatLegacyAutocompleteHarness>;
}

// (No @packageDocumentation comment for this package)

```
