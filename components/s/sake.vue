<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jb3vqab5q"/><path class="lb1nozr5k"/><g class="r5qwt0j4h"><path class="f6x948bqn"/><ellipse class="dc1xc6byw"/></g><g class="r-tup0bzs"><path class="mw6g_6dtn"/><ellipse class="edxs1_bix"/><ellipse class="bj9gnz69x"/></g><path class="udm_hdcuh"/><path class="u1g6zybzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:sake" /></template>
<style>
.bj9gnz69x {
  cx: 13px;
  cy: 56.9px;
  rx: 11px;
  ry: 3.8px;
}

.dc1xc6byw {
  cx: 13px;
  cy: 58.5px;
  rx: 10.1px;
  ry: 3.5px;
}

.edxs1_bix {
  cx: 13px;
  cy: 43.8px;
  rx: 11px;
  ry: 3.8px;
}

.f6x948bqn {
  d: path("M37 5.7c-.8 4.9 14.9 4.9 14.1 0c-.6-4-13.4-4-14.1 0");
}

.jb3vqab5q {
  fill: var(--svg-color--b7b198, #b7b198);
  d: path("M44.1 50.4c7.6 0 13.8 2.6 13.8 5.8S51.7 62 44.1 62s-13.8-2.6-13.8-5.8s6.1-5.8 13.8-5.8");
}

.lb1nozr5k {
  fill: var(--svg-color--f9f3d9, #f9f3d9);
  d: path("M35.6 5.4c-.3 2.2 1.9 6.4 2 8.7c.2 3.3-18.4 24.7-8.6 40.5c4.4 7.1 25.7 7.1 30.1 0c9.8-15.8-8.8-37.1-8.6-40.5c.1-2.2 2.4-6.5 2-8.7c-.7-4.5-16.1-4.5-16.9 0");
}

.mw6g_6dtn {
  d: path("M2 43.8h22v13.1H2z");
}

.r-tup0bzs {
  fill: var(--svg-color--f9f3d9, #f9f3d9);
}

.r5qwt0j4h {
  fill: var(--svg-color--b7b198, #b7b198);
}

.u1g6zybzc {
  fill: var(--svg-color--b4d7ee, #b4d7ee);
  d: path("M22.1 45.1c-1.5-1.1-5-1.9-9.1-1.9s-7.7.8-9.1 1.9c1.5 1.1 5 1.9 9.1 1.9c4.1-.1 7.7-.9 9.1-1.9");
}

.udm_hdcuh {
  fill: var(--svg-color--b7b198, #b7b198);
  d: path("M22.1 45.1c.5-.3.7-.7.7-1.1c0-1.6-4.4-3-9.8-3s-9.8 1.3-9.8 3c0 .4.3.8.7 1.1c1.5-1.1 5-1.9 9.1-1.9s7.7.8 9.1 1.9");
}

</style>
