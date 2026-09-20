<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGRiGVheCl" cx="64" cy="-2640" r="56.96" fx="64" fy="-2640" gradientTransform="matrix(1 0 0 -1 0 -2576)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGRiGVheCl)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="kl0movx6s"/><path class="ycl1kkbje"/><path class="cz9_5_hny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sleepy-face" /></template>
<style>
.cz9_5_hny {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("m36.07 46.37l.14-.03c2.14-.5 2.06-3.72-.38-3.64c-1.9.1-3.85.48-5.75 1.18c-5.23 1.9-9.33 5.79-11.47 10.18c-1.03 2.21 1.89 3.59 3.19 1.81c3.35-4.47 8.43-8 14.28-9.49Zm55.86 0l-.14-.03c-2.14-.5-2.06-3.72.38-3.64c1.9.1 3.85.48 5.75 1.18c5.23 1.9 9.33 5.79 11.47 10.18c1.03 2.21-1.89 3.59-3.19 1.81c-3.35-4.47-8.43-8-14.28-9.49ZM49.8 62.8c-2.07 2.14-4.98 3.89-8.1 3.8h.1c-3.14.23-6.41-1.9-8.41-4.01c-2.09-2.12-6.71.17-5.28 3.11c.94 1.97 2.73 4.19 4.86 5.61c7.13 5.08 18.45 2.63 22.03-5.42c1.39-2.88-3.02-5.53-5.2-3.1Zm44.9 0c-2.07 2.14-4.98 3.89-8.1 3.8h.1c-3.13.23-6.41-1.9-8.4-4c-2.09-2.14-6.72.14-5.3 3.1c.94 1.96 2.72 4.18 4.85 5.6c7.12 5.09 18.47 2.64 22.05-5.41c1.39-2.88-3.02-5.53-5.2-3.1Zm-30.67 41.68c3.85 0 7.73.74 11.37 1.74c7.99 3.37 14.37-4.69 9.9-10.02c-4.66-5.54-12.25-7.68-21.53-7.68S47.66 90.14 43 95.69c-5.19 5.29 1.81 13.34 9.81 10.52c3.62-.99 7.36-1.74 11.21-1.74Z");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.kl0movx6s {
  fill: var(--svg-color--4fc3f7, #4fc3f7);
  d: path("M112.34 110.82c21.29-4.71 14.81-41.1-21.71-36.29c-6.33.83-13 5-17.74 9.19c-1.16 1.03-.65 3 .9 2.89c15.23-1.05 14.78 29.47 38.56 24.21Z");
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

.ycl1kkbje {
  fill: var(--svg-color--b3e5fc, #b3e5fc);
  d: path("M113.61 81.45c.56.55 1.08 1.17 1.32 1.92s.18 1.63-.31 2.24c-.72.89-2.04.95-3.18.84c-3.11-.31-6.15-1.32-8.83-2.93c-1.53-.92-3.33-2.51-2.91-4.53c.29-1.35 1.6-1.67 2.82-1.7c3.74-.09 8.4 1.59 11.07 4.17Z");
}

</style>
