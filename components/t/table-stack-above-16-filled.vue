<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x8yodpbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-above-16-filled" /></template>
<style>
.x8yodpbdv {
  fill: currentColor;
  d: path("M2.5 2a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1zM11 6h2.5a.5.5 0 0 1 .5.5V10h-3zm-1 0H6v4h4zm-8 4V6.5a.5.5 0 0 1 .5-.5H5v4zm3 1H2v.5A2.5 2.5 0 0 0 4.5 14H5zm1 3h4v-3H6zm5.5 0H11v-3h3v.5a2.5 2.5 0 0 1-2.5 2.5");
}

</style>
