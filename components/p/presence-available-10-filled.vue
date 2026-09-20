<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="t80um-b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-available-10-filled" /></template>
<style>
.t80um-b-c {
  fill: currentColor;
  d: path("M5 10A5 5 0 1 0 5 0a5 5 0 0 0 0 10m2.104-5.896l-2.25 2.25a.5.5 0 0 1-.708 0l-1-1a.5.5 0 0 1 .708-.708l.646.647l1.896-1.897a.5.5 0 0 1 .708.708");
}

</style>
