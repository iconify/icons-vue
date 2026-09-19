<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="f_s3udb7k"/><path fill="url(#iVKgcbb)" class="kbhx5eb4x"/><path fill="url(#ivpDJ8b)" class="kbhx5eb4x"/><path fill="url(#ixiu4Jc)" class="kbhx5eb4x"/><path fill="url(#i1sGBgb)" class="kbhx5eb4x"/><path fill="url(#iOGItpe)" class="kbhx5eb4x"/><path fill="url(#iPATq0i)" class="lxq61sbym"/><path fill="url(#i7U9Emb)" class="lxq61sbym"/><path fill="url(#iKkcJCb)" class="lxq61sbym"/><path fill="url(#iyzeYVc)" class="lxq61sbym"/><path fill="url(#izouA8b)" class="lxq61sbym"/><g filter="url(#i07i1pe)"><path fill="url(#iaL5Cdd)" class="dtw7ug7jc"/><path fill="url(#iMTZjlb)" class="dtw7ug7jc"/><path fill="url(#iSPOvfd)" class="dtw7ug7jc"/></g><g filter="url(#iHj0Ctc)"><path fill="url(#ivceOob)" class="rkgbv5bmz"/><path fill="url(#iAX39ne)" class="rkgbv5bmz"/><path fill="url(#iG7eEIb)" class="rkgbv5bmz"/></g><g filter="url(#iBM41Ke)"><path class="bddoai5px"/><path fill="url(#ieFifId)" class="uspv73yga"/><path fill="url(#iCGXIed)" class="uspv73yga"/><path fill="url(#iLZ0kld)" class="uspv73yga"/></g><g filter="url(#iMEgDpc)"><path fill="url(#iT7lZJb)" class="zb1t1wb8v"/></g><g filter="url(#iBDJvvb)"><path fill="url(#io81NzP)" class="rd3u85-sz"/></g><defs><radialGradient id="iVKgcbb" cx="0" cy="0" r="1" gradientTransform="matrix(10.2623 8.87497 -9.18398 10.6196 2.433 5.205)" gradientUnits="userSpaceOnUse"><stop class="qbgxppb7z"/><stop offset="1" class="u_zgrrbfz"/></radialGradient><radialGradient id="ivpDJ8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.71522 4.39205 -6.53585 2.55243 17.84 3.497)" gradientUnits="userSpaceOnUse"><stop offset=".266" class="yclo9pbdx"/><stop offset="1" class="drf2_2-nl"/></radialGradient><radialGradient id="ixiu4Jc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0236 3.2091 -6.1489 -1.9613 13 4.624)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="xm6e_wb5j"/><stop offset="1" class="e9xr8wbfs"/></radialGradient><radialGradient id="i1sGBgb" cx="0" cy="0" r="1" gradientTransform="matrix(4.1497 -1.93652 2.21216 4.74034 4.745 19.397)" gradientUnits="userSpaceOnUse"><stop class="d1gegdxhm"/><stop offset="1" class="hvr0epg6a"/></radialGradient><radialGradient id="iOGItpe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99187 -3.15375 4.75952 -3.00605 27.928 17.295)" gradientUnits="userSpaceOnUse"><stop class="har94pb2j"/><stop offset="1" class="dqarw_04t"/></radialGradient><radialGradient id="iPATq0i" cx="0" cy="0" r="1" gradientTransform="rotate(173.508 10.262 11.255)scale(16.149 16.858)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="qwesrtbki"/><stop offset="1" class="aigmeeb9r"/></radialGradient><radialGradient id="i7U9Emb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71122 -13.44496 3.47426 -.7006 11.938 31.293)" gradientUnits="userSpaceOnUse"><stop class="gr129pp3o"/><stop offset="1" class="a-cwi7bip"/></radialGradient><radialGradient id="iKkcJCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.82094 3.7266 0 15.857 23.52)" gradientUnits="userSpaceOnUse"><stop class="et6kbacvk"/><stop offset="1" class="r79ivlq6g"/></radialGradient><radialGradient id="iyzeYVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.5207 4.64766 0 17.581 24.654)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="om03kib-j"/><stop offset="1" class="dfvyn5b_x"/></radialGradient><radialGradient id="izouA8b" cx="0" cy="0" r="1" gradientTransform="rotate(-112.455 16.401 8.966)scale(9.1635 2.83681)" gradientUnits="userSpaceOnUse"><stop class="erwgcyy2b"/><stop offset="1" class="kcdyz5b5v"/></radialGradient><radialGradient id="iaL5Cdd" cx="0" cy="0" r="1" gradientTransform="rotate(130.48 4.425 6.599)scale(15.3655 15.7978)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="cfluiy-al"/><stop offset="1" class="x0h1i926q"/></radialGradient><radialGradient id="iMTZjlb" cx="0" cy="0" r="1" gradientTransform="rotate(49.774 -3.623 3.65)scale(11.0446 11.2576)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="qbgxppb7z"/><stop offset="1" class="u_zgrrbfz"/></radialGradient><radialGradient id="iSPOvfd" cx="0" cy="0" r="1" gradientTransform="rotate(135.919 4.975 7.662)scale(8.26537 7.73692)" gradientUnits="userSpaceOnUse"><stop class="k18fg7ooi"/><stop offset="1" class="xxsdgczib"/></radialGradient><radialGradient id="ivceOob" cx="0" cy="0" r="1" gradientTransform="matrix(3.78947 14.88872 -15.30757 3.89607 19.198 4.06)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="agplp2btk"/><stop offset="1" class="fky1q6bty"/></radialGradient><radialGradient id="iAX39ne" cx="0" cy="0" r="1" gradientTransform="rotate(62.418 3.096 18.834)scale(5.30463 5.65926)" gradientUnits="userSpaceOnUse"><stop class="taavcbpov"/><stop offset="1" class="cchmodkxu"/></radialGradient><radialGradient id="iG7eEIb" cx="0" cy="0" r="1" gradientTransform="rotate(146.768 11.161 8.643)scale(7.29892 6.07636)" gradientUnits="userSpaceOnUse"><stop class="k18fg7ooi"/><stop offset="1" class="xxsdgczib"/></radialGradient><radialGradient id="ieFifId" cx="0" cy="0" r="1" gradientTransform="matrix(3.00658 -6.8296 5.26225 2.31658 10.812 8.632)" gradientUnits="userSpaceOnUse"><stop class="jih0deptr"/><stop offset="1" class="tv4hqwb6d"/></radialGradient><radialGradient id="iCGXIed" cx="0" cy="0" r="1" gradientTransform="rotate(154.978 10.799 5.765)scale(7.96383 3.74152)" gradientUnits="userSpaceOnUse"><stop class="qzooa0bqp"/><stop offset="1" class="lgqrz40-g"/></radialGradient><radialGradient id="iLZ0kld" cx="0" cy="0" r="1" gradientTransform="matrix(-6.24567 -6.56135 3.87629 -3.6898 16.497 14.176)" gradientUnits="userSpaceOnUse"><stop class="qzooa0bqp"/><stop offset="1" class="lgqrz40-g"/></radialGradient><filter id="i07i1pe" width="16.897" height="16.951" x="1.342" y="3.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5101" stdDeviation=".5"/></filter><filter id="iHj0Ctc" width="16.897" height="16.489" x="13.061" y="3.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5101" stdDeviation=".5"/></filter><filter id="iBM41Ke" width="17.276" height="5.069" x="7.168" y="4.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5101" stdDeviation=".125"/></filter><filter id="iMEgDpc" width="9.065" height="13.774" x="17.407" y="15.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5101" stdDeviation="1"/></filter><filter id="iBDJvvb" width="7.624" height="10.303" x="7.586" y="18.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5101" stdDeviation="1"/></filter><linearGradient id="iT7lZJb" x1="23.335" x2="21.94" y1="17.738" y2="28.195" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="io81NzP" x1="12.989" x2="10.886" y1="27.182" y2="18.803" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tooth" /></template>
<style>
.a-cwi7bip {
  stop-color: var(--svg-color--d7bee7, #D7BEE7);
  stop-opacity: 0;
}

.agplp2btk {
  stop-color: var(--svg-color--d7c5e2, #D7C5E2);
  stop-opacity: 0;
}

.aigmeeb9r {
  stop-color: var(--svg-color--a097a7, #A097A7);
}

.bddoai5px {
  fill: var(--svg-color--cac9ca, #CAC9CA);
  d: path("M7.62 5.705c-.21-.04-.278-.3-.1-.416c1.135-.743 3.306-1.506 5.4-.178c1.732 1.097 2.041 1.311 2.384 1.415a1.6 1.6 0 0 0 1.005 0c.343-.104.652-.318 2.383-1.415c2.096-1.328 4.266-.565 5.4.178c.178.116.11.375-.099.416c-1.643.321-3.62.979-5.118 1.922c-1.484.934-2.02 1.218-3.068 1.328c-1.049-.11-1.585-.394-3.069-1.328c-1.497-.943-3.475-1.6-5.118-1.922");
}

.cchmodkxu {
  stop-color: var(--svg-color--a5a5a6, #A5A5A6);
  stop-opacity: 0;
}

.cfluiy-al {
  stop-color: var(--svg-color--baa5c7, #BAA5C7);
  stop-opacity: 0;
}

.d1gegdxhm {
  stop-color: var(--svg-color--b7a2c3, #B7A2C3);
}

.dfvyn5b_x {
  stop-color: var(--svg-color--cfbade, #CFBADE);
  stop-opacity: 0;
}

.dqarw_04t {
  stop-color: var(--svg-color--d1c2da, #D1C2DA);
  stop-opacity: 0;
}

.drf2_2-nl {
  stop-color: var(--svg-color--a8a8a8, #A8A8A8);
  stop-opacity: 0;
}

.dtw7ug7jc {
  d: path("M9.116 19.01c4.484 0 8.122-4.097 8.122-8.581c0-1.59-.457-3.074-1.247-4.327c-.255.08-.476.118-.618.13a3.55 3.55 0 0 1-1.597-.605a7 7 0 0 0-.24-.188l-.015-.012h-.001A6.94 6.94 0 0 0 9.37 4.06c-3.849 0-7.03 2.905-7.03 6.97c0 2.525 1.422 4.786 3.466 6.287l.104.076c.34.248.604.44.78.787c.654.582 1.579.831 2.425.831");
}

.e9xr8wbfs {
  stop-color: var(--svg-color--ececec, #ECECEC);
  stop-opacity: 0;
}

.erwgcyy2b {
  stop-color: var(--svg-color--fff2ff, #FFF2FF);
}

.et6kbacvk {
  stop-color: var(--svg-color--cab1db, #CAB1DB);
}

.f_s3udb7k {
  fill: var(--svg-color--e3dfe7, #E3DFE7);
  d: path("M15.857 5.839a3.8 3.8 0 0 1-1.712-.652a7 7 0 0 0-.258-.203l-.016-.014l-.001.002a7.4 7.4 0 0 0-4.449-1.475c-4.128 0-7.538 3.13-7.538 7.51c0 2.722 1.523 5.159 3.716 6.776l.112.082c.558.409.923.675 1.054 1.62c.114 2.398.624 4.75 2.016 6.744c.454.65.975 1.286 1.558 1.838c.819.622 2.474.828 2.817-1.112l.56-4.61c.124-1.116.752-2.762 2.141-2.765c1.39.003 2.018 1.65 2.142 2.765l.56 4.61c.343 1.94 1.998 1.734 2.816 1.112a12 12 0 0 0 1.559-1.838c1.392-1.994 1.902-4.346 2.016-6.743c.131-.946.495-1.213 1.054-1.621l.112-.082c2.192-1.617 3.716-4.054 3.716-6.776c0-4.38-3.41-7.51-7.539-7.51a7.4 7.4 0 0 0-4.448 1.475l-.001-.002l-.016.014a8 8 0 0 0-.258.203a3.8 3.8 0 0 1-1.713.652");
}

.fky1q6bty {
  stop-color: var(--svg-color--d7c5e2, #D7C5E2);
}

.ft5dv1b6b {
  fill: none;
}

.gr129pp3o {
  stop-color: var(--svg-color--d7bee7, #D7BEE7);
}

.har94pb2j {
  stop-color: var(--svg-color--d1c2da, #D1C2DA);
}

.hvr0epg6a {
  stop-color: var(--svg-color--b7a2c3, #B7A2C3);
  stop-opacity: 0;
}

.jih0deptr {
  stop-color: var(--svg-color--fcfcfc, #FCFCFC);
}

.k18fg7ooi {
  stop-color: var(--svg-color--fcfafd, #FCFAFD);
}

.kbhx5eb4x {
  d: path("M15.857 5.839a3.8 3.8 0 0 1-1.712-.652a7 7 0 0 0-.258-.203l-.016-.014l-.001.002a7.4 7.4 0 0 0-4.449-1.475c-4.128 0-7.538 3.13-7.538 7.51c0 2.722 1.523 5.159 3.716 6.776l.112.082c.558.409.923.675 1.054 1.62c.114 2.398.624 4.75 2.016 6.744c.454.65.975 1.286 1.558 1.838c.819.622 2.474.828 2.817-1.112l.56-4.61c.124-1.116.752-2.762 2.141-2.765c1.39.003 2.018 1.65 2.142 2.765l.56 4.61c.343 1.94 1.998 1.734 2.816 1.112a12 12 0 0 0 1.559-1.838c1.392-1.994 1.902-4.346 2.016-6.743c.131-.946.495-1.213 1.054-1.621l.112-.082c2.192-1.617 3.716-4.054 3.716-6.776c0-4.38-3.41-7.51-7.539-7.51a7.4 7.4 0 0 0-4.448 1.475l-.001-.002l-.016.014a8 8 0 0 0-.258.203a3.8 3.8 0 0 1-1.713.652");
}

.kcdyz5b5v {
  stop-color: var(--svg-color--fff2ff, #FFF2FF);
  stop-opacity: 0;
}

.lgqrz40-g {
  stop-color: var(--svg-color--9b9b9b, #9B9B9B);
  stop-opacity: 0;
}

.lxq61sbym {
  d: path("M25.457 18.328c-5.82-.531-8.857-3.48-9.702-5.072c-3.762 6.324-6.957 5.837-9.498 5.036c.263.264.442.59.525 1.194c.114 2.397.624 4.75 2.016 6.743c.455.65.976 1.286 1.559 1.838c.818.622 2.473.828 2.816-1.112l.56-4.61c.124-1.116.753-2.762 2.142-2.765c1.389.003 2.017 1.65 2.142 2.765l.56 4.61c.342 1.94 1.997 1.734 2.816 1.112a12 12 0 0 0 1.558-1.838c1.392-1.994 1.902-4.346 2.016-6.743c.08-.576.246-.9.49-1.158");
}

.om03kib-j {
  stop-color: var(--svg-color--b5a5bf, #B5A5BF);
}

.qbgxppb7z {
  stop-color: var(--svg-color--969596, #969596);
}

.qwesrtbki {
  stop-color: var(--svg-color--a097a7, #A097A7);
  stop-opacity: 0;
}

.qzooa0bqp {
  stop-color: var(--svg-color--9b9b9b, #9B9B9B);
}

.r79ivlq6g {
  stop-color: var(--svg-color--cab1db, #CAB1DB);
  stop-opacity: 0;
}

.rd3u85-sz {
  d: path("M13.21 20.958c-.487 2.235-.645 5.08-.664 6.224c-1.991-1.527-2.803-4.232-2.96-5.394c1.262-1.018 2.942-.978 3.624-.83");
}

.rkgbv5bmz {
  d: path("M22.18 18.548a8.12 8.12 0 0 1-6.87-12.446a3 3 0 0 0 .618.13c.31-.026.989-.178 1.596-.605a7 7 0 0 1 .241-.188l.015-.012a6.94 6.94 0 0 1 4.15-1.368c3.848 0 7.029 2.905 7.029 6.97c0 2.525-1.421 4.786-3.466 6.287l-.104.076c-.34.248-.603.44-.779.787a8.1 8.1 0 0 1-2.428.37");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.taavcbpov {
  stop-color: var(--svg-color--a5a5a6, #A5A5A6);
}

.tv4hqwb6d {
  stop-color: var(--svg-color--fcfcfc, #FCFCFC);
  stop-opacity: 0;
}

.u_zgrrbfz {
  stop-color: var(--svg-color--969596, #969596);
  stop-opacity: 0;
}

.uspv73yga {
  d: path("M7.62 5.705c-.21-.04-.278-.3-.1-.416c1.135-.743 3.306-1.506 5.4-.178c1.732 1.097 2.041 1.311 2.384 1.415a1.6 1.6 0 0 0 1.005 0c.343-.104.652-.318 2.383-1.415c2.096-1.328 4.266-.565 5.4.178c.178.116.11.375-.099.416c-1.643.321-3.62.979-5.118 1.922c-1.484.934-2.02 1.218-3.068 1.328c-1.049-.11-1.585-.394-3.069-1.328c-1.497-.943-3.475-1.6-5.118-1.922");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.x0h1i926q {
  stop-color: var(--svg-color--baa5c7, #BAA5C7);
}

.xm6e_wb5j {
  stop-color: var(--svg-color--ececec, #ECECEC);
}

.xxsdgczib {
  stop-color: var(--svg-color--fcfafd, #FCFAFD);
  stop-opacity: 0;
}

.yclo9pbdx {
  stop-color: var(--svg-color--a8a8a8, #A8A8A8);
}

.zb1t1wb8v {
  d: path("M19.407 17.738c3.098 3.532 1.987 7.997 1.445 9.645c-.031.096.082.171.157.102c2.51-2.315 3.514-6.675 3.46-8.696c-1.576.166-3.485.055-5.062-1.052");
}

</style>
