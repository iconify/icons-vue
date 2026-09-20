<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz3pm8b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-t-24-filled" /></template>
<style>
.yz3pm8b9m {
  fill: currentColor;
  d: path("M4.75 5a1 1 0 0 1 1-1h12.5a1 1 0 0 1 1 1v2a1 1 0 1 1-2 0V6H13v12h1a1 1 0 1 1 0 2h-4a1 1 0 1 1 0-2h1V6H6.75v1a1 1 0 0 1-2 0z");
}

</style>
