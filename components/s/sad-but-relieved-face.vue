<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGhPFEudra" cx="64" cy="-1752" r="56.96" fx="64" fy="-1752" gradientTransform="matrix(1 0 0 -1 0 -1688)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGsViJTgyo" cx="20.59" cy="554.48" r="33.4" fx="20.59" fy="554.48" gradientTransform="matrix(1 0 0 1.54 0 -790.73)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="ruwj0vb6x"/><stop offset=".51" class="x3uwub1ak"/><stop offset=".87" class="jj-ds7b-i"/><stop offset="1" class="eljssxb3r"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGhPFEudra)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path fill="url(#SVGsViJTgyo)" class="oef5m6blm"/><path class="l-pv99bqf"/><path class="n2j_f8ibk"/><path class="z5vop3bjd"/><path class="w-lytrods"/><path class="ozvri7bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sad-but-relieved-face" /></template>
<style>
.eljssxb3r {
  stop-color: var(--svg-color--2489d6, #2489d6);
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.jj-ds7b-i {
  stop-color: var(--svg-color--2b94db, #2b94db);
}

.l-pv99bqf {
  fill: var(--svg-color--a1ebff, #a1ebff);
  d: path("M9.27 94.88c1.84 4.62 6.37 3.39 7.29-.93c.69-3.24-1-12.52-1.67-14.32s-2.47-1.39-3.35.93c-.74 1.94-4.09 9.74-2.26 14.32Z");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.n2j_f8ibk {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M64 88.25c10.82 0 17.83 7.92 19.65 11.57c.7 1.41.74 2.58.14 3.13c-.46.41-1.21.4-2.08.01c-.29-.13-.59-.31-.9-.52c-4.76-3.34-10.72-5.41-16.84-5.4c-6.08.01-12.02 2.07-16.77 5.4c-.3.21-.61.39-.9.52c-.87.4-1.63.41-2.08-.01c-.6-.55-.56-1.72.14-3.13c1.81-3.64 8.82-11.57 19.64-11.57M27.12 40.87c-2.2.39-2.31 3.59.09 3.7c4.9.12 10.21-1.66 14.32-5.45c1.5-1.29 2.81-2.89 3.72-4.49c1.21-2.2-1.59-3.71-2.99-2.11l-.1.1c-4.02 4.49-9.53 7.37-15.03 8.24Zm58.73-8.25l-.1-.1c-1.41-1.59-4.2-.08-2.99 2.11c.91 1.6 2.21 3.19 3.72 4.49c4.11 3.78 9.42 5.57 14.32 5.45c2.4-.11 2.29-3.31.09-3.7c-5.5-.88-11.01-3.76-15.03-8.24ZM44.67 56.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.oef5m6blm {
  d: path("M19.52 107.26c-8.46 0-14.97-8.2-14.97-15.23c0-4.95 2.21-10.68 5.34-18.62c.39-1.17.91-2.34 1.43-3.65c1.49-3.72 2.81-7.75 4.81-11.24c1.36-2.38 4.83-2.38 6.14.03c1.86 3.43 3.14 7.14 5.07 11.47c5.47 12.24 7.03 17.18 7.03 22.13c.13 6.9-6.51 15.1-14.84 15.1Z");
}

.ozvri7bkr {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.63 59.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.ruwj0vb6x {
  stop-color: var(--svg-color--44b7eb, #44b7eb);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.w-lytrods {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.02 56.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.x3uwub1ak {
  stop-color: var(--svg-color--3dade6, #3dade6);
}

.z5vop3bjd {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.28 59.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

</style>
