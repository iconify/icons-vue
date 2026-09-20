<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f01ia2u0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-plug-rounded" /></template>
<style>
.f01ia2u0y {
  fill: currentColor;
  d: path("M10.27 19.192v-1.846l-2.791-2.79q-.218-.217-.348-.518T7 13.406V9.62q0-.668.475-1.144T8.615 8h1.231l-.5.5v-4q0-.213.144-.356Q9.634 4 9.847 4t.356.144t.143.356V8h3.308V4.5q0-.213.144-.356T14.155 4t.356.144t.143.356v4l-.5-.5h1.23q.667 0 1.142.476T17 9.619v3.786q0 .324-.13.629q-.132.305-.349.522l-2.79 2.79v1.846q0 .344-.232.576t-.576.232h-1.846q-.343 0-.575-.232t-.233-.576");
}

</style>
