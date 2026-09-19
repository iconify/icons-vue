<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2jd_9btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-incomplete-circle" /></template>
<style>
.y2jd_9btn {
  fill: currentColor;
  d: path("M22 12c0 5.52-4.48 10-10 10S2 17.52 2 12c0-2.76 1.12-5.26 2.93-7.07L12 12V2c5.52 0 10 4.48 10 10");
}

</style>
