<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivx7Icf)" class="rmv5f6ekt"/><path fill="url(#iw70gsb)" class="rmv5f6ekt"/><path fill="url(#iHLn7qb)" class="rmv5f6ekt"/><path fill="url(#iIgCXNe)" class="rmv5f6ekt"/><path fill="url(#iT2cmYb)" class="rmv5f6ekt"/><rect fill="url(#iRWnjKd)" class="qm8bcbjeu"/><g filter="url(#iD2rced)"><circle fill="url(#ifPhUfb)" class="k8b9xebdz"/></g><g filter="url(#ixhwHsc)"><circle fill="url(#iwJVGKe)" class="du4sk2x2d"/></g><g filter="url(#i60oiUb)"><circle fill="url(#iUBZYcG)" class="kubvk0but"/><circle fill="url(#icrqUAb)" class="kubvk0but"/></g><g filter="url(#ircBwQe)"><circle class="c7pvfwdsd"/><circle fill="url(#iAF0Asc)" class="p68b48bqt"/><circle fill="url(#iPjrTzb)" class="p68b48bqt"/></g><g filter="url(#i04NJpc)"><path fill="url(#ivd9Fbd)" class="bg35arzyv"/><path fill="url(#ibO5Exe)" class="bg35arzyv"/><path fill="url(#iybXNvb)" class="bg35arzyv"/><path fill="url(#idRJoHc)" class="bg35arzyv"/><path fill="url(#iIGCusb)" class="bg35arzyv"/></g><g filter="url(#if46Hvc)"><path fill="url(#ipp2zlB)" class="eygiiccrn"/></g><g filter="url(#iofP69d)"><path class="f10-33b6c"/><path fill="url(#iwvd9Xd)" class="mlchpo15m"/><path fill="url(#ioahRAc)" class="mlchpo15m"/><path fill="url(#iVZVv1c)" class="mlchpo15m"/><path fill="url(#iJNoGUb)" class="mlchpo15m"/></g><g filter="url(#igW1kwb)"><path class="q0azxmbhq"/></g><g filter="url(#ixmNSVh)"><path class="sf2toj3nr"/><path fill="url(#iG6sr7b)" class="oc-zgqeem"/><path fill="url(#iGV7I8b)" class="oc-zgqeem"/><path fill="url(#iCkpj7d)" class="oc-zgqeem"/><path fill="url(#iORn6Tb)" class="oc-zgqeem"/></g><path fill="url(#iV3TbPc)" class="oc-zgqeem"/><path class="x4ukk4g1w"/><path fill="url(#iJxurWc)" class="n-x-eqble"/><path class="z919ptbwd"/><g filter="url(#i10Yusb)"><path class="jcr2ccl3a"/><path fill="url(#iRdX8Ae)" class="db90eobmg"/></g><g filter="url(#iGm4wce)"><path fill="url(#iEItQpe)" class="hy-9rp8wv"/></g><path class="i8fix6b7o"/><path fill="url(#iKuW4ae)" class="luxs16bmf"/><path class="hz4gvyb5d"/><g filter="url(#idhG9Hb)"><path fill="url(#iXVCllb)" class="d4f8ve26n"/></g><g filter="url(#iEqxwzv)"><ellipse transform="rotate(-27.914 12.856 12.299)" class="ch72wlb0u"/><ellipse fill="url(#ifzTQyb)" transform="rotate(-27.914 12.856 12.299)" class="t2k0q_b0y"/></g><g filter="url(#iBFHTbb)"><path stroke="url(#itEmh8d)" class="u8monjbum"/></g><g filter="url(#i8QltxS)"><path clip-rule="evenodd" class="k1hreqbcg"/></g><g filter="url(#iCxZ6Ol)"><path clip-rule="evenodd" class="qk03576nt"/></g><g filter="url(#i6zRaib)"><path stroke="url(#iCB6jue)" class="ri6y867pw"/></g><g filter="url(#iq0UlQd)"><path stroke="url(#iUIiAOc)" class="ch3bstb0u"/></g><g filter="url(#iJU7RDb)"><path stroke="url(#iHoKZqk)" clip-rule="evenodd" class="w348_pd9z"/><path stroke="url(#i2JZy6c)" clip-rule="evenodd" class="w348_pd9z"/></g><path clip-rule="evenodd" class="jcalhtb6q"/><defs><radialGradient id="ivx7Icf" cx="0" cy="0" r="1" gradientTransform="rotate(160.481 9.331 14.06)scale(12.5328 12.8728)" gradientUnits="userSpaceOnUse"><stop class="v-2sss5_q"/><stop offset=".578" class="rl_l27czx"/></radialGradient><radialGradient id="iw70gsb" cx="0" cy="0" r="1" gradientTransform="matrix(-20.8125 0 0 -13.0625 25.199 29.069)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zx529yrpf"/><stop offset="1" class="vith88blc"/></radialGradient><radialGradient id="iIgCXNe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25498 0 0 -2.00346 15.703 21.083)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="kwfxid2mc"/><stop offset="1" class="axqjsnbkb"/></radialGradient><radialGradient id="iT2cmYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.77741 5.6184 0 12.446 30.118)" gradientUnits="userSpaceOnUse"><stop class="ylk4vpbqv"/><stop offset="1" class="cac2is6pz"/></radialGradient><radialGradient id="iRWnjKd" cx="0" cy="0" r="1" gradientTransform="rotate(45 -17.432 28.787)scale(4.26636 6.72801)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="yzrng7b6j"/><stop offset=".963" class="j8zxh6bbq"/></radialGradient><radialGradient id="ifPhUfb" cx="0" cy="0" r="1" gradientTransform="matrix(2.26599 0 0 3.9655 7.74 13.303)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="icrqUAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0675 -.77729 .88717 1.2184 22.66 12.961)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iAF0Asc" cx="0" cy="0" r="1" gradientTransform="matrix(1.06047 -1.9505 1.14163 .6207 22.126 14.364)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iPjrTzb" cx="0" cy="0" r="1" gradientTransform="matrix(.33481 .33141 -.42723 .43162 22.18 13.303)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="ibO5Exe" cx="0" cy="0" r="1" gradientTransform="matrix(-.55053 10.67511 -14.49094 -.74732 16.063 10.897)" gradientUnits="userSpaceOnUse"><stop offset=".703" class="jbdjvjesn"/><stop offset="1" class="z0cx0-b2p"/></radialGradient><radialGradient id="idRJoHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.68778 2.07727 0 19.055 11.661)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iIGCusb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.79597 2.23345 0 13.17 11.618)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iwvd9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0302 -3.81777 1.41575 .38203 21.637 8)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ioahRAc" cx="0" cy="0" r="1" gradientTransform="matrix(4.93886 .4545 -.24438 2.6556 19.516 5.728)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iVZVv1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.16825 -3.35801 0 16.026 2.197)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iJNoGUb" cx="0" cy="0" r="1" gradientTransform="matrix(3.96927 -2.90878 4.5571 6.21854 7.699 11)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iORn6Tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25425 -.81684 0 16.449 15.378)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iJxurWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04738 -1.66598 0 18.84 12.423)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iRdX8Ae" cx="0" cy="0" r="1" gradientTransform="matrix(-.2994 -.38581 .53117 -.4122 18.545 12.531)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKuW4ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04744 -1.66607 0 13.206 12.422)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ifzTQyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00999 -.63784 .76672 -.012 12.836 12.706)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHoKZqk" cx="0" cy="0" r="1" gradientTransform="matrix(-.08594 .28125 -1.54727 -.47278 16.34 17.371)" gradientUnits="userSpaceOnUse"><stop class="nasdam3mi"/><stop offset="1" class="dx0mdfj-h"/></radialGradient><radialGradient id="i2JZy6c" cx="0" cy="0" r="1" gradientTransform="matrix(.191 -.14453 .57285 .75707 14.407 17.688)" gradientUnits="userSpaceOnUse"><stop class="nasdam3mi"/><stop offset="1" class="dx0mdfj-h"/></radialGradient><filter id="iD2rced" width="4.511" height="4.311" x="7.74" y="11.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21942"/></filter><filter id="ixhwHsc" width="3.57" height="3.57" x="8.111" y="11.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".25"/></filter><filter id="i60oiUb" width="4.561" height="4.561" x="20.024" y="10.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21942"/></filter><filter id="ircBwQe" width="3.57" height="3.57" x="20.395" y="11.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".25"/></filter><filter id="i04NJpc" width="13.395" height="15.781" x="9.366" y="6.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21942"/></filter><filter id="if46Hvc" width="9.483" height="7.96" x="14.246" y="4.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation="1"/></filter><filter id="iofP69d" width="16.272" height="10.886" x="7.89" y="1.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21942"/></filter><filter id="igW1kwb" width="3.773" height="4.962" x="13.831" y="12.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".375"/></filter><filter id="ixmNSVh" width="2.923" height="3.962" x="14.565" y="12.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".125"/></filter><filter id="i10Yusb" width=".958" height=".841" x="17.921" y="11.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".05"/></filter><filter id="iGm4wce" width="1.034" height="1.063" x="19.034" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".1"/></filter><filter id="idhG9Hb" width="1.157" height="1.227" x="13.299" y="11.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".1"/></filter><filter id="iEqxwzv" width="1.121" height=".851" x="12.295" y="11.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".05"/></filter><filter id="iBFHTbb" width="1.083" height="2.712" x="9.465" y="6.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".125"/></filter><filter id="i8QltxS" width="3.582" height="2.502" x="11.003" y="8.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21942"/></filter><filter id="iCxZ6Ol" width="3.582" height="2.502" x="17.792" y="8.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21942"/></filter><filter id="i6zRaib" width="2.982" height="1.752" x="11.178" y="9.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".15"/></filter><filter id="iq0UlQd" width="2.982" height="1.752" x="18.048" y="9.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".15"/></filter><filter id="iJU7RDb" width="3.695" height="1.445" x="14.157" y="16.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21942" stdDeviation=".05"/></filter><linearGradient id="iHLn7qb" x1="16" x2="16" y1="29.889" y2="29.303" gradientUnits="userSpaceOnUse"><stop class="mbdrodj7c"/><stop offset="1" class="twkbxyfkj"/></linearGradient><linearGradient id="iwJVGKe" x1="9.895" x2="9.068" y1="13.663" y2="13.663" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iUBZYcG" x1="23.582" x2="22.525" y1="11.894" y2="15.169" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="ivd9Fbd" x1="21.238" x2="11.376" y1="13.806" y2="15.276" gradientUnits="userSpaceOnUse"><stop class="ydq0kpc8x"/><stop offset="1" class="e-sxlzbkb"/></linearGradient><linearGradient id="iybXNvb" x1="9.059" x2="11.488" y1="17.287" y2="17.201" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="ipp2zlB" x1="15.34" x2="25.856" y1="9.952" y2="6.187" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iG6sr7b" x1="14.91" x2="16.122" y1="14.657" y2="14.657" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iGV7I8b" x1="17.238" x2="15.914" y1="15.074" y2="15.055" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iCkpj7d" x1="16.277" x2="16.277" y1="16.032" y2="15.292" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iV3TbPc" x1="16.189" x2="16.189" y1="16.086" y2="15.87" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="iEItQpe" x1="19.844" x2="19.439" y1="12.492" y2="12.742" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXVCllb" x1="14.166" x2="13.761" y1="12.492" y2="12.742" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itEmh8d" x1="10.006" x2="10.006" y1="6.963" y2="9.748" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iCB6jue" x1="13.105" x2="12.066" y1="9.904" y2="8.694" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iUIiAOc" x1="19.103" x2="20.142" y1="9.818" y2="8.608" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-frowning-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.axqjsnbkb {
  stop-color: var(--svg-color--176bb1, #176BB1);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bg35arzyv {
  d: path("M9.366 10.655c0-.345.138-.758.415-.964l.208-.207c.346-.276.485-.689.485-1.102V7.28c0-.344.208-.62.554-.689c.831-.206 2.563-.55 5.056-.55c2.494 0 4.225.344 5.056.55c.277.07.555.345.555.69v1.101c0 .413.207.826.484 1.102c.649.454.608.704.554 1.24a60 60 0 0 0-.138 1.859h.023l-.343 5.111c-.207 2.285-2.004 3.878-4.145 3.878h-4.146c-2.21 0-3.938-1.593-4.145-3.878c-.18-2.345-.26-4.698-.473-7.04");
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

.c7pvfwdsd {
  cx: 22.18px;
  cy: 13.303px;
  r: 1.285px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.cac2is6pz {
  stop-color: var(--svg-color--2888f9, #2888F9);
  stop-opacity: 0;
}

.ch3bstb0u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.58 10.413a3.03 3.03 0 0 1-2.082-.852");
}

.ch72wlb0u {
  cx: 12.856px;
  cy: 12.299px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.503px;
  ry: 0.255px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d4f8ve26n {
  d: path("M14.256 12.824c0-.373-.303-.621-.385-.696l-.372.36l.229.466z");
}

.db90eobmg {
  d: path("M18.758 12.05c.082.11-.09.244-.285.39s-.34.248-.422.139c-.082-.11.01-.318.205-.463s.42-.175.502-.066");
}

.du4sk2x2d {
  cx: 9.895px;
  cy: 13.303px;
  r: 1.285px;
}

.dx0mdfj-h {
  stop-color: var(--svg-color--f5c0b0, #F5C0B0);
  stop-opacity: 0;
}

.e-sxlzbkb {
  stop-color: var(--svg-color--daa594, #DAA594);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eygiiccrn {
  d: path("M21.144 6.04L17.17 7.366a1.352 1.352 0 0 0 .607 2.623l3.951-.529z");
}

.f10-33b6c {
  fill: var(--svg-color--242324, #242324);
  d: path("m22.249 4.939l.554.275c.97.482 1.523 1.584 1.316 2.755l-.762 3.925c-.068.406-.336.679-.739.689h-.023s.07-1.17.138-1.86c.057-.559-.041-.73-.554-1.24c-.277-.275-.484-.688-.484-1.101V7.28c0-.344-.278-.62-.555-.689c-.83-.206-2.562-.55-5.056-.55c-2.493 0-4.225.344-5.056.55c-.346.07-.554.345-.554.69v1.101c0 .413-.139.826-.485 1.102l-.208.207c-.277.206-.415.62-.415.964c.069.757.138 1.86.138 1.86l-.063-.003a.82.82 0 0 1-.768-.687L7.911 7.9c-.138-1.102.416-2.204 1.385-2.686l.555-.275c.346-.207.692-.482 1.038-.758l1.247-1.308c.762-.69 1.87-.896 2.84-.414a3.8 3.8 0 0 0 2.147 0c1.04-.344 2.217-.068 3.048.69L21.21 4.18c.277.344.623.551 1.039.758");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hy-9rp8wv {
  d: path("M19.869 12.807a1.1 1.1 0 0 0-.3-.597l-.335.368l.152.295z");
}

.hz4gvyb5d {
  fill: var(--svg-color--000, #000);
  d: path("M13.863 12.959a.657.657 0 0 0-.66-.66a.657.657 0 0 0-.586.964h1.168a.66.66 0 0 0 .078-.304");
}

.i8fix6b7o {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.936 11.456c-.843 0-1.555.581-1.75 1.367a.354.354 0 0 0 .347.44h2.88c.183 0 .33-.168.293-.351a1.81 1.81 0 0 0-1.77-1.456");
}

.j8zxh6bbq {
  stop-color: var(--svg-color--f6c6b6, #F6C6B6);
}

.jbdjvjesn {
  stop-color: var(--svg-color--e3aca7, #E3ACA7);
  stop-opacity: 0;
}

.jcalhtb6q {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M17.171 17.67c-.918-.627-1.93-.26-2.34.005a.275.275 0 1 1-.298-.462c.495-.319 1.765-.806 2.949.004a.275.275 0 1 1-.31.454");
}

.jcr2ccl3a {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.758 12.05c.082.11-.09.244-.285.39s-.34.248-.422.139c-.082-.11.01-.318.205-.463s.42-.175.502-.066");
}

.k1hreqbcg {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M14.161 9.371c.239.25.23.645-.019.884a3.66 3.66 0 0 1-2.514 1.025a.625.625 0 1 1 0-1.25a2.4 2.4 0 0 0 1.65-.678a.625.625 0 0 1 .883.02");
}

.k8b9xebdz {
  cx: 9.895px;
  cy: 13.303px;
  r: 2.156px;
}

.kubvk0but {
  cx: 22.18px;
  cy: 13.303px;
  r: 2.156px;
}

.kwfxid2mc {
  stop-color: var(--svg-color--176bb1, #176BB1);
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.luxs16bmf {
  d: path("M13.203 11.807a1.152 1.152 0 0 0-1.11 1.456h2.226q.04-.149.042-.304a1.16 1.16 0 0 0-1.158-1.152");
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbdrodj7c {
  stop-color: var(--svg-color--2771fc, #2771FC);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlchpo15m {
  d: path("m22.249 4.939l.554.275c.97.482 1.523 1.584 1.316 2.755l-.762 3.925c-.068.406-.336.679-.739.689h-.023s.07-1.17.138-1.86c.057-.559-.041-.73-.554-1.24c-.277-.275-.484-.688-.484-1.101V7.28c0-.344-.278-.62-.555-.689c-.83-.206-2.562-.55-5.056-.55c-2.493 0-4.225.344-5.056.55c-.346.07-.554.345-.554.69v1.101c0 .413-.139.826-.485 1.102l-.208.207c-.277.206-.415.62-.415.964c.069.757.138 1.86.138 1.86l-.063-.003a.82.82 0 0 1-.768-.687L7.911 7.9c-.138-1.102.416-2.204 1.385-2.686l.555-.275c.346-.207.692-.482 1.038-.758l1.247-1.308c.762-.69 1.87-.896 2.84-.414a3.8 3.8 0 0 0 2.147 0c1.04-.344 2.217-.068 3.048.69L21.21 4.18c.277.344.623.551 1.039.758");
}

.n-x-eqble {
  d: path("M18.842 11.807a1.152 1.152 0 0 1 1.11 1.456h-2.225a1.157 1.157 0 0 1 1.116-1.456");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nasdam3mi {
  stop-color: var(--svg-color--f5c0b0, #F5C0B0);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.oc-zgqeem {
  d: path("m15.533 12.935l-.686 2.194a.696.696 0 0 0 .672.903h1.015a.698.698 0 0 0 .672-.903l-.686-2.194c-.147-.486-.833-.486-.987 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p68b48bqt {
  cx: 22.18px;
  cy: 13.303px;
  r: 1.285px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q0azxmbhq {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.67 13.145l-1.059 2.195c-.131.451.184.903.63.903h.953c.446 0 .761-.458.63-.903l-.644-2.195c-.137-.486-.365-.486-.51 0");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qk03576nt {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("M17.965 9.371a.625.625 0 0 0 .02.884a3.66 3.66 0 0 0 2.514 1.025a.625.625 0 1 0 0-1.25a2.4 2.4 0 0 1-1.65-.678a.625.625 0 0 0-.884.02");
}

.qm8bcbjeu {
  width: 5.188px;
  height: 6.789px;
  x: 13.451px;
  y: 17.141px;
  rx: 2.594px;
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

.ri6y867pw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.628 10.499c.656 0 1.441-.239 2.082-.852");
}

.rl_l27czx {
  stop-color: var(--svg-color--2e96ff, #2E96FF);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rmv5f6ekt {
  d: path("M16 19.631c-5.502 0-9.963 4.461-9.963 9.963v.21h19.926v-.21c0-5.502-4.46-9.963-9.963-9.963");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sf2toj3nr {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.533 12.935l-.686 2.194a.696.696 0 0 0 .672.903h1.015a.698.698 0 0 0 .672-.903l-.686-2.194c-.147-.486-.833-.486-.987 0");
}

.t2k0q_b0y {
  cx: 12.856px;
  cy: 12.299px;
  rx: 0.503px;
  ry: 0.255px;
}

.twkbxyfkj {
  stop-color: var(--svg-color--2771fc, #2771FC);
  stop-opacity: 0;
}

.u8monjbum {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.173 7.09v1.16c-.01.191-.09.62-.333.802");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.v-2sss5_q {
  stop-color: var(--svg-color--4ab3ff, #4AB3FF);
}

.vith88blc {
  stop-color: var(--svg-color--3a8fc0, #3A8FC0);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w348_pd9z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M17.171 17.67c-.918-.627-1.93-.26-2.34.005a.275.275 0 1 1-.298-.462c.495-.319 1.765-.806 2.949.004a.275.275 0 1 1-.31.454Z");
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

.x4ukk4g1w {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.11 11.456c.843 0 1.555.581 1.749 1.367a.354.354 0 0 1-.346.44h-2.88a.297.297 0 0 1-.294-.351a1.804 1.804 0 0 1 1.77-1.456");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.ydq0kpc8x {
  stop-color: var(--svg-color--ffdac0, #FFDAC0);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ylk4vpbqv {
  stop-color: var(--svg-color--2888f9, #2888F9);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.yzrng7b6j {
  stop-color: var(--svg-color--bc8384, #BC8384);
}

.z0cx0-b2p {
  stop-color: var(--svg-color--b57995, #B57995);
}

.z919ptbwd {
  fill: var(--svg-color--000, #000);
  d: path("M18.183 12.959c0-.367.293-.66.66-.66a.657.657 0 0 1 .586.964H18.26a.6.6 0 0 1-.078-.304");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zx529yrpf {
  stop-color: var(--svg-color--3a8fc0, #3A8FC0);
  stop-opacity: 0;
}

</style>
