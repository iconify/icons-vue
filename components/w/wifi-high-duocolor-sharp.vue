<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8-p7nbgc"/><path class="eyhvntpqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-high-duocolor-sharp" /></template>
<style>
.d8-p7nbgc {
  stroke-opacity: 0.4;
  d: path("M9 16c1.427-2.14 4.573-2.14 6 0m-9-3c3.123-3.747 8.878-3.747 12 0M3 10c4.79-5.389 13.21-5.389 18 0");
}

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

</style>
