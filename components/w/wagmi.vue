<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGUmbchbCs)" class="tyibrxb3c"/><defs><linearGradient id="SVGUmbchbCs" x1="3" x2="20.161" y1="10.788" y2="10.788" gradientUnits="userSpaceOnUse"><stop class="ffqf11p4o"/><stop offset="1" class="yctw9cc4l"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wagmi" /></template>
<style>
.ffqf11p4o {
  stop-color: var(--svg-color--dcc093, #dcc093);
}

.ft5dv1b6b {
  fill: none;
}

.tyibrxb3c {
  d: path("M3.116 4.286H3v6.14l9 7.727l9-8.145V4.325l-9 7.495zm13.796 0L12 8.53L7.089 4.286zM21 13.878l-6.943 5.837H21zm-10.993 5.837L3 13.672v6.043z");
}

.yctw9cc4l {
  stop-color: var(--svg-color--c4a878, #c4a878);
}

</style>
