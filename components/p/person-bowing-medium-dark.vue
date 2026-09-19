<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iN6esmx)" class="stl2eh0-w"/><path fill="url(#ieH2K0o)" class="stl2eh0-w"/><path fill="url(#ik7Ej4d)" class="stl2eh0-w"/><g filter="url(#i6lnn2d)"><path fill="url(#i7kjDfb)" class="qorul39wm"/><path fill="url(#i3wcHze)" class="qorul39wm"/></g><path fill="url(#iotLsme)" class="gisw3ccqa"/><path fill="url(#izPxqUd)" class="gisw3ccqa"/><path fill="url(#iSzOnNd)" class="gisw3ccqa"/><path fill="url(#is1BSsb)" class="gisw3ccqa"/><path fill="url(#ihkPjRb)" class="gisw3ccqa"/><g filter="url(#imvHGFd)"><path fill="url(#iqOWnvT)" class="mn0y67p7y"/></g><g filter="url(#i1uL0hc)"><path fill="url(#ikCMoMd)" class="wlupvhb1e"/></g><g filter="url(#iWxGlDg)"><path fill="url(#iDAE40d)" class="syjjuecsk"/></g><path fill="url(#iEK0tcA)" class="cp5_h6jgc"/><path fill="url(#i1vUH5d)" class="a2iq_fqyu"/><path fill="url(#iauBSNb)" class="a2iq_fqyu"/><g filter="url(#iQMhy4s)"><path class="aiazahbuj"/><path fill="url(#ifk56ob)" class="skp27sdhu"/><path fill="url(#iWJROeS)" class="skp27sdhu"/><path fill="url(#ita4g7O)" class="skp27sdhu"/><path fill="url(#iY810ZY)" class="skp27sdhu"/><path fill="url(#iIwnujc)" class="skp27sdhu"/><path fill="url(#i9lvUDd)" class="skp27sdhu"/><path fill="url(#inZC1bG)" class="skp27sdhu"/><path fill="url(#ieSd65c)" class="skp27sdhu"/></g><g filter="url(#i4seSEd)"><path class="q2brfbbih"/></g><g filter="url(#ihNTaDd)"><path class="fyfwj-b7p"/></g><g filter="url(#iK5oLOd)"><path class="qb4hd7b6s"/></g><g filter="url(#iupJoEc)"><path class="j5yl4gbwo"/><path fill="url(#i6KCSRb)" class="zf_iy8elj"/></g><path fill="url(#iHenCXb)" class="zf_iy8elj"/><g filter="url(#iAlirIb)"><path fill="url(#itMsM2d)" class="kez9wobwn"/><path fill="url(#iSZfNle)" class="kez9wobwn"/><path fill="url(#ipNwwVz)" class="kez9wobwn"/></g><g filter="url(#i6pDN3d)"><path fill="url(#i0vazle)" class="etx-6fb-w"/></g><g filter="url(#iNsUy3c)"><path fill="url(#idPXzHe)" class="qjj0lffhu"/><path fill="url(#irUlccb)" class="qjj0lffhu"/><path fill="url(#izOIVYb)" class="qjj0lffhu"/></g><path class="cuuqdiaon"/><path fill="url(#iLoTSCd)" class="il0gaac1r"/><path class="rivulnook"/><g filter="url(#i7oLv2c)"><path fill="url(#i4Jqltc)" class="ld2sfl-zq"/></g><g filter="url(#iwi1Xhe)"><ellipse transform="rotate(-27.914 12.824 20.378)" class="uxvfyeb6o"/><ellipse fill="url(#iterD4d)" transform="rotate(-27.914 12.824 20.378)" class="sb255hb9s"/></g><path class="c8w5x9b_a"/><path fill="url(#ieXINcc)" class="qarq2v8fx"/><path class="bsmrao3ak"/><g filter="url(#iICQKAb)"><path fill="url(#iUTmlvb)" class="r6ds3cb6g"/></g><g filter="url(#iAdptWA)"><ellipse transform="rotate(-27.914 18.48 20.378)" class="avewiybkm"/><ellipse fill="url(#ivW8H5b)" transform="rotate(-27.914 18.48 20.378)" class="rsj0j6dgp"/></g><g filter="url(#iY2G7ed)"><path stroke="url(#ixjutdv)" class="rtzrsx6xb"/></g><g filter="url(#i5LD38h)"><path stroke="url(#idhVhId)" class="vkzrg3btf"/></g><g filter="url(#itOxfcc)"><path class="psb0xwpdf"/></g><g filter="url(#ibf3nYd)"><path fill="url(#iGyqbNb)" class="uf1yr4rof"/></g><defs><radialGradient id="iN6esmx" cx="0" cy="0" r="1" gradientTransform="rotate(123.959 7.437 15.857)scale(12.144 23.7823)" gradientUnits="userSpaceOnUse"><stop class="tn5cwfbmj"/><stop offset=".27" class="gur5_240r"/><stop offset="1" class="hke44nb4h"/></radialGradient><radialGradient id="ieH2K0o" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01499 4.36558 -4.67954 -3.23182 14.328 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="ml47xab2p"/><stop offset="1" class="ih_n8tb4s"/></radialGradient><radialGradient id="i7kjDfb" cx="0" cy="0" r="1" gradientTransform="rotate(-164.898 7.343 12.764)scale(6.67145 7.19435)" gradientUnits="userSpaceOnUse"><stop class="ygnqhzbrp"/><stop offset="1" class="pmiei2beq"/></radialGradient><radialGradient id="iotLsme" cx="0" cy="0" r="1" gradientTransform="matrix(-8.03127 4.7187 -4.36101 -7.42248 28.489 24.435)" gradientUnits="userSpaceOnUse"><stop class="mi21-2olq"/><stop offset=".724" class="wziyle_fm"/></radialGradient><radialGradient id="iSzOnNd" cx="0" cy="0" r="1" gradientTransform="matrix(6.28125 -1.78432 .36961 1.30113 22.27 27)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="sludkgsww"/><stop offset="1" class="pjd1wtbcg"/></radialGradient><radialGradient id="is1BSsb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.04861 -4.1627 5.4796 -7.96214 25.052 31.292)" gradientUnits="userSpaceOnUse"><stop offset=".855" class="sd7jkkb7x"/><stop offset="1" class="lt28sz2zp"/></radialGradient><radialGradient id="iEK0tcA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79873 0 0 -1.83056 9.753 17.931)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tyr2ocbkv"/><stop offset="1" class="mnuqjbbig"/></radialGradient><radialGradient id="iauBSNb" cx="0" cy="0" r="1" gradientTransform="rotate(100.008 3.866 18.366)scale(1.23447)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="n8gt6nhas"/><stop offset="1" class="g02e8i-0p"/></radialGradient><radialGradient id="ifk56ob" cx="0" cy="0" r="1" gradientTransform="matrix(3.03125 5.4375 -6.00358 3.34682 15.313 19.562)" gradientUnits="userSpaceOnUse"><stop class="q28dpmngs"/><stop offset="1" class="jci56fb0d"/></radialGradient><radialGradient id="iWJROeS" cx="0" cy="0" r="1" gradientTransform="rotate(157.126 6.99 12.583)scale(2.87205 1.88788)" gradientUnits="userSpaceOnUse"><stop class="r-seyp_oj"/><stop offset="1" class="tvkdv_bbu"/></radialGradient><radialGradient id="ita4g7O" cx="0" cy="0" r="1" gradientTransform="matrix(11.4008 0 0 12.5877 11.506 20.271)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="fq486f1su"/><stop offset=".946" class="jhzj-fbdy"/></radialGradient><radialGradient id="iY810ZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.26796 -1.03368 .62988 .77264 19.259 20)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="gd_s4ac4r"/><stop offset="1" class="m0f1m-25x"/></radialGradient><radialGradient id="iIwnujc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39098 -1.24648 1.121 -1.25096 12.615 19.848)" gradientUnits="userSpaceOnUse"><stop class="oj28hv52h"/><stop offset="1" class="nhe2e_3rg"/><stop offset="1" class="fep4_2b7o"/></radialGradient><radialGradient id="i9lvUDd" cx="0" cy="0" r="1" gradientTransform="rotate(86.82 -3.028 12.825)scale(8.07057 1.48882)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="rquh0tvia"/><stop offset="1" class="a8cv3pbcg"/></radialGradient><radialGradient id="inZC1bG" cx="0" cy="0" r="1" gradientTransform="matrix(.14283 11.45751 -11.29472 .1408 16.013 14.543)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="xjzvvkb0j"/><stop offset="1" class="knc3fubhc"/></radialGradient><radialGradient id="ieSd65c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1875 1.73657 0 16.013 26.594)" gradientUnits="userSpaceOnUse"><stop class="vkxh0jh0l"/><stop offset="1" class="sq6hui9va"/></radialGradient><radialGradient id="i6KCSRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.13784 -1.92952 1.14204 -.08158 16.916 22.7)" gradientUnits="userSpaceOnUse"><stop class="ce_jhsb5w"/><stop offset="1" class="fjlcorpcw"/></radialGradient><radialGradient id="iSZfNle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.10938 .25 0 9.625 30.202)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="ll4a91bdg"/><stop offset="1" class="e846x4b3a"/></radialGradient><radialGradient id="ipNwwVz" cx="0" cy="0" r="1" gradientTransform="rotate(-155.863 10.268 12.812)scale(1.56665 .45501)" gradientUnits="userSpaceOnUse"><stop class="rmlrk8dem"/><stop offset=".609" class="vq5fe_b-i"/></radialGradient><radialGradient id="i0vazle" cx="0" cy="0" r="1" gradientTransform="rotate(111.209 1.178 20.399)scale(3.90976 5.9215)" gradientUnits="userSpaceOnUse"><stop class="o11910s3t"/><stop offset="1" class="wdy5h_ywe"/></radialGradient><radialGradient id="idPXzHe" cx="0" cy="0" r="1" gradientTransform="rotate(141.127 9.74 8.767)scale(17.2506 15.7503)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="fjokhrbxg"/><stop offset=".559" class="u_-gyttbr"/></radialGradient><radialGradient id="irUlccb" cx="0" cy="0" r="1" gradientTransform="rotate(164.808 10.606 7.122)scale(15.0251 12.7011)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="mw0shub2u"/><stop offset="1" class="z0ea7q-rn"/></radialGradient><radialGradient id="izOIVYb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.44243 3.68753 -3.99367 -4.81125 24.255 9.983)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="id_02gjio"/><stop offset="1" class="a4g-s4b0z"/></radialGradient><radialGradient id="iLoTSCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 13.176 20.502)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dggggwbdc"/></radialGradient><radialGradient id="iterD4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 12.805 20.786)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieXINcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 18.832 20.502)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dggggwbdc"/></radialGradient><radialGradient id="ivW8H5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 18.46 20.786)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i6lnn2d" width="11" height="6.1" x="2.003" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.478431 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/></filter><filter id="imvHGFd" width="3.2" height="3.2" x="14.403" y="1.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4039" result="effect2_innerShadow_4002_4039"/></filter><filter id="i1uL0hc" width="3.323" height="3.322" x="7.783" y="2.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4039" result="effect2_innerShadow_4002_4039"/></filter><filter id="iWxGlDg" width="3.315" height="3.322" x="20.903" y="2.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4039" result="effect2_innerShadow_4002_4039"/></filter><filter id="iQMhy4s" width="12.65" height="11.707" x="9.688" y="14.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.192157 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/></filter><filter id="i4seSEd" width="2.836" height="1.386" x="11.259" y="17.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0823529 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/></filter><filter id="ihNTaDd" width="2.836" height="1.386" x="17.911" y="17.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0823529 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/></filter><filter id="iK5oLOd" width="3.344" height="4.294" x="14.148" y="20.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".25"/></filter><filter id="iupJoEc" width="2.445" height="3.473" x="14.831" y="20.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.223529 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/></filter><filter id="iAlirIb" width="7" height="3.5" x="9.003" y="26.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/></filter><filter id="i6pDN3d" width="7" height="3.6" x="16.503" y="26.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.219608 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/></filter><filter id="iNsUy3c" width="17" height="12.5" x="7.755" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.0470588 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4039"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0509804 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4039" result="effect2_innerShadow_4002_4039"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0509804 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_4039" result="effect3_innerShadow_4002_4039"/></filter><filter id="i7oLv2c" width="1.161" height="1.231" x="13.27" y="20.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".1"/></filter><filter id="iwi1Xhe" width="1.125" height=".855" x="12.261" y="19.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".05"/></filter><filter id="iICQKAb" width="1.161" height="1.231" x="18.927" y="20.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".1"/></filter><filter id="iAdptWA" width="1.125" height=".855" x="17.917" y="19.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".05"/></filter><filter id="iY2G7ed" width="2.906" height="1.276" x="17.91" y="17.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".125"/></filter><filter id="i5LD38h" width="2.906" height="1.276" x="11.224" y="17.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".125"/></filter><filter id="itOxfcc" width="5.315" height="2.887" x="17.785" y="26.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".25"/></filter><filter id="ibf3nYd" width="6.235" height="2.78" x="16.921" y="12.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4039" stdDeviation=".375"/></filter><linearGradient id="ik7Ej4d" x1="2.953" x2="7.202" y1="23.5" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="zsvzg4bjp"/><stop offset="1" class="t727h725g"/></linearGradient><linearGradient id="i3wcHze" x1="7.193" x2="7.193" y1="30.219" y2="27.274" gradientUnits="userSpaceOnUse"><stop class="y8gz67bnb"/><stop offset="1" class="jiyavqyhw"/></linearGradient><linearGradient id="izPxqUd" x1="24.503" x2="24.503" y1="30.044" y2="29.122" gradientUnits="userSpaceOnUse"><stop class="dcio5xd0n"/><stop offset="1" class="mw21cz39d"/></linearGradient><linearGradient id="ihkPjRb" x1="23.047" x2="23.188" y1="24.827" y2="25.249" gradientUnits="userSpaceOnUse"><stop class="wfpeklbwv"/><stop offset="1" class="v6e6fkb_o"/></linearGradient><linearGradient id="iqOWnvT" x1="17.503" x2="14.908" y1="2.499" y2="5" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="ikCMoMd" x1="11.006" x2="8.305" y1="3.399" y2="6.003" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="iDAE40d" x1="24.118" x2="21.417" y1="3.398" y2="5.995" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="i1vUH5d" x1="21.77" x2="23.957" y1="19.497" y2="16.497" gradientUnits="userSpaceOnUse"><stop class="am9kyybjv"/><stop offset="1" class="zs0txrbkc"/></linearGradient><linearGradient id="iHenCXb" x1="16.003" x2="16.003" y1="20.841" y2="23.94" gradientUnits="userSpaceOnUse"><stop class="c44k8s86m"/><stop offset=".363" class="rjbq44g8q"/></linearGradient><linearGradient id="itMsM2d" x1="13.407" x2="11.872" y1="27.345" y2="31.044" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ozl-omb1v"/><stop offset=".672" class="kwusyxbfn"/></linearGradient><linearGradient id="i4Jqltc" x1="14.141" x2="13.734" y1="20.572" y2="20.823" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUTmlvb" x1="19.797" x2="19.39" y1="20.572" y2="20.823" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixjutdv" x1="20.341" x2="18.285" y1="18.125" y2="17.784" gradientUnits="userSpaceOnUse"><stop offset=".515" class="q3al9kbsw"/><stop offset="1" class="bxiuq5trc"/></linearGradient><linearGradient id="idhVhId" x1="14.141" x2="11.719" y1="17.703" y2="18.188" gradientUnits="userSpaceOnUse"><stop offset=".515" class="q3al9kbsw"/><stop offset="1" class="bxiuq5trc"/></linearGradient><linearGradient id="iGyqbNb" x1="17.95" x2="23.157" y1="14.608" y2="12.876" gradientUnits="userSpaceOnUse"><stop class="w3-fsjbrt"/><stop offset="1" class="j_m7dibdv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bowing-medium-dark" /></template>
<style>
.a2iq_fqyu {
  d: path("M22.253 19.75a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.a4g-s4b0z {
  stop-color: var(--svg-color--45343a, #45343A);
  stop-opacity: 0;
}

.a8cv3pbcg {
  stop-color: var(--svg-color--805b57, #805B57);
  stop-opacity: 0;
}

.aiazahbuj {
  fill: var(--svg-color--8e5b56, #8E5B56);
  d: path("M9.696 17.791c-.15-2.288 1.778-3.248 4.098-3.248h1.713c.32.03.59.231.711.533a3.1 3.1 0 0 0 2.835 1.833h1.563q.208.008.412.01c.754.008 1.4.016 1.3.8l-.062.774h.002l-.265 3.207s-.44 4.3-5.97 4.3s-6.03-4.3-6.03-4.3l-.286-3.651l-.01-.126l-.003-.03z");
}

.am9kyybjv {
  stop-color: var(--svg-color--442832, #442832);
}

.avewiybkm {
  cx: 18.48px;
  cy: 20.378px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.bsmrao3ak {
  fill: var(--svg-color--000, #000);
  d: path("M19.493 21.041a.66.66 0 0 0-.664-.663a.66.66 0 0 0-.59.968h1.175a.66.66 0 0 0 .079-.305");
}

.bxiuq5trc {
  stop-color: var(--svg-color--473c3d, #473C3D);
  stop-opacity: 0;
}

.c44k8s86m {
  stop-color: var(--svg-color--7e4b5a, #7E4B5A);
}

.c8w5x9b_a {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.03 19.53c-.848 0-1.564.585-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.464");
}

.ce_jhsb5w {
  stop-color: var(--svg-color--8c625e, #8C625E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cp5_h6jgc {
  d: path("M9.753 19.75a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.cuuqdiaon {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.905 19.53c-.848 0-1.564.585-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.464");
}

.cy-darb1h {
  stop-color: var(--svg-color--3a91ce, #3A91CE);
}

.dcio5xd0n {
  stop-color: var(--svg-color--eb5b6d, #EB5B6D);
}

.dggggwbdc {
  stop-color: var(--svg-color--6a4c45, #6A4C45);
}

.e846x4b3a {
  stop-color: var(--svg-color--835857, #835857);
  stop-opacity: 0;
}

.etx-6fb-w {
  d: path("M21.359 26.5c-.244 0-.477.051-.691.153L16.96 28.42a.82.82 0 0 0-.457.734c0 .45.34.847.769.847h5.721l.01-1.765c.01-.949-.73-1.724-1.645-1.735");
}

.fep4_2b7o {
  stop-color: var(--svg-color--3f1c1e, #3F1C1E);
  stop-opacity: 0;
}

.fjlcorpcw {
  stop-color: var(--svg-color--8c625e, #8C625E);
  stop-opacity: 0;
}

.fjokhrbxg {
  stop-color: var(--svg-color--47353a, #47353A);
}

.fq486f1su {
  stop-color: var(--svg-color--9e6857, #9E6857);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyfwj-b7p {
  fill: var(--svg-color--372b2b, #372B2B);
  d: path("M20.393 18.69c-.07 0-.15-.02-.21-.07c-.01-.01-.77-.57-1.88-.44c-.2.01-.37-.12-.39-.31a.35.35 0 0 1 .31-.39c1.4-.17 2.35.55 2.39.58c.15.12.18.34.06.49c-.07.1-.18.14-.28.14");
}

.g02e8i-0p {
  stop-color: var(--svg-color--3b232a, #3B232A);
  stop-opacity: 0;
}

.gd_s4ac4r {
  stop-color: var(--svg-color--783f49, #783F49);
}

.gisw3ccqa {
  d: path("M21.029 25.59c-.115.03-.229.06-.333.098c-.987.361-1.693 1.268-1.693 2.332c0 .81.405 1.522 1.039 1.98h6.782c1.756 0 3.179-1.356 3.179-3.004c0-1.65-1.423-2.996-3.189-2.996c-.27 0-.54.04-.79.098a3 3 0 0 0-.332.098z");
}

.gur5_240r {
  stop-color: var(--svg-color--ff802a, #FF802A);
}

.hke44nb4h {
  stop-color: var(--svg-color--fb5b1b, #FB5B1B);
}

.id_02gjio {
  stop-color: var(--svg-color--45343a, #45343A);
}

.ih_n8tb4s {
  stop-color: var(--svg-color--e4380a, #E4380A);
  stop-opacity: 0;
}

.il0gaac1r {
  d: path("M13.173 19.883a1.158 1.158 0 0 0-1.116 1.463h2.237q.041-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.j_m7dibdv {
  stop-color: var(--svg-color--513e44, #513E44);
  stop-opacity: 0;
}

.j5yl4gbwo {
  fill: var(--svg-color--80505c, #80505C);
  d: path("m15.523 20.92l-.66 2.14c-.14.44.19.88.65.88h.98c.46 0 .79-.45.65-.88l-.66-2.14c-.15-.47-.82-.47-.96 0");
}

.jci56fb0d {
  stop-color: var(--svg-color--7b475b, #7B475B);
  stop-opacity: 0;
}

.jhzj-fbdy {
  stop-color: var(--svg-color--9e6857, #9E6857);
}

.jiyavqyhw {
  stop-color: var(--svg-color--fc6028, #FC6028);
  stop-opacity: 0;
}

.kez9wobwn {
  d: path("M10.648 26.5c.243 0 .476.051.69.153l3.708 1.766a.82.82 0 0 1 .457.734c0 .45-.34.847-.769.847H9.013l-.01-1.765c-.01-.949.73-1.724 1.645-1.735");
}

.knc3fubhc {
  stop-color: var(--svg-color--70332f, #70332F);
}

.kwusyxbfn {
  stop-color: var(--svg-color--79455b, #79455B);
}

.ld2sfl-zq {
  d: path("M14.231 20.905c0-.374-.304-.624-.387-.7l-.374.363l.23.469z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4a91bdg {
  stop-color: var(--svg-color--835857, #835857);
}

.lt28sz2zp {
  stop-color: var(--svg-color--b64101, #B64101);
}

.m0f1m-25x {
  stop-color: var(--svg-color--783f49, #783F49);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mi21-2olq {
  stop-color: var(--svg-color--ffa741, #FFA741);
}

.ml47xab2p {
  stop-color: var(--svg-color--e4380a, #E4380A);
}

.mn0y67p7y {
  d: path("M15.663 4.79L14.54 2.542A.377.377 0 0 1 14.88 2h2.244c.28 0 .46.291.34.542L16.343 4.79a.38.38 0 0 1-.68 0");
}

.mnuqjbbig {
  stop-color: var(--svg-color--4f3b38, #4F3B38);
}

.mw0shub2u {
  stop-color: var(--svg-color--413333, #413333);
  stop-opacity: 0;
}

.mw21cz39d {
  stop-color: var(--svg-color--ff6836, #FF6836);
  stop-opacity: 0;
}

.n8gt6nhas {
  stop-color: var(--svg-color--3b232a, #3B232A);
}

.nhe2e_3rg {
  stop-color: var(--svg-color--6f3948, #6F3948);
  stop-opacity: 0;
}

.o11910s3t {
  stop-color: var(--svg-color--996f5e, #996F5E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oj28hv52h {
  stop-color: var(--svg-color--6f3948, #6F3948);
}

.ozl-omb1v {
  stop-color: var(--svg-color--865e51, #865E51);
}

.pjd1wtbcg {
  stop-color: var(--svg-color--ff9d3d, #FF9D3D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmiei2beq {
  stop-color: var(--svg-color--f46a2e, #F46A2E);
}

.psb0xwpdf {
  fill: var(--svg-color--a27b74, #A27B74);
  d: path("M20.353 27.53c-1.085.562-1.83.828-2.068.89c.188.105.723.095 1.525-.109c.604-.153 1.257-.445 1.786-.398c.424.037.841.784.99 1.117c.022-.276.036-.928-.083-1.328c-.149-.5-.794-.875-2.15-.172");
}

.q28dpmngs {
  stop-color: var(--svg-color--7b475b, #7B475B);
}

.q2brfbbih {
  fill: var(--svg-color--372b2b, #372B2B);
  d: path("M11.613 18.69a.35.35 0 0 1-.28-.14a.35.35 0 0 1 .06-.49c.04-.03.99-.75 2.39-.58c.19.02.33.2.31.39s-.19.33-.39.31c-1.11-.13-1.87.43-1.88.44c-.06.05-.14.07-.21.07");
}

.q3al9kbsw {
  stop-color: var(--svg-color--473c3d, #473C3D);
}

.qarq2v8fx {
  d: path("M18.83 19.883a1.158 1.158 0 0 0-1.116 1.463h2.237q.04-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.qb4hd7b6s {
  fill: var(--svg-color--693641, #693641);
  d: path("m15.444 21.184l-.754 2.045c-.16.42.15.862.61.883l.98.045c.459.02.808-.4.688-.824l-.565-2.105c-.13-.463-.799-.494-.96-.044");
}

.qjj0lffhu {
  d: path("M23.852 11.15a2.98 2.98 0 0 0-1.623-1.34a3.17 3.17 0 0 1-1.733-1.37A2.98 2.98 0 0 0 17.94 7c-.41 0-.811.08-1.172.242a1.93 1.93 0 0 1-1.533 0A2.8 2.8 0 0 0 14.074 7a2.98 2.98 0 0 0-2.524 1.4a3.37 3.37 0 0 1-1.773 1.41a3.02 3.02 0 0 0-1.673 1.43a3.04 3.04 0 0 0 .18 3.122c.22.332.35.714.35 1.117v1.984c0 .574.545 1.037 1.116 1.037l-.043-.577c-.234-2.383 1.723-3.38 4.087-3.38h1.713c.32.03.59.231.711.534a3.1 3.1 0 0 0 2.835 1.832h1.563c.911.04 1.83-.115 1.712.811l-.062.773c.55 0 1.095-.446 1.095-1V15.47c0-.393.12-.785.35-1.107a2.98 2.98 0 0 0 .14-3.213");
}

.qorul39wm {
  d: path("M10.978 25.59c.114.03.228.06.332.098c.987.361 1.693 1.268 1.693 2.332c0 .81-.405 1.522-1.039 1.98H5.181c-1.755 0-3.178-1.356-3.178-3.004c0-1.65 1.423-2.996 3.189-2.996c.27 0 .54.04.79.098c.114.03.228.059.332.098z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-seyp_oj {
  stop-color: var(--svg-color--90625b, #90625B);
}

.r6ds3cb6g {
  d: path("M19.887 20.905c0-.374-.304-.624-.386-.7l-.374.363l.23.469z");
}

.rivulnook {
  fill: var(--svg-color--000, #000);
  d: path("M13.836 21.041a.66.66 0 0 0-.663-.663a.66.66 0 0 0-.59.968h1.174a.66.66 0 0 0 .08-.305");
}

.rjbq44g8q {
  stop-color: var(--svg-color--7e4b5a, #7E4B5A);
  stop-opacity: 0;
}

.rmlrk8dem {
  stop-color: var(--svg-color--9b7870, #9B7870);
}

.rquh0tvia {
  stop-color: var(--svg-color--805b57, #805B57);
}

.rsj0j6dgp {
  cx: 18.48px;
  cy: 20.378px;
  rx: 0.506px;
  ry: 0.256px;
}

.rtzrsx6xb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.286 17.794c.348-.036 1.484 0 2.156.516");
}

.sb255hb9s {
  cx: 12.824px;
  cy: 20.378px;
  rx: 0.506px;
  ry: 0.256px;
}

.sd7jkkb7x {
  stop-color: var(--svg-color--b64101, #B64101);
  stop-opacity: 0;
}

.skp27sdhu {
  d: path("M9.696 17.791c-.15-2.288 1.778-3.248 4.098-3.248h1.713c.32.03.59.231.711.533a3.1 3.1 0 0 0 2.835 1.833h1.563q.208.008.412.01c.754.008 1.4.016 1.3.8l-.062.774h.002l-.265 3.207s-.44 4.3-5.97 4.3s-6.03-4.3-6.03-4.3l-.286-3.651l-.01-.126l-.003-.03z");
}

.sludkgsww {
  stop-color: var(--svg-color--ff9d3d, #FF9D3D);
}

.sq6hui9va {
  stop-color: var(--svg-color--6b3551, #6B3551);
  stop-opacity: 0;
}

.stl2eh0-w {
  d: path("M26.919 19.189A3.58 3.58 0 0 0 23.614 17H8.312c-1.442 0-2.744.86-3.305 2.189L2.253 25.83h4.75V30h18v-4.15l4.75-.016z");
}

.syjjuecsk {
  d: path("m21.494 5.98l2.37-.79a.38.38 0 0 0 .15-.62l-1.58-1.58c-.2-.2-.53-.12-.62.15l-.79 2.38c-.1.28.18.56.47.46");
}

.t727h725g {
  stop-color: var(--svg-color--e57544, #E57544);
  stop-opacity: 0;
}

.tn5cwfbmj {
  stop-color: var(--svg-color--ff9c2c, #FF9C2C);
}

.tvkdv_bbu {
  stop-color: var(--svg-color--90625b, #90625B);
  stop-opacity: 0;
}

.tyr2ocbkv {
  stop-color: var(--svg-color--2a1722, #2A1722);
}

.u_-gyttbr {
  stop-color: var(--svg-color--302123, #302123);
}

.ua70ijcgb {
  stop-color: var(--svg-color--399be2, #399BE2);
}

.uf1yr4rof {
  d: path("m22.188 13.264l-4.517.727c1.423.945 3.892.46 4.735.148z");
}

.uxvfyeb6o {
  cx: 12.824px;
  cy: 20.378px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.v6e6fkb_o {
  stop-color: var(--svg-color--c95506, #C95506);
  stop-opacity: 0;
}

.vkxh0jh0l {
  stop-color: var(--svg-color--6b3551, #6B3551);
}

.vkzrg3btf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.755 17.794c-.349-.036-1.484 0-2.156.516");
}

.vq5fe_b-i {
  stop-color: var(--svg-color--9b7870, #9B7870);
  stop-opacity: 0;
}

.w3-fsjbrt {
  stop-color: var(--svg-color--513e44, #513E44);
}

.wdy5h_ywe {
  stop-color: var(--svg-color--835262, #835262);
}

.wfpeklbwv {
  stop-color: var(--svg-color--c95506, #C95506);
}

.wlupvhb1e {
  d: path("m10.515 5.982l-2.38-.79a.373.373 0 0 1-.14-.62l1.58-1.58c.2-.2.53-.12.62.15l.79 2.38c.1.28-.18.56-.47.46");
}

.wziyle_fm {
  stop-color: var(--svg-color--ff7530, #FF7530);
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xjzvvkb0j {
  stop-color: var(--svg-color--70332f, #70332F);
  stop-opacity: 0;
}

.y8gz67bnb {
  stop-color: var(--svg-color--e95252, #E95252);
}

.ygnqhzbrp {
  stop-color: var(--svg-color--ff7919, #FF7919);
}

.z0ea7q-rn {
  stop-color: var(--svg-color--413333, #413333);
}

.zf_iy8elj {
  d: path("m15.523 20.92l-.66 2.14c-.14.44.19.88.65.88h.98c.46 0 .79-.45.65-.88l-.66-2.14c-.15-.47-.82-.47-.96 0");
}

.zs0txrbkc {
  stop-color: var(--svg-color--695655, #695655);
}

.zsvzg4bjp {
  stop-color: var(--svg-color--e57544, #E57544);
}

</style>
