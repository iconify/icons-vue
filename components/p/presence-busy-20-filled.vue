<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rqekgqf0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-busy-20-filled" /></template>
<style>
.rqekgqf0e {
  fill: currentColor;
  d: path("M20 10c0 5.523-4.477 10-10 10S0 15.523 0 10S4.477 0 10 0s10 4.477 10 10");
}

</style>
