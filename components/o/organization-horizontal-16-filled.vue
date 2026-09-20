<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pg2w95bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:organization-horizontal-16-filled" /></template>
<style>
.pg2w95bni {
  fill: currentColor;
  d: path("M3.5 10.5a2.5 2.5 0 1 1 2.45-3H7V5.367C7 4.612 7.612 4 8.367 4h1.683a2.5 2.5 0 1 1 0 1H8.367A.367.367 0 0 0 8 5.366v5.267c0 .203.164.367.367.367h1.683a2.5 2.5 0 1 1 0 1H8.367A1.367 1.367 0 0 1 7 10.633V8.501H5.95A2.5 2.5 0 0 1 3.5 10.5");
}

</style>
