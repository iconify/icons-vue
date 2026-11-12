<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3j3v3bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sd-card-fill-round" /></template>
<style>
.t3j3v3bfl {
  fill: currentColor;
  d: path("M20 17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V8c0-1.039.578-1.992 1.293-2.707l2-2C8.008 2.578 8.961 2 10 2h5a5 5 0 0 1 5 5ZM11 7a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm3 0a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm3 3V7a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0");
}

</style>
