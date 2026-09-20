<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="huz3xb-7n"/><linearGradient id="SVGWoItueDl" x1="25.87" x2="53.21" y1="45.3" y2="45.3" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ms-lo7bhi"/><stop offset="1" class="gg42svbns"/></linearGradient><path fill="url(#SVGWoItueDl)" class="e7p1a9b-n"/><path class="fk6cadm2d"/><linearGradient id="SVG0t4y4rPb" x1="10.42" x2="36.071" y1="44.65" y2="44.65" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ms-lo7bhi"/><stop offset="1" class="gg42svbns"/></linearGradient><path fill="url(#SVG0t4y4rPb)" class="nc1qd5b_i"/><path class="klyrfy40m"/><path class="psdkbcmoz"/><path class="wxbak8lid"/><path class="hskhyxbuu"/><path class="yngey2gke"/><radialGradient id="SVGWLcwucyX" cx="-952.686" cy="627.614" r="1" gradientTransform="rotate(-173.183 -7481.68 -5520.813)scale(16.3827 -16.1583)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGWLcwucyX)" class="dl-8ddbqt"/><path class="l9fpjpbnq"/><linearGradient id="SVGD1gQrLUY" x1="31.509" x2="68.407" y1="76.026" y2="76.026" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="gg42svbns"/><stop offset="1" class="ms-lo7bhi"/></linearGradient><path fill="url(#SVGD1gQrLUY)" class="oqks-vpxu"/><linearGradient id="SVGXvLC7cnQ" x1="56.538" x2="58.476" y1="73.426" y2="75.364" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="jdm0k360m"/><stop offset="1" class="ms-lo7bhi"/></linearGradient><path fill="url(#SVGXvLC7cnQ)" class="fuo1u-krl"/><linearGradient id="SVGeXieF7fi" x1="43.891" x2="38.797" y1="77.695" y2="75.767" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="jdm0k360m"/><stop offset="1" class="ms-lo7bhi"/></linearGradient><path fill="url(#SVGeXieF7fi)" class="t2vt1xbzj"/><radialGradient id="SVG48ytncGN" cx="-840.091" cy="575.859" r="1" gradientTransform="matrix(16.2998 0 0 -16.2998 13720.296 9451.03)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="o_4j53rwc"/><stop offset=".563" class="wkjr7927g"/><stop offset=".983" class="b5pelhk-b"/></radialGradient><path fill="url(#SVG48ytncGN)" class="i8p85dbjh"/><linearGradient id="SVGyp4dGcRI" x1="31.564" x2="51.564" y1="84.635" y2="63.426" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="gg42svbns"/><stop offset="1" class="ms-lo7bhi"/></linearGradient><path fill="url(#SVGyp4dGcRI)" class="lr5iu3b5b"/><path class="uvqbgqb1h"/><path class="uoho8pb9q"/><path class="i9lgkq9yx"/><path class="e1ppjnbry"/><linearGradient id="SVGjJGJbe8U" x1="86.659" x2="51.997" y1="77.716" y2="77.716" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".599" class="tisq54bqj"/><stop offset="1" class="asbw0jbgl"/></linearGradient><path fill="url(#SVGjJGJbe8U)" class="vl-hl1kok"/><linearGradient id="SVG5rtlNcXV" x1="65.47" x2="94.2" y1="44" y2="44" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset="1" class="tisq54bqj"/></linearGradient><path fill="url(#SVG5rtlNcXV)" class="zpt5fo_tq"/><path class="xoeeeb-wo"/><linearGradient id="SVGeoU5Fb6D" x1="107.687" x2="89.617" y1="36.347" y2="55.324" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset="1" class="tisq54bqj"/></linearGradient><path fill="url(#SVGeoU5Fb6D)" class="q8fo88sdw"/><path class="v_1p9j2jb"/><path class="grk8r7opl"/><path class="b-q6fybpu"/><path class="jo5s9gt1s"/><radialGradient id="SVGTPu9BbpY" cx="-842.403" cy="571.885" r="1" gradientTransform="rotate(176.118 7087.754 4398.698)scale(-16.3658 16.141)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGTPu9BbpY)" class="lct5jdxum"/><radialGradient id="SVGitAU0KBj" cx="-840.85" cy="576.261" r="1" gradientTransform="matrix(16.5281 0 0 -16.5281 13985.658 9582.847)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zs84mcc3v"/><stop offset=".705" class="fwmih7b7q"/><stop offset="1" class="xv220cbff"/></radialGradient><path fill="url(#SVGitAU0KBj)" class="htsznfbzh"/><linearGradient id="SVGJRmQi9Xv" x1="61.134" x2="83.93" y1="61.324" y2="78.91" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".599" class="tisq54bqj"/><stop offset="1" class="asbw0jbgl"/></linearGradient><path fill="url(#SVGJRmQi9Xv)" class="xgj2_40uc"/><path class="plh8wtq6k"/><path class="xtf4ndbhk"/><radialGradient id="SVGSX3mrcTU" cx="-767.605" cy="537.388" r="1" gradientTransform="matrix(7.0254 0 0 -7.0254 5465.883 3881.767)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xv220cbff"/><stop offset="1" class="xv220cbff"/></radialGradient><path fill="url(#SVGSX3mrcTU)" class="x3tflxbpz"/><path class="n_fw6snrv"/><radialGradient id="SVGceJinpoQ" cx="-775.537" cy="541.598" r="1" gradientTransform="matrix(7.4919 0 0 -7.4919 5929.79 4156.376)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xv220cbff"/><stop offset="1" class="xv220cbff"/></radialGradient><path fill="url(#SVGceJinpoQ)" class="q3k8qyuqq"/><path class="ogfp9kbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:men-wrestling-medium-light-skin-tone-medium-dark-skin-tone" /></template>
<style>
.asbw0jbgl {
  stop-color: var(--svg-color--8d5738, #8d5738);
}

.atqdr-9uk {
  stop-color: var(--svg-color--bfa055, #bfa055);
}

.b-q6fybpu {
  fill: var(--svg-color--42312c, #42312c);
  d: path("M71.38 36.86c.59-.14.9-.99.69-1.9c-.21-.92-.86-1.55-1.45-1.41s-.9.99-.69 1.9s.86 1.54 1.45 1.41M69.8 33c-.9.7-1.4.1-1.3-.6c.1-.5.6-1.1 1.9-1.3c1.2-.2 1.9.3 2.4.6s.6.7.3.8c-.3.3-2.2-.3-3.3.5");
}

.b5pelhk-b {
  stop-color: var(--svg-color--ef6c00, #ef6c00);
}

.dl-8ddbqt {
  d: path("M29.6 18.8c2.9-2.2 7.5-3 11.5-2.3c2.7.5 5.1 1.6 7 3.2c0 0 3.7 3.1 4.1 5.3c.5 2.4-.7 3.4-1 3.6c-.4.3-1.2 0-1.2 0c-1.5-.5-6.4-2.1-9-2.2c-.4 0-.9 0-1.2.3c-.1.1-.4 1.1-.5 1.3c-.7 2.2-.9 3.7-2 4.9c-.2.2-.7.4-.7.4l-.6-1.7c-.4-1-.7-1.8-1.5-1.8c-2.3-.1-3 3.9-.7 5.5c0 0-1.3 3-4.2 2.8c-2.6-.2-2.8-.8-2.8-1.8c0-2.2-.3-3.2-.7-4.3c-.4-1.3-.94-2.63-.6-5.7s1.7-5.6 4.1-7.5");
}

.e1ppjnbry {
  fill: var(--svg-color--fb8c00, #fb8c00);
  d: path("M11.8 92s-.5-.1-1.2-.1c-.9 0-2 .1-3 .4l-2.7.8c-.6.2-1 .8-.8 1.5l4.7 15.1c.1.4.5.7 1 .7c.1 0 .2 0 .3-.1l1.2-.4c1.6-.5 2.7-1.9 2.8-3.6l.1-6.7z");
}

.e7p1a9b-n {
  d: path("M47.6 75c-2.3-1.2-19-7.9-19-7.9l-2.7 11.4s11.9 4.1 16.1 5.7c.7.3 1.2.9 1.4 1.7l3.2 16.4h6.3s.3-12.3.3-17.3c0-6.5-2.7-8.5-5.6-10");
}

.fk6cadm2d {
  fill: var(--svg-color--e65100, #e65100);
  d: path("M29.5 66.2c-.9-.3-1.7-.4-2.6-.4c-3 0-5.8 1.8-6.9 4.8c-1.4 3.8.5 8.1 4.4 9.5l9.2 3.4l5.1-13.9z");
}

.fuo1u-krl {
  d: path("M63.03 55.49c-.8.3-4.93 1.61-5.23 1.71c-1.8-.9-4-3.3-4-3.3l3.5-2.1z");
}

.fwmih7b7q {
  stop-color: var(--svg-color--00b29a, #00b29a);
}

.gg42svbns {
  stop-color: var(--svg-color--e0bb95, #e0bb95);
}

.grk8r7opl {
  fill: var(--svg-color--473530, #473530);
  d: path("M71.2 42.4c-.6.6-1.4 1-2.3 1.1c-.2-.4-.4-.8-.5-1.2c.7 0 1.5-.3 1.9-.6c.9-.6 1.5 0 .9.7");
}

.hskhyxbuu {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M42.4 33.1c-.2-.1-.1-.5.3-.8c.5-.3 1.2-.7 2.4-.5c1.3.3 1.8.8 1.8 1.4c.1.7-.4 1.2-1.3.5c-1-.9-2.9-.4-3.2-.6");
}

.htsznfbzh {
  d: path("M97.5 71.8c.3-.8.4-1.8.4-2.8c.2-5.9-1-12-3.7-17.8c-.9-2-3.1-6.8-8.2-6.8h-.8c-6.6.6-7.5 6.4-6.5 11.1c1.4 6.7 2.4 10.3 2.7 16.6c.1 2.1.9 4.5 2.5 5.4c.7 2.5 2.3 6 3.9 8.3c4.1-1.5 8.1-3.1 12.1-4.9c-.8-2.8-2.4-9.1-2.4-9.1");
}

.huz3xb-7n {
  fill: var(--svg-color--875334, #875334);
  d: path("M56.5 51.7c0-.4-2.11-1.36-2.41-1.66c-.84.06-3.07.24-3.89.56c-.82.31-2.8 1.1-2.8 1.1c-.4.2-1.1.58-1.1 1.5c0 .59.53.9 1.9.9s7-.6 7-.6c.8-.2 1.3-1 1.3-1.8");
}

.i8p85dbjh {
  d: path("M36 55.1c1.9-4.4 1.1-7.6-.1-8.7c-2-1.9-4.53-2.4-6.1-2.4c-3.66 0-6.6 2.8-8.7 7.2c-2.8 5.8-4.4 12.8-4.4 18.7c0 5.4 5.2 12.9 6.5 15.5c4-1.7 7.9-3.4 11.8-5.4c-.4-1.1-1.1-2.7-1.9-4.4c.3-.8.5-1.7.5-2.6c.6-5.5.2-11.9 2.4-17.9");
}

.i9lgkq9yx {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m16.7 89l-7.6 4.2l2.5 8l8.6-3.4z");
}

.jdm0k360m {
  stop-color: var(--svg-color--e0bb95, #e0bb95);
  stop-opacity: 0;
}

.jo5s9gt1s {
  fill: var(--svg-color--3c2c23, #3c2c23);
  d: path("M86.6 19c-2.8-2.4-7.3-3.4-11.3-2.9c-2.7.4-5.2 1.4-7.2 2.8c0 0-3.8 2.9-4.4 5.1c-.6 2.4.6 3.4.8 3.6c.4.3 1.2 0 1.2 0c1.5-.4 6.5-1.7 9.1-1.7c.4 0 .9 0 1.1.4c.1.1.4 1.1.4 1.3c.6 2.2.7 3.7 1.7 5c.2.2.7.4.7.4l.6-1.6c.4-.9.8-1.8 1.6-1.8c2.3 0 2.8 4 .4 5.5c0 0 1.1 3 4.1 3c2.6 0 2.8-.7 2.9-1.7c.1-2.2.5-3.2.9-4.2c.5-1.3.9-2.41.9-5.7c0-3.39-1.2-5.5-3.5-7.5");
}

.klyrfy40m {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M48.3 36c-.2.85 1.75 3.47 1.6 4.5c-.18 1.27-1.93 1.24-2.32 1.34s-.78.66-.98 1.16c-.2.4-.3.8-.6 1.2c-.8 1.4-2.2 2.8-5.7 2.2c-2.3-.4-2.5-.5-3.3-.6c-1.5-.2-2.7 2-2.7 2s-2.9 5.2-6.5 3c-4.2-2.5-3.07-4.66-3.07-4.66s3.87-4.84 2.67-9.34c-1.1-4.3.3-12.9 2.5-15c3.4-3.3 9.7-5 14.1-3.1c4.9 2.1 6.7 6.5 6.3 11.4c-.2 1.8-.6 3.12-.89 3.79c-.28.66-.91 1.26-1.11 2.11");
}

.l1arbqe-k {
  stop-color: var(--svg-color--bfa055, #bfa055);
  stop-opacity: 0;
}

.l9fpjpbnq {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M75.1 48.7c-.68-.11-2.07-.17-3.1-.2c-.68-.02-5.5.98-5.5 2c0 2.1.85 2.43 1.8 2.3c0 0 6.21-1.42 6.9-1.6s1.42-.56 1.4-1.4c-.01-.58-.82-.99-1.5-1.1");
}

.lct5jdxum {
  d: path("M86.6 19c-2.8-2.4-7.3-3.4-11.3-2.9c-2.7.4-5.2 1.4-7.2 2.8c0 0-3.8 2.9-4.4 5.1c-.6 2.4.6 3.4.8 3.6c.4.3 1.2 0 1.2 0c1.5-.4 6.5-1.7 9.1-1.7c.4 0 .9 0 1.1.4c.1.1.4 1.1.4 1.3c.6 2.2.7 3.7 1.7 5c.2.2.7.4.7.4l.6-1.6c.4-.9.8-1.8 1.6-1.8c2.3 0 2.8 4 .4 5.5c0 0 1.1 3 4.1 3c2.6 0 2.8-.7 2.9-1.7c.1-2.2.44-3.17.83-4.12c.44-1.07 1.01-2.7.97-5.78c-.04-3.09-1.2-5.5-3.5-7.5");
}

.lr5iu3b5b {
  d: path("M67.03 67.51c-.13-.16-.53-.31-1.03-.31c.2-.1.7-.46.5-1.2c-.3-.8-1.7-.7-3.5-.4c-.7.1-1.5.2-1.9.2c-.3 0-1.1 0-1.8-.1h.1c.8-.3 1.33-.71 1.75-1.07c.48-.4.52-.78.45-1.02c-.22-.7-1.09-.78-2.02-.62c-.77.13-1.73.45-2.29.71c-.7.3-2.91.68-3.93.43c-.9-.22-8.5-2.77-9.67-3.23s-1.96-1.06-2.56-2.16c0 0-4.72-8.83-5.24-9.74c-.86-1.48-2.7-2.4-4.5-2.2c-2 .1-3.8 1.6-4.4 3.6c-.3 1.2-.24 2.37.4 3.5s6.6 10.3 6.6 10.3c1.1 1.8 2.8 3 4.8 3.6l14.6 4.1h.2c.7.3 1.5.5 2.4.8l.6.2c1.7.4 3.7.8 5.5.8c1.7 0 3.16-.33 3.2-1.3c.02-.44-.5-.7-1.2-.8c1.1-.1 2.12-.56 2.11-1.17s-.41-.83-.61-.83c.8-.2 1.62-.66 1.69-1.32c.04-.31-.13-.61-.25-.77");
}

.m_5onzv2u {
  stop-color: var(--svg-color--554138, #554138);
}

.mlb8vsb9l {
  stop-color: var(--svg-color--554138, #554138);
  stop-opacity: 0;
}

.ms-lo7bhi {
  stop-color: var(--svg-color--cca47a, #cca47a);
}

.n_fw6snrv {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m110.8 88.1l-3.3 8.2l9.2 2l2.2-6.9z");
}

.nc1qd5b_i {
  d: path("m35.5 83.3l-4.9-12.1l-10.9 4.4l4.2 8.7c.5.8.2 1.7-.6 2.1l-13 6.8l3.1 6.3l18.1-7.2c3.8-1.3 5.5-5.4 4-9");
}

.o_4j53rwc {
  stop-color: var(--svg-color--fb8c00, #fb8c00);
}

.ogfp9kbvc {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M72.7 50.2s-6.43-1.9-8.53 0c0 0 5.35 1.96 6.03 2.2c.69.23 3.31.62 3.7-.7c.29-.98-.7-1.3-1.2-1.5");
}

.oqks-vpxu {
  d: path("M68.4 52.56c0 1-4.55 2.69-9 4.14s-10.44 2.76-11.38 2.88c-1.45.18-2.13.14-3.44-.12c-1.34-.27-5.78-1.16-5.78-1.16l-7.4-1.5l2.57-8.54L46.7 52.8c2.1-.3 16.8-2.5 18.3-2.5c2.2 0 3.4.55 3.4 2.26");
}

.plh8wtq6k {
  fill: var(--svg-color--875334, #875334);
  d: path("M55.4 67.78c-.01.21-.17.22-.49.21s-3.5-.11-5.06-.9c.18-.02.28-.02.43-.02c1.87.35 3.31.43 4.64.47c.3.01.49.04.48.24m-5.09 1.52c1.75.61 4.59.63 4.92.61c.27-.02.34-.12.34-.32c0-.1-.1-.2-.3-.2c-1.5.1-3.3 0-4.8-.2zm5.56 2.19c0 .1-.04.28-.34.29c-1.47.07-2.99-.22-4.09-.42c0 0 .48-.16.55-.16s2.39.23 3.39.13c.25-.03.49-.04.49.16");
}

.psdkbcmoz {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M46.6 43c-.2.4-.3.8-.6 1.2c-.8-.2-1.7-.6-2.2-1.2c-.6-.8.05-1.24.72-.81c.73.47 1.38.71 2.08.81");
}

.q3k8qyuqq {
  d: path("m123.8 90.7l-2.7-.8c-1-.3-2.1-.4-3-.4c-.7 0-1.2.1-1.2.1l-2.4 7.7l.1 6.7c.1 1.7 1.2 3.1 2.8 3.6c0 0 1.4.5 1.5.5c.4 0 .8-.3 1-.7l4.7-15.1c.2-.7-.2-1.4-.8-1.6");
}

.q8fo88sdw {
  d: path("m100.1 85.3l-5.6-20.7L82.3 69s7.44 18.98 8.5 21.4s2.15 3.1 4.6 3.5c1.42.23 20.3 2.8 20.3 2.8l2.2-5.2z");
}

.t2vt1xbzj {
  d: path("m45.03 59.55l-6.07-1.21L34.2 48.3l8.3 3.06z");
}

.tisq54bqj {
  stop-color: var(--svg-color--a56c43, #a56c43);
}

.uoho8pb9q {
  fill: var(--svg-color--fb8c00, #fb8c00);
  d: path("m59.6 104.4l-6.4-2.1h-7.1s-2 2.2-2 4.1v2.8c0 .6.5 1.2 1.2 1.2l15.8.1c.6 0 1-.5 1-1v-1.3c.1-1.7-.9-3.2-2.5-3.8");
}

.uvqbgqb1h {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m45.1 96.9l1.3 6.9h6.9l.4-7.7z");
}

.v_1p9j2jb {
  fill: var(--svg-color--a56c43, #a56c43);
  d: path("M86.8 50.9c-3.8 2-6.4-3.3-6.4-3.3s-1.1-2.3-2.6-2.1c-.7.1-.9.2-3.3.5c-3.6.4-4.9-1-5.6-2.5c-.2-.4-.4-.8-.5-1.2c-.2-.5-.4-1-.6-1.2s-2.6-.4-2.5-1.5c0-1.5 2.2-3.2 1.8-4.5c-.1-.3-.37-.98-.6-1.5c-.47-1.07-.9-2.9-1-4.6c-.2-4.9 1.9-9.1 6.9-11c4.5-1.7 10.7.3 13.9 3.8c2.1 2.2 2.22 10.01 1.41 15.64c-.79 5.47 2.2 8.32 2.2 8.32s1.19 2.84-3.11 5.14");
}

.vl-hl1kok {
  d: path("M85.6 47.8c-1.2-1.3-3.1-1.8-4.8-1.4c-1.16.23-12.6 4.4-12.6 4.4c-1.8-.3-7.4-1.2-10.3-1.1c-1.1 0-3.63.31-4.09.36s-.78.3-1.17.65c-.38.35-2.35 2.13-2.84 2.59c-.36.33-.7.94-.58 1.45c.13.54.32.77.81.82c.58.06 1.75-.24 5.47-2.17q.75-.3 1.5 0s6.68 3.26 8.1 4s3.28 1.09 5.3.8s12.24-2.27 13.3-2.5s3.26-1.16 3.26-4.16c0-.79.04-2.24-1.36-3.74");
}

.wkjr7927g {
  stop-color: var(--svg-color--f67f00, #f67f00);
}

.wxbak8lid {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M45.44 35.95c.26-.9-.01-1.77-.59-1.94s-1.27.43-1.52 1.33c-.26.9.01 1.77.59 1.94c.59.17 1.27-.43 1.52-1.33");
}

.x3tflxbpz {
  d: path("M82.2 106.4c0-1.9-2-4.1-2-4.1h-7.1l-6.4 2.1c-1.5.6-2.6 2.1-2.6 3.8v1.3c0 .6.4 1 1 1l15.8-.1c.6 0 1.2-.5 1.2-1.2z");
}

.xgj2_40uc {
  d: path("M89.3 51.1c-.16-1.4-.7-2.5-1.7-3.3s-2.3-1.2-3.6-1.2c-1.5.1-3.06 1.09-3.7 2.2c-.36.61-5.9 11.3-5.9 11.3s-10.25 3.58-11.57 3.91c-1.33.33-3.03-.11-3.73-.41c-1.83-.61-2.18-.74-3.16-.73c-.87.02-1.1.44-1.12.72c-.03.27.03.47.18.71c.35.56 2.1 1.3 2.1 1.3c-.7.1-1.5.1-1.9.1c-.3 0-1.1-.1-1.8-.2c-1.32-.15-2.46-.25-3.12-.05c-.55.17-.59.68-.54.94c.07.37.35.57.55.67c-.2 0-.56-.01-.94.18c-.38.2-.38.54-.35.75c.06.42.69.96 1.5 1.2c0 0-.3.12-.44.31c-.13.17-.16.3-.16.49c0 .73.83 1.08 1.83 1.18l.27.03c-.64.16-1.22.29-1.2.9s.8 1.31 3.2 1.2c1.7-.08 3.02-.12 5.99-.71S77.1 67.3 77.9 67s1.85-.8 2.78-1.96c.65-.81 7.3-9.99 7.78-10.68c.77-1.14.96-2.19.84-3.26");
}

.xoeeeb-wo {
  fill: var(--svg-color--04846c, #04846c);
  d: path("M93.4 72.8c-1.2-2.3-3.6-3.7-6-3.7c-1.1 0-2.1.2-3.1.8L75 74.7l6.3 12.1l9.2-4.8c3.3-1.7 4.6-5.8 2.9-9.2");
}

.xtf4ndbhk {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M78.7 96.7L70 98.6l3.3 5.9l7.4-.7z");
}

.xv220cbff {
  stop-color: var(--svg-color--00ab94, #00ab94);
}

.yngey2gke {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M29.6 18.8c2.9-2.2 7.5-3 11.5-2.3c2.7.5 5.1 1.6 7 3.2c0 0 3.7 3.1 4.1 5.3c.5 2.4-.7 3.4-1 3.6c-.4.3-1.2 0-1.2 0c-1.5-.5-6.4-2.1-9-2.2c-.4 0-.9 0-1.2.3c-.1.1-.4 1.1-.5 1.3c-.7 2.2-.9 3.7-2 4.9c-.2.2-.7.4-.7.4l-.6-1.7c-.4-1-.7-1.8-1.5-1.8c-2.3-.1-3 3.9-.7 5.5c0 0-1.3 3-4.2 2.8c-2.6-.2-2.8-.8-2.8-1.8c0-2.2-.3-3.2-.7-4.3c-.4-1.3-.9-2.6-.6-5.7c.3-3 1.7-5.6 4.1-7.5");
}

.zpt5fo_tq {
  d: path("m94.2 79.3l-4.7-11l-20.3 11c-3.1 1.7-4.7 5.3-3.1 9.3c1.7 4.2 7.1 15.1 7.1 15.1l6.6-1.3l-4.4-14.8z");
}

.zs84mcc3v {
  stop-color: var(--svg-color--00bfa5, #00bfa5);
}

</style>
