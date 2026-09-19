<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuyRCtc)" class="ad6zenl5p"/><path fill="url(#iwPHmHc)" class="ad6zenl5p"/><path fill="url(#iEv1z7b)" class="ad6zenl5p"/><path fill="url(#ig2uhxd)" class="ad6zenl5p"/><path fill="url(#iAFkfSb)" class="ad6zenl5p"/><path fill="url(#iaUjSoe)" class="ubraf2bsa"/><path fill="url(#iTlj5Ce)" class="ubraf2bsa"/><path class="kp7cfduip"/><path fill="url(#ihJj5Db)" class="d0i-qonjb"/><path fill="url(#iQPaFqb)" class="d0i-qonjb"/><path class="tkc4hvb0d"/><path fill="url(#iWh4s0d)" class="ai325kb6x"/><path fill="url(#irWxKOa)" class="ai325kb6x"/><g filter="url(#ihUvYZd)"><circle fill="url(#iKEF2fe)" class="xee17_bfa"/></g><circle fill="url(#i7tGxec)" class="xee17_bfa"/><g filter="url(#i6HPBrb)"><circle fill="url(#ibvrjVc)" class="wb4a9hbls"/></g><g filter="url(#ijeEdXo)"><circle fill="url(#iGdTgue)" class="qeqnj6bwc"/><circle fill="url(#iLnWQMe)" class="qeqnj6bwc"/></g><g filter="url(#iuJp0Ss)"><circle class="wj347g5uq"/><circle fill="url(#iJgwg7h)" class="njc_4fbku"/><circle fill="url(#i94Grdz)" class="njc_4fbku"/></g><g filter="url(#iTQpXCc)"><path fill="url(#iOuhjWG)" class="yq5--pdjx"/><path fill="url(#iqxuxqe)" class="yq5--pdjx"/><path fill="url(#iMJwcwb)" class="yq5--pdjx"/></g><path fill="url(#iPe3B8d)" class="p3i1c_8gc"/><path fill="url(#ifFFOVL)" class="p3i1c_8gc"/><path fill="url(#izoDK6X)" class="p3i1c_8gc"/><g filter="url(#iV3eDeP)"><path fill="url(#iYHILlb)" class="k9b2ju7jq"/></g><g filter="url(#isj20be)"><path class="o0amu2b5i"/><path fill="url(#iVmqsQL)" class="gyqhhd_4o"/><path fill="url(#iSw79xe)" class="gyqhhd_4o"/><path fill="url(#iJnT5ee)" class="gyqhhd_4o"/><path fill="url(#iumK1Ee)" class="gyqhhd_4o"/></g><g filter="url(#i0W2ktT)"><path class="c_cuvml4y"/></g><g filter="url(#iPYH01d)"><path class="rnl91gb8n"/><path fill="url(#i4LNc9c)" class="atmzz1y4m"/><path fill="url(#iI2PDYb)" class="atmzz1y4m"/><path fill="url(#iShuGgd)" class="atmzz1y4m"/><path fill="url(#irC00pR)" class="atmzz1y4m"/></g><path stroke="url(#iD1baab)" class="y6q895bci"/><g filter="url(#igOZDtb)"><path class="qmmxotaou"/><path fill="url(#i0QupOb)" class="wlnsi_b8m"/></g><g filter="url(#iERAdyb)"><path class="ur76s4bgv"/><path fill="url(#ils1MSb)" class="hmafmcb4e"/></g><path class="xmx82cnqk"/><path fill="url(#i5zH5bd)" class="yqvz3__yv"/><path class="s8skxyn0j"/><g filter="url(#iCMjRKb)"><path class="y2kcw2b0l"/><path fill="url(#iPJlird)" class="mn5xrd5ls"/></g><g filter="url(#i1nyrSc)"><path fill="url(#iPcCnPb)" class="w457ubb8p"/></g><path class="vo905zb4s"/><path fill="url(#iTdLnCd)" class="irpiiabvl"/><path class="x_8osmbty"/><g filter="url(#iCFHThG)"><path fill="url(#iRY1qee)" class="gqkb4ibjo"/></g><g filter="url(#iwpMked)"><ellipse transform="rotate(-27.914 12.16 12.393)" class="f2r5v8bfp"/><ellipse fill="url(#iwiypTg)" transform="rotate(-27.914 12.16 12.393)" class="v6-g8enxe"/></g><g filter="url(#iLi6HEp)"><path stroke="url(#iX6qckc)" class="qg1uz5bds"/></g><g filter="url(#iQ3pp7d)"><path stroke="url(#iTHwIQc)" class="f0e9j6bsz"/></g><g filter="url(#i3sApIK)"><path stroke="url(#iPSUR3b)" class="qz5ypoujz"/></g><path fill="url(#i0I5BPd)" class="i6rcqrbyt"/><path fill="url(#ihY3HLY)" class="i6rcqrbyt"/><path fill="url(#ixn7Nrd)" class="m2no4lz0w"/><path fill="url(#iqFOvTT)" class="m2no4lz0w"/><path fill="url(#iAyumpb)" class="p_xiulv7p"/><path fill="url(#i0dpVqq)" class="p_xiulv7p"/><g filter="url(#iR39hfc)"><circle fill="url(#iuDFgAe)" class="sm84e7bem"/><circle fill="url(#ipce8Sd)" class="sm84e7bem"/><circle fill="url(#i4KKWbc)" class="sm84e7bem"/></g><g filter="url(#iN93ORb)"><path fill="url(#i3sRbOd)" clip-rule="evenodd" class="lslinwphh"/></g><path fill="url(#ivqPuuj)" clip-rule="evenodd" class="lslinwphh"/><g filter="url(#i6dZRHb)"><path fill="url(#ie1h4be)" clip-rule="evenodd" class="x8g_-0bes"/></g><g filter="url(#iw5aASb)"><circle stroke="url(#ijcJdMb)" class="yfngg9boj"/></g><g filter="url(#iqZa0Nb)"><circle stroke="url(#ibfKRzb)" class="kpfztrcsd"/></g><g filter="url(#ievskbb)"><circle stroke="url(#iTiFI5M)" class="i1-v3abff"/></g><g filter="url(#iG0t4Nb)"><circle stroke="url(#iCqanBe)" class="h9vakccdw"/></g><defs><radialGradient id="iuyRCtc" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.313 13.901)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="tet72waca"/><stop offset="1" class="bmx48tuma"/></radialGradient><radialGradient id="iwPHmHc" cx="0" cy="0" r="1" gradientTransform="rotate(-115.528 17.238 10.578)scale(12.9022 18.5657)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="rxprtfb0z"/><stop offset="1" class="m-fo0lvbc"/></radialGradient><radialGradient id="iEv1z7b" cx="0" cy="0" r="1" gradientTransform="rotate(166.984 5.946 10.215)scale(6.38273 2.1839)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="zdar40bkv"/><stop offset="1" class="cybfe7yaw"/></radialGradient><radialGradient id="ig2uhxd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.546 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="puczgzv3j"/><stop offset="1" class="mq0bii3nt"/></radialGradient><radialGradient id="iAFkfSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.24045 0 0 9.50024 7.166 29.356)" gradientUnits="userSpaceOnUse"><stop class="wke-8-xfb"/><stop offset="1" class="h-56b9bpz"/></radialGradient><radialGradient id="iaUjSoe" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.577 28.578)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="kin3dabop"/><stop offset="1" class="jlkbatyzp"/></radialGradient><radialGradient id="iTlj5Ce" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.577 29.356)" gradientUnits="userSpaceOnUse"><stop class="hos3q5hgu"/><stop offset="1" class="txm2ysbkn"/></radialGradient><radialGradient id="ihJj5Db" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.31 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="vp_-q7ldm"/><stop offset=".956" class="k-z4zg2os"/></radialGradient><radialGradient id="iQPaFqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.31 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="oxun88gow"/><stop offset="1" class="zi0iv1bfj"/></radialGradient><radialGradient id="iWh4s0d" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.7 18.991)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="uc_e6-bbg"/><stop offset="1" class="owv1xe5nh"/></radialGradient><radialGradient id="irWxKOa" cx="0" cy="0" r="1" gradientTransform="rotate(139.583 4.476 13.308)scale(2.48229 1.07513)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="on_jcmgtl"/><stop offset="1" class="stji6gbyf"/></radialGradient><radialGradient id="iKEF2fe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 8.197 13.17)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="i7tGxec" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.798 4.85)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iLnWQMe" cx="0" cy="0" r="1" gradientTransform="matrix(.82664 -.60191 .687 .9435 19.751 12.906)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iJgwg7h" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.338 13.992)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="i94Grdz" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -6.324 30.148)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iqxuxqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 16.96 11.9)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iMJwcwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 12.402 12.033)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="izoDK6X" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.32774 -10.3217 0 14.481 11.634)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="j-umvlb7c"/><stop offset="1" class="an_-aznlj"/></radialGradient><radialGradient id="iVmqsQL" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 15.397 -7.844)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iSw79xe" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -70.89 192.224)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iJnT5ee" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 14.614 4.57)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iumK1Ee" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 8.166 11.388)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="irC00pR" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 14.941 14.777)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="i0QupOb" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 17.057 11.087)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ils1MSb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 12.538 -1.528)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i5zH5bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 16.793 12.489)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iPJlird" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 16.565 12.573)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTdLnCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 12.43 12.489)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iwiypTg" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.327 .376)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0I5BPd" cx="0" cy="0" r="1" gradientTransform="rotate(152.76 11.013 5.226)scale(5.16675 4.07534)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cidorvbnk"/><stop offset=".943" class="x7utjgb1r"/></radialGradient><radialGradient id="ihY3HLY" cx="0" cy="0" r="1" gradientTransform="matrix(3.46875 .90625 -.1653 .63269 17.43 6.751)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="pkl5_wldm"/><stop offset="1" class="fy9pbzqvw"/></radialGradient><radialGradient id="iuDFgAe" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.74 7.666)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="ipce8Sd" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.594 7.347)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="i4KKWbc" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.37 6.91)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="i3sRbOd" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.397 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="ie1h4be" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.543 8.273)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="ihUvYZd" width="3.539" height="3.339" x="8.197" y="11.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/></filter><filter id="i6HPBrb" width="2.99" height="2.99" x="8.372" y="11.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".25"/></filter><filter id="ijeEdXo" width="3.589" height="3.589" x="17.71" y="11.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/></filter><filter id="iuJp0Ss" width="2.99" height="2.99" x="17.884" y="11.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".25"/></filter><filter id="iTQpXCc" width="10.373" height="12.177" x="9.457" y="7.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/></filter><filter id="iV3eDeP" width="8.246" height="7.066" x="12.784" y="5.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation="1"/></filter><filter id="isj20be" width="12.601" height="8.543" x="8.314" y="4.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/></filter><filter id="i0W2ktT" width="3.26" height="4.181" x="12.745" y="12.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".375"/></filter><filter id="iPYH01d" width="2.077" height="2.881" x="13.576" y="12.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".05"/></filter><filter id="igOZDtb" width="2.979" height="1.873" x="15.796" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/></filter><filter id="iERAdyb" width="2.98" height="1.873" x="10.649" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/></filter><filter id="iCMjRKb" width=".787" height=".696" x="16.059" y="12.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".05"/></filter><filter id="i1nyrSc" width=".891" height=".913" x="16.899" y="12.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".1"/></filter><filter id="iCFHThG" width=".986" height="1.04" x="12.457" y="12.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".1"/></filter><filter id="iwpMked" width=".913" height=".704" x="11.703" y="12.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".05"/></filter><filter id="iLi6HEp" width="3.099" height="1.681" x="15.649" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".25"/></filter><filter id="iQ3pp7d" width="3.177" height="1.738" x="10.431" y="9.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".25"/></filter><filter id="i3sApIK" width="1.008" height="2.269" x="9.449" y="7.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".125"/></filter><filter id="iR39hfc" width=".726" height=".726" x="23.426" y="6.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/></filter><filter id="iN93ORb" width="3.834" height="4.387" x="20.968" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_32" result="effect2_innerShadow_4002_32"/></filter><filter id="i6dZRHb" width="4.283" height="3.734" x="24.166" y="5.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_32"/></filter><filter id="iw5aASb" width="3.843" height="3.843" x="24.637" y="5.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".1"/></filter><filter id="iqZa0Nb" width="2.734" height="2.734" x="25.191" y="6.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".1"/></filter><filter id="ievskbb" width="2.734" height="2.734" x="21.543" y="8.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".1"/></filter><filter id="iG0t4Nb" width="3.805" height="3.805" x="21.008" y="7.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_32" stdDeviation=".1"/></filter><linearGradient id="ibvrjVc" x1="9.866" x2="9.226" y1="13.449" y2="13.449" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iGdTgue" x1="20.466" x2="19.647" y1="12.079" y2="14.615" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iOuhjWG" x1="18.65" x2="11.014" y1="13.56" y2="14.698" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iPe3B8d" x1="9.219" x2="11.1" y1="16.256" y2="16.189" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="ifFFOVL" x1="19.535" x2="18.422" y1="15.415" y2="15.318" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iYHILlb" x1="14.082" x2="22.226" y1="10.575" y2="7.66" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="i4LNc9c" x1="13.75" x2="14.688" y1="14.219" y2="14.219" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iI2PDYb" x1="15.553" x2="14.527" y1="14.542" y2="14.527" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iShuGgd" x1="14.809" x2="14.809" y1="15.284" y2="14.711" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iD1baab" x1="13.577" x2="14.012" y1="16.899" y2="16.211" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iPcCnPb" x1="17.571" x2="17.257" y1="12.543" y2="12.736" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRY1qee" x1="13.174" x2="12.86" y1="12.543" y2="12.736" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iX6qckc" x1="17.586" x2="17.166" y1="10.403" y2="9.544" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iTHwIQc" x1="12.282" x2="11.093" y1="10.275" y2="9.777" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iPSUR3b" x1="9.953" x2="9.953" y1="8.261" y2="10.418" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="ixn7Nrd" x1="24.949" x2="23.758" y1="5.049" y2="4.704" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iqFOvTT" x1="23.801" x2="23.875" y1="6.542" y2="6.253" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iAyumpb" x1="22.887" x2="23.152" y1="7.398" y2="6.101" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="i0dpVqq" x1="24.298" x2="24.1" y1="7.48" y2="7.424" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="ivqPuuj" x1="23.637" x2="23.578" y1="7.57" y2="7.796" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="ijcJdMb" x1="24.887" x2="28.077" y1="8.172" y2="6.7" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="ibfKRzb" x1="25.441" x2="27.573" y1="8.05" y2="7.066" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iTiFI5M" x1="21.793" x2="23.925" y1="10.064" y2="9.08" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iCqanBe" x1="24.563" x2="22.91" y1="9.276" y2="9.817" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-haircut-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.ad6zenl5p {
  d: path("M3.601 28.893c0-5.916 4.854-10.711 10.842-10.711s10.842 4.795 10.842 10.71v.464H3.601z");
}

.ai325kb6x {
  d: path("M12.63 17.976h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
}

.atmzz1y4m {
  d: path("m14.232 12.885l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bmx48tuma {
  stop-color: var(--svg-color--2477dd, #2477DD);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c_cuvml4y {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m14.339 13.049l-.82 1.699c-.102.35.142.7.487.7h.738c.345 0 .59-.356.488-.7l-.499-1.7c-.106-.376-.283-.376-.394 0");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.cidorvbnk {
  stop-color: var(--svg-color--361c30, #361C30);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cybfe7yaw {
  stop-color: var(--svg-color--27719e, #27719E);
  stop-opacity: 0;
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d0i-qonjb {
  d: path("M7.31 20.827C5.037 22.79 3.6 25.676 3.6 28.893v.463h3.71z");
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f0e9j6bsz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.056 10.825c.327-.29 1.041-.594 1.927-.453");
}

.f2r5v8bfp {
  cx: 12.159px;
  cy: 12.393px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fy9pbzqvw {
  stop-color: var(--svg-color--634747, #634747);
  stop-opacity: 0;
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gqkb4ibjo {
  d: path("M13.243 12.8c0-.29-.234-.481-.298-.54l-.288.28l.178.36z");
}

.gyqhhd_4o {
  d: path("m19.433 6.693l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.907.107-1.44c.044-.433-.032-.565-.429-.96a1.25 1.25 0 0 1-.375-.853v-.853c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.586.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.43-.213a8 8 0 0 0 .804-.586l.965-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.266 1.716-.053 2.36.534l.804.8c.215.266.483.426.805.586");
}

.h-56b9bpz {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
  stop-opacity: 0;
}

.h9vakccdw {
  cx: 22.91px;
  cy: 9.817px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hmafmcb4e {
  d: path("m10.841 10.451l.002-.001l.001-.002l.005-.003l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.24-.14.42-.211a2.83 2.83 0 0 1 1.492-.158a.534.534 0 1 1-.166 1.054a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.824");
}

.hos3q5hgu {
  stop-color: var(--svg-color--367bf1, #367BF1);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.i1-v3abff {
  cx: 22.91px;
  cy: 9.817px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.i6rcqrbyt {
  d: path("M20.283 5.867c-1.214-.028-1.641-.098-2.18-.286l1.138 2.147l.52.065q.085.011.17.005c.707-.055 2.12-.401 2.837-1.045c.844-.758.785-1.492.715-1.758c-.07-.265-.211-.445-.352-.453c-.14-.007-.26.062-.39.375c-.212.508-.883.985-2.458.95");
}

.irpiiabvl {
  d: path("M12.428 12.012a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j-umvlb7c {
  stop-color: var(--svg-color--986272, #986272);
  stop-opacity: 0;
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jlkbatyzp {
  stop-color: var(--svg-color--43a0f3, #43A0F3);
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k-z4zg2os {
  stop-color: var(--svg-color--517cc3, #517CC3);
}

.k9b2ju7jq {
  d: path("M18.577 7.547L15.5 8.573a1.047 1.047 0 0 0 .47 2.03l3.06-.409z");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kin3dabop {
  stop-color: var(--svg-color--43a2ff, #43A2FF);
}

.kp7cfduip {
  fill: var(--svg-color--2b7fde, #2B7FDE);
  d: path("M7.31 20.827C5.037 22.79 3.6 25.676 3.6 28.893v.463h3.71z");
}

.kpfztrcsd {
  cx: 26.559px;
  cy: 7.803px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lslinwphh {
  fill-rule: evenodd;
  d: path("M23.013 7.442a.1.1 0 0 0-.124.068l-.104.357a.22.22 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.22.22 0 0 1-.068-.22l.102-.349a.1.1 0 0 0-.069-.124zm.74 2.391a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m-fo0lvbc {
  stop-color: var(--svg-color--407da5, #407DA5);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m2no4lz0w {
  d: path("m24.342 2.644l-1.388 4.83l1.187.346l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mn5xrd5ls {
  d: path("M16.73 12.2c.063.086-.07.19-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358s.325-.135.389-.05");
}

.mq0bii3nt {
  stop-color: var(--svg-color--459bfc, #459BFC);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.njc_4fbku {
  cx: 19.379px;
  cy: 13.171px;
  r: 0.995px;
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o0amu2b5i {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m19.433 6.693l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.907.107-1.44c.044-.433-.032-.565-.429-.96a1.25 1.25 0 0 1-.375-.853v-.853c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.272.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.586.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.43-.213a8 8 0 0 0 .804-.586l.965-1.014c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.266 1.716-.053 2.36.534l.804.8c.215.266.483.426.805.586");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.on_jcmgtl {
  stop-color: var(--svg-color--a8857f, #A8857F);
}

.owv1xe5nh {
  stop-color: var(--svg-color--80546a, #80546A);
  stop-opacity: 0;
}

.oxun88gow {
  stop-color: var(--svg-color--438dec, #438DEC);
}

.p_xiulv7p {
  d: path("m19.694 5.22l5.419 1.537l-.337 1.189l-4.313-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.p3i1c_8gc {
  d: path("M9.457 11.12c0-.267.107-.587.321-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.534c.643-.16 1.984-.426 3.915-.426s3.272.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.545.43.96c-.055.533-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.002-3.21 3.002h-3.21c-1.712 0-3.05-1.233-3.21-3.002c-.14-1.817-.2-3.638-.366-5.451");
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkl5_wldm {
  stop-color: var(--svg-color--634747, #634747);
}

.puczgzv3j {
  stop-color: var(--svg-color--459bfc, #459BFC);
}

.qeqnj6bwc {
  cx: 19.379px;
  cy: 13.171px;
  r: 1.669px;
}

.qg1uz5bds {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.274 10.306c.43-.075 1.27-.054 1.85.398");
}

.qmmxotaou {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m18.334 10.451l-.002-.001l-.002-.002l-.004-.003l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.539-.291a2.83 2.83 0 0 0-1.492-.158a.534.534 0 1 0 .166 1.054c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .679-.824");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qz5ypoujz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.082 8.36v.897c-.008.149-.07.481-.258.622");
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.rnl91gb8n {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m14.232 12.885l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.rxprtfb0z {
  stop-color: var(--svg-color--407da5, #407DA5);
  stop-opacity: 0;
}

.s8skxyn0j {
  fill: var(--svg-color--000, #000);
  d: path("M16.284 12.904c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.06-.235");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.sm84e7bem {
  cx: 23.739px;
  cy: 7px;
  r: 0.313px;
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.stji6gbyf {
  stop-color: var(--svg-color--a8857f, #A8857F);
  stop-opacity: 0;
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.tet72waca {
  stop-color: var(--svg-color--339ff3, #339FF3);
}

.tkc4hvb0d {
  fill: var(--svg-color--99686f, #99686F);
  d: path("M12.63 17.976h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.txm2ysbkn {
  stop-color: var(--svg-color--367bf1, #367BF1);
  stop-opacity: 0;
}

.ubraf2bsa {
  d: path("M21.577 29.356h3.708v-.463c0-3.217-1.435-6.103-3.708-8.066z");
}

.uc_e6-bbg {
  stop-color: var(--svg-color--80546a, #80546A);
}

.ur76s4bgv {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m10.841 10.451l.002-.001l.001-.002l.005-.003l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.24-.14.42-.211a2.83 2.83 0 0 1 1.492-.158a.534.534 0 1 1-.166 1.054a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.824");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v6-g8enxe {
  cx: 12.159px;
  cy: 12.393px;
  rx: 0.389px;
  ry: 0.197px;
}

.vo905zb4s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.221 11.74c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vp_-q7ldm {
  stop-color: var(--svg-color--517cc3, #517CC3);
  stop-opacity: 0;
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w457ubb8p {
  d: path("M17.59 12.787a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.wb4a9hbls {
  cx: 9.866px;
  cy: 13.171px;
  r: 0.995px;
}

.wj347g5uq {
  cx: 19.379px;
  cy: 13.171px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.wke-8-xfb {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
}

.wlnsi_b8m {
  d: path("m18.334 10.451l-.002-.001l-.002-.002l-.004-.003l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.539-.291a2.83 2.83 0 0 0-1.492-.158a.534.534 0 1 0 .166 1.054c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .679-.824");
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x_8osmbty {
  fill: var(--svg-color--000, #000);
  d: path("M12.939 12.904a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.745h.904a.5.5 0 0 0 .061-.235");
}

.x7utjgb1r {
  stop-color: var(--svg-color--5c4040, #5C4040);
}

.x8g_-0bes {
  fill-rule: evenodd;
  d: path("M24.457 6.655a.1.1 0 0 1 .123-.07l.359.095c.08.021.163-.01.217-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.094a.1.1 0 0 1-.071-.122zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xee17_bfa {
  cx: 9.867px;
  cy: 13.171px;
  r: 1.669px;
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xmx82cnqk {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.002 11.74c.652 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.y2kcw2b0l {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.73 12.2c.063.086-.07.19-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358s.325-.135.389-.05");
}

.y6q895bci {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.252 15.928a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24c.344.52.942.867 1.624.867s1.28-.347 1.624-.868a.19.19 0 0 0-.02-.241a.2.2 0 0 0-.242-.04a2.94 2.94 0 0 1-1.362.323c-.5 0-.969-.117-1.362-.322Z");
}

.yfngg9boj {
  cx: 26.559px;
  cy: 7.804px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.yq5--pdjx {
  d: path("m9.515 12.558l.049.002s-.054-.854-.107-1.44c0-.267.107-.587.321-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.534c.643-.16 1.984-.426 3.915-.426s3.272.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.545.43.96c-.055.533-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.002-3.21 3.002h-3.21c-1.712 0-3.05-1.233-3.21-3.002z");
}

.yqvz3__yv {
  d: path("M16.795 12.012a.892.892 0 0 1 .86 1.127H15.93a.896.896 0 0 1 .864-1.127");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zdar40bkv {
  stop-color: var(--svg-color--145491, #145491);
}

.zi0iv1bfj {
  stop-color: var(--svg-color--438dec, #438DEC);
  stop-opacity: 0;
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
