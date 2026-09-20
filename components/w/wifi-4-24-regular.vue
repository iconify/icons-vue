<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt0hg4bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wifi-4-24-regular" /></template>
<style>
.rt0hg4bmb {
  fill: currentColor;
  d: path("M10.94 18.561a1.5 1.5 0 1 0 2.121-2.122a1.5 1.5 0 0 0-2.122 2.122");
}

</style>
