<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn-xtwijd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-minus-fill" /></template>
<style>
.dn-xtwijd {
  fill: currentColor;
  d: path("M6 2h12a3 3 0 0 1 3 3v5c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V5a3 3 0 0 1 3-3m3 8a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Z");
}

</style>
