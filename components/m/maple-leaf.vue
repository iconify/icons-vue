<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVG7dTlUsTI" x1="64.466" x2="64.466" y1="91.429" y2="112.358" gradientUnits="userSpaceOnUse"><stop offset="0" class="xyhvt-xig"/><stop offset=".348" class="mddycfgfz"/><stop offset="1" class="skf-k9n8a"/></linearGradient><path fill="url(#SVG7dTlUsTI)" class="i-26wghjf"/><radialGradient id="SVGadiYhbee" cx="65.836" cy="38.176" r="62.079" gradientTransform="rotate(180.773 .01 71.3)scale(-1 1.2816)" gradientUnits="userSpaceOnUse"><stop offset=".002" class="ipeg7mbcn"/><stop offset=".12" class="up25g2g5s"/><stop offset=".26" class="oor8xp_3j"/><stop offset=".412" class="uwb9tr1-e"/><stop offset=".571" class="c-1ff4kwo"/><stop offset=".679" class="mnl6en2ux"/><stop offset="1" class="qtb-mmdrd"/></radialGradient><path fill="url(#SVGadiYhbee)" class="rfz4w0b7u"/><radialGradient id="SVGhifEPdVR" cx="65.7" cy="86.334" r="42.364" gradientTransform="matrix(1 0 0 1.54133 0 -46.736)" gradientUnits="userSpaceOnUse"><stop offset=".42" class="xyhvt-xig"/><stop offset=".717" class="qhn8mnbgh"/><stop offset="1" class="skf-k9n8a"/></radialGradient><path fill="url(#SVGhifEPdVR)" class="ds88huaek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:maple-leaf" /></template>
<style>
.c-1ff4kwo {
  stop-color: var(--svg-color--ff7113, #ff7113);
}

.ds88huaek {
  d: path("M64.486 91.914s1.82-1.4 5.59-2.16c2.07-.42 4.88-.47 7.95-.4c8.24.17 17.03 1.71 21.65 1.87c4.62.15 8.86 0 8.78-1s-7.16-.54-12.55-1.54s-13.17-2.08-16.41-2.23c-8.37-.41-10.09.77-10.09.77s10.78-9.55 14.79-12.63s10.47-8.12 16.41-13.4c5.17-4.6 14.63-14.33 14.02-15.17c-.62-.85-12.25 10.24-16.48 13.63c-4.24 3.39-9.85 7.6-18.55 14.46s-13.34 11.35-13.34 11.35s-.69-25.8-.92-31.89c-.23-6.08-.23-28.87-.39-31.64s.39-14.26-1-14.19c-1.39.08-1.62 9.4-1.77 14.1s-.15 24.49-.31 30.58s.23 32.73.23 32.73s-16.56-12.46-22.72-17.39s-16.47-14.18-17.86-15.34s-6.71-6.11-7.33-5.49s7.17 8.88 10.1 11.5s16.15 14.09 21.85 18.78s12.88 9.92 12.88 9.92s-6.78-.77-15.92.05c-6.93.62-13.43 1.42-16.28 1.65s-7.24.31-7.39.92c-.15.62 3.54 1.54 10.94 1.08c7.39-.46 11.26-.79 16.64-1.05c7.32-.35 12.02-.1 13.86.36c1.85.46 3.62 1.77 3.62 1.77");
}

.i-26wghjf {
  d: path("M59.686 122.154c.2.99 1.31 1.87 4.39 2.07s5.15-.3 5.23-1.95c.09-1.65-1.14-3.49-1.34-4.88s-.99-10.74-1.19-15.61s-.36-14.16-.36-14.16l-4.07.43s.06 9.65-.14 14.52s-1.01 12.01-1.11 13.89c-.09 1.71-1.83 3.61-1.41 5.69");
}

.ipeg7mbcn {
  stop-color: var(--svg-color--ffbe06, #ffbe06);
}

.mddycfgfz {
  stop-color: var(--svg-color--cf721b, #cf721b);
}

.mnl6en2ux {
  stop-color: var(--svg-color--ff5617, #ff5617);
}

.oor8xp_3j {
  stop-color: var(--svg-color--ffaa09, #ffaa09);
}

.qhn8mnbgh {
  stop-color: var(--svg-color--c0681b, #c0681b);
}

.qtb-mmdrd {
  stop-color: var(--svg-color--df1024, #df1024);
}

.rfz4w0b7u {
  d: path("M64.396 89.454s-5.57 6.36-9.55 8.75s-9.55 5.27-10.54 4.57s1.39-5.57 1.39-5.57s-8.32 1.88-17.53-.79c-8.82-2.55-14.09-6.37-13.69-7.47s4.57-1.69 8.65-3.28s9.55-4.18 9.55-4.18s-7.83-2.84-12.3-5.62s-7.29-5.41-7.39-6.31c-.1-.89 6.26-2.49 6.26-2.49s-3.48-2.39-6.07-10.14s-3.27-13.63-2.78-14.21c1.18-1.37 11.73 2.28 14.72 3.85c2.88 1.51 7.55 4.5 7.55 4.5s-.3-5.97.7-5.97c.99 0 3.58 2.39 5.87 5.37s9.05 13.32 10.74 12.53c1.69-.8.09-5.78-2.28-10.67c-1.49-3.08-3.59-8.23-4.78-14.29c-1.18-6-.5-10.94.2-11.53c.7-.6 7.46 4.67 7.46 4.67s-.54-5.79.55-10.76s2.03-6.46 2.62-6.56c.6-.1 2.99 3.4 2.99 3.4s.92-4.95 2.91-8.43s3.75-5.09 4.64-5.09s3.52 3.49 4.71 7.17s1.88 6.73 1.88 6.73s1.51-3.09 2.18-3.2c.57-.09 2.58 2.16 3.57 7.43s.99 8.91.99 8.91s4.28-4.47 5.07-4.57c.8-.1 2.79 5.07 1.3 12.13s-5.37 13.88-6.27 17.56c-.89 3.68-1.69 7.29-.2 7.69s3-4.1 6.18-9.08s7.54-10.21 8.14-9.82c.6.4 1.49 2.29 1.69 3.28s.3 2.88.3 2.88s4.57-3.08 8.55-4.57s12.93-4.77 14.82-3.18s-1.49 10.14-3.48 14.52s-6.36 10.93-6.36 10.93s5.95 1.14 5.85 2.03s-4.95 4.89-9.33 7.18s-9.96 4.13-9.96 4.13s2.49 1.69 8.35 3.58c5.87 1.89 10.74 2.49 11.14 3.48s-2.29 4.47-11.24 6.86s-18.93 1.06-19.43 1.55c-.5.5 2.43 4.41 1.63 5.51s-6.17-.42-10.34-3.98c-5.35-4.56-9.63-9.43-9.63-9.43");
}

.skf-k9n8a {
  stop-color: var(--svg-color--a6581c, #a6581c);
}

.up25g2g5s {
  stop-color: var(--svg-color--ffb907, #ffb907);
}

.uwb9tr1-e {
  stop-color: var(--svg-color--ff920d, #ff920d);
}

.xyhvt-xig {
  stop-color: var(--svg-color--df7c1a, #df7c1a);
}

</style>
