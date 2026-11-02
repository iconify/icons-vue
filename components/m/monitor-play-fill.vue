<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6hcd7b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-fill" /></template>
<style>
.n6hcd7b0a {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm6 1v6a.998.998 0 0 0 1.6.8l4-3a1 1 0 0 0 0-1.6l-4-3A.999.999 0 0 0 9 7m0 12h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
