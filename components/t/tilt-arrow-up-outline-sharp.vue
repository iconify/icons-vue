<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3nl0obvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tilt-arrow-up-outline-sharp" /></template>
<style>
.j3nl0obvx {
  fill: currentColor;
  d: path("M2 21L6 3h12l4 18zm2.5-2h15L16.4 5H7.6zm6.5-7.175V16h2v-4.175l1.6 1.575L16 12l-4-4l-4 4l1.4 1.425zM19.5 19h-15z");
}

</style>
