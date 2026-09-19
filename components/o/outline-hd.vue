<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeqy9ac1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-hd" /></template>
<style>
.jeqy9ac1d {
  fill: currentColor;
  d: path("M19 3H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14zM7.5 13h2v2H11V9H9.5v2.5h-2V9H6v6h1.5zM18 14v-4c0-.55-.45-1-1-1h-4v6h4c.55 0 1-.45 1-1m-1.5-.5h-2v-3h2z");
}

</style>
