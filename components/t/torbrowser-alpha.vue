<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxp9wcxsz"/><path class="o9lho3-6g"/><path class="fwqcm5bvq"/><path class="whv6v4bpb"/><circle class="vi_nxfq0r"/><path class="ykgdrkrde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:torbrowser-alpha" /></template>
<style>
.fwqcm5bvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.725a10.275 10.275 0 0 1 0 20.55m7.505 3.997A16.05 16.05 0 0 1 24 40.122");
}

.o9lho3-6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.01a4.99 4.99 0 0 1 0 9.98");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.whv6v4bpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.879a16.127 16.127 0 0 1 14.271 23.627");
}

.ykgdrkrde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.9 42.476l2.599-7.976m2.601 8l-2.601-8m1.731 5.324h-3.466");
}

.zxp9wcxsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.326 33.432a21.486 21.486 0 1 0-9.894 9.894");
}

</style>
