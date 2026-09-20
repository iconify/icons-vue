<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGCwxsucJm" cx="75.424" cy="-61.613" r="183.963" gradientUnits="userSpaceOnUse"><stop offset=".532" class="bx9kipbhg"/><stop offset=".615" class="bxsz06bjc"/><stop offset=".696" class="q4t_hfqeb"/><stop offset=".739" class="e4i1t933y"/><stop offset=".793" class="v9v3zjbmp"/><stop offset=".839" class="ph03dtbxc"/><stop offset=".883" class="m7dbgmbro"/><stop offset=".925" class="xikl8zr0d"/><stop offset=".962" class="gohlk-bvx"/></radialGradient><path fill="url(#SVGCwxsucJm)" class="ad4a84dng"/><path class="b1rs0sbvi"/><path class="vd4si2xub"/><path class="nfz0bkbxp"/><path class="zjrmyvdje"/><path class="qgwreab-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:mango" /></template>
<style>
.ad4a84dng {
  d: path("M4.03 89.43c-1.2 6.01 5.66 29.12 41.45 33.74c18.39 2.37 36.45-4.16 50.75-15.11S119.3 83 122.31 70.11c4.63-19.85-.69-49.82-40.06-51.59c-40.26-1.81-53.79 40.28-62.23 52.65C9.86 86.08 5.12 84 4.03 89.43");
}

.b1rs0sbvi {
  fill: var(--svg-color--dc0d27, #dc0d27);
  d: path("M41.89 36.33s13.57 6.9 34.61 5.44c17.03-1.18 23.73-9.54 23.73-9.54s7.49 2.06 12.46.74c1.99-.53 2.42-1.61-.01-4.13c-3.67-3.82-16.27-10.89-34.85-9.7c-23.25 1.51-35.94 17.19-35.94 17.19");
}

.bx9kipbhg {
  stop-color: var(--svg-color--f33a1f, #f33a1f);
}

.bxsz06bjc {
  stop-color: var(--svg-color--f86922, #f86922);
}

.e4i1t933y {
  stop-color: var(--svg-color--ffa025, #ffa025);
}

.gohlk-bvx {
  stop-color: var(--svg-color--aaa61c, #aaa61c);
}

.m7dbgmbro {
  stop-color: var(--svg-color--dfa222, #dfa222);
}

.nfz0bkbxp {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M102.36 24.98c-.68 2.97 2.05 5.05 3.94 6.54s6.15 2.05 7.57 1.02c1.42-1.02-.16-4.02.87-5.83c1.02-1.81 2.84-4.02.63-5.52c-1.85-1.26-4.34-1.73-6.62-1.26s-2.29 2.21-3.23 2.68c-.96.48-2.93 1.35-3.16 2.37");
}

.ph03dtbxc {
  stop-color: var(--svg-color--f1a124, #f1a124);
}

.q4t_hfqeb {
  stop-color: var(--svg-color--fd9124, #fd9124);
}

.qgwreab-o {
  fill: var(--svg-color--366918, #366918);
  d: path("M50.46 24.92c.37.46 7.35.72 11.24.59c8.88-.29 15.91-2.65 24.66-3.63s16.38 0 16.67-.34c.53-.62-4.84-7.92-22.41-5.95c-6.47.73-14.79 4.02-20.53 6.31c-3.66 1.49-9.98 2.58-9.63 3.02");
}

.v9v3zjbmp {
  stop-color: var(--svg-color--fca025, #fca025);
}

.vd4si2xub {
  fill: var(--svg-color--ffebc9, #ffebc9);
  d: path("M26.04 76.62c2.36 3.93 9.35-1.14 14.27-6.07c7.1-7.12 10.33-13.64 12.22-16.95s4.45-10.44-.71-11.59c-5.37-1.19-6.96 5.45-9.72 10.34s-6.6 10.71-9.68 14.5c-3.27 4.03-7.78 7.44-6.38 9.77");
}

.xikl8zr0d {
  stop-color: var(--svg-color--c7a41f, #c7a41f);
}

.zjrmyvdje {
  fill: var(--svg-color--518e30, #518e30);
  d: path("M100.14 25.88c-2.52 1.1-9.94 6.95-27.26 8.28c-19.1 1.47-41.53-.8-45.27-1.33s-10.12-.78-10.03-2.38c.13-2.4 2.61-1.63 7.61-3.07c6.01-1.74 12.15-4.14 16.83-6.94c7.18-4.31 21.8-15.09 36.19-15.36c15.76-.29 20.83 4.67 24.7 8.81s3.93 8.48 2.86 10.22c-1.06 1.74-2.56.44-5.63 1.77");
}

</style>
