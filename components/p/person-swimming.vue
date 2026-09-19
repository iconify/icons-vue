<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iB3If7c)"><path fill="url(#i3hWgBA)" class="f5o3bbwoj"/></g><g filter="url(#irpJjPe)"><path class="oc9c5r57k"/></g><path fill="url(#ijnrfed)" class="i-gamdbxk"/><path fill="url(#iXeJCfc)" class="i-gamdbxk"/><path fill="url(#iZrTfqU)" class="i-gamdbxk"/><path fill="url(#igiaFNd)" class="itedrub7o"/><path fill="url(#inS9Tgb)" class="rkvqsdrut"/><circle fill="url(#iNFZFVb)" class="hnpfzrzlu"/><g filter="url(#iYowCQb)"><circle class="zowuonbmg"/></g><circle class="dr_nfx0ox"/><circle class="db696fxan"/><path class="brqv9fbno"/><path fill="url(#iEJSvEb)" class="t1bgw6m6y"/><g filter="url(#iQzPxwe)"><path fill="url(#iOB5rue)" class="omkku6bhl"/><path fill="url(#idHGlFe)" class="omkku6bhl"/></g><g filter="url(#iKI3oYb)"><path fill="url(#iKNBjec)" class="kjt8t8beu"/></g><g filter="url(#iFKLHPb)"><circle stroke="url(#io7dQke)" class="v9f4hvapl"/></g><circle class="shho5dbnr"/><g filter="url(#imzcpcd)"><path class="sfpwjtbye"/></g><g filter="url(#iEtqBye)"><path class="dkp5uo1co"/></g><path fill="url(#i5hVk0I)" transform="rotate(45.489 14.576 14.447)" class="zfoyj9b_m"/><path fill="url(#iKoH0uc)" transform="rotate(45.489 14.576 14.447)" class="zfoyj9b_m"/><path class="ketvxen3s"/><path fill="url(#icW56oe)" class="ypt6accsz"/><path fill="url(#ibjLaiR)" class="ypt6accsz"/><path class="oa4_fqjsq"/><path fill="url(#i9TlDgy)" class="v_13ezbio"/><path fill="url(#ibhxFlk)" class="v_13ezbio"/><g filter="url(#ipCknFb)"><path fill="url(#iyKTPGe)" class="wduf44nbu"/></g><path clip-rule="evenodd" class="k1_xog4fv"/><g filter="url(#inXMALI)"><path clip-rule="evenodd" class="rsa-8gb7q"/></g><g filter="url(#iLN3Yqd)"><path fill="url(#i4EDBAb)" class="auivi10da"/></g><path clip-rule="evenodd" class="s1tm77bcz"/><g filter="url(#iix2CIb)"><path stroke="url(#iBZM1es)" clip-rule="evenodd" class="l0y1bewei"/></g><path fill="url(#izyIGxc)" class="bmuo4gvci"/><path fill="url(#icW9JTd)" class="bmuo4gvci"/><path fill="url(#iAC3myc)" class="bmuo4gvci"/><path fill="url(#ilCy3Pe)" class="bmuo4gvci"/><path fill="url(#iw863ve)" clip-rule="evenodd" class="utk49icaf"/><path clip-rule="evenodd" class="q5tuqccgg"/><path fill="url(#ipxYxUc)" clip-rule="evenodd" class="scdz6cc-w"/><path clip-rule="evenodd" class="ff8hjccoa"/><path fill="url(#ilCyzXb)" clip-rule="evenodd" class="p_cqefbjp"/><path clip-rule="evenodd" class="h4_2iqqvt"/><path fill="url(#ifVI2Fz)" clip-rule="evenodd" class="ez-pwjb7i"/><g filter="url(#i3g2T3A)"><path clip-rule="evenodd" class="g-yrcjbos"/></g><path fill="url(#i2qg1ob)" class="ak1dblbqt"/><defs><radialGradient id="ijnrfed" cx="0" cy="0" r="1" gradientTransform="rotate(-21.324 68.355 -31.86)scale(12.5465 22.8637)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="mg2_h_bez"/><stop offset="1" class="gscp5ewot"/></radialGradient><radialGradient id="iXeJCfc" cx="0" cy="0" r="1" gradientTransform="matrix(5.40625 1.9375 -3.91835 10.93347 16.64 18.645)" gradientUnits="userSpaceOnUse"><stop class="r-yyy1bsz"/><stop offset="1" class="mqif30hqe"/></radialGradient><radialGradient id="iZrTfqU" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 .59375 -4.82693 -1.65131 22.031 15.863)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ah1qi0bpq"/><stop offset="1" class="s6eqh9b-p"/></radialGradient><radialGradient id="igiaFNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .61718 -2.20347 -1.8967 13.602 19.785)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="o5grvubsv"/><stop offset="1" class="qjk4gabpx"/></radialGradient><radialGradient id="inS9Tgb" cx="0" cy="0" r="1" gradientTransform="rotate(64.414 -1.083 22.008)scale(2.0442 .95422)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="h0m5e-b1w"/><stop offset="1" class="sbtdeuvbe"/></radialGradient><radialGradient id="iNFZFVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12498 -2.10938 1.2392 -.66089 18.703 13.582)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="p3mcnub9l"/><stop offset="1" class="s1zh3d05d"/></radialGradient><radialGradient id="idHGlFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 5.88499 -6.78343 2.12523 15.36 15.02)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="pqg0n5byu"/><stop offset="1" class="mp1-tzbqs"/></radialGradient><radialGradient id="iKoH0uc" cx="0" cy="0" r="1" gradientTransform="rotate(90.613 .343 14.587)scale(.28732 .60402)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="wjyjhxryd"/><stop offset="1" class="y01zyrbyt"/></radialGradient><radialGradient id="izyIGxc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 -2.62501 3.8318 -4.01424 14.203 12.738)" gradientUnits="userSpaceOnUse"><stop class="taiuw254n"/><stop offset="1" class="wk7-7rb8w"/></radialGradient><radialGradient id="icW9JTd" cx="0" cy="0" r="1" gradientTransform="rotate(-157.729 8.642 5.272)scale(6.59658 10.6884)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="sr-z703qg"/><stop offset="1" class="ue4dw-rff"/></radialGradient><radialGradient id="iAC3myc" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 -1.98437 .81115 .08303 8.766 14.582)" gradientUnits="userSpaceOnUse"><stop class="mo87chbhx"/><stop offset="1" class="bbj4eu2oj"/></radialGradient><radialGradient id="ipxYxUc" cx="0" cy="0" r="1" gradientTransform="rotate(146.787 3.398 4.75)scale(3.43755 1.60167)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="bx7jkhbvj"/><stop offset="1" class="am1-_ogjy"/></radialGradient><radialGradient id="ilCyzXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.76027 2.13307 -1.04932 -1.35786 8.58 7.985)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="bx7jkhbvj"/><stop offset="1" class="am1-_ogjy"/></radialGradient><radialGradient id="ifVI2Fz" cx="0" cy="0" r="1" gradientTransform="rotate(144.615 3.209 5.665)scale(3.29193 1.58011)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="bx7jkhbvj"/><stop offset="1" class="am1-_ogjy"/></radialGradient><radialGradient id="i2qg1ob" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .375 -.21772 2.97553 10.642 5.059)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="z1lq2pb-m"/><stop offset="1" class="duz-bhd4p"/></radialGradient><linearGradient id="i3hWgBA" x1="26.833" x2="2.047" y1="17.514" y2="17.514" gradientUnits="userSpaceOnUse"><stop class="q8sgc5k5k"/><stop offset="1" class="o5v952b3t"/></linearGradient><linearGradient id="iEJSvEb" x1="16.656" x2="16.93" y1="11.254" y2="11.785" gradientUnits="userSpaceOnUse"><stop offset=".18" class="nt1151bhp"/><stop offset=".592" class="x0bh2pb1n"/></linearGradient><linearGradient id="iOB5rue" x1="19.016" x2="14.391" y1="14.77" y2="20.27" gradientUnits="userSpaceOnUse"><stop class="p-1qhibxi"/><stop offset=".751" class="mijncc25w"/></linearGradient><linearGradient id="iKNBjec" x1="26.833" x2="2.047" y1="24.576" y2="24.576" gradientUnits="userSpaceOnUse"><stop class="t8k4gwbbc"/><stop offset="1" class="kpw0uhrkg"/></linearGradient><linearGradient id="io7dQke" x1="17.219" x2="17.188" y1="18.582" y2="16.676" gradientUnits="userSpaceOnUse"><stop class="y1t1nrw8p"/><stop offset="1" class="nf85kqb4p"/></linearGradient><linearGradient id="i5hVk0I" x1="14.945" x2="14.954" y1="14.62" y2="15.57" gradientUnits="userSpaceOnUse"><stop class="uhfoyqb3x"/><stop offset="1" class="eb0haibji"/></linearGradient><linearGradient id="icW56oe" x1="16.734" x2="16.848" y1="11.645" y2="11.723" gradientUnits="userSpaceOnUse"><stop offset=".354" class="dl167p71s"/><stop offset="1" class="xzj0ejbiv"/></linearGradient><linearGradient id="ibjLaiR" x1="17.383" x2="17.301" y1="12.063" y2="12.007" gradientUnits="userSpaceOnUse"><stop class="g5n4zdb7u"/><stop offset="1" class="ghkrj68hc"/></linearGradient><linearGradient id="i9TlDgy" x1="11.422" x2="11.305" y1="17.988" y2="17.805" gradientUnits="userSpaceOnUse"><stop offset=".145" class="dhopq3sqb"/><stop offset="1" class="omxd5rb7l"/></linearGradient><linearGradient id="ibhxFlk" x1="10.984" x2="11.027" y1="17.359" y2="17.43" gradientUnits="userSpaceOnUse"><stop class="cnv_atlwx"/><stop offset="1" class="ujtpm2dyq"/></linearGradient><linearGradient id="iyKTPGe" x1="16.766" x2="15.219" y1="13.113" y2="14.629" gradientUnits="userSpaceOnUse"><stop class="t40s1ccrt"/><stop offset="1" class="vjkwz1bxm"/></linearGradient><linearGradient id="i4EDBAb" x1="13.977" x2="12.43" y1="15.871" y2="17.387" gradientUnits="userSpaceOnUse"><stop class="ol7r9kndd"/><stop offset="1" class="xs-q3bbyy"/></linearGradient><linearGradient id="iBZM1es" x1="14.269" x2="12.127" y1="15.574" y2="17.62" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qi1y9bzby"/><stop offset=".322" class="f-nlkoezi"/><stop offset=".768" class="qi1y9bzby"/></linearGradient><linearGradient id="ilCy3Pe" x1="13.703" x2="13.641" y1="13.367" y2="13.309" gradientUnits="userSpaceOnUse"><stop class="d1-v2bc1s"/><stop offset="1" class="lt8u35u8x"/></linearGradient><linearGradient id="iw863ve" x1="8.172" x2="10.922" y1="4.803" y2="4.541" gradientUnits="userSpaceOnUse"><stop class="q92mq5bjp"/><stop offset="1" class="f2pssab6d"/></linearGradient><filter id="iB3If7c" width="28.306" height="9.762" x="1.847" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.584314 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23147" result="effect2_innerShadow_3987_23147"/></filter><filter id="irpJjPe" width="19.969" height="19.969" x="10.642" y="2.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.647059 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.517647 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23147" result="effect2_innerShadow_3987_23147"/></filter><filter id="iYowCQb" width="2.053" height="2.053" x="16.759" y="11.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23147" stdDeviation=".075"/></filter><filter id="iQzPxwe" width="11.327" height="11.381" x="8.984" y="9.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.619608 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23147"/></filter><filter id="iKI3oYb" width="28.306" height="9.762" x="1.847" y="20.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.580392 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.482353 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23147" result="effect2_innerShadow_3987_23147"/></filter><filter id="iFKLHPb" width="2.217" height="2.217" x="15.887" y="16.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23147" stdDeviation=".1"/></filter><filter id="imzcpcd" width="3.106" height="3.164" x="13.726" y="14.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23147" stdDeviation=".25"/></filter><filter id="iEtqBye" width="2.203" height="2.458" x="14.338" y="14.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.623529 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23147"/><feGaussianBlur result="effect2_foregroundBlur_3987_23147" stdDeviation=".05"/></filter><filter id="ipCknFb" width="2.23" height="2.219" x="14.699" y="12.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.631373 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23147" result="effect2_innerShadow_3987_23147"/></filter><filter id="inXMALI" width="2.872" height="2.875" x="14.46" y="12.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23147" stdDeviation=".075"/></filter><filter id="iLN3Yqd" width="2.23" height="2.219" x="11.909" y="15.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.407843 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23147"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.564706 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23147" result="effect2_innerShadow_3987_23147"/></filter><filter id="iix2CIb" width="2.872" height="2.875" x="11.68" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23147" stdDeviation=".075"/></filter><filter id="i3g2T3A" width="4.333" height="3.319" x="7.677" y="6.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23147"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-swimming" /></template>
<style>
.ah1qi0bpq {
  stop-color: var(--svg-color--e8972a, #E8972A);
}

.ak1dblbqt {
  d: path("M10.642 7.996h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.52h-4.457z");
}

.am1-_ogjy {
  stop-color: var(--svg-color--fab730, #FAB730);
  stop-opacity: 0;
}

.auivi10da {
  d: path("M12.745 15.675a.821.821 0 0 1 1.147 1.175l-.487.476a.822.822 0 0 1-1.148-1.175z");
}

.bbj4eu2oj {
  stop-color: var(--svg-color--dd617e, #DD617E);
  stop-opacity: 0;
}

.bmuo4gvci {
  d: path("M9.475 16.682c-1.367-1.367-1.202-3.537.236-5.17l1.21-1.203c1.556-1.414 3.79-1.595 5.156-.229l.317.318a.2.2 0 0 1 0 .283l-6.319 6.318a.2.2 0 0 1-.282 0z");
}

.brqv9fbno {
  fill: var(--svg-color--c88147, #C88147);
  d: path("m10.762 17.691l-.84-.714l.293-.555l1.137.887z");
}

.bx7jkhbvj {
  stop-color: var(--svg-color--ce893e, #CE893E);
}

.cnv_atlwx {
  stop-color: var(--svg-color--6a6373, #6A6373);
}

.d1-v2bc1s {
  stop-color: var(--svg-color--f64a6a, #F64A6A);
}

.db696fxan {
  cx: 12.201px;
  cy: 18.473px;
  r: 0.822px;
  fill: var(--svg-color--ca8018, #CA8018);
}

.dhopq3sqb {
  stop-color: var(--svg-color--4f3b6a, #4F3B6A);
}

.dkp5uo1co {
  fill: var(--svg-color--ffc92e, #FFC92E);
  d: path("m15.22 16.974l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.633l-.465.457a.4.4 0 0 1-.638-.105");
}

.dl167p71s {
  stop-color: var(--svg-color--654748, #654748);
}

.dr_nfx0ox {
  cx: 12.201px;
  cy: 18.473px;
  r: 1.296px;
  fill: var(--svg-color--d18a2f, #D18A2F);
}

.duz-bhd4p {
  stop-color: var(--svg-color--f9b630, #F9B630);
  stop-opacity: 0;
}

.eb0haibji {
  stop-color: var(--svg-color--413251, #413251);
}

.ez-pwjb7i {
  fill-rule: evenodd;
  d: path("M11.37 6.46a.663.663 0 0 1-.635.69c-1.184.05-2.098.941-2.665 1.871a.663.663 0 0 1-1.131-.69c.65-1.067 1.893-2.427 3.74-2.505a.663.663 0 0 1 .69.634");
}

.f-nlkoezi {
  stop-color: var(--svg-color--5f5669, #5F5669);
  stop-opacity: 0;
}

.f2pssab6d {
  stop-color: var(--svg-color--fab730, #FAB730);
}

.f5o3bbwoj {
  d: path("M3.922 13.098c-.975 0-1.656.49-1.875.734v9.027h27.906v-8.87l-.003-.004c-.623-.545-1.015-.887-2.2-.887c-.906 0-1.67.67-2.05 1.003c-.261.224-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.734-1.914-.734c-.963 0-1.857.666-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.468-1.907.78c-.367.313-1.006.892-2.093.892c-.985 0-1.585-.5-1.915-.775l-.007-.007c-.276-.297-1.072-.89-2.047-.89");
}

.ff8hjccoa {
  fill: var(--svg-color--f9b630, #F9B630);
  fill-rule: evenodd;
  d: path("M11.67 5.686a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 0 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.ft5dv1b6b {
  fill: none;
}

.g-yrcjbos {
  fill: var(--svg-color--f8b227, #F8B227);
  fill-rule: evenodd;
  d: path("M11.348 8.022c-.585 0-1.22.227-1.659.526c-.31.21-.668.602-.82.805a.662.662 0 1 1-1.058-.8c.202-.266.661-.78 1.133-1.1c.63-.429 1.52-.756 2.404-.756a.662.662 0 1 1 0 1.325");
}

.g5n4zdb7u {
  stop-color: var(--svg-color--6a5b65, #6A5B65);
}

.ghkrj68hc {
  stop-color: var(--svg-color--6a5b65, #6A5B65);
  stop-opacity: 0;
}

.gscp5ewot {
  stop-color: var(--svg-color--ffe344, #FFE344);
}

.h0m5e-b1w {
  stop-color: var(--svg-color--ffc030, #FFC030);
}

.h4_2iqqvt {
  fill: var(--svg-color--f9b630, #F9B630);
  fill-rule: evenodd;
  d: path("M11.37 6.46a.663.663 0 0 1-.635.69c-1.184.05-2.098.941-2.665 1.871a.663.663 0 0 1-1.131-.69c.65-1.067 1.893-2.427 3.74-2.505a.663.663 0 0 1 .69.634");
}

.hnpfzrzlu {
  cx: 17.785px;
  cy: 12.884px;
  r: 1.296px;
}

.i-gamdbxk {
  d: path("M17.313 17.52c-1.688 1.15-3.224 3.25-3.782 4.156c3.25 2.162 7.927 2.172 9.86 1.906l6.53-2.266c-.765-1.304-2.036-2.52-2.53-3l-5.407-2.375c-.937 0-2.562.141-4.672 1.579");
}

.itedrub7o {
  d: path("m12.973 20.238l-.614-.57l.235-.937l2.14 1.87c-.937.266-1.493-.13-1.761-.363");
}

.k1_xog4fv {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m16.933 14.35l-.488.476a1.181 1.181 0 0 1-1.65-1.69l.487-.477a1.181 1.181 0 0 1 1.65 1.69m-.238-1.42a.82.82 0 0 0-1.162-.013l-.487.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.161");
}

.ketvxen3s {
  fill: var(--svg-color--695058, #695058);
  d: path("M17.065 11.205a.1.1 0 0 1 .139-.027l.439.298a.1.1 0 0 1 .027.139l-.84 1.239l-.605-.41z");
}

.kjt8t8beu {
  d: path("M3.922 20.16c-.975 0-1.656.49-1.875.735v9.027h27.906V21.05l-.003-.003c-.623-.545-1.015-.888-2.2-.888c-.906 0-1.67.67-2.05 1.003v.001c-.261.224-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.735-1.914-.735c-.963 0-1.857.667-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.469-1.907.781s-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.775l-.007-.006c-.276-.297-1.072-.89-2.047-.89");
}

.kpw0uhrkg {
  stop-color: var(--svg-color--4184e7, #4184E7);
}

.l0y1bewei {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.077 15.563c-.364-.373-1-.41-1.373-.046l-.56.547c-.372.363-.34.99.024 1.362s.977.43 1.35.067l.559-.546c.372-.364.363-1.012 0-1.384Z");
}

.lt8u35u8x {
  stop-color: var(--svg-color--f64a6a, #F64A6A);
  stop-opacity: 0;
}

.mg2_h_bez {
  stop-color: var(--svg-color--f7b71e, #F7B71E);
}

.mijncc25w {
  stop-color: var(--svg-color--eeaa31, #EEAA31);
}

.mo87chbhx {
  stop-color: var(--svg-color--dd617e, #DD617E);
}

.mp1-tzbqs {
  stop-color: var(--svg-color--c68723, #C68723);
}

.mqif30hqe {
  stop-color: var(--svg-color--febc17, #FEBC17);
  stop-opacity: 0;
}

.nf85kqb4p {
  stop-color: var(--svg-color--f5ba3a, #F5BA3A);
  stop-opacity: 0;
}

.nt1151bhp {
  stop-color: var(--svg-color--ffc62a, #FFC62A);
}

.o5grvubsv {
  stop-color: var(--svg-color--c36f27, #C36F27);
}

.o5v952b3t {
  stop-color: var(--svg-color--3ea5fe, #3EA5FE);
}

.oa4_fqjsq {
  fill: var(--svg-color--5f5876, #5F5876);
  d: path("M10.925 18.278a.1.1 0 0 1-.138-.03l-.29-.444a.1.1 0 0 1 .03-.138l1.253-.818l.4.612z");
}

.oc9c5r57k {
  fill: var(--svg-color--ffe045, #FFE045);
  d: path("M10.642 7.996h4.828a4 4 0 0 1 3.602 2.26l6.164 12.459l4.125-.594l-6.687-13.604a8 8 0 0 0-7.204-4.52h-4.43z");
}

.ol7r9kndd {
  stop-color: var(--svg-color--3387e0, #3387E0);
}

.omkku6bhl {
  d: path("m8.984 15.775l6.11-6.101l4.26 4.74a3.15 3.15 0 0 1-.079 4.296l-1.195 1.235a3.15 3.15 0 0 1-4.39.134z");
}

.omxd5rb7l {
  stop-color: var(--svg-color--605976, #605976);
  stop-opacity: 0;
}

.p_cqefbjp {
  fill-rule: evenodd;
  d: path("M11.67 5.686a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 0 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.p-1qhibxi {
  stop-color: var(--svg-color--ffe245, #FFE245);
}

.p3mcnub9l {
  stop-color: var(--svg-color--ffc930, #FFC930);
}

.pqg0n5byu {
  stop-color: var(--svg-color--f0af33, #F0AF33);
  stop-opacity: 0;
}

.q5tuqccgg {
  fill: var(--svg-color--f9b630, #F9B630);
  fill-rule: evenodd;
  d: path("M11.266 4.904a.663.663 0 0 1-.608.713c-1.395.112-2.487 1.077-3.036 1.864a.663.663 0 0 1-1.087-.758c.678-.972 2.085-2.272 4.018-2.426a.663.663 0 0 1 .713.607");
}

.q8sgc5k5k {
  stop-color: var(--svg-color--40aafe, #40AAFE);
}

.q92mq5bjp {
  stop-color: var(--svg-color--e7b631, #E7B631);
}

.qi1y9bzby {
  stop-color: var(--svg-color--5f5669, #5F5669);
}

.qjk4gabpx {
  stop-color: var(--svg-color--d58c44, #D58C44);
}

.r-yyy1bsz {
  stop-color: var(--svg-color--cc8810, #CC8810);
}

.rkvqsdrut {
  d: path("m19.598 13.684l-.614-.668l-.785.73l1.664 1.91c.375-.844.047-1.633-.265-1.972");
}

.rsa-8gb7q {
  stroke: var(--svg-color--5c4c6d, #5C4C6D);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.857 12.768c-.364-.373-1-.409-1.373-.045l-.559.546c-.373.364-.34.99.024 1.362c.363.373.976.431 1.348.067l.56-.546c.372-.363.364-1.012 0-1.384Z");
}

.s1tm77bcz {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m14.144 17.108l-.488.476a1.182 1.182 0 0 1-1.65-1.691l.487-.476a1.181 1.181 0 1 1 1.65 1.69m-.238-1.42a.82.82 0 0 0-1.162-.013l-.487.476a.821.821 0 1 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.162");
}

.s1zh3d05d {
  stop-color: var(--svg-color--f0b61b, #F0B61B);
}

.s6eqh9b-p {
  stop-color: var(--svg-color--fbc72b, #FBC72B);
  stop-opacity: 0;
}

.sbtdeuvbe {
  stop-color: var(--svg-color--ffa319, #FFA319);
}

.scdz6cc-w {
  fill-rule: evenodd;
  d: path("M11.266 4.904a.663.663 0 0 1-.608.713c-1.395.112-2.487 1.077-3.036 1.864a.663.663 0 0 1-1.087-.758c.678-.972 2.085-2.272 4.018-2.426a.663.663 0 0 1 .713.607");
}

.sfpwjtbye {
  fill: var(--svg-color--e69d28, #E69D28);
  d: path("m15.047 17.24l-.821-1.635l.304-.296l1.588.896a.42.42 0 0 1 .088.666l-.488.481a.42.42 0 0 1-.67-.111");
}

.shho5dbnr {
  cx: 16.996px;
  cy: 17.652px;
  r: 0.809px;
  fill: var(--svg-color--89024e, #89024E);
}

.sr-z703qg {
  stop-color: var(--svg-color--c73a7a, #C73A7A);
  stop-opacity: 0;
}

.t1bgw6m6y {
  d: path("m17.133 11.36l-.758-.743l-.844.301c.401.427 1.206 1.277 1.215 1.258z");
}

.t40s1ccrt {
  stop-color: var(--svg-color--489be1, #489BE1);
}

.t8k4gwbbc {
  stop-color: var(--svg-color--3f90f0, #3F90F0);
}

.taiuw254n {
  stop-color: var(--svg-color--fb5684, #FB5684);
}

.ue4dw-rff {
  stop-color: var(--svg-color--c73a7a, #C73A7A);
}

.uhfoyqb3x {
  stop-color: var(--svg-color--52475d, #52475D);
}

.ujtpm2dyq {
  stop-color: var(--svg-color--6a6373, #6A6373);
  stop-opacity: 0;
}

.utk49icaf {
  fill-rule: evenodd;
  d: path("M9.936 5.41c-.557.042-1.037.1-1.262.157a.663.663 0 1 1-.324-1.285c.836-.21 1.78-.262 2.642-.262c.366 0 1.05.296 1.05.662a.66.66 0 0 1-.663.663c-.345 0-.9.023-1.443.064");
}

.v_13ezbio {
  d: path("M10.925 18.278a.1.1 0 0 1-.138-.03l-.29-.444a.1.1 0 0 1 .03-.138l1.253-.818l.4.612z");
}

.v9f4hvapl {
  cx: 16.996px;
  cy: 17.652px;
  r: 0.809px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.vjkwz1bxm {
  stop-color: var(--svg-color--4799ea, #4799EA);
}

.wduf44nbu {
  d: path("M15.534 12.917a.821.821 0 0 1 1.147 1.175l-.487.476a.821.821 0 0 1-1.148-1.175z");
}

.wjyjhxryd {
  stop-color: var(--svg-color--453b50, #453B50);
}

.wk7-7rb8w {
  stop-color: var(--svg-color--e12e6e, #E12E6E);
}

.x0bh2pb1n {
  stop-color: var(--svg-color--8e5d03, #8E5D03);
}

.xs-q3bbyy {
  stop-color: var(--svg-color--2f81cb, #2F81CB);
}

.xzj0ejbiv {
  stop-color: var(--svg-color--654748, #654748);
  stop-opacity: 0;
}

.y01zyrbyt {
  stop-color: var(--svg-color--453b50, #453B50);
  stop-opacity: 0;
}

.y1t1nrw8p {
  stop-color: var(--svg-color--f5ba3a, #F5BA3A);
}

.ypt6accsz {
  d: path("M17.065 11.205a.1.1 0 0 1 .139-.027l.439.298a.1.1 0 0 1 .027.139l-.84 1.239l-.605-.41z");
}

.z1lq2pb-m {
  stop-color: var(--svg-color--f9b630, #F9B630);
}

.zfoyj9b_m {
  d: path("M14.576 14.447h.758v1.123h-.758z");
}

.zowuonbmg {
  cx: 17.785px;
  cy: 12.884px;
  r: 0.877px;
  fill: var(--svg-color--ffbc24, #FFBC24);
}

</style>
