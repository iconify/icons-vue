<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o0lvz2bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sim-16-regular" /></template>
<style>
.o0lvz2bhc {
  fill: currentColor;
  d: path("M5 9.5A1.5 1.5 0 0 1 6.5 8h3A1.5 1.5 0 0 1 11 9.5v2A1.5 1.5 0 0 1 9.5 13h-3A1.5 1.5 0 0 1 5 11.5zM6.5 9a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H8V9zM9 9v3h.5a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-.5-.5zM3 3.5A2.5 2.5 0 0 1 5.5 1h3.172a2.5 2.5 0 0 1 1.767.732l1.829 1.829A2.5 2.5 0 0 1 13 5.328V12.5a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 3 12.5zM5.5 2A1.5 1.5 0 0 0 4 3.5v9A1.5 1.5 0 0 0 5.5 14h5a1.5 1.5 0 0 0 1.5-1.5V5.328a1.5 1.5 0 0 0-.44-1.06L9.733 2.439A1.5 1.5 0 0 0 8.672 2z");
}

</style>
