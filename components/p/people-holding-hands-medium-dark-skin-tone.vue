<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGGobiEbDD" x1="48.373" x2="65.03" y1="56.744" y2="78.777" gradientTransform="rotate(170.984 58.25 .453)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".405" class="tisq54bqj"/></linearGradient><path fill="url(#SVGGobiEbDD)" class="ggzrctssn"/><linearGradient id="SVGtZ4EKzYl" x1="66.865" x2="70.29" y1="77.077" y2="71.48" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset="1" class="njynq2ywd"/></linearGradient><path fill="url(#SVGtZ4EKzYl)" class="kg8mw9bxw"/><path class="tajsh7foc"/><path class="wiau9ou2e"/><linearGradient id="SVGPXWSZerJ" x1="2029.735" x2="2010.276" y1="53.492" y2="86.593" gradientTransform="matrix(-1 0 0 1 2133.463 0)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".401" class="tisq54bqj"/></linearGradient><path fill="url(#SVGPXWSZerJ)" class="fu9bhttza"/><linearGradient id="SVG21rvvtxE" x1="2041.917" x2="2041.917" y1="43.814" y2="78" gradientTransform="matrix(-1 0 0 1 2133.463 0)" gradientUnits="userSpaceOnUse"><stop offset=".366" class="mujsf_8ht"/><stop offset=".672" class="nlb89objm"/><stop offset="1" class="b5pelhk-b"/></linearGradient><path fill="url(#SVG21rvvtxE)" class="hg-9rbldu"/><path class="z_tilxbde"/><radialGradient id="SVG2urYobQi" cx="80.384" cy="38.003" r="10.125" gradientTransform="matrix(1 0 0 -.4912 17.453 56.67)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVG2urYobQi)" class="n9zjxtbmn"/><radialGradient id="SVGnNN5DdOz" cx="70.412" cy="36.497" r="2.992" gradientTransform="rotate(154.924 82.042 8.87)scale(1 -.7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVGnNN5DdOz)" class="dhayusc9l"/><radialGradient id="SVGjocqsc4t" cx="78.166" cy="28.033" r="13.142" gradientTransform="matrix(-.0746 -.9972 -.8311 .0622 129.186 104.238)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGjocqsc4t)" class="hm_tflbqq"/><radialGradient id="SVG79jgVeJg" cx="83.02" cy="28.033" r="13.142" gradientTransform="matrix(.0746 -.9972 .8311 .0622 53.526 109.078)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVG79jgVeJg)" class="d55a2v9wg"/><radialGradient id="SVGXYbNKbTb" cx="85.237" cy="38.003" r="10.125" gradientTransform="matrix(-1 0 0 -.4912 170.475 56.67)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGXYbNKbTb)" class="aoitwmb8k"/><radialGradient id="SVG11J3gbea" cx="75.266" cy="36.497" r="2.992" gradientTransform="rotate(25.076 54.082 31.786)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVG11J3gbea)" class="l9h03nbew"/><path class="rnj6bzm1r"/><path class="topfecjbg"/><path class="tcjxzpbtc"/><radialGradient id="SVGwQT0wbRT" cx="99.323" cy="21.1" r="15.405" gradientTransform="matrix(.3076 .9515 -.706 .2282 83.667 -78.222)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGwQT0wbRT)" class="o0wapkbev"/><radialGradient id="SVG0rdwIbEs" cx="84.304" cy="4.303" r="4.039" gradientTransform="matrix(.8813 .4726 -.5603 1.045 12.419 -40.034)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVG0rdwIbEs)" class="bjtjsm2ge"/><radialGradient id="SVGk364lcNI" cx="138.141" cy="46.449" r="12.417" gradientTransform="matrix(-.9378 -.3944 .2182 -.5285 212.746 90.669)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGk364lcNI)" class="elbau5r8n"/><radialGradient id="SVGOSxTbdsf" cx="82.682" cy="7.988" r="3.707" gradientTransform="matrix(1 0 0 1.2233 0 -1.784)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGOSxTbdsf)" class="ete_hcc5f"/><radialGradient id="SVGEbR53dim" cx="82.172" cy="14.532" r="6.953" gradientTransform="matrix(-.9657 -.2598 .2432 -.9037 157.988 49.015)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGEbR53dim)" class="a1djbxwmy"/><radialGradient id="SVGLLGMAbQy" cx="80.523" cy="21.246" r="7.3" gradientTransform="rotate(7.833 143.416 25.557)scale(1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGLLGMAbQy)" class="p3o65qbfn"/><path class="d9nnv-_2x"/><path class="vsomxzbbw"/><g class="fgqj36-ft"><ellipse class="wcky_6n0l"/><ellipse class="kl3eeacvj"/></g><path class="z1o7etndr"/><path class="mwo57_mcw"/><path class="jwav7kbmz"/><linearGradient id="SVGYzFNs47f" x1="65.262" x2="45.803" y1="53.492" y2="86.594" gradientTransform="translate(-40.898)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".401" class="tisq54bqj"/></linearGradient><path fill="url(#SVGYzFNs47f)" class="hbj3lpbfo"/><linearGradient id="SVGtzw5Hbdn" x1="143.186" x2="123.586" y1="74.617" y2="41.275" gradientTransform="rotate(184.985 96.666 65.757)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".401" class="tisq54bqj"/></linearGradient><path fill="url(#SVGtzw5Hbdn)" class="r311fk34v"/><linearGradient id="SVG6yQAgehu" x1="14.142" x2="58.79" y1="60.907" y2="60.907" gradientUnits="userSpaceOnUse"><stop offset=".172" class="fqlolabaa"/><stop offset=".369" class="jct3k-imk"/><stop offset=".732" class="x_enifbfx"/><stop offset=".994" class="necgdbbfe"/></linearGradient><path fill="url(#SVG6yQAgehu)" class="msafpsbfl"/><path class="mik72qbtw"/><radialGradient id="SVGLqsdsdxl" cx="135.458" cy="38.003" r="10.125" gradientTransform="matrix(1 0 0 -.4912 -92.695 56.67)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGLqsdsdxl)" class="mislshxhn"/><radialGradient id="SVG40gf3trr" cx="125.486" cy="36.497" r="2.992" gradientTransform="rotate(154.924 82.042 -3.378)scale(1 -.7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVG40gf3trr)" class="e2kz-5brv"/><radialGradient id="SVGNeqsjdbs" cx="133.241" cy="28.033" r="13.142" gradientTransform="matrix(-.0746 -.9972 -.8311 .0622 78.222 159.159)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGNeqsjdbs)" class="u7tavs5cz"/><radialGradient id="SVGwPACpbXv" cx="27.946" cy="28.033" r="13.142" gradientTransform="matrix(.0746 -.9972 .8311 .0622 2.562 54.157)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGwPACpbXv)" class="qb-9nm35h"/><radialGradient id="SVG8d4spexU" cx="30.163" cy="38.003" r="10.125" gradientTransform="matrix(-1 0 0 -.4912 60.327 56.67)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVG8d4spexU)" class="fb9bes3kp"/><radialGradient id="SVGBLmBOdVA" cx="20.192" cy="36.497" r="2.992" gradientTransform="rotate(25.076 -.992 31.786)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVGBLmBOdVA)" class="estxbuz5s"/><path class="teoasjbpu"/><path class="asakcmbhw"/><path class="m9bvmlbio"/><path class="mbcfixbfs"/><radialGradient id="SVGEUuJBb3h" cx="44.248" cy="21.1" r="15.405" gradientTransform="matrix(.3076 .9515 -.706 .2282 45.534 -25.818)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGEUuJBb3h)" class="po6_isyww"/><radialGradient id="SVGhpBsbeWP" cx="29.23" cy="4.303" r="4.039" gradientTransform="matrix(.8813 .4726 -.5603 1.045 5.881 -14.007)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVGhpBsbeWP)" class="t69h5d3km"/><radialGradient id="SVGHCAXud7w" cx="163.034" cy="95.777" r="12.417" gradientTransform="matrix(-.9378 -.3944 .2182 -.5285 170.255 126.553)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGHCAXud7w)" class="ecvy4bb0r"/><radialGradient id="SVG6MnSveYc" cx="27.608" cy="7.988" r="3.707" gradientTransform="matrix(1 0 0 1.2233 0 -1.784)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVG6MnSveYc)" class="jfe_kkbgu"/><radialGradient id="SVGHOJyheDF" cx="27.098" cy="14.532" r="6.953" gradientTransform="matrix(-.9657 -.2598 .2432 -.9037 49.732 34.705)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGHOJyheDF)" class="qg1ju8bzf"/><radialGradient id="SVG5Sl5weMp" cx="25.448" cy="21.246" r="7.3" gradientTransform="rotate(7.833 88.333 25.557)scale(1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVG5Sl5weMp)" class="t-xf0pb2p"/><path class="jrud5cbus"/><g class="fgqj36-ft"><ellipse class="ibn0tfb_a"/><ellipse class="qlz_o4bnb"/></g><path class="s6rnnwbfx"/><path class="hsap_yb2p"/><path class="n03sagaag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:people-holding-hands-medium-dark-skin-tone" /></template>
<style>
.a1djbxwmy {
  d: path("m80.76 10.15l-2.08-.34c-.08 0-.36.02-.51.05c-1.17.16-2.55.77-3.3 2.32c-.8 1.67-.78 3.1-.56 4.06c.06.32.19.68.19.68s1.03-.98 3.48-1.04z");
}

.aoitwmb8k {
  d: path("M91.55 43.9v-4.08l-12.35-.98l-1.12 1.38s2.66 3.68 9.61 3.68z");
}

.asakcmbhw {
  fill: var(--svg-color--a56c43, #a56c43);
  d: path("M36.46 6.66c-7.62 0-14.69 8.15-14.69 19.89c0 11.67 7.28 17.44 14.69 17.44s14.69-5.77 14.69-17.44c0-11.74-7.07-19.89-14.69-19.89");
}

.asbw0jbgl {
  stop-color: var(--svg-color--8d5738, #8d5738);
}

.b5pelhk-b {
  stop-color: var(--svg-color--ef6c00, #ef6c00);
}

.bjtjsm2ge {
  d: path("M88.49 5.68c-.47.23-.89.46-1.25.65c-.42.23-3.1 1.72-4.98.65c-1.16-.65-1.16-2.41-1.16-2.47c-.53.68-2.14 5.53 2.56 5.85c2.03.14 3.28-1.63 4.02-3.13c.27-.54.69-1.33.81-1.55");
}

.d55a2v9wg {
  d: path("M73.12 22.65c-1.84 4.48.1 9.08 1.91 11.03c.25.27 1.3 1.3 1.54 2.13c0 0 4.12-5.75 5.36-9.13c.25-.68.47-1.39.5-2.11c.02-.54-.06-1.19-.38-1.65c-.38-.57-.83-.42-1.49-.42c-1.25 0-6.69-.32-7.12-.32c.01 0-.32.47-.32.47");
}

.d9nnv-_2x {
  fill: var(--svg-color--473530, #473530);
  d: path("M95.23 35.99c-1.4.83-5.97.83-7.37 0c-.8-.48-1.62.25-1.29.98c.33.72 2.82 2.38 4.98 2.38s4.62-1.66 4.95-2.38c.33-.73-.47-1.46-1.27-.98");
}

.dhayusc9l {
  d: path("M104.98 38.44c-1.85-2.81 2.25-3.86 2.25-3.86c-.71.89-1.04 1.66-.62 2.42c.52.95 2.08 1.09 2.08 1.09s-2.12 1.9-3.71.35");
}

.e2kz-5brv {
  d: path("M49.9 38.44c-1.85-2.81 2.25-3.86 2.25-3.86c-.71.89-1.04 1.66-.62 2.42c.52.95 2.08 1.09 2.08 1.09s-2.11 1.9-3.71.35");
}

.ecvy4bb0r {
  d: path("M43.01 4.85c3.17.86 4.71 2.47 5.22 4.62c.15.63.33 6.52-10.91-.17c-4.18-2.49-3.04-4.05-2.55-4.22c1.92-.7 4.7-1.19 8.24-.23");
}

.elbau5r8n {
  d: path("M98.09 4.85c3.17.86 4.71 2.47 5.22 4.62c.15.63.33 6.52-10.91-.17c-4.18-2.49-3.04-4.05-2.55-4.22c1.91-.7 4.69-1.19 8.24-.23");
}

.estxbuz5s {
  d: path("M23.02 38.44c1.85-2.81-2.25-3.86-2.25-3.86c.71.89 1.04 1.66.62 2.42c-.52.95-2.08 1.09-2.08 1.09s2.12 1.9 3.71.35");
}

.ete_hcc5f {
  d: path("M81.09 4.51c-.01 0-.01.01-.03.01c-.4.17-3.56 1.63-2.38 5.3l3.36.54c-2.98-3.02-.94-5.86-.94-5.86z");
}

.fb9bes3kp {
  d: path("M36.47 43.9v-4.08l-12.35-.98L23 40.22s2.66 3.68 9.61 3.68z");
}

.fgqj36-ft {
  fill: var(--svg-color--42312c, #42312c);
}

.fqlolabaa {
  stop-color: var(--svg-color--4fc3f7, #4fc3f7);
}

.fu9bhttza {
  d: path("m100.1 54.1l9.7-.6s4.5 10 6 13.33c0 0 4.24 6.32 6.17 9.17c1.88 1.92 2.36 2.62 3.04 5.19c.75 2.83.4 4.38.04 5.06c-.35.69-2.25 2.46-3.42 1.38c-1.24-1.15-1.15-5.22-2.31-4.94c-.6.15.16 1.36.23 2.56s-.85 1.41-1.5 1.08c-.33-.17-1.85-2.71-1.85-2.71l-.65-4.21l-15.13-21.23z");
}

.ggzrctssn {
  d: path("M71.96 53s-3.53 11.93-5 15.33l-4.39 11.02c-.7 1.55-.08 3.58 1.39 4.43c1.69.97 4.14.24 4.95-1.53l12.54-26.41l-1.01-3.46z");
}

.hbj3lpbfo {
  d: path("m27.99 54.1l-9.7-.6s-4.5 10-6 13.33c0 0-4.24 6.32-6.17 9.17c-1.88 1.92-2.36 2.62-3.04 5.19c-.75 2.83-.4 4.38-.04 5.06s2.25 2.46 3.42 1.38c1.24-1.15 1.15-5.22 2.31-4.94c.6.15-.16 1.36-.23 2.56s.85 1.41 1.5 1.08c.33-.17 1.85-2.71 1.85-2.71l.65-4.21l15.13-21.24z");
}

.hg-9rbldu {
  d: path("M80.94 44.87c2.42-.64 6.65-1.06 10.65-1.06c4-.01 8.19.42 10.61 1.06c7.55 2.01 9.42 5.56 11.67 11.65l-8.28 3.2V78h-28V59.72l-8.37-3.2c2.25-6.09 4.17-9.64 11.72-11.65");
}

.hm_tflbqq {
  d: path("M109.96 22.65c1.84 4.48-.1 9.08-1.91 11.03c-.25.27-1.3 1.3-1.54 2.13c0 0-4.12-5.75-5.36-9.13c-.25-.68-.47-1.39-.5-2.11c-.02-.54.06-1.19.38-1.65c.38-.57 8.72-.73 8.72-.73c-.01-.01.21.46.21.46");
}

.hsap_yb2p {
  fill: var(--svg-color--a56c43, #a56c43);
  d: path("M67.34 86.4c-.16-.07-.32-.11-.5-.11c-.04 0-.07.01-.11.02l.05-.1c.28-.62.04-1.36-.55-1.66q-.24-.12-.51-.12c-.07 0-.14.02-.21.03c.25-.6.03-1.31-.53-1.61c-.17-.09-.35-.14-.54-.14c-.26 0-.51.1-.71.26c-.07-.37-.29-.72-.66-.91c-.17-.09-.35-.13-.53-.13c-.46 0-.87.27-1.07.7l-.92 1.96c-.29.62-.05 1.39.58 1.71c.17.09.35.13.54.13s.36-.06.52-.14c.01.1 0 .2.03.29c.1.32.3.58.58.73c.17.09.35.14.54.14c.21 0 .4-.06.57-.16c.06.39.27.76.63.94q.24.12.51.12c.16 0 .31-.04.44-.11c.08.38.3.72.65.89c.16.07.32.11.5.11c.47 0 .9-.29 1.09-.74l.18-.42c.3-.63.03-1.39-.57-1.68");
}

.ibn0tfb_a {
  cx: 29.26px;
  cy: 28.33px;
  rx: 2.16px;
  ry: 2.24px;
}

.jct3k-imk {
  stop-color: var(--svg-color--42bff6, #42bff6);
}

.jfe_kkbgu {
  d: path("M26.01 4.51c-.01 0-.01.01-.03.01c-.4.17-3.56 1.63-2.38 5.3l3.36.54c-2.98-3.02-.94-5.86-.94-5.86s0 .01-.01.01");
}

.jrud5cbus {
  fill: var(--svg-color--875334, #875334);
  d: path("M38.15 32.4a1 1 0 0 0-.14-.04h-3.1c-.05.01-.1.02-.14.04c-.28.11-.44.4-.3.72s.75 1.18 1.99 1.18s1.86-.87 1.99-1.18s-.02-.6-.3-.72");
}

.jwav7kbmz {
  fill: var(--svg-color--424242, #424242);
  d: path("M25.48 124h-4.45c-.82-.02-1.41-.96-1.17-1.78c.74-2.5 2.99-4.32 5.62-4.32c2.68 0 4.96 1.9 5.66 4.46c.22.82-.39 1.63-1.21 1.63c0 .01-4.45.01-4.45.01m22.05 0h4.45c.82-.02 1.41-.96 1.17-1.78c-.74-2.5-2.99-4.32-5.62-4.32c-2.68 0-4.96 1.9-5.66 4.46c-.22.82.39 1.63 1.21 1.63c0 .01 4.45.01 4.45.01");
}

.kg8mw9bxw {
  d: path("m66.37 69.83l-1.78 4.46l1.44 2.76l3.91 3.07l3.67-7.74z");
}

.kl3eeacvj {
  cx: 98.74px;
  cy: 28.33px;
  rx: 2.16px;
  ry: 2.24px;
}

.l9h03nbew {
  d: path("M78.1 38.44c1.85-2.81-2.25-3.86-2.25-3.86c.71.89 1.04 1.66.62 2.42c-.52.95-2.08 1.09-2.08 1.09s2.11 1.9 3.71.35");
}

.m_5onzv2u {
  stop-color: var(--svg-color--554138, #554138);
}

.m9bvmlbio {
  fill: var(--svg-color--473530, #473530);
  d: path("M40.15 35.99c-1.4.83-5.97.83-7.37 0c-.8-.48-1.62.25-1.29.98c.33.72 2.82 2.38 4.98 2.38s4.62-1.66 4.95-2.38c.34-.73-.47-1.46-1.27-.98");
}

.mbcfixbfs {
  fill: var(--svg-color--3c2c23, #3c2c23);
  d: path("M53.78 13.34c-1.06-1.6-3.42-3.74-5.54-3.88c-.34-2.04-2.52-3.76-4.64-4.43c-5.72-1.81-9.44.22-11.44 1.31c-.42.23-3.1 1.72-4.98.65c-1.18-.67-1.16-2.48-1.16-2.48s-3.69 1.4-2.42 5.32c-1.26.05-2.93.59-3.81 2.36c-1.05 2.12-.67 3.89-.37 4.74c-1.09.92-2.46 2.89-1.52 5.45c.71 1.92 3.53 2.81 3.53 2.81c-.2 3.46.45 5.59.79 6.46c.06.15.27.14.31-.02c.43-1.71 1.89-7.69 1.74-8.74c0 0 4.91-.97 9.58-4.42c.95-.7 1.98-1.3 3.08-1.74c5.88-2.34 7.1 1.65 7.1 1.65s4.07-.78 5.3 4.87c.46 2.12.78 5.51 1.04 7.89c.02.17.25.2.31.05c.41-.94 1.23-2.81 1.43-4.72c.07-.67 1.88-1.56 2.65-4.44c1.06-3.84-.21-7.53-.98-8.69");
}

.mik72qbtw {
  fill: var(--svg-color--3c2c23, #3c2c23);
  d: path("M51.55 37.01c-.54-.98.15-1.98 1.32-3.22c1.86-1.96 3.89-6.51 2.01-11.14c.01-.03-.37-.81-.36-.83l-.78-.04c-.25-.04-8.76-.05-17.28-.05s-17.03.02-17.28.05c0 0-1.15.84-1.14.87c-1.88 4.62.15 9.17 2.01 11.14c1.17 1.24 1.86 2.24 1.32 3.22c-.52.95-2.08 1.09-2.08 1.09s.36.98 1.23 1.5c.8.49 1.78.6 2.47.62c0 0 2.66 3.68 9.61 3.68h7.74c6.95 0 9.61-3.68 9.61-3.68c.68-.02 1.66-.13 2.47-.62c.87-.53 1.22-1.5 1.22-1.5s-1.57-.14-2.09-1.09");
}

.mislshxhn {
  d: path("M36.45 43.9v-4.08l12.35-.98l1.12 1.38s-2.66 3.68-9.61 3.68z");
}

.mlb8vsb9l {
  stop-color: var(--svg-color--554138, #554138);
  stop-opacity: 0;
}

.msafpsbfl {
  d: path("M47.08 44.87c-2.42-.64-6.65-1.06-10.65-1.06c-4-.01-8.19.42-10.61 1.06c-7.55 2.01-9.42 5.56-11.67 11.65l8.28 3.2V78h28V59.72l8.37-3.2c-2.26-6.09-4.18-9.64-11.72-11.65");
}

.mujsf_8ht {
  stop-color: var(--svg-color--f78c1f, #f78c1f);
}

.mwo57_mcw {
  fill: var(--svg-color--7c7c7c, #7c7c7c);
  d: path("M22.53 74.61v48.08h5.65l7.87-38.21c.04-.24.24-.41.46-.41s.42.17.46.41l7.87 38.21h5.65V74.61z");
}

.n03sagaag {
  fill: var(--svg-color--875334, #875334);
  d: path("M67.56 86.32c.54-1.78-1.46-2.21-1.46-2.21c.28-1.01-1.32-2.17-2.31-1.59c-1.48-1.48-2.52-.13-2.66.81c0 0 .74-1.13 1.51-.77c.52.24.51.74.35 1.22c-.25.75-.46 1.51-.46 1.51s.56-.95 1.04-1.56c.16-.21.67-.63 1.21-.33c.54.29.55.96.47 1.2c-.26.82-.93 1.92-.93 1.92s.5-.51.92-.99c.33-.38.61-.62 1.11-.39c.54.25.51.86.35 1.17c-.33.66-.76 1.45-.76 1.45s.78-1.19 1.59-.52c.51.43.06 1.48.12 1.42c1.44-1.46-.09-2.34-.09-2.34");
}

.n9zjxtbmn {
  d: path("M91.53 43.9v-4.08l12.35-.98l1.12 1.38s-2.66 3.68-9.61 3.68z");
}

.necgdbbfe {
  stop-color: var(--svg-color--03a9f4, #03a9f4);
}

.njynq2ywd {
  stop-color: var(--svg-color--a56c43, #a56c43);
  stop-opacity: 0;
}

.nlb89objm {
  stop-color: var(--svg-color--f47f12, #f47f12);
}

.o0wapkbev {
  d: path("M107.19 26.48c.07-.67 1.88-1.56 2.65-4.44c.08-.31.15-.62.22-.93c.63-3.5-.5-6.71-1.21-7.77c-.98-1.48-3.07-3.41-5.06-3.81c-.17-.02-.34-.04-.5-.05c0 0 .14.93-.23 1.67c-.49.96-1.47 1.19-1.47 1.19c5.18 5.18 4.81 9.51 5.6 14.14");
}

.p3o65qbfn {
  d: path("M74.4 17c-1.02.91-2.4 2.94-1.39 5.45c.77 1.9 3.5 2.72 3.5 2.72c0 .01.55.17.83.17l.64-9.47c-1.31 0-2.57.39-3.38.96c.01.02-.2.16-.2.17");
}

.po6_isyww {
  d: path("M52.12 26.48c.07-.67 1.88-1.56 2.65-4.44c.08-.31.15-.62.22-.93c.63-3.5-.5-6.71-1.21-7.77c-.98-1.48-3.07-3.41-5.06-3.81c-.17-.02-.34-.04-.5-.05c0 0 .14.93-.23 1.67c-.49.96-1.47 1.19-1.47 1.19c5.17 5.18 4.8 9.51 5.6 14.14");
}

.qb-9nm35h {
  d: path("M18.04 22.65c-1.84 4.48.1 9.08 1.91 11.03c.25.27 1.3 1.3 1.54 2.13c0 0 4.12-5.75 5.36-9.13c.25-.68.48-1.39.5-2.11c.02-.54-.06-1.19-.38-1.65c-.38-.57-.83-.42-1.49-.42c-1.25 0-6.69-.32-7.12-.32c.02 0-.32.47-.32.47");
}

.qg1ju8bzf {
  d: path("m25.68 10.15l-2.08-.33c-.08 0-.36.02-.51.05c-1.17.16-2.55.77-3.3 2.32c-.8 1.67-.78 3.1-.56 4.06c.06.32.19.68.19.68s1.03-.98 3.48-1.04z");
}

.qlz_o4bnb {
  cx: 43.66px;
  cy: 28.33px;
  rx: 2.16px;
  ry: 2.24px;
}

.r311fk34v {
  d: path("m46.93 57.48l14.15 23.51s-1.53 2.62-.39 4.91c1.6 1.15 2.32-2.27 2.94-2.36c1.19-.18 3.08 4.56 4.34 4.56c2.41 1.04 3.53-2.18 3.57-4.08c.91-3.31-5.37-6.79-5.37-6.79c-1.68-3-4.67-9.8-4.67-9.8c-1.21-3.45-4.82-13.8-4.82-13.8l-9.71-.25z");
}

.rnj6bzm1r {
  fill: var(--svg-color--7a4c32, #7a4c32);
  d: path("M91.54 40.72h-5v5.3c0 2.4 2.04 4.34 4.54 4.34H92c2.51 0 4.54-1.94 4.54-4.34v-5.3zm11.98-16.38H79.57c-2.58 0-4.69 2.25-4.69 5s2.11 5 4.69 5h23.95c2.58 0 4.69-2.25 4.69-5s-2.11-5-4.69-5");
}

.s6rnnwbfx {
  fill: var(--svg-color--42312c, #42312c);
  d: path("M40.46 24.32c.41-.54 1.36-1.34 3.21-1.34s2.8.79 3.21 1.34c.18.24.14.52.01.69c-.12.16-.46.3-.84.17s-1.13-.51-2.37-.52c-1.25.01-1.99.39-2.37.52s-.73-.01-.84-.17a.54.54 0 0 1-.01-.69m-14.41 0c.41-.54 1.36-1.34 3.21-1.34c1.84 0 2.8.79 3.21 1.34c.18.24.14.52.01.69c-.12.16-.46.3-.84.17s-1.13-.51-2.37-.52c-1.25.01-1.99.39-2.37.52s-.73-.01-.84-.17a.53.53 0 0 1-.01-.69");
}

.t-xf0pb2p {
  d: path("M19.33 17c-1.02.91-2.4 2.94-1.39 5.45c.77 1.9 3.5 2.72 3.5 2.72c0 .01.55.17.83.17l.64-9.47c-1.31 0-2.57.39-3.38.96c0 .02-.21.16-.2.17");
}

.t69h5d3km {
  d: path("M33.41 5.68c-.47.23-.89.46-1.25.65c-.42.23-3.1 1.72-4.98.65c-1.16-.66-1.16-2.41-1.16-2.47c-.53.68-2.14 5.53 2.56 5.85c2.03.14 3.28-1.63 4.02-3.13c.28-.54.7-1.33.81-1.55");
}

.tajsh7foc {
  fill: var(--svg-color--7c7c7c, #7c7c7c);
  d: path("M105.56 74.61v48.08h-5.65l-7.87-38.21c-.04-.24-.24-.41-.46-.41s-.42.17-.46.41l-7.87 38.21H77.6V74.61z");
}

.tcjxzpbtc {
  fill: var(--svg-color--3c2c23, #3c2c23);
  d: path("M108.86 13.34c-1.06-1.6-3.42-3.74-5.54-3.88c-.34-2.04-2.52-3.77-4.64-4.44c-5.72-1.81-9.44.22-11.44 1.31c-.42.23-3.1 1.72-4.98.65c-1.18-.67-1.16-2.48-1.16-2.48s-3.69 1.4-2.43 5.32c-1.26.05-2.93.59-3.81 2.36c-1.05 2.12-.68 3.89-.37 4.74c-1.09.92-2.46 2.89-1.52 5.45c.71 1.92 3.53 2.81 3.53 2.81c-.2 3.46.45 5.59.79 6.46c.06.15.27.14.31-.02c.43-1.71 1.89-7.69 1.74-8.74c0 0 4.9-.97 9.58-4.42c.95-.7 1.98-1.3 3.08-1.74c5.88-2.34 7.11 1.65 7.11 1.65s4.07-.78 5.3 4.87c.46 2.12.78 5.51 1.04 7.89c.02.17.25.2.31.05c.41-.94 1.23-2.81 1.43-4.72c.07-.67 1.88-1.56 2.65-4.44c1.06-3.83-.22-7.52-.98-8.68");
}

.teoasjbpu {
  fill: var(--svg-color--7a4c32, #7a4c32);
  d: path("M36.47 40.72h5v5.3c0 2.4-2.03 4.34-4.55 4.34h-.91c-2.51 0-4.55-1.94-4.55-4.34v-5.3zm11.97-16.38H24.49c-2.58 0-4.69 2.25-4.69 5s2.11 5 4.69 5h23.95c2.58 0 4.69-2.25 4.69-5s-2.11-5-4.69-5");
}

.tisq54bqj {
  stop-color: var(--svg-color--a56c43, #a56c43);
}

.topfecjbg {
  fill: var(--svg-color--a56c43, #a56c43);
  d: path("M91.54 6.66c-7.62 0-14.69 8.15-14.69 19.89c0 11.67 7.28 17.44 14.69 17.44s14.69-5.77 14.69-17.44c-.01-11.74-7.07-19.89-14.69-19.89");
}

.u7tavs5cz {
  d: path("M54.88 22.65c1.84 4.48-.1 9.08-1.91 11.03c-.25.27-1.3 1.3-1.54 2.13c0 0-4.12-5.75-5.36-9.13c-.25-.68-.47-1.39-.51-2.11c-.02-.54.06-1.19.38-1.65c.38-.57 8.72-.73 8.72-.73c0-.01.22.46.22.46");
}

.vsomxzbbw {
  fill: var(--svg-color--875334, #875334);
  d: path("M93.23 32.4a1 1 0 0 0-.14-.04h-3.1c-.05.01-.1.02-.14.04c-.28.11-.44.4-.3.72c.13.31.75 1.18 1.99 1.18s1.86-.87 1.99-1.18s-.02-.6-.3-.72");
}

.wcky_6n0l {
  cx: 84.34px;
  cy: 28.33px;
  rx: 2.16px;
  ry: 2.24px;
}

.wiau9ou2e {
  fill: var(--svg-color--424242, #424242);
  d: path("M102.61 124h4.45c.82-.02 1.41-.96 1.17-1.78c-.74-2.5-2.99-4.32-5.62-4.32c-2.68 0-4.96 1.9-5.66 4.46c-.22.82.39 1.63 1.21 1.63c0 .01 4.45.01 4.45.01m-22.05 0h-4.45c-.82-.02-1.41-.96-1.17-1.78c.74-2.5 2.99-4.32 5.62-4.32c2.68 0 4.96 1.9 5.66 4.46c.22.82-.39 1.63-1.21 1.63c0 .01-4.45.01-4.45.01");
}

.x_enifbfx {
  stop-color: var(--svg-color--20b3f5, #20b3f5);
}

.z_tilxbde {
  fill: var(--svg-color--3c2c23, #3c2c23);
  d: path("M106.62 37.01c-.54-.98.15-1.98 1.32-3.22c1.86-1.96 3.89-6.51 2.01-11.14c.01-.03-.37-.81-.36-.83l-.78-.04c-.25-.04-8.76-.05-17.28-.05s-17.03.02-17.28.05c0 0-1.15.84-1.14.87c-1.88 4.62.14 9.17 2.01 11.14c1.17 1.24 1.86 2.24 1.32 3.22c-.52.95-2.08 1.09-2.08 1.09s.36.98 1.22 1.5c.8.49 1.79.6 2.47.62c0 0 2.66 3.68 9.61 3.68h7.74c6.95 0 9.61-3.68 9.61-3.68c.68-.02 1.66-.13 2.47-.62c.87-.53 1.22-1.5 1.22-1.5s-1.56-.14-2.08-1.09");
}

.z1o7etndr {
  fill: var(--svg-color--42312c, #42312c);
  d: path("M95.54 24.32c.41-.54 1.36-1.34 3.21-1.34s2.8.79 3.21 1.34c.18.24.14.52.01.69c-.12.16-.46.3-.84.17s-1.13-.51-2.37-.52c-1.25.01-1.99.39-2.37.52s-.73-.01-.84-.17a.53.53 0 0 1-.01-.69m-14.42 0c.41-.54 1.36-1.34 3.21-1.34s2.8.79 3.21 1.34c.18.24.14.52.01.69c-.12.16-.46.3-.84.17s-1.13-.51-2.37-.52c-1.25.01-1.99.39-2.37.52s-.73-.01-.84-.17a.554.554 0 0 1-.01-.69");
}

</style>
