<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzg02ccuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-24-regular" /></template>
<style>
.lzg02ccuw {
  fill: currentColor;
  d: path("M5.75 2a.75.75 0 0 0-.75.75v11.5a2.25 2.25 0 0 0 2.25 2.25H9.5v3a2.5 2.5 0 1 0 5 0v-3h2.25A2.25 2.25 0 0 0 19 14.25V2.75a.75.75 0 0 0-.75-.75zm.75 9V3.5h6v1.752a.75.75 0 1 0 1.5 0V3.5h1v2.751a.75.75 0 1 0 1.5 0V3.5h1V11zm0 3.25V12.5h11v1.75a.75.75 0 0 1-.75.75h-3a.75.75 0 0 0-.75.75v3.75a1 1 0 0 1-2 0v-3.75a.75.75 0 0 0-.75-.75h-3a.75.75 0 0 1-.75-.75");
}

</style>
