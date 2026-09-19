<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igtPXve)" class="m1i1rlbvk"/><g filter="url(#ieqNCeb)"><path class="xk18tyb3e"/></g><path class="zai0whbkr"/><path fill="url(#i4RHwye)" class="mp2n73xvx"/><path fill="url(#i86fP2c)" class="mp2n73xvx"/><path fill="url(#i23ntQe)" class="mp2n73xvx"/><path class="jse2phbtg"/><path fill="url(#i2nIhZb)" class="om0oq7b1v"/><path fill="url(#ivP9Jjb)" class="om0oq7b1v"/><path fill="url(#i77Ytid)" class="om0oq7b1v"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><path fill="url(#ijcUagb)" class="dvr2s59yl"/><path fill="url(#iDoneVc)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#i6G3R0c)" class="rom2yrbwh"/><g filter="url(#i2zGKNc)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#iEiPIoc)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#iM9apZd)"><path class="ss37frb2f"/></g><g filter="url(#i9oiqJe)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#ixaGDYd)" class="u1e8ikbzb"/></g><g filter="url(#i1cIf2c)"><path class="z5g21op2e"/></g><g filter="url(#iaqGLgc)"><path fill="url(#iYwEt7d)" class="pv8cx5b7o"/><path fill="url(#iMR6TEe)" class="pv8cx5b7o"/><path fill="url(#iM4MnPm)" class="pv8cx5b7o"/><path fill="url(#iT7ND8b)" class="pv8cx5b7o"/><path fill="url(#if0BDQe)" class="pv8cx5b7o"/></g><g filter="url(#iYfAr2d)"><path stroke="url(#iTqOeXb)" class="cjq4b16bn"/></g><g filter="url(#ivS0XJE)"><path stroke="url(#ipaGmae)" class="luyfkt2yj"/></g><g filter="url(#ievLvqc)"><path stroke="url(#isoouNc)" class="eqaszhbhb"/></g><g filter="url(#iq6Amkx)"><circle fill="url(#im24Z0c)" class="pg0bv5b8w"/><circle fill="url(#i2jQU2d)" class="pg0bv5b8w"/></g><g filter="url(#i9jweQb)"><circle class="s9ybl0bgd"/><circle fill="url(#iK0HMFb)" class="h12u57b7h"/><circle fill="url(#i0ZsX7y)" class="h12u57b7h"/></g><g filter="url(#iwcCfue)"><circle fill="url(#i3fi6jA)" class="def6hrb_v"/></g><g filter="url(#iMYFc6p)"><circle fill="url(#id4bpne)" class="byuwo1cmi"/></g><g filter="url(#iIALyzd)"><path fill="url(#i3RXzjy)" class="l5opnwo_v"/><path fill="url(#i5xHZtd)" class="l5opnwo_v"/><path fill="url(#iKGcanN)" class="l5opnwo_v"/><path fill="url(#iKlqowQ)" class="l5opnwo_v"/><path fill="url(#ibQvF7K)" class="l5opnwo_v"/><path fill="url(#iZ9oAkc)" class="l5opnwo_v"/><path fill="url(#i5gA4mv)" class="l5opnwo_v"/><path fill="url(#ikZcucc)" class="l5opnwo_v"/></g><g filter="url(#iF0Vane)"><path class="cy03tjbgk"/></g><g filter="url(#ik2o1qr)"><path class="d3n18lg2d"/><path fill="url(#i0T4uOe)" class="ru2-v-bir"/><path fill="url(#iEPpcXg)" class="ru2-v-bir"/><path fill="url(#iQgziTc)" class="ru2-v-bir"/><path fill="url(#iP9u85d)" class="ru2-v-bir"/><path fill="url(#ikGDl7t)" class="ru2-v-bir"/></g><path stroke="url(#i2mxLLd)" class="n08nfbigz"/><path class="fp6ketqsz"/><path fill="url(#ioUGptd)" class="j0c9wubzc"/><path class="kxq0a97mr"/><g filter="url(#io28npd)"><path class="u8y7qkbcb"/><path fill="url(#iGD1zUC)" class="ob019-k-z"/></g><g filter="url(#ikcbZSb)"><path fill="url(#iIRuJFc)" class="lr9_1kbyp"/></g><path class="d8n119bib"/><path fill="url(#iOvpvjK)" class="plzbs5b3z"/><path class="kvirybi5t"/><g filter="url(#ieocl9b)"><path fill="url(#iWwPm0b)" class="f5d-s7_vd"/></g><g filter="url(#iEIqZZc)"><ellipse transform="rotate(-27.914 13.238 10.294)" class="zgj-p7fcf"/><ellipse fill="url(#icLaZSd)" transform="rotate(-27.914 13.238 10.294)" class="aehqf9b1b"/></g><g filter="url(#i1YRdzc)"><path clip-rule="evenodd" class="wxhuuccmk"/></g><g filter="url(#iaMuU0b)"><path clip-rule="evenodd" class="iu_vgeb8h"/></g><path fill="url(#iSTZ2xM)" class="o-h13i3vo"/><path fill="url(#iC0oeWc)" class="mivm0cboq"/><g filter="url(#iryP5BO)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#iWabhiQ)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="i23ntQe" cx="0" cy="0" r="1" gradientTransform="rotate(135.74 4.223 11.079)scale(3.58199 4.84976)" gradientUnits="userSpaceOnUse"><stop class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="ijcUagb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7453 1.74043 -2.1505 -2.15651 27.338 23.373)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iDoneVc" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .3134 .41161 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="i6G3R0c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.553 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="ixaGDYd" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.839)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="iMR6TEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iM4MnPm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iT7ND8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="if0BDQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="i2jQU2d" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 27.02 -26.606)scale(1.02361 1.16832)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iK0HMFb" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.425 11.894)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="i0ZsX7y" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.466 11.073)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="i3fi6jA" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.273 11.072)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iKGcanN" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.6133 0 15.418 10.873)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iKlqowQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.60345 0 18.057 9.8)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="ibQvF7K" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.72401 0 13.514 9.766)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iZ9oAkc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.83177 -.68748 .40546 -1.6701 19.973 17.238)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="i5gA4mv" cx="0" cy="0" r="1" gradientTransform="rotate(132.936 8.646 8.205)scale(4.90874 6.54919)" gradientUnits="userSpaceOnUse"><stop class="zx2qd4bhl"/><stop offset="1" class="y7qcqib5l"/></radialGradient><radialGradient id="ikZcucc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.03125 -7.41394 0 15.793 7.069)" gradientUnits="userSpaceOnUse"><stop class="j-ef6wx1p"/><stop offset="1" class="esvo74b3k"/></radialGradient><radialGradient id="iP9u85d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.023 12.68)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="ioUGptd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.877 10.39)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iGD1zUC" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.65 10.474)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOvpvjK" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.51 10.39)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="icLaZSd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.834 -1.204)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><linearGradient id="igtPXve" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="hzctbo64o"/><stop offset="1" class="ncpoyrbpw"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="i2nIhZb" x1="19.937" x2="18.312" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="ivP9Jjb" x1="17" x2="17.937" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iYwEt7d" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iTqOeXb" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ipaGmae" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="isoouNc" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="im24Z0c" x1="21.553" x2="20.734" y1="9.98" y2="12.518" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="id4bpne" x1="10.944" x2="10.303" y1="11.351" y2="11.351" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="i3RXzjy" x1="19.741" x2="12.128" y1="11.462" y2="12.592" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="i5xHZtd" x1="10.34" x2="12.598" y1="14.161" y2="14.02" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="i0T4uOe" x1="14.831" x2="15.77" y1="12.122" y2="12.122" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iEPpcXg" x1="16.635" x2="15.609" y1="12.445" y2="12.43" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iQgziTc" x1="15.891" x2="15.891" y1="13.188" y2="12.614" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="ikGDl7t" x1="15.696" x2="15.696" y1="10.504" y2="11.632" gradientUnits="userSpaceOnUse"><stop class="qiq9pubtd"/><stop offset="1" class="ip7imhbjo"/></linearGradient><linearGradient id="i2mxLLd" x1="14.658" x2="15.093" y1="14.804" y2="14.116" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iIRuJFc" x1="18.655" x2="18.342" y1="10.444" y2="10.637" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWwPm0b" x1="14.254" x2="13.94" y1="10.444" y2="10.637" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSTZ2xM" x1="10.651" x2="10.158" y1="8.668" y2="8.668" gradientUnits="userSpaceOnUse"><stop class="gfuj0ibqm"/><stop offset="1" class="jhxo97b8s"/></linearGradient><linearGradient id="iC0oeWc" x1="20.833" x2="21.326" y1="8.668" y2="8.668" gradientUnits="userSpaceOnUse"><stop offset=".548" class="j9k2-bbvj"/><stop offset="1" class="mm0r6cb0n"/></linearGradient><filter id="ieqNCeb" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".5"/></filter><filter id="i2zGKNc" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1949"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1949" result="shape"/></filter><filter id="iEiPIoc" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="iM9apZd" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="i9oiqJe" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="i1cIf2c" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".325"/></filter><filter id="iaqGLgc" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="iYfAr2d" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".05"/></filter><filter id="ivS0XJE" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".05"/></filter><filter id="ievLvqc" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".05"/></filter><filter id="iq6Amkx" width="3.592" height="3.592" x="18.795" y="9.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="i9jweQb" width="2.992" height="2.992" x="18.97" y="9.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".25"/></filter><filter id="iwcCfue" width="3.542" height="3.342" x="9.273" y="9.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="iMYFc6p" width="2.992" height="2.992" x="9.448" y="9.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".25"/></filter><filter id="iIALyzd" width="10.433" height="12.3" x="10.577" y="5.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="iF0Vane" width="3.262" height="4.184" x="13.826" y="9.917" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".375"/></filter><filter id="ik2o1qr" width="2.379" height="3.184" x="14.507" y="10.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".125"/></filter><filter id="io28npd" width=".787" height=".697" x="17.142" y="9.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".05"/></filter><filter id="ikcbZSb" width=".892" height=".914" x="17.983" y="10.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".1"/></filter><filter id="ieocl9b" width=".987" height="1.041" x="13.537" y="9.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".1"/></filter><filter id="iEIqZZc" width=".914" height=".705" x="12.781" y="9.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1949" stdDeviation=".05"/></filter><filter id="i1YRdzc" width="2.854" height="1.798" x="16.961" y="7.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="iaMuU0b" width="2.854" height="1.798" x="11.827" y="7.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="iryP5BO" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter><filter id="iWabhiQ" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1949"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-mechanic-dark" /></template>
<style>
.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.aehqf9b1b {
  cx: 13.238px;
  cy: 10.294px;
  rx: 0.39px;
  ry: 0.197px;
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.byuwo1cmi {
  cx: 10.944px;
  cy: 11.072px;
  r: 0.996px;
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cjq4b16bn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 25.992H25.3");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cy03tjbgk {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.42 10.95l-.82 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.701c-.107-.377-.284-.377-.396 0");
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.d3n18lg2d {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.313 10.787l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.d8n119bib {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.3 9.64c-.653 0-1.205.45-1.355 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271A1.4 1.4 0 0 0 13.3 9.64");
}

.def6hrb_v {
  cx: 10.944px;
  cy: 11.072px;
  r: 1.671px;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.esvo74b3k {
  stop-color: var(--svg-color--2b1c2e, #2B1C2E);
  stop-opacity: 0;
}

.f5d-s7_vd {
  d: path("M14.324 10.7c0-.288-.235-.48-.298-.539l-.289.28l.178.361z");
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fp6ketqsz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.086 9.64c.654 0 1.206.451 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h12u57b7h {
  cx: 20.466px;
  cy: 11.072px;
  r: 0.996px;
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hzctbo64o {
  stop-color: var(--svg-color--d6c6ed, #D6C6ED);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.ip7imhbjo {
  stop-color: var(--svg-color--432c2e, #432C2E);
  stop-opacity: 0;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iu_vgeb8h {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M13.915 8.754c-.72-.067-1.183.214-1.295.317a.473.473 0 1 1-.64-.695c.306-.283 1.032-.656 2.023-.563a.473.473 0 1 1-.088.94");
}

.j-ef6wx1p {
  stop-color: var(--svg-color--2b1c2e, #2B1C2E);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j0c9wubzc {
  d: path("M17.88 9.912a.893.893 0 0 1 .86 1.129h-1.726a.897.897 0 0 1 .865-1.129");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j9k2-bbvj {
  stop-color: var(--svg-color--252224, #252224);
}

.jhxo97b8s {
  stop-color: var(--svg-color--463f3d, #463F3D);
}

.jse2phbtg {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.kvirybi5t {
  fill: var(--svg-color--000, #000);
  d: path("M14.02 10.806a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.kxq0a97mr {
  fill: var(--svg-color--000, #000);
  d: path("M17.368 10.805a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.236");
}

.l5opnwo_v {
  d: path("M10.577 8.878c0-.905.323-1.884.323-2.793c0-.908 8.518-1.148 9.813.14c.503.352.224 2.432.182 2.848c-.18 1.791-.234 3.606-.355 5.403c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.713 0-3.052-1.235-3.213-3.006c-.14-1.811-.323-3.78-.323-5.598");
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

.lr9_1kbyp {
  d: path("M18.675 10.688a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.m1cydckkt {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
  stop-opacity: 0;
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mivm0cboq {
  d: path("M21.325 9.608V7.264h-1.198c.048.139.199.47.425.69c.227.219.302.595.302.807l-.047 1.391c.268 0 .53-.222.518-.544");
}

.mm0r6cb0n {
  stop-color: var(--svg-color--5b5a5a, #5B5A5A);
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mp2n73xvx {
  d: path("M11.736 16.236v4.904c0 .434.418.668.813.38l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.609");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n08nfbigz {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.333 13.832c.393.205.863.323 1.363.323c.505 0 .97-.118 1.363-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .021.241m-2.99-.28l2.948.253m-2.947-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.027l-.041-.027m.041.027l-.041-.027m.041.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.508-.919.846-1.584.846s-1.25-.338-1.584-.846m-.042.027v.001l.042-.028m-.042.027l.042-.027");
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.ncpoyrbpw {
  stop-color: var(--svg-color--cdb2d2, #CDB2D2);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-h13i3vo {
  d: path("M10.16 9.608V7.264h1.196c-.047.139-.198.47-.425.69s-.302.595-.302.807v1.391c-.268 0-.482-.222-.47-.544");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.ob019-k-z {
  d: path("M17.813 10.101c.064.085-.069.189-.22.302s-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.om0oq7b1v {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.pg0bv5b8w {
  cx: 20.466px;
  cy: 11.072px;
  r: 1.671px;
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plzbs5b3z {
  d: path("M13.508 9.912a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pv8cx5b7o {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qiq9pubtd {
  stop-color: var(--svg-color--432c2e, #432C2E);
}

.qunsngokg {
  stop-color: var(--svg-color--7c6987, #7C6987);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.ru2-v-bir {
  d: path("m15.313 10.787l-.531 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.s9ybl0bgd {
  cx: 20.466px;
  cy: 11.072px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.ss37frb2f {
  fill: var(--svg-color--442133, #442133);
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.92c-.355 1.237-1.492 1.738-2.01 1.84");
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.u8y7qkbcb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.813 10.101c.064.085-.069.189-.22.302s-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.05");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.ul2cu2h0c {
  stop-color: var(--svg-color--f0e1ff, #F0E1FF);
  stop-opacity: 0;
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wxhuuccmk {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M17.478 8.754c.72-.067 1.182.214 1.294.317a.473.473 0 1 0 .64-.695c-.306-.283-1.032-.656-2.022-.563a.473.473 0 1 0 .087.94");
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xk18tyb3e {
  fill: var(--svg-color--caadc8, #CAADC8);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y7qcqib5l {
  stop-color: var(--svg-color--5a4340, #5A4340);
  stop-opacity: 0;
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zai0whbkr {
  fill: var(--svg-color--eddffd, #EDDFFD);
  d: path("M11.736 16.236v4.904c0 .434.418.668.813.38l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.609");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zgj-p7fcf {
  cx: 13.238px;
  cy: 10.294px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

.zx2qd4bhl {
  stop-color: var(--svg-color--5a4340, #5A4340);
}

</style>
