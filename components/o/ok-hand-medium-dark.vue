<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iIaSfwp)" class="d2kvgvbvc"><path class="x9sbbz01j"/><path fill="url(#iHxBl6e)" class="cq9prsi4g"/><path fill="url(#ix8Omcc)" class="cq9prsi4g"/><path fill="url(#iA1fZWd)" class="cq9prsi4g"/><path fill="url(#ig6R3rc)" class="cq9prsi4g"/></g><path fill="url(#i7TtSkd)" class="c_se9ggnw"/><path fill="url(#ihaJYsd)" class="c_se9ggnw"/><path fill="url(#iENMWbv)" class="c_se9ggnw"/><path fill="url(#ix9OABc)" class="c_se9ggnw"/><path fill="url(#idCpcYd)" class="c_se9ggnw"/><path fill="url(#iTj0gzd)" class="r4n0bhb9j"/><path fill="url(#iG5eYFc)" class="r4n0bhb9j"/><path fill="url(#ibAFBce)" class="r4n0bhb9j"/><path fill="url(#iBitIZc)" class="wwtloyb4r"/><path fill="url(#i4eec7p)" class="kasfw-b4p"/><path fill="url(#iKfHjFc)" class="kasfw-b4p"/><path fill="url(#ildRgOb)" class="kasfw-b4p"/><path fill="url(#iNhl2YG)" class="kasfw-b4p"/><g filter="url(#iaSrCCe)"><path stroke="url(#iXrwgmb)" class="bu5meojdd"/></g><g filter="url(#ijwqIYd)"><path stroke="url(#iIywtHd)" class="bkawxhb2a"/></g><g filter="url(#ixRGS1d)"><path stroke="url(#inHGR8b)" class="kz2xabbma"/></g><g filter="url(#iszlOjb)"><path stroke="url(#iOJdeac)" class="tdy7-m_fn"/></g><g filter="url(#i4cMo7b)"><path stroke="url(#ijVMUrd)" class="ojt9yacts"/></g><g filter="url(#ic9b6Zd)"><path fill="url(#i0JFNse)" class="l6as6xbzq"/></g><path fill="url(#ipoY4RN)" clip-rule="evenodd" class="t9ok82b3y"/><g filter="url(#ib3Gxmb)"><path stroke="url(#i3ICs7c)" class="dd7t-y1vp"/></g><path fill="url(#iiQHVYc)" clip-rule="evenodd" class="nc_7llbtt"/><path fill="url(#iwqu58b)" clip-rule="evenodd" class="nc_7llbtt"/><defs><radialGradient id="iHxBl6e" cx="0" cy="0" r="1" gradientTransform="matrix(5.375 -4.125 3.93242 5.12408 17.156 19.594)" gradientUnits="userSpaceOnUse"><stop class="hkz328bqo"/><stop offset="1" class="wca7y5bhk"/></radialGradient><radialGradient id="ix8Omcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 18.56245 -25.6022 -.2586 16.938 13.625)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="wca7y5bhk"/><stop offset="1" class="hkz328bqo"/></radialGradient><radialGradient id="iA1fZWd" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -4.09375 3.46317 3.80685 16.4 20.641)" gradientUnits="userSpaceOnUse"><stop class="z-0gueb0f"/><stop offset="1" class="jht_zhawt"/></radialGradient><radialGradient id="ig6R3rc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00781 .49219 -1.27635 -.02026 10.525 20.212)" gradientUnits="userSpaceOnUse"><stop class="n5i92-bxt"/><stop offset="1" class="tyk5u9bea"/></radialGradient><radialGradient id="ihaJYsd" cx="0" cy="0" r="1" gradientTransform="rotate(-174.743 10.476 2.126)scale(8.33535 9.22751)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="xni46r-cx"/><stop offset="1" class="d0xayr3dz"/></radialGradient><radialGradient id="iENMWbv" cx="0" cy="0" r="1" gradientTransform="rotate(-154.517 11.642 2.015)scale(9.9117 7.62008)" gradientUnits="userSpaceOnUse"><stop offset=".843" class="aqhysfbck"/><stop offset="1" class="k173lu9mn"/></radialGradient><radialGradient id="ibAFBce" cx="0" cy="0" r="1" gradientTransform="matrix(1.49666 -1.00685 2.09997 3.12156 21.8 11.109)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="nme1cfesl"/><stop offset="1" class="ef1pub4em"/></radialGradient><radialGradient id="iBitIZc" cx="0" cy="0" r="1" gradientTransform="rotate(-139.939 13.932 -.23)scale(6.46203 7.66123)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="t00zf_cht"/><stop offset="1" class="rwu83tbfd"/></radialGradient><radialGradient id="iKfHjFc" cx="0" cy="0" r="1" gradientTransform="matrix(.04249 -1.69485 4.92857 .12355 13.049 12.268)" gradientUnits="userSpaceOnUse"><stop class="khtdutk0u"/><stop offset="1" class="uobifuudt"/></radialGradient><radialGradient id="ildRgOb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.72015 -2.73997 2.13394 -9.90668 18.338 10.888)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="c7drhqdxk"/><stop offset="1" class="jh87cpzru"/></radialGradient><radialGradient id="iNhl2YG" cx="0" cy="0" r="1" gradientTransform="rotate(119.455 6.198 9.903)scale(1.52522 3.27464)" gradientUnits="userSpaceOnUse"><stop class="ry5i5sbis"/><stop offset="1" class="py95h14ou"/></radialGradient><radialGradient id="ipoY4RN" cx="0" cy="0" r="1" gradientTransform="matrix(17.94785 -2.6167 3.73476 25.61648 8.775 18.267)" gradientUnits="userSpaceOnUse"><stop offset=".938" class="w2cs_g5_a"/><stop offset="1" class="gj8dnnbxp"/></radialGradient><radialGradient id="i3ICs7c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.01673 2.30124 -3.6321 -6.3397 24.612 14.691)" gradientUnits="userSpaceOnUse"><stop class="luxj8_upm"/><stop offset="1" class="uleenob4d"/></radialGradient><radialGradient id="iiQHVYc" cx="0" cy="0" r="1" gradientTransform="rotate(-136.278 18.377 8.968)scale(21.5991 16.1413)" gradientUnits="userSpaceOnUse"><stop offset=".896" class="e5xukvbnc"/><stop offset=".995" class="e_pv8vb-f"/></radialGradient><radialGradient id="iwqu58b" cx="0" cy="0" r="1" gradientTransform="matrix(4.45938 3.05706 -3.07412 4.48427 16.859 20.452)" gradientUnits="userSpaceOnUse"><stop class="dnrnmmbrl"/><stop offset="1" class="tdwmw7_4a"/></radialGradient><linearGradient id="i7TtSkd" x1="14.915" x2="16.619" y1="8.438" y2="7.11" gradientUnits="userSpaceOnUse"><stop class="rprohccev"/><stop offset="1" class="n046mbcil"/></linearGradient><linearGradient id="ix9OABc" x1="21.9" x2="19.462" y1="6.985" y2="9.485" gradientUnits="userSpaceOnUse"><stop class="rqd6f-bxg"/><stop offset="1" class="q3w127o1w"/></linearGradient><linearGradient id="idCpcYd" x1="22.337" x2="21.025" y1="10.985" y2="9.235" gradientUnits="userSpaceOnUse"><stop class="xokztdbiw"/><stop offset="1" class="nons3q-fd"/></linearGradient><linearGradient id="iTj0gzd" x1="20.369" x2="23.096" y1="9.704" y2="9.473" gradientUnits="userSpaceOnUse"><stop class="msqjrkbsa"/><stop offset="1" class="dnxgkab9a"/></linearGradient><linearGradient id="iG5eYFc" x1="25.65" x2="24.892" y1="12.329" y2="11.389" gradientUnits="userSpaceOnUse"><stop class="xokztdbiw"/><stop offset="1" class="nons3q-fd"/></linearGradient><linearGradient id="i4eec7p" x1="8.781" x2="9.554" y1="12.268" y2="9.473" gradientUnits="userSpaceOnUse"><stop class="phw3o18-l"/><stop offset="1" class="dp19-7b1f"/></linearGradient><linearGradient id="iXrwgmb" x1="22.747" x2="27.634" y1="5.273" y2="7.796" gradientUnits="userSpaceOnUse"><stop class="bvh29-rfu"/><stop offset="1" class="k8lf-zbxd"/></linearGradient><linearGradient id="iIywtHd" x1="17.056" x2="22.05" y1="4.922" y2="11.363" gradientUnits="userSpaceOnUse"><stop class="bvh29-rfu"/><stop offset="1" class="k8lf-zbxd"/></linearGradient><linearGradient id="inHGR8b" x1="9.868" x2="10.319" y1="8.65" y2="11.524" gradientUnits="userSpaceOnUse"><stop class="vf7g99b5q"/><stop offset="1" class="ih2u7_t8f"/></linearGradient><linearGradient id="iOJdeac" x1="10.586" x2="18.055" y1="17.274" y2="11.748" gradientUnits="userSpaceOnUse"><stop class="dfypbomlg"/><stop offset="1" class="vc1buwnev"/></linearGradient><linearGradient id="ijVMUrd" x1="11.444" x2="18.854" y1="22.654" y2="23.12" gradientUnits="userSpaceOnUse"><stop class="bcb3j38ph"/><stop offset="1" class="hwahr-bmb"/></linearGradient><linearGradient id="i0JFNse" x1="26.998" x2="22.025" y1="20.364" y2="11.641" gradientUnits="userSpaceOnUse"><stop class="yeujlnb_f"/><stop offset="1" class="ylx9ivbbn"/></linearGradient><filter id="iIaSfwp" width="21.365" height="26.791" x="5.617" y="2.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.25098 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1761"/></filter><filter id="iaSrCCe" width="6.375" height="10.781" x="20.181" y="2.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1761" stdDeviation=".625"/></filter><filter id="ijwqIYd" width="9.391" height="9.797" x="13.697" y="2.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1761" stdDeviation=".625"/></filter><filter id="ixRGS1d" width="11.703" height="5.477" x="5.9" y="6.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1761" stdDeviation=".625"/></filter><filter id="iszlOjb" width="11.469" height="8.74" x="8.586" y="11.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1761" stdDeviation=".625"/></filter><filter id="i4cMo7b" width="10.391" height="7.415" x="9.125" y="20.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1761" stdDeviation=".625"/></filter><filter id="ic9b6Zd" width="10.483" height="12.356" x="16.369" y="9.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1761" stdDeviation=".5"/></filter><filter id="ib3Gxmb" width="8.873" height="11.495" x="17.77" y="10.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1761" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ok-hand-medium-dark" /></template>
<style>
.aqhysfbck {
  stop-color: var(--svg-color--75594e, #75594E);
  stop-opacity: 0;
}

.bcb3j38ph {
  stop-color: var(--svg-color--ac847b, #AC847B);
}

.bkawxhb2a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M15.572 4.563c1.062.672 3.609 2.984 5.64 6.047");
}

.bu5meojdd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M22.056 4.855c.625.823 2.156 4.38 2.625 7.031");
}

.bvh29-rfu {
  stop-color: var(--svg-color--a27d6f, #A27D6F);
}

.c_se9ggnw {
  d: path("M13.358 3.771a2.25 2.25 0 0 1 3.158-.39c2.27 1.77 4.471 4.407 6.043 7.323h-3.168c-1.46-1.223-3.148-2.128-4.81-2.779q-.432-.467-.85-.863c-.98-.764-1.137-2.31-.373-3.29");
}

.c7drhqdxk {
  stop-color: var(--svg-color--84635a, #84635A);
  stop-opacity: 0;
}

.cq9prsi4g {
  d: path("M13.358 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.176-1.39c1.49 2.53 2.62 6.233 2.907 9.933l.011-.001l.015.278c.034.597.104 1.816.067 4.111c-.037 2.313-.674 4.143-1.606 5.678c-1.613 2.756-4.67 4.575-8.089 4.575c-3.786 0-6.906-2.332-8.36-5.315a2.5 2.5 0 0 1 1.734-3.542a2.504 2.504 0 0 1-2.06-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.946-.754-3.947-.805a2.5 2.5 0 1 1 .253-4.993c1.543.078 3.914.49 6.336 1.438q-.43-.467-.85-.863c-.98-.764-1.136-2.31-.372-3.29m3.32 12.419c-1.893 0-3.443.973-4.032 2.475a2.5 2.5 0 0 1-1.815 1.534a2.5 2.5 0 0 1 1.982 1.39c.714 1.467 2.205 2.272 3.864 2.272c1.901-.15 3.542-1.663 3.542-3.802c0-2.138-1.499-3.87-3.542-3.87");
}

.d0xayr3dz {
  stop-color: var(--svg-color--7e5d52, #7E5D52);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dd7t-y1vp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.02 13.248c1.488.511 4.445 2.626 4.37 6.994");
}

.dfypbomlg {
  stop-color: var(--svg-color--8b5f61, #8B5F61);
}

.dnrnmmbrl {
  stop-color: var(--svg-color--413330, #413330);
}

.dnxgkab9a {
  stop-color: var(--svg-color--694032, #694032);
  stop-opacity: 0;
}

.dp19-7b1f {
  stop-color: var(--svg-color--663955, #663955);
  stop-opacity: 0;
}

.e_pv8vb-f {
  stop-color: var(--svg-color--6c4e45, #6C4E45);
}

.e5xukvbnc {
  stop-color: var(--svg-color--6c4e45, #6C4E45);
  stop-opacity: 0;
}

.ef1pub4em {
  stop-color: var(--svg-color--977162, #977162);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gj8dnnbxp {
  stop-color: var(--svg-color--a38377, #A38377);
}

.hkz328bqo {
  stop-color: var(--svg-color--824877, #824877);
}

.hwahr-bmb {
  stop-color: var(--svg-color--ac847b, #AC847B);
  stop-opacity: 0;
}

.ih2u7_t8f {
  stop-color: var(--svg-color--966e60, #966E60);
  stop-opacity: 0;
}

.jh87cpzru {
  stop-color: var(--svg-color--84635a, #84635A);
}

.jht_zhawt {
  stop-color: var(--svg-color--70544d, #70544D);
  stop-opacity: 0;
}

.k173lu9mn {
  stop-color: var(--svg-color--75594e, #75594E);
}

.k8lf-zbxd {
  stop-color: var(--svg-color--a27d6f, #A27D6F);
  stop-opacity: 0;
}

.kasfw-b4p {
  d: path("M8.244 6.487a2.5 2.5 0 0 0-.253 4.993c.99.05 2.414.299 3.896.788a9.5 9.5 0 0 1 4.926-1.363c1.217 0 2.381.227 3.452.641a2.5 2.5 0 0 0-.288-.322C16.362 7.822 10.99 6.626 8.244 6.487");
}

.khtdutk0u {
  stop-color: var(--svg-color--6e4c3f, #6E4C3F);
}

.kz2xabbma {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M7.775 8.547c2.093.25 6.187 1.22 7.953 1.727");
}

.l6as6xbzq {
  d: path("M25.717 20.77c-1.317-8.847-6.973-9.15-8.348-9.504c2.875-1.844 7.155-.352 7.625 1.25c.906 3.094.994 6.713.723 8.255");
}

.luxj8_upm {
  stop-color: var(--svg-color--b98c81, #B98C81);
}

.msqjrkbsa {
  stop-color: var(--svg-color--694032, #694032);
}

.n046mbcil {
  stop-color: var(--svg-color--653d31, #653D31);
  stop-opacity: 0;
}

.n5i92-bxt {
  stop-color: var(--svg-color--562b21, #562B21);
}

.nc_7llbtt {
  fill-rule: evenodd;
  d: path("M23.643 26.051a9.4 9.4 0 0 1-6.958 3.052c-3.786 0-6.906-2.34-8.36-5.332a2.51 2.51 0 0 1 1.734-3.553a2.51 2.51 0 0 1-2.06-3.41a9.14 9.14 0 0 1 3.947-4.567l-.024-.008c1.437-.82 3.08-1.296 4.775-1.296c5.079 0 9.196 4.088 9.196 9.13c0 2.29-.849 4.382-2.25 5.984m-10.989-7.41c.59-1.507 2.139-2.483 4.031-2.483c2.043 0 3.542 1.736 3.542 3.881c0 2.146-1.641 3.663-3.542 3.813c-1.659 0-3.15-.806-3.864-2.277a2.5 2.5 0 0 0-1.982-1.396a2.5 2.5 0 0 0 1.815-1.538");
}

.nme1cfesl {
  stop-color: var(--svg-color--977162, #977162);
}

.nons3q-fd {
  stop-color: var(--svg-color--8f6758, #8F6758);
  stop-opacity: 0;
}

.ojt9yacts {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M11 21.94c.542 1.378 2.629 4.031 6.641 3.623");
}

.phw3o18-l {
  stop-color: var(--svg-color--663955, #663955);
}

.py95h14ou {
  stop-color: var(--svg-color--896350, #896350);
  stop-opacity: 0;
}

.q3w127o1w {
  stop-color: var(--svg-color--98715e, #98715E);
  stop-opacity: 0;
}

.r4n0bhb9j {
  d: path("M26.166 13.329c-.407-3.314-1.456-6.535-2.794-8.807a2.25 2.25 0 0 0-4.176 1.39c1.889 2.112 3.544 4.722 4.57 7.417z");
}

.rprohccev {
  stop-color: var(--svg-color--653d31, #653D31);
}

.rqd6f-bxg {
  stop-color: var(--svg-color--98715e, #98715E);
}

.rwu83tbfd {
  stop-color: var(--svg-color--765147, #765147);
}

.ry5i5sbis {
  stop-color: var(--svg-color--896350, #896350);
}

.t00zf_cht {
  stop-color: var(--svg-color--765147, #765147);
  stop-opacity: 0;
}

.t9ok82b3y {
  fill-rule: evenodd;
  d: path("M13.358 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.176-1.39c1.49 2.53 2.62 6.233 2.907 9.933l.011-.001l.015.278c.034.597.104 1.816.067 4.111c-.037 2.313-.674 4.143-1.606 5.678c-1.613 2.756-4.67 4.575-8.089 4.575c-3.786 0-6.906-2.332-8.36-5.315a2.5 2.5 0 0 1 1.734-3.542a2.504 2.504 0 0 1-2.06-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.946-.754-3.947-.805a2.5 2.5 0 1 1 .253-4.993c1.543.078 3.914.49 6.336 1.438q-.43-.467-.85-.863c-.98-.764-1.136-2.31-.372-3.29m3.32 12.419c-1.893 0-3.443.973-4.032 2.475a2.5 2.5 0 0 1-1.815 1.534a2.5 2.5 0 0 1 1.982 1.39c.714 1.467 2.205 2.272 3.864 2.272c1.901-.15 3.542-1.663 3.542-3.802c0-2.138-1.499-3.87-3.542-3.87");
}

.tdwmw7_4a {
  stop-color: var(--svg-color--413330, #413330);
  stop-opacity: 0;
}

.tdy7-m_fn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.586 18.068c1.188-3.406 5.094-5.062 7.469-4.687");
}

.tyk5u9bea {
  stop-color: var(--svg-color--562b21, #562B21);
  stop-opacity: 0;
}

.uleenob4d {
  stop-color: var(--svg-color--b98c81, #B98C81);
  stop-opacity: 0;
}

.uobifuudt {
  stop-color: var(--svg-color--6e4c3f, #6E4C3F);
  stop-opacity: 0;
}

.vc1buwnev {
  stop-color: var(--svg-color--8b5f61, #8B5F61);
  stop-opacity: 0;
}

.vf7g99b5q {
  stop-color: var(--svg-color--966e60, #966E60);
}

.w2cs_g5_a {
  stop-color: var(--svg-color--a38377, #A38377);
  stop-opacity: 0;
}

.wca7y5bhk {
  stop-color: var(--svg-color--824877, #824877);
  stop-opacity: 0;
}

.wwtloyb4r {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M26.166 13.329c-.407-3.314-1.456-6.535-2.794-8.807a2.25 2.25 0 0 0-4.176 1.39c1.889 2.112 3.544 4.722 4.57 7.417z");
}

.x9sbbz01j {
  fill: var(--svg-color--8f6758, #8F6758);
  d: path("M13.358 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.176-1.39c1.49 2.53 2.62 6.233 2.907 9.933l.011-.001l.015.278c.034.597.104 1.816.067 4.111c-.037 2.313-.674 4.143-1.606 5.678c-1.613 2.756-4.67 4.575-8.089 4.575c-3.786 0-6.906-2.332-8.36-5.315a2.5 2.5 0 0 1 1.734-3.542a2.504 2.504 0 0 1-2.06-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.946-.754-3.947-.805a2.5 2.5 0 1 1 .253-4.993c1.543.078 3.914.49 6.336 1.438q-.43-.467-.85-.863c-.98-.764-1.136-2.31-.372-3.29m3.32 12.419c-1.893 0-3.443.973-4.032 2.475a2.5 2.5 0 0 1-1.815 1.534a2.5 2.5 0 0 1 1.982 1.39c.714 1.467 2.205 2.272 3.864 2.272c1.901-.15 3.542-1.663 3.542-3.802c0-2.138-1.499-3.87-3.542-3.87");
}

.xni46r-cx {
  stop-color: var(--svg-color--7e5d52, #7E5D52);
  stop-opacity: 0;
}

.xokztdbiw {
  stop-color: var(--svg-color--8f6758, #8F6758);
}

.yeujlnb_f {
  stop-color: var(--svg-color--a58579, #A58579);
}

.ylx9ivbbn {
  stop-color: var(--svg-color--a58579, #A58579);
  stop-opacity: 0;
}

.z-0gueb0f {
  stop-color: var(--svg-color--70544d, #70544D);
}

</style>
