<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ef5q8_bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-16-filled" /></template>
<style>
.ef5q8_bsg {
  d: path("M4 6.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5zm4 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5zm4 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
