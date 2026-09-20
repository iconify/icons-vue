<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2rt6h_1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:molecule-48-regular" /></template>
<style>
.n2rt6h_1s {
  fill: currentColor;
  d: path("M32 24c5.523 0 10-4.477 10-10S37.523 4 32 4S22 8.477 22 14a9.96 9.96 0 0 0 1.453 5.195l-5.387 3.589a8 8 0 1 0 .443 9.868l7.682 3.84a6 6 0 1 0 1.12-2.235l-7.682-3.84A8 8 0 0 0 20 28a8 8 0 0 0-.618-3.089l5.634-3.754A9.97 9.97 0 0 0 32 24m0-2.5a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15m-20 12a5.5 5.5 0 1 1 0-11a5.5 5.5 0 0 1 0 11M35.5 38a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0");
}

</style>
