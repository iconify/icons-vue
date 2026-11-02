<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5by80bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-sparkle-fill" /></template>
<style>
.k5by80bct {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m7 4a1 1 0 0 0-1 1c0 .574-.086 1.151-.293 1.688a3.5 3.5 0 0 1-.789 1.23a3.5 3.5 0 0 1-1.23.789A4.7 4.7 0 0 1 7 11a1 1 0 0 0 0 2c.574 0 1.151.086 1.688.293c.459.176.882.441 1.23.789s.613.771.789 1.23c.207.537.293 1.114.293 1.688a1 1 0 0 0 2 0c0-.574.086-1.151.293-1.688c.176-.459.441-.882.789-1.23a3.5 3.5 0 0 1 1.23-.789A4.7 4.7 0 0 1 17 13a1 1 0 0 0 0-2a4.7 4.7 0 0 1-1.688-.293a3.5 3.5 0 0 1-1.23-.789a3.5 3.5 0 0 1-.789-1.23A4.7 4.7 0 0 1 13 7a1 1 0 0 0-1-1");
}

</style>
