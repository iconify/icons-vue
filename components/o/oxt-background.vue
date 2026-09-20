<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uvuu0423j"/><path class="v_h865b9h"/><path class="vpa9m5bib"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oxt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uvuu0423j {
  fill: var(--svg-color--5f45ba, #5f45ba);
  d: path("M24 0H0v24h24z");
}

.v_h865b9h {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.982 6.075a.913.913 0 1 1-1.586-.904a.913.913 0 0 1 1.586.904m-2.707.114a.686.686 0 1 1-1.178-.703a.686.686 0 0 1 1.178.703m8.258 13.066a7.303 7.303 0 0 0 1.045-14.314a7.3 7.3 0 0 0-2.862-.18c-.967.077-1.78.447-1.78.447c-.667.32-1.096.862-1.096 1.588c0 .94.735 1.52 1.676 1.52c.16 0 .703-.173.83-.214a3.9 3.9 0 0 1 1.544-.21c2.56 0 3.894 2.1 3.894 4.355s-1.616 3.863-4.406 3.863c-2.447 0-3.72-2.434-3.812-4.657C8.534 10.54 8 9.828 7.078 9.828a1.71 1.71 0 0 0-1.648 1.26a7.305 7.305 0 0 0 8.103 8.167");
}

.vpa9m5bib {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.037 8.704a1.142 1.142 0 1 1-1.963-1.169a1.142 1.142 0 0 1 1.963 1.17");
}

</style>
