<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="kzc66iras"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tcl-home" /></template>
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

.kzc66iras {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.492 15.611v9.584h4.738m-24.46-9.584h6.278m-3.139 9.584v-9.584m13 6.369v.04c0 1.753-1.405 3.174-3.139 3.174s-3.139-1.421-3.139-3.175v-3.234c0-1.754 1.405-3.175 3.139-3.175s3.139 1.421 3.139 3.175v.039m-2.545 13.561v-4.58l2.43 4.585l2.428-4.578v4.578M11.77 27.805v4.585m3.219-4.585v4.585m-3.219-2.301h3.219m18.812.008h1.585m.844 2.293H33.8v-4.585h2.43m-16.054 0zc.89 0 1.61.68 1.61 1.519v1.547c0 .839-.72 1.519-1.61 1.519c-.888 0-1.61-.68-1.61-1.519v-1.547c0-.839.721-1.519 1.61-1.519");
}

</style>
