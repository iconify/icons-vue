<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hekhb9bnm"/><rect class="o2nc-y10z"/><path class="kjie_mbme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:theodolite" /></template>
<style>
.hekhb9bnm {
  width: 14px;
  height: 3.5px;
  x: 3.25px;
  y: 4.75px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kjie_mbme {
  d: path("M10.5 12.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-2 4.25l-2.75 4.5m9.75-4.5l2.75 4.5M12 16.75v4.5M17.25 6.5h2.5");
}

.o2nc-y10z {
  width: 10px;
  height: 8.5px;
  x: 7px;
  y: 8.25px;
  rx: 1.5px;
}

</style>
