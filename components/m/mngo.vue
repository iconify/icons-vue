<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGqAnuMdEP)" class="v4f2tactu"/><path fill="url(#SVGfyvM9dAJ)" class="d2b9pobdf"/><path fill="url(#SVGlmKthcdp)" class="eid7s0bmh"/><path fill="url(#SVGRlgdXbjS)" class="fb15fxdqz"/><path fill="url(#SVGTkb9Zcze)" class="i349yp78e"/><path fill="url(#SVG08izfclP)" class="k_z7v2bbi"/><path class="s5lt1_u2x"/><defs><linearGradient id="SVGqAnuMdEP" x1="1.31" x2="20.571" y1="16.895" y2="13.349" gradientUnits="userSpaceOnUse"><stop offset=".21" class="kwj85acaa"/><stop offset=".84" class="rrlvibb7d"/></linearGradient><linearGradient id="SVGfyvM9dAJ" x1="5.818" x2="19.353" y1="11.983" y2="12.093" gradientUnits="userSpaceOnUse"><stop offset=".4" class="rrlvibb7d"/><stop offset="1" class="tsp75n4iy"/></linearGradient><linearGradient id="SVGlmKthcdp" x1="2.911" x2="14.209" y1="21.319" y2="3.671" gradientUnits="userSpaceOnUse"><stop offset=".16" class="kwj85acaa"/><stop offset=".84" class="rrlvibb7d"/></linearGradient><linearGradient id="SVGRlgdXbjS" x1="13.048" x2="12.765" y1="4.919" y2="19.77" gradientUnits="userSpaceOnUse"><stop class="rrlvibb7d"/><stop offset=".76" class="kwj85acaa"/></linearGradient><linearGradient id="SVGTkb9Zcze" x1="15.121" x2="13.356" y1="4.121" y2="15.734" gradientUnits="userSpaceOnUse"><stop offset=".16" class="rrlvibb7d"/><stop offset="1" class="kwj85acaa"/></linearGradient><linearGradient id="SVG08izfclP" x1="5.252" x2="22.922" y1="4.276" y2="6.35" gradientUnits="userSpaceOnUse"><stop offset=".15" class="u6b9znbqb"/><stop offset="1" class="tsp75n4iy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mngo" /></template>
<style>
.d2b9pobdf {
  d: path("M15.679 18.784A5.4 5.4 0 0 1 15.302 21c1.822-.045 3.73-.562 4.218-2.503c.102-.416.113-.866-.056-1.254c-.168-.377-.489-.67-.776-.973a7 7 0 0 1-.731-.929c-1.227.507-2.374 1.52-2.278 3.443");
}

.eid7s0bmh {
  d: path("M16.5 11.96c-.28-.73-.517-1.473-.877-2.16a8.8 8.8 0 0 0-1.631-2.097a5.3 5.3 0 0 1-2.424-.518c-.788 1.091-1.677 2.936-.861 5.04c1.21 3.11-1.237 5.237-2.812 6.553l.078.056q.442.04.883-.01c2.082-.209 3.887-1.632 4.782-3.725c.81-1.9 1.985-2.62 2.941-2.868z");
}

.fb15fxdqz {
  d: path("M6.223 7.821a7.14 7.14 0 0 0-1.817 4.888a6.54 6.54 0 0 0 .957 3.297c2.53-2.492 1.62-6.21.86-8.185");
}

.ft5dv1b6b {
  fill: none;
}

.i349yp78e {
  d: path("M10.751 12.224c-.815-2.11.057-3.937.833-5.029a4.4 4.4 0 0 1-1.345-1.046a5.4 5.4 0 0 0-4.106 1.76c.743 1.936 1.637 5.57-.832 8.005a9.8 9.8 0 0 0 2.638 2.897c1.57-1.317 4.022-3.476 2.812-6.581z");
}

.k_z7v2bbi {
  d: path("M13.8 4.951c1.71.664 2.908.844 3.78.816l.023-.017c-3.235-5.422-7.47-1.153-7.47-1.153l.006.011a6.86 6.86 0 0 1 3.656.338z");
}

.kwj85acaa {
  stop-color: var(--svg-color--e54033, #e54033);
}

.rrlvibb7d {
  stop-color: var(--svg-color--feca1a, #feca1a);
}

.s5lt1_u2x {
  fill: var(--svg-color--afd803, #afd803);
  d: path("M13.824 4.912c-1.424-.551-2.757-.529-3.685-.304c2.436 4.19 7.06 1.395 7.436 1.159c-.866.028-2.041-.191-3.751-.855");
}

.tsp75n4iy {
  stop-color: var(--svg-color--afd803, #afd803);
}

.u6b9znbqb {
  stop-color: var(--svg-color--6cbf00, #6cbf00);
}

.v4f2tactu {
  d: path("M13.576 15.115c-.89 2.098-2.6 3.488-4.675 3.696c-.045 0-.618.05-.928.028a12.45 12.45 0 0 0 5.366 2.059a17 17 0 0 0 2.025.095a5.2 5.2 0 0 0 .355-2.194c-.096-1.923 1.04-2.913 2.272-3.42a12.3 12.3 0 0 1-1.423-3.206c-.962.253-2.182 1.04-2.987 2.942z");
}

</style>
