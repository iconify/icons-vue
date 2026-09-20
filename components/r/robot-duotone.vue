<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="i2wulbcae"/><path class="u0ixp5bhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:robot-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i2wulbcae {
  d: path("M200 56H56a24 24 0 0 0-24 24v112a24 24 0 0 0 24 24h144a24 24 0 0 0 24-24V80a24 24 0 0 0-24-24m-36 128H92a20 20 0 0 1 0-40h72a20 20 0 0 1 0 40");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u0ixp5bhq {
  d: path("M200 48h-64V16a8 8 0 0 0-16 0v32H56a32 32 0 0 0-32 32v112a32 32 0 0 0 32 32h144a32 32 0 0 0 32-32V80a32 32 0 0 0-32-32m16 144a16 16 0 0 1-16 16H56a16 16 0 0 1-16-16V80a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16ZM72 108a12 12 0 1 1 12 12a12 12 0 0 1-12-12m88 0a12 12 0 1 1 12 12a12 12 0 0 1-12-12m4 28H92a28 28 0 0 0 0 56h72a28 28 0 0 0 0-56m-24 16v24h-24v-24Zm-60 12a12 12 0 0 1 12-12h8v24h-8a12 12 0 0 1-12-12m84 12h-8v-24h8a12 12 0 0 1 0 24");
}

</style>
