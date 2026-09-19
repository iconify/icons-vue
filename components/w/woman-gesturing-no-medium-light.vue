<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iX0wQ9d)"><path fill="url(#ifPUErb)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#iCHAzjh)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#iNAo6qe)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#iGu8Uhd)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#i45ockc)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#iakyEld)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#iRFVB4d)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#i77I3Oc)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#iErjX4v)" clip-rule="evenodd" class="r594lytyn"/><path fill="url(#ih7Y2Je)" clip-rule="evenodd" class="r594lytyn"/></g><path fill="url(#ioihRxd)" clip-rule="evenodd" class="r594lytyn"/><g filter="url(#is0y5Ee)"><path fill="url(#ikRfkbc)" class="ja6b6i3wf"/></g><g filter="url(#iG4THvJ)"><path fill="url(#iGgVykd)" class="pcjcfdcqg"/><path fill="url(#iJG4d0b)" class="pcjcfdcqg"/></g><g filter="url(#iH0aSNb)"><path class="rnuj69bls"/><path fill="url(#ia5Bhvc)" class="h2_5b9b-m"/></g><g filter="url(#id4iOmd)"><path class="ldoae_5ma"/><path fill="url(#iUT1EPc)" class="gayqowq-c"/></g><g filter="url(#iqtWRme)"><path fill="url(#iismtPb)" class="hyx6dcc2k"/><path fill="url(#imiPLDe)" class="hyx6dcc2k"/><path fill="url(#ihU2qDP)" class="hyx6dcc2k"/><path fill="url(#iobkEjb)" class="hyx6dcc2k"/><path fill="url(#iSkGtEb)" class="hyx6dcc2k"/><path fill="url(#iNJUSVc)" class="hyx6dcc2k"/><path fill="url(#iaFkaoc)" class="hyx6dcc2k"/></g><path fill="url(#iTA6JUb)" class="jdp51105x"/><path fill="url(#iLloqEX)" class="jdp51105x"/><g filter="url(#iUPj2ld)"><path class="eq_fjabcu"/></g><g filter="url(#ibaadKb)"><path class="v9q6brb3d"/><path fill="url(#iiKFPYq)" class="l32lfm6cu"/><path fill="url(#i9uXmbc)" class="l32lfm6cu"/><path fill="url(#iVOqGad)" class="l32lfm6cu"/></g><path fill="url(#i8nNuOb)" class="l32lfm6cu"/><path fill="url(#ixwqGWc)" class="l32lfm6cu"/><g filter="url(#iP4ZCob)"><path class="ck2zm2jih"/></g><g filter="url(#iA4hkCe)"><path class="ykvy-obdh"/></g><path class="r6yp65b6h"/><path fill="url(#ifxqCVd)" class="d8h7ar12o"/><path class="runybrbtv"/><g filter="url(#iobktPe)"><path class="on_mu-bbf"/><path fill="url(#iv075uc)" class="g148pmbqn"/></g><g filter="url(#iEgMpgd)"><path fill="url(#i7OuFlB)" class="t77o7ob_c"/></g><path class="ulx55wb6s"/><path fill="url(#iaig08b)" class="ji-5-2wkk"/><path class="aakerk86q"/><g filter="url(#iGD9poe)"><path fill="url(#iK079Cd)" class="mxqn-tmeq"/></g><g filter="url(#iNyrrbe)"><ellipse transform="rotate(-27.914 12.91 11.836)" class="f93ezcbos"/><ellipse fill="url(#itj3QWb)" transform="rotate(-27.914 12.91 11.836)" class="xqi3rzbvq"/></g><g filter="url(#iWPonWr)"><path fill="url(#iUKCa4d)" class="yn9dvdegj"/><path fill="url(#i8SDmRd)" class="yn9dvdegj"/></g><g filter="url(#imbrk1d)"><path fill="url(#iRaTQSb)" class="v5ovupb9l"/><path fill="url(#iI4qdjc)" class="v5ovupb9l"/><path fill="url(#iSYvCHd)" class="v5ovupb9l"/></g><g filter="url(#igQpjdb)"><path stroke="url(#iKcHNNb)" class="nnikzcbjy"/></g><g filter="url(#iGFUldB)"><path class="qsrvd3bbo"/></g><g filter="url(#iYtLnFT)"><path class="dbbkm8r5g"/></g><g filter="url(#i47HVYW)"><path class="duuxb9bip"/></g><g filter="url(#ivTggOe)"><path class="su64_3bwn"/></g><path class="sz9l9lc9u"/><path fill="url(#iJD9oab)" class="y57xohvpz"/><path fill="url(#ioGfCsb)" class="y57xohvpz"/><path fill="url(#iqgXPWH)" class="y57xohvpz"/><path fill="url(#icXzeJb)" class="o-3y3l8ww"/><path fill="url(#i7RDBCe)" class="uza0nib2y"/><path fill="url(#ih3094d)" class="uza0nib2y"/><path fill="url(#igi1Cxd)" class="uza0nib2y"/><path fill="url(#i7tPZsc)" class="uza0nib2y"/><path fill="url(#ivvJGYb)" class="uza0nib2y"/><path fill="url(#iMTmOGc)" class="uza0nib2y"/><path fill="url(#iR3T2Nc)" class="uza0nib2y"/><path fill="url(#iZZ4QUi)" class="spt1f3y0o"/><path fill="url(#inVUPuG)" class="spt1f3y0o"/><path fill="url(#i6AnLvp)" class="c_g0zlbky"/><path fill="url(#iwP8L1c)" class="c_g0zlbky"/><path fill="url(#iomHb0y)" class="c_g0zlbky"/><path fill="url(#icZhhSc)" class="c_g0zlbky"/><path fill="url(#igr3QGd)" class="x1ls_mb4u"/><path fill="url(#iYQ3t0k)" class="x1ls_mb4u"/><path fill="url(#i9iwhQb)" class="x1ls_mb4u"/><path fill="url(#iQMnohL)" class="b4ne_pb_z"/><path fill="url(#ixhWWFv)" class="b4ne_pb_z"/><path fill="url(#i4q9jKj)" class="me1f_zg8u"/><path fill="url(#iUMdaDc)" class="me1f_zg8u"/><path fill="url(#issm3wd)" class="me1f_zg8u"/><path fill="url(#icYA7cc)" class="me1f_zg8u"/><g filter="url(#i6QaOzd)"><path fill="url(#iVL8rGe)" class="hsx7mfqqi"/><path fill="url(#id5VUQd)" class="hsx7mfqqi"/></g><path fill="url(#ickCN2V)" class="hsx7mfqqi"/><g filter="url(#if2CMCe)"><path fill="url(#i35v49b)" class="g-qc2ggws"/></g><defs><radialGradient id="iCHAzjh" cx="0" cy="0" r="1" gradientTransform="matrix(2.19576 -4.5604 10.398 5.00646 21.911 20.039)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iNAo6qe" cx="0" cy="0" r="1" gradientTransform="matrix(-.16894 6.9673 -6.52184 -.15814 15.155 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iGu8Uhd" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 3.261 10.167)scale(5.02561 6.18626)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="i45ockc" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 1.571 9.068)scale(2.24341 2.03916)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iakyEld" cx="0" cy="0" r="1" gradientTransform="matrix(-2.93472 -.65448 .9621 -4.31405 10.574 11.109)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iRFVB4d" cx="0" cy="0" r="1" gradientTransform="rotate(55.684 2.581 12.155)scale(4.8313 8.43127)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="i77I3Oc" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 10.26 7.778)scale(2.06217 2.88185)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iErjX4v" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.9 7.632)scale(2.41861 5.26257)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="ih7Y2Je" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 11.017 10.132)scale(4.31368 6.873)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iGgVykd" cx="0" cy="0" r="1" gradientTransform="matrix(3.13528 -1.42513 1.74002 3.82804 21.088 13.262)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iJG4d0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.25622 .35893 -.1887 .66045 22.377 10.465)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="ia5Bhvc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 47.23 -54.346)scale(1.64329)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iUT1EPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53279 0 0 -1.46621 10.122 12.71)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iismtPb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.48 8.167)scale(9.02114 12.0746)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="imiPLDe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65749 1.40564 -1.19259 -2.25469 18.394 12.91)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="ihU2qDP" cx="0" cy="0" r="1" gradientTransform="matrix(1.05418 -5.09537 6.46508 1.33756 13.254 20.575)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iobkEjb" cx="0" cy="0" r="1" gradientTransform="rotate(99.506 3.424 13.248)scale(9.20499 11.0632)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="pj__wrb2a"/><stop offset="1" class="hiw8w_whp"/></radialGradient><radialGradient id="iSkGtEb" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.9 8.049)scale(7.28568 12.5437)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iNJUSVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44954 2.08389 0 18.899 11.505)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iaFkaoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.7131 1.96333 0 13.584 11.615)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iTA6JUb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69666 0 0 -5.58546 22.418 13.379)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iLloqEX" cx="0" cy="0" r="1" gradientTransform="rotate(-118.684 13.68 5.56)scale(7.80865 7.12508)" gradientUnits="userSpaceOnUse"><stop class="keyognb9o"/><stop offset="1" class="lrlfk0bvq"/></radialGradient><radialGradient id="iiKFPYq" cx="0" cy="0" r="1" gradientTransform="matrix(-.87854 -3.08576 1.76571 -.50271 16.988 14.294)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="ixwqGWc" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 5.963 9.544)scale(1.98378 2.65712)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="ifxqCVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02196 -1.62554 0 18.749 11.957)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iv075uc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29213 -.37645 .51828 -.4022 18.462 12.062)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iaig08b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02196 -1.62555 0 13.251 11.957)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="itj3QWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00974 -.62233 .74807 -.01171 12.891 12.233)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUKCa4d" cx="0" cy="0" r="1" gradientTransform="rotate(54.19 -.48 10.722)scale(4.16551 8.27687)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="i8SDmRd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36476 3.12473 -2.4506 -1.8546 12.58 5.134)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iRaTQSb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.346 7.15)scale(6.13805 8.72806)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iI4qdjc" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 7.842 9.365)scale(4.18158 7.46424)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iSYvCHd" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 12.074 .36)scale(9.08251 8.13015)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iJD9oab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.562 30.436)" gradientUnits="userSpaceOnUse"><stop class="gfj1348zm"/><stop offset=".714" class="vqiy7zq_f"/></radialGradient><radialGradient id="ioGfCsb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.47)" gradientUnits="userSpaceOnUse"><stop class="uatqp3rks"/><stop offset="1" class="oln0s8bds"/></radialGradient><radialGradient id="iqgXPWH" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.252)" gradientUnits="userSpaceOnUse"><stop class="leds28lfi"/><stop offset="1" class="x0hvtbbrr"/></radialGradient><radialGradient id="icXzeJb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.345 17.274)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="xjoxl1baz"/><stop offset="1" class="xm7oxtb8r"/></radialGradient><radialGradient id="i7RDBCe" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 14.913 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="fupnc-bzv"/><stop offset="1" class="h4nid6imp"/></radialGradient><radialGradient id="ih3094d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 2.06252 -1.29855 -3.22666 31 24.235)" gradientUnits="userSpaceOnUse"><stop class="qomb6ec0x"/><stop offset="1" class="ha79_8bui"/></radialGradient><radialGradient id="igi1Cxd" cx="0" cy="0" r="1" gradientTransform="rotate(116.107 1.598 13.3)scale(4.96085 7.77144)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="vxxihotpt"/><stop offset="1" class="amuq4_bzy"/></radialGradient><radialGradient id="ivvJGYb" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.5 -3.058)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="fjifp0bsg"/><stop offset="1" class="wn5ytjbyn"/></radialGradient><radialGradient id="iR3T2Nc" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3 .29081 .6725 18.155 24.515)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="zlawngbku"/><stop offset="1" class="oc_o5xbok"/></radialGradient><radialGradient id="iZZ4QUi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.405 17.843)" gradientUnits="userSpaceOnUse"><stop class="y0cud7bhd"/><stop offset="1" class="irfgqiu-v"/></radialGradient><radialGradient id="i6AnLvp" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.908)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y0d2ypbdf"/><stop offset="1" class="tmdmcl4vt"/></radialGradient><radialGradient id="igr3QGd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.494)" gradientUnits="userSpaceOnUse"><stop class="aa7vwbb4q"/><stop offset=".615" class="b51u270in"/></radialGradient><radialGradient id="iQMnohL" cx="0" cy="0" r="1" gradientTransform="rotate(25.705 -37.136 15.8)scale(1.9602 2.66792)" gradientUnits="userSpaceOnUse"><stop class="s6hgzbzaq"/><stop offset=".697" class="tqvfhbbxd"/></radialGradient><radialGradient id="ixhWWFv" cx="0" cy="0" r="1" gradientTransform="matrix(-.8664 .26697 -.4987 -1.61843 4.819 17.232)" gradientUnits="userSpaceOnUse"><stop class="luld7ndnd"/><stop offset="1" class="dsgye7-db"/></radialGradient><radialGradient id="i4q9jKj" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.296 6.369)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ps47ry3bo"/><stop offset="1" class="y_wsbk4sp"/></radialGradient><radialGradient id="iUMdaDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.162 13.251)" gradientUnits="userSpaceOnUse"><stop class="l94zn1bjc"/><stop offset="1" class="wncwu8b0a"/></radialGradient><radialGradient id="icYA7cc" cx="0" cy="0" r="1" gradientTransform="matrix(2.96386 -2.56198 2.74355 3.17391 24.182 21.102)" gradientUnits="userSpaceOnUse"><stop class="idon908fh"/><stop offset="1" class="f2po-obrk"/></radialGradient><radialGradient id="id5VUQd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.313)" gradientUnits="userSpaceOnUse"><stop class="f5tmiabas"/><stop offset="1" class="uo2he_6_t"/></radialGradient><radialGradient id="ickCN2V" cx="0" cy="0" r="1" gradientTransform="matrix(1.00475 -.26214 .85754 3.28688 4.382 18.218)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="x5w5cvbwy"/><stop offset="1" class="ug66v3bff"/></radialGradient><filter id="iX0wQ9d" width="19.167" height="19.667" x="6.541" y="1.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="is0y5Ee" width="4.204" height="4.304" x="8.071" y="10.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="iG4THvJ" width="4.054" height="4.304" x="20.054" y="10.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="iH0aSNb" width="3.706" height="3.706" x="20.228" y="10.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".25"/></filter><filter id="id4iOmd" width="3.506" height="3.506" x="8.369" y="10.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".2"/></filter><filter id="iqtWRme" width="12.837" height="14.101" x="9.582" y="6.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="iUPj2ld" width="3.365" height="4.378" x="14.113" y="11.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".25"/></filter><filter id="ibaadKb" width="2.865" height="3.878" x="14.568" y="11.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".125"/></filter><filter id="iP4ZCob" width="3.729" height="1.619" x="17.239" y="10.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="iA4hkCe" width="3.729" height="1.619" x="11.033" y="10.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="iobktPe" width=".939" height=".825" x="17.85" y="11.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".05"/></filter><filter id="iEgMpgd" width="1.019" height="1.047" x="18.934" y="11.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".1"/></filter><filter id="iGD9poe" width="1.139" height="1.206" x="13.337" y="11.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".1"/></filter><filter id="iNyrrbe" width="1.098" height=".835" x="12.361" y="11.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".05"/></filter><filter id="iWPonWr" width="5.641" height="6.853" x="7.995" y="3.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".375"/></filter><filter id="imbrk1d" width="12.099" height="8.151" x="11.386" y="2.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".375"/></filter><filter id="igQpjdb" width="1.286" height="2.754" x="12.058" y="4.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".1"/></filter><filter id="iGFUldB" width="2.984" height="1.44" x="11.376" y="9.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.254902 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="iYtLnFT" width="2.984" height="1.44" x="17.939" y="9.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.254902 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="i47HVYW" width="2.617" height="1.134" x="11.536" y="9.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".1"/></filter><filter id="ivTggOe" width="2.781" height="1.17" x="17.946" y="9.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".1"/></filter><filter id="i6QaOzd" width="7.3" height="8.016" x="2" y="12.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24804"/></filter><filter id="if2CMCe" width="5.538" height="5.423" x="24.197" y="13.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24804" stdDeviation=".2"/></filter><linearGradient id="ifPUErb" x1="21.912" x2="13.34" y1="3.951" y2="19.828" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="ioihRxd" x1="16" x2="16" y1="21.349" y2="19.575" gradientUnits="userSpaceOnUse"><stop class="hqpka7yim"/><stop offset="1" class="jj4p15bbx"/></linearGradient><linearGradient id="ikRfkbc" x1="8.071" x2="11.799" y1="12.819" y2="12.819" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="i9uXmbc" x1="14.682" x2="15.758" y1="14.316" y2="14.448" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iVOqGad" x1="16" x2="16" y1="15.392" y2="14.624" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="i8nNuOb" x1="16.099" x2="16.099" y1="15.359" y2="15.184" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="i7OuFlB" x1="19.729" x2="19.333" y1="12.025" y2="12.268" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iK079Cd" x1="14.188" x2="13.793" y1="12.025" y2="12.268" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKcHNNb" x1="12.358" x2="13.044" y1="4.901" y2="6.506" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="i7tPZsc" x1="9.156" x2="10.486" y1="18.533" y2="19.157" gradientUnits="userSpaceOnUse"><stop class="x0-05wb5o"/><stop offset="1" class="b_wdx7bxu"/></linearGradient><linearGradient id="iMTmOGc" x1="17.482" x2="17.906" y1="26.739" y2="25.783" gradientUnits="userSpaceOnUse"><stop class="jbvrfolcv"/><stop offset=".46" class="byl3sfbil"/></linearGradient><linearGradient id="inVUPuG" x1="24.108" x2="23.968" y1="18.344" y2="18.41" gradientUnits="userSpaceOnUse"><stop class="zb0hqnb-l"/><stop offset="1" class="sqzs4ozft"/></linearGradient><linearGradient id="iwP8L1c" x1="14.945" x2="14.231" y1="27.177" y2="25.57" gradientUnits="userSpaceOnUse"><stop class="na3bqccxs"/><stop offset="1" class="tndlebqua"/></linearGradient><linearGradient id="iomHb0y" x1="22.968" x2="21.812" y1="18.703" y2="19.266" gradientUnits="userSpaceOnUse"><stop class="fp2c12bya"/><stop offset="1" class="xyqac8gqa"/></linearGradient><linearGradient id="icZhhSc" x1="3.231" x2="6.517" y1="28.32" y2="26.713" gradientUnits="userSpaceOnUse"><stop class="m_3r9vbdq"/><stop offset="1" class="iioqnhb4d"/></linearGradient><linearGradient id="iYQ3t0k" x1="27.52" x2="26.84" y1="19.689" y2="18.127" gradientUnits="userSpaceOnUse"><stop class="wvesq7bsq"/><stop offset="1" class="rgj_ccorv"/></linearGradient><linearGradient id="i9iwhQb" x1="26.75" x2="27.494" y1="17.424" y2="18.183" gradientUnits="userSpaceOnUse"><stop offset=".353" class="s1zw3qoay"/><stop offset="1" class="sg0r51lje"/></linearGradient><linearGradient id="issm3wd" x1="25.489" x2="25.997" y1="14.315" y2="15.215" gradientUnits="userSpaceOnUse"><stop class="v9kdkd3dw"/><stop offset="1" class="izl0csmmw"/></linearGradient><linearGradient id="iVL8rGe" x1="8" x2="5.5" y1="15.783" y2="19.549" gradientUnits="userSpaceOnUse"><stop offset=".206" class="wm1rnnuue"/><stop offset="1" class="zcorn7o9q"/></linearGradient><linearGradient id="i35v49b" x1="29.217" x2="24.074" y1="14.879" y2="17.747" gradientUnits="userSpaceOnUse"><stop class="wyj2c0peu"/><stop offset="1" class="tx-xnn8qh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-no-medium-light" /></template>
<style>
.aa7vwbb4q {
  stop-color: var(--svg-color--edbfa2, #EDBFA2);
}

.aakerk86q {
  fill: var(--svg-color--000, #000);
  d: path("M13.893 12.48a.64.64 0 0 0-.644-.644a.64.64 0 0 0-.572.94h1.14a.64.64 0 0 0 .076-.296");
}

.amuq4_bzy {
  stop-color: var(--svg-color--9771d7, #9771D7);
  stop-opacity: 0;
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.b_wdx7bxu {
  stop-color: var(--svg-color--62429a, #62429A);
  stop-opacity: 0;
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b4ne_pb_z {
  d: path("M7.246 19.806a.885.885 0 0 0-.351-1.203l-2.553-1.397a.899.899 0 1 0-.855 1.58l2.565 1.374a.885.885 0 0 0 1.194-.354");
}

.b51u270in {
  stop-color: var(--svg-color--dead8c, #DEAD8C);
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.byl3sfbil {
  stop-color: var(--svg-color--684c9e, #684C9E);
  stop-opacity: 0;
}

.c_g0zlbky {
  d: path("M20.44 16.132L5.033 23.304a3.53 3.53 0 0 0-1.7 4.691A3.516 3.516 0 0 0 8.011 29.7l15.407-7.183c.503-.232.724-.837.483-1.341l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.ck2zm2jih {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.439 11.992c.334-.588.842-1.052 1.936-1.052c.48 0 .941.133 1.352.464c.338.274.293.624.03.755l-.7.4c-.82-.265-1.729-.301-2.618-.567");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.d8h7ar12o {
  d: path("M18.751 11.356a1.124 1.124 0 0 1 1.083 1.42h-2.171a1.13 1.13 0 0 1 1.088-1.42");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.dbbkm8r5g {
  fill: var(--svg-color--99622f, #99622F);
  d: path("M20.711 10.217a.35.35 0 0 0-.25-.426l-2.086-.542a.349.349 0 0 0-.175.675l2.086.542a.35.35 0 0 0 .425-.249");
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dsgye7-db {
  stop-color: var(--svg-color--bb7753, #BB7753);
  stop-opacity: 0;
}

.duuxb9bip {
  stroke: var(--svg-color--99643b, #99643B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 10.037l2.017-.534");
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eq_fjabcu {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.506 12.429l-.862 2.14a.68.68 0 0 0 .656.882h.99a.68.68 0 0 0 .657-.881l-.67-2.142c-.143-.474-.621-.474-.772 0");
}

.f2po-obrk {
  stop-color: var(--svg-color--cb7c77, #CB7C77);
  stop-opacity: 0;
}

.f5tmiabas {
  stop-color: var(--svg-color--eebca0, #EEBCA0);
}

.f93ezcbos {
  cx: 12.91px;
  cy: 11.836px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.491px;
  ry: 0.248px;
}

.fjifp0bsg {
  stop-color: var(--svg-color--745b8c, #745B8C);
}

.fp2c12bya {
  stop-color: var(--svg-color--a680df, #A680DF);
}

.ft5dv1b6b {
  fill: none;
}

.fupnc-bzv {
  stop-color: var(--svg-color--8066bd, #8066BD);
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g-qc2ggws {
  d: path("M26.691 15.656c.527-.846 1.795-1.665 2.462-1.988a.13.13 0 0 1 .153.034a.132.132 0 0 1-.034.197c-2.06 1.272-1.875 1.784-2.645 3.097c-.354.604-1.176 1.112-1.556 1.283l-.474-.898c.53-.281 1.463-.712 2.094-1.725");
}

.g148pmbqn {
  d: path("M18.668 11.594c.08.107-.087.238-.277.38s-.332.242-.412.135s.01-.31.2-.451c.19-.143.41-.171.49-.064");
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gayqowq-c {
  d: path("M10.122 14.062a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.gfj1348zm {
  stop-color: var(--svg-color--6547af, #6547AF);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.h2_5b9b-m {
  d: path("M22.08 14.062a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.h4nid6imp {
  stop-color: var(--svg-color--593b97, #593B97);
}

.ha79_8bui {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
  stop-opacity: 0;
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hiw8w_whp {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
}

.hqpka7yim {
  stop-color: var(--svg-color--d08d9c, #D08D9C);
}

.hsx7mfqqi {
  d: path("m9 16.103l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hyx6dcc2k {
  d: path("m9.595 10.784l-.013-.385c.025-1.195.723-1.658 1.02-1.812l.065-.026l.064-.026A2.9 2.9 0 0 0 12.23 6.98l.103-.244a.332.332 0 0 1 .581-.064a4.87 4.87 0 0 0 4.018 2.108h4.056c.226 0 1.363.11 1.43 1.678l-.15 3.87c-.155 3.53-2.911 5.901-6.276 5.901s-6.122-2.37-6.277-5.9z");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.idon908fh {
  stop-color: var(--svg-color--cb7c77, #CB7C77);
}

.iioqnhb4d {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0;
}

.irfgqiu-v {
  stop-color: var(--svg-color--58448e, #58448E);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.izl0csmmw {
  stop-color: var(--svg-color--c6916f, #C6916F);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.ja6b6i3wf {
  d: path("M10.098 14.736a2.027 2.027 0 1 0 0-4.054a2.027 2.027 0 0 0 0 4.054");
}

.jbvrfolcv {
  stop-color: var(--svg-color--684c9e, #684C9E);
}

.jdp51105x {
  d: path("M9.592 11.119h.015l-.012-.335l-.013-.385c.025-1.195.723-1.658 1.02-1.812l.065-.026l.064-.026A2.9 2.9 0 0 0 12.23 6.98l.103-.244a.332.332 0 0 1 .581-.064a4.87 4.87 0 0 0 4.018 2.108h4.056c.226 0 1.363.11 1.43 1.678l-.15 3.87c-.155 3.53-2.911 5.901-6.276 5.901s-6.122-2.37-6.277-5.9z");
}

.ji-5-2wkk {
  d: path("M13.249 11.356a1.124 1.124 0 0 0-1.084 1.42h2.172q.04-.144.041-.296a1.13 1.13 0 0 0-1.13-1.124");
}

.jj4p15bbx {
  stop-color: var(--svg-color--d08d9c, #D08D9C);
  stop-opacity: 0;
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.keyognb9o {
  stop-color: var(--svg-color--a77367, #A77367);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.l32lfm6cu {
  d: path("m15.519 12.254l-.67 2.142a.68.68 0 0 0 .656.88h.99a.68.68 0 0 0 .656-.88l-.67-2.142c-.143-.474-.812-.474-.963 0");
}

.l94zn1bjc {
  stop-color: var(--svg-color--f2c4a6, #F2C4A6);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.ldoae_5ma {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M10.122 14.062a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.leds28lfi {
  stop-color: var(--svg-color--785e96, #785E96);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lrlfk0bvq {
  stop-color: var(--svg-color--a77367, #A77367);
  stop-opacity: 0;
}

.luld7ndnd {
  stop-color: var(--svg-color--bb7753, #BB7753);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.m_3r9vbdq {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0.939;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me1f_zg8u {
  d: path("m23 16.103l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.mxqn-tmeq {
  d: path("M14.276 12.348c0-.363-.296-.605-.375-.678l-.364.35l.224.456z");
}

.na3bqccxs {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nnikzcbjy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.358 4.469c.03.306.296 1.456.686 2.153");
}

.o-3y3l8ww {
  d: path("m6.81 20.603l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.oc_o5xbok {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oln0s8bds {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
  stop-opacity: 0;
}

.on_mu-bbf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.668 11.594c.08.107-.087.238-.277.38s-.332.242-.412.135s.01-.31.2-.451c.19-.143.41-.171.49-.064");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pcjcfdcqg {
  d: path("M22.08 14.736a2.027 2.027 0 1 0 0-4.054a2.027 2.027 0 0 0 0 4.054");
}

.pj__wrb2a {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.ps47ry3bo {
  stop-color: var(--svg-color--e6b396, #E6B396);
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qomb6ec0x {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
}

.qsrvd3bbo {
  fill: var(--svg-color--99622f, #99622F);
  d: path("M11.388 10.217a.35.35 0 0 1 .25-.426l2.086-.542a.349.349 0 0 1 .175.675l-2.086.542a.35.35 0 0 1-.425-.249");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r594lytyn {
  fill-rule: evenodd;
  d: path("M25.05 14.485c.268-.548.409-1.16.409-1.798c0-.588-.121-1.14-.339-1.644h.007a4 4 0 0 0-.354-.646l-.003-.004a4.1 4.1 0 0 1-.663-2.231V8.15a4.156 4.156 0 0 0-4.155-4.155a.68.68 0 0 1-.574-.294A4.16 4.16 0 0 0 16 1.967c-1.39 0-2.626.688-3.378 1.733a.71.71 0 0 1-.574.294l-.107.001a4.156 4.156 0 0 0-4.049 4.154v.013a4.1 4.1 0 0 1-.662 2.23l-.003.006a4.16 4.16 0 0 0-.278 4.087c.09.178.09.395 0 .573a4.1 4.1 0 0 0-.408 1.772a4.05 4.05 0 0 0 4.054 4.054h10.81a4.05 4.05 0 0 0 4.054-4.054a4.1 4.1 0 0 0-.408-1.772a.65.65 0 0 1 0-.573M9.608 11.119h-.015l1.51 2.967c.155 3.53 1.533 0 4.898 0s4.832 3.929 4.988.399l1.43-4.027c-.067-1.568-1.204-1.678-1.43-1.678h-4.056a4.87 4.87 0 0 1-4.018-2.108a.332.332 0 0 0-.581.064l-.103.244a2.9 2.9 0 0 1-1.563 1.581q-.035.016-.065.026c-.297.154-.995.617-1.02 1.812l.013.385z");
}

.r6yp65b6h {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.012 11.014a1.76 1.76 0 0 1 1.706 1.333a.345.345 0 0 1-.337.43h-2.81a.29.29 0 0 1-.286-.343a1.76 1.76 0 0 1 1.727-1.42");
}

.rgj_ccorv {
  stop-color: var(--svg-color--ca8684, #CA8684);
  stop-opacity: 0;
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rnuj69bls {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M22.08 14.062a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.runybrbtv {
  fill: var(--svg-color--000, #000);
  d: path("M18.107 12.48c0-.357.286-.644.644-.644a.64.64 0 0 1 .572.94h-1.14a.6.6 0 0 1-.076-.296");
}

.s1zw3qoay {
  stop-color: var(--svg-color--d0976d, #D0976D);
}

.s6hgzbzaq {
  stop-color: var(--svg-color--c68c71, #C68C71);
}

.sg0r51lje {
  stop-color: var(--svg-color--d0976d, #D0976D);
  stop-opacity: 0;
}

.spt1f3y0o {
  d: path("m25.19 20.603l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sqzs4ozft {
  stop-color: var(--svg-color--8071aa, #8071AA);
  stop-opacity: 0;
}

.su64_3bwn {
  stroke: var(--svg-color--99643b, #99643B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.428 10.073l-2.182-.57");
}

.sz9l9lc9u {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M15.989 19.484c.791 0 1.433-.689 1.433-1.538s-.642-1.538-1.433-1.538s-1.433.689-1.433 1.538s.642 1.538 1.433 1.538");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t77o7ob_c {
  d: path("M19.752 12.332a1.06 1.06 0 0 0-.291-.583l-.327.36l.147.287z");
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tmdmcl4vt {
  stop-color: var(--svg-color--69569a, #69569A);
}

.tndlebqua {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
  stop-opacity: 0;
}

.tqvfhbbxd {
  stop-color: var(--svg-color--bd756f, #BD756F);
}

.tx-xnn8qh {
  stop-color: var(--svg-color--f1c2a5, #F1C2A5);
  stop-opacity: 0;
}

.uatqp3rks {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ug66v3bff {
  stop-color: var(--svg-color--d59883, #D59883);
  stop-opacity: 0;
}

.ulx55wb6s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.988 11.014a1.76 1.76 0 0 0-1.707 1.333c-.056.22.113.43.338.43h2.81a.29.29 0 0 0 .286-.343a1.765 1.765 0 0 0-1.727-1.42");
}

.uo2he_6_t {
  stop-color: var(--svg-color--eebca0, #EEBCA0);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.uza0nib2y {
  d: path("m11.56 16.132l15.407 7.177a3.53 3.53 0 0 1 1.7 4.688a3.52 3.52 0 0 1-4.679 1.703L8.581 22.513a1 1 0 0 1-.483-1.341l2.123-4.567a1.004 1.004 0 0 1 1.339-.473");
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v5ovupb9l {
  d: path("M15.24 2.896c-1.427-.315-2.956 1.203-3.104 1.731c1.943 4.56 4.926 4.126 8.235 3.758c1.98-.22 2.195.683 2.364 1.12c-.549-5.11-4.244-5.891-7.495-6.61");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9kdkd3dw {
  stop-color: var(--svg-color--c6916f, #C6916F);
}

.v9q6brb3d {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.519 12.254l-.67 2.142a.68.68 0 0 0 .656.88h.99a.68.68 0 0 0 .656-.88l-.67-2.142c-.143-.474-.812-.474-.963 0");
}

.vqiy7zq_f {
  stop-color: var(--svg-color--53329c, #53329C);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vxxihotpt {
  stop-color: var(--svg-color--9771d7, #9771D7);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wm1rnnuue {
  stop-color: var(--svg-color--f1bf99, #F1BF99);
}

.wn5ytjbyn {
  stop-color: var(--svg-color--745b8c, #745B8C);
  stop-opacity: 0;
}

.wncwu8b0a {
  stop-color: var(--svg-color--f2c4a6, #F2C4A6);
  stop-opacity: 0;
}

.wvesq7bsq {
  stop-color: var(--svg-color--ca8684, #CA8684);
}

.wyj2c0peu {
  stop-color: var(--svg-color--f1c2a5, #F1C2A5);
}

.x0-05wb5o {
  stop-color: var(--svg-color--62429a, #62429A);
}

.x0hvtbbrr {
  stop-color: var(--svg-color--785e96, #785E96);
  stop-opacity: 0;
}

.x1ls_mb4u {
  d: path("M24.75 19.837a.885.885 0 0 1 .35-1.204l2.609-1.427a.899.899 0 1 1 .856 1.58l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.x5w5cvbwy {
  stop-color: var(--svg-color--d59883, #D59883);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjoxl1baz {
  stop-color: var(--svg-color--76679f, #76679F);
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xm7oxtb8r {
  stop-color: var(--svg-color--433169, #433169);
}

.xqi3rzbvq {
  cx: 12.91px;
  cy: 11.836px;
  rx: 0.491px;
  ry: 0.248px;
}

.xyqac8gqa {
  stop-color: var(--svg-color--a680df, #A680DF);
  stop-opacity: 0;
}

.y_wsbk4sp {
  stop-color: var(--svg-color--daa884, #DAA884);
}

.y0cud7bhd {
  stop-color: var(--svg-color--705f9f, #705F9F);
}

.y0d2ypbdf {
  stop-color: var(--svg-color--8b64ce, #8B64CE);
}

.y57xohvpz {
  d: path("M25.5 30.033h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ykvy-obdh {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.562 11.992c-.335-.588-.843-1.052-1.937-1.052c-.479 0-.94.133-1.351.464c-.339.274-.294.624-.031.755l.7.4c.821-.265 1.73-.301 2.619-.567");
}

.yn9dvdegj {
  d: path("M9.835 5.134c.782-.697 1.91-.704 2.544-.591l.507 1.625c-.324-.049-.612.064-.855.296c-.57 2.111-2.724 1.794-3.146 3.378c-.19-1.88-.401-3.505.95-4.708");
}

.zb0hqnb-l {
  stop-color: var(--svg-color--8071aa, #8071AA);
}

.zcorn7o9q {
  stop-color: var(--svg-color--d1927f, #D1927F);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zlawngbku {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
