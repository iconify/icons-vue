<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="myqkgpi4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:replay-16-filled" /></template>
<style>
.myqkgpi4c {
  fill: currentColor;
  d: path("M2.5 3.668V2.5a.5.5 0 0 0-1 0v3A.5.5 0 0 0 2 6h2.5a.5.5 0 0 0 0-1H2.802a6 6 0 1 1-.782 3.5a.534.534 0 0 0-.52-.5a.474.474 0 0 0-.483.5A7 7 0 1 0 2.5 3.668m4.996 1.465A1 1 0 0 0 6 6.001V10a1 1 0 0 0 1.496.868l3.498-2a1 1 0 0 0 0-1.736z");
}

</style>
