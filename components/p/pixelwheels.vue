<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 24 24)" class="qni-53p4r"/><path class="v609tkb4l"/><path class="fglzb5p_g"/><path class="z22qzhbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixelwheels" /></template>
<style>
.fglzb5p_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.25 26.44l-3.541.757l-.389-.388l4.579-4.579h1.144l1.209 1.209zm14.238.382h3.56c0-2.356.188-3.24-.561-3.99l-6.32-6.319c-.75-.75-1.633-.562-3.989-.562v3.561Zm-2.745 5.135h1.171l5.135-5.135h-3.561l-3.94 3.94z");
}

.qni-53p4r {
  width: 18.925px;
  height: 37.078px;
  x: 14.538px;
  y: 5.461px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.724px;
}

.v609tkb4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.42 41.962a1.38 1.38 0 0 0 1.953 0l3.56-3.56a1.38 1.38 0 0 0 0-1.953m11.516-11.516a1.38 1.38 0 0 0 1.953 0l3.56-3.56a1.38 1.38 0 0 0 0-1.954m-18.895-7.868a1.38 1.38 0 0 1 0-1.953l3.56-3.56a1.38 1.38 0 0 1 1.954 0M6.038 28.58a1.38 1.38 0 0 1 0-1.953l3.56-3.56a1.38 1.38 0 0 1 1.953 0m4.492-.81v-1.171l5.135-5.135v3.561l-3.94 3.94z");
}

.z22qzhbmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.56 33.75l-.757 3.541l.388.389l4.579-4.579v-1.144l-1.209-1.209zm-3.849 3.541h3.092l.586-2.743l-7.937-7.937l-2.743.586v3.092zm13.776-14.459l5.643-5.643v-2.274l2.002-2.001m-13.964 3.599l5.643-5.643h2.274l2.001-2.002");
}

</style>
