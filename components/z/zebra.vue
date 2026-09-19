<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ixv16xqeg"/><path fill="url(#idILXhe)" class="lkgef85ip"/><g filter="url(#ibK6iae)"><path fill="url(#imVEcly)" class="plz84hcnm"/></g><path fill="url(#i60H03Q)" class="vljnzf_ql"/><path fill="url(#iVmS3ne)" class="vljnzf_ql"/><path fill="url(#iMh4bCd)" class="vljnzf_ql"/><path fill="url(#i0RAj7b)" class="vljnzf_ql"/><path fill="url(#ikxeroe)" class="vljnzf_ql"/><path fill="url(#iYwZeqc)" class="k9c8rxb7z"/><path fill="url(#igx1oYc)" class="k9c8rxb7z"/><path fill="url(#iom4fYH)" class="k9c8rxb7z"/><path class="qqlloez7y"/><path class="sy5nff_mh"/><path class="li7nb4f0v"/><path fill="url(#iSPoczd)" class="cr_umbc6g"/><path fill="url(#i4bEq9b)" class="cr_umbc6g"/><path fill="url(#i7ziwhW)" class="pvgm9qm0t"/><path fill="url(#iqMwx3b)" class="pvgm9qm0t"/><path fill="url(#ikI8fhT)" class="pvgm9qm0t"/><path fill="url(#i1Qztvd)" class="pvgm9qm0t"/><path fill="url(#i0emKCd)" class="pvgm9qm0t"/><path fill="url(#iM2xTed)" class="pvgm9qm0t"/><path fill="url(#i9vDDFc)" class="pvgm9qm0t"/><path fill="url(#iDrJpFe)" class="pvgm9qm0t"/><path fill="url(#iK7Epsc)" class="pvgm9qm0t"/><g filter="url(#i8XoUzb)"><path class="sz8qc1bho"/></g><path fill="url(#iyN0pFe)" class="tn364qfvv"/><path fill="url(#izqJcrc)" class="tn364qfvv"/><path fill="url(#iXRoiPc)" class="tn364qfvv"/><path fill="url(#inYiP7Z)" class="wysdbsbty"/><path fill="url(#iLplv9c)" class="wysdbsbty"/><path fill="url(#iP7q1zb)" class="wysdbsbty"/><path class="fa-mzebwu"/><path fill="url(#iGNGRfb)" class="devwv500s"/><path clip-rule="evenodd" class="ummnoccep"/><path fill="url(#iQJRUQb)" class="mb2kfcc_c"/><path fill="url(#iB2X4TE)" class="g5ff0dvhb"/><path fill="url(#io048cD)" class="l6j68fbnq"/><path fill="url(#ivxZCEd)" class="c04nnyb2c"/><path fill="url(#iuaieZb)" class="yu-vrccot"/><path fill="url(#iTwayFe)" class="iajhjibot"/><path fill="url(#i4TB8pe)" class="jkipcqstv"/><path fill="url(#i45jkIe)" class="x_dkntb2t"/><path fill="url(#izwWSnT)" class="sexd79bcd"/><path class="swt4lnbbm"/><path class="qn_6qbbex"/><path fill="url(#iJ2eFGe)" class="kh1iprb4f"/><path fill="url(#iSF6cCH)" class="p-s-tsb1p"/><path fill="url(#iIr9XTd)" class="jlds8-abq"/><g filter="url(#iA6xilN)"><ellipse transform="rotate(49.457 4.871 7.033)" class="hm3r1actb"/></g><circle fill="url(#iCUofOc)" class="z4vzfx2fx"/><g filter="url(#iHeaWSB)"><path class="m5ubxc5my"/></g><g filter="url(#iIm8s9d)"><path class="b6_4bc7ju"/></g><g filter="url(#i9VoAte)"><path class="gx-p7ybqf"/></g><g filter="url(#ivhHU9D)"><path fill="url(#iw2eroJ)" class="adp2zi2xk"/></g><defs><linearGradient id="i60H03Q" x1="20.999" x2="20.999" y1="17.596" y2="30.999" gradientUnits="userSpaceOnUse"><stop class="lqyb_ubdr"/><stop offset="1" class="n65owb8sc"/></linearGradient><linearGradient id="iVmS3ne" x1="23.188" x2="21.246" y1="20.002" y2="22.272" gradientUnits="userSpaceOnUse"><stop class="e39-0tvvd"/><stop offset="1" class="sgzndxb5m"/></linearGradient><linearGradient id="iMh4bCd" x1="20.999" x2="20.999" y1="20.127" y2="22.533" gradientUnits="userSpaceOnUse"><stop class="e39-0tvvd"/><stop offset="1" class="sgzndxb5m"/></linearGradient><linearGradient id="ikxeroe" x1="21.438" x2="21.438" y1="31.939" y2="26.502" gradientUnits="userSpaceOnUse"><stop offset=".149" class="y9p0ywbnw"/><stop offset=".425" class="lgsykeaal"/></linearGradient><linearGradient id="iYwZeqc" x1="13.875" x2="10.999" y1="21.283" y2="31.056" gradientUnits="userSpaceOnUse"><stop class="lqyb_ubdr"/><stop offset="1" class="n65owb8sc"/></linearGradient><linearGradient id="igx1oYc" x1="13.688" x2="11.5" y1="28.096" y2="28.096" gradientUnits="userSpaceOnUse"><stop class="lqyb_ubdr"/><stop offset="1" class="xn03pwb0p"/></linearGradient><linearGradient id="iom4fYH" x1="11.187" x2="11.187" y1="32.09" y2="26.109" gradientUnits="userSpaceOnUse"><stop offset=".149" class="y9p0ywbnw"/><stop offset=".425" class="lgsykeaal"/></linearGradient><linearGradient id="i7ziwhW" x1="15.499" x2="15.499" y1="2.433" y2="39.721" gradientUnits="userSpaceOnUse"><stop class="gpux4klke"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="ikI8fhT" x1="16.188" x2="27.75" y1="20.158" y2="19.783" gradientUnits="userSpaceOnUse"><stop class="wc2crwbro"/><stop offset="1" class="u_lr15bqk"/></linearGradient><linearGradient id="iM2xTed" x1="17.254" x2="17.254" y1="34.656" y2="19.433" gradientUnits="userSpaceOnUse"><stop offset=".149" class="y9p0ywbnw"/><stop offset=".185" class="y9p0ywbnw"/><stop offset=".349" class="lgsykeaal"/></linearGradient><linearGradient id="iDrJpFe" x1="21.625" x2="27.75" y1="19.783" y2="19.783" gradientUnits="userSpaceOnUse"><stop class="wc2crwbro"/><stop offset="1" class="eomw7ewte"/></linearGradient><linearGradient id="iyN0pFe" x1="14.516" x2="11.5" y1="23.933" y2="24.533" gradientUnits="userSpaceOnUse"><stop class="en8bykbfx"/><stop offset="1" class="r6v6gcb6b"/></linearGradient><linearGradient id="izqJcrc" x1="13.197" x2="13.197" y1="32.033" y2="26.539" gradientUnits="userSpaceOnUse"><stop offset=".149" class="y9p0ywbnw"/><stop offset=".425" class="lgsykeaal"/></linearGradient><linearGradient id="iXRoiPc" x1="13.008" x2="13.008" y1="19.721" y2="21.971" gradientUnits="userSpaceOnUse"><stop class="b-9f70bnm"/><stop offset="1" class="hx5ipyb0a"/></linearGradient><linearGradient id="inYiP7Z" x1="8.188" x2="12.499" y1="10.408" y2="7.846" gradientUnits="userSpaceOnUse"><stop class="nbupcysqh"/><stop offset=".894" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGNGRfb" x1="7.834" x2="7.834" y1="4.221" y2="7.096" gradientUnits="userSpaceOnUse"><stop class="q4ay10b-c"/><stop offset="1" class="ja8c-bpki"/></linearGradient><linearGradient id="iQJRUQb" x1="11.5" x2="6.063" y1="11.34" y2="11.34" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="jxl8jbctk"/></linearGradient><linearGradient id="iB2X4TE" x1="13.563" x2="19.875" y1="11.43" y2="17.221" gradientUnits="userSpaceOnUse"><stop class="x01s_nb_e"/><stop offset="1" class="af5o1cvwa"/></linearGradient><linearGradient id="io048cD" x1="18.459" x2="18.459" y1="12.43" y2="16.533" gradientUnits="userSpaceOnUse"><stop class="goovo3b4g"/><stop offset="1" class="gvg91abbd"/></linearGradient><linearGradient id="ivxZCEd" x1="27.75" x2="22.75" y1="13.346" y2="21.43" gradientUnits="userSpaceOnUse"><stop class="lgpad07mj"/><stop offset="1" class="n7z50ovtm"/></linearGradient><linearGradient id="iuaieZb" x1="30" x2="26.625" y1="15.721" y2="20.2" gradientUnits="userSpaceOnUse"><stop class="t1dt-1bgk"/><stop offset="1" class="y9ey0pdvu"/></linearGradient><linearGradient id="iTwayFe" x1="31.313" x2="24.063" y1="23.23" y2="23.23" gradientUnits="userSpaceOnUse"><stop class="c0yoqkuqx"/><stop offset="1" class="y4xdt7ayb"/></linearGradient><linearGradient id="i4TB8pe" x1="29.938" x2="26.938" y1="24.31" y2="26.283" gradientUnits="userSpaceOnUse"><stop class="i6lb36bbs"/><stop offset="1" class="aw4x5jbgu"/></linearGradient><linearGradient id="i45jkIe" x1="24.609" x2="26.594" y1="29.46" y2="29.46" gradientUnits="userSpaceOnUse"><stop class="e5x_zg99a"/><stop offset="1" class="j5ax47b6s"/></linearGradient><linearGradient id="izwWSnT" x1="8.253" x2="8.253" y1="15.564" y2="19.47" gradientUnits="userSpaceOnUse"><stop class="eqqsdrbzm"/><stop offset="1" class="z_k8o-57c"/></linearGradient><linearGradient id="iJ2eFGe" x1="2.063" x2="2.953" y1="8.377" y2="10.111" gradientUnits="userSpaceOnUse"><stop class="ixuczfbhb"/><stop offset="1" class="gaadbc7ca"/></linearGradient><linearGradient id="iSF6cCH" x1="20.422" x2="21.5" y1="28.299" y2="29.252" gradientUnits="userSpaceOnUse"><stop class="rm_l-cc8e"/><stop offset="1" class="br-0w783y"/></linearGradient><linearGradient id="iIr9XTd" x1="20.5" x2="24.499" y1="25.43" y2="25.43" gradientUnits="userSpaceOnUse"><stop class="rm_l-cc8e"/><stop offset="1" class="br-0w783y"/></linearGradient><linearGradient id="iw2eroJ" x1="6.344" x2="7.469" y1="2.533" y2="4.596" gradientUnits="userSpaceOnUse"><stop class="hngzuob8m"/><stop offset="1" class="j4hz4o_ss"/></linearGradient><radialGradient id="idILXhe" cx="0" cy="0" r="1" gradientTransform="matrix(3.22261 -1.96875 4.92126 8.05551 26.016 10.252)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="wn070w6dm"/><stop offset="1" class="casc60bmc"/></radialGradient><radialGradient id="imVEcly" cx="0" cy="0" r="1" gradientTransform="matrix(2.582 -1.4375 2.04211 3.66797 26.656 10.283)" gradientUnits="userSpaceOnUse"><stop class="q0903mb8p"/><stop offset="1" class="wn070w6dm"/></radialGradient><radialGradient id="i0RAj7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.48438 -1.64063 3.29557 2.9817 18.094 23.846)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="jy90dvbiz"/><stop offset="1" class="pixhuubru"/></radialGradient><radialGradient id="iSPoczd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 .64062 -.73393 -.87714 12.938 11.846)" gradientUnits="userSpaceOnUse"><stop class="lac6d2b3s"/><stop offset="1" class="kw3un7bki"/></radialGradient><radialGradient id="i4bEq9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99219 .53906 -.42878 -1.58461 5.969 3.752)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="e9cswec5r"/><stop offset="1" class="ws-ebtbdz"/></radialGradient><radialGradient id="iqMwx3b" cx="0" cy="0" r="1" gradientTransform="rotate(114.087 3.629 10.765)scale(11.6384 18.2254)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="lgsykeaal"/><stop offset=".931" class="y9p0ywbnw"/></radialGradient><radialGradient id="i1Qztvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.72652 20.1875 0 16.938 23.158)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="y9p0ywbnw"/><stop offset=".697" class="lgsykeaal"/></radialGradient><radialGradient id="i0emKCd" cx="0" cy="0" r="1" gradientTransform="matrix(2.8125 -5.03124 5.7643 3.22229 24.813 23.94)" gradientUnits="userSpaceOnUse"><stop class="y9p0ywbnw"/><stop offset=".574" class="lgsykeaal"/></radialGradient><radialGradient id="i9vDDFc" cx="0" cy="0" r="1" gradientTransform="rotate(44.318 -4.222 5.566)scale(3.71257 6.63102)" gradientUnits="userSpaceOnUse"><stop class="uu-54ri1j"/><stop offset="1" class="rj82fccoa"/></radialGradient><radialGradient id="iK7Epsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06252 4 -9.2506 -2.45725 24.75 12.908)" gradientUnits="userSpaceOnUse"><stop class="eomw7ewte"/><stop offset=".619" class="wc2crwbro"/></radialGradient><radialGradient id="iLplv9c" cx="0" cy="0" r="1" gradientTransform="matrix(6 -11.18751 7.94516 4.26109 2.625 17.72)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="pv8vkz7wu"/><stop offset=".881" class="magc03bnw"/></radialGradient><radialGradient id="iP7q1zb" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 -4.3125 2.85757 1.94646 4.281 11.47)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="y9p0ywbnw"/><stop offset=".881" class="lgsykeaal"/></radialGradient><radialGradient id="iCUofOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 .64312 -.5597 -.29916 5.19 6.79)" gradientUnits="userSpaceOnUse"><stop class="ckq7otbdc"/><stop offset="1" class="jx0oumbhp"/></radialGradient><filter id="ibK6iae" width="5.296" height="9.768" x="24.442" y="4.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2572" stdDeviation=".25"/></filter><filter id="i8XoUzb" width="18.41" height="14.75" x="11.84" y="11.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2572" stdDeviation=".75"/></filter><filter id="iA6xilN" width="1.442" height="1.422" x="4.15" y="6.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2572" stdDeviation=".125"/></filter><filter id="iHeaWSB" width="6.208" height="9.752" x="8.293" y="2.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2572" stdDeviation=".2"/></filter><filter id="iIm8s9d" width="5.003" height="2.714" x="10.489" y="19.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2572" stdDeviation=".5"/></filter><filter id="i9VoAte" width="1.6" height="10.037" x="13.137" y="20.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2572" stdDeviation=".35"/></filter><filter id="ivhHU9D" width="1.959" height="2.819" x="5.606" y="2.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2572" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:zebra" /></template>
<style>
.adp2zi2xk {
  d: path("m6.781 4.97l-.875-2.218l1.36 1.015z");
}

.af5o1cvwa {
  stop-color: var(--svg-color--5f5d61, #5F5D61);
}

.aw4x5jbgu {
  stop-color: var(--svg-color--524d58, #524D58);
}

.b-9f70bnm {
  stop-color: var(--svg-color--9279a9, #9279A9);
}

.b6_4bc7ju {
  stroke: var(--svg-color--ebeaec, #EBEAEC);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.639 20.94c.443-.313 1.603-.75 2.703 0");
}

.br-0w783y {
  stop-color: var(--svg-color--413c47, #413C47);
}

.c04nnyb2c {
  d: path("m26.529 12.86l-6.62 8.57h1.26l6.23-8.06c-.26-.2-.56-.37-.87-.51");
}

.c0yoqkuqx {
  stop-color: var(--svg-color--6c6a6e, #6C6A6E);
}

.casc60bmc {
  stop-color: var(--svg-color--7d7c7e, #7D7C7E);
}

.ckq7otbdc {
  stop-color: var(--svg-color--605255, #605255);
}

.cr_umbc6g {
  d: path("M12.179 4.61C11.054 3.561 9.192 2.7 7.619 2.7c-1.39 0-2.69.53-3.7 1.35c-.23.19-.24.55-.02.76l2.72 2.63l.415-.054l.395.394c.21-.18.49-.29.8-.31c.47-.02.92.3 1.12.72c.12.2.18.42.17.64c-.02.4-.07.8-.13 1.2c-.07.94-.19 1.87-.35 2.8h5.48v-3c0-1.77-.66-3.47-1.88-4.77a7 7 0 0 0-.46-.45");
}

.devwv500s {
  d: path("M7.529 3.447V4.73a.8.8 0 0 1-.244.576a.5.5 0 1 0 .707.708A1.8 1.8 0 0 0 8.53 4.73v-.946c-.322-.115-.638-.185-1-.337");
}

.e39-0tvvd {
  stop-color: var(--svg-color--5c4c6b, #5C4C6B);
}

.e5x_zg99a {
  stop-color: var(--svg-color--5d5763, #5D5763);
}

.e9cswec5r {
  stop-color: var(--svg-color--444246, #444246);
}

.en8bykbfx {
  stop-color: var(--svg-color--d4cddc, #D4CDDC);
}

.eomw7ewte {
  stop-color: var(--svg-color--ddd5e6, #DDD5E6);
}

.eqqsdrbzm {
  stop-color: var(--svg-color--545158, #545158);
}

.fa-mzebwu {
  fill: var(--svg-color--636363, #636363);
  d: path("m21.829 28.76l-1.19-1.19l-.6.81l1.16 1.17zm-.65-4.33c.18.3.28.64.31 1h2.85c.11-.29.16-.59.16-.9v-.1z");
}

.ft5dv1b6b {
  fill: none;
}

.g5ff0dvhb {
  d: path("M12.499 11.93c0 .191.138.455.45.5h-1.76c-.2 0-.37.1-.48.26c-.1.17-.12.36-.04.54l1.28 2.89c.31.69.99 1.13 1.74 1.13h4.49a3 3 0 0 0 2.37-1.14l2.93-3.68h1.037l.136.002q.05.002.097.008l-3.42 4.29a4 4 0 0 1-3.15 1.52h-4.49c-1.14 0-2.19-.68-2.65-1.73l-1.28-2.89c-.21-.49-.17-1.04.12-1.49c.29-.44.78-.71 1.31-.71h1.31z");
}

.gaadbc7ca {
  stop-color: var(--svg-color--493d55, #493D55);
}

.goovo3b4g {
  stop-color: var(--svg-color--5f5f5f, #5F5F5F);
}

.gpux4klke {
  stop-color: var(--svg-color--cbcacd, #CBCACD);
}

.gvg91abbd {
  stop-color: var(--svg-color--605867, #605867);
}

.gx-p7ybqf {
  stroke: var(--svg-color--ebeaec, #EBEAEC);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.938 21.002v8.437");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hm3r1actb {
  cx: 4.871px;
  cy: 7.033px;
  fill: var(--svg-color--9e99a3, #9E99A3);
  rx: 0.433px;
  ry: 0.497px;
}

.hngzuob8m {
  stop-color: var(--svg-color--e2e1e3, #E2E1E3);
}

.hx5ipyb0a {
  stop-color: var(--svg-color--9279a9, #9279A9);
  stop-opacity: 0;
}

.i6lb36bbs {
  stop-color: var(--svg-color--666369, #666369);
}

.iajhjibot {
  d: path("M29.499 22.23h-5.917l1.34 1h4.577z");
}

.ixuczfbhb {
  stop-color: var(--svg-color--595959, #595959);
}

.ixv16xqeg {
  fill: var(--svg-color--484749, #484749);
  d: path("M25.125 8.214c2.469 3.22 1.969 3.594 1.969 4.97l.843.767c1.925-2.025 1.282-4.237.782-5.05s-3.75-3.718-3.75-3.718c-.825 1.4-.188 2.656.156 3.031");
}

.j4hz4o_ss {
  stop-color: var(--svg-color--e2e1e3, #E2E1E3);
  stop-opacity: 0;
}

.j5ax47b6s {
  stop-color: var(--svg-color--56515a, #56515A);
}

.ja8c-bpki {
  stop-color: var(--svg-color--58545b, #58545B);
}

.jkipcqstv {
  d: path("m26.199 26.79l3.12-1.32c.12-.3.18-.62.18-.94v-.22l-3 1.27v.05c0 .41-.1.8-.3 1.16");
}

.jlds8-abq {
  d: path("M21.179 24.43c.18.3.28.64.31 1h2.85c.11-.29.16-.59.16-.9v-.1z");
}

.jx0oumbhp {
  stop-color: var(--svg-color--3c273a, #3C273A);
}

.jxl8jbctk {
  stop-color: var(--svg-color--4b494e, #4B494E);
}

.jy90dvbiz {
  stop-color: var(--svg-color--6e4694, #6E4694);
}

.k9c8rxb7z {
  d: path("M12.499 21.43v8.74c0 .14-.12.26-.26.26h-.55c-.11 0-.22-.08-.25-.19l-1.36-4.67c-.38-1.34-.58-2.74-.58-4.14v-2h3z");
}

.kh1iprb4f {
  d: path("M2.319 7.53c-.34.36-.56.6-.56.6c-.22.25-.31.6-.23.94c.15.68.84 1.01 1.48.75l.77-.31z");
}

.kw3un7bki {
  stop-color: var(--svg-color--555456, #555456);
  stop-opacity: 0;
}

.l6j68fbnq {
  d: path("m20.019 12.43l-1.83 2.25c-.17.21-.42.33-.69.33c-.49 0-.89-.4-.89-.89v-1.69h-1v1.68c0 1.04.85 1.89 1.89 1.89c.57 0 1.1-.25 1.46-.7l2.35-2.87z");
}

.lac6d2b3s {
  stop-color: var(--svg-color--555456, #555456);
}

.lgpad07mj {
  stop-color: var(--svg-color--686869, #686869);
}

.lgsykeaal {
  stop-color: var(--svg-color--9179a7, #9179A7);
  stop-opacity: 0;
}

.li7nb4f0v {
  fill: var(--svg-color--5e5c61, #5E5C61);
  d: path("M12.179 4.61C11.054 3.561 9.192 2.7 7.619 2.7c-1.39 0-2.69.53-3.7 1.35c-.23.19-.24.55-.02.76l2.72 2.63l.415-.054l.395.394c.21-.18.49-.29.8-.31c.47-.02.92.3 1.12.72c.12.2.18.42.17.64c-.02.4-.07.8-.13 1.2c-.07.94-.19 1.87-.35 2.8h5.48v-3c0-1.77-.66-3.47-1.88-4.77a7 7 0 0 0-.46-.45");
}

.lkgef85ip {
  d: path("M25.125 8.214c2.469 3.22 1.969 3.594 1.969 4.97l.843.767c1.925-2.025 1.282-4.237.782-5.05s-3.75-3.718-3.75-3.718c-.825 1.4-.188 2.656.156 3.031");
}

.lqyb_ubdr {
  stop-color: var(--svg-color--69587a, #69587A);
}

.m5ubxc5my {
  stroke: var(--svg-color--7b7a7c, #7B7A7C);
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.719 3.267c3.625 1.297 5.687 3.625 5.25 8.876");
}

.magc03bnw {
  stop-color: var(--svg-color--afa9b6, #AFA9B6);
  stop-opacity: 0;
}

.mb2kfcc_c {
  d: path("m6.499 11.34l.2-.26c.52-.71 1.36-1.13 2.24-1.13h3.56v-.52a6 6 0 0 0-.02-.48H8.93c-.9 0-1.76.32-2.43.89z");
}

.n65owb8sc {
  stop-color: var(--svg-color--beb4c8, #BEB4C8);
}

.n7z50ovtm {
  stop-color: var(--svg-color--58535d, #58535D);
}

.nbupcysqh {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
  stop-opacity: 0;
}

.p-s-tsb1p {
  d: path("m21.829 28.76l-1.19-1.19l-.6.81l1.16 1.17z");
}

.pixhuubru {
  stop-color: var(--svg-color--8152ac, #8152AC);
  stop-opacity: 0;
}

.plz84hcnm {
  d: path("M24.943 5.228c-.012.705.308 1.773 2.01 3.461c1.985 1.97 1.358 3.491.62 4.93l.364.332c1.925-2.025 1.282-4.237.782-5.05s-3.75-3.718-3.75-3.718q-.015.022-.026.045");
}

.pv8vkz7wu {
  stop-color: var(--svg-color--afa9b6, #AFA9B6);
}

.pvgm9qm0t {
  d: path("M24.499 12.43h-11.5a.5.5 0 0 1-.5-.5v-2.5a6 6 0 0 0-4.35-5.767c-.41-.117-.813-.266-1.166-.504L5.959 2.47a.312.312 0 0 0-.46.27c0 .878-.325 1.715-.923 2.359C3.468 6.294 1.76 8.13 1.76 8.13c-.22.25-.31.6-.23.94c.15.68.84 1.01 1.48.75l3.146-1.271a.25.25 0 0 1 .344.232v7.649a5 5 0 0 0 4.75 4.994c.138.007.25.118.252.256c.022 1.316.221 2.63.588 3.89l1.36 4.67c.03.11.13.19.25.19h.55c.14 0 .26-.12.26-.26v-8.34a.4.4 0 0 1 .4-.4h6.95c.43 0 .84.14 1.18.39l2.52 1.89a2.4 2.4 0 0 1 .48 3.36l-2.24 2.99c-.14.15-.03.37.16.37h1.22c.2 0 .39-.09.52-.25l3.24-4.05c.36-.45.56-1.02.56-1.6v-7.1c0-2.76-2.24-5-5-5");
}

.q0903mb8p {
  stop-color: var(--svg-color--c3bdc9, #C3BDC9);
}

.q4ay10b-c {
  stop-color: var(--svg-color--696869, #696869);
}

.qn_6qbbex {
  fill: var(--svg-color--646169, #646169);
  d: path("M14.499 24.43v-1h-2.86c.05.34.1.67.17 1z");
}

.qqlloez7y {
  fill: var(--svg-color--3b3444, #3B3444);
  d: path("M12.499 27.46v-1h-2.15l.29 1z");
}

.r6v6gcb6b {
  stop-color: var(--svg-color--a8a0b1, #A8A0B1);
}

.rj82fccoa {
  stop-color: var(--svg-color--b2b1b3, #B2B1B3);
  stop-opacity: 0;
}

.rm_l-cc8e {
  stop-color: var(--svg-color--4c4653, #4C4653);
}

.sexd79bcd {
  d: path("M9.699 18.69c.33-.49.4-1.1.19-1.65l-.89-2.3c-.19-.49-.66-.81-1.18-.81h-1.32v1h1.32c.11 0 .21.07.25.17l.89 2.3c.09.24.06.51-.08.72c-.15.22-.38.35-.65.35h-1.3c.16.36.36.69.59 1h.71c.59 0 1.14-.29 1.47-.78");
}

.sgzndxb5m {
  stop-color: var(--svg-color--5c4c6b, #5C4C6B);
  stop-opacity: 0;
}

.swt4lnbbm {
  fill: var(--svg-color--5b5660, #5B5660);
  d: path("M14.516 27.46v-1h-2.15l.29 1z");
}

.sy5nff_mh {
  fill: var(--svg-color--3e3745, #3E3745);
  d: path("M12.499 24.43v-1h-2.86c.05.34.1.67.17 1z");
}

.sz8qc1bho {
  stroke: var(--svg-color--ebeaec, #EBEAEC);
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M13.34 13.614h10.82a4.216 4.216 0 0 1 4.215 4.215v7.16");
}

.t1dt-1bgk {
  stop-color: var(--svg-color--747375, #747375);
}

.tn364qfvv {
  d: path("M12.094 25.57c-.39-1.34-.594-2.74-.594-4.14c0-.704.953-.905 1.5-.905s1.516.211 1.516 1.227v8.418a.27.27 0 0 1-.266.26h-.547c-.12 0-.22-.08-.25-.19z");
}

.u_lr15bqk {
  stop-color: var(--svg-color--bcb2c8, #BCB2C8);
}

.ummnoccep {
  fill: var(--svg-color--6f6e70, #6F6E70);
  fill-rule: evenodd;
  d: path("M9.249 4.098V5.75c0 .886.714 1.6 1.6 1.6h1.279q-.195-.526-.48-1h-.8a.597.597 0 0 1-.6-.6V4.747a6 6 0 0 0-1-.65");
}

.uu-54ri1j {
  stop-color: var(--svg-color--b2b1b3, #B2B1B3);
}

.vljnzf_ql {
  d: path("m17.499 21.43l3.04 2.28a2.4 2.4 0 0 1 .48 3.36l-2.24 2.99c-.12.15-.01.37.18.37h1.22c.2 0 .39-.09.52-.25l3.24-4.05c.36-.45.56-1.02.56-1.6v-4.1h-7z");
}

.wc2crwbro {
  stop-color: var(--svg-color--cbcacd, #CBCACD);
  stop-opacity: 0;
}

.wn070w6dm {
  stop-color: var(--svg-color--7d7c7e, #7D7C7E);
  stop-opacity: 0;
}

.ws-ebtbdz {
  stop-color: var(--svg-color--444246, #444246);
  stop-opacity: 0;
}

.wysdbsbty {
  d: path("M12.499 12.43v-3a6 6 0 0 0-4.35-5.767c-.41-.117-.813-.266-1.166-.504L5.959 2.47a.312.312 0 0 0-.46.27c0 .878-.325 1.715-.923 2.359C3.468 6.294 1.76 8.13 1.76 8.13c-.22.25-.31.6-.23.94c.15.68.84 1.01 1.48.75l3.146-1.271a.25.25 0 0 1 .344.232v7.649c0 1.137.225 2.065 1.02 3.026C9.75 16.43 11 14.87 12.499 12.43");
}

.x_dkntb2t {
  d: path("M27.079 28.46h-2.1l-.75 1h2.05z");
}

.x01s_nb_e {
  stop-color: var(--svg-color--69676c, #69676C);
}

.xn03pwb0p {
  stop-color: var(--svg-color--69587a, #69587A);
  stop-opacity: 0;
}

.y4xdt7ayb {
  stop-color: var(--svg-color--453a50, #453A50);
}

.y9ey0pdvu {
  stop-color: var(--svg-color--5d5961, #5D5961);
}

.y9p0ywbnw {
  stop-color: var(--svg-color--896ba4, #896BA4);
}

.yu-vrccot {
  d: path("M29.499 19.19h-2.5c-.21 0-.31-.15-.34-.21a.37.37 0 0 1 .04-.4l2.38-3.15c-.15-.33-.33-.65-.54-.94l-2.64 3.5c-.32.42-.37.97-.13 1.45c.23.47.71.76 1.23.76h2.5z");
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z4vzfx2fx {
  cx: 5px;
  cy: 6.933px;
  r: 0.5px;
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

</style>
