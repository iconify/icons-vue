<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="nup83sn9j"/><path fill="url(#iqClXye)" class="gs5m-ccna"/><path fill="url(#ia7zTFd)" class="gs5m-ccna"/><path fill="url(#iRZUxLd)" class="gs5m-ccna"/><path fill="url(#ii8LQcc)" class="gs5m-ccna"/><g filter="url(#ieJCIjd)"><path class="feafmua8h"/></g><g filter="url(#ijuLtJI)"><path class="t3vrztbsm"/></g><path fill="url(#iWpqrxl)" class="p0ei18b7a"/><path fill="url(#iraQoIb)" class="mdlagmx-e"/><path fill="url(#ifCV9jZ)" class="c484q8_-g"/><path fill="url(#iSyPvtY)" class="ruhyj4z3o"/><path fill="url(#idrOozB)" class="gymiaqbxw"/><path fill="url(#iVbYmKe)" class="gymiaqbxw"/><path fill="url(#iBpphic)" class="kemn23e_x"/><path fill="url(#iaCgYze)" class="lpwlpbz5r"/><path fill="url(#iC5nRJj)" class="lpwlpbz5r"/><path fill="url(#iN2Kg1d)" class="yikceybik"/><path fill="url(#ijuDQ6c)" class="yikceybik"/><path fill="url(#iRdNUle)" class="yikceybik"/><path fill="url(#iNmLnxc)" class="yikceybik"/><g filter="url(#iW9SpIe)"><path fill="url(#i7zQrJc)" class="fes8yec0j"/><path fill="url(#id7Misc)" class="fes8yec0j"/><path fill="url(#iayqrqP)" class="fes8yec0j"/></g><path fill="url(#ijHxz1g)" class="u4by3ifev"/><path fill="url(#iJgP8te)" class="u4by3ifev"/><path fill="url(#iWkhOKb)" class="u4by3ifev"/><path fill="url(#ijHxz1g)" class="u4by3ifev"/><path fill="url(#iJgP8te)" class="u4by3ifev"/><path fill="url(#iWkhOKb)" class="u4by3ifev"/><path fill="url(#icXS2Sd)" class="aiw6v2buw"/><path fill="url(#iR7ylNc)" class="aiw6v2buw"/><path fill="url(#iLK4xib)" class="aiw6v2buw"/><defs><linearGradient id="iqClXye" x1="19.527" x2="19.527" y1="29.901" y2="26.25" gradientUnits="userSpaceOnUse"><stop offset=".178" class="ezq0aol0o"/><stop offset="1" class="qw5fzrqyg"/></linearGradient><linearGradient id="ia7zTFd" x1="30.277" x2="24.964" y1="21.313" y2="21.313" gradientUnits="userSpaceOnUse"><stop class="p6jsacbgg"/><stop offset="1" class="u0hdzpblp"/></linearGradient><linearGradient id="iRZUxLd" x1="2.001" x2="5.527" y1="18.75" y2="18.75" gradientUnits="userSpaceOnUse"><stop class="zn_cq6bqi"/><stop offset="1" class="ztgulqbpf"/></linearGradient><linearGradient id="iWpqrxl" x1="4.839" x2="4.839" y1="3.865" y2="29.877" gradientUnits="userSpaceOnUse"><stop class="g0dpuhghq"/><stop offset=".195" class="arukckn5v"/><stop offset=".861" class="arukckn5v"/><stop offset="1" class="j24az8j8v"/></linearGradient><linearGradient id="iraQoIb" x1="9.683" x2="8.808" y1="5.063" y2="29.901" gradientUnits="userSpaceOnUse"><stop offset=".032" class="li9cmgxtp"/><stop offset=".201" class="arukckn5v"/><stop offset=".821" class="dh66m6bwu"/><stop offset="1" class="w6wmx_fvl"/></linearGradient><linearGradient id="ifCV9jZ" x1="23.745" x2="22.87" y1="5.063" y2="29.901" gradientUnits="userSpaceOnUse"><stop class="pzwe3fbfh"/><stop offset=".201" class="ghkgt8bnw"/><stop offset=".821" class="t8u0hib7l"/><stop offset="1" class="aw2g63ipt"/></linearGradient><linearGradient id="iSyPvtY" x1="27.105" x2="27.105" y1="3.963" y2="29.834" gradientUnits="userSpaceOnUse"><stop class="f7uhaybbw"/><stop offset=".195" class="xnguepb6l"/><stop offset=".832" class="qv4z7041y"/><stop offset="1" class="i0f64nbug"/></linearGradient><linearGradient id="idrOozB" x1="13.339" x2="19.322" y1="15.313" y2="15.313" gradientUnits="userSpaceOnUse"><stop class="xw3lf2b4s"/><stop offset="1" class="pzwe3fbfh"/></linearGradient><linearGradient id="iVbYmKe" x1="19.322" x2="17.995" y1="10.531" y2="12.906" gradientUnits="userSpaceOnUse"><stop offset=".228" class="mw9v9vpkb"/><stop offset="1" class="z_v3dqxji"/></linearGradient><linearGradient id="iaCgYze" x1="15.931" x2="15.931" y1="2.13" y2="9.424" gradientUnits="userSpaceOnUse"><stop class="vnzf2acko"/><stop offset=".4" class="gozb1040e"/><stop offset="1" class="kee3eqq-e"/></linearGradient><linearGradient id="iC5nRJj" x1="18.202" x2="17.683" y1="7.09" y2="6.497" gradientUnits="userSpaceOnUse"><stop offset=".197" class="m5pmh2b_i"/><stop offset="1" class="r8145jbym"/></linearGradient><linearGradient id="iN2Kg1d" x1="15.922" x2="15.922" y1="11.932" y2="28.716" gradientUnits="userSpaceOnUse"><stop class="gh7-o2vvf"/><stop offset="1" class="jcbgltbtm"/></linearGradient><linearGradient id="ijuDQ6c" x1="11.911" x2="13.424" y1="21.839" y2="22.209" gradientUnits="userSpaceOnUse"><stop class="h15cxwb-o"/><stop offset="1" class="t3zhb7b1u"/></linearGradient><linearGradient id="iNmLnxc" x1="18.23" x2="17.73" y1="15.656" y2="15.797" gradientUnits="userSpaceOnUse"><stop class="vn9qoh31k"/><stop offset="1" class="rdvs42jzt"/></linearGradient><linearGradient id="i7zQrJc" x1="16" x2="16" y1="8.823" y2="13.089" gradientUnits="userSpaceOnUse"><stop offset=".115" class="i0882cbzh"/><stop offset="1" class="vcxg3vbpm"/></linearGradient><linearGradient id="ijHxz1g" x1="12.845" x2="10.79" y1="6.112" y2="9.195" gradientUnits="userSpaceOnUse"><stop offset=".034" class="ml56slbjd"/><stop offset="1" class="py8dnxbyy"/></linearGradient><linearGradient id="iJgP8te" x1="9.077" x2="10.752" y1="9.195" y2="8.167" gradientUnits="userSpaceOnUse"><stop class="ov6ozmbgz"/><stop offset="1" class="pks71zb0s"/></linearGradient><linearGradient id="iWkhOKb" x1="13.15" x2="12.465" y1="11.213" y2="9.995" gradientUnits="userSpaceOnUse"><stop class="c-5ljhfyl"/><stop offset="1" class="znthsytmr"/></linearGradient><linearGradient id="icXS2Sd" x1="23.541" x2="17.413" y1="7.406" y2="6.923" gradientUnits="userSpaceOnUse"><stop class="y3y1j0bmn"/><stop offset="1" class="py8dnxbyy"/></linearGradient><linearGradient id="iR7ylNc" x1="18.517" x2="19.659" y1="5.807" y2="6.923" gradientUnits="userSpaceOnUse"><stop class="kk1czch3m"/><stop offset="1" class="y5yf0lb2a"/></linearGradient><linearGradient id="iLK4xib" x1="18.694" x2="19.379" y1="11.213" y2="9.995" gradientUnits="userSpaceOnUse"><stop class="c-5ljhfyl"/><stop offset="1" class="znthsytmr"/></linearGradient><radialGradient id="ii8LQcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.75 51.2914 0 15.83 22.563)" gradientUnits="userSpaceOnUse"><stop offset=".804" class="z2vo-xbhd"/><stop offset="1" class="ck4m2ybgy"/></radialGradient><radialGradient id="iBpphic" cx="0" cy="0" r="1" gradientTransform="matrix(1.97031 0 0 9.6875 12.337 14.25)" gradientUnits="userSpaceOnUse"><stop class="xdfabr30j"/><stop offset="1" class="dio_a44_h"/></radialGradient><radialGradient id="iRdNUle" cx="0" cy="0" r="1" gradientTransform="matrix(3.45463 15.67278 -2.55128 .56236 17.992 13.888)" gradientUnits="userSpaceOnUse"><stop class="e98mdyhdy"/><stop offset="1" class="s4g7_9c6y"/></radialGradient><radialGradient id="id7Misc" cx="0" cy="0" r="1" gradientTransform="rotate(120.964 5.968 9.9)scale(2.18661 3.38003)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yeoe_dbow"/><stop offset="1" class="gc41fibdl"/></radialGradient><radialGradient id="iayqrqP" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 .82813 -3.40691 -2.31412 17.777 9.844)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="da_w2_96b"/><stop offset="1" class="dhvgteedf"/></radialGradient><filter id="ieJCIjd" width="10.152" height="10.722" x="6.57" y="2.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16352" stdDeviation=".4"/></filter><filter id="ijuLtJI" width="10.152" height="10.722" x="14.842" y="2.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_16352" stdDeviation=".4"/></filter><filter id="iW9SpIe" width="6.994" height="4.266" x="12.703" y="8.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.133333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_16352"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:necktie" /></template>
<style>
.aiw6v2buw {
  d: path("m21.388 10.984l3.166-7.463a1 1 0 0 0-.921-1.391h-.199a1.5 1.5 0 0 0-1.053.432l-6.385 6.293a.25.25 0 0 0 .042.389l3.602 2.284a1.2 1.2 0 0 0 1.747-.544");
}

.arukckn5v {
  stop-color: var(--svg-color--35bfff, #35BFFF);
}

.aw2g63ipt {
  stop-color: var(--svg-color--429aff, #429AFF);
}

.c-5ljhfyl {
  stop-color: var(--svg-color--b688ea, #B688EA);
}

.c484q8_-g {
  d: path("M22.34 29.9V3.649h1.062V29.9z");
}

.ck4m2ybgy {
  stop-color: var(--svg-color--529ef8, #529EF8);
}

.da_w2_96b {
  stop-color: var(--svg-color--291a5d, #291A5D);
}

.dh66m6bwu {
  stop-color: var(--svg-color--41ceff, #41CEFF);
}

.dhvgteedf {
  stop-color: var(--svg-color--291a5d, #291A5D);
  stop-opacity: 0;
}

.dio_a44_h {
  stop-color: var(--svg-color--297ff4, #297FF4);
}

.e98mdyhdy {
  stop-color: var(--svg-color--40457d, #40457D);
}

.ezq0aol0o {
  stop-color: var(--svg-color--5562f6, #5562F6);
}

.f7uhaybbw {
  stop-color: var(--svg-color--59ffff, #59FFFF);
}

.feafmua8h {
  fill: var(--svg-color--3453d2, #3453D2);
  d: path("M10.557 11.8L7.45 4.698c-.274-.627.2-1.323.904-1.323h.195c.387 0 .758.148 1.034.41l6.267 5.99a.234.234 0 0 1-.041.37l-3.536 2.174c-.614.377-1.43.13-1.715-.519");
}

.fes8yec0j {
  d: path("m13.786 12.608l-1.083-1.785l1.469-2l1.742.213l.617-.213l2.766 1.734l-1.285 2.06a1 1 0 0 1-.848.472H14.64a1 1 0 0 1-.855-.481");
}

.ft5dv1b6b {
  fill: none;
}

.g0dpuhghq {
  stop-color: var(--svg-color--51d8f2, #51D8F2);
}

.gc41fibdl {
  stop-color: var(--svg-color--4b3d74, #4B3D74);
  stop-opacity: 0;
}

.gh7-o2vvf {
  stop-color: var(--svg-color--332c70, #332C70);
}

.ghkgt8bnw {
  stop-color: var(--svg-color--41d7ff, #41D7FF);
}

.gozb1040e {
  stop-color: var(--svg-color--cecbd2, #CECBD2);
}

.gs5m-ccna {
  d: path("M2.001 8.448a4.8 4.8 0 0 1 4.8-4.8h18.057a4.8 4.8 0 0 1 4.8 4.8V26.1a3.8 3.8 0 0 1-3.8 3.8H5.801a3.8 3.8 0 0 1-3.8-3.8z");
}

.gymiaqbxw {
  d: path("M12.337 29.9V3.649h6.985V29.9z");
}

.h15cxwb-o {
  stop-color: var(--svg-color--142c63, #142C63);
}

.i0882cbzh {
  stop-color: var(--svg-color--362865, #362865);
}

.i0f64nbug {
  stop-color: var(--svg-color--49abff, #49ABFF);
}

.j24az8j8v {
  stop-color: var(--svg-color--4a96ff, #4A96FF);
}

.jcbgltbtm {
  stop-color: var(--svg-color--501069, #501069);
}

.kee3eqq-e {
  stop-color: var(--svg-color--9c8aad, #9C8AAD);
}

.kemn23e_x {
  d: path("M12.337 29.9V3.649h3.305V29.9z");
}

.kk1czch3m {
  stop-color: var(--svg-color--c6c3c9, #C6C3C9);
}

.li9cmgxtp {
  stop-color: var(--svg-color--2e8df9, #2E8DF9);
}

.lpwlpbz5r {
  d: path("M15.892 10.864L8.11 2.13h15.641z");
}

.m5pmh2b_i {
  stop-color: var(--svg-color--9b8aac, #9B8AAC);
}

.mdlagmx-e {
  d: path("M8.277 29.9V3.649h1.062V29.9z");
}

.ml56slbjd {
  stop-color: var(--svg-color--e1dee5, #E1DEE5);
}

.mw9v9vpkb {
  stop-color: var(--svg-color--2b8afd, #2B8AFD);
}

.nup83sn9j {
  fill: var(--svg-color--477ff4, #477FF4);
  d: path("M2.001 8.448a4.8 4.8 0 0 1 4.8-4.8h18.057a4.8 4.8 0 0 1 4.8 4.8V26.1a3.8 3.8 0 0 1-3.8 3.8H5.801a3.8 3.8 0 0 1-3.8-3.8z");
}

.ov6ozmbgz {
  stop-color: var(--svg-color--9f8cc4, #9F8CC4);
}

.p0ei18b7a {
  d: path("M4.308 29.596V4.346q.496-.304 1.062-.481v26.012a3.8 3.8 0 0 1-1.062-.28");
}

.p6jsacbgg {
  stop-color: var(--svg-color--6aa9ff, #6AA9FF);
}

.pks71zb0s {
  stop-color: var(--svg-color--bfa4db, #BFA4DB);
  stop-opacity: 0;
}

.py8dnxbyy {
  stop-color: var(--svg-color--caaee6, #CAAEE6);
}

.pzwe3fbfh {
  stop-color: var(--svg-color--40d1ff, #40D1FF);
}

.qv4z7041y {
  stop-color: var(--svg-color--4fecff, #4FECFF);
}

.qw5fzrqyg {
  stop-color: var(--svg-color--5562f6, #5562F6);
  stop-opacity: 0;
}

.r8145jbym {
  stop-color: var(--svg-color--b1a4bd, #B1A4BD);
  stop-opacity: 0;
}

.rdvs42jzt {
  stop-color: var(--svg-color--1b3d78, #1B3D78);
  stop-opacity: 0;
}

.ruhyj4z3o {
  d: path("M26.574 29.834V3.964q.572.22 1.062.569V29.46a3.8 3.8 0 0 1-1.062.374");
}

.s4g7_9c6y {
  stop-color: var(--svg-color--40457d, #40457D);
  stop-opacity: 0;
}

.t3vrztbsm {
  fill: var(--svg-color--3453d2, #3453D2);
  d: path("m21.007 11.8l3.108-7.102c.275-.627-.2-1.323-.904-1.323h-.195c-.387 0-.758.148-1.033.41l-6.268 5.99a.234.234 0 0 0 .041.37l3.536 2.174c.614.377 1.431.13 1.715-.519");
}

.t3zhb7b1u {
  stop-color: var(--svg-color--381d62, #381D62);
  stop-opacity: 0;
}

.t8u0hib7l {
  stop-color: var(--svg-color--42d5ff, #42D5FF);
}

.u0hdzpblp {
  stop-color: var(--svg-color--6aa9ff, #6AA9FF);
  stop-opacity: 0;
}

.u4by3ifev {
  d: path("M10.456 10.984L7.29 3.52a1 1 0 0 1 .92-1.391h.2a1.5 1.5 0 0 1 1.052.432l6.385 6.293a.25.25 0 0 1-.041.389l-3.602 2.284a1.2 1.2 0 0 1-1.748-.544");
}

.vcxg3vbpm {
  stop-color: var(--svg-color--461368, #461368);
}

.vn9qoh31k {
  stop-color: var(--svg-color--1b3d78, #1B3D78);
}

.vnzf2acko {
  stop-color: var(--svg-color--cbcbcc, #CBCBCC);
}

.w6wmx_fvl {
  stop-color: var(--svg-color--629bff, #629BFF);
}

.xdfabr30j {
  stop-color: var(--svg-color--297ff4, #297FF4);
  stop-opacity: 0;
}

.xnguepb6l {
  stop-color: var(--svg-color--4dedff, #4DEDFF);
}

.xw3lf2b4s {
  stop-color: var(--svg-color--3dbcff, #3DBCFF);
}

.y3y1j0bmn {
  stop-color: var(--svg-color--f6f2fc, #F6F2FC);
}

.y5yf0lb2a {
  stop-color: var(--svg-color--d8d0e2, #D8D0E2);
  stop-opacity: 0;
}

.yeoe_dbow {
  stop-color: var(--svg-color--4b3d74, #4B3D74);
}

.yikceybik {
  d: path("m10.563 29.9l3.75-17.247l3.03-.72L21.282 29.9z");
}

.z_v3dqxji {
  stop-color: var(--svg-color--2b8afd, #2B8AFD);
  stop-opacity: 0;
}

.z2vo-xbhd {
  stop-color: var(--svg-color--529ef8, #529EF8);
  stop-opacity: 0;
}

.zn_cq6bqi {
  stop-color: var(--svg-color--4c76bf, #4C76BF);
}

.znthsytmr {
  stop-color: var(--svg-color--c8a6ea, #C8A6EA);
  stop-opacity: 0;
}

.ztgulqbpf {
  stop-color: var(--svg-color--4c76bf, #4C76BF);
  stop-opacity: 0;
}

</style>
