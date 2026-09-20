<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="va8737bdo"/><path class="tcp-unbdr"/><path class="zlt136b_n"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wbeth-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tcp-unbdr {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.497 17.816A7.97 7.97 0 0 1 12 20c-2.094 0-4-.8-5.421-2.118l.663-.668A7.04 7.04 0 0 0 12 19.06a7.02 7.02 0 0 0 4.828-1.91zm.578-.611A7.97 7.97 0 0 0 20 12c0-2.09-.8-3.995-2.118-5.421l-.659.668A7.04 7.04 0 0 1 19.06 12a7.02 7.02 0 0 1-1.652 4.537zM7.464 6.593A7.02 7.02 0 0 1 12 4.94c1.765 0 3.379.65 4.612 1.718l.673-.668A8 8 0 0 0 12 4a7.95 7.95 0 0 0-5.205 1.93zm-.612.579l-.668-.668A7.97 7.97 0 0 0 4 12c0 2.023.753 3.873 1.99 5.28l.669-.668A7.03 7.03 0 0 1 4.94 12c0-1.868.725-3.567 1.91-4.828M12 10.597L8.706 12C9.803 10.306 12 6.908 12 6.823zm0 0L15.294 12C14.193 10.306 12 6.908 12 6.823z");
}

.va8737bdo {
  fill: var(--svg-color--868686, #868686);
  d: path("M24 0H0v24h24z");
}

.zlt136b_n {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 13.882L8.706 12L12 10.588zm0 0L15.294 12L12 10.588zm0 .682l-3.294-1.859L12 17.175zm0 0l3.294-1.859L12 17.175z");
}

</style>
