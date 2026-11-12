<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qoajfvbnt"/><path class="sl9ddkbub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pipe-droplet-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qoajfvbnt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12.8 12.4l3 4a1 1 0 0 1 .2.6c0 .587-.106 1.174-.342 1.713C15.021 20.169 13.563 21 12 21a4.3 4.3 0 0 1-1.437-.245c-.99-.353-1.798-1.074-2.221-2.042A4.3 4.3 0 0 1 8 17a1 1 0 0 1 .2-.6l3-4a1 1 0 0 1 1.6 0");
}

.sl9ddkbub {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h5l2 3l-2 3H3m18-6h-5l-2 3l2 3h5m-9 4l-3 4c0 4 6 4 6 0Z");
}

</style>
