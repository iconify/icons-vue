<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh5c70b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-panorama-horizontal" /></template>
<style>
.xh5c70b8d {
  fill: currentColor;
  d: path("M4 6.55c2.6.77 5.28 1.16 8 1.16s5.41-.39 8-1.16v10.91c-2.6-.77-5.28-1.16-8-1.16s-5.41.39-8 1.16zM2 3.77v16.47s.77-.26.88-.3A26.2 26.2 0 0 1 12 18.3c3.09 0 6.18.55 9.12 1.64c.11.04.88.3.88.3V3.77s-.77.26-.88.3C18.18 5.15 15.09 5.71 12 5.71s-6.18-.56-9.12-1.64c-.11-.05-.88-.3-.88-.3");
}

</style>
