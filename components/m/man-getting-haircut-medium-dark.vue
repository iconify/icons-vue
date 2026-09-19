<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuyRCtc)" class="ad6zenl5p"/><path fill="url(#iwPHmHc)" class="ad6zenl5p"/><path fill="url(#iEv1z7b)" class="ad6zenl5p"/><path fill="url(#ig2uhxd)" class="ad6zenl5p"/><path fill="url(#iAFkfSb)" class="ad6zenl5p"/><path fill="url(#imizA9b)" class="qzrjotblb"/><path fill="url(#iWl9v6E)" class="qzrjotblb"/><path class="ymkk5wbru"/><path fill="url(#ihJj5Db)" class="pfektw6xz"/><path fill="url(#iQPaFqb)" class="pfektw6xz"/><path class="q-_ytlb_r"/><path fill="url(#iyGhque)" class="ai325kb6x"/><path fill="url(#i4YHyec)" class="ai325kb6x"/><g filter="url(#i2I5e1d)"><circle fill="url(#iFcnuxe)" class="iyyxy4ppu"/></g><g filter="url(#ivQ38qe)"><circle fill="url(#iMPzU4m)" class="hek-c-bvd"/></g><g filter="url(#imaGKdv)"><circle fill="url(#imlctwL)" class="m6fuk7bfm"/><circle fill="url(#iyRhMVG)" class="m6fuk7bfm"/></g><g filter="url(#izLZHDb)"><circle class="dtz-cwgbi"/><circle fill="url(#igj2HAR)" class="ys19y1-vh"/><circle fill="url(#i8nZyne)" class="ys19y1-vh"/></g><g filter="url(#iSrKvZb)"><path fill="url(#iiVGSec)" class="uml6ftb3k"/><path fill="url(#iVOy9Ne)" class="uml6ftb3k"/><path fill="url(#ir0V2Qd)" class="uml6ftb3k"/></g><path fill="url(#iGnOldd)" class="i0szs_a_l"/><path fill="url(#iGi1Z7d)" class="i0szs_a_l"/><path fill="url(#iWZCvyc)" class="i0szs_a_l"/><g filter="url(#i8Tx7ic)"><path fill="url(#ifim9lb)" class="thhl4p_7i"/></g><g filter="url(#iylmHbb)"><path class="rukf5j73i"/><path fill="url(#iazU81c)" class="o_ihx0xut"/><path fill="url(#ib4IJ0c)" class="o_ihx0xut"/><path fill="url(#ieHlFFb)" class="o_ihx0xut"/><path fill="url(#iWawmDb)" class="o_ihx0xut"/></g><g filter="url(#iIlz5tb)"><path class="u6c4-l3bo"/></g><g filter="url(#inPvIEb)"><path class="mamogtbyo"/><path fill="url(#iiimjve)" class="ip1tm4b_i"/><path fill="url(#i5vCNTb)" class="ip1tm4b_i"/><path fill="url(#iczodFc)" class="ip1tm4b_i"/><path fill="url(#iFkGydP)" class="ip1tm4b_i"/></g><path stroke="url(#idlMS0c)" class="buc9st__f"/><g filter="url(#ilsMx6G)"><path class="mhwmhpbbf"/><path fill="url(#idoH5xd)" class="txyxnfb9g"/></g><g filter="url(#i8phKYd)"><path class="lp9fu3hjo"/><path fill="url(#iFXuW3d)" class="vgmiwxb_r"/></g><path class="csssiybdn"/><path fill="url(#iS80Nyb)" class="tvfcf6bwv"/><path class="onnrjsbtn"/><g filter="url(#iopaQ5c)"><path class="laog378oa"/><path fill="url(#irlD6Bb)" class="mce0ddw_e"/></g><g filter="url(#iZxlo1b)"><path fill="url(#i3BuonF)" class="s83hmorcr"/></g><path class="ou32v36sl"/><path fill="url(#iQMIvye)" class="u0p_k56qv"/><path class="trwjt9cxn"/><g filter="url(#i2VQYke)"><path fill="url(#iRGuuhd)" class="mt_bu1boi"/></g><g filter="url(#iHsjLsb)"><ellipse transform="rotate(-27.914 12.17 12.386)" class="rw8v4bbxs"/><ellipse fill="url(#iPdInwb)" transform="rotate(-27.914 12.17 12.386)" class="g03-dccvo"/></g><g filter="url(#i5acbqd)"><path stroke="url(#iEOLqXc)" class="ekor3hbsu"/></g><g filter="url(#iQwvKvd)"><path stroke="url(#izu7Czd)" class="ta0_tcb5e"/></g><g filter="url(#iZeWQGe)"><path stroke="url(#ie1yZ7b)" class="s4zmj5b9x"/></g><path fill="url(#i5bvqQd)" class="pxaz2bi6p"/><path fill="url(#ijU8njZ)" class="pxaz2bi6p"/><path fill="url(#ixn7Nrd)" class="j9_tcit_c"/><path fill="url(#iqFOvTT)" class="j9_tcit_c"/><path fill="url(#iAyumpb)" class="yx0ye_ufd"/><path fill="url(#i0dpVqq)" class="yx0ye_ufd"/><g filter="url(#iOCaCLb)"><circle fill="url(#iuDFgAe)" class="sm84e7bem"/><circle fill="url(#ipce8Sd)" class="sm84e7bem"/><circle fill="url(#imM1H1b)" class="sm84e7bem"/></g><g filter="url(#iWqGKFe)"><path fill="url(#i5lhlOb)" clip-rule="evenodd" class="h83b67bow"/></g><path fill="url(#ivqPuuj)" clip-rule="evenodd" class="h83b67bow"/><g filter="url(#iezSfDc)"><path fill="url(#ie1h4be)" clip-rule="evenodd" class="v99r5cc_a"/></g><g filter="url(#inhjCqd)"><circle stroke="url(#ijcJdMb)" class="dusbyk69d"/></g><g filter="url(#i9XMs4c)"><circle stroke="url(#ibfKRzb)" class="c4y9rnb2u"/></g><g filter="url(#i2Csx2b)"><circle stroke="url(#iTiFI5M)" class="i1-v3abff"/></g><g filter="url(#iOigyxe)"><circle stroke="url(#iCqanBe)" class="h9vakccdw"/></g><defs><radialGradient id="iuyRCtc" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.313 13.901)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="tet72waca"/><stop offset="1" class="bmx48tuma"/></radialGradient><radialGradient id="iwPHmHc" cx="0" cy="0" r="1" gradientTransform="rotate(-115.528 17.238 10.578)scale(12.9022 18.5657)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="rxprtfb0z"/><stop offset="1" class="m-fo0lvbc"/></radialGradient><radialGradient id="iEv1z7b" cx="0" cy="0" r="1" gradientTransform="rotate(166.984 5.946 10.215)scale(6.38273 2.1839)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="zdar40bkv"/><stop offset="1" class="cybfe7yaw"/></radialGradient><radialGradient id="ig2uhxd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.546 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="puczgzv3j"/><stop offset="1" class="mq0bii3nt"/></radialGradient><radialGradient id="iAFkfSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.24045 0 0 9.50024 7.166 29.356)" gradientUnits="userSpaceOnUse"><stop class="wke-8-xfb"/><stop offset="1" class="h-56b9bpz"/></radialGradient><radialGradient id="imizA9b" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.576 28.578)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="kin3dabop"/><stop offset="1" class="jlkbatyzp"/></radialGradient><radialGradient id="iWl9v6E" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.576 29.356)" gradientUnits="userSpaceOnUse"><stop class="hos3q5hgu"/><stop offset="1" class="txm2ysbkn"/></radialGradient><radialGradient id="ihJj5Db" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.31 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="vp_-q7ldm"/><stop offset=".956" class="k-z4zg2os"/></radialGradient><radialGradient id="iQPaFqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.31 29.356)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="oxun88gow"/><stop offset="1" class="zi0iv1bfj"/></radialGradient><radialGradient id="iyGhque" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.7 18.991)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="cff89lpud"/><stop offset="1" class="uml_129yg"/></radialGradient><radialGradient id="i4YHyec" cx="0" cy="0" r="1" gradientTransform="rotate(139.583 4.476 13.308)scale(2.48229 1.07513)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="agxu4b52q"/><stop offset="1" class="x91hkhs6n"/></radialGradient><radialGradient id="iFcnuxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.204 13.164)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iyRhMVG" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 19.77 12.899)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="igj2HAR" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 19.356 13.986)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="i8nZyne" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 19.398 13.164)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iVOy9Ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 16.975 11.891)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="ir0V2Qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 12.413 12.025)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iWZCvyc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8549 -12.0201 0 14.325 11.388)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="xibwmkbfz"/><stop offset=".955" class="y8g8d8bmh"/></radialGradient><radialGradient id="iazU81c" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.42495 .3845 18.977 9.054)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="ib4IJ0c" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 17.333 7.292)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="ieHlFFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 14.627 4.555)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iWawmDb" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 8.173 11.38)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iFkGydP" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 14.955 14.772)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="idoH5xd" cx="0" cy="0" r="1" gradientTransform="matrix(.10429 -.60384 1.7864 .30853 17.073 11.078)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iFXuW3d" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 12.538 -1.539)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iS80Nyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 16.808 12.482)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="irlD6Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 16.58 12.566)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQMIvye" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 12.44 12.481)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iPdInwb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.33 .368)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5bvqQd" cx="0" cy="0" r="1" gradientTransform="rotate(152.815 11.014 5.22)scale(5.16422 4.07334)" gradientUnits="userSpaceOnUse"><stop class="gxg_8_b1a"/><stop offset=".871" class="ojybrqbyt"/></radialGradient><radialGradient id="ijU8njZ" cx="0" cy="0" r="1" gradientTransform="matrix(2.98437 .4375 -.0798 .54434 17.743 6.74)" gradientUnits="userSpaceOnUse"><stop offset=".037" class="e9ucyqbno"/><stop offset="1" class="ii6m_dbvx"/></radialGradient><radialGradient id="iuDFgAe" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.74 7.666)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="ipce8Sd" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.594 7.347)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="imM1H1b" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.369 6.91)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="i5lhlOb" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.396 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="ie1h4be" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.543 8.273)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="i2I5e1d" width="3.542" height="3.342" x="8.204" y="11.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/></filter><filter id="ivQ38qe" width="2.992" height="2.992" x="8.379" y="11.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".25"/></filter><filter id="imaGKdv" width="3.592" height="3.592" x="17.726" y="11.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/></filter><filter id="izLZHDb" width="2.992" height="2.992" x="17.901" y="11.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".25"/></filter><filter id="iSrKvZb" width="10.383" height="12.189" x="9.464" y="7.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/></filter><filter id="i8Tx7ic" width="8.25" height="7.07" x="12.797" y="5.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation="1"/></filter><filter id="iylmHbb" width="12.614" height="8.551" x="8.321" y="4.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/></filter><filter id="iIlz5tb" width="3.262" height="4.184" x="12.757" y="12.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".375"/></filter><filter id="inPvIEb" width="2.079" height="2.884" x="13.588" y="12.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".05"/></filter><filter id="ilsMx6G" width="2.982" height="1.874" x="15.81" y="9.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/></filter><filter id="i8phKYd" width="2.982" height="1.874" x="10.658" y="9.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/></filter><filter id="iopaQ5c" width=".787" height=".697" x="16.074" y="12.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".05"/></filter><filter id="iZxlo1b" width=".892" height=".914" x="16.914" y="12.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".1"/></filter><filter id="i2VQYke" width=".987" height="1.041" x="12.468" y="12.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".1"/></filter><filter id="iHsjLsb" width=".914" height=".705" x="11.713" y="12.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".05"/></filter><filter id="i5acbqd" width="3.101" height="1.681" x="15.664" y="9.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".25"/></filter><filter id="iQwvKvd" width="3.179" height="1.739" x="10.44" y="9.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".25"/></filter><filter id="iZeWQGe" width="1.008" height="2.271" x="9.457" y="7.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".125"/></filter><filter id="iOCaCLb" width=".726" height=".726" x="23.426" y="6.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/></filter><filter id="iWqGKFe" width="3.834" height="4.387" x="20.968" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_29" result="effect2_innerShadow_4002_29"/></filter><filter id="iezSfDc" width="4.283" height="3.734" x="24.166" y="5.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_29"/></filter><filter id="inhjCqd" width="3.843" height="3.843" x="24.637" y="5.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".1"/></filter><filter id="i9XMs4c" width="2.734" height="2.734" x="25.191" y="6.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".1"/></filter><filter id="i2Csx2b" width="2.734" height="2.734" x="21.543" y="8.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".1"/></filter><filter id="iOigyxe" width="3.805" height="3.805" x="21.008" y="7.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_29" stdDeviation=".1"/></filter><linearGradient id="iMPzU4m" x1="9.875" x2="9.234" y1="13.443" y2="13.443" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="imlctwL" x1="20.485" x2="19.665" y1="12.071" y2="14.61" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iiVGSec" x1="18.667" x2="11.023" y1="13.554" y2="14.693" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iGnOldd" x1="9.226" x2="11.109" y1="16.252" y2="16.185" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iGi1Z7d" x1="19.496" x2="18.439" y1="15.414" y2="15.313" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="ifim9lb" x1="14.095" x2="22.247" y1="10.566" y2="7.648" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iiimjve" x1="13.762" x2="14.701" y1="14.214" y2="14.214" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="i5vCNTb" x1="15.566" x2="14.54" y1="14.537" y2="14.522" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iczodFc" x1="14.822" x2="14.822" y1="15.28" y2="14.706" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="idlMS0c" x1="13.589" x2="14.025" y1="16.896" y2="16.208" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i3BuonF" x1="17.587" x2="17.273" y1="12.535" y2="12.729" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRGuuhd" x1="13.185" x2="12.872" y1="12.535" y2="12.729" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEOLqXc" x1="17.602" x2="17.182" y1="10.394" y2="9.534" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="izu7Czd" x1="12.293" x2="11.102" y1="10.266" y2="9.766" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ie1yZ7b" x1="9.961" x2="9.961" y1="8.249" y2="10.408" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="ixn7Nrd" x1="24.949" x2="23.758" y1="5.049" y2="4.704" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iqFOvTT" x1="23.801" x2="23.875" y1="6.542" y2="6.253" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iAyumpb" x1="22.887" x2="23.152" y1="7.398" y2="6.101" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="i0dpVqq" x1="24.298" x2="24.1" y1="7.48" y2="7.424" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="ivqPuuj" x1="23.637" x2="23.578" y1="7.57" y2="7.796" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="ijcJdMb" x1="24.887" x2="28.077" y1="8.172" y2="6.7" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="ibfKRzb" x1="25.441" x2="27.573" y1="8.05" y2="7.066" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iTiFI5M" x1="21.793" x2="23.925" y1="10.064" y2="9.08" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iCqanBe" x1="24.563" x2="22.91" y1="9.276" y2="9.817" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-haircut-medium-dark" /></template>
<style>
.ad6zenl5p {
  d: path("M3.601 28.893c0-5.916 4.854-10.711 10.842-10.711s10.842 4.795 10.842 10.71v.464H3.601z");
}

.agxu4b52q {
  stop-color: var(--svg-color--7e5c61, #7E5C61);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ai325kb6x {
  d: path("M12.63 17.976h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.bmx48tuma {
  stop-color: var(--svg-color--2477dd, #2477DD);
}

.buc9st__f {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.264 15.924a2.96 2.96 0 0 0 1.363.323c.505 0 .97-.118 1.364-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .02.241m-2.99-.281l2.949.253m-2.948-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.253m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.869a1.94 1.94 0 0 1-1.626-.869m3.21-.028a1.89 1.89 0 0 1-1.584.847c-.665 0-1.25-.339-1.584-.847m-.042.028l.042-.028m-.042.028l.042-.028");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c4y9rnb2u {
  cx: 26.558px;
  cy: 7.803px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cff89lpud {
  stop-color: var(--svg-color--643c53, #643C53);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.csssiybdn {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.018 11.732c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.13");
}

.cybfe7yaw {
  stop-color: var(--svg-color--27719e, #27719E);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dtz-cwgbi {
  cx: 19.397px;
  cy: 13.164px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.dusbyk69d {
  cx: 26.558px;
  cy: 7.804px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9ucyqbno {
  stop-color: var(--svg-color--423539, #423539);
}

.ekor3hbsu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.29 10.297c.43-.076 1.27-.054 1.85.398");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g03-dccvo {
  cx: 12.17px;
  cy: 12.386px;
  rx: 0.39px;
  ry: 0.197px;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
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

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gxg_8_b1a {
  stop-color: var(--svg-color--1f1027, #1F1027);
}

.h-56b9bpz {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
  stop-opacity: 0;
}

.h83b67bow {
  fill-rule: evenodd;
  d: path("M23.013 7.442a.1.1 0 0 0-.124.068l-.104.357a.22.22 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.101-.349a.1.1 0 0 0-.068-.124zm.74 2.391a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.h9vakccdw {
  cx: 22.91px;
  cy: 9.817px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.hek-c-bvd {
  cx: 9.875px;
  cy: 13.164px;
  r: 0.996px;
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hos3q5hgu {
  stop-color: var(--svg-color--367bf1, #367BF1);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.i0szs_a_l {
  d: path("M9.464 11.11c0-.266.108-.586.322-.746l.161-.16c.269-.214.376-.534.376-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.054.43.267.43.534v.854c0 .32.16.64.375.854c.503.353.471.546.43.961a46 46 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.213 3.005h-3.214c-1.714 0-3.052-1.234-3.213-3.005c-.14-1.819-.2-3.642-.367-5.457");
}

.i1-v3abff {
  cx: 22.91px;
  cy: 9.817px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ii6m_dbvx {
  stop-color: var(--svg-color--423539, #423539);
  stop-opacity: 0;
}

.ip1tm4b_i {
  d: path("m14.245 12.879l-.532 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.iyyxy4ppu {
  cx: 9.875px;
  cy: 13.164px;
  r: 1.671px;
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.j9_tcit_c {
  d: path("m24.342 2.644l-1.388 4.83l1.186.346l1.072-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jlkbatyzp {
  stop-color: var(--svg-color--43a0f3, #43A0F3);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k-z4zg2os {
  stop-color: var(--svg-color--517cc3, #517CC3);
}

.kin3dabop {
  stop-color: var(--svg-color--43a2ff, #43A2FF);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.laog378oa {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.745 12.193c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.359c.15-.113.325-.135.389-.05");
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lp9fu3hjo {
  fill: var(--svg-color--352827, #352827);
  d: path("m10.85 10.442l.002-.002l.002-.001l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.241-.14.42-.21c.36-.143.873-.257 1.494-.16a.534.534 0 0 1-.166 1.056a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.68-.824");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m-fo0lvbc {
  stop-color: var(--svg-color--407da5, #407DA5);
}

.m6fuk7bfm {
  cx: 19.397px;
  cy: 13.164px;
  r: 1.671px;
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mamogtbyo {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m14.245 12.879l-.532 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mce0ddw_e {
  d: path("M16.745 12.193c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.359c.15-.113.325-.135.389-.05");
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mhwmhpbbf {
  fill: var(--svg-color--352827, #352827);
  d: path("m18.35 10.442l-.001-.002l-.002-.001l-.004-.004l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.494-.158a.534.534 0 0 0 .167 1.055c.398-.063.717.01.935.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .68-.825");
}

.mq0bii3nt {
  stop-color: var(--svg-color--459bfc, #459BFC);
  stop-opacity: 0;
}

.mt_bu1boi {
  d: path("M13.255 12.792c0-.288-.235-.48-.298-.54l-.289.28l.178.362z");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.o_ihx0xut {
  d: path("m19.45 6.68l.43.214c.752.373 1.182 1.228 1.02 2.135l-.59 3.043c-.053.314-.26.526-.572.534h-.019s.054-.908.108-1.441c.043-.434-.032-.566-.43-.961c-.215-.214-.376-.534-.376-.855v-.854c0-.267-.214-.48-.43-.534c-.643-.16-1.986-.427-3.919-.427c-1.932 0-3.275.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.641-.375.854l-.161.16c-.215.16-.322.481-.322.748c.053.587.107 1.441.107 1.441l-.05-.001a.634.634 0 0 1-.594-.532l-.591-3.043c-.107-.854.322-1.709 1.074-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.268 1.718-.054 2.362.533l.805.801c.215.267.484.427.806.587");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojybrqbyt {
  stop-color: var(--svg-color--37282c, #37282C);
}

.onnrjsbtn {
  fill: var(--svg-color--000, #000);
  d: path("M16.299 12.897a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.236");
}

.ou32v36sl {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.232 11.732c-.653 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.13");
}

.oxun88gow {
  stop-color: var(--svg-color--438dec, #438DEC);
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pfektw6xz {
  d: path("M7.31 20.826c-2.273 1.964-3.71 4.85-3.71 8.067v.463h3.71z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.puczgzv3j {
  stop-color: var(--svg-color--459bfc, #459BFC);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pxaz2bi6p {
  d: path("M20.283 5.867c-1.215-.028-1.642-.098-2.18-.286V7.32l1.163.479a.86.86 0 0 0 .426.065c.796-.095 2.4-.502 3.076-1.11c.843-.758.785-1.492.715-1.758c-.07-.265-.211-.445-.352-.453c-.14-.007-.26.062-.39.375c-.212.508-.883.985-2.458.95");
}

.q-_ytlb_r {
  fill: var(--svg-color--814f52, #814F52);
  d: path("M12.63 17.976h3.985v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzrjotblb {
  d: path("M21.577 29.356h3.708v-.463c0-3.217-1.436-6.103-3.709-8.066z");
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.rukf5j73i {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m19.45 6.68l.43.214c.752.373 1.182 1.228 1.02 2.135l-.59 3.043c-.053.314-.26.526-.572.534h-.019s.054-.908.108-1.441c.043-.434-.032-.566-.43-.961c-.215-.214-.376-.534-.376-.855v-.854c0-.267-.214-.48-.43-.534c-.643-.16-1.986-.427-3.919-.427c-1.932 0-3.275.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.641-.375.854l-.161.16c-.215.16-.322.481-.322.748c.053.587.107 1.441.107 1.441l-.05-.001a.634.634 0 0 1-.594-.532l-.591-3.043c-.107-.854.322-1.709 1.074-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.268 1.718-.054 2.362.533l.805.801c.215.267.484.427.806.587");
}

.rw8v4bbxs {
  cx: 12.17px;
  cy: 12.386px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.rxprtfb0z {
  stop-color: var(--svg-color--407da5, #407DA5);
  stop-opacity: 0;
}

.s4zmj5b9x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.09 8.348v.899c-.008.148-.07.481-.258.622");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.s83hmorcr {
  d: path("M17.606 12.78a.84.84 0 0 0-.232-.464l-.26.286l.117.228z");
}

.sm84e7bem {
  cx: 23.739px;
  cy: 7px;
  r: 0.313px;
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.ta0_tcb5e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.065 10.816c.327-.29 1.042-.594 1.929-.453");
}

.tet72waca {
  stop-color: var(--svg-color--339ff3, #339FF3);
}

.thhl4p_7i {
  d: path("m18.595 7.534l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.trwjt9cxn {
  fill: var(--svg-color--000, #000);
  d: path("M12.95 12.897a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.456.747h.906a.5.5 0 0 0 .06-.236");
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tvfcf6bwv {
  d: path("M16.81 12.004a.893.893 0 0 1 .86 1.129h-1.725a.896.896 0 0 1 .865-1.128");
}

.txm2ysbkn {
  stop-color: var(--svg-color--367bf1, #367BF1);
  stop-opacity: 0;
}

.txyxnfb9g {
  d: path("m18.35 10.442l-.001-.002l-.002-.001l-.004-.004l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.494-.158a.534.534 0 0 0 .167 1.055c.398-.063.717.01.935.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .68-.825");
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u0p_k56qv {
  d: path("M12.439 12.004a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.u6c4-l3bo {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m14.352 13.042l-.822 1.7c-.101.35.143.7.49.7h.737c.346 0 .59-.355.489-.7l-.5-1.7c-.106-.377-.282-.377-.394 0");
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uml_129yg {
  stop-color: var(--svg-color--643c53, #643C53);
  stop-opacity: 0;
}

.uml6ftb3k {
  d: path("m9.523 12.55l.049.002s-.054-.854-.108-1.441c0-.267.108-.587.322-.747l.161-.16c.269-.214.376-.534.376-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.054.43.267.43.534v.854c0 .32.16.64.375.854c.503.353.471.546.43.961a46 46 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.213 3.005h-3.214c-1.714 0-3.052-1.234-3.213-3.005z");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.v99r5cc_a {
  fill-rule: evenodd;
  d: path("M24.457 6.655a.1.1 0 0 1 .123-.07l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.094a.1.1 0 0 1-.071-.122zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vgmiwxb_r {
  d: path("m10.85 10.442l.002-.002l.002-.001l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.241-.14.42-.21c.36-.143.873-.257 1.494-.16a.534.534 0 0 1-.166 1.056a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.68-.824");
}

.vp_-q7ldm {
  stop-color: var(--svg-color--517cc3, #517CC3);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wke-8-xfb {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x91hkhs6n {
  stop-color: var(--svg-color--7e5c61, #7E5C61);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xibwmkbfz {
  stop-color: var(--svg-color--7d4b5d, #7D4B5D);
  stop-opacity: 0;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y8g8d8bmh {
  stop-color: var(--svg-color--62405c, #62405C);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ymkk5wbru {
  fill: var(--svg-color--2b7fde, #2B7FDE);
  d: path("M7.31 20.826c-2.273 1.964-3.71 4.85-3.71 8.067v.463h3.71z");
}

.ys19y1-vh {
  cx: 19.397px;
  cy: 13.164px;
  r: 0.996px;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.yx0ye_ufd {
  d: path("m19.694 5.22l5.42 1.537l-.338 1.189l-4.313-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
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

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
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

</style>
