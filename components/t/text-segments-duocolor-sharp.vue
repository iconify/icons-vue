<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z_3d7nbol"/><path class="xg9roobfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-segments-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xg9roobfw {
  d: path("M3 5h7v5H3Zm0 9h10v5H3Z");
}

.z_3d7nbol {
  stroke-opacity: 0.4;
  d: path("M14 5h7v5h-7Zm3 9h4v5h-4Z");
}

</style>
