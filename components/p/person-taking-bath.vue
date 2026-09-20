<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yuxm_1gsd"/><path class="kt5lgk9lq"/><ellipse class="q7-78zgww"/><path class="rvg3wmbxc"/><path class="av5p4ybhm"/><path class="fcqkay09t"/><circle class="fjf66zz4g"/><circle class="v8fe-mbab"/><path class="izgfmlbop"/><path class="rsgd6l_7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:person-taking-bath" /></template>
<style>
.av5p4ybhm {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M28 6c0 1.104-1.343 1-3 1s-3 .104-3-1s1.343-2 3-2s3 .896 3 2");
}

.fcqkay09t {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M29 7a1 1 0 0 1-1 1h-6a1 1 0 1 1 0-2h6a1 1 0 0 1 1 1");
}

.fjf66zz4g {
  cx: 12px;
  cy: 34px;
  r: 2px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.izgfmlbop {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M30 34H12C7 34 2 28 1 20c-.248-1.984.812-1 3.021-1C4.021 19 17 21 30 21c2 0 5-1.209 5 1c0 0-1 12-5 12");
}

.kt5lgk9lq {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M9 13c0-1-3-2-6 1s1.021 5 1.021 5S8 22 7 19s2-5.001 2-6");
}

.q7-78zgww {
  cx: 32px;
  cy: 16px;
  fill: var(--svg-color--99aab5, #99aab5);
  rx: 2px;
  ry: 1px;
}

.rsgd6l_7g {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M36 21a1 1 0 0 1-1 1L1 20a1 1 0 1 1 0-2l34 2a1 1 0 0 1 1 1");
}

.rvg3wmbxc {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M33 21a1 1 0 0 1-1-1V4c0-1.582-1.962-2-3-2s-3 .418-3 2a1 1 0 1 1-2 0c0-2.626 2.516-4 5-4s5 1.374 5 4v16a1 1 0 0 1-1 1");
}

.v8fe-mbab {
  cx: 28px;
  cy: 34px;
  r: 2px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.yuxm_1gsd {
  fill: var(--svg-color--ffdc5d, #ffdc5d);
  d: path("M11 17c1 3 .209 5-2 5s-5.012-2.024-6-4c-1-2 .904-4.301 3-5c3-1 4.368 2.102 5 4");
}

</style>
