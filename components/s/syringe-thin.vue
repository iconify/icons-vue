<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="buzne6bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:syringe-thin" /></template>
<style>
.buzne6bvd {
  fill: currentColor;
  d: path("m234.83 69.17l-48-48a4 4 0 0 0-5.66 5.66L202.34 48L168 82.34l-37.17-37.17a4 4 0 1 0-5.66 5.66l9.17 9.17l-86.83 86.83a12 12 0 0 0-3.51 8.48v51l-22.83 22.86a4 4 0 0 0 5.66 5.66L49.66 212h51a11.93 11.93 0 0 0 8.48-3.51L196 121.66l9.17 9.17a4 4 0 0 0 5.66-5.66L173.66 88L208 53.66l21.17 21.17a4 4 0 1 0 5.66-5.66M103.51 202.83a4 4 0 0 1-2.82 1.17H52v-48.69a4 4 0 0 1 1.17-2.82L74 131.66l23.17 23.17a4 4 0 1 0 5.66-5.66L79.66 126L98 107.66l23.17 23.17a4 4 0 0 0 5.66-5.66L103.66 102L140 65.66l25.17 25.17L190.34 116Z");
}

</style>
