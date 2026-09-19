<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v16w4pw3i"/><rect class="xq-89_owi"/><path class="lq9k0hbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:write-japanese" /></template>
<style>
.lq9k0hbhm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.217 27.722h10.766m-6.738-1.852v6.505c0 1.408.217 3.111 1.294 4.02m2.49-5.604c-1.319 4.57-3.126 7.724-5.566 7.724c-1.576 0-2.661-1.249-2.661-2.753c0-2.679 3.061-5.131 6.982-5.141c2.604-.007 4.736 1.926 4.736 4.386c0 2.286-1.853 3.61-4.663 4.142");
}

.v16w4pw3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.263 19.299L5.5 33.61M31.349 7.866L14.263 19.299M42.5 22.627H28.217c-3.207.035-7.734 3.123-7.708 7.866V42.5m10.84-34.634l-1.623 14.762M26.42 11.164l4.276 2.653m-16.433 5.482l8.687 5.682");
}

.xq-89_owi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
