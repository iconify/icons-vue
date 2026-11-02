<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mq48yf4vi"/><path class="lz_zqfaow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dot-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lz_zqfaow {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v18H3Zm8 9a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.mq48yf4vi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 3v18H3V3Zm-9 10a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
