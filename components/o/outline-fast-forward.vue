<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtidhiwom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-fast-forward" /></template>
<style>
.wtidhiwom {
  fill: currentColor;
  d: path("M15 9.86L18.03 12L15 14.14zm-9 0L9.03 12L6 14.14zM13 6v12l8.5-6zM4 6v12l8.5-6z");
}

</style>
