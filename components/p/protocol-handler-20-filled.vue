<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rvdpupbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:protocol-handler-20-filled" /></template>
<style>
.rvdpupbfb {
  fill: currentColor;
  d: path("M5.585 5.414L2.414 8.585a2 2 0 0 0 0 2.829l3.171 3.172a2 2 0 0 0 2.829 0l3.172-3.172a2 2 0 0 0 0-2.829L8.414 5.414a2 2 0 0 0-2.829 0m6 9.172l-.878-.88l1.586-1.585a3 3 0 0 0 0-4.243l-1.586-1.585l.878-.88a2 2 0 0 1 2.829 0l3.172 3.172a2 2 0 0 1 0 2.829l-3.172 3.172a2 2 0 0 1-2.828 0");
}

</style>
