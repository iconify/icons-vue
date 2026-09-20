<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wrnic2b7h"/><path class="zb6vo9c-p"/><path class="ucsncyqqe"/><path class="olxc00wjs"/><path class="zka_zabrc"/><path class="kdybz_aht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:silver-medal-duotone-regular" /></template>
<style>
.kdybz_aht {
  d: path("M9 17h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.olxc00wjs {
  d: path("M6 15a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.ucsncyqqe {
  d: path("m17 3 -5 5");
}

.wrnic2b7h {
  fill: currentColor;
  d: path("M6 15a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zb6vo9c-p {
  d: path("m7 3 5 5");
}

.zka_zabrc {
  d: path("M9 13h6");
}

</style>
