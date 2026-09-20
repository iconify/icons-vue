<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVG5CN2Iezl" cx="64" cy="808.9" r="56.96" fx="64" fy="808.9" gradientTransform="translate(0 -746)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><clipPath id="SVG0XhsQcnE"><path class="o2idk2bry"/></clipPath><path id="SVG9DVV6cLc" class="bgkarsjlj"/></defs><g class="wj4kgr0on"><path fill="url(#SVG5CN2Iezl)" class="vx4yod9me"/><path class="krzinnb4c"/></g><path class="gd6g0vbrg"/><use href="#SVG9DVV6cLc"/><g clip-path="url(#SVG0XhsQcnE)"><use href="#SVG9DVV6cLc"/></g><g class="wj4kgr0on"><path class="w3gqndbke"/><path class="ycp1ecc3g"/><path class="pmoahgrwk"/></g><path class="agej1zbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:squinting-face-with-tongue" /></template>
<style>
.agej1zbgf {
  fill: var(--svg-color--ab3f2e, #ab3f2e);
  d: path("M64.72 106.25c1.1 0 2-.9 2-2V85h-4v19.24c0 1.1.89 2 1.99 2.01z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.bgkarsjlj {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M63.99 80.43c-11.5.06-22.98-.9-34.31-2.89a3.51 3.51 0 0 0-4.1 2.79c-.08.44-.08.9 0 1.34c3.26 16 19 29.13 38.4 29.13c21.21 0 35.48-13.57 38.45-29.19c.34-1.91-.92-3.73-2.83-4.08c-.42-.08-.86-.07-1.28 0a192.6 192.6 0 0 1-34.33 2.89Z");
}

.gd6g0vbrg {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M31.53 60.38L43.7 58l-12.55-5.18l-.42-.23a4.19 4.19 0 0 1-1.75-5.67c.26-.48.6-.91 1.02-1.27a5.99 5.99 0 0 1 6.88-.3l21.27 13c.52.19.78.77.59 1.28c-.13.35-.44.6-.81.65L35 68.93c-.15 0-.32.11-.48.15c-3 .84-6.33-.88-6.79-3.78c-.33-2.2 1.37-4.25 3.8-4.92m64.94-.25L84.3 57.78l12.55-5.21l.42-.23a4.19 4.19 0 0 0 1.75-5.67c-.26-.48-.6-.91-1.02-1.27a5.99 5.99 0 0 0-6.88-.3l-21.27 13c-.52.19-.78.77-.59 1.28c.13.35.44.6.81.65L93 68.68c.15 0 .32.11.48.15c3 .84 6.33-.88 6.79-3.78c.33-2.2-1.37-4.25-3.8-4.92");
}

.krzinnb4c {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 29.67c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 110.52 44.81 118.8 64 118.8c15.4 0 29.8-5.2 40.4-14.5C115.9 94.1 122 79.8 122 62.9c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.o2idk2bry {
  fill: none;
  stroke-width: var(--svg-stroke-width--0px, 0px);
  d: path("M63.99 80.43c-11.5.06-22.98-.9-34.31-2.89a3.51 3.51 0 0 0-4.1 2.79c-.08.44-.08.9 0 1.34c3.26 16 19 29.13 38.4 29.13c21.21 0 35.48-13.57 38.45-29.19c.34-1.91-.92-3.73-2.83-4.08c-.42-.08-.86-.07-1.28 0a192.6 192.6 0 0 1-34.33 2.89Z");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.pmoahgrwk {
  fill: var(--svg-color--ab3f2e, #ab3f2e);
  d: path("M66.71 85h-3.99c-5.73 0-11.38-.27-16.81-.72v3.55c4.74 1.07 18.8 3.48 37.61-.22v-3.46c-5.42.49-11.06.78-16.81.85");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.vx4yod9me {
  d: path("M64 118.8c-27.9 0-58-17.5-58-55.9S36.1 7 64 7c15.5 0 29.8 5.1 40.4 14.4C115.9 31.6 122 46 122 62.9s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.w3gqndbke {
  fill: var(--svg-color--ff4081, #ff4081);
  d: path("M45.91 87.83v21.02c.01 9.47 7.7 17.15 17.17 17.15h3.27c9.48 0 17.17-7.69 17.17-17.17V87.61c-18.81 3.7-32.87 1.29-37.61.22");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.ycp1ecc3g {
  fill: var(--svg-color--ff4081, #ff4081);
  d: path("M66.71 85h-3.99c-5.73 0-11.38-.27-16.81-.72v3.55c4.74 1.07 18.8 3.48 37.61-.22v-3.46c-5.42.49-11.06.78-16.81.85");
}

</style>
