<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z37wupstu"/><path class="eyhvntpqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-low-duocolor" /></template>
<style>
.eyhvntpqg {
  d: path("M12 19h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z37wupstu {
  stroke-opacity: 0.4;
  d: path("M9 16c1.427-2.14 4.573-2.14 6 0");
}

</style>
