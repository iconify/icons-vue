<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q5e5dvbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:phosphor-logo" /></template>
<style>
.q5e5dvbyg {
  fill: currentColor;
  d: path("M152 32H72a8 8 0 0 0-8 8v128a80.09 80.09 0 0 0 80 80a8 8 0 0 0 8-8v-64a72 72 0 0 0 0-144M80 70.54L130.32 160H80Zm56 66.92L85.68 48H136ZM80.51 176H136v55.5A64.14 64.14 0 0 1 80.51 176M152 160V48a56 56 0 0 1 0 112");
}

</style>
