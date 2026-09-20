<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGSRzSYcfE" cx="64" cy="-568" r="56.96" fx="64" fy="-568" gradientTransform="matrix(1 0 0 -1 0 -504)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGSRzSYcfE)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="suzrw9j4o"/><path class="bj2hf8b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:winking-face" /></template>
<style>
.bj2hf8b8h {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.28 51.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95c1-1.45.67-2.97-.36-3.69");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
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

.suzrw9j4o {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M64 96.54c-12.74 0-21.82-6.61-24.55-10.77c-1.06-1.61-1.26-3.35-.55-4.67c.53-.99 1.51-1.56 2.67-1.56c.39 0 .79.07 1.2.19c6.42 2.01 13.78 3.07 21.28 3.07s14.79-1.06 21.19-3.07c.41-.13.81-.19 1.2-.19c1.16 0 2.14.57 2.67 1.56c.71 1.31.5 3.06-.55 4.67c-2.73 4.17-11.82 10.77-24.55 10.77ZM29.84 45.9c-.89 0-1.7-.41-2.18-1.11c-.48-.69-.56-1.56-.24-2.44c1.94-5.01 5.94-9.21 10.99-11.54c1.88-.87 3.85-1.45 5.86-1.72c.15-.02.27-.02.4-.02c1.31 0 2.32.85 2.52 2.11c.18 1.15-.41 2.56-1.89 3.04l-.12.04c-5.33 1.84-10.08 5.6-13.03 10.32c-.51.83-1.35 1.32-2.32 1.32Zm67.67 17.24c-2.31-3.47-6.98-5.69-11.23-6.37c2.69-1.47 5.9-3.05 8.55-3.97c2.77-.96 2.13-5.28-.85-5.34c-8.16.37-17.49 5.64-22.01 12.46c-1.28 2.24.95 5.46 3.52 4.36c.48-.23.96-.32 1.58-.47c2.67-.6 5.78-.53 8.61-.03c2.77.48 5.91 1.58 7.99 3.15c2.4 1.82 5.65-1.31 3.84-3.79m-52.84-15.1c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
