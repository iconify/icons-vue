<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ovajgiquf"/><path class="l_3124bcr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pgx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l_3124bcr {
  fill: var(--svg-color--000, #000);
  d: path("M4.43 15.56c.381-.443 1.558-.98 3.611-.98h3.742c2.735.005 8.205-1.362 8.205-5.836c.134-1.496-.744-4.484-5.336-4.484S8.315 5.632 7.53 7.113l-3.344 8.314a.136.136 0 0 0 .129.185c.046 0 .087-.02.113-.051m4.731-3.89l1.15-3.194a.4.4 0 0 1 .063-.104c.31-.366 1.708-1.016 3.06-1.016h.067c1.734 0 3.4 0 3.4 1.352c0 1.373-1.996 2.776-4.5 2.776h-2.218c-.392 0-.723.103-.913.155zm-.339 7.534c-.273.619-.835.531-1.176.531c-3.096 0-3.715-1.207-3.638-1.816c.666-2.384 5.16-2.307 5.744-2.307c.47 0 .474.34.418.516z");
}

.ovajgiquf {
  fill: var(--svg-color--03edae, #03edae);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
