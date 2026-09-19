<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIoAMJe)" class="r3ywl8pyd"/><path fill="url(#ifimi3b)" class="r3ywl8pyd"/><path fill="url(#iWwl0sc)" class="cnd2itcca"/><path fill="url(#inM7Njc)" class="cnd2itcca"/><g filter="url(#igXZzie)"><path fill="url(#i44jddc)" class="cqzkekh-d"/></g><path fill="url(#imdgbwe)" class="cqzkekh-d"/><path fill="url(#invZS6b)" class="cqzkekh-d"/><path fill="url(#ipjNFJd)" class="cqzkekh-d"/><path fill="url(#ixUjVab)" class="cqzkekh-d"/><path fill="url(#ijYKPUc)" class="cqzkekh-d"/><path fill="url(#iDMQUxd)" class="cqzkekh-d"/><path fill="url(#iqP8IMB)" class="cqzkekh-d"/><path fill="url(#iQvcIVS)" class="cqzkekh-d"/><g filter="url(#i6SFULd)"><path class="kdp9uubpu"/></g><g filter="url(#iuHejIc)"><path class="mo8cd_bxk"/><path fill="url(#i37Ds4b)" class="uw932mb8u"/><path fill="url(#iqfH1Td)" class="uw932mb8u"/><path fill="url(#iF0Jqpc)" class="uw932mb8u"/><path fill="url(#i3GNcib)" class="uw932mb8u"/><path fill="url(#iTnbRsb)" class="uw932mb8u"/></g><g filter="url(#ireF2lb)"><path stroke="url(#i65Un8b)" class="igekverse"/></g><path fill="url(#i83hIHb)" class="ec80sooem"/><g filter="url(#ipfOqkb)"><path fill="url(#igtwQhc)" class="v2jqeg7xe"/><path fill="url(#i1yYH6b)" class="v2jqeg7xe"/><path fill="url(#iyMAAHc)" class="v2jqeg7xe"/><path fill="url(#iapc6kc)" class="v2jqeg7xe"/><path fill="url(#i0v2nkc)" class="v2jqeg7xe"/><path fill="url(#inNaIeX)" class="v2jqeg7xe"/></g><g filter="url(#iHowN8L)"><path class="o7a5dbcfj"/></g><g filter="url(#iJOpHwb)"><path class="hkcqjjbbp"/></g><g filter="url(#iLSL6nd)"><path fill="url(#iRaPqBb)" class="b27i4cbjy"/><path fill="url(#i28NZHd)" class="b27i4cbjy"/></g><g filter="url(#iKlS5Fc)"><path fill="url(#iZLQ4fb)" class="rpazyibjp"/><path fill="url(#i5KwUBc)" class="rpazyibjp"/><path fill="url(#iJNruve)" class="rpazyibjp"/><path fill="url(#inwxC0d)" class="rpazyibjp"/><path fill="url(#iDhQ3CY)" class="rpazyibjp"/></g><path class="qcopzc5iw"/><path fill="url(#iaLBOcb)" class="na4dsyf3s"/><path class="y-_sqsq4r"/><g filter="url(#iRHeige)"><path class="mxgfotkxz"/><path fill="url(#i8DK2Uc)" class="s2u076rko"/></g><g filter="url(#izDgOqd)"><path fill="url(#iRP5WEb)" class="ig2pmop4j"/></g><path class="yp6ym3btc"/><path fill="url(#iYax22d)" class="q9ri5sbne"/><path class="sydu3xpbt"/><g filter="url(#iioRoNd)"><path fill="url(#irybZNd)" class="nadebokqo"/></g><g filter="url(#iGY8Igb)"><ellipse transform="rotate(-27.914 11.338 17.146)" class="jdxch_b6r"/><ellipse fill="url(#ibSnHld)" transform="rotate(-27.914 11.338 17.146)" class="tlv48hbvs"/></g><path fill="url(#iyXOnGb)" class="hftodlqzp"/><path fill="url(#iZwwTqT)" class="hftodlqzp"/><path fill="url(#iBM7W1c)" class="hftodlqzp"/><path fill="url(#iPOJgde)" class="hftodlqzp"/><path fill="url(#iOMKPKc)" class="quo27y7dg"/><path fill="url(#iwhhxMc)" class="quo27y7dg"/><g filter="url(#ioF9KbX)"><path fill="url(#iZ3GWCe)" class="o66_14b5c"/></g><g filter="url(#iVcjIPG)"><path fill="url(#iScGwDi)" class="mumw7ng_v"/></g><g filter="url(#iLJ72Ld)"><path class="s4pre3b9d"/></g><g filter="url(#ihqIsNc)"><path class="eat4debxo"/></g><defs><radialGradient id="iIoAMJe" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 4.96 20.71)scale(6.07867 7.22099)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="y-cveupjc"/><stop offset="1" class="bc6pupb0c"/></radialGradient><radialGradient id="ifimi3b" cx="0" cy="0" r="1" gradientTransform="matrix(.54688 .75 -.63714 .46458 24.866 21.288)" gradientUnits="userSpaceOnUse"><stop class="ygff5vfwh"/><stop offset="1" class="m2-9pwbbm"/></radialGradient><radialGradient id="iWwl0sc" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 5 -2.27273 1.07954 5.569 21.007)" gradientUnits="userSpaceOnUse"><stop class="x08e984jt"/><stop offset="1" class="gyp47d6zd"/></radialGradient><radialGradient id="inM7Njc" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 1.85937 -1.63106 .52084 6.803 20.991)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="jg96q12xv"/><stop offset="1" class="yq5y_ab2t"/></radialGradient><radialGradient id="i44jddc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.147 19.033)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="invZS6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90593 23.16252 -19.18137 -1.57834 18.86 8.008)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="ipjNFJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.141 2.64949 0 20.475 16.585)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="ixUjVab" cx="0" cy="0" r="1" gradientTransform="matrix(.00733 -2.04019 2.2202 .00797 11.624 16.672)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="ijYKPUc" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.827 10.79)scale(15.8715 40.5438)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iDMQUxd" cx="0" cy="0" r="1" gradientTransform="matrix(7.59374 -4.9375 1.80748 2.77985 5.719 10.969)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iqP8IMB" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 4.65625 -1.8613 -.17489 26.25 13.594)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iQvcIVS" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24997 5.37502 -4.43752 -2.68312 20.438 9.75)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iqfH1Td" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4551 -1.43034 0 16.782 21.57)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="i3GNcib" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.26 12.11)scale(3.11992 5.01397)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i83hIHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 15.912 25.632)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="i1yYH6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.162 16.083)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="gxt6tevqz"/><stop offset="1" class="eznm9_btg"/></radialGradient><radialGradient id="iyMAAHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 24.975 16.083)" gradientUnits="userSpaceOnUse"><stop class="yat4_qblk"/><stop offset="1" class="dhu3d4t5g"/></radialGradient><radialGradient id="iapc6kc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 12.188 .02)scale(6.48857 3.45559)" gradientUnits="userSpaceOnUse"><stop class="ud522stie"/><stop offset="1" class="dmat9gbaw"/></radialGradient><radialGradient id="i0v2nkc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 2.625 -6.38151 7.90093 8.725 3.87)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="rex51obcx"/><stop offset="1" class="fxz6o0b4v"/></radialGradient><radialGradient id="inNaIeX" cx="0" cy="0" r="1" gradientTransform="rotate(-128.047 5.473 3.097)scale(2.24211 4.11492)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="pwzky5y2s"/><stop offset="1" class="ne8r-1b8h"/></radialGradient><radialGradient id="iRaPqBb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.13156 2.93075 -.8157 -2.2632 16.385 4.102)" gradientUnits="userSpaceOnUse"><stop class="cjw5wkr6j"/><stop offset="1" class="c2gqogevh"/></radialGradient><radialGradient id="i28NZHd" cx="0" cy="0" r="1" gradientTransform="rotate(-58.775 14.942 1.86)scale(11.9254 13.2121)" gradientUnits="userSpaceOnUse"><stop class="www4chwuy"/><stop offset=".233" class="a408_iblx"/><stop offset="1" class="vfbc23b7l"/></radialGradient><radialGradient id="iZLQ4fb" cx="0" cy="0" r="1" gradientTransform="matrix(6.3125 1.49307 -.7558 3.1954 22.662 6.069)" gradientUnits="userSpaceOnUse"><stop class="i461t-b7g"/><stop offset="1" class="y_60f3smc"/></radialGradient><radialGradient id="i5KwUBc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.957 -.01)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="o53euhbvm"/><stop offset="1" class="hzkxetqij"/></radialGradient><radialGradient id="iJNruve" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.319 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="sw48khtja"/><stop offset="1" class="duvueybsu"/></radialGradient><radialGradient id="inwxC0d" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.079 4.395)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="cnvbc-41i"/><stop offset="1" class="s2wf2et5i"/></radialGradient><radialGradient id="iDhQ3CY" cx="0" cy="0" r="1" gradientTransform="matrix(-.21876 .71543 -3.27084 -1.00012 22.35 5.618)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="bxevcpx9v"/><stop offset="1" class="hu-rubh3f"/></radialGradient><radialGradient id="iaLBOcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.98 17.325)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8DK2Uc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.059 3.952)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYax22d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.844 17.325)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibSnHld" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.384 3.3)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZwwTqT" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 .82 24.844)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iBM7W1c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.194 18.366)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iPOJgde" cx="0" cy="0" r="1" gradientTransform="matrix(1.0944 -2.89062 3.86227 1.46228 25.406 18.688)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iwhhxMc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -4.198 11.335)scale(3.94637 3.87964)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iZ3GWCe" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.585 9.563)scale(1.73369 .76465)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="igXZzie" width="20.055" height="23.21" x="6.472" y="7.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2260"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2260" result="effect2_innerShadow_3930_2260"/></filter><filter id="i6SFULd" width="5.257" height="7.407" x="13.019" y="16.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".5"/></filter><filter id="iuHejIc" width="3.9" height="5.807" x="13.962" y="16.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".1"/></filter><filter id="ireF2lb" width="6.5" height="2.5" x="12.662" y="23.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".05"/></filter><filter id="ipfOqkb" width="24" height="15.148" x="3.912" y="2.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2260"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.294118 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2260" result="effect2_innerShadow_3930_2260"/></filter><filter id="iHowN8L" width="4.274" height="2.047" x="18.875" y="12.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2260"/></filter><filter id="iJOpHwb" width="4.274" height="2.019" x="9.075" y="12.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2260"/></filter><filter id="iLSL6nd" width="12.344" height="11.239" x="4.541" y="3.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".25"/></filter><filter id="iKlS5Fc" width="12.094" height="10.965" x="15.417" y="4.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".25"/></filter><filter id="iRHeige" width="1.294" height="1.125" x="18.698" y="16.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".05"/></filter><filter id="izDgOqd" width="1.316" height="1.357" x="20.351" y="16.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".1"/></filter><filter id="iioRoNd" width="1.493" height="1.594" x="12.068" y="16.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".1"/></filter><filter id="iGY8Igb" width="1.529" height="1.141" x="10.574" y="16.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".05"/></filter><filter id="ioF9KbX" width="2.045" height="4.004" x="4.791" y="16.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".125"/></filter><filter id="iVcjIPG" width="2.765" height="4.549" x="24.628" y="16.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".25"/></filter><filter id="iLJ72Ld" width="3.836" height="1.515" x="9.248" y="12.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".125"/></filter><filter id="ihqIsNc" width="3.836" height="1.515" x="19.091" y="12.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2260" stdDeviation=".125"/></filter><linearGradient id="imdgbwe" x1="25.527" x2="17.412" y1="22.175" y2="22.175" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="i37Ds4b" x1="17.475" x2="15.912" y1="20.291" y2="20.356" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iF0Jqpc" x1="15.912" x2="15.912" y1="22.415" y2="21.548" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iTnbRsb" x1="15.912" x2="15.912" y1="16.906" y2="18.391" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="i65Un8b" x1="13.672" x2="14.266" y1="25.344" y2="23.788" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="igtwQhc" x1="25.912" x2="7.037" y1="8.475" y2="8.475" gradientUnits="userSpaceOnUse"><stop class="rdywzssnj"/><stop offset="1" class="r434h8bwv"/></linearGradient><linearGradient id="iRP5WEb" x1="21.431" x2="20.846" y1="17.425" y2="17.786" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irybZNd" x1="13.231" x2="12.646" y1="17.425" y2="17.785" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyXOnGb" x1="27.912" x2="25.662" y1="17.475" y2="21.533" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iOMKPKc" x1="5.006" x2="7.725" y1="18.788" y2="18.55" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iScGwDi" x1="26.011" x2="26.011" y1="16.764" y2="20.312" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-red-hair-dark" /></template>
<style>
.a408_iblx {
  stop-color: var(--svg-color--cc5249, #CC5249);
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
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

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b27i4cbjy {
  d: path("M16.346 8.563a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.182.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc6pupb0c {
  stop-color: var(--svg-color--c15961, #C15961);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bxevcpx9v {
  stop-color: var(--svg-color--db815c, #DB815C);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c2gqogevh {
  stop-color: var(--svg-color--e56f39, #E56F39);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.cjw5wkr6j {
  stop-color: var(--svg-color--e56f39, #E56F39);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnd2itcca {
  d: path("M6.849 21.363a3.06 3.06 0 0 1-1.687-.575v1.736c0 1.665.992 3.148 2.5 3.764a7.6 7.6 0 0 1-.644-2.2z");
}

.cnvbc-41i {
  stop-color: var(--svg-color--cc5425, #CC5425);
  stop-opacity: 0;
}

.cqzkekh-d {
  d: path("M6.917 24.188a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35c.22-3.512.441-7.01.605-10.52c-.02-1.43-1.148-2.61-2.572-2.67h-2.61a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3c0 3.47.217 6.882.445 10.36");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dhu3d4t5g {
  stop-color: var(--svg-color--d6805e, #D6805E);
  stop-opacity: 0;
}

.dmat9gbaw {
  stop-color: var(--svg-color--e09171, #E09171);
  stop-opacity: 0;
}

.duvueybsu {
  stop-color: var(--svg-color--ca5743, #CA5743);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eat4debxo {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.552 13.71c-.48-.344-1.674-.949-3.086-.711");
}

.ec80sooem {
  d: path("M15.912 24.433a5.6 5.6 0 0 1-2.583-.612c-.255-.13-.53.158-.369.39a3.53 3.53 0 0 0 2.952 1.577a3.53 3.53 0 0 0 2.952-1.577c.161-.242-.113-.52-.369-.39a5.6 5.6 0 0 1-2.583.612");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.eznm9_btg {
  stop-color: var(--svg-color--ae6456, #AE6456);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxz6o0b4v {
  stop-color: var(--svg-color--ba7461, #BA7461);
  stop-opacity: 0;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gxt6tevqz {
  stop-color: var(--svg-color--ae6456, #AE6456);
}

.gyp47d6zd {
  stop-color: var(--svg-color--b0495c, #B0495C);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.hftodlqzp {
  d: path("M25.089 21.533q.186-2.975.344-5.95a3 3 0 0 1-.344 5.95");
}

.hkcqjjbbp {
  fill: var(--svg-color--202020, #202020);
  d: path("M9.553 13.274a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.027a4.14 4.14 0 0 0-2.586.53a3 3 0 0 0-.17.112l-.006.004a.517.517 0 0 1-.633-.818z");
}

.hu-rubh3f {
  stop-color: var(--svg-color--db815c, #DB815C);
  stop-opacity: 0;
}

.hzkxetqij {
  stop-color: var(--svg-color--ce5d46, #CE5D46);
  stop-opacity: 0;
}

.i461t-b7g {
  stop-color: var(--svg-color--fb865c, #FB865C);
}

.ig2pmop4j {
  d: path("M21.467 17.88a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.426z");
}

.igekverse {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.364 23.754a.36.36 0 0 0-.43.074a.33.33 0 0 0-.036.425a3.6 3.6 0 0 0 3.014 1.61a3.6 3.6 0 0 0 3.015-1.611a.334.334 0 0 0-.037-.427a.36.36 0 0 0-.428-.07h-.001a5.5 5.5 0 0 1-2.549.603c-.934 0-1.812-.22-2.548-.604Z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.jdxch_b6r {
  cx: 11.338px;
  cy: 17.146px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.jg96q12xv {
  stop-color: var(--svg-color--a84a33, #A84A33);
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kdp9uubpu {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.164 18.066l-1.101 3.427c-.189.705.263 1.41.903 1.41h1.364c.64 0 1.091-.716.903-1.41l-.922-3.427c-.198-.76-.94-.76-1.147 0");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m2-9pwbbm {
  stop-color: var(--svg-color--c96949, #C96949);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mo8cd_bxk {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.2 17.7l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.mumw7ng_v {
  d: path("M25.128 20.312q.109-1.774.206-3.549a1.782 1.782 0 0 1-.206 3.55");
}

.mxgfotkxz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.862 16.787c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.na4dsyf3s {
  d: path("M19.985 16.435a1.664 1.664 0 0 1 1.603 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.672-1.664");
}

.nadebokqo {
  d: path("M13.36 17.904c0-.538-.437-.896-.555-1.005l-.537.52l.33.674z");
}

.ne8r-1b8h {
  stop-color: var(--svg-color--bc7a6a, #BC7A6A);
  stop-opacity: 0;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o53euhbvm {
  stop-color: var(--svg-color--ce5d46, #CE5D46);
}

.o66_14b5c {
  d: path("M6.431 16.799a1.782 1.782 0 0 0 .156 3.503c-.065-1.168-.12-2.335-.156-3.503");
}

.o7a5dbcfj {
  fill: var(--svg-color--202020, #202020);
  d: path("M22.872 13.478c-.327-.285-.706-.586-1.282-.768c-.567-.178-1.277-.226-2.26-.106a.517.517 0 0 0 .125 1.027c.897-.11 1.447-.053 1.825.066c.37.116.62.305.913.56a.517.517 0 0 0 .679-.78");
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
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

.pwzky5y2s {
  stop-color: var(--svg-color--bc7a6a, #BC7A6A);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q9ri5sbne {
  d: path("M11.84 16.435a1.664 1.664 0 0 0-1.603 2.103h3.214q.059-.214.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.qcopzc5iw {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.37 15.929c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.quo27y7dg {
  d: path("M6.49 15.567a3 3 0 0 0 .258 5.966c-.12-1.992-.22-3.973-.258-5.966");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3ywl8pyd {
  d: path("M24.976 21.363a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.r434h8bwv {
  stop-color: var(--svg-color--b4644a, #B4644A);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rdywzssnj {
  stop-color: var(--svg-color--ea8759, #EA8759);
}

.rex51obcx {
  stop-color: var(--svg-color--ba7461, #BA7461);
}

.rpazyibjp {
  d: path("m25.63 14.654l-.053-1.177c-.02-1.424-1.197-2.598-2.62-2.658h-2.611a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.587c2.066.274 4.934.919 6.905 2.204c3.252 2.122 2.683 5.945.97 7.746");
}

.s2u076rko {
  d: path("M19.862 16.787c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.s2wf2et5i {
  stop-color: var(--svg-color--cc5425, #CC5425);
}

.s4pre3b9d {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.623 13.796c.48-.344 1.674-.949 3.086-.711");
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sw48khtja {
  stop-color: var(--svg-color--ca5743, #CA5743);
}

.sydu3xpbt {
  fill: var(--svg-color--000, #000);
  d: path("M12.794 18.1a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.tlv48hbvs {
  cx: 11.338px;
  cy: 17.146px;
  rx: 0.726px;
  ry: 0.368px;
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.ud522stie {
  stop-color: var(--svg-color--e09171, #E09171);
}

.uw932mb8u {
  d: path("m15.2 17.7l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.v2jqeg7xe {
  d: path("M24.964 6.648c.959.33 1.82 1 2.363 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.504 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.146-2.995c-.02-1.43-1.147-2.61-2.57-2.67h-2.611a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3l.058 2.866c-.474.07-.969.228-1.343.492v-2.238c0-.58-.178-1.15-.504-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.422-2.1a5 5 0 0 0 2.581-2.07a4.34 4.34 0 0 1 3.679-2.05c.603 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.701-.35c1.572 0 2.947.85 3.708 2.11c.574.95 1.474 1.64 2.522 2");
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vfbc23b7l {
  stop-color: var(--svg-color--cc5249, #CC5249);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.www4chwuy {
  stop-color: var(--svg-color--b0463c, #B0463C);
}

.x08e984jt {
  stop-color: var(--svg-color--b56a57, #B56A57);
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

.y_60f3smc {
  stop-color: var(--svg-color--fb865c, #FB865C);
  stop-opacity: 0;
}

.y-_sqsq4r {
  fill: var(--svg-color--000, #000);
  d: path("M19.032 18.1a.95.95 0 0 1 .953-.954c.529 0 .952.424.952.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.y-cveupjc {
  stop-color: var(--svg-color--e18055, #E18055);
}

.yat4_qblk {
  stop-color: var(--svg-color--d6805e, #D6805E);
}

.ygff5vfwh {
  stop-color: var(--svg-color--c96949, #C96949);
}

.yp6ym3btc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.455 15.929a2.6 2.6 0 0 0-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.yq5y_ab2t {
  stop-color: var(--svg-color--a84a33, #A84A33);
  stop-opacity: 0;
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
