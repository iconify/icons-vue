<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlfhqlzbs"/><path class="de4_krqzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:verified" /></template>
<style>
.de4_krqzo {
  d: path("M8.75 12.25L11 14.5l4.25-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nlfhqlzbs {
  d: path("m13.02 3.47l.92.65q1.03.72 2.26.93l1.11.2q1.23.21 1.44 1.44l.2 1.11q.21 1.23.93 2.26l.65.92q.72 1.02 0 2.04l-.65.92q-.72 1.03-.93 2.26l-.2 1.11q-.21 1.23-1.44 1.44l-1.11.2q-1.23.21-2.26.93l-.92.65q-1.02.72-2.04 0l-.92-.65q-1.03-.72-2.26-.93l-1.11-.2q-1.23-.21-1.44-1.44l-.2-1.11q-.21-1.23-.93-2.26l-.65-.92q-.72-1.02 0-2.04l.65-.92q.72-1.03.93-2.26l.2-1.11q.21-1.23 1.44-1.44l1.11-.2q1.23-.21 2.26-.93l.92-.65q1.02-.72 2.04 0");
}

</style>
