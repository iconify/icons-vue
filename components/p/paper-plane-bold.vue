<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p1sto63mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paper-plane-bold" /></template>
<style>
.p1sto63mk {
  fill: currentColor;
  d: path("m241.42 198.2l-.06-.09L145.3 30.17a20 20 0 0 0-34.82 0L14.58 198.2a20 20 0 0 0 24.06 28.65L128 196.67l89.36 30.18a20 20 0 0 0 6.69 1.15a20 20 0 0 0 17.37-29.8M140 175.39V120a12 12 0 0 0-24 0v55.39l-75.28 25.43l87.17-152.76l87.37 152.75Z");
}

</style>
