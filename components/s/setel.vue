<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mfvf950lk"/><path class="wl112cq5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:setel" /></template>
<style>
.mfvf950lk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.622L4.798 31.396h38.404zm19.202 28.774L24 45.377L4.798 31.396");
}

.wl112cq5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.594 31.392L24 45.378l-9.594-13.986L24 2.627z");
}

</style>
