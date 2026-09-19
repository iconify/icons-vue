<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#idxNEqe)" class="t33_u7ubh"/><path fill="url(#iH7kEqb)" class="t33_u7ubh"/><path class="qlm1ogbzf"/><path fill="url(#iEFRvje)" class="e894g4uve"/><path fill="url(#iC845UK)" class="e894g4uve"/><path fill="url(#i0ssEFe)" class="gsb4pmijh"/><path fill="url(#icQek1d)" class="ck7n5tgmp"/><path fill="url(#iKsVOQe)" class="ofy_3cbpe"/><g filter="url(#ipVz68b)"><circle fill="url(#ivLt2zO)" class="nfhvlubqq"/></g><g filter="url(#iMxSk0b)"><circle fill="url(#iQ6IT1b)" class="vwpcicbfm"/></g><g filter="url(#i0iG5Ac)"><circle fill="url(#iyD7dqc)" class="jpgm3tbkg"/><circle fill="url(#iEwIjic)" class="jpgm3tbkg"/></g><g filter="url(#ij7V4Ad)"><circle class="eq22whbkx"/><circle fill="url(#iMTCN3c)" class="ylwfifbow"/><circle fill="url(#iqqeVDp)" class="ylwfifbow"/></g><g filter="url(#isWLgfc)"><path fill="url(#iEIaJtD)" class="av9f1lb0o"/><path fill="url(#ibCaPec)" class="av9f1lb0o"/><path fill="url(#iKze3fd)" class="av9f1lb0o"/><path fill="url(#ioqrGCc)" class="av9f1lb0o"/><path fill="url(#id3rhEd)" class="av9f1lb0o"/><path fill="url(#iLU8HKd)" class="av9f1lb0o"/></g><g filter="url(#i6ZMsqe)"><path fill="url(#ib4IYLb)" class="oov_job6w"/></g><g filter="url(#iL9UEEO)"><path class="px_us0b5s"/><path fill="url(#iXlqRJb)" class="rojh-xb-t"/><path fill="url(#iXKxUYd)" class="rojh-xb-t"/><path fill="url(#iVeWUiC)" class="rojh-xb-t"/><path fill="url(#idjHAUY)" class="rojh-xb-t"/></g><g filter="url(#ifuSqJe)"><path class="yze2dtm7a"/></g><g filter="url(#id0Wzib)"><path class="b__p51-sk"/><path fill="url(#iPUFf0d)" class="f7dil5b8w"/><path fill="url(#i1JCFdd)" class="f7dil5b8w"/><path fill="url(#iN2Mz5c)" class="f7dil5b8w"/><path fill="url(#imTbAQd)" class="f7dil5b8w"/></g><path fill="url(#iz7P5Yb)" class="f7dil5b8w"/><path stroke="url(#ivcqWje)" class="rdu-6vuat"/><g filter="url(#iQZISic)"><path class="r_673df_l"/></g><g filter="url(#iJM9pme)"><path class="hcrp-lnvr"/></g><path class="diccegtzr"/><path fill="url(#iE3ID0w)" class="dbruw5zjj"/><path class="uh1bc69mr"/><g filter="url(#isvBTwd)"><path class="xyaiqyb1d"/><path fill="url(#iQFt9ze)" class="yjh853bae"/></g><g filter="url(#injwrpd)"><path fill="url(#iFqIuGd)" class="hzd4ywoql"/></g><path class="eem5nwbbx"/><path fill="url(#ivAnQod)" class="x7nuoab2y"/><path class="y0-oorbyy"/><g filter="url(#in5dwnd)"><path fill="url(#iU2Zckg)" class="gvmg8ob6v"/></g><g filter="url(#iIlBkwf)"><ellipse transform="rotate(-27.914 13.529 10.166)" class="xf3coib0e"/><ellipse fill="url(#iN3uMDe)" transform="rotate(-27.914 13.529 10.166)" class="i04-0zb8e"/></g><g filter="url(#ipAP5ld)"><path stroke="url(#iR9ASQc)" class="r3v8upbmw"/></g><g filter="url(#iOwS5JZ)"><path stroke="url(#iWX9ePe)" class="t058gv1zl"/></g><g filter="url(#ijtJEoD)"><path stroke="url(#iaEwTHd)" class="odcp9s_mm"/></g><g filter="url(#iqTO2hd)"><path fill="url(#ih7UPDc)" class="rlusx7b3t"/><path fill="url(#ibqe71c)" class="rlusx7b3t"/><path fill="url(#iPSTseb)" class="rlusx7b3t"/><path fill="url(#iwBvMZb)" class="rlusx7b3t"/><path fill="url(#idR73sb)" class="rlusx7b3t"/><path fill="url(#i2ot4bu)" class="rlusx7b3t"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><linearGradient id="iC845UK" x1="26.966" x2="27.302" y1="28.483" y2="28.483" gradientUnits="userSpaceOnUse"><stop class="msex9gbuq"/><stop offset="1" class="eu7hrybov"/></linearGradient><linearGradient id="i0ssEFe" x1="16" x2="16" y1="6.348" y2="34.257" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="icQek1d" x1="10.918" x2="1.428" y1="23.649" y2="23.69" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iKsVOQe" x1="22.998" x2="28.652" y1="23.666" y2="23.666" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iQ6IT1b" x1="11.234" x2="10.593" y1="11.223" y2="11.223" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iyD7dqc" x1="21.844" x2="21.025" y1="9.852" y2="12.391" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iEIaJtD" x1="20.026" x2="12.382" y1="11.334" y2="12.473" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="ibCaPec" x1="10.586" x2="12.853" y1="14.033" y2="13.891" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="ib4IYLb" x1="16.947" x2="25.572" y1="7.953" y2="4.985" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iPUFf0d" x1="15.122" x2="16.061" y1="11.994" y2="11.994" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="i1JCFdd" x1="16.926" x2="15.899" y1="12.317" y2="12.302" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iN2Mz5c" x1="16.181" x2="16.181" y1="13.06" y2="12.486" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iz7P5Yb" x1="16.112" x2="16.112" y1="13.102" y2="12.934" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="ivcqWje" x1="14.949" x2="15.384" y1="14.677" y2="13.988" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iFqIuGd" x1="18.946" x2="18.632" y1="10.316" y2="10.509" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iU2Zckg" x1="14.545" x2="14.231" y1="10.316" y2="10.509" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iR9ASQc" x1="18.962" x2="18.541" y1="8.174" y2="7.315" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iWX9ePe" x1="13.652" x2="12.462" y1="8.046" y2="7.547" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iaEwTHd" x1="11.32" x2="11.32" y1="6.03" y2="8.189" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="ih7UPDc" x1="7.493" x2="11.284" y1="19.4" y2="30.45" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iPSTseb" x1="16" x2="16" y1="15.665" y2="17.025" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iwBvMZb" x1="5" x2="6.055" y1="23.9" y2="23.9" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="idR73sb" x1="27" x2="25.524" y1="24.837" y2="24.837" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><radialGradient id="idxNEqe" cx="0" cy="0" r="1" gradientTransform="matrix(2.80769 -1.3591 1.47615 3.04949 2.748 29.664)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="xomn_jqkl"/><stop offset="1" class="yvpae5bzc"/></radialGradient><radialGradient id="iH7kEqb" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.336 14.816)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="ff9bywbjm"/><stop offset=".927" class="bf-s3qwzt"/></radialGradient><radialGradient id="iEFRvje" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 29.764)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="nbncwobqn"/><stop offset=".988" class="n55x1ubvq"/></radialGradient><radialGradient id="ivLt2zO" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.563 10.944)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iEwIjic" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.129 10.68)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iMTCN3c" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.715 11.766)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iqqeVDp" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.757 10.944)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iKze3fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 15.685 10.745)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="ioqrGCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.335 9.672)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="id3rhEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.773 9.638)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iLU8HKd" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.149 7.348)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iXlqRJb" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 20.336 6.834)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iXKxUYd" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.692 5.073)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iVeWUiC" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.987 2.335)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="idjHAUY" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.532 9.16)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="imTbAQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.314 12.552)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iE3ID0w" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.168 10.261)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iQFt9ze" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.939 10.346)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivAnQod" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.8 10.262)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iN3uMDe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.916 -1.412)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibqe71c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 30.712)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="i2ot4bu" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.306)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><filter id="ipVz68b" width="3.542" height="3.342" x="9.563" y="9.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_877"/></filter><filter id="iMxSk0b" width="2.992" height="2.992" x="9.738" y="9.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".25"/></filter><filter id="i0iG5Ac" width="3.592" height="3.592" x="19.085" y="9.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_877"/></filter><filter id="ij7V4Ad" width="2.992" height="2.992" x="19.261" y="9.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".25"/></filter><filter id="isWLgfc" width="10.383" height="12.189" x="10.824" y="5.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_877"/></filter><filter id="i6ZMsqe" width="6.25" height="5.07" x="15.157" y="4.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".5"/></filter><filter id="iL9UEEO" width="12.614" height="8.551" x="9.68" y="1.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_877"/></filter><filter id="ifuSqJe" width="3.262" height="4.184" x="14.117" y="9.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".375"/></filter><filter id="id0Wzib" width="2.379" height="3.184" x="14.797" y="10.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".125"/></filter><filter id="iQZISic" width="2.982" height="1.874" x="17.17" y="7.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_877"/></filter><filter id="iJM9pme" width="2.982" height="1.874" x="12.017" y="7.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_877"/></filter><filter id="isvBTwd" width=".787" height=".697" x="17.433" y="9.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".05"/></filter><filter id="injwrpd" width=".892" height=".914" x="18.274" y="9.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".1"/></filter><filter id="in5dwnd" width=".987" height="1.041" x="13.828" y="9.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".1"/></filter><filter id="iIlBkwf" width=".914" height=".705" x="13.072" y="9.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".05"/></filter><filter id="ipAP5ld" width="2.701" height="1.281" x="17.224" y="7.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".15"/></filter><filter id="iOwS5JZ" width="2.779" height="1.339" x="11.999" y="7.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".15"/></filter><filter id="ijtJEoD" width="1.008" height="2.271" x="10.816" y="5.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_877" stdDeviation=".125"/></filter><filter id="iqTO2hd" width="22" height="14.1" x="5" y="15.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_877"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-technologist-dark" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.av9f1lb0o {
  d: path("m10.882 10.33l.05.003s-.055-.855-.108-1.442c0-.267.107-.587.322-.747l.161-.16c.268-.214.376-.534.376-.854v-.855a.52.52 0 0 1 .43-.533c.644-.16 1.986-.428 3.919-.428s3.275.267 3.92.428c.214.053.429.266.429.533v.855c0 .32.16.64.375.854c.503.352.472.546.43.96a45 45 0 0 0-.107 1.442h.018l-.266 3.962c-.161 1.771-1.553 3.006-3.214 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006z");
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b__p51-sk {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.604 10.659l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.bf-s3qwzt {
  stop-color: var(--svg-color--634d49, #634D49);
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ck7n5tgmp {
  d: path("M8.98 17.665a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.dbruw5zjj {
  d: path("M18.17 9.784a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.diccegtzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.377 9.512c.653 0 1.205.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e894g4uve {
  d: path("M29.938 29.665q.005-.08.005-.163a3.138 3.138 0 1 0-6.272.163z");
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eem5nwbbx {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.591 9.512c-.653 0-1.205.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.eq22whbkx {
  cx: 20.757px;
  cy: 10.944px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.eu7hrybov {
  stop-color: var(--svg-color--533e40, #533E40);
  stop-opacity: 0;
}

.f7dil5b8w {
  d: path("m15.604 10.659l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.377-.646-.377-.765 0");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.ff9bywbjm {
  stop-color: var(--svg-color--634d49, #634D49);
  stop-opacity: 0;
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gsb4pmijh {
  d: path("M16 15.165c-6.07 0-11 4.92-11 11v3.5h22v-3.5c0-6.08-4.93-11-11-11");
}

.gvmg8ob6v {
  d: path("M14.614 10.572c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hcrp-lnvr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.21 8.222l.002-.002l.005-.003l.011-.01a1.3 1.3 0 0 1 .155-.108c.1-.062.242-.14.42-.21a2.83 2.83 0 0 1 1.495-.159a.534.534 0 0 1-.167 1.055a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.3.16l-.008.006a.534.534 0 0 1-.68-.825");
}

.hzd4ywoql {
  d: path("M18.965 10.56a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.i04-0zb8e {
  cx: 13.529px;
  cy: 10.166px;
  rx: 0.39px;
  ry: 0.197px;
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jpgm3tbkg {
  cx: 20.756px;
  cy: 10.944px;
  r: 1.671px;
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.msex9gbuq {
  stop-color: var(--svg-color--533e40, #533E40);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n55x1ubvq {
  stop-color: var(--svg-color--533837, #533837);
  stop-opacity: 0;
}

.nbncwobqn {
  stop-color: var(--svg-color--6b5957, #6B5957);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nfhvlubqq {
  cx: 11.234px;
  cy: 10.944px;
  r: 1.671px;
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odcp9s_mm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.45 6.128v.899c-.008.149-.071.481-.259.622");
}

.ofy_3cbpe {
  d: path("M23 17.675v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.oov_job6w {
  d: path("m19.954 5.314l-3.08 1.027a1.048 1.048 0 0 0 .47 2.034l3.063-.41z");
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.px_us0b5s {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.81 4.46l.43.214c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.054.315-.261.526-.573.534h-.019s.054-.907.108-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.854c0-.267-.215-.481-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.747c.053.588.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qlm1ogbzf {
  fill: var(--svg-color--533836, #533836);
  d: path("M29.938 29.665q.005-.08.005-.163a3.138 3.138 0 1 0-6.272.163z");
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_673df_l {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.71 8.222l-.002-.001l-.001-.002l-.005-.003l-.012-.01a2 2 0 0 0-.155-.108c-.1-.062-.241-.14-.42-.21a2.84 2.84 0 0 0-1.494-.159a.534.534 0 1 0 .167 1.055c.398-.062.717.01.934.097a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .679-.825");
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.r3v8upbmw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.649 8.077c.43-.075 1.27-.054 1.851.398");
}

.rdu-6vuat {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.623 13.704c.394.206.864.323 1.364.323c.505 0 .97-.117 1.363-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .02.242m-2.989-.282l2.948.254m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.21.027l-.042-.027m.042.027l-.042-.027m.042.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.508-.92.846-1.584.846c-.666 0-1.25-.338-1.585-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.rlusx7b3t {
  d: path("M26.03 15.665H5.97a.97.97 0 0 0-.97.97v13.03h22v-13.03a.97.97 0 0 0-.97-.97");
}

.rojh-xb-t {
  d: path("m20.81 4.46l.43.214c.751.374 1.18 1.228 1.02 2.135l-.59 3.043c-.054.315-.261.526-.573.534h-.019s.054-.907.108-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.854c0-.267-.215-.481-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.747c.053.588.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.054 2.362.533l.806.801c.215.267.483.427.805.587");
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t058gv1zl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.424 8.596c.328-.29 1.043-.594 1.93-.453");
}

.t33_u7ubh {
  d: path("M8.329 29.665q.004-.08.004-.163a3.138 3.138 0 1 0-6.271.163z");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.uh1bc69mr {
  fill: var(--svg-color--000, #000);
  d: path("M17.658 10.678a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.vwpcicbfm {
  cx: 11.234px;
  cy: 10.944px;
  r: 0.996px;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x7nuoab2y {
  d: path("M13.799 9.784a.893.893 0 0 0-.861 1.129h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.xf3coib0e {
  cx: 13.529px;
  cy: 10.166px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.xomn_jqkl {
  stop-color: var(--svg-color--503c3b, #503C3B);
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xyaiqyb1d {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.104 9.973c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.36c.151-.112.325-.135.389-.05");
}

.y0-oorbyy {
  fill: var(--svg-color--000, #000);
  d: path("M14.31 10.678a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .061-.236");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yjh853bae {
  d: path("M18.104 9.973c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.36c.151-.112.325-.135.389-.05");
}

.ylwfifbow {
  cx: 20.757px;
  cy: 10.944px;
  r: 0.996px;
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yvpae5bzc {
  stop-color: var(--svg-color--3b2a28, #3B2A28);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.yze2dtm7a {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.711 10.822l-.821 1.701c-.102.35.142.7.489.7h.737c.346 0 .59-.355.489-.7l-.499-1.7c-.107-.378-.283-.378-.395 0");
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
