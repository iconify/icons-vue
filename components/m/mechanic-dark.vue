<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#im0wb4T)" class="m1i1rlbvk"/><g filter="url(#iH9voKe)"><path class="u7j5qywzc"/></g><path class="zai0whbkr"/><path fill="url(#i4RHwye)" class="mp2n73xvx"/><path fill="url(#i86fP2c)" class="mp2n73xvx"/><path fill="url(#iGxIi3d)" class="mp2n73xvx"/><path class="llp516bpm"/><path fill="url(#ioCT77d)" class="xn6dhjjio"/><path fill="url(#if8dKTc)" class="xn6dhjjio"/><path fill="url(#i77Ytid)" class="xn6dhjjio"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><path fill="url(#ijcUagb)" class="dvr2s59yl"/><path fill="url(#iDoneVc)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#ixge7fe)" class="rom2yrbwh"/><g filter="url(#ivDIpBe)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#iFWFsae)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#iesC2Kt)"><path class="edxb3ybgc"/></g><g filter="url(#ifexyrd)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#i9sxEsb)" class="u1e8ikbzb"/></g><g filter="url(#iLhzyUb)"><path class="z5g21op2e"/></g><g filter="url(#iESIRed)"><path fill="url(#iYwEt7d)" class="pimvl5kot"/><path fill="url(#iMR6TEe)" class="pimvl5kot"/><path fill="url(#iM4MnPm)" class="pimvl5kot"/><path fill="url(#iT7ND8b)" class="pimvl5kot"/><path fill="url(#if0BDQe)" class="pimvl5kot"/></g><g filter="url(#ireIz1k)"><path stroke="url(#iTqOeXb)" class="cjq4b16bn"/></g><g filter="url(#iQdtxdb)"><path stroke="url(#ipaGmae)" class="luyfkt2yj"/></g><g filter="url(#irhj61L)"><path stroke="url(#isoouNc)" class="eqaszhbhb"/></g><path fill="url(#ijuJNhe)" class="hzm2c3bha"/><path fill="url(#iNf0NTb)" class="m23nrebkr"/><path fill="url(#iLm9Wib)" class="d1nqo1ozq"/><path fill="url(#iVYRS4b)" class="gbm0j7buv"/><g filter="url(#ioLm9ec)"><path fill="url(#ixkVALd)" class="q8910qc9y"/></g><path fill="url(#iWbrcdc)" class="q8910qc9y"/><path fill="url(#iLl24Cb)" class="q8910qc9y"/><path fill="url(#iQT9v8b)" class="q8910qc9y"/><path fill="url(#iDU083b)" class="q8910qc9y"/><path fill="url(#ioySvUb)" class="q8910qc9y"/><path fill="url(#i1JcVne)" class="q8910qc9y"/><path fill="url(#iFbDbhc)" class="q8910qc9y"/><path fill="url(#iwM8iCc)" class="q8910qc9y"/><path fill="url(#iVBdlCb)" class="q8910qc9y"/><path fill="url(#iNKaP1c)" class="q8910qc9y"/><path fill="url(#iEYLWod)" class="q8910qc9y"/><g filter="url(#ihXQY9b)"><path class="jhsp6vb7h"/></g><g filter="url(#iPlTOQS)"><path class="e4czubdaz"/><path fill="url(#i70AJ0c)" class="pl8yez_4c"/><path fill="url(#ihDknte)" class="pl8yez_4c"/><path fill="url(#iDJCnRe)" class="pl8yez_4c"/><path fill="url(#i0xdgPe)" class="pl8yez_4c"/><path fill="url(#iWQ9myJ)" class="pl8yez_4c"/></g><g filter="url(#iY7pRgd)"><path stroke="url(#iXmzwyu)" class="e6qrk4bng"/></g><path fill="url(#iTKsYpb)" class="n1y6xablc"/><g filter="url(#iwLrbub)"><path class="b0m66ib8t"/></g><g filter="url(#i2zaA1d)"><path class="g7fwrrnhw"/></g><path class="kema50sgd"/><path fill="url(#ieh8BZc)" class="a6zw9sbfb"/><path class="t4zox_b8l"/><g filter="url(#iFnWvEd)"><path class="jsu2z0bfz"/><path fill="url(#i5Zd0MZ)" class="w63ac8ldj"/></g><g filter="url(#iqh35Ob)"><path fill="url(#iieRoec)" class="m3ayqbb7p"/></g><path class="kp8gu6pix"/><path fill="url(#ioPdWie)" class="a1bm_7bxi"/><path class="i9dyq3bii"/><g filter="url(#iz3ZSkd)"><path fill="url(#ibjYmcP)" class="y7cstgbaj"/></g><g filter="url(#iD758Gd)"><ellipse transform="rotate(-27.914 13.2 9.668)" class="xwhv343ph"/><ellipse fill="url(#iKFv6Pe)" transform="rotate(-27.914 13.2 9.668)" class="x8h5m09gp"/></g><path fill="url(#iJAwipe)" class="arfo26bqv"/><path fill="url(#ipMsI8c)" class="arfo26bqv"/><path fill="url(#iNsEzzc)" class="arfo26bqv"/><path fill="url(#iaq60Zb)" class="arfo26bqv"/><path fill="url(#iVO8yid)" class="ui9wfdvss"/><path fill="url(#iU3QHEc)" class="ui9wfdvss"/><g filter="url(#iHZXSDe)"><path fill="url(#iZzYe7b)" class="n0dg5ccxh"/></g><g filter="url(#idbizHb)"><path fill="url(#iKXJbOd)" class="vqqm1jjav"/></g><g filter="url(#imdJt0c)"><path class="ogijq9bup"/></g><g filter="url(#i5s2KRb)"><path class="e60pjifpz"/></g><g filter="url(#iYELuJe)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#infq4pe)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="iGxIi3d" cx="0" cy="0" r="1" gradientTransform="rotate(131.119 3.397 11.463)scale(2.81867 4.68292)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="ijcUagb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7453 1.74043 -2.1505 -2.15651 27.338 23.373)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iDoneVc" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .3134 .41161 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="ixge7fe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.554 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="i9sxEsb" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.838)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="iMR6TEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iM4MnPm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iT7ND8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="if0BDQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iLm9Wib" cx="0" cy="0" r="1" gradientTransform="matrix(.76433 2.06149 -2.44889 .90797 20.557 11.662)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iVYRS4b" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -34.87 37.11)scale(1.57981 4.87383)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="ixkVALd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.37627 0 0 -9.44013 18.596 10.7)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iLl24Cb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05124 12.6816 -10.57921 -.87696 17.334 4.665)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iQT9v8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17221 1.46143 0 18.225 9.36)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iDU083b" cx="0" cy="0" r="1" gradientTransform="rotate(-89.793 11.392 -1.991)scale(1.11702 1.22465)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="ioySvUb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.73718 .54755 -1.38845 -22.15514 19.238 11.71)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="i1JcVne" cx="0" cy="0" r="1" gradientTransform="matrix(4.18864 -2.7033 .9866 1.52868 10.085 6.286)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iFbDbhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.24132 2.54931 -1.02654 -.09717 21.41 7.723)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iwM8iCc" cx="0" cy="0" r="1" gradientTransform="rotate(121.348 7.524 7.922)scale(3.44586 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iEYLWod" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.19103 -5.25528 0 15.756 7.104)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="svlo6-b0u"/><stop offset="1" class="snclfibeh"/></radialGradient><radialGradient id="ihDknte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24917 -.78312 0 16.18 12.09)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="i0xdgPe" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.894 7.533)scale(1.70817 2.74517)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iTKsYpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.7357 2.95994 0 15.705 14.314)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="ieh8BZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82817 -1.3173 0 17.932 9.766)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i5Zd0MZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.23674 -.30507 .42 -.32593 17.7 9.852)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ioPdWie" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82822 -1.31737 0 13.477 9.766)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iKFv6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.0079 -.50435 .60625 -.0095 13.185 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipMsI8c" cx="0" cy="0" r="1" gradientTransform="matrix(.6416 2.28987 -2.18472 .61214 20.418 9.78)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iNsEzzc" cx="0" cy="0" r="1" gradientTransform="matrix(.80415 -1.10356 .925 .67403 20.786 10.336)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iaq60Zb" cx="0" cy="0" r="1" gradientTransform="matrix(.5992 -1.58263 2.1146 .8006 20.903 10.512)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iU3QHEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.42145 2.11915 -2.08332 -.41432 10.32 9.951)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iZzYe7b" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 4.89 5.673)scale(.9492 .41865)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><linearGradient id="im0wb4T" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="d__di5b1k"/><stop offset="1" class="ldn_ouzqy"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="ioCT77d" x1="19.938" x2="18.313" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="if8dKTc" x1="17" x2="17.938" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iYwEt7d" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iTqOeXb" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ipaGmae" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="isoouNc" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ijuJNhe" x1="10.427" x2="10.427" y1="7.621" y2="9.757" gradientUnits="userSpaceOnUse"><stop class="qi731gbjb"/><stop offset="1" class="zmama0ttw"/></linearGradient><linearGradient id="iNf0NTb" x1="20.983" x2="20.983" y1="7.446" y2="9.041" gradientUnits="userSpaceOnUse"><stop class="ty8nzq04x"/><stop offset="1" class="uf4kgmbxa"/></linearGradient><linearGradient id="iWbrcdc" x1="21.012" x2="16.535" y1="12.421" y2="12.421" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iVBdlCb" x1="15.757" x2="15.757" y1="17.083" y2="16.429" gradientUnits="userSpaceOnUse"><stop class="vyq0t1bed"/><stop offset="1" class="zhfu_nban"/></linearGradient><linearGradient id="iNKaP1c" x1="20.787" x2="20.404" y1="12.597" y2="12.573" gradientUnits="userSpaceOnUse"><stop class="vh02o1b7a"/><stop offset="1" class="at0fzabbu"/></linearGradient><linearGradient id="i70AJ0c" x1="16.561" x2="15.705" y1="11.39" y2="11.425" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iDJCnRe" x1="15.705" x2="15.705" y1="12.553" y2="12.078" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iWQ9myJ" x1="15.705" x2="15.705" y1="9.537" y2="10.559" gradientUnits="userSpaceOnUse"><stop class="z1zpvutiy"/><stop offset="1" class="aa0g1obge"/></linearGradient><linearGradient id="iXmzwyu" x1="14.478" x2="14.803" y1="14.156" y2="13.304" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iieRoec" x1="18.726" x2="18.406" y1="9.821" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibjYmcP" x1="14.237" x2="13.917" y1="9.821" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJAwipe" x1="22.275" x2="21.043" y1="9.848" y2="12.07" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iVO8yid" x1="9.722" x2="11.21" y1="10.567" y2="10.437" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iKXJbOd" x1="21.325" x2="21.325" y1="9.462" y2="11.405" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><filter id="iH9voKe" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".5"/></filter><filter id="ivDIpBe" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1947"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1947" result="shape"/></filter><filter id="iFWFsae" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/></filter><filter id="iesC2Kt" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0627451 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/></filter><filter id="ifexyrd" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/></filter><filter id="iLhzyUb" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".325"/></filter><filter id="iESIRed" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/></filter><filter id="ireIz1k" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".05"/></filter><filter id="iQdtxdb" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".05"/></filter><filter id="irhj61L" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".05"/></filter><filter id="ioLm9ec" width="11.511" height="12.798" x="10.501" y="4.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1947" result="effect2_innerShadow_4002_1947"/></filter><filter id="ihXQY9b" width="3.916" height="4.96" x="13.535" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".5"/></filter><filter id="iPlTOQS" width="2.316" height="3.36" x="14.547" y="9.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".1"/></filter><filter id="iY7pRgd" width="3.685" height="1.495" x="13.862" y="13.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".05"/></filter><filter id="iwLrbub" width="2.385" height="1.211" x="17.327" y="7.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/></filter><filter id="i2zaA1d" width="2.385" height="1.196" x="11.961" y="7.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/></filter><filter id="iFnWvEd" width=".799" height=".707" x="17.185" y="9.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".05"/></filter><filter id="iqh35Ob" width=".901" height=".924" x="18.044" y="9.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".1"/></filter><filter id="iz3ZSkd" width=".999" height="1.054" x="13.509" y="9.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".1"/></filter><filter id="iD758Gd" width=".928" height=".715" x="12.737" y="9.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".05"/></filter><filter id="iHZXSDe" width="1.346" height="2.418" x="9.482" y="9.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".125"/></filter><filter id="idbizHb" width="1.966" height="2.943" x="20.342" y="8.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".25"/></filter><filter id="imdJt0c" width="2.44" height="1.169" x="11.886" y="7.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".125"/></filter><filter id="i5s2KRb" width="2.44" height="1.178" x="17.275" y="7.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1947" stdDeviation=".125"/></filter><filter id="iYELuJe" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/></filter><filter id="infq4pe" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1947"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mechanic-dark" /></template>
<style>
.a1bm_7bxi {
  d: path("M13.475 9.279a.91.91 0 0 0-.877 1.151h1.76a1 1 0 0 0 .033-.24a.917.917 0 0 0-.916-.911");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a6zw9sbfb {
  d: path("M17.934 9.279a.91.91 0 0 1 .878 1.151h-1.76a.915.915 0 0 1 .882-1.151");
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.aa0g1obge {
  stop-color: var(--svg-color--39262f, #39262F);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.arfo26bqv {
  d: path("M20.729 12.07c.067-1.087.119-2.161.197-3.247a1.624 1.624 0 0 1 1.349 1.607c0 .875-.684 1.59-1.546 1.64");
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.at0fzabbu {
  stop-color: var(--svg-color--6c5c5a, #6C5C5A);
  stop-opacity: 0;
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b0m66ib8t {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.515 7.93a1.9 1.9 0 0 0-.701-.42c-.311-.098-.7-.125-1.238-.059a.283.283 0 1 0 .069.562c.49-.06.792-.029.999.036c.202.064.339.167.5.307a.283.283 0 0 0 .371-.427");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
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

.d__di5b1k {
  stop-color: var(--svg-color--d2c4ec, #D2C4EC);
}

.d1nqo1ozq {
  d: path("M20.667 11.977a1.67 1.67 0 0 0 .923-.315v.95c0 .912-.543 1.724-1.368 2.061q.262-.556.353-1.204z");
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4czubdaz {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.315 9.971l-.543 1.877c-.11.386.155.772.531.772h.803c.377 0 .642-.392.532-.772l-.543-1.877c-.116-.415-.659-.415-.78 0");
}

.e60pjifpz {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.34 8.056c-.288-.303-.916-.519-1.69-.389");
}

.e6qrk4bng {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.314 13.278c.402.21.88.33 1.39.33c.516 0 .99-.12 1.392-.33a.21.21 0 0 1 .246.04a.19.19 0 0 1 .02.245m-3.048-.285l3.007.258m-3.007-.258a.21.21 0 0 0-.246.042a.19.19 0 0 0-.02.244m.266-.286l-.225.258m3.274.027l-.042-.027m.042.027l-.042-.027m.042.027a1.98 1.98 0 0 1-1.658.886a1.98 1.98 0 0 1-1.658-.885m3.274-.028a1.93 1.93 0 0 1-1.616.864a1.93 1.93 0 0 1-1.616-.864m-.042.028l.042-.028m-.042.028l.042-.028");
}

.edxb3ybgc {
  fill: var(--svg-color--472337, #472337);
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.921c-.356 1.237-1.494 1.738-2.012 1.84");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g7fwrrnhw {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.223 7.81a2.83 2.83 0 0 1 1.775-.367a.283.283 0 0 1-.069.563a2.27 2.27 0 0 0-1.415.29a1 1 0 0 0-.094.061l-.003.002a.283.283 0 0 1-.346-.447z");
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gbm0j7buv {
  d: path("M10.743 11.977a1.67 1.67 0 0 1-.924-.315v.95c0 .912.543 1.724 1.369 2.061a4.2 4.2 0 0 1-.353-1.204z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
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

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hzm2c3bha {
  d: path("M10.2 7.095h.716v2.662h-.98z");
}

.i9dyq3bii {
  fill: var(--svg-color--000, #000);
  d: path("M13.997 10.19a.52.52 0 0 0-.522-.522a.52.52 0 0 0-.463.762h.923a.5.5 0 0 0 .062-.24");
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.jhsp6vb7h {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.209 10.171l-.649 1.877c-.11.386.155.772.532.772h.803c.376 0 .642-.392.531-.772l-.542-1.877c-.117-.415-.554-.415-.675 0");
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jsu2z0bfz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.867 9.471c.065.087-.07.193-.225.308c-.154.116-.268.197-.333.11s.007-.25.162-.366c.154-.115.331-.138.396-.052");
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kema50sgd {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.146 9.001c.666 0 1.23.46 1.383 1.081a.28.28 0 0 1-.274.348h-2.277a.235.235 0 0 1-.232-.278a1.43 1.43 0 0 1 1.4-1.15");
}

.kp8gu6pix {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.264 9.001c-.666 0-1.23.46-1.383 1.081a.28.28 0 0 0 .274.348h2.277a.235.235 0 0 0 .232-.278a1.43 1.43 0 0 0-1.4-1.15");
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.ldn_ouzqy {
  stop-color: var(--svg-color--c6c4d3, #C6C4D3);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llp516bpm {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m1cydckkt {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
  stop-opacity: 0;
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m23nrebkr {
  d: path("M20.493 7.095h.804l.176 2.662h-.98z");
}

.m3ayqbb7p {
  d: path("M18.746 10.07a.86.86 0 0 0-.236-.473l-.266.292l.12.232z");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mp2n73xvx {
  d: path("M11.736 16.236v4.904c0 .434.418.668.813.38l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.609");
}

.n0dg5ccxh {
  d: path("M10.493 9.478a.976.976 0 0 0 .085 1.919a79 79 0 0 1-.085-1.919");
}

.n1y6xablc {
  d: path("M15.705 13.658a3.1 3.1 0 0 1-1.414-.335c-.14-.072-.29.086-.202.213c.341.518.937.864 1.616.864c.678 0 1.274-.346 1.616-.864c.088-.132-.062-.285-.202-.213c-.41.213-.891.335-1.414.335");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
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

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogijq9bup {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.262 8.096c.262-.188.916-.52 1.69-.39");
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pimvl5kot {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl8yez_4c {
  d: path("m15.315 9.971l-.543 1.877c-.11.386.155.772.531.772h.803c.377 0 .642-.392.532-.772l-.543-1.877c-.116-.415-.659-.415-.78 0");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q8910qc9y {
  d: path("M10.78 13.523A4 4 0 0 0 14.746 17h1.926a4 4 0 0 0 3.966-3.477c.12-1.923.284-4.479.374-6.4c-.011-.783-.67-.788-1.45-.821h-1.43a2.47 2.47 0 0 1-2.257-1.473a.68.68 0 0 0-.628-.427h-1.3c-1.884 0-3.446.815-3.446 2.72c0 1.9.154 4.497.279 6.401");
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qi731gbjb {
  stop-color: var(--svg-color--282121, #282121);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
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

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.snclfibeh {
  stop-color: var(--svg-color--2c1c2d, #2C1C2D);
  stop-opacity: 0;
}

.svlo6-b0u {
  stop-color: var(--svg-color--2c1c2d, #2C1C2D);
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t4zox_b8l {
  fill: var(--svg-color--000, #000);
  d: path("M17.413 10.19a.52.52 0 0 1 .521-.522a.52.52 0 0 1 .464.762h-.923a.5.5 0 0 1-.062-.24");
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.ty8nzq04x {
  stop-color: var(--svg-color--373032, #373032);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.u7j5qywzc {
  fill: var(--svg-color--b1a1bf, #B1A1BF);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.uf4kgmbxa {
  stop-color: var(--svg-color--271d21, #271D21);
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.ui9wfdvss {
  d: path("M10.534 8.804a1.64 1.64 0 0 0-1.41 1.626c0 .877.702 1.588 1.567 1.635c-.043-1.09-.136-2.17-.157-3.261");
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

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vh02o1b7a {
  stop-color: var(--svg-color--6c5c5a, #6C5C5A);
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.vqqm1jjav {
  d: path("M20.842 11.405q.06-.972.113-1.943a.975.975 0 0 1-.113 1.943");
}

.vyq0t1bed {
  stop-color: var(--svg-color--411b43, #411B43);
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w63ac8ldj {
  d: path("M17.867 9.471c.065.087-.07.193-.225.308c-.154.116-.268.197-.333.11s.007-.25.162-.366c.154-.115.331-.138.396-.052");
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x8h5m09gp {
  cx: 13.201px;
  cy: 9.668px;
  rx: 0.398px;
  ry: 0.201px;
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xn6dhjjio {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.xwhv343ph {
  cx: 13.201px;
  cy: 9.668px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.201px;
}

.y7cstgbaj {
  d: path("M14.308 10.083c0-.295-.24-.491-.304-.55l-.295.284l.181.37z");
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z1zpvutiy {
  stop-color: var(--svg-color--39262f, #39262F);
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
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

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zhfu_nban {
  stop-color: var(--svg-color--411b43, #411B43);
  stop-opacity: 0;
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zmama0ttw {
  stop-color: var(--svg-color--46403d, #46403D);
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
