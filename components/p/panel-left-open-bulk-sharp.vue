<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m_ax_bbup"/><path class="k2skpw02v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-open-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k2skpw02v {
  d: path("M10 4v16a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0m3.293 10.293L15.586 12l-2.293-2.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

.m_ax_bbup {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>
