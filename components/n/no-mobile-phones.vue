<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="x4q62uhhj"/><path class="irgaj9b1l"/><path class="qzr50pbxu"/><path class="a5dc0nbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:no-mobile-phones" /></template>
<style>
.a5dc0nbmf {
  fill: var(--svg-color--be1e2d, #be1e2d);
  d: path("M51.86 48.979C39.548 36.67 27.234 24.354 14.92 12.042c-5.48-5.481-8.357-2.6-2.878 2.878l36.936 36.938c5.482 5.482 8.361 2.603 2.882-2.879");
}

.irgaj9b1l {
  fill: var(--svg-color--be1e2d, #be1e2d);
  d: path("M31.953 0C14.334 0 0 14.335 0 31.953s14.334 31.953 31.953 31.953c17.617 0 31.952-14.335 31.952-31.953S49.57 0 31.953 0m0 55.986c-13.253 0-24.034-10.78-24.034-24.033S18.7 7.917 31.953 7.917c13.254 0 24.034 10.783 24.034 24.036s-10.78 24.033-24.034 24.033");
}

.qzr50pbxu {
  fill: var(--svg-color--fff, #fff);
  d: path("M41.31 13.08H22.59a3 3 0 0 0-2.996 2.997v31.747a3 3 0 0 0 2.996 2.993h18.72a3 3 0 0 0 2.996-2.993V16.077a3 3 0 0 0-2.996-2.997m1.496 24.26v7.917a1.5 1.5 0 0 1-1.496 1.497H22.59c-.826 0-1.5-.672-1.5-1.497v-29.18c0-.825.674-1.498 1.5-1.498h18.72c.822 0 1.496.673 1.496 1.498v21.266");
}

.x4q62uhhj {
  cx: 31.951px;
  cy: 31.949px;
  r: 27.956px;
  fill: var(--svg-color--25333a, #25333a);
}

</style>
