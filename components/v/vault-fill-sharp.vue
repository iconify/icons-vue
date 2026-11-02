<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcf9p5r5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vault-fill-sharp" /></template>
<style>
.dcf9p5r5o {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-3v1a1 1 0 0 1-2 0v-1H8v1a1 1 0 0 1-2 0v-1H3a1 1 0 0 1-1-1Zm5 8a5 5 0 1 0 10.001-.001A5 5 0 0 0 7 11m7.765-1.167a3.002 3.002 0 0 1-5.529 2.334a3.001 3.001 0 0 1 5.529-2.334M12.01 10H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
