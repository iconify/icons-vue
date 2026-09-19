<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqn2vnbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mail-outline" /></template>
<style>
.aqn2vnbqm {
  fill: currentColor;
  d: path("M22 4H2.01L2 20h20zm-2 14H4V8l8 5l8-5zm-8-7L4 6h16z");
}

</style>
