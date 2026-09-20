<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGfGDCMeKC)" class="eg8fz-txq"/><path class="w--79edon"/><path class="i3a2sbc2w"/><path class="xk9_33bfc"/><defs><linearGradient id="SVGfGDCMeKC" x1="16.391" x2="15.351" y1="13.116" y2="13.116" gradientUnits="userSpaceOnUse"><stop class="byw4q2bjs"/><stop offset=".967" class="p4uvpgkgk"/><stop offset="1" class="byw4q2bjs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:token-pocket" /></template>
<style>
.byw4q2bjs {
  stop-color: var(--svg-color--2980fe, #2980fe);
}

.eg8fz-txq {
  d: path("M15.35 10.793v4.527a4.6 4.6 0 0 0 .936.117h.032v-3.6a1.04 1.04 0 0 1-.968-1.044");
}

.ft5dv1b6b {
  fill: none;
}

.i3a2sbc2w {
  fill: var(--svg-color--2980fe, #2980fe);
  d: path("M16.39 6.15c-2.545 0-4.61 2.08-4.61 4.644a4.64 4.64 0 0 0 3.57 4.526v-4.526c0-.578.467-1.047 1.04-1.047s1.04.47 1.04 1.047a1.04 1.04 0 0 1-1.04 1.046v3.597q.135 0 .265-.006C19.077 15.29 21 13.269 21 10.794c.003-2.564-2.062-4.644-4.61-4.644");
}

.p4uvpgkgk {
  stop-color: var(--svg-color--6ca8ff, #6ca8ff);
}

.w--79edon {
  fill: var(--svg-color--2980fe, #2980fe);
  d: path("M15.348 10.794H11.78v6.485c0 .307.246.555.55.555h2.467c.304 0 .55-.248.55-.555zm-5.29-4.644H3.55a.55.55 0 0 0-.55.554v2.25c0 .307.246.555.55.555h2.095v7.787c0 .306.246.554.55.554H8.54c.304 0 .55-.248.55-.554V9.509h.959c.92 0 1.667-.754 1.667-1.68a1.66 1.66 0 0 0-1.658-1.679");
}

.xk9_33bfc {
  fill: var(--svg-color--2980fe, #2980fe);
  d: path("M16.39 15.437V11.84q-.037 0-.075-.003v3.6z");
}

</style>
