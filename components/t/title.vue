<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqz0xrkdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:title" /></template>
<style>
.tqz0xrkdc {
  fill: currentColor;
  d: path("M10.5 20V7H5V4h14v3h-5.5v13z");
}

</style>
