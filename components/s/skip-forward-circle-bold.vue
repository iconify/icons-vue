<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vukub5t_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:skip-forward-circle-bold" /></template>
<style>
.vukub5t_w {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m32-136a12 12 0 0 0-12 12v18.35l-45.64-28.53A12 12 0 0 0 84 88v80a12 12 0 0 0 18.36 10.18L148 149.65V168a12 12 0 0 0 24 0V88a12 12 0 0 0-12-12m-52 70.35v-36.7L137.36 128Z");
}

</style>
