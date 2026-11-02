<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u24z3jtfd"/><path class="wta6pi43a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sheep-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.u24z3jtfd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 12.268a3.1 3.1 0 0 1-2.201-.875c-1.36-1.308-1.46-3.521.005-4.792c-.41-1.896.998-3.606 2.871-3.836a3.1 3.1 0 0 1 2.217.569c1.659-1.78 4.556-1.78 6.216 0a3.1 3.1 0 0 1 2.217-.569c1.873.23 3.281 1.94 2.871 3.836c1.465 1.271 1.365 3.484.005 4.792a3.1 3.1 0 0 1-2.201.875V17c0 1.554-.49 3.007-1.794 3.939C15.008 21.794 13.435 22 12 22s-3.008-.206-4.206-1.061C6.49 20.007 6 18.554 6 17Z");
}

.wta6pi43a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 11c-2.667 1.333-4.667-2.667-2-4c-1.333-2.667 2.667-4.667 4-2c1.111-2.667 4.889-2.667 6 0c1.333-2.667 5.333-.667 4 2c2.667 1.333.667 5.333-2 4v6c0 3-2 4-5 4s-5-1-5-4Zm0 3l-3 1m13-1l3 1m-10-2h.01M14 13h.01M12 18h.01");
}

</style>
