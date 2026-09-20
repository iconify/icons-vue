<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v319xsbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:umbrella-bold" /></template>
<style>
.v319xsbys {
  fill: currentColor;
  d: path("M243.93 126.3A116.43 116.43 0 0 0 49 50.81a115.45 115.45 0 0 0-37 75.49A20 20 0 0 0 32 148h84v52a36 36 0 0 0 72 0a12 12 0 0 0-24 0a12 12 0 0 1-24 0v-52h84a20 20 0 0 0 20-21.7ZM100.41 124c2.67-39.33 18.08-63.51 27.59-74.87c9.52 11.39 24.92 35.56 27.59 74.87Zm-35.1-55.54A92 92 0 0 1 99 48.65C88.8 65.25 78.39 90.08 76.36 124H36.44a91.56 91.56 0 0 1 28.87-55.54M179.64 124c-2-33.92-12.44-58.75-22.65-75.35A92.19 92.19 0 0 1 219.56 124Z");
}

</style>
