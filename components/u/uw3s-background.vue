<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGIwtZfddM)" class="j4mg-j70i"/><path fill="url(#SVGCQHIBbPg)" class="rish6_e7d"/></g><defs><linearGradient id="SVGIwtZfddM" x1="18.888" x2="3.992" y1="11.329" y2="14.96" gradientUnits="userSpaceOnUse"><stop class="dmy9zg56z"/><stop offset=".17" class="rsd0wnbna"/><stop offset=".45" class="z76u_-ehv"/><stop offset=".69" class="l84b3cbie"/><stop offset=".95" class="fi--x_beo"/></linearGradient><linearGradient id="SVGCQHIBbPg" x1="19.47" x2="9.327" y1="9.282" y2="20" gradientUnits="userSpaceOnUse"><stop class="k1i_wdboy"/><stop offset=".2" class="gvi9n3bjq"/><stop offset=".49" class="cs9aqtbyf"/><stop offset="1" class="qczs_7b7r"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uw3s-background" /></template>
<style>
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

.j4mg-j70i {
  d: path("M14.798 8.996H8.996v5.802a5.408 5.408 0 0 1-3.412-9.214a5.407 5.407 0 0 1 9.214 3.412");
}

.k1i_wdboy {
  stop-color: var(--svg-color--e9cfeb, #e9cfeb);
}

.l84b3cbie {
  stop-color: var(--svg-color--7698ec, #7698ec);
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qczs_7b7r {
  stop-color: var(--svg-color--3095f4, #3095f4);
}

.rish6_e7d {
  d: path("M9.187 14.708a5.517 5.517 0 0 0 5.516-5.711H20V20H8.997v-5.302z");
}

.rsd0wnbna {
  stop-color: var(--svg-color--c7c6e8, #c7c6e8);
}

.z76u_-ehv {
  stop-color: var(--svg-color--d196e5, #d196e5);
}

</style>
