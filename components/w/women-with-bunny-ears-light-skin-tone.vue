<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gceq0h0ek"/><path class="pc_9zccax"/><path class="tjk9p17dy"/><linearGradient id="SVG9MnmIdsL" x1="30.566" x2="31.31" y1="25.291" y2="14.222" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".4" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVG9MnmIdsL)" class="wjqbksbvb"/><linearGradient id="SVG5PEA8Zeq" x1="52.038" x2="53.156" y1="32.432" y2="15.808" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".4" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVG5PEA8Zeq)" class="eg4t0ymfl"/><linearGradient id="SVGDu6BucCu" x1="34.868" x2="40.356" y1="39.583" y2="27.21" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".4" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGDu6BucCu)" class="t2fr8g_6b"/><path class="kx398hjfc"/><path class="vb4b6pbku"/><linearGradient id="SVGbxvuIbOd" x1="34.39" x2="34.39" y1="66.515" y2="42.113" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tv94cubcg"/><stop offset=".944" class="xsgkrbcbf"/></linearGradient><path fill="url(#SVGbxvuIbOd)" class="ffi7ffbtu"/><linearGradient id="SVGqt1hJbGE" x1="44.335" x2="54.009" y1="63.926" y2="52.577" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="s6rm2gd3x"/><stop offset=".5" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGqt1hJbGE)" class="ro84_bbnq"/><linearGradient id="SVGSGLLvdWw" x1="24.878" x2="14.461" y1="63.322" y2="52.905" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="s6rm2gd3x"/><stop offset=".5" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGSGLLvdWw)" class="uo7flmwgk"/><linearGradient id="SVGfpB0pcIg" x1="34.42" x2="34.42" y1="66.515" y2="42.114" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tv94cubcg"/><stop offset=".944" class="xsgkrbcbf"/></linearGradient><path fill="url(#SVGfpB0pcIg)" class="ad3lljb7d"/><path class="x0uusz9xr"/><path class="ai1eilbdp"/><path class="fgc8_ebhn"/><path class="aem8crxpz"/><path class="fhxkllb7c"/><path class="tw8x-xggf"/><path class="aff0smzpm"/><path class="jts_k6boh"/><path class="y2v26ubql"/><radialGradient id="SVGxMKf6b6w" cx="-842.214" cy="584.309" r="1" gradientTransform="matrix(16.9553 0 0 -22.957 14314.469 13453.4)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVGxMKf6b6w)" class="v7nr9ba_e"/><linearGradient id="SVGRVPhdbgP" x1="34.371" x2="34.371" y1="113.284" y2="99.534" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="fboms9lpk"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGRVPhdbgP)" class="y5z2xjbae"/><path class="y_ftxbcck"/><path class="s_s983p_j"/><path class="pggaeabha"/><path class="vxl-b5bre"/><linearGradient id="SVGRpbdccoj" x1="86.415" x2="87.16" y1="25.291" y2="14.222" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".4" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGRpbdccoj)" class="to1otcbjx"/><linearGradient id="SVGMJ3IobAu" x1="107.888" x2="109.005" y1="32.432" y2="15.808" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".4" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGMJ3IobAu)" class="n5mogab2i"/><linearGradient id="SVGrC7hrGpP" x1="90.718" x2="96.206" y1="39.583" y2="27.21" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".4" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGrC7hrGpP)" class="d0oe4w5rk"/><path class="xck2m9enn"/><path class="kj1gnps4o"/><linearGradient id="SVGpJggudXu" x1="90.24" x2="90.24" y1="66.515" y2="42.113" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tv94cubcg"/><stop offset=".944" class="xsgkrbcbf"/></linearGradient><path fill="url(#SVGpJggudXu)" class="hc-xzyg_b"/><linearGradient id="SVGjYkcaeHN" x1="100.185" x2="109.859" y1="63.926" y2="52.577" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="s6rm2gd3x"/><stop offset=".5" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGjYkcaeHN)" class="fpxb8pm1u"/><linearGradient id="SVG1w4oWvXc" x1="80.728" x2="70.311" y1="63.322" y2="52.905" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="s6rm2gd3x"/><stop offset=".5" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVG1w4oWvXc)" class="b02b77b7z"/><linearGradient id="SVGcTU2acSw" x1="90.27" x2="90.27" y1="66.515" y2="42.114" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tv94cubcg"/><stop offset=".944" class="xsgkrbcbf"/></linearGradient><path fill="url(#SVGcTU2acSw)" class="nvc_48b6f"/><path class="qqmocyb2v"/><path class="wunx1fu4y"/><path class="z19dwyb9u"/><path class="km6_stbtq"/><path class="bytqsj24z"/><path class="jib60rbuo"/><path class="qs4559b6u"/><path class="kl1auos4k"/><path class="pcvipcbzy"/><radialGradient id="SVGFi5vPcQP" cx="-842.214" cy="584.328" r="1" gradientTransform="matrix(16.9553 0 0 -22.9781 14370.318 13466.164)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVGFi5vPcQP)" class="qzp88f9js"/><linearGradient id="SVGkr8AgeXv" x1="90.41" x2="90.41" y1="113.284" y2="99.534" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="fboms9lpk"/><stop offset=".275" class="alyihb0gj"/><stop offset=".602" class="e_z5lx61b"/><stop offset=".955" class="osi2yu8vz"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGkr8AgeXv)" class="uv2kb_x0w"/><path class="qi6sqcbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:women-with-bunny-ears-light-skin-tone" /></template>
<style>
.ad3lljb7d {
  d: path("M53.92 60.34s-3.07-7.41-20.04-7.41s-18.96 7.41-18.96 7.41l7.35 6.83h24.25z");
}

.aem8crxpz {
  fill: var(--svg-color--f9ddbd, #f9ddbd);
  d: path("M34.45 20.27c-6.84 0-13.17 5.1-13.17 15.91c0 8.68 5.36 13.82 10.03 15.48c1.11.39 2.19.59 3.14.59s2.01-.2 3.12-.59c4.67-1.65 10.05-6.79 10.05-15.48c0-10.81-6.33-15.91-13.17-15.91");
}

.aff0smzpm {
  fill: var(--svg-color--454140, #454140);
  d: path("M30.93 34.41c-.37-.49-1.22-1.2-2.87-1.2s-2.51.71-2.87 1.2c-.16.22-.12.47-.01.62c.1.14.41.27.76.15c.34-.12 1.01-.46 2.13-.47c1.12.01 1.79.35 2.13.47s.65-.01.76-.15c.1-.16.14-.41-.03-.62m12.92 0c-.37-.49-1.22-1.2-2.87-1.2s-2.51.71-2.87 1.2c-.16.22-.12.47-.01.62c.1.14.41.27.76.15c.34-.12 1.01-.46 2.13-.47c1.12.01 1.79.35 2.13.47s.65-.01.76-.15c.09-.16.13-.41-.03-.62");
}

.ai1eilbdp {
  fill: var(--svg-color--504f4f, #504f4f);
  d: path("M32.14 124h-4.38c-.81-.02-1.39-.95-1.15-1.75c.73-2.46 2.95-4.27 5.53-4.27c2.64 0 4.89 1.88 5.57 4.41c.22.81-.38 1.61-1.19 1.61z");
}

.alyihb0gj {
  stop-color: var(--svg-color--4a4a4a, #4a4a4a);
}

.b02b77b7z {
  d: path("M82.22 77.94c.02-.3-.11-.59-.32-.83s-.26-.66-.05-.89c.18-.2.21-.75-.18-1.05c-.44-.34-2.11-.46-2.11-.46l-.02.01h-.39c-1.19 0-2.12.13-2.66.16l-5.19-4.31l7.42-6.95l-6.19-4.38l-7.38 9.79c-1 1.15-1.05 3.04 0 4.15c0 0 10.35 8.42 10.39 8.44c1.51.59 2.7.82 3.61.82c1.01 0 1.69-.28 2.08-.63c.42-.38.01-.81.05-.94c.1-.33.53-.42.63-.85c.05-.21-.15-.63-.27-.87c-.08-.15 0-.43.14-.53c.29-.22.42-.39.44-.68");
}

.bytqsj24z {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M83.91 40.03c1.07 0 1.93-.9 1.93-2.01s-.86-2.01-1.93-2.01s-1.93.9-1.93 2.01s.86 2.01 1.93 2.01m12.91 0c1.07 0 1.93-.9 1.93-2.01s-.86-2.01-1.93-2.01s-1.93.9-1.93 2.01s.86 2.01 1.93 2.01");
}

.d0oe4w5rk {
  d: path("M107.84 99.03a4.648 4.648 0 0 1-8.28 2.9c-.21-.25-.4-.53-.56-.81l-6.83-12.65c-.04-.22-1.21-.37-1.41-.37s-.37.16-.41.37l.39 14.34v.13a4.537 4.537 0 0 1-4.54 4.51c-1.94 0-3.59-1.21-4.24-2.91l-.29-1.76l-3.43-20.16l11.34-8.03l12.7 8.02l4.67 13.7l.1.29c.14.35.32.69.56.99c.15.45.23.94.23 1.44");
}

.e_z5lx61b {
  stop-color: var(--svg-color--3c3b3b, #3c3b3b);
}

.eg4t0ymfl {
  d: path("M59.71 113.47c-1 .56-2.24.49-3.17-.19l-12.15-10.64c-.11-.1-.22-.2-.32-.31a4.648 4.648 0 0 0 7.69-4.74c.01.01.02.03.03.04l8.55 11.16c1.39 1.38 1.08 3.72-.63 4.68");
}

.fboms9lpk {
  stop-color: var(--svg-color--504f4f, #504f4f);
}

.ffi7ffbtu {
  d: path("M53.89 60.34s-3.07-7.41-20.04-7.41s-18.96 7.41-18.96 7.41l7.42 6.89v15.42l9.74 6.43c.77.39 1.62.59 2.48.59c.89 0 1.77-.22 2.56-.63l9.31-6.39V67.23z");
}

.fgc8_ebhn {
  fill: var(--svg-color--edc391, #edc391);
  d: path("M33.96 57.3c-1.97 0-3.57-1.52-3.57-3.4v-4.26h7.96v4.26c0 1.87-1.6 3.4-3.57 3.4z");
}

.fhxkllb7c {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M28.06 40.03c1.07 0 1.93-.9 1.93-2.01s-.86-2.01-1.93-2.01s-1.93.9-1.93 2.01s.86 2.01 1.93 2.01m12.91 0c1.07 0 1.93-.9 1.93-2.01s-.86-2.01-1.93-2.01s-1.93.9-1.93 2.01s.86 2.01 1.93 2.01");
}

.fpxb8pm1u {
  d: path("m115.71 69.01l-7.39-9.77l-6.18 4.36l7.42 6.95l-5.19 4.31c-.54-.02-1.47-.16-2.66-.16h-.39l-.02-.01s-1.67.12-2.11.46c-.4.31-.36.85-.18 1.05c.21.24.16.66-.05.89c-.21.24-.34.53-.32.83c.02.29.15.46.44.68c.14.1.21.38.14.53c-.12.24-.31.65-.27.87c.09.43.53.52.63.85c.04.13-.37.57.05.94c.39.35 1.06.63 2.08.63c.91 0 2.1-.22 3.61-.82c.04-.02 10.39-8.44 10.39-8.44c1.05-1.11 1-2.99 0-4.15");
}

.fwx9zn6gv {
  stop-color: var(--svg-color--454140, #454140);
}

.gceq0h0ek {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M34.66 16.33c-16.3 0-16.17 15.11-16.17 15.35c0 9.79.75 23.62 4.65 29.06c1.55 2.16 4.54 2.28 4.54 2.28l6.75-.02l6.74.01s2.99-.12 4.54-2.28c3.91-5.44 4.65-19.27 4.65-29.06c.01-.23.6-15.34-15.7-15.34");
}

.hc-xzyg_b {
  d: path("M109.74 60.34s-3.07-7.41-20.04-7.41s-18.96 7.41-18.96 7.41l7.42 6.89v15.42l9.74 6.43c.77.39 1.62.59 2.48.59c.89 0 1.77-.22 2.56-.63l9.31-6.39V67.23z");
}

.jb0j4_2gw {
  stop-color: var(--svg-color--f9ddbd, #f9ddbd);
}

.jib60rbuo {
  fill: var(--svg-color--dba689, #dba689);
  d: path("M91.78 41.67a.3.3 0 0 0-.13-.03h-2.78c-.04.01-.08.02-.13.03c-.25.1-.39.36-.27.64s.67 1.06 1.79 1.06c1.11 0 1.67-.78 1.79-1.06c.12-.27-.02-.53-.27-.64");
}

.jts_k6boh {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M34.62 16.33c-16.34 0-16.21 15.11-16.21 15.35c0 7.3.42 16.85 2.26 23.49q.9-.405 1.98-.75c.26-.09.53-.17.81-.25c-.15-2.04-.79-10.82-.87-15.24c-.02-1.17-.37-5.52 2.05-6.07c8.89-2.02 13.91-6.79 13.91-6.79c1.31 2.89 5.4 5.71 6.86 6.78c1.21.88 1.04 4.49 1.01 6.04l-1.19 15.49l.48.15c.86.28 1.63.59 2.33.9c1.91-6.65 2.33-16.35 2.33-23.75c0-.24.59-15.35-15.75-15.35");
}

.kj1gnps4o {
  fill: var(--svg-color--444, #444);
  d: path("M108.77 60.34s-2.07-7.41-19.04-7.41s-17.96 7.41-17.96 7.41l6.35 4.83h23.25z");
}

.kl1auos4k {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M90.47 16.33c-16.34 0-16.21 15.11-16.21 15.35c0 7.3.42 16.85 2.26 23.49q.9-.405 1.98-.75c.26-.09.53-.17.81-.25c-.15-2.04-.79-10.82-.87-15.24c-.02-1.17-.37-5.52 2.05-6.07c8.89-2.02 13.91-6.79 13.91-6.79c1.31 2.89 5.4 5.71 6.86 6.78c1.21.88 1.04 4.49 1.01 6.04l-1.19 15.49l.48.15c.86.28 1.63.59 2.33.9c1.91-6.65 2.33-16.35 2.33-23.75c0-.24.59-15.35-15.75-15.35");
}

.km6_stbtq {
  fill: var(--svg-color--f9ddbd, #f9ddbd);
  d: path("M90.3 20.27c-6.84 0-13.17 5.1-13.17 15.91c0 8.68 5.36 13.82 10.03 15.48c1.11.39 2.19.59 3.14.59s2.01-.2 3.12-.59c4.67-1.65 10.05-6.79 10.05-15.48c0-10.81-6.33-15.91-13.17-15.91");
}

.kx398hjfc {
  fill: var(--svg-color--edc391, #edc391);
  d: path("m49.04 75.14l-2.64-2.22c-.17-.12-.72.24-.91.29c-.06 0-.52.15-.58.16l-.9.16c-.38.09-.63.48-.54.87l.04.21a.7.7 0 0 0 .84.55l1.37-.32l2.38 1.68c.32.23.76.14.99-.19l.12-.18a.73.73 0 0 0-.17-1.01");
}

.n5mogab2i {
  d: path("M115.56 113.47c-1 .56-2.24.49-3.17-.19l-12.15-10.64c-.11-.1-.22-.2-.32-.31a4.648 4.648 0 0 0 7.69-4.74c.01.01.02.03.03.04l8.55 11.16c1.39 1.38 1.08 3.72-.63 4.68");
}

.nvc_48b6f {
  d: path("M109.77 60.34s-3.07-7.41-20.04-7.41s-18.96 7.41-18.96 7.41l7.35 6.83h24.25z");
}

.osi2yu8vz {
  stop-color: var(--svg-color--242424, #242424);
}

.pc_9zccax {
  fill: var(--svg-color--edc391, #edc391);
  d: path("m20.11 75.4l2.33-2.38c.17-.12 1.1-.14 1.29-.08c.06 0 .45.69.51.7l.9.16c.38.09.63.48.54.87l-.04.21a.7.7 0 0 1-.84.55l-1.37-.32l-2.38 1.68c-.32.23-.76.14-.99-.19l-.12-.18c-.23-.35-.15-.8.17-1.02");
}

.pcvipcbzy {
  fill: var(--svg-color--444, #444);
  d: path("M93.57 45.08c-1.25.75-5.35.75-6.6 0c-.72-.43-1.45.23-1.15.88c.29.64 2.53 2.14 4.46 2.14s4.14-1.49 4.44-2.14c.3-.66-.43-1.31-1.15-.88");
}

.pggaeabha {
  fill: var(--svg-color--edc391, #edc391);
  d: path("m75.96 75.4l2.33-2.38c.17-.12 1.1-.14 1.29-.08c.06 0 .45.69.51.7l.9.16c.38.09.63.48.54.87l-.04.21a.7.7 0 0 1-.84.55l-1.37-.32l-2.38 1.68c-.32.23-.76.14-.99-.19l-.12-.18c-.23-.35-.15-.8.17-1.02");
}

.qi6sqcbpy {
  fill: var(--svg-color--ff4081, #ff4081);
  d: path("M98.31 11.77c-1.04 1.8-1.25 4.86-1.3 6.18c-.01.29.29.47.54.31c1.12-.7 3.65-2.41 4.69-4.22c.91-1.58.83-3.54.68-4.63a.677.677 0 0 0-.95-.55c-1.02.42-2.75 1.33-3.66 2.91m-15.81 0c1.04 1.8 1.26 4.86 1.3 6.19c.01.29-.29.47-.53.31c-1.12-.7-3.65-2.41-4.69-4.22c-.91-1.58-.83-3.54-.69-4.63c.06-.47.52-.73.95-.55c1.01.41 2.75 1.32 3.66 2.9");
}

.qqmocyb2v {
  fill: var(--svg-color--f9ddbd, #f9ddbd);
  d: path("M100.76 54.3c-.09 3-3.82 7.27-10.5 7.27c-6.76 0-10.5-4.33-10.5-7.33c0-.05 0-.1.01-.15c2.48-.7 5.72-1.16 9.96-1.16c4.75 0 8.34.53 11.03 1.37");
}

.qs4559b6u {
  fill: var(--svg-color--454140, #454140);
  d: path("M86.78 34.41c-.37-.49-1.22-1.2-2.87-1.2s-2.51.71-2.87 1.2c-.16.22-.12.47-.01.62c.1.14.41.27.76.15c.34-.12 1.01-.46 2.13-.47c1.12.01 1.79.35 2.13.47s.65-.01.76-.15c.1-.16.14-.41-.03-.62m12.92 0c-.37-.49-1.22-1.2-2.87-1.2s-2.51.71-2.87 1.2c-.16.22-.12.47-.01.62c.1.14.41.27.76.15c.34-.12 1.01-.46 2.13-.47c1.12.01 1.79.35 2.13.47s.65-.01.76-.15c.09-.16.13-.41-.03-.62");
}

.qzp88f9js {
  d: path("M106.23 31.66c0 7.41-.43 17.12-2.34 23.77c-3.03-1.39-7.54-2.52-14.18-2.52c-6.17 0-10.36.98-13.19 2.22c-1.83-6.64-2.25-16.17-2.25-23.47c0-.24-.13-15.35 16.21-15.35s15.75 15.11 15.75 15.35");
}

.ro84_bbnq {
  d: path("m59.86 69.01l-7.39-9.77l-6.18 4.36l7.42 6.95l-5.19 4.31c-.54-.02-1.47-.16-2.66-.16h-.39l-.02-.01s-1.67.12-2.11.46c-.4.31-.36.85-.18 1.05c.21.24.16.66-.05.89c-.21.24-.34.53-.32.83c.02.29.15.46.44.68c.14.1.21.38.14.53c-.12.24-.31.65-.27.87c.09.43.53.52.63.85c.04.13-.37.57.05.94c.39.35 1.06.63 2.08.63c.91 0 2.1-.22 3.61-.82c.04-.02 10.39-8.44 10.39-8.44c1.05-1.11 1-2.99 0-4.15");
}

.s_s983p_j {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M90.51 16.33c-16.3 0-16.17 15.11-16.17 15.35c0 9.79.75 23.62 4.65 29.06c1.55 2.16 4.54 2.28 4.54 2.28l6.75-.02l6.74.01s2.99-.12 4.54-2.28c3.91-5.44 4.65-19.27 4.65-29.06c.01-.23.6-15.34-15.7-15.34");
}

.s6rm2gd3x {
  stop-color: var(--svg-color--ffd29c, #ffd29c);
}

.t2fr8g_6b {
  d: path("M51.99 99.03a4.648 4.648 0 0 1-8.28 2.9c-.21-.25-.4-.53-.56-.81l-6.83-12.65c-.04-.22-1.21-.37-1.41-.37s-.37.16-.41.37l.39 14.34v.13a4.537 4.537 0 0 1-4.54 4.51c-1.94 0-3.59-1.21-4.24-2.91l-.29-1.76l-3.43-20.16l11.34-8.03l12.7 8.02l4.67 13.7l.1.29c.14.35.32.69.56.99c.15.45.23.94.23 1.44");
}

.tjk9p17dy {
  fill: var(--svg-color--504f4f, #504f4f);
  d: path("M64.99 113.17c-.56-2.43-3.24-5.12-5.87-7.72c-1.7-1.68-4.76-1.33-6.43.38s-1.97 4.78-.27 6.46c2.63 2.6 5.36 5.24 7.79 5.76c1.91.41 3.5-.2 4.07-.78c.57-.59 1.15-2.19.71-4.1");
}

.to1otcbjx {
  d: path("M91.3 123.82h-6.06l-3.28-19.28c.65 1.7 2.3 2.91 4.24 2.91c2.5 0 4.53-2.02 4.54-4.51z");
}

.tv94cubcg {
  stop-color: var(--svg-color--515151, #515151);
}

.tw8x-xggf {
  fill: var(--svg-color--dba689, #dba689);
  d: path("M35.93 41.67a.3.3 0 0 0-.13-.03h-2.78c-.04.01-.08.02-.13.03c-.25.1-.39.36-.27.64s.67 1.06 1.79 1.06c1.11 0 1.67-.78 1.79-1.06c.12-.27-.02-.53-.27-.64");
}

.uo7flmwgk {
  d: path("M26.37 77.94c.02-.3-.11-.59-.32-.83s-.26-.66-.05-.89c.18-.2.21-.75-.18-1.05c-.44-.34-2.11-.46-2.11-.46l-.02.01h-.39c-1.19 0-2.12.13-2.66.16l-5.19-4.31l7.42-6.95l-6.19-4.38l-7.38 9.79c-1 1.15-1.05 3.04 0 4.15c0 0 10.35 8.42 10.39 8.44c1.51.59 2.7.82 3.61.82c1.01 0 1.69-.28 2.08-.63c.42-.38.01-.81.05-.94c.1-.33.53-.42.63-.85c.05-.21-.15-.63-.27-.87c-.08-.15 0-.43.14-.53c.29-.22.42-.39.44-.68");
}

.uv2kb_x0w {
  d: path("M105.99 5.34c-.17-1-1.2-1.59-2.14-1.24c-2.22.82-5.98 2.63-7.88 5.93c-1.43 2.48-2.03 6.16-2.27 9.18a2 2 0 0 1-2.14 1.84c-.37-.03-1.94-.03-2.31 0c-1.1.08-2.06-.73-2.14-1.84c-.24-3.02-.84-6.7-2.27-9.18c-1.9-3.31-5.68-5.11-7.89-5.93c-.94-.35-1.95.24-2.12 1.23c-.4 2.33-.73 6.52 1.18 9.82c1.43 2.49 4.3 4.84 6.79 6.56c.56.39.56 1.2.02 1.62c-1.01.77-1.77 1.67-2.36 2.57c-.58.9.45 1.99 1.35 1.41c1.78-1.15 4.49-2.09 8.59-2.09s6.81.94 8.59 2.09c.9.58 1.94-.51 1.35-1.41c-.59-.91-1.35-1.8-2.35-2.58c-.54-.42-.54-1.23.02-1.62c2.48-1.72 5.35-4.07 6.79-6.56c1.91-3.29 1.59-7.46 1.19-9.8");
}

.v7nr9ba_e {
  d: path("M50.38 31.66c0 7.41-.43 17.12-2.34 23.77c-3.03-1.39-7.54-2.52-14.18-2.52c-6.17 0-10.36.98-13.19 2.22c-1.83-6.64-2.25-16.17-2.25-23.47c0-.24-.13-15.35 16.21-15.35s15.75 15.11 15.75 15.35");
}

.vb4b6pbku {
  fill: var(--svg-color--444, #444);
  d: path("M52.92 60.34s-2.07-7.41-19.04-7.41s-17.96 7.41-17.96 7.41l6.35 4.83h23.25z");
}

.vxl-b5bre {
  fill: var(--svg-color--504f4f, #504f4f);
  d: path("M120.84 113.17c-.56-2.43-3.24-5.12-5.87-7.72c-1.7-1.68-4.76-1.33-6.43.38s-1.97 4.78-.27 6.46c2.63 2.6 5.36 5.24 7.79 5.76c1.91.41 3.5-.2 4.07-.78c.57-.59 1.15-2.19.71-4.1");
}

.wjqbksbvb {
  d: path("M35.45 123.82h-6.06l-3.28-19.28c.65 1.7 2.3 2.91 4.24 2.91c2.5 0 4.53-2.02 4.54-4.51z");
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.wunx1fu4y {
  fill: var(--svg-color--504f4f, #504f4f);
  d: path("M87.99 124h-4.38c-.81-.02-1.39-.95-1.15-1.75c.73-2.46 2.95-4.27 5.53-4.27c2.64 0 4.89 1.88 5.57 4.41c.22.81-.38 1.61-1.19 1.61z");
}

.x0uusz9xr {
  fill: var(--svg-color--f9ddbd, #f9ddbd);
  d: path("M44.91 54.35c-.09 3-3.82 7.22-10.5 7.22c-6.76 0-10.5-4.33-10.5-7.33c0-.05 0-.1.01-.15c2.48-.7 5.72-1.16 9.96-1.16c4.75 0 8.34.58 11.03 1.42");
}

.x21lzsbti {
  stop-color: var(--svg-color--454140, #454140);
  stop-opacity: 0;
}

.xck2m9enn {
  fill: var(--svg-color--edc391, #edc391);
  d: path("m104.89 75.14l-2.64-2.22c-.17-.12-.72.24-.91.29c-.06 0-.52.15-.58.16l-.9.16c-.38.09-.63.48-.54.87l.04.21a.7.7 0 0 0 .84.55l1.37-.32l2.38 1.68c.32.23.76.14.99-.19l.12-.18a.73.73 0 0 0-.17-1.01");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y_ftxbcck {
  fill: var(--svg-color--ff4081, #ff4081);
  d: path("M42.27 11.77c-1.04 1.8-1.25 4.86-1.3 6.18c-.01.29.29.47.54.31c1.12-.7 3.65-2.41 4.69-4.22c.91-1.58.83-3.54.68-4.63a.677.677 0 0 0-.95-.55c-1.02.42-2.75 1.33-3.66 2.91m-15.81 0c1.04 1.8 1.26 4.86 1.3 6.19c.01.29-.29.47-.53.31c-1.12-.7-3.65-2.41-4.69-4.22c-.91-1.58-.83-3.54-.69-4.63c.06-.47.52-.73.95-.55c1.01.41 2.75 1.32 3.66 2.9");
}

.y2v26ubql {
  fill: var(--svg-color--444, #444);
  d: path("M37.72 45.08c-1.25.75-5.35.75-6.6 0c-.72-.43-1.45.23-1.15.88c.29.64 2.53 2.14 4.46 2.14s4.14-1.49 4.44-2.14c.3-.66-.43-1.31-1.15-.88");
}

.y5z2xjbae {
  d: path("M49.95 5.34c-.17-1-1.2-1.59-2.14-1.24c-2.22.82-5.98 2.63-7.88 5.93c-1.43 2.48-2.03 6.16-2.27 9.18a2 2 0 0 1-2.14 1.84c-.37-.03-1.94-.03-2.31 0c-1.1.08-2.06-.73-2.14-1.84c-.24-3.02-.84-6.7-2.27-9.18c-1.9-3.31-5.68-5.11-7.89-5.93c-.94-.35-1.95.24-2.12 1.23c-.4 2.33-.73 6.52 1.18 9.82c1.43 2.49 4.3 4.84 6.79 6.56c.56.39.56 1.2.02 1.62c-1.01.77-1.77 1.67-2.36 2.57c-.58.9.45 1.99 1.35 1.41c1.78-1.15 4.49-2.09 8.59-2.09s6.81.94 8.59 2.09c.9.58 1.94-.51 1.35-1.41c-.59-.91-1.35-1.8-2.35-2.58c-.54-.42-.54-1.23.02-1.62c2.48-1.72 5.35-4.07 6.79-6.56c1.91-3.29 1.59-7.46 1.19-9.8");
}

.z19dwyb9u {
  fill: var(--svg-color--edc391, #edc391);
  d: path("M90 57.3c-1.97 0-3.57-1.52-3.57-3.4v-4.26h7.96v4.26c0 1.87-1.6 3.4-3.57 3.4z");
}

</style>
