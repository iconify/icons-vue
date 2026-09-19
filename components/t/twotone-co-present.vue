<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="gorgu1bpf"/><path class="n6jxzbbjz"/><path class="ic9rndbss"/><path class="x2b8dk3tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-co-present" /></template>
<style>
.gorgu1bpf {
  cx: 9px;
  cy: 10px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ic9rndbss {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v8h2V5h18v16c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2");
}

.n6jxzbbjz {
  fill: currentColor;
  d: path("M14.48 18.34C13.29 17.73 11.37 17 9 17s-4.29.73-5.48 1.34C2.9 18.66 3 19.28 3 20h12c0-.71.11-1.34-.52-1.66");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.x2b8dk3tv {
  fill: currentColor;
  d: path("M13 10c0-2.21-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4m-6 0c0-1.1.9-2 2-2s2 .9 2 2s-.9 2-2 2s-2-.9-2-2m8.39 6.56C13.71 15.7 11.53 15 9 15s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 1 19.22V22h16v-2.78c0-1.12-.61-2.15-1.61-2.66M15 20H3c0-.72-.1-1.34.52-1.66C4.71 17.73 6.63 17 9 17s4.29.73 5.48 1.34c.63.32.52.95.52 1.66");
}

</style>
