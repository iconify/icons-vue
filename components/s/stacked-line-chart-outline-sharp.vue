<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw0amo67q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stacked-line-chart-outline-sharp" /></template>
<style>
.zw0amo67q {
  fill: currentColor;
  d: path("M3.5 21.5L2 20l7.5-7.5l4 4l7.1-8L22 9.9l-8.5 9.6l-4-4zm0-6L2 14l7.5-7.5l4 4l7.1-8L22 3.9l-8.5 9.6l-4-4z");
}

</style>
