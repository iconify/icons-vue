<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9hy98wfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:widgets" /></template>
<style>
.z9hy98wfe {
  fill: currentColor;
  d: path("M13 13v8h8v-8zM3 21h8v-8H3zM3 3v8h8V3zm13.66-1.31L11 7.34L16.66 13l5.66-5.66z");
}

</style>
