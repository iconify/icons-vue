<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f9l7v_m2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:upload-thin" /></template>
<style>
.f9l7v_m2o {
  fill: currentColor;
  d: path("M236 136v64a12 12 0 0 1-12 12H32a12 12 0 0 1-12-12v-64a12 12 0 0 1 12-12h48a4 4 0 0 1 0 8H32a4 4 0 0 0-4 4v64a4 4 0 0 0 4 4h192a4 4 0 0 0 4-4v-64a4 4 0 0 0-4-4h-48a4 4 0 0 1 0-8h48a12 12 0 0 1 12 12M82.83 74.83L124 33.66V128a4 4 0 0 0 8 0V33.66l41.17 41.17a4 4 0 1 0 5.66-5.66l-48-48a4 4 0 0 0-5.66 0l-48 48a4 4 0 0 0 5.66 5.66M196 168a8 8 0 1 0-8 8a8 8 0 0 0 8-8");
}

</style>
