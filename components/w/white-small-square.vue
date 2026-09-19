<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fjjssfbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:white-small-square" /></template>
<style>
.fjjssfbju {
  fill: var(--svg-color--d0d2d3, #d0d2d3);
  d: path("M43.36 39.932a2.18 2.18 0 0 1-2.181 2.181H25.316a2.18 2.18 0 0 1-2.181-2.181V24.068c0-1.205.978-2.181 2.181-2.181h15.863a2.18 2.18 0 0 1 2.181 2.181z");
}

</style>
