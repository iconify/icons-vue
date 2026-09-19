<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m4elzebub"/><path class="z-1r63ets"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:satellite" /></template>
<style>
.m4elzebub {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M26.736 22.723a3.2 3.2 0 1 1-4.224-1.625a3.2 3.2 0 0 1 4.224 1.625Z");
}

.z-1r63ets {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.282 4.5l7.812 13m7.812 13l7.812 13");
}

</style>
