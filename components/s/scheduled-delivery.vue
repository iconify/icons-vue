<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="woapewu-e"/><path class="lw7bzrwfa"/><rect class="z49l-vbav"/><path class="g36fvl0il"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scheduled-delivery" /></template>
<style>
.g36fvl0il {
  d: path("M12 11.75v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lw7bzrwfa {
  d: path("M2.75 8.75h18.5m-13.5-6v3m8.5-3v3");
}

.woapewu-e {
  width: 18.5px;
  height: 17px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

.z49l-vbav {
  width: 7px;
  height: 6.5px;
  x: 8.5px;
  y: 11.75px;
  rx: 0.75px;
}

</style>
