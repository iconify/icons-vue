<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hmsg9qb5j"/><path class="ngi71-bhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hmsg9qb5j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 4h9a2.003 2.003 0 0 1 2 2v2a2.003 2.003 0 0 1-2 2h-3Zm-5 6a2.003 2.003 0 0 1-2-2V6c0-.787.46-1.5 1.177-1.823L10 10Zm14 10H5a2.003 2.003 0 0 1-2-2v-2a2.003 2.003 0 0 1 2-2h9l5.823 5.823c-.26.117-.538.177-.823.177");
}

.ngi71-bhq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10H5a2 2 0 0 1-2-2V6a2 2 0 0 1 1.177-1.823M10 4h9a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-3m3.823 9.823c-.25.114-.53.177-.823.177H5a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h9m-7 3h.01M2 2l20 20");
}

</style>
