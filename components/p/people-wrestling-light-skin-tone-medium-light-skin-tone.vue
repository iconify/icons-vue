<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ngccpbbgb"/><linearGradient id="SVG1sVejb1l" x1="25.87" x2="53.21" y1="45.3" y2="45.3" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset="1" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVG1sVejb1l)" class="e7p1a9b-n"/><path class="o80-tkbsr"/><linearGradient id="SVG4nRRwbXc" x1="10.42" x2="36.071" y1="44.65" y2="44.65" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset="1" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVG4nRRwbXc)" class="nc1qd5b_i"/><path class="b9fn5-bcs"/><path class="rlrfr4bym"/><path class="xb8szu46a"/><path class="s0ywn2bjh"/><path class="nco8tdb8o"/><linearGradient id="SVGm3fQEb6B" x1="31.51" x2="68.715" y1="75.95" y2="75.95" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="jb0j4_2gw"/><stop offset="1" class="s6rm2gd3x"/></linearGradient><path fill="url(#SVGm3fQEb6B)" class="kv3gj1-be"/><linearGradient id="SVG2QcTGeBk" x1="43.901" x2="38.738" y1="77.759" y2="75.805" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r2o_cv-as"/><stop offset="1" class="s6rm2gd3x"/></linearGradient><path fill="url(#SVG2QcTGeBk)" class="mmgz2rb-y"/><radialGradient id="SVGyNl8lb5q" cx="-840.091" cy="575.859" r="1" gradientTransform="matrix(16.2998 0 0 -16.2998 13720.296 9451.03)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="fqlolabaa"/><stop offset=".368" class="jct3k-imk"/><stop offset=".727" class="x_enifbfx"/><stop offset=".988" class="necgdbbfe"/></radialGradient><path fill="url(#SVGyNl8lb5q)" class="vn2h84uvy"/><linearGradient id="SVG3wr8ubRj" x1="31.564" x2="51.564" y1="84.635" y2="63.426" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="jb0j4_2gw"/><stop offset="1" class="s6rm2gd3x"/></linearGradient><path fill="url(#SVG3wr8ubRj)" class="lr5iu3b5b"/><path class="uvqbgqb1h"/><path class="a1-v45bfx"/><path class="i9lgkq9yx"/><path class="owe1llbqh"/><path class="t8hsl5oga"/><radialGradient id="SVGhE8wQcBK" cx="-1012.206" cy="660.942" r="1" gradientTransform="rotate(-6.546 -55372.285 66189.5)scale(-7.1243 10.2595)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVGhE8wQcBK)" class="jh50sg1-i"/><radialGradient id="SVGSC0hke4W" cx="-1034.407" cy="617.62" r="1" gradientTransform="rotate(-158.561 -3183.875 -3510.85)scale(7.2212 -9.1125)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVGSC0hke4W)" class="tr_pubbax"/><radialGradient id="SVG3Oa1feQq" cx="-962.87" cy="613.562" r="1" gradientTransform="rotate(22.54 24309.66 -32366.385)scale(-14.8625 11.1724)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVG3Oa1feQq)" class="wmv16m4lo"/><radialGradient id="SVGQw0GubTl" cx="-1006.284" cy="698.985" r="1" gradientTransform="matrix(-8.0012 .076 .0488 5.144 -8056.816 -3485.046)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVGQw0GubTl)" class="yje-pabom"/><linearGradient id="SVGlZbz6cJl" x1="56.508" x2="58.461" y1="73.458" y2="75.411" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r2o_cv-as"/><stop offset="1" class="s6rm2gd3x"/></linearGradient><path fill="url(#SVGlZbz6cJl)" class="p4t9d3prr"/><path class="ln4271bjj"/><path class="jfr4c6qix"/><path class="dbeg1k2kn"/><path class="r5zwc3hjz"/><path class="cg4h7m7nn"/><radialGradient id="SVGOOrIbnfe" cx="-758.971" cy="572.619" r="1" gradientTransform="rotate(9.033 -39625.11 31496.968)scale(7.046 -10.1476)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGOOrIbnfe)" class="m0lvkpbzw"/><radialGradient id="SVGrvetzdBv" cx="-800.654" cy="525.077" r="1" gradientTransform="rotate(161.047 3382.6 1960.643)scale(-7.3369 9.2582)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGrvetzdBv)" class="xqebojbib"/><radialGradient id="SVGJAOu023w" cx="-849.016" cy="537.033" r="1" gradientTransform="rotate(159.947 6819.49 1888.317)scale(-14.7414 11.0802)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGJAOu023w)" class="e9_kp-6pf"/><radialGradient id="SVGzwHqeePn" cx="-778.784" cy="520.978" r="1" gradientTransform="rotate(183.027 3087.635 1421.68)scale(-7.9062 5.083)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGzwHqeePn)" class="gez7k187r"/><linearGradient id="SVGB5SoGc2I" x1="86.588" x2="51.965" y1="77.717" y2="77.717" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ms-lo7bhi"/><stop offset=".599" class="gg42svbns"/><stop offset="1" class="ms-lo7bhi"/></linearGradient><path fill="url(#SVGB5SoGc2I)" class="vrcbjnbjh"/><linearGradient id="SVGwSGqzdRh" x1="65.47" x2="94.2" y1="44" y2="44" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ms-lo7bhi"/><stop offset="1" class="gg42svbns"/></linearGradient><path fill="url(#SVGwSGqzdRh)" class="zpt5fo_tq"/><path class="yio6tj1fh"/><linearGradient id="SVGhyXQNcXD" x1="107.733" x2="89.663" y1="36.391" y2="55.368" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ms-lo7bhi"/><stop offset="1" class="gg42svbns"/></linearGradient><path fill="url(#SVGhyXQNcXD)" class="ggyb9ibfm"/><radialGradient id="SVGap1xhc8w" cx="-840.85" cy="576.261" r="1" gradientTransform="matrix(16.5281 0 0 -16.5281 13988.178 9581.706)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="o_4j53rwc"/><stop offset=".563" class="wkjr7927g"/><stop offset=".983" class="b5pelhk-b"/></radialGradient><path fill="url(#SVGap1xhc8w)" class="htsznfbzh"/><linearGradient id="SVG8ogsneAX" x1="61.134" x2="83.93" y1="61.324" y2="78.91" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="gg42svbns"/><stop offset="1" class="ms-lo7bhi"/></linearGradient><path fill="url(#SVG8ogsneAX)" class="xgj2_40uc"/><path class="xtf4ndbhk"/><path class="n4q3gg5ka"/><path class="n_fw6snrv"/><path class="gbhek7hso"/><path class="u0m-60b3k"/><path class="g2-ouaczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:people-wrestling-light-skin-tone-medium-light-skin-tone" /></template>
<style>
.a1-v45bfx {
  fill: var(--svg-color--039be5, #039be5);
  d: path("m59.6 104.4l-6.4-2.1h-7.1s-2 2.2-2 4.1v2.8c0 .6.5 1.2 1.2 1.2l15.8.1c.6 0 1-.5 1-1v-1.3c.1-1.7-.9-3.2-2.5-3.8");
}

.atqdr-9uk {
  stop-color: var(--svg-color--bfa055, #bfa055);
}

.b5pelhk-b {
  stop-color: var(--svg-color--ef6c00, #ef6c00);
}

.b9fn5-bcs {
  fill: var(--svg-color--f9ddbd, #f9ddbd);
  d: path("M50.1 29.9c.4-4.6-1.3-8.8-5.8-11l-.6-.3l-.9-.3h-.1c-.3-.1-.5-.1-.8-.2h-.3c-.2 0-.5-.1-.7-.1h-1.5c-.4 0-.8 0-1.2.1h-.1c-.4 0-.8.1-1.3.2c-.1 0-.2 0-.3.1c-.4.1-.7.2-1.1.3c-.07 0-.13.03-.2.1c-.4.1-.8.3-1.2.4c-.1 0-.1.1-.2.1c-.3.1-.7.3-1 .5c-.1 0-.2.1-.2.1c-.4.2-.8.4-1.1.6c-.4.2-.7.5-1 .7l-.1.1c-.3.3-.6.5-.9.8c-2.2 2.2-3.1 10.3-2 14.6c1.2 4.5-.99 8.68-1.5 10s.3 3.5 1.6 4.3c.6.4 1.2.5 1.8.5c2.7 0 4.7-3.5 4.7-3.5s1.26-1.84 2.25-1.95c.69-.08 1.28.13 3.68.53c.6.1 1.18.12 1.68.12c3.94 0 4.36-3.06 5.07-4.3c.23-.4.38-.45.73-.53c.73-.17 2.21-.41 2.2-1.27c-.02-1.54-2.1-3.3-1.6-4.5c.19-.5 1.97-3.4 1.99-6.2");
}

.cg4h7m7nn {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M89.5 21.6c-1.9-3-4.7-3.4-5.6-3.5c-.6-1.1-3.5-5.1-10.6-2.4c-1.7.6-2.83 1.67-3.8 2.7c-.42.44-.77.78-1.09 1.02s-.91.56-1.5.56c-1.31 0-1.21-2.08-1.21-2.08s-4.2 1.8-1.6 5.6c-1.3.9-1.7 2.6-1.7 4.1c0 2 1.4 3.75 3.4 4.25c0 0-.05-.34-.07-.68c-.05-.94.3-2.65 3.67-3.16c1.4-.2 2.9-.3 4.2-1.1c.5-.3.9-.7 1.3-1h.2c1.9.6.4 5.1 2.8 7.1c.5.4.8.2.8.2l.6-1.3c.4-.9.8-1.7 1.6-1.7c2.2 0 2.6 4 .2 5.3c-.2.1 1.2 4.3 6.5 3.2c2.7-.5 3.2-3 3.2-3s-1.1.5-1.6-.4c-.2-.51.1-1.31.8-2.21c2-2.7.6-5 .1-5.7c.3-.9.9-3.5-.6-5.8");
}

.dbeg1k2kn {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M71.38 36.76c.59-.14.9-.99.69-1.9c-.21-.92-.86-1.55-1.45-1.41s-.9.99-.69 1.9s.86 1.54 1.45 1.41");
}

.e7p1a9b-n {
  d: path("M47.6 75c-2.3-1.2-19-7.9-19-7.9l-2.7 11.4s11.9 4.1 16.1 5.7c.7.3 1.2.9 1.4 1.7l3.2 16.4h6.3s.3-12.3.3-17.3c0-6.5-2.7-8.5-5.6-10");
}

.e9_kp-6pf {
  d: path("M84.2 20.5c.4-2.3-1.21-4.05-3.21-5.05c-2.4-1.1-5.14-.7-7.54.2c-1.7.6-2.79 1.59-3.85 2.65c-.4.4-1.4 1.69-2.72 1.69c-1.24 0-1.18-2.09-1.18-2.09s-4.2 1.8-1.6 5.6c-1.3.9-1.7 2.55-1.7 4.05c0 2 1.34 3.76 3.34 4.26c0 0-.93-3.1 3.67-3.8c1.4-.2 2.8-.19 4.3-1.2c1.1-.7 1.3-1.4 2.7-1.6s3.4 0 4.8-.5c2.69-1.11 2.99-4.11 2.99-4.21");
}

.fqlolabaa {
  stop-color: var(--svg-color--4fc3f7, #4fc3f7);
}

.fwx9zn6gv {
  stop-color: var(--svg-color--454140, #454140);
}

.g2-ouaczx {
  fill: var(--svg-color--edbd82, #edbd82);
  d: path("M72.7 50.2s-6.3-1.8-8.4.1l5.9 2.1s2.8 1.3 3.7-.7c.4-.8-.7-1.3-1.2-1.5");
}

.gbhek7hso {
  fill: var(--svg-color--fb8c00, #fb8c00);
  d: path("m123.8 90.7l-2.7-.8c-1-.3-2.1-.4-3-.4c-.7 0-1.2.1-1.2.1l-2.4 7.7l.1 6.7c.1 1.7 1.2 3.1 2.8 3.6l1.2.4c.1 0 .2.1.3.1c.4 0 .8-.3 1-.7l4.7-15.1c.2-.7-.2-1.4-.8-1.6");
}

.gez7k187r {
  d: path("M86.1 35.89c-1.1-.8-1.7-2.4-3.4-3c-.1 1-.6 2.1-1.6 2.6c-.2.1 1.2 4.3 6.5 3.2c2.7-.5 3.2-3 3.2-3s-2.5 1.9-4.7.2");
}

.gg42svbns {
  stop-color: var(--svg-color--e0bb95, #e0bb95);
}

.ggyb9ibfm {
  d: path("m100.1 85.3l-5.6-20.7L82.3 69l8.5 21.4l.1.1c.3.6.6 1.2 1.2 1.8c.7.7 1.5 1.2 2.3 1.4h.2c.3.1.5.1.8.2l20.3 2.8l2.2-5.2z");
}

.htsznfbzh {
  d: path("M97.5 71.8c.3-.8.4-1.8.4-2.8c.2-5.9-1-12-3.7-17.8c-.9-2-3.1-6.8-8.2-6.8h-.8c-6.6.6-7.5 6.4-6.5 11.1c1.4 6.7 2.4 10.3 2.7 16.6c.1 2.1.9 4.5 2.5 5.4c.7 2.5 2.3 6 3.9 8.3c4.1-1.5 8.1-3.1 12.1-4.9c-.8-2.8-2.4-9.1-2.4-9.1");
}

.i9lgkq9yx {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m16.7 89l-7.6 4.2l2.5 8l8.6-3.4z");
}

.jb0j4_2gw {
  stop-color: var(--svg-color--f9ddbd, #f9ddbd);
}

.jct3k-imk {
  stop-color: var(--svg-color--42bff6, #42bff6);
}

.jfr4c6qix {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M68.9 43.5c.8-.1 1.6-.5 2.2-1.1c.7-.7 0-1.3-.8-.7c-.5.3-1.2.6-1.9.6z");
}

.jh50sg1-i {
  d: path("M25.2 26.9c0-.1.3 2.1 3.9 2.7c1.4.4 2.6 4.3-.1 6.1c-2.4 1.6-4.8-.3-4.8-.3s.4.2 1 .1c.4 0 .6-.5.6-.5c.3-.5 0-1.3-.7-2.3c-1.9-2.8-.4-5.1.1-5.8");
}

.kv3gj1-be {
  d: path("M68.6 52.1c-.3.8-2.4 2-5.2 3.1c-.2.1-.3.1-.5.2c-.8.3-1.7.7-2.6 1l-.9.3c-4.8 1.6-10.2 2.9-12.9 3h-.7c-.2 0-.3-.1-.4-.1l-.4-.1l-6.2-1.2l-7.4-1.5l2.6-8.2l.1-.2l8.3 2.9l4.3 1.5c2.1-.3 12.9-1.8 14.5-2.1c.8-.2 2.3-.4 3.8-.4c2.2 0 4.2.4 3.6 1.8");
}

.l1arbqe-k {
  stop-color: var(--svg-color--bfa055, #bfa055);
  stop-opacity: 0;
}

.ln4271bjj {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M89.31 45.24c-.84-.92-1.44-2.55-1.58-4.12c-.37-4.08 1.43-9.75.42-14.26c-1.53-6.79-4.98-9.37-12.35-9.37S63.07 28.87 67 35.19c.47 1.29-1.86 2.6-1.79 4.4c.02.43.38.94 1.24 1.21c.64.2 1.37.15 1.52.49c.1.24.42 1.02.65 1.56c.23.53.84 1.87 1.66 2.5s2.14.91 3.23.84c1.55-.13 3.66-.42 4.4-.5s.92.11 1.36.69s1.21 4.13 5.74 5.11c3.56.02 5.7-4.65 4.3-6.25");
}

.lr5iu3b5b {
  d: path("M67.03 67.51c-.13-.16-.53-.31-1.03-.31c.2-.1.7-.46.5-1.2c-.3-.8-1.7-.7-3.5-.4c-.7.1-1.5.2-1.9.2c-.3 0-1.1 0-1.8-.1h.1c.8-.3 1.33-.71 1.75-1.07c.48-.4.52-.78.45-1.02c-.22-.7-1.09-.78-2.02-.62c-.77.13-1.73.45-2.29.71c-.7.3-2.91.68-3.93.43c-.9-.22-8.5-2.77-9.67-3.23s-1.96-1.06-2.56-2.16c0 0-4.72-8.83-5.24-9.74c-.86-1.48-2.7-2.4-4.5-2.2c-2 .1-3.8 1.6-4.4 3.6c-.3 1.2-.24 2.37.4 3.5s6.6 10.3 6.6 10.3c1.1 1.8 2.8 3 4.8 3.6l14.6 4.1h.2c.7.3 1.5.5 2.4.8l.6.2c1.7.4 3.7.8 5.5.8c1.7 0 3.16-.33 3.2-1.3c.02-.44-.5-.7-1.2-.8c1.1-.1 2.12-.56 2.11-1.17s-.41-.83-.61-.83c.8-.2 1.62-.66 1.69-1.32c.04-.31-.13-.61-.25-.77");
}

.m0lvkpbzw {
  d: path("M90.1 27.4s-.62 2.06-3.97 2.41c-1.4.3-2.8 4.1-.2 6c2.3 1.7 4.84-.1 4.84-.1s-.47.21-.95.08s-.68-.51-.68-.78s.1-.94.8-1.84c2.09-2.77.66-5.07.16-5.77");
}

.mmgz2rb-y {
  d: path("m45.1 59.4l-6.2-1.2l-4.7-9.7v-.2l8.3 3z");
}

.ms-lo7bhi {
  stop-color: var(--svg-color--cca47a, #cca47a);
}

.n_fw6snrv {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m110.8 88.1l-3.3 8.2l9.2 2l2.2-6.9z");
}

.n4q3gg5ka {
  fill: var(--svg-color--fb8c00, #fb8c00);
  d: path("M82.2 106.4c0-1.9-2-4.1-2-4.1h-7.1l-6.4 2.1c-1.5.6-2.6 2.1-2.6 3.8v1.3c0 .6.4 1 1 1l15.8-.1c.6 0 1.2-.5 1.2-1.2z");
}

.nc1qd5b_i {
  d: path("m35.5 83.3l-4.9-12.1l-10.9 4.4l4.2 8.7c.5.8.2 1.7-.6 2.1l-13 6.8l3.1 6.3l18.1-7.2c3.8-1.3 5.5-5.4 4-9");
}

.nco8tdb8o {
  fill: var(--svg-color--dba689, #dba689);
  d: path("m75.1 48.7l-3.1-.2c-.8.1-4.7.6-5.5 2c-.2.3-.2.7-.1.9c.2.8.8 1.4 1.6 1.4h.3l6.9-1.6c1.2-.4 1.4-1.1 1.4-1.2v-.2c-.1-.8-.9-1-1.5-1.1");
}

.necgdbbfe {
  stop-color: var(--svg-color--03a9f4, #03a9f4);
}

.ngccpbbgb {
  fill: var(--svg-color--ba8f63, #ba8f63);
  d: path("M56.5 51.7c0-.4-.1-.7-.4-1c-1.2-1-5.1-.3-5.9-.1l-2.8 1.1c-.4.2-1.2.7-1.1 1.5c0 .07.03.13.1.2c0 .1.5.7 1.8.7l7-.6c.8-.2 1.3-1 1.3-1.8");
}

.o_4j53rwc {
  stop-color: var(--svg-color--fb8c00, #fb8c00);
}

.o80-tkbsr {
  fill: var(--svg-color--0288d1, #0288d1);
  d: path("M29.5 66.2c-.9-.3-1.7-.4-2.6-.4c-3 0-5.8 1.8-6.9 4.8c-1.4 3.8.5 8.1 4.4 9.5l9.2 3.4l5.1-13.9z");
}

.owe1llbqh {
  fill: var(--svg-color--039be5, #039be5);
  d: path("M11.8 92s-.5-.1-1.2-.1c-.9 0-2 .1-3 .4l-2.7.8c-.6.2-1 .8-.8 1.5l4.7 15.1c.1.4.5.7 1 .7c.1 0 .2 0 .3-.1l1.2-.4c1.6-.5 2.7-1.9 2.8-3.6l.1-6.7z");
}

.p4t9d3prr {
  d: path("M63 55.4c-.8.3-4.9 1.7-5.2 1.8c-1.8-.9-4-3.3-4-3.3l3.5-2.1z");
}

.r2o_cv-as {
  stop-color: var(--svg-color--f9ddbd, #f9ddbd);
  stop-opacity: 0;
}

.r5zwc3hjz {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M69.8 33c-.9.7-1.4.1-1.3-.6c.1-.5.6-1.1 1.9-1.3c1.2-.2 1.9.3 2.4.6s.6.7.3.8c-.3.3-2.2-.3-3.3.5");
}

.rlrfr4bym {
  fill: var(--svg-color--444, #444);
  d: path("M46 44.2c-.8-.2-1.6-.5-2.2-1.2c-.6-.8 0-1.3.8-.7c.5.4 1.2.7 1.9.7z");
}

.s0ywn2bjh {
  fill: var(--svg-color--454140, #454140);
  d: path("M45.6 33.7c.9.7 1.4.1 1.3-.5c-.1-.5-.6-1.1-1.9-1.3c-1.2-.2-1.9.2-2.4.5s-.6.7-.3.8s2.2-.4 3.3.5");
}

.s6rm2gd3x {
  stop-color: var(--svg-color--ffd29c, #ffd29c);
}

.t8hsl5oga {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M26.2 21.2c2.1-2.9 4.9-3.2 5.8-3.3c.7-1.1 3.8-5 10.8-2c1.7.7 2.8 1.9 3.8 2.9c.4.4.8.9 1.2 1.2c.3.2.9.6 1.5.5c1.3-.1 1.3-2 1.3-2s4.1 1.9 1.2 5.6c1.3 1 1.6 2.7 1.5 4.2c-.1 2.1-1.5 3.7-3.7 4.1c0 0 1.2-3.1-3.5-4c-1.4-.3-3-.4-4.2-1.3c-.5-.3-.8-.8-1.3-1.1h-.2c-2 .5-.7 5.1-3.2 7.1c-.5.4-.8.1-.8.1l-.5-1.3c-.4-.9-.8-1.7-1.5-1.7c-2.3 0-2.8 3.9-.5 5.4c.2.2-1.4 4.3-6.7 3c-2.7-.7-3.1-3.2-3.1-3.2s1.1.6 1.6-.3c.3-.5 0-1.3-.7-2.3c-1.9-2.8-.4-5.1.1-5.8c-.1-.9-.5-3.5 1.1-5.8");
}

.tr_pubbax {
  d: path("M26.2 21.2c1.1-1.5 2.7-2.6 4.5-3.1c.3 0 .9-.1 1.3-.1c-.4.7-.5 1.5-.4 2.4c0 0 .1 1.4.9 2.6c-1 .9-1.7 2.1-2.4 3.3c-.6 1-1.2 2.2-1 3.3c-.7-.2-1.8-.3-2.8-1.1S25 26.3 25 25s.4-2.6 1.2-3.8");
}

.u0m-60b3k {
  fill: var(--svg-color--ba8f63, #ba8f63);
  d: path("M55.4 67.78c-.01.21-.17.22-.49.21s-3.5-.11-5.06-.9c.18-.02.28-.02.43-.02c1.87.35 3.31.43 4.64.47c.3.01.49.04.48.24m-5.09 1.52c1.75.61 4.59.63 4.92.61c.27-.02.34-.12.34-.32c0-.1-.1-.2-.3-.2c-1.5.1-3.3 0-4.8-.2zm5.56 2.19c0 .1-.04.28-.34.29c-1.47.07-2.99-.22-4.09-.42c0 0 .48-.16.55-.16s2.39.23 3.39.13c.25-.03.49-.04.49.16");
}

.uvqbgqb1h {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m45.1 96.9l1.3 6.9h6.9l.4-7.7z");
}

.vn2h84uvy {
  d: path("M36 55.1c1.9-4.4 1.1-7.6-.1-8.7c-2-1.9-4-2.1-5-2.3c-.4-.1-.7-.1-1.1-.1c-3.7 0-6.6 2.8-8.7 7.2c-2.8 5.8-4.4 12.8-4.4 18.7c0 5.4 5.2 12.9 6.5 15.5c4-1.7 7.9-3.4 11.8-5.4c-.4-1.1-1.1-2.7-1.9-4.4c.3-.8.5-1.7.5-2.6c.6-5.5.2-11.9 2.4-17.9");
}

.vrcbjnbjh {
  d: path("M85.6 47.8c-1.2-1.3-3.1-1.8-4.8-1.4h-.3c-.07 0-.13.03-.2.1l-12.1 4.3c-1.8-.3-7.4-1.2-10.3-1.1c-1.1 0-4.3.4-4.4.4s-.2.1-.3.1l-3.4 3.1c-.7.5-.8 1.4-.4 2c.3.4.7.9 6.1-1.9q.75-.3 1.5 0l8.1 4c1.2.6 2.4.9 3.7.9c.5 0 1 0 1.6-.1L82.2 56c.4 0 .9-.1 1.3-.2c.07 0 .13-.03.2-.1c1.1-.4 2-1.2 2.6-2.3c1-1.7.7-4.1-.7-5.6");
}

.wkjr7927g {
  stop-color: var(--svg-color--f67f00, #f67f00);
}

.wmv16m4lo {
  d: path("M31.6 20.4c-.3-2.4 1.4-4.1 3.5-5c2.5-1.1 5.3-.5 7.7.5c1.7.7 2.8 1.9 3.8 2.9c.4.4.8.9 1.2 1.2c.3.2.9.6 1.5.5c1.3-.1 1.3-2 1.3-2s4.1 1.9 1.2 5.6c1.3 1 1.6 2.7 1.5 4.2c-.1 2.1-1.5 3.7-3.7 4.1c0 0 1.2-3.1-3.5-4c-1.4-.3-3-.4-4.2-1.3c-1-.8-1.3-1.5-2.6-1.7c-1.4-.3-3.4-.2-4.8-.8c-2.8-1.1-2.9-4.2-2.9-4.2");
}

.x_enifbfx {
  stop-color: var(--svg-color--20b3f5, #20b3f5);
}

.x21lzsbti {
  stop-color: var(--svg-color--454140, #454140);
  stop-opacity: 0;
}

.xb8szu46a {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M45.33 36.01c.25-.91-.02-1.77-.61-1.93s-1.26.44-1.51 1.35s.02 1.77.61 1.93s1.26-.45 1.51-1.35");
}

.xgj2_40uc {
  d: path("M89.3 51.1c-.16-1.4-.7-2.5-1.7-3.3s-2.3-1.2-3.6-1.2c-1.5.1-3.06 1.09-3.7 2.2c-.36.61-5.9 11.3-5.9 11.3s-10.25 3.58-11.57 3.91c-1.33.33-3.03-.11-3.73-.41c-1.83-.61-2.18-.74-3.16-.73c-.87.02-1.1.44-1.12.72c-.03.27.03.47.18.71c.35.56 2.1 1.3 2.1 1.3c-.7.1-1.5.1-1.9.1c-.3 0-1.1-.1-1.8-.2c-1.32-.15-2.46-.25-3.12-.05c-.55.17-.59.68-.54.94c.07.37.35.57.55.67c-.2 0-.56-.01-.94.18c-.38.2-.38.54-.35.75c.06.42.69.96 1.5 1.2c0 0-.3.12-.44.31c-.13.17-.16.3-.16.49c0 .73.83 1.08 1.83 1.18l.27.03c-.64.16-1.22.29-1.2.9s.8 1.31 3.2 1.2c1.7-.08 3.02-.12 5.99-.71S77.1 67.3 77.9 67s1.85-.8 2.78-1.96c.65-.81 7.3-9.99 7.78-10.68c.77-1.14.96-2.19.84-3.26");
}

.xqebojbib {
  d: path("M89.51 21.64c-1-1.6-2.39-2.74-4.19-3.24c-.3-.1-1.03-.3-1.43-.3c.3.7.47 1.46.31 2.44c-.17 1.03-.42 1.78-1.15 2.78c1 .9 1.79 2.02 2.39 3.22c.5 1 1.04 2.17.74 3.27c.78-.09 1.79-.26 2.84-1.04c1.03-.7 1.45-2.09 1.45-3.6s-.26-2.43-.96-3.53");
}

.xtf4ndbhk {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M78.7 96.7L70 98.6l3.3 5.9l7.4-.7z");
}

.yio6tj1fh {
  fill: var(--svg-color--e65100, #e65100);
  d: path("M93.4 72.8c-1.2-2.3-3.6-3.7-6-3.7c-1.1 0-2.1.2-3.1.8L75 74.7l6.3 12.1l9.2-4.8c3.3-1.7 4.6-5.8 2.9-9.2");
}

.yje-pabom {
  d: path("M29 35.7c1.2-.8 1.8-2.4 3.5-2.9c0 1 .5 2.1 1.5 2.7c.2.2-1.4 4.3-6.7 3c-2.7-.7-3.1-3.2-3.1-3.2s2.4 1.9 4.8.4");
}

.zpt5fo_tq {
  d: path("m94.2 79.3l-4.7-11l-20.3 11c-3.1 1.7-4.7 5.3-3.1 9.3c1.7 4.2 7.1 15.1 7.1 15.1l6.6-1.3l-4.4-14.8z");
}

</style>
