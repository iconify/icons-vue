<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9z8knspd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-arrow-clockwise-24-filled" /></template>
<style>
.x9z8knspd {
  fill: currentColor;
  d: path("M5.75 3A2.75 2.75 0 0 0 3 5.75v5.351A6.98 6.98 0 0 1 8 9c.983 0 1.92.203 2.768.569A1.749 1.749 0 0 1 14 10.5v1.892A6.97 6.97 0 0 1 15 16a6.98 6.98 0 0 1-2.101 5h5.351A2.75 2.75 0 0 0 21 18.25V8h-7.75A2.25 2.25 0 0 1 11 5.75V3zm6.75 0v2.75c0 .414.336.75.75.75H21v-.75A2.75 2.75 0 0 0 18.25 3zm.5 10.25a.75.75 0 0 1-.75.75H9.5a.75.75 0 0 1 0-1.5h1.33l-.018-.013A4.5 4.5 0 1 0 12.5 16a.75.75 0 0 1 1.5 0a6 6 0 1 1-2.5-4.874V10.5a.747.747 0 0 1 .75-.75a.75.75 0 0 1 .75.75z");
}

</style>
