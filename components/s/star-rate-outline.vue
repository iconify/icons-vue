<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2e67hbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:star-rate-outline" /></template>
<style>
.q2e67hbpm {
  fill: currentColor;
  d: path("M9.6 15.65L12 13.8l2.4 1.85l-.9-3.05l2.25-1.6h-2.8L12 7.9l-.95 3.1h-2.8l2.25 1.6zM5.825 21l2.325-7.6L2 9h7.6L12 1l2.4 8H22l-6.15 4.4l2.325 7.6L12 16.3zM12 11.775");
}

</style>
