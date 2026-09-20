<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw_bb3ntg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-24-regular" /></template>
<style>
.hw_bb3ntg {
  fill: currentColor;
  d: path("M3.754 12.5h16.492a.75.75 0 0 0 0-1.5H3.754a.75.75 0 0 0 0 1.5");
}

</style>
