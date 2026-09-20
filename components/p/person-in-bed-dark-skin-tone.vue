<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mnwi0z5mo"/><path class="g40lcyopq"/><path class="zpcmxwi-k"/><path class="op9oufb-p"/><path class="n96nnxb5g"/><path class="vk_ke3fve"/><path class="rh6j849ls"/><ellipse transform="rotate(-62.651 9.598 19.046)" class="v0fvcqb1w"/><path class="f7cbmomig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:person-in-bed-dark-skin-tone" /></template>
<style>
.f7cbmomig {
  fill: var(--svg-color--0b0200, #0b0200);
  d: path("M7.875 22.376s-3.812-1.972-2.09-5.303c1.378-2.665 5.191-.693 5.191-.693s-1.906-.986-2.94 1.013c-.689 1.333 2.17 2.811-.161 4.983");
}

.g40lcyopq {
  fill: var(--svg-color--aa8dd8, #aa8dd8);
  d: path("M17 17h-2c-1.1 0-2 .9-2 2v4h4z");
}

.mnwi0z5mo {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M35 20a1 1 0 0 0-1 1v7H2V13a1 1 0 1 0-2 0v22a1 1 0 1 0 2 0v-2h32v2a1 1 0 1 0 2 0V21a1 1 0 0 0-1-1");
}

.n96nnxb5g {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M2.114 20.279c-.283 1.213 1.897 2.518 4.871 2.917c2.974.398 5.614-.263 5.898-1.475s-1.897-2.518-4.871-2.917c-2.973-.399-5.614.262-5.898 1.475");
}

.op9oufb-p {
  fill: var(--svg-color--bdddf4, #bdddf4);
  d: path("M13 23H4a2 2 0 0 0-2 2v4h10z");
}

.rh6j849ls {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M34 21H13.452c-.11.365-.197.705-.263 1H34z");
}

.v0fvcqb1w {
  cx: 9.598px;
  cy: 19.045px;
  fill: var(--svg-color--7c533e, #7c533e);
  rx: 3px;
  ry: 4.292px;
}

.vk_ke3fve {
  fill: var(--svg-color--269, #269);
  d: path("M13.189 22c-.134.595-.189 1-.189 1h21v-1z");
}

.zpcmxwi-k {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M31 18.222L17 17c-3.208 0-4 6-4 6h-1v6h22v-8c0-1.925-1.075-2.778-3-2.778");
}

</style>
