<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dkboptbkx"/><path class="gssjfmb9r"/><circle class="htbyahblg"/><path class="j377ufb7b"/><path class="vtfov4bnl"/><path class="ajzzkfbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:rocket" /></template>
<style>
.ajzzkfbta {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M8 28s0-4 1-5s13.001-10.999 14-10s-9.001 13-10.001 14S8 28 8 28");
}

.dkboptbkx {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("m1 17l8-7l16 1l1 16l-7 8s.001-5.999-6-12s-12-6-12-6");
}

.gssjfmb9r {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M.973 35s-.036-7.979 2.985-11S15 21.187 15 21.187S14.999 29 11.999 32S.973 35 .973 35");
}

.htbyahblg {
  cx: 8.999px;
  cy: 27px;
  r: 4px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.j377ufb7b {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M35.999 0s-10 0-22 10c-6 5-6 14-4 16s11 2 16-4c10-12 10-22 10-22");
}

.vtfov4bnl {
  d: path("M26.999 5a4 4 0 0 0-3.641 2.36A4 4 0 0 1 24.999 7a4 4 0 0 1 4 4c0 .586-.133 1.139-.359 1.64A3.99 3.99 0 0 0 30.999 9a4 4 0 0 0-4-4");
}

</style>
