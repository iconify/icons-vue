<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="herb-bg1p"/><path class="rsyv2tb6l"/><linearGradient id="SVGxRiqPwNT" x1="55.562" x2="69.459" y1="105.748" y2="34.253" gradientUnits="userSpaceOnUse"><stop offset=".362" class="vc--wpv5i"/><stop offset=".412" class="pvsbeo8gd"/><stop offset=".51" class="rrmc_w39m"/><stop offset=".646" class="zl3uzcb2b"/><stop offset=".788" class="bbhu4wb5t"/><stop offset=".817" class="srbycabvv"/><stop offset=".944" class="h-htnbcov"/></linearGradient><path fill="url(#SVGxRiqPwNT)" class="lhv9tkb8t"/><path class="e3mcjpbat"/><path class="gwgoo14xl"/><path class="c-wxl4k7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:penguin" /></template>
<style>
.bbhu4wb5t {
  stop-color: var(--svg-color--ffc139, #ffc139);
}

.c-wxl4k7x {
  fill: var(--svg-color--000409, #000409);
  d: path("M63.76 22c.09 2.15-2 3.99-3.88 3.68c-2.37-.4-3.53-2.66-3.28-4.9s2.29-3.42 4.18-3.21c1.9.2 2.89 2.18 2.98 4.43");
}

.e3mcjpbat {
  fill: var(--svg-color--adadb7, #adadb7);
  d: path("M47.1 18.15s-.97-3.62-3.43-4.08c-4.74-.89-11.31 2.21-13.98 3.85c-2.16 1.33-5.12 4.22-4.22 5.63s5.77.05 9.95.75c2.89.49 6.9 1.69 8.59 1.64c1.35-.04 3.1-2.35 3.33-3.43s.23-3-.24-4.36");
}

.gwgoo14xl {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
  d: path("M47.33 18.52s-3.99 1.74-12.39 2.3c-3.56.24-9.57 1.97-9.57 1.97s-.61.61.38 1.13s6.01-.91 9.1-1.08c5.02-.28 14.22-.94 14.22-.94z");
}

.h-htnbcov {
  stop-color: var(--svg-color--ff9700, #ff9700);
}

.herb-bg1p {
  fill: var(--svg-color--adadb7, #adadb7);
  d: path("M69.77 112.75s-6.69 4.63-7.32 5.44c-.63.8-.9 1.74.32 2.11s3.16-.14 3.16-.14s-.97 1.44 1.31 1.97c1.53.35 4.5-1.2 4.5-1.2s-.49 1.37 1.55 1.65c2.94.41 8.02-5.9 9.06-7.87s.56-3.66.56-3.66zm-17.6-4.16s-8.21 4.92-8.87 5.2s-3.22 1.71-2.25 3.28c.75 1.22 3.66.28 3.66.28s-.63 1.37 1.03 2.16c1.67.79 5.16-1.13 5.16-1.13s-.39 1.71 1.88 1.97c2.91.34 9.39-8.54 9.39-8.54z");
}

.lhv9tkb8t {
  d: path("M39.78 38.37s-6.1 6.34-6.66 15.06c-.47 7.33-.52 20.69 3.71 32.66s12.25 21.87 23.93 24.21c12.64 2.54 26.65-1.92 27.08-2.06c.42-.14-2.53-3.28-4.6-6.38c-1.57-2.36-3.61-7.6-3.61-7.6s.14 4.04-2.46 4.36c-1.98.25-4.79-1.69-6.9-6.34s-4.98-17.27-5.77-27.66c-.7-9.29.25-15.27 1.2-17.88c.57-1.57 1.72-2.64 1.72-2.64s3.2 3.89 8.27 2.57c4.88-1.27 6.1-6.62 5.26-10.98c-1.01-5.21-3.1-10.84-10.18-9.29c-8.04 1.76-5.24 12.14-5.24 12.14s-5.74 4.68-13.76 3.84c-8.05-.84-11.99-4.01-11.99-4.01");
}

.pvsbeo8gd {
  stop-color: var(--svg-color--fffaef, #fffaef);
}

.rrmc_w39m {
  stop-color: var(--svg-color--ffedc7, #ffedc7);
}

.rsyv2tb6l {
  fill: var(--svg-color--4d4d4d, #4d4d4d);
  d: path("M84.97 38.37s1.13-17.6-7.46-25.76s-19.15-7.23-22.39-6.38c-3.24.84-8.88 2.88-12.86 8.63c-5.26 7.6-3.1 14.73-5.54 19.33c-1.92 3.63-7.23 14.03-8.07 21.49s-1.41 21.59-.99 26.61c.41 4.91.61 9.24 3.24 13.23c1.57 2.39 4.7 2.44 5.77 1.13c.63-.77.42-1.9.42-1.9s4.28 6.38 6.01 8.52c2.82 3.47 8.67 9.06 18.21 10.7c12.58 2.16 33.22-4.5 33.22-4.5s1.77 1.2 4.58 1.34c1.43.07 3.1-1.34 2.89-2.75s-1.83-3.38-2.18-4.15s.73-22.31-2.65-36.95s-9.67-26.62-12.2-28.59");
}

.srbycabvv {
  stop-color: var(--svg-color--ffb92e, #ffb92e);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.zl3uzcb2b {
  stop-color: var(--svg-color--ffd985, #ffd985);
}

</style>
