<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isL7gwc)" class="jddm9tctr"/><path fill="url(#izoXaNe)" class="jddm9tctr"/><path fill="url(#iJxIRqd)" class="mmf83abgd"/><path fill="url(#iWhRu4b)" class="mmf83abgd"/><path fill="url(#iC2kHcc)" class="b5feq2trt"/><path fill="url(#ibGZYEe)" class="b5feq2trt"/><path fill="url(#iDqZRFd)" class="b5feq2trt"/><path fill="url(#i2YVihb)" class="b5feq2trt"/><path fill="url(#iLZLVBb)" class="b5feq2trt"/><g filter="url(#iPJ6yiJ)"><path fill="url(#iwU2Fmc)" class="by3ainbne"/><path fill="url(#iuMDS5b)" class="by3ainbne"/></g><g filter="url(#iGt526b)"><path class="eunxegb_m"/><path fill="url(#i3Zy4Zc)" class="j5-4bzb_q"/></g><path fill="url(#irqIBHc)" class="bthh05_yc"/><path fill="url(#iyOKeWz)" class="bthh05_yc"/><g filter="url(#iuH4wyd)"><path class="oydooacgz"/></g><g filter="url(#ijgz87b)"><path class="krsb9vstl"/></g><path fill="url(#ijHWFqc)" class="mz-tmnbha"/><path fill="url(#iZAqkAe)" class="mz-tmnbha"/><path fill="url(#irMNDvd)" class="mz-tmnbha"/><path fill="url(#iwKRTOe)" class="mz-tmnbha"/><path fill="url(#it0p1Nb)" class="mz-tmnbha"/><path fill="url(#iZXJxNc)" class="mz-tmnbha"/><g filter="url(#izulYcd)"><path fill="url(#is3Y98N)" class="ezijx-2ny"/></g><path fill="url(#ieMBn5b)" class="fi4u7obyw"/><path fill="url(#ic8lvqe)" class="fi4u7obyw"/><g filter="url(#i248Vne)"><path fill="url(#i53qtNe)" class="kk6eiiu8j"/><path fill="url(#iS7v9fe)" class="kk6eiiu8j"/><path fill="url(#ikAB5Tc)" class="kk6eiiu8j"/><path fill="url(#izVEWwd)" class="kk6eiiu8j"/></g><g filter="url(#i872Z9c)"><path fill="url(#im5jibd)" class="i-ndh-byx"/><path fill="url(#iTeeNte)" class="i-ndh-byx"/><path fill="url(#iiQWn0b)" class="i-ndh-byx"/><path fill="url(#in11e8l)" class="i-ndh-byx"/></g><path fill="url(#ifQ5N2c)" class="xjhgekhzp"/><path fill="url(#iZ9PWjb)" class="xjhgekhzp"/><path fill="url(#iIsINed)" class="xjhgekhzp"/><path clip-rule="evenodd" class="gexrbwbqs"/><g filter="url(#ie5CYNc)"><path clip-rule="evenodd" class="zvhegdavw"/></g><path class="xzi5knbju"/><g filter="url(#iyVr6pb)"><path class="ffhc8ijjk"/></g><defs><linearGradient id="isL7gwc" x1="5.919" x2="5.919" y1="27.454" y2="29.142" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="we894y8xm"/></linearGradient><linearGradient id="izoXaNe" x1="4.181" x2="4.642" y1="29.509" y2="29.509" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iJxIRqd" x1="26.818" x2="26.818" y1="27.454" y2="29.142" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="yudqmabvt"/></linearGradient><linearGradient id="iWhRu4b" x1="25.052" x2="25.52" y1="29.509" y2="29.509" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iC2kHcc" x1="14.33" x2="16.353" y1="21.111" y2="26.361" gradientUnits="userSpaceOnUse"><stop class="s50shpiqt"/><stop offset="1" class="ctq4_rb_x"/></linearGradient><linearGradient id="ibGZYEe" x1="2.439" x2="4.189" y1="26.236" y2="26.236" gradientUnits="userSpaceOnUse"><stop offset=".205" class="xxaw6lbdd"/><stop offset="1" class="znfsawb6t"/></linearGradient><linearGradient id="iDqZRFd" x1="30.267" x2="28.861" y1="25.986" y2="25.986" gradientUnits="userSpaceOnUse"><stop offset=".089" class="dzbbssbmi"/><stop offset="1" class="ihb5mw0qq"/></linearGradient><linearGradient id="i2YVihb" x1="18.58" x2="18.58" y1="27.826" y2="27.548" gradientUnits="userSpaceOnUse"><stop class="bw9bhgcag"/><stop offset="1" class="yylhrtbwl"/></linearGradient><linearGradient id="iLZLVBb" x1="16.353" x2="16.353" y1="20.704" y2="20.907" gradientUnits="userSpaceOnUse"><stop class="yonqiacdw"/><stop offset="1" class="u7ukf0cyw"/></linearGradient><linearGradient id="iwU2Fmc" x1="11.486" x2="5.58" y1="19.954" y2="19.954" gradientUnits="userSpaceOnUse"><stop class="j_iqhtv2z"/><stop offset="1" class="lfx99ibod"/></linearGradient><linearGradient id="iuMDS5b" x1="11.705" x2="10.173" y1="20.298" y2="20.298" gradientUnits="userSpaceOnUse"><stop class="erd70ybna"/><stop offset="1" class="xrdg6g6_d"/></linearGradient><linearGradient id="i3Zy4Zc" x1="11.611" x2="9.955" y1="16.673" y2="16.673" gradientUnits="userSpaceOnUse"><stop offset=".057" class="qpqpigz0q"/><stop offset="1" class="nw5hewkux"/></linearGradient><linearGradient id="irqIBHc" x1="5.361" x2="2.439" y1="20.704" y2="20.704" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tmk_n7bre"/><stop offset="1" class="kgz9t0b5t"/></linearGradient><linearGradient id="iyOKeWz" x1="5.548" x2="4.486" y1="20.704" y2="20.704" gradientUnits="userSpaceOnUse"><stop class="zq06kkbop"/><stop offset="1" class="atnucacjf"/></linearGradient><linearGradient id="ijHWFqc" x1="12.267" x2="29.142" y1="18.361" y2="18.361" gradientUnits="userSpaceOnUse"><stop class="oesdu5b_i"/><stop offset="1" class="yeuw1mqbz"/></linearGradient><linearGradient id="iZAqkAe" x1="11.455" x2="12.767" y1="21.017" y2="21.017" gradientUnits="userSpaceOnUse"><stop class="yx0c6y8nw"/><stop offset="1" class="fl_2tebol"/></linearGradient><linearGradient id="irMNDvd" x1="23.392" x2="23.392" y1="21.978" y2="21.54" gradientUnits="userSpaceOnUse"><stop class="kbcj9odgo"/><stop offset="1" class="gmid2kucu"/></linearGradient><linearGradient id="iwKRTOe" x1="11.275" x2="11.744" y1="18.361" y2="18.361" gradientUnits="userSpaceOnUse"><stop class="z7g_zwxuh"/><stop offset="1" class="fu6a58b1y"/></linearGradient><linearGradient id="it0p1Nb" x1="20.861" x2="20.861" y1="12.361" y2="13.548" gradientUnits="userSpaceOnUse"><stop class="gr6t18twh"/><stop offset="1" class="s8sy2oshg"/></linearGradient><linearGradient id="i53qtNe" x1="10.419" x2="12.47" y1="13.001" y2="10.593" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="iIsINed" x1="9.7" x2="9.612" y1="12.505" y2="12.644" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><radialGradient id="iZXJxNc" cx="0" cy="0" r="1" gradientTransform="rotate(125.151 11.972 14.136)scale(6.45916 9.77416)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="tejv_ybih"/><stop offset="1" class="cf8m5rrfx"/></radialGradient><radialGradient id="is3Y98N" cx="0" cy="0" r="1" gradientTransform="matrix(-9.2187 9.56259 -16.93759 -16.32847 30.017 13.767)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ffbkz6xwn"/><stop offset="1" class="w-2pnubhf"/></radialGradient><radialGradient id="ieMBn5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.08925 .59102 -.83425 -.12598 12.608 10.024)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="ic8lvqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.17713 -.29931 .4492 -.26583 12.62 10.592)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iS7v9fe" cx="0" cy="0" r="1" gradientTransform="matrix(.51887 -.77448 .94425 .6326 9.557 12.784)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="ikAB5Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5703 -3.44396 1.33817 -1.7758 12.526 11.02)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="izVEWwd" cx="0" cy="0" r="1" gradientTransform="rotate(37 -10.94 21.892)scale(.43092 .67203)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="im5jibd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.31409 .82728 -1.25761 -5.03802 9.277 11.404)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="iTeeNte" cx="0" cy="0" r="1" gradientTransform="rotate(163.088 4.1 4.904)scale(1.63873 2.63641)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="iiQWn0b" cx="0" cy="0" r="1" gradientTransform="matrix(.47829 -.36261 .17817 .235 9.186 14.88)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="in11e8l" cx="0" cy="0" r="1" gradientTransform="matrix(-.77713 .64461 -1.72716 -2.08223 9.165 12.188)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="ifQ5N2c" cx="0" cy="0" r="1" gradientTransform="rotate(143.189 2.72 7.852)scale(.83461 .40736)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iZ9PWjb" cx="0" cy="0" r="1" gradientTransform="matrix(.88937 .9823 -1.0236 .92676 9.318 12.336)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><filter id="iPJ6yiJ" width="8.313" height="3.734" x="5.361" y="16.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.376471 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_132"/></filter><filter id="iGt526b" width="8.313" height="3.734" x="5.361" y="13.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.266667 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_132"/></filter><filter id="iuH4wyd" width="19.127" height="9.563" x="11.265" y="13.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_132" stdDeviation=".25"/></filter><filter id="ijgz87b" width="8.547" height="8.868" x="5.618" y="8.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_132" stdDeviation=".5"/></filter><filter id="izulYcd" width="18.738" height="9.363" x="11.58" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_132" stdDeviation=".375"/></filter><filter id="i248Vne" width="6.871" height="5.767" x="6.929" y="8.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.619608 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_132"/></filter><filter id="i872Z9c" width="5.017" height="7.545" x="5.612" y="7.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_132"/></filter><filter id="ie5CYNc" width=".694" height="1.081" x="9.628" y="9.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_132"/></filter><filter id="iyVr6pb" width=".779" height=".968" x="10.473" y="10.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_132" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-bed-light" /></template>
<style>
.atnucacjf {
  stop-color: var(--svg-color--2a2356, #2A2356);
  stop-opacity: 0;
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.b5feq2trt {
  d: path("M2.439 20.854a.15.15 0 0 1 .15-.15h27.528a.15.15 0 0 1 .15.15v6.822a.15.15 0 0 1-.15.15H2.59a.15.15 0 0 1-.15-.15z");
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bthh05_yc {
  d: path("M2.439 11.4a1.46 1.46 0 0 1 2.922 0v9.304H2.539a.1.1 0 0 1-.1-.1z");
}

.bw9bhgcag {
  stop-color: var(--svg-color--481764, #481764);
}

.by3ainbne {
  d: path("M5.36 17.37c0-.22.18-.4.4-.4h7.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.cf8m5rrfx {
  stop-color: var(--svg-color--3173da, #3173DA);
  stop-opacity: 0;
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.ctq4_rb_x {
  stop-color: var(--svg-color--4a2160, #4A2160);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
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

.ffbkz6xwn {
  stop-color: var(--svg-color--5490e6, #5490E6);
}

.ffhc8ijjk {
  stroke: var(--svg-color--2f2f2f, #2F2F2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.623 10.998c.094-.028.257-.053.399-.242c.104-.14.084-.314.062-.426");
}

.fi4u7obyw {
  d: path("M12.03 9.99c-.233.04-.48-.034-.574-.076l-.12.158l.992.747c.263-.099.448-.384.328-.6c-.103-.186-.335-.28-.626-.229");
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

.gexrbwbqs {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M11.88 11.917a.14.14 0 0 0 .157.116c.365-.054.646-.318.729-.407a.138.138 0 0 0-.203-.188c-.07.076-.297.282-.567.322a.14.14 0 0 0-.116.157");
}

.gmid2kucu {
  stop-color: var(--svg-color--1441b8, #1441B8);
  stop-opacity: 0;
}

.gr6t18twh {
  stop-color: var(--svg-color--497dba, #497DBA);
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i-ndh-byx {
  d: path("M8.859 8.119a1.13 1.13 0 0 0-1.163.483c-.53.788-.345 1.089-1.002 1.667c-.695.611-.921 1-1.014 1.416l-.002.008c-.091.41-.28 1.258 1.012 2.232c1.191.897 2.14.946 2.52.91l-.017.052c-.08.26.074.507.334.587c.221.069.487-.076.653-.387c.19-.355.321-.62.423-.83a.274.274 0 0 0-.083-.338l-.98-.74a1.09 1.09 0 0 1-.417-.971c-.416-.336-.514-.614-.457-.905c.096-.483.263-.529.848-1.412c.59-.889.079-1.63-.655-1.772");
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.ihb5mw0qq {
  stop-color: var(--svg-color--4e3568, #4E3568);
  stop-opacity: 0;
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.j_iqhtv2z {
  stop-color: var(--svg-color--817ed9, #817ED9);
}

.j5-4bzb_q {
  d: path("M5.36 14.636a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
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

.kbcj9odgo {
  stop-color: var(--svg-color--1441b8, #1441B8);
}

.kgz9t0b5t {
  stop-color: var(--svg-color--32274d, #32274D);
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.kk6eiiu8j {
  d: path("M11.032 9.547c-.732-.498-1.244-.525-1.425-.493l-2.478 3.289l2.746 2.155c2.444.645 4.28-1.625 3.867-2.482s-1.864-1.892-2.71-2.469");
}

.krsb9vstl {
  fill: var(--svg-color--25409f, #25409F);
  d: path("M8.073 10.15c.157-.239.531-.56 1.078-.459c.448.084.809.408.85.855c.232.007.642.098 1.179.457c.168.113.362.245.566.39a1 1 0 0 0 .364.014c.27-.05.486.036.583.208c.077.136.023.303-.096.425c.486.404.287 1.533.483 1.93c.36.732-.415 1.903-2.422 1.734q-.098.197-.233.456c-.152.29-.399.427-.605.366c-.241-.073-.386-.302-.313-.544l.014-.048c-.352.037-1.235-.002-2.347-.827c-1.208-.895-.082-1.448 0-1.83l.53-.237c.084-.387-1.193-.758-.552-1.332c.355-.318.443-.545.553-.826c.077-.2.166-.426.368-.732");
}

.kun3pubeg {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lfx99ibod {
  stop-color: var(--svg-color--7f7dcb, #7F7DCB);
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

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
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

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.qpqpigz0q {
  stop-color: var(--svg-color--28469e, #28469E);
}

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.s50shpiqt {
  stop-color: var(--svg-color--40225f, #40225F);
}

.s8sy2oshg {
  stop-color: var(--svg-color--497dba, #497DBA);
  stop-opacity: 0;
}

.tejv_ybih {
  stop-color: var(--svg-color--4790dd, #4790DD);
}

.tmk_n7bre {
  stop-color: var(--svg-color--403064, #403064);
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u7ukf0cyw {
  stop-color: var(--svg-color--160639, #160639);
  stop-opacity: 0;
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.w-2pnubhf {
  stop-color: var(--svg-color--5490e6, #5490E6);
  stop-opacity: 0;
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.we894y8xm {
  stop-color: var(--svg-color--7b74d4, #7B74D4);
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.xjhgekhzp {
  d: path("m10.474 12.954l-1.4-.78a.802.802 0 0 0 1.4.78");
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

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.znfsawb6t {
  stop-color: var(--svg-color--3c2c4d, #3C2C4D);
  stop-opacity: 0;
}

.zq06kkbop {
  stop-color: var(--svg-color--0d0426, #0D0426);
}

.zvhegdavw {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M10.145 10.287a1 1 0 0 1 .13-.202a.166.166 0 1 0-.238-.23c-.055.056-.13.16-.19.288c-.063.13-.118.296-.12.475a.166.166 0 0 0 .332.003a.8.8 0 0 1 .086-.334");
}

</style>
