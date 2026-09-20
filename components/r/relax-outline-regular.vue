<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qb7w1fbvo"/><path class="yxqt_ilaa"/><path class="k11irslia"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:relax-outline-regular" /></template>
<style>
.k11irslia {
  d: path("M12 16c4 0 7 -3 7 -6 -4 0 -7 3 -7 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.qb7w1fbvo {
  d: path("M12 6c3 3 3 7 0 10 -3 -3 -3 -7 0 -10");
}

.yxqt_ilaa {
  d: path("M12 16c-4 0 -7 -3 -7 -6 4 0 7 3 7 6");
}

</style>
