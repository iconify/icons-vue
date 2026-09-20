<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="acq2nibah"/><path class="xxkktx_7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zero-network" /></template>
<style>
.acq2nibah {
  fill: var(--svg-color--fe5161, #fe5161);
  d: path("M12 21a9 9 0 1 1 0-18a9 9 0 0 1 0 18");
}

.ft5dv1b6b {
  fill: none;
}

.xxkktx_7m {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.04 7.173c-3.136 0-4.376 1.917-4.376 4.74c0 2.822 1.24 4.833 4.377 4.833s4.377-2.011 4.377-4.834s-1.24-4.74-4.377-4.74m.001 8.026c-1.43 0-2.171-.84-2.395-2.253a.175.175 0 0 1 .172-.203h4.424c.107 0 .189.096.173.202c-.218 1.414-.943 2.254-2.373 2.254M9.8 11.21a.175.175 0 0 1-.173-.2c.198-1.47.94-2.291 2.414-2.291s2.2.822 2.392 2.292a.175.175 0 0 1-.173.199z");
}

</style>
