<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jzdk39bft"/><path class="mc1dnqb_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:newspaper-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jzdk39bft {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 4v16H3V8h4V4Z");
}

.mc1dnqb_a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4h14v16H3V8h4zm0 4v12m4-12h6m-6 4h6m-6 4h6");
}

</style>
