<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVG3BXDpbgq" x1="64" x2="64" y1="34.333" y2="110.86" gradientUnits="userSpaceOnUse"><stop offset="0" class="ak45bo23a"/><stop offset="1" class="iwryzprlb"/></linearGradient><path fill="url(#SVG3BXDpbgq)" class="zg8ocbcxm"/><g class="tncun38sa"><linearGradient id="SVGY6BIfLzA" x1="58.569" x2="58.569" y1="17.695" y2="39.902" gradientTransform="matrix(1.0651 -.1281 .1293 1.0755 -16.28 -1.387)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset=".136" class="u24ka2b2d"/><stop offset=".311" class="zomvvbcmt"/><stop offset=".508" class="z494f1bfm"/><stop offset=".722" class="c8hgyxr3x"/><stop offset=".948" class="kwpypqzpr"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGY6BIfLzA)" class="hdxycw6yc"/><linearGradient id="SVGcpq5veHu" x1="62.767" x2="62.767" y1="27.316" y2="46.182" gradientTransform="matrix(.9919 -.2786 .2895 1.0307 -24.035 6.935)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset=".136" class="u24ka2b2d"/><stop offset=".311" class="zomvvbcmt"/><stop offset=".508" class="z494f1bfm"/><stop offset=".722" class="c8hgyxr3x"/><stop offset=".948" class="kwpypqzpr"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGcpq5veHu)" class="rhc9j-bbo"/><linearGradient id="SVGv1JQ9Lsm" x1="66.786" x2="66.786" y1="29.593" y2="47.655" gradientTransform="rotate(-24.638 44.084 77.814)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset=".136" class="u24ka2b2d"/><stop offset=".311" class="zomvvbcmt"/><stop offset=".508" class="z494f1bfm"/><stop offset=".722" class="c8hgyxr3x"/><stop offset=".948" class="kwpypqzpr"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGv1JQ9Lsm)" class="ohbtl3blw"/><linearGradient id="SVGMqYFRyEo" x1="133.39" x2="133.39" y1="26.606" y2="48.812" gradientTransform="matrix(-1.0651 -.1281 -.1293 1.0755 225.13 -1.387)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset=".136" class="u24ka2b2d"/><stop offset=".311" class="zomvvbcmt"/><stop offset=".508" class="z494f1bfm"/><stop offset=".722" class="c8hgyxr3x"/><stop offset=".948" class="kwpypqzpr"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGMqYFRyEo)" class="w_n_17bru"/><linearGradient id="SVGEWZ9vi9B" x1="138.32" x2="138.32" y1="47.737" y2="66.602" gradientTransform="matrix(-.9919 -.2786 -.2895 1.0307 232.88 6.935)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset=".136" class="u24ka2b2d"/><stop offset=".311" class="zomvvbcmt"/><stop offset=".508" class="z494f1bfm"/><stop offset=".722" class="c8hgyxr3x"/><stop offset=".948" class="kwpypqzpr"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGEWZ9vi9B)" class="q2txbgbhp"/><linearGradient id="SVGcIljKbIn" x1="140.28" x2="140.28" y1="63.296" y2="81.358" gradientTransform="rotate(24.638 60.343 556)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset=".136" class="u24ka2b2d"/><stop offset=".311" class="zomvvbcmt"/><stop offset=".508" class="z494f1bfm"/><stop offset=".722" class="c8hgyxr3x"/><stop offset=".948" class="kwpypqzpr"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGcIljKbIn)" class="tg4imwipn"/></g><path class="gu-81ccsp"/><path class="bn6bipb5r"/><linearGradient id="SVGFjFVLd4M" x1="78.815" x2="84.271" y1="49.594" y2="36.305" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGFjFVLd4M)" class="g7bwphu5j"/><path class="zyi0t3bzm"/><linearGradient id="SVG6V5prcSO" x1="63.177" x2="63.177" y1="56.031" y2="91.612" gradientUnits="userSpaceOnUse"><stop offset="0" class="hs8__5lpv"/><stop offset=".997" class="pcyjh7p8j"/></linearGradient><path fill="url(#SVG6V5prcSO)" class="x4cgyhp8l"/><path class="dcut70b9j"/><linearGradient id="SVGgsJSxblJ" x1="63.681" x2="63.681" y1="23.984" y2="64.169" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGgsJSxblJ)" class="il8_k_vpn"/><path class="qxw7w3brl"/><path class="xbplr95cb"/><path class="lzgjwcbuj"/><linearGradient id="SVGCGu5PbHu" x1="63.985" x2="63.985" y1="26.331" y2="4.95" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".216" class="m3cq709zi"/><stop offset=".573" class="k69-rnpfa"/><stop offset="1" class="tisq54bqj"/></linearGradient><path fill="url(#SVGCGu5PbHu)" class="h99_zjb3o"/><path class="dyap9ybls"/><path class="vj-mqqb2k"/><path class="p50zshbtx"/><path class="si3tfpbbe"/><radialGradient id="SVGve2WadJe" cx="60.467" cy="17.09" r="3.376" gradientTransform="rotate(22.135 33.964 11.583)scale(1 .3973)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="la1q1sbut"/><stop offset=".072" class="zofgs1bky"/><stop offset=".712" class="j6d92kb5k"/><stop offset="1" class="en-lbmvhf"/></radialGradient><path fill="url(#SVGve2WadJe)" class="pd0od1zgl"/><path class="b25nc8bun"/><radialGradient id="SVG42taZc4Y" cx="128.53" cy="17.39" r="3.375" gradientTransform="rotate(157.865 95.743 -.846)scale(1 -.3973)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="la1q1sbut"/><stop offset=".072" class="zofgs1bky"/><stop offset=".712" class="j6d92kb5k"/><stop offset="1" class="en-lbmvhf"/></radialGradient><path fill="url(#SVG42taZc4Y)" class="kpqco5bss"/><path class="ma0bv3brs"/><path class="t0sle7b8p"/><radialGradient id="SVGnbE58c6B" cx="59.684" cy="34.333" r="3.841" gradientTransform="matrix(.9649 -.0175 .0701 1.0351 6.385 3.193)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="la1q1sbut"/><stop offset=".072" class="zofgs1bky"/><stop offset=".712" class="j6d92kb5k"/><stop offset="1" class="en-lbmvhf"/></radialGradient><path fill="url(#SVGnbE58c6B)" class="i982jb03n"/><path class="tp7he0bmn"/><linearGradient id="SVGVqq5geqT" x1="29.486" x2="55.539" y1="31.867" y2="27.85" gradientUnits="userSpaceOnUse"><stop offset=".003" class="pcyjh7p8j"/><stop offset="1" class="hs8__5lpv"/></linearGradient><path fill="url(#SVGVqq5geqT)" class="i3pmzabmw"/><path class="xidbg2bsq"/><path class="gegt69bbt"/><path class="ugujspbkg"/><path class="opysq0wvx"/><linearGradient id="SVGyOlF0HVb" x1="23.415" x2="35.025" y1="4.267" y2="30.012" gradientUnits="userSpaceOnUse"><stop offset="0" class="a9ktnkbvg"/><stop offset=".356" class="f1ygkh_0q"/><stop offset=".719" class="j6pw57qfe"/><stop offset=".997" class="r_nlw5wtb"/></linearGradient><path fill="url(#SVGyOlF0HVb)" class="eezw7yu6m"/><linearGradient id="SVGagAgNdCg" x1="90.522" x2="101.4" y1="24.083" y2="48.207" gradientUnits="userSpaceOnUse"><stop offset="0" class="a9ktnkbvg"/><stop offset=".356" class="f1ygkh_0q"/><stop offset=".719" class="j6pw57qfe"/><stop offset=".997" class="r_nlw5wtb"/></linearGradient><path fill="url(#SVGagAgNdCg)" class="w5_fr9wdn"/><defs><path id="SVGnupjDdGU" class="uegphzbvm"/></defs><clipPath id="SVGvhcbSXbR"><use href="#SVGnupjDdGU"/></clipPath><g clip-path="url(#SVGvhcbSXbR)"><radialGradient id="SVG5rBhMbBD" cx="240.81" cy="-23.604" r="12.949" gradientTransform="rotate(.005 -222950.837 -1489871.88)scale(.796)" gradientUnits="userSpaceOnUse"><stop offset="0" class="m_5onzv2u"/><stop offset="1" class="mu7wwsbgh"/></radialGradient><path fill="url(#SVG5rBhMbBD)" class="rjiyx1bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:woman-supervillain-medium-dark-skin-tone" /></template>
<style>
.a9ktnkbvg {
  stop-color: var(--svg-color--17cb1f, #17cb1f);
}

.ak45bo23a {
  stop-color: var(--svg-color--691b66, #691b66);
}

.asbw0jbgl {
  stop-color: var(--svg-color--8d5738, #8d5738);
}

.b25nc8bun {
  d: path("M58.38 15.96c.46 0 1.03.04 1.51.19c.97.31 1.75.81 1.62 1.23c-.08.24-.42.38-.87.38c-.35 0-.77-.09-1.18-.28c-1.1-.52-1.9-1.48-1.9-1.48s.35-.04.82-.04m0-.57c-.5 0-.87.04-.89.05l-1.05.12l.68.81c.04.04.9 1.06 2.08 1.63c.45.22.96.34 1.43.34c.73 0 1.26-.29 1.41-.77c.24-.75-.48-1.46-1.98-1.95c-.45-.16-1.02-.23-1.68-.23m7.11 1.11c.24 0 .48-.02.71-.05l.34-.05l.33-.07c.22-.04.43-.11.65-.17s.42-.13.63-.2c.82-.31 1.61-.69 2.35-1.17l.51-.33l-.13-.43c-.06-.19-.12-.37-.2-.55l-.11-.28l-.13-.27c-.08-.18-.18-.36-.28-.54s-.22-.35-.35-.53l-.09.02l.18 1.15l.2 1.15l.04-.08l-1.18.57l-1.18.58l-1.18.59c-.39.19-.78.4-1.17.6z");
}

.bn6bipb5r {
  fill: var(--svg-color--291d15, #291d15);
  d: path("M64.17 2.56c3.21 0 5.71.88 7.42 2.63c2.63 2.69 2.63 6.65 2.62 7.13c0 9.99-1.09 17.01-3.08 19.77c-.78 1.08-2.4 1.18-2.38 1.18l-4.74-.01l-4.7.01c-.02 0-1.64-.09-2.42-1.18c-1.99-2.76-3.08-9.78-3.08-19.78c0-.17.02-4.28 2.81-7.07c1.77-1.78 4.31-2.68 7.55-2.68m0-1c-11.45 0-11.36 10.59-11.36 10.76c0 6.86.52 16.54 3.27 20.35c1.09 1.51 3.19 1.59 3.19 1.59l4.74-.01l4.74.01s2.1-.08 3.19-1.59c2.74-3.81 3.27-13.5 3.27-20.35c0-.17.41-10.76-11.04-10.76");
}

.c8hgyxr3x {
  stop-color: var(--svg-color--0e305b, #0e305b);
}

.dcut70b9j {
  fill: var(--svg-color--0e2b52, #0e2b52);
  d: path("M55.68 56.29c1.23.46 3.97 1.58 7.83 3.76c.84.47 1.7.71 2.55.71c2.12 0 3.68-1.46 4.54-2.55q.255.27.6.63c.45.47 1.07 1.12 1.18 1.27a.9.9 0 0 1-.14-.33c.22 1.04 8.74 12.85 16.03 22.82c-.84 1.26-2.99 4.33-5 6.02c-2.36-3.43-10.13-12.34-14.07-16.49c-.92-.96-2.15-1.5-3.48-1.5c-1.28 0-2.48.5-3.38 1.4c-6 6.01-13.08 13.34-15.23 15.7c-3.19-.61-7.12-2.01-8.97-2.7c1.44-2.71 5.58-10.38 9.18-16.18c.04-.07.45-.68 1.07-1.61c4.65-6.93 6.52-9.75 7.29-10.95m-.43-1.21c-.04.2-8.65 13.1-8.75 13.25c-4.5 7.25-9.75 17.25-9.75 17.25s6.25 2.5 10.75 3.25c1.53-1.75 9.16-9.66 15.57-16.08c.74-.74 1.7-1.11 2.67-1.11c1 0 2.01.4 2.76 1.18c5.55 5.86 14.17 16.09 14.5 17.26c2.97-1.89 6.5-7.5 6.5-7.5s-16.04-21.93-16.27-23c-.04-.18-2.69-2.8-2.73-3c0 0-1.69 3.18-4.44 3.18c-.63 0-1.32-.17-2.06-.58c-5.5-3.1-8.75-4.1-8.75-4.1");
}

.dyap9ybls {
  fill: var(--svg-color--875334, #875334);
  d: path("M63.99 5c5.1 0 8.26 5.9 8.26 11.36c0 4.77-2.58 9.9-8.26 9.9c-5.67 0-8.26-5.13-8.26-9.9C55.73 10.9 58.89 5 63.99 5m0-.5c-4.55 0-8.76 4.86-8.76 11.86c0 6.96 4.34 10.4 8.76 10.4s8.76-3.44 8.76-10.4c-.01-7-4.22-11.86-8.76-11.86");
}

.eezw7yu6m {
  stroke: var(--svg-color--009245, #009245);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M34.24 9.14c.36.36.96.36 1.33 0c.36-.36.36-.96 0-1.33L34.3 6.24c-1.32-1.57-2.54-.82-2.54-.82c.03-.16.03-.32-.03-.48a.937.937 0 0 0-1.2-.55s-1.58.26-1.68.13a.947.947 0 0 0-1.32-.14L25.3 6.2c-.25.2-2.31 4.39-2.71 7.97c-.67 6 .7 13.92 4.17 21c0 0 1.39-3.67 3.04-5.4c1.18-1.26 3.18-2.39 5.26-2.43c0 0-.53-2.46-4.36-8.13c-1.65-2.44-2.19-4.07-2.13-5.37h2.87a.939.939 0 1 0 0-1.88h-1.63c-2.12-1.19.04-3.15 1.15-3.92c.67-.46 1.35-.21 1.35-.21z");
}

.en-lbmvhf {
  stop-color: var(--svg-color--730000, #730000);
}

.f1ygkh_0q {
  stop-color: var(--svg-color--0bb42e, #0bb42e);
}

.g7bwphu5j {
  d: path("M86.34 52.95c-.67 0-1.3-.25-1.76-.72L70.44 38.09c-.97-.97-.97-2.56 0-3.54l1.95-1.94c.31-.31.99-.49 1.87-.49c1.44 0 3.04.47 3.64 1.07L87.74 47l3.19-4.09c.38-.32.96-.53 1.56-.53c.73 0 1.42.32 1.9.87l.22.25c.43.5.64 1.15.59 1.82s-.35 1.27-.86 1.71l-6.19 5.33c-.45.38-1.01.59-1.63.59z");
}

.gegt69bbt {
  d: path("m33.8 85.39l12.78 3.68l9.61 30.88c.03.17-.01.24-.06.31c-.73 1.02-4.41 1.41-5.99 1.58c-.43.05-.81.09-1.12.13c-2.94.4-5.65.6-8.05.6c-5.47 0-8.46-1.02-10.04-1.94c17.75-3.75 18.35-5.19 18.68-5.97c.2-.48.15-.99-.12-1.42c-3.84-5.98-12.14-21.26-15.69-27.85m-.26-1.35c-.82 0-1.43.9-1 1.69c3.27 6.08 11.94 22.05 15.88 28.19c.89 1.39-12.71 4.41-18.06 5.53c-1.01.21-1.24 1.54-.37 2.09c1.7 1.08 4.96 2.3 10.98 2.3c2.31 0 5.03-.18 8.23-.61c2.28-.31 8.91-.54 8.22-3.6l-9.65-31c-.11-.37-.41-.65-.78-.76l-13.13-3.78a.9.9 0 0 0-.32-.05");
}

.gu-81ccsp {
  fill: var(--svg-color--3b2c22, #3b2c22);
  d: path("M59.27 33.76s-1.86-.1-2.79-1.39c-2.05-2.84-3.17-9.97-3.17-20.06c0-.19.02-4.5 2.95-7.43c1.87-1.87 4.53-2.82 7.91-2.82c3.35 0 5.97.94 7.77 2.78c2.72 2.77 2.78 6.69 2.76 7.45c0 10.12-1.13 17.25-3.17 20.09c-.9 1.25-2.66 1.38-2.8 1.39L64 33.76z");
}

.h99_zjb3o {
  d: path("M63.99 26.51c-4.1 0-8.51-3.18-8.51-10.15c0-5.58 3.25-11.61 8.51-11.61s8.51 6.03 8.51 11.61c-.01 6.97-4.42 10.15-8.51 10.15");
}

.hdxycw6yc {
  stroke-width: var(--svg-stroke-width--1-368px, 1.368px);
  d: path("m35.75 14.48l12.55-4.43l16.01 22.96l-6.75.54l-9.87-19.93z");
}

.hs8__5lpv {
  stop-color: var(--svg-color--170d1f, #170d1f);
}

.i3pmzabmw {
  d: path("M33.55 40c-1.67 0-3.2-1.04-3.8-2.59l-4.12-10.63c-.4-1.03.11-2.2 1.15-2.6l2.74-1.06c.23-.09.47-.14.72-.14c.83 0 1.58.52 1.88 1.28l2.82 7.26l16.09-4.28c.33-.09.67-.13 1.02-.13c1.81 0 3.39 1.22 3.85 2.96c.56 2.12-.7 4.3-2.82 4.87l-18 4.79c-.56.18-1.04.27-1.53.27");
}

.i982jb03n {
  d: path("M64.33 36.39L66 32.47l2.26 3.82l-1.57 6.6z");
}

.il8_k_vpn {
  d: path("M66.19 63.89c-.97 0-1.89-.37-2.59-1.04l-7.1-6.78c-.63-.6-1.03-1.4-1.13-2.26c-.17-1.42-.55-3.75-1.38-6.86c-1.4-5.21-3.1-9.75-4.22-12.76c-.41-1.1-.73-1.96-.91-2.52c-.75-2.32-.7-4.08.13-5.22c.85-1.17 2.58-1.77 5.12-1.77c4.58 0 10.17 1.97 10.23 1.99c1.08.41 2.26.78 3.51 1.17c5.56 1.75 11.87 3.73 11.13 10.02c-.02.21-.08.44-.15.69c-.8 2.51-4.81 15.26-5.76 19.22c-.17.7-.52 1.33-1.01 1.82c-.83.82-2.06 2.05-3.21 3.2c-.72.71-1.66 1.1-2.66 1.1");
}

.iwryzprlb {
  stop-color: var(--svg-color--c735c1, #c735c1);
}

.j6d92kb5k {
  stop-color: var(--svg-color--980000, #980000);
}

.j6pw57qfe {
  stop-color: var(--svg-color--03a438, #03a438);
}

.k69-rnpfa {
  stop-color: var(--svg-color--a26941, #a26941);
}

.kpqco5bss {
  d: path("M67.34 18.05c-.6 0-1.03-.21-1.14-.57a.68.68 0 0 1 .05-.5c.29-.57 1.32-.96 1.75-1.09c.43-.14.96-.21 1.6-.21c.49 0 .85.04.85.04l.52.06l-.34.4c-.04.04-.86 1.01-1.99 1.55c-.41.2-.88.32-1.3.32");
}

.kwpypqzpr {
  stop-color: var(--svg-color--15142b, #15142b);
}

.la1q1sbut {
  stop-color: var(--svg-color--red, red);
}

.lzgjwcbuj {
  fill: var(--svg-color--663b22, #663b22);
  d: path("M66.9 25.09v2.84c0 1.21-1 2.2-2.23 2.2h-.59c-1.23 0-2.23-.99-2.23-2.2v-2.84zm.7-.7h-6.44v3.54c0 1.6 1.31 2.9 2.93 2.9h.59c1.62 0 2.93-1.3 2.93-2.9v-3.54z");
}

.m_5onzv2u {
  stop-color: var(--svg-color--554138, #554138);
}

.m3cq709zi {
  stop-color: var(--svg-color--97603d, #97603d);
}

.ma0bv3brs {
  d: path("M69.59 15.96c.47 0 .82.04.82.04s-.81.96-1.89 1.48c-.41.19-.83.28-1.18.28c-.45 0-.8-.14-.87-.38c-.14-.42.64-.92 1.62-1.23c.47-.15 1.04-.19 1.5-.19m0-.57c-.66 0-1.23.07-1.68.22c-1.5.48-2.23 1.2-1.98 1.95c.16.48.68.77 1.41.77c.47 0 .97-.12 1.43-.34c1.19-.57 2.05-1.58 2.08-1.63l.68-.81l-1.05-.12c-.02 0-.39-.04-.89-.04");
}

.mu7wwsbgh {
  stop-color: var(--svg-color--3c2c23, #3c2c23);
}

.ohbtl3blw {
  stroke-width: var(--svg-stroke-width--1-167px, 1.167px);
  d: path("m36.92 29.34l7.66-4.89l15.93 13.11l-5.37 2.21l-10.75-11.72z");
}

.opysq0wvx {
  d: path("M89.94 81.89c.64 5.6 2.52 21.89 3.34 27.74c.11.79.28 1.99 15.06 7.73a39 39 0 0 1-9.2.54c-7.08-.4-8.75-2.02-9.14-2.76l-8.5-23.81zm.15-1.38c-.24 0-.47.09-.66.3l-8.83 9.88c-.22.24-.28.58-.17.89l8.57 24c1.41 2.89 8.08 3.3 10.08 3.42c.82.05 1.61.07 2.36.07c3.3 0 5.99-.39 7.83-.77c.87-.18.96-1.38.13-1.7c-4.86-1.88-14.87-5.89-15.05-7.12c-.83-5.94-2.74-22.48-3.39-28.18a.86.86 0 0 0-.87-.79");
}

.p50zshbtx {
  fill: var(--svg-color--473530, #473530);
  d: path("M68.92 20.75c-3.13 1.71-6.4 1.71-9.87 0c-.24-.12 1.1 3.43 4.94 3.43s5.17-3.56 4.93-3.43");
}

.pcyjh7p8j {
  stop-color: var(--svg-color--0063b2, #0063b2);
}

.pd0od1zgl {
  d: path("M60.63 18.05c-.42 0-.89-.11-1.3-.31c-1.13-.54-1.95-1.51-1.99-1.55l-.34-.41l.52-.06s.36-.04.85-.04c.63 0 1.17.07 1.6.21s1.46.52 1.75 1.09c.08.17.1.34.05.5c-.11.35-.54.57-1.14.57");
}

.q2txbgbhp {
  stroke-width: var(--svg-stroke-width--1-225px, 1.225px);
  d: path("m91.27 21.49l-10.34-4.24l-14.37 17.52l5.82 1.37l9.16-15.51z");
}

.qxw7w3brl {
  fill: var(--svg-color--0e2b52, #0e2b52);
  d: path("M54.11 25.19c4.49 0 10.01 1.94 10.04 1.95c1.1.42 2.29.79 3.55 1.18c5.64 1.77 11.48 3.61 10.79 9.48c-.02.18-.07.38-.13.6c-.8 2.52-4.82 15.28-5.77 19.26c-.15.61-.45 1.15-.88 1.58c-.83.82-2.07 2.05-3.22 3.2c-.61.61-1.43.95-2.3.95c-.84 0-1.64-.32-2.25-.9l-7.1-6.78c-.54-.52-.89-1.21-.98-1.96c-.17-1.43-.55-3.79-1.4-6.93c-1.41-5.23-3.11-9.79-4.23-12.8c-.41-1.09-.73-1.95-.9-2.49c-.7-2.16-.68-3.77.06-4.77c.75-1.04 2.34-1.57 4.72-1.57m0-1c-4.21 0-7.67 1.6-5.73 7.64c.66 2.06 3.2 8.1 5.12 15.25c.83 3.1 1.2 5.41 1.37 6.79c.12.98.57 1.88 1.28 2.56l7.1 6.78a4.22 4.22 0 0 0 2.94 1.18c1.09 0 2.17-.41 3-1.24c1.15-1.15 2.39-2.38 3.21-3.2c.57-.56.96-1.27 1.15-2.05c.95-3.96 5-16.83 5.75-19.19c.08-.25.14-.52.17-.78c.95-8.14-8.9-9.42-14.97-11.72c0 0-5.67-2.02-10.39-2.02");
}

.r_nlw5wtb {
  stop-color: var(--svg-color--009e3c, #009e3c);
}

.rhc9j-bbo {
  stroke-width: var(--svg-stroke-width--1-225px, 1.225px);
  d: path("m36.73 21.49l10.34-4.24l14.37 17.52l-5.82 1.37l-9.16-15.51z");
}

.rjiyx1bvt {
  d: path("M74.21 11.89s.27-9.56-10.16-9.56s-10.2 9.56-10.2 9.56s.09 12.22.86 13.81s1.93 1.53 1.93 1.53s-.54-7.13-.61-10.49c-.01-.78-.25-3.69 1.39-4.05c6.01-1.35 9.41-4.53 9.41-4.53c.88 1.93 3.65 3.81 4.64 4.53c.81.59.7 3.01.69 4.04l-.82 10.49s1.26.1 2.05-1.52s.82-13.81.82-13.81");
}

.si3tfpbbe {
  d: path("M62.48 16.5c-.24 0-.48-.02-.71-.05l-.34-.05l-.33-.07c-.22-.04-.43-.11-.65-.17s-.42-.13-.63-.2c-.82-.31-1.61-.69-2.35-1.17l-.51-.33l.13-.43c.06-.19.12-.37.2-.55l.11-.28l.13-.27c.08-.18.18-.36.28-.54s.22-.35.35-.53l.09.02l-.18 1.15l-.2 1.15l-.04-.08l1.17.55l1.18.58l1.18.59c.39.19.78.4 1.17.6z");
}

.t0sle7b8p {
  fill: none;
  stroke: var(--svg-color--875334, #875334);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-522px, 0.522px);
  d: path("M62.8 13.7s.45 1.69-.13 2.63m2.47-2.63s-.45 1.69.13 2.63");
}

.tg4imwipn {
  stroke-width: var(--svg-stroke-width--1-167px, 1.167px);
  d: path("m91.08 29.34l-7.66-4.89l-15.93 13.11l5.37 2.21l10.75-11.72z");
}

.tisq54bqj {
  stop-color: var(--svg-color--a56c43, #a56c43);
}

.tncun38sa {
  stroke: var(--svg-color--0e2b52, #0e2b52);
  stroke-miterlimit: 10;
}

.tp7he0bmn {
  d: path("m66.04 33.18l1.88 3.16l-1.29 5.44l-1.96-5.38zm-.09-1.41l-.5 1.16l-1.37 3.22l-.1.23l.09.24L66.02 42l.73 2.01l.49-2.08l1.29-5.44l.06-.25l-.13-.22l-1.88-3.16z");
}

.u24ka2b2d {
  stop-color: var(--svg-color--0160ac, #0160ac);
}

.uegphzbvm {
  d: path("m55.01 24.3l-.4-13.82c0-4.55 4.24-8.02 8.79-8.02h1.32c4.55 0 8.74 3.47 8.74 8.02l-.4 13.75z");
}

.ugujspbkg {
  fill: var(--svg-color--0e2b52, #0e2b52);
  d: path("M101.45 118.52c-.75 0-1.53-.02-2.33-.07c-6.89-.39-9.03-1.91-9.62-3.11L80.95 91.4a.33.33 0 0 1 .07-.34l8.83-9.88c.07-.08.15-.12.25-.12c.15 0 .32.09.34.3c.75 6.56 2.59 22.44 3.39 28.19c.07.51.24 1.71 15.39 7.56c.21.08.22.27.22.35c-.01.08-.04.25-.26.3c-1.69.34-4.39.76-7.73.76");
}

.vj-mqqb2k {
  fill: var(--svg-color--875334, #875334);
  d: path("M62.78 19.74c.08.19 1.21 1.21 1.21 1.21s1.13-1.02 1.21-1.21c.07-.19-2.5-.19-2.42 0");
}

.w_n_17bru {
  stroke-width: var(--svg-stroke-width--1-368px, 1.368px);
  d: path("M92.25 14.48L79.7 10.05L63.69 33.01l6.75.54l9.87-19.93z");
}

.w5_fr9wdn {
  stroke: var(--svg-color--009245, #009245);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M103.92 24.67L101 22.08c-.92-.42-.78-.55-1.42 0c-1.17 1 1.17 2.5 1.17 2.5c-.07.09-2.78-1.57-2.78-1.57a.85.85 0 0 0-1.19.19l-.03.04a.85.85 0 0 0 .19 1.19l1.82 1.33c.11.08-2.85-.89-2.85-.89c-.45-.14-.93.1-1.07.55l-.02.05c-.15.45.1.93.55 1.07l1.85.6c0 .01 0 .01.01.02c0 0 .33.82.67 1.71c.43 1.12.39 2.46-.81 2.54l-1.33-.08c-.81-.06-2.25 1.5.08 1.92l3.28.45c-.2 1.44-1.16 2.86-4.27 4.78c-5.51 3.42-6.97 5.3-6.97 5.3c1.7.76 2.87 2.4 3.33 3.87c.64 2.03-.22 6.58-.22 6.58c5.79-4.73 10.22-13.04 11.86-17.59v0c1.28-3.55.76-7.55.84-7.96c0 0 .43-3.71.23-4.01");
}

.x4cgyhp8l {
  d: path("M83.17 89.36c-1.68-2.64-9.48-11.79-14.32-16.87a4.28 4.28 0 0 0-3.12-1.34c-1.14 0-2.22.45-3.02 1.25c-6.19 6.2-13.52 13.79-15.4 15.89c-3.62-.65-8.31-2.38-9.86-2.97c1.12-2.11 5.6-10.49 9.47-16.72c.03-.05.45-.68 1.08-1.63c5.25-7.88 6.92-10.42 7.46-11.28c.99.35 3.94 1.48 8.28 3.93c.76.43 1.54.65 2.31.65c2.25 0 3.81-1.83 4.5-2.82c.22.24.54.58 1 1.06c.47.5 1.12 1.17 1.23 1.32c.88 1.9 12.22 17.48 16.1 22.78c-.7 1.08-3.34 4.98-5.71 6.75");
}

.xbplr95cb {
  fill: var(--svg-color--7a4c32, #7a4c32);
  d: path("M64.08 30.48c-1.42 0-2.58-1.14-2.58-2.55v-3.19h5.75v3.19c0 1.41-1.16 2.55-2.58 2.55z");
}

.xidbg2bsq {
  fill: var(--svg-color--0e2b52, #0e2b52);
  d: path("M30.23 23.37c.67 0 1.28.41 1.51 1.03l2.69 6.93l.26.66l.68-.18l15.75-4.19a3.59 3.59 0 0 1 4.38 2.54c.24.92.11 1.89-.37 2.72s-1.25 1.42-2.18 1.67l-17.96 4.77h-.04l-.1.02l-.04.02c-.41.16-.85.24-1.29.24c-1.51 0-2.89-.94-3.44-2.34l-4.12-10.63c-.32-.83.09-1.77.92-2.09l2.74-1.06c.22-.08.41-.11.61-.11m0-.79c-.29 0-.58.05-.86.16l-2.74 1.06a2.41 2.41 0 0 0-1.37 3.11l4.12 10.63a4.48 4.48 0 0 0 4.17 2.85c.52 0 1.05-.09 1.57-.29c.02 0 .04 0 .06-.01l18-4.79a4.38 4.38 0 0 0 3.1-5.35a4.394 4.394 0 0 0-4.23-3.25c-.37 0-.74.05-1.12.15l-15.75 4.19l-2.69-6.93a2.43 2.43 0 0 0-2.26-1.53M40.97 123.2c-5.94 0-9.07-1.2-10.64-2.2a.52.52 0 0 1-.24-.53c.02-.1.09-.34.4-.4c17.72-3.73 18.31-5.13 18.53-5.66c.12-.28.09-.58-.07-.84c-3.9-6.06-12.39-21.7-15.86-28.14a.48.48 0 0 1 .01-.5c.07-.12.23-.25.43-.25c.05 0 .1.01.15.02l13.13 3.78c.17.05.29.17.35.34l9.65 31c.06.29.01.56-.17.81c-.9 1.26-4.5 1.63-6.43 1.84c-.42.04-.8.08-1.1.12c-2.96.4-5.7.61-8.14.61q.015 0 0 0");
}

.z494f1bfm {
  stop-color: var(--svg-color--084681, #084681);
}

.zg8ocbcxm {
  stroke: var(--svg-color--611a5e, #611a5e);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M48.75 31.83L31.5 108.17c5.32 1.53 10.92 3.01 16.42 3.6c8.01.87 15.75-3.36 23.76-1.92c5.83 1.05 9.46 2.13 15.28.37c3.26-.98 6.47-2.24 9.54-3.71L76 31.83z");
}

.zofgs1bky {
  stop-color: var(--svg-color--f50000, #f50000);
}

.zomvvbcmt {
  stop-color: var(--svg-color--03569c, #03569c);
}

.zyi0t3bzm {
  fill: var(--svg-color--0e2b52, #0e2b52);
  d: path("M74.26 32.62c1.36 0 2.74.45 3.24.88l9.44 13.25l.78 1.09l.82-1.06l2.71-3.48c.35-.27.78-.42 1.23-.42c.59 0 1.14.25 1.52.69l.22.25c.72.84.63 2.1-.21 2.82l-6.19 5.33c-.45.39-.96.47-1.31.47h-.18c-.54 0-1.04-.2-1.41-.57L70.8 37.73c-.78-.78-.78-2.05 0-2.83l1.94-1.94c.17-.17.71-.34 1.52-.34m0-1c-.94 0-1.78.19-2.23.64l-1.94 1.94a3 3 0 0 0 0 4.24l14.14 14.14c.58.58 1.35.86 2.12.86h.18c.69 0 1.39-.22 1.95-.71l6.19-5.33a3.015 3.015 0 0 0 .32-4.23l-.22-.25a2.98 2.98 0 0 0-2.28-1.04a3 3 0 0 0-1.95.72l-2.78 3.56l-9.5-13.33c-.73-.72-2.49-1.21-4-1.21");
}

</style>
