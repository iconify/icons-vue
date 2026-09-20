<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7d250moc"/><path class="jpf4_0b1i"/><path class="d9y6q7nzx"/><path class="k0h8jyb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:router-agent-outline-thin" /></template>
<style>
.d9y6q7nzx {
  d: path("m14 12 5 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpf4_0b1i {
  d: path("M9 12h5");
}

.k0h8jyb-f {
  d: path("m14 12 5 5");
}

.n7d250moc {
  d: path("M3 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
