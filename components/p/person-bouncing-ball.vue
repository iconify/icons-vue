<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ihODcwd)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#isvbJGc)"><path class="omy7ubc2p"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#inCRP5c)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#ii6XIKb)" class="b1yazzwzl"/><path fill="url(#iMTFQmc)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#iWWCphd)"><path fill="url(#iiLGrnb)" class="cyh5i_zar"/><path fill="url(#irBCE5b)" class="cyh5i_zar"/><path fill="url(#iOuH9yc)" class="cyh5i_zar"/></g><g filter="url(#inF1s3b)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#i0DZJgb)" class="qexsyge6i"/><path fill="url(#i1ufe0d)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#ixMLWzc)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#iQK29Ac)"><path fill="url(#iTF2f9h)" class="yxagr-bug"/><path fill="url(#iDFUiOc)" class="yxagr-bug"/></g><g filter="url(#iFguyRb)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#inTpqRb)"><path fill="url(#iABhcFd)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="swibnbi7z"/><path fill="url(#i21nLld)" class="eikeckbha"/><path fill="url(#iGhsDnd)" class="eikeckbha"/><g filter="url(#iltBLbc)"><path class="j9f4fjdso"/><path fill="url(#iEvaKRd)" class="hpxf53bap"/></g><path fill="url(#i8Vm0td)" clip-rule="evenodd" class="x99s9tbej"/><path fill="url(#iyHZdvb)" clip-rule="evenodd" class="x99s9tbej"/><path fill="url(#iaP1CED)" clip-rule="evenodd" class="y8eztfbsi"/><path fill="url(#iTaT2wK)" clip-rule="evenodd" class="y8eztfbsi"/><path fill="url(#ixVzGgd)" clip-rule="evenodd" class="t7cma5ywk"/><path fill="url(#i5Auype)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="ggznuxqhy"/><path fill="url(#iJJbgjd)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#in30yCe)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#iQSOCKe)"><path fill="url(#i40rhfb)" class="p3ru7q3ze"/><path fill="url(#iBXH0lc)" class="p3ru7q3ze"/></g><path fill="url(#iPJ2hNc)" class="p3ru7q3ze"/><path fill="url(#iLeYWpc)" class="s0k1mrqwn"/><path fill="url(#iJ1SiFd)" class="s0k1mrqwn"/><path fill="url(#iQH8PSt)" class="fmpd-_xyj"/><path fill="url(#iVn50be)" class="fmpd-_xyj"/><g filter="url(#iJVsnAb)"><path fill="url(#iMTxgrd)" class="ppogkm8sl"/></g><path fill="url(#inocHLc)" class="ppogkm8sl"/><path fill="url(#iA1Tgcv)" class="ppogkm8sl"/><path fill="url(#i2IhV5b)" class="ppogkm8sl"/><path fill="url(#ir3S9NI)" class="ppogkm8sl"/><g filter="url(#i2dCDbe)"><path class="e1qeljbtf"/></g><g filter="url(#ikiJRxb)"><path fill="url(#i756ZFb)" class="na810ccvo"/><path fill="url(#ixyuhPd)" class="na810ccvo"/><path fill="url(#ieAGrWd)" class="na810ccvo"/><path fill="url(#imJdhUc)" class="na810ccvo"/></g><g filter="url(#iqAu1nb)"><path stroke="url(#iykhVoe)" class="ux5bl2hml"/></g><path fill="url(#itoOpTK)" class="dekrocbav"/><g filter="url(#iCkZZ2b)"><path fill="url(#iHkdVRd)" class="podjqxb2m"/><path fill="url(#iQbN0Me)" class="podjqxb2m"/><path fill="url(#iKsPvmc)" class="podjqxb2m"/><path fill="url(#iCTyKqe)" class="podjqxb2m"/><path fill="url(#iICgCDc)" class="podjqxb2m"/></g><g filter="url(#iAedKMd)"><path class="i600yacue"/></g><g filter="url(#iLY9qhe)"><path class="cmybhebxd"/></g><g filter="url(#iDIoSpd)"><path fill="url(#ilea7IO)" class="k_t2a2ulc"/><path fill="url(#ivVr07c)" class="k_t2a2ulc"/></g><g filter="url(#i6N5pmc)"><path fill="url(#i47thfd)" class="xk-67ebxg"/><path fill="url(#i4hoNlc)" class="xk-67ebxg"/><path fill="url(#iv7MYCc)" class="xk-67ebxg"/><path fill="url(#iOgK3cc)" class="xk-67ebxg"/><path fill="url(#iy7hjDe)" class="xk-67ebxg"/></g><path class="jjrlpyxfw"/><path fill="url(#ijbDZ1c)" class="z7vzzek9g"/><path class="jwgdn5bsq"/><g filter="url(#iXwLllh)"><path class="q2_7isbvq"/><path fill="url(#iZOsNFe)" class="n1hgt6xzx"/></g><g filter="url(#ioNFqsb)"><path fill="url(#iTuJzld)" class="proqfw3jj"/></g><path class="fl5qg3bua"/><path fill="url(#iolLuwe)" class="s19ln7btb"/><path class="yf7i1xbax"/><g filter="url(#ikcOMRb)"><path fill="url(#i5rMBKe)" class="oltlfmbmq"/></g><g filter="url(#iAlCQCc)"><ellipse transform="rotate(-27.914 11.735 5.655)" class="lck3-wbne"/><ellipse fill="url(#iOqyDEd)" transform="rotate(-27.914 11.735 5.655)" class="fxi7ulo5m"/></g><path fill="url(#igUNDwb)" class="udg1p6bpm"/><path fill="url(#ijEJeHd)" class="udg1p6bpm"/><path fill="url(#iX8b5Bd)" class="udg1p6bpm"/><path fill="url(#iCJ4JnG)" class="t1on3zqxv"/><path fill="url(#iT3c9Mc)" class="t1on3zqxv"/><g filter="url(#im0sm4O)"><path class="ijz9mfb4k"/></g><g filter="url(#iql4BCc)"><path class="ozv8tqbah"/></g><path fill="url(#ivCn2Hc)" class="jb48c2b-f"/><path fill="url(#ih1rWNe)" class="jb48c2b-f"/><path fill="url(#iXUnPse)" class="jb48c2b-f"/><path fill="url(#iHOcF4b)" class="jb48c2b-f"/><path fill="url(#i2b22fd)" clip-rule="evenodd" class="y_4pajl7d"/><path fill="url(#i44eZYb)" clip-rule="evenodd" class="y_4pajl7d"/><defs><radialGradient id="ihODcwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="e5q41c8fy"/><stop offset="1" class="ld99d_7hf"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="ii6XIKb" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="hxm-6izwk"/><stop offset="1" class="j-x6w7b4y"/></radialGradient><radialGradient id="iMTFQmc" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="u-m77k52c"/><stop offset=".977" class="nhbmuhbvb"/></radialGradient><radialGradient id="iiLGrnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="gr7jnieaq"/><stop offset="1" class="fni059bsf"/></radialGradient><radialGradient id="irBCE5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="r24pfmh2j"/><stop offset="1" class="jat2c8bpf"/></radialGradient><radialGradient id="iOuH9yc" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="yzedoqb0u"/><stop offset="1" class="f4147fa0n"/></radialGradient><radialGradient id="i0DZJgb" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="a30nnuz6x"/><stop offset="1" class="sg7xbrbid"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iTF2f9h" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="l277r0b8m"/><stop offset="1" class="m1km_jo3a"/></radialGradient><radialGradient id="iABhcFd" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="fthz0iw6h"/><stop offset="1" class="doutuqf7h"/></radialGradient><radialGradient id="i21nLld" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="amshv2yws"/><stop offset="1" class="fszi1o-7g"/></radialGradient><radialGradient id="iGhsDnd" cx="0" cy="0" r="1" gradientTransform="rotate(165.718 7.598 5.547)scale(.44339 2.09581)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="qe2iy6u-s"/><stop offset="1" class="b8n9t1b9i"/></radialGradient><radialGradient id="iEvaKRd" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="xjp952bfc"/><stop offset="1" class="qqpuob36k"/></radialGradient><radialGradient id="iyHZdvb" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="lcjnzacgs"/><stop offset="1" class="f8fpdnbnw"/></radialGradient><radialGradient id="iTaT2wK" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="lcjnzacgs"/><stop offset="1" class="f8fpdnbnw"/></radialGradient><radialGradient id="i5Auype" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="lcjnzacgs"/><stop offset="1" class="f8fpdnbnw"/></radialGradient><radialGradient id="iJJbgjd" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="lcjnzacgs"/><stop offset="1" class="f8fpdnbnw"/></radialGradient><radialGradient id="in30yCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3125 1.36718 -.72758 -.69848 7 14.33)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="zxijwrkla"/><stop offset="1" class="xt8_tkusr"/></radialGradient><radialGradient id="i40rhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.479)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="j--7hbfuf"/><stop offset=".81" class="zozrgybxd"/></radialGradient><radialGradient id="iBXH0lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8437 -6.87502 1.8572 -.49805 18.024 16.393)" gradientUnits="userSpaceOnUse"><stop class="wsjf7pm3j"/><stop offset="1" class="u1162e6xa"/></radialGradient><radialGradient id="iPJ2hNc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.271 8.996)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="x0hdn9b5y"/><stop offset="1" class="eziwjdbdq"/></radialGradient><radialGradient id="iLeYWpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39457 1.68636 -2.00326 -.46872 15.354 6.539)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iJ1SiFd" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 .959 18.098)scale(.22519 .1913)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iQH8PSt" cx="0" cy="0" r="1" gradientTransform="matrix(.60297 1.77463 -.80665 .27408 10.335 6.592)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iVn50be" cx="0" cy="0" r="1" gradientTransform="matrix(.14405 .4511 -.3957 .12636 10.635 6.588)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iMTxgrd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36463 0 0 -4.18301 14.115 6.113)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="inocHLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53146 5.95753 0 12.757 8.979)" gradientUnits="userSpaceOnUse"><stop class="ujgovaclr"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="iA1Tgcv" cx="0" cy="0" r="1" gradientTransform="matrix(-.18208 2.75999 -1.01468 -.06694 15.177 6.008)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="i2IhV5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6395 .76994 0 11.899 5.58)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="ir3S9NI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.69441 .90067 0 13.97 5.393)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iykhVoe" cx="0" cy="0" r="1" gradientTransform="matrix(.15703 -.28018 .81535 .45695 12.335 7.6)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="itoOpTK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.326 1.31158 0 12.845 7.714)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iQbN0Me" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.58677 4.58325 0 10.48 5.398)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iKsPvmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6431 2.91125 0 15.043 5.398)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iCTyKqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85744 -.6517 .34708 -.9892 14.702 2.559)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iICgCDc" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 4.575 12.03)scale(.78276 1.81249)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="ilea7IO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72192 .62129 -.17292 -.47925 12.96 2.49)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="ivVr07c" cx="0" cy="0" r="1" gradientTransform="matrix(1.45564 -2.30473 2.5534 1.6127 10.388 4.644)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="i47thfd" cx="0" cy="0" r="1" gradientTransform="matrix(1.53144 .36222 -.20258 .85649 14.483 3.016)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="i4hoNlc" cx="0" cy="0" r="1" gradientTransform="matrix(-.97184 -1.67523 .93427 -.542 15.165 5.098)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iv7MYCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59134 -.99613 .71348 -.42355 14.884 4.964)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="iOgK3cc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1704 .5207 -.5629 -2.34628 15.013 2.963)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iy7hjDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.05307 .17357 -.79352 -.24263 14.406 2.906)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="ijbDZ1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36697 -.5837 0 13.832 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iZOsNFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10502 -.13533 .18632 -.14459 13.729 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iolLuwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36699 -.58374 0 11.858 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iOqyDEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22374 .26894 -.00421 11.729 5.798)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijEJeHd" cx="0" cy="0" r="1" gradientTransform="matrix(.2843 1.01466 -.96807 .27125 14.933 5.705)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iX8b5Bd" cx="0" cy="0" r="1" gradientTransform="matrix(.35633 -.489 .40988 .29867 15.096 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iT3c9Mc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 2.86 7.184)scale(.95741 .94121)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="ivCn2Hc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.4 3.862)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="iHOcF4b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.227 3.33)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><radialGradient id="i2b22fd" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gifgm4i1v"/><stop offset="1" class="jyrqxvbae"/></radialGradient><radialGradient id="i44eZYb" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.42188 .2738 .40562 6.907 14.22)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="wgpnrcbke"/><stop offset="1" class="knaev-n-x"/></radialGradient><filter id="isvbJGc" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.498039 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="inCRP5c" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="iWWCphd" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.32549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="inF1s3b" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="ixMLWzc" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="iQK29Ac" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.231373 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="iFguyRb" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="inTpqRb" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.423529 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23220" result="effect2_innerShadow_3987_23220"/></filter><filter id="iltBLbc" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="iQSOCKe" width="7.636" height="9.986" x="11.582" y="7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.215686 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="iJVsnAb" width="5.123" height="5.782" x="10.555" y="3.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23220" result="effect2_innerShadow_3987_23220"/></filter><filter id="i2dCDbe" width="2.849" height="3.312" x="11.326" y="4.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".5"/></filter><filter id="ikiJRxb" width="1.049" height="1.512" x="12.32" y="5.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".05"/></filter><filter id="iqAu1nb" width="1.956" height=".985" x="11.867" y="7.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".05"/></filter><filter id="iCkZZ2b" width="5.822" height="4.054" x="9.933" y="1.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23220" result="effect2_innerShadow_3987_23220"/></filter><filter id="iAedKMd" width="1.113" height=".648" x="13.564" y="4.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="iLY9qhe" width="1.113" height=".641" x="11.186" y="4.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23220"/></filter><filter id="iDIoSpd" width="3.052" height="2.765" x="10.057" y="2.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".075"/></filter><filter id="i6N5pmc" width="2.877" height="2.63" x="12.81" y="2.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".075"/></filter><filter id="iXwLllh" width=".466" height=".425" x="13.445" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".05"/></filter><filter id="ioNFqsb" width=".622" height=".632" x="13.77" y="5.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".1"/></filter><filter id="ikcOMRb" width=".665" height=".689" x="11.761" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".1"/></filter><filter id="iAlCQCc" width=".523" height=".428" x="11.474" y="5.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".05"/></filter><filter id="im0sm4O" width=".875" height="1.35" x="9.979" y="5.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".125"/></filter><filter id="iql4BCc" width=".928" height="1.361" x="14.839" y="5.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23220" stdDeviation=".125"/></filter><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="i1ufe0d" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="rahvf0pdu"/><stop offset="1" class="z2lhmbb7y"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iDFUiOc" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="g7p406nqv"/><stop offset="1" class="r52adsb8o"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="i8Vm0td" x1="6.061" x2="4.746" y1="13.15" y2="14.646" gradientUnits="userSpaceOnUse"><stop class="g74-q2bdc"/><stop offset="1" class="oimmmv6rh"/></linearGradient><linearGradient id="iaP1CED" x1="5.959" x2="4.202" y1="13.445" y2="15.118" gradientUnits="userSpaceOnUse"><stop class="g74-q2bdc"/><stop offset="1" class="oimmmv6rh"/></linearGradient><linearGradient id="ixVzGgd" x1="5.821" x2="3.962" y1="13.924" y2="15.565" gradientUnits="userSpaceOnUse"><stop class="g74-q2bdc"/><stop offset="1" class="oimmmv6rh"/></linearGradient><linearGradient id="i756ZFb" x1="12.845" x2="13.231" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="ixyuhPd" x1="12.359" x2="12.845" y1="6.418" y2="6.444" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="ieAGrWd" x1="12.845" x2="12.845" y1="6.668" y2="7.054" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="imJdhUc" x1="12.845" x2="12.845" y1="5.652" y2="5.841" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iHkdVRd" x1="15.271" x2="10.692" y1="3.552" y2="3.552" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iTuJzld" x1="14.183" x2="14.042" y1="5.723" y2="5.81" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5rMBKe" x1="12.194" x2="12.052" y1="5.723" y2="5.81" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igUNDwb" x1="15.756" x2="15.21" y1="5.735" y2="6.72" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iCJ4JnG" x1="10.199" x2="10.858" y1="6.054" y2="5.996" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="ih1rWNe" x1="9.782" x2="13.493" y1="4.049" y2="4.049" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iXUnPse" x1="13.556" x2="13.556" y1="4.393" y2="4.276" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bouncing-ball" /></template>
<style>
.a30nnuz6x {
  stop-color: var(--svg-color--ffc327, #FFC327);
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.amshv2yws {
  stop-color: var(--svg-color--da800e, #DA800E);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.b1yazzwzl {
  d: path("m11 20.604l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.646 1.008-1.82");
}

.b1ysgbbus {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.469px;
  rx: 0.33px;
}

.b8n9t1b9i {
  stop-color: var(--svg-color--fed031, #FED031);
  stop-opacity: 0;
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmybhebxd {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M11.302 4.716a1.25 1.25 0 0 1 .787-.163a.125.125 0 1 1-.031.25a1 1 0 0 0-.661.15l-.008.005l-.001.001a.126.126 0 0 1-.154-.198z");
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.cyh5i_zar {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.059c.12-.108.433-.271.71-.059c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.198l-4.34-2.419a.3.3 0 0 1-.105-.424l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.dekrocbav {
  d: path("M12.845 7.423a1.36 1.36 0 0 1-.627-.148c-.062-.032-.128.038-.09.094c.152.23.416.383.717.383c.3 0 .565-.153.716-.383c.04-.058-.027-.126-.09-.094a1.35 1.35 0 0 1-.626.148");
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.doutuqf7h {
  stop-color: var(--svg-color--ffb834, #FFB834);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e1qeljbtf {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m12.625 5.879l-.287.831c-.05.171.069.342.235.342h.356c.167 0 .284-.174.235-.342l-.24-.831c-.051-.185-.245-.185-.299 0");
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.e5q41c8fy {
  stop-color: var(--svg-color--ed9827, #ED9827);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.eziwjdbdq {
  stop-color: var(--svg-color--ff8524, #FF8524);
  stop-opacity: 0;
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f4147fa0n {
  stop-color: var(--svg-color--ff7447, #FF7447);
  stop-opacity: 0;
}

.f8fpdnbnw {
  stop-color: var(--svg-color--ffc031, #FFC031);
  stop-opacity: 0;
}

.fl5qg3bua {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.763 5.36a.63.63 0 0 0-.613.479c-.02.079.04.154.121.154h1.01a.104.104 0 0 0 .102-.123a.634.634 0 0 0-.62-.51");
}

.fmpd-_xyj {
  d: path("M10.646 6.679a.74.74 0 0 1-.41-.14v.421c0 .404.241.764.607.913a1.9 1.9 0 0 1-.156-.533z");
}

.fni059bsf {
  stop-color: var(--svg-color--ff6b3f, #FF6B3F);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.fszi1o-7g {
  stop-color: var(--svg-color--da800e, #DA800E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fthz0iw6h {
  stop-color: var(--svg-color--ffc12d, #FFC12D);
}

.fxi7ulo5m {
  cx: 11.735px;
  cy: 5.655px;
  rx: 0.176px;
  ry: 0.089px;
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g74-q2bdc {
  stop-color: var(--svg-color--ffbf31, #FFBF31);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.g7p406nqv {
  stop-color: var(--svg-color--d0431b, #D0431B);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.ggznuxqhy {
  fill: var(--svg-color--ffbf31, #FFBF31);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gifgm4i1v {
  stop-color: var(--svg-color--ffc128, #FFC128);
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gr7jnieaq {
  stop-color: var(--svg-color--ff6b38, #FF6B38);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.hxm-6izwk {
  stop-color: var(--svg-color--ffcd30, #FFCD30);
}

.i600yacue {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M14.533 4.765a.8.8 0 0 0-.31-.186c-.138-.043-.31-.055-.55-.025a.126.126 0 0 0 .031.249c.218-.027.351-.013.443.016c.09.028.15.074.221.136a.125.125 0 0 0 .165-.19");
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ijz9mfb4k {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.566 5.571a.432.432 0 0 0 .038.85a36 36 0 0 1-.038-.85");
}

.j--7hbfuf {
  stop-color: var(--svg-color--ff9128, #FF9128);
}

.j-x6w7b4y {
  stop-color: var(--svg-color--eda120, #EDA120);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.jat2c8bpf {
  stop-color: var(--svg-color--ff7049, #FF7049);
  stop-opacity: 0;
}

.jb48c2b-f {
  d: path("M9.782 3.43a.1.1 0 0 1 .1-.1h5.925a.1.1 0 0 1 .1.1v.863a.1.1 0 0 1-.1.1H9.882a.1.1 0 0 1-.1-.1z");
}

.jjrlpyxfw {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.926 5.36c.296 0 .545.204.613.479a.124.124 0 0 1-.121.154h-1.01a.104.104 0 0 1-.102-.123a.63.63 0 0 1 .62-.51");
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jwgdn5bsq {
  fill: var(--svg-color--000, #000);
  d: path("M13.601 5.887a.23.23 0 0 1 .232-.232a.23.23 0 0 1 .205.338h-.409a.2.2 0 0 1-.028-.106");
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.jyrqxvbae {
  stop-color: var(--svg-color--ffc128, #FFC128);
  stop-opacity: 0;
}

.k_t2a2ulc {
  d: path("m12.95 3.573l-.03-.062a.3.3 0 0 0-.278-.189h-.576a1.52 1.52 0 0 0-1.511 1.528v.125c-.154-.117-.348-.364-.348-.763c0-.485.354-.73.58-.887c.063-.044.117-.08.15-.114l.044-.048c.158-.167.44-.466.932-.597q.12-.03.239-.048c.468-.07.807.349.807.822v.227z");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.knaev-n-x {
  stop-color: var(--svg-color--ffd135, #FFD135);
  stop-opacity: 0;
}

.l277r0b8m {
  stop-color: var(--svg-color--ff6836, #FF6836);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lcjnzacgs {
  stop-color: var(--svg-color--e58f20, #E58F20);
}

.lck3-wbne {
  cx: 11.735px;
  cy: 5.655px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.ld99d_7hf {
  stop-color: var(--svg-color--e68e17, #E68E17);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m1km_jo3a {
  stop-color: var(--svg-color--ff5a36, #FF5A36);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.n1hgt6xzx {
  d: path("M13.804 5.568c.028.039-.032.086-.1.137c-.069.051-.12.087-.148.048c-.03-.038.003-.11.071-.162c.069-.051.148-.061.176-.023");
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.na810ccvo {
  d: path("m12.672 5.79l-.24.831c-.05.171.068.343.235.343h.355c.167 0 .285-.174.236-.343l-.24-.831c-.052-.184-.292-.184-.346 0");
}

.nhbmuhbvb {
  stop-color: var(--svg-color--c98041, #C98041);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of70meq1k {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.oimmmv6rh {
  stop-color: var(--svg-color--e2a433, #E2A433);
}

.oltlfmbmq {
  d: path("M12.226 5.84c0-.131-.107-.218-.135-.244l-.13.126l.08.163z");
}

.omy7ubc2p {
  fill: var(--svg-color--ffd231, #FFD231);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.ozv8tqbah {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("m15.09 6.425l.05-.86a.432.432 0 0 1-.05.86");
}

.p3ru7q3ze {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.podjqxb2m {
  d: path("M15.04 3.109c.233.08.442.242.574.475c.211.371.18.815-.048 1.143a.7.7 0 0 0-.122.395v.538a.8.8 0 0 0-.302-.122l.035-.726a.656.656 0 0 0-.623-.648h-.634c-.431 0-.822-.255-1-.653a.3.3 0 0 0-.278-.189h-.576a1.52 1.52 0 0 0-1.511 1.529l.013.695a.8.8 0 0 0-.325.12v-.544a.7.7 0 0 0-.123-.395a1.08 1.08 0 0 1-.064-1.106a1.06 1.06 0 0 1 .587-.51c.26-.092.48-.267.627-.502a1.05 1.05 0 0 1 1.307-.413a.67.67 0 0 0 .54 0a1.05 1.05 0 0 1 1.312.427c.139.23.357.398.612.486");
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.ppogkm8sl {
  d: path("M10.662 7.364c.117.883.868 1.54 1.758 1.54h.853c.89 0 1.641-.657 1.758-1.54c.053-.852.107-1.7.146-2.552a.656.656 0 0 0-.623-.648h-.634c-.431 0-.822-.255-1-.653a.3.3 0 0 0-.278-.189h-.576a1.52 1.52 0 0 0-1.511 1.528c0 .842.052 1.67.107 2.514");
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.proqfw3jj {
  d: path("M14.192 5.833a.4.4 0 0 0-.104-.209l-.118.13l.053.102z");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q2_7isbvq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.804 5.568c.028.039-.032.086-.1.137c-.069.051-.12.087-.148.048c-.03-.038.003-.11.071-.162c.069-.051.148-.061.176-.023");
}

.qe2iy6u-s {
  stop-color: var(--svg-color--fed031, #FED031);
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qqpuob36k {
  stop-color: var(--svg-color--c2b1ce, #C2B1CE);
  stop-opacity: 0;
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r24pfmh2j {
  stop-color: var(--svg-color--ff7049, #FF7049);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r52adsb8o {
  stop-color: var(--svg-color--d0431b, #D0431B);
  stop-opacity: 0;
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rahvf0pdu {
  stop-color: var(--svg-color--df9a36, #DF9A36);
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s0k1mrqwn {
  d: path("M15.044 6.679a.74.74 0 0 0 .409-.14v.421a.98.98 0 0 1-.607.913q.116-.246.157-.533z");
}

.s19ln7btb {
  d: path("M11.857 5.483a.404.404 0 0 0-.39.51h.78a.407.407 0 0 0-.39-.51");
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.sa73rem9k {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sepv3nkwr {
  d: path("M5.527 16.647c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.sg7xbrbid {
  stop-color: var(--svg-color--df9d34, #DF9D34);
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.swibnbi7z {
  fill: var(--svg-color--ffde41, #FFDE41);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.t1on3zqxv {
  d: path("M10.559 5.272a.728.728 0 0 0 .062 1.448a35 35 0 0 1-.062-1.448");
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u-m77k52c {
  stop-color: var(--svg-color--db9236, #DB9236);
  stop-opacity: 0;
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.u1162e6xa {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
  stop-opacity: 0;
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.udg1p6bpm {
  d: path("M15.07 6.72q.047-.722.084-1.444a.728.728 0 0 1-.083 1.444");
}

.ujgovaclr {
  stop-color: var(--svg-color--d57a1a, #D57A1A);
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.ux5bl2hml {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.253 7.208c.17.09.374.14.592.14c.22 0 .422-.05.592-.14a.144.144 0 0 1 .171.028a.14.14 0 0 1 .016.175m-1.371-.203l1.308.161m-1.308-.16v-.001a.144.144 0 0 0-.172.03a.14.14 0 0 0-.014.173m.186-.203l-.124.161m1.495.042l-.063-.042m.063.042l-.063-.042m.063.042a.93.93 0 0 1-.78.416a.93.93 0 0 1-.777-.416m1.494-.042a.86.86 0 0 1-.716.383a.86.86 0 0 1-.716-.383m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wgpnrcbke {
  stop-color: var(--svg-color--ffd135, #FFD135);
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wsjf7pm3j {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x0hdn9b5y {
  stop-color: var(--svg-color--ffa61d, #FFA61D);
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xjp952bfc {
  stop-color: var(--svg-color--ac799e, #AC799E);
}

.xk-67ebxg {
  d: path("m15.203 5.098l-.013-.285a.665.665 0 0 0-.636-.645h-.633c-.402 0-.77-.22-.961-.57c0 0 .326-.94.866-.818c.395.089.818.229 1.141.44c.79.514.651 1.442.236 1.878");
}

.xt8_tkusr {
  stop-color: var(--svg-color--e8992d, #E8992D);
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.yf7i1xbax {
  fill: var(--svg-color--000, #000);
  d: path("M12.088 5.887a.23.23 0 0 0-.231-.232a.23.23 0 0 0-.206.338h.41a.23.23 0 0 0 .027-.106");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.yxagr-bug {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.313-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.256");
}

.yzedoqb0u {
  stop-color: var(--svg-color--ff7447, #FF7447);
}

.z2lhmbb7y {
  stop-color: var(--svg-color--ffc428, #FFC428);
  stop-opacity: 0;
}

.z7vzzek9g {
  d: path("M13.833 5.483a.404.404 0 0 1 .389.51h-.78a.405.405 0 0 1 .39-.51");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zozrgybxd {
  stop-color: var(--svg-color--ed5722, #ED5722);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zxijwrkla {
  stop-color: var(--svg-color--ffd23b, #FFD23B);
}

</style>
