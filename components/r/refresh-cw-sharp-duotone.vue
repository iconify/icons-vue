<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a_h2u23xb"/><path class="q-4sndczh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:refresh-cw-sharp-duotone" /></template>
<style>
.a_h2u23xb {
  stroke-opacity: 0.4;
  d: path("M3.4273 14.9172L3.2117 13.9407C3.071 13.3034 3 12.6527 3 12C3 7.0294 7.0294 3 12 3C14.4831 3 16.8559 4.0259 18.5568 5.8349L19.0133 6.3204M19.8369 2.1414L19.2001 6.5999L14.7414 5.9631");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-4sndczh {
  d: path("M20.5727 9.0828L20.7883 10.0593C20.929 10.6966 21 11.3473 21 12C21 16.9706 16.9706 21 12 21C9.5169 21 7.1441 19.9741 5.4432 18.1651L4.9867 17.6796M4.1631 21.8586L4.7999 17.4001L9.2586 18.0369");
}

</style>
