<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vafv5ogol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wine-bar" /></template>
<style>
.vafv5ogol {
  fill: currentColor;
  d: path("M8.692 20v-1H11.5v-4.523q-2.15-.33-3.383-1.875T6.884 9V4h10.232v5q0 2.058-1.233 3.602T12.5 14.477V19h2.808v1zM7.884 8.5h8.231V5h-8.23z");
}

</style>
