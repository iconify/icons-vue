<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw_mnk_0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-comfy-outline" /></template>
<style>
.vw_mnk_0a {
  fill: currentColor;
  d: path("M3 19V5h18v14zm17-7.5V6H4v5.5zM9.385 18H20v-5.5H9.385zM4 18h4.385v-5.5H4z");
}

</style>
