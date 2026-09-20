<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGfNrTEc9c)" class="p82novbhb"/><path fill="url(#SVGNOgFdecD)" class="mydrw247r"/><defs><linearGradient id="SVGfNrTEc9c" x1="2.998" x2="19.05" y1="12.163" y2="12.092" gradientUnits="userSpaceOnUse"><stop class="cl8wg8bua"/><stop offset="1" class="xofk90tyd"/></linearGradient><linearGradient id="SVGNOgFdecD" x1="3.001" x2="19.05" y1="15.425" y2="15.319" gradientUnits="userSpaceOnUse"><stop class="ap_9dsxlc"/><stop offset="1" class="cou61vb0d"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:para" /></template>
<style>
.ap_9dsxlc {
  stop-color: var(--svg-color--fecf7b, #fecf7b);
}

.cl8wg8bua {
  stop-color: var(--svg-color--02daff, #02daff);
}

.cou61vb0d {
  stop-color: var(--svg-color--ef26a8, #ef26a8);
}

.ft5dv1b6b {
  fill: none;
}

.mydrw247r {
  d: path("m5.622 12.58l6.377 3.374c.422.225.939.225 1.35-.017l4.909-2.828l1.816.978a1.698 1.698 0 0 1 0 3.02l-6.883 3.728a1.32 1.32 0 0 1-1.27 0l-7.997-4.313a1.697 1.697 0 0 1-.006-3.02z");
}

.p82novbhb {
  d: path("m3.923 9.87l7.996 4.318c.394.214.878.214 1.271 0l6.889-3.728a1.7 1.7 0 0 0 0-3.02L12.206 3.2a1.64 1.64 0 0 0-1.563 0L3.917 6.855a1.698 1.698 0 0 0 0 3.014z");
}

.xofk90tyd {
  stop-color: var(--svg-color--5414f1, #5414f1);
}

</style>
