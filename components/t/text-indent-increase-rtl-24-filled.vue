<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l20dm4p0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-rtl-24-filled" /></template>
<style>
.l20dm4p0u {
  fill: currentColor;
  d: path("M15 8H6.5a1 1 0 0 1-.117-1.993L6.5 6H15a1 1 0 0 1 .117 1.993zH6.5zm6.707 6.707a1 1 0 0 1-1.32.083l-.094-.083l-2-2a1 1 0 0 1-.083-1.32l.083-.094l2-2a1 1 0 0 1 1.497 1.32l-.083.094L20.414 12l1.293 1.293a1 1 0 0 1 0 1.414M15 13l-11.5.001a1 1 0 0 1-.117-1.993L3.5 11H15a1 1 0 0 1 .117 1.993zl-11.5.001zm0 5H6.5a1 1 0 0 1-.117-1.993L6.5 16H15a1 1 0 0 1 .117 1.993zH6.5z");
}

</style>
