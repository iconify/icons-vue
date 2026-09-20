<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bh9h_3zcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-vertical-12-regular" /></template>
<style>
.bh9h_3zcs {
  fill: currentColor;
  d: path("M5.5 1a.5.5 0 0 0-.5.5v9a.5.5 0 0 0 1 0v-9a.5.5 0 0 0-.5-.5m-3 1H4v1H2.5a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 .5.5H4v1H2.5A1.5 1.5 0 0 1 1 8.5v-5A1.5 1.5 0 0 1 2.5 2m6 7H7v1h1.5A1.5 1.5 0 0 0 10 8.5v-5A1.5 1.5 0 0 0 8.5 2H7v1h1.5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5");
}

</style>
