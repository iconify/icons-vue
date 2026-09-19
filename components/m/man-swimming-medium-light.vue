<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iCxnB5d)"><path fill="url(#iISwNoe)" class="hq22c7puo"/></g><g filter="url(#iHIVLro)"><path class="pd3ozqbaq"/></g><path fill="url(#iXf6dhe)" class="j__2dbl8c"/><path fill="url(#i9FXMiN)" class="j__2dbl8c"/><path fill="url(#iPHqeQD)" class="j__2dbl8c"/><circle fill="url(#iRZz2QE)" class="premirkyr"/><g filter="url(#iKFz5LX)"><circle fill="url(#iO1A1Jc)" class="njmctzbwn"/></g><circle class="l684lpbti"/><g filter="url(#ioslB2c)"><circle class="k05_hc75e"/></g><path class="cpkbjhbqe"/><path fill="url(#iVb8Y7u)" class="uhr4ypblr"/><g filter="url(#iEM1IOe)"><path fill="url(#iypyAVb)" class="pjhiw06nd"/><path fill="url(#iYXArbQ)" class="pjhiw06nd"/><path fill="url(#i8WBGic)" class="pjhiw06nd"/><path fill="url(#iz4dSgd)" class="pjhiw06nd"/></g><g filter="url(#iQR1OUb)"><path class="a67zszbnw"/></g><g filter="url(#iIemWBb)"><path fill="url(#iKTFDec)" class="hz8z6ybug"/></g><g filter="url(#idIVCPd)"><circle stroke="url(#id7INCd)" class="t_ahmacni"/></g><circle class="djlop0b9r"/><g filter="url(#iT8bSOd)"><path class="gh0rpsb-s"/></g><g filter="url(#ilBosbe)"><path class="n3l2t6b1b"/><path fill="url(#i6DSbSc)" class="ur6owyxzy"/></g><path fill="url(#iIWkcQd)" transform="rotate(45.489 14.576 13.488)" class="d1op3cbdr"/><path fill="url(#iUtlsMc)" transform="rotate(45.489 14.576 13.488)" class="d1op3cbdr"/><path fill="url(#iKTWmOe)" class="dtlo7bbjo"/><path fill="url(#imhuo2c)" class="dtlo7bbjo"/><path fill="url(#iYjs9ke)" class="dtlo7bbjo"/><path class="s0xuyuogh"/><path fill="url(#ieuK6Dc)" class="e0q3adb4l"/><path fill="url(#ioT2Gxb)" class="e0q3adb4l"/><path fill="url(#i4zaWid)" class="e0q3adb4l"/><g filter="url(#i6XGnAD)"><path fill="url(#iB0nLpb)" class="qv9su6bdk"/></g><path clip-rule="evenodd" class="q0mle0b1f"/><g filter="url(#iNgKBYI)"><path clip-rule="evenodd" class="vtuno087z"/></g><g filter="url(#imKykCd)"><path fill="url(#iKSN7XZ)" class="e4pmr_b_l"/></g><path clip-rule="evenodd" class="oz7ue17ow"/><g filter="url(#iWhuSWj)"><path stroke="url(#iCTe8gQ)" clip-rule="evenodd" class="fz2afrwxr"/></g><path fill="url(#iOvbDsb)" class="qis6k4bsu"/><path fill="url(#i60IONc)" class="qis6k4bsu"/><path fill="url(#iYDivIc)" class="qis6k4bsu"/><path fill="url(#ios3ezE)" clip-rule="evenodd" class="zzremtast"/><path fill="url(#iDV4ofX)" clip-rule="evenodd" class="p40y1eg2v"/><path fill="url(#iyY1qQb)" clip-rule="evenodd" class="jced6l6qw"/><path fill="url(#ijcqO0Z)" clip-rule="evenodd" class="ln4e9ebwd"/><g filter="url(#ibajQGc)"><path clip-rule="evenodd" class="ty0kushdy"/></g><path fill="url(#ilDDS5e)" class="rg2z0enhu"/><g filter="url(#iGJDDub)"><path class="b_9jtewkq"/></g><defs><linearGradient id="iISwNoe" x1="26.833" x2="2.047" y1="16.555" y2="16.555" gradientUnits="userSpaceOnUse"><stop class="q8sgc5k5k"/><stop offset="1" class="o5v952b3t"/></linearGradient><linearGradient id="iypyAVb" x1="19.353" x2="15.291" y1="14.865" y2="19.711" gradientUnits="userSpaceOnUse"><stop class="d0zw7oq6w"/><stop offset=".886" class="cs1vkybxa"/></linearGradient><linearGradient id="iKTFDec" x1="26.833" x2="2.047" y1="23.617" y2="23.617" gradientUnits="userSpaceOnUse"><stop class="t8k4gwbbc"/><stop offset="1" class="kpw0uhrkg"/></linearGradient><linearGradient id="id7INCd" x1="17.219" x2="17.188" y1="17.623" y2="15.717" gradientUnits="userSpaceOnUse"><stop class="rzorcbc7r"/><stop offset="1" class="lt8zy5hkm"/></linearGradient><linearGradient id="iIWkcQd" x1="14.945" x2="14.954" y1="13.662" y2="14.611" gradientUnits="userSpaceOnUse"><stop class="uhfoyqb3x"/><stop offset="1" class="eb0haibji"/></linearGradient><linearGradient id="iKTWmOe" x1="16.327" x2="17.416" y1="11.358" y2="11.181" gradientUnits="userSpaceOnUse"><stop class="nd7thpbgb"/><stop offset="1" class="fs5c4ebko"/></linearGradient><linearGradient id="imhuo2c" x1="16.702" x2="16.815" y1="10.625" y2="10.695" gradientUnits="userSpaceOnUse"><stop offset=".354" class="r7rn_bcmx"/><stop offset="1" class="ht-1xqb8g"/></linearGradient><linearGradient id="iYjs9ke" x1="17.308" x2="17.227" y1="11.064" y2="11.015" gradientUnits="userSpaceOnUse"><stop class="hb9tx9b6i"/><stop offset="1" class="ppgh7wbyg"/></linearGradient><linearGradient id="ioT2Gxb" x1="11.273" x2="11.147" y1="17.065" y2="16.87" gradientUnits="userSpaceOnUse"><stop offset=".145" class="u8ol5ho1k"/><stop offset="1" class="bbcrpz64i"/></linearGradient><linearGradient id="i4zaWid" x1="10.812" x2="10.858" y1="16.394" y2="16.469" gradientUnits="userSpaceOnUse"><stop class="bwf4x3cld"/><stop offset="1" class="a5orf1efs"/></linearGradient><linearGradient id="iB0nLpb" x1="16.766" x2="15.219" y1="12.154" y2="13.67" gradientUnits="userSpaceOnUse"><stop class="t40s1ccrt"/><stop offset="1" class="vjkwz1bxm"/></linearGradient><linearGradient id="iKSN7XZ" x1="13.977" x2="12.43" y1="14.912" y2="16.428" gradientUnits="userSpaceOnUse"><stop class="ol7r9kndd"/><stop offset="1" class="xs-q3bbyy"/></linearGradient><linearGradient id="iCTe8gQ" x1="14.269" x2="12.127" y1="14.615" y2="16.661" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qi1y9bzby"/><stop offset=".322" class="f-nlkoezi"/><stop offset=".768" class="qi1y9bzby"/></linearGradient><linearGradient id="ios3ezE" x1="8.205" x2="11.23" y1="3.844" y2="3.527" gradientUnits="userSpaceOnUse"><stop class="l2jvne_2k"/><stop offset="1" class="gw4pa76xg"/></linearGradient><linearGradient id="iDV4ofX" x1="6.827" x2="10.357" y1="5.07" y2="4.877" gradientUnits="userSpaceOnUse"><stop class="l2jvne_2k"/><stop offset="1" class="gw4pa76xg"/></linearGradient><linearGradient id="iyY1qQb" x1="6.711" x2="10.654" y1="6.083" y2="5.87" gradientUnits="userSpaceOnUse"><stop class="l2jvne_2k"/><stop offset="1" class="gw4pa76xg"/></linearGradient><linearGradient id="ijcqO0Z" x1="7.225" x2="10.521" y1="6.623" y2="6.456" gradientUnits="userSpaceOnUse"><stop class="l2jvne_2k"/><stop offset="1" class="gw4pa76xg"/></linearGradient><radialGradient id="iXf6dhe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.875 18.583 4.383)scale(6.23829 9.65927)" gradientUnits="userSpaceOnUse"><stop class="l1d8gzbpr"/><stop offset="1" class="hfjpw3r3n"/></radialGradient><radialGradient id="i9FXMiN" cx="0" cy="0" r="1" gradientTransform="matrix(5.40625 1.9375 -3.91835 10.93347 16.64 17.686)" gradientUnits="userSpaceOnUse"><stop class="n8x10_yyu"/><stop offset="1" class="hf6gjo7so"/></radialGradient><radialGradient id="iPHqeQD" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 .59375 -4.82693 -1.65131 22.031 14.904)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="e53cpys3y"/><stop offset="1" class="izl0csmmw"/></radialGradient><radialGradient id="iRZz2QE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01562 .92188 -.5107 -.56264 18.655 11.266)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="uh4sajbra"/><stop offset="1" class="n5u671d-u"/></radialGradient><radialGradient id="iO1A1Jc" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 -.30469 .39566 .41595 17.912 11.854)" gradientUnits="userSpaceOnUse"><stop class="qkzq6ngxm"/><stop offset="1" class="qsbfs9brs"/></radialGradient><radialGradient id="iVb8Y7u" cx="0" cy="0" r="1" gradientTransform="matrix(-.96094 .57072 -1.33444 -2.24682 11.587 16.99)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="sf7txh8tg"/><stop offset="1" class="lm8e5jb5s"/></radialGradient><radialGradient id="iYXArbQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.62564 5.1713 -5.97735 1.87902 16.13 15.085)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="dz0jipb-b"/><stop offset="1" class="gb6fkji1r"/></radialGradient><radialGradient id="i8WBGic" cx="0" cy="0" r="1" gradientTransform="rotate(46.245 -7.488 25.085)scale(2.03959 2.08955)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="lelh2xe6v"/><stop offset="1" class="nea38by1j"/></radialGradient><radialGradient id="iz4dSgd" cx="0" cy="0" r="1" gradientTransform="rotate(50.187 -9.927 21.395)scale(2.10506 2.28731)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="bruh6vbyh"/><stop offset="1" class="rmf6m6b3y"/></radialGradient><radialGradient id="i6DSbSc" cx="0" cy="0" r="1" gradientTransform="rotate(135.14 5.032 10.976)scale(.85969 .22297)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="hxo-hsbpj"/><stop offset="1" class="pdslbmrwt"/></radialGradient><radialGradient id="iUtlsMc" cx="0" cy="0" r="1" gradientTransform="rotate(90.613 .817 14.107)scale(.28732 .60402)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="wjyjhxryd"/><stop offset="1" class="y01zyrbyt"/></radialGradient><radialGradient id="ieuK6Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-.49002 .31976 -.36893 -.56538 11.838 16.22)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="y84i3jbqp"/><stop offset="1" class="mn36x_bue"/></radialGradient><radialGradient id="iOvbDsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.98375 -2.84815 4.15752 -4.35547 14.232 11.827)" gradientUnits="userSpaceOnUse"><stop class="vlvwusbfo"/><stop offset="1" class="p6ttd9f2t"/></radialGradient><radialGradient id="i60IONc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.62339 -2.71253 4.39512 -10.73188 14.707 12.573)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="rhchqfjux"/><stop offset="1" class="zutq5mb1t"/></radialGradient><radialGradient id="iYDivIc" cx="0" cy="0" r="1" gradientTransform="rotate(-166.638 8.09 5.425)scale(6.57907 6.85827)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="rhchqfjux"/><stop offset="1" class="upjjwiblx"/></radialGradient><radialGradient id="ilDDS5e" cx="0" cy="0" r="1" gradientTransform="matrix(6.37158 .5409 -.31404 3.69927 10.642 4.1)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="dvwb7ebev"/><stop offset="1" class="h-knxwkhr"/></radialGradient><filter id="iCxnB5d" width="28.306" height="9.762" x="1.847" y="12.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.584314 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23161" result="effect2_innerShadow_3987_23161"/></filter><filter id="iHIVLro" width="19.969" height="19.969" x="10.642" y="1.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.568627 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.505882 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23161" result="effect2_innerShadow_3987_23161"/></filter><filter id="iKFz5LX" width="2.053" height="2.053" x="16.759" y="10.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23161" stdDeviation=".075"/></filter><filter id="ioslB2c" width="2.044" height="2.044" x="11.179" y="16.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23161" stdDeviation=".1"/></filter><filter id="iEM1IOe" width="10.005" height="10.019" x="10.508" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.462745 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/></filter><filter id="iQR1OUb" width="2.645" height="2.414" x="15.001" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.682353 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/></filter><filter id="iIemWBb" width="28.306" height="9.762" x="1.847" y="19.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.580392 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.482353 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23161" result="effect2_innerShadow_3987_23161"/></filter><filter id="idIVCPd" width="2.217" height="2.217" x="15.887" y="15.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23161" stdDeviation=".1"/></filter><filter id="iT8bSOd" width="3.106" height="3.164" x="13.726" y="13.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23161" stdDeviation=".25"/></filter><filter id="ilBosbe" width="2.203" height="2.458" x="14.338" y="13.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.482353 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/><feGaussianBlur result="effect2_foregroundBlur_3987_23161" stdDeviation=".05"/></filter><filter id="i6XGnAD" width="2.23" height="2.219" x="14.699" y="11.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.631373 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23161" result="effect2_innerShadow_3987_23161"/></filter><filter id="iNgKBYI" width="2.872" height="2.874" x="14.46" y="11.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23161" stdDeviation=".075"/></filter><filter id="imKykCd" width="2.23" height="2.219" x="11.909" y="14.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.564706 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23161" result="effect2_innerShadow_3987_23161"/></filter><filter id="iWhuSWj" width="2.872" height="2.874" x="11.68" y="14.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23161" stdDeviation=".075"/></filter><filter id="ibajQGc" width="4.333" height="3.319" x="7.677" y="5.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.517647 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23161"/></filter><filter id="iGJDDub" width="10.371" height="13.323" x="17.114" y="4.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23161" stdDeviation=".35"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-swimming-medium-light" /></template>
<style>
.a5orf1efs {
  stop-color: var(--svg-color--504b5b, #504B5B);
  stop-opacity: 0;
}

.a67zszbnw {
  fill: var(--svg-color--e8c5a0, #E8C5A0);
  d: path("m16.642 9.375l.859 1.336c.096.141.225.492.08.878c-.39-.418-.739-.781-.986-1.026c-.079-.078-.224-.182-.543-.176c-.22.004-.504.022-.728.036h-.003l-.32-.196z");
}

.b_9jtewkq {
  fill: var(--svg-color--f3c0a3, #F3C0A3);
  d: path("M20.251 7.45c-.675-1.474-1.906-1.968-2.437-2.03c1.468-.157 2.672.789 3.156 1.656l5.814 10.25l-2.533-1.282c-1.052-2.25-3.325-7.118-4-8.593");
}

.bbcrpz64i {
  stop-color: var(--svg-color--443873, #443873);
  stop-opacity: 0;
}

.bruh6vbyh {
  stop-color: var(--svg-color--ab717c, #AB717C);
}

.bwf4x3cld {
  stop-color: var(--svg-color--504b5b, #504B5B);
}

.cpkbjhbqe {
  fill: var(--svg-color--c494a0, #C494A0);
  d: path("m10.83 17.399l-1.368-.93l1.101-1.266L11.79 17.4c-.294.294-.763.122-.96 0");
}

.cs1vkybxa {
  stop-color: var(--svg-color--b37783, #B37783);
}

.d0zw7oq6w {
  stop-color: var(--svg-color--fdc9a7, #FDC9A7);
}

.d1op3cbdr {
  d: path("M14.576 13.488h.758v1.123h-.758z");
}

.djlop0b9r {
  cx: 16.996px;
  cy: 16.693px;
  r: 0.809px;
  fill: var(--svg-color--87014e, #87014E);
}

.dtlo7bbjo {
  d: path("M17.132 10.162a.1.1 0 0 1 .122-.036q.016.008.027.024l.292.421l.01.02a.2.2 0 0 1-.023.173l-.73 1.13l-.605-.41z");
}

.dvwb7ebev {
  stop-color: var(--svg-color--c99878, #C99878);
}

.dz0jipb-b {
  stop-color: var(--svg-color--d59e95, #D59E95);
  stop-opacity: 0;
}

.e0q3adb4l {
  d: path("M10.81 17.382c-.046.03-.083.05-.165 0l-.428-.283a.1.1 0 0 1-.027-.03a.1.1 0 0 1 .039-.12l1.538-1.06l.27.704z");
}

.e4pmr_b_l {
  d: path("M12.745 14.716a.821.821 0 0 1 1.147 1.175l-.487.476a.821.821 0 1 1-1.148-1.175z");
}

.e53cpys3y {
  stop-color: var(--svg-color--bc7e5b, #BC7E5B);
}

.eb0haibji {
  stop-color: var(--svg-color--413251, #413251);
}

.f-nlkoezi {
  stop-color: var(--svg-color--5f5669, #5F5669);
  stop-opacity: 0;
}

.fs5c4ebko {
  stop-color: var(--svg-color--4c4055, #4C4055);
}

.ft5dv1b6b {
  fill: none;
}

.fz2afrwxr {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.077 14.604c-.364-.373-1-.41-1.373-.046l-.56.547c-.372.363-.34.99.024 1.362s.977.43 1.35.067l.559-.546c.372-.364.363-1.012 0-1.384Z");
}

.gb6fkji1r {
  stop-color: var(--svg-color--a46379, #A46379);
}

.gh0rpsb-s {
  fill: var(--svg-color--b97b7c, #B97B7C);
  d: path("m15.047 16.282l-.821-1.636l.304-.296l1.588.896a.42.42 0 0 1 .088.666l-.488.481a.42.42 0 0 1-.67-.111");
}

.gw4pa76xg {
  stop-color: var(--svg-color--c69976, #C69976);
}

.h-knxwkhr {
  stop-color: var(--svg-color--e1ac8c, #E1AC8C);
  stop-opacity: 0;
}

.hb9tx9b6i {
  stop-color: var(--svg-color--574e60, #574E60);
}

.hf6gjo7so {
  stop-color: var(--svg-color--e0a580, #E0A580);
  stop-opacity: 0;
}

.hfjpw3r3n {
  stop-color: var(--svg-color--dfa67f, #DFA67F);
}

.hq22c7puo {
  d: path("M3.922 12.139c-.975 0-1.656.49-1.875.734V21.9h27.906v-8.87l-.003-.004c-.623-.545-1.015-.887-2.2-.887c-.906 0-1.67.67-2.05 1.003c-.261.225-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.734-1.914-.734c-.963 0-1.857.666-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.468-1.907.78c-.367.313-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.774l-.007-.007c-.276-.297-1.072-.89-2.047-.89");
}

.ht-1xqb8g {
  stop-color: var(--svg-color--403044, #403044);
  stop-opacity: 0;
}

.hxo-hsbpj {
  stop-color: var(--svg-color--f3c4a7, #F3C4A7);
}

.hz8z6ybug {
  d: path("M3.922 19.201c-.975 0-1.656.49-1.875.735v9.027h27.906v-8.871l-.003-.003c-.623-.545-1.015-.888-2.2-.888c-.906 0-1.67.67-2.05 1.003v.001c-.261.224-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.735-1.914-.735c-.963 0-1.857.667-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.469-1.907.781s-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.775l-.007-.006c-.276-.297-1.072-.89-2.047-.89");
}

.izl0csmmw {
  stop-color: var(--svg-color--c6916f, #C6916F);
  stop-opacity: 0;
}

.j__2dbl8c {
  d: path("M17.313 16.56c-1.688 1.15-3.224 3.25-3.782 4.157c3.25 2.162 7.927 2.172 9.86 1.906l6.53-2.266c-.765-1.304-2.036-2.52-2.53-3l-5.407-2.375c-.937 0-2.562.141-4.672 1.579");
}

.jced6l6qw {
  fill-rule: evenodd;
  d: path("M11.67 4.727a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 1 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.k05_hc75e {
  cx: 12.201px;
  cy: 17.514px;
  r: 0.822px;
  fill: var(--svg-color--a76669, #A76669);
}

.kpw0uhrkg {
  stop-color: var(--svg-color--4184e7, #4184E7);
}

.l1d8gzbpr {
  stop-color: var(--svg-color--eab8a0, #EAB8A0);
}

.l2jvne_2k {
  stop-color: var(--svg-color--d59d7b, #D59D7B);
}

.l684lpbti {
  cx: 12.201px;
  cy: 17.514px;
  r: 1.296px;
  fill: var(--svg-color--ae6e7f, #AE6E7F);
}

.lelh2xe6v {
  stop-color: var(--svg-color--b27a68, #B27A68);
}

.lm8e5jb5s {
  stop-color: var(--svg-color--ae7973, #AE7973);
  stop-opacity: 0;
}

.ln4e9ebwd {
  fill-rule: evenodd;
  d: path("M11.37 5.501a.663.663 0 0 1-.635.69c-1.184.05-2.098.941-2.665 1.871a.662.662 0 1 1-1.131-.69c.65-1.067 1.893-2.427 3.74-2.505a.663.663 0 0 1 .69.634");
}

.lt8zy5hkm {
  stop-color: var(--svg-color--e3a695, #E3A695);
}

.mn36x_bue {
  stop-color: var(--svg-color--483e5b, #483E5B);
  stop-opacity: 0;
}

.n3l2t6b1b {
  fill: var(--svg-color--ddac8e, #DDAC8E);
  d: path("m15.22 16.015l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.634l-.465.457a.4.4 0 0 1-.638-.106");
}

.n5u671d-u {
  stop-color: var(--svg-color--e7ad85, #E7AD85);
}

.n8x10_yyu {
  stop-color: var(--svg-color--a86d65, #A86D65);
}

.nd7thpbgb {
  stop-color: var(--svg-color--574c62, #574C62);
}

.nea38by1j {
  stop-color: var(--svg-color--b27a68, #B27A68);
  stop-opacity: 0;
}

.njmctzbwn {
  cx: 17.785px;
  cy: 11.925px;
  r: 0.877px;
}

.o5v952b3t {
  stop-color: var(--svg-color--3ea5fe, #3EA5FE);
}

.ol7r9kndd {
  stop-color: var(--svg-color--3387e0, #3387E0);
}

.oz7ue17ow {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m14.144 16.149l-.488.476a1.181 1.181 0 1 1-1.65-1.69l.487-.477a1.181 1.181 0 1 1 1.65 1.69m-.238-1.42a.82.82 0 0 0-1.162-.013l-.487.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.162");
}

.p40y1eg2v {
  fill-rule: evenodd;
  d: path("M11.266 3.945a.663.663 0 0 1-.608.714c-1.395.11-2.487 1.076-3.036 1.863a.662.662 0 1 1-1.087-.758c.678-.972 2.085-2.272 4.018-2.426a.663.663 0 0 1 .713.607");
}

.p6ttd9f2t {
  stop-color: var(--svg-color--287ed9, #287ED9);
}

.pd3ozqbaq {
  fill: var(--svg-color--ebb793, #EBB793);
  d: path("M10.642 7.037h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.52h-4.43z");
}

.pdslbmrwt {
  stop-color: var(--svg-color--f3c4a7, #F3C4A7);
  stop-opacity: 0;
}

.pjhiw06nd {
  d: path("M10.509 16.024v-.766l4.562-4.82c.211-.01.662-.045.98-.05c.32-.007.465.097.544.175c.68.672 2.117 2.238 3.101 3.367c.934 1.071.732 2.465.328 2.977c-.609.77-2.003 2.354-3.14 3.054s-2.396-.01-2.883-.453c-.86-.773-2.672-2.403-3.047-2.734c-.375-.332-.453-.638-.445-.75");
}

.ppgh7wbyg {
  stop-color: var(--svg-color--574e60, #574E60);
  stop-opacity: 0;
}

.premirkyr {
  cx: 17.785px;
  cy: 11.925px;
  r: 1.296px;
}

.q0mle0b1f {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m16.933 13.39l-.488.477a1.181 1.181 0 0 1-1.65-1.69l.487-.477a1.182 1.182 0 0 1 1.65 1.69m-.238-1.418a.82.82 0 0 0-1.162-.014l-.487.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.161");
}

.q8sgc5k5k {
  stop-color: var(--svg-color--40aafe, #40AAFE);
}

.qi1y9bzby {
  stop-color: var(--svg-color--5f5669, #5F5669);
}

.qis6k4bsu {
  d: path("M9.102 16.106c-1.483-1.483-1.304-3.838.256-5.61l1.314-1.305c1.687-1.534 4.11-1.73 5.593-.248l.344.345a.217.217 0 0 1 0 .306L9.753 16.45a.217.217 0 0 1-.307 0z");
}

.qkzq6ngxm {
  stop-color: var(--svg-color--e7b18d, #E7B18D);
}

.qsbfs9brs {
  stop-color: var(--svg-color--dea076, #DEA076);
}

.qv9su6bdk {
  d: path("M15.534 11.958a.821.821 0 0 1 1.147 1.175l-.487.476a.821.821 0 0 1-1.148-1.175z");
}

.r7rn_bcmx {
  stop-color: var(--svg-color--403044, #403044);
}

.rg2z0enhu {
  d: path("M10.642 7.037h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.52h-4.457z");
}

.rhchqfjux {
  stop-color: var(--svg-color--3e81b3, #3E81B3);
  stop-opacity: 0;
}

.rmf6m6b3y {
  stop-color: var(--svg-color--ab717c, #AB717C);
  stop-opacity: 0;
}

.rzorcbc7r {
  stop-color: var(--svg-color--dbab9f, #DBAB9F);
}

.s0xuyuogh {
  fill: var(--svg-color--4e496a, #4E496A);
  d: path("M10.81 17.382c-.046.03-.083.05-.165 0l-.428-.283a.1.1 0 0 1-.027-.03a.1.1 0 0 1 .039-.12l1.538-1.06l.27.704z");
}

.sf7txh8tg {
  stop-color: var(--svg-color--ae7973, #AE7973);
}

.t_ahmacni {
  cx: 16.996px;
  cy: 16.693px;
  r: 0.809px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.t40s1ccrt {
  stop-color: var(--svg-color--489be1, #489BE1);
}

.t8k4gwbbc {
  stop-color: var(--svg-color--3f90f0, #3F90F0);
}

.ty0kushdy {
  fill: var(--svg-color--cd9881, #CD9881);
  fill-rule: evenodd;
  d: path("M11.348 7.063c-.585 0-1.22.227-1.659.526c-.31.21-.668.602-.82.805a.662.662 0 1 1-1.058-.8c.202-.266.661-.78 1.133-1.1c.63-.429 1.52-.756 2.404-.756a.662.662 0 1 1 0 1.325");
}

.u8ol5ho1k {
  stop-color: var(--svg-color--443873, #443873);
}

.uh4sajbra {
  stop-color: var(--svg-color--f2c2a2, #F2C2A2);
}

.uhfoyqb3x {
  stop-color: var(--svg-color--52475d, #52475D);
}

.uhr4ypblr {
  d: path("m10.83 17.399l-1.368-.93l1.101-1.266L11.79 17.4c-.294.294-.763.122-.96 0");
}

.upjjwiblx {
  stop-color: var(--svg-color--5c86b9, #5C86B9);
}

.ur6owyxzy {
  d: path("m15.22 16.015l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.634l-.465.457a.4.4 0 0 1-.638-.106");
}

.vjkwz1bxm {
  stop-color: var(--svg-color--4799ea, #4799EA);
}

.vlvwusbfo {
  stop-color: var(--svg-color--58a9fa, #58A9FA);
}

.vtuno087z {
  stroke: var(--svg-color--5c4c6d, #5C4C6D);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.857 11.809c-.364-.372-1-.409-1.373-.045l-.559.546c-.373.364-.34.99.024 1.362c.363.372.976.431 1.348.067l.56-.546c.372-.363.364-1.012 0-1.384Z");
}

.wjyjhxryd {
  stop-color: var(--svg-color--453b50, #453B50);
}

.xs-q3bbyy {
  stop-color: var(--svg-color--2f81cb, #2F81CB);
}

.y01zyrbyt {
  stop-color: var(--svg-color--453b50, #453B50);
  stop-opacity: 0;
}

.y84i3jbqp {
  stop-color: var(--svg-color--483e5b, #483E5B);
}

.zutq5mb1t {
  stop-color: var(--svg-color--3560c1, #3560C1);
}

.zzremtast {
  fill-rule: evenodd;
  d: path("M9.936 4.45c-.557.043-1.037.101-1.262.158a.663.663 0 0 1-.324-1.285c.836-.21 1.78-.262 2.642-.262c.366 0 1.05.296 1.05.662a.66.66 0 0 1-.663.663c-.345 0-.9.023-1.443.064");
}

</style>
