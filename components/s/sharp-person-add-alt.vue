<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iosgi2b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-person-add-alt" /></template>
<style>
.iosgi2b8t {
  fill: currentColor;
  d: path("M15.39 14.56C13.71 13.7 11.53 13 9 13s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 1 17.22V20h16v-2.78c0-1.12-.61-2.15-1.61-2.66M9 12c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m11-3V6h-2v3h-3v2h3v3h2v-3h3V9z");
}

</style>
