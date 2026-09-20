<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGy0ZhpdaU)" class="r4i437pya"/><path clip-rule="evenodd" class="wq9aaxxuw"/></g><defs><linearGradient id="SVGy0ZhpdaU" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="qcpr4gbsn"/><stop offset="1" class="l45hyccwt"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nwc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l45hyccwt {
  stop-color: var(--svg-color--3476bc, #3476bc);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qcpr4gbsn {
  stop-color: var(--svg-color--35b4e8, #35b4e8);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wq9aaxxuw {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4L7.541 6.405l.447.828L12 5.07l4.012 2.164l.447-.828zM5.883 8.46l.942-.55l-.473-.812l-1.41.821v8.3L11.058 20v-3.39l-3.515-2.194l-.5.798l3.074 1.918v1.18l-4.235-2.616zm12.235 0l-.943-.55l.473-.812l1.41.821v8.3L12.942 20v-3.39l3.515-2.194l.5.798l-3.074 1.918v1.18l4.236-2.616zM12 6.284l4.459 2.405l-.447.828L12 7.354L7.988 9.518l-.447-.828l4.235-2.285zm-1.412 4.304h-.47v-.941h.47v-.47h.941v.47H12v-.47h.941v.47a1.411 1.411 0 0 1 1.155 2.223a1.411 1.411 0 0 1-.92 2.483h-.235v.47H12v-.47h-.47v.47h-.942v-.47h-.47v-.941h.47zm2.824.47a.47.47 0 0 1-.47.471h-1.413v-.94h1.412a.47.47 0 0 1 .47.47m-1.883 2.354v-.942h1.647a.47.47 0 1 1 0 .941z");
}

</style>
