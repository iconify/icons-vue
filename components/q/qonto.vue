<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ftj_hyb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qonto" /></template>
<style>
.ftj_hyb3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.485 42.5Q25.926 40.85 24 24q16.253 3.266 18.486 18.5zm.015-37Q40.266 20.75 24 24Q25.94 7.15 42.5 5.5m-36.984 37Q22.074 40.85 24 24Q7.747 27.266 5.514 42.5zM5.5 5.5Q7.734 20.75 24 24Q22.06 7.15 5.5 5.5");
}

</style>
