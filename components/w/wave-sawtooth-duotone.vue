<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="f_1c03m3a"/><path class="ihpk138tc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wave-sawtooth-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f_1c03m3a {
  d: path("M128 64v64H24Zm104 64H128v64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ihpk138tc {
  d: path("m236.19 134.81l-104 64A8 8 0 0 1 120 192V78.32l-91.81 56.49a8 8 0 0 1-8.38-13.62l104-64A8 8 0 0 1 136 64v113.68l91.81-56.49a8 8 0 0 1 8.38 13.62");
}

</style>
