<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lrgwget7i"/><path class="rvot348of"/><path class="entdgs0no"/><path class="q30lbsbyl"/><path class="f8gsx7b5s"/><path class="vn9zmkbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shade-tint-duotone-bold" /></template>
<style>
.entdgs0no {
  d: path("M3 5h18v6H3Z");
}

.f8gsx7b5s {
  d: path("M6 8h12");
}

.lrgwget7i {
  fill: currentColor;
  d: path("M3 5h18v6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q30lbsbyl {
  d: path("M3 14h18v6H3Z");
}

.rvot348of {
  fill: currentColor;
  d: path("M3 14h18v6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vn9zmkbyj {
  d: path("M12 17h6");
}

</style>
