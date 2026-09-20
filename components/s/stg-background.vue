<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k9l1j4ucx"/><path class="t-31m53-l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stg-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k9l1j4ucx {
  fill: var(--svg-color--8e8e8e, #8e8e8e);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t-31m53-l {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.055 10.78c.24-.332.589-.57.985-.675c1.07-.27 2.675-1.345 3.21-1.88c.535-.54 1.605-2.69 1.875-3.23l.03-.06c.09-.2.29-.63.71-.935a8.05 8.05 0 0 0-6.81 6.78M4 12.725A8.05 8.05 0 0 0 11.035 20c-.27-.235-.43-.565-.565-.855l-.08-.165l-.12-.265c-.315-.73-1.105-2.54-2.02-3.23c-1.07-.805-2.14-1.615-2.945-1.885c-.5-.165-1-.435-1.305-.875m9.07 7.26a8.05 8.05 0 0 0 6.93-7.35a2.1 2.1 0 0 1-1.045.7c-.8.265-2.675 1.61-3.21 2.15a15.3 15.3 0 0 0-2.145 3.5a2.3 2.3 0 0 1-.53 1m6.875-9.14A8.05 8.05 0 0 0 13.125 4c.315.245.561.567.715.935l.03.06l.195.44c.31.725.82 1.93 1.68 2.79c.85.86 2.05 1.375 2.775 1.685c.18.08.33.14.435.2c.31.15.71.4.99.735M12.574 7.89a.55.55 0 0 0-1.045-.01a5.43 5.43 0 0 1-3.64 3.55a.55.55 0 0 0-.01 1.04a5.43 5.43 0 0 1 3.55 3.64a.55.55 0 0 0 1.04.01a5.43 5.43 0 0 1 3.64-3.55a.55.55 0 0 0 .01-1.04a5.43 5.43 0 0 1-3.55-3.64z");
}

</style>
