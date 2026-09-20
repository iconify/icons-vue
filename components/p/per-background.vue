<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGRCAax3mn)" class="im6ez8bzo"/><path fill="url(#SVGEY4Nse1V)" class="svf9wbcwn"/><path fill="url(#SVGZTGJ8bCR)" class="nh5gr4b3d"/></g><defs><linearGradient id="SVGRCAax3mn" x1="17.627" x2="4.816" y1="7.19" y2="14.361" gradientUnits="userSpaceOnUse"><stop class="m8m80lbjp"/><stop offset="1" class="sa9qxxbzd"/></linearGradient><linearGradient id="SVGEY4Nse1V" x1="16.9" x2="9.895" y1="4.796" y2="18.852" gradientUnits="userSpaceOnUse"><stop class="h974rh0rd"/><stop offset="1" class="ox97subyi"/></linearGradient><linearGradient id="SVGZTGJ8bCR" x1="10.03" x2="8.996" y1="17.289" y2="19.767" gradientUnits="userSpaceOnUse"><stop class="eutyfbboq"/><stop offset="1" class="ibvw_sb1j"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:per-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.eutyfbboq {
  stop-color: var(--svg-color--fefefc, #fefefc);
}

.ft5dv1b6b {
  fill: none;
}

.h974rh0rd {
  stop-color: var(--svg-color--e67f5e, #e67f5e);
}

.ibvw_sb1j {
  stop-color: var(--svg-color--ffc125, #ffc125);
}

.im6ez8bzo {
  d: path("M12 18.629a7.314 7.314 0 1 0 0-14.63a7.314 7.314 0 0 0 0 14.63");
}

.m8m80lbjp {
  stop-color: var(--svg-color--fd2307, #fd2307);
}

.nh5gr4b3d {
  d: path("m4.75 10.268l-.028.228c1.577-1.5 4.508-2.615 6.66-2.615c2.218 0 3.818 1.326 3.818 2.953c0 2.387-3.525 3.52-5.029 3.735V10.4a.914.914 0 1 0-1.828 0v8.686a.914.914 0 1 0 1.828 0v-2.752c5.76-1.362 6.4-4.38 6.4-5.298c0-.915-.68-3.836-4.9-3.836c-3.054 0-5.692 1.865-6.921 3.068");
}

.ox97subyi {
  stop-color: var(--svg-color--fcc252, #fcc252);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sa9qxxbzd {
  stop-color: var(--svg-color--fdb106, #fdb106);
}

.svf9wbcwn {
  d: path("m4.736 10.445l-.023.256c1.088-.928 3.812-2.587 6.761-2.587c2.39 0 3.762 1.371 4.146 2.075l-.384 3.027l-4.292 2.368l-.316.242v-5.472a.862.862 0 1 0-1.723 0v7.588a7 7 0 0 0 1.723.549v-1.509c2.222-.292 5.943-1.622 5.943-5.289c0-1.394-1.033-2.903-1.582-3.479l-2.88-.836l-3.24.49l-2.497 1.284z");
}

</style>
