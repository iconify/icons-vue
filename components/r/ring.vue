<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGLY2XXEbc)" class="fdpk-9b7g"/><defs><linearGradient id="SVGLY2XXEbc" x1="5.761" x2="9.954" y1="8.89" y2="18.73" gradientUnits="userSpaceOnUse"><stop class="la2ll6b9g"/><stop offset="1" class="e6mu-3auj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ring" /></template>
<style>
.e6mu-3auj {
  stop-color: var(--svg-color--fb3777, #fb3777);
}

.fdpk-9b7g {
  d: path("M4.35 9.728a1.125 1.125 0 1 0-.45 0v5.422h.45zm8.418 1.162c.446-.713.97-1.22 1.482-1.55v4.033a1.125 1.125 0 1 0 .45 0V9.09c.36-.164.7-.24.987-.24h1.263v5.422a1.126 1.126 0 1 0 .45 0V8.85h2.25v5.423a1.124 1.124 0 1 0 .45 0V8.85h.9V8.4h-5.313c-1.005 0-2.363.725-3.329 2.298a1.35 1.35 0 0 0-1.175 2.377a4.95 4.95 0 0 1-1.433 1.44v-3.887a1.125 1.125 0 1 0-.45 0v4.144c-.525.26-1.032.378-1.434.378H3v.45h4.866c1.074 0 2.67-.695 3.717-2.315a1.35 1.35 0 0 0 1.185-2.395M6.6 9.728a1.125 1.125 0 1 1 .45 0v5.422H6.6z");
}

.ft5dv1b6b {
  fill: none;
}

.la2ll6b9g {
  stop-color: var(--svg-color--4530dd, #4530dd);
}

</style>
