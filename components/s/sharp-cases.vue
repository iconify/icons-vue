<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv609gbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-cases" /></template>
<style>
.xv609gbag {
  fill: currentColor;
  d: path("M18 5V1h-8v4H5v13h18V5zm-2 0h-4V3h4zM3 9H1v13h18v-2H3z");
}

</style>
