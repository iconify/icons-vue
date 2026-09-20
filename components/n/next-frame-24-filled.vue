<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxh168bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:next-frame-24-filled" /></template>
<style>
.yxh168bnj {
  fill: currentColor;
  d: path("M5.5 3.75a.75.75 0 0 0-1.5 0v16.5a.75.75 0 0 0 1.5 0zm6.24-.44C10.577 2.513 9 3.344 9 4.752v14.495c0 1.413 1.589 2.244 2.75 1.437l10.498-7.302a1.75 1.75 0 0 0-.01-2.88z");
}

</style>
