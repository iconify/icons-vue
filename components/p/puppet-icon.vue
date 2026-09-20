<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":395};
const content = `<path class="ublzfsbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:puppet-icon" /></template>
<style>
.ublzfsbbn {
  fill: var(--svg-color--ffae1a, #ffae1a);
  d: path("M256 256V138.204h-90.155l-48.049-48.307V0H0v117.796h90.155l48.307 48.307v62.256l-48.307 48.307H0v117.796h117.796v-89.897l48.307-48.307H256zM39.265 39.265h39.266v39.266H39.265zm39.266 315.673H39.265v-39.265h39.266z");
}

</style>
