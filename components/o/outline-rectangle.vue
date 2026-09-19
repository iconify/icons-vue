<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5wnm1b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-rectangle" /></template>
<style>
.g5wnm1b8d {
  fill: currentColor;
  d: path("M2 4v16h20V4zm18 14H4V6h16z");
}

</style>
