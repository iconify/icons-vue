<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(-45 1.76 12.69)" class="ni1f3ybnb"/><rect transform="rotate(-45 12.424 23.315)" class="teaiskqrf"/><path fill="url(#iVPRBoE)" transform="rotate(-45 9.583 14.373)" class="fujdaxbzw"/><path fill="url(#iLG2cqe)" transform="rotate(-45 9.583 14.373)" class="fujdaxbzw"/><path fill="url(#itKrpqc)" transform="rotate(-45 9.583 14.373)" class="fujdaxbzw"/><path fill="url(#i3jHKUb)" transform="rotate(-45 9.583 14.373)" class="fujdaxbzw"/><g filter="url(#iBFB8sc)"><path fill="url(#iI5UMQc)" class="e45gmd_kw"/><path fill="url(#iki1Woe)" class="e45gmd_kw"/><path fill="url(#ixOEYSZ)" class="e45gmd_kw"/><path fill="url(#iLMhmte)" class="e45gmd_kw"/></g><g filter="url(#i4POUNI)"><path fill="url(#i659Akb)" class="s_fqvqb0k"/><path fill="url(#iGXcfpe)" class="s_fqvqb0k"/></g><g filter="url(#itk91Mb)"><path fill="url(#is7neld)" class="xnrz800pp"/><path fill="url(#iLuXVWc)" class="xnrz800pp"/></g><g filter="url(#irSk9nc)"><path fill="url(#iDQnOXd)" class="h1os5rb_p"/><path fill="url(#i4RHVXd)" class="h1os5rb_p"/></g><g filter="url(#iPqgZVc)"><path fill="url(#iSVORRc)" class="rtsquubvp"/><path fill="url(#iwkKKue)" class="rtsquubvp"/></g><g filter="url(#iQbORlc)"><path fill="url(#iyvtvle)" class="osutr4bux"/><path fill="url(#ic6i6lC)" class="osutr4bux"/></g><path fill="url(#ipax6Fd)" class="du0dk-b3k"/><path fill="url(#iXsQFEe)" class="du0dk-b3k"/><path fill="url(#iSTPIkd)" class="du0dk-b3k"/><path fill="url(#i8qJKJe)" class="bp-6-0bhm"/><path fill="url(#i0PZ0kb)" class="bp-6-0bhm"/><path fill="url(#iDiSXxb)" class="bp-6-0bhm"/><path fill="url(#iLtMCSd)" class="kq06a5bxf"/><path fill="url(#impWW8G)" class="kq06a5bxf"/><path fill="url(#iJzTE4b)" class="kq06a5bxf"/><path fill="url(#iHRnz5c)" class="cr75l54jg"/><path fill="url(#i3lPDub)" class="cr75l54jg"/><path fill="url(#iUfV5db)" class="cr75l54jg"/><path fill="url(#iSyV23h)" class="ooufmxb1d"/><path fill="url(#iEy0Mib)" class="ooufmxb1d"/><path fill="url(#iSPvNpc)" class="ooufmxb1d"/><path fill="url(#iwk7Cae)" class="cld-9frbv"/><path fill="url(#iDIhGTZ)" class="cld-9frbv"/><path fill="url(#iNBCC0c)" class="cld-9frbv"/><defs><linearGradient id="iVPRBoE" x1="15.384" x2="9.108" y1="20.161" y2="20.073" gradientUnits="userSpaceOnUse"><stop offset=".096" class="dpoq6g9zo"/><stop offset="1" class="y_7_rui9j"/></linearGradient><linearGradient id="iLG2cqe" x1="9.395" x2="10.412" y1="21.2" y2="21.155" gradientUnits="userSpaceOnUse"><stop offset=".103" class="seslu4x4p"/><stop offset="1" class="ykmenjbge"/></linearGradient><linearGradient id="itKrpqc" x1="16.643" x2="15.693" y1="22.923" y2="22.945" gradientUnits="userSpaceOnUse"><stop class="jb8ile72u"/><stop offset="1" class="e_82vjbbi"/></linearGradient><linearGradient id="i3jHKUb" x1="12.958" x2="13.395" y1="14.373" y2="17.244" gradientUnits="userSpaceOnUse"><stop offset=".326" class="oiic8kcbl"/><stop offset="1" class="h-87kl5io"/></linearGradient><linearGradient id="iI5UMQc" x1="27.59" x2="23.244" y1="23.208" y2="27.455" gradientUnits="userSpaceOnUse"><stop offset=".156" class="rer8u4_cd"/><stop offset="1" class="y_7_rui9j"/></linearGradient><linearGradient id="iki1Woe" x1="22.59" x2="24.621" y1="23.708" y2="24.864" gradientUnits="userSpaceOnUse"><stop offset=".287" class="colph-y6o"/><stop offset="1" class="pyeevkbev"/></linearGradient><linearGradient id="ixOEYSZ" x1="28.871" x2="28.059" y1="23.77" y2="24.583" gradientUnits="userSpaceOnUse"><stop class="b8lv7ibeb"/><stop offset="1" class="kaicoabua"/></linearGradient><linearGradient id="i659Akb" x1="15.402" x2="11.215" y1="10.958" y2="17.076" gradientUnits="userSpaceOnUse"><stop class="z_jdw8bsx"/><stop offset="1" class="vf9rs_beo"/></linearGradient><linearGradient id="is7neld" x1="26.137" x2="21.949" y1="21.669" y2="27.787" gradientUnits="userSpaceOnUse"><stop class="z_jdw8bsx"/><stop offset="1" class="vf9rs_beo"/></linearGradient><linearGradient id="iDQnOXd" x1="17.059" x2="12.871" y1="12.63" y2="18.748" gradientUnits="userSpaceOnUse"><stop class="z_jdw8bsx"/><stop offset="1" class="vf9rs_beo"/></linearGradient><linearGradient id="iSVORRc" x1="27.793" x2="23.606" y1="23.34" y2="29.458" gradientUnits="userSpaceOnUse"><stop class="z_jdw8bsx"/><stop offset="1" class="vf9rs_beo"/></linearGradient><linearGradient id="iyvtvle" x1="18.715" x2="14.527" y1="14.302" y2="20.42" gradientUnits="userSpaceOnUse"><stop class="z_jdw8bsx"/><stop offset="1" class="vf9rs_beo"/></linearGradient><linearGradient id="ipax6Fd" x1="11.896" x2="15.959" y1="8.558" y2="4.246" gradientUnits="userSpaceOnUse"><stop class="w_5a8mv2g"/><stop offset="1" class="vv1ms1bgn"/></linearGradient><linearGradient id="iXsQFEe" x1="16.552" x2="16.076" y1="8.589" y2="8.097" gradientUnits="userSpaceOnUse"><stop class="sqhodub-z"/><stop offset="1" class="jjpgbon7o"/></linearGradient><linearGradient id="iSTPIkd" x1="11.162" x2="11.574" y1="3.261" y2="3.677" gradientUnits="userSpaceOnUse"><stop offset=".15" class="h8nnpglmy"/><stop offset="1" class="xrjlb-bcr"/></linearGradient><linearGradient id="i8qJKJe" x1="11.934" x2="8.277" y1="8.177" y2="12.208" gradientUnits="userSpaceOnUse"><stop class="d3ob2je0o"/><stop offset="1" class="qk3lrwe_x"/></linearGradient><linearGradient id="i0PZ0kb" x1="13.17" x2="12.671" y1="12.219" y2="11.704" gradientUnits="userSpaceOnUse"><stop offset=".324" class="jbum7c37w"/><stop offset="1" class="ltvjenbkq"/></linearGradient><linearGradient id="iDiSXxb" x1="7.53" x2="8.168" y1="6.645" y2="7.239" gradientUnits="userSpaceOnUse"><stop offset=".297" class="a0kmxhnng"/><stop offset="1" class="z457iyhvk"/></linearGradient><linearGradient id="iLtMCSd" x1="4.84" x2="8.902" y1="15.614" y2="11.302" gradientUnits="userSpaceOnUse"><stop class="law0jqbco"/><stop offset="1" class="pimiy_b9w"/></linearGradient><linearGradient id="impWW8G" x1="9.496" x2="9.02" y1="15.645" y2="15.153" gradientUnits="userSpaceOnUse"><stop offset=".185" class="aiawfxa2k"/><stop offset="1" class="fsu31dbjk"/></linearGradient><linearGradient id="iJzTE4b" x1="4.106" x2="4.59" y1="10.317" y2="10.794" gradientUnits="userSpaceOnUse"><stop offset=".297" class="zt1l7tsnp"/><stop offset="1" class="fsu31dbjk"/></linearGradient><linearGradient id="iHRnz5c" x1="22.56" x2="26.622" y1="19.183" y2="14.871" gradientUnits="userSpaceOnUse"><stop class="w_5a8mv2g"/><stop offset="1" class="vv1ms1bgn"/></linearGradient><linearGradient id="i3lPDub" x1="27.216" x2="26.74" y1="19.214" y2="18.722" gradientUnits="userSpaceOnUse"><stop class="sqhodub-z"/><stop offset="1" class="jjpgbon7o"/></linearGradient><linearGradient id="iUfV5db" x1="21.826" x2="22.238" y1="13.886" y2="14.302" gradientUnits="userSpaceOnUse"><stop offset=".15" class="h8nnpglmy"/><stop offset="1" class="xrjlb-bcr"/></linearGradient><linearGradient id="iSyV23h" x1="22.598" x2="18.942" y1="18.802" y2="22.833" gradientUnits="userSpaceOnUse"><stop class="d3ob2je0o"/><stop offset="1" class="qk3lrwe_x"/></linearGradient><linearGradient id="iEy0Mib" x1="23.834" x2="23.335" y1="22.844" y2="22.329" gradientUnits="userSpaceOnUse"><stop offset=".324" class="jbum7c37w"/><stop offset="1" class="ltvjenbkq"/></linearGradient><linearGradient id="iSPvNpc" x1="18.194" x2="18.832" y1="17.27" y2="17.864" gradientUnits="userSpaceOnUse"><stop offset=".297" class="a0kmxhnng"/><stop offset="1" class="z457iyhvk"/></linearGradient><linearGradient id="iwk7Cae" x1="15.504" x2="19.567" y1="26.239" y2="21.927" gradientUnits="userSpaceOnUse"><stop class="law0jqbco"/><stop offset="1" class="pimiy_b9w"/></linearGradient><linearGradient id="iDIhGTZ" x1="20.16" x2="19.684" y1="26.27" y2="25.778" gradientUnits="userSpaceOnUse"><stop offset=".185" class="aiawfxa2k"/><stop offset="1" class="fsu31dbjk"/></linearGradient><linearGradient id="iNBCC0c" x1="14.77" x2="15.254" y1="20.942" y2="21.419" gradientUnits="userSpaceOnUse"><stop offset=".297" class="zt1l7tsnp"/><stop offset="1" class="fsu31dbjk"/></linearGradient><radialGradient id="iLMhmte" cx="0" cy="0" r="1" gradientTransform="matrix(-4.15624 3.93751 -1.5257 -1.61045 30.84 26.114)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="rqg7hlbfi"/><stop offset="1" class="dlh_7b_4u"/></radialGradient><radialGradient id="iGXcfpe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 4.59375 -.54609 -.41607 15.184 11.74)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="g4iutwc4h"/><stop offset="1" class="cxsygj9-f"/></radialGradient><radialGradient id="iLuXVWc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 4.59375 -.54609 -.41607 25.918 22.45)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="g4iutwc4h"/><stop offset="1" class="cxsygj9-f"/></radialGradient><radialGradient id="i4RHVXd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 4.59375 -.54609 -.41607 16.84 13.411)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="g4iutwc4h"/><stop offset="1" class="cxsygj9-f"/></radialGradient><radialGradient id="iwkKKue" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 4.59375 -.54609 -.41607 27.574 24.122)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="g4iutwc4h"/><stop offset="1" class="cxsygj9-f"/></radialGradient><radialGradient id="ic6i6lC" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 4.59375 -.54609 -.41607 18.496 15.083)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="g4iutwc4h"/><stop offset="1" class="cxsygj9-f"/></radialGradient><filter id="iBFB8sc" width="9.72" height="9.72" x="20.317" y="20.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.286275 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24377"/></filter><filter id="i4POUNI" width="5.437" height="6.941" x="10.907" y="10.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.270588 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24377"/></filter><filter id="itk91Mb" width="5.437" height="6.941" x="21.642" y="20.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.270588 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24377"/></filter><filter id="irSk9nc" width="5.437" height="6.941" x="12.563" y="11.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.270588 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24377"/></filter><filter id="iPqgZVc" width="5.437" height="6.941" x="23.298" y="22.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.270588 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24377"/></filter><filter id="iQbORlc" width="5.437" height="6.941" x="14.22" y="13.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.270588 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24377"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:nut-and-bolt" /></template>
<style>
.a0kmxhnng {
  stop-color: var(--svg-color--a9a7ac, #A9A7AC);
}

.aiawfxa2k {
  stop-color: var(--svg-color--5e3d78, #5E3D78);
}

.b8lv7ibeb {
  stop-color: var(--svg-color--6b696f, #6B696F);
}

.bp-6-0bhm {
  d: path("m14.414 10.714l-3.74 3.739l-5.338-5.34l3.739-3.738z");
}

.cld-9frbv {
  d: path("M12.848 22.89a.6.6 0 0 0 0 .85l4.49 4.49a.6.6 0 0 0 .849 0l3.162-3.163l-5.339-5.338z");
}

.colph-y6o {
  stop-color: var(--svg-color--6e607d, #6E607D);
}

.cr75l54jg {
  d: path("m25.067 21.35l-5.339-5.34l3.162-3.162a.6.6 0 0 1 .849 0l4.49 4.49l.005.005a.6.6 0 0 1-.005.844z");
}

.cxsygj9-f {
  stop-color: var(--svg-color--c6c0cc, #C6C0CC);
  stop-opacity: 0;
}

.d3ob2je0o {
  stop-color: var(--svg-color--b8b0c2, #B8B0C2);
}

.dlh_7b_4u {
  stop-color: var(--svg-color--6e6a72, #6E6A72);
  stop-opacity: 0;
}

.dpoq6g9zo {
  stop-color: var(--svg-color--9f9ca1, #9F9CA1);
}

.du0dk-b3k {
  d: path("M14.403 10.724L9.064 5.385l3.162-3.162a.6.6 0 0 1 .849 0l4.49 4.49l.005.006a.6.6 0 0 1-.005.843z");
}

.e_82vjbbi {
  stop-color: var(--svg-color--a09ea2, #A09EA2);
  stop-opacity: 0;
}

.e45gmd_kw {
  d: path("m20.318 25.084l4.773-4.774l4.27 4.27a1.8 1.8 0 0 1 0 2.545l-2.229 2.228a1.8 1.8 0 0 1-2.545 0z");
}

.fsu31dbjk {
  stop-color: var(--svg-color--7c7087, #7C7087);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fujdaxbzw {
  d: path("M9.583 14.373h6.751v8.859H9.583z");
}

.g4iutwc4h {
  stop-color: var(--svg-color--c6c0cc, #C6C0CC);
}

.h-87kl5io {
  stop-color: var(--svg-color--62566e, #62566E);
  stop-opacity: 0;
}

.h1os5rb_p {
  d: path("M16.903 12.034a.551.551 0 1 1 .893.648L13.56 18.52a.551.551 0 0 1-.893-.647z");
}

.h8nnpglmy {
  stop-color: var(--svg-color--abaaac, #ABAAAC);
}

.jb8ile72u {
  stop-color: var(--svg-color--706f70, #706F70);
}

.jbum7c37w {
  stop-color: var(--svg-color--847295, #847295);
}

.jjpgbon7o {
  stop-color: var(--svg-color--aeaab4, #AEAAB4);
  stop-opacity: 0;
}

.kaicoabua {
  stop-color: var(--svg-color--7e7687, #7E7687);
  stop-opacity: 0;
}

.kq06a5bxf {
  d: path("M2.184 12.266a.6.6 0 0 0 0 .848l4.49 4.49a.6.6 0 0 0 .849 0l3.162-3.162l-5.339-5.339z");
}

.law0jqbco {
  stop-color: var(--svg-color--7b7087, #7B7087);
}

.ltvjenbkq {
  stop-color: var(--svg-color--9e91ad, #9E91AD);
  stop-opacity: 0;
}

.ni1f3ybnb {
  width: 15.402px;
  height: 7.55px;
  x: 1.76px;
  y: 12.69px;
  fill: var(--svg-color--e7c823, #E7C823);
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  rx: 0.6px;
}

.oiic8kcbl {
  stop-color: var(--svg-color--62566e, #62566E);
}

.ooufmxb1d {
  d: path("m25.078 21.339l-3.74 3.739L16 19.738L19.739 16z");
}

.osutr4bux {
  d: path("M18.56 13.706a.551.551 0 1 1 .892.648l-4.235 5.838a.551.551 0 0 1-.892-.647z");
}

.pimiy_b9w {
  stop-color: var(--svg-color--8a7d98, #8A7D98);
}

.pyeevkbev {
  stop-color: var(--svg-color--6e607d, #6E607D);
  stop-opacity: 0;
}

.qk3lrwe_x {
  stop-color: var(--svg-color--a197ac, #A197AC);
}

.rer8u4_cd {
  stop-color: var(--svg-color--9d9aa0, #9D9AA0);
}

.rqg7hlbfi {
  stop-color: var(--svg-color--6e6a72, #6E6A72);
}

.rtsquubvp {
  d: path("M27.638 22.745a.551.551 0 1 1 .892.647l-4.235 5.839a.551.551 0 0 1-.892-.648z");
}

.s_fqvqb0k {
  d: path("M15.247 10.363a.551.551 0 0 1 .892.647l-4.234 5.838a.551.551 0 1 1-.893-.647z");
}

.seslu4x4p {
  stop-color: var(--svg-color--564964, #564964);
}

.sqhodub-z {
  stop-color: var(--svg-color--7a7183, #7A7183);
}

.teaiskqrf {
  width: 15.402px;
  height: 7.55px;
  x: 12.424px;
  y: 23.315px;
  fill: var(--svg-color--e7c823, #E7C823);
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  rx: 0.6px;
}

.vf9rs_beo {
  stop-color: var(--svg-color--746087, #746087);
}

.vv1ms1bgn {
  stop-color: var(--svg-color--c4c2c6, #C4C2C6);
}

.w_5a8mv2g {
  stop-color: var(--svg-color--c4c1c7, #C4C1C7);
}

.xnrz800pp {
  d: path("M25.981 21.073a.551.551 0 0 1 .893.648l-4.235 5.838a.551.551 0 0 1-.892-.647z");
}

.xrjlb-bcr {
  stop-color: var(--svg-color--bfbec1, #BFBEC1);
  stop-opacity: 0;
}

.y_7_rui9j {
  stop-color: var(--svg-color--675b74, #675B74);
}

.ykmenjbge {
  stop-color: var(--svg-color--6d6178, #6D6178);
  stop-opacity: 0;
}

.z_jdw8bsx {
  stop-color: var(--svg-color--9c999f, #9C999F);
}

.z457iyhvk {
  stop-color: var(--svg-color--aba2b6, #ABA2B6);
  stop-opacity: 0;
}

.zt1l7tsnp {
  stop-color: var(--svg-color--8b888e, #8B888E);
}

</style>
