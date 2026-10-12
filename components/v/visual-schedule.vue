<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="pcf54sy2i"/><path class="kafegnbvy"/><rect class="iod7g-btv"/><path class="gilxcj5fr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:visual-schedule" /></template>
<style>
.gilxcj5fr {
  d: path("m15 15.75l1.75 3h-3.5ZM4.75 4.5v14m-2-2l2 2l2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iod7g-btv {
  width: 12.5px;
  height: 7.5px;
  x: 8.75px;
  y: 13.75px;
  rx: 2px;
}

.kafegnbvy {
  d: path("M13.5 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.pcf54sy2i {
  width: 12.5px;
  height: 7.5px;
  x: 8.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
