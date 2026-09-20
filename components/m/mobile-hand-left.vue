<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0hd2tb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-hand-left" /></template>
<style>
.a0hd2tb-r {
  fill: currentColor;
  d: path("m12.216 21l5.119-6.471l-1.65-1.714q-.77-.788-1.839-.996t-2.058.287l-1.25.63V5.134H7.924v-.519q0-.67.472-1.143Q8.867 3 9.54 3h7.846q.67 0 1.143.472q.472.472.472 1.144v14.769q0 .67-.472 1.143q-.472.472-1.143.472zM7.23 21q-1.25 0-2.125-.875T4.23 18v-7.48q0-1.25.875-2.126T7.23 7.52h.923v9.039l4.688-2.306q.298-.143.595-.07q.298.072.515.29l.221.22l-4.477 5.64q-.275.35-.659.51q-.383.158-.814.158zM14 7.078q.23-.23.23-.54T14 6t-.54-.23q-.309 0-.539.23t-.23.54t.23.539q.23.23.54.23t.539-.23");
}

</style>
