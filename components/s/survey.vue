<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><path class="ifksg0bxy"/><circle class="pbtvbbcua"/><path class="a3cu9ndgh"/><circle class="oggm679kn"/><path class="pv0kulbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:survey" /></template>
<style>
.a3cu9ndgh {
  d: path("M12.5 11.5h3.25");
}

.dnp2npbye {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifksg0bxy {
  d: path("M8.25 6.75h7.5");
}

.oggm679kn {
  cx: 9px;
  cy: 16.5px;
  r: 1.5px;
}

.pbtvbbcua {
  cx: 9px;
  cy: 11.5px;
  r: 1.5px;
}

.pv0kulbqn {
  d: path("M12.5 16.5h3.25");
}

</style>
