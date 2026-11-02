<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t6r1jgw6n"/><path class="vco3hvbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:venus-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t6r1jgw6n {
  stroke-opacity: 0.4;
  d: path("M12 13v8m-3-4h6");
}

.vco3hvbdw {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 0 0 7 8");
}

</style>
