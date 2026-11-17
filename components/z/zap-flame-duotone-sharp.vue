<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pvnsh5k0e"/><path class="u4uvd5bcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pvnsh5k0e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.833 3v4.667h3.5L6.5 15v-4.667H3ZM17 9c.331 1.653 1.335 3.001 2.667 4C20.742 14.077 21 15.534 21 17a4 4 0 0 1-8 0c0-.682.166-1.499.667-2a1.333 1.333 0 0 0 2.666 0c0-1-.333-1.333-.666-2c-.817-1.635.037-2.962 1.333-4");
}

.u4uvd5bcx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.833 3L3 10.333h3.5V15l5.833-7.333h-3.5zM17 9c.333 1.667 1.333 3 2.667 4c1 1 1.333 2.333 1.333 4a4 4 0 1 1-8 0c0-1 .333-1.667.667-2m0 0a1.333 1.333 0 1 0 2.666 0c0-1-.333-1.333-.666-2C15 11.667 15.333 10.333 17 9");
}

</style>
