<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8op1mb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-guide-sharp" /></template>
<style>
.k8op1mb9p {
  fill: currentColor;
  d: path("M4 20V4h16v16zm4.962-4.962h1V9.962h2.173L14 15.038h1.077l2.27-6.077h-1.155L14.54 13.52l-1.616-4.558h-6.5v1h2.539z");
}

</style>
