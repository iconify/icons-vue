<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sowt4_0jd"/><path class="bkw_7zbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-lock-corner-bulk" /></template>
<style>
.bkw_7zbxq {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM20 15a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2a3 3 0 0 1 6 0m-2 0a1 1 0 0 0-1-1h-.001a1 1 0 0 0-.712.299A.96.96 0 0 0 16 15ZM7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.sowt4_0jd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm8 8v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1");
}

</style>
