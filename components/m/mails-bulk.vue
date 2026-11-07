<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e-kpsim8k"/><path class="nr3kl4_bi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mails-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e-kpsim8k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.nr3kl4_bi {
  d: path("M9 2h10a3.004 3.004 0 0 1 3 3v10a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1H9a1 1 0 0 0-1 1a1 1 0 0 1-2 0v-.001A3 3 0 0 1 9 2M4.293 8.879l4.414 4.414c.324.323.866.742 1.355.705a1.4 1.4 0 0 0 .491-.152c.277-.139.522-.335.74-.553l4.414-4.414a.999.999 0 1 1 1.414 1.414l-4.414 4.414c-.37.37-.791.693-1.26.928c-.972.486-1.921.486-2.894 0a4.9 4.9 0 0 1-1.26-.928l-4.414-4.414a.999.999 0 1 1 1.414-1.414");
}

</style>
