<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i1geOcc)" class="jbftd1byo"/><path fill="url(#iIKm7Ob)" class="jbftd1byo"/><path fill="url(#iR232Kd)" class="bqvma2bfx"/><path fill="url(#iyDyq2d)" class="bqvma2bfx"/><path fill="url(#i14b1zd)" class="uoeftxp7k"/><path fill="url(#iS237Fe)" class="uoeftxp7k"/><path fill="url(#iHFPupe)" class="uoeftxp7k"/><path fill="url(#iOGlSbb)" class="uoeftxp7k"/><path fill="url(#iblvdKe)" class="uoeftxp7k"/><g filter="url(#iaJxwbb)"><path fill="url(#iIXhxih)" class="rmdvovbqy"/><path fill="url(#iSzpG9b)" class="rmdvovbqy"/></g><g filter="url(#i1L7U6c)"><path class="bd2w7rblm"/><path fill="url(#iwDL4zd)" class="p01sf_8pt"/></g><path fill="url(#iGvkood)" class="v1-ucdd8u"/><path fill="url(#iUUEsAe)" class="v1-ucdd8u"/><g filter="url(#i8WJwje)"><path class="lnyyum7gn"/></g><g filter="url(#iVQOuCd)"><path class="nwbx8xjmz"/></g><path fill="url(#i5veFze)" class="mrj5_jblj"/><path fill="url(#iH6fucb)" class="mrj5_jblj"/><path fill="url(#iadRwgb)" class="mrj5_jblj"/><path fill="url(#i3MNy2c)" class="mrj5_jblj"/><path fill="url(#iKvazMe)" class="mrj5_jblj"/><path fill="url(#iyIfbme)" class="mrj5_jblj"/><g filter="url(#iTbEspb)"><path fill="url(#ijxuCHc)" class="fsu2zvbda"/></g><path fill="url(#iDfzEUc)" class="r65pqhb_a"/><g filter="url(#iEdWonb)"><path fill="url(#idD85Hd)" class="vzh3oj5bk"/><path fill="url(#iqufxGd)" class="vzh3oj5bk"/><path fill="url(#imzFkFA)" class="vzh3oj5bk"/><path fill="url(#ipVeoAd)" class="vzh3oj5bk"/></g><g filter="url(#ilCVvEc)"><path fill="url(#iik8VDS)" class="vw4hmzxuv"/><path fill="url(#isgzIfd)" class="vw4hmzxuv"/><path fill="url(#igHHNxe)" class="vw4hmzxuv"/><path fill="url(#iNCkGRc)" class="vw4hmzxuv"/></g><path fill="url(#iQIKWzb)" class="g1y9vvb0u"/><path fill="url(#i8Oz1Re)" class="g1y9vvb0u"/><path fill="url(#iDMCEkc)" class="g1y9vvb0u"/><path clip-rule="evenodd" class="qj9i__bkr"/><g filter="url(#iZsEfke)"><path clip-rule="evenodd" class="j2yok5bap"/></g><path class="yozp8vswl"/><g filter="url(#ivRRRre)"><path class="l9wb0otcj"/></g><defs><linearGradient id="i1geOcc" x1="5.919" x2="5.919" y1="27.746" y2="29.434" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="we894y8xm"/></linearGradient><linearGradient id="iIKm7Ob" x1="4.181" x2="4.642" y1="29.801" y2="29.801" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iR232Kd" x1="26.818" x2="26.818" y1="27.746" y2="29.434" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="yudqmabvt"/></linearGradient><linearGradient id="iyDyq2d" x1="25.052" x2="25.52" y1="29.801" y2="29.801" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="i14b1zd" x1="14.33" x2="16.353" y1="21.403" y2="26.653" gradientUnits="userSpaceOnUse"><stop class="s50shpiqt"/><stop offset="1" class="ctq4_rb_x"/></linearGradient><linearGradient id="iS237Fe" x1="2.439" x2="4.189" y1="26.528" y2="26.528" gradientUnits="userSpaceOnUse"><stop offset=".205" class="xxaw6lbdd"/><stop offset="1" class="znfsawb6t"/></linearGradient><linearGradient id="iHFPupe" x1="30.267" x2="28.861" y1="26.278" y2="26.278" gradientUnits="userSpaceOnUse"><stop offset=".089" class="dzbbssbmi"/><stop offset="1" class="ihb5mw0qq"/></linearGradient><linearGradient id="iOGlSbb" x1="18.58" x2="18.58" y1="28.117" y2="27.84" gradientUnits="userSpaceOnUse"><stop class="bw9bhgcag"/><stop offset="1" class="yylhrtbwl"/></linearGradient><linearGradient id="iblvdKe" x1="16.353" x2="16.353" y1="20.996" y2="21.2" gradientUnits="userSpaceOnUse"><stop class="yonqiacdw"/><stop offset="1" class="u7ukf0cyw"/></linearGradient><linearGradient id="iIXhxih" x1="11.486" x2="5.58" y1="20.246" y2="20.246" gradientUnits="userSpaceOnUse"><stop class="j_iqhtv2z"/><stop offset="1" class="lfx99ibod"/></linearGradient><linearGradient id="iSzpG9b" x1="11.705" x2="10.173" y1="20.59" y2="20.59" gradientUnits="userSpaceOnUse"><stop class="erd70ybna"/><stop offset="1" class="xrdg6g6_d"/></linearGradient><linearGradient id="iwDL4zd" x1="11.611" x2="9.955" y1="16.965" y2="16.965" gradientUnits="userSpaceOnUse"><stop offset=".057" class="qpqpigz0q"/><stop offset="1" class="nw5hewkux"/></linearGradient><linearGradient id="iGvkood" x1="5.361" x2="2.439" y1="20.996" y2="20.996" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tmk_n7bre"/><stop offset="1" class="kgz9t0b5t"/></linearGradient><linearGradient id="iUUEsAe" x1="5.548" x2="4.486" y1="20.996" y2="20.996" gradientUnits="userSpaceOnUse"><stop class="zq06kkbop"/><stop offset="1" class="atnucacjf"/></linearGradient><linearGradient id="i5veFze" x1="12.267" x2="29.142" y1="18.653" y2="18.653" gradientUnits="userSpaceOnUse"><stop class="oesdu5b_i"/><stop offset="1" class="yeuw1mqbz"/></linearGradient><linearGradient id="iH6fucb" x1="11.455" x2="12.767" y1="21.309" y2="21.309" gradientUnits="userSpaceOnUse"><stop class="yx0c6y8nw"/><stop offset="1" class="fl_2tebol"/></linearGradient><linearGradient id="iadRwgb" x1="23.392" x2="23.392" y1="22.27" y2="21.832" gradientUnits="userSpaceOnUse"><stop class="kbcj9odgo"/><stop offset="1" class="gmid2kucu"/></linearGradient><linearGradient id="i3MNy2c" x1="11.275" x2="11.744" y1="18.653" y2="18.653" gradientUnits="userSpaceOnUse"><stop class="z7g_zwxuh"/><stop offset="1" class="fu6a58b1y"/></linearGradient><linearGradient id="iKvazMe" x1="20.861" x2="20.861" y1="12.653" y2="13.84" gradientUnits="userSpaceOnUse"><stop class="gr6t18twh"/><stop offset="1" class="s8sy2oshg"/></linearGradient><linearGradient id="idD85Hd" x1="10.345" x2="12.453" y1="13.271" y2="10.839" gradientUnits="userSpaceOnUse"><stop class="co18c5bwy"/><stop offset="1" class="kj_uw-bok"/></linearGradient><linearGradient id="iDMCEkc" x1="9.621" x2="9.498" y1="12.696" y2="13" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><radialGradient id="iyIfbme" cx="0" cy="0" r="1" gradientTransform="rotate(125.151 11.897 14.282)scale(6.45916 9.77416)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="tejv_ybih"/><stop offset="1" class="cf8m5rrfx"/></radialGradient><radialGradient id="ijxuCHc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.2187 9.56259 -16.93759 -16.32847 30.017 14.059)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ffbkz6xwn"/><stop offset="1" class="w-2pnubhf"/></radialGradient><radialGradient id="iDfzEUc" cx="0" cy="0" r="1" gradientTransform="rotate(99.058 1.922 10.505)scale(.60813 .85841)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="n304-r4kd"/><stop offset=".684" class="uk3jx7nau"/></radialGradient><radialGradient id="iqufxGd" cx="0" cy="0" r="1" gradientTransform="matrix(.53435 -.7836 .95537 .65148 9.47 13.043)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jijo4-b9s"/><stop offset="1" class="ni_rkbnps"/></radialGradient><radialGradient id="imzFkFA" cx="0" cy="0" r="1" gradientTransform="rotate(-142.529 8.165 3.516)scale(5.82229 1.57833)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="dd9hd6bwg"/><stop offset="1" class="aw2d6h33n"/></radialGradient><radialGradient id="ipVeoAd" cx="0" cy="0" r="1" gradientTransform="matrix(.34796 .26671 -.41595 .54267 10.924 11.232)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jynvl5b3k"/><stop offset="1" class="b-jom1b0d"/></radialGradient><radialGradient id="iik8VDS" cx="0" cy="0" r="1" gradientTransform="rotate(166.454 3.908 6.364)scale(3.47527 5.28303)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="my1ob8bzv"/><stop offset="1" class="eys4t1u9r"/></radialGradient><radialGradient id="isgzIfd" cx="0" cy="0" r="1" gradientTransform="rotate(163.559 4.078 4.97)scale(1.66727 2.68232)" gradientUnits="userSpaceOnUse"><stop class="bd_cirbzn"/><stop offset="1" class="u8iayhb4j"/></radialGradient><radialGradient id="igHHNxe" cx="0" cy="0" r="1" gradientTransform="matrix(.48963 -.36492 .1793 .24057 9.075 15.173)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="e4cf86x4h"/><stop offset="1" class="dar5wrbvj"/></radialGradient><radialGradient id="iNCkGRc" cx="0" cy="0" r="1" gradientTransform="rotate(140.795 2.324 7.833)scale(1.02726 2.75243)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="iQIKWzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.684 .50318 -.2456 -.33385 9.52 12.762)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="i8Oz1Re" cx="0" cy="0" r="1" gradientTransform="matrix(.89662 1.0068 -1.04914 .93431 9.23 12.585)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><filter id="iaJxwbb" width="8.313" height="3.734" x="5.361" y="17.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.376471 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_75"/></filter><filter id="i1L7U6c" width="8.313" height="3.734" x="5.361" y="13.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.266667 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_75"/></filter><filter id="i8WJwje" width="19.127" height="9.563" x="11.265" y="13.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_75" stdDeviation=".25"/></filter><filter id="iVQOuCd" width="8.547" height="8.868" x="5.618" y="8.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_75" stdDeviation=".5"/></filter><filter id="iTbEspb" width="18.738" height="9.363" x="11.58" y="13.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_75" stdDeviation=".375"/></filter><filter id="iEdWonb" width="6.987" height="5.872" x="6.804" y="9.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.25098 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_75"/></filter><filter id="ilCVvEc" width="5.088" height="7.682" x="5.462" y="8.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0509804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_75"/></filter><filter id="iZsEfke" width=".709" height="1.095" x="9.562" y="10.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_75"/></filter><filter id="ivRRRre" width=".779" height=".968" x="10.473" y="10.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_75" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-bed-medium-dark" /></template>
<style>
.atnucacjf {
  stop-color: var(--svg-color--2a2356, #2A2356);
  stop-opacity: 0;
}

.aw2d6h33n {
  stop-color: var(--svg-color--9a7468, #9A7468);
  stop-opacity: 0;
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-jom1b0d {
  stop-color: var(--svg-color--845a4e, #845A4E);
  stop-opacity: 0;
}

.bd_cirbzn {
  stop-color: var(--svg-color--514342, #514342);
}

.bd2w7rblm {
  fill: var(--svg-color--2f63c0, #2F63C0);
  d: path("M5.36 14.928a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.bqvma2bfx {
  d: path("M25.314 27.184h3.008v2.969h-3.008z");
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.bw9bhgcag {
  stop-color: var(--svg-color--481764, #481764);
}

.cf8m5rrfx {
  stop-color: var(--svg-color--3173da, #3173DA);
  stop-opacity: 0;
}

.co18c5bwy {
  stop-color: var(--svg-color--825756, #825756);
}

.ctq4_rb_x {
  stop-color: var(--svg-color--4a2160, #4A2160);
}

.dar5wrbvj {
  stop-color: var(--svg-color--3f3438, #3F3438);
  stop-opacity: 0;
}

.dd9hd6bwg {
  stop-color: var(--svg-color--9d726c, #9D726C);
}

.dzbbssbmi {
  stop-color: var(--svg-color--4e3568, #4E3568);
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e4cf86x4h {
  stop-color: var(--svg-color--3f3438, #3F3438);
}

.erd70ybna {
  stop-color: var(--svg-color--6964bd, #6964BD);
}

.eys4t1u9r {
  stop-color: var(--svg-color--3d2d32, #3D2D32);
}

.ffbkz6xwn {
  stop-color: var(--svg-color--5490e6, #5490E6);
}

.fl_2tebol {
  stop-color: var(--svg-color--1f60bf, #1F60BF);
  stop-opacity: 0;
}

.fsu2zvbda {
  d: path("M12.33 14.359h14.437v-.6H12.33zm16.637 2.2v5.062h.6V16.56zm-2.2-2.2a2.2 2.2 0 0 1 2.2 2.2h.6a2.8 2.8 0 0 0-2.8-2.8z");
}

.ft5dv1b6b {
  fill: none;
}

.fu6a58b1y {
  stop-color: var(--svg-color--1d46a7, #1D46A7);
  stop-opacity: 0;
}

.g1y9vvb0u {
  d: path("m10.401 13.224l-1.418-.806a.816.816 0 0 0 1.418.806");
}

.gmid2kucu {
  stop-color: var(--svg-color--1441b8, #1441B8);
  stop-opacity: 0;
}

.gr6t18twh {
  stop-color: var(--svg-color--497dba, #497DBA);
}

.ihb5mw0qq {
  stop-color: var(--svg-color--4e3568, #4E3568);
  stop-opacity: 0;
}

.j_iqhtv2z {
  stop-color: var(--svg-color--817ed9, #817ED9);
}

.j2yok5bap {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M10.089 10.507a1 1 0 0 1 .134-.203a.168.168 0 0 0-.24-.237a1.2 1.2 0 0 0-.196.292c-.065.13-.122.299-.125.482a.168.168 0 1 0 .337.006a.8.8 0 0 1 .09-.34");
}

.jbftd1byo {
  d: path("M4.439 27.184h2.96v2.969H4.44z");
}

.jijo4-b9s {
  stop-color: var(--svg-color--794b40, #794B40);
}

.jp856yt_g {
  stop-color: var(--svg-color--5e4ac0, #5E4AC0);
}

.jynvl5b3k {
  stop-color: var(--svg-color--845a4e, #845A4E);
}

.kbcj9odgo {
  stop-color: var(--svg-color--1441b8, #1441B8);
}

.kgz9t0b5t {
  stop-color: var(--svg-color--32274d, #32274D);
}

.kj_uw-bok {
  stop-color: var(--svg-color--875d51, #875D51);
}

.kun3pubeg {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
}

.l9wb0otcj {
  stroke: var(--svg-color--2f2f2f, #2F2F2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.623 11.29c.094-.028.257-.053.399-.242c.104-.14.084-.314.062-.426");
}

.lfx99ibod {
  stop-color: var(--svg-color--7f7dcb, #7F7DCB);
}

.lnyyum7gn {
  fill: var(--svg-color--321853, #321853);
  d: path("M12.142 14.434H26.59a3.293 3.293 0 0 1 3.302 3.284v4.997a.28.28 0 0 1-.283.281H12.142a.376.376 0 0 1-.377-.375z");
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.mrj5_jblj {
  d: path("M11.455 13.059h15.312a3.5 3.5 0 0 1 3.5 3.5v5.325a.3.3 0 0 1-.3.3H11.855a.4.4 0 0 1-.4-.4z");
}

.my1ob8bzv {
  stop-color: var(--svg-color--301f27, #301F27);
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
}

.ni_rkbnps {
  stop-color: var(--svg-color--794b40, #794B40);
  stop-opacity: 0;
}

.nw5hewkux {
  stop-color: var(--svg-color--305fb8, #305FB8);
  stop-opacity: 0;
}

.nwbx8xjmz {
  fill: var(--svg-color--25409f, #25409F);
  d: path("M8.073 10.442c.157-.239.531-.56 1.078-.459c.448.084.809.408.85.855c.232.007.642.098 1.179.457c.168.113.362.245.566.39a1 1 0 0 0 .364.014c.27-.05.486.036.583.208c.077.136.023.303-.096.425c.486.403.287 1.533.483 1.93c.36.732-.415 1.903-2.422 1.734q-.098.197-.233.456c-.152.29-.399.427-.605.365c-.241-.072-.386-.301-.313-.543l.014-.048c-.352.037-1.235-.002-2.347-.827c-1.208-.895-.082-1.448 0-1.83l.53-.237c.084-.387-1.193-.758-.552-1.332c.355-.318.443-.545.553-.826c.077-.2.166-.426.368-.732");
}

.oesdu5b_i {
  stop-color: var(--svg-color--3071d8, #3071D8);
}

.onfzp-bwy {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
  stop-opacity: 0;
}

.p01sf_8pt {
  d: path("M5.36 14.928a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.qj9i__bkr {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M11.842 12.18a.14.14 0 0 0 .158.12c.371-.053.66-.32.744-.409a.14.14 0 1 0-.204-.193c-.072.077-.305.285-.58.324a.14.14 0 0 0-.118.158");
}

.qpqpigz0q {
  stop-color: var(--svg-color--28469e, #28469E);
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.r65pqhb_a {
  d: path("M12.01 10.221a1.1 1.1 0 0 1-.584-.082l-.123.16l1.003.768c.268-.098.459-.386.338-.608c-.103-.19-.338-.286-.635-.238");
}

.rmdvovbqy {
  d: path("M5.36 17.662c0-.22.18-.4.4-.4h7.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
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

.u7ukf0cyw {
  stop-color: var(--svg-color--160639, #160639);
  stop-opacity: 0;
}

.u8iayhb4j {
  stop-color: var(--svg-color--514342, #514342);
  stop-opacity: 0;
}

.uk3jx7nau {
  stop-color: var(--svg-color--8a5752, #8A5752);
}

.uoeftxp7k {
  d: path("M2.439 21.146a.15.15 0 0 1 .15-.15h27.528a.15.15 0 0 1 .15.15v6.822a.15.15 0 0 1-.15.15H2.59a.15.15 0 0 1-.15-.15z");
}

.v1-ucdd8u {
  d: path("M2.439 11.692a1.46 1.46 0 0 1 2.922 0v9.304H2.539a.1.1 0 0 1-.1-.1z");
}

.vw4hmzxuv {
  d: path("M8.799 8.29a1.15 1.15 0 0 0-1.187.482c-.545.798-.36 1.105-1.034 1.688c-.712.616-.945 1.01-1.043 1.433l-.002.008c-.096.416-.296 1.277 1.011 2.279c1.204.923 2.169.98 2.555.947l-.016.052c-.084.264.07.517.334.6c.224.072.497-.073.668-.388c.195-.36.332-.629.437-.841a.28.28 0 0 0-.082-.345l-.99-.76c-.418-.32-.442-.805-.417-.992c-.42-.345-.517-.629-.456-.925c.1-.49.271-.535.874-1.429c.606-.9.094-1.657-.652-1.809");
}

.vzh3oj5bk {
  d: path("M10.998 9.763c-.74-.513-1.261-.546-1.445-.514l-2.549 3.325L9.78 14.79c2.481.676 4.368-1.618 3.954-2.493c-.414-.876-1.88-1.94-2.736-2.534");
}

.w-2pnubhf {
  stop-color: var(--svg-color--5490e6, #5490E6);
  stop-opacity: 0;
}

.we894y8xm {
  stop-color: var(--svg-color--7b74d4, #7B74D4);
}

.xrdg6g6_d {
  stop-color: var(--svg-color--6964bd, #6964BD);
  stop-opacity: 0;
}

.xxaw6lbdd {
  stop-color: var(--svg-color--3c2c4d, #3C2C4D);
}

.yeuw1mqbz {
  stop-color: var(--svg-color--3172d9, #3172D9);
}

.yonqiacdw {
  stop-color: var(--svg-color--160639, #160639);
}

.yozp8vswl {
  stroke: var(--svg-color--271e22, #271E22);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M10.56 11.325c.094-.03.257-.054.399-.243c.104-.139.085-.314.063-.425");
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
