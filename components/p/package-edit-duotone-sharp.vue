<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ypziembin"/><path class="e2ugtnb7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-edit-duotone-sharp" /></template>
<style>
.e2ugtnb7l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5 6l1-2h12l2 4v12H4V8zM4 8h16M9 17v-2l4-4l2 2l-4 4Z");
}

.ft5dv1b6b {
  fill: none;
}

.ypziembin {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 4h12l2 4H4Z");
}

</style>
