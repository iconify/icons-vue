<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgwpunbrh"/><path class="duxixbb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-roller-shades" /></template>
<style>
.duxixbb1s {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zm-2 0H6v-6h5v1.82A1.746 1.746 0 0 0 12 18a1.746 1.746 0 0 0 1-3.18V13h5zm0-8H6V5h12z");
}

.pgwpunbrh {
  fill: currentColor;
  d: path("M6 5h12v6H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
