<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGLJNmnbWt)" clip-rule="evenodd" class="q1wokqu6q"/><defs><linearGradient id="SVGLJNmnbWt" x1="4.787" x2="18.992" y1="7.923" y2="18.383" gradientUnits="userSpaceOnUse"><stop offset=".058" class="kucuuvb3c"/><stop offset=".306" class="xxyb1jwcz"/><stop offset=".819" class="pdtx7rblb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rari" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kucuuvb3c {
  stop-color: var(--svg-color--2568ff, #2568ff);
}

.pdtx7rblb {
  stop-color: var(--svg-color--ff74f2, #ff74f2);
}

.q1wokqu6q {
  fill-rule: evenodd;
  d: path("M3 5.25h14.39c1.994 0 3.61 1.605 3.61 3.586a3.59 3.59 0 0 1-2.003 3.212c1.186.578 2.003 1.779 2.003 3.166q0 .163-.015.322H21v3.214h-5.143v-3.424c0-.594-.545-1.076-1.217-1.076H8.143v4.5H3zm11.893 3.214h-6.75v1.929h6.75c.414 0 .964-.432.964-.964c0-.533-.55-.965-.964-.965");
}

.xxyb1jwcz {
  stop-color: var(--svg-color--5e9afe, #5e9afe);
}

</style>
