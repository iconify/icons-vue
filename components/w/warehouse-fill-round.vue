<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-p9daceg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-fill-round" /></template>
<style>
.s-p9daceg {
  fill: currentColor;
  d: path("M17 21.901V14a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3v7.901A5.01 5.01 0 0 1 3 17v-6.528A5 5 0 0 1 5.764 6l2.944-1.472c.694-.35 1.46-.53 2.236-.528h2.112a4.94 4.94 0 0 1 2.236.528L18.236 6A5 5 0 0 1 21 10.472V17a5.01 5.01 0 0 1-4 4.901M9 16v-2a.997.997 0 0 1 1-1h4a.997.997 0 0 1 1 1v2Zm0 6v-4h6v4Z");
}

</style>
