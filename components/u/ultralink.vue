<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zqr71171n"/><path class="c3h1tkb8y"/><path class="sqvjqh3fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ultralink" /></template>
<style>
.c3h1tkb8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.505 12.561h16.804a2.26 2.26 0 0 1 2.264 2.256v6.611a2.26 2.26 0 0 1-2.255 2.264H14.505a2.26 2.26 0 0 1-2.264-2.257v-6.61a2.26 2.26 0 0 1 2.257-2.264z");
}

.sqvjqh3fg {
  fill: currentColor;
  d: path("M17.518 31.856a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m13.132 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m-9.85 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.284 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.283 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m-9.849 3.228a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m13.132 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m-9.85 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.284 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.283 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0M20.8 28.628a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.284 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.283 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0M20.8 38.312a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.284 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.283 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.zqr71171n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.54 8.028h18.735a4.517 4.517 0 0 1 4.528 4.506v26.439a4.517 4.517 0 0 1-4.507 4.527H13.54a4.517 4.517 0 0 1-4.527-4.507V12.555a4.517 4.517 0 0 1 4.506-4.527zm-.925-.033V6.764c0-1.254.874-2.264 1.96-2.264c1.087 0 1.96 1.01 1.96 2.264V7.9m20.396 7.78a2.26 2.26 0 0 1 2.057 2.254v3.885c0 1.184-.9 2.15-2.058 2.254");
}

</style>
