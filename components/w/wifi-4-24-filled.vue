<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u760py7xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wifi-4-24-filled" /></template>
<style>
.u760py7xa {
  fill: currentColor;
  d: path("M10.96 18.567a1.501 1.501 0 1 0 2.122-2.122a1.501 1.501 0 0 0-2.123 2.122");
}

</style>
