<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="gyzn7pp-t"/><path class="nlhxnr71c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subtract-square-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gyzn7pp-t {
  d: path("M216 96v120H96v-56h64V96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nlhxnr71c {
  d: path("M216 88h-48V40a8 8 0 0 0-8-8H40a8 8 0 0 0-8 8v120a8 8 0 0 0 8 8h48v48a8 8 0 0 0 8 8h120a8 8 0 0 0 8-8V96a8 8 0 0 0-8-8M48 48h104v104H48Zm160 160H104v-40h56a8 8 0 0 0 8-8v-56h40Z");
}

</style>
