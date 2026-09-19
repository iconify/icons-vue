<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3yRybc)" class="h-wrbvbaj"/><g filter="url(#i0VB69x)"><path fill="url(#iXLRPoM)" class="fir_x3lkx"/><path fill="url(#ir4VsFc)" class="fir_x3lkx"/></g><path fill="url(#itzBUue)" class="xp5tyrb9h"/><g filter="url(#isdE3zc)"><path fill="url(#iKfkMAc)" class="zpfzvmboh"/></g><path fill="url(#iYEOHJJ)" class="pwbqwxbuo"/><path fill="url(#irYowge)" class="pwbqwxbuo"/><path fill="url(#i3IxmcV)" class="pwbqwxbuo"/><path fill="url(#i0hzJZc)" class="pwbqwxbuo"/><path fill="url(#ilvXoGd)" class="pwbqwxbuo"/><path fill="url(#izOfPJe)" class="pwbqwxbuo"/><path fill="url(#izD4dme)" class="pwbqwxbuo"/><path fill="url(#iOqaXXb)" class="pwbqwxbuo"/><path fill="url(#icCQoSd)" class="jcv675w6u"/><path fill="url(#iUp0Wxb)" class="jcv675w6u"/><path fill="url(#iM3yElc)" class="qyo-sfboi"/><path fill="url(#iXJYGHe)" class="qyo-sfboi"/><path fill="url(#ipKjL7b)" class="qyo-sfboi"/><path fill="url(#isG10Od)" class="qiw2lo8xj"/><path fill="url(#idf2Bve)" class="qiw2lo8xj"/><path fill="url(#iJpq4RY)" class="qiw2lo8xj"/><g filter="url(#i2VSz0b)"><path class="oegqju6nx"/></g><g filter="url(#iBnfgGd)"><path class="qpjplr-8j"/></g><g filter="url(#ihTk5gd)"><path fill="url(#iyhNkne)" class="fom0o-b5s"/><path fill="url(#iwRKhAd)" class="fom0o-b5s"/><path fill="url(#iV0zBAc)" class="fom0o-b5s"/></g><g filter="url(#ii5dh0c)"><path fill="url(#i0X2fhd)" class="fpuz4ebbn"/></g><g filter="url(#iJgjzjd)"><path class="iekgv_oar"/><path fill="url(#i166U6c)" class="dwjylab2g"/><path fill="url(#imDUJiZ)" class="dwjylab2g"/><path fill="url(#iK5ctLc)" class="dwjylab2g"/><path fill="url(#iDF3jzd)" class="dwjylab2g"/><path fill="url(#iCU5Hoc)" class="dwjylab2g"/><path fill="url(#imONIDb)" class="dwjylab2g"/></g><g filter="url(#iTbwTmP)"><path stroke="url(#iRsdWsw)" class="pr-i1fb-b"/></g><path class="qfp_zpbmu"/><path fill="url(#iW3m3ZG)" class="o22onf4kj"/><path class="ej8y-3brn"/><path clip-rule="evenodd" class="keb-8ctdm"/><path fill="url(#iEIkO4b)" clip-rule="evenodd" class="jvm-g58di"/><path clip-rule="evenodd" class="kavwzfgga"/><path fill="url(#iS9ZmDb)" clip-rule="evenodd" class="w9-gl-bca"/><g filter="url(#iNDykhd)"><path class="fegitei5f"/></g><g filter="url(#i1e7BTD)"><path class="shtm8sb5v"/><path fill="url(#iwMXtuc)" class="pm9qglbyu"/><path fill="url(#ia3XWKc)" class="pm9qglbyu"/><path fill="url(#ihDGREe)" class="pm9qglbyu"/><path fill="url(#iugxlGc)" class="pm9qglbyu"/></g><path class="j7d6tdb2g"/><path fill="url(#iBF3bmd)" class="c8p9zqb6v"/><path class="o-vl_tbgb"/><g filter="url(#iecYfpD)"><path class="nknl4u8nb"/><path fill="url(#iUA2J8q)" class="oug_496gg"/></g><g filter="url(#icURpOD)"><path fill="url(#iawMBsb)" class="tik5rtblr"/></g><path class="qriicvbhe"/><path fill="url(#i7Mx4Bd)" class="d73walu2l"/><path class="flz2c8iyl"/><g filter="url(#ijYRtqC)"><path fill="url(#iMJRHhX)" class="q4uqrvgrz"/></g><g filter="url(#icRJoxO)"><ellipse transform="rotate(-27.914 13.509 9.978)" class="xgtnudb2w"/><ellipse fill="url(#iJ8zpLc)" transform="rotate(-27.914 13.509 9.978)" class="klq3puw7i"/></g><path fill="url(#iAq3Ayd)" class="fp4672bcn"/><path fill="url(#ioVzSnd)" class="fp4672bcn"/><path fill="url(#iuQfdCe)" class="fp4672bcn"/><path fill="url(#ifkY8wb)" class="lpnng9rjr"/><path fill="url(#iXYDXbd)" class="lpnng9rjr"/><g filter="url(#iGStLuK)"><path fill="url(#iRsJhRd)" class="u_per4bve"/><path fill="url(#iLouQpc)" class="u_per4bve"/></g><g filter="url(#ijdkyde)"><path fill="url(#iAWX0ud)" class="lmxk8n8zo"/></g><path fill="url(#imm8slc)" class="ydy3gyb-u"/><path fill="url(#iYdgarb)" class="ydy3gyb-u"/><path fill="url(#iPzLIVb)" class="ydy3gyb-u"/><path fill="url(#iBEJh9q)" class="ydy3gyb-u"/><path stroke="url(#ivx9Tjd)" class="lrj77tebu"/><g filter="url(#izmHsuC)"><path stroke="url(#iA35frd)" class="en6kh9i1y"/></g><g filter="url(#iF3R28c)"><path stroke="url(#iaQgqQv)" class="y5ykz5l3i"/></g><path stroke="url(#i689LGd)" class="rar1_ifed"/><g filter="url(#iIAdVOd)"><path stroke="url(#iBZJrNd)" class="xy4gpnq9q"/></g><g filter="url(#ir6J2cb)"><path fill="url(#iZWS3Ie)" class="gdwph8byq"/></g><defs><radialGradient id="i3yRybc" cx="0" cy="0" r="1" gradientTransform="matrix(3.93792 -7.29125 14.315 7.73138 20.553 16.769)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="1" class="gdsiwyiyr"/></radialGradient><radialGradient id="iXLRPoM" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92122 7.06151 -2.22108 -.91882 27.573 12.245)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jpxim8b1x"/><stop offset="1" class="n52c8qgao"/></radialGradient><radialGradient id="ir4VsFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 4.15626 -.42744 -.1607 27.323 12.713)" gradientUnits="userSpaceOnUse"><stop class="fg6i_oqme"/><stop offset="1" class="ih2ibv29b"/></radialGradient><radialGradient id="itzBUue" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58397 -6.61442 12.98618 -8.99977 12.493 17.046)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="0" class="pxp9rxlhv"/><stop offset="1" class="e06hnni3m"/></radialGradient><radialGradient id="irYowge" cx="0" cy="0" r="1" gradientTransform="rotate(-118.874 16.525 8.487)scale(12.4902 33.343)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="f6lcb9bkn"/><stop offset="1" class="jtbt9y0gz"/></radialGradient><radialGradient id="i3IxmcV" cx="0" cy="0" r="1" gradientTransform="rotate(-65.133 29.239 1.614)scale(12.2618 28.8332)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="r21k1wzrc"/><stop offset="1" class="b2cn2_uce"/></radialGradient><radialGradient id="i0hzJZc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71875 0 0 -14.5625 23.292 23.338)" gradientUnits="userSpaceOnUse"><stop class="odfe47amh"/><stop offset="1" class="carxtabzu"/></radialGradient><radialGradient id="ilvXoGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6875 -.22656 0 19.206 16.744)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="z8m-hreok"/><stop offset="1" class="ehu1o5vid"/></radialGradient><radialGradient id="izOfPJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 3.5 -5.72433 -1.89104 12.667 16.37)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="a75cnrb-k"/><stop offset="1" class="ri_i1lblj"/></radialGradient><radialGradient id="icCQoSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6045 2.48458 0 23.855 29.963)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="vbb18ixfb"/><stop offset="1" class="p5bq_2b9f"/></radialGradient><radialGradient id="iUp0Wxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5781 .52466 0 23.11 29.963)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l0d7sccpf"/><stop offset="1" class="r3f5xvbmj"/></radialGradient><radialGradient id="iM3yElc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.2188 2.95614 0 7.292 29.963)" gradientUnits="userSpaceOnUse"><stop class="oj4dw6cda"/><stop offset="1" class="jsbpdr4yj"/></radialGradient><radialGradient id="iXJYGHe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21875 0 0 -14.5625 8.542 29.494)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ihp7x-bon"/><stop offset="1" class="g_z46f3jl"/></radialGradient><radialGradient id="iyhNkne" cx="0" cy="0" r="1" gradientTransform="rotate(-169.531 10.424 8.323)scale(4.12749 5.76206)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="ea1q1sbfd"/><stop offset="1" class="cy4s12tgo"/><stop offset="1" class="cy4s12tgo"/></radialGradient><radialGradient id="iwRKhAd" cx="0" cy="0" r="1" gradientTransform="matrix(.375 3.375 -7.05108 .78345 14.73 14.37)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="jzwike70j"/><stop offset="1" class="gbck5ebgo"/></radialGradient><radialGradient id="iV0zBAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87568 -2.6343 0 15.948 16.4)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="aizyt6k5q"/><stop offset="1" class="gvkakgbfc"/></radialGradient><radialGradient id="i166U6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.56252 8.90625 -6.9019 -.43592 19.6 8.467)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="i7q65hbym"/><stop offset="1" class="l0_fn5b0x"/></radialGradient><radialGradient id="imDUJiZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -11.3027 0 15.937 8.404)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="haloy8y2o"/><stop offset="1" class="zgi9r7gea"/></radialGradient><radialGradient id="iK5ctLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51563 3.44528 0 15.937 17.154)" gradientUnits="userSpaceOnUse"><stop class="af_da6bwp"/><stop offset="1" class="q8bgk8b-m"/></radialGradient><radialGradient id="iDF3jzd" cx="0" cy="0" r="1" gradientTransform="scale(13.1395 11.2344)rotate(-90 1.3 .087)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="k7rg44qrz"/><stop offset="1" class="x5wnyrbme"/></radialGradient><radialGradient id="iCU5Hoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 1.54688 0 18.428 9.7)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="jter3kb4y"/><stop offset="1" class="ayctmyypx"/></radialGradient><radialGradient id="imONIDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30469 1.49364 0 13.787 9.693)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="j-2rutb6v"/><stop offset="1" class="k2g-xbbbp"/></radialGradient><radialGradient id="iBF3bmd" cx="0" cy="0" r="1" gradientTransform="rotate(-117.266 12.234 -.373)scale(.57126 .90459)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iUA2J8q" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.919 10.158)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="i7Mx4Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26172 -.50781 .80412 -.41444 13.803 10.33)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iJ8zpLc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.814 -1.495)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="ioVzSnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.79688 2.67188 -.8949 -.2669 23.526 7.854)" gradientUnits="userSpaceOnUse"><stop class="rvhhg_4it"/><stop offset="1" class="e4gg3dbwm"/></radialGradient><radialGradient id="iXYDXbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.29688 .47656 -2.49611 -1.55496 10.48 8.378)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="y2apkgedy"/><stop offset="1" class="r54sjr93u"/></radialGradient><radialGradient id="iRsJhRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.59772 -1.40625 .5978 .67918 20.98 10.338)" gradientUnits="userSpaceOnUse"><stop class="gv6p65gra"/><stop offset="1" class="vn-dnfmxn"/></radialGradient><radialGradient id="iLouQpc" cx="0" cy="0" r="1" gradientTransform="matrix(.94064 -.03119 .05856 1.76633 20.798 10.317)" gradientUnits="userSpaceOnUse"><stop class="tl7x7-b-x"/><stop offset="1" class="ffov9zhbj"/></radialGradient><radialGradient id="iAWX0ud" cx="0" cy="0" r="1" gradientTransform="rotate(-132.082 7.744 2.73)scale(2.41247 2.17677)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="v-eqfrben"/><stop offset="1" class="uu4r1rb8r"/></radialGradient><radialGradient id="imm8slc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.93271 6.4606 -9.67475 -7.38675 20.88 4.029)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ja62qnbvn"/></radialGradient><radialGradient id="iYdgarb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.114 9.345 .93)scale(6.55215 1.19385)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="mzjok2vtv"/><stop offset="1" class="moen_vfyr"/></radialGradient><radialGradient id="iPzLIVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -1.25 1.2273 1.2273 20.287 3.716)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="xn5dksb-u"/><stop offset="1" class="otpekjb_s"/></radialGradient><radialGradient id="iBEJh9q" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.15625 -2.7392 0 15.948 1.904)" gradientUnits="userSpaceOnUse"><stop class="yucjgfb4f"/><stop offset="1" class="neb43bcvz"/></radialGradient><radialGradient id="ivx9Tjd" cx="0" cy="0" r="1" gradientTransform="matrix(.81311 .46108 -.86614 1.52744 12.563 7.904)" gradientUnits="userSpaceOnUse"><stop class="z0crr23qd"/><stop offset="1" class="y2ao_obhc"/></radialGradient><radialGradient id="i689LGd" cx="0" cy="0" r="1" gradientTransform="rotate(150.445 8.666 6.513)scale(.93474 1.75592)" gradientUnits="userSpaceOnUse"><stop class="z0crr23qd"/><stop offset="1" class="y2ao_obhc"/></radialGradient><radialGradient id="iZWS3Ie" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 -1.15625 6.34532 -.68598 17.482 4.85)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="ing6ksb7p"/><stop offset=".789" class="b-0vp4bih"/></radialGradient><linearGradient id="iKfkMAc" x1="5.54" x2="8.862" y1="12" y2="18.369" gradientUnits="userSpaceOnUse"><stop class="imlbmc2sy"/><stop offset="1" class="h7wwwp44w"/></linearGradient><linearGradient id="iYEOHJJ" x1="15.935" x2="15.935" y1="15.588" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="plsegxa8t"/><stop offset="1" class="dbg8b7bda"/></linearGradient><linearGradient id="izD4dme" x1="8.661" x2="8.938" y1="29.963" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="rq6u1obxj"/><stop offset="1" class="yomd27bxe"/></linearGradient><linearGradient id="iOqaXXb" x1="23.206" x2="22.776" y1="29.963" y2="29.963" gradientUnits="userSpaceOnUse"><stop offset=".136" class="i0lopbdha"/><stop offset="1" class="w11i7m31i"/></linearGradient><linearGradient id="ipKjL7b" x1="8.759" x2="7.51" y1="28.776" y2="28.776" gradientUnits="userSpaceOnUse"><stop class="k6ta6mb-r"/><stop offset="1" class="drixk4bdm"/></linearGradient><linearGradient id="isG10Od" x1="15.939" x2="15.939" y1="20.932" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="zajm34fcf"/><stop offset="1" class="puh_1hb6q"/></linearGradient><linearGradient id="idf2Bve" x1="15.939" x2="15.939" y1="29.963" y2="27.307" gradientUnits="userSpaceOnUse"><stop class="ou_12nqfl"/><stop offset="1" class="ypzxpcc2j"/></linearGradient><linearGradient id="iJpq4RY" x1="19.542" x2="17.698" y1="28.776" y2="28.776" gradientUnits="userSpaceOnUse"><stop offset=".119" class="zxxizob4i"/><stop offset="1" class="u7u0nyv_w"/></linearGradient><linearGradient id="i0X2fhd" x1="15.935" x2="15.935" y1="17.854" y2="25.882" gradientUnits="userSpaceOnUse"><stop class="gmn9ea1yo"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="iRsdWsw" x1="15.948" x2="15.948" y1="14.705" y2="14.284" gradientUnits="userSpaceOnUse"><stop class="tmd-skbgv"/><stop offset="1" class="z_e79kubw"/></linearGradient><linearGradient id="iW3m3ZG" x1="17.479" x2="16.94" y1="13.893" y2="14.135" gradientUnits="userSpaceOnUse"><stop class="fqd3y7eiz"/><stop offset="1" class="joyqtdb2o"/></linearGradient><linearGradient id="iEIkO4b" x1="16.351" x2="16.479" y1="19.112" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iS9ZmDb" x1="15.546" x2="15.417" y1="19.112" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iwMXtuc" x1="15.101" x2="16.04" y1="11.807" y2="11.807" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="ia3XWKc" x1="17.088" x2="15.879" y1="12.182" y2="12.115" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="ihDGREe" x1="16.161" x2="16.161" y1="12.872" y2="12.299" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iugxlGc" x1="15.966" x2="15.966" y1="10.189" y2="11.135" gradientUnits="userSpaceOnUse"><stop class="az5wi_bef"/><stop offset="1" class="h1lv9vb1d"/></linearGradient><linearGradient id="iawMBsb" x1="18.886" x2="18.63" y1="10.136" y2="10.301" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iMJRHhX" x1="14.524" x2="14.21" y1="10.128" y2="10.322" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iAq3Ayd" x1="21.542" x2="22.417" y1="8.432" y2="11.119" gradientUnits="userSpaceOnUse"><stop class="x9i77q88f"/><stop offset="1" class="z5dqrdruq"/></linearGradient><linearGradient id="iuQfdCe" x1="21.862" x2="22.131" y1="8.174" y2="8.596" gradientUnits="userSpaceOnUse"><stop class="jbde53ben"/><stop offset="1" class="lh964wkyr"/></linearGradient><linearGradient id="ifkY8wb" x1="8.979" x2="11.385" y1="10.511" y2="9.511" gradientUnits="userSpaceOnUse"><stop class="zof5jdb0e"/><stop offset="1" class="lgpsfqpss"/></linearGradient><linearGradient id="iA35frd" x1="14.302" x2="12.333" y1="7.576" y2="8.256" gradientUnits="userSpaceOnUse"><stop class="s0qsib-ln"/><stop offset="1" class="i5bggbceb"/></linearGradient><linearGradient id="iaQgqQv" x1="14.302" x2="12.615" y1="7.49" y2="8.048" gradientUnits="userSpaceOnUse"><stop class="i5bggbceb"/><stop offset="1" class="s0qsib-ln"/></linearGradient><linearGradient id="iBZJrNd" x1="17.593" x2="19.8" y1="7.394" y2="8.156" gradientUnits="userSpaceOnUse"><stop class="s0qsib-ln"/><stop offset="1" class="i5bggbceb"/></linearGradient><filter id="i0VB69x" width="4.702" height="8.2" x="22.301" y="11.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1216"/></filter><filter id="isdE3zc" width="4.902" height="8.4" x="5.146" y="11.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.321569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1216"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1216" result="effect2_innerShadow_4002_1216"/></filter><filter id="i2VSz0b" width="6.968" height="4.815" x="12.464" y="15.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".25"/></filter><filter id="iBnfgGd" width="6.431" height="9.028" x="12.527" y="17.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".25"/></filter><filter id="ihTk5gd" width="6.43" height="4.36" x="12.733" y="15.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.698039 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1216"/></filter><filter id="ii5dh0c" width="5.531" height="8.006" x="13.22" y="18.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.67451 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1216"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.643137 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1216" result="effect2_innerShadow_4002_1216"/></filter><filter id="iJgjzjd" width="11.31" height="13.063" x="10.782" y="4.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.623529 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1216"/></filter><filter id="iTbwTmP" width="3.566" height="1.546" x="14.165" y="13.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".05"/></filter><filter id="iNDykhd" width="3.262" height="4.184" x="14.096" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".375"/></filter><filter id="i1e7BTD" width="2.079" height="2.884" x="14.927" y="10.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".05"/></filter><filter id="iecYfpD" width=".787" height=".697" x="17.413" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".05"/></filter><filter id="icURpOD" width=".892" height=".914" x="18.253" y="9.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".1"/></filter><filter id="ijYRtqC" width=".987" height="1.041" x="13.807" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".1"/></filter><filter id="icRJoxO" width=".914" height=".705" x="13.052" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".05"/></filter><filter id="iGStLuK" width="1.798" height="3.38" x="20.88" y="8.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".05"/></filter><filter id="ijdkyde" width="1.817" height="3.395" x="9.192" y="8.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".05"/></filter><filter id="izmHsuC" width="2.477" height="1.211" x="12.138" y="7.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".125"/></filter><filter id="iF3R28c" width="2.477" height="1.211" x="12.138" y="7.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".125"/></filter><filter id="iIAdVOd" width="2.685" height="1.267" x="17.287" y="7.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".125"/></filter><filter id="ir6J2cb" width="5.117" height="2.477" x="15.74" y="3.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1216" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-vampire" /></template>
<style>
.a75cnrb-k {
  stop-color: var(--svg-color--47374c, #47374C);
}

.af_da6bwp {
  stop-color: var(--svg-color--df8a85, #DF8A85);
}

.aizyt6k5q {
  stop-color: var(--svg-color--bb789e, #BB789E);
}

.ayctmyypx {
  stop-color: var(--svg-color--ffbe26, #FFBE26);
  stop-opacity: 0;
}

.az5wi_bef {
  stop-color: var(--svg-color--fecf3c, #FECF3C);
}

.b-0vp4bih {
  stop-color: var(--svg-color--454445, #454445);
  stop-opacity: 0;
}

.b2cn2_uce {
  stop-color: var(--svg-color--60506b, #60506B);
}

.c8p9zqb6v {
  d: path("M18.15 9.597a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.carxtabzu {
  stop-color: var(--svg-color--604f70, #604F70);
  stop-opacity: 0;
}

.cy4s12tgo {
  stop-color: var(--svg-color--d7bdcd, #D7BDCD);
}

.d73walu2l {
  d: path("M13.778 9.597a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.dbg8b7bda {
  stop-color: var(--svg-color--553d71, #553D71);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.dwjylab2g {
  d: path("M10.783 7.58a3 3 0 0 1 2.999-3.082h4.31a3 3 0 0 1 3 3.06l-.198 6.36c-.035 1.77-1.408 3.142-3.178 3.142h-3.51c-1.761 0-3.07-1.351-3.194-3.118z");
}

.e06hnni3m {
  stop-color: var(--svg-color--e73665, #E73665);
}

.e4gg3dbwm {
  stop-color: var(--svg-color--ffd749, #FFD749);
  stop-opacity: 0;
}

.ea1q1sbfd {
  stop-color: var(--svg-color--f6e6f8, #F6E6F8);
}

.ehu1o5vid {
  stop-color: var(--svg-color--47304f, #47304F);
  stop-opacity: 0;
}

.ej8y-3brn {
  fill: var(--svg-color--faceeb, #FACEEB);
  d: path("m14.735 14.62l.396-.895a3.2 3.2 0 0 1-.623-.263c-.103-.058-.249.043-.22.156l.259.986a.1.1 0 0 0 .188.016");
}

.en6kh9i1y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.513 8.365a2.63 2.63 0 0 1 1.727-.45");
}

.f1lm8sbjk {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
}

.f6lcb9bkn {
  stop-color: var(--svg-color--56475f, #56475F);
  stop-opacity: 0;
}

.fegitei5f {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.69 10.635l-.82 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.377-.283-.377-.395 0");
}

.ffov9zhbj {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
  stop-opacity: 0;
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

.fp4672bcn {
  d: path("M20.945 12.31c.037-1.41.045-2.426.076-3.638c.49-.321 1.231-.682 1.833-.97c.214-.103.456.02.461.257c.014.641-.118 1.503-.656 2.528c-.62 1.215-1.21 1.655-1.714 1.822");
}

.fpuz4ebbn {
  d: path("m14.084 19.6l-.859 5.24a.402.402 0 0 0 .602.409l.202-.118a.51.51 0 0 1 .553.027l.706.514a1.1 1.1 0 0 0 1.294 0l.706-.514a.51.51 0 0 1 .553-.027l.202.117a.402.402 0 0 0 .602-.408l-.857-5.235c-.81-.504-1.855-1.279-1.855-1.279s-1.107.796-1.85 1.273");
}

.fqd3y7eiz {
  stop-color: var(--svg-color--ffe5ff, #FFE5FF);
}

.ft5dv1b6b {
  fill: none;
}

.g_z46f3jl {
  stop-color: var(--svg-color--655578, #655578);
}

.gbck5ebgo {
  stop-color: var(--svg-color--a99494, #A99494);
  stop-opacity: 0;
}

.gdsiwyiyr {
  stop-color: var(--svg-color--e82e5c, #E82E5C);
}

.gdwph8byq {
  d: path("M16.45 4.287c-.25.302-.42.947-.46 1.468c.352-.992.773-1.197 1.258-1.293c1.139-.146 2.78.484 3.359.997l-.374-.997c-2.665-1.135-3.425-.61-3.783-.175");
}

.gmn9ea1yo {
  stop-color: var(--svg-color--f4dff7, #F4DFF7);
}

.gv6p65gra {
  stop-color: var(--svg-color--ffc234, #FFC234);
}

.gvkakgbfc {
  stop-color: var(--svg-color--c896a8, #C896A8);
  stop-opacity: 0;
}

.h-wrbvbaj {
  d: path("M26.478 11.561c-2.243-2.143-5.051-3.376-6.334-3.816l-4.062 12.312h5.89c2.916-1.118 4.431-4.528 4.986-6.894a1.68 1.68 0 0 0-.48-1.602");
}

.h1lv9vb1d {
  stop-color: var(--svg-color--fecf3c, #FECF3C);
  stop-opacity: 0;
}

.h1sgipbfm {
  stop-color: var(--svg-color--d82535, #D82535);
}

.h7wwwp44w {
  stop-color: var(--svg-color--302736, #302736);
}

.haloy8y2o {
  stop-color: var(--svg-color--fba43a, #FBA43A);
  stop-opacity: 0;
}

.hl4dixbko {
  stop-color: var(--svg-color--ff6d74, #FF6D74);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.i0lopbdha {
  stop-color: var(--svg-color--4a2f65, #4A2F65);
}

.i5bggbceb {
  stop-color: var(--svg-color--4f494b, #4F494B);
}

.i7q65hbym {
  stop-color: var(--svg-color--ffe847, #FFE847);
}

.iekgv_oar {
  fill: var(--svg-color--ffad2a, #FFAD2A);
  d: path("M10.783 7.58a3 3 0 0 1 2.999-3.082h4.31a3 3 0 0 1 3 3.06l-.198 6.36c-.035 1.77-1.408 3.142-3.178 3.142h-3.51c-1.761 0-3.07-1.351-3.194-3.118z");
}

.ih2ibv29b {
  stop-color: var(--svg-color--574b64, #574B64);
  stop-opacity: 0;
}

.ihp7x-bon {
  stop-color: var(--svg-color--655578, #655578);
  stop-opacity: 0;
}

.imlbmc2sy {
  stop-color: var(--svg-color--554961, #554961);
}

.ing6ksb7p {
  stop-color: var(--svg-color--454445, #454445);
}

.j-2rutb6v {
  stop-color: var(--svg-color--f09526, #F09526);
}

.j7d6tdb2g {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.356 9.325c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.ja62qnbvn {
  stop-color: var(--svg-color--252525, #252525);
}

.jbde53ben {
  stop-color: var(--svg-color--c69824, #C69824);
}

.jcv675w6u {
  d: path("M23.11 18.359v11.604h3.762V26.73c0-3.295-1.456-6.31-3.761-8.37");
}

.joyqtdb2o {
  stop-color: var(--svg-color--ffd9f6, #FFD9F6);
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

.jter3kb4y {
  stop-color: var(--svg-color--ffbe26, #FFBE26);
}

.jvm-g58di {
  fill-rule: evenodd;
  d: path("M16.458 19.113a.125.125 0 0 1 .141.106l.649 4.672a.125.125 0 1 1-.248.035l-.648-4.672a.125.125 0 0 1 .106-.141");
}

.jzwike70j {
  stop-color: var(--svg-color--a99494, #A99494);
}

.k2g-xbbbp {
  stop-color: var(--svg-color--f09526, #F09526);
  stop-opacity: 0;
}

.k6ta6mb-r {
  stop-color: var(--svg-color--423153, #423153);
}

.k7rg44qrz {
  stop-color: var(--svg-color--d19303, #D19303);
  stop-opacity: 0;
}

.kavwzfgga {
  fill: var(--svg-color--decee8, #DECEE8);
  fill-rule: evenodd;
  d: path("M15.438 19.113a.125.125 0 0 0-.141.106l-.649 4.672a.125.125 0 1 0 .248.035l.649-4.672a.125.125 0 0 0-.107-.141");
}

.keb-8ctdm {
  fill: var(--svg-color--decee7, #DECEE7);
  fill-rule: evenodd;
  d: path("M16.458 19.113a.125.125 0 0 1 .141.106l.649 4.672a.125.125 0 1 1-.248.035l-.648-4.672a.125.125 0 0 1 .106-.141");
}

.klq3puw7i {
  cx: 13.509px;
  cy: 9.978px;
  rx: 0.39px;
  ry: 0.197px;
}

.l0_fn5b0x {
  stop-color: var(--svg-color--ffe847, #FFE847);
  stop-opacity: 0;
}

.l0d7sccpf {
  stop-color: var(--svg-color--48335e, #48335E);
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lft-zacfy {
  stop-color: var(--svg-color--ff242f, #FF242F);
}

.lgpsfqpss {
  stop-color: var(--svg-color--cf7e22, #CF7E22);
}

.lh964wkyr {
  stop-color: var(--svg-color--f1b52e, #F1B52E);
  stop-opacity: 0;
}

.lmxk8n8zo {
  d: path("m10.778 9.338l.062 1.134l.069 1.24C9.833 10.847 9.41 9.59 9.294 8.765c-.028-.2.19-.318.355-.204z");
}

.lpnng9rjr {
  d: path("M10.846 8.669c.034 1.21.073 2.413.109 3.638c-.507-.163-1.116-.605-1.744-1.835c-.538-1.025-.67-1.887-.656-2.528c.005-.237.247-.36.46-.258c.61.292 1.337.659 1.83.983");
}

.lrj77tebu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M12.513 8.365a2.63 2.63 0 0 1 1.727-.45");
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.moen_vfyr {
  stop-color: var(--svg-color--47423f, #47423F);
  stop-opacity: 0;
}

.mzjok2vtv {
  stop-color: var(--svg-color--47423f, #47423F);
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

.o-vl_tbgb {
  fill: var(--svg-color--000, #000);
  d: path("M17.638 10.49a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
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

.plsegxa8t {
  stop-color: var(--svg-color--503d5d, #503D5D);
}

.pm9qglbyu {
  d: path("m15.583 10.471l-.531 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.377-.646-.377-.766 0");
}

.pr-i1fb-b {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.513 13.463a2.94 2.94 0 0 0 2.87 0c.077-.042.17.023.143.107c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.084.066-.149.143-.107Z");
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

.q4uqrvgrz {
  d: path("M14.594 10.385c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.q8bgk8b-m {
  stop-color: var(--svg-color--df8a85, #DF8A85);
  stop-opacity: 0;
}

.qfp_zpbmu {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.513 13.463a2.94 2.94 0 0 0 2.87 0c.077-.042.17.023.143.107c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.084.066-.149.143-.107");
}

.qhxuaybfw {
  stop-color: var(--svg-color--dfcfe8, #DFCFE8);
  stop-opacity: 0;
}

.qiw2lo8xj {
  d: path("M12.733 29.963V16.071a10.7 10.7 0 0 1 3.183-.483c1.124 0 2.208.175 3.23.497v13.878z");
}

.qpjplr-8j {
  fill: var(--svg-color--c91a3b, #C91A3B);
  d: path("m14.177 17.916l-1.144 6.986a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.028l.706.513a1.1 1.1 0 0 0 1.294 0l.706-.513a.51.51 0 0 1 .553-.028l.202.118a.402.402 0 0 0 .602-.409l-1.145-6.986z");
}

.qriicvbhe {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.571 9.325c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
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

.r54sjr93u {
  stop-color: var(--svg-color--d88c25, #D88C25);
  stop-opacity: 0;
}

.rar1_ifed {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M19.466 8.365a2.63 2.63 0 0 0-1.726-.45");
}

.ri_i1lblj {
  stop-color: var(--svg-color--47374c, #47374C);
  stop-opacity: 0;
}

.rq6u1obxj {
  stop-color: var(--svg-color--453455, #453455);
}

.rvhhg_4it {
  stop-color: var(--svg-color--ffd749, #FFD749);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s0qsib-ln {
  stop-color: var(--svg-color--4f494b, #4F494B);
  stop-opacity: 0;
}

.shtm8sb5v {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.583 10.471l-.531 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.377-.646-.377-.766 0");
}

.tik5rtblr {
  d: path("M18.945 10.372a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.tmd-skbgv {
  stop-color: var(--svg-color--fdb032, #FDB032);
}

.u_per4bve {
  d: path("m20.98 11.696l.131-2.371l1.11-.764c.165-.114.383.004.355.204c-.117.82-.534 2.067-1.596 2.931");
}

.u7u0nyv_w {
  stop-color: var(--svg-color--dd2864, #DD2864);
  stop-opacity: 0;
}

.uu4r1rb8r {
  stop-color: var(--svg-color--da8421, #DA8421);
  stop-opacity: 0;
}

.uw1qucxdm {
  stop-color: var(--svg-color--d2bdd8, #D2BDD8);
}

.v-eqfrben {
  stop-color: var(--svg-color--da8421, #DA8421);
}

.vbb18ixfb {
  stop-color: var(--svg-color--6b5a80, #6B5A80);
}

.vn-dnfmxn {
  stop-color: var(--svg-color--f9b42e, #F9B42E);
}

.vo8nxhb-a {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
  stop-opacity: 0;
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w11i7m31i {
  stop-color: var(--svg-color--665579, #665579);
  stop-opacity: 0;
}

.w9-gl-bca {
  fill-rule: evenodd;
  d: path("M15.438 19.113a.125.125 0 0 0-.141.106l-.649 4.672a.125.125 0 1 0 .248.035l.649-4.672a.125.125 0 0 0-.107-.141");
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x5wnyrbme {
  stop-color: var(--svg-color--d19303, #D19303);
}

.x9i77q88f {
  stop-color: var(--svg-color--eeb22c, #EEB22C);
}

.xgtnudb2w {
  cx: 13.509px;
  cy: 9.978px;
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.39px;
  ry: 0.197px;
}

.xn_fidfol {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
  stop-opacity: 0;
}

.xn5dksb-u {
  stop-color: var(--svg-color--464646, #464646);
}

.xp5tyrb9h {
  d: path("M5.77 11.561c2.243-2.143 5.052-3.376 6.334-3.816l4.063 12.312h-5.891c-2.916-1.118-4.43-4.528-4.986-6.894a1.68 1.68 0 0 1 .48-1.602");
}

.xy4gpnq9q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.598 8.279a2.95 2.95 0 0 0-1.936-.504");
}

.y2ao_obhc {
  stop-color: var(--svg-color--321931, #321931);
}

.y2apkgedy {
  stop-color: var(--svg-color--a86c06, #A86C06);
}

.y5ykz5l3i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.513 8.279a2.63 2.63 0 0 1 1.727-.45");
}

.ydy3gyb-u {
  d: path("m10.37 10.082l-.617-2.736c-.117-.426-.242-1.394.024-2.013c.264-.612.68-.836 1.05-1.035c.125-.066.243-.13.35-.205q.123-.086.235-.16c.298-.201.536-.361.875-.762c.422-.5 1.056-1.005 1.76-1.114c.406-.064.784.036 1.146.132c.259.069.509.135.755.137c.246-.002.497-.068.755-.137c.362-.096.74-.196 1.147-.132c.703.109 1.337.613 1.76 1.114c.338.4.576.56.874.762l.236.16c.106.075.224.139.348.205c.37.199.787.423 1.05 1.035c.268.62.142 1.587.025 2.013l-.616 2.736a.55.55 0 0 1-.533.407l.023-1.72c0-1.345-.334-2.386-1.032-3.034c-.982-.91-1.858-.91-2.483-.91c-.675 0-.847.379-1.041.745l-.09.165c-.155.268-.336.337-.423.33c-.087.007-.267-.062-.42-.33q-.048-.082-.091-.165c-.195-.366-.368-.745-1.043-.745c-.625 0-1.5 0-2.483.91c-.697.648-1.032 1.69-1.032 3.034l.021 1.72a.546.546 0 0 1-.53-.407");
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

.z_e79kubw {
  stop-color: var(--svg-color--fdb032, #FDB032);
  stop-opacity: 0;
}

.z0crr23qd {
  stop-color: var(--svg-color--352a2e, #352A2E);
}

.z5dqrdruq {
  stop-color: var(--svg-color--f6b930, #F6B930);
}

.z8m-hreok {
  stop-color: var(--svg-color--47304f, #47304F);
}

.zajm34fcf {
  stop-color: var(--svg-color--e32d3d, #E32D3D);
}

.zgi9r7gea {
  stop-color: var(--svg-color--de8252, #DE8252);
}

.zof5jdb0e {
  stop-color: var(--svg-color--e59c2b, #E59C2B);
}

.zpfzvmboh {
  d: path("M6.27 11.106q-.255.22-.5.455a1.68 1.68 0 0 0-.48 1.602c.461 1.964 1.584 4.649 3.62 6.143l1.038-.694c-2.588-1.72-3.697-4.97-3.678-7.506");
}

.zxxizob4i {
  stop-color: var(--svg-color--c52133, #C52133);
}

</style>
