<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj1p_xbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-exclude-24-filled" /></template>
<style>
.oj1p_xbyo {
  fill: currentColor;
  d: path("M5.25 2H9.5v7.5H2V5.25A3.25 3.25 0 0 1 5.25 2M2 11v4.25a3.25 3.25 0 0 0 3.25 3.25H9.5V11zm16.5-1.5V5.25A3.25 3.25 0 0 0 15.25 2H11v7.5zm-6 5.25a2.25 2.25 0 0 1 2.25-2.25h5A2.25 2.25 0 0 1 22 14.75v5A2.25 2.25 0 0 1 19.75 22h-5a2.25 2.25 0 0 1-2.25-2.25z");
}

</style>
