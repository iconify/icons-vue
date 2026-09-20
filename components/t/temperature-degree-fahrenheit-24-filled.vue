<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c95xm6bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-fahrenheit-24-filled" /></template>
<style>
.c95xm6bsw {
  fill: currentColor;
  d: path("M5 8.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0M6.5 5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7M13 5a1 1 0 0 0-1 1v12a1 1 0 1 0 2 0v-5h5.5a1 1 0 1 0 0-2H14V7h6a1 1 0 1 0 0-2z");
}

</style>
