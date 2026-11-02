<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li52xsbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-close-fill-sharp" /></template>
<style>
.li52xsbqi {
  fill: currentColor;
  d: path("M4 2h16a1 1 0 0 1 1 1v7c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V3a1 1 0 0 1 1-1m6.707 6.293a.999.999 0 1 0-1.414 1.414L10.586 11l-1.293 1.293a.999.999 0 1 0 1.414 1.414L12 12.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L13.414 11l1.293-1.293a.999.999 0 1 0-1.414-1.414L12 9.586Z");
}

</style>
