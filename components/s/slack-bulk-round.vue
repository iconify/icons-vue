<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k39oqmy_k"/><path class="qnjgpj4el"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slack-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k39oqmy_k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 9.5a1.5 1.5 0 0 1-3 0v-5c0-.75.551-1.384 1.294-1.486c.445.044.878.188 1.261.419c.286.283.446.665.445 1.067ZM9.5 11h-5c-.75 0-1.384-.551-1.486-1.294c.044-.445.188-.878.419-1.261A1.5 1.5 0 0 1 4.5 8h5a1.5 1.5 0 0 1 0 3m1.5 8.5c0 .75-.551 1.384-1.294 1.486a3 3 0 0 1-1.261-.419A1.5 1.5 0 0 1 8 19.5v-5a1.5 1.5 0 0 1 3 0Zm9.986-5.206a3 3 0 0 1-.419 1.261A1.5 1.5 0 0 1 19.5 16h-5a1.5 1.5 0 0 1 0-3h5c.75 0 1.384.551 1.486 1.294");
}

.qnjgpj4el {
  d: path("M9.5 6A1.5 1.5 0 1 1 11 4.5V5a1 1 0 0 1-1 1ZM18 9.5a1.5 1.5 0 1 1 1.5 1.5H19a1 1 0 0 1-1-1Zm-12 5A1.5 1.5 0 1 1 4.5 13H5a1 1 0 0 1 1 1Zm8.5 3.5a1.5 1.5 0 1 1-1.5 1.5V19a1 1 0 0 1 1-1Z");
}

</style>
