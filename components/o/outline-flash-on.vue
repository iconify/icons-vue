<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erkqwpm1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-flash-on" /></template>
<style>
.erkqwpm1w {
  fill: currentColor;
  d: path("M7 2v11h3v9l7-12h-4l3-8z");
}

</style>
