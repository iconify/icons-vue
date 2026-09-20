<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGNziG0AKJ)" class="r4i437pya"/><path class="e_7v534pk"/><path clip-rule="evenodd" class="isyhkdbji"/></g><defs><linearGradient id="SVGNziG0AKJ" x1="8.771" x2="12.461" y1="9.09" y2="15.772" gradientUnits="userSpaceOnUse"><stop offset=".03" class="hfn4j9bst"/><stop offset=".69" class="km_rl6s3m"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mav-background" /></template>
<style>
.e_7v534pk {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.287 10.457v-.004c-.113.33-.381 1.153-.598 1.835c-.654 1.925-1.407 2.537-1.69 2.537c-.305 0-1.025-.612-1.693-2.542L9.92 11.07l-.918-2.804a.5.5 0 0 1 .16-.029c.532 0 1.021.866 1.675 2.015l.316.555l.188.353c.259.494.461.828.659.842c.197-.014.4-.348.659-.847l.188-.348l.315-.555c.654-1.149 1.144-2.015 1.676-2.015q.085 0 .164.029zm.193.66c.193.686.419 1.576.461 2.089c.047.456.094.903.141 1.233c.033.24.236.414.48.414h1.417a.197.197 0 0 0 .197-.221c-.282-1.92-.95-5.177-1.835-6.127l-.861 2.616zm-7.657 3.52c.283-1.925.956-5.187 1.845-6.132l.852 2.607c-.188.691-.419 1.58-.461 2.098a35 35 0 0 1-.141 1.233a.48.48 0 0 1-.48.415H7.02a.194.194 0 0 1-.192-.138a.2.2 0 0 1-.006-.084");
}

.ft5dv1b6b {
  fill: none;
}

.hfn4j9bst {
  stop-color: var(--svg-color--d3606c, #d3606c);
}

.isyhkdbji {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.47a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06");
}

.km_rl6s3m {
  stop-color: var(--svg-color--5b7cfd, #5b7cfd);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
