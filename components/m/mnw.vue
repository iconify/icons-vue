<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGbYytFAgI)" class="bs-3ug92d"/><path fill="url(#SVG1lbLEbON)" class="i2_o45bfq"/><path fill="url(#SVG0FWN4c6q)" class="rtv50q93j"/><path fill="url(#SVGAFbNHeZI)" class="scmfyac2w"/><defs><linearGradient id="SVGbYytFAgI" x1="16.314" x2="15.69" y1="6.432" y2="10.842" gradientUnits="userSpaceOnUse"><stop class="eloosfbwh"/><stop offset="1" class="gemvhx06g"/></linearGradient><linearGradient id="SVG1lbLEbON" x1="19.249" x2="3.001" y1="12.983" y2="13.37" gradientUnits="userSpaceOnUse"><stop class="n2cx89b4t"/><stop offset="1" class="z02449b3j"/></linearGradient><linearGradient id="SVG0FWN4c6q" x1="9.221" x2="11.438" y1="8.324" y2="19.244" gradientUnits="userSpaceOnUse"><stop class="yjvmfgbgb"/><stop offset="1" class="t57boab_q"/></linearGradient><linearGradient id="SVGAFbNHeZI" x1="7.129" x2="3.9" y1="12.874" y2="18.232" gradientUnits="userSpaceOnUse"><stop class="n2cx89b4t"/><stop offset="1" class="wm-bpb0nw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mnw" /></template>
<style>
.bs-3ug92d {
  d: path("m6.06 6.474l-3.034 11.24c-.196.73.752 1.228 1.26.656l4.056-4.553l2.488 2.817a1.58 1.58 0 0 0 2.35 0l2.489-2.811l4.044 4.526c.514.572 1.456.074 1.26-.656L17.945 6.49a1.513 1.513 0 0 0-2.589-.593L12 9.693L8.654 5.892a1.514 1.514 0 0 0-2.589.582z");
}

.eloosfbwh {
  stop-color: var(--svg-color--5083a9, #5083a9);
}

.ft5dv1b6b {
  fill: none;
}

.gemvhx06g {
  stop-color: var(--svg-color--12132c, #12132c);
}

.i2_o45bfq {
  d: path("M6.06 6.474L4.064 13.87a2.25 2.25 0 0 1 3.044-1.164c.53.248.942.72 1.234 1.111l2.488 2.806a1.576 1.576 0 0 0 2.35 0l2.489-2.806l3.255-3.7a4.625 4.625 0 0 1-6.93-.424L8.65 5.892a1.514 1.514 0 0 0-2.59.582");
}

.n2cx89b4t {
  stop-color: var(--svg-color--1c2849, #1c2849);
}

.rtv50q93j {
  d: path("m15.669 13.817l4.045 4.526c.513.572 1.455.074 1.26-.656l-2.05-7.57z");
}

.scmfyac2w {
  d: path("m4.064 13.864l-1.038 3.844c-.196.73.752 1.228 1.26.656l4.056-4.552a3.1 3.1 0 0 0-1.335-1.15a2.25 2.25 0 0 0-2.456.474c-.21.208-.378.456-.492.728z");
}

.t57boab_q {
  stop-color: var(--svg-color--5284ac, #5284ac);
}

.wm-bpb0nw {
  stop-color: var(--svg-color--436c92, #436c92);
}

.yjvmfgbgb {
  stop-color: var(--svg-color--13182f, #13182f);
}

.z02449b3j {
  stop-color: var(--svg-color--5893ba, #5893ba);
}

</style>
