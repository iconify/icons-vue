<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNFEV8c)" class="aib3jmbbm"/><path fill="url(#izmz3Ob)" class="aib3jmbbm"/><path fill="url(#iskOlze)" class="uveufac6n"/><path fill="url(#it6raod)" class="uveufac6n"/><g filter="url(#i11s8Id)"><path fill="url(#iUufkqb)" class="que_gyesm"/></g><path fill="url(#iaPhbed)" class="que_gyesm"/><path fill="url(#iTLBUwb)" class="que_gyesm"/><path fill="url(#i5wZ9Vd)" class="que_gyesm"/><path fill="url(#iECvVKZ)" class="que_gyesm"/><path fill="url(#iKg1Txy)" class="que_gyesm"/><g filter="url(#iOKUIWb)"><path class="qh1j3tg7q"/></g><g filter="url(#i7JuCEd)"><path fill="url(#i4zyfYd)" class="ycyqvjfog"/><path fill="url(#iYbQoUC)" class="ycyqvjfog"/><path fill="url(#iQZjnye)" class="ycyqvjfog"/><path fill="url(#iB8WOXg)" class="ycyqvjfog"/></g><g filter="url(#iRhP0Ms)"><path stroke="url(#iFfa2he)" class="t6_40babe"/></g><path fill="url(#i4hUped)" class="lhh8apb3n"/><g filter="url(#ipKGh6b)"><path fill="url(#im0LO5Z)" class="xnxpn1bow"/><path fill="url(#irN1M5d)" class="xnxpn1bow"/><path fill="url(#iTt5i3c)" class="xnxpn1bow"/><path fill="url(#ihKKIXb)" class="xnxpn1bow"/><path fill="url(#i36kZtb)" class="xnxpn1bow"/></g><g filter="url(#iprJIwc)"><path class="ir7kpnb3u"/></g><g filter="url(#ikzhXhc)"><path class="fzxn01b9i"/></g><g filter="url(#ihzrype)"><path fill="url(#iVf4cnd)" class="d046ilbmx"/><path fill="url(#iYHMHRb)" class="d046ilbmx"/></g><g filter="url(#ixqqaIc)"><path fill="url(#ifLnD8v)" class="vees0xbqk"/><path fill="url(#i5PLhCd)" class="vees0xbqk"/><path fill="url(#iI0GF8d)" class="vees0xbqk"/><path fill="url(#i6qM76z)" class="vees0xbqk"/><path fill="url(#iw3fkLe)" class="vees0xbqk"/></g><path class="gz2x3oecy"/><path fill="url(#iOUfeKd)" class="vbauy8beq"/><path class="fxut9jb9x"/><g filter="url(#imJFy2b)"><path class="yusxt287n"/><path fill="url(#i52w8kc)" class="y10v_ybhn"/></g><g filter="url(#iHCYaLe)"><path fill="url(#iiYhpVc)" class="uqf4a6koj"/></g><path class="s-vq0zbku"/><path fill="url(#iREXYfO)" class="rmq5es9yb"/><path class="t2kq2vbzr"/><g filter="url(#ixNU36b)"><path fill="url(#i6lH32d)" class="noiry72ij"/></g><g filter="url(#iAmHQdb)"><ellipse transform="rotate(-27.914 11.435 16.711)" class="ogo1c7oad"/><ellipse fill="url(#iV5LwPc)" transform="rotate(-27.914 11.435 16.711)" class="anol1zn4w"/></g><path fill="url(#i9Tw5Yb)" class="gh-o9-brl"/><path fill="url(#ikr7BUt)" class="gh-o9-brl"/><path fill="url(#ilbrkxb)" class="gh-o9-brl"/><path fill="url(#iuaCgPb)" class="tu4cljr2t"/><path fill="url(#i1zu5uU)" class="tu4cljr2t"/><g filter="url(#iMeCGwd)"><path class="e8z8p_yua"/></g><g filter="url(#ik0btse)"><path class="caqn71bqb"/></g><g filter="url(#igxBsze)"><path class="mf9uh0bgx"/></g><g filter="url(#iE1zrvd)"><path class="v8c8z9blb"/></g><defs><radialGradient id="iNFEV8c" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 5.18 20.53)scale(6.07867 7.22099)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="bwfxpzp0c"/><stop offset="1" class="cqf-ohbhv"/></radialGradient><radialGradient id="izmz3Ob" cx="0" cy="0" r="1" gradientTransform="matrix(.54688 .75 -.63714 .46458 24.962 20.853)" gradientUnits="userSpaceOnUse"><stop class="dhmh3e1ol"/><stop offset="1" class="rz5bd0b6s"/></radialGradient><radialGradient id="iskOlze" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 5 -2.27273 1.07954 5.665 20.571)" gradientUnits="userSpaceOnUse"><stop class="kpym4yewg"/><stop offset="1" class="t51tzvbuk"/></radialGradient><radialGradient id="it6raod" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 1.85937 -1.63106 .52084 6.9 20.556)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="s-wuddcax"/><stop offset="1" class="htl_mzbwg"/></radialGradient><radialGradient id="iUufkqb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.244 18.598)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iTLBUwb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.131 24.16843 -20.01435 -1.76472 18.957 7.572)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g1wxybbrb"/><stop offset=".971" class="gej3nhzpp"/></radialGradient><radialGradient id="i5wZ9Vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 3.09375 0 20.571 16.509)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="qtwfj5bch"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="iECvVKZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.5 2.72059 -.034 11.759 16.696)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="yq9cl_lgn"/><stop offset="1" class="sw1t1obly"/></radialGradient><radialGradient id="iKg1Txy" cx="0" cy="0" r="1" gradientTransform="matrix(3.71585 -5.1531 1.1623 .83812 5.831 11.724)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="isc_1j8cq"/><stop offset="1" class="ib736acio"/></radialGradient><radialGradient id="iFfa2he" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 28.058 .496)scale(1.32391 3.85262)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i4hUped" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 16.009 25.196)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="irN1M5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.259 15.648)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="ynmqlsboi"/><stop offset="1" class="ipxdzpbtr"/></radialGradient><radialGradient id="iTt5i3c" cx="0" cy="0" r="1" gradientTransform="scale(12 6.77276)rotate(-90 2.2 .11)" gradientUnits="userSpaceOnUse"><stop class="nerkoubdj"/><stop offset="1" class="t52ha8bdg"/></radialGradient><radialGradient id="ihKKIXb" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 12.196 -.207)scale(6.48857 3.45559)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="i36kZtb" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 2.625 -6.38151 7.90093 8.821 3.434)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="l_pokqbdh"/><stop offset="1" class="y7-q8z4gm"/></radialGradient><radialGradient id="iVf4cnd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.13156 2.93075 -.8157 -2.2632 16.481 3.667)" gradientUnits="userSpaceOnUse"><stop class="hr217vhio"/><stop offset="1" class="o3acwp2gg"/></radialGradient><radialGradient id="iYHMHRb" cx="0" cy="0" r="1" gradientTransform="rotate(-58.775 14.604 1.557)scale(11.9254 13.2121)" gradientUnits="userSpaceOnUse"><stop class="twinuccla"/><stop offset=".233" class="n78pd-b5i"/><stop offset="1" class="age677bqv"/></radialGradient><radialGradient id="ifLnD8v" cx="0" cy="0" r="1" gradientTransform="matrix(6.3125 1.49307 -.57258 2.42079 22.759 5.83)" gradientUnits="userSpaceOnUse"><stop class="vsbibr_ed"/><stop offset="1" class="zmahyob7y"/></radialGradient><radialGradient id="i5PLhCd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.937 -.157)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="w-6a5tbqx"/><stop offset="1" class="dgs1e68st"/></radialGradient><radialGradient id="iI0GF8d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.415 13.855)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="j4tu-1b_q"/><stop offset="1" class="w5r4ae2jv"/></radialGradient><radialGradient id="i6qM76z" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.141 4.281)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="mbtrbz0eb"/><stop offset="1" class="pyp_qyqhv"/></radialGradient><radialGradient id="iw3fkLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.21876 .71543 -3.27084 -1.00012 22.446 5.38)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="ota_qabww"/><stop offset="1" class="wuchx3byb"/></radialGradient><radialGradient id="iOUfeKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.077 16.89)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i52w8kc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14 3.71)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iREXYfO" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.94 16.89)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iV5LwPc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.218 3.034)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikr7BUt" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.156 24.69)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ilbrkxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.29 17.93)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i1zu5uU" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -3.971 11.157)scale(3.94637 3.87964)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="i11s8Id" width="19.805" height="23.21" x="6.569" y="7.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2168"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2168" result="effect2_innerShadow_3930_2168"/></filter><filter id="iOKUIWb" width="5.183" height="7.407" x="12.872" y="16.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".5"/></filter><filter id="i7JuCEd" width="3.7" height="5.607" x="14.159" y="16.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".05"/></filter><filter id="iRhP0Ms" width="6.5" height="2.5" x="12.759" y="23.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".05"/></filter><filter id="ipKGh6b" width="24" height="15.148" x="4.009" y="1.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.741176 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2168"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2168" result="effect2_innerShadow_3930_2168"/></filter><filter id="iprJIwc" width="4.274" height="2.047" x="18.972" y="11.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.258824 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2168"/></filter><filter id="ikzhXhc" width="4.274" height="2.019" x="9.172" y="11.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.258824 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2168"/></filter><filter id="ihzrype" width="12.344" height="11.239" x="4.638" y="3.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".25"/></filter><filter id="ixqqaIc" width="12.094" height="10.965" x="15.513" y="3.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".25"/></filter><filter id="imJFy2b" width="1.294" height="1.125" x="18.795" y="16.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".05"/></filter><filter id="iHCYaLe" width="1.316" height="1.357" x="20.447" y="16.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".1"/></filter><filter id="ixNU36b" width="1.493" height="1.594" x="12.164" y="16.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".1"/></filter><filter id="iAmHQdb" width="1.529" height="1.141" x="10.67" y="16.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".05"/></filter><filter id="iMeCGwd" width="2.045" height="4.004" x="4.978" y="16.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".125"/></filter><filter id="ik0btse" width="2.101" height="3.72" x="25.017" y="16.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".125"/></filter><filter id="igxBsze" width="3.836" height="1.515" x="9.345" y="12.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".125"/></filter><filter id="iE1zrvd" width="3.836" height="1.515" x="19.187" y="12.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2168" stdDeviation=".125"/></filter><linearGradient id="iaPhbed" x1="25.624" x2="16.096" y1="21.74" y2="21.74" gradientUnits="userSpaceOnUse"><stop class="aflrgacjk"/><stop offset="1" class="pp1jb50uj"/></linearGradient><linearGradient id="i4zyfYd" x1="16.009" x2="17.602" y1="20.143" y2="20.143" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iYbQoUC" x1="14.009" x2="16.011" y1="19.853" y2="19.963" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iQZjnye" x1="16.009" x2="16.009" y1="20.886" y2="22.474" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iB8WOXg" x1="16.009" x2="16.009" y1="16.696" y2="17.478" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="im0LO5Z" x1="26.009" x2="7.134" y1="8.04" y2="8.04" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="gz4sdm9gk"/></linearGradient><linearGradient id="iiYhpVc" x1="21.527" x2="20.942" y1="16.99" y2="17.35" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6lH32d" x1="13.328" x2="12.742" y1="16.99" y2="17.35" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9Tw5Yb" x1="28.009" x2="25.759" y1="17.04" y2="21.098" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iuaCgPb" x1="5.103" x2="7.821" y1="18.353" y2="18.115" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-blonde-hair" /></template>
<style>
.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
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

.age677bqv {
  stop-color: var(--svg-color--e8b391, #E8B391);
  stop-opacity: 0;
}

.aib3jmbbm {
  d: path("M25.072 20.928a3.06 3.06 0 0 0 1.687-.575v1.735c0 1.666-.992 3.15-2.5 3.765a7.6 7.6 0 0 0 .645-2.2z");
}

.anol1zn4w {
  cx: 11.435px;
  cy: 16.711px;
  rx: 0.726px;
  ry: 0.368px;
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bwfxpzp0c {
  stop-color: var(--svg-color--ffe1b0, #FFE1B0);
}

.caqn71bqb {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M25.267 19.725q.098-1.61.187-3.22a1.617 1.617 0 0 1-.187 3.22");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqf-ohbhv {
  stop-color: var(--svg-color--e0a598, #E0A598);
}

.d046ilbmx {
  d: path("M16.442 8.128a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.147-.78h-2.373c-3.442 0-6.23 2.82-6.23 6.3v.513c-.634-.483-1.431-1.5-1.431-3.147c0-1.998 1.457-3.008 2.387-3.653c.262-.182.483-.334.616-.472l.186-.195c.652-.692 1.813-1.923 3.84-2.461c1.3-.345 2.62-.348 3.512-.269c.47.042.802.45.802.924v3.47z");
}

.dgs1e68st {
  stop-color: var(--svg-color--f0c297, #F0C297);
  stop-opacity: 0;
}

.dhmh3e1ol {
  stop-color: var(--svg-color--f1b78d, #F1B78D);
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e8z8p_yua {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M6.617 16.365a1.782 1.782 0 0 0 .156 3.503c-.065-1.168-.12-2.335-.156-3.503");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ft5dv1b6b {
  fill: none;
}

.fxut9jb9x {
  fill: var(--svg-color--000, #000);
  d: path("M19.128 17.664c0-.53.423-.953.953-.953s.953.424.953.953a.94.94 0 0 1-.106.439H19.24a.86.86 0 0 1-.113-.439");
}

.fzxn01b9i {
  fill: var(--svg-color--96602e, #96602E);
  d: path("M9.65 12.839a5.17 5.17 0 0 1 3.242-.67a.517.517 0 0 1-.126 1.026a4.14 4.14 0 0 0-2.585.531a3 3 0 0 0-.171.112l-.005.004a.517.517 0 0 1-.634-.818z");
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
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

.gej3nhzpp {
  stop-color: var(--svg-color--d77869, #D77869);
}

.gh-o9-brl {
  d: path("M25.185 21.098c.123-1.985.241-3.966.344-5.95a3 3 0 0 1-.344 5.95");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gz2x3oecy {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.467 15.493c1.217 0 2.246.84 2.526 1.974a.51.51 0 0 1-.5.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.557-2.103");
}

.gz4sdm9gk {
  stop-color: var(--svg-color--efcb95, #EFCB95);
}

.hr217vhio {
  stop-color: var(--svg-color--fff9b8, #FFF9B8);
}

.htl_mzbwg {
  stop-color: var(--svg-color--d69b78, #D69B78);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ib736acio {
  stop-color: var(--svg-color--c77a1c, #C77A1C);
  stop-opacity: 0;
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ipxdzpbtr {
  stop-color: var(--svg-color--e6b386, #E6B386);
  stop-opacity: 0;
}

.ir7kpnb3u {
  fill: var(--svg-color--96602e, #96602E);
  d: path("M22.968 13.042c-.326-.284-.706-.586-1.282-.767c-.567-.178-1.277-.226-2.26-.106a.517.517 0 1 0 .126 1.026c.897-.11 1.446-.052 1.824.067c.37.116.62.305.913.56a.517.517 0 1 0 .68-.78");
}

.isc_1j8cq {
  stop-color: var(--svg-color--c77a1c, #C77A1C);
}

.j4tu-1b_q {
  stop-color: var(--svg-color--eab68a, #EAB68A);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.kpym4yewg {
  stop-color: var(--svg-color--f0b78e, #F0B78E);
}

.l_pokqbdh {
  stop-color: var(--svg-color--e0ca93, #E0CA93);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lhh8apb3n {
  d: path("M16.009 23.998a5.6 5.6 0 0 1-2.583-.612c-.256-.13-.53.158-.37.39a3.53 3.53 0 0 0 2.953 1.577a3.53 3.53 0 0 0 2.952-1.578c.16-.24-.114-.52-.37-.39a5.6 5.6 0 0 1-2.582.613");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbtrbz0eb {
  stop-color: var(--svg-color--e6b383, #E6B383);
  stop-opacity: 0;
}

.mf9uh0bgx {
  stroke: var(--svg-color--9d6840, #9D6840);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.72 13.36c.479-.343 1.673-.948 3.086-.71");
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
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

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.noiry72ij {
  d: path("M13.457 17.469c0-.538-.437-.897-.555-1.005l-.538.52l.33.674z");
}

.o3acwp2gg {
  stop-color: var(--svg-color--fff9b8, #FFF9B8);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ogo1c7oad {
  cx: 11.435px;
  cy: 16.711px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.ota_qabww {
  stop-color: var(--svg-color--fff1b2, #FFF1B2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp1jb50uj {
  stop-color: var(--svg-color--ffd93b, #FFD93B);
  stop-opacity: 0;
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.pyp_qyqhv {
  stop-color: var(--svg-color--e6b383, #E6B383);
}

.qh1j3tg7q {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m14.991 17.63l-1.076 3.428c-.184.705.257 1.41.882 1.41h1.334c.625 0 1.067-.716.883-1.41l-.902-3.428c-.193-.759-.918-.759-1.12 0");
}

.qtwfj5bch {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
}

.que_gyesm {
  d: path("M7.013 23.753a7.3 7.3 0 0 0 7.245 6.35h3.517a7.3 7.3 0 0 0 7.245-6.35c.22-3.512.44-7.01.604-10.52c-.02-1.43-1.147-2.61-2.571-2.67h-2.61a4.52 4.52 0 0 1-4.124-2.69a1.24 1.24 0 0 0-1.147-.78h-2.373c-3.442 0-6.23 2.82-6.23 6.3c0 3.469.217 6.882.444 10.36");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rmq5es9yb {
  d: path("M11.937 16a1.664 1.664 0 0 0-1.604 2.103h3.215q.059-.214.06-.439A1.675 1.675 0 0 0 11.937 16");
}

.rz5bd0b6s {
  stop-color: var(--svg-color--f1b78d, #F1B78D);
  stop-opacity: 0;
}

.s-vq0zbku {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.551 15.493c-1.218 0-2.246.84-2.526 1.974a.51.51 0 0 0 .5.636h4.159a.43.43 0 0 0 .424-.507a2.61 2.61 0 0 0-2.557-2.103");
}

.s-wuddcax {
  stop-color: var(--svg-color--d69b78, #D69B78);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.sw1t1obly {
  stop-color: var(--svg-color--ef9330, #EF9330);
  stop-opacity: 0;
}

.t2kq2vbzr {
  fill: var(--svg-color--000, #000);
  d: path("M12.89 17.664a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.038.31.106.439h1.686a.94.94 0 0 0 .114-.44");
}

.t51tzvbuk {
  stop-color: var(--svg-color--d9988c, #D9988C);
}

.t52ha8bdg {
  stop-color: var(--svg-color--fed69f, #FED69F);
  stop-opacity: 0;
}

.t6_40babe {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.46 23.32v-.001a.36.36 0 0 0-.43.074a.33.33 0 0 0-.035.424a3.6 3.6 0 0 0 3.014 1.61a3.6 3.6 0 0 0 3.014-1.61a.334.334 0 0 0-.037-.428a.36.36 0 0 0-.428-.07a5.5 5.5 0 0 1-2.55.604c-.934 0-1.811-.22-2.548-.604Z");
}

.tu4cljr2t {
  d: path("M6.586 15.132a3 3 0 0 0 .258 5.966a145 145 0 0 1-.258-5.966");
}

.twinuccla {
  stop-color: var(--svg-color--cc9571, #CC9571);
}

.uqf4a6koj {
  d: path("M21.563 17.445a1.57 1.57 0 0 0-.431-.863l-.485.532l.219.425z");
}

.uveufac6n {
  d: path("M6.945 20.928a3.06 3.06 0 0 1-1.686-.575v1.735c0 1.666.992 3.15 2.5 3.765a7.6 7.6 0 0 1-.645-2.2z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v8c8z9blb {
  stroke: var(--svg-color--9d6840, #9D6840);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.648 13.275c-.48-.344-1.674-.949-3.086-.711");
}

.vbauy8beq {
  d: path("M20.08 16a1.664 1.664 0 0 1 1.604 2.103H18.47a1.7 1.7 0 0 1-.06-.439A1.67 1.67 0 0 1 20.08 16");
}

.vees0xbqk {
  d: path("m25.727 14.415l-.054-1.177c-.02-1.423-1.196-2.598-2.62-2.658h-2.61a4.51 4.51 0 0 1-3.96-2.348s-.383-.885-.467-2.18c-.065-1 .84-1.718 1.835-1.586c2.066.273 4.934.918 6.905 2.204c3.253 2.121 2.683 5.945.971 7.745");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vsbibr_ed {
  stop-color: var(--svg-color--ffffc5, #FFFFC5);
}

.w-6a5tbqx {
  stop-color: var(--svg-color--f0c297, #F0C297);
}

.w5r4ae2jv {
  stop-color: var(--svg-color--eab68a, #EAB68A);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.wuchx3byb {
  stop-color: var(--svg-color--fff1b2, #FFF1B2);
  stop-opacity: 0;
}

.xnxpn1bow {
  d: path("M25.06 6.213c.96.33 1.82 1 2.364 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.505 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.147-2.995c-.02-1.43-1.147-2.61-2.571-2.67h-2.61a4.52 4.52 0 0 1-4.124-2.69a1.24 1.24 0 0 0-1.147-.78h-2.373c-3.442 0-6.23 2.82-6.23 6.3l.057 2.866c-.474.07-.968.228-1.343.491v-2.237c0-.58-.178-1.15-.504-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.423-2.1a5 5 0 0 0 2.58-2.07a4.34 4.34 0 0 1 3.68-2.05c.602 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.7-.35c1.573 0 2.947.85 3.709 2.11c.573.95 1.473 1.64 2.521 2");
}

.y10v_ybhn {
  d: path("M19.958 16.352c.119.158-.129.352-.41.562c-.282.211-.491.36-.61.2c-.118-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.y7-q8z4gm {
  stop-color: var(--svg-color--e0ca93, #E0CA93);
  stop-opacity: 0;
}

.ycyqvjfog {
  d: path("m15.296 17.265l-.991 3.428c-.202.705.283 1.41.97 1.41h1.467c.687 0 1.173-.716.97-1.41l-.99-3.428c-.213-.759-1.204-.759-1.426 0");
}

.ynmqlsboi {
  stop-color: var(--svg-color--e6b386, #E6B386);
}

.yq9cl_lgn {
  stop-color: var(--svg-color--ef9330, #EF9330);
}

.yusxt287n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.958 16.352c.119.158-.129.352-.41.562c-.282.211-.491.36-.61.2c-.118-.158.014-.457.296-.668c.281-.21.606-.253.724-.094");
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zmahyob7y {
  stop-color: var(--svg-color--ffffc5, #FFFFC5);
  stop-opacity: 0;
}

</style>
