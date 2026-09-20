<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwuuvwbzr"/><path class="r6id0zbnx"/><path class="d2bvmxmlz"/><path fill="url(#SVG2QH2qc0z)" clip-rule="evenodd" class="u4q2cccbu"/><path fill="url(#SVGHftjheTj)" clip-rule="evenodd" class="u3ozd10bw"/><defs><linearGradient id="SVG2QH2qc0z" x1="16.175" x2="10.401" y1="10.109" y2="15.851" gradientUnits="userSpaceOnUse"><stop class="lv5oa4vqb"/><stop offset=".817" class="xs076xski"/></linearGradient><linearGradient id="SVGHftjheTj" x1="9.84" x2="14.306" y1="14.649" y2="10.948" gradientUnits="userSpaceOnUse"><stop class="yek7wiboa"/><stop offset="1" class="faq-wij2e"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pros" /></template>
<style>
.d2bvmxmlz {
  fill: var(--svg-color--5901f6, #5901f6);
  d: path("M21 3L3 21V3z");
}

.faq-wij2e {
  stop-color: var(--svg-color--01fdfe, #01fdfe);
  stop-opacity: 0.06;
}

.ft5dv1b6b {
  fill: none;
}

.kwuuvwbzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 3H3v18h18z");
}

.lv5oa4vqb {
  stop-color: var(--svg-color--fbfcfa, #fbfcfa);
}

.r6id0zbnx {
  fill: var(--svg-color--333, #333);
  d: path("M3 3h18v18H3z");
}

.u3ozd10bw {
  fill-rule: evenodd;
  d: path("m14.69 9.286l.036.034c2.4 2.402 3.137 5.558 1.645 7.05s-4.648.755-7.049-1.646l-.02-.021l.867-.872l.023.024c1.91 1.91 4.28 2.639 5.29 1.627c1.013-1.012.284-3.381-1.626-5.292l-.033-.033z");
}

.u4q2cccbu {
  fill-rule: evenodd;
  d: path("m9.31 14.713l-.036-.034c-2.4-2.402-3.137-5.558-1.645-7.05s4.648-.756 7.049 1.645l.02.022l-.867.872l-.023-.024c-1.91-1.91-4.28-2.64-5.291-1.627c-1.012 1.012-.283 3.381 1.627 5.292l.033.033z");
}

.xs076xski {
  stop-color: var(--svg-color--9359fd, #9359fd);
  stop-opacity: 0.07;
}

.yek7wiboa {
  stop-color: var(--svg-color--01fdfe, #01fdfe);
}

</style>
