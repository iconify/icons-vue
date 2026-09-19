<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0kgf0aje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-video-stable" /></template>
<style>
.a0kgf0aje {
  fill: currentColor;
  d: path("M2 4v16h20V4zm2 14V6h2.95l-2.33 8.73L16.82 18zm16 0h-2.95l2.34-8.73L7.18 6H20z");
}

</style>
