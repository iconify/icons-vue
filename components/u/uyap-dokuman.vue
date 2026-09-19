<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eq0f2wb1h"/><circle class="s4roj7b5l"/><circle class="swvcqhase"/><path class="vcdp36bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uyap-dokuman" /></template>
<style>
.eq0f2wb1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5C13.783 42.5 5.5 34.218 5.5 24S13.783 5.5 24 5.5S42.5 13.783 42.5 24v18.5z");
}

.s4roj7b5l {
  cx: 21.056px;
  cy: 22.094px;
  r: 11.967px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.swvcqhase {
  cx: 35.368px;
  cy: 36.076px;
  r: 3.466px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vcdp36bvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.36 19.043v4.042c0 1.144.916 2.06 1.983 2.06s1.983-.916 1.983-2.06v-4.042m8.375 3.051h1.983m1.067 3.051h-3.05v-6.102h3.05m-9.175 6.101v-6.101h1.373c1.449 0 2.67 1.22 2.67 2.669v.763c0 1.449-1.221 2.669-2.67 2.669z");
}

</style>
