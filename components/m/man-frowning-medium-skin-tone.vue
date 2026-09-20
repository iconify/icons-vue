<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGQCzSmdFg" x1="64" x2="64" y1="33.807" y2="5.927" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zs84mcc3v"/><stop offset=".471" class="fwmih7b7q"/><stop offset="1" class="lgwbsx_1t"/></linearGradient><path fill="url(#SVGQCzSmdFg)" class="he-sltlqn"/><path class="y93kzenxm"/><path class="ynavb2k-f"/><path class="lsns2bbhz"/><path class="r6gtvjbvm"/><path class="qlzbsdx5i"/><path class="nz0mbmbad"/><path class="zxk1zm_yy"/><radialGradient id="SVGlirTkcwy" cx="64.001" cy="73.422" r="38.092" gradientTransform="matrix(1 0 0 -1.1282 0 137.411)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGlirTkcwy)" class="eikybp-0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:man-frowning-medium-skin-tone" /></template>
<style>
.eikybp-0e {
  d: path("M100.15 63.65s9.31-51.9-36.13-52.14h-.04c-.71 0-1.4.02-2.08.05c-1.35.06-2.66.16-3.92.31h-.04c-.09.01-.17.03-.26.04c-38.25 4.81-29.83 51.74-29.83 51.74l2.98 7.68c.13.34.62.31.7-.05c.98-4.39 4.46-19.71 6.22-24.37a6.075 6.075 0 0 1 6.79-3.83c4.45.81 11.55 1.81 19.37 1.81h.16c7.82 0 14.92-1 19.37-1.81c2.9-.53 5.76 1.08 6.79 3.83c1.76 4.68 5.25 20.1 6.21 24.42c.08.36.57.39.7.05c.96-2.36 3.01-7.73 3.01-7.73");
}

.fwmih7b7q {
  stop-color: var(--svg-color--00b29a, #00b29a);
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.he-sltlqn {
  d: path("M80.74 88.51c-2.85-.54-30.62-.54-33.47 0C29.22 91.94 16 100.9 16 117.88V124h96v-6.12c0-16.98-13.22-25.94-31.26-29.37");
}

.lgwbsx_1t {
  stop-color: var(--svg-color--009e89, #009e89);
}

.lsns2bbhz {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M67.81 78.06c-.11-.04-.21-.07-.32-.08H60.5c-.11.01-.21.04-.32.08c-.63.26-.98.91-.68 1.61s1.69 2.66 4.49 2.66s4.2-1.96 4.49-2.66c.31-.7-.03-1.36-.67-1.61");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.nz0mbmbad {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M55.39 58.29c-1.2-1.14-3.8-2.64-8.22-1.79s-6.39 3.22-7.16 4.74c-.34.67-.12 1.33.25 1.68c.34.33 1.23.52 2.09.03s2.5-1.78 5.49-2.37c3-.55 4.94.05 5.9.19s1.74-.37 1.95-.81c.23-.47.23-1.17-.3-1.67M88 61.26c-.77-1.52-2.74-3.89-7.16-4.74c-4.43-.85-7.02.65-8.22 1.79a1.43 1.43 0 0 0-.3 1.67c.22.44.99.95 1.95.81c.97-.14 2.91-.74 5.9-.19c2.99.6 4.62 1.88 5.49 2.37c.86.49 1.75.3 2.09-.03c.37-.35.59-1 .25-1.68");
}

.qlzbsdx5i {
  fill: var(--svg-color--49362e, #49362e);
  d: path("M43.33 68.26c.01-.52.1-1.02.22-1.5c.97-.13 2.01-.33 3.15-.67a9.9 9.9 0 0 0 3.91-2.24c1.07 1.01 1.76 2.62 1.72 4.43c-.06 3.06-2.13 5.54-4.62 5.53c-2.48 0-4.44-2.49-4.38-5.55m41.34 0c-.01-.52-.1-1.02-.22-1.5c-.97-.13-2-.33-3.15-.67a9.9 9.9 0 0 1-3.91-2.24c-1.07 1.01-1.76 2.62-1.71 4.43c.07 3.06 2.13 5.54 4.62 5.53c2.47 0 4.43-2.49 4.37-5.55");
}

.r6gtvjbvm {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M56.67 91.77c4.63-1.45 10.27-1.38 14.66 0c.8.25 1.2-.57.65-1.41c-.78-1.18-3.67-3.46-7.98-3.46s-7.2 2.28-7.98 3.46c-.55.85-.15 1.67.65 1.41");
}

.y93kzenxm {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M54.92 93.85v9.98c0 4.51 4.33 8.17 9.08 8.17s9.08-3.66 9.08-8.17v-9.98zm36.41-35.42H36.67c-5.89 0-10.71 5.14-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41c.01-6.27-4.81-11.41-10.7-11.41");
}

.ynavb2k-f {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M64 19.07c-17.4 0-33.52 18.61-33.52 45.39c0 26.64 16.61 39.81 33.52 39.81S97.52 91.1 97.52 64.46c0-26.78-16.12-45.39-33.52-45.39");
}

.zs84mcc3v {
  stop-color: var(--svg-color--00bfa5, #00bfa5);
}

.zxk1zm_yy {
  fill: var(--svg-color--543930, #543930);
  d: path("M64.02 11.51h-.04c-45.44.24-36.13 52.14-36.13 52.14s2.04 5.35 2.97 7.71c.13.34.63.3.71-.05c.97-4.34 4.46-19.73 6.22-24.4a6.075 6.075 0 0 1 6.79-3.83c4.45.81 11.55 1.81 19.37 1.81h.16c7.82 0 14.92-1 19.37-1.81c2.9-.53 5.76 1.08 6.79 3.83c1.75 4.66 5.22 19.96 6.2 24.36c.08.36.58.39.71.05l2.98-7.67c.03 0 9.34-51.9-36.1-52.14");
}

</style>
