<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iorohegil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:virtual-network-16-regular" /></template>
<style>
.iorohegil {
  fill: currentColor;
  d: path("M3.117 4.68a.5.5 0 0 1 .767.64L1.651 8l2.233 2.68a.5.5 0 0 1-.767.64l-2.5-3a.5.5 0 0 1 0-.64zm9.063-.064a.5.5 0 0 1 .704.064l2.5 3a.5.5 0 0 1 0 .64l-2.5 3a.5.5 0 0 1-.767-.64L14.35 8l-2.233-2.68a.5.5 0 0 1 .063-.704M11.125 7.13a.875.875 0 1 1 0 1.75a.875.875 0 0 1 0-1.75m-6.25-.005a.875.875 0 1 1 0 1.75a.875.875 0 0 1 0-1.75m3.125 0a.875.875 0 1 1 0 1.75a.875.875 0 0 1 0-1.75");
}

</style>
