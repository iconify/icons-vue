<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlnpwi78g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-mark-email-read" /></template>
<style>
.nlnpwi78g {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h8v-2H4V8l8 5l8-5v5h2V6c0-1.1-.9-2-2-2m-8 7L4 6h16zm5.34 11l-3.54-3.54l1.41-1.41l2.12 2.12l4.24-4.24L23 16.34z");
}

</style>
