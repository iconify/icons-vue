<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="sm47_ub9m"/><circle class="ajou2zb6o"/><path class="cq9pvfbrp"/><path class="z_dk15b7a"/><path class="xcm3yeb4k"/><path class="md_e9gbeb"/><circle class="f7ycq8blf"/><circle class="u7kcu6bsd"/><circle class="ygvp66b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:shallow-pan-of-food" /></template>
<style>
.ajou2zb6o {
  cx: 18px;
  cy: 18px;
  r: 17px;
  fill: var(--svg-color--292f33, #292f33);
}

.cq9pvfbrp {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M31.6 18c0 7.511-6.089 13.6-13.6 13.6S4.4 25.511 4.4 18S10.489 4.4 18 4.4S31.6 10.489 31.6 18");
}

.f7ycq8blf {
  cx: 15px;
  cy: 17px;
  r: 2px;
  fill: var(--svg-color--f4900c, #f4900c);
}

.md_e9gbeb {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M9.333 16.5c0 1.933 3.099 3.5 1.167 3.5a3.5 3.5 0 1 1 0-7c1.933 0-1.167 1.567-1.167 3.5m8.685 9.49c1.599.771 4.136-1.167 3.364.433a3.217 3.217 0 1 1-5.794-2.798c.772-1.6.831 1.593 2.43 2.365");
}

.sm47_ub9m {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M2.488 33.514c2.41 2.41 5.103 3.627 7.688 1.042c1.835-1.835 1.368-5.277-1.043-7.689c-2.411-2.41-5.852-2.877-7.688-1.042c-2.585 2.585-1.368 5.277 1.043 7.689m6.553-6.554c1.808 1.808 2.158 4.39.782 5.767c-1.938 1.938-3.958 1.025-5.767-.783s-2.721-3.826-.782-5.766c1.376-1.376 3.958-1.026 5.767.782M33.513 2.487c-2.41-2.411-5.102-3.627-7.688-1.042c-1.835 1.835-1.368 5.277 1.043 7.688s5.851 2.878 7.688 1.042c2.585-2.585 1.368-5.278-1.043-7.688M26.96 9.04c-1.808-1.808-2.158-4.389-.782-5.766c1.938-1.938 3.958-1.026 5.767.782s2.721 3.827.782 5.766c-1.376 1.376-3.958 1.026-5.767-.782");
}

.u7kcu6bsd {
  cx: 24px;
  cy: 24px;
  r: 1px;
  fill: var(--svg-color--f4900c, #f4900c);
}

.xcm3yeb4k {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M27.669 20.336c.723-.723 2.551-3.826.021-6.356c-1.763-1.763-3.184-1.662-5.827-2.317c-1.084-.362-2.498-1.665-2.859-2.026c-.362.361-.235 1.683-.235 1.683s-1.575.128-1.937.489c.361.361 2.041 1.95 2.335 2.695c.79 2.508.7 3.784 2.464 5.546c2.891 2.891 5.316 1.009 6.038.286");
}

.ygvp66b4x {
  cx: 11px;
  cy: 23px;
  r: 1px;
  fill: var(--svg-color--f4900c, #f4900c);
}

.z_dk15b7a {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("m19.445 10.665l-2.539-2.539a1.121 1.121 0 0 0-1.655-1.511c-.27.27-.372.643-.311.991a1.124 1.124 0 0 0-.991 1.902c.415.415 1.07.433 1.511.064l2.539 2.538z");
}

</style>
