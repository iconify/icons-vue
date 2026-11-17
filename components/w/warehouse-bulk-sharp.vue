<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mk_cyjbts"/><path class="eb7gxi5dk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eb7gxi5dk {
  d: path("M7 16v-4a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v9a1 1 0 0 1-2 0v-4H9v4a1 1 0 0 1-2 0Zm2-1h6v-2H9Z");
}

.mk_cyjbts {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8c0-.379.214-.725.553-.894l6-3A1 1 0 0 1 10 4h4c.155 0 .308.036.447.106l6 3A1 1 0 0 1 21 8v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
