<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k9vw8zb-m"/><rect class="o4dndpzsd"/><path class="cxlphtcuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stock-count" /></template>
<style>
.cxlphtcuw {
  d: path("M9 10h6m-6 3.5h6M9 17h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9vw8zb-m {
  d: path("M9 4.5H7.75a2 2 0 0 0-2 2v12.75a2 2 0 0 0 2 2h8.5a2 2 0 0 0 2-2V6.5a2 2 0 0 0-2-2H15");
}

.o4dndpzsd {
  width: 6px;
  height: 3.5px;
  x: 9px;
  y: 2.75px;
  rx: 1px;
}

</style>
