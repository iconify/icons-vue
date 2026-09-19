<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aevgs5bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-sd-card-alert" /></template>
<style>
.aevgs5bgr {
  fill: currentColor;
  d: path("M18 2h-8L4.02 8L4 20c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H6V8.83L10.83 4H18zm-7-5h2v2h-2zm0-7h2v5h-2z");
}

</style>
