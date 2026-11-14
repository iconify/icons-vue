<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzw5_ybwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:thought-bubble" /></template>
<style>
.mzw5_ybwc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 14.25q-.027 0-.053-.002q-1.76-.125-2.916-1.458Q2.874 11.457 3 9.696t1.46-2.915q1.039-.9 2.337-1.022q.222-1.703 1.491-2.971Q9.825 1.25 12 1.25t3.712 1.538q1.269 1.268 1.491 2.971q1.298.122 2.337 1.022q1.334 1.155 1.459 2.915q.126 1.761-1.03 3.094t-2.916 1.458q-.026.002-.053.002zm1.5.75Q6 15 6 17.5T8.5 20t2.5-2.5T8.5 15m-5.75 5.5q0-1.75 1.75-1.75t1.75 1.75t-1.75 1.75t-1.75-1.75");
}

</style>
