<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iE68rCc)"><path class="n2ljw7bum"/></g><path fill="url(#iT4BEec)" class="yjs_1lmgw"/><g filter="url(#iy63Ore)"><path fill="url(#ilFKzlc)" class="wrjncmbvl"/></g><g filter="url(#i9bo3ue)"><path stroke="url(#i77yBdc)" class="j27_zub1v"/></g><g filter="url(#i2aKAad)"><path stroke="url(#ibZ2sCe)" class="wqoser8ru"/></g><g filter="url(#ipAwuvc)"><path stroke="url(#iMq826c)" class="r_n1v7r5p"/></g><g filter="url(#iGOlUte)"><path fill="url(#iRztRQc)" class="m275xhwfx"/><path fill="url(#iLm1vdd)" class="m275xhwfx"/><path fill="url(#iK8Tinb)" class="m275xhwfx"/></g><path fill="url(#iyHOuOc)" class="vgjfbsb7l"/><path fill="url(#i7VBsyx)" class="vgjfbsb7l"/><path fill="url(#iH2NTle)" class="vgjfbsb7l"/><path fill="url(#iE3xHuc)" class="vgjfbsb7l"/><g filter="url(#iKVYrQc)"><rect class="txp88d1_z"/><rect fill="url(#iNKFmde)" class="uc68slbrm"/></g><g filter="url(#ixojwIe)"><path fill="url(#imyDoTc)" class="i9c-eob6c"/><path fill="url(#ieCLF6d)" class="i9c-eob6c"/><path fill="url(#i6UTi5W)" class="i9c-eob6c"/></g><g filter="url(#iFwjA6b)"><path fill="url(#i6lgGWd)" class="cv_2u2b1j"/><path fill="url(#ifpKcgd)" class="cv_2u2b1j"/><path fill="url(#iQoAQxc)" class="cv_2u2b1j"/><path fill="url(#iitSWMb)" class="cv_2u2b1j"/><path fill="url(#iqsuJnm)" class="cv_2u2b1j"/></g><path fill="url(#i7LS4Hc)" class="nid47tbzi"/><path fill="url(#iqK3Q4b)" class="nid47tbzi"/><path fill="url(#itQ1Tyd)" class="nid47tbzi"/><path fill="url(#iWzWLLb)" class="nid47tbzi"/><path fill="url(#iOIELYc)" class="dxbw9fmxo"/><path fill="url(#i7yxCOp)" class="dxbw9fmxo"/><g filter="url(#iqxZyJc)"><path fill="url(#isu8Aqc)" class="t06-rzbwx"/><path fill="url(#i20eIBe)" class="t06-rzbwx"/><path fill="url(#i2Mutue)" class="t06-rzbwx"/></g><path fill="url(#iH6JE3c)" class="jqtbx6bdj"/><path fill="url(#irmEBLd)" class="jqtbx6bdj"/><path fill="url(#i6tfqok)" class="jqtbx6bdj"/><path fill="url(#i2nnCUr)" class="jqtbx6bdj"/><g filter="url(#ihfGO2d)"><path stroke="url(#iv0YjMe)" class="doky60syc"/></g><g filter="url(#if6Y3jV)"><path stroke="url(#iekjRMb)" class="t1qofdbri"/></g><g filter="url(#iv3lGpc)"><path fill="url(#iuS78cd)" class="uxmx_b5qt"/></g><g filter="url(#iNmzalK)"><path stroke="url(#icAMA8b)" class="h8f39p-0t"/></g><g filter="url(#iIhVOMd)"><path stroke="url(#iTqnyxe)" class="ilhx4zbpd"/></g><g filter="url(#iTY5KId)"><path stroke="url(#iDO4QVy)" class="jt0iaf2nr"/></g><g filter="url(#iE1pL8b)"><circle fill="url(#i6ULGNe)" class="k8f-b6tly"/></g><g filter="url(#im1HLNe)"><circle fill="url(#iDfSz4c)" class="df0eo_byv"/></g><g filter="url(#iJMfxSc)"><circle fill="url(#ii3IUPc)" class="rq16spb6n"/><circle fill="url(#i4yLCie)" class="rq16spb6n"/></g><g filter="url(#izFpLLd)"><circle class="qzqmwo46e"/><circle fill="url(#iIJUmEb)" class="bh6f89byw"/><circle fill="url(#iR0Tyic)" class="bh6f89byw"/></g><g filter="url(#ih7dGlb)"><path fill="url(#iXobnXc)" class="h0pezzb4t"/><path fill="url(#iyaiANb)" class="h0pezzb4t"/><path fill="url(#iEfjmjz)" class="h0pezzb4t"/><path fill="url(#i55Ebfb)" class="h0pezzb4t"/><path fill="url(#iCcRsAe)" class="h0pezzb4t"/><path fill="url(#igZM0qv)" class="h0pezzb4t"/></g><g filter="url(#izkLKce)"><path fill="url(#iD7DRpP)" class="zhz7llmuh"/></g><g filter="url(#ilkYdod)"><path class="ynn79me_v"/><path fill="url(#iMQXNbb)" class="kw6ccvhnj"/><path fill="url(#iIxz2jb)" class="kw6ccvhnj"/><path fill="url(#i4LthLb)" class="kw6ccvhnj"/><path fill="url(#ib0nhUi)" class="kw6ccvhnj"/></g><g filter="url(#inTD7ub)"><path class="c0j4z7x4c"/></g><g filter="url(#iDwEt2c)"><path class="zrq257m0n"/><path fill="url(#iAF2eMd)" class="uotkb3-yl"/><path fill="url(#iqwoNrb)" class="uotkb3-yl"/><path fill="url(#iDOofNb)" class="uotkb3-yl"/><path fill="url(#igOGpZd)" class="uotkb3-yl"/></g><path stroke="url(#itx8Zfb)" class="l0mey06vx"/><g filter="url(#iGFJo1i)"><path class="j9kccbb3k"/></g><g filter="url(#iI9ydEc)"><path class="bnmi0jbyn"/></g><path class="vw0r--b4a"/><path fill="url(#iRzgEoc)" class="y_66wxvct"/><path class="kwq24xrzi"/><g filter="url(#iHP8qEb)"><path class="vacnm89zp"/><path fill="url(#iYHVHUc)" class="ga1jnhb0w"/></g><g filter="url(#iBFRpcb)"><path fill="url(#ilhZW0d)" class="o_79i76cm"/></g><path class="ddlxeb9xu"/><path fill="url(#i8akAHJ)" class="acx3wxb5i"/><path class="kwkhc9bqp"/><g filter="url(#iLoA0Tb)"><path fill="url(#iwI1iwc)" class="gnxfttbkz"/></g><g filter="url(#i4980hc)"><ellipse transform="rotate(-27.914 13.431 6.532)" class="zx29jrbqo"/><ellipse fill="url(#i2onmee)" transform="rotate(-27.914 13.431 6.532)" class="npl8uhbaw"/></g><g filter="url(#iQzugvd)"><path stroke="url(#is6Llqe)" class="xrch4ccua"/></g><g filter="url(#iUyZ8cd)"><path stroke="url(#iQ8yTOc)" class="acvm8_bqb"/></g><g filter="url(#ihHJoYc)"><path stroke="url(#iuEAovc)" class="mj-xq2bve"/></g><defs><radialGradient id="iT4BEec" cx="0" cy="0" r="1" gradientTransform="matrix(12.502 -3.897 4.76721 15.29373 8.201 25.12)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="ilFKzlc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 20.046 20.648)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iRztRQc" cx="0" cy="0" r="1" gradientTransform="matrix(7.75852 4.4892 -3.11118 5.37693 16.862 11.13)" gradientUnits="userSpaceOnUse"><stop class="zk2hbubsr"/><stop offset="1" class="qduh4yb_v"/></radialGradient><radialGradient id="iLm1vdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.09374 2.54688 -.87207 .71691 17.692 13.742)" gradientUnits="userSpaceOnUse"><stop class="c4-zm246s"/><stop offset="1" class="tyhrgacfx"/></radialGradient><radialGradient id="iK8Tinb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92188 -.83495 0 24.395 14.851)" gradientUnits="userSpaceOnUse"><stop class="r-3jeabjq"/><stop offset="1" class="zq-itunnh"/><stop offset="1" class="d62u3bbpg"/></radialGradient><radialGradient id="iyHOuOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.5273 1.08984 0 24.823 29.968)" gradientUnits="userSpaceOnUse"><stop class="vj07kubhl"/><stop offset="1" class="keqz-8g7v"/></radialGradient><radialGradient id="i7VBsyx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -17.8945 2.43359 0 24.823 28.336)" gradientUnits="userSpaceOnUse"><stop offset=".906" class="sy7qt-bzl"/><stop offset="1" class="i8gxpdlwn"/></radialGradient><radialGradient id="iH2NTle" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.3125 -1.10912 0 24.823 15.836)" gradientUnits="userSpaceOnUse"><stop class="ti8dkw8jh"/><stop offset="1" class="uw8wenb6w"/></radialGradient><radialGradient id="iNKFmde" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31815 0 0 -1.07813 26.163 9.882)" gradientUnits="userSpaceOnUse"><stop class="jk8wwdkvh"/><stop offset="1" class="kt1qsbbol"/></radialGradient><radialGradient id="imyDoTc" cx="0" cy="0" r="1" gradientTransform="rotate(108.771 12.726 11.781)scale(5.04985 5.80366)" gradientUnits="userSpaceOnUse"><stop class="l1mhifosa"/><stop offset="1" class="nwr0ulaka"/></radialGradient><radialGradient id="ieCLF6d" cx="0" cy="0" r="1" gradientTransform="matrix(2 8.14203 -5.28875 1.29912 23.35 2.1)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="tfpize5dt"/><stop offset="1" class="udxjy24sj"/></radialGradient><radialGradient id="i6UTi5W" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 1 -.64044 -.57039 23.148 2.398)" gradientUnits="userSpaceOnUse"><stop offset=".048" class="ozaj1r-nb"/><stop offset="1" class="pkl3f-q-p"/></radialGradient><radialGradient id="ifpKcgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25757 0 0 -.32031 26.255 15.52)" gradientUnits="userSpaceOnUse"><stop class="y3_83ydue"/><stop offset="1" class="dc-06s26c"/></radialGradient><radialGradient id="iQoAQxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06226 0 0 -.27056 26.255 14.718)" gradientUnits="userSpaceOnUse"><stop class="y3_83ydue"/><stop offset="1" class="dc-06s26c"/></radialGradient><radialGradient id="iitSWMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.97632 0 0 -.27344 26.255 13.992)" gradientUnits="userSpaceOnUse"><stop class="y3_83ydue"/><stop offset="1" class="dc-06s26c"/></radialGradient><radialGradient id="iqsuJnm" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17944 0 0 -.28906 26.255 13.218)" gradientUnits="userSpaceOnUse"><stop class="y3_83ydue"/><stop offset="1" class="dc-06s26c"/></radialGradient><radialGradient id="iqK3Q4b" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.28098 -1.58159 .34725 23.942 12.67)" gradientUnits="userSpaceOnUse"><stop class="fy0ejufsy"/><stop offset="1" class="cb6451bsk"/></radialGradient><radialGradient id="itQ1Tyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 0 0 -1 25.63 13.843)" gradientUnits="userSpaceOnUse"><stop class="fmkv8wb6f"/><stop offset="1" class="hezodxunz"/></radialGradient><radialGradient id="iWzWLLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -.9375 .74865 -.02496 24.27 14.492)" gradientUnits="userSpaceOnUse"><stop class="yuxw77bqf"/><stop offset="1" class="u2hnt4brx"/></radialGradient><radialGradient id="iOIELYc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -.26562 .64937 1.60434 4.241 16.757)" gradientUnits="userSpaceOnUse"><stop class="m94_fabps"/><stop offset="1" class="i49u8-0rl"/></radialGradient><radialGradient id="isu8Aqc" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3.1875 1.21246 2.63887 4.726 16.21)" gradientUnits="userSpaceOnUse"><stop class="iq11kgb3w"/><stop offset="1" class="pnk2q80jk"/></radialGradient><radialGradient id="i20eIBe" cx="0" cy="0" r="1" gradientTransform="rotate(138.102 3.516 9.17)scale(4.49229 1.70257)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="rf8so6s6c"/><stop offset="1" class="h37qa-b9r"/></radialGradient><radialGradient id="i2Mutue" cx="0" cy="0" r="1" gradientTransform="rotate(-179.561 6.573 5.161)scale(2.03912 1.41902)" gradientUnits="userSpaceOnUse"><stop class="ihfloop4h"/><stop offset="1" class="nsqwfwb_x"/></radialGradient><radialGradient id="iH6JE3c" cx="0" cy="0" r="1" gradientTransform="matrix(.78907 8.61887 -5.42589 .49675 18.155 11.748)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="jq9e5d-ak"/><stop offset="1" class="uky5yo4fu"/></radialGradient><radialGradient id="irmEBLd" cx="0" cy="0" r="1" gradientTransform="matrix(.3615 4.948 -2.46163 .17985 11.008 14.73)" gradientUnits="userSpaceOnUse"><stop class="gl6q2fbez"/><stop offset="1" class="rwgvkoy3b"/></radialGradient><radialGradient id="i6tfqok" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -1.8125 4.2981 10.67113 13.52 14.539)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="p_qw0-dft"/><stop offset="1" class="wma2t5r-c"/></radialGradient><radialGradient id="i2nnCUr" cx="0" cy="0" r="1" gradientTransform="matrix(-3.34375 1.37499 -.66249 -1.61107 15.255 9.685)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="vswdc-2rm"/><stop offset="1" class="ul7gy9rza"/></radialGradient><radialGradient id="iuS78cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 .23438 -.46507 -.83711 25.304 2.828)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nvk-74bwn"/><stop offset="1" class="f1ri06bus"/></radialGradient><radialGradient id="iDO4QVy" cx="0" cy="0" r="1" gradientTransform="matrix(4.84376 2.56248 -.9379 1.77288 19.114 12.82)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="hvtacgb4z"/><stop offset="1" class="p8sjifbbs"/></radialGradient><radialGradient id="i6ULGNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.00956 0 0 1.76674 11.152 6.98)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="i4yLCie" cx="0" cy="0" r="1" gradientTransform="matrix(.4756 -.3463 .39527 .54283 17.8 6.827)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iIJUmEb" cx="0" cy="0" r="1" gradientTransform="matrix(.47247 -.869 .50863 .27654 17.562 7.452)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iR0Tyic" cx="0" cy="0" r="1" gradientTransform="matrix(.14917 .14765 -.19034 .1923 17.585 6.98)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iyaiANb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.42806 -7.3683 0 14.86 5.872)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="iCcRsAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.75196 .92548 0 16.194 6.248)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="igZM0qv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.80016 .99507 0 13.571 6.229)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iMQXNbb" cx="0" cy="0" r="1" gradientTransform="matrix(.45898 -1.70092 .63076 .1702 17.343 4.618)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iIxz2jb" cx="0" cy="0" r="1" gradientTransform="matrix(2.2004 .2025 -.10888 1.18314 16.399 3.605)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i4LthLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96602 -1.49609 0 14.844 2.032)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="ib0nhUi" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 14.666 -14.037)scale(2.19244 3.43483)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="igOGpZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11328 -.36393 0 15.032 7.904)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iRzgEoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46664 -.74224 0 16.098 6.587)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iYHVHUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13339 -.1719 .23665 -.18365 15.966 6.636)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8akAHJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46666 -.74228 0 13.588 6.587)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i2onmee" cx="0" cy="0" r="1" gradientTransform="matrix(-.00445 -.28418 .3416 -.00535 13.422 6.714)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iE68rCc" width="16.97" height="13.626" x="4.983" y="16.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1304" result="effect2_innerShadow_4002_1304"/></filter><filter id="iy63Ore" width="8.803" height="12.453" x="12.427" y="15.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".5"/></filter><filter id="i9bo3ue" width="11.112" height="3.615" x="8.173" y="25.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".2"/></filter><filter id="i2aKAad" width="3.297" height="3.17" x="5.589" y="23.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".2"/></filter><filter id="ipAwuvc" width="3.085" height="3.032" x="8.851" y="23.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".2"/></filter><filter id="iGOlUte" width="8.453" height="6.378" x="16.55" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.8"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.662745 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.517647 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1304" result="effect2_innerShadow_4002_1304"/></filter><filter id="iKVYrQc" width="2.963" height="1.158" x="23.363" y="9.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.541176 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="ixojwIe" width="8.438" height="7.533" x="20.669" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.517647 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="iFwjA6b" width="1.765" height="3.013" x="24.69" y="13.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.572549 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="iqxZyJc" width="10.053" height="7.208" x="2.993" y="10.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.517647 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="ihfGO2d" width="2.209" height="5.708" x="26.777" y="3.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".1"/></filter><filter id="if6Y3jV" width="1.759" height="1.3" x="26.569" y="2.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".1"/></filter><filter id="iv3lGpc" width="1.189" height="1.345" x="24.572" y="2.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".1"/></filter><filter id="iNmzalK" width="2.586" height="5.952" x="24.656" y="3.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".1"/></filter><filter id="iIhVOMd" width="2.948" height="6.859" x="20.962" y="2.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".1"/></filter><filter id="iTY5KId" width="7.3" height="3.894" x="17.558" y="11.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".3"/></filter><filter id="iE1pL8b" width="2.121" height="1.921" x="11.152" y="6.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="im1HLNe" width="2.145" height="2.145" x="11.04" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".25"/></filter><filter id="iJMfxSc" width="2.171" height="2.171" x="16.625" y="5.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="izFpLLd" width="2.145" height="2.145" x="16.513" y="5.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".25"/></filter><filter id="ih7dGlb" width="5.968" height="7.17" x="11.877" y="3.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="izkLKce" width="6.443" height="5.764" x="12.942" y="1.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation="1"/></filter><filter id="ilkYdod" width="7.25" height="5.127" x="11.219" y="1.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="inTD7ub" width="2.513" height="3.042" x="13.45" y="5.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".375"/></filter><filter id="iDwEt2c" width="1.28" height="1.742" x="14.204" y="6.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".05"/></filter><filter id="iGFJo1i" width="1.82" height="1.247" x="15.524" y="4.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="iI9ydEc" width="1.82" height="1.247" x="12.563" y="4.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1304"/></filter><filter id="iHP8qEb" width=".538" height=".486" x="15.633" y="6.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".05"/></filter><filter id="iBFRpcb" width=".683" height=".695" x="16.073" y="6.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".1"/></filter><filter id="iLoA0Tb" width=".737" height=".768" x="13.518" y="6.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".1"/></filter><filter id="i4980hc" width=".61" height=".49" x="13.126" y="6.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".05"/></filter><filter id="iQzugvd" width="1.464" height=".648" x="15.599" y="5.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".075"/></filter><filter id="iUyZ8cd" width="1.509" height=".681" x="12.597" y="5.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".075"/></filter><filter id="ihHJoYc" width=".898" height="1.624" x="11.713" y="3.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1304" stdDeviation=".125"/></filter><linearGradient id="i77yBdc" x1="9.112" x2="18.219" y1="27.046" y2="28.889" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ibZ2sCe" x1="7.862" x2="5.547" y1="25.839" y2="25.467" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iMq826c" x1="11.357" x2="10.826" y1="24.177" y2="26.286" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iE3xHuc" x1="25.417" x2="25.113" y1="20.679" y2="20.679" gradientUnits="userSpaceOnUse"><stop class="y_8gxtivd"/><stop offset="1" class="rtj1uebvi"/></linearGradient><linearGradient id="i6lgGWd" x1="25.472" x2="25.472" y1="13.218" y2="16.031" gradientUnits="userSpaceOnUse"><stop class="j0tdmnb4r"/><stop offset="1" class="q1w2v7mcl"/></linearGradient><linearGradient id="i7LS4Hc" x1="24.195" x2="25.702" y1="13.951" y2="13.951" gradientUnits="userSpaceOnUse"><stop offset=".342" class="mmywztbhc"/><stop offset="1" class="qujzk4b-u"/></linearGradient><linearGradient id="i7yxCOp" x1="4.021" x2="4.289" y1="16.859" y2="16.835" gradientUnits="userSpaceOnUse"><stop class="mcxasqd9p"/><stop offset="1" class="m0mxk2b4m"/></linearGradient><linearGradient id="iv0YjMe" x1="27.226" x2="28.976" y1="3.679" y2="9.414" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="iekjRMb" x1="27.437" x2="27.067" y1="2.812" y2="3.028" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset="1" class="msr886b7s"/></linearGradient><linearGradient id="icAMA8b" x1="25.17" x2="27.718" y1="3.765" y2="13.135" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="iTqnyxe" x1="21.517" x2="24.201" y1="3.146" y2="13.697" gradientUnits="userSpaceOnUse"><stop class="luqq4ccam"/><stop offset=".765" class="msr886b7s"/></linearGradient><linearGradient id="iDfSz4c" x1="12.112" x2="11.744" y1="7.14" y2="7.14" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="ii3IUPc" x1="18.21" x2="17.739" y1="6.352" y2="7.811" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iXobnXc" x1="17.166" x2="12.772" y1="7.204" y2="7.859" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="iEfjmjz" x1="11.598" x2="13.53" y1="8.082" y2="8.148" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="i55Ebfb" x1="11.74" x2="12.822" y1="8.755" y2="8.716" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iD7DRpP" x1="14.538" x2="19.223" y1="5.487" y2="3.809" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iAF2eMd" x1="14.347" x2="14.886" y1="7.583" y2="7.583" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iqwoNrb" x1="15.384" x2="14.794" y1="7.769" y2="7.76" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iDOofNb" x1="14.956" x2="14.956" y1="8.196" y2="7.866" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="itx8Zfb" x1="14.247" x2="14.498" y1="9.125" y2="8.729" gradientUnits="userSpaceOnUse"><stop class="ld2xxcbwz"/><stop offset=".663" class="hukqombqg"/></linearGradient><linearGradient id="ilhZW0d" x1="16.545" x2="16.364" y1="6.618" y2="6.73" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwI1iwc" x1="14.015" x2="13.835" y1="6.618" y2="6.73" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="is6Llqe" x1="16.554" x2="16.312" y1="5.387" y2="4.893" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iQ8yTOc" x1="13.502" x2="12.818" y1="5.314" y2="5.027" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iuEAovc" x1="12.162" x2="12.162" y1="4.155" y2="5.396" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-merpeople-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.acvm8_bqb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.797 5.63c.188-.166.599-.341 1.108-.26");
}

.acx3wxb5i {
  d: path("M13.586 6.313a.513.513 0 0 0-.494.649h.991a.517.517 0 0 0-.497-.649");
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bh6f89byw {
  cx: 17.585px;
  cy: 6.98px;
  r: 0.572px;
}

.bnmi0jbyn {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.673 5.415l.002-.001l.003-.003l.006-.005a1 1 0 0 1 .09-.062a1.63 1.63 0 0 1 1.1-.212a.307.307 0 0 1-.096.606a1.02 1.02 0 0 0-.678.126l-.032.022l-.005.003a.307.307 0 0 1-.39-.474");
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.c0j4z7x4c {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m14.686 6.91l-.472.977c-.059.201.082.402.28.402h.425c.198 0 .339-.204.28-.402l-.286-.978c-.062-.216-.163-.216-.228 0");
}

.c4-zm246s {
  stop-color: var(--svg-color--d69585, #D69585);
}

.cb6451bsk {
  stop-color: var(--svg-color--dca58d, #DCA58D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cv_2u2b1j {
  d: path("M25.256 13.218a.34.34 0 0 0-.338.338v.019c0 .128.072.24.178.297c.017.01.017.04 0 .049a.34.34 0 0 0-.178.297v.019c0 .13.073.242.18.298c.007.004.005.015-.003.015a.405.405 0 0 0-.143.785c.019.007.022.04.005.052a.349.349 0 0 0 .186.644h.762a.35.35 0 0 0 .2-.636c-.035-.024-.041-.109-.01-.136a.404.404 0 0 0-.036-.634c-.026-.019-.022-.081.005-.097a.34.34 0 0 0 .166-.291v-.019a.34.34 0 0 0-.168-.292c-.026-.015-.029-.065-.005-.082a.34.34 0 0 0 .133-.27v-.018a.34.34 0 0 0-.338-.338z");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d62u3bbpg {
  stop-color: var(--svg-color--c87c71, #C87C71);
  stop-opacity: 0;
}

.dc-06s26c {
  stop-color: var(--svg-color--faceb7, #FACEB7);
  stop-opacity: 0;
}

.ddlxeb9xu {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.467 6.157a.8.8 0 0 0-.78.609c-.025.1.052.196.155.196h1.283a.132.132 0 0 0 .13-.157a.806.806 0 0 0-.788-.648");
}

.df0eo_byv {
  cx: 12.112px;
  cy: 6.98px;
  r: 0.572px;
}

.doky60syc {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M27.077 3.43c0 .382.117.882.602 1.452c.669.788 1.008 1.22 1.008 1.844c0 .399-.118 1.305-1.008 1.93");
}

.dxbw9fmxo {
  d: path("M4.022 16.009a.517.517 0 0 1 1.033-.063l.052.87a.517.517 0 0 1-1.033.062z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.f1ri06bus {
  stop-color: var(--svg-color--f2be56, #F2BE56);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fmkv8wb6f {
  stop-color: var(--svg-color--ffd1ba, #FFD1BA);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fy0ejufsy {
  stop-color: var(--svg-color--dca58d, #DCA58D);
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.ga1jnhb0w {
  d: path("M16.06 6.422c.038.049-.039.108-.126.173s-.151.111-.188.062c-.036-.049.004-.141.091-.206s.187-.078.224-.03");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gl6q2fbez {
  stop-color: var(--svg-color--d39b89, #D39B89);
}

.gnxfttbkz {
  d: path("M14.055 6.766c0-.166-.135-.276-.171-.31l-.166.16l.102.208z");
}

.h0pezzb4t {
  d: path("M11.877 5.8c0-.154.061-.338.185-.43l.092-.092a.61.61 0 0 0 .216-.49v-.492a.3.3 0 0 1 .247-.307c.37-.092 1.142-.245 2.253-.245c1.11 0 1.882.153 2.252.245a.33.33 0 0 1 .247.307v.491c0 .184.093.368.216.491c.29.203.271.314.247.552c-.03.307-.062.829-.062.829h.01l-.152 2.277c-.092 1.018-.893 1.728-1.847 1.728h-1.847c-.985 0-1.754-.71-1.847-1.728c-.08-1.045-.115-2.093-.21-3.136");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h37qa-b9r {
  stop-color: var(--svg-color--d09084, #D09084);
  stop-opacity: 0;
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.h8f39p-0t {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M24.96 3.507v4.22c-.026.213.05.798.625 1.085c.575.288 1.211.078 1.422 0");
}

.hezodxunz {
  stop-color: var(--svg-color--ffd1ba, #FFD1BA);
  stop-opacity: 0;
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hukqombqg {
  stop-color: var(--svg-color--e4b1a2, #E4B1A2);
  stop-opacity: 0;
}

.hvtacgb4z {
  stop-color: var(--svg-color--ffcfb6, #FFCFB6);
}

.i49u8-0rl {
  stop-color: var(--svg-color--c78065, #C78065);
}

.i8gxpdlwn {
  stop-color: var(--svg-color--d6803e, #D6803E);
}

.i9c-eob6c {
  d: path("m24.646 2.201l-.753 1.02a.2.2 0 0 0 .163.318l.21-.002a.15.15 0 0 1 .152.15v3.856a1 1 0 0 1-1 1h-.032c-.902 0-1.538-.625-1.71-1.228c-.105-.37-.112-.645-.033-.906c.082-.27.275-.58.67-.983c.862-.882.866-1.887.87-3.02v-.04a.15.15 0 0 0-.243-.117l-1.3 1.025a.15.15 0 0 0 .092.268h.37c.085 0 .153.071.137.155a2.13 2.13 0 0 1-.584 1.086c-.446.456-.75.889-.892 1.358c-.146.48-.109.944.028 1.425a2.76 2.76 0 0 0 2.661 1.967h2.772a2.76 2.76 0 0 0 2.661-1.967c.137-.481.175-.945.029-1.425c-.143-.469-.447-.902-.892-1.358a2.14 2.14 0 0 1-.585-1.086c-.015-.084.053-.155.138-.155h.37a.15.15 0 0 0 .092-.268l-1.3-1.025a.15.15 0 0 0-.243.118v.04c.004 1.132.008 2.137.87 3.019c.395.404.587.713.67.983c.079.261.072.536-.034.906c-.171.603-.798 1.228-1.776 1.228a.95.95 0 0 1-.951-.952V3.678a.15.15 0 0 1 .148-.15l.213-.002a.2.2 0 0 0 .159-.32l-.745-1.005a.25.25 0 0 0-.402 0");
}

.ihfloop4h {
  stop-color: var(--svg-color--d7987b, #D7987B);
}

.ilhx4zbpd {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.953 2.586c0 .984-.058 1.818-.946 2.718c-1.11 1.125-.686 2.145-.562 2.422c.226.508.812 1.219 2.265 1.219");
}

.iq11kgb3w {
  stop-color: var(--svg-color--eab6a4, #EAB6A4);
}

.j0tdmnb4r {
  stop-color: var(--svg-color--f6c7ab, #F6C7AB);
}

.j27_zub1v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.773 26.94c-.007.65.436 1.949 2.266 1.949h3.177c1.01-.014 3.317-.517 4.469-2.415");
}

.j9kccbb3k {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m16.984 5.415l-.002-.001l-.002-.003l-.007-.005a1 1 0 0 0-.09-.062a1.63 1.63 0 0 0-1.1-.212a.307.307 0 1 0 .096.606a1.02 1.02 0 0 1 .679.126l.036.025a.307.307 0 0 0 .39-.474");
}

.jk8wwdkvh {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jq9e5d-ak {
  stop-color: var(--svg-color--ffccb3, #FFCCB3);
}

.jqtbx6bdj {
  d: path("M12.966 10.445c-.475.528-1.424 2.02-1.424 3.764v3.051c0 .359.291.65.65.65h5.314a.65.65 0 0 0 .65-.65v-3.051c0-1.744-.95-3.236-1.424-3.764z");
}

.jt0iaf2nr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m18.458 12.445l1.884 1.942a.5.5 0 0 0 .359.152h3.257");
}

.k8f-b6tly {
  cx: 12.113px;
  cy: 6.98px;
  r: 0.96px;
}

.keqz-8g7v {
  stop-color: var(--svg-color--e49c45, #E49C45);
}

.kt1qsbbol {
  stop-color: var(--svg-color--ebaf51, #EBAF51);
  stop-opacity: 0;
}

.kw6ccvhnj {
  d: path("m17.616 3.253l.247.123c.432.215.679.706.586 1.227l-.34 1.75c-.03.18-.149.301-.328.306h-.01s.03-.522.061-.828c.025-.25-.018-.326-.247-.553a.72.72 0 0 1-.216-.49v-.492a.33.33 0 0 0-.247-.306c-.37-.092-1.141-.246-2.252-.246s-1.883.154-2.253.246a.3.3 0 0 0-.247.306v.491a.61.61 0 0 1-.216.491l-.092.092c-.124.092-.186.276-.186.43c.031.337.062.828.062.828h-.028a.364.364 0 0 1-.342-.306l-.34-1.75c-.061-.49.186-.981.617-1.196l.247-.123c.155-.092.309-.215.463-.337l.556-.583c.34-.307.833-.4 1.265-.184c.309.092.648.092.957 0a1.39 1.39 0 0 1 1.357.306l.463.46c.124.154.278.246.463.338");
}

.kwkhc9bqp {
  fill: var(--svg-color--000, #000);
  d: path("M13.88 6.826a.293.293 0 0 0-.294-.294a.293.293 0 0 0-.261.43h.52a.3.3 0 0 0 .035-.136");
}

.kwq24xrzi {
  fill: var(--svg-color--000, #000);
  d: path("M15.805 6.826c0-.163.13-.294.294-.294a.293.293 0 0 1 .261.43h-.52a.3.3 0 0 1-.035-.136");
}

.l0mey06vx {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.07 8.547c.223.117.49.184.774.184c.287 0 .55-.067.774-.184a.14.14 0 0 1 .164.027a.13.13 0 0 1 .014.165m-1.726-.192l1.685.165m-1.685-.165a.14.14 0 0 0-.164.028a.13.13 0 0 0-.014.165m.178-.193l-.137.165m1.863.027l-.041-.027m.041.027l-.041-.027m.041.027a1.14 1.14 0 0 1-.952.51c-.4 0-.75-.204-.952-.51m1.863-.027a1.09 1.09 0 0 1-.911.486c-.382 0-.718-.194-.91-.486m-.042.028l.041-.028m-.041.028l.041-.028");
}

.l1mhifosa {
  stop-color: var(--svg-color--f0b438, #F0B438);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ld2xxcbwz {
  stop-color: var(--svg-color--e4b1a2, #E4B1A2);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.luqq4ccam {
  stop-color: var(--svg-color--f6c059, #F6C059);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m0mxk2b4m {
  stop-color: var(--svg-color--d79583, #D79583);
  stop-opacity: 0;
}

.m275xhwfx {
  d: path("m20.646 13.364l-2.182-2.114c-.68-.61-1.46-.703-1.914-.836l.946 3.59c.218.184.953.847 1.585 1.453c.579.488 1.254.535 1.61.535h4.312v-2.125c-.426-.06-2.951-.279-4.12-.393a.4.4 0 0 1-.237-.11");
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m94_fabps {
  stop-color: var(--svg-color--d59583, #D59583);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcxasqd9p {
  stop-color: var(--svg-color--efb9a5, #EFB9A5);
}

.mj-xq2bve {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.236 4.212v.516c-.004.086-.04.277-.148.358");
}

.mmywztbhc {
  stop-color: var(--svg-color--eebca2, #EEBCA2);
}

.msr886b7s {
  stop-color: var(--svg-color--f6c059, #F6C059);
  stop-opacity: 0;
}

.n2ljw7bum {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M10.7 19.168c0-1.425.76-2.102 1.16-2.243l5.66-.34c1.61.72 2.954 2.782 3.141 5.282c.188 2.5-.203 4.953-2.265 6.562c-1.65 1.288-3.959 1.552-4.938 1.532h-2.472c-2.625 0-3.246-1.891-3.356-2.297a11 11 0 0 0-.184-.599a.43.43 0 0 0-.221-.26c-.528-.243-1.52-.486-1.946-1.387a3.1 3.1 0 0 1-.28-1.63c.021-.214.231-.344.44-.297c.52.12.95.253 1.57.567a3.4 3.4 0 0 1 1.237 1.227c.065.11.238.111.304.002c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.766-.747 2.275-1.198 2.513c-.288.132-.62.278-.865.388c-.14.063-.209.224-.141.36c.474.957 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.723c-.063-1.813-1.563-2.516-2.57-3.149c-.524-.328-2.055-1.144-2.055-2.925");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nid47tbzi {
  d: path("M24.808 13.027h-.5c-.53 0-.779.382-.887.863l.848.266l.042-.177a.1.1 0 0 1 .11-.076l.2.027c.078.01.136.078.136.156v.316a.473.473 0 0 0 .945 0v-.453c0-.258-.027-.461-.304-.692a1 1 0 0 0-.59-.23");
}

.npl8uhbaw {
  cx: 13.431px;
  cy: 6.532px;
  rx: 0.224px;
  ry: 0.113px;
}

.nsqwfwb_x {
  stop-color: var(--svg-color--d7987b, #D7987B);
  stop-opacity: 0;
}

.nvk-74bwn {
  stop-color: var(--svg-color--f2be56, #F2BE56);
}

.nwr0ulaka {
  stop-color: var(--svg-color--f0a23f, #F0A23F);
}

.o_79i76cm {
  d: path("M16.556 6.759a.5.5 0 0 0-.133-.266l-.15.164l.068.13z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ozaj1r-nb {
  stop-color: var(--svg-color--f1c057, #F1C057);
}

.p_qw0-dft {
  stop-color: var(--svg-color--ffc7ad, #FFC7AD);
  stop-opacity: 0;
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
}

.p8sjifbbs {
  stop-color: var(--svg-color--ffcfb6, #FFCFB6);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkl3f-q-p {
  stop-color: var(--svg-color--f1c057, #F1C057);
  stop-opacity: 0;
}

.pnk2q80jk {
  stop-color: var(--svg-color--e8b3a0, #E8B3A0);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q1w2v7mcl {
  stop-color: var(--svg-color--dfa89d, #DFA89D);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qduh4yb_v {
  stop-color: var(--svg-color--e9b79e, #E9B79E);
}

.qujzk4b-u {
  stop-color: var(--svg-color--f2bea2, #F2BEA2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzqmwo46e {
  cx: 17.585px;
  cy: 6.98px;
  r: 0.572px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.r_n1v7r5p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.336 23.986c-.308.353-1.133 1.101-1.885 1.832");
}

.r-3jeabjq {
  stop-color: var(--svg-color--c87c71, #C87C71);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rf8so6s6c {
  stop-color: var(--svg-color--d09084, #D09084);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rq16spb6n {
  cx: 17.585px;
  cy: 6.98px;
  r: 0.96px;
}

.rtj1uebvi {
  stop-color: var(--svg-color--e69440, #E69440);
  stop-opacity: 0;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rwgvkoy3b {
  stop-color: var(--svg-color--dfaa99, #DFAA99);
  stop-opacity: 0;
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sy7qt-bzl {
  stop-color: var(--svg-color--d6803e, #D6803E);
  stop-opacity: 0;
}

.t06-rzbwx {
  d: path("M10.933 11.367c.775-.75 1.746-.925 2.113-.914v4.054h-1.422c-.112-.13-.218-.09-.258-.054c-.502.424-1.62 1.372-2.07 1.765c-.45.394-1.208.498-1.531.5H6.13a.4.4 0 0 0-.273.108l-.472.44a.537.537 0 0 1-.748-.769l.358-.363a.102.102 0 0 0-.022-.161l-.068-.038a.32.32 0 0 0-.391.058l-.65.68a.506.506 0 0 1-.754-.674l.788-.944a.8.8 0 0 1 .518-.28l3.203-.37a.3.3 0 0 0 .172-.08c.758-.72 2.284-2.198 3.142-2.958");
}

.t1qofdbri {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m26.827 2.593l.993.72h-.72");
}

.tfpize5dt {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
}

.ti8dkw8jh {
  stop-color: var(--svg-color--d77735, #D77735);
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.txp88d1_z {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.533px;
  fill: var(--svg-color--eca63f, #ECA63F);
  rx: 0.454px;
}

.tyhrgacfx {
  stop-color: var(--svg-color--d69585, #D69585);
  stop-opacity: 0;
}

.u2hnt4brx {
  stop-color: var(--svg-color--b9746f, #B9746F);
  stop-opacity: 0;
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.uc68slbrm {
  width: 2.963px;
  height: 0.908px;
  x: 23.363px;
  y: 9.533px;
  rx: 0.454px;
}

.udxjy24sj {
  stop-color: var(--svg-color--ebad2f, #EBAD2F);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uky5yo4fu {
  stop-color: var(--svg-color--e7b2a1, #E7B2A1);
}

.ul7gy9rza {
  stop-color: var(--svg-color--ce8b72, #CE8B72);
  stop-opacity: 0;
}

.uotkb3-yl {
  d: path("m14.624 6.816l-.306.977a.31.31 0 0 0 .3.403h.452a.31.31 0 0 0 .3-.403l-.306-.977c-.066-.217-.371-.217-.44 0");
}

.uw8wenb6w {
  stop-color: var(--svg-color--d77735, #D77735);
  stop-opacity: 0;
}

.uxmx_b5qt {
  d: path("m25.562 3.234l-.617-.945l-.173.945z");
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.vacnm89zp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.06 6.422c.038.049-.039.108-.126.173s-.151.111-.188.062c-.036-.049.004-.141.091-.206s.187-.078.224-.03");
}

.vgjfbsb7l {
  d: path("M24.359 10.441h.93v19.377a.15.15 0 0 1-.15.15h-.63a.15.15 0 0 1-.15-.15z");
}

.vj07kubhl {
  stop-color: var(--svg-color--f8a33e, #F8A33E);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vswdc-2rm {
  stop-color: var(--svg-color--b46c54, #B46C54);
}

.vw0r--b4a {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.218 6.157c.375 0 .693.259.779.609a.158.158 0 0 1-.154.196H15.56a.132.132 0 0 1-.131-.157a.804.804 0 0 1 .789-.648");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wma2t5r-c {
  stop-color: var(--svg-color--ffc7ad, #FFC7AD);
}

.wqoser8ru {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.189 24.505c.41.162 1.402.783 2.097 1.97");
}

.wrjncmbvl {
  d: path("M18.661 26.742c0-5.344-3.922-7.969-5.234-9l3.25-1.453c1.125.52 3.035 2.357 3.453 5.11c.485 3.187-.927 4.926-1.469 5.343");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xrch4ccua {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.8 5.332c.247-.044.73-.031 1.063.229");
}

.y_66wxvct {
  d: path("M16.099 6.313a.513.513 0 0 1 .494.649h-.991a.515.515 0 0 1 .497-.649");
}

.y_8gxtivd {
  stop-color: var(--svg-color--cc802a, #CC802A);
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y3_83ydue {
  stop-color: var(--svg-color--faceb7, #FACEB7);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yjs_1lmgw {
  d: path("M10.7 19.168c0-1.425.76-2.102 1.16-2.243l5.66-.34c1.61.72 2.954 2.782 3.141 5.282c.188 2.5-.203 4.953-2.265 6.562c-1.65 1.288-3.959 1.552-4.938 1.532h-2.472c-2.625 0-3.246-1.891-3.356-2.297a11 11 0 0 0-.184-.599a.43.43 0 0 0-.221-.26c-.528-.243-1.52-.486-1.946-1.387a3.1 3.1 0 0 1-.28-1.63c.021-.214.231-.344.44-.297c.52.12.95.253 1.57.567a3.4 3.4 0 0 1 1.237 1.227c.065.11.238.111.304.002c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.766-.747 2.275-1.198 2.513c-.288.132-.62.278-.865.388c-.14.063-.209.224-.141.36c.474.957 1.468.87 2.858.87c1.851 0 2.96-1.325 2.844-2.723c-.063-1.813-1.563-2.516-2.57-3.149c-.524-.328-2.055-1.144-2.055-2.925");
}

.ynn79me_v {
  fill: var(--svg-color--242324, #242324);
  d: path("m17.616 3.253l.247.123c.432.215.679.706.586 1.227l-.34 1.75c-.03.18-.149.301-.328.306h-.01s.03-.522.061-.828c.025-.25-.018-.326-.247-.553a.72.72 0 0 1-.216-.49v-.492a.33.33 0 0 0-.247-.306c-.37-.092-1.141-.246-2.252-.246s-1.883.154-2.253.246a.3.3 0 0 0-.247.306v.491a.61.61 0 0 1-.216.491l-.092.092c-.124.092-.186.276-.186.43c.031.337.062.828.062.828h-.028a.364.364 0 0 1-.342-.306l-.34-1.75c-.061-.49.186-.981.617-1.196l.247-.123c.155-.092.309-.215.463-.337l.556-.583c.34-.307.833-.4 1.265-.184c.309.092.648.092.957 0a1.39 1.39 0 0 1 1.357.306l.463.46c.124.154.278.246.463.338");
}

.yuxw77bqf {
  stop-color: var(--svg-color--b9746f, #B9746F);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zhz7llmuh {
  d: path("m17.124 3.744l-1.77.59a.602.602 0 0 0 .27 1.169l1.76-.236z");
}

.zk2hbubsr {
  stop-color: var(--svg-color--fec9b0, #FEC9B0);
}

.zq-itunnh {
  stop-color: var(--svg-color--c28177, #C28177);
  stop-opacity: 0;
}

.zrq257m0n {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m14.624 6.816l-.306.977a.31.31 0 0 0 .3.403h.452a.31.31 0 0 0 .3-.403l-.306-.977c-.066-.217-.371-.217-.44 0");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zx29jrbqo {
  cx: 13.431px;
  cy: 6.532px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.224px;
  ry: 0.113px;
}

</style>
