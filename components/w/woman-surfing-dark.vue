<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZf38he)"><path fill="url(#i0n68sc)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#iU8mBgY)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#i8Eejuc)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#i8TuAte)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#iwmlryd)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#iA4F7vb)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#iiEcdze)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#iL37XCz)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#ip943fd)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#iUB0EOd)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#iErJvWc)" clip-rule="evenodd" class="gs0rbvbfk"/><path fill="url(#iJ0FkFd)" clip-rule="evenodd" class="gs0rbvbfk"/></g><g filter="url(#iQwpGwd)"><path class="j7yytib_q"/><path fill="url(#iowsK2d)" class="ieaggqbvt"/></g><path fill="url(#iIoDHDd)" class="ieaggqbvt"/><path fill="url(#iF117ye)" class="ieaggqbvt"/><path fill="url(#iihFrAe)" class="ieaggqbvt"/><path fill="url(#io8EX5F)" class="ieaggqbvt"/><g filter="url(#iC17Q3c)"><path class="bc9mracia"/><path fill="url(#iydEkKe)" class="d052-0m2t"/></g><path class="wgn2vpbrp"/><path fill="url(#iFiUoFd)" class="un73mibps"/><path fill="url(#ionnvlb)" class="kc3j0qb6x"/><path fill="url(#ihBsP9c)" class="w0sqqrfqv"/><path fill="url(#iJKMIsb)" class="w0sqqrfqv"/><g filter="url(#iwsmDqc)"><path fill="url(#i5vY7oE)" class="gs-6lebez"/><path fill="url(#iPonf1c)" class="gs-6lebez"/></g><g filter="url(#ipgKpce)"><circle fill="url(#igywHHb)" class="lwub8rssv"/></g><g filter="url(#iQDobmd)"><circle fill="url(#iFuLNKe)" class="pd-zpcboh"/></g><g filter="url(#iRx9Udb)"><circle fill="url(#iRaRmfb)" class="b-ol02ugq"/></g><rect fill="url(#iCuyw7d)" transform="rotate(26.595 20.662 12.82)" class="oomjc-sil"/><g filter="url(#ivMactc)"><path fill="url(#iOhFZOd)" class="nrj0eebvt"/></g><path class="lgva52unf"/><g filter="url(#ipJljWc)"><path class="czv8_cbhz"/><path fill="url(#i19w8xe)" class="cgprekbkw"/><path fill="url(#iQyx2Wd)" class="cgprekbkw"/></g><g filter="url(#ipmHfvd)"><path fill="url(#ipp2gzz)" class="mak0bjbps"/><path fill="url(#i0xbTKc)" class="mak0bjbps"/><path fill="url(#iLd4nFc)" class="mak0bjbps"/></g><path fill="url(#iEoY6lI)" class="mak0bjbps"/><path fill="url(#iynIiHo)" class="s66euczxx"/><path fill="url(#iqwHkAf)" class="s66euczxx"/><path clip-rule="evenodd" class="qyf3nqkrh"/><path fill="url(#iJfITQd)" clip-rule="evenodd" class="brv8-4bhg"/><path clip-rule="evenodd" class="djfqx0cnm"/><path fill="url(#i6Xonqd)" clip-rule="evenodd" class="xt1wrzbia"/><path clip-rule="evenodd" class="nfiun5b-m"/><path fill="url(#itvAvcd)" clip-rule="evenodd" class="un8wc3fhr"/><path clip-rule="evenodd" class="ef4g6xbon"/><path fill="url(#imv7ate)" clip-rule="evenodd" class="rf3w2xb4u"/><path class="iks-xkbdj"/><path fill="url(#iDnH1na)" class="t1b4djbha"/><g filter="url(#iAHcoWd)"><path fill="url(#iVxKvFH)" class="p579ty99z"/></g><g filter="url(#isY8fwd)"><path fill="url(#id9dLtc)" class="f38c13bbb"/></g><g filter="url(#iPbiyjc)"><path stroke="url(#ibXCRvd)" class="bstx89bkb"/></g><path fill="url(#iL2nJIb)" class="br_r8y3lo"/><path fill="url(#iV7zX2b)" class="j7k-i4wra"/><g filter="url(#iIbvk3C)"><path fill="url(#iO0zEUb)" class="a79s2sb0o"/></g><g filter="url(#isyXXso)"><path fill="url(#iII5omb)" class="bp6nul0-m"/><path fill="url(#iUQRFyx)" class="bp6nul0-m"/></g><g filter="url(#iMMVT4H)"><path class="hnl-7zbgn"/><path fill="url(#icWPLbd)" class="du37ii9nh"/></g><g filter="url(#i2orG2r)"><path class="h_7_qmbbm"/><path fill="url(#iuZpGlb)" class="pgj7d_61z"/></g><path fill="url(#iwwFGQe)" class="yf_6ppbwc"/><path fill="url(#ifuK0fc)" class="yf_6ppbwc"/><path fill="url(#iFEtFTd)" class="yf_6ppbwc"/><path fill="url(#iKOkxKb)" class="yf_6ppbwc"/><path fill="url(#iePOfle)" class="yf_6ppbwc"/><path fill="url(#iCXLN8d)" class="yf_6ppbwc"/><path fill="url(#ibWxCBd)" class="yf_6ppbwc"/><path fill="url(#iwO376d)" class="yf_6ppbwc"/><path fill="url(#iyFcEpe)" class="yf_6ppbwc"/><path fill="url(#ikwa6Qc)" class="yf_6ppbwc"/><g filter="url(#ibz0qyd)"><path class="dth0a6bob"/></g><g filter="url(#iyzDGte)"><path class="s18vaccje"/><path fill="url(#ivNbUBb)" class="ylblg5bkh"/><path fill="url(#iPLtTbe)" class="ylblg5bkh"/><path fill="url(#iuitl2c)" class="ylblg5bkh"/><path fill="url(#imr8Sld)" class="ylblg5bkh"/></g><g filter="url(#iNtKGfe)"><path stroke="url(#i4X29Jb)" class="zv24o18re"/></g><path class="tr0w_q2jx"/><g filter="url(#ixdex9c)"><path class="brtunodig"/></g><g filter="url(#iN8seLd)"><path class="x-yvkjyox"/></g><g filter="url(#il5vuRd)"><path class="ptm8n5bjx"/></g><g filter="url(#iudS4Qb)"><path clip-rule="evenodd" class="v8i2zqhme"/></g><path class="gpqfqdbkf"/><path fill="url(#iPM0JQe)" class="owen7hbex"/><path class="f2gyyizqn"/><g filter="url(#inKr48i)"><path class="d1ie7bvai"/><path fill="url(#ipLXhvb)" class="g6wcqwkdr"/></g><g filter="url(#itmfsrD)"><path fill="url(#iLSsNec)" class="amyzy-kzo"/></g><path class="sl2o96bxa"/><path fill="url(#i8xD8ad)" class="kqjlo5b-s"/><path class="wgxb-hb6y"/><g filter="url(#icHLKqd)"><path fill="url(#iaY49Rc)" class="gd-09pbfx"/></g><g filter="url(#i3xqocc)"><ellipse transform="rotate(-27.914 13.06 5.692)" class="j5bld3bdx"/><ellipse fill="url(#if2l0JN)" transform="rotate(-27.914 13.06 5.692)" class="bcrzj3bts"/></g><g filter="url(#ijmKTQF)"><path class="kfnf0rbka"/><path fill="url(#iIbvzKd)" class="ejzodi91e"/><path fill="url(#ichZM3B)" class="ejzodi91e"/></g><g filter="url(#iBBu5Me)"><path stroke="url(#i5JhcSd)" class="x4lh8jb1x"/></g><g filter="url(#iP86bdc)"><path class="k35cl6bwr"/></g><defs><radialGradient id="iU8mBgY" cx="0" cy="0" r="1" gradientTransform="matrix(-.26744 2.02065 -2.5242 -.33408 14.013 7.107)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i8Eejuc" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 5.278 5.564)scale(1.54123 2.02505)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i8TuAte" cx="0" cy="0" r="1" gradientTransform="matrix(-.57945 .75775 -.58184 -.44493 12 6.097)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iwmlryd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57203 .93603 -.65935 -.40294 12.2 5.198)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iA4F7vb" cx="0" cy="0" r="1" gradientTransform="matrix(.60916 1.1589 -1.60874 .8456 12.587 2.426)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iiEcdze" cx="0" cy="0" r="1" gradientTransform="matrix(-.63884 .63889 -.89283 -.89277 16.732 3.348)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iL37XCz" cx="0" cy="0" r="1" gradientTransform="matrix(-.81714 .23773 -.49576 -1.70408 17.475 5.621)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ip943fd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.248 .31202 -.39747 -1.58978 17.208 7.137)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iUB0EOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40086 -1.17463 .92907 -.31706 16.245 4.541)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iErJvWc" cx="0" cy="0" r="1" gradientTransform="matrix(.66656 .06992 -.11329 1.08001 11.425 5.605)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iJ0FkFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3866 1.23498 -1.1384 -.35636 11.651 4.236)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iIoDHDd" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.782)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="iihFrAe" cx="0" cy="0" r="1" gradientTransform="matrix(3.56253 -6.12498 3.8162 2.21965 22.203 21.937)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="io8EX5F" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.781)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iydEkKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.169 25.219)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iFiUoFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.761 25.153)" gradientUnits="userSpaceOnUse"><stop class="ub7ea32uh"/><stop offset="1" class="w7mkf5ikd"/></radialGradient><radialGradient id="iJKMIsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.484)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="iPonf1c" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.746 2.824)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="igywHHb" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.213 11.143)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iFuLNKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.567)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iRaRmfb" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.166 9.178)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iCuyw7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.12)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="vgekv3bdy"/><stop offset="1" class="r95brsblk"/></radialGradient><radialGradient id="iOhFZOd" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.197 10.93)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="nbncwobqn"/><stop offset="1" class="na5vpgbch"/></radialGradient><radialGradient id="i19w8xe" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.924 6.723)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="hiph0yb8z"/><stop offset="1" class="nng6piu-d"/></radialGradient><radialGradient id="iQyx2Wd" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.33 10.558)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="rjhj4ebho"/><stop offset="1" class="m0m5thktx"/></radialGradient><radialGradient id="i0xbTKc" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.328 24.437)" gradientUnits="userSpaceOnUse"><stop class="zhpuq6bwb"/><stop offset="1" class="lrsiznbuc"/></radialGradient><radialGradient id="iLd4nFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.617)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="sz7_smkrr"/><stop offset="1" class="rqh0k2bpm"/></radialGradient><radialGradient id="iEoY6lI" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 -.625 2.3294 4.19292 17.339 21.25)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tn---htwd"/><stop offset="1" class="accyaboul"/></radialGradient><radialGradient id="iqwHkAf" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -1.10084 2.4083 18.61 10.764)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ns_rnx4db"/><stop offset="1" class="airol1bay"/><stop offset="1" class="cfcr9ub1k"/></radialGradient><radialGradient id="iJfITQd" cx="0" cy="0" r="1" gradientTransform="rotate(-164.074 4.364 6.446)scale(1.78035 1.88131)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="i6Xonqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6671 -.63637 .8491 -2.2244 6.355 14.415)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="itvAvcd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6486 -.68743 .9779 -2.34523 6.177 14.958)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="kn6afsb3f"/><stop offset=".922" class="t7r9i6b3f"/></radialGradient><radialGradient id="imv7ate" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40308 -.60156 .87252 -2.03506 6.294 15.229)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="iDnH1na" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.791)" gradientUnits="userSpaceOnUse"><stop class="bu3azkbir"/><stop offset="1" class="zga9nrbjv"/></radialGradient><radialGradient id="iVxKvFH" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.505 15.408)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iII5omb" cx="0" cy="0" r="1" gradientTransform="matrix(1.10318 -.50145 .61224 1.34693 15.938 6.193)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iUQRFyx" cx="0" cy="0" r="1" gradientTransform="matrix(.58316 .32687 -.09241 .16487 16.395 5.253)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="icWPLbd" cx="0" cy="0" r="1" gradientTransform="matrix(.6692 -.04978 .03891 .52313 16.093 6.048)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iuZpGlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53488 0 0 -.42195 12.108 5.999)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iwwFGQe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88248 1.3292 -1.77912 -3.85815 15.414 5.76)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="ifuK0fc" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 6.785 4.758)scale(.99989 .6963)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iFEtFTd" cx="0" cy="0" r="1" gradientTransform="matrix(.47578 -1.54065 1.9548 .60368 13.18 8.767)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iKOkxKb" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 4.602 9.31)scale(3.03475 3.051)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iePOfle" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.91055 -2.92613 0 14.03 5.933)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iCXLN8d" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.157 3.99)scale(3.11907 5.37008)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="ibWxCBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51004 .62596 0 15.167 5.575)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iwO376d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58173 .6667 0 13.227 5.474)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iyFcEpe" cx="0" cy="0" r="1" gradientTransform="matrix(-.56966 0 0 -2.85677 16.405 6.234)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="ikwa6Qc" cx="0" cy="0" r="1" gradientTransform="rotate(139.279 6.453 6.961)scale(1.06959 .71687)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="ivNbUBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2019 -.90593 .2792 -.06222 14.495 6.556)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="imr8Sld" cx="0" cy="0" r="1" gradientTransform="matrix(-.34544 0 0 -.09658 14.389 6.65)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iPM0JQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35959 -.57196 0 15.114 5.734)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ipLXhvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10254 -.13214 .18193 -.14118 15.012 5.771)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8xD8ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35959 -.57197 0 13.18 5.734)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="if2l0JN" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 9.397 -3.51)scale(.21848 .26262)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIbvzKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.93605 1.94635 -3.18218 -1.53038 14.994 2.486)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ichZM3B" cx="0" cy="0" r="1" gradientTransform="matrix(-.09322 .60596 -1.3037 -.20057 14.24 2.65)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iZf38he" width="6.906" height="7.406" x="10.819" y="1.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="iQwpGwd" width="23.977" height="13.398" x="6.016" y="16.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="iC17Q3c" width="20.681" height="10.082" x="6.11" y="20.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".75"/></filter><filter id="iwsmDqc" width="24.344" height="8.644" x="2.007" y="21.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="ipgKpce" width="2.686" height="2.686" x="24.571" y="13.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="iQDobmd" width="2.186" height="2.186" x="27.821" y="11.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="iRx9Udb" width="1.928" height="1.928" x="25.946" y="9.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="ivMactc" width="2.857" height="2.898" x="20.532" y="12.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.14902 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="ipJljWc" width="5.571" height="6.952" x="7.773" y="7.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.219608 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="ipmHfvd" width="14.97" height="18.152" x="8.427" y="7.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.470588 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="iAHcoWd" width="17.737" height="14.8" x="13.579" y="15.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation="1"/></filter><filter id="isY8fwd" width="6.506" height="14.75" x="14.572" y="7.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".375"/></filter><filter id="iPbiyjc" width="5.506" height="5.421" x="17.991" y="7.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".3"/></filter><filter id="iIbvk3C" width="1.576" height="1.426" x="11.357" y="5.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="isyXXso" width="1.426" height="1.676" x="15.574" y="5.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="iMMVT4H" width="1.952" height="1.952" x="15.31" y="5.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".25"/></filter><filter id="i2orG2r" width="1.452" height="1.452" x="11.353" y="5.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".125"/></filter><filter id="ibz0qyd" width="1.832" height="2.189" x="13.159" y="5.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".25"/></filter><filter id="iyzDGte" width="1.032" height="1.389" x="13.631" y="5.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".05"/></filter><filter id="iNtKGfe" width="1.864" height=".899" x="13.215" y="6.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".05"/></filter><filter id="ixdex9c" width="1.442" height=".57" x="14.454" y="5.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="iN8seLd" width="1.442" height=".57" x="12.399" y="5.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="il5vuRd" width="1.198" height=".595" x="12.459" y="4.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="iudS4Qb" width="1.198" height=".595" x="14.86" y="4.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/></filter><filter id="inKr48i" width=".459" height=".419" x="14.733" y="5.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".05"/></filter><filter id="itmfsrD" width=".617" height=".627" x="15.05" y="5.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".1"/></filter><filter id="icHLKqd" width=".659" height=".683" x="13.081" y="5.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".1"/></filter><filter id="i3xqocc" width=".515" height=".423" x="12.802" y="5.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".05"/></filter><filter id="ijmKTQF" width="4.092" height="2.691" x="12.575" y="2.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22992"/><feGaussianBlur result="effect2_foregroundBlur_3987_22992" stdDeviation=".075"/></filter><filter id="iBBu5Me" width=".841" height="1.358" x="12.566" y="2.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".1"/></filter><filter id="iP86bdc" width="3.684" height="2.33" x="13.472" y="2.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22992" stdDeviation=".375"/></filter><linearGradient id="i0n68sc" x1="16.227" x2="13.211" y1="2.917" y2="8.504" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iowsK2d" x1="7.172" x2="16.735" y1="29.375" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iF117ye" x1="16.86" x2="16.766" y1="30.281" y2="28.656" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="ionnvlb" x1="21.172" x2="19.469" y1="21.938" y2="23.023" gradientUnits="userSpaceOnUse"><stop class="l20_z6baj"/><stop offset="1" class="spcerobbw"/></linearGradient><linearGradient id="ihBsP9c" x1="22.095" x2="23.329" y1="24.844" y2="26.125" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="i5vY7oE" x1="5.891" x2="25.735" y1="29.25" y2="22.344" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="ipp2gzz" x1="15.777" x2="15.777" y1="7.617" y2="25.578" gradientUnits="userSpaceOnUse"><stop class="t_t1uhgaw"/><stop offset="1" class="wlohty-lv"/></linearGradient><linearGradient id="iynIiHo" x1="23.651" x2="16.517" y1="12.514" y2="8.56" gradientUnits="userSpaceOnUse"><stop class="g55u5uboh"/><stop offset=".91" class="hq3x-3bjw"/></linearGradient><linearGradient id="id9dLtc" x1="17.826" x2="20.269" y1="8.172" y2="21.408" gradientUnits="userSpaceOnUse"><stop class="xf-olmy6i"/><stop offset="1" class="nb49g6u5x"/></linearGradient><linearGradient id="ibXCRvd" x1="22.438" x2="18.766" y1="11.891" y2="8" gradientUnits="userSpaceOnUse"><stop class="o-7v_hpgv"/><stop offset="1" class="qosi95ahb"/></linearGradient><linearGradient id="iL2nJIb" x1="10.971" x2="17.327" y1="8.13" y2="8.13" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iV7zX2b" x1="10.986" x2="17.312" y1="8.117" y2="8.117" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iO0zEUb" x1="11.357" x2="12.669" y1="6.037" y2="6.037" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iPLtTbe" x1="13.731" x2="14.147" y1="6.589" y2="6.589" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iuitl2c" x1="14.147" x2="14.147" y1="6.943" y2="6.672" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i4X29Jb" x1="13.675" x2="13.88" y1="7.568" y2="7.252" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iLSsNec" x1="15.459" x2="15.32" y1="5.758" y2="5.843" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaY49Rc" x1="13.509" x2="13.37" y1="5.758" y2="5.843" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5JhcSd" x1="12.866" x2="13.107" y1="3.251" y2="3.816" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-surfing-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a79s2sb0o {
  d: path("M12.07 6.712a.713.713 0 1 0 0-1.427a.713.713 0 0 0 0 1.427");
}

.accyaboul {
  stop-color: var(--svg-color--593b9d, #593B9D);
  stop-opacity: 0;
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.amyzy-kzo {
  d: path("M15.467 5.865a.37.37 0 0 0-.102-.204l-.115.126l.052.1z");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b-ol02ugq {
  cx: 26.86px;
  cy: 10.738px;
  r: 0.914px;
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.bc9mracia {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("m21.985 27.344l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.199 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.bcrzj3bts {
  cx: 13.059px;
  cy: 5.692px;
  rx: 0.172px;
  ry: 0.087px;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bp6nul0-m {
  d: path("M16.287 6.712a.713.713 0 1 0 0-1.426a.713.713 0 0 0 0 1.426");
}

.br_r8y3lo {
  d: path("M14.305 8.117q.166.008.34.022q-.17-.014-.34-.022");
}

.brtunodig {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M14.654 5.746c.117-.206.296-.37.68-.37c.17 0 .332.047.476.164c.12.096.104.219.011.265l-.246.14c-.289-.093-.608-.105-.921-.199");
}

.brv8-4bhg {
  fill-rule: evenodd;
  d: path("M7.127 13.555c-.941-.284-1.295.01-1.388.12a.375.375 0 0 1-.57-.489c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.bstx89bkb {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.297c1.209-.021 3.782.828 4.104 4");
}

.bu3azkbir {
  stop-color: var(--svg-color--61504f, #61504F);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.cfcr9ub1k {
  stop-color: var(--svg-color--6845b9, #6845B9);
  stop-opacity: 0;
}

.cgprekbkw {
  d: path("M10.684 11.707c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.03c.3-.026 1.148-.108 2.5-.718c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.387c-.376 1.032-1.005 2.246-2.38 3.262");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.czv8_cbhz {
  fill: var(--svg-color--7a5cb9, #7A5CB9);
  d: path("M10.684 11.707c-.967.715-2.204 1.017-2.723 1.059c-.13 1 .107 1.77.243 2.03c.3-.026 1.148-.108 2.5-.718c1.679-.757 2.458-1.803 2.64-2.246l-.28-3.387c-.376 1.032-1.005 2.246-2.38 3.262");
}

.d052-0m2t {
  d: path("m21.985 27.344l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.199 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d1ie7bvai {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.085 5.606c.028.038-.03.084-.097.134s-.117.085-.145.047c-.028-.037.004-.108.07-.158c.067-.05.144-.06.172-.023");
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.djfqx0cnm {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.404 14.15s.02-.027.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 1 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dth0a6bob {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m13.973 5.9l-.303.753a.24.24 0 0 0 .231.31h.349a.24.24 0 0 0 .23-.31l-.235-.753c-.05-.167-.219-.167-.272 0");
}

.du37ii9nh {
  d: path("M16.287 6.475a.476.476 0 1 0 0-.952a.476.476 0 0 0 0 .952");
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.ef4g6xbon {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.611 14.956a.375.375 0 0 1-.69-.295c.093-.216.328-.446.6-.605a1.76 1.76 0 0 1 1.119-.236a.375.375 0 1 1-.099.743a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164c-.051.051-.07.083-.074.089");
}

.ejzodi91e {
  d: path("M13.88 2.546c-.502-.111-.953.39-1.005.575c.466 1.572 1.646 1.485 2.81 1.356c.697-.077.772.24.832.394c0-1.743-1.482-2.07-2.625-2.323z");
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.f2gyyizqn {
  fill: var(--svg-color--000, #000);
  d: path("M14.889 5.918c0-.126.1-.226.226-.226a.226.226 0 0 1 .201.33h-.4a.2.2 0 0 1-.027-.104");
}

.f38c13bbb {
  d: path("M16.782 13.461c-.65-1.28-1.166-3.185-1.443-4.423a.714.714 0 0 1 .588-.856c.447-.075.855.271.91.722c.205 1.698.95 3.373 1.445 4.682c.578 1.531.312 1.063.234 3.516c-.057 1.78 1.266 3.25 1.813 4.11l-.407.21c-.609-.828-2.203-2.945-2.203-4.852c0-1.79.063-1.14-.937-3.109");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g55u5uboh {
  stop-color: var(--svg-color--896ad2, #896AD2);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6wcqwkdr {
  d: path("M15.085 5.606c.028.038-.03.084-.097.134s-.117.085-.145.047c-.028-.037.004-.108.07-.158c.067-.05.144-.06.172-.023");
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gd-09pbfx {
  d: path("M13.54 5.871c0-.127-.104-.213-.132-.238l-.127.123l.078.16z");
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gpqfqdbkf {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.207 5.402c.29 0 .534.2.6.47a.12.12 0 0 1-.118.15h-.99a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .608-.5");
}

.gs-6lebez {
  d: path("M24.458 21.273L2.29 28.962a.421.421 0 0 0 .138.82h3.948c.487 0 .968-.1 1.156-.157c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.001c.094-.25.047-1.031-.5-1.453c-.437-.338-1.105-.185-1.355-.07");
}

.gs0rbvbfk {
  fill-rule: evenodd;
  d: path("M17.332 6.623c.094-.193.143-.408.143-.632q-.002-.312-.119-.579h.003a1.4 1.4 0 0 0-.125-.227l-.001-.001A1.44 1.44 0 0 1 17 4.399v-.005c0-.807-.655-1.462-1.462-1.462a.24.24 0 0 1-.202-.103a1.465 1.465 0 0 0-2.378 0a.25.25 0 0 1-.201.103h-.038c-.79.02-1.425.667-1.425 1.462V4.4c0 .278-.08.551-.233.785v.001a1.46 1.46 0 0 0-.098 1.438a.23.23 0 0 1 0 .202a1.424 1.424 0 0 0 1.283 2.05h3.803a1.424 1.424 0 0 0 1.283-2.05a.23.23 0 0 1 0-.202M11.898 5.44h-.006l.532 1.044c.054 1.242.539 0 1.723 0s1.7 1.382 1.755.14l.504-1.417c-.024-.551-.424-.59-.504-.59h-1.427a1.71 1.71 0 0 1-1.414-.742a.117.117 0 0 0-.204.023l-.037.086c-.1.249-.29.438-.527.547l-.022.009l-.023.01c-.105.053-.35.216-.36.637l.005.135z");
}

.h_7_qmbbm {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M12.079 6.475a.476.476 0 1 0 0-.952a.476.476 0 0 0 0 .952");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hiph0yb8z {
  stop-color: var(--svg-color--8069a8, #8069A8);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hnl-7zbgn {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M16.287 6.475a.476.476 0 1 0 0-.952a.476.476 0 0 0 0 .952");
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hq3x-3bjw {
  stop-color: var(--svg-color--8c6dd3, #8C6DD3);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.ieaggqbvt {
  d: path("M19.75 29.76H6.017c3.433-1.327 10.769-4.347 12.657-5.819c2.359-1.84 2.937-3.291 4.109-4.976c1.172-1.684 2.062-2.293 3.922-2.035c1.691.234 3.164 1.574 3.289 4.039c0 4.593-2.74 6.555-4.164 7.511c-1.907 1.28-4.625 1.326-6.078 1.28");
}

.iks-xkbdj {
  fill: var(--svg-color--4c3531, #4C3531);
  d: path("M6.126 14.898c.125-.137.398-.46.52-.605c.23 0 .91-.066 1.198-.098c-.39.715-.84 1.004-1.074 1.196c-.316.21-.605 0-.644-.067c-.047-.047-.157-.254 0-.426");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j5bld3bdx {
  cx: 13.059px;
  cy: 5.692px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.j7k-i4wra {
  d: path("M14.158 8.117h-.017c.044 0 .083 0 .127.005q-.054-.006-.11-.005");
}

.j7yytib_q {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.76H6.017c3.433-1.327 10.769-4.347 12.657-5.819c2.359-1.84 2.937-3.291 4.109-4.976c1.172-1.684 2.062-2.293 3.922-2.035c1.691.234 3.164 1.574 3.289 4.039c0 4.593-2.74 6.555-4.164 7.511c-1.907 1.28-4.625 1.326-6.078 1.28");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.k35cl6bwr {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m15.214 4.145l-.632.117a.305.305 0 1 1-.055-.605h1.037c.614 0 .817.618.842.83a1.4 1.4 0 0 0-1.192-.342");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kc3j0qb6x {
  d: path("M19.837 23.023a29 29 0 0 1-.907-.867l1.867-.883c.075.132.51.8.72 1.118z");
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kfnf0rbka {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M13.88 2.546c-.502-.111-.953.39-1.005.575c.466 1.572 1.646 1.485 2.81 1.356c.697-.077.772.24.832.394c0-1.743-1.482-2.07-2.625-2.323z");
}

.kn6afsb3f {
  stop-color: var(--svg-color--58443e, #58443E);
  stop-opacity: 0;
}

.kqjlo5b-s {
  d: path("M13.179 5.523a.396.396 0 0 0-.381.5h.764a.398.398 0 0 0-.383-.5");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l20_z6baj {
  stop-color: var(--svg-color--695857, #695857);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lgva52unf {
  fill: var(--svg-color--4c3531, #4C3531);
  d: path("M7.602 12.787h.594c-.106.669.012 1.608.114 1.996c-1.006.132-1.637-.108-1.856-.246l-.11-1.46c.332-.257.977-.3 1.258-.29");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lrsiznbuc {
  stop-color: var(--svg-color--623f8d, #623F8D);
  stop-opacity: 0;
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.lwub8rssv {
  cx: 25.864px;
  cy: 14.773px;
  r: 1.293px;
}

.m0m5thktx {
  stop-color: var(--svg-color--572cad, #572CAD);
  stop-opacity: 0;
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mak0bjbps {
  d: path("M12.759 11.664c-.432-1.715.169-3.161.507-3.484l2.344-.563h1.742c1.524 0 2.822.19 4.203 1.258c1.354 1.047 1.622 2.8 1.589 3.592a.05.05 0 0 1-.051.047l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.372-.066-1.274-1-2.015c-.606-.48-1.519-.531-2.146-.494a.373.373 0 0 0-.323.498c.316.956.84 2.513 1.212 3.52c.546 1.484-.11 2.953.375 4.484c.377 1.192 1.203 2.419 1.636 2.92a.04.04 0 0 1-.013.064l-1.834.85a.04.04 0 0 1-.048-.01c-1.848-2.156-2.5-3.825-2.562-3.988c-.062-.164-.23-.531-.574-.531c-.275 0-.59.351-.809.73l-4.667 7.137a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.067c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.917.14-1.086c-.03-.13-.218-.711-.585-2.172");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.na5vpgbch {
  stop-color: var(--svg-color--4b3234, #4B3234);
}

.nb49g6u5x {
  stop-color: var(--svg-color--8b79ca, #8B79CA);
}

.nbncwobqn {
  stop-color: var(--svg-color--6b5957, #6B5957);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nfiun5b-m {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.25 14.678q-.005.007-.002.001a.375.375 0 0 1-.69-.296a1.2 1.2 0 0 1 .27-.354a2.6 2.6 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.369a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.262a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.nng6piu-d {
  stop-color: var(--svg-color--8069a8, #8069A8);
  stop-opacity: 0;
}

.nrj0eebvt {
  d: path("M20.68 13.86c.256-.588.373-1.22.399-1.462l2.047.024c.046.269-.04.584-.079.703c.088.322.037.687 0 .83c-.054.225-.178.712-.238.859c-.074.184-.183.246-.348.23a.4.4 0 0 1-.148-.042a.3.3 0 0 0-.23-.02a.43.43 0 0 1-.227.02a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.005a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.071c-.085.007-.183.002-.235-.041c-.098-.082-.219-.176.031-.747");
}

.ns_rnx4db {
  stop-color: var(--svg-color--6845b9, #6845B9);
}

.o-7v_hpgv {
  stop-color: var(--svg-color--9577dc, #9577DC);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.oomjc-sil {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.82px;
  rx: 0.299px;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.owen7hbex {
  d: path("M15.115 5.523a.396.396 0 0 1 .381.5h-.764a.397.397 0 0 1 .383-.5");
}

.p579ty99z {
  d: path("M26.485 24.344c.981-2.279.626-3.887.055-5.014c-.474-.935-.003-1.662 1.018-1.42c.737.174 1.364.694 1.54 1.43c.721 3.025-.313 6.182-3.582 7.816c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.722 10.906-4.281");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pd-zpcboh {
  cx: 28.864px;
  cy: 12.824px;
  r: 1.043px;
}

.pgj7d_61z {
  d: path("M12.079 6.475a.476.476 0 1 0 0-.952a.476.476 0 0 0 0 .952");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ptm8n5bjx {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.641 5.21l-.002.002a.119.119 0 0 1-.122-.204l.002-.001l.004-.003l.015-.008l.051-.026c.044-.02.106-.047.182-.071c.15-.049.361-.089.589-.049a.119.119 0 0 1-.042.234a1 1 0 0 0-.475.041a1 1 0 0 0-.192.08z");
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qosi95ahb {
  stop-color: var(--svg-color--9577dc, #9577DC);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qyf3nqkrh {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M7.127 13.555c-.941-.284-1.295.01-1.388.12a.375.375 0 0 1-.57-.489c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r95brsblk {
  stop-color: var(--svg-color--3a1c21, #3A1C21);
}

.rf3w2xb4u {
  fill-rule: evenodd;
  d: path("M5.611 14.956a.375.375 0 0 1-.69-.295c.093-.216.328-.446.6-.605a1.76 1.76 0 0 1 1.119-.236a.375.375 0 1 1-.099.743a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164c-.051.051-.07.083-.074.089");
}

.rjhj4ebho {
  stop-color: var(--svg-color--572cad, #572CAD);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rqh0k2bpm {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
  stop-opacity: 0;
}

.s18vaccje {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m13.978 5.839l-.236.753a.24.24 0 0 0 .231.31h.349a.24.24 0 0 0 .23-.31l-.235-.753c-.05-.167-.286-.167-.34 0");
}

.s66euczxx {
  d: path("M17.568 10.289a.37.37 0 0 1 .34-.416c.628-.037 1.541.013 2.147.494c.934.741 1.038 1.643 1 2.015c-.003.03.02.056.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.794-.235-2.546-1.589-3.593c-1.381-1.069-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.672");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sl2o96bxa {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.088 5.402a.62.62 0 0 0-.6.47a.12.12 0 0 0 .118.15h.989a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.607-.5");
}

.spcerobbw {
  stop-color: var(--svg-color--371f23, #371F23);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sz7_smkrr {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
}

.t_t1uhgaw {
  stop-color: var(--svg-color--8463ce, #8463CE);
}

.t1b4djbha {
  d: path("M6.126 14.898c.125-.137.398-.46.52-.605c.23 0 .91-.066 1.198-.098c-.39.715-.84 1.004-1.074 1.196c-.316.21-.605 0-.644-.067c-.047-.047-.157-.254 0-.426");
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t7r9i6b3f {
  stop-color: var(--svg-color--58443e, #58443E);
}

.tn---htwd {
  stop-color: var(--svg-color--593b9d, #593B9D);
}

.tr0w_q2jx {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M14.147 7.29c-.23 0-.448-.056-.63-.154c-.062-.032-.13.04-.09.098a.856.856 0 0 0 1.44 0c.04-.06-.027-.13-.09-.098a1.34 1.34 0 0 1-.63.153");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ub7ea32uh {
  stop-color: var(--svg-color--635351, #635351);
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.un73mibps {
  d: path("m7.305 27.36l1.172-2.391l1.766.304v1.04z");
}

.un8wc3fhr {
  fill-rule: evenodd;
  d: path("M5.25 14.678q-.005.007-.002.001a.375.375 0 0 1-.69-.296a1.2 1.2 0 0 1 .27-.354a2.6 2.6 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.369a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.262a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v8i2zqhme {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m15.8 5.008l-.06.102za.119.119 0 0 1-.121.204l-.002-.001l-.05-.026a1 1 0 0 0-.152-.06a1 1 0 0 0-.475-.04a.119.119 0 1 1-.041-.235c.227-.04.438 0 .588.049a1.5 1.5 0 0 1 .248.105l.004.003z");
}

.vgekv3bdy {
  stop-color: var(--svg-color--3e2828, #3E2828);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.w0sqqrfqv {
  d: path("m23.469 25.338l-.422-1.143l-2.351.537l2.225 1.098a.396.396 0 0 0 .547-.492");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w7mkf5ikd {
  stop-color: var(--svg-color--635351, #635351);
  stop-opacity: 0;
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgn2vpbrp {
  fill: var(--svg-color--4e3732, #4E3732);
  d: path("m7.305 27.36l1.172-2.391l1.766.304v1.04z");
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wgxb-hb6y {
  fill: var(--svg-color--000, #000);
  d: path("M13.406 5.918a.225.225 0 0 0-.227-.226a.226.226 0 0 0-.201.33h.4a.2.2 0 0 0 .028-.104");
}

.wlohty-lv {
  stop-color: var(--svg-color--6247a5, #6247A5);
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x-yvkjyox {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.64 5.746c-.117-.206-.296-.37-.68-.37a.74.74 0 0 0-.476.164c-.12.096-.103.219-.01.265l.246.14c.288-.093.608-.105.92-.199");
}

.x4lh8jb1x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.866 3.1c.01.107.104.512.241.757");
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xf-olmy6i {
  stop-color: var(--svg-color--9a7ce0, #9A7CE0);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xt1wrzbia {
  fill-rule: evenodd;
  d: path("M5.404 14.15s.02-.027.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 1 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yf_6ppbwc {
  d: path("M11.892 5.439h.006l-.005-.118l-.005-.135c.01-.42.255-.584.36-.638l.022-.009l.023-.009c.236-.108.427-.298.527-.547l.037-.086c.036-.086.15-.1.204-.023c.318.466.85.742 1.414.742h1.427c.08 0 .48.039.503.59l-.052 1.362c-.055 1.243-1.025 2.077-2.209 2.077s-2.154-.834-2.209-2.077z");
}

.ylblg5bkh {
  d: path("m13.978 5.839l-.236.753a.24.24 0 0 0 .231.31h.349a.24.24 0 0 0 .23-.31l-.235-.753c-.05-.167-.286-.167-.34 0");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zga9nrbjv {
  stop-color: var(--svg-color--61504f, #61504F);
  stop-opacity: 0;
}

.zhpuq6bwb {
  stop-color: var(--svg-color--623f8d, #623F8D);
}

.zv24o18re {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.147 7.29c-.23 0-.448-.056-.63-.154c-.062-.032-.13.04-.09.098a.856.856 0 0 0 1.44 0c.04-.06-.027-.13-.09-.098a1.34 1.34 0 0 1-.63.153Z");
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
