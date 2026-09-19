<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1c1fvm9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-format-size" /></template>
<style>
.e1c1fvm9g {
  fill: currentColor;
  d: path("M3 12h3v7h3v-7h3V9H3zm6-5h5v12h3V7h5V4H9z");
}

</style>
