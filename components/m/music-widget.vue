<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="s_4o94gwi"/><path class="x2vs7b4qp"/><path class="uv1e35bye"/><path class="uaj1k140a"/><circle class="lfz6amxlq"/><path class="ebolfdc2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:music-widget" /></template>
<style>
.ebolfdc2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.586 36.732v-5.47h1.254");
}

.lfz6amxlq {
  cx: 10.379px;
  cy: 36.732px;
  r: 1.207px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s_4o94gwi {
  width: 13.928px;
  height: 13.921px;
  x: 4.5px;
  y: 27.211px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.928px;
  ry: 0.928px;
}

.uaj1k140a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.997 12.474l15.974 11.47c1.812 1.301 1.914 3.811.525 4.673");
}

.uv1e35bye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.829 31.514l-.013 2.657c-.013 2.536 2.805 2.645 5.194 1.092l16.622-10.8c1.97-1.28 2.941-3.661.052-5.503L24.334 7.901c-2.547-1.624-5.245-1.555-5.245 1.817v1.817");
}

.x2vs7b4qp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.18 27.21l-.208-16.713c-.037-2.978 2.666-4.184 4.883-2.804l17.35 10.8c2.715 1.69 2.84 4.818-.104 6.646l-11.21 6.957");
}

</style>
