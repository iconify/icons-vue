<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z74qcvnhy"/><rect class="xpih1f7uh"/><path class="f2r5uobqx"/><rect class="ip0et7bgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:projector-office" /></template>
<style>
.f2r5uobqx {
  d: path("M12 12.75v-4M8.92 6.41l4.66-2.32q.67-.34 1.04.31l.26.45q.37.65-.3.99L9.92 8.16q-.67.34-1.04-.31l-.26-.45q-.37-.65.3-.99");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ip0et7bgo {
  width: 3px;
  height: 6.5px;
  x: 18.25px;
  y: 2.75px;
  rx: 0.75px;
}

.xpih1f7uh {
  width: 12.5px;
  height: 3px;
  x: 5.75px;
  y: 12.75px;
  rx: 1px;
}

.z74qcvnhy {
  width: 16.5px;
  height: 5.5px;
  x: 3.75px;
  y: 15.75px;
  rx: 2px;
}

</style>
