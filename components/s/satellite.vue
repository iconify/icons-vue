<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3lKIMY)" class="i9jqvw7jt"/><path fill="url(#iZMuGvc)" class="plqx7txoj"/><path fill="url(#i5Uec6b)" class="plqx7txoj"/><g filter="url(#iIlv9qd)"><path fill="url(#iwjqFVc)" class="uoug7fbgr"/></g><path fill="url(#iOsy20c)" class="uoug7fbgr"/><path fill="url(#iZmeflb)" class="uoug7fbgr"/><path fill="url(#i1xZlEc)" class="h4t3tcbbu"/><path fill="url(#it90TKe)" class="wf5wb5bvn"/><path fill="url(#iL7sh4c)" class="wf5wb5bvn"/><path fill="url(#ia1vMvc)" class="wf5wb5bvn"/><path fill="url(#icFjqxp)" class="gnxk2jb6s"/><path fill="url(#imHVvhd)" class="jb_xeobil"/><path fill="url(#iCoP5Ly)" class="jb_xeobil"/><path fill="url(#iPQ9Umj)" class="st6yblbaq"/><path fill="url(#iV8ifBb)" class="st6yblbaq"/><path fill="url(#i6r8Vgb)" class="st6yblbaq"/><path fill="url(#iRmsGcb)" class="st6yblbaq"/><path fill="url(#iRxMcde)" class="dwv8uaczr"/><path fill="url(#ibA6pIe)" class="pcu8utbaw"/><path fill="url(#iirHz6b)" class="ol64g4vof"/><path fill="url(#iYGjiIe)" class="k37-poaia"/><g filter="url(#iINGZ9c)"><path fill="url(#iCo7Iue)" class="ciiy2jwej"/></g><path fill="url(#i5kmy3j)" class="ciiy2jwej"/><path fill="url(#iRzpiCw)" class="f8_cugcua"/><path fill="url(#iPaaVEJ)" class="bfrac8bhb"/><path fill="url(#i1pfvIc)" class="e86pssb1z"/><path fill="url(#i5DtNed)" class="qgv0j_blb"/><path fill="url(#iQ2tr0o)" class="qgv0j_blb"/><path fill="url(#ipsIedd)" class="qgv0j_blb"/><path fill="url(#iaQxCOb)" class="qgv0j_blb"/><defs><linearGradient id="i3lKIMY" x1="19.448" x2="19.837" y1="18.872" y2="18.317" gradientUnits="userSpaceOnUse"><stop class="jjww-03bw"/><stop offset="1" class="dz_ee-s2p"/></linearGradient><linearGradient id="iZMuGvc" x1="20.378" x2="18.843" y1="9.01" y2="11.218" gradientUnits="userSpaceOnUse"><stop class="lcg121p_c"/><stop offset=".203" class="oq_y79bjc"/><stop offset=".784" class="oq_y79bjc"/><stop offset="1" class="bhx0owbbz"/></linearGradient><linearGradient id="i5Uec6b" x1="16.109" x2="20.14" y1="7.89" y2="11.046" gradientUnits="userSpaceOnUse"><stop class="o-jxcsp4c"/><stop offset="1" class="aw2fuh2hg"/></linearGradient><linearGradient id="iwjqFVc" x1="18.559" x2="27.22" y1="27.211" y2="14.742" gradientUnits="userSpaceOnUse"><stop class="e9i83h23y"/><stop offset="1" class="e8c95xorb"/></linearGradient><linearGradient id="iOsy20c" x1="26.553" x2="25.834" y1="21.46" y2="20.976" gradientUnits="userSpaceOnUse"><stop class="b4vmhze6i"/><stop offset="1" class="eqt9dyrdh"/></linearGradient><linearGradient id="iZmeflb" x1="20.805" x2="21.677" y1="18.325" y2="18.828" gradientUnits="userSpaceOnUse"><stop class="b4vmhze6i"/><stop offset="1" class="eqt9dyrdh"/></linearGradient><linearGradient id="i1xZlEc" x1="11.705" x2="13.234" y1="21.382" y2="19.181" gradientUnits="userSpaceOnUse"><stop class="sq5nrkbki"/><stop offset="1" class="m76zvyxdf"/></linearGradient><linearGradient id="it90TKe" x1="18.585" x2="21.116" y1="13.388" y2="11.388" gradientUnits="userSpaceOnUse"><stop class="vkrbqr7kl"/><stop offset="1" class="esq_w8bks"/></linearGradient><linearGradient id="iL7sh4c" x1="14.905" x2="17.46" y1="10.075" y2="11.825" gradientUnits="userSpaceOnUse"><stop class="drxdvw-xc"/><stop offset="1" class="n10nl1bfg"/></linearGradient><linearGradient id="ia1vMvc" x1="21.101" x2="20.726" y1="12.481" y2="12.919" gradientUnits="userSpaceOnUse"><stop class="iyavs5hnm"/><stop offset="1" class="s3klhs7vr"/></linearGradient><linearGradient id="icFjqxp" x1="8.153" x2="9.682" y1="26.52" y2="24.318" gradientUnits="userSpaceOnUse"><stop class="sq5nrkbki"/><stop offset="1" class="m76zvyxdf"/></linearGradient><linearGradient id="iRmsGcb" x1="11.773" x2="12.496" y1="21.346" y2="20.294" gradientUnits="userSpaceOnUse"><stop class="y6-24nbdy"/><stop offset=".797" class="jaa6gf1tp"/></linearGradient><linearGradient id="iRxMcde" x1="26.2" x2="24.671" y1="16.21" y2="18.411" gradientUnits="userSpaceOnUse"><stop class="jpdemgbwp"/><stop offset="1" class="xp4k3ebnc"/></linearGradient><linearGradient id="ibA6pIe" x1="23.652" x2="22.123" y1="19.879" y2="22.081" gradientUnits="userSpaceOnUse"><stop class="jpdemgbwp"/><stop offset="1" class="xp4k3ebnc"/></linearGradient><linearGradient id="iirHz6b" x1="21.103" x2="19.574" y1="23.548" y2="25.75" gradientUnits="userSpaceOnUse"><stop class="jpdemgbwp"/><stop offset="1" class="xp4k3ebnc"/></linearGradient><linearGradient id="iYGjiIe" x1="11.248" x2="11.758" y1="13.44" y2="12.706" gradientUnits="userSpaceOnUse"><stop class="jjww-03bw"/><stop offset="1" class="dz_ee-s2p"/></linearGradient><linearGradient id="iCo7Iue" x1="3.87" x2="12.535" y1="17.018" y2="4.542" gradientUnits="userSpaceOnUse"><stop class="evkubdkql"/><stop offset="1" class="ebf26xe8r"/></linearGradient><linearGradient id="i5kmy3j" x1="11.866" x2="11.148" y1="11.263" y2="10.779" gradientUnits="userSpaceOnUse"><stop class="b4vmhze6i"/><stop offset="1" class="eqt9dyrdh"/></linearGradient><linearGradient id="iRzpiCw" x1="6.418" x2="4.889" y1="13.349" y2="15.551" gradientUnits="userSpaceOnUse"><stop class="ph6clsjam"/><stop offset="1" class="ecdy-bkqu"/></linearGradient><linearGradient id="iPaaVEJ" x1="8.967" x2="7.438" y1="9.68" y2="11.881" gradientUnits="userSpaceOnUse"><stop class="ud7o-nbas"/><stop offset="1" class="dkt0qqbge"/></linearGradient><linearGradient id="i1pfvIc" x1="11.515" x2="9.986" y1="6.01" y2="8.211" gradientUnits="userSpaceOnUse"><stop class="bv9mpmooi"/><stop offset="1" class="ezzdusbdi"/></linearGradient><linearGradient id="i5DtNed" x1="13.253" x2="17.84" y1="19.184" y2="12.579" gradientUnits="userSpaceOnUse"><stop class="clhf_2jlz"/><stop offset=".09" class="b0hon_b8a"/><stop offset=".909" class="b0hon_b8a"/><stop offset="1" class="v4p5pkbin"/></linearGradient><linearGradient id="iQ2tr0o" x1="11.841" x2="15.546" y1="13.11" y2="15.483" gradientUnits="userSpaceOnUse"><stop class="qe_nrwybn"/><stop offset="1" class="w_ytsjgoo"/></linearGradient><radialGradient id="imHVvhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.81327 -2.96952 0 7.906 26.36)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="c9japsb2c"/><stop offset="1" class="x7266q1wu"/></radialGradient><radialGradient id="iCoP5Ly" cx="0" cy="0" r="1" gradientTransform="matrix(.10253 -3.15625 2.78328 .09041 7.804 28.575)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="dib12bcfv"/><stop offset=".953" class="pimtg_bcq"/></radialGradient><radialGradient id="iPQ9Umj" cx="0" cy="0" r="1" gradientTransform="rotate(124.824 .174 14.58)scale(3.50223 5.57512)" gradientUnits="userSpaceOnUse"><stop class="x39h03s9k"/><stop offset="1" class="ktp8chb5l"/></radialGradient><radialGradient id="iV8ifBb" cx="0" cy="0" r="1" gradientTransform="rotate(-145.243 10.85 11.303)scale(9.84795 1.06545)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="vg79pwryr"/><stop offset="1" class="esscwkbrq"/></radialGradient><radialGradient id="i6r8Vgb" cx="0" cy="0" r="1" gradientTransform="rotate(-123.588 13.4 10.051)scale(8.47906 7.76128)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="rcnui0bxp"/><stop offset="1" class="a2toggb9d"/></radialGradient><radialGradient id="ipsIedd" cx="0" cy="0" r="1" gradientTransform="rotate(-153.324 13.565 7.534)scale(7.23928 7.23945)" gradientUnits="userSpaceOnUse"><stop class="gjrlqlbhh"/><stop offset="1" class="e3o0o5b9c"/></radialGradient><radialGradient id="iaQxCOb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90626 -2.59374 .33807 -.50914 22.023 15.45)" gradientUnits="userSpaceOnUse"><stop class="o-4z4tbfb"/><stop offset="1" class="ps0a30bgj"/></radialGradient><filter id="iIlv9qd" width="13.723" height="16.364" x="16.026" y="12.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.384314 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12983"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.176471 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12983" result="effect2_innerShadow_18_12983"/></filter><filter id="iINGZ9c" width="13.728" height="16.368" x="1.336" y="2.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.352941 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12983"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.211765 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12983" result="effect2_innerShadow_18_12983"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:satellite" /></template>
<style>
.a2toggb9d {
  stop-color: var(--svg-color--97949b, #97949B);
}

.aw2fuh2hg {
  stop-color: var(--svg-color--838284, #838284);
  stop-opacity: 0;
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.b4vmhze6i {
  stop-color: var(--svg-color--252229, #252229);
}

.bfrac8bhb {
  d: path("M7.727 9.118a.25.25 0 0 1 .348-.063L9.866 10.3a.25.25 0 0 1 .063.348l-1.244 1.791a.25.25 0 0 1-.348.063l-1.79-1.244a.25.25 0 0 1-.064-.348z");
}

.bhx0owbbz {
  stop-color: var(--svg-color--6e5286, #6E5286);
}

.bv9mpmooi {
  stop-color: var(--svg-color--6d5fa4, #6D5FA4);
}

.c9japsb2c {
  stop-color: var(--svg-color--a99eb4, #A99EB4);
}

.ciiy2jwej {
  d: path("m10.682 3.25l3.706 2.575a.877.877 0 0 1 .22 1.218L6.936 18.088a.877.877 0 0 1-1.218.22l-3.706-2.574a.877.877 0 0 1-.22-1.22L9.464 3.47a.883.883 0 0 1 1.218-.22");
}

.clhf_2jlz {
  stop-color: var(--svg-color--8a64aa, #8A64AA);
}

.dib12bcfv {
  stop-color: var(--svg-color--8f8898, #8F8898);
  stop-opacity: 0;
}

.dkt0qqbge {
  stop-color: var(--svg-color--8656e2, #8656E2);
}

.drxdvw-xc {
  stop-color: var(--svg-color--70667a, #70667A);
}

.dwv8uaczr {
  d: path("m27.1 16.83l-1.791-1.244a.25.25 0 0 0-.348.062l-1.244 1.791a.25.25 0 0 0 .063.348l1.79 1.244a.25.25 0 0 0 .349-.062l1.244-1.792a.25.25 0 0 0-.063-.347");
}

.dz_ee-s2p {
  stop-color: var(--svg-color--515152, #515152);
}

.e3o0o5b9c {
  stop-color: var(--svg-color--9689a1, #9689A1);
  stop-opacity: 0;
}

.e86pssb1z {
  d: path("M10.276 5.448a.25.25 0 0 1 .348-.062l1.79 1.244a.25.25 0 0 1 .064.348l-1.244 1.79a.25.25 0 0 1-.348.063L9.095 7.587a.25.25 0 0 1-.063-.348z");
}

.e8c95xorb {
  stop-color: var(--svg-color--473855, #473855);
}

.e9i83h23y {
  stop-color: var(--svg-color--312d37, #312D37);
}

.ebf26xe8r {
  stop-color: var(--svg-color--38363a, #38363A);
}

.ecdy-bkqu {
  stop-color: var(--svg-color--8554e1, #8554E1);
}

.eqt9dyrdh {
  stop-color: var(--svg-color--252229, #252229);
  stop-opacity: 0;
}

.esq_w8bks {
  stop-color: var(--svg-color--7a6d87, #7A6D87);
}

.esscwkbrq {
  stop-color: var(--svg-color--9a71be, #9A71BE);
  stop-opacity: 0;
}

.evkubdkql {
  stop-color: var(--svg-color--4a385c, #4A385C);
}

.ezzdusbdi {
  stop-color: var(--svg-color--8858e2, #8858E2);
}

.f8_cugcua {
  d: path("M5.179 12.788a.25.25 0 0 1 .348-.063l1.79 1.244a.25.25 0 0 1 .063.348l-1.244 1.79a.25.25 0 0 1-.348.063l-1.79-1.244a.25.25 0 0 1-.063-.348z");
}

.ft5dv1b6b {
  fill: none;
}

.gjrlqlbhh {
  stop-color: var(--svg-color--9689a1, #9689A1);
}

.gnxk2jb6s {
  d: path("m10.057 24.575l-.74-.515l-1.53 2.202l.741.514z");
}

.h4t3tcbbu {
  d: path("m13.606 19.435l-.734-.51l-1.53 2.202l.734.51z");
}

.i9jqvw7jt {
  d: path("m20.742 18.941l-1.797-1.248l-.51.734l1.797 1.248z");
}

.iyavs5hnm {
  stop-color: var(--svg-color--58406e, #58406E);
}

.jaa6gf1tp {
  stop-color: var(--svg-color--67616e, #67616E);
}

.jb_xeobil {
  d: path("M7.142 27.989a1.34 1.34 0 1 0 1.529-2.201a1.34 1.34 0 0 0-1.53 2.201");
}

.jjww-03bw {
  stop-color: var(--svg-color--281e30, #281E30);
}

.jpdemgbwp {
  stop-color: var(--svg-color--7048b7, #7048B7);
}

.k37-poaia {
  d: path("m11.03 12.195l1.467 1.02l-.51.734l-1.467-1.02z");
}

.ktp8chb5l {
  stop-color: var(--svg-color--aaa9ab, #AAA9AB);
}

.lcg121p_c {
  stop-color: var(--svg-color--c0c0c1, #C0C0C1);
}

.m76zvyxdf {
  stop-color: var(--svg-color--21122f, #21122F);
}

.n10nl1bfg {
  stop-color: var(--svg-color--949494, #949494);
  stop-opacity: 0;
}

.o-4z4tbfb {
  stop-color: var(--svg-color--c5c3c7, #C5C3C7);
}

.o-jxcsp4c {
  stop-color: var(--svg-color--838284, #838284);
}

.ol64g4vof {
  d: path("m22.003 24.168l-1.791-1.244a.25.25 0 0 0-.348.063l-1.244 1.79a.25.25 0 0 0 .062.349l1.791 1.244a.25.25 0 0 0 .348-.063l1.244-1.791a.25.25 0 0 0-.062-.348");
}

.oq_y79bjc {
  stop-color: var(--svg-color--92899b, #92899B);
}

.pcu8utbaw {
  d: path("m24.551 20.499l-1.79-1.244a.25.25 0 0 0-.349.063l-1.244 1.79a.25.25 0 0 0 .063.349l1.791 1.244a.25.25 0 0 0 .348-.063l1.244-1.791a.25.25 0 0 0-.063-.348");
}

.ph6clsjam {
  stop-color: var(--svg-color--6a5ba1, #6A5BA1);
}

.pimtg_bcq {
  stop-color: var(--svg-color--8f8898, #8F8898);
}

.plqx7txoj {
  d: path("m21.559 13.083l-5.41-3.757a.72.72 0 0 1-.18-1.008l.698-1.005a.72.72 0 0 1 1.007-.181l5.409 3.756c.33.23.41.677.181 1.008l-.698 1.005a.715.715 0 0 1-1.007.181");
}

.ps0a30bgj {
  stop-color: var(--svg-color--c5c3c7, #C5C3C7);
  stop-opacity: 0;
}

.qe_nrwybn {
  stop-color: var(--svg-color--8e8d8f, #8E8D8F);
}

.qgv0j_blb {
  d: path("m15.96 21.059l-5.41-3.757a.72.72 0 0 1-.181-1.007l3.757-5.41a.72.72 0 0 1 1.007-.18l5.409 3.756c.33.23.41.677.181 1.008l-3.756 5.408a.715.715 0 0 1-1.008.182");
}

.rcnui0bxp {
  stop-color: var(--svg-color--97949b, #97949B);
  stop-opacity: 0;
}

.s3klhs7vr {
  stop-color: var(--svg-color--58406e, #58406E);
  stop-opacity: 0;
}

.sq5nrkbki {
  stop-color: var(--svg-color--28202f, #28202F);
}

.st6yblbaq {
  d: path("m12.376 26.186l-5.379-3.737a1.038 1.038 0 0 1-.05-1.666a4.468 4.468 0 0 1 7.001 4.862c-.206.673-1 .938-1.572.54");
}

.ud7o-nbas {
  stop-color: var(--svg-color--6a5ca1, #6A5CA1);
}

.uoug7fbgr {
  d: path("m20.408 28.5l-3.706-2.574a.877.877 0 0 1-.22-1.218l7.666-11.038a.877.877 0 0 1 1.22-.22l3.705 2.575a.877.877 0 0 1 .22 1.218L21.62 28.288a.87.87 0 0 1-1.213.212");
}

.v4p5pkbin {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
}

.vg79pwryr {
  stop-color: var(--svg-color--9a71be, #9A71BE);
}

.vkrbqr7kl {
  stop-color: var(--svg-color--939195, #939195);
}

.w_ytsjgoo {
  stop-color: var(--svg-color--8e8d8f, #8E8D8F);
  stop-opacity: 0;
}

.wf5wb5bvn {
  d: path("m21.508 12.945l-5.284-3.67l-1.32 1.899l5.285 3.67z");
}

.x39h03s9k {
  stop-color: var(--svg-color--cfc9d6, #CFC9D6);
}

.x7266q1wu {
  stop-color: var(--svg-color--a27fc3, #A27FC3);
}

.xp4k3ebnc {
  stop-color: var(--svg-color--66559f, #66559F);
}

.y6-24nbdy {
  stop-color: var(--svg-color--67616e, #67616E);
  stop-opacity: 0;
}

</style>
