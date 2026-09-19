<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igoxEXd)" class="p1t68ub2u"/><g filter="url(#iyok3lb)"><path class="onheo8bba"/><path fill="url(#ijYIljj)" class="x2tagob0x"/></g><path fill="url(#i12Ftrt)" class="tos9toa0w"/><path fill="url(#iaTm0De)" class="tos9toa0w"/><g filter="url(#ilqFIWd)"><path fill="url(#i0pUZbe)" class="u4el_pbub"/></g><g filter="url(#isFCNLd)"><path class="u06d3zbvs"/><path fill="url(#i1zitIe)" class="jit21bcof"/></g><g filter="url(#i4aCtsb)"><path fill="url(#iXibLoe)" class="ecsl7pwdh"/><path fill="url(#i1iK1Cd)" class="ecsl7pwdh"/></g><g filter="url(#iBULBnc)"><path class="ab09hrbvw"/><path fill="url(#iLNMGMc)" class="svvkrhblm"/></g><g filter="url(#iSk0nhW)"><path fill="url(#iWshQHc)" class="oo-z-0bdz"/><path fill="url(#i8gAuII)" class="oo-z-0bdz"/><path fill="url(#iQ7tWhd)" class="oo-z-0bdz"/><path fill="url(#iz4TcSc)" class="oo-z-0bdz"/><path fill="url(#ijPjdOC)" class="oo-z-0bdz"/><path fill="url(#itrwpfb)" class="oo-z-0bdz"/></g><path fill="url(#iDtHJur)" class="oo-z-0bdz"/><path fill="url(#iY0LnDe)" class="oo-z-0bdz"/><path fill="url(#iu9UTTc)" class="oo-z-0bdz"/><path fill="url(#i6jLumb)" class="oo-z-0bdz"/><g filter="url(#ihfOKbb)"><path class="j116ke8ef"/></g><g filter="url(#i4GsH2c)"><path class="f-bh1dbvu"/><path fill="url(#iZiSeMb)" class="wi4cdsb7r"/><path fill="url(#iMmlDsd)" class="wi4cdsb7r"/><path fill="url(#iSccrYt)" class="wi4cdsb7r"/><path fill="url(#ioXs6eb)" class="wi4cdsb7r"/></g><path fill="url(#idu77ne)" class="wi4cdsb7r"/><path fill="url(#iNeG3Tb)" class="wi4cdsb7r"/><path stroke="url(#ifYUW5c)" class="tvf8_ibds"/><g filter="url(#iM0wG5i)"><path class="w3pv9o4ng"/></g><g filter="url(#iadlvsc)"><path class="f-wrv_bsh"/></g><g filter="url(#ixHOC6S)"><path class="ooybeuwfn"/></g><g filter="url(#iMyX0Lb)"><path class="blnb1hgzw"/></g><path class="kccskachc"/><path fill="url(#igpBNpd)" class="uksdmvb8v"/><path class="n5_jbqrja"/><g filter="url(#isEtLUd)"><path fill="url(#i1aWe6d)" class="foqmszbeh"/></g><g filter="url(#i53brVc)"><ellipse transform="rotate(-27.914 11.432 18.326)" class="iy8_2ibno"/><ellipse fill="url(#i4wIkIb)" transform="rotate(-27.914 11.432 18.326)" class="oxr24vbrk"/></g><path class="xdlhcqbvr"/><path fill="url(#iNCzPee)" class="h9r_sybgn"/><path class="c_7ab9q9j"/><g filter="url(#iOeP4Ac)"><path class="mzpt3xpio"/><path fill="url(#i1VldGi)" class="ume_64sfv"/></g><g filter="url(#idLU1He)"><path fill="url(#ip9plhc)" class="fymtymbzc"/></g><g filter="url(#i46bo6b)"><path stroke="url(#iicmMkj)" class="s00jozx4n"/></g><g filter="url(#ipfPv7c)"><path stroke="url(#iIrZtde)" class="rs3aw2b6w"/></g><g filter="url(#iOP6fpe)"><path fill="url(#i25OLJc)" class="t-y2r113w"/></g><g filter="url(#isI6YBb)"><path fill="url(#ibXBoTc)" class="or71rpdmj"/></g><path clip-rule="evenodd" class="yf7btbbww"/><path clip-rule="evenodd" class="v7t8cj09f"/><defs><radialGradient id="igoxEXd" cx="0" cy="0" r="1" gradientTransform="rotate(159.45 8.82 4.453)scale(8.16232 6.90297)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="jpk3lwb9k"/><stop offset=".879" class="mzsejxbhe"/></radialGradient><radialGradient id="ijYIljj" cx="0" cy="0" r="1" gradientTransform="matrix(7.70897 -9.00929 11.38856 9.74484 6.164 15.847)" gradientUnits="userSpaceOnUse"><stop class="jwo0h5dbt"/><stop offset="1" class="igxv_jb3j"/></radialGradient><radialGradient id="i12Ftrt" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73002 0 0 -3.69719 8.345 14.77)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="lxwev9kth"/><stop offset="1" class="dbmm3wbls"/></radialGradient><radialGradient id="iaTm0De" cx="0" cy="0" r="1" gradientTransform="rotate(-109.573 9.23 .966)scale(1.93641 .96821)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="edx7bubmp"/><stop offset="1" class="m2s_72ssr"/></radialGradient><radialGradient id="i1zitIe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23544 0 0 -1.76349 7.429 19.6)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iXibLoe" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 -3.79687 4.63581 4.15888 24.414 21.319)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="i1iK1Cd" cx="0" cy="0" r="1" gradientTransform="matrix(2.45313 1.375 -.38873 .69354 25.46 16.366)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iLNMGMc" cx="0" cy="0" r="1" gradientTransform="matrix(2.79684 -.20804 .16263 2.18635 24.225 19.807)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iWshQHc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.83758 10.56244 -10.33625 -9.62691 22.462 17.688)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="am3a9544w"/><stop offset="1" class="j1qr75obr"/></radialGradient><radialGradient id="i8gAuII" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1875 3.14012 0 20.4 17.781)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="pl7lspb3v"/><stop offset="1" class="owjbqrb5w"/></radialGradient><radialGradient id="iQ7tWhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 2.75 0 11.994 17.781)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="p9gefx6_p"/><stop offset="1" class="lshnc7l2t"/></radialGradient><radialGradient id="iz4TcSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.46875 -2.69492 0 11.588 19.156)" gradientUnits="userSpaceOnUse"><stop offset=".291" class="gabh4r9qh"/><stop offset="1" class="u_x9-l0lf"/></radialGradient><radialGradient id="ijPjdOC" cx="0" cy="0" r="1" gradientTransform="matrix(-2.72442 5.81787 -4.91398 -2.30114 19.9 12.778)" gradientUnits="userSpaceOnUse"><stop class="e5xuy61kp"/><stop offset="1" class="rp23cdihu"/></radialGradient><radialGradient id="itrwpfb" cx="0" cy="0" r="1" gradientTransform="rotate(-13.335 97.775 -61.44)scale(1.96872 2.43365)" gradientUnits="userSpaceOnUse"><stop class="qkza4tkjj"/><stop offset="1" class="t13m9bbya"/></radialGradient><radialGradient id="iDtHJur" cx="0" cy="0" r="1" gradientTransform="matrix(-3.99991 13.56256 -19.47614 -5.74396 17.275 17.25)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="lw-38m7ll"/><stop offset="1" class="rzuw14dkb"/></radialGradient><radialGradient id="iY0LnDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47497 10.6875 -2.35379 -.32484 25.5 20.25)" gradientUnits="userSpaceOnUse"><stop class="p2luicaxb"/><stop offset="1" class="ypy_6dbzj"/></radialGradient><radialGradient id="iu9UTTc" cx="0" cy="0" r="1" gradientTransform="matrix(1.06875 2.59374 -3.06547 1.26312 10.525 8.438)" gradientUnits="userSpaceOnUse"><stop class="tiegjubqx"/><stop offset="1" class="hhgglwylk"/></radialGradient><radialGradient id="i6jLumb" cx="0" cy="0" r="1" gradientTransform="matrix(4.8125 -4.4375 2.99107 3.24384 6.5 10.438)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="yexuwtdlp"/><stop offset="1" class="wxorzojah"/></radialGradient><radialGradient id="iZiSeMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.84932 -3.81088 1.17448 -.26175 17.462 22.264)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="ioXs6eb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45312 0 0 -.40625 17.016 22.658)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iNeG3Tb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5565 1.75513 -2.1094 -3.07252 16.703 21.549)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="igpBNpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51264 -2.40602 0 11.938 18.505)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i4wIkIb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 15.012 3.843)scale(.92124 1.10737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNCzPee" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.406 0 19.968 18.56)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1VldGi" cx="0" cy="0" r="1" gradientTransform="matrix(-.43239 -.5572 .76712 -.5953 19.543 18.716)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iyok3lb" width="22.676" height="13.787" x="4.837" y="4.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.45098 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19562"/></filter><filter id="ilqFIWd" width="6.15" height="6" x="4.308" y="16.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19562"/></filter><filter id="isFCNLd" width="4.779" height="4.779" x="4.918" y="17.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".2"/></filter><filter id="i4aCtsb" width="6" height="6.25" x="22.008" y="16.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19562"/></filter><filter id="iBULBnc" width="4.979" height="4.979" x="22.543" y="17.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".25"/></filter><filter id="iSk0nhW" width="20" height="21.833" x="6.5" y="9.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.690196 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19562"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.603922 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19562" result="effect2_innerShadow_3987_19562"/></filter><filter id="ihfOKbb" width="4.5" height="6" x="13.438" y="18.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".25"/></filter><filter id="i4GsH2c" width="4" height="5.5" x="14" y="18.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".125"/></filter><filter id="iM0wG5i" width="4.35" height="1.811" x="18.9" y="14.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19562"/></filter><filter id="iadlvsc" width="4.35" height="1.811" x="8.9" y="14.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.305882 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19562"/></filter><filter id="ixHOC6S" width="5.419" height="2.462" x="8.604" y="17.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19562"/></filter><filter id="iMyX0Lb" width="5.419" height="2.462" x="18.104" y="17.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19562"/></filter><filter id="isEtLUd" width="1.493" height="1.594" x="12.162" y="17.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".1"/></filter><filter id="i53brVc" width="1.529" height="1.141" x="10.668" y="17.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".05"/></filter><filter id="iOeP4Ac" width="1.294" height="1.125" x="18.686" y="17.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".05"/></filter><filter id="idLU1He" width="1.316" height="1.357" x="20.338" y="18.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".1"/></filter><filter id="i46bo6b" width="3.891" height="1.401" x="9.088" y="14.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".125"/></filter><filter id="ipfPv7c" width="3.891" height="1.401" x="19.219" y="14.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".125"/></filter><filter id="iOP6fpe" width="17.593" height="9.464" x="9.558" y="4.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".625"/></filter><filter id="isI6YBb" width="6.633" height="6.958" x="5.287" y="6.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19562" stdDeviation=".625"/></filter><linearGradient id="i0pUZbe" x1="4.308" x2="9.825" y1="19.762" y2="19.762" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iMmlDsd" x1="14.25" x2="16" y1="22.4" y2="22.4" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iSccrYt" x1="16" x2="16" y1="23.889" y2="22.752" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="idu77ne" x1="16.146" x2="16.146" y1="23.841" y2="23.581" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="ifYUW5c" x1="14.066" x2="14.877" y1="26.23" y2="24.947" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="i1aWe6d" x1="13.325" x2="12.74" y1="18.605" y2="18.966" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ip9plhc" x1="21.418" x2="20.834" y1="18.66" y2="19.02" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iicmMkj" x1="9.74" x2="12.771" y1="15.901" y2="15.005" gradientUnits="userSpaceOnUse"><stop class="wgmwydz1w"/><stop offset="1" class="jxtrqmq9q"/></linearGradient><linearGradient id="iIrZtde" x1="18.236" x2="22.439" y1="14.841" y2="15.482" gradientUnits="userSpaceOnUse"><stop class="wgmwydz1w"/><stop offset="1" class="jxtrqmq9q"/></linearGradient><linearGradient id="i25OLJc" x1="22.557" x2="12.479" y1="9.995" y2="5.491" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient><linearGradient id="ibXBoTc" x1="10.32" x2="10.044" y1="7.952" y2="10.795" gradientUnits="userSpaceOnUse"><stop class="ft_qk78lm"/><stop offset="1" class="eu_5adeum"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:old-woman-light" /></template>
<style>
.ab09hrbvw {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M27.022 19.6a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.am3a9544w {
  stop-color: var(--svg-color--ffdcc1, #FFDCC1);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.blnb1hgzw {
  fill: var(--svg-color--36292e, #36292E);
  d: path("M18.104 18.726c.494-.87.987-1.593 2.606-1.593c.969-.067 1.652.232 2.26.723c.501.405.42.835.06 1.148l-.793.582c-1.215-.393-2.817-.467-4.133-.86");
}

.c_7ab9q9j {
  fill: var(--svg-color--000, #000);
  d: path("M19.019 19.334c0-.53.423-.953.953-.953s.953.423.953.953a.94.94 0 0 1-.106.439h-1.687a.86.86 0 0 1-.113-.44");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.dbmm3wbls {
  stop-color: var(--svg-color--6f524d, #6F524D);
  stop-opacity: 0;
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5xuy61kp {
  stop-color: var(--svg-color--f0bfb1, #F0BFB1);
}

.ecsl7pwdh {
  d: path("M28.008 19.5a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.edx7bubmp {
  stop-color: var(--svg-color--776169, #776169);
}

.eu_5adeum {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
  stop-opacity: 0;
}

.f-bh1dbvu {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.287 19.244l-.99 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.f-wrv_bsh {
  fill: var(--svg-color--7e7c7f, #7E7C7F);
  d: path("m9.666 16.142l-.009.005a.5.5 0 0 1-.514-.858h.001l.002-.002l.006-.003l.017-.01a3 3 0 0 1 .277-.143c.184-.088.445-.2.765-.302c.633-.202 1.52-.372 2.476-.203a.5.5 0 0 1-.174.984c-.743-.13-1.457-.001-1.998.172a5 5 0 0 0-.85.36");
}

.foqmszbeh {
  d: path("M13.455 19.084c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.ft_qk78lm {
  stop-color: var(--svg-color--bbb9bc, #BBB9BC);
}

.ft5dv1b6b {
  fill: none;
}

.fymtymbzc {
  d: path("M21.454 19.115a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.gabh4r9qh {
  stop-color: var(--svg-color--e8b49e, #E8B49E);
}

.h9r_sybgn {
  d: path("M19.972 17.67a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.67-1.664");
}

.hhgglwylk {
  stop-color: var(--svg-color--8d5d52, #8D5D52);
  stop-opacity: 0;
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.igxv_jb3j {
  stop-color: var(--svg-color--82747b, #82747B);
  stop-opacity: 0;
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.iy8_2ibno {
  cx: 11.432px;
  cy: 18.326px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.j116ke8ef {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.25 19.475l-1.266 3.17a1.005 1.005 0 0 0 .97 1.303h1.467c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.701-.929-.701-1.151 0");
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.jit21bcof {
  d: path("M9.297 19.6a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
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

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kccskachc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.549 17.109c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lshnc7l2t {
  stop-color: var(--svg-color--cf948d, #CF948D);
  stop-opacity: 0;
}

.lw-38m7ll {
  stop-color: var(--svg-color--b67994, #B67994);
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

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mzpt3xpio {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.85 18.022c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.mzsejxbhe {
  stop-color: var(--svg-color--868381, #868381);
}

.n5_jbqrja {
  fill: var(--svg-color--000, #000);
  d: path("M12.888 19.28a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .159.037.31.106.439h1.686a.94.94 0 0 0 .114-.439");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.onheo8bba {
  fill: var(--svg-color--a5a5a5, #A5A5A5);
  d: path("M26.69 13.483C25.976 9.033 23.63 5.47 16 5.47c-7.635 0-10.201 3.569-11.064 8.024c-.377 1.95.345 3.736 1.66 5.014L6.5 14.865c.038-1.769 1.07-2.453 1.51-2.682q.046-.016.096-.038t.096-.038a4.3 4.3 0 0 0 2.217-2.302l.153-.361a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.483l-.1 3.046c1.027-1.223 1.566-2.804 1.29-4.515");
}

.oo-z-0bdz {
  d: path("M6.5 14.866c.038-1.77 1.07-2.454 1.51-2.682a1 1 0 0 0 .096-.039q.051-.022.096-.038a4.3 4.3 0 0 0 2.217-2.301l.153-.362a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.484l-.222 6.783c-.23 5.225-4.31 8.734-9.29 8.734c-4.981 0-9.061-3.509-9.291-8.734z");
}

.ooybeuwfn {
  fill: var(--svg-color--36292e, #36292E);
  d: path("M13.823 18.726c-.495-.87-.987-1.593-2.607-1.593c-.968-.067-1.652.232-2.26.723c-.5.405-.42.835-.06 1.148l.793.582c1.215-.393 2.817-.467 4.134-.86");
}

.or71rpdmj {
  d: path("M10.67 7.53c-.116 1.076-.929 3.994-4.133 4.458c.03-1.176 1.045-4.156 4.133-4.458");
}

.owjbqrb5w {
  stop-color: var(--svg-color--f4b9a9, #F4B9A9);
  stop-opacity: 0;
}

.oxr24vbrk {
  cx: 11.432px;
  cy: 18.326px;
  rx: 0.726px;
  ry: 0.368px;
}

.p1t68ub2u {
  d: path("M21 7.563a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

.p2luicaxb {
  stop-color: var(--svg-color--ffd7bb, #FFD7BB);
}

.p9gefx6_p {
  stop-color: var(--svg-color--cf948d, #CF948D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl7lspb3v {
  stop-color: var(--svg-color--f4b9a9, #F4B9A9);
}

.qkza4tkjj {
  stop-color: var(--svg-color--ffdcc2, #FFDCC2);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rp23cdihu {
  stop-color: var(--svg-color--f0bfb1, #F0BFB1);
  stop-opacity: 0;
}

.rs3aw2b6w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.734 15.607c-.344-.245-1.553-.775-3.14-.625");
}

.rzuw14dkb {
  stop-color: var(--svg-color--b67994, #B67994);
}

.s00jozx4n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.463 15.656c.343-.245 1.553-.775 3.14-.625");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.svvkrhblm {
  d: path("M27.022 19.6a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t-y2r113w {
  d: path("M17.634 11.667c-4.272 0-6.27-3.127-6.826-4.55c0-.512 2.554-1.417 6.826-1.162c6.23.373 8.111 4.613 8.266 6.92c-.371-1.078-1.393-1.13-1.857-1.208z");
}

.t13m9bbya {
  stop-color: var(--svg-color--ffdcc2, #FFDCC2);
  stop-opacity: 0;
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tiegjubqx {
  stop-color: var(--svg-color--8d5d52, #8D5D52);
}

.tos9toa0w {
  d: path("M26.69 13.483C25.976 9.033 23.63 5.47 16 5.47c-7.635 0-10.201 3.569-11.064 8.024c-.377 1.95.345 3.736 1.66 5.014l-.058-2.576l-.019-.495l-.019-.57c.038-1.77 1.07-2.454 1.51-2.683q.046-.016.096-.038t.096-.038a4.3 4.3 0 0 0 2.217-2.302l.153-.361a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.483l-.1 3.046c1.027-1.223 1.566-2.804 1.29-4.515");
}

.tvf8_ibds {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.44 24.457a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393A3.58 3.58 0 0 0 16 26.518a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607a5.54 5.54 0 0 1-2.56-.607Z");
}

.u_x9-l0lf {
  stop-color: var(--svg-color--e8b49e, #E8B49E);
  stop-opacity: 0;
}

.u06d3zbvs {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M9.297 19.6a1.99 1.99 0 1 1-3.979 0a1.99 1.99 0 0 1 3.98 0");
}

.u4el_pbub {
  d: path("M10.308 19.6a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uksdmvb8v {
  d: path("M11.935 17.615a1.664 1.664 0 0 0-1.604 2.103h3.215c.037-.144.06-.288.06-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.ume_64sfv {
  d: path("M19.85 18.022c.118.158-.13.352-.412.562s-.49.36-.609.2c-.119-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v7t8cj09f {
  fill: var(--svg-color--e19b92, #E19B92);
  fill-rule: evenodd;
  d: path("M13.48 20.586a.45.45 0 0 0-.636.031c-.196.217-.842.684-1.672.657a.45.45 0 1 0-.03.9c1.159.037 2.043-.593 2.369-.952a.45.45 0 0 0-.031-.636");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w3pv9o4ng {
  fill: var(--svg-color--7e7c7f, #7E7C7F);
  d: path("m22.857 15.289l-.002-.002l-.005-.003l-.018-.01l-.06-.034a6 6 0 0 0-.98-.411c-.635-.202-1.521-.372-2.478-.203a.5.5 0 0 0 .174.984c.743-.13 1.457-.001 1.999.172a5 5 0 0 1 .849.36l.008.005a.5.5 0 0 0 .514-.858");
}

.wgmwydz1w {
  stop-color: var(--svg-color--a3a2a4, #A3A2A4);
  stop-opacity: 0;
}

.wi4cdsb7r {
  d: path("m15.287 19.244l-.99 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.97-1.304l-.99-3.17c-.213-.702-1.203-.702-1.426 0");
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wxorzojah {
  stop-color: var(--svg-color--9a6250, #9A6250);
  stop-opacity: 0;
}

.x2tagob0x {
  d: path("M26.69 13.483C25.976 9.033 23.63 5.47 16 5.47c-7.635 0-10.201 3.569-11.064 8.024c-.377 1.95.345 3.736 1.66 5.014L6.5 14.865c.038-1.769 1.07-2.453 1.51-2.682q.046-.016.096-.038t.096-.038a4.3 4.3 0 0 0 2.217-2.302l.153-.361a.492.492 0 0 1 .86-.095a7.2 7.2 0 0 0 5.947 3.12h6.003c.336 0 2.018.163 2.118 2.483l-.1 3.046c1.027-1.223 1.566-2.804 1.29-4.515");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdlhcqbvr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.358 17.163c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.557-2.103");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.yexuwtdlp {
  stop-color: var(--svg-color--9a6250, #9A6250);
}

.yf7btbbww {
  fill: var(--svg-color--ffbcae, #FFBCAE);
  fill-rule: evenodd;
  d: path("M18.602 20.586a.45.45 0 0 1 .636.031c.196.217.841.684 1.672.657a.45.45 0 1 1 .03.9c-1.16.037-2.043-.593-2.37-.952a.45.45 0 0 1 .032-.636");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.ypy_6dbzj {
  stop-color: var(--svg-color--ffd7bb, #FFD7BB);
  stop-opacity: 0;
}

</style>
