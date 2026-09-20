<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gtgmjbcgs"/><path class="aw7f6pvyq"/><path clip-rule="evenodd" class="y9cegcu0k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:png-background" /></template>
<style>
.aw7f6pvyq {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.163 7.766l-.415 1.27l2.636 1.92l-2.094 1.516l-2.466-1.803l.94-2.903zm.489 0l2.113 1.538v1.356l-2.47-1.798zm-.353 5.275l-.005.019l2.47 1.797v-3.609L9.3 13.036zm.452.927l2.01 1.463h.004v1.746l-2.47-1.797l.46-1.412zm5.087-6.202h1.397l.942 2.913l-2.471 1.793l-2.08-1.52l2.626-1.906zm-2.603 1.538l2.118-1.538l.353 1.096l-2.47 1.793V9.3zm2.466 3.737l-2.461-1.788h-.005v3.604l2.471-1.797zm-2.466 2.395l2.014-1.463l.457 1.411l-2.47 1.793v-1.745z");
}

.ft5dv1b6b {
  fill: none;
}

.gtgmjbcgs {
  fill: var(--svg-color--ffc800, #ffc800);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y9cegcu0k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
