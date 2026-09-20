<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vep-8_bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:play-circle-16-filled" /></template>
<style>
.vep-8_bel {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m-.872 4.602A.75.75 0 0 0 6 6.249v3.502a.75.75 0 0 0 1.128.647l3-1.75a.75.75 0 0 0 0-1.295z");
}

</style>
