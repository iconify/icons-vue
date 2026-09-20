<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="phykye34l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tv-usb-16-regular" /></template>
<style>
.phykye34l {
  fill: currentColor;
  d: path("M4 3a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h4.176A2 2 0 0 1 8 10.179V10H4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h9c.293 0 .572.063.823.177A2 2 0 0 0 12 3zm.5 9h4.344l.656.915V13h-5a.5.5 0 0 1 0-1M10 6v2a1 1 0 0 0-1 1v1.179a1 1 0 0 0 .187.582l1.313 1.833V14a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1v-1.406l1.309-1.8a1 1 0 0 0 .191-.588V9a1 1 0 0 0-1-1V6a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1m3 2h-2V6h2z");
}

</style>
