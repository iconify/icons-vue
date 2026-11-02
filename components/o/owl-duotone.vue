<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zplvtebpz"/><path class="frk8_ob9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-duotone" /></template>
<style>
.frk8_ob9m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3c2.5 1.5 5 2 8 2s5.5-.5 8-2c1 2.5 1 4.5 1 7c0 4.5-4 8-9 8s-9-3.5-9-8c0-2.5 0-4.5 1-7M3 21h18m-11-3v3m4-3v3M6 10a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m-2 3v2");
}

.ft5dv1b6b {
  fill: none;
}

.zplvtebpz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.044 3.59C9.337 3.897 10.674 4 12 4s2.663-.103 3.956-.41a12.4 12.4 0 0 0 3.53-1.447a.998.998 0 0 1 1.442.486c.483 1.205.799 2.47.941 3.761C22.002 7.588 22 8.796 22 10a8.3 8.3 0 0 1-.799 3.575a8.8 8.8 0 0 1-2.163 2.861c-2.924 2.586-7.275 3.224-10.9 1.885c-2.302-.851-4.284-2.509-5.339-4.746A8.3 8.3 0 0 1 2 10c0-1.204-.002-2.412.131-3.61c.142-1.291.458-2.556.941-3.761a.998.998 0 0 1 1.442-.486a12.4 12.4 0 0 0 3.53 1.447");
}

</style>
