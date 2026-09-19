<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vlxt6s7_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swa-mobil" /></template>
<style>
.vlxt6s7_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.933 4.5c-1.254 1.878-2.927 4.13-4.6 6.72c-1.671 2.59-3.344 5.52-4.598 8.757s-2.09 6.778-2.09 10.593m-.047 2.416c.127 7.263 6.162 10.633 13.425 10.51c7.263.123 13.252-3.247 13.379-10.51m0-2.416c0-3.815-.836-7.357-2.09-10.593s-2.927-6.166-4.6-8.757s-3.344-4.841-4.598-6.72");
}

</style>
