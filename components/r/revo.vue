<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jr1mzy0qc"/><path class="xyeae9bfj"/><path fill="url(#SVGTU0uTclW)" class="n5zbhm6nq"/><path class="a7y-kwz_l"/><path class="uy5_1bc0w"/><path fill="url(#SVGoKrn3G8K)" class="e7kw5ehsw"/><path fill="url(#SVGEJlfgetp)" class="upze-xbwc"/><path fill="url(#SVGRL0N0cJz)" class="iyvsrbb8o"/><path fill="url(#SVGp5LemcXm)" class="fe1pgfb4g"/><path class="vc162zb5q"/><path class="kkjd42b3y"/><path class="eluxjdbir"/><path fill="url(#SVG2264rb7Q)" class="fwf7tub9v"/><path class="y99-vob1r"/><path class="on1cm-avk"/><path class="xxp_0tbrn"/><path fill="url(#SVGmzdISdFW)" class="zgz5aykhk"/><path fill="url(#SVGXDiCsesT)" class="bi2kzo85x"/><path class="z-1280bmt"/><path class="lljnzp3se"/><path class="x8o3fpb7g"/><path fill="url(#SVGzMHiHbtw)" class="e3e6jgbcx"/><path fill="url(#SVGK5ng6dEe)" class="fzxkbdm2i"/><path fill="url(#SVG6VVmjbxu)" class="jx1xcfd7q"/><path fill="url(#SVGTIZxKeyA)" class="sigx5tbkt"/><path fill="url(#SVGrsZB5T2N)" clip-rule="evenodd" class="i_gq3vb_k"/><path fill="url(#SVGJGMErcTo)" class="dd6r96btf"/><path fill="url(#SVGL8yvceDQ)" class="wsjyw0bgi"/><path clip-rule="evenodd" class="rc4-_xbkv"/><path fill="url(#SVG4Cip5cus)" class="wb54-1day"/><path fill="url(#SVGF1BOscSV)" class="a4-ab8b5d"/><path clip-rule="evenodd" class="su00gzbad"/><path fill="url(#SVGRmVhpbMK)" class="l80ruibyg"/><path fill="url(#SVG1PkxeeZQ)" class="ui2badbss"/><path clip-rule="evenodd" class="en_6gms7f"/><path fill="url(#SVGoW5TdcuZ)" clip-rule="evenodd" class="hyth7s1pd"/><path fill="url(#SVGqmr6Mdpg)" clip-rule="evenodd" class="ly4gcqblh"/><path clip-rule="evenodd" class="abtsjubxx"/><path fill="url(#SVGi6LXzdpQ)" class="xcmucccca"/><path class="l-ab5acjm"/><path fill="url(#SVGo8H8rbVK)" class="m-rsdhbhr"/><path fill="url(#SVGssVHP31a)" class="bctj_xaap"/><path fill="url(#SVG92CkjMJW)" class="cezou5ojv"/><path fill="url(#SVGRWXgxbsR)" class="brcrrd81k"/><path fill="url(#SVGpvdPUndE)" class="gnve5nb3p"/><path fill="url(#SVGPx3JrevL)" class="qola699_e"/><path fill="url(#SVGJO2hod3A)" class="dpm4lkbto"/><path class="uahv8ybdf"/><path fill="url(#SVGrW9WEemy)" class="b6jxpenjo"/><defs><linearGradient id="SVGTU0uTclW" x1="14.479" x2="6.1" y1="3.539" y2="18.559" gradientUnits="userSpaceOnUse"><stop class="ctnjnobff"/><stop offset="1" class="grxlq1b6y"/></linearGradient><linearGradient id="SVGoKrn3G8K" x1="3.809" x2="23.577" y1="2.957" y2="8.567" gradientUnits="userSpaceOnUse"><stop class="nf9r_ybbj"/><stop offset="1" class="u7lib01wg"/></linearGradient><linearGradient id="SVGEJlfgetp" x1="4.947" x2="45.386" y1="2.839" y2="24.093" gradientUnits="userSpaceOnUse"><stop class="nf9r_ybbj"/><stop offset="1" class="u7lib01wg"/></linearGradient><linearGradient id="SVGRL0N0cJz" x1="-31.397" x2="42.179" y1="-29.324" y2="-4.416" gradientUnits="userSpaceOnUse"><stop class="nf9r_ybbj"/><stop offset="1" class="u7lib01wg"/></linearGradient><linearGradient id="SVGp5LemcXm" x1="-16.508" x2="29.483" y1="-80.895" y2="-76.008" gradientUnits="userSpaceOnUse"><stop class="nf9r_ybbj"/><stop offset="1" class="u7lib01wg"/></linearGradient><linearGradient id="SVG2264rb7Q" x1="12.107" x2="12.107" y1="3.53" y2="20.471" gradientUnits="userSpaceOnUse"><stop class="uqsj89l5f"/><stop offset="1" class="u811vwk6d"/></linearGradient><linearGradient id="SVGmzdISdFW" x1="11.967" x2="23.222" y1="3.479" y2="18.805" gradientUnits="userSpaceOnUse"><stop class="cay8-jbhr"/><stop offset="1" class="ini-h701j"/></linearGradient><linearGradient id="SVGXDiCsesT" x1="19.557" x2="4.118" y1="6.929" y2="9.215" gradientUnits="userSpaceOnUse"><stop class="orn5pvbkj"/><stop offset=".37" class="km-diwl_t"/><stop offset="1" class="yclc5xbqn"/></linearGradient><linearGradient id="SVGzMHiHbtw" x1="11.977" x2="11.977" y1="3.53" y2="20.47" gradientUnits="userSpaceOnUse"><stop class="hrgj6hr3h"/><stop offset=".29" class="vgggjxbpf"/><stop offset=".53" class="jsmslkv_d"/><stop offset="1" class="t17ibebxu"/></linearGradient><linearGradient id="SVGK5ng6dEe" x1="21" x2=".784" y1="4.672" y2="10.023" gradientUnits="userSpaceOnUse"><stop class="zz5mp1bkb"/><stop offset=".27" class="w0nzm-bmd"/><stop offset=".74" class="xdb4kbb0s"/><stop offset="1" class="rqm__bczc"/></linearGradient><linearGradient id="SVG6VVmjbxu" x1="14.272" x2="15.889" y1="4.843" y2="10.782" gradientUnits="userSpaceOnUse"><stop class="y6lomxbgh"/><stop offset=".34" class="cg358e3uu"/><stop offset=".52" class="fw-9bdlmf"/><stop offset=".72" class="rxuc65bjj"/><stop offset="1" class="myr4m5ksw"/></linearGradient><linearGradient id="SVGTIZxKeyA" x1="4.694" x2="20.531" y1="14.247" y2="13.912" gradientUnits="userSpaceOnUse"><stop class="i7ey02bhg"/><stop offset="1" class="hrig79nkz"/></linearGradient><linearGradient id="SVGrsZB5T2N" x1="10.216" x2="16.067" y1="5.874" y2="16.646" gradientUnits="userSpaceOnUse"><stop class="phdjydl5q"/><stop offset=".49" class="sou1-8b_q"/><stop offset="1" class="k5rjqimee"/></linearGradient><linearGradient id="SVGJGMErcTo" x1="12" x2="12" y1="3.8" y2="20.471" gradientUnits="userSpaceOnUse"><stop class="p67gip28v"/><stop offset=".23" class="l_2n9daaj"/><stop offset=".49" class="k2-vtobij"/><stop offset=".63" class="bn89nzbta"/><stop offset=".87" class="nvu86ab7j"/><stop offset="1" class="c3xqvdqwh"/></linearGradient><linearGradient id="SVGL8yvceDQ" x1="7.18" x2="8.993" y1="4.672" y2="19.129" gradientUnits="userSpaceOnUse"><stop class="r1a85pb6y"/><stop offset=".23" class="siuq8p_np"/><stop offset=".42" class="zrpfm0eqr"/><stop offset=".63" class="w0fhw9b0k"/><stop offset=".81" class="ohnd0ubjj"/><stop offset="1" class="udl2bucst"/></linearGradient><linearGradient id="SVG4Cip5cus" x1="12.197" x2="12.064" y1="3.549" y2="20.844" gradientUnits="userSpaceOnUse"><stop class="w62no5b4q"/><stop offset=".21" class="vtsjl8b0l"/><stop offset=".33" class="j914bjvha"/><stop offset=".49" class="i1v9ccnxa"/><stop offset=".57" class="r4ghx9z6l"/><stop offset=".77" class="gd_7vsb9z"/><stop offset=".89" class="c54voultg"/><stop offset="1" class="yu-p3ybhl"/></linearGradient><linearGradient id="SVGF1BOscSV" x1="4.424" x2="9.135" y1="5.827" y2="21.275" gradientUnits="userSpaceOnUse"><stop class="m4yr4sbbp"/><stop offset=".21" class="h_2h0ebya"/><stop offset=".33" class="j914bjvha"/><stop offset=".49" class="d0oe0wbsh"/><stop offset=".57" class="il6bxjr1h"/><stop offset=".77" class="q5yvr-b4s"/><stop offset=".89" class="t0mzh-bsg"/><stop offset="1" class="xpeaznbhr"/></linearGradient><linearGradient id="SVGRmVhpbMK" x1="9.008" x2="11.895" y1="4.372" y2="20.015" gradientUnits="userSpaceOnUse"><stop class="pwlwojbeh"/><stop offset=".19" class="f94ouzbcl"/><stop offset=".37" class="nddq-vs_r"/><stop offset=".68" class="y9_30gv5z"/><stop offset="1" class="b_8s0ybwf"/></linearGradient><linearGradient id="SVG1PkxeeZQ" x1="9.009" x2="12.172" y1="4.412" y2="20.802" gradientUnits="userSpaceOnUse"><stop class="gs3umobfp"/><stop offset=".19" class="j5kg19b2d"/><stop offset=".37" class="sft9xgblt"/><stop offset=".68" class="k555vrjgo"/><stop offset="1" class="rbh2qkb9z"/></linearGradient><linearGradient id="SVGoW5TdcuZ" x1="11.987" x2="11.987" y1="4.371" y2="20.47" gradientUnits="userSpaceOnUse"><stop class="ljnvkvi3w"/><stop offset=".44" class="emf7z-b4w"/><stop offset=".74" class="yflrh3bwq"/><stop offset="1" class="s9ah406ug"/></linearGradient><linearGradient id="SVGqmr6Mdpg" x1="8.082" x2="10.341" y1="4.802" y2="20.696" gradientUnits="userSpaceOnUse"><stop class="o_k8_db7f"/><stop offset=".3" class="le315gtod"/><stop offset="1" class="pg-4fq0md"/></linearGradient><linearGradient id="SVGi6LXzdpQ" x1="15.504" x2="3.717" y1="3.529" y2="4.464" gradientUnits="userSpaceOnUse"><stop class="nmnt8dz9c"/><stop offset="1" class="lngswp6ud"/></linearGradient><linearGradient id="SVGo8H8rbVK" x1="11.999" x2="10.014" y1="3.53" y2="20.536" gradientUnits="userSpaceOnUse"><stop class="v7pbuprxq"/><stop offset=".31" class="nsozokb9r"/><stop offset=".65" class="ba7mozb-c"/><stop offset="1" class="kne89tbpx"/></linearGradient><linearGradient id="SVGssVHP31a" x1="11.979" x2="11.979" y1="3.53" y2="20.471" gradientUnits="userSpaceOnUse"><stop class="e0epr8wlk"/><stop offset=".28" class="w886jtvog"/><stop offset=".57" class="f33tz3b9n"/><stop offset="1" class="gaiki3_rk"/></linearGradient><linearGradient id="SVG92CkjMJW" x1="12.007" x2="12.007" y1="3.508" y2="20.47" gradientUnits="userSpaceOnUse"><stop class="b8noanbwp"/><stop offset=".33" class="qctn6zb_s"/><stop offset=".5" class="rnmrfabyb"/><stop offset="1" class="tp68qcbea"/></linearGradient><linearGradient id="SVGRWXgxbsR" x1="12.037" x2="12.037" y1="3.529" y2="20.47" gradientUnits="userSpaceOnUse"><stop class="b8noanbwp"/><stop offset=".33" class="qctn6zb_s"/><stop offset=".5" class="rnmrfabyb"/><stop offset="1" class="tp68qcbea"/></linearGradient><linearGradient id="SVGpvdPUndE" x1="12.001" x2="12.001" y1="3.53" y2="20.471" gradientUnits="userSpaceOnUse"><stop class="ixvot5b7m"/><stop offset=".25" class="ip61n4v0g"/><stop offset=".51" class="b43pozbjz"/><stop offset=".74" class="t7hie9bir"/><stop offset="1" class="f45vi66xr"/></linearGradient><linearGradient id="SVGPx3JrevL" x1="15.834" x2="13.66" y1="3.55" y2="21.255" gradientUnits="userSpaceOnUse"><stop class="qp1im6b2d"/><stop offset=".39" class="aigaykqcn"/><stop offset="1" class="wsab7s0wp"/></linearGradient><linearGradient id="SVGJO2hod3A" x1="11.986" x2="12.271" y1="3.51" y2="19.251" gradientUnits="userSpaceOnUse"><stop class="tm0zt33dn"/><stop offset=".3" class="px_loss3w"/><stop offset=".49" class="d0um-zb1y"/><stop offset=".7" class="m0bl40btn"/><stop offset="1" class="kovaaccvw"/></linearGradient><linearGradient id="SVGrW9WEemy" x1="17.114" x2="17.114" y1="13.266" y2="17.417" gradientUnits="userSpaceOnUse"><stop class="kcnrnobdu"/><stop offset=".19" class="in25yj9wo"/><stop offset=".6" class="xit7nq7je"/><stop offset=".8" class="p374oab7y"/><stop offset="1" class="gw76e2zkx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:revo" /></template>
<style>
.a4-ab8b5d {
  d: path("m10.2 9.776l-2.7.54l.334 4.262l2.477-.656v-.874l-1.577.328v-.984l1.35-.329v-.873l-1.462.328v-.545l1.578-.328z");
}

.a7y-kwz_l {
  fill: var(--svg-color--424d8d, #424d8d);
  d: path("m8.849 8.028l-.228-.55l-.328.656l.561-.106z");
}

.abtsjubxx {
  fill: var(--svg-color--ffdbc6, #ffdbc6);
  fill-rule: evenodd;
  d: path("M16.362 11.19c0 .391-.133.714-.302.92c-.17.202-.34.265-.466.265c-.122 0-.296-.063-.46-.264a1.47 1.47 0 0 1-.302-.922c0-.386.132-.709.301-.915c.165-.201.34-.265.46-.265c.128 0 .297.063.467.264c.17.207.302.53.302.916m-.768 2.096c.926 0 1.71-.916 1.71-2.097c0-1.175-.784-2.09-1.71-2.09s-1.71.915-1.71 2.09c0 1.181.784 2.097 1.71 2.097m.678-2.097c0 .371-.127.678-.281.863c-.159.186-.302.233-.397.233c-.09 0-.238-.047-.392-.233c-.159-.185-.28-.487-.28-.863c0-.37.127-.672.28-.857c.154-.19.302-.233.392-.233c.095 0 .243.042.397.233c.159.185.28.487.28.857m1.122 0c0 1.208-.805 2.187-1.8 2.187c-.99 0-1.8-.98-1.8-2.187c0-1.201.81-2.18 1.8-2.18c.995 0 1.8.979 1.8 2.18");
}

.aigaykqcn {
  stop-color: var(--svg-color--25a3d5, #25a3d5);
}

.b_8s0ybwf {
  stop-color: var(--svg-color--a276ae, #a276ae);
}

.b43pozbjz {
  stop-color: var(--svg-color--59edfb, #59edfb);
}

.b6jxpenjo {
  d: path("m15.6 17.416l.223-3.933l1.01-.212l.79 2.07l.222-2.075h.789l-.45 4.039h-.678L16.5 14.902l-.116 2.514z");
}

.b8noanbwp {
  stop-color: var(--svg-color--99f3fd, #99f3fd);
}

.ba7mozb-c {
  stop-color: var(--svg-color--166189, #166189);
}

.bctj_xaap {
  d: path("M7.5 20.365L6.49 14.25h1.233l1.016 6.22z");
}

.bi2kzo85x {
  d: path("M9.861 6.716c-.09 0-.111-.074-.111-.106l-.117.212c0 .334.34.55.678.55c.339 0 .672-.216 1.239-.216c.56 0 1.233.323 1.572.323c.27 0 .561-.874.672-1.308c-.45-.328-1.164-.328-1.8-.328c-.444 0-2.022.873-2.133.873");
}

.bn89nzbta {
  stop-color: var(--svg-color--66211c, #66211c);
}

.brcrrd81k {
  d: path("M19.423 14.578v-1.096c1.006.222 1.122.768 1.006 2.075a1.51 1.51 0 0 1-1.345 1.419v-.762c.185-.18.561-.636.561-.985c0-.35-.148-.582-.222-.651");
}

.c3xqvdqwh {
  stop-color: var(--svg-color--5e1b1c, #5e1b1c);
}

.c54voultg {
  stop-color: var(--svg-color--9e3641, #9e3641);
}

.cay8-jbhr {
  stop-color: var(--svg-color--fbffff, #fbffff);
}

.cezou5ojv {
  d: path("m12.782 13.481l.562 4.04h1.127l.45-.329l.789.223v-.44l1.8.217h1.345V13.27H14.92l-.45.106v.439l-.111.44l-.117-.768h-1.46z");
}

.cg358e3uu {
  stop-color: var(--svg-color--229acc, #229acc);
}

.ctnjnobff {
  stop-color: var(--svg-color--fdfcfe, #fdfcfe);
}

.d0oe0wbsh {
  stop-color: var(--svg-color--fcd77f, #fcd77f);
}

.d0um-zb1y {
  stop-color: var(--svg-color--3be0ff, #3be0ff);
}

.dd6r96btf {
  d: path("m4.8 16.977l-.56-5.787l1.905-.545c.9 0 1.916.476 2.139.657l-.561 2.292l.9 2.181l-1.35.873l-.673-.211l-.45-.879l.112 1.53l-1.24.545l-1.46-.217z");
}

.dpm4lkbto {
  d: path("m13.122 13.593l1.123-.106l1.127 3.929l-.9.106l-.18-.705l-1.085.212l-.196.715l-1.011.212zm.36 2.446l.583-.106l-.265-1.032z");
}

.e0epr8wlk {
  stop-color: var(--svg-color--3b99cd, #3b99cd);
}

.e3e6jgbcx {
  d: path("M7.61 7.918c.27.524.488 1.747.562 2.292v.98l-2.022-.106l.672-.657l-.106-.216l.106-.106c-.54-.09-.746-.477-.783-.657l.105-.222c0-.524.53-1.017.795-1.202l.333-.434l.339.545z");
}

.e7kw5ehsw {
  d: path("M10.305 4.535A3.4 3.4 0 0 1 9.3 3.88c0-.217 1.123.106 1.462.328c.238.154.788.546 1.01.763a16 16 0 0 1-1.46-.435z");
}

.eluxjdbir {
  fill: var(--svg-color--6991f0, #6991f0);
  d: path("M10.438 6.055c.037.069.1.116.211.116c.265 0 .334-.217.334-.328a2.2 2.2 0 0 0-.561-.106c-.006.032-.016.07-.016.111a.11.11 0 0 1 .095.106a.105.105 0 0 1-.063.106z");
}

.emf7z-b4w {
  stop-color: var(--svg-color--e85e39, #e85e39);
}

.en_6gms7f {
  fill: var(--svg-color--ffdbc6, #ffdbc6);
  fill-rule: evenodd;
  d: path("m11.434 9.555l-1.122.217l1.46 3.933h1.123l1.128-4.478l-1.011.105l-.79 2.626zm1.641-.138l-.847 2.838l-.852-2.594l-.943.18l1.403 3.774h.99l1.08-4.288l-.825.09z");
}

.f33tz3b9n {
  stop-color: var(--svg-color--2bbef2, #2bbef2);
}

.f45vi66xr {
  stop-color: var(--svg-color--1d68a1, #1d68a1);
}

.f94ouzbcl {
  stop-color: var(--svg-color--be3427, #be3427);
}

.fe1pgfb4g {
  d: path("M13.8 5.082c-.455 0-.942.142-1.128.217c.186.037.651.105 1.011.105s.826-.142 1.012-.211a3.2 3.2 0 0 0-.9-.111z");
}

.ft5dv1b6b {
  fill: none;
}

.fw-9bdlmf {
  stop-color: var(--svg-color--0c5c9b, #0c5c9b);
}

.fwf7tub9v {
  d: path("M10.762 6.06c-.18 0-.228-.212-.228-.328c.18 0 .376.074.45.111c0 .074-.042.217-.222.217");
}

.fzxkbdm2i {
  d: path("M15.373 7.479c-.635.265-.789 1.202-.789 1.641l.519-.44l.159-.216v.217l.222-.217l.789-.44l.333-.434v.217l.34-.217v.106c.36-.17 2.25-.942 3.149-1.308l.228-.545c-.36-.085-3.076 1.128-4.389 1.747c-.074.106-.291.328-.561.328s.111-.29.339-.439z");
}

.gaiki3_rk {
  stop-color: var(--svg-color--1b5d83, #1b5d83);
}

.gd_7vsb9z {
  stop-color: var(--svg-color--dd7f8f, #dd7f8f);
}

.gnve5nb3p {
  d: path("M19.2 17.188v.006h-.794l.45-3.817l.794.105l-.005.016c.582.074 1.43.44 1.35 1.514c-.106 1.456-1.032 2.118-1.8 2.182zm.09-.757c.397-.037.953-.286 1.033-1.09c.069-.779-.392-1.038-.773-1.086l-.265 2.176z");
}

.grxlq1b6y {
  stop-color: var(--svg-color--e6d4c6, #e6d4c6);
}

.gs3umobfp {
  stop-color: var(--svg-color--fff379, #fff379);
}

.gw76e2zkx {
  stop-color: var(--svg-color--2179b8, #2179b8);
}

.h_2h0ebya {
  stop-color: var(--svg-color--ffd871, #ffd871);
}

.hrgj6hr3h {
  stop-color: var(--svg-color--619caa, #619caa);
}

.hrig79nkz {
  stop-color: var(--svg-color--254c6b, #254c6b);
}

.hyth7s1pd {
  fill-rule: evenodd;
  d: path("M16.5 12.285c.196 0 .672-.26.672-.985s-.476-.984-.677-.984c-.196 0-.673.26-.673.984c0 .726.477.985.673.985zm0 1.09c.99 0 1.8-.93 1.8-2.075c0-1.143-.81-2.292-1.8-2.292c-.381 0-.794 0-1.127.106c-.477.376-.678 1.472-.678 2.186c0 .869.132 1.769.794 2.076z");
}

.i_gq3vb_k {
  fill-rule: evenodd;
  d: path("m3.679 15.891l-.45.545c0 1.128.54 3.384 2.7 3.384c1.455 0 3.176-.567 4.77-1.091c1.355-.445 2.615-.863 3.547-.874h.942c1.948.027 4.426.053 4.907-1.53c.562-1.852.562-3.494-5.06-3.6c-4.5-.09-9.445 2.07-11.356 3.166m2.244 3.16a1.11 1.11 0 0 0 1.128-1.09a1.11 1.11 0 0 0-1.128-1.09a1.11 1.11 0 0 0-1.122 1.09a1.11 1.11 0 0 0 1.122 1.09");
}

.i1v9ccnxa {
  stop-color: var(--svg-color--5b1d22, #5b1d22);
}

.i7ey02bhg {
  stop-color: var(--svg-color--6d444c, #6d444c);
}

.il6bxjr1h {
  stop-color: var(--svg-color--f9976b, #f9976b);
}

.in25yj9wo {
  stop-color: var(--svg-color--35c3f3, #35c3f3);
}

.ini-h701j {
  stop-color: var(--svg-color--fefff9, #fefff9);
}

.ip61n4v0g {
  stop-color: var(--svg-color--3ab6f3, #3ab6f3);
}

.ixvot5b7m {
  stop-color: var(--svg-color--71d1ff, #71d1ff);
}

.iyvsrbb8o {
  d: path("M12.672 5.187c.302-.254.943-.72 1.123-.545s-.673.44-1.123.545");
}

.j5kg19b2d {
  stop-color: var(--svg-color--fec35f, #fec35f);
}

.j914bjvha {
  stop-color: var(--svg-color--b24143, #b24143);
}

.jr1mzy0qc {
  fill: var(--svg-color--d7c1c3, #d7c1c3);
  d: path("M15.144 9.987c-.63-.344-.635-1.016-.561-1.413c1.689-.768 4.357-1.8 4.611-1.419c.228.323-3.261 3.272-4.05 2.838z");
}

.jsmslkv_d {
  stop-color: var(--svg-color--374568, #374568);
}

.jx1xcfd7q {
  d: path("M14.021 6.282c-1.35.874-4.05 7.46-4.5 8.402l5.173-.328v-5.02c0-.698.45-1.53.677-1.852h.334l.106-.111h-.556l-.339.106a8 8 0 0 0-.9-1.197z");
}

.k2-vtobij {
  stop-color: var(--svg-color--902524, #902524);
}

.k555vrjgo {
  stop-color: var(--svg-color--f25762, #f25762);
}

.k5rjqimee {
  stop-color: var(--svg-color--d6c8c9, #d6c8c9);
}

.kcnrnobdu {
  stop-color: var(--svg-color--a3f6fb, #a3f6fb);
}

.kkjd42b3y {
  fill: var(--svg-color--fa4b3d, #fa4b3d);
  d: path("M8.512 6.605c-.09.175-.037.292 0 .329c.222-.397.9-1.218 1.8-1.308s1.424.18 1.572.328c.636-.09 1.461.037 1.8.106c-.672-.873-1.233-1.196-2.133-1.308c-.9-.105-1.917.435-2.139.546c-.228.106-.111.217-.228.328c-.106.106-.333.434-.45.545c-.106.106-.106.217-.222.434");
}

.km-diwl_t {
  stop-color: var(--svg-color--e66a12, #e66a12);
}

.kne89tbpx {
  stop-color: var(--svg-color--1c6091, #1c6091);
}

.kovaaccvw {
  stop-color: var(--svg-color--2b7fbf, #2b7fbf);
}

.l_2n9daaj {
  stop-color: var(--svg-color--eb6234, #eb6234);
}

.l-ab5acjm {
  fill: var(--svg-color--6dbedc, #6dbedc);
  d: path("M7.722 14.25H6.494l1.572-.44l1.239.106l-1.578.334z");
}

.l80ruibyg {
  d: path("m12.672 9.777l-1.239-.222l.789 4.15h1.689l1.233-4.256l-1.122-.222l-1.011 2.292l-.339-1.747z");
}

.le315gtod {
  stop-color: var(--svg-color--fc674f, #fc674f);
}

.ljnvkvi3w {
  stop-color: var(--svg-color--9a3441, #9a3441);
}

.lljnzp3se {
  fill: var(--svg-color--934800, #934800);
  d: path("M11.476 6.373a9 9 0 0 1 1.646-.312c-.545 0-1.053.137-1.583.232c-.17.027-.36.112-.577.202c-.338.148-.725.317-1.149.328H9.75l.048.048c.09.074.254.174.402.174c.138 0 .46-.19.805-.397c.159-.095.317-.19.476-.275zm-1.276.63a.5.5 0 0 1-.244-.08a1 1 0 0 1-.09-.052c.389-.04.766-.153 1.112-.334l.318-.132l.085-.027l-.398.233q-.276.159-.556.312l-.137.053a.3.3 0 0 1-.09.027");
}

.lngswp6ud {
  stop-color: var(--svg-color--75bdfe, #75bdfe);
}

.ly4gcqblh {
  fill-rule: evenodd;
  d: path("M15.99 12.052c.16-.185.282-.487.282-.863c0-.37-.127-.672-.281-.857c-.159-.19-.302-.233-.397-.233c-.09 0-.238.042-.392.233c-.159.185-.28.487-.28.857c0 .371.127.678.28.863c.154.186.302.233.392.233c.095 0 .243-.047.397-.233m-.396 1.324c.995 0 1.8-.98 1.8-2.187c0-1.201-.805-2.18-1.8-2.18c-.99 0-1.8.979-1.8 2.18c0 1.208.81 2.187 1.8 2.187");
}

.m-rsdhbhr {
  d: path("m10.088 18.829l-.794-4.908l-1.456.302l-.116.027l1.016 6.22l3.484-.985v-1.307l-2.134.656z");
}

.m0bl40btn {
  stop-color: var(--svg-color--34a7e8, #34a7e8);
}

.m4yr4sbbp {
  stop-color: var(--svg-color--faee84, #faee84);
}

.myr4m5ksw {
  stop-color: var(--svg-color--0e4f75, #0e4f75);
}

.n5zbhm6nq {
  d: path("M11.1 5.08c-2.34.086-3.527 3.458-3.829 5.13l5.962-.216l1.8-1.747c-.34-1.09-1.6-3.256-3.934-3.166");
}

.nddq-vs_r {
  stop-color: var(--svg-color--982827, #982827);
}

.nf9r_ybbj {
  stop-color: var(--svg-color--fafe78, #fafe78);
}

.nmnt8dz9c {
  stop-color: var(--svg-color--59bdfb, #59bdfb);
}

.nsozokb9r {
  stop-color: var(--svg-color--4ee9fe, #4ee9fe);
}

.nvu86ab7j {
  stop-color: var(--svg-color--782424, #782424);
}

.o_k8_db7f {
  stop-color: var(--svg-color--faf37e, #faf37e);
}

.ohnd0ubjj {
  stop-color: var(--svg-color--fe4e4e, #fe4e4e);
}

.on1cm-avk {
  fill: var(--svg-color--110f15, #110f15);
  d: path("m10.009 5.78l-.037-.048l.111-.043c.604 0 .921.133 1.032.218h.096v.09h-.085c-.132.232-.476.545-.942.434a.33.33 0 0 1-.265-.334c0-.111.042-.228.09-.318m.254 0c-.18.063-.254.211-.254.317c0 .127.069.217.201.249c.402.1.71-.18.831-.381c-.212-.148-.53-.186-.778-.186");
}

.orn5pvbkj {
  stop-color: var(--svg-color--ffff75, #ffff75);
}

.p374oab7y {
  stop-color: var(--svg-color--2b9fda, #2b9fda);
}

.p67gip28v {
  stop-color: var(--svg-color--992f34, #992f34);
}

.pg-4fq0md {
  stop-color: var(--svg-color--f15b64, #f15b64);
}

.phdjydl5q {
  stop-color: var(--svg-color--6cbddb, #6cbddb);
}

.pwlwojbeh {
  stop-color: var(--svg-color--de5c64, #de5c64);
}

.px_loss3w {
  stop-color: var(--svg-color--1f90cc, #1f90cc);
}

.q5yvr-b4s {
  stop-color: var(--svg-color--fe5953, #fe5953);
}

.qctn6zb_s {
  stop-color: var(--svg-color--207baa, #207baa);
}

.qola699_e {
  d: path("M13.122 13.593h-1.128l-1.233 4.367H12l1.122-4.373z");
}

.qp1im6b2d {
  stop-color: var(--svg-color--549ee9, #549ee9);
}

.r1a85pb6y {
  stop-color: var(--svg-color--feb05b, #feb05b);
}

.r4ghx9z6l {
  stop-color: var(--svg-color--cc3f35, #cc3f35);
}

.rbh2qkb9z {
  stop-color: var(--svg-color--f35c62, #f35c62);
}

.rc4-_xbkv {
  fill: var(--svg-color--ffdbc6, #ffdbc6);
  fill-rule: evenodd;
  d: path("M6.489 13.81a2.76 2.76 0 0 0 .672-2.181c-.18-.964-.9-1.06-1.239-.985L3 11.523l.561 5.897l1.239-.545V14.8l.339-.217L6.6 16.436l1.233-.763L6.49 13.82zm1.217 1.831l-1.334-1.837l.048-.053c.143-.158.35-.45.498-.825c.153-.371.243-.821.158-1.282c-.09-.46-.301-.699-.518-.82a.92.92 0 0 0-.61-.095l-2.853.852l.546 5.701l1.069-.47v-2.065l.445-.291l1.466 1.858zm-3.213-1.943l-.127-1.477l.069-.02l.106-.038h.01c.201-.074.524-.185.81-.19c.148 0 .297.02.418.105a.57.57 0 0 1 .233.413c.053.355-.2.63-.497.816c-.297.19-.667.317-.921.37zm.08-.105l.09-.022c.508-.132 1.344-.492 1.26-1.07c-.101-.687-.943-.396-1.35-.258l-.107.042z");
}

.rnmrfabyb {
  stop-color: var(--svg-color--1481be, #1481be);
}

.rqm__bczc {
  stop-color: var(--svg-color--10162f, #10162f);
}

.rxuc65bjj {
  stop-color: var(--svg-color--0b4d8a, #0b4d8a);
}

.s9ah406ug {
  stop-color: var(--svg-color--a45f8f, #a45f8f);
}

.sft9xgblt {
  stop-color: var(--svg-color--fd7354, #fd7354);
}

.sigx5tbkt {
  d: path("M3.45 17.744c0 .07.015.149.031.233c.233.699 1.567 1.88 2.663 1.837c2.922-.106 6.078-2.07 8.55-2.07c1.98 0 3.674-.185 4.272-.328c-.222.545-3.822.762-4.95.874c-1.122.105-5.733 2.18-8.1 1.852a2.764 2.764 0 0 1-2.467-2.398");
}

.siuq8p_np {
  stop-color: var(--svg-color--fe9c51, #fe9c51);
}

.sou1-8b_q {
  stop-color: var(--svg-color--cddde4, #cddde4);
}

.su00gzbad {
  fill: var(--svg-color--ffdbc6, #ffdbc6);
  fill-rule: evenodd;
  d: path("m8.622 10.973l1.578-.328v-.869l-2.7.546l.334 4.261l2.477-.656v-.874l-1.577.329v-.985l1.35-.328v-.874l-1.462.328zM10 11.3l-1.467.328v-.725l1.578-.328v-.694l-2.515.508l.318 4.077l2.308-.614v-.7l-1.577.33v-1.16L9.994 12v-.7z");
}

.t0mzh-bsg {
  stop-color: var(--svg-color--fe5754, #fe5754);
}

.t17ibebxu {
  stop-color: var(--svg-color--637c90, #637c90);
}

.t7hie9bir {
  stop-color: var(--svg-color--41acff, #41acff);
}

.tm0zt33dn {
  stop-color: var(--svg-color--3697db, #3697db);
}

.tp68qcbea {
  stop-color: var(--svg-color--12386a, #12386a);
}

.u7lib01wg {
  stop-color: var(--svg-color--fffdce, #fffdce);
}

.u811vwk6d {
  stop-color: var(--svg-color--090f1f, #090f1f);
}

.uahv8ybdf {
  fill: var(--svg-color--ceebfe, #ceebfe);
  d: path("m14.472 13.376l1.35.105l1.122-.211h-2.022z");
}

.udl2bucst {
  stop-color: var(--svg-color--fe4f4b, #fe4f4b);
}

.ui2badbss {
  d: path("m11.434 9.555l-1.122.217l1.46 3.933h1.123l1.128-4.478l-1.011.105l-.79 2.626z");
}

.upze-xbwc {
  d: path("M11.205 3.99q.462.478.9.979a9 9 0 0 1-1.122-.545c-.561-.329-.784-.763-.673-.874c.112-.106.673.217.9.44z");
}

.uqsj89l5f {
  stop-color: var(--svg-color--5d5b70, #5d5b70);
}

.uy5_1bc0w {
  fill: var(--svg-color--776b8e, #776b8e);
  d: path("M8.734 10.212v-.657l.566.545l-.566.106z");
}

.v7pbuprxq {
  stop-color: var(--svg-color--3b89c7, #3b89c7);
}

.vc162zb5q {
  fill: var(--svg-color--151b31, #151b31);
  d: path("M8.171 10.21h-.9c.34-2.292 1.8-4.584 2.928-4.912c-.36.175-.9.947-1.128 1.307H9.3c-1.26 1.398-1.276 2.986-1.128 3.6z");
}

.vgggjxbpf {
  stop-color: var(--svg-color--183f78, #183f78);
}

.vtsjl8b0l {
  stop-color: var(--svg-color--e74425, #e74425);
}

.w0fhw9b0k {
  stop-color: var(--svg-color--fd594f, #fd594f);
}

.w0nzm-bmd {
  stop-color: var(--svg-color--44608e, #44608e);
}

.w62no5b4q {
  stop-color: var(--svg-color--f67141, #f67141);
}

.w886jtvog {
  stop-color: var(--svg-color--34bfe8, #34bfe8);
}

.wb54-1day {
  d: path("m10.2 9.777l-1.916.434l.339.762l.111 2.404l-.9 1.201h1.689l1.948-.439v-.868l-1.165-.217l-.444.217v-.657l1.35-.323l.105-.767l-1.233-.328l.9-.435v-.773l-.784-.222z");
}

.wsab7s0wp {
  stop-color: var(--svg-color--1f93cc, #1f93cc);
}

.wsjyw0bgi {
  d: path("m3 11.524l2.922-.879c.34-.068 1.06.022 1.24.985c.18.958-.371 1.853-.673 2.181l1.344 1.853l-1.233.768l-1.461-1.853l-.339.211v2.081l-1.239.546L3 11.519zm1.461.763l.111 1.307c.487-.106 1.44-.476 1.35-1.09c-.1-.689-.942-.397-1.35-.26l-.106.043z");
}

.x8o3fpb7g {
  fill: var(--svg-color--8a8b8d, #8a8b8d);
  d: path("m12.439 5.207l-.021-.074a.04.04 0 0 1 .002-.032a.04.04 0 0 1 .024-.02c.026-.011.053 0 .058.026l.032.106q.06.006.116.026c.022.01.032.037.022.058s-.037.032-.064.021l-.047-.015l.042.169a.04.04 0 0 1-.042.042a.05.05 0 0 1-.053-.042q-.015-.09-.043-.18a.6.6 0 0 0-.18.026c-.026.011-.053 0-.063-.02a.04.04 0 0 1-.002-.032a.03.03 0 0 1 .01-.013l.013-.009a.5.5 0 0 1 .196-.037");
}

.xcmucccca {
  d: path("m12.223 18.177l-2.14.656l-.444-.217l1.461-.44z");
}

.xdb4kbb0s {
  stop-color: var(--svg-color--152549, #152549);
}

.xit7nq7je {
  stop-color: var(--svg-color--3ddff6, #3ddff6);
}

.xpeaznbhr {
  stop-color: var(--svg-color--fb5a52, #fb5a52);
}

.xxp_0tbrn {
  fill: var(--svg-color--a1354e, #a1354e);
  d: path("M9.634 5.187c-.074 0-.243.021-.333.111c-.117.106-.037.249-.117.328c-.106.106-.45.329-.56.546c-.112.217 0 .217-.112.434c-.09.175-.037.291 0 .328c.672-.873 1.117-1.308 2.022-1.308c.678 0 1.202.18 1.35.329h.34c-.34-.329-.9-.546-1.69-.546c-.56 0-.9.323-.9.212c0-.085.53-.323.794-.434z");
}

.xyeae9bfj {
  fill: var(--svg-color--addfff, #addfff);
  d: path("m18.358 5.775l-3.214.614l2.785-.868l2.054-.329c-.207.07-.683.397-.9.52q-.136.07-.244.18l.07.052l.174.01h.27l-.19.186c-.075.069-.191.08-.318.021a2 2 0 0 1-.255-.053a.4.4 0 0 1-.148-.08a.3.3 0 0 1-.084-.253m.296-.164l-.032.063a.4.4 0 0 0-.037.122c-.005.048 0 .069.016.08l.005.005v-.022a.3.3 0 0 1 .08-.132a1.2 1.2 0 0 1 .206-.159zm.826 2.101l-1.911 2.584l1.974-2.097l1.16-1.673c-.154.149-.657.435-.858.578q-.124.091-.27.142l-.026-.084l.063-.159l.117-.238l-.254.09c-.101.037-.16.132-.154.275q-.037.12-.058.244a.3.3 0 0 0 .01.158a.31.31 0 0 0 .207.18m.275-.19h-.074a.3.3 0 0 1-.127-.016c-.048-.016-.063-.032-.069-.048v-.005a.3.3 0 0 0 .18 0q.104-.042.233-.122z");
}

.y6lomxbgh {
  stop-color: var(--svg-color--4caace, #4caace);
}

.y9_30gv5z {
  stop-color: var(--svg-color--da4f3a, #da4f3a);
}

.y99-vob1r {
  fill: var(--svg-color--d9d9d9, #d9d9d9);
  d: path("M10.703 5.896a.053.053 0 0 1-.053.053a.05.05 0 0 1-.054-.032l-.005-.021c0-.027.027-.053.053-.053c.032 0 .059.026.059.053");
}

.yclc5xbqn {
  stop-color: var(--svg-color--ae4213, #ae4213);
}

.yflrh3bwq {
  stop-color: var(--svg-color--cb3445, #cb3445);
}

.yu-p3ybhl {
  stop-color: var(--svg-color--722432, #722432);
}

.z-1280bmt {
  fill: var(--svg-color--fdeadc, #fdeadc);
  d: path("M10.2 7.045c-.18 0-.376-.149-.45-.217c.784 0 1.461-.546 1.906-.546c-.508.244-1.234.763-1.456.763");
}

.zgz5aykhk {
  d: path("M12.9 5.843c0-.106-.116-.762-.227-.873c-.09-.085-.789.037-1.128.106c-.222.11 1.017.767 1.128.767s.222.106.222 0z");
}

.zrpfm0eqr {
  stop-color: var(--svg-color--ffea76, #ffea76);
}

.zz5mp1bkb {
  stop-color: var(--svg-color--b2c9e8, #b2c9e8);
}

</style>
