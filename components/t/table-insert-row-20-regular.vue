<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dfbwnkxey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-row-20-regular" /></template>
<style>
.dfbwnkxey {
  fill: currentColor;
  d: path("M3.5 16a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zm0-13a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zM3 11a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V9a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2zm9 1H8V8h4zM5 8h2v4H5a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1m8 4V8h2a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1z");
}

</style>
