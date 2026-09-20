<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eztt9wbjn"/><circle class="fs_72-4ea"/><path class="fktge7bsz"/><path class="k7uc1cv5r"/><path class="vojt6v8qs"/><circle class="x3kcf326r"/><path class="j_1ckmbkm"/><circle transform="rotate(-60.007 30.447 50.681)" class="k9afq4b6g"/><circle class="ds-_ivd-g"/><path class="g-k155a4e"/><circle transform="rotate(-60.007 44.629 103.607)" class="alyz7zbys"/><circle class="ohpx6r69f"/><circle transform="rotate(-29.991 83.37 103.603)" class="dpqki2bed"/><ellipse transform="rotate(-59.974 97.546 89.428)" class="v18r_q2uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:stopwatch" /></template>
<style>
.alyz7zbys {
  cx: 44.63px;
  cy: 103.61px;
  r: 2.86px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.dpqki2bed {
  cx: 83.37px;
  cy: 103.61px;
  r: 2.86px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.ds-_ivd-g {
  cx: 25.26px;
  cy: 70.05px;
  r: 2.86px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.eztt9wbjn {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m90.007 16.411l3.95-6.841l9.327 5.385l-3.95 6.841zm-1.009 5.09l2.425-4.2l6.062 3.5l-2.425 4.2zM54.03 0h19.94v7.98H54.03zM58 8h12v11H58z");
}

.fktge7bsz {
  fill: var(--svg-color--fff, #fff);
  d: path("M64 114.85c-24.7 0-44.8-20.09-44.8-44.8c0-24.7 20.09-44.79 44.8-44.79c24.7 0 44.79 20.1 44.79 44.79c.01 24.71-20.09 44.8-44.79 44.8");
}

.fs_72-4ea {
  cx: 64px;
  cy: 70.05px;
  r: 57px;
  fill: var(--svg-color--19699d, #19699d);
}

.g-k155a4e {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M29.02 86.95a2.87 2.87 0 0 0-1.05 3.9a2.853 2.853 0 0 0 3.9 1.05a2.85 2.85 0 0 0 1.05-3.9a2.86 2.86 0 0 0-3.9-1.05");
}

.j_1ckmbkm {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M98.98 53.16a2.87 2.87 0 0 0 1.05-3.91a2.87 2.87 0 0 0-3.9-1.05a2.87 2.87 0 0 0-1.05 3.91a2.85 2.85 0 0 0 3.9 1.05M84.8 34.03a2.85 2.85 0 0 0-3.9 1.05a2.853 2.853 0 0 0 1.05 3.9c1.37.79 3.12.32 3.9-1.05a2.85 2.85 0 0 0-1.05-3.9m-41.6-.01a2.86 2.86 0 0 0-1.05 3.9a2.85 2.85 0 0 0 3.9 1.05a2.847 2.847 0 0 0 1.04-3.9a2.854 2.854 0 0 0-3.89-1.05");
}

.k7uc1cv5r {
  fill: var(--svg-color--bee8f1, #bee8f1);
  d: path("M64 20.48c-27.34 0-49.58 22.25-49.58 49.58c0 27.34 22.24 49.58 49.58 49.58s49.58-22.24 49.58-49.58S91.34 20.48 64 20.48m0 94.37c-24.7 0-44.8-20.09-44.8-44.8c0-24.7 20.09-44.79 44.8-44.79c24.7 0 44.79 20.1 44.79 44.79c.01 24.71-20.09 44.8-44.79 44.8");
}

.k9afq4b6g {
  cx: 30.45px;
  cy: 50.68px;
  r: 2.86px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.ohpx6r69f {
  cx: 64px;
  cy: 108.8px;
  r: 2.86px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.v18r_q2uv {
  cx: 97.55px;
  cy: 89.43px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  rx: 2.85px;
  ry: 2.86px;
}

.vojt6v8qs {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M68.63 64.08V43.54h-1.06V31.98c0-1.54-1.25-2.79-2.79-2.79h-1.57c-1.54 0-2.79 1.25-2.79 2.79v11.56h-1.06v20.54c-2.17 1.68-3.43 4.48-2.79 7.56c.61 2.94 2.98 5.3 5.93 5.86c4.84.92 9.08-2.76 9.08-7.45c.01-2.44-1.16-4.58-2.95-5.97m-7.01 7.56c-.05-.08-.09-.17-.13-.25c-.22-.4-.35-.85-.35-1.34c0-.48.13-.94.35-1.34c.48-.9 1.42-1.52 2.51-1.52s2.03.63 2.51 1.53c.21.4.35.85.35 1.33c0 .49-.13.94-.35 1.34c-.04.09-.08.18-.13.25c-.31.46-.74.82-1.25 1.04c-.01.01-.03.01-.04.02c-.33.13-.7.21-1.08.21c-.39 0-.75-.08-1.08-.21c-.01-.01-.03-.01-.04-.02c-.53-.22-.96-.58-1.27-1.04");
}

.x3kcf326r {
  cx: 102.74px;
  cy: 70.06px;
  r: 2.86px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

</style>
