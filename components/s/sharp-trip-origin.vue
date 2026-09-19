<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtv4ecbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-trip-origin" /></template>
<style>
.vtv4ecbhn {
  fill: currentColor;
  d: path("M2 12C2 6.48 6.48 2 12 2s10 4.48 10 10s-4.48 10-10 10S2 17.52 2 12m10 6c3.31 0 6-2.69 6-6s-2.69-6-6-6s-6 2.69-6 6s2.69 6 6 6");
}

</style>
