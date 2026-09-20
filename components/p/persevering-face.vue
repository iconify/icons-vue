<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGLQb4bblj" cx="64" cy="-1160" r="56.96" fx="64" fy="-1160" gradientTransform="matrix(1 0 0 -1 0 -1096)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGLQb4bblj)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="mr55t1bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:persevering-face" /></template>
<style>
.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.mr55t1bhf {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M57.77 67.51C54.11 64.83 45.12 57.65 41.29 55c-4.62-3.16-9.02 3.56-4.4 6.5l10.89 4.81c-5.37.54-17.59.17-18.89 6.89c-.24 1.99.88 4.41 2.9 5c1.98.65 4.05.37 5.9-.8c3.53-1.95 6.87-3.37 10.7-4.3c2.59-.65 5.2-.94 8.1-1.1c1.82-.08 2.72-3.27 1.28-4.49m42.12 5.69c-1.39-6.79-13.53-6.35-18.98-6.89l10.88-4.81c4.61-2.93.23-9.66-4.4-6.5c-3.74 2.65-12.72 9.83-16.38 12.51c-1.43 1.22-.55 4.41 1.28 4.49c4.11.21 7.78.79 11.5 2.1c3.49.87 6.73 3.63 10.3 4.4c3.22.57 6.27-1.98 5.8-5.3M64.4 84.3c10.8 0 17.8 7.9 19.7 11.6c.7 1.4.7 2.6.1 3.1q-.75.6-2.1 0c-.3-.1-.6-.3-.9-.5c-4.8-3.4-10.7-5.5-16.8-5.5s-12 2.1-16.8 5.4c-.3.2-.6.4-.9.5q-1.35.6-2.1 0c-.6-.6-.6-1.7.1-3.1c1.9-3.6 8.9-11.5 19.7-11.5M28.28 43.9c-2.2.4-2.3 3.6.1 3.7c4.9.1 10.2-1.7 14.3-5.5c1.5-1.3 2.8-2.9 3.7-4.5c1.2-2.2-1.6-3.7-3-2.1l-.1.1c-4 4.5-9.5 7.4-15 8.3m57.1-8.4c-1.4-1.7-4.2-.1-3 2.1c.9 1.6 2.2 3.2 3.7 4.5c4 3.7 9.4 5.6 14.3 5.5c2.5-.1 2.3-3.3.1-3.7c-5.6-.9-11.1-3.8-15.1-8.4");
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
