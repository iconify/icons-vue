<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iUvHa2U)" class="do7oqlnuw"/><path fill="url(#ieaFVMc)" class="do7oqlnuw"/><path fill="url(#iPNv0WW)" class="s93ctabvw"/><path fill="url(#iAhkdAc)" class="s93ctabvw"/><path fill="url(#iaQtDlc)" class="li_vg9e-a"/><path fill="url(#iFQuYLd)" class="li_vg9e-a"/><path fill="url(#ibrV2Fe)" class="li_vg9e-a"/><path fill="url(#italj1r)" class="li_vg9e-a"/><path fill="url(#iDTfnrb)" class="li_vg9e-a"/><g filter="url(#iy12A2c)"><path fill="url(#i95nthe)" class="hgktr4b5y"/><path fill="url(#it5Jdgc)" class="hgktr4b5y"/></g><g filter="url(#i3GAz8b)"><path class="li8pvwbti"/><path fill="url(#i6pGLwd)" class="ahjdmeiko"/></g><path fill="url(#iBNasgb)" class="xgm44ebmf"/><path fill="url(#inINi6b)" class="xgm44ebmf"/><g filter="url(#ix9uSwb)"><path class="bkk3-sbbm"/></g><g filter="url(#ioWdNcb)"><path class="pkrft29_p"/></g><path fill="url(#iATEcDd)" class="p60oc5_su"/><path fill="url(#ibXnQzc)" class="p60oc5_su"/><path fill="url(#iy6LNjy)" class="p60oc5_su"/><path fill="url(#ikcTd4c)" class="p60oc5_su"/><path fill="url(#iKB5vFe)" class="p60oc5_su"/><path fill="url(#iDvxtHc)" class="p60oc5_su"/><g filter="url(#iw5ioMd)"><path fill="url(#i0UK0VO)" class="yyv33bcdz"/></g><path fill="url(#iAjpaKd)" class="j7-z7_o1p"/><path fill="url(#iwTLM9l)" class="j7-z7_o1p"/><g filter="url(#iYoO93r)"><path fill="url(#iXUarRc)" class="moajd-bli"/><path fill="url(#iM0ykYf)" class="moajd-bli"/><path fill="url(#iibsIIb)" class="moajd-bli"/><path fill="url(#i9VCkAe)" class="moajd-bli"/></g><g filter="url(#iHZkymw)"><path fill="url(#iNxw8yc)" class="ot9wnc9ed"/><path fill="url(#irP0OLO)" class="ot9wnc9ed"/><path fill="url(#i77cICh)" class="ot9wnc9ed"/></g><path fill="url(#iWECEjb)" class="poegjdbeo"/><path fill="url(#izItobb)" class="poegjdbeo"/><path fill="url(#iOL7LKe)" class="poegjdbeo"/><path clip-rule="evenodd" class="dve9wowdr"/><g filter="url(#iBM9JIb)"><path clip-rule="evenodd" class="ut0n96bzl"/></g><path class="k4c71y6as"/><g filter="url(#iu8V4vp)"><path class="y3aeiyb0j"/></g><defs><linearGradient id="iUvHa2U" x1="5.919" x2="5.919" y1="26.96" y2="28.648" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="we894y8xm"/></linearGradient><linearGradient id="ieaFVMc" x1="4.181" x2="4.642" y1="29.015" y2="29.015" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iPNv0WW" x1="26.818" x2="26.818" y1="26.96" y2="28.648" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="yudqmabvt"/></linearGradient><linearGradient id="iAhkdAc" x1="25.052" x2="25.52" y1="29.015" y2="29.015" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iaQtDlc" x1="14.33" x2="16.353" y1="20.617" y2="25.867" gradientUnits="userSpaceOnUse"><stop class="s50shpiqt"/><stop offset="1" class="ctq4_rb_x"/></linearGradient><linearGradient id="iFQuYLd" x1="2.439" x2="4.189" y1="25.742" y2="25.742" gradientUnits="userSpaceOnUse"><stop offset=".205" class="xxaw6lbdd"/><stop offset="1" class="znfsawb6t"/></linearGradient><linearGradient id="ibrV2Fe" x1="30.267" x2="28.861" y1="25.492" y2="25.492" gradientUnits="userSpaceOnUse"><stop offset=".089" class="dzbbssbmi"/><stop offset="1" class="ihb5mw0qq"/></linearGradient><linearGradient id="italj1r" x1="18.58" x2="18.58" y1="27.331" y2="27.054" gradientUnits="userSpaceOnUse"><stop class="bw9bhgcag"/><stop offset="1" class="yylhrtbwl"/></linearGradient><linearGradient id="iDTfnrb" x1="16.353" x2="16.353" y1="20.21" y2="20.413" gradientUnits="userSpaceOnUse"><stop class="yonqiacdw"/><stop offset="1" class="u7ukf0cyw"/></linearGradient><linearGradient id="i95nthe" x1="11.486" x2="5.58" y1="19.46" y2="19.46" gradientUnits="userSpaceOnUse"><stop class="j_iqhtv2z"/><stop offset="1" class="lfx99ibod"/></linearGradient><linearGradient id="it5Jdgc" x1="11.705" x2="10.173" y1="19.804" y2="19.804" gradientUnits="userSpaceOnUse"><stop class="erd70ybna"/><stop offset="1" class="xrdg6g6_d"/></linearGradient><linearGradient id="i6pGLwd" x1="11.611" x2="9.955" y1="16.179" y2="16.179" gradientUnits="userSpaceOnUse"><stop offset=".057" class="qpqpigz0q"/><stop offset="1" class="nw5hewkux"/></linearGradient><linearGradient id="iBNasgb" x1="5.361" x2="2.439" y1="20.21" y2="20.21" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tmk_n7bre"/><stop offset="1" class="kgz9t0b5t"/></linearGradient><linearGradient id="inINi6b" x1="5.548" x2="4.486" y1="20.21" y2="20.21" gradientUnits="userSpaceOnUse"><stop class="zq06kkbop"/><stop offset="1" class="atnucacjf"/></linearGradient><linearGradient id="iATEcDd" x1="12.267" x2="29.142" y1="17.867" y2="17.867" gradientUnits="userSpaceOnUse"><stop class="oesdu5b_i"/><stop offset="1" class="yeuw1mqbz"/></linearGradient><linearGradient id="ibXnQzc" x1="11.455" x2="12.767" y1="20.523" y2="20.523" gradientUnits="userSpaceOnUse"><stop class="yx0c6y8nw"/><stop offset="1" class="fl_2tebol"/></linearGradient><linearGradient id="iy6LNjy" x1="23.392" x2="23.392" y1="21.484" y2="21.046" gradientUnits="userSpaceOnUse"><stop class="kbcj9odgo"/><stop offset="1" class="gmid2kucu"/></linearGradient><linearGradient id="ikcTd4c" x1="11.275" x2="11.744" y1="17.867" y2="17.867" gradientUnits="userSpaceOnUse"><stop class="z7g_zwxuh"/><stop offset="1" class="fu6a58b1y"/></linearGradient><linearGradient id="iKB5vFe" x1="20.861" x2="20.861" y1="11.867" y2="13.054" gradientUnits="userSpaceOnUse"><stop class="gr6t18twh"/><stop offset="1" class="s8sy2oshg"/></linearGradient><linearGradient id="iXUarRc" x1="10.431" x2="12.456" y1="12.46" y2="10.085" gradientUnits="userSpaceOnUse"><stop class="w6b0chbuk"/><stop offset="1" class="n3dqqoxxk"/></linearGradient><linearGradient id="iOL7LKe" x1="9.723" x2="9.636" y1="11.971" y2="12.108" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><radialGradient id="iDvxtHc" cx="0" cy="0" r="1" gradientTransform="rotate(125.151 12.1 13.89)scale(6.45916 9.77416)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="tejv_ybih"/><stop offset="1" class="cf8m5rrfx"/></radialGradient><radialGradient id="i0UK0VO" cx="0" cy="0" r="1" gradientTransform="matrix(-9.2187 9.56259 -16.93759 -16.32847 30.017 13.273)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ffbkz6xwn"/><stop offset="1" class="w-2pnubhf"/></radialGradient><radialGradient id="iAjpaKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.08813 .58313 -.82299 -.12437 12.59 9.523)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="rcpmccbyc"/><stop offset=".684" class="wdglv_bwm"/></radialGradient><radialGradient id="iwTLM9l" cx="0" cy="0" r="1" gradientTransform="rotate(-120.611 9.175 1.448)scale(.3431 .51501)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iM0ykYf" cx="0" cy="0" r="1" gradientTransform="matrix(.51199 -.76419 .93145 .62405 9.581 12.246)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="iibsIIb" cx="0" cy="0" r="1" gradientTransform="rotate(-143 8.013 3.16)scale(5.64513 2.19403)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="nkfrpdbdq"/><stop offset="1" class="eqwiy2pxg"/></radialGradient><radialGradient id="i9VCkAe" cx="0" cy="0" r="1" gradientTransform="matrix(.33949 .25583 -.39907 .52957 10.977 10.479)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="iNxw8yc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.26962 .81666 -1.2414 -4.97014 9.305 10.885)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="te4zz7dbn"/><stop offset="1" class="otf1z2b9l"/></radialGradient><radialGradient id="irP0OLO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.54684 .47053 -.75693 -2.48837 9.475 7.923)" gradientUnits="userSpaceOnUse"><stop class="r-95cxbic"/><stop offset="1" class="efo8wovhu"/></radialGradient><radialGradient id="i77cICh" cx="0" cy="0" r="1" gradientTransform="matrix(.4719 -.35782 .17577 .23181 9.215 14.315)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="cl2mrcsll"/><stop offset="1" class="hms2sfnpk"/></radialGradient><radialGradient id="iWECEjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.65928 .49347 -.2408 -.32171 9.627 11.974)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="izItobb" cx="0" cy="0" r="1" gradientTransform="matrix(.87728 .96906 -1.01005 .9144 9.345 11.804)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><filter id="iy12A2c" width="8.313" height="3.734" x="5.361" y="16.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.376471 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_113"/></filter><filter id="i3GAz8b" width="8.313" height="3.734" x="5.361" y="12.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.266667 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_113"/></filter><filter id="ix9uSwb" width="19.127" height="9.563" x="11.265" y="13.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_113" stdDeviation=".25"/></filter><filter id="ioWdNcb" width="8.547" height="8.868" x="5.618" y="8.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_113" stdDeviation=".5"/></filter><filter id="iw5ioMd" width="18.738" height="9.363" x="11.58" y="12.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_113" stdDeviation=".375"/></filter><filter id="iYoO93r" width="6.781" height="5.692" x="6.986" y="8.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.654902 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_113"/></filter><filter id="iHZkymw" width="4.95" height="7.446" x="5.69" y="7.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.682353 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_113"/></filter><filter id="iBM9JIb" width=".686" height="1.067" x="9.65" y="9.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_113"/></filter><filter id="iu8V4vp" width=".779" height=".968" x="10.473" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_113" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-bed-medium-light" /></template>
<style>
.ahjdmeiko {
  d: path("M5.36 14.142a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.atnucacjf {
  stop-color: var(--svg-color--2a2356, #2A2356);
  stop-opacity: 0;
}

.bkk3-sbbm {
  fill: var(--svg-color--321853, #321853);
  d: path("M12.142 13.648H26.59a3.293 3.293 0 0 1 3.302 3.284v4.997a.28.28 0 0 1-.283.281H12.142a.376.376 0 0 1-.377-.375z");
}

.bw9bhgcag {
  stop-color: var(--svg-color--481764, #481764);
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cf8m5rrfx {
  stop-color: var(--svg-color--3173da, #3173DA);
  stop-opacity: 0;
}

.cl2mrcsll {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
}

.ctq4_rb_x {
  stop-color: var(--svg-color--4a2160, #4A2160);
}

.do7oqlnuw {
  d: path("M4.439 26.398h2.96v2.969H4.44z");
}

.dve9wowdr {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M11.874 11.39c.01.074.08.126.154.114c.36-.053.637-.314.718-.402a.136.136 0 1 0-.199-.185c-.07.075-.294.279-.559.318a.136.136 0 0 0-.114.155");
}

.dzbbssbmi {
  stop-color: var(--svg-color--4e3568, #4E3568);
}

.efo8wovhu {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
  stop-opacity: 0;
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.eqwiy2pxg {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
  stop-opacity: 0;
}

.erd70ybna {
  stop-color: var(--svg-color--6964bd, #6964BD);
}

.ffbkz6xwn {
  stop-color: var(--svg-color--5490e6, #5490E6);
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

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.gr6t18twh {
  stop-color: var(--svg-color--497dba, #497DBA);
}

.hgktr4b5y {
  d: path("M5.36 16.876c0-.22.18-.4.4-.4h7.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.hms2sfnpk {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
  stop-opacity: 0;
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

.j7-z7_o1p {
  d: path("M12.02 9.49a1.1 1.1 0 0 1-.566-.076l-.118.156l.978.737c.26-.097.442-.378.323-.592c-.101-.183-.33-.275-.617-.226");
}

.jp856yt_g {
  stop-color: var(--svg-color--5e4ac0, #5E4AC0);
}

.k4c71y6as {
  stroke: var(--svg-color--794629, #794629);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M10.56 10.539c.094-.03.257-.054.399-.243c.104-.139.085-.313.063-.425");
}

.kbcj9odgo {
  stop-color: var(--svg-color--1441b8, #1441B8);
}

.kgz9t0b5t {
  stop-color: var(--svg-color--32274d, #32274D);
}

.ksl77bchk {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
  stop-opacity: 0;
}

.kun3pubeg {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
}

.lfx99ibod {
  stop-color: var(--svg-color--7f7dcb, #7F7DCB);
}

.li_vg9e-a {
  d: path("M2.439 20.36a.15.15 0 0 1 .15-.15h27.528a.15.15 0 0 1 .15.15v6.822a.15.15 0 0 1-.15.15H2.59a.15.15 0 0 1-.15-.15z");
}

.li8pvwbti {
  fill: var(--svg-color--2f63c0, #2F63C0);
  d: path("M5.36 14.142a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.moajd-bli {
  d: path("M11.036 9.053c-.721-.491-1.227-.519-1.405-.486L7.186 11.81l2.708 2.126c2.412.637 4.224-1.603 3.816-2.45c-.409-.845-1.838-1.865-2.674-2.434");
}

.n3dqqoxxk {
  stop-color: var(--svg-color--f2b592, #F2B592);
}

.nkfrpdbdq {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
}

.nw5hewkux {
  stop-color: var(--svg-color--305fb8, #305FB8);
  stop-opacity: 0;
}

.oesdu5b_i {
  stop-color: var(--svg-color--3071d8, #3071D8);
}

.onfzp-bwy {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
  stop-opacity: 0;
}

.ot9wnc9ed {
  d: path("M8.893 7.644a1.12 1.12 0 0 0-1.147.477c-.522.777-.341 1.074-.99 1.645c-.685.603-.908.987-1 1.397l-.001.008c-.09.405-.277 1.241.998 2.202c1.175.885 2.11.933 2.485.898l-.016.05c-.079.256.073.5.329.58c.218.067.481-.076.644-.382a23 23 0 0 0 .418-.82a.27.27 0 0 0-.082-.333l-.967-.729a1.07 1.07 0 0 1-.411-.959c-.41-.33-.507-.606-.45-.893c.094-.476.26-.521.836-1.393c.582-.877.078-1.607-.646-1.748");
}

.otf1z2b9l {
  stop-color: var(--svg-color--ffedae, #FFEDAE);
}

.p60oc5_su {
  d: path("M11.455 12.273h15.312a3.5 3.5 0 0 1 3.5 3.5v5.325a.3.3 0 0 1-.3.3H11.855a.4.4 0 0 1-.4-.4z");
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.pkrft29_p {
  fill: var(--svg-color--25409f, #25409F);
  d: path("M8.073 9.656c.157-.239.531-.56 1.078-.459c.448.084.809.408.85.855c.232.007.642.098 1.179.457c.168.113.362.245.566.39a1 1 0 0 0 .364.014c.27-.05.486.036.583.208c.077.136.023.303-.096.425c.486.404.287 1.533.483 1.93c.36.732-.415 1.903-2.422 1.734q-.098.197-.233.456c-.152.29-.399.427-.605.366c-.241-.073-.386-.302-.313-.544l.014-.048c-.352.037-1.235-.002-2.347-.827c-1.208-.895-.082-1.448 0-1.83l.53-.237c.084-.387-1.193-.758-.552-1.332c.355-.318.443-.545.553-.826c.077-.2.166-.426.368-.732");
}

.poegjdbeo {
  d: path("m10.485 12.414l-1.381-.77a.79.79 0 0 0 1.381.77");
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qpqpigz0q {
  stop-color: var(--svg-color--28469e, #28469E);
}

.r-95cxbic {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
}

.rcpmccbyc {
  stop-color: var(--svg-color--fec19d, #FEC19D);
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.s50shpiqt {
  stop-color: var(--svg-color--40225f, #40225F);
}

.s8sy2oshg {
  stop-color: var(--svg-color--497dba, #497DBA);
  stop-opacity: 0;
}

.s93ctabvw {
  d: path("M25.314 26.398h3.008v2.969h-3.008z");
}

.te4zz7dbn {
  stop-color: var(--svg-color--ffe2ad, #FFE2AD);
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

.ut0n96bzl {
  fill: var(--svg-color--915d37, #915D37);
  fill-rule: evenodd;
  d: path("M10.161 9.782a.8.8 0 0 1 .129-.199a.163.163 0 0 0-.235-.227a1.2 1.2 0 0 0-.188.285a1.1 1.1 0 0 0-.117.468a.163.163 0 1 0 .326.003a.8.8 0 0 1 .085-.33");
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.w-2pnubhf {
  stop-color: var(--svg-color--5490e6, #5490E6);
  stop-opacity: 0;
}

.w6b0chbuk {
  stop-color: var(--svg-color--dfa289, #DFA289);
}

.wdglv_bwm {
  stop-color: var(--svg-color--f2b08a, #F2B08A);
}

.we894y8xm {
  stop-color: var(--svg-color--7b74d4, #7B74D4);
}

.xgm44ebmf {
  d: path("M2.439 10.906a1.461 1.461 0 0 1 2.922 0v9.304H2.539a.1.1 0 0 1-.1-.1z");
}

.xrdg6g6_d {
  stop-color: var(--svg-color--6964bd, #6964BD);
  stop-opacity: 0;
}

.xxaw6lbdd {
  stop-color: var(--svg-color--3c2c4d, #3C2C4D);
}

.y3aeiyb0j {
  stroke: var(--svg-color--a67145, #A67145);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.623 10.504c.094-.028.257-.053.399-.242c.104-.14.084-.314.062-.426");
}

.yeuw1mqbz {
  stop-color: var(--svg-color--3172d9, #3172D9);
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
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

.yyv33bcdz {
  d: path("M12.33 13.573h14.437v-.6H12.33zm16.637 2.2v5.062h.6v-5.062zm-2.2-2.2a2.2 2.2 0 0 1 2.2 2.2h.6a2.8 2.8 0 0 0-2.8-2.8z");
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

</style>
