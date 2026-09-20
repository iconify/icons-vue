<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axi7gs86e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-notes-24-filled" /></template>
<style>
.axi7gs86e {
  fill: currentColor;
  d: path("M20 2.75a.75.75 0 0 0-.965-.718l-10 3a.75.75 0 0 0-.535.718v9.877a3.5 3.5 0 1 0 1.496 2.702L10 18.25v-7.942l8.5-2.55v5.87a3.5 3.5 0 1 0 1.496 2.702l.004-.08z");
}

</style>
