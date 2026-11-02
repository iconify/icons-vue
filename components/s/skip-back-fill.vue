<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cde73hblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-back-fill" /></template>
<style>
.cde73hblb {
  fill: currentColor;
  d: path("M16.41 4.456A2.999 2.999 0 0 1 21 7v10a3 3 0 0 1-4.59 2.544l-8-5a3 3 0 0 1 0-5.088ZM5 19a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
