<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac0xocc7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-first-line-24-regular" /></template>
<style>
.ac0xocc7n {
  fill: currentColor;
  d: path("M3.78 3.22a.75.75 0 0 0-1.06 1.06l1.47 1.47l-1.47 1.47a.75.75 0 0 0 1.06 1.06l2-2a.75.75 0 0 0 0-1.06zM9.75 5a.75.75 0 0 0 0 1.5h11.5a.75.75 0 0 0 0-1.5zm-7 13a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5zM2 12.25a.75.75 0 0 1 .75-.75h18.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75");
}

</style>
