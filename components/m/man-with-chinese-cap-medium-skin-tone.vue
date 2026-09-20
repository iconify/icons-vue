<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ibpx62b0z"/><path class="p-m6lfbqf"/><path class="or9vrjb_r"/><path class="a9lbz-bmy"/><path class="izpzwvovu"/><ellipse class="dde9vuq4c"/><ellipse class="jb7cegbvd"/><path class="jdbh6ab2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:man-with-chinese-cap-medium-skin-tone" /></template>
<style>
.a9lbz-bmy {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M18 1s5 4 6 8c.97 3.88 0 7 0 7H12s-1-3 0-7s6-8 6-8");
}

.dde9vuq4c {
  cx: 18px;
  cy: 1px;
  fill: var(--svg-color--414042, #414042);
  rx: 2px;
  ry: 1px;
}

.ibpx62b0z {
  fill: var(--svg-color--d5ab88, #d5ab88);
  d: path("M30.5 14c-.428 0-.824.188-1.177.491C27.69 8.459 23.244 4.125 18 4.125S8.309 8.46 6.676 14.49C6.324 14.188 5.928 14 5.5 14C4.119 14 3 15.79 3 18s1.119 4 2.5 4c.225 0 .438-.062.646-.151C7.006 29.287 11.978 35 18 35s10.993-5.713 11.854-13.152c.208.09.421.152.646.152c1.381 0 2.5-1.791 2.5-4s-1.119-4-2.5-4");
}

.izpzwvovu {
  fill: var(--svg-color--414042, #414042);
  d: path("M6 11s3 3 12 3s12-3 12-3s1 2 0 3s-4 3-12 3s-11-2-12-3s0-3 0-3");
}

.jb7cegbvd {
  cx: 18px;
  cy: 11px;
  fill: var(--svg-color--ffd983, #ffd983);
  rx: 3px;
  ry: 2px;
}

.jdbh6ab2a {
  fill: var(--svg-color--662113, #662113);
  d: path("M13 22a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1m10 0a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1");
}

.or9vrjb_r {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M18 31c-2.21 0-4.357-1.06-4.447-1.105a1 1 0 0 1 .893-1.79c.018.009 1.824.895 3.554.895s3.536-.886 3.554-.896a1 1 0 0 1 .894 1.79C22.356 29.94 20.211 31 18 31m1-5h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

.p-m6lfbqf {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M6 12.11C6 7.055 10.958 1 18 1s12 6.056 12 11.111C30 12.833 25.041 15 18 15S6 12.833 6 12.11");
}

</style>
