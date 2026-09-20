<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGGqph1jRK)" class="beont6bhr"/><path fill="url(#SVGcBb0Beyb)" class="rt524jb4o"/><defs><linearGradient id="SVGGqph1jRK" x1="19.749" x2="2.991" y1="11.245" y2="15.33" gradientUnits="userSpaceOnUse"><stop class="dmy9zg56z"/><stop offset=".17" class="rsd0wnbna"/><stop offset=".45" class="z76u_-ehv"/><stop offset=".69" class="l84b3cbie"/><stop offset=".95" class="fi--x_beo"/></linearGradient><linearGradient id="SVGcBb0Beyb" x1="20.404" x2="8.993" y1="8.942" y2="21" gradientUnits="userSpaceOnUse"><stop class="k1i_wdboy"/><stop offset=".2" class="gvi9n3bjq"/><stop offset=".49" class="cs9aqtbyf"/><stop offset="1" class="qczs_7b7r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uw3s" /></template>
<style>
.beont6bhr {
  d: path("M15.148 8.62H8.62v6.528a6.085 6.085 0 0 1-5.48-7.365a6.083 6.083 0 0 1 12.008.837");
}

.cs9aqtbyf {
  stop-color: var(--svg-color--7567f8, #7567f8);
}

.dmy9zg56z {
  stop-color: var(--svg-color--c3f5e9, #c3f5e9);
}

.fi--x_beo {
  stop-color: var(--svg-color--5693f0, #5693f0);
}

.ft5dv1b6b {
  fill: none;
}

.gvi9n3bjq {
  stop-color: var(--svg-color--ac90f4, #ac90f4);
}

.k1i_wdboy {
  stop-color: var(--svg-color--e9cfeb, #e9cfeb);
}

.l84b3cbie {
  stop-color: var(--svg-color--7698ec, #7698ec);
}

.qczs_7b7r {
  stop-color: var(--svg-color--3095f4, #3095f4);
}

.rsd0wnbna {
  stop-color: var(--svg-color--c7c6e8, #c7c6e8);
}

.rt524jb4o {
  d: path("M8.835 15.047A6.207 6.207 0 0 0 15.04 8.62H21V21H8.62v-5.964z");
}

.z76u_-ehv {
  stop-color: var(--svg-color--d196e5, #d196e5);
}

</style>
