<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iv0qXzd)" class="ol4k0bwog"/><path fill="url(#irLfvdd)" class="ol4k0bwog"/><path fill="url(#iRQ2DHJ)" class="svw3fj76s"/><path fill="url(#irB4U4b)" class="svw3fj76s"/><g filter="url(#ieB9uqe)"><path fill="url(#iVnZEkd)" class="o8swx14tw"/></g><path fill="url(#iuwZ9Jb)" class="o8swx14tw"/><path fill="url(#i49r69c)" class="o8swx14tw"/><path fill="url(#it0tNkc)" class="o8swx14tw"/><path fill="url(#icrDwoe)" class="o8swx14tw"/><path fill="url(#i4UPaLe)" class="o8swx14tw"/><g filter="url(#iTmHxOb)"><path class="a_h7j0ooy"/></g><g filter="url(#iqZ2Ucd)"><path fill="url(#iLX4xme)" class="iums48bis"/><path fill="url(#iryxMUb)" class="iums48bis"/><path fill="url(#in3A2zq)" class="iums48bis"/><path fill="url(#i170Lyd)" class="iums48bis"/></g><g filter="url(#izYgKNe)"><path stroke="url(#iwR9IRP)" class="spk2babjh"/></g><path fill="url(#i9XGmxd)" class="h_oh90w8o"/><g filter="url(#iS8Y8tv)"><path fill="url(#ijs75Mc)" class="fz4t4hgck"/><path fill="url(#iKPKZvc)" class="fz4t4hgck"/><path fill="url(#iUreJsb)" class="fz4t4hgck"/><path fill="url(#iSq6cte)" class="fz4t4hgck"/><path fill="url(#i9Jjmvb)" class="fz4t4hgck"/><path fill="url(#igsVEDu)" class="fz4t4hgck"/></g><g filter="url(#iPdGdqc)"><path class="x_mthd6lb"/></g><g filter="url(#iP7JUWb)"><path class="uiuzuq7ej"/></g><g filter="url(#i3JaUQb)"><path fill="url(#irTQtFc)" class="f5-1tub5g"/><path fill="url(#iLMhUre)" class="f5-1tub5g"/></g><g filter="url(#i7GF27c)"><path fill="url(#iBKjJIb)" class="cova42peu"/><path fill="url(#ieRFTHc)" class="cova42peu"/><path fill="url(#iWGg3ub)" class="cova42peu"/><path fill="url(#iCoSQSb)" class="cova42peu"/><path fill="url(#iCoqbSA)" class="cova42peu"/></g><path class="jgiouvwga"/><path fill="url(#i44PyMd)" class="g5hndsbub"/><path class="ry-qmab6k"/><g filter="url(#ireYiqb)"><path class="wu4l9jjxy"/><path fill="url(#ieZ2AXd)" class="gaj5n3b3e"/></g><g filter="url(#iWDu4td)"><path fill="url(#iEvkpQc)" class="lnv6hpbvc"/></g><path class="bu6bjuduk"/><path fill="url(#iObrMoc)" class="c47ufxwbm"/><path class="nje5f61-e"/><g filter="url(#iaoFVxe)"><path fill="url(#iLiD8Ic)" class="bwuva7blw"/></g><g filter="url(#iMQwEPb)"><ellipse transform="rotate(-27.914 11.426 16.608)" class="py4u3gbdm"/><ellipse fill="url(#iA7qA1b)" transform="rotate(-27.914 11.426 16.608)" class="nyk28ejhn"/></g><path fill="url(#ic1CbBd)" class="p061szbyy"/><path fill="url(#it0pyOr)" class="p061szbyy"/><path fill="url(#iPBJtsi)" class="p061szbyy"/><path fill="url(#iteqi4b)" class="diidobhvb"/><path fill="url(#i3nyTCc)" class="diidobhvb"/><g filter="url(#iRiVOWc)"><path class="f_dhdrb_m"/></g><g filter="url(#ikLamze)"><path class="j-_s4zb6b"/></g><g filter="url(#ia3fEJe)"><path class="wu19-mbwu"/></g><g filter="url(#iqm7KPc)"><path class="y_4gjebjq"/></g><defs><radialGradient id="iv0qXzd" cx="0" cy="0" r="1" gradientTransform="rotate(103.679 5.216 20.476)scale(6.07867 7.22099)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="y-cveupjc"/><stop offset="1" class="bc6pupb0c"/></radialGradient><radialGradient id="irLfvdd" cx="0" cy="0" r="1" gradientTransform="matrix(.54688 .75 -.63714 .46458 24.953 20.75)" gradientUnits="userSpaceOnUse"><stop class="ygff5vfwh"/><stop offset="1" class="m2-9pwbbm"/></radialGradient><radialGradient id="iRQ2DHJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 5 -2.27273 1.07954 5.656 20.469)" gradientUnits="userSpaceOnUse"><stop class="x08e984jt"/><stop offset="1" class="gyp47d6zd"/></radialGradient><radialGradient id="irB4U4b" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 1.85937 -1.63106 .52084 6.89 20.453)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="jg96q12xv"/><stop offset="1" class="yq5y_ab2t"/></radialGradient><radialGradient id="iVnZEkd" cx="0" cy="0" r="1" gradientTransform="matrix(-9.74687 0 0 -17.2421 21.235 18.495)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="i49r69c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.131 24.16843 -20.01435 -1.76472 18.948 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g1wxybbrb"/><stop offset=".971" class="gej3nhzpp"/></radialGradient><radialGradient id="it0tNkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 3.09375 0 20.563 16.406)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="qtwfj5bch"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="icrDwoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.5 2.72059 -.034 11.75 16.594)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="yq9cl_lgn"/><stop offset="1" class="sw1t1obly"/></radialGradient><radialGradient id="i4UPaLe" cx="0" cy="0" r="1" gradientTransform="matrix(3.71585 -5.1531 1.1623 .83812 5.822 11.622)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="isc_1j8cq"/><stop offset="1" class="ib736acio"/></radialGradient><radialGradient id="iwR9IRP" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 27.966 .452)scale(1.32391 3.85262)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i9XGmxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 16 25.094)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iKPKZvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.25 15.546)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="gxt6tevqz"/><stop offset="1" class="eznm9_btg"/></radialGradient><radialGradient id="iUreJsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 25.063 15.546)" gradientUnits="userSpaceOnUse"><stop class="yat4_qblk"/><stop offset="1" class="dhu3d4t5g"/></radialGradient><radialGradient id="iSq6cte" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 12.182 -.257)scale(6.48857 3.45559)" gradientUnits="userSpaceOnUse"><stop class="ud522stie"/><stop offset="1" class="dmat9gbaw"/></radialGradient><radialGradient id="i9Jjmvb" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 2.625 -6.38151 7.90093 8.813 3.332)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="rex51obcx"/><stop offset="1" class="fxz6o0b4v"/></radialGradient><radialGradient id="igsVEDu" cx="0" cy="0" r="1" gradientTransform="rotate(-128.047 5.386 2.807)scale(2.24211 4.11492)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="pwzky5y2s"/><stop offset="1" class="ne8r-1b8h"/></radialGradient><radialGradient id="irTQtFc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.13156 2.93075 -.8157 -2.2632 16.473 3.564)" gradientUnits="userSpaceOnUse"><stop class="cjw5wkr6j"/><stop offset="1" class="c2gqogevh"/></radialGradient><radialGradient id="iLMhUre" cx="0" cy="0" r="1" gradientTransform="rotate(-58.775 14.508 1.513)scale(11.9254 13.2121)" gradientUnits="userSpaceOnUse"><stop class="www4chwuy"/><stop offset=".233" class="a408_iblx"/><stop offset="1" class="vfbc23b7l"/></radialGradient><radialGradient id="iBKjJIb" cx="0" cy="0" r="1" gradientTransform="matrix(6.3125 1.49307 -.7558 3.1954 22.75 5.727)" gradientUnits="userSpaceOnUse"><stop class="i461t-b7g"/><stop offset="1" class="y_60f3smc"/></radialGradient><radialGradient id="ieRFTHc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.903 -.205)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="o53euhbvm"/><stop offset="1" class="hzkxetqij"/></radialGradient><radialGradient id="iWGg3ub" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.406 13.753)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="sw48khtja"/><stop offset="1" class="duvueybsu"/></radialGradient><radialGradient id="iCoSQSb" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.143 4.23)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="cnvbc-41i"/><stop offset="1" class="s2wf2et5i"/></radialGradient><radialGradient id="iCoqbSA" cx="0" cy="0" r="1" gradientTransform="matrix(-.21876 .71543 -3.27084 -1.00012 22.439 5.277)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="bxevcpx9v"/><stop offset="1" class="hu-rubh3f"/></radialGradient><radialGradient id="i44PyMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.068 16.787)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ieZ2AXd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.97 3.662)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iObrMoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.932 16.787)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iA7qA1b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.163 2.987)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="it0pyOr" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.22 24.633)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iPBJtsi" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.281 17.828)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i3nyTCc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -3.934 11.102)scale(3.94637 3.87964)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="ieB9uqe" width="19.805" height="23.21" x="6.56" y="6.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2264"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2264" result="effect2_innerShadow_3930_2264"/></filter><filter id="iTmHxOb" width="5.183" height="7.407" x="12.864" y="15.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".5"/></filter><filter id="iqZ2Ucd" width="3.7" height="5.607" x="14.15" y="16.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".05"/></filter><filter id="izYgKNe" width="6.5" height="2.5" x="12.75" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".05"/></filter><filter id="iS8Y8tv" width="24" height="15.148" x="4" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.32549 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2264"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.294118 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2264" result="effect2_innerShadow_3930_2264"/></filter><filter id="iPdGdqc" width="4.274" height="2.047" x="18.963" y="11.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.211765 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2264"/></filter><filter id="iP7JUWb" width="4.274" height="2.019" x="9.163" y="11.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.211765 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2264"/></filter><filter id="i3JaUQb" width="12.344" height="11.239" x="4.629" y="3.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".25"/></filter><filter id="i7GF27c" width="12.094" height="10.965" x="15.504" y="3.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".25"/></filter><filter id="ireYiqb" width="1.294" height="1.125" x="18.786" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".05"/></filter><filter id="iWDu4td" width="1.316" height="1.357" x="20.438" y="16.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".1"/></filter><filter id="iaoFVxe" width="1.493" height="1.594" x="12.155" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".1"/></filter><filter id="iMQwEPb" width="1.529" height="1.141" x="10.661" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".05"/></filter><filter id="iRiVOWc" width="2.045" height="4.004" x="4.969" y="16.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".125"/></filter><filter id="ikLamze" width="2.101" height="3.72" x="25.008" y="16.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".125"/></filter><filter id="ia3fEJe" width="3.836" height="1.515" x="9.336" y="12.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".125"/></filter><filter id="iqm7KPc" width="3.836" height="1.515" x="19.178" y="12.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2264" stdDeviation=".125"/></filter><linearGradient id="iuwZ9Jb" x1="25.615" x2="16.088" y1="21.637" y2="21.637" gradientUnits="userSpaceOnUse"><stop class="aflrgacjk"/><stop offset="1" class="pp1jb50uj"/></linearGradient><linearGradient id="iLX4xme" x1="16" x2="17.594" y1="20.04" y2="20.04" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iryxMUb" x1="14" x2="16.003" y1="19.75" y2="19.86" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="in3A2zq" x1="16" x2="16" y1="20.784" y2="22.372" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i170Lyd" x1="16" x2="16" y1="16.593" y2="17.375" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="ijs75Mc" x1="26" x2="7.125" y1="7.938" y2="7.938" gradientUnits="userSpaceOnUse"><stop class="rdywzssnj"/><stop offset="1" class="r434h8bwv"/></linearGradient><linearGradient id="iEvkpQc" x1="21.519" x2="20.934" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLiD8Ic" x1="13.319" x2="12.734" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ic1CbBd" x1="28" x2="25.75" y1="16.938" y2="20.995" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iteqi4b" x1="5.094" x2="7.813" y1="18.25" y2="18.013" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-red-hair" /></template>
<style>
.a_h7j0ooy {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m14.983 17.528l-1.077 3.427c-.184.705.257 1.41.883 1.41h1.333c.625 0 1.067-.716.883-1.41l-.901-3.427c-.193-.76-.92-.76-1.121 0");
}

.a408_iblx {
  stop-color: var(--svg-color--cc5249, #CC5249);
}

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

.bc6pupb0c {
  stop-color: var(--svg-color--c15961, #C15961);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bu6bjuduk {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.542 15.39c-1.217 0-2.246.84-2.526 1.975a.51.51 0 0 0 .5.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.557-2.102");
}

.bwuva7blw {
  d: path("M13.448 17.366c0-.538-.437-.896-.555-1.005l-.538.52l.331.674z");
}

.bxevcpx9v {
  stop-color: var(--svg-color--db815c, #DB815C);
}

.c2gqogevh {
  stop-color: var(--svg-color--e56f39, #E56F39);
  stop-opacity: 0;
}

.c47ufxwbm {
  d: path("M11.928 15.897A1.664 1.664 0 0 0 10.325 18h3.214c.038-.144.06-.287.06-.439a1.675 1.675 0 0 0-1.67-1.664");
}

.cjw5wkr6j {
  stop-color: var(--svg-color--e56f39, #E56F39);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnvbc-41i {
  stop-color: var(--svg-color--cc5425, #CC5425);
  stop-opacity: 0;
}

.cova42peu {
  d: path("m25.719 14.312l-.055-1.176c-.02-1.424-1.196-2.598-2.62-2.658h-2.61a4.51 4.51 0 0 1-3.96-2.349s-.382-.885-.466-2.18c-.066-1 .84-1.718 1.834-1.586c2.066.273 4.934.918 6.905 2.204c3.253 2.122 2.683 5.945.971 7.745");
}

.dhu3d4t5g {
  stop-color: var(--svg-color--d6805e, #D6805E);
  stop-opacity: 0;
}

.diidobhvb {
  d: path("M6.577 15.03a3 3 0 0 0 .258 5.966c-.12-1.993-.22-3.974-.258-5.966");
}

.dmat9gbaw {
  stop-color: var(--svg-color--e09171, #E09171);
  stop-opacity: 0;
}

.duvueybsu {
  stop-color: var(--svg-color--ca5743, #CA5743);
  stop-opacity: 0;
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.eznm9_btg {
  stop-color: var(--svg-color--ae6456, #AE6456);
  stop-opacity: 0;
}

.f_dhdrb_m {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M6.609 16.262a1.782 1.782 0 0 0 .155 3.504a147 147 0 0 1-.155-3.504");
}

.f5-1tub5g {
  d: path("M16.433 8.025a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.147-.78H12.79c-3.441 0-6.23 2.82-6.23 6.3v.513c-.634-.482-1.431-1.5-1.431-3.147c0-1.998 1.457-3.008 2.387-3.653c.263-.181.483-.334.617-.472l.185-.195c.652-.691 1.813-1.923 3.84-2.461c1.3-.345 2.62-.348 3.512-.268c.47.042.803.45.803.923V8z");
}

.ft5dv1b6b {
  fill: none;
}

.fxz6o0b4v {
  stop-color: var(--svg-color--ba7461, #BA7461);
  stop-opacity: 0;
}

.fz4t4hgck {
  d: path("M25.052 6.11c.959.33 1.819 1 2.363 1.96a4.42 4.42 0 0 1-.198 4.71a2.9 2.9 0 0 0-.504 1.63v2.215a3.25 3.25 0 0 0-1.244-.5l.146-2.995c-.02-1.43-1.147-2.61-2.57-2.67h-2.611a4.52 4.52 0 0 1-4.124-2.69a1.24 1.24 0 0 0-1.147-.78H12.79c-3.441 0-6.23 2.82-6.23 6.3l.057 2.866c-.473.07-.968.228-1.342.492V14.41c0-.58-.178-1.15-.505-1.63a4.46 4.46 0 0 1-.267-4.56a4.37 4.37 0 0 1 2.423-2.1a5 5 0 0 0 2.58-2.07A4.34 4.34 0 0 1 13.187 2c.603 0 1.176.13 1.71.35c.712.31 1.513.31 2.225 0a4.4 4.4 0 0 1 1.7-.35c1.573 0 2.947.85 3.709 2.11c.573.95 1.473 1.64 2.521 2");
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

.g5hndsbub {
  d: path("M20.072 15.898A1.664 1.664 0 0 1 21.675 18h-3.214a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.663");
}

.gaj5n3b3e {
  d: path("M19.95 16.25c.118.158-.13.351-.411.562c-.282.21-.491.358-.61.2c-.118-.159.014-.458.296-.669c.282-.21.606-.252.725-.094");
}

.gej3nhzpp {
  stop-color: var(--svg-color--d77869, #D77869);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gxt6tevqz {
  stop-color: var(--svg-color--ae6456, #AE6456);
}

.gyp47d6zd {
  stop-color: var(--svg-color--b0495c, #B0495C);
}

.h_oh90w8o {
  d: path("M16 23.895a5.6 5.6 0 0 1-2.583-.612c-.255-.13-.53.158-.369.39A3.53 3.53 0 0 0 16 25.25a3.53 3.53 0 0 0 2.952-1.577c.16-.241-.114-.52-.369-.39a5.6 5.6 0 0 1-2.583.612");
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

.isc_1j8cq {
  stop-color: var(--svg-color--c77a1c, #C77A1C);
}

.iums48bis {
  d: path("m15.287 17.163l-.99 3.427c-.203.705.282 1.41.97 1.41h1.466c.688 0 1.173-.716.97-1.41l-.99-3.427c-.213-.76-1.203-.76-1.426 0");
}

.j-_s4zb6b {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M25.258 19.623q.099-1.61.187-3.22a1.617 1.617 0 0 1-.187 3.22");
}

.jg96q12xv {
  stop-color: var(--svg-color--a84a33, #A84A33);
}

.jgiouvwga {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.458 15.39c1.217 0 2.246.84 2.526 1.975a.51.51 0 0 1-.5.635h-4.159a.43.43 0 0 1-.424-.507a2.606 2.606 0 0 1 2.557-2.102");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnv6hpbvc {
  d: path("M21.554 17.342a1.57 1.57 0 0 0-.431-.862l-.485.531l.219.426z");
}

.m2-9pwbbm {
  stop-color: var(--svg-color--c96949, #C96949);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.ne8r-1b8h {
  stop-color: var(--svg-color--bc7a6a, #BC7A6A);
  stop-opacity: 0;
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nje5f61-e {
  fill: var(--svg-color--000, #000);
  d: path("M12.881 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.038.31.106.439h1.687a.95.95 0 0 0 .113-.439");
}

.nyk28ejhn {
  cx: 11.426px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.o53euhbvm {
  stop-color: var(--svg-color--ce5d46, #CE5D46);
}

.o8swx14tw {
  d: path("M7.004 23.65A7.3 7.3 0 0 0 14.25 30h3.517a7.3 7.3 0 0 0 7.245-6.35c.22-3.512.44-7.01.604-10.52c-.02-1.43-1.147-2.61-2.57-2.67h-2.612a4.52 4.52 0 0 1-4.123-2.69a1.24 1.24 0 0 0-1.147-.78H12.79c-3.441 0-6.23 2.82-6.23 6.3c0 3.47.217 6.882.444 10.36");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol4k0bwog {
  d: path("M25.064 20.825a3.06 3.06 0 0 0 1.686-.575v1.736c0 1.665-.992 3.148-2.5 3.764a7.6 7.6 0 0 0 .645-2.2z");
}

.p061szbyy {
  d: path("M25.177 20.995c.122-1.984.24-3.966.344-5.95a3 3 0 0 1-.344 5.95");
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

.pwzky5y2s {
  stop-color: var(--svg-color--bc7a6a, #BC7A6A);
}

.py4u3gbdm {
  cx: 11.426px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
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

.r434h8bwv {
  stop-color: var(--svg-color--b4644a, #B4644A);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rdywzssnj {
  stop-color: var(--svg-color--ea8759, #EA8759);
}

.rex51obcx {
  stop-color: var(--svg-color--ba7461, #BA7461);
}

.ry-qmab6k {
  fill: var(--svg-color--000, #000);
  d: path("M19.12 17.561c0-.53.423-.953.952-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.114-.439");
}

.s2wf2et5i {
  stop-color: var(--svg-color--cc5425, #CC5425);
}

.spk2babjh {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.452 23.217h-.001a.36.36 0 0 0-.429.074a.33.33 0 0 0-.036.424A3.6 3.6 0 0 0 16 25.325a3.6 3.6 0 0 0 3.015-1.61a.334.334 0 0 0-.037-.428a.36.36 0 0 0-.429-.07A5.5 5.5 0 0 1 16 23.82c-.934 0-1.812-.22-2.548-.603Z");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.svw3fj76s {
  d: path("M6.937 20.825a3.06 3.06 0 0 1-1.687-.575v1.736c0 1.665.992 3.148 2.5 3.764a7.6 7.6 0 0 1-.645-2.2z");
}

.sw1t1obly {
  stop-color: var(--svg-color--ef9330, #EF9330);
  stop-opacity: 0;
}

.sw48khtja {
  stop-color: var(--svg-color--ca5743, #CA5743);
}

.ud522stie {
  stop-color: var(--svg-color--e09171, #E09171);
}

.uiuzuq7ej {
  fill: var(--svg-color--c04f29, #C04F29);
  d: path("M9.64 12.736a5.17 5.17 0 0 1 3.242-.67a.517.517 0 1 1-.125 1.027a4.14 4.14 0 0 0-2.585.53a3 3 0 0 0-.14.09l-.031.022l-.005.004a.517.517 0 0 1-.633-.818z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vfbc23b7l {
  stop-color: var(--svg-color--cc5249, #CC5249);
  stop-opacity: 0;
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.wu19-mbwu {
  stroke: var(--svg-color--c96a55, #C96A55);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.71 13.258c.48-.344 1.674-.949 3.087-.711");
}

.wu4l9jjxy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.95 16.25c.118.158-.13.351-.411.562c-.282.21-.491.358-.61.2c-.118-.159.014-.458.296-.669c.282-.21.606-.252.725-.094");
}

.www4chwuy {
  stop-color: var(--svg-color--b0463c, #B0463C);
}

.x_mthd6lb {
  fill: var(--svg-color--c04f29, #C04F29);
  d: path("M22.96 12.94c-.327-.285-.707-.586-1.282-.767c-.567-.179-1.278-.227-2.26-.107a.517.517 0 0 0 .125 1.027c.897-.11 1.446-.053 1.824.066c.37.116.62.305.913.56a.517.517 0 1 0 .68-.78");
}

.x08e984jt {
  stop-color: var(--svg-color--b56a57, #B56A57);
}

.y_4gjebjq {
  stroke: var(--svg-color--c96a55, #C96A55);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.64 13.172c-.48-.344-1.674-.949-3.087-.711");
}

.y_60f3smc {
  stop-color: var(--svg-color--fb865c, #FB865C);
  stop-opacity: 0;
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

.yq5y_ab2t {
  stop-color: var(--svg-color--a84a33, #A84A33);
  stop-opacity: 0;
}

.yq9cl_lgn {
  stop-color: var(--svg-color--ef9330, #EF9330);
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

</style>
