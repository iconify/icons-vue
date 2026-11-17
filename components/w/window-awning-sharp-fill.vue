<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6nk0lrxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-sharp-fill" /></template>
<style>
.l6nk0lrxt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 2C20.552 2 21 2.448 21 3V20H23V22H1V20H3V3C3 2.448 3.448 2 4 2H20ZM5 8V10H11V14H5V16H11V20H13V16H19V14H13V10H19V8H5Z");
}

</style>
