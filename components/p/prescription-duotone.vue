<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="li-qiccld"/><path class="sb84q8p0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:prescription-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.li-qiccld {
  d: path("M168 84a44 44 0 0 1-44 44H72V40h52a44 44 0 0 1 44 44");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sb84q8p0x {
  d: path("m183.31 188l22.35-22.34a8 8 0 0 0-11.32-11.32L172 176.69l-41.15-41.16A52 52 0 0 0 124 32H72a8 8 0 0 0-8 8v152a8 8 0 0 0 16 0v-56h28.69l52 52l-22.35 22.34a8 8 0 0 0 11.32 11.32L172 199.31l22.34 22.35a8 8 0 0 0 11.32-11.32ZM80 48h44a36 36 0 0 1 0 72H80Z");
}

</style>
