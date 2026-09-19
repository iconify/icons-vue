<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjoljvb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-money" /></template>
<style>
.kjoljvb2a {
  fill: currentColor;
  d: path("M14 16h5V8h-5zm2-6h1v4h-1zm-8 6h5V8H8zm2-6h1v4h-1zM5 8h2v8H5zM2 4v16h20V4zm18 14H4V6h16z");
}

</style>
