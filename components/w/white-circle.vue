<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bp3nwdp9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:white-circle" /></template>
<style>
.bp3nwdp9d {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M64 24.3c-21.92 0-39.69 17.78-39.69 39.71S42.08 103.7 64 103.7s39.69-17.77 39.69-39.69S85.92 24.3 64 24.3");
}

</style>
