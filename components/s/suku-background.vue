<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s6zil6f4v"/><path class="jx6zqsbey"/><path class="ns_k4bbdb"/><path class="r-n5e4bhn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:suku-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jx6zqsbey {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.41 16.586c.065-.25.098-.51.096-.77a2.3 2.3 0 0 0-.407-1.214c-.604-.891-1.702-1.3-2.644-1.676a29 29 0 0 1-.637-.254l-.932.68c-.42.309-.842.632-1.403 1.062c-.627.478-1.332 1.12-1.59 1.88a2.77 2.77 0 0 0 .37 2.542l.033-.026l-.035.026c.252.367.59.665.983.868c.392.203.828.304 1.27.295c.792-.007 1.615-.479 2.26-.934a180 180 0 0 0 2.426-1.756q.07-.175.118-.358c.033-.12.067-.25.097-.374");
}

.ns_k4bbdb {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.411 16.587c.064-.25.097-.51.095-.77a2.3 2.3 0 0 0-.407-1.214c-.604-.892-1.702-1.3-2.644-1.676c-.332-.13-.665-.26-.99-.407a8.9 8.9 0 0 1-2.446-1.629C5.833 8.79 7.089 5.197 9.587 4.05c.381-.175.363.142.285.435c-.368 1.395.807 2.924 1.906 3.518c1.43.774 2.996 1.197 4.22 2.341c1.1 1.028 1.614 2.802 1.008 4.232c-.322.76-.915 1.359-1.564 1.833l-1.242.907q.072-.176.118-.359c.033-.12.068-.249.097-.373");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r-n5e4bhn {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.411 16.586c.064-.25.097-.51.095-.77a2.3 2.3 0 0 0-.407-1.214c-.604-.891-1.702-1.3-2.644-1.676a32 32 0 0 1-.638-.254l-.93.68c.964.407 2.01.8 2.812 1.51c.723.64 1.202 1.523 1.503 2.449q.071-.175.118-.36c.033-.12.067-.249.097-.373");
}

.s6zil6f4v {
  fill: var(--svg-color--a7bf2e, #a7bf2e);
  d: path("M24 0H0v24h24z");
}

</style>
