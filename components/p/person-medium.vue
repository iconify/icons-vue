<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iLgkYrK)" class="be6rpdeaj"/><path fill="url(#iZv1pFb)" class="u_8o32b5j"/><g filter="url(#iZNieqe)"><path fill="url(#iCAfdPc)" class="znj7aitbq"/><path fill="url(#i2Bk4ie)" class="znj7aitbq"/></g><path fill="url(#ivhSvmc)" class="znj7aitbq"/><path fill="url(#iJ3TIUd)" class="znj7aitbq"/><path fill="url(#iFVFHKc)" class="znj7aitbq"/><path fill="url(#ihgkJjb)" class="znj7aitbq"/><path fill="url(#ioYBncd)" class="znj7aitbq"/><path fill="url(#iVIbYlc)" class="znj7aitbq"/><path fill="url(#iMBoFQc)" class="znj7aitbq"/><path fill="url(#itLmmFe)" class="znj7aitbq"/><g filter="url(#i9AWWgj)"><path class="z9ga4xbmt"/></g><g filter="url(#iKMNJGd)"><path class="t7f-5kbuz"/><path fill="url(#i89qKIe)" class="oyvbqu0mt"/><path fill="url(#iJKpwbd)" class="oyvbqu0mt"/><path fill="url(#ibtWIYT)" class="oyvbqu0mt"/><path fill="url(#ipD2OGe)" class="oyvbqu0mt"/><path fill="url(#i8VNRHb)" class="oyvbqu0mt"/></g><path fill="url(#ipZzW4d)" class="oyvbqu0mt"/><path fill="url(#i43pu2c)" class="oyvbqu0mt"/><g filter="url(#iItdxPe)"><path stroke="url(#ighm3ke)" class="vhy08-bop"/></g><path fill="url(#iUUls1b)" class="mlzz411wz"/><g filter="url(#iIc9Xje)"><path fill="url(#iflWbuM)" class="pjk2z4bnh"/><path fill="url(#iN0Jrce)" class="pjk2z4bnh"/><path fill="url(#i4dWNlc)" class="pjk2z4bnh"/><path fill="url(#isgwdEY)" class="pjk2z4bnh"/><path fill="url(#ips1CtQ)" class="pjk2z4bnh"/></g><g filter="url(#iIcKYac)"><path class="rvhz-bbpu"/></g><g filter="url(#iDQg32b)"><path class="b-rui_b9n"/></g><g filter="url(#ilja3zb)"><path class="c-9x7nb8b"/><path fill="url(#i2aeGfd)" class="nm9wxtyyu"/><path fill="url(#iQuSGhd)" class="nm9wxtyyu"/></g><g filter="url(#iFmlopb)"><path class="jbnif4b5t"/><path fill="url(#ii3ZkHb)" class="pkja9bbsb"/><path fill="url(#iRCC2Uo)" class="pkja9bbsb"/><path fill="url(#ihuIWAd)" class="pkja9bbsb"/></g><path class="irwnsrbdy"/><path fill="url(#i7VoyFd)" class="t8rz6-b4j"/><path class="au9gygbbx"/><g filter="url(#imw2ZSb)"><path class="oqyz1-b1x"/><path fill="url(#iFJoSpc)" class="jhr6jzbby"/></g><g filter="url(#iy3FWpj)"><path fill="url(#i4ebNXO)" class="wagfjcb7l"/></g><path class="ae8styofm"/><path fill="url(#ibp6VUb)" class="rr7m3ibhc"/><path class="qcy-xjb9z"/><g filter="url(#iqqbYFc)"><path fill="url(#ilLt4wb)" class="kf_7dpbrd"/></g><g filter="url(#itFjUNc)"><ellipse transform="rotate(-27.914 11.338 16.646)" class="wti4q6bgh"/><ellipse fill="url(#in65Ppd)" transform="rotate(-27.914 11.338 16.646)" class="vhqb4xrsh"/></g><path fill="url(#i0C6DEZ)" class="x08-9gb4f"/><path fill="url(#iInCHkc)" class="x08-9gb4f"/><path fill="url(#i6fpBEe)" class="x08-9gb4f"/><path fill="url(#iiVdy7d)" class="x08-9gb4f"/><path fill="url(#iJpCOAb)" class="f4_kk0baf"/><path fill="url(#iE7AC6d)" class="f4_kk0baf"/><g filter="url(#ilt3ete)"><path fill="url(#i5jusge)" class="fmz6o5bzy"/></g><g filter="url(#i3UJZXc)"><path fill="url(#i97mQXY)" class="pumrz073t"/></g><g filter="url(#ixTNXab)"><path class="i0rsuccgt"/></g><g filter="url(#imAH8Cd)"><path class="cm6x3xbgl"/></g><defs><radialGradient id="iLgkYrK" cx="0" cy="0" r="1" gradientTransform="matrix(1.39603 3.76525 -4.47282 1.65837 24.775 20.288)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iZv1pFb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75273 .86514 -2.66903 8.49237 4.62 21.202)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iCAfdPc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.77212 0 0 -15.5178 21.147 18.533)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="i2Bk4ie" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24997 5.37502 -4.43752 -2.68312 20.438 9.25)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iJ3TIUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90593 23.16252 -19.18137 -1.57834 18.86 7.507)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="iFVFHKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.141 2.64949 0 20.475 16.085)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="ihgkJjb" cx="0" cy="0" r="1" gradientTransform="matrix(.00733 -2.04019 2.2202 .00797 11.624 16.172)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="ioYBncd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.835 10.54)scale(15.8715 40.5438)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iVIbYlc" cx="0" cy="0" r="1" gradientTransform="matrix(6.3125 -5.4375 1.60615 1.8646 3.25 13.438)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iMBoFQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 4.65625 -1.8613 -.17489 26.25 13.094)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="itLmmFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.625 -3.11954 0 11.781 17.61)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iJKpwbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4551 -1.43034 0 16.782 21.07)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="ipD2OGe" cx="0" cy="0" r="1" gradientTransform="rotate(156.092 6.381 11.803)scale(3.45078 5.54568)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="i43pu2c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39062 2.28126 -3.2924 -3.45025 16.719 19.469)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iUUls1b" cx="0" cy="0" r="1" gradientTransform="matrix(4.06811 -2 8.04654 16.36708 14.997 25.288)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iN0Jrce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.52791 16.5083 0 6.162 13.14)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="p2s973_gj"/><stop offset="1" class="p6dlq8bal"/></radialGradient><radialGradient id="i4dWNlc" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 20.64 -5.275)scale(4.68924 8.30841)" gradientUnits="userSpaceOnUse"><stop class="gpki0lbqt"/><stop offset="1" class="jxp-9c9su"/></radialGradient><radialGradient id="isgwdEY" cx="0" cy="0" r="1" gradientTransform="rotate(-149.819 11.362 -1.123)scale(5.93139 4.35394)" gradientUnits="userSpaceOnUse"><stop class="g6v8l_bkd"/><stop offset="1" class="gs7m3x8bv"/></radialGradient><radialGradient id="ips1CtQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 2.75 -6.36771 3.90746 14.225 .913)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="ptziuobjj"/><stop offset="1" class="irfbnmbhq"/></radialGradient><radialGradient id="i2aeGfd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10381 0 0 -1.52308 16.385 5.125)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iQuSGhd" cx="0" cy="0" r="1" gradientTransform="matrix(6 -9.5 10.52499 6.64735 5.787 12.475)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="ii3ZkHb" cx="0" cy="0" r="1" gradientTransform="matrix(5.70209 0 0 2.22942 22.277 6.573)" gradientUnits="userSpaceOnUse"><stop class="wkq1lrbro"/><stop offset="1" class="ay2ml8bfu"/></radialGradient><radialGradient id="iRCC2Uo" cx="0" cy="0" r="1" gradientTransform="rotate(-41.829 26.42 -21.126)scale(7.40336 13.5537)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="ihuIWAd" cx="0" cy="0" r="1" gradientTransform="matrix(6.01324 1.35007 -.56525 2.51763 19.213 8.84)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="i7VoyFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.98 16.825)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iFJoSpc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.936 3.702)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibp6VUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.844 16.825)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="in65Ppd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.138 3.05)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iInCHkc" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.15 24.594)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="i6fpBEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.194 17.866)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iiVdy7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.0944 -2.89062 3.86227 1.46228 25.406 18.188)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iE7AC6d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09167 0 0 -3.45229 6.748 18.046)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i5jusge" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.606 9.313)scale(1.73369 1.77757)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="iZNieqe" width="20.055" height="23.21" x="6.472" y="7.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2017"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2017" result="effect2_innerShadow_3930_2017"/></filter><filter id="i9AWWgj" width="5.257" height="7.407" x="13.019" y="15.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".5"/></filter><filter id="iKMNJGd" width="3.9" height="5.807" x="13.962" y="16.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".1"/></filter><filter id="iItdxPe" width="6.5" height="2.5" x="12.662" y="23.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".05"/></filter><filter id="iIc9Xje" width="24" height="15.148" x="3.912" y="1.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2017"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2017" result="effect2_innerShadow_3930_2017"/></filter><filter id="iIcKYac" width="4.274" height="2.047" x="18.875" y="11.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2017"/></filter><filter id="iDQg32b" width="4.274" height="2.019" x="9.075" y="11.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2017"/></filter><filter id="ilja3zb" width="12.344" height="11.239" x="4.541" y="3.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2017"/><feGaussianBlur result="effect2_foregroundBlur_3930_2017" stdDeviation=".25"/></filter><filter id="iFmlopb" width="12.594" height="10.965" x="15.417" y="3.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.152941 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2017"/><feGaussianBlur result="effect2_foregroundBlur_3930_2017" stdDeviation=".25"/></filter><filter id="imw2ZSb" width="1.294" height="1.125" x="18.698" y="16.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".05"/></filter><filter id="iy3FWpj" width="1.316" height="1.357" x="20.351" y="16.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".1"/></filter><filter id="iqqbYFc" width="1.493" height="1.594" x="12.068" y="16.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".1"/></filter><filter id="itFjUNc" width="1.529" height="1.141" x="10.574" y="16.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".05"/></filter><filter id="ilt3ete" width="2.045" height="4.004" x="4.791" y="16.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".125"/></filter><filter id="i3UJZXc" width="2.503" height="4.277" x="24.828" y="15.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".25"/></filter><filter id="ixTNXab" width="3.836" height="1.515" x="9.248" y="12.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".125"/></filter><filter id="imAH8Cd" width="3.836" height="1.515" x="19.091" y="12.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2017" stdDeviation=".125"/></filter><linearGradient id="ivhSvmc" x1="25.527" x2="20.813" y1="21.675" y2="21.675" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="i89qKIe" x1="17.475" x2="15.912" y1="19.791" y2="19.856" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="ibtWIYT" x1="15.912" x2="15.912" y1="21.915" y2="21.048" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="i8VNRHb" x1="15.912" x2="15.912" y1="16.872" y2="17.891" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="ipZzW4d" x1="16.688" x2="16.688" y1="22.172" y2="21.813" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="ighm3ke" x1="13.672" x2="14.266" y1="24.844" y2="23.288" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iflWbuM" x1="28.687" x2="7.037" y1="7.975" y2="7.975" gradientUnits="userSpaceOnUse"><stop class="ej5y0weeq"/><stop offset="1" class="fj0i7pb1f"/></linearGradient><linearGradient id="i4ebNXO" x1="21.431" x2="20.846" y1="16.925" y2="17.286" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilLt4wb" x1="13.231" x2="12.646" y1="16.925" y2="17.286" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0C6DEZ" x1="27.912" x2="25.662" y1="16.975" y2="21.033" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iJpCOAb" x1="5.006" x2="7.725" y1="18.288" y2="18.05" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="i97mQXY" x1="26.079" x2="26.079" y1="16.399" y2="19.677" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-medium" /></template>
<style>
.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.ae8styofm {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.455 15.429c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.au9gygbbx {
  fill: var(--svg-color--000, #000);
  d: path("M19.032 17.6a.95.95 0 0 1 .953-.954c.529 0 .952.424.952.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.ay2ml8bfu {
  stop-color: var(--svg-color--6b4e4e, #6B4E4E);
  stop-opacity: 0;
}

.b-rui_b9n {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M9.553 12.774a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.027a4.14 4.14 0 0 0-2.586.53a3 3 0 0 0-.17.112l-.006.004a.517.517 0 0 1-.633-.818z");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.be6rpdeaj {
  d: path("M24.976 20.863a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c-9x7nb8b {
  fill: var(--svg-color--533634, #533634);
  d: path("M16.346 8.063a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.181.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm6x3xbgl {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.552 13.21c-.48-.344-1.674-.949-3.086-.711");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ej5y0weeq {
  stop-color: var(--svg-color--6f514d, #6F514D);
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f4_kk0baf {
  d: path("M6.508 15.059a3.025 3.025 0 0 0-2.596 2.979a3 3 0 0 0 2.836 2.996q-.181-2.988-.24-5.975");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fj0i7pb1f {
  stop-color: var(--svg-color--523d3b, #523D3B);
}

.fmz6o5bzy {
  d: path("M6.431 16.299a1.782 1.782 0 0 0 .156 3.503c-.065-1.168-.12-2.335-.156-3.503");
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g6v8l_bkd {
  stop-color: var(--svg-color--563937, #563937);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gpki0lbqt {
  stop-color: var(--svg-color--473033, #473033);
}

.gs7m3x8bv {
  stop-color: var(--svg-color--563937, #563937);
  stop-opacity: 0;
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i0rsuccgt {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.623 13.296c.48-.344 1.674-.949 3.086-.711");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.irfbnmbhq {
  stop-color: var(--svg-color--654f4c, #654F4C);
  stop-opacity: 0;
}

.irwnsrbdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.37 15.429c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jbnif4b5t {
  fill: var(--svg-color--563936, #563936);
  d: path("m25.63 14.154l-.053-1.177c-.02-1.424-1.197-2.598-2.62-2.658h-2.611a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.587c2.066.274 4.934.919 6.905 2.204c3.252 2.122 2.683 5.945.97 7.746");
}

.jhr6jzbby {
  d: path("M19.862 16.287c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jxp-9c9su {
  stop-color: var(--svg-color--473033, #473033);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kf_7dpbrd {
  d: path("M13.36 17.404c0-.538-.437-.896-.555-1.005l-.537.52l.33.674z");
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mlzz411wz {
  d: path("M15.912 23.933a5.6 5.6 0 0 1-2.583-.612c-.255-.13-.53.158-.369.39a3.53 3.53 0 0 0 2.952 1.577a3.53 3.53 0 0 0 2.952-1.577c.161-.242-.113-.52-.369-.39a5.6 5.6 0 0 1-2.583.612");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nm9wxtyyu {
  d: path("M16.346 8.063a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.181.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.oqyz1-b1x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.862 16.287c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oyvbqu0mt {
  d: path("m15.2 17.2l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.427c-.213-.76-1.204-.76-1.426 0");
}

.p2s973_gj {
  stop-color: var(--svg-color--53403e, #53403E);
}

.p6dlq8bal {
  stop-color: var(--svg-color--53403e, #53403E);
  stop-opacity: 0;
}

.pjk2z4bnh {
  d: path("M24.964 6.148c.959.33 1.82 1 2.363 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.504 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.146-2.995c-.02-1.43-1.147-2.61-2.57-2.67h-2.611a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3l.058 2.866c-.474.07-.969.228-1.343.492v-2.238c0-.58-.178-1.15-.504-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.422-2.1a5 5 0 0 0 2.581-2.07a4.34 4.34 0 0 1 3.679-2.05c.603 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.701-.35c1.572 0 2.947.85 3.708 2.11c.574.95 1.474 1.64 2.522 2");
}

.pkja9bbsb {
  d: path("m25.63 14.154l-.053-1.177c-.02-1.424-1.197-2.598-2.62-2.658h-2.611a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.587c2.066.274 4.934.919 6.905 2.204c3.252 2.122 2.683 5.945.97 7.746");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.ptziuobjj {
  stop-color: var(--svg-color--654f4c, #654F4C);
}

.pumrz073t {
  d: path("M25.328 19.677q.092-1.639.176-3.278c.748.101 1.327.794 1.327 1.633c0 .903-.672 1.636-1.503 1.645");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qcy-xjb9z {
  fill: var(--svg-color--000, #000);
  d: path("M12.794 17.6a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rr7m3ibhc {
  d: path("M11.84 15.935a1.664 1.664 0 0 0-1.603 2.103h3.214q.059-.214.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.rvhz-bbpu {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M22.872 12.978c-.327-.285-.706-.586-1.282-.768c-.567-.178-1.277-.226-2.26-.106a.517.517 0 0 0 .125 1.027c.897-.11 1.447-.053 1.825.066c.37.116.62.305.913.56a.517.517 0 1 0 .679-.78");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.t7f-5kbuz {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.2 17.2l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.427c-.213-.76-1.204-.76-1.426 0");
}

.t8rz6-b4j {
  d: path("M19.985 15.935a1.664 1.664 0 0 1 1.603 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.672-1.664");
}

.u_8o32b5j {
  d: path("M6.849 20.863a3.06 3.06 0 0 1-1.687-.575v1.736c0 1.665.992 3.148 2.5 3.764a7.6 7.6 0 0 1-.644-2.2z");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vhqb4xrsh {
  cx: 11.338px;
  cy: 16.646px;
  rx: 0.726px;
  ry: 0.368px;
}

.vhy08-bop {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.364 23.255a.36.36 0 0 0-.43.073a.33.33 0 0 0-.036.425a3.6 3.6 0 0 0 3.014 1.61a3.6 3.6 0 0 0 3.015-1.61a.334.334 0 0 0-.037-.428a.36.36 0 0 0-.428-.07h-.001a5.5 5.5 0 0 1-2.549.603c-.934 0-1.812-.22-2.548-.604Z");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.wagfjcb7l {
  d: path("M21.467 17.38a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.426z");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wkq1lrbro {
  stop-color: var(--svg-color--6b4e4e, #6B4E4E);
}

.wti4q6bgh {
  cx: 11.338px;
  cy: 16.646px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.x08-9gb4f {
  d: path("M25.089 21.033q.186-2.975.344-5.95a3 3 0 0 1-.344 5.95");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.z9ga4xbmt {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.164 17.566l-1.101 3.427c-.189.705.263 1.41.903 1.41h1.364c.64 0 1.091-.716.903-1.41l-.922-3.427c-.198-.76-.94-.76-1.147 0");
}

.znj7aitbq {
  d: path("M6.917 23.688a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35c.22-3.512.441-7.01.605-10.52c-.02-1.43-1.148-2.61-2.572-2.67h-2.61a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3c0 3.47.217 6.882.445 10.36");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
