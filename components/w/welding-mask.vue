<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h11vggblz"/><rect class="y5b_66b-m"/><path class="csu0owb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:welding-mask" /></template>
<style>
.csu0owb4a {
  d: path("M9.5 17h5");
}

.h11vggblz {
  d: path("M12 2.75c4.5 0 7.25 3 7.25 7.5v4.5c0 4-3.25 6.5-7.25 6.5s-7.25-2.5-7.25-6.5v-4.5c0-4.5 2.75-7.5 7.25-7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5b_66b-m {
  width: 8.5px;
  height: 4px;
  x: 7.75px;
  y: 8.5px;
  rx: 1px;
}

</style>
