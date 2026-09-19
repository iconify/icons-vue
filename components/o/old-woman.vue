<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i132g4d)" class="x9mlfx_2j"/><g filter="url(#imwKtZd)"><path class="i7vi0rq6c"/><path fill="url(#iFWiuJb)" class="t4pkfp8jr"/></g><path fill="url(#iTyTRXd)" class="rgy2i2b6g"/><path fill="url(#id4DIxe)" class="rgy2i2b6g"/><g filter="url(#iVljgAb)"><path fill="url(#iNDqvYL)" class="lgrkq2c6e"/></g><g filter="url(#i5T35pd)"><path class="enp4o1bhv"/><path fill="url(#iyRl8Wc)" class="uk2ytdbak"/></g><g filter="url(#iO9ZqKd)"><path fill="url(#inFETAf)" class="luw25xboi"/></g><g filter="url(#iADoZlc)"><path class="utw_k16bp"/><path fill="url(#i1SkC7d)" class="ab-jnnpfq"/></g><g filter="url(#iSL2WFO)"><path fill="url(#i9cGwTd)" class="nxl-dbcjo"/><path fill="url(#ipvqnGc)" class="nxl-dbcjo"/><path fill="url(#ihU0plb)" class="nxl-dbcjo"/><path fill="url(#iKznbjd)" class="nxl-dbcjo"/></g><path fill="url(#iK0myTb)" class="nxl-dbcjo"/><path fill="url(#iqZwpac)" class="nxl-dbcjo"/><path fill="url(#idg5kke)" class="nxl-dbcjo"/><path fill="url(#ia0Vj7R)" class="nxl-dbcjo"/><g filter="url(#id1CTGk)"><path class="elhu_bfua"/></g><g filter="url(#i6JWWCb)"><path fill="url(#igPIitb)" class="r2yk5gw0f"/><path fill="url(#irr0Tbb)" class="r2yk5gw0f"/><path fill="url(#i5jbR2e)" class="r2yk5gw0f"/><path fill="url(#iRlEodb)" class="r2yk5gw0f"/></g><path fill="url(#idX4lOd)" class="r2yk5gw0f"/><path fill="url(#iN47tjb)" class="r2yk5gw0f"/><path stroke="url(#ib1JKxM)" class="rtngogk3c"/><g filter="url(#iF7kO9T)"><path class="kyklyjb9e"/></g><g filter="url(#iHiPBHy)"><path class="lr4e-z88g"/></g><g filter="url(#i6YnvRc)"><path class="ep72r4b_h"/></g><g filter="url(#iloatxz)"><path class="bnx-9gb_w"/></g><path class="pq1e7sbto"/><path fill="url(#iIY7JDd)" class="yiw98ibiy"/><path class="wwps083zl"/><g filter="url(#iGYvW1d)"><path fill="url(#ilAj8th)" class="e_uz5pbaw"/></g><g filter="url(#iwp0kje)"><ellipse transform="rotate(-27.914 11.432 17.826)" class="jc1ppccfd"/><ellipse fill="url(#i0qi8yc)" transform="rotate(-27.914 11.432 17.826)" class="d3y0s-bts"/></g><path class="fzf99ttvf"/><path fill="url(#iy5Ef4d)" class="xmkzofbmz"/><path class="wqp_7gbss"/><g filter="url(#iRkTeNe)"><path class="luj6enz-m"/><path fill="url(#iS2vvCc)" class="e2se8v1zp"/></g><g filter="url(#ivPkeLb)"><path fill="url(#i7qHxub)" class="zxgv1qbii"/></g><g filter="url(#icHY9Er)"><path stroke="url(#izrafxc)" class="zk3f21p4e"/></g><g filter="url(#i2wzpje)"><path stroke="url(#iYtthJc)" class="w-20hqkmf"/></g><g filter="url(#iT69plc)"><path fill="url(#iYzNiVb)" class="krsahyb0g"/></g><g filter="url(#iMQvrfd)"><path fill="url(#iyIWVxb)" class="kha3bxb8d"/></g><path clip-rule="evenodd" class="mral5vd-y"/><path clip-rule="evenodd" class="efpe-zboe"/><defs><radialGradient id="i132g4d" cx="0" cy="0" r="1" gradientTransform="rotate(159.45 8.866 4.203)scale(8.16232 6.90297)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="jpk3lwb9k"/><stop offset=".879" class="mzsejxbhe"/></radialGradient><radialGradient id="iFWiuJb" cx="0" cy="0" r="1" gradientTransform="matrix(7.70897 -9.00929 11.38856 9.74484 6.164 15.347)" gradientUnits="userSpaceOnUse"><stop class="jwo0h5dbt"/><stop offset="1" class="igxv_jb3j"/></radialGradient><radialGradient id="iTyTRXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73002 0 0 -3.69719 8.345 14.27)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="lxwev9kth"/><stop offset="1" class="dbmm3wbls"/></radialGradient><radialGradient id="id4DIxe" cx="0" cy="0" r="1" gradientTransform="rotate(-109.573 9.054 .716)scale(1.93641 .96821)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="edx7bubmp"/><stop offset="1" class="m2s_72ssr"/></radialGradient><radialGradient id="iyRl8Wc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98962 0 0 -1.9032 7.308 19.1)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="inFETAf" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 57.517 -44.426)scale(5.09754 6.22385)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="i1SkC7d" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 66.88 -58.937)scale(2.41654)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="i9cGwTd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.06253 11.24998 -11.00901 -9.847 22.462 17.188)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="gmt6_psxo"/><stop offset="1" class="fgo4n-bok"/></radialGradient><radialGradient id="ipvqnGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1875 3.14012 0 20.4 17.281)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="v9h-bwbdq"/><stop offset="1" class="zgjs8ccpx"/></radialGradient><radialGradient id="ihU0plb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 2.75 0 11.994 17.281)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="t9sc4bbzq"/><stop offset="1" class="kqg5ugbzw"/></radialGradient><radialGradient id="iKznbjd" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 1.78125 -1.94444 .75048 11.588 18.656)" gradientUnits="userSpaceOnUse"><stop class="nzkoedb-r"/><stop offset="1" class="cahcukb8j"/></radialGradient><radialGradient id="iK0myTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.99991 13.56256 -19.47614 -5.74396 17.275 16.75)" gradientUnits="userSpaceOnUse"><stop offset=".605" class="bok47wbnv"/><stop offset="1" class="ze8r_ji0b"/></radialGradient><radialGradient id="iqZwpac" cx="0" cy="0" r="1" gradientTransform="rotate(100.183 4.94 20.535)scale(11.3126 2.49146)" gradientUnits="userSpaceOnUse"><stop class="r_8k9swvo"/><stop offset="1" class="q9ojxt_ur"/></radialGradient><radialGradient id="idg5kke" cx="0" cy="0" r="1" gradientTransform="rotate(62.199 -1.317 12.693)scale(1.94304 1.49899)" gradientUnits="userSpaceOnUse"><stop class="kpi7e9wsr"/><stop offset="1" class="mtco-acko"/></radialGradient><radialGradient id="ia0Vj7R" cx="0" cy="0" r="1" gradientTransform="matrix(3.3125 -3.125 2.10639 2.23277 6.806 10.5)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="kpi7e9wsr"/><stop offset="1" class="mtco-acko"/></radialGradient><radialGradient id="irr0Tbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27489 -5.6078 1.55926 -.35448 17.462 21.764)" gradientUnits="userSpaceOnUse"><stop class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iN47tjb" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 4.887 13.198)scale(2.93624 3.93288)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iIY7JDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.938 18.005)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i0qi8yc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.766 3.593)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iy5Ef4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 19.968 18.06)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iS2vvCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.543 18.216)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="imwKtZd" width="22.676" height="13.787" x="4.837" y="4.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.45098 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19566"/></filter><filter id="iVljgAb" width="6.15" height="6.25" x="4.308" y="16.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.627451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19566"/></filter><filter id="i5T35pd" width="4.979" height="4.979" x="4.818" y="16.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".25"/></filter><filter id="iO9ZqKd" width="6" height="6.25" x="22.008" y="15.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19566"/></filter><filter id="iADoZlc" width="4.979" height="4.979" x="22.543" y="16.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".25"/></filter><filter id="iSL2WFO" width="19.5" height="21.833" x="6.5" y="8.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.619608 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19566"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.501961 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19566" result="effect2_innerShadow_3987_19566"/></filter><filter id="id1CTGk" width="4.163" height="5.86" x="13.579" y="18.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".25"/></filter><filter id="i6JWWCb" width="4" height="5.5" x="14" y="17.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".125"/></filter><filter id="iF7kO9T" width="4.35" height="1.811" x="18.9" y="13.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.368627 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19566"/></filter><filter id="iHiPBHy" width="4.35" height="1.811" x="8.9" y="13.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.368627 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19566"/></filter><filter id="i6YnvRc" width="5.419" height="2.462" x="8.604" y="16.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19566"/></filter><filter id="iloatxz" width="5.419" height="2.462" x="18.104" y="16.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19566"/></filter><filter id="iGYvW1d" width="1.493" height="1.594" x="12.162" y="17.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".1"/></filter><filter id="iwp0kje" width="1.529" height="1.141" x="10.668" y="17.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".05"/></filter><filter id="iRkTeNe" width="1.294" height="1.125" x="18.686" y="17.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".05"/></filter><filter id="ivPkeLb" width="1.316" height="1.357" x="20.338" y="17.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".1"/></filter><filter id="icHY9Er" width="3.891" height="1.401" x="9.088" y="14.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".125"/></filter><filter id="i2wzpje" width="3.891" height="1.401" x="19.055" y="14.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".125"/></filter><filter id="iT69plc" width="17.593" height="9.464" x="9.558" y="4.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".625"/></filter><filter id="iMQvrfd" width="6.633" height="6.958" x="5.287" y="5.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19566" stdDeviation=".625"/></filter><linearGradient id="iNDqvYL" x1="4.308" x2="9.825" y1="19.263" y2="19.263" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="igPIitb" x1="16" x2="16" y1="23.218" y2="18.218" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="i5jbR2e" x1="14.049" x2="15.642" y1="21.796" y2="21.991" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iRlEodb" x1="16" x2="16" y1="23.389" y2="22.252" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="idX4lOd" x1="16.146" x2="16.146" y1="23.341" y2="23.081" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="ib1JKxM" x1="14.675" x2="15.469" y1="25.849" y2="24.286" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ilAj8th" x1="13.325" x2="12.74" y1="18.105" y2="18.466" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7qHxub" x1="21.418" x2="20.834" y1="18.16" y2="18.52" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izrafxc" x1="8.556" x2="12.025" y1="15.437" y2="14.187" gradientUnits="userSpaceOnUse"><stop class="w2ivw_b4o"/><stop offset="1" class="fpmaj-b2k"/></linearGradient><linearGradient id="iYtthJc" x1="18.072" x2="22.275" y1="14.39" y2="15.031" gradientUnits="userSpaceOnUse"><stop class="w2ivw_b4o"/><stop offset="1" class="fpmaj-b2k"/></linearGradient><linearGradient id="iYzNiVb" x1="22.557" x2="12.479" y1="9.495" y2="4.991" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient><linearGradient id="iyIWVxb" x1="10.32" x2="10.044" y1="7.452" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-woman" /></template>
<style>
.ab-jnnpfq {
  d: path("M27.022 19.1a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.bnx-9gb_w {
  fill: var(--svg-color--36292e, #36292E);
  d: path("M18.104 18.226c.494-.87.987-1.593 2.606-1.593c.969-.067 1.652.232 2.26.723c.501.405.42.835.06 1.148l-.793.582c-1.215-.393-2.817-.467-4.133-.86");
}

.bok47wbnv {
  stop-color: var(--svg-color--d67766, #D67766);
  stop-opacity: 0;
}

.cahcukb8j {
  stop-color: var(--svg-color--ffba23, #FFBA23);
  stop-opacity: 0;
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

.e_uz5pbaw {
  d: path("M13.455 18.584c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.e2se8v1zp {
  d: path("M19.85 17.522c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.edx7bubmp {
  stop-color: var(--svg-color--776169, #776169);
}

.efpe-zboe {
  fill: var(--svg-color--ffa30c, #FFA30C);
  fill-rule: evenodd;
  d: path("M13.48 20.086a.45.45 0 0 0-.636.031c-.196.217-.842.684-1.672.657a.45.45 0 1 0-.03.9c1.159.037 2.043-.593 2.369-.952a.45.45 0 0 0-.031-.636");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.elhu_bfua {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.192 18.987l-1.054 3.011c-.216.62.19 1.271.81 1.304l1.324.069c.621.032 1.093-.583.943-1.212l-.736-3.105c-.156-.687-1.05-.734-1.287-.067");
}

.enp4o1bhv {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M9.297 19.1a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.ep72r4b_h {
  fill: var(--svg-color--36292e, #36292E);
  d: path("M13.823 18.226c-.495-.87-.987-1.593-2.607-1.593c-.968-.067-1.652.232-2.26.723c-.5.405-.42.835-.06 1.148l.793.582c1.215-.393 2.817-.467 4.134-.86");
}

.eu_5adeum {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
  stop-opacity: 0;
}

.fgo4n-bok {
  stop-color: var(--svg-color--ee9830, #EE9830);
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fpmaj-b2k {
  stop-color: var(--svg-color--959092, #959092);
}

.ft_qk78lm {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
}

.ft5dv1b6b {
  fill: none;
}

.fzf99ttvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.358 16.663c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.557-2.103");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gmt6_psxo {
  stop-color: var(--svg-color--ffe335, #FFE335);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.i7vi0rq6c {
  fill: var(--svg-color--a5a5a5, #A5A5A5);
  d: path("M26.69 12.983C25.976 8.533 23.63 4.97 16 4.97c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014L6.5 14.366c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.igxv_jb3j {
  stop-color: var(--svg-color--82747b, #82747B);
  stop-opacity: 0;
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.jc1ppccfd {
  cx: 11.432px;
  cy: 17.826px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.jpk3lwb9k {
  stop-color: var(--svg-color--c3c3c3, #C3C3C3);
}

.jwo0h5dbt {
  stop-color: var(--svg-color--82747b, #82747B);
}

.kha3bxb8d {
  d: path("M10.67 7.03c-.116 1.076-.929 3.994-4.133 4.458c.03-1.176 1.045-4.156 4.133-4.458");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpi7e9wsr {
  stop-color: var(--svg-color--8c4b06, #8C4B06);
}

.kqg5ugbzw {
  stop-color: var(--svg-color--ed9128, #ED9128);
  stop-opacity: 0;
}

.krsahyb0g {
  d: path("M17.634 11.167c-4.272 0-6.27-3.127-6.826-4.55c0-.512 2.554-1.417 6.826-1.162c6.23.373 8.111 4.613 8.266 6.92c-.371-1.078-1.393-1.13-1.857-1.208z");
}

.kyklyjb9e {
  fill: var(--svg-color--7b7777, #7B7777);
  d: path("m22.857 14.789l-.002-.002l-.005-.003l-.018-.01l-.06-.034a6 6 0 0 0-.98-.411c-.635-.202-1.521-.372-2.478-.203a.5.5 0 0 0 .174.984c.743-.13 1.457-.001 1.999.172a5 5 0 0 1 .849.36l.008.005a.5.5 0 0 0 .514-.858");
}

.lgrkq2c6e {
  d: path("M10.308 19.1a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lr4e-z88g {
  fill: var(--svg-color--7b7777, #7B7777);
  d: path("m9.666 15.642l-.009.005a.5.5 0 0 1-.514-.858h.001l.002-.002l.006-.003l.017-.01a3 3 0 0 1 .277-.143c.184-.088.445-.2.765-.302c.633-.202 1.52-.372 2.476-.203a.5.5 0 0 1-.174.984c-.743-.13-1.457-.001-1.998.172a5 5 0 0 0-.85.36");
}

.luj6enz-m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.85 17.522c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.luw25xboi {
  d: path("M28.008 19a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
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

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mral5vd-y {
  fill: var(--svg-color--ffc31b, #FFC31B);
  fill-rule: evenodd;
  d: path("M18.602 20.086a.45.45 0 0 1 .636.031c.196.217.841.684 1.672.657a.45.45 0 1 1 .03.9c-1.16.037-2.043-.593-2.37-.952a.45.45 0 0 1 .032-.636");
}

.mtco-acko {
  stop-color: var(--svg-color--8c4b06, #8C4B06);
  stop-opacity: 0;
}

.mzsejxbhe {
  stop-color: var(--svg-color--868381, #868381);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nxl-dbcjo {
  d: path("M6.5 14.366c.038-1.77 1.07-2.454 1.51-2.682a1 1 0 0 0 .096-.039q.051-.022.096-.038a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.222 6.783c-.23 5.225-4.31 8.734-9.29 8.734c-4.981 0-9.061-3.509-9.291-8.734z");
}

.nzkoedb-r {
  stop-color: var(--svg-color--ffba23, #FFBA23);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq1e7sbto {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.549 16.609c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q9ojxt_ur {
  stop-color: var(--svg-color--ffda40, #FFDA40);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r_8k9swvo {
  stop-color: var(--svg-color--ffda40, #FFDA40);
}

.r2yk5gw0f {
  d: path("m15.287 18.744l-.99 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.rgy2i2b6g {
  d: path("M26.69 12.983C25.976 8.533 23.63 4.97 16 4.97c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014l-.058-2.576l-.019-.495l-.019-.57c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.rtngogk3c {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.44 23.957a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393A3.58 3.58 0 0 0 16 26.018a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607a5.54 5.54 0 0 1-2.56-.607Z");
}

.t4pkfp8jr {
  d: path("M26.69 12.983C25.976 8.533 23.63 4.97 16 4.97c-7.635 0-10.201 3.568-11.064 8.023c-.377 1.95.345 3.737 1.66 5.014L6.5 14.366c.038-1.77 1.07-2.454 1.51-2.682q.046-.016.096-.038q.051-.023.096-.039a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.1 3.045c1.027-1.223 1.566-2.804 1.29-4.515");
}

.t9sc4bbzq {
  stop-color: var(--svg-color--ed9128, #ED9128);
}

.uk2ytdbak {
  d: path("M9.297 19.1a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.utw_k16bp {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M27.022 19.1a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9h-bwbdq {
  stop-color: var(--svg-color--ffb827, #FFB827);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w-20hqkmf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.57 15.156c-.343-.245-1.553-.775-3.14-.625");
}

.w2ivw_b4o {
  stop-color: var(--svg-color--959092, #959092);
  stop-opacity: 0;
}

.wqp_7gbss {
  fill: var(--svg-color--000, #000);
  d: path("M19.019 18.834c0-.53.423-.953.953-.953s.953.424.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.439");
}

.wwps083zl {
  fill: var(--svg-color--000, #000);
  d: path("M12.888 18.78a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .16.037.31.106.439h1.686a.94.94 0 0 0 .114-.439");
}

.x9mlfx_2j {
  d: path("M21 7.063a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.xmkzofbmz {
  d: path("M19.972 17.17a1.664 1.664 0 0 1 1.603 2.103h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.67-1.664");
}

.yiw98ibiy {
  d: path("M11.935 17.115a1.664 1.664 0 0 0-1.604 2.103h3.215c.037-.144.06-.288.06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.ze8r_ji0b {
  stop-color: var(--svg-color--d67766, #D67766);
}

.zgjs8ccpx {
  stop-color: var(--svg-color--ffb827, #FFB827);
  stop-opacity: 0;
}

.zk3f21p4e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.463 15.156c.343-.245 1.553-.775 3.14-.625");
}

.zxgv1qbii {
  d: path("M21.454 18.615a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

</style>
