<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ypziembin"/><path class="me1e_zl4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-close-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.me1e_zl4c {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5 6l1-2h12l2 4v12H4V8zM4 8h16m-10 4l4 4m0-4l-4 4");
}

.ypziembin {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 4h12l2 4H4Z");
}

</style>
