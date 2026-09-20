<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGqs0gaejl" cx="64" cy="62.9" r="56.96" fx="64" fy="62.9" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><clipPath id="SVGGPZ1Yb5H"><path class="wpg8al5vc"/></clipPath></defs><g class="wj4kgr0on"><path fill="url(#SVGqs0gaejl)" class="vx4yod9me"/><path class="krzinnb4c"/></g><g class="wj4kgr0on"><circle class="dmhae1ygm"/><path class="hg2g-8bjp"/></g><g clip-path="url(#SVGGPZ1Yb5H)"><path class="t3a5v43jg"/></g><g class="wj4kgr0on"><path class="q54gfqbvu"/><path class="d969aecmc"/></g><path class="pmoahgrwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:winking-face-with-tongue" /></template>
<style>
.d969aecmc {
  fill: var(--svg-color--ab3f2e, #ab3f2e);
  d: path("M64.72 106.25c1.1 0 1.99-.89 1.99-1.99V85c-.91.01-1.81.03-2.73.03c-.42 0-.84 0-1.26-.01v19.24c0 1.1.89 1.99 1.99 1.99Z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.dmhae1ygm {
  cx: 84.01px;
  cy: 53.75px;
  r: 17.44px;
  fill: var(--svg-color--fff, #fff);
}

.hg2g-8bjp {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M84.76 46.15c-4.13 0-7.48 2.45-7.48 7.6s3.35 7.6 7.48 7.6s7.48-2.45 7.48-7.6s-3.35-7.6-7.48-7.6M54.01 56.89s-.05-.09-.15-.25c-2.31-3.57-6.44-6.62-10.28-8.84c-3.5-1.98-8.03-3.84-11.85-4.2c-1.56-.23-3.16-.03-3.71 1.63c-.42 1.29.29 2.68 1.58 3.1c.4.13.3.1 1.13.36c1.73.58 3.89 1.55 5.86 2.53c1.46.75 2.87 1.48 4.34 2.34c-.45.04-.9.08-1.35.14c-.88.14-1.74.3-2.58.51c-2.97.75-5.9 2.14-8.05 4.08c-1.44 1.34-3.27 3.1-1.9 5.04c1 1.31 2.72 1.25 3.88.17c2.21-1.69 5.53-2.87 8.48-3.38c3.18-.57 6.69-.62 9.68.15c.51.13.82.24 1.2.35c1.69 1.03 3.91.18 4.03-1.9c.13-.6.05-1.26-.3-1.83Z");
}

.krzinnb4c {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 29.67c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 110.52 44.81 118.8 64 118.8c15.4 0 29.8-5.2 40.4-14.5C115.9 94.1 122 79.8 122 62.9c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.pmoahgrwk {
  fill: var(--svg-color--ab3f2e, #ab3f2e);
  d: path("M66.71 85h-3.99c-5.73 0-11.38-.27-16.81-.72v3.55c4.74 1.07 18.8 3.48 37.61-.22v-3.46c-5.42.49-11.06.78-16.81.85");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.q54gfqbvu {
  fill: var(--svg-color--ff4081, #ff4081);
  d: path("M66.71 85c-.91.01-1.81.03-2.73.03c-.42 0-.84 0-1.26-.01c-5.73-.03-11.38-.27-16.81-.72v24.58c0 9.48 7.69 17.17 17.17 17.17h3.27c9.48 0 17.17-7.69 17.17-17.17V84.17c-5.42.49-11.06.77-16.81.84Z");
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.t3a5v43jg {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M63.99 80.43c-12.68 0-24.48-1.06-34.31-2.88c-2.44-.45-4.6 1.69-4.1 4.12c3.27 16 19.02 29.13 38.4 29.13c21.21 0 35.49-13.57 38.45-29.19c.46-2.41-1.69-4.52-4.11-4.07c-9.84 1.82-21.64 2.89-34.33 2.89");
}

.vx4yod9me {
  d: path("M64 118.8c-27.9 0-58-17.5-58-55.9S36.1 7 64 7c15.5 0 29.8 5.1 40.4 14.4C115.9 31.6 122 46 122 62.9s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.wpg8al5vc {
  fill: none;
  stroke-width: var(--svg-stroke-width--0px, 0px);
  d: path("M63.99 80.43c-12.68 0-24.48-1.06-34.31-2.88c-2.44-.45-4.6 1.69-4.1 4.12c3.27 16 19.02 29.13 38.4 29.13c21.21 0 35.49-13.57 38.45-29.19c.46-2.41-1.69-4.52-4.11-4.07c-9.84 1.82-21.64 2.89-34.33 2.89");
}

</style>
