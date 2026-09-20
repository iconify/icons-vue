<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGidL9AcgO" x1="181.152" x2="210.317" y1="182.727" y2="197.875" gradientTransform="rotate(192.075 137.187 138.735)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGidL9AcgO)" class="y7hp08v5w"/><g class="cnjyhhbwn"><path class="r-o_7kcyf"/><path class="azl6zwbdg"/></g><linearGradient id="SVGNkDDbIve" x1="195.165" x2="238.754" y1="252.46" y2="211.435" gradientTransform="rotate(194.277 141.156 147.884)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGNkDDbIve)" class="pd_bth0yw"/><g class="cnjyhhbwn"><path class="vifvhmb6s"/><path class="vt7pioxhb"/></g><linearGradient id="SVGJ2QUDcHH" x1="1662.647" x2="1691.812" y1="-134.19" y2="-119.042" gradientTransform="rotate(167.925 -830.705 65.384)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGJ2QUDcHH)" class="hby83vbct"/><g class="cnjyhhbwn"><path class="hnzhkj9_i"/><path class="pcrft3yca"/></g><linearGradient id="SVGViDsweYy" x1="1663.963" x2="1707.552" y1="-118.996" y2="-160.022" gradientTransform="rotate(165.723 -834.674 61.03)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGViDsweYy)" class="vdjkmvb0a"/><g class="cnjyhhbwn"><path class="rrexejbhj"/><path class="zhitf1lrl"/></g><linearGradient id="SVGrUKgXdvA" x1="46.523" x2="57.631" y1="34.175" y2="34.175" gradientTransform="rotate(185.463 1.619 62.523)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGrUKgXdvA)" class="nebnbfbwy"/><linearGradient id="SVGaXiFddAa" x1="68.859" x2="67.619" y1="64.867" y2="35.822" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGaXiFddAa)" class="im0wcqakk"/><linearGradient id="SVGunKkWc5w" x1="62.482" x2="70.505" y1="38.594" y2="37.827" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="r2o_cv-as"/></linearGradient><path fill="url(#SVGunKkWc5w)" class="lmzzrvowm"/><linearGradient id="SVGD5VSDcQu" x1="59.639" x2="48.639" y1="61.903" y2="9.569" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGD5VSDcQu)" class="rlii_hu5p"/><linearGradient id="SVGDH2lVbgN" x1="51.263" x2="19.433" y1="70.105" y2="70.105" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGDH2lVbgN)" class="y3mkxlbwj"/><linearGradient id="SVGoJvK5Gwz" x1="76.658" x2="102.615" y1="74.615" y2="74.615" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGoJvK5Gwz)" class="pksabwa6j"/><linearGradient id="SVGLzyIhezD" x1="107.282" x2="99.677" y1="82.707" y2="77.73" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGLzyIhezD)" class="pntnc2bla"/><linearGradient id="SVGRjbANdvC" x1="98.832" x2="102.144" y1="77.973" y2="76.758" gradientTransform="rotate(171.118 1.075 73.16)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="r2o_cv-as"/><stop offset="1" class="s6rm2gd3x"/></linearGradient><path fill="url(#SVGRjbANdvC)" class="jdym93bgl"/><path class="sray88kjm"/><path class="vk_0_0bmz"/><path class="qpoil6vnu"/><linearGradient id="SVGaGZkCcSs" x1="64" x2="64" y1="100.863" y2="53.246" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ud_ztjbwi"/><stop offset=".022" class="k5z4crbis"/><stop offset=".301" class="h62rqbc3q"/><stop offset=".565" class="ow7kfccqs"/><stop offset=".805" class="zrec46bkw"/><stop offset="1" class="o_bi82bgg"/></linearGradient><path fill="url(#SVGaGZkCcSs)" class="cs8erbb5o"/><linearGradient id="SVGR7n4aeap" x1="63.925" x2="63.925" y1="39.409" y2="48.317" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".63" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGR7n4aeap)" class="k3yiyacql"/><path class="q1h46ybph"/><path class="i69pcng0v"/><path class="twtb-tw5d"/><g class="edr3jwbtv"><ellipse transform="rotate(-88.802 57.98 24.212)" class="iw0rafbvb"/><ellipse transform="rotate(-88.802 70.055 24.464)" class="gwcidn3kj"/></g><path class="g-mn6hbsr"/><path class="q5jafebjn"/><path class="euzy0_pwd"/><linearGradient id="SVGTt7ZxbBg" x1="104.379" x2="108.704" y1="77.316" y2="77.316" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGTt7ZxbBg)" class="o5v8zkmit"/><linearGradient id="SVGA0MWqApP" x1="104.379" x2="108.704" y1="79.451" y2="79.451" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGA0MWqApP)" class="xp3trfblt"/><linearGradient id="SVGfDTpje6l" x1="104.379" x2="108.704" y1="81.797" y2="81.797" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGfDTpje6l)" class="x2fby4bgy"/><linearGradient id="SVGvURL4bFC" x1="104.379" x2="108.704" y1="83.785" y2="83.785" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGvURL4bFC)" class="d0jmyfbcv"/><path class="kig7n3cto"/><linearGradient id="SVGzNVb9dyE" x1="106.212" x2="100.351" y1="83.832" y2="80.483" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset=".575" class="jb0j4_2gw"/></linearGradient><path fill="url(#SVGzNVb9dyE)" class="sx4o3sb2r"/><path class="csws88ujn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:man-fairy-tone1" /></template>
<style>
.awx491bun {
  stop-color: var(--svg-color--ffa6c9, #ffa6c9);
}

.azl6zwbdg {
  d: path("M95.31 80.89c-1.81-6.25-4.28-8.96-6.43-12.49");
}

.cnjyhhbwn {
  fill: none;
  stroke: var(--svg-color--87cdde, #87cdde);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-956px, 0.956px);
}

.cs8erbb5o {
  d: path("m76.33 53.51l.14 15.76L68 75.88c-.8.44-1.7.67-2.61.67c-.88.01-1.75-.19-2.54-.58l-11.01-6.48l-.13-15.77l-7.64-6.97s1.05-4.06 8.4-6.3c2.7-.82 6.25-1.4 10.91-1.44c5.15-.04 9.06.59 12 1.51c6.97 2.16 8.55 5.88 8.55 5.88z");
}

.csws88ujn {
  fill: var(--svg-color--edbd82, #edbd82);
  d: path("M100.41 49.91c1.43.24 2.87-.93 3.29-2.32l.04-.13l.02-.07c.01-.03.02-.06 0 0c-.03.07-.11.12-.18.12c-.07.01-.18-.07-.19-.12l.23.47c.16.31.33.61.51.91c.31.56.85 1.36 1.76 1.41c.85.04 1.72-.69 1.57-1.63c-.17-.71-.43-1.37-.83-1.96c-.79-1.17-1.29-2.18-2.9-1.98c1.37.19 1.96 1.03 2.54 2.2c.3.58.53 1.22.65 1.84c.08.47-.49.96-.98.89c-.25-.02-.49-.14-.7-.34c-.21-.19-.36-.47-.54-.76c-.17-.29-.33-.58-.49-.88l-.23-.44c-.04-.12-.23-.26-.39-.25c-.16 0-.32.1-.39.24c-.04.09-.03.11-.04.12l-.01.06l-.03.11c-.17.61-.51 1.16-.96 1.6c-.23.21-.51.39-.8.52c-.32.14-.63.21-.95.39");
}

.d0jmyfbcv {
  d: path("M103.46 46.8c.15.65.8 1.06 1.45.91l2.68-.62a1.23 1.23 0 0 0 .91-1.46c-.15-.65-.8-1.06-1.45-.91l-2.68.62c-.66.15-1.05.8-.91 1.46");
}

.edr3jwbtv {
  fill: var(--svg-color--312d2d, #312d2d);
}

.euzy0_pwd {
  fill: var(--svg-color--20d39e, #20d39e);
  d: path("M64.45 4.22s-.01 0 0 0h-.01c-16.7-.26-13.68 18.87-13.68 18.87s.57 2.36 1.14 3.4c0-2.67 1.83-7.48 2.62-9.47c.4-1 1.46-1.57 2.52-1.36c1.63.33 4.23.75 7.1.81h.06c2.87.06 5.49-.25 7.13-.51a2.24 2.24 0 0 1 2.47 1.46c.71 2.02 2.2 6.79 2.25 9.42c.63-.5 1.26-3.2 1.26-3.2S81.14 4.66 64.45 4.22");
}

.g-mn6hbsr {
  fill: var(--svg-color--dba689, #dba689);
  d: path("M65.37 27.77a.3.3 0 0 0-.12-.03l-2.6-.05q-.06 0-.12.03c-.24.09-.37.33-.27.59c.11.26.61 1 1.65 1.02s1.58-.7 1.69-.95c.12-.27 0-.51-.23-.61");
}

.gsabqfbpm {
  stop-color: var(--svg-color--abe1e1, #abe1e1);
}

.gwcidn3kj {
  cx: 70.05px;
  cy: 24.46px;
  rx: 1.87px;
  ry: 1.81px;
}

.h62rqbc3q {
  stop-color: var(--svg-color--20d0a3, #20d0a3);
}

.hby83vbct {
  d: path("M24.38 85.2c11.04 11.24 47.55-18.37 39.7-24.6c-9.49-7.54-54.74 9.29-39.7 24.6");
}

.hnzhkj9_i {
  d: path("M25.39 80.43c8.97-10.2 17.84-14.49 30.11-20.32c.28-.13.6-.33.58-.64s-.64-.29-.51-.01M39.54 80.89c3.72-2.49 15.7-13.97 22.79-21.7l-.49.34");
}

.i69pcng0v {
  fill: var(--svg-color--f9ddbd, #f9ddbd);
  d: path("M64.39 6.8C58 6.67 51.93 13.38 51.73 23.22c-.21 9.78 5.79 14.75 12 14.88s12.41-4.58 12.62-14.36c.21-9.84-5.57-16.8-11.96-16.94");
}

.im0wcqakk {
  d: path("m55.64 90.21l13-4.42c0-.43-4.1-11.29-4.1-11.29l8.23-14.6c1.75 3.3 7.11 18.7 8.84 26.71c.65 3.01-.48 6.94-4.98 8.11c-5.02 1.3-9.87 1.92-16.25 2.58c-6.37.66-8.57-5.38-4.74-7.09");
}

.iw0rafbvb {
  cx: 57.98px;
  cy: 24.21px;
  rx: 1.87px;
  ry: 1.81px;
}

.jb0j4_2gw {
  stop-color: var(--svg-color--f9ddbd, #f9ddbd);
}

.jdym93bgl {
  d: path("m103.61 47.87l1.04 1.27l-1.12 5.44l-1.14.12l-4.65 4.05l1-8.51s-.28-.06 1.68-.32c1.95-.26 3.19-2.05 3.19-2.05");
}

.k3yiyacql {
  d: path("M68.17 39.18V34.6h-8.68v4.58c-2.81.24-5.12.69-7.01 1.26c.88 3.35 5.03 6.97 11.56 6.92c6.35-.05 10.39-3.56 11.35-6.85c-1.96-.61-4.34-1.09-7.22-1.33");
}

.k5z4crbis {
  stop-color: var(--svg-color--29b9c6, #29b9c6);
}

.kig7n3cto {
  fill: var(--svg-color--edbd82, #edbd82);
  d: path("M107.65 51.9c-.46-.34-.96-.47-1.46-.56c-.51-.07-1.02-.09-1.57.08c.46.34.96.48 1.46.56c.51.07 1.02.09 1.57-.08m.19-2.45c-.49-.25-.98-.31-1.47-.31c-.49.01-.98.08-1.46.35c.49.26.98.31 1.47.31c.48-.02.97-.09 1.46-.35m-3.07-1.64c.59.11 1.13.02 1.66-.11c.52-.15 1.03-.35 1.49-.74c-.59-.11-1.13-.03-1.66.11c-.52.15-1.03.35-1.49.74");
}

.lmzzrvowm {
  d: path("m68.64 85.79l-10.37 3.52l1.38 8.02s7.55-.6 11.85-1.51c4.3-.9-2.86-10.03-2.86-10.03");
}

.ltgl6j0rh {
  stop-color: var(--svg-color--ccc9d8, #ccc9d8);
}

.m5aiqz05p {
  stop-color: var(--svg-color--93f1e8, #93f1e8);
}

.nebnbfbwy {
  d: path("M50.58 88.82c-1.64.3-3.18 1.64-3.43 3.29c-.12.82.12 1.64.36 2.43c.65 2.11 1.33 4.2 2.04 6.28c.39 1.14.96 2.43 2.13 2.71c.78.19 1.61-.17 2.18-.74s.92-1.31 1.23-2.05c1.44-3.44 3.12-4.93 3.18-8.65c.07-4.74-4.17-3.91-7.69-3.27");
}

.o_bi82bgg {
  stop-color: var(--svg-color--15ed76, #15ed76);
}

.o5v8zkmit {
  d: path("M104.05 52.19c-.16.66.25 1.33.9 1.48l1.69.41a1.224 1.224 0 1 0 .58-2.38l-1.69-.41a1.21 1.21 0 0 0-1.48.9");
}

.ow7kfccqs {
  stop-color: var(--svg-color--1ae08a, #1ae08a);
}

.pcrft3yca {
  d: path("M31.5 81.54c1.08-3.71 10.56-12.46 12.57-15.75");
}

.pd_bth0yw {
  d: path("M118.54 35.52c6.64 19.8-55.96 37.47-58.55 26.1c-3.57-15.61 50.34-50.56 58.55-26.1");
}

.pksabwa6j {
  d: path("M104.34 49.19c-.08-.09-.17-.17-.26-.26a2.69 2.69 0 0 0-2.8-.48c-1.25.49-5.64 3.46-6.71 4.1l-5.04 3.03l-5.86-9.76l-9.25 4.78l10.65 12.45c1.14 1.71 3.57 2.44 5.39 1.48c0 0 .08-.06.21-.15c.27-.12.54-.28.78-.46c3.08-2.44 9.6-7.91 10.56-8.83c1.49-1.47 4.27-3.79 2.33-5.9");
}

.pntnc2bla {
  d: path("M106.38 53.59c-1.68 1.36-5.35 1.1-6.94-1.5c-2.88-4.72 2.68-7.65 4.84-7.5c2.25.16 5.72 6.17 2.1 9");
}

.q1h46ybph {
  fill: var(--svg-color--edc391, #edc391);
  d: path("m74.12 21.47l-2.71-.06l-14.66-.31l-2.71-.06c-2.16-.05-3.97 1.8-4.02 4.11s1.68 4.23 3.85 4.27l2.71.06l14.66.31l2.71.06c2.16.05 3.97-1.8 4.02-4.11c.05-2.3-1.68-4.22-3.85-4.27");
}

.q5jafebjn {
  fill: var(--svg-color--444, #444);
  d: path("M67.14 30.77c-1.18.67-5.02.59-6.18-.13c-.66-.41-1.36.18-1.1.8c.26.61 2.33 2.04 4.13 2.08c1.81.04 3.9-1.31 4.19-1.91c.31-.6-.36-1.22-1.04-.84");
}

.qpoil6vnu {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M104.55 50.74c.22-.05.38-.12.56-.26l-.79 3.89l-1.85.06l.93-4.17c.31.27.67.59 1.15.48");
}

.r-o_7kcyf {
  d: path("M102.66 82.21C94.56 70.73 85.45 65.19 72.5 60.1c-.29-.11-.6-.33-.58-.64s.64-.29.51-.01m20.39 25.21c-2.44-.98-20.06-17.74-27.16-25.47l.49.34");
}

.r2o_cv-as {
  stop-color: var(--svg-color--f9ddbd, #f9ddbd);
  stop-opacity: 0;
}

.r8ludbcjj {
  stop-color: var(--svg-color--80ffee, #80ffee);
}

.rlii_hu5p {
  d: path("M65.46 74.38c-.3-4.5-1.21-9.32-2.13-13.95l-.42-.26l-11.06 8.87l-1.49 24.46l-3.22 15.87c-1.56.2-3.17.85-3.78 2.27c-.32.76-.3 1.62-.26 2.45c.1 2.2.23 4.4.4 6.6c.09 1.2.32 2.59 1.38 3.16c.71.38 1.6.24 2.29-.17c.69-.4 1.22-1.04 1.7-1.67c1.47-1.94 3.65-6.32 3.65-6.32s6.21-11.51 8.47-19.36c3.12-10.88 4.32-21.98 4.47-21.95");
}

.rrexejbhj {
  d: path("M17.26 29.35c18.27 6.95 32.96 17.46 46.58 31.14M13.11 39.11C28.5 51.57 43.73 56.17 63.01 61.6");
}

.s6rm2gd3x {
  stop-color: var(--svg-color--ffd29c, #ffd29c);
}

.sray88kjm {
  fill: var(--svg-color--6d4c41, #6d4c41);
  stroke: var(--svg-color--6d4c41, #6d4c41);
  stroke-miterlimit: 10;
  d: path("m110.46 21.27l-.09-.03l-9.15 40.97a.482.482 0 1 0 .94.22v-.01z");
}

.sx4o3sb2r {
  d: path("M107.03 48.06c.49.78-.49 1.55-1.08 1.66c-.58.11-1-.38-1.26-.91c-.49-.97-.87-1.39-1.22-1.56c-.32-.16-.03 2.03-2.18 2.48c-1.24.26-2.28-.62-2.29-1.51c-.01-1.19 2.06-3.13 4.71-3.6c2.49.2 3.08 3.06 3.32 3.44");
}

.sxvxm2bwq {
  stop-color: var(--svg-color--f7accb, #f7accb);
}

.twtb-tw5d {
  fill: var(--svg-color--454140, #454140);
  d: path("M72.89 21.51s-.82-1.37-2.76-1.4s-2.8 1.32-2.8 1.32c-.07.1-.11.22-.12.35c0 .33.25.6.57.6c.07 0 .23-.05.24-.05c1.17-.48 2.08-.47 2.08-.47s.9.02 2.06.53c.01.01.18.06.24.06c.32 0 .58-.26.59-.59c0-.13-.04-.25-.1-.35m-12.1-.17s-.82-1.37-2.76-1.4c-1.95-.03-2.8 1.32-2.8 1.32c-.07.1-.11.22-.12.35c0 .33.25.6.57.6c.07 0 .23-.05.24-.05c1.17-.48 2.08-.47 2.08-.47s.9.02 2.06.53c.01.01.18.06.24.06c.32 0 .58-.26.59-.59a.53.53 0 0 0-.1-.35");
}

.u_ug8ubbn {
  stop-color: var(--svg-color--85fced, #85fced);
}

.ud_ztjbwi {
  stop-color: var(--svg-color--2ab7c9, #2ab7c9);
}

.vdjkmvb0a {
  d: path("M9.47 33.3C2.82 53.1 65.42 70.78 68.02 59.4C71.58 43.8 17.67 8.84 9.47 33.3");
}

.vifvhmb6s {
  d: path("M110.46 31.56C92.2 38.51 77.77 49.02 64.15 62.7m51.62-25.23c-15.38 12.46-31.5 20.92-50.79 26.35");
}

.vk_0_0bmz {
  fill: var(--svg-color--ffd600, #ffd600);
  d: path("m111.39 14.69l-2.5 3.44l-4.24-.11l2.5 3.44l-1.41 4.01l4.04-1.32l3.37 2.58v-4.25l3.5-2.41l-4.05-1.31z");
}

.vt7pioxhb {
  d: path("M97.43 31.02c-5.33 4.8-7.72 8.38-10.12 12.42m26.43-10.18c-4.72 3.95-8.3 7.58-10.26 13.35m-12.06 6.76c-5.97 1.22-10.36 1.32-15.62-.61");
}

.x2fby4bgy {
  d: path("M103.98 48.17s.55 1.3 1.21 1.3l2.52-.01c.67-.01 1.21-.55 1.2-1.22v-.1c0-.67-.55-1.21-1.22-1.2l-2.52.01c-.66.01-1.2.55-1.19 1.22");
}

.xp3trfblt {
  d: path("M104.14 50.31c-.07.68.43 1.28 1.11 1.35l2.26.23c.68.07 1.28-.43 1.35-1.11s-.43-1.28-1.11-1.35l-2.26-.23c-.68-.06-1.28.43-1.35 1.11");
}

.y3mkxlbwj {
  d: path("M30.01 75.09c-2.86-.68-5.05-1.69-6.54-2.19c-1.5-.5-1.55-3.35 1.59-2.43c1.79.52 1.08-.68-.39-1.45c-1.47-.78-5.2 1.08-6.08.25c-.61-.57-.52-1.39-.18-1.7c1.15-1.02 3.9-1.99 6.32-1.88c2.16.1 5.55 3.29 7.63 2.74c.01 0 3.97-7.04 7.59-13.47l5.86-10.41l10.88 4.62s-18.5 21.87-19.47 22.77c-2.17 2.01-4.17 3.87-7.21 3.15");
}

.y7hp08v5w {
  d: path("M103.62 85.2c-11.04 11.24-47.55-18.37-39.7-24.6c9.49-7.54 54.74 9.29 39.7 24.6");
}

.zhitf1lrl {
  d: path("M29.36 29.5c4.23 2.82 6.09 4.91 7.84 9.61m-20.43-5.36c4.72 3.95 7.3 8.23 9.26 14m4.91-5.03c7.32 3.4 16.19 9.65 21.26 9.82");
}

.zrec46bkw {
  stop-color: var(--svg-color--16ea7b, #16ea7b);
}

</style>
