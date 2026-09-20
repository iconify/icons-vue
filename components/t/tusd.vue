<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttuifqhjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tusd" /></template>
<style>
.ttuifqhjm {
  fill: var(--svg-color--1b5aff, #1b5aff);
  d: path("M9 3H3v6a6 6 0 0 0 6-6m0 18V8.994C9 5.682 11.478 3 14.844 3H21v6h-6v12z");
}

</style>
