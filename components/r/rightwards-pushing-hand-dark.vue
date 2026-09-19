<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path class="ma_0w0k7g"/><path fill="url(#icIqnUc)" class="icp2bwbof"/><path fill="url(#i2ethIe)" class="icp2bwbof"/><path fill="url(#idoFQhg)" class="icp2bwbof"/><path fill="url(#ivw0O4b)" class="icp2bwbof"/><path fill="url(#iLsqJDb)" class="icp2bwbof"/><path fill="url(#iUhS8Wd)" class="icp2bwbof"/><path fill="url(#i0Up8vd)" class="icp2bwbof"/><path fill="url(#iTtTvQb)" class="icp2bwbof"/><path fill="url(#iUhT64P)" class="icp2bwbof"/><path fill="url(#itXytfb)" class="icp2bwbof"/><path fill="url(#im43Afd)" class="icp2bwbof"/><path fill="url(#iI4F36c)" class="icp2bwbof"/><path fill="url(#ivNPYhd)" class="icp2bwbof"/><path fill="url(#icMPmQA)" class="icp2bwbof"/><path fill="url(#id8JlUb)" class="w9b2spbia"/><path class="ooa-e1dmy"/><path fill="url(#ibLxjOs)" class="ujer3lbrk"/><path fill="url(#iJi3lgC)" class="h7odlkbxb"/><path fill="url(#iznMLJm)" class="h7odlkbxb"/><path fill="url(#iuJq2nb)" class="h7odlkbxb"/><path fill="url(#ilJSVSb)" class="h7odlkbxb"/><path fill="url(#ibuVBve)" class="h7odlkbxb"/><path fill="url(#i0m2Vbf)" class="l1r-6tcnd"/><path fill="url(#i3Q2jwe)" class="l1r-6tcnd"/><path fill="url(#iTA9WBc)" class="l1r-6tcnd"/><path fill="url(#ilCjv0d)" class="l1r-6tcnd"/><path fill="url(#iEn6Der)" class="l1r-6tcnd"/><path fill="url(#ingtW6d)" class="mx8nfobnr"/><path fill="url(#iJC5WUd)" class="mx8nfobnr"/><path fill="url(#iHOUIfQ)" class="mx8nfobnr"/><path fill="url(#ishB7He)" class="mx8nfobnr"/><path fill="url(#i59gWhu)" class="mx8nfobnr"/><path fill="url(#icwqDJv)" class="ht-zrjbae"/><path fill="url(#iM4dFZC)" class="ht-zrjbae"/><path fill="url(#ipbnUyb)" class="ht-zrjbae"/><path fill="url(#im0xSEb)" class="ht-zrjbae"/><path fill="url(#ilhjDDb)" class="ht-zrjbae"/><path class="b_w6p3g-t"/><path fill="url(#ihFu0Rb)" class="a_vuny-qj"/><path fill="url(#ilnGElb)" class="a_vuny-qj"/><path fill="url(#ivvQqBe)" class="a_vuny-qj"/><path fill="url(#iPRI25L)" class="a_vuny-qj"/><path fill="url(#i8exRHc)" class="a_vuny-qj"/><path fill="url(#i18iMrd)" class="a_vuny-qj"/><path fill="url(#iCJF9Yd)" class="a_vuny-qj"/><path fill="url(#ijNZNzb)" class="a_vuny-qj"/><path fill="url(#ipmeibe)" class="a_vuny-qj"/><path fill="url(#iRiu1Lj)" class="a_vuny-qj"/><path fill="url(#i7HsYId)" class="gd0q7bbnj"/><path fill="url(#iME9XwR)" class="gd0q7bbnj"/><path fill="url(#iO3gv9H)" class="gd0q7bbnj"/><path fill="url(#iVm8Kqe)" class="gd0q7bbnj"/></g><defs><radialGradient id="idoFQhg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50001 10.00002 -24.1071 -3.61608 14.488 21)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="eebf5ub9j"/><stop offset=".874" class="k90wp6bmc"/></radialGradient><radialGradient id="iUhS8Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68767 6.50126 -6.0031 -.63498 17.668 20.942)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="i6o-qu9fo"/><stop offset="1" class="r5htkxbvz"/></radialGradient><radialGradient id="i0Up8vd" cx="0" cy="0" r="1" gradientTransform="matrix(.53853 7.97018 -6.15248 .41571 17.088 21.648)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="pf1xml9sl"/><stop offset="1" class="rd54rdzck"/></radialGradient><radialGradient id="iTtTvQb" cx="0" cy="0" r="1" gradientTransform="matrix(16.01925 10.36522 -13.13305 20.29688 1.482 16.766)" gradientUnits="userSpaceOnUse"><stop offset=".974" class="v10_5zwzh"/><stop offset="1" class="jn_5q-btc"/></radialGradient><radialGradient id="itXytfb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.822 5.35543 -6.78547 -9.91068 16.821 26.128)" gradientUnits="userSpaceOnUse"><stop class="yk1d-rbcz"/><stop offset="1" class="vy67icc3g"/></radialGradient><radialGradient id="im43Afd" cx="0" cy="0" r="1" gradientTransform="rotate(18.358 -64.362 4.587)scale(20.8924 11.2164)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="i-lj0-gmv"/><stop offset="1" class="vvyrbnhyh"/></radialGradient><radialGradient id="ivNPYhd" cx="0" cy="0" r="1" gradientTransform="matrix(.37564 6.01026 -5.0257 .3141 16.684 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".02" class="gkxiyeb3x"/><stop offset=".645" class="gkxiyeb3x"/><stop offset=".705" class="s4qko67rc"/><stop offset=".947" class="gkxiyeb3x"/></radialGradient><radialGradient id="icMPmQA" cx="0" cy="0" r="1" gradientTransform="rotate(90.939 -.538 17.327)scale(8.59395 7.27784)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="tqnkvib7j"/><stop offset="1" class="bdynesb7r"/></radialGradient><radialGradient id="iznMLJm" cx="0" cy="0" r="1" gradientTransform="matrix(1.4421 -8.96427 5.94373 .95618 22.66 16.384)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="tutb2eb2g"/><stop offset="1" class="g719sobvw"/></radialGradient><radialGradient id="iuJq2nb" cx="0" cy="0" r="1" gradientTransform="matrix(.24459 3.88283 -.58052 .03657 22.92 11.08)" gradientUnits="userSpaceOnUse"><stop class="rjlaqlbzk"/><stop offset="1" class="j6h0vdbbf"/></radialGradient><radialGradient id="ibuVBve" cx="0" cy="0" r="1" gradientTransform="matrix(-.58293 .91192 -1.112 -.71083 24.266 8.274)" gradientUnits="userSpaceOnUse"><stop class="zpyuicbyc"/><stop offset="1" class="d3d7iwl-t"/></radialGradient><radialGradient id="i3Q2jwe" cx="0" cy="0" r="1" gradientTransform="matrix(1.4758 -10.24131 6.11321 .88093 20.254 15.264)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="tutb2eb2g"/><stop offset="1" class="g719sobvw"/></radialGradient><radialGradient id="iTA9WBc" cx="0" cy="0" r="1" gradientTransform="matrix(.2503 4.43595 -.59456 .03355 20.52 9.204)" gradientUnits="userSpaceOnUse"><stop class="rjlaqlbzk"/><stop offset="1" class="j6h0vdbbf"/></radialGradient><radialGradient id="iEn6Der" cx="0" cy="0" r="1" gradientTransform="matrix(-.59656 1.04182 -1.2072 -.69126 21.898 5.998)" gradientUnits="userSpaceOnUse"><stop class="zpyuicbyc"/><stop offset="1" class="d3d7iwl-t"/></radialGradient><radialGradient id="iJC5WUd" cx="0" cy="0" r="1" gradientTransform="matrix(2.39675 -12.2161 9.75814 1.9145 16.2 15.435)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="tutb2eb2g"/><stop offset="1" class="g719sobvw"/></radialGradient><radialGradient id="ishB7He" cx="0" cy="0" r="1" gradientTransform="rotate(64.687 6.109 17.289)scale(1.98059 1.34616)" gradientUnits="userSpaceOnUse"><stop class="zpyuicbyc"/><stop offset="1" class="d3d7iwl-t"/></radialGradient><radialGradient id="i59gWhu" cx="0" cy="0" r="1" gradientTransform="matrix(1.10699 5.81505 -1.41016 .26845 17.927 7.831)" gradientUnits="userSpaceOnUse"><stop class="rjlaqlbzk"/><stop offset="1" class="j6h0vdbbf"/></radialGradient><radialGradient id="iM4dFZC" cx="0" cy="0" r="1" gradientTransform="matrix(-.45637 1.49075 -1.1158 -.34158 16.878 6.151)" gradientUnits="userSpaceOnUse"><stop class="zpyuicbyc"/><stop offset="1" class="d3d7iwl-t"/></radialGradient><radialGradient id="ipbnUyb" cx="0" cy="0" r="1" gradientTransform="rotate(43.773 -8.902 26.867)scale(2.82875 .8004)" gradientUnits="userSpaceOnUse"><stop class="e4j14bghc"/><stop offset="1" class="ddt4h9ktn"/></radialGradient><radialGradient id="ilhjDDb" cx="0" cy="0" r="1" gradientTransform="matrix(.9148 1.42301 -1.56358 1.00516 19.43 13.696)" gradientUnits="userSpaceOnUse"><stop class="wwui2nhqs"/><stop offset="1" class="adewjy2nb"/></radialGradient><radialGradient id="ilnGElb" cx="0" cy="0" r="1" gradientTransform="matrix(-.55105 7.96632 -4.84722 -.3353 12.05 18.744)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="xir7fw_9u"/><stop offset="1" class="kscqpvi1a"/></radialGradient><radialGradient id="ivvQqBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.43559 6.7733 -4.1213 -.26504 12.05 18.745)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="b4dxy-bzl"/><stop offset="1" class="pdm-6hpua"/></radialGradient><radialGradient id="iPRI25L" cx="0" cy="0" r="1" gradientTransform="matrix(-.73121 5.2724 -2.38869 -.33128 12.346 19.322)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="y51fvzb4v"/><stop offset="1" class="m9487nvnu"/></radialGradient><radialGradient id="i8exRHc" cx="0" cy="0" r="1" gradientTransform="matrix(2.9794 2.8765 -.8157 .84488 16.156 13.934)" gradientUnits="userSpaceOnUse"><stop class="jx0i5jflv"/><stop offset="1" class="f4lt50bmo"/></radialGradient><radialGradient id="i18iMrd" cx="0" cy="0" r="1" gradientTransform="rotate(46.273 -7.679 24.04)scale(3.67463 2.23588)" gradientUnits="userSpaceOnUse"><stop class="hc_-6cbqt"/><stop offset="1" class="kfkdnybxj"/></radialGradient><radialGradient id="ijNZNzb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33231 -3.55487 2.163 -3.24452 16.194 23.662)" gradientUnits="userSpaceOnUse"><stop class="f2nye-u1s"/><stop offset="1" class="itbdrrbkq"/></radialGradient><radialGradient id="ipmeibe" cx="0" cy="0" r="1" gradientTransform="matrix(.32838 4.59737 -1.91946 .1371 13.547 21.365)" gradientUnits="userSpaceOnUse"><stop class="b_n_y7-2u"/><stop offset="1" class="mt9y5gb6l"/></radialGradient><radialGradient id="i7HsYId" cx="0" cy="0" r="1" gradientTransform="matrix(2.4826 1.59919 -1.46857 2.27982 13.889 23.916)" gradientUnits="userSpaceOnUse"><stop class="yaxlxtb3d"/><stop offset="1" class="v81t67okt"/></radialGradient><radialGradient id="iME9XwR" cx="0" cy="0" r="1" gradientTransform="rotate(79.606 -6.717 18.7)scale(2.94131 .99204)" gradientUnits="userSpaceOnUse"><stop class="d7mo8bb_w"/><stop offset="1" class="n_98k21lh"/></radialGradient><radialGradient id="iO3gv9H" cx="0" cy="0" r="1" gradientTransform="rotate(96.195 1.446 17.788)scale(4.53816 2.72633)" gradientUnits="userSpaceOnUse"><stop class="lcujjyrav"/><stop offset="1" class="ab2kz83yd"/></radialGradient><radialGradient id="iVm8Kqe" cx="0" cy="0" r="1" gradientTransform="rotate(94.279 1.923 16.928)scale(2.03257 .86339)" gradientUnits="userSpaceOnUse"><stop class="jssar8bjs"/><stop offset="1" class="c9ujuffjz"/></radialGradient><linearGradient id="icIqnUc" x1="8.488" x2="8.999" y1="27" y2="31.063" gradientUnits="userSpaceOnUse"><stop offset=".456" class="wz0ektb2t"/><stop offset=".974" class="ink3gpbzz"/><stop offset="1" class="odhggkl1x"/></linearGradient><linearGradient id="i2ethIe" x1="15.487" x2="12.362" y1="30.047" y2="22.991" gradientUnits="userSpaceOnUse"><stop class="ajic0q7cm"/><stop offset="1" class="m7gdckjal"/></linearGradient><linearGradient id="ivw0O4b" x1="-.562" x2="7.112" y1="27.45" y2="26.309" gradientUnits="userSpaceOnUse"><stop class="v6d9zubux"/><stop offset="1" class="bh-87dbgb"/></linearGradient><linearGradient id="iLsqJDb" x1="6.738" x2="8.55" y1="18.063" y2="30.25" gradientUnits="userSpaceOnUse"><stop offset=".052" class="gmmht-bmp"/><stop offset=".313" class="pe70qdb4r"/><stop offset=".716" class="gmmht-bmp"/></linearGradient><linearGradient id="iUhT64P" x1="8.999" x2="8.999" y1="17.278" y2="31.483" gradientUnits="userSpaceOnUse"><stop offset=".25" class="glhjr8b8a"/><stop offset=".658" class="dfx-3gbqu"/><stop offset="1" class="v3mqk9bny"/></linearGradient><linearGradient id="iI4F36c" x1="7.87" x2="8.713" y1="26.209" y2="30.964" gradientUnits="userSpaceOnUse"><stop offset=".67" class="s-b47gbty"/><stop offset=".804" class="j-f1eub7w"/></linearGradient><linearGradient id="id8JlUb" x1="13.86" x2="15.971" y1="21.022" y2="26.633" gradientUnits="userSpaceOnUse"><stop class="rtcjn_z-o"/><stop offset=".525" class="im8vvxbai"/><stop offset=".844" class="itqr8e2zb"/><stop offset=".932" class="j5yskjbcs"/></linearGradient><linearGradient id="ibLxjOs" x1="21.386" x2="19.223" y1="13.283" y2="25.969" gradientUnits="userSpaceOnUse"><stop offset=".147" class="d6-vlubha"/><stop offset=".381" class="dz9p_acij"/><stop offset=".598" class="xjbkgabnf"/><stop offset="1" class="p4hv68b3e"/></linearGradient><linearGradient id="iJi3lgC" x1="25.544" x2="21.624" y1="11.857" y2="11.857" gradientUnits="userSpaceOnUse"><stop class="s-3t9ccnv"/><stop offset=".109" class="i0ch-nmzk"/><stop offset=".348" class="ownpgmboe"/><stop offset=".616" class="b8838hbwy"/><stop offset=".712" class="lbh256w_i"/><stop offset=".722" class="law7kr1eg"/></linearGradient><linearGradient id="ilJSVSb" x1="24.863" x2="23.66" y1="12.797" y2="15.125" gradientUnits="userSpaceOnUse"><stop offset=".226" class="bk0bbvtbc"/><stop offset=".572" class="b8kwatowj"/></linearGradient><linearGradient id="i0m2Vbf" x1="23.206" x2="19.195" y1="10.091" y2="10.091" gradientUnits="userSpaceOnUse"><stop class="s-3t9ccnv"/><stop offset=".109" class="i0ch-nmzk"/><stop offset=".348" class="ownpgmboe"/><stop offset=".616" class="b8838hbwy"/><stop offset=".712" class="lbh256w_i"/><stop offset=".722" class="law7kr1eg"/></linearGradient><linearGradient id="ilCjv0d" x1="22.509" x2="21.05" y1="11.166" y2="13.695" gradientUnits="userSpaceOnUse"><stop offset=".226" class="bk0bbvtbc"/><stop offset=".572" class="b8kwatowj"/></linearGradient><linearGradient id="ingtW6d" x1="20.994" x2="14.48" y1="8.268" y2="9.265" gradientUnits="userSpaceOnUse"><stop offset=".061" class="k7acx4bkv"/><stop offset=".186" class="os5-c2bmg"/><stop offset=".348" class="qtu4cvboo"/><stop offset=".411" class="cqs25qqpc"/><stop offset=".616" class="b8838hbwy"/><stop offset=".712" class="lbh256w_i"/><stop offset=".722" class="law7kr1eg"/></linearGradient><linearGradient id="iHOUIfQ" x1="19.862" x2="18.418" y1="10.546" y2="13.954" gradientUnits="userSpaceOnUse"><stop offset=".226" class="bk0bbvtbc"/><stop offset=".572" class="b8kwatowj"/></linearGradient><linearGradient id="icwqDJv" x1="18.474" x2="14.505" y1="9.65" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="r3wf-797f"/><stop offset=".24" class="i0ch-nmzk"/><stop offset=".542" class="byz46kb_q"/><stop offset=".776" class="sqvts9xow"/><stop offset="1" class="pkg0scblm"/></linearGradient><linearGradient id="im0xSEb" x1="14.872" x2="19.099" y1="10.194" y2="13.445" gradientUnits="userSpaceOnUse"><stop offset=".789" class="y-4na345v"/><stop offset="1" class="as0qo37mo"/></linearGradient><linearGradient id="ihFu0Rb" x1="13.182" x2="15.462" y1="11.278" y2="20.688" gradientUnits="userSpaceOnUse"><stop class="tu96-3b2b"/><stop offset="1" class="l1w12qbms"/></linearGradient><linearGradient id="iCJF9Yd" x1="19.462" x2="17.58" y1="18.976" y2="19.207" gradientUnits="userSpaceOnUse"><stop class="i-pgwb1iv"/><stop offset="1" class="s_6u1e_ya"/></linearGradient><linearGradient id="iRiu1Lj" x1="13.916" x2="17.857" y1="12.704" y2="23.09" gradientUnits="userSpaceOnUse"><stop offset=".748" class="gik51j62x"/><stop offset=".902" class="e4u0bfbkj"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rightwards-pushing-hand-dark" /></template>
<style>
.a_vuny-qj {
  d: path("M16.996 13.928c.817 1.407 1.592 2.091 1.877 2.257c.088.05 1.863 2.455-1.212 5.876c-1.669 1.469-4.85 3.505-4.279-1.24c.062-.517.56-1.798.658-2.18c.03-.317-.146-.993-.255-1.29c-.234-.764-.681-1.413-1.445-2.94c-.764-1.529.047-3.223 1.684-3.13c1.637.094 1.95.888 2.972 2.647");
}

.ab2kz83yd {
  stop-color: var(--svg-color--5d4341, #5D4341);
  stop-opacity: 0;
}

.adewjy2nb {
  stop-color: var(--svg-color--6a5350, #6A5350);
  stop-opacity: 0;
}

.ajic0q7cm {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
}

.as0qo37mo {
  stop-color: var(--svg-color--614745, #614745);
}

.b_n_y7-2u {
  stop-color: var(--svg-color--4a3639, #4A3639);
}

.b_w6p3g-t {
  fill: var(--svg-color--4d3036, #4D3036);
  d: path("M16.996 13.928c.817 1.407 1.592 2.091 1.877 2.257c.088.05 1.863 2.455-1.212 5.876c-1.669 1.469-4.85 3.505-4.279-1.24c.062-.517.56-1.798.658-2.18c.03-.317-.146-.993-.255-1.29c-.234-.764-.681-1.413-1.445-2.94c-.764-1.529.047-3.223 1.684-3.13c1.637.094 1.95.888 2.972 2.647");
}

.b4dxy-bzl {
  stop-color: var(--svg-color--3f262f, #3F262F);
}

.b8838hbwy {
  stop-color: var(--svg-color--443031, #443031);
}

.b8kwatowj {
  stop-color: var(--svg-color--6d5653, #6D5653);
}

.bdynesb7r {
  stop-color: var(--svg-color--572685, #572685);
  stop-opacity: 0;
}

.bh-87dbgb {
  stop-color: var(--svg-color--465eff, #465EFF);
  stop-opacity: 0;
}

.bk0bbvtbc {
  stop-color: var(--svg-color--6d5653, #6D5653);
  stop-opacity: 0;
}

.byz46kb_q {
  stop-color: var(--svg-color--462e2e, #462E2E);
}

.c9ujuffjz {
  stop-color: var(--svg-color--6c5653, #6C5653);
  stop-opacity: 0;
}

.cqs25qqpc {
  stop-color: var(--svg-color--483334, #483334);
}

.d3d7iwl-t {
  stop-color: var(--svg-color--6b5553, #6B5553);
  stop-opacity: 0;
}

.d6-vlubha {
  stop-color: var(--svg-color--6c5552, #6C5552);
}

.d7mo8bb_w {
  stop-color: var(--svg-color--38232d, #38232D);
}

.ddt4h9ktn {
  stop-color: var(--svg-color--432e2c, #432E2C);
  stop-opacity: 0;
}

.dfx-3gbqu {
  stop-color: var(--svg-color--5736f5, #5736F5);
}

.dz9p_acij {
  stop-color: var(--svg-color--604644, #604644);
}

.e4j14bghc {
  stop-color: var(--svg-color--432e2c, #432E2C);
}

.e4u0bfbkj {
  stop-color: var(--svg-color--4e343f, #4E343F);
}

.eebf5ub9j {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
}

.f2nye-u1s {
  stop-color: var(--svg-color--422837, #422837);
}

.f4lt50bmo {
  stop-color: var(--svg-color--6a5452, #6A5452);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g719sobvw {
  stop-color: var(--svg-color--644d49, #644D49);
}

.gd0q7bbnj {
  d: path("m15.87 12.126l9.637-.25c.026 1.096.063 3.58 0 4.739v.011c-.078 1.442-.12 2.229-1.43 5.06c-1.049 2.273-3.918 3.745-5.222 4.198c-.56.18-2.16.194-4.087-1.185c-1.46-1.044-1.566-2.532-1.409-3.61q.009-.13.024-.268c.034-.329.245-.941.423-1.457c.103-.298.194-.564.234-.724l.005-.022c.029-.197-.104-.953-.286-1.432c-.147-.388-.63-1.31-.853-1.724l.009-.01c-.17-.314-.361-.673-.574-1.099c-.764-1.528.046-3.165 1.684-3.071c.906.052 1.406.318 1.846.844");
}

.gik51j62x {
  stop-color: var(--svg-color--4e343f, #4E343F);
  stop-opacity: 0;
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

.h7odlkbxb {
  d: path("m25.484 11.896l.06 2.666c-1.687-.202-2.602-1.26-2.602-2.743c-.012-.255-.046-.838-.09-1.767c-.035-.742-.143-2.258-.192-2.923c.252-.083.895-.174 1.454.123c1.352.608 1.252 1.987 1.37 4.644");
}

.hc_-6cbqt {
  stop-color: var(--svg-color--695351, #695351);
}

.ht-zrjbae {
  d: path("M18.584 10.228c.216 1.956.585 2.715.743 2.85c-.198 1.232-.184 4.19-.743 4.61c-.966.726-2.705-1.725-3.446-2.076l-.417-3.03c-.203-1.63-.626-5.025-.698-5.575c-.09-.686.135-2.398 1.824-2.455s2.174 1.374 2.264 1.949l.003.02c.09.57.203 1.291.47 3.707");
}

.i-lj0-gmv {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
  stop-opacity: 0;
}

.i-pgwb1iv {
  stop-color: var(--svg-color--5b403f, #5B403F);
}

.i0ch-nmzk {
  stop-color: var(--svg-color--664f4c, #664F4C);
}

.i6o-qu9fo {
  stop-color: var(--svg-color--852dbd, #852DBD);
}

.icp2bwbof {
  d: path("m17.998 26.047l-3.027-8.769c-.059.216-.94.29-1.373.3L0 19.93v11.553l14.752-2.527c2.322-.306 3.126-2.074 3.246-2.91");
}

.im8vvxbai {
  stop-color: var(--svg-color--3d2730, #3D2730);
}

.ink3gpbzz {
  stop-color: var(--svg-color--9d68ff, #9D68FF);
}

.itbdrrbkq {
  stop-color: var(--svg-color--422837, #422837);
  stop-opacity: 0;
}

.itqr8e2zb {
  stop-color: var(--svg-color--3e2437, #3E2437);
}

.j-f1eub7w {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
}

.j5yskjbcs {
  stop-color: var(--svg-color--452d42, #452D42);
}

.j6h0vdbbf {
  stop-color: var(--svg-color--2e1b1b, #2E1B1B);
  stop-opacity: 0;
}

.jn_5q-btc {
  stop-color: var(--svg-color--806dd1, #806DD1);
}

.jssar8bjs {
  stop-color: var(--svg-color--6c5653, #6C5653);
}

.jx0i5jflv {
  stop-color: var(--svg-color--6a5452, #6A5452);
}

.k7acx4bkv {
  stop-color: var(--svg-color--563c39, #563C39);
}

.k90wp6bmc {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
  stop-opacity: 0;
}

.kfkdnybxj {
  stop-color: var(--svg-color--695351, #695351);
  stop-opacity: 0;
}

.kscqpvi1a {
  stop-color: var(--svg-color--432732, #432732);
  stop-opacity: 0;
}

.l1r-6tcnd {
  d: path("M22.905 10.705c.037 1.253.216 2.174.301 2.477c-.965-.182-2.697-.41-2.587-2.714a96 96 0 0 0-.11-2.451c-.036-.629-.136-2.46-.255-3.389c.255-.036.693-.128 1.476.383c.784.51.83 1.339.92 1.977c.091.637.21 2.15.255 3.716");
}

.l1w12qbms {
  stop-color: var(--svg-color--513835, #513835);
  stop-opacity: 0;
}

.law7kr1eg {
  stop-color: var(--svg-color--412e2e, #412E2E);
}

.lbh256w_i {
  stop-color: var(--svg-color--301d1c, #301D1C);
}

.lcujjyrav {
  stop-color: var(--svg-color--5d4341, #5D4341);
}

.m7gdckjal {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
  stop-opacity: 0;
}

.m9487nvnu {
  stop-color: var(--svg-color--544247, #544247);
  stop-opacity: 0;
}

.ma_0w0k7g {
  fill: var(--svg-color--8248dd, #8248DD);
  d: path("m17.998 26.047l-3.027-8.769c-.059.216-.94.29-1.373.3L0 19.93v11.553l14.752-2.527c2.322-.306 3.126-2.074 3.246-2.91");
}

.mt9y5gb6l {
  stop-color: var(--svg-color--4a3639, #4A3639);
  stop-opacity: 0;
}

.mx8nfobnr {
  d: path("M20.617 10.028c.062 1.683.267 1.688.377 1.974c-1.07 1.51-3.642.886-4.793.385v-7.76c.107-.716.707-2.1 2.245-1.895c1.923.255 1.88 2.214 1.958 3.315s.165 2.864.212 3.98");
}

.n_98k21lh {
  stop-color: var(--svg-color--38232d, #38232D);
  stop-opacity: 0;
}

.odhggkl1x {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
  stop-opacity: 0;
}

.ooa-e1dmy {
  fill: var(--svg-color--593e3d, #593E3D);
  d: path("M24.077 21.687c-1.05 2.271-3.919 3.744-5.222 4.197c-.56.18-2.16.194-4.087-1.185c-2.408-1.723-1.135-4.65-1.068-4.96s.31-.93.343-1.113c.034-.184-.1-.954-.284-1.44c-.148-.388-.63-1.31-.854-1.724l2.83-3.332l9.64-.24c.026 1.097.296 3.157.132 4.724v.012c-.079 1.442-.121 2.229-1.43 5.06");
}

.os5-c2bmg {
  stop-color: var(--svg-color--654d4a, #654D4A);
}

.ownpgmboe {
  stop-color: var(--svg-color--654f4d, #654F4D);
}

.p4hv68b3e {
  stop-color: var(--svg-color--493040, #493040);
}

.pdm-6hpua {
  stop-color: var(--svg-color--3f262f, #3F262F);
  stop-opacity: 0;
}

.pe70qdb4r {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0.62;
}

.pf1xml9sl {
  stop-color: var(--svg-color--852aab, #852AAB);
}

.pkg0scblm {
  stop-color: var(--svg-color--54433f, #54433F);
}

.qtu4cvboo {
  stop-color: var(--svg-color--614c4a, #614C4A);
}

.r3wf-797f {
  stop-color: var(--svg-color--5d4440, #5D4440);
}

.r5htkxbvz {
  stop-color: var(--svg-color--852dbd, #852DBD);
  stop-opacity: 0;
}

.rd54rdzck {
  stop-color: var(--svg-color--6f32fb, #6F32FB);
  stop-opacity: 0;
}

.rjlaqlbzk {
  stop-color: var(--svg-color--2e1b1b, #2E1B1B);
}

.rtcjn_z-o {
  stop-color: var(--svg-color--2d1926, #2D1926);
}

.s_6u1e_ya {
  stop-color: var(--svg-color--5b403f, #5B403F);
  stop-opacity: 0;
}

.s-3t9ccnv {
  stop-color: var(--svg-color--715e5b, #715E5B);
}

.s-b47gbty {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
  stop-opacity: 0;
}

.s4qko67rc {
  stop-color: var(--svg-color--7232f9, #7232F9);
}

.sqvts9xow {
  stop-color: var(--svg-color--432c2b, #432C2B);
}

.tqnkvib7j {
  stop-color: var(--svg-color--572685, #572685);
}

.tu96-3b2b {
  stop-color: var(--svg-color--513835, #513835);
}

.tutb2eb2g {
  stop-color: var(--svg-color--644d49, #644D49);
  stop-opacity: 0;
}

.ujer3lbrk {
  d: path("M24.077 21.687c-1.05 2.271-3.919 3.744-5.222 4.197c-.56.18-2.16.194-4.087-1.185c-2.408-1.723-1.135-4.65-1.068-4.96s.31-.93.343-1.113c.034-.184-.1-.954-.284-1.44c-.148-.388-.63-1.31-.854-1.724l2.83-3.332l9.64-.24c.026 1.097.296 3.157.132 4.724v.012c-.079 1.442-.121 2.229-1.43 5.06");
}

.v10_5zwzh {
  stop-color: var(--svg-color--806dd1, #806DD1);
  stop-opacity: 0;
}

.v3mqk9bny {
  stop-color: var(--svg-color--603d8b, #603D8B);
  stop-opacity: 0;
}

.v6d9zubux {
  stop-color: var(--svg-color--465eff, #465EFF);
}

.v81t67okt {
  stop-color: var(--svg-color--3e2733, #3E2733);
  stop-opacity: 0;
}

.vvyrbnhyh {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
}

.vy67icc3g {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
  stop-opacity: 0;
}

.w9b2spbia {
  d: path("M17.537 26.225c.865-.173 1.417-.37 1.584-.447c-2.339-3.984-6.979-11.862-6.829-11.512c.188.437 1.016 2 1.383 2.718c.367.72.36 1.602.36 1.758s-.29.68-.36 1.008c-.07.078-.633.625-.797 1.828c-.131.963-.099 1.622-.066 1.832c.094 1.241.6 1.906 1.021 2.384c.734.834 1.871.87 2.136.828c.138-.022.486-.182 1.568-.397");
}

.wwui2nhqs {
  stop-color: var(--svg-color--6a5350, #6A5350);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.wz0ektb2t {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
}

.xir7fw_9u {
  stop-color: var(--svg-color--432732, #432732);
}

.xjbkgabnf {
  stop-color: var(--svg-color--583d3c, #583D3C);
}

.y-4na345v {
  stop-color: var(--svg-color--654c4a, #654C4A);
  stop-opacity: 0;
}

.y51fvzb4v {
  stop-color: var(--svg-color--544247, #544247);
}

.yaxlxtb3d {
  stop-color: var(--svg-color--3e2733, #3E2733);
}

.yk1d-rbcz {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
}

.zpyuicbyc {
  stop-color: var(--svg-color--6b5553, #6B5553);
}

</style>
