<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iMRzmDc)"><path fill="url(#iq7sHCb)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#ic8tonb)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#i3RQFfc)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#imj4URc)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iMLCjTd)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#igBwHHe)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#i26QoRF)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iUcvsyd)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#i2GYrcb)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#iTBp8Bs)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#ieHP5yd)" clip-rule="evenodd" class="zm9zkcl5b"/><path fill="url(#igMUT6d)" clip-rule="evenodd" class="zm9zkcl5b"/></g><path class="uzvwpqz1p"/><path class="usmnphbrw"/><g filter="url(#iHhiHvb)"><path class="dijt3iwmx"/><path fill="url(#ibfnKEe)" class="o_hp5nbjg"/></g><path class="wznkn9tzm"/><path fill="url(#iJLE8ye)" class="o93ji_bej"/><path fill="url(#iZ0eGke)" class="o93ji_bej"/><g filter="url(#ioWJ6Ly)"><path class="b5au3h6bl"/></g><path class="pu1qalb0n"/><path fill="url(#ieyaRhd)" class="pcr8w9bct"/><path fill="url(#i9fb3ne)" class="pcr8w9bct"/><path fill="url(#iek6ihd)" class="pcr8w9bct"/><path fill="url(#izgSJzU)" class="pcr8w9bct"/><path class="myif5tbjr"/><path fill="url(#iNC83fb)" class="u1ssmd66p"/><path fill="url(#iBwD5cu)" class="u1ssmd66p"/><g filter="url(#icwVyUb)"><path class="xqme1t_en"/></g><path fill="url(#icWbAmd)" class="cge-036tr"/><path fill="url(#iJO9Dac)" class="cge-036tr"/><path fill="url(#iApyzzd)" class="cge-036tr"/><path fill="url(#ivzWvsb)" class="cge-036tr"/><g filter="url(#ibAWpil)"><path fill="url(#iCEVb2b)" class="qr3eebgfz"/><path fill="url(#iS5fSJc)" class="qr3eebgfz"/></g><path fill="url(#iO1McLA)" class="qr3eebgfz"/><path fill="url(#iIFRdJe)" class="qr3eebgfz"/><path fill="url(#iXG18Rd)" class="i0vp1so6w"/><path fill="url(#i4zfwum)" class="i0vp1so6w"/><g filter="url(#iQ9Hrlb)"><path class="ise8hkbqb"/></g><path fill="url(#iiFwxIb)" class="ukvj5-vlj"/><path fill="url(#iNo9Upb)" class="ukvj5-vlj"/><g filter="url(#iIobive)"><path class="hm4ptbkef"/></g><path fill="url(#imXX7Fy)" class="r7p4z7bsm"/><path fill="url(#iFVyysb)" class="d8xf2ibmq"/><g filter="url(#ipecNtc)"><path fill="url(#i7arbsW)" class="qrmj1y8xw"/></g><path fill="url(#iJ1vqFe)" class="qrmj1y8xw"/><g filter="url(#iE4RtRc)"><path fill="url(#imqsose)" class="ymsp3kbav"/><path fill="url(#iqB9NwX)" class="ymsp3kbav"/></g><g filter="url(#i5vBH6d)"><path class="rmne4ubxs"/><path fill="url(#ipahrre)" class="ojwkb-b4s"/></g><g filter="url(#ijjRqfe)"><path class="now9rmbjg"/><path fill="url(#it7P5Od)" class="zjcs0bbar"/></g><g filter="url(#iRKGOKs)"><path fill="url(#iqSD2rc)" class="j1j51bc4m"/><path fill="url(#ifUKNAb)" class="j1j51bc4m"/><path fill="url(#iVSJWje)" class="j1j51bc4m"/><path fill="url(#i44d3Uc)" class="j1j51bc4m"/><path fill="url(#is8eLAd)" class="j1j51bc4m"/><path fill="url(#i3E7app)" class="j1j51bc4m"/><path fill="url(#ihoxicd)" class="j1j51bc4m"/><path fill="url(#iszPaWd)" class="j1j51bc4m"/></g><path fill="url(#imZHKTb)" class="j1j51bc4m"/><g filter="url(#iPSJPfe)"><path class="cfbaygb8k"/></g><g filter="url(#iPcGMOb)"><path class="djps4rb_t"/><path fill="url(#iA1Ydoe)" class="xc4tawbvb"/><path fill="url(#ikoIrGq)" class="xc4tawbvb"/><path fill="url(#iBt6Ajd)" class="xc4tawbvb"/><path fill="url(#iSZED7L)" class="xc4tawbvb"/></g><g filter="url(#ijD1Gcc)"><path stroke="url(#iMwdn3d)" class="qe-nmobot"/></g><path class="ikpy-qbyu"/><g filter="url(#iyVEjmM)"><path class="geoo1pnos"/></g><g filter="url(#i0dVYPd)"><path class="h3y0xybwn"/></g><g filter="url(#ivlki2b)"><path class="jtspvdbwc"/></g><g filter="url(#idS4Q2c)"><path clip-rule="evenodd" class="ni4u1bbhm"/></g><path class="nv-tm3b_c"/><path fill="url(#ivy8uXd)" class="r0w13r7uj"/><path class="umgvlrbgn"/><g filter="url(#iGBVzpe)"><path class="bmuzas5gv"/><path fill="url(#iSxL7AH)" class="ffhuevyci"/></g><g filter="url(#iP2Uxmd)"><path fill="url(#iGh2oyc)" class="vy3y1vbex"/></g><path class="hil4-np7l"/><path fill="url(#izqF4vd)" class="t_70vht6h"/><path class="q3bc6bbmg"/><g filter="url(#i2rDmYb)"><path fill="url(#icnlnye)" class="tkifgyigj"/></g><g filter="url(#iFNsm2b)"><ellipse transform="rotate(-27.914 14.922 5.528)" class="u-feptipi"/><ellipse fill="url(#i8RfYrc)" transform="rotate(-27.914 14.922 5.528)" class="bmn6q0bjm"/></g><g filter="url(#iGrW4bb)"><path class="bh8f0fvkc"/><path fill="url(#ibdx49c)" class="jimqrcckc"/><path fill="url(#i8xkK6d)" class="jimqrcckc"/></g><g filter="url(#iEKXxpd)"><path class="t7iga1bol"/><path fill="url(#inSxVMk)" class="d98v_ccwx"/><path fill="url(#iOutZ2c)" class="d98v_ccwx"/></g><g filter="url(#irwA4je)"><path class="jjkdnok3l"/></g><defs><radialGradient id="ic8tonb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26505 2.0026 -2.50165 -.3311 15.868 6.931)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="i3RQFfc" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 6.238 5.76)scale(1.52746 2.00696)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="imj4URc" cx="0" cy="0" r="1" gradientTransform="matrix(-.57427 .75098 -.57664 -.44096 13.873 5.93)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iMLCjTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.56692 .92768 -.65346 -.39934 14.071 5.039)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="igBwHHe" cx="0" cy="0" r="1" gradientTransform="matrix(.60373 1.14855 -1.59437 .83807 14.454 2.293)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i26QoRF" cx="0" cy="0" r="1" gradientTransform="matrix(-.63314 .63318 -.88485 -.8848 18.562 3.206)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iUcvsyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.80984 .23559 -.4913 -1.68887 19.298 5.458)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="i2GYrcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23686 .30923 -.39392 -1.57558 19.033 6.96)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iTBp8Bs" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 10.61 -4.272)scale(1.23007 .97291)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="ieHP5yd" cx="0" cy="0" r="1" gradientTransform="matrix(.6606 .0693 -.11228 1.07037 13.302 5.443)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="igMUT6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.36812 -1.62712 .58726 -.13286 18.246 5.157)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="ibfnKEe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.482)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="zay0pib-e"/><stop offset="1" class="f283vybwl"/></radialGradient><radialGradient id="iJLE8ye" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.482)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="nrk1uwb9l"/><stop offset="1" class="jewrngbdz"/></radialGradient><radialGradient id="iZ0eGke" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 -.5625 .3991 .13026 19.319 18.877)" gradientUnits="userSpaceOnUse"><stop class="w48qw8bka"/><stop offset="1" class="q7l1h8mqg"/></radialGradient><radialGradient id="ieyaRhd" cx="0" cy="0" r="1" gradientTransform="rotate(107.067 2.409 10.603)scale(1.86331 .9169)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="mwlubcb3u"/><stop offset="1" class="sf6dqgv3q"/></radialGradient><radialGradient id="i9fb3ne" cx="0" cy="0" r="1" gradientTransform="matrix(-3.84619 0 0 -3.93164 15.377 12.374)" gradientUnits="userSpaceOnUse"><stop offset=".865" class="k359d0bjg"/><stop offset="1" class="zqan0v-dy"/></radialGradient><radialGradient id="iek6ihd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.683)" gradientUnits="userSpaceOnUse"><stop class="b9nndyb1o"/><stop offset="1" class="aslchbbcc"/></radialGradient><radialGradient id="iNC83fb" cx="0" cy="0" r="1" gradientTransform="matrix(1.08228 -.29102 1.20718 4.48944 18.794 11.828)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="a76ibt5dn"/><stop offset="1" class="s61flvbkc"/></radialGradient><radialGradient id="iJO9Dac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 17.953)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="iApyzzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.075 28.316)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="ivzWvsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.406)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iS5fSJc" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.454 8.152)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="elt890uby"/><stop offset="1" class="r2rrbr4ji"/></radialGradient><radialGradient id="iIFRdJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.92188 -7.88477 10.52054 -1.23005 16.423 15.796)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="kqc1q6b3u"/><stop offset=".967" class="dpe-7hbaw"/></radialGradient><radialGradient id="iXG18Rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11133 -1.40894 0 16 8.337)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="bwhjsl3pz"/><stop offset="1" class="mszjt37ue"/></radialGradient><radialGradient id="i4zfwum" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89844 -.2837 0 15.129 8.138)" gradientUnits="userSpaceOnUse"><stop class="cdcyp1bih"/><stop offset="1" class="tcfzn_bju"/></radialGradient><radialGradient id="iNo9Upb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.264)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="iJ1vqFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.28714 -.52863 .599 -.32537 13.769 6.54)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="imqsose" cx="0" cy="0" r="1" gradientTransform="matrix(1.09333 -.49697 .60678 1.3349 17.774 6.025)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iqB9NwX" cx="0" cy="0" r="1" gradientTransform="matrix(.5301 0 0 .22824 18.172 5.083)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="ipahrre" cx="0" cy="0" r="1" gradientTransform="matrix(.66323 -.04933 .03857 .51846 17.93 5.882)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="it7P5Od" cx="0" cy="0" r="1" gradientTransform="rotate(-179.832 6.99 2.916)scale(.46384)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iqSD2rc" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.014 4.692)scale(3.14584 4.21065)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="ifUKNAb" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.805 4.759)scale(1.04632 .72864)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iVSJWje" cx="0" cy="0" r="1" gradientTransform="matrix(.56627 -1.72556 2.18941 .71849 15.05 8.455)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i44d3Uc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.89504 -3.61876 0 16 5.711)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="a-xgu9mrq"/><stop offset="1" class="hk_5_2bqz"/></radialGradient><radialGradient id="is8eLAd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03335 .59528 -1.0249 -5.2225 16.795 6.357)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="i3E7app" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50548 .62037 0 17.01 5.412)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="ihoxicd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57653 .66074 0 15.088 5.312)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iszPaWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.38222 1.41737 -1.13413 -.30584 16.608 4.395)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="imZHKTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.56457 0 0 -2.83125 18.238 6.066)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iA1Ydoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2001 -.89784 .2767 -.06167 16.345 6.385)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iSZED7L" cx="0" cy="0" r="1" gradientTransform="matrix(-.34236 0 0 -.09571 16.24 6.478)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="ivy8uXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35637 -.56685 0 16.958 5.57)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iSxL7AH" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 9.802 -1.325)scale(.16616 .22877)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izqF4vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35638 -.56686 0 15.042 5.57)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i8RfYrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0034 -.21702 .26087 -.00408 14.916 5.666)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibdx49c" cx="0" cy="0" r="1" gradientTransform="matrix(.55435 -1.21034 .61918 .2836 13.515 4.639)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="i8xkK6d" cx="0" cy="0" r="1" gradientTransform="matrix(.50494 -.86764 .4658 .27108 14.265 4.208)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="inSxVMk" cx="0" cy="0" r="1" gradientTransform="matrix(-.92769 1.92897 -3.15375 -1.51671 16.84 2.351)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iOutZ2c" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 6.968 8.16)scale(.60762 1.30724)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="iMRzmDc" width="6.847" height="7.347" x="12.702" y="1.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="iHhiHvb" width="2.311" height="8.028" x="11.403" y="12.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.505882 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="ioWJ6Ly" width="1.437" height="7.032" x="19.118" y="11.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".25"/></filter><filter id="icwVyUb" width="6.169" height="12.453" x="13.016" y="15.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="ibAWpil" width="6.517" height="7.694" x="12.941" y="8.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="iQ9Hrlb" width="3.316" height="1.848" x="12.434" y="28.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="iIobive" width="6.594" height="13.766" x="12.841" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".5"/></filter><filter id="ipecNtc" width="1.564" height="1.414" x="13.235" y="5.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="iE4RtRc" width="1.414" height="1.664" x="17.414" y="4.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="i5vBH6d" width="1.944" height="1.944" x="17.149" y="4.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".25"/></filter><filter id="ijjRqfe" width="1.644" height="1.644" x="13.129" y="5.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".175"/></filter><filter id="iRKGOKs" width="4.476" height="4.878" x="13.762" y="3.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="iPSJPfe" width="1.825" height="2.178" x="15.016" y="5.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".25"/></filter><filter id="iPcGMOb" width="1.025" height="1.378" x="15.488" y="5.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".05"/></filter><filter id="ijD1Gcc" width="1.751" height=".795" x="15.125" y="6.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".05"/></filter><filter id="iyVEjmM" width="1.431" height=".565" x="16.302" y="5.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="i0dVYPd" width="1.431" height=".565" x="14.268" y="5.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="ivlki2b" width="1.19" height=".591" x="14.327" y="4.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="idS4Q2c" width="1.19" height=".591" x="16.707" y="4.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/></filter><filter id="iGBVzpe" width=".458" height=".418" x="16.58" y="5.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".05"/></filter><filter id="iP2Uxmd" width=".616" height=".625" x="16.893" y="5.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".1"/></filter><filter id="i2rDmYb" width=".658" height=".681" x="14.941" y="5.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".1"/></filter><filter id="iFNsm2b" width=".513" height=".422" x="14.666" y="5.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".05"/></filter><filter id="iGrW4bb" width="2.199" height="2.331" x="13.184" y="2.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/><feGaussianBlur result="effect2_foregroundBlur_4002_177" stdDeviation=".1"/></filter><filter id="iEKXxpd" width="4.01" height="2.62" x="14.439" y="2.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_177"/><feGaussianBlur result="effect2_foregroundBlur_4002_177" stdDeviation=".05"/></filter><filter id="irwA4je" width="2.664" height="1.322" x="15.824" y="3.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_177" stdDeviation=".125"/></filter><linearGradient id="iq7sHCb" x1="18.062" x2="15.367" y1="2.779" y2="7.505" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="izgSJzU" x1="12.466" x2="12.466" y1="12.632" y2="12.474" gradientUnits="userSpaceOnUse"><stop class="d8l0ribxz"/><stop offset="1" class="sgj6b5b-t"/></linearGradient><linearGradient id="iBwD5cu" x1="19.747" x2="19.747" y1="12.632" y2="12.394" gradientUnits="userSpaceOnUse"><stop class="w2wdskbew"/><stop offset="1" class="lj8hkjeee"/></linearGradient><linearGradient id="icWbAmd" x1="16" x2="16" y1="15.863" y2="16.296" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="iCEVb2b" x1="16" x2="16" y1="8.953" y2="15.914" gradientUnits="userSpaceOnUse"><stop class="qb52yacny"/><stop offset="1" class="k3iqnbc3x"/></linearGradient><linearGradient id="iO1McLA" x1="17.173" x2="17.173" y1="15.914" y2="15.654" gradientUnits="userSpaceOnUse"><stop offset=".068" class="d10os3b5g"/><stop offset="1" class="tfix0o_9x"/></linearGradient><linearGradient id="iiFwxIb" x1="18.247" x2="16.5" y1="29.578" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="imXX7Fy" x1="12.866" x2="19.137" y1="7.821" y2="7.821" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iFVyysb" x1="12.866" x2="19.137" y1="7.807" y2="7.807" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i7arbsW" x1="13.235" x2="14.051" y1="5.871" y2="5.871" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="ikoIrGq" x1="15.588" x2="16" y1="6.417" y2="6.417" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iBt6Ajd" x1="16" x2="16" y1="6.728" y2="6.452" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iMwdn3d" x1="15.532" x2="15.735" y1="7.387" y2="7.074" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iGh2oyc" x1="17.3" x2="17.162" y1="5.594" y2="5.679" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icnlnye" x1="15.368" x2="15.23" y1="5.594" y2="5.679" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-standing-medium" /></template>
<style>
.a-xgu9mrq {
  stop-color: var(--svg-color--a47373, #A47373);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a76ibt5dn {
  stop-color: var(--svg-color--624da1, #624DA1);
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.aslchbbcc {
  stop-color: var(--svg-color--5e4f7e, #5E4F7E);
  stop-opacity: 0;
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b5au3h6bl {
  stroke: var(--svg-color--bd8a7d, #BD8A7D);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.767 12.193c.104 1.156.25 3.975 0 6");
}

.b9nndyb1o {
  stop-color: var(--svg-color--5e4f7e, #5E4F7E);
}

.bh8f0fvkc {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M13.773 3.202c.249-.263.72-.264.936-.224l.174.567c-.11-.018-.13-.001-.213.08c-.06.48-.604.771-1.268.965c-.065-.655.048-1.045.371-1.388");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bmn6q0bjm {
  cx: 14.922px;
  cy: 5.528px;
  rx: 0.171px;
  ry: 0.087px;
}

.bmuzas5gv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.93 5.443c.029.038-.03.083-.096.133c-.067.05-.116.085-.144.047c-.028-.037.003-.108.07-.157c.066-.05.143-.06.17-.023");
}

.bwhjsl3pz {
  stop-color: var(--svg-color--a17076, #A17076);
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.cdcyp1bih {
  stop-color: var(--svg-color--9a706a, #9A706A);
}

.cfbaygb8k {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.828 5.735l-.3.746a.237.237 0 0 0 .228.307h.345a.238.238 0 0 0 .23-.307l-.234-.746c-.05-.166-.217-.166-.27 0");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.cge-036tr {
  d: path("m13.016 15.863l.484 12.453h2l.238-9.523c0-.329.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.d10os3b5g {
  stop-color: var(--svg-color--614699, #614699);
}

.d8l0ribxz {
  stop-color: var(--svg-color--482f7c, #482F7C);
}

.d8xf2ibmq {
  d: path("M16.01 7.808h-.017c.044 0 .083 0 .127.004q-.054-.005-.11-.004");
}

.d98v_ccwx {
  d: path("M15.735 2.41c-.498-.11-.944.387-.996.57c.462 1.558 1.631 1.473 2.785 1.345c.69-.077.766.238.825.39c0-1.728-1.47-2.052-2.602-2.302z");
}

.dijt3iwmx {
  fill: var(--svg-color--996a67, #996A67);
  d: path("M12.112 20.292c-.938-1.982-.769-6.259-.488-7.824h1.672c-.071 2.426.04 5.243.178 6.512c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.202c.061.299.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.djps4rb_t {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.832 5.674l-.233.746a.237.237 0 0 0 .228.308h.346a.238.238 0 0 0 .228-.308l-.233-.746c-.05-.166-.284-.166-.336 0");
}

.dpe-7hbaw {
  stop-color: var(--svg-color--271a45, #271A45);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.elt890uby {
  stop-color: var(--svg-color--9e85d7, #9E85D7);
}

.f283vybwl {
  stop-color: var(--svg-color--8d434a, #8D434A);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.ffhuevyci {
  d: path("M16.93 5.443c.029.038-.03.083-.096.133c-.067.05-.116.085-.144.047c-.028-.037.003-.108.07-.157c.066-.05.143-.06.17-.023");
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.geoo1pnos {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M16.502 5.582c.116-.205.294-.367.675-.367c.167 0 .328.047.471.162c.118.096.102.218.011.264l-.244.14c-.287-.093-.603-.106-.913-.199");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h3y0xybwn {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M15.498 5.582c-.116-.205-.293-.367-.675-.367a.73.73 0 0 0-.471.162c-.118.096-.103.218-.011.264l.244.14c.287-.093.603-.106.913-.199");
}

.hil4-np7l {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.95 5.241a.614.614 0 0 0-.595.465a.12.12 0 0 0 .117.15h.98a.1.1 0 0 0 .1-.12a.615.615 0 0 0-.602-.495");
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hk_5_2bqz {
  stop-color: var(--svg-color--925870, #925870);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hm4ptbkef {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("M13.841 16.234L14.31 28h.812V17.39h2.203V28h.672l.438-11.766z");
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i0vp1so6w {
  d: path("M15.129 7.226h1.742v1.352a.871.871 0 0 1-1.742 0z");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.ikpy-qbyu {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16 7.111a1.3 1.3 0 0 1-.624-.151c-.062-.032-.129.039-.09.096a.848.848 0 0 0 1.428 0c.038-.06-.028-.128-.09-.096c-.18.096-.393.151-.624.151");
}

.ise8hkbqb {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.671v.243H15.5v-1.598h-1.992c-.102.367-.574.754-.817.914a.54.54 0 0 0-.257.441");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j1j51bc4m {
  d: path("M13.765 5.278h.006l-.005-.117l-.004-.134c.009-.417.252-.578.356-.632l.022-.01l.023-.008c.234-.108.423-.296.522-.542l.036-.086a.116.116 0 0 1 .203-.022c.315.462.842.735 1.4.735h1.415c.08 0 .476.038.5.585l-.053 1.35c-.054 1.231-1.015 2.058-2.189 2.058c-1.173 0-2.135-.827-2.189-2.058z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jewrngbdz {
  stop-color: var(--svg-color--b06e67, #B06E67);
  stop-opacity: 0;
}

.jimqrcckc {
  d: path("M13.773 3.202c.249-.263.72-.264.936-.224l.174.567c-.11-.018-.13-.001-.213.08c-.06.48-.604.771-1.268.965c-.065-.655.048-1.045.371-1.388");
}

.jjkdnok3l {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m17.057 3.996l-.626.115a.302.302 0 1 1-.055-.6h1.028c.608 0 .81.613.834.823a1.38 1.38 0 0 0-1.18-.338");
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jtspvdbwc {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m14.508 5.051l-.002.002a.118.118 0 0 1-.122-.202h.001l.001-.002l.005-.002l.014-.008l.05-.026a1.4 1.4 0 0 1 .18-.07c.15-.048.359-.089.584-.049a.118.118 0 1 1-.04.232a1 1 0 0 0-.472.04a1 1 0 0 0-.19.08z");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k359d0bjg {
  stop-color: var(--svg-color--645b87, #645B87);
  stop-opacity: 0;
}

.k3iqnbc3x {
  stop-color: var(--svg-color--7759b9, #7759B9);
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.kqc1q6b3u {
  stop-color: var(--svg-color--4b3677, #4B3677);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj8hkjeee {
  stop-color: var(--svg-color--6c5ca2, #6C5CA2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mszjt37ue {
  stop-color: var(--svg-color--a67474, #A67474);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mwlubcb3u {
  stop-color: var(--svg-color--4a367d, #4A367D);
}

.myif5tbjr {
  fill: var(--svg-color--8b7dbc, #8B7DBC);
  d: path("M20.468 12.512c-.487-2.254-1.629-3.334-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.121");
}

.ni4u1bbhm {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m17.64 4.85l-.062.102za.118.118 0 0 1-.12.202h-.001l-.002-.002l-.05-.025a1 1 0 0 0-.15-.06a1 1 0 0 0-.47-.04a.118.118 0 0 1-.042-.232c.226-.04.434 0 .584.048a1.4 1.4 0 0 1 .245.105l.004.002z");
}

.now9rmbjg {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M13.95 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.nrk1uwb9l {
  stop-color: var(--svg-color--8e4a4a, #8E4A4A);
}

.nv-tm3b_c {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.05 5.241c.287 0 .53.198.595.465a.12.12 0 0 1-.117.15h-.98a.1.1 0 0 1-.1-.12a.614.614 0 0 1 .602-.495");
}

.o_hp5nbjg {
  d: path("M12.112 20.292c-.938-1.982-.769-6.259-.488-7.824h1.672c-.071 2.426.04 5.243.178 6.512c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.202c.061.299.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o93ji_bej {
  d: path("M19.888 20.292c.938-1.982.769-6.259.487-7.824h-1.671c.071 2.426-.156 5.254-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.202c-.061.299-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojwkb-b4s {
  d: path("M18.12 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.pcr8w9bct {
  d: path("M11.533 12.512c.486-2.254 1.628-3.334 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.121");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pu1qalb0n {
  fill: var(--svg-color--64558f, #64558F);
  d: path("M11.533 12.512c.486-2.254 1.628-3.334 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.121");
}

.q3bc6bbmg {
  fill: var(--svg-color--000, #000);
  d: path("M15.265 5.753c0-.125-.1-.225-.224-.225a.224.224 0 0 0-.2.328h.398a.2.2 0 0 0 .026-.103");
}

.q7l1h8mqg {
  stop-color: var(--svg-color--9e6774, #9E6774);
  stop-opacity: 0;
}

.qb52yacny {
  stop-color: var(--svg-color--8467c1, #8467C1);
}

.qe-nmobot {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16 7.111a1.3 1.3 0 0 1-.624-.151c-.062-.032-.129.039-.09.096a.848.848 0 0 0 1.428 0c.038-.06-.028-.128-.09-.096c-.18.096-.393.151-.624.151Z");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qr3eebgfz {
  d: path("M12.941 11.378a3.059 3.059 0 0 1 6.118 0v4.442a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.qrmj1y8xw {
  d: path("M13.942 6.54a.707.707 0 1 0 0-1.414a.707.707 0 0 0 0 1.413");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0w13r7uj {
  d: path("M16.96 5.36a.392.392 0 0 1 .377.496h-.757a.394.394 0 0 1 .38-.495");
}

.r2rrbr4ji {
  stop-color: var(--svg-color--886cc6, #886CC6);
  stop-opacity: 0;
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r7p4z7bsm {
  d: path("M16.155 7.808q.164.008.336.021c-.114-.008-.223-.017-.336-.021");
}

.rmne4ubxs {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M18.12 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.s61flvbkc {
  stop-color: var(--svg-color--7361ab, #7361AB);
  stop-opacity: 0;
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.sf6dqgv3q {
  stop-color: var(--svg-color--4a367d, #4A367D);
  stop-opacity: 0;
}

.sgj6b5b-t {
  stop-color: var(--svg-color--655690, #655690);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t_70vht6h {
  d: path("M15.04 5.36a.392.392 0 0 0-.377.496h.757a.395.395 0 0 0-.38-.495");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t7iga1bol {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.735 2.41c-.498-.11-.944.387-.996.57c.462 1.558 1.631 1.473 2.785 1.345c.69-.077.766.238.825.39c0-1.728-1.47-2.052-2.602-2.302z");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tcfzn_bju {
  stop-color: var(--svg-color--9a706a, #9A706A);
  stop-opacity: 0;
}

.tfix0o_9x {
  stop-color: var(--svg-color--7c63b5, #7C63B5);
  stop-opacity: 0;
}

.tkifgyigj {
  d: path("M15.399 5.707c0-.127-.103-.212-.131-.237l-.127.122l.078.16z");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u-feptipi {
  cx: 14.922px;
  cy: 5.528px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.171px;
  ry: 0.087px;
}

.u1ssmd66p {
  d: path("M20.468 12.512c-.487-2.254-1.629-3.334-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.121");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.ukvj5-vlj {
  d: path("M19.566 29.671v.243H16.5v-1.598h1.992c.102.367.574.754.817.914c.186.123.257.3.257.441");
}

.umgvlrbgn {
  fill: var(--svg-color--000, #000);
  d: path("M16.735 5.753c0-.125.1-.225.224-.225a.224.224 0 0 1 .2.328h-.397a.2.2 0 0 1-.027-.103");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.usmnphbrw {
  fill: var(--svg-color--8f5f62, #8F5F62);
  d: path("M19.333 19.011a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.113a.32.32 0 0 1 .074-.301c.083-.077.271-.253.355-.344");
}

.uzvwpqz1p {
  fill: var(--svg-color--794a4d, #794A4D);
  d: path("M12.668 19.011a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.113a.32.32 0 0 0-.074-.301a9 9 0 0 1-.355-.344");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vy3y1vbex {
  d: path("M17.309 5.701a.37.37 0 0 0-.102-.203l-.114.125l.051.1z");
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w2wdskbew {
  stop-color: var(--svg-color--503a89, #503A89);
}

.w48qw8bka {
  stop-color: var(--svg-color--8d5460, #8D5460);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wznkn9tzm {
  fill: var(--svg-color--bb937c, #BB937C);
  d: path("M19.888 20.292c.938-1.982.769-6.259.487-7.824h-1.671c.071 2.426-.156 5.254-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.202c-.061.299-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.xc4tawbvb {
  d: path("m15.832 5.674l-.233.746a.237.237 0 0 0 .228.308h.346a.238.238 0 0 0 .228-.308l-.233-.746c-.05-.166-.284-.166-.336 0");
}

.xqme1t_en {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.016 15.863l.484 12.453h2l.238-9.523c0-.329.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ymsp3kbav {
  d: path("M18.12 6.54a.707.707 0 1 0 0-1.414a.707.707 0 0 0 0 1.413");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.zay0pib-e {
  stop-color: var(--svg-color--8d434a, #8D434A);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zjcs0bbar {
  d: path("M13.95 6.304a.472.472 0 1 0 0-.943a.472.472 0 0 0 0 .943");
}

.zm9zkcl5b {
  fill-rule: evenodd;
  d: path("M19.156 6.452a1.44 1.44 0 0 0 .024-1.2h.003a1.4 1.4 0 0 0-.124-.226v-.001a1.4 1.4 0 0 1-.232-.778v-.005c0-.8-.649-1.449-1.449-1.449a.24.24 0 0 1-.2-.102a1.452 1.452 0 0 0-2.356 0a.25.25 0 0 1-.2.102h-.037a1.45 1.45 0 0 0-1.412 1.45v.004c0 .275-.08.547-.231.778l-.001.001a1.45 1.45 0 0 0-.097 1.426a.23.23 0 0 1 0 .2a1.41 1.41 0 0 0 1.271 2.032h3.77a1.412 1.412 0 0 0 1.271-2.032a.23.23 0 0 1 0-.2m-5.385-1.174h-.006l.527 1.035c.054 1.23.535 0 1.708 0s1.685 1.37 1.74.139l.498-1.405c-.023-.546-.42-.585-.499-.585h-1.414a1.7 1.7 0 0 1-1.401-.735a.116.116 0 0 0-.203.023l-.036.085a1 1 0 0 1-.522.542l-.023.009l-.022.009c-.104.054-.347.215-.356.632l.004.134z");
}

.zqan0v-dy {
  stop-color: var(--svg-color--645b87, #645B87);
}

</style>
