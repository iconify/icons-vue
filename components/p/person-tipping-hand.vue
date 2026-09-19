<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iD8okAb)" class="zm858vb9z"/><path fill="url(#itijl7b)" class="zm858vb9z"/><path fill="url(#ivGkfLx)" class="zm858vb9z"/><rect fill="url(#iu1nLEE)" class="pogdb8bsm"/><path class="uw5u5tb9a"/><path fill="url(#iAq2PDi)" class="wdc-rnbqv"/><path fill="url(#i7cA9vb)" class="wdc-rnbqv"/><path clip-rule="evenodd" class="nxaqm6bxm"/><path fill="url(#i6RlgBb)" clip-rule="evenodd" class="dracc7kkp"/><path fill="url(#iuOYw9k)" clip-rule="evenodd" class="dracc7kkp"/><path fill="url(#iNMwWyc)" clip-rule="evenodd" class="dracc7kkp"/><path clip-rule="evenodd" class="z2fht5tro"/><path fill="url(#iIunDLd)" clip-rule="evenodd" class="nfaqvuxyn"/><path fill="url(#iLsHMrb)" clip-rule="evenodd" class="nfaqvuxyn"/><path fill="url(#iwmRX4b)" clip-rule="evenodd" class="nfaqvuxyn"/><path clip-rule="evenodd" class="jp5jo2brz"/><path fill="url(#i67Pq8d)" clip-rule="evenodd" class="a8qq5zq_t"/><path fill="url(#iXbVsbc)" clip-rule="evenodd" class="a8qq5zq_t"/><path fill="url(#iBZg4He)" clip-rule="evenodd" class="a8qq5zq_t"/><g filter="url(#iSNihBc)"><path clip-rule="evenodd" class="mc2e_wm7l"/><path fill="url(#ihEgXFa)" clip-rule="evenodd" class="ef_e2pbms"/><path fill="url(#igReise)" clip-rule="evenodd" class="ef_e2pbms"/><path fill="url(#iIo379d)" clip-rule="evenodd" class="ef_e2pbms"/></g><path fill="url(#iP5C93c)" class="d0rzwy_nb"/><path fill="url(#iXDJuSd)" class="d0rzwy_nb"/><path fill="url(#iwNlhSc)" class="tfzc3rbat"/><path fill="url(#iX437dc)" class="tfzc3rbat"/><path fill="url(#i0CBqye)" class="ytfamwmwg"/><path fill="url(#iVnpySc)" class="ytfamwmwg"/><path fill="url(#iosGx1c)" class="ytfamwmwg"/><path fill="url(#ihE9pKd)" class="q4zvnujip"/><path fill="url(#iW66Cvc)" class="q4zvnujip"/><path fill="url(#ixbeDNc)" class="sam6tzb0f"/><path fill="url(#iYWL6vc)" class="sam6tzb0f"/><g filter="url(#inOyH2b)"><path fill="url(#iBzTtXd)" class="alhjzvm2y"/></g><path fill="url(#iTN7Pid)" class="alhjzvm2y"/><path fill="url(#iEUMLnc)" class="alhjzvm2y"/><path fill="url(#ibLNMZb)" class="alhjzvm2y"/><path fill="url(#i4WCRxe)" class="alhjzvm2y"/><g filter="url(#iE5fwWc)"><path class="e6r63w0de"/></g><g filter="url(#iiRUvuw)"><path fill="url(#i2SzVCd)" class="z6c5w6cyf"/><path fill="url(#iTqpnbc)" class="z6c5w6cyf"/><path fill="url(#iJecJMb)" class="z6c5w6cyf"/><path fill="url(#ilCnURc)" class="z6c5w6cyf"/></g><g filter="url(#iPRTk7T)"><path stroke="url(#iRC2ljD)" class="qpasjissb"/></g><path fill="url(#ipj6GSb)" class="ewzfx45qx"/><g filter="url(#iYymvXb)"><path fill="url(#iUgozyd)" class="sx4x2vbnb"/><path fill="url(#i36u2bc)" class="sx4x2vbnb"/><path fill="url(#ikUBwqc)" class="sx4x2vbnb"/><path fill="url(#iC8kxsb)" class="sx4x2vbnb"/><path fill="url(#i0udmac)" class="sx4x2vbnb"/></g><g filter="url(#i8hSCAe)"><path class="kswhw3son"/></g><g filter="url(#ipLUbQc)"><path class="chjwbpjrq"/></g><g filter="url(#iNzfYge)"><path fill="url(#iLRxW1b)" class="g7wsges1c"/><path fill="url(#iRP26Cb)" class="g7wsges1c"/></g><g filter="url(#ixfFHIT)"><path fill="url(#i6Yk2xd)" class="rxa8i7bqf"/><path fill="url(#iFaZCeb)" class="rxa8i7bqf"/><path fill="url(#iC2CRXb)" class="rxa8i7bqf"/><path fill="url(#ihhO0Tc)" class="rxa8i7bqf"/><path fill="url(#i95mo1I)" class="rxa8i7bqf"/></g><path class="wvw0m4z-y"/><path fill="url(#iuc5UVc)" class="c52xkobmj"/><path class="xb_gabxuq"/><g filter="url(#iqvMq9d)"><path class="esyiu3bdx"/><path fill="url(#imGFSDe)" class="w7zv_4b3n"/></g><g filter="url(#i84I62d)"><path fill="url(#iKYP4sc)" class="ylbet3bat"/></g><path class="gtjuf3b5w"/><path fill="url(#iuKPiMe)" class="hvwxf2b_q"/><path class="rs8x1wbme"/><g filter="url(#iKpDepd)"><path fill="url(#ioQL28b)" class="vn8z_zbqx"/></g><g filter="url(#io2IPGk)"><ellipse transform="rotate(-27.914 9.842 12.103)" class="ydhtf9ruh"/><ellipse fill="url(#iPqUBQi)" transform="rotate(-27.914 9.842 12.103)" class="pzzjtjreo"/></g><path fill="url(#iXmzCrc)" class="tc8_26b9u"/><path fill="url(#ikSsVCe)" class="tc8_26b9u"/><path fill="url(#iWoTLVN)" class="tc8_26b9u"/><path fill="url(#iQjrFCb)" class="oelystb9m"/><path fill="url(#ij91GeA)" class="oelystb9m"/><g filter="url(#iAhwICe)"><path class="sv48nz4ux"/></g><g filter="url(#i9lDlGc)"><path class="f3ntlcsjw"/></g><g filter="url(#izuvKab)"><path class="f6egcur_x"/></g><g filter="url(#ikSp2xd)"><path class="e0cy9f3yq"/></g><defs><radialGradient id="itijl7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.33523 -6.23448 0 12.904 20.036)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="zg4a17b1f"/><stop offset="1" class="c2hsbpb1i"/></radialGradient><radialGradient id="ivGkfLx" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89737 -6.66767 3.24499 -1.89675 21.662 29.476)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="xaavtj_gl"/><stop offset="1" class="ig4trablp"/></radialGradient><radialGradient id="iu1nLEE" cx="0" cy="0" r="1" gradientTransform="matrix(2.81734 3.45124 -5.56183 4.54028 11.778 20.507)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="g8udi_b5x"/><stop offset=".826" class="g_fiqgqzh"/></radialGradient><radialGradient id="iAq2PDi" cx="0" cy="0" r="1" gradientTransform="rotate(131.424 9.173 12.14)scale(2.12546 1.04757)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset="1" class="kruo6kbky"/></radialGradient><radialGradient id="i7cA9vb" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.585 -8.943)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="av00hmb0p"/><stop offset="1" class="amtu30rgy"/></radialGradient><radialGradient id="i6RlgBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.89575 .18 -.22855 -1.1374 30.16 14.163)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iNMwWyc" cx="0" cy="0" r="1" gradientTransform="matrix(.04403 .33209 -2.56302 .33983 27.715 13.64)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iIunDLd" cx="0" cy="0" r="1" gradientTransform="rotate(164.445 14.38 9.336)scale(.78159 1.2098)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iwmRX4b" cx="0" cy="0" r="1" gradientTransform="matrix(.04382 .26178 -2.05938 .3447 28.305 13.965)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="i67Pq8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.89428 .16927 -.20335 -1.07433 30.457 14.935)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iBZg4He" cx="0" cy="0" r="1" gradientTransform="matrix(.0434 .28906 -2.36234 .35465 28.017 14.402)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="ihEgXFa" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 14.104 9.212)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="igReise" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 5.101 23.74)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iXDJuSd" cx="0" cy="0" r="1" gradientTransform="rotate(157.027 11.93 10.07)scale(3.12266 1.85514)" gradientUnits="userSpaceOnUse"><stop class="eksmwwbms"/><stop offset="1" class="jxtp3vx1u"/></radialGradient><radialGradient id="iwNlhSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .95313 -3.31428 0 24.626 17.387)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="buivx-bne"/><stop offset="1" class="v3bk_f4rq"/></radialGradient><radialGradient id="iVnpySc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.75 -3.6875 0 26.189 17.715)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="p69mofo0i"/><stop offset="1" class="x-u3yxwuj"/></radialGradient><radialGradient id="ihE9pKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.97304 3.99792 -4.74923 -1.1559 19.94 14.568)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iW66Cvc" cx="0" cy="0" r="1" gradientTransform="matrix(.37018 .50767 -.43128 .31447 18.999 14.907)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="ixbeDNc" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 -8.673 12.054)scale(3.7469 1.70313)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iYWL6vc" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 -6.68 11.989)scale(1.32122 1.15898)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iBzTtXd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.59763 0 0 -11.6711 16.482 13.38)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iTN7Pid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.27296 16.6223 0 12.694 21.376)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset="1" class="yhtyhvpuw"/></radialGradient><radialGradient id="iEUMLnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.50804 7.70072 -2.8311 -.18678 19.447 13.088)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="ibLNMZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.78431 2.14822 0 10.3 11.89)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="i4WCRxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.9375 2.513 0 16.08 11.371)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iRC2ljD" cx="0" cy="0" r="1" gradientTransform="matrix(.43812 -.78175 2.27492 1.27496 11.517 17.532)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="ipj6GSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.90958 3.65948 0 12.938 17.847)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i36u2bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.21743 12.7879 0 6.339 11.384)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="ikUBwqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58447 8.12277 0 19.073 11.384)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iC8kxsb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1037 -1.56532 .83364 -2.18548 18.121 3.463)" gradientUnits="userSpaceOnUse"><stop class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="i0udmac" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 4.6 11.266)scale(2.18399 5.0571)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iLRxW1b" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 6.343 2.796)scale(5.10755 1.42155)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iRP26Cb" cx="0" cy="0" r="1" gradientTransform="matrix(4.06138 -6.43053 7.12436 4.49959 6.085 9.28)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="i6Yk2xd" cx="0" cy="0" r="1" gradientTransform="matrix(4.27292 1.01063 -.56521 2.3897 17.507 4.738)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iFaZCeb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71157 -4.67413 2.60673 -1.51222 19.412 10.55)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iC2CRXb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 12.21 -.218)scale(3.23216 2.31506)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="ihhO0Tc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 9.223 3.418)scale(6.22753 6.7322)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="i95mo1I" cx="0" cy="0" r="1" gradientTransform="matrix(-.14808 .48427 -2.21403 -.67698 17.296 4.433)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iuc5UVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0239 -1.62862 0 15.692 12.224)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imGFSDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.29269 -.37717 .51926 -.40295 15.405 12.33)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuKPiMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02395 -1.62871 0 10.185 12.224)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iPqUBQi" cx="0" cy="0" r="1" gradientTransform="matrix(-.00976 -.62354 .74952 -.01174 9.823 12.5)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikSsVCe" cx="0" cy="0" r="1" gradientTransform="matrix(.79322 2.83106 -2.70104 .75679 18.766 12.241)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iWoTLVN" cx="0" cy="0" r="1" gradientTransform="matrix(.9942 -1.36437 1.14361 .83333 19.22 12.929)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="ij91GeA" cx="0" cy="0" r="1" gradientTransform="matrix(-.52105 2.61997 -2.57568 -.51224 6.297 12.453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><linearGradient id="iD8okAb" x1="12.904" x2="12.904" y1="30.087" y2="25.061" gradientUnits="userSpaceOnUse"><stop class="zazrfkbck"/><stop offset="1" class="lnx-x012h"/></linearGradient><linearGradient id="iuOYw9k" x1="28.329" x2="28.03" y1="15.71" y2="14.457" gradientUnits="userSpaceOnUse"><stop class="iewh3ibyo"/><stop offset="1" class="dbywulbre"/></linearGradient><linearGradient id="iLsHMrb" x1="28.75" x2="28.624" y1="15.984" y2="14.758" gradientUnits="userSpaceOnUse"><stop offset=".217" class="iewh3ibyo"/><stop offset="1" class="dbywulbre"/></linearGradient><linearGradient id="iXbVsbc" x1="28.463" x2="28.345" y1="16.39" y2="15.207" gradientUnits="userSpaceOnUse"><stop offset=".217" class="iewh3ibyo"/><stop offset="1" class="dbywulbre"/></linearGradient><linearGradient id="iIo379d" x1="25.11" x2="26.704" y1="16.84" y2="16.527" gradientUnits="userSpaceOnUse"><stop offset=".585" class="oc3fsgi2c"/><stop offset="1" class="v-pv693fm"/></linearGradient><linearGradient id="iP5C93c" x1="27.493" x2="27.439" y1="17.004" y2="16.684" gradientUnits="userSpaceOnUse"><stop offset=".101" class="gvo57cbnb"/><stop offset="1" class="wodu9bbyy"/></linearGradient><linearGradient id="iX437dc" x1="24.005" x2="24.005" y1="18.338" y2="18.079" gradientUnits="userSpaceOnUse"><stop offset=".316" class="qpac9rbcm"/><stop offset="1" class="rm84xebof"/></linearGradient><linearGradient id="i0CBqye" x1="24.876" x2="24.876" y1="19.402" y2="38.715" gradientUnits="userSpaceOnUse"><stop class="pvy3eqxuo"/><stop offset=".621" class="l7mlu3-3a"/></linearGradient><linearGradient id="iosGx1c" x1="23.834" x2="23.834" y1="18.243" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".366" class="kyz4h9b7r"/><stop offset="1" class="vsqt-vb2z"/></linearGradient><linearGradient id="i2SzVCd" x1="12.939" x2="14.017" y1="14.426" y2="14.426" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iTqpnbc" x1="11.585" x2="12.94" y1="14.23" y2="14.305" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iJecJMb" x1="12.939" x2="12.939" y1="14.929" y2="16.005" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="ilCnURc" x1="12.939" x2="12.939" y1="12.093" y2="12.622" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iUgozyd" x1="19.707" x2="6.931" y1="6.234" y2="6.234" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iKYP4sc" x1="16.674" x2="16.278" y1="12.292" y2="12.536" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ioQL28b" x1="11.124" x2="10.728" y1="12.292" y2="12.536" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXmzCrc" x1="21.061" x2="19.538" y1="12.326" y2="15.073" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iQjrFCb" x1="5.556" x2="7.396" y1="13.214" y2="13.054" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><filter id="iSNihBc" width="7.879" height="3.847" x="21.78" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.603922 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3786"/></filter><filter id="inOyH2b" width="13.648" height="15.775" x="6.549" y="5.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3786"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3786" result="effect2_innerShadow_4002_3786"/></filter><filter id="iE5fwWc" width="4.369" height="5.66" x="10.492" y="11.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".5"/></filter><filter id="iiRUvuw" width="2.569" height="3.86" x="11.654" y="11.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".05"/></filter><filter id="iPRTk7T" width="4.562" height="1.854" x="10.658" y="16.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".05"/></filter><filter id="iYymvXb" width="16.245" height="10.415" x="4.816" y="1.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3786"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3786" result="effect2_innerShadow_4002_3786"/></filter><filter id="i8hSCAe" width="2.925" height="1.45" x="14.944" y="8.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3786"/></filter><filter id="ipLUbQc" width="2.925" height="1.431" x="8.311" y="8.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3786"/></filter><filter id="iNzfYge" width="8.679" height="7.931" x="5.08" y="2.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".25"/></filter><filter id="ixfFHIT" width="8.461" height="7.674" x="12.49" y="3.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".25"/></filter><filter id="iqvMq9d" width=".941" height=".826" x="14.792" y="11.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".05"/></filter><filter id="i84I62d" width="1.02" height="1.048" x="15.878" y="11.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".1"/></filter><filter id="iKpDepd" width="1.14" height="1.208" x="10.271" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".1"/></filter><filter id="io2IPGk" width="1.1" height=".837" x="9.292" y="11.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".05"/></filter><filter id="iAhwICe" width="1.546" height="2.872" x="5.391" y="11.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".125"/></filter><filter id="i9lDlGc" width="1.695" height="2.902" x="18.95" y="11.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".125"/></filter><filter id="izuvKab" width="2.839" height="1.268" x="8.307" y="8.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".125"/></filter><filter id="ikSp2xd" width="2.839" height="1.268" x="14.969" y="8.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3786" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-tipping-hand" /></template>
<style>
.a8qq5zq_t {
  fill-rule: evenodd;
  d: path("M30.454 15.067a.85.85 0 0 1-.773.921a28 28 0 0 0-1.26.162l-.03.004c-.525.075-1.133.16-1.787.231a.85.85 0 0 1-.182-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
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

.adnp-y-dh {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
  stop-opacity: 0;
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.alhjzvm2y {
  d: path("M6.85 16.87a4.94 4.94 0 0 0 4.903 4.298h2.381a4.94 4.94 0 0 0 4.904-4.298c.149-2.378.299-4.745.409-7.121a1.83 1.83 0 0 0-1.74-1.808H15.94a3.06 3.06 0 0 1-2.791-1.82a.84.84 0 0 0-.777-.528h-1.606c-2.33 0-4.217 1.909-4.217 4.264c0 2.348.146 4.659.3 7.013");
}

.amtu30rgy {
  stop-color: var(--svg-color--eab23a, #EAB23A);
}

.av00hmb0p {
  stop-color: var(--svg-color--eab23a, #EAB23A);
  stop-opacity: 0;
}

.ax8207b9e {
  stop-color: var(--svg-color--e4b833, #E4B833);
  stop-opacity: 0;
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.buivx-bne {
  stop-color: var(--svg-color--ff7849, #FF7849);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c2hsbpb1i {
  stop-color: var(--svg-color--c95513, #C95513);
  stop-opacity: 0;
}

.c52xkobmj {
  d: path("M15.695 11.622a1.126 1.126 0 0 1 1.085 1.423h-2.176a1.13 1.13 0 0 1 1.09-1.423");
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.chjwbpjrq {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M8.634 9.482a3.5 3.5 0 0 1 2.195-.454a.35.35 0 1 1-.086.696a2.8 2.8 0 0 0-1.75.359a2 2 0 0 0-.115.075l-.004.003a.35.35 0 0 1-.428-.553z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.d0rzwy_nb {
  d: path("M26.092 14.017c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.873-.095 1.181-.192c.243-.077.5-.219.96-.306c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.492.05");
}

.dbywulbre {
  stop-color: var(--svg-color--ffcb38, #FFCB38);
  stop-opacity: 0;
}

.dracc7kkp {
  fill-rule: evenodd;
  d: path("M30.147 14.181a.85.85 0 0 1-.69.985c-.147.026-.337.066-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.715-.142a.85.85 0 0 1 .985.69");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e0cy9f3yq {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.433 9.777c-.325-.233-1.133-.642-2.09-.481");
}

.e6r63w0de {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m12.325 12.726l-.801 2.32c-.137.477.191.954.657.954h.992c.466 0 .794-.485.657-.954l-.67-2.32c-.144-.514-.684-.514-.835 0");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.ef_e2pbms {
  fill-rule: evenodd;
  d: path("M26.091 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.866-.153 1.174-.25c.243-.077.508-.16.967-.248c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.493.05");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.eksmwwbms {
  stop-color: var(--svg-color--ffd836, #FFD836);
}

.esyiu3bdx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.612 11.86c.08.107-.087.238-.278.38c-.19.143-.332.244-.413.136s.01-.31.2-.452c.191-.143.41-.171.491-.064");
}

.ewzfx45qx {
  d: path("M12.939 17.036a3.8 3.8 0 0 1-1.749-.415c-.173-.087-.359.107-.25.264a2.39 2.39 0 0 0 1.999 1.068a2.39 2.39 0 0 0 1.998-1.068c.109-.163-.077-.352-.25-.264a3.8 3.8 0 0 1-1.748.415");
}

.f3ntlcsjw {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M19.2 14.251q.075-1.2.14-2.402a1.206 1.206 0 0 1-.14 2.402");
}

.f6egcur_x {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M8.682 9.835c.324-.232 1.132-.642 2.088-.48");
}

.ft5dv1b6b {
  fill: none;
}

.g_fiqgqzh {
  stop-color: var(--svg-color--ffb628, #FFB628);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g7wsges1c {
  d: path("M13.232 6.293a3 3 0 0 1-.083-.172a.84.84 0 0 0-.777-.528h-1.606c-2.33 0-4.217 1.909-4.217 4.264v.347c-.43-.326-.969-1.015-.969-2.13c0-1.352.987-2.036 1.616-2.472a3 3 0 0 0 .417-.32l.126-.132c.441-.468 1.227-1.302 2.6-1.666a7 7 0 0 1 2.114-.2c.473.025.806.433.806.906v2.086z");
}

.g8udi_b5x {
  stop-color: var(--svg-color--dd7d2c, #DD7D2C);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gtjuf3b5w {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.921 11.279c-.824 0-1.52.568-1.71 1.336c-.056.22.113.43.338.43h2.816a.29.29 0 0 0 .287-.343a1.77 1.77 0 0 0-1.73-1.423");
}

.gvo57cbnb {
  stop-color: var(--svg-color--e38654, #E38654);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hvwxf2b_q {
  d: path("M10.182 11.622a1.126 1.126 0 0 0-1.085 1.423h2.176q.039-.144.04-.297a1.134 1.134 0 0 0-1.13-1.126");
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

.id09adcid {
  stop-color: var(--svg-color--ffe047, #FFE047);
}

.iewh3ibyo {
  stop-color: var(--svg-color--e48851, #E48851);
}

.ig4trablp {
  stop-color: var(--svg-color--bb2c0d, #BB2C0D);
  stop-opacity: 0;
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.jp5jo2brz {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M30.454 15.067a.85.85 0 0 1-.773.921a28 28 0 0 0-1.26.162l-.03.004c-.525.075-1.133.16-1.787.231a.85.85 0 0 1-.182-1.69c.622-.067 1.205-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jxtp3vx1u {
  stop-color: var(--svg-color--ffd836, #FFD836);
  stop-opacity: 0;
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

.kruo6kbky {
  stop-color: var(--svg-color--fab91d, #FAB91D);
}

.kswhw3son {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M17.65 9.62c-.221-.193-.479-.397-.868-.52c-.384-.12-.865-.153-1.53-.071a.35.35 0 0 0 .085.695c.607-.075.979-.036 1.235.044c.25.08.42.207.618.38a.35.35 0 0 0 .46-.528");
}

.kyz4h9b7r {
  stop-color: var(--svg-color--ff9c1d, #FF9C1D);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l7mlu3-3a {
  stop-color: var(--svg-color--ea6033, #EA6033);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnx-x012h {
  stop-color: var(--svg-color--ff732c, #FF732C);
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc2e_wm7l {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M26.091 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.866-.153 1.174-.25c.243-.077.508-.16.967-.248c.917-.102 1.759-.206 2.235-.308a.825.825 0 0 0-.346-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.493.05");
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nfaqvuxyn {
  fill-rule: evenodd;
  d: path("M30.725 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693a27 27 0 0 0 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nxaqm6bxm {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M30.147 14.181a.85.85 0 0 1-.69.985c-.147.026-.337.066-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.083.715-.142a.85.85 0 0 1 .985.69");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.oc3fsgi2c {
  stop-color: var(--svg-color--ffca38, #FFCA38);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oelystb9m {
  d: path("M6.56 11.035a2.031 2.031 0 0 0 .175 4.038a98 98 0 0 1-.175-4.038");
}

.p69mofo0i {
  stop-color: var(--svg-color--ff9f3b, #FF9F3B);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pogdb8bsm {
  width: 4.898px;
  height: 6.68px;
  x: 10.466px;
  y: 17.009px;
  rx: 2.449px;
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.pvy3eqxuo {
  stop-color: var(--svg-color--ff872c, #FF872C);
}

.pzzjtjreo {
  cx: 9.842px;
  cy: 12.103px;
  rx: 0.492px;
  ry: 0.249px;
}

.q4zvnujip {
  d: path("M19.074 14.958a2.07 2.07 0 0 0 1.141-.39v1.175a2.74 2.74 0 0 1-1.692 2.548q.325-.687.436-1.489z");
}

.qpac9rbcm {
  stop-color: var(--svg-color--f05918, #F05918);
}

.qpasjissb {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.225 16.555a3.7 3.7 0 0 0 1.713.406c.636 0 1.22-.148 1.714-.406h.001a.27.27 0 0 1 .319.052a.25.25 0 0 1 .027.32l-.062-.042a2.39 2.39 0 0 1-1.998 1.068a2.39 2.39 0 0 1-1.999-1.068zm0 0a.27.27 0 0 0-.32.055a.25.25 0 0 0-.027.317z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rm84xebof {
  stop-color: var(--svg-color--f05918, #F05918);
  stop-opacity: 0;
}

.rs8x1wbme {
  fill: var(--svg-color--000, #000);
  d: path("M10.827 12.748a.64.64 0 0 0-.645-.645a.642.642 0 0 0-.573.942h1.142a.64.64 0 0 0 .076-.297");
}

.rtamvw1ka {
  stop-color: var(--svg-color--e4b833, #E4B833);
}

.rxa8i7bqf {
  d: path("m19.517 10.55l-.037-.797c-.013-.964-.81-1.759-1.773-1.8H15.94a3.06 3.06 0 0 1-2.68-1.59s-.153-.352-.25-.912c-.17-.989.746-1.717 1.736-1.553c1.324.22 2.95.65 4.114 1.408c2.201 1.436 1.816 4.024.657 5.243");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.sam6tzb0f {
  d: path("M6.803 14.958a2.07 2.07 0 0 1-1.141-.39v1.175a2.74 2.74 0 0 0 1.692 2.548a5.2 5.2 0 0 1-.436-1.489z");
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.sv48nz4ux {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M6.582 11.869a1.206 1.206 0 0 0 .105 2.372q-.067-1.186-.105-2.372");
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.sx4x2vbnb {
  d: path("M19.066 4.997a2.93 2.93 0 0 1 1.6 1.327a2.99 2.99 0 0 1-.135 3.188c-.22.325-.341.71-.341 1.103v1.5a2.2 2.2 0 0 0-.842-.339l.099-2.027a1.83 1.83 0 0 0-1.74-1.807H15.94a3.06 3.06 0 0 1-2.791-1.821a.84.84 0 0 0-.777-.528h-1.606c-2.33 0-4.217 1.909-4.217 4.264l.038 1.94c-.32.047-.655.154-.908.333v-1.515c0-.392-.12-.778-.342-1.103a3.02 3.02 0 0 1-.18-3.087a2.96 2.96 0 0 1 1.64-1.421a3.4 3.4 0 0 0 1.746-1.401a2.935 2.935 0 0 1 3.648-1.151a1.88 1.88 0 0 0 1.506 0a3 3 0 0 1 1.152-.237c1.064 0 1.994.575 2.51 1.428c.388.643.997 1.11 1.706 1.354");
}

.tc8_26b9u {
  d: path("M19.15 15.073q.126-2.015.233-4.028a2.031 2.031 0 0 1-.233 4.028");
}

.tfzc3rbat {
  d: path("M21.537 17.548a.25.25 0 0 1 .25-.25h4.094a.25.25 0 0 1 .25.25v1.64h-4.594z");
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uw5u5tb9a {
  fill: var(--svg-color--f1a31e, #F1A31E);
  d: path("M21.78 15.789h4.015v2.016H21.78z");
}

.v-pv693fm {
  stop-color: var(--svg-color--ffca38, #FFCA38);
  stop-opacity: 0;
}

.v3bk_f4rq {
  stop-color: var(--svg-color--f3632f, #F3632F);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vn8z_zbqx {
  d: path("M11.211 12.616c0-.364-.296-.607-.376-.68l-.364.352l.224.456z");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vsqt-vb2z {
  stop-color: var(--svg-color--ff9c1d, #FF9C1D);
  stop-opacity: 0;
}

.w7zv_4b3n {
  d: path("M15.612 11.86c.08.107-.087.238-.278.38c-.19.143-.332.244-.413.136s.01-.31.2-.452c.191-.143.41-.171.491-.064");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wdc-rnbqv {
  d: path("M22.552 13.876c-.554.648-.74 1.417-.761 1.758l1.847-.102l.887-1.183c.29-.383.54-1.02-.035-1.442c-.466-.342-.945-.066-1.102.106a28 28 0 0 0-.836.863");
}

.wodu9bbyy {
  stop-color: var(--svg-color--e99344, #E99344);
  stop-opacity: 0;
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wvw0m4z-y {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.956 11.28c.824 0 1.52.567 1.71 1.335a.346.346 0 0 1-.338.43h-2.816a.29.29 0 0 1-.286-.343a1.764 1.764 0 0 1 1.73-1.423");
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x-u3yxwuj {
  stop-color: var(--svg-color--ff9f3b, #FF9F3B);
  stop-opacity: 0;
}

.xaavtj_gl {
  stop-color: var(--svg-color--bb2c0d, #BB2C0D);
}

.xb_gabxuq {
  fill: var(--svg-color--000, #000);
  d: path("M15.05 12.748c0-.358.286-.645.645-.645a.642.642 0 0 1 .573.942h-1.141a.6.6 0 0 1-.077-.297");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.ydhtf9ruh {
  cx: 9.842px;
  cy: 12.103px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.492px;
  ry: 0.249px;
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.ylbet3bat {
  d: path("M16.698 12.6a1.06 1.06 0 0 0-.292-.584l-.328.36l.148.288z");
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.ytfamwmwg {
  d: path("M20.638 19.043a.8.8 0 0 1 .8-.8h4.79a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.z2fht5tro {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M30.725 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693a27 27 0 0 0 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.z6c5w6cyf {
  d: path("m12.456 12.478l-.67 2.32c-.137.478.191.955.656.955h.993c.465 0 .794-.485.657-.955l-.67-2.32c-.145-.514-.815-.514-.966 0");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zazrfkbck {
  stop-color: var(--svg-color--f6563d, #F6563D);
}

.zg4a17b1f {
  stop-color: var(--svg-color--c95513, #C95513);
}

.zm858vb9z {
  d: path("M12.904 20.036c-5.523 0-10 4.477-10 10v.05h20v-.05c0-5.523-4.477-10-10-10");
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
