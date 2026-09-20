<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="lpxf29bmg"/><circle class="j3e5hubtg"/><circle class="hxuxkg7-l"/><circle class="f62_51bdh"/><circle class="teenvebbu"/><circle class="zfi1ojv3g"/><path class="p27dhee_k"/><path class="wnd4fkb_k"/><path class="b9o-tib5x"/><path class="nu2aowbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:tiger-face" /></template>
<style>
.b9o-tib5x {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.678 23c-2.402 0-4.501.953-5.678 2.378C16.823 23.953 14.723 23 12.321 23C2 23 2.043 23.421 2 26.182c-.087 5.61 6.63 6.9 10.321 6.818c2.401-.053 4.502-.989 5.679-2.397c1.177 1.408 3.276 2.345 5.678 2.397c3.691.082 10.409-1.208 10.321-6.818c-.043-2.761 0-3.182-10.321-3.182");
}

.f62_51bdh {
  cx: 29px;
  cy: 6px;
  r: 6px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.hxuxkg7-l {
  cx: 18px;
  cy: 30px;
  r: 4px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.j3e5hubtg {
  cx: 18px;
  cy: 30px;
  r: 6px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.lpxf29bmg {
  cx: 7px;
  cy: 6px;
  r: 6px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.nu2aowbhg {
  fill: var(--svg-color--272b2b, #272b2b);
  d: path("M33.66 25.242c.204.279.333.588.339.939c.03 1.905-.745 3.303-1.915 4.327L26.999 31zM15 25c-1 1 2 4 3 4s4-3 3-4s-5-1-6 0M10 3c2.667 2 8 4 8 4s5.333-2 8-4l-8 1zm8-1s1.652-.62 3.576-1.514C20.48.178 19.295 0 18 0s-2.481.178-3.576.486C16.348 1.38 18 2 18 2m-7 7c3 2 7 4 7 4s4-2 7-4l-7 1zm20.645 2.285L27 15l6.006.75a36 36 0 0 0-1.361-4.465m1.911 7.159L28 24h5.835A12 12 0 0 0 34 22s-.081-1.43-.444-3.556m-31.112 0C2.082 20.57 2 22 2 22c0 .748.063 1.405.165 2H8zm-.105 6.798c-.204.279-.333.588-.339.94c-.03 1.905.745 3.303 1.916 4.327L9 31zM9 15l-4.644-3.715a36 36 0 0 0-1.361 4.466z");
}

.p27dhee_k {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M34 22c0 7-4.923 7-4.923 7H6.923S2 29 2 22C2 22 3.231 0 18 0s16 22 16 22");
}

.teenvebbu {
  cx: 7px;
  cy: 6px;
  r: 4px;
  fill: var(--svg-color--e6aaaa, #e6aaaa);
}

.wnd4fkb_k {
  fill: var(--svg-color--272b2b, #272b2b);
  d: path("M11 17s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2zm10 0s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2z");
}

.zfi1ojv3g {
  cx: 29px;
  cy: 6px;
  r: 4px;
  fill: var(--svg-color--e6aaaa, #e6aaaa);
}

</style>
