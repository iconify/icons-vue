<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iLjGxMc)" class="cy_s7hoty"/><path fill="url(#itZ3ome)" class="cy_s7hoty"/><path fill="url(#i7UBHoe)" class="lf7z0hb_m"/><path fill="url(#iixF7bb)" class="u3a-a1bho"/><path fill="url(#ihFoNvv)" class="yej7s1m3l"/><path fill="url(#isl6Vlc)" class="n6wvbtbwk"/><path fill="url(#iBtEZEe)" class="n6wvbtbwk"/><path fill="url(#iYatn9d)" class="n6wvbtbwk"/><path fill="url(#ickXjcc)" class="n6wvbtbwk"/><path fill="url(#iYmp4Vb)" class="j0aasaboc"/><path fill="url(#iKrKD5q)" class="j0aasaboc"/><path fill="url(#ihoTFhd)" class="j0aasaboc"/><path fill="url(#i6aJdJd)" class="j0aasaboc"/><path fill="url(#i86an2d)" class="j0aasaboc"/><path fill="url(#irS4xpd)" class="mh2qb2b-w"/><path fill="url(#i725ieb)" class="mh2qb2b-w"/><path fill="url(#idx4T6c)" class="mh2qb2b-w"/><path fill="url(#io5Zryn)" class="mh2qb2b-w"/><path fill="url(#i0QfcBb)" class="mh2qb2b-w"/><path fill="url(#iJ1ziJd)" class="bemp_dbpj"/><path fill="url(#iHQmmTd)" class="rp-nwl8xc"/><path fill="url(#iYQdOiu)" class="dm9sis9zl"/><path fill="url(#iaRDMeb)" class="kt9l2wb7n"/><path fill="url(#ieRShte)" class="bz80hl4kw"/><path fill="url(#iRBf3Ac)" class="bz80hl4kw"/><path fill="url(#iHd14hd)" class="s-cuoijli"/><path fill="url(#iDzjJRc)" class="hk868acvz"/><path fill="url(#i3W0y4c)" class="hk868acvz"/><path fill="url(#it80jmb)" class="kqsbeva3d"/><path fill="url(#iUUGUMb)" class="dwiqnmbzy"/><path fill="url(#ihgq15c)" class="f_n9sohaa"/><path fill="url(#iBI3uhb)" class="ldykl25zg"/><path fill="url(#iROaqSb)" class="hupr_hb6r"/><g filter="url(#ifAHOLe)"><path class="fi9zpmewj"/></g><path fill="url(#iUoU1Ud)" class="riqadb5er"/><path fill="url(#i4rIxec)" class="riqadb5er"/><path fill="url(#iDAmDqb)" class="riqadb5er"/><g filter="url(#iVDGaIe)"><path stroke="url(#iHEfXyb)" class="xc9jrbbfw"/></g><g filter="url(#iABstjb)"><path stroke="url(#iefwi8c)" class="lyzdl1bhd"/></g><path fill="url(#i2JR0FB)" class="iqs088b5m"/><g filter="url(#ivWJNuc)"><path stroke="url(#iZp9MMc)" class="rar8acbiz"/></g><g filter="url(#icOfh7d)"><path stroke="url(#iJLI5Ab)" class="mvaevw92n"/></g><g filter="url(#i4pw3Dd)"><path stroke="url(#i0qYGqc)" class="e0rcxrbfr"/></g><g filter="url(#ivL7bsc)"><path stroke="url(#i3ipTpe)" class="z63r93rne"/></g><path fill="url(#iBQv9fe)" class="dnq5q3ben"/><path fill="url(#if3qG6d)" class="dnq5q3ben"/><path fill="url(#ieTxJ1c)" class="lxcs7pb6c"/><defs><linearGradient id="iLjGxMc" x1="28.229" x2="28.229" y1="26.375" y2="14.25" gradientUnits="userSpaceOnUse"><stop class="znreifbiu"/><stop offset="1" class="idprm_bem"/></linearGradient><linearGradient id="itZ3ome" x1="24.979" x2="26.694" y1="19.438" y2="19.125" gradientUnits="userSpaceOnUse"><stop offset=".203" class="vl0nxwbiv"/><stop offset=".822" class="r_ls4fxld"/></linearGradient><linearGradient id="i7UBHoe" x1="29.167" x2="29.167" y1="24.863" y2="27.189" gradientUnits="userSpaceOnUse"><stop class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iixF7bb" x1="28.385" x2="25.682" y1="21.314" y2="21.314" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="ihFoNvv" x1="28.542" x2="25.104" y1="17.314" y2="17.314" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="isl6Vlc" x1="19.854" x2="18.763" y1="23.5" y2="31.125" gradientUnits="userSpaceOnUse"><stop class="oqp5hhb0f"/><stop offset=".754" class="wl17-900p"/></linearGradient><linearGradient id="iBtEZEe" x1="18.762" x2="18.762" y1="30.137" y2="29.344" gradientUnits="userSpaceOnUse"><stop class="ji7ngcckm"/><stop offset="1" class="lzh9fgk4o"/></linearGradient><linearGradient id="iYatn9d" x1="20.292" x2="18.762" y1="24.125" y2="29.344" gradientUnits="userSpaceOnUse"><stop class="f0y3oacmo"/><stop offset="1" class="lzh9fgk4o"/><stop offset="1" class="q9j7412fn"/></linearGradient><linearGradient id="ickXjcc" x1="20.323" x2="18.948" y1="27.969" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="f0y3oacmo"/><stop offset=".72" class="lzh9fgk4o"/><stop offset="1" class="q9j7412fn"/></linearGradient><linearGradient id="iYmp4Vb" x1="13.056" x2="13.057" y1="23.063" y2="31.125" gradientUnits="userSpaceOnUse"><stop class="oqp5hhb0f"/><stop offset=".754" class="wl17-900p"/></linearGradient><linearGradient id="iKrKD5q" x1="13.056" x2="13.056" y1="30.137" y2="29.484" gradientUnits="userSpaceOnUse"><stop class="ji7ngcckm"/><stop offset="1" class="lzh9fgk4o"/></linearGradient><linearGradient id="ihoTFhd" x1="11.698" x2="12.639" y1="24.219" y2="28.029" gradientUnits="userSpaceOnUse"><stop class="f0y3oacmo"/><stop offset="1" class="lzh9fgk4o"/><stop offset="1" class="q9j7412fn"/></linearGradient><linearGradient id="i6aJdJd" x1="15.292" x2="14.085" y1="27" y2="27.297" gradientUnits="userSpaceOnUse"><stop class="f0y3oacmo"/><stop offset="1" class="lzh9fgk4o"/><stop offset="1" class="q9j7412fn"/></linearGradient><linearGradient id="i86an2d" x1="11.276" x2="11.911" y1="24.078" y2="24.65" gradientUnits="userSpaceOnUse"><stop class="h14qmm_bu"/><stop offset="1" class="lzh9fgk4o"/><stop offset="1" class="q9j7412fn"/></linearGradient><linearGradient id="irS4xpd" x1="12.354" x2="12.354" y1="9.625" y2="30.063" gradientUnits="userSpaceOnUse"><stop class="w9pzsdbov"/><stop offset=".667" class="vtuk12buc"/><stop offset="1" class="nva2h1_xv"/></linearGradient><linearGradient id="idx4T6c" x1="14.109" x2="14.109" y1="30.281" y2="28.875" gradientUnits="userSpaceOnUse"><stop class="ji7ngcckm"/><stop offset="1" class="lzh9fgk4o"/></linearGradient><linearGradient id="iJ1ziJd" x1="21.932" x2="24.104" y1="26.557" y2="26.557" gradientUnits="userSpaceOnUse"><stop class="jsr9pccgk"/><stop offset=".469" class="jwywbgb3b"/><stop offset="1" class="owp0kmbkm"/></linearGradient><linearGradient id="iHQmmTd" x1="14.104" x2="14.104" y1="14.696" y2="20.563" gradientUnits="userSpaceOnUse"><stop offset=".006" class="rtk_xcc_q"/><stop offset="1" class="cy60n0hav"/></linearGradient><linearGradient id="iYQdOiu" x1="18.104" x2="18.104" y1="15.569" y2="19.844" gradientUnits="userSpaceOnUse"><stop offset=".006" class="rtk_xcc_q"/><stop offset="1" class="cy60n0hav"/></linearGradient><linearGradient id="iaRDMeb" x1="22.104" x2="22.104" y1="15.569" y2="19.938" gradientUnits="userSpaceOnUse"><stop offset=".006" class="rtk_xcc_q"/><stop offset="1" class="cy60n0hav"/></linearGradient><linearGradient id="ieRShte" x1="6.917" x2="2.667" y1="14.563" y2="19" gradientUnits="userSpaceOnUse"><stop class="g23nou-go"/><stop offset=".491" class="y61-t1cwv"/><stop offset="1" class="tb5a1zb_m"/></linearGradient><linearGradient id="iHd14hd" x1="5.549" x2="7.167" y1="21.433" y2="21.433" gradientUnits="userSpaceOnUse"><stop class="i9aykuoam"/><stop offset=".857" class="d415wgb_s"/></linearGradient><linearGradient id="iDzjJRc" x1="5.151" x2="4.838" y1="16.891" y2="18.334" gradientUnits="userSpaceOnUse"><stop class="qfx22hlij"/><stop offset=".643" class="hskyajbzx"/><stop offset="1" class="swqm-7b1p"/></linearGradient><linearGradient id="i3W0y4c" x1="1.963" x2="3.042" y1="16.219" y2="16.219" gradientUnits="userSpaceOnUse"><stop class="i9aykuoam"/><stop offset=".857" class="d415wgb_s"/></linearGradient><linearGradient id="iUUGUMb" x1="15.384" x2="15.384" y1="22.063" y2="24.469" gradientUnits="userSpaceOnUse"><stop class="x22zi0bgn"/><stop offset="1" class="swqm-7b1p"/></linearGradient><linearGradient id="ihgq15c" x1="20.168" x2="24.104" y1="24.562" y2="24.562" gradientUnits="userSpaceOnUse"><stop class="jsr9pccgk"/><stop offset=".651" class="jwywbgb3b"/><stop offset="1" class="owp0kmbkm"/></linearGradient><linearGradient id="iBI3uhb" x1="8.322" x2="10.729" y1="26.552" y2="26.552" gradientUnits="userSpaceOnUse"><stop class="jsr9pccgk"/><stop offset=".469" class="jwywbgb3b"/><stop offset="1" class="owp0kmbkm"/></linearGradient><linearGradient id="iROaqSb" x1="8.322" x2="10.526" y1="24.562" y2="24.562" gradientUnits="userSpaceOnUse"><stop class="jsr9pccgk"/><stop offset=".469" class="jwywbgb3b"/><stop offset="1" class="owp0kmbkm"/></linearGradient><linearGradient id="iUoU1Ud" x1="7.046" x2="6.496" y1="13.063" y2="13.063" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="i4rIxec" x1="7.26" x2="7.26" y1="14.412" y2="13.352" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iDAmDqb" x1="5.713" x2="6.495" y1="13.609" y2="13.609" gradientUnits="userSpaceOnUse"><stop class="dyysy0bzo"/><stop offset=".84" class="zmzak_sfz"/></linearGradient><linearGradient id="iefwi8c" x1="13.893" x2="17.854" y1="5.938" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="q4_-xdbrx"/><stop offset="1" class="wm77fyu_r"/></linearGradient><linearGradient id="iZp9MMc" x1="14.823" x2="13.417" y1="28.609" y2="23.563" gradientUnits="userSpaceOnUse"><stop class="acnyk8b0e"/><stop offset="1" class="fw37eab2p"/></linearGradient><linearGradient id="iJLI5Ab" x1="18.918" x2="17.512" y1="28.609" y2="23.563" gradientUnits="userSpaceOnUse"><stop class="acnyk8b0e"/><stop offset="1" class="fw37eab2p"/></linearGradient><linearGradient id="i0qYGqc" x1="10.453" x2="10.453" y1="28.656" y2="23.563" gradientUnits="userSpaceOnUse"><stop class="pvd28u9cy"/><stop offset="1" class="fw37eab2p"/></linearGradient><linearGradient id="i3ipTpe" x1="25.104" x2="34.974" y1="19.125" y2="28.623" gradientUnits="userSpaceOnUse"><stop class="m5bpwubxd"/><stop offset="1" class="ym-xbob2b"/></linearGradient><linearGradient id="iBQv9fe" x1="10.45" x2="9.385" y1="14.015" y2="15.08" gradientUnits="userSpaceOnUse"><stop offset=".006" class="aoo6bub-i"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="if3qG6d" x1="10.921" x2="9.614" y1="13.723" y2="14.972" gradientUnits="userSpaceOnUse"><stop offset=".006" class="pfuckqb8h"/><stop offset="1" class="pxobhjbfh"/></linearGradient><linearGradient id="ieTxJ1c" x1="10.792" x2="8.754" y1="11.438" y2="13.813" gradientUnits="userSpaceOnUse"><stop offset=".006" class="pfuckqb8h"/><stop offset="1" class="pxobhjbfh"/></linearGradient><radialGradient id="i725ieb" cx="0" cy="0" r="1" gradientTransform="rotate(101.889 -.07 19.481)scale(3.64059 7.69806)" gradientUnits="userSpaceOnUse"><stop class="znreifbiu"/><stop offset="1" class="q6bvkbcto"/></radialGradient><radialGradient id="io5Zryn" cx="0" cy="0" r="1" gradientTransform="matrix(1.67188 .6875 -1.0214 2.4839 7.37 27.172)" gradientUnits="userSpaceOnUse"><stop class="pvd28u9cy"/><stop offset=".831" class="oz18dxcww"/></radialGradient><radialGradient id="i0QfcBb" cx="0" cy="0" r="1" gradientTransform="rotate(127.178 9.309 14.032)scale(4.98107 5.77109)" gradientUnits="userSpaceOnUse"><stop class="te9-ibbqz"/><stop offset=".533" class="umstw2bds"/></radialGradient><radialGradient id="iRBf3Ac" cx="0" cy="0" r="1" gradientTransform="rotate(142.336 2.013 9.25)scale(2.76173 4.23882)" gradientUnits="userSpaceOnUse"><stop class="i9aykuoam"/><stop offset=".857" class="d415wgb_s"/></radialGradient><radialGradient id="it80jmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.32813 -.34375 .6628 -.63269 3.182 13.484)" gradientUnits="userSpaceOnUse"><stop class="mqpbk469p"/><stop offset="1" class="bp2mrabfz"/></radialGradient><radialGradient id="iHEfXyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.29224 -1.8623 0 24.966 17.166)" gradientUnits="userSpaceOnUse"><stop class="te9-ibbqz"/><stop offset="1" class="tii0cl-5h"/></radialGradient><radialGradient id="i2JR0FB" cx="0" cy="0" r="1" gradientTransform="matrix(.76562 -.84375 .63966 .58043 9.338 9.906)" gradientUnits="userSpaceOnUse"><stop class="uo-vgrm9c"/><stop offset=".871" class="vb-kn8b8a"/></radialGradient><filter id="ifAHOLe" width="2.059" height="2.919" x="5.332" y="11.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2293" stdDeviation=".3"/></filter><filter id="iVDGaIe" width="4.988" height="8.731" x="21.354" y="14.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2293" stdDeviation=".5"/></filter><filter id="iABstjb" width="7.117" height="10.531" x="7.768" y="7.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2293" stdDeviation=".75"/></filter><filter id="ivWJNuc" width="2.5" height="5.625" x="12.791" y="24.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2293" stdDeviation=".25"/></filter><filter id="icOfh7d" width="3.688" height="6.688" x="17.01" y="23.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2293" stdDeviation=".5"/></filter><filter id="i4pw3Dd" width="1.25" height="6.844" x="9.828" y="22.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2293" stdDeviation=".25"/></filter><filter id="ivL7bsc" width="4.169" height="11.325" x="25.879" y="15.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2293" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tiger" /></template>
<style>
.acnyk8b0e {
  stop-color: var(--svg-color--ff8c82, #FF8C82);
}

.aoo6bub-i {
  stop-color: var(--svg-color--513468, #513468);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bemp_dbpj {
  d: path("M21.903 27.062h1.701c.28 0 .5-.22.5-.5v-.01c0-.28-.22-.5-.5-.5h-1.95l.104.104a.75.75 0 0 1 .194.725z");
}

.bp2mrabfz {
  stop-color: var(--svg-color--3b2439, #3B2439);
}

.bz80hl4kw {
  d: path("m8.464 17.503l.63-.94c.43-.64-.03-1.5-.81-1.5h-2.3c-.54 0-1.03-.31-1.27-.79l-.61-1.21h-1.28c-.4 0-.72.32-.72.72v1.54c0 1.51 1.23 2.74 2.74 2.74h.76a.5.5 0 0 1 .5.5v1.92c0 1.4.81 2.62 1.99 3.21v-4.96c0-.44.13-.86.37-1.23");
}

.cy_s7hoty {
  d: path("M29.104 27.063c-1.65 0-3-1.35-3-3v-6c0-.55-.45-1-1-1h-.82c-.55 0-1-.45-1-1s.45-1 1-1h.82c1.65 0 3 1.35 3 3v6c0 .55.45 1 1 1s1 .45 1 1s-.45 1-1 1");
}

.cy60n0hav {
  stop-color: var(--svg-color--4e4757, #4E4757);
}

.d415wgb_s {
  stop-color: var(--svg-color--ffe5bf, #FFE5BF);
  stop-opacity: 0;
}

.dm9sis9zl {
  d: path("M17.104 15.063v3c0 .55.45 1 1 1s1-.45 1-1v-3z");
}

.dnq5q3ben {
  d: path("M9.424 15.033c-.2-.2-.2-.51 0-.71l.45-.45c.2-.2.51-.2.71 0s.2.51 0 .71l-.46.45c-.19.19-.51.19-.7 0");
}

.dwiqnmbzy {
  d: path("M17.674 22.063h-6.58v2h8.58c0-1.1-.9-2-2-2");
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e0rcxrbfr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.453 23.125v5.594");
}

.f_n9sohaa {
  d: path("M23.604 24.063h-3.94l1 1h2.94c.28 0 .5-.22.5-.5s-.22-.5-.5-.5");
}

.f0y3oacmo {
  stop-color: var(--svg-color--bb1715, #BB1715);
}

.fi9zpmewj {
  fill: var(--svg-color--bc5a28, #BC5A28);
  d: path("M6.362 14.068a.433.433 0 0 1-.43-.43v-.859c0-.235.195-.43.43-.43s.43.195.43.43v.86a.43.43 0 0 1-.43.43");
}

.ft5dv1b6b {
  fill: none;
}

.fw37eab2p {
  stop-color: var(--svg-color--ff8c82, #FF8C82);
  stop-opacity: 0;
}

.g23nou-go {
  stop-color: var(--svg-color--ffd7b0, #FFD7B0);
}

.h14qmm_bu {
  stop-color: var(--svg-color--8d1514, #8D1514);
}

.hk868acvz {
  d: path("M5.604 18.063h-.76c-1.51 0-2.74-1.23-2.74-2.74v-1.54c0-.4.32-.72.72-.72h1.28l.61 1.21c.24.48.73.79 1.27.79h2.3a1 1 0 0 1 .412.088c-.952 1.145-1.891 2.912-3.092 2.912");
}

.hskyajbzx {
  stop-color: var(--svg-color--d37f97, #D37F97);
  stop-opacity: 0.4;
}

.hupr_hb6r {
  d: path("M10.104 24.563c0-.28-.22-.5-.5-.5h-1.51v1h1.51c.28 0 .5-.22.5-.5");
}

.i9aykuoam {
  stop-color: var(--svg-color--ffe5bf, #FFE5BF);
}

.idprm_bem {
  stop-color: var(--svg-color--ff8718, #FF8718);
}

.iqs088b5m {
  d: path("M10.104 10.063v-.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5v.5z");
}

.j0aasaboc {
  d: path("m15.494 29.673l-1.89-7.09h-3l1.392 5.217c.043.161-.059.323-.196.418a.83.83 0 0 0-.346.535l-.17.98c-.03.17.1.33.28.33h3.63c.21 0 .36-.19.3-.39");
}

.ji7ngcckm {
  stop-color: var(--svg-color--d03a56, #D03A56);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jsr9pccgk {
  stop-color: var(--svg-color--3e2b4d, #3E2B4D);
}

.jwywbgb3b {
  stop-color: var(--svg-color--48355b, #48355B);
}

.kqsbeva3d {
  d: path("M2.824 13.063c-.4 0-.72.32-.72.72v1.28l1.69-2z");
}

.kt9l2wb7n {
  d: path("M21.104 15.063v3c0 .55.45 1 1 1s1-.45 1-1v-3z");
}

.ldykl25zg {
  d: path("M10.104 26.553c0-.28-.22-.5-.5-.5h-1.51v1h1.51c.28 0 .5-.22.5-.5");
}

.lf7z0hb_m {
  d: path("M29.104 25.063c-.38 0-.7-.21-.88-.52v2.39c.28.08.58.13.88.13c.55 0 1-.45 1-1s-.45-1-1-1");
}

.lxcs7pb6c {
  d: path("M7.754 14.213c-.2-.2-.2-.51 0-.71l1.29-1.29c.2-.2.51-.2.71 0s.2.51 0 .71l-1.3 1.29c-.19.19-.51.19-.7 0");
}

.lyzdl1bhd {
  stroke-linecap: round;
  d: path("M9.768 9.625v2.587a2 2 0 0 0 .586 1.415l2.531 2.53");
}

.lzh9fgk4o {
  stop-color: var(--svg-color--d03a56, #D03A56);
  stop-opacity: 0;
}

.m5bpwubxd {
  stop-color: var(--svg-color--ffc893, #FFC893);
}

.mh2qb2b-w {
  d: path("M25.694 15.823c-.37-.48-.94-.76-1.55-.76h-9.57c-.3 0-.59-.12-.81-.33l-2.29-2.29c-.24-.24-.38-.58-.38-.92v-1.96c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.15a.35.35 0 0 1-.35.35c-.73 0-1.41.32-1.88.87c-.73.87-1.76 2.09-1.76 2.13h-1.28c-.4 0-.72.32-.72.72v1.54c0 1.51 1.23 2.74 2.74 2.74h1.26v2.42c0 1.4.81 2.62 1.99 3.21v3.87c0 .276-.237.489-.48.621a.98.98 0 0 0-.51.858v.6c0 .23.19.42.42.42h3.25c.17 0 .31-.14.31-.31v-5.69h8.58l2.094 2.094a.75.75 0 0 1 .194.725l-.26.969a.29.29 0 0 1-.278.212c-.48 0-.9.33-1.01.79l-.2.8c-.05.21.11.41.33.41h3.22c.22 0 .41-.14.47-.34l1.5-4.5c.26-.77.39-1.57.39-2.38v-5.82a2 2 0 0 0-.42-1.2");
}

.mqpbk469p {
  stop-color: var(--svg-color--67545f, #67545F);
}

.mvaevw92n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.448 25l-1.188 4.188");
}

.n6wvbtbwk {
  d: path("m18.544 22.583l-1.45 5.402a.104.104 0 0 1-.1.078c-.4 0-.75.29-.82.69l-.17.95c-.03.19.11.36.3.36h2.84c.23 0 .42-.15.48-.37l1.9-7.11z");
}

.nva2h1_xv {
  stop-color: var(--svg-color--f25038, #F25038);
}

.oqp5hhb0f {
  stop-color: var(--svg-color--e42b2e, #E42B2E);
}

.owp0kmbkm {
  stop-color: var(--svg-color--5b4e6b, #5B4E6B);
}

.oz18dxcww {
  stop-color: var(--svg-color--ff9288, #FF9288);
  stop-opacity: 0;
}

.pfuckqb8h {
  stop-color: var(--svg-color--735e88, #735E88);
}

.pvd28u9cy {
  stop-color: var(--svg-color--ff9288, #FF9288);
}

.pxobhjbfh {
  stop-color: var(--svg-color--614979, #614979);
}

.q4_-xdbrx {
  stop-color: var(--svg-color--ffe092, #FFE092);
}

.q6bvkbcto {
  stop-color: var(--svg-color--fc2f01, #FC2F01);
  stop-opacity: 0;
}

.q9j7412fn {
  stop-color: var(--svg-color--bb1715, #BB1715);
  stop-opacity: 0;
}

.qfx22hlij {
  stop-color: var(--svg-color--d37f97, #D37F97);
  stop-opacity: 0;
}

.r_ls4fxld {
  stop-color: var(--svg-color--d03614, #D03614);
  stop-opacity: 0;
}

.rar8acbiz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13.417 24.719l1.25 4.375");
}

.riqadb5er {
  d: path("M6.604 14.063a.504.504 0 0 1-.5-.5v-1c0-.274.227-.5.5-.5s.5.226.5.5v1a.5.5 0 0 1-.5.5");
}

.rp-nwl8xc {
  d: path("M14.574 15.063c-.3 0-.59-.12-.81-.33l-.66-.67v4c0 .55.45 1 1 1s1-.45 1-1v-3z");
}

.rtk_xcc_q {
  stop-color: var(--svg-color--57426a, #57426A);
}

.s-cuoijli {
  d: path("M8.198 18.063H5.604a.5.5 0 0 1 .5.5v1.92c0 1.4.81 2.62 1.99 3.21v-4.96q.001-.347.104-.67");
}

.swqm-7b1p {
  stop-color: var(--svg-color--d37f97, #D37F97);
}

.tb5a1zb_m {
  stop-color: var(--svg-color--e6aba2, #E6ABA2);
}

.te9-ibbqz {
  stop-color: var(--svg-color--ffac62, #FFAC62);
}

.tii0cl-5h {
  stop-color: var(--svg-color--ff9d61, #FF9D61);
  stop-opacity: 0;
}

.u3a-a1bho {
  d: path("M28.104 21.063h-2v2h2z");
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.umstw2bds {
  stop-color: var(--svg-color--ffac62, #FFAC62);
  stop-opacity: 0;
}

.uo-vgrm9c {
  stop-color: var(--svg-color--ff8945, #FF8945);
}

.vb-kn8b8a {
  stop-color: var(--svg-color--f32312, #F32312);
}

.vl0nxwbiv {
  stop-color: var(--svg-color--d03614, #D03614);
}

.vtuk12buc {
  stop-color: var(--svg-color--f65936, #F65936);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w9pzsdbov {
  stop-color: var(--svg-color--ff9b50, #FF9B50);
}

.wl17-900p {
  stop-color: var(--svg-color--fc563c, #FC563C);
}

.wm77fyu_r {
  stop-color: var(--svg-color--ffe092, #FFE092);
  stop-opacity: 0;
}

.x22zi0bgn {
  stop-color: var(--svg-color--f5bdae, #F5BDAE);
}

.xc9jrbbfw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M24.592 21.387v-3.812c0-1.072-.75-1.419-1.488-1.419");
}

.y61-t1cwv {
  stop-color: var(--svg-color--f9cca9, #F9CCA9);
}

.yej7s1m3l {
  d: path("M28.104 19.063v-1a3 3 0 0 0-.17-1h-2.83c.55 0 1 .45 1 1v1z");
}

.ym-xbob2b {
  stop-color: var(--svg-color--ffeddb, #FFEDDB);
  stop-opacity: 0;
}

.z63r93rne {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M26.604 16.188c.26.093.781.606.781 1.906v6.25c.032.573.463 1.718 1.938 1.718");
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.znreifbiu {
  stop-color: var(--svg-color--fc2f01, #FC2F01);
}

</style>
