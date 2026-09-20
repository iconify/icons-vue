<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rxh79hbfu"/><path class="u6isbcwht"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pln-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rxh79hbfu {
  fill: var(--svg-color--fc2952, #fc2952);
  d: path("M24 0H0v24h24z");
}

.u6isbcwht {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.55 4H8.49L4.04 9.61L4 9.65l1.54 7.09l6.415 3.215L12 20l6.46-3.215L20 9.695zm1.115 9.955l1.965-2.475l-.85 3.91zm-8.73.745l2.865 3.61l-4.105-2.045zM9.69 4.96h4.665L12 8.085l-2.31-3.13zM12 9.61L15.51 14L12 18.435L8.49 14zm-4.105 3.61L5.11 9.745l3.6-4.48L11.4 8.83zm8.17 1.525l1.24 1.52l-4.065 2.045zM18.93 9.79l-2.78 3.475l-3.51-4.435l2.7-3.565zM7.335 13.92l-1.11 1.39l-.855-3.87z");
}

</style>
