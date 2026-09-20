<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9cq3uj1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scales-24-regular" /></template>
<style>
.i9cq3uj1t {
  fill: currentColor;
  d: path("M3 3.75A.75.75 0 0 1 3.75 3h16.5a.75.75 0 0 1 0 1.5h-1.042l2.737 6.717A.8.8 0 0 1 22 11.5a3.5 3.5 0 1 1-7 0a.8.8 0 0 1 .055-.283L17.792 4.5H12.75v12h4a2.25 2.25 0 0 1 0 4.5H7.253a2.25 2.25 0 0 1 0-4.5h3.997v-12H6.208l2.737 6.717A.8.8 0 0 1 9 11.5a3.5 3.5 0 1 1-7 0a.8.8 0 0 1 .055-.283L4.792 4.5H3.75A.75.75 0 0 1 3 3.75m3.503 15c0 .414.336.75.75.75h9.497a.75.75 0 0 0 0-1.5H7.253a.75.75 0 0 0-.75.75m.852-6.5h-3.71a2 2 0 0 0 3.71 0m-.22-1.5L5.5 6.738L3.865 10.75zM18.5 13.5a2 2 0 0 0 1.855-1.25h-3.71A2 2 0 0 0 18.5 13.5m-1.635-2.75h3.27L18.5 6.738z");
}

</style>
