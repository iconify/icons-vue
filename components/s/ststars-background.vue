<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ffg559uqm"/><path clip-rule="evenodd" class="d_yfkacul"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ststars-background" /></template>
<style>
.d_yfkacul {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12q0 3.315-2.344 5.656A7.7 7.7 0 0 1 12 19.999c-2.212 0-4.094-.781-5.656-2.343A7.7 7.7 0 0 1 4.001 12c0-2.212.781-4.094 2.343-5.656A7.7 7.7 0 0 1 12 4.001q3.315 0 5.656 2.343A7.7 7.7 0 0 1 19.999 12m-2.735 5.265A7.1 7.1 0 0 1 12 19.444q-3.084.001-5.265-2.179A7.18 7.18 0 0 1 4.556 12q-.001-3.084 2.179-5.265a7.4 7.4 0 0 1 2.54-1.685A7.4 7.4 0 0 1 12 4.556q3.084-.001 5.265 2.179A7.17 7.17 0 0 1 19.444 12c0 2.056-.73 3.811-2.179 5.265m.113-6.757l-3.604-.164a.254.254 0 0 1-.245-.18l-1.27-3.396a.254.254 0 0 0-.259-.18a.254.254 0 0 0-.259.18l-1.27 3.397a.254.254 0 0 1-.245.179l-3.604.164a.25.25 0 0 0-.25.189a.26.26 0 0 0 .09.306l2.823 2.263c.094.075.122.174.094.291l-.96 3.501q-.054.183.104.297c.099.075.207.075.31.004l3.012-2a.255.255 0 0 1 .306 0l3.011 2c.108.07.216.07.315-.004q.158-.114.104-.297l-.955-3.5a.254.254 0 0 1 .094-.292l2.823-2.264a.26.26 0 0 0 .085-.3a.255.255 0 0 0-.25-.189z");
}

.ffg559uqm {
  fill: var(--svg-color--e40570, #e40570);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
