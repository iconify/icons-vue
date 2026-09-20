<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiizlu3sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:r-mobiledata" /></template>
<style>
.kiizlu3sg {
  fill: currentColor;
  d: path("M2 10V2h5q.825 0 1.413.588T9 4v1.35q0 .6-.35 1.088T7.8 7.2L9 10H7L5.85 7.35H4V10zm2-4.65h3V4H4z");
}

</style>
