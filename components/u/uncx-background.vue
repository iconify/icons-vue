<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="eqk0dtbno"/><path clip-rule="evenodd" class="ipe_v0h1h"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uncx-background" /></template>
<style>
.eqk0dtbno {
  fill: var(--svg-color--00d379, #00d379);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.ipe_v0h1h {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m.5-.5c3.5 0 7-3.96 7-8c0-.646 0-1.5-.5-2c-1.18-1.14-2.31-1.71-2.305-1.706l-.69.77c.01-.02.3-.925.3-.945c0 0-1.185-.505-2.256-.57l-.215 1.055l-.14-1.09l-.044-.001c-.247-.011-1.438-.065-2.47.186l.53.96c-.45-.1-.88-.06-1.446.765L9.09 8.71v.005L6 8.164l3.614 1.68s-1.75 2.75-1.935 3.06c-.195.325-.4.905.665 1.175c.2.065.4.105.61.125c1.111-.034 2.129-.41 3.146-.785l.04-.014l.42-.156l.003.004c.333.308 1.343 1.242.396 2.777c-.614 1.002-1.892 1.337-3.125 1.44A19 19 0 0 1 8 17.5c1.207 1.02 2 1.353 2.328 1.456c.671.324 1.385.543 2.172.543m-.366-9.11L11 11.224s-.35-.41.1-.75a1.1 1.1 0 0 1 1.035-.085");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
