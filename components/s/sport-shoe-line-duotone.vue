<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtzvslsur"/><path class="rqdozi5bz"/><path class="hym1ucbpj"/><path class="cjq4-0kvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sport-shoe-line-duotone" /></template>
<style>
.cjq4-0kvi {
  d: path("M13.5 11.7797L14.9 10.5797");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hym1ucbpj {
  d: path("M11.1992 9.87969L12.6992 8.67969");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rqdozi5bz {
  d: path("M2.00586 15.2797H21.948");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vtzvslsur {
  d: path("M3.5 18.2797H19.5C21.1 18.2797 22 17.3797 22 15.8797C22 14.3797 21.1 13.4797 19.6 12.9797L16.2 11.8797C14.5 11.2797 13.4 10.3797 12.4 8.87971L10.8 6.47971C10.2 5.57971 9.2 5.47971 8.6 6.17971C7.5 7.47971 5.6 7.67971 4.3 6.47971C3.5 5.77971 2.3 6.27971 2.2 7.37971L2 15.4797C2 17.1797 2.6 18.2797 3.5 18.2797Z");
}

</style>
