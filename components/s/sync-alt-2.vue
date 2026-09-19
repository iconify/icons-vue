<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="odvfbumrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sync-alt-2" /></template>
<style>
.odvfbumrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.822 22.466l-12.9-16.599a.95.95 0 0 0-1.502 0L13.327 24H6.93a.95.95 0 0 0-.75 1.534l12.9 16.599a.95.95 0 0 0 1.501 0L34.673 24h6.398a.95.95 0 0 0 .75-1.534");
}

</style>
