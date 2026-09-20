<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1isrostl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:waterfall-chart" /></template>
<style>
.g1isrostl {
  fill: currentColor;
  d: path("M3 20v-6h3v6zm5-6V9h3v5zm5-5V4h3v5zm5 11V4h3v16z");
}

</style>
