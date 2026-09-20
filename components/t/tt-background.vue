<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG4D06Vbiq)" class="r4i437pya"/><path class="omgypby1l"/></g><defs><linearGradient id="SVG4D06Vbiq" x1="11.995" x2="11.995" y1="4.473" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="zwdf8tbhz"/><stop offset="1" class="tr4subcwo"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.omgypby1l {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.747 18.775l4.112-6.516c.061-.1-.01-.26-.127-.26h-3.6c-.29 0-.47-.286-.314-.536l4.427-7.456l-.25-.005a7.998 7.998 0 0 0-4.248 14.773m4.013 1.223h.235a7.999 7.999 0 0 0 4.258-14.773l-3.947 6.544a.15.15 0 0 0 .127.23H16.3c.292 0 .508.358.353.608l-4.898 7.386z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tr4subcwo {
  stop-color: var(--svg-color--0502da, #0502da);
}

.zwdf8tbhz {
  stop-color: var(--svg-color--06fcd7, #06fcd7);
}

</style>
