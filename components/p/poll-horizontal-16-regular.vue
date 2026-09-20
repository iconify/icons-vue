<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvuttbbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-horizontal-16-regular" /></template>
<style>
.fvuttbbhd {
  fill: currentColor;
  d: path("M15 8a2 2 0 0 0-2-2H3a2 2 0 1 0 0 4h10a2 2 0 0 0 2-2m-2 1H3a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2M9 3a2 2 0 0 0-2-2H3a2 2 0 1 0 0 4h4a2 2 0 0 0 2-2M3 4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2zm6 7a2 2 0 1 1 0 4H3a2 2 0 1 1 0-4zm0 3a1 1 0 1 0 0-2H3a1 1 0 1 0 0 2z");
}

</style>
