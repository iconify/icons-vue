<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4zi-4u_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-horizontal-end-sharp-fill" /></template>
<style>
.v4zi-4u_c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM12.3333 9L17 9L17 7L12.3333 7L12.3333 9ZM7 13L17 13L17 11L7 11L7 13ZM9.6667 17L17 17L17 15L9.6667 15L9.6667 17Z");
}

</style>
