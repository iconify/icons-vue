<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNaem7b)" class="hh12597rk"/><path fill="url(#ij0zAXc)" class="hh12597rk"/><path fill="url(#iobUlhe)" class="hh12597rk"/><path fill="url(#is8nMoT)" class="hh12597rk"/><path fill="url(#iehwFfb)" class="hh12597rk"/><path fill="url(#iCE2gve)" class="hh12597rk"/><path fill="url(#i2TyyUn)" class="hh12597rk"/><path fill="url(#iEndYtb)" class="hh12597rk"/><path fill="url(#iCfXIXd)" class="hh12597rk"/><path fill="url(#iawUGoc)" class="hh12597rk"/><g filter="url(#ieK4lGz)"><path fill="url(#iWAd0ud)" class="w_emflcmq"/><path fill="url(#iivkXjb)" class="w_emflcmq"/><path fill="url(#i2usj1K)" class="w_emflcmq"/></g><path fill="url(#i1SHKQN)" class="f6tme448a"/><path fill="url(#imtYDve)" class="f6tme448a"/><g filter="url(#iXm7t0d)"><path class="w_afovxuq"/><path fill="url(#iFkWi5c)" class="zh2n0--fp"/></g><path fill="url(#iWJevRb)" class="zh2n0--fp"/><path fill="url(#icIKGib)" class="zh2n0--fp"/><path fill="url(#iCZXOKe)" class="zh2n0--fp"/><path fill="url(#iPQqaXD)" class="zh2n0--fp"/><defs><radialGradient id="ij0zAXc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57262 2.30382 -2.03268 -2.26984 16.741 5.187)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="q3m8m7bhy"/><stop offset="1" class="vxrp39aul"/></radialGradient><radialGradient id="iobUlhe" cx="0" cy="0" r="1" gradientTransform="rotate(67.811 .83 7.818)scale(5.49009 4.84396)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="uhy_-rb7u"/><stop offset="1" class="gsrhrkoli"/></radialGradient><radialGradient id="is8nMoT" cx="0" cy="0" r="1" gradientTransform="rotate(-164.745 11.868 3.103)scale(2.18897 3.03092)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="iehwFfb" cx="0" cy="0" r="1" gradientTransform="rotate(154.195 12.037 9.286)scale(3.88115 2.86651)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="iCE2gve" cx="0" cy="0" r="1" gradientTransform="matrix(-4.30048 -.49918 .2813 -2.42347 27.761 18.971)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="pud-xubcs"/><stop offset="1" class="ku2pfdbii"/></radialGradient><radialGradient id="i2TyyUn" cx="0" cy="0" r="1" gradientTransform="rotate(-43.964 41.671 -17.583)scale(3.92708 3.78328)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="iEndYtb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84307 -2.38062 2.29345 -1.77559 5.683 23.08)" gradientUnits="userSpaceOnUse"><stop class="kypg0578v"/><stop offset="1" class="yiqe49k2f"/></radialGradient><radialGradient id="iCfXIXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.76459 1.30552 -1.5779 3.3414 1.574 12.905)" gradientUnits="userSpaceOnUse"><stop class="mulvig9sp"/><stop offset="1" class="a_xm9geyk"/></radialGradient><radialGradient id="iawUGoc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.82744 -2.17059 2.04777 -2.66745 19.824 28.362)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="rwhrj1bde"/><stop offset="1" class="tzt2apygr"/></radialGradient><radialGradient id="iWAd0ud" cx="0" cy="0" r="1" gradientTransform="rotate(117.739 6.607 11.602)scale(17.5199 21.6353)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="mlwsi7b0o"/><stop offset="1" class="hemkrl1wk"/><stop offset="1" class="j756vz6_d"/></radialGradient><radialGradient id="iivkXjb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.72487 -3.87677 3.27312 -3.98916 10.89 22.496)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="aksdkybif"/><stop offset="1" class="chsd9qafy"/></radialGradient><radialGradient id="i2usj1K" cx="0" cy="0" r="1" gradientTransform="rotate(168.299 10.422 8.73)scale(20.9088 17.6531)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="chsd9qafy"/><stop offset="1" class="aksdkybif"/></radialGradient><radialGradient id="i1SHKQN" cx="0" cy="0" r="1" gradientTransform="rotate(-172.463 9.573 9.762)scale(4.15963)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="ew49psbno"/><stop offset="1" class="kz7b9dj2g"/></radialGradient><radialGradient id="imtYDve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.76088 -1.41366 1.29524 -1.61337 17.015 21.564)" gradientUnits="userSpaceOnUse"><stop class="ktb62eb8s"/><stop offset="1" class="lhdtcbcje"/></radialGradient><radialGradient id="iWJevRb" cx="0" cy="0" r="1" gradientTransform="rotate(136.5 9.37 16.145)scale(8.36814 8.97651)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="qobktdb-h"/><stop offset="1" class="obuie9bnj"/></radialGradient><radialGradient id="icIKGib" cx="0" cy="0" r="1" gradientTransform="rotate(144.444 3.048 14.55)scale(5.1338 5.37944)" gradientUnits="userSpaceOnUse"><stop class="qobktdb-h"/><stop offset="1" class="obuie9bnj"/></radialGradient><radialGradient id="iCZXOKe" cx="0" cy="0" r="1" gradientTransform="matrix(-17.41542 4.1316 -3.25377 -13.71522 26.409 23.218)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="m_t75sbfg"/><stop offset="1" class="gh040h5xh"/></radialGradient><radialGradient id="iPQqaXD" cx="0" cy="0" r="1" gradientTransform="rotate(-46.79 41.846 2.013)scale(4.8491 6.69189)" gradientUnits="userSpaceOnUse"><stop class="z1aynhbjt"/><stop offset="1" class="py52bpbbf"/></radialGradient><linearGradient id="iNaem7b" x1="22.005" x2="7.976" y1="8.321" y2="26.22" gradientUnits="userSpaceOnUse"><stop class="s91ts3bpo"/><stop offset="1" class="uc7451bcz"/></linearGradient><linearGradient id="iFkWi5c" x1="21.643" x2="21.643" y1="29.644" y2="24.008" gradientUnits="userSpaceOnUse"><stop class="xx8tv_e5i"/><stop offset="1" class="h1bfoacex"/></linearGradient><filter id="ieK4lGz" width="20.236" height="20.236" x="3.961" y="7.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.47451 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_15087"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_15087" result="shape"/></filter><filter id="iXm7t0d" width="21.006" height="14.504" x="8.994" y="15.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.784314 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15087"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sun-behind-small-cloud" /></template>
<style>
.a_xm9geyk {
  stop-color: var(--svg-color--f0851d, #F0851D);
  stop-opacity: 0;
}

.aksdkybif {
  stop-color: var(--svg-color--dca225, #DCA225);
}

.chsd9qafy {
  stop-color: var(--svg-color--dca225, #DCA225);
  stop-opacity: 0;
}

.ew49psbno {
  stop-color: var(--svg-color--e8e8e9, #E8E8E9);
}

.f6tme448a {
  d: path("M16.69 24.852a3.03 3.03 0 1 0 0-6.062a3.03 3.03 0 0 0 0 6.062");
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

.hemkrl1wk {
  stop-color: var(--svg-color--dca21c, #DCA21C);
}

.hh12597rk {
  d: path("M12.11 5.09c1.399-1.576 3.301-1.325 4.519 0l.742.86c.258.279.63.424 1.008.392l1.32-.393c1.8-.386 3.435.957 3.435 3.042v.785c.038.429.412.72.799.908l1.193.499c1.725.842 2.156 2.841.9 4.52l-.358.47c-.32.433-.254 1.002.065 1.436l.357.5c1.299 1.599.566 3.793-1.27 4.56l-1.026.428c-.387.162-.538.44-.61.852l-.072 1.342a2.84 2.84 0 0 1-3.199 2.489l-1.563-.418c-.376-.053-.843.071-1.093.464l-.564.771c-1.4 1.578-3.288 1.316-4.241.393l-1.04-1.26c-.273-.264-.617-.49-1.028-.334l-1.573.43c-1.3.184-2.83-.815-3.075-2.104l-.181-1.866a1.23 1.23 0 0 0-.688-.884l-1.104-.38c-1.66-.773-2.217-2.646-1.263-4.21l.622-.86a1.23 1.23 0 0 0-.03-1.327l-.465-.657c-1.313-1.87-.405-3.962 1.542-4.588l.429-.139c.474-.152.932-.546.971-1.042l.096-1.205C5.82 6.61 7.605 5.486 9.48 6.057l.608.185c.585.228 1.044.034 1.363-.315z");
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

.kz7b9dj2g {
  stop-color: var(--svg-color--d2d2d2, #D2D2D2);
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

.vxrp39aul {
  stop-color: var(--svg-color--ffa13a, #FFA13A);
  stop-opacity: 0;
}

.w_afovxuq {
  fill: var(--svg-color--d5d4da, #D5D4DA);
  d: path("M27.967 18.786c-2.668-2.6-6.938-2.556-9.54.113a6.7 6.7 0 0 0-1.485 2.325a.275.275 0 0 1-.402.131a4.5 4.5 0 0 0-.668-.351a4.854 4.854 0 0 0-5.818 7.442a4.87 4.87 0 0 0 3.886 1.924h9.54a6.3 6.3 0 0 0 5.134-2.646c2.044-2.676 1.826-6.525-.647-8.938");
}

.w_emflcmq {
  d: path("M14.38 26.66c5.422 0 9.818-4.395 9.818-9.817s-4.396-9.819-9.819-9.819c-5.422 0-9.818 4.396-9.818 9.819c0 5.422 4.396 9.818 9.818 9.818");
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

.zh2n0--fp {
  d: path("M27.967 18.786c-2.668-2.6-6.938-2.556-9.54.113a6.7 6.7 0 0 0-1.485 2.325a.275.275 0 0 1-.402.131a4.5 4.5 0 0 0-.668-.351a4.854 4.854 0 0 0-5.818 7.442a4.87 4.87 0 0 0 3.886 1.924h9.54a6.3 6.3 0 0 0 5.134-2.646c2.044-2.676 1.826-6.525-.647-8.938");
}

</style>
