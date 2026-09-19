<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#id4kA8c)" class="f44xcqfni"/><g filter="url(#iBCLtcb)"><path fill="url(#iGtg3he)" class="t3--j5bga"/><path fill="url(#iBe9zNd)" class="t3--j5bga"/></g><path fill="url(#i0yySkc)" class="ya3n-2bve"/><g filter="url(#iYGHQBc)"><path fill="url(#i08C1Rd)" class="zc8ra3ejp"/></g><path fill="url(#ir9UGGc)" class="yd4ohcbkp"/><path fill="url(#iayx3yi)" class="yd4ohcbkp"/><path fill="url(#iMc5nAc)" class="yd4ohcbkp"/><path fill="url(#ieXxwRd)" class="yd4ohcbkp"/><path fill="url(#iDbI4Gd)" class="yd4ohcbkp"/><path fill="url(#ieexiPb)" class="yd4ohcbkp"/><path fill="url(#i5BMpsm)" class="yd4ohcbkp"/><path fill="url(#iAuEgMd)" class="yd4ohcbkp"/><path fill="url(#ieCAmgd)" class="eg-zrqbbw"/><path fill="url(#iFksbec)" class="eg-zrqbbw"/><path fill="url(#ipc6bgy)" class="ss9ml3bse"/><path fill="url(#iXG9kFc)" class="ss9ml3bse"/><path fill="url(#i3XLnOx)" class="ss9ml3bse"/><path fill="url(#igrm2Zc)" class="ccqf-acug"/><path fill="url(#ixNK0yE)" class="ccqf-acug"/><path fill="url(#imLwHGb)" class="ccqf-acug"/><g filter="url(#izFaKwc)"><path class="dyw70ubbw"/></g><g filter="url(#inmsgAc)"><path class="k23bu8bhi"/></g><path class="fpnr3nb3u"/><g filter="url(#iPTHkKd)"><path class="icnkybd-m"/></g><g filter="url(#iKus7id)"><path fill="url(#i0kvOWd)" class="gjjy9fb6v"/><path fill="url(#ikDGtdd)" class="gjjy9fb6v"/><path fill="url(#ifBNLgd)" class="gjjy9fb6v"/></g><g filter="url(#i2drUlb)"><path fill="url(#iYfuJ3Y)" class="ja9xhwbfv"/></g><g filter="url(#ik5tuLV)"><path fill="url(#iqzxjCb)" class="hp042yb8a"/></g><path fill="url(#iMaKQOc)" class="hp042yb8a"/><path fill="url(#iR2Ry0d)" class="hp042yb8a"/><path fill="url(#iLANQVP)" class="hp042yb8a"/><path fill="url(#igd5pie)" class="hp042yb8a"/><path fill="url(#iDM8y5d)" class="hp042yb8a"/><path fill="url(#iKBLQ5c)" class="hp042yb8a"/><path fill="url(#iPYBrJb)" class="hp042yb8a"/><path class="jf64hac-x"/><path fill="url(#iUmuJ4b)" class="uarfs1nvj"/><path fill="url(#i8L2Z3p)" class="uarfs1nvj"/><path fill="url(#i7hLObb)" class="uarfs1nvj"/><path fill="url(#i4SQfue)" class="go_hcsbdb"/><path fill="url(#ilqXxxB)" class="go_hcsbdb"/><path fill="url(#i3a9m8b)" class="go_hcsbdb"/><path fill="url(#iY3cvUy)" class="hon_u6n-c"/><path fill="url(#imaHtBb)" class="hon_u6n-c"/><g filter="url(#iNF7W2c)"><path stroke="url(#ihIlxcb)" class="osxbsq6gx"/></g><path class="d4nqttb2n"/><path class="s5279o3ha"/><path class="ljchh6cjg"/><g filter="url(#ixoMPud)"><path fill="url(#iH1DeHc)" class="vsyzp2bxj"/><path fill="url(#iZpUVKc)" class="vsyzp2bxj"/></g><g filter="url(#ihQ2WEe)"><path fill="url(#i1Q5PGb)" class="b9ovt-b8n"/><path fill="url(#iw18snb)" class="b9ovt-b8n"/></g><path clip-rule="evenodd" class="f04mv2bop"/><path fill="url(#iip8Wcc)" clip-rule="evenodd" class="l1z-2_-xs"/><path clip-rule="evenodd" class="wvbza2eye"/><path fill="url(#ifDk9pI)" clip-rule="evenodd" class="px8a23bzh"/><path fill="url(#iX6QJub)" clip-rule="evenodd" class="i--at434j"/><path clip-rule="evenodd" class="yhu-j5byc"/><path fill="url(#imWQINe)" clip-rule="evenodd" class="fgx8jdcge"/><g filter="url(#iP3PmJc)"><path class="e8jz-xbdz"/></g><path fill="url(#iZpASye)" class="ef1xzqbkt"/><path fill="url(#i3tm7dd)" class="ef1xzqbkt"/><path fill="url(#iDAdAhb)" class="ef1xzqbkt"/><path fill="url(#izAODKe)" class="ef1xzqbkt"/><g filter="url(#i2BdoQd)"><path stroke="url(#iZ72OHb)" class="fpdhhs1to"/></g><g filter="url(#iEGha0c)"><path stroke="url(#iGfuDPc)" class="nhjnhub6s"/></g><g filter="url(#iCOKlPd)"><path stroke="url(#iYARn8c)" class="y8q4s599i"/></g><g filter="url(#iAF2mMc)"><path class="ksrftlb6p"/></g><g filter="url(#icxG77j)"><path class="ecp7aibdh"/><path fill="url(#iW8FOLc)" class="spzd9kgpv"/><path fill="url(#iUjkw2d)" class="spzd9kgpv"/><path fill="url(#i5Vh0bb)" class="spzd9kgpv"/><path fill="url(#iqCjjHe)" class="spzd9kgpv"/><path fill="url(#iglarwx)" class="spzd9kgpv"/></g><path class="w75s09kgl"/><path fill="url(#ie6Qoqc)" class="mplulyb8g"/><path class="nna-exbrs"/><g filter="url(#iE07jkd)"><path class="gqk1oq8vx"/><path fill="url(#iRv5O9d)" class="s0w2dj02n"/></g><g filter="url(#ii87gYb)"><path fill="url(#ioggciZ)" class="ys8_95bug"/></g><path class="tokp2q_9y"/><path fill="url(#irFiQcd)" class="f46he3n7b"/><path class="pbkbtxb-e"/><g filter="url(#i2eWSFe)"><path fill="url(#i26arvn)" class="fpeu3cbza"/></g><g filter="url(#iYVnC1d)"><ellipse transform="rotate(-27.914 13.508 9.965)" class="jn8atjbpi"/><ellipse fill="url(#iTZl2lb)" transform="rotate(-27.914 13.508 9.965)" class="dbsvo228g"/></g><defs><radialGradient id="id4kA8c" cx="0" cy="0" r="1" gradientTransform="matrix(3.93792 -7.29125 14.315 7.73138 20.553 16.756)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="1" class="gdsiwyiyr"/></radialGradient><radialGradient id="iGtg3he" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92122 7.06151 -2.22108 -.91882 27.573 12.23)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jpxim8b1x"/><stop offset="1" class="n52c8qgao"/></radialGradient><radialGradient id="iBe9zNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 4.15626 -.42744 -.1607 27.323 12.7)" gradientUnits="userSpaceOnUse"><stop class="fg6i_oqme"/><stop offset="1" class="ih2ibv29b"/></radialGradient><radialGradient id="i0yySkc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58397 -6.61442 12.98618 -8.99977 12.493 17.032)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="0" class="pxp9rxlhv"/><stop offset="1" class="e06hnni3m"/></radialGradient><radialGradient id="iayx3yi" cx="0" cy="0" r="1" gradientTransform="rotate(-118.874 16.521 8.48)scale(12.4902 33.343)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="f6lcb9bkn"/><stop offset="1" class="jtbt9y0gz"/></radialGradient><radialGradient id="iMc5nAc" cx="0" cy="0" r="1" gradientTransform="rotate(-65.133 29.228 1.607)scale(12.2618 28.8332)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="r21k1wzrc"/><stop offset="1" class="b2cn2_uce"/></radialGradient><radialGradient id="ieXxwRd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71875 0 0 -14.5625 23.292 23.325)" gradientUnits="userSpaceOnUse"><stop class="odfe47amh"/><stop offset="1" class="carxtabzu"/></radialGradient><radialGradient id="iDbI4Gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6875 -.22656 0 19.206 16.73)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="z8m-hreok"/><stop offset="1" class="ehu1o5vid"/></radialGradient><radialGradient id="ieexiPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 3.5 -5.72433 -1.89104 12.667 16.356)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="a75cnrb-k"/><stop offset="1" class="ri_i1lblj"/></radialGradient><radialGradient id="ieCAmgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6045 2.48458 0 23.855 29.95)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="vbb18ixfb"/><stop offset="1" class="p5bq_2b9f"/></radialGradient><radialGradient id="iFksbec" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5781 .52466 0 23.11 29.95)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l0d7sccpf"/><stop offset="1" class="r3f5xvbmj"/></radialGradient><radialGradient id="ipc6bgy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.2188 2.95614 0 7.292 29.95)" gradientUnits="userSpaceOnUse"><stop class="oj4dw6cda"/><stop offset="1" class="jsbpdr4yj"/></radialGradient><radialGradient id="iXG9kFc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21875 0 0 -14.5625 8.542 29.48)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ihp7x-bon"/><stop offset="1" class="g_z46f3jl"/></radialGradient><radialGradient id="i0kvOWd" cx="0" cy="0" r="1" gradientTransform="rotate(57.496 -7.284 21.838)scale(4.18715 6.17567)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="xksrntfob"/><stop offset="1" class="pu1_ubb-e"/></radialGradient><radialGradient id="ikDGtdd" cx="0" cy="0" r="1" gradientTransform="matrix(.375 3.375 -7.05108 .78345 14.73 14.356)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="jzwike70j"/><stop offset="1" class="gbck5ebgo"/></radialGradient><radialGradient id="ifBNLgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87568 -2.6343 0 15.948 16.387)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="uxwciubxp"/><stop offset="1" class="kqp3z9b3n"/></radialGradient><radialGradient id="iqzxjCb" cx="0" cy="0" r="1" gradientTransform="rotate(147.066 8.155 7.33)scale(6.62758 6.4385)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="xbzsco1zl"/><stop offset="1" class="ui505nlmt"/></radialGradient><radialGradient id="iMaKQOc" cx="0" cy="0" r="1" gradientTransform="matrix(4.7006 -4.8896 .69774 .67077 10.721 6.83)" gradientUnits="userSpaceOnUse"><stop class="v6in1309f"/><stop offset="1" class="irlvk16yo"/></radialGradient><radialGradient id="iR2Ry0d" cx="0" cy="0" r="1" gradientTransform="matrix(2.99475 -2.09375 1.42285 2.03514 18.172 5.746)" gradientUnits="userSpaceOnUse"><stop class="yafzpfb5d"/><stop offset="1" class="zw8obf2yu"/></radialGradient><radialGradient id="iLANQVP" cx="0" cy="0" r="1" gradientTransform="matrix(4.28125 -6.34375 6.82732 4.6076 15.328 11.278)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="v0b1ehlvd"/><stop offset=".976" class="zbra2iiyy"/></radialGradient><radialGradient id="igd5pie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.46875 15.0153 0 15.944 17.074)" gradientUnits="userSpaceOnUse"><stop class="coha3f57o"/><stop offset="1" class="sxf6ctbxu"/></radialGradient><radialGradient id="iDM8y5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1 5.96164 0 15.944 17.356)" gradientUnits="userSpaceOnUse"><stop class="d4rdiyhnm"/><stop offset="1" class="cjqaktb2p"/></radialGradient><radialGradient id="iKBLQ5c" cx="0" cy="0" r="1" gradientTransform="matrix(.09375 -1.375 1.65495 .11284 18.516 9.746)" gradientUnits="userSpaceOnUse"><stop class="dpu7pkxix"/><stop offset="1" class="ikzxr830v"/></radialGradient><radialGradient id="iPYBrJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.4375 1.59375 0 13.797 9.487)" gradientUnits="userSpaceOnUse"><stop class="cjca-p9bb"/><stop offset="1" class="xkba2oejb"/></radialGradient><radialGradient id="iUmuJ4b" cx="0" cy="0" r="1" gradientTransform="rotate(135.269 9.646 6.278)scale(4.70673 6.16305)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="glx9rn1kk"/><stop offset="1" class="st-pambja"/></radialGradient><radialGradient id="i8L2Z3p" cx="0" cy="0" r="1" gradientTransform="rotate(-139.028 6.6 1.066)scale(3.14556 5.45202)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="n_d3gr2_k"/><stop offset="1" class="st-pambja"/></radialGradient><radialGradient id="i7hLObb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.24277 -3.79959 0 15.935 2.05)" gradientUnits="userSpaceOnUse"><stop class="y465w_bjd"/><stop offset="1" class="d6o1i3elf"/></radialGradient><radialGradient id="ilqXxxB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0193 1.125 -.25102 -.22744 23.316 7.793)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="u6c9fccih"/><stop offset="1" class="i4ydmtein"/></radialGradient><radialGradient id="imaHtBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.29688 .47656 -2.49611 -1.55496 10.48 8.38)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="druknjb2h"/><stop offset="1" class="vs77n03cp"/></radialGradient><radialGradient id="iH1DeHc" cx="0" cy="0" r="1" gradientTransform="matrix(1.59772 -1.40625 .5978 .67918 20.98 10.325)" gradientUnits="userSpaceOnUse"><stop class="rglphuhmg"/><stop offset="1" class="fyc1bbcaj"/></radialGradient><radialGradient id="iZpUVKc" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.0625 .1101 1.101 20.86 10.73)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="kn-2pccmm"/><stop offset="1" class="mrkz_8b_u"/></radialGradient><radialGradient id="i1Q5PGb" cx="0" cy="0" r="1" gradientTransform="rotate(-132.082 7.741 2.723)scale(2.41247 2.17677)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="z256j7ndo"/><stop offset="1" class="ckmg8ibfr"/></radialGradient><radialGradient id="iw18snb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18123 .63382 -1.16713 -2.17513 11.01 9.78)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="l7o55475l"/><stop offset="1" class="e1xn34b4b"/></radialGradient><radialGradient id="iZpASye" cx="0" cy="0" r="1" gradientTransform="matrix(0 1 -6.0416 0 15.99 2.825)" gradientUnits="userSpaceOnUse"><stop class="p9pt_iv8l"/><stop offset="1" class="i30ki7brg"/></radialGradient><radialGradient id="i3tm7dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45508 3.06778 0 15.99 5.686)" gradientUnits="userSpaceOnUse"><stop class="d__zvs94x"/><stop offset="1" class="exhvt3bml"/></radialGradient><radialGradient id="iDAdAhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -2.6875 1.35972 .82215 12.266 6.637)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="ii6mzr5ev"/><stop offset="1" class="wolfrvf5u"/></radialGradient><radialGradient id="izAODKe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18749 -3.4375 1.7319 -1.1021 20.125 7.653)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="ii6mzr5ev"/><stop offset="1" class="wolfrvf5u"/></radialGradient><radialGradient id="iUjkw2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2259 -.76773 0 16.433 12.378)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iqCjjHe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69327 .69415 -1.05674 -2.57775 16.55 11.851)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="ie6Qoqc" cx="0" cy="0" r="1" gradientTransform="rotate(-117.266 12.23 -.38)scale(.57126 .90459)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iRv5O9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.92 10.144)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="irFiQcd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26172 -.50781 .80412 -.41444 13.803 10.316)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iTZl2lb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.807 -1.502)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><linearGradient id="i08C1Rd" x1="5.54" x2="8.863" y1="11.987" y2="18.355" gradientUnits="userSpaceOnUse"><stop class="imlbmc2sy"/><stop offset="1" class="h7wwwp44w"/></linearGradient><linearGradient id="ir9UGGc" x1="15.935" x2="15.935" y1="15.575" y2="29.95" gradientUnits="userSpaceOnUse"><stop class="plsegxa8t"/><stop offset="1" class="dbg8b7bda"/></linearGradient><linearGradient id="i5BMpsm" x1="8.661" x2="8.938" y1="29.95" y2="29.95" gradientUnits="userSpaceOnUse"><stop class="rq6u1obxj"/><stop offset="1" class="yomd27bxe"/></linearGradient><linearGradient id="iAuEgMd" x1="23.206" x2="22.776" y1="29.95" y2="29.95" gradientUnits="userSpaceOnUse"><stop offset=".136" class="i0lopbdha"/><stop offset="1" class="w11i7m31i"/></linearGradient><linearGradient id="i3XLnOx" x1="8.759" x2="7.51" y1="28.762" y2="28.762" gradientUnits="userSpaceOnUse"><stop class="k6ta6mb-r"/><stop offset="1" class="drixk4bdm"/></linearGradient><linearGradient id="igrm2Zc" x1="15.939" x2="15.939" y1="20.918" y2="29.95" gradientUnits="userSpaceOnUse"><stop class="zajm34fcf"/><stop offset="1" class="puh_1hb6q"/></linearGradient><linearGradient id="ixNK0yE" x1="15.939" x2="15.939" y1="29.95" y2="27.293" gradientUnits="userSpaceOnUse"><stop class="ou_12nqfl"/><stop offset="1" class="ypzxpcc2j"/></linearGradient><linearGradient id="imLwHGb" x1="19.542" x2="17.698" y1="28.762" y2="28.762" gradientUnits="userSpaceOnUse"><stop offset=".119" class="zxxizob4i"/><stop offset="1" class="u7u0nyv_w"/></linearGradient><linearGradient id="iYfuJ3Y" x1="15.935" x2="15.935" y1="17.84" y2="25.869" gradientUnits="userSpaceOnUse"><stop class="gmn9ea1yo"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="i4SQfue" x1="21.542" x2="22.417" y1="8.418" y2="11.106" gradientUnits="userSpaceOnUse"><stop class="t0vl4obzm"/><stop offset="1" class="cy4cy6bws"/></linearGradient><linearGradient id="i3a9m8b" x1="21.862" x2="22.131" y1="8.16" y2="8.582" gradientUnits="userSpaceOnUse"><stop class="gov8w8rhe"/><stop offset="1" class="qg2f7w0bc"/></linearGradient><linearGradient id="iY3cvUy" x1="8.979" x2="11.385" y1="10.512" y2="9.512" gradientUnits="userSpaceOnUse"><stop class="g-cxxi1ky"/><stop offset="1" class="wnse4gbor"/></linearGradient><linearGradient id="ihIlxcb" x1="15.948" x2="15.948" y1="14.692" y2="14.27" gradientUnits="userSpaceOnUse"><stop class="pgeb39bto"/><stop offset="1" class="mo1945_5k"/></linearGradient><linearGradient id="iip8Wcc" x1="16.351" x2="16.479" y1="19.098" y2="19.707" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="ifDk9pI" x1="15.546" x2="15.417" y1="19.098" y2="19.707" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iX6QJub" x1="12.448" x2="14.433" y1="8.461" y2="7.762" gradientUnits="userSpaceOnUse"><stop class="bq_0jebkw"/><stop offset="1" class="kjjvcb6je"/><stop offset="1" class="wasds5b8d"/></linearGradient><linearGradient id="imWQINe" x1="19.43" x2="17.445" y1="8.461" y2="7.762" gradientUnits="userSpaceOnUse"><stop class="bq_0jebkw"/><stop offset="1" class="kjjvcb6je"/><stop offset="1" class="wasds5b8d"/></linearGradient><linearGradient id="iZ72OHb" x1="16.042" x2="20.276" y1="5.371" y2="4.137" gradientUnits="userSpaceOnUse"><stop offset=".164" class="a0m3qtb0g"/><stop offset=".481" class="y8ovvibws"/><stop offset=".742" class="aplh-7tkj"/></linearGradient><linearGradient id="iGfuDPc" x1="14.057" x2="12.174" y1="7.789" y2="8.16" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></linearGradient><linearGradient id="iYARn8c" x1="19.439" x2="16.973" y1="8.149" y2="7.94" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></linearGradient><linearGradient id="iW8FOLc" x1="16.805" x2="15.966" y1="11.743" y2="11.781" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i5Vh0bb" x1="15.966" x2="15.966" y1="12.798" y2="12.367" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iglarwx" x1="15.966" x2="15.966" y1="10.294" y2="10.8" gradientUnits="userSpaceOnUse"><stop class="je0hzjbmv"/><stop offset="1" class="l017if5vv"/></linearGradient><linearGradient id="ioggciZ" x1="18.887" x2="18.63" y1="10.122" y2="10.287" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="i26arvn" x1="14.524" x2="14.21" y1="10.114" y2="10.308" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><filter id="iBCLtcb" width="4.702" height="8.2" x="22.301" y="11.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1223"/></filter><filter id="iYGHQBc" width="4.902" height="8.4" x="5.146" y="10.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.321569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1223"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1223" result="effect2_innerShadow_4002_1223"/></filter><filter id="izFaKwc" width="6.968" height="4.815" x="12.464" y="15.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".25"/></filter><filter id="inmsgAc" width="1.583" height="3.273" x="10.143" y="11.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.258824 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1223"/></filter><filter id="iPTHkKd" width="6.431" height="9.028" x="12.527" y="17.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".25"/></filter><filter id="iKus7id" width="6.43" height="4.46" x="12.733" y="15.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.835294 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1223"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.733333 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1223" result="effect2_innerShadow_4002_1223"/></filter><filter id="i2drUlb" width="5.531" height="8.006" x="13.219" y="18.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.705882 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1223"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.670588 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1223" result="effect2_innerShadow_4002_1223"/></filter><filter id="ik5tuLV" width="11.095" height="12.422" x="10.721" y="4.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.443137 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1223"/></filter><filter id="iNF7W2c" width="3.566" height="1.546" x="14.165" y="13.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".05"/></filter><filter id="ixoMPud" width="2.098" height="3.68" x="20.73" y="8.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".125"/></filter><filter id="ihQ2WEe" width="2.017" height="3.595" x="9.092" y="8.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".1"/></filter><filter id="iP3PmJc" width="12.683" height="5.723" x="9.648" y="2.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1223"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1223" result="effect2_innerShadow_4002_1223"/></filter><filter id="i2BdoQd" width="6.906" height="3.493" x="15.313" y="3.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".25"/></filter><filter id="iEGha0c" width="2.177" height=".868" x="12.199" y="7.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".075"/></filter><filter id="iCOKlPd" width="2.177" height=".868" x="17.488" y="7.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".075"/></filter><filter id="iAF2mMc" width="3.57" height="4.684" x="13.846" y="9.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".5"/></filter><filter id="icxG77j" width="2.279" height="3.084" x="14.827" y="9.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".1"/></filter><filter id="iE07jkd" width=".787" height=".697" x="17.412" y="9.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".05"/></filter><filter id="ii87gYb" width=".892" height=".914" x="18.253" y="9.696" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".1"/></filter><filter id="i2eWSFe" width=".987" height="1.041" x="13.807" y="9.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".1"/></filter><filter id="iYVnC1d" width=".914" height=".705" x="13.052" y="9.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1223" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-vampire-medium" /></template>
<style>
.a0m3qtb0g {
  stop-color: var(--svg-color--505050, #505050);
}

.a75cnrb-k {
  stop-color: var(--svg-color--47374c, #47374C);
}

.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.b2cn2_uce {
  stop-color: var(--svg-color--60506b, #60506B);
}

.b9ovt-b8n {
  d: path("m10.778 9.324l.062 1.134l.069 1.24c-1.076-.865-1.498-2.122-1.615-2.947c-.028-.2.19-.318.355-.204z");
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bq_0jebkw {
  stop-color: var(--svg-color--281c22, #281C22);
}

.carxtabzu {
  stop-color: var(--svg-color--604f70, #604F70);
  stop-opacity: 0;
}

.ccqf-acug {
  d: path("M12.733 29.95V16.057a10.7 10.7 0 0 1 3.183-.482a10.7 10.7 0 0 1 3.23.496V29.95z");
}

.cjca-p9bb {
  stop-color: var(--svg-color--8c5c61, #8C5C61);
}

.cjqaktb2p {
  stop-color: var(--svg-color--a66a98, #A66A98);
  stop-opacity: 0;
}

.ckmg8ibfr {
  stop-color: var(--svg-color--835a60, #835A60);
}

.coha3f57o {
  stop-color: var(--svg-color--995c81, #995C81);
}

.cy4cy6bws {
  stop-color: var(--svg-color--b1867a, #B1867A);
}

.d__zvs94x {
  stop-color: var(--svg-color--21132a, #21132A);
}

.d4nqttb2n {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M14.513 13.45a2.94 2.94 0 0 0 2.87 0c.077-.042.17.023.143.106c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.083.066-.148.143-.106");
}

.d4rdiyhnm {
  stop-color: var(--svg-color--a66a98, #A66A98);
}

.d6o1i3elf {
  stop-color: var(--svg-color--404040, #404040);
  stop-opacity: 0;
}

.dbg8b7bda {
  stop-color: var(--svg-color--553d71, #553D71);
}

.dbsvo228g {
  cx: 13.508px;
  cy: 9.965px;
  rx: 0.39px;
  ry: 0.197px;
}

.dpu7pkxix {
  stop-color: var(--svg-color--ab7870, #AB7870);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.druknjb2h {
  stop-color: var(--svg-color--5e3c33, #5E3C33);
}

.dyw70ubbw {
  fill: var(--svg-color--bb172a, #BB172A);
  d: path("M12.964 19.832v-3.485h5.968v3.387c0 .374-.216.56-.721.322c-.685-.322-2.277-1.5-2.277-1.5s-1.793 1.288-2.23 1.482c-.438.195-.74.168-.74-.206");
}

.e06hnni3m {
  stop-color: var(--svg-color--e73665, #E73665);
}

.e1xn34b4b {
  stop-color: var(--svg-color--8c6660, #8C6660);
}

.e8jz-xbdz {
  fill: var(--svg-color--1f1e1d, #1F1E1D);
  d: path("M21.153 8.547c-.01-2.238-1.441-3.281-2.21-3.54c-.872-.29-1.484-.263-1.917-.074c-.418.182-.565.53-.695.836l-.014.035c-.14.326-.614.302-.742 0l-.014-.035c-.13-.307-.277-.654-.695-.836c-.434-.19-1.067-.217-1.938.075c-.763.255-2.14 1.27-2.186 3.48c-.276-.21-.66-.662-.764-1.382c-.139-.975.218-1.366.728-1.926q.095-.103.194-.215l.032-.036c.62-.7 1.864-2.104 3.937-2.104h2.241c2.073 0 3.317 1.403 3.937 2.104l.032.036l.194.215c.51.56.867.951.728 1.926c-.114.797-.574 1.266-.848 1.441");
}

.ecp7aibdh {
  fill: var(--svg-color--a2756d, #A2756D);
  d: path("m15.584 10.458l-.532 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.ef1xzqbkt {
  d: path("M21.153 8.547c-.01-2.238-1.441-3.281-2.21-3.54c-.872-.29-1.484-.263-1.917-.074c-.418.182-.565.53-.695.836l-.014.035c-.14.326-.614.302-.742 0l-.014-.035c-.13-.307-.277-.654-.695-.836c-.434-.19-1.067-.217-1.938.075c-.763.255-2.14 1.27-2.186 3.48c-.276-.21-.66-.662-.764-1.382c-.139-.975.218-1.366.728-1.926q.095-.103.194-.215l.032-.036c.62-.7 1.864-2.104 3.937-2.104h2.241c2.073 0 3.317 1.403 3.937 2.104l.032.036l.194.215c.51.56.867.951.728 1.926c-.114.797-.574 1.266-.848 1.441");
}

.eg-zrqbbw {
  d: path("M23.11 18.345V29.95h3.762v-3.235c0-3.295-1.456-6.31-3.761-8.37");
}

.ehu1o5vid {
  stop-color: var(--svg-color--47304f, #47304F);
  stop-opacity: 0;
}

.exhvt3bml {
  stop-color: var(--svg-color--21132a, #21132A);
  stop-opacity: 0;
}

.f04mv2bop {
  fill: var(--svg-color--decee7, #DECEE7);
  fill-rule: evenodd;
  d: path("M16.458 19.1a.125.125 0 0 1 .141.106l.649 4.672a.125.125 0 1 1-.248.034l-.648-4.672a.125.125 0 0 1 .106-.14");
}

.f1lm8sbjk {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
}

.f44xcqfni {
  d: path("M26.478 11.547c-2.243-2.143-5.051-3.376-6.334-3.816l-4.062 12.312h5.89c2.916-1.118 4.431-4.528 4.986-6.894a1.68 1.68 0 0 0-.48-1.602");
}

.f46he3n7b {
  d: path("M13.778 9.583a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.f6lcb9bkn {
  stop-color: var(--svg-color--56475f, #56475F);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fg6i_oqme {
  stop-color: var(--svg-color--574b64, #574B64);
}

.fgx8jdcge {
  fill-rule: evenodd;
  d: path("M17.74 8.07c.717-.133 1.346.18 1.57.343a.25.25 0 1 0 .294-.404c-.292-.212-1.059-.597-1.955-.43a.25.25 0 0 0 .092.491");
}

.fpdhhs1to {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M15.964 5.418c.182-.536.734-1.453 1.953-1.61c1.394-.178 3.043 1.114 3.652 2.177");
}

.fpeu3cbza {
  d: path("M14.594 10.371c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.fpnr3nb3u {
  fill: var(--svg-color--1e1c21, #1E1C21);
  d: path("m21.722 12.727l.03-1.145H20.37v3.274c1.125-.524 1.354-1.603 1.352-2.13");
}

.ft5dv1b6b {
  fill: none;
}

.fyc1bbcaj {
  stop-color: var(--svg-color--a17164, #A17164);
}

.g_z46f3jl {
  stop-color: var(--svg-color--655578, #655578);
}

.g-cxxi1ky {
  stop-color: var(--svg-color--7e5e52, #7E5E52);
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gbck5ebgo {
  stop-color: var(--svg-color--a99494, #A99494);
  stop-opacity: 0;
}

.gdsiwyiyr {
  stop-color: var(--svg-color--e82e5c, #E82E5C);
}

.gjjy9fb6v {
  d: path("M12.733 19.688v-3.754h6.43v3.649c0 .403-.233.603-.777.347c-.739-.347-2.453-1.617-2.453-1.617S14 19.7 13.53 19.91s-.797.18-.797-.223");
}

.glx9rn1kk {
  stop-color: var(--svg-color--494949, #494949);
}

.gmn9ea1yo {
  stop-color: var(--svg-color--f4dff7, #F4DFF7);
}

.go_hcsbdb {
  d: path("M20.945 12.296c.03-.514.065-1.151.103-1.838l.098-1.8a16 16 0 0 1 1.708-.97c.214-.102.456.021.461.258c.014.64-.118 1.503-.656 2.527c-.62 1.215-1.21 1.656-1.714 1.823");
}

.gov8w8rhe {
  stop-color: var(--svg-color--755743, #755743);
}

.gqk1oq8vx {
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M18.083 9.772c.064.085-.069.189-.22.302s-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.114.326-.136.39-.051");
}

.h1sgipbfm {
  stop-color: var(--svg-color--d82535, #D82535);
}

.h7wwwp44w {
  stop-color: var(--svg-color--302736, #302736);
}

.hl4dixbko {
  stop-color: var(--svg-color--ff6d74, #FF6D74);
}

.hon_u6n-c {
  d: path("m10.743 8.67l.006.139l.091 1.649c.038.69.073 1.33.104 1.844c-.508-.163-1.105-.599-1.733-1.829c-.538-1.024-.67-1.887-.656-2.527c.005-.237.247-.36.46-.258c.61.292 1.235.659 1.728.982");
}

.hp042yb8a {
  d: path("M13.237 4.887c-1.172.219-2.635 1.68-2.508 3.922c.032.555.062 1.116.091 1.649c.064 1.157.12 2.177.16 2.695c.04.453.252 1.55.765 2.312c.64.953 1.89 1.61 2.969 1.61h2.46c1.079 0 2.329-.657 2.97-1.61c.512-.762.723-1.86.765-2.312c.04-.518.095-1.538.158-2.695l.092-1.65c.127-2.241-1.336-3.702-2.508-3.921c-1.677-.313-3.737-.313-5.414 0");
}

.i--at434j {
  fill-rule: evenodd;
  d: path("M14.138 8.07c-.717-.133-1.345.18-1.57.343a.25.25 0 0 1-.293-.404c.291-.212 1.058-.597 1.954-.43a.25.25 0 1 1-.091.491");
}

.i0lopbdha {
  stop-color: var(--svg-color--4a2f65, #4A2F65);
}

.i30ki7brg {
  stop-color: var(--svg-color--202020, #202020);
  stop-opacity: 0;
}

.i4ydmtein {
  stop-color: var(--svg-color--c19f8a, #C19F8A);
  stop-opacity: 0;
}

.icnkybd-m {
  fill: var(--svg-color--c91a3b, #C91A3B);
  d: path("m14.177 17.903l-1.144 6.986a.402.402 0 0 0 .602.408l.201-.118a.51.51 0 0 1 .554.028l.706.514a1.1 1.1 0 0 0 1.294 0l.706-.514a.51.51 0 0 1 .553-.028l.202.118a.402.402 0 0 0 .602-.409l-1.145-6.985z");
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ih2ibv29b {
  stop-color: var(--svg-color--574b64, #574B64);
  stop-opacity: 0;
}

.ihp7x-bon {
  stop-color: var(--svg-color--655578, #655578);
  stop-opacity: 0;
}

.ii6mzr5ev {
  stop-color: var(--svg-color--060303, #060303);
}

.ikzxr830v {
  stop-color: var(--svg-color--ab7870, #AB7870);
  stop-opacity: 0;
}

.imlbmc2sy {
  stop-color: var(--svg-color--554961, #554961);
}

.irlvk16yo {
  stop-color: var(--svg-color--6b4944, #6B4944);
  stop-opacity: 0;
}

.ja9xhwbfv {
  d: path("m14.083 19.586l-.858 5.24a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.027l.705.514a1.1 1.1 0 0 0 1.295 0l.706-.514a.51.51 0 0 1 .553-.027l.202.118a.402.402 0 0 0 .602-.409l-.858-5.234c-.81-.505-1.855-1.28-1.855-1.28s-1.107.796-1.849 1.274");
}

.je0hzjbmv {
  stop-color: var(--svg-color--b28775, #B28775);
}

.jf64hac-x {
  fill: var(--svg-color--1e1d1d, #1E1D1D);
  d: path("M10.047 8.602c-.01-.09-.088-.45-.315-1.182c-.284-.915-.348-1.17-.142-1.75c.238-.67.713-.979 1.214-1.304q.12-.077.24-.158c.583-.394.772-.572 1.292-1.108s1.38-1.225 2.55-1.009c.484.11.861.12 1.049.126a5.3 5.3 0 0 0 1.048-.126c1.17-.216 2.03.473 2.55 1.01c.52.535.71.713 1.293 1.107l.24.158c.5.325.976.634 1.214 1.304c.206.58.142.835-.142 1.75c-.227.731-.305 1.093-.315 1.182l-.68.3c.149-2.484-1.392-3.623-2.201-3.894c-.871-.292-1.483-.264-1.916-.075c-.418.182-.565.53-.695.836l-.014.035c-.14.326-.614.302-.742 0l-.014-.035c-.13-.307-.277-.654-.695-.836c-.434-.19-1.067-.217-1.938.075c-.81.27-2.308 1.395-2.18 3.894z");
}

.jn8atjbpi {
  cx: 13.508px;
  cy: 9.965px;
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.39px;
  ry: 0.197px;
}

.jpxim8b1x {
  stop-color: var(--svg-color--534263, #534263);
}

.jsbpdr4yj {
  stop-color: var(--svg-color--483859, #483859);
}

.jtbt9y0gz {
  stop-color: var(--svg-color--56475f, #56475F);
}

.jzwike70j {
  stop-color: var(--svg-color--a99494, #A99494);
}

.k23bu8bhi {
  fill: var(--svg-color--302838, #302838);
  d: path("m10.174 12.727l-.03-1.145h1.382v3.274c-1.125-.524-1.354-1.603-1.352-2.13");
}

.k6ta6mb-r {
  stop-color: var(--svg-color--423153, #423153);
}

.kjjvcb6je {
  stop-color: var(--svg-color--301d1b, #301D1B);
}

.kn-2pccmm {
  stop-color: var(--svg-color--b9937f, #B9937F);
}

.kqp3z9b3n {
  stop-color: var(--svg-color--9c8ea7, #9C8EA7);
  stop-opacity: 0;
}

.ksrftlb6p {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.6 10.62l-.733 1.702c-.09.35.127.7.436.7h.657c.309 0 .527-.355.436-.7l-.445-1.701c-.095-.377-.252-.377-.352 0");
}

.l017if5vv {
  stop-color: var(--svg-color--b28775, #B28775);
  stop-opacity: 0;
}

.l0d7sccpf {
  stop-color: var(--svg-color--48335e, #48335E);
}

.l1z-2_-xs {
  fill-rule: evenodd;
  d: path("M16.458 19.1a.125.125 0 0 1 .141.106l.649 4.672a.125.125 0 1 1-.248.034l-.648-4.672a.125.125 0 0 1 .106-.14");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7o55475l {
  stop-color: var(--svg-color--8c6660, #8C6660);
  stop-opacity: 0;
}

.lft-zacfy {
  stop-color: var(--svg-color--ff242f, #FF242F);
}

.ljchh6cjg {
  fill: var(--svg-color--d7c2e1, #D7C2E1);
  d: path("m14.735 14.606l.396-.895a3.2 3.2 0 0 1-.624-.263c-.102-.057-.248.043-.218.157l.257.986a.1.1 0 0 0 .189.015");
}

.map3_rs3n {
  stop-color: var(--svg-color--4e4649, #4E4649);
}

.mo1945_5k {
  stop-color: var(--svg-color--a87f77, #A87F77);
  stop-opacity: 0;
}

.mplulyb8g {
  d: path("M18.15 9.583a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.mrkz_8b_u {
  stop-color: var(--svg-color--b9937f, #B9937F);
  stop-opacity: 0;
}

.n_d3gr2_k {
  stop-color: var(--svg-color--4a4a4a, #4A4A4A);
}

.n52c8qgao {
  stop-color: var(--svg-color--3d3743, #3D3743);
}

.nhjnhub6s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.424 8.207c.224-.18.93-.5 1.727-.398");
}

.nna-exbrs {
  fill: var(--svg-color--000, #000);
  d: path("M17.638 10.476a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.236");
}

.odfe47amh {
  stop-color: var(--svg-color--746784, #746784);
}

.oj4dw6cda {
  stop-color: var(--svg-color--543e6e, #543E6E);
}

.osxbsq6gx {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.513 13.45a2.94 2.94 0 0 0 2.87 0c.077-.042.17.023.143.106c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.083.066-.148.143-.106Z");
}

.ou_12nqfl {
  stop-color: var(--svg-color--f73397, #F73397);
}

.ozza9wbzj {
  stop-color: var(--svg-color--ff136b, #FF136B);
}

.p5bq_2b9f {
  stop-color: var(--svg-color--605075, #605075);
}

.p71wtvbay {
  stop-color: var(--svg-color--f3e0ff, #F3E0FF);
}

.p9pt_iv8l {
  stop-color: var(--svg-color--202020, #202020);
}

.pbkbtxb-e {
  fill: var(--svg-color--000, #000);
  d: path("M14.29 10.476a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.pgeb39bto {
  stop-color: var(--svg-color--a87f77, #A87F77);
}

.plsegxa8t {
  stop-color: var(--svg-color--503d5d, #503D5D);
}

.pu1_ubb-e {
  stop-color: var(--svg-color--eae1f3, #EAE1F3);
}

.puh_1hb6q {
  stop-color: var(--svg-color--ff3779, #FF3779);
}

.px8a23bzh {
  fill-rule: evenodd;
  d: path("M15.438 19.1a.125.125 0 0 0-.141.106l-.649 4.672a.125.125 0 0 0 .248.034l.649-4.672a.125.125 0 0 0-.107-.14");
}

.pxp9rxlhv {
  stop-color: var(--svg-color--e33e4b, #E33E4B);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qg2f7w0bc {
  stop-color: var(--svg-color--906c58, #906C58);
  stop-opacity: 0;
}

.qhxuaybfw {
  stop-color: var(--svg-color--dfcfe8, #DFCFE8);
  stop-opacity: 0;
}

.r21k1wzrc {
  stop-color: var(--svg-color--60506b, #60506B);
  stop-opacity: 0;
}

.r3f5xvbmj {
  stop-color: var(--svg-color--48335e, #48335E);
  stop-opacity: 0;
}

.rglphuhmg {
  stop-color: var(--svg-color--ad8273, #AD8273);
}

.ri_i1lblj {
  stop-color: var(--svg-color--47374c, #47374C);
  stop-opacity: 0;
}

.rq6u1obxj {
  stop-color: var(--svg-color--453455, #453455);
}

.s0w2dj02n {
  d: path("M18.083 9.772c.064.085-.069.189-.22.302s-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.114.326-.136.39-.051");
}

.s5279o3ha {
  fill: var(--svg-color--e6d3ef, #E6D3EF);
  d: path("m17.153 14.606l-.396-.895c.257-.078.466-.175.624-.263c.102-.057.248.043.218.157l-.258.986a.1.1 0 0 1-.188.015");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.spzd9kgpv {
  d: path("m15.584 10.458l-.532 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.ss9ml3bse {
  d: path("M8.76 18.345V29.95H4.996v-3.235c0-3.295 1.457-6.31 3.762-8.37");
}

.st-pambja {
  stop-color: var(--svg-color--494949, #494949);
  stop-opacity: 0;
}

.sxf6ctbxu {
  stop-color: var(--svg-color--9e6775, #9E6775);
  stop-opacity: 0;
}

.t0vl4obzm {
  stop-color: var(--svg-color--9c7664, #9C7664);
}

.t3--j5bga {
  d: path("M25.979 11.093q.254.22.5.454c.431.413.616 1.02.48 1.602c-.462 1.965-1.584 4.649-3.62 6.143l-1.038-.694c2.587-1.72 3.696-4.97 3.678-7.505");
}

.tokp2q_9y {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.57 9.311c-.653 0-1.205.45-1.355 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.u6c9fccih {
  stop-color: var(--svg-color--c19f8a, #C19F8A);
}

.u7u0nyv_w {
  stop-color: var(--svg-color--dd2864, #DD2864);
  stop-opacity: 0;
}

.uarfs1nvj {
  d: path("M10.047 8.602c-.01-.09-.088-.45-.315-1.182c-.284-.915-.348-1.17-.142-1.75c.238-.67.713-.979 1.214-1.304q.12-.077.24-.158c.583-.394.772-.572 1.292-1.108s1.38-1.225 2.55-1.009c.484.11.861.12 1.049.126a5.3 5.3 0 0 0 1.048-.126c1.17-.216 2.03.473 2.55 1.01c.52.535.71.713 1.293 1.107l.24.158c.5.325.976.634 1.214 1.304c.206.58.142.835-.142 1.75c-.227.731-.305 1.093-.315 1.182l-.68.3c.149-2.484-1.392-3.623-2.201-3.894c-.871-.292-1.483-.264-1.916-.075c-.418.182-.565.53-.695.836l-.014.035c-.14.326-.614.302-.742 0l-.014-.035c-.13-.307-.277-.654-.695-.836c-.434-.19-1.067-.217-1.938.075c-.81.27-2.308 1.395-2.18 3.894z");
}

.ui505nlmt {
  stop-color: var(--svg-color--976c67, #976C67);
}

.uw1qucxdm {
  stop-color: var(--svg-color--d2bdd8, #D2BDD8);
}

.uxwciubxp {
  stop-color: var(--svg-color--776484, #776484);
}

.v0b1ehlvd {
  stop-color: var(--svg-color--906b58, #906B58);
  stop-opacity: 0;
}

.v6in1309f {
  stop-color: var(--svg-color--553435, #553435);
}

.vbb18ixfb {
  stop-color: var(--svg-color--6b5a80, #6B5A80);
}

.vo8nxhb-a {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
  stop-opacity: 0;
}

.vs77n03cp {
  stop-color: var(--svg-color--5e3c33, #5E3C33);
  stop-opacity: 0;
}

.vsyzp2bxj {
  d: path("m20.98 11.683l.131-2.372l1.11-.764c.165-.114.383.005.355.204c-.117.82-.534 2.068-1.596 2.932");
}

.w11i7m31i {
  stop-color: var(--svg-color--665579, #665579);
  stop-opacity: 0;
}

.w75s09kgl {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.356 9.311c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.wasds5b8d {
  stop-color: var(--svg-color--1f1216, #1F1216);
}

.wnse4gbor {
  stop-color: var(--svg-color--875960, #875960);
}

.wolfrvf5u {
  stop-color: var(--svg-color--060303, #060303);
  stop-opacity: 0;
}

.wvbza2eye {
  fill: var(--svg-color--decee8, #DECEE8);
  fill-rule: evenodd;
  d: path("M15.438 19.1a.125.125 0 0 0-.141.106l-.649 4.672a.125.125 0 0 0 .248.034l.649-4.672a.125.125 0 0 0-.107-.14");
}

.xbzsco1zl {
  stop-color: var(--svg-color--c49880, #C49880);
}

.xkba2oejb {
  stop-color: var(--svg-color--8c5c61, #8C5C61);
  stop-opacity: 0;
}

.xksrntfob {
  stop-color: var(--svg-color--b3a9bc, #B3A9BC);
}

.xn_fidfol {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
  stop-opacity: 0;
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.y465w_bjd {
  stop-color: var(--svg-color--404040, #404040);
}

.y8ovvibws {
  stop-color: var(--svg-color--484848, #484848);
  stop-opacity: 0;
}

.y8q4s599i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.44 8.149c-.225-.18-.93-.5-1.728-.399");
}

.ya3n-2bve {
  d: path("M5.77 11.547c2.244-2.143 5.052-3.376 6.334-3.816l4.063 12.312h-5.89C7.36 18.925 5.845 15.515 5.29 13.15a1.68 1.68 0 0 1 .48-1.602");
}

.yafzpfb5d {
  stop-color: var(--svg-color--c69d89, #C69D89);
}

.yd4ohcbkp {
  d: path("M15.935 15.575c-6.04 0-10.938 5.1-10.938 11.14v3.235h21.875v-3.235c0-6.04-4.896-11.14-10.937-11.14");
}

.yhu-j5byc {
  fill: var(--svg-color--393939, #393939);
  fill-rule: evenodd;
  d: path("M17.74 8.07c.717-.133 1.346.18 1.57.343a.25.25 0 1 0 .294-.404c-.292-.212-1.059-.597-1.955-.43a.25.25 0 0 0 .092.491");
}

.ymkmd4kjm {
  stop-color: var(--svg-color--4e4649, #4E4649);
  stop-opacity: 0;
}

.yomd27bxe {
  stop-color: var(--svg-color--453455, #453455);
  stop-opacity: 0;
}

.ypzxpcc2j {
  stop-color: var(--svg-color--f73397, #F73397);
  stop-opacity: 0;
}

.ys8_95bug {
  d: path("M18.945 10.359a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.z256j7ndo {
  stop-color: var(--svg-color--744e4c, #744E4C);
}

.z8m-hreok {
  stop-color: var(--svg-color--47304f, #47304F);
}

.zajm34fcf {
  stop-color: var(--svg-color--e32d3d, #E32D3D);
}

.zbra2iiyy {
  stop-color: var(--svg-color--6b4439, #6B4439);
}

.zc8ra3ejp {
  d: path("M6.27 11.093q-.254.22-.5.454a1.68 1.68 0 0 0-.48 1.602c.462 1.965 1.584 4.649 3.62 6.143l1.038-.694c-2.588-1.72-3.696-4.97-3.678-7.505");
}

.zw8obf2yu {
  stop-color: var(--svg-color--c69d89, #C69D89);
  stop-opacity: 0;
}

.zxxizob4i {
  stop-color: var(--svg-color--c52133, #C52133);
}

</style>
