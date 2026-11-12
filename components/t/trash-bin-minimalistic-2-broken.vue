<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fh6a-dbrt"/><path class="kvdjm4bsr"/><path class="k218w6buj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-minimalistic-2-broken" /></template>
<style>
.fh6a-dbrt {
  d: path("M20.5001 6H3.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k218w6buj {
  d: path("M5.16699 8.5L5.62693 15.3991C5.80393 18.054 5.89242 19.3815 6.75743 20.1907C7.62244 21 8.95284 21 11.6136 21H12.387C15.0478 21 16.3782 21 17.2432 20.1907C18.1082 19.3815 18.1967 18.054 18.3737 15.3991M18.6337 11.5L18.8337 8.5");
}

.kvdjm4bsr {
  d: path("M9.1709 4C9.58273 2.83481 10.694 2 12.0002 2C13.3064 2 14.4177 2.83481 14.8295 4");
}

</style>
