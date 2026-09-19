<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1kmxjbam"/><path class="p8xec_bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-discount" /></template>
<style>
.i1kmxjbam {
  fill: currentColor;
  d: path("M12.79 21L3 11.21v2.83l9.79 9.79l9.04-9.04l-1.42-1.41z");
}

.p8xec_bop {
  fill: currentColor;
  d: path("m3 9.04l9.79 9.79l9.04-9.04L12.04 0H3zM7.25 3a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
