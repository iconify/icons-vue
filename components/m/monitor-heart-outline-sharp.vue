<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdivbcu1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor-heart-outline-sharp" /></template>
<style>
.bdivbcu1b {
  fill: currentColor;
  d: path("M3 9.5V5h18v4.5h-1V6H4v3.5zM3 19v-4.5h1V18h16v-3.5h1V19zm4.683-6.5l1.911 3.804h.812L14 9.134l1.683 3.366H21v-1h-4.683l-1.911-3.804h-.812L10 14.866L8.317 11.5H3v1zM12 12");
}

</style>
