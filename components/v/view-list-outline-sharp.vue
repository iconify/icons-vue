<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8trll-rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-list-outline-sharp" /></template>
<style>
.w8trll-rj {
  fill: currentColor;
  d: path("M8.5 18H20v-3.175H8.5zM4 9.175h3.5V6H4zm0 4.675h3.5v-3.675H4zM4 18h3.5v-3.175H4zm4.5-4.15H20v-3.675H8.5zm0-4.675H20V6H8.5zM3 19V5h18v14z");
}

</style>
