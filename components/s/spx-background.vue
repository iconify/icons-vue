<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGhcXjvcBx)" class="r4i437pya"/><path clip-rule="evenodd" class="y9cegcu0k"/><path class="gua7ghbjl"/></g><defs><linearGradient id="SVGhcXjvcBx" x1="4.235" x2="20" y1="12.706" y2="13.177" gradientUnits="userSpaceOnUse"><stop class="w10i9rrox"/><stop offset="1" class="bvtb07cgm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:spx-background" /></template>
<style>
.bvtb07cgm {
  stop-color: var(--svg-color--0bf2fe, #0bf2fe);
}

.ft5dv1b6b {
  fill: none;
}

.gua7ghbjl {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.998 12.16l.565 3.106a3.75 3.75 0 0 1-2.118-.975c-.376-.343-.931-.484-1.364-.22c-.462.272-.603.88-.245 1.27a5.63 5.63 0 0 0 4.07 1.835l.113.636a.942.942 0 1 0 1.855-.33l-.104-.588a5.65 5.65 0 0 0 3.821-6.188c-.122-.857-.998-1.313-1.854-1.177c-2.461.396-4.922.753-7.393 1.13a3.765 3.765 0 0 1 5.61-2.353c.362.22.814.282 1.18.08c.565-.306.697-1.06.175-1.436a5.646 5.646 0 0 0-8.955 4.58c0 .752.729 1.242 1.477 1.129c1.05-.165 2.08-.335 3.167-.5m1.864-.283l2.903-.433v.085a3.76 3.76 0 0 1-2.339 3.483l-.564-3.13z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.w10i9rrox {
  stop-color: var(--svg-color--fd00ff, #fd00ff);
}

.y9cegcu0k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
