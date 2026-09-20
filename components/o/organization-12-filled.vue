<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pulkdxg0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:organization-12-filled" /></template>
<style>
.pulkdxg0q {
  fill: currentColor;
  d: path("M5.5 4.937a2 2 0 1 1 1 0V6h2a1 1 0 0 1 1 1v1.063a2 2 0 1 1-1 0V7h-5v1.063a2 2 0 1 1-1 0V7a1 1 0 0 1 1-1h2z");
}

</style>
