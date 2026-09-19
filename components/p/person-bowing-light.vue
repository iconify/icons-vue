<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGpjnCb)" class="zyl1aqefu"/><path fill="url(#izIOhhc)" class="zyl1aqefu"/><path fill="url(#icfQ2Mb)" class="zyl1aqefu"/><g filter="url(#iJr36sc)"><path fill="url(#izK9JdP)" class="t9kf6-dgx"/><path fill="url(#if9fjSd)" class="t9kf6-dgx"/></g><path fill="url(#i8xQxVY)" class="pouq8sxtv"/><path fill="url(#idj2Fab)" class="pouq8sxtv"/><path fill="url(#i0ZxBPc)" class="pouq8sxtv"/><path fill="url(#i4M36Nb)" class="pouq8sxtv"/><g filter="url(#iivlgdd)"><path fill="url(#i0tRGSb)" class="f1bbqmbqb"/></g><g filter="url(#idZc6dc)"><path fill="url(#i33C30b)" class="zga6vzu6c"/></g><g filter="url(#i8AP2Sc)"><path fill="url(#ith7pLe)" class="o6h5vobfi"/></g><path fill="url(#iAAk8Wp)" class="x-bbadc0e"/><path fill="url(#iV6kEqu)" class="ba9qdhato"/><path fill="url(#iaPdT0k)" class="ba9qdhato"/><path class="f9d_k7bir"/><path fill="url(#iDHNNee)" class="wej4rd4yy"/><path fill="url(#iqzAbRb)" class="wej4rd4yy"/><path fill="url(#iFyaodU)" class="wej4rd4yy"/><path fill="url(#iX8cboF)" class="wej4rd4yy"/><path fill="url(#ioBk9tc)" class="wej4rd4yy"/><path fill="url(#iYFrVge)" class="wej4rd4yy"/><path fill="url(#iobyFee)" class="wej4rd4yy"/><g filter="url(#i4GBMke)"><path class="zs4-mpbwk"/></g><g filter="url(#iGUdOpc)"><path class="hw-39-xyp"/></g><g filter="url(#iCR4CwL)"><path class="l9-a4ksrj"/></g><g filter="url(#iiYFlEc)"><path class="yfgejfb8x"/><path fill="url(#inL3rre)" class="fvy7tabyd"/></g><path fill="url(#idH6xEe)" class="fvy7tabyd"/><g filter="url(#iIA3npc)"><path fill="url(#iUeilxb)" class="tfe13zb-t"/><path fill="url(#iOxLZgc)" class="tfe13zb-t"/><path fill="url(#ieyWQMc)" class="tfe13zb-t"/></g><g filter="url(#iaJcbGd)"><path fill="url(#iOVEO5W)" class="cvn8yhb0e"/></g><g filter="url(#i2dLtse)"><path fill="url(#iplRvcw)" class="z-ofjjjah"/><path fill="url(#iprhmEd)" class="z-ofjjjah"/><path fill="url(#i1XfE2b)" class="z-ofjjjah"/></g><path class="h75gmsbeb"/><path fill="url(#iLP4CEe)" class="pkmpwdtwq"/><path class="w-i21bcei"/><g filter="url(#ieqaTEd)"><path fill="url(#iacC5kd)" class="nrohlub_d"/></g><g filter="url(#ikiDlFw)"><ellipse transform="rotate(-27.914 12.824 20.64)" class="es6zpkbma"/><ellipse fill="url(#itwnyLb)" transform="rotate(-27.914 12.824 20.64)" class="pm-3hetnk"/></g><path class="jujktlw7p"/><path fill="url(#i4q7cbD)" class="yp9pssbjt"/><path class="f70_ivb1v"/><g filter="url(#imbZxbd)"><path fill="url(#i8GGJ9s)" class="dltz-cc1o"/></g><g filter="url(#infzZJb)"><ellipse transform="rotate(-27.914 18.48 20.64)" class="vntwdnbat"/><ellipse fill="url(#iJQopBd)" transform="rotate(-27.914 18.48 20.64)" class="fk3wcv_fi"/></g><g filter="url(#i8dWmTd)"><path stroke="url(#iXXOCCe)" class="zlbgcf5wc"/></g><g filter="url(#ie6dQqd)"><path stroke="url(#ih92K3b)" class="k2ef9mb3g"/></g><g filter="url(#iunmpxd)"><path class="coky_i3pk"/></g><g filter="url(#ihe0xSc)"><path fill="url(#isjdfwe)" class="vhdej_7rc"/></g><defs><radialGradient id="iGpjnCb" cx="0" cy="0" r="1" gradientTransform="rotate(123.959 7.367 15.988)scale(12.144 23.7823)" gradientUnits="userSpaceOnUse"><stop class="tn5cwfbmj"/><stop offset=".27" class="gur5_240r"/><stop offset="1" class="hke44nb4h"/></radialGradient><radialGradient id="izIOhhc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01499 4.36558 -4.67954 -3.23182 14.328 23.762)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="ml47xab2p"/><stop offset="1" class="ih_n8tb4s"/></radialGradient><radialGradient id="izK9JdP" cx="0" cy="0" r="1" gradientTransform="rotate(-164.898 7.36 12.895)scale(6.67145 7.19435)" gradientUnits="userSpaceOnUse"><stop class="ygnqhzbrp"/><stop offset="1" class="pmiei2beq"/></radialGradient><radialGradient id="i8xQxVY" cx="0" cy="0" r="1" gradientTransform="matrix(-8.03127 4.7187 -4.36101 -7.42248 28.489 24.697)" gradientUnits="userSpaceOnUse"><stop class="mi21-2olq"/><stop offset=".724" class="wziyle_fm"/></radialGradient><radialGradient id="i0ZxBPc" cx="0" cy="0" r="1" gradientTransform="matrix(6.28125 -1.78432 .36961 1.30113 22.27 27.262)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="sludkgsww"/><stop offset="1" class="pjd1wtbcg"/></radialGradient><radialGradient id="i4M36Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.04861 -4.1627 5.4796 -7.96214 25.052 31.554)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="b2tj25bjo"/><stop offset="1" class="ojp20rs2q"/></radialGradient><radialGradient id="iAAk8Wp" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79873 0 0 -1.83056 9.753 18.193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="xqw25_nlo"/><stop offset="1" class="uwfbj0bza"/></radialGradient><radialGradient id="iaPdT0k" cx="0" cy="0" r="1" gradientTransform="rotate(100.008 3.757 18.497)scale(1.23447)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="h7sf75x5w"/><stop offset="1" class="pmvvskbdj"/></radialGradient><radialGradient id="iDHNNee" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6462 1.11638 -.94379 -2.2371 18.322 21.722)" gradientUnits="userSpaceOnUse"><stop class="abe00scbl"/><stop offset="1" class="jjy7pyzfk"/></radialGradient><radialGradient id="iqzAbRb" cx="0" cy="0" r="1" gradientTransform="matrix(11.4008 0 0 12.5877 11.506 20.534)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="gnl0uxdxo"/><stop offset=".946" class="w0bk2cb3c"/></radialGradient><radialGradient id="iFyaodU" cx="0" cy="0" r="1" gradientTransform="rotate(-39.188 38.089 -16.921)scale(1.63592 1.57593)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="dxzww_79w"/><stop offset="1" class="pfg89rzer"/></radialGradient><radialGradient id="iX8cboF" cx="0" cy="0" r="1" gradientTransform="rotate(-133.107 10.864 7.428)scale(2.18013 1.98665)" gradientUnits="userSpaceOnUse"><stop class="auwq-mblr"/><stop offset="1" class="q4xs56bfx"/></radialGradient><radialGradient id="ioBk9tc" cx="0" cy="0" r="1" gradientTransform="matrix(.4477 8.05814 -1.48653 .08259 9.945 15.4)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="ml8qh4bmo"/><stop offset="1" class="b-05l3cyt"/></radialGradient><radialGradient id="iYFrVge" cx="0" cy="0" r="1" gradientTransform="matrix(1.87498 3.13274 -2.10938 1.26249 17.032 14.805)" gradientUnits="userSpaceOnUse"><stop class="xwi_niyrc"/><stop offset="1" class="jdwtmzbkw"/></radialGradient><radialGradient id="iobyFee" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.62002 -8.35458 0 16.013 17.038)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="g36mx3bsc"/><stop offset="1" class="m630zdbbe"/></radialGradient><radialGradient id="inL3rre" cx="0" cy="0" r="1" gradientTransform="matrix(.10392 -2.06539 1.60645 .08083 16.674 23.098)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="e_h5sgb4g"/><stop offset="1" class="g5i-sbckt"/></radialGradient><radialGradient id="iOxLZgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.10938 .25 0 9.625 30.464)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="ba81d8b2u"/><stop offset="1" class="izyqnbcdg"/></radialGradient><radialGradient id="ieyWQMc" cx="0" cy="0" r="1" gradientTransform="rotate(-155.863 10.296 12.943)scale(1.56665 .45501)" gradientUnits="userSpaceOnUse"><stop class="yasaahjks"/><stop offset=".609" class="dox4utblj"/></radialGradient><radialGradient id="iOVEO5W" cx="0" cy="0" r="1" gradientTransform="matrix(6 -3.25 2.38008 4.394 17.614 30.51)" gradientUnits="userSpaceOnUse"><stop class="cka266mdm"/><stop offset=".741" class="dos8-9u_k"/></radialGradient><radialGradient id="iplRvcw" cx="0" cy="0" r="1" gradientTransform="rotate(141.127 9.694 8.898)scale(17.2506 15.7503)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="wqu1hduus"/><stop offset=".559" class="bstw1xboe"/></radialGradient><radialGradient id="iprhmEd" cx="0" cy="0" r="1" gradientTransform="rotate(164.808 10.588 7.253)scale(15.0251 12.7011)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="zalfqh_is"/><stop offset="1" class="tww8s068l"/></radialGradient><radialGradient id="i1XfE2b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.44243 3.68753 -3.99367 -4.81125 24.255 10.245)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iLP4CEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 13.176 20.764)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dggggwbdc"/></radialGradient><radialGradient id="itwnyLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 12.804 21.049)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4q7cbD" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 18.832 20.764)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dggggwbdc"/></radialGradient><radialGradient id="iJQopBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 18.46 21.047)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iJr36sc" width="11" height="6.1" x="2.003" y="24.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.478431 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/></filter><filter id="iivlgdd" width="3.2" height="3.2" x="14.403" y="2.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4048" result="effect2_innerShadow_4002_4048"/></filter><filter id="idZc6dc" width="3.323" height="3.322" x="7.783" y="3.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4048" result="effect2_innerShadow_4002_4048"/></filter><filter id="i8AP2Sc" width="3.315" height="3.322" x="20.903" y="3.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4048" result="effect2_innerShadow_4002_4048"/></filter><filter id="i4GBMke" width="2.836" height="1.386" x="11.259" y="17.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0313726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/></filter><filter id="iGUdOpc" width="2.836" height="1.386" x="17.911" y="17.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0313726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/></filter><filter id="iCR4CwL" width="3.344" height="4.294" x="14.148" y="20.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".25"/></filter><filter id="iiYFlEc" width="2.445" height="3.473" x="14.831" y="20.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.556863 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/></filter><filter id="iIA3npc" width="7" height="3.5" x="9.003" y="26.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.584314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/></filter><filter id="iaJcbGd" width="7" height="3.6" x="16.503" y="26.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.54902 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/></filter><filter id="i2dLtse" width="17" height="12.5" x="7.755" y="6.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.027451 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.160784 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4048" result="effect2_innerShadow_4002_4048"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0509804 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_4048" result="effect3_innerShadow_4002_4048"/></filter><filter id="ieqaTEd" width="1.161" height="1.231" x="13.27" y="20.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".1"/></filter><filter id="ikiDlFw" width="1.125" height=".855" x="12.261" y="20.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".05"/></filter><filter id="imbZxbd" width="1.161" height="1.231" x="18.927" y="20.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".1"/></filter><filter id="infzZJb" width="1.125" height=".855" x="17.917" y="20.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".05"/></filter><filter id="i8dWmTd" width="2.906" height="1.276" x="17.91" y="17.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".125"/></filter><filter id="ie6dQqd" width="2.906" height="1.276" x="11.224" y="17.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".125"/></filter><filter id="iunmpxd" width="5.315" height="2.887" x="17.785" y="26.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".25"/></filter><filter id="ihe0xSc" width="6.235" height="2.78" x="16.921" y="12.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4048" stdDeviation=".375"/></filter><linearGradient id="icfQ2Mb" x1="2.953" x2="7.202" y1="23.762" y2="25.079" gradientUnits="userSpaceOnUse"><stop class="zsvzg4bjp"/><stop offset="1" class="t727h725g"/></linearGradient><linearGradient id="if9fjSd" x1="7.193" x2="7.193" y1="30.481" y2="27.536" gradientUnits="userSpaceOnUse"><stop class="y8gz67bnb"/><stop offset="1" class="jiyavqyhw"/></linearGradient><linearGradient id="idj2Fab" x1="24.503" x2="24.503" y1="30.306" y2="29.384" gradientUnits="userSpaceOnUse"><stop class="dcio5xd0n"/><stop offset="1" class="mw21cz39d"/></linearGradient><linearGradient id="i0tRGSb" x1="17.503" x2="14.908" y1="2.761" y2="5.262" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="i33C30b" x1="11.006" x2="8.305" y1="3.661" y2="6.265" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="ith7pLe" x1="24.118" x2="21.417" y1="3.66" y2="6.257" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="iV6kEqu" x1="21.77" x2="23.957" y1="19.759" y2="16.759" gradientUnits="userSpaceOnUse"><stop class="dhr7acfzu"/><stop offset="1" class="cnnf9s-0l"/></linearGradient><linearGradient id="idH6xEe" x1="16.003" x2="16.003" y1="21.103" y2="24.202" gradientUnits="userSpaceOnUse"><stop class="bket_m3-f"/><stop offset=".363" class="k1t018bdv"/></linearGradient><linearGradient id="iUeilxb" x1="13.407" x2="11.872" y1="27.607" y2="31.306" gradientUnits="userSpaceOnUse"><stop offset=".053" class="rnv4ixbjn"/><stop offset=".697" class="wdq8bfb6i"/></linearGradient><linearGradient id="iacC5kd" x1="14.141" x2="13.734" y1="20.834" y2="21.085" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8GGJ9s" x1="19.797" x2="19.39" y1="20.834" y2="21.085" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXXOCCe" x1="20.341" x2="18.285" y1="18.388" y2="18.046" gradientUnits="userSpaceOnUse"><stop offset=".515" class="a6x862b5i"/><stop offset="1" class="rkma5lbuf"/></linearGradient><linearGradient id="ih92K3b" x1="13.555" x2="11.43" y1="17.987" y2="18.675" gradientUnits="userSpaceOnUse"><stop offset=".333" class="a6x862b5i"/><stop offset="1" class="rkma5lbuf"/></linearGradient><linearGradient id="isjdfwe" x1="17.95" x2="23.157" y1="14.87" y2="13.138" gradientUnits="userSpaceOnUse"><stop class="hdoticcnk"/><stop offset="1" class="v-pdexbhk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bowing-light" /></template>
<style>
.a6x862b5i {
  stop-color: var(--svg-color--333, #333);
}

.abe00scbl {
  stop-color: var(--svg-color--ffc8b7, #FFC8B7);
}

.auwq-mblr {
  stop-color: var(--svg-color--c68284, #C68284);
}

.b-05l3cyt {
  stop-color: var(--svg-color--e2a693, #E2A693);
  stop-opacity: 0;
}

.b2tj25bjo {
  stop-color: var(--svg-color--f44e0b, #F44E0B);
  stop-opacity: 0;
}

.ba81d8b2u {
  stop-color: var(--svg-color--dea198, #DEA198);
}

.ba9qdhato {
  d: path("M22.253 20.012a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.bket_m3-f {
  stop-color: var(--svg-color--de9f99, #DE9F99);
}

.bstw1xboe {
  stop-color: var(--svg-color--251d20, #251D20);
}

.cka266mdm {
  stop-color: var(--svg-color--d3979d, #D3979D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnnf9s-0l {
  stop-color: var(--svg-color--ffd4bd, #FFD4BD);
}

.coky_i3pk {
  fill: var(--svg-color--ffdcc7, #FFDCC7);
  d: path("M20.353 27.792c-1.085.562-1.83.828-2.068.89c.188.105.723.095 1.525-.109c.604-.153 1.257-.445 1.786-.398c.424.037.841.784.99 1.117c.022-.276.036-.928-.083-1.328c-.149-.5-.794-.875-2.15-.172");
}

.cvn8yhb0e {
  d: path("M21.359 26.762c-.244 0-.477.051-.691.153l-3.708 1.766a.82.82 0 0 0-.457.734c0 .45.34.847.769.847h5.721l.01-1.765c.01-.949-.73-1.724-1.645-1.735");
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

.dhr7acfzu {
  stop-color: var(--svg-color--f7ae95, #F7AE95);
}

.dltz-cc1o {
  d: path("M19.887 21.167c0-.374-.304-.624-.386-.7l-.374.363l.23.469z");
}

.dos8-9u_k {
  stop-color: var(--svg-color--ffd1b9, #FFD1B9);
}

.dox4utblj {
  stop-color: var(--svg-color--fdc9b7, #FDC9B7);
  stop-opacity: 0;
}

.dxzww_79w {
  stop-color: var(--svg-color--d89791, #D89791);
}

.e_h5sgb4g {
  stop-color: var(--svg-color--f1baaf, #F1BAAF);
}

.es6zpkbma {
  cx: 12.824px;
  cy: 20.64px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.f1bbqmbqb {
  d: path("M15.663 5.052L14.54 2.804a.377.377 0 0 1 .34-.542h2.244c.28 0 .46.291.34.542l-1.122 2.248a.38.38 0 0 1-.68 0");
}

.f70_ivb1v {
  fill: var(--svg-color--000, #000);
  d: path("M19.493 21.303a.66.66 0 0 0-.664-.663a.66.66 0 0 0-.59.968h1.175a.66.66 0 0 0 .079-.305");
}

.f9d_k7bir {
  fill: var(--svg-color--dfa099, #DFA099);
  d: path("M9.696 18.053c-.15-2.288 1.778-3.248 4.098-3.248h1.713c.32.03.59.231.711.534a3.1 3.1 0 0 0 2.835 1.832h1.563q.208.008.412.01c.754.008 1.4.016 1.3.8l-.062.774h.002l-.265 3.207s-.44 4.3-5.97 4.3s-6.03-4.3-6.03-4.3l-.286-3.651l-.01-.126l-.003-.03z");
}

.fk3wcv_fi {
  cx: 18.48px;
  cy: 20.64px;
  rx: 0.506px;
  ry: 0.256px;
}

.ft5dv1b6b {
  fill: none;
}

.fvy7tabyd {
  d: path("m15.523 21.182l-.66 2.14c-.14.44.19.88.65.88h.98c.46 0 .79-.45.65-.88l-.66-2.14c-.15-.47-.82-.47-.96 0");
}

.g36mx3bsc {
  stop-color: var(--svg-color--d8725f, #D8725F);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g5i-sbckt {
  stop-color: var(--svg-color--f1baaf, #F1BAAF);
  stop-opacity: 0;
}

.gnl0uxdxo {
  stop-color: var(--svg-color--ffc9ad, #FFC9AD);
  stop-opacity: 0;
}

.gur5_240r {
  stop-color: var(--svg-color--ff802a, #FF802A);
}

.h75gmsbeb {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.905 19.792c-.848 0-1.564.585-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.464");
}

.h7sf75x5w {
  stop-color: var(--svg-color--eaa993, #EAA993);
}

.hdoticcnk {
  stop-color: var(--svg-color--62585b, #62585B);
}

.hke44nb4h {
  stop-color: var(--svg-color--fb5b1b, #FB5B1B);
}

.hw-39-xyp {
  fill: var(--svg-color--130b1a, #130B1A);
  d: path("M20.393 18.952c-.07 0-.15-.02-.21-.07c-.01-.01-.77-.57-1.88-.44c-.2.01-.37-.12-.39-.31a.35.35 0 0 1 .31-.39c1.4-.17 2.35.55 2.39.58c.15.12.18.34.06.49c-.07.1-.18.14-.28.14");
}

.ih_n8tb4s {
  stop-color: var(--svg-color--e4380a, #E4380A);
  stop-opacity: 0;
}

.izyqnbcdg {
  stop-color: var(--svg-color--dea198, #DEA198);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jdwtmzbkw {
  stop-color: var(--svg-color--ba847d, #BA847D);
  stop-opacity: 0;
}

.jiyavqyhw {
  stop-color: var(--svg-color--fc6028, #FC6028);
  stop-opacity: 0;
}

.jjy7pyzfk {
  stop-color: var(--svg-color--ffc8b7, #FFC8B7);
  stop-opacity: 0;
}

.jujktlw7p {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.03 19.792c-.848 0-1.564.585-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.464");
}

.k1t018bdv {
  stop-color: var(--svg-color--de9f99, #DE9F99);
  stop-opacity: 0;
}

.k2ef9mb3g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.755 18.056c-.349-.036-1.484 0-2.156.516");
}

.l9-a4ksrj {
  fill: var(--svg-color--d18a85, #D18A85);
  d: path("m15.444 21.446l-.754 2.045c-.16.42.15.862.61.883l.98.045c.459.02.808-.4.688-.824l-.565-2.106c-.13-.462-.799-.493-.96-.043");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m630zdbbe {
  stop-color: var(--svg-color--d8725f, #D8725F);
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

.ml8qh4bmo {
  stop-color: var(--svg-color--e2a693, #E2A693);
}

.mw21cz39d {
  stop-color: var(--svg-color--ff6836, #FF6836);
  stop-opacity: 0;
}

.nrohlub_d {
  d: path("M14.231 21.167c0-.374-.304-.624-.387-.7l-.374.363l.23.469z");
}

.o6h5vobfi {
  d: path("m21.494 6.242l2.37-.79a.38.38 0 0 0 .15-.62l-1.58-1.58c-.2-.2-.53-.12-.62.15l-.79 2.38c-.1.28.18.56.47.46");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp20rs2q {
  stop-color: var(--svg-color--f44e0b, #F44E0B);
}

.pfg89rzer {
  stop-color: var(--svg-color--d89791, #D89791);
  stop-opacity: 0;
}

.pjd1wtbcg {
  stop-color: var(--svg-color--ff9d3d, #FF9D3D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkmpwdtwq {
  d: path("M13.173 20.145a1.158 1.158 0 0 0-1.116 1.463h2.237q.041-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.pm-3hetnk {
  cx: 12.824px;
  cy: 20.64px;
  rx: 0.506px;
  ry: 0.256px;
}

.pmiei2beq {
  stop-color: var(--svg-color--f46a2e, #F46A2E);
}

.pmvvskbdj {
  stop-color: var(--svg-color--eaa993, #EAA993);
  stop-opacity: 0;
}

.pouq8sxtv {
  d: path("M21.029 25.853a3 3 0 0 0-.333.097c-.987.361-1.693 1.268-1.693 2.332c0 .81.405 1.522 1.039 1.98h6.782c1.756 0 3.179-1.356 3.179-3.004c0-1.65-1.423-2.996-3.189-2.996c-.27 0-.54.04-.79.098c-.114.03-.228.058-.332.097z");
}

.q4xs56bfx {
  stop-color: var(--svg-color--c68284, #C68284);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rkma5lbuf {
  stop-color: var(--svg-color--333, #333);
  stop-opacity: 0;
}

.rnv4ixbjn {
  stop-color: var(--svg-color--fbc4ab, #FBC4AB);
}

.sludkgsww {
  stop-color: var(--svg-color--ff9d3d, #FF9D3D);
}

.t727h725g {
  stop-color: var(--svg-color--e57544, #E57544);
  stop-opacity: 0;
}

.t9kf6-dgx {
  d: path("M10.978 25.853c.114.029.228.058.332.097c.987.361 1.693 1.268 1.693 2.332c0 .81-.405 1.522-1.039 1.98H5.181c-1.755 0-3.178-1.356-3.178-3.004c0-1.65 1.423-2.996 3.189-2.996c.27 0 .54.04.79.098c.114.03.228.058.332.097z");
}

.tfe13zb-t {
  d: path("M10.648 26.762c.243 0 .476.051.69.153l3.708 1.766a.82.82 0 0 1 .457.734c0 .45-.34.847-.769.847H9.013l-.01-1.765c-.01-.949.73-1.724 1.645-1.735");
}

.tn5cwfbmj {
  stop-color: var(--svg-color--ff9c2c, #FF9C2C);
}

.tww8s068l {
  stop-color: var(--svg-color--403837, #403837);
}

.ua70ijcgb {
  stop-color: var(--svg-color--399be2, #399BE2);
}

.uwfbj0bza {
  stop-color: var(--svg-color--e5a592, #E5A592);
}

.v-pdexbhk {
  stop-color: var(--svg-color--62585b, #62585B);
  stop-opacity: 0;
}

.vhdej_7rc {
  d: path("m22.188 13.526l-4.517.727c1.423.945 3.892.46 4.735.148z");
}

.vntwdnbat {
  cx: 18.48px;
  cy: 20.64px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.w-i21bcei {
  fill: var(--svg-color--000, #000);
  d: path("M13.836 21.303a.66.66 0 0 0-.663-.663a.66.66 0 0 0-.59.968h1.174a.66.66 0 0 0 .08-.305");
}

.w0bk2cb3c {
  stop-color: var(--svg-color--ffc9ad, #FFC9AD);
}

.wdq8bfb6i {
  stop-color: var(--svg-color--ce939a, #CE939A);
}

.wej4rd4yy {
  d: path("M9.696 18.053c-.15-2.288 1.778-3.248 4.098-3.248h1.713c.32.03.59.231.711.534a3.1 3.1 0 0 0 2.835 1.832h1.563q.208.008.412.01c.754.008 1.4.016 1.3.8l-.062.774h.002l-.265 3.207s-.44 4.3-5.97 4.3s-6.03-4.3-6.03-4.3l-.286-3.651l-.01-.126l-.003-.03z");
}

.wqu1hduus {
  stop-color: var(--svg-color--453e41, #453E41);
}

.wziyle_fm {
  stop-color: var(--svg-color--ff7530, #FF7530);
}

.x-bbadc0e {
  d: path("M9.753 20.012a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xqw25_nlo {
  stop-color: var(--svg-color--c98577, #C98577);
}

.xwi_niyrc {
  stop-color: var(--svg-color--ba847d, #BA847D);
}

.y8gz67bnb {
  stop-color: var(--svg-color--e95252, #E95252);
}

.yasaahjks {
  stop-color: var(--svg-color--fdc9b7, #FDC9B7);
}

.yfgejfb8x {
  fill: var(--svg-color--dba099, #DBA099);
  d: path("m15.523 21.182l-.66 2.14c-.14.44.19.88.65.88h.98c.46 0 .79-.45.65-.88l-.66-2.14c-.15-.47-.82-.47-.96 0");
}

.ygnqhzbrp {
  stop-color: var(--svg-color--ff7919, #FF7919);
}

.yp9pssbjt {
  d: path("M18.83 20.145a1.158 1.158 0 0 0-1.116 1.463h2.237q.04-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.z-ofjjjah {
  d: path("M23.852 11.411a2.97 2.97 0 0 0-1.623-1.34a3.17 3.17 0 0 1-1.733-1.369a2.98 2.98 0 0 0-2.555-1.44c-.41 0-.811.08-1.172.242a1.93 1.93 0 0 1-1.533 0a2.8 2.8 0 0 0-1.162-.242a2.98 2.98 0 0 0-2.524 1.4a3.37 3.37 0 0 1-1.773 1.41a3.02 3.02 0 0 0-1.673 1.43a3.04 3.04 0 0 0 .18 3.121c.22.333.35.716.35 1.118v1.984c0 .574.545 1.037 1.116 1.037l-.043-.577c-.234-2.383 1.723-3.38 4.087-3.38h1.713c.32.03.59.231.711.534a3.1 3.1 0 0 0 2.835 1.832h1.563c.911.04 1.83-.115 1.712.81l-.062.774c.55 0 1.095-.446 1.095-1v-2.024c0-.393.12-.785.35-1.107a2.98 2.98 0 0 0 .14-3.213");
}

.zalfqh_is {
  stop-color: var(--svg-color--403837, #403837);
  stop-opacity: 0;
}

.zga6vzu6c {
  d: path("m10.515 6.244l-2.38-.79a.373.373 0 0 1-.14-.62l1.58-1.58c.2-.2.53-.12.62.15l.79 2.38c.1.28-.18.56-.47.46");
}

.zlbgcf5wc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.286 18.056c.348-.036 1.484 0 2.156.516");
}

.zs4-mpbwk {
  fill: var(--svg-color--130b1a, #130B1A);
  d: path("M11.613 18.952a.35.35 0 0 1-.28-.14a.35.35 0 0 1 .06-.49c.04-.03.99-.75 2.39-.58c.19.02.33.2.31.39s-.19.33-.39.31c-1.11-.13-1.87.43-1.88.44c-.06.05-.14.07-.21.07");
}

.zsvzg4bjp {
  stop-color: var(--svg-color--e57544, #E57544);
}

.zyl1aqefu {
  d: path("M26.919 19.45a3.58 3.58 0 0 0-3.305-2.188H8.312c-1.442 0-2.744.86-3.305 2.189l-2.754 6.641h4.75v4.17h18v-4.15l4.75-.016z");
}

</style>
