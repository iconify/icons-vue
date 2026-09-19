<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i6XJJ8b)"><path fill="url(#iISwNoe)" class="hq22c7puo"/></g><g filter="url(#iZkMhXm)"><path class="i0pxrj5ff"/></g><path fill="url(#iP7Xftd)" class="j__2dbl8c"/><path fill="url(#iGVc24l)" class="j__2dbl8c"/><path fill="url(#inIo1zb)" class="j__2dbl8c"/><circle fill="url(#idNUI9P)" class="premirkyr"/><g filter="url(#iWRjsJe)"><circle fill="url(#iDPwiEm)" class="njmctzbwn"/></g><circle class="f_v1n5b6w"/><g filter="url(#ilmACEe)"><circle class="tabmnfn9n"/></g><path class="bxpj3s7ww"/><path fill="url(#iIV8T1c)" class="uhr4ypblr"/><g filter="url(#inhrd3c)"><path fill="url(#iLjv72u)" class="pjhiw06nd"/><path fill="url(#iBkCOUd)" class="pjhiw06nd"/><path fill="url(#ifByiRd)" class="pjhiw06nd"/><path fill="url(#iHHKhPc)" class="pjhiw06nd"/></g><g filter="url(#iZTTqFc)"><path class="y2lkn4tly"/></g><g filter="url(#iyB2qec)"><path fill="url(#iKTFDec)" class="hz8z6ybug"/></g><g filter="url(#iYtj2Nc)"><circle stroke="url(#id7INCd)" class="t_ahmacni"/></g><circle class="djlop0b9r"/><g filter="url(#iWoed9q)"><path class="pqv_h0bgd"/></g><g filter="url(#i8O6OEe)"><path class="xze2cp9-k"/><path fill="url(#irvflpe)" class="ur6owyxzy"/></g><path fill="url(#iIWkcQd)" transform="rotate(45.489 14.576 13.488)" class="d1op3cbdr"/><path fill="url(#iUtlsMc)" transform="rotate(45.489 14.576 13.488)" class="d1op3cbdr"/><path fill="url(#iKTWmOe)" class="dtlo7bbjo"/><path fill="url(#imhuo2c)" class="dtlo7bbjo"/><path fill="url(#iYjs9ke)" class="dtlo7bbjo"/><path class="s0xuyuogh"/><path fill="url(#ieuK6Dc)" class="e0q3adb4l"/><path fill="url(#ioT2Gxb)" class="e0q3adb4l"/><path fill="url(#i4zaWid)" class="e0q3adb4l"/><g filter="url(#iRUgZUc)"><path fill="url(#iB0nLpb)" class="qv9su6bdk"/></g><path clip-rule="evenodd" class="qi61eibwi"/><g filter="url(#iq6CR0d)"><path clip-rule="evenodd" class="vtuno087z"/></g><g filter="url(#iuyI9Vc)"><path fill="url(#iKSN7XZ)" class="e4pmr_b_l"/></g><path clip-rule="evenodd" class="w0xaq7i8z"/><g filter="url(#ixIzV7U)"><path stroke="url(#iCTe8gQ)" clip-rule="evenodd" class="fz2afrwxr"/></g><path fill="url(#iOvbDsb)" class="qis6k4bsu"/><path fill="url(#i60IONc)" class="qis6k4bsu"/><path fill="url(#iYDivIc)" class="qis6k4bsu"/><path fill="url(#iKqn1Lc)" clip-rule="evenodd" class="zzremtast"/><path clip-rule="evenodd" class="mxoy8whay"/><path fill="url(#i2GOZXb)" clip-rule="evenodd" class="hvloo2bsa"/><path clip-rule="evenodd" class="yov31dbgq"/><path fill="url(#iLBlXPd)" clip-rule="evenodd" class="jced6l6qw"/><path clip-rule="evenodd" class="m74tglble"/><path fill="url(#iDUb7ec)" clip-rule="evenodd" class="ln4e9ebwd"/><g filter="url(#iTsn78b)"><path clip-rule="evenodd" class="ywicvv73b"/></g><path fill="url(#iVv7gCc)" class="rg2z0enhu"/><g filter="url(#iXM8BWb)"><path class="n3hr9_9ah"/></g><defs><radialGradient id="iP7Xftd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.875 18.583 4.383)scale(6.23829 9.65927)" gradientUnits="userSpaceOnUse"><stop class="qkza4tkjj"/><stop offset="1" class="p-g29ytws"/></radialGradient><radialGradient id="iGVc24l" cx="0" cy="0" r="1" gradientTransform="matrix(5.40625 1.9375 -3.91835 10.93347 16.64 17.686)" gradientUnits="userSpaceOnUse"><stop class="qgmdss-1z"/><stop offset="1" class="vh8h0wvlv"/></radialGradient><radialGradient id="inIo1zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 .59375 -4.82693 -1.65131 22.031 14.904)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ddam2y24q"/><stop offset="1" class="e2coowbrg"/></radialGradient><radialGradient id="idNUI9P" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01562 .92188 -.5107 -.56264 18.655 11.266)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="igx665z_i"/><stop offset="1" class="zfpdrebcu"/></radialGradient><radialGradient id="iDPwiEm" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 -.30469 .39566 .41595 17.912 11.854)" gradientUnits="userSpaceOnUse"><stop class="skl6euwzp"/><stop offset="1" class="dh7n4ztfg"/></radialGradient><radialGradient id="iIV8T1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.96094 .57072 -1.33444 -2.24682 11.587 16.99)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="vmakp5jzq"/><stop offset="1" class="un0gu9ray"/></radialGradient><radialGradient id="iBkCOUd" cx="0" cy="0" r="1" gradientTransform="matrix(1.62564 5.1713 -5.97735 1.87902 16.13 15.085)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="d9x_-fb5p"/><stop offset="1" class="g5wr4t9sk"/></radialGradient><radialGradient id="ifByiRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.49805 1.76563 -1.80888 1.53474 15.436 12.885)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="xi4c_pugf"/><stop offset="1" class="w0ktp0baq"/></radialGradient><radialGradient id="iHHKhPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.24999 1.37647 -1.47443 1.33895 13.152 15.322)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="p4jbl87fs"/><stop offset="1" class="iz7_01bqj"/></radialGradient><radialGradient id="irvflpe" cx="0" cy="0" r="1" gradientTransform="rotate(135.14 5.032 10.976)scale(.85969 .22297)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="qpkqxibzk"/><stop offset="1" class="pdslbmrwt"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iUtlsMc" cx="0" cy="0" r="1" gradientTransform="rotate(90.613 .817 14.107)scale(.28732 .60402)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="wjyjhxryd"/><stop offset="1" class="y01zyrbyt"/></radialGradient><radialGradient id="ieuK6Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-.49002 .31976 -.36893 -.56538 11.838 16.22)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="y84i3jbqp"/><stop offset="1" class="mn36x_bue"/></radialGradient><radialGradient id="iOvbDsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.98375 -2.84815 4.15752 -4.35547 14.232 11.827)" gradientUnits="userSpaceOnUse"><stop class="vlvwusbfo"/><stop offset="1" class="p6ttd9f2t"/></radialGradient><radialGradient id="i60IONc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.62339 -2.71253 4.39512 -10.73188 14.707 12.573)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="rhchqfjux"/><stop offset="1" class="zutq5mb1t"/></radialGradient><radialGradient id="iYDivIc" cx="0" cy="0" r="1" gradientTransform="rotate(-166.638 8.09 5.425)scale(6.57907 6.85827)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="rhchqfjux"/><stop offset="1" class="upjjwiblx"/></radialGradient><radialGradient id="i2GOZXb" cx="0" cy="0" r="1" gradientTransform="rotate(146.787 3.54 4.27)scale(3.43755 1.60167)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="morzxly6g"/><stop offset="1" class="hi8t0xwzs"/></radialGradient><radialGradient id="iLBlXPd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21274 2.13195 -.99864 -1.5049 8.962 7.027)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="morzxly6g"/><stop offset="1" class="hi8t0xwzs"/></radialGradient><radialGradient id="iDUb7ec" cx="0" cy="0" r="1" gradientTransform="rotate(144.615 3.362 5.186)scale(3.29193 1.58011)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="morzxly6g"/><stop offset="1" class="hi8t0xwzs"/></radialGradient><radialGradient id="iVv7gCc" cx="0" cy="0" r="1" gradientTransform="matrix(6.37158 .5409 -.31404 3.69927 10.642 4.1)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="hg6bed3ov"/><stop offset="1" class="h-knxwkhr"/></radialGradient><filter id="i6XJJ8b" width="28.306" height="9.762" x="1.847" y="12.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.584314 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23164" result="effect2_innerShadow_3987_23164"/></filter><filter id="iZkMhXm" width="19.969" height="19.969" x="10.642" y="1.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.607843 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.509804 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23164" result="effect2_innerShadow_3987_23164"/></filter><filter id="iWRjsJe" width="2.053" height="2.053" x="16.759" y="10.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23164" stdDeviation=".075"/></filter><filter id="ilmACEe" width="2.044" height="2.044" x="11.179" y="16.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23164" stdDeviation=".1"/></filter><filter id="inhrd3c" width="10.005" height="10.019" x="10.508" y="10.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.505882 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/></filter><filter id="iZTTqFc" width="2.645" height="2.414" x="15.001" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0313726 0 0 0 0 0.0352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/></filter><filter id="iyB2qec" width="28.306" height="9.762" x="1.847" y="19.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.580392 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.482353 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23164" result="effect2_innerShadow_3987_23164"/></filter><filter id="iYtj2Nc" width="2.217" height="2.217" x="15.887" y="15.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23164" stdDeviation=".1"/></filter><filter id="iWoed9q" width="3.106" height="3.164" x="13.726" y="13.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23164" stdDeviation=".25"/></filter><filter id="i8O6OEe" width="2.203" height="2.458" x="14.338" y="13.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.545098 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/><feGaussianBlur result="effect2_foregroundBlur_3987_23164" stdDeviation=".05"/></filter><filter id="iRUgZUc" width="2.23" height="2.219" x="14.699" y="11.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.631373 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23164" result="effect2_innerShadow_3987_23164"/></filter><filter id="iq6CR0d" width="2.872" height="2.874" x="14.46" y="11.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23164" stdDeviation=".075"/></filter><filter id="iuyI9Vc" width="2.23" height="2.219" x="11.909" y="14.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.564706 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23164" result="effect2_innerShadow_3987_23164"/></filter><filter id="ixIzV7U" width="2.872" height="2.874" x="11.68" y="14.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23164" stdDeviation=".075"/></filter><filter id="iTsn78b" width="4.333" height="3.319" x="7.677" y="5.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.529412 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23164"/></filter><filter id="iXM8BWb" width="10.971" height="13.923" x="16.814" y="4.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23164" stdDeviation=".5"/></filter><linearGradient id="iISwNoe" x1="26.833" x2="2.047" y1="16.555" y2="16.555" gradientUnits="userSpaceOnUse"><stop class="q8sgc5k5k"/><stop offset="1" class="o5v952b3t"/></linearGradient><linearGradient id="iLjv72u" x1="19.353" x2="15.291" y1="14.865" y2="19.711" gradientUnits="userSpaceOnUse"><stop class="wayqrfbdo"/><stop offset=".782" class="gmzqfccqh"/></linearGradient><linearGradient id="iKTFDec" x1="26.833" x2="2.047" y1="23.617" y2="23.617" gradientUnits="userSpaceOnUse"><stop class="t8k4gwbbc"/><stop offset="1" class="kpw0uhrkg"/></linearGradient><linearGradient id="id7INCd" x1="17.219" x2="17.188" y1="17.623" y2="15.717" gradientUnits="userSpaceOnUse"><stop class="rzorcbc7r"/><stop offset="1" class="lt8zy5hkm"/></linearGradient><linearGradient id="iIWkcQd" x1="14.945" x2="14.954" y1="13.662" y2="14.611" gradientUnits="userSpaceOnUse"><stop class="uhfoyqb3x"/><stop offset="1" class="eb0haibji"/></linearGradient><linearGradient id="iKTWmOe" x1="16.327" x2="17.416" y1="11.358" y2="11.181" gradientUnits="userSpaceOnUse"><stop class="nd7thpbgb"/><stop offset="1" class="fs5c4ebko"/></linearGradient><linearGradient id="imhuo2c" x1="16.702" x2="16.815" y1="10.625" y2="10.695" gradientUnits="userSpaceOnUse"><stop offset=".354" class="r7rn_bcmx"/><stop offset="1" class="ht-1xqb8g"/></linearGradient><linearGradient id="iYjs9ke" x1="17.308" x2="17.227" y1="11.064" y2="11.015" gradientUnits="userSpaceOnUse"><stop class="hb9tx9b6i"/><stop offset="1" class="ppgh7wbyg"/></linearGradient><linearGradient id="ioT2Gxb" x1="11.273" x2="11.147" y1="17.065" y2="16.87" gradientUnits="userSpaceOnUse"><stop offset=".145" class="u8ol5ho1k"/><stop offset="1" class="bbcrpz64i"/></linearGradient><linearGradient id="i4zaWid" x1="10.812" x2="10.858" y1="16.394" y2="16.469" gradientUnits="userSpaceOnUse"><stop class="bwf4x3cld"/><stop offset="1" class="a5orf1efs"/></linearGradient><linearGradient id="iB0nLpb" x1="16.766" x2="15.219" y1="12.154" y2="13.67" gradientUnits="userSpaceOnUse"><stop class="t40s1ccrt"/><stop offset="1" class="vjkwz1bxm"/></linearGradient><linearGradient id="iKSN7XZ" x1="13.977" x2="12.43" y1="14.912" y2="16.428" gradientUnits="userSpaceOnUse"><stop class="ol7r9kndd"/><stop offset="1" class="xs-q3bbyy"/></linearGradient><linearGradient id="iCTe8gQ" x1="14.269" x2="12.127" y1="14.615" y2="16.661" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qi1y9bzby"/><stop offset=".322" class="f-nlkoezi"/><stop offset=".768" class="qi1y9bzby"/></linearGradient><linearGradient id="iKqn1Lc" x1="8.205" x2="11.23" y1="3.844" y2="3.527" gradientUnits="userSpaceOnUse"><stop class="cljygbcta"/><stop offset="1" class="o9z30xbsa"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-swimming-light" /></template>
<style>
.a5orf1efs {
  stop-color: var(--svg-color--504b5b, #504B5B);
  stop-opacity: 0;
}

.bbcrpz64i {
  stop-color: var(--svg-color--443873, #443873);
  stop-opacity: 0;
}

.bwf4x3cld {
  stop-color: var(--svg-color--504b5b, #504B5B);
}

.bxpj3s7ww {
  fill: var(--svg-color--282e5c, #282E5C);
  d: path("m10.83 17.399l-1.368-.93l1.101-1.266L11.79 17.4c-.294.294-.763.122-.96 0");
}

.cljygbcta {
  stop-color: var(--svg-color--e7ad91, #E7AD91);
}

.d1op3cbdr {
  d: path("M14.576 13.488h.758v1.123h-.758z");
}

.d9x_-fb5p {
  stop-color: var(--svg-color--deaaa8, #DEAAA8);
  stop-opacity: 0;
}

.ddam2y24q {
  stop-color: var(--svg-color--cb8d71, #CB8D71);
}

.dh7n4ztfg {
  stop-color: var(--svg-color--f4b798, #F4B798);
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

.e0q3adb4l {
  d: path("M10.81 17.382c-.046.03-.083.05-.165 0l-.428-.283a.1.1 0 0 1-.027-.03a.1.1 0 0 1 .039-.12l1.538-1.06l.27.704z");
}

.e2coowbrg {
  stop-color: var(--svg-color--cb8d71, #CB8D71);
  stop-opacity: 0;
}

.e4pmr_b_l {
  d: path("M12.745 14.716a.821.821 0 0 1 1.147 1.175l-.487.476a.821.821 0 1 1-1.148-1.175z");
}

.eb0haibji {
  stop-color: var(--svg-color--413251, #413251);
}

.f_v1n5b6w {
  cx: 12.201px;
  cy: 17.514px;
  r: 1.296px;
  fill: var(--svg-color--b8808d, #B8808D);
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

.g5wr4t9sk {
  stop-color: var(--svg-color--ab7188, #AB7188);
}

.gmzqfccqh {
  stop-color: var(--svg-color--c7949f, #C7949F);
}

.h-knxwkhr {
  stop-color: var(--svg-color--e1ac8c, #E1AC8C);
  stop-opacity: 0;
}

.hb9tx9b6i {
  stop-color: var(--svg-color--574e60, #574E60);
}

.hg6bed3ov {
  stop-color: var(--svg-color--d4a18c, #D4A18C);
}

.hi8t0xwzs {
  stop-color: var(--svg-color--cf997e, #CF997E);
  stop-opacity: 0;
}

.hq22c7puo {
  d: path("M3.922 12.139c-.975 0-1.656.49-1.875.734V21.9h27.906v-8.87l-.003-.004c-.623-.545-1.015-.887-2.2-.887c-.906 0-1.67.67-2.05 1.003c-.261.225-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.734-1.914-.734c-.963 0-1.857.666-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.468-1.907.78c-.367.313-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.774l-.007-.007c-.276-.297-1.072-.89-2.047-.89");
}

.ht-1xqb8g {
  stop-color: var(--svg-color--403044, #403044);
  stop-opacity: 0;
}

.hvloo2bsa {
  fill-rule: evenodd;
  d: path("M11.266 3.945a.663.663 0 0 1-.608.713c-1.395.112-2.487 1.077-3.036 1.864a.663.663 0 0 1-1.087-.759c.678-.97 2.085-2.271 4.018-2.425a.663.663 0 0 1 .713.607");
}

.hz8z6ybug {
  d: path("M3.922 19.201c-.975 0-1.656.49-1.875.735v9.027h27.906v-8.871l-.003-.003c-.623-.545-1.015-.888-2.2-.888c-.906 0-1.67.67-2.05 1.003v.001c-.261.224-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.735-1.914-.735c-.963 0-1.857.667-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.469-1.907.781s-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.775l-.007-.006c-.276-.297-1.072-.89-2.047-.89");
}

.i0pxrj5ff {
  fill: var(--svg-color--f7c5aa, #F7C5AA);
  d: path("M10.642 7.037h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.52h-4.43z");
}

.igx665z_i {
  stop-color: var(--svg-color--ffd3bb, #FFD3BB);
}

.iz7_01bqj {
  stop-color: var(--svg-color--be8888, #BE8888);
  stop-opacity: 0;
}

.j__2dbl8c {
  d: path("M17.313 16.56c-1.688 1.15-3.224 3.25-3.782 4.157c3.25 2.162 7.927 2.172 9.86 1.906l6.53-2.266c-.765-1.304-2.036-2.52-2.53-3l-5.407-2.375c-.937 0-2.562.141-4.672 1.579");
}

.jced6l6qw {
  fill-rule: evenodd;
  d: path("M11.67 4.727a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 1 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.kpw0uhrkg {
  stop-color: var(--svg-color--4184e7, #4184E7);
}

.ln4e9ebwd {
  fill-rule: evenodd;
  d: path("M11.37 5.501a.663.663 0 0 1-.635.69c-1.184.05-2.098.941-2.665 1.871a.662.662 0 1 1-1.131-.69c.65-1.067 1.893-2.427 3.74-2.505a.663.663 0 0 1 .69.634");
}

.lt8zy5hkm {
  stop-color: var(--svg-color--e3a695, #E3A695);
}

.m74tglble {
  fill: var(--svg-color--d5a28e, #D5A28E);
  fill-rule: evenodd;
  d: path("M11.37 5.501a.663.663 0 0 1-.635.69c-1.184.05-2.098.941-2.665 1.871a.662.662 0 1 1-1.131-.69c.65-1.067 1.893-2.427 3.74-2.505a.663.663 0 0 1 .69.634");
}

.mn36x_bue {
  stop-color: var(--svg-color--483e5b, #483E5B);
  stop-opacity: 0;
}

.morzxly6g {
  stop-color: var(--svg-color--cf997e, #CF997E);
}

.mxoy8whay {
  fill: var(--svg-color--d5a28e, #D5A28E);
  fill-rule: evenodd;
  d: path("M11.266 3.945a.663.663 0 0 1-.608.713c-1.395.112-2.487 1.077-3.036 1.864a.663.663 0 0 1-1.087-.759c.678-.97 2.085-2.271 4.018-2.425a.663.663 0 0 1 .713.607");
}

.n3hr9_9ah {
  fill: var(--svg-color--fad1b0, #FAD1B0);
  d: path("M20.251 7.45c-.675-1.474-1.906-1.968-2.437-2.03c1.468-.157 2.672.789 3.156 1.656l5.814 10.25l-2.533-1.282c-1.052-2.25-3.325-7.118-4-8.593");
}

.nd7thpbgb {
  stop-color: var(--svg-color--574c62, #574C62);
}

.njmctzbwn {
  cx: 17.785px;
  cy: 11.925px;
  r: 0.877px;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o5v952b3t {
  stop-color: var(--svg-color--3ea5fe, #3EA5FE);
}

.o9z30xbsa {
  stop-color: var(--svg-color--d8ac90, #D8AC90);
}

.ol7r9kndd {
  stop-color: var(--svg-color--3387e0, #3387E0);
}

.p-g29ytws {
  stop-color: var(--svg-color--f2bcac, #F2BCAC);
}

.p4jbl87fs {
  stop-color: var(--svg-color--be8888, #BE8888);
}

.p6ttd9f2t {
  stop-color: var(--svg-color--287ed9, #287ED9);
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

.pqv_h0bgd {
  fill: var(--svg-color--ca9297, #CA9297);
  d: path("m15.047 16.282l-.821-1.636l.304-.296l1.588.896a.42.42 0 0 1 .088.666l-.488.481a.42.42 0 0 1-.67-.111");
}

.premirkyr {
  cx: 17.785px;
  cy: 11.925px;
  r: 1.296px;
}

.q8sgc5k5k {
  stop-color: var(--svg-color--40aafe, #40AAFE);
}

.qgmdss-1z {
  stop-color: var(--svg-color--bb7c7d, #BB7C7D);
}

.qi1y9bzby {
  stop-color: var(--svg-color--5f5669, #5F5669);
}

.qi61eibwi {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m16.933 13.39l-.488.477a1.181 1.181 0 0 1-1.65-1.69l.487-.477a1.181 1.181 0 0 1 1.65 1.69m-.238-1.418a.82.82 0 0 0-1.162-.014l-.487.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.161");
}

.qis6k4bsu {
  d: path("M9.102 16.106c-1.483-1.483-1.304-3.838.256-5.61l1.314-1.305c1.687-1.534 4.11-1.73 5.593-.248l.344.345a.217.217 0 0 1 0 .306L9.753 16.45a.217.217 0 0 1-.307 0z");
}

.qkza4tkjj {
  stop-color: var(--svg-color--ffdcc2, #FFDCC2);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
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

.rzorcbc7r {
  stop-color: var(--svg-color--dbab9f, #DBAB9F);
}

.s0xuyuogh {
  fill: var(--svg-color--4e496a, #4E496A);
  d: path("M10.81 17.382c-.046.03-.083.05-.165 0l-.428-.283a.1.1 0 0 1-.027-.03a.1.1 0 0 1 .039-.12l1.538-1.06l.27.704z");
}

.skl6euwzp {
  stop-color: var(--svg-color--fcc5a9, #FCC5A9);
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

.tabmnfn9n {
  cx: 12.201px;
  cy: 17.514px;
  r: 0.822px;
  fill: var(--svg-color--b2757c, #B2757C);
}

.u8ol5ho1k {
  stop-color: var(--svg-color--443873, #443873);
}

.uhfoyqb3x {
  stop-color: var(--svg-color--52475d, #52475D);
}

.uhr4ypblr {
  d: path("m10.83 17.399l-1.368-.93l1.101-1.266L11.79 17.4c-.294.294-.763.122-.96 0");
}

.un0gu9ray {
  stop-color: var(--svg-color--080207, #080207);
  stop-opacity: 0;
}

.upjjwiblx {
  stop-color: var(--svg-color--5c86b9, #5C86B9);
}

.ur6owyxzy {
  d: path("m15.22 16.015l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.634l-.465.457a.4.4 0 0 1-.638-.106");
}

.vh8h0wvlv {
  stop-color: var(--svg-color--f1ae9a, #F1AE9A);
  stop-opacity: 0;
}

.vjkwz1bxm {
  stop-color: var(--svg-color--4799ea, #4799EA);
}

.vlvwusbfo {
  stop-color: var(--svg-color--58a9fa, #58A9FA);
}

.vmakp5jzq {
  stop-color: var(--svg-color--080207, #080207);
}

.vtuno087z {
  stroke: var(--svg-color--5c4c6d, #5C4C6D);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.857 11.809c-.364-.372-1-.409-1.373-.045l-.559.546c-.373.364-.34.99.024 1.362c.363.372.976.431 1.348.067l.56-.546c.372-.363.364-1.012 0-1.384Z");
}

.w0ktp0baq {
  stop-color: var(--svg-color--e1b0a2, #E1B0A2);
  stop-opacity: 0;
}

.w0xaq7i8z {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m14.144 16.148l-.488.477a1.182 1.182 0 0 1-1.65-1.691l.487-.476a1.181 1.181 0 1 1 1.65 1.69m-.238-1.419a.82.82 0 0 0-1.162-.013l-.487.476a.821.821 0 1 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.162");
}

.wayqrfbdo {
  stop-color: var(--svg-color--ffe2c6, #FFE2C6);
}

.wjyjhxryd {
  stop-color: var(--svg-color--453b50, #453B50);
}

.xi4c_pugf {
  stop-color: var(--svg-color--e1b0a2, #E1B0A2);
}

.xs-q3bbyy {
  stop-color: var(--svg-color--2f81cb, #2F81CB);
}

.xze2cp9-k {
  fill: var(--svg-color--eebfab, #EEBFAB);
  d: path("m15.22 16.015l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.634l-.465.457a.4.4 0 0 1-.638-.106");
}

.y01zyrbyt {
  stop-color: var(--svg-color--453b50, #453B50);
  stop-opacity: 0;
}

.y2lkn4tly {
  fill: var(--svg-color--322e2f, #322E2F);
  d: path("m16.642 9.375l.859 1.336c.096.141.225.492.08.878c-.39-.418-.739-.781-.986-1.026c-.079-.078-.224-.182-.543-.176c-.22.004-.504.022-.728.036h-.003l-.32-.196z");
}

.y84i3jbqp {
  stop-color: var(--svg-color--483e5b, #483E5B);
}

.yov31dbgq {
  fill: var(--svg-color--d5a28e, #D5A28E);
  fill-rule: evenodd;
  d: path("M11.67 4.727a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 1 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.ywicvv73b {
  fill: var(--svg-color--dfac99, #DFAC99);
  fill-rule: evenodd;
  d: path("M11.348 7.063c-.585 0-1.22.227-1.659.526c-.31.21-.668.602-.82.805a.662.662 0 1 1-1.058-.8c.202-.266.661-.78 1.133-1.1c.63-.429 1.52-.756 2.404-.756a.662.662 0 1 1 0 1.325");
}

.zfpdrebcu {
  stop-color: var(--svg-color--fbc2a4, #FBC2A4);
}

.zutq5mb1t {
  stop-color: var(--svg-color--3560c1, #3560C1);
}

.zzremtast {
  fill-rule: evenodd;
  d: path("M9.936 4.45c-.557.043-1.037.101-1.262.158a.663.663 0 0 1-.324-1.285c.836-.21 1.78-.262 2.642-.262c.366 0 1.05.296 1.05.662a.66.66 0 0 1-.663.663c-.345 0-.9.023-1.443.064");
}

</style>
