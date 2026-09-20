<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rx_i2ob2c"/><path class="q9jdmhbsc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rad-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q9jdmhbsc {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.565 12.124c-.423-.635-1.543-1.817-2.048-2.323c4.582-1.099 6.987 2.312 7.617 4.155c.062-.687.568-2.849 2.075-6.043C15.72 4.718 18.358 3.975 19.483 4c-.062 1.083-.423 3.638-1.357 5.17c-.94 1.528-3.314 1.683-4.315 1.575a31 31 0 0 0-1.037 3.426c-.346 1.425.32 4.026.346 4.784c.025.77-.455 1.012-1.146 1.043c-.691.026-1.037-.464-1.037-1.043c0-.567.557-3.498.423-5.005c-.103-1.198-.774-1.864-1.089-2.05c-.31.424-1.105 1.245-1.786 1.178c-.851-.083-1.383-.166-1.92-.955");
}

.rx_i2ob2c {
  fill: var(--svg-color--52dd4e, #52dd4e);
  d: path("M24 0H0v24h24z");
}

</style>
