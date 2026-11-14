<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctu-_ogcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-plumber" /></template>
<style>
.ctu-_ogcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.338 18.187l8.132-8.132l2.475 2.475l-8.132 8.132Zm8.132-8.132l-.354-3.182l3.889-3.889l1.945 1.945l-2.122 2.121l2.122 2.122l2.121-2.122l1.945 1.945l-3.889 3.889l-3.182-.354Z");
}

</style>
