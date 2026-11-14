<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="amtaj-x2u"/><path class="u3-2zab6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medication-trolley" /></template>
<style>
.amtaj-x2u {
  d: path("M2.5 3.5h2V15h8.7m4.3-2.8V8.5h-13");
}

.u3-2zab6m {
  d: path("M3.75 16.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm9.451-.979q-.121-.178-.28-.322q-.16-.143-.35-.244t-.398-.153T11.75 15q-.086 0-.172.008t-.169.026q-.085.016-.167.041t-.162.058q-.079.033-.155.074t-.147.088q-.072.048-.138.102q-.067.055-.127.116q-.061.06-.116.127q-.054.066-.102.138q-.048.071-.088.147q-.041.076-.074.155q-.033.08-.058.162t-.041.167q-.017.084-.026.169T10 16.75q0 .086.008.172t.026.169q.016.085.041.167t.058.162t.074.155t.088.147q.048.072.102.138q.055.067.116.127q.06.061.127.116q.066.054.138.102q.071.048.147.088q.076.041.155.074q.08.033.162.058t.167.041t.169.026q.086.008.172.008q.215 0 .423-.052q.209-.052.399-.153q.189-.101.349-.245q.16-.143.28-.321M16 15h5.5m-5 2.75H21v4h-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
