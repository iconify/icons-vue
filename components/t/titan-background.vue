<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGLZrqzdsz)" class="r4i437pya"/><path clip-rule="evenodd" class="o4xlg1b0o"/><path clip-rule="evenodd" class="prrh88f7n"/></g><defs><linearGradient id="SVGLZrqzdsz" x1="4.507" x2="20.086" y1="15.546" y2="8.694" gradientUnits="userSpaceOnUse"><stop class="nk6ojylru"/><stop offset=".782" class="ohmm7omcz"/><stop offset="1" class="pnpu0-_dg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:titan-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nk6ojylru {
  stop-color: var(--svg-color--04d9ff, #04d9ff);
}

.o4xlg1b0o {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.895 12a5.895 5.895 0 0 1-10.27 3.95c-.412.09-.793.164-1.131.222c-.775.085-2.358-.007-2.487-1.054c-.117-.954 1.231-2.186 2.105-2.822a5.895 5.895 0 0 1 10.11-4.41c4.128-.661 4.062 1.013 3.51 1.937c-.479.675-1.111 1.295-1.846 1.862q.009.157.009.315M12 16.21c-.893 0-1.72-.277-2.4-.75q1.618-.45 3.186-1.052l-.766-1.441l-.28.127c-.925.433-3.433 1.347-6.08 1.547c.417-.385 1.378-1.211 2.208-1.663l.034-.007a4.21 4.21 0 0 1 8.179-2.013q-.756.474-1.556.868l-.439.2l.421 1.653q.826-.382 1.618-.832A4.21 4.21 0 0 1 12 16.21m5.523-6.274a6 6 0 0 0-.272-.616c.351-.038.826-.086 1.067-.097c-.15.162-.42.413-.795.713");
}

.ohmm7omcz {
  stop-color: var(--svg-color--445cfe, #445cfe);
}

.pnpu0-_dg {
  stop-color: var(--svg-color--7269ef, #7269ef);
}

.prrh88f7n {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.263 14.947a1.684 1.684 0 1 0 0-3.368a1.684 1.684 0 0 0 0 3.368m0-.842a.842.842 0 1 0 0-1.684a.842.842 0 0 0 0 1.684");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
