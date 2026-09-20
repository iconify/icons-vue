<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="q7zb8o9nz"/><path class="hylsozhul"/><path class="bg0jgxbtk"/><path class="hk7v_cc-r"/><path class="pdd-f1m9n"/><path class="si7eqhf5o"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pi-background" /></template>
<style>
.bg0jgxbtk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.987 7.12c-1.715-.075-3.644.262-4.4.436c.472 0 1.823.08 3.854.782c2.03.698 2.693 2.03 2.746 2.84a2.82 2.82 0 0 1-1.91 2.8c-1.64.56-5.218.866-6.8.95c.622.258 2.822.645 5.093.645a9.15 9.15 0 0 0 5.186-1.591a3.93 3.93 0 0 0 1.764-3.413c-.07-2.329-3.382-3.351-5.533-3.449");
}

.ft5dv1b6b {
  fill: none;
}

.hk7v_cc-r {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.942 11.267a2.26 2.26 0 0 1-.444 1.489c0-.41-.97-1.858-4.578-1.742c-3.866.12-4.28.449-4.71.72c-.659.408-.823 1.404-.716 1.875c-1.125-1.791-.64-3.137.444-4.289c.862-.915 2.044-1.333 2.533-1.426c6.044-.16 7.44 2.413 7.471 3.373");
}

.hylsozhul {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.378 16.889c-3.12-.067-5.484-1.036-6.28-1.511a14.8 14.8 0 0 0 6.17.28c.532-.111 1.928-.28 3.652-1.467a4.03 4.03 0 0 0 1.773-3.764c.556 2 .232 3.409 0 3.866c-.47.889-2.19 2.658-5.315 2.596");
}

.pdd-f1m9n {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.587 11.255c-4.12-.032-4.968 1.142-4.88 1.733c.654-.556 1.805-.667 3.978-.667c1.556 0 2.862.182 3.587.476c.68.275.546.875.355 1.155c1.133-.275 1.578-.755 1.662-.964c.152-.565-.577-1.698-4.702-1.733");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q7zb8o9nz {
  fill: var(--svg-color--265aa3, #265aa3);
  d: path("M24 0H0v24h24z");
}

.si7eqhf5o {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.001 11.893c.045-1.218 1.142-2.28 1.685-2.658c-.845.991-1.094 1.458-1.151 2.658c-.045.955.804 2.044 1.235 2.466c-.613-.315-1.813-1.253-1.769-2.466m.676 1.982c.115.169.444.556.853.729a3.5 3.5 0 0 0-.853-.729");
}

</style>
