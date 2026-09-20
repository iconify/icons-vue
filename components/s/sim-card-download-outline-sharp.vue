<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2jo7sntp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sim-card-download-outline-sharp" /></template>
<style>
.z2jo7sntp {
  fill: currentColor;
  d: path("m12 17l4-4l-1.4-1.4l-1.6 1.55V9h-2v4.15L9.4 11.6L8 13zm-8 5V8l6-6h10v20zm2-2h12V4h-7.15L6 8.85zm0 0h12z");
}

</style>
