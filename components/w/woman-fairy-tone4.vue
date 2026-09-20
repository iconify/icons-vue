<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGXE6TtuSb" x1="181.136" x2="210.302" y1="182.655" y2="197.803" gradientTransform="rotate(192.075 137.187 138.735)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGXE6TtuSb)" class="xf6fh6bhw"/><g class="cnjyhhbwn"><path class="n1u6nbc0f"/><path class="py4qnz7vk"/></g><linearGradient id="SVGlXI7H7IU" x1="195.146" x2="238.736" y1="252.387" y2="211.362" gradientTransform="rotate(194.277 141.156 147.884)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGlXI7H7IU)" class="xnopq2pqj"/><g class="cnjyhhbwn"><path class="migximbql"/><path class="b62g__mfy"/></g><linearGradient id="SVG5WWAHbGV" x1="1662.631" x2="1691.797" y1="-134.263" y2="-119.115" gradientTransform="rotate(167.925 -830.705 65.384)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVG5WWAHbGV)" class="mslkq1m7s"/><g class="cnjyhhbwn"><path class="kg6dsbc9e"/><path class="px8n4hb0v"/></g><linearGradient id="SVG3fyFyexY" x1="1663.945" x2="1707.534" y1="-119.069" y2="-160.094" gradientTransform="rotate(165.723 -834.674 61.03)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVG3fyFyexY)" class="a_i9byb0q"/><g class="cnjyhhbwn"><path class="efbfk7fqo"/><path class="oghj2ob8r"/></g><linearGradient id="SVGEDcKdULq" x1="46.53" x2="57.638" y1="34.1" y2="34.1" gradientTransform="rotate(185.463 1.619 62.523)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGEDcKdULq)" class="zz49ylmdp"/><linearGradient id="SVGD6wpF7Gq" x1="68.859" x2="67.619" y1="64.792" y2="35.747" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGD6wpF7Gq)" class="dt2pj8_mi"/><linearGradient id="SVGoCmTgeSl" x1="62.482" x2="70.505" y1="38.52" y2="37.752" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="njynq2ywd"/></linearGradient><path fill="url(#SVGoCmTgeSl)" class="gxg1-qb0e"/><linearGradient id="SVGcj206dgC" x1="59.639" x2="48.639" y1="61.828" y2="9.495" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGcj206dgC)" class="d1_fqacwe"/><linearGradient id="SVGLHduS7ZK" x1="51.263" x2="19.433" y1="70.031" y2="70.031" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGLHduS7ZK)" class="o9go5fboh"/><linearGradient id="SVGKxsHwc1o" x1="76.658" x2="102.615" y1="74.54" y2="74.54" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGKxsHwc1o)" class="p4aum-bul"/><linearGradient id="SVGAVIw9cjp" x1="98.82" x2="102.132" y1="77.9" y2="76.685" gradientTransform="rotate(171.118 1.075 73.16)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="njynq2ywd"/><stop offset="1" class="asbw0jbgl"/></linearGradient><path fill="url(#SVGAVIw9cjp)" class="yromiiypm"/><path class="zhy9_lb7y"/><path class="lls72si_r"/><path class="m198sgbda"/><linearGradient id="SVG7HvP4SjK" x1="64" x2="64" y1="100.789" y2="53.171" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="qxo5t2h3y"/><stop offset=".188" class="vt1muuwrv"/><stop offset=".376" class="me0e_ybij"/><stop offset=".555" class="k3krp1ban"/><stop offset=".723" class="hbfhgtbkx"/><stop offset=".876" class="rd5dvgb4j"/><stop offset="1" class="v9cqrbcjy"/></linearGradient><path fill="url(#SVG7HvP4SjK)" class="cy1fo48jq"/><linearGradient id="SVGORsEPeOT" x1="104.379" x2="108.704" y1="77.241" y2="77.241" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGORsEPeOT)" class="pw4_46ulx"/><linearGradient id="SVGlsOVfbCj" x1="104.379" x2="108.704" y1="79.376" y2="79.376" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGlsOVfbCj)" class="xf8zq9-vv"/><linearGradient id="SVGxjcABdDT" x1="104.379" x2="108.704" y1="81.722" y2="81.722" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGxjcABdDT)" class="qdyydemhc"/><linearGradient id="SVGtBA9VdoT" x1="104.379" x2="108.704" y1="83.71" y2="83.71" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGtBA9VdoT)" class="j14cgnbzo"/><path class="bmv5smxal"/><linearGradient id="SVGoKO1vbHp" x1="106.212" x2="100.351" y1="83.757" y2="80.409" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".575" class="tisq54bqj"/></linearGradient><path fill="url(#SVGoKO1vbHp)" class="z-717raaq"/><path class="hq3849b8e"/><linearGradient id="SVGoJTSbdwy" x1="63.925" x2="63.925" y1="39.497" y2="48.404" gradientUnits="userSpaceOnUse"><stop offset="0" class="asbw0jbgl"/><stop offset=".63" class="tisq54bqj"/></linearGradient><path fill="url(#SVGoJTSbdwy)" class="k93h_nbic"/><linearGradient id="SVGJw2RXbAI" x1="25.214" x2="62.486" y1="112.404" y2="112.404" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="cv8sj5b5k"/><stop offset="1" class="e0map1bcp"/></linearGradient><path fill="url(#SVGJw2RXbAI)" class="x_lf2cbav"/><path class="mh-s6shno"/><path class="jnnh-hphs"/><path class="y21qtfb8d"/><g class="fgqj36-ft"><ellipse transform="rotate(-88.802 58.062 24.274)" class="e880_9b7k"/><ellipse transform="rotate(-88.802 70.004 24.524)" class="y9kojhgwk"/></g><path class="zpb91f8rg"/><path class="ledl0yz1b"/><radialGradient id="SVGYMVlrd4g" cx="66.735" cy="122.8" r="13.956" gradientTransform="matrix(-.9872 0 0 -1.0217 129.012 132.14)" gradientUnits="userSpaceOnUse"><stop offset=".005" class="i_7m7ezqb"/><stop offset="1" class="cv8sj5b5k"/></radialGradient><path fill="url(#SVGYMVlrd4g)" class="v-7rzibyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:woman-fairy-tone4" /></template>
<style>
.a_i9byb0q {
  d: path("M9.47 33.38c-6.65 19.8 55.96 37.47 58.55 26.1c3.56-15.61-50.35-50.56-58.55-26.1");
}

.asbw0jbgl {
  stop-color: var(--svg-color--8d5738, #8d5738);
}

.awx491bun {
  stop-color: var(--svg-color--ffa6c9, #ffa6c9);
}

.b62g__mfy {
  d: path("M97.43 31.09c-5.33 4.8-7.72 8.38-10.12 12.42m26.43-10.17c-4.72 3.95-8.3 7.58-10.26 13.35m-12.06 6.75c-5.97 1.22-10.36 1.32-15.62-.61");
}

.bmv5smxal {
  fill: var(--svg-color--875334, #875334);
  d: path("M107.65 51.97c-.46-.34-.96-.47-1.46-.56c-.51-.07-1.02-.09-1.57.08c.46.34.96.48 1.46.56c.51.08 1.02.1 1.57-.08m.19-2.45c-.49-.25-.98-.31-1.47-.31c-.49.01-.98.08-1.46.35c.49.26.98.31 1.47.31c.48-.02.97-.08 1.46-.35m-3.07-1.63c.59.11 1.13.02 1.66-.11c.52-.15 1.03-.35 1.49-.74c-.59-.11-1.13-.03-1.66.11c-.52.14-1.03.34-1.49.74");
}

.cnjyhhbwn {
  fill: none;
  stroke: var(--svg-color--87cdde, #87cdde);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-956px, 0.956px);
}

.cv8sj5b5k {
  stop-color: var(--svg-color--b346bd, #b346bd);
}

.cy1fo48jq {
  d: path("m76.33 53.58l.14 15.76L68 75.96c-.8.44-1.7.67-2.61.67c-.88.01-1.75-.19-2.54-.58l-11.01-6.48l-.13-15.77l-7.64-6.97s1.05-4.06 8.4-6.3c2.7-.82 6.25-1.4 10.91-1.44c5.15-.04 9.06.59 12 1.51c6.97 2.16 8.55 5.88 8.55 5.88z");
}

.d1_fqacwe {
  d: path("M65.46 74.45c-.3-4.5-1.21-9.32-2.13-13.95l-.42-.26l-11.06 8.86l-1.48 24.47l-3.22 15.87c-1.56.2-3.17.85-3.78 2.27c-.32.76-.3 1.62-.26 2.45c.1 2.2.23 4.4.4 6.6c.09 1.2.32 2.59 1.38 3.16c.71.38 1.6.24 2.29-.17c.69-.4 1.22-1.04 1.7-1.67c1.47-1.94 3.65-6.32 3.65-6.32S58.74 104.25 61 96.4c3.11-10.87 4.31-21.98 4.46-21.95");
}

.dt2pj8_mi {
  d: path("m55.64 90.28l13-4.42c0-.43-4.1-11.29-4.1-11.29l8.23-14.6c1.75 3.3 7.11 18.7 8.84 26.71c.65 3.01-.48 6.94-4.98 8.11c-5.02 1.3-9.87 1.92-16.25 2.58c-6.37.66-8.57-5.38-4.74-7.09");
}

.e0map1bcp {
  stop-color: var(--svg-color--762d7d, #762d7d);
}

.e880_9b7k {
  cx: 58.06px;
  cy: 24.27px;
  rx: 1.85px;
  ry: 1.79px;
}

.efbfk7fqo {
  d: path("M17.26 29.42c18.27 6.95 32.96 17.46 46.58 31.14M13.11 39.19c15.38 12.46 30.61 17.06 49.9 22.49");
}

.fgqj36-ft {
  fill: var(--svg-color--42312c, #42312c);
}

.gsabqfbpm {
  stop-color: var(--svg-color--abe1e1, #abe1e1);
}

.gxg1-qb0e {
  d: path("m68.64 85.87l-10.37 3.52l1.38 8.02s7.55-.6 11.85-1.51c4.3-.9-2.86-10.03-2.86-10.03");
}

.hbfhgtbkx {
  stop-color: var(--svg-color--c73395, #c73395);
}

.hq3849b8e {
  fill: var(--svg-color--875334, #875334);
  d: path("M100.41 49.99c1.43.24 2.87-.93 3.29-2.32l.04-.13l.02-.07c.01-.03.02-.06 0 0c-.03.07-.11.12-.18.12c-.07.01-.18-.07-.19-.12l.23.47c.16.31.33.61.51.91c.31.56.85 1.36 1.76 1.41c.85.04 1.72-.69 1.57-1.63c-.17-.71-.43-1.37-.83-1.96c-.79-1.17-1.29-2.18-2.9-1.98c1.37.19 1.96 1.03 2.54 2.2c.3.58.53 1.22.65 1.84c.08.47-.49.96-.98.89c-.25-.02-.49-.14-.7-.34c-.21-.19-.36-.47-.54-.76c-.17-.29-.33-.58-.49-.88l-.23-.44c-.04-.12-.23-.26-.39-.25c-.16 0-.32.1-.39.24c-.04.09-.03.11-.04.12l-.01.06l-.03.11c-.17.61-.51 1.16-.96 1.6c-.23.21-.51.39-.8.52c-.32.14-.63.21-.95.39");
}

.i_7m7ezqb {
  stop-color: var(--svg-color--d553e0, #d553e0);
}

.j14cgnbzo {
  d: path("M103.46 46.87c.15.65.8 1.06 1.45.91l2.68-.62a1.23 1.23 0 0 0 .91-1.46c-.15-.65-.8-1.06-1.45-.91l-2.68.62c-.66.16-1.05.81-.91 1.46");
}

.jnnh-hphs {
  fill: var(--svg-color--a56c43, #a56c43);
  d: path("M64.34 10.21c5.96.17 11.35 4.76 11.07 14.16c-.22 7.54-5.02 11.87-9.13 13.19c-.98.32-1.92.46-2.75.44s-1.75-.22-2.7-.59c-4.03-1.55-8.58-6.15-8.36-13.71c.27-9.39 5.91-13.66 11.87-13.49");
}

.k3krp1ban {
  stop-color: var(--svg-color--ae4c9d, #ae4c9d);
}

.k93h_nbic {
  d: path("M68.17 39.26v-4.58h-8.68v4.58c-2.81.24-5.12.69-7.01 1.26c.88 3.35 5.03 6.97 11.56 6.92c6.35-.05 10.39-3.56 11.35-6.85c-1.96-.6-4.34-1.08-7.22-1.33");
}

.kg6dsbc9e {
  d: path("M25.39 80.5c8.97-10.2 17.84-14.49 30.11-20.32c.28-.13.6-.33.58-.64s-.64-.29-.51-.01M39.54 80.96c3.72-2.49 15.7-13.97 22.79-21.7l-.49.34");
}

.ledl0yz1b {
  fill: var(--svg-color--473530, #473530);
  d: path("M67.14 30.77c-1.18.67-5.02.59-6.18-.13c-.66-.41-1.36.18-1.1.8c.26.61 2.33 2.04 4.13 2.08c1.81.04 3.9-1.31 4.19-1.91c.31-.6-.36-1.22-1.04-.84");
}

.lls72si_r {
  fill: var(--svg-color--ffd600, #ffd600);
  d: path("m111.39 14.76l-2.5 3.44l-4.24-.1l2.5 3.43l-1.41 4.01l4.04-1.32l3.37 2.59v-4.25l3.5-2.42l-4.05-1.31z");
}

.ltgl6j0rh {
  stop-color: var(--svg-color--ccc9d8, #ccc9d8);
}

.m198sgbda {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M104.55 50.81c.22-.05.38-.12.56-.26l-.79 3.89l-1.85.06l.93-4.17c.31.28.67.6 1.15.48");
}

.m5aiqz05p {
  stop-color: var(--svg-color--93f1e8, #93f1e8);
}

.me0e_ybij {
  stop-color: var(--svg-color--8c6fa9, #8c6fa9);
}

.mh-s6shno {
  fill: var(--svg-color--7a4c32, #7a4c32);
  d: path("m73.86 21.57l-2.67-.06l-14.47-.3l-2.67-.06c-2.14-.04-3.92 1.78-3.97 4.06c-.05 2.27 1.66 4.17 3.8 4.22l2.67.06l14.47.3l2.67.06c2.14.04 3.92-1.78 3.97-4.06s-1.67-4.17-3.8-4.22");
}

.migximbql {
  d: path("M110.46 31.63C92.2 38.58 77.77 49.1 64.15 62.77m51.62-25.23C100.39 50 84.27 58.46 64.99 63.89");
}

.mslkq1m7s {
  d: path("M24.38 85.27c11.04 11.24 47.55-18.37 39.7-24.6c-9.49-7.53-54.74 9.29-39.7 24.6");
}

.n1u6nbc0f {
  d: path("M102.66 82.29c-8.1-11.48-17.21-17.02-30.16-22.11c-.29-.11-.6-.33-.58-.64s.64-.29.51-.01m20.39 25.21C90.38 83.76 72.76 67 65.67 59.27l.49.34");
}

.njynq2ywd {
  stop-color: var(--svg-color--a56c43, #a56c43);
  stop-opacity: 0;
}

.o9go5fboh {
  d: path("M30.01 75.16c-2.86-.68-5.05-1.69-6.54-2.19c-1.5-.5-1.55-3.35 1.59-2.43c1.79.52 1.08-.68-.39-1.45c-1.47-.78-5.2 1.08-6.08.25c-.61-.57-.52-1.39-.18-1.7c1.15-1.02 3.9-1.99 6.32-1.88c2.16.1 5.55 3.29 7.63 2.74c.01 0 3.97-7.04 7.59-13.47l5.86-10.41l10.88 4.62s-18.5 21.87-19.47 22.77c-2.17 2.02-4.17 3.88-7.21 3.15");
}

.oghj2ob8r {
  d: path("M29.36 29.57c4.23 2.82 6.09 4.91 7.84 9.61m-20.43-5.35c4.72 3.95 7.3 8.23 9.26 14m4.91-5.04c7.32 3.4 16.19 9.65 21.26 9.82");
}

.p4aum-bul {
  d: path("M104.34 49.26c-.08-.09-.17-.17-.26-.26a2.69 2.69 0 0 0-2.8-.48c-1.25.49-5.64 3.46-6.71 4.1l-5.04 3.03l-5.86-9.76l-9.25 4.78l10.65 12.45c1.14 1.71 3.57 2.44 5.39 1.48c0 0 .08-.06.21-.15c.27-.12.54-.28.78-.46c3.08-2.44 9.6-7.91 10.56-8.83c1.49-1.47 4.27-3.78 2.33-5.9");
}

.pw4_46ulx {
  d: path("M104.05 52.26c-.16.66.25 1.33.9 1.48l1.69.41a1.224 1.224 0 1 0 .58-2.38l-1.69-.41c-.65-.17-1.32.24-1.48.9");
}

.px8n4hb0v {
  d: path("M31.5 81.62c1.08-3.71 10.56-12.46 12.57-15.75");
}

.py4qnz7vk {
  d: path("M95.31 80.96c-1.81-6.25-4.28-8.96-6.43-12.49");
}

.qdyydemhc {
  d: path("M103.98 48.25s.55 1.3 1.21 1.3l2.52-.01c.67-.01 1.21-.55 1.2-1.22v-.1c0-.67-.55-1.21-1.22-1.2l-2.52.01c-.66 0-1.2.55-1.19 1.22");
}

.qxo5t2h3y {
  stop-color: var(--svg-color--2cd1c9, #2cd1c9);
}

.r8ludbcjj {
  stop-color: var(--svg-color--80ffee, #80ffee);
}

.rd5dvgb4j {
  stop-color: var(--svg-color--d62490, #d62490);
}

.sxvxm2bwq {
  stop-color: var(--svg-color--f7accb, #f7accb);
}

.tisq54bqj {
  stop-color: var(--svg-color--a56c43, #a56c43);
}

.u_ug8ubbn {
  stop-color: var(--svg-color--85fced, #85fced);
}

.v-7rzibyl {
  d: path("M77.66 24.27c1.85-5.49 1.45-12.32-3.33-16.4c-2.94-2.51-6.74-3.45-10.5-3.37c-5.14.12-10.22 2.09-12.64 7.06c-1.52 3.11-1.67 6.28-1.22 9.64c.6 4.3 2.93 7.31 2.93 7.31s-.33-1.35-.42-3.99c-.05-1.36.33-4.83 1.89-5.19c8.67-2.65 12.74-6.62 12.74-6.62c.7 1.52 1.95 3.34 3.21 4.36c.63.51 1.3.98 1.94 1.48c.5.38 2.1 1.2 2.48 2.31c1.42 4.94-.45 9.07-.45 9.07s2.43-2.02 3.37-5.66");
}

.v9cqrbcjy {
  stop-color: var(--svg-color--db1f8e, #db1f8e);
}

.vt1muuwrv {
  stop-color: var(--svg-color--609cb7, #609cb7);
}

.x_lf2cbav {
  d: path("M51.97 8.24c-2.83.3-5.42 1.79-7.46 3.73c-1.74 1.66-4.52 6.41-7.46 3.73c-.98-.89.1-2.49.1-2.49s-3.05.47-2.04 3.77c0 0-7.75-3.51-9.88 3.04c0 0 1.29-1.74 3.44-1.6c1.36.09 2.5 1.04 3.44 2.01c.94.96 1.71 2.07 2.65 3.03c2.13 2.16 5.13 3.59 8.21 3.59c4.6 0 8.93-3.68 11.25-5.68c1.3-1.12 6.33-10.26 7.95-11.39c2.26-1.59-7.37-2.04-10.2-1.74");
}

.xf6fh6bhw {
  d: path("M103.62 85.27c-11.04 11.24-47.55-18.37-39.7-24.6c9.49-7.53 54.74 9.29 39.7 24.6");
}

.xf8zq9-vv {
  d: path("M104.14 50.39c-.07.68.43 1.28 1.11 1.35l2.26.23c.68.07 1.28-.43 1.35-1.11s-.43-1.28-1.11-1.35l-2.26-.23c-.68-.07-1.28.43-1.35 1.11");
}

.xnopq2pqj {
  d: path("M118.54 35.59c6.64 19.8-55.96 37.47-58.55 26.1c-3.57-15.6 50.34-50.56 58.55-26.1");
}

.y21qtfb8d {
  fill: var(--svg-color--42312c, #42312c);
  d: path("M67.76 21.27c.33-.42 1.09-1.01 2.54-.97c1.44.04 2.17.68 2.47 1.12c.14.19.09.41-.01.54c-.1.12-.37.22-.66.12c-.3-.11-.87-.43-1.84-.46c-.97-.02-1.56.26-1.87.36c-.3.09-.57-.03-.65-.15c-.1-.16-.13-.38.02-.56m-12.2-.33c.33-.42 1.09-1.01 2.54-.97c1.44.04 2.17.68 2.47 1.12c.14.19.09.41-.01.54c-.1.12-.37.22-.66.12c-.3-.11-.87-.43-1.84-.46c-.97-.02-1.56.26-1.87.36c-.3.09-.57-.03-.65-.15a.5.5 0 0 1 .02-.56");
}

.y9kojhgwk {
  cx: 70px;
  cy: 24.52px;
  rx: 1.85px;
  ry: 1.79px;
}

.yromiiypm {
  d: path("m103.61 47.94l1.04 1.27l-1.12 5.44l-1.14.12l-4.65 4.05l1-8.51s-.28-.06 1.68-.32c1.95-.25 3.19-2.05 3.19-2.05");
}

.z-717raaq {
  d: path("M107.03 48.13c.49.78-.49 1.55-1.08 1.66c-.58.11-1-.38-1.26-.91c-.49-.97-.87-1.39-1.22-1.56c-.32-.16-.03 2.03-2.18 2.48c-1.24.26-2.28-.62-2.29-1.51c-.01-1.19 2.06-3.13 4.71-3.6c2.49.2 3.08 3.07 3.32 3.44");
}

.zhy9_lb7y {
  fill: var(--svg-color--6d4c41, #6d4c41);
  stroke: var(--svg-color--6d4c41, #6d4c41);
  stroke-miterlimit: 10;
  d: path("m110.46 21.34l-.09-.03l-9.15 40.97a.482.482 0 1 0 .94.22v-.01z");
}

.zpb91f8rg {
  fill: var(--svg-color--875334, #875334);
  d: path("M65.37 27.79a.3.3 0 0 0-.12-.03l-2.57-.05q-.06 0-.12.03c-.23.09-.37.33-.26.59c.1.26.6.99 1.63 1.01s1.56-.69 1.67-.94c.12-.27 0-.51-.23-.61");
}

.zz49ylmdp {
  d: path("M50.58 88.89c-1.64.3-3.18 1.64-3.43 3.29c-.12.82.12 1.64.36 2.43c.65 2.11 1.33 4.2 2.04 6.29c.39 1.14.96 2.43 2.13 2.71c.78.19 1.61-.17 2.18-.74s.92-1.31 1.23-2.05c1.44-3.44 3.12-4.93 3.18-8.65c.07-4.74-4.17-3.91-7.69-3.28");
}

</style>
