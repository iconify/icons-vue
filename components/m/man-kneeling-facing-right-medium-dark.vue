<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ie6NMoc)"><path class="dz21q-40r"/></g><g filter="url(#i7fwS7d)"><path stroke="url(#iJ0VMBq)" class="a53npacec"/></g><path fill="url(#iqZIqud)" class="g-qq3ibor"/><g filter="url(#iF0W1Ug)"><path class="ri1zmvb-y"/></g><path fill="url(#iXCK64b)" class="f9v9ozbdu"/><path fill="url(#ihi1d7c)" class="f9v9ozbdu"/><path fill="url(#ifYDL8b)" class="w35ek6xjn"/><g filter="url(#iAvG3de)"><path class="x9hn7nb5p"/><path fill="url(#ijsvioF)" class="wwt3f-2vl"/><path fill="url(#i4ps14d)" class="wwt3f-2vl"/></g><g filter="url(#iWdFH5c)"><path class="bh4x7__-v"/><path fill="url(#ipaE4vc)" class="tb39e92-h"/><path fill="url(#izVntNc)" class="tb39e92-h"/></g><path fill="url(#ihRIsac)" transform="scale(-1 1)rotate(-14.867 26.913 74.109)" class="ofkpelbcu"/><path fill="url(#irtznBd)" transform="scale(-1 1)rotate(-14.867 26.913 74.109)" class="ofkpelbcu"/><path fill="url(#iBAZphd)" transform="scale(-1 1)rotate(-14.867 26.913 74.109)" class="ofkpelbcu"/><path fill="url(#ijT5a6C)" class="l9qfqibeo"/><path fill="url(#irnSRNW)" class="l9qfqibeo"/><path fill="url(#il1UTZb)" class="l9qfqibeo"/><g filter="url(#it3dHCc)"><path class="at_-kr1ue"/><path fill="url(#ipeviZb)" class="urod72ofy"/></g><g filter="url(#itffJOe)"><path class="qs6zccbgj"/></g><g filter="url(#iAQQCgb)"><path class="g0dni_baq"/></g><path fill="url(#i10wMxu)" class="c5jx54b-b"/><path fill="url(#i1xZxyd)" class="c5jx54b-b"/><g filter="url(#iIkJgXb)"><path fill="url(#i4d8HGe)" class="jav0dzbhd"/></g><path fill="url(#ir3nZpE)" class="znevsi9yp"/><g filter="url(#iIXFpEc)"><path fill="url(#iROnkTd)" class="lxyq9ey9t"/><path fill="url(#iRS7lab)" class="lxyq9ey9t"/><path fill="url(#i07jXbb)" class="lxyq9ey9t"/><path fill="url(#idb1L6d)" class="lxyq9ey9t"/></g><g filter="url(#itipi1d)"><path fill="url(#i46xgze)" class="rw2tz8b0r"/><path fill="url(#iem0Ide)" class="rw2tz8b0r"/><path fill="url(#iTdCPOc)" class="rw2tz8b0r"/></g><path fill="url(#iCKPzEe)" class="kshm84bvz"/><path fill="url(#iywKrHd)" class="kshm84bvz"/><path fill="url(#iOTCkxc)" class="kshm84bvz"/><path clip-rule="evenodd" class="pqy6j-bak"/><path class="uvumtyekc"/><path fill="url(#igtVtCd)" class="kv4iulwkd"/><path fill="url(#ivpUnGb)" class="uw-7e6bwm"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -26.23 -40.685)" class="m1l7k9jve"/><g filter="url(#iD5ggvb)"><path clip-rule="evenodd" class="f40b4ibag"/></g><defs><radialGradient id="iJ0VMBq" cx="0" cy="0" r="1" gradientTransform="rotate(-130.67 14.029 9.627)scale(5.34656 3.97082)" gradientUnits="userSpaceOnUse"><stop class="lt2_2ybqi"/><stop offset="1" class="bils69brp"/></radialGradient><radialGradient id="iqZIqud" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 3.29646 -1.78135 .28708 15.776 20.19)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="bmj_fbbea"/><stop offset="1" class="q_g8mnbhc"/></radialGradient><radialGradient id="ihi1d7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03125 -5.37969 0 19.151 17.861)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="nu9hhfe4u"/><stop offset="1" class="t_vl9fbku"/></radialGradient><radialGradient id="ifYDL8b" cx="0" cy="0" r="1" gradientTransform="matrix(.1094 3.14063 -8.2876 .28869 17.557 17.97)" gradientUnits="userSpaceOnUse"><stop offset=".558" class="gwwxm_bpq"/><stop offset=".971" class="xv9roqx4c"/></radialGradient><radialGradient id="ihRIsac" cx="0" cy="0" r="1" gradientTransform="matrix(1.75062 .2869 -.80955 4.93989 .09 1.583)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="z4m0hk31o"/><stop offset="1" class="pp9y_ov5j"/></radialGradient><radialGradient id="irtznBd" cx="0" cy="0" r="1" gradientTransform="rotate(117.861 .923 .84)scale(.83385 .74963)" gradientUnits="userSpaceOnUse"><stop class="ra4kqjbah"/><stop offset="1" class="ng2vn7s5c"/></radialGradient><radialGradient id="ijT5a6C" cx="0" cy="0" r="1" gradientTransform="matrix(3.45312 4 -4.99487 4.31198 14.323 13.486)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="b2o3a7r9l"/><stop offset="1" class="g7ee89odc"/></radialGradient><radialGradient id="irnSRNW" cx="0" cy="0" r="1" gradientTransform="matrix(2.03122 3.14064 -3.13218 2.02576 14.76 11.612)" gradientUnits="userSpaceOnUse"><stop class="oo0a8g8xe"/><stop offset="1" class="hc1x_wbbe"/></radialGradient><radialGradient id="il1UTZb" cx="0" cy="0" r="1" gradientTransform="matrix(3.73437 .23436 -.4261 6.78981 14.837 15.235)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="brpomvbii"/><stop offset="1" class="lmk5_gb2n"/></radialGradient><radialGradient id="ipeviZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.34375 -.8049 -.04293 15.651 15.23)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="a3cmd2asj"/><stop offset="1" class="y3ztz7b1k"/></radialGradient><radialGradient id="i1xZxyd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 1.04686 -.99542 1.2183 15.203 11.611)" gradientUnits="userSpaceOnUse"><stop class="n6csxrxuy"/><stop offset="1" class="obkbkpctx"/></radialGradient><radialGradient id="ir3nZpE" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 9.2 6.741)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="n304-r4kd"/><stop offset=".684" class="uk3jx7nau"/></radialGradient><radialGradient id="iRS7lab" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 16.837 7.59)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="jijo4-b9s"/><stop offset="1" class="ni_rkbnps"/></radialGradient><radialGradient id="i07jXbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 19.733 8.778)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="dd9hd6bwg"/><stop offset="1" class="aw2d6h33n"/></radialGradient><radialGradient id="idb1L6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 18.905 7.637)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="jynvl5b3k"/><stop offset="1" class="b-jom1b0d"/></radialGradient><radialGradient id="i46xgze" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.125 -3.54355 3.8979 14.962 4.928)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="lgum6kbvi"/><stop offset="1" class="ri9ygtemw"/></radialGradient><radialGradient id="iem0Ide" cx="0" cy="0" r="1" gradientTransform="matrix(-.39452 2.68273 -1.18513 -.17428 15.069 5.678)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="x4tqf8rmd"/><stop offset="1" class="m5kggdiwk"/></radialGradient><radialGradient id="iTdCPOc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 -.09374 .18396 -2.94358 20.259 5.543)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="bd_cirbzn"/><stop offset="1" class="u8iayhb4j"/></radialGradient><radialGradient id="iCKPzEe" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 9.062 2.523)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="rovuy_e_s"/><stop offset="1" class="r42gxacgx"/></radialGradient><radialGradient id="iywKrHd" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 5.55 10.625)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="mkaeqfx_v"/><stop offset="1" class="bw90kjbqe"/></radialGradient><radialGradient id="igtVtCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.2 7.665)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ivpUnGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.368 7.686)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><filter id="ie6NMoc" width="7.28" height="8.609" x="10.996" y="19.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.466667 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2073" result="effect2_innerShadow_2_2073"/></filter><filter id="i7fwS7d" width="5.734" height="7.279" x="11.071" y="20.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2073" stdDeviation=".25"/></filter><filter id="iF0W1Ug" width="11.64" height="10.135" x="13.28" y="17.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.490196 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/></filter><filter id="iAvG3de" width="4.352" height="2.364" x="20.218" y="25.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.254902 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/></filter><filter id="iWdFH5c" width="3.579" height="3.542" x="7.83" y="24.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/></filter><filter id="it3dHCc" width="6.876" height="3.179" x="15.419" y="14.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.345098 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2073" result="effect2_innerShadow_2_2073"/></filter><filter id="itffJOe" width="1.071" height="1.439" x="21.358" y="17.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.290196 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/></filter><filter id="iAQQCgb" width="1.196" height="1.065" x="20.878" y="17.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.290196 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/></filter><filter id="iIkJgXb" width="8.168" height="8.42" x="14.276" y="18.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2073" stdDeviation=".375"/></filter><filter id="iIXFpEc" width="4.443" height="5.249" x="15.569" y="5.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/></filter><filter id="itipi1d" width="6.391" height="5.479" x="14.154" y="3.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0862745 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2073" result="effect2_innerShadow_2_2073"/></filter><filter id="iD5ggvb" width="1.117" height=".648" x="18.291" y="6.318" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2073"/></filter><linearGradient id="iXCK64b" x1="15.214" x2="15.214" y1="17.767" y2="18.299" gradientUnits="userSpaceOnUse"><stop class="fy99v1bac"/><stop offset="1" class="l0bg_dlbj"/></linearGradient><linearGradient id="ijsvioF" x1="20.089" x2="21.073" y1="27.033" y2="27.033" gradientUnits="userSpaceOnUse"><stop class="jje8gccwz"/><stop offset="1" class="ifze1vbqw"/></linearGradient><linearGradient id="i4ps14d" x1="21.526" x2="21.526" y1="27.896" y2="27.525" gradientUnits="userSpaceOnUse"><stop class="k1dl65w8i"/><stop offset="1" class="pqpq_lljy"/></linearGradient><linearGradient id="ipaE4vc" x1="11.064" x2="10.378" y1="24.986" y2="25.65" gradientUnits="userSpaceOnUse"><stop class="olt5ljabw"/><stop offset="1" class="xgk77dt3o"/></linearGradient><linearGradient id="izVntNc" x1="8.917" x2="9.132" y1="26.189" y2="26.361" gradientUnits="userSpaceOnUse"><stop offset=".098" class="fwheo7gdw"/><stop offset="1" class="oy9f4cbur"/></linearGradient><linearGradient id="iBAZphd" x1="-.003" x2=".233" y1="1.875" y2="1.869" gradientUnits="userSpaceOnUse"><stop class="ptopy6fga"/><stop offset="1" class="n03q6iq6j"/></linearGradient><linearGradient id="i10wMxu" x1="15.235" x2="17.725" y1="14.236" y2="14.314" gradientUnits="userSpaceOnUse"><stop class="ofo46gsuq"/><stop offset="1" class="lq0qk0brb"/></linearGradient><linearGradient id="i4d8HGe" x1="21.694" x2="15.213" y1="24.783" y2="18.846" gradientUnits="userSpaceOnUse"><stop offset=".552" class="cl3ijcbld"/><stop offset="1" class="v224y-b0w"/></linearGradient><linearGradient id="iROnkTd" x1="17.149" x2="20.012" y1="8.332" y2="8.504" gradientUnits="userSpaceOnUse"><stop class="co18c5bwy"/><stop offset="1" class="kj_uw-bok"/></linearGradient><linearGradient id="iOTCkxc" x1="17.163" x2="16.882" y1="7.508" y2="7.586" gradientUnits="userSpaceOnUse"><stop class="q_8osebjr"/><stop offset="1" class="ay5mqacxq"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-kneeling-facing-right-medium-dark" /></template>
<style>
.a3cmd2asj {
  stop-color: var(--svg-color--906964, #906964);
}

.a53npacec {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.792 20.549c.138.94.573 3.263 1.239 5.337a.5.5 0 0 1-.152.535a.55.55 0 0 1-.538.086c-.689-.243-2.053-.526-3.737-.302");
}

.at_-kr1ue {
  fill: var(--svg-color--835c5a, #835C5A);
  d: path("m17.315 16.033l.04-.781l-1.891-.125c-.047.664-.118 1.594.148 1.984s.765.858 2.2.945a42 42 0 0 0 3.269.032v-.18h.672l.34-.215c.038-.191-.39-.568-.79-.71c-1.254-.45-2.96-.821-3.988-.95");
}

.aw2d6h33n {
  stop-color: var(--svg-color--9a7468, #9A7468);
  stop-opacity: 0;
}

.ay5mqacxq {
  stop-color: var(--svg-color--825c51, #825C51);
  stop-opacity: 0;
}

.b-jom1b0d {
  stop-color: var(--svg-color--845a4e, #845A4E);
  stop-opacity: 0;
}

.b2o3a7r9l {
  stop-color: var(--svg-color--45a7f8, #45A7F8);
}

.bd_cirbzn {
  stop-color: var(--svg-color--514342, #514342);
}

.bh4x7__-v {
  fill: var(--svg-color--443c7f, #443C7F);
  d: path("m10.524 24.72l.885.75l-.406 1.5c-.39.198-1.35.654-2.063.891c-.547.183-.887.06-1.056-.083c-.078-.066-.066-.18 0-.258l2.285-2.768a.25.25 0 0 1 .355-.032");
}

.bils69brp {
  stop-color: var(--svg-color--a49dac, #A49DAC);
  stop-opacity: 0;
}

.bmj_fbbea {
  stop-color: var(--svg-color--6a5a7a, #6A5A7A);
}

.brpomvbii {
  stop-color: var(--svg-color--4b77af, #4B77AF);
  stop-opacity: 0;
}

.bw90kjbqe {
  stop-color: var(--svg-color--7b4845, #7B4845);
}

.c5jx54b-b {
  d: path("M17.724 12.569a1.261 1.261 0 0 0-2.52-.12l-.155 2.775l2.567.153z");
}

.cl3ijcbld {
  stop-color: var(--svg-color--a098a8, #A098A8);
}

.co18c5bwy {
  stop-color: var(--svg-color--825756, #825756);
}

.dd9hd6bwg {
  stop-color: var(--svg-color--9d726c, #9D726C);
}

.dz21q-40r {
  fill: var(--svg-color--97919f, #97919F);
  d: path("M17.27 25.572c.05-1.837-.196-4.492-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.266c-1.062-.266-2.578-.172-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.14 2.372.085 2.43-2.047");
}

.f40b4ibag {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M18.708 6.829c.147-.106.363-.111.5-.111a.2.2 0 1 0 0-.4h-.01c-.128 0-.463 0-.723.186a.2.2 0 0 0 .233.325");
}

.f9v9ozbdu {
  d: path("M22.764 21.064c-.137.575-.807 3.427-1.125 4.782c.573.231 1.39.668 2.067 1.007c.325.163.533.496.443.848a.26.26 0 0 1-.252.195h-3.43a.25.25 0 0 1-.25-.252l.076-7.17c-1.787.443-3.937.809-5.747.262c-1.2-.362-1.266-1.816-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.ft5dv1b6b {
  fill: none;
}

.fwheo7gdw {
  stop-color: var(--svg-color--60608e, #60608E);
}

.fy99v1bac {
  stop-color: var(--svg-color--897694, #897694);
}

.g-qq3ibor {
  d: path("M17.27 25.572c.05-1.837-.196-4.492-.32-5.57l-3.485-.696c.555 3.344 1.328 5.508 1.687 6.266c-1.062-.266-2.578-.172-3.765-.117l-.39 1.516c1.233.125 3.339.522 3.843.648c.562.14 2.372.085 2.43-2.047");
}

.g0dni_baq {
  fill: var(--svg-color--785451, #785451);
  d: path("M21.448 17.701c-.325-.003-.516.178-.57.27c.271.144.499.375.65.566c.1.125.278.17.413.086a.266.266 0 0 0 .079-.39c-.257-.328-.48-.49-.572-.532");
}

.g7ee89odc {
  stop-color: var(--svg-color--3370b9, #3370B9);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gwwxm_bpq {
  stop-color: var(--svg-color--857297, #857297);
  stop-opacity: 0;
}

.hc1x_wbbe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
  stop-opacity: 0;
}

.ifze1vbqw {
  stop-color: var(--svg-color--605f91, #605F91);
  stop-opacity: 0;
}

.jav0dzbhd {
  d: path("m21.682 20.4l-.656 5.492l-.312.125l.43-5.73a.487.487 0 0 0-.482-.527c-.926-.006-3.848 0-4.542 0c-.813 0-1.094-.274-1.094-.649c1.193-.01 4.677-.025 5.664 0s1.04.862.992 1.29");
}

.jijo4-b9s {
  stop-color: var(--svg-color--794b40, #794B40);
}

.jje8gccwz {
  stop-color: var(--svg-color--605f91, #605F91);
}

.jynvl5b3k {
  stop-color: var(--svg-color--845a4e, #845A4E);
}

.k1dl65w8i {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
}

.kj_uw-bok {
  stop-color: var(--svg-color--875d51, #875D51);
}

.kshm84bvz {
  d: path("m17.213 8.346l-.2-1.439a.727.727 0 0 0 .2 1.44");
}

.kv4iulwkd {
  d: path("M18.872 7.686v-.004c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l0bg_dlbj {
  stop-color: var(--svg-color--897694, #897694);
  stop-opacity: 0;
}

.l9qfqibeo {
  d: path("M18.323 13.084c.162 1.15.094 2.636-.016 3.527v1.29h-5.031c.055-2.063.578-4.73 1.367-6.048c.664-1.11 1.422-1.176 2.055-.957c.605.184 1.422.75 1.625 2.188");
}

.lgum6kbvi {
  stop-color: var(--svg-color--35232c, #35232C);
}

.lmk5_gb2n {
  stop-color: var(--svg-color--4b77af, #4B77AF);
}

.lq0qk0brb {
  stop-color: var(--svg-color--3a78c3, #3A78C3);
}

.lt2_2ybqi {
  stop-color: var(--svg-color--a49dac, #A49DAC);
}

.lxyq9ey9t {
  d: path("M19.984 6.892c-.039-.801-.298-1.187-.42-1.3H15.83l-.062 3.163c.866 2.122 3.511 2.213 3.906 1.446s.354-2.381.309-3.309");
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m5kggdiwk {
  stop-color: var(--svg-color--3f3035, #3F3035);
  stop-opacity: 0;
}

.mkaeqfx_v {
  stop-color: var(--svg-color--7b4845, #7B4845);
  stop-opacity: 0;
}

.n03q6iq6j {
  stop-color: var(--svg-color--865f5b, #865F5B);
  stop-opacity: 0;
}

.n304-r4kd {
  stop-color: var(--svg-color--9e746b, #9E746B);
}

.n6csxrxuy {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ng2vn7s5c {
  stop-color: var(--svg-color--744f48, #744F48);
  stop-opacity: 0;
}

.ni_rkbnps {
  stop-color: var(--svg-color--794b40, #794B40);
  stop-opacity: 0;
}

.nu9hhfe4u {
  stop-color: var(--svg-color--774e55, #774E55);
}

.obkbkpctx {
  stop-color: var(--svg-color--4ba6ed, #4BA6ED);
  stop-opacity: 0;
}

.ofkpelbcu {
  d: path("M0 0h1.976v2.198H0z");
}

.ofo46gsuq {
  stop-color: var(--svg-color--439ff0, #439FF0);
}

.olt5ljabw {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
}

.oo0a8g8xe {
  stop-color: var(--svg-color--4aa9ee, #4AA9EE);
}

.oy9f4cbur {
  stop-color: var(--svg-color--60608e, #60608E);
  stop-opacity: 0;
}

.pp9y_ov5j {
  stop-color: var(--svg-color--8d6c64, #8D6C64);
}

.pqpq_lljy {
  stop-color: var(--svg-color--3f2d7e, #3F2D7E);
  stop-opacity: 0;
}

.pqy6j-bak {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M18.732 8.8a.125.125 0 0 0 .002.176c.238.234.582.294.692.305a.125.125 0 1 0 .025-.249c-.093-.01-.366-.061-.542-.234a.125.125 0 0 0-.177.002");
}

.ptopy6fga {
  stop-color: var(--svg-color--865f5b, #865F5B);
}

.q_8osebjr {
  stop-color: var(--svg-color--8a655b, #8A655B);
}

.q_g8mnbhc {
  stop-color: var(--svg-color--766b81, #766B81);
  stop-opacity: 0;
}

.qs6zccbgj {
  fill: var(--svg-color--785451, #785451);
  d: path("m21.401 17.103l-.043.633c.233.182.452.428.603.608a.27.27 0 0 0 .346.059c.117-.072.16-.223.084-.338a3.6 3.6 0 0 0-.99-.962");
}

.r42gxacgx {
  stop-color: var(--svg-color--7f5a4d, #7F5A4D);
}

.ra4kqjbah {
  stop-color: var(--svg-color--744f48, #744F48);
}

.ri1zmvb-y {
  fill: var(--svg-color--968ba1, #968BA1);
  d: path("M22.764 21.064c-.137.575-.807 3.427-1.125 4.782c.573.231 1.39.668 2.067 1.007c.325.163.533.496.443.848a.26.26 0 0 1-.252.195h-3.43a.25.25 0 0 1-.25-.252l.076-7.17c-1.787.443-3.937.809-5.747.262c-1.2-.362-1.266-1.816-1.266-2.875l7.61.078a2.726 2.726 0 0 1 1.874 3.125");
}

.ri9ygtemw {
  stop-color: var(--svg-color--2a1528, #2A1528);
}

.rovuy_e_s {
  stop-color: var(--svg-color--917169, #917169);
}

.rw2tz8b0r {
  d: path("M19.345 6.14c.656 0 .969-.372 1-.837c0-.656-.501-.795-.695-.816c-.22-.024-.305-.047-.61-.262a.9.9 0 0 0-.91-.098c-.148.07-.476.106-.71.035c-.391-.117-.696-.113-.997.118c-.209.16-.363.16-.613.16c-.344 0-.636.154-.856.32c-.657.498-.582 2.207-.258 3.168c.31.92.778 1.027 1.168.992c.47-.042.59-.398.66-.695c.057-.238.201-.99.266-1.238c.136-.062.431-.085.532-.473c.1-.387.492-.432.757-.406c.162.015.61.031 1.266.031");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_vl9fbku {
  stop-color: var(--svg-color--8f7c7f, #8F7C7F);
  stop-opacity: 0;
}

.tb39e92-h {
  d: path("m10.524 24.72l.885.75l-.406 1.5c-.39.198-1.35.654-2.063.891c-.547.183-.887.06-1.056-.083c-.078-.066-.066-.18 0-.258l2.285-2.768a.25.25 0 0 1 .355-.032");
}

.u8iayhb4j {
  stop-color: var(--svg-color--514342, #514342);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uk3jx7nau {
  stop-color: var(--svg-color--8a5752, #8A5752);
}

.urod72ofy {
  d: path("m17.315 16.033l.04-.781l-1.891-.125c-.047.664-.118 1.594.148 1.984s.765.858 2.2.945a42 42 0 0 0 3.269.032v-.18h.672l.34-.215c.038-.191-.39-.568-.79-.71c-1.254-.45-2.96-.821-3.988-.95");
}

.uvumtyekc {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.478 7.686h-.989c0-.392.221-.709.494-.709s.494.317.494.709");
}

.uw-7e6bwm {
  d: path("m19.068 7.686l-.005-.072c0-.186.08-.336.176-.336c.097 0 .176.15.176.336l-.004.072z");
}

.v224y-b0w {
  stop-color: var(--svg-color--a098a8, #A098A8);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w35ek6xjn {
  d: path("M20.293 20.477v-.003c-1.787.443-3.937.809-5.747.262c-1.2-.362-1.266-1.816-1.266-2.875l7.61.078q.4.139.701.337z");
}

.wwt3f-2vl {
  d: path("M20.23 26.474a6.3 6.3 0 0 1 1.413-.642l-.004.014c.433.175 1.005.466 1.55.745q.267.137.517.262c.325.163.533.496.443.848a.26.26 0 0 1-.252.195h-3.43a.25.25 0 0 1-.25-.252z");
}

.x4tqf8rmd {
  stop-color: var(--svg-color--3f3035, #3F3035);
}

.x9hn7nb5p {
  fill: var(--svg-color--55538a, #55538A);
  d: path("M20.23 26.474a6.3 6.3 0 0 1 1.413-.642l-.004.014c.433.175 1.005.466 1.55.745q.267.137.517.262c.325.163.533.496.443.848a.26.26 0 0 1-.252.195h-3.43a.25.25 0 0 1-.25-.252z");
}

.xgk77dt3o {
  stop-color: var(--svg-color--3f3e62, #3F3E62);
  stop-opacity: 0;
}

.xv9roqx4c {
  stop-color: var(--svg-color--7e5e9a, #7E5E9A);
}

.y3ztz7b1k {
  stop-color: var(--svg-color--906964, #906964);
  stop-opacity: 0;
}

.z4m0hk31o {
  stop-color: var(--svg-color--774b48, #774B48);
}

.znevsi9yp {
  d: path("M20.208 7.856a1 1 0 0 1-.258-.457h-.18v1.125c.215.137.523.115.614-.09c.078-.176.02-.394-.176-.578");
}

</style>
