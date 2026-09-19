<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7iflkqua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-text-rotation-down" /></template>
<style>
.p7iflkqua {
  fill: currentColor;
  d: path("m6 20l3-3H7V4H5v13H3zm6.2-11.5v5l-2.2.9v2.1l11-4.75v-1.5L10 5.5v2.1zm6.82 2.5L14 12.87V9.13z");
}

</style>
