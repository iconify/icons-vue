<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="guj5ndblb"/><path class="mkwvu5bez"/><path class="gweihee3d"/><path class="obcs1cbgf"/><path class="gcs2nkswg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-broken" /></template>
<style>
.gcs2nkswg {
  d: path("M20 10V11C20 14.012 18.3354 16.6353 15.876 18M4 10V11C4 15.4183 7.58172 19 12 19");
}

.guj5ndblb {
  d: path("M7 8C7 5.23858 9.23858 3 12 3C14.7614 3 17 5.23858 17 8V11C17 13.7614 14.7614 16 12 16C9.23858 16 7 13.7614 7 11V8Z");
}

.gweihee3d {
  d: path("M13 11L17 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mkwvu5bez {
  d: path("M13 8L17 8");
}

.obcs1cbgf {
  d: path("M12 19V22");
}

</style>
