<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zrip-1dll"/><path class="gi76mbcrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-minus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gi76mbcrc {
  d: path("M15 11h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

.zrip-1dll {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 7v10a2.32 2.32 0 0 1-1.276 2.086c-.379.19-.801.269-1.222.217a2.06 2.06 0 0 1-1.209-.596l-1-1C6.98 17.395 6.468 17 6 17H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1c.468 0 .98-.395 1.293-.707l1-1a2.06 2.06 0 0 1 1.209-.596c.421-.052.843.027 1.222.217A2.32 2.32 0 0 1 12 7");
}

</style>
