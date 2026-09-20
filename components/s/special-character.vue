<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj5ox2hor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:special-character" /></template>
<style>
.qj5ox2hor {
  fill: currentColor;
  d: path("M3 21v-3h5q-2.1-1.125-3.3-3.125T3.5 10.5q0-3.55 2.475-6.025T12 2t6.025 2.475T20.5 10.5q0 2.375-1.2 4.375T16 18h5v3h-8v-5.1q1.95-.35 3.225-1.875T17.5 10.5q0-2.3-1.6-3.9T12 5T8.1 6.6t-1.6 3.9q0 2 1.275 3.525T11 15.9V21z");
}

</style>
