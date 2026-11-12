<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="at_81ebpk"/><path class="tf_8-xb1g"/><path class="qxli02nev"/><path class="fsttjsb0t"/><path class="ksstd-fcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-line-duotone" /></template>
<style>
.at_81ebpk {
  d: path("M19.5 5.5C19.5 6.88071 18.3807 8 17 8C15.6193 8 14.5 6.88071 14.5 5.5C14.5 4.11929 15.6193 3 17 3C18.3807 3 19.5 4.11929 19.5 5.5Z");
}

.fsttjsb0t {
  d: path("M9.09668 13.3628L14.9038 17.1374");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksstd-fcd {
  d: path("M9.09668 10.6372L14.9039 6.86258");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qxli02nev {
  d: path("M4.5 12C4.5 10.6193 5.61929 9.5 7 9.5C8.38071 9.5 9.5 10.6193 9.5 12C9.5 13.3807 8.38071 14.5 7 14.5C5.61929 14.5 4.5 13.3807 4.5 12Z");
}

.tf_8-xb1g {
  d: path("M14.5 18.5C14.5 17.1193 15.6193 16 17 16C18.3807 16 19.5 17.1193 19.5 18.5C19.5 19.8807 18.3807 21 17 21C15.6193 21 14.5 19.8807 14.5 18.5Z");
}

</style>
