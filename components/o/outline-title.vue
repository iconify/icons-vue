<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqbie6beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-title" /></template>
<style>
.uqbie6beg {
  fill: currentColor;
  d: path("M5 4v3h5.5v12h3V7H19V4z");
}

</style>
