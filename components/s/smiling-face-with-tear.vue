<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGzLaS2dSx" cx="64" cy="-2936" r="56.96" fx="64" fy="-2936" gradientTransform="matrix(1 0 0 -1 0 -2872)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVG6o3UVdTG" cx="38.63" cy="351.65" r="26.42" fx="38.63" fy="351.65" gradientTransform="matrix(1 0 0 1.54 0 -471.05)" gradientUnits="userSpaceOnUse"><stop offset=".46" class="v1-56mb1l"/><stop offset="1" class="r5vbxk1ae"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGzLaS2dSx)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="dknq9ghxx"/><path class="w62ozmbqg"/><path class="jf00rc3go"/><path class="ioc7ivb7h"/><g class="wj4kgr0on"><path fill="url(#SVG6o3UVdTG)" class="p1nt-_1_p"/><path class="ta-877bhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:smiling-face-with-tear" /></template>
<style>
.dknq9ghxx {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M63.96 92.71c-10.69 0-19.15-5.07-23.82-10.48c-.47-.54-.58-1.28-.28-1.92c.3-.65.94-1.08 1.65-1.08c.32 0 .63.09.92.25c4.81 2.77 12.88 6.21 21.51 6.21h.14c8.63 0 16.7-3.43 21.51-6.21c.29-.16.6-.25.92-.25c.7 0 1.35.43 1.65 1.08a1.8 1.8 0 0 1-.28 1.92c-4.67 5.42-13.13 10.48-23.82 10.48M44.82 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.ioc7ivb7h {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.79 45.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.jf00rc3go {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.18 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.p1nt-_1_p {
  d: path("M37.81 105.6c-6.5 0-11.5-6.3-11.5-11.7c0-3.8 1.7-8.2 4.1-14.3c.3-.9.7-1.8 1.1-2.8c1.4-3.6 3-7.2 4.8-10.6c.4-.7 1.2-1 1.9-.7c.3.1.5.4.7.7c1.5 3.1 3.2 6.9 4.9 10.8c4.2 9.4 5.4 13.2 5.4 17c.1 5.3-5 11.6-11.4 11.6");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.r5vbxk1ae {
  stop-color: var(--svg-color--1e88e5, #1e88e5);
}

.ta-877bhf {
  fill: var(--svg-color--a1ebff, #a1ebff);
  d: path("M30.14 93.13c1.32 3.31 4.56 2.43 5.22-.67c.49-2.32-.72-8.97-1.2-10.26s-1.77-1-2.4.67c-.53 1.39-2.93 6.98-1.62 10.27Z");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.v1-56mb1l {
  stop-color: var(--svg-color--29b6f6, #29b6f6);
}

.w62ozmbqg {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.43 45.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
