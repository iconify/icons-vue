<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#is5Jxee)" class="i5n85z-bl"/><path fill="url(#iBxMeJi)" class="i5n85z-bl"/><path fill="url(#itngNUj)" class="i5n85z-bl"/><path fill="url(#ivphyYd)" class="i5n85z-bl"/><path fill="url(#iNbh1Pe)" class="i5n85z-bl"/><g filter="url(#idvQZgb)"><path fill="url(#iCPTktS)" class="po-l-b2eq"/></g><path fill="url(#iyPEMeB)" class="ptg2wsevi"/><path fill="url(#ilokxLe)" class="ptg2wsevi"/><path fill="url(#iwwM1ce)" class="ptg2wsevi"/><path fill="url(#iEOaVxG)" class="ptg2wsevi"/><path fill="url(#i4mGQgU)" class="ptg2wsevi"/><path fill="url(#iDUrRqe)" class="ptg2wsevi"/><path fill="url(#iWXEsUr)" class="m6e8egx8l"/><path fill="url(#iJGRAzb)" class="m6e8egx8l"/><path fill="url(#iq7cjde)" class="m6e8egx8l"/><path fill="url(#iSnwKMe)" class="m7w3t5bve"/><path fill="url(#i83S7TI)" class="m7w3t5bve"/><path fill="url(#iD3RlKe)" class="m7w3t5bve"/><path fill="url(#iQoCLyd)" class="m7w3t5bve"/><g filter="url(#idbC8md)"><path fill="url(#imjraec)" class="oas87b1xo"/></g><path fill="url(#i3Ne7kD)" class="yzfgfrbbo"/><path fill="url(#iZ7LvCc)" class="yzfgfrbbo"/><path fill="url(#iHFGTec)" class="yzfgfrbbo"/><path fill="url(#iQBosJb)" class="yzfgfrbbo"/><path fill="url(#iymNGse)" class="yzfgfrbbo"/><path fill="url(#iPAkBgb)" class="o4dmaij5r"/><path fill="url(#i5YQwKe)" class="o4dmaij5r"/><path fill="url(#iPPhuyc)" class="o4dmaij5r"/><path fill="url(#iXU08xe)" class="o4dmaij5r"/><path fill="url(#iKo7H9L)" class="o4dmaij5r"/><path fill="url(#iuTSYgb)" class="o4dmaij5r"/><path fill="url(#iUrlTzQ)" class="nojp1vb8m"/><path fill="url(#iD44eqd)" class="nojp1vb8m"/><path fill="url(#iLj2LDb)" class="nojp1vb8m"/><path fill="url(#iloCZ4b)" class="nojp1vb8m"/><g filter="url(#iMvp3mf)"><ellipse fill="url(#iBov9bd)" transform="rotate(-28.298 14.857 10.546)" class="syze-50bn"/></g><g filter="url(#iWAS36d)"><circle fill="url(#imre5ld)" class="ilfphlyeh"/></g><g filter="url(#iSOQuye)"><path stroke="url(#iU8Df2b)" class="vut3h-uei"/></g><g filter="url(#ie9uMZb)"><ellipse fill="url(#iBwWkce)" transform="rotate(36.536 25.447 4.436)" class="qfeqchu9u"/></g><g filter="url(#ifNQNgc)"><ellipse fill="url(#i825Ofc)" transform="rotate(34.838 12.646 4.587)" class="ki9z_1bco"/></g><defs><radialGradient id="itngNUj" cx="0" cy="0" r="1" gradientTransform="matrix(2.46259 4.6468 -1.33678 .70843 16.566 9.04)" gradientUnits="userSpaceOnUse"><stop class="s0ufkwb8b"/><stop offset="1" class="rgd1vib-k"/></radialGradient><radialGradient id="ivphyYd" cx="0" cy="0" r="1" gradientTransform="rotate(134.423 6.23 7.834)scale(5.66681 1.1388)" gradientUnits="userSpaceOnUse"><stop class="s0ufkwb8b"/><stop offset="1" class="rgd1vib-k"/></radialGradient><radialGradient id="iNbh1Pe" cx="0" cy="0" r="1" gradientTransform="rotate(117.987 4.543 11.2)scale(4.24372 3.01145)" gradientUnits="userSpaceOnUse"><stop class="yvkhccbce"/><stop offset="1" class="tbh8158dw"/></radialGradient><radialGradient id="iyPEMeB" cx="0" cy="0" r="1" gradientTransform="rotate(91.409 4.045 8.16)scale(5.2441 12.1906)" gradientUnits="userSpaceOnUse"><stop class="z6q45nb8k"/><stop offset="1" class="c684h3qwq"/></radialGradient><radialGradient id="ilokxLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.65232 -6.96779 0 11.018 5.598)" gradientUnits="userSpaceOnUse"><stop class="s6gql-lox"/><stop offset="1" class="bht7z6b3k"/></radialGradient><radialGradient id="i4mGQgU" cx="0" cy="0" r="1" gradientTransform="rotate(161.115 3.97 4.9)scale(4.14941 1.65712)" gradientUnits="userSpaceOnUse"><stop class="knnvrdb1c"/><stop offset="1" class="me838rbhy"/></radialGradient><radialGradient id="iDUrRqe" cx="0" cy="0" r="1" gradientTransform="rotate(176.403 6.048 3.767)scale(9.02414 7.42158)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="i2copv-9c"/><stop offset=".984" class="k3smzdfzf"/></radialGradient><radialGradient id="iWXEsUr" cx="0" cy="0" r="1" gradientTransform="matrix(-14.6235 0 0 -15.2713 26.918 6.103)" gradientUnits="userSpaceOnUse"><stop class="tqwv7rbmi"/><stop offset="1" class="ogc755bvv"/></radialGradient><radialGradient id="iJGRAzb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.34375 0 0 -4.67926 26.209 5.344)" gradientUnits="userSpaceOnUse"><stop class="njp3v8brf"/><stop offset="1" class="hsvnbjb2q"/></radialGradient><radialGradient id="iSnwKMe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.12494 7.56253 -6.87037 -3.7474 13.803 10.813)" gradientUnits="userSpaceOnUse"><stop class="eem5z5bgx"/><stop offset="1" class="i1vauib5r"/></radialGradient><radialGradient id="i83S7TI" cx="0" cy="0" r="1" gradientTransform="rotate(134.668 3.559 8.484)scale(4.83983 1.45831)" gradientUnits="userSpaceOnUse"><stop class="q9pq5y0wh"/><stop offset="1" class="cfjkb2b5j"/></radialGradient><radialGradient id="iD3RlKe" cx="0" cy="0" r="1" gradientTransform="rotate(133.809 4.105 8.686)scale(2.65951 2.51637)" gradientUnits="userSpaceOnUse"><stop class="lw1yd2bzc"/><stop offset="1" class="y-c4zmzga"/></radialGradient><radialGradient id="i3Ne7kD" cx="0" cy="0" r="1" gradientTransform="matrix(-3.30218 3.17754 -5.52045 -5.737 23.235 9.707)" gradientUnits="userSpaceOnUse"><stop class="wbrhw-a3f"/><stop offset="1" class="bflrrb2kn"/></radialGradient><radialGradient id="iZ7LvCc" cx="0" cy="0" r="1" gradientTransform="matrix(1.52648 -1.68223 6.92444 6.28333 20.431 14.785)" gradientUnits="userSpaceOnUse"><stop class="u0uvrl57z"/><stop offset="1" class="mpog9pbws"/></radialGradient><radialGradient id="iHFGTec" cx="0" cy="0" r="1" gradientTransform="matrix(13.05895 7.66348 -7.0955 12.0911 13.266 7.651)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="l7e42zbzu"/><stop offset="1" class="u4d608b9y"/></radialGradient><radialGradient id="iQBosJb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.221 14.693 -1.37)scale(2.65606 1.34422)" gradientUnits="userSpaceOnUse"><stop class="hhyiprbyf"/><stop offset="1" class="obi8hkbgj"/></radialGradient><radialGradient id="iPAkBgb" cx="0" cy="0" r="1" gradientTransform="rotate(130.622 6.364 10.805)scale(2.9519 3.72501)" gradientUnits="userSpaceOnUse"><stop class="m7xkaub6o"/><stop offset="1" class="itbdozb4y"/></radialGradient><radialGradient id="i5YQwKe" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -2.16569 2.37772 .27448 17.803 15.01)" gradientUnits="userSpaceOnUse"><stop class="rrghrubou"/><stop offset="1" class="zu9od1bds"/></radialGradient><radialGradient id="iPPhuyc" cx="0" cy="0" r="1" gradientTransform="rotate(-125.655 13.432 2.517)scale(.44229 1.42759)" gradientUnits="userSpaceOnUse"><stop class="jifi4guxg"/><stop offset="1" class="dwc8e7rxl"/></radialGradient><radialGradient id="iXU08xe" cx="0" cy="0" r="1" gradientTransform="rotate(-32.905 32.292 -20.33)scale(.63276 1.04367)" gradientUnits="userSpaceOnUse"><stop class="jifi4guxg"/><stop offset="1" class="dwc8e7rxl"/></radialGradient><radialGradient id="iKo7H9L" cx="0" cy="0" r="1" gradientTransform="matrix(3.74601 -2.52168 2.23979 3.32726 16.439 14.404)" gradientUnits="userSpaceOnUse"><stop offset=".817" class="q3its-gbz"/><stop offset="1" class="s3f7e_b_x"/></radialGradient><radialGradient id="iuTSYgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.59191 -.53915 0 16.185 12.087)" gradientUnits="userSpaceOnUse"><stop class="fj6wbrn4a"/><stop offset="1" class="sycyf3r5m"/></radialGradient><radialGradient id="iUrlTzQ" cx="0" cy="0" r="1" gradientTransform="rotate(130.622 4.824 8.886)scale(2.9519 3.72501)" gradientUnits="userSpaceOnUse"><stop class="v_jz3ruoj"/><stop offset="1" class="itbdozb4y"/></radialGradient><radialGradient id="iD44eqd" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -2.16569 2.37772 .27448 13.803 13.01)" gradientUnits="userSpaceOnUse"><stop class="z0_740bym"/><stop offset="1" class="sy1ce4b2s"/></radialGradient><radialGradient id="iLj2LDb" cx="0" cy="0" r="1" gradientTransform="matrix(.125 -.39063 .89643 .28686 13.553 13.078)" gradientUnits="userSpaceOnUse"><stop class="jifi4guxg"/><stop offset="1" class="dwc8e7rxl"/></radialGradient><radialGradient id="iloCZ4b" cx="0" cy="0" r="1" gradientTransform="matrix(3.74601 -2.52168 2.23979 3.32726 12.44 12.405)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="q3its-gbz"/><stop offset="1" class="s3f7e_b_x"/></radialGradient><radialGradient id="iBov9bd" cx="0" cy="0" r="1" gradientTransform="rotate(149.172 6.21 7.271)scale(2.56438 2.68745)" gradientUnits="userSpaceOnUse"><stop class="l8iihihqc"/><stop offset="1" class="o15z220fn"/></radialGradient><radialGradient id="imre5ld" cx="0" cy="0" r="1" gradientTransform="rotate(151.44 8.08 8.627)scale(2.66467)" gradientUnits="userSpaceOnUse"><stop class="l8iihihqc"/><stop offset="1" class="o15z220fn"/></radialGradient><radialGradient id="iU8Df2b" cx="0" cy="0" r="1" gradientTransform="rotate(132.065 10.052 9.274)scale(1.72046 5.17039)" gradientUnits="userSpaceOnUse"><stop class="nbaivqvxv"/><stop offset="1" class="az5nixb_q"/></radialGradient><radialGradient id="iBwWkce" cx="0" cy="0" r="1" gradientTransform="matrix(-3.98643 -.14778 .0275 -.74194 27.526 4.224)" gradientUnits="userSpaceOnUse"><stop class="gvuxz-h-v"/><stop offset="1" class="fi40vtj0l"/></radialGradient><radialGradient id="i825Ofc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.5335 .7063 -.24777 -1.94117 15.824 4.24)" gradientUnits="userSpaceOnUse"><stop class="seat-y7nu"/><stop offset="1" class="fbajdfbma"/></radialGradient><linearGradient id="is5Jxee" x1="13.202" x2="19.169" y1="18.982" y2="18.982" gradientUnits="userSpaceOnUse"><stop class="fgwsvxs0l"/><stop offset=".385" class="sle0o82xc"/><stop offset="1" class="eih8yjtgn"/></linearGradient><linearGradient id="iBxMeJi" x1="17.747" x2="17.515" y1="10.116" y2="16.602" gradientUnits="userSpaceOnUse"><stop class="fgwsvxs0l"/><stop offset="1" class="jbrpnkbdp"/></linearGradient><linearGradient id="iCPTktS" x1="17.732" x2="20.119" y1=".853" y2="22.87" gradientUnits="userSpaceOnUse"><stop class="r7tuuvbuj"/><stop offset="1" class="vx-466eqw"/></linearGradient><linearGradient id="iwwM1ce" x1="16.054" x2="14.609" y1="8.57" y2="6.175" gradientUnits="userSpaceOnUse"><stop class="fpn960bvz"/><stop offset="1" class="jo_lu387v"/></linearGradient><linearGradient id="iEOaVxG" x1="8.747" x2="8.747" y1="8.694" y2="7.62" gradientUnits="userSpaceOnUse"><stop class="x8klxo89l"/><stop offset="1" class="dxzlvebbe"/></linearGradient><linearGradient id="iq7cjde" x1="24.959" x2="24.959" y1="9.09" y2="7.656" gradientUnits="userSpaceOnUse"><stop class="avvvvq2yl"/><stop offset="1" class="vjz02wh1m"/></linearGradient><linearGradient id="iQoCLyd" x1="11.654" x2="11.304" y1="13.568" y2="13.248" gradientUnits="userSpaceOnUse"><stop class="n9p9ibcmz"/><stop offset="1" class="qpq9-xljm"/></linearGradient><linearGradient id="imjraec" x1="15.021" x2="11.428" y1="8.625" y2="9.344" gradientUnits="userSpaceOnUse"><stop class="zily7gznb"/><stop offset="1" class="r9nou88mb"/></linearGradient><linearGradient id="iymNGse" x1="19.588" x2="20.456" y1="13.47" y2="12.603" gradientUnits="userSpaceOnUse"><stop class="uy2av3plo"/><stop offset="1" class="s_4sbejos"/></linearGradient><filter id="idvQZgb" width="3.906" height="18.357" x="15.779" y="12.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7023" stdDeviation=".75"/></filter><filter id="idbC8md" width="7.023" height="5.22" x="9.803" y="6.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7023" stdDeviation=".25"/></filter><filter id="iMvp3mf" width="3.75" height="3.841" x="12.982" y="8.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7023" stdDeviation=".5"/></filter><filter id="iWAS36d" width="3.819" height="3.819" x="16.952" y="10.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7023" stdDeviation=".5"/></filter><filter id="iSOQuye" width="6.952" height="5.127" x="19.089" y="6.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7023" stdDeviation=".25"/></filter><filter id="ie9uMZb" width="5.058" height="4.292" x="22.919" y="2.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7023" stdDeviation=".375"/></filter><filter id="ifNQNgc" width="5.541" height="4.926" x="9.876" y="2.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7023" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palm-tree" /></template>
<style>
.avvvvq2yl {
  stop-color: var(--svg-color--95a096, #95A096);
}

.az5nixb_q {
  stop-color: var(--svg-color--80b35c, #80B35C);
  stop-opacity: 0;
}

.bflrrb2kn {
  stop-color: var(--svg-color--517d2a, #517D2A);
}

.bht7z6b3k {
  stop-color: var(--svg-color--9ac644, #9AC644);
  stop-opacity: 0;
}

.c684h3qwq {
  stop-color: var(--svg-color--799d4b, #799D4B);
}

.cfjkb2b5j {
  stop-color: var(--svg-color--69785c, #69785C);
  stop-opacity: 0;
}

.dwc8e7rxl {
  stop-color: var(--svg-color--ad619b, #AD619B);
  stop-opacity: 0;
}

.dxzlvebbe {
  stop-color: var(--svg-color--9c99a6, #9C99A6);
  stop-opacity: 0;
}

.eem5z5bgx {
  stop-color: var(--svg-color--65943f, #65943F);
}

.eih8yjtgn {
  stop-color: var(--svg-color--a97270, #A97270);
}

.fbajdfbma {
  stop-color: var(--svg-color--b8e172, #B8E172);
  stop-opacity: 0;
}

.fgwsvxs0l {
  stop-color: var(--svg-color--734951, #734951);
}

.fi40vtj0l {
  stop-color: var(--svg-color--c0ef77, #C0EF77);
  stop-opacity: 0;
}

.fj6wbrn4a {
  stop-color: var(--svg-color--893e2f, #893E2F);
}

.fpn960bvz {
  stop-color: var(--svg-color--5d9501, #5D9501);
}

.ft5dv1b6b {
  fill: none;
}

.gvuxz-h-v {
  stop-color: var(--svg-color--c0ef77, #C0EF77);
}

.hhyiprbyf {
  stop-color: var(--svg-color--3e6a0c, #3E6A0C);
}

.hsvnbjb2q {
  stop-color: var(--svg-color--a3cf56, #A3CF56);
  stop-opacity: 0;
}

.i1vauib5r {
  stop-color: var(--svg-color--4c712c, #4C712C);
}

.i2copv-9c {
  stop-color: var(--svg-color--82ab5a, #82AB5A);
  stop-opacity: 0;
}

.i5n85z-bl {
  d: path("M19.17 7.969H13.2v22.03h5.97z");
}

.ilfphlyeh {
  cx: 18.862px;
  cy: 12.548px;
  r: 0.91px;
}

.itbdozb4y {
  stop-color: var(--svg-color--82582f, #82582F);
}

.jbrpnkbdp {
  stop-color: var(--svg-color--734951, #734951);
  stop-opacity: 0;
}

.jifi4guxg {
  stop-color: var(--svg-color--ad619b, #AD619B);
}

.jo_lu387v {
  stop-color: var(--svg-color--5d9501, #5D9501);
  stop-opacity: 0;
}

.k3smzdfzf {
  stop-color: var(--svg-color--82ab5a, #82AB5A);
}

.ki9z_1bco {
  cx: 12.646px;
  cy: 4.587px;
  rx: 2.271px;
  ry: 1.363px;
}

.knnvrdb1c {
  stop-color: var(--svg-color--66981b, #66981B);
}

.l7e42zbzu {
  stop-color: var(--svg-color--6c9543, #6C9543);
  stop-opacity: 0;
}

.l8iihihqc {
  stop-color: var(--svg-color--d79f87, #D79F87);
}

.lw1yd2bzc {
  stop-color: var(--svg-color--4e5e45, #4E5E45);
}

.m6e8egx8l {
  d: path("M22.16 2.09a6.164 6.164 0 0 0-6.14 5.66a.47.47 0 0 0 .48.5h11.32a.47.47 0 0 0 .48-.5a6.156 6.156 0 0 0-6.14-5.66");
}

.m7w3t5bve {
  d: path("M7.923 8.463a6.15 6.15 0 0 0-.34 8.342c.18.21.498.21.694.014l8.003-8.003a.47.47 0 0 0-.015-.693a6.17 6.17 0 0 0-8.342.34");
}

.m7xkaub6o {
  stop-color: var(--svg-color--b97056, #B97056);
}

.me838rbhy {
  stop-color: var(--svg-color--66981b, #66981B);
  stop-opacity: 0;
}

.mpog9pbws {
  stop-color: var(--svg-color--576043, #576043);
  stop-opacity: 0;
}

.n9p9ibcmz {
  stop-color: var(--svg-color--617247, #617247);
}

.nbaivqvxv {
  stop-color: var(--svg-color--80b35c, #80B35C);
}

.njp3v8brf {
  stop-color: var(--svg-color--a3cf56, #A3CF56);
}

.nojp1vb8m {
  d: path("M14.185 13.01a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.o15z220fn {
  stop-color: var(--svg-color--d79f87, #D79F87);
  stop-opacity: 0;
}

.o4dmaij5r {
  d: path("M18.185 15.01a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.oas87b1xo {
  d: path("m16.326 8.484l-2.883 2.704l-3.14-3.915c2.525-.812 4.882.133 6.023 1.211");
}

.obi8hkbgj {
  stop-color: var(--svg-color--3e6a0c, #3E6A0C);
  stop-opacity: 0;
}

.ogc755bvv {
  stop-color: var(--svg-color--679e15, #679E15);
}

.po-l-b2eq {
  d: path("M17.279 14.073h.906V29.43h-.906z");
}

.ptg2wsevi {
  d: path("M10.21 2.09a6.164 6.164 0 0 0-6.14 5.66a.47.47 0 0 0 .48.5h11.32a.47.47 0 0 0 .48-.5a6.157 6.157 0 0 0-6.14-5.66");
}

.q3its-gbz {
  stop-color: var(--svg-color--ac794f, #AC794F);
  stop-opacity: 0;
}

.q9pq5y0wh {
  stop-color: var(--svg-color--69785c, #69785C);
}

.qfeqchu9u {
  cx: 25.447px;
  cy: 4.436px;
  rx: 2.155px;
  ry: 0.683px;
}

.qpq9-xljm {
  stop-color: var(--svg-color--617247, #617247);
  stop-opacity: 0;
}

.r7tuuvbuj {
  stop-color: var(--svg-color--ae7779, #AE7779);
  stop-opacity: 0;
}

.r9nou88mb {
  stop-color: var(--svg-color--7c9d5a, #7C9D5A);
  stop-opacity: 0;
}

.rgd1vib-k {
  stop-color: var(--svg-color--4b2231, #4B2231);
  stop-opacity: 0;
}

.rrghrubou {
  stop-color: var(--svg-color--b5547d, #B5547D);
}

.s_4sbejos {
  stop-color: var(--svg-color--394b28, #394B28);
  stop-opacity: 0;
}

.s0ufkwb8b {
  stop-color: var(--svg-color--4b2231, #4B2231);
}

.s3f7e_b_x {
  stop-color: var(--svg-color--ac794f, #AC794F);
}

.s6gql-lox {
  stop-color: var(--svg-color--9ac644, #9AC644);
}

.seat-y7nu {
  stop-color: var(--svg-color--b8e172, #B8E172);
}

.sle0o82xc {
  stop-color: var(--svg-color--924f67, #924F67);
}

.sy1ce4b2s {
  stop-color: var(--svg-color--ac4d77, #AC4D77);
  stop-opacity: 0;
}

.sycyf3r5m {
  stop-color: var(--svg-color--893e2f, #893E2F);
  stop-opacity: 0;
}

.syze-50bn {
  cx: 14.857px;
  cy: 10.546px;
  rx: 0.856px;
  ry: 0.938px;
}

.tbh8158dw {
  stop-color: var(--svg-color--6c3250, #6C3250);
  stop-opacity: 0;
}

.tqwv7rbmi {
  stop-color: var(--svg-color--a3d350, #A3D350);
}

.u0uvrl57z {
  stop-color: var(--svg-color--576043, #576043);
}

.u4d608b9y {
  stop-color: var(--svg-color--6c9543, #6C9543);
}

.uy2av3plo {
  stop-color: var(--svg-color--394b28, #394B28);
}

.v_jz3ruoj {
  stop-color: var(--svg-color--aa674f, #AA674F);
}

.vjz02wh1m {
  stop-color: var(--svg-color--95a096, #95A096);
  stop-opacity: 0;
}

.vut3h-uei {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.84 7.464c1.027-.124 4.547.56 5.45 3.614");
}

.vx-466eqw {
  stop-color: var(--svg-color--b68087, #B68087);
}

.wbrhw-a3f {
  stop-color: var(--svg-color--74a550, #74A550);
}

.x8klxo89l {
  stop-color: var(--svg-color--9c99a6, #9C99A6);
}

.y-c4zmzga {
  stop-color: var(--svg-color--4e5e45, #4E5E45);
  stop-opacity: 0;
}

.yvkhccbce {
  stop-color: var(--svg-color--6c3250, #6C3250);
}

.yzfgfrbbo {
  d: path("M24.525 8.47a6.15 6.15 0 0 0-8.342-.34a.47.47 0 0 0-.014.694l8.003 8.002a.47.47 0 0 0 .692-.014a6.17 6.17 0 0 0-.339-8.342");
}

.z0_740bym {
  stop-color: var(--svg-color--ac4d77, #AC4D77);
}

.z6q45nb8k {
  stop-color: var(--svg-color--9ed141, #9ED141);
}

.zily7gznb {
  stop-color: var(--svg-color--7c9d5a, #7C9D5A);
}

.zu9od1bds {
  stop-color: var(--svg-color--b5547d, #B5547D);
  stop-opacity: 0;
}

</style>
