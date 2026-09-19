<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#icK3bsl)" class="be6rpdeaj"/><path fill="url(#iL3fkYb)" class="be6rpdeaj"/><path fill="url(#iFN5gFb)" class="u_8o32b5j"/><g filter="url(#inn4wve)"><path fill="url(#iDgPy0Q)" class="hryevwuwq"/></g><path fill="url(#i5gUCOa)" class="hryevwuwq"/><path fill="url(#ihPIGuc)" class="hryevwuwq"/><path fill="url(#iYiU7jb)" class="hryevwuwq"/><path fill="url(#iVPMpYW)" class="hryevwuwq"/><path fill="url(#iNpcfYA)" class="hryevwuwq"/><path fill="url(#iOyzhSc)" class="hryevwuwq"/><path fill="url(#iM1OR1b)" class="hryevwuwq"/><path fill="url(#i8aX3hg)" class="hryevwuwq"/><g filter="url(#idCHkOe)"><path class="e25ecjbye"/></g><g filter="url(#irW2jVc)"><path fill="url(#il3jSub)" class="f3xy4fbyy"/><path fill="url(#iAVYakd)" class="f3xy4fbyy"/><path fill="url(#ietgEje)" class="f3xy4fbyy"/><path fill="url(#iPbNq3N)" class="f3xy4fbyy"/></g><path fill="url(#ixobcOe)" class="f3xy4fbyy"/><path fill="url(#iB5Eatc)" class="f3xy4fbyy"/><g filter="url(#iAitGTc)"><path stroke="url(#iCL7dlb)" class="n68r1hb9o"/></g><path fill="url(#ieMyCxe)" class="mlzz411wz"/><g filter="url(#ibumcux)"><path fill="url(#iwVu2gb)" class="pjk2z4bnh"/><path fill="url(#iJgkxte)" class="pjk2z4bnh"/><path fill="url(#i61pkbi)" class="pjk2z4bnh"/><path fill="url(#iqHJDRc)" class="pjk2z4bnh"/><path fill="url(#i31VaBb)" class="pjk2z4bnh"/></g><g filter="url(#ifLN4yc)"><path class="cfa3df2sl"/></g><g filter="url(#iWtYxze)"><path class="zykaovrot"/></g><g filter="url(#i76VOmy)"><path fill="url(#iR7Ae8a)" class="ds71pnb-p"/><path fill="url(#iAtoVPd)" class="ds71pnb-p"/></g><g filter="url(#iwSFbre)"><path fill="url(#iSLgX0g)" class="eay_l51dq"/><path fill="url(#ijTGUNc)" class="eay_l51dq"/><path fill="url(#iObE64d)" class="eay_l51dq"/><path fill="url(#iL6wghc)" class="eay_l51dq"/><path fill="url(#ia2ZM0d)" class="eay_l51dq"/></g><path class="irwnsrbdy"/><path fill="url(#i39xo8O)" class="t8rz6-b4j"/><path class="au9gygbbx"/><g filter="url(#idsHcRd)"><path class="oqyz1-b1x"/><path fill="url(#iFJoSpc)" class="jhr6jzbby"/></g><g filter="url(#iTmTDip)"><path fill="url(#i4ebNXO)" class="wagfjcb7l"/></g><path class="lks4f7lui"/><path fill="url(#imjxJsM)" class="rr7m3ibhc"/><path class="qcy-xjb9z"/><g filter="url(#ikoeUvc)"><path fill="url(#ixlhrFb)" class="kf_7dpbrd"/></g><g filter="url(#iaYygPe)"><ellipse transform="rotate(-27.914 11.338 16.646)" class="wti4q6bgh"/><ellipse fill="url(#in65Ppd)" transform="rotate(-27.914 11.338 16.646)" class="vhqb4xrsh"/></g><path fill="url(#iTf8Uze)" class="x08-9gb4f"/><path fill="url(#iT28GeN)" class="x08-9gb4f"/><path fill="url(#iwTMyRc)" class="x08-9gb4f"/><path fill="url(#iSXNOza)" class="q2unmfbzf"/><path fill="url(#iHKhvyv)" class="q2unmfbzf"/><g filter="url(#ibDsm6c)"><path class="ilod4rs-k"/></g><g filter="url(#iM9Z5ye)"><path class="slv_h0d2l"/></g><g filter="url(#iOX8Lqe)"><path class="f11_yds_g"/></g><g filter="url(#isX4lad)"><path class="aeu_7q_lm"/></g><defs><radialGradient id="icK3bsl" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 5.157 20.46)scale(6.07867 7.22099)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="beywhq7jp"/><stop offset="1" class="qd0vyqf9z"/></radialGradient><radialGradient id="iL3fkYb" cx="0" cy="0" r="1" gradientTransform="matrix(.375 1.4375 -2.0036 .52268 25.216 20.685)" gradientUnits="userSpaceOnUse"><stop class="yuksi-0vv"/><stop offset="1" class="zox87yb_h"/></radialGradient><radialGradient id="iFN5gFb" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 5 -2.27273 1.07954 5.569 20.507)" gradientUnits="userSpaceOnUse"><stop class="t-6p9njiq"/><stop offset="1" class="l7pebubmo"/></radialGradient><radialGradient id="iDgPy0Q" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.147 18.533)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="ihPIGuc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.131 24.16843 -20.01435 -1.76472 18.86 7.508)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="zgchiqbcj"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="iYiU7jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 3.09375 0 20.475 16.444)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iVPMpYW" cx="0" cy="0" r="1" gradientTransform="matrix(-.10826 -2.0572 2.23871 -.1178 11.74 16.189)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iNpcfYA" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 0 0 11.4362 6.812 19.25)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iOyzhSc" cx="0" cy="0" r="1" gradientTransform="matrix(4.875 -6.8125 1.54304 1.1042 5 12.937)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iM1OR1b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.49993 -19.0971 21.036 -4.9568 15.625 26.125)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="i8aX3hg" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 1.34375 -.8061 2.28709 19.563 8.5)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iB5Eatc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.4297 3.41405 -2.16998 -2.17993 17.813 18.39)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iCL7dlb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 27.955 .546)scale(1.32391 3.85262)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="ieMyCxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 15.912 25.132)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iJgkxte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.162 15.583)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="xi587ab8p"/><stop offset="1" class="veen2hyde"/></radialGradient><radialGradient id="i61pkbi" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 24.975 15.583)" gradientUnits="userSpaceOnUse"><stop class="shhwiqyyt"/><stop offset="1" class="xct-m9bex"/></radialGradient><radialGradient id="iqHJDRc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 2.625 -6.38151 7.90093 8.725 3.37)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="urfrcsboi"/><stop offset="1" class="vi2pbcbzr"/></radialGradient><radialGradient id="i31VaBb" cx="0" cy="0" r="1" gradientTransform="rotate(-128.047 5.351 2.847)scale(2.24211 4.11492)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="tlv177bnc"/><stop offset="1" class="aoa5c28ss"/></radialGradient><radialGradient id="iR7Ae8a" cx="0" cy="0" r="1" gradientTransform="matrix(-8.13156 2.93075 -.8157 -2.2632 16.385 3.602)" gradientUnits="userSpaceOnUse"><stop class="gdp977b3v"/><stop offset="1" class="g9yl07uss"/></radialGradient><radialGradient id="iAtoVPd" cx="0" cy="0" r="1" gradientTransform="rotate(-58.775 14.498 1.61)scale(11.9254 13.2121)" gradientUnits="userSpaceOnUse"><stop class="tt4n8bcqq"/><stop offset=".233" class="cv1cs5blk"/><stop offset="1" class="fjj8rhbfs"/></radialGradient><radialGradient id="iSLgX0g" cx="0" cy="0" r="1" gradientTransform="matrix(7.11624 1.54509 -.95711 4.4082 22.663 5.765)" gradientUnits="userSpaceOnUse"><stop class="exw4y6u-y"/><stop offset="1" class="qhwcf43hj"/></radialGradient><radialGradient id="ijTGUNc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.87 -.161)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="i8ob3ybgw"/><stop offset="1" class="yxjccacgf"/></radialGradient><radialGradient id="iObE64d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.319 13.79)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="m-_vcfkqs"/><stop offset="1" class="dw544eozv"/></radialGradient><radialGradient id="iL6wghc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.097 4.243)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="p4gx43bmc"/><stop offset="1" class="dj4y9ccpa"/></radialGradient><radialGradient id="ia2ZM0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 1.46875 -8.70091 -2.03645 22.435 4.904)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="splxym76g"/><stop offset="1" class="eo39z7bsb"/></radialGradient><radialGradient id="i39xo8O" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 19.98 16.825)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iFJoSpc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.936 3.702)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imjxJsM" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.844 16.825)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="in65Ppd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.138 3.05)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iT28GeN" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.15 24.594)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iwTMyRc" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.194 17.866)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iHKhvyv" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 4.03 8.78)scale(3.15614 3.10277)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="inn4wve" width="19.805" height="23.21" x="6.472" y="7.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2318"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2318" result="effect2_innerShadow_3930_2318"/></filter><filter id="idCHkOe" width="5.271" height="7.264" x="12.776" y="16.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".5"/></filter><filter id="irW2jVc" width="3.7" height="5.607" x="14.062" y="16.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".05"/></filter><filter id="iAitGTc" width="6.5" height="2.5" x="12.662" y="23.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".05"/></filter><filter id="ibumcux" width="24" height="15.148" x="3.912" y="1.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.670588 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2318"/></filter><filter id="ifLN4yc" width="4.274" height="2.047" x="18.875" y="11.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.6 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2318"/></filter><filter id="iWtYxze" width="4.274" height="2.019" x="9.075" y="11.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.6 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2318"/></filter><filter id="i76VOmy" width="12.344" height="11.239" x="4.541" y="3.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".25"/></filter><filter id="iwSFbre" width="12.094" height="10.965" x="15.417" y="3.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".25"/></filter><filter id="idsHcRd" width="1.294" height="1.125" x="18.698" y="16.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".05"/></filter><filter id="iTmTDip" width="1.316" height="1.357" x="20.351" y="16.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".1"/></filter><filter id="ikoeUvc" width="1.493" height="1.594" x="12.068" y="16.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".1"/></filter><filter id="iaYygPe" width="1.529" height="1.141" x="10.574" y="16.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".05"/></filter><filter id="ibDsm6c" width="2.045" height="4.004" x="4.881" y="16.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".125"/></filter><filter id="iM9Z5ye" width="2.265" height="4.049" x="24.913" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".125"/></filter><filter id="iOX8Lqe" width="4.136" height="1.815" x="9.098" y="12.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".2"/></filter><filter id="isX4lad" width="4.136" height="1.815" x="18.941" y="11.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2318" stdDeviation=".2"/></filter><linearGradient id="i5gUCOa" x1="25.527" x2="19.837" y1="21.675" y2="21.017" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="il3jSub" x1="15.912" x2="17.506" y1="20.078" y2="20.078" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iAVYakd" x1="13.912" x2="15.915" y1="19.788" y2="19.898" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ietgEje" x1="15.912" x2="15.912" y1="20.821" y2="22.41" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iPbNq3N" x1="15.912" x2="15.912" y1="16.631" y2="17.413" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ixobcOe" x1="16.156" x2="16.156" y1="22.078" y2="21.969" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="iwVu2gb" x1="25.912" x2="7.037" y1="7.975" y2="7.975" gradientUnits="userSpaceOnUse"><stop class="jbz6du1ge"/><stop offset="1" class="p_u2yzyfd"/></linearGradient><linearGradient id="i4ebNXO" x1="21.431" x2="20.846" y1="16.925" y2="17.286" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixlhrFb" x1="13.231" x2="12.646" y1="16.925" y2="17.285" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTf8Uze" x1="27.912" x2="25.662" y1="16.975" y2="21.033" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iSXNOza" x1="5.006" x2="7.725" y1="18.288" y2="18.05" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-white-hair-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.aeu_7q_lm {
  stroke: var(--svg-color--dcd7df, #DCD7DF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.552 13.21c-.48-.344-1.674-.949-3.086-.711");
}

.aoa5c28ss {
  stop-color: var(--svg-color--b5afb2, #B5AFB2);
  stop-opacity: 0;
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.au9gygbbx {
  fill: var(--svg-color--000, #000);
  d: path("M19.032 17.6a.95.95 0 0 1 .953-.954c.529 0 .952.424.952.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.be6rpdeaj {
  d: path("M24.976 20.863a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.beywhq7jp {
  stop-color: var(--svg-color--ede0eb, #EDE0EB);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cfa3df2sl {
  fill: var(--svg-color--c3bbc5, #C3BBC5);
  d: path("M22.872 12.978c-.327-.285-.706-.586-1.282-.768c-.567-.178-1.277-.226-2.26-.106a.517.517 0 0 0 .125 1.027c.897-.11 1.447-.053 1.825.066c.37.116.62.305.913.56a.517.517 0 0 0 .679-.78");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv1cs5blk {
  stop-color: var(--svg-color--bcb0c0, #BCB0C0);
}

.dj4y9ccpa {
  stop-color: var(--svg-color--cbc1ce, #CBC1CE);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.ds71pnb-p {
  d: path("M16.346 8.063a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3v.513c-.633-.482-1.43-1.5-1.43-3.147c0-1.998 1.457-3.008 2.386-3.653c.263-.182.483-.334.617-.472l.186-.195c.652-.691 1.813-1.923 3.84-2.461c1.299-.345 2.62-.348 3.511-.269c.471.043.803.451.803.924v3.47z");
}

.dw544eozv {
  stop-color: var(--svg-color--dbd4e1, #DBD4E1);
  stop-opacity: 0;
}

.e25ecjbye {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.11 17.906l-1.29 3.087c-.19.705.264 1.41.906 1.41h1.37c.643 0 1.097-.716.908-1.41l-.926-3.427c-.199-.76-.76-.419-.969.34");
}

.eay_l51dq {
  d: path("m25.63 14.35l-.053-1.177c-.02-1.423-1.197-2.598-2.62-2.657h-2.611a4.51 4.51 0 0 1-3.96-2.349s-.382-.885-.466-2.18c-.065-1 .84-1.718 1.835-1.586c2.066.273 4.934.918 6.905 2.204c3.252 2.121 2.683 5.945.97 7.745");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eo39z7bsb {
  stop-color: var(--svg-color--e2dadc, #E2DADC);
  stop-opacity: 0;
}

.exw4y6u-y {
  stop-color: var(--svg-color--fff5fb, #FFF5FB);
}

.f11_yds_g {
  stroke: var(--svg-color--dcd7df, #DCD7DF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.623 13.296c.48-.344 1.674-.949 3.086-.711");
}

.f3xy4fbyy {
  d: path("m15.2 17.2l-.991 3.428c-.202.705.283 1.41.97 1.41h1.466c.688 0 1.173-.716.971-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fjj8rhbfs {
  stop-color: var(--svg-color--bcb0c0, #BCB0C0);
  stop-opacity: 0;
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g9yl07uss {
  stop-color: var(--svg-color--e4dfe3, #E4DFE3);
  stop-opacity: 0;
}

.gdp977b3v {
  stop-color: var(--svg-color--e4dfe3, #E4DFE3);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hryevwuwq {
  d: path("M6.917 23.688a7.3 7.3 0 0 0 7.244 6.35h3.518a7.3 7.3 0 0 0 7.244-6.35c.22-3.512.441-7.01.605-10.52c-.02-1.43-1.148-2.61-2.572-2.67h-2.61a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3c0 3.469.217 6.882.445 10.36");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i8ob3ybgw {
  stop-color: var(--svg-color--d0c7d6, #D0C7D6);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ilod4rs-k {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M6.521 16.3a1.782 1.782 0 0 0 .156 3.504c-.065-1.169-.12-2.335-.156-3.504");
}

.irwnsrbdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.37 15.429c1.218 0 2.246.84 2.526 1.974a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.jbz6du1ge {
  stop-color: var(--svg-color--ece8eb, #ECE8EB);
}

.jhr6jzbby {
  d: path("M19.862 16.287c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.kf_7dpbrd {
  d: path("M13.36 17.404c0-.538-.437-.896-.555-1.005l-.537.52l.33.674z");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l7pebubmo {
  stop-color: var(--svg-color--a594aa, #A594AA);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lks4f7lui {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.455 15.429a2.6 2.6 0 0 0-2.526 1.974a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.m-_vcfkqs {
  stop-color: var(--svg-color--dbd4e1, #DBD4E1);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mlzz411wz {
  d: path("M15.912 23.933a5.6 5.6 0 0 1-2.583-.612c-.255-.13-.53.158-.369.39a3.53 3.53 0 0 0 2.952 1.577a3.53 3.53 0 0 0 2.952-1.577c.161-.242-.113-.52-.369-.39a5.6 5.6 0 0 1-2.583.612");
}

.n68r1hb9o {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.364 23.254a.36.36 0 0 0-.43.074a.33.33 0 0 0-.036.425a3.6 3.6 0 0 0 3.014 1.61a3.6 3.6 0 0 0 3.015-1.611a.334.334 0 0 0-.037-.427a.36.36 0 0 0-.428-.07h-.001a5.5 5.5 0 0 1-2.549.603c-.934 0-1.812-.22-2.548-.604Z");
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oqyz1-b1x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.862 16.287c.119.159-.13.352-.41.563c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.253.725-.094");
}

.p_u2yzyfd {
  stop-color: var(--svg-color--cfcccd, #CFCCCD);
}

.p4gx43bmc {
  stop-color: var(--svg-color--cbc1ce, #CBC1CE);
  stop-opacity: 0;
}

.pjk2z4bnh {
  d: path("M24.964 6.148c.959.33 1.82 1 2.363 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.504 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.146-2.995c-.02-1.43-1.147-2.61-2.57-2.67h-2.611a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.148-.78h-2.373c-3.441 0-6.23 2.82-6.23 6.3l.058 2.866c-.474.07-.969.228-1.343.492v-2.238c0-.58-.178-1.15-.504-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.422-2.1a5 5 0 0 0 2.581-2.07a4.34 4.34 0 0 1 3.679-2.05c.603 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.701-.35c1.572 0 2.947.85 3.708 2.11c.574.95 1.474 1.64 2.522 2");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q2unmfbzf {
  d: path("M6.49 15.067a3 3 0 0 0 .258 5.966c-.12-1.992-.22-3.973-.258-5.966");
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qcy-xjb9z {
  fill: var(--svg-color--000, #000);
  d: path("M12.794 17.6a.95.95 0 0 0-.953-.954a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
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

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.rr7m3ibhc {
  d: path("M11.84 15.935a1.664 1.664 0 0 0-1.603 2.103h3.214q.059-.214.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.shhwiqyyt {
  stop-color: var(--svg-color--ded7d9, #DED7D9);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.slv_h0d2l {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M25.163 19.819q.109-1.774.207-3.549a1.781 1.781 0 0 1-.207 3.549");
}

.splxym76g {
  stop-color: var(--svg-color--e2dadc, #E2DADC);
}

.t-6p9njiq {
  stop-color: var(--svg-color--bda3b2, #BDA3B2);
}

.t8rz6-b4j {
  d: path("M19.985 15.935a1.664 1.664 0 0 1 1.603 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.672-1.664");
}

.tlv177bnc {
  stop-color: var(--svg-color--b5afb2, #B5AFB2);
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tt4n8bcqq {
  stop-color: var(--svg-color--a297a6, #A297A6);
}

.u_8o32b5j {
  d: path("M6.849 20.863a3.06 3.06 0 0 1-1.687-.575v1.736c0 1.665.992 3.148 2.5 3.764a7.6 7.6 0 0 1-.644-2.2z");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.urfrcsboi {
  stop-color: var(--svg-color--b4b0b1, #B4B0B1);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.veen2hyde {
  stop-color: var(--svg-color--a59ca6, #A59CA6);
  stop-opacity: 0;
}

.vhqb4xrsh {
  cx: 11.338px;
  cy: 16.646px;
  rx: 0.726px;
  ry: 0.368px;
}

.vi2pbcbzr {
  stop-color: var(--svg-color--b4b0b1, #B4B0B1);
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

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x08-9gb4f {
  d: path("M25.089 21.033q.186-2.975.344-5.95a3 3 0 0 1-.344 5.95");
}

.xct-m9bex {
  stop-color: var(--svg-color--ded7d9, #DED7D9);
  stop-opacity: 0;
}

.xi587ab8p {
  stop-color: var(--svg-color--a59ca6, #A59CA6);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yuksi-0vv {
  stop-color: var(--svg-color--e2d0db, #E2D0DB);
}

.yxjccacgf {
  stop-color: var(--svg-color--d0c7d6, #D0C7D6);
  stop-opacity: 0;
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.zgchiqbcj {
  stop-color: var(--svg-color--b36e91, #B36E91);
  stop-opacity: 0;
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zox87yb_h {
  stop-color: var(--svg-color--e2d0db, #E2D0DB);
  stop-opacity: 0;
}

.zykaovrot {
  fill: var(--svg-color--c3bbc5, #C3BBC5);
  d: path("M9.553 12.774a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.027a4.14 4.14 0 0 0-2.586.53a3 3 0 0 0-.17.112l-.006.004a.517.517 0 0 1-.633-.818z");
}

</style>
