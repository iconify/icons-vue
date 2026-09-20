<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGTkOq0bYN)" class="r4i437pya"/><path clip-rule="evenodd" class="el7om1bfm"/></g><defs><linearGradient id="SVGTkOq0bYN" x1="12.744" x2="12.411" y1="4.499" y2="17.449" gradientUnits="userSpaceOnUse"><stop class="yhbg5lb8l"/><stop offset=".394" class="q5aca_buc"/><stop offset=".561" class="dpr1be7tb"/><stop offset="1" class="dn3mfnbou"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mina-background" /></template>
<style>
.dn3mfnbou {
  stop-color: var(--svg-color--8e7df2, #8e7df2);
}

.dpr1be7tb {
  stop-color: var(--svg-color--ce5937, #ce5937);
}

.el7om1bfm {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.248c.902.037 1.175-.775 1.397-1.505c.053-.176.105-.346.162-.493c1.009-.306 1.674-1.181 1.846-2.515l1.122-7.986c.418-.068 1.142.055 1.473.146V18.75h2V9.246c0-1.325-.42-2.333-1.5-2.722v-.557c0-.728-.62-1.217-1.27-1.217s-1.157.408-1.263 1.15l-.08.473c-1.18.334-1.789 1.403-1.989 2.951l-.911 7.522q-.489.094-.987.081a4.6 4.6 0 0 1-.987-.081l-.911-7.522c-.2-1.548-.845-2.607-2.024-2.942L8.033 5.9c-.107-.742-.614-1.15-1.263-1.15c-.65 0-1.27.489-1.27 1.217v.561C4.42 6.918 4 7.926 4 9.25v9.5h2V6.94c.471-.156.98-.225 1.473-.145l1.122 7.94c.172 1.334.837 2.209 1.845 2.515c.059.147.11.317.163.493c.221.73.495 1.541 1.397 1.505m0-1.751a5 5 0 0 1-.893-.067c.075.582.21 1.24.893 1.327c.682-.087.818-.745.893-1.327q-.444.073-.893.067m-6.5.753h-1v-9c0-1.124.461-1.744 1-2.079zM8.078 6.908c.79.289 1.25 1.005 1.42 2.341l.868 7.365c-.862-.625-.995-.783-1.14-1.92zM6 6.381V5.97c0-.525.426-.72.77-.72c.253 0 .623.13.703.686l.027.314c-.5-.064-1.013.013-1.5.131m12.5 11.87h1V9.248c0-1.123-.461-1.797-1-2.131zM15.887 6.894c-.79.29-1.215 1.018-1.386 2.355l-.867 7.365c.861-.625.995-.783 1.14-1.92zM18 6.347V5.97c0-.525-.426-.72-.77-.72c-.253 0-.624.13-.703.686l-.063.318A4.3 4.3 0 0 1 18 6.347");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q5aca_buc {
  stop-color: var(--svg-color--e37b44, #e37b44);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.yhbg5lb8l {
  stop-color: var(--svg-color--c2e0f4, #c2e0f4);
}

</style>
