<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3yRybc)" class="lt9tcnl8a"/><g filter="url(#iJnpAXd)"><path fill="url(#iXLRPoM)" class="ca_cpzbpw"/><path fill="url(#ir4VsFc)" class="ca_cpzbpw"/></g><path fill="url(#itzBUue)" class="k-yfaib1f"/><g filter="url(#ir9yXEc)"><path fill="url(#iKfkMAc)" class="zq1muvb_r"/></g><path fill="url(#iYEOHJJ)" class="pwbqwxbuo"/><path fill="url(#irYowge)" class="pwbqwxbuo"/><path fill="url(#i3IxmcV)" class="pwbqwxbuo"/><path fill="url(#i0hzJZc)" class="pwbqwxbuo"/><path fill="url(#ilvXoGd)" class="pwbqwxbuo"/><path fill="url(#izOfPJe)" class="pwbqwxbuo"/><path fill="url(#izD4dme)" class="pwbqwxbuo"/><path fill="url(#iOqaXXb)" class="pwbqwxbuo"/><path fill="url(#icCQoSd)" class="jcv675w6u"/><path fill="url(#iUp0Wxb)" class="jcv675w6u"/><path fill="url(#iM3yElc)" class="qyo-sfboi"/><path fill="url(#iXJYGHe)" class="qyo-sfboi"/><path fill="url(#ipKjL7b)" class="qyo-sfboi"/><path fill="url(#isG10Od)" class="w7p3xxgxw"/><path fill="url(#idf2Bve)" class="w7p3xxgxw"/><path fill="url(#iJpq4RY)" class="w7p3xxgxw"/><g filter="url(#iAOzrAc)"><path class="oegqju6nx"/></g><g filter="url(#iJfENOb)"><path class="zo0v05b9a"/></g><g filter="url(#ia9S4tc)"><path fill="url(#iJrmKzj)" class="fom0o-b5s"/><path fill="url(#iwRKhAd)" class="fom0o-b5s"/><path fill="url(#iCLw6Zc)" class="fom0o-b5s"/></g><g filter="url(#iCEjAec)"><path fill="url(#i0X2fhd)" class="fpuz4ebbn"/></g><g filter="url(#iF2hdnd)"><path fill="url(#i4ErBSc)" class="x4ket23ym"/><path fill="url(#iLaDhnb)" class="x4ket23ym"/><path fill="url(#i2cUAve)" class="x4ket23ym"/><path fill="url(#i49plXc)" class="x4ket23ym"/><path fill="url(#iayRL4M)" class="x4ket23ym"/><path fill="url(#iu9Fuqc)" class="x4ket23ym"/><path fill="url(#iZKeQNd)" class="x4ket23ym"/></g><path fill="url(#iNEzAEc)" class="x4ket23ym"/><path fill="url(#iY7r8Uc)" class="x4ket23ym"/><g filter="url(#ita00qc)"><path fill="url(#ihx55fd)" class="ikn67-bal"/></g><g filter="url(#iVXxsDd)"><path stroke="url(#iOCEe2F)" class="bv2dogb4d"/></g><path class="fai_osbjm"/><path fill="url(#iW3m3ZG)" class="hbnqzrcju"/><path class="trxhxpadd"/><path clip-rule="evenodd" class="zanwp13zc"/><path fill="url(#iEIkO4b)" clip-rule="evenodd" class="knk60smxr"/><path clip-rule="evenodd" class="k3ni8ebrh"/><path fill="url(#iS9ZmDb)" clip-rule="evenodd" class="h_ltlobtq"/><g filter="url(#idgKgxe)"><path class="cqxd2rkco"/></g><g filter="url(#iWnvske)"><path class="ldrp94bxq"/><path fill="url(#i4Aug4d)" class="sv6-s7bnh"/><path fill="url(#iEdxC9b)" class="sv6-s7bnh"/><path fill="url(#i9B8mTb)" class="sv6-s7bnh"/><path fill="url(#iaGaueH)" class="sv6-s7bnh"/></g><path class="j7d6tdb2g"/><path fill="url(#iBF3bmd)" class="c8p9zqb6v"/><path class="o-vl_tbgb"/><g filter="url(#isd7rjR)"><path class="bp-vzngbu"/><path fill="url(#iUA2J8q)" class="e7kaubcpd"/></g><g filter="url(#ipljz0d)"><path fill="url(#iawMBsb)" class="tik5rtblr"/></g><path class="qriicvbhe"/><path fill="url(#i7Mx4Bd)" class="d73walu2l"/><path class="flz2c8iyl"/><g filter="url(#iUU4o4c)"><path fill="url(#iMJRHhX)" class="q4uqrvgrz"/></g><g filter="url(#ikwF2Lc)"><ellipse transform="rotate(-27.914 13.509 9.978)" class="xgtnudb2w"/><ellipse fill="url(#iJ8zpLc)" transform="rotate(-27.914 13.509 9.978)" class="klq3puw7i"/></g><path fill="url(#iQ6n1we)" class="fp4672bcn"/><path fill="url(#iaMHOld)" class="fp4672bcn"/><path fill="url(#iLJ98Pb)" class="fp4672bcn"/><path fill="url(#iXzF3Oe)" class="aw-9yhbqw"/><path fill="url(#iMG7C2d)" class="aw-9yhbqw"/><g filter="url(#iXAkvId)"><path fill="url(#iv8Uzzd)" class="u_per4bve"/><path fill="url(#iKXedXb)" class="u_per4bve"/></g><g filter="url(#i5PlyKe)"><path fill="url(#i8crpZd)" class="lmxk8n8zo"/><path fill="url(#iCO3Omp)" class="lmxk8n8zo"/></g><path fill="url(#iEiXAwd)" class="p2-8u3v4t"/><path fill="url(#iYdgarb)" class="p2-8u3v4t"/><path fill="url(#iPzLIVb)" class="p2-8u3v4t"/><path fill="url(#iBEJh9q)" class="p2-8u3v4t"/><g filter="url(#izECx0f)"><path clip-rule="evenodd" class="xon9p4yuw"/></g><g filter="url(#ivJCmzc)"><path stroke="url(#iZvZE6c)" class="en6kh9i1y"/></g><g filter="url(#izoRn6d)"><path stroke="url(#ikoviGe)" class="y5ykz5l3i"/></g><g filter="url(#iveQbwc)"><path clip-rule="evenodd" class="blu0296ak"/></g><g filter="url(#ipcHT2d)"><path stroke="url(#ija004O)" class="xy4gpnq9q"/></g><g filter="url(#i3lNU2d)"><path fill="url(#iwaDu4c)" class="zpyvujcqa"/></g><defs><radialGradient id="i3yRybc" cx="0" cy="0" r="1" gradientTransform="matrix(3.93792 -7.29125 14.315 7.73138 20.553 16.769)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="1" class="gdsiwyiyr"/></radialGradient><radialGradient id="iXLRPoM" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92122 7.06151 -2.22108 -.91882 27.573 12.245)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jpxim8b1x"/><stop offset="1" class="n52c8qgao"/></radialGradient><radialGradient id="ir4VsFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 4.15626 -.42744 -.1607 27.323 12.713)" gradientUnits="userSpaceOnUse"><stop class="fg6i_oqme"/><stop offset="1" class="ih2ibv29b"/></radialGradient><radialGradient id="itzBUue" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58397 -6.61442 12.98618 -8.99977 12.493 17.046)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="0" class="pxp9rxlhv"/><stop offset="1" class="e06hnni3m"/></radialGradient><radialGradient id="irYowge" cx="0" cy="0" r="1" gradientTransform="rotate(-118.874 16.525 8.487)scale(12.4902 33.343)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="f6lcb9bkn"/><stop offset="1" class="jtbt9y0gz"/></radialGradient><radialGradient id="i3IxmcV" cx="0" cy="0" r="1" gradientTransform="rotate(-65.133 29.239 1.614)scale(12.2618 28.8332)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="r21k1wzrc"/><stop offset="1" class="b2cn2_uce"/></radialGradient><radialGradient id="i0hzJZc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71875 0 0 -14.5625 23.292 23.338)" gradientUnits="userSpaceOnUse"><stop class="odfe47amh"/><stop offset="1" class="carxtabzu"/></radialGradient><radialGradient id="ilvXoGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6875 -.22656 0 19.206 16.744)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="z8m-hreok"/><stop offset="1" class="ehu1o5vid"/></radialGradient><radialGradient id="izOfPJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 3.5 -5.72433 -1.89104 12.667 16.37)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="a75cnrb-k"/><stop offset="1" class="ri_i1lblj"/></radialGradient><radialGradient id="icCQoSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6045 2.48458 0 23.855 29.963)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="vbb18ixfb"/><stop offset="1" class="p5bq_2b9f"/></radialGradient><radialGradient id="iUp0Wxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5781 .52466 0 23.11 29.963)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l0d7sccpf"/><stop offset="1" class="r3f5xvbmj"/></radialGradient><radialGradient id="iM3yElc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.2188 2.95614 0 7.292 29.963)" gradientUnits="userSpaceOnUse"><stop class="oj4dw6cda"/><stop offset="1" class="jsbpdr4yj"/></radialGradient><radialGradient id="iXJYGHe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21875 0 0 -14.5625 8.542 29.494)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ihp7x-bon"/><stop offset="1" class="g_z46f3jl"/></radialGradient><radialGradient id="iJrmKzj" cx="0" cy="0" r="1" gradientTransform="rotate(57.496 -7.297 21.845)scale(4.18715 6.17567)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="xksrntfob"/><stop offset="1" class="pu1_ubb-e"/></radialGradient><radialGradient id="iwRKhAd" cx="0" cy="0" r="1" gradientTransform="matrix(.375 3.375 -7.05108 .78345 14.73 14.37)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="jzwike70j"/><stop offset="1" class="gbck5ebgo"/></radialGradient><radialGradient id="iCLw6Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87568 -2.6343 0 15.948 16.4)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="uxwciubxp"/><stop offset="1" class="kqp3z9b3n"/></radialGradient><radialGradient id="i2cUAve" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.42095 -9.58583 0 15.615 10.16)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="i49plXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36518 1.59886 0 18.24 9.044)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iayRL4M" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45269 1.71908 0 13.71 9.01)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iZKeQNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.2624 12.1938 0 15.937 15.76)" gradientUnits="userSpaceOnUse"><stop offset=".918" class="b6_v0lbsx"/><stop offset=".979" class="p67pqmk9y"/></radialGradient><radialGradient id="iNEzAEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.97197 3.89694 0 15.937 17.06)" gradientUnits="userSpaceOnUse"><stop class="z556dzc9p"/><stop offset="1" class="u298-db2x"/></radialGradient><radialGradient id="iY7r8Uc" cx="0" cy="0" r="1" gradientTransform="matrix(7.03125 2.875 -5.05738 12.36859 13.443 12.979)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="zr5cz1b9r"/><stop offset=".967" class="khy8pi8et"/></radialGradient><radialGradient id="iaGaueH" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.294 12.365)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iBF3bmd" cx="0" cy="0" r="1" gradientTransform="rotate(-117.266 12.234 -.373)scale(.57126 .90459)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iUA2J8q" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.919 10.158)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="i7Mx4Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26172 -.50781 .80412 -.41444 13.803 10.33)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="iJ8zpLc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.814 -1.495)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="iaMHOld" cx="0" cy="0" r="1" gradientTransform="rotate(132.451 10.077 9.016)scale(2.50015 .55787)" gradientUnits="userSpaceOnUse"><stop class="ko44f1ecp"/><stop offset="1" class="i1u0xeg2c"/></radialGradient><radialGradient id="iMG7C2d" cx="0" cy="0" r="1" gradientTransform="rotate(122.009 2.922 7.096)scale(.56277 2.95205)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="vx8dsgrfz"/><stop offset="1" class="sfkkzgbur"/></radialGradient><radialGradient id="iv8Uzzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.59772 -1.40625 .5978 .67918 20.98 10.338)" gradientUnits="userSpaceOnUse"><stop class="tt0m3dw5o"/><stop offset="1" class="iwate57pq"/></radialGradient><radialGradient id="iKXedXb" cx="0" cy="0" r="1" gradientTransform="matrix(.771 .03125 -.09929 2.44952 20.839 10.338)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="lymk7up5q"/><stop offset="1" class="udqi13bwa"/></radialGradient><radialGradient id="i8crpZd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.082 7.744 2.73)scale(2.41247 2.17677)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="rlrkc3tlk"/><stop offset="1" class="hy1_v56-b"/></radialGradient><radialGradient id="iCO3Omp" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18123 .63382 -1.16713 -2.17513 11.01 9.795)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="nnv6oabuq"/><stop offset="1" class="ih2vhqbgt"/></radialGradient><radialGradient id="iEiXAwd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.93271 6.4606 -9.67475 -7.38675 20.88 4.029)" gradientUnits="userSpaceOnUse"><stop class="ja62qnbvn"/><stop offset="1" class="doeokpgss"/></radialGradient><radialGradient id="iYdgarb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.114 9.345 .93)scale(6.55215 1.19385)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="mzjok2vtv"/><stop offset="1" class="moen_vfyr"/></radialGradient><radialGradient id="iPzLIVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -1.25 1.2273 1.2273 20.287 3.716)" gradientUnits="userSpaceOnUse"><stop offset=".308" class="xn5dksb-u"/><stop offset="1" class="otpekjb_s"/></radialGradient><radialGradient id="iBEJh9q" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.15625 -2.7392 0 15.948 1.904)" gradientUnits="userSpaceOnUse"><stop class="yucjgfb4f"/><stop offset="1" class="neb43bcvz"/></radialGradient><radialGradient id="iwaDu4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 -1.20384 6.351 -.65945 17.482 4.812)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="ing6ksb7p"/><stop offset=".789" class="b-0vp4bih"/></radialGradient><linearGradient id="iKfkMAc" x1="5.54" x2="8.862" y1="12" y2="18.369" gradientUnits="userSpaceOnUse"><stop class="imlbmc2sy"/><stop offset="1" class="h7wwwp44w"/></linearGradient><linearGradient id="iYEOHJJ" x1="15.935" x2="15.935" y1="15.588" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="plsegxa8t"/><stop offset="1" class="dbg8b7bda"/></linearGradient><linearGradient id="izD4dme" x1="8.661" x2="8.938" y1="29.963" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="rq6u1obxj"/><stop offset="1" class="yomd27bxe"/></linearGradient><linearGradient id="iOqaXXb" x1="23.206" x2="22.776" y1="29.963" y2="29.963" gradientUnits="userSpaceOnUse"><stop offset=".136" class="i0lopbdha"/><stop offset="1" class="w11i7m31i"/></linearGradient><linearGradient id="ipKjL7b" x1="8.759" x2="7.51" y1="28.776" y2="28.776" gradientUnits="userSpaceOnUse"><stop class="k6ta6mb-r"/><stop offset="1" class="drixk4bdm"/></linearGradient><linearGradient id="isG10Od" x1="15.939" x2="15.939" y1="20.932" y2="29.963" gradientUnits="userSpaceOnUse"><stop class="zajm34fcf"/><stop offset="1" class="puh_1hb6q"/></linearGradient><linearGradient id="idf2Bve" x1="15.939" x2="15.939" y1="29.963" y2="27.307" gradientUnits="userSpaceOnUse"><stop class="ou_12nqfl"/><stop offset="1" class="ypzxpcc2j"/></linearGradient><linearGradient id="iJpq4RY" x1="19.542" x2="17.698" y1="28.776" y2="28.776" gradientUnits="userSpaceOnUse"><stop offset=".119" class="zxxizob4i"/><stop offset="1" class="u7u0nyv_w"/></linearGradient><linearGradient id="i0X2fhd" x1="15.935" x2="15.935" y1="17.854" y2="25.882" gradientUnits="userSpaceOnUse"><stop class="gmn9ea1yo"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="i4ErBSc" x1="19.919" x2="12.314" y1="10.779" y2="11.857" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iLaDhnb" x1="10.546" x2="12.797" y1="13.595" y2="13.461" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iu9Fuqc" x1="15.937" x2="15.937" y1="-6.218" y2="17.27" gradientUnits="userSpaceOnUse"><stop offset=".979" class="wvw1ebchz"/><stop offset="1" class="y2xm7ibwq"/></linearGradient><linearGradient id="ihx55fd" x1="17.146" x2="25.771" y1="7.274" y2="4.305" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iOCEe2F" x1="15.948" x2="15.948" y1="14.705" y2="14.284" gradientUnits="userSpaceOnUse"><stop class="hln8tw04j"/><stop offset="1" class="muom63bbu"/></linearGradient><linearGradient id="iW3m3ZG" x1="17.479" x2="16.94" y1="13.893" y2="14.135" gradientUnits="userSpaceOnUse"><stop class="fqd3y7eiz"/><stop offset="1" class="joyqtdb2o"/></linearGradient><linearGradient id="iEIkO4b" x1="16.351" x2="16.479" y1="19.112" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="iS9ZmDb" x1="15.546" x2="15.417" y1="19.112" y2="19.721" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="i4Aug4d" x1="15.101" x2="16.04" y1="11.807" y2="11.807" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iEdxC9b" x1="16.905" x2="15.879" y1="12.129" y2="12.115" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="i9B8mTb" x1="16.161" x2="16.161" y1="12.872" y2="12.299" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iawMBsb" x1="18.886" x2="18.63" y1="10.136" y2="10.301" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iMJRHhX" x1="14.524" x2="14.21" y1="10.128" y2="10.322" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iQ6n1we" x1="21.542" x2="22.417" y1="8.432" y2="11.12" gradientUnits="userSpaceOnUse"><stop class="nn6-fgbyw"/><stop offset="1" class="kgk9-3b8f"/></linearGradient><linearGradient id="iLJ98Pb" x1="21.862" x2="22.131" y1="8.174" y2="8.596" gradientUnits="userSpaceOnUse"><stop class="b-jo-_osr"/><stop offset="1" class="bmy67tbbi"/></linearGradient><linearGradient id="iXzF3Oe" x1="8.981" x2="11.396" y1="10.514" y2="9.507" gradientUnits="userSpaceOnUse"><stop class="fhqxyfhau"/><stop offset="1" class="thtu3qbtz"/></linearGradient><linearGradient id="iZvZE6c" x1="12.913" x2="14.317" y1="8.298" y2="8.031" gradientUnits="userSpaceOnUse"><stop class="s0qsib-ln"/><stop offset="1" class="i5bggbceb"/></linearGradient><linearGradient id="ikoviGe" x1="13.738" x2="13.252" y1="7.957" y2="7.091" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ija004O" x1="18.225" x2="18.769" y1="7.918" y2="6.947" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><filter id="iJnpAXd" width="4.702" height="8.2" x="22.301" y="11.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1219"/></filter><filter id="ir9yXEc" width="4.902" height="8.4" x="5.146" y="11.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.321569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1219"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1219" result="effect2_innerShadow_4002_1219"/></filter><filter id="iAOzrAc" width="6.968" height="4.815" x="12.464" y="15.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".25"/></filter><filter id="iJfENOb" width="6.431" height="9.028" x="12.527" y="17.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".25"/></filter><filter id="ia9S4tc" width="6.43" height="4.46" x="12.733" y="15.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.835294 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1219"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.733333 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1219" result="effect2_innerShadow_4002_1219"/></filter><filter id="iCEjAec" width="5.531" height="8.006" x="13.22" y="18.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.705882 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1219"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.670588 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1219" result="effect2_innerShadow_4002_1219"/></filter><filter id="iF2hdnd" width="10.31" height="12.713" x="10.782" y="4.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1219"/></filter><filter id="ita00qc" width="6.25" height="5.07" x="15.357" y="3.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".5"/></filter><filter id="iVXxsDd" width="3.566" height="1.546" x="14.165" y="13.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".05"/></filter><filter id="idgKgxe" width="3.262" height="4.184" x="14.096" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".375"/></filter><filter id="iWnvske" width="2.379" height="3.184" x="14.777" y="9.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".125"/></filter><filter id="isd7rjR" width=".787" height=".697" x="17.413" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".05"/></filter><filter id="ipljz0d" width=".892" height=".914" x="18.253" y="9.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".1"/></filter><filter id="iUU4o4c" width=".987" height="1.041" x="13.807" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".1"/></filter><filter id="ikwF2Lc" width=".914" height=".705" x="13.052" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".05"/></filter><filter id="iXAkvId" width="1.798" height="3.38" x="20.88" y="8.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".05"/></filter><filter id="i5PlyKe" width="2.017" height="3.595" x="9.092" y="8.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".1"/></filter><filter id="izECx0f" width="2.927" height="1.811" x="12.038" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1219"/></filter><filter id="ivJCmzc" width="2.477" height="1.211" x="12.138" y="7.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".125"/></filter><filter id="izoRn6d" width="2.577" height="1.311" x="12.088" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".15"/></filter><filter id="iveQbwc" width="2.927" height="1.811" x="17.264" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1219"/></filter><filter id="ipcHT2d" width="2.785" height="1.367" x="17.237" y="7.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".15"/></filter><filter id="i3lNU2d" width="5.117" height="2.558" x="15.74" y="3.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1219" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-vampire-dark" /></template>
<style>
.a75cnrb-k {
  stop-color: var(--svg-color--47374c, #47374C);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aw-9yhbqw {
  d: path("M10.846 8.669c.034 1.21.073 2.413.109 3.638c-.507-.163-1.116-.606-1.744-1.836c-.538-1.024-.67-1.886-.656-2.527c.005-.237.247-.36.46-.258c.61.292 1.337.659 1.83.983");
}

.b-0vp4bih {
  stop-color: var(--svg-color--454445, #454445);
  stop-opacity: 0;
}

.b-jo-_osr {
  stop-color: var(--svg-color--2f1c19, #2F1C19);
}

.b2cn2_uce {
  stop-color: var(--svg-color--60506b, #60506B);
}

.b6_v0lbsx {
  stop-color: var(--svg-color--351c1a, #351C1A);
  stop-opacity: 0;
}

.blu0296ak {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M17.784 8.389a2.15 2.15 0 0 1 1.417.37a.475.475 0 1 0 .53-.788a3.1 3.1 0 0 0-2.037-.528a.475.475 0 1 0 .09.946");
}

.bmy67tbbi {
  stop-color: var(--svg-color--2f1c19, #2F1C19);
  stop-opacity: 0;
}

.bp-vzngbu {
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M18.084 9.786c.063.085-.07.188-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.bv2dogb4d {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.513 13.464a2.94 2.94 0 0 0 2.87 0c.077-.043.17.022.143.106c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.084.066-.149.143-.107Z");
}

.c8p9zqb6v {
  d: path("M18.15 9.597a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.ca_cpzbpw {
  d: path("M25.979 11.106q.254.22.5.455c.431.413.616 1.02.48 1.601c-.462 1.965-1.584 4.65-3.62 6.144l-1.038-.694c2.587-1.72 3.696-4.97 3.678-7.506");
}

.carxtabzu {
  stop-color: var(--svg-color--604f70, #604F70);
  stop-opacity: 0;
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.cqxd2rkco {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.69 10.635l-.82 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.377-.283-.377-.395 0");
}

.d73walu2l {
  d: path("M13.778 9.597a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.dbg8b7bda {
  stop-color: var(--svg-color--553d71, #553D71);
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

.e7kaubcpd {
  d: path("M18.084 9.786c.063.085-.07.188-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
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

.f6lcb9bkn {
  stop-color: var(--svg-color--56475f, #56475F);
  stop-opacity: 0;
}

.fai_osbjm {
  fill: var(--svg-color--290118, #290118);
  d: path("M14.513 13.464a2.94 2.94 0 0 0 2.87 0c.077-.043.17.022.143.106c-.26.85-.993 1.026-1.578 1.026s-1.317-.176-1.578-1.026c-.026-.084.066-.149.143-.107");
}

.fg6i_oqme {
  stop-color: var(--svg-color--574b64, #574B64);
}

.fhqxyfhau {
  stop-color: var(--svg-color--382326, #382326);
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

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
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

.h_ltlobtq {
  fill-rule: evenodd;
  d: path("M15.438 19.113a.125.125 0 0 0-.141.107l-.649 4.671a.125.125 0 0 0 .248.035l.649-4.672a.125.125 0 0 0-.107-.141");
}

.h1sgipbfm {
  stop-color: var(--svg-color--d82535, #D82535);
}

.h7wwwp44w {
  stop-color: var(--svg-color--302736, #302736);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hbnqzrcju {
  d: path("m17.154 14.62l-.396-.895a3.2 3.2 0 0 0 .623-.264c.102-.057.248.044.218.157l-.257.986a.1.1 0 0 1-.188.015");
}

.hl4dixbko {
  stop-color: var(--svg-color--ff6d74, #FF6D74);
}

.hln8tw04j {
  stop-color: var(--svg-color--4d3c3c, #4D3C3C);
}

.hy1_v56-b {
  stop-color: var(--svg-color--38212d, #38212D);
}

.i0lopbdha {
  stop-color: var(--svg-color--4a2f65, #4A2F65);
}

.i1u0xeg2c {
  stop-color: var(--svg-color--665654, #665654);
  stop-opacity: 0;
}

.i5bggbceb {
  stop-color: var(--svg-color--4f494b, #4F494B);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.ih2ibv29b {
  stop-color: var(--svg-color--574b64, #574B64);
  stop-opacity: 0;
}

.ih2vhqbgt {
  stop-color: var(--svg-color--443738, #443738);
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

.iwate57pq {
  stop-color: var(--svg-color--3e2322, #3E2322);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7d6tdb2g {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.356 9.325c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.ja62qnbvn {
  stop-color: var(--svg-color--252525, #252525);
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

.jzwike70j {
  stop-color: var(--svg-color--a99494, #A99494);
}

.k-yfaib1f {
  d: path("M5.77 11.561c2.243-2.143 5.052-3.376 6.334-3.817l4.063 12.313h-5.891c-2.916-1.118-4.43-4.528-4.986-6.894a1.68 1.68 0 0 1 .48-1.602");
}

.k3ni8ebrh {
  fill: var(--svg-color--decee8, #DECEE8);
  fill-rule: evenodd;
  d: path("M15.438 19.113a.125.125 0 0 0-.141.107l-.649 4.671a.125.125 0 0 0 .248.035l.649-4.672a.125.125 0 0 0-.107-.141");
}

.k6ta6mb-r {
  stop-color: var(--svg-color--423153, #423153);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kgk9-3b8f {
  stop-color: var(--svg-color--4c3332, #4C3332);
}

.khy8pi8et {
  stop-color: var(--svg-color--5c4745, #5C4745);
}

.klq3puw7i {
  cx: 13.509px;
  cy: 9.978px;
  rx: 0.39px;
  ry: 0.197px;
}

.knk60smxr {
  fill-rule: evenodd;
  d: path("M16.458 19.113a.125.125 0 0 1 .141.107l.649 4.671a.125.125 0 1 1-.248.035l-.648-4.672a.125.125 0 0 1 .106-.141");
}

.ko44f1ecp {
  stop-color: var(--svg-color--665654, #665654);
}

.kqp3z9b3n {
  stop-color: var(--svg-color--9c8ea7, #9C8EA7);
  stop-opacity: 0;
}

.l0d7sccpf {
  stop-color: var(--svg-color--48335e, #48335E);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.ldrp94bxq {
  fill: var(--svg-color--442d2b, #442D2B);
  d: path("m15.583 10.471l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.766 0");
}

.lft-zacfy {
  stop-color: var(--svg-color--ff242f, #FF242F);
}

.lmxk8n8zo {
  d: path("m10.778 9.338l.062 1.134l.069 1.24C9.833 10.847 9.41 9.59 9.294 8.765c-.028-.2.19-.318.355-.204z");
}

.lt9tcnl8a {
  d: path("M26.478 11.561c-2.243-2.143-5.051-3.376-6.334-3.817l-4.062 12.313h5.89c2.916-1.118 4.431-4.528 4.986-6.894a1.68 1.68 0 0 0-.48-1.602");
}

.lymk7up5q {
  stop-color: var(--svg-color--594948, #594948);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.moen_vfyr {
  stop-color: var(--svg-color--47423f, #47423F);
  stop-opacity: 0;
}

.muom63bbu {
  stop-color: var(--svg-color--4d3c3c, #4D3C3C);
  stop-opacity: 0;
}

.mzjok2vtv {
  stop-color: var(--svg-color--47423f, #47423F);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n52c8qgao {
  stop-color: var(--svg-color--3d3743, #3D3743);
}

.neb43bcvz {
  stop-color: var(--svg-color--4d4d4d, #4D4D4D);
  stop-opacity: 0;
}

.nn6-fgbyw {
  stop-color: var(--svg-color--463032, #463032);
}

.nnv6oabuq {
  stop-color: var(--svg-color--443738, #443738);
  stop-opacity: 0;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o-vl_tbgb {
  fill: var(--svg-color--000, #000);
  d: path("M17.638 10.49a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
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

.ozza9wbzj {
  stop-color: var(--svg-color--ff136b, #FF136B);
}

.p2-8u3v4t {
  d: path("m10.37 10.082l-.617-2.736c-.117-.426-.242-1.394.024-2.013c.264-.612.68-.836 1.05-1.035c.125-.066.243-.13.35-.204q.123-.089.235-.161c.298-.201.536-.361.875-.762c.422-.5 1.056-1.005 1.76-1.114c.406-.064.784.036 1.146.132c.259.069.509.135.755.137c.246-.002.497-.068.755-.137c.362-.096.74-.196 1.147-.132c.703.11 1.337.613 1.76 1.114c.338.401.576.561.874.762l.236.16c.106.075.224.139.348.205c.37.199.787.423 1.05 1.035c.268.62.142 1.587.025 2.013l-.616 2.736c-.054.238-.298.398-.542.398l.032-1.71c0-1.346-.334-2.387-1.032-3.034c-.982-.911-1.858-.911-2.483-.911c-.675 0-.847.379-1.041.745l-.09.166c-.155.267-.336.337-.423.33c-.087.007-.267-.063-.42-.33q-.048-.082-.091-.166c-.195-.366-.368-.745-1.043-.745c-.625 0-1.5 0-2.483.91c-.697.648-1.032 1.69-1.032 3.034l.021 1.72a.546.546 0 0 1-.53-.407");
}

.p5bq_2b9f {
  stop-color: var(--svg-color--605075, #605075);
}

.p67pqmk9y {
  stop-color: var(--svg-color--351c1a, #351C1A);
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

.pwbqwxbuo {
  d: path("M15.935 15.588c-6.04 0-10.938 5.1-10.938 11.14v3.235h21.875V26.73c0-6.04-4.896-11.14-10.937-11.14");
}

.pxp9rxlhv {
  stop-color: var(--svg-color--e33e4b, #E33E4B);
}

.q4uqrvgrz {
  d: path("M14.594 10.385c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.qhxuaybfw {
  stop-color: var(--svg-color--dfcfe8, #DFCFE8);
  stop-opacity: 0;
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

.ri_i1lblj {
  stop-color: var(--svg-color--47374c, #47374C);
  stop-opacity: 0;
}

.rlrkc3tlk {
  stop-color: var(--svg-color--301f25, #301F25);
}

.rq6u1obxj {
  stop-color: var(--svg-color--453455, #453455);
}

.s0qsib-ln {
  stop-color: var(--svg-color--4f494b, #4F494B);
  stop-opacity: 0;
}

.sfkkzgbur {
  stop-color: var(--svg-color--281717, #281717);
  stop-opacity: 0;
}

.sv6-s7bnh {
  d: path("m15.583 10.471l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.766 0");
}

.thtu3qbtz {
  stop-color: var(--svg-color--221210, #221210);
}

.tik5rtblr {
  d: path("M18.945 10.372a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.trxhxpadd {
  fill: var(--svg-color--faceeb, #FACEEB);
  d: path("m14.735 14.62l.396-.895a3 3 0 0 1-.623-.264c-.103-.057-.249.044-.22.157l.259.986a.1.1 0 0 0 .188.015");
}

.tt0m3dw5o {
  stop-color: var(--svg-color--473031, #473031);
}

.u_per4bve {
  d: path("m20.98 11.696l.131-2.371l1.11-.764c.165-.114.383.004.355.204c-.117.82-.534 2.067-1.596 2.931");
}

.u298-db2x {
  stop-color: var(--svg-color--5b4261, #5B4261);
  stop-opacity: 0;
}

.u7u0nyv_w {
  stop-color: var(--svg-color--dd2864, #DD2864);
  stop-opacity: 0;
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.udqi13bwa {
  stop-color: var(--svg-color--594948, #594948);
  stop-opacity: 0;
}

.uw1qucxdm {
  stop-color: var(--svg-color--d2bdd8, #D2BDD8);
}

.uxwciubxp {
  stop-color: var(--svg-color--776484, #776484);
}

.vbb18ixfb {
  stop-color: var(--svg-color--6b5a80, #6B5A80);
}

.vo8nxhb-a {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
  stop-opacity: 0;
}

.vx8dsgrfz {
  stop-color: var(--svg-color--281717, #281717);
}

.w11i7m31i {
  stop-color: var(--svg-color--665579, #665579);
  stop-opacity: 0;
}

.w7p3xxgxw {
  d: path("M12.733 29.963V16.071a10.7 10.7 0 0 1 3.183-.483a10.7 10.7 0 0 1 3.23.497v13.878z");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wvw1ebchz {
  stop-color: var(--svg-color--624d68, #624D68);
  stop-opacity: 0;
}

.x4ket23ym {
  d: path("M10.783 7.58a3 3 0 0 1 2.999-3.082h4.31a3 3 0 0 1 3 3.06l-.198 6.36c-.035 1.769-1.408 3.142-3.178 3.142h-3.51c-1.761 0-3.07-1.351-3.194-3.118z");
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

.xon9p4yuw {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M14.195 8.389a2.15 2.15 0 0 0-1.417.37a.475.475 0 1 1-.53-.788a3.1 3.1 0 0 1 2.037-.528a.475.475 0 1 1-.09.946");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xy4gpnq9q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.598 8.279a2.95 2.95 0 0 0-1.936-.504");
}

.y2xm7ibwq {
  stop-color: var(--svg-color--624d68, #624D68);
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

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z556dzc9p {
  stop-color: var(--svg-color--5b4261, #5B4261);
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

.zo0v05b9a {
  fill: var(--svg-color--c91a3b, #C91A3B);
  d: path("m14.177 17.916l-1.144 6.986a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.027l.706.514a1.1 1.1 0 0 0 1.294 0l.706-.514a.51.51 0 0 1 .553-.027l.202.118a.402.402 0 0 0 .602-.409l-1.145-6.986z");
}

.zpyvujcqa {
  d: path("M16.45 4.226c-.25.315-.42.986-.46 1.53c.352-1.034.773-1.247 1.258-1.347c1.139-.152 2.78.504 3.359 1.038l-.374-1.038c-2.665-1.182-3.425-.635-3.783-.183");
}

.zq1muvb_r {
  d: path("M6.27 11.106q-.255.22-.5.455a1.68 1.68 0 0 0-.48 1.601c.461 1.965 1.584 4.65 3.62 6.144l1.038-.694c-2.588-1.72-3.697-4.97-3.678-7.506");
}

.zr5cz1b9r {
  stop-color: var(--svg-color--5c4745, #5C4745);
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
