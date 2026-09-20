<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdmau8b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-rows-narrow-outline-sharp" /></template>
<style>
.bdmau8b_r {
  fill: currentColor;
  d: path("M5 15.25h14V12.5H5zm0-3.75h14V8.75H5zm0-3.75h14V5H5zM4 20V4h16v16zm1-1h14v-2.75H5z");
}

</style>
