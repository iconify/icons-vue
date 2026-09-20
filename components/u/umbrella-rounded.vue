<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj831_osj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:umbrella-rounded" /></template>
<style>
.nj831_osj {
  fill: currentColor;
  d: path("m13 14.8l1.95-5.95l-.9.225L13 8.3zm-2 0V8.3l-1.05.8l-.925-.25zm.438 7.038q-.263-.163-.388-.513L6.575 7.775q-.2-.575.2-.987T7.75 6.5l1.75.425l1.5-1.15V3.4q0-1 .725-1.7T13.5 1t1.775.7T16 3.4q0 .425-.288.713T15 4.4t-.712-.288T14 3.4q0-.2-.15-.337t-.35-.138t-.35.138T13 3.4v2.375l1.5 1.15l1.75-.425q.575-.125.975.288t.2.987L12.95 21.3q-.125.35-.387.525T12 22t-.562-.162");
}

</style>
