<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u_ovgpbgb"/><path class="b63ibobyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tent-sharp-two-tone" /></template>
<style>
.b63ibobyi {
  d: path("M3 21L12 3L21 21M1 21L23 21M12 3L12 21M12 13L16 21");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u_ovgpbgb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.1056 20.5528L11.1056 2.5528C11.275 2.214 11.6212 2 12 2C12.3788 2 12.725 2.214 12.8944 2.5528L21.8944 20.5528C21.9639 20.6916 22 20.8448 22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21C2 20.8448 2.0361 20.6916 2.1056 20.5528Z");
  stroke: none;
}

</style>
