<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v123zgddh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-timeline-outline-sharp" /></template>
<style>
.v123zgddh {
  fill: currentColor;
  d: path("M6.539 16.5h4.923v-1H6.539zm6-8h4.923v-1h-4.923zm-3 4h4.923v-1H9.539zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
