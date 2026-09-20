<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iks3fibpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-note-off-2-20-filled" /></template>
<style>
.iks3fibpu {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708L7 7.707V13.5a2.5 2.5 0 1 0 1 2V8.707l3.414 3.414a2.5 2.5 0 0 0 3.465 3.465l2.267 2.268a.5.5 0 0 0 .708-.708zM13.5 11q-.18 0-.354.025l2.83 2.829q.023-.174.024-.354V3.18q0-.084-.013-.165a1 1 0 0 0-1.285-.79l-7 2.188a1 1 0 0 0-.617.55l2.811 2.812L15 6.18v5.32a2.5 2.5 0 0 0-1.5-.5");
}

</style>
