# Brand Concierge Block

## Overview

The Brand Concierge block provides a mount point for the Brand Concierge interactive experience. It sets a stable DOM id (`brand-concierge-mount`) on the block element so that an external application can attach to it.

## Integration

### Block Configuration

<!-- No configuration keys are read by this block. -->

<!-- ### URL Parameters

No URL parameters affect this block's behavior. -->

<!-- ### Local Storage

No localStorage keys are used by this block. -->

<!-- ### Events

#### Event Listeners

No event listeners are implemented in this block.

#### Event Emitters

No events are emitted by this block. -->

## Behavior Patterns

### Page Context Detection

- **All Contexts**: Renders a single empty container with `id="brand-concierge-mount"` for the external application to mount into.

### User Interaction Flows

1. **Page Load**: Block initializes and sets the `id` attribute on the block element, making it available as a mount target.

### Error Handling

- **Fallback Behavior**: If the external application fails to mount, the block renders as an empty container with no visible content.
