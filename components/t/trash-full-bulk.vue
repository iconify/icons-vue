<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hmvt8ia6s"/><path class="qsl0uqejf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-full-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hmvt8ia6s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 5a1 1 0 0 1 1 1v13a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V6a1 1 0 0 1 1-1Zm-9 5v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0m4 0v7a1 1 0 0 0 2 0v-7a1 1 0 0 0-2 0");
}

.qsl0uqejf {
  d: path("M9.999 2h4a3 3 0 0 1 3 3h3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3c0-1.657 1.342-3 2.999-3M15 5a.987.987 0 0 0-.948-.999h-.001L14 4h-4l-.089.004h-.005A1 1 0 0 0 9 4.998V5Zm-4 5v7a1 1 0 0 1-2 0v-7a1 1 0 0 1 2 0m4 0v7a1 1 0 0 1-2 0v-7a1 1 0 0 1 2 0");
}

</style>
