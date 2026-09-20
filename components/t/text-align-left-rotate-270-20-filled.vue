<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l9kyzcblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-left-rotate-270-20-filled" /></template>
<style>
.l9kyzcblv {
  fill: currentColor;
  d: path("M4.25 18a.75.75 0 0 1-.75-.75V6.75a.75.75 0 0 1 1.5 0v10.5a.75.75 0 0 1-.75.75m5 0a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.5 0v14.5a.75.75 0 0 1-.75.75m4.25-.75a.75.75 0 0 0 1.5 0v-8.5a.75.75 0 0 0-1.5 0z");
}

</style>
