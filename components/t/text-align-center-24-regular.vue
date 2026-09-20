<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1qoyit8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-center-24-regular" /></template>
<style>
.f1qoyit8o {
  fill: currentColor;
  d: path("M4 5.75A.75.75 0 0 1 4.75 5h14.5a.75.75 0 0 1 0 1.5H4.75A.75.75 0 0 1 4 5.75m2 13a.75.75 0 0 1 .75-.75h10.5a.75.75 0 0 1 0 1.5H6.75a.75.75 0 0 1-.75-.75M2.75 11.5a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5z");
}

</style>
