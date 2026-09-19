<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="od2kd3bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:small-blue-diamond" /></template>
<style>
.od2kd3bdj {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M32.507 56.655L8.136 32.667L32.507 8.678l24.366 23.989z");
}

</style>
