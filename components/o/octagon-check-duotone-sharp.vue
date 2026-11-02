<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a0pmvabzr"/><path class="hq3yrg7iu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-check-duotone-sharp" /></template>
<style>
.a0pmvabzr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3h4l5 5v8l-5 5H8l-5-5V8l5-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.hq3yrg7iu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h4l5 5v8l-5 5H8l-5-5V8l5-5zm-4 9l3 3l5-6");
}

</style>
