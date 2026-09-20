<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n5_jfmb-c"/><path class="k0iof-hza"/><path class="v2e2n735q"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rootstock-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k0iof-hza {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.01 8.394a2.195 2.195 0 0 0 2.193-2.197A2.195 2.195 0 0 0 12.01 4a2.195 2.195 0 0 0-2.193 2.197c0 1.213.982 2.197 2.193 2.197");
}

.n5_jfmb-c {
  fill: var(--svg-color--ff9103, #ff9103);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v2e2n735q {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.103 12.987a2.191 2.191 0 0 0-3.288 1.95c.023.972-.85 1.473-1.677.972c-.031-.017-.063-.04-.103-.057c-.834-.469-.834-1.464 0-1.926a2.2 2.2 0 0 0 1.152-1.934v-.048c-.024-.971.85-1.473 1.676-.971a2.18 2.18 0 0 0 2.875-.539a2.2 2.2 0 0 0 .434-1.625a2.191 2.191 0 0 0-4.366.334c.025.97-.85 1.472-1.668.97a2.15 2.15 0 0 0-1.144-.326c-.402 0-.797.11-1.143.318c-.827.494-1.693-.008-1.669-.97A2.2 2.2 0 0 0 8.9 8.006a2.18 2.18 0 0 0-2.477-1.039c-.56.152-1.04.522-1.332 1.028a2.203 2.203 0 0 0 .81 3.001a2.2 2.2 0 0 0 2.232-.024c.827-.502 1.693 0 1.669.971v.048c0 .835.46 1.56 1.152 1.935c.834.469.834 1.464 0 1.926c-.032.015-.064.04-.096.055c-.826.494-1.691-.008-1.668-.97a2.191 2.191 0 0 0-3.289-1.958a2.224 2.224 0 0 0-.801 3.016a2.19 2.19 0 0 0 2.995.805c.016-.009.023-.017.039-.025c.826-.5 1.692 0 1.668.972v.055A2.2 2.2 0 0 0 11.995 20a2.2 2.2 0 0 0 2.192-2.197v-.047c-.023-.972.85-1.473 1.677-.972a.2.2 0 0 1 .047.032a2.19 2.19 0 0 0 2.996-.804c.603-1.074.245-2.42-.804-3.025");
}

</style>
