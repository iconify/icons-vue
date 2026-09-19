<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7o-514hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-playlist-add-check" /></template>
<style>
.e7o-514hm {
  fill: currentColor;
  d: path("M3 10h11v2H3zm0-4h11v2H3zm0 8h7v2H3zm17.59-2.07l-4.25 4.24l-2.12-2.12l-1.41 1.41L16.34 19L22 13.34z");
}

</style>
