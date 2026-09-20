<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mgm6svima"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:radical-bold" /></template>
<style>
.mgm6svima {
  fill: currentColor;
  d: path("M252 80v24a12 12 0 0 1-24 0V92h-91.68L91.24 212.21a12 12 0 0 1-22.47 0l-48-128a12 12 0 1 1 22.47-8.43l36.76 98l36.77-98A12 12 0 0 1 128 68h112a12 12 0 0 1 12 12");
}

</style>
