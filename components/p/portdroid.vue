<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="el3j14bcn"/><path class="tgc6r_0ao"/><circle class="x0-uid_wl"/><path class="o-0qvxcjr"/><circle class="o-bd-8b6o"/><path class="gvxeqx9ls"/><circle class="rp922793s"/><path class="z0ocg4b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:portdroid" /></template>
<style>
.el3j14bcn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M19.205 45.035C-2.857 34.876 2.955 12.425 4.461 7.71a2 2 0 0 1 1.174-1.244c4.991-1.997 11.302-3.682 13.829-3.682c2.047 0 10.003 1.689 14.999 3.688a1.98 1.98 0 0 1 1.16 1.242c1.508 4.721 7.312 27.165-14.745 37.321a2.02 2.02 0 0 1-1.673 0Z");
}

.gvxeqx9ls {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M21.975 22.756h19.541");
}

.o-0qvxcjr {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M22.605 26.737h5.182");
}

.o-bd-8b6o {
  cx: 29.98px;
  cy: 26.737px;
  r: 1.766px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.rp922793s {
  cx: 43.591px;
  cy: 22.756px;
  r: 1.766px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.tgc6r_0ao {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M23.11 18.494h6.145");
}

.x0-uid_wl {
  cx: 31.432px;
  cy: 18.494px;
  r: 1.766px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.z0ocg4b7r {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("m21.633 22.911l1.028 6.56a.66.66 0 0 1-.651.761h-4.006a.66.66 0 0 1-.651-.762l1.041-6.595a.69.69 0 0 0-.272-.639a3.072 3.072 0 1 1 3.794.028a.69.69 0 0 0-.283.647Z");
}

</style>
