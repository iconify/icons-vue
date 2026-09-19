<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1t-4526n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-south-east" /></template>
<style>
.i1t-4526n {
  fill: currentColor;
  d: path("M19 9h-2v6.59L5.41 4L4 5.41L15.59 17H9v2h10z");
}

</style>
