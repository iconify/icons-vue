<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihBrcOc)"><path fill="url(#iIfHegb)" class="z5gkcf-av"/></g><path fill="url(#iZDAgBZ)" class="z5gkcf-av"/><path fill="url(#i7aucWl)" class="z5gkcf-av"/><g filter="url(#iAimafd)"><rect fill="url(#iDX3WUb)" class="kgq1yxb-w"/></g><g filter="url(#iX74Cct)"><path class="aic4fwr8p"/></g><rect fill="url(#i7A5Aae)" class="yqrsv_hxq"/><rect fill="url(#i4k3Gic)" class="yqrsv_hxq"/><rect fill="url(#iMkarNT)" class="yqrsv_hxq"/><rect fill="url(#isuTUKb)" class="yqrsv_hxq"/><path fill="url(#ipms2ke)" class="irgyn1bud"/><path fill="url(#iWF73Id)" class="irgyn1bud"/><path fill="url(#ib95tcb)" class="irgyn1bud"/><path fill="url(#iXAa8YC)" class="irgyn1bud"/><rect class="q1vclbzpe"/><rect fill="url(#iixP3Cd)" class="tcvr7tulc"/><rect fill="url(#iq5tv9b)" class="tcvr7tulc"/><rect fill="url(#iHF1wvd)" class="tcvr7tulc"/><path fill="url(#iYchLzS)" class="e599lnq0o"/><path fill="url(#ic7yXLV)" class="e599lnq0o"/><path fill="url(#iWoVTUb)" class="e599lnq0o"/><path fill="url(#ilCp0qe)" class="e599lnq0o"/><path fill="url(#iVIdc5d)" class="c-hm1bbbt"/><path fill="url(#iwxFE6c)" class="c-hm1bbbt"/><path fill="url(#i1EXWsb)" class="c-hm1bbbt"/><path fill="url(#innJFIe)" class="c-hm1bbbt"/><path fill="url(#iF0sNpc)" class="c-hm1bbbt"/><path fill="url(#iqab0Zc)" class="c-hm1bbbt"/><g filter="url(#iPA8Sud)"><path stroke="url(#iL9xLFc)" class="tgo5q5srk"/></g><defs><radialGradient id="iZDAgBZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0399 -20.6277 0 16 18.075)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="wsjm7obid"/><stop offset="1" class="rp0g791ql"/></radialGradient><radialGradient id="i7aucWl" cx="0" cy="0" r="1" gradientTransform="rotate(164.074 7.028 9.94)scale(13.9404 19.1941)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="ll8qulb7z"/><stop offset="1" class="gar93mbmo"/></radialGradient><radialGradient id="i7A5Aae" cx="0" cy="0" r="1" gradientTransform="matrix(-3.83217 0 0 -8.73643 8.233 10.438)" gradientUnits="userSpaceOnUse"><stop class="swm3hl7jc"/><stop offset=".582" class="ehz5zqbke"/><stop offset="1" class="xgdzadbun"/></radialGradient><radialGradient id="i4k3Gic" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.04945 -6.98425 0 6.885 7.064)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="geab5obof"/><stop offset="1" class="fmc0sdbka"/></radialGradient><radialGradient id="iMkarNT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67954 0 0 -10.0187 9.663 10.126)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="wybcglblv"/><stop offset="1" class="zfirxjb1t"/></radialGradient><radialGradient id="isuTUKb" cx="0" cy="0" r="1" gradientTransform="matrix(1.22807 1.63545 -3.19277 2.39747 4.202 5.531)" gradientUnits="userSpaceOnUse"><stop class="u5ndy96ka"/><stop offset="1" class="df8t-ybjo"/></radialGradient><radialGradient id="ipms2ke" cx="0" cy="0" r="1" gradientTransform="matrix(-3.83217 0 0 -10.0007 13.49 9.762)" gradientUnits="userSpaceOnUse"><stop class="nmarq1ici"/><stop offset=".582" class="ve8l4db9j"/><stop offset="1" class="nhlbqnvga"/></radialGradient><radialGradient id="iWF73Id" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.97327 -6.80156 0 12.142 5.9)" gradientUnits="userSpaceOnUse"><stop offset=".615" class="geab5obof"/><stop offset=".991" class="fmc0sdbka"/></radialGradient><radialGradient id="ib95tcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21564 0 0 -8.30086 15.09 9.404)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="i5q-apyrb"/><stop offset="1" class="lav7enb9o"/></radialGradient><radialGradient id="iXAa8YC" cx="0" cy="0" r="1" gradientTransform="rotate(56.736 .892 10.831)scale(2.23897 4.17494)" gradientUnits="userSpaceOnUse"><stop class="u5ndy96ka"/><stop offset="1" class="df8t-ybjo"/></radialGradient><radialGradient id="iixP3Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.50737 0 0 -12.255 25.925 7.517)" gradientUnits="userSpaceOnUse"><stop class="z5hru1gqn"/><stop offset=".582" class="ve8l4db9j"/><stop offset="1" class="nhlbqnvga"/></radialGradient><radialGradient id="iq5tv9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.46343 0 0 10.4111 20.598 8.548)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="i5q-apyrb"/><stop offset="1" class="lav7enb9o"/></radialGradient><radialGradient id="iHF1wvd" cx="0" cy="0" r="1" gradientTransform="rotate(57.804 8.094 21.228)scale(2.30488 4.22527)" gradientUnits="userSpaceOnUse"><stop class="u5ndy96ka"/><stop offset="1" class="df8t-ybjo"/></radialGradient><radialGradient id="iYchLzS" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91713 0 0 -14.6921 20.012 8.512)" gradientUnits="userSpaceOnUse"><stop class="eesdbufdu"/><stop offset=".582" class="ve8l4db9j"/><stop offset="1" class="nhlbqnvga"/></radialGradient><radialGradient id="ic7yXLV" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1233 -6.70183 0 18.125 4.997)" gradientUnits="userSpaceOnUse"><stop offset=".615" class="geab5obof"/><stop offset=".991" class="fmc0sdbka"/></radialGradient><radialGradient id="iWoVTUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29989 0 0 -10.1627 21.9 8.951)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="k_zd3bbsf"/><stop offset="1" class="e47cs2-pf"/></radialGradient><radialGradient id="ilCp0qe" cx="0" cy="0" r="1" gradientTransform="rotate(60.19 5.138 14.865)scale(2.43413 4.26884)" gradientUnits="userSpaceOnUse"><stop class="u5ndy96ka"/><stop offset="1" class="df8t-ybjo"/></radialGradient><radialGradient id="iVIdc5d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30518 5.45366 -11.83567 -2.83254 23.77 10.987)" gradientUnits="userSpaceOnUse"><stop class="udixtobuq"/><stop offset="1" class="xl4e6ub5o"/></radialGradient><radialGradient id="iwxFE6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.77179 -6.41638 0 19.836 17.548)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="roch1zbeh"/><stop offset="1" class="g3ksnjbko"/></radialGradient><radialGradient id="i1EXWsb" cx="0" cy="0" r="1" gradientTransform="matrix(2.68404 -3.56818 5.7103 4.29537 23.33 21.526)" gradientUnits="userSpaceOnUse"><stop offset=".386" class="qaqtxwb7y"/><stop offset="1" class="bdf8n5bly"/></radialGradient><radialGradient id="innJFIe" cx="0" cy="0" r="1" gradientTransform="matrix(3.74677 0 0 5.4251 14.24 13.267)" gradientUnits="userSpaceOnUse"><stop class="ys8plenby"/><stop offset="1" class="l-3jxvlgd"/></radialGradient><radialGradient id="iF0sNpc" cx="0" cy="0" r="1" gradientTransform="matrix(2.9832 -2.51707 2.60763 3.09052 16.171 16.72)" gradientUnits="userSpaceOnUse"><stop class="ucphdj0gw"/><stop offset="1" class="uodovhfvh"/></radialGradient><radialGradient id="iqab0Zc" cx="0" cy="0" r="1" gradientTransform="matrix(1.14015 -.98439 1.64762 1.90833 15.307 15.661)" gradientUnits="userSpaceOnUse"><stop class="j9ezdfd_y"/><stop offset="1" class="lx9thna-i"/></radialGradient><filter id="ihBrcOc" width="25.02" height="20.828" x="3.49" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.576471 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3164"/></filter><filter id="iAimafd" width="18.678" height="12.194" x="7.28" y="9.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3164" stdDeviation="1.5"/></filter><filter id="iX74Cct" width="24.653" height="14.935" x="3.21" y="3.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3164" stdDeviation="1"/></filter><filter id="iPA8Sud" width="12.76" height="8.553" x="17.466" y="9.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3164" stdDeviation=".85"/></filter><linearGradient id="iIfHegb" x1="15.541" x2="29.355" y1="20.604" y2="20.604" gradientUnits="userSpaceOnUse"><stop class="qvu9h2lyl"/><stop offset="1" class="swr2e6x5l"/></linearGradient><linearGradient id="iDX3WUb" x1="20.393" x2="8.571" y1="17.241" y2="21.196" gradientUnits="userSpaceOnUse"><stop class="ylmdbwpce"/><stop offset="1" class="nsdgl-bjf"/></linearGradient><linearGradient id="iL9xLFc" x1="20.166" x2="31.468" y1="12.671" y2="16.361" gradientUnits="userSpaceOnUse"><stop class="zqk-m3e9a"/><stop offset="1" class="shn-mzogu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-fist-medium-light" /></template>
<style>
.aic4fwr8p {
  fill: var(--svg-color--844843, #844843);
  d: path("M15.024 14.283c-.504.868-1.422 1.472-2.47 1.472c-.93 0-1.757-.314-2.283-.987a2.882 2.882 0 0 1-5.06-1.886v-2.704a2.882 2.882 0 0 1 4.61-2.306c.383-1.244 1.462-1.81 2.733-1.81c.936 0 1.768.447 2.294 1.138c.26-1.272 1.408-2.135 2.785-2.135a2.84 2.84 0 0 1 2.674 1.884a2.882 2.882 0 0 1 5.556 1.074v4.335a2.882 2.882 0 0 1-5.44 1.327a2.84 2.84 0 0 1-5.4.598");
}

.bdf8n5bly {
  stop-color: var(--svg-color--dba38e, #DBA38E);
  stop-opacity: 0;
}

.c-hm1bbbt {
  d: path("M18.339 9.797c-1.965 0-3.559 1.507-3.559 3.365s1.594 3.365 3.559 3.365h2.602c1.168 0 2.115.896 2.115 2v2.999h.2c3.464 0 5.254-3.022 5.254-5.766c0-3.293-2.823-5.963-6.306-5.963z");
}

.df8t-ybjo {
  stop-color: var(--svg-color--c69b7d, #C69B7D);
  stop-opacity: 0;
}

.e47cs2-pf {
  stop-color: var(--svg-color--d69f76, #D69F76);
  stop-opacity: 0;
}

.e599lnq0o {
  d: path("M14.78 5.675c0-1.847 1.498-3.166 3.345-3.166a3.345 3.345 0 0 1 3.346 3.346v6.192a3.345 3.345 0 0 1-6.69 0z");
}

.eesdbufdu {
  stop-color: var(--svg-color--ffd1a9, #FFD1A9);
}

.ehz5zqbke {
  stop-color: var(--svg-color--d6a481, #D6A481);
}

.fmc0sdbka {
  stop-color: var(--svg-color--b9777a, #B9777A);
}

.ft5dv1b6b {
  fill: none;
}

.g3ksnjbko {
  stop-color: var(--svg-color--b37079, #B37079);
  stop-opacity: 0;
}

.gar93mbmo {
  stop-color: var(--svg-color--e7aa93, #E7AA93);
}

.geab5obof {
  stop-color: var(--svg-color--b9777a, #B9777A);
  stop-opacity: 0;
}

.i5q-apyrb {
  stop-color: var(--svg-color--b27b51, #B27B51);
}

.irgyn1bud {
  d: path("M8.747 7.09c0-2.35 1.52-3.396 3.395-3.396a3.395 3.395 0 0 1 3.395 3.395v4.509c0 1.875-1.52 3.516-3.395 3.516s-3.395-1.085-3.395-3.516z");
}

.j9ezdfd_y {
  stop-color: var(--svg-color--c88c7d, #C88C7D);
}

.k_zd3bbsf {
  stop-color: var(--svg-color--d69f76, #D69F76);
}

.kgq1yxb-w {
  width: 12.678px;
  height: 6.195px;
  x: 10.28px;
  y: 12.903px;
  rx: 3.097px;
}

.l-3jxvlgd {
  stop-color: var(--svg-color--cb947b, #CB947B);
  stop-opacity: 0;
}

.lav7enb9o {
  stop-color: var(--svg-color--b27b51, #B27B51);
  stop-opacity: 0;
}

.ll8qulb7z {
  stop-color: var(--svg-color--dc9f88, #DC9F88);
  stop-opacity: 0;
}

.lx9thna-i {
  stop-color: var(--svg-color--c88c7d, #C88C7D);
  stop-opacity: 0;
}

.nhlbqnvga {
  stop-color: var(--svg-color--c59071, #C59071);
}

.nmarq1ici {
  stop-color: var(--svg-color--f3c09f, #F3C09F);
}

.nsdgl-bjf {
  stop-color: var(--svg-color--9c5f55, #9C5F55);
  stop-opacity: 0;
}

.q1vclbzpe {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  fill: var(--svg-color--7dde5b, #7DDE5B);
  fill-opacity: var(--svg-fill-opacity--0-55, 0.55);
  rx: 3.395px;
}

.qaqtxwb7y {
  stop-color: var(--svg-color--dba38e, #DBA38E);
}

.qvu9h2lyl {
  stop-color: var(--svg-color--cc9580, #CC9580);
}

.roch1zbeh {
  stop-color: var(--svg-color--b37079, #B37079);
}

.rp0g791ql {
  stop-color: var(--svg-color--b46d8c, #B46D8C);
}

.shn-mzogu {
  stop-color: var(--svg-color--fcc8a6, #FCC8A6);
  stop-opacity: 0;
}

.swm3hl7jc {
  stop-color: var(--svg-color--e6b499, #E6B499);
}

.swr2e6x5l {
  stop-color: var(--svg-color--e4ab96, #E4AB96);
}

.tcvr7tulc {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  rx: 3.395px;
}

.tgo5q5srk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.166 12.519h2.14c3.187-.132 4.706 1.01 5.22 3.142");
}

.u5ndy96ka {
  stop-color: var(--svg-color--c69b7d, #C69B7D);
}

.ucphdj0gw {
  stop-color: var(--svg-color--b5727c, #B5727C);
}

.udixtobuq {
  stop-color: var(--svg-color--edbc91, #EDBC91);
}

.uodovhfvh {
  stop-color: var(--svg-color--b5727c, #B5727C);
  stop-opacity: 0;
}

.ve8l4db9j {
  stop-color: var(--svg-color--e0ae89, #E0AE89);
}

.wsjm7obid {
  stop-color: var(--svg-color--b46d8c, #B46D8C);
  stop-opacity: 0;
}

.wybcglblv {
  stop-color: var(--svg-color--b98863, #B98863);
}

.xgdzadbun {
  stop-color: var(--svg-color--c29275, #C29275);
}

.xl4e6ub5o {
  stop-color: var(--svg-color--dda293, #DDA293);
}

.ylmdbwpce {
  stop-color: var(--svg-color--9c5f55, #9C5F55);
}

.yqrsv_hxq {
  width: 6.79px;
  height: 9.976px;
  x: 3.49px;
  y: 5.138px;
  rx: 3.395px;
}

.ys8plenby {
  stop-color: var(--svg-color--cb947b, #CB947B);
}

.z5gkcf-av {
  d: path("M27.823 9.479H3.49v9.328c0 6.351 5.149 11.5 11.5 11.5h1.333c2.153 0 4.168-.592 5.89-1.621l.005.018c2.518-1.454 5.089-4.099 5.904-7.358c.83-3.325.134-5.707-.3-6.552z");
}

.z5hru1gqn {
  stop-color: var(--svg-color--ffd2a9, #FFD2A9);
}

.zfirxjb1t {
  stop-color: var(--svg-color--b98863, #B98863);
  stop-opacity: 0;
}

.zqk-m3e9a {
  stop-color: var(--svg-color--fcc8a6, #FCC8A6);
}

</style>
