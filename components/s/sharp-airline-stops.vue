<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx4a8mbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-airline-stops" /></template>
<style>
.hx4a8mbnx {
  fill: currentColor;
  d: path("M18.21 9.21C15.93 10.78 13.45 13.3 13 17h2v2H9v-2h2c-.5-4.5-4.37-8-9-8V7c4.39 0 8.22 2.55 10 6.3c1.13-2.43 2.99-4.25 4.78-5.52L14 5h7v7z");
}

</style>
