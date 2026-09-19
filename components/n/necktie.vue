<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="er_40mbih"/><g class="z3p269btt"><path class="pkrf5l-rz"/><path class="eqqxhxbwm"/></g><path class="zh-dvabdg"/><path class="x18_vlbpe"/><path class="m_x684b8g"/><path class="nvw_lnbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:necktie" /></template>
<style>
.eqqxhxbwm {
  d: path("m18.4 2.9l-3.3 6.6l12 17.7V15.1zm27.2 0l3.3 6.6l-12 17.7V15.1z");
}

.er_40mbih {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M64 59.7c0 2.4-2.2 4.3-4.9 4.3H4.9C2.2 64 0 62.1 0 59.7V9.1c0-2.4 2.2-4.3 4.9-4.3h54.2c2.7 0 4.9 1.9 4.9 4.3z");
}

.m_x684b8g {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("m38.1 27.6l-.3-3.3H26.3l-.3 3.3c2.4 1.8 9.5 1.7 12.1 0");
}

.nvw_lnbnu {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M38.6 24.4c-2.2 2.2-11.2 2.4-13.1 0c-2-2.5 1.6-12.2 1.6-12.2s3.7 1.4 4.9 1.4s4.9-1.4 4.9-1.4s4 9.9 1.7 12.2");
}

.pkrf5l-rz {
  d: path("M48.9 9.5H15.1L18.4 0h27.2z");
}

.x18_vlbpe {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M37.7 24.4H26.3L23 56.8l9.1 7.2l8.9-7.2z");
}

.z3p269btt {
  fill: var(--svg-color--94989b, #94989b);
}

.zh-dvabdg {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.4 0l-3.3 9.5l12 14.9V12.2zm27.2 0l3.3 9.5l-12 14.9V12.2z");
}

</style>
