<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zcb15ixya"/><path class="v22nukbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:turtle-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v22nukbrd {
  d: path("M3 14a7 7 0 0 1 14 0Zm12.745-4H19a2 2 0 1 1 0 4h-2a7 7 0 0 0-1.255-4M8 11h4m-4 0L6.476 7.952M12 11l1.524-3.048");
}

.zcb15ixya {
  stroke-opacity: 0.4;
  d: path("M3 14v3a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-3m8 0v3a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-3");
}

</style>
