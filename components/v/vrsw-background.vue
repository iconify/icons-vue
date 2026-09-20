<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGcI0rvbeS)" class="r4i437pya"/><path class="l45732hoe"/></g><defs><linearGradient id="SVGcI0rvbeS" x1="4" x2="17.642" y1="8.139" y2="8.445" gradientUnits="userSpaceOnUse"><stop class="fwl_qbuqn"/><stop offset="1" class="qjx1lmbms"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vrsw-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fwl_qbuqn {
  stop-color: var(--svg-color--ff6900, #ff6900);
}

.l45732hoe {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.144 12.101c2.315-3.106 4.88-5.628 8.663-6.682a.17.17 0 0 1 .099 0a.2.2 0 0 1 .085.06l.009.03a.19.19 0 0 1-.099.16l-1.035.47c-2.024.94-4.033 3.45-5.285 6.146c-.621 1.336-1.237 2.579-1.844 4.047c-.08.188.065.367.254.371h1.397c.033 0 .024.01.024.029v1.797c0 .033-.01.057-.047.057c-1.718.01-3.803-.005-5.525 0c-.024 0-.047-.033-.056-.047a.1.1 0 0 1-.02-.062V16.75c0-.037.02-.051.052-.051h1.328c.051 0 .098-.029.14-.062a.2.2 0 0 0 .057-.136a.7.7 0 0 0-.056-.292a66.5 66.5 0 0 0-4.292-8.32c-.104-.174-.659-.131-.904-.131A.085.085 0 0 1 4 7.673V5.927q0-.019.014-.033a.05.05 0 0 1 .038-.014h6.047l.014.019v1.783c0 .047-.019.08-.07.08h-.838A.15.15 0 0 0 9.1 7.8a.16.16 0 0 0-.047.108c0 .066.01.127.038.188c.626 1.318 1.27 2.65 1.943 3.996c.033.06.066.06.108.01");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qjx1lmbms {
  stop-color: var(--svg-color--f5430d, #f5430d);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
