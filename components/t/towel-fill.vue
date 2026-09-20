<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dsozqyb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:towel-fill" /></template>
<style>
.dsozqyb7i {
  fill: currentColor;
  d: path("M224 48v104a8 8 0 0 1-8.53 8a8.17 8.17 0 0 1-7.47-8.25V48a8 8 0 0 0-8.55-8a8.19 8.19 0 0 0-7.45 8.28V180a4 4 0 0 1-4 4H52a4 4 0 0 1-4-4V48a24 24 0 0 1 24-24h128a24 24 0 0 1 24 24m-36 152H52a4 4 0 0 0-4 4v12a16 16 0 0 0 16 16h112a16 16 0 0 0 16-16v-12a4 4 0 0 0-4-4");
}

</style>
