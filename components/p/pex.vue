<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG1cdbgbvz)" class="fgdmi8d2o"/><path fill="url(#SVGEAIA3ZEW)" clip-rule="evenodd" class="pdz3gw7lg"/><path fill="url(#SVGDWGJncSw)" clip-rule="evenodd" class="lspa9h6qd"/><path fill="url(#SVGBNuIocql)" clip-rule="evenodd" class="es5vghbms"/><defs><linearGradient id="SVG1cdbgbvz" x1="8.379" x2="12.634" y1="5.33" y2="13.793" gradientUnits="userSpaceOnUse"><stop class="m-oqq_zzq"/><stop offset="1" class="b9_zjab9h"/></linearGradient><linearGradient id="SVGEAIA3ZEW" x1="8.379" x2="12.633" y1="5.33" y2="13.794" gradientUnits="userSpaceOnUse"><stop class="m-oqq_zzq"/><stop offset="1" class="b9_zjab9h"/></linearGradient><linearGradient id="SVGDWGJncSw" x1="2.206" x2="20.492" y1="10.117" y2="14.297" gradientUnits="userSpaceOnUse"><stop class="bbotrqgoj"/><stop offset="1" class="n98mp4rbf"/></linearGradient><linearGradient id="SVGBNuIocql" x1="7.219" x2="14.118" y1="4.456" y2="20.571" gradientUnits="userSpaceOnUse"><stop class="k4g_q4gfo"/><stop offset="1" class="xp88zmblg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pex" /></template>
<style>
.b9_zjab9h {
  stop-color: var(--svg-color--0db775, #0db775);
}

.bbotrqgoj {
  stop-color: var(--svg-color--05462e, #05462e);
}

.es5vghbms {
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-.794a8.206 8.206 0 1 0 0-16.413a8.206 8.206 0 0 0 0 16.413");
}

.fgdmi8d2o {
  d: path("m11.244 10.366l-.154.2c-.678.867-1.69 2.164-1.737 2.932c-.069 1.112 1.218 2.208 2.647 2.208c1.43 0 2.716-1.096 2.647-2.208c-.047-.768-1.059-2.07-1.736-2.938l-.392-.508c-.111-.154-.323-.17-.519-.17c-.17-.005-.428.048-.518.17a9 9 0 0 1-.238.314");
}

.ft5dv1b6b {
  fill: none;
}

.k4g_q4gfo {
  stop-color: var(--svg-color--24c998, #24c998);
}

.lspa9h6qd {
  fill-rule: evenodd;
  d: path("M12 20.345a8.345 8.345 0 1 0-.001-16.69a8.345 8.345 0 0 0 0 16.69m0-.704a7.639 7.639 0 1 0 0-15.278a7.639 7.639 0 0 0 0 15.278");
}

.m-oqq_zzq {
  stop-color: var(--svg-color--c2f2df, #c2f2df);
}

.n98mp4rbf {
  stop-color: var(--svg-color--23c49b, #23c49b);
}

.pdz3gw7lg {
  fill-rule: evenodd;
  d: path("M20.343 12.164a8.343 8.343 0 1 1-16.687 0a8.343 8.343 0 0 1 16.687 0m-6.745-5.458c-.37.413-1.122 1.308-1.175 1.589h.37l1.96-1.589zm-1.683 1.589h.17c.656.01 1.29.25 1.789.677q.128.122.233.265a24 24 0 0 1 1.318 2.091l.024.042c.144.248.273.47.383.646a3.37 3.37 0 0 1 0 3.193A4.35 4.35 0 0 1 12 17.295a4.35 4.35 0 0 1-3.833-2.086a3.37 3.37 0 0 1 0-3.193c.116-.185.254-.423.402-.688l.067-.114c.354-.6.784-1.33 1.257-1.977c.54-.741 1.519-.932 2.022-.942");
}

.xp88zmblg {
  stop-color: var(--svg-color--2ead7b, #2ead7b);
}

</style>
