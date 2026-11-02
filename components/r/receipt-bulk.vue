<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a9bvykmfi"/><path class="l172ypweo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-bulk" /></template>
<style>
.a9bvykmfi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2h12a3 3 0 0 1 3 3v15c.003.406-.193.788-.525 1.023c-.674.478-1.631.235-2.182-.316a.413.413 0 0 0-.586 0a2.4 2.4 0 0 1-1.707.707a2.4 2.4 0 0 1-1.707-.707a.413.413 0 0 0-.586 0a2.4 2.4 0 0 1-1.707.707a2.4 2.4 0 0 1-1.707-.707a.413.413 0 0 0-.586 0A2.4 2.4 0 0 1 8 21.414a2.4 2.4 0 0 1-1.707-.707a.413.413 0 0 0-.586 0a1.95 1.95 0 0 1-1.345.57C3.622 21.277 3 20.761 3 20V5a3 3 0 0 1 3-3");
}

.cuyn6tgcc {
  fill: currentColor;
}

.l172ypweo {
  d: path("M16 6a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm-8 4h4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>
