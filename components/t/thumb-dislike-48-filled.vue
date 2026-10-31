<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l8_5s_bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-dislike-48-filled" /></template>
<style>
.l8_5s_bqa {
  fill: currentColor;
  d: path("M24.285 4.403c6.333-1.733 12.798 2.304 14.022 8.755l1.563 8.241c.846 4.466-2.578 8.6-7.124 8.6h-2.455c.085.42.18.905.274 1.427c.294 1.634.605 3.722.605 5.292c0 2.999-1.03 4.99-2.14 6.239a7.2 7.2 0 0 1-1.52 1.3a6 6 0 0 1-.53.3c-.14.07-.281.125-.425.185c-1.985.822-4.137-.452-4.628-2.4c-1.114-4.421-4.353-13.315-12.816-17.715c-2.625-1.365-4.596-4.246-4.012-7.435l.746-4.072a6.25 6.25 0 0 1 4.497-4.901z");
}

</style>
