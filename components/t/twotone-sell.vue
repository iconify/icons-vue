<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqihjwbrs"/><path class="tawtilbcd"/><circle class="k79q3xboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sell" /></template>
<style>
.k79q3xboj {
  cx: 6.5px;
  cy: 6.5px;
  r: 1.5px;
  fill: currentColor;
}

.rqihjwbrs {
  fill: currentColor;
  d: path("M4 4v7.17L12.83 20L20 12.83L11.17 4zm2.5 4C5.67 8 5 7.33 5 6.5S5.67 5 6.5 5S8 5.67 8 6.5S7.33 8 6.5 8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.tawtilbcd {
  fill: currentColor;
  d: path("m21.41 11.41l-8.83-8.83c-.37-.37-.88-.58-1.41-.58H4c-1.1 0-2 .9-2 2v7.17c0 .53.21 1.04.59 1.41l8.83 8.83c.78.78 2.05.78 2.83 0l7.17-7.17c.78-.78.78-2.04-.01-2.83M12.83 20L4 11.17V4h7.17L20 12.83z");
}

</style>
