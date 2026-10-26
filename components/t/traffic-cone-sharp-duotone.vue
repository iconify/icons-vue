<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fx9n16b-h"/><path clip-rule="evenodd" class="e6ezu_b1h"/><path class="lm77aob4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:traffic-cone-sharp-duotone" /></template>
<style>
.e6ezu_b1h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.256 7.6667L16.744 7.6667L17.344 9.6667L6.656 9.6667L7.256 7.6667ZM5.256 14.3333L18.744 14.3333L19.344 16.3333L4.656 16.3333L5.256 14.3333Z");
  stroke: none;
}

.fx9n16b-h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.0422 21.7127L9.0422 1.7127C9.1691 1.2897 9.5584 1 10 1L14 1C14.4416 1 14.8309 1.2897 14.9578 1.7127L20.9578 21.7127C20.9858 21.8059 21 21.9027 21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22C3 21.9027 3.0142 21.8059 3.0422 21.7127Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lm77aob4a {
  d: path("M1 22L23 22");
}

</style>
