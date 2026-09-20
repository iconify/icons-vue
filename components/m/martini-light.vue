<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cwd4_tb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:martini-light" /></template>
<style>
.cwd4_tb1f {
  fill: currentColor;
  d: path("M236.24 44.24A6 6 0 0 0 232 34H24a6 6 0 0 0-4.24 10.24L122 146.49V210H88a6 6 0 0 0 0 12h80a6 6 0 0 0 0-12h-34v-63.51ZM70.49 78h115L128 135.51Zm147-32l-20 20h-139l-20-20Z");
}

</style>
