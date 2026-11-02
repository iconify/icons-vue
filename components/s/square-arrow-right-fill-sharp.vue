<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4a97fb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-right-fill-sharp" /></template>
<style>
.e4a97fb5s {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m10.293-6.707a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414l-3-3a.999.999 0 1 0-1.414 1.414L13.586 11H8a1 1 0 0 0 0 2h5.586Z");
}

</style>
