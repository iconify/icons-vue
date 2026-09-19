<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZV7nHf)"><path fill="url(#iPJag7N)" class="g8wq_wx5x"/><path fill="url(#iXCHDxc)" class="g8wq_wx5x"/><path fill="url(#iGiWK1c)" class="g8wq_wx5x"/></g><path fill="url(#itlxVuc)" class="g8wq_wx5x"/><path fill="url(#iXpD6ef)" class="g8wq_wx5x"/><path fill="url(#iBcW0fd)" class="g8wq_wx5x"/><g filter="url(#izuBCfe)"><path class="eyszd8umi"/></g><g filter="url(#il1haPd)"><path class="iqhredtnl"/></g><rect fill="url(#i57Msnd)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#ireSqgb)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#iNw8YMb)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#i5EvEQb)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#ixvPkBc)" transform="rotate(-90 6.896 21.013)" class="dmcp6rbjw"/><rect fill="url(#i4Pt07F)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#iO2PmJz)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#int3MFD)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#iPokJXs)" transform="rotate(-90 7.194 7.81)" class="ezcfr6bsl"/><rect fill="url(#if3STkc)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#ib5riBd)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#i6Nnyab)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#iwRfJld)" transform="rotate(-90 5.904 12.064)" class="dtv3nbcrv"/><rect fill="url(#i1DzIjb)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#iUd3Moe)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#iNuj1qQ)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><rect fill="url(#i5kkM9c)" transform="rotate(-90 5.949 16.486)" class="s434mcboj"/><defs><radialGradient id="iXCHDxc" cx="0" cy="0" r="1" gradientTransform="rotate(90.785 -3.306 18.257)scale(6.84439 2.83792)" gradientUnits="userSpaceOnUse"><stop class="pujz33b0z"/><stop offset="1" class="mpxi01hly"/></radialGradient><radialGradient id="iGiWK1c" cx="0" cy="0" r="1" gradientTransform="rotate(-63.938 22.844 -6.436)scale(7.24207 13.4771)" gradientUnits="userSpaceOnUse"><stop class="e19yjxfqk"/><stop offset="1" class="s02hbcckd"/></radialGradient><radialGradient id="itlxVuc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.09874 3.46893 -3.9808 -6.99866 24.688 7.567)" gradientUnits="userSpaceOnUse"><stop class="xk2cvxnjj"/><stop offset="1" class="xs_ny18pa"/></radialGradient><radialGradient id="iXpD6ef" cx="0" cy="0" r="1" gradientTransform="matrix(4.64396 0 0 9.96517 20.089 26.084)" gradientUnits="userSpaceOnUse"><stop class="fu21nqb1g"/><stop offset="1" class="r9udekbww"/></radialGradient><radialGradient id="iBcW0fd" cx="0" cy="0" r="1" gradientTransform="scale(12.9389 20.0228)rotate(90 .42 .93)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="s1o2h4bjd"/><stop offset="1" class="lgmy-bbit"/></radialGradient><radialGradient id="iNw8YMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.58086 2.00356 0 10.449 28.655)" gradientUnits="userSpaceOnUse"><stop class="ww497ohhe"/><stop offset="1" class="v8tstobea"/></radialGradient><radialGradient id="i5EvEQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.17279 -7.31561 8.00204 -.189 9.788 28.327)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="b0ikyrb8a"/><stop offset="1" class="j6a6ytb2p"/></radialGradient><radialGradient id="ixvPkBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9313 0 0 -4.89838 11.409 24.948)" gradientUnits="userSpaceOnUse"><stop class="na9_iabpf"/><stop offset="1" class="i89-9hbuo"/></radialGradient><radialGradient id="iO2PmJz" cx="0" cy="0" r="1" gradientTransform="matrix(1.06838 0 0 4.40184 8.078 12.125)" gradientUnits="userSpaceOnUse"><stop class="clh82toxv"/><stop offset="1" class="cj65ock7u"/></radialGradient><radialGradient id="int3MFD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78495 2.38236 0 10.98 14.998)" gradientUnits="userSpaceOnUse"><stop class="memfomb_s"/><stop offset="1" class="jcp_ehm4o"/></radialGradient><radialGradient id="iPokJXs" cx="0" cy="0" r="1" gradientTransform="matrix(-.16817 -7.16786 7.78679 -.18269 10.01 14.978)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="w-n6dkbve"/><stop offset="1" class="sd5fm_b6b"/></radialGradient><radialGradient id="ib5riBd" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 0 0 5.04687 6.835 17.011)" gradientUnits="userSpaceOnUse"><stop class="x_6h1dbbe"/><stop offset="1" class="j1dthjb3y"/></radialGradient><radialGradient id="i6Nnyab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.68226 2.10732 0 9.43 20.227)" gradientUnits="userSpaceOnUse"><stop class="c74ekhq1u"/><stop offset="1" class="xvb59v0yy"/></radialGradient><radialGradient id="iwRfJld" cx="0" cy="0" r="1" gradientTransform="matrix(-.17705 -8.21822 8.20018 -.17667 8.867 20.282)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="hfsmjab7x"/><stop offset="1" class="q7mwecbnw"/></radialGradient><radialGradient id="iUd3Moe" cx="0" cy="0" r="1" gradientTransform="matrix(2.38035 0 0 7.9345 5.694 20.031)" gradientUnits="userSpaceOnUse"><stop class="w107uhb4g"/><stop offset="1" class="rbp3d91jy"/></radialGradient><radialGradient id="iNuj1qQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6702 2.06121 0 9.398 24.613)" gradientUnits="userSpaceOnUse"><stop class="ln6e3rbao"/><stop offset="1" class="jhrd71x6s"/></radialGradient><radialGradient id="i5kkM9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.17323 -8.18127 8.02085 -.16983 8.848 24.669)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="df4sbdb2p"/><stop offset="1" class="op6049lep"/></radialGradient><linearGradient id="iPJag7N" x1="26.78" x2="12.286" y1="8.105" y2="29.819" gradientUnits="userSpaceOnUse"><stop class="wyry-tbnu"/><stop offset="1" class="qg4xrrbcq"/></linearGradient><linearGradient id="i57Msnd" x1="9.788" x2="9.788" y1="21.013" y2="30" gradientUnits="userSpaceOnUse"><stop class="i0pm_-1gg"/><stop offset="1" class="m905_hpdm"/></linearGradient><linearGradient id="ireSqgb" x1="6.543" x2="8.42" y1="25.506" y2="25.506" gradientUnits="userSpaceOnUse"><stop class="rr1h57bjb"/><stop offset="1" class="gb6x77o8m"/></linearGradient><linearGradient id="i4Pt07F" x1="8.538" x2="10.883" y1="8.718" y2="15.823" gradientUnits="userSpaceOnUse"><stop class="hg3hkfbko"/><stop offset="1" class="swjehmaxb"/></linearGradient><linearGradient id="if3STkc" x1="7.319" x2="10.194" y1="13.105" y2="21.105" gradientUnits="userSpaceOnUse"><stop class="bnk7vmbpn"/><stop offset="1" class="q_go36w8p"/></linearGradient><linearGradient id="i1DzIjb" x1="8.847" x2="8.847" y1="16.486" y2="25.515" gradientUnits="userSpaceOnUse"><stop class="rpyibbqyd"/><stop offset="1" class="r1stp4bcw"/></linearGradient><filter id="iZV7nHf" width="18.933" height="27.637" x="9.373" y="2.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.556863 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3070"/></filter><filter id="izuBCfe" width="12.677" height="20.87" x="5.131" y="1.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3070" stdDeviation="1"/></filter><filter id="il1haPd" width="12.088" height="5.26" x="12.396" y="15.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3070" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:thumbs-down-medium" /></template>
<style>
.b0ikyrb8a {
  stop-color: var(--svg-color--9c766a, #9C766A);
  stop-opacity: 0;
}

.bnk7vmbpn {
  stop-color: var(--svg-color--8f6d5b, #8F6D5B);
}

.c74ekhq1u {
  stop-color: var(--svg-color--d0a790, #D0A790);
}

.cj65ock7u {
  stop-color: var(--svg-color--7e5a43, #7E5A43);
  stop-opacity: 0;
}

.clh82toxv {
  stop-color: var(--svg-color--7e5a43, #7E5A43);
}

.df4sbdb2p {
  stop-color: var(--svg-color--9c7769, #9C7769);
  stop-opacity: 0;
}

.dmcp6rbjw {
  width: 5.784px;
  height: 8.988px;
  x: 6.896px;
  y: 21.013px;
  rx: 2.892px;
}

.dtv3nbcrv {
  width: 5.927px;
  height: 10.097px;
  x: 5.904px;
  y: 12.064px;
  rx: 2.91px;
}

.e19yjxfqk {
  stop-color: var(--svg-color--a67079, #A67079);
}

.eyszd8umi {
  fill: var(--svg-color--8f6954, #8F6954);
  d: path("M8.24 5.919c0 .468.122.907.336 1.283c-.855.428-1.445 1.34-1.445 2.394c0 .82.356 1.554.917 2.04a2.64 2.64 0 0 0-.878 1.98c0 1.04.585 1.936 1.431 2.35a2.65 2.65 0 0 0-.618 1.71c0 1.431 1.113 2.591 2.486 2.591h2.753c1.373 0 2.485-1.16 2.485-2.59a2.63 2.63 0 0 0-.89-1.988a2.63 2.63 0 0 0 .99-2.073c0-.803-.349-1.52-.897-1.996c.55-.487.898-1.213.898-2.024c0-.728-.281-1.387-.736-1.866c.454-.459.736-1.1.736-1.811c0-1.393-1.083-2.521-2.419-2.521h-2.73c-1.337 0-2.42 1.128-2.42 2.52");
}

.ezcfr6bsl {
  width: 5.629px;
  height: 8.806px;
  x: 7.194px;
  y: 7.81px;
  rx: 2.814px;
}

.ft5dv1b6b {
  fill: none;
}

.fu21nqb1g {
  stop-color: var(--svg-color--cb9c89, #CB9C89);
}

.g8wq_wx5x {
  d: path("M20.5 26.55a3.268 3.268 0 0 1-6.536 0v-3.76q-.001-.482.072-.96a6 6 0 0 0 .047-.35c.036-.369-.008-.85-.258-1.173l.598-.576a9.28 9.28 0 0 1-5.05-8.275c0-.979.15-1.922.43-2.808l.99-6.466h8.051v.002c4.973.107 8.962 3.35 8.962 9.272c0 3.481-1.667 6.284-4.189 7.864l.006.005c-.172.12-.374.24-.591.371l-.002.001c-.715.429-1.59.953-2.05 1.81c-.4.743-.478 1.949-.478 2.508l-.002-.001z");
}

.gb6x77o8m {
  stop-color: var(--svg-color--94567f, #94567F);
  stop-opacity: 0;
}

.hfsmjab7x {
  stop-color: var(--svg-color--9b7869, #9B7869);
  stop-opacity: 0;
}

.hg3hkfbko {
  stop-color: var(--svg-color--8f6b5c, #8F6B5C);
}

.i0pm_-1gg {
  stop-color: var(--svg-color--8e665f, #8E665F);
}

.i89-9hbuo {
  stop-color: var(--svg-color--784547, #784547);
  stop-opacity: 0;
}

.iqhredtnl {
  fill: var(--svg-color--a06971, #A06971);
  d: path("M22.984 18.984c-3.643-2.241-7.3-.668-8.247 0l-.84-1.082c5.38-2.562 8.246-.36 9.087 1.081");
}

.j1dthjb3y {
  stop-color: var(--svg-color--936863, #936863);
  stop-opacity: 0;
}

.j6a6ytb2p {
  stop-color: var(--svg-color--9c766a, #9C766A);
}

.jcp_ehm4o {
  stop-color: var(--svg-color--cca48b, #CCA48B);
  stop-opacity: 0;
}

.jhrd71x6s {
  stop-color: var(--svg-color--cfa690, #CFA690);
  stop-opacity: 0;
}

.lgmy-bbit {
  stop-color: var(--svg-color--995880, #995880);
}

.ln6e3rbao {
  stop-color: var(--svg-color--cfa690, #CFA690);
}

.m905_hpdm {
  stop-color: var(--svg-color--bc9173, #BC9173);
}

.memfomb_s {
  stop-color: var(--svg-color--cca48b, #CCA48B);
}

.mpxi01hly {
  stop-color: var(--svg-color--865754, #865754);
  stop-opacity: 0;
}

.na9_iabpf {
  stop-color: var(--svg-color--784547, #784547);
}

.op6049lep {
  stop-color: var(--svg-color--9c7769, #9C7769);
}

.pujz33b0z {
  stop-color: var(--svg-color--865754, #865754);
}

.q_go36w8p {
  stop-color: var(--svg-color--ba9373, #BA9373);
}

.q7mwecbnw {
  stop-color: var(--svg-color--9b7869, #9B7869);
}

.qg4xrrbcq {
  stop-color: var(--svg-color--9c6e6a, #9C6E6A);
}

.r1stp4bcw {
  stop-color: var(--svg-color--be9575, #BE9575);
}

.r9udekbww {
  stop-color: var(--svg-color--cb9c89, #CB9C89);
  stop-opacity: 0;
}

.rbp3d91jy {
  stop-color: var(--svg-color--8c5368, #8C5368);
  stop-opacity: 0;
}

.rpyibbqyd {
  stop-color: var(--svg-color--906e5c, #906E5C);
}

.rr1h57bjb {
  stop-color: var(--svg-color--94567f, #94567F);
}

.s02hbcckd {
  stop-color: var(--svg-color--a67079, #A67079);
  stop-opacity: 0;
}

.s1o2h4bjd {
  stop-color: var(--svg-color--995880, #995880);
  stop-opacity: 0;
}

.s434mcboj {
  width: 5.797px;
  height: 10.051px;
  x: 5.949px;
  y: 16.486px;
  rx: 2.899px;
}

.sd5fm_b6b {
  stop-color: var(--svg-color--926f5d, #926F5D);
}

.swjehmaxb {
  stop-color: var(--svg-color--bf9a7c, #BF9A7C);
}

.v8tstobea {
  stop-color: var(--svg-color--cba18d, #CBA18D);
  stop-opacity: 0;
}

.w-n6dkbve {
  stop-color: var(--svg-color--926f5d, #926F5D);
  stop-opacity: 0;
}

.w107uhb4g {
  stop-color: var(--svg-color--8c5368, #8C5368);
}

.ww497ohhe {
  stop-color: var(--svg-color--cba18d, #CBA18D);
}

.wyry-tbnu {
  stop-color: var(--svg-color--bf9779, #BF9779);
}

.x_6h1dbbe {
  stop-color: var(--svg-color--936863, #936863);
}

.xk2cvxnjj {
  stop-color: var(--svg-color--d9af94, #D9AF94);
}

.xs_ny18pa {
  stop-color: var(--svg-color--cea68d, #CEA68D);
  stop-opacity: 0;
}

.xvb59v0yy {
  stop-color: var(--svg-color--d0a790, #D0A790);
  stop-opacity: 0;
}

</style>
