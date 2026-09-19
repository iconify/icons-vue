<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iEScWPc)" transform="rotate(-180 25.404 27.272)" class="uib5ptygi"/><g filter="url(#i94b43d)"><rect transform="scale(-1 1)rotate(44.184 -43.275 -19.634)" class="s_txeqb5u"/><rect fill="url(#iCAMPGd)" transform="scale(-1 1)rotate(44.184 -43.275 -19.634)" class="j6w3anb3u"/></g><g filter="url(#iILn6ec)"><rect transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="qzk34pbjf"/><rect fill="url(#ivhuhgb)" transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="b_028jvwm"/></g><g filter="url(#i4P9IOb)"><rect transform="scale(-1 1)rotate(44.184 -44.184 -18.961)" class="r96i785dr"/><rect fill="url(#iX8Qwud)" transform="scale(-1 1)rotate(44.184 -44.184 -18.961)" class="hebxnubow"/></g><g filter="url(#iF0b06c)"><rect transform="scale(-1 1)rotate(44.184 -44.651 -18.254)" class="h91tgxbdh"/></g><path fill="url(#id8fUTd)" transform="rotate(135.816 26.633 25.336)" class="d7t5c3bcg"/><path fill="url(#iDqQddd)" transform="rotate(135.816 26.633 25.336)" class="d7t5c3bcg"/><path fill="url(#iaz4Zxj)" transform="rotate(-180 18.655 20.195)" class="gr0xwfbsq"/><rect fill="url(#i9rlPqj)" transform="rotate(-180 13.888 29.188)" class="lxwna7htg"/><path class="na5ps0b6u"/><path fill="url(#ixq2wMc)" class="kx-bcespw"/><path fill="url(#i9aGk3K)" class="kx-bcespw"/><path fill="url(#i6s7Fre)" class="kx-bcespw"/><path fill="url(#iFT1ARc)" class="kx-bcespw"/><g filter="url(#iS0U2Mb)"><path fill="url(#iQxpQTd)" class="m546nebir"/><path fill="url(#iZF7kXd)" class="m546nebir"/><path fill="url(#iMplImd)" class="m546nebir"/><path fill="url(#iGB7t1c)" class="m546nebir"/><path fill="url(#ipNY3Mc)" class="m546nebir"/></g><path class="equhh1t5g"/><path fill="url(#iNgO3ue)" class="li6veqsxp"/><path fill="url(#i5V8ece)" class="li6veqsxp"/><path fill="url(#isr2aip)" class="li6veqsxp"/><g filter="url(#iGmGlee)"><path class="caog4u2we"/></g><g filter="url(#iq2efLb)"><path class="v1g1kqbgg"/><path fill="url(#iU7laze)" class="a6h5ccbnr"/></g><path fill="url(#ilxSKgd)" class="a6h5ccbnr"/><path fill="url(#iMhVatp)" class="a6h5ccbnr"/><g filter="url(#iVYwXob)" class="n52mgrb1s"><path class="mt_0cpx2h"/></g><path fill="url(#iqIEnAK)" class="nv7x83egt"/><path fill="url(#iAk3Tac)" class="nv7x83egt"/><path fill="url(#iimnBpB)" class="nv7x83egt"/><g filter="url(#iYfvgjc)"><path class="qm9kvjbbx"/><path fill="url(#iuxv2xc)" class="znagombkh"/><path fill="url(#ihiEgZR)" class="znagombkh"/></g><path class="fce_0tbwc"/><path fill="url(#iefxFde)" class="acooy_brq"/><path fill="url(#ito5fYb)" class="xkxb7i23v"/><path fill="url(#izTPAAb)" class="xkxb7i23v"/><g filter="url(#iFFKPWd)"><path class="i1gy6l-dg"/></g><g filter="url(#isYs0Bb)"><path fill="url(#iyfOdhT)" class="v6tz--bhh"/><path fill="url(#idIBxyc)" class="v6tz--bhh"/></g><g filter="url(#i5IjRvd)"><path stroke="url(#i5qSm4z)" class="rg2j5ukfn"/></g><path class="vvygfyb5w"/><path fill="url(#ipQodAd)" class="wr73-rkij"/><g filter="url(#ihGKtte)"><path class="zdlct5bqh"/></g><g filter="url(#inR2Uce)"><path class="x34v5ibpx"/></g><g filter="url(#ixYsCnb)"><path class="iuoi1mb4z"/><path fill="url(#i2hNe1d)" class="vm87efbps"/></g><g filter="url(#idlXtBd)"><path class="nd5jn1bki"/><path fill="url(#iGFUWvc)" class="fretmcbwx"/><path fill="url(#iWI87Oe)" class="fretmcbwx"/></g><path class="wp9md_1ih"/><path fill="url(#ibwgR1b)" class="mfraueb8y"/><path class="tp85um94k"/><g filter="url(#i2X5Ukb)"><path class="q7c98roxw"/><path fill="url(#iQ01x0w)" class="bs2i_1znm"/></g><g filter="url(#ikI3plb)"><path fill="url(#ibMSxJd)" class="x57fihbhz"/></g><path class="qzr-n-b-m"/><path fill="url(#i7ULjtd)" class="v6-if6afu"/><path class="kwp1jsbas"/><g filter="url(#iBjlkxb)"><path fill="url(#iKBlMUd)" class="tkingabjf"/></g><g filter="url(#iazC7ld)"><ellipse transform="matrix(-.88173 .47176 -.46454 -.88555 18.493 22.76)" class="f9_6ngb8g"/><ellipse fill="url(#iL5v7Vb)" transform="matrix(-.88173 .47176 -.46454 -.88555 18.493 22.76)" class="gat_xeb0t"/></g><path fill="url(#iYPTd5c)" class="mjekxty3q"/><path class="bgilymbju"/><path fill="url(#ismE12G)" class="g1olaqbqg"/><g filter="url(#iy2N9Ne)"><path class="x5k9uab0a"/></g><g filter="url(#itfzfUb)"><path class="b4nssz08n"/></g><g filter="url(#ixa4ZXb)"><path class="xrewtzzvk"/></g><g filter="url(#iKVrkgH)"><path class="n162shb9v"/></g><defs><radialGradient id="iaz4Zxj" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .61719 -.75071 1.4064 19.293 20.633)" gradientUnits="userSpaceOnUse"><stop class="h2ug0z0zy"/><stop offset="1" class="nqe9_3xqo"/></radialGradient><radialGradient id="i9rlPqj" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .17335 -.34548 -.77853 15.085 29.47)" gradientUnits="userSpaceOnUse"><stop class="w3mc4qk1n"/><stop offset="1" class="ol2abdblh"/></radialGradient><radialGradient id="ixq2wMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48865 0 0 -3.771 15.486 28)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="k2wpap9_u"/><stop offset="1" class="de3gtwbql"/></radialGradient><radialGradient id="i9aGk3K" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91895 0 0 -4.67725 15.658 24.031)" gradientUnits="userSpaceOnUse"><stop offset=".414" class="bltptbchx"/><stop offset="1" class="ghbrfbb8g"/></radialGradient><radialGradient id="i6s7Fre" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1 3.83881 0 14.07 30.031)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="bbk20sbrs"/><stop offset="1" class="s8mikn8pw"/></radialGradient><radialGradient id="iFT1ARc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.76709 .3344 0 13.63 25.98)" gradientUnits="userSpaceOnUse"><stop class="v3a4xqbpf"/><stop offset="1" class="br6wf4dup"/></radialGradient><radialGradient id="iQxpQTd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.96875 0 0 -7.09375 20.718 18.344)" gradientUnits="userSpaceOnUse"><stop class="it0i-9poh"/><stop offset="1" class="c2c-tdbgt"/></radialGradient><radialGradient id="iZF7kXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 1.5 -.78696 .59022 20.655 19.25)" gradientUnits="userSpaceOnUse"><stop class="cuayq7bpx"/><stop offset="1" class="x36benbsm"/></radialGradient><radialGradient id="iMplImd" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 -.9375 2.63274 2.01844 19.593 21.5)" gradientUnits="userSpaceOnUse"><stop class="s-n6o8b9p"/><stop offset="1" class="t5vd2wb5s"/></radialGradient><radialGradient id="ipNY3Mc" cx="0" cy="0" r="1" gradientTransform="rotate(-142.918 11.854 7.775)scale(1.68439 3.3263)" gradientUnits="userSpaceOnUse"><stop class="unngbdc_q"/><stop offset="1" class="afx92cb1k"/></radialGradient><radialGradient id="i5V8ece" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 0 0 -4.625 13.051 12.49)" gradientUnits="userSpaceOnUse"><stop class="e_oa-tb8l"/><stop offset="1" class="bo50hoaxz"/></radialGradient><radialGradient id="iU7laze" cx="0" cy="0" r="1" gradientTransform="rotate(132.58 14.64 7.66)scale(1.57029 1.5193)" gradientUnits="userSpaceOnUse"><stop class="qp90otrnq"/><stop offset="1" class="jbzjrkbhk"/></radialGradient><radialGradient id="iimnBpB" cx="0" cy="0" r="1" gradientTransform="rotate(78.283 -5.952 8.098)scale(2.15427 6.77116)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="bef5gkb7g"/><stop offset="1" class="c62vuxxso"/></radialGradient><radialGradient id="iefxFde" cx="0" cy="0" r="1" gradientTransform="rotate(-162.389 11.68 9.318)scale(.64485 2.00552)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="ito5fYb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71924 0 0 -5.64748 18.63 21.98)" gradientUnits="userSpaceOnUse"><stop class="u3zcvnbjy"/><stop offset=".552" class="hjeaf0kfx"/></radialGradient><radialGradient id="izTPAAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.08883 1.17167 0 18.441 22.596)" gradientUnits="userSpaceOnUse"><stop class="mp3-5nt4j"/><stop offset="1" class="bfty3ybmf"/></radialGradient><radialGradient id="idIBxyc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47266 0 0 -.1563 17.781 21.7)" gradientUnits="userSpaceOnUse"><stop class="rgikgeffu"/><stop offset="1" class="oskiey9pw"/></radialGradient><radialGradient id="i2hNe1d" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 1.2624 -3.03347 2.36538 18.483 23.91)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="cpvxurbrw"/><stop offset="1" class="tti32obdt"/></radialGradient><radialGradient id="iGFUWvc" cx="0" cy="0" r="1" gradientTransform="rotate(153.734 5.496 13.878)scale(1.53331 2.40757)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="vbbx-tqjr"/><stop offset="1" class="t7ktntowc"/></radialGradient><radialGradient id="iWI87Oe" cx="0" cy="0" r="1" gradientTransform="matrix(-.65625 .20515 -.16236 -.51937 17.255 24.646)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="ibwgR1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34066 .53654 0 16.565 22.72)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iQ01x0w" cx="0" cy="0" r="1" gradientTransform="matrix(.09654 .12564 -.17255 .13259 16.659 22.684)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7ULjtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34068 .53657 0 18.38 22.72)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iL5v7Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00323 -.20727 .24777 -.00386 .156 .215)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYPTd5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.77344 0 0 -.87395 15.527 22.441)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="z2p55f_ys"/><stop offset="1" class="wnz4hcbxb"/></radialGradient><radialGradient id="ismE12G" cx="0" cy="0" r="1" gradientTransform="matrix(.42344 -.95181 .92957 .41355 19.41 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="flq8uy9_y"/><stop offset=".887" class="r66150hyt"/></radialGradient><filter id="i94b43d" width="2.064" height="2.201" x="25.478" y="24.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="iILn6ec" width="2.069" height="2.206" x="25.515" y="25.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="i4P9IOb" width="1.801" height="1.929" x="25.239" y="25.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="iF0b06c" width="1.405" height="1.524" x="24.915" y="26.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="iS0U2Mb" width="8.77" height="8.383" x="13.223" y="13.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="iGmGlee" width="6.829" height="7.242" x="20.747" y="3.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.317647 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="iq2efLb" width="4.79" height="2.813" x="25.665" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="iVYwXob" width="5.938" height="6.795" x="21.027" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".15"/></filter><filter id="iYfvgjc" width="10.596" height="6.162" x="12.56" y="8.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="iFFKPWd" width="2.727" height="3.219" x="16.168" y="20.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".5"/></filter><filter id="isYs0Bb" width=".981" height="1.419" x="16.982" y="21.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="i5IjRvd" width="1.74" height=".851" x="16.602" y="20.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="ihGKtte" width="1.032" height=".616" x="15.879" y="23.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="inR2Uce" width="1.032" height=".61" x="18.066" y="23.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23557"/></filter><filter id="ixYsCnb" width="2.872" height="2.495" x="17.239" y="23.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="idlXtBd" width="2.571" height="2.362" x="14.896" y="23.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="i2X5Ukb" width=".444" height=".409" x="16.484" y="22.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="ikI3plb" width=".604" height=".615" x="16.034" y="22.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".1"/></filter><filter id="iBjlkxb" width=".643" height=".668" x="17.843" y="22.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".1"/></filter><filter id="iazC7ld" width=".497" height=".412" x="18.244" y="22.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="iy2N9Ne" width=".594" height=".999" x="14.923" y="21.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="itfzfUb" width=".988" height=".472" x="18.038" y="23.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="ixa4ZXb" width=".988" height=".472" x="15.841" y="23.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><filter id="iKVrkgH" width=".545" height=".989" x="19.454" y="21.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23557" stdDeviation=".05"/></filter><linearGradient id="iEScWPc" x1="26.276" x2="25.725" y1="27.951" y2="27.951" gradientUnits="userSpaceOnUse"><stop class="r2_7pkbmo"/><stop offset="1" class="wcwoqrbaq"/></linearGradient><linearGradient id="iCAMPGd" x1=".146" x2=".125" y1=".968" y2="1.327" gradientUnits="userSpaceOnUse"><stop offset=".115" class="jbqcexb-p"/><stop offset="1" class="b2el6qblq"/></linearGradient><linearGradient id="ivhuhgb" x1=".201" x2=".188" y1=".545" y2="1.014" gradientUnits="userSpaceOnUse"><stop offset=".255" class="jbqcexb-p"/><stop offset="1" class="le3x4zbvz"/></linearGradient><linearGradient id="iX8Qwud" x1=".211" x2=".203" y1=".458" y2=".853" gradientUnits="userSpaceOnUse"><stop offset=".255" class="jbqcexb-p"/><stop offset="1" class="le3x4zbvz"/></linearGradient><linearGradient id="id8fUTd" x1="26.892" x2="29.141" y1="28.145" y2="28.432" gradientUnits="userSpaceOnUse"><stop offset=".144" class="y3cw3wbjk"/><stop offset=".951" class="umwffwbyy"/></linearGradient><linearGradient id="iDqQddd" x1="28.792" x2="28" y1="28.767" y2="28.757" gradientUnits="userSpaceOnUse"><stop class="ry8hkacaj"/><stop offset="1" class="qfa7lcbwg"/></linearGradient><linearGradient id="iGB7t1c" x1="14.03" x2="18.843" y1="13.438" y2="15.094" gradientUnits="userSpaceOnUse"><stop offset=".288" class="yvm272b3l"/><stop offset="1" class="t7_glwz_k"/></linearGradient><linearGradient id="iNgO3ue" x1="8.962" x2="8.962" y1="14.039" y2="12.521" gradientUnits="userSpaceOnUse"><stop class="kkx5bsbxf"/><stop offset="1" class="ywea8pb6g"/></linearGradient><linearGradient id="isr2aip" x1="8.114" x2="8.192" y1="11.833" y2="12.349" gradientUnits="userSpaceOnUse"><stop class="iwyc2pgqn"/><stop offset="1" class="w9a9hvbwq"/></linearGradient><linearGradient id="ilxSKgd" x1="27.436" x2="27.436" y1="2.063" y2="2.211" gradientUnits="userSpaceOnUse"><stop class="su56_nrsk"/><stop offset="1" class="wrxtldewy"/></linearGradient><linearGradient id="iMhVatp" x1="25.915" x2="26.592" y1="2.531" y2="2.531" gradientUnits="userSpaceOnUse"><stop class="gt57qko1f"/><stop offset="1" class="mak5wnjve"/></linearGradient><linearGradient id="iqIEnAK" x1="5.468" x2="4.811" y1="11.812" y2="12.391" gradientUnits="userSpaceOnUse"><stop class="d3k6isbnm"/><stop offset="1" class="mi7m9xbsl"/></linearGradient><linearGradient id="iAk3Tac" x1="3.1" x2="3.257" y1="12.578" y2="12.766" gradientUnits="userSpaceOnUse"><stop offset=".07" class="kfgxjwb7e"/><stop offset="1" class="gzc8sbczu"/></linearGradient><linearGradient id="iuxv2xc" x1="12.876" x2="13.345" y1="14.469" y2="11.781" gradientUnits="userSpaceOnUse"><stop offset=".264" class="kswhxtfcb"/><stop offset="1" class="cj3zw_ajv"/></linearGradient><linearGradient id="ihiEgZR" x1="21.72" x2="20.845" y1="12.875" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="a3l5-0b9h"/><stop offset="1" class="b3vardzds"/></linearGradient><linearGradient id="iyfOdhT" x1="17.769" x2="17.238" y1="22.154" y2="22.154" gradientUnits="userSpaceOnUse"><stop class="qafkwysiq"/><stop offset="1" class="tyvu9i1wu"/></linearGradient><linearGradient id="i5qSm4z" x1="18.142" x2="17.836" y1="20.892" y2="21.26" gradientUnits="userSpaceOnUse"><stop class="sfhz-f7-s"/><stop offset="1" class="salt5zbwy"/></linearGradient><linearGradient id="ipQodAd" x1="18.52" x2="17.27" y1="26.208" y2="24.255" gradientUnits="userSpaceOnUse"><stop class="gyl-lqo5h"/><stop offset="1" class="owp7pqbrv"/></linearGradient><linearGradient id="ibMSxJd" x1="16.242" x2="16.373" y1="22.697" y2="22.617" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iKBlMUd" x1="18.072" x2="18.202" y1="22.698" y2="22.618" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-cartwheeling-medium-dark" /></template>
<style>
.a3l5-0b9h {
  stop-color: var(--svg-color--9d94a4, #9D94A4);
}

.a6h5ccbnr {
  d: path("m27.548 4.375l-1.633-.773v-1.29a.25.25 0 0 1 .25-.25h3.972c.151 0 .3.086.315.237c.026.281-.125.62-.6.951c-.542.352-1.699.844-2.304 1.125");
}

.acooy_brq {
  d: path("M19.495 21.81c.14.004.27.052.376.13v-.392a.91.91 0 0 0-.558-.849q.107.23.144.496z");
}

.afx92cb1k {
  stop-color: var(--svg-color--e36121, #E36121);
  stop-opacity: 0;
}

.b_028jvwm {
  width: 0.699px;
  height: 2.521px;
  rx: 0.349px;
}

.b2el6qblq {
  stop-color: var(--svg-color--94736d, #94736D);
  stop-opacity: 0;
}

.b3vardzds {
  stop-color: var(--svg-color--9d94a4, #9D94A4);
  stop-opacity: 0;
}

.b4nssz08n {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.876 23.515a.96.96 0 0 1-.688.16");
}

.bbk20sbrs {
  stop-color: var(--svg-color--81466d, #81466D);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bef5gkb7g {
  stop-color: var(--svg-color--403178, #403178);
  stop-opacity: 0;
}

.bfty3ybmf {
  stop-color: var(--svg-color--94605f, #94605F);
  stop-opacity: 0;
}

.bgilymbju {
  fill: var(--svg-color--815754, #815754);
  d: path("M19.575 23.116a.674.674 0 0 0 .575-.67a.674.674 0 0 0-.633-.676c.027.45.05.896.058 1.346");
}

.bltptbchx {
  stop-color: var(--svg-color--64353e, #64353E);
}

.bo50hoaxz {
  stop-color: var(--svg-color--714652, #714652);
  stop-opacity: 0;
}

.br6wf4dup {
  stop-color: var(--svg-color--8f685e, #8F685E);
  stop-opacity: 0;
}

.bs2i_1znm {
  d: path("M16.591 22.84c-.026-.035.03-.078.092-.126c.063-.047.11-.08.136-.045s-.003.103-.066.15c-.063.048-.135.058-.162.022");
}

.c2c-tdbgt {
  stop-color: var(--svg-color--f7702e, #F7702E);
}

.c62vuxxso {
  stop-color: var(--svg-color--403178, #403178);
}

.caog4u2we {
  fill: var(--svg-color--805a4e, #805A4E);
  d: path("m23.118 10.59l4.458-6.244l-1.635-.748l-5.194 4.836z");
}

.cj3zw_ajv {
  stop-color: var(--svg-color--9e93a6, #9E93A6);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cuayq7bpx {
  stop-color: var(--svg-color--ffa764, #FFA764);
}

.d3k6isbnm {
  stop-color: var(--svg-color--686897, #686897);
}

.d7t5c3bcg {
  d: path("M26.633 25.336h2.014v7.07h-2.014z");
}

.de3gtwbql {
  stop-color: var(--svg-color--926b68, #926B68);
  stop-opacity: 0;
}

.e_oa-tb8l {
  stop-color: var(--svg-color--714652, #714652);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.equhh1t5g {
  fill: var(--svg-color--856053, #856053);
  d: path("m12.767 14.04l-7.61-.142l.625-1.57l6.844-.984z");
}

.f9_6ngb8g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.163px;
  ry: 0.083px;
}

.fce_0tbwc {
  fill: var(--svg-color--271d1c, #271D1C);
  d: path("M15.45 21.81a.7.7 0 0 0-.376.13v-.392c0-.376.222-.71.558-.849q-.106.23-.144.496z");
}

.flq8uy9_y {
  stop-color: var(--svg-color--93716a, #93716A);
  stop-opacity: 0;
}

.fretmcbwx {
  d: path("m15.304 23.322l.012.265c.004.32.267.585.585.599h.582c.37 0 .707.204.884.529c0 0-.304.873-.805.758c-.361-.082-.746-.212-1.041-.406c-.726-.478-.599-1.34-.217-1.745");
}

.ft5dv1b6b {
  fill: none;
}

.g1olaqbqg {
  d: path("M19.575 23.116a.674.674 0 0 0 .575-.67a.674.674 0 0 0-.633-.676c.027.45.05.896.058 1.346");
}

.gat_xeb0t {
  rx: 0.163px;
  ry: 0.083px;
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ghbrfbb8g {
  stop-color: var(--svg-color--744c4e, #744C4E);
  stop-opacity: 0;
}

.gr0xwfbsq {
  d: path("M18.655 20.195h2.326v1.781h-2.326z");
}

.gt57qko1f {
  stop-color: var(--svg-color--5f5e7a, #5F5E7A);
}

.gyl-lqo5h {
  stop-color: var(--svg-color--44294d, #44294D);
}

.gzc8sbczu {
  stop-color: var(--svg-color--424272, #424272);
  stop-opacity: 0;
}

.h2ug0z0zy {
  stop-color: var(--svg-color--75524a, #75524A);
}

.h91tgxbdh {
  width: 0.665px;
  height: 1.584px;
  fill: var(--svg-color--7f4d5f, #7F4D5F);
  rx: 0.332px;
}

.hebxnubow {
  width: 0.737px;
  height: 2.121px;
  rx: 0.368px;
}

.hjeaf0kfx {
  stop-color: var(--svg-color--7e4e4e, #7E4E4E);
}

.i1gy6l-dg {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m17.64 22.553l.245-.773c.042-.16-.059-.318-.202-.318h-.304c-.143 0-.244.161-.202.318l.206.773c.044.171.21.171.256 0");
}

.it0i-9poh {
  stop-color: var(--svg-color--ff954f, #FF954F);
}

.iuoi1mb4z {
  fill: var(--svg-color--300f2f, #300F2F);
  d: path("M17.347 24.784q.016.028.028.057c.042.106.284.112.397.112h.53c.767 0 1.39-.636 1.39-1.42v-.116c.14.109.319.338.319.71c0 .45-.326.677-.533.823a1 1 0 0 0-.18.15c-.145.156-.404.433-.856.554a2 2 0 0 1-.277.053c-.412.05-.728-.288-.792-.698l-.034-.22z");
}

.iwyc2pgqn {
  stop-color: var(--svg-color--7d6155, #7D6155);
}

.j6w3anb3u {
  width: 0.684px;
  height: 2.521px;
  rx: 0.342px;
}

.jbqcexb-p {
  stop-color: var(--svg-color--a07d74, #A07D74);
}

.jbzjrkbhk {
  stop-color: var(--svg-color--686995, #686995);
  stop-opacity: 0;
}

.k2wpap9_u {
  stop-color: var(--svg-color--926b68, #926B68);
}

.kfgxjwb7e {
  stop-color: var(--svg-color--424272, #424272);
}

.kkx5bsbxf {
  stop-color: var(--svg-color--804b71, #804B71);
}

.kswhxtfcb {
  stop-color: var(--svg-color--836591, #836591);
}

.kwp1jsbas {
  fill: var(--svg-color--000, #000);
  d: path("M18.169 22.545a.213.213 0 1 0 .425 0a.2.2 0 0 0-.024-.098h-.376a.2.2 0 0 0-.025.098");
}

.kx-bcespw {
  d: path("M14.82 29.85c-.296.03-.955.087-1.58.087c-.653 0-.73-.345-.731-.519c-.01-.115.056-.368.39-.465c.121-.035.26-.072.397-.108a.2.2 0 0 0 .15-.194v-6.628h2.04v7.129a.7.7 0 0 1-.564.686l.001.002l-.025.003z");
}

.le3x4zbvz {
  stop-color: var(--svg-color--8c6564, #8C6564);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li6veqsxp {
  d: path("m12.767 14.04l-7.61-.142l.625-1.57l6.844-.984z");
}

.lxwna7htg {
  width: 1.121px;
  height: 0.563px;
  x: 13.888px;
  y: 29.188px;
  rx: 0.281px;
}

.m546nebir {
  d: path("M20.693 18.206c.526.664 1.057 1.569 1.3 2.278l-1.578 1.43l-1.82-1.43l-.826-1.669a.3.3 0 0 0-.534-.006l-1.695 3.214h-2.117c.084-1.569.551-3.03.88-3.75c.07-.15.112-.313.112-.48v-4.152h6.188v4.309c0 .093.032.183.09.256");
}

.mak5wnjve {
  stop-color: var(--svg-color--41406b, #41406B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfraueb8y {
  d: path("M16.564 22.92a.373.373 0 0 1-.358-.473h.717a.374.374 0 0 1-.36.474");
}

.mi7m9xbsl {
  stop-color: var(--svg-color--514f87, #514F87);
}

.mjekxty3q {
  d: path("M15.425 21.77q-.041.672-.077 1.342a.675.675 0 0 1-.553-.666c0-.36.278-.655.63-.676");
}

.mp3-5nt4j {
  stop-color: var(--svg-color--94605f, #94605F);
}

.mt_0cpx2h {
  stroke: var(--svg-color--896661, #896661);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m26.551 4.229l-5.11 6");
}

.n162shb9v {
  fill: var(--svg-color--673d39, #673D39);
  d: path("M19.588 22.838a.4.4 0 0 0 .31-.391a.4.4 0 0 0-.344-.398q.021.394.034.79");
}

.n52mgrb1s {
  opacity: var(--svg-opacity--0-4, 0.4);
}

.na5ps0b6u {
  fill: var(--svg-color--86595c, #86595C);
  d: path("M14.82 29.85c-.296.03-.955.087-1.58.087c-.653 0-.73-.345-.731-.519c-.01-.115.056-.368.39-.465c.121-.035.26-.072.397-.108a.2.2 0 0 0 .15-.194v-6.628h2.04v7.129a.7.7 0 0 1-.564.686l.001.002l-.025.003z");
}

.nd5jn1bki {
  fill: var(--svg-color--2a171d, #2A171D);
  d: path("m15.304 23.322l.012.265c.004.32.267.585.585.599h.582c.37 0 .707.204.884.529c0 0-.304.873-.805.758c-.361-.082-.746-.212-1.041-.406c-.726-.478-.599-1.34-.217-1.745");
}

.nqe9_3xqo {
  stop-color: var(--svg-color--714a3d, #714A3D);
}

.nv7x83egt {
  d: path("M4.698 11.294a.25.25 0 0 1 .346.027l.875.984l-.734 1.59l-1.176.335c-.305.1-1.059.303-1.637.325a.89.89 0 0 1-.778-.37c-.092-.123-.047-.291.072-.389z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol2abdblh {
  stop-color: var(--svg-color--794e41, #794E41);
}

.oskiey9pw {
  stop-color: var(--svg-color--a87f75, #A87F75);
  stop-opacity: 0;
}

.owp7pqbrv {
  stop-color: var(--svg-color--361e2a, #361E2A);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q7c98roxw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.591 22.84c-.026-.035.03-.078.092-.126c.063-.047.11-.08.136-.045s-.003.103-.066.15c-.063.048-.135.058-.162.022");
}

.qafkwysiq {
  stop-color: var(--svg-color--8b5961, #8B5961);
}

.qfa7lcbwg {
  stop-color: var(--svg-color--743e50, #743E50);
  stop-opacity: 0;
}

.qm9kvjbbx {
  fill: var(--svg-color--a59dae, #A59DAE);
  d: path("m20.615 14.064l2.542-3.495L20.783 8.4c-.14.134-.505.492-.84.85c-1.188 1.15-2.767 1.43-3.776 1.58l-3.607.495v2.737z");
}

.qp90otrnq {
  stop-color: var(--svg-color--686995, #686995);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzk34pbjf {
  width: 0.699px;
  height: 2.521px;
  fill: var(--svg-color--875d5c, #875D5C);
  rx: 0.349px;
}

.qzr-n-b-m {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.467 23.034c.272 0 .501-.19.564-.445a.115.115 0 0 0-.112-.143h-.928a.096.096 0 0 0-.095.114c.052.27.289.474.57.474");
}

.r2_7pkbmo {
  stop-color: var(--svg-color--855b5b, #855B5B);
}

.r66150hyt {
  stop-color: var(--svg-color--93716a, #93716A);
}

.r96i785dr {
  width: 0.737px;
  height: 2.121px;
  fill: var(--svg-color--875d5c, #875D5C);
  rx: 0.368px;
}

.rg2j5ukfn {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.472 21.118c.211 0 .41.05.577.138c.057.029.118-.036.082-.088a.786.786 0 0 0-1.318 0c-.036.054.025.117.082.088c.167-.088.364-.138.577-.138Z");
}

.rgikgeffu {
  stop-color: var(--svg-color--a87f75, #A87F75);
}

.ry8hkacaj {
  stop-color: var(--svg-color--743e50, #743E50);
}

.s_txeqb5u {
  width: 0.684px;
  height: 2.521px;
  fill: var(--svg-color--947266, #947266);
  rx: 0.342px;
}

.s-n6o8b9p {
  stop-color: var(--svg-color--d95968, #D95968);
}

.s8mikn8pw {
  stop-color: var(--svg-color--85575e, #85575E);
  stop-opacity: 0;
}

.salt5zbwy {
  stop-color: var(--svg-color--9e786e, #9E786E);
  stop-opacity: 0;
}

.sfhz-f7-s {
  stop-color: var(--svg-color--9e786e, #9E786E);
}

.su56_nrsk {
  stop-color: var(--svg-color--444570, #444570);
}

.t5vd2wb5s {
  stop-color: var(--svg-color--ff782c, #FF782C);
  stop-opacity: 0;
}

.t7_glwz_k {
  stop-color: var(--svg-color--d25836, #D25836);
  stop-opacity: 0;
}

.t7ktntowc {
  stop-color: var(--svg-color--3f2c32, #3F2C32);
}

.tkingabjf {
  d: path("M18.043 22.59c0 .12.097.201.123.226l.12-.117l-.074-.152z");
}

.tp85um94k {
  fill: var(--svg-color--000, #000);
  d: path("M16.777 22.545a.213.213 0 1 1-.425 0q0-.055.023-.099h.376a.2.2 0 0 1 .026.1");
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tyvu9i1wu {
  stop-color: var(--svg-color--815950, #815950);
}

.u3zcvnbjy {
  stop-color: var(--svg-color--a1786d, #A1786D);
}

.uib5ptygi {
  width: 0.809px;
  height: 1.648px;
  x: 25.404px;
  y: 27.272px;
  rx: 0.404px;
}

.umwffwbyy {
  stop-color: var(--svg-color--82505a, #82505A);
}

.unngbdc_q {
  stop-color: var(--svg-color--e36121, #E36121);
}

.v1g1kqbgg {
  fill: var(--svg-color--504e84, #504E84);
  d: path("m27.548 4.375l-1.633-.773v-1.29a.25.25 0 0 1 .25-.25h3.972c.151 0 .3.086.315.237c.026.281-.125.62-.6.951c-.542.352-1.699.844-2.304 1.125");
}

.v3a4xqbpf {
  stop-color: var(--svg-color--8f685e, #8F685E);
}

.v6-if6afu {
  d: path("M18.381 22.92a.373.373 0 0 0 .358-.473h-.717a.376.376 0 0 0 .36.474");
}

.v6tz--bhh {
  d: path("m17.632 22.635l.22-.773c.046-.159-.062-.318-.216-.318h-.327c-.154 0-.262.162-.217.318l.221.773c.047.171.269.171.319 0");
}

.vbbx-tqjr {
  stop-color: var(--svg-color--3f2c32, #3F2C32);
  stop-opacity: 0;
}

.vm87efbps {
  d: path("M17.347 24.784q.016.028.028.057c.042.106.284.112.397.112h.53c.767 0 1.39-.636 1.39-1.42v-.116c.14.109.319.338.319.71c0 .45-.326.677-.533.823a1 1 0 0 0-.18.15c-.145.156-.404.433-.856.554a2 2 0 0 1-.277.053c-.412.05-.728-.288-.792-.698l-.034-.22z");
}

.vvygfyb5w {
  fill: var(--svg-color--87014e, #87014E);
  d: path("M17.472 21.118c.211 0 .41.05.577.138c.057.029.118-.036.082-.088a.786.786 0 0 0-1.318 0c-.036.054.025.117.082.088c.167-.088.364-.138.577-.138");
}

.w3mc4qk1n {
  stop-color: var(--svg-color--815c51, #815C51);
}

.w9a9hvbwq {
  stop-color: var(--svg-color--7d6155, #7D6155);
  stop-opacity: 0;
}

.wcwoqrbaq {
  stop-color: var(--svg-color--6f3a41, #6F3A41);
}

.wnz4hcbxb {
  stop-color: var(--svg-color--775654, #775654);
}

.wp9md_1ih {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.477 23.034a.58.58 0 0 1-.564-.445a.115.115 0 0 1 .112-.143h.929c.059 0 .106.054.094.114a.58.58 0 0 1-.57.474");
}

.wr73-rkij {
  d: path("M15.453 25.126a.97.97 0 0 1-.527-.442a1 1 0 0 1 .044-1.061a.66.66 0 0 0 .112-.368v-.499a.7.7 0 0 0 .278.113l-.033.675a.606.606 0 0 0 .574.601h.582c.398 0 .757.237.92.607a.28.28 0 0 0 .256.175h.53c.768 0 1.39-.635 1.39-1.42l-.013-.645a.7.7 0 0 0 .3-.111v.504c0 .131.04.26.112.368c.199.295.234.691.06 1.027a.98.98 0 0 1-.54.473a1.12 1.12 0 0 0-.577.467a.965.965 0 0 1-1.202.383a.6.6 0 0 0-.497 0a1 1 0 0 1-.379.079a.97.97 0 0 1-.827-.476a1.05 1.05 0 0 0-.563-.45");
}

.wrxtldewy {
  stop-color: var(--svg-color--444570, #444570);
  stop-opacity: 0;
}

.x34v5ibpx {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.892 23.632a1.15 1.15 0 0 1-.724.151a.116.116 0 0 1-.1-.13a.116.116 0 0 1 .128-.101a.9.9 0 0 0 .608-.14l.007-.005h.001c.05-.04.123-.03.162.02s.03.124-.02.164z");
}

.x36benbsm {
  stop-color: var(--svg-color--ffa764, #FFA764);
  stop-opacity: 0;
}

.x57fihbhz {
  d: path("M16.234 22.595c.014.097.07.17.096.194l.108-.12l-.049-.095z");
}

.x5k9uab0a {
  fill: var(--svg-color--663c39, #663C39);
  d: path("m15.416 22.047l-.046.8a.4.4 0 0 1-.347-.399a.4.4 0 0 1 .393-.401");
}

.xkxb7i23v {
  d: path("M19.48 21.173a1.635 1.635 0 0 0-1.617-1.43h-.785c-.818 0-1.509.61-1.616 1.43c-.05.791-.098 1.58-.135 2.37a.606.606 0 0 0 .574.602h.582c.398 0 .757.237.92.607a.28.28 0 0 0 .256.175h.53c.768 0 1.39-.635 1.39-1.42c0-.781-.049-1.55-.1-2.334");
}

.xrewtzzvk {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.992 23.534a.96.96 0 0 0 .688.16");
}

.y3cw3wbjk {
  stop-color: var(--svg-color--9f7c73, #9F7C73);
}

.yvm272b3l {
  stop-color: var(--svg-color--d25836, #D25836);
}

.ywea8pb6g {
  stop-color: var(--svg-color--855c5a, #855C5A);
  stop-opacity: 0;
}

.z2p55f_ys {
  stop-color: var(--svg-color--6c4447, #6C4447);
}

.zdlct5bqh {
  fill: var(--svg-color--202020, #202020);
  d: path("M15.919 23.587a.8.8 0 0 0 .286.172c.127.04.285.052.505.024a.116.116 0 0 0 .1-.13a.116.116 0 0 0-.128-.101c-.2.025-.323.012-.408-.015a.54.54 0 0 1-.203-.126a.115.115 0 0 0-.163.011a.117.117 0 0 0 .01.165");
}

.znagombkh {
  d: path("m20.615 14.064l2.542-3.495L20.783 8.4c-.14.134-.505.492-.84.85c-1.188 1.15-2.767 1.43-3.776 1.58l-3.607.495v2.737z");
}

</style>
