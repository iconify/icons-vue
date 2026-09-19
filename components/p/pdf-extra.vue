<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dd-q9-ydj"/><path class="l6l7fmxxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pdf-extra" /></template>
<style>
.dd-q9-ydj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.96 20.012c1.738-7.465 8.487-12.987 16.565-12.987C35.933 7.025 43.5 14.592 43.5 24s-7.567 16.975-16.975 16.975");
}

.l6l7fmxxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.164 19.296L4.54 39.441c-.205.818.409 1.534 1.227 1.534h20.758m5.011-12.373H7.607M31.331 8.048L25.4 18.273l-6.033 10.329m17.384 8.896L25.503 18.171");
}

</style>
