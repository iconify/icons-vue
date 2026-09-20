<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egp78c4hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slash-forward-24-filled" /></template>
<style>
.egp78c4hs {
  fill: currentColor;
  d: path("M15.317 2.051a1 1 0 0 1 .632 1.265l-6 18a1 1 0 1 1-1.897-.632l6-18a1 1 0 0 1 1.265-.633");
}

</style>
