<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iyVNrPe)" class="ol4k0bwog"/><path fill="url(#iElsh4b)" class="ol4k0bwog"/><path fill="url(#ie1bwqd)" class="svw3fj76s"/><g filter="url(#iaINhcb)"><path fill="url(#iW50O9b)" class="o8swx14tw"/></g><path fill="url(#ixOvBPe)" class="o8swx14tw"/><path fill="url(#ik1MThi)" class="o8swx14tw"/><path fill="url(#iPrI4OX)" class="o8swx14tw"/><path fill="url(#iYU4eod)" class="o8swx14tw"/><path fill="url(#iPNCi1b)" class="o8swx14tw"/><path fill="url(#ils8QYd)" class="o8swx14tw"/><rect fill="url(#iGAoAAb)" class="y2_30cbha"/><rect fill="url(#ivqCtbd)" class="ypargx3vg"/><g filter="url(#iWXfQMc)"><path class="hl5xllbai"/></g><g filter="url(#iFINSOc)"><path fill="url(#iLX4xme)" class="iums48bis"/><path fill="url(#iEh2S6d)" class="iums48bis"/><path fill="url(#in3A2zq)" class="iums48bis"/><path fill="url(#i170Lyd)" class="iums48bis"/></g><g filter="url(#iXpBjcb)"><path stroke="url(#iwR9IRP)" class="spk2babjh"/></g><path fill="url(#i9XGmxd)" class="h_oh90w8o"/><g filter="url(#i147jOd)"><path fill="url(#iANYDxA)" class="fz4t4hgck"/><path fill="url(#i77vUqb)" class="fz4t4hgck"/><path fill="url(#if2sbQo)" class="fz4t4hgck"/><path fill="url(#iJdsbie)" class="fz4t4hgck"/><path fill="url(#iPR4JEb)" class="fz4t4hgck"/><path fill="url(#iigOExe)" class="fz4t4hgck"/></g><g filter="url(#iuGcprb)"><path class="eaa02w1fl"/></g><g filter="url(#itvLYuc)"><path class="q3vso_btk"/></g><g filter="url(#iD6mF3c)"><path fill="url(#iGhhNhA)" class="f8vlvkgdl"/><path fill="url(#iwjO2Rd)" class="f8vlvkgdl"/><path fill="url(#iCOi9jc)" class="f8vlvkgdl"/></g><g filter="url(#imA6Dud)"><path fill="url(#ipPGeab)" class="cova42peu"/><path fill="url(#ipe4Qab)" class="cova42peu"/><path fill="url(#i7bMJjd)" class="cova42peu"/><path fill="url(#i8wP1JX)" class="cova42peu"/><path fill="url(#iRtevBe)" class="cova42peu"/></g><path class="jgiouvwga"/><path fill="url(#i44PyMd)" class="g5hndsbub"/><path class="ry-qmab6k"/><g filter="url(#iNfY8me)"><path class="iuvgw_24e"/><path fill="url(#ieZ2AXd)" class="nyzupnb0d"/></g><g filter="url(#iWfaZOe)"><path fill="url(#iEvkpQc)" class="ctljvyjzm"/></g><path class="bu6bjuduk"/><path fill="url(#iObrMoc)" class="sew0brbxf"/><path class="puf-v8bxg"/><g filter="url(#i8hp8Pd)"><path fill="url(#iLiD8Ic)" class="bwuva7blw"/></g><g filter="url(#iuKjFPc)"><ellipse transform="rotate(-27.914 11.426 16.608)" class="py4u3gbdm"/><ellipse fill="url(#iA7qA1b)" transform="rotate(-27.914 11.426 16.608)" class="nyk28ejhn"/></g><path fill="url(#ic1CbBd)" class="p061szbyy"/><path fill="url(#it0pyOr)" class="p061szbyy"/><path fill="url(#iPBJtsi)" class="p061szbyy"/><path fill="url(#iteqi4b)" class="diidobhvb"/><path fill="url(#i3nyTCc)" class="diidobhvb"/><g filter="url(#ihykWic)"><path class="f_dhdrb_m"/></g><g filter="url(#iNQBrlb)"><path class="j-_s4zb6b"/></g><g filter="url(#ifXVryc)"><path class="sfv23riic"/></g><g filter="url(#iqdb8jb)"><path class="nxrasfbey"/></g><path clip-rule="evenodd" class="pmcajhsqn"/><path clip-rule="evenodd" class="vchsgcc1i"/><defs><radialGradient id="iyVNrPe" cx="0" cy="0" r="1" gradientTransform="rotate(94.722 3.237 22.506)scale(5.25312 6.2403)" gradientUnits="userSpaceOnUse"><stop offset=".023" class="jczlmhbmo"/><stop offset="1" class="o_lvus6yw"/></radialGradient><radialGradient id="iElsh4b" cx="0" cy="0" r="1" gradientTransform="rotate(61.858 -4.828 31.199)scale(1.5239 1.38035)" gradientUnits="userSpaceOnUse"><stop class="v1p6h440p"/><stop offset="1" class="bwonkkpej"/></radialGradient><radialGradient id="ie1bwqd" cx="0" cy="0" r="1" gradientTransform="rotate(22.199 -52.008 23.18)scale(3.07491 4.87698)" gradientUnits="userSpaceOnUse"><stop class="rlw56_b2h"/><stop offset="1" class="qainwtbpo"/></radialGradient><radialGradient id="iW50O9b" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5625 0 0 -27.7227 22.804 18.495)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="ik1MThi" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3948 24.92753 -20.64296 -1.98318 18.948 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="g1wxybbrb"/><stop offset=".971" class="gej3nhzpp"/></radialGradient><radialGradient id="iPrI4OX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.625 3.24844 0 20.563 16.023)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="qtwfj5bch"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="iYU4eod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.125 3.40074 0 11.75 16.21)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="yq9cl_lgn"/><stop offset="1" class="sw1t1obly"/></radialGradient><radialGradient id="iPNCi1b" cx="0" cy="0" r="1" gradientTransform="matrix(4.26552 -5.30408 1.19635 .9621 5.272 11.773)" gradientUnits="userSpaceOnUse"><stop class="k7he02b3e"/><stop offset="1" class="ce9a_wbqt"/></radialGradient><radialGradient id="iwR9IRP" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 27.966 .452)scale(1.32391 3.85262)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i9XGmxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34375 5.40625 0 16 25.094)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i77vUqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 6.25 15.546)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="zi33_dotg"/><stop offset="1" class="w_8dtjbuj"/></radialGradient><radialGradient id="if2sbQo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.77276 12 0 25.063 15.546)" gradientUnits="userSpaceOnUse"><stop class="b7o_a-ufk"/><stop offset="1" class="fn-6y2b3e"/></radialGradient><radialGradient id="iJdsbie" cx="0" cy="0" r="1" gradientTransform="matrix(-6.0625 -2.3125 1.8287 -4.79416 23.656 3.844)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="oo1rmc60b"/><stop offset="1" class="xx1ixxclr"/></radialGradient><radialGradient id="iPR4JEb" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 2.625 -6.38151 7.90093 8.813 3.332)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="bokltk6ur"/><stop offset="1" class="h971dxbuw"/></radialGradient><radialGradient id="iigOExe" cx="0" cy="0" r="1" gradientTransform="rotate(-128.047 5.386 2.807)scale(2.24211 4.11492)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="wlle64bqr"/><stop offset="1" class="ruc6_jjva"/></radialGradient><radialGradient id="iGhhNhA" cx="0" cy="0" r="1" gradientTransform="rotate(159.039 7.666 3.261)scale(8.19233 3.17954)" gradientUnits="userSpaceOnUse"><stop class="nn0rbxjbd"/><stop offset="1" class="x_co3obgp"/></radialGradient><radialGradient id="iwjO2Rd" cx="0" cy="0" r="1" gradientTransform="rotate(-56.889 15.194 .928)scale(11.4413 12.6757)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="w9m9tnbbh"/><stop offset="1" class="awv71abxv"/><stop offset="1" class="oojhf0ffl"/></radialGradient><radialGradient id="iCOi9jc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 2.71875 -3.39382 3.19878 9.96 10.148)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="vsaf-49nk"/><stop offset="1" class="k7rtr6bbf"/></radialGradient><radialGradient id="ipPGeab" cx="0" cy="0" r="1" gradientTransform="matrix(7.5302 2.50389 -1.55105 4.66463 22.75 5.727)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="q0ij9lset"/><stop offset="1" class="gf7sg188l"/></radialGradient><radialGradient id="ipe4Qab" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 16.903 -.205)scale(7.98306 4.45209)" gradientUnits="userSpaceOnUse"><stop class="szdxxsb_a"/><stop offset="1" class="tjk3f768l"/></radialGradient><radialGradient id="i7bMJjd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43747 -4.10598 2.94094 -1.74586 24.406 13.753)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="sq4omlxxe"/><stop offset="1" class="cp2vlpb3w"/></radialGradient><radialGradient id="i8wP1JX" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 12.143 4.23)scale(9.20011 9.94567)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="rubu-6bkw"/><stop offset="1" class="le8srzbht"/></radialGradient><radialGradient id="iRtevBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.53126 1.25 -7.40502 -3.14721 22.616 5.241)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="zn038fb-d"/><stop offset="1" class="er2bncbah"/></radialGradient><radialGradient id="i44PyMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.068 16.787)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ieZ2AXd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.97 3.662)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iObrMoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.932 16.787)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iA7qA1b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.163 2.987)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="it0pyOr" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.22 24.633)scale(4.34346 4.144)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iPBJtsi" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 -2.01563 1.6895 1.2311 25.281 17.828)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="i3nyTCc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -3.934 11.102)scale(3.94637 3.87964)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="iaINhcb" width="19.805" height="23.21" x="6.56" y="6.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.580392 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2360"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.607843 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3930_2360" result="effect2_innerShadow_3930_2360"/></filter><filter id="iWXfQMc" width="5.003" height="7.407" x="12.864" y="15.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".5"/></filter><filter id="iFINSOc" width="3.7" height="5.607" x="14.15" y="16.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".05"/></filter><filter id="iXpBjcb" width="6.5" height="2.5" x="12.75" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".05"/></filter><filter id="i147jOd" width="24" height="15.148" x="4" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.466667 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2360"/></filter><filter id="iuGcprb" width="4.274" height="2.047" x="18.963" y="11.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.380392 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2360"/></filter><filter id="itvLYuc" width="4.274" height="2.019" x="9.163" y="11.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.45098 0 0 0 0 0.380392 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3930_2360"/></filter><filter id="iD6mF3c" width="12.344" height="11.239" x="4.629" y="3.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".25"/></filter><filter id="imA6Dud" width="12.094" height="10.965" x="15.504" y="3.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".25"/></filter><filter id="iNfY8me" width="1.294" height="1.125" x="18.786" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".05"/></filter><filter id="iWfaZOe" width="1.316" height="1.357" x="20.438" y="16.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".1"/></filter><filter id="i8hp8Pd" width="1.493" height="1.594" x="12.155" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".1"/></filter><filter id="iuKjFPc" width="1.529" height="1.141" x="10.661" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".05"/></filter><filter id="ihykWic" width="2.045" height="4.004" x="4.969" y="16.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".125"/></filter><filter id="iNQBrlb" width="2.101" height="3.72" x="25.008" y="16.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".125"/></filter><filter id="ifXVryc" width="4.178" height="1.872" x="9.182" y="11.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".2"/></filter><filter id="iqdb8jb" width="4.136" height="1.815" x="19.028" y="11.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3930_2360" stdDeviation=".2"/></filter><linearGradient id="ixOvBPe" x1="25.615" x2="21.866" y1="21.638" y2="21.638" gradientUnits="userSpaceOnUse"><stop class="aflrgacjk"/><stop offset="1" class="pp1jb50uj"/></linearGradient><linearGradient id="ils8QYd" x1="6.56" x2="8.866" y1="19.46" y2="19.46" gradientUnits="userSpaceOnUse"><stop class="xjjr03pvs"/><stop offset="1" class="fyqklcd3z"/></linearGradient><linearGradient id="iGAoAAb" x1="12.068" x2="20.638" y1="10.929" y2="10.929" gradientUnits="userSpaceOnUse"><stop class="nekl6bw4d"/><stop offset="1" class="vidj55b5k"/></linearGradient><linearGradient id="ivqCtbd" x1="13.513" x2="16.898" y1="8.444" y2="8.444" gradientUnits="userSpaceOnUse"><stop class="mid_j8bxx"/><stop offset="1" class="bbrqxmbjo"/></linearGradient><linearGradient id="iLX4xme" x1="16" x2="17.594" y1="20.04" y2="20.04" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iEh2S6d" x1="14" x2="16.003" y1="19.75" y2="19.861" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="in3A2zq" x1="16" x2="16" y1="20.784" y2="22.372" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i170Lyd" x1="16" x2="16" y1="16.593" y2="17.375" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iANYDxA" x1="26" x2="7.125" y1="7.938" y2="7.938" gradientUnits="userSpaceOnUse"><stop class="e_5hjqbcc"/><stop offset="1" class="kophhkbny"/></linearGradient><linearGradient id="iEvkpQc" x1="21.519" x2="20.934" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLiD8Ic" x1="13.319" x2="12.734" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ic1CbBd" x1="28" x2="25.75" y1="16.938" y2="20.995" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iteqi4b" x1="5.094" x2="7.813" y1="18.25" y2="18.013" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:older-person" /></template>
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

.awv71abxv {
  stop-color: var(--svg-color--977d7d, #977D7D);
  stop-opacity: 0;
}

.b7o_a-ufk {
  stop-color: var(--svg-color--aaa49f, #AAA49F);
}

.bbrqxmbjo {
  stop-color: var(--svg-color--d79412, #D79412);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bokltk6ur {
  stop-color: var(--svg-color--82807f, #82807F);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bu6bjuduk {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.542 15.39c-1.217 0-2.246.84-2.526 1.975a.51.51 0 0 0 .5.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.557-2.102");
}

.bwonkkpej {
  stop-color: var(--svg-color--a09095, #A09095);
  stop-opacity: 0;
}

.bwuva7blw {
  d: path("M13.448 17.366c0-.538-.437-.896-.555-1.005l-.538.52l.331.674z");
}

.ce9a_wbqt {
  stop-color: var(--svg-color--a76413, #A76413);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cova42peu {
  d: path("m25.719 14.312l-.055-1.176c-.02-1.424-1.196-2.598-2.62-2.658h-2.61a4.51 4.51 0 0 1-3.96-2.349s-.382-.885-.466-2.18c-.066-1 .84-1.718 1.834-1.586c2.066.273 4.934.918 6.905 2.204c3.253 2.122 2.683 5.945.971 7.745");
}

.cp2vlpb3w {
  stop-color: var(--svg-color--988275, #988275);
  stop-opacity: 0;
}

.ctljvyjzm {
  d: path("M21.554 17.342a1.57 1.57 0 0 0-.431-.862l-.485.532l.219.425z");
}

.diidobhvb {
  d: path("M6.577 15.03a3 3 0 0 0 .258 5.966c-.12-1.993-.22-3.974-.258-5.966");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e_5hjqbcc {
  stop-color: var(--svg-color--bebebf, #BEBEBF);
}

.eaa02w1fl {
  fill: var(--svg-color--88817e, #88817E);
  d: path("M22.96 12.94c-.327-.285-.707-.586-1.282-.767c-.567-.179-1.278-.227-2.26-.107a.517.517 0 0 0 .125 1.027c.897-.11 1.446-.053 1.824.066c.37.116.62.305.913.56a.517.517 0 1 0 .68-.78");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.er2bncbah {
  stop-color: var(--svg-color--b1b1b1, #B1B1B1);
  stop-opacity: 0;
}

.f_dhdrb_m {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M6.609 16.262a1.782 1.782 0 0 0 .155 3.504a147 147 0 0 1-.155-3.504");
}

.f8vlvkgdl {
  d: path("M16.433 8.025a5 5 0 0 1-.123-.255a1.24 1.24 0 0 0-1.147-.78H12.79c-3.441 0-6.23 2.82-6.23 6.3v.513c-.634-.482-1.431-1.5-1.431-3.147c0-1.998 1.457-3.008 2.387-3.652c.263-.182.483-.335.617-.473l.185-.195c.652-.691 1.813-1.923 3.84-2.46c1.3-.346 2.62-.349 3.512-.27c.47.043.803.451.803.924V8z");
}

.fn-6y2b3e {
  stop-color: var(--svg-color--aaa49f, #AAA49F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyqklcd3z {
  stop-color: var(--svg-color--d19e49, #D19E49);
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

.gej3nhzpp {
  stop-color: var(--svg-color--d77869, #D77869);
}

.gf7sg188l {
  stop-color: var(--svg-color--bfbfbf, #BFBFBF);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.h_oh90w8o {
  d: path("M16 23.895a5.6 5.6 0 0 1-2.583-.612c-.255-.13-.53.158-.369.39A3.53 3.53 0 0 0 16 25.25a3.53 3.53 0 0 0 2.952-1.577c.16-.241-.114-.52-.369-.39a5.6 5.6 0 0 1-2.583.612");
}

.h971dxbuw {
  stop-color: var(--svg-color--82807f, #82807F);
  stop-opacity: 0;
}

.hl5xllbai {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m14.919 17.528l-1.016 3.427c-.173.705.243 1.41.833 1.41h1.258c.59 0 1.006-.716.832-1.41l-.85-3.427c-.182-.76-.866-.76-1.057 0");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.iums48bis {
  d: path("m15.287 17.163l-.99 3.427c-.203.705.282 1.41.97 1.41h1.466c.688 0 1.173-.716.97-1.41l-.99-3.427c-.213-.76-1.203-.76-1.426 0");
}

.iuvgw_24e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.95 16.25c.118.158-.13.351-.411.562c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.j-_s4zb6b {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M25.258 19.623q.099-1.61.187-3.22a1.617 1.617 0 0 1-.187 3.22");
}

.jczlmhbmo {
  stop-color: var(--svg-color--bdb6b6, #BDB6B6);
}

.jgiouvwga {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.458 15.39c1.217 0 2.246.84 2.526 1.975a.51.51 0 0 1-.5.635h-4.159a.43.43 0 0 1-.424-.507a2.606 2.606 0 0 1 2.557-2.102");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k7he02b3e {
  stop-color: var(--svg-color--a76413, #A76413);
}

.k7rtr6bbf {
  stop-color: var(--svg-color--967d7e, #967D7E);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.kophhkbny {
  stop-color: var(--svg-color--868382, #868382);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.le8srzbht {
  stop-color: var(--svg-color--7d7476, #7D7476);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mid_j8bxx {
  stop-color: var(--svg-color--eeaa13, #EEAA13);
}

.nekl6bw4d {
  stop-color: var(--svg-color--f2a818, #F2A818);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nn0rbxjbd {
  stop-color: var(--svg-color--b5b4b5, #B5B4B5);
}

.nxrasfbey {
  stroke: var(--svg-color--9d9899, #9D9899);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.64 13.172c-.48-.344-1.674-.948-3.087-.71");
}

.nyk28ejhn {
  cx: 11.426px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.nyzupnb0d {
  d: path("M19.95 16.25c.118.158-.13.351-.411.562c-.282.21-.491.359-.61.2c-.118-.158.014-.458.296-.668s.606-.253.725-.095");
}

.o_lvus6yw {
  stop-color: var(--svg-color--8a8092, #8A8092);
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

.oo1rmc60b {
  stop-color: var(--svg-color--bdbdbd, #BDBDBD);
}

.oojhf0ffl {
  stop-color: var(--svg-color--7e707b, #7E707B);
  stop-opacity: 0;
}

.p061szbyy {
  d: path("M25.177 20.995c.122-1.984.24-3.966.344-5.95a3 3 0 0 1-.344 5.95");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmcajhsqn {
  fill: var(--svg-color--ffa20a, #FFA20A);
  fill-rule: evenodd;
  d: path("M13.539 18.555a.45.45 0 0 1-.014.636c-.89.853-1.98.89-2.381.89a.45.45 0 1 1 0-.9c.348 0 1.132-.04 1.758-.64a.45.45 0 0 1 .637.014");
}

.pp1jb50uj {
  stop-color: var(--svg-color--ffd93b, #FFD93B);
  stop-opacity: 0;
}

.puf-v8bxg {
  fill: var(--svg-color--000, #000);
  d: path("M12.881 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.038.31.106.44h1.687a.95.95 0 0 0 .113-.44");
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.py4u3gbdm {
  cx: 11.426px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.q0ij9lset {
  stop-color: var(--svg-color--bfbfbf, #BFBFBF);
}

.q3vso_btk {
  fill: var(--svg-color--88817e, #88817E);
  d: path("M9.64 12.736a5.17 5.17 0 0 1 3.242-.67a.517.517 0 0 1-.125 1.027a4.14 4.14 0 0 0-2.585.53a3 3 0 0 0-.171.112l-.005.004a.517.517 0 0 1-.633-.818z");
}

.qainwtbpo {
  stop-color: var(--svg-color--7d6e72, #7D6E72);
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

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rlw56_b2h {
  stop-color: var(--svg-color--91888a, #91888A);
}

.rubu-6bkw {
  stop-color: var(--svg-color--7d7476, #7D7476);
  stop-opacity: 0;
}

.ruc6_jjva {
  stop-color: var(--svg-color--8b8585, #8B8585);
  stop-opacity: 0;
}

.ry-qmab6k {
  fill: var(--svg-color--000, #000);
  d: path("M19.12 17.561c0-.53.423-.953.952-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.114-.439");
}

.sew0brbxf {
  d: path("M11.928 15.898A1.664 1.664 0 0 0 10.325 18h3.214c.038-.144.06-.287.06-.439a1.675 1.675 0 0 0-1.67-1.663");
}

.sfv23riic {
  stroke: var(--svg-color--9d9899, #9D9899);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.707 13.306c.48-.344 1.644-.893 3.128-.815");
}

.spk2babjh {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.452 23.217h-.001a.36.36 0 0 0-.429.074a.33.33 0 0 0-.036.424A3.6 3.6 0 0 0 16 25.325a3.6 3.6 0 0 0 3.015-1.61a.334.334 0 0 0-.037-.428a.36.36 0 0 0-.429-.07A5.5 5.5 0 0 1 16 23.82c-.934 0-1.812-.22-2.548-.603Z");
}

.sq4omlxxe {
  stop-color: var(--svg-color--988275, #988275);
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

.szdxxsb_a {
  stop-color: var(--svg-color--95827a, #95827A);
}

.tjk3f768l {
  stop-color: var(--svg-color--95827a, #95827A);
  stop-opacity: 0;
}

.v1p6h440p {
  stop-color: var(--svg-color--a09095, #A09095);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vchsgcc1i {
  fill: var(--svg-color--ffc41a, #FFC41A);
  fill-rule: evenodd;
  d: path("M18.444 18.555a.45.45 0 0 0 .013.636c.89.853 1.98.89 2.382.89a.45.45 0 0 0 0-.9c-.349 0-1.133-.04-1.759-.64a.45.45 0 0 0-.636.014");
}

.vidj55b5k {
  stop-color: var(--svg-color--eaa821, #EAA821);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vsaf-49nk {
  stop-color: var(--svg-color--967d7e, #967D7E);
}

.w_8dtjbuj {
  stop-color: var(--svg-color--887f7d, #887F7D);
  stop-opacity: 0;
}

.w9m9tnbbh {
  stop-color: var(--svg-color--7e707b, #7E707B);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wlle64bqr {
  stop-color: var(--svg-color--8b8585, #8B8585);
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.x_co3obgp {
  stop-color: var(--svg-color--b5b4b5, #B5B4B5);
  stop-opacity: 0;
}

.xjjr03pvs {
  stop-color: var(--svg-color--d19e49, #D19E49);
}

.xx1ixxclr {
  stop-color: var(--svg-color--bdbdbd, #BDBDBD);
  stop-opacity: 0;
}

.y2_30cbha {
  width: 8.57px;
  height: 0.828px;
  x: 12.068px;
  y: 10.101px;
  rx: 0.414px;
}

.ypargx3vg {
  width: 5.68px;
  height: 0.828px;
  x: 13.513px;
  y: 7.616px;
  rx: 0.414px;
}

.yq9cl_lgn {
  stop-color: var(--svg-color--ef9330, #EF9330);
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zi33_dotg {
  stop-color: var(--svg-color--887f7d, #887F7D);
}

.zn038fb-d {
  stop-color: var(--svg-color--b1b1b1, #B1B1B1);
}

</style>
