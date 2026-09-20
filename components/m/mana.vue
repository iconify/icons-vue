<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG405vMwoP)" class="hgjrwr8yo"/><path class="rsu439c7m"/><path class="ofcp-b6qg"/><path class="vgwee0bec"/><path fill="url(#SVGm1GdcdDA)" class="s9y0whgwx"/><path class="wreyv_s5z"/><path class="p61-t_b5h"/><defs><linearGradient id="SVG405vMwoP" x1="12.287" x2="12.287" y1="3.01" y2="20.991" gradientUnits="userSpaceOnUse"><stop class="p3e3q7b0d"/><stop offset="1" class="sylo0lm-i"/></linearGradient><linearGradient id="SVGm1GdcdDA" x1="11.995" x2="11.995" y1="3.01" y2="20.99" gradientUnits="userSpaceOnUse"><stop class="p3e3q7b0d"/><stop offset="1" class="sylo0lm-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mana" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hgjrwr8yo {
  d: path("M9.206 6.863v7.706h6.637z");
}

.ofcp-b6qg {
  fill: var(--svg-color--ff2d55, #ff2d55);
  d: path("M6.251 19.064a10.7 10.7 0 0 0 6.165 1.926c2.312 0 4.449-.717 6.165-1.926z");
}

.p3e3q7b0d {
  stop-color: var(--svg-color--a524b3, #a524b3);
}

.p61-t_b5h {
  fill: var(--svg-color--ffc95b, #ffc95b);
  d: path("M16.29 9.688a2.568 2.568 0 1 0 0-5.137a2.568 2.568 0 0 0 0 5.137m-7.084-4.11a1.284 1.284 0 1 0 0-2.568a1.284 1.284 0 0 0 0 2.568");
}

.rsu439c7m {
  fill: var(--svg-color--fff, #fff);
  d: path("M3 14.569h6.206V6.863z");
}

.s9y0whgwx {
  d: path("M16.29 12v5.78H21z");
}

.sylo0lm-i {
  stop-color: var(--svg-color--ff2d55, #ff2d55);
}

.vgwee0bec {
  fill: var(--svg-color--ffbc5b, #ffbc5b);
  d: path("M3 14.57c.32.687.722 1.334 1.197 1.926H15.93v-1.927z");
}

.wreyv_s5z {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.584 17.78h4.706V12z");
}

</style>
