<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4xm0ibis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-video-camera-back" /></template>
<style>
.g4xm0ibis {
  fill: currentColor;
  d: path("M18 10.48V4H2v16h16v-6.48l4 3.98v-11zM5 16l2.38-3.17L9 15l2.62-3.5L15 16z");
}

</style>
