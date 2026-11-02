<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ncjjet46h"/><path class="i-7ssyblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reddit-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i-7ssyblh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 10l1-6h4m0 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M9 14h.01M15 14h.01M9 17a5 5 0 0 0 6 0m-8.457-5.273C7.96 10.625 9.934 10 12 10s4.04.625 5.457 1.727a2 2 0 1 1 2.005 3.219c.288 2.087-1.068 4.113-3.496 5.222s-5.504 1.109-7.932 0s-3.784-3.135-3.496-5.222a2 2 0 1 1 2.005-3.219");
}

.ncjjet46h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.606 10.465c3.121-1.956 7.667-1.956 10.788 0a3.002 3.002 0 1 1 3.106 5.134c-.034 1.738-.966 3.273-2.291 4.354c-2.845 2.32-7.304 2.625-10.59 1.125c-1.258-.575-2.408-1.441-3.182-2.598c-.571-.852-.917-1.853-.937-2.881a3.002 3.002 0 0 1 .071-5.237a3 3 0 0 1 3.035.103");
}

</style>
