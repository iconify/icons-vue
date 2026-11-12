<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w3r9-bcte"/><path class="hi-iqlg2z"/><path class="evr7kjbjs"/><path class="sget89fql"/><path class="uu15i6ydm"/><path class="yr2vusnxh"/><path class="z4f5_ebln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-circle-line-duotone" /></template>
<style>
.evr7kjbjs {
  d: path("M14 14C12.8954 14 12 13.1046 12 12C12 10.8954 12.8954 10 14 10C15.1046 10 16 10.8954 16 12C16 13.1046 15.1046 14 14 14Z");
}

.hi-iqlg2z {
  d: path("M7 8L7 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sget89fql {
  d: path("M16 10L17 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uu15i6ydm {
  d: path("M11 15L12 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w3r9-bcte {
  d: path("M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22Z");
}

.yr2vusnxh {
  d: path("M12 10L11 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z4f5_ebln {
  d: path("M17 15L16 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
