<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l24q6kb2h"/><path fill="url(#iP1bJDd)" class="tnpt-t2uw"/><path fill="url(#iJmGGke)" class="tnpt-t2uw"/><path fill="url(#ie3YjVn)" class="tnpt-t2uw"/><path fill="url(#ioyKE4Z)" class="tnpt-t2uw"/><path fill="url(#i0swfcb)" class="v6c3nhbts"/><path fill="url(#iqNygBc)" class="v6c3nhbts"/><path fill="url(#iGbr5xL)" class="v6c3nhbts"/><path class="x9hjl8d-m"/><path fill="url(#iWrOkOc)" class="vjszzqk1z"/><path fill="url(#iDCWdPd)" class="vjszzqk1z"/><path fill="url(#ihITPlA)" class="o9n4vcbdp"/><path fill="url(#iOCFCvd)" class="vjszzqk1z"/><path fill="url(#iwKmBcb)" class="vjszzqk1z"/><path class="x98x9chky"/><path fill="url(#i8umjfb)" class="oiy29llca"/><path fill="url(#idvXMjd)" class="oiy29llca"/><path fill="url(#iVHAOLb)" class="oiy29llca"/><path fill="url(#ie7WVTd)" class="oiy29llca"/><g filter="url(#igEtzbe)"><path class="hpasfhvva"/></g><path class="pmhehitbo"/><path fill="url(#imPJuvQ)" class="n09aenbwo"/><path fill="url(#iyxA26c)" class="n09aenbwo"/><path fill="url(#iB34kbb)" class="n09aenbwo"/><path class="uml7_ybhj"/><path class="cxdn5_b6c"/><path fill="url(#idkQalb)" class="kw6z2q_cb"/><path fill="url(#iZ48DXd)" class="kw6z2q_cb"/><path class="hhqyopx3v"/><path class="hi_9g3exn"/><path fill="url(#i3eZLIu)" class="vejrjxbje"/><path fill="url(#iKRNAQb)" class="vejrjxbje"/><g filter="url(#isXaX0b)"><path fill="url(#ixmdFQb)" class="k-q31r0oe"/></g><g filter="url(#iGtXVcd)"><path fill="url(#ix9yzCl)" class="myo_odb8a"/></g><defs><radialGradient id="iP1bJDd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4.78126 -5.30978 1.45758 20.216 28.85)" gradientUnits="userSpaceOnUse"><stop class="e7zvbkjfl"/><stop offset=".962" class="deg05tt1v"/></radialGradient><radialGradient id="iJmGGke" cx="0" cy="0" r="1" gradientTransform="rotate(110.468 -3.293 18.117)scale(4.73651 2.77297)" gradientUnits="userSpaceOnUse"><stop class="njm5aob0y"/><stop offset="1" class="v44qa_yhw"/></radialGradient><radialGradient id="ie3YjVn" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.625 -3.3625 0 16.172 27.538)" gradientUnits="userSpaceOnUse"><stop class="aj21aobha"/><stop offset="1" class="ojin-2btb"/></radialGradient><radialGradient id="iqNygBc" cx="0" cy="0" r="1" gradientTransform="rotate(144.713 10.768 11.687)scale(4.9769 8.47205)" gradientUnits="userSpaceOnUse"><stop class="plyw68bup"/><stop offset="1" class="x2ju17bho"/></radialGradient><radialGradient id="iDCWdPd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99999 1.422 -2.67838 -13.1847 25.497 15.744)" gradientUnits="userSpaceOnUse"><stop class="zlxu-thdk"/><stop offset="1" class="gwfdv78iu"/></radialGradient><radialGradient id="ihITPlA" cx="0" cy="0" r="1" gradientTransform="rotate(-165.741 15.382 8.803)scale(23.3441 20.09)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="ion22g0yh"/><stop offset="1" class="g3z3_096a"/></radialGradient><radialGradient id="iOCFCvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41113 -7.77269 0 16.087 14.879)" gradientUnits="userSpaceOnUse"><stop class="b2ao6kbea"/><stop offset="1" class="krvat8b_m"/></radialGradient><radialGradient id="iwKmBcb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12491 11.3954 -12.97923 -3.55924 16.997 16.671)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="e6ls6c_rr"/><stop offset="1" class="k8en-hbrc"/></radialGradient><radialGradient id="idvXMjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.3125 -19.1955 0 16.172 7.694)" gradientUnits="userSpaceOnUse"><stop offset=".752" class="co4onxyko"/><stop offset="1" class="oopvm4bza"/></radialGradient><radialGradient id="iVHAOLb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 -.28125 .27194 2.4173 5.466 4.663)" gradientUnits="userSpaceOnUse"><stop class="rtvjbqzkt"/><stop offset="1" class="nnpzpm2bh"/></radialGradient><radialGradient id="ie7WVTd" cx="0" cy="0" r="1" gradientTransform="rotate(145.597 11.322 7.67)scale(3.48448 3.68395)" gradientUnits="userSpaceOnUse"><stop class="s9bif3bza"/><stop offset="1" class="f1wu6gb8f"/></radialGradient><radialGradient id="imPJuvQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.3125 2.61314 0 16.087 13.022)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="e3mo_5vcj"/><stop offset="1" class="ue0tg3b-a"/></radialGradient><radialGradient id="iyxA26c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.42187 1.47028 0 16.872 13.022)" gradientUnits="userSpaceOnUse"><stop class="rp-4frzni"/><stop offset="1" class="ojv3bzbeb"/></radialGradient><radialGradient id="idkQalb" cx="0" cy="0" r="1" gradientTransform="rotate(131.005 4.265 7.042)scale(2.19471 2.10749)" gradientUnits="userSpaceOnUse"><stop class="lksk0cb0r"/><stop offset=".834" class="b3rg-fb6u"/></radialGradient><radialGradient id="iZ48DXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5625 3.64879 0 10.627 11.975)" gradientUnits="userSpaceOnUse"><stop class="n_lgnbb3i"/><stop offset="1" class="oeq3yac2z"/></radialGradient><radialGradient id="i3eZLIu" cx="0" cy="0" r="1" gradientTransform="rotate(131.005 9.575 9.462)scale(2.19471 2.10749)" gradientUnits="userSpaceOnUse"><stop class="lksk0cb0r"/><stop offset=".834" class="b3rg-fb6u"/></radialGradient><radialGradient id="iKRNAQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5625 3.64879 0 21.247 11.975)" gradientUnits="userSpaceOnUse"><stop class="n_lgnbb3i"/><stop offset="1" class="oeq3yac2z"/></radialGradient><linearGradient id="ioyKE4Z" x1="16.172" x2="16.172" y1="30.007" y2="29.35" gradientUnits="userSpaceOnUse"><stop offset=".029" class="nqwk8achb"/><stop offset="1" class="ui83chyqg"/></linearGradient><linearGradient id="i0swfcb" x1="10.122" x2="22.559" y1="25.507" y2="25.507" gradientUnits="userSpaceOnUse"><stop class="e8omx91_l"/><stop offset="1" class="v87lh5bbx"/></linearGradient><linearGradient id="iGbr5xL" x1="16.097" x2="16.097" y1="23.569" y2="27.444" gradientUnits="userSpaceOnUse"><stop class="cvstbns4l"/><stop offset="1" class="fcu2_2byj"/></linearGradient><linearGradient id="iWrOkOc" x1="9.497" x2="19.997" y1="21.122" y2="21.122" gradientUnits="userSpaceOnUse"><stop class="c0kh_sbfh"/><stop offset="1" class="zjt6xbcnr"/></linearGradient><linearGradient id="i8umjfb" x1="16.997" x2="16.997" y1="14.632" y2="6.569" gradientUnits="userSpaceOnUse"><stop class="t-adavxpx"/><stop offset="1" class="vi5yxqcrw"/></linearGradient><linearGradient id="iB34kbb" x1="16.087" x2="16.087" y1="13.061" y2="12.749" gradientUnits="userSpaceOnUse"><stop class="ue0tg3b-a"/><stop offset="1" class="e3mo_5vcj"/></linearGradient><linearGradient id="ixmdFQb" x1="24.544" x2="28.309" y1="3.413" y2="1.819" gradientUnits="userSpaceOnUse"><stop class="aak4mns6g"/><stop offset="1" class="vs8nz3bla"/></linearGradient><linearGradient id="ix9yzCl" x1="24.309" x2="26.521" y1="4.178" y2="5.286" gradientUnits="userSpaceOnUse"><stop class="aak4mns6g"/><stop offset="1" class="vs8nz3bla"/></linearGradient><filter id="igEtzbe" width="4.708" height="2.545" x="13.597" y="10.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5045" stdDeviation=".15"/></filter><filter id="isXaX0b" width="7.906" height="2.656" x="19.309" y="1.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5045" stdDeviation=".25"/></filter><filter id="iGtXVcd" width="5.078" height="2.406" x="21.137" y="3.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5045" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:owl" /></template>
<style>
.aak4mns6g {
  stop-color: var(--svg-color--a58472, #A58472);
}

.aj21aobha {
  stop-color: var(--svg-color--ff6729, #FF6729);
}

.b2ao6kbea {
  stop-color: var(--svg-color--f19989, #F19989);
}

.b3rg-fb6u {
  stop-color: var(--svg-color--4f4142, #4F4142);
}

.c0kh_sbfh {
  stop-color: var(--svg-color--ffb298, #FFB298);
}

.co4onxyko {
  stop-color: var(--svg-color--8d584b, #8D584B);
  stop-opacity: 0;
}

.cvstbns4l {
  stop-color: var(--svg-color--733b50, #733B50);
  stop-opacity: 0;
}

.cxdn5_b6c {
  fill: var(--svg-color--f8d41e, #F8D41E);
  d: path("M10.937 12.977a3.28 3.28 0 1 0 0-6.56a3.28 3.28 0 0 0 0 6.56");
}

.deg05tt1v {
  stop-color: var(--svg-color--ffac76, #FFAC76);
  stop-opacity: 0;
}

.e3mo_5vcj {
  stop-color: var(--svg-color--ea5d1a, #EA5D1A);
  stop-opacity: 0;
}

.e6ls6c_rr {
  stop-color: var(--svg-color--f58285, #F58285);
  stop-opacity: 0;
}

.e7zvbkjfl {
  stop-color: var(--svg-color--ffac76, #FFAC76);
}

.e8omx91_l {
  stop-color: var(--svg-color--5e392f, #5E392F);
}

.f1wu6gb8f {
  stop-color: var(--svg-color--a58371, #A58371);
  stop-opacity: 0;
}

.fcu2_2byj {
  stop-color: var(--svg-color--733b50, #733B50);
}

.ft5dv1b6b {
  fill: none;
}

.g3z3_096a {
  stop-color: var(--svg-color--ffec79, #FFEC79);
}

.gwfdv78iu {
  stop-color: var(--svg-color--fff6c0, #FFF6C0);
  stop-opacity: 0;
}

.hhqyopx3v {
  fill: var(--svg-color--2e2a31, #2E2A31);
  d: path("M22.017 13.157a3.97 3.97 0 1 0 0-7.94a3.97 3.97 0 0 0 0 7.94");
}

.hi_9g3exn {
  fill: var(--svg-color--f8d41e, #F8D41E);
  d: path("M21.557 12.977a3.28 3.28 0 1 0 0-6.56a3.28 3.28 0 0 0 0 6.56");
}

.hpasfhvva {
  fill: var(--svg-color--622b2e, #622B2E);
  d: path("M18.005 12.85h-4.108c0-1.072.924-1.945 2.06-1.945c1.136.013 2.048.873 2.048 1.945");
}

.ion22g0yh {
  stop-color: var(--svg-color--ffec79, #FFEC79);
  stop-opacity: 0;
}

.k-q31r0oe {
  d: path("m19.81 3.57l6.906-1.188l-2.813 1.656c-.812-.5-3.5-.469-4.094-.469");
}

.k8en-hbrc {
  stop-color: var(--svg-color--f58285, #F58285);
}

.krvat8b_m {
  stop-color: var(--svg-color--f19989, #F19989);
  stop-opacity: 0;
}

.kw6z2q_cb {
  d: path("M10.937 11.717a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.l24q6kb2h {
  fill: var(--svg-color--ff6729, #FF6729);
  d: path("M22.14 29.258c.052.411-.289.749-.703.749h-10.53c-.414 0-.755-.338-.704-.749a6.02 6.02 0 0 1 5.974-5.271a6.01 6.01 0 0 1 5.964 5.271");
}

.lksk0cb0r {
  stop-color: var(--svg-color--796b6c, #796B6C);
}

.myo_odb8a {
  d: path("m21.638 3.678l.07-.004l1.93-.12c.992.25 1.656.96 2.078 1.406c-1.205-.896-3.332-1.308-4.008-1.286z");
}

.n_lgnbb3i {
  stop-color: var(--svg-color--4f2c51, #4F2C51);
}

.n09aenbwo {
  d: path("M18.116 13.022h-4.058c0-1.122.913-2.035 2.035-2.035a2.035 2.035 0 0 1 2.023 2.035");
}

.njm5aob0y {
  stop-color: var(--svg-color--ff8654, #FF8654);
}

.nnpzpm2bh {
  stop-color: var(--svg-color--634941, #634941);
  stop-opacity: 0;
}

.nqwk8achb {
  stop-color: var(--svg-color--fd5a4b, #FD5A4B);
}

.o9n4vcbdp {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M24.717 17.403c0 4.709-3.86 10.664-8.63 10.664s-8.63-5.955-8.63-10.664s3.86-8.536 8.63-8.536s8.63 3.818 8.63 8.536");
}

.oeq3yac2z {
  stop-color: var(--svg-color--4f2c51, #4F2C51);
  stop-opacity: 0;
}

.oiy29llca {
  d: path("M25.817 5.067a4.6 4.6 0 0 0 1.133-2.561c.03-.275-.197-.5-.473-.5h-5.15c-1.09 0-2.09.38-2.88 1.01h-4.56a4.6 4.6 0 0 0-2.88-1.01h-5.14c-.276 0-.503.225-.473.5a4.64 4.64 0 0 0 1.133 2.56a5.9 5.9 0 0 0-1.45 3.86c0 5.9 4.82 6.8 10.72 6.8h.75c5.9 0 10.72-.9 10.72-6.8c0-1.47-.55-2.82-1.45-3.86");
}

.ojin-2btb {
  stop-color: var(--svg-color--ff6729, #FF6729);
  stop-opacity: 0;
}

.ojv3bzbeb {
  stop-color: var(--svg-color--ffa174, #FFA174);
  stop-opacity: 0;
}

.oopvm4bza {
  stop-color: var(--svg-color--8d584b, #8D584B);
}

.plyw68bup {
  stop-color: var(--svg-color--a28171, #A28171);
}

.pmhehitbo {
  fill: var(--svg-color--ff7838, #FF7838);
  d: path("M18.116 13.022h-4.058c0-1.122.913-2.035 2.035-2.035a2.035 2.035 0 0 1 2.023 2.035");
}

.rp-4frzni {
  stop-color: var(--svg-color--ffa174, #FFA174);
}

.rtvjbqzkt {
  stop-color: var(--svg-color--634941, #634941);
}

.s9bif3bza {
  stop-color: var(--svg-color--a58371, #A58371);
}

.t-adavxpx {
  stop-color: var(--svg-color--713754, #713754);
}

.tnpt-t2uw {
  d: path("M22.14 29.258c.052.411-.289.749-.703.749h-10.53c-.414 0-.755-.338-.704-.749a6.02 6.02 0 0 1 5.974-5.271a6.01 6.01 0 0 1 5.964 5.271");
}

.ue0tg3b-a {
  stop-color: var(--svg-color--ea5d1a, #EA5D1A);
}

.ui83chyqg {
  stop-color: var(--svg-color--fd5a4b, #FD5A4B);
  stop-opacity: 0;
}

.uml7_ybhj {
  fill: var(--svg-color--2e2a31, #2E2A31);
  d: path("M10.497 13.157a3.97 3.97 0 1 0 0-7.94a3.97 3.97 0 0 0 0 7.94");
}

.v44qa_yhw {
  stop-color: var(--svg-color--ff8654, #FF8654);
  stop-opacity: 0;
}

.v6c3nhbts {
  d: path("M16.097 28.067c6.13 0 11.1-4.97 11.1-11.1s-4.97-11.1-11.1-11.1s-11.1 4.97-11.1 11.1s4.97 11.1 11.1 11.1");
}

.v87lh5bbx {
  stop-color: var(--svg-color--845249, #845249);
}

.vejrjxbje {
  d: path("M21.557 11.717a2.02 2.02 0 1 0 0-4.04a2.02 2.02 0 0 0 0 4.04");
}

.vi5yxqcrw {
  stop-color: var(--svg-color--713754, #713754);
  stop-opacity: 0;
}

.vjszzqk1z {
  d: path("M24.717 17.403c0 4.709-3.86 10.664-8.63 10.664s-8.63-5.955-8.63-10.664s3.86-8.536 8.63-8.536s8.63 3.818 8.63 8.536");
}

.vs8nz3bla {
  stop-color: var(--svg-color--a58472, #A58472);
  stop-opacity: 0;
}

.x2ju17bho {
  stop-color: var(--svg-color--a28171, #A28171);
  stop-opacity: 0;
}

.x98x9chky {
  fill: var(--svg-color--845a40, #845A40);
  d: path("M25.817 5.067a4.6 4.6 0 0 0 1.133-2.561c.03-.275-.197-.5-.473-.5h-5.15c-1.09 0-2.09.38-2.88 1.01h-4.56a4.6 4.6 0 0 0-2.88-1.01h-5.14c-.276 0-.503.225-.473.5a4.64 4.64 0 0 0 1.133 2.56a5.9 5.9 0 0 0-1.45 3.86c0 5.9 4.82 6.8 10.72 6.8h.75c5.9 0 10.72-.9 10.72-6.8c0-1.47-.55-2.82-1.45-3.86");
}

.x9hjl8d-m {
  fill: var(--svg-color--ffbea6, #FFBEA6);
  d: path("M24.717 17.403c0 4.709-3.86 10.664-8.63 10.664s-8.63-5.955-8.63-10.664s3.86-8.536 8.63-8.536s8.63 3.818 8.63 8.536");
}

.zjt6xbcnr {
  stop-color: var(--svg-color--ffb298, #FFB298);
  stop-opacity: 0;
}

.zlxu-thdk {
  stop-color: var(--svg-color--fff6c0, #FFF6C0);
}

</style>
