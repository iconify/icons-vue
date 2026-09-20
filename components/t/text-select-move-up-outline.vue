<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhwek4lcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-select-move-up-outline" /></template>
<style>
.jhwek4lcy {
  fill: currentColor;
  d: path("M4 20v-1h16v1zm7.5-3.5V9.633l-2.1 2.075L8.692 11L12 7.692L15.308 11l-.708.708l-2.1-2.075V16.5zM4 5V4h16v1z");
}

</style>
