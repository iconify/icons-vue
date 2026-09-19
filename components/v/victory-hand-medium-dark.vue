<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFd3A1c)"><path class="nfh1yvbgf"/><path fill="url(#iFlvqpe)" class="ju83evbuy"/></g><g filter="url(#ifZ45Pb)"><path class="fffvvgbry"/></g><g filter="url(#iVjfOoc)"><path class="vipp6ul9p"/></g><rect transform="rotate(-8.494 5.439 12.006)" class="dk1sai6zl"/><rect fill="url(#idb6zNd)" transform="rotate(-8.494 5.439 12.006)" class="zz_jtnbtp"/><rect fill="url(#i56sHTb)" transform="rotate(-8.494 5.439 12.006)" class="zz_jtnbtp"/><rect fill="url(#iGOKvZd)" transform="rotate(-8.494 5.439 12.006)" class="zz_jtnbtp"/><rect fill="url(#ig0nmIe)" transform="rotate(-8.494 5.439 12.006)" class="zz_jtnbtp"/><path fill="url(#iJxDjad)" class="b26keudmb"/><path fill="url(#iJ6tuXw)" class="b26keudmb"/><path fill="url(#iL0rW2b)" class="b26keudmb"/><path fill="url(#iMs3igz)" class="b26keudmb"/><path fill="url(#izXaGub)" class="b26keudmb"/><path fill="url(#itssGJe)" class="hy91-kefs"/><path fill="url(#iXb0xga)" class="hy91-kefs"/><path fill="url(#izOszYM)" class="hy91-kefs"/><path fill="url(#ir70q4o)" class="ju83evbuy"/><g filter="url(#iE7QAXb)"><rect transform="rotate(-8.139 9.208 12.536)" class="bppp_ob3l"/></g><rect transform="rotate(-8.494 9.298 10.437)" class="llh8z0dxd"/><rect fill="url(#ik65Trc)" transform="rotate(-8.494 9.298 10.437)" class="igda9pb4k"/><rect fill="url(#iUqQZsb)" transform="rotate(-8.494 9.298 10.437)" class="igda9pb4k"/><g filter="url(#ijCFYqd)" class="mc2zb0bvp"><rect fill="url(#ixSfTyL)" transform="rotate(-8.33 8.44 13.432)" class="ufggbn64j"/></g><g filter="url(#iYIZrWb)" class="mc2zb0bvp"><rect fill="url(#iPr0sje)" transform="rotate(-8.33 11.878 11.114)" class="m0b086_8q"/></g><g filter="url(#ioxy1Je)"><path stroke="url(#i5Tslwe)" class="cy6z8lecx"/></g><g filter="url(#ibfmNNI)"><path stroke="url(#iMeflYc)" class="p70qsqbnm"/></g><path class="ugvx_i1tt"/><path fill="url(#iC2jeqd)" class="aef_fb7la"/><path fill="url(#iboY3Wd)" class="aef_fb7la"/><path fill="url(#iy1KGGd)" class="aef_fb7la"/><g filter="url(#iWaUzXb)"><path stroke="url(#i6xyDEc)" class="iao9bnbvp"/></g><path fill="url(#iYXXKxb)" class="ju83evbuy"/><defs><linearGradient id="idb6zNd" x1="5.7" x2="7.558" y1="16.431" y2="16.388" gradientUnits="userSpaceOnUse"><stop class="empkz_b4d"/><stop offset="1" class="lvpaa1p3y"/></linearGradient><linearGradient id="iGOKvZd" x1="5.551" x2="6.244" y1="16.419" y2="16.39" gradientUnits="userSpaceOnUse"><stop class="nvpfuqb-a"/><stop offset="1" class="arg0pn5gw"/></linearGradient><linearGradient id="iJxDjad" x1="13.488" x2="16.448" y1="8.675" y2="7.934" gradientUnits="userSpaceOnUse"><stop class="suir5xulk"/><stop offset="1" class="jy1bdwegu"/></linearGradient><linearGradient id="iJ6tuXw" x1="13.371" x2="14.072" y1="8.655" y2="8.538" gradientUnits="userSpaceOnUse"><stop class="ymmzm-xje"/><stop offset="1" class="qsya1p45u"/></linearGradient><linearGradient id="iL0rW2b" x1="19.282" x2="18.137" y1="9.752" y2="10.087" gradientUnits="userSpaceOnUse"><stop class="xy7vxwn4u"/><stop offset=".99" class="v4dblpb7o"/></linearGradient><linearGradient id="iMs3igz" x1="17.097" x2="16.582" y1="15.217" y2="11.28" gradientUnits="userSpaceOnUse"><stop class="m_wc24ffo"/><stop offset="1" class="y7n-zs35f"/></linearGradient><linearGradient id="itssGJe" x1="19.099" x2="21.995" y1="7.801" y2="7.905" gradientUnits="userSpaceOnUse"><stop class="mym-28cxt"/><stop offset="1" class="v5eqls5gk"/></linearGradient><linearGradient id="iXb0xga" x1="21.285" x2="21.347" y1="15.155" y2="13.241" gradientUnits="userSpaceOnUse"><stop class="xppfpacii"/><stop offset="1" class="upsrocb_c"/></linearGradient><linearGradient id="ik65Trc" x1="9.604" x2="11.71" y1="15.284" y2="15.126" gradientUnits="userSpaceOnUse"><stop class="hhkc1jtqj"/><stop offset="1" class="enc5wf1is"/></linearGradient><linearGradient id="ixSfTyL" x1="9.153" x2="9.177" y1="16.413" y2="12.579" gradientUnits="userSpaceOnUse"><stop class="x0lnkulib"/><stop offset="1" class="cgkhpk0ni"/></linearGradient><linearGradient id="iPr0sje" x1="13.554" x2="10.965" y1="14.166" y2="9.215" gradientUnits="userSpaceOnUse"><stop class="xq-an8bsm"/><stop offset="1" class="fvgz27qdw"/></linearGradient><linearGradient id="i5Tslwe" x1="17.664" x2="14.416" y1="12.884" y2="12.184" gradientUnits="userSpaceOnUse"><stop class="g-4jqxg-j"/><stop offset="1" class="g-4jqxg-j"/></linearGradient><linearGradient id="iMeflYc" x1="22.988" x2="22.442" y1="14.407" y2="14.389" gradientUnits="userSpaceOnUse"><stop class="mkjy0qbit"/><stop offset="1" class="g-4jqxg-j"/><stop offset="1" class="ugtdcobau"/></linearGradient><linearGradient id="i6xyDEc" x1="19.642" x2="25.108" y1="17.16" y2="20.134" gradientUnits="userSpaceOnUse"><stop class="ripzkxbcm"/><stop offset="1" class="nc9smn6vd"/></linearGradient><radialGradient id="iFlvqpe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.82482 3.27838 -2.93875 -3.42858 20.933 20.252)" gradientUnits="userSpaceOnUse"><stop class="leogcl8sa"/><stop offset="1" class="o36_dmbvp"/></radialGradient><radialGradient id="i56sHTb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.635 13.777 5.647)scale(3.91433 5.29446)" gradientUnits="userSpaceOnUse"><stop class="h6qmu6bgf"/><stop offset="1" class="r9kuk9bai"/></radialGradient><radialGradient id="ig0nmIe" cx="0" cy="0" r="1" gradientTransform="rotate(112.53 1.012 9.115)scale(3.35002 3.96464)" gradientUnits="userSpaceOnUse"><stop class="giqal2bfp"/><stop offset="1" class="pjlr7nbha"/></radialGradient><radialGradient id="izXaGub" cx="0" cy="0" r="1" gradientTransform="matrix(3.58284 -11.32088 8.83347 2.79563 12.595 13.526)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="zxfr9bbzm"/><stop offset="1" class="upohxl69y"/></radialGradient><radialGradient id="izOszYM" cx="0" cy="0" r="1" gradientTransform="matrix(3.76872 -9.50125 6.77294 2.68652 19.31 12.254)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="my9t1qbit"/><stop offset="1" class="v_u49o62p"/></radialGradient><radialGradient id="ir70q4o" cx="0" cy="0" r="1" gradientTransform="rotate(-167.551 13.283 6.91)scale(11.1157 8.78497)" gradientUnits="userSpaceOnUse"><stop class="e-wllnbzp"/><stop offset="1" class="dydcj5d2k"/></radialGradient><radialGradient id="iUqQZsb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.68 15.57 3.517)scale(4.57555 8.11932)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="h6qmu6bgf"/><stop offset="1" class="r9kuk9bai"/></radialGradient><radialGradient id="iC2jeqd" cx="0" cy="0" r="1" gradientTransform="matrix(2.75551 -9.57995 12.81598 3.6863 19.16 24.58)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="uy5sp_stg"/><stop offset="1" class="wdxsa7beh"/></radialGradient><radialGradient id="iboY3Wd" cx="0" cy="0" r="1" gradientTransform="matrix(3.0638 1.7944 -2.84171 4.85204 15.595 15)" gradientUnits="userSpaceOnUse"><stop class="lig8pib2j"/><stop offset="1" class="afoahbbil"/></radialGradient><radialGradient id="iy1KGGd" cx="0" cy="0" r="1" gradientTransform="rotate(99.33 1.343 18.929)scale(2.98159 6.08814)" gradientUnits="userSpaceOnUse"><stop class="ny0opbtbw"/><stop offset="1" class="my7o8dueq"/></radialGradient><radialGradient id="iYXXKxb" cx="0" cy="0" r="1" gradientTransform="rotate(11.85 -90.953 70.785)scale(14.3049 25.7029)" gradientUnits="userSpaceOnUse"><stop offset=".865" class="dydcj5d2k"/><stop offset="1" class="e-wllnbzp"/></radialGradient><filter id="iFd3A1c" width="20.456" height="28.462" x="6.022" y="1.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.75"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.254902 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2083"/></filter><filter id="ifZ45Pb" width="10.247" height="11.456" x="5.972" y="10.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2083" stdDeviation="1"/></filter><filter id="iVjfOoc" width="13.44" height="9.076" x="13.587" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2083" stdDeviation="1"/></filter><filter id="iE7QAXb" width="3.501" height="7.258" x="8.265" y="11.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2083" stdDeviation=".5"/></filter><filter id="ijCFYqd" width="2.901" height="5.126" x="7.757" y="12.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2083" stdDeviation=".375"/></filter><filter id="iYIZrWb" width="4.906" height="7.95" x="10.811" y="9.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2083" stdDeviation=".6"/></filter><filter id="ioxy1Je" width="6.515" height="12.042" x="13.673" y="2.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2083" stdDeviation=".75"/></filter><filter id="ibfmNNI" width="4.826" height="12.521" x="20.457" y="2.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2083" stdDeviation=".75"/></filter><filter id="iWaUzXb" width="9.691" height="8.199" x="17.037" y="14.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2083" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:victory-hand-medium-dark" /></template>
<style>
.aef_fb7la {
  d: path("M25.924 19.848c.096.982.082 2.031-.184 2.938c-.394 1.705-1.43 3.191-2.617 4.316l-1.497-2.332c.147-2.29-.16-3.456-.54-3.892c-.427-.49-.682-.49-1.752-.49a5.4 5.4 0 0 1-1.095-.106a3 3 0 0 1-.226-.053a2 2 0 0 1-.413-.15l.001-.005A2.665 2.665 0 0 1 18.732 15h1.916c1.14 0 4.553.854 5.276 4.848");
}

.afoahbbil {
  stop-color: var(--svg-color--634032, #634032);
  stop-opacity: 0;
}

.arg0pn5gw {
  stop-color: var(--svg-color--805a56, #805A56);
  stop-opacity: 0;
}

.b26keudmb {
  d: path("M12.66 5.458c-.325-1.419.591-2.858 2.01-3.185s2.85.542 3.177 1.96l1.72 7.734c.325 1.419-1.188 1.438-2.313 1.75s-2.643.366-2.97-1.052z");
}

.bppp_ob3l {
  width: 0.874px;
  height: 5.303px;
  x: 9.208px;
  y: 12.536px;
  fill: var(--svg-color--593327, #593327);
  rx: 0.437px;
}

.cgkhpk0ni {
  stop-color: var(--svg-color--926f6d, #926F6D);
  stop-opacity: 0;
}

.cy6z8lecx {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.076 4.487l1.71 7.237");
}

.dk1sai6zl {
  width: 5.182px;
  height: 7.437px;
  x: 5.439px;
  y: 12.006px;
  fill: var(--svg-color--7f5b4f, #7F5B4F);
  rx: 2.591px;
}

.dydcj5d2k {
  stop-color: var(--svg-color--a47f71, #A47F71);
  stop-opacity: 0;
}

.e-wllnbzp {
  stop-color: var(--svg-color--a47f71, #A47F71);
}

.empkz_b4d {
  stop-color: var(--svg-color--744e47, #744E47);
}

.enc5wf1is {
  stop-color: var(--svg-color--60382f, #60382F);
  stop-opacity: 0;
}

.fffvvgbry {
  fill: var(--svg-color--432027, #432027);
  d: path("m7.972 13.32l5.25-.784l.997 6.672l-5.25.784z");
}

.ft5dv1b6b {
  fill: none;
}

.fvgz27qdw {
  stop-color: var(--svg-color--b0867b, #B0867B);
  stop-opacity: 0;
}

.g-4jqxg-j {
  stop-color: var(--svg-color--98776b, #98776B);
}

.giqal2bfp {
  stop-color: var(--svg-color--6b524a, #6B524A);
}

.h6qmu6bgf {
  stop-color: var(--svg-color--6e3b54, #6E3B54);
}

.hhkc1jtqj {
  stop-color: var(--svg-color--60382f, #60382F);
}

.hy91-kefs {
  d: path("M19.407 5.814a2.636 2.636 0 0 1 2.674-2.596c1.456.022 2.667 1.22 2.645 2.675l-.086 5.766c-.021 1.455-1.103 1.798-2.559 1.777c-1.455-.022-2.696-.387-2.674-1.843z");
}

.iao9bnbvp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.287 17.16h1.807c1.194 0 2.43.401 2.923 1.489a5.3 5.3 0 0 1 .46 2.21");
}

.igda9pb4k {
  width: 5.309px;
  height: 8.693px;
  x: 9.298px;
  y: 10.437px;
  rx: 2.591px;
}

.ju83evbuy {
  d: path("M12.66 5.458c-.325-1.419.591-2.858 2.01-3.185s2.85.542 3.177 1.96l1.527 6.993l.081-5.412a2.636 2.636 0 1 1 5.271.08l-.112 7.47a6 6 0 0 0 .199 1.623l.498 1.888c.347 1.087 1.03 3.863.428 5.91c-.61 2.65-2.771 4.77-4.646 5.83s-3.944 1.58-6.971 1.152c-3.903-.836-6.115-3.577-6.9-7.124c-.668-2.74-1.04-5.634-1.2-6.76l8.586-2.116z");
}

.jy1bdwegu {
  stop-color: var(--svg-color--663f33, #663F33);
  stop-opacity: 0;
}

.leogcl8sa {
  stop-color: var(--svg-color--8b6365, #8B6365);
}

.lig8pib2j {
  stop-color: var(--svg-color--634032, #634032);
}

.llh8z0dxd {
  width: 5.309px;
  height: 8.693px;
  x: 9.298px;
  y: 10.437px;
  fill: var(--svg-color--7f5b4f, #7F5B4F);
  rx: 2.591px;
}

.lvpaa1p3y {
  stop-color: var(--svg-color--744e47, #744E47);
  stop-opacity: 0;
}

.m_wc24ffo {
  stop-color: var(--svg-color--864e4a, #864E4A);
}

.m0b086_8q {
  width: 1.984px;
  height: 5.588px;
  x: 11.878px;
  y: 11.114px;
  rx: 0.992px;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mkjy0qbit {
  stop-color: var(--svg-color--a37e73, #A37E73);
}

.my7o8dueq {
  stop-color: var(--svg-color--6e384b, #6E384B);
  stop-opacity: 0;
}

.my9t1qbit {
  stop-color: var(--svg-color--8e7062, #8E7062);
  stop-opacity: 0;
}

.mym-28cxt {
  stop-color: var(--svg-color--5a3730, #5A3730);
}

.nc9smn6vd {
  stop-color: var(--svg-color--a17d72, #A17D72);
  stop-opacity: 0;
}

.nfh1yvbgf {
  fill: var(--svg-color--7e5353, #7E5353);
  d: path("M12.66 5.458c-.325-1.419.591-2.858 2.01-3.185s2.85.542 3.177 1.96l1.527 6.993l.081-5.412a2.636 2.636 0 1 1 5.271.08l-.112 7.47a6 6 0 0 0 .199 1.623l.498 1.888c.347 1.087 1.03 3.863.428 5.91c-.61 2.65-2.771 4.77-4.646 5.83s-3.944 1.58-6.971 1.152c-3.903-.836-6.115-3.577-6.9-7.124c-.668-2.74-1.04-5.634-1.2-6.76l8.586-2.116z");
}

.nvpfuqb-a {
  stop-color: var(--svg-color--805a56, #805A56);
}

.ny0opbtbw {
  stop-color: var(--svg-color--6e384b, #6E384B);
}

.o36_dmbvp {
  stop-color: var(--svg-color--8b6365, #8B6365);
  stop-opacity: 0;
}

.p70qsqbnm {
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m23.008 5.159l-.275 7.97");
}

.pjlr7nbha {
  stop-color: var(--svg-color--6b524a, #6B524A);
  stop-opacity: 0;
}

.qsya1p45u {
  stop-color: var(--svg-color--735246, #735246);
  stop-opacity: 0;
}

.r9kuk9bai {
  stop-color: var(--svg-color--6e3b54, #6E3B54);
  stop-opacity: 0;
}

.ripzkxbcm {
  stop-color: var(--svg-color--a17d72, #A17D72);
}

.suir5xulk {
  stop-color: var(--svg-color--663f33, #663F33);
}

.ufggbn64j {
  width: 1.019px;
  height: 3.653px;
  x: 8.439px;
  y: 13.432px;
  rx: 0.51px;
}

.ugtdcobau {
  stop-color: var(--svg-color--9e796e, #9E796E);
}

.ugvx_i1tt {
  fill: var(--svg-color--7e5353, #7E5353);
  d: path("M25.924 19.848c.096.982.082 2.031-.184 2.938c-.394 1.705-1.43 3.191-2.617 4.316l-1.497-2.332c.147-2.29-.16-3.456-.54-3.892c-.427-.49-.682-.49-1.752-.49a5.4 5.4 0 0 1-1.095-.106a3 3 0 0 1-.226-.053a2 2 0 0 1-.413-.15l.001-.005A2.665 2.665 0 0 1 18.732 15h1.916c1.14 0 4.553.854 5.276 4.848");
}

.upohxl69y {
  stop-color: var(--svg-color--937263, #937263);
}

.upsrocb_c {
  stop-color: var(--svg-color--966d68, #966D68);
  stop-opacity: 0;
}

.uy5sp_stg {
  stop-color: var(--svg-color--88614f, #88614F);
  stop-opacity: 0;
}

.v_u49o62p {
  stop-color: var(--svg-color--8e7062, #8E7062);
}

.v4dblpb7o {
  stop-color: var(--svg-color--6a544e, #6A544E);
  stop-opacity: 0;
}

.v5eqls5gk {
  stop-color: var(--svg-color--5a3730, #5A3730);
  stop-opacity: 0;
}

.vipp6ul9p {
  fill: var(--svg-color--432027, #432027);
  d: path("M25.027 21.066a11 11 0 0 0-.039-.498A5.38 5.38 0 0 0 19.951 16h-1.83c-1.4.005-2.534 1.127-2.534 2.51a2.51 2.51 0 0 0 1.454 2.27v.005c.08.042.214.094.393.142q.106.03.217.05c.277.057.63.1 1.045.1h.088v-.01z");
}

.wdxsa7beh {
  stop-color: var(--svg-color--88614f, #88614F);
}

.x0lnkulib {
  stop-color: var(--svg-color--926f6d, #926F6D);
}

.xppfpacii {
  stop-color: var(--svg-color--987069, #987069);
}

.xq-an8bsm {
  stop-color: var(--svg-color--b0867b, #B0867B);
}

.xy7vxwn4u {
  stop-color: var(--svg-color--6a544e, #6A544E);
}

.y7n-zs35f {
  stop-color: var(--svg-color--864e4a, #864E4A);
  stop-opacity: 0;
}

.ymmzm-xje {
  stop-color: var(--svg-color--735246, #735246);
}

.zxfr9bbzm {
  stop-color: var(--svg-color--937263, #937263);
  stop-opacity: 0;
}

.zz_jtnbtp {
  width: 5.182px;
  height: 7.437px;
  x: 5.439px;
  y: 12.006px;
  rx: 2.591px;
}

</style>
