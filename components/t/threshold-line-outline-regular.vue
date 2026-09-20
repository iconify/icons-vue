<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="a5uqb5btg"/><path class="qn21uclav"/><path class="mcdduacou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:threshold-line-outline-regular" /></template>
<style>
.a5uqb5btg {
  d: path("M9 14v4");
}

.e_6o-gbms {
  d: path("M6 10h13");
}

.mcdduacou {
  d: path("M17 7v11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.qn21uclav {
  d: path("M13 12v6");
}

.r3faxubne {
  d: path("M4 4v16");
}

</style>
