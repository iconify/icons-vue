<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="joi_wsbpc"/><path class="nvgqe6zou"/><circle class="iaji0abaq"/><circle class="nbxv73-5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scooter-electric" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iaji0abaq {
  cx: 6.5px;
  cy: 18.5px;
  r: 2.25px;
}

.joi_wsbpc {
  d: path("m2.95 14.77l.6-3.79Q3.75 9.75 5 9.75h4.25q1.25 0 1.63 1.19l1.24 3.87Q12.5 16 11.25 16H4q-1.25 0-1.05-1.23");
}

.nbxv73-5j {
  cx: 18.75px;
  cy: 18.5px;
  r: 2.25px;
}

.nvgqe6zou {
  d: path("M8.25 11.25L6.75 13h2.5l-1.5 1.75M12.5 16h5.75m.03.3L16 5.5m-2 0h4");
}

</style>
