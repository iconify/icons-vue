<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1wjqqbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-width-wide" /></template>
<style>
.m1wjqqbnz {
  fill: currentColor;
  d: path("M22 4H2v16h20zM4 6h2v12H4zm16 12h-2V6h2z");
}

</style>
