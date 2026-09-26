<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pzck7wbzu"/><path class="zu2u1mcjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:reply-all-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pzck7wbzu {
  stroke-opacity: 0.4;
  d: path("M14 4L8 10L14 16M8 10L18 10C20.2091 10 22 11.7909 22 14L22 20");
}

.zu2u1mcjz {
  d: path("M8 4L2 10L8 16");
}

</style>
