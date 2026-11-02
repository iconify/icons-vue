<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk3m9y--z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-fill" /></template>
<style>
.fk3m9y--z {
  fill: currentColor;
  d: path("M10 15v4a3 3 0 1 1-6 0v-4.171A3 3 0 0 1 2 12v-2a3 3 0 0 1 3-3h5.764l7.789-3.894c.356-.181.75-.274 1.149-.273C20.924 2.836 22 3.735 22 5v12c0 1.265-1.076 2.164-2.298 2.167a2.5 2.5 0 0 1-1.149-.273L10.764 15Zm0-2V9H5a.997.997 0 0 0-1 1v2a.997.997 0 0 0 1 1Zm-4 6a1 1 0 0 0 2 0v-4H6Z");
}

</style>
