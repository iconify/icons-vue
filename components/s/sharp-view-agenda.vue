<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn-vzhbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-agenda" /></template>
<style>
.mn-vzhbwb {
  fill: currentColor;
  d: path("M3 13h18v8H3zM3 3h18v8H3z");
}

</style>
