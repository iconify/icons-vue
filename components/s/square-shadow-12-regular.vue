<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ogjvj5jcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-shadow-12-regular" /></template>
<style>
.ogjvj5jcg {
  fill: currentColor;
  d: path("M3 1a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2a2 2 0 0 0 2 2h3.5A2.5 2.5 0 0 0 11 8.5V5a2 2 0 0 0-2-2a2 2 0 0 0-2-2zm5 2v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1");
}

</style>
