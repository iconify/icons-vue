<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="afz9bc0dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pair-16-regular" /></template>
<style>
.afz9bc0dw {
  fill: currentColor;
  d: path("M9.5 1.25a1.25 1.25 0 0 1 .5 2.395V6h2.355A1.249 1.249 0 1 1 14 7.645v4.71A1.25 1.25 0 1 1 12.355 14h-4.71A1.249 1.249 0 1 1 6 12.354V10H3.645A1.249 1.249 0 1 1 2 8.354v-4.71A1.249 1.249 0 1 1 3.645 2h4.71A1.25 1.25 0 0 1 9.5 1.25m.5 7.104A1.25 1.25 0 1 1 8.355 10H7v2.355c.288.125.519.357.645.645h4.71a1.26 1.26 0 0 1 .645-.646v-4.71A1.25 1.25 0 0 1 12.355 7H10zM3.645 3A1.25 1.25 0 0 1 3 3.645v4.71c.288.125.519.357.645.645H6V7.645A1.249 1.249 0 1 1 7.645 6H9V3.645A1.25 1.25 0 0 1 8.355 3zm4 4A1.25 1.25 0 0 1 7 7.645V9h1.355c.126-.288.357-.52.645-.646V7z");
}

</style>
