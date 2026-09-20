<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgvo2acwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:variable-add-sharp" /></template>
<style>
.hgvo2acwh {
  fill: currentColor;
  d: path("M4 16V8h16v1.633q-.125-.012-.244-.015q-.118-.003-.256-.003q-2.384 0-4.038 1.654t-1.654 4.039q0 .178.006.347t.03.345zm15 3v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
