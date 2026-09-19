<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iztqLFd)" class="r3ywl8pyd"/><path fill="url(#ifOz7Kc)" class="r3ywl8pyd"/><path fill="url(#iKyjErd)" class="cnd2itcca"/><g filter="url(#i511jSc)"><path fill="url(#iqZYxsd)" class="wofq4huja"/><path fill="url(#iCsvYlN)" class="wofq4huja"/></g><path fill="url(#ixsAjtc)" class="wofq4huja"/><path fill="url(#iBjZe7b)" class="wofq4huja"/><path fill="url(#i0PUY5c)" class="wofq4huja"/><path fill="url(#iotFhqd)" class="wofq4huja"/><path fill="url(#iP1o8Hb)" class="wofq4huja"/><path fill="url(#i3EMMTc)" class="wofq4huja"/><path fill="url(#iDoX9sc)" class="wofq4huja"/><path fill="url(#iKUA3Qb)" class="wofq4huja"/><g filter="url(#inkCybc)"><path class="a2wrl3bba"/></g><g filter="url(#ihjZkYj)"><path class="d4lrbpfep"/><path fill="url(#ixQKMdd)" class="uw932mb8u"/><path fill="url(#ioQPLpc)" class="uw932mb8u"/><path fill="url(#iZR06ve)" class="uw932mb8u"/><path fill="url(#iDy81Mc)" class="uw932mb8u"/><path fill="url(#iOzgukb)" class="uw932mb8u"/></g><path fill="url(#icKg5Xv)" class="uw932mb8u"/><path fill="url(#iZzodFL)" class="uw932mb8u"/><g filter="url(#i1HaxAc)"><path stroke="url(#icPzbXd)" class="igekverse"/></g><path fill="url(#iQTdige)" class="ec80sooem"/><g filter="url(#i4Wyc3t)"><path fill="url(#iYib8LL)" class="v2jqeg7xe"/><path fill="url(#ihSkAdd)" class="v2jqeg7xe"/><path fill="url(#ifZyn6c)" class="v2jqeg7xe"/><path fill="url(#icV02MT)" class="v2jqeg7xe"/><path fill="url(#i6CCFEW)" class="v2jqeg7xe"/></g><g filter="url(#i9el7zc)"><path class="hkr2icc8q"/></g><g filter="url(#iQzEhdb)"><path class="tkencrcug"/></g><g filter="url(#i4gERdm)"><path fill="url(#iylgcLx)" class="b27i4cbjy"/><path fill="url(#iK0dubc)" class="b27i4cbjy"/></g><g filter="url(#i9Sld6Y)"><path fill="url(#iqYqFbb)" class="rpazyibjp"/><path fill="url(#iNS3XCc)" class="rpazyibjp"/><path fill="url(#ijhnyCd)" class="rpazyibjp"/><path fill="url(#i2BnyRd)" class="rpazyibjp"/><path fill="url(#iwh24Ge)" class="rpazyibjp"/></g><path class="qcopzc5iw"/><path fill="url(#iaLBOcb)" class="na4dsyf3s"/><path class="y-_sqsq4r"/><g filter="url(#i7XJ7Cd)"><path class="mxgfotkxz"/><path fill="url(#i8DK2Uc)" class="s2u076rko"/></g><g filter="url(#i1Byixd)"><path fill="url(#iRP5WEb)" class="ig2pmop4j"/></g><path class="yp6ym3btc"/><path fill="url(#iYax22d)" class="q9ri5sbne"/><path class="sydu3xpbt"/><g filter="url(#ioAyOFc)"><path fill="url(#irybZNd)" class="nadebokqo"/></g><g filter="url(#ilLj9Ob)"><ellipse transform="rotate(-27.914 11.338 17.146)" class="jdxch_b6r"/><ellipse fill="url(#ibSnHld)" transform="rotate(-27.914 11.338 17.146)" class="tlv48hbvs"/></g><path fill="url(#iVPwCll)" class="hftodlqzp"/><path fill="url(#i3nMckb)" class="hftodlqzp"/><path fill="url(#iOIDFdb)" class="hftodlqzp"/><path fill="url(#iTc6ZHV)" class="hftodlqzp"/><path fill="url(#izq88nd)" class="odbrf0bjn"/><path fill="url(#ivMMSpd)" class="odbrf0bjn"/><g filter="url(#iYf6xSc)"><path fill="url(#iWvS7Jb)" class="o66_14b5c"/></g><g filter="url(#ihkZZ2L)"><path fill="url(#iW7hN5d)" class="xpqpbwbij"/></g><g filter="url(#ieWT0qd)"><path class="zpjcwsbeh"/></g><g filter="url(#ikgwnue)"><path class="ahhxrkbaj"/></g><defs><radialGradient id="iztqLFd" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 4.96 20.71)scale(6.07867 7.22099)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="beywhq7jp"/><stop offset="1" class="qd0vyqf9z"/></radialGradient><radialGradient id="ifOz7Kc" cx="0" cy="0" r="1" gradientTransform="matrix(.375 1.4375 -2.0036 .52268 25.216 21.185)" gradientUnits="userSpaceOnUse"><stop class="yuksi-0vv"/><stop offset="1" class="zox87yb_h"/></radialGradient><radialGradient id="iKyjErd" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 5 -2.27273 1.07954 5.569 21.007)" gradientUnits="userSpaceOnUse"><stop class="t-6p9njiq"/><stop offset="1" class="l7pebubmo"/></radialGradient><radialGradient id="iqZYxsd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.77212 0 0 -15.5178 21.147 19.033)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iCsvYlN" cx="0" cy="0" r="1" gradientTransform="matrix(-3.24997 5.37502 -4.43752 -2.68312 20.438 9.75)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iBjZe7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90593 23.16252 -19.18137 -1.57834 18.861 8.007)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="i0PUY5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.141 2.64949 0 20.475 16.585)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iotFhqd" cx="0" cy="0" r="1" gradientTransform="matrix(.00733 -2.04019 2.2202 .00797 11.624 16.672)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iP1o8Hb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 10.827 10.79)scale(15.8715 40.5438)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i3EMMTc" cx="0" cy="0" r="1" gradientTransform="matrix(6.3125 -5.4375 1.60615 1.8646 3.25 13.937)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iDoX9sc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 4.65625 -1.8613 -.17489 26.25 13.594)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iKUA3Qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.625 -3.11954 0 11.781 18.11)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="ioQPLpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4551 -1.43034 0 16.782 21.57)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iDy81Mc" cx="0" cy="0" r="1" gradientTransform="rotate(156.092 6.328 12.053)scale(3.45078 5.54568)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iZzodFL" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39062 2.28126 -3.2924 -3.45025 16.719 19.969)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iQTdige" cx="0" cy="0" r="1" gradientTransform="matrix(4.06811 -2 8.04654 16.36708 14.997 25.788)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ihSkAdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.162 16.083)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="xi587ab8p"/><stop offset="1" class="veen2hyde"/></radialGradient><radialGradient id="ifZyn6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 24.975 16.083)" gradientUnits="userSpaceOnUse"><stop class="shhwiqyyt"/><stop offset="1" class="xct-m9bex"/></radialGradient><radialGradient id="icV02MT" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 2.625 -6.38151 7.90093 8.725 3.87)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="urfrcsboi"/><stop offset="1" class="vi2pbcbzr"/></radialGradient><radialGradient id="i6CCFEW" cx="0" cy="0" r="1" gradientTransform="rotate(-128.047 5.473 3.097)scale(2.24211 4.11492)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="tlv177bnc"/><stop offset="1" class="aoa5c28ss"/></radialGradient><radialGradient id="iylgcLx" cx="0" cy="0" r="1" gradientTransform="matrix(-8.13156 2.93075 -.8157 -2.2632 16.385 4.102)" gradientUnits="userSpaceOnUse"><stop class="gdp977b3v"/><stop offset="1" class="g9yl07uss"/></radialGradient><radialGradient id="iK0dubc" cx="0" cy="0" r="1" gradientTransform="rotate(-58.775 14.942 1.86)scale(11.9254 13.2121)" gradientUnits="userSpaceOnUse"><stop class="tt4n8bcqq"/><stop offset=".233" class="cv1cs5blk"/><stop offset="1" class="fjj8rhbfs"/></radialGradient><radialGradient id="iqYqFbb" cx="0" cy="0" r="1" gradientTransform="matrix(7.11624 1.54509 -.95711 4.4082 22.663 6.069)" gradientUnits="userSpaceOnUse"><stop class="exw4y6u-y"/><stop offset="1" class="qhwcf43hj"/></radialGradient><radialGradient id="iNS3XCc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.957 -.01)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="i8ob3ybgw"/><stop offset="1" class="yxjccacgf"/></radialGradient><radialGradient id="ijhnyCd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.319 14.094)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="m-_vcfkqs"/><stop offset="1" class="dw544eozv"/></radialGradient><radialGradient id="i2BnyRd" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.079 4.395)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="p4gx43bmc"/><stop offset="1" class="dj4y9ccpa"/></radialGradient><radialGradient id="iwh24Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.46875 -8.70091 -2.03645 22.435 5.207)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="splxym76g"/><stop offset="1" class="eo39z7bsb"/></radialGradient><radialGradient id="iaLBOcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.98 17.325)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8DK2Uc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.059 3.952)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYax22d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.844 17.325)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibSnHld" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.384 3.3)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3nMckb" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 .82 24.844)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iOIDFdb" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.194 18.366)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iTc6ZHV" cx="0" cy="0" r="1" gradientTransform="matrix(1.0944 -2.89062 3.86227 1.46228 25.406 18.688)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="ivMMSpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09167 0 0 -3.45229 6.748 18.546)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iWvS7Jb" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 2.585 9.563)scale(1.73369 1.77757)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="i511jSc" width="20.055" height="23.21" x="6.472" y="7.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2319"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2319" result="effect2_innerShadow_3930_2319"/></filter><filter id="inkCybc" width="5.257" height="7.407" x="13.019" y="16.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".5"/></filter><filter id="ihjZkYj" width="3.9" height="5.807" x="13.962" y="16.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".1"/></filter><filter id="i1HaxAc" width="6.5" height="2.5" x="12.662" y="23.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".05"/></filter><filter id="i4Wyc3t" width="24" height="15.148" x="3.912" y="2.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.670588 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2319"/></filter><filter id="i9el7zc" width="4.274" height="2.047" x="18.875" y="12.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.6 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2319"/></filter><filter id="iQzEhdb" width="4.274" height="2.019" x="9.075" y="12.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.6 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2319"/></filter><filter id="i4gERdm" width="12.344" height="11.239" x="4.541" y="3.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".25"/></filter><filter id="i9Sld6Y" width="12.094" height="10.965" x="15.417" y="4.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".25"/></filter><filter id="i7XJ7Cd" width="1.294" height="1.125" x="18.698" y="16.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".05"/></filter><filter id="i1Byixd" width="1.316" height="1.357" x="20.351" y="16.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".1"/></filter><filter id="ioAyOFc" width="1.493" height="1.594" x="12.068" y="16.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".1"/></filter><filter id="ilLj9Ob" width="1.529" height="1.141" x="10.574" y="16.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".05"/></filter><filter id="iYf6xSc" width="2.045" height="4.004" x="4.791" y="16.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".125"/></filter><filter id="ihkZZ2L" width="2.503" height="4.277" x="24.828" y="16.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".25"/></filter><filter id="ieWT0qd" width="4.136" height="1.815" x="9.098" y="12.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".2"/></filter><filter id="ikgwnue" width="4.136" height="1.815" x="18.941" y="12.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2319" stdDeviation=".2"/></filter><linearGradient id="ixsAjtc" x1="25.527" x2="20.813" y1="22.175" y2="22.175" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ixQKMdd" x1="17.475" x2="15.912" y1="20.291" y2="20.356" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iZR06ve" x1="15.912" x2="15.912" y1="22.415" y2="21.548" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iOzgukb" x1="15.912" x2="15.912" y1="17.372" y2="18.391" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="icKg5Xv" x1="16.688" x2="16.688" y1="22.672" y2="22.313" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="icPzbXd" x1="13.672" x2="14.266" y1="25.344" y2="23.788" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iYib8LL" x1="25.912" x2="7.037" y1="8.475" y2="8.475" gradientUnits="userSpaceOnUse"><stop class="jbz6du1ge"/><stop offset="1" class="p_u2yzyfd"/></linearGradient><linearGradient id="iRP5WEb" x1="21.431" x2="20.846" y1="17.425" y2="17.786" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irybZNd" x1="13.231" x2="12.646" y1="17.425" y2="17.785" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVPwCll" x1="27.912" x2="25.662" y1="17.475" y2="21.533" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="izq88nd" x1="5.006" x2="7.725" y1="18.788" y2="18.55" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iW7hN5d" x1="26.079" x2="26.079" y1="16.899" y2="20.177" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-white-hair-medium" /></template>
<style>
.a2wrl3bba {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.164 18.066l-1.101 3.427c-.189.705.263 1.41.903 1.41h1.364c.64 0 1.091-.716.903-1.41l-.922-3.427c-.198-.76-.94-.76-1.147 0");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.ahhxrkbaj {
  stroke: var(--svg-color--dcd7df, #DCD7DF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.552 13.71c-.48-.344-1.674-.949-3.086-.711");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.aoa5c28ss {
  stop-color: var(--svg-color--b5afb2, #B5AFB2);
  stop-opacity: 0;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b27i4cbjy {
  d: path("M16.346 8.563a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.182.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.beywhq7jp {
  stop-color: var(--svg-color--ede0eb, #EDE0EB);
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

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
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

.d4lrbpfep {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.2 17.7l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dj4y9ccpa {
  stop-color: var(--svg-color--cbc1ce, #CBC1CE);
}

.dw544eozv {
  stop-color: var(--svg-color--dbd4e1, #DBD4E1);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
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

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fjj8rhbfs {
  stop-color: var(--svg-color--bcb0c0, #BCB0C0);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g9yl07uss {
  stop-color: var(--svg-color--e4dfe3, #E4DFE3);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gdp977b3v {
  stop-color: var(--svg-color--e4dfe3, #E4DFE3);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hftodlqzp {
  d: path("M25.089 21.533q.186-2.975.344-5.95a3 3 0 0 1-.344 5.95");
}

.hkr2icc8q {
  fill: var(--svg-color--c3bbc5, #C3BBC5);
  d: path("M22.872 13.478c-.327-.285-.706-.586-1.282-.768c-.567-.178-1.277-.226-2.26-.106a.517.517 0 0 0 .125 1.027c.897-.11 1.447-.053 1.825.066c.37.116.62.305.913.56a.517.517 0 0 0 .679-.78");
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i8ob3ybgw {
  stop-color: var(--svg-color--d0c7d6, #D0C7D6);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ig2pmop4j {
  d: path("M21.467 17.88a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.426z");
}

.igekverse {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.364 23.754a.36.36 0 0 0-.43.074a.33.33 0 0 0-.036.425a3.6 3.6 0 0 0 3.014 1.61a3.6 3.6 0 0 0 3.015-1.611a.334.334 0 0 0-.037-.427a.36.36 0 0 0-.428-.07h-.001a5.5 5.5 0 0 1-2.549.603c-.934 0-1.812-.22-2.548-.604Z");
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

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7pebubmo {
  stop-color: var(--svg-color--a594aa, #A594AA);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m-_vcfkqs {
  stop-color: var(--svg-color--dbd4e1, #DBD4E1);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mxgfotkxz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.862 16.787c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.na4dsyf3s {
  d: path("M19.985 16.435a1.664 1.664 0 0 1 1.603 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.672-1.664");
}

.nadebokqo {
  d: path("M13.36 17.904c0-.538-.437-.896-.555-1.005l-.537.52l.33.674z");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o66_14b5c {
  d: path("M6.431 16.799a1.782 1.782 0 0 0 .156 3.503c-.065-1.168-.12-2.335-.156-3.503");
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

.odbrf0bjn {
  d: path("M6.508 15.559a3.025 3.025 0 0 0-2.596 2.979a3 3 0 0 0 2.836 2.996q-.181-2.988-.24-5.975");
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
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

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
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

.r3ywl8pyd {
  d: path("M24.976 21.363a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rpazyibjp {
  d: path("m25.63 14.654l-.053-1.177c-.02-1.424-1.197-2.598-2.62-2.658h-2.611a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.587c2.066.274 4.934.919 6.905 2.204c3.252 2.122 2.683 5.945.97 7.746");
}

.s2u076rko {
  d: path("M19.862 16.787c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.shhwiqyyt {
  stop-color: var(--svg-color--ded7d9, #DED7D9);
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
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

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.urfrcsboi {
  stop-color: var(--svg-color--b4b0b1, #B4B0B1);
}

.uw932mb8u {
  d: path("m15.2 17.7l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.v2jqeg7xe {
  d: path("M24.964 6.648c.959.33 1.82 1 2.363 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.504 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.146-2.995c-.02-1.43-1.147-2.61-2.57-2.67h-2.611a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3l.058 2.866c-.474.07-.969.228-1.343.492v-2.238c0-.58-.178-1.15-.504-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.422-2.1a5 5 0 0 0 2.581-2.07a4.34 4.34 0 0 1 3.679-2.05c.603 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.701-.35c1.572 0 2.947.85 3.708 2.11c.574.95 1.474 1.64 2.522 2");
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.veen2hyde {
  stop-color: var(--svg-color--a59ca6, #A59CA6);
  stop-opacity: 0;
}

.vi2pbcbzr {
  stop-color: var(--svg-color--b4b0b1, #B4B0B1);
  stop-opacity: 0;
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
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

.xpqpbwbij {
  d: path("M25.328 20.177q.092-1.639.176-3.278c.748.101 1.327.794 1.327 1.633c0 .903-.672 1.636-1.503 1.645");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.y-_sqsq4r {
  fill: var(--svg-color--000, #000);
  d: path("M19.032 18.1a.95.95 0 0 1 .953-.954c.529 0 .952.424.952.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
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

.zox87yb_h {
  stop-color: var(--svg-color--e2d0db, #E2D0DB);
  stop-opacity: 0;
}

.zpjcwsbeh {
  stroke: var(--svg-color--dcd7df, #DCD7DF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.623 13.796c.48-.344 1.674-.949 3.086-.711");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
