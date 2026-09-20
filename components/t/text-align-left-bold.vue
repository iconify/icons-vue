<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x3ixo9b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-align-left-bold" /></template>
<style>
.x3ixo9b-v {
  fill: currentColor;
  d: path("M28 64a12 12 0 0 1 12-12h176a12 12 0 0 1 0 24H40a12 12 0 0 1-12-12m12 52h128a12 12 0 0 0 0-24H40a12 12 0 0 0 0 24m176 16H40a12 12 0 0 0 0 24h176a12 12 0 0 0 0-24m-48 40H40a12 12 0 0 0 0 24h128a12 12 0 0 0 0-24");
}

</style>
