<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iefDlpe)" class="u0sztvvta"/><path fill="url(#i13DFbi)" class="u0sztvvta"/><path fill="url(#iGN15oc)" class="dghr3cbhl"/><path fill="url(#irjQpbb)" class="dghr3cbhl"/><g filter="url(#iqDTQQc)"><path fill="url(#iWq0Fuf)" class="kyll3esht"/></g><path fill="url(#iSNtpLx)" class="kyll3esht"/><path fill="url(#iZ3W2te)" class="kyll3esht"/><path fill="url(#ibED2qe)" class="kyll3esht"/><path fill="url(#iZuRwBd)" class="kyll3esht"/><g filter="url(#i57tdyd)"><path class="q20a69bld"/></g><g filter="url(#itYIIDe)"><path fill="url(#ixSwzHd)" class="o6r_5sbre"/><path fill="url(#ivXTUGd)" class="o6r_5sbre"/><path fill="url(#iTOtfmd)" class="o6r_5sbre"/><path fill="url(#ixteYCd)" class="o6r_5sbre"/></g><g filter="url(#iRaJ59b)"><path stroke="url(#ibD8rCe)" class="a8itbym5e"/></g><path fill="url(#iTfP3Fb)" class="ugn940b7l"/><g filter="url(#iuOUnqM)"><path fill="url(#i077hGD)" class="iy9e97u6v"/><path fill="url(#iYqCqZE)" class="iy9e97u6v"/><path fill="url(#iNFGAQH)" class="iy9e97u6v"/><path fill="url(#iGrHusb)" class="iy9e97u6v"/><path fill="url(#i62VSfc)" class="iy9e97u6v"/></g><g filter="url(#iNJd0Cc)"><path class="i2ggaxb0k"/></g><g filter="url(#iBXbCUc)"><path class="ex1dpab_x"/></g><g filter="url(#idDOPob)"><path fill="url(#ipePJve)" class="xxat7ab-j"/><path fill="url(#iSIwHGb)" class="xxat7ab-j"/></g><g filter="url(#iLFxJub)"><path fill="url(#iAsZ8iA)" class="v-c_8zbvh"/><path fill="url(#iX5byac)" class="v-c_8zbvh"/><path fill="url(#iRbTHDc)" class="v-c_8zbvh"/><path fill="url(#i8Vbq7d)" class="v-c_8zbvh"/><path fill="url(#isVRNId)" class="v-c_8zbvh"/></g><path class="ua4s2ibqm"/><path fill="url(#iHzUrGe)" class="rrsxzz9zh"/><path class="tq6iimski"/><g filter="url(#iJf261b)"><path class="ybeja_bvi"/><path fill="url(#i6JQxNi)" class="sf9us26hw"/></g><g filter="url(#i9Ps03d)"><path fill="url(#iO40F3b)" class="a9id4uyil"/></g><path class="fv5ej8bvp"/><path fill="url(#isngHQc)" class="km8noybjp"/><path class="v8oo64bhk"/><g filter="url(#iUtjDeb)"><path fill="url(#i8PII9d)" class="kpnd49b5v"/></g><g filter="url(#ibnPflc)"><ellipse transform="rotate(-27.914 11.426 16.5)" class="ik0szwbtf"/><ellipse fill="url(#iSn8tXd)" transform="rotate(-27.914 11.426 16.5)" class="kf1aqtbpe"/></g><path fill="url(#iEPdLHe)" class="cpq24fb_l"/><path fill="url(#iTWTCkc)" class="cpq24fb_l"/><path fill="url(#i9Mi9Hc)" class="cpq24fb_l"/><path fill="url(#iZvAqCe)" class="hwrx1bk3v"/><path fill="url(#izwJ0ic)" class="hwrx1bk3v"/><g filter="url(#ivWefTd)"><path class="b6ooh3pwa"/></g><g filter="url(#iHupHfd)"><path class="ybuckvbnb"/></g><g filter="url(#iLHuDJe)"><path class="glvezj19g"/></g><g filter="url(#iKxXGBz)"><path class="jfddrobyw"/></g><defs><radialGradient id="iefDlpe" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 5.258 20.422)scale(6.07867 7.22099)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="xitcw8bap"/><stop offset="1" class="v2o3hnbel"/></radialGradient><radialGradient id="i13DFbi" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 .75 -.63714 .46458 24.953 20.643)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iGN15oc" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 5 -2.27273 1.07954 5.656 20.361)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="irjQpbb" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 1.85937 -1.63106 .52084 6.89 20.346)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iWq0Fuf" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.235 18.387)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iZ3W2te" cx="0" cy="0" r="1" gradientTransform="matrix(-2.131 24.16843 -20.01435 -1.76472 18.948 7.362)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g1wxybbrb"/><stop offset=".971" class="gej3nhzpp"/></radialGradient><radialGradient id="ibED2qe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 3.09375 0 20.563 16.299)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="qtwfj5bch"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="iZuRwBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.5 2.72059 -.034 11.75 16.486)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="yq9cl_lgn"/><stop offset="1" class="sw1t1obly"/></radialGradient><radialGradient id="ibD8rCe" cx="0" cy="0" r="1" gradientTransform="matrix(.64725 -1.1549 3.3608 1.88353 13.9 24.52)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iTfP3Fb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 16 24.986)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iYqCqZE" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.25 15.438)" gradientUnits="userSpaceOnUse"><stop class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iNFGAQH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 25.063 15.438)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iGrHusb" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 12.172 -.311)scale(6.48857 3.45559)" gradientUnits="userSpaceOnUse"><stop class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="i62VSfc" cx="0" cy="0" r="1" gradientTransform="matrix(1.68751 2.75 -6.3677 3.90748 14.312 .768)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="ipePJve" cx="0" cy="0" r="1" gradientTransform="matrix(-7.09766 2.56091 -.71276 -1.97545 16.473 3.456)" gradientUnits="userSpaceOnUse"><stop class="b6ai19bel"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iSIwHGb" cx="0" cy="0" r="1" gradientTransform="matrix(6 -9.5 10.52499 6.64735 5.875 12.33)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iAsZ8iA" cx="0" cy="0" r="1" gradientTransform="matrix(6.3125 1.49307 -.57258 2.42079 22.75 5.62)" gradientUnits="userSpaceOnUse"><stop class="da8sh5f1a"/><stop offset="1" class="lguy1wbep"/></radialGradient><radialGradient id="iX5byac" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.872 -.26)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iRbTHDc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.406 13.645)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="i8Vbq7d" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.15 4.176)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="isVRNId" cx="0" cy="0" r="1" gradientTransform="matrix(-.21876 .71543 -3.27084 -1.00012 22.438 5.168)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iHzUrGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.068 16.68)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i6JQxNi" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.944 3.608)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isngHQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.932 16.68)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iSn8tXd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.11 2.934)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTWTCkc" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.29 24.579)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="i9Mi9Hc" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.281 17.72)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="izwJ0ic" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -3.89 11.048)scale(3.94637 3.87964)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="iqDTQQc" width="19.805" height="23.21" x="6.56" y="6.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_61"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_1800_61" result="effect2_innerShadow_1800_61"/></filter><filter id="i57tdyd" width="5.5" height="7.407" x="12.864" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".5"/></filter><filter id="itYIIDe" width="3.7" height="5.607" x="14.15" y="16.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".05"/></filter><filter id="iRaJ59b" width="6.5" height="2.5" x="12.75" y="22.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".05"/></filter><filter id="iuOUnqM" width="24" height="15.148" x="4" y="1.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_61"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_1800_61" result="effect2_innerShadow_1800_61"/></filter><filter id="iNJd0Cc" width="4.274" height="2.047" x="18.963" y="11.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_61"/></filter><filter id="iBXbCUc" width="4.274" height="2.019" x="9.163" y="11.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_1800_61"/></filter><filter id="idDOPob" width="12.344" height="11.239" x="4.629" y="2.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".25"/></filter><filter id="iLFxJub" width="12.094" height="10.965" x="15.504" y="3.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".25"/></filter><filter id="iJf261b" width="1.294" height="1.125" x="18.786" y="15.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".05"/></filter><filter id="i9Ps03d" width="1.316" height="1.357" x="20.438" y="16.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".1"/></filter><filter id="iUtjDeb" width="1.493" height="1.594" x="12.155" y="16.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".1"/></filter><filter id="ibnPflc" width="1.529" height="1.141" x="10.661" y="15.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".05"/></filter><filter id="ivWefTd" width="2.045" height="4.004" x="4.969" y="15.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".125"/></filter><filter id="iHupHfd" width="2.265" height="4.049" x="25.001" y="15.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".125"/></filter><filter id="iLHuDJe" width="3.836" height="1.515" x="9.336" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".125"/></filter><filter id="iKxXGBz" width="3.836" height="1.515" x="19.178" y="11.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_1800_61" stdDeviation=".125"/></filter><linearGradient id="iSNtpLx" x1="25.615" x2="17.5" y1="21.53" y2="21.53" gradientUnits="userSpaceOnUse"><stop class="aflrgacjk"/><stop offset="1" class="pp1jb50uj"/></linearGradient><linearGradient id="ixSwzHd" x1="16" x2="17.594" y1="19.932" y2="19.932" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="ivXTUGd" x1="14" x2="16.003" y1="19.642" y2="19.753" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iTOtfmd" x1="16" x2="16" y1="20.676" y2="22.264" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="ixteYCd" x1="16" x2="16" y1="16.485" y2="17.267" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="i077hGD" x1="26" x2="7.125" y1="7.83" y2="7.83" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iO40F3b" x1="21.519" x2="20.934" y1="16.78" y2="17.14" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8PII9d" x1="13.319" x2="12.734" y1="16.78" y2="17.14" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEPdLHe" x1="28" x2="25.75" y1="16.83" y2="20.887" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iZvAqCe" x1="5.094" x2="7.813" y1="18.142" y2="17.905" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person" /></template>
<style>
.a8itbym5e {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.452 23.109h-.001a.36.36 0 0 0-.429.074a.33.33 0 0 0-.036.424A3.6 3.6 0 0 0 16 25.217a3.6 3.6 0 0 0 3.015-1.61a.334.334 0 0 0-.037-.428a.36.36 0 0 0-.429-.07a5.5 5.5 0 0 1-2.549.604c-.934 0-1.812-.22-2.548-.604Z");
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.a9id4uyil {
  d: path("M21.554 17.235a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.aflrgacjk {
  stop-color: var(--svg-color--ffd93b, #FFD93B);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.b6ai19bel {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
}

.b6ooh3pwa {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M6.609 16.154a1.782 1.782 0 0 0 .155 3.504a146 146 0 0 1-.155-3.504");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cpq24fb_l {
  d: path("M25.177 20.887c.122-1.984.24-3.965.344-5.95a3 3 0 0 1-.344 5.95");
}

.da8sh5f1a {
  stop-color: var(--svg-color--ffe137, #FFE137);
}

.dghr3cbhl {
  d: path("M6.937 20.718a3.06 3.06 0 0 1-1.687-.576v1.736c0 1.665.992 3.149 2.5 3.764a7.6 7.6 0 0 1-.645-2.2z");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ex1dpab_x {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M9.64 12.629a5.17 5.17 0 0 1 3.242-.67a.517.517 0 0 1-.125 1.026a4.14 4.14 0 0 0-2.585.531a3 3 0 0 0-.171.112l-.005.003a.517.517 0 0 1-.633-.817z");
}

.ft5dv1b6b {
  fill: none;
}

.fv5ej8bvp {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.542 15.283c-1.217 0-2.246.84-2.526 1.974a.51.51 0 0 0 .5.635h4.16a.43.43 0 0 0 .423-.506a2.61 2.61 0 0 0-2.557-2.103");
}

.g1wxybbrb {
  stop-color: var(--svg-color--d77869, #D77869);
  stop-opacity: 0;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gej3nhzpp {
  stop-color: var(--svg-color--d77869, #D77869);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glvezj19g {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.71 13.15c.48-.344 1.674-.948 3.087-.71");
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hwrx1bk3v {
  d: path("M6.577 14.922a3 3 0 0 0 .258 5.966c-.12-1.992-.22-3.973-.258-5.966");
}

.i2ggaxb0k {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M22.96 12.832c-.327-.284-.707-.586-1.282-.767c-.567-.179-1.278-.226-2.26-.106a.517.517 0 0 0 .125 1.026c.897-.11 1.446-.053 1.824.066c.37.117.62.305.913.56a.517.517 0 1 0 .68-.779");
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ik0szwbtf {
  cx: 11.426px;
  cy: 16.501px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.iy9e97u6v {
  d: path("M25.052 6.002c.959.33 1.819 1 2.363 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.504 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.146-2.995c-.02-1.43-1.147-2.61-2.57-2.67h-2.611a4.52 4.52 0 0 1-4.124-2.69a1.24 1.24 0 0 0-1.147-.78H12.79c-3.441 0-6.23 2.82-6.23 6.3l.057 2.867c-.473.07-.968.227-1.342.491v-2.238c0-.58-.178-1.15-.505-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.423-2.1a5 5 0 0 0 2.58-2.07a4.34 4.34 0 0 1 3.68-2.05c.603 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.7-.35c1.573 0 2.947.85 3.709 2.11c.573.95 1.473 1.64 2.521 2");
}

.jfddrobyw {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.64 13.064c-.48-.343-1.674-.948-3.087-.71");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kf1aqtbpe {
  cx: 11.426px;
  cy: 16.501px;
  rx: 0.726px;
  ry: 0.368px;
}

.km8noybjp {
  d: path("M11.928 15.79a1.664 1.664 0 0 0-1.603 2.102h3.214q.059-.213.06-.438a1.675 1.675 0 0 0-1.67-1.664");
}

.kpnd49b5v {
  d: path("M13.448 17.258c0-.537-.437-.896-.555-1.004l-.538.52l.331.673z");
}

.kyll3esht {
  d: path("M7.004 23.542a7.3 7.3 0 0 0 7.245 6.35h3.517a7.3 7.3 0 0 0 7.245-6.35c.22-3.512.44-7.01.604-10.52c-.02-1.43-1.147-2.61-2.57-2.67h-2.612a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.147-.78H12.79c-3.441 0-6.23 2.82-6.23 6.3c0 3.47.217 6.882.444 10.36");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lguy1wbep {
  stop-color: var(--svg-color--ffe137, #FFE137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o6r_5sbre {
  d: path("m15.287 17.055l-.99 3.427c-.203.705.282 1.41.97 1.41h1.466c.688 0 1.173-.715.97-1.41l-.99-3.427c-.213-.76-1.203-.76-1.426 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp1jb50uj {
  stop-color: var(--svg-color--ffd93b, #FFD93B);
  stop-opacity: 0;
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q20a69bld {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.094 17.42l-1.184 3.427c-.202.705.283 1.41.97 1.41h1.467c.687 0 1.173-.715.97-1.41l-.99-3.427c-.213-.76-1.01-.76-1.233 0");
}

.qtwfj5bch {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rrsxzz9zh {
  d: path("M20.072 15.79a1.664 1.664 0 0 1 1.603 2.102h-3.214a1.7 1.7 0 0 1-.06-.438a1.67 1.67 0 0 1 1.671-1.664");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.sf9us26hw {
  d: path("M19.95 16.142c.118.158-.13.351-.411.562c-.282.21-.491.359-.61.2c-.118-.158.014-.457.296-.668c.282-.21.606-.253.725-.094");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.sw1t1obly {
  stop-color: var(--svg-color--ef9330, #EF9330);
  stop-opacity: 0;
}

.tq6iimski {
  fill: var(--svg-color--000, #000);
  d: path("M19.12 17.454c0-.53.423-.953.952-.953c.53 0 .953.423.953.953a.94.94 0 0 1-.106.438h-1.686a.86.86 0 0 1-.114-.438");
}

.u0sztvvta {
  d: path("M25.064 20.718a3.06 3.06 0 0 0 1.686-.576v1.736c0 1.665-.992 3.149-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.ua4s2ibqm {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.458 15.283c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.635h-4.159a.43.43 0 0 1-.424-.506a2.606 2.606 0 0 1 2.557-2.103");
}

.ugn940b7l {
  d: path("M16 23.788a5.6 5.6 0 0 1-2.583-.613c-.255-.13-.53.158-.369.39A3.53 3.53 0 0 0 16 25.142a3.53 3.53 0 0 0 2.952-1.577c.16-.241-.114-.52-.369-.39a5.6 5.6 0 0 1-2.583.613");
}

.v-c_8zbvh {
  d: path("m25.719 14.205l-.055-1.177c-.02-1.424-1.196-2.598-2.62-2.658h-2.61a4.51 4.51 0 0 1-3.96-2.348s-.382-.885-.466-2.18c-.066-1 .84-1.718 1.834-1.587c2.066.274 4.934.919 6.905 2.205c3.253 2.121 2.683 5.944.971 7.745");
}

.v2o3hnbel {
  stop-color: var(--svg-color--e4803e, #E4803E);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v8oo64bhk {
  fill: var(--svg-color--000, #000);
  d: path("M12.881 17.454a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.038.31.106.438h1.687a.95.95 0 0 0 .113-.438");
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xxat7ab-j {
  d: path("M16.433 7.918a5 5 0 0 1-.123-.256a1.24 1.24 0 0 0-1.147-.78H12.79c-3.441 0-6.23 2.82-6.23 6.3v.513c-.634-.482-1.431-1.5-1.431-3.146c0-1.999 1.457-3.009 2.387-3.653c.263-.182.483-.335.617-.472l.185-.196c.652-.69 1.813-1.922 3.84-2.46c1.3-.345 2.62-.349 3.512-.269c.47.042.803.45.803.923v3.47z");
}

.ybeja_bvi {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.95 16.142c.118.158-.13.351-.411.562c-.282.21-.491.359-.61.2c-.118-.158.014-.457.296-.668c.282-.21.606-.253.725-.094");
}

.ybuckvbnb {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M25.25 19.674q.11-1.774.207-3.549a1.781 1.781 0 0 1-.206 3.549");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yq9cl_lgn {
  stop-color: var(--svg-color--ef9330, #EF9330);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
