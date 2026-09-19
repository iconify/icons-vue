<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDK7Rxn)"><path fill="url(#inNnxEd)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#iQAHcFb)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#ieUO17d)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#i0EHvLS)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#iaBDvse)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#ig0xche)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#isEsjEc)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#iTEPMJv)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#iM7ujxb)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#ioxXkhi)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#iQGW1mc)" clip-rule="evenodd" class="cve2j7bwh"/><path fill="url(#ibSynrd)" clip-rule="evenodd" class="cve2j7bwh"/></g><path fill="url(#iCL8jRW)" class="f6jx5hbjw"/><path fill="url(#iMgzVBd)" class="f6jx5hbjw"/><path fill="url(#ieH9iFw)" class="f6jx5hbjw"/><path fill="url(#iL6b4oc)" class="f6jx5hbjw"/><rect fill="url(#iF0tMNc)" class="c-m0h9unw"/><rect fill="url(#iwmNCEc)" class="c-m0h9unw"/><g filter="url(#iZQ8HMj)"><path class="gb_43eltn"/><path fill="url(#inG05Xd)" class="tj0ua4-4q"/><path fill="url(#ifdrmed)" class="tj0ua4-4q"/><path fill="url(#iOin9GA)" class="tj0ua4-4q"/></g><g filter="url(#icRZJ0b)"><path fill="url(#iGJoWor)" class="x9prdyaoh"/><path fill="url(#ivShmJe)" class="x9prdyaoh"/><path fill="url(#ifZWzfe)" class="x9prdyaoh"/></g><g filter="url(#i088OHc)"><path clip-rule="evenodd" class="g-3ktq4ee"/><path fill="url(#i8lBA2b)" clip-rule="evenodd" class="u2cg76bkx"/><path fill="url(#i1SyoPb)" clip-rule="evenodd" class="u2cg76bkx"/><path fill="url(#irtO9Ib)" clip-rule="evenodd" class="u2cg76bkx"/></g><g filter="url(#iGKCLfd)"><path clip-rule="evenodd" class="t2xo9ubxq"/><path fill="url(#iqSvp0b)" clip-rule="evenodd" class="r3osmtbwz"/><path fill="url(#iHXh4Xb)" clip-rule="evenodd" class="r3osmtbwz"/><path fill="url(#ixVdxeO)" clip-rule="evenodd" class="r3osmtbwz"/></g><g filter="url(#iEfLxYb)"><path clip-rule="evenodd" class="btm8flb_l"/><path fill="url(#i4YvFte)" clip-rule="evenodd" class="h5p97osrc"/><path fill="url(#iLrCjWd)" clip-rule="evenodd" class="h5p97osrc"/><path fill="url(#iDaYVnd)" clip-rule="evenodd" class="h5p97osrc"/></g><g filter="url(#iaf5Kfc)"><path clip-rule="evenodd" class="bjac39bcf"/><path fill="url(#i9RC0xe)" clip-rule="evenodd" class="e418f2bdb"/><path fill="url(#iwgV4id)" clip-rule="evenodd" class="e418f2bdb"/><path fill="url(#iGHhRse)" clip-rule="evenodd" class="e418f2bdb"/></g><g filter="url(#in3D1SX)"><path class="jxpyyfjtn"/><path fill="url(#iKsH0qo)" class="vxsyxybal"/><path fill="url(#ichI6bd)" class="vxsyxybal"/><path fill="url(#iPKHube)" class="vxsyxybal"/></g><path fill="url(#id5WUfd)" class="zxu2ysp1r"/><path fill="url(#iHoFTrb)" class="zxu2ysp1r"/><g filter="url(#i0pgcsc)"><path fill="url(#i0iDgwb)" class="rmvpd4mhh"/><path fill="url(#itzcXdb)" class="rmvpd4mhh"/><path fill="url(#iVVJc3d)" class="rmvpd4mhh"/><path fill="url(#ilBHKIc)" class="rmvpd4mhh"/></g><g filter="url(#i3apM6d)"><path stroke="url(#iaR2nAb)" class="vm8azdt3q"/></g><g filter="url(#iK3iRxb)"><path fill="url(#i5AMNBc)" class="u2odskbna"/></g><path fill="url(#iXA8HvR)" class="u2odskbna"/><g filter="url(#i2hJeJe)"><path fill="url(#iRlfgsK)" class="mhdrkkbes"/><path fill="url(#ieRMAvd)" class="mhdrkkbes"/></g><g filter="url(#iIbtkUc)"><path class="utztfdimk"/><path fill="url(#idxyk7z)" class="fs7zxpbjy"/></g><g filter="url(#iKcY14h)"><path class="fyq_05bqq"/><path fill="url(#igUkvec)" class="haxo4um8e"/></g><g filter="url(#i5oU2nr)"><path fill="url(#iZhFbEu)" class="il834qa_s"/><path fill="url(#iOrTnGc)" class="il834qa_s"/><path fill="url(#iYLGbqT)" class="il834qa_s"/><path fill="url(#i8uR1Wc)" class="il834qa_s"/><path fill="url(#iyIwive)" class="il834qa_s"/><path fill="url(#ixjczCe)" class="il834qa_s"/><path fill="url(#iysdV4q)" class="il834qa_s"/><path fill="url(#iDSmPgd)" class="il834qa_s"/><path fill="url(#ie2dHFb)" class="il834qa_s"/></g><path fill="url(#i7Fg1bc)" class="il834qa_s"/><g filter="url(#i11Zsjc)"><path class="vp91edbxh"/></g><g filter="url(#ik0zSxe)"><path class="sm_jwybta"/><path fill="url(#iSCCH2d)" class="kl_jetb4k"/><path fill="url(#iIeSBzc)" class="kl_jetb4k"/><path fill="url(#ikqsdTd)" class="kl_jetb4k"/><path fill="url(#iBUNrmc)" class="kl_jetb4k"/></g><path fill="url(#i7RSGBb)" class="kl_jetb4k"/><path fill="url(#iqJwMJb)" class="kl_jetb4k"/><path stroke="url(#iHIZWCe)" class="w-ygdhhti"/><g filter="url(#iOMdROb)"><path class="w_ole4b0t"/></g><g filter="url(#ihtIP7m)"><path class="mowoigbtu"/></g><g filter="url(#iXD605b)"><path class="us1b95zkc"/></g><g filter="url(#iA1GPde)"><path clip-rule="evenodd" class="ozqavabwo"/></g><path class="iwh2gc0_v"/><path fill="url(#iUTTwWM)" class="bk1c7ei-f"/><path class="ve5hsjbem"/><g filter="url(#iBLLEhe)"><path class="fn2fsjb6v"/><path fill="url(#ivHDcNc)" class="d-23whrlh"/></g><g filter="url(#i5tmoFd)"><path fill="url(#iH923ib)" class="i4tarebhh"/></g><path class="e92x3abyb"/><path fill="url(#imTeKfb)" class="ar59spbzj"/><path class="arvgq3bng"/><g filter="url(#i3CNkgb)"><path fill="url(#iAnWjOJ)" class="g-o7r1d6v"/></g><g filter="url(#ilnZPgc)"><ellipse transform="rotate(-27.914 9.314 12.452)" class="qutvv9byr"/><ellipse fill="url(#iNeoQ4y)" transform="rotate(-27.914 9.314 12.452)" class="ja5shnp0m"/></g><g filter="url(#i3bYE3d)"><path class="q4i1lqbnd"/></g><g filter="url(#ikJohhc)"><path class="fq6dhwbpb"/></g><g filter="url(#iYgYHUd)"><path class="ycqdlkbeq"/><path fill="url(#iFDDuBb)" class="vpw_4kyku"/><path fill="url(#i7Ncrwb)" class="vpw_4kyku"/></g><g filter="url(#ifGX0rb)"><path class="n8wh5fbks"/><path fill="url(#iOgi0Ud)" class="be62pdbtt"/><path fill="url(#iKi6DXc)" class="be62pdbtt"/></g><g filter="url(#i6LQ2Sb)"><path stroke="url(#iWjgpvc)" class="e5cwm7bbs"/></g><g filter="url(#izSS9Kd)"><path class="f8h_un9mf"/></g><defs><radialGradient id="iQAHcFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.77696 5.8704 -7.33332 -.97058 12.085 16.564)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="ieUO17d" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 1.645 9.748)scale(4.47758 5.88319)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="i0EHvLS" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68341 2.20141 -1.69038 -1.29263 6.236 13.63)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iaBDvse" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 .32 7.42)scale(3.18696 2.24493)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="ig0xche" cx="0" cy="0" r="1" gradientTransform="matrix(1.76974 3.36685 -4.67371 2.45667 7.94 2.968)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="isEsjEc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.823 6.96)scale(2.62482 3.66815)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iTEPMJv" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.198 7.702)scale(2.47237 5.15595)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iM7ujxb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62572 .90648 -1.15472 -4.61864 21.365 16.65)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="ioxXkhi" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.543 -2.084)scale(3.6058 2.85198)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iQGW1mc" cx="0" cy="0" r="1" gradientTransform="matrix(1.93649 .20312 -.32912 3.13768 4.564 12.201)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="ibSynrd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.068 -1.932)scale(4.89025 1.76499)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iMgzVBd" cx="0" cy="0" r="1" gradientTransform="rotate(-128.9 17.788 9.584)scale(14.3752 17.7454)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="prklqobcj"/><stop offset="1" class="ff_veq9dp"/></radialGradient><radialGradient id="ieH9iFw" cx="0" cy="0" r="1" gradientTransform="rotate(80.311 -5.82 15.88)scale(6.49895 15.3845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="qt4ap0b2z"/><stop offset="1" class="f46_0ydpi"/></radialGradient><radialGradient id="iL6b4oc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.904 18.97 8.72)scale(9.57741 4.33562)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="kptn98y8b"/><stop offset="1" class="xy2mpdbhe"/></radialGradient><radialGradient id="iF0tMNc" cx="0" cy="0" r="1" gradientTransform="matrix(3.22707 3.60967 -4.23022 3.78186 10.938 20.348)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ll4a91bdg"/><stop offset=".826" class="na9-zpgzs"/></radialGradient><radialGradient id="inG05Xd" cx="0" cy="0" r="1" gradientTransform="rotate(173.116 12.197 9.163)scale(.49483 .58088)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="ifdrmed" cx="0" cy="0" r="1" gradientTransform="matrix(.00796 .06217 -.74977 .09602 24.447 16.492)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="iOin9GA" cx="0" cy="0" r="1" gradientTransform="matrix(1.48887 .51514 -.5214 1.50697 21.19 16.52)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="iGJoWor" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42187 1.4375 -.43294 -.42823 24.125 13.063)" gradientUnits="userSpaceOnUse"><stop class="s8lp15btp"/><stop offset="1" class="f3rvvbc1q"/></radialGradient><radialGradient id="ivShmJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.37263 .08503 -.18186 -.797 24.436 14.189)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="ifZWzfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.12934 .73823 -1.10747 1.6942 21.24 13.79)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="i8lBA2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.58754 .06566 -.07147 -.63952 29.777 14.595)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="i1SyoPb" cx="0" cy="0" r="1" gradientTransform="matrix(.07825 .46522 -6.05348 1.01824 28.388 13.318)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="irtO9Ib" cx="0" cy="0" r="1" gradientTransform="matrix(1.78068 .57009 -.54226 1.69375 24.738 14.287)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="iqSvp0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.58467 .06405 -.06838 -.62413 30.355 14.895)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="iHXh4Xb" cx="0" cy="0" r="1" gradientTransform="matrix(.07787 .4538 -6.0172 1.03254 28.973 13.65)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="ixVdxeO" cx="0" cy="0" r="1" gradientTransform="matrix(1.77198 .5561 -.5204 1.65823 25.34 14.595)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="i4YvFte" cx="0" cy="0" r="1" gradientTransform="matrix(-.58658 .06175 -.0634 -.60226 30.074 15.34)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="iLrCjWd" cx="0" cy="0" r="1" gradientTransform="matrix(.07813 .4375 -6.0225 1.07545 28.687 14.14)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="iDaYVnd" cx="0" cy="0" r="1" gradientTransform="matrix(1.77775 .53612 -.48545 1.6097 25.043 15.051)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="i9RC0xe" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.888 9.192)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iwgV4id" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.885 23.49)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iKsH0qo" cx="0" cy="0" r="1" gradientTransform="matrix(-.96409 .10438 -.11015 -1.0174 29.307 15.74)" gradientUnits="userSpaceOnUse"><stop class="tnzljqbeq"/><stop offset="1" class="lmvunqbvz"/></radialGradient><radialGradient id="ichI6bd" cx="0" cy="0" r="1" gradientTransform="matrix(.01563 .10937 -1.46562 .20938 27.428 15.203)" gradientUnits="userSpaceOnUse"><stop class="zou-tybqy"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="e0ixrbbzo"/></radialGradient><radialGradient id="iPKHube" cx="0" cy="0" r="1" gradientTransform="matrix(2.92188 .90625 -.8399 2.70799 21.038 15.25)" gradientUnits="userSpaceOnUse"><stop class="razeofbhj"/><stop offset="1" class="ei3uyjb-y"/></radialGradient><radialGradient id="id5WUfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05458 -3.66708 0 24.195 17.387)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="sipuclb6i"/><stop offset="1" class="su4gzg9-j"/></radialGradient><radialGradient id="iVVJc3d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1875 0 0 -.57813 24.812 19.227)" gradientUnits="userSpaceOnUse"><stop class="ow11_7b9u"/><stop offset="1" class="n-9oslbsi"/></radialGradient><radialGradient id="iXA8HvR" cx="0" cy="0" r="1" gradientTransform="rotate(-118.51 7.552 5.943)scale(1.76346 1.99824)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iRlfgsK" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 40.945 -33.843)scale(3.52054 4.29841)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="ieRMAvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.55393 0 0 .66905 18.84 11.147)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="idxyk7z" cx="0" cy="0" r="1" gradientTransform="matrix(1.94418 -.14461 .11305 1.51981 18.127 13.489)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="igUkvec" cx="0" cy="0" r="1" gradientTransform="rotate(-180 3.274 6.672)scale(1.35969)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iZhFbEu" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.689 8.099)scale(9.22168 12.3431)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iOrTnGc" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 6.06 8.454)scale(3.06717 2.13593)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iYLGbqT" cx="0" cy="0" r="1" gradientTransform="matrix(1.65995 -5.05828 6.41801 2.10616 9.689 21.031)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i8uR1Wc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6542 9.49394 -11.86731 -2.06772 13.79 12.116)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ndb61xwjr"/><stop offset="1" class="l57p2o49o"/></radialGradient><radialGradient id="iyIwive" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.07178 -8.11501 0 12.136 13.154)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="i-c7amj6z"/><stop offset="1" class="nmcs74byh"/></radialGradient><radialGradient id="ixjczCe" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 6.679 8.16)scale(9.06154 15.6012)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iysdV4q" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.48177 1.81853 0 15.436 12.113)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iDSmPgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69003 1.93689 0 9.8 11.819)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="ie2dHFb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12044 4.15486 -3.32457 -.89654 14.254 9.131)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="i7Fg1bc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65497 0 0 -8.29951 19.034 14.029)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iSCCH2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.58657 -2.63193 .81114 -.18078 13.483 14.965)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iBUNrmc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00358 0 0 -.28057 13.174 15.237)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iqJwMJb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 4.235 9.246)scale(2.14166 2.57394)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="iUTTwWM" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04467 -1.66167 0 15.283 12.575)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ivHDcNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29862 -.38482 .5298 -.41113 14.989 12.684)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imTeKfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04468 -1.66168 0 9.663 12.575)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iNeoQ4y" cx="0" cy="0" r="1" gradientTransform="matrix(-.00996 -.63617 .7647 -.01197 9.294 12.858)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFDDuBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.62502 -3.54797 1.81505 .83132 5.187 9.845)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="i7Ncrwb" cx="0" cy="0" r="1" gradientTransform="rotate(-59.802 11.156 -2.13)scale(2.94273 1.57984)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="iOgi0Ud" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.48 6.265)scale(6.27449 10.2584)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iKi6DXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27083 1.76044 -3.7875 -.58269 12.744 3.616)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="iDK7Rxn" width="19.588" height="20.088" x="2.804" y="1.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="iZQ8HMj" width="4.015" height="2.316" x="21.349" y="15.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="icRZJ0b" width="3.045" height="3.19" x="21.36" y="12.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="i088OHc" width="4.802" height="2.532" x="24.927" y="13.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="iGKCLfd" width="4.778" height="2.477" x="25.529" y="13.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="iEfLxYb" width="4.794" height="2.399" x="25.232" y="13.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="iaf5Kfc" width="7.879" height="3.847" x="21.349" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.603922 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="in3D1SX" width="7.879" height="3.847" x="21.349" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.376471 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="i0pgcsc" width="6.491" height="11.844" x="20.207" y="18.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="i3apM6d" width="5.722" height="1.374" x="23.292" y="15.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".125"/></filter><filter id="iK3iRxb" width="4.294" height="4.144" x="4.368" y="11.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="i2hJeJe" width="4.144" height="4.394" x="16.617" y="11.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="iIbtkUc" width="3.766" height="3.766" x="16.806" y="11.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".25"/></filter><filter id="iKcY14h" width="3.466" height="3.466" x="4.731" y="11.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".175"/></filter><filter id="i5oU2nr" width="13.122" height="14.405" x="5.912" y="7.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="i11Zsjc" width="3.417" height="4.453" x="10.555" y="12.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".25"/></filter><filter id="ik0zSxe" width="2.917" height="3.953" x="11.014" y="12.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".125"/></filter><filter id="iOMdROb" width="3.807" height="1.655" x="13.744" y="11.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="ihtIP7m" width="3.807" height="1.655" x="7.396" y="11.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="iXD605b" width="3.101" height="1.347" x="7.57" y="9.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="iA1GPde" width="3.101" height="1.347" x="14.545" y="9.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/></filter><filter id="iBLLEhe" width=".956" height=".839" x="14.366" y="12.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".05"/></filter><filter id="i5tmoFd" width="1.033" height="1.061" x="15.476" y="12.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".1"/></filter><filter id="i3CNkgb" width="1.155" height="1.224" x="9.756" y="12.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".1"/></filter><filter id="ilnZPgc" width="1.118" height=".85" x="8.755" y="12.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".05"/></filter><filter id="i3bYE3d" width="3.339" height="1.686" x="14.37" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".2"/></filter><filter id="ikJohhc" width="3.339" height="1.686" x="7.351" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".2"/></filter><filter id="iYgYHUd" width="5.293" height="5.681" x="4.406" y="4.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/><feGaussianBlur result="effect2_foregroundBlur_4002_3796" stdDeviation=".2"/></filter><filter id="ifGX0rb" width="11.131" height="7.301" x="8.477" y="3.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3796"/><feGaussianBlur result="effect2_foregroundBlur_4002_3796" stdDeviation=".125"/></filter><filter id="i6LQ2Sb" width="1.301" height="2.801" x="8.45" y="4.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".1"/></filter><filter id="izSS9Kd" width="8.344" height="4.41" x="11.69" y="5.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3796" stdDeviation=".5"/></filter><linearGradient id="inNnxEd" x1="18.516" x2="10.617" y1="4.392" y2="18.248" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iCL8jRW" x1="12.473" x2="12.473" y1="30.602" y2="25.695" gradientUnits="userSpaceOnUse"><stop class="actv8ccua"/><stop offset="1" class="g60esfuqb"/></linearGradient><linearGradient id="iwmNCEc" x1="12.442" x2="12.442" y1="20.641" y2="21.585" gradientUnits="userSpaceOnUse"><stop class="rk72x724k"/><stop offset="1" class="jgp2uobfz"/></linearGradient><linearGradient id="iGHhRse" x1="24.679" x2="26.273" y1="16.84" y2="16.527" gradientUnits="userSpaceOnUse"><stop offset=".585" class="oc3fsgi2c"/><stop offset="1" class="v-pv693fm"/></linearGradient><linearGradient id="iHoFTrb" x1="23.574" x2="23.574" y1="18.338" y2="18.164" gradientUnits="userSpaceOnUse"><stop offset=".316" class="gublzhv6p"/><stop offset="1" class="crzqbdcxn"/></linearGradient><linearGradient id="i0iDgwb" x1="24.445" x2="24.445" y1="19.402" y2="38.715" gradientUnits="userSpaceOnUse"><stop class="eh67o3baq"/><stop offset=".621" class="fhdfn3b2i"/></linearGradient><linearGradient id="itzcXdb" x1="27.859" x2="22.432" y1="28.93" y2="28.93" gradientUnits="userSpaceOnUse"><stop class="p82q4v34p"/><stop offset=".458" class="aw40h5l5c"/><stop offset="1" class="p82q4v34p"/></linearGradient><linearGradient id="ilBHKIc" x1="23.403" x2="23.403" y1="18.243" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".366" class="kj63bk6ym"/><stop offset="1" class="weadzoqrn"/></linearGradient><linearGradient id="iaR2nAb" x1="28.294" x2="23.473" y1="15.739" y2="16.246" gradientUnits="userSpaceOnUse"><stop class="fxqi8abqb"/><stop offset="1" class="u1zz4n4nv"/></linearGradient><linearGradient id="i5AMNBc" x1="4.368" x2="6.759" y1="13.457" y2="13.457" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iIeSBzc" x1="11.264" x2="12.473" y1="15.058" y2="15.058" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="ikqsdTd" x1="12.473" x2="12.473" y1="15.969" y2="15.162" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="i7RSGBb" x1="12.574" x2="12.574" y1="16.053" y2="15.874" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="iHIZWCe" x1="11.102" x2="11.696" y1="17.902" y2="16.985" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iH923ib" x1="16.284" x2="15.88" y1="12.645" y2="12.894" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAnWjOJ" x1="10.621" x2="10.217" y1="12.645" y2="12.894" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWjgpvc" x1="8.47" x2="9.101" y1="4.392" y2="6.021" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-tipping-hand-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.actv8ccua {
  stop-color: var(--svg-color--9069d4, #9069D4);
}

.adnp-y-dh {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
  stop-opacity: 0;
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

.ar59spbzj {
  d: path("M9.66 11.961a1.15 1.15 0 0 0-1.107 1.452h2.22q.04-.147.042-.303a1.157 1.157 0 0 0-1.154-1.149");
}

.arvgq3bng {
  fill: var(--svg-color--000, #000);
  d: path("M10.319 13.11a.655.655 0 0 0-.658-.658a.655.655 0 0 0-.585.961h1.164a.65.65 0 0 0 .079-.303");
}

.aw40h5l5c {
  stop-color: var(--svg-color--9f77e5, #9F77E5);
}

.ax8207b9e {
  stop-color: var(--svg-color--e4b833, #E4B833);
  stop-opacity: 0;
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.be62pdbtt {
  d: path("M11.696 3.313c-1.458-.322-2.768 1.133-2.919 1.672c1.354 4.565 4.781 4.315 8.164 3.94c2.025-.226 2.244.697 2.417 1.143c0-5.064-4.306-6.014-7.625-6.747z");
}

.bjac39bcf {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M25.66 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.248c.917-.102 1.759-.206 2.234-.308a.825.825 0 0 0-.345-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.493.05");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bk1c7ei-f {
  d: path("M15.285 11.961a1.15 1.15 0 0 1 1.108 1.452h-2.22a1.154 1.154 0 0 1 1.113-1.452");
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.btm8flb_l {
  fill: var(--svg-color--bd9679, #BD9679);
  fill-rule: evenodd;
  d: path("M30.023 15.067a.85.85 0 0 1-.773.921a28 28 0 0 0-1.26.162l-.03.004c-.525.075-1.133.16-1.787.231a.85.85 0 0 1-.182-1.69c.622-.067 1.204-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.c-m0h9unw {
  width: 4.898px;
  height: 6.68px;
  x: 10.035px;
  y: 17.009px;
  rx: 2.449px;
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crzqbdcxn {
  stop-color: var(--svg-color--533b7c, #533B7C);
  stop-opacity: 0;
}

.cve2j7bwh {
  fill-rule: evenodd;
  d: path("M21.725 15.16c.273-.56.417-1.186.417-1.838c0-.602-.124-1.166-.346-1.68h.007a4 4 0 0 0-.362-.661l-.003-.004a4.17 4.17 0 0 1-.677-2.28v-.014a4.25 4.25 0 0 0-4.248-4.248a.7.7 0 0 1-.587-.3a4.26 4.26 0 0 0-3.453-1.772c-1.42 0-2.685.704-3.453 1.772a.73.73 0 0 1-.587.3l-.11.001a4.25 4.25 0 0 0-4.138 4.247v.013c0 .808-.234 1.603-.677 2.28l-.003.005a4.25 4.25 0 0 0-.284 4.179a.66.66 0 0 1 0 .586a4.2 4.2 0 0 0-.417 1.811a4.14 4.14 0 0 0 4.144 4.144h11.05a4.14 4.14 0 0 0 4.144-4.144c0-.651-.157-1.264-.417-1.811a.66.66 0 0 1 0-.587M5.938 11.718h-.016l1.544 3.033c.159 3.609 1.567 0 5.007 0s4.94 4.017 5.098.409l1.463-4.117c-.07-1.603-1.23-1.716-1.463-1.716h-4.146A4.97 4.97 0 0 1 9.32 7.173a.34.34 0 0 0-.595.065l-.105.25a2.97 2.97 0 0 1-1.532 1.59q-.03.01-.066.026q-.035.016-.066.026c-.304.158-1.017.63-1.043 1.853l.013.394z");
}

.d-23whrlh {
  d: path("M15.2 12.204c.083.11-.088.243-.283.389c-.195.145-.339.248-.42.138c-.083-.11.009-.316.203-.462c.195-.145.419-.174.5-.065");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0ixrbbzo {
  stop-color: var(--svg-color--ab876c, #AB876C);
  stop-opacity: 0;
}

.e418f2bdb {
  fill-rule: evenodd;
  d: path("M25.66 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.248c.917-.102 1.759-.206 2.234-.308a.825.825 0 0 0-.345-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.493.05");
}

.e5cwm7bbs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.75 4.92c.03.314.302 1.49.702 2.202");
}

.e92x3abyb {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.394 11.611c-.84 0-1.551.58-1.744 1.364a.353.353 0 0 0 .344.438h2.873c.183 0 .33-.167.293-.35a1.804 1.804 0 0 0-1.766-1.452");
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eh67o3baq {
  stop-color: var(--svg-color--8860cb, #8860CB);
}

.ei3uyjb-y {
  stop-color: var(--svg-color--956f58, #956F58);
  stop-opacity: 0;
}

.f3rvvbc1q {
  stop-color: var(--svg-color--ab866a, #AB866A);
}

.f46_0ydpi {
  stop-color: var(--svg-color--8460bf, #8460BF);
  stop-opacity: 0;
}

.f6jx5hbjw {
  d: path("M12.473 20.036c-5.523 0-10 4.477-10 10v.05h20v-.05c0-5.523-4.477-10-10-10");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.f8h_un9mf {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m15.572 7.96l-1.836.338a.886.886 0 1 1-.16-1.757h3.013c1.783 0 2.373 1.796 2.445 2.41a4.05 4.05 0 0 0-3.462-.99");
}

.ff_veq9dp {
  stop-color: var(--svg-color--8e6bd1, #8E6BD1);
  stop-opacity: 0;
}

.fhdfn3b2i {
  stop-color: var(--svg-color--8560c7, #8560C7);
}

.fn2fsjb6v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.2 12.204c.083.11-.088.243-.283.389c-.195.145-.339.248-.42.138c-.083-.11.009-.316.203-.462c.195-.145.419-.174.5-.065");
}

.fq6dhwbpb {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.09 10.29c-.416-.102-1.449-.051-2.14.443");
}

.fs7zxpbjy {
  d: path("M18.689 14.727a1.383 1.383 0 1 0 0-2.766a1.383 1.383 0 0 0 0 2.766");
}

.ft5dv1b6b {
  fill: none;
}

.fxqi8abqb {
  stop-color: var(--svg-color--c9a38d, #C9A38D);
}

.fyq_05bqq {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M6.464 14.727a1.383 1.383 0 1 0 0-2.766a1.383 1.383 0 0 0 0 2.766");
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g-3ktq4ee {
  fill: var(--svg-color--bd9679, #BD9679);
  fill-rule: evenodd;
  d: path("M29.716 14.181a.85.85 0 0 1-.69.985a21 21 0 0 0-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.317-.38q.39-.083.716-.142a.85.85 0 0 1 .985.69");
}

.g-o7r1d6v {
  d: path("M10.71 12.975c0-.371-.302-.619-.383-.693l-.371.359l.228.465z");
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g60esfuqb {
  stop-color: var(--svg-color--8d66ce, #8D66CE);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gb_43eltn {
  fill: var(--svg-color--bd9679, #BD9679);
  d: path("M21.349 15.789h4.015v2.016h-4.015z");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gublzhv6p {
  stop-color: var(--svg-color--533b7c, #533B7C);
}

.h5p97osrc {
  fill-rule: evenodd;
  d: path("M30.023 15.067a.85.85 0 0 1-.773.921a28 28 0 0 0-1.26.162l-.03.004c-.525.075-1.133.16-1.787.231a.85.85 0 0 1-.182-1.69c.622-.067 1.204-.15 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.haxo4um8e {
  d: path("M6.464 14.727a1.383 1.383 0 1 0 0-2.766a1.383 1.383 0 0 0 0 2.766");
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i-c7amj6z {
  stop-color: var(--svg-color--9f6394, #9F6394);
  stop-opacity: 0;
}

.i4tarebhh {
  d: path("M16.309 12.959a1.1 1.1 0 0 0-.298-.596l-.335.367l.151.294z");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.il834qa_s {
  d: path("M5.922 11.718h.016l-.013-.341l-.013-.394c.026-1.222.74-1.695 1.043-1.853l.066-.026l.066-.026a2.97 2.97 0 0 0 1.532-1.59l.105-.25a.34.34 0 0 1 .595-.065a4.97 4.97 0 0 0 4.106 2.154h4.146c.232 0 1.394.113 1.463 1.716L18.88 15c-.159 3.608-2.977 6.031-6.417 6.031S6.208 18.608 6.048 15z");
}

.iwh2gc0_v {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.552 11.611c.84 0 1.551.58 1.744 1.364a.353.353 0 0 1-.344.438h-2.873a.296.296 0 0 1-.293-.35a1.8 1.8 0 0 1 1.766-1.452");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.ja5shnp0m {
  cx: 9.314px;
  cy: 12.452px;
  rx: 0.502px;
  ry: 0.254px;
}

.jc2cbvyjw {
  stop-color: var(--svg-color--886658, #886658);
  stop-opacity: 0;
}

.jgp2uobfz {
  stop-color: var(--svg-color--87505e, #87505E);
  stop-opacity: 0;
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jxpyyfjtn {
  fill: var(--svg-color--bd9679, #BD9679);
  d: path("M25.66 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.873-.095 1.181-.192c.243-.077.5-.219.96-.306c.917-.102 1.759-.206 2.234-.308a.825.825 0 1 0-.345-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.493.05");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kj63bk6ym {
  stop-color: var(--svg-color--8d67cd, #8D67CD);
}

.kl_jetb4k {
  d: path("m11.98 12.88l-.684 2.188c-.14.45.196.9.67.9h1.013c.475 0 .81-.457.67-.9l-.684-2.189c-.146-.485-.83-.485-.984 0");
}

.kptn98y8b {
  stop-color: var(--svg-color--613ea5, #613EA5);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.l57p2o49o {
  stop-color: var(--svg-color--97577d, #97577D);
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

.ll4a91bdg {
  stop-color: var(--svg-color--835857, #835857);
}

.lmvunqbvz {
  stop-color: var(--svg-color--cba68f, #CBA68F);
  stop-opacity: 0;
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhdrkkbes {
  d: path("M18.689 15.416a2.072 2.072 0 1 0 0-4.144a2.072 2.072 0 0 0 0 4.144");
}

.mowoigbtu {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M11.003 12.612c-.342-.602-.862-1.076-1.98-1.076c-.49 0-.962.135-1.381.474c-.346.28-.3.638-.032.772l.716.409c.84-.272 1.767-.308 2.677-.58");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n-9oslbsi {
  stop-color: var(--svg-color--a681e6, #A681E6);
  stop-opacity: 0;
}

.n8wh5fbks {
  fill: var(--svg-color--553836, #553836);
  d: path("M11.696 3.313c-1.458-.322-2.768 1.133-2.919 1.672c1.354 4.565 4.781 4.315 8.164 3.94c2.025-.226 2.244.697 2.417 1.143c0-5.064-4.306-6.014-7.625-6.747z");
}

.na9-zpgzs {
  stop-color: var(--svg-color--a97976, #A97976);
}

.ndb61xwjr {
  stop-color: var(--svg-color--97577d, #97577D);
  stop-opacity: 0;
}

.nmcs74byh {
  stop-color: var(--svg-color--9f6394, #9F6394);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.oc3fsgi2c {
  stop-color: var(--svg-color--ffca38, #FFCA38);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ow11_7b9u {
  stop-color: var(--svg-color--a681e6, #A681E6);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.ozqavabwo {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m17.278 10.466l-.178.296za.345.345 0 0 1-.355.592l-.006-.003l-.028-.016l-.117-.059a4 4 0 0 0-.441-.174c-.374-.12-.867-.209-1.38-.118a.345.345 0 1 1-.12-.68c.66-.117 1.272 0 1.71.14a4 4 0 0 1 .719.307l.012.007l.004.003z");
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p82q4v34p {
  stop-color: var(--svg-color--9f77e5, #9F77E5);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prklqobcj {
  stop-color: var(--svg-color--8e6bd1, #8E6BD1);
}

.q4i1lqbnd {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.97 10.29c.416-.102 1.449-.051 2.139.443");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qt4ap0b2z {
  stop-color: var(--svg-color--503876, #503876);
}

.qutvv9byr {
  cx: 9.314px;
  cy: 12.452px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.502px;
  ry: 0.254px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3osmtbwz {
  fill-rule: evenodd;
  d: path("M30.294 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693a27 27 0 0 0 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.razeofbhj {
  stop-color: var(--svg-color--956f58, #956F58);
}

.rk72x724k {
  stop-color: var(--svg-color--87505e, #87505E);
}

.rmvpd4mhh {
  d: path("M20.207 19.043a.8.8 0 0 1 .8-.8h4.79a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.rtamvw1ka {
  stop-color: var(--svg-color--e4b833, #E4B833);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.s8lp15btp {
  stop-color: var(--svg-color--c29e83, #C29E83);
}

.sipuclb6i {
  stop-color: var(--svg-color--7c65a2, #7C65A2);
}

.sm_jwybta {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m11.98 12.88l-.684 2.188c-.14.45.196.9.67.9h1.013c.475 0 .81-.457.67-.9l-.684-2.189c-.146-.485-.83-.485-.984 0");
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.su4gzg9-j {
  stop-color: var(--svg-color--604789, #604789);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t2xo9ubxq {
  fill: var(--svg-color--bd9679, #BD9679);
  fill-rule: evenodd;
  d: path("M30.294 14.51a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693a27 27 0 0 0 2.552-.383l.459-.084a.85.85 0 0 1 .984.69");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tj0ua4-4q {
  d: path("M21.349 15.789h4.015v2.016h-4.015z");
}

.tnzljqbeq {
  stop-color: var(--svg-color--cba68f, #CBA68F);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u1zz4n4nv {
  stop-color: var(--svg-color--c9a38d, #C9A38D);
  stop-opacity: 0;
}

.u2cg76bkx {
  fill-rule: evenodd;
  d: path("M29.716 14.181a.85.85 0 0 1-.69.985a21 21 0 0 0-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.317-.38q.39-.083.716-.142a.85.85 0 0 1 .985.69");
}

.u2odskbna {
  d: path("M6.44 15.416a2.072 2.072 0 1 0 0-4.144a2.072 2.072 0 0 0 0 4.144");
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

.us1b95zkc {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m8.098 11.055l-.005.003h-.001a.346.346 0 0 1-.355-.592h.001l.001-.001l.004-.003l.012-.007a3 3 0 0 1 .192-.098c.126-.06.307-.138.528-.209c.437-.14 1.05-.257 1.71-.14a.345.345 0 1 1-.12.68c-.514-.09-1.007-.001-1.38.118a3.5 3.5 0 0 0-.587.249");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.utztfdimk {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M18.689 14.727a1.383 1.383 0 1 0 0-2.766a1.383 1.383 0 0 0 0 2.766");
}

.v-pv693fm {
  stop-color: var(--svg-color--ffca38, #FFCA38);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.ve5hsjbem {
  fill: var(--svg-color--000, #000);
  d: path("M14.627 13.11c0-.365.293-.658.658-.658a.655.655 0 0 1 .585.961h-1.164a.6.6 0 0 1-.079-.303");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vm8azdt3q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.667 16.363c.85-.058 3.032-.263 4.973-.624");
}

.vp91edbxh {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m11.968 13.058l-.88 2.188c-.14.45.195.901.67.901h1.012c.475 0 .81-.457.67-.9l-.684-2.19c-.146-.484-.635-.484-.788 0");
}

.vpw_4kyku {
  d: path("M5.946 5.634c.728-.772 2.107-.773 2.744-.658l.51 1.662c-.326-.05-.381-.002-.625.235c-.178 1.407-1.773 2.262-3.717 2.83c-.191-1.921.14-3.065 1.088-4.07");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vxsyxybal {
  d: path("M25.66 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.177-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.873-.095 1.181-.192c.243-.077.5-.219.96-.306c.917-.102 1.759-.206 2.234-.308a.825.825 0 1 0-.345-1.614c-.37.08-1.053.167-1.874.26l-.203-1.363c-.161.014-.31.03-.493.05");
}

.w_ole4b0t {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M13.944 12.612c.341-.602.86-1.076 1.98-1.076c.489 0 .96.135 1.38.474c.347.28.3.638.032.772l-.716.409c-.839-.272-1.767-.308-2.676-.58");
}

.w-ygdhhti {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.666 16.605a.25.25 0 0 0-.302.053a.24.24 0 0 0-.025.301a2.537 2.537 0 0 0 4.268 0a.24.24 0 0 0-.026-.303a.25.25 0 0 0-.3-.051h-.001a3.8 3.8 0 0 1-1.807.438c-.663 0-1.285-.16-1.807-.438Z");
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
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

.weadzoqrn {
  stop-color: var(--svg-color--8d67cd, #8D67CD);
  stop-opacity: 0;
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

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x9prdyaoh {
  d: path("M22.121 13.876c-.554.648-.74 1.417-.761 1.758l1.847-.102l.887-1.183c.29-.383.54-1.02-.035-1.442c-.466-.342-.946-.066-1.102.106a28 28 0 0 0-.836.863");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xy2mpdbhe {
  stop-color: var(--svg-color--6c4da8, #6C4DA8);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.ycqdlkbeq {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M5.946 5.634c.728-.772 2.107-.773 2.744-.658l.51 1.662c-.326-.05-.381-.002-.625.235c-.178 1.407-1.773 2.262-3.717 2.83c-.191-1.921.14-3.065 1.088-4.07");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zou-tybqy {
  stop-color: var(--svg-color--ab876c, #AB876C);
}

.zxu2ysp1r {
  d: path("M21.106 17.548a.25.25 0 0 1 .25-.25h4.093a.25.25 0 0 1 .25.25v1.64h-4.593z");
}

</style>
