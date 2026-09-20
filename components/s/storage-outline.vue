<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tza20vb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:storage-outline" /></template>
<style>
.tza20vb4d {
  fill: currentColor;
  d: path("M3 20v-4h18v4zm2-1h2v-2H5zM3 8V4h18v4zm2-1h2V5H5zm-2 7v-4h18v4zm2-1h2v-2H5z");
}

</style>
