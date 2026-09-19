<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1t9t1rtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-format-quote" /></template>
<style>
.l1t9t1rtc {
  fill: currentColor;
  d: path("M18.62 18h-5.24l2-4H13V6h8v7.24zm-2-2h.76L19 12.76V8h-4v4h3.62zm-8 2H3.38l2-4H3V6h8v7.24zm-2-2h.76L9 12.76V8H5v4h3.62z");
}

</style>
