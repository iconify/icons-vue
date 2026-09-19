<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rh5pvqb8c"/><path class="jb4sxxbzc"/><path class="nmg3-j4-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plex-photos" /></template>
<style>
.jb4sxxbzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 12.6h-8l-2.594-4h-9.812l-2.594 4h-8a4 4 0 0 0-4 4v18.8a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4V16.6a4 4 0 0 0-4-4");
}

.nmg3-j4-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.104 30.808L26.09 26l-3.986-4.808");
}

.rh5pvqb8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 17.5a8.5 8.5 0 1 1-8.5 8.5h0a8.5 8.5 0 0 1 8.5-8.5");
}

</style>
