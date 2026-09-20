<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGa45fn1xG)" class="xc0q8hjum"/><path fill="url(#SVGeSMZ7duN)" class="bo4qnubph"/><path fill="url(#SVG9FrgWbJb)" class="ci96ynitp"/><defs><linearGradient id="SVGa45fn1xG" x1="18.088" x2="6.706" y1="5.118" y2="18.618" gradientUnits="userSpaceOnUse"><stop class="oqk-8e9wc"/><stop offset="1" class="dca7mp5ce"/></linearGradient><linearGradient id="SVGeSMZ7duN" x1="20.011" x2="3.772" y1="3.676" y2="13.615" gradientUnits="userSpaceOnUse"><stop class="wa2q_nbap"/><stop offset="1" class="mc2r3rbah"/></linearGradient><linearGradient id="SVG9FrgWbJb" x1="7.31" x2="13.636" y1="17.829" y2="12.91" gradientUnits="userSpaceOnUse"><stop class="ofaf4j-jd"/><stop offset="1" class="k0qny2b6i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:thor" /></template>
<style>
.bo4qnubph {
  d: path("m10.285 8.83l1.948 1.884l4.326-4.606l-6.274 2.716zm7.232-3.712l.307.413l-5.575 5.94l-2.895-2.806z");
}

.ci96ynitp {
  d: path("m14.276 14.15l-1.996-1.912l-5.183 5.38zm-8.1 4.468l-.297-.424l6.385-6.723l2.912 2.848z");
}

.dca7mp5ce {
  stop-color: var(--svg-color--08acfc, #08acfc);
}

.ft5dv1b6b {
  fill: none;
}

.k0qny2b6i {
  stop-color: var(--svg-color--1cd2f1, #1cd2f1);
}

.mc2r3rbah {
  stop-color: var(--svg-color--29e0ee, #29e0ee);
}

.ofaf4j-jd {
  stop-color: var(--svg-color--14aafe, #14aafe);
}

.oqk-8e9wc {
  stop-color: var(--svg-color--37faf9, #37faf9);
}

.wa2q_nbap {
  stop-color: var(--svg-color--3efffa, #3efffa);
}

.xc0q8hjum {
  d: path("M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0m-9 8.47a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94");
}

</style>
