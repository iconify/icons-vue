<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wv3avxa3e"/><path class="tt2ye8b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-cursor-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tt2ye8b1m {
  stroke-opacity: 0.4;
  d: path("M21 19H12");
}

.wv3avxa3e {
  fill: currentColor;
  d: path("M13.768 3.77343C14.9252 3.40124 16.0243 4.4913 15.6557 5.65429L15.6538 5.66112L12.5298 15.2891C12.1127 16.5849 10.3211 16.6994 9.74362 15.4639L7.78855 11.2832L3.91745 9.64257L3.91843 9.64159C2.6436 9.10607 2.71087 7.27571 4.0239 6.83691C4.02945 6.83506 4.0359 6.83377 4.04148 6.83202L13.768 3.77343Z");
  stroke: none;
}

</style>
