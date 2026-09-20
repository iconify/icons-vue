<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-saiebxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-column-two-left-24-filled" /></template>
<style>
.y-saiebxe {
  fill: currentColor;
  d: path("M21 6a1 1 0 0 0-1-1h-9a1 1 0 1 0 0 2h9a1 1 0 0 0 1-1M8 6a1 1 0 0 0-1-1H4a1 1 0 0 0 0 2h3a1 1 0 0 0 1-1m13 4a1 1 0 0 0-1-1h-9a1 1 0 1 0 0 2h9a1 1 0 0 0 1-1M8 10a1 1 0 0 0-1-1H4a1 1 0 0 0 0 2h3a1 1 0 0 0 1-1m13 4a1 1 0 0 0-1-1h-9a1 1 0 1 0 0 2h9a1 1 0 0 0 1-1M8 14a1 1 0 0 0-1-1H4a1 1 0 1 0 0 2h3a1 1 0 0 0 1-1m13 4a1 1 0 0 0-1-1h-9a1 1 0 1 0 0 2h9a1 1 0 0 0 1-1M8 18a1 1 0 0 0-1-1H4a1 1 0 1 0 0 2h3a1 1 0 0 0 1-1");
}

</style>
