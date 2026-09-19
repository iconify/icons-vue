<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iOWJ3ic)" class="lr-iuirkd"/><path fill="url(#isP7ODb)" class="lr-iuirkd"/><path fill="url(#iuFGkKb)" class="lr-iuirkd"/><path fill="url(#iljk3je)" class="lr-iuirkd"/><path fill="url(#iSQKEqb)" class="lr-iuirkd"/><path fill="url(#i5aMFyQ)" class="lr-iuirkd"/><path fill="url(#iWSyoxc)" class="lr-iuirkd"/><path fill="url(#igAqwfc)" class="lr-iuirkd"/><path fill="url(#iYH0ZQb)" class="lr-iuirkd"/><path fill="url(#ivdqove)" class="lr-iuirkd"/><path fill="url(#iFDGdce)" class="lr-iuirkd"/><path fill="url(#ie4C6Gd)" class="lr-iuirkd"/><g filter="url(#ijk9Ayk)"><path stroke="url(#iYVkYhb)" class="gj_pv9bgn"/></g><g filter="url(#ieIeGYc)"><path stroke="url(#icTIvIb)" class="j1aad2bix"/></g><g filter="url(#iKljonP)"><path stroke="url(#iwHEEMb)" class="gu3v_k24n"/></g><g filter="url(#iSsAIod)"><path stroke="url(#i8THhbc)" class="i6vwvnf0x"/></g><g filter="url(#ifeORNb)"><path stroke="url(#iDRd7Cb)" class="p-m_1mbfg"/></g><g filter="url(#iOr0pQe)"><path stroke="url(#i9TWeFc)" class="n-28zubdd"/></g><g filter="url(#i4IR22x)"><path stroke="url(#ii26R7c)" class="s5yq33b3c"/></g><g filter="url(#i2KdCGe)"><path stroke="url(#iG1ir1G)" class="v7boqxhcs"/></g><g filter="url(#iuVBPKe)"><path stroke="url(#iZrOxFb)" class="sf99phbve"/></g><g filter="url(#iphI3Hd)"><path stroke="url(#iE39uUb)" class="u62ixwbju"/></g><path fill="url(#iFhHSLb)" class="dwt__obip"/><path fill="url(#itfU9Gd)" class="dwt__obip"/><path fill="url(#iYWwtwb)" class="dwt__obip"/><path fill="url(#ikdde6c)" class="zxmocx6ig"/><path fill="url(#iTQobNb)" class="zxmocx6ig"/><path fill="url(#iU4ghje)" class="zxmocx6ig"/><path fill="url(#iM5ETdd)" class="t6_nkac4i"/><path fill="url(#ieev1Be)" class="t6_nkac4i"/><path fill="url(#iPdFsSX)" class="t6_nkac4i"/><path fill="url(#idrC3vb)" class="t6_nkac4i"/><path fill="url(#iwuBGed)" class="t6_nkac4i"/><path fill="url(#ihIPMGc)" class="t6_nkac4i"/><path fill="url(#iLfeZed)" class="rc8ljf8lb"/><path fill="url(#iEhPgzW)" class="rc8ljf8lb"/><g filter="url(#igjxnbc)"><path stroke="url(#irpXAZw)" class="ppy479bpq"/></g><g filter="url(#inlMo4c)"><circle fill="url(#icZpRzc)" class="xm75ajb4k"/></g><g filter="url(#iUaQ3Bc)"><circle fill="url(#iKsvIfe)" class="v46okmbvl"/></g><g filter="url(#iQehykd)"><circle fill="url(#icHuNdc)" class="pc1m58puw"/><circle fill="url(#itB1tfe)" class="pc1m58puw"/></g><g filter="url(#iQn0deb)"><circle class="g5d0dobpo"/><circle fill="url(#iRSKEVd)" class="tewa6_b_g"/><circle fill="url(#iB7I16b)" class="tewa6_b_g"/></g><g filter="url(#igN583Q)"><path fill="url(#i5abtMb)" class="ygz6o7bgm"/><path fill="url(#iIhysoe)" class="ygz6o7bgm"/><path fill="url(#iMTHgUc)" class="ygz6o7bgm"/><path fill="url(#iAg9Dtc)" class="ygz6o7bgm"/><path fill="url(#iCeKrvc)" class="ygz6o7bgm"/></g><g filter="url(#iMWD6Le)"><path class="bt9t76zok"/><path fill="url(#imv2xpc)" class="nfql5kgcv"/><path fill="url(#iLhkIFc)" class="nfql5kgcv"/><path fill="url(#i2ZhxGd)" class="nfql5kgcv"/><path fill="url(#irHE7bc)" class="nfql5kgcv"/><path fill="url(#iRw4xMc)" class="nfql5kgcv"/></g><path fill="url(#iW73NSd)" class="nfql5kgcv"/><path fill="url(#icg6x5b)" class="nfql5kgcv"/><g filter="url(#icS7tde)"><path class="v2dqj6bfb"/></g><g filter="url(#ic3e2Oe)"><path class="n08vq6wnt"/><path fill="url(#iYVxICe)" class="u35dl1bhv"/><path fill="url(#i4Bg7Yc)" class="u35dl1bhv"/><path fill="url(#ifMA2ye)" class="u35dl1bhv"/></g><path fill="url(#iQ4jbvb)" class="u35dl1bhv"/><path stroke="url(#ivQZWPb)" class="ixp34-bkk"/><g filter="url(#izPsGBe)"><path class="u0-3rvbpd"/></g><g filter="url(#iTeeIeZ)"><path class="yfgdr3b5p"/></g><path class="ap0ejfjaf"/><path fill="url(#inApZ8b)" class="ww6kpos8t"/><path class="qczyap8xv"/><g filter="url(#igYalIf)"><path class="ttv30ab9m"/><path fill="url(#ikPcffe)" class="b6dgc3bep"/></g><g filter="url(#iO5B1tb)"><path fill="url(#iNuIXgK)" class="vt1vh9b2m"/></g><path class="jeoth2bte"/><path fill="url(#i1ABDeb)" class="u1k6efbcx"/><path class="tqethqbxe"/><g filter="url(#icZebLd)"><path fill="url(#i1l75gc)" class="hkmkuhklj"/></g><g filter="url(#icRuede)"><ellipse transform="rotate(-27.914 16.39 13.255)" class="uuvxkpb6m"/><ellipse fill="url(#icQtAyN)" transform="rotate(-27.914 16.39 13.255)" class="ju3xmq33r"/></g><g filter="url(#i8tukAd)"><path stroke="url(#i7iBSVb)" class="kqp7atbzj"/></g><g filter="url(#i7zQ2fc)"><path stroke="url(#iBYdepO)" class="l3ktvxsjr"/></g><defs><radialGradient id="iOWJ3ic" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 6.185 11.555)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="vpa8ubcez"/><stop offset="1" class="nick4i1gd"/></radialGradient><radialGradient id="isP7ODb" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 3.01 7.228)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="tvy-4obul"/><stop offset="1" class="rlvwxbcbx"/></radialGradient><radialGradient id="iljk3je" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.91 4.741)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="iSQKEqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.558 3.577)" gradientUnits="userSpaceOnUse"><stop class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="i5aMFyQ" cx="0" cy="0" r="1" gradientTransform="rotate(99.609 3.076 5.009)scale(4.02522 .49917)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="iWSyoxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 10.027 3.173)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="igAqwfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 8.1 2.145)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="iYH0ZQb" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.868 3.907)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="ivdqove" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 4.286 3.961)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="iFDGdce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09125 1.09125 -.85394 -.85394 12.322 6.44)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="itfU9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 7.44 12.308)" gradientUnits="userSpaceOnUse"><stop class="zen3jbcth"/><stop offset="1" class="e873ol6-u"/></radialGradient><radialGradient id="iTQobNb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68288 2.79847 -2.9931 -9.28678 26.41 27.057)" gradientUnits="userSpaceOnUse"><stop class="ul7rmpbso"/><stop offset="1" class="ezu_a_bod"/></radialGradient><radialGradient id="iU4ghje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.19204 2.98189 0 11.2 30.422)" gradientUnits="userSpaceOnUse"><stop class="iqmfu1bfz"/><stop offset="1" class="b_ji9tgfr"/></radialGradient><radialGradient id="ieev1Be" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 3.29 12.855)" gradientUnits="userSpaceOnUse"><stop class="v74r7idhd"/><stop offset="1" class="hk_d6vbsx"/></radialGradient><radialGradient id="iPdFsSX" cx="0" cy="0" r="1" gradientTransform="rotate(-167.876 10.083 9.174)scale(10.3399 4.20474)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="dz4ncrwcz"/><stop offset="1" class="ou0802bre"/></radialGradient><radialGradient id="idrC3vb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.7286 12.06 15.767)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="pzn0rnkkd"/><stop offset="1" class="zpuae6b8t"/></radialGradient><radialGradient id="iLfeZed" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3731 -4.14332 0 19.323 20.759)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="f_gwqccqg"/><stop offset="1" class="ywfp1px4j"/></radialGradient><radialGradient id="iEhPgzW" cx="0" cy="0" r="1" gradientTransform="matrix(1.90434 4.58794 -4.92328 2.04353 18.373 20.46)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="zhvue1b_t"/><stop offset=".914" class="rq0vvgb8y"/></radialGradient><radialGradient id="icZpRzc" cx="0" cy="0" r="1" gradientTransform="matrix(2.08899 0 0 3.65575 11.674 14.18)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="itB1tfe" cx="0" cy="0" r="1" gradientTransform="matrix(.98411 -.71658 .81789 1.12324 25.428 13.865)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iRSKEVd" cx="0" cy="0" r="1" gradientTransform="matrix(.97763 -1.79814 1.05245 .5722 24.936 15.158)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iB7I16b" cx="0" cy="0" r="1" gradientTransform="matrix(.30866 .30552 -.39386 .3979 24.986 14.18)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iIhysoe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32584 12.52744 -11.96876 -1.26671 20.673 10.933)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="mx6r32s2r"/><stop offset=".835" class="a-e0cj8zq"/><stop offset="1" class="j61mf2btk"/></radialGradient><radialGradient id="iAg9Dtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.55595 1.91501 0 22.106 12.667)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iCeKrvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65569 2.059 0 16.68 12.627)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="imv2xpc" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 10.63 8.306)scale(6.6736 11.3491)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="i2ZhxGd" cx="0" cy="0" r="1" gradientTransform="rotate(-92.056 12.017 -1.875)scale(2.21733 1.08898)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="irHE7bc" cx="0" cy="0" r="1" gradientTransform="matrix(1.02272 -2.3409 1.90918 .83411 24.344 12.112)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iRw4xMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.18181 1.46641 -1.29473 1.04346 18.39 3.941)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iW73NSd" cx="0" cy="0" r="1" gradientTransform="rotate(76.961 7.59 14.639)scale(.957 1.5733)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="icg6x5b" cx="0" cy="0" r="1" gradientTransform="matrix(.86363 1.06818 -2.3934 1.93509 14.14 5.998)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="inApZ8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.07512 -1.27214 0 21.907 13.765)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ikPcffe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.116 1.436)scale(.45021 .61983)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1ABDeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.07517 -1.27221 0 16.713 13.765)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="icQtAyN" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.895 -1.244)scale(.58809 .70692)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iuFGkKb" x1="6.668" x2="6.668" y1="12.215" y2="10.512" gradientUnits="userSpaceOnUse"><stop class="mwk8f57wh"/><stop offset="1" class="ily2h4rfo"/></linearGradient><linearGradient id="ie4C6Gd" x1="3.27" x2="4.08" y1="9.099" y2="9.02" gradientUnits="userSpaceOnUse"><stop class="qe0h-qt8x"/><stop offset="1" class="je3tjybua"/></linearGradient><linearGradient id="iYVkYhb" x1="5.158" x2="4.207" y1="4.909" y2="6.695" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="icTIvIb" x1="6.579" x2="5.278" y1="4.48" y2="5.459" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="iwHEEMb" x1="8.338" x2="7.956" y1="5.08" y2="6.644" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="i8THhbc" x1="3.924" x2="4.344" y1="5.021" y2="7.629" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iDRd7Cb" x1="5.069" x2="5.281" y1="4.148" y2="7.272" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="i9TWeFc" x1="7.218" x2="8.32" y1="3.392" y2="7.068" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="ii26R7c" x1="8.173" x2="8.489" y1="4.341" y2="7.773" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iG1ir1G" x1="5.219" x2="4.127" y1="6.889" y2="6.82" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iZrOxFb" x1="6.491" x2="5.927" y1="6.717" y2="6.576" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iE39uUb" x1="7.992" x2="7.189" y1="6.53" y2="6.317" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iFhHSLb" x1="4.509" x2="8.884" y1="12.418" y2="12.418" gradientUnits="userSpaceOnUse"><stop class="w8p93gb0x"/><stop offset=".743" class="m--3robwq"/></linearGradient><linearGradient id="iYWwtwb" x1="6.779" x2="6.779" y1="11.832" y2="12.09" gradientUnits="userSpaceOnUse"><stop class="qp7m7zbwo"/><stop offset="1" class="va6027bik"/></linearGradient><linearGradient id="ikdde6c" x1="21.507" x2="5.77" y1="30.697" y2="12.855" gradientUnits="userSpaceOnUse"><stop class="cgidz9b8x"/><stop offset=".401" class="qxg6rvb4w"/></linearGradient><linearGradient id="iM5ETdd" x1="9.776" x2="10.507" y1="26.523" y2="21.697" gradientUnits="userSpaceOnUse"><stop offset=".1" class="nrwls_btk"/><stop offset="1" class="tilf7ac3p"/></linearGradient><linearGradient id="iwuBGed" x1="14.045" x2="13.306" y1="24.547" y2="23.152" gradientUnits="userSpaceOnUse"><stop offset=".35" class="lign7ubxp"/><stop offset=".794" class="iu5n-nb1z"/></linearGradient><linearGradient id="ihIPMGc" x1="7.305" x2="7.305" y1="12.855" y2="13.895" gradientUnits="userSpaceOnUse"><stop class="nwxnfd6vs"/><stop offset="1" class="uwkg4cb-r"/></linearGradient><linearGradient id="irpXAZw" x1="7.322" x2="13.072" y1="14.563" y2="22.844" gradientUnits="userSpaceOnUse"><stop class="rtxxuvbkk"/><stop offset="1" class="cm0qez-we"/></linearGradient><linearGradient id="iKsvIfe" x1="13.661" x2="12.898" y1="14.512" y2="14.512" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="icHuNdc" x1="26.279" x2="25.304" y1="12.881" y2="15.9" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="i5abtMb" x1="24.117" x2="15.026" y1="14.644" y2="15.999" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iMTHgUc" x1="12.89" x2="15.642" y1="17.853" y2="17.494" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iLhkIFc" x1="13.526" x2="16.981" y1="13.862" y2="7.726" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iYVxICe" x1="18.284" x2="19.401" y1="15.428" y2="15.428" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="i4Bg7Yc" x1="20.43" x2="19.209" y1="15.812" y2="15.795" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="ifMA2ye" x1="19.544" x2="19.544" y1="16.696" y2="16.014" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iQ4jbvb" x1="19.462" x2="19.462" y1="16.746" y2="16.547" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="ivQZWPb" x1="18.078" x2="18.596" y1="18.619" y2="17.8" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iNuIXgK" x1="22.832" x2="22.459" y1="13.432" y2="13.662" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1l75gc" x1="17.598" x2="17.225" y1="13.432" y2="13.662" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7iBSVb" x1="22.851" x2="22.351" y1="10.886" y2="9.863" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iBYdepO" x1="16.536" x2="15.121" y1="10.733" y2="10.139" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><filter id="ijk9Ayk" width=".423" height="2.22" x="4.765" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".05"/></filter><filter id="ieIeGYc" width=".345" height="2.572" x="6.32" y="4.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".05"/></filter><filter id="iKljonP" width=".509" height="1.681" x="7.797" y="4.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".05"/></filter><filter id="iSsAIod" width="1.556" height="3.487" x="3.631" y="4.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".2"/></filter><filter id="ifeORNb" width="1.2" height="3.889" x="5.316" y="3.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".2"/></filter><filter id="iOr0pQe" width="1.488" height="4.773" x="6.864" y="2.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".2"/></filter><filter id="i4IR22x" width="2.002" height="4.299" x="8.267" y="3.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".2"/></filter><filter id="i2KdCGe" width="1.412" height="1.358" x="3.921" y="6.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".1"/></filter><filter id="iuVBPKe" width="1.118" height=".999" x="5.57" y="6.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".1"/></filter><filter id="iphI3Hd" width="1.312" height="1.023" x="6.835" y="6.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".1"/></filter><filter id="igjxnbc" width="9.217" height="11.911" x="5.665" y="12.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".75"/></filter><filter id="inlMo4c" width="4.175" height="3.975" x="11.674" y="12.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3873"/></filter><filter id="iUaQ3Bc" width="3.369" height="3.369" x="11.976" y="12.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".25"/></filter><filter id="iQehykd" width="4.225" height="4.225" x="22.998" y="11.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3873"/></filter><filter id="iQn0deb" width="3.369" height="3.369" x="23.301" y="12.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".25"/></filter><filter id="igN583Q" width="12.349" height="14.568" x="13.173" y="7.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3873"/></filter><filter id="iMWD6Le" width="15.001" height="10.075" x="11.812" y="3.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3873"/></filter><filter id="icS7tde" width="3.595" height="4.692" x="17.231" y="12.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".375"/></filter><filter id="ic3e2Oe" width="2.734" height="3.692" x="17.946" y="13.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".125"/></filter><filter id="izPsGBe" width="3.499" height="2.153" x="20.72" y="9.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3873"/></filter><filter id="iTeeIeZ" width="3.5" height="2.153" x="14.592" y="9.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3873"/></filter><filter id="igYalIf" width=".898" height=".791" x="21.052" y="12.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".05"/></filter><filter id="iO5B1tb" width=".985" height="1.011" x="22.07" y="12.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".1"/></filter><filter id="icZebLd" width="1.098" height="1.162" x="16.783" y="12.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".1"/></filter><filter id="icRuede" width="1.049" height=".8" x="15.866" y="12.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".05"/></filter><filter id="i8tukAd" width="3.702" height="2.013" x="20.54" y="9.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".25"/></filter><filter id="i7zQ2fc" width="3.794" height="2.081" x="14.326" y="10.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3873" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-raising-hand-medium-light" /></template>
<style>
.a-e0cj8zq {
  stop-color: var(--svg-color--ba7e80, #BA7E80);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ap0ejfjaf {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.155 12.477c.777 0 1.434.536 1.613 1.26a.326.326 0 0 1-.319.406h-2.655a.274.274 0 0 1-.27-.324c.15-.763.82-1.342 1.631-1.342");
}

.b_ji9tgfr {
  stop-color: var(--svg-color--4496db, #4496DB);
  stop-opacity: 0;
}

.b6dgc3bep {
  d: path("M21.83 13.025c.077.101-.082.225-.261.36c-.18.134-.314.228-.39.127c-.075-.101.01-.292.19-.427c.18-.134.386-.161.462-.06");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bt9t76zok {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m25.05 6.469l.51.254c.894.444 1.405 1.46 1.213 2.54l-.702 3.618c-.063.374-.31.626-.681.635h-.022s.064-1.08.128-1.714c.052-.516-.038-.673-.51-1.143c-.256-.254-.448-.635-.448-1.016V8.628c0-.318-.255-.572-.51-.635c-.767-.19-2.363-.508-4.662-.508s-3.895.317-4.661.508a.62.62 0 0 0-.51.635v1.015c0 .381-.129.762-.448 1.016l-.191.19c-.256.191-.383.572-.383.89c.063.698.127 1.714.127 1.714l-.058-.002a.754.754 0 0 1-.708-.633l-.702-3.619c-.128-1.016.383-2.032 1.277-2.476l.51-.254c.32-.19.64-.444.958-.698l1.15-1.207c.702-.635 1.724-.825 2.618-.38a3.5 3.5 0 0 0 1.98 0c.957-.318 2.042-.064 2.809.634l.957.953c.256.317.575.508.958.698");
}

.cgidz9b8x {
  stop-color: var(--svg-color--38a2f1, #38A2F1);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm0qez-we {
  stop-color: var(--svg-color--56a6ff, #56A6FF);
  stop-opacity: 0;
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dwt__obip {
  d: path("M4.673 12.032c0-.11.09-.2.2-.2h3.811c.11 0 .2.09.2.2v1.714h-4.21z");
}

.dz4ncrwcz {
  stop-color: var(--svg-color--09538b, #09538B);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e873ol6-u {
  stop-color: var(--svg-color--3983b7, #3983B7);
  stop-opacity: 0;
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.ezu_a_bod {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
  stop-opacity: 0;
}

.f_gwqccqg {
  stop-color: var(--svg-color--ab747c, #AB747C);
}

.ft5dv1b6b {
  fill: none;
}

.g5d0dobpo {
  cx: 24.986px;
  cy: 14.18px;
  r: 1.184px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gj_pv9bgn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("M4.903 4.906L5.05 6.85");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gu3v_k24n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m8.168 5.077l-.234 1.407");
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.hk_d6vbsx {
  stop-color: var(--svg-color--3394d1, #3394D1);
  stop-opacity: 0;
}

.hkmkuhklj {
  d: path("M17.68 13.738c0-.343-.278-.572-.354-.641l-.343.332l.211.43z");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.i1fbwbbit {
  stop-color: var(--svg-color--cd8d5e, #CD8D5E);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i6vwvnf0x {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m4.229 4.545l.36 2.633");
}

.ily2h4rfo {
  stop-color: var(--svg-color--cf8a62, #CF8A62);
  stop-opacity: 0;
}

.iqmfu1bfz {
  stop-color: var(--svg-color--4496db, #4496DB);
}

.iu5n-nb1z {
  stop-color: var(--svg-color--2877cd, #2877CD);
  stop-opacity: 0;
}

.ixp34-bkk {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.687 17.47a.23.23 0 0 0-.277.049a.21.21 0 0 0-.023.273a2.3 2.3 0 0 0 1.926 1.029c.808 0 1.518-.412 1.926-1.03a.215.215 0 0 0-.024-.275a.23.23 0 0 0-.276-.045a3.5 3.5 0 0 1-1.626.385c-.596 0-1.156-.14-1.626-.385Z");
}

.j1aad2bix {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.528 4.476l-.07 2.297");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j61mf2btk {
  stop-color: var(--svg-color--9b7287, #9B7287);
}

.je3tjybua {
  stop-color: var(--svg-color--ffc3a0, #FFC3A0);
  stop-opacity: 0;
}

.jeoth2bte {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.464 12.477c-.777 0-1.434.536-1.612 1.26a.326.326 0 0 0 .318.406h2.656a.274.274 0 0 0 .27-.324a1.67 1.67 0 0 0-1.632-1.342");
}

.jfno0m0sa {
  stop-color: var(--svg-color--f2c4a1, #F2C4A1);
  stop-opacity: 0;
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.ju3xmq33r {
  cx: 16.39px;
  cy: 13.255px;
  rx: 0.464px;
  ry: 0.235px;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.kqp7atbzj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M21.29 10.77c.512-.09 1.51-.064 2.201.474");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l3ktvxsjr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.076 11.387c.39-.344 1.24-.706 2.294-.538");
}

.lc7szmbjn {
  stop-color: var(--svg-color--cd8d5e, #CD8D5E);
  stop-opacity: 0;
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lign7ubxp {
  stop-color: var(--svg-color--2790d8, #2790D8);
}

.lr-iuirkd {
  d: path("M3.606 8.918c-.125-1.921-.281-2.958-.328-3.64c-.035-.512.023-1.067.71-1.192c.599-.074.884.452.907.66c-.002-.2 0-.679 0-.804c0-.211.008-.977.86-.977c.6 0 .816.588.8.864c.01-.102.023-.414.035-.707c.019-.434.252-.99.946-.977c.597.039.793.613.765.977l-.117 1.867c.024-.188.103-.665.278-1.34s.701-.72.957-.684c.326.046.88.361.648 1.274c-.275 1.156-.462 2.644-.527 3.285c.324-.133.642-.413 1.001-.788c.36-.375.887-.383 1.184-.16c.34.293.522.967.12 1.37c-.463.425-2.13 2.405-2.958 3.394c-.229.292-.997.875-2.234.875c-2.203-.094-2.942-1.676-3.047-3.297");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.m--3robwq {
  stop-color: var(--svg-color--1b6b9f, #1B6B9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mwk8f57wh {
  stop-color: var(--svg-color--cf8a62, #CF8A62);
}

.mx6r32s2r {
  stop-color: var(--svg-color--d19984, #D19984);
  stop-opacity: 0;
}

.n-28zubdd {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.752 2.678l-.289 3.944");
}

.n08vq6wnt {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m18.858 13.84l-.633 2.024a.64.64 0 0 0 .62.832h.936a.644.644 0 0 0 .62-.832l-.633-2.024c-.136-.448-.768-.448-.91 0");
}

.n2lghubug {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
}

.nfql5kgcv {
  d: path("m25.05 6.469l.51.254c.894.444 1.405 1.46 1.213 2.54l-.702 3.618c-.063.374-.31.626-.681.635h-.022s.064-1.08.128-1.714c.052-.516-.038-.673-.51-1.143c-.256-.254-.448-.635-.448-1.016V8.628c0-.318-.255-.572-.51-.635c-.767-.19-2.363-.508-4.662-.508s-3.895.317-4.661.508a.62.62 0 0 0-.51.635v1.015c0 .381-.129.762-.448 1.016l-.191.19c-.256.191-.383.572-.383.89c.063.698.127 1.714.127 1.714l-.058-.002a.754.754 0 0 1-.708-.633l-.702-3.619c-.128-1.016.383-2.032 1.277-2.476l.51-.254c.32-.19.64-.444.958-.698l1.15-1.207c.702-.635 1.724-.825 2.618-.38a3.5 3.5 0 0 0 1.98 0c.957-.318 2.042-.064 2.809.634l.957.953c.256.317.575.508.958.698");
}

.nick4i1gd {
  stop-color: var(--svg-color--e5b38f, #E5B38F);
}

.nkqxn1-bm {
  stop-color: var(--svg-color--f2c4a1, #F2C4A1);
}

.nrwls_btk {
  stop-color: var(--svg-color--2a6bc6, #2A6BC6);
}

.nwxnfd6vs {
  stop-color: var(--svg-color--408dc5, #408DC5);
}

.o-9gnobjq {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
  stop-opacity: 0;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogs4x8_bh {
  stop-color: var(--svg-color--efb99b, #EFB99B);
  stop-opacity: 0;
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.ou0802bre {
  stop-color: var(--svg-color--1473af, #1473AF);
  stop-opacity: 0;
}

.p-m_1mbfg {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.916 3.59v3.088");
}

.pc1m58puw {
  cx: 24.985px;
  cy: 14.18px;
  r: 1.987px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.ppy479bpq {
  d: path("M7.666 13.783v5.172a2 2 0 0 0 1.38 1.901l4.182 1.363");
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pzn0rnkkd {
  stop-color: var(--svg-color--3473ab, #3473AB);
}

.qczyap8xv {
  fill: var(--svg-color--000, #000);
  d: path("M21.3 13.863c0-.338.271-.609.609-.609a.606.606 0 0 1 .54.889h-1.076a.55.55 0 0 1-.072-.28");
}

.qe0h-qt8x {
  stop-color: var(--svg-color--ffc3a0, #FFC3A0);
}

.qnynbebrn {
  stop-color: var(--svg-color--efb99b, #EFB99B);
}

.qp7m7zbwo {
  stop-color: var(--svg-color--186a98, #186A98);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxg6rvb4w {
  stop-color: var(--svg-color--268fd7, #268FD7);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.rc8ljf8lb {
  d: path("M19.323 23.96c-1.268 0-2.296-.985-2.296-2.2v-2.599c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.215-1.028 2.2-2.296 2.2");
}

.rlvwxbcbx {
  stop-color: var(--svg-color--cf9271, #CF9271);
  stop-opacity: 0;
}

.rq0vvgb8y {
  stop-color: var(--svg-color--d39f86, #D39F86);
}

.rtxxuvbkk {
  stop-color: var(--svg-color--56a6ff, #56A6FF);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s5yq33b3c {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.674 3.725L8.862 7.13");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sf99phbve {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.388 6.728c-.13.165-.332.3-.518.4");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t6_nkac4i {
  d: path("m18.681 20.965l-7.874 5.245a.66.66 0 0 0-.4-.48l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198V13.87c0-.564.425-1.015.935-1.015h4.13c.52 0 .935.461.935 1.015v3.985c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.tewa6_b_g {
  cx: 24.986px;
  cy: 14.18px;
  r: 1.184px;
}

.tilf7ac3p {
  stop-color: var(--svg-color--2a6bc6, #2A6BC6);
  stop-opacity: 0;
}

.tqethqbxe {
  fill: var(--svg-color--000, #000);
  d: path("M17.319 13.863a.606.606 0 0 0-.609-.609a.606.606 0 0 0-.54.889h1.076a.6.6 0 0 0 .073-.28");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.ttv30ab9m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.83 13.025c.077.101-.082.225-.261.36c-.18.134-.314.228-.39.127c-.075-.101.01-.292.19-.427c.18-.134.386-.161.462-.06");
}

.tvy-4obul {
  stop-color: var(--svg-color--c3806d, #C3806D);
}

.u0-3rvbpd {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m23.74 10.942l-.003-.003l-.005-.004l-.015-.011a2 2 0 0 0-.184-.128a3 3 0 0 0-.5-.251a3.4 3.4 0 0 0-1.777-.189a.635.635 0 1 0 .199 1.255c.473-.074.852.013 1.111.115a1.8 1.8 0 0 1 .367.197a.635.635 0 0 0 .808-.98");
}

.u1k6efbcx {
  d: path("M16.71 12.8a1.062 1.062 0 0 0-1.023 1.343h2.052q.037-.137.038-.28A1.07 1.07 0 0 0 16.71 12.8");
}

.u35dl1bhv {
  d: path("m18.858 13.84l-.633 2.024a.64.64 0 0 0 .62.832h.936a.644.644 0 0 0 .62-.832l-.633-2.024c-.136-.448-.768-.448-.91 0");
}

.u62ixwbju {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.847 6.536c-.13.165-.501.36-.712.423");
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ul7rmpbso {
  stop-color: var(--svg-color--4ab7ff, #4AB7FF);
}

.uuvxkpb6m {
  cx: 16.39px;
  cy: 13.255px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.464px;
  ry: 0.235px;
}

.uwkg4cb-r {
  stop-color: var(--svg-color--408dc5, #408DC5);
  stop-opacity: 0;
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v2dqj6bfb {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m18.985 14.035l-.976 2.023c-.122.416.169.832.58.832h.878c.412 0 .702-.422.581-.832l-.593-2.023c-.127-.448-.337-.448-.47 0");
}

.v46okmbvl {
  cx: 13.661px;
  cy: 14.18px;
  r: 1.184px;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v74r7idhd {
  stop-color: var(--svg-color--3394d1, #3394D1);
}

.v7boqxhcs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M4.221 7.693c.11-.062.617-.379.813-.757");
}

.va6027bik {
  stop-color: var(--svg-color--186a98, #186A98);
  stop-opacity: 0;
}

.vpa8ubcez {
  stop-color: var(--svg-color--e1a88d, #E1A88D);
}

.vrs9uvb1p {
  stop-color: var(--svg-color--ca895a, #CA895A);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vt1vh9b2m {
  d: path("M22.855 13.723a1 1 0 0 0-.275-.55l-.31.339l.14.271z");
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w8p93gb0x {
  stop-color: var(--svg-color--3688bf, #3688BF);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.ww6kpos8t {
  d: path("M21.909 12.8a1.062 1.062 0 0 1 1.023 1.343h-2.051a1.066 1.066 0 0 1 1.028-1.342");
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xm75ajb4k {
  cx: 13.661px;
  cy: 14.18px;
  r: 1.987px;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yfgdr3b5p {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m14.82 10.943l.002-.001l.003-.003l.005-.004l.014-.011a2 2 0 0 1 .185-.128c.118-.075.287-.167.5-.251a3.4 3.4 0 0 1 1.776-.189a.635.635 0 1 1-.198 1.255a2.1 2.1 0 0 0-1.111.115a1.8 1.8 0 0 0-.367.197a.635.635 0 0 1-.808-.98");
}

.ygz6o7bgm {
  d: path("m13.242 13.45l.058.003s-.063-1.016-.127-1.714c0-.318.127-.699.383-.89l.191-.19c.32-.254.447-.635.447-1.016V8.628c0-.318.192-.572.511-.635c.766-.19 2.363-.508 4.661-.508c2.3 0 3.895.317 4.662.508c.255.063.51.317.51.635v1.015c0 .381.192.762.447 1.016c.598.42.56.65.511 1.143a55 55 0 0 0-.127 1.714h.021l-.316 4.712c-.191 2.107-1.848 3.575-3.822 3.575H17.43c-2.038 0-3.63-1.468-3.821-3.575z");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.ywfp1px4j {
  stop-color: var(--svg-color--b78178, #B78178);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zen3jbcth {
  stop-color: var(--svg-color--3983b7, #3983B7);
}

.zhvue1b_t {
  stop-color: var(--svg-color--d39f86, #D39F86);
  stop-opacity: 0;
}

.zhwoeykns {
  stop-color: var(--svg-color--ca895a, #CA895A);
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zpuae6b8t {
  stop-color: var(--svg-color--127cc2, #127CC2);
  stop-opacity: 0;
}

.zxmocx6ig {
  d: path("M20.288 20.855h.97c2.49 0 7.472 3.5 7.472 9H10.797v-3.5a.67.67 0 0 0-.414-.625L7.31 24.355c-2.49-1-3.487-3.5-3.487-5.198V13.87c0-.564.424-1.015.932-1.015h4.114c.518 0 .932.461.932 1.015v3.985c0 1.302.996 1.5.996 1.5l5.978 1.5z");
}

</style>
