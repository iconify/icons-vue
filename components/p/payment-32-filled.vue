<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d6aff5bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:payment-32-filled" /></template>
<style>
.d6aff5bls {
  fill: currentColor;
  d: path("M6.5 5A4.5 4.5 0 0 0 2 9.5V11h28V9.5A4.5 4.5 0 0 0 25.5 5zM2 22.5V13h28v9.5a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 22.5M21 19a1 1 0 1 0 0 2h3a1 1 0 1 0 0-2z");
}

</style>
