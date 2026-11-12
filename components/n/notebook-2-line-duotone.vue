<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pzp8ogjvu"/><path class="o5fhfcboe"/><path class="v_v5z6bnm"/><path class="utdmog81f"/><path class="pw7af6bia"/><path class="h1cr886eo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-2-line-duotone" /></template>
<style>
.h1cr886eo {
  d: path("M19 13L15 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o5fhfcboe {
  stroke-linejoin: round;
  d: path("M2 4.99792V16.1437C2 17.2547 2.90605 18.1536 4.01486 18.2229C4.98428 18.2836 6.12329 18.4021 7 18.6335C8.08145 18.9189 9.37293 19.5366 10.3724 20.0694C11.3852 20.6092 12.6148 20.6092 13.6276 20.0694C14.6271 19.5366 15.9185 18.9189 17 18.6335C17.8767 18.4021 19.0157 18.2836 19.9851 18.2229C21.094 18.1536 22 17.2547 22 16.1437V4.93332C22 3.86087 21.1538 2.98053 20.082 3.01787C18.9534 3.05718 17.5469 3.17415 16.5 3.48757C15.5924 3.75929 14.5353 4.30431 13.6738 4.80287C12.6355 5.40379 11.3428 5.43636 10.2823 4.87558C9.29611 4.35413 8.04921 3.76443 7 3.48757C6.11349 3.25363 4.95877 3.13502 3.9824 3.07501C2.8863 3.00764 2 3.89975 2 4.99792Z");
}

.pw7af6bia {
  d: path("M5 13L9 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pzp8ogjvu {
  stroke-linejoin: round;
  d: path("M12 5.27454V20.4743");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.utdmog81f {
  d: path("M19 9L15 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v_v5z6bnm {
  d: path("M5 9L9 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
