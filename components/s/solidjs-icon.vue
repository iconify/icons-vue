<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":239,"left":256,"top":239};
const content = `<defs><linearGradient id="SVGzqueV6fZ" x1="27.5" x2="152" y1="3" y2="63.5" gradientTransform="translate(249.56 233.12)scale(1.61006)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="jg7y7xv_t"/><stop offset=".3" class="l3_n0iu4n"/><stop offset="1" class="jg7y7xv_t"/></linearGradient><linearGradient id="SVGuCz8Ub4Y" x1="95.8" x2="74" y1="32.6" y2="105.2" gradientTransform="translate(249.56 233.12)scale(1.61006)" gradientUnits="userSpaceOnUse"><stop offset="0" class="jg7y7xv_t"/><stop offset=".5" class="wtr_fdb0a"/><stop offset="1" class="tpk3--bmh"/></linearGradient><linearGradient id="SVGgHpuIdPS" x1="18.4" x2="144.3" y1="64.2" y2="149.8" gradientTransform="translate(249.56 233.12)scale(1.61006)" gradientUnits="userSpaceOnUse"><stop offset="0" class="so36b3c6c"/><stop offset=".5" class="d30anl59i"/><stop offset="1" class="so36b3c6c"/></linearGradient><linearGradient id="SVGBIJUtckh" x1="75.2" x2="24.4" y1="74.5" y2="260.8" gradientTransform="translate(249.56 233.12)scale(1.61006)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wtr_fdb0a"/><stop offset=".5" class="q34odkk-f"/><stop offset="1" class="q34odkk-f"/></linearGradient></defs><path class="cz6incb7m"/><path fill="url(#SVGzqueV6fZ)" class="mu9tabtge"/><path class="j_gewnhxx"/><path fill="url(#SVGuCz8Ub4Y)" class="r4awz_pvh"/><path fill="url(#SVGgHpuIdPS)" class="we6dmkbpn"/><path fill="url(#SVGBIJUtckh)" class="m1duttbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:solidjs-icon" /></template>
<style>
.cz6incb7m {
  fill: var(--svg-color--76b3e1, #76b3e1);
  d: path("M512 289.472s-85.333-62.791-151.347-48.301l-4.829 1.61c-9.66 3.221-17.711 8.05-22.542 14.491l-3.219 4.829l-24.152 41.862l41.863 8.051c17.71 11.27 40.251 16.101 61.182 11.27l74.063 14.491z");
}

.d30anl59i {
  stop-color: var(--svg-color--518ac8, #518ac8);
}

.j_gewnhxx {
  fill: var(--svg-color--518ac8, #518ac8);
  d: path("m333.282 289.472l-6.439 1.611c-27.371 8.05-35.421 33.811-20.932 56.352c16.101 20.931 49.913 32.201 77.284 24.151l99.824-33.811s-85.334-62.792-149.737-48.303");
}

.jg7y7xv_t {
  stop-color: var(--svg-color--76b3e1, #76b3e1);
}

.l3_n0iu4n {
  stop-color: var(--svg-color--dcf2fd, #dcf2fd);
}

.m1duttbpo {
  d: path("M433.106 418.277c-18.439-23.036-49.006-32.588-77.282-24.15L256 426.328s85.333 64.402 151.346 48.303l4.83-1.612c27.371-8.049 37.031-33.81 20.93-54.742");
}

.mu9tabtge {
  d: path("M512 289.472s-85.333-62.791-151.347-48.301l-4.829 1.61c-9.66 3.221-17.711 8.05-22.542 14.491l-3.219 4.829l-24.152 41.862l41.863 8.051c17.71 11.27 40.251 16.101 61.182 11.27l74.063 14.491z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.q34odkk-f {
  stop-color: var(--svg-color--1a336b, #1a336b);
}

.r4awz_pvh {
  d: path("m333.282 289.472l-6.439 1.611c-27.371 8.05-35.421 33.811-20.932 56.352c16.101 20.931 49.913 32.201 77.284 24.151l99.824-33.811s-85.334-62.792-149.737-48.303");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.so36b3c6c {
  stop-color: var(--svg-color--315aa9, #315aa9);
}

.tpk3--bmh {
  stop-color: var(--svg-color--1f3b77, #1f3b77);
}

.we6dmkbpn {
  d: path("M465.308 361.925c-18.439-23.036-49.008-32.588-77.283-24.15l-99.823 32.201L256 426.328l180.327 30.592l32.201-57.963c6.441-11.271 4.831-24.15-3.22-37.032");
}

.wtr_fdb0a {
  stop-color: var(--svg-color--4377bb, #4377bb);
}

</style>
