<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGLQb4bblj" cx="64" cy="-1160" r="56.96" fx="64" fy="-1160" gradientTransform="matrix(1 0 0 -1 0 -1096)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGLQb4bblj)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="omlmmddtl"/><path class="vsl5mh6ic"/><path class="cx5g_nbcy"/><path class="r8fc4x3fd"/><path class="q9un0nblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:worried-face" /></template>
<style>
.cx5g_nbcy {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.58 51.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.omlmmddtl {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M64.38 83.1c-10.5 0-18 6.3-20.2 9.8c-.9 1.3-1 2.8-.5 3.9c.4.8 1.2 1.3 2.2 1.3c.3 0 .7-.1 1-.2c5.3-1.7 9.9-4.1 17.5-4.1s12.2 2.5 17.5 4.1c.3.1.7.2 1 .2c1 0 1.8-.5 2.2-1.3c.6-1.1.4-2.6-.5-3.9c-2.2-3.5-9.7-9.8-20.2-9.8M45.22 51.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.q9un0nblz {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M28.28 35.9c-2.2.4-2.3 3.6.1 3.7c4.9.1 10.2-1.7 14.3-5.5c1.5-1.3 2.8-2.9 3.7-4.5c1.2-2.2-1.6-3.7-3-2.1l-.1.1c-4 4.5-9.5 7.4-15 8.3m57.1-8.4c-1.4-1.7-4.2-.1-3 2.1c.9 1.6 2.2 3.2 3.7 4.5c4 3.7 9.4 5.6 14.3 5.5c2.5-.1 2.3-3.3.1-3.7c-5.6-.9-11.1-3.8-15.1-8.4");
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.r8fc4x3fd {
  fill: var(--svg-color--896024, #896024);
  d: path("M83.19 54.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.vsl5mh6ic {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.83 54.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
