<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rph4n7f-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-column-top-bottom-16-regular" /></template>
<style>
.rph4n7f-n {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zM3 11h2v2h-.5A1.5 1.5 0 0 1 3 11.5zm7-1H6V6h4zM3 6h2v4H3zm1.5-3H5v2H3v-.5A1.5 1.5 0 0 1 4.5 3M11 6h2v4h-2zm0 5h2v.5a1.5 1.5 0 0 1-1.5 1.5H11zm2-6.5V5h-2V3h.5A1.5 1.5 0 0 1 13 4.5");
}

</style>
