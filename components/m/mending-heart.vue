<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZLfnQd)" class="u49y1ob3c"/><path fill="url(#ikDizLb)" class="u49y1ob3c"/><path fill="url(#iTXPlie)" class="u49y1ob3c"/><path fill="url(#igOFF1V)" class="u49y1ob3c"/><path fill="url(#iYFK5Od)" class="u49y1ob3c"/><path fill="url(#iQfi6Ie)" class="wh9lo751k"/><path fill="url(#iNsiUpb)" class="n3nlfccmg"/><g filter="url(#ihsoase)"><path class="rhgkpuzib"/></g><g filter="url(#i8AxYYc)"><path class="zyzenhbtc"/></g><g filter="url(#ir6Evkb)"><ellipse fill="url(#i2YgbWy)" transform="rotate(-44.19 25.034 11.256)" class="uywokbcmt"/></g><g filter="url(#iSHEhMd)"><ellipse fill="url(#iqFowjc)" transform="rotate(-128.955 13.708 13.168)" class="ujmm7mgyr"/></g><g filter="url(#isigAsd)"><ellipse class="wn5d7wntx"/></g><g filter="url(#iWpMXmd)"><ellipse class="iaamw3bve"/></g><path fill="url(#iTLTnce)" class="m1hnsyb0j"/><path fill="url(#imGQd8d)" class="m1hnsyb0j"/><path fill="url(#iQ8RJDb)" class="h771dzmfp"/><path fill="url(#iFOzDie)" class="h771dzmfp"/><path fill="url(#iMQyKHd)" clip-rule="evenodd" class="z-jgobcjo"/><path fill="url(#iUYK2vc)" clip-rule="evenodd" class="z-jgobcjo"/><g filter="url(#iZ2YZ3b)"><path class="ztlfb_bsh"/></g><path fill="url(#iLBYCpd)" class="oxiftccbt"/><path fill="url(#i06L3te)" class="oxiftccbt"/><path fill="url(#iTTdJjc)" class="oxiftccbt"/><path fill="url(#iIvAHub)" class="oxiftccbt"/><path fill="url(#i06ZxJc)" class="oxiftccbt"/><defs><linearGradient id="igOFF1V" x1="17.576" x2="8.543" y1="18.899" y2="30.09" gradientUnits="userSpaceOnUse"><stop offset=".151" class="k0jhnr2iw"/><stop offset=".895" class="gqtzoxfau"/></linearGradient><linearGradient id="iQfi6Ie" x1="17.85" x2="25.951" y1="16.234" y2="25.875" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iNsiUpb" x1="16.846" x2="7.339" y1="16.636" y2="27.348" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iTLTnce" x1="27.89" x2="10.326" y1="13.579" y2="26.107" gradientUnits="userSpaceOnUse"><stop class="k3e_7cjfq"/><stop offset="1" class="nu39-lucu"/></linearGradient><linearGradient id="imGQd8d" x1=".952" x2="8.327" y1="17.875" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="bp_pxiots"/><stop offset="1" class="uv-emwxtv"/></linearGradient><linearGradient id="iQ8RJDb" x1="16.952" x2="13.827" y1="12.313" y2="9.125" gradientUnits="userSpaceOnUse"><stop class="eu-87q5qq"/><stop offset="1" class="fxzep2bhm"/></linearGradient><linearGradient id="iFOzDie" x1="10.957" x2="10.957" y1="9.563" y2="11.219" gradientUnits="userSpaceOnUse"><stop class="nqw9qiugk"/><stop offset="1" class="r_a9lt41m"/></linearGradient><linearGradient id="iMQyKHd" x1="20.265" x2="22.197" y1="13.625" y2="16.438" gradientUnits="userSpaceOnUse"><stop offset=".349" class="di1jnsb9s"/><stop offset=".87" class="qg7fidcwu"/></linearGradient><linearGradient id="iUYK2vc" x1="25.14" x2="25.227" y1="20" y2="16.893" gradientUnits="userSpaceOnUse"><stop offset=".156" class="gh43pq77i"/><stop offset="1" class="algjvrbvy"/></linearGradient><linearGradient id="iLBYCpd" x1="28.265" x2="8.702" y1="12.75" y2="21.75" gradientUnits="userSpaceOnUse"><stop offset=".12" class="l3_ginzph"/><stop offset="1" class="nu39-lucu"/></linearGradient><linearGradient id="i06L3te" x1="22.171" x2="20.296" y1="18.156" y2="13.969" gradientUnits="userSpaceOnUse"><stop class="tiswix-cf"/><stop offset="1" class="mh358hkmc"/></linearGradient><linearGradient id="iTTdJjc" x1="20.827" x2="20.108" y1="16.844" y2="15.187" gradientUnits="userSpaceOnUse"><stop class="gh43pq77i"/><stop offset="1" class="algjvrbvy"/></linearGradient><linearGradient id="iIvAHub" x1="18.265" x2="18.89" y1="9.75" y2="11.062" gradientUnits="userSpaceOnUse"><stop class="ja5-0jbxg"/><stop offset="1" class="mh358hkmc"/></linearGradient><linearGradient id="i06ZxJc" x1="16.782" x2="2.952" y1="19.75" y2="23.25" gradientUnits="userSpaceOnUse"><stop class="rzx1jsbra"/><stop offset=".956" class="eqevcdbbw"/></linearGradient><filter id="ihsoase" width="24.031" height="6.488" x="4.702" y="12.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7137_6142" stdDeviation=".375"/></filter><filter id="i8AxYYc" width="7.966" height="12.721" x="14.793" y="7.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7137_6142" stdDeviation="1"/></filter><filter id="ir6Evkb" width="10.262" height="10.189" x="19.903" y="6.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7137_6142" stdDeviation=".75"/></filter><filter id="iSHEhMd" width="10.31" height="11.206" x="8.553" y="7.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7137_6142" stdDeviation=".75"/></filter><filter id="isigAsd" width="7.124" height="3.802" x="19.835" y="4.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7137_6142" stdDeviation=".75"/></filter><filter id="iWpMXmd" width="7.124" height="3.802" x="5.869" y="4.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7137_6142" stdDeviation=".75"/></filter><filter id="iZ2YZ3b" width="4.713" height="8.75" x="12.077" y="9.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7137_6142" stdDeviation=".75"/></filter><radialGradient id="iZLfnQd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.93754 -13.37496 27.03893 -18.0682 11.327 22.25)" gradientUnits="userSpaceOnUse"><stop class="dfoclab_o"/><stop offset=".634" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="ikDizLb" cx="0" cy="0" r="1" gradientTransform="matrix(-21.1736 15.96356 -29.9013 -39.6602 23.188 11.411)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="iTXPlie" cx="0" cy="0" r="1" gradientTransform="matrix(-21.4247 -8.36909 11.8309 -30.28687 20.127 17.908)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="iYFK5Od" cx="0" cy="0" r="1" gradientTransform="rotate(90 .875 14.766)scale(20.9184)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="i2YgbWy" cx="0" cy="0" r="1" gradientTransform="rotate(-176.775 14.806 5.661)scale(6.22377 4.20257)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="iqFowjc" cx="0" cy="0" r="1" gradientTransform="rotate(-177.229 8.449 6.736)scale(6.31058 3.34222)" gradientUnits="userSpaceOnUse"><stop class="j0jx7sb_q"/><stop offset="1" class="nwq74cdll"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mending-heart" /></template>
<style>
.algjvrbvy {
  stop-color: var(--svg-color--ab7ada, #AB7ADA);
  stop-opacity: 0;
}

.bp_pxiots {
  stop-color: var(--svg-color--9a94a0, #9A94A0);
}

.dfoclab_o {
  stop-color: var(--svg-color--ff0d39, #FF0D39);
}

.di1jnsb9s {
  stop-color: var(--svg-color--b6a2c7, #B6A2C7);
}

.eqevcdbbw {
  stop-color: var(--svg-color--a899b9, #A899B9);
}

.eu-87q5qq {
  stop-color: var(--svg-color--bbb, #BBB);
}

.fdfp5-b0w {
  stop-color: var(--svg-color--b91d43, #B91D43);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxzep2bhm {
  stop-color: var(--svg-color--c8c3c9, #C8C3C9);
  stop-opacity: 0;
}

.gh43pq77i {
  stop-color: var(--svg-color--ab7ada, #AB7ADA);
}

.gqtzoxfau {
  stop-color: var(--svg-color--c12372, #C12372);
}

.h771dzmfp {
  d: path("M19.805 10.625H2.312c-.398 1.718-.243 3.802.739 6.208q.169.506.432 1.042h4.58c3.815-2.344 8.354-5.15 11.742-7.25");
}

.iaamw3bve {
  cx: 9.431px;
  cy: 6.257px;
  fill: var(--svg-color--ff93ba, #FF93BA);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 2.062px;
  ry: 0.401px;
}

.j0jx7sb_q {
  stop-color: var(--svg-color--ffa7c7, #FFA7C7);
}

.ja5-0jbxg {
  stop-color: var(--svg-color--a2a2a2, #A2A2A2);
}

.k0jhnr2iw {
  stop-color: var(--svg-color--c12372, #C12372);
  stop-opacity: 0;
}

.k3e_7cjfq {
  stop-color: var(--svg-color--e3deea, #E3DEEA);
}

.l3_ginzph {
  stop-color: var(--svg-color--f1f0f4, #F1F0F4);
}

.lj35z3s3o {
  stop-color: var(--svg-color--b91d43, #B91D43);
}

.m1hnsyb0j {
  d: path("M3.483 17.875H28.74q.372-.724.674-1.478c.94-2.087 1.064-4.066.631-5.772H2.312c-.398 1.718-.243 3.802.739 6.208q.169.506.432 1.042");
}

.mh358hkmc {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
  stop-opacity: 0;
}

.n3nlfccmg {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M15.303 29.453a1.73 1.73 0 0 0 1.71-.023c3.622-2.067 9.926-6.836 12.4-13.032c3.63-8.061-4.891-14.496-10.78-9.868c-.616.484-1.392 1.039-1.923 1.564c-.238.234-.656.258-.903.034c-.698-.637-1.795-1.456-2.498-1.931C8.29 2.8-.846 7.277 3.051 16.833c1.428 4.293 8.24 10.384 12.252 12.62");
}

.nqw9qiugk {
  stop-color: var(--svg-color--d0cbd0, #D0CBD0);
}

.nu39-lucu {
  stop-color: var(--svg-color--b4a4c6, #B4A4C6);
}

.nwq74cdll {
  stop-color: var(--svg-color--ffa7c7, #FFA7C7);
  stop-opacity: 0;
}

.oxiftccbt {
  d: path("M6.59 22.226c2.263-.998 6.936-3.106 11.673-5.243c4.68-2.112 9.423-4.251 11.965-5.376a7.57 7.57 0 0 0-3.257-5.374c-6.076 2.6-19.733 9.384-23.634 11.331c.654 1.461 1.833 3.08 3.252 4.662");
}

.pl211ybaw {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
}

.qg7fidcwu {
  stop-color: var(--svg-color--b6a2c7, #B6A2C7);
  stop-opacity: 0;
}

.qnbh2pn9v {
  stop-color: var(--svg-color--ff73a6, #FF73A6);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r_a9lt41m {
  stop-color: var(--svg-color--d0cbd0, #D0CBD0);
  stop-opacity: 0;
}

.r-3kexbeb {
  stop-color: var(--svg-color--ff4ec6, #FF4EC6);
}

.rhgkpuzib {
  fill: var(--svg-color--b70952, #B70952);
  d: path("M5.452 13.168h22.531v4.988H5.452z");
}

.rzx1jsbra {
  stop-color: var(--svg-color--b4a4c6, #B4A4C6);
  stop-opacity: 0;
}

.tiswix-cf {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
}

.u49y1ob3c {
  d: path("M15.303 29.453a1.73 1.73 0 0 0 1.71-.023c3.622-2.067 9.926-6.836 12.4-13.032c3.63-8.061-4.891-14.496-10.78-9.868c-.616.484-1.392 1.039-1.923 1.564c-.238.234-.656.258-.903.034c-.698-.637-1.795-1.456-2.498-1.931C8.29 2.8-.846 7.277 3.051 16.833c1.428 4.293 8.24 10.384 12.252 12.62");
}

.ujmm7mgyr {
  cx: 13.708px;
  cy: 13.168px;
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 4.835px;
  ry: 2.609px;
}

.uv-emwxtv {
  stop-color: var(--svg-color--9a94a0, #9A94A0);
  stop-opacity: 0;
}

.uywokbcmt {
  cx: 25.034px;
  cy: 11.256px;
  rx: 4.209px;
  ry: 2.896px;
}

.wh9lo751k {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M15.303 29.453a1.73 1.73 0 0 0 1.71-.023c3.622-2.067 9.926-6.836 12.4-13.032c3.63-8.061-4.891-14.496-10.78-9.868c-.616.484-1.392 1.039-1.923 1.564c-.238.234-.656.258-.903.034c-.698-.637-1.795-1.456-2.498-1.931C8.29 2.8-.846 7.277 3.051 16.833c1.428 4.293 8.24 10.384 12.252 12.62");
}

.wn5d7wntx {
  cx: 23.397px;
  cy: 6.257px;
  fill: var(--svg-color--ff93ba, #FF93BA);
  rx: 2.062px;
  ry: 0.401px;
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.z-jgobcjo {
  fill-rule: evenodd;
  d: path("M14.11 17.875h14.63q.372-.724.674-1.478c.94-2.087 1.065-4.066.631-5.772H27.02z");
}

.ztlfb_bsh {
  fill: var(--svg-color--f4f4f4, #F4F4F4);
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.577 10.875h1.713v5.75h-1.713z");
}

.zyzenhbtc {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M16.793 10.62v6.933c0 .905 1.096 1.334 1.661.627c1.773-2.217 3.21-4.92 1.617-7.125c-.61-.845-1.78-1.385-2.735-1.21c-.353.065-.543.417-.543.775");
}

</style>
