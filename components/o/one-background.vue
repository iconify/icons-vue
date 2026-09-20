<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGn1BSYc8y)" class="r4i437pya"/><path class="diur3688b"/></g><defs><linearGradient id="SVGn1BSYc8y" x1="17.588" x2="7.228" y1="6.211" y2="18.164" gradientUnits="userSpaceOnUse"><stop class="k2ejx3ixm"/><stop offset="1" class="kvff8nqgh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:one-background" /></template>
<style>
.diur3688b {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.57 4.001A3.6 3.6 0 0 0 13 7.441v3.834c-.35 0-.6.05-1 .05s-.65 0-1 .05V7.441C11 5.546 9.315 3.95 7.38 4C5.54 4 4.051 5.595 4.001 7.44v9.169A3.45 3.45 0 0 0 7.531 20c1.884-.05 3.47-1.55 3.47-3.39v-3.84c.349 0 .599-.05.999-.05s.65 0 1-.05v3.89A3.574 3.574 0 0 0 16.62 20a3.465 3.465 0 0 0 3.379-3.44V7.44a3.44 3.44 0 0 0-3.43-3.439m-9.09 1.5c1.14 0 2.02.795 2.02 1.94v4.034c-.995.15-1.97.45-2.914.85c-.4.2-.735.4-1.085.7v-5.59c0-1.1.835-1.939 1.98-1.939zM9.5 16.61c0 1.15-.88 1.89-2.02 1.89c-1.144 0-1.98-.746-1.98-1.89v-.9c0-.795.586-1.59 1.68-2.04c.75-.35 1.475-.55 2.32-.7zm7.07 1.89c-1.14 0-2.07-.746-2.07-1.89v-4.035c.994-.15 2.02-.45 2.964-.85c.4-.2.685-.4 1.035-.7v5.585c0 1.15-.835 1.89-1.93 1.89m.3-8.07c-.75.35-1.526.55-2.37.7V7.44c0-1.15.93-1.94 2.07-1.94a1.844 1.844 0 0 1 1.929 1.94v.9c.05.845-.535 1.59-1.63 2.09");
}

.ft5dv1b6b {
  fill: none;
}

.k2ejx3ixm {
  stop-color: var(--svg-color--00e8a2, #00e8a2);
}

.kvff8nqgh {
  stop-color: var(--svg-color--00b1e2, #00b1e2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
