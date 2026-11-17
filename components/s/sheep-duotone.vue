<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hj72mtslv"/><path class="wta6pi43a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sheep-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hj72mtslv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 11c-2.669 1.329-4.665-2.663-2-4c-1.329-2.669 2.663-4.665 4-2a3.25 3.25 0 0 1 6 0c1.337-2.665 5.329-.669 4 2c2.665 1.337.669 5.329-2 4v6c-.002 3.155-2.225 3.999-5 4c-2.775-.001-4.998-.845-5-4Z");
}

.wta6pi43a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 11c-2.667 1.333-4.667-2.667-2-4c-1.333-2.667 2.667-4.667 4-2c1.111-2.667 4.889-2.667 6 0c1.333-2.667 5.333-.667 4 2c2.667 1.333.667 5.333-2 4v6c0 3-2 4-5 4s-5-1-5-4Zm0 3l-3 1m13-1l3 1m-10-2h.01M14 13h.01M12 18h.01");
}

</style>
