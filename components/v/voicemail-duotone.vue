<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rv04hs9mh"/><path class="adu42kbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:voicemail-duotone" /></template>
<style>
.adu42kbdr {
  d: path("M200 72a56 56 0 0 0-39.14 96H95.14A56 56 0 1 0 56 184h144a56 56 0 0 0 0-112M16 128a40 40 0 1 1 40 40a40 40 0 0 1-40-40m184 40a40 40 0 1 1 40-40a40 40 0 0 1-40 40");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rv04hs9mh {
  d: path("M104 128a48 48 0 1 1-48-48a48 48 0 0 1 48 48m96-48a48 48 0 1 0 48 48a48 48 0 0 0-48-48");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
