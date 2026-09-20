<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcyp6b-hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-horizontal-24-filled" /></template>
<style>
.qcyp6b-hm {
  fill: currentColor;
  d: path("M21.25 12.5a.75.75 0 0 0 0-1.5H2.75a.75.75 0 0 0 0 1.5zM17.75 2A2.25 2.25 0 0 1 20 4.25V10H4V4.25A2.25 2.25 0 0 1 6.25 2zM4 19.25V13.5h16v5.75a2.25 2.25 0 0 1-2.25 2.25H6.25A2.25 2.25 0 0 1 4 19.25");
}

</style>
