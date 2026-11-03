<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":237};
const content = `<defs><linearGradient id="SVGP7o34dXs" x1="0%" x2="100%" y1="0%" y2="100%"><stop offset="0%" class="noy6zvqys"/><stop offset="100%" class="bxfe4js4m"/></linearGradient></defs><path fill="url(#SVGP7o34dXs)" class="hx4z1-bvy"/><path fill="url(#SVGP7o34dXs)" class="v_gl41bbv"/><path fill="url(#SVGP7o34dXs)" class="o199i3bcx"/><path class="ni2_n1axa"/><circle class="uq3mdbq3v"/><circle class="nech1bqdn"/><circle class="sjcabnb6s"/><circle class="cz5p334mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:openclaw-icon" /></template>
<style>
.bxfe4js4m {
  stop-color: var(--svg-color--991b1b, #991b1b);
}

.cz5p334mj {
  cx: 164.009px;
  cy: 65.009px;
  r: 5.626px;
  fill: var(--svg-color--dde2e9, #dde2e9);
  opacity: var(--svg-opacity--0-82, 0.82);
}

.hx4z1-bvy {
  d: path("M128 10.996c-67.516 0-101.275 56.263-101.275 101.274s33.759 90.022 67.517 101.275v22.506h22.505v-22.506s11.253 4.501 22.506 0v22.506h22.505v-22.506c33.758-11.253 67.517-56.264 67.517-101.275c0-45.01-33.759-101.274-101.275-101.274");
}

.nech1bqdn {
  cx: 161.758px;
  cy: 67.259px;
  r: 13.503px;
  fill: var(--svg-color--181a1f, #181a1f);
}

.ni2_n1axa {
  fill: var(--svg-color--ff4d4d, #ff4d4d);
  d: path("M76.635 2.587c6.232 2.908 13.222 8.3 21.095 16.174a4.933 4.933 0 0 1-6.976 6.975c-7.13-7.13-13.27-11.866-18.29-14.209c-4.263-1.989-7.265-2.109-9.443-.803a4.933 4.933 0 1 1-5.075-8.46c5.324-3.194 11.7-2.939 18.69.323m121.418-.322a4.933 4.933 0 1 1-5.075 8.46c-2.178-1.307-5.18-1.187-9.442.802c-5.022 2.343-11.16 7.079-18.29 14.21a4.933 4.933 0 1 1-6.977-6.976c7.873-7.874 14.863-13.266 21.095-16.174c6.99-3.262 13.365-3.517 18.69-.322");
}

.noy6zvqys {
  stop-color: var(--svg-color--ff4d4d, #ff4d4d);
}

.o199i3bcx {
  d: path("M218.022 89.765c33.758-11.253 45.011 11.253 33.758 33.758s-33.758 11.253-45.01-11.253c-6.752-15.753 0-22.505 11.252-22.505");
}

.sjcabnb6s {
  cx: 96.492px;
  cy: 65.009px;
  r: 5.626px;
  fill: var(--svg-color--dde2e9, #dde2e9);
  opacity: var(--svg-opacity--0-82, 0.82);
}

.uq3mdbq3v {
  cx: 94.242px;
  cy: 67.259px;
  r: 13.503px;
  fill: var(--svg-color--181a1f, #181a1f);
}

.v_gl41bbv {
  d: path("M37.978 89.765C4.22 78.512-7.033 101.018 4.22 123.523s33.758 11.253 45.01-11.253c6.752-15.753 0-22.505-11.252-22.505");
}

</style>
