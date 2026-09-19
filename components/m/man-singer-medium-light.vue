<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVmrk8c)"><path class="xhp754bts"/><path fill="url(#i4IqaWU)" class="dj6qfxndk"/></g><path fill="url(#itEOEpd)" class="m4u9d6r0j"/><path fill="url(#i0kszZb)" class="m4u9d6r0j"/><path fill="url(#ihWU5kt)" class="xpd2e2t7y"/><path fill="url(#i5ZDW9d)" class="xpd2e2t7y"/><path fill="url(#iaEm3Me)" class="neyz8yb1c"/><path fill="url(#iRje3Sd)" class="neyz8yb1c"/><path fill="url(#iJ4jfzc)" class="neyz8yb1c"/><path fill="url(#iGp4x1u)" class="neyz8yb1c"/><path fill="url(#iznjpvi)" class="n8wtl0b_o"/><path fill="url(#iXaaQ8d)" class="n8wtl0b_o"/><path fill="url(#iSdAYrB)" class="n8wtl0b_o"/><path fill="url(#iNR0DWb)" class="n8wtl0b_o"/><path fill="url(#iWAOYke)" class="n8wtl0b_o"/><path fill="url(#iBIA20c)" class="n8wtl0b_o"/><path fill="url(#iWNIeub)" class="wfk0b1b2c"/><path fill="url(#iFsev9K)" class="rqemgpbiq"/><path fill="url(#iYxVM6c)" class="sjsog7b_u"/><path fill="url(#il5NChb)" class="fva4zc4tm"/><path fill="url(#ikBiWlc)" class="fva4zc4tm"/><path fill="url(#i0BmV1d)" class="fva4zc4tm"/><path fill="url(#ie4OMGd)" class="ci289sbof"/><path fill="url(#iq2Kksc)" class="ci289sbof"/><path fill="url(#iJqB6Cd)" class="js7h86bfp"/><path fill="url(#iv6p3Ed)" class="js7h86bfp"/><path fill="url(#ieu3U5d)" class="js7h86bfp"/><path fill="url(#is7ILLb)" class="js7h86bfp"/><g filter="url(#ibY6xUb)"><path fill="url(#ino6VTb)" class="ovwqwcbkx"/><path fill="url(#i23dblb)" class="ovwqwcbkx"/><path fill="url(#iLfxbDs)" class="ovwqwcbkx"/></g><path fill="url(#iAtNg5a)" class="y0_5ht3_i"/><path fill="url(#igbvAmd)" class="y0_5ht3_i"/><path fill="url(#inPX58b)" class="y0_5ht3_i"/><g filter="url(#i4Qz3Be)"><path fill="url(#iYOnrFc)" class="low24eudf"/></g><g filter="url(#i8ea97d)"><circle fill="url(#iCKEY2d)" class="dvmb0bckc"/></g><g filter="url(#iB6c5xd)"><circle fill="url(#i1vEgjd)" class="tg-s8abty"/></g><g filter="url(#izekmCu)"><path fill="url(#ifWSkts)" class="x1ne5fbzc"/><path fill="url(#iGCwfFc)" class="x1ne5fbzc"/><path fill="url(#i1SPrOe)" class="x1ne5fbzc"/><path fill="url(#iKiMRue)" class="x1ne5fbzc"/><path fill="url(#iOJsEPM)" class="x1ne5fbzc"/></g><path fill="url(#i3E6u9b)" class="x1ne5fbzc"/><g filter="url(#i2joJrd)"><path stroke="url(#ih9XnPe)" class="oe1j8rb7n"/></g><g filter="url(#iJobRHb)"><path stroke="url(#ivsFrze)" class="ouy8z3mnc"/></g><g filter="url(#iplCzFb)"><path stroke="url(#inRwBkn)" class="sigduobyo"/></g><g filter="url(#it39aQe)"><circle fill="url(#ikmjy1c)" class="io24nwwgn"/></g><g filter="url(#iTEhI5c)"><circle fill="url(#inILizc)" class="jpwfu-e-s"/></g><g filter="url(#iUi7psR)"><circle fill="url(#iw1hzpc)" class="as2pky0jp"/><circle fill="url(#iyvgTFc)" class="as2pky0jp"/></g><g filter="url(#iJH0U9c)"><circle class="apn7ddbmj"/><circle fill="url(#iRvdF8c)" class="tfx5otb7y"/><circle fill="url(#ikaRnCe)" class="tfx5otb7y"/></g><g filter="url(#iFku24c)"><path fill="url(#i7rV2ne)" class="c7230xn7l"/><path fill="url(#ii4OSmV)" class="c7230xn7l"/><path fill="url(#ihbN8nc)" class="c7230xn7l"/><path fill="url(#iP5MrSd)" class="c7230xn7l"/><path fill="url(#idjTT9c)" class="c7230xn7l"/></g><g filter="url(#iX0q9sc)"><path class="gx9s9j3sy"/><path fill="url(#iVxnuwc)" class="rx4ce3blw"/><path fill="url(#iNTpI4b)" class="rx4ce3blw"/><path fill="url(#ivJOkGb)" class="rx4ce3blw"/><path fill="url(#iWpPcre)" class="rx4ce3blw"/><path fill="url(#itrGBcd)" class="rx4ce3blw"/></g><path fill="url(#iMIaJMb)" class="rx4ce3blw"/><path fill="url(#iL4k2gc)" class="rx4ce3blw"/><g filter="url(#im86gle)"><path class="sh7tmum4y"/></g><g filter="url(#iwRJYnc)"><path class="hcpr6cc-o"/><path fill="url(#itDHiVP)" class="o9et0qb8x"/><path fill="url(#iPSDxwd)" class="o9et0qb8x"/><path fill="url(#idq6gMX)" class="o9et0qb8x"/></g><path fill="url(#iNTOtLe)" class="o9et0qb8x"/><path fill="url(#iixKk6d)" class="m361m5alk"/><path fill="url(#ixIi50c)" class="m361m5alk"/><path fill="url(#i6AN4ee)" class="m361m5alk"/><path stroke="url(#iqP8Vwb)" class="yimlv425j"/><g filter="url(#igxxFwr)"><path class="fhk2k-b2h"/></g><g filter="url(#i2D5qhk)"><path class="ayhkgbcfd"/></g><path class="r6gk2ob0d"/><path fill="url(#iFn6web)" class="oa_yw8g2j"/><path class="fxrhd9nep"/><g filter="url(#iSsQjpd)"><path class="n-7noab7a"/><path fill="url(#ieT4kGF)" class="oxhl00c8r"/></g><g filter="url(#imONrtb)"><path fill="url(#iZBRaqb)" class="h_u3apvbc"/></g><path class="c-z6rh5fm"/><path fill="url(#i9zNMse)" class="c2j9vgd0d"/><path class="d3cfkkwyg"/><g filter="url(#ix9ANTb)"><path fill="url(#ikGxA0N)" class="qf8tf3huz"/></g><g filter="url(#iK4HIfb)"><ellipse transform="rotate(-27.914 12.606 11.826)" class="slev0_bsk"/><ellipse fill="url(#ihusHWd)" transform="rotate(-27.914 12.606 11.826)" class="tieh5dq6f"/></g><g filter="url(#iEmiKud)"><path stroke="url(#iisv1Hc)" class="qb1jv518x"/></g><g filter="url(#ib0pkZc)"><path stroke="url(#iLmcBrb)" class="nw3m5of2w"/></g><defs><radialGradient id="itEOEpd" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.628 26.119)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="ihWU5kt" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.451 19.77)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="iJ4jfzc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.16 18.4)" gradientUnits="userSpaceOnUse"><stop class="m4vk7-mbl"/><stop offset="1" class="esw1hmivn"/></radialGradient><radialGradient id="iXaaQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55616 -6.67822 .6506 -.1516 13.17 29.02)" gradientUnits="userSpaceOnUse"><stop class="o4j1rvu5g"/><stop offset="1" class="yp-hr1bpr"/></radialGradient><radialGradient id="iBIA20c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17874 .81494 -1.02635 -2.74392 12.107 18.285)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="k910dfb4a"/><stop offset="1" class="vm-pj7b0c"/></radialGradient><radialGradient id="il5NChb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.026 20.767)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="qlsp8sbaz"/><stop offset=".838" class="w422gwoow"/></radialGradient><radialGradient id="ikBiWlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.026 24.71)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="k-23bl_xw"/><stop offset=".937" class="f6id_baiq"/></radialGradient><radialGradient id="ie4OMGd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1394 1.4599 -1.43346 -2.10066 28.638 22.029)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iq2Kksc" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.006 21.867)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iv6p3Ed" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.19 12.322)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="ieu3U5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.762 15.715)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="is7ILLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.832 17.073)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="i23dblb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.426 17.464)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iYOnrFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.901 21.335)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="iCKEY2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39063 -2.6875 6.04551 -3.1282 15.845 20.61)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="pz-_6uplk"/><stop offset="1" class="ixm2pmbhy"/></radialGradient><radialGradient id="i1vEgjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5843 -1.90116 0 15.07 18.945)" gradientUnits="userSpaceOnUse"><stop class="xu32dvb5s"/><stop offset="1" class="ohzrjbbgt"/></radialGradient><radialGradient id="iGCwfFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 25.994 23.874)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i1SPrOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 25.994 25.293)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iKiMRue" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 25.994 26.663)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iOJsEPM" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 25.994 28.144)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i3E6u9b" cx="0" cy="0" r="1" gradientTransform="rotate(120.493 7.784 19.986)scale(6.49967 4.40837)" gradientUnits="userSpaceOnUse"><stop class="hsdt12m1i"/><stop offset="1" class="v1bt46wqv"/></radialGradient><radialGradient id="ikmjy1c" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 8.644 12.604)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iyvgTFc" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 20.198 12.339)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iRvdF8c" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.785 13.425)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="ikaRnCe" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 19.826 12.604)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="ii4OSmV" cx="0" cy="0" r="1" gradientTransform="matrix(-.37433 10.18753 -9.73318 -.35763 15.906 9.063)" gradientUnits="userSpaceOnUse"><stop offset=".758" class="fihgniict"/><stop offset=".984" class="w0p4v4b3q"/></radialGradient><radialGradient id="iP5MrSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 17.407 11.332)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="idjTT9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 12.85 11.299)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iVxnuwc" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 8.179 7.039)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="ivJOkGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 10.868 9.149)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iWpPcre" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 19.288 10.867)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="itrGBcd" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 14.286 4.003)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iMIaJMb" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 15.756 4.003)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iL4k2gc" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 10.716 5.731)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iixKk6d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.587 7.217)" gradientUnits="userSpaceOnUse"><stop class="po4m-u0pm"/><stop offset="1" class="f13vhyddz"/></radialGradient><radialGradient id="ixIi50c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.053 11.686)" gradientUnits="userSpaceOnUse"><stop class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="i6AN4ee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.61343 7.44672 0 13.053 12.594)" gradientUnits="userSpaceOnUse"><stop offset=".958" class="di5ujabpk"/><stop offset="1" class="k959jsblr"/></radialGradient><radialGradient id="iFn6web" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 17.24 12.255)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ieT4kGF" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.446 1.837)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9zNMse" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 12.877 12.255)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ihusHWd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.272 -.127)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="i4IqaWU" x1="16.822" x2="15.424" y1="26.64" y2="26.337" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="i0kszZb" x1="7.119" x2="5.947" y1="26.439" y2="26.439" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="i5ZDW9d" x1="23.048" x2="23.69" y1="26.525" y2="26.494" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iaEm3Me" x1="22.69" x2="18.315" y1="16.51" y2="29.02" gradientUnits="userSpaceOnUse"><stop class="c08ew-b0i"/><stop offset="1" class="exuz4sbao"/></linearGradient><linearGradient id="iRje3Sd" x1="16.744" x2="17.451" y1="27.011" y2="27.105" gradientUnits="userSpaceOnUse"><stop class="q5z4iwf2u"/><stop offset="1" class="t7ud1ab5b"/></linearGradient><linearGradient id="iGp4x1u" x1="20.707" x2="20.707" y1="16.51" y2="17.609" gradientUnits="userSpaceOnUse"><stop offset=".457" class="tffk3lifv"/><stop offset="1" class="e4yz8gz4u"/></linearGradient><linearGradient id="iznjpvi" x1="7.815" x2="11.815" y1="18.15" y2="29.4" gradientUnits="userSpaceOnUse"><stop class="m3gjwjbhl"/><stop offset="1" class="c9zswtx-n"/></linearGradient><linearGradient id="iSdAYrB" x1="8.285" x2="8.983" y1="16.256" y2="19.82" gradientUnits="userSpaceOnUse"><stop class="s434a46or"/><stop offset="1" class="qrv_44bpu"/></linearGradient><linearGradient id="iNR0DWb" x1="7.815" x2="8.229" y1="23.088" y2="22.884" gradientUnits="userSpaceOnUse"><stop class="bwk0n7bpz"/><stop offset="1" class="oinrtsbml"/></linearGradient><linearGradient id="iWAOYke" x1="13.659" x2="13.248" y1="28.716" y2="28.802" gradientUnits="userSpaceOnUse"><stop class="ifhx39w3y"/><stop offset="1" class="tmbtljdgb"/></linearGradient><linearGradient id="iWNIeub" x1="23.315" x2="21.534" y1="26.556" y2="26.556" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="iFsev9K" x1="8.034" x2="10.315" y1="28.369" y2="27.213" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="iYxVM6c" x1="15.032" x2="15.032" y1="17.91" y2="29.014" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i0BmV1d" x1="17.806" x2="15.845" y1="22.6" y2="22.272" gradientUnits="userSpaceOnUse"><stop offset=".196" class="kgt9ojbtf"/><stop offset=".671" class="m1nlemiqb"/></linearGradient><linearGradient id="iJqB6Cd" x1="25.659" x2="25.659" y1="16.206" y2="20.263" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="ino6VTb" x1="25.854" x2="25.712" y1="17.142" y2="18.346" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iLfxbDs" x1="23.156" x2="23.283" y1="17.079" y2="17.515" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="iAtNg5a" x1="26.856" x2="24.569" y1="21.649" y2="21.649" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="igbvAmd" x1="24.386" x2="24.767" y1="21.492" y2="21.464" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="inPX58b" x1="27.004" x2="26.742" y1="21.363" y2="21.34" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="ifWSkts" x1="27.917" x2="23.048" y1="26.896" y2="26.896" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="ih9XnPe" x1="23.663" x2="25.583" y1="24.694" y2="24.694" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="ivsFrze" x1="23.663" x2="25.583" y1="26.136" y2="26.136" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="inRwBkn" x1="23.663" x2="25.583" y1="27.566" y2="27.566" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="inILizc" x1="10.314" x2="9.673" y1="12.882" y2="12.882" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iw1hzpc" x1="20.912" x2="20.094" y1="11.512" y2="14.048" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="i7rV2ne" x1="19.097" x2="11.46" y1="12.993" y2="14.131" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ihbN8nc" x1="9.666" x2="11.978" y1="15.689" y2="15.387" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iNTpI4b" x1="10.2" x2="13.102" y1="12.337" y2="7.182" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="itDHiVP" x1="14.197" x2="15.135" y1="13.652" y2="13.652" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iPSDxwd" x1="15.999" x2="14.974" y1="13.975" y2="13.96" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="idq6gMX" x1="15.256" x2="15.256" y1="14.717" y2="14.144" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iNTOtLe" x1="15.187" x2="15.187" y1="14.759" y2="14.591" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iqP8Vwb" x1="14.024" x2="14.459" y1="16.332" y2="15.645" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iZBRaqb" x1="18.017" x2="17.704" y1="11.976" y2="12.169" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikGxA0N" x1="13.621" x2="13.307" y1="11.976" y2="12.169" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iisv1Hc" x1="18.033" x2="17.613" y1="9.836" y2="8.978" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iLmcBrb" x1="12.729" x2="11.54" y1="9.709" y2="9.21" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><filter id="iVmrk8c" width="5.513" height="4.74" x="12.768" y="24.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="ibY6xUb" width="6.102" height="1.228" x="22.711" y="16.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="i4Qz3Be" width="1.075" height="1.075" x="25.119" y="21.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2323" result="effect2_innerShadow_4002_2323"/></filter><filter id="i8ea97d" width="5.967" height="5.967" x="12.086" y="15.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".125"/></filter><filter id="iB6c5xd" width="5.612" height="5.612" x="12.264" y="15.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".2"/></filter><filter id="izekmCu" width="5.369" height="6.076" x="23.048" y="22.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="i2joJrd" width="2.319" height=".3" x="23.513" y="24.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".05"/></filter><filter id="iJobRHb" width="2.319" height=".3" x="23.513" y="25.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".05"/></filter><filter id="iplCzFb" width="2.319" height=".3" x="23.513" y="27.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".05"/></filter><filter id="it39aQe" width="3.539" height="3.339" x="8.644" y="10.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="iTEhI5c" width="2.99" height="2.99" x="8.819" y="11.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".25"/></filter><filter id="iUi7psR" width="3.589" height="3.589" x="18.157" y="10.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="iJH0U9c" width="2.99" height="2.99" x="18.331" y="11.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".25"/></filter><filter id="iFku24c" width="10.373" height="12.077" x="9.903" y="6.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="iX0q9sc" width="12.601" height="8.543" x="8.761" y="3.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="im86gle" width="3.26" height="4.181" x="13.192" y="11.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".375"/></filter><filter id="iwRJYnc" width="2.377" height="3.181" x="13.873" y="11.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".125"/></filter><filter id="igxxFwr" width="2.979" height="1.873" x="16.243" y="8.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="i2D5qhk" width="2.98" height="1.873" x="11.096" y="8.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2323"/></filter><filter id="iSsQjpd" width=".787" height=".696" x="16.506" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".05"/></filter><filter id="imONrtb" width=".891" height=".913" x="17.346" y="11.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".1"/></filter><filter id="ix9ANTb" width=".986" height="1.04" x="12.904" y="11.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".1"/></filter><filter id="iK4HIfb" width=".913" height=".704" x="12.149" y="11.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".05"/></filter><filter id="iEmiKud" width="3.099" height="1.681" x="16.097" y="9.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".25"/></filter><filter id="ib0pkZc" width="3.177" height="1.738" x="10.878" y="9.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2323" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-singer-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.apn7ddbmj {
  cx: 19.826px;
  cy: 12.604px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.as2pky0jp {
  cx: 19.826px;
  cy: 12.604px;
  r: 1.669px;
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.ayhkgbcfd {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m11.288 9.884l.002-.001l.005-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.16a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.3.16l-.008.005a.534.534 0 0 1-.68-.824");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bwk0n7bpz {
  stop-color: var(--svg-color--3e8ed5, #3E8ED5);
}

.c-z6rh5fm {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.668 11.173c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.c08ew-b0i {
  stop-color: var(--svg-color--2ca9dd, #2CA9DD);
}

.c2j9vgd0d {
  d: path("M12.875 11.445a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.c7230xn7l {
  d: path("m9.962 11.991l.049.002s-.054-.853-.107-1.44c0-.267.107-.587.321-.747l.161-.16c.268-.213.376-.533.376-.853V7.94c0-.267.16-.48.429-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.272.267 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003z");
}

.c9zswtx-n {
  stop-color: var(--svg-color--3073d6, #3073D6);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.ci289sbof {
  d: path("M27.197 21.335c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d3cfkkwyg {
  fill: var(--svg-color--000, #000);
  d: path("M13.386 12.337a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.904a.5.5 0 0 0 .061-.235");
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.di5ujabpk {
  stop-color: var(--svg-color--f0276f, #F0276F);
  stop-opacity: 0;
}

.dj6qfxndk {
  d: path("M12.768 24.27v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dvmb0bckc {
  cx: 15.07px;
  cy: 18.16px;
  r: 2.734px;
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e4yz8gz4u {
  stop-color: var(--svg-color--2ea1dc, #2EA1DC);
  stop-opacity: 0;
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.esw1hmivn {
  stop-color: var(--svg-color--2796d4, #2796D4);
  stop-opacity: 0;
}

.exuz4sbao {
  stop-color: var(--svg-color--3069c9, #3069C9);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f13vhyddz {
  stop-color: var(--svg-color--e9295e, #E9295E);
}

.f6id_baiq {
  stop-color: var(--svg-color--bb6a4f, #BB6A4F);
}

.fhk2k-b2h {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m18.78 9.884l-.003-.001l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107a2.5 2.5 0 0 0-.42-.21a2.83 2.83 0 0 0-1.492-.16a.534.534 0 0 0 .166 1.055c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .3.16l.008.005a.534.534 0 0 0 .678-.824");
}

.fihgniict {
  stop-color: var(--svg-color--d69494, #D69494);
  stop-opacity: 0;
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.fva4zc4tm {
  d: path("M15.038 16.823c-1.16 0-2.486.209-3.566.58l1.29 6.873c.72.325 1.496.434 2.316.434c.77 0 1.51-.073 2.19-.352l1.313-6.955c-1.05-.383-2.383-.58-3.543-.58");
}

.fxrhd9nep {
  fill: var(--svg-color--000, #000);
  d: path("M16.73 12.337c0-.284.228-.51.512-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.061-.235");
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gx9s9j3sy {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m19.88 6.127l.429.213c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.43-.96a1.25 1.25 0 0 1-.374-.853V7.94c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.586.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04C8.67 7.566 9.1 6.713 9.85 6.34l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h_u3apvbc {
  d: path("M18.037 12.22a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.hcpr6cc-o {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m14.679 12.319l-.531 1.699c-.109.35.151.7.52.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hsdt12m1i {
  stop-color: var(--svg-color--feca9f, #FECA9F);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.ifhx39w3y {
  stop-color: var(--svg-color--3469bc, #3469BC);
}

.io24nwwgn {
  cx: 10.314px;
  cy: 12.604px;
  r: 1.669px;
}

.ixm2pmbhy {
  stop-color: var(--svg-color--c0705f, #C0705F);
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jpwfu-e-s {
  cx: 10.314px;
  cy: 12.604px;
  r: 0.995px;
}

.js7h86bfp {
  d: path("M25.687 20.209a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k-23bl_xw {
  stop-color: var(--svg-color--bb6a4f, #BB6A4F);
  stop-opacity: 0;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k910dfb4a {
  stop-color: var(--svg-color--2c649b, #2C649B);
}

.k959jsblr {
  stop-color: var(--svg-color--f0276f, #F0276F);
}

.kgt9ojbtf {
  stop-color: var(--svg-color--ae6047, #AE6047);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
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

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.low24eudf {
  d: path("M25.656 22.138a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.m1nlemiqb {
  stop-color: var(--svg-color--c37b68, #C37B68);
  stop-opacity: 0;
}

.m361m5alk {
  d: path("M14.964 6.98c-.905.007-1.676.071-2.301.154l-2.104 6.194h1.809l-.508 2.687l3.688-5.133h-1.883z");
}

.m3gjwjbhl {
  stop-color: var(--svg-color--258ec6, #258EC6);
}

.m4u9d6r0j {
  d: path("M6.998 29.01v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.m4vk7-mbl {
  stop-color: var(--svg-color--40a8ea, #40A8EA);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.n-7noab7a {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.176 11.634c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n8wtl0b_o {
  d: path("M5.325 17.031h6.086l2.248 11.99h-2.79L4.99 17.49c-.086-.124-.07-.46.336-.46");
}

.neyz8yb1c {
  d: path("M24.233 17.024h-5.58L16.38 29.02h3.148l5.325-11.016a.685.685 0 0 0-.62-.98");
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.nw3m5of2w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.503 10.258c.327-.29 1.041-.594 1.927-.452");
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o4j1rvu5g {
  stop-color: var(--svg-color--3778d0, #3778D0);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o9et0qb8x {
  d: path("m14.679 12.319l-.531 1.699c-.109.35.151.7.52.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.oa_yw8g2j {
  d: path("M17.242 11.445a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe1j8rb7n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.663 24.616h2.019");
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ohzrjbbgt {
  stop-color: var(--svg-color--d1867a, #D1867A);
}

.oinrtsbml {
  stop-color: var(--svg-color--2a85ce, #2A85CE);
  stop-opacity: 0;
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.ouy8z3mnc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.663 26.057h2.019");
}

.ovwqwcbkx {
  d: path("m28.134 17.05l-4.844-.02a.57.57 0 0 0-.579.58c0 .324.254.578.58.578l4.843.02a.57.57 0 0 0 .579-.579a.585.585 0 0 0-.58-.578");
}

.oxhl00c8r {
  d: path("M17.176 11.634c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.po4m-u0pm {
  stop-color: var(--svg-color--ff338e, #FF338E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pz-_6uplk {
  stop-color: var(--svg-color--db9a86, #DB9A86);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q5z4iwf2u {
  stop-color: var(--svg-color--3466b9, #3466B9);
}

.qb1jv518x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.722 9.74c.43-.076 1.268-.054 1.849.397");
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qf8tf3huz {
  d: path("M13.69 12.232c0-.288-.234-.48-.298-.538l-.288.278l.178.362z");
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qlsp8sbaz {
  stop-color: var(--svg-color--e3a28a, #E3A28A);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qrv_44bpu {
  stop-color: var(--svg-color--2987cc, #2987CC);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r6gk2ob0d {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.449 11.173c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.rqemgpbiq {
  d: path("M6.998 29.01h3.87l-3.87-7.596z");
}

.rx4ce3blw {
  d: path("m19.88 6.127l.429.213c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.43-.96a1.25 1.25 0 0 1-.374-.853V7.94c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.323.48-.323.747c.054.586.108 1.44.108 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04C8.67 7.566 9.1 6.713 9.85 6.34l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.694 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s434a46or {
  stop-color: var(--svg-color--3a90be, #3A90BE);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sh7tmum4y {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m14.786 12.482l-.82 1.7c-.102.349.142.698.488.698h.737c.345 0 .59-.355.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.sigduobyo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.663 27.488h2.019");
}

.sjsog7b_u {
  d: path("M15.038 17.91c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.slev0_bsk {
  cx: 12.606px;
  cy: 11.826px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t7ud1ab5b {
  stop-color: var(--svg-color--3073cd, #3073CD);
  stop-opacity: 0;
}

.tffk3lifv {
  stop-color: var(--svg-color--3ca6cf, #3CA6CF);
}

.tfx5otb7y {
  cx: 19.826px;
  cy: 12.604px;
  r: 0.995px;
}

.tg-s8abty {
  cx: 15.07px;
  cy: 18.27px;
  r: 2.406px;
}

.tieh5dq6f {
  cx: 12.606px;
  cy: 11.826px;
  rx: 0.389px;
  ry: 0.197px;
}

.tmbtljdgb {
  stop-color: var(--svg-color--2e7fd1, #2E7FD1);
  stop-opacity: 0;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v1bt46wqv {
  stop-color: var(--svg-color--feca9f, #FECA9F);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vm-pj7b0c {
  stop-color: var(--svg-color--288acb, #288ACB);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w0p4v4b3q {
  stop-color: var(--svg-color--c17c8d, #C17C8D);
}

.w422gwoow {
  stop-color: var(--svg-color--ba6a59, #BA6A59);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wfk0b1b2c {
  d: path("M23.048 29.01v-7.268l-3.52 7.268z");
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrhkd7bsy {
  stop-color: var(--svg-color--be2252, #BE2252);
  stop-opacity: 0;
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x1ne5fbzc {
  d: path("M23.048 23.897a.81.81 0 0 1 .816-.802h3.055c.744 0 1.348.588 1.348 1.315v3.514c0 .605-.503 1.096-1.124 1.096h-3.279a.81.81 0 0 1-.816-.802c0-.314.187-.589.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.721a.8.8 0 0 1-.458-.72");
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xhp754bts {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.768 24.27v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xpd2e2t7y {
  d: path("M26.938 29.01c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xu32dvb5s {
  stop-color: var(--svg-color--bf6d76, #BF6D76);
}

.y0_5ht3_i {
  d: path("M25.646 26.85a.784.784 0 0 1-.782-.71l-.67-6.429l2.975.01l-.73 6.428a.8.8 0 0 1-.793.701");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yimlv425j {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.7 15.36a2.94 2.94 0 0 0 1.361.324c.505 0 .969-.118 1.362-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.986-.28l2.945.253m-2.945-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.22.253m3.207.028l-.042-.028m.042.028l-.042-.028m.042.028a1.94 1.94 0 0 1-1.625.868c-.681 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.yp-hr1bpr {
  stop-color: var(--svg-color--3778d0, #3778D0);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
