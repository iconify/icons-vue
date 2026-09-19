<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epz5hiyxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mobile-off" /></template>
<style>
.epz5hiyxo {
  fill: currentColor;
  d: path("M17 5v8.61l2 2V1H5v.61L8.39 5zM2.9 2.35L1.49 3.76L5 7.27V23h14v-1.73l1.7 1.7l1.41-1.41zM7 19V9.27L16.73 19z");
}

</style>
