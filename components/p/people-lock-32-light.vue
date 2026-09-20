<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wswumhbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-lock-32-light" /></template>
<style>
.wswumhbap {
  fill: currentColor;
  d: path("M23 16.5a3.5 3.5 0 0 1 3.5 3.5v.5h.5a2.5 2.5 0 0 1 2.5 2.5v6a2.5 2.5 0 0 1-2.5 2.5h-8a2.5 2.5 0 0 1-2.5-2.5v-6a2.5 2.5 0 0 1 2.5-2.5h.5V20a3.5 3.5 0 0 1 3.5-3.5m0 7.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-7-7c.956 0 1.806.45 2.355 1.146a5 5 0 0 0-.275.96q-.13.033-.258.073A2 2 0 0 0 16 18H5a2 2 0 0 0-2 2c0 .884.333 2.12 1.406 3.137C5.476 24.15 7.34 25 10.5 25c1.958 0 3.418-.327 4.5-.816v1.084c-1.174.455-2.653.732-4.5.732c-3.339 0-5.476-.9-6.781-2.137C2.417 22.63 2 21.116 2 20a3 3 0 0 1 3-3zm7 1.5a1.5 1.5 0 0 0-1.5 1.5v.5h3V20a1.5 1.5 0 0 0-1.5-1.5M10.5 4a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M23 7a4 4 0 1 1 0 8a4 4 0 0 1 0-8M10.5 5a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9M23 8a3 3 0 1 0 0 6a3 3 0 0 0 0-6");
}

</style>
