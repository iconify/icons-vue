<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":314};
const content = `<defs><linearGradient id="SVG1ChKRdyM" x1="68.188%" x2="27.823%" y1="17.487%" y2="89.755%"><stop offset="0%" class="s2hyoh3lv"/><stop offset="32.88%" class="d7vudgn0g"/><stop offset="63.52%" class="gg43bqxfk"/><stop offset="93.19%" class="g1lzlhixa"/><stop offset="100%" class="ujpwwv57m"/></linearGradient><linearGradient id="SVGaMJtkcxE" x1="43.277%" x2="159.245%" y1="55.169%" y2="-18.306%"><stop offset="13.76%" class="s2hyoh3lv"/><stop offset="40.32%" class="dmoa5yb3v"/><stop offset="71.36%" class="c1olx2wpd"/><stop offset="90.81%" class="h0i5739eb"/></linearGradient><linearGradient id="SVG6PkGjd1W" x1="-4413.77%" x2="5327.93%" y1="13.43%" y2="13.43%"><stop offset="9.192%" class="h0i5739eb"/><stop offset="28.64%" class="c1olx2wpd"/><stop offset="59.68%" class="dmoa5yb3v"/><stop offset="86.24%" class="s2hyoh3lv"/></linearGradient><linearGradient id="SVGPqbGjbGu" x1="-4.389%" x2="101.499%" y1="49.997%" y2="49.997%"><stop offset="9.192%" class="h0i5739eb"/><stop offset="28.64%" class="c1olx2wpd"/><stop offset="59.68%" class="dmoa5yb3v"/><stop offset="86.24%" class="s2hyoh3lv"/></linearGradient><linearGradient id="SVGhSuPuc0t" x1="-9713.77%" x2="27.93%" y1="36.21%" y2="36.21%"><stop offset="9.192%" class="h0i5739eb"/><stop offset="28.64%" class="c1olx2wpd"/><stop offset="59.68%" class="dmoa5yb3v"/><stop offset="86.24%" class="s2hyoh3lv"/></linearGradient><linearGradient id="SVGFiwIH9Kx" x1="-103.861%" x2="100.797%" y1="50.275%" y2="50.275%"><stop offset="9.192%" class="h0i5739eb"/><stop offset="28.64%" class="c1olx2wpd"/><stop offset="59.68%" class="dmoa5yb3v"/><stop offset="86.24%" class="s2hyoh3lv"/></linearGradient><linearGradient id="SVGozO7odBP" x1="130.613%" x2="4.393%" y1="-211.069%" y2="201.605%"><stop offset="0%" class="s2hyoh3lv"/><stop offset="32.88%" class="d7vudgn0g"/><stop offset="63.52%" class="gg43bqxfk"/><stop offset="93.19%" class="g1lzlhixa"/><stop offset="100%" class="ujpwwv57m"/></linearGradient><path id="SVGnk2VSdjf" class="m5ukngs1j"/></defs><g class="ft5dv1b6b"><path class="b3-fk5blk"/><path class="u29lo4bcf"/><path class="vpm60l5yo"/><g transform="translate(134.068 70.501)"><mask id="SVGifRk2cfR" class="n1mjunbsu"><use href="#SVGnk2VSdjf"/></mask><use fill="url(#SVG1ChKRdyM)" href="#SVGnk2VSdjf"/><g mask="url(#SVGifRk2cfR)"><path class="o7d8chext"/><path fill="url(#SVGaMJtkcxE)" class="tg8qdkbkn"/></g><g mask="url(#SVGifRk2cfR)"><path class="v5wpwop0k"/><path fill="url(#SVG6PkGjd1W)" transform="translate(0 -9.246)" class="tbs5lcbgj"/><path fill="url(#SVGPqbGjbGu)" transform="translate(0 -9.246)" class="i-hksbbcm"/><path fill="url(#SVGhSuPuc0t)" transform="translate(0 -9.246)" class="s_oz67bms"/><path fill="url(#SVGFiwIH9Kx)" transform="translate(0 -9.246)" class="s95xvkbhn"/><path fill="url(#SVGozO7odBP)" transform="translate(0 -9.246)" class="s95xvkbhn"/></g></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:nodejs" /></template>
<style>
.b3-fk5blk {
  fill: var(--svg-color--539e43, #539e43);
  d: path("M253.11 313.094c-1.733 0-3.351-.462-4.854-1.271l-15.371-9.13c-2.312-1.272-1.156-1.734-.462-1.965c3.12-1.04 3.698-1.272 6.934-3.12c.347-.232.81-.116 1.156.115l11.789 7.05c.462.231 1.04.231 1.386 0l46.115-26.698c.462-.231.694-.694.694-1.271v-53.28c0-.579-.232-1.04-.694-1.272l-46.115-26.582c-.462-.232-1.04-.232-1.386 0l-46.115 26.582c-.462.231-.694.809-.694 1.271v53.28c0 .463.232 1.04.694 1.272l12.598 7.281c6.819 3.467 11.095-.578 11.095-4.623v-52.587c0-.693.578-1.387 1.387-1.387h5.894c.694 0 1.387.578 1.387 1.387v52.587c0 9.13-4.97 14.447-13.638 14.447c-2.658 0-4.738 0-10.633-2.89l-12.135-6.934c-3.005-1.733-4.854-4.97-4.854-8.437v-53.28c0-3.467 1.849-6.704 4.854-8.437l46.114-26.698c2.89-1.618 6.82-1.618 9.709 0l46.114 26.698c3.005 1.733 4.855 4.97 4.855 8.437v53.28c0 3.467-1.85 6.704-4.855 8.437l-46.114 26.698c-1.503.694-3.236 1.04-4.854 1.04m14.216-36.637c-20.225 0-24.386-9.246-24.386-17.105c0-.694.578-1.387 1.387-1.387h6.01c.693 0 1.271.462 1.271 1.156c.925 6.125 3.583 9.13 15.834 9.13c9.708 0 13.87-2.196 13.87-7.397c0-3.005-1.157-5.2-16.297-6.703c-12.598-1.272-20.457-4.045-20.457-14.1c0-9.362 7.86-14.91 21.035-14.91c14.793 0 22.075 5.086 23 16.18q0 .521-.347 1.041c-.232.231-.578.462-.925.462h-6.01c-.578 0-1.156-.462-1.271-1.04c-1.387-6.356-4.97-8.437-14.447-8.437c-10.633 0-11.905 3.699-11.905 6.472c0 3.352 1.503 4.392 15.834 6.241c14.216 1.85 20.92 4.508 20.92 14.447c-.116 10.171-8.437 15.95-23.116 15.95");
}

.c1olx2wpd {
  stop-color: var(--svg-color--66b848, #66b848);
}

.d7vudgn0g {
  stop-color: var(--svg-color--418b3d, #418b3d);
}

.dmoa5yb3v {
  stop-color: var(--svg-color--54a044, #54a044);
}

.ft5dv1b6b {
  fill: none;
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

.i-hksbbcm {
  fill-rule: evenodd;
  d: path("M106.792 105.636c1.387-.809 2.427-2.196 2.89-3.698L56.053 10.402c-1.387-.231-2.89-.116-4.16.693L3.351 39.065l52.355 95.465a8 8 0 0 0 2.196-.693z");
}

.m5ukngs1j {
  d: path("M57.903 1.85a5.96 5.96 0 0 0-5.894 0L3.352 29.933c-1.85 1.04-2.89 3.005-2.89 5.085v56.286c0 2.08 1.156 4.045 2.89 5.085l48.657 28.085a5.96 5.96 0 0 0 5.894 0l48.658-28.085c1.849-1.04 2.89-3.005 2.89-5.085V35.019c0-2.08-1.157-4.045-2.89-5.085z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.o7d8chext {
  d: path("M51.893 1.85L3.121 29.933C1.27 30.974 0 32.94 0 35.02v56.286c0 1.387.578 2.658 1.502 3.698L56.285 1.156c-1.387-.231-3.005-.116-4.392.693m4.739 123.204c.462-.116.925-.347 1.387-.578l48.773-28.085c1.85-1.04 3.005-3.005 3.005-5.085V35.019c0-1.502-.694-3.005-1.734-4.045z");
}

.s_oz67bms {
  fill-rule: evenodd;
  d: path("m111.3 104.712l-.347-.578v.809z");
}

.s2hyoh3lv {
  stop-color: var(--svg-color--41873f, #41873f);
}

.s95xvkbhn {
  fill-rule: evenodd;
  d: path("m106.792 105.636l-48.773 28.085a7 7 0 0 1-2.196.693l.925 1.734l54.089-31.32v-.694l-1.387-2.312c-.231 1.618-1.271 3.005-2.658 3.814");
}

.tbs5lcbgj {
  fill-rule: evenodd;
  d: path("m50.391.809l-.693.347h.924z");
}

.tg8qdkbkn {
  d: path("M106.676 29.934L57.788 1.85a8 8 0 0 0-1.503-.578L1.502 95.12a6.1 6.1 0 0 0 1.619 1.387l48.888 28.085c1.387.809 3.005 1.04 4.507.577l51.432-94.078c-.347-.462-.81-.81-1.272-1.156");
}

.u29lo4bcf {
  fill: var(--svg-color--333, #333);
  d: path("M110.028 104.712c0-2.08-1.156-4.046-3.005-5.086l-49.004-28.2c-.81-.463-1.734-.694-2.658-.81h-.463c-.924 0-1.849.347-2.658.81l-49.004 28.2c-1.85 1.04-3.005 3.005-3.005 5.086l.116 75.817c0 1.04.578 2.08 1.502 2.543c.925.578 2.08.578 2.89 0l29.125-16.643c1.849-1.04 3.005-3.005 3.005-5.085v-35.482c0-2.08 1.155-4.045 3.005-5.085l12.366-7.166c.925-.578 1.965-.81 3.005-.81s2.08.232 2.89.81l12.366 7.166c1.85 1.04 3.005 3.004 3.005 5.085v35.482c0 2.08 1.156 4.045 3.005 5.085l29.125 16.643a2.82 2.82 0 0 0 3.005 0c.925-.463 1.503-1.503 1.503-2.543zM345.571.347c-.924-.463-2.08-.463-2.89 0c-.924.578-1.502 1.502-1.502 2.542v75.125c0 .693-.346 1.386-1.04 1.849q-1.04.519-2.08 0l-12.251-7.05a5.96 5.96 0 0 0-5.895 0l-49.004 28.316c-1.849 1.04-3.005 3.005-3.005 5.085v56.516c0 2.08 1.156 4.046 3.005 5.086l49.004 28.316a5.96 5.96 0 0 0 5.895 0l49.004-28.316c1.849-1.04 3.005-3.005 3.005-5.086V21.844c0-2.196-1.156-4.16-3.005-5.201zm-4.507 143.776c0 .578-.231 1.04-.694 1.271l-16.758 9.708a1.71 1.71 0 0 1-1.503 0l-16.758-9.708c-.463-.231-.694-.809-.694-1.271v-19.417c0-.578.231-1.04.694-1.271l16.758-9.709a1.71 1.71 0 0 1 1.503 0l16.758 9.709c.463.23.694.809.694 1.271zm167.584-19.879c1.85-1.04 2.89-3.005 2.89-5.086v-13.753c0-2.08-1.156-4.045-2.89-5.085l-48.657-28.2a5.96 5.96 0 0 0-5.895 0l-49.004 28.315c-1.85 1.04-3.005 3.005-3.005 5.085v56.517c0 2.08 1.156 4.045 3.005 5.085l48.657 27.738c1.85 1.04 4.046 1.04 5.78 0L489 178.45c.925-.463 1.503-1.503 1.503-2.543s-.578-2.08-1.503-2.543l-49.235-28.316c-.925-.578-1.503-1.502-1.503-2.542v-17.683c0-1.04.578-2.08 1.503-2.543l15.371-8.784a2.82 2.82 0 0 1 3.005 0l15.372 8.784c.925.578 1.502 1.502 1.502 2.543v13.869c0 1.04.578 2.08 1.503 2.542a2.82 2.82 0 0 0 3.005 0z");
}

.ujpwwv57m {
  stop-color: var(--svg-color--3fae2a, #3fae2a);
}

.v5wpwop0k {
  d: path("M109.797 91.305V35.019c0-2.08-1.271-4.045-3.12-5.085L57.786 1.85a5.1 5.1 0 0 0-1.848-.693l53.511 91.42c.231-.347.347-.809.347-1.271M3.12 29.934C1.272 30.974 0 32.94 0 35.02v56.286c0 2.08 1.387 4.045 3.12 5.085l48.889 28.085q1.734 1.04 3.814.693L3.467 29.818z");
}

.vpm60l5yo {
  fill: var(--svg-color--539e43, #539e43);
  d: path("M456.292 121.585a1.05 1.05 0 0 1 1.156 0l9.362 5.432c.346.232.577.578.577 1.04v10.865c0 .462-.23.809-.577 1.04l-9.362 5.432a1.05 1.05 0 0 1-1.156 0l-9.361-5.432c-.347-.231-.578-.578-.578-1.04v-10.864c0-.463.23-.81.578-1.04z");
}

</style>
