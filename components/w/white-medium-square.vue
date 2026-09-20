<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sdd03o8jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:white-medium-square" /></template>
<style>
.sdd03o8jg {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M23 23h82v82H23z");
}

</style>
