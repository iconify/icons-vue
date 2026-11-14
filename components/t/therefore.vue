<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6j0kqbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:therefore" /></template>
<style>
.h6j0kqbbf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 6.5q0-2 2-2t2 2t-2 2t-2-2M6 15q-2 0-2 2t2 2t2-2t-2-2m10 2q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
