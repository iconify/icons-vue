<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="r9co1dboz"/><path class="yx9ptr6oa"/><rect class="cpmswccvi"/><path class="zy9xxactq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:office-chair" /></template>
<style>
.cpmswccvi {
  width: 14.5px;
  height: 3px;
  x: 4.75px;
  y: 13px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r9co1dboz {
  width: 9.5px;
  height: 7px;
  x: 7.25px;
  y: 2.75px;
  rx: 2.5px;
}

.yx9ptr6oa {
  d: path("M12 9.75V13");
}

.zy9xxactq {
  d: path("M12 16v2.75m-5.75 2.5l5.75-2.5l5.75 2.5");
}

</style>
