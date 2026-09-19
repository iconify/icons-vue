<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ijro4ld)" class="rc215lbby"/><path fill="url(#iniYcvd)" class="rc215lbby"/><path fill="url(#iNszRJc)" class="rc215lbby"/><g filter="url(#iRnBCdJ)"><path fill="url(#iBGyjac)" class="nhj4i_bms"/><path fill="url(#iuN1f9b)" class="nhj4i_bms"/><path fill="url(#i4Zu9md)" class="nhj4i_bms"/><path fill="url(#iDMVfDh)" class="nhj4i_bms"/></g><path fill="url(#ivOHRgb)" class="wtaramjok"/><path fill="url(#iRVbuyd)" class="wtaramjok"/><path fill="url(#ii0eZ3R)" class="wtaramjok"/><path fill="url(#itGKHDd)" class="wtaramjok"/><path fill="url(#i6DTLOd)" class="wtaramjok"/><g filter="url(#ihd8Mqe)"><path class="rhb4t3bzk"/></g><g filter="url(#i8nrPpe)"><path fill="url(#izPrgyc)" class="gryn5pb4u"/><path fill="url(#i6OCNQo)" class="gryn5pb4u"/></g><g filter="url(#ifKxojc)"><path fill="url(#iSfAq6C)" class="h1c878bbm"/></g><g filter="url(#izNz8Nd)"><path fill="url(#iF6Kv2c)" class="a4bz3r0bf"/><path fill="url(#iksJ4fd)" class="a4bz3r0bf"/><path fill="url(#iJQVC1d)" class="a4bz3r0bf"/><path fill="url(#ihPEozd)" class="a4bz3r0bf"/><path fill="url(#iqVrOdc)" class="a4bz3r0bf"/></g><g filter="url(#ilztcIe)"><circle fill="url(#ikbk5ec)" class="y_8hnfieu"/></g><g filter="url(#iS0k5be)"><circle fill="url(#ilpIvlD)" class="pqt7-zbwk"/></g><circle fill="url(#iycBkee)" class="yzcjkob4x"/><g filter="url(#iYjalId)"><circle fill="url(#isoMosc)" transform="matrix(-1 0 0 1 13.698 11.161)" class="c4qt1x-4l"/></g><g filter="url(#igd9Ese)"><circle fill="url(#iLKmm6b)" transform="matrix(-1 0 0 1 13.865 11.06)" class="vtnx2drof"/></g><circle fill="url(#iR34enG)" transform="matrix(-1 0 0 1 13.951 10.992)" class="z_9umw9an"/><g filter="url(#i2b6Yac)"><path class="eoym5ru3r"/></g><g filter="url(#ix0v76d)"><path class="yxwkngbqm"/></g><circle fill="url(#ixks9Jc)" class="e7u2ypbfg"/><circle fill="url(#inQCawd)" class="q9l1jebxb"/><g filter="url(#ipwNW2b)"><path class="wqdzfcb7w"/></g><g filter="url(#iMCBN8b)"><path class="fck56kbuv"/></g><rect class="rn4dim-yx"/><g filter="url(#iHucENd)"><path fill="url(#iVVrniF)" class="targooq4c"/></g><g filter="url(#iTLGUcc)"><path class="iauo99bxn"/></g><path fill="url(#ih2eiuc)" class="qj2syq4jy"/><g filter="url(#iEotj3d)"><path class="mc8h2rb1y"/></g><g filter="url(#iTViQmd)"><path class="fuerjac6x"/></g><g filter="url(#iFdaAOj)"><path fill="url(#iwFGoUd)" class="fd0kzbb4m"/><path fill="url(#ij7Rkmc)" class="fd0kzbb4m"/></g><g filter="url(#iF7lacW)"><path fill="url(#ioDqbqb)" class="ne66mebaq"/></g><g filter="url(#iUjeTRd)"><path fill="url(#iV2Zemc)" class="cxxzg2bju"/></g><g filter="url(#iQVnk9c)"><path fill="url(#iLRZ0Od)" class="rz3pseb1x"/><path fill="url(#iH2zbTb)" class="rz3pseb1x"/><path fill="url(#iGMJbmd)" class="rz3pseb1x"/><path fill="url(#i1I3fGe)" class="rz3pseb1x"/><path fill="url(#io1iOxe)" class="rz3pseb1x"/></g><g filter="url(#ieiXgge)"><path stroke="url(#iJmcHhe)" class="dgkjjwdep"/></g><g filter="url(#ivgQVZA)"><path stroke="url(#iiCIAsd)" class="rn2u64yrm"/></g><g filter="url(#itRrnrq)"><path stroke="url(#iui7P0U)" class="wq-6-p92q"/></g><g filter="url(#i5LsLsq)"><path fill="url(#iUfcrGe)" class="b9p5wybui"/><path fill="url(#i7LIsNb)" class="b9p5wybui"/></g><g filter="url(#iSTUoUd)"><ellipse stroke="url(#iLmKfud)" transform="rotate(-27.468 15.345 12.9)" class="kickzkblc"/></g><ellipse transform="rotate(-27.468 15.345 12.9)" class="x-dptac0v"/><g filter="url(#ixgtcLc)"><ellipse stroke="url(#i7zfvWb)" transform="scale(-1 1)rotate(-27.468 18.17 40.088)" class="hj7cmvfio"/></g><ellipse transform="scale(-1 1)rotate(-27.468 18.17 40.088)" class="q98qo9jlk"/><g filter="url(#iQzj1xe)"><path stroke="url(#iXrEgnb)" class="tt4fvdb3j"/></g><g filter="url(#iTdJLme)"><path stroke="url(#iv43Qte)" class="cpcptqbqn"/></g><defs><radialGradient id="iniYcvd" cx="0" cy="0" r="1" gradientTransform="rotate(50.194 -11.144 23.056)scale(5.61362 9.99758)" gradientUnits="userSpaceOnUse"><stop class="fg3cc6bsg"/><stop offset="1" class="f4gj-sb6f"/></radialGradient><radialGradient id="iNszRJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 3.34375 -5.37285 -4.4188 19.327 17.576)" gradientUnits="userSpaceOnUse"><stop class="fg3cc6bsg"/><stop offset="1" class="f4gj-sb6f"/></radialGradient><radialGradient id="iBGyjac" cx="0" cy="0" r="1" gradientTransform="rotate(107.103 -1.565 15.01)scale(9.77606 11.8898)" gradientUnits="userSpaceOnUse"><stop class="lhr_3ac9n"/><stop offset="1" class="vbcb-fb1l"/></radialGradient><radialGradient id="iDMVfDh" cx="0" cy="0" r="1" gradientTransform="rotate(173.199 6.048 9.238)scale(3.56333 6.3573)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="zkpn2ibtl"/><stop offset="1" class="q8wgbqbcn"/></radialGradient><radialGradient id="ivOHRgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6565 -9.21497 0 22.342 19.107)" gradientUnits="userSpaceOnUse"><stop class="h-83zabic"/><stop offset="1" class="pzz3gdbly"/></radialGradient><radialGradient id="iRVbuyd" cx="0" cy="0" r="1" gradientTransform="rotate(-71.711 30.086 1.368)scale(12.0768 20.0562)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="bx0l_ccaj"/><stop offset="1" class="qnvqzcc1m"/></radialGradient><radialGradient id="ii0eZ3R" cx="0" cy="0" r="1" gradientTransform="matrix(2.36743 0 0 7.48701 18.889 26.136)" gradientUnits="userSpaceOnUse"><stop class="ko75tfrwy"/><stop offset="1" class="dt1c45b0s"/></radialGradient><radialGradient id="i6DTLOd" cx="0" cy="0" r="1" gradientTransform="rotate(83.726 1.944 23.235)scale(6.00472 4.45914)" gradientUnits="userSpaceOnUse"><stop class="h3226gbct"/><stop offset="1" class="pk30gknce"/></radialGradient><radialGradient id="izPrgyc" cx="0" cy="0" r="1" gradientTransform="rotate(69.679 -1.693 9.992)scale(6.74565 3.89889)" gradientUnits="userSpaceOnUse"><stop class="syb-1rb3h"/><stop offset="1" class="lhjmeebtt"/></radialGradient><radialGradient id="i6OCNQo" cx="0" cy="0" r="1" gradientTransform="matrix(1.20312 1.85937 -.70306 .45492 8.343 8.31)" gradientUnits="userSpaceOnUse"><stop class="j0pn2lbsn"/><stop offset="1" class="w1f16tbss"/></radialGradient><radialGradient id="iF6Kv2c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73748 8.17278 -7.83024 -3.58083 18.281 6.559)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="bw87avb1e"/><stop offset="1" class="aftw2eb7h"/></radialGradient><radialGradient id="iksJ4fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91552 -1.96806 0 15.896 12.977)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="p4wqvab5o"/><stop offset="1" class="qlfvtijmg"/></radialGradient><radialGradient id="iJQVC1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -4.54737 0 21.407 10.92)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="dzmcozbqf"/><stop offset="1" class="naauh9-gp"/></radialGradient><radialGradient id="ihPEozd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.03125 1.73291 0 21.407 9.7)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="lrchco4tn"/><stop offset="1" class="xecuo-e-m"/></radialGradient><radialGradient id="iqVrOdc" cx="0" cy="0" r="1" gradientTransform="rotate(-160.327 7.668 .786)scale(3.20255 1.40165)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="x7oxp5mut"/><stop offset="1" class="j3em52b1z"/></radialGradient><radialGradient id="ilpIvlD" cx="0" cy="0" r="1" gradientTransform="rotate(56.962 -.833 21.065)scale(2.66533)" gradientUnits="userSpaceOnUse"><stop class="s0bq7rbpe"/><stop offset="1" class="eatsizbuc"/></radialGradient><radialGradient id="iycBkee" cx="0" cy="0" r="1" gradientTransform="rotate(90 3.684 14.15)scale(1.13672)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="cs0j_h4cy"/><stop offset="1" class="mvspolbmy"/></radialGradient><radialGradient id="iLKmm6b" cx="0" cy="0" r="1" gradientTransform="rotate(56.962 -.276 1.297)scale(2.66533)" gradientUnits="userSpaceOnUse"><stop class="s0bq7rbpe"/><stop offset="1" class="eatsizbuc"/></radialGradient><radialGradient id="iR34enG" cx="0" cy="0" r="1" gradientTransform="rotate(90 .263 .349)scale(1.13672)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="cs0j_h4cy"/><stop offset="1" class="mvspolbmy"/></radialGradient><radialGradient id="ixks9Jc" cx="0" cy="0" r="1" gradientTransform="rotate(45.31 -.375 20.684)scale(1.02201)" gradientUnits="userSpaceOnUse"><stop class="rjltpq9lx"/><stop offset="1" class="k2ofbphfl"/></radialGradient><radialGradient id="inQCawd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.38672 -1.49536 0 12.885 5.263)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="k2ofbphfl"/><stop offset="1" class="k2ofbphfl"/></radialGradient><radialGradient id="iVVrniF" cx="0" cy="0" r="1" gradientTransform="matrix(1.33417 -1.20215 1.6417 1.82199 26.415 24.497)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="juqts7l5m"/><stop offset="1" class="aj0-5xjbw"/></radialGradient><radialGradient id="ij7Rkmc" cx="0" cy="0" r="1" gradientTransform="rotate(108.969 3.12 13.628)scale(2.21398 4.05568)" gradientUnits="userSpaceOnUse"><stop offset=".266" class="saz7k6bvf"/><stop offset="1" class="re-2avbts"/></radialGradient><radialGradient id="iV2Zemc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62504 4.24999 -5.99388 -2.29184 17.109 2.357)" gradientUnits="userSpaceOnUse"><stop class="se7n-pbsq"/><stop offset="1" class="spvk17-nq"/></radialGradient><radialGradient id="iH2zbTb" cx="0" cy="0" r="1" gradientTransform="rotate(121.317 6.804 20.14)scale(2.27653 2.42296)" gradientUnits="userSpaceOnUse"><stop class="o4xq8p77z"/><stop offset="1" class="azmaa-7wv"/></radialGradient><radialGradient id="iGMJbmd" cx="0" cy="0" r="1" gradientTransform="matrix(2.34037 0 0 .46736 23.645 25.722)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="piafwjb_s"/><stop offset="1" class="opllrac4n"/></radialGradient><radialGradient id="i1I3fGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.62365 0 0 .52393 23.457 27.053)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="piafwjb_s"/><stop offset="1" class="opllrac4n"/></radialGradient><radialGradient id="io1iOxe" cx="0" cy="0" r="1" gradientTransform="matrix(2.75151 0 0 .32903 23.36 28.323)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="piafwjb_s"/><stop offset="1" class="opllrac4n"/></radialGradient><radialGradient id="iUfcrGe" cx="0" cy="0" r="1" gradientTransform="rotate(86.271 2.158 14.074)scale(2.71008 1.38848)" gradientUnits="userSpaceOnUse"><stop class="ew3d07bgx"/><stop offset="1" class="b2-603b0s"/></radialGradient><radialGradient id="i7LIsNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.35938 -3.85008 0 15.896 11.295)" gradientUnits="userSpaceOnUse"><stop offset=".669" class="x6nuu07ue"/><stop offset=".993" class="j8hc429st"/></radialGradient><filter id="iRnBCdJ" width="7.006" height="12.905" x="5.773" y="16.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.478431 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.309804 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4713" result="effect2_innerShadow_13929_4713"/></filter><filter id="ihd8Mqe" width="2.763" height="5.488" x="21.126" y="7.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.415686 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.419608 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4713" result="effect2_innerShadow_13929_4713"/></filter><filter id="i8nrPpe" width="2.763" height="5.038" x="7.844" y="8.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.635294 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="ifKxojc" width="2.496" height="3.5" x="8.58" y="8.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4713" stdDeviation=".125"/></filter><filter id="izNz8Nd" width="11.521" height="14.625" x="10.386" y="3.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.552941 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="ilztcIe" width="3.539" height="3.639" x="16.319" y="9.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.490196 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iS0k5be" width="3.305" height="3.305" x="16.219" y="9.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.690196 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iYjalId" width="3.539" height="3.639" x="11.928" y="9.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.490196 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="igd9Ese" width="3.305" height="3.305" x="12.163" y="9.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.690196 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="i2b6Yac" width="2.805" height="1.71" x="11.717" y="7.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0745098 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="ix0v76d" width="2.805" height="1.71" x="17.265" y="7.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0745098 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="ipwNW2b" width="1.266" height="1.001" x="13.874" y="13.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.74902 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iMCBN8b" width="1.266" height="1.001" x="16.647" y="13.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.74902 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iHucENd" width="1.958" height="3.22" x="25.869" y="22.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.776471 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iTLGUcc" width="5.604" height="23.258" x="24.894" y="1.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.356863 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.196078 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4713" result="effect2_innerShadow_13929_4713"/></filter><filter id="iEotj3d" width="2.66" height="4.233" x="22.258" y="17.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.156863 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iTViQmd" width="7.431" height="22.75" x="21.779" y="1.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.337255 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.313726 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_4713" result="effect2_innerShadow_13929_4713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.470588 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_13929_4713" result="effect3_innerShadow_13929_4713"/></filter><filter id="iFdaAOj" width="11.035" height="10.897" x="10.386" y="8.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0627451 0 0 0 0 0.0235294 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iF7lacW" width="6.788" height="7.848" x="12.503" y="19.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.45098 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_13929_4713"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_13929_4713" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.0784314 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_13929_4713"/></filter><filter id="iUjeTRd" width="5.3" height="4.058" x="13.247" y="1.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0941176 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iQVnk9c" width="5.001" height="5.571" x="23.126" y="24.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.521569 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="ieiXgge" width="2.069" height=".25" x="23.555" y="25.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4713" stdDeviation=".05"/></filter><filter id="ivgQVZA" width="2.069" height=".25" x="23.555" y="26.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4713" stdDeviation=".05"/></filter><filter id="itRrnrq" width="2.069" height=".25" x="23.555" y="28.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4713" stdDeviation=".05"/></filter><filter id="i5LsLsq" width="2.897" height="3.532" x="14.448" y="9.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.545098 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_4713"/></filter><filter id="iSTUoUd" width=".691" height=".715" x="14.999" y="12.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4713" stdDeviation=".025"/></filter><filter id="ixgtcLc" width=".691" height=".715" x="16.097" y="12.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4713" stdDeviation=".025"/></filter><filter id="iQzj1xe" width=".75" height="6.406" x="20.484" y="8.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4713" stdDeviation=".125"/></filter><filter id="iTdJLme" width="1.05" height="6.706" x="10.442" y="8.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_4713" stdDeviation=".2"/></filter><linearGradient id="ijro4ld" x1="17.515" x2="12.515" y1="15.701" y2="26.576" gradientUnits="userSpaceOnUse"><stop class="ute4pq3tr"/><stop offset="1" class="wtnpcgtta"/></linearGradient><linearGradient id="iuN1f9b" x1="12.679" x2="12.001" y1="27.827" y2="27.827" gradientUnits="userSpaceOnUse"><stop class="vqiqi2bbn"/><stop offset="1" class="n4wt7jmeh"/></linearGradient><linearGradient id="i4Zu9md" x1="12.679" x2="12.37" y1="28.276" y2="28.276" gradientUnits="userSpaceOnUse"><stop class="pogysgzkw"/><stop offset="1" class="gug7lhbdb"/></linearGradient><linearGradient id="itGKHDd" x1="18.889" x2="19.132" y1="25.013" y2="25.013" gradientUnits="userSpaceOnUse"><stop class="y-wb67bqn"/><stop offset="1" class="ito8mpqqo"/></linearGradient><linearGradient id="iSfAq6C" x1="10.578" x2="8.83" y1="11.482" y2="9.404" gradientUnits="userSpaceOnUse"><stop class="ri8qzbp1v"/><stop offset="1" class="c0-icsbwd"/></linearGradient><linearGradient id="ikbk5ec" x1="18.088" x2="18.088" y1="9.391" y2="12.931" gradientUnits="userSpaceOnUse"><stop class="fk8t7b6eg"/><stop offset="1" class="qk953tvmu"/></linearGradient><linearGradient id="isoMosc" x1="1.77" x2="1.77" y1="0" y2="3.539" gradientUnits="userSpaceOnUse"><stop class="fk8t7b6eg"/><stop offset="1" class="qk953tvmu"/></linearGradient><linearGradient id="ih2eiuc" x1="29.319" x2="29.319" y1="1.977" y2="3.961" gradientUnits="userSpaceOnUse"><stop offset=".545" class="p-0zct1vy"/><stop offset="1" class="rqsyqg22w"/></linearGradient><linearGradient id="iwFGoUd" x1="15.903" x2="15.903" y1="8.638" y2="19.036" gradientUnits="userSpaceOnUse"><stop class="djjammbep"/><stop offset="1" class="m9376cboj"/></linearGradient><linearGradient id="ioDqbqb" x1="15.897" x2="15.897" y1="19.914" y2="26.262" gradientUnits="userSpaceOnUse"><stop offset=".39" class="qo6mf4b7e"/><stop offset="1" class="e-pao9wmw"/></linearGradient><linearGradient id="iLRZ0Od" x1="27.533" x2="23.457" y1="27.82" y2="27.82" gradientUnits="userSpaceOnUse"><stop class="s_oh1j3nm"/><stop offset=".861" class="j2t9ppb_v"/></linearGradient><linearGradient id="iJmcHhe" x1="25.38" x2="23.522" y1="25.734" y2="25.734" gradientUnits="userSpaceOnUse"><stop class="awwg6_wsl"/><stop offset="1" class="wokoe4blp"/></linearGradient><linearGradient id="iiCIAsd" x1="25.38" x2="23.522" y1="27.053" y2="27.053" gradientUnits="userSpaceOnUse"><stop class="awwg6_wsl"/><stop offset="1" class="wokoe4blp"/></linearGradient><linearGradient id="iui7P0U" x1="25.38" x2="23.522" y1="28.361" y2="28.361" gradientUnits="userSpaceOnUse"><stop class="awwg6_wsl"/><stop offset="1" class="wokoe4blp"/></linearGradient><linearGradient id="iLmKfud" x1="15.186" x2="15.424" y1="13.205" y2="12.827" gradientUnits="userSpaceOnUse"><stop class="p4qmumb7g"/><stop offset="1" class="b1s7hwfcy"/></linearGradient><linearGradient id="i7zfvWb" x1=".083" x2=".321" y1=".566" y2=".189" gradientUnits="userSpaceOnUse"><stop class="p4qmumb7g"/><stop offset="1" class="b1s7hwfcy"/></linearGradient><linearGradient id="iXrEgnb" x1="21.359" x2="21.359" y1="9.248" y2="14.904" gradientUnits="userSpaceOnUse"><stop class="bts97abrd"/><stop offset="1" class="oq7c5gb4s"/></linearGradient><linearGradient id="iv43Qte" x1="11.467" x2="11.467" y1="9.115" y2="14.771" gradientUnits="userSpaceOnUse"><stop class="ksd7txb1v"/><stop offset="1" class="pif0ap43s"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:troll" /></template>
<style>
.a4bz3r0bf {
  d: path("M10.386 7.888a4.5 4.5 0 0 1 4.5-4.5h2.021a4.5 4.5 0 0 1 4.5 4.5v7.079l-5.424 3.046l-5.597-3.14z");
}

.aftw2eb7h {
  stop-color: var(--svg-color--9f9f54, #9F9F54);
}

.aj0-5xjbw {
  stop-color: var(--svg-color--bbdf6f, #BBDF6F);
}

.awwg6_wsl {
  stop-color: var(--svg-color--73972a, #73972A);
  stop-opacity: 0;
}

.azmaa-7wv {
  stop-color: var(--svg-color--b6dc6b, #B6DC6B);
  stop-opacity: 0;
}

.b1s7hwfcy {
  stop-color: var(--svg-color--a2a766, #A2A766);
  stop-opacity: 0;
}

.b2-603b0s {
  stop-color: var(--svg-color--9ea24f, #9EA24F);
}

.b9p5wybui {
  d: path("M15.897 10.197c-.11 0-.21.063-.257.162l-1.147 2.404c-.09.19-.047.418.147.504c.258.114.668.22 1.237.212c.577.009 1.004-.1 1.274-.216c.194-.084.24-.31.148-.5l-1.145-2.404a.28.28 0 0 0-.257-.162");
}

.bts97abrd {
  stop-color: var(--svg-color--4d255c, #4D255C);
}

.bw87avb1e {
  stop-color: var(--svg-color--b9d568, #B9D568);
}

.bx0l_ccaj {
  stop-color: var(--svg-color--994a23, #994A23);
  stop-opacity: 0;
}

.c0-icsbwd {
  stop-color: var(--svg-color--969253, #969253);
}

.c4qt1x-4l {
  r: 1.77px;
}

.cpcptqbqn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.967 9.115v5.656");
}

.cs0j_h4cy {
  stop-color: var(--svg-color--a22c42, #A22C42);
}

.cxxzg2bju {
  d: path("M15.41 5.586a.89.89 0 0 0 .973 0c.485-.319 1.254-.822 1.654-1.073c.586-.367.633-.988.312-1.464c-.24-.319-.633-.315-.882-.313h-.055c-.242 0-.41-.023-.625-.316c-.294-.357-.64-.446-.89-.446s-.597.09-.89.446c-.215.293-.383.316-.625.316h-.056c-.249-.002-.642-.006-.882.313c-.32.476-.273 1.097.313 1.464c.4.251 1.169.754 1.653 1.073");
}

.dgkjjwdep {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.68 25.734h1.818");
}

.djjammbep {
  stop-color: var(--svg-color--3f1d4f, #3F1D4F);
}

.dt1c45b0s {
  stop-color: var(--svg-color--a05640, #A05640);
  stop-opacity: 0;
}

.dzmcozbqf {
  stop-color: var(--svg-color--868045, #868045);
}

.e-pao9wmw {
  stop-color: var(--svg-color--23132f, #23132F);
}

.e7u2ypbfg {
  cx: 14.948px;
  cy: 6.615px;
  r: 0.516px;
}

.eatsizbuc {
  stop-color: var(--svg-color--ffc770, #FFC770);
}

.eoym5ru3r {
  stroke: var(--svg-color--3b2444, #3B2444);
  stroke-linecap: round;
  d: path("M12.217 8.763c.183-.187.852-.601 1.805-.492");
}

.ew3d07bgx {
  stop-color: var(--svg-color--bdd06a, #BDD06A);
}

.f4gj-sb6f {
  stop-color: var(--svg-color--575c26, #575C26);
  stop-opacity: 0;
}

.fck56kbuv {
  fill: var(--svg-color--ffd3a2, #FFD3A2);
  d: path("M17.913 13.786v.876h-1.266l1.056-.968a.125.125 0 0 1 .21.092");
}

.fd0kzbb4m {
  d: path("M10.404 9.074a.436.436 0 0 1 .872 0v4.83h-.003v.55a1.3 1.3 0 0 0 .807 1.202l.933.382c.376.155.808.066 1.094-.223l.687-.688c.278-.309.73-.341.93-.341h.268c.201 0 .695 0 1.07.384l.638.645a1 1 0 0 0 1.094.223l.933-.382a1.3 1.3 0 0 0 .807-1.203v-.549h-.003v-4.83a.436.436 0 0 1 .872 0v4.589l.018 1.796a2 2 0 0 1-1.125 1.818l-2.987 1.455c-.41.2-.86.304-1.317.304h-.177c-.457 0-.907-.104-1.317-.304l-2.987-1.455a2 2 0 0 1-1.125-1.818l.018-1.798z");
}

.fg3cc6bsg {
  stop-color: var(--svg-color--373e13, #373E13);
}

.fk8t7b6eg {
  stop-color: var(--svg-color--5e9836, #5E9836);
}

.ft5dv1b6b {
  fill: none;
}

.fuerjac6x {
  fill: var(--svg-color--a96853, #A96853);
  d: path("M24.154 24.735h.74v-3.514c0-.155.036-.308.105-.447l1.635-3.27a1 1 0 0 0-.062-1.002l-.785-1.177a1 1 0 0 1-.062-1.002l1.746-3.493q.06-.12.111-.241c.125-.3-.114-.604-.437-.604h-1.647a.5.5 0 0 1-.5-.5V8.274a.5.5 0 0 1 .25-.433l2.145-1.237a1 1 0 0 0 .5-.866V2.393c-.007-.086-.03-.37.317-.408h-1.212a1 1 0 0 0-1 1v.502a1 1 0 0 1-.397.798l-2.778 2.1a2 2 0 0 0-.794 1.595v3.507a2 2 0 0 0 .234.938l1.649 3.105a1 1 0 0 1 .011.916l-.77 1.54h1.264a.5.5 0 0 1 .426.76s-1.24 1.442-1.823 2.972l1.028 2.056a1 1 0 0 1 .106.447z");
}

.gryn5pb4u {
  d: path("M8.178 8.13c.797.286 1.95 1.011 2.43 1.368v3.5C9.342 12.483 8.092 10.1 7.85 8.416c-.04-.21.13-.365.328-.285");
}

.gug7lhbdb {
  stop-color: var(--svg-color--9e4f2b, #9E4F2B);
  stop-opacity: 0;
}

.h-83zabic {
  stop-color: var(--svg-color--9a4b23, #9A4B23);
}

.h1c878bbm {
  d: path("M8.834 9.356c.479 1.762 1.28 2.58 1.657 2.876l.336-1.812L8.98 9.248a.098.098 0 0 0-.147.108");
}

.h3226gbct {
  stop-color: var(--svg-color--b67249, #B67249);
}

.hj7cmvfio {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  rx: 0.241px;
  ry: 0.262px;
}

.iauo99bxn {
  fill: var(--svg-color--834e4a, #834E4A);
  d: path("M24.894 24.735h2.104v-3.514a1 1 0 0 1 .105-.447l1.635-3.27a1 1 0 0 0-.062-1.002l-.785-1.177a1 1 0 0 1-.062-1.002l1.746-3.493a4 4 0 0 0 .423-1.79V2.986a1 1 0 0 0-1-1c-.29 0-.629-.017-.788 0c-.38.042-.316.38-.316.427v3.326a1 1 0 0 1-.5.866L25.247 7.84a.5.5 0 0 0-.25.433v1.211a.5.5 0 0 0 .5.5h1.646c.324 0 .563.305.438.604a4 4 0 0 1-.11.24l-1.748 3.494a1 1 0 0 0 .063 1.002l.785 1.177a1 1 0 0 1 .062 1.002L25 20.774a1 1 0 0 0-.105.447z");
}

.ito8mpqqo {
  stop-color: var(--svg-color--91492d, #91492D);
  stop-opacity: 0;
}

.j0pn2lbsn {
  stop-color: var(--svg-color--a4ab57, #A4AB57);
}

.j2t9ppb_v {
  stop-color: var(--svg-color--96a553, #96A553);
}

.j3em52b1z {
  stop-color: var(--svg-color--757d34, #757D34);
  stop-opacity: 0;
}

.j8hc429st {
  stop-color: var(--svg-color--777d41, #777D41);
}

.juqts7l5m {
  stop-color: var(--svg-color--95c544, #95C544);
}

.k2ofbphfl {
  stop-color: var(--svg-color--59942c, #59942C);
}

.kickzkblc {
  cx: 15.345px;
  cy: 12.9px;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  rx: 0.241px;
  ry: 0.262px;
}

.ko75tfrwy {
  stop-color: var(--svg-color--a05640, #A05640);
}

.ksd7txb1v {
  stop-color: var(--svg-color--613673, #613673);
}

.lhjmeebtt {
  stop-color: var(--svg-color--877d4d, #877D4D);
}

.lhr_3ac9n {
  stop-color: var(--svg-color--bf663a, #BF663A);
}

.lrchco4tn {
  stop-color: var(--svg-color--596125, #596125);
}

.m9376cboj {
  stop-color: var(--svg-color--2d1242, #2D1242);
}

.mc8h2rb1y {
  fill: var(--svg-color--814642, #814642);
  d: path("M22.825 21.327s.102.248.195.391a18 18 0 0 1 1.823-2.971a.5.5 0 0 0-.426-.762h-1.263l-.33.659a3 3 0 0 0 0 2.683");
}

.mvspolbmy {
  stop-color: var(--svg-color--9b1038, #9B1038);
}

.n4wt7jmeh {
  stop-color: var(--svg-color--ad6d5c, #AD6D5C);
  stop-opacity: 0;
}

.naauh9-gp {
  stop-color: var(--svg-color--a7ae5a, #A7AE5A);
  stop-opacity: 0;
}

.ne66mebaq {
  d: path("M16.127 20.021a.3.3 0 0 0-.46 0l-2.196 2.613a.25.25 0 0 0 .191.41h.327a.2.2 0 0 1 .15.333l-.81.92a.3.3 0 0 0 .225.498h.887a.4.4 0 0 1 .316.155l.943 1.215a.25.25 0 0 0 .395 0l.942-1.215a.4.4 0 0 1 .316-.155h.887a.3.3 0 0 0 .225-.499l-.81-.919a.2.2 0 0 1 .15-.332h.327a.25.25 0 0 0 .191-.411z");
}

.nhj4i_bms {
  d: path("M12.679 29.763V16.96c-.992.164-2.445.593-4.156 1.984c-1.488 1.29-2.366 3.46-2.718 4.64a.195.195 0 0 0 .19.25h.465a.2.2 0 0 1 .174.3l-.777 1.363a.2.2 0 0 0 .174.299h.488a.2.2 0 0 1 .173.3l-.83 1.43a.2.2 0 0 0 .172.3h.404a.2.2 0 0 1 .178.292l-.843 1.646z");
}

.o4xq8p77z {
  stop-color: var(--svg-color--bce470, #BCE470);
}

.opllrac4n {
  stop-color: var(--svg-color--9fb35a, #9FB35A);
  stop-opacity: 0;
}

.oq7c5gb4s {
  stop-color: var(--svg-color--4d255c, #4D255C);
  stop-opacity: 0;
}

.p-0zct1vy {
  stop-color: var(--svg-color--83524d, #83524D);
}

.p4qmumb7g {
  stop-color: var(--svg-color--a2a766, #A2A766);
}

.p4wqvab5o {
  stop-color: var(--svg-color--888e4f, #888E4F);
}

.piafwjb_s {
  stop-color: var(--svg-color--899c4b, #899C4B);
}

.pif0ap43s {
  stop-color: var(--svg-color--613673, #613673);
  stop-opacity: 0;
}

.pk30gknce {
  stop-color: var(--svg-color--9b502d, #9B502D);
  stop-opacity: 0;
}

.pogysgzkw {
  stop-color: var(--svg-color--9e4f2b, #9E4F2B);
}

.pqt7-zbwk {
  cx: 17.921px;
  cy: 11.06px;
  r: 1.602px;
}

.pzz3gdbly {
  stop-color: var(--svg-color--884842, #884842);
}

.q8wgbqbcn {
  stop-color: var(--svg-color--ac562a, #AC562A);
  stop-opacity: 0;
}

.q98qo9jlk {
  fill: var(--svg-color--2c1633, #2C1633);
  rx: 0.241px;
  ry: 0.262px;
}

.q9l1jebxb {
  cx: 12.885px;
  cy: 5.904px;
  r: 0.746px;
}

.qj2syq4jy {
  d: path("M24.894 24.735h2.104v-3.514a1 1 0 0 1 .105-.447l1.635-3.27a1 1 0 0 0-.062-1.002l-.785-1.177a1 1 0 0 1-.062-1.002l1.746-3.493a4 4 0 0 0 .423-1.79V2.986a1 1 0 0 0-1-1c-.29 0-.629-.017-.788 0c-.38.042-.316.38-.316.427v3.326a1 1 0 0 1-.5.866L25.247 7.84a.5.5 0 0 0-.25.433v1.211a.5.5 0 0 0 .5.5h1.646c.324 0 .563.305.438.604a4 4 0 0 1-.11.24l-1.748 3.494a1 1 0 0 0 .063 1.002l.785 1.177a1 1 0 0 1 .062 1.002L25 20.774a1 1 0 0 0-.105.447z");
}

.qk953tvmu {
  stop-color: var(--svg-color--598e32, #598E32);
}

.qlfvtijmg {
  stop-color: var(--svg-color--888e4f, #888E4F);
  stop-opacity: 0;
}

.qnvqzcc1m {
  stop-color: var(--svg-color--b06c44, #B06C44);
}

.qo6mf4b7e {
  stop-color: var(--svg-color--341b40, #341B40);
}

.rc215lbby {
  d: path("M4.234 29.393c.08-1.838.213-4.893 1.921-7.403c1.672-2.79 4.719-5.352 9.75-5.352s8.078 2.563 9.75 5.352c1.708 2.51 1.838 5.16 1.918 6.997c-.015-.343-1.102.66-1.096.776H4.217z");
}

.re-2avbts {
  stop-color: var(--svg-color--472e59, #472E59);
  stop-opacity: 0;
}

.rhb4t3bzk {
  fill: var(--svg-color--504c2f, #504C2F);
  d: path("M23.556 8.13c-.797.286-1.951 1.011-2.43 1.368v3.5c1.265-.515 2.515-2.898 2.758-4.582c.04-.21-.13-.365-.329-.285");
}

.ri8qzbp1v {
  stop-color: var(--svg-color--847940, #847940);
}

.rjltpq9lx {
  stop-color: var(--svg-color--59932c, #59932C);
}

.rn2u64yrm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.68 27.053h1.818");
}

.rn4dim-yx {
  width: 4.035px;
  height: 0.516px;
  x: 13.877px;
  y: 14.388px;
  fill: var(--svg-color--2e1c32, #2E1C32);
  rx: 0.258px;
}

.rqsyqg22w {
  stop-color: var(--svg-color--83524d, #83524D);
  stop-opacity: 0;
}

.rz3pseb1x {
  d: path("M23.126 25.076c0-.402.329-.734.735-.734h2.751a1.21 1.21 0 0 1 1.215 1.204v3.215c0 .553-.453 1.002-1.012 1.002H23.86a.736.736 0 0 1-.735-.734c0-.287.168-.538.412-.658a.74.74 0 0 1-.412-.66c0-.287.168-.538.412-.658a.74.74 0 0 1-.412-.66c0-.287.168-.538.412-.658a.74.74 0 0 1-.412-.659");
}

.s_oh1j3nm {
  stop-color: var(--svg-color--b9e16e, #B9E16E);
}

.s0bq7rbpe {
  stop-color: var(--svg-color--ffdd7c, #FFDD7C);
}

.saz7k6bvf {
  stop-color: var(--svg-color--472e59, #472E59);
}

.se7n-pbsq {
  stop-color: var(--svg-color--462c59, #462C59);
}

.spvk17-nq {
  stop-color: var(--svg-color--36203f, #36203F);
}

.syb-1rb3h {
  stop-color: var(--svg-color--a5a65b, #A5A65B);
}

.targooq4c {
  d: path("M26.848 22.842a.98.98 0 0 1 .979.979v2.24h-1.958v-2.24c0-.54.44-.98.979-.98");
}

.tt4fvdb3j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.859 9.248v5.656");
}

.ute4pq3tr {
  stop-color: var(--svg-color--77873c, #77873C);
}

.vbcb-fb1l {
  stop-color: var(--svg-color--a05c51, #A05C51);
}

.vqiqi2bbn {
  stop-color: var(--svg-color--ad6d5c, #AD6D5C);
}

.vtnx2drof {
  r: 1.602px;
}

.w1f16tbss {
  stop-color: var(--svg-color--a4ab57, #A4AB57);
  stop-opacity: 0;
}

.wokoe4blp {
  stop-color: var(--svg-color--73972a, #73972A);
}

.wq-6-p92q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.68 28.361h1.818");
}

.wqdzfcb7w {
  fill: var(--svg-color--ffd3a2, #FFD3A2);
  d: path("M13.874 13.786v.876h1.265l-1.056-.968a.125.125 0 0 0-.21.092");
}

.wtaramjok {
  d: path("M18.889 29.763V16.96c.992.164 2.445.593 4.156 1.984c1.488 1.29 2.365 3.46 2.718 4.64a.195.195 0 0 1-.19.25h-.465a.2.2 0 0 0-.174.3l.777 1.363a.2.2 0 0 1-.174.299h-.488a.2.2 0 0 0-.173.3l.83 1.43a.2.2 0 0 1-.172.3h-.404a.2.2 0 0 0-.178.292l.843 1.646z");
}

.wtnpcgtta {
  stop-color: var(--svg-color--a5bb5f, #A5BB5F);
}

.x-dptac0v {
  cx: 15.345px;
  cy: 12.9px;
  fill: var(--svg-color--2c1633, #2C1633);
  rx: 0.241px;
  ry: 0.262px;
}

.x6nuu07ue {
  stop-color: var(--svg-color--777d41, #777D41);
  stop-opacity: 0;
}

.x7oxp5mut {
  stop-color: var(--svg-color--757d34, #757D34);
}

.xecuo-e-m {
  stop-color: var(--svg-color--979851, #979851);
  stop-opacity: 0;
}

.y_8hnfieu {
  cx: 18.088px;
  cy: 11.161px;
  r: 1.77px;
}

.y-wb67bqn {
  stop-color: var(--svg-color--91492d, #91492D);
}

.yxwkngbqm {
  stroke: var(--svg-color--3b2444, #3B2444);
  stroke-linecap: round;
  d: path("M19.57 8.763c-.182-.187-.852-.601-1.805-.492");
}

.yzcjkob4x {
  cx: 17.835px;
  cy: 10.992px;
  r: 0.611px;
}

.z_9umw9an {
  r: 0.611px;
}

.zkpn2ibtl {
  stop-color: var(--svg-color--89320c, #89320C);
}

</style>
