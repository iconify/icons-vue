<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iP7zEld)" class="ui_a8hb3g"/><path fill="url(#iDAdjcc)" class="ui_a8hb3g"/><g filter="url(#iSJ0Vne)"><path class="zlxon6xvk"/></g><g filter="url(#iyQ0Vtl)"><path class="brnjlwy3g"/></g><path fill="url(#iqAyazd)" class="bviyofble"/><path fill="url(#iaMtb3V)" class="bviyofble"/><path fill="url(#iW50Ihe)" class="bviyofble"/><path fill="url(#iv0QOJe)" class="kgzjoacou"/><path fill="url(#ingztnd)" class="kgzjoacou"/><g filter="url(#iBf20gG)"><path fill="url(#igNFGdO)" class="g18g3hazc"/><path fill="url(#i9D2pCd)" class="g18g3hazc"/><path fill="url(#i0cdIHb)" class="g18g3hazc"/></g><path fill="url(#icMdM1b)" class="g18g3hazc"/><path fill="url(#ivIExjd)" class="g18g3hazc"/><g filter="url(#i5y49jI)"><path fill="url(#iFqtARb)" class="peljpmbvy"/></g><g filter="url(#io6JIic)"><path class="gnmrevbqs"/><path fill="url(#iD3gaLe)" class="tst3fqbyu"/></g><path fill="url(#iFjsuWd)" class="hwp9k689i"/><path fill="url(#iVM89qb)" class="hwp9k689i"/><path fill="url(#im5nTid)" class="gd9asv2dz"/><path fill="url(#iUMX9Yy)" class="v19pu8bbf"/><path fill="url(#i3hCxWb)" class="v19pu8bbf"/><path fill="url(#imHW8ye)" class="v19pu8bbf"/><path fill="url(#iFMs2Fd)" class="o-ykf2b5h"/><path fill="url(#iaWSPwe)" class="ha65atb6r"/><path fill="url(#iXWiQrd)" class="by77erb9m"/><path fill="url(#iVKVIAa)" class="by77erb9m"/><path fill="url(#iXWiQrd)" class="by77erb9m"/><path fill="url(#iVKVIAa)" class="by77erb9m"/><g filter="url(#iKMRKZF)"><path fill="url(#izfNLmc)" class="sh7z558vh"/></g><path fill="url(#iYC3eTd)" class="sh7z558vh"/><path fill="url(#inFUgQE)" class="sh7z558vh"/><path fill="url(#iiP3fge)" class="sh7z558vh"/><path fill="url(#iysbJac)" class="sh7z558vh"/><path fill="url(#i5cM4Tb)" class="sh7z558vh"/><path fill="url(#iIItr4h)" class="sh7z558vh"/><path fill="url(#i0Qj3Pd)" class="sh7z558vh"/><path fill="url(#iVAEc1c)" class="sh7z558vh"/><g filter="url(#iS7L6Qb)"><path class="ongsz-b4d"/></g><g filter="url(#iAev3dc)"><path fill="url(#iXPxKQc)" class="u7s6si0jh"/><path fill="url(#iQz00we)" class="u7s6si0jh"/><path fill="url(#i0Hzctv)" class="u7s6si0jh"/><path fill="url(#iVivGNf)" class="u7s6si0jh"/></g><path fill="url(#i3UX6zc)" class="u7s6si0jh"/><path fill="url(#iSk9ZBu)" class="u7s6si0jh"/><g filter="url(#i1K2nue)"><path stroke="url(#i52SSqb)" class="h84tc5b2w"/></g><path fill="url(#i6LiOmd)" class="r46izwfys"/><g filter="url(#i4Ydyae)"><path fill="url(#ihaYTCv)" class="v8_5_pbkv"/><path fill="url(#iWcztnb)" class="v8_5_pbkv"/><path fill="url(#ijNrD2b)" class="v8_5_pbkv"/><path fill="url(#i6cSTvb)" class="v8_5_pbkv"/><path fill="url(#i2xPt8b)" class="v8_5_pbkv"/></g><g filter="url(#ivh7LAf)"><path class="cn6sjxb-h"/></g><g filter="url(#i8bFZPc)"><path class="l6k0lhbrb"/></g><g filter="url(#iavGGUd)"><path fill="url(#iVO9nQe)" class="ovzy3ibpk"/><path fill="url(#iUSrmLb)" class="ovzy3ibpk"/></g><g filter="url(#i6wmaDd)"><path fill="url(#iShuO3c)" class="hwv2bpixa"/><path fill="url(#ioJhqkb)" class="hwv2bpixa"/><path fill="url(#iVHRX6d)" class="hwv2bpixa"/><path fill="url(#iePuoEb)" class="hwv2bpixa"/><path fill="url(#if1bbUd)" class="hwv2bpixa"/><path fill="url(#in5Q99b)" class="hwv2bpixa"/></g><path class="kkj52zy4r"/><path fill="url(#iioKLiF)" class="uwvhw_b7p"/><path class="d8fc76baa"/><g filter="url(#iGVNXcL)"><path class="ieh-e-wuc"/><path fill="url(#iG4P49R)" class="d6897wbra"/></g><g filter="url(#itarpUd)"><path fill="url(#igt6eyd)" class="w7pnt4bdh"/></g><path class="bpgl05b7v"/><path fill="url(#ihDeaeg)" class="bq15r0ehm"/><path class="uw1lddc2s"/><g filter="url(#iBzmoZb)"><path fill="url(#iwznpHc)" class="ga6s3ac2h"/></g><g filter="url(#iwZEQpd)"><ellipse transform="rotate(-27.914 13.532 9.849)" class="ms8py6btl"/><ellipse fill="url(#iHt2SZi)" transform="rotate(-27.914 13.532 9.849)" class="djtduk3cy"/></g><path fill="url(#i7b2peo)" class="ysw61acjh"/><path fill="url(#io6vqPd)" class="ysw61acjh"/><path fill="url(#iWGwGwc)" class="ysw61acjh"/><path fill="url(#iXqpBnc)" class="snkf9sbuy"/><path fill="url(#ii81PSc)" class="snkf9sbuy"/><g filter="url(#iHsvRbe)"><path class="wwrt9_bkr"/></g><g filter="url(#izYzQme)"><path class="fptms4bli"/></g><g filter="url(#idzTZpe)"><path class="opkgysbgu"/></g><g filter="url(#igsQTJe)"><path class="uvpyziz_p"/></g><defs><radialGradient id="iDAdjcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.47)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="iqAyazd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 23.042)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iv0QOJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.977)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="i0cdIHb" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.708 11.656)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="yfhz1ybyq"/><stop offset="1" class="kyt4h2bsk"/></radialGradient><radialGradient id="ivIExjd" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15358 .53752 11.395 19.734)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="iFjsuWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.491)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="ft6yvtbqk"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iVM89qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.988)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="kx98i3bkm"/><stop offset=".876" class="mf716dhmi"/></radialGradient><radialGradient id="iUMX9Yy" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.982 21.38)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="lv0iykbih"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iFMs2Fd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42103 -1.24999 2.39752 -2.72558 17.45 17.845)" gradientUnits="userSpaceOnUse"><stop class="fnpav4b9l"/><stop offset="1" class="f6x8csbnt"/></radialGradient><radialGradient id="iaWSPwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.444 11.637)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iXWiQrd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.437 11.92)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iVKVIAa" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.184 12.384)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="izfNLmc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.793 10.86)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="inFUgQE" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -10.0786 0 16.232 9.88)" gradientUnits="userSpaceOnUse"><stop offset=".645" class="sope1ebpi"/><stop offset=".944" class="npd09_nrq"/><stop offset="1" class="q23fb4b7u"/></radialGradient><radialGradient id="iiP3fge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.432 9.74)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iysbJac" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.429 -1.72)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="i5cM4Tb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.104 11.245)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iIItr4h" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.132 7.86)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="i0Qj3Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.83 14.932)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iVAEc1c" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 17.943 5.479)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iSk9ZBu" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 6.276 8.902)scale(2.59561 1.64977)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="i52SSqb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.504 -5.605)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="i6LiOmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.985 14.4)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iWcztnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 10.755 9.278)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ijNrD2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 20.846 9.278)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="i6cSTvb" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.322 -.35)scale(3.48023 1.85345)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="i2xPt8b" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.08 1.41)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iVO9nQe" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.87 2.846)scale(4.04714 1.12642)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iUSrmLb" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.182 -5.769)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iShuO3c" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .80083 -.44788 1.89356 19.606 4.012)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="ioJhqkb" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.039 -1.772)scale(4.28182 2.38794)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iVHRX6d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.57741 -.93641 20.494 8.317)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iePuoEb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.779 3.896)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="if1bbUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.438 3.77)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="in5Q99b" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.831 7.315)scale(4.25147 10.9633)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iioKLiF" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.167 9.944)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iG4P49R" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 17.939 10.028)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihDeaeg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.803 9.944)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iHt2SZi" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.517 10.163)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="io6vqPd" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.604 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iWGwGwc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.963 10.503)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="ii81PSc" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.92 4.898)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><linearGradient id="iP7zEld" x1="16" x2="16" y1="16.288" y2="31.226" gradientUnits="userSpaceOnUse"><stop class="hac9w68gp"/><stop offset="1" class="u61ykmvtc"/></linearGradient><linearGradient id="iaMtb3V" x1="18.903" x2="17.059" y1="25.288" y2="25.288" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="iW50Ihe" x1="15.591" x2="15.669" y1="17.835" y2="21.726" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="ingztnd" x1="23" x2="23.744" y1="29.464" y2="29.44" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="igNFGdO" x1="11.902" x2="11.902" y1="16.067" y2="29.967" gradientUnits="userSpaceOnUse"><stop class="j-er45bzw"/><stop offset=".524" class="iwz00abqx"/></linearGradient><linearGradient id="i9D2pCd" x1="13.671" x2="13.05" y1="22.526" y2="22.526" gradientUnits="userSpaceOnUse"><stop class="recxkftoe"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="icMdM1b" x1="11.902" x2="12.839" y1="25.943" y2="25.541" gradientUnits="userSpaceOnUse"><stop offset=".196" class="yqlqjsfuk"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="iFqtARb" x1="15.988" x2="15.988" y1="18.96" y2="20.945" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mu96iuqwe"/><stop offset="1" class="p-sb3ibac"/></linearGradient><linearGradient id="iD3gaLe" x1="18.71" x2="20.111" y1="21.574" y2="21.574" gradientUnits="userSpaceOnUse"><stop offset=".093" class="fxp5v2b6t"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="im5nTid" x1="9.452" x2="7.02" y1="23.984" y2="23.984" gradientUnits="userSpaceOnUse"><stop class="rpmno-b9y"/><stop offset="1" class="a9ts2kezv"/></linearGradient><linearGradient id="i3hCxWb" x1="14.606" x2="14.899" y1="24.847" y2="24.886" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="imHW8ye" x1="17.411" x2="17.012" y1="24.663" y2="24.71" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iYC3eTd" x1="21.142" x2="16.79" y1="12.546" y2="12.546" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iXPxKQc" x1="15.985" x2="16.84" y1="11.689" y2="11.689" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iQz00we" x1="14.912" x2="15.986" y1="11.534" y2="11.593" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="i0Hzctv" x1="15.985" x2="15.985" y1="12.088" y2="12.94" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iVivGNf" x1="15.985" x2="15.985" y1="9.84" y2="10.26" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="i3UX6zc" x1="16.116" x2="16.116" y1="12.762" y2="12.703" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="ihaYTCv" x1="21.349" x2="11.225" y1="5.198" y2="5.198" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="igt6eyd" x1="18.945" x2="18.631" y1="9.998" y2="10.191" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwznpHc" x1="14.547" x2="14.233" y1="9.998" y2="10.191" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7b2peo" x1="22.421" x2="21.215" y1="10.025" y2="12.201" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iXqpBnc" x1="10.135" x2="11.594" y1="10.729" y2="10.602" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><filter id="iSJ0Vne" width="6.556" height="14.595" x="9.212" y="15.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".5"/></filter><filter id="iyQ0Vtl" width="3.95" height="13.362" x="17.96" y="16.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".375"/></filter><filter id="iBf20gG" width="2.897" height="14" x="10.503" y="16.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2102"/></filter><filter id="i5y49jI" width="2.734" height="2.883" x="14.624" y="18.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2102" result="effect2_innerShadow_4002_2102"/></filter><filter id="io6JIic" width="2.902" height="14.05" x="18.61" y="16.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2102"/></filter><filter id="iKMRKZF" width="10.97" height="12.542" x="10.922" y="4.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2102" result="effect2_innerShadow_4002_2102"/></filter><filter id="iS7L6Qb" width="3.754" height="4.824" x="13.839" y="9.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".5"/></filter><filter id="iAev3dc" width="2.077" height="3.1" x="14.946" y="9.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".05"/></filter><filter id="i1K2nue" width="3.718" height="1.573" x="14.126" y="13.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".05"/></filter><filter id="i4Ydyae" width="12.873" height="8.357" x="9.549" y="1.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2102"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2102" result="effect2_innerShadow_4002_2102"/></filter><filter id="ivh7LAf" width="2.339" height="1.19" x="17.574" y="7.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2102"/></filter><filter id="i8bFZPc" width="2.339" height="1.176" x="12.318" y="7.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2102"/></filter><filter id="iavGGUd" width="6.584" height="5.992" x="9.904" y="2.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".125"/></filter><filter id="i6wmaDd" width="6.362" height="5.736" x="15.826" y="3.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".125"/></filter><filter id="iGVNXcL" width=".787" height=".696" x="17.433" y="9.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".05"/></filter><filter id="itarpUd" width=".891" height=".913" x="18.273" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".1"/></filter><filter id="iBzmoZb" width=".986" height="1.04" x="13.83" y="9.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".1"/></filter><filter id="iwZEQpd" width=".913" height=".705" x="13.075" y="9.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".05"/></filter><filter id="iHsvRbe" width="1.329" height="2.379" x="9.952" y="9.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".125"/></filter><filter id="izYzQme" width="1.447" height="2.403" x="20.697" y="9.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".125"/></filter><filter id="idzTZpe" width="2.405" height="1.16" x="12.237" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".125"/></filter><filter id="igsQTJe" width="2.405" height="1.16" x="17.516" y="7.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2102" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:office-worker-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.a9ts2kezv {
  stop-color: var(--svg-color--584a7e, #584A7E);
  stop-opacity: 0;
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.bpgl05b7v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.594 9.195c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.bq15r0ehm {
  d: path("M13.801 9.467a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.brnjlwy3g {
  fill: var(--svg-color--463d68, #463D68);
  d: path("m20.905 21.158l-1.19-.828a.23.23 0 0 1 .166-.393h.919a.252.252 0 0 0 .227-.359l-1.076-2.29a8 8 0 0 0-.646-.236h-.595v11.861l2.404-6.872a.85.85 0 0 0-.21-.883");
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.bviyofble {
  d: path("M18.71 16.097h-5.42v13.89h5.42z");
}

.by77erb9m {
  d: path("M11.124 12.11a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn6sjxb-h {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.718 7.88a1.85 1.85 0 0 0-.687-.41c-.305-.096-.686-.122-1.213-.058a.277.277 0 1 0 .067.55c.481-.058.776-.027.979.036c.198.063.332.164.49.3a.277.277 0 0 0 .364-.417");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d6897wbra {
  d: path("M18.104 9.656c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.d8fc76baa {
  fill: var(--svg-color--000, #000);
  d: path("M17.658 10.36a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.236");
}

.djtduk3cy {
  cx: 13.532px;
  cy: 9.849px;
  rx: 0.39px;
  ry: 0.197px;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f6x8csbnt {
  stop-color: var(--svg-color--ac7073, #AC7073);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.fnpav4b9l {
  stop-color: var(--svg-color--b68577, #B68577);
}

.fptms4bli {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.947 11.55q.059-.952.11-1.903a.956.956 0 0 1-.11 1.903");
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

.g18g3hazc {
  d: path("M13.29 16.067h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.ga6s3ac2h {
  d: path("M14.617 10.255c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.gd9asv2dz {
  d: path("M7.032 29.977H8.97V18.013a11 11 0 0 0-3.656 5.842a11 11 0 0 0-.304 2.632l.02 3.49z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.gnmrevbqs {
  fill: var(--svg-color--605890, #605890);
  d: path("m21.22 21.097l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h84tc5b2w {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.634 13.362a.23.23 0 0 0-.271.047a.21.21 0 0 0-.024.27c.349.528.956.88 1.646.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.ha65atb6r {
  d: path("M20.846 12.11c.336-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.hac9w68gp {
  stop-color: var(--svg-color--534973, #534973);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwp9k689i {
  d: path("M16 15.034h-2.71v4.74c0 .31.36.49.61.29L16 18.67l2.1 1.393c.25.2.61.02.61-.29v-4.74z");
}

.hwv2bpixa {
  d: path("m21.198 8.617l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.367c-.256-.97.671-1.713 1.656-1.522c.973.189 2.082.517 2.902 1.052c1.745 1.138 1.44 3.188.52 4.154");
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ieh-e-wuc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.104 9.656c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iwz00abqx {
  stop-color: var(--svg-color--5f5289, #5F5289);
}

.j-er45bzw {
  stop-color: var(--svg-color--544a76, #544A76);
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kgzjoacou {
  d: path("M23 17.995v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.kkj52zy4r {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.376 9.195c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kx98i3bkm {
  stop-color: var(--svg-color--837a8d, #837A8D);
  stop-opacity: 0;
}

.kyt4h2bsk {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l6k0lhbrb {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.574 7.772a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.55a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.438z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lv0iykbih {
  stop-color: var(--svg-color--56406d, #56406D);
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mf716dhmi {
  stop-color: var(--svg-color--544a5f, #544A5F);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.ms8py6btl {
  cx: 13.532px;
  cy: 9.849px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.mu96iuqwe {
  stop-color: var(--svg-color--4b375e, #4B375E);
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.npd09_nrq {
  stop-color: var(--svg-color--b87387, #B87387);
}

.o-ykf2b5h {
  d: path("M14.045 16.867c.02.213.205.69.746 1.054c.214.144 1.213.629 1.193.619c.156-.078.807-.299 1.284-.619c.54-.364.725-.841.746-1.055l-1.985-.953z");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.ongsz-b4d {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.555 10.524l-.692 1.656c-.102.378.142.756.486.756h.735c.345 0 .588-.384.486-.756l-.496-1.838c-.107-.408-.408-.225-.52.182");
}

.opkgysbgu {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.612 8.051c.257-.184.897-.508 1.655-.381");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.ovzy3ibpk {
  d: path("m16.218 5.245l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.614 1.28-1.96c.142-.097.26-.179.331-.252l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.892v1.485z");
}

.p-sb3ibac {
  stop-color: var(--svg-color--483b55, #483B55);
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.peljpmbvy {
  d: path("m16.01 18.304l-1.24 1.204a.15.15 0 0 0-.033.168l.547 1.26c.04.092.13.15.23.15h.952c.1 0 .19-.059.23-.15l.55-1.28a.15.15 0 0 0-.033-.167z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q23fb4b7u {
  stop-color: var(--svg-color--ad638b, #AD638B);
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r46izwfys {
  d: path("M15.985 13.757c-.507 0-.984-.12-1.385-.328c-.137-.07-.285.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
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

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rpmno-b9y {
  stop-color: var(--svg-color--41375c, #41375C);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.sh7z558vh {
  d: path("M11.16 13.625a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.564-2.212-1.443a.66.66 0 0 0-.615-.419h-1.273c-1.845 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.snkf9sbuy {
  d: path("M10.931 9.002a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.sope1ebpi {
  stop-color: var(--svg-color--cc9089, #CC9089);
  stop-opacity: 0;
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tst3fqbyu {
  d: path("m21.22 21.097l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u61ykmvtc {
  stop-color: var(--svg-color--584982, #584982);
}

.u7s6si0jh {
  d: path("m15.603 10.146l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.ui_a8hb3g {
  d: path("M16 15.477c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uvpyziz_p {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.546 8.005c-.257-.184-.897-.509-1.655-.381");
}

.uw1lddc2s {
  fill: var(--svg-color--000, #000);
  d: path("M14.312 10.36a.51.51 0 0 0-.51-.512a.51.51 0 0 0-.455.747h.904a.5.5 0 0 0 .061-.236");
}

.uwvhw_b7p {
  d: path("M18.17 9.467a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v19pu8bbf {
  d: path("M15.505 21.087a.25.25 0 0 0-.247.212l-1.328 8.668h4.11l-1.318-8.668a.25.25 0 0 0-.247-.212z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v8_5_pbkv {
  d: path("M20.84 4.218c.514.177.976.536 1.268 1.05A2.37 2.37 0 0 1 22 7.796a1.56 1.56 0 0 0-.27.874v1.188a1.75 1.75 0 0 0-.667-.268l.078-1.606a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.446a2.35 2.35 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.913-.188c.843 0 1.58.456 1.988 1.132c.308.51.79.88 1.353 1.073");
}

.w7pnt4bdh {
  d: path("M18.964 10.242a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wwrt9_bkr {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.948 9.663a.956.956 0 0 0 .083 1.879a78 78 0 0 1-.083-1.88");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.yfhz1ybyq {
  stop-color: var(--svg-color--3c2e57, #3C2E57);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yqlqjsfuk {
  stop-color: var(--svg-color--55477c, #55477C);
}

.ysw61acjh {
  d: path("M20.907 12.201q.1-1.595.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zlxon6xvk {
  fill: var(--svg-color--41355c, #41355C);
  d: path("M13.419 16.826c-.513 0-1.296-.03-1.77.166l-1.38 2.723c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.343c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.115l-1.34-11.477z");
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

</style>
