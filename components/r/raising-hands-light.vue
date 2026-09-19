<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXTCEXc)"><path fill="url(#ixCepFc)" class="wqnxuubvf"/></g><path fill="url(#iEU5Hlc)" class="wqnxuubvf"/><path fill="url(#i5cUsNc)" class="wqnxuubvf"/><rect fill="url(#iJBFRLc)" transform="rotate(-7.151 .718 15.861)" class="v67ok2_yl"/><rect fill="url(#inArY4d)" transform="rotate(-7.151 .718 15.861)" class="v67ok2_yl"/><path fill="url(#i0Txqzc)" class="ezj6kvbvw"/><path fill="url(#iHfN2Lb)" class="ezj6kvbvw"/><path fill="url(#i6h9UEd)" class="ezj6kvbvw"/><path fill="url(#ibO0vPe)" class="ezj6kvbvw"/><path fill="url(#iey8sXb)" class="u596-n57q"/><path fill="url(#iX81zsd)" class="u596-n57q"/><path fill="url(#ixf4b0c)" class="u596-n57q"/><path fill="url(#igXIhNe)" class="u596-n57q"/><path fill="url(#iMUoLEc)" class="sz4p65b8v"/><path fill="url(#i2zunvd)" class="sz4p65b8v"/><path fill="url(#i0kzUxh)" class="sz4p65b8v"/><path fill="url(#ioZAIKc)" class="r7_i2-bhj"/><path fill="url(#isk2uNe)" class="r7_i2-bhj"/><g filter="url(#iGUfBSd)"><path stroke="url(#ixFogIb)" class="m-_hu7fyo"/></g><g filter="url(#itfl38N)"><path stroke="url(#iyvsPVb)" class="w-467sbjv"/></g><g filter="url(#isv81jc)"><path stroke="url(#iwXDbee)" class="b-eosq6uk"/></g><g filter="url(#ijWVHMb)"><path stroke="url(#iqZBwUv)" class="d7jtivbdy"/></g><g filter="url(#iQfRxye)"><path stroke="url(#iYgynqe)" class="gkof-gbbn"/></g><g filter="url(#iDPhiLd)"><path fill="url(#iS17jve)" class="ir5_dt_ir"/></g><path fill="url(#io37uNd)" class="ir5_dt_ir"/><path fill="url(#iO6ePOd)" class="ir5_dt_ir"/><rect fill="url(#iBxKsJc)" transform="scale(-1 1)rotate(-7.151 111.365 256.782)" class="euhd2fska"/><rect fill="url(#i3h2fie)" transform="scale(-1 1)rotate(-7.151 111.365 256.782)" class="euhd2fska"/><path fill="url(#imNLfuc)" class="zjz13eb3u"/><path fill="url(#i9SWlEc)" class="zjz13eb3u"/><path fill="url(#ixZGksU)" class="zjz13eb3u"/><path fill="url(#ix35mre)" class="zjz13eb3u"/><path fill="url(#il46mfb)" class="rpc9hc5fu"/><path fill="url(#iKgVIJc)" class="rpc9hc5fu"/><path fill="url(#i2j0dze)" class="rpc9hc5fu"/><path fill="url(#i9gTOHc)" class="rpc9hc5fu"/><path fill="url(#iKPecxb)" class="eyz39abjk"/><path fill="url(#ipOdPve)" class="eyz39abjk"/><path fill="url(#ipHBa8b)" class="eyz39abjk"/><path fill="url(#igHsqBc)" class="rt56_gbci"/><path fill="url(#i9whjsb)" class="rt56_gbci"/><g filter="url(#i36awub)"><path stroke="url(#i7aAF8c)" class="eye_zcvwl"/></g><g filter="url(#iLLr7Ge)"><path stroke="url(#i1URRsd)" class="oiwg6lben"/></g><g filter="url(#i4dAF0d)"><path stroke="url(#ijZbtMe)" class="v35u4bbmh"/></g><g filter="url(#ivFjIic)"><path stroke="url(#inpH4xe)" class="mc-bdgbvx"/></g><g filter="url(#ilP9gQe)"><path stroke="url(#i3QD3be)" class="v4a228bcc"/></g><g filter="url(#iQIqzrJ)"><path class="lmnczzrig"/></g><g filter="url(#iQ22RAd)"><path class="wsb98zb_z"/></g><g filter="url(#ictIWEe)"><path class="zec9efufq"/></g><defs><radialGradient id="ixCepFc" cx="0" cy="0" r="1" gradientTransform="rotate(113.351 -.398 12.354)scale(13.4891 10.406)" gradientUnits="userSpaceOnUse"><stop class="rnzjqbc8i"/><stop offset="1" class="i8zj9jgbm"/></radialGradient><radialGradient id="iEU5Hlc" cx="0" cy="0" r="1" gradientTransform="rotate(59.708 -14.048 11.381)scale(14.6213 14.9226)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="lls8at9hv"/><stop offset="1" class="l3i9autcx"/></radialGradient><radialGradient id="iJBFRLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9179 2.73097 -4.18501 -1.40662 2.84 15.414)" gradientUnits="userSpaceOnUse"><stop class="l0zmnsnlm"/><stop offset="1" class="o0ns2fg4w"/></radialGradient><radialGradient id="inArY4d" cx="0" cy="0" r="1" gradientTransform="rotate(-143.869 3.228 7.978)scale(1.29526 1.06025)" gradientUnits="userSpaceOnUse"><stop class="bnyaugbrs"/><stop offset="1" class="cydcr2oxb"/></radialGradient><radialGradient id="i0Txqzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.37556 -.09326 .3675 5.42054 3.757 18.375)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="d4homcbud"/><stop offset="1" class="ocru3ofdh"/></radialGradient><radialGradient id="iHfN2Lb" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 -2.404 8.502)scale(2.14913 4.00283)" gradientUnits="userSpaceOnUse"><stop class="eco_im0as"/><stop offset="1" class="jj-qmgboq"/></radialGradient><radialGradient id="i6h9UEd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.905 7.051 7.217)scale(5.17754 6.62191)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="vx1lmrr7g"/><stop offset="1" class="hymklqb8k"/></radialGradient><radialGradient id="ibO0vPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03477 -.76368 .62715 -.84978 3.734 13.647)" gradientUnits="userSpaceOnUse"><stop class="g73iv-bvy"/><stop offset="1" class="alsobs70x"/></radialGradient><radialGradient id="iX81zsd" cx="0" cy="0" r="1" gradientTransform="matrix(1.00593 .05159 -.23046 4.49403 6.519 16.878)" gradientUnits="userSpaceOnUse"><stop class="pa4fxpwhz"/><stop offset="1" class="e7n-49gph"/></radialGradient><radialGradient id="ixf4b0c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99108 2.73847 -4.79078 -3.48326 9.618 10.73)" gradientUnits="userSpaceOnUse"><stop class="fabxae9xv"/><stop offset="1" class="ydcuu3bmb"/></radialGradient><radialGradient id="igXIhNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3056 -.72165 .61055 -1.1046 6.721 11.773)" gradientUnits="userSpaceOnUse"><stop class="aa7vi3cec"/><stop offset="1" class="fldlpiboq"/><stop offset="1" class="d25330b8w"/></radialGradient><radialGradient id="iMUoLEc" cx="0" cy="0" r="1" gradientTransform="rotate(-83.98 15.995 3.979)scale(7.68187 4.39481)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="xew5-obiw"/><stop offset="1" class="ksr7cab6d"/></radialGradient><radialGradient id="i2zunvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.34996 .25525 -.89731 4.74563 9.13 15.653)" gradientUnits="userSpaceOnUse"><stop class="w7vlgvbtw"/><stop offset="1" class="ri5m3ob_y"/></radialGradient><radialGradient id="ioZAIKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.686 2.61634 -3.75523 -.9846 14.186 16.547)" gradientUnits="userSpaceOnUse"><stop class="mp-zponox"/><stop offset="1" class="wk90ikpwz"/></radialGradient><radialGradient id="isk2uNe" cx="0" cy="0" r="1" gradientTransform="rotate(10.784 -89.392 67.257)scale(2.00415 3.316)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="f66el3wsf"/><stop offset="1" class="hn86bdcly"/></radialGradient><radialGradient id="iS17jve" cx="0" cy="0" r="1" gradientTransform="matrix(5.34656 12.38427 -9.5537 4.12454 21.032 17.616)" gradientUnits="userSpaceOnUse"><stop class="rnzjqbc8i"/><stop offset="1" class="i8zj9jgbm"/></radialGradient><radialGradient id="io37uNd" cx="0" cy="0" r="1" gradientTransform="rotate(120.292 9.377 17.194)scale(14.6213 14.9226)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="lls8at9hv"/><stop offset="1" class="l3i9autcx"/></radialGradient><radialGradient id="iBxKsJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9179 2.73097 -4.18501 -1.40662 2.122 -.447)" gradientUnits="userSpaceOnUse"><stop class="l0zmnsnlm"/><stop offset="1" class="o0ns2fg4w"/></radialGradient><radialGradient id="i3h2fie" cx="0" cy="0" r="1" gradientTransform="rotate(-143.869 .282 .164)scale(1.29526 1.06025)" gradientUnits="userSpaceOnUse"><stop class="bnyaugbrs"/><stop offset="1" class="cydcr2oxb"/></radialGradient><radialGradient id="imNLfuc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.121 14.342 8.713)scale(1.37872 5.43298)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="d4homcbud"/><stop offset="1" class="ocru3ofdh"/></radialGradient><radialGradient id="i9SWlEc" cx="0" cy="0" r="1" gradientTransform="rotate(74.908 4.81 23.905)scale(2.14913 4.00283)" gradientUnits="userSpaceOnUse"><stop class="eco_im0as"/><stop offset="1" class="jj-qmgboq"/></radialGradient><radialGradient id="ixZGksU" cx="0" cy="0" r="1" gradientTransform="matrix(3.59046 -3.73035 4.771 4.59209 25.077 17.303)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="vx1lmrr7g"/><stop offset="1" class="hymklqb8k"/></radialGradient><radialGradient id="ix35mre" cx="0" cy="0" r="1" gradientTransform="matrix(1.03477 -.76368 .62716 .84978 28.084 13.647)" gradientUnits="userSpaceOnUse"><stop class="g73iv-bvy"/><stop offset="1" class="alsobs70x"/></radialGradient><radialGradient id="iKgVIJc" cx="0" cy="0" r="1" gradientTransform="rotate(177.064 12.434 8.763)scale(1.00725 4.49994)" gradientUnits="userSpaceOnUse"><stop class="pa4fxpwhz"/><stop offset="1" class="e7n-49gph"/></radialGradient><radialGradient id="i2j0dze" cx="0" cy="0" r="1" gradientTransform="matrix(1.99107 2.73848 -4.79078 3.48325 22.2 10.73)" gradientUnits="userSpaceOnUse"><stop class="fabxae9xv"/><stop offset="1" class="ydcuu3bmb"/></radialGradient><radialGradient id="i9gTOHc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3056 -.72165 .61055 1.1046 25.097 11.773)" gradientUnits="userSpaceOnUse"><stop class="aa7vi3cec"/><stop offset="1" class="fldlpiboq"/><stop offset="1" class="d25330b8w"/></radialGradient><radialGradient id="iKPecxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.80564 -7.6395 4.37057 -.4609 21.457 19.468)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="xew5-obiw"/><stop offset="1" class="ksr7cab6d"/></radialGradient><radialGradient id="ipOdPve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34996 .25525 -.8973 -4.74564 22.689 15.653)" gradientUnits="userSpaceOnUse"><stop class="w7vlgvbtw"/><stop offset="1" class="ri5m3ob_y"/></radialGradient><radialGradient id="igHsqBc" cx="0" cy="0" r="1" gradientTransform="matrix(.686 2.61634 -3.75523 .9846 17.632 16.547)" gradientUnits="userSpaceOnUse"><stop class="mp-zponox"/><stop offset="1" class="wk90ikpwz"/></radialGradient><radialGradient id="i9whjsb" cx="0" cy="0" r="1" gradientTransform="rotate(169.216 9.56 9.94)scale(2.00415 3.316)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="f66el3wsf"/><stop offset="1" class="hn86bdcly"/></radialGradient><linearGradient id="i5cUsNc" x1="-.705" x2="3.79" y1="23.373" y2="22.97" gradientUnits="userSpaceOnUse"><stop class="b8-ohp3ft"/><stop offset="1" class="t0wejbbpl"/></linearGradient><linearGradient id="iey8sXb" x1="11.422" x2="5.85" y1="14.318" y2="14.124" gradientUnits="userSpaceOnUse"><stop offset=".813" class="mz-7uabeh"/><stop offset="1" class="f2ynl0btr"/><stop offset="1" class="mzl_h2r6k"/></linearGradient><linearGradient id="i0kzUxh" x1="8.826" x2="10.389" y1="20.184" y2="18.78" gradientUnits="userSpaceOnUse"><stop class="kupioobkb"/><stop offset="1" class="ligdeu_qm"/></linearGradient><linearGradient id="ixFogIb" x1="4.396" x2="4.881" y1="14.102" y2="18.695" gradientUnits="userSpaceOnUse"><stop class="j2u72qbdb"/><stop offset="1" class="r2rd1hnwy"/></linearGradient><linearGradient id="iyvsPVb" x1="8.217" x2="7.053" y1="7.342" y2="18.352" gradientUnits="userSpaceOnUse"><stop class="z2r1jqbnc"/><stop offset="1" class="f1-i52p7u"/></linearGradient><linearGradient id="iwXDbee" x1="10.274" x2="10.221" y1="12.788" y2="19.939" gradientUnits="userSpaceOnUse"><stop class="m9v_hz1nq"/><stop offset="1" class="maon7_brh"/></linearGradient><linearGradient id="iqZBwUv" x1="12.935" x2="12.93" y1="18.102" y2="20.827" gradientUnits="userSpaceOnUse"><stop class="amznj2bvx"/><stop offset="1" class="w7derebob"/></linearGradient><linearGradient id="iYgynqe" x1="1.64" x2="5.413" y1="18.078" y2="30.518" gradientUnits="userSpaceOnUse"><stop class="ovtz5gblp"/><stop offset="1" class="so0_nlb6m"/></linearGradient><linearGradient id="iO6ePOd" x1="32.523" x2="28.028" y1="23.373" y2="22.97" gradientUnits="userSpaceOnUse"><stop class="b8-ohp3ft"/><stop offset="1" class="t0wejbbpl"/></linearGradient><linearGradient id="il46mfb" x1="20.396" x2="25.968" y1="14.318" y2="14.124" gradientUnits="userSpaceOnUse"><stop offset=".813" class="mz-7uabeh"/><stop offset="1" class="f2ynl0btr"/><stop offset="1" class="mzl_h2r6k"/></linearGradient><linearGradient id="ipHBa8b" x1="22.992" x2="21.429" y1="20.184" y2="18.78" gradientUnits="userSpaceOnUse"><stop class="kupioobkb"/><stop offset="1" class="ligdeu_qm"/></linearGradient><linearGradient id="i7aAF8c" x1="27.422" x2="26.937" y1="14.102" y2="18.695" gradientUnits="userSpaceOnUse"><stop class="j2u72qbdb"/><stop offset="1" class="r2rd1hnwy"/></linearGradient><linearGradient id="i1URRsd" x1="23.601" x2="24.765" y1="7.342" y2="18.352" gradientUnits="userSpaceOnUse"><stop class="z2r1jqbnc"/><stop offset="1" class="f1-i52p7u"/></linearGradient><linearGradient id="ijZbtMe" x1="21.544" x2="21.597" y1="12.788" y2="19.939" gradientUnits="userSpaceOnUse"><stop class="m9v_hz1nq"/><stop offset="1" class="maon7_brh"/></linearGradient><linearGradient id="inpH4xe" x1="18.883" x2="18.888" y1="18.102" y2="20.827" gradientUnits="userSpaceOnUse"><stop class="amznj2bvx"/><stop offset="1" class="w7derebob"/></linearGradient><linearGradient id="i3QD3be" x1="30.178" x2="26.405" y1="18.078" y2="30.518" gradientUnits="userSpaceOnUse"><stop class="ovtz5gblp"/><stop offset="1" class="so0_nlb6m"/></linearGradient><filter id="iXTCEXc" width="15.482" height="18.923" x=".906" y="11.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.584314 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.854902 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6224" result="effect2_innerShadow_20020_6224"/></filter><filter id="iGUfBSd" width="2.469" height="6.969" x="3.521" y="13.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation=".375"/></filter><filter id="itfl38N" width="2.766" height="8.109" x="5.928" y="11.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation=".375"/></filter><filter id="isv81jc" width="3.223" height="8.647" x="8.381" y="12.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation=".375"/></filter><filter id="ijWVHMb" width="3.625" height="4.688" x="10.725" y="17.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation=".375"/></filter><filter id="iQfRxye" width="10.469" height="15.398" x=".179" y="15.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation="1"/></filter><filter id="iDPhiLd" width="15.482" height="18.923" x="16.429" y="11.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.584314 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.854902 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6224" result="effect2_innerShadow_20020_6224"/></filter><filter id="i36awub" width="2.469" height="6.969" x="25.828" y="13.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation=".375"/></filter><filter id="iLLr7Ge" width="2.766" height="8.109" x="23.125" y="11.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation=".375"/></filter><filter id="i4dAF0d" width="3.223" height="8.647" x="20.214" y="12.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation=".375"/></filter><filter id="ivFjIic" width="3.625" height="4.688" x="17.468" y="17.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation=".375"/></filter><filter id="ilP9gQe" width="10.469" height="15.398" x="21.171" y="15.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6224" stdDeviation="1"/></filter><filter id="iQIqzrJ" width="3.069" height="3.027" x="19.134" y="6.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.568627 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.341176 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6224" result="effect2_innerShadow_20020_6224"/></filter><filter id="iQ22RAd" width="2.892" height="2.913" x="14.527" y="6.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.568627 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.341176 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6224" result="effect2_innerShadow_20020_6224"/></filter><filter id="ictIWEe" width="3.208" height="2.913" x="9.723" y="7.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.113725 0 0 0 0 0.568627 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6224"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.341176 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6224" result="effect2_innerShadow_20020_6224"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raising-hands-light" /></template>
<style>
.aa7vi3cec {
  stop-color: var(--svg-color--ffdfc2, #FFDFC2);
}

.alsobs70x {
  stop-color: var(--svg-color--ffe2c5, #FFE2C5);
  stop-opacity: 0;
}

.amznj2bvx {
  stop-color: var(--svg-color--e3b1a0, #E3B1A0);
}

.b-eosq6uk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m10.479 13.36l-.973 6.398");
}

.b8-ohp3ft {
  stop-color: var(--svg-color--ffcbb5, #FFCBB5);
}

.bnyaugbrs {
  stop-color: var(--svg-color--ffe0c2, #FFE0C2);
}

.cydcr2oxb {
  stop-color: var(--svg-color--ffe0c2, #FFE0C2);
  stop-opacity: 0;
}

.d25330b8w {
  stop-color: var(--svg-color--ffdfc2, #FFDFC2);
  stop-opacity: 0;
}

.d4homcbud {
  stop-color: var(--svg-color--d29078, #D29078);
}

.d7jtivbdy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m13.225 18.32l-1.375 2.438");
}

.e7n-49gph {
  stop-color: var(--svg-color--c9866d, #C9866D);
  stop-opacity: 0;
}

.eco_im0as {
  stop-color: var(--svg-color--daa589, #DAA589);
}

.euhd2fska {
  width: 3.231px;
  height: 7.176px;
  rx: 1.616px;
}

.eye_zcvwl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m27.297 14.461l-.47 4.969");
}

.eyz39abjk {
  d: path("M23.217 19.317a1.6 1.6 0 0 1-.571-1.1l-.44-5.248a2 2 0 0 1-.006-.184a1.58 1.58 0 0 0-2.729 1.251l.6 5.333a1.58 1.58 0 0 0 3.146-.052");
}

.ezj6kvbvw {
  d: path("M4.869 13.184a1.57 1.57 0 0 0-1.544 1.591l.016 1.095c.417.246.72.675.784 1.192l.407 3.24a1.568 1.568 0 0 0 1.989-1.534l-.061-4.04a1.57 1.57 0 0 0-1.591-1.544");
}

.f1-i52p7u {
  stop-color: var(--svg-color--ffd4bb, #FFD4BB);
  stop-opacity: 0;
}

.f2ynl0btr {
  stop-color: var(--svg-color--efb795, #EFB795);
}

.f66el3wsf {
  stop-color: var(--svg-color--be8063, #BE8063);
}

.fabxae9xv {
  stop-color: var(--svg-color--c79a82, #C79A82);
}

.fldlpiboq {
  stop-color: var(--svg-color--ffcca6, #FFCCA6);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g73iv-bvy {
  stop-color: var(--svg-color--ffe2c5, #FFE2C5);
}

.gkof-gbbn {
  stroke-linecap: round;
  d: path("m2.679 18.078l.812 5.875c.146 1.636 1.282 4.825 4.657 4.5");
}

.hn86bdcly {
  stop-color: var(--svg-color--be8063, #BE8063);
  stop-opacity: 0;
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i8zj9jgbm {
  stop-color: var(--svg-color--f0b8aa, #F0B8AA);
}

.ir5_dt_ir {
  d: path("M23.672 11.233a1.607 1.607 0 0 1 1.736 1.467l.114 1.353a1.568 1.568 0 0 1 2.971.722l-.016 1.095a1.616 1.616 0 0 1 2.422 1.594l-.491 3.914a2 2 0 0 1-.024.143l-.252 2.014c-.055.657-.31 2.186-.898 3.303a5.085 5.085 0 0 1-9.732-1.15a10 10 0 0 1-.11-.501a5.6 5.6 0 0 0-.26-.844l-2.505-4.706a1.68 1.68 0 0 1 .649-2.25l.044-.026a1.68 1.68 0 0 1 2.297.624l.371.648l-.517-4.597a1.58 1.58 0 0 1 2.73-1.251a1.607 1.607 0 0 1 1.471-1.552");
}

.j2u72qbdb {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
}

.jj-qmgboq {
  stop-color: var(--svg-color--daa589, #DAA589);
  stop-opacity: 0;
}

.ksr7cab6d {
  stop-color: var(--svg-color--bb947e, #BB947E);
}

.kupioobkb {
  stop-color: var(--svg-color--daa699, #DAA699);
}

.l0zmnsnlm {
  stop-color: var(--svg-color--e2aa8c, #E2AA8C);
}

.l3i9autcx {
  stop-color: var(--svg-color--ad7289, #AD7289);
}

.ligdeu_qm {
  stop-color: var(--svg-color--daa699, #DAA699);
  stop-opacity: 0;
}

.lls8at9hv {
  stop-color: var(--svg-color--ad7289, #AD7289);
  stop-opacity: 0;
}

.lmnczzrig {
  fill: var(--svg-color--1a78c3, #1A78C3);
  d: path("m19.877 9.82l1.867-1.024a.4.4 0 0 0 .057-.664l-1.325-1.05a.4.4 0 0 0-.636.212l-.543 2.075a.4.4 0 0 0 .58.452");
}

.m-_hu7fyo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m4.521 14.461l.47 4.969");
}

.m9v_hz1nq {
  stop-color: var(--svg-color--d8aa9c, #D8AA9C);
}

.maon7_brh {
  stop-color: var(--svg-color--d8aa9c, #D8AA9C);
  stop-opacity: 0;
}

.mc-bdgbvx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.594 18.32l1.375 2.438");
}

.mp-zponox {
  stop-color: var(--svg-color--c19680, #C19680);
}

.mz-7uabeh {
  stop-color: var(--svg-color--ffddbf, #FFDDBF);
  stop-opacity: 0;
}

.mzl_h2r6k {
  stop-color: var(--svg-color--ffddbf, #FFDDBF);
}

.o0ns2fg4w {
  stop-color: var(--svg-color--e2aa8c, #E2AA8C);
  stop-opacity: 0;
}

.ocru3ofdh {
  stop-color: var(--svg-color--d29078, #D29078);
  stop-opacity: 0;
}

.oiwg6lben {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m24.25 12.492l.515 5.86");
}

.ovtz5gblp {
  stop-color: var(--svg-color--f5bcab, #F5BCAB);
}

.pa4fxpwhz {
  stop-color: var(--svg-color--c9866d, #C9866D);
}

.r2rd1hnwy {
  stop-color: var(--svg-color--ffd3ba, #FFD3BA);
  stop-opacity: 0;
}

.r7_i2-bhj {
  d: path("m14.068 21.747l1.123-2.11a1.683 1.683 0 0 0-.649-2.25l-.044-.026a1.68 1.68 0 0 0-2.297.624l-.4.697l-.537 3.17z");
}

.ri5m3ob_y {
  stop-color: var(--svg-color--bf7f6a, #BF7F6A);
  stop-opacity: 0;
}

.rnzjqbc8i {
  stop-color: var(--svg-color--d2a092, #D2A092);
}

.rpc9hc5fu {
  d: path("M23.672 11.233a1.607 1.607 0 0 1 1.736 1.467l.114 1.353c-.101.204-.16.432-.164.675l-.06 4.04q-.004.248.065.473a1.607 1.607 0 0 1-2.717-1.023l-.44-5.25a1.607 1.607 0 0 1 1.466-1.735");
}

.rt56_gbci {
  d: path("m17.75 21.747l-1.123-2.11a1.683 1.683 0 0 1 .649-2.25l.044-.026a1.68 1.68 0 0 1 2.297.624l.4.697l.538 3.17z");
}

.so0_nlb6m {
  stop-color: var(--svg-color--f5bcab, #F5BCAB);
  stop-opacity: 0;
}

.sz4p65b8v {
  d: path("M8.601 19.317c.318-.266.534-.654.571-1.1l.44-5.248q.009-.093.006-.184a1.58 1.58 0 0 1 2.729 1.251l-.6 5.333a1.58 1.58 0 0 1-3.146-.052");
}

.t0wejbbpl {
  stop-color: var(--svg-color--ffcbb5, #FFCBB5);
  stop-opacity: 0;
}

.u596-n57q {
  d: path("M8.146 11.233A1.607 1.607 0 0 0 6.41 12.7l-.114 1.353c.101.204.16.432.164.675l.06 4.04q.003.248-.064.473a1.607 1.607 0 0 0 2.717-1.023l.44-5.25a1.607 1.607 0 0 0-1.467-1.735");
}

.v35u4bbmh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m21.34 13.36l.972 6.398");
}

.v4a228bcc {
  stroke-linecap: round;
  d: path("m29.14 18.078l-.813 5.875c-.146 1.636-1.282 4.825-4.657 4.5");
}

.v67ok2_yl {
  width: 3.231px;
  height: 7.176px;
  x: 0.718px;
  y: 15.861px;
  rx: 1.616px;
}

.vx1lmrr7g {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
  stop-opacity: 0;
}

.w-467sbjv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m7.568 12.492l-.515 5.86");
}

.w7derebob {
  stop-color: var(--svg-color--e3b1a0, #E3B1A0);
  stop-opacity: 0;
}

.w7vlgvbtw {
  stop-color: var(--svg-color--bf7f6a, #BF7F6A);
}

.wk90ikpwz {
  stop-color: var(--svg-color--c19680, #C19680);
  stop-opacity: 0;
}

.wqnxuubvf {
  d: path("M8.146 11.233A1.607 1.607 0 0 0 6.41 12.7l-.114 1.353a1.568 1.568 0 0 0-2.971.722l.016 1.095A1.616 1.616 0 0 0 .92 17.464l.491 3.914q.01.073.025.143l.25 2.014c.056.657.312 2.186.9 3.303a5.084 5.084 0 0 0 9.731-1.15c.036-.148.076-.322.11-.501c.052-.265.165-.595.26-.844l2.505-4.706a1.68 1.68 0 0 0-.649-2.25l-.044-.026a1.68 1.68 0 0 0-2.297.624l-.371.648l.517-4.597a1.58 1.58 0 0 0-2.73-1.251a1.607 1.607 0 0 0-1.471-1.552");
}

.wsb98zb_z {
  fill: var(--svg-color--1a78c3, #1A78C3);
  d: path("m15.536 8.824l-.827-1.964a.4.4 0 0 1 .368-.555h1.69a.4.4 0 0 1 .367.56L16.27 8.83a.4.4 0 0 1-.734-.005");
}

.xew5-obiw {
  stop-color: var(--svg-color--bb947e, #BB947E);
  stop-opacity: 0;
}

.ydcuu3bmb {
  stop-color: var(--svg-color--c79a82, #C79A82);
  stop-opacity: 0;
}

.z2r1jqbnc {
  stop-color: var(--svg-color--ffd4bb, #FFD4BB);
}

.zec9efufq {
  fill: var(--svg-color--1a78c3, #1A78C3);
  d: path("m12.146 9.79l-2.007-.715a.4.4 0 0 1-.16-.647l1.14-1.247a.4.4 0 0 1 .662.108l.866 1.963a.4.4 0 0 1-.5.538");
}

.zjz13eb3u {
  d: path("M26.95 13.184a1.57 1.57 0 0 1 1.543 1.591l-.016 1.095a1.61 1.61 0 0 0-.784 1.192l-.407 3.24a1.568 1.568 0 0 1-1.988-1.534l.06-4.04a1.57 1.57 0 0 1 1.591-1.544");
}

</style>
