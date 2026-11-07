<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d6_nu_bnk"/><path class="a_ymf1_zi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mails-bulk-round" /></template>
<style>
.a_ymf1_zi {
  d: path("M9 2h8a5 5 0 0 1 5 5v8a1 1 0 0 1-2 0V7a3.004 3.004 0 0 0-3-3H9a1 1 0 0 0-1 1a1 1 0 0 1-2 0v-.001A3 3 0 0 1 9 2m-4.576 8.01l3.283 3.283c.95.949 3.639.946 4.586 0l3.283-3.283a.999.999 0 1 1 1.414 1.414l-3.283 3.283C12.749 15.665 11.317 16 10 16a6.5 6.5 0 0 1-2.056-.311c-.613-.205-1.192-.523-1.651-.982L3.01 11.424a.999.999 0 1 1 1.414-1.414");
}

.cuyn6tgcc {
  fill: currentColor;
}

.d6_nu_bnk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 13a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v4a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

</style>
