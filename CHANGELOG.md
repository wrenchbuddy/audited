## [Unreleased]
  - Revert button size loading.
  - Hide scrollbar for carousel on safari.
  - Remove align-items from badge.
  - Remove full width from accordion.
  - Revert card component.
  - Remove !important from dialog.css.

## [0.0.27] - 2024-07-25
  - Simplify flash.
  - Simplify dialog__close.
  - Add turbo-frame to _reset.css.
  - Adjust loading button.
  - Remove btn border color.
  - Add toggle buttons.
  - Remover border width input.
  - Adjust focus on toggle.

## [0.0.26] - 2024-07-23
  - Remove comments.
  - Move options to _reset.css.
  - Add z-index variables.

## [0.0.25] - 2024-07-23
  - Reduce rounded and shadow utilities
  - Add skeleton.
  - Add color-link.
  - Add add color-selected-dark.
  - Add invalid feedback to inputs.
  - Better reset for dialog page scroll.
  - Add Flash message.
  - Set bg and color to card.
  - Small adjust in carousel.
  - Remove !important from hidden, contents and inputs.

## [0.0.24] - 2024-07-21
  - Hide spinner for step any inputs.
  - Fix empty date field height on safari IOS.
  - Move "Prevent page scroll when dialog is open" to reset.
  - Add sheet component.

## [0.0.23] - 2024-07-20
  - Don't disable text area resize.
  - Add hover to accordion and table.
  - Add new object-fit utilities.
  - Add aspect ratio variables.
  - Add carousel.

## [0.0.22] - 2024-07-18
  - Adjust prose headers.
  - Adjust responsive fonts again.
  - Use antialiased fonts and bold links on prose.

## [0.0.21] - 2024-07-17
  - Remove antialiased utility.
  - Fix --text-xl-responsive.
  - Remove --width-prose.
  - Rename reponsive font utilities
  - Apply font responsive and max-inline-size to prose

## [0.0.20] - 2024-07-17
  - Add shadow-inner utility.
  - Add responsive fonts.
  - Remove font-size and antialiased from prose.
  - Remove link color from prose.

## [0.0.19] - 2024-07-16
  - Add more animations.
  - Remove shadow-xs.
  - Remove shadow from button.
  - Use color-primary for focus.
  - Fix dark --color-border-dark.
  - Add prose component.
  - Fix card-shadow.

## [0.0.18] - 2024-07-14
  - Transform dialog in a drawer on mobile
  - Correct the arrow style of datalist in Chrome.
  - Fix badge outline border.
  - Add pagination component.
  - Change collapsible component.
  - Fix default icon color alert.
  - Fix badge size.
  - Add button_to_close_dialog helper.
  - Add autogrow textarea.
  - Input server side validation.
  - Add padding to select option.
  - Avatar use local variable for avatar-size
  - Remove size-3 from the utilities
  - Add modern font stack
  - Rename --color-border-darker to --color-border-dark.
  - Introduce --color-border-light.
  - More border utilities.

## [0.0.17] - 2024-07-06
  - Add `color-filter-text-subtle` color and add `colorize-shade` utility class.
  - Change `.break-words` utility class.
  - Add breadcrumb component.
  - Remove not([class]) from button and alert
  - Add collapsible component.
  - Add size-3 to utility classes.
  - Add avatar component.

## [0.0.16] - 2024-07-04
  - Remove return string on `dialog` close.
  - Don't use `light-dark` function in base.css.
  - Use logical properties instead of physical properties.
  - Add grow-0, shrink, and bg-shade to utility classes.
  - Use `min-inline-size: fit-content;` instead of `white-space: nowrap;` for buttons.
  - Fix `transition-property` for dialog.

## [0.0.15] - 2024-07-03
  - `Dialog` was reimplemented to not support popover.

## [0.0.14] - 2024-07-02
  - `Alert dialog` was removed and `dialog` was changed to support `<dialog>` and `<dialog popover>`.
