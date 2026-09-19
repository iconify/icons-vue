<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpwzc7off"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-add-to-home-screen" /></template>
<style>
.wpwzc7off {
  fill: currentColor;
  d: path("M20 1.01L6 1v5h2V5h10v14H8v-1H6v5h14zM10 15h2V8H5v2h3.59L3 15.59L4.41 17L10 11.41z");
}

</style>
