<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5a0s0xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-vertical-bulk" /></template>
<style>
.hm5a0s0xs {
  fill: currentColor;
  d: path("M10.158 5.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m0 6a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m0 6a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
