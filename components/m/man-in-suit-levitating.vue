<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGFGXeCbDf" cx="63.999" cy="8.016" r="15.202" gradientTransform="matrix(1 0 0 -.305 0 122.44)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="xred8dbeu"/><stop offset=".872" class="r9z4lqb_z"/></radialGradient><path fill="url(#SVGFGXeCbDf)" class="aq57zxxfg"/><path class="l75h81--u"/><radialGradient id="SVG4cHaVdVa" cx="108.979" cy="96.368" r="8.369" gradientTransform="matrix(1 0 0 .5046 -39.736 -17.129)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVG4cHaVdVa)" class="uai_s6b2j"/><radialGradient id="SVGN6WZObzV" cx="100.736" cy="97.613" r="2.473" gradientTransform="matrix(-.9057 .4354 -.3144 -.6903 199.416 53.745)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGN6WZObzV)" class="bc5vu2b3v"/><radialGradient id="SVGZgG24ctK" cx="107.146" cy="104.609" r="10.864" gradientTransform="matrix(-.0746 -1.0244 .8311 -.0639 -7.87 139.48)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGZgG24ctK)" class="zocrpacvk"/><radialGradient id="SVGI9i3Beea" cx="56.994" cy="104.609" r="10.864" gradientTransform="matrix(.0746 -1.0244 -.8311 -.0639 139.682 88.103)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGI9i3Beea)" class="r0lnctd1m"/><radialGradient id="SVGmTo2Qbfn" cx="58.827" cy="96.368" r="8.369" gradientTransform="matrix(-1 0 0 .5046 117.654 -17.129)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGmTo2Qbfn)" class="cii0vsbwy"/><radialGradient id="SVG0nk1ij7F" cx="50.584" cy="97.613" r="2.473" gradientTransform="matrix(.9057 .4354 .3144 -.6903 -25.922 75.58)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVG0nk1ij7F)" class="nbbmphbjg"/><path class="n691qgb_g"/><linearGradient id="SVGFS2pNezv" x1="51.934" x2="51.934" y1="58.604" y2="47.957" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sc9knx3mp"/><stop offset=".5" class="kp5kqybdr"/></linearGradient><path fill="url(#SVGFS2pNezv)" class="iv-irfjfm"/><linearGradient id="SVGVXpZndJV" x1="76.066" x2="76.066" y1="58.947" y2="48.3" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sc9knx3mp"/><stop offset=".5" class="kp5kqybdr"/></linearGradient><path fill="url(#SVGVXpZndJV)" class="ew3gyjbtr"/><linearGradient id="SVGa8mPxbUH" x1="60.598" x2="60.598" y1="27.572" y2="16.206" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset=".788" class="aplh-7tkj"/></linearGradient><path fill="url(#SVGa8mPxbUH)" class="s9huv2cyb"/><linearGradient id="SVGxn3LZcnq" x1="60.692" x2="60.692" y1="27.328" y2="20.476" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="ip0ngccya"/><stop offset=".721" class="rwhk7-m5g"/></linearGradient><path fill="url(#SVGxn3LZcnq)" class="fac-s44mn"/><linearGradient id="SVG1XGs9dGK" x1="67.246" x2="67.246" y1="27.572" y2="16.206" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset=".788" class="aplh-7tkj"/></linearGradient><path fill="url(#SVG1XGs9dGK)" class="jh_ykc85b"/><linearGradient id="SVGKG0ARdrm" x1="67.153" x2="67.153" y1="27.328" y2="20.476" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="ip0ngccya"/><stop offset=".721" class="rwhk7-m5g"/></linearGradient><path fill="url(#SVGKG0ARdrm)" class="eejnxd2tg"/><linearGradient id="SVGj28bqdhO" x1="63.983" x2="63.983" y1="63.365" y2="29.361" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset=".878" class="aplh-7tkj"/></linearGradient><path fill="url(#SVGj28bqdhO)" class="dskh23baw"/><linearGradient id="SVGDP1lFrGw" x1="63.913" x2="63.913" y1="27.046" y2="56.135" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ot05wr4_j"/><stop offset=".754" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGDP1lFrGw)" class="t_9dekbkt"/><path class="g_2k82bde"/><linearGradient id="SVGuXXvLesJ" x1="64" x2="64" y1="88.573" y2="50.663" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="jqhqmlbkz"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGuXXvLesJ)" class="vr_h_jaek"/><path class="mh3r0qdmm"/><path class="y22z2vbmb"/><path class="rrau8dcns"/><path class="mf9q5zmxw"/><path class="cg2xhgf-m"/><linearGradient id="SVGb8OdueQF" x1="57.675" x2="57.675" y1="98.896" y2="72.53" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="aplh-7tkj"/><stop offset=".836" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGb8OdueQF)" class="c-p3qfmrl"/><linearGradient id="SVGuQ7RjeIB" x1="70.371" x2="70.371" y1="98.903" y2="72.508" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="aplh-7tkj"/><stop offset=".836" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGuQ7RjeIB)" class="b9y2ocbcl"/><linearGradient id="SVGkyc4icwc" x1="52.771" x2="52.771" y1="63.481" y2="81.395" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ot05wr4_j"/><stop offset=".754" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGkyc4icwc)" class="chv93m2ji"/><linearGradient id="SVGtcdEMc8o" x1="75.315" x2="75.315" y1="63.493" y2="81.394" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ot05wr4_j"/><stop offset=".754" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGtcdEMc8o)" class="fhu_w0fvo"/><circle class="l2gdxtxzi"/><path class="cxj09i95n"/><path class="m8_ddz6dh"/><path class="grjhh0fvp"/><path class="wuu8b5bxy"/><path class="gd-67-bxm"/><path class="gpw7pvbbk"/><linearGradient id="SVGlzzu3dKW" x1="64" x2="64" y1="125.338" y2="106.08" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="jqhqmlbkz"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGlzzu3dKW)" class="x4zawkdgt"/><linearGradient id="SVG9bBOx3Yi" x1="64.002" x2="64.002" y1="106.736" y2="97.714" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".005" class="aplh-7tkj"/><stop offset=".4" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVG9bBOx3Yi)" class="eo8927bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:man-in-suit-levitating" /></template>
<style>
.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.aq57zxxfg {
  d: path("M79.3 120c0 2.21-6.85 4-15.3 4s-15.3-1.79-15.3-4s6.85-4.01 15.3-4.01s15.3 1.79 15.3 4.01");
}

.b9y2ocbcl {
  d: path("m75.36 36.85l-2 3.65l3.4.44l-12.77 18.18v-4l6.33-19.49z");
}

.bc5vu2b3v {
  d: path("M75.14 31.87C73.61 29.48 77 28.59 77 28.59c-.59.75-.86 1.41-.51 2.06c.43.81 1.72.93 1.72.93s-1.75 1.6-3.07.29");
}

.c-p3qfmrl {
  d: path("m52.74 36.85l2.01 3.65l-3.4.44L64 59.09l-.01-4l-6.21-19.46z");
}

.cg2xhgf-m {
  fill: var(--svg-color--d32f2f, #d32f2f);
  d: path("M74.39 50.92h-5.15v-.63l2.58-2.02l2.57 2.02z");
}

.chv93m2ji {
  d: path("m51.67 47.58l1.01 16.94h1.2l-.31-17.14c-.02-.33-.36-.83-1.06-.76c-.7.06-.89.63-.84.96");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cii0vsbwy {
  d: path("M64.04 36.51v-3.47l-10.21-.83l-.93 1.17s2.2 3.12 7.94 3.12z");
}

.cxj09i95n {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M73.68 21.3H54.32c-2.09 0-3.79 1.82-3.79 4.04s1.71 4.04 3.79 4.04h19.36c2.09 0 3.79-1.82 3.79-4.04s-1.7-4.04-3.79-4.04");
}

.dskh23baw {
  d: path("M69.66 101.96H58.29a2.02 2.02 0 0 1-2.01-1.83l-3.06-32.41h21.52l-3.07 32.41a2.006 2.006 0 0 1-2.01 1.83");
}

.eejnxd2tg {
  d: path("M64.81 105.25c.01 1.09.79 2.57 1.65 2.57c1.87 0 2.82-4.13 2.95-5.14s.13-2.2.13-2.2l-4.77-.01z");
}

.eo8927bvy {
  d: path("m75.65 22.12l-.26-.06c-1.66-.39-3.35-.58-5.04-.58c-.63 0-1.67.15-2.72.33c-2.38.42-4.82.42-7.19 0c-1.07-.19-2.12-.34-2.76-.34c-1.7 0-3.39.2-5.05.58l-.26.06c-.21.05-.38.23-.38.43v1.08c0 .27.27.48.56.44l.44 2.77c.29 1.89 1.94 3.58 4.75 3.58c2.91 0 4.36-2.67 5.05-4.9c.17-.53.66-.9 1.22-.9h.02c.56 0 1.05.37 1.22.9c.7 2.23 2.14 4.9 5.05 4.9c2.81 0 4.46-1.69 4.75-3.58l.42-2.77c.28.03.54-.17.54-.44v-1.08c.01-.19-.14-.37-.36-.42");
}

.ew3gyjbtr {
  d: path("M79.3 70.12a8 8 0 0 1-1.48 3.32c-1.26 1.67-3.59 1.54-4.45 1.56c-1.59.04-.9-4.07-.88-4.2c0 0 .34-6.45 4.58-6.45c1.73.04 3.01 1.62 2.69 3.32z");
}

.fac-s44mn {
  d: path("M63.04 105.25c-.01 1.09-.79 2.57-1.65 2.57c-1.87 0-2.83-4.13-2.95-5.14s-.13-2.2-.13-2.2l4.77-.01z");
}

.fhu_w0fvo {
  d: path("m76.38 47.58l-1.04 16.89l-1.1.04l.24-17.13c.02-.33.36-.83 1.06-.76c.7.06.89.63.84.96");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.g_2k82bde {
  fill: var(--svg-color--e5e5e5, #e5e5e5);
  d: path("M73.41 68.86h5.56c1.05 0 1.92-.8 2.01-1.84l.26-2.88h-7.83zm-18.53 0h-5.56c-1.05 0-1.92-.8-2.01-1.84l-.26-2.88h7.83z");
}

.gd-67-bxm {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M65.37 27.81c-.04-.01-.08-.02-.11-.03h-2.51c-.04 0-.08.01-.11.03a.42.42 0 0 0-.24.58c.11.25.61.95 1.61.95c1.01 0 1.5-.7 1.61-.95c.1-.25-.03-.48-.25-.58");
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.gpw7pvbbk {
  fill: var(--svg-color--543930, #543930);
  d: path("M75.36 27.16c-.02-.17 1.25-2.29 1.47-4.44c.08-.75.61-3.26.07-4.84C75.28 11.4 70.94 7.5 63.95 7.5c-7.34 0-11.85 3.9-13.09 10.88c0 1.29.55 3.27.55 3.27c-.22 3.85.99 5.71.99 5.71s1.51-6.61 1.37-7.62c0 0 2.78-.55 5.93-2.36c2.13-1.22 3.59-2.65 5.98-3.19c3.64-.82 4.46 1.82 4.46 1.82s3.37-.65 4.39 4.04c.42 1.93.6 5.15.83 7.11");
}

.grjhh0fvp {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M55.53 21.4c.7-1.06 2.2-1.42 3.38-1.18c.63.12 1.27.42 1.72.9c.38.41.57 1.16-.25 1.17c-.3.01-.64-.22-.92-.31c-.64-.19-1.33-.24-1.99-.13c-.32.05-.64.16-.95.26c-.23.08-.38.23-.64.17c-.36-.09-.58-.53-.35-.88m16.32.85c-.87-.46-1.95-.58-2.9-.37c-.46.1-2.46.93-1.74-.49c.58-1.14 2.45-1.41 3.52-1.15c.57.14 1.21.43 1.6.89c.38.42.36 1.46-.48 1.12");
}

.ip0ngccya {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
}

.iv-irfjfm {
  d: path("M48.7 70.12c.23 1.21.74 2.34 1.48 3.32c1.26 1.67 3.59 1.54 4.45 1.56c1.59.04.9-4.07.88-4.2c0 0-.34-6.45-4.58-6.45a2.802 2.802 0 0 0-2.69 3.32z");
}

.jh_ykc85b {
  d: path("M63.92 108.48c.01 1.54.19 3.64 2.34 3.64c2.66 0 4.01-5.86 4.19-7.31s.18-4.14.18-4.14l-6.77-.01z");
}

.jqhqmlbkz {
  stop-color: var(--svg-color--5f5f5f, #5f5f5f);
}

.kp5kqybdr {
  stop-color: var(--svg-color--ffca28, #ffca28);
}

.l2gdxtxzi {
  cx: 64.23px;
  cy: 63.24px;
  r: 2.02px;
  fill: var(--svg-color--212121, #212121);
}

.l75h81--u {
  fill: var(--svg-color--543930, #543930);
  d: path("M76.5 30.65c-.44-.83.12-1.68 1.09-2.73c1.54-1.67 3.21-5.53 1.66-9.46c.01-.02-.31-.68-.3-.7l-.64-.03c-.21-.03-7.24-.05-14.28-.05s-14.08.01-14.28.05c0 0-.95.72-.94.74c-1.56 3.92.12 7.79 1.66 9.46c.97 1.05 1.54 1.9 1.09 2.73c-.43.81-1.72.93-1.72.93s.3.83 1.01 1.28c.66.41 1.48.51 2.04.52c0 0 2.2 3.12 7.94 3.12h6.4c5.75 0 7.94-3.12 7.94-3.12c.56-.01 1.38-.11 2.04-.52c.72-.45 1.01-1.28 1.01-1.28s-1.29-.13-1.72-.94");
}

.m8_ddz6dh {
  fill: var(--svg-color--ffca28, #ffca28);
  d: path("M64 7c-6.17 0-11.88 6.59-11.88 16.08c0 9.44 5.88 14.1 11.88 14.1s11.88-4.67 11.88-14.1C75.88 13.59 70.17 7 64 7");
}

.mf9q5zmxw {
  fill: var(--svg-color--fff, #fff);
  d: path("m60.3 35.51l3.77 4.89l-3.73 3.25l-2.49-7.82zm7.42-.05l-3.65 4.94l3.67 3.22l2.56-7.83c-.92-.16-2.58-.33-2.58-.33");
}

.mh3r0qdmm {
  fill: var(--svg-color--e5e5e5, #e5e5e5);
  d: path("m68.62 50.48l-4.59 6.07l-4.11-6.07v-9h8.7z");
}

.n691qgb_g {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M64 35.85h-4.04v4.28c0 1.94 1.65 3.51 3.67 3.51h.73c2.03 0 3.68-1.57 3.68-3.51v-4.28z");
}

.nbbmphbjg {
  d: path("M52.93 31.87c1.53-2.39-1.86-3.28-1.86-3.28c.59.75.86 1.41.51 2.06c-.43.81-1.72.93-1.72.93s1.74 1.6 3.07.29");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.ot05wr4_j {
  stop-color: var(--svg-color--616161, #616161);
  stop-opacity: 0.2;
}

.r0lnctd1m {
  d: path("M48.81 18.46c-1.52 3.8.08 7.71 1.58 9.36c.21.23 1.08 1.1 1.27 1.81c0 0 3.41-4.89 4.43-7.76c.21-.58.39-1.18.42-1.79c.02-.46-.05-1.01-.31-1.4c-.32-.48-.69-.35-1.23-.35c-1.03 0-5.53-.27-5.88-.27c-.01 0-.28.4-.28.4");
}

.r9z4lqb_z {
  stop-color: var(--svg-color--616161, #616161);
  stop-opacity: 0;
}

.rrau8dcns {
  fill: var(--svg-color--d32f2f, #d32f2f);
  d: path("M65.2 43.88h-2.19l-.97-2.21l.41-1.28h3.3l.41 1.28z");
}

.rwhk7-m5g {
  stop-color: var(--svg-color--eee, #eee);
}

.s9huv2cyb {
  d: path("M63.93 108.48c-.01 1.54-.07 3.64-2.34 3.64c-2.66 0-4.01-5.86-4.19-7.31c-.18-1.44-.18-4.14-.18-4.14l6.77-.01z");
}

.sc9knx3mp {
  stop-color: var(--svg-color--ffb300, #ffb300);
}

.t_9dekbkt {
  d: path("M63.16 72.07c-.45.27-.72.77-.71 1.29l.95 27.58h1.19l.78-27.59c.01-.53-.26-1.02-.71-1.29h-.01c-.45-.26-1.03-.26-1.49.01");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uai_s6b2j {
  d: path("M64.03 36.51v-3.47l10.21-.83l.93 1.17s-2.2 3.12-7.94 3.12z");
}

.vr_h_jaek {
  d: path("M79.5 37.8s-5.95-1.74-11.75-2.33l-3.69 4.94l-3.77-4.89c-5.79.63-11.8 2.29-11.8 2.29c-2.73.74-3.82 3.37-3.49 7.42l1.87 20.27h6.12l.7 7.29h20.63l.7-7.29h6.12L83 45.22c.32-4.05-.76-6.68-3.5-7.42");
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.wuu8b5bxy {
  fill: var(--svg-color--795548, #795548);
  d: path("M66.98 31.15c-1.13.67-4.83.67-5.96 0c-.65-.39-1.31.2-1.04.79c.26.58 2.28 1.92 4.03 1.92s3.74-1.34 4-1.92c.27-.58-.38-1.17-1.03-.79");
}

.x4zawkdgt {
  d: path("M77.09 14.88s-1.24-7.34-2.68-8.99C72.98 4.26 67.37 4.01 64 4c-3.37.01-8.98.26-10.41 1.89c-1.45 1.65-2.68 8.99-2.68 8.99s-5.5 1.63-3.11 3.03c1.17.68 6.28 1.11 16.2 1.12c9.92-.01 15.03-.43 16.2-1.12c2.4-1.4-3.11-3.03-3.11-3.03");
}

.xred8dbeu {
  stop-color: var(--svg-color--504f4f, #504f4f);
  stop-opacity: 0.8;
}

.y22z2vbmb {
  fill: var(--svg-color--d32f2f, #d32f2f);
  d: path("m64.1 57.1l-2.34-3.89l1.25-9.41h2.19l1.25 9.4z");
}

.zocrpacvk {
  d: path("M79.26 18.46c1.52 3.8-.08 7.71-1.58 9.36c-.21.23-1.08 1.1-1.27 1.81c0 0-3.41-4.89-4.43-7.76c-.21-.58-.39-1.18-.42-1.79c-.02-.46.05-1.01.31-1.4c.32-.48 7.21-.62 7.21-.62z");
}

</style>
