<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="eu_696b5l"/><path class="jry7u0bpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:note-blank-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eu_696b5l {
  d: path("m216 160l-56 56v-56Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jry7u0bpo {
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h108.69a15.86 15.86 0 0 0 11.31-4.69L219.31 168a15.86 15.86 0 0 0 4.69-11.31V48a16 16 0 0 0-16-16M48 48h160v104h-48a8 8 0 0 0-8 8v48H48Zm148.69 120L168 196.69V168Z");
}

</style>
