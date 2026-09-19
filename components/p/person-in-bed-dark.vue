<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isL7gwc)" class="jddm9tctr"/><path fill="url(#izoXaNe)" class="jddm9tctr"/><path fill="url(#iJxIRqd)" class="mmf83abgd"/><path fill="url(#iWhRu4b)" class="mmf83abgd"/><path fill="url(#iC2kHcc)" class="b5feq2trt"/><path fill="url(#ibGZYEe)" class="b5feq2trt"/><path fill="url(#iDqZRFd)" class="b5feq2trt"/><path fill="url(#i2YVihb)" class="b5feq2trt"/><path fill="url(#i9zWJSQ)" class="b5feq2trt"/><g filter="url(#iEZuICe)"><path fill="url(#iwU2Fmc)" class="by3ainbne"/><path fill="url(#iuMDS5b)" class="by3ainbne"/></g><g filter="url(#io5LEqb)"><path class="eunxegb_m"/><path fill="url(#i3Zy4Zc)" class="j5-4bzb_q"/></g><path fill="url(#irqIBHc)" class="bthh05_yc"/><path fill="url(#iyOKeWz)" class="bthh05_yc"/><g filter="url(#itPm7Ce)"><path class="oydooacgz"/></g><g filter="url(#iIgMKha)"><path class="krsb9vstl"/></g><path fill="url(#ijHWFqc)" class="mz-tmnbha"/><path fill="url(#iZAqkAe)" class="mz-tmnbha"/><path fill="url(#irMNDvd)" class="mz-tmnbha"/><path fill="url(#iwKRTOe)" class="mz-tmnbha"/><path fill="url(#it0p1Nb)" class="mz-tmnbha"/><path fill="url(#iZXJxNc)" class="mz-tmnbha"/><g filter="url(#iLuEcYd)"><path fill="url(#is3Y98N)" class="ezijx-2ny"/></g><path fill="url(#ib1qQPc)" class="bwnl49brd"/><g filter="url(#iO9gqec)"><path fill="url(#iNRcHOb)" class="rjyqpwbuq"/><path fill="url(#il7iTxc)" class="rjyqpwbuq"/><path fill="url(#iMM8byl)" class="rjyqpwbuq"/><path fill="url(#iGtHt4b)" class="rjyqpwbuq"/></g><g filter="url(#iv0RqxF)"><path fill="url(#ijkolvb)" class="k5rpxgpbq"/><path fill="url(#iTRSvOI)" class="k5rpxgpbq"/><path fill="url(#iYhlPmd)" class="k5rpxgpbq"/><path fill="url(#iUfEZId)" class="k5rpxgpbq"/></g><g filter="url(#ie0sAVd)"><path fill="url(#ijkolvb)" class="k5rpxgpbq"/><path fill="url(#iTRSvOI)" class="k5rpxgpbq"/><path fill="url(#iYhlPmd)" class="k5rpxgpbq"/><path fill="url(#iUfEZId)" class="k5rpxgpbq"/></g><path fill="url(#iaExskd)" class="lhhmeyb1f"/><path fill="url(#i5uL1rb)" class="lhhmeyb1f"/><path clip-rule="evenodd" class="j57n97o4v"/><g filter="url(#i7N4KCb)"><path clip-rule="evenodd" class="wv6ewcbsk"/></g><path class="xzi5knbju"/><g filter="url(#iE3KA5c)"><path class="ffhc8ijjk"/></g><defs><linearGradient id="isL7gwc" x1="5.919" x2="5.919" y1="27.454" y2="29.142" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="we894y8xm"/></linearGradient><linearGradient id="izoXaNe" x1="4.181" x2="4.642" y1="29.509" y2="29.509" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iJxIRqd" x1="26.818" x2="26.818" y1="27.454" y2="29.142" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="yudqmabvt"/></linearGradient><linearGradient id="iWhRu4b" x1="25.052" x2="25.52" y1="29.509" y2="29.509" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iC2kHcc" x1="14.33" x2="16.353" y1="21.111" y2="26.361" gradientUnits="userSpaceOnUse"><stop class="s50shpiqt"/><stop offset="1" class="ctq4_rb_x"/></linearGradient><linearGradient id="ibGZYEe" x1="2.439" x2="4.189" y1="26.236" y2="26.236" gradientUnits="userSpaceOnUse"><stop offset=".205" class="xxaw6lbdd"/><stop offset="1" class="znfsawb6t"/></linearGradient><linearGradient id="iDqZRFd" x1="30.267" x2="28.861" y1="25.986" y2="25.986" gradientUnits="userSpaceOnUse"><stop offset=".089" class="dzbbssbmi"/><stop offset="1" class="ihb5mw0qq"/></linearGradient><linearGradient id="i2YVihb" x1="18.58" x2="18.58" y1="27.826" y2="27.548" gradientUnits="userSpaceOnUse"><stop class="bw9bhgcag"/><stop offset="1" class="yylhrtbwl"/></linearGradient><linearGradient id="i9zWJSQ" x1="16.353" x2="16.353" y1="20.704" y2="20.908" gradientUnits="userSpaceOnUse"><stop class="yonqiacdw"/><stop offset="1" class="u7ukf0cyw"/></linearGradient><linearGradient id="iwU2Fmc" x1="11.486" x2="5.58" y1="19.954" y2="19.954" gradientUnits="userSpaceOnUse"><stop class="j_iqhtv2z"/><stop offset="1" class="lfx99ibod"/></linearGradient><linearGradient id="iuMDS5b" x1="11.705" x2="10.173" y1="20.298" y2="20.298" gradientUnits="userSpaceOnUse"><stop class="erd70ybna"/><stop offset="1" class="xrdg6g6_d"/></linearGradient><linearGradient id="i3Zy4Zc" x1="11.611" x2="9.955" y1="16.673" y2="16.673" gradientUnits="userSpaceOnUse"><stop offset=".057" class="qpqpigz0q"/><stop offset="1" class="nw5hewkux"/></linearGradient><linearGradient id="irqIBHc" x1="5.361" x2="2.439" y1="20.704" y2="20.704" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tmk_n7bre"/><stop offset="1" class="kgz9t0b5t"/></linearGradient><linearGradient id="iyOKeWz" x1="5.548" x2="4.486" y1="20.704" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="zq06kkbop"/><stop offset="1" class="atnucacjf"/></linearGradient><linearGradient id="ijHWFqc" x1="12.267" x2="29.142" y1="18.361" y2="18.361" gradientUnits="userSpaceOnUse"><stop class="oesdu5b_i"/><stop offset="1" class="yeuw1mqbz"/></linearGradient><linearGradient id="iZAqkAe" x1="11.455" x2="12.767" y1="21.017" y2="21.017" gradientUnits="userSpaceOnUse"><stop class="yx0c6y8nw"/><stop offset="1" class="fl_2tebol"/></linearGradient><linearGradient id="irMNDvd" x1="23.392" x2="23.392" y1="21.978" y2="21.54" gradientUnits="userSpaceOnUse"><stop class="kbcj9odgo"/><stop offset="1" class="gmid2kucu"/></linearGradient><linearGradient id="iwKRTOe" x1="11.275" x2="11.744" y1="18.361" y2="18.361" gradientUnits="userSpaceOnUse"><stop class="z7g_zwxuh"/><stop offset="1" class="fu6a58b1y"/></linearGradient><linearGradient id="it0p1Nb" x1="20.861" x2="20.861" y1="12.361" y2="13.548" gradientUnits="userSpaceOnUse"><stop class="gr6t18twh"/><stop offset="1" class="s8sy2oshg"/></linearGradient><linearGradient id="iNRcHOb" x1="10.383" x2="12.435" y1="12.989" y2="10.557" gradientUnits="userSpaceOnUse"><stop class="bmcblacal"/><stop offset="1" class="d0kv1cyul"/></linearGradient><linearGradient id="i5uL1rb" x1="9.642" x2="9.58" y1="12.509" y2="12.62" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><radialGradient id="iZXJxNc" cx="0" cy="0" r="1" gradientTransform="rotate(125.151 11.972 14.136)scale(6.45916 9.77416)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="tejv_ybih"/><stop offset="1" class="cf8m5rrfx"/></radialGradient><radialGradient id="is3Y98N" cx="0" cy="0" r="1" gradientTransform="matrix(-9.2187 9.56259 -16.93759 -16.32847 30.017 13.767)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ffbkz6xwn"/><stop offset="1" class="w-2pnubhf"/></radialGradient><radialGradient id="ib1qQPc" cx="0" cy="0" r="1" gradientTransform="rotate(98.308 1.97 10.426)scale(.60133 .84879)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="il7iTxc" cx="0" cy="0" r="1" gradientTransform="matrix(.51819 -.78168 .95303 .63178 9.515 12.775)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iMM8byl" cx="0" cy="0" r="1" gradientTransform="rotate(-143.279 8.07 3.42)scale(5.75711 1.56066)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iGtHt4b" cx="0" cy="0" r="1" gradientTransform="matrix(.3475 .25921 -.40424 .54192 10.93 10.966)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="ijkolvb" cx="0" cy="0" r="1" gradientTransform="rotate(165.705 3.899 6.272)scale(3.43636 5.22389)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="iTRSvOI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57495 .48726 -.7839 -2.5338 9.384 8.368)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="iYhlPmd" cx="0" cy="0" r="1" gradientTransform="matrix(.47938 -.36714 .18039 .23554 9.151 14.886)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="iUfEZId" cx="0" cy="0" r="1" gradientTransform="rotate(140.045 2.345 7.746)scale(1.01576 2.72162)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="iaExskd" cx="0" cy="0" r="1" gradientTransform="rotate(142.91 2.684 7.852)scale(.83964 .40981)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><filter id="iEZuICe" width="8.313" height="3.734" x="5.361" y="16.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.376471 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_55"/></filter><filter id="io5LEqb" width="8.313" height="3.734" x="5.361" y="13.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.266667 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_55"/></filter><filter id="itPm7Ce" width="19.127" height="9.563" x="11.265" y="13.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_55" stdDeviation=".25"/></filter><filter id="iIgMKha" width="8.547" height="8.868" x="5.618" y="8.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_55" stdDeviation=".5"/></filter><filter id="iLuEcYd" width="18.738" height="9.363" x="11.58" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_55" stdDeviation=".375"/></filter><filter id="iO9gqec" width="6.911" height="5.795" x="6.87" y="8.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.172549 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_55"/></filter><filter id="iv0RqxF" width="5.457" height="7.435" x="5.143" y="8.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.223529 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_55"/></filter><filter id="ie0sAVd" width="5.457" height="7.435" x="5.143" y="8.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.223529 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_55"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.129412 0 0 0 0 0.109804 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_55" result="effect2_innerShadow_2_55"/></filter><filter id="i7N4KCb" width=".694" height="1.087" x="9.576" y="9.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_55"/></filter><filter id="iE3KA5c" width=".779" height=".968" x="10.473" y="10.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_55" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-bed-dark" /></template>
<style>
.atnucacjf {
  stop-color: var(--svg-color--2a2356, #2A2356);
  stop-opacity: 0;
}

.b5feq2trt {
  d: path("M2.439 20.854a.15.15 0 0 1 .15-.15h27.528a.15.15 0 0 1 .15.15v6.822a.15.15 0 0 1-.15.15H2.59a.15.15 0 0 1-.15-.15z");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bthh05_yc {
  d: path("M2.439 11.4a1.46 1.46 0 0 1 2.922 0v9.304H2.539a.1.1 0 0 1-.1-.1z");
}

.bw9bhgcag {
  stop-color: var(--svg-color--481764, #481764);
}

.bwnl49brd {
  d: path("M11.987 9.952a1.1 1.1 0 0 1-.577-.074l-.12.16l1.001.747c.264-.1.45-.388.327-.605c-.104-.187-.338-.28-.63-.228");
}

.by3ainbne {
  d: path("M5.36 17.37c0-.22.18-.4.4-.4h7.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.cf8m5rrfx {
  stop-color: var(--svg-color--3173da, #3173DA);
  stop-opacity: 0;
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.ctq4_rb_x {
  stop-color: var(--svg-color--4a2160, #4A2160);
}

.d0kv1cyul {
  stop-color: var(--svg-color--5b4542, #5B4542);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dzbbssbmi {
  stop-color: var(--svg-color--4e3568, #4E3568);
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.erd70ybna {
  stop-color: var(--svg-color--6964bd, #6964BD);
}

.eunxegb_m {
  fill: var(--svg-color--2f63c0, #2F63C0);
  d: path("M5.36 14.636a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.ezijx-2ny {
  d: path("M12.33 14.067h14.437v-.6H12.33zm16.637 2.2v5.062h.6v-5.062zm-2.2-2.2a2.2 2.2 0 0 1 2.2 2.2h.6a2.8 2.8 0 0 0-2.8-2.8z");
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
}

.ffbkz6xwn {
  stop-color: var(--svg-color--5490e6, #5490E6);
}

.ffhc8ijjk {
  stroke: var(--svg-color--2f2f2f, #2F2F2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.623 10.998c.094-.028.257-.053.399-.242c.104-.14.084-.314.062-.426");
}

.fl_2tebol {
  stop-color: var(--svg-color--1f60bf, #1F60BF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fu6a58b1y {
  stop-color: var(--svg-color--1d46a7, #1D46A7);
  stop-opacity: 0;
}

.gmid2kucu {
  stop-color: var(--svg-color--1441b8, #1441B8);
  stop-opacity: 0;
}

.gr6t18twh {
  stop-color: var(--svg-color--497dba, #497DBA);
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.ihb5mw0qq {
  stop-color: var(--svg-color--4e3568, #4E3568);
  stop-opacity: 0;
}

.j_iqhtv2z {
  stop-color: var(--svg-color--817ed9, #817ED9);
}

.j5-4bzb_q {
  d: path("M5.36 14.636a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.j57n97o4v {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M11.848 11.891a.14.14 0 0 0 .158.116c.366-.057.648-.323.73-.413a.139.139 0 0 0-.204-.188c-.07.077-.298.285-.568.327a.14.14 0 0 0-.116.158");
}

.jddm9tctr {
  d: path("M4.439 26.892h2.96v2.969H4.44z");
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jp856yt_g {
  stop-color: var(--svg-color--5e4ac0, #5E4AC0);
}

.k5rpxgpbq {
  d: path("M8.789 8.085a1.14 1.14 0 0 0-1.168.492c-.528.796-.342 1.097-1 1.682c-.696.619-.921 1.011-1.013 1.43l-.001.008c-.09.413-.276 1.267 1.029 2.24c1.202.897 2.156.942 2.538.904l-.016.051c-.079.262.077.51.338.59c.223.067.49-.08.656-.393c.188-.358.32-.626.421-.838a.276.276 0 0 0-.085-.34l-.99-.737c-.417-.311-.446-.791-.424-.976c-.42-.336-.52-.616-.463-.909c.093-.485.261-.533.846-1.424c.588-.897.07-1.64-.668-1.78");
}

.kbcj9odgo {
  stop-color: var(--svg-color--1441b8, #1441B8);
}

.kgz9t0b5t {
  stop-color: var(--svg-color--32274d, #32274D);
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.krsb9vstl {
  fill: var(--svg-color--25409f, #25409F);
  d: path("M8.073 10.15c.157-.239.531-.56 1.078-.459c.448.084.809.408.85.855c.232.007.642.098 1.179.457c.168.113.362.245.566.39a1 1 0 0 0 .364.014c.27-.05.486.036.583.208c.077.136.023.303-.096.425c.486.404.287 1.533.483 1.93c.36.732-.415 1.903-2.422 1.734q-.098.197-.233.456c-.152.29-.399.427-.605.366c-.241-.073-.386-.302-.313-.544l.014-.048c-.352.037-1.235-.002-2.347-.827c-1.208-.895-.082-1.448 0-1.83l.53-.237c.084-.387-1.193-.758-.552-1.332c.355-.318.443-.545.553-.826c.077-.2.166-.426.368-.732");
}

.kun3pubeg {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
}

.lfx99ibod {
  stop-color: var(--svg-color--7f7dcb, #7F7DCB);
}

.lhhmeyb1f {
  d: path("m10.437 12.941l-1.413-.777a.806.806 0 0 0 1.413.777");
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.mmf83abgd {
  d: path("M25.314 26.892h3.008v2.969h-3.008z");
}

.mz-tmnbha {
  d: path("M11.455 12.767h15.312a3.5 3.5 0 0 1 3.5 3.5v5.325a.3.3 0 0 1-.3.3H11.855a.4.4 0 0 1-.4-.4z");
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.nw5hewkux {
  stop-color: var(--svg-color--305fb8, #305FB8);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.oesdu5b_i {
  stop-color: var(--svg-color--3071d8, #3071D8);
}

.onfzp-bwy {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
  stop-opacity: 0;
}

.oydooacgz {
  fill: var(--svg-color--321853, #321853);
  d: path("M12.142 14.142H26.59a3.293 3.293 0 0 1 3.302 3.284v4.997a.28.28 0 0 1-.283.281H12.142a.376.376 0 0 1-.377-.375z");
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.qpqpigz0q {
  stop-color: var(--svg-color--28469e, #28469E);
}

.rjyqpwbuq {
  d: path("M10.982 9.512c-.738-.497-1.254-.523-1.436-.489l-2.476 3.32l2.773 2.155c2.462.637 4.298-1.655 3.877-2.516c-.42-.86-1.883-1.894-2.738-2.47");
}

.s50shpiqt {
  stop-color: var(--svg-color--40225f, #40225F);
}

.s8sy2oshg {
  stop-color: var(--svg-color--497dba, #497DBA);
  stop-opacity: 0;
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.tejv_ybih {
  stop-color: var(--svg-color--4790dd, #4790DD);
}

.tmk_n7bre {
  stop-color: var(--svg-color--403064, #403064);
}

.u7ukf0cyw {
  stop-color: var(--svg-color--160639, #160639);
  stop-opacity: 0;
}

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.w-2pnubhf {
  stop-color: var(--svg-color--5490e6, #5490E6);
  stop-opacity: 0;
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.we894y8xm {
  stop-color: var(--svg-color--7b74d4, #7B74D4);
}

.wv6ewcbsk {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M10.094 10.26a1 1 0 0 1 .13-.203a.166.166 0 1 0-.24-.23c-.056.056-.13.161-.191.29c-.062.13-.116.297-.117.478a.166.166 0 1 0 .333.002c0-.117.036-.235.085-.337");
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xrdg6g6_d {
  stop-color: var(--svg-color--6964bd, #6964BD);
  stop-opacity: 0;
}

.xxaw6lbdd {
  stop-color: var(--svg-color--3c2c4d, #3C2C4D);
}

.xzi5knbju {
  stroke: var(--svg-color--271e22, #271E22);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M10.56 11.033c.094-.03.257-.054.399-.243c.104-.139.085-.313.063-.425");
}

.yeuw1mqbz {
  stop-color: var(--svg-color--3172d9, #3172D9);
}

.yonqiacdw {
  stop-color: var(--svg-color--160639, #160639);
}

.yudqmabvt {
  stop-color: var(--svg-color--7c75d7, #7C75D7);
}

.yx0c6y8nw {
  stop-color: var(--svg-color--1c4eb1, #1C4EB1);
}

.yylhrtbwl {
  stop-color: var(--svg-color--481764, #481764);
  stop-opacity: 0;
}

.z7g_zwxuh {
  stop-color: var(--svg-color--0b3081, #0B3081);
}

.znfsawb6t {
  stop-color: var(--svg-color--3c2c4d, #3C2C4D);
  stop-opacity: 0;
}

.zq06kkbop {
  stop-color: var(--svg-color--0d0426, #0D0426);
}

</style>
