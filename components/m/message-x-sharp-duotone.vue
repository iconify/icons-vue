<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rphf6ybon"/><path class="w8psy9brd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-x-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rphf6ybon {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.7234 19.8057L5.4389 21.8985C4.8104 22.2055 4.0689 21.7889 4.0043 21.0924L3.6081 16.825C1.9807 15.2413 1 13.081 1 11C1 6.1011 6.1264 2 12 2C17.8736 2 23 6.1011 23 11C23 15.8989 17.8736 20 12 20C11.2503 20 10.4661 19.9328 9.7234 19.8057Z");
  stroke: none;
}

.w8psy9brd {
  d: path("M8.7071 7.7071L15.2929 14.2929M15.2929 7.7071L8.7071 14.2929");
}

</style>
