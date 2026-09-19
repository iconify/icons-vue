<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8d079bih"/><path class="c8l65pxft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mi-sphere-cam" /></template>
<style>
.c8l65pxft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.408 33.598c2.976.75 6.26 1.145 9.592 1.153c3.334-.008 6.62-.404 9.595-1.156c.752-2.976 1.147-6.26 1.155-9.594c0-3.338-.39-6.629-1.137-9.613");
}

.o8d079bih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c-4.067.02-7.78 4.627-9.595 11.906C7.127 16.22 2.52 19.933 2.5 24c.02 4.067 4.627 7.78 11.905 9.595C16.22 40.873 19.933 45.48 24 45.5c4.067-.02 7.78-4.627 9.595-11.905C40.873 31.78 45.48 28.067 45.5 24c-.002-4.071-4.604-7.792-11.887-9.613C31.793 7.104 28.07 2.502 24 2.5");
}

</style>
