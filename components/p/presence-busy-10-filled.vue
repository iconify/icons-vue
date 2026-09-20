<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="crb63ug3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-busy-10-filled" /></template>
<style>
.crb63ug3l {
  fill: currentColor;
  d: path("M10 5A5 5 0 1 1 0 5a5 5 0 0 1 10 0");
}

</style>
