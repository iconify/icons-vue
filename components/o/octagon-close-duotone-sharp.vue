<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a0pmvabzr"/><path class="ja5o24bac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-close-duotone-sharp" /></template>
<style>
.a0pmvabzr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3h4l5 5v8l-5 5H8l-5-5V8l5-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.ja5o24bac {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h4l5 5v8l-5 5H8l-5-5V8l5-5zM9 9l6 6m0-6l-6 6");
}

</style>
