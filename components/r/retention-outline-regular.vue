<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="ler50rfbf"/><path class="siun7_bal"/><path class="cub64ac5a"/><path class="cjsg0ab2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retention-outline-regular" /></template>
<style>
.cjsg0ab2y {
  d: path("M2 20h20");
}

.cub64ac5a {
  d: path("M19 13v7");
}

.ler50rfbf {
  d: path("M9 8v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r3faxubne {
  d: path("M4 4v16");
}

.siun7_bal {
  d: path("M14 11v9");
}

</style>
