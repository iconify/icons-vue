<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uyk2s0b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sign-in-thin" /></template>
<style>
.uyk2s0b6f {
  fill: currentColor;
  d: path("m138.83 130.83l-40 40a4 4 0 0 1-5.66-5.66L126.34 132H24a4 4 0 0 1 0-8h102.34L93.17 90.83a4 4 0 0 1 5.66-5.66l40 40a4 4 0 0 1 0 5.66M200 36h-64a4 4 0 0 0 0 8h60v168h-60a4 4 0 0 0 0 8h64a4 4 0 0 0 4-4V40a4 4 0 0 0-4-4");
}

</style>
