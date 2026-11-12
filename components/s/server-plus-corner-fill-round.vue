<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfv10zbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-plus-corner-fill-round" /></template>
<style>
.vfv10zbzf {
  fill: currentColor;
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M18 13v3h3a1 1 0 0 1 0 2h-3v3a1 1 0 0 1-2 0v-3h-3a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0m-9 8H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m-1.99-5H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
