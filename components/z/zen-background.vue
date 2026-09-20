<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGJPt1abJI)" class="r4i437pya"/><path class="gn8vvsb7c"/><path class="bcn2p59vr"/><path class="tuea4r8na"/></g><defs><radialGradient id="SVGJPt1abJI" cx="0" cy="0" r="1" gradientTransform="matrix(17.034 0 0 17.0165 18.119 3.995)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="oepyb769y"/><stop offset=".26" class="mhnax-bah"/><stop offset=".56" class="nhg7phc8l"/><stop offset=".89" class="c1c9kfbgq"/></radialGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zen-background" /></template>
<style>
.bcn2p59vr {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.012 16.007a4.015 4.015 0 0 0 3.952-3.293a9.15 9.15 0 0 0-7.284 1.515a4.02 4.02 0 0 0 3.332 1.778");
}

.c1c9kfbgq {
  stop-color: var(--svg-color--0e9de5, #0e9de5);
}

.ft5dv1b6b {
  fill: none;
}

.gn8vvsb7c {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.508 7.338L17.2 9.365a5.834 5.834 0 0 1-4.263 8.384a5.8 5.8 0 0 1-3.544-.55L7.36 18.506a7.988 7.988 0 0 0 12.612-5.857a8.02 8.02 0 0 0-1.464-5.316h.005z");
}

.mhnax-bah {
  stop-color: var(--svg-color--23d29a, #23d29a);
}

.nhg7phc8l {
  stop-color: var(--svg-color--1abbbb, #1abbbb);
}

.oepyb769y {
  stop-color: var(--svg-color--26db8d, #26db8d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tuea4r8na {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.992 11.777q1.03.001 2.038.222a4.02 4.02 0 0 0-7.87-1.157a4 4 0 0 0-.13 1.697c-.555.409-1.06.88-1.506 1.407a5.833 5.833 0 0 1 4.739-7.706a5.8 5.8 0 0 1 3.35.565l2.024-1.313A7.986 7.986 0 0 0 4.02 11.439a8 8 0 0 0 1.548 5.32a9.6 9.6 0 0 1 1.365-1.886q.654-.676 1.411-1.237a9.55 9.55 0 0 1 5.652-1.858z");
}

</style>
