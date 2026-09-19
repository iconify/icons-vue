<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDZZbgc)"><path class="xm1eavbhd"/><path fill="url(#iDXuhRb)" class="onff_pbvz"/></g><path fill="url(#i27QxPe)" class="onff_pbvz"/><path fill="url(#ibdLcle)" class="r-0b0ebfr"/><path fill="url(#igkZFkd)" class="r-0b0ebfr"/><circle fill="url(#ipDFeae)" class="un1s7042i"/><g filter="url(#iP3PTwb)"><circle fill="url(#iP9ug0d)" class="fy301klzq"/></g><g filter="url(#ive3cVc)"><circle fill="url(#iRUxkrc)" class="kd9sqzn4j"/><circle fill="url(#iJ2ZzIb)" class="kd9sqzn4j"/></g><g filter="url(#iJTDKIe)"><circle class="zlivpjjso"/><circle fill="url(#ixzbWIb)" class="lt_6sfbfh"/><circle fill="url(#ibz4LOd)" class="lt_6sfbfh"/></g><path fill="url(#i4mEFQH)" class="p_at91bjt"/><path fill="url(#i3TRcxd)" class="p_at91bjt"/><path fill="url(#iMjQkAZ)" class="p_at91bjt"/><path fill="url(#iA4s2ge)" class="p_at91bjt"/><path fill="url(#i8yIDwD)" class="p_at91bjt"/><path fill="url(#ieSUfic)" class="p_at91bjt"/><g filter="url(#iQDx8Vc)"><path class="c5rrs6bxi"/><path fill="url(#ineNH5D)" class="rrj20zcfg"/><path fill="url(#i5d1Nbd)" class="rrj20zcfg"/><path fill="url(#itO2CBb)" class="rrj20zcfg"/><path fill="url(#igPjEgw)" class="rrj20zcfg"/><path fill="url(#i8tITAe)" class="rrj20zcfg"/><path fill="url(#i0mRm8p)" class="rrj20zcfg"/></g><path fill="url(#ihkhvFc)" class="rrj20zcfg"/><path fill="url(#izFEA6d)" class="rrj20zcfg"/><path fill="url(#iJSrUrr)" class="rrj20zcfg"/><g filter="url(#i6vW7bd)"><path fill="url(#ign0hEd)" clip-rule="evenodd" class="x-y69psvt"/></g><g filter="url(#iM4iwic)"><path class="i_3i3cgxw"/></g><g filter="url(#ilAUjyd)"><path fill="url(#i4jXi8d)" clip-rule="evenodd" class="zium8mc3e"/></g><g filter="url(#iwYaq7d)"><path class="ah2mmqbwe"/></g><path fill="url(#i0ncvsd)" class="id2v71bmv"/><path fill="url(#iQzAzTm)" class="id2v71bmv"/><g filter="url(#i05HgbR)"><path fill="url(#iAzGnHr)" class="tvvtj8d6u"/></g><g filter="url(#ij2ImBc)"><path fill="url(#iOE338E)" clip-rule="evenodd" class="ugnp-5bfk"/></g><path class="f1l8tljlq"/><g filter="url(#i7zDAQe)"><path class="xpfn1uy9q"/><path fill="url(#ivRWdAd)" class="y9f8y_b6f"/><path fill="url(#iiOCBMd)" class="y9f8y_b6f"/><path fill="url(#irAb3wv)" class="y9f8y_b6f"/><path fill="url(#iTOS50d)" class="y9f8y_b6f"/></g><path fill="url(#isbzh0b)" class="y9f8y_b6f"/><path fill="url(#izNv5qn)" class="ay8x0ubqe"/><path fill="url(#iaYUHub)" class="ay8x0ubqe"/><path fill="url(#i5GPM6b)" class="w3nqf8i5r"/><path fill="url(#iv5cwKd)" class="w3nqf8i5r"/><path fill="url(#iVn4NZd)" class="w3nqf8i5r"/><path fill="url(#iYPt2ld)" class="w3nqf8i5r"/><g filter="url(#iwmczub)"><path stroke="url(#ia3oUzp)" class="p1b01acps"/></g><g filter="url(#iTBXfMO)"><path stroke="url(#igqSI3D)" class="lsv4v5blf"/></g><g filter="url(#i8Dd9rc)"><path stroke="url(#iEcoShc)" class="itdj3x85b"/></g><g filter="url(#iIVSXKd)"><path stroke="url(#ifBEBBq)" class="dfl74__zr"/></g><g filter="url(#iZQaDmc)"><path stroke="url(#ivAvU7d)" class="g_dz4cd7h"/></g><defs><radialGradient id="iDXuhRb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.38721 2.45336 -5.57243 -14.5076 21.385 26.328)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="xp6xvybaw"/><stop offset="1" class="n-s36oh9s"/></radialGradient><radialGradient id="i27QxPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.84375 -6.97792 0 16 18.125)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="qvg0urbpt"/><stop offset="1" class="yu7mlobzw"/></radialGradient><radialGradient id="ibdLcle" cx="0" cy="0" r="1" gradientTransform="matrix(2.32812 3.40625 -3.8571 2.63627 14.687 20.312)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="h0-blzbbk"/><stop offset=".878" class="gslsq1v8t"/></radialGradient><radialGradient id="ipDFeae" cx="0" cy="0" r="1" gradientTransform="matrix(2.21653 0 0 3.87895 7.883 12.927)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iJ2ZzIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.04419 -.76033 .86782 1.19181 22.478 12.592)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="ixzbWIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03732 -1.90792 1.11671 .60715 21.956 13.964)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="ibz4LOd" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -4.713 33.222)scale(.46081 .59406)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iMjQkAZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.8668 11.08456 -16.3152 -1.27584 18.489 10.563)" gradientUnits="userSpaceOnUse"><stop offset=".507" class="az3fkmbzf"/><stop offset="1" class="kk8ms1szj"/></radialGradient><radialGradient id="iA4s2ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65095 2.03193 0 18.952 11.32)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="i8yIDwD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.75678 2.18471 0 13.196 11.279)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="ineNH5D" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.546 6.65)scale(7.08105 12.042)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="itO2CBb" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.18 -.741)scale(2.52746 1.24129)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="igPjEgw" cx="0" cy="0" r="1" gradientTransform="matrix(1.08517 -2.48382 2.02575 .88503 21.328 10.732)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="i8tITAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.25397 1.55594 -1.37379 1.10717 15.01 2.063)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="i0mRm8p" cx="0" cy="0" r="1" gradientTransform="matrix(1.83271 -3.83426 1.3248 .63323 21.28 7.597)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ihkhvFc" cx="0" cy="0" r="1" gradientTransform="matrix(.32987 1.2819 -2.10752 .54233 16.866 2.063)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="izFEA6d" cx="0" cy="0" r="1" gradientTransform="matrix(1.39816 2.01957 -4.2027 2.90956 10.454 3.655)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iJSrUrr" cx="0" cy="0" r="1" gradientTransform="rotate(155.748 7.926 5.581)scale(9.98479 12.4938)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="ign0hEd" cx="0" cy="0" r="1" gradientTransform="rotate(-76.373 15.994 -7.058)scale(1.05502 2.31454)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="i4jXi8d" cx="0" cy="0" r="1" gradientTransform="rotate(-103.627 10.425 -.012)scale(1.05502 2.31454)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="i0ncvsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 22.424 13.864)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iQzAzTm" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.524 14.188)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iOE338E" cx="0" cy="0" r="1" gradientTransform="matrix(1.60227 1.22796 -.50064 .65325 11.994 11.955)" gradientUnits="userSpaceOnUse"><stop class="f9orwjbsj"/><stop offset="1" class="o7ej1q_7k"/></radialGradient><radialGradient id="ivRWdAd" cx="0" cy="0" r="1" gradientTransform="matrix(1 2.48437 -.40982 .16496 15.486 11.687)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="iiOCBMd" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.314 9.531)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="irAb3wv" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.595 8.718)" gradientUnits="userSpaceOnUse"><stop class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="iTOS50d" cx="0" cy="0" r="1" gradientTransform="matrix(-.29552 3.9685 -.3574 -.02661 22.61 10.578)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="nl6pfdccl"/><stop offset="1" class="noux9m6yk"/></radialGradient><radialGradient id="isbzh0b" cx="0" cy="0" r="1" gradientTransform="rotate(139.873 10.295 10.232)scale(2.23046 2.64338)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="yomsttbzk"/><stop offset="1" class="gduc03b1p"/></radialGradient><radialGradient id="izNv5qn" cx="0" cy="0" r="1" gradientTransform="matrix(-3.40626 .93747 -.39961 -1.45197 22.216 19.688)" gradientUnits="userSpaceOnUse"><stop class="wzor__shc"/><stop offset="1" class="v-1d3bc7d"/></radialGradient><radialGradient id="iv5cwKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.29332 10.73456 -3.15485 .674 23.298 21.265)" gradientUnits="userSpaceOnUse"><stop class="dtygiz9_c"/><stop offset="1" class="cz7bliorf"/></radialGradient><linearGradient id="igkZFkd" x1="13.046" x2="14.526" y1="21.109" y2="21.109" gradientUnits="userSpaceOnUse"><stop class="a9w0npdui"/><stop offset="1" class="gjaf2hfdw"/></linearGradient><linearGradient id="iP9ug0d" x1="9.992" x2="9.183" y1="13.278" y2="13.278" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iRUxkrc" x1="23.38" x2="22.346" y1="11.548" y2="14.751" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i4mEFQH" x1="21.087" x2="11.441" y1="13.418" y2="14.856" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset="1" class="x2e45tbep"/></linearGradient><linearGradient id="i3TRcxd" x1="9.174" x2="12.094" y1="16.824" y2="16.443" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="ieSUfic" x1="15.5" x2="15.5" y1="21.219" y2="20.578" gradientUnits="userSpaceOnUse"><stop class="ykr_hnwfb"/><stop offset="1" class="z2mzyybfg"/></linearGradient><linearGradient id="i5d1Nbd" x1="9.849" x2="13.514" y1="12.589" y2="6.078" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iAzGnHr" x1="18.252" x2="15.551" y1="8.443" y2="19.11" gradientUnits="userSpaceOnUse"><stop class="f8pv0zkqn"/><stop offset="1" class="qbc-5zb2i"/></linearGradient><linearGradient id="iaYUHub" x1="20.454" x2="20.552" y1="19.418" y2="19.781" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p3v2l8b8s"/><stop offset="1" class="cd065ixil"/></linearGradient><linearGradient id="i5GPM6b" x1="19.704" x2="26.142" y1="28.109" y2="26.734" gradientUnits="userSpaceOnUse"><stop class="n2xirpb3k"/><stop offset="1" class="rdd-97n4h"/></linearGradient><linearGradient id="iVn4NZd" x1="18.5" x2="19.719" y1="27.781" y2="27.406" gradientUnits="userSpaceOnUse"><stop class="pjq5kjqnj"/><stop offset="1" class="luw53jggo"/></linearGradient><linearGradient id="iYPt2ld" x1="20.154" x2="20.498" y1="20.375" y2="21.813" gradientUnits="userSpaceOnUse"><stop offset=".19" class="qp1xf-bno"/><stop offset="1" class="kzp7x6blp"/></linearGradient><linearGradient id="ia3oUzp" x1="18.929" x2="20.216" y1="8.577" y2="17.532" gradientUnits="userSpaceOnUse"><stop class="q1m7atbak"/><stop offset="1" class="ov_c3kn0b"/></linearGradient><linearGradient id="igqSI3D" x1="16.679" x2="17.492" y1="10.43" y2="14.143" gradientUnits="userSpaceOnUse"><stop class="q1m7atbak"/><stop offset="1" class="ov_c3kn0b"/></linearGradient><linearGradient id="iEcoShc" x1="14.96" x2="15.917" y1="12.665" y2="14.793" gradientUnits="userSpaceOnUse"><stop class="q1m7atbak"/><stop offset="1" class="ov_c3kn0b"/></linearGradient><linearGradient id="ifBEBBq" x1="22.525" x2="22.57" y1="12.637" y2="18.702" gradientUnits="userSpaceOnUse"><stop class="q1m7atbak"/><stop offset="1" class="ov_c3kn0b"/></linearGradient><linearGradient id="ivAvU7d" x1="21.283" x2="21.548" y1="9.015" y2="17.672" gradientUnits="userSpaceOnUse"><stop class="q1m7atbak"/><stop offset="1" class="ov_c3kn0b"/></linearGradient><filter id="iDZZbgc" width="20.98" height="11.16" x="6.01" y="19.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.521569 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4108"/></filter><filter id="iP3PTwb" width="3.513" height="3.513" x="8.235" y="11.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".25"/></filter><filter id="ive3cVc" width="4.467" height="4.467" x="19.899" y="10.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4108"/></filter><filter id="iJTDKIe" width="3.513" height="3.513" x="20.251" y="11.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".25"/></filter><filter id="iQDx8Vc" width="15.917" height="10.659" x="8.031" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4108"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4108" result="effect2_innerShadow_4002_4108"/></filter><filter id="i6vW7bd" width="3.287" height="2.014" x="17.585" y="8.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4108"/></filter><filter id="iM4iwic" width="3.142" height="1.621" x="17.657" y="8.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".2"/></filter><filter id="ilAUjyd" width="3.287" height="2.014" x="11.107" y="8.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4108"/></filter><filter id="iwYaq7d" width="3.142" height="1.621" x="11.178" y="8.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".2"/></filter><filter id="i05HgbR" width="12.214" height="13.502" x="12.145" y="7.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".625"/></filter><filter id="ij2ImBc" width="3.412" height="1.462" x="11.792" y="11.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.2 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4108"/></filter><filter id="i7zDAQe" width="12.047" height="12.796" x="13.464" y="7.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.607843 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4108"/></filter><filter id="iwmczub" width="3.875" height="7.906" x="17.079" y="6.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".5"/></filter><filter id="iTBXfMO" width="4.36" height="7" x="14.861" y="8.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".5"/></filter><filter id="i8Dd9rc" width="4.235" height="5.719" x="13.142" y="10.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".5"/></filter><filter id="iIVSXKd" width="4.938" height="8.906" x="20.439" y="10.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".5"/></filter><filter id="iZQaDmc" width="3.672" height="11.438" x="19.579" y="7.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4108" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-facepalming" /></template>
<style>
.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.a9w0npdui {
  stop-color: var(--svg-color--ba8138, #BA8138);
}

.ah2mmqbwe {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.703 9.93c.264-.243 1.014-.656 2.093-.555");
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ay8x0ubqe {
  d: path("M17.88 20.42a.25.25 0 0 1 .182-.302l4.733-1.204a.25.25 0 0 1 .305.183l.274 1.13l-5.229 1.268z");
}

.az3fkmbzf {
  stop-color: var(--svg-color--e3823a, #E3823A);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c5rrs6bxi {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m22.076 4.745l.542.27c.948.47 1.49 1.549 1.287 2.694l-.745 3.84c-.067.396-.329.663-.723.673c.045-.636.087-1.662.104-1.825c.055-.547-.032-.708-.533-1.206c-.271-.27-.474-.674-.474-1.078V7.035c0-.337-.271-.606-.542-.674c-.813-.202-2.507-.539-4.946-.539c-2.44 0-4.133.337-4.946.54c-.339.067-.542.336-.542.673v1.078c0 .404-.136.808-.474 1.078l-.204.202c-.27.202-.407.624-.407.96c.018.197.044 1.329.074 1.8a.8.8 0 0 1-.75-.672l-.746-3.84c-.135-1.077.407-2.155 1.355-2.627c1.28-.561 1.747-1.413 2.778-2.29c.745-.674 1.83-.876 2.778-.405a3.7 3.7 0 0 0 2.1 0c1.016-.336 2.168-.067 2.981.674l1.016 1.01c.271.337.61.54 1.017.742");
}

.cd065ixil {
  stop-color: var(--svg-color--256abd, #256ABD);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.cz7bliorf {
  stop-color: var(--svg-color--31a8ff, #31A8FF);
  stop-opacity: 0;
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dfl74__zr {
  stroke-linecap: round;
  d: path("m23.876 12.484l-.937 1.89a3.56 3.56 0 0 0-.36 1.782c.079.969-.265 1.828-.64 2.234");
}

.dtygiz9_c {
  stop-color: var(--svg-color--48c9ff, #48C9FF);
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f1l8tljlq {
  fill: var(--svg-color--8a0051, #8A0051);
  d: path("M18.191 17.484a2.47 2.47 0 0 0-2.06-1.12c-.861 0-1.618.45-2.059 1.12c-.095.144.039.316.192.297h3.726c.164 0 .297-.144.201-.297");
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f8pv0zkqn {
  stop-color: var(--svg-color--f47b25, #F47B25);
}

.f9orwjbsj {
  stop-color: var(--svg-color--b25e4e, #B25E4E);
}

.ft5dv1b6b {
  fill: none;
}

.fy301klzq {
  cx: 9.992px;
  cy: 12.927px;
  r: 1.257px;
}

.g_dz4cd7h {
  stroke-linecap: round;
  d: path("m21.08 8.797l.671 8.437");
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.gduc03b1p {
  stop-color: var(--svg-color--ffe549, #FFE549);
  stop-opacity: 0;
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gjaf2hfdw {
  stop-color: var(--svg-color--ba8138, #BA8138);
  stop-opacity: 0;
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gslsq1v8t {
  stop-color: var(--svg-color--db9d3b, #DB9D3B);
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.h0-blzbbk {
  stop-color: var(--svg-color--c86f29, #C86F29);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i_3i3cgxw {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.275 9.962c-.264-.243-1.014-.656-2.093-.555");
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.id2v71bmv {
  d: path("M21.596 14.236a2 2 0 0 0 1.09-.372v1.123a2.62 2.62 0 0 1-1.616 2.435q.309-.658.417-1.424z");
}

.itdj3x85b {
  stroke-linecap: round;
  d: path("m14.642 12.172l1.234 2.718");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kd9sqzn4j {
  cx: 22.008px;
  cy: 12.927px;
  r: 2.109px;
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kk8ms1szj {
  stop-color: var(--svg-color--cf8352, #CF8352);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.kzp7x6blp {
  stop-color: var(--svg-color--1b92fc, #1B92FC);
  stop-opacity: 0;
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.lsv4v5blf {
  stroke-linecap: round;
  d: path("m16.36 10.094l1.36 4");
}

.lt_6sfbfh {
  cx: 22.008px;
  cy: 12.927px;
  r: 1.257px;
}

.luw53jggo {
  stop-color: var(--svg-color--387fe2, #387FE2);
  stop-opacity: 0;
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.n-s36oh9s {
  stop-color: var(--svg-color--1e74f4, #1E74F4);
  stop-opacity: 0;
}

.n2xirpb3k {
  stop-color: var(--svg-color--2478eb, #2478EB);
}

.nl6pfdccl {
  stop-color: var(--svg-color--f69202, #F69202);
}

.noux9m6yk {
  stop-color: var(--svg-color--f69202, #F69202);
  stop-opacity: 0;
}

.o7ej1q_7k {
  stop-color: var(--svg-color--98353d, #98353D);
}

.onff_pbvz {
  d: path("M25.99 29.925v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.ov_c3kn0b {
  stop-color: var(--svg-color--ffe648, #FFE648);
  stop-opacity: 0;
}

.p_at91bjt {
  d: path("M9.548 12.153a38 38 0 0 1-.074-1.817c0-.337.136-.741.407-.943l.203-.202c.338-.27.474-.674.474-1.078V7.035c0-.337.203-.606.542-.674c.813-.202 2.507-.539 4.946-.539s4.133.337 4.946.54c.27.067.542.336.542.673v1.078c0 .404.203.808.474 1.078c.634.444.595.688.542 1.212c-.016.162-.068 1.509-.113 1.819l-.335 5c-.203 2.235-1.96 3.793-4.055 3.793h-4.055c-2.163 0-3.853-1.558-4.055-3.793z");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p1b01acps {
  stroke-linecap: round;
  d: path("m18.58 8.422l.875 4.906");
}

.p3v2l8b8s {
  stop-color: var(--svg-color--256abd, #256ABD);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pjq5kjqnj {
  stop-color: var(--svg-color--387fe2, #387FE2);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q1m7atbak {
  stop-color: var(--svg-color--ffe648, #FFE648);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qbc-5zb2i {
  stop-color: var(--svg-color--ea802c, #EA802C);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qp1xf-bno {
  stop-color: var(--svg-color--2291e1, #2291E1);
}

.qvg0urbpt {
  stop-color: var(--svg-color--2365ae, #2365AE);
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.r-0b0ebfr {
  d: path("M16 22.922c-1.438 0-2.605-.605-2.605-1.969V17.58c0-1.365 1.167-2.471 2.605-2.471s2.605 1.106 2.605 2.47v3.375c0 1.364-1.167 1.969-2.605 1.969");
}

.rdd-97n4h {
  stop-color: var(--svg-color--4daefd, #4DAEFD);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rrj20zcfg {
  d: path("m22.076 4.745l.542.27c.948.47 1.49 1.549 1.287 2.694l-.745 3.84c-.067.396-.329.663-.723.673c.045-.636.087-1.662.104-1.825c.055-.547-.032-.708-.533-1.206c-.271-.27-.474-.674-.474-1.078V7.035c0-.337-.271-.606-.542-.674c-.813-.202-2.507-.539-4.946-.539c-2.44 0-4.133.337-4.946.54c-.339.067-.542.336-.542.673v1.078c0 .404-.136.808-.474 1.078l-.204.202c-.27.202-.407.624-.407.96c.018.197.044 1.329.074 1.8a.8.8 0 0 1-.75-.672l-.746-3.84c-.135-1.077.407-2.155 1.355-2.627c1.28-.561 1.747-1.413 2.778-2.29c.745-.674 1.83-.876 2.778-.405a3.7 3.7 0 0 0 2.1 0c1.016-.336 2.168-.067 2.981.674l1.016 1.01c.271.337.61.54 1.017.742");
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tvvtj8d6u {
  d: path("M17.44 8.46a.946.946 0 0 1 1.108.75l.356 1.85l-.086-1.383a.946.946 0 1 1 1.888-.118l.197 3.17l.327-.674a.989.989 0 1 1 1.78.863l-.817 1.683c-.174.42-.182.808-.19 1.218c-.009.374-.017.768-.152 1.222c-.236.795-.707 1.433-.913 1.652l-2.634.753c-2.028-.497-2.646-1.653-2.982-2.62a13 13 0 0 0-.658-1.585l-1.162-2.238a.946.946 0 1 1 1.678-.872l.194.372l-.463-1.349a.946.946 0 0 1 1.79-.614l.404 1.18l-.415-2.152a.946.946 0 0 1 .75-1.107");
}

.ugnp-5bfk {
  fill-rule: evenodd;
  d: path("M15.065 12.158c.15.109.184.32.074.47a2.02 2.02 0 0 1-1.641.827a2.05 2.05 0 0 1-1.639-.824a.336.336 0 0 1 .538-.403c.256.34.656.555 1.1.555c.457 0 .855-.215 1.099-.551a.337.337 0 0 1 .47-.074");
}

.un1s7042i {
  cx: 9.992px;
  cy: 12.927px;
  r: 2.109px;
}

.v-1d3bc7d {
  stop-color: var(--svg-color--2469bc, #2469BC);
}

.w3nqf8i5r {
  d: path("M17.317 22.494a1 1 0 0 1 .723-1.22l5.303-1.34a1 1 0 0 1 1.213.719l2.414 9.289h-7.719z");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wzor__shc {
  stop-color: var(--svg-color--489ee3, #489EE3);
}

.x-y69psvt {
  fill-rule: evenodd;
  d: path("M18.237 10.14c.91-.084 1.492.27 1.634.4a.597.597 0 1 0 .808-.876c-.387-.357-1.303-.828-2.553-.711a.596.596 0 1 0 .111 1.188");
}

.x2e45tbep {
  stop-color: var(--svg-color--ffac1b, #FFAC1B);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xm1eavbhd {
  fill: var(--svg-color--1e7ce6, #1E7CE6);
  d: path("M25.99 29.925v-.39c0-5.39-4.47-9.77-9.99-9.77c-5.52.01-9.99 4.38-9.99 9.77v.39z");
}

.xp6xvybaw {
  stop-color: var(--svg-color--266df8, #266DF8);
}

.xpfn1uy9q {
  fill: var(--svg-color--ffca3d, #FFCA3D);
  d: path("M18.168 7.662a1.1 1.1 0 0 1 1.288.872l.415 2.15l-.1-1.608a1.1 1.1 0 1 1 2.195-.137l.23 3.687l.38-.784a1.15 1.15 0 1 1 2.07 1.003l-.95 1.958c-.203.488-.212.94-.222 1.417c-.01.435-.019.892-.176 1.42c-.275.925-.823 1.667-1.062 1.922l-3.063.875c-2.36-.578-3.078-1.922-3.468-3.047c-.313-.9-.641-1.604-.766-1.843l-1.351-2.603a1.1 1.1 0 0 1 1.952-1.014l.225.433l-.539-1.569a1.1 1.1 0 0 1 2.082-.714l.47 1.373l-.482-2.503a1.1 1.1 0 0 1 .872-1.288");
}

.y9f8y_b6f {
  d: path("M18.168 7.662a1.1 1.1 0 0 1 1.288.872l.415 2.15l-.1-1.608a1.1 1.1 0 1 1 2.195-.137l.23 3.687l.38-.784a1.15 1.15 0 1 1 2.07 1.003l-.95 1.958c-.203.488-.212.94-.222 1.417c-.01.435-.019.892-.176 1.42c-.275.925-.823 1.667-1.062 1.922l-3.063.875c-2.36-.578-3.078-1.922-3.468-3.047c-.313-.9-.641-1.604-.766-1.843l-1.351-2.603a1.1 1.1 0 0 1 1.952-1.014l.225.433l-.539-1.569a1.1 1.1 0 0 1 2.082-.714l.47 1.373l-.482-2.503a1.1 1.1 0 0 1 .872-1.288");
}

.ykr_hnwfb {
  stop-color: var(--svg-color--cc7172, #CC7172);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yu7mlobzw {
  stop-color: var(--svg-color--2365ae, #2365AE);
  stop-opacity: 0;
}

.z2mzyybfg {
  stop-color: var(--svg-color--cd7556, #CD7556);
  stop-opacity: 0;
}

.zium8mc3e {
  fill-rule: evenodd;
  d: path("M13.741 10.109c-.909-.085-1.492.27-1.633.4a.596.596 0 1 1-.809-.877c.387-.357 1.303-.828 2.553-.711a.597.597 0 0 1-.11 1.188");
}

.zlivpjjso {
  cx: 22.008px;
  cy: 12.927px;
  r: 1.257px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
