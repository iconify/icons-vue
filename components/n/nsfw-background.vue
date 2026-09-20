<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kpgeayubc"/><path class="gjsjmjbxz"/><path class="rvn5xgkfg"/><path class="l1d4ajb-j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nsfw-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gjsjmjbxz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 18.223v-7.556H4zm0 0v-7.556h8z");
}

.kpgeayubc {
  fill: var(--svg-color--8e04e2, #8e04e2);
  d: path("M24 0H0v24h24z");
}

.l1d4ajb-j {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 10.666V7.72L7.779 5.777z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rvn5xgkfg {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.222 5.777L12 10.667h8zm-8.444 0L12 10.667H4zM12 10.666V7.72l4.222-1.943z");
}

</style>
