<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m_xwzru_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-column-top-bottom-20-filled" /></template>
<style>
.m_xwzru_e {
  fill: currentColor;
  d: path("M13 17h1.5a2.5 2.5 0 0 0 2.5-2.5V13h-4zm0-5V8h4v4zm-1 0H8V8h4zm-4 4h4v1H8zm-1-4V8H3v4zm-4 1h4v4H5.5A2.5 2.5 0 0 1 3 14.5zm10-6h4V5.5A2.5 2.5 0 0 0 14.5 3H13zM8 4h4V3H8zM7 3v4H3V5.5A2.5 2.5 0 0 1 5.5 3z");
}

</style>
