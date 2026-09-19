<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAco9Yc)" class="vbq0404qf"/><path fill="url(#ipDs6zO)" class="vbq0404qf"/><path fill="url(#ioE5UPd)" class="vbq0404qf"/><path fill="url(#iPZPvzb)" class="vbq0404qf"/><path fill="url(#iO0V2Jb)" class="vbq0404qf"/><path fill="url(#iS16GFb)" class="vbq0404qf"/><path fill="url(#ixXVkOb)" class="vbq0404qf"/><path fill="url(#iByFJdW)" class="vbq0404qf"/><path fill="url(#iCD8RUd)" class="vbq0404qf"/><path fill="url(#iAgjKMe)" class="vbq0404qf"/><g filter="url(#iUQLQne)"><path fill="url(#ivJcuad)" class="ho17x8bec"/><path fill="url(#iFPFIRb)" class="ho17x8bec"/><path fill="url(#ipIKkJc)" class="ho17x8bec"/></g><path fill="url(#iMjMWBd)" class="bb9t61_hc"/><path fill="url(#ilM2a2d)" class="bb9t61_hc"/><g filter="url(#ijuS3ac)"><path fill="url(#iO9yc5b)" class="ei7e82vjx"/><path fill="url(#iN6cbhc)" class="ei7e82vjx"/><path fill="url(#i1qHKsb)" class="ei7e82vjx"/></g><path fill="url(#iyDTWQb)" class="ei7e82vjx"/><path fill="url(#iMB0ESd)" class="ei7e82vjx"/><path fill="url(#iur29te)" class="ei7e82vjx"/><path fill="url(#isRH7db)" class="ei7e82vjx"/><g filter="url(#iaNRLws)"><path class="hd6-_5ncw"/></g><defs><radialGradient id="ipDs6zO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.54374 1.38245 -1.21975 -1.36206 11.526 6.887)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="q3m8m7bhy"/><stop offset="1" class="vxrp39aul"/></radialGradient><radialGradient id="ioE5UPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.24421 3.05044 -2.69144 1.09778 6.134 6.232)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="uhy_-rb7u"/><stop offset="1" class="gsrhrkoli"/></radialGradient><radialGradient id="iPZPvzb" cx="0" cy="0" r="1" gradientTransform="rotate(-164.745 8.114 3.65)scale(1.31353 1.81876)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="iO0V2Jb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09672 1.01382 -.74878 -1.54857 17.632 11.218)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="iS16GFb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.58058 -.29954 .1688 -1.45425 18.139 15.158)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="ixXVkOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.69616 -1.6359 1.576 1.63405 15.811 18.177)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="iByFJdW" cx="0" cy="0" r="1" gradientTransform="rotate(-127.747 6.767 7.613)scale(1.80662 1.74046)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="iCD8RUd" cx="0" cy="0" r="1" gradientTransform="matrix(1.65894 .78339 -.94684 2.00507 2.425 11.518)" gradientUnits="userSpaceOnUse"><stop class="mulvig9sp"/><stop offset="1" class="a_xm9geyk"/></radialGradient><radialGradient id="iAgjKMe" cx="0" cy="0" r="1" gradientTransform="rotate(-142.487 10.218 8.125)scale(2.13896 2.01793)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="rwhrj1bde"/><stop offset="1" class="tzt2apygr"/></radialGradient><radialGradient id="ivJcuad" cx="0" cy="0" r="1" gradientTransform="matrix(-4.89327 9.3049 -11.49069 -6.04273 13.452 10.468)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="mlwsi7b0o"/><stop offset="1" class="hemkrl1wk"/><stop offset="1" class="j756vz6_d"/></radialGradient><radialGradient id="iFPFIRb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.83524 -2.32633 1.9641 -2.39376 8.014 17.273)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="aksdkybif"/><stop offset="1" class="chsd9qafy"/></radialGradient><radialGradient id="ipIKkJc" cx="0" cy="0" r="1" gradientTransform="matrix(-12.28597 2.54453 -2.14833 -10.37297 14.92 12.875)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="chsd9qafy"/><stop offset="1" class="aksdkybif"/></radialGradient><radialGradient id="iMjMWBd" cx="0" cy="0" r="1" gradientTransform="rotate(176.658 9.754 6.62)scale(13.419)" gradientUnits="userSpaceOnUse"><stop offset=".211" class="uu8s2_d7p"/><stop offset="1" class="vi4gafj3v"/></radialGradient><radialGradient id="ilM2a2d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5423 -4.88912 6.70252 -3.48525 13.717 18.135)" gradientUnits="userSpaceOnUse"><stop class="ktb62eb8s"/><stop offset="1" class="lhdtcbcje"/></radialGradient><radialGradient id="i1qHKsb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99177 -12.19105 12.79662 -7.33908 20.904 29.136)" gradientUnits="userSpaceOnUse"><stop class="xcfalibap"/><stop offset="1" class="cznea_lps"/></radialGradient><radialGradient id="iyDTWQb" cx="0" cy="0" r="1" gradientTransform="rotate(143.827 10.193 13.36)scale(12.4671 13.3735)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="qobktdb-h"/><stop offset="1" class="obuie9bnj"/></radialGradient><radialGradient id="iMB0ESd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53107 3.95344 -4.1426 -5.79573 8.706 22.378)" gradientUnits="userSpaceOnUse"><stop class="qobktdb-h"/><stop offset="1" class="obuie9bnj"/></radialGradient><radialGradient id="iur29te" cx="0" cy="0" r="1" gradientTransform="matrix(-23.06326 5.47148 -4.30897 -18.16307 25.154 20.528)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="m_t75sbfg"/><stop offset="1" class="gh040h5xh"/></radialGradient><radialGradient id="isRH7db" cx="0" cy="0" r="1" gradientTransform="matrix(5.29375 -6.3716 8.79294 7.30549 5.711 31.012)" gradientUnits="userSpaceOnUse"><stop class="z1aynhbjt"/><stop offset="1" class="py52bpbbf"/></radialGradient><linearGradient id="iAco9Yc" x1="14.684" x2="6.266" y1="8.767" y2="19.508" gradientUnits="userSpaceOnUse"><stop class="s91ts3bpo"/><stop offset="1" class="uc7451bcz"/></linearGradient><linearGradient id="iO9yc5b" x1="16" x2="16" y1="12.116" y2="30" gradientUnits="userSpaceOnUse"><stop class="dlmz6ebuq"/><stop offset="1" class="bntogl9mp"/></linearGradient><linearGradient id="iN6cbhc" x1="18.842" x2="18.842" y1="29.038" y2="21.574" gradientUnits="userSpaceOnUse"><stop class="xx8tv_e5i"/><stop offset="1" class="h1bfoacex"/></linearGradient><filter id="iUQLQne" width="12.383" height="12.383" x="3.617" y="7.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.47451 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_15105"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_15105" result="shape"/></filter><filter id="ijuS3ac" width="27.819" height="18.884" x="2.091" y="11.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.784314 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15105"/></filter><filter id="iaNRLws" width="7.586" height="5.518" x="11.114" y="24.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15105" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sun-behind-large-cloud" /></template>
<style>
.a_xm9geyk {
  stop-color: var(--svg-color--f0851d, #F0851D);
  stop-opacity: 0;
}

.aksdkybif {
  stop-color: var(--svg-color--dca225, #DCA225);
}

.bb9t61_hc {
  d: path("M14.484 24.388a7.358 7.358 0 1 0 0-14.716a7.358 7.358 0 0 0 0 14.716");
}

.bntogl9mp {
  stop-color: var(--svg-color--d5d4da, #D5D4DA);
}

.chsd9qafy {
  stop-color: var(--svg-color--dca225, #DCA225);
  stop-opacity: 0;
}

.cznea_lps {
  stop-color: var(--svg-color--d5cbff, #D5CBFF);
  stop-opacity: 0;
}

.dlmz6ebuq {
  stop-color: var(--svg-color--c7c6c6, #C7C6C6);
}

.ei7e82vjx {
  d: path("M27.217 14.66c-3.534-3.445-9.188-3.386-12.633.149a8.9 8.9 0 0 0-2.006 3.185a.268.268 0 0 1-.399.129a6 6 0 0 0-.98-.527A6.428 6.428 0 0 0 2.09 23.44a6.44 6.44 0 0 0 1.404 4.011A6.45 6.45 0 0 0 8.641 30h12.633a8.33 8.33 0 0 0 6.8-3.504c2.707-3.544 2.418-8.641-.857-11.837");
}

.ft5dv1b6b {
  fill: none;
}

.gh040h5xh {
  stop-color: var(--svg-color--ceccd7, #CECCD7);
}

.gsrhrkoli {
  stop-color: var(--svg-color--ff942a, #FF942A);
  stop-opacity: 0;
}

.h1bfoacex {
  stop-color: var(--svg-color--ded7fa, #DED7FA);
  stop-opacity: 0;
}

.hd6-_5ncw {
  fill: var(--svg-color--eae0ff, #EAE0FF);
  d: path("M14.892 25.811a11.2 11.2 0 0 1-2.278 2.518h4.587c-.888-.528-1.909-1.899-2.309-2.518");
}

.hemkrl1wk {
  stop-color: var(--svg-color--dca21c, #DCA21C);
}

.ho17x8bec {
  d: path("M10.108 19.773a5.892 5.892 0 1 0 0-11.784a5.892 5.892 0 0 0 0 11.784");
}

.j756vz6_d {
  stop-color: var(--svg-color--d89a29, #D89A29);
}

.ktb62eb8s {
  stop-color: var(--svg-color--cdcdce, #CDCDCE);
}

.ku2pfdbii {
  stop-color: var(--svg-color--ffa13d, #FFA13D);
  stop-opacity: 0;
}

.kypg0578v {
  stop-color: var(--svg-color--e0762a, #E0762A);
}

.lhdtcbcje {
  stop-color: var(--svg-color--cdcdce, #CDCDCE);
  stop-opacity: 0;
}

.m_t75sbfg {
  stop-color: var(--svg-color--ceccd7, #CECCD7);
  stop-opacity: 0;
}

.mlwsi7b0o {
  stop-color: var(--svg-color--ffd13d, #FFD13D);
}

.mulvig9sp {
  stop-color: var(--svg-color--f0851d, #F0851D);
}

.obuie9bnj {
  stop-color: var(--svg-color--fcfbfe, #FCFBFE);
  stop-opacity: 0;
}

.pud-xubcs {
  stop-color: var(--svg-color--ffa13d, #FFA13D);
}

.py52bpbbf {
  stop-color: var(--svg-color--d0c9ee, #D0C9EE);
  stop-opacity: 0;
}

.q3m8m7bhy {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
}

.qobktdb-h {
  stop-color: var(--svg-color--fcfbfe, #FCFBFE);
}

.rwhrj1bde {
  stop-color: var(--svg-color--e3745b, #E3745B);
}

.s91ts3bpo {
  stop-color: var(--svg-color--fc8b23, #FC8B23);
}

.tzt2apygr {
  stop-color: var(--svg-color--e3745b, #E3745B);
  stop-opacity: 0;
}

.uc7451bcz {
  stop-color: var(--svg-color--e67639, #E67639);
}

.uhy_-rb7u {
  stop-color: var(--svg-color--ff942a, #FF942A);
}

.uu8s2_d7p {
  stop-color: var(--svg-color--f0eff1, #F0EFF1);
}

.vbq0404qf {
  d: path("M8.746 6.828c.84-.945 1.982-.795 2.712 0l.446.516a.74.74 0 0 0 .605.236l.792-.236c1.08-.231 2.06.574 2.06 1.825v.471c.023.258.248.432.48.545l.716.3c1.035.505 1.294 1.705.54 2.712l-.215.282c-.192.26-.152.601.04.862l.213.3c.78.96.34 2.276-.761 2.736l-.616.257c-.232.097-.323.264-.366.511l-.043.806a1.706 1.706 0 0 1-1.92 1.493l-.938-.25c-.226-.033-.506.042-.656.278l-.338.462c-.84.947-1.973.79-2.545.236l-.624-.756c-.164-.159-.37-.294-.617-.2l-.944.258c-.78.11-1.698-.49-1.845-1.263l-.109-1.12a.74.74 0 0 0-.413-.53l-.662-.228c-.997-.464-1.33-1.588-.758-2.526l.373-.517a.74.74 0 0 0-.018-.796l-.279-.394c-.788-1.123-.243-2.377.925-2.753l.258-.083c.284-.092.559-.328.583-.626l.057-.723c.093-1.173 1.164-1.847 2.29-1.504l.365.11a.696.696 0 0 0 .818-.188z");
}

.vi4gafj3v {
  stop-color: var(--svg-color--c9c7cc, #C9C7CC);
}

.vxrp39aul {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
  stop-opacity: 0;
}

.xcfalibap {
  stop-color: var(--svg-color--d5cbff, #D5CBFF);
}

.xx8tv_e5i {
  stop-color: var(--svg-color--ded7fa, #DED7FA);
}

.yiqe49k2f {
  stop-color: var(--svg-color--e0762a, #E0762A);
  stop-opacity: 0;
}

.z1aynhbjt {
  stop-color: var(--svg-color--d0c9ee, #D0C9EE);
}

</style>
