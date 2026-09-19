<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iu6kkxb)" class="r-tw7vv-t"/><path fill="url(#iOt3HYd)" class="r-tw7vv-t"/><path fill="url(#iashTSb)" class="hkabsz05q"/><path fill="url(#iYBRGgc)" class="hkabsz05q"/><path fill="url(#icop9Mc)" class="e3pfcobau"/><path fill="url(#ix5X7Ke)" class="e3pfcobau"/><path fill="url(#i5MdPpc)" class="e3pfcobau"/><path fill="url(#iNBJ2YT)" class="e3pfcobau"/><path fill="url(#iN1QLJd)" class="e3pfcobau"/><g filter="url(#iAaeBRc)"><path fill="url(#inrV6ib)" class="jd2auwx6s"/><path fill="url(#ibP6b3d)" class="jd2auwx6s"/></g><g filter="url(#ine1Tpe)"><path class="khs4dgbps"/><path fill="url(#ikHOi9d)" class="qw3p8bayt"/></g><path fill="url(#iDnMz5b)" class="pprjyfbvx"/><path fill="url(#itxnmDe)" class="pprjyfbvx"/><g filter="url(#i0ygqNd)"><path class="kaynp2-9s"/></g><g filter="url(#iiKfVhc)"><path class="n5zuw6buu"/></g><path fill="url(#iDedZgd)" class="ttny6fqui"/><path fill="url(#iHVEJnd)" class="ttny6fqui"/><path fill="url(#iMbEi8d)" class="ttny6fqui"/><path fill="url(#i221EOe)" class="ttny6fqui"/><path fill="url(#ilcVPnc)" class="ttny6fqui"/><path fill="url(#ibwimad)" class="ttny6fqui"/><g filter="url(#iqtJV1b)"><path fill="url(#iGNLnSb)" class="gmvlz-bpm"/></g><path fill="url(#i9e9foc)" class="do_oqma9l"/><path fill="url(#it8Zqpd)" class="do_oqma9l"/><g filter="url(#iJYsoFe)"><path fill="url(#iigycDb)" class="b-jhlinsb"/><path fill="url(#iiaFMAd)" class="b-jhlinsb"/><path fill="url(#ilr7nVb)" class="b-jhlinsb"/><path fill="url(#i2FNdqF)" class="b-jhlinsb"/></g><g filter="url(#ioOXhme)"><path fill="url(#iD93rnd)" class="nvbnfxbyl"/><path fill="url(#iIryckd)" class="nvbnfxbyl"/><path fill="url(#i0ASEyc)" class="nvbnfxbyl"/></g><path fill="url(#iaj5iPc)" class="he201gb6y"/><path fill="url(#iMn8SEe)" class="he201gb6y"/><path fill="url(#ift9jyp)" class="he201gb6y"/><path clip-rule="evenodd" class="d_2oqxbnp"/><g filter="url(#inQJQDd)"><path clip-rule="evenodd" class="fx-jwfixg"/></g><path class="yvaz01hvo"/><g filter="url(#ir66R1d)"><path class="s5v_1my2n"/></g><defs><linearGradient id="iu6kkxb" x1="5.919" x2="5.919" y1="27.892" y2="29.58" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="we894y8xm"/></linearGradient><linearGradient id="iOt3HYd" x1="4.181" x2="4.642" y1="29.947" y2="29.947" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="iashTSb" x1="26.818" x2="26.818" y1="27.892" y2="29.58" gradientUnits="userSpaceOnUse"><stop class="jp856yt_g"/><stop offset="1" class="yudqmabvt"/></linearGradient><linearGradient id="iYBRGgc" x1="25.052" x2="25.52" y1="29.947" y2="29.947" gradientUnits="userSpaceOnUse"><stop class="kun3pubeg"/><stop offset="1" class="onfzp-bwy"/></linearGradient><linearGradient id="icop9Mc" x1="14.33" x2="16.353" y1="21.549" y2="26.799" gradientUnits="userSpaceOnUse"><stop class="s50shpiqt"/><stop offset="1" class="ctq4_rb_x"/></linearGradient><linearGradient id="ix5X7Ke" x1="2.439" x2="4.189" y1="26.674" y2="26.674" gradientUnits="userSpaceOnUse"><stop offset=".205" class="xxaw6lbdd"/><stop offset="1" class="znfsawb6t"/></linearGradient><linearGradient id="i5MdPpc" x1="30.267" x2="28.861" y1="26.424" y2="26.424" gradientUnits="userSpaceOnUse"><stop offset=".089" class="dzbbssbmi"/><stop offset="1" class="ihb5mw0qq"/></linearGradient><linearGradient id="iNBJ2YT" x1="18.58" x2="18.58" y1="28.264" y2="27.986" gradientUnits="userSpaceOnUse"><stop class="bw9bhgcag"/><stop offset="1" class="yylhrtbwl"/></linearGradient><linearGradient id="iN1QLJd" x1="16.353" x2="16.353" y1="21.142" y2="21.346" gradientUnits="userSpaceOnUse"><stop class="yonqiacdw"/><stop offset="1" class="u7ukf0cyw"/></linearGradient><linearGradient id="inrV6ib" x1="11.486" x2="5.58" y1="20.392" y2="20.392" gradientUnits="userSpaceOnUse"><stop class="j_iqhtv2z"/><stop offset="1" class="lfx99ibod"/></linearGradient><linearGradient id="ibP6b3d" x1="11.705" x2="10.173" y1="20.736" y2="20.736" gradientUnits="userSpaceOnUse"><stop class="erd70ybna"/><stop offset="1" class="xrdg6g6_d"/></linearGradient><linearGradient id="ikHOi9d" x1="11.611" x2="9.955" y1="17.111" y2="17.111" gradientUnits="userSpaceOnUse"><stop offset=".057" class="qpqpigz0q"/><stop offset="1" class="nw5hewkux"/></linearGradient><linearGradient id="iDnMz5b" x1="5.361" x2="2.439" y1="21.142" y2="21.142" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tmk_n7bre"/><stop offset="1" class="kgz9t0b5t"/></linearGradient><linearGradient id="itxnmDe" x1="5.548" x2="4.486" y1="21.142" y2="21.142" gradientUnits="userSpaceOnUse"><stop class="zq06kkbop"/><stop offset="1" class="atnucacjf"/></linearGradient><linearGradient id="iDedZgd" x1="12.267" x2="29.142" y1="18.799" y2="18.799" gradientUnits="userSpaceOnUse"><stop class="oesdu5b_i"/><stop offset="1" class="yeuw1mqbz"/></linearGradient><linearGradient id="iHVEJnd" x1="11.455" x2="12.767" y1="21.455" y2="21.455" gradientUnits="userSpaceOnUse"><stop class="yx0c6y8nw"/><stop offset="1" class="fl_2tebol"/></linearGradient><linearGradient id="iMbEi8d" x1="23.392" x2="23.392" y1="22.416" y2="21.978" gradientUnits="userSpaceOnUse"><stop class="kbcj9odgo"/><stop offset="1" class="gmid2kucu"/></linearGradient><linearGradient id="i221EOe" x1="11.275" x2="11.744" y1="18.799" y2="18.799" gradientUnits="userSpaceOnUse"><stop class="z7g_zwxuh"/><stop offset="1" class="fu6a58b1y"/></linearGradient><linearGradient id="ilcVPnc" x1="20.861" x2="20.861" y1="12.799" y2="13.986" gradientUnits="userSpaceOnUse"><stop class="gr6t18twh"/><stop offset="1" class="s8sy2oshg"/></linearGradient><linearGradient id="iigycDb" x1="10.331" x2="12.454" y1="13.456" y2="10.965" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="ift9jyp" x1="9.587" x2="9.496" y1="12.944" y2="13.087" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><radialGradient id="ibwimad" cx="0" cy="0" r="1" gradientTransform="rotate(125.151 11.859 14.355)scale(6.45916 9.77416)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="tejv_ybih"/><stop offset="1" class="cf8m5rrfx"/></radialGradient><radialGradient id="iGNLnSb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.2187 9.56259 -16.93759 -16.32847 30.017 14.205)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="ffbkz6xwn"/><stop offset="1" class="w-2pnubhf"/></radialGradient><radialGradient id="i9e9foc" cx="0" cy="0" r="1" gradientTransform="rotate(98.587 1.835 10.607)scale(.6185 .87304)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="it8Zqpd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.617 9.43 1.887)scale(.35989 .5401)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="iiaFMAd" cx="0" cy="0" r="1" gradientTransform="matrix(.5369 -.8014 .97707 .6546 9.44 13.231)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="ilr7nVb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.72916 -3.56368 1.38468 -1.83753 12.512 11.407)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="i2FNdqF" cx="0" cy="0" r="1" gradientTransform="matrix(.35611 .26835 -.4185 .55536 10.903 11.378)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="iD93rnd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.42928 .85603 -1.30132 -5.21312 9.15 11.804)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="lbq-lsb6f"/><stop offset="1" class="g-7ivnbav"/></radialGradient><radialGradient id="iIryckd" cx="0" cy="0" r="1" gradientTransform="rotate(163.088 4.017 5.042)scale(1.69569 2.72805)" gradientUnits="userSpaceOnUse"><stop class="tue5drbtp"/><stop offset="1" class="d6crxg3sz"/></radialGradient><radialGradient id="i0ASEyc" cx="0" cy="0" r="1" gradientTransform="rotate(-37.168 27.431 -5.765)scale(.62107 .30515)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="ja8qkqbty"/><stop offset="1" class="rxuswac8h"/></radialGradient><radialGradient id="iaj5iPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.69143 .51746 -.25257 -.33748 9.487 12.946)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="iMn8SEe" cx="0" cy="0" r="1" gradientTransform="matrix(.92028 1.01645 -1.05918 .95897 9.191 12.768)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><filter id="iAaeBRc" width="8.313" height="3.734" x="5.361" y="17.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.376471 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_94"/></filter><filter id="ine1Tpe" width="8.313" height="3.734" x="5.361" y="13.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.266667 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_94"/></filter><filter id="i0ygqNd" width="19.127" height="9.563" x="11.265" y="14.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_94" stdDeviation=".25"/></filter><filter id="iiKfVhc" width="8.547" height="8.868" x="5.618" y="9.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_94" stdDeviation=".5"/></filter><filter id="iqtJV1b" width="18.738" height="9.363" x="11.58" y="13.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_94" stdDeviation=".375"/></filter><filter id="iJYsoFe" width="7.103" height="5.96" x="6.927" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.403922 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_94"/></filter><filter id="ioOXhme" width="5.192" height="7.802" x="5.357" y="8.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.14902 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_94"/></filter><filter id="inQJQDd" width=".714" height="1.114" x="9.516" y="10.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_94"/></filter><filter id="ir66R1d" width=".779" height=".968" x="10.473" y="10.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_94" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-bed-medium" /></template>
<style>
.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.atnucacjf {
  stop-color: var(--svg-color--2a2356, #2A2356);
  stop-opacity: 0;
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.b-jhlinsb {
  d: path("M10.965 9.883c-.757-.515-1.287-.544-1.474-.51l-2.564 3.402l2.841 2.23c2.53.668 4.43-1.68 4.002-2.568c-.429-.887-1.928-1.958-2.805-2.554");
}

.bw9bhgcag {
  stop-color: var(--svg-color--481764, #481764);
}

.cf8m5rrfx {
  stop-color: var(--svg-color--3173da, #3173DA);
  stop-opacity: 0;
}

.ctq4_rb_x {
  stop-color: var(--svg-color--4a2160, #4A2160);
}

.d_2oqxbnp {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M11.844 12.335a.143.143 0 0 0 .163.12c.376-.057.667-.33.753-.422a.143.143 0 1 0-.21-.194c-.073.079-.308.291-.586.333a.143.143 0 0 0-.12.162");
}

.d6crxg3sz {
  stop-color: var(--svg-color--68514d, #68514D);
  stop-opacity: 0;
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.do_oqma9l {
  d: path("M11.998 10.34a1.15 1.15 0 0 1-.594-.078l-.123.164l1.025.772c.273-.101.464-.396.34-.62c-.107-.192-.347-.29-.648-.237");
}

.dzbbssbmi {
  stop-color: var(--svg-color--4e3568, #4E3568);
}

.e3pfcobau {
  d: path("M2.439 21.292a.15.15 0 0 1 .15-.15h27.528a.15.15 0 0 1 .15.15v6.821a.15.15 0 0 1-.15.15H2.59a.15.15 0 0 1-.15-.15z");
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
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

.fx-jwfixg {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M10.048 10.648a1 1 0 0 1 .134-.209a.171.171 0 0 0-.246-.238a1.2 1.2 0 0 0-.197.298a1.2 1.2 0 0 0-.123.491a.171.171 0 0 0 .343.003a.8.8 0 0 1 .088-.345");
}

.g-7ivnbav {
  stop-color: var(--svg-color--583e3b, #583E3B);
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gmid2kucu {
  stop-color: var(--svg-color--1441b8, #1441B8);
  stop-opacity: 0;
}

.gmvlz-bpm {
  d: path("M12.33 14.505h14.437v-.6H12.33zm16.637 2.2v5.062h.6v-5.062zm-2.2-2.2a2.2 2.2 0 0 1 2.2 2.2h.6a2.8 2.8 0 0 0-2.8-2.8z");
}

.gr6t18twh {
  stop-color: var(--svg-color--497dba, #497DBA);
}

.he201gb6y {
  d: path("m10.388 13.408l-1.45-.807a.83.83 0 0 0 1.45.807");
}

.hkabsz05q {
  d: path("M25.314 27.33h3.008v2.969h-3.008z");
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ihb5mw0qq {
  stop-color: var(--svg-color--4e3568, #4E3568);
  stop-opacity: 0;
}

.j_iqhtv2z {
  stop-color: var(--svg-color--817ed9, #817ED9);
}

.ja8qkqbty {
  stop-color: var(--svg-color--5f4745, #5F4745);
}

.jd2auwx6s {
  d: path("M5.36 17.808c0-.22.18-.4.4-.4h7.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jp856yt_g {
  stop-color: var(--svg-color--5e4ac0, #5E4AC0);
}

.kaynp2-9s {
  fill: var(--svg-color--321853, #321853);
  d: path("M12.142 14.58H26.59a3.293 3.293 0 0 1 3.302 3.284v4.997a.28.28 0 0 1-.283.281H12.142a.376.376 0 0 1-.377-.375z");
}

.kbcj9odgo {
  stop-color: var(--svg-color--1441b8, #1441B8);
}

.kgz9t0b5t {
  stop-color: var(--svg-color--32274d, #32274D);
}

.khs4dgbps {
  fill: var(--svg-color--2f63c0, #2F63C0);
  d: path("M5.36 15.074a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.kun3pubeg {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.lbq-lsb6f {
  stop-color: var(--svg-color--503339, #503339);
}

.lfx99ibod {
  stop-color: var(--svg-color--7f7dcb, #7F7DCB);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.n5zuw6buu {
  fill: var(--svg-color--25409f, #25409F);
  d: path("M8.073 10.588c.157-.239.531-.56 1.078-.459c.448.084.809.408.85.856c.232.006.642.097 1.179.456c.168.113.362.244.566.39a1 1 0 0 0 .364.014c.27-.05.486.036.583.208c.077.136.023.303-.096.425c.486.404.287 1.533.483 1.93c.36.732-.415 1.903-2.422 1.734q-.098.197-.233.456c-.152.29-.399.427-.605.366c-.241-.073-.386-.302-.313-.544l.014-.048c-.352.037-1.235-.002-2.347-.827c-1.208-.895-.082-1.448 0-1.83l.53-.237c.084-.387-1.193-.758-.552-1.332c.355-.318.443-.545.553-.826c.077-.2.166-.426.368-.732");
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nvbnfxbyl {
  d: path("M8.717 8.404a1.17 1.17 0 0 0-1.203.5c-.548.816-.358 1.127-1.038 1.726c-.719.632-.953 1.035-1.048 1.465l-.002.009c-.095.424-.29 1.301 1.047 2.309c1.232.928 2.214.979 2.606.942l-.016.053c-.083.269.076.525.345.608c.229.07.504-.08.676-.401c.195-.367.332-.642.437-.86a.284.284 0 0 0-.085-.349l-1.015-.764c-.427-.322-.455-.816-.431-1.006c-.43-.347-.532-.636-.472-.937c.098-.499.272-.547.877-1.46c.61-.92.081-1.687-.678-1.835");
}

.nw5hewkux {
  stop-color: var(--svg-color--305fb8, #305FB8);
  stop-opacity: 0;
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.oesdu5b_i {
  stop-color: var(--svg-color--3071d8, #3071D8);
}

.onfzp-bwy {
  stop-color: var(--svg-color--5a4eb7, #5A4EB7);
  stop-opacity: 0;
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pprjyfbvx {
  d: path("M2.439 11.838a1.46 1.46 0 0 1 2.922 0v9.304H2.539a.1.1 0 0 1-.1-.1z");
}

.qpqpigz0q {
  stop-color: var(--svg-color--28469e, #28469E);
}

.qw3p8bayt {
  d: path("M5.36 15.074a1.4 1.4 0 0 1 1.4-1.4h6.913v3.734H5.761a.4.4 0 0 1-.4-.4z");
}

.r-tw7vv-t {
  d: path("M4.439 27.33h2.96v2.969H4.44z");
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rxuswac8h {
  stop-color: var(--svg-color--5f4745, #5F4745);
  stop-opacity: 0;
}

.s50shpiqt {
  stop-color: var(--svg-color--40225f, #40225F);
}

.s5v_1my2n {
  stroke: var(--svg-color--483d3d, #483D3D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.623 11.436c.094-.028.257-.053.399-.242c.104-.14.084-.314.062-.426");
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

.ttny6fqui {
  d: path("M11.455 13.205h15.312a3.5 3.5 0 0 1 3.5 3.5v5.325a.3.3 0 0 1-.3.3H11.855a.4.4 0 0 1-.4-.4z");
}

.tue5drbtp {
  stop-color: var(--svg-color--68514d, #68514D);
}

.u7ukf0cyw {
  stop-color: var(--svg-color--160639, #160639);
  stop-opacity: 0;
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
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

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
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

.yudqmabvt {
  stop-color: var(--svg-color--7c75d7, #7C75D7);
}

.yvaz01hvo {
  stroke: var(--svg-color--52363a, #52363A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M10.56 11.47c.094-.028.257-.053.399-.242c.104-.139.085-.313.063-.425");
}

.yx0c6y8nw {
  stop-color: var(--svg-color--1c4eb1, #1C4EB1);
}

.yylhrtbwl {
  stop-color: var(--svg-color--481764, #481764);
  stop-opacity: 0;
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
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
