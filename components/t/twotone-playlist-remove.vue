<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osmxkx6qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-playlist-remove" /></template>
<style>
.osmxkx6qh {
  fill: currentColor;
  d: path("M14 10H3v2h11zm0-4H3v2h11zM3 16h7v-2H3zm11.41 6L17 19.41L19.59 22L21 20.59L18.41 18L21 15.41L19.59 14L17 16.59L14.41 14L13 15.41L15.59 18L13 20.59z");
}

</style>
