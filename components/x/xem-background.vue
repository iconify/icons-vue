<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c1gdl2azp"/><path class="tyl_b77aw"/><path class="x2-hhlb_e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xem-background" /></template>
<style>
.c1gdl2azp {
  fill: var(--svg-color--32a4f2, #32a4f2);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tyl_b77aw {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.808 15.669a4.7 4.7 0 0 0-.584-2.32c-.935-1.723-3.204-2.243-3.568-4.353A3.616 3.616 0 0 1 15.36 4.82c1.615-.394 3.274.502 4.64 1.272c-.014 3.468-1.222 6.74-3.192 9.577");
}

.x2-hhlb_e {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.333 5.5a4.8 4.8 0 0 1 1.611-1.4c-3.455-.335-6.908.27-9.944 2c.004 1.891.151 4.324 1.948 5.375c2.018 1.18 4.688.08 5.316-2.143c.38-1.379.143-2.565 1.07-3.832m-2.15 7.008c-1.475.847-3.355.852-4.824-.008c1.356 3.093 3.705 5.8 6.64 7.488c2.04-1.204 4.319-2.63 3.465-5.376c-.658-2.218-3.29-3.24-5.28-2.104");
}

</style>
