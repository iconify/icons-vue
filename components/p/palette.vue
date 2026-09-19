<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="lx190bbdu"/><path class="zlahjrbth"/><ellipse class="la4znszdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:palette" /></template>
<style>
.la4znszdr {
  cx: 24px;
  cy: 38.01px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.965px;
  ry: 1.957px;
}

.lx190bbdu {
  width: 18.314px;
  height: 39px;
  x: 14.843px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
}

.zlahjrbth {
  fill: none;
  stroke: currentColor;
  d: path("M14.843 33.4h18.314M14.843 22.236s3.933-.233 5.292 2.27s2.605 3.387 4.466.291s3.5-6.83 8.556-.514m-.001-11.601s-1.669-2.183-3.418-2.088s-4.099 4.972-5.418 4.852s-2.285-6.481-4.118-7.03s-5.36 2.35-5.36 2.35");
}

</style>
