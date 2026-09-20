<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kthkg_bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:map-pin-20-regular" /></template>
<style>
.kthkg_bzc {
  fill: currentColor;
  d: path("M10 2a2.5 2.5 0 0 1 .5 4.95V9h3.307a1.5 1.5 0 0 1 1.405.974l2.25 6A1.5 1.5 0 0 1 16.058 18H3.943a1.5 1.5 0 0 1-1.404-2.026l2.25-6A1.5 1.5 0 0 1 6.193 9H9.5V6.95A2.5 2.5 0 0 1 10 2m-3.807 8a.5.5 0 0 0-.468.324l-2.25 6a.5.5 0 0 0 .468.676h12.115a.5.5 0 0 0 .467-.676l-2.25-6a.5.5 0 0 0-.468-.324H10.5v3.5a.5.5 0 0 1-1 0V10zM10 3a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
