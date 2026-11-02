<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x1fnfzazw"/><path class="f6rg45f9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shower-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f6rg45f9r {
  d: path("m4.707 3.293l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.999.999 0 1 1 1.414-1.414M16 9h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2m4 1h.01a1 1 0 0 1 0 2H20a1 1 0 0 1 0-2m-7 2h.01a1 1 0 0 1 0 2H13a1 1 0 0 1 0-2m4 1h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2m-7 2h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 1h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-3 3h.01a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2");
}

.x1fnfzazw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.707 13.707a1 1 0 0 1-1.414 0a5.2 5.2 0 0 1-1.152-1.735A5.2 5.2 0 0 1 4.757 10a5.23 5.23 0 0 1 1.536-3.707A5.23 5.23 0 0 1 10 4.757a5.2 5.2 0 0 1 1.972.384c.65.263 1.241.655 1.735 1.152a1 1 0 0 1 0 1.414Z");
}

</style>
