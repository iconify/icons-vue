<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path class="ma_0w0k7g"/><path fill="url(#icIqnUc)" class="icp2bwbof"/><path fill="url(#i2ethIe)" class="icp2bwbof"/><path fill="url(#idoFQhg)" class="icp2bwbof"/><path fill="url(#ivw0O4b)" class="icp2bwbof"/><path fill="url(#iLsqJDb)" class="icp2bwbof"/><path fill="url(#iUhS8Wd)" class="icp2bwbof"/><path fill="url(#i0Up8vd)" class="icp2bwbof"/><path fill="url(#iTtTvQb)" class="icp2bwbof"/><path fill="url(#iUhT64P)" class="icp2bwbof"/><path fill="url(#itXytfb)" class="icp2bwbof"/><path fill="url(#im43Afd)" class="icp2bwbof"/><path fill="url(#iI4F36c)" class="icp2bwbof"/><path fill="url(#ivNPYhd)" class="icp2bwbof"/><path fill="url(#icMPmQA)" class="icp2bwbof"/><path fill="url(#ijM1fpb)" class="w9b2spbia"/><path fill="url(#ihgj9le)" class="e1dbxpbus"/><path fill="url(#iaxaQFb)" class="h7odlkbxb"/><path fill="url(#i444rWc)" class="h7odlkbxb"/><path fill="url(#i9UrRDc)" class="h7odlkbxb"/><path fill="url(#iT34pmc)" class="h7odlkbxb"/><path fill="url(#iPKBETd)" class="h7odlkbxb"/><path fill="url(#izVX3qc)" class="l1r-6tcnd"/><path fill="url(#itfo7cc)" class="l1r-6tcnd"/><path fill="url(#ijwvdvc)" class="l1r-6tcnd"/><path fill="url(#iJivnkc)" class="l1r-6tcnd"/><path fill="url(#iDbkvgd)" class="l1r-6tcnd"/><path fill="url(#iIGfrWb)" class="mx8nfobnr"/><path fill="url(#irDW3gb)" class="mx8nfobnr"/><path fill="url(#iN4ChTc)" class="mx8nfobnr"/><path fill="url(#iLc4uYb)" class="mx8nfobnr"/><path fill="url(#iX2rBMd)" class="mx8nfobnr"/><path fill="url(#is67odd)" class="mx8nfobnr"/><path fill="url(#i1JjPed)" class="mx8nfobnr"/><path fill="url(#isIrywd)" class="ht-zrjbae"/><path fill="url(#ikSmKWb)" class="ht-zrjbae"/><path fill="url(#iPcRTVs)" class="ht-zrjbae"/><path fill="url(#i6jyvUb)" class="ht-zrjbae"/><path class="r1d5fjb1b"/><path fill="url(#i05P0Jp)" class="a_vuny-qj"/><path fill="url(#iIn2qOb)" class="a_vuny-qj"/><path fill="url(#iF1mx8c)" class="a_vuny-qj"/><path fill="url(#i7SxJBw)" class="a_vuny-qj"/><path fill="url(#izejzuc)" class="a_vuny-qj"/><path fill="url(#ikrJ9Wb)" class="a_vuny-qj"/><path fill="url(#iK4uRVd)" class="a_vuny-qj"/><path fill="url(#iwd7k5c)" class="a_vuny-qj"/><path fill="url(#ikxiCzc)" class="a_vuny-qj"/><path fill="url(#igiozPe)" class="a_vuny-qj"/><path fill="url(#i1E1o8c)" class="gd0q7bbnj"/><path fill="url(#i722Ene)" class="gd0q7bbnj"/><path fill="url(#iaRt4td)" class="gd0q7bbnj"/><path fill="url(#i8iLNTd)" class="gd0q7bbnj"/><path fill="url(#iG4sYIe)" class="gd0q7bbnj"/></g><defs><radialGradient id="idoFQhg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50001 10.00002 -24.1071 -3.61608 14.488 21)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="eebf5ub9j"/><stop offset=".874" class="k90wp6bmc"/></radialGradient><radialGradient id="iUhS8Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68767 6.50126 -6.0031 -.63498 17.668 20.942)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="i6o-qu9fo"/><stop offset="1" class="r5htkxbvz"/></radialGradient><radialGradient id="i0Up8vd" cx="0" cy="0" r="1" gradientTransform="matrix(.53853 7.97018 -6.15248 .41571 17.088 21.648)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="pf1xml9sl"/><stop offset="1" class="rd54rdzck"/></radialGradient><radialGradient id="iTtTvQb" cx="0" cy="0" r="1" gradientTransform="matrix(16.01925 10.36522 -13.13305 20.29688 1.482 16.766)" gradientUnits="userSpaceOnUse"><stop offset=".974" class="v10_5zwzh"/><stop offset="1" class="jn_5q-btc"/></radialGradient><radialGradient id="itXytfb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.822 5.35543 -6.78547 -9.91068 16.821 26.128)" gradientUnits="userSpaceOnUse"><stop class="yk1d-rbcz"/><stop offset="1" class="vy67icc3g"/></radialGradient><radialGradient id="im43Afd" cx="0" cy="0" r="1" gradientTransform="rotate(18.358 -64.362 4.587)scale(20.8924 11.2164)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="i-lj0-gmv"/><stop offset="1" class="vvyrbnhyh"/></radialGradient><radialGradient id="ivNPYhd" cx="0" cy="0" r="1" gradientTransform="matrix(.37564 6.01026 -5.0257 .3141 16.684 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".02" class="gkxiyeb3x"/><stop offset=".645" class="gkxiyeb3x"/><stop offset=".705" class="s4qko67rc"/><stop offset=".947" class="gkxiyeb3x"/></radialGradient><radialGradient id="icMPmQA" cx="0" cy="0" r="1" gradientTransform="rotate(90.939 -.538 17.327)scale(8.59395 7.27784)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="tqnkvib7j"/><stop offset="1" class="bdynesb7r"/></radialGradient><radialGradient id="i444rWc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4421 -8.96427 5.94373 .95618 22.66 16.384)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="wbv4idj6m"/><stop offset="1" class="owd2t_ban"/></radialGradient><radialGradient id="i9UrRDc" cx="0" cy="0" r="1" gradientTransform="matrix(.24459 3.88283 -.58052 .03657 22.92 11.08)" gradientUnits="userSpaceOnUse"><stop class="xs5jiwu-i"/><stop offset="1" class="n7-elkbkq"/></radialGradient><radialGradient id="iPKBETd" cx="0" cy="0" r="1" gradientTransform="matrix(.76348 1.52697 -1.10197 .55098 24.364 8.652)" gradientUnits="userSpaceOnUse"><stop class="lg7-j0bme"/><stop offset="1" class="hj5r_l0gb"/></radialGradient><radialGradient id="itfo7cc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4758 -10.24131 6.11321 .88093 20.254 15.264)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="wbv4idj6m"/><stop offset="1" class="owd2t_ban"/></radialGradient><radialGradient id="ijwvdvc" cx="0" cy="0" r="1" gradientTransform="matrix(.2503 4.43595 -.59456 .03355 20.52 9.204)" gradientUnits="userSpaceOnUse"><stop class="xs5jiwu-i"/><stop offset="1" class="n7-elkbkq"/></radialGradient><radialGradient id="iDbkvgd" cx="0" cy="0" r="1" gradientTransform="matrix(.57105 1.99262 -1.34114 .38435 22 6.43)" gradientUnits="userSpaceOnUse"><stop class="lg7-j0bme"/><stop offset="1" class="hj5r_l0gb"/></radialGradient><radialGradient id="irDW3gb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5967 -10.15434 8.11122 -6.0682 24.937 13.843)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="b6nrrw1za"/><stop offset="1" class="yyr9d6bnt"/></radialGradient><radialGradient id="iN4ChTc" cx="0" cy="0" r="1" gradientTransform="rotate(81.254 4.486 14.082)scale(8.03364 1.72108)" gradientUnits="userSpaceOnUse"><stop class="xs5jiwu-i"/><stop offset="1" class="n7-elkbkq"/></radialGradient><radialGradient id="iLc4uYb" cx="0" cy="0" r="1" gradientTransform="matrix(.92737 2.37685 -2.04546 .79807 19.033 4.897)" gradientUnits="userSpaceOnUse"><stop class="lg7-j0bme"/><stop offset="1" class="hj5r_l0gb"/></radialGradient><radialGradient id="iX2rBMd" cx="0" cy="0" r="1" gradientTransform="matrix(.41755 3.81741 -.42098 .04605 18.18 8.537)" gradientUnits="userSpaceOnUse"><stop class="xs5jiwu-i"/><stop offset="1" class="n7-elkbkq"/></radialGradient><radialGradient id="is67odd" cx="0" cy="0" r="1" gradientTransform="matrix(.24398 3.70846 -1.8975 .12483 17.225 6.649)" gradientUnits="userSpaceOnUse"><stop class="xs5jiwu-i"/><stop offset="1" class="n7-elkbkq"/></radialGradient><radialGradient id="ikSmKWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45637 1.49075 -1.1158 -.34158 16.878 6.151)" gradientUnits="userSpaceOnUse"><stop class="xbpiv709r"/><stop offset=".99" class="l82nk1bkn"/></radialGradient><radialGradient id="iPcRTVs" cx="0" cy="0" r="1" gradientTransform="rotate(43.773 -8.902 26.867)scale(2.82875 .8004)" gradientUnits="userSpaceOnUse"><stop class="mgec5nbhb"/><stop offset="1" class="t2blcqbgx"/></radialGradient><radialGradient id="iIn2qOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.55105 7.96632 -4.84722 -.3353 12.05 18.744)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="wowm9pdax"/><stop offset="1" class="dfy4z6b7v"/></radialGradient><radialGradient id="iF1mx8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.43559 6.7733 -4.1213 -.26504 12.05 18.745)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="pp3ea9btx"/><stop offset="1" class="oi1hracww"/></radialGradient><radialGradient id="i7SxJBw" cx="0" cy="0" r="1" gradientTransform="matrix(-.73121 5.2724 -2.38869 -.33128 12.346 19.322)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="jnc3gbcqz"/><stop offset="1" class="s_rox9bwc"/></radialGradient><radialGradient id="izejzuc" cx="0" cy="0" r="1" gradientTransform="matrix(2.32086 3.53837 -1.49833 .98277 15.003 14.688)" gradientUnits="userSpaceOnUse"><stop class="so8t2lbtx"/><stop offset=".886" class="tqrjct9qx"/></radialGradient><radialGradient id="ikrJ9Wb" cx="0" cy="0" r="1" gradientTransform="matrix(2.2706 5.15695 -1.46238 .64389 16.156 13.934)" gradientUnits="userSpaceOnUse"><stop class="mzg47sbfd"/><stop offset="1" class="hkrdnft_o"/></radialGradient><radialGradient id="iK4uRVd" cx="0" cy="0" r="1" gradientTransform="rotate(63.113 -2.413 18.75)scale(3.76462 3.11174)" gradientUnits="userSpaceOnUse"><stop class="yyuqaqb0l"/><stop offset=".85" class="g_3g2umds"/></radialGradient><radialGradient id="ikxiCzc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33231 -3.55487 2.163 -3.24452 16.194 23.662)" gradientUnits="userSpaceOnUse"><stop class="b84y11b_b"/><stop offset="1" class="d1l2_i-gl"/></radialGradient><radialGradient id="igiozPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1484 3.65496 -2.16671 -.6808 13.199 19.633)" gradientUnits="userSpaceOnUse"><stop class="o0e1hkb4h"/><stop offset="1" class="a0zlt70ir"/></radialGradient><radialGradient id="i1E1o8c" cx="0" cy="0" r="1" gradientTransform="matrix(2.4826 1.59919 -1.46857 2.27982 13.889 23.916)" gradientUnits="userSpaceOnUse"><stop class="ztynohymq"/><stop offset="1" class="wx2ozgkpn"/></radialGradient><radialGradient id="i722Ene" cx="0" cy="0" r="1" gradientTransform="matrix(2.27111 1.71814 -1.57781 2.08561 12.783 22.297)" gradientUnits="userSpaceOnUse"><stop class="e9anqybkt"/><stop offset="1" class="o3z-7ywqu"/></radialGradient><radialGradient id="iaRt4td" cx="0" cy="0" r="1" gradientTransform="rotate(96.195 1.446 17.788)scale(4.53816 2.72633)" gradientUnits="userSpaceOnUse"><stop class="g4x2unb_n"/><stop offset="1" class="euin9no7l"/></radialGradient><radialGradient id="i8iLNTd" cx="0" cy="0" r="1" gradientTransform="rotate(94.279 1.923 16.928)scale(2.03257 .86339)" gradientUnits="userSpaceOnUse"><stop class="iqk_b94ku"/><stop offset="1" class="j_li4o9eq"/></radialGradient><radialGradient id="iG4sYIe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46178 6.89405 -6.33095 -2.2607 21.258 19.075)" gradientUnits="userSpaceOnUse"><stop class="da09a-vmu"/><stop offset=".917" class="ciy5vot7u"/></radialGradient><linearGradient id="icIqnUc" x1="8.488" x2="8.999" y1="27" y2="31.063" gradientUnits="userSpaceOnUse"><stop offset=".456" class="wz0ektb2t"/><stop offset=".974" class="ink3gpbzz"/><stop offset="1" class="odhggkl1x"/></linearGradient><linearGradient id="i2ethIe" x1="15.487" x2="12.362" y1="30.047" y2="22.991" gradientUnits="userSpaceOnUse"><stop class="ajic0q7cm"/><stop offset="1" class="m7gdckjal"/></linearGradient><linearGradient id="ivw0O4b" x1="-.562" x2="7.112" y1="27.45" y2="26.309" gradientUnits="userSpaceOnUse"><stop class="v6d9zubux"/><stop offset="1" class="bh-87dbgb"/></linearGradient><linearGradient id="iLsqJDb" x1="6.738" x2="8.55" y1="18.063" y2="30.25" gradientUnits="userSpaceOnUse"><stop offset=".052" class="gmmht-bmp"/><stop offset=".313" class="pe70qdb4r"/><stop offset=".716" class="gmmht-bmp"/></linearGradient><linearGradient id="iUhT64P" x1="8.999" x2="8.999" y1="17.278" y2="31.483" gradientUnits="userSpaceOnUse"><stop offset=".25" class="glhjr8b8a"/><stop offset=".658" class="dfx-3gbqu"/><stop offset="1" class="v3mqk9bny"/></linearGradient><linearGradient id="iI4F36c" x1="7.87" x2="8.713" y1="26.209" y2="30.964" gradientUnits="userSpaceOnUse"><stop offset=".67" class="s-b47gbty"/><stop offset=".804" class="j-f1eub7w"/></linearGradient><linearGradient id="ijM1fpb" x1="13.86" x2="15.971" y1="21.022" y2="26.633" gradientUnits="userSpaceOnUse"><stop class="wt66i1bek"/><stop offset=".525" class="rdx7u5b8m"/><stop offset=".844" class="wu_f8tbio"/><stop offset=".932" class="l_22bbb7r"/></linearGradient><linearGradient id="ihgj9le" x1="23.777" x2="19.224" y1="13.549" y2="25.969" gradientUnits="userSpaceOnUse"><stop offset=".107" class="bwp7pnbqb"/><stop offset=".308" class="ag4c77bht"/><stop offset=".598" class="ufuwm4b_g"/><stop offset="1" class="t3qqvobcu"/></linearGradient><linearGradient id="iaxaQFb" x1="25.544" x2="21.624" y1="11.857" y2="11.857" gradientUnits="userSpaceOnUse"><stop class="u2nbcybsk"/><stop offset=".109" class="qkza4tkjj"/><stop offset=".333" class="w12xup1lx"/><stop offset=".521" class="xsw99j59z"/><stop offset=".661" class="mlcj4hrun"/><stop offset=".712" class="uj7qgjebr"/></linearGradient><linearGradient id="iT34pmc" x1="24.863" x2="23.66" y1="12.797" y2="15.125" gradientUnits="userSpaceOnUse"><stop offset=".226" class="gib-zub8b"/><stop offset=".572" class="bwp7pnbqb"/></linearGradient><linearGradient id="izVX3qc" x1="23.206" x2="19.195" y1="10.091" y2="10.091" gradientUnits="userSpaceOnUse"><stop class="u2nbcybsk"/><stop offset=".109" class="qkza4tkjj"/><stop offset=".333" class="w12xup1lx"/><stop offset=".521" class="xsw99j59z"/><stop offset=".661" class="mlcj4hrun"/><stop offset=".712" class="uj7qgjebr"/></linearGradient><linearGradient id="iJivnkc" x1="22.509" x2="21.05" y1="11.166" y2="13.695" gradientUnits="userSpaceOnUse"><stop offset=".226" class="gib-zub8b"/><stop offset=".572" class="bwp7pnbqb"/></linearGradient><linearGradient id="iIGfrWb" x1="20.994" x2="14.48" y1="9.265" y2="9.265" gradientUnits="userSpaceOnUse"><stop class="u2nbcybsk"/><stop offset=".109" class="qkza4tkjj"/><stop offset=".333" class="w12xup1lx"/><stop offset=".521" class="xsw99j59z"/><stop offset=".661" class="mlcj4hrun"/><stop offset=".712" class="uj7qgjebr"/></linearGradient><linearGradient id="i1JjPed" x1="19.862" x2="18.418" y1="10.546" y2="13.954" gradientUnits="userSpaceOnUse"><stop offset=".226" class="gib-zub8b"/><stop offset=".572" class="bwp7pnbqb"/></linearGradient><linearGradient id="isIrywd" x1="18.474" x2="14.505" y1="9.65" y2="10.25" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset=".24" class="kvk8wz14r"/><stop offset=".542" class="zgwb37bzk"/><stop offset=".844" class="podrrsixv"/><stop offset="1" class="tmldqtcnj"/></linearGradient><linearGradient id="i6jyvUb" x1="14.872" x2="19.099" y1="10.194" y2="13.445" gradientUnits="userSpaceOnUse"><stop offset=".789" class="yuaawcc-e"/><stop offset="1" class="wayqrfbdo"/></linearGradient><linearGradient id="i05P0Jp" x1="13.182" x2="15.462" y1="11.278" y2="20.688" gradientUnits="userSpaceOnUse"><stop class="t4k5f4brr"/><stop offset="1" class="xx_upbcgv"/></linearGradient><linearGradient id="iwd7k5c" x1="19.462" x2="17.58" y1="18.976" y2="19.207" gradientUnits="userSpaceOnUse"><stop class="qazoa-bcq"/><stop offset="1" class="qy9m03_md"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rightwards-pushing-hand-light" /></template>
<style>
.a_vuny-qj {
  d: path("M16.996 13.928c.817 1.407 1.592 2.091 1.877 2.257c.088.05 1.863 2.455-1.212 5.876c-1.669 1.469-4.85 3.505-4.279-1.24c.062-.517.56-1.798.658-2.18c.03-.317-.146-.993-.255-1.29c-.234-.764-.681-1.413-1.445-2.94c-.764-1.529.047-3.223 1.684-3.13c1.637.094 1.95.888 2.972 2.647");
}

.a0zlt70ir {
  stop-color: var(--svg-color--d49e90, #D49E90);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ajic0q7cm {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
}

.b6nrrw1za {
  stop-color: var(--svg-color--dfaa8d, #DFAA8D);
  stop-opacity: 0;
}

.b84y11b_b {
  stop-color: var(--svg-color--c68d9b, #C68D9B);
}

.bdynesb7r {
  stop-color: var(--svg-color--572685, #572685);
  stop-opacity: 0;
}

.bh-87dbgb {
  stop-color: var(--svg-color--465eff, #465EFF);
  stop-opacity: 0;
}

.bwp7pnbqb {
  stop-color: var(--svg-color--ffe6c9, #FFE6C9);
}

.ciy5vot7u {
  stop-color: var(--svg-color--ffddc2, #FFDDC2);
  stop-opacity: 0;
}

.d1l2_i-gl {
  stop-color: var(--svg-color--c68d9b, #C68D9B);
  stop-opacity: 0;
}

.da09a-vmu {
  stop-color: var(--svg-color--ffddc2, #FFDDC2);
}

.dfx-3gbqu {
  stop-color: var(--svg-color--5736f5, #5736F5);
}

.dfy4z6b7v {
  stop-color: var(--svg-color--d49c9b, #D49C9B);
  stop-opacity: 0;
}

.e1dbxpbus {
  d: path("M24.078 21.687c-1.05 2.271-3.92 3.744-5.223 4.196c-.56.18-2.16.195-4.087-1.184c-2.408-1.723-1.134-4.65-1.067-4.96s.31-.93.343-1.113c.034-.184-.1-.954-.285-1.44c-.147-.388-.63-1.311-.853-1.724l2.829-3.332l9.772-.255c.026 1.097.063 3.58 0 4.74v.011c-.078 1.442-.12 2.229-1.43 5.06");
}

.e9anqybkt {
  stop-color: var(--svg-color--af7d79, #AF7D79);
}

.eebf5ub9j {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
}

.euin9no7l {
  stop-color: var(--svg-color--ffdbc1, #FFDBC1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g_3g2umds {
  stop-color: var(--svg-color--ffe1c7, #FFE1C7);
  stop-opacity: 0;
}

.g4x2unb_n {
  stop-color: var(--svg-color--ffdbc1, #FFDBC1);
}

.gd0q7bbnj {
  d: path("m15.87 12.126l9.637-.25c.026 1.096.063 3.58 0 4.739v.011c-.078 1.442-.12 2.229-1.43 5.06c-1.049 2.273-3.918 3.745-5.222 4.198c-.56.18-2.16.194-4.087-1.185c-1.46-1.044-1.566-2.532-1.409-3.61q.009-.13.024-.268c.034-.329.245-.941.423-1.457c.103-.298.194-.564.234-.724l.005-.022c.029-.197-.104-.953-.286-1.432c-.147-.388-.63-1.31-.853-1.724l.009-.01c-.17-.314-.361-.673-.574-1.099c-.764-1.528.046-3.165 1.684-3.071c.906.052 1.406.318 1.846.844");
}

.gib-zub8b {
  stop-color: var(--svg-color--ffe6c9, #FFE6C9);
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

.hj5r_l0gb {
  stop-color: var(--svg-color--ffe2c7, #FFE2C7);
  stop-opacity: 0;
}

.hkrdnft_o {
  stop-color: var(--svg-color--e9b8a7, #E9B8A7);
  stop-opacity: 0;
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

.ink3gpbzz {
  stop-color: var(--svg-color--9d68ff, #9D68FF);
}

.iqk_b94ku {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
}

.j_li4o9eq {
  stop-color: var(--svg-color--ffe4c9, #FFE4C9);
  stop-opacity: 0;
}

.j-f1eub7w {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
}

.jn_5q-btc {
  stop-color: var(--svg-color--806dd1, #806DD1);
}

.jnc3gbcqz {
  stop-color: var(--svg-color--c78d8a, #C78D8A);
}

.k90wp6bmc {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
  stop-opacity: 0;
}

.kvk8wz14r {
  stop-color: var(--svg-color--ffdcc3, #FFDCC3);
}

.l_22bbb7r {
  stop-color: var(--svg-color--b27793, #B27793);
}

.l1r-6tcnd {
  d: path("M22.905 10.705c.037 1.253.216 2.174.301 2.477c-.965-.182-2.697-.41-2.587-2.714a96 96 0 0 0-.11-2.451c-.036-.629-.136-2.46-.255-3.389c.255-.036.693-.128 1.476.383c.784.51.83 1.339.92 1.977c.091.637.21 2.15.255 3.716");
}

.l82nk1bkn {
  stop-color: var(--svg-color--ffe0c6, #FFE0C6);
  stop-opacity: 0;
}

.lg7-j0bme {
  stop-color: var(--svg-color--ffe2c7, #FFE2C7);
}

.m7gdckjal {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
  stop-opacity: 0;
}

.ma_0w0k7g {
  fill: var(--svg-color--8248dd, #8248DD);
  d: path("m17.998 26.047l-3.027-8.769c-.059.216-.94.29-1.373.3L0 19.93v11.553l14.752-2.527c2.322-.306 3.126-2.074 3.246-2.91");
}

.mgec5nbhb {
  stop-color: var(--svg-color--f1af92, #F1AF92);
}

.mlcj4hrun {
  stop-color: var(--svg-color--f5af98, #F5AF98);
}

.mx8nfobnr {
  d: path("M20.617 10.028c.062 1.683.267 1.688.377 1.974c-1.07 1.51-3.642.886-4.793.385v-7.76c.107-.716.707-2.1 2.245-1.895c1.923.255 1.88 2.214 1.958 3.315s.165 2.864.212 3.98");
}

.mzg47sbfd {
  stop-color: var(--svg-color--ffe0c7, #FFE0C7);
}

.n7-elkbkq {
  stop-color: var(--svg-color--e9957d, #E9957D);
  stop-opacity: 0;
}

.o0e1hkb4h {
  stop-color: var(--svg-color--d49e90, #D49E90);
}

.o3z-7ywqu {
  stop-color: var(--svg-color--af7d79, #AF7D79);
  stop-opacity: 0;
}

.odhggkl1x {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
  stop-opacity: 0;
}

.oi1hracww {
  stop-color: var(--svg-color--c78c8b, #C78C8B);
  stop-opacity: 0;
}

.owd2t_ban {
  stop-color: var(--svg-color--edb395, #EDB395);
}

.pe70qdb4r {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0.62;
}

.pf1xml9sl {
  stop-color: var(--svg-color--852aab, #852AAB);
}

.podrrsixv {
  stop-color: var(--svg-color--d6a086, #D6A086);
}

.pp3ea9btx {
  stop-color: var(--svg-color--c78c8b, #C78C8B);
}

.qazoa-bcq {
  stop-color: var(--svg-color--ffd8c0, #FFD8C0);
}

.qkza4tkjj {
  stop-color: var(--svg-color--ffdcc2, #FFDCC2);
}

.qy9m03_md {
  stop-color: var(--svg-color--ffd8c0, #FFD8C0);
  stop-opacity: 0;
}

.r1d5fjb1b {
  fill: var(--svg-color--f7c3b4, #F7C3B4);
  d: path("M16.996 13.928c.817 1.407 1.592 2.091 1.877 2.257c.088.05 1.863 2.455-1.212 5.876c-1.669 1.469-4.85 3.505-4.279-1.24c.062-.517.56-1.798.658-2.18c.03-.317-.146-.993-.255-1.29c-.234-.764-.681-1.413-1.445-2.94c-.764-1.529.047-3.223 1.684-3.13c1.637.094 1.95.888 2.972 2.647");
}

.r5htkxbvz {
  stop-color: var(--svg-color--852dbd, #852DBD);
  stop-opacity: 0;
}

.rd54rdzck {
  stop-color: var(--svg-color--6f32fb, #6F32FB);
  stop-opacity: 0;
}

.rdx7u5b8m {
  stop-color: var(--svg-color--b58283, #B58283);
}

.s_rox9bwc {
  stop-color: var(--svg-color--c78d8a, #C78D8A);
  stop-opacity: 0;
}

.s-b47gbty {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
  stop-opacity: 0;
}

.s4qko67rc {
  stop-color: var(--svg-color--7232f9, #7232F9);
}

.so8t2lbtx {
  stop-color: var(--svg-color--ebb6ab, #EBB6AB);
}

.t2blcqbgx {
  stop-color: var(--svg-color--f1af92, #F1AF92);
  stop-opacity: 0;
}

.t3qqvobcu {
  stop-color: var(--svg-color--ba7f94, #BA7F94);
}

.t4k5f4brr {
  stop-color: var(--svg-color--d8aa92, #D8AA92);
}

.tmldqtcnj {
  stop-color: var(--svg-color--dba58d, #DBA58D);
}

.tqnkvib7j {
  stop-color: var(--svg-color--572685, #572685);
}

.tqrjct9qx {
  stop-color: var(--svg-color--ebb6ab, #EBB6AB);
  stop-opacity: 0;
}

.u2nbcybsk {
  stop-color: var(--svg-color--ffd5bb, #FFD5BB);
}

.ufuwm4b_g {
  stop-color: var(--svg-color--ffceb9, #FFCEB9);
}

.uj7qgjebr {
  stop-color: var(--svg-color--ea9781, #EA9781);
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

.vvyrbnhyh {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
}

.vy67icc3g {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
  stop-opacity: 0;
}

.w12xup1lx {
  stop-color: var(--svg-color--ffd9bf, #FFD9BF);
}

.w9b2spbia {
  d: path("M17.537 26.225c.865-.173 1.417-.37 1.584-.447c-2.339-3.984-6.979-11.862-6.829-11.512c.188.437 1.016 2 1.383 2.718c.367.72.36 1.602.36 1.758s-.29.68-.36 1.008c-.07.078-.633.625-.797 1.828c-.131.963-.099 1.622-.066 1.832c.094 1.241.6 1.906 1.021 2.384c.734.834 1.871.87 2.136.828c.138-.022.486-.182 1.568-.397");
}

.wayqrfbdo {
  stop-color: var(--svg-color--ffe2c6, #FFE2C6);
}

.wbv4idj6m {
  stop-color: var(--svg-color--edb395, #EDB395);
  stop-opacity: 0;
}

.wowm9pdax {
  stop-color: var(--svg-color--d49c9b, #D49C9B);
}

.wt66i1bek {
  stop-color: var(--svg-color--a8786f, #A8786F);
}

.wu_f8tbio {
  stop-color: var(--svg-color--b87e92, #B87E92);
}

.wx2ozgkpn {
  stop-color: var(--svg-color--b68286, #B68286);
  stop-opacity: 0;
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.wz0ektb2t {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
}

.xbpiv709r {
  stop-color: var(--svg-color--ffe0c6, #FFE0C6);
}

.xs5jiwu-i {
  stop-color: var(--svg-color--e9957d, #E9957D);
}

.xsw99j59z {
  stop-color: var(--svg-color--ffcbb3, #FFCBB3);
}

.xx_upbcgv {
  stop-color: var(--svg-color--d8aa92, #D8AA92);
  stop-opacity: 0;
}

.yk1d-rbcz {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
}

.yuaawcc-e {
  stop-color: var(--svg-color--ffe2c6, #FFE2C6);
  stop-opacity: 0;
}

.yyr9d6bnt {
  stop-color: var(--svg-color--dfaa8d, #DFAA8D);
}

.yyuqaqb0l {
  stop-color: var(--svg-color--ffe1c7, #FFE1C7);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.zgwb37bzk {
  stop-color: var(--svg-color--f4c1aa, #F4C1AA);
}

.ztynohymq {
  stop-color: var(--svg-color--b68286, #B68286);
}

</style>
