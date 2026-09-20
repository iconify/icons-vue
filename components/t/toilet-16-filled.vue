<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bz42qdu6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toilet-16-filled" /></template>
<style>
.bz42qdu6w {
  fill: currentColor;
  d: path("M12.504 10.959q.242.04.496.041l.001-.001V13a2 2 0 0 1-2 2h-6a1 1 0 0 1-.912-1.41l.687-1.53A5.97 5.97 0 0 0 8 13c1.796 0 3.405-.79 4.504-2.041M3.5 9h6.673c.237.67.704 1.227 1.306 1.583A4.98 4.98 0 0 1 8 12a5 5 0 0 1-4.586-3.005zm10-8A1.5 1.5 0 0 1 15 2.5V8a2 2 0 1 1-4 0V2.5A1.5 1.5 0 0 1 12.5 1zM10 8H3a1 1 0 0 1 0-2h7z");
}

</style>
