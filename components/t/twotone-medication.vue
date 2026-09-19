<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni2caqtou"/><path class="tugrwzb8k"/><path class="c6gxa0bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-medication" /></template>
<style>
.c6gxa0bde {
  fill: currentColor;
  d: path("M10.5 17.5h3V15H16v-3h-2.5V9.5h-3V12H8v3h2.5z");
}

.ni2caqtou {
  fill: currentColor;
  d: path("M7 19h10V8H7zm1-7h2.5V9.5h3V12H16v3h-2.5v2.5h-3V15H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.tugrwzb8k {
  fill: currentColor;
  d: path("M6 3h12v2H6zm11 3H7c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 13H7V8h10z");
}

</style>
