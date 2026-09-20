<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f-qptvb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rainbow-bold" /></template>
<style>
.f-qptvb2u {
  fill: currentColor;
  d: path("M256 172v8a12 12 0 0 1-24 0v-8a104 104 0 0 0-208 0v8a12 12 0 0 1-24 0v-8a128 128 0 0 1 256 0m-128-32a36 36 0 0 0-36 36v4a12 12 0 0 0 24 0v-4a12 12 0 0 1 24 0v4a12 12 0 0 0 24 0v-4a36 36 0 0 0-36-36m0-48a84.09 84.09 0 0 0-84 84v4a12 12 0 0 0 24 0v-4a60 60 0 0 1 120 0v4a12 12 0 0 0 24 0v-4a84.09 84.09 0 0 0-84-84");
}

</style>
