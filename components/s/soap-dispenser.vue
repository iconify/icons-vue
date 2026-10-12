<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lo-9w9bwd"/><rect class="xjvz5lbsk"/><rect class="zk8uc6b_m"/><path class="k8tynqfme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soap-dispenser" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8tynqfme {
  d: path("M9.25 14.75h5.5");
}

.lo-9w9bwd {
  d: path("M12 7.75v-3m3 0H8a.75.75 0 0 0-.75.75v1.25");
}

.xjvz5lbsk {
  width: 4px;
  height: 2.5px;
  x: 10px;
  y: 7.75px;
  rx: 0.5px;
}

.zk8uc6b_m {
  width: 11.5px;
  height: 11px;
  x: 6.25px;
  y: 10.25px;
  rx: 2.5px;
}

</style>
