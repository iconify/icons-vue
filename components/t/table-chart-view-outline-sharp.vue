<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5sn8gnxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-chart-view-outline-sharp" /></template>
<style>
.i5sn8gnxj {
  fill: currentColor;
  d: path("M7.4 22L6 20.6l6.9-6.925l3.5 3.5L21.575 12L23 13.425L16.4 20l-3.5-3.5zM4 21H2V3h18v7H4zM4 8h14V5H4zm0 0V5z");
}

</style>
