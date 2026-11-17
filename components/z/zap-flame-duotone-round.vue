<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e6nwxmfqr"/><path class="x3psvjb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-duotone-round" /></template>
<style>
.e6nwxmfqr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.417 11.333L7.33 13.957a.466.466 0 0 1-.83-.29v-2c0-.737-.597-1.334-1.333-1.334h-.834A.642.642 0 0 1 3.83 9.29l4.173-5.247a.466.466 0 0 1 .83.29v2c0 .737.597 1.334 1.334 1.334H11a.642.642 0 0 1 .503 1.043ZM17 9c.331 1.653 1.335 3.001 2.667 4C20.742 14.077 21 15.534 21 17a4 4 0 0 1-8 0c0-.682.166-1.499.667-2a1.333 1.333 0 0 0 2.666 0c0-1-.333-1.333-.666-2c-.817-1.635.037-2.962 1.333-4");
}

.ft5dv1b6b {
  fill: none;
}

.x3psvjb2h {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9.417 11.333l2.086-2.623A.643.643 0 0 0 11 7.667h-.833a1.333 1.333 0 0 1-1.334-1.334v-2a.466.466 0 0 0-.83-.29L3.83 9.29a.643.643 0 0 0 .503 1.043h.834c.736 0 1.333.597 1.333 1.334v2c0 .44.556.635.83.29zM17 9c.333 1.667 1.333 3 2.667 4c1 1 1.333 2.333 1.333 4a4 4 0 1 1-8 0c0-1 .333-1.667.667-2m0 0a1.333 1.333 0 1 0 2.666 0c0-1-.333-1.333-.666-2C15 11.667 15.333 10.333 17 9");
}

</style>
