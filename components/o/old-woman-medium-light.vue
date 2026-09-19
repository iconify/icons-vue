<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i132g4d)" class="x9mlfx_2j"/><g filter="url(#iTKE9Pd)"><path class="ivnmnzefq"/><path fill="url(#iFWiuJb)" class="x322lk_kp"/></g><path fill="url(#iTyTRXd)" class="i8y3-tbld"/><path fill="url(#id4DIxe)" class="i8y3-tbld"/><g filter="url(#iFCWofr)"><path fill="url(#iHmbTId)" class="lgrkq2c6e"/></g><g filter="url(#ihvfSko)"><path class="l4_f42b4s"/><path fill="url(#iOzYaxe)" class="uk2ytdbak"/></g><g filter="url(#iTgD1Zl)"><path fill="url(#ifQIgfd)" class="luw25xboi"/><path fill="url(#iJqEuDN)" class="luw25xboi"/></g><g filter="url(#i7mdOIb)"><path class="c5dj4fblc"/><path fill="url(#iVHXLco)" class="ab-jnnpfq"/></g><g filter="url(#ijt0LOb)"><path fill="url(#iiGdwne)" class="nxl-dbcjo"/><path fill="url(#iAqf80d)" class="nxl-dbcjo"/><path fill="url(#i7sgbJe)" class="nxl-dbcjo"/><path fill="url(#iBXScoy)" class="nxl-dbcjo"/><path fill="url(#iNG4dXh)" class="nxl-dbcjo"/><path fill="url(#ig4OHbb)" class="nxl-dbcjo"/></g><path fill="url(#iPGNe5d)" class="nxl-dbcjo"/><path fill="url(#iq86Tne)" class="nxl-dbcjo"/><path fill="url(#i2FRc4S)" class="nxl-dbcjo"/><path fill="url(#i4XjXLq)" class="nxl-dbcjo"/><g filter="url(#idYwfDB)"><path class="xqcaxb1pm"/></g><g filter="url(#ia2uzze)"><path class="e1l8dxpgh"/><path fill="url(#iek3u1b)" class="r2yk5gw0f"/><path fill="url(#i4UaZKe)" class="r2yk5gw0f"/><path fill="url(#ilFMzvb)" class="r2yk5gw0f"/></g><path fill="url(#ijT8rUd)" class="r2yk5gw0f"/><path fill="url(#i5YAlme)" class="r2yk5gw0f"/><path stroke="url(#iljMbmd)" class="wg2tsowyr"/><g filter="url(#iFcBeVd)"><path class="fxyfb0blf"/></g><g filter="url(#ivx8AIb)"><path class="rlzr4770z"/></g><g filter="url(#iiteOXd)"><path class="ep72r4b_h"/></g><g filter="url(#iwD5Moc)"><path class="bnx-9gb_w"/></g><path class="pq1e7sbto"/><path fill="url(#isXcECb)" class="yiw98ibiy"/><path class="sslzjdb6p"/><g filter="url(#iFQnZoe)"><path fill="url(#ilAj8th)" class="e_uz5pbaw"/></g><g filter="url(#iq2MF0b)"><ellipse transform="rotate(-27.914 11.432 17.826)" class="jc1ppccfd"/><ellipse fill="url(#i0qi8yc)" transform="rotate(-27.914 11.432 17.826)" class="d3y0s-bts"/></g><path class="fzf99ttvf"/><path fill="url(#iWkdF9a)" class="jkxrl8b_z"/><path class="k2fqxwbrs"/><g filter="url(#i3zGGJd)"><path class="luj6enz-m"/><path fill="url(#iS2vvCc)" class="e2se8v1zp"/></g><g filter="url(#iH2HJZd)"><path fill="url(#i7qHxub)" class="zxgv1qbii"/></g><g filter="url(#i84SIEb)"><path stroke="url(#iSU1Wre)" class="zk3f21p4e"/></g><g filter="url(#iqtIC2b)"><path stroke="url(#iGnQfkU)" class="wxs_4pb2h"/></g><g filter="url(#itdxW5b)"><path fill="url(#iYzNiVb)" class="krsahyb0g"/></g><g filter="url(#iAiASFt)"><path fill="url(#iyIWVxb)" class="kha3bxb8d"/></g><path clip-rule="evenodd" class="ze81vzbah"/><path clip-rule="evenodd" class="fivaadb9w"/><defs><radialGradient id="i132g4d" cx="0" cy="0" r="1" gradientTransform="rotate(159.45 8.866 4.203)scale(8.16232 6.90297)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="jpk3lwb9k"/><stop offset=".879" class="mzsejxbhe"/></radialGradient><radialGradient id="iFWiuJb" cx="0" cy="0" r="1" gradientTransform="matrix(7.70897 -9.00929 11.38856 9.74484 6.164 15.347)" gradientUnits="userSpaceOnUse"><stop class="jwo0h5dbt"/><stop offset="1" class="igxv_jb3j"/></radialGradient><radialGradient id="iTyTRXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73002 0 0 -3.69719 8.345 14.27)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="lxwev9kth"/><stop offset="1" class="dbmm3wbls"/></radialGradient><radialGradient id="id4DIxe" cx="0" cy="0" r="1" gradientTransform="rotate(-109.573 9.054 .716)scale(1.93641 .96821)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="edx7bubmp"/><stop offset="1" class="m2s_72ssr"/></radialGradient><radialGradient id="iOzYaxe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25405 0 0 -2.15614 7.308 19.1)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="ifQIgfd" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 57.517 -44.426)scale(5.09754 6.22385)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iJqEuDN" cx="0" cy="0" r="1" gradientTransform="rotate(15.945 -43.249 98.68)scale(1.93378 1.01666)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iVHXLco" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 66.88 -58.937)scale(2.41654)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iiGdwne" cx="0" cy="0" r="1" gradientTransform="matrix(-9.83758 10.56244 -10.33625 -9.62691 22.462 17.188)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="rpzlw5bfj"/><stop offset="1" class="fzvd1vbkr"/></radialGradient><radialGradient id="iAqf80d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1875 3.14012 0 20.4 17.281)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="keh2dibey"/><stop offset="1" class="oyxsw1vjr"/></radialGradient><radialGradient id="i7sgbJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 2.75 0 11.994 17.281)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y7ojx4qfz"/><stop offset="1" class="uq4apca-d"/></radialGradient><radialGradient id="iBXScoy" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.46875 -2.69492 0 11.588 18.656)" gradientUnits="userSpaceOnUse"><stop offset=".291" class="jpjncjiaz"/><stop offset="1" class="v95xvybxy"/></radialGradient><radialGradient id="iNG4dXh" cx="0" cy="0" r="1" gradientTransform="matrix(-2.72442 5.81787 -4.91398 -2.30114 19.9 12.278)" gradientUnits="userSpaceOnUse"><stop class="zuywj_bfz"/><stop offset="1" class="s4ntudbyn"/></radialGradient><radialGradient id="ig4OHbb" cx="0" cy="0" r="1" gradientTransform="rotate(-13.335 95.637 -61.69)scale(1.96872 2.43365)" gradientUnits="userSpaceOnUse"><stop class="l5yho0zlp"/><stop offset="1" class="gqn3elbhv"/></radialGradient><radialGradient id="iPGNe5d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.99991 13.56256 -19.47614 -5.74396 17.275 16.75)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="pj__wrb2a"/><stop offset="1" class="hiw8w_whp"/></radialGradient><radialGradient id="iq86Tne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47497 10.6875 -2.35379 -.32484 25.5 19.75)" gradientUnits="userSpaceOnUse"><stop class="chlegabck"/><stop offset="1" class="uabx3jpcs"/></radialGradient><radialGradient id="i2FRc4S" cx="0" cy="0" r="1" gradientTransform="matrix(1.06875 2.59374 -3.06547 1.26312 10.525 7.937)" gradientUnits="userSpaceOnUse"><stop class="ezfx0bb5f"/><stop offset="1" class="xwnzn9b7x"/></radialGradient><radialGradient id="i4XjXLq" cx="0" cy="0" r="1" gradientTransform="matrix(4.8125 -4.4375 2.99107 3.24384 6.5 9.938)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="yexuwtdlp"/><stop offset="1" class="wxorzojah"/></radialGradient><radialGradient id="iek3u1b" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 16.947 4.29)scale(4.74883 2.71734)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i5YAlme" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 4.887 13.198)scale(2.93624 3.93288)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="isXcECb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.938 18.005)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i0qi8yc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.766 3.593)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWkdF9a" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 19.968 18.06)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iS2vvCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.543 18.216)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iTKE9Pd" width="22.676" height="13.787" x="4.837" y="4.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.45098 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19563"/></filter><filter id="iFCWofr" width="6.15" height="6.25" x="4.308" y="16.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19563"/></filter><filter id="ihvfSko" width="4.779" height="4.779" x="4.918" y="16.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".2"/></filter><filter id="iTgD1Zl" width="6" height="6.25" x="22.008" y="15.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19563"/></filter><filter id="i7mdOIb" width="4.979" height="4.979" x="22.543" y="16.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".25"/></filter><filter id="ijt0LOb" width="20" height="21.833" x="6.5" y="8.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.631373 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19563"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.427451 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19563" result="effect2_innerShadow_3987_19563"/></filter><filter id="idYwfDB" width="4.5" height="6" x="13.438" y="17.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".25"/></filter><filter id="ia2uzze" width="4" height="5.5" x="14" y="17.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".125"/></filter><filter id="iFcBeVd" width="4.35" height="1.811" x="18.9" y="13.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19563"/></filter><filter id="ivx8AIb" width="4.35" height="1.811" x="8.9" y="13.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19563"/></filter><filter id="iiteOXd" width="5.419" height="2.462" x="8.604" y="16.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19563"/></filter><filter id="iwD5Moc" width="5.419" height="2.462" x="18.104" y="16.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19563"/></filter><filter id="iFQnZoe" width="1.493" height="1.594" x="12.162" y="17.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".1"/></filter><filter id="iq2MF0b" width="1.529" height="1.141" x="10.668" y="17.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".05"/></filter><filter id="i3zGGJd" width="1.294" height="1.125" x="18.686" y="17.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".05"/></filter><filter id="iH2HJZd" width="1.316" height="1.357" x="20.338" y="17.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".1"/></filter><filter id="i84SIEb" width="3.891" height="1.401" x="9.088" y="14.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".125"/></filter><filter id="iqtIC2b" width="3.891" height="1.401" x="19.219" y="14.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".125"/></filter><filter id="itdxW5b" width="17.593" height="9.464" x="9.558" y="4.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".625"/></filter><filter id="iAiASFt" width="6.633" height="6.958" x="5.287" y="5.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19563" stdDeviation=".625"/></filter><linearGradient id="iHmbTId" x1="4.308" x2="9.825" y1="19.262" y2="19.262" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="i4UaZKe" x1="14.049" x2="15.642" y1="21.796" y2="21.991" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="ilFMzvb" x1="16" x2="16" y1="23.389" y2="22.252" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ijT8rUd" x1="16.146" x2="16.146" y1="23.341" y2="23.081" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="iljMbmd" x1="14.675" x2="15.469" y1="25.849" y2="24.286" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="ilAj8th" x1="13.325" x2="12.74" y1="18.105" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7qHxub" x1="21.418" x2="20.834" y1="18.16" y2="18.52" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSU1Wre" x1="9.74" x2="12.771" y1="15.401" y2="14.505" gradientUnits="userSpaceOnUse"><stop class="wgmwydz1w"/><stop offset="1" class="jxtrqmq9q"/></linearGradient><linearGradient id="iGnQfkU" x1="18.236" x2="22.439" y1="14.341" y2="14.982" gradientUnits="userSpaceOnUse"><stop class="wgmwydz1w"/><stop offset="1" class="jxtrqmq9q"/></linearGradient><linearGradient id="iYzNiVb" x1="22.557" x2="12.479" y1="9.495" y2="4.991" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient><linearGradient id="iyIWVxb" x1="10.32" x2="10.044" y1="7.452" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-woman-medium-light" /></template>
<style>
.ab-jnnpfq {
  d: path("M27.022 19.1a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bnx-9gb_w {
  fill: var(--svg-color--36292e, #36292E);
  d: path("M18.104 18.226c.494-.87.987-1.593 2.606-1.593c.969-.067 1.652.232 2.26.723c.501.405.42.835.06 1.148l-.793.582c-1.215-.393-2.817-.467-4.133-.86");
}

.c5dj4fblc {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M27.022 19.1a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.chlegabck {
  stop-color: var(--svg-color--f4c09b, #F4C09B);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d3y0s-bts {
  cx: 11.432px;
  cy: 17.826px;
  rx: 0.726px;
  ry: 0.368px;
}

.dbmm3wbls {
  stop-color: var(--svg-color--6f524d, #6F524D);
  stop-opacity: 0;
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.e_uz5pbaw {
  d: path("M13.455 18.584c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1l8dxpgh {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.287 18.744l-.99 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.e2se8v1zp {
  d: path("M19.85 17.522c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.edx7bubmp {
  stop-color: var(--svg-color--776169, #776169);
}

.ep72r4b_h {
  fill: var(--svg-color--36292e, #36292E);
  d: path("M13.823 18.226c-.495-.87-.987-1.593-2.607-1.593c-.968-.067-1.652.232-2.26.723c-.5.405-.42.835-.06 1.148l.793.582c1.215-.393 2.817-.467 4.134-.86");
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eu_5adeum {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
  stop-opacity: 0;
}

.ezfx0bb5f {
  stop-color: var(--svg-color--87513f, #87513F);
}

.fivaadb9w {
  fill: var(--svg-color--c68d7d, #C68D7D);
  fill-rule: evenodd;
  d: path("M13.48 20.086a.45.45 0 0 0-.636.031c-.196.217-.842.684-1.672.657a.45.45 0 1 0-.03.9c1.159.037 2.043-.593 2.369-.952a.45.45 0 0 0-.031-.636");
}

.ft_qk78lm {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
}

.ft5dv1b6b {
  fill: none;
}

.fxyfb0blf {
  fill: var(--svg-color--7e7c7f, #7E7C7F);
  d: path("m22.857 14.789l-.002-.002l-.005-.003l-.018-.01l-.06-.034a6 6 0 0 0-.98-.411c-.635-.202-1.521-.372-2.478-.203a.5.5 0 0 0 .174.984c.743-.13 1.457-.001 1.999.172a5 5 0 0 1 .849.36l.008.005a.5.5 0 0 0 .514-.858");
}

.fzf99ttvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.358 16.663c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.557-2.103");
}

.fzvd1vbkr {
  stop-color: var(--svg-color--c4907a, #C4907A);
}

.gqn3elbhv {
  stop-color: var(--svg-color--fec6a3, #FEC6A3);
  stop-opacity: 0;
}

.hiw8w_whp {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
}

.i8y3-tbld {
  d: path("M26.69 12.983C25.976 8.533 23.63 4.97 16 4.97c-7.635 0-10.201 3.569-11.064 8.024c-.377 1.95.345 3.736 1.66 5.014l-.058-2.576l-.019-.495l-.019-.57c.038-1.77 1.07-2.454 1.51-2.683q.046-.016.096-.038t.096-.038a4.3 4.3 0 0 0 2.217-2.302l.153-.361a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.483l-.1 3.046c1.027-1.223 1.566-2.804 1.29-4.515");
}

.igxv_jb3j {
  stop-color: var(--svg-color--82747b, #82747B);
  stop-opacity: 0;
}

.ivnmnzefq {
  fill: var(--svg-color--a5a5a5, #A5A5A5);
  d: path("M26.69 12.983C25.976 8.533 23.63 4.97 16 4.97c-7.635 0-10.201 3.569-11.064 8.024c-.377 1.95.345 3.736 1.66 5.014L6.5 14.365c.038-1.769 1.07-2.453 1.51-2.682q.046-.016.096-.038t.096-.038a4.3 4.3 0 0 0 2.217-2.302l.153-.361a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.483l-.1 3.046c1.027-1.223 1.566-2.804 1.29-4.515");
}

.jc1ppccfd {
  cx: 11.432px;
  cy: 17.826px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.jkxrl8b_z {
  d: path("M19.972 17.17a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.67-1.664");
}

.jpjncjiaz {
  stop-color: var(--svg-color--d5a182, #D5A182);
}

.jpk3lwb9k {
  stop-color: var(--svg-color--c3c3c3, #C3C3C3);
}

.jwo0h5dbt {
  stop-color: var(--svg-color--82747b, #82747B);
}

.jxtrqmq9q {
  stop-color: var(--svg-color--a3a2a4, #A3A2A4);
}

.k2fqxwbrs {
  fill: var(--svg-color--000, #000);
  d: path("M19.019 18.834c0-.53.423-.953.953-.953s.953.423.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.44");
}

.keh2dibey {
  stop-color: var(--svg-color--e2a18d, #E2A18D);
}

.kha3bxb8d {
  d: path("M10.67 7.03c-.116 1.076-.929 3.994-4.133 4.458c.03-1.176 1.045-4.156 4.133-4.458");
}

.krsahyb0g {
  d: path("M17.634 11.167c-4.272 0-6.27-3.127-6.826-4.55c0-.512 2.554-1.417 6.826-1.162c6.23.373 8.111 4.613 8.266 6.92c-.371-1.078-1.393-1.13-1.857-1.208z");
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.l4_f42b4s {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M9.297 19.1a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.l5yho0zlp {
  stop-color: var(--svg-color--fec6a3, #FEC6A3);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lgrkq2c6e {
  d: path("M10.308 19.1a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.luj6enz-m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.85 17.522c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.luw25xboi {
  d: path("M28.008 19a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lxwev9kth {
  stop-color: var(--svg-color--6f524d, #6F524D);
}

.m2s_72ssr {
  stop-color: var(--svg-color--776169, #776169);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mzsejxbhe {
  stop-color: var(--svg-color--868381, #868381);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nxl-dbcjo {
  d: path("M6.5 14.366c.038-1.77 1.07-2.454 1.51-2.682a1 1 0 0 0 .096-.039q.051-.022.096-.038a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.222 6.783c-.23 5.225-4.31 8.734-9.29 8.734c-4.981 0-9.061-3.509-9.291-8.734z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oyxsw1vjr {
  stop-color: var(--svg-color--e2a18d, #E2A18D);
  stop-opacity: 0;
}

.pj__wrb2a {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq1e7sbto {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.549 16.609c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2yk5gw0f {
  d: path("m15.287 18.744l-.99 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.rlzr4770z {
  fill: var(--svg-color--7e7c7f, #7E7C7F);
  d: path("m9.666 15.642l-.009.005a.5.5 0 0 1-.514-.858h.001l.002-.002l.006-.003l.017-.01a3 3 0 0 1 .277-.143c.184-.088.445-.2.765-.302c.633-.202 1.52-.372 2.476-.203a.5.5 0 0 1-.174.984c-.743-.13-1.457-.001-1.998.172a5 5 0 0 0-.85.36");
}

.rpzlw5bfj {
  stop-color: var(--svg-color--fcc4a0, #FCC4A0);
}

.s4ntudbyn {
  stop-color: var(--svg-color--daa995, #DAA995);
  stop-opacity: 0;
}

.sslzjdb6p {
  fill: var(--svg-color--000, #000);
  d: path("M12.888 18.78a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .159.037.31.106.439h1.686a.94.94 0 0 0 .114-.439");
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.uabx3jpcs {
  stop-color: var(--svg-color--f4c09b, #F4C09B);
  stop-opacity: 0;
}

.uk2ytdbak {
  d: path("M9.297 19.1a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.uq4apca-d {
  stop-color: var(--svg-color--c2837b, #C2837B);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.v95xvybxy {
  stop-color: var(--svg-color--d5a182, #D5A182);
  stop-opacity: 0;
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.wg2tsowyr {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.44 23.957a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393A3.58 3.58 0 0 0 16 26.018a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607a5.54 5.54 0 0 1-2.56-.607Z");
}

.wgmwydz1w {
  stop-color: var(--svg-color--a3a2a4, #A3A2A4);
  stop-opacity: 0;
}

.wxorzojah {
  stop-color: var(--svg-color--9a6250, #9A6250);
  stop-opacity: 0;
}

.wxs_4pb2h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.734 15.107c-.344-.245-1.553-.775-3.14-.625");
}

.x322lk_kp {
  d: path("M26.69 12.983C25.976 8.533 23.63 4.97 16 4.97c-7.635 0-10.201 3.569-11.064 8.024c-.377 1.95.345 3.736 1.66 5.014L6.5 14.365c.038-1.769 1.07-2.453 1.51-2.682q.046-.016.096-.038t.096-.038a4.3 4.3 0 0 0 2.217-2.302l.153-.361a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.483l-.1 3.046c1.027-1.223 1.566-2.804 1.29-4.515");
}

.x9mlfx_2j {
  d: path("M21 7.063a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xqcaxb1pm {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.25 18.975l-1.266 3.17a1.005 1.005 0 0 0 .97 1.303h1.467c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.701-.929-.701-1.151 0");
}

.xwnzn9b7x {
  stop-color: var(--svg-color--87513f, #87513F);
  stop-opacity: 0;
}

.y7ojx4qfz {
  stop-color: var(--svg-color--c2837b, #C2837B);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yexuwtdlp {
  stop-color: var(--svg-color--9a6250, #9A6250);
}

.yiw98ibiy {
  d: path("M11.935 17.115a1.664 1.664 0 0 0-1.604 2.103h3.215c.037-.144.06-.288.06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.ze81vzbah {
  fill: var(--svg-color--e4a790, #E4A790);
  fill-rule: evenodd;
  d: path("M18.602 20.086a.45.45 0 0 1 .636.031c.196.217.841.684 1.672.657a.45.45 0 1 1 .03.9c-1.16.037-2.043-.593-2.37-.952a.45.45 0 0 1 .032-.636");
}

.zk3f21p4e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.463 15.156c.343-.245 1.553-.775 3.14-.625");
}

.zuywj_bfz {
  stop-color: var(--svg-color--daa995, #DAA995);
}

.zxgv1qbii {
  d: path("M21.454 18.615a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

</style>
