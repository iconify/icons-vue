<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="emwpxgbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:map-20-filled" /></template>
<style>
.emwpxgbop {
  fill: currentColor;
  d: path("m12 6.04l-4-2.8v10.72l4 2.8zm1 10.72l4.787-3.35A.5.5 0 0 0 18 13V3.5a.5.5 0 0 0-.787-.41L13 6.04zM2.213 6.59L7 3.24v10.72l-4.213 2.95A.5.5 0 0 1 2 16.5V7a.5.5 0 0 1 .213-.41");
}

</style>
