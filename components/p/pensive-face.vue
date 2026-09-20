<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGH5as8dov" cx="64" cy="24" r="56.96" fx="64" fy="24" gradientTransform="matrix(1 0 0 -1 0 88)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGH5as8dov)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="j3thnvj_u"/><path class="evfmnkbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:pensive-face" /></template>
<style>
.evfmnkbog {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M49.6 66.1c-2.07 2.14-4.98 3.89-8.1 3.8h.1c-3.16.21-6.39-1.86-8.39-3.99c-2.08-2.15-6.73.12-5.31 3.09c.71 2.02 2.7 4.15 4.73 5.59c6.58 4.67 16.88 3.1 21.17-3.79c.35-.45.76-1.22.9-1.6c1.36-2.83-2.85-5.48-5.1-3.1m44.91.37c-2.03 2.14-4.98 3.76-8.02 3.72h.14c-3.12.15-6.38-1.78-8.37-3.9c-2.11-2.29-6.82.01-5.34 3.09c2.1 4.92 8.1 8.28 13.57 8.18c5.51.03 11.29-3.06 13.52-8.11c1.4-3.2-3.42-5.33-5.5-2.98M23.38 49.9c-2.2.4-2.3 3.6.1 3.7c4.9.1 10.2-1.7 14.3-5.5c1.5-1.3 2.8-2.9 3.7-4.5c1.2-2.2-1.6-3.7-3-2.1l-.1.1c-4 4.5-9.5 7.4-15 8.3m66.1-8.4c-1.4-1.7-4.2-.1-3 2.1c.9 1.6 2.2 3.2 3.7 4.5c4 3.7 9.4 5.6 14.3 5.5c2.5-.1 2.3-3.3.1-3.7c-5.6-.9-11.1-3.8-15.1-8.4");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.j3thnvj_u {
  fill: var(--svg-color--35220b, #35220b);
  d: path("M75 100.1H53c-2.21 0-4-1.79-4-4s1.79-4 4-4h22c2.21 0 4 1.79 4 4s-1.79 4-4 4");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
