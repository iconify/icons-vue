<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qfl8xxbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-horizontal-20-regular" /></template>
<style>
.qfl8xxbte {
  fill: currentColor;
  d: path("M17.5 10a.5.5 0 0 0 0-1h-15a.5.5 0 0 0 0 1zM16 4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v4h1V4a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v4h1zm0 7h-1v4a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-4H4v4a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2z");
}

</style>
