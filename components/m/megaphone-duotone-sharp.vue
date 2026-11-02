<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hb_kicvyv"/><path class="aotm4fb4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-duotone-sharp" /></template>
<style>
.aotm4fb4q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 8l10-5v16l-10-5zm0 0H3v6h8m-6 0v7h4v-7");
}

.ft5dv1b6b {
  fill: none;
}

.hb_kicvyv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20.553 2.106A1 1 0 0 1 22 3v16a1 1 0 0 1-1.447.894l-10-5A1 1 0 0 1 10 14V8c0-.379.214-.725.553-.894Z");
}

</style>
