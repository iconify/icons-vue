<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wawan5g4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speaker-3" /></template>
<style>
.wawan5g4d {
  fill: currentColor;
  d: path("M8 22v-1H7q-1.25 0-2.125-.875T4 18V5q0-1.25.875-2.125T7 2h10q1.25 0 2.125.875T20 5v13q0 1.25-.875 2.125T17 21h-1v1z");
}

</style>
