<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vzmikccga"/><path class="wfpo08bkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vzmikccga {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.wfpo08bkg {
  d: path("M20.553 6.106A1 1 0 0 1 22 7v10a1 1 0 0 1-1.447.894l-6-3a1 1 0 1 1 .894-1.788L20 15.382V8.618l-4.553 2.276a1 1 0 1 1-.894-1.788Z");
}

</style>
