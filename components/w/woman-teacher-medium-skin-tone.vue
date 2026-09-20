<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGLEr5UsId" x1="63.999" x2="63.999" y1="116.605" y2="39.511" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="enyuzabou"/><stop offset="1" class="o-oe42blr"/></linearGradient><path fill="url(#SVGLEr5UsId)" class="zj2v9acmv"/><linearGradient id="SVGlqVRqcbK" x1="63.999" x2="63.999" y1="119.455" y2="37.224" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j1_fzqjbi"/><stop offset=".779" class="hedll2xbz"/></linearGradient><path fill="url(#SVGlqVRqcbK)" class="nz2dn-lcw"/><path class="afgjgibhm"/><radialGradient id="SVGqPQObcyK" cx="64" cy="69.561" r="47.532" gradientTransform="matrix(1 0 0 -1.1901 0 141.221)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGqPQObcyK)" class="egor6rvyi"/><linearGradient id="SVGCy6SEdjI" x1="64" x2="64" y1="18.343" y2="4.85" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="qt2whjved"/><stop offset="1" class="l3v2272-w"/></linearGradient><path fill="url(#SVGCy6SEdjI)" class="a5wy59b0z"/><path class="acvnqzbyb"/><linearGradient id="SVGlRYp0dKt" x1="30.39" x2="30.39" y1="32.297" y2="4.991" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xb94qyb-t"/><stop offset=".705" class="ci_fo_bpd"/><stop offset="1" class="u3kz4vb7l"/></linearGradient><path fill="url(#SVGlRYp0dKt)" class="i0o35jb7h"/><linearGradient id="SVG8XNZL1QH" x1="98" x2="98" y1="30.994" y2="5.033" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xb94qyb-t"/><stop offset=".705" class="ci_fo_bpd"/><stop offset="1" class="u3kz4vb7l"/></linearGradient><path fill="url(#SVG8XNZL1QH)" class="xkx9frfii"/><linearGradient id="SVGy96TccvT" x1="39.001" x2="39.001" y1="29" y2="5.422" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ranfy3p3c"/><stop offset=".785" class="upuoffbeu"/></linearGradient><path fill="url(#SVGy96TccvT)" class="m4a924hba"/><linearGradient id="SVG7C1rgdfp" x1="997.477" x2="997.477" y1="30.237" y2="5.612" gradientTransform="matrix(-1 0 0 -1 1086.477 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ranfy3p3c"/><stop offset=".785" class="upuoffbeu"/></linearGradient><path fill="url(#SVG7C1rgdfp)" class="bel2dzi_t"/><path class="vn5d0lb8b"/><linearGradient id="SVGAJYXsdPv" x1="54.339" x2="55.176" y1="16.875" y2="37.154" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="lr0geib8f"/><stop offset="1" class="ibo9lk-wv"/></linearGradient><path fill="url(#SVGAJYXsdPv)" class="ub1b6o8az"/><linearGradient id="SVGa7xHtbnC" x1="72.97" x2="73.807" y1="16.106" y2="36.385" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="lr0geib8f"/><stop offset="1" class="ibo9lk-wv"/></linearGradient><path fill="url(#SVGa7xHtbnC)" class="b4upy61uu"/><linearGradient id="SVGAWn9ye5j" x1="79.15" x2="72.817" y1="21.117" y2="-5.55" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".002" class="bm8-i2rdi"/><stop offset="1" class="aigw4_ass"/></linearGradient><path fill="url(#SVGAWn9ye5j)" class="aqfzubmzy"/><path class="dz00ggcqz"/><linearGradient id="SVGNzyutduh" x1="81.888" x2="76.721" y1="17.259" y2="-.074" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o-m18bc6g"/><stop offset="1" class="pqgvm3vez"/></linearGradient><path fill="url(#SVGNzyutduh)" class="wj96wn2ud"/><path class="l4pe8zbpz"/><linearGradient id="SVGGzkFacME" x1="-117.44" x2="-73.995" y1="-972.312" y2="-972.312" gradientTransform="matrix(.9612 .2758 -.3192 1.1123 -136.555 1216.41)" gradientUnits="userSpaceOnUse"><stop offset=".01" class="ip0ngccya"/><stop offset=".987" class="sl8ua6bht"/></linearGradient><path fill="url(#SVGGzkFacME)" class="gb_-h-blg"/><defs><path id="SVGfa9HKe7y" class="fikz1yblj"/></defs><clipPath id="SVGqACuHbTS"><use href="#SVGfa9HKe7y"/></clipPath><linearGradient id="SVG7NgeSbei" x1="52.555" x2="56.93" y1="5.954" y2="19.704" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset="1" class="a72as_i6q"/></linearGradient><path fill="url(#SVG7NgeSbei)" clip-path="url(#SVGqACuHbTS)" class="z_mp1oy8k"/><path class="yenhdubmr"/><path class="i1-x5onrx"/><g class="h3iawzbwl"><ellipse class="na7hbybaj"/><ellipse class="x68zbhbtu"/></g><path class="s7g1vnbdm"/><path class="g-l6h3kdx"/><path class="s724_2bvk"/><path class="ucf53pbfm"/><radialGradient id="SVG1mFK2dRz" cx="64.333" cy="65.537" r="49.788" gradientTransform="matrix(1 0 0 -1.2135 0 141.995)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVG1mFK2dRz)" class="cskp51b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:woman-teacher-medium-skin-tone" /></template>
<style>
.a5wy59b0z {
  d: path("M114.5 123.94v-3.18c0-15.47-25.34-23.56-50.36-23.56H64c-25.14.03-50.5 7.32-50.5 23.56v3.18z");
}

.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.acvnqzbyb {
  fill: var(--svg-color--3488c1, #3488c1);
  d: path("M15 123.94v-3.18c0-15.2 24.61-22.03 49-22.06h.13c12.9 0 25.42 2.19 34.36 6c6.62 2.83 14.51 7.91 14.51 16.05v3.18h3v-3.18C116 104 89.74 95.7 64.13 95.7H64c-25.49.03-52 7.28-52 25.06v3.18z");
}

.afgjgibhm {
  fill: var(--svg-color--543930, #543930);
  d: path("M64.57 2.87c-41.01 0-40.68 37.92-40.68 38.52c0 24.56 1.88 59.25 11.71 72.9c3.9 5.41 11.43 5.71 11.43 5.71l16.97-.02l16.97.02s7.54-.3 11.43-5.71c9.83-13.65 11.71-48.34 11.71-72.9c-.01-.6 1.47-38.52-39.54-38.52");
}

.aigw4_ass {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0.6;
}

.aqfzubmzy {
  d: path("m100.99 123.94l.76-2.65l.63-2.18l-.06-.02l.01-.05l-1.55-.44l1.64-5.72c.1-.35.09-.7 0-1.02c0-.01-.01-.03-.01-.04a.3.3 0 0 0-.04-.1c-.17-.54-.56-.97-1.09-1.13l-.15-.04h-.01l-3.75-1.08l-34.93-10.05c-.05-.01-.09-.01-.13-.03a6.177 6.177 0 0 0-7.51 4.27l-1.44 5.03q-.15.51-.33 1.11l-1.32 4.61l-2.74 9.53z");
}

.b4upy61uu {
  d: path("m74.21 91.88l-9.98 12.81s-.5-.38 0 0l16.23 6.64l2.41-14.54z");
}

.bel2dzi_t {
  d: path("M92.56 123.94c-.01-4.89-.53-14.67-3.75-25.85l-3.38-.82c3.54 11.43 4.09 21.73 4.12 26.67z");
}

.bm8-i2rdi {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0.2;
}

.ci_fo_bpd {
  stop-color: var(--svg-color--5914f2, #5914f2);
}

.cskp51b_e {
  d: path("M64.57 2.87c-41.01 0-40.68 37.92-40.68 38.52c0 7.76.19 16.53.75 25.32l6.72-.02c-.06-2.92 1.99-20.97 8.08-22.34c22.36-5.03 35.01-16.89 35.01-16.89c3.29 7.18 13.58 14.19 17.27 16.86c3.03 2.19 4.58 18.55 4.52 22.38h7.09c0-.05.02-.1.02-.16c.56-8.75.74-17.46.74-25.17c.01-.58 1.49-38.5-39.52-38.5");
}

.dz00ggcqz {
  fill: var(--svg-color--424242, #424242);
  d: path("m102.29 123.94l3.46-12.06c.29-1.01-.29-2.06-1.3-2.34l-38.69-11.1a6.19 6.19 0 0 0-7.65 4.24l-6.1 21.27z");
}

.egor6rvyi {
  d: path("M64.57 2.87c-41.01 0-40.68 37.92-40.68 38.52c0 24.56 1.88 59.25 11.71 72.9c3.9 5.41 11.43 5.71 11.43 5.71l16.97-.02l16.97.02s7.54-.3 11.43-5.71c9.83-13.65 11.71-48.34 11.71-72.9c-.01-.6 1.47-38.52-39.54-38.52");
}

.enyuzabou {
  stop-color: var(--svg-color--26a69a, #26a69a);
}

.fikz1yblj {
  d: path("m105.67 118.03l-44.5-12.66c-3.53-1-3.9.22-4.81 3.43l-4.34 15.18l51.97-.02z");
}

.g-l6h3kdx {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M72.62 76.14c-3.15 1.87-13.47 1.87-16.61 0c-1.81-1.07-3.65.57-2.9 2.21c.74 1.61 6.37 5.36 11.23 5.36s10.42-3.75 11.16-5.36c.75-1.64-1.07-3.29-2.88-2.21");
}

.gb_-h-blg {
  d: path("m103.37 112.12l-39.8-11.42c-1.08-.31-2.26.46-2.62 1.71l-.06.22c-.36 1.25.23 2.53 1.31 2.84l39.8 11.42s-.34-.83.07-2.3c.41-1.48 1.3-2.47 1.3-2.47");
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.h3iawzbwl {
  fill: var(--svg-color--49362e, #49362e);
}

.hedll2xbz {
  stop-color: var(--svg-color--795548, #795548);
}

.i0o35jb7h {
  d: path("M12 120.75v3.18h32.6c.78-21.78 4.18-28.01 4.18-28.01C31.83 99.62 12.75 104 12 120.75");
}

.i1-x5onrx {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M68.37 68.06c-.11-.04-.21-.07-.32-.08h-6.99c-.11.01-.21.04-.32.08c-.63.26-.98.91-.68 1.61s1.69 2.66 4.49 2.66s4.19-1.96 4.5-2.66c.3-.7-.05-1.36-.68-1.61");
}

.ibo9lk-wv {
  stop-color: var(--svg-color--81d4fa, #81d4fa);
}

.ip0ngccya {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
}

.j1_fzqjbi {
  stop-color: var(--svg-color--8d6e63, #8d6e63);
}

.l3v2272-w {
  stop-color: var(--svg-color--70afe3, #70afe3);
}

.l4pe8zbpz {
  fill: var(--svg-color--424242, #424242);
  d: path("M64.33 101.57c.18 0 .38.02.59.07l37.25 10.7l-.31 1.08c-11.79-3.29-34.29-9.62-38.94-11.16c.24-.33.71-.69 1.41-.69m0-3.33c-4.52 0-6.78 5.57-3.12 6.94c4.03 1.5 42.93 12.32 42.93 12.32l1.58-5.52c.31-1.06-.19-2.14-1.11-2.4L65.77 98.42q-.75-.18-1.44-.18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lr0geib8f {
  stop-color: var(--svg-color--e1f5fe, #e1f5fe);
}

.m4a924hba {
  d: path("M38.45 123.94c.03-4.94.58-15.24 4.12-26.67l-3.38.82c-3.22 11.18-3.74 20.96-3.75 25.85z");
}

.na7hbybaj {
  cx: 49.31px;
  cy: 58.87px;
  rx: 4.87px;
  ry: 5.04px;
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.nz2dn-lcw {
  d: path("M119.29 13.26v72.81H8.71V13.26zM124 8.55H4v82.23h120z");
}

.o-m18bc6g {
  stop-color: var(--svg-color--ef5350, #ef5350);
}

.o-oe42blr {
  stop-color: var(--svg-color--00796b, #00796b);
}

.pqgvm3vez {
  stop-color: var(--svg-color--e53935, #e53935);
}

.qt2whjved {
  stop-color: var(--svg-color--b3e5fc, #b3e5fc);
}

.ranfy3p3c {
  stop-color: var(--svg-color--d1c4e9, #d1c4e9);
  stop-opacity: 0.2;
}

.s724_2bvk {
  fill: var(--svg-color--212121, #212121);
  stroke: var(--svg-color--212121, #212121);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M93.93 52.93c-.07-1.19-.12-1.31-1.69-1.81c-1.23-.39-7.95-.94-13.01-.66c-.36.02-.71.04-1.04.07c-4.59.39-10.1 2.24-14.24 2.34c-1.76.04-9.01-1.86-14.14-2.26c-.33-.02-.66-.05-1-.06c-5.07-.26-11.82.33-13.05.73c-1.57.51-1.62.63-1.68 1.82c-.07 1.18.13 2.2 1.06 2.51c1.27.42 1.28 2 2.13 6.54c.77 4.14 2.62 7.41 10.57 7.98c.34.02.66.04.98.04c7.03.1 9.45-4.53 10.25-6.07c1.49-2.86 1.02-6.8 4.96-6.81c3.93-.01 3.56 3.86 5.07 6.71c.81 1.53 3.17 6.18 10.14 6.08c.34 0 .69-.02 1.05-.05c7.94-.62 9.78-3.9 10.52-8.04c.82-4.55.83-6.14 2.09-6.56c.91-.3 1.1-1.31 1.03-2.5zM53.37 68.17c-1.22.57-2.85.86-4.57.86c-3.59-.01-7.57-1.27-9.01-3.81c-2.04-3.62-2.57-10.94.03-12.47c1.14-.67 4.99-1.13 8.97-.96c4.13.18 8.4 1.04 9.94 3.06c2.56 3.33-1.5 11.5-5.36 13.32zm34.9-3.1c-1.43 2.56-5.44 3.85-9.05 3.86c-1.7.01-3.31-.27-4.51-.83c-3.87-1.8-7.97-9.94-5.45-13.29c1.53-2.04 5.82-2.92 9.96-3.12c3.97-.19 7.81.25 8.94.91c2.62 1.52 2.13 8.84.11 12.47z");
}

.s7g1vnbdm {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M55.54 49.82c-.93-1.23-3.07-3.01-7.23-3.01S42 48.6 41.08 49.82c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.29-.38.39-1.01-.02-1.55m32.5 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.38-1.01-.02-1.55");
}

.sl8ua6bht {
  stop-color: var(--svg-color--f5f5f5, #f5f5f5);
}

.u3kz4vb7l {
  stop-color: var(--svg-color--530eeb, #530eeb);
}

.ub1b6o8az {
  d: path("m54 91.88l9.98 12.81s.5-.38 0 0l-16.23 6.64l-2.41-14.54z");
}

.ucf53pbfm {
  fill: var(--svg-color--543930, #543930);
  d: path("M64.57 2.87c-41.01 0-40.68 37.92-40.68 38.52c0 7.76.19 16.53.75 25.32l6.72-.02c-.06-2.92 1.99-20.97 8.08-22.34c22.36-5.03 35.01-16.89 35.01-16.89c3.29 7.18 13.58 14.19 17.27 16.86c3.03 2.19 4.58 18.55 4.52 22.38h7.09c0-.05.02-.1.02-.16c.56-8.75.74-17.46.74-25.17c.01-.58 1.49-38.5-39.52-38.5");
}

.upuoffbeu {
  stop-color: var(--svg-color--d1c4e9, #d1c4e9);
  stop-opacity: 0.6;
}

.vn5d0lb8b {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M64 92.33h-9.08v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98z");
}

.wj96wn2ud {
  d: path("m104.04 123.94l1.04-3.63c.35-1.22-.38-2.5-1.62-2.85l-41.52-11.9c-4.53-1.3-5.32 2.35-6.59 6.78l-3.33 11.6z");
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.x68zbhbtu {
  cx: 79.8px;
  cy: 58.87px;
  rx: 4.87px;
  ry: 5.04px;
}

.xb94qyb-t {
  stop-color: var(--svg-color--651fff, #651fff);
}

.xkx9frfii {
  d: path("M79.61 95.93s3.39 6.23 4.18 28.01h32.6v-3.18c-.75-16.76-19.83-21.14-36.78-24.83");
}

.yenhdubmr {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M64.31 16.04c-17.2 0-33.13 12.79-33.13 39.91c0 21.78 13.49 34.67 25.23 38.83c2.8.99 5.5 1.49 7.9 1.49c2.38 0 5.07-.49 7.85-1.47c11.76-4.14 25.28-17.03 25.28-38.84c0-27.13-15.93-39.92-33.13-39.92");
}

.z_mp1oy8k {
  d: path("m55.88 123.94l7.75-26.99l-6.43-1.85l-8.28 28.84z");
}

.zj2v9acmv {
  d: path("M6.36 10.9h115.29v77.52H6.36z");
}

</style>
