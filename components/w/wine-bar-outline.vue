<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no0xbnb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wine-bar-outline" /></template>
<style>
.no0xbnb5m {
  fill: currentColor;
  d: path("M8.692 20v-1H11.5v-4.523q-2.15-.33-3.383-1.875T6.884 9V4h10.232v5q0 2.058-1.233 3.602T12.5 14.477V19h2.808v1zm6.047-7.658q1.165-1.158 1.342-2.842H7.919q.177 1.685 1.343 2.842T12 13.5t2.739-1.158M7.884 8.5h8.232V5H7.885zm4.116 5");
}

</style>
