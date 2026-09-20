<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tvo5v-bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-45-right-16-regular" /></template>
<style>
.tvo5v-bvt {
  fill: currentColor;
  d: path("M1.148 6.145a.5.5 0 0 1 .707 0L9 13.294V12a.5.5 0 0 1 1 0v2.5a.5.5 0 0 1-.5.5H7a.5.5 0 0 1 0-1h1.294L1.148 6.852a.5.5 0 0 1 0-.707m9.498-.5a.5.5 0 0 1 .707 0L14 8.293V7a.5.5 0 0 1 1 0v2.5a.5.5 0 0 1-.5.5H12a.5.5 0 0 1 0-1h1.293l-2.648-2.648a.5.5 0 0 1 0-.707m-.282-4.628a.5.5 0 0 1 .591.691l-3 6.5a.5.5 0 0 1-.908-.42l.898-1.947l-1.788-1.788l-1.947.9a.5.5 0 1 1-.418-.907l6.5-3.002zm-3.239 2.59l1.267 1.267l1.087-2.353z");
}

</style>
