<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":292};
const content = `<defs><linearGradient id="SVG1ChKRdyM" x1="68.188%" x2="27.823%" y1="17.487%" y2="89.755%"><stop offset="0%" class="s2hyoh3lv"/><stop offset="32.88%" class="d7vudgn0g"/><stop offset="63.52%" class="gg43bqxfk"/><stop offset="93.19%" class="g1lzlhixa"/><stop offset="100%" class="ujpwwv57m"/></linearGradient><linearGradient id="SVGaMJtkcxE" x1="43.277%" x2="159.245%" y1="55.169%" y2="-18.306%"><stop offset="13.76%" class="s2hyoh3lv"/><stop offset="40.32%" class="dmoa5yb3v"/><stop offset="71.36%" class="c1olx2wpd"/><stop offset="90.81%" class="h0i5739eb"/></linearGradient><linearGradient id="SVGPqbGjbGu" x1="-4.389%" x2="101.499%" y1="49.997%" y2="49.997%"><stop offset="9.192%" class="h0i5739eb"/><stop offset="28.64%" class="c1olx2wpd"/><stop offset="59.68%" class="dmoa5yb3v"/><stop offset="86.24%" class="s2hyoh3lv"/></linearGradient><path id="SVGoVetVcQA" class="hw_vrzbno"/></defs><path fill="url(#SVG1ChKRdyM)" class="hw_vrzbno"/><mask id="SVGp8cGfcMV" class="n1mjunbsu"><use href="#SVGoVetVcQA"/></mask><path fill="url(#SVGaMJtkcxE)" mask="url(#SVGp8cGfcMV)" class="o_q0g1xpk"/><path fill="url(#SVGPqbGjbGu)" mask="url(#SVGp8cGfcMV)" class="svxb7q1ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:nodejs-icon-alt" /></template>
<style>
.c1olx2wpd {
  stop-color: var(--svg-color--66b848, #66b848);
}

.d7vudgn0g {
  stop-color: var(--svg-color--418b3d, #418b3d);
}

.dmoa5yb3v {
  stop-color: var(--svg-color--54a044, #54a044);
}

.g1lzlhixa {
  stop-color: var(--svg-color--3fa92d, #3fa92d);
}

.gg43bqxfk {
  stop-color: var(--svg-color--419637, #419637);
}

.h0i5739eb {
  stop-color: var(--svg-color--6cc04a, #6cc04a);
}

.hw_vrzbno {
  d: path("M134.923 1.832c-4.344-2.443-9.502-2.443-13.846 0L6.787 67.801C2.443 70.244 0 74.859 0 79.745v132.208c0 4.887 2.715 9.502 6.787 11.945l114.29 65.968c4.344 2.444 9.502 2.444 13.846 0l114.29-65.968c4.344-2.443 6.787-7.058 6.787-11.945V79.745c0-4.886-2.715-9.501-6.787-11.944z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.o_q0g1xpk {
  d: path("M249.485 67.8L134.65 1.833c-1.086-.542-2.443-1.085-3.529-1.357L2.443 220.912c1.086 1.357 2.444 2.443 3.8 3.258l114.834 65.968c3.258 1.9 7.059 2.443 10.588 1.357L252.47 70.515c-.815-1.086-1.9-1.9-2.986-2.714");
}

.s2hyoh3lv {
  stop-color: var(--svg-color--41873f, #41873f);
}

.svxb7q1ut {
  d: path("M249.756 223.898c3.258-1.9 5.701-5.158 6.787-8.687L130.579.204c-3.258-.543-6.787-.272-9.773 1.628L6.786 67.53l122.979 224.238c1.628-.272 3.529-.815 5.158-1.63z");
}

.ujpwwv57m {
  stop-color: var(--svg-color--3fae2a, #3fae2a);
}

</style>
