<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v08u51g1f"/><linearGradient id="SVGmD3EZV9p" x1="25.87" x2="53.21" y1="45.3" y2="45.3" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset="1" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGmD3EZV9p)" class="e7p1a9b-n"/><path class="o6z3vabvv"/><linearGradient id="SVG35vfHcxL" x1="10.42" x2="36.071" y1="44.65" y2="44.65" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset="1" class="ygm_dez4e"/></linearGradient><path fill="url(#SVG35vfHcxL)" class="nc1qd5b_i"/><path class="bgjqh8bbr"/><path class="stg138y3s"/><path class="dza5agbrz"/><path class="xg38eubmv"/><path class="ecj9uh00h"/><radialGradient id="SVGPPbWed4m" cx="-954.268" cy="605.336" r="1" gradientTransform="rotate(-152.365 -6881.9 -7106.11)scale(17.0955 -16.8977)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGPPbWed4m)" class="v9ziyccwm"/><radialGradient id="SVG4J4cnboG" cx="-839.586" cy="607.316" r="1" gradientTransform="rotate(210.374 6157.072 7703.62)scale(-18.2686 18.4521)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".526" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVG4J4cnboG)" class="bts9uq96w"/><radialGradient id="SVGxuOa1dZY" cx="-797.997" cy="606.668" r="1" gradientTransform="rotate(30.528 -34512.742 7038.62)scale(10.4349 -27.2563)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGxuOa1dZY)" class="iwzegzq6c"/><path class="x-ak-59mr"/><radialGradient id="SVGSyWvvc4v" cx="-973.196" cy="625.466" r="1" gradientTransform="rotate(-167.258 -5609.602 -4730.75)scale(12.5035 -12.9923)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGSyWvvc4v)" class="k4iwphp8k"/><path class="ru3egjr7k"/><linearGradient id="SVGrqSDKdhz" x1="31.509" x2="68.407" y1="76.026" y2="76.026" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="ygm_dez4e"/><stop offset="1" class="x16mk-bfp"/></linearGradient><path fill="url(#SVGrqSDKdhz)" class="oqks-vpxu"/><linearGradient id="SVGTVSKqduQ" x1="56.538" x2="58.476" y1="73.426" y2="75.364" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="flyfeos6a"/><stop offset="1" class="x16mk-bfp"/></linearGradient><path fill="url(#SVGTVSKqduQ)" class="fuo1u-krl"/><linearGradient id="SVGQZoJrdoo" x1="43.891" x2="38.797" y1="77.695" y2="75.767" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="flyfeos6a"/><stop offset="1" class="x16mk-bfp"/></linearGradient><path fill="url(#SVGQZoJrdoo)" class="t2vt1xbzj"/><radialGradient id="SVGuWjH9c4O" cx="-840.091" cy="575.859" r="1" gradientTransform="matrix(16.2998 0 0 -16.2998 13718.235 9445.445)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o-m18bc6g"/><stop offset=".545" class="xpwmi9bxi"/><stop offset=".987" class="pqgvm3vez"/></radialGradient><path fill="url(#SVGuWjH9c4O)" class="i8p85dbjh"/><linearGradient id="SVGXYeB1HZw" x1="31.564" x2="51.564" y1="84.635" y2="63.426" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="ygm_dez4e"/><stop offset="1" class="x16mk-bfp"/></linearGradient><path fill="url(#SVGXYeB1HZw)" class="gox8j8bdi"/><path class="uvqbgqb1h"/><path class="ul1ujbiao"/><path class="i9lgkq9yx"/><path class="dh64f6b8v"/><path class="wdmqm4mmj"/><path class="n2ut4xcwt"/><path class="fff982bxs"/><path class="sdj03mb0j"/><path class="k927ngbug"/><radialGradient id="SVGds8Fke9C" cx="-860.432" cy="556.292" r="1" gradientTransform="rotate(153.637 8496.764 3005.378)scale(-17.0967 16.8972)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGds8Fke9C)" class="v21u60_1u"/><radialGradient id="SVG1kxoRcoK" cx="-925.158" cy="651.085" r="1" gradientTransform="rotate(150.896 -9961.353 -3779.187)scale(18.2689 -18.4519)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".526" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVG1kxoRcoK)" class="bekqhub0d"/><radialGradient id="SVGTIWsxFXQ" cx="-947.582" cy="636.253" r="1" gradientTransform="rotate(150.745 -7162.825 -7350.565)scale(10.4354 -27.2552)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGTIWsxFXQ)" class="t83l4yb_z"/><path class="bdjh87bui"/><radialGradient id="SVGyTECZddF" cx="-832.314" cy="555.393" r="1" gradientTransform="rotate(168.528 5594.621 3098.05)scale(-12.4852 12.9723)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGyTECZddF)" class="hznph12uf"/><linearGradient id="SVGY0OvBc9d" x1="86.588" x2="51.965" y1="77.717" y2="77.717" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".599" class="ygm_dez4e"/><stop offset="1" class="x16mk-bfp"/></linearGradient><path fill="url(#SVGY0OvBc9d)" class="uvwjpdf6c"/><linearGradient id="SVGtJ5c9c0O" x1="65.471" x2="94.2" y1="44.1" y2="44.1" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset="1" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGtJ5c9c0O)" class="fzuvvh07s"/><path class="f4dnuhbcj"/><linearGradient id="SVGId0nac0e" x1="107.718" x2="89.649" y1="36.407" y2="55.383" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset="1" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGId0nac0e)" class="ggyb9ibfm"/><radialGradient id="SVGMYxNNb8M" cx="-840.85" cy="576.261" r="1" gradientTransform="matrix(16.5281 0 0 -16.5281 13988.178 9581.677)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xb94qyb-t"/><stop offset=".705" class="ci_fo_bpd"/><stop offset="1" class="u3kz4vb7l"/></radialGradient><path fill="url(#SVGMYxNNb8M)" class="k5cyxib-s"/><linearGradient id="SVGCZWB7c9I" x1="61.133" x2="83.93" y1="61.324" y2="78.91" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="ygm_dez4e"/><stop offset="1" class="x16mk-bfp"/></linearGradient><path fill="url(#SVGCZWB7c9I)" class="xgj2_40uc"/><path class="x20bfvbhy"/><path class="fs3h5l0-s"/><linearGradient id="SVGiQIPpc8b" x1="64.24" x2="82.25" y1="23.6" y2="23.6" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xb94qyb-t"/><stop offset=".705" class="ci_fo_bpd"/><stop offset="1" class="u3kz4vb7l"/></linearGradient><path fill="url(#SVGiQIPpc8b)" class="x3tflxbpz"/><path class="jozhe5dbj"/><linearGradient id="SVGBOkyidIH" x1="114.42" x2="124.613" y1="31.2" y2="31.2" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xb94qyb-t"/><stop offset=".705" class="ci_fo_bpd"/><stop offset="1" class="u3kz4vb7l"/></linearGradient><path fill="url(#SVGBOkyidIH)" class="jt1fvtbli"/><path class="rccen5mxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:women-wrestling-tone3" /></template>
<style>
.bdjh87bui {
  fill: var(--svg-color--543930, #543930);
  d: path("M86 18.3c-2.8-2.4-6.9-3.5-10.8-2.9c-3.4.5-8 2.4-10.3 5.9c-1.4 2.1-2 4.7-1.2 7.2c.5 1.5 1.8 2.1 1.8 2.1s.8-3.9 4.4-3.7c3.8.2 5.3-.9 5.3-.9c-.7 3.3.7 4.7 1.9 5.5c.7.4 1.3 1 1.6 1.3c.2.2.3.1.3-.1c.1-.5.2-1.5.3-1.9c.4-1.5 1.6-1.3 1.6-1.3c1.6.2 2.7 3.3.6 5.7c-.1.1-.2.2 0 .5c1.6 3 5.2 2.4 5.4 2.2h.1c.4-.3.7-.8.6-1.4c-.1-2.2.7-3 1.2-4.1c.5-1.2 1.2-2.6 1-6.1c-.2-3.2-1.5-6-3.8-8");
}

.bekqhub0d {
  d: path("M100.1 37.3c-.5-1.8-.7-3.8-.8-5.7c-.1-1.7 0-3.2-1.7-4.2c-2.7-1.5-6.8-1-9.6 1.1c-.8.6-1.3 1.3-.9 2c.3.5.6 1 .8 1.6c.5 1.3.9 2.7 1.4 4.1c1.2 3.2 2.8 6.4 5.9 8.4c8.6 5.7 14.2 2.1 14.2 2.1s-7.2-2.3-9.3-9.4");
}

.bgjqh8bbr {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M48.17 36c-.5 1.2 1.6 3.1 1.6 4.5c0 1.1-2.4 1.2-2.6 1.4c-.3.1-.5.6-.7 1.1c-.2.4-.3.8-.6 1.2c-.8 1.4-2.2 2.8-5.7 2.2c-2.3-.4-2.5-.5-3.3-.6c-1.5-.2-2.7 2-2.7 2s-2.9 5.2-6.5 3c-4.2-2.5-2.1-5.8-2.1-5.8s3.8-5.2 2.7-9.8c-1.1-4.3-.7-11.3 1.5-13.4c3.4-3.3 9.7-5 14.1-3.1c4.9 2.1 6.7 6.5 6.3 11.4c-.2 1.8-.64 3.5-1.14 4.44c-.34.66-.76 1.12-.86 1.46");
}

.bts9uq96w {
  d: path("M15.11 37c.6-1.8.8-3.8.9-5.7c.1-1.7.1-3.2 1.8-4.2c2.7-1.5 6.8-.9 9.6 1.3c.8.7 1.2 1.3.8 2c-.3.5-.6 1-.9 1.6c-.5 1.3-.9 2.7-1.5 4c-1.2 3.2-3 6.3-6 8.3c-8.7 5.5-14.3 1.8-14.3 1.8s7.4-2 9.6-9.1");
}

.ci_fo_bpd {
  stop-color: var(--svg-color--5914f2, #5914f2);
}

.dh64f6b8v {
  fill: var(--svg-color--e53935, #e53935);
  d: path("M11.8 92s-.5-.1-1.2-.1c-.9 0-2 .1-3 .4l-2.7.8c-.6.2-1 .8-.8 1.5l4.7 15.1c.1.4.5.7 1 .7c.1 0 .2 0 .3-.1l1.2-.4c1.6-.5 2.7-1.9 2.8-3.6l.1-6.7z");
}

.dza5agbrz {
  fill: var(--svg-color--49362e, #49362e);
  d: path("M45.29 35.98c.26-.9-.01-1.77-.59-1.94s-1.27.43-1.52 1.33c-.26.9.01 1.77.59 1.94c.58.18 1.26-.42 1.52-1.33");
}

.e7p1a9b-n {
  d: path("M47.6 75c-2.3-1.2-19-7.9-19-7.9l-2.7 11.4s11.9 4.1 16.1 5.7c.7.3 1.2.9 1.4 1.7l3.2 16.4h6.3s.3-12.3.3-17.3c0-6.5-2.7-8.5-5.6-10");
}

.ecj9uh00h {
  fill: var(--svg-color--543930, #543930);
  d: path("M15.11 37c2.3-7.3-1.1-13.7 6.4-17c5-2.2 11.6 2.4 12.4 4.3c1.5 3.7-3.6 4.4-5.1 5.4c-2.2 1.4-2.5 10.7-8.9 14.7c-8.7 5.5-14.3 1.8-14.3 1.8s7.3-2.1 9.5-9.2");
}

.f4dnuhbcj {
  fill: var(--svg-color--4300d9, #4300d9);
  d: path("M93.4 72.8c-1.2-2.3-3.6-3.7-6-3.7c-1.1 0-2.1.2-3.1.8L75 74.7l6.3 12.1l9.2-4.8c3.3-1.8 4.6-5.9 2.9-9.2");
}

.fff982bxs {
  fill: var(--svg-color--49362e, #49362e);
  d: path("M71.55 37.05c.59-.15.87-1.01.64-1.92c-.24-.91-.9-1.52-1.49-1.37s-.87 1.01-.64 1.92s.9 1.52 1.49 1.37");
}

.flyfeos6a {
  stop-color: var(--svg-color--ba8d68, #ba8d68);
  stop-opacity: 0;
}

.fs3h5l0-s {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M78.7 96.7L70 98.6l3.3 5.8l7.4-.6z");
}

.fuo1u-krl {
  d: path("M63.03 55.49c-.8.3-4.93 1.61-5.23 1.71c-1.8-.9-4-3.3-4-3.3l3.5-2.1z");
}

.fzuvvh07s {
  d: path("m94.2 79.2l-4.7-11l-20.3 11c-3.1 1.7-4.7 5.3-3.1 9.3c1.7 4.2 7.1 15.1 7.1 15.1l6.6-1.3l-4.4-14.8z");
}

.ggyb9ibfm {
  d: path("m100.1 85.3l-5.6-20.7L82.3 69l8.5 21.4l.1.1c.3.6.6 1.2 1.2 1.8c.7.7 1.5 1.2 2.3 1.4h.2c.3.1.5.1.8.2l20.3 2.8l2.2-5.2z");
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.gox8j8bdi {
  d: path("M67.03 67.51c-.13-.16-.53-.31-1.03-.31c.2-.1.7-.46.5-1.2c-.3-.8-1.7-.7-3.5-.4c-.7.1-1.5.2-1.9.2c-.3 0-1.1 0-1.8-.1h.1c.8-.3 1.33-.71 1.76-1.07c.48-.4.52-.78.45-1.02c-.22-.7-1.09-.78-2.02-.62c-.77.13-1.73.45-2.29.71c-.7.3-2.91.68-3.93.43c-.9-.22-8.5-2.77-9.67-3.23s-1.96-1.06-2.56-2.16c0 0-4.72-8.83-5.24-9.74c-.86-1.48-2.7-2.4-4.5-2.2c-2 .1-3.8 1.6-4.4 3.6c-.3 1.2-.24 2.37.4 3.5S34 64.2 34 64.2c1.1 1.8 2.8 3 4.8 3.6l14.6 4.1h.2c.7.3 1.5.5 2.4.8l.6.2c1.7.4 3.7.8 5.5.8c1.7 0 3.16-.33 3.2-1.3c.02-.44-.5-.7-1.2-.8c1.1-.1 2.12-.56 2.11-1.17s-.41-.83-.61-.83c.8-.2 1.62-.66 1.69-1.32c.03-.31-.14-.61-.26-.77");
}

.hznph12uf {
  d: path("M86 18.3c-2.8-2.4-6.9-3.5-10.8-2.9c-3.4.5-8 2.4-10.3 5.9c-1.4 2.1-2 4.7-1.2 7.2c.5 1.5 1.8 2.1 1.8 2.1s.8-3.9 4.4-3.7c3.8.2 5.3-.9 5.3-.9c-.7 3.3.7 4.7 1.9 5.5c.7.4 1.3 1 1.6 1.3c.2.2.3.1.3-.1c.1-.5.2-1.5.3-1.9c.4-1.5 1.6-1.3 1.6-1.3c1.6.2 2.7 3.3.6 5.7c-.1.1-.2.2 0 .5c1.6 3 5.2 2.4 5.4 2.2h.1c.4-.3.7-.8.6-1.4c-.1-2.2.7-3 1.2-4.1c.5-1.2 1.2-2.6 1-6.1c-.2-3.2-1.5-6-3.8-8");
}

.i8p85dbjh {
  d: path("M36 55.1c1.9-4.4 1.1-7.6-.1-8.7c-2-1.9-4.53-2.4-6.1-2.4c-3.66 0-6.6 2.8-8.7 7.2c-2.8 5.8-4.4 12.8-4.4 18.7c0 5.4 5.2 12.9 6.5 15.5c4-1.7 7.9-3.4 11.8-5.4c-.4-1.1-1.1-2.7-1.9-4.4c.3-.8.5-1.7.5-2.6c.6-5.5.2-11.9 2.4-17.9");
}

.i9lgkq9yx {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m16.7 89l-7.6 4.2l2.5 8l8.6-3.4z");
}

.iwzegzq6c {
  d: path("M11.61 47.4s8-.6 12-6.6c1.6-2.4 2.5-4.6 2.9-6.2c.4-1.3 2.5-6.5 4.3-7.5c.1.1-13.1 6.4-19.2 20.3");
}

.jozhe5dbj {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m110.8 88.1l-3.3 8.2l9.2 1.9l2.2-6.9z");
}

.jt1fvtbli {
  d: path("m123.8 90.7l-2.7-.8c-1-.3-2.1-.4-3-.4c-.7 0-1.2.1-1.2.1l-2.4 7.7l.1 6.7c.1 1.7 1.2 3.1 2.8 3.6l1.2.4c.1 0 .2.1.3.1c.4 0 .8-.3 1-.7l4.7-15.1c.2-.7-.2-1.4-.8-1.6");
}

.k4iwphp8k {
  d: path("M29.71 18.3c2.9-2.4 6.9-3.4 10.9-2.7c3.4.6 7.9 2.5 10.2 6.1c1.3 2.2 1.9 4.7 1.1 7.3c-.5 1.5-1.9 2-1.9 2s-.7-3.9-4.3-3.8c-3.8.1-5.3-1-5.3-1c.6 3.3-.8 4.7-2 5.5c-.7.4-1.3.9-1.7 1.2c-.2.2-.3.1-.3-.1c0-.5-.1-1.5-.2-1.9c-.4-1.5-1.6-1.3-1.6-1.3c-1.6.2-2.8 3.2-.8 5.7c0 .1.2.2 0 .5c-1.6 3-5.3 2.3-5.5 2.1c-.4-.3-.6-.8-.6-1.4c.1-2.2-.6-3-1.1-4.1c-.5-1.2-1.1-2.6-.9-6.1c.2-3.3 1.6-6 4-8");
}

.k5cyxib-s {
  d: path("M97.5 71.7c.3-.8.4-1.8.4-2.8c.2-5.9-1-12-3.7-17.8c-.9-2-3.1-6.8-8.2-6.8h-.8c-6.6.6-7.5 6.4-6.5 11.1c1.4 6.7 2.4 10.3 2.7 16.6c.1 2.1.9 4.5 2.5 5.4c.7 2.5 2.3 6 3.9 8.3c4.1-1.5 8.1-3.1 12.1-4.9c-.8-2.7-2.4-9.1-2.4-9.1");
}

.k927ngbug {
  fill: var(--svg-color--543930, #543930);
  d: path("M100.1 37.3c-2.2-7.4 1.4-13.7-6-17.1c-4.9-2.3-11.7 2.1-12.5 4c-1.6 3.7 3.5 4.5 5 5.5c2.1 1.5 2.3 10.7 8.6 14.9c8.6 5.7 14.2 2.1 14.2 2.1s-7.2-2.3-9.3-9.4");
}

.n2ut4xcwt {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M68.83 42.6c.2.4.3.8.5 1.2c.8-.2 1.7-.5 2.2-1.2c.6-.8 0-1.3-.8-.7c-.4.3-1.2.6-1.9.7");
}

.nc1qd5b_i {
  d: path("m35.5 83.3l-4.9-12.1l-10.9 4.4l4.2 8.7c.5.8.2 1.7-.6 2.1l-13 6.8l3.1 6.3l18.1-7.2c3.8-1.3 5.5-5.4 4-9");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.o-m18bc6g {
  stop-color: var(--svg-color--ef5350, #ef5350);
}

.o6z3vabvv {
  fill: var(--svg-color--c62828, #c62828);
  d: path("M29.5 66.2c-.9-.3-1.7-.4-2.6-.4c-3 0-5.8 1.8-6.9 4.8c-1.4 3.8.5 8.1 4.4 9.5l9.2 3.4l5.1-13.9z");
}

.oqks-vpxu {
  d: path("M68.4 52.56c0 1-4.55 2.69-9 4.14s-10.44 2.76-11.38 2.88c-1.45.18-2.13.14-3.44-.12c-1.34-.27-5.78-1.16-5.78-1.16l-7.4-1.5l2.57-8.54L46.7 52.8c2.1-.3 16.8-2.5 18.3-2.5c2.2 0 3.4.55 3.4 2.26");
}

.pqgvm3vez {
  stop-color: var(--svg-color--e53935, #e53935);
}

.rccen5mxj {
  fill: var(--svg-color--91674d, #91674d);
  d: path("M72.7 50.2s-6.43-1.9-8.53 0c0 0 5.35 1.96 6.03 2.2c.69.23 3.31.62 3.7-.7c.29-.98-.7-1.3-1.2-1.5");
}

.ru3egjr7k {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M75.1 48.7c-.68-.11-2.07-.17-3.1-.2c-.68-.02-5.5.98-5.5 2c0 2.1.85 2.43 1.8 2.3c0 0 6.21-1.42 6.9-1.6s1.42-.56 1.4-1.4c-.01-.58-.82-.99-1.5-1.1");
}

.sdj03mb0j {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M73.23 32.8c.2-.1.1-.5-.3-.8s-1.2-.8-2.4-.5c-1.3.2-1.8.8-1.9 1.3c-.1.7.4 1.3 1.3.6c1.1-1 3-.4 3.3-.6");
}

.stg138y3s {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M46.47 43c-.2.4-.3.8-.6 1.2c-.8-.2-1.7-.6-2.2-1.2c-.6-.8.1-1.3.8-.7c.5.3 1.3.6 2 .7");
}

.t2vt1xbzj {
  d: path("m45.03 59.55l-6.07-1.21L34.2 48.3l8.3 3.06z");
}

.t83l4yb_z {
  d: path("M103.4 47.8s-8-.8-11.9-6.9c-1.5-2.4-2.4-4.7-2.8-6.2c-.4-1.3-2.3-6.6-4.2-7.5c.1-.1 13.1 6.5 18.9 20.6");
}

.u3kz4vb7l {
  stop-color: var(--svg-color--530eeb, #530eeb);
}

.ul1ujbiao {
  fill: var(--svg-color--e53935, #e53935);
  d: path("m59.6 104.4l-6.4-2.1h-7.1s-2 2.2-2 4.1v2.8c0 .6.5 1.2 1.2 1.2l15.8.1c.6 0 1-.5 1-1v-1.3c.1-1.7-.9-3.2-2.5-3.8");
}

.uvqbgqb1h {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m45.1 96.9l1.3 6.9h6.9l.4-7.7z");
}

.uvwjpdf6c {
  d: path("M85.6 47.8c-1.2-1.3-3.1-1.8-4.8-1.4h-.3c-.07 0-.13.03-.2.1l-12.1 4.3c-1.8-.3-7.4-1.2-10.3-1.1c-1.1 0-4.3.4-4.4.4s-.2.1-.3.1l-3.4 3.1c-.7.5-.8 1.4-.4 2c.3.4.7.9 6.1-1.9q.75-.3 1.5 0l8.1 4c1.2.6 2.4.9 3.7.9c.5 0 1 0 1.6-.1L82.2 56c.4 0 .9-.1 1.3-.2c.07 0 .13-.03.2-.1c1.1-.4 2-1.2 2.6-2.3c1-1.8.7-4.1-.7-5.6");
}

.v08u51g1f {
  fill: var(--svg-color--91674d, #91674d);
  d: path("M56.5 51.7c0-.4-.1-.7-.4-1c-1.2-1-5.1-.3-5.9-.1l-2.8 1.1c-.4.2-1.2.7-1.1 1.5c0 .07.03.13.1.2c0 .1.5.7 1.8.7l7-.6c.8-.2 1.3-1 1.3-1.8");
}

.v21u60_1u {
  d: path("M99.4 33.8c-.6-5.8.8-10.7-5.4-13.6c-4.9-2.3-11.7 2.1-12.5 4c-1.6 3.7 3.5 4.5 5 5.5c2.1 1.5 12.9 4.1 12.9 4.1");
}

.v9ziyccwm {
  d: path("M15.91 33.5c.7-5.8-.6-10.7 5.7-13.4c5-2.2 11.6 2.4 12.4 4.3c1.5 3.7-3.6 4.4-5.1 5.4c-2.2 1.4-13 3.7-13 3.7");
}

.wdmqm4mmj {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M67.23 35.5c.5 1.2-1.7 3-1.7 4.5c0 1.1 2.4 1.3 2.6 1.4c.3.2.4.6.6 1.1c.2.4.3.8.5 1.2c.7 1.4 2.1 2.8 5.7 2.3c2.4-.3 2.6-.5 3.3-.6c1.5-.2 2.7 2 2.7 2s2.8 5.2 6.4 3.1c4.2-2.4 3.3-4.2 3.3-4.2s-4.8-6.9-3.5-11.4c1.2-4.3 1-11.3-1.2-13.4c-3.4-3.4-9.6-5.2-14-3.4c-5 2-6.9 6.4-6.6 11.2c.1 1.8.84 4.09 1.1 4.6c.25.51.8 1.3.8 1.6");
}

.x-ak-59mr {
  fill: var(--svg-color--543930, #543930);
  d: path("M29.71 18.3c2.9-2.4 6.9-3.4 10.9-2.7c3.4.6 7.9 2.5 10.2 6.1c1.3 2.2 1.9 4.7 1.1 7.3c-.5 1.5-1.9 2-1.9 2s-.7-3.9-4.3-3.8c-3.8.1-5.3-1-5.3-1c.6 3.3-.8 4.7-2 5.5c-.7.4-1.3.9-1.7 1.2c-.2.2-.3.1-.3-.1c0-.5-.1-1.5-.2-1.9c-.4-1.5-1.6-1.3-1.6-1.3c-1.6.2-2.8 3.2-.8 5.7c0 .1.2.2 0 .5c-1.6 3-5.3 2.3-5.5 2.1c-.4-.3-.6-.8-.6-1.4c.1-2.2-.6-3-1.1-4.1c-.5-1.2-1.1-2.6-.9-6.1c.2-3.3 1.6-6 4-8");
}

.x16mk-bfp {
  stop-color: var(--svg-color--a47b62, #a47b62);
}

.x20bfvbhy {
  fill: var(--svg-color--91674d, #91674d);
  d: path("M55.4 67.78c-.01.21-.17.22-.49.21s-3.5-.11-5.06-.9c.18-.02.28-.02.43-.02c1.87.35 3.31.43 4.64.47c.3.01.49.04.48.24m-5.09 1.52c1.75.61 4.59.63 4.92.61c.27-.02.34-.12.34-.32c0-.1-.1-.2-.3-.2c-1.5.1-3.3 0-4.8-.2zm5.56 2.19c0 .1-.04.28-.34.29c-1.47.07-2.99-.22-4.09-.42c0 0 .48-.16.55-.16s2.39.23 3.39.13c.25-.03.49-.04.49.16");
}

.x3tflxbpz {
  d: path("M82.2 106.4c0-1.9-2-4.1-2-4.1h-7.1l-6.4 2.1c-1.5.6-2.6 2.1-2.6 3.8v1.3c0 .6.4 1 1 1l15.8-.1c.6 0 1.2-.5 1.2-1.2z");
}

.xb94qyb-t {
  stop-color: var(--svg-color--651fff, #651fff);
}

.xg38eubmv {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M42.27 33.1c-.2-.1-.1-.5.3-.8c.5-.3 1.2-.7 2.4-.5c1.3.3 1.8.8 1.8 1.4c.1.7-.4 1.2-1.3.5c-1-.9-2.9-.4-3.2-.6");
}

.xgj2_40uc {
  d: path("M89.3 51.1c-.16-1.4-.7-2.5-1.7-3.3s-2.3-1.2-3.6-1.2c-1.5.1-3.06 1.09-3.7 2.2c-.36.61-5.9 11.3-5.9 11.3s-10.25 3.58-11.57 3.91c-1.33.33-3.03-.11-3.73-.41c-1.83-.61-2.18-.74-3.16-.73c-.87.02-1.1.44-1.12.72c-.03.27.03.47.18.71c.35.56 2.1 1.3 2.1 1.3c-.7.1-1.5.1-1.9.1c-.3 0-1.1-.1-1.8-.2c-1.32-.15-2.46-.25-3.12-.05c-.55.17-.59.68-.54.94c.07.37.35.57.55.67c-.2 0-.56-.01-.94.18c-.38.2-.38.54-.35.75c.06.42.69.96 1.5 1.2c0 0-.3.12-.44.31c-.13.17-.16.3-.16.49c0 .73.83 1.08 1.83 1.18l.27.03c-.64.16-1.22.29-1.2.9s.8 1.31 3.2 1.2c1.7-.08 3.02-.12 5.99-.71S77.1 67.3 77.9 67s1.85-.8 2.78-1.96c.65-.81 7.3-9.99 7.78-10.68c.77-1.14.96-2.19.84-3.26");
}

.xpwmi9bxi {
  stop-color: var(--svg-color--ea4643, #ea4643);
}

.ygm_dez4e {
  stop-color: var(--svg-color--ba8d68, #ba8d68);
}

</style>
