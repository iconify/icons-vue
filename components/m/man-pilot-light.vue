<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#iMvTABe)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="umfrftwnu"/><path fill="url(#iqdGPbc)" class="umfrftwnu"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#imxr95F)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#izUhOOc)"><path class="yqf7_qb9p"/></g><path fill="url(#ii5h9Zd)" class="q9zrzf44o"/><g filter="url(#i5BfB3d)"><path class="ya3ebpr_n"/></g><g filter="url(#i69BDob)"><path fill="url(#iMm4Ddd)" class="d8vxffbru"/><path fill="url(#ideVytc)" class="d8vxffbru"/><path fill="url(#iNjTTxJ)" class="d8vxffbru"/></g><path fill="url(#iXFEZTd)" class="d8vxffbru"/><g filter="url(#iyLUeDd)"><path class="e463lyb9n"/></g><g filter="url(#iP6ruCc)"><path fill="url(#itFU7Nd)" class="fc6zhkb0f"/><path fill="url(#ipIpBme)" class="fc6zhkb0f"/></g><path fill="url(#iq5GnHe)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#i03SEAe)" class="gael-ox4b"/><path fill="url(#i56uO1c)" class="gael-ox4b"/><g filter="url(#iYrtqTc)"><path fill="url(#i6qOhPd)" class="qckr5_bvx"/></g><g filter="url(#ip9yupc)"><circle fill="url(#idMNeBe)" class="qiuvc6bvd"/></g><g filter="url(#iRWuMIe)"><circle fill="url(#iubswNb)" class="s4kxvck1a"/></g><g filter="url(#iB04zQy)"><circle fill="url(#izItKXR)" class="t8u5wytke"/><circle fill="url(#iomZNqe)" class="t8u5wytke"/></g><g filter="url(#izhVa4b)"><circle class="rtp1x1-jh"/><circle fill="url(#inkWwje)" class="jk5tdbk2k"/><circle fill="url(#ieQAcCc)" class="jk5tdbk2k"/></g><g filter="url(#ipQ6nMn)"><path fill="url(#ia5l5tm)" class="nsanav3_p"/><path fill="url(#i6ygb3b)" class="nsanav3_p"/><path fill="url(#isE7Csd)" class="nsanav3_p"/><path fill="url(#ijav8un)" class="nsanav3_p"/><path fill="url(#iF9GKXc)" class="nsanav3_p"/><path fill="url(#iyay85u)" class="nsanav3_p"/><path fill="url(#i4hCUtd)" class="nsanav3_p"/></g><g filter="url(#iHya20r)"><path class="u5cwzs33r"/></g><g filter="url(#i2RpdKc)"><path class="xvi75lbhm"/><path fill="url(#iJeoSPc)" class="w438u6biz"/><path fill="url(#iLjS9db)" class="w438u6biz"/><path fill="url(#iyX1JOe)" class="w438u6biz"/><path fill="url(#iCLw5hW)" class="w438u6biz"/><path fill="url(#iOrrhzc)" class="w438u6biz"/></g><g filter="url(#iGKMete)"><path stroke="url(#i7a0eBw)" class="zb7wgfb8v"/></g><path class="kwe53e2_o"/><path class="y-3_rtb1n"/><path fill="url(#ih7FL0d)" class="ypn2iubpd"/><path class="bku3z2bpr"/><g filter="url(#ii4neEd)"><path class="rewwskbaf"/><path fill="url(#i5E0Elb)" class="uh7lwyaiy"/></g><g filter="url(#iJ7X63g)"><path fill="url(#iq6D1Pb)" class="di_3nybew"/></g><path class="ha02ucrke"/><path fill="url(#i9O5ILz)" class="yqpxhwbch"/><path class="wvywwz6cx"/><g filter="url(#iswst1d)"><path fill="url(#ie69ENX)" class="t20laobfb"/></g><g filter="url(#ioMz5Xc)"><ellipse transform="rotate(-27.914 13.541 9.782)" class="vlom-obrs"/><ellipse fill="url(#il7mfOc)" transform="rotate(-27.914 13.541 9.782)" class="k24icpb3s"/></g><g filter="url(#iJvJeUd)"><path class="wuuxbrbut"/><path fill="url(#iK9ogCc)" class="wt9b0xbck"/><path fill="url(#i5mbBBB)" class="wt9b0xbck"/><path fill="url(#iNNF8rd)" class="wt9b0xbck"/><path fill="url(#iEoPjlc)" class="wt9b0xbck"/></g><g filter="url(#iOBnxud)"><path fill="url(#iMNODVc)" class="tttp4x6mw"/></g><g filter="url(#iPOXJOb)"><path class="iz2_smy4d"/></g><g filter="url(#i2U3wSd)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#im41Hle)" class="wb9snib6m"/><path fill="url(#iik2bBb)" class="wb9snib6m"/><path fill="url(#iNQcnJd)" class="wb9snib6m"/><g filter="url(#igSndde)"><path fill="url(#iorGERc)" class="ywpgx-8qy"/></g><path fill="url(#iJIPMLc)" class="d43ioubeg"/><path fill="url(#iUbYlyc)" class="d43ioubeg"/><path fill="url(#iEHuhpd)" class="d43ioubeg"/><g filter="url(#iNs4MPb)"><path class="ho8k-2bnl"/></g><g filter="url(#ijaghxe)"><path fill="url(#iNlblBe)" class="wes-0ybwy"/><path fill="url(#i18Wkwz)" class="wes-0ybwy"/></g><g filter="url(#iMShRBd)"><path fill="url(#iYqfV7X)" class="hdde0uvpo"/></g><g filter="url(#iw7opdc)"><path fill="url(#iRal8Sb)" class="yi-thdc0w"/></g><path fill="url(#izWDMkb)" class="yi-thdc0w"/><defs><radialGradient id="iMvTABe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.403)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="ii5h9Zd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.99 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="ipIpBme" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.868)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="iq5GnHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="adgho6gps"/><stop offset="1" class="p81iumb5r"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="i6qOhPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.41287 -1.9196 0 16.005 17.153)" gradientUnits="userSpaceOnUse"><stop class="tuc4ddckg"/><stop offset="1" class="gn-9dlbjr"/></radialGradient><radialGradient id="idMNeBe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 9.58 10.56)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iomZNqe" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.133 10.295)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="inkWwje" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.72 11.38)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ieQAcCc" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.459 30.523)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="i6ygb3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.43448 -12.8068 0 16.025 8.635)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="ko7f8cc6s"/><stop offset=".899" class="cbmmvvbyn"/></radialGradient><radialGradient id="iF9GKXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.342 9.288)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iyay85u" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.784 9.255)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="i4hCUtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.47176 -4.26578 0 15.385 8.227)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="oj__bjnwj"/><stop offset="1" class="rmj27hbsh"/></radialGradient><radialGradient id="iCLw5hW" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.323 12.166)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="ih7FL0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.175 9.878)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i5E0Elb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.947 9.962)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9O5ILz" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.812 9.878)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="il7mfOc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.733 -1.61)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iK9ogCc" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.79367 1.08842 .31112 20.334 6.65)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="i5mbBBB" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .33258 -.16897 1.94502 18.69 4.988)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iNNF8rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.58663 -2.60303 0 15.985 2.403)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iEoPjlc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07686 -2.12852 3.27241 4.7304 9.53 8.846)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="im41Hle" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.485 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iik2bBb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.798 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iNQcnJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.38 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iorGERc" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.263 -3.831)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iUbYlyc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.099 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iEHuhpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.099 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="i18Wkwz" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.675 -1.206)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iRal8Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.583 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="izWDMkb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.88 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><filter id="izUhOOc" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".5"/></filter><filter id="i5BfB3d" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".5"/></filter><filter id="i69BDob" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2472" result="effect2_innerShadow_4002_2472"/></filter><filter id="iyLUeDd" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".5"/></filter><filter id="iP6ruCc" width="3.042" height="14.123" x="18.465" y="15.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2472" result="effect2_innerShadow_4002_2472"/></filter><filter id="iYrtqTc" width="3.989" height="1.699" x="13.935" y="16.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.415686 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><filter id="ip9yupc" width="3.539" height="3.339" x="9.58" y="8.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><filter id="iRWuMIe" width="2.99" height="2.99" x="9.754" y="9.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".25"/></filter><filter id="iB04zQy" width="3.589" height="3.589" x="19.092" y="8.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><filter id="izhVa4b" width="2.99" height="2.99" x="19.266" y="9.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".25"/></filter><filter id="ipQ6nMn" width="10.373" height="12.277" x="10.839" y="4.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><filter id="iHya20r" width="3.26" height="4.181" x="14.127" y="9.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".375"/></filter><filter id="i2RpdKc" width="2.377" height="3.181" x="14.808" y="9.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".125"/></filter><filter id="iGKMete" width="3.617" height="1.472" x="14.188" y="13.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".05"/></filter><filter id="ii4neEd" width=".787" height=".696" x="17.441" y="9.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".05"/></filter><filter id="iJ7X63g" width=".891" height=".913" x="18.281" y="9.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".1"/></filter><filter id="iswst1d" width=".986" height="1.04" x="13.839" y="9.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".1"/></filter><filter id="ioMz5Xc" width=".913" height=".704" x="13.085" y="9.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".05"/></filter><filter id="iJvJeUd" width="12.614" height="8.1" x="9.678" y="1.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><filter id="iOBnxud" width="2.735" height="2.58" x="14.632" y="18.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2472" result="effect2_innerShadow_4002_2472"/></filter><filter id="iPOXJOb" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".1"/></filter><filter id="i2U3wSd" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2472" result="effect2_innerShadow_4002_2472"/></filter><filter id="igSndde" width="10.9" height="2.77" x="10.555" y="6.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><filter id="iNs4MPb" width="4.831" height="2.64" x="13.59" y="2.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2472" stdDeviation=".125"/></filter><filter id="ijaghxe" width="2.293" height="1.21" x="13.861" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><filter id="iMShRBd" width="2.298" height="1.22" x="15.944" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><filter id="iw7opdc" width="1.63" height="1.63" x="15.295" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2472"/></filter><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="imxr95F" x1="9.135" x2="6.942" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iXFEZTd" x1="13.295" x2="13.295" y1="29.69" y2="23.356" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="i03SEAe" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="ovo1ps97q"/><stop offset="1" class="k5-d0pb7l"/><stop offset="1" class="mrezdm8zl"/></linearGradient><linearGradient id="i56uO1c" x1="18.818" x2="17.747" y1="18.66" y2="18.66" gradientUnits="userSpaceOnUse"><stop class="k3yv484oe"/><stop offset="1" class="gi8--rb6p"/></linearGradient><linearGradient id="iubswNb" x1="11.249" x2="10.608" y1="10.838" y2="10.838" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="izItKXR" x1="21.848" x2="21.029" y1="9.468" y2="12.004" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="ia5l5tm" x1="20.032" x2="12.396" y1="10.949" y2="12.087" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="isE7Csd" x1="10.354" x2="13.712" y1="12.476" y2="12.59" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="ijav8un" x1="10.601" x2="12.482" y1="13.645" y2="13.578" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iJeoSPc" x1="15.132" x2="16.07" y1="11.608" y2="11.608" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iLjS9db" x1="16.935" x2="15.909" y1="11.931" y2="11.916" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iyX1JOe" x1="16.191" x2="16.191" y1="12.673" y2="12.1" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iOrrhzc" x1="15.996" x2="15.943" y1="9.992" y2="10.962" gradientUnits="userSpaceOnUse"><stop class="a1-xcu3rx"/><stop offset="1" class="zz08j3bgt"/></linearGradient><linearGradient id="i7a0eBw" x1="14.959" x2="15.394" y1="14.288" y2="13.601" gradientUnits="userSpaceOnUse"><stop class="it9bz-b_p"/><stop offset=".663" class="wle36ubdh"/></linearGradient><linearGradient id="iq6D1Pb" x1="18.953" x2="18.639" y1="9.932" y2="10.125" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ie69ENX" x1="14.556" x2="14.242" y1="9.932" y2="10.125" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="iJIPMLc" x1="17.349" x2="11.13" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset="1" class="ayzgumbov"/></linearGradient><linearGradient id="iNlblBe" x1="16.091" x2="14.513" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iYqfV7X" x1="18.083" x2="16.597" y1="3.169" y2="4.16" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-pilot-light" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a1-xcu3rx {
  stop-color: var(--svg-color--dba69b, #DBA69B);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.adgho6gps {
  stop-color: var(--svg-color--c9c0d4, #C9C0D4);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.bku3z2bpr {
  fill: var(--svg-color--000, #000);
  d: path("M17.666 10.293c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.06-.235");
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

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.cbmmvvbyn {
  stop-color: var(--svg-color--bb7399, #BB7399);
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d43ioubeg {
  d: path("M15.955 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d8vxffbru {
  d: path("M13.295 15.837q-.691.176-1.345.435l-.035.019l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.di_3nybew {
  d: path("M18.972 10.176a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e463lyb9n {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.479l.444 1.05c.202.26.272.65.178 1.01l-1.295 4.645l-.22-10.445l.09-.183q.508.173.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fc6zhkb0f {
  d: path("m19.865 19.79l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V16.05l.117-.182q.653.173 1.272.423l1.26 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.gael-ox4b {
  d: path("M16.005 15.284h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gi8--rb6p {
  stop-color: var(--svg-color--9c92a5, #9C92A5);
  stop-opacity: 0;
}

.gn-9dlbjr {
  stop-color: var(--svg-color--c88898, #C88898);
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.ha02ucrke {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.604 9.129c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.hdde0uvpo {
  d: path("M16.098 4.24h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.ho8k-2bnl {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.793 4.352h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.475a.8.8 0 0 0-.415.005l-.272-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.it9bz-b_p {
  stop-color: var(--svg-color--e7b3a8, #E7B3A8);
}

.iz2_smy4d {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.612c-.22 0-.42.13-.515.329c-.01.02-.039.02-.039 0a.57.57 0 0 0-.515-.33h-.592c-.125 0-.23.09-.24.22s.096.25.22.25h.153c.18 0 .18.079.213.149c.057.12.172.2.306.2h.238l.54.128c.133 0 .46-.099.518-.219l.086-.199a.1.1 0 0 1 .095-.06h.144c.124 0 .229-.09.238-.219c-.01-.14-.114-.25-.238-.25");
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.jk5tdbk2k {
  cx: 20.761px;
  cy: 10.56px;
  r: 0.995px;
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.k24icpb3s {
  cx: 13.541px;
  cy: 9.782px;
  rx: 0.389px;
  ry: 0.197px;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k3yv484oe {
  stop-color: var(--svg-color--665c72, #665C72);
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.ko7f8cc6s {
  stop-color: var(--svg-color--d496a2, #D496A2);
  stop-opacity: 0;
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.kwe53e2_o {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.996 13.69c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.846c.086-.13-.06-.279-.198-.209c-.4.21-.872.329-1.385.329");
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mrezdm8zl {
  stop-color: var(--svg-color--4e4852, #4E4852);
  stop-opacity: 0;
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.nsanav3_p {
  d: path("M10.839 8.509c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.534c.644-.16 1.984-.426 3.915-.426s3.272.266 3.916.426c.214.054.429.267.429.534v.853c0 .32.16.64.375.853c.502.352.47.545.43.96c-.054.533-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003c-.14-1.816-.2-3.638-.366-5.451");
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.oj__bjnwj {
  stop-color: var(--svg-color--bc8287, #BC8287);
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.ovo1ps97q {
  stop-color: var(--svg-color--4e4852, #4E4852);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p81iumb5r {
  stop-color: var(--svg-color--6d6675, #6D6675);
}

.pj095ubna {
  stop-color: var(--svg-color--635870, #635870);
  stop-opacity: 0;
}

.pk_fxjb0k {
  stop-color: var(--svg-color--6e658c, #6E658C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q9zrzf44o {
  d: path("M15.517 21.044a.25.25 0 0 0-.247.212l-1.335 8.745h4.12l-1.33-8.745a.25.25 0 0 0-.247-.212z");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qckr5_bvx {
  d: path("M16.005 18.445c1.789-.788 1.932-1.316 1.919-1.7h-3.838c-.013.384.224.97 1.919 1.7");
}

.qg2z49_rr {
  stop-color: var(--svg-color--564973, #564973);
}

.qga7xqb8q {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
}

.qiuvc6bvd {
  cx: 11.249px;
  cy: 10.56px;
  r: 1.669px;
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rewwskbaf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.111 9.59c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.388-.05");
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rmj27hbsh {
  stop-color: var(--svg-color--b98183, #B98183);
  stop-opacity: 0;
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.rtp1x1-jh {
  cx: 20.761px;
  cy: 10.56px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s4kxvck1a {
  cx: 11.249px;
  cy: 10.56px;
  r: 0.995px;
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.t20laobfb {
  d: path("M14.625 10.188c0-.288-.234-.48-.297-.538l-.289.278l.178.361z");
}

.t8u5wytke {
  cx: 20.761px;
  cy: 10.56px;
  r: 1.669px;
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tttp4x6mw {
  d: path("m14.732 19.661l1.267-1.097l1.268 1.074l-.546 1.265a.24.24 0 0 1-.217.141h-1.021a.24.24 0 0 1-.216-.141z");
}

.tuc4ddckg {
  stop-color: var(--svg-color--bc7693, #BC7693);
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.u5cwzs33r {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.72 10.438l-.82 1.699c-.101.35.143.7.489.7h.737c.346 0 .59-.356.488-.7l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.uh7lwyaiy {
  d: path("M18.111 9.59c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.388-.05");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.umfrftwnu {
  d: path("M23.13 18.124V30h3.865v-3.5c0-3.357-1.5-6.36-3.865-8.377");
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vlom-obrs {
  cx: 13.541px;
  cy: 9.782px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.w438u6biz {
  d: path("m15.614 10.274l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wb9snib6m {
  d: path("M21.747 3.55c-2.66-1.66-5.7-1.55-5.74-1.55s-3.14-.01-5.74 1.54c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wes-0ybwy {
  d: path("M16.045 4.24h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wle36ubdh {
  stop-color: var(--svg-color--e7b3a8, #E7B3A8);
  stop-opacity: 0;
}

.wt9b0xbck {
  d: path("m20.808 4.408l.43.2a1.826 1.826 0 0 1 1.02 2.014l-.59 2.87a.6.6 0 0 1-.596.512c.035-.476.077-1.25.09-1.371c.043-.41-.01-.53-.408-.903c-.214-.202-.375-.504-.375-.806V6.12c0-.252-.215-.453-.43-.503c-.644-.151-1.986-.403-3.92-.403c-1.932 0-3.274.252-3.919.403a.5.5 0 0 0-.43.503v.805c0 .302-.107.604-.375.806c-.283.243-.464.327-.464.837c.014.147.066 1.023.09 1.375c-.3-.02-.595-.214-.646-.5l-.59-2.87a1.9 1.9 0 0 1 1.073-1.963c1.015-.42 1.384-1.056 2.201-1.712a2.06 2.06 0 0 1 2.202-.302a3.1 3.1 0 0 0 1.664 0a2.52 2.52 0 0 1 2.362.504l.806.755c.215.252.483.403.805.554");
}

.wuuxbrbut {
  fill: var(--svg-color--242324, #242324);
  d: path("m20.808 4.408l.43.2a1.826 1.826 0 0 1 1.02 2.014l-.59 2.87a.6.6 0 0 1-.596.512c.035-.476.077-1.25.09-1.371c.043-.41-.01-.53-.408-.903c-.214-.202-.375-.504-.375-.806V6.12c0-.252-.215-.453-.43-.503c-.644-.151-1.986-.403-3.92-.403c-1.932 0-3.274.252-3.919.403a.5.5 0 0 0-.43.503v.805c0 .302-.107.604-.375.806c-.283.243-.464.327-.464.837c.014.147.066 1.023.09 1.375c-.3-.02-.595-.214-.646-.5l-.59-2.87a1.9 1.9 0 0 1 1.073-1.963c1.015-.42 1.384-1.056 2.201-1.712a2.06 2.06 0 0 1 2.202-.302a3.1 3.1 0 0 0 1.664 0a2.52 2.52 0 0 1 2.362.504l.806.755c.215.252.483.403.805.554");
}

.wvywwz6cx {
  fill: var(--svg-color--000, #000);
  d: path("M14.321 10.293a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.905a.5.5 0 0 0 .06-.235");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xvi75lbhm {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.614 10.274l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.y-3_rtb1n {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.384 9.13c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ya3ebpr_n {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.27c-.54.784-1.546 2.2-1.85 2.874c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.894 6.334z");
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.yi-thdc0w {
  d: path("M16.085 5.16a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.ypn2iubpd {
  d: path("M18.177 9.401a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.yqf7_qb9p {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.005 15.348h-2.516v4.74c0 .31.335.49.567.29l1.949-1.67l1.95 1.67c.231.2.566.02.566-.29v-4.74z");
}

.yqpxhwbch {
  d: path("M13.81 9.4a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.ywpgx-8qy {
  d: path("M16.005 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
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

.zb7wgfb8v {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.996 13.69c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.846c.086-.13-.06-.279-.198-.209c-.4.21-.872.329-1.385.329Z");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zz08j3bgt {
  stop-color: var(--svg-color--dba69b, #DBA69B);
  stop-opacity: 0;
}

</style>
