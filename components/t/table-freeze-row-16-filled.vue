<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fojhoumux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-row-16-filled" /></template>
<style>
.fojhoumux {
  fill: currentColor;
  d: path("M11.5 3A1.5 1.5 0 0 1 13 4.5V6h-2v4h3V4.5A2.5 2.5 0 0 0 11.5 2h-7A2.5 2.5 0 0 0 2 4.5V10h3V6H3V4.5A1.5 1.5 0 0 1 4.5 3zM10 6H6v4h4zm-5 5H2v.5A2.5 2.5 0 0 0 4.5 14H5zm1 3h4v-3H6zm5.5 0H11v-3h3v.5a2.5 2.5 0 0 1-2.5 2.5");
}

</style>
