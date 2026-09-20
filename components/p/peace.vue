<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yycnrrh9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:peace" /></template>
<style>
.yycnrrh9y {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m88 104a87.5 87.5 0 0 1-11.64 43.7L136 123.84V40.37A88.11 88.11 0 0 1 216 128m-96-87.63v83.47L51.64 171.7A88 88 0 0 1 120 40.37M60.84 184.79L120 143.37v72.26a87.85 87.85 0 0 1-59.16-30.84M136 215.63v-72.26l59.16 41.42A87.85 87.85 0 0 1 136 215.63");
}

</style>
