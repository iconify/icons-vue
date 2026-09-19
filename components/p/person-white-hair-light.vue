<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iztqLFd)" class="r3ywl8pyd"/><path fill="url(#ifOz7Kc)" class="r3ywl8pyd"/><path fill="url(#iKyjErd)" class="cnd2itcca"/><g filter="url(#iV30Mhv)"><path fill="url(#iECsTtb)" class="wofq4huja"/></g><path fill="url(#ijJe9Jd)" class="wofq4huja"/><path fill="url(#i6zJPSd)" class="wofq4huja"/><path fill="url(#ixKBBce)" class="wofq4huja"/><path fill="url(#i1A7eWc)" class="wofq4huja"/><path fill="url(#igIyP6c)" class="wofq4huja"/><path fill="url(#iDSiyPb)" class="wofq4huja"/><path fill="url(#iKCQQvb)" class="wofq4huja"/><g filter="url(#iv4VkKc)"><path class="zpcu4rbnn"/></g><g filter="url(#izt1lTb)"><path class="c3xhj8b9v"/><path fill="url(#iAhi1Gd)" class="uw932mb8u"/><path fill="url(#isAxdLe)" class="uw932mb8u"/><path fill="url(#iwQsQ5b)" class="uw932mb8u"/><path fill="url(#iIExtYz)" class="uw932mb8u"/><path fill="url(#iwfI5tb)" class="uw932mb8u"/></g><g filter="url(#iJDpfeQ)"><path stroke="url(#iTG843t)" class="igekverse"/></g><path fill="url(#iyqv8re)" class="ec80sooem"/><g filter="url(#i91UmKb)"><path fill="url(#iYib8LL)" class="v2jqeg7xe"/><path fill="url(#ihSkAdd)" class="v2jqeg7xe"/><path fill="url(#ifZyn6c)" class="v2jqeg7xe"/><path fill="url(#icV02MT)" class="v2jqeg7xe"/><path fill="url(#i6CCFEW)" class="v2jqeg7xe"/></g><g filter="url(#iDyAnjd)"><path class="hkr2icc8q"/></g><g filter="url(#iuusXpe)"><path class="tkencrcug"/></g><g filter="url(#ic9UCVr)"><path fill="url(#iylgcLx)" class="b27i4cbjy"/><path fill="url(#iK0dubc)" class="b27i4cbjy"/></g><g filter="url(#iXDyTce)"><path fill="url(#iqYqFbb)" class="rpazyibjp"/><path fill="url(#iNS3XCc)" class="rpazyibjp"/><path fill="url(#ijhnyCd)" class="rpazyibjp"/><path fill="url(#i2BnyRd)" class="rpazyibjp"/><path fill="url(#iwh24Ge)" class="rpazyibjp"/></g><path class="qcopzc5iw"/><path fill="url(#iaLBOcb)" class="na4dsyf3s"/><path class="y-_sqsq4r"/><g filter="url(#iflGqkb)"><path class="mxgfotkxz"/><path fill="url(#i8DK2Uc)" class="s2u076rko"/></g><g filter="url(#iKSHWOt)"><path fill="url(#iRP5WEb)" class="ig2pmop4j"/></g><path class="yp6ym3btc"/><path fill="url(#iYax22d)" class="q9ri5sbne"/><path class="sydu3xpbt"/><g filter="url(#iorpZld)"><path fill="url(#irybZNd)" class="nadebokqo"/></g><g filter="url(#iwjg1oe)"><ellipse transform="rotate(-27.914 11.338 17.146)" class="jdxch_b6r"/><ellipse fill="url(#ibSnHld)" transform="rotate(-27.914 11.338 17.146)" class="tlv48hbvs"/></g><path fill="url(#ipzBX3T)" class="hftodlqzp"/><path fill="url(#i5Y9pqb)" class="hftodlqzp"/><path fill="url(#id0UpUB)" class="hftodlqzp"/><path fill="url(#iY71P7c)" class="hftodlqzp"/><path fill="url(#iQ5KyTc)" class="k2lt7acah"/><path fill="url(#i8qBUkc)" class="k2lt7acah"/><g filter="url(#iFbxXKb)"><path fill="url(#isQXZYK)" class="o66_14b5c"/></g><g filter="url(#ijnm7Yb)"><path fill="url(#iAfhQ6d)" class="h47i_9ryn"/></g><g filter="url(#iQDG6Tb)"><path class="zpjcwsbeh"/></g><g filter="url(#id00VHd)"><path class="ahhxrkbaj"/></g><defs><radialGradient id="iztqLFd" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 4.96 20.71)scale(6.07867 7.22099)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="beywhq7jp"/><stop offset="1" class="qd0vyqf9z"/></radialGradient><radialGradient id="ifOz7Kc" cx="0" cy="0" r="1" gradientTransform="matrix(.375 1.4375 -2.0036 .52268 25.216 21.185)" gradientUnits="userSpaceOnUse"><stop class="yuksi-0vv"/><stop offset="1" class="zox87yb_h"/></radialGradient><radialGradient id="iKyjErd" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 5 -2.27273 1.07954 5.569 21.007)" gradientUnits="userSpaceOnUse"><stop class="t-6p9njiq"/><stop offset="1" class="l7pebubmo"/></radialGradient><radialGradient id="iECsTtb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.147 19.033)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="i6zJPSd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86098 23.80477 -19.71315 -1.5411 18.86 8.008)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="lut-i8bzq"/><stop offset="1" class="cz7k6-b_c"/></radialGradient><radialGradient id="ixKBBce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.141 2.64949 0 20.475 16.585)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="i1A7eWc" cx="0" cy="0" r="1" gradientTransform="matrix(.00733 -2.04019 2.2202 .00797 11.624 16.672)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="igIyP6c" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.827 10.79)scale(15.8715 40.5438)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iDSiyPb" cx="0" cy="0" r="1" gradientTransform="matrix(5.77672 -6.1111 2.2371 2.11469 5.719 10.969)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="hw8svib4r"/><stop offset="1" class="dvwoo-blq"/></radialGradient><radialGradient id="iKCQQvb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24997 5.37502 -4.43752 -2.68312 20.438 9.75)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="isAxdLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4551 -1.43034 0 16.782 21.57)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iIExtYz" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.26 12.11)scale(3.11992 5.01397)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iyqv8re" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 15.912 25.632)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="ihSkAdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.162 16.083)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="xi587ab8p"/><stop offset="1" class="veen2hyde"/></radialGradient><radialGradient id="ifZyn6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 24.975 16.083)" gradientUnits="userSpaceOnUse"><stop class="shhwiqyyt"/><stop offset="1" class="xct-m9bex"/></radialGradient><radialGradient id="icV02MT" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 2.625 -6.38151 7.90093 8.725 3.87)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="urfrcsboi"/><stop offset="1" class="vi2pbcbzr"/></radialGradient><radialGradient id="i6CCFEW" cx="0" cy="0" r="1" gradientTransform="rotate(-128.047 5.473 3.097)scale(2.24211 4.11492)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="tlv177bnc"/><stop offset="1" class="aoa5c28ss"/></radialGradient><radialGradient id="iylgcLx" cx="0" cy="0" r="1" gradientTransform="matrix(-8.13156 2.93075 -.8157 -2.2632 16.385 4.102)" gradientUnits="userSpaceOnUse"><stop class="gdp977b3v"/><stop offset="1" class="g9yl07uss"/></radialGradient><radialGradient id="iK0dubc" cx="0" cy="0" r="1" gradientTransform="rotate(-58.775 14.942 1.86)scale(11.9254 13.2121)" gradientUnits="userSpaceOnUse"><stop class="tt4n8bcqq"/><stop offset=".233" class="cv1cs5blk"/><stop offset="1" class="fjj8rhbfs"/></radialGradient><radialGradient id="iqYqFbb" cx="0" cy="0" r="1" gradientTransform="matrix(7.11624 1.54509 -.95711 4.4082 22.663 6.069)" gradientUnits="userSpaceOnUse"><stop class="exw4y6u-y"/><stop offset="1" class="qhwcf43hj"/></radialGradient><radialGradient id="iNS3XCc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.957 -.01)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="i8ob3ybgw"/><stop offset="1" class="yxjccacgf"/></radialGradient><radialGradient id="ijhnyCd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.319 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="m-_vcfkqs"/><stop offset="1" class="dw544eozv"/></radialGradient><radialGradient id="i2BnyRd" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.079 4.395)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="p4gx43bmc"/><stop offset="1" class="dj4y9ccpa"/></radialGradient><radialGradient id="iwh24Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.46875 -8.70091 -2.03645 22.435 5.207)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="splxym76g"/><stop offset="1" class="eo39z7bsb"/></radialGradient><radialGradient id="iaLBOcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.98 17.325)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8DK2Uc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.059 3.952)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYax22d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.844 17.325)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibSnHld" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.384 3.3)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5Y9pqb" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 .82 24.844)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="id0UpUB" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.194 18.366)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iY71P7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.0944 -2.89062 3.86227 1.46228 25.406 18.688)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="i8qBUkc" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 3.938 9.07)scale(3.02997 3.25254)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="isQXZYK" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.585 9.563)scale(1.73369 2.12732)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><filter id="iV30Mhv" width="20.055" height="23.21" x="6.472" y="7.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2317"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2317" result="effect2_innerShadow_3930_2317"/></filter><filter id="iv4VkKc" width="5.257" height="7.407" x="13.019" y="16.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".5"/></filter><filter id="izt1lTb" width="3.9" height="5.807" x="13.962" y="16.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".1"/></filter><filter id="iJDpfeQ" width="6.5" height="2.5" x="12.662" y="23.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".05"/></filter><filter id="i91UmKb" width="24" height="15.148" x="3.912" y="2.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.670588 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2317"/></filter><filter id="iDyAnjd" width="4.274" height="2.047" x="18.875" y="12.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.6 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2317"/></filter><filter id="iuusXpe" width="4.274" height="2.019" x="9.075" y="12.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.6 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2317"/></filter><filter id="ic9UCVr" width="12.344" height="11.239" x="4.541" y="3.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".25"/></filter><filter id="iXDyTce" width="12.094" height="10.965" x="15.417" y="4.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".25"/></filter><filter id="iflGqkb" width="1.294" height="1.125" x="18.698" y="16.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".05"/></filter><filter id="iKSHWOt" width="1.316" height="1.357" x="20.351" y="16.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".1"/></filter><filter id="iorpZld" width="1.493" height="1.594" x="12.068" y="16.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".1"/></filter><filter id="iwjg1oe" width="1.529" height="1.141" x="10.574" y="16.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".05"/></filter><filter id="iFbxXKb" width="2.045" height="4.004" x="4.791" y="16.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".125"/></filter><filter id="ijnm7Yb" width="2.765" height="4.549" x="24.745" y="16.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".25"/></filter><filter id="iQDG6Tb" width="4.136" height="1.815" x="9.098" y="12.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".2"/></filter><filter id="id00VHd" width="4.136" height="1.815" x="18.941" y="12.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2317" stdDeviation=".2"/></filter><linearGradient id="ijJe9Jd" x1="25.527" x2="17.412" y1="22.175" y2="22.175" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iAhi1Gd" x1="17.475" x2="15.912" y1="20.291" y2="20.356" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iwQsQ5b" x1="15.912" x2="15.912" y1="22.415" y2="21.548" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iwfI5tb" x1="15.912" x2="15.912" y1="17.131" y2="18.391" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="iTG843t" x1="13.672" x2="14.266" y1="25.344" y2="23.788" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="iYib8LL" x1="25.912" x2="7.037" y1="8.475" y2="8.475" gradientUnits="userSpaceOnUse"><stop class="jbz6du1ge"/><stop offset="1" class="p_u2yzyfd"/></linearGradient><linearGradient id="iRP5WEb" x1="21.431" x2="20.846" y1="17.425" y2="17.786" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irybZNd" x1="13.231" x2="12.646" y1="17.425" y2="17.785" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipzBX3T" x1="27.912" x2="25.662" y1="17.475" y2="21.533" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iQ5KyTc" x1="5.006" x2="7.725" y1="18.788" y2="18.55" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iAfhQ6d" x1="26.128" x2="26.128" y1="16.784" y2="20.332" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-white-hair-light" /></template>
<style>
.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ahhxrkbaj {
  stroke: var(--svg-color--dcd7df, #DCD7DF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.552 13.71c-.48-.344-1.674-.949-3.086-.711");
}

.aoa5c28ss {
  stop-color: var(--svg-color--b5afb2, #B5AFB2);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.b27i4cbjy {
  d: path("M16.346 8.563a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.182.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.beywhq7jp {
  stop-color: var(--svg-color--ede0eb, #EDE0EB);
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

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c3xhj8b9v {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.2 17.7l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnd2itcca {
  d: path("M6.849 21.363a3.06 3.06 0 0 1-1.687-.575v1.736c0 1.665.992 3.148 2.5 3.764a7.6 7.6 0 0 1-.644-2.2z");
}

.cv1cs5blk {
  stop-color: var(--svg-color--bcb0c0, #BCB0C0);
}

.cz7k6-b_c {
  stop-color: var(--svg-color--b57997, #B57997);
}

.dj4y9ccpa {
  stop-color: var(--svg-color--cbc1ce, #CBC1CE);
}

.dvwoo-blq {
  stop-color: var(--svg-color--cc8874, #CC8874);
  stop-opacity: 0;
}

.dw544eozv {
  stop-color: var(--svg-color--dbd4e1, #DBD4E1);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.ec80sooem {
  d: path("M15.912 24.433a5.6 5.6 0 0 1-2.583-.612c-.255-.13-.53.158-.369.39a3.53 3.53 0 0 0 2.952 1.577a3.53 3.53 0 0 0 2.952-1.577c.161-.242-.113-.52-.369-.39a5.6 5.6 0 0 1-2.583.612");
}

.eo39z7bsb {
  stop-color: var(--svg-color--e2dadc, #E2DADC);
  stop-opacity: 0;
}

.exw4y6u-y {
  stop-color: var(--svg-color--fff5fb, #FFF5FB);
}

.fjj8rhbfs {
  stop-color: var(--svg-color--bcb0c0, #BCB0C0);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.g9yl07uss {
  stop-color: var(--svg-color--e4dfe3, #E4DFE3);
  stop-opacity: 0;
}

.gdp977b3v {
  stop-color: var(--svg-color--e4dfe3, #E4DFE3);
}

.h47i_9ryn {
  d: path("M25.245 20.332q.109-1.774.207-3.548a1.781 1.781 0 0 1-.207 3.548");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hftodlqzp {
  d: path("M25.089 21.533q.186-2.975.344-5.95a3 3 0 0 1-.344 5.95");
}

.hkr2icc8q {
  fill: var(--svg-color--c3bbc5, #C3BBC5);
  d: path("M22.872 13.478c-.327-.285-.706-.586-1.282-.768c-.567-.178-1.277-.226-2.26-.106a.517.517 0 0 0 .125 1.027c.897-.11 1.447-.053 1.825.066c.37.116.62.305.913.56a.517.517 0 0 0 .679-.78");
}

.hw8svib4r {
  stop-color: var(--svg-color--cc8874, #CC8874);
}

.i8ob3ybgw {
  stop-color: var(--svg-color--d0c7d6, #D0C7D6);
}

.ig2pmop4j {
  d: path("M21.467 17.88a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.426z");
}

.igekverse {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.364 23.754a.36.36 0 0 0-.43.074a.33.33 0 0 0-.036.425a3.6 3.6 0 0 0 3.014 1.61a3.6 3.6 0 0 0 3.015-1.611a.334.334 0 0 0-.037-.427a.36.36 0 0 0-.428-.07h-.001a5.5 5.5 0 0 1-2.549.603c-.934 0-1.812-.22-2.548-.604Z");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jbz6du1ge {
  stop-color: var(--svg-color--ece8eb, #ECE8EB);
}

.jdxch_b6r {
  cx: 11.338px;
  cy: 17.146px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.k2lt7acah {
  d: path("M6.508 15.566c-1.457.206-2.596 1.458-2.596 2.972a3 3 0 0 0 2.836 2.996c-.12-1.993-.202-3.975-.24-5.968");
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.l7pebubmo {
  stop-color: var(--svg-color--a594aa, #A594AA);
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

.m-_vcfkqs {
  stop-color: var(--svg-color--dbd4e1, #DBD4E1);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
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

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o66_14b5c {
  d: path("M6.431 16.799a1.782 1.782 0 0 0 .156 3.503c-.065-1.168-.12-2.335-.156-3.503");
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p_u2yzyfd {
  stop-color: var(--svg-color--cfcccd, #CFCCCD);
}

.p4gx43bmc {
  stop-color: var(--svg-color--cbc1ce, #CBC1CE);
  stop-opacity: 0;
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

.q9ri5sbne {
  d: path("M11.84 16.435a1.664 1.664 0 0 0-1.603 2.103h3.214q.059-.214.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.qcopzc5iw {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.37 15.929c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.qd0vyqf9z {
  stop-color: var(--svg-color--b8adc0, #B8ADC0);
}

.qhwcf43hj {
  stop-color: var(--svg-color--fff5fb, #FFF5FB);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3ywl8pyd {
  d: path("M24.976 21.363a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rpazyibjp {
  d: path("m25.63 14.654l-.053-1.177c-.02-1.424-1.197-2.598-2.62-2.658h-2.611a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.587c2.066.274 4.934.919 6.905 2.204c3.252 2.122 2.683 5.945.97 7.746");
}

.s2u076rko {
  d: path("M19.862 16.787c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.shhwiqyyt {
  stop-color: var(--svg-color--ded7d9, #DED7D9);
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.splxym76g {
  stop-color: var(--svg-color--e2dadc, #E2DADC);
}

.sydu3xpbt {
  fill: var(--svg-color--000, #000);
  d: path("M12.794 18.1a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.t-6p9njiq {
  stop-color: var(--svg-color--bda3b2, #BDA3B2);
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tkencrcug {
  fill: var(--svg-color--c3bbc5, #C3BBC5);
  d: path("M9.553 13.274a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.027a4.14 4.14 0 0 0-2.586.53a3 3 0 0 0-.17.112l-.006.004a.517.517 0 0 1-.633-.818z");
}

.tlv177bnc {
  stop-color: var(--svg-color--b5afb2, #B5AFB2);
}

.tlv48hbvs {
  cx: 11.338px;
  cy: 17.146px;
  rx: 0.726px;
  ry: 0.368px;
}

.tt4n8bcqq {
  stop-color: var(--svg-color--a297a6, #A297A6);
}

.urfrcsboi {
  stop-color: var(--svg-color--b4b0b1, #B4B0B1);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uw932mb8u {
  d: path("m15.2 17.7l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.v2jqeg7xe {
  d: path("M24.964 6.648c.959.33 1.82 1 2.363 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.504 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.146-2.995c-.02-1.43-1.147-2.61-2.57-2.67h-2.611a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3l.058 2.866c-.474.07-.969.228-1.343.492v-2.238c0-.58-.178-1.15-.504-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.422-2.1a5 5 0 0 0 2.581-2.07a4.34 4.34 0 0 1 3.679-2.05c.603 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.701-.35c1.572 0 2.947.85 3.708 2.11c.574.95 1.474 1.64 2.522 2");
}

.veen2hyde {
  stop-color: var(--svg-color--a59ca6, #A59CA6);
  stop-opacity: 0;
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vi2pbcbzr {
  stop-color: var(--svg-color--b4b0b1, #B4B0B1);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wofq4huja {
  d: path("M6.917 24.188a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35c.22-3.512.441-7.01.605-10.52c-.02-1.43-1.148-2.61-2.572-2.67h-2.61a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3c0 3.469.217 6.882.445 10.36");
}

.xct-m9bex {
  stop-color: var(--svg-color--ded7d9, #DED7D9);
  stop-opacity: 0;
}

.xi587ab8p {
  stop-color: var(--svg-color--a59ca6, #A59CA6);
}

.y-_sqsq4r {
  fill: var(--svg-color--000, #000);
  d: path("M19.032 18.1a.95.95 0 0 1 .953-.954c.529 0 .952.424.952.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
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

.yp6ym3btc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.455 15.929a2.6 2.6 0 0 0-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.yuksi-0vv {
  stop-color: var(--svg-color--e2d0db, #E2D0DB);
}

.yxjccacgf {
  stop-color: var(--svg-color--d0c7d6, #D0C7D6);
  stop-opacity: 0;
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zox87yb_h {
  stop-color: var(--svg-color--e2d0db, #E2D0DB);
  stop-opacity: 0;
}

.zpcu4rbnn {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.164 18.056l-1.101 3.427c-.189.706.263 1.41.903 1.41h1.364c.64 0 1.091-.715.903-1.41l-.922-3.427c-.198-.76-.94-.76-1.147 0");
}

.zpjcwsbeh {
  stroke: var(--svg-color--dcd7df, #DCD7DF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.623 13.796c.48-.344 1.674-.949 3.086-.711");
}

</style>
