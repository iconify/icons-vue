<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="za979ab-x"/><path class="mfn_rnb_z"/><path class="kil06obbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podcast-duotone" /></template>
<style>
.kil06obbz {
  fill: currentColor;
  d: path("M13 11C13 11.5523 12.5523 12 12 12C11.4477 12 11 11.5523 11 11C11 10.4477 11.4477 10 12 10C12.5523 10 13 10.4477 13 11Z");
  stroke: none;
}

.mfn_rnb_z {
  d: path("M15.4641 13C15.8152 12.3919 16 11.7022 16 11C16 8.7909 14.2091 7 12 7C9.7909 7 8 8.7909 8 11C8 11.7022 8.1848 12.3919 8.5359 13M12 15L12 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.za979ab-x {
  stroke-opacity: 0.4;
  d: path("M18.9282 15C19.6304 13.7839 20 12.4043 20 11C20 6.5817 16.4183 3 12 3C7.5817 3 4 6.5817 4 11C4 12.4043 4.3697 13.7839 5.0718 15");
}

</style>
