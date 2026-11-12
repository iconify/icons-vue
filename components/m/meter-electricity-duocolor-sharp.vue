<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jps9vkgsi"/><path class="gyaiv24xg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-electricity-duocolor-sharp" /></template>
<style>
.gyaiv24xg {
  d: path("M5 3h14v18H5Zm-2 9h2m14 0h2");
}

.jps9vkgsi {
  stroke-opacity: 0.4;
  d: path("m13 8l-3 4h4l-3 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
