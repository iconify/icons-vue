<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="ba-8s6d9y"/><circle class="gmg-dmash"/><circle class="hdzmg-blf"/><circle class="n6s84ft2j"/><path class="h3t145b2r"/><circle class="lu6y77bay"/><circle class="hxuxkg7-l"/><path class="cpfm---ag"/><path class="mhne1abxu"/><path class="a_ynnhptd"/><path class="c2k-evbfs"/><path class="he908e7jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:panda" /></template>
<style>
.a_ynnhptd {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 20S7 23.687 7 27a6 6 0 0 0 11 3.315A6 6 0 0 0 29 27c0-3.313-11-7-11-7");
}

.ba-8s6d9y {
  cx: 7px;
  cy: 6px;
  r: 6px;
  fill: var(--svg-color--272b2b, #272b2b);
}

.c2k-evbfs {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M21 17s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2z");
}

.cpfm---ag {
  fill: var(--svg-color--272b2b, #272b2b);
  d: path("M20.709 12.654C25.163 9.878 32 17 26.952 22.67C23.463 26.591 20 25 20 25s-2.636-10.26.709-12.346m-5.442.011C10.813 9.888 3.976 17.01 9.023 22.681c3.49 3.92 6.953 2.329 6.953 2.329s2.636-10.26-.709-12.345");
}

.gmg-dmash {
  cx: 29px;
  cy: 6px;
  r: 6px;
  fill: var(--svg-color--272b2b, #272b2b);
}

.h3t145b2r {
  fill: var(--svg-color--eee, #eee);
  d: path("M35 22c0 7-6.375 12-17 12S1 29 1 22C1 22 2.308 0 18 0s17 22 17 22");
}

.hdzmg-blf {
  cx: 7px;
  cy: 6px;
  r: 4px;
  fill: var(--svg-color--66757f, #66757f);
}

.he908e7jw {
  fill: var(--svg-color--272b2b, #272b2b);
  d: path("M13.125 25c-1.624 1 3.25 4 4.875 4s6.499-3 4.874-4s-8.124-1-9.749 0");
}

.hxuxkg7-l {
  cx: 18px;
  cy: 30px;
  r: 4px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.lu6y77bay {
  cx: 18px;
  cy: 30px;
  r: 6px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.mhne1abxu {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M11 17s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2z");
}

.n6s84ft2j {
  cx: 29px;
  cy: 6px;
  r: 4px;
  fill: var(--svg-color--66757f, #66757f);
}

</style>
