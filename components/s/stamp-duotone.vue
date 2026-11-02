<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wxn_-lb2q"/><path class="x7mmocc_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stamp-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wxn_-lb2q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 11V8.38a3.828 3.828 0 0 1 5.601-5.189A3.83 3.83 0 0 1 15 8.38V11h3a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3Z");
}

.x7mmocc_o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm1 7h14m-9-9V8a2.828 2.828 0 1 1 4 0v4");
}

</style>
