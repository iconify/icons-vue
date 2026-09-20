<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz76q5bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transit-enterexit-outline" /></template>
<style>
.xz76q5bpc {
  fill: currentColor;
  d: path("M6 18V8h3v4.75l6.8-6.8l2.2 2.2L11.15 15H16v3z");
}

</style>
