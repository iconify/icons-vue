<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c0wa_ab7g"/><path class="bgzbpwivi"/><path class="no8uvwrah"/><path class="w-vd2h7jf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mpl-background" /></template>
<style>
.bgzbpwivi {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 5.411c4.41 0 8 1.478 8 3.294c0 1.713-3.021 3.125-7.059 3.294v-.564c.038-1.582.287-1.553 1.6-2.222c.748-.244 1.224-.611 1.224-1.035c0-.739-1.577-1.341-3.53-1.341s-3.53.602-3.53 1.35c0 .302.25.575.688.8c1.36.782 2.136.575 2.136 2.495v.517C7.266 11.933 4 10.484 4 8.705c0-1.816 3.576-3.294 8-3.294");
}

.c0wa_ab7g {
  fill: var(--svg-color--ff7900, #ff7900);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.no8uvwrah {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.59 11.059c.264.31.41.644.41.983c0 .993-.979 1.727-2.823 2.31v-1.364c0-.377.051-.358.409-.499a5 5 0 0 0 2.005-1.43m-3.825 3.764c-1.134.25-2.386.47-3.77.47c-4.41 0-7.995-1.51-7.995-3.242c0-.348.141-.682.41-.978c1.016 1.204 3.731 2.09 7.12 2.15v.424c0 .31.235.706.663.706s.748-.41.748-.706v-.438a16 16 0 0 0 2.513-.268c.174 0 .31.15.31.32z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w-vd2h7jf {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.553 14.354c.287.329.447.691.447 1.058c0 1.75-3.577 3.177-8 3.177c-4.41 0-8-1.426-8-3.177c0-.367.179-.73.47-1.059c1.097 1.238 4.034 1.883 7.516 1.883c1.388 0 2.837 0 3.779-.156v.405c0 .315.244.692.715.692c.47 0 .697-.405.697-.706v-.706c1.185-.367 1.872-.847 2.376-1.412");
}

</style>
