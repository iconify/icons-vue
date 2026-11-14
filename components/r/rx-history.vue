<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8xjto_7p"/><path class="o2gvs3b4v"/><path class="knwgaebnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rx-history" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knwgaebnp {
  d: path("M12.5 8.5V11H15");
}

.o2gvs3b4v {
  d: path("m10.5 6l-2.75-.75l.75-2.75m.5 6h3.5L15 11v5.5H9Z");
}

.r8xjto_7p {
  d: path("M3.75 10.25a8.5 8.5 0 1 0 4-5");
}

</style>
