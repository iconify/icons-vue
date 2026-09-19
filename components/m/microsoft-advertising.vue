<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="d-phk184y"/><path class="opy946hdr"/><rect class="c6ctkubbc"/><path class="k4drek6fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-advertising" /></template>
<style>
.c6ctkubbc {
  width: 17px;
  height: 17px;
  x: 7px;
  y: 22.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
  ry: 1.5px;
}

.d-phk184y {
  cx: 39.5px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 15.5px;
}

.k4drek6fx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.675 32.641h-4.35m-1.078 3.219l3.253-9.722l3.252 9.723");
}

.opy946hdr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.999 33.813L39.323 39.5m0-31L13.608 18H6.393a1.5 1.5 0 0 0-1.455 1.135c-.025.098-.09.295-.145.623C4.611 20.848 4.5 22.34 4.5 24s.111 3.151.293 4.242c.055.328.12.524.145.623A1.5 1.5 0 0 0 6.393 30H7");
}

</style>
