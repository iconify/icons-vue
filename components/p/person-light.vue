<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i7NTObX)" class="be6rpdeaj"/><path fill="url(#i3q6QBd)" class="u_8o32b5j"/><g filter="url(#iddyNYY)"><path fill="url(#irEM1ld)" class="znj7aitbq"/></g><path fill="url(#iESnEJb)" class="znj7aitbq"/><path fill="url(#iEXVr7d)" class="znj7aitbq"/><path fill="url(#izcfQjy)" class="znj7aitbq"/><path fill="url(#ifH2g4z)" class="znj7aitbq"/><path fill="url(#ieqxIVP)" class="znj7aitbq"/><path fill="url(#idPltuR)" class="znj7aitbq"/><path fill="url(#isYKm6c)" class="znj7aitbq"/><g filter="url(#iwCUzae)"><path class="tyimv5b5l"/></g><g filter="url(#iwgQaAe)"><path class="mv8tp37iq"/><path fill="url(#isUIyqd)" class="oyvbqu0mt"/><path fill="url(#ituzCMb)" class="oyvbqu0mt"/><path fill="url(#i8Gge7d)" class="oyvbqu0mt"/><path fill="url(#iRrTWlb)" class="oyvbqu0mt"/><path fill="url(#iP32hHd)" class="oyvbqu0mt"/></g><g filter="url(#iPhMk3c)"><path stroke="url(#izasfFe)" class="vhy08-bop"/></g><path fill="url(#ipiXh3d)" class="mlzz411wz"/><g filter="url(#i4wWGCc)"><path fill="url(#ib6CilY)" class="pjk2z4bnh"/><path fill="url(#iixUzje)" class="pjk2z4bnh"/><path fill="url(#iO2dryc)" class="pjk2z4bnh"/><path fill="url(#iso1DTc)" class="pjk2z4bnh"/><path fill="url(#iQ2SSOd)" class="pjk2z4bnh"/></g><g filter="url(#izGXtpd)"><path class="rh5-uimdk"/></g><g filter="url(#i5vag8d)"><path class="rgfkbzb4o"/></g><g filter="url(#iHBmf3b)"><path class="u9hm2nbbi"/><path fill="url(#iLVes6d)" class="nm9wxtyyu"/><path fill="url(#iFTqWjc)" class="nm9wxtyyu"/></g><g filter="url(#iwCvowe)"><path class="vro0yb0to"/><path fill="url(#iUvxmdd)" class="pkja9bbsb"/><path fill="url(#i0qoNxd)" class="pkja9bbsb"/><path fill="url(#itgMI1d)" class="pkja9bbsb"/></g><path class="irwnsrbdy"/><path fill="url(#i7VoyFd)" class="t8rz6-b4j"/><path class="au9gygbbx"/><g filter="url(#ijAPjme)"><path class="oqyz1-b1x"/><path fill="url(#iFJoSpc)" class="jhr6jzbby"/></g><g filter="url(#is2ugLe)"><path fill="url(#i4ebNXO)" class="wagfjcb7l"/></g><path class="ae8styofm"/><path fill="url(#ibp6VUb)" class="rr7m3ibhc"/><path class="qcy-xjb9z"/><g filter="url(#ivxx3re)"><path fill="url(#ilLt4wb)" class="kf_7dpbrd"/></g><g filter="url(#ibv0Oeb)"><ellipse transform="rotate(-27.914 11.338 16.646)" class="wti4q6bgh"/><ellipse fill="url(#in65Ppd)" transform="rotate(-27.914 11.338 16.646)" class="vhqb4xrsh"/></g><path fill="url(#i7MK3Qb)" class="x08-9gb4f"/><path fill="url(#i45AkAc)" class="x08-9gb4f"/><path fill="url(#i79ULed)" class="x08-9gb4f"/><path fill="url(#iC6AeUc)" class="x08-9gb4f"/><path fill="url(#iPfC5oc)" class="c09vwg1jl"/><path fill="url(#iXwoMWd)" class="c09vwg1jl"/><g filter="url(#i60jpNb)"><path fill="url(#izixeVc)" class="fmz6o5bzy"/></g><g filter="url(#ijF4nfu)"><path fill="url(#iAz59Jc)" class="b40ohmbqb"/></g><g filter="url(#ixjQZed)"><path class="vkgn28s3c"/></g><g filter="url(#ibaRkBw)"><path class="vg4ncn-3a"/></g><defs><radialGradient id="i7NTObX" cx="0" cy="0" r="1" gradientTransform="matrix(1.39603 3.76525 -4.47282 1.65837 24.775 20.288)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="i3q6QBd" cx="0" cy="0" r="1" gradientTransform="matrix(2.75273 .86514 -2.66903 8.49237 4.62 21.202)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="irEM1ld" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.147 18.533)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iEXVr7d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86098 23.80477 -19.71315 -1.5411 18.86 7.508)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="lut-i8bzq"/><stop offset="1" class="cz7k6-b_c"/></radialGradient><radialGradient id="izcfQjy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.141 2.64949 0 20.475 16.085)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="ifH2g4z" cx="0" cy="0" r="1" gradientTransform="matrix(.00733 -2.04019 2.2202 .00797 11.624 16.172)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="ieqxIVP" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.835 10.54)scale(15.8715 40.5438)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="idPltuR" cx="0" cy="0" r="1" gradientTransform="matrix(5.77672 -6.1111 2.2371 2.11469 5.719 10.469)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="isYKm6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24997 5.37502 -4.43752 -2.68312 20.438 9.25)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="ituzCMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4551 -1.43034 0 16.782 21.07)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iRrTWlb" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.315 11.86)scale(3.11992 5.01397)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="ipiXh3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 15.912 25.132)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iixUzje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.52791 16.5083 0 6.162 13.14)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iO2dryc" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 20.64 -5.275)scale(4.68924 8.30841)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iso1DTc" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 12.365 -1.587)scale(5.26377 3.86388)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iQ2SSOd" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 2.75 -6.36771 3.90746 14.225 .913)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iLVes6d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10381 0 0 -1.52308 16.385 5.125)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iFTqWjc" cx="0" cy="0" r="1" gradientTransform="matrix(6 -9.5 10.52499 6.64735 5.787 12.475)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iUvxmdd" cx="0" cy="0" r="1" gradientTransform="matrix(5.70209 0 0 2.22942 22.277 6.573)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="i0qoNxd" cx="0" cy="0" r="1" gradientTransform="rotate(-43.614 25.702 -19.903)scale(6.89811 12.6287)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="itgMI1d" cx="0" cy="0" r="1" gradientTransform="matrix(6.056 .70788 -.29638 2.53554 19.172 9.484)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i7VoyFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.98 16.825)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iFJoSpc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.936 3.702)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibp6VUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.844 16.825)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="in65Ppd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.138 3.05)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i45AkAc" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.15 24.594)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="i79ULed" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.194 17.866)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iC6AeUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0944 -2.89062 3.86227 1.46228 25.406 18.188)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iXwoMWd" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 3.923 8.82)scale(3.02997 3.25254)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="izixeVc" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.606 9.313)scale(1.73369 2.12732)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><filter id="iddyNYY" width="20.055" height="23.21" x="6.472" y="7.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2033"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2033" result="effect2_innerShadow_3930_2033"/></filter><filter id="iwCUzae" width="5.257" height="7.407" x="13.019" y="15.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".5"/></filter><filter id="iwgQaAe" width="3.9" height="5.807" x="13.962" y="16.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".1"/></filter><filter id="iPhMk3c" width="6.5" height="2.5" x="12.662" y="23.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".05"/></filter><filter id="i4wWGCc" width="24" height="15.148" x="3.912" y="1.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2033"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2033" result="effect2_innerShadow_3930_2033"/></filter><filter id="izGXtpd" width="4.274" height="2.047" x="18.875" y="11.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2033"/></filter><filter id="i5vag8d" width="4.274" height="2.019" x="9.075" y="11.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2033"/></filter><filter id="iHBmf3b" width="12.344" height="11.239" x="4.541" y="3.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2033"/><feGaussianBlur result="effect2_foregroundBlur_3930_2033" stdDeviation=".25"/></filter><filter id="iwCvowe" width="12.094" height="10.965" x="15.417" y="3.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".25"/></filter><filter id="ijAPjme" width="1.294" height="1.125" x="18.698" y="16.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".05"/></filter><filter id="is2ugLe" width="1.316" height="1.357" x="20.351" y="16.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".1"/></filter><filter id="ivxx3re" width="1.493" height="1.594" x="12.068" y="16.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".1"/></filter><filter id="ibv0Oeb" width="1.529" height="1.141" x="10.574" y="16.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".05"/></filter><filter id="i60jpNb" width="2.045" height="4.004" x="4.791" y="16.049" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".125"/></filter><filter id="ijF4nfu" width="2.765" height="4.549" x="24.745" y="15.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".25"/></filter><filter id="ixjQZed" width="3.836" height="1.515" x="9.248" y="12.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".125"/></filter><filter id="ibaRkBw" width="3.836" height="1.515" x="19.091" y="12.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2033" stdDeviation=".125"/></filter><linearGradient id="iESnEJb" x1="25.527" x2="17.412" y1="21.675" y2="21.675" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="isUIyqd" x1="17.475" x2="15.912" y1="19.791" y2="19.856" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="i8Gge7d" x1="15.912" x2="15.912" y1="21.915" y2="21.048" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iP32hHd" x1="15.912" x2="15.912" y1="16.631" y2="17.891" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="izasfFe" x1="13.672" x2="14.266" y1="24.844" y2="23.288" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="ib6CilY" x1="28.687" x2="7.037" y1="7.975" y2="7.975" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="i4ebNXO" x1="21.431" x2="20.846" y1="16.925" y2="17.286" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilLt4wb" x1="13.231" x2="12.646" y1="16.925" y2="17.286" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7MK3Qb" x1="27.912" x2="25.662" y1="16.975" y2="21.033" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iPfC5oc" x1="5.006" x2="7.725" y1="18.288" y2="18.05" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iAz59Jc" x1="26.128" x2="26.128" y1="16.284" y2="19.832" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.ae8styofm {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.455 15.429c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.au9gygbbx {
  fill: var(--svg-color--000, #000);
  d: path("M19.032 17.6a.95.95 0 0 1 .953-.954c.529 0 .952.424.952.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b40ohmbqb {
  d: path("M25.245 19.832q.109-1.774.207-3.548a1.781 1.781 0 0 1-.207 3.548");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.be6rpdeaj {
  d: path("M24.976 20.863a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c09vwg1jl {
  d: path("M6.508 15.066c-1.457.206-2.596 1.458-2.596 2.972a3 3 0 0 0 2.836 2.996c-.12-1.993-.202-3.975-.24-5.968");
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cz7k6-b_c {
  stop-color: var(--svg-color--b57997, #B57997);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fmz6o5bzy {
  d: path("M6.431 16.299a1.782 1.782 0 0 0 .156 3.503c-.065-1.168-.12-2.335-.156-3.503");
}

.ft5dv1b6b {
  fill: none;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.irwnsrbdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.37 15.429c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jhr6jzbby {
  d: path("M19.862 16.287c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kf_7dpbrd {
  d: path("M13.36 17.404c0-.538-.437-.896-.555-1.005l-.537.52l.33.674z");
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lut-i8bzq {
  stop-color: var(--svg-color--b57997, #B57997);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mlzz411wz {
  d: path("M15.912 23.933a5.6 5.6 0 0 1-2.583-.612c-.255-.13-.53.158-.369.39a3.53 3.53 0 0 0 2.952 1.577a3.53 3.53 0 0 0 2.952-1.577c.161-.242-.113-.52-.369-.39a5.6 5.6 0 0 1-2.583.612");
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mv8tp37iq {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.2 17.2l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.427c-.213-.76-1.204-.76-1.426 0");
}

.nm9wxtyyu {
  d: path("M16.346 8.063a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.181.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oqyz1-b1x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.862 16.287c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oyvbqu0mt {
  d: path("m15.2 17.2l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.427c-.213-.76-1.204-.76-1.426 0");
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

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qcy-xjb9z {
  fill: var(--svg-color--000, #000);
  d: path("M12.794 17.6a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rgfkbzb4o {
  fill: var(--svg-color--202020, #202020);
  d: path("M9.553 12.774a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.027a4.14 4.14 0 0 0-2.586.53a3 3 0 0 0-.17.112l-.006.004a.517.517 0 0 1-.633-.818z");
}

.rh5-uimdk {
  fill: var(--svg-color--202020, #202020);
  d: path("M22.872 12.978c-.327-.285-.706-.586-1.282-.768c-.567-.178-1.277-.226-2.26-.106a.517.517 0 0 0 .125 1.027c.897-.11 1.447-.053 1.825.066c.37.116.62.305.913.56a.517.517 0 1 0 .679-.78");
}

.rr7m3ibhc {
  d: path("M11.84 15.935a1.664 1.664 0 0 0-1.603 2.103h3.214q.059-.214.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t8rz6-b4j {
  d: path("M19.985 15.935a1.664 1.664 0 0 1 1.603 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.672-1.664");
}

.tyimv5b5l {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.164 17.556l-1.101 3.427c-.189.706.263 1.41.903 1.41h1.364c.64 0 1.091-.715.903-1.41l-.922-3.427c-.198-.76-.94-.76-1.147 0");
}

.u_8o32b5j {
  d: path("M6.849 20.863a3.06 3.06 0 0 1-1.687-.575v1.736c0 1.665.992 3.148 2.5 3.764a7.6 7.6 0 0 1-.644-2.2z");
}

.u9hm2nbbi {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M16.346 8.063a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.181.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.vg4ncn-3a {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.552 13.21c-.48-.344-1.674-.949-3.086-.711");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
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

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vro0yb0to {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m25.63 14.154l-.053-1.177c-.02-1.424-1.197-2.598-2.62-2.658h-2.611a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.587c2.066.274 4.934.919 6.905 2.204c3.252 2.122 2.683 5.945.97 7.746");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wagfjcb7l {
  d: path("M21.467 17.38a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.426z");
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wti4q6bgh {
  cx: 11.338px;
  cy: 16.646px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x08-9gb4f {
  d: path("M25.089 21.033q.186-2.975.344-5.95a3 3 0 0 1-.344 5.95");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.znj7aitbq {
  d: path("M6.917 23.688a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35c.22-3.512.441-7.01.605-10.52c-.02-1.43-1.148-2.61-2.572-2.67h-2.61a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3c0 3.47.217 6.882.445 10.36");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
