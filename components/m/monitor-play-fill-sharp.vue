<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccaj-tukm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-fill-sharp" /></template>
<style>
.ccaj-tukm {
  fill: currentColor;
  d: path("M3 17V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1M9 7v6a.998.998 0 0 0 1.6.8l4-3a1 1 0 0 0 0-1.6l-4-3A.999.999 0 0 0 9 7m0 12h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
