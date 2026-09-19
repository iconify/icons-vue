<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#itKRlfd)"><path fill="url(#ivCJCDe)" class="z6iq89k-l"/><path fill="url(#i83uBhd)" class="z6iq89k-l"/></g><g filter="url(#iSL7Gvb)"><path class="piadky3jn"/><path fill="url(#iYhAS3F)" class="p9vqx753j"/><path fill="url(#iebEf6S)" class="p9vqx753j"/></g><path fill="url(#izCdhes)" class="pzbf-jbze"/><g filter="url(#iGpKTdb)"><path fill="url(#iAm5omc)" class="fckvymngf"/></g><g filter="url(#ibOu0Ne)"><path fill="url(#iMjJxPe)" class="a52jxxbfs"/><path fill="url(#il8BDJc)" class="a52jxxbfs"/><path fill="url(#inizTfe)" class="a52jxxbfs"/><path fill="url(#iXX1iNb)" class="a52jxxbfs"/><path fill="url(#iIFGLde)" class="a52jxxbfs"/><path fill="url(#iadcJGc)" class="a52jxxbfs"/><path fill="url(#ic8fStb)" class="a52jxxbfs"/></g><g filter="url(#ikud9ve)"><path class="rerqw8b5s"/></g><g filter="url(#ijGFqyB)"><path class="jkpxbfuaz"/><path fill="url(#iLz0Feb)" class="znzaaubnk"/><path fill="url(#itPvrFe)" class="znzaaubnk"/><path fill="url(#iUqfBfe)" class="znzaaubnk"/></g><path class="kw864jbvf"/><path fill="url(#icQCmld)" class="wz52iplvu"/><path fill="url(#inqcDHd)" class="wz52iplvu"/><g filter="url(#ivbmIne)"><path class="lit4869de"/><path fill="url(#irQWmPd)" class="chjxwsbzf"/><path fill="url(#iplfhue)" class="chjxwsbzf"/><path fill="url(#imL5VQc)" class="chjxwsbzf"/></g><path stroke="url(#iwvwAXb)" class="uvaxluuzh"/><path class="wynbmo_vz"/><path class="m2hokjbdt"/><rect fill="url(#irqhOBe)" class="h35r4abeo"/><rect fill="url(#iqsKTwC)" class="r4sz7ng0d"/><path class="n0to9vbsx"/><path fill="url(#iCfbqqJ)" class="uz0pj_bkh"/><path class="y5r__wkxq"/><g filter="url(#i1UJnbc)"><path fill="url(#iDSmrbC)" class="jd9v5rb-z"/></g><g filter="url(#iCtRxld)"><ellipse transform="rotate(-27.914 11.516 16.824)" class="k1ub3bcjy"/><ellipse fill="url(#iEVaPFc)" transform="rotate(-27.914 11.516 16.824)" class="s8t9myb8q"/></g><path class="rt3_y7bzi"/><path fill="url(#isJX3zb)" class="cqci3b2qy"/><path class="m4g3-xncq"/><g filter="url(#iqNT7oa)"><path class="hmtpk2bbc"/><path fill="url(#i8Ob9SP)" class="uu6qi9bsp"/></g><g filter="url(#ifbGa2b)"><path fill="url(#i7HHy5b)" class="h78cjko8o"/></g><g filter="url(#ifk1jeI)"><path class="r22ck6bij"/></g><g filter="url(#ibn1GBd)"><path stroke="url(#iHiRoKd)" class="nenx9k6va"/></g><g filter="url(#iNMBcre)"><path class="jyshombsi"/></g><g filter="url(#icQdkqd)"><path stroke="url(#inpVLRb)" class="g4d_qebii"/></g><defs><radialGradient id="i83uBhd" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 39.87 -30.608)scale(1.93052 2.20343)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iYhAS3F" cx="0" cy="0" r="1" gradientTransform="matrix(1.64694 -3.0292 1.773 .96396 24.87 19.752)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iebEf6S" cx="0" cy="0" r="1" gradientTransform="matrix(.51997 .5147 -.66351 .67031 24.954 18.105)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="izCdhes" cx="0" cy="0" r="1" gradientTransform="matrix(3.31277 0 0 5.79738 4.067 18.105)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iMjJxPe" cx="0" cy="0" r="1" gradientTransform="rotate(152.026 9.332 10.298)scale(17.0552 31.3253)" gradientUnits="userSpaceOnUse"><stop class="efamoh3_s"/><stop offset=".885" class="eoj3umbss"/><stop offset="1" class="fk9ehdchw"/></radialGradient><radialGradient id="il8BDJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.8125 26.0906 0 16.125 30.016)" gradientUnits="userSpaceOnUse"><stop class="xcqa65bgd"/><stop offset="1" class="c4g4xyz0z"/></radialGradient><radialGradient id="inizTfe" cx="0" cy="0" r="1" gradientTransform="rotate(159.254 12.385 6.7)scale(13.233 12.7637)" gradientUnits="userSpaceOnUse"><stop class="bxzm90wdr"/><stop offset="1" class="vbc1pcc0r"/></radialGradient><radialGradient id="iXX1iNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.625 3.09375 0 20.935 15.797)" gradientUnits="userSpaceOnUse"><stop class="jl1lwog9k"/><stop offset="1" class="d1e-cp73v"/></radialGradient><radialGradient id="iIFGLde" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.875 3.15323 0 12.625 16.063)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="xal_ovbdi"/><stop offset="1" class="z4mkwacyn"/></radialGradient><radialGradient id="iadcJGc" cx="0" cy="0" r="1" gradientTransform="rotate(-142.765 14.29 .85)scale(2.94381 2.5308)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="gn6su3bsr"/><stop offset="1" class="amjspub2k"/></radialGradient><radialGradient id="ic8fStb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.54686 1.37501 -1.06983 -1.20354 7.513 10.89)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="mq_dd8u_o"/><stop offset="1" class="yaxzkyb1m"/></radialGradient><radialGradient id="icQCmld" cx="0" cy="0" r="1" gradientTransform="rotate(139.273 2.45 6.038)scale(4.16691 7.99724)" gradientUnits="userSpaceOnUse"><stop class="rlhs-hbwc"/><stop offset="1" class="xi80kbc0k"/></radialGradient><radialGradient id="inqcDHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.04688 -.9516 0 7.09 14.86)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="l9fk14bxd"/><stop offset="1" class="uyez41bsl"/></radialGradient><radialGradient id="irQWmPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.98438 -2.09375 .72837 .69032 24.622 13.297)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="aq7827bba"/><stop offset="1" class="tco_4qs8v"/></radialGradient><radialGradient id="iplfhue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 2.625 -2.01353 -1.12662 25.904 9.14)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="wgw2105cx"/><stop offset="1" class="fj_enu3ru"/></radialGradient><radialGradient id="imL5VQc" cx="0" cy="0" r="1" gradientTransform="matrix(.32886 -4.54687 .85753 .06202 26.841 16.39)" gradientUnits="userSpaceOnUse"><stop class="bddxqszam"/><stop offset="1" class="bwtw0srgi"/></radialGradient><radialGradient id="iCfbqqJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 12.021 17.625)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iEVaPFc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.314 3.051)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isJX3zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.158 17.624)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8Ob9SP" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.068 3.747)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="itKRlfd" width="6.553" height="6.553" x="21.802" y="14.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20111"/></filter><filter id="iSL7Gvb" width="4.991" height="4.991" x="22.459" y="15.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".25"/></filter><filter id="iGpKTdb" width="4.991" height="4.991" x="4.723" y="15.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".25"/></filter><filter id="ibOu0Ne" width="20.543" height="25.5" x="6.354" y="4.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20111"/></filter><filter id="ikud9ve" width="4.796" height="6.408" x="13.272" y="16.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".375"/></filter><filter id="ijGFqyB" width="3.796" height="5.408" x="14.272" y="16.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".125"/></filter><filter id="ivbmIne" width="4.3" height="9.2" x="23.17" y="7.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.568627 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20111"/></filter><filter id="i1UJnbc" width="1.493" height="1.594" x="12.245" y="16.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".1"/></filter><filter id="iCtRxld" width="1.529" height="1.141" x="10.751" y="16.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".05"/></filter><filter id="iqNT7oa" width="1.294" height="1.125" x="18.875" y="16.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".05"/></filter><filter id="ifbGa2b" width="1.316" height="1.357" x="20.528" y="16.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".1"/></filter><filter id="ifk1jeI" width="5.214" height="3" x="18.514" y="11.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20111"/></filter><filter id="ibn1GBd" width="4.458" height="2.061" x="18.789" y="12.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".2"/></filter><filter id="iNMBcre" width="5.214" height="3" x="8.912" y="11.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20111"/></filter><filter id="icQdkqd" width="4.458" height="2.061" x="9.093" y="12.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20111" stdDeviation=".2"/></filter><linearGradient id="ivCJCDe" x1="27.005" x2="25.459" y1="16.044" y2="20.832" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iAm5omc" x1="7.218" x2="5.934" y1="18.663" y2="18.663" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iLz0Feb" x1="14.522" x2="15.966" y1="20.016" y2="19.953" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="itPvrFe" x1="17.818" x2="16.017" y1="20.665" y2="20.64" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iUqfBfe" x1="16.512" x2="16.512" y1="22.024" y2="20.975" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iwvwAXb" x1="14.845" x2="15.639" y1="25.084" y2="23.521" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="irqhOBe" x1="13.17" x2="16.341" y1="8.159" y2="8.159" gradientUnits="userSpaceOnUse"><stop class="akv6opcyu"/><stop offset="1" class="pwvx5nbpq"/></linearGradient><linearGradient id="iqsKTwC" x1="11.126" x2="19.466" y1="10.538" y2="10.538" gradientUnits="userSpaceOnUse"><stop class="wn_hhmb-o"/><stop offset="1" class="brr6wubwq"/></linearGradient><linearGradient id="iDSmrbC" x1="13.408" x2="12.823" y1="17.103" y2="17.463" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7HHy5b" x1="21.608" x2="21.023" y1="17.103" y2="17.463" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHiRoKd" x1="22.646" x2="19.154" y1="13.555" y2="13.555" gradientUnits="userSpaceOnUse"><stop class="k1bf3nb_z"/><stop offset="1" class="crw81imix"/></linearGradient><linearGradient id="inpVLRb" x1="12.794" x2="9.091" y1="12.693" y2="14.172" gradientUnits="userSpaceOnUse"><stop class="k1bf3nb_z"/><stop offset="1" class="crw81imix"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-man" /></template>
<style>
.a52jxxbfs {
  d: path("M15.27 4.516c-5.2 0-9.2 4.4-8.9 9.5l.8 10.4c.3 3.3 2.8 5.6 6 5.6h6c3.1 0 5.7-2.3 6-5.6l.7-10.4c.4-5.2-3.7-9.5-8.9-9.5z");
}

.akv6opcyu {
  stop-color: var(--svg-color--efae13, #EFAE13);
}

.amjspub2k {
  stop-color: var(--svg-color--e0a212, #E0A212);
  stop-opacity: 0;
}

.aq7827bba {
  stop-color: var(--svg-color--8f8286, #8F8286);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bddxqszam {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
}

.brr6wubwq {
  stop-color: var(--svg-color--ffc428, #FFC428);
}

.bwtw0srgi {
  stop-color: var(--svg-color--b1adb0, #B1ADB0);
  stop-opacity: 0;
}

.bxzm90wdr {
  stop-color: var(--svg-color--ffea45, #FFEA45);
}

.c4g4xyz0z {
  stop-color: var(--svg-color--fda63f, #FDA63F);
  stop-opacity: 0;
}

.chjxwsbzf {
  d: path("M23.904 11.564a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.562-.508.998-1.071.998v-3.527a1 1 0 0 0-.366-.773l-1.403-1.15z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqci3b2qy {
  d: path("M20.162 16.113a1.664 1.664 0 0 1 1.603 2.103h-3.214a1.7 1.7 0 0 1-.06-.44a1.67 1.67 0 0 1 1.67-1.663");
}

.crw81imix {
  stop-color: var(--svg-color--a9a8a9, #A9A8A9);
  stop-opacity: 0;
}

.d1e-cp73v {
  stop-color: var(--svg-color--ffb727, #FFB727);
  stop-opacity: 0;
}

.efamoh3_s {
  stop-color: var(--svg-color--ffe444, #FFE444);
}

.eoj3umbss {
  stop-color: var(--svg-color--f39f2a, #F39F2A);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.fckvymngf {
  d: path("M7.218 20.1a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.fj_enu3ru {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
  stop-opacity: 0;
}

.fk9ehdchw {
  stop-color: var(--svg-color--e58d37, #E58D37);
}

.ft5dv1b6b {
  fill: none;
}

.g4d_qebii {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.951 12.711c-.883-.07-2.195.039-3.258.844");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gn6su3bsr {
  stop-color: var(--svg-color--e0a212, #E0A212);
}

.h35r4abeo {
  width: 6px;
  height: 1px;
  x: 13.17px;
  y: 7.159px;
  rx: 0.5px;
}

.h78cjko8o {
  d: path("M21.644 17.558a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.425z");
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hmtpk2bbc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M20.04 16.465c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.jd9v5rb-z {
  d: path("M13.538 17.581c0-.537-.437-.896-.556-1.004l-.537.52l.33.673z");
}

.jkpxbfuaz {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.567 17.624l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.655-.944-.7-1.244 0");
}

.jl1lwog9k {
  stop-color: var(--svg-color--ffb727, #FFB727);
}

.jyshombsi {
  stroke: var(--svg-color--9c9892, #9C9892);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M12.951 13.016c-.71-.094-2.086-.079-3.164.812");
}

.k1bf3nb_z {
  stop-color: var(--svg-color--a9a8a9, #A9A8A9);
}

.k1ub3bcjy {
  cx: 11.516px;
  cy: 16.824px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kw864jbvf {
  fill: var(--svg-color--7f7680, #7F7680);
  d: path("M8.356 11.564a2 2 0 1 0-3.245-1.26l.407 5.714c.04.562.508.99 1.072.99v-3.519a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.l9fk14bxd {
  stop-color: var(--svg-color--735551, #735551);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lit4869de {
  fill: var(--svg-color--9f9aa1, #9F9AA1);
  d: path("M23.904 11.564a2 2 0 1 1 3.246-1.26l-.409 5.714c-.04.562-.508.998-1.071.998v-3.527a1 1 0 0 0-.366-.773l-1.403-1.15z");
}

.m2hokjbdt {
  fill: var(--svg-color--ffa30c, #FFA30C);
  d: path("M13.335 18.827a.5.5 0 0 1 .724.69h-.001l-.002.002l-.004.005l-.011.011l-.038.037q-.047.044-.13.114a3.56 3.56 0 0 1-2.255.806a.5.5 0 1 1-.001-1a2.56 2.56 0 0 0 1.718-.665");
}

.m4g3-xncq {
  fill: var(--svg-color--000, #000);
  d: path("M19.209 17.777c0-.53.423-.953.953-.953s.953.423.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.44");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mq_dd8u_o {
  stop-color: var(--svg-color--c5801b, #C5801B);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n0to9vbsx {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.632 15.606c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.636h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.nenx9k6va {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.389 12.711c.883-.07 2.195.039 3.258.844");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.p9vqx753j {
  d: path("M24.954 20.1a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.piadky3jn {
  fill: var(--svg-color--ffbf34, #FFBF34);
  d: path("M24.954 20.1a1.995 1.995 0 1 0 0-3.99a1.995 1.995 0 0 0 0 3.99");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pwvx5nbpq {
  stop-color: var(--svg-color--ffc321, #FFC321);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.pzbf-jbze {
  d: path("M7.218 21.256a3.152 3.152 0 1 0 0-6.303a3.152 3.152 0 0 0 0 6.303");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r22ck6bij {
  stroke: var(--svg-color--9c9892, #9C9892);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
  d: path("M19.389 13.016c.71-.094 2.086-.079 3.164.812");
}

.r4sz7ng0d {
  width: 10px;
  height: 1px;
  x: 11.126px;
  y: 9.538px;
  rx: 0.5px;
}

.rerqw8b5s {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("M15.638 17.9L14.067 21c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.9-3.1c-.227-.655-.429-.7-.729 0");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rlhs-hbwc {
  stop-color: var(--svg-color--bbb6b3, #BBB6B3);
}

.rt3_y7bzi {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.547 15.606c1.218 0 2.247.84 2.526 1.974a.51.51 0 0 1-.499.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.103");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s8t9myb8q {
  cx: 11.516px;
  cy: 16.824px;
  rx: 0.726px;
  ry: 0.368px;
}

.tco_4qs8v {
  stop-color: var(--svg-color--8f8286, #8F8286);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.uu6qi9bsp {
  d: path("M20.04 16.465c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.uvaxluuzh {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.61 23.192a.335.335 0 0 0-.4.069a.305.305 0 0 0-.034.393a3.58 3.58 0 0 0 2.994 1.6a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.397a.34.34 0 0 0-.4-.065a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.221-2.56-.607Z");
}

.uyez41bsl {
  stop-color: var(--svg-color--735551, #735551);
  stop-opacity: 0;
}

.uz0pj_bkh {
  d: path("M12.018 16.113a1.664 1.664 0 0 0-1.604 2.103h3.215c.037-.144.06-.288.06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vbc1pcc0r {
  stop-color: var(--svg-color--ffea45, #FFEA45);
  stop-opacity: 0;
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.wgw2105cx {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
}

.wn_hhmb-o {
  stop-color: var(--svg-color--efa814, #EFA814);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wynbmo_vz {
  fill: var(--svg-color--ffc31b, #FFC31B);
  d: path("M18.11 18.8a.5.5 0 0 1 .706.038c.195.219.377.37.612.474c.24.106.575.18 1.095.18a.5.5 0 1 1 0 1c-.612 0-1.094-.086-1.499-.265c-.409-.181-.701-.44-.954-.722a.5.5 0 0 1 .04-.706");
}

.wz52iplvu {
  d: path("M8.356 11.564a2 2 0 1 0-3.245-1.26l.407 5.714c.04.562.508.99 1.072.99v-3.519a1 1 0 0 1 .366-.773l1.403-1.15z");
}

.xal_ovbdi {
  stop-color: var(--svg-color--f1942a, #F1942A);
}

.xcqa65bgd {
  stop-color: var(--svg-color--d77973, #D77973);
}

.xi80kbc0k {
  stop-color: var(--svg-color--807680, #807680);
  stop-opacity: 0;
}

.y5r__wkxq {
  fill: var(--svg-color--000, #000);
  d: path("M12.97 17.777a.95.95 0 0 0-.952-.953a.95.95 0 0 0-.953.953c0 .159.037.31.106.439h1.686a.95.95 0 0 0 .114-.439");
}

.yaxzkyb1m {
  stop-color: var(--svg-color--c5801b, #C5801B);
  stop-opacity: 0;
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.z4mkwacyn {
  stop-color: var(--svg-color--f1942a, #F1942A);
  stop-opacity: 0;
}

.z6iq89k-l {
  d: path("M24.954 21.256a3.152 3.152 0 1 0 0-6.303a3.152 3.152 0 0 0 0 6.303");
}

.znzaaubnk {
  d: path("m15.567 17.624l-1 3.1c-.2.6.3 1.3.9 1.3h1.4c.7 0 1.1-.6.9-1.3l-.956-3.1c-.226-.655-.944-.7-1.244 0");
}

</style>
