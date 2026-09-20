<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="le41ikb_c"/><path class="km4nftb1k"/><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="qh-87afpi"/><path class="tr6mw0eac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:seller-profile-duotone-regular" /></template>
<style>
.ia4sldbfw {
  d: path("M3 21a9 9 0 0 1 18 0");
}

.km4nftb1k {
  fill: currentColor;
  d: path("M9 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.le41ikb_c {
  fill: currentColor;
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.qh-87afpi {
  d: path("M9 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.tr6mw0eac {
  d: path("M12 15v4");
}

</style>
