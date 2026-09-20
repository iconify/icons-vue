<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a_i9wb66e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mic-off-32-regular" /></template>
<style>
.a_i9wb66e {
  fill: currentColor;
  d: path("M10 11.415L2.293 3.707a1 1 0 0 1 1.414-1.414l26 26a1 1 0 0 1-1.414 1.414l-5.964-5.964a9.95 9.95 0 0 1-5.33 2.208L17 26v3a1 1 0 1 1-2 0v-3l.002-.05C9.948 25.45 6 21.187 6 16a1 1 0 1 1 2 0a8 8 0 0 0 12.906 6.32l-1.43-1.43A6 6 0 0 1 10 16zm8.032 8.031L12 13.415V16a4 4 0 0 0 6.032 3.446M20 16q0 .224-.024.441l1.65 1.65A6 6 0 0 0 22 16V8a6 6 0 0 0-11.84-1.376L12 8.466V8a4 4 0 0 1 8 0zm3.143 3.608l1.473 1.472A9.95 9.95 0 0 0 26 16a1 1 0 1 0-2 0a8 8 0 0 1-.857 3.608");
}

</style>
