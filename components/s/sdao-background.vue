<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGrfaVab5a)" class="v8tl3opqg"/><path class="p-mufv0ly"/><path fill="url(#SVGCAn9bcby)" class="s9sa1xbdg"/></g><defs><linearGradient id="SVGrfaVab5a" x1="20" x2="4" y1="12.014" y2="12.014" gradientUnits="userSpaceOnUse"><stop offset=".11" class="ab49cibdr"/><stop offset=".2" class="n2jqz6pop"/><stop offset=".35" class="x0nbll51i"/><stop offset=".46" class="pwmcsebhe"/><stop offset=".7" class="g499chlgl"/><stop offset="1" class="nljkssbui"/></linearGradient><linearGradient id="SVGCAn9bcby" x1="9.905" x2="8.216" y1="15.826" y2="15.901" gradientUnits="userSpaceOnUse"><stop class="t9dkn6_og"/><stop offset="1" class="r2caf12fb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sdao-background" /></template>
<style>
.ab49cibdr {
  stop-color: var(--svg-color--e25900, #e25900);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.g499chlgl {
  stop-color: var(--svg-color--2024de, #2024de);
}

.n2jqz6pop {
  stop-color: var(--svg-color--cbc91e, #cbc91e);
}

.nljkssbui {
  stop-color: var(--svg-color--2624df, #2624df);
}

.p-mufv0ly {
  fill: var(--svg-color--203bdb, #203bdb);
  d: path("M6.848 8.705c2.8-3.002 6.244-2.183 6.244-2.183l-.066-.076c-.376-.094-3.849-.706-6.178 2.26");
}

.pwmcsebhe {
  stop-color: var(--svg-color--3093d3, #3093d3);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r2caf12fb {
  stop-color: var(--svg-color--2133dd, #2133dd);
  stop-opacity: 0.4;
}

.s9sa1xbdg {
  d: path("M15.058 18.32c-1.181.659-2.903 1.176-4.179.48a2.41 2.41 0 0 1-1.181-2.48c.155-.777.715-1.539 1.313-2.259c.32-.386.659-.753.993-1.13l.518-.569c-.885.932-2.231 1.389-3.2 2.137c-.965.739-1.271 1.854-1.017 3.045c.268 1.223 1.181 2.352 3.384 2.447c1.378.06 2.456-.848 3.37-1.671");
}

.t9dkn6_og {
  stop-color: var(--svg-color--203bdb, #203bdb);
}

.v8tl3opqg {
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m2.023-10.25c.184-.795.08-1.82-.903-3.228c3.534.772 5.77 4.617 4.81 8.043a6.06 6.06 0 0 1-2.876 3.755c-1.181.659-2.903 1.176-4.179.48a2.41 2.41 0 0 1-1.18-2.48c.154-.777.714-1.539 1.312-2.259c.32-.386.659-.753.993-1.13l.518-.569c.668-.757 1.275-1.656 1.496-2.611z");
}

.x0nbll51i {
  stop-color: var(--svg-color--2de2c1, #2de2c1);
}

</style>
