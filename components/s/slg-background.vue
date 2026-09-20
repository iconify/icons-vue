<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGJDHJgdIR)" class="nqeqwvltn"/><path fill="url(#SVGegzXRbfP)" clip-rule="evenodd" class="ti1u3mbhy"/><path fill="url(#SVGTRgSocUZ)" class="ii4b33bvd"/><path fill="url(#SVGoxnlpe6o)" class="vq8c7wb1i"/></g><defs><linearGradient id="SVGJDHJgdIR" x1="11.849" x2="11.849" y1="19.365" y2="13.525" gradientUnits="userSpaceOnUse"><stop offset=".59" class="nd2xe-t1t"/><stop offset="1" class="vqadd0zuh"/></linearGradient><linearGradient id="SVGegzXRbfP" x1="12" x2="12" y1="9.698" y2="14.875" gradientUnits="userSpaceOnUse"><stop offset=".57" class="o2dkrib9y"/><stop offset="1" class="y48o4db6v"/></linearGradient><linearGradient id="SVGTRgSocUZ" x1="8.973" x2="11.665" y1="10.216" y2="5.261" gradientUnits="userSpaceOnUse"><stop offset=".46" class="gcb-jtbke"/><stop offset="1" class="b1w_4jb7m"/></linearGradient><linearGradient id="SVGoxnlpe6o" x1="15.025" x2="12.334" y1="10.216" y2="5.261" gradientUnits="userSpaceOnUse"><stop offset=".26" class="lpiouh0nc"/><stop offset="1" class="b1w_4jb7m"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:slg-background" /></template>
<style>
.b1w_4jb7m {
  stop-color: var(--svg-color--d8f3fc, #d8f3fc);
}

.ft5dv1b6b {
  fill: none;
}

.gcb-jtbke {
  stop-color: var(--svg-color--70b8c7, #70b8c7);
}

.ii4b33bvd {
  d: path("M12 11.53L8.233 9.872L12 4z");
}

.lpiouh0nc {
  stop-color: var(--svg-color--96cedf, #96cedf);
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.nd2xe-t1t {
  stop-color: var(--svg-color--a9cfd8, #a9cfd8);
}

.nqeqwvltn {
  d: path("m4.47 16.645l2.354-4.376l5.223 2.296l5.13-2.296l2.352 4.376L12.047 20z");
}

.o2dkrib9y {
  stop-color: var(--svg-color--d7fdff, #d7fdff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ti1u3mbhy {
  fill-rule: evenodd;
  d: path("M11.99 14.875a853 853 0 0 0-5.166-2.607l5.167-2.57l5.186 2.57zm0-.815c-1.162-.588-3.5-1.774-3.543-1.788l3.544-1.76l3.562 1.765l-3.562 1.788zm-1.637-1.355l1.647.706l1.647-.71L12 11.999l-1.647.701z");
}

.vq8c7wb1i {
  d: path("m12 11.53l3.764-1.657L12 4z");
}

.vqadd0zuh {
  stop-color: var(--svg-color--cfe6ee, #cfe6ee);
}

.y48o4db6v {
  stop-color: var(--svg-color--dafbff, #dafbff);
}

</style>
