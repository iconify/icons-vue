<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="n-vrqob0o"/><circle class="mu4rwhbgl"/><path class="t67okk_pp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shot-put" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mu4rwhbgl {
  cx: 14.25px;
  cy: 6.5px;
  r: 1.75px;
}

.n-vrqob0o {
  cx: 8.75px;
  cy: 4.5px;
  r: 1.75px;
}

.t67okk_pp {
  d: path("m10 8.5l2.5 5.5M10 8.5l2.67-1.26M10 8.5l-4.25 3M12.5 14L9 17l-.5 4.25m4-7.25l4.5 2.5l.5 4.75");
}

</style>
