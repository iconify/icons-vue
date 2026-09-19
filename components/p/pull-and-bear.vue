<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kc16pj9zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pull-and-bear" /></template>
<style>
.kc16pj9zv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.306 13.373h14.247m-14.247 0h8.521v21.8H5.306zm11.454 8.591c1.87 0 3.385-1.923 3.385-4.295s-1.516-4.296-3.386-4.296h8.332c2.238 0 4.052 2.302 4.052 5.141c0 1.328-.396 2.538-1.047 3.45h1.826c1.87 0 3.385-1.923 3.385-4.296s-1.515-4.295-3.385-4.295h8.331c2.238 0 4.052 2.302 4.052 5.141c0 3.59-2.092 5.76-4.33 5.76c2.372 0 4.295 2.44 4.295 5.449s-1.923 5.45-4.295 5.45H19.787V27.83h8.52v5.55h.836c1.982 0 3.589-2.039 3.589-4.554c0-1.395-.495-2.644-1.274-3.48l-14.699.001z");
}

</style>
