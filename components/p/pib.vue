<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGk5B5mchG)" class="cxu8qzbfg"/><defs><linearGradient id="SVGk5B5mchG" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="hvlv70b8z"/><stop offset=".191" class="kb33n56ay"/><stop offset=".386" class="u1_ha7agk"/><stop offset=".579" class="srmmxjhyl"/><stop offset=".8" class="ks6404b-d"/><stop offset="1" class="acj8-9b4s"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pib" /></template>
<style>
.acj8-9b4s {
  stop-color: var(--svg-color--7270af, #7270af);
}

.cxu8qzbfg {
  d: path("M5 10.232V7.045l3.574-2.033l2.755 1.582zM11.75 3L9 4.681l6.5 3.69V5.132zM16 12.82V5.399l3 1.64V11.2zm2.999 2.067v-3.194l-6.3 3.639l2.734 1.658zM8.5 16.777v-3.219L15 17.27L12.25 19zM5 19.364v-6.708L8 11v10zm5-9.686L12 8.5l2 1.178v2.555L12 13.5l-2-1.267z");
}

.ft5dv1b6b {
  fill: none;
}

.hvlv70b8z {
  stop-color: var(--svg-color--8cb69d, #8cb69d);
}

.kb33n56ay {
  stop-color: var(--svg-color--a2c98a, #a2c98a);
}

.ks6404b-d {
  stop-color: var(--svg-color--6e7cb4, #6e7cb4);
}

.srmmxjhyl {
  stop-color: var(--svg-color--df6b83, #df6b83);
}

.u1_ha7agk {
  stop-color: var(--svg-color--c1a879, #c1a879);
}

</style>
