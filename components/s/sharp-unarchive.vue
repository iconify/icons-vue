<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkta2db5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-unarchive" /></template>
<style>
.rkta2db5x {
  fill: currentColor;
  d: path("M18.71 3H5.29L3 5.79V21h18V5.79zM14 15v2h-4v-2H6.5L12 9.5l5.5 5.5zM5.12 5l.81-1h12l.94 1z");
}

</style>
