<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc-844boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-high-quality" /></template>
<style>
.zc-844boc {
  fill: currentColor;
  d: path("M21 4H3v16h18zM11 15H9.5v-2h-2v2H6V9h1.5v2.5h2V9H11zm7 0h-1.75v1.5h-1.5V15H13V9h5zm-3.5-1.5h2v-3h-2z");
}

</style>
