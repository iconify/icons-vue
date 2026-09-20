<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGfzZ9Cecc)" class="m9tkp0bxh"/><path fill="url(#SVG1VyWzHqU)" class="u6r8hsvqk"/><path fill="url(#SVGYG217bJx)" class="qboslcboi"/><path fill="url(#SVGrlrFSb1r)" class="ndxf11bmi"/></g><defs><linearGradient id="SVGfzZ9Cecc" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="v0s2c_06o"/><stop offset="1" class="qgbgi-bvo"/></linearGradient><linearGradient id="SVG1VyWzHqU" x1="12" x2="12" y1="3.999" y2="19.999" gradientUnits="userSpaceOnUse"><stop class="i4yxaebqy"/><stop offset="1" class="u9b-j3blt"/></linearGradient><linearGradient id="SVGYG217bJx" x1="12" x2="12" y1="3.999" y2="20" gradientUnits="userSpaceOnUse"><stop class="zvi-6sbvs"/><stop offset=".496" class="kjj05abgk"/><stop offset="1" class="f5nymbcvb"/></linearGradient><linearGradient id="SVGrlrFSb1r" x1="12.008" x2="12.008" y1="8.637" y2="14.137" gradientUnits="userSpaceOnUse"><stop class="bqzbqcbyb"/><stop offset="1" class="su1_1ybkr"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sha-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bqzbqcbyb {
  stop-color: var(--svg-color--31237b, #31237b);
}

.f5nymbcvb {
  stop-color: var(--svg-color--faeffd, #faeffd);
}

.ft5dv1b6b {
  fill: none;
}

.i4yxaebqy {
  stop-color: var(--svg-color--f8f9fb, #f8f9fb);
}

.kjj05abgk {
  stop-color: var(--svg-color--a27dc3, #a27dc3);
}

.m9tkp0bxh {
  d: path("M12.2 4.036a.53.53 0 0 0-.389 0q-2.702.973-5.401 1.953c-.22.084-.352.268-.352.393v5.033c0 3.134.834 4.67 1.785 5.805c1.853 1.987 3.796 2.618 3.971 2.733c.13.085.317.036.395 0c1.696-.745 3.215-1.887 3.938-2.733c1.428-1.675 1.795-3.174 1.795-5.806V6.337c0-.204-.2-.317-.3-.349z");
}

.ndxf11bmi {
  d: path("M12.668 11.141a1.371 1.371 0 1 0-1.346-.006l-.693 2.922h2.743z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qboslcboi {
  d: path("M12.169 4.946a.43.43 0 0 0-.329 0q-2.286.86-4.57 1.73c-.186.073-.298.236-.298.347v4.457c0 2.776.705 4.136 1.51 5.14c1.568 1.76 3.212 2.32 3.36 2.422c.11.075.269.032.335 0c1.434-.66 2.72-1.671 3.331-2.421c1.208-1.483 1.52-2.81 1.52-5.141V6.985c0-.181-.17-.282-.255-.309z");
}

.qgbgi-bvo {
  stop-color: var(--svg-color--b02cbc, #b02cbc);
}

.su1_1ybkr {
  stop-color: var(--svg-color--72259e, #72259e);
}

.u6r8hsvqk {
  d: path("M12.184 4.49a.48.48 0 0 0-.358 0Q9.33 5.407 6.84 6.33c-.203.079-.325.252-.325.37v4.745c0 2.955.77 4.402 1.647 5.473c1.711 1.873 3.504 2.468 3.666 2.577c.12.08.293.033.365 0c1.565-.703 2.968-1.779 3.634-2.577c1.319-1.579 1.658-2.992 1.658-5.473V6.659c0-.192-.185-.299-.278-.328z");
}

.u9b-j3blt {
  stop-color: var(--svg-color--af2cbb, #af2cbb);
}

.v0s2c_06o {
  stop-color: var(--svg-color--132368, #132368);
}

.zvi-6sbvs {
  stop-color: var(--svg-color--1b246c, #1b246c);
}

</style>
