<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6z77xbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-arrow-back-ios-new" /></template>
<style>
.i6z77xbiz {
  fill: currentColor;
  d: path("M17.77 3.77L16 2L6 12l10 10l1.77-1.77L9.54 12z");
}

</style>
