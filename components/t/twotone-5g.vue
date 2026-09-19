<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg9fmg_ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-5g" /></template>
<style>
.eg9fmg_ji {
  fill: currentColor;
  d: path("M16.5 13H19v2h-5V9h7c0-1.1-.9-2-2-2h-5c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h5c1.1 0 2-.9 2-2v-4h-4.5zM3 13h5v2H3v2h5c1.1 0 2-.9 2-2v-2c0-1.1-.9-2-2-2H5V9h5V7H3z");
}

</style>
