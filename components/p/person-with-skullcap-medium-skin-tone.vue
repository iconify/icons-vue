<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jyz0nac_s"/><radialGradient id="SVG4ap4CbPT" cx="93.745" cy="45.308" r="23.544" gradientTransform="matrix(.9899 -.1418 .0697 .4862 -11.485 73.959)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVG4ap4CbPT)" class="xmq6k4b_c"/><radialGradient id="SVGJIpuzc7g" cx="77.912" cy="46.087" r="6.52" gradientTransform="rotate(154.924 83.804 60.54)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGJIpuzc7g)" class="jwjiehadp"/><radialGradient id="SVGohPXWcPw" cx="87.716" cy="58.941" r="23.288" gradientTransform="matrix(-.0746 -.9972 .8311 -.0622 48.065 160.197)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGohPXWcPw)" class="d52xl336r"/><radialGradient id="SVGyYySkePd" cx="93.745" cy="45.308" r="23.544" gradientTransform="matrix(-.9899 -.1418 -.0697 .4862 139.818 73.959)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGyYySkePd)" class="lvk1dubwa"/><radialGradient id="SVGribWpc0N" cx="77.912" cy="46.087" r="6.52" gradientTransform="rotate(25.076 -208.058 -88.3)scale(1 -.7418)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGribWpc0N)" class="b79xof-xt"/><radialGradient id="SVGCvFpUbZl" cx="87.716" cy="58.941" r="23.288" gradientTransform="matrix(.0746 -.9972 -.8311 -.0622 80.268 160.197)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGCvFpUbZl)" class="n70oepr5a"/><linearGradient id="SVGW4ahJuSL" x1="64" x2="64" y1="31.09" y2="4" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="mujsf_8ht"/><stop offset=".494" class="eadiaackc"/><stop offset="1" class="m06zxpakv"/></linearGradient><path fill="url(#SVGW4ahJuSL)" class="uhzznob1v"/><path class="j6b9r7scv"/><path class="po0trqb4l"/><path class="sk73tgbwd"/><path class="i8l4gtbzw"/><path class="nxt8pccip"/><path class="hsu7mj6cf"/><path class="tzhwzt3nh"/><g class="h3iawzbwl"><ellipse class="f5vbzgh4r"/><ellipse class="h4p1kobsj"/></g><path class="ourzaxbna"/><path class="o1bbjhbuy"/><path class="tlsalx15n"/><path class="fz3y6-bvd"/><path class="g-cwp_vyd"/><linearGradient id="SVGd1oISbJP" x1="64" x2="64" y1="120.426" y2="74.398" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ai1a8abib"/><stop offset=".382" class="em-wo1blr"/><stop offset="1" class="yac5kp3-q"/></linearGradient><path fill="url(#SVGd1oISbJP)" class="pcxfdgaki"/><linearGradient id="SVGiosA7cMt" x1="64.002" x2="64.002" y1="117.373" y2="98.511" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="mujsf_8ht"/><stop offset=".494" class="eadiaackc"/><stop offset="1" class="m06zxpakv"/></linearGradient><path fill="url(#SVGiosA7cMt)" class="cvk580bcr"/><linearGradient id="SVGpebe3cPj" x1="63.792" x2="63.792" y1="99.841" y2="74.173" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vlzxxcccm"/><stop offset=".005" class="pz8osybzb"/><stop offset=".117" class="tseifdc7i"/><stop offset=".257" class="y77mn86yk"/><stop offset=".454" class="ontbme8yj"/><stop offset="1" class="fboms9lpk"/></linearGradient><path fill="url(#SVGpebe3cPj)" class="zzp_h5bag"/><linearGradient id="SVGcbCLu6dj" x1="59.967" x2="68.231" y1="96.208" y2="87.944" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="fbeq_z80i"/><stop offset=".02" class="o8ap0dbfq"/><stop offset=".131" class="z2n3k_b_e"/><stop offset=".268" class="vte4slbov"/><stop offset=".462" class="fbjspeb0y"/><stop offset="1" class="gd36nc3sj"/></linearGradient><path fill="url(#SVGcbCLu6dj)" class="qu42p01nq"/><linearGradient id="SVGXQZfntqA" x1="81.63" x2="81.63" y1="28.97" y2="5.06" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ai1a8abib"/><stop offset=".382" class="em-wo1blr"/><stop offset="1" class="yac5kp3-q"/></linearGradient><path fill="url(#SVGXQZfntqA)" class="omwin-awf"/><linearGradient id="SVGsuvxNeXg" x1="45.556" x2="45.556" y1="28.97" y2="5.06" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ai1a8abib"/><stop offset=".382" class="em-wo1blr"/><stop offset="1" class="yac5kp3-q"/></linearGradient><path fill="url(#SVGsuvxNeXg)" class="e36irx9ty"/><path class="j0cd__bus"/><path class="f9rcmf10f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:person-with-skullcap-medium-skin-tone" /></template>
<style>
.ai1a8abib {
  stop-color: var(--svg-color--f44336, #f44336);
}

.b79xof-xt {
  d: path("M34.68 85.72c6.22-8.37-9.84-9.39-9.84-9.39c2.3 2.38 4.78 3.71 4.68 5.26c-.24 3.58-5.07 3.2-5.07 3.2s5.84 5.18 10.23.93");
}

.cvk580bcr {
  d: path("M63.98 7.62s-21.27 6.15-21.27 35.24c0 0 7.91-4.6 21.19-4.6s21.39 4.6 21.39 4.6c0-29.09-21.31-35.24-21.31-35.24");
}

.d52xl336r {
  d: path("M103.73 76.07c-.6.59-17.52-5.79-20.37-13.62c-.58-1.58-1.1-3.21-1.17-4.89c-.05-1.26.14-2.76.87-3.83c.89-1.31 20.18-1.7 20.18-1.7c8.3 9.1 5.44 19.15.49 24.04");
}

.e36irx9ty {
  d: path("M55.32 112.63c-5.58-1.37-10-4.03-13.08-8.1c-1.23-1.63-2.11-3.35-2.75-5.06c-1.16.27-2.31.56-3.42.88a58 58 0 0 0-5.68 1.87V124h30.34v-4.55c0-3.25-2.25-6.04-5.41-6.82");
}

.eadiaackc {
  stop-color: var(--svg-color--f37f21, #f37f21);
}

.em-wo1blr {
  stop-color: var(--svg-color--eb3e34, #eb3e34);
}

.f5vbzgh4r {
  cx: 47.99px;
  cy: 60.69px;
  rx: 4.8px;
  ry: 4.97px;
}

.f9rcmf10f {
  fill: var(--svg-color--da6727, #da6727);
  d: path("m65.99 110.36l13.28-5.42c1.15-.47 1.9-1.59 1.9-2.83V96.7c0-2.17-2.2-3.65-4.21-2.83L64.91 98.8c-.54.22-.89.74-.89 1.32v8.92c0 1.02 1.03 1.71 1.97 1.32");
}

.fbeq_z80i {
  stop-color: var(--svg-color--ff0, #ff0);
}

.fbjspeb0y {
  stop-color: var(--svg-color--ffd800, #ffd800);
}

.fboms9lpk {
  stop-color: var(--svg-color--504f4f, #504f4f);
}

.fz3y6-bvd {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M64.18 16.78h-.17a5.91 5.91 0 0 1-5.9-5.9v-.47c0-3.25 2.65-5.9 5.9-5.9h.17c3.25 0 5.9 2.65 5.9 5.9v.47c.01 3.24-2.65 5.9-5.9 5.9");
}

.g-cwp_vyd {
  fill: var(--svg-color--e59600, #e59600);
  d: path("M64.18 16.78h-.17a5.91 5.91 0 0 1-5.9-5.9v-.47c0-3.25 2.65-5.9 5.9-5.9h.17c3.25 0 5.9 2.65 5.9 5.9v.47c.01 3.24-2.65 5.9-5.9 5.9");
}

.gd36nc3sj {
  stop-color: var(--svg-color--ffd600, #ffd600);
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.h3iawzbwl {
  fill: var(--svg-color--49362e, #49362e);
}

.h4p1kobsj {
  cx: 80.01px;
  cy: 60.69px;
  rx: 4.8px;
  ry: 4.97px;
}

.hsu7mj6cf {
  fill: none;
  d: path("M64 16.19c7.72 0 15.41 4.21 21.1 11.55c6.16 7.94 9.55 18.83 9.55 30.66c0 11.51-3.32 21.1-9.6 27.74c-5.51 5.82-12.99 9.03-21.05 9.03s-15.54-3.21-21.05-9.03c-6.28-6.64-9.6-16.23-9.6-27.74c0-11.83 3.39-22.72 9.55-30.66C48.59 20.4 56.28 16.19 64 16.19m0-2c-16.95 0-32.65 18.13-32.65 44.21c0 25.94 16.17 38.77 32.65 38.77S96.65 84.35 96.65 58.4c0-26.08-15.7-44.21-32.65-44.21");
}

.i8l4gtbzw {
  fill: none;
  d: path("M90.61 54.53c4.65 0 8.43 4.09 8.43 9.11c0 5.03-3.78 9.11-8.43 9.11H37.39c-4.65 0-8.43-4.09-8.43-9.11c0-5.03 3.78-9.11 8.43-9.11zm0-2H37.39c-5.74 0-10.43 5-10.43 11.11s4.69 11.11 10.43 11.11h53.23c5.74 0 10.43-5 10.43-11.11s-4.7-11.11-10.44-11.11");
}

.j0cd__bus {
  fill: var(--svg-color--da6727, #da6727);
  d: path("m62.2 110.36l-13.28-5.42a3.06 3.06 0 0 1-1.9-2.83V96.7c0-2.17 2.2-3.65 4.21-2.83l12.05 4.92c.54.22.89.74.89 1.32v8.92c0 1.03-1.03 1.72-1.97 1.33");
}

.j6b9r7scv {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M64 91.14h-8.85v9.72c0 4.4 3.6 7.96 8.04 7.96h1.61c4.44 0 8.04-3.56 8.04-7.96v-9.72z");
}

.jwjiehadp {
  d: path("M93.65 85.72c-6.22-8.37 9.84-9.39 9.84-9.39c-2.3 2.38-4.78 3.71-4.68 5.26c.24 3.58 5.07 3.2 5.07 3.2s-5.83 5.18-10.23.93");
}

.jyz0nac_s {
  fill: var(--svg-color--543930, #543930);
  d: path("M99.08 82.67c-.87-2.08.43-2.71 3.14-5.11c4.3-3.81 8.63-10.89 4.78-19.93c-2.27-5.34-6.14-7.46-6.14-7.46l-1.11 2.9c-5.54.01-14.64.12-17.6.12h-36c-2.96 0-12.06-.1-17.6-.12l-1.11-2.9s-3.87 2.12-6.14 7.46c-3.85 9.04.49 16.12 4.78 19.93c2.71 2.4 4.01 3.03 3.14 5.11c-.98 2.35-4.8 2.12-4.8 2.12s.65 1.94 2.83 2.92c1.9.85 4.12 1.17 5.69 1.2c.18 0 .44.17.83.53c5.06 4.72 9.04 6.23 21.35 6.61V96h18.06v.05c12.31-.38 16.29-1.89 21.35-6.61c.39-.37.65-.53.83-.53c1.57-.03 3.79-.35 5.69-1.2c2.18-.97 2.83-2.92 2.83-2.92s-3.83.23-4.8-2.12");
}

.lvk1dubwa {
  d: path("M64.48 97.52v-9.45l-28.6-2.26l-2.28 3.49s2.19 1.89 3.15 2.59c1.71 1.25 5 3.11 10.66 3.65z");
}

.m06zxpakv {
  stop-color: var(--svg-color--ed6d23, #ed6d23);
}

.mujsf_8ht {
  stop-color: var(--svg-color--f78c1f, #f78c1f);
}

.n70oepr5a {
  d: path("M24.6 76.07c.6.59 17.52-5.79 20.37-13.62c.58-1.58 1.1-3.21 1.17-4.89c.05-1.26-.15-2.76-.87-3.83c-.89-1.31-20.18-1.7-20.18-1.7c-8.3 9.1-5.44 19.15-.49 24.04");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.nxt8pccip {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M64 14.19c-16.95 0-32.65 18.13-32.65 44.21c0 25.94 16.17 38.77 32.65 38.77S96.65 84.35 96.65 58.4c0-26.08-15.7-44.21-32.65-44.21");
}

.o1bbjhbuy {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M72.2 77.57c-3.1 1.85-13.27 1.85-16.38 0c-1.78-1.06-3.6.56-2.86 2.18c.73 1.59 6.28 5.28 11.07 5.28s10.28-3.69 11-5.28c.75-1.62-1.05-3.24-2.83-2.18");
}

.o8ap0dbfq {
  stop-color: var(--svg-color--fffb00, #fffb00);
}

.omwin-awf {
  d: path("M93.3 100.99c-.71-.22-1.44-.44-2.18-.64c-1.11-.32-2.26-.61-3.42-.88c-.64 1.71-1.52 3.43-2.75 5.06c-3.08 4.07-7.5 6.73-13.08 8.1c-3.16.78-5.41 3.57-5.41 6.82V124H96.8v-21.78c-1.13-.44-2.3-.85-3.5-1.23");
}

.ontbme8yj {
  stop-color: var(--svg-color--525151, #525151);
}

.ourzaxbna {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M67.76 69.69c-.1-.04-.21-.07-.31-.08h-6.89c-.1.01-.21.04-.31.08c-.62.25-.97.9-.67 1.59s1.67 2.62 4.43 2.62s4.14-1.93 4.43-2.62c.29-.68-.06-1.33-.68-1.59");
}

.pcxfdgaki {
  d: path("M101.33 44.78c0-22.24-10.2-37.21-37.33-37.21S26.67 22.54 26.67 44.78c0 3.03.3 5.98.87 8.82c0 0 7.21-11.51 36.46-11.51s36.46 11.51 36.46 11.51c.57-2.84.87-5.79.87-8.82");
}

.po0trqb4l {
  fill: var(--svg-color--d18100, #d18100);
  d: path("M70.85 93.14v7.72c0 3.29-2.71 5.96-6.04 5.96H63.2c-3.33 0-6.04-2.67-6.04-5.96v-7.72zm2-2h-17.7v9.72c0 4.4 3.6 7.96 8.04 7.96h1.61c4.44 0 8.04-3.56 8.04-7.96v-9.72z");
}

.pz8osybzb {
  stop-color: var(--svg-color--747474, #747474);
}

.qu42p01nq {
  d: path("M65.35 41.29h-2.49c-2.19 0-3.99-1.8-3.99-3.99v-2.76c0-2.19 1.8-3.99 3.99-3.99h2.49c2.19 0 3.99 1.8 3.99 3.99v2.76c0 2.2-1.8 3.99-3.99 3.99");
}

.sk73tgbwd {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M90.61 52.53H37.39c-5.74 0-10.43 5-10.43 11.11s4.69 11.11 10.43 11.11h53.23c5.74 0 10.43-5 10.43-11.11s-4.7-11.11-10.44-11.11");
}

.tlsalx15n {
  fill: var(--svg-color--543930, #543930);
  d: path("M31.43 34.88c-3.01 6.09-2.07 17.75-2.07 17.75c-.62 10.72 2.76 15.92 2.76 15.92s4.2-18.41 3.81-21.22c0 0 7.74-1.54 16.53-6.57c5.94-3.4 10-7.39 16.67-8.89c10.16-2.29 12.43 5.07 12.43 5.07s9.4-1.81 12.24 11.25c1.17 5.37 1.67 14.34 2.3 19.8c-.06-.47 3.49-6.38 4.11-12.38c.23-2.23 1.68-7.28-1.28-14.21c-3.56-8.33.22-27.3-28.64-30.52s-35.98 18.17-38.86 24");
}

.tseifdc7i {
  stop-color: var(--svg-color--646363, #646363);
}

.tzhwzt3nh {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M55.21 51.63c-.92-1.22-3.07-3.01-7.22-3.01s-6.29 1.78-7.22 3.01c-.41.54-.31 1.17-.02 1.54c.26.35 1.04.68 1.9.39s2.53-1.16 5.34-1.18c2.81.02 4.48.89 5.34 1.18s1.63-.03 1.9-.39c.28-.37.39-.99-.02-1.54m32.01 0c-.92-1.22-3.07-3.01-7.22-3.01s-6.29 1.78-7.22 3.01c-.41.54-.31 1.17-.02 1.54c.26.35 1.04.68 1.9.39s2.53-1.16 5.34-1.18c2.81.02 4.48.89 5.34 1.18s1.63-.03 1.9-.39c.29-.37.39-.99-.02-1.54");
}

.uhzznob1v {
  d: path("M114.64 121.31V124H13.36v-2.69c0-17.31 25.82-24.37 50.64-24.4c8.13-.01 16.34.84 23.7 2.56c1.16.27 2.31.56 3.42.88a58 58 0 0 1 5.68 1.87c10.57 4.03 17.84 10.39 17.84 19.09");
}

.vlzxxcccm {
  stop-color: var(--svg-color--757575, #757575);
}

.vte4slbov {
  stop-color: var(--svg-color--ffdf00, #ffdf00);
}

.xmq6k4b_c {
  d: path("M63.85 97.52v-9.45l28.6-2.26l2.28 3.49s-2.19 1.89-3.14 2.59c-1.71 1.25-5 3.11-10.66 3.65z");
}

.y77mn86yk {
  stop-color: var(--svg-color--585858, #585858);
}

.yac5kp3-q {
  stop-color: var(--svg-color--d32f2f, #d32f2f);
}

.z2n3k_b_e {
  stop-color: var(--svg-color--ffea00, #ffea00);
}

.zzp_h5bag {
  d: path("M102.52 38.33c-2.66-2.38-13.33-10.15-38.64-10.17c-25.31.01-36.01 7.78-38.67 10.17c-1.48 1.33-1.5 3.13-1.5 4.37v.05l.25 6.86c.1 1.14.39 2.71 1.92 3.59c.73.42 1.55.64 2.38.64c.65 0 1.28-.13 1.88-.39c2.09-.89 3.9-2.1 5.65-3.28c4.45-2.98 10.29-5.89 28.19-5.9c17.9 0 23.74 2.91 28.19 5.9c1.75 1.17 3.56 2.38 5.65 3.28c.6.26 1.24.39 1.89.39c.83 0 1.66-.22 2.39-.64c1.53-.88 1.61-2.45 1.71-3.59l.07-6.86v-.05c-.01-1.25.12-3.05-1.36-4.37");
}

</style>
