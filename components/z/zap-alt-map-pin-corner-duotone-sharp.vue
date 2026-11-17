<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bgu3prbob"/><path class="ai22aac8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-map-pin-corner-duotone-sharp" /></template>
<style>
.ai22aac8b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.394 10H10l4-7H7l-4 9h3l-2 9l6.085-6.085M17 21c-1.5-1-3-3-3-5a3 3 0 0 1 6 0c0 2-1.5 4-3 5m0-5h.01");
}

.bgu3prbob {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 10h3.394a7 7 0 0 0-3.309 4.915L4 21l2-9H3l4-9h7Zm7 11c-1.574-1.051-2.999-3.053-3-5a3 3 0 1 1 6 0c-.001 1.947-1.426 3.949-3 5");
}

.ft5dv1b6b {
  fill: none;
}

</style>
