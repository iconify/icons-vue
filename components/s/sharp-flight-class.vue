<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icrmcws_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-flight-class" /></template>
<style>
.icrmcws_t {
  fill: currentColor;
  d: path("M18 4h-6v9h6zM9.5 16H18v2H8L5 8V4h2v4zM8 19h10v2H8z");
}

</style>
