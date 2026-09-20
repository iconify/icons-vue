<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knnyx7bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mindfulness" /></template>
<style>
.knnyx7bpq {
  fill: currentColor;
  d: path("M7 21v-3.762q-1.425-1.3-2.212-2.922T4 10.986q0-3.327 2.333-5.657T12 3q2.702 0 4.884 1.645t2.83 4.25l1.036 4.103q.1.38-.142.692q-.242.31-.646.31H18v3.385q0 .666-.475 1.14t-1.14.475H14v2zm4.5-7.5h1v-6h-1zm3-1.5h1V8.5h-1zm-6-.5h1v-3h-1z");
}

</style>
