<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryt9rccao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-left-rotate-270-24-regular" /></template>
<style>
.ryt9rccao {
  fill: currentColor;
  d: path("M5.75 22a.75.75 0 0 1-.75-.75V5.75a.75.75 0 0 1 1.5 0v15.5a.75.75 0 0 1-.75.75m13 0a.75.75 0 0 1-.75-.75v-10.5a.75.75 0 0 1 1.5 0v10.5a.75.75 0 0 1-.75.75m-7.25-.75a.75.75 0 0 0 1.5 0V2.75a.75.75 0 0 0-1.5 0z");
}

</style>
