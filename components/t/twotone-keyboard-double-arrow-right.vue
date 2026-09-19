<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix24v_o1u"/><path class="xm9bz0bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-keyboard-double-arrow-right" /></template>
<style>
.ix24v_o1u {
  fill: currentColor;
  d: path("M6.41 6L5 7.41L9.58 12L5 16.59L6.41 18l6-6z");
}

.xm9bz0bfz {
  fill: currentColor;
  d: path("m13 6l-1.41 1.41L16.17 12l-4.58 4.59L13 18l6-6z");
}

</style>
