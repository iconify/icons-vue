<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSGQ2uc)"><path fill="url(#iOKd1Md)" class="w45c8mg_n"/><path fill="url(#iP9jkmY)" class="w45c8mg_n"/></g><path fill="url(#icFKa2b)" class="w45c8mg_n"/><path fill="url(#iLiapnd)" class="n0di03lui"/><path fill="url(#iy5kqVb)" class="n0di03lui"/><path fill="url(#iXw6soe)" class="goamc_brz"/><path fill="url(#iLwDf2c)" class="goamc_brz"/><path fill="url(#iT4LbIc)" class="kcorxra1y"/><g filter="url(#iF7J7pd)"><path class="vuo1an55t"/><path fill="url(#iF9a92c)" class="yiugnhb3z"/></g><path fill="url(#iepXYOe)" class="sdaphlkml"/><path fill="url(#iDpyvBn)" class="sdaphlkml"/><path fill="url(#iDhnB9c)" class="sdaphlkml"/><g filter="url(#ic2jN7d)"><path class="g92_8_btw"/></g><g filter="url(#iKiqtTl)"><path fill="url(#i8ha3mc)" class="h1w__zbkb"/><path fill="url(#ihNsEAb)" class="h1w__zbkb"/><path fill="url(#iWk2Byb)" class="h1w__zbkb"/><path fill="url(#iLiASpb)" class="h1w__zbkb"/><path fill="url(#iTD8Wfc)" class="h1w__zbkb"/></g><g filter="url(#iH2UPad)"><path class="dzgv6mb2z"/></g><g filter="url(#izzhJXd)"><path class="rungqkwwx"/></g><g filter="url(#iibrDmR)"><path class="jbrydubyf"/><path fill="url(#idTg4BB)" class="psqk2pbxf"/><path fill="url(#iuNMYJd)" class="psqk2pbxf"/></g><g filter="url(#itvfaXq)"><path class="ib2ehb0yz"/><path fill="url(#iRjVeye)" class="summtbtdy"/></g><path fill="url(#ivp7G8b)" class="mxq3i9b3i"/><path fill="url(#iHsjOVc)" class="ijir-hxla"/><path fill="url(#iYNtgdN)" class="ijir-hxla"/><g filter="url(#ie6a4Vd)"><path class="jxz1dzg3f"/></g><g filter="url(#iZTmUCc)"><path class="pdbw0fbip"/></g><g filter="url(#i6BcLGe)"><path class="usnsepd-y"/></g><g clip-rule="evenodd" filter="url(#ifIK5Yb)" class="d2kvgvbvc"><path class="q0qnzuewi"/><path fill="url(#iJt0fbd)" class="p9gagp09o"/></g><path class="v8z2i9i0d"/><g filter="url(#iXT3sts)"><path fill="url(#i54uPBb)" class="i3y62md1z"/><path fill="url(#i8NvqDe)" class="i3y62md1z"/><path fill="url(#iOKBZKc)" class="i3y62md1z"/><path fill="url(#in7v2Qd)" class="i3y62md1z"/><path fill="url(#i0ZK5Od)" class="i3y62md1z"/><path fill="url(#iiZlgfd)" class="i3y62md1z"/></g><path fill="url(#iuJVvfc)" class="ccra0xskq"/><path fill="url(#iVr2nxi)" class="ccra0xskq"/><path fill="url(#iG9tvVf)" class="wy7qqvbub"/><path fill="url(#iG1dmHb)" class="wy7qqvbub"/><g filter="url(#iQ0egRd)"><path class="rxci6fbpp"/></g><g filter="url(#iC2Esdu)"><path class="ztdylzwtd"/></g><g filter="url(#itaQ1bd)"><path class="d85s3vm4i"/></g><g filter="url(#iHuE7Fc)"><path stroke="url(#iZIMTdc)" class="aqswvcuut"/></g><g filter="url(#i8FzGsc)"><path stroke="url(#iQHkJqd)" class="ogao-rb8k"/></g><g filter="url(#iucIuNA)"><path class="d8th2gydh"/></g><defs><radialGradient id="iP9jkmY" cx="0" cy="0" r="1" gradientTransform="rotate(161.322 8.287 15.115)scale(5.27798 10.393)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="f8_tgzbue"/><stop offset="1" class="v_-r5lbgt"/></radialGradient><radialGradient id="icFKa2b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.07686 2.88187 -1.88528 -3.9754 14.768 19.666)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="vzyrucblm"/><stop offset="1" class="a2i8hds4q"/></radialGradient><radialGradient id="iLiapnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.93285 -3.98995 0 15.583 19.961)" gradientUnits="userSpaceOnUse"><stop offset=".49" class="qeqv8acyn"/><stop offset="1" class="j4znd5bge"/></radialGradient><radialGradient id="iy5kqVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.17187 -.58594 0 13.188 20.781)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="i3xvtgq6p"/><stop offset="1" class="vglza9plq"/></radialGradient><radialGradient id="iXw6soe" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 22.284 14.305)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iLwDf2c" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.385 14.629)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iT4LbIc" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 -6.977 14.265)scale(3.58066 1.62757)" gradientUnits="userSpaceOnUse"><stop class="cy485ebzy"/><stop offset="1" class="pi95o6_xg"/></radialGradient><radialGradient id="iF9a92c" cx="0" cy="0" r="1" gradientTransform="rotate(114.356 6.266 9.529)scale(4.56231 3.13463)" gradientUnits="userSpaceOnUse"><stop class="y40rkpbmj"/><stop offset="1" class="b8lpz_bho"/></radialGradient><radialGradient id="iepXYOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.4855 7.35906 -2.7055 -.17849 21.813 12.89)" gradientUnits="userSpaceOnUse"><stop class="id19h77qj"/><stop offset="1" class="v6h3qtb9x"/></radialGradient><radialGradient id="iDpyvBn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.70515 2.05291 0 13.07 11.746)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="w3o5239uo"/><stop offset="1" class="uo4-a-q-g"/></radialGradient><radialGradient id="iDhnB9c" cx="0" cy="0" r="1" gradientTransform="matrix(4.01332 -4.5 .9586 .85492 9.487 8.578)" gradientUnits="userSpaceOnUse"><stop class="g86mcjych"/><stop offset="1" class="ub-l1fbpr"/></radialGradient><radialGradient id="ihNsEAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.22268 10.6787 0 9.286 9.682)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iWk2Byb" cx="0" cy="0" r="1" gradientTransform="matrix(.13754 -3.03019 5.3689 .24369 21.455 11.262)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iLiASpb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8448 -1.87103 1.37344 -2.08823 20.546 3.692)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iTD8Wfc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0916 1.77888 -4.11904 2.52761 14.5 1.772)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="idTg4BB" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65461 0 0 -.98523 15.899 4.497)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iuNMYJd" cx="0" cy="0" r="1" gradientTransform="matrix(3.88123 -6.1452 6.80825 4.3 9.043 9.251)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iRjVeye" cx="0" cy="0" r="1" gradientTransform="matrix(3.91742 .45788 -.1917 1.64015 17.7 7.443)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iYNtgdN" cx="0" cy="0" r="1" gradientTransform="matrix(-.49793 2.50374 -2.4614 -.48951 9.246 12.284)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ml5rhcc2b"/><stop offset="1" class="w61k36btm"/></radialGradient><radialGradient id="iJt0fbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3711 .9961 -.44329 .61017 11.605 12.8)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="sozvcjboj"/><stop offset=".568" class="b8btyqb8s"/></radialGradient><radialGradient id="i54uPBb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12305 8.4804 -7.48749 -1.87448 21.095 12.398)" gradientUnits="userSpaceOnUse"><stop class="wkradz6bg"/><stop offset="1" class="sl7z3ibwx"/></radialGradient><radialGradient id="i8NvqDe" cx="0" cy="0" r="1" gradientTransform="matrix(1 2.48437 -.40982 .16496 15.346 12.129)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="iOKBZKc" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.174 9.972)" gradientUnits="userSpaceOnUse"><stop class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="in7v2Qd" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.455 9.16)" gradientUnits="userSpaceOnUse"><stop class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="i0ZK5Od" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 6.564 15.391)scale(3.93108 .49375)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="rk9yz2b8g"/><stop offset="1" class="mleb6mb5e"/></radialGradient><radialGradient id="iiZlgfd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.87 11.495 7.067)scale(1.98874 3.13779)" gradientUnits="userSpaceOnUse"><stop class="m2_juxbhz"/><stop offset="1" class="rfz2yfljl"/></radialGradient><radialGradient id="iuJVvfc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.96874 1.06253 -.45292 -1.69174 22.94 19.957)" gradientUnits="userSpaceOnUse"><stop class="yzag7e8_g"/><stop offset="1" class="tgllzx6xq"/></radialGradient><radialGradient id="iG1dmHb" cx="0" cy="0" r="1" gradientTransform="rotate(76.973 -2.072 25.417)scale(8.17927 4.47567)" gradientUnits="userSpaceOnUse"><stop class="awna98bfd"/><stop offset="1" class="i4docjyne"/></radialGradient><filter id="iSGQ2uc" width="20.98" height="11.177" x="5.603" y="20.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.423529 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/></filter><filter id="iF7J7pd" width="13.076" height="15.613" x="9.487" y="5.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0745098 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4109" result="effect2_innerShadow_4002_4109"/></filter><filter id="ic2jN7d" width="12.214" height="13.502" x="12.005" y="7.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".625"/></filter><filter id="iKiqtTl" width="15.525" height="9.975" x="7.831" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4109" result="effect2_innerShadow_4002_4109"/></filter><filter id="iH2UPad" width="2.8" height="1.394" x="17.51" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/></filter><filter id="izzhJXd" width="2.8" height="1.377" x="11.17" y="9.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/></filter><filter id="iibrDmR" width="8.338" height="7.623" x="8.061" y="3.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/><feGaussianBlur result="effect2_foregroundBlur_4002_4109" stdDeviation=".25"/></filter><filter id="itvfaXq" width="8.12" height="7.367" x="15.151" y="3.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/><feGaussianBlur result="effect2_foregroundBlur_4002_4109" stdDeviation=".25"/></filter><filter id="ie6a4Vd" width="1.5" height="2.767" x="8.283" y="11.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".125"/></filter><filter id="iZTmUCc" width="2.051" height="3.216" x="21.118" y="11.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".15"/></filter><filter id="i6BcLGe" width="2.746" height="1.245" x="11.15" y="9.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".125"/></filter><filter id="ifIK5Yb" width="3.412" height="1.562" x="11.244" y="12.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0392157 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/></filter><filter id="iXT3sts" width="11.547" height="12.796" x="13.324" y="8.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.137255 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4109"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.215686 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4109" result="effect2_innerShadow_4002_4109"/></filter><filter id="iQ0egRd" width="2.467" height="5.606" x="17.564" y="7.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".25"/></filter><filter id="iC2Esdu" width="2.78" height="4.622" x="15.346" y="9.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".25"/></filter><filter id="itaQ1bd" width="2.438" height="3.281" x="13.906" y="11.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".25"/></filter><filter id="iHuE7Fc" width="3.688" height="7.656" x="20.862" y="12.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".25"/></filter><filter id="i8FzGsc" width="2.422" height="10.188" x="20.064" y="8.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".25"/></filter><filter id="iucIuNA" width="6.067" height="3.146" x="16.854" y="4.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4109" stdDeviation=".3"/></filter><linearGradient id="iOKd1Md" x1="20.291" x2="5.914" y1="27.469" y2="30.374" gradientUnits="userSpaceOnUse"><stop class="ee6wyldiv"/><stop offset="1" class="lrdcrkb9v"/></linearGradient><linearGradient id="i8ha3mc" x1="23.857" x2="9.852" y1="6.341" y2="6.341" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ivp7G8b" x1="23.355" x2="21.9" y1="12.162" y2="14.787" gradientUnits="userSpaceOnUse"><stop class="eghj5eb6n"/><stop offset="1" class="yr1b81w8m"/></linearGradient><linearGradient id="iHsjOVc" x1="8.538" x2="10.297" y1="13.011" y2="12.858" gradientUnits="userSpaceOnUse"><stop class="b6ilcbc-v"/><stop offset="1" class="lzduf8g5l"/></linearGradient><linearGradient id="iVr2nxi" x1="20.314" x2="20.396" y1="19.859" y2="20.152" gradientUnits="userSpaceOnUse"><stop offset=".245" class="f8osbx-ej"/><stop offset="1" class="oxk0gpbzd"/></linearGradient><linearGradient id="iG9tvVf" x1="19.564" x2="26.002" y1="28.55" y2="27.175" gradientUnits="userSpaceOnUse"><stop class="uu8x24bjn"/><stop offset="1" class="gmelrdffb"/></linearGradient><linearGradient id="iZIMTdc" x1="23.907" x2="21.737" y1="12.732" y2="16.545" gradientUnits="userSpaceOnUse"><stop class="hgr8iwbbk"/><stop offset="1" class="oai-xmbha"/></linearGradient><linearGradient id="iQHkJqd" x1="20.939" x2="21.611" y1="10.812" y2="18.031" gradientUnits="userSpaceOnUse"><stop class="hgr8iwbbk"/><stop offset="1" class="oai-xmbha"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-facepalming-dark" /></template>
<style>
.a2i8hds4q {
  stop-color: var(--svg-color--9f3b09, #9F3B09);
  stop-opacity: 0;
}

.aqswvcuut {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m23.675 12.908l-.938 1.89a3.56 3.56 0 0 0-.36 1.782c.08.969-.265 1.828-.64 2.234");
}

.awna98bfd {
  stop-color: var(--svg-color--ff9946, #FF9946);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b6ilcbc-v {
  stop-color: var(--svg-color--342224, #342224);
}

.b8btyqb8s {
  stop-color: var(--svg-color--262626, #262626);
  stop-opacity: 0;
}

.b8lpz_bho {
  stop-color: var(--svg-color--4d4241, #4D4241);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ccra0xskq {
  d: path("M17.74 20.862a.25.25 0 0 1 .182-.302l4.733-1.205a.25.25 0 0 1 .305.183l.274 1.131l-5.229 1.267z");
}

.cy485ebzy {
  stop-color: var(--svg-color--48413f, #48413F);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d85s3vm4i {
  stroke: var(--svg-color--655553, #655553);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.781 12.719l.688 1.531");
}

.d8th2gydh {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.768 6.341h-2.69a.626.626 0 1 1 .1-1.242c.697.111 1.624.266 2.245.42c1.403.348 1.79 1.03 1.898 1.518a1.96 1.96 0 0 0-1.554-.696");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dzgv6mb2z {
  fill: var(--svg-color--202020, #202020);
  d: path("M20.095 9.948c-.211-.184-.457-.379-.83-.496c-.366-.116-.826-.147-1.462-.069a.334.334 0 1 0 .082.664c.58-.07.936-.034 1.18.043c.24.075.4.197.59.363a.335.335 0 0 0 .44-.505");
}

.ee6wyldiv {
  stop-color: var(--svg-color--f84d1b, #F84D1B);
}

.eghj5eb6n {
  stop-color: var(--svg-color--4c3430, #4C3430);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f8_tgzbue {
  stop-color: var(--svg-color--ff5016, #FF5016);
}

.f8osbx-ej {
  stop-color: var(--svg-color--d74a13, #D74A13);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g86mcjych {
  stop-color: var(--svg-color--211011, #211011);
}

.g92_8_btw {
  fill: var(--svg-color--291819, #291819);
  d: path("M17.3 8.902a.946.946 0 0 1 1.108.75l.356 1.849l-.086-1.383A.946.946 0 0 1 20.566 10l.197 3.17l.327-.675a.989.989 0 0 1 1.78.863l-.817 1.683c-.174.42-.182.808-.19 1.219c-.008.374-.017.767-.152 1.221c-.236.796-.707 1.433-.913 1.653l-2.634.752c-2.028-.497-2.646-1.652-2.982-2.62a13 13 0 0 0-.659-1.585l-1.161-2.238a.946.946 0 0 1 1.678-.872l.194.372l-.463-1.349a.946.946 0 0 1 1.79-.613l.404 1.18l-.415-2.152a.946.946 0 0 1 .75-1.108");
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.goamc_brz {
  d: path("M21.456 14.677c.404-.013.783-.15 1.09-.372v1.123a2.62 2.62 0 0 1-1.616 2.435q.309-.658.417-1.423z");
}

.h1w__zbkb {
  d: path("M21.448 5.158a2.8 2.8 0 0 1 1.529 1.268c.563.99.48 2.174-.128 3.047a1.9 1.9 0 0 0-.326 1.054v1.433a2.1 2.1 0 0 0-.805-.323l.095-1.938a1.75 1.75 0 0 0-1.663-1.727h-1.69a2.92 2.92 0 0 1-2.666-1.74a.8.8 0 0 0-.742-.504h-1.536c-2.226 0-4.03 1.824-4.03 4.075l.038 1.854c-.307.045-.627.147-.869.318v-1.448a1.9 1.9 0 0 0-.326-1.054a2.88 2.88 0 0 1-.173-2.95a2.83 2.83 0 0 1 1.567-1.358a3.23 3.23 0 0 0 1.67-1.34a2.804 2.804 0 0 1 3.486-1.099c.46.2.979.2 1.44 0c.338-.142.71-.226 1.1-.226c1.016 0 1.905.55 2.398 1.365c.371.614.953 1.06 1.631 1.293");
}

.hgr8iwbbk {
  stop-color: var(--svg-color--655553, #655553);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i3xvtgq6p {
  stop-color: var(--svg-color--4e3a37, #4E3A37);
}

.i3y62md1z {
  d: path("M18.028 8.103a1.1 1.1 0 0 1 1.289.872l.414 2.15l-.1-1.608a1.1 1.1 0 0 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.957c-.203.489-.212.94-.222 1.417c-.01.435-.019.893-.176 1.42c-.275.926-.823 1.667-1.062 1.923l-3.063.875c-2.36-.579-3.078-1.922-3.469-3.047a15.5 15.5 0 0 0-.765-1.844l-1.351-2.602a1.1 1.1 0 0 1 1.952-1.014l.225.432l-.539-1.568a1.1 1.1 0 0 1 2.081-.714l.471 1.372l-.482-2.503a1.1 1.1 0 0 1 .872-1.288");
}

.i4docjyne {
  stop-color: var(--svg-color--ff9946, #FF9946);
  stop-opacity: 0;
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.ib2ehb0yz {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.88 10.464l-.035-.761c-.013-.92-.774-1.68-1.695-1.72h-1.69a2.92 2.92 0 0 1-2.56-1.517s-.132-.306-.225-.796c-.185-.986.732-1.717 1.721-1.548c1.252.214 2.765.622 3.855 1.333c2.104 1.372 1.736 3.846.629 5.01");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.id19h77qj {
  stop-color: var(--svg-color--62504d, #62504D);
}

.ijir-hxla {
  d: path("M9.516 10.945c-.943.133-1.685.926-1.685 1.905a1.94 1.94 0 0 0 1.834 1.937a93 93 0 0 1-.15-3.842");
}

.j4znd5bge {
  stop-color: var(--svg-color--472524, #472524);
}

.jbrydubyf {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M15.873 6.397a3 3 0 0 1-.08-.165a.8.8 0 0 0-.741-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075v.332c-.41-.312-.926-.97-.926-2.036c0-1.292.943-1.946 1.544-2.363c.17-.117.312-.216.399-.305l.12-.126c.422-.448 1.173-1.244 2.484-1.592a6.7 6.7 0 0 1 1.986-.193c.472.022.805.43.805.903V6.38z");
}

.jxz1dzg3f {
  fill: var(--svg-color--2c1c22, #2C1C22);
  d: path("M9.432 11.733a1.153 1.153 0 0 0 .1 2.267a94 94 0 0 1-.1-2.267");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kcorxra1y {
  d: path("M9.73 14.677a2 2 0 0 1-1.09-.372v1.123a2.62 2.62 0 0 0 1.616 2.435a5 5 0 0 1-.417-1.423z");
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.lrdcrkb9v {
  stop-color: var(--svg-color--e5571e, #E5571E);
}

.lzduf8g5l {
  stop-color: var(--svg-color--271419, #271419);
}

.m2_juxbhz {
  stop-color: var(--svg-color--6c5957, #6C5957);
}

.ml5rhcc2b {
  stop-color: var(--svg-color--3b2536, #3B2536);
  stop-opacity: 0;
}

.mleb6mb5e {
  stop-color: var(--svg-color--3f2a28, #3F2A28);
  stop-opacity: 0;
}

.mxq3i9b3i {
  d: path("M21.529 14.787q.121-1.924.223-3.849a1.941 1.941 0 0 1-.223 3.849");
}

.n0di03lui {
  d: path("M15.583 23.207c-1.46 0-2.64-.912-2.64-2.04v-2.411c0-1.128 1.18-2.04 2.64-2.04s2.64.912 2.64 2.04v2.41c0 1.129-1.18 2.04-2.64 2.04");
}

.oai-xmbha {
  stop-color: var(--svg-color--655553, #655553);
  stop-opacity: 0;
}

.ogao-rb8k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m20.94 9.238l.671 8.437");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oxk0gpbzd {
  stop-color: var(--svg-color--d74a13, #D74A13);
  stop-opacity: 0;
}

.p9gagp09o {
  d: path("M14.517 12.6c.15.108.183.318.074.469a2.02 2.02 0 0 1-1.641.827a2.05 2.05 0 0 1-1.639-.824a.336.336 0 1 1 .538-.403a1.372 1.372 0 0 0 2.198.005c.11-.15.32-.184.47-.075");
}

.pdbw0fbip {
  stroke: var(--svg-color--645553, #645553);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.577 14.002q.07-1.148.133-2.296a1.152 1.152 0 0 1-.133 2.296Z");
}

.pi95o6_xg {
  stop-color: var(--svg-color--231828, #231828);
}

.psqk2pbxf {
  d: path("M15.873 6.397a3 3 0 0 1-.08-.165a.8.8 0 0 0-.741-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075v.332c-.41-.312-.926-.97-.926-2.036c0-1.292.943-1.946 1.544-2.363c.17-.117.312-.216.399-.305l.12-.126c.422-.448 1.173-1.244 2.484-1.592a6.7 6.7 0 0 1 1.986-.193c.472.022.805.43.805.903V6.38z");
}

.q0qnzuewi {
  fill: var(--svg-color--0e0e0e, #0E0E0E);
  d: path("M14.517 12.6c.15.108.183.318.074.469a2.02 2.02 0 0 1-1.641.827a2.05 2.05 0 0 1-1.639-.824a.336.336 0 1 1 .538-.403a1.372 1.372 0 0 0 2.198.005c.11-.15.32-.184.47-.075");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qeqv8acyn {
  stop-color: var(--svg-color--361926, #361926);
}

.rfz2yfljl {
  stop-color: var(--svg-color--503438, #503438);
  stop-opacity: 0;
}

.rk9yz2b8g {
  stop-color: var(--svg-color--3f2a28, #3F2A28);
}

.rungqkwwx {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.48 9.817a3.35 3.35 0 0 1 2.097-.433a.335.335 0 0 1-.082.663a2.68 2.68 0 0 0-1.672.344a2 2 0 0 0-.11.072l-.004.002a.335.335 0 0 1-.41-.529z");
}

.rxci6fbpp {
  stroke: var(--svg-color--655553, #655553);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.44 8.863l.716 3.856");
}

.sdaphlkml {
  d: path("M9.774 17.037a4.72 4.72 0 0 0 4.686 4.107h2.276a4.72 4.72 0 0 0 4.686-4.107c.142-2.272.285-5.067.39-7.338a1.75 1.75 0 0 0-1.662-1.727h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.14 4.984.287 7.234");
}

.sl7z3ibwx {
  stop-color: var(--svg-color--482b34, #482B34);
}

.sozvcjboj {
  stop-color: var(--svg-color--262626, #262626);
}

.summtbtdy {
  d: path("m21.88 10.464l-.035-.761c-.013-.92-.774-1.68-1.695-1.72h-1.69a2.92 2.92 0 0 1-2.56-1.517s-.132-.306-.225-.796c-.185-.986.732-1.717 1.721-1.548c1.252.214 2.765.622 3.855 1.333c2.104 1.372 1.736 3.846.629 5.01");
}

.tgllzx6xq {
  stop-color: var(--svg-color--d54625, #D54625);
}

.ub-l1fbpr {
  stop-color: var(--svg-color--211011, #211011);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uo4-a-q-g {
  stop-color: var(--svg-color--341f24, #341F24);
  stop-opacity: 0;
}

.usnsepd-y {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.525 10.154c.31-.222 1.082-.613 1.996-.46");
}

.uu8x24bjn {
  stop-color: var(--svg-color--e5562d, #E5562D);
}

.v_-r5lbgt {
  stop-color: var(--svg-color--ff5016, #FF5016);
  stop-opacity: 0;
}

.v6h3qtb9x {
  stop-color: var(--svg-color--62504d, #62504D);
  stop-opacity: 0;
}

.v8z2i9i0d {
  fill: var(--svg-color--280017, #280017);
  d: path("M17.643 17.827a2.47 2.47 0 0 0-2.06-1.12c-.862 0-1.618.45-2.059 1.12c-.096.144.038.316.192.297h3.726c.153.038.296-.144.2-.297");
}

.vglza9plq {
  stop-color: var(--svg-color--4e3a37, #4E3A37);
  stop-opacity: 0;
}

.vuo1an55t {
  fill: var(--svg-color--412a2a, #412A2A);
  d: path("M9.771 17.033a4.72 4.72 0 0 0 4.686 4.107h2.276a4.72 4.72 0 0 0 4.686-4.107c.142-2.272.288-5.063.394-7.334a1.75 1.75 0 0 0-1.663-1.727h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.137 4.98.284 7.23");
}

.vzyrucblm {
  stop-color: var(--svg-color--9f3b09, #9F3B09);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w3o5239uo {
  stop-color: var(--svg-color--341f24, #341F24);
}

.w45c8mg_n {
  d: path("M25.583 30.383v-.39c0-5.4-4.47-9.787-9.99-9.787c-5.52.01-9.99 4.387-9.99 9.786v.39z");
}

.w61k36btm {
  stop-color: var(--svg-color--3b2536, #3B2536);
}

.wkradz6bg {
  stop-color: var(--svg-color--4d3236, #4D3236);
}

.wy7qqvbub {
  d: path("M17.177 22.936a1 1 0 0 1 .723-1.221l5.303-1.34a1 1 0 0 1 1.213.719l2.414 9.289h-7.719z");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.y40rkpbmj {
  stop-color: var(--svg-color--4d4241, #4D4241);
}

.yiugnhb3z {
  d: path("M9.771 17.033a4.72 4.72 0 0 0 4.686 4.107h2.276a4.72 4.72 0 0 0 4.686-4.107c.142-2.272.288-5.063.394-7.334a1.75 1.75 0 0 0-1.663-1.727h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.504h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.137 4.98.284 7.23");
}

.yr1b81w8m {
  stop-color: var(--svg-color--381d1b, #381D1B);
}

.yzag7e8_g {
  stop-color: var(--svg-color--ff764c, #FF764C);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.ztdylzwtd {
  stroke: var(--svg-color--655553, #655553);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.22 10.535l1.03 2.871");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
