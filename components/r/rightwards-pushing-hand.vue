<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path class="ma_0w0k7g"/><path fill="url(#icIqnUc)" class="icp2bwbof"/><path fill="url(#i2ethIe)" class="icp2bwbof"/><path fill="url(#idoFQhg)" class="icp2bwbof"/><path fill="url(#ivw0O4b)" class="icp2bwbof"/><path fill="url(#iLsqJDb)" class="icp2bwbof"/><path fill="url(#iUhS8Wd)" class="icp2bwbof"/><path fill="url(#i0Up8vd)" class="icp2bwbof"/><path fill="url(#iTtTvQb)" class="icp2bwbof"/><path fill="url(#iUhT64P)" class="icp2bwbof"/><path fill="url(#itXytfb)" class="icp2bwbof"/><path fill="url(#im43Afd)" class="icp2bwbof"/><path fill="url(#iI4F36c)" class="icp2bwbof"/><path fill="url(#ivNPYhd)" class="icp2bwbof"/><path fill="url(#icMPmQA)" class="icp2bwbof"/><path fill="url(#ikT2u8d)" class="w9b2spbia"/><path class="eo8vwnsqv"/><path fill="url(#itAxWde)" class="e1dbxpbus"/><path fill="url(#iMUL0Qc)" class="h7odlkbxb"/><path fill="url(#iSYFlbe)" class="h7odlkbxb"/><path fill="url(#ivCUdZc)" class="h7odlkbxb"/><path fill="url(#irVvmie)" class="h7odlkbxb"/><path fill="url(#iDrG7Zb)" class="h7odlkbxb"/><path fill="url(#ijUjAgc)" class="l1r-6tcnd"/><path fill="url(#iHaHqje)" class="l1r-6tcnd"/><path fill="url(#ifs5che)" class="l1r-6tcnd"/><path fill="url(#i6mYXTS)" class="l1r-6tcnd"/><path fill="url(#is1ztSd)" class="l1r-6tcnd"/><path fill="url(#icjOeCc)" class="mx8nfobnr"/><path fill="url(#iRDmcjc)" class="mx8nfobnr"/><path fill="url(#iIqgdTc)" class="mx8nfobnr"/><path fill="url(#iuIhePc)" class="mx8nfobnr"/><path fill="url(#iKr9asY)" class="mx8nfobnr"/><path fill="url(#iYUY5me)" class="ht-zrjbae"/><path fill="url(#i5BBv5B)" class="ht-zrjbae"/><path fill="url(#itvTiGc)" class="ht-zrjbae"/><path fill="url(#iODk1me)" class="ht-zrjbae"/><path class="h2g6-jb0d"/><path fill="url(#igvKx3d)" class="a_vuny-qj"/><path fill="url(#ig27zoc)" class="a_vuny-qj"/><path fill="url(#i27tcdb)" class="a_vuny-qj"/><path fill="url(#i3Sz9eb)" class="a_vuny-qj"/><path fill="url(#iDmnQLQ)" class="a_vuny-qj"/><path fill="url(#iDWiJhc)" class="a_vuny-qj"/><path fill="url(#i7gFugb)" class="a_vuny-qj"/><path fill="url(#ir6hOjc)" class="a_vuny-qj"/><path fill="url(#iDC7yIb)" class="gd0q7bbnj"/><path fill="url(#ixS4Dab)" class="gd0q7bbnj"/><path fill="url(#iwced7d)" class="gd0q7bbnj"/><path fill="url(#ixXMCMc)" class="gd0q7bbnj"/><path fill="url(#iXl4pCm)" class="gd0q7bbnj"/></g><defs><radialGradient id="idoFQhg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50001 10.00002 -24.1071 -3.61608 14.488 21)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="eebf5ub9j"/><stop offset=".874" class="k90wp6bmc"/></radialGradient><radialGradient id="iUhS8Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68767 6.50126 -6.0031 -.63498 17.668 20.942)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="i6o-qu9fo"/><stop offset="1" class="r5htkxbvz"/></radialGradient><radialGradient id="i0Up8vd" cx="0" cy="0" r="1" gradientTransform="matrix(.53853 7.97018 -6.15248 .41571 17.088 21.648)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="pf1xml9sl"/><stop offset="1" class="rd54rdzck"/></radialGradient><radialGradient id="iTtTvQb" cx="0" cy="0" r="1" gradientTransform="matrix(16.01925 10.36522 -13.13305 20.29688 1.482 16.766)" gradientUnits="userSpaceOnUse"><stop offset=".974" class="v10_5zwzh"/><stop offset="1" class="jn_5q-btc"/></radialGradient><radialGradient id="itXytfb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.822 5.35543 -6.78547 -9.91068 16.821 26.128)" gradientUnits="userSpaceOnUse"><stop class="yk1d-rbcz"/><stop offset="1" class="vy67icc3g"/></radialGradient><radialGradient id="im43Afd" cx="0" cy="0" r="1" gradientTransform="rotate(18.358 -64.362 4.587)scale(20.8924 11.2164)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="i-lj0-gmv"/><stop offset="1" class="vvyrbnhyh"/></radialGradient><radialGradient id="ivNPYhd" cx="0" cy="0" r="1" gradientTransform="matrix(.37564 6.01026 -5.0257 .3141 16.684 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".02" class="gkxiyeb3x"/><stop offset=".645" class="gkxiyeb3x"/><stop offset=".705" class="s4qko67rc"/><stop offset=".947" class="gkxiyeb3x"/></radialGradient><radialGradient id="icMPmQA" cx="0" cy="0" r="1" gradientTransform="rotate(90.939 -.538 17.327)scale(8.59395 7.27784)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="tqnkvib7j"/><stop offset="1" class="bdynesb7r"/></radialGradient><radialGradient id="iSYFlbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.4421 -8.96427 5.94373 .95618 22.66 16.384)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="it206jbsy"/><stop offset="1" class="u0h5jybmg"/></radialGradient><radialGradient id="ivCUdZc" cx="0" cy="0" r="1" gradientTransform="matrix(.24459 3.88283 -.58052 .03657 22.92 11.08)" gradientUnits="userSpaceOnUse"><stop class="cw3zcw38m"/><stop offset="1" class="s09sbkbvb"/></radialGradient><radialGradient id="iDrG7Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.44235 .57699 -.4164 -.31924 24.298 8.339)" gradientUnits="userSpaceOnUse"><stop class="ivx1b_bju"/><stop offset="1" class="ldzi-sbgr"/></radialGradient><radialGradient id="iHaHqje" cx="0" cy="0" r="1" gradientTransform="matrix(1.4758 -10.24131 6.11321 .88093 20.254 15.264)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="it206jbsy"/><stop offset="1" class="u0h5jybmg"/></radialGradient><radialGradient id="ifs5che" cx="0" cy="0" r="1" gradientTransform="matrix(.2503 4.43595 -.66999 .0378 20.52 9.204)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="v2x24m9bf"/><stop offset="1" class="am82-szit"/></radialGradient><radialGradient id="is1ztSd" cx="0" cy="0" r="1" gradientTransform="rotate(124.48 9.367 8.808)scale(.79966 .55774)" gradientUnits="userSpaceOnUse"><stop class="ivx1b_bju"/><stop offset="1" class="ldzi-sbgr"/></radialGradient><radialGradient id="iRDmcjc" cx="0" cy="0" r="1" gradientTransform="rotate(-122.448 14.717 -.748)scale(10.5643 4.46473)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="w1hhjvb1e"/><stop offset="1" class="xf2dogbeb"/></radialGradient><radialGradient id="iIqgdTc" cx="0" cy="0" r="1" gradientTransform="matrix(.3279 5.3448 -1.09214 .067 17.979 9.337)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="v2x24m9bf"/><stop offset="1" class="am82-szit"/></radialGradient><radialGradient id="iKr9asY" cx="0" cy="0" r="1" gradientTransform="matrix(.26917 1.23816 -.92319 .2007 19.442 4.336)" gradientUnits="userSpaceOnUse"><stop class="ivx1b_bju"/><stop offset="1" class="ldzi-sbgr"/></radialGradient><radialGradient id="i5BBv5B" cx="0" cy="0" r="1" gradientTransform="matrix(-.45637 1.49075 -1.1158 -.34158 16.878 6.151)" gradientUnits="userSpaceOnUse"><stop class="ivx1b_bju"/><stop offset="1" class="ldzi-sbgr"/></radialGradient><radialGradient id="itvTiGc" cx="0" cy="0" r="1" gradientTransform="rotate(43.773 -8.902 26.867)scale(2.82875 .8004)" gradientUnits="userSpaceOnUse"><stop class="fwxucb51f"/><stop offset="1" class="pmgphlkow"/></radialGradient><radialGradient id="ig27zoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.55105 7.96632 -4.84722 -.3353 12.05 18.744)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="qw9si_bcq"/><stop offset="1" class="r3d2ebc0u"/></radialGradient><radialGradient id="i27tcdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.43559 6.7733 -4.1213 -.26504 12.05 18.745)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="j7mihdcgi"/><stop offset="1" class="zh95tprrk"/></radialGradient><radialGradient id="i3Sz9eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73121 5.2724 -2.38869 -.33128 12.346 19.322)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="dxp3wsbik"/><stop offset="1" class="q6kfqobyp"/></radialGradient><radialGradient id="iDmnQLQ" cx="0" cy="0" r="1" gradientTransform="matrix(2.2706 5.15695 -1.46238 .64389 16.156 13.934)" gradientUnits="userSpaceOnUse"><stop class="ckx0-obzi"/><stop offset="1" class="qxdqoqbix"/></radialGradient><radialGradient id="iDWiJhc" cx="0" cy="0" r="1" gradientTransform="rotate(46.273 -7.679 24.04)scale(3.67463 2.23588)" gradientUnits="userSpaceOnUse"><stop class="d0ptz0bpd"/><stop offset="1" class="qxdqoqbix"/></radialGradient><radialGradient id="ir6hOjc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33231 -3.55487 2.163 -3.24452 16.194 23.662)" gradientUnits="userSpaceOnUse"><stop class="fynrnl9gn"/><stop offset="1" class="w8gfh4buw"/></radialGradient><radialGradient id="iDC7yIb" cx="0" cy="0" r="1" gradientTransform="matrix(2.4826 1.59919 -1.46857 2.27982 13.889 23.916)" gradientUnits="userSpaceOnUse"><stop class="tfyupgyie"/><stop offset="1" class="tzqf1ibwq"/></radialGradient><radialGradient id="ixS4Dab" cx="0" cy="0" r="1" gradientTransform="matrix(2.27111 1.71814 -1.57781 2.08561 12.783 22.297)" gradientUnits="userSpaceOnUse"><stop class="uykv4tzfl"/><stop offset="1" class="ammtk1b2l"/></radialGradient><radialGradient id="iwced7d" cx="0" cy="0" r="1" gradientTransform="rotate(96.195 1.446 17.788)scale(4.53816 2.72633)" gradientUnits="userSpaceOnUse"><stop class="sze7ve8et"/><stop offset="1" class="ktutpqbow"/></radialGradient><radialGradient id="ixXMCMc" cx="0" cy="0" r="1" gradientTransform="rotate(94.279 1.923 16.928)scale(2.03257 .86339)" gradientUnits="userSpaceOnUse"><stop class="ivx1b_bju"/><stop offset="1" class="ldzi-sbgr"/></radialGradient><radialGradient id="iXl4pCm" cx="0" cy="0" r="1" gradientTransform="rotate(100.784 2.727 17.412)scale(4.3393 3.98488)" gradientUnits="userSpaceOnUse"><stop class="zs1o4tlrc"/><stop offset="1" class="v5fyc58lm"/></radialGradient><linearGradient id="icIqnUc" x1="8.488" x2="8.999" y1="27" y2="31.063" gradientUnits="userSpaceOnUse"><stop offset=".456" class="wz0ektb2t"/><stop offset=".974" class="ink3gpbzz"/><stop offset="1" class="odhggkl1x"/></linearGradient><linearGradient id="i2ethIe" x1="15.487" x2="12.362" y1="30.047" y2="22.991" gradientUnits="userSpaceOnUse"><stop class="ajic0q7cm"/><stop offset="1" class="m7gdckjal"/></linearGradient><linearGradient id="ivw0O4b" x1="-.562" x2="7.112" y1="27.45" y2="26.309" gradientUnits="userSpaceOnUse"><stop class="v6d9zubux"/><stop offset="1" class="bh-87dbgb"/></linearGradient><linearGradient id="iLsqJDb" x1="6.738" x2="8.55" y1="18.063" y2="30.25" gradientUnits="userSpaceOnUse"><stop offset=".052" class="gmmht-bmp"/><stop offset=".313" class="pe70qdb4r"/><stop offset=".716" class="gmmht-bmp"/></linearGradient><linearGradient id="iUhT64P" x1="8.999" x2="8.999" y1="17.278" y2="31.483" gradientUnits="userSpaceOnUse"><stop offset=".25" class="glhjr8b8a"/><stop offset=".658" class="dfx-3gbqu"/><stop offset="1" class="v3mqk9bny"/></linearGradient><linearGradient id="iI4F36c" x1="7.87" x2="8.713" y1="26.209" y2="30.964" gradientUnits="userSpaceOnUse"><stop offset=".67" class="s-b47gbty"/><stop offset=".804" class="j-f1eub7w"/></linearGradient><linearGradient id="ikT2u8d" x1="13.86" x2="15.971" y1="21.022" y2="26.633" gradientUnits="userSpaceOnUse"><stop class="zbsau8bfu"/><stop offset=".525" class="xwfgiz_7s"/><stop offset=".844" class="z2viy5bme"/><stop offset=".932" class="l0f9_abst"/></linearGradient><linearGradient id="itAxWde" x1="23.777" x2="19.224" y1="13.549" y2="25.969" gradientUnits="userSpaceOnUse"><stop offset=".107" class="a3d1q97ux"/><stop offset=".308" class="sfkl74bxu"/><stop offset=".598" class="qynjq7aec"/><stop offset="1" class="abvozrbgg"/></linearGradient><linearGradient id="iMUL0Qc" x1="25.544" x2="21.624" y1="11.857" y2="11.857" gradientUnits="userSpaceOnUse"><stop class="fq7xu5b5a"/><stop offset=".109" class="ilrpvdsmh"/><stop offset=".333" class="e7jb-vbpi"/><stop offset=".521" class="f_5dzpbms"/><stop offset=".661" class="b9chg4uto"/><stop offset=".712" class="wppg5gbrl"/></linearGradient><linearGradient id="irVvmie" x1="24.863" x2="23.66" y1="12.797" y2="15.125" gradientUnits="userSpaceOnUse"><stop offset=".226" class="mf-jtwozd"/><stop offset=".572" class="imvnuoowq"/></linearGradient><linearGradient id="ijUjAgc" x1="23.206" x2="19.195" y1="10.091" y2="10.091" gradientUnits="userSpaceOnUse"><stop class="fq7xu5b5a"/><stop offset=".109" class="ilrpvdsmh"/><stop offset=".333" class="e7jb-vbpi"/><stop offset=".477" class="f_5dzpbms"/><stop offset=".661" class="b9chg4uto"/><stop offset=".712" class="wppg5gbrl"/></linearGradient><linearGradient id="i6mYXTS" x1="22.509" x2="21.05" y1="11.166" y2="13.695" gradientUnits="userSpaceOnUse"><stop offset=".226" class="mf-jtwozd"/><stop offset=".572" class="imvnuoowq"/></linearGradient><linearGradient id="icjOeCc" x1="20.994" x2="14.48" y1="9.265" y2="9.265" gradientUnits="userSpaceOnUse"><stop class="fq7xu5b5a"/><stop offset=".109" class="ilrpvdsmh"/><stop offset=".333" class="e7jb-vbpi"/><stop offset=".477" class="f_5dzpbms"/><stop offset=".661" class="b9chg4uto"/><stop offset=".712" class="wppg5gbrl"/></linearGradient><linearGradient id="iuIhePc" x1="19.862" x2="18.418" y1="10.546" y2="13.954" gradientUnits="userSpaceOnUse"><stop offset=".226" class="mf-jtwozd"/><stop offset=".572" class="imvnuoowq"/></linearGradient><linearGradient id="iYUY5me" x1="18.474" x2="14.505" y1="9.65" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="posyr3b3x"/><stop offset=".24" class="jc5vk4p_i"/><stop offset=".542" class="guy29_bpm"/><stop offset=".776" class="hg7tbhmri"/><stop offset="1" class="umokeccgz"/></linearGradient><linearGradient id="iODk1me" x1="14.872" x2="19.099" y1="10.194" y2="13.445" gradientUnits="userSpaceOnUse"><stop offset=".789" class="xr07nxbnn"/><stop offset="1" class="q2r_e-beb"/></linearGradient><linearGradient id="igvKx3d" x1="13.182" x2="15.462" y1="11.278" y2="20.688" gradientUnits="userSpaceOnUse"><stop class="aqp8m292r"/><stop offset="1" class="igy525bpv"/></linearGradient><linearGradient id="i7gFugb" x1="19.462" x2="17.58" y1="18.976" y2="19.207" gradientUnits="userSpaceOnUse"><stop class="b8bjw039c"/><stop offset="1" class="y1m56true"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rightwards-pushing-hand" /></template>
<style>
.a_vuny-qj {
  d: path("M16.996 13.928c.817 1.407 1.592 2.091 1.877 2.257c.088.05 1.863 2.455-1.212 5.876c-1.669 1.469-4.85 3.505-4.279-1.24c.062-.517.56-1.798.658-2.18c.03-.317-.146-.993-.255-1.29c-.234-.764-.681-1.413-1.445-2.94c-.764-1.529.047-3.223 1.684-3.13c1.637.094 1.95.888 2.972 2.647");
}

.a3d1q97ux {
  stop-color: var(--svg-color--ffed5c, #FFED5C);
}

.abvozrbgg {
  stop-color: var(--svg-color--f6916d, #F6916D);
}

.ajic0q7cm {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
}

.am82-szit {
  stop-color: var(--svg-color--f29122, #F29122);
  stop-opacity: 0;
}

.ammtk1b2l {
  stop-color: var(--svg-color--bc7936, #BC7936);
  stop-opacity: 0;
}

.aqp8m292r {
  stop-color: var(--svg-color--eeb929, #EEB929);
}

.b8bjw039c {
  stop-color: var(--svg-color--ffdb3b, #FFDB3B);
}

.b9chg4uto {
  stop-color: var(--svg-color--ffaf3a, #FFAF3A);
}

.bdynesb7r {
  stop-color: var(--svg-color--572685, #572685);
  stop-opacity: 0;
}

.bh-87dbgb {
  stop-color: var(--svg-color--465eff, #465EFF);
  stop-opacity: 0;
}

.ckx0-obzi {
  stop-color: var(--svg-color--ffdc40, #FFDC40);
}

.cw3zcw38m {
  stop-color: var(--svg-color--f39222, #F39222);
}

.d0ptz0bpd {
  stop-color: var(--svg-color--ffe756, #FFE756);
}

.dfx-3gbqu {
  stop-color: var(--svg-color--5736f5, #5736F5);
}

.dxp3wsbik {
  stop-color: var(--svg-color--c4764b, #C4764B);
}

.e1dbxpbus {
  d: path("M24.078 21.687c-1.05 2.271-3.92 3.744-5.223 4.196c-.56.18-2.16.195-4.087-1.184c-2.408-1.723-1.134-4.65-1.067-4.96s.31-.93.343-1.113c.034-.184-.1-.954-.285-1.44c-.147-.388-.63-1.311-.853-1.724l2.829-3.332l9.772-.255c.026 1.097.063 3.58 0 4.74v.011c-.078 1.442-.12 2.229-1.43 5.06");
}

.e7jb-vbpi {
  stop-color: var(--svg-color--ffe85c, #FFE85C);
}

.eebf5ub9j {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
}

.eo8vwnsqv {
  fill: var(--svg-color--ffdb3b, #FFDB3B);
  d: path("M24.078 21.687c-1.05 2.271-3.92 3.744-5.223 4.196c-.56.18-2.16.195-4.087-1.184c-2.408-1.723-1.134-4.65-1.067-4.96s.31-.93.343-1.113c.034-.184-.1-.954-.285-1.44c-.147-.388-.63-1.311-.853-1.724l2.829-3.332l9.772-.255c.026 1.097.063 3.58 0 4.74v.011c-.078 1.442-.12 2.229-1.43 5.06");
}

.f_5dzpbms {
  stop-color: var(--svg-color--ffd651, #FFD651);
}

.fq7xu5b5a {
  stop-color: var(--svg-color--ffdb54, #FFDB54);
}

.ft5dv1b6b {
  fill: none;
}

.fwxucb51f {
  stop-color: var(--svg-color--b85227, #B85227);
}

.fynrnl9gn {
  stop-color: var(--svg-color--f7956b, #F7956B);
}

.gd0q7bbnj {
  d: path("m15.87 12.126l9.637-.25c.026 1.096.063 3.58 0 4.739v.011c-.078 1.442-.12 2.229-1.43 5.06c-1.049 2.273-3.918 3.745-5.222 4.198c-.56.18-2.16.194-4.087-1.185c-1.46-1.044-1.566-2.532-1.409-3.61q.009-.13.024-.268c.034-.329.245-.941.423-1.457c.103-.298.194-.564.234-.724l.005-.022c.029-.197-.104-.953-.286-1.432c-.147-.388-.63-1.31-.853-1.724l.009-.01c-.17-.314-.361-.673-.574-1.099c-.764-1.528.046-3.165 1.684-3.071c.906.052 1.406.318 1.846.844");
}

.gkxiyeb3x {
  stop-color: var(--svg-color--7232f9, #7232F9);
  stop-opacity: 0;
}

.glhjr8b8a {
  stop-color: var(--svg-color--603d8b, #603D8B);
}

.gmmht-bmp {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0;
}

.guy29_bpm {
  stop-color: var(--svg-color--fec448, #FEC448);
}

.h2g6-jb0d {
  fill: var(--svg-color--ffc640, #FFC640);
  d: path("M16.996 13.928c.817 1.407 1.592 2.091 1.877 2.257c.088.05 1.863 2.455-1.212 5.876c-1.669 1.469-4.85 3.505-4.279-1.24c.062-.517.56-1.798.658-2.18c.03-.317-.146-.993-.255-1.29c-.234-.764-.681-1.413-1.445-2.94c-.764-1.529.047-3.223 1.684-3.13c1.637.094 1.95.888 2.972 2.647");
}

.h7odlkbxb {
  d: path("m25.484 11.896l.06 2.666c-1.687-.202-2.602-1.26-2.602-2.743c-.012-.255-.046-.838-.09-1.767c-.035-.742-.143-2.258-.192-2.923c.252-.083.895-.174 1.454.123c1.352.608 1.252 1.987 1.37 4.644");
}

.hg7tbhmri {
  stop-color: var(--svg-color--d8a324, #D8A324);
}

.ht-zrjbae {
  d: path("M18.584 10.228c.216 1.956.585 2.715.743 2.85c-.198 1.232-.184 4.19-.743 4.61c-.966.726-2.705-1.725-3.446-2.076l-.417-3.03c-.203-1.63-.626-5.025-.698-5.575c-.09-.686.135-2.398 1.824-2.455s2.174 1.374 2.264 1.949l.003.02c.09.57.203 1.291.47 3.707");
}

.i-lj0-gmv {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
  stop-opacity: 0;
}

.i6o-qu9fo {
  stop-color: var(--svg-color--852dbd, #852DBD);
}

.icp2bwbof {
  d: path("m17.998 26.047l-3.027-8.769c-.059.216-.94.29-1.373.3L0 19.93v11.553l14.752-2.527c2.322-.306 3.126-2.074 3.246-2.91");
}

.igy525bpv {
  stop-color: var(--svg-color--eeb929, #EEB929);
  stop-opacity: 0;
}

.ilrpvdsmh {
  stop-color: var(--svg-color--ffe65a, #FFE65A);
}

.imvnuoowq {
  stop-color: var(--svg-color--ffed5d, #FFED5D);
}

.ink3gpbzz {
  stop-color: var(--svg-color--9d68ff, #9D68FF);
}

.it206jbsy {
  stop-color: var(--svg-color--f9cd40, #F9CD40);
  stop-opacity: 0;
}

.ivx1b_bju {
  stop-color: var(--svg-color--ffec68, #FFEC68);
}

.j-f1eub7w {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
}

.j7mihdcgi {
  stop-color: var(--svg-color--e78d4e, #E78D4E);
}

.jc5vk4p_i {
  stop-color: var(--svg-color--ffe55d, #FFE55D);
}

.jn_5q-btc {
  stop-color: var(--svg-color--806dd1, #806DD1);
}

.k90wp6bmc {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
  stop-opacity: 0;
}

.ktutpqbow {
  stop-color: var(--svg-color--ffd436, #FFD436);
  stop-opacity: 0;
}

.l0f9_abst {
  stop-color: var(--svg-color--e77b8a, #E77B8A);
}

.l1r-6tcnd {
  d: path("M22.905 10.705c.037 1.253.216 2.174.301 2.477c-.965-.182-2.697-.41-2.587-2.714a96 96 0 0 0-.11-2.451c-.036-.629-.136-2.46-.255-3.389c.255-.036.693-.128 1.476.383c.784.51.83 1.339.92 1.977c.091.637.21 2.15.255 3.716");
}

.ldzi-sbgr {
  stop-color: var(--svg-color--ffec68, #FFEC68);
  stop-opacity: 0;
}

.m7gdckjal {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
  stop-opacity: 0;
}

.ma_0w0k7g {
  fill: var(--svg-color--8248dd, #8248DD);
  d: path("m17.998 26.047l-3.027-8.769c-.059.216-.94.29-1.373.3L0 19.93v11.553l14.752-2.527c2.322-.306 3.126-2.074 3.246-2.91");
}

.mf-jtwozd {
  stop-color: var(--svg-color--ffed5d, #FFED5D);
  stop-opacity: 0;
}

.mx8nfobnr {
  d: path("M20.617 10.028c.062 1.683.267 1.688.377 1.974c-1.07 1.51-3.642.886-4.793.385v-7.76c.107-.716.707-2.1 2.245-1.895c1.923.255 1.88 2.214 1.958 3.315s.165 2.864.212 3.98");
}

.odhggkl1x {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
  stop-opacity: 0;
}

.pe70qdb4r {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0.62;
}

.pf1xml9sl {
  stop-color: var(--svg-color--852aab, #852AAB);
}

.pmgphlkow {
  stop-color: var(--svg-color--b85227, #B85227);
  stop-opacity: 0;
}

.posyr3b3x {
  stop-color: var(--svg-color--ffdc43, #FFDC43);
}

.q2r_e-beb {
  stop-color: var(--svg-color--ffed5b, #FFED5B);
}

.q6kfqobyp {
  stop-color: var(--svg-color--c4764b, #C4764B);
  stop-opacity: 0;
}

.qw9si_bcq {
  stop-color: var(--svg-color--f8a359, #F8A359);
}

.qxdqoqbix {
  stop-color: var(--svg-color--ffe756, #FFE756);
  stop-opacity: 0;
}

.qynjq7aec {
  stop-color: var(--svg-color--ffcd39, #FFCD39);
}

.r3d2ebc0u {
  stop-color: var(--svg-color--f8a359, #F8A359);
  stop-opacity: 0;
}

.r5htkxbvz {
  stop-color: var(--svg-color--852dbd, #852DBD);
  stop-opacity: 0;
}

.rd54rdzck {
  stop-color: var(--svg-color--6f32fb, #6F32FB);
  stop-opacity: 0;
}

.s-b47gbty {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
  stop-opacity: 0;
}

.s09sbkbvb {
  stop-color: var(--svg-color--f39222, #F39222);
  stop-opacity: 0;
}

.s4qko67rc {
  stop-color: var(--svg-color--7232f9, #7232F9);
}

.sfkl74bxu {
  stop-color: var(--svg-color--ffe54b, #FFE54B);
}

.sze7ve8et {
  stop-color: var(--svg-color--ffd436, #FFD436);
}

.tfyupgyie {
  stop-color: var(--svg-color--d37852, #D37852);
}

.tqnkvib7j {
  stop-color: var(--svg-color--572685, #572685);
}

.tzqf1ibwq {
  stop-color: var(--svg-color--d37852, #D37852);
  stop-opacity: 0;
}

.u0h5jybmg {
  stop-color: var(--svg-color--f9cd40, #F9CD40);
}

.umokeccgz {
  stop-color: var(--svg-color--b38b44, #B38B44);
}

.uykv4tzfl {
  stop-color: var(--svg-color--bc7936, #BC7936);
}

.v10_5zwzh {
  stop-color: var(--svg-color--806dd1, #806DD1);
  stop-opacity: 0;
}

.v2x24m9bf {
  stop-color: var(--svg-color--f29122, #F29122);
}

.v3mqk9bny {
  stop-color: var(--svg-color--603d8b, #603D8B);
  stop-opacity: 0;
}

.v5fyc58lm {
  stop-color: var(--svg-color--ffe853, #FFE853);
  stop-opacity: 0;
}

.v6d9zubux {
  stop-color: var(--svg-color--465eff, #465EFF);
}

.vvyrbnhyh {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
}

.vy67icc3g {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
  stop-opacity: 0;
}

.w1hhjvb1e {
  stop-color: var(--svg-color--ba9947, #BA9947);
  stop-opacity: 0;
}

.w8gfh4buw {
  stop-color: var(--svg-color--faa85a, #FAA85A);
  stop-opacity: 0;
}

.w9b2spbia {
  d: path("M17.537 26.225c.865-.173 1.417-.37 1.584-.447c-2.339-3.984-6.979-11.862-6.829-11.512c.188.437 1.016 2 1.383 2.718c.367.72.36 1.602.36 1.758s-.29.68-.36 1.008c-.07.078-.633.625-.797 1.828c-.131.963-.099 1.622-.066 1.832c.094 1.241.6 1.906 1.021 2.384c.734.834 1.871.87 2.136.828c.138-.022.486-.182 1.568-.397");
}

.wppg5gbrl {
  stop-color: var(--svg-color--f49321, #F49321);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.wz0ektb2t {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
}

.xf2dogbeb {
  stop-color: var(--svg-color--ba9947, #BA9947);
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xwfgiz_7s {
  stop-color: var(--svg-color--cc8034, #CC8034);
}

.y1m56true {
  stop-color: var(--svg-color--ffdb3b, #FFDB3B);
  stop-opacity: 0;
}

.yk1d-rbcz {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
}

.z2viy5bme {
  stop-color: var(--svg-color--e17a5d, #E17A5D);
}

.zbsau8bfu {
  stop-color: var(--svg-color--a16d37, #A16D37);
}

.zh95tprrk {
  stop-color: var(--svg-color--e78d4e, #E78D4E);
  stop-opacity: 0;
}

.zs1o4tlrc {
  stop-color: var(--svg-color--ffe853, #FFE853);
}

</style>
