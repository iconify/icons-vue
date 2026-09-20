<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pde511gmx"><path class="xjcdfabvw"/><path class="o67z0nb9l"/><path class="so3http2i"/><path clip-rule="evenodd" class="skod6iu8v"/><path class="nrzivwbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:poolx" /></template>
<style>
.nrzivwbdn {
  d: path("M18.311 17.315L7.81 4.012l.883-.698l10.502 13.298l-.884.697z");
}

.o67z0nb9l {
  d: path("m20.466 10.11l-11.24 2.475l-5.889-2.498l.44-1.035l5.551 2.363l10.89-2.396l.242 1.096z");
}

.pde511gmx {
  fill: var(--svg-color--181b1e, #181b1e);
}

.skod6iu8v {
  fill-rule: evenodd;
  d: path("M8.524 4.125L4.215 9.733l1.547 6.846l6.244 3.161l6.322-3.161l1.463-6.83l-4.4-5.624zM15.937 3h-7.97L3 9.469l1.783 7.875L12 21l7.312-3.656L21 9.469z");
}

.so3http2i {
  d: path("M11.448 20.224L15.015 3.63l1.096.236l-3.56 16.594z");
}

.xjcdfabvw {
  d: path("M5.081 16.528L15.307 3.31l.89.691l-10.222 13.22l-.888-.693z");
}

</style>
