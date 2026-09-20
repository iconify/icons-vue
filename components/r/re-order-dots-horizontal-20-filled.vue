<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sou8m4_qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-horizontal-20-filled" /></template>
<style>
.sou8m4_qb {
  fill: currentColor;
  d: path("M14 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0m-5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0M5.5 8a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3m8.5 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0M10.5 15a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3M4 13.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0");
}

</style>
