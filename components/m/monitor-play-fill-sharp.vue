<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w84mifbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-fill-sharp" /></template>
<style>
.w84mifbup {
  fill: currentColor;
  d: path("M3 17V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1m12.573-7.319l-5-3.5A1 1 0 0 0 9 7v7a.999.999 0 0 0 1.573.819l5-3.5a1 1 0 0 0 0-1.638M9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
