<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ef-sr-7js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:play-circle-20-regular" /></template>
<style>
.ef-sr-7js {
  fill: currentColor;
  d: path("M9.125 7.184A.75.75 0 0 0 8 7.834v4.333a.75.75 0 0 0 1.125.65l4.125-2.384a.5.5 0 0 0 0-.866zM2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8-7a7 7 0 1 0 0 14a7 7 0 0 0 0-14");
}

</style>
