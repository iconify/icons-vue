<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmed4ibmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-horizontal-24-regular" /></template>
<style>
.fmed4ibmb {
  fill: currentColor;
  d: path("M7.75 12a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0m6 0a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0M18 13.75a1.75 1.75 0 1 0 0-3.5a1.75 1.75 0 0 0 0 3.5");
}

</style>
