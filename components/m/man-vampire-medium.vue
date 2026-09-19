<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3yRybc)" class="h-wrbvbaj"/><g filter="url(#iKs3qEV)"><path fill="url(#iXLRPoM)" class="fir_x3lkx"/><path fill="url(#ir4VsFc)" class="fir_x3lkx"/></g><path fill="url(#itzBUue)" class="xp5tyrb9h"/><g filter="url(#i9DXOLb)"><path fill="url(#iKfkMAc)" class="zpfzvmboh"/></g><path fill="url(#iYEOHJJ)" class="pwbqwxbuo"/><path fill="url(#irYowge)" class="pwbqwxbuo"/><path fill="url(#i3IxmcV)" class="pwbqwxbuo"/><path fill="url(#i0hzJZc)" class="pwbqwxbuo"/><path fill="url(#ilvXoGd)" class="pwbqwxbuo"/><path fill="url(#izOfPJe)" class="pwbqwxbuo"/><path fill="url(#izD4dme)" class="pwbqwxbuo"/><path fill="url(#iOqaXXb)" class="pwbqwxbuo"/><path fill="url(#icCQoSd)" class="jcv675w6u"/><path fill="url(#iUp0Wxb)" class="jcv675w6u"/><path fill="url(#iM3yElc)" class="qyo-sfboi"/><path fill="url(#iXJYGHe)" class="qyo-sfboi"/><path fill="url(#ipKjL7b)" class="qyo-sfboi"/><path fill="url(#isG10Od)" class="qiw2lo8xj"/><path fill="url(#idf2Bve)" class="qiw2lo8xj"/><path fill="url(#iJpq4RY)" class="qiw2lo8xj"/><g filter="url(#iypDERc)"><path class="oegqju6nx"/></g><g filter="url(#ix7LHyG)"><path class="qpjplr-8j"/></g><g filter="url(#i9TgIWd)"><path fill="url(#iJrmKzj)" class="fom0o-b5s"/><path fill="url(#iwRKhAd)" class="fom0o-b5s"/><path fill="url(#iCLw6Zc)" class="fom0o-b5s"/></g><g filter="url(#iQPYcSd)"><path fill="url(#i0X2fhd)" class="fpuz4ebbn"/></g><g filter="url(#iT3L2Ld)"><path fill="url(#i6V862b)" class="dwjylab2g"/><path fill="url(#iSOtPjz)" class="dwjylab2g"/><path fill="url(#iGWl5ie)" class="dwjylab2g"/></g><path fill="url(#idh0SCq)" class="dwjylab2g"/><path fill="url(#in5ln6T)" class="dwjylab2g"/><path fill="url(#iixtTNb)" class="dwjylab2g"/><path fill="url(#iD10iBe)" class="dwjylab2g"/><path fill="url(#iesd3Ge)" class="dwjylab2g"/><g filter="url(#iy6xzHd)"><path fill="url(#igpY7Nd)" class="ikn67-bal"/></g><g filter="url(#ifGf3se)"><path stroke="url(#ioQ0vTd)" class="bv2dogb4d"/></g><path class="k8ujccw3q"/><path fill="url(#iDVwLNd)" class="o22onf4kj"/><path fill="url(#iYBwG9b)" class="q5ffgjbrn"/><path clip-rule="evenodd" class="zanwp13zc"/><path fill="url(#iEIkO4b)" clip-rule="evenodd" class="knk60smxr"/><path clip-rule="evenodd" class="k3ni8ebrh"/><path fill="url(#iS9ZmDb)" clip-rule="evenodd" class="h_ltlobtq"/><g filter="url(#ijCoSme)"><path class="kndj6yb3d"/></g><g filter="url(#ikxYFnb)"><path class="g6uayibor"/><path fill="url(#iNSOUTm)" class="pm9qglbyu"/><path fill="url(#iSsMltb)" class="pm9qglbyu"/><path fill="url(#i4L0XGe)" class="pm9qglbyu"/><path fill="url(#iYZP1Hy)" class="pm9qglbyu"/></g><path class="fe7e9yb5h"/><path fill="url(#iBF3bmd)" class="eg13vqfoz"/><path class="xvn4q2b0p"/><g filter="url(#iaN6Evd)"><path class="nknl4u8nb"/><path fill="url(#iUA2J8q)" class="oug_496gg"/></g><g filter="url(#ixLnpHd)"><path fill="url(#iawMBsb)" class="tik5rtblr"/></g><path class="qriicvbhe"/><path fill="url(#i7Mx4Bd)" class="d73walu2l"/><path class="flz2c8iyl"/><g filter="url(#ijmqAPd)"><path fill="url(#iMJRHhX)" class="q4uqrvgrz"/></g><g filter="url(#iYWqSOd)"><ellipse transform="rotate(-27.914 13.509 9.978)" class="xgtnudb2w"/><ellipse fill="url(#iJ8zpLc)" transform="rotate(-27.914 13.509 9.978)" class="klq3puw7i"/></g><path fill="url(#iqytG6d)" class="z7yo4atmg"/><path fill="url(#iBHaFIe)" class="z7yo4atmg"/><path fill="url(#iI0bIJd)" class="z7yo4atmg"/><path fill="url(#i4yrNMo)" class="lpnng9rjr"/><path fill="url(#i2Jrw2d)" class="lpnng9rjr"/><g filter="url(#iixKmCe)"><path fill="url(#imN9Cae)" class="u_per4bve"/><path fill="url(#ieCtHTY)" class="u_per4bve"/></g><g filter="url(#iQ5PCPe)"><path fill="url(#i3m8iqc)" class="lmxk8n8zo"/><path fill="url(#iSiOt8d)" class="lmxk8n8zo"/></g><path fill="url(#iEiXAwd)" class="lfrbiybeu"/><path fill="url(#iYdgarb)" class="lfrbiybeu"/><path fill="url(#iPzLIVb)" class="lfrbiybeu"/><path fill="url(#iBEJh9q)" class="lfrbiybeu"/><g filter="url(#iJqaJYc)"><path clip-rule="evenodd" class="xon9p4yuw"/></g><g filter="url(#iiRQj3c)"><path stroke="url(#iZvZE6c)" class="en6kh9i1y"/></g><g filter="url(#igXTxhG)"><path stroke="url(#ikoviGe)" class="y5ykz5l3i"/></g><g filter="url(#iPAmmZd)"><path clip-rule="evenodd" class="blu0296ak"/></g><g filter="url(#i8JUrsb)"><path stroke="url(#ija004O)" class="xy4gpnq9q"/></g><g filter="url(#iPPjwee)"><path fill="url(#iwaDu4c)" class="d9i9oiblk"/></g><defs><radialGradient id="i3yRybc" cx="0" cy="0" r="1" gradientTransform="matrix(3.93792 -7.29125 14.315 7.73138 20.553 16.769)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="1" class="gdsiwyiyr"/></radialGradient><radialGradient id="iXLRPoM" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92122 7.06151 -2.22108 -.91882 27.573 12.245)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jpxim8b1x"/><stop offset="1" class="n52c8qgao"/></radialGradient><radialGradient id="ir4VsFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 4.15626 -.42744 -.1607 27.323 12.713)" gradientUnits="userSpaceOnUse"><stop class="fg6i_oqme"/><stop offset="1" class="ih2ibv29b"/></radialGradient><radialGradient id="itzBUue" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58397 -6.61442 12.98618 -8.99977 12.493 17.046)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="0" class="pxp9rxlhv"/><stop offset="1" class="e06hnni3m"/></radialGradient><radialGradient id="irYowge" cx="0" cy="0" r="1" gradientTransform="rotate(-118.874 16.525 8.487)scale(12.4902 33.343)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="f6lcb9bkn"/><stop offset="1" class="jtbt9y0gz"/></radialGradient><radialGradient id="i3IxmcV" cx="0" cy="0" r="1" gradientTransform="rotate(-65.133 29.239 1.614)scale(12.2618 28.8332)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="r21k1wzrc"/><stop offset="1" class="b2cn2_uce"/></radialGradient><radialGradient id="i0hzJZc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71875 0 0 -14.5625 23.292 23.338)" gradientUnits="userSpaceOnUse"><stop class="odfe47amh"/><stop offset="1" class="carxtabzu"/></radialGradient><radialGradient id="ilvXoGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6875 -.22656 0 19.206 16.744)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="z8m-hreok"/><stop offset="1" class="ehu1o5vid"/></radialGradient><radialGradient id="izOfPJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 3.5 -5.72433 -1.89104 12.667 16.37)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="a75cnrb-k"/><stop offset="1" class="ri_i1lblj"/></radialGradient><radialGradient id="icCQoSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6045 2.48458 0 23.855 29.963)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="vbb18ixfb"/><stop offset="1" class="p5bq_2b9f"/></radialGradient><radialGradient id="iUp0Wxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5781 .52466 0 23.11 29.963)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l0d7sccpf"/><stop offset="1" class="r3f5xvbmj"/></radialGradient><radialGradient id="iM3yElc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.2188 2.95614 0 7.292 29.963)" gradientUnits="userSpaceOnUse"><stop class="oj4dw6cda"/><stop offset="1" class="jsbpdr4yj"/></radialGradient><radialGradient id="iXJYGHe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21875 0 0 -14.5625 8.542 29.494)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ihp7x-bon"/><stop offset="1" class="g_z46f3jl"/></radialGradient><radialGradient id="iJrmKzj" cx="0" cy="0" r="1" gradientTransform="rotate(57.496 -7.297 21.845)scale(4.18715 6.17567)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="xksrntfob"/><stop offset="1" class="pu1_ubb-e"/></radialGradient><radialGradient id="iwRKhAd" cx="0" cy="0" r="1" gradientTransform="matrix(.375 3.375 -7.05108 .78345 14.73 14.37)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="jzwike70j"/><stop offset="1" class="gbck5ebgo"/></radialGradient><radialGradient id="iCLw6Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87568 -2.6343 0 15.948 16.4)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="uxwciubxp"/><stop offset="1" class="kqp3z9b3n"/></radialGradient><radialGradient id="iSOtPjz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36518 1.59886 0 18.24 9.044)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iGWl5ie" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.43518 1.69837 0 13.71 9.184)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iixtTNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.9375 12.5275 0 15.937 17.188)" gradientUnits="userSpaceOnUse"><stop offset=".076" class="wzpo11zau"/><stop offset="1" class="dcym8repk"/></radialGradient><radialGradient id="iD10iBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6875 4.57129 0 15.937 17.282)" gradientUnits="userSpaceOnUse"><stop class="c71t0xnys"/><stop offset="1" class="q0utukbim"/></radialGradient><radialGradient id="iesd3Ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4375 10.3813 0 15.937 14.75)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="fak8eyb5r"/><stop offset=".988" class="b9rs4i5yv"/></radialGradient><radialGradient id="iYZP1Hy" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.294 12.365)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iBF3bmd" cx="0" cy="0" r="1" gradientTransform="rotate(-117.266 12.234 -.373)scale(.57126 .90459)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iUA2J8q" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.919 10.158)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="i7Mx4Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26172 -.50781 .80412 -.41444 13.803 10.33)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iJ8zpLc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.814 -1.495)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="iBHaFIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0193 1.125 -.25102 -.22744 23.316 7.807)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="u6c9fccih"/><stop offset="1" class="i4ydmtein"/></radialGradient><radialGradient id="i2Jrw2d" cx="0" cy="0" r="1" gradientTransform="rotate(122.009 2.922 7.096)scale(.56277 2.95205)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="druknjb2h"/><stop offset="1" class="vs77n03cp"/></radialGradient><radialGradient id="imN9Cae" cx="0" cy="0" r="1" gradientTransform="matrix(1.59772 -1.40625 .5978 .67918 20.98 10.338)" gradientUnits="userSpaceOnUse"><stop class="rglphuhmg"/><stop offset="1" class="fyc1bbcaj"/></radialGradient><radialGradient id="ieCtHTY" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.0625 .1101 1.101 20.86 10.745)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="kn-2pccmm"/><stop offset="1" class="mrkz_8b_u"/></radialGradient><radialGradient id="i3m8iqc" cx="0" cy="0" r="1" gradientTransform="rotate(-132.082 7.744 2.73)scale(2.41247 2.17677)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="z256j7ndo"/><stop offset="1" class="ckmg8ibfr"/></radialGradient><radialGradient id="iSiOt8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18123 .63382 -1.16713 -2.17513 11.01 9.795)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="l7o55475l"/><stop offset="1" class="e1xn34b4b"/></radialGradient><radialGradient id="iEiXAwd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.93271 6.4606 -9.67475 -7.38675 20.88 4.029)" gradientUnits="userSpaceOnUse"><stop class="ja62qnbvn"/><stop offset="1" class="doeokpgss"/></radialGradient><radialGradient id="iYdgarb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.114 9.345 .93)scale(6.55215 1.19385)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="mzjok2vtv"/><stop offset="1" class="moen_vfyr"/></radialGradient><radialGradient id="iPzLIVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -1.25 1.2273 1.2273 20.287 3.716)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="xn5dksb-u"/><stop offset="1" class="otpekjb_s"/></radialGradient><radialGradient id="iBEJh9q" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.15625 -2.7392 0 15.948 1.904)" gradientUnits="userSpaceOnUse"><stop class="yucjgfb4f"/><stop offset="1" class="neb43bcvz"/></radialGradient><radialGradient id="iwaDu4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 -1.20384 6.351 -.65945 17.482 4.812)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="ing6ksb7p"/><stop offset=".789" class="b-0vp4bih"/></radialGradient><linearGradient id="iKfkMAc" x1="5.54" x2="8.862" y1="12" y2="18.369" gradientUnits="userSpaceOnUse"><stop class="imlbmc2sy"/><stop offset="1" class="h7wwwp44w"/></linearGradient><linearGradient id="iYEOHJJ" x1="15.935" x2="15.935" y1="15.588" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="plsegxa8t"/><stop offset="1" class="dbg8b7bda"/></linearGradient><linearGradient id="izD4dme" x1="8.661" x2="8.938" y1="29.963" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="rq6u1obxj"/><stop offset="1" class="yomd27bxe"/></linearGradient><linearGradient id="iOqaXXb" x1="23.206" x2="22.776" y1="29.963" y2="29.963" gradientUnits="userSpaceOnUse"><stop offset=".136" class="i0lopbdha"/><stop offset="1" class="w11i7m31i"/></linearGradient><linearGradient id="ipKjL7b" x1="8.759" x2="7.51" y1="28.776" y2="28.776" gradientUnits="userSpaceOnUse"><stop class="k6ta6mb-r"/><stop offset="1" class="drixk4bdm"/></linearGradient><linearGradient id="isG10Od" x1="15.939" x2="15.939" y1="20.932" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="zajm34fcf"/><stop offset="1" class="puh_1hb6q"/></linearGradient><linearGradient id="idf2Bve" x1="15.939" x2="15.939" y1="29.963" y2="27.307" gradientUnits="userSpaceOnUse"><stop class="ou_12nqfl"/><stop offset="1" class="ypzxpcc2j"/></linearGradient><linearGradient id="iJpq4RY" x1="19.542" x2="17.698" y1="28.776" y2="28.776" gradientUnits="userSpaceOnUse"><stop offset=".119" class="zxxizob4i"/><stop offset="1" class="u7u0nyv_w"/></linearGradient><linearGradient id="i0X2fhd" x1="15.935" x2="15.935" y1="17.854" y2="25.882" gradientUnits="userSpaceOnUse"><stop class="gmn9ea1yo"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="i6V862b" x1="19.919" x2="12.314" y1="10.779" y2="11.857" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="idh0SCq" x1="10.546" x2="12.416" y1="13.595" y2="13.531" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="in5ln6T" x1="20.799" x2="19.693" y1="12.716" y2="12.624" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="igpY7Nd" x1="15.654" x2="23.806" y1="7.667" y2="4.748" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="ioQ0vTd" x1="15.948" x2="15.948" y1="14.706" y2="14.284" gradientUnits="userSpaceOnUse"><stop class="pgeb39bto"/><stop offset="1" class="mo1945_5k"/></linearGradient><linearGradient id="iDVwLNd" x1="17.479" x2="16.94" y1="13.893" y2="14.135" gradientUnits="userSpaceOnUse"><stop class="h4n1x2_nx"/><stop offset="1" class="kbidwf4gr"/></linearGradient><linearGradient id="iYBwG9b" x1="14.969" x2="14.516" y1="14.135" y2="14.062" gradientUnits="userSpaceOnUse"><stop class="ftqk6c0fk"/><stop offset="1" class="seh9j6z3x"/></linearGradient><linearGradient id="iEIkO4b" x1="16.351" x2="16.479" y1="19.112" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iS9ZmDb" x1="15.546" x2="15.417" y1="19.112" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iNSOUTm" x1="15.101" x2="16.04" y1="11.807" y2="11.807" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iSsMltb" x1="16.905" x2="15.879" y1="12.129" y2="12.115" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="i4L0XGe" x1="16.161" x2="16.161" y1="12.872" y2="12.299" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iawMBsb" x1="18.886" x2="18.63" y1="10.136" y2="10.301" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iMJRHhX" x1="14.524" x2="14.21" y1="10.128" y2="10.322" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iqytG6d" x1="21.542" x2="22.417" y1="8.432" y2="11.12" gradientUnits="userSpaceOnUse"><stop class="t0vl4obzm"/><stop offset="1" class="cy4cy6bws"/></linearGradient><linearGradient id="iI0bIJd" x1="21.862" x2="22.131" y1="8.174" y2="8.596" gradientUnits="userSpaceOnUse"><stop class="gov8w8rhe"/><stop offset="1" class="qg2f7w0bc"/></linearGradient><linearGradient id="i4yrNMo" x1="8.981" x2="11.396" y1="10.514" y2="9.507" gradientUnits="userSpaceOnUse"><stop class="g-cxxi1ky"/><stop offset="1" class="wnse4gbor"/></linearGradient><linearGradient id="iZvZE6c" x1="12.913" x2="14.317" y1="8.298" y2="8.031" gradientUnits="userSpaceOnUse"><stop class="s0qsib-ln"/><stop offset="1" class="i5bggbceb"/></linearGradient><linearGradient id="ikoviGe" x1="13.738" x2="13.252" y1="7.957" y2="7.091" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ija004O" x1="18.225" x2="18.769" y1="7.918" y2="6.947" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><filter id="iKs3qEV" width="4.702" height="8.2" x="22.301" y="11.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1225"/></filter><filter id="i9DXOLb" width="4.902" height="8.4" x="5.146" y="11.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.321569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1225"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1225" result="effect2_innerShadow_4002_1225"/></filter><filter id="iypDERc" width="6.968" height="4.815" x="12.464" y="15.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".25"/></filter><filter id="ix7LHyG" width="6.431" height="9.028" x="12.527" y="17.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".25"/></filter><filter id="i9TgIWd" width="6.43" height="4.46" x="12.733" y="15.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.835294 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1225"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.733333 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1225" result="effect2_innerShadow_4002_1225"/></filter><filter id="iQPYcSd" width="5.531" height="8.006" x="13.22" y="18.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.705882 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1225"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.670588 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1225" result="effect2_innerShadow_4002_1225"/></filter><filter id="iT3L2Ld" width="10.31" height="12.713" x="10.782" y="4.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1225"/></filter><filter id="iy6xzHd" width="8.25" height="7.07" x="14.357" y="2.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation="1"/></filter><filter id="ifGf3se" width="3.566" height="1.546" x="14.165" y="13.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".05"/></filter><filter id="ijCoSme" width="3.262" height="4.184" x="14.096" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".375"/></filter><filter id="ikxYFnb" width="2.379" height="3.184" x="14.777" y="9.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".125"/></filter><filter id="iaN6Evd" width=".787" height=".697" x="17.413" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".05"/></filter><filter id="ixLnpHd" width=".892" height=".914" x="18.253" y="9.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".1"/></filter><filter id="ijmqAPd" width=".987" height="1.041" x="13.807" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".1"/></filter><filter id="iYWqSOd" width=".914" height=".705" x="13.052" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".05"/></filter><filter id="iixKmCe" width="2.098" height="3.68" x="20.73" y="8.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".125"/></filter><filter id="iQ5PCPe" width="2.017" height="3.595" x="9.092" y="8.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".1"/></filter><filter id="iJqaJYc" width="2.927" height="1.811" x="12.038" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1225"/></filter><filter id="iiRQj3c" width="2.477" height="1.211" x="12.138" y="7.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".125"/></filter><filter id="igXTxhG" width="2.577" height="1.311" x="12.088" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".15"/></filter><filter id="iPAmmZd" width="2.927" height="1.811" x="17.264" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1225"/></filter><filter id="i8JUrsb" width="2.785" height="1.367" x="17.237" y="7.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".15"/></filter><filter id="iPPjwee" width="5.117" height="2.558" x="15.74" y="3.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1225" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-vampire-medium" /></template>
<style>
.a75cnrb-k {
  stop-color: var(--svg-color--47374c, #47374C);
}

.b-0vp4bih {
  stop-color: var(--svg-color--454445, #454445);
  stop-opacity: 0;
}

.b2cn2_uce {
  stop-color: var(--svg-color--60506b, #60506B);
}

.b9rs4i5yv {
  stop-color: var(--svg-color--764d38, #764D38);
}

.blu0296ak {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M17.784 8.389a2.15 2.15 0 0 1 1.417.37a.475.475 0 1 0 .53-.788a3.1 3.1 0 0 0-2.037-.528a.475.475 0 1 0 .09.946");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bv2dogb4d {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.513 13.464a2.94 2.94 0 0 0 2.87 0c.077-.043.17.022.143.106c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.084.066-.149.143-.107Z");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c71t0xnys {
  stop-color: var(--svg-color--a66998, #A66998);
}

.carxtabzu {
  stop-color: var(--svg-color--604f70, #604F70);
  stop-opacity: 0;
}

.ckmg8ibfr {
  stop-color: var(--svg-color--835a60, #835A60);
}

.cy4cy6bws {
  stop-color: var(--svg-color--b1867a, #B1867A);
}

.d73walu2l {
  d: path("M13.778 9.597a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.d9i9oiblk {
  d: path("M16.45 4.226c-.25.315-.42.986-.46 1.53c.352-1.033.773-1.247 1.258-1.347c1.139-.152 2.78.504 3.359 1.038l-.374-1.038c-2.665-1.182-3.425-.635-3.783-.183");
}

.dbg8b7bda {
  stop-color: var(--svg-color--553d71, #553D71);
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.doeokpgss {
  stop-color: var(--svg-color--191818, #191818);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.druknjb2h {
  stop-color: var(--svg-color--5e3c33, #5E3C33);
}

.dwjylab2g {
  d: path("M10.783 7.58a3 3 0 0 1 2.999-3.082h4.31a3 3 0 0 1 3 3.06l-.198 6.36c-.035 1.77-1.408 3.142-3.178 3.142h-3.51c-1.761 0-3.07-1.351-3.194-3.118z");
}

.e06hnni3m {
  stop-color: var(--svg-color--e73665, #E73665);
}

.e1xn34b4b {
  stop-color: var(--svg-color--8c6660, #8C6660);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eg13vqfoz {
  d: path("M18.15 9.597a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.ehu1o5vid {
  stop-color: var(--svg-color--47304f, #47304F);
  stop-opacity: 0;
}

.en6kh9i1y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.513 8.365a2.63 2.63 0 0 1 1.727-.45");
}

.f1lm8sbjk {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f6lcb9bkn {
  stop-color: var(--svg-color--56475f, #56475F);
  stop-opacity: 0;
}

.fak8eyb5r {
  stop-color: var(--svg-color--9f7967, #9F7967);
  stop-opacity: 0;
}

.fe7e9yb5h {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.356 9.325c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.13");
}

.fg6i_oqme {
  stop-color: var(--svg-color--574b64, #574B64);
}

.fir_x3lkx {
  d: path("M25.979 11.106q.254.22.5.455c.431.413.616 1.02.48 1.602c-.462 1.964-1.584 4.649-3.62 6.143l-1.038-.694c2.587-1.72 3.696-4.97 3.678-7.506");
}

.flz2c8iyl {
  fill: var(--svg-color--000, #000);
  d: path("M14.29 10.49a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.fom0o-b5s {
  d: path("M12.733 19.702v-3.754h6.43v3.649c0 .403-.233.603-.777.347c-.739-.347-2.453-1.617-2.453-1.617S14 19.714 13.53 19.924s-.797.181-.797-.223");
}

.fpuz4ebbn {
  d: path("m14.084 19.6l-.859 5.24a.402.402 0 0 0 .602.409l.202-.118a.51.51 0 0 1 .553.027l.706.514a1.1 1.1 0 0 0 1.294 0l.706-.514a.51.51 0 0 1 .553-.027l.202.117a.402.402 0 0 0 .602-.408l-.857-5.235c-.81-.504-1.855-1.279-1.855-1.279s-1.107.796-1.85 1.273");
}

.ft5dv1b6b {
  fill: none;
}

.ftqk6c0fk {
  stop-color: var(--svg-color--d1c8d8, #D1C8D8);
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

.g6uayibor {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.583 10.471l-.531 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.377-.646-.377-.766 0");
}

.gbck5ebgo {
  stop-color: var(--svg-color--a99494, #A99494);
  stop-opacity: 0;
}

.gdsiwyiyr {
  stop-color: var(--svg-color--e82e5c, #E82E5C);
}

.gmn9ea1yo {
  stop-color: var(--svg-color--f4dff7, #F4DFF7);
}

.gov8w8rhe {
  stop-color: var(--svg-color--755743, #755743);
}

.h_ltlobtq {
  fill-rule: evenodd;
  d: path("M15.438 19.113a.125.125 0 0 0-.141.107l-.649 4.671a.125.125 0 0 0 .248.035l.649-4.672a.125.125 0 0 0-.107-.141");
}

.h-wrbvbaj {
  d: path("M26.478 11.561c-2.243-2.143-5.051-3.376-6.334-3.816l-4.062 12.312h5.89c2.916-1.118 4.431-4.528 4.986-6.894a1.68 1.68 0 0 0-.48-1.602");
}

.h1sgipbfm {
  stop-color: var(--svg-color--d82535, #D82535);
}

.h4n1x2_nx {
  stop-color: var(--svg-color--e6deec, #E6DEEC);
}

.h7wwwp44w {
  stop-color: var(--svg-color--302736, #302736);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hl4dixbko {
  stop-color: var(--svg-color--ff6d74, #FF6D74);
}

.i0lopbdha {
  stop-color: var(--svg-color--4a2f65, #4A2F65);
}

.i4ydmtein {
  stop-color: var(--svg-color--c19f8a, #C19F8A);
  stop-opacity: 0;
}

.i5bggbceb {
  stop-color: var(--svg-color--4f494b, #4F494B);
}

.ih2ibv29b {
  stop-color: var(--svg-color--574b64, #574B64);
  stop-opacity: 0;
}

.ihp7x-bon {
  stop-color: var(--svg-color--655578, #655578);
  stop-opacity: 0;
}

.ikn67-bal {
  d: path("m20.154 4.635l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.imlbmc2sy {
  stop-color: var(--svg-color--554961, #554961);
}

.ing6ksb7p {
  stop-color: var(--svg-color--454445, #454445);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.ja62qnbvn {
  stop-color: var(--svg-color--252525, #252525);
}

.jcv675w6u {
  d: path("M23.11 18.359v11.604h3.762V26.73c0-3.295-1.456-6.31-3.761-8.37");
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

.k3ni8ebrh {
  fill: var(--svg-color--decee8, #DECEE8);
  fill-rule: evenodd;
  d: path("M15.438 19.113a.125.125 0 0 0-.141.107l-.649 4.671a.125.125 0 0 0 .248.035l.649-4.672a.125.125 0 0 0-.107-.141");
}

.k6ta6mb-r {
  stop-color: var(--svg-color--423153, #423153);
}

.k8ujccw3q {
  fill: var(--svg-color--87014e, #87014E);
  d: path("M14.513 13.464a2.94 2.94 0 0 0 2.87 0c.077-.043.17.022.143.106c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.084.066-.149.143-.107");
}

.kbidwf4gr {
  stop-color: var(--svg-color--d3cadb, #D3CADB);
}

.klq3puw7i {
  cx: 13.509px;
  cy: 9.978px;
  rx: 0.39px;
  ry: 0.197px;
}

.kn-2pccmm {
  stop-color: var(--svg-color--b9937f, #B9937F);
}

.kndj6yb3d {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.69 10.635l-.82 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.377-.283-.377-.395 0");
}

.knk60smxr {
  fill-rule: evenodd;
  d: path("M16.458 19.113a.125.125 0 0 1 .141.107l.649 4.671a.125.125 0 1 1-.248.035l-.648-4.672a.125.125 0 0 1 .106-.141");
}

.kqp3z9b3n {
  stop-color: var(--svg-color--9c8ea7, #9C8EA7);
  stop-opacity: 0;
}

.l0d7sccpf {
  stop-color: var(--svg-color--48335e, #48335E);
}

.l7o55475l {
  stop-color: var(--svg-color--8c6660, #8C6660);
  stop-opacity: 0;
}

.lfrbiybeu {
  d: path("m10.37 10.082l-.617-2.736c-.117-.426-.242-1.394.024-2.013c.264-.612.68-.836 1.05-1.035c.125-.066.243-.13.35-.205q.123-.086.235-.16c.298-.201.536-.361.875-.762c.422-.5 1.056-1.005 1.76-1.114c.406-.064.784.036 1.146.132c.259.069.509.135.755.137c.246-.002.497-.068.755-.137c.362-.096.74-.196 1.147-.132c.703.109 1.337.613 1.76 1.114c.338.4.576.56.874.762l.236.16c.106.075.224.139.348.205c.37.199.787.423 1.05 1.035c.268.62.142 1.587.025 2.013l-.616 2.736c-.054.238-.298.398-.542.398l.032-1.71c0-1.346-.334-2.387-1.032-3.035c-.982-.91-1.858-.91-2.483-.91c-.675 0-.847.379-1.041.745l-.09.165c-.155.268-.336.337-.423.33c-.087.007-.267-.062-.42-.33q-.048-.082-.091-.165c-.195-.366-.368-.745-1.043-.745c-.625 0-1.5 0-2.483.91c-.697.648-1.032 1.69-1.032 3.034l.021 1.72a.546.546 0 0 1-.53-.407");
}

.lft-zacfy {
  stop-color: var(--svg-color--ff242f, #FF242F);
}

.lmxk8n8zo {
  d: path("m10.778 9.338l.062 1.134l.069 1.24C9.833 10.847 9.41 9.59 9.294 8.765c-.028-.2.19-.318.355-.204z");
}

.lpnng9rjr {
  d: path("M10.846 8.669c.034 1.21.073 2.413.109 3.638c-.507-.163-1.116-.605-1.744-1.835c-.538-1.025-.67-1.887-.656-2.528c.005-.237.247-.36.46-.258c.61.292 1.337.659 1.83.983");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mo1945_5k {
  stop-color: var(--svg-color--a87f77, #A87F77);
  stop-opacity: 0;
}

.moen_vfyr {
  stop-color: var(--svg-color--47423f, #47423F);
  stop-opacity: 0;
}

.mrkz_8b_u {
  stop-color: var(--svg-color--b9937f, #B9937F);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.mzjok2vtv {
  stop-color: var(--svg-color--47423f, #47423F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n52c8qgao {
  stop-color: var(--svg-color--3d3743, #3D3743);
}

.neb43bcvz {
  stop-color: var(--svg-color--4d4d4d, #4D4D4D);
  stop-opacity: 0;
}

.nknl4u8nb {
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M18.084 9.786c.063.085-.07.189-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o22onf4kj {
  d: path("m17.154 14.62l-.396-.895a3.2 3.2 0 0 0 .623-.263c.102-.058.248.043.218.156l-.257.986a.1.1 0 0 1-.188.016");
}

.odfe47amh {
  stop-color: var(--svg-color--746784, #746784);
}

.oegqju6nx {
  fill: var(--svg-color--bb172a, #BB172A);
  d: path("M12.964 19.845v-3.484h5.968v3.387c0 .374-.216.56-.721.322c-.686-.322-2.278-1.501-2.278-1.501s-1.792 1.288-2.23 1.483s-.74.168-.74-.207");
}

.oj4dw6cda {
  stop-color: var(--svg-color--543e6e, #543E6E);
}

.otpekjb_s {
  stop-color: var(--svg-color--464646, #464646);
  stop-opacity: 0;
}

.ou_12nqfl {
  stop-color: var(--svg-color--f73397, #F73397);
}

.oug_496gg {
  d: path("M18.084 9.786c.063.085-.07.189-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
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

.pgeb39bto {
  stop-color: var(--svg-color--a87f77, #A87F77);
}

.plsegxa8t {
  stop-color: var(--svg-color--503d5d, #503D5D);
}

.pm9qglbyu {
  d: path("m15.583 10.471l-.531 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.377-.646-.377-.766 0");
}

.pu1_ubb-e {
  stop-color: var(--svg-color--eae1f3, #EAE1F3);
}

.puh_1hb6q {
  stop-color: var(--svg-color--ff3779, #FF3779);
}

.pwbqwxbuo {
  d: path("M15.935 15.588c-6.04 0-10.938 5.1-10.938 11.14v3.235h21.875V26.73c0-6.04-4.896-11.14-10.937-11.14");
}

.pxp9rxlhv {
  stop-color: var(--svg-color--e33e4b, #E33E4B);
}

.q0utukbim {
  stop-color: var(--svg-color--a66998, #A66998);
  stop-opacity: 0;
}

.q4uqrvgrz {
  d: path("M14.594 10.385c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.q5ffgjbrn {
  d: path("m14.735 14.62l.396-.895a3.2 3.2 0 0 1-.623-.263c-.103-.058-.249.043-.22.156l.259.986a.1.1 0 0 0 .188.016");
}

.qg2f7w0bc {
  stop-color: var(--svg-color--906c58, #906C58);
  stop-opacity: 0;
}

.qhxuaybfw {
  stop-color: var(--svg-color--dfcfe8, #DFCFE8);
  stop-opacity: 0;
}

.qiw2lo8xj {
  d: path("M12.733 29.963V16.071a10.7 10.7 0 0 1 3.183-.483c1.124 0 2.208.175 3.23.497v13.878z");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qpjplr-8j {
  fill: var(--svg-color--c91a3b, #C91A3B);
  d: path("m14.177 17.916l-1.144 6.986a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.028l.706.513a1.1 1.1 0 0 0 1.294 0l.706-.513a.51.51 0 0 1 .553-.028l.202.118a.402.402 0 0 0 .602-.409l-1.145-6.986z");
}

.qriicvbhe {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.571 9.325c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qyo-sfboi {
  d: path("M8.76 18.359v11.604H4.996V26.73c0-3.295 1.457-6.31 3.762-8.37");
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

.s0qsib-ln {
  stop-color: var(--svg-color--4f494b, #4F494B);
  stop-opacity: 0;
}

.seh9j6z3x {
  stop-color: var(--svg-color--c7becf, #C7BECF);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.t0vl4obzm {
  stop-color: var(--svg-color--9c7664, #9C7664);
}

.tik5rtblr {
  d: path("M18.945 10.372a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.u_per4bve {
  d: path("m20.98 11.696l.131-2.371l1.11-.764c.165-.114.383.004.355.204c-.117.82-.534 2.067-1.596 2.931");
}

.u6c9fccih {
  stop-color: var(--svg-color--c19f8a, #C19F8A);
}

.u7u0nyv_w {
  stop-color: var(--svg-color--dd2864, #DD2864);
  stop-opacity: 0;
}

.uw1qucxdm {
  stop-color: var(--svg-color--d2bdd8, #D2BDD8);
}

.uxwciubxp {
  stop-color: var(--svg-color--776484, #776484);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
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

.w11i7m31i {
  stop-color: var(--svg-color--665579, #665579);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wnse4gbor {
  stop-color: var(--svg-color--875960, #875960);
}

.wzpo11zau {
  stop-color: var(--svg-color--955678, #955678);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xgtnudb2w {
  cx: 13.509px;
  cy: 9.978px;
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.39px;
  ry: 0.197px;
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xksrntfob {
  stop-color: var(--svg-color--b3a9bc, #B3A9BC);
}

.xn_fidfol {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
  stop-opacity: 0;
}

.xn5dksb-u {
  stop-color: var(--svg-color--464646, #464646);
}

.xon9p4yuw {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M14.195 8.389a2.15 2.15 0 0 0-1.417.37a.475.475 0 1 1-.53-.788a3.1 3.1 0 0 1 2.037-.528a.475.475 0 1 1-.09.946");
}

.xp5tyrb9h {
  d: path("M5.77 11.561c2.243-2.143 5.052-3.376 6.334-3.816l4.063 12.312h-5.891c-2.916-1.118-4.43-4.528-4.986-6.894a1.68 1.68 0 0 1 .48-1.602");
}

.xvn4q2b0p {
  fill: var(--svg-color--000, #000);
  d: path("M17.638 10.49a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.236");
}

.xy4gpnq9q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.598 8.279a2.95 2.95 0 0 0-1.936-.504");
}

.y5ykz5l3i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.513 8.279a2.63 2.63 0 0 1 1.727-.45");
}

.yomd27bxe {
  stop-color: var(--svg-color--453455, #453455);
  stop-opacity: 0;
}

.ypzxpcc2j {
  stop-color: var(--svg-color--f73397, #F73397);
  stop-opacity: 0;
}

.yucjgfb4f {
  stop-color: var(--svg-color--4d4d4d, #4D4D4D);
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z256j7ndo {
  stop-color: var(--svg-color--744e4c, #744E4C);
}

.z7yo4atmg {
  d: path("M20.945 12.31c.037-1.41.045-2.426.076-3.638c.49-.32 1.231-.682 1.833-.97c.214-.103.456.02.461.257c.014.641-.118 1.504-.656 2.528c-.62 1.215-1.21 1.655-1.714 1.823");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.z8m-hreok {
  stop-color: var(--svg-color--47304f, #47304F);
}

.zajm34fcf {
  stop-color: var(--svg-color--e32d3d, #E32D3D);
}

.zanwp13zc {
  fill: var(--svg-color--decee7, #DECEE7);
  fill-rule: evenodd;
  d: path("M16.458 19.113a.125.125 0 0 1 .141.107l.649 4.671a.125.125 0 1 1-.248.035l-.648-4.672a.125.125 0 0 1 .106-.141");
}

.zpfzvmboh {
  d: path("M6.27 11.106q-.255.22-.5.455a1.68 1.68 0 0 0-.48 1.602c.461 1.964 1.584 4.649 3.62 6.143l1.038-.694c-2.588-1.72-3.697-4.97-3.678-7.506");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zxxizob4i {
  stop-color: var(--svg-color--c52133, #C52133);
}

</style>
