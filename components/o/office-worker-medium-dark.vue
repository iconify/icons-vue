<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ii1n4Zb)" class="fpc-w8unn"/><path fill="url(#ibfv0gb)" class="fpc-w8unn"/><g filter="url(#iPJoZRb)"><path class="bju_r4d8q"/></g><g filter="url(#is5Uyde)"><path class="sx8bpzjax"/></g><path fill="url(#itSRADc)" class="exvucxbiq"/><path fill="url(#igJ2lEb)" class="exvucxbiq"/><path fill="url(#iYOtWUb)" class="exvucxbiq"/><path fill="url(#iE5g3gb)" class="xc6znrbjq"/><path fill="url(#i0lVWpe)" class="xc6znrbjq"/><g filter="url(#iq47iwc)"><path fill="url(#ieGD6ac)" class="vlp0azbmu"/><path fill="url(#iZLNDad)" class="vlp0azbmu"/><path fill="url(#inid5Fe)" class="vlp0azbmu"/></g><path fill="url(#i94DaMb)" class="vlp0azbmu"/><path fill="url(#iLsRwmu)" class="vlp0azbmu"/><g filter="url(#ibbbODe)"><path fill="url(#i97Wwjc)" class="q-5kgzb9v"/></g><g filter="url(#iJ88FJT)"><path class="tl0sjenli"/><path fill="url(#itkESmc)" class="yi0b9jgtv"/></g><path fill="url(#igaeQHe)" class="dem1xwbda"/><path fill="url(#iC4gGWb)" class="dem1xwbda"/><path fill="url(#iEpnpvd)" class="zmh2_lmnk"/><path fill="url(#iUMX9Yy)" class="gyd099b4k"/><path fill="url(#i8IKsne)" class="gyd099b4k"/><path fill="url(#i3dQgzj)" class="gyd099b4k"/><path fill="url(#iMh500d)" class="m_p9nbvvu"/><path fill="url(#iGpt0cb)" class="p40w45b0m"/><path fill="url(#iAkKa4p)" class="qp_036lgc"/><g filter="url(#idBp4ke)"><path fill="url(#iQYxqww)" class="bjdo61bvj"/><path fill="url(#i5lwx5b)" class="bjdo61bvj"/></g><path fill="url(#ifHFItc)" class="bjdo61bvj"/><path fill="url(#ikgBAod)" class="bjdo61bvj"/><path fill="url(#if2nbVd)" class="bjdo61bvj"/><path fill="url(#inA6N8c)" class="bjdo61bvj"/><path fill="url(#iBVsdac)" class="bjdo61bvj"/><path fill="url(#itYQo1c)" class="bjdo61bvj"/><path fill="url(#i5VUJjc)" class="bjdo61bvj"/><g filter="url(#i4m1HCb)"><path class="pu4uxzbke"/></g><g filter="url(#iIOPigc)"><path class="krp_8sbav"/><path fill="url(#ipplFnb)" class="f-zdqxbkg"/><path fill="url(#iNSMo8b)" class="f-zdqxbkg"/><path fill="url(#iI6Jssd)" class="f-zdqxbkg"/><path fill="url(#iyi96ke)" class="f-zdqxbkg"/><path fill="url(#iDttTnb)" class="f-zdqxbkg"/></g><path fill="url(#ihUh5Zn)" class="f-zdqxbkg"/><path fill="url(#ihXOHvd)" class="f-zdqxbkg"/><g filter="url(#ip4ZOoh)"><path stroke="url(#ilARpOe)" class="fy5-xkbsu"/></g><path fill="url(#ims9qoc)" class="lmj4o7p8j"/><g filter="url(#iVqG8Ge)"><path fill="url(#iclas1c)" class="mnh60uoct"/><path fill="url(#iCIw3ec)" class="mnh60uoct"/><path fill="url(#iOhcExc)" class="mnh60uoct"/><path fill="url(#i9KVfyH)" class="mnh60uoct"/><path fill="url(#iBkL0ld)" class="mnh60uoct"/></g><g filter="url(#ijzKyye)"><path class="zypsjd-vn"/></g><g filter="url(#ieRd3Gc)"><path class="jdpyi6b3h"/></g><g filter="url(#iiK0Mne)"><path class="hq5jj0bms"/><path fill="url(#ioT9nZh)" class="i87aqlbgz"/><path fill="url(#i9Pd4Cb)" class="i87aqlbgz"/></g><g filter="url(#ibyp39b)"><path class="yn0_2i7om"/><path fill="url(#itz0y1d)" class="elefwzbti"/><path fill="url(#irCOFid)" class="elefwzbti"/></g><path class="k6qrw-bgi"/><path fill="url(#iKYtPXc)" class="zbihuyb5u"/><path class="pyf1n-b5f"/><g filter="url(#iXBBlYb)"><path class="qzxfk-bvt"/><path fill="url(#igam9qe)" class="dgy01bbst"/></g><g filter="url(#i0XCYIX)"><path fill="url(#iM2CEfc)" class="yde48lbmb"/></g><path class="ek7__m0ly"/><path fill="url(#i5QPhdb)" class="jfca2riaw"/><path class="lq9czjb_m"/><g filter="url(#i2ItTUf)"><path fill="url(#i45Xe0d)" class="pktgskbex"/></g><g filter="url(#igB6vzx)"><ellipse transform="rotate(-27.914 13.594 9.859)" class="xy8a-i1-m"/><ellipse fill="url(#i8UQqTd)" transform="rotate(-27.914 13.594 9.859)" class="jz_kubloe"/></g><path fill="url(#iKy0Dob)" class="gwb-3qh9n"/><path fill="url(#iuxucGc)" class="gwb-3qh9n"/><path fill="url(#iLTPS1b)" class="gwb-3qh9n"/><path fill="url(#ifP0kRc)" class="gwb-3qh9n"/><path fill="url(#i3wXYdc)" class="u84kpwb2s"/><path fill="url(#iHN7nAe)" class="u84kpwb2s"/><g filter="url(#iUoMLYc)"><path fill="url(#iCOjCpc)" class="stckw27bb"/></g><g filter="url(#ixUyOZc)"><path fill="url(#iZlVV8d)" class="igvzvjbbq"/></g><g filter="url(#isxwO6X)"><path class="evehssecb"/></g><g filter="url(#iFKvRCe)"><path class="pdocal3rx"/></g><g filter="url(#iheyc7A)"><path class="wff4-7bou"/></g><defs><radialGradient id="ibfv0gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.46)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="itSRADc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iE5g3gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.967)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="inid5Fe" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.711 11.651)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="yfhz1ybyq"/><stop offset="1" class="kyt4h2bsk"/></radialGradient><radialGradient id="iLsRwmu" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15357 .53751 11.395 19.723)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="igaeQHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.481)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="ft6yvtbqk"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iC4gGWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.978)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="kx98i3bkm"/><stop offset=".876" class="mf716dhmi"/></radialGradient><radialGradient id="iUMX9Yy" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.982 21.38)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lv0iykbih"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iMh500d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3026 -5.67273 0 16.03 17.227)" gradientUnits="userSpaceOnUse"><stop class="ork-vcb7p"/><stop offset="1" class="tllu15bjk"/></radialGradient><radialGradient id="iGpt0cb" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.912 20.854)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iAkKa4p" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 9.99 12.302)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iQYxqww" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.855 10.87)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i5lwx5b" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.576 8.155)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="ikgBAod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.494 9.558)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="if2nbVd" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.693 -2.096)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="inA6N8c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.48 11.859)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iBVsdac" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.255 8.138)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="itYQo1c" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.175 13.806)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="i5VUJjc" cx="0" cy="0" r="1" gradientTransform="scale(13.6989 11.4687)rotate(90 .32 .854)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="ml0kw6b9u"/><stop offset="1" class="k37kt3cne"/></radialGradient><radialGradient id="iNSMo8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.513 12.231)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iyi96ke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.63 11.662)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ihXOHvd" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.962 8.987)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="ims9qoc" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 15.556 14.494)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iCIw3ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.818 7.978)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iOhcExc" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.314 -6.295)scale(2.51513 4.45632)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i9KVfyH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.154 3.012)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iBkL0ld" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 15.142 1.42)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="ioT9nZh" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.3 3.68)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i9Pd4Cb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.222 -5.82)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="itz0y1d" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 18.68 7.493)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="irCOFid" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 17.795 6.017)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iKYtPXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.23 9.954)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="igam9qe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18 10.039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5QPhdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.865 9.954)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8UQqTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.578 10.174)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuxucGc" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.665 9.969)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iLTPS1b" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.025 10.513)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="ifP0kRc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.14 10.685)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iHN7nAe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.132 10.61)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iCOjCpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.132 10.612)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><linearGradient id="ii1n4Zb" x1="16" x2="16" y1="16.278" y2="31.216" gradientUnits="userSpaceOnUse"><stop class="hac9w68gp"/><stop offset="1" class="u61ykmvtc"/></linearGradient><linearGradient id="igJ2lEb" x1="18.903" x2="17.059" y1="25.278" y2="25.278" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="iYOtWUb" x1="15.591" x2="15.669" y1="17.825" y2="21.716" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="i0lVWpe" x1="23" x2="23.744" y1="29.454" y2="29.43" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="ieGD6ac" x1="11.902" x2="11.902" y1="16.057" y2="29.957" gradientUnits="userSpaceOnUse"><stop class="j-er45bzw"/><stop offset=".524" class="iwz00abqx"/></linearGradient><linearGradient id="iZLNDad" x1="13.671" x2="13.05" y1="22.516" y2="22.516" gradientUnits="userSpaceOnUse"><stop class="recxkftoe"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="i94DaMb" x1="11.902" x2="12.839" y1="25.933" y2="25.531" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yqlqjsfuk"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="i97Wwjc" x1="15.988" x2="15.988" y1="18.95" y2="20.935" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mu96iuqwe"/><stop offset="1" class="p-sb3ibac"/></linearGradient><linearGradient id="itkESmc" x1="18.71" x2="20.111" y1="21.564" y2="21.564" gradientUnits="userSpaceOnUse"><stop offset=".093" class="fxp5v2b6t"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="iEpnpvd" x1="9.452" x2="7.02" y1="23.974" y2="23.974" gradientUnits="userSpaceOnUse"><stop class="rpmno-b9y"/><stop offset="1" class="a9ts2kezv"/></linearGradient><linearGradient id="i8IKsne" x1="14.606" x2="14.899" y1="24.837" y2="24.876" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="i3dQgzj" x1="17.411" x2="17.012" y1="24.653" y2="24.7" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="ifHFItc" x1="21.204" x2="18.675" y1="12.556" y2="12.556" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ipplFnb" x1="16.885" x2="16.047" y1="11.546" y2="11.58" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iI6Jssd" x1="16.047" x2="16.047" y1="12.685" y2="12.22" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iDttTnb" x1="16.047" x2="16.047" y1="9.98" y2="10.526" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="ihUh5Zn" x1="16.463" x2="16.463" y1="12.822" y2="12.63" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="ilARpOe" x1="14.845" x2="15.164" y1="14.255" y2="13.421" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iclas1c" x1="22.899" x2="11.287" y1="5.208" y2="5.208" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iM2CEfc" x1="19.007" x2="18.693" y1="10.008" y2="10.202" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i45Xe0d" x1="14.609" x2="14.295" y1="10.008" y2="10.202" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKy0Dob" x1="22.483" x2="21.277" y1="10.035" y2="12.211" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="i3wXYdc" x1="10.197" x2="11.656" y1="10.739" y2="10.612" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iZlVV8d" x1="21.463" x2="21.463" y1="9.653" y2="11.557" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><filter id="iPJoZRb" width="6.556" height="14.595" x="9.212" y="15.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".5"/></filter><filter id="is5Uyde" width="3.95" height="13.362" x="17.96" y="16.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".375"/></filter><filter id="iq47iwc" width="2.897" height="14" x="10.503" y="16.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2096"/></filter><filter id="ibbbODe" width="2.734" height="2.883" x="14.624" y="18.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2096"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2096" result="effect2_innerShadow_4002_2096"/></filter><filter id="iJ88FJT" width="2.902" height="14.05" x="18.61" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2096"/></filter><filter id="idBp4ke" width="11.22" height="12.542" x="10.984" y="4.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2096"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2096" result="effect2_innerShadow_4002_2096"/></filter><filter id="i4m1HCb" width="3.747" height="4.9" x="14.032" y="9.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".5"/></filter><filter id="iIOPigc" width="2.277" height="3.3" x="14.908" y="9.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".1"/></filter><filter id="ip4ZOoh" width="3.718" height="1.573" x="14.188" y="13.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".05"/></filter><filter id="iVqG8Ge" width="12.873" height="8.357" x="9.611" y="1.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2096"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2096" result="effect2_innerShadow_4002_2096"/></filter><filter id="ijzKyye" width="2.339" height="1.19" x="17.636" y="7.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2096"/></filter><filter id="ieRd3Gc" width="2.339" height="1.176" x="12.38" y="7.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2096"/></filter><filter id="iiK0Mne" width="6.584" height="5.992" x="9.966" y="2.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2096"/><feGaussianBlur result="effect2_foregroundBlur_4002_2096" stdDeviation=".125"/></filter><filter id="ibyp39b" width="6.319" height="5.711" x="15.888" y="3.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".125"/></filter><filter id="iXBBlYb" width=".787" height=".696" x="17.495" y="9.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".05"/></filter><filter id="i0XCYIX" width=".891" height=".913" x="18.335" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".1"/></filter><filter id="i2ItTUf" width=".986" height="1.04" x="13.892" y="9.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".1"/></filter><filter id="igB6vzx" width=".913" height=".705" x="13.137" y="9.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".05"/></filter><filter id="iUoMLYc" width="1.329" height="2.379" x="9.966" y="9.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".125"/></filter><filter id="ixUyOZc" width="1.947" height="2.903" x="20.49" y="9.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".25"/></filter><filter id="isxwO6X" width="2.405" height="1.16" x="12.299" y="7.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".125"/></filter><filter id="iFKvRCe" width="2.405" height="1.16" x="17.578" y="7.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".125"/></filter><filter id="iheyc7A" width="5.266" height="3.006" x="16.926" y="3.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2096" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:office-worker-medium-dark" /></template>
<style>
.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.a9ts2kezv {
  stop-color: var(--svg-color--584a7e, #584A7E);
  stop-opacity: 0;
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bjdo61bvj {
  d: path("M11.222 13.636a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.bju_r4d8q {
  fill: var(--svg-color--41355c, #41355C);
  d: path("M13.419 16.816c-.513 0-1.296-.03-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.342c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.115l-1.34-11.477z");
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.dem1xwbda {
  d: path("M16 15.024h-2.71v4.74c0 .31.36.49.61.29L16 18.66l2.1 1.393c.25.2.61.02.61-.29v-4.74z");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dgy01bbst {
  d: path("M18.166 9.666c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.ek7__m0ly {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.656 9.206c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341H14.8a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.elefwzbti {
  d: path("m21.26 8.522l-.03-.632c-.01-.763-.641-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.135-.12-.368c-.256-.97.671-1.706 1.65-1.488c.94.209 2.004.558 2.816 1.087c1.744 1.138 1.53 3.12.613 4.086");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.evehssecb {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.674 8.062c.257-.185.897-.51 1.655-.382");
}

.exvucxbiq {
  d: path("M18.71 16.087h-5.42v13.89h5.42z");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f-zdqxbkg {
  d: path("m15.665 10.156l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fpc-w8unn {
  d: path("M16 15.467c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.ft2atdbel {
  stop-color: var(--svg-color--877f93, #877F93);
}

.ft5dv1b6b {
  fill: none;
}

.ft6yvtbqk {
  stop-color: var(--svg-color--cac3d3, #CAC3D3);
}

.fxp5v2b6t {
  stop-color: var(--svg-color--453d68, #453D68);
}

.fy5-xkbsu {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.696 13.372a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.gwb-3qh9n {
  d: path("M20.969 12.211q.1-1.596.185-3.19a1.61 1.61 0 0 1-.185 3.19");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.gyd099b4k {
  d: path("M15.505 21.077a.25.25 0 0 0-.247.212l-1.328 8.668h4.11l-1.318-8.668a.25.25 0 0 0-.247-.212z");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hac9w68gp {
  stop-color: var(--svg-color--534973, #534973);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hq5jj0bms {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.28 5.255l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.098.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.892v1.485z");
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i87aqlbgz {
  d: path("m16.28 5.255l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.098.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.892v1.485z");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.igvzvjbbq {
  d: path("M20.99 11.557q.059-.952.11-1.904a.955.955 0 0 1-.11 1.904");
}

.iwz00abqx {
  stop-color: var(--svg-color--5f5289, #5F5289);
}

.j-er45bzw {
  stop-color: var(--svg-color--544a76, #544A76);
}

.jdpyi6b3h {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.636 7.782a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.jfca2riaw {
  d: path("M13.863 9.477a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.jz_kubloe {
  cx: 13.594px;
  cy: 9.859px;
  rx: 0.39px;
  ry: 0.197px;
}

.k37kt3cne {
  stop-color: var(--svg-color--763671, #763671);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k6qrw-bgi {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.438 9.206c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.krp_8sbav {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.665 10.156l-.532 1.838c-.108.379.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.kx98i3bkm {
  stop-color: var(--svg-color--837a8d, #837A8D);
  stop-opacity: 0;
}

.kyt4h2bsk {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
  stop-opacity: 0;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmj4o7p8j {
  d: path("M16.047 13.767c-.508 0-.985-.12-1.386-.328c-.136-.07-.284.084-.197.209c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lq9czjb_m {
  fill: var(--svg-color--000, #000);
  d: path("M14.374 10.37a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lv0iykbih {
  stop-color: var(--svg-color--56406d, #56406D);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m_p9nbvvu {
  d: path("M14.045 16.856c.02.214.205.691.746 1.055c.214.144 1.213.629 1.193.619c.156-.078.807-.299 1.284-.619c.54-.364.725-.841.746-1.055l-1.985-.953z");
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf716dhmi {
  stop-color: var(--svg-color--544a5f, #544A5F);
}

.ml0kw6b9u {
  stop-color: var(--svg-color--79435c, #79435C);
  stop-opacity: 0;
}

.mnh60uoct {
  d: path("M20.902 4.228c.514.177.976.536 1.267 1.051a2.37 2.37 0 0 1-.105 2.526a1.55 1.55 0 0 0-.271.875v1.188a1.75 1.75 0 0 0-.667-.269l.078-1.606a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875A2.39 2.39 0 0 1 9.88 5.36a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.913-.188c.843 0 1.58.456 1.988 1.132c.308.51.79.88 1.353 1.073");
}

.mu96iuqwe {
  stop-color: var(--svg-color--4b375e, #4B375E);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.ork-vcb7p {
  stop-color: var(--svg-color--673944, #673944);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p-sb3ibac {
  stop-color: var(--svg-color--483b55, #483B55);
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p40w45b0m {
  d: path("M20.908 12.12c.336-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pdocal3rx {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.608 8.016c-.257-.185-.898-.51-1.655-.382");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pktgskbex {
  d: path("M14.678 10.265c0-.288-.234-.48-.298-.539l-.288.28l.178.36z");
}

.pu4uxzbke {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.646 10.352l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.383.484-.756l-.494-1.838c-.106-.407-.504-.407-.615 0");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pyf1n-b5f {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.37c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.q-5kgzb9v {
  d: path("m16.01 18.294l-1.24 1.204a.15.15 0 0 0-.033.168l.547 1.26c.04.092.13.15.23.15h.952c.1 0 .19-.059.23-.15l.55-1.28a.15.15 0 0 0-.033-.167z");
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qp_036lgc {
  d: path("M11.186 12.12a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qzxfk-bvt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.166 9.666c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.recxkftoe {
  stop-color: var(--svg-color--3e305b, #3E305B);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rpmno-b9y {
  stop-color: var(--svg-color--41375c, #41375C);
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stckw27bb {
  d: path("M10.962 9.672a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.084-1.88");
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sx8bpzjax {
  fill: var(--svg-color--463d68, #463D68);
  d: path("m20.905 21.148l-1.19-.828a.23.23 0 0 1 .166-.393h.919a.252.252 0 0 0 .227-.359l-1.076-2.29a8 8 0 0 0-.646-.236h-.595v11.861l2.404-6.872a.85.85 0 0 0-.21-.883");
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tl0sjenli {
  fill: var(--svg-color--605890, #605890);
  d: path("m21.22 21.087l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.tllu15bjk {
  stop-color: var(--svg-color--6a433f, #6A433F);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.u61ykmvtc {
  stop-color: var(--svg-color--584982, #584982);
}

.u84kpwb2s {
  d: path("M11.003 9.007a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vlp0azbmu {
  d: path("M13.29 16.057h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wff4-7bou {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.24 5.21h-2.081a.483.483 0 1 1 .077-.96c.54.085 1.257.205 1.737.324c1.086.27 1.385.798 1.47 1.175a1.51 1.51 0 0 0-1.203-.539");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xc6znrbjq {
  d: path("M23 17.985v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xy8a-i1-m {
  cx: 13.594px;
  cy: 9.859px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.yde48lbmb {
  d: path("M19.026 10.252a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.yfhz1ybyq {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
}

.yi0b9jgtv {
  d: path("m21.22 21.087l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.yn0_2i7om {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.26 8.522l-.03-.632c-.01-.763-.641-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.059-.135-.12-.368c-.256-.97.671-1.706 1.65-1.488c.94.209 2.004.558 2.816 1.087c1.744 1.138 1.53 3.12.613 4.086");
}

.yqlqjsfuk {
  stop-color: var(--svg-color--55477c, #55477C);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zbihuyb5u {
  d: path("M18.231 9.477a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zmh2_lmnk {
  d: path("M7.032 29.967H8.97V18.003a11 11 0 0 0-3.656 5.842a11 11 0 0 0-.304 2.632l.02 3.49z");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zypsjd-vn {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.78 7.89a1.85 1.85 0 0 0-.688-.41c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

</style>
