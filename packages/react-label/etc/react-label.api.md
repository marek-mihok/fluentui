## API Report File for "@fluentui/react-label"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import type { ComponentProps } from '@fluentui/react-utilities';
import type { ComponentState } from '@fluentui/react-utilities';
import type { ForwardRefComponent } from '@fluentui/react-utilities';
import * as React_2 from 'react';
import type { Slot } from '@fluentui/react-utilities';

// @public
export const Label: ForwardRefComponent<LabelProps>;

// @public (undocumented)
export const labelClassName = "fui-Label";

// @public (undocumented)
export type LabelCommons = {
    disabled: boolean;
    size: 'small' | 'medium' | 'large';
    strong: boolean;
};

// @public
export type LabelProps = Omit<ComponentProps<LabelSlots>, 'required'> & Partial<LabelCommons> & {
    required?: boolean | Slot<'span'>;
};

// @public (undocumented)
export type LabelSlots = {
    root: Slot<'label'>;
    required?: Slot<'span'>;
};

// @public
export type LabelState = ComponentState<LabelSlots> & LabelCommons;

// @public
export const renderLabel_unstable: (state: LabelState) => JSX.Element;

// @public
export const useLabel_unstable: (props: LabelProps, ref: React_2.Ref<HTMLElement>) => LabelState;

// @public
export const useLabelStyles_unstable: (state: LabelState) => LabelState;

// (No @packageDocumentation comment for this package)

```
