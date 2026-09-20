<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGKmSdtIUq)" class="yce0mk1ru"/><path fill="url(#SVGFgHbPcTT)" class="i0nmgjbuv"/><path fill="url(#SVGZF6UqbrF)" class="wwzhmca1n"/><path class="v5v8ej9jj"/><defs><linearGradient id="SVGKmSdtIUq" x1="12.186" x2="11.982" y1="14.033" y2="20.998" gradientUnits="userSpaceOnUse"><stop class="jemgizbdb"/><stop offset="1" class="w5kn6cafe"/></linearGradient><linearGradient id="SVGFgHbPcTT" x1="12" x2="12" y1="2.999" y2="20.996" gradientUnits="userSpaceOnUse"><stop offset=".69" class="yyj268bmp"/><stop offset="1" class="x5s8adoti"/></linearGradient><linearGradient id="SVGZF6UqbrF" x1="12" x2="12" y1="2.998" y2="21.01" gradientUnits="userSpaceOnUse"><stop offset=".55" class="hp9y0yj4e"/><stop offset=".94" class="x5s8adoti"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xava" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hp9y0yj4e {
  stop-color: var(--svg-color--ff8368, #ff8368);
}

.i0nmgjbuv {
  d: path("M6.073 11.897c.6.3 1.536.894 2.717 1.896c2.178 1.842 5.268.924 6.162-.09c.864-.984 1.38-1.53 2.904-1.95L14.07 4.302a2.297 2.297 0 0 0-4.14 0z");
}

.jemgizbdb {
  stop-color: var(--svg-color--ff7153, #ff7153);
}

.v5v8ej9jj {
  fill: var(--svg-color--ff4746, #ff4746);
  d: path("m8.25 7.602l1.68-3.3a2.299 2.299 0 0 1 4.14 0l1.482 2.922a4.66 4.66 0 0 1-3.798 1.907c-1.404 0-2.664-.594-3.504-1.53");
}

.w5kn6cafe {
  stop-color: var(--svg-color--ff2f45, #ff2f45);
}

.wwzhmca1n {
  d: path("M7.207 9.66c.39.257.87.623 1.367 1.103a4.64 4.64 0 0 0 3.168 1.32c.624 0 2.094-.3 3.468-1.578a9.2 9.2 0 0 1 1.428-1.152L14.07 4.302a2.297 2.297 0 0 0-4.14 0z");
}

.x5s8adoti {
  stop-color: var(--svg-color--ff4746, #ff4746);
}

.yce0mk1ru {
  d: path("M14.07 4.302a2.297 2.297 0 0 0-4.14 0L3.277 17.387c-.828 1.637.3 3.611 2.07 3.611c.42 0 .822-.132 1.158-.378l4.091-3.006a2.39 2.39 0 0 1 2.898.036l3.701 2.85c.42.324.93.498 1.458.498c1.77 0 2.898-1.974 2.07-3.611z");
}

.yyj268bmp {
  stop-color: var(--svg-color--ff6c58, #ff6c58);
}

</style>
