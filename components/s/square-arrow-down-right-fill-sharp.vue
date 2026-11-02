<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-_echbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-right-fill-sharp" /></template>
<style>
.i-_echbfk {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m9-5h4a1 1 0 0 0 1-1v-4a1 1 0 0 0-2 0v1.586L9.707 8.293a.999.999 0 1 0-1.414 1.414L12.586 14H11a1 1 0 0 0 0 2");
}

</style>
