<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3yRybc)" class="h_663fbdb"/><g filter="url(#iNrxRec)"><path fill="url(#iXLRPoM)" class="nncrckb7j"/><path fill="url(#ir4VsFc)" class="nncrckb7j"/></g><path fill="url(#itzBUue)" class="k-yfaib1f"/><g filter="url(#iPyrtib)"><path fill="url(#iKfkMAc)" class="rwt1q5dmi"/></g><path fill="url(#iYEOHJJ)" class="eg8evhbao"/><path fill="url(#irYowge)" class="eg8evhbao"/><path fill="url(#i3IxmcV)" class="eg8evhbao"/><path fill="url(#i0hzJZc)" class="eg8evhbao"/><path fill="url(#ilvXoGd)" class="eg8evhbao"/><path fill="url(#izOfPJe)" class="eg8evhbao"/><path fill="url(#izD4dme)" class="eg8evhbao"/><path fill="url(#iOqaXXb)" class="eg8evhbao"/><path fill="url(#icCQoSd)" class="yhfjs3b_u"/><path fill="url(#iUp0Wxb)" class="yhfjs3b_u"/><path fill="url(#iM3yElc)" class="egreut69z"/><path fill="url(#iXJYGHe)" class="egreut69z"/><path fill="url(#iVMCm6v)" class="egreut69z"/><path fill="url(#isG10Od)" class="stkbhibum"/><path fill="url(#idf2Bve)" class="stkbhibum"/><path fill="url(#iJpq4RY)" class="stkbhibum"/><g filter="url(#ioDdURb)"><path class="hzk4iiysy"/></g><g filter="url(#i3Oc7Jb)"><path class="y-w-t6xce"/></g><g filter="url(#ifdnf6b)"><path fill="url(#iJrmKzj)" class="a2jdagb7t"/><path fill="url(#iwRKhAd)" class="a2jdagb7t"/><path fill="url(#iCLw6Zc)" class="a2jdagb7t"/></g><g filter="url(#iZGHzPb)"><path fill="url(#i0X2fhd)" class="s33x_rlrk"/></g><g filter="url(#iGqPmrd)"><path fill="url(#iWckEde)" class="s4c2fljuq"/><path fill="url(#ihw7aRd)" class="s4c2fljuq"/><path fill="url(#iMb8sCb)" class="s4c2fljuq"/></g><path fill="url(#ixbcFPd)" class="s4c2fljuq"/><path fill="url(#iafROCc)" class="s4c2fljuq"/><path fill="url(#i9WXycb)" class="s4c2fljuq"/><path fill="url(#i1O0K1b)" class="s4c2fljuq"/><path fill="url(#ijFFF2e)" class="s4c2fljuq"/><g filter="url(#iLQmmme)"><path fill="url(#ia276Gb)" class="ikn67-bal"/></g><g filter="url(#i2JtZIc)"><path stroke="url(#ilc5jrP)" class="mkjj11mec"/></g><path class="scmrgijcl"/><path fill="url(#iDVwLNd)" class="w4rs107px"/><path fill="url(#iYBwG9b)" class="ccu7-vkqu"/><path clip-rule="evenodd" class="ug1qc4adm"/><path fill="url(#iEIkO4b)" clip-rule="evenodd" class="gtuifoboq"/><path clip-rule="evenodd" class="vaq8c7bwp"/><path fill="url(#iS9ZmDb)" clip-rule="evenodd" class="g-2j_fe5a"/><g filter="url(#iDrYXGe)"><path class="jbpamekbj"/></g><g filter="url(#iMsgfnd)"><path class="bjqixac9e"/><path fill="url(#iOjKpAe)" class="ms2l1ee1l"/><path fill="url(#iimTfNb)" class="ms2l1ee1l"/><path fill="url(#ivsvnBb)" class="ms2l1ee1l"/><path fill="url(#irbIdRc)" class="ms2l1ee1l"/><path fill="url(#iCSnZHM)" class="ms2l1ee1l"/></g><path class="z83jabc3z"/><path fill="url(#iBF3bmd)" class="tk3__qb9x"/><path class="o-vl_tbgb"/><g filter="url(#iJywfQd)"><path class="yeb1olbpu"/><path fill="url(#iUA2J8q)" class="xdg5h7l9v"/></g><g filter="url(#ieTOcKb)"><path fill="url(#iawMBsb)" class="tik5rtblr"/></g><path class="vb84lev-x"/><path fill="url(#i7Mx4Bd)" class="d73walu2l"/><path class="flz2c8iyl"/><g filter="url(#iQXRxAc)"><path fill="url(#iMJRHhX)" class="q4uqrvgrz"/></g><g filter="url(#iyEqDKe)"><ellipse transform="rotate(-27.914 13.509 9.978)" class="xgtnudb2w"/><ellipse fill="url(#iJ8zpLc)" transform="rotate(-27.914 13.509 9.978)" class="klq3puw7i"/></g><path fill="url(#ijNw9Ne)" class="fp4672bcn"/><path fill="url(#igfrMjV)" class="fp4672bcn"/><path fill="url(#ijv2Ajb)" class="fp4672bcn"/><path fill="url(#iEyhnsd)" class="jm1e8rb8n"/><path fill="url(#idPXx4c)" class="jm1e8rb8n"/><g filter="url(#ioDTDDd)"><path fill="url(#ibSkmxc)" class="xfhq7ccuj"/><path fill="url(#iyDZMpd)" class="xfhq7ccuj"/></g><g filter="url(#iEZ3akd)"><path fill="url(#iV0pdPe)" class="ilkzm1byh"/><path fill="url(#iVDLHfd)" class="ilkzm1byh"/></g><path fill="url(#iEiXAwd)" class="upb62yo6l"/><path fill="url(#iYdgarb)" class="upb62yo6l"/><path fill="url(#iPzLIVb)" class="upb62yo6l"/><path fill="url(#iBEJh9q)" class="upb62yo6l"/><g filter="url(#iqKh3od)"><path clip-rule="evenodd" class="h_yz-vbsr"/></g><g filter="url(#ibBF9ab)"><path stroke="url(#i76XRhc)" class="en6kh9i1y"/></g><g filter="url(#iS58Xvc)"><path stroke="url(#ikoviGe)" class="y5ykz5l3i"/></g><g filter="url(#iPDOJBc)"><path clip-rule="evenodd" class="yckq1hbsn"/></g><g filter="url(#i35Yyue)"><path stroke="url(#ija004O)" class="xy4gpnq9q"/></g><g filter="url(#iZaYJuw)"><path fill="url(#ipajzze)" class="tzu9mywbt"/></g><defs><radialGradient id="i3yRybc" cx="0" cy="0" r="1" gradientTransform="matrix(3.93792 -7.29125 14.315 7.73138 20.553 16.769)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="1" class="gdsiwyiyr"/></radialGradient><radialGradient id="iXLRPoM" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92122 7.06151 -2.22108 -.91882 27.573 12.245)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jpxim8b1x"/><stop offset="1" class="n52c8qgao"/></radialGradient><radialGradient id="ir4VsFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 4.15626 -.42744 -.1607 27.323 12.713)" gradientUnits="userSpaceOnUse"><stop class="fg6i_oqme"/><stop offset="1" class="ih2ibv29b"/></radialGradient><radialGradient id="itzBUue" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58397 -6.61442 12.98618 -8.99977 12.493 17.046)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="0" class="pxp9rxlhv"/><stop offset="1" class="e06hnni3m"/></radialGradient><radialGradient id="irYowge" cx="0" cy="0" r="1" gradientTransform="rotate(-118.874 16.525 8.487)scale(12.4902 33.343)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="f6lcb9bkn"/><stop offset="1" class="jtbt9y0gz"/></radialGradient><radialGradient id="i3IxmcV" cx="0" cy="0" r="1" gradientTransform="rotate(-65.133 29.239 1.614)scale(12.2618 28.8332)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="r21k1wzrc"/><stop offset="1" class="b2cn2_uce"/></radialGradient><radialGradient id="i0hzJZc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71875 0 0 -14.5625 23.292 23.338)" gradientUnits="userSpaceOnUse"><stop class="odfe47amh"/><stop offset="1" class="carxtabzu"/></radialGradient><radialGradient id="ilvXoGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6875 -.22656 0 19.206 16.744)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="z8m-hreok"/><stop offset="1" class="ehu1o5vid"/></radialGradient><radialGradient id="izOfPJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 3.5 -5.72433 -1.89104 12.667 16.37)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="a75cnrb-k"/><stop offset="1" class="ri_i1lblj"/></radialGradient><radialGradient id="icCQoSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6045 2.48458 0 23.855 29.963)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="vbb18ixfb"/><stop offset="1" class="p5bq_2b9f"/></radialGradient><radialGradient id="iUp0Wxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5781 .52466 0 23.11 29.963)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l0d7sccpf"/><stop offset="1" class="r3f5xvbmj"/></radialGradient><radialGradient id="iM3yElc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.2188 2.95614 0 7.292 29.963)" gradientUnits="userSpaceOnUse"><stop class="oj4dw6cda"/><stop offset="1" class="jsbpdr4yj"/></radialGradient><radialGradient id="iXJYGHe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21875 0 0 -14.5625 8.542 29.494)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ihp7x-bon"/><stop offset="1" class="g_z46f3jl"/></radialGradient><radialGradient id="iJrmKzj" cx="0" cy="0" r="1" gradientTransform="rotate(57.496 -7.297 21.845)scale(4.18715 6.17567)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="xksrntfob"/><stop offset="1" class="pu1_ubb-e"/></radialGradient><radialGradient id="iwRKhAd" cx="0" cy="0" r="1" gradientTransform="matrix(.375 3.375 -7.05108 .78345 14.73 14.37)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="jzwike70j"/><stop offset="1" class="gbck5ebgo"/></radialGradient><radialGradient id="iCLw6Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87568 -2.6343 0 15.948 16.4)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="uxwciubxp"/><stop offset="1" class="kqp3z9b3n"/></radialGradient><radialGradient id="iWckEde" cx="0" cy="0" r="1" gradientTransform="rotate(175.808 9.716 6.071)scale(7.5402 11.0759)" gradientUnits="userSpaceOnUse"><stop class="ip9ohr47j"/><stop offset="1" class="mv083ubql"/></radialGradient><radialGradient id="ihw7aRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36518 1.59886 0 18.24 9.044)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iMb8sCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.43518 1.69837 0 13.71 9.184)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="i9WXycb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.42509 10.3835 0 15.937 17.06)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="tdz6kqb3w"/><stop offset="1" class="xyj20w7ww"/></radialGradient><radialGradient id="i1O0K1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.95635 4.09478 0 15.937 17.06)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="b2ltqybtd"/><stop offset="1" class="xyj20w7ww"/><stop offset="1" class="xyj20w7ww"/><stop offset="1" class="srp7mbh4c"/></radialGradient><radialGradient id="ijFFF2e" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.9499 14.9438 0 15.937 15.447)" gradientUnits="userSpaceOnUse"><stop offset=".905" class="frudo5yld"/><stop offset="1" class="wdpffnb7r"/></radialGradient><radialGradient id="iimTfNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2259 -.76773 0 16.433 12.392)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="irbIdRc" cx="0" cy="0" r="1" gradientTransform="rotate(157.024 7.069 7.614)scale(1.6534 2.5206)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iBF3bmd" cx="0" cy="0" r="1" gradientTransform="rotate(-117.266 12.234 -.373)scale(.57126 .90459)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iUA2J8q" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.919 10.158)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="i7Mx4Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26172 -.50781 .80412 -.41444 13.803 10.33)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iJ8zpLc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.814 -1.495)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="igfrMjV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0193 1.125 -.25102 -.22744 23.316 7.807)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="oye8lqbkv"/><stop offset="1" class="n5t1ewtyv"/></radialGradient><radialGradient id="idPXx4c" cx="0" cy="0" r="1" gradientTransform="rotate(122.009 2.923 7.096)scale(.56277 2.95205)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="zar60tfds"/><stop offset="1" class="zcyi13bvi"/></radialGradient><radialGradient id="ibSkmxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.59772 -1.40625 .5978 .67918 20.98 10.338)" gradientUnits="userSpaceOnUse"><stop class="nvpfuqb-a"/><stop offset="1" class="skcf9z1zl"/></radialGradient><radialGradient id="iyDZMpd" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.0625 .1101 1.101 20.86 10.744)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="nnhn70ftf"/><stop offset="1" class="i8gko0bpu"/></radialGradient><radialGradient id="iV0pdPe" cx="0" cy="0" r="1" gradientTransform="rotate(-132.082 7.744 2.73)scale(2.41247 2.17677)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="k3bbh1b2g"/><stop offset="1" class="xu87aibcb"/></radialGradient><radialGradient id="iVDLHfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18123 .63382 -1.16713 -2.17513 11.01 9.795)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="azamzibei"/><stop offset="1" class="m8g2io15v"/></radialGradient><radialGradient id="iEiXAwd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.93271 6.4606 -9.67475 -7.38675 20.88 4.029)" gradientUnits="userSpaceOnUse"><stop class="ja62qnbvn"/><stop offset="1" class="doeokpgss"/></radialGradient><radialGradient id="iYdgarb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.114 9.345 .93)scale(6.55215 1.19385)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="mzjok2vtv"/><stop offset="1" class="moen_vfyr"/></radialGradient><radialGradient id="iPzLIVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -1.25 1.2273 1.2273 20.287 3.716)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="xn5dksb-u"/><stop offset="1" class="otpekjb_s"/></radialGradient><radialGradient id="iBEJh9q" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.15625 -2.7392 0 15.948 1.904)" gradientUnits="userSpaceOnUse"><stop class="yucjgfb4f"/><stop offset="1" class="neb43bcvz"/></radialGradient><radialGradient id="ipajzze" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 -1.20384 6.351 -.65945 17.483 4.812)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="ing6ksb7p"/><stop offset=".789" class="b-0vp4bih"/></radialGradient><linearGradient id="iKfkMAc" x1="5.54" x2="8.862" y1="12" y2="18.369" gradientUnits="userSpaceOnUse"><stop class="imlbmc2sy"/><stop offset="1" class="h7wwwp44w"/></linearGradient><linearGradient id="iYEOHJJ" x1="15.935" x2="15.935" y1="15.588" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="plsegxa8t"/><stop offset="1" class="dbg8b7bda"/></linearGradient><linearGradient id="izD4dme" x1="8.661" x2="8.938" y1="29.963" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="rq6u1obxj"/><stop offset="1" class="yomd27bxe"/></linearGradient><linearGradient id="iOqaXXb" x1="23.206" x2="22.776" y1="29.963" y2="29.963" gradientUnits="userSpaceOnUse"><stop offset=".136" class="i0lopbdha"/><stop offset="1" class="w11i7m31i"/></linearGradient><linearGradient id="iVMCm6v" x1="8.759" x2="7.511" y1="28.776" y2="28.776" gradientUnits="userSpaceOnUse"><stop class="k6ta6mb-r"/><stop offset="1" class="drixk4bdm"/></linearGradient><linearGradient id="isG10Od" x1="15.939" x2="15.939" y1="20.932" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="zajm34fcf"/><stop offset="1" class="puh_1hb6q"/></linearGradient><linearGradient id="idf2Bve" x1="15.939" x2="15.939" y1="29.963" y2="27.307" gradientUnits="userSpaceOnUse"><stop class="ou_12nqfl"/><stop offset="1" class="ypzxpcc2j"/></linearGradient><linearGradient id="iJpq4RY" x1="19.542" x2="17.698" y1="28.776" y2="28.776" gradientUnits="userSpaceOnUse"><stop offset=".119" class="zxxizob4i"/><stop offset="1" class="u7u0nyv_w"/></linearGradient><linearGradient id="i0X2fhd" x1="15.935" x2="15.935" y1="17.854" y2="25.882" gradientUnits="userSpaceOnUse"><stop class="gmn9ea1yo"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="ixbcFPd" x1="10.545" x2="12.415" y1="13.595" y2="13.531" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iafROCc" x1="20.743" x2="19.693" y1="12.72" y2="12.624" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="ia276Gb" x1="15.654" x2="23.806" y1="7.667" y2="4.748" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="ilc5jrP" x1="15.948" x2="15.948" y1="14.705" y2="14.284" gradientUnits="userSpaceOnUse"><stop class="vroryhbbk"/><stop offset="1" class="ri19dgbsk"/></linearGradient><linearGradient id="iDVwLNd" x1="17.479" x2="16.94" y1="13.893" y2="14.135" gradientUnits="userSpaceOnUse"><stop class="h4n1x2_nx"/><stop offset="1" class="kbidwf4gr"/></linearGradient><linearGradient id="iYBwG9b" x1="14.969" x2="14.516" y1="14.135" y2="14.062" gradientUnits="userSpaceOnUse"><stop class="ftqk6c0fk"/><stop offset="1" class="seh9j6z3x"/></linearGradient><linearGradient id="iEIkO4b" x1="16.351" x2="16.479" y1="19.112" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iS9ZmDb" x1="15.546" x2="15.417" y1="19.112" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iOjKpAe" x1="16.905" x2="15.87" y1="11.776" y2="11.829" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ivsvnBb" x1="15.966" x2="15.966" y1="12.811" y2="12.381" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iCSnZHM" x1="15.966" x2="15.966" y1="10.308" y2="10.814" gradientUnits="userSpaceOnUse"><stop class="i5etcbh5r"/><stop offset="1" class="kyqssj_6u"/></linearGradient><linearGradient id="iawMBsb" x1="18.886" x2="18.63" y1="10.136" y2="10.301" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iMJRHhX" x1="14.524" x2="14.21" y1="10.128" y2="10.322" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="ijNw9Ne" x1="21.541" x2="22.416" y1="8.432" y2="11.12" gradientUnits="userSpaceOnUse"><stop class="f5t1fub_l"/><stop offset="1" class="kcoeg77gv"/></linearGradient><linearGradient id="ijv2Ajb" x1="21.862" x2="22.131" y1="8.174" y2="8.596" gradientUnits="userSpaceOnUse"><stop class="bgirfjbcd"/><stop offset="1" class="f3w7r3b-t"/></linearGradient><linearGradient id="iEyhnsd" x1="8.981" x2="11.397" y1="10.514" y2="9.507" gradientUnits="userSpaceOnUse"><stop class="hldlhts-f"/><stop offset="1" class="g2u36d4kg"/></linearGradient><linearGradient id="i76XRhc" x1="12.913" x2="14.318" y1="8.298" y2="8.031" gradientUnits="userSpaceOnUse"><stop class="s0qsib-ln"/><stop offset="1" class="i5bggbceb"/></linearGradient><linearGradient id="ikoviGe" x1="13.738" x2="13.252" y1="7.957" y2="7.091" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ija004O" x1="18.225" x2="18.769" y1="7.918" y2="6.947" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><filter id="iNrxRec" width="4.702" height="8.2" x="22.301" y="11.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1222"/></filter><filter id="iPyrtib" width="4.902" height="8.4" x="5.146" y="11.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.321569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1222"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1222" result="effect2_innerShadow_4002_1222"/></filter><filter id="ioDdURb" width="6.968" height="4.815" x="12.464" y="15.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".25"/></filter><filter id="i3Oc7Jb" width="6.431" height="9.028" x="12.527" y="17.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".25"/></filter><filter id="ifdnf6b" width="6.43" height="4.46" x="12.733" y="15.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.835294 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1222"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.733333 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1222" result="effect2_innerShadow_4002_1222"/></filter><filter id="iZGHzPb" width="5.531" height="8.006" x="13.22" y="18.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.705882 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1222"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.670588 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1222" result="effect2_innerShadow_4002_1222"/></filter><filter id="iGqPmrd" width="10.31" height="12.713" x="10.782" y="4.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1222"/></filter><filter id="iLQmmme" width="8.25" height="7.07" x="14.356" y="2.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation="1"/></filter><filter id="i2JtZIc" width="3.566" height="1.546" x="14.165" y="13.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".05"/></filter><filter id="iDrYXGe" width="3.262" height="4.184" x="14.096" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".375"/></filter><filter id="iMsgfnd" width="2.279" height="3.084" x="14.827" y="9.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".1"/></filter><filter id="iJywfQd" width=".787" height=".697" x="17.413" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".05"/></filter><filter id="ieTOcKb" width=".892" height=".914" x="18.253" y="9.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".1"/></filter><filter id="iQXRxAc" width=".987" height="1.041" x="13.807" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".1"/></filter><filter id="iyEqDKe" width=".914" height=".705" x="13.052" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".05"/></filter><filter id="ioDTDDd" width="1.798" height="3.38" x="20.881" y="8.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".05"/></filter><filter id="iEZ3akd" width="2.017" height="3.595" x="9.092" y="8.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".1"/></filter><filter id="iqKh3od" width="2.927" height="1.811" x="12.038" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1222"/></filter><filter id="ibBF9ab" width="2.477" height="1.211" x="12.138" y="7.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".125"/></filter><filter id="iS58Xvc" width="2.577" height="1.311" x="12.088" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".15"/></filter><filter id="iPDOJBc" width="2.927" height="1.811" x="17.264" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1222"/></filter><filter id="i35Yyue" width="2.785" height="1.367" x="17.237" y="7.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".15"/></filter><filter id="iZaYJuw" width="5.117" height="2.558" x="15.74" y="3.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1222" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-vampire-medium-dark" /></template>
<style>
.a2jdagb7t {
  d: path("M12.733 19.702v-3.754h6.43v3.649c0 .403-.233.603-.777.347c-.738-.347-2.453-1.617-2.453-1.617S14 19.714 13.53 19.924s-.797.181-.797-.223");
}

.a75cnrb-k {
  stop-color: var(--svg-color--47374c, #47374C);
}

.azamzibei {
  stop-color: var(--svg-color--6d4d4c, #6D4D4C);
  stop-opacity: 0;
}

.b-0vp4bih {
  stop-color: var(--svg-color--454445, #454445);
  stop-opacity: 0;
}

.b2cn2_uce {
  stop-color: var(--svg-color--60506b, #60506B);
}

.b2ltqybtd {
  stop-color: var(--svg-color--895481, #895481);
}

.bgirfjbcd {
  stop-color: var(--svg-color--6c4639, #6C4639);
}

.bjqixac9e {
  fill: var(--svg-color--80594f, #80594F);
  d: path("m15.584 10.471l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.765 0");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.carxtabzu {
  stop-color: var(--svg-color--604f70, #604F70);
  stop-opacity: 0;
}

.ccu7-vkqu {
  d: path("m14.735 14.62l.396-.895a3 3 0 0 1-.623-.264c-.102-.057-.249.044-.219.157l.258.986a.1.1 0 0 0 .188.015");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d73walu2l {
  d: path("M13.778 9.597a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.dbg8b7bda {
  stop-color: var(--svg-color--553d71, #553D71);
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.doeokpgss {
  stop-color: var(--svg-color--191818, #191818);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.e06hnni3m {
  stop-color: var(--svg-color--e73665, #E73665);
}

.eg8evhbao {
  d: path("M15.935 15.588c-6.04 0-10.937 5.1-10.937 11.14v3.235h21.875V26.73c0-6.04-4.897-11.14-10.938-11.14");
}

.egreut69z {
  d: path("M8.76 18.359v11.604H4.997V26.73c0-3.295 1.456-6.31 3.761-8.37");
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

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.f1lm8sbjk {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
}

.f3w7r3b-t {
  stop-color: var(--svg-color--6c4639, #6C4639);
  stop-opacity: 0;
}

.f5t1fub_l {
  stop-color: var(--svg-color--7f5d51, #7F5D51);
}

.f6lcb9bkn {
  stop-color: var(--svg-color--56475f, #56475F);
  stop-opacity: 0;
}

.fg6i_oqme {
  stop-color: var(--svg-color--574b64, #574B64);
}

.flz2c8iyl {
  fill: var(--svg-color--000, #000);
  d: path("M14.29 10.49a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.fp4672bcn {
  d: path("M20.945 12.31c.037-1.41.045-2.426.076-3.638c.49-.321 1.231-.682 1.833-.97c.214-.103.456.02.461.257c.014.641-.118 1.503-.656 2.528c-.62 1.215-1.21 1.655-1.714 1.822");
}

.frudo5yld {
  stop-color: var(--svg-color--60382e, #60382E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftqk6c0fk {
  stop-color: var(--svg-color--d1c8d8, #D1C8D8);
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g_z46f3jl {
  stop-color: var(--svg-color--655578, #655578);
}

.g-2j_fe5a {
  fill-rule: evenodd;
  d: path("M15.438 19.113a.125.125 0 0 0-.14.107l-.65 4.671a.125.125 0 0 0 .248.035l.649-4.672a.125.125 0 0 0-.107-.141");
}

.g2u36d4kg {
  stop-color: var(--svg-color--664642, #664642);
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

.gtuifoboq {
  fill-rule: evenodd;
  d: path("M16.458 19.113a.125.125 0 0 1 .141.107l.649 4.671a.125.125 0 0 1-.248.035l-.648-4.672a.125.125 0 0 1 .106-.141");
}

.h_663fbdb {
  d: path("M26.478 11.561c-2.243-2.143-5.051-3.376-6.334-3.817l-4.062 12.313h5.89c2.916-1.118 4.43-4.528 4.986-6.894a1.68 1.68 0 0 0-.48-1.602");
}

.h_yz-vbsr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M14.195 8.389a2.15 2.15 0 0 0-1.417.37a.475.475 0 0 1-.53-.788a3.1 3.1 0 0 1 2.037-.528a.475.475 0 1 1-.09.946");
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

.hl4dixbko {
  stop-color: var(--svg-color--ff6d74, #FF6D74);
}

.hldlhts-f {
  stop-color: var(--svg-color--6b4648, #6B4648);
}

.hzk4iiysy {
  fill: var(--svg-color--bb172a, #BB172A);
  d: path("M12.964 19.845v-3.484h5.968v3.387c0 .374-.216.56-.721.322c-.686-.322-2.277-1.501-2.277-1.501s-1.793 1.288-2.23 1.483s-.74.168-.74-.207");
}

.i0lopbdha {
  stop-color: var(--svg-color--4a2f65, #4A2F65);
}

.i5bggbceb {
  stop-color: var(--svg-color--4f494b, #4F494B);
}

.i5etcbh5r {
  stop-color: var(--svg-color--845b55, #845B55);
}

.i8gko0bpu {
  stop-color: var(--svg-color--907068, #907068);
  stop-opacity: 0;
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

.ilkzm1byh {
  d: path("m10.778 9.338l.13 2.374c-1.075-.865-1.497-2.122-1.614-2.947c-.028-.2.19-.318.356-.204z");
}

.imlbmc2sy {
  stop-color: var(--svg-color--554961, #554961);
}

.ing6ksb7p {
  stop-color: var(--svg-color--454445, #454445);
}

.ip9ohr47j {
  stop-color: var(--svg-color--9a6d5f, #9A6D5F);
}

.ja62qnbvn {
  stop-color: var(--svg-color--252525, #252525);
}

.jbpamekbj {
  fill: var(--svg-color--724047, #724047);
  d: path("m15.69 10.635l-.82 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.377-.283-.377-.395 0");
}

.jm1e8rb8n {
  d: path("M10.846 8.669c.034 1.21.074 2.413.11 3.638c-.508-.163-1.117-.606-1.745-1.836c-.538-1.024-.67-1.886-.656-2.527c.005-.237.247-.36.46-.258c.61.292 1.338.659 1.83.983");
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

.k-yfaib1f {
  d: path("M5.77 11.561c2.243-2.143 5.052-3.376 6.334-3.817l4.063 12.313h-5.891c-2.916-1.118-4.43-4.528-4.986-6.894a1.68 1.68 0 0 1 .48-1.602");
}

.k3bbh1b2g {
  stop-color: var(--svg-color--5c3838, #5C3838);
}

.k6ta6mb-r {
  stop-color: var(--svg-color--423153, #423153);
}

.kbidwf4gr {
  stop-color: var(--svg-color--d3cadb, #D3CADB);
}

.kcoeg77gv {
  stop-color: var(--svg-color--825b59, #825B59);
}

.klq3puw7i {
  cx: 13.509px;
  cy: 9.978px;
  rx: 0.39px;
  ry: 0.197px;
}

.kqp3z9b3n {
  stop-color: var(--svg-color--9c8ea7, #9C8EA7);
  stop-opacity: 0;
}

.kyqssj_6u {
  stop-color: var(--svg-color--845b55, #845B55);
  stop-opacity: 0;
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l0d7sccpf {
  stop-color: var(--svg-color--48335e, #48335E);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lft-zacfy {
  stop-color: var(--svg-color--ff242f, #FF242F);
}

.m8g2io15v {
  stop-color: var(--svg-color--6d4d4c, #6D4D4C);
}

.mkjj11mec {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.513 13.464a2.94 2.94 0 0 0 2.87 0c.077-.043.169.022.143.106c-.26.85-.993 1.026-1.578 1.026s-1.318-.176-1.578-1.026c-.026-.084.066-.149.143-.107Z");
}

.moen_vfyr {
  stop-color: var(--svg-color--47423f, #47423F);
  stop-opacity: 0;
}

.ms2l1ee1l {
  d: path("m15.584 10.471l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.765 0");
}

.mv083ubql {
  stop-color: var(--svg-color--744a4e, #744A4E);
}

.mzjok2vtv {
  stop-color: var(--svg-color--47423f, #47423F);
}

.n52c8qgao {
  stop-color: var(--svg-color--3d3743, #3D3743);
}

.n5t1ewtyv {
  stop-color: var(--svg-color--957971, #957971);
  stop-opacity: 0;
}

.neb43bcvz {
  stop-color: var(--svg-color--4d4d4d, #4D4D4D);
  stop-opacity: 0;
}

.nncrckb7j {
  d: path("M25.979 11.106q.253.22.5.455c.431.413.616 1.02.48 1.601c-.462 1.965-1.584 4.65-3.62 6.144l-1.038-.694c2.587-1.72 3.696-4.97 3.678-7.506");
}

.nnhn70ftf {
  stop-color: var(--svg-color--907068, #907068);
}

.nvpfuqb-a {
  stop-color: var(--svg-color--805a56, #805A56);
}

.o-vl_tbgb {
  fill: var(--svg-color--000, #000);
  d: path("M17.638 10.49a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.odfe47amh {
  stop-color: var(--svg-color--746784, #746784);
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

.oye8lqbkv {
  stop-color: var(--svg-color--957971, #957971);
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

.pu1_ubb-e {
  stop-color: var(--svg-color--eae1f3, #EAE1F3);
}

.puh_1hb6q {
  stop-color: var(--svg-color--ff3779, #FF3779);
}

.pxp9rxlhv {
  stop-color: var(--svg-color--e33e4b, #E33E4B);
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q4uqrvgrz {
  d: path("M14.594 10.385c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.qhxuaybfw {
  stop-color: var(--svg-color--dfcfe8, #DFCFE8);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.r21k1wzrc {
  stop-color: var(--svg-color--60506b, #60506B);
  stop-opacity: 0;
}

.r3f5xvbmj {
  stop-color: var(--svg-color--48335e, #48335E);
  stop-opacity: 0;
}

.ri_i1lblj {
  stop-color: var(--svg-color--47374c, #47374C);
  stop-opacity: 0;
}

.ri19dgbsk {
  stop-color: var(--svg-color--7f585b, #7F585B);
  stop-opacity: 0;
}

.rq6u1obxj {
  stop-color: var(--svg-color--453455, #453455);
}

.rwt1q5dmi {
  d: path("M6.27 11.106q-.255.22-.5.455a1.68 1.68 0 0 0-.48 1.601c.461 1.965 1.584 4.65 3.62 6.144l1.038-.694c-2.588-1.72-3.696-4.97-3.678-7.506");
}

.s0qsib-ln {
  stop-color: var(--svg-color--4f494b, #4F494B);
  stop-opacity: 0;
}

.s33x_rlrk {
  d: path("m14.084 19.6l-.859 5.24a.402.402 0 0 0 .603.409l.2-.118a.51.51 0 0 1 .554.027l.706.514a1.1 1.1 0 0 0 1.295 0l.705-.514a.51.51 0 0 1 .554-.027l.201.117a.402.402 0 0 0 .602-.408l-.857-5.235c-.81-.504-1.855-1.279-1.855-1.279s-1.107.796-1.85 1.273");
}

.s4c2fljuq {
  d: path("M10.783 7.58a3 3 0 0 1 2.999-3.082h4.31a3 3 0 0 1 3 3.06l-.198 6.36c-.035 1.769-1.408 3.142-3.178 3.142h-3.51c-1.761 0-3.07-1.351-3.195-3.118z");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.scmrgijcl {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M14.513 13.464a2.94 2.94 0 0 0 2.87 0c.077-.043.169.022.143.106c-.26.85-.993 1.026-1.578 1.026s-1.318-.176-1.578-1.026c-.026-.084.066-.149.143-.107");
}

.seh9j6z3x {
  stop-color: var(--svg-color--c7becf, #C7BECF);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.skcf9z1zl {
  stop-color: var(--svg-color--7d5457, #7D5457);
}

.srp7mbh4c {
  stop-color: var(--svg-color--895481, #895481);
  stop-opacity: 0;
}

.stkbhibum {
  d: path("M12.733 29.963V16.071a10.7 10.7 0 0 1 3.184-.483a10.7 10.7 0 0 1 3.228.497v13.878z");
}

.tdz6kqb3w {
  stop-color: var(--svg-color--80476b, #80476B);
}

.tik5rtblr {
  d: path("M18.945 10.372a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.tk3__qb9x {
  d: path("M18.15 9.597a.893.893 0 0 1 .86 1.128h-1.726a.897.897 0 0 1 .865-1.129");
}

.tzu9mywbt {
  d: path("M16.45 4.226c-.249.315-.42.986-.46 1.53c.352-1.034.773-1.247 1.258-1.347c1.139-.152 2.78.504 3.359 1.038l-.374-1.038c-2.664-1.182-3.425-.635-3.783-.183");
}

.u7u0nyv_w {
  stop-color: var(--svg-color--dd2864, #DD2864);
  stop-opacity: 0;
}

.ug1qc4adm {
  fill: var(--svg-color--decee7, #DECEE7);
  fill-rule: evenodd;
  d: path("M16.458 19.113a.125.125 0 0 1 .141.107l.649 4.671a.125.125 0 0 1-.248.035l-.648-4.672a.125.125 0 0 1 .106-.141");
}

.upb62yo6l {
  d: path("m10.37 10.082l-.617-2.736c-.116-.426-.242-1.394.024-2.013c.264-.612.68-.836 1.05-1.035c.125-.066.244-.13.35-.204q.124-.089.235-.161c.298-.201.536-.361.875-.762c.422-.5 1.056-1.005 1.76-1.114c.406-.064.784.036 1.146.132c.259.069.509.135.755.137c.246-.002.497-.068.755-.137c.362-.096.74-.196 1.147-.132c.703.11 1.337.613 1.76 1.114c.338.401.576.561.875.762l.235.16c.106.075.225.139.348.205c.37.199.787.423 1.051 1.035c.267.62.14 1.587.024 2.013l-.616 2.736c-.054.238-.298.398-.542.398l.032-1.71c0-1.346-.334-2.387-1.032-3.034c-.982-.911-1.858-.911-2.483-.911c-.675 0-.847.379-1.041.745l-.09.166c-.154.267-.336.337-.423.33c-.086.007-.267-.063-.42-.33q-.048-.082-.091-.166c-.194-.366-.368-.745-1.042-.745c-.626 0-1.502 0-2.483.91c-.698.648-1.033 1.69-1.033 3.034l.021 1.72a.546.546 0 0 1-.53-.407");
}

.uw1qucxdm {
  stop-color: var(--svg-color--d2bdd8, #D2BDD8);
}

.uxwciubxp {
  stop-color: var(--svg-color--776484, #776484);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vaq8c7bwp {
  fill: var(--svg-color--decee8, #DECEE8);
  fill-rule: evenodd;
  d: path("M15.438 19.113a.125.125 0 0 0-.14.107l-.65 4.671a.125.125 0 0 0 .248.035l.649-4.672a.125.125 0 0 0-.107-.141");
}

.vb84lev-x {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.571 9.325c-.653 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.vbb18ixfb {
  stop-color: var(--svg-color--6b5a80, #6B5A80);
}

.vo8nxhb-a {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
  stop-opacity: 0;
}

.vroryhbbk {
  stop-color: var(--svg-color--7f5859, #7F5859);
}

.w11i7m31i {
  stop-color: var(--svg-color--665579, #665579);
  stop-opacity: 0;
}

.w4rs107px {
  d: path("m17.154 14.62l-.396-.895a3.2 3.2 0 0 0 .623-.264c.102-.057.248.044.219.157l-.258.986a.1.1 0 0 1-.188.015");
}

.wdpffnb7r {
  stop-color: var(--svg-color--60382e, #60382E);
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.xdg5h7l9v {
  d: path("M18.084 9.786c.063.085-.07.188-.22.302c-.152.113-.264.192-.328.107s.008-.246.159-.359c.15-.113.325-.136.389-.05");
}

.xfhq7ccuj {
  d: path("M20.98 11.696c.022-.376.044-.79.068-1.224l.063-1.147l1.11-.764c.166-.114.383.004.355.204c-.117.82-.534 2.067-1.596 2.931");
}

.xgtnudb2w {
  cx: 13.509px;
  cy: 9.978px;
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.39px;
  ry: 0.197px;
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

.xu87aibcb {
  stop-color: var(--svg-color--623d4c, #623D4C);
}

.xy4gpnq9q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.598 8.279a2.95 2.95 0 0 0-1.936-.504");
}

.xyj20w7ww {
  stop-color: var(--svg-color--754850, #754850);
  stop-opacity: 0;
}

.y-w-t6xce {
  fill: var(--svg-color--c91a3b, #C91A3B);
  d: path("m14.177 17.916l-1.144 6.986a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.027l.705.514a1.1 1.1 0 0 0 1.295 0l.706-.514a.51.51 0 0 1 .553-.027l.202.118a.402.402 0 0 0 .602-.409l-1.145-6.986z");
}

.y5ykz5l3i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.513 8.279a2.63 2.63 0 0 1 1.727-.45");
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yckq1hbsn {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M17.784 8.389a2.15 2.15 0 0 1 1.417.37a.475.475 0 0 0 .53-.788a3.1 3.1 0 0 0-2.037-.528a.475.475 0 1 0 .09.946");
}

.yeb1olbpu {
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M18.084 9.786c.063.085-.07.188-.22.302c-.152.113-.264.192-.328.107s.008-.246.159-.359c.15-.113.325-.136.389-.05");
}

.yhfjs3b_u {
  d: path("M23.11 18.359v11.604h3.763V26.73c0-3.295-1.457-6.31-3.762-8.37");
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

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z83jabc3z {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.357 9.325c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.z8m-hreok {
  stop-color: var(--svg-color--47304f, #47304F);
}

.zajm34fcf {
  stop-color: var(--svg-color--e32d3d, #E32D3D);
}

.zar60tfds {
  stop-color: var(--svg-color--53302b, #53302B);
}

.zcyi13bvi {
  stop-color: var(--svg-color--53302b, #53302B);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zxxizob4i {
  stop-color: var(--svg-color--c52133, #C52133);
}

</style>
