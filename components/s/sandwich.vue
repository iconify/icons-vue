<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuuucyd)" class="y4xp_7bos"/><path class="fi679tbrp"/><path fill="url(#ilGpwqe)" class="q-lltrbqh"/><path class="avg0684fc"/><path fill="url(#iDzI0Ox)" class="czhyjmbuz"/><g filter="url(#ihipXfb)"><path fill="url(#ivwG00c)" class="tc5lshbwq"/></g><g filter="url(#i09fkAk)"><path class="r59phcc1b"/></g><path fill="url(#ipd4Ngd)" class="s1lh5ubue"/><g filter="url(#iUFXaQd)"><path class="t19b03bzr"/><path fill="url(#irTtiPe)" class="y4gt11m3p"/><path fill="url(#iW2LBLd)" class="y4gt11m3p"/></g><path class="c3hhegb5z"/><path fill="url(#ihMwqnb)" class="y4b-tzbmk"/><path class="dox938srl"/><path fill="url(#isA5n3b)" class="sgy8okv-m"/><path class="c5vn7qv2p"/><path fill="url(#ihY4UXZ)" class="ck2arjr-u"/><path fill="url(#ibRra8b)" class="ck2arjr-u"/><path fill="url(#i2JPfId)" class="ck2arjr-u"/><g filter="url(#i4HktrI)"><path stroke="url(#iWOmcwc)" class="b15ihfjnv"/></g><g filter="url(#iGJCeFd)"><path fill="url(#ilCp9Gc)" class="o9c2numtn"/></g><g filter="url(#i7c9yle)"><path stroke="url(#iWn1Qqe)" class="r_ys_-bqc"/></g><g filter="url(#inv5Thc)"><path stroke="url(#idXFmvb)" class="wmrs_vbsv"/></g><g filter="url(#iVOKXab)"><path class="rs8cxdqfy"/></g><g filter="url(#i3HBA5T)"><path fill="url(#iZqmeMb)" class="r3dd2db_b"/></g><defs><linearGradient id="iuuucyd" x1="28.58" x2="3.875" y1="20.875" y2="20.875" gradientUnits="userSpaceOnUse"><stop class="bd-v6gbmx"/><stop offset=".175" class="on8cgfyfm"/><stop offset=".443" class="uh5cjbcae"/><stop offset=".507" class="fj868mbih"/><stop offset="1" class="cwi-evb4l"/></linearGradient><linearGradient id="iDzI0Ox" x1="26.063" x2="18.438" y1="20.563" y2="20.563" gradientUnits="userSpaceOnUse"><stop class="j1zs1v4ja"/><stop offset=".615" class="b9foksc6i"/><stop offset="1" class="z1gyvxbop"/></linearGradient><linearGradient id="ivwG00c" x1="26.855" x2="18" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop offset=".407" class="q804jbc3l"/><stop offset="1" class="v8682sbew"/></linearGradient><linearGradient id="ipd4Ngd" x1="29.99" x2="2.625" y1="18.125" y2="18.125" gradientUnits="userSpaceOnUse"><stop class="fvk5t41rd"/><stop offset=".141" class="kkjh76w8d"/><stop offset=".212" class="ozi4o6brq"/><stop offset=".322" class="um7vfmiih"/><stop offset=".445" class="pv7raogvs"/><stop offset=".509" class="tpxoqbcuy"/><stop offset=".623" class="m_89w1bxv"/><stop offset=".678" class="rcb3fgqdx"/><stop offset=".756" class="xkdzkif0h"/><stop offset="1" class="idxzs4scf"/></linearGradient><linearGradient id="irTtiPe" x1="29.563" x2="2.406" y1="15.895" y2="15.895" gradientUnits="userSpaceOnUse"><stop class="t0milbbou"/><stop offset="1" class="wd8c21gbw"/></linearGradient><linearGradient id="ihMwqnb" x1="28.563" x2="13.188" y1="15.065" y2="15.065" gradientUnits="userSpaceOnUse"><stop class="it9t_u8xc"/><stop offset=".69" class="nd82adbed"/><stop offset="1" class="r3tyafb1g"/></linearGradient><linearGradient id="isA5n3b" x1="28.58" x2="3.43" y1="12.5" y2="12.5" gradientUnits="userSpaceOnUse"><stop class="ye3d1wbel"/><stop offset=".446" class="r5c0i3vpd"/><stop offset=".503" class="s71rqty5z"/><stop offset=".577" class="e9pyzlbrd"/><stop offset=".873" class="wq4n0_8sy"/><stop offset="1" class="y0ouu4bug"/></linearGradient><linearGradient id="ihY4UXZ" x1="21.875" x2="14.75" y1="5.75" y2="17.997" gradientUnits="userSpaceOnUse"><stop class="maynbbgil"/><stop offset=".193" class="lmw-qlotb"/><stop offset=".52" class="c203s0ktk"/><stop offset=".817" class="t1qq7efeb"/><stop offset=".984" class="tkuh66roc"/></linearGradient><linearGradient id="ibRra8b" x1="9.438" x2="12.906" y1="5.5" y2="11.469" gradientUnits="userSpaceOnUse"><stop offset=".126" class="l_uiicwih"/><stop offset=".152" class="shjgk_b9k"/><stop offset=".211" class="ynj-hwd9z"/></linearGradient><linearGradient id="i2JPfId" x1="20.125" x2="18.75" y1="16.875" y2="14.438" gradientUnits="userSpaceOnUse"><stop offset=".258" class="q0as9d3ks"/><stop offset=".707" class="yszd5vb6v"/></linearGradient><linearGradient id="iWOmcwc" x1="27.719" x2="16.813" y1="14.781" y2="21.281" gradientUnits="userSpaceOnUse"><stop class="e5wwqmflc"/><stop offset=".955" class="dympq9b5r"/><stop offset="1" class="sc5sd3b5f"/></linearGradient><linearGradient id="ilCp9Gc" x1="29.516" x2="15.5" y1="16.344" y2="21.5" gradientUnits="userSpaceOnUse"><stop offset=".202" class="fv75ibqyn"/><stop offset=".272" class="uusq6ib0c"/><stop offset=".389" class="nglfq4b3v"/><stop offset=".643" class="qmjt609ia"/><stop offset=".726" class="bu80lab3l"/><stop offset=".876" class="artagy78o"/><stop offset="1" class="w1zjneg6j"/></linearGradient><linearGradient id="iWn1Qqe" x1="12.125" x2="7.625" y1="21.922" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".327" class="fncagobod"/><stop offset="1" class="ujjqr3h6k"/></linearGradient><linearGradient id="idXFmvb" x1="6.463" x2="2.345" y1="19.745" y2="17.102" gradientUnits="userSpaceOnUse"><stop offset=".327" class="fncagobod"/><stop offset="1" class="ujjqr3h6k"/></linearGradient><linearGradient id="iZqmeMb" x1="11.375" x2="6.469" y1="23.625" y2="21.563" gradientUnits="userSpaceOnUse"><stop class="l0lf_bs1e"/><stop offset="1" class="d7g7ccbqi"/></linearGradient><filter id="ihipXfb" width="12.55" height="11.948" x="14.555" y="12.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".125"/></filter><filter id="i09fkAk" width="22.844" height="10.271" x="4.736" y="15.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".5"/></filter><filter id="iUFXaQd" width="27.656" height="11.411" x="2.156" y="12.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".125"/></filter><filter id="i4HktrI" width="13.531" height="8.406" x="15.187" y="14.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".25"/></filter><filter id="iGJCeFd" width="14.55" height="9.969" x="15.5" y="14.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".25"/></filter><filter id="i7c9yle" width="5.859" height="3.289" x="6.969" y="19.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".25"/></filter><filter id="inv5Thc" width="5.526" height="3.842" x="1.656" y="16.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".25"/></filter><filter id="iVOKXab" width="5.125" height="4.438" x="21.703" y="20.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".125"/></filter><filter id="i3HBA5T" width="6.313" height="4.344" x="5.969" y="20.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28680" stdDeviation=".25"/></filter><radialGradient id="ilGpwqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.27 -5.48034 0 15.995 23.188)" gradientUnits="userSpaceOnUse"><stop offset=".42" class="veasdubyi"/><stop offset=".975" class="wgvtjdbxt"/></radialGradient><radialGradient id="iW2LBLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.96873 5 -6.03484 -1.16923 28.188 14.125)" gradientUnits="userSpaceOnUse"><stop class="sgydqvbbj"/><stop offset="1" class="m-v_txbrf"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sandwich" /></template>
<style>
.artagy78o {
  stop-color: var(--svg-color--b2d4ac, #B2D4AC);
}

.avg0684fc {
  fill: var(--svg-color--c62d62, #C62D62);
  d: path("M7.92 14.38c-3.7 2.14-3.7 7.48 0 9.62a6.5 6.5 0 0 0 6.5 0c3.7-2.14 3.7-7.48 0-9.62a6.5 6.5 0 0 0-6.5 0");
}

.b15ihfjnv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M27.969 15.094L15.937 22");
}

.b9foksc6i {
  stop-color: var(--svg-color--d12175, #D12175);
}

.bd-v6gbmx {
  stop-color: var(--svg-color--f8b78b, #F8B78B);
}

.bu80lab3l {
  stop-color: var(--svg-color--568c58, #568C58);
}

.c203s0ktk {
  stop-color: var(--svg-color--ffeac1, #FFEAC1);
}

.c3hhegb5z {
  fill: var(--svg-color--d2b432, #D2B432);
  d: path("M14.97 7.84L3.9 14.24a.956.956 0 0 0 0 1.65l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4a.956.956 0 0 0 0-1.65l-11.07-6.4c-.63-.37-1.41-.37-2.05 0");
}

.c5vn7qv2p {
  fill: var(--svg-color--ffebc2, #FFEBC2);
  d: path("M14.97 3.28L3.91 9.67a.956.956 0 0 0 0 1.65l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4a.956.956 0 0 0 0-1.65l-11.07-6.4c-.64-.36-1.42-.36-2.06.01");
}

.ck2arjr-u {
  d: path("M14.97 3.28L3.91 9.67a.956.956 0 0 0 0 1.65l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4a.956.956 0 0 0 0-1.65l-11.07-6.4c-.64-.36-1.42-.36-2.06.01");
}

.cwi-evb4l {
  stop-color: var(--svg-color--c37c58, #C37C58);
}

.czhyjmbuz {
  d: path("M24.08 14.38c3.7 2.14 3.7 7.48 0 9.62a6.5 6.5 0 0 1-6.5 0c-3.7-2.14-3.7-7.48 0-9.62a6.5 6.5 0 0 1 6.5 0");
}

.d7g7ccbqi {
  stop-color: var(--svg-color--c83b6b, #C83B6B);
  stop-opacity: 0;
}

.dox938srl {
  fill: var(--svg-color--c17a4f, #C17A4F);
  d: path("m26.1 10.62l-9.08-5.25c-.63-.37-1.41-.37-2.05 0l-9.08 5.25H3.43v2.54c0 .32.16.64.48.82l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4c.32-.18.48-.5.48-.82v-2.54z");
}

.dympq9b5r {
  stop-color: var(--svg-color--fff27f, #FFF27F);
  stop-opacity: 0.656;
}

.e5wwqmflc {
  stop-color: var(--svg-color--ffd660, #FFD660);
}

.e9pyzlbrd {
  stop-color: var(--svg-color--c77e5d, #C77E5D);
}

.fi679tbrp {
  fill: var(--svg-color--e9c2bd, #E9C2BD);
  d: path("M14.97 11.73L3.9 18.13a.956.956 0 0 0 0 1.65l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4a.956.956 0 0 0 0-1.65l-11.07-6.4a2.08 2.08 0 0 0-2.05 0");
}

.fj868mbih {
  stop-color: var(--svg-color--da7e77, #DA7E77);
}

.fncagobod {
  stop-color: var(--svg-color--80ac5e, #80AC5E);
}

.ft5dv1b6b {
  fill: none;
}

.fv75ibqyn {
  stop-color: var(--svg-color--6ba78a, #6BA78A);
}

.fvk5t41rd {
  stop-color: var(--svg-color--3d7a69, #3D7A69);
}

.idxzs4scf {
  stop-color: var(--svg-color--77a446, #77A446);
}

.it9t_u8xc {
  stop-color: var(--svg-color--ffca46, #FFCA46);
}

.j1zs1v4ja {
  stop-color: var(--svg-color--e33160, #E33160);
}

.kkjh76w8d {
  stop-color: var(--svg-color--427569, #427569);
}

.l_uiicwih {
  stop-color: var(--svg-color--e3d4b3, #E3D4B3);
}

.l0lf_bs1e {
  stop-color: var(--svg-color--d04071, #D04071);
}

.lmw-qlotb {
  stop-color: var(--svg-color--ffe8bc, #FFE8BC);
}

.m_89w1bxv {
  stop-color: var(--svg-color--62864c, #62864C);
}

.m-v_txbrf {
  stop-color: var(--svg-color--4f926e, #4F926E);
  stop-opacity: 0;
}

.maynbbgil {
  stop-color: var(--svg-color--ffecbc, #FFECBC);
}

.nd82adbed {
  stop-color: var(--svg-color--ffd155, #FFD155);
}

.nglfq4b3v {
  stop-color: var(--svg-color--7ab186, #7AB186);
}

.o9c2numtn {
  d: path("M17.984 23.336c-.656.531-1.203.602-1.984.789c.781.36 2.563-.555 3.406-2.023c.04-.069.205-.295.672-.188c.82.188 1.916.236 2.594-.062c1.889-.832 1.778-1.787 2.367-2.07c.63-.303 2.275-.144 3.148-.696c1.15-.726 1.72-2.336 1.125-3.852c.11 1.188.32 3.5-3.617 4.243c-.213.04-.43-.227-.797-.047s-1.319 1.326-2.132 1.906c-.353.251-1.564.595-2.141.516c-.449-.062-.57-.154-.914-.125c-.758.062-.871.916-1.727 1.609");
}

.on8cgfyfm {
  stop-color: var(--svg-color--f2aa87, #F2AA87);
}

.ozi4o6brq {
  stop-color: var(--svg-color--539467, #539467);
}

.pv7raogvs {
  stop-color: var(--svg-color--709b6c, #709B6C);
}

.q-lltrbqh {
  d: path("M14.97 11.73L3.9 18.13a.956.956 0 0 0 0 1.65l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4a.956.956 0 0 0 0-1.65l-11.07-6.4a2.08 2.08 0 0 0-2.05 0");
}

.q0as9d3ks {
  stop-color: var(--svg-color--fffad5, #FFFAD5);
}

.q804jbc3l {
  stop-color: var(--svg-color--ee4873, #EE4873);
}

.qmjt609ia {
  stop-color: var(--svg-color--6ba879, #6BA879);
}

.r_ys_-bqc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.078 21.828c-.515-.078-.735.101-1.39.14c-.774.048-2.196-.085-2.97-1.78");
}

.r3dd2db_b {
  d: path("M10.938 23.188c-1.438 0-2.938-.282-4.47-2.094c0 2.218 3.688 3.343 5.313 3.343c-.187-.468-.219-.812-.844-1.25");
}

.r3tyafb1g {
  stop-color: var(--svg-color--ffcc42, #FFCC42);
  stop-opacity: 0;
}

.r59phcc1b {
  fill: var(--svg-color--a20c47, #A20C47);
  d: path("M22.94 16.506c-.401-.155-13.817-.024-13.88 0c-3.372 1.713-3.685 3.338-3.07 4.12c.53-.06 1.03.22 1.26.7c.75 1.59 2.58 2.19 4.15 1.79c.52-.13 1.06.07 1.34.51c.51 1.19 1.65.977 3 1.077h.54c1.35-.1 2.49.113 3-1.077c.28-.44.82-.64 1.34-.51c1.56.4 3.4-.2 4.15-1.79c.23-.48.73-.76 1.26-.7c1.501-.657-.249-2.626-3.09-4.12");
}

.r5c0i3vpd {
  stop-color: var(--svg-color--f3a077, #F3A077);
}

.rcb3fgqdx {
  stop-color: var(--svg-color--627956, #627956);
}

.rs8cxdqfy {
  fill: var(--svg-color--fb6885, #FB6885);
  d: path("M26.578 20.36c-.344 1.328-1.862 3.574-4.625 3.937c2.313-1.063 3.761-2.424 4.625-3.938");
}

.s1lh5ubue {
  d: path("M22.94 16.09c-1.97-.76-4.61.18-4.9 2.83c-.51-.37-1.13-.6-1.79-.64c-.06 0-.12-.01-.18-.01h-.14c-.06 0-.12 0-.18.01c-.66.05-1.28.28-1.79.64c-.29-2.64-2.93-3.59-4.9-2.83c-.69-4-6.96-3.78-7.03.65c.04 2.51 2.08 3.67 3.96 3.47c.53-.06 1.03.22 1.26.7C8 22.5 9.83 23.1 11.4 22.7c.52-.13 1.06.07 1.34.51a3.55 3.55 0 0 0 3 2.14h.01c.08.01.16.01.25.01h.02c.08 0 .16 0 .25-.01h.01a3.55 3.55 0 0 0 3-2.14c.28-.44.82-.64 1.34-.51c1.56.4 3.4-.2 4.15-1.79c.23-.48.73-.76 1.26-.7c1.88.2 3.91-.96 3.96-3.47c-.1-4.43-6.36-4.65-7.05-.65");
}

.s71rqty5z {
  stop-color: var(--svg-color--e28974, #E28974);
}

.sc5sd3b5f {
  stop-color: var(--svg-color--ffd85b, #FFD85B);
  stop-opacity: 0;
}

.sgy8okv-m {
  d: path("m26.1 10.62l-9.08-5.25c-.63-.37-1.41-.37-2.05 0l-9.08 5.25H3.43v2.54c0 .32.16.64.48.82l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4c.32-.18.48-.5.48-.82v-2.54z");
}

.sgydqvbbj {
  stop-color: var(--svg-color--407d6b, #407D6B);
}

.shjgk_b9k {
  stop-color: var(--svg-color--f0deba, #F0DEBA);
}

.t0milbbou {
  stop-color: var(--svg-color--46946c, #46946C);
}

.t19b03bzr {
  fill: var(--svg-color--679636, #679636);
  d: path("M22.715 15.807c-1.913-.684-4.477.162-4.759 2.55a3.47 3.47 0 0 0-1.738-.577c-.059 0-.117-.01-.175-.01h-.136c-.059 0-.117 0-.175.01a3.66 3.66 0 0 0-1.739.576c-.281-2.378-2.845-3.233-4.759-2.549c-.67-3.602-6.76-3.404-6.828.586c.04 2.26 2.02 3.305 3.846 3.125c.515-.054 1 .198 1.224.63c.729 1.432 2.506 1.973 4.03 1.613c.506-.117 1.03.063 1.302.459c.496 1.072 1.603 1.837 2.914 1.927h.01c.078.01.155.01.243.01h.02c.077 0 .155 0 .242-.01h.01c1.31-.09 2.418-.855 2.913-1.927c.272-.396.797-.576 1.302-.46c1.515.36 3.302-.18 4.03-1.612c.224-.432.71-.684 1.224-.63c1.826.18 3.798-.865 3.846-3.125c-.097-3.99-6.177-4.188-6.847-.586");
}

.t1qq7efeb {
  stop-color: var(--svg-color--ffeac3, #FFEAC3);
}

.tc5lshbwq {
  d: path("M24.08 13.898c3.7 2.156 3.7 7.537 0 9.694a6.46 6.46 0 0 1-6.5 0c-3.7-2.157-3.7-7.538 0-9.694a6.46 6.46 0 0 1 6.5 0");
}

.tkuh66roc {
  stop-color: var(--svg-color--eed6be, #EED6BE);
}

.tpxoqbcuy {
  stop-color: var(--svg-color--608065, #608065);
}

.uh5cjbcae {
  stop-color: var(--svg-color--ef9c7e, #EF9C7E);
}

.ujjqr3h6k {
  stop-color: var(--svg-color--749459, #749459);
  stop-opacity: 0;
}

.um7vfmiih {
  stop-color: var(--svg-color--527e67, #527E67);
}

.uusq6ib0c {
  stop-color: var(--svg-color--4e8e6c, #4E8E6C);
}

.v8682sbew {
  stop-color: var(--svg-color--bf1362, #BF1362);
}

.veasdubyi {
  stop-color: var(--svg-color--c17f85, #C17F85);
}

.w1zjneg6j {
  stop-color: var(--svg-color--76a36a, #76A36A);
}

.wd8c21gbw {
  stop-color: var(--svg-color--72a33c, #72A33C);
}

.wgvtjdbxt {
  stop-color: var(--svg-color--d49894, #D49894);
  stop-opacity: 0;
}

.wmrs_vbsv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.433 19.645c-.496-.163-.743-.023-1.395-.092c-.77-.083-2.15-.45-2.632-2.25");
}

.wq4n0_8sy {
  stop-color: var(--svg-color--c0794c, #C0794C);
}

.xkdzkif0h {
  stop-color: var(--svg-color--6e964a, #6E964A);
}

.y0ouu4bug {
  stop-color: var(--svg-color--c1845e, #C1845E);
}

.y4b-tzbmk {
  d: path("M14.97 7.84L3.9 14.24a.956.956 0 0 0 0 1.65l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4a.956.956 0 0 0 0-1.65l-11.07-6.4c-.63-.37-1.41-.37-2.05 0");
}

.y4gt11m3p {
  d: path("M22.715 15.807c-1.913-.684-4.477.162-4.759 2.55a3.47 3.47 0 0 0-1.738-.577c-.059 0-.117-.01-.175-.01h-.136c-.059 0-.117 0-.175.01a3.66 3.66 0 0 0-1.739.576c-.281-2.378-2.845-3.233-4.759-2.549c-.67-3.602-6.76-3.404-6.828.586c.04 2.26 2.02 3.305 3.846 3.125c.515-.054 1 .198 1.224.63c.729 1.432 2.506 1.973 4.03 1.613c.506-.117 1.03.063 1.302.459c.496 1.072 1.603 1.837 2.914 1.927h.01c.078.01.155.01.243.01h.02c.077 0 .155 0 .242-.01h.01c1.31-.09 2.418-.855 2.913-1.927c.272-.396.797-.576 1.302-.46c1.515.36 3.302-.18 4.03-1.612c.224-.432.71-.684 1.224-.63c1.826.18 3.798-.865 3.846-3.125c-.097-3.99-6.177-4.188-6.847-.586");
}

.y4xp_7bos {
  d: path("m26.1 19.07l-9.08-5.25c-.63-.37-1.42-.37-2.05 0l-9.08 5.25H3.43v2.54c0 .32.16.64.48.82l11.07 6.4c.63.37 1.42.37 2.05 0l11.07-6.4c.32-.18.48-.5.48-.82v-2.54z");
}

.ye3d1wbel {
  stop-color: var(--svg-color--fab987, #FAB987);
}

.ynj-hwd9z {
  stop-color: var(--svg-color--fbe8c3, #FBE8C3);
  stop-opacity: 0;
}

.yszd5vb6v {
  stop-color: var(--svg-color--fffad6, #FFFAD6);
  stop-opacity: 0;
}

.z1gyvxbop {
  stop-color: var(--svg-color--cc246f, #CC246F);
}

</style>
