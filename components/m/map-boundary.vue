<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fczp76bmy"/><path class="xti2_cccs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-boundary" /></template>
<style>
.fczp76bmy {
  d: path("m2.5 5.5l6-2l7 2l6-2v15l-6 2l-7-2l-6 2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xti2_cccs {
  d: path("M12 7.5a4.5 4.5 0 0 1 3.686 1.919M16.5 12a4.5 4.5 0 0 1-1.919 3.686M12 16.5a4.5 4.5 0 0 1-3.686-1.919M7.5 12a4.5 4.5 0 0 1 1.919-3.686");
}

</style>
