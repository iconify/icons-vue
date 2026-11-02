<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf5g16b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-fill-round" /></template>
<style>
.vf5g16b_w {
  fill: currentColor;
  d: path("M16 2a5 5 0 0 1 5 5v3c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V7a5 5 0 0 1 5-5Z");
}

</style>
