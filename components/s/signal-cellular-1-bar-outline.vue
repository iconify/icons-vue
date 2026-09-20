<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omf6sab1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-1-bar-outline" /></template>
<style>
.omf6sab1k {
  fill: currentColor;
  d: path("M3 21L21 3v18zm6.289-1H20V5.427L9.289 16.139z");
}

</style>
