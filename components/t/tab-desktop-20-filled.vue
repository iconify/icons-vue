<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xdrzzu7pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-20-filled" /></template>
<style>
.xdrzzu7pe {
  fill: currentColor;
  d: path("M5.497 3a2.5 2.5 0 0 0-2.5 2.5v9a2.5 2.5 0 0 0 2.5 2.5h9a2.5 2.5 0 0 0 2.5-2.5V7h-7.5a1.5 1.5 0 0 1-1.5-1.5V3zm3.5 0v2.5a.5.5 0 0 0 .5.5h7.5v-.5a2.5 2.5 0 0 0-2.5-2.5z");
}

</style>
