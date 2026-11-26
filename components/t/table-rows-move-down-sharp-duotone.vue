<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v7v5jwbly"/><path clip-rule="evenodd" class="jmpp78b-l"/><path class="s9tgszbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-move-down-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jmpp78b-l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 2C2 1.4477 2.4477 1 3 1L21 1C21.5523 1 22 1.4477 22 2L22 12L2 12Z");
  stroke: none;
}

.s9tgszbps {
  d: path("M12 15L12 22M8.7071 18.7071L12 22L15.2929 18.7071");
}

.v7v5jwbly {
  stroke-opacity: 0.4;
  d: path("M6 20L3 20L3 11M21 11L21 20L18 20");
}

</style>
