<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="n3eg_ob3b"/><path class="qr-0lllzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:trash-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n3eg_ob3b {
  d: path("M200 56v152a8 8 0 0 1-8 8H64a8 8 0 0 1-8-8V56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qr-0lllzy {
  d: path("M216 48H40a8 8 0 0 0 0 16h8v144a16 16 0 0 0 16 16h128a16 16 0 0 0 16-16V64h8a8 8 0 0 0 0-16m-24 160H64V64h128ZM80 24a8 8 0 0 1 8-8h80a8 8 0 0 1 0 16H88a8 8 0 0 1-8-8");
}

</style>
