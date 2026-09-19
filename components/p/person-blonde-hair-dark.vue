<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igCx29d)" class="be6rpdeaj"/><path fill="url(#ikzWnGb)" class="be6rpdeaj"/><path fill="url(#i8oUbYb)" class="u_8o32b5j"/><path fill="url(#iaWYesc)" class="u_8o32b5j"/><g filter="url(#i8FAZWw)"><path fill="url(#if9g38A)" class="znj7aitbq"/></g><path fill="url(#iNWJeCe)" class="znj7aitbq"/><path fill="url(#iTzo4Qn)" class="znj7aitbq"/><path fill="url(#i9y0qAb)" class="znj7aitbq"/><path fill="url(#iQC01Wb)" class="znj7aitbq"/><path fill="url(#irH9oCd)" class="znj7aitbq"/><path fill="url(#iS8iGAb)" class="znj7aitbq"/><path fill="url(#ihl9kAd)" class="znj7aitbq"/><path fill="url(#iZtpmad)" class="znj7aitbq"/><g filter="url(#iczIbkc)"><path class="e3kumhuuk"/></g><g filter="url(#i4RZvwc)"><path class="oaqqe4bgw"/><path fill="url(#i8op47b)" class="f3xy4fbyy"/><path fill="url(#iKYBOOe)" class="f3xy4fbyy"/><path fill="url(#i2ZAwBR)" class="f3xy4fbyy"/><path fill="url(#iozY2Yd)" class="f3xy4fbyy"/><path fill="url(#i9ezFpc)" class="f3xy4fbyy"/></g><g filter="url(#inQvlYb)"><path stroke="url(#izOywId)" class="vhy08-bop"/></g><path fill="url(#iKX5Imc)" class="ovub05bqx"/><g filter="url(#iQZpeRc)"><path fill="url(#iM2euse)" class="pjk2z4bnh"/><path fill="url(#i9VzAFD)" class="pjk2z4bnh"/><path fill="url(#iFMoLId)" class="pjk2z4bnh"/><path fill="url(#iyusiFc)" class="pjk2z4bnh"/><path fill="url(#iUQnxPb)" class="pjk2z4bnh"/></g><g filter="url(#ia4ofRb)"><path class="h1j8qf4ba"/></g><g filter="url(#iPfG6Sc)"><path class="rgfkbzb4o"/></g><g filter="url(#i795XHb)"><path fill="url(#ij6swJe)" class="ds71pnb-p"/><path fill="url(#iuZOURb)" class="ds71pnb-p"/></g><g filter="url(#igez9Md)"><path fill="url(#iVo001u)" class="pkja9bbsb"/><path fill="url(#itlCImc)" class="pkja9bbsb"/><path fill="url(#ip7s9Le)" class="pkja9bbsb"/><path fill="url(#iDM242G)" class="pkja9bbsb"/><path fill="url(#iS3D8ye)" class="pkja9bbsb"/></g><path class="irwnsrbdy"/><path fill="url(#i7VoyFd)" class="t8rz6-b4j"/><path class="au9gygbbx"/><g filter="url(#ihpT7DW)"><path class="oqyz1-b1x"/><path fill="url(#iFJoSpc)" class="jhr6jzbby"/></g><g filter="url(#izcL3hX)"><path fill="url(#i4ebNXO)" class="wagfjcb7l"/></g><path class="lks4f7lui"/><path fill="url(#ibp6VUb)" class="zumy-vz5s"/><path class="qcy-xjb9z"/><g filter="url(#iwkuS0k)"><path fill="url(#ixlhrFb)" class="kf_7dpbrd"/></g><g filter="url(#igR19ve)"><ellipse transform="rotate(-27.914 11.338 16.646)" class="wti4q6bgh"/><ellipse fill="url(#in65Ppd)" transform="rotate(-27.914 11.338 16.646)" class="vhqb4xrsh"/></g><path fill="url(#i1QwGXv)" class="x08-9gb4f"/><path fill="url(#iuep5Ab)" class="x08-9gb4f"/><path fill="url(#iqfaSHK)" class="x08-9gb4f"/><path fill="url(#iZt9mFe)" class="x08-9gb4f"/><path fill="url(#i0x39ed)" class="o5-qtcc3y"/><path fill="url(#icFMlmb)" class="o5-qtcc3y"/><g filter="url(#iW1Wbwb)"><path fill="url(#ifM80ub)" class="fmz6o5bzy"/></g><g filter="url(#ixhqqic)"><path fill="url(#idibuhb)" class="m2sqkwbus"/></g><g filter="url(#iWfSnPb)"><path class="vkgn28s3c"/></g><g filter="url(#ilE9vFb)"><path class="vg4ncn-3a"/></g><defs><radialGradient id="igCx29d" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 5.157 20.46)scale(6.07867 7.22099)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="bwfxpzp0c"/><stop offset="1" class="cqf-ohbhv"/></radialGradient><radialGradient id="ikzWnGb" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 .75 -.63714 .46458 24.866 20.788)" gradientUnits="userSpaceOnUse"><stop class="dhmh3e1ol"/><stop offset="1" class="rz5bd0b6s"/></radialGradient><radialGradient id="i8oUbYb" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 5 -2.27273 1.07954 5.569 20.507)" gradientUnits="userSpaceOnUse"><stop class="kpym4yewg"/><stop offset="1" class="t51tzvbuk"/></radialGradient><radialGradient id="iaWYesc" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 1.85937 -1.63106 .52084 6.803 20.491)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="s-wuddcax"/><stop offset="1" class="htl_mzbwg"/></radialGradient><radialGradient id="if9g38A" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.147 18.533)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iTzo4Qn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90593 23.16252 -19.18137 -1.57834 18.86 7.507)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="i9y0qAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.141 2.64949 0 20.475 16.085)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iQC01Wb" cx="0" cy="0" r="1" gradientTransform="matrix(.00733 -2.04019 2.2202 .00797 11.624 16.172)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="irH9oCd" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.835 10.54)scale(15.8715 40.5438)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iS8iGAb" cx="0" cy="0" r="1" gradientTransform="matrix(7.59374 -4.9375 1.80748 2.77985 5.719 10.469)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="ihl9kAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 4.65625 -1.8613 -.17489 26.25 13.094)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iZtpmad" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24997 5.37502 -4.43752 -2.68312 20.438 9.25)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iKYBOOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4551 -1.43034 0 16.782 21.07)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iozY2Yd" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.315 11.86)scale(3.11992 5.01397)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iKX5Imc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 15.912 25.132)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="i9VzAFD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.162 15.584)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="ynmqlsboi"/><stop offset="1" class="ipxdzpbtr"/></radialGradient><radialGradient id="iFMoLId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 24.975 15.584)" gradientUnits="userSpaceOnUse"><stop class="nerkoubdj"/><stop offset="1" class="t52ha8bdg"/></radialGradient><radialGradient id="iyusiFc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 12.142 -.23)scale(6.48857 3.45559)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iUQnxPb" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 2.625 -6.38151 7.90093 8.725 3.37)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="l_pokqbdh"/><stop offset="1" class="y7-q8z4gm"/></radialGradient><radialGradient id="ij6swJe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.13156 2.93075 -.8157 -2.2632 16.385 3.602)" gradientUnits="userSpaceOnUse"><stop class="hr217vhio"/><stop offset="1" class="o3acwp2gg"/></radialGradient><radialGradient id="iuZOURb" cx="0" cy="0" r="1" gradientTransform="rotate(-58.775 14.498 1.61)scale(11.9254 13.2121)" gradientUnits="userSpaceOnUse"><stop class="twinuccla"/><stop offset=".233" class="n78pd-b5i"/><stop offset="1" class="age677bqv"/></radialGradient><radialGradient id="iVo001u" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -12.537 99.92)scale(6.48667 2.48758)" gradientUnits="userSpaceOnUse"><stop class="vsbibr_ed"/><stop offset="1" class="zmahyob7y"/></radialGradient><radialGradient id="itlCImc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.813 -.26)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="w-6a5tbqx"/><stop offset="1" class="dgs1e68st"/></radialGradient><radialGradient id="ip7s9Le" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.319 13.594)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="j4tu-1b_q"/><stop offset="1" class="w5r4ae2jv"/></radialGradient><radialGradient id="iDM242G" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.109 4.145)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="mbtrbz0eb"/><stop offset="1" class="pyp_qyqhv"/></radialGradient><radialGradient id="iS3D8ye" cx="0" cy="0" r="1" gradientTransform="matrix(-.21876 .71543 -3.27084 -1.00012 22.35 5.118)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="ota_qabww"/><stop offset="1" class="wuchx3byb"/></radialGradient><radialGradient id="i7VoyFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.98 16.825)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iFJoSpc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.936 3.702)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibp6VUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.844 16.825)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="in65Ppd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.138 3.05)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuep5Ab" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.15 24.594)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iqfaSHK" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.194 17.866)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iZt9mFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.0944 -2.89062 3.86227 1.46228 25.406 18.188)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="icFMlmb" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -3.993 11.085)scale(3.94637 3.87964)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="ifM80ub" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.606 9.313)scale(1.73369 .76465)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="i8FAZWw" width="20.055" height="23.21" x="6.472" y="7.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2164"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2164" result="effect2_innerShadow_3930_2164"/></filter><filter id="iczIbkc" width="5.257" height="7.407" x="13.019" y="15.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".5"/></filter><filter id="i4RZvwc" width="3.9" height="5.807" x="13.962" y="16.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".1"/></filter><filter id="inQvlYb" width="6.5" height="2.5" x="12.662" y="23.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".05"/></filter><filter id="iQZpeRc" width="24" height="15.148" x="3.912" y="1.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.741176 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2164"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2164" result="effect2_innerShadow_3930_2164"/></filter><filter id="ia4ofRb" width="4.274" height="2.047" x="18.875" y="11.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2164"/></filter><filter id="iPfG6Sc" width="4.274" height="2.019" x="9.075" y="11.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2164"/></filter><filter id="i795XHb" width="12.344" height="11.239" x="4.541" y="3.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".25"/></filter><filter id="igez9Md" width="12.094" height="10.965" x="15.417" y="3.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".25"/></filter><filter id="ihpT7DW" width="1.294" height="1.125" x="18.698" y="16.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".05"/></filter><filter id="izcL3hX" width="1.316" height="1.357" x="20.351" y="16.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".1"/></filter><filter id="iwkuS0k" width="1.493" height="1.594" x="12.068" y="16.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".1"/></filter><filter id="igR19ve" width="1.529" height="1.141" x="10.574" y="16.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".05"/></filter><filter id="iW1Wbwb" width="2.045" height="4.004" x="4.791" y="16.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".125"/></filter><filter id="ixhqqic" width="2.765" height="4.549" x="24.628" y="15.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".25"/></filter><filter id="iWfSnPb" width="3.836" height="1.515" x="9.248" y="12.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".125"/></filter><filter id="ilE9vFb" width="3.836" height="1.515" x="19.091" y="12.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2164" stdDeviation=".125"/></filter><linearGradient id="iNWJeCe" x1="25.527" x2="17.412" y1="21.675" y2="21.675" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="i8op47b" x1="17.475" x2="15.912" y1="19.791" y2="19.856" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="i2ZAwBR" x1="15.912" x2="15.912" y1="21.915" y2="21.048" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="i9ezFpc" x1="15.912" x2="15.912" y1="16.406" y2="17.891" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="izOywId" x1="13.672" x2="14.266" y1="24.844" y2="23.288" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iM2euse" x1="25.912" x2="7.037" y1="7.975" y2="7.975" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="gz4sdm9gk"/></linearGradient><linearGradient id="i4ebNXO" x1="21.431" x2="20.846" y1="16.925" y2="17.286" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixlhrFb" x1="13.231" x2="12.646" y1="16.925" y2="17.285" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1QwGXv" x1="27.912" x2="25.662" y1="16.975" y2="21.033" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="i0x39ed" x1="5.006" x2="7.725" y1="18.288" y2="18.05" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="idibuhb" x1="26.011" x2="26.011" y1="16.264" y2="19.812" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-blonde-hair-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.age677bqv {
  stop-color: var(--svg-color--e8b391, #E8B391);
  stop-opacity: 0;
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.au9gygbbx {
  fill: var(--svg-color--000, #000);
  d: path("M19.032 17.6a.95.95 0 0 1 .953-.954c.529 0 .952.424.952.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.be6rpdeaj {
  d: path("M24.976 20.863a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bwfxpzp0c {
  stop-color: var(--svg-color--ffe1b0, #FFE1B0);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqf-ohbhv {
  stop-color: var(--svg-color--e0a598, #E0A598);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dgs1e68st {
  stop-color: var(--svg-color--f0c297, #F0C297);
  stop-opacity: 0;
}

.dhmh3e1ol {
  stop-color: var(--svg-color--f1b78d, #F1B78D);
}

.ds71pnb-p {
  d: path("M16.346 8.063a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.182.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3kumhuuk {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.164 17.566l-1.101 3.427c-.189.705.263 1.41.903 1.41h1.364c.64 0 1.091-.716.903-1.41l-.922-3.427c-.198-.76-.94-.76-1.147 0");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f3xy4fbyy {
  d: path("m15.2 17.2l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fmz6o5bzy {
  d: path("M6.431 16.299a1.782 1.782 0 0 0 .156 3.503c-.065-1.168-.12-2.335-.156-3.503");
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gz4sdm9gk {
  stop-color: var(--svg-color--efcb95, #EFCB95);
}

.h1j8qf4ba {
  fill: var(--svg-color--202020, #202020);
  d: path("M22.872 12.978c-.327-.285-.706-.586-1.282-.768c-.567-.178-1.277-.226-2.26-.106a.517.517 0 1 0 .125 1.027c.897-.11 1.447-.053 1.825.066c.37.116.62.305.913.56a.517.517 0 0 0 .679-.78");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.hr217vhio {
  stop-color: var(--svg-color--fff9b8, #FFF9B8);
}

.htl_mzbwg {
  stop-color: var(--svg-color--d69b78, #D69B78);
  stop-opacity: 0;
}

.ipxdzpbtr {
  stop-color: var(--svg-color--e6b386, #E6B386);
  stop-opacity: 0;
}

.irwnsrbdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.37 15.429c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j4tu-1b_q {
  stop-color: var(--svg-color--eab68a, #EAB68A);
}

.jhr6jzbby {
  d: path("M19.862 16.287c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kf_7dpbrd {
  d: path("M13.36 17.404c0-.538-.437-.896-.555-1.005l-.537.52l.33.674z");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kpym4yewg {
  stop-color: var(--svg-color--f0b78e, #F0B78E);
}

.l_pokqbdh {
  stop-color: var(--svg-color--e0ca93, #E0CA93);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lks4f7lui {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.455 15.429a2.6 2.6 0 0 0-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m2sqkwbus {
  d: path("M25.128 19.812q.109-1.774.206-3.549a1.782 1.782 0 0 1-.206 3.55");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbtrbz0eb {
  stop-color: var(--svg-color--e6b383, #E6B383);
  stop-opacity: 0;
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.n78pd-b5i {
  stop-color: var(--svg-color--e8b391, #E8B391);
}

.nerkoubdj {
  stop-color: var(--svg-color--fed69f, #FED69F);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o3acwp2gg {
  stop-color: var(--svg-color--fff9b8, #FFF9B8);
  stop-opacity: 0;
}

.o5-qtcc3y {
  d: path("M6.49 15.068a3 3 0 0 0 .258 5.966c-.12-1.993-.22-3.974-.258-5.966");
}

.oaqqe4bgw {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.2 17.2l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oqyz1-b1x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.862 16.287c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.ota_qabww {
  stop-color: var(--svg-color--fff1b2, #FFF1B2);
}

.ovub05bqx {
  d: path("M15.912 23.933a5.6 5.6 0 0 1-2.583-.612c-.255-.13-.53.158-.369.39a3.53 3.53 0 0 0 2.952 1.577a3.53 3.53 0 0 0 2.952-1.577c.161-.241-.113-.52-.369-.39a5.6 5.6 0 0 1-2.583.612");
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
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

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pyp_qyqhv {
  stop-color: var(--svg-color--e6b383, #E6B383);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.qcy-xjb9z {
  fill: var(--svg-color--000, #000);
  d: path("M12.794 17.6a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rgfkbzb4o {
  fill: var(--svg-color--202020, #202020);
  d: path("M9.553 12.774a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.027a4.14 4.14 0 0 0-2.586.53a3 3 0 0 0-.17.112l-.006.004a.517.517 0 0 1-.633-.818z");
}

.rz5bd0b6s {
  stop-color: var(--svg-color--f1b78d, #F1B78D);
  stop-opacity: 0;
}

.s-wuddcax {
  stop-color: var(--svg-color--d69b78, #D69B78);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t51tzvbuk {
  stop-color: var(--svg-color--d9988c, #D9988C);
}

.t52ha8bdg {
  stop-color: var(--svg-color--fed69f, #FED69F);
  stop-opacity: 0;
}

.t8rz6-b4j {
  d: path("M19.985 15.935a1.664 1.664 0 0 1 1.603 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.672-1.664");
}

.twinuccla {
  stop-color: var(--svg-color--cc9571, #CC9571);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u_8o32b5j {
  d: path("M6.849 20.863a3.06 3.06 0 0 1-1.687-.575v1.736c0 1.665.992 3.148 2.5 3.764a7.6 7.6 0 0 1-.644-2.2z");
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vg4ncn-3a {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.552 13.21c-.48-.344-1.674-.949-3.086-.711");
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

.vkgn28s3c {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.623 13.296c.48-.344 1.674-.949 3.086-.711");
}

.vsbibr_ed {
  stop-color: var(--svg-color--ffffc5, #FFFFC5);
}

.w-6a5tbqx {
  stop-color: var(--svg-color--f0c297, #F0C297);
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w5r4ae2jv {
  stop-color: var(--svg-color--eab68a, #EAB68A);
  stop-opacity: 0;
}

.wagfjcb7l {
  d: path("M21.467 17.38a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.426z");
}

.wti4q6bgh {
  cx: 11.338px;
  cy: 16.646px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.wuchx3byb {
  stop-color: var(--svg-color--fff1b2, #FFF1B2);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x08-9gb4f {
  d: path("M25.089 21.033q.186-2.975.344-5.95a3 3 0 0 1-.344 5.95");
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.y7-q8z4gm {
  stop-color: var(--svg-color--e0ca93, #E0CA93);
  stop-opacity: 0;
}

.ynmqlsboi {
  stop-color: var(--svg-color--e6b386, #E6B386);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zmahyob7y {
  stop-color: var(--svg-color--ffffc5, #FFFFC5);
  stop-opacity: 0;
}

.znj7aitbq {
  d: path("M6.917 23.688a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35c.22-3.512.441-7.01.605-10.52c-.02-1.43-1.148-2.61-2.572-2.67h-2.61a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3c0 3.47.217 6.882.445 10.36");
}

.zumy-vz5s {
  d: path("M11.84 15.935a1.664 1.664 0 0 0-1.603 2.103h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
