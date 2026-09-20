<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="npws3hf2k"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:marriott-bonvoy" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.npws3hf2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.045 33.572h6.01m-3.088-2.07za1.715 1.715 0 0 1-1.728-1.702v-1.82c0-.997.798-1.794 1.728-1.794c.996 0 1.794.797 1.794 1.794v1.727c0 .997-.798 1.794-1.794 1.794zm-.017-9.689zc-1.5 0-2.6-1.2-2.6-2.6v-2.7c0-1.5 1.2-2.7 2.6-2.7c1.5 0 2.7 1.2 2.7 2.7v2.6c0 1.5-1.2 2.7-2.7 2.7m-9.202-4h-3.4m3.2 0c1.1 0 2 .9 2 2s-.9 2-2 2h-3.3v-8h3.3c1.1 0 2 .9 2 2s-.9 2-2 2m1.9 8.374l-2.6 8l-2.6-8m22.854 8v-4m2.6-4l-2.6 4l-2.6-4m-.05-4.374v-8l5.3 8v-8");
}

</style>
