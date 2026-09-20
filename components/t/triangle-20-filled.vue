<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lrbh8obgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-20-filled" /></template>
<style>
.lrbh8obgj {
  fill: currentColor;
  d: path("M1.176 15.8A1.5 1.5 0 0 0 2.502 18h14.995a1.5 1.5 0 0 0 1.318-2.215l-7.6-14C10.643.731 9.13.74 8.57 1.798z");
}

</style>
