<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iG2u1jc)" transform="rotate(-180 25.403 27.272)" class="hb-psqlil"/><g filter="url(#i6pSOxk)"><rect transform="scale(-1 1)rotate(44.184 -43.275 -19.634)" class="gi506kb9q"/><rect fill="url(#ijCVFhe)" transform="scale(-1 1)rotate(44.184 -43.275 -19.634)" class="j6w3anb3u"/></g><g filter="url(#iwmBssN)"><rect transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="x34qmvpwc"/><rect fill="url(#i0s4Axc)" transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="b_028jvwm"/></g><g filter="url(#iqlwiPb)"><rect transform="scale(-1 1)rotate(44.184 -44.184 -18.961)" class="dwz22lr8d"/><rect fill="url(#iuxWGGb)" transform="scale(-1 1)rotate(44.184 -44.184 -18.961)" class="hebxnubow"/></g><g filter="url(#i5qfLbb)"><rect transform="scale(-1 1)rotate(44.184 -44.65 -18.254)" class="xtbl79bad"/></g><path fill="url(#i4ISUjb)" transform="rotate(135.816 26.632 25.336)" class="rajtvkueh"/><path fill="url(#ipe63GQ)" transform="rotate(135.816 26.632 25.336)" class="rajtvkueh"/><path fill="url(#i3pZ15b)" transform="rotate(-180 18.655 20.195)" class="gr0xwfbsq"/><rect fill="url(#izofXxd)" transform="rotate(-180 13.888 29.188)" class="lxwna7htg"/><path class="v978--kqi"/><path fill="url(#iaHP7ud)" class="kx-bcespw"/><path fill="url(#isYAP1b)" class="kx-bcespw"/><path fill="url(#i3DBK1b)" class="kx-bcespw"/><path fill="url(#inGfAJd)" class="kx-bcespw"/><g filter="url(#i0B60fd)"><path fill="url(#iTAmixd)" class="kac7h8b2r"/><path fill="url(#iSzRw8b)" class="kac7h8b2r"/><path fill="url(#icMBAeg)" class="kac7h8b2r"/><path fill="url(#ifIFHwe)" class="kac7h8b2r"/><path fill="url(#iZcOVBb)" class="kac7h8b2r"/></g><path class="bgkl6acgr"/><path fill="url(#irS7u4T)" class="li6veqsxp"/><g filter="url(#iOSCMKY)"><path class="ihbgqvgtu"/></g><g filter="url(#inZ61jd)"><path class="v1g1kqbgg"/><path fill="url(#iU7laze)" class="a6h5ccbnr"/></g><path fill="url(#ilxSKgd)" class="a6h5ccbnr"/><path fill="url(#iMhVatp)" class="a6h5ccbnr"/><g filter="url(#ix0nqec)" class="n52mgrb1s"><path class="xwu2ttbct"/></g><path fill="url(#ihoERHb)" class="nv7x83egt"/><path fill="url(#iUuV1Vz)" class="nv7x83egt"/><path fill="url(#iimnBpB)" class="nv7x83egt"/><g filter="url(#iAydgsb)"><path class="iyyz2kbjw"/><path fill="url(#iuxv2xc)" class="j87yrib4w"/><path fill="url(#ihiEgZR)" class="j87yrib4w"/></g><g filter="url(#itnllJb)"><circle fill="url(#iyiRY7P)" transform="rotate(-180 19.459 22.462)" class="ralokpx7i"/></g><g filter="url(#iOBNDUh)"><circle fill="url(#iG9WhEA)" transform="rotate(-180 19.459 22.462)" class="k0uyrwzqx"/></g><g filter="url(#iRudbzq)"><circle fill="url(#i40L6Qc)" transform="rotate(-180 15.448 22.462)" class="hfnxbsdpj"/><circle fill="url(#ig858cd)" transform="rotate(-180 15.448 22.462)" class="hfnxbsdpj"/></g><g filter="url(#ixcSijb)"><circle transform="rotate(-180 15.448 22.462)" class="oynfubcml"/><circle fill="url(#iq6PCrR)" transform="rotate(-180 15.448 22.462)" class="ze_lg5i_b"/><circle fill="url(#iZCv60d)" transform="rotate(-180 15.448 22.462)" class="ze_lg5i_b"/></g><path fill="url(#iIkHYtd)" class="b5sr_bcwj"/><path fill="url(#iueweeb)" class="b5sr_bcwj"/><path fill="url(#is6ThZb)" class="b5sr_bcwj"/><path fill="url(#i8wGEHc)" class="b5sr_bcwj"/><g filter="url(#ixPACbx)"><path fill="url(#i8wQcVc)" class="f3452-bzb"/></g><g filter="url(#iqJ202d)"><path class="o77xylwhk"/><path fill="url(#i0ZANsc)" class="e5m9wwbgi"/><path fill="url(#imn0cGd)" class="e5m9wwbgi"/><path fill="url(#iiEimgI)" class="e5m9wwbgi"/><path fill="url(#iyqd2hd)" class="e5m9wwbgi"/></g><g filter="url(#iVbBjib)"><path fill="url(#ibKRWhe)" class="sz02ezb7m"/><path fill="url(#iwPzK2b)" class="sz02ezb7m"/></g><g filter="url(#iGioXge)"><path stroke="url(#iKoFfRb)" class="rway69lgs"/></g><path class="cxjpfissf"/><g filter="url(#iiL4wNc)"><path class="lsqvpebwa"/></g><g filter="url(#isidhzP)"><path class="p5b4ieqxw"/></g><path class="q8ncrs8qa"/><path fill="url(#iugebvd)" class="z1i56bbno"/><path class="enc8ox11m"/><g filter="url(#iALwbkb)"><path class="b4y3feb1s"/><path fill="url(#iBa6Q0b)" class="wpcm56j6f"/></g><g filter="url(#iY3kGZd)"><path fill="url(#iHiqf1d)" class="hqf-7yhrj"/></g><path class="a86x2abyw"/><path fill="url(#igAKc1t)" class="aa075pnyu"/><path class="gztp5n77n"/><g filter="url(#i3UhP5b)"><path fill="url(#ikAbMzc)" class="h-0euwbuu"/></g><g filter="url(#iGDS1tc)"><ellipse transform="rotate(152.086 18.492 22.79)" class="o-yi08b2m"/><ellipse fill="url(#ijgAQFS)" transform="rotate(152.086 18.492 22.79)" class="c-8xs89ph"/></g><g filter="url(#iNcLr8c)"><path stroke="url(#iZHSoGb)" class="mgj5ibbjf"/></g><g filter="url(#idR4A3d)"><path stroke="url(#iO9p8jc)" class="r2wxnnb3e"/></g><g filter="url(#i8Lyf8S)"><path stroke="url(#ifGxYUb)" class="l7q-ctb4a"/></g><defs><radialGradient id="i3pZ15b" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .61719 -.75071 1.4064 19.293 20.633)" gradientUnits="userSpaceOnUse"><stop class="f4mk8fixa"/><stop offset="1" class="pxnxywniq"/></radialGradient><radialGradient id="izofXxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .17335 -.34548 -.77853 15.085 29.47)" gradientUnits="userSpaceOnUse"><stop class="o3mvph8dm"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iaHP7ud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48865 0 0 -3.771 15.486 28)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="tnqh9ccqf"/><stop offset="1" class="zjrvq0-we"/></radialGradient><radialGradient id="isYAP1b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91895 0 0 -4.67725 15.657 24.031)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="bcch6bcem"/><stop offset="1" class="tz-uiqujb"/></radialGradient><radialGradient id="i3DBK1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1 3.83881 0 14.069 30.031)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="l_1xkfbcx"/><stop offset="1" class="euozh3rjl"/></radialGradient><radialGradient id="inGfAJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.76709 .3344 0 13.629 25.98)" gradientUnits="userSpaceOnUse"><stop class="os2wlib8d"/><stop offset="1" class="le9atxcgh"/></radialGradient><radialGradient id="iTAmixd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.96875 0 0 -7.09375 20.717 18.344)" gradientUnits="userSpaceOnUse"><stop class="jk0wsqyqs"/><stop offset="1" class="d490xxnbe"/></radialGradient><radialGradient id="iSzRw8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 1.5 -.78696 .59022 20.655 19.25)" gradientUnits="userSpaceOnUse"><stop class="ht2yfkjwb"/><stop offset="1" class="bamjsvb8t"/></radialGradient><radialGradient id="icMBAeg" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 -.9375 2.63274 2.01844 19.592 21.5)" gradientUnits="userSpaceOnUse"><stop class="h5k7xu51c"/><stop offset="1" class="ot3t6hbfc"/></radialGradient><radialGradient id="iZcOVBb" cx="0" cy="0" r="1" gradientTransform="rotate(-142.918 11.854 7.775)scale(1.68439 3.3263)" gradientUnits="userSpaceOnUse"><stop class="kcvv1loqd"/><stop offset="1" class="ngyzvbbds"/></radialGradient><radialGradient id="iU7laze" cx="0" cy="0" r="1" gradientTransform="rotate(132.58 14.64 7.66)scale(1.57029 1.5193)" gradientUnits="userSpaceOnUse"><stop class="qp90otrnq"/><stop offset="1" class="jbzjrkbhk"/></radialGradient><radialGradient id="iimnBpB" cx="0" cy="0" r="1" gradientTransform="rotate(78.283 -5.952 8.098)scale(2.15427 6.77116)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="bef5gkb7g"/><stop offset="1" class="c62vuxxso"/></radialGradient><radialGradient id="iyiRY7P" cx="0" cy="0" r="1" gradientTransform="matrix(.73986 0 0 1.29476 18.755 22.462)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="ig858cd" cx="0" cy="0" r="1" gradientTransform="matrix(.34854 -.2538 .28967 .39782 15.604 22.35)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iq6PCrR" cx="0" cy="0" r="1" gradientTransform="rotate(-61.468 26.896 -1.572)scale(.72489 .42428)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iZCv60d" cx="0" cy="0" r="1" gradientTransform="matrix(.10932 .1082 -.1395 .14093 15.448 22.462)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iIkHYtd" cx="0" cy="0" r="1" gradientTransform="rotate(59.94 -9.045 24.534)scale(5.81313 5.01362)" gradientUnits="userSpaceOnUse"><stop class="x6cb79s7g"/><stop offset="1" class="vxng6nb4k"/></radialGradient><radialGradient id="iueweeb" cx="0" cy="0" r="1" gradientTransform="rotate(150.21 6.885 12.645)scale(2.48457 1.07315)" gradientUnits="userSpaceOnUse"><stop class="m2_juxbhz"/><stop offset="1" class="ik_rtwb6g"/></radialGradient><radialGradient id="is6ThZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92188 -.9624 0 18.407 23.026)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="qxt6awing"/><stop offset="1" class="jaxrm4b9t"/></radialGradient><radialGradient id="i8wGEHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .95313 -.82204 0 18.36 22.448)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="o1_vcrbmn"/><stop offset="1" class="mm2o7sbxj"/></radialGradient><radialGradient id="i0ZANsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.33636 1.24653 -.46225 -.12473 15.625 24.193)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="imn0cGd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61258 -.1484 .0798 -.86707 16.317 24.935)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iiEimgI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.70795 1.09641 0 17.457 26.088)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iyqd2hd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29599 .94974 -1.48793 -2.0304 20.176 23.214)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iwPzK2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.47859 0 0 -.14492 17.77 21.716)" gradientUnits="userSpaceOnUse"><stop class="eser-fblc"/><stop offset="1" class="v41ltixcj"/></radialGradient><radialGradient id="iugebvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34198 .54395 0 16.538 22.75)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iBa6Q0b" cx="0" cy="0" r="1" gradientTransform="matrix(.09775 .12597 -.17343 .13458 16.634 22.714)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igAKc1t" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.342 .54398 0 18.378 22.75)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijgAQFS" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 20.526 2.362)scale(.20829 .25036)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i6pSOxk" width="2.064" height="2.201" x="25.477" y="24.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.301961 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="iwmBssN" width="2.069" height="2.206" x="25.515" y="25.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.301961 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="iqlwiPb" width="1.801" height="1.929" x="25.239" y="25.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.301961 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="i5qfLbb" width="1.405" height="1.524" x="24.915" y="26.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.341176 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="i0B60fd" width="8.77" height="8.383" x="13.223" y="13.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.647059 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="iOSCMKY" width="6.829" height="7.242" x="20.747" y="3.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.196078 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="inZ61jd" width="4.79" height="2.813" x="25.665" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="ix0nqec" width="5.638" height="6.495" x="21.177" y="3.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".075"/></filter><filter id="iAydgsb" width="10.596" height="6.162" x="12.56" y="8.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="itnllJb" width="1.608" height="1.408" x="18.755" y="21.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="iOBNDUh" width="1.839" height="1.839" x="18.539" y="21.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".25"/></filter><filter id="iRudbzq" width="1.658" height="1.658" x="14.744" y="21.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="ixcSijb" width="1.839" height="1.839" x="14.528" y="21.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".25"/></filter><filter id="ixPACbx" width="2.99" height="2.493" x="14.58" y="22.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".3"/></filter><filter id="iqJ202d" width="5.313" height="3.891" x="14.8" y="22.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="iVbBjib" width=".991" height="1.33" x="16.961" y="21.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".05"/></filter><filter id="iGioXge" width="2.157" height="1.252" x="16.378" y="20.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".1"/></filter><filter id="iiL4wNc" width="1.401" height="1.021" x="15.807" y="22.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="isidhzP" width="1.401" height="1.021" x="17.978" y="22.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23556"/></filter><filter id="iALwbkb" width=".447" height=".409" x="16.458" y="22.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".05"/></filter><filter id="iY3kGZd" width=".607" height=".616" x="16.002" y="22.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".1"/></filter><filter id="i3UhP5b" width=".647" height=".67" x="17.835" y="22.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".1"/></filter><filter id="iGDS1tc" width=".501" height=".413" x="18.242" y="22.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".05"/></filter><filter id="iNcLr8c" width="1.08" height=".482" x="15.827" y="23.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".05"/></filter><filter id="idR4A3d" width="1.113" height=".506" x="17.995" y="23.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".05"/></filter><filter id="i8Lyf8S" width=".859" height="1.391" x="18.993" y="23.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23556" stdDeviation=".125"/></filter><linearGradient id="iG2u1jc" x1="26.276" x2="25.725" y1="27.951" y2="27.951" gradientUnits="userSpaceOnUse"><stop class="h673f0b8e"/><stop offset="1" class="xvly769iz"/></linearGradient><linearGradient id="ijCVFhe" x1=".25" x2=".271" y1=".929" y2="1.399" gradientUnits="userSpaceOnUse"><stop offset=".428" class="teq1wcc5y"/><stop offset="1" class="b77kwcxfk"/></linearGradient><linearGradient id="i0s4Axc" x1=".261" x2=".265" y1=".63" y2="1.399" gradientUnits="userSpaceOnUse"><stop class="xa9-br0qr"/><stop offset="1" class="f0lf6f3kb"/></linearGradient><linearGradient id="iuxWGGb" x1=".275" x2=".278" y1=".53" y2="1.177" gradientUnits="userSpaceOnUse"><stop class="xa9-br0qr"/><stop offset="1" class="f0lf6f3kb"/></linearGradient><linearGradient id="i4ISUjb" x1="26.997" x2="28.808" y1="28.247" y2="28.311" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset="1" class="v34cuvbln"/></linearGradient><linearGradient id="ipe63GQ" x1="28.792" x2="28" y1="28.767" y2="28.757" gradientUnits="userSpaceOnUse"><stop class="oitdcsota"/><stop offset="1" class="o9s385b5r"/></linearGradient><linearGradient id="ifIFHwe" x1="14.03" x2="18.842" y1="13.438" y2="15.094" gradientUnits="userSpaceOnUse"><stop offset=".288" class="gesenab-k"/><stop offset="1" class="kscf9stoz"/></linearGradient><linearGradient id="irS7u4T" x1="8.962" x2="8.962" y1="14.039" y2="12.691" gradientUnits="userSpaceOnUse"><stop class="o_ps3m-cy"/><stop offset="1" class="uqe6fccna"/></linearGradient><linearGradient id="ilxSKgd" x1="27.436" x2="27.436" y1="2.063" y2="2.211" gradientUnits="userSpaceOnUse"><stop class="su56_nrsk"/><stop offset="1" class="wrxtldewy"/></linearGradient><linearGradient id="iMhVatp" x1="25.915" x2="26.592" y1="2.531" y2="2.531" gradientUnits="userSpaceOnUse"><stop class="gt57qko1f"/><stop offset="1" class="mak5wnjve"/></linearGradient><linearGradient id="ihoERHb" x1="5.467" x2="4.811" y1="11.812" y2="12.391" gradientUnits="userSpaceOnUse"><stop class="d3k6isbnm"/><stop offset="1" class="mi7m9xbsl"/></linearGradient><linearGradient id="iUuV1Vz" x1="3.1" x2="3.256" y1="12.578" y2="12.766" gradientUnits="userSpaceOnUse"><stop offset=".07" class="kfgxjwb7e"/><stop offset="1" class="gzc8sbczu"/></linearGradient><linearGradient id="iuxv2xc" x1="12.876" x2="13.345" y1="14.469" y2="11.781" gradientUnits="userSpaceOnUse"><stop offset=".264" class="kswhxtfcb"/><stop offset="1" class="cj3zw_ajv"/></linearGradient><linearGradient id="ihiEgZR" x1="21.72" x2="20.845" y1="12.875" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="a3l5-0b9h"/><stop offset="1" class="b3vardzds"/></linearGradient><linearGradient id="iG9WhEA" x1="19.459" x2="19.189" y1="22.58" y2="22.58" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="i40L6Qc" x1="15.906" x2="15.56" y1="22.002" y2="23.071" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="i8wQcVc" x1="16.637" x2="13.005" y1="23.722" y2="24.972" gradientUnits="userSpaceOnUse"><stop class="tsmkxzbsq"/><stop offset="1" class="qch_jxzrh"/></linearGradient><linearGradient id="ibKRWhe" x1="17.758" x2="17.22" y1="22.136" y2="22.136" gradientUnits="userSpaceOnUse"><stop class="nrr3n3buo"/><stop offset="1" class="g_uy3wbky"/></linearGradient><linearGradient id="iKoFfRb" x1="17.894" x2="17.711" y1="20.89" y2="21.18" gradientUnits="userSpaceOnUse"><stop class="mk3b6ubaz"/><stop offset=".663" class="miy4z8bft"/></linearGradient><linearGradient id="iHiqf1d" x1="16.21" x2="16.343" y1="22.727" y2="22.645" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikAbMzc" x1="18.064" x2="18.197" y1="22.727" y2="22.645" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZHSoGb" x1="16.204" x2="16.381" y1="23.629" y2="23.991" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iO9p8jc" x1="18.44" x2="18.942" y1="23.683" y2="23.893" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ifGxYUb" x1="19.422" x2="19.422" y1="24.532" y2="23.623" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-cartwheeling-dark" /></template>
<style>
.a3l5-0b9h {
  stop-color: var(--svg-color--9d94a4, #9D94A4);
}

.a6h5ccbnr {
  d: path("m27.548 4.375l-1.633-.773v-1.29a.25.25 0 0 1 .25-.25h3.972c.151 0 .3.086.315.237c.026.281-.125.62-.6.951c-.542.352-1.699.844-2.304 1.125");
}

.a86x2abyw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.466 23.065c.275 0 .508-.19.571-.446a.116.116 0 0 0-.113-.144h-.94a.097.097 0 0 0-.096.115a.59.59 0 0 0 .578.475");
}

.aa075pnyu {
  d: path("M18.379 22.95a.376.376 0 0 0 .362-.475h-.727a.38.38 0 0 0 .364.475");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.b_028jvwm {
  width: 0.699px;
  height: 2.521px;
  rx: 0.349px;
}

.b3vardzds {
  stop-color: var(--svg-color--9d94a4, #9D94A4);
  stop-opacity: 0;
}

.b4y3feb1s {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.565 22.871c-.027-.036.03-.08.093-.127c.064-.048.111-.081.138-.045s-.003.103-.067.15c-.064.049-.137.058-.164.022");
}

.b5sr_bcwj {
  d: path("M19.607 22.72h-.02s.022.36.045.607c0 .112-.046.247-.136.314l-.068.068a.45.45 0 0 0-.158.36v.36a.22.22 0 0 1-.181.224c-.271.068-.837.18-1.65.18c-.815 0-1.38-.112-1.652-.18a.24.24 0 0 1-.18-.224v-.36a.53.53 0 0 0-.159-.36c-.212-.148-.199-.23-.18-.405c.022-.225.044-.607.044-.607h-.007l.112-1.669c.067-.746.654-1.266 1.353-1.266h1.354c.722 0 1.286.52 1.353 1.266z");
}

.b77kwcxfk {
  stop-color: var(--svg-color--6b5755, #6B5755);
  stop-opacity: 0;
}

.bamjsvb8t {
  stop-color: var(--svg-color--50c7ff, #50C7FF);
  stop-opacity: 0;
}

.bcch6bcem {
  stop-color: var(--svg-color--271118, #271118);
}

.bef5gkb7g {
  stop-color: var(--svg-color--403178, #403178);
  stop-opacity: 0;
}

.bgkl6acgr {
  fill: var(--svg-color--4b3231, #4B3231);
  d: path("m12.767 14.04l-7.61-.142l.625-1.57l6.844-.984z");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c-8xs89ph {
  cx: 18.492px;
  cy: 22.79px;
  rx: 0.164px;
  ry: 0.083px;
}

.c62vuxxso {
  stop-color: var(--svg-color--403178, #403178);
}

.cj3zw_ajv {
  stop-color: var(--svg-color--9e93a6, #9E93A6);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxjpfissf {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M17.457 21.142c.214 0 .415.05.584.139c.058.03.12-.036.083-.088a.8.8 0 0 0-.667-.357a.8.8 0 0 0-.668.357c-.036.054.026.117.084.088a1.26 1.26 0 0 1 .584-.139");
}

.d3k6isbnm {
  stop-color: var(--svg-color--686897, #686897);
}

.d490xxnbe {
  stop-color: var(--svg-color--33a2f1, #33A2F1);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dwz22lr8d {
  width: 0.737px;
  height: 2.121px;
  fill: var(--svg-color--3f202f, #3F202F);
  rx: 0.368px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5m9wwbgi {
  d: path("m15.425 25.193l-.18-.09a.83.83 0 0 1-.43-.9l.248-1.281c.023-.132.11-.221.242-.225h.007s-.022.382-.045.607c-.018.183.014.239.18.405a.53.53 0 0 1 .16.36v.36c0 .112.09.202.18.225c.271.067.837.18 1.651.18s1.38-.113 1.65-.18a.22.22 0 0 0 .182-.225v-.36c0-.135.045-.27.158-.36l.068-.067c.09-.068.136-.203.136-.315c-.023-.248-.046-.607-.046-.607h.021c.126.009.23.097.25.225l.25 1.281a.86.86 0 0 1-.453.877l-.18.09a3 3 0 0 0-.34.247l-.407.428a.83.83 0 0 1-.927.135a1.24 1.24 0 0 0-.701 0c-.34.112-.724.022-.995-.225l-.34-.338a.95.95 0 0 0-.339-.247");
}

.enc8ox11m {
  fill: var(--svg-color--000, #000);
  d: path("M16.753 22.574c0 .12-.096.216-.216.216a.215.215 0 0 1-.191-.315h.381a.2.2 0 0 1 .026.1");
}

.eser-fblc {
  stop-color: var(--svg-color--675250, #675250);
}

.euozh3rjl {
  stop-color: var(--svg-color--422640, #422640);
  stop-opacity: 0;
}

.f0lf6f3kb {
  stop-color: var(--svg-color--432633, #432633);
  stop-opacity: 0;
}

.f3452-bzb {
  d: path("m15.37 24.833l1.298-.432a.442.442 0 0 0-.198-.857l-1.29.173z");
}

.f4mk8fixa {
  stop-color: var(--svg-color--432c2a, #432C2A);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g_uy3wbky {
  stop-color: var(--svg-color--40272d, #40272D);
}

.gesenab-k {
  stop-color: var(--svg-color--3280d1, #3280D1);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gi506kb9q {
  width: 0.684px;
  height: 2.521px;
  fill: var(--svg-color--3f202f, #3F202F);
  rx: 0.342px;
}

.gr0xwfbsq {
  d: path("M18.655 20.195h2.326v1.781h-2.326z");
}

.gt57qko1f {
  stop-color: var(--svg-color--5f5e7a, #5F5E7A);
}

.gzc8sbczu {
  stop-color: var(--svg-color--424272, #424272);
  stop-opacity: 0;
}

.gztp5n77n {
  fill: var(--svg-color--000, #000);
  d: path("M18.163 22.574c0 .12.096.216.216.216a.215.215 0 0 0 .191-.315h-.381a.2.2 0 0 0-.026.1");
}

.h-0euwbuu {
  d: path("M18.035 22.619c0 .121.099.202.125.227l.122-.118l-.075-.152z");
}

.h5k7xu51c {
  stop-color: var(--svg-color--487fd0, #487FD0);
}

.h673f0b8e {
  stop-color: var(--svg-color--523f3e, #523F3E);
}

.hb-psqlil {
  width: 0.809px;
  height: 1.648px;
  x: 25.403px;
  y: 27.272px;
  rx: 0.404px;
}

.hebxnubow {
  width: 0.737px;
  height: 2.121px;
  rx: 0.368px;
}

.hfnxbsdpj {
  cx: 15.448px;
  cy: 22.462px;
  r: 0.704px;
}

.hqf-7yhrj {
  d: path("M16.202 22.624c.014.097.071.17.098.195l.11-.12l-.05-.096z");
}

.ht2yfkjwb {
  stop-color: var(--svg-color--5dd2ff, #5DD2FF);
}

.ihbgqvgtu {
  fill: var(--svg-color--452f2c, #452F2C);
  d: path("m23.118 10.59l4.458-6.244l-1.635-.748l-5.194 4.836z");
}

.ik_rtwb6g {
  stop-color: var(--svg-color--6c5957, #6C5957);
  stop-opacity: 0;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iyyz2kbjw {
  fill: var(--svg-color--a59dae, #A59DAE);
  d: path("m20.615 14.064l2.541-3.495L20.783 8.4c-.14.134-.505.492-.841.85c-1.187 1.15-2.766 1.43-3.775 1.58l-3.607.495v2.737z");
}

.j6w3anb3u {
  width: 0.684px;
  height: 2.521px;
  rx: 0.342px;
}

.j87yrib4w {
  d: path("m20.615 14.064l2.541-3.495L20.783 8.4c-.14.134-.505.492-.841.85c-1.187 1.15-2.766 1.43-3.775 1.58l-3.607.495v2.737z");
}

.jaxrm4b9t {
  stop-color: var(--svg-color--665453, #665453);
  stop-opacity: 0;
}

.jbzjrkbhk {
  stop-color: var(--svg-color--686995, #686995);
  stop-opacity: 0;
}

.jk0wsqyqs {
  stop-color: var(--svg-color--4cbfff, #4CBFFF);
}

.k0uyrwzqx {
  cx: 19.459px;
  cy: 22.462px;
  r: 0.419px;
}

.kac7h8b2r {
  d: path("M20.693 18.206c.526.664 1.056 1.569 1.3 2.278l-1.578 1.43l-1.82-1.43l-.826-1.669a.3.3 0 0 0-.534-.006l-1.695 3.214h-2.117c.084-1.569.551-3.03.88-3.75c.07-.15.112-.313.112-.48v-4.152h6.188v4.309c0 .093.032.183.09.256");
}

.kcvv1loqd {
  stop-color: var(--svg-color--2874ab, #2874AB);
}

.kfgxjwb7e {
  stop-color: var(--svg-color--424272, #424272);
}

.kibsqob-j {
  stop-color: var(--svg-color--6a5654, #6A5654);
}

.kscf9stoz {
  stop-color: var(--svg-color--309fea, #309FEA);
  stop-opacity: 0;
}

.kswhxtfcb {
  stop-color: var(--svg-color--836591, #836591);
}

.kx-bcespw {
  d: path("M14.82 29.85c-.296.03-.955.087-1.58.087c-.653 0-.73-.345-.731-.519c-.01-.115.056-.368.39-.465c.121-.035.26-.072.397-.108a.2.2 0 0 0 .15-.194v-6.628h2.04v7.129a.7.7 0 0 1-.564.686l.001.002l-.025.003z");
}

.l_1xkfbcx {
  stop-color: var(--svg-color--422640, #422640);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7q-ctb4a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.368 24.49v-.378c.003-.063.03-.203.109-.262");
}

.le9atxcgh {
  stop-color: var(--svg-color--574440, #574440);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li6veqsxp {
  d: path("m12.767 14.04l-7.61-.142l.625-1.57l6.844-.984z");
}

.lsqvpebwa {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m15.889 23.609l.003.002l.005.004l.015.012l.05.034a1.2 1.2 0 0 0 .806.155a.225.225 0 1 0-.07-.444a.74.74 0 0 1-.497-.093l-.026-.018a.225.225 0 0 0-.286.348");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lxwna7htg {
  width: 1.121px;
  height: 0.563px;
  x: 13.888px;
  y: 29.188px;
  rx: 0.281px;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m2_juxbhz {
  stop-color: var(--svg-color--6c5957, #6C5957);
}

.mak5wnjve {
  stop-color: var(--svg-color--41406b, #41406B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgj5ibbjf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.757 23.67c-.182.032-.535.022-.78-.168");
}

.mi7m9xbsl {
  stop-color: var(--svg-color--514f87, #514F87);
}

.miy4z8bft {
  stop-color: var(--svg-color--502f37, #502F37);
  stop-opacity: 0;
}

.mk3b6ubaz {
  stop-color: var(--svg-color--502f37, #502F37);
}

.mm2o7sbxj {
  stop-color: var(--svg-color--4a2c31, #4A2C31);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n52mgrb1s {
  opacity: var(--svg-opacity--0-4, 0.4);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ngyzvbbds {
  stop-color: var(--svg-color--3293c7, #3293C7);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nrr3n3buo {
  stop-color: var(--svg-color--4e3236, #4E3236);
}

.nv7x83egt {
  d: path("M4.698 11.294a.25.25 0 0 1 .346.027l.875.984l-.734 1.59l-1.176.335c-.305.1-1.059.303-1.637.325a.89.89 0 0 1-.778-.37c-.092-.123-.047-.291.072-.389z");
}

.o_ps3m-cy {
  stop-color: var(--svg-color--40253c, #40253C);
}

.o-yi08b2m {
  cx: 18.492px;
  cy: 22.79px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.164px;
  ry: 0.083px;
}

.o1_vcrbmn {
  stop-color: var(--svg-color--4a2c31, #4A2C31);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o3mvph8dm {
  stop-color: var(--svg-color--53413e, #53413E);
}

.o77xylwhk {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m15.425 25.193l-.18-.09a.83.83 0 0 1-.43-.9l.248-1.281c.023-.132.11-.221.242-.225h.007s-.022.382-.045.607c-.018.183.014.239.18.405a.53.53 0 0 1 .16.36v.36c0 .112.09.202.18.225c.271.067.837.18 1.651.18s1.38-.113 1.65-.18a.22.22 0 0 0 .182-.225v-.36c0-.135.045-.27.158-.36l.068-.067c.09-.068.136-.203.136-.315c-.023-.248-.046-.607-.046-.607h.021c.126.009.23.097.25.225l.25 1.281a.86.86 0 0 1-.453.877l-.18.09a3 3 0 0 0-.34.247l-.407.428a.83.83 0 0 1-.927.135a1.24 1.24 0 0 0-.701 0c-.34.112-.724.022-.995-.225l-.34-.338a.95.95 0 0 0-.339-.247");
}

.o9s385b5r {
  stop-color: var(--svg-color--371f2e, #371F2E);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oitdcsota {
  stop-color: var(--svg-color--371f2e, #371F2E);
}

.os2wlib8d {
  stop-color: var(--svg-color--574440, #574440);
}

.ot3t6hbfc {
  stop-color: var(--svg-color--34a4e5, #34A4E5);
  stop-opacity: 0;
}

.oynfubcml {
  cx: 15.448px;
  cy: 22.462px;
  r: 0.419px;
  fill: var(--svg-color--463133, #463133);
}

.p5b4ieqxw {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.048 23.609h-.002l-.002.002l-.005.004l-.065.046a1.2 1.2 0 0 1-.806.155a.225.225 0 0 1 .07-.444a.74.74 0 0 0 .497-.093l.023-.015l.004-.003a.225.225 0 0 1 .286.348");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxnxywniq {
  stop-color: var(--svg-color--442e32, #442E32);
}

.q8ncrs8qa {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.45 23.065a.59.59 0 0 1-.571-.446a.116.116 0 0 1 .113-.144h.94c.06 0 .108.055.096.115a.59.59 0 0 1-.578.475");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qch_jxzrh {
  stop-color: var(--svg-color--594541, #594541);
  stop-opacity: 0;
}

.qp90otrnq {
  stop-color: var(--svg-color--686995, #686995);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxt6awing {
  stop-color: var(--svg-color--665453, #665453);
}

.r2wxnnb3e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.958 23.451c-.138.122-.44.25-.813.19");
}

.rajtvkueh {
  d: path("M26.632 25.336h2.014v7.07h-2.014z");
}

.ralokpx7i {
  cx: 19.459px;
  cy: 22.462px;
  r: 0.704px;
}

.rway69lgs {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m16.79 21.193l-.084-.056a.16.16 0 0 0 .018.2a.165.165 0 0 0 .194.033h.001a1.16 1.16 0 0 1 .538-.128c.198 0 .383.047.538.127v.001c.074.037.15.013.195-.034a.16.16 0 0 0 .017-.2a.9.9 0 0 0-.75-.4a.9.9 0 0 0-.751.402zm0 0a.8.8 0 0 1 .667-.357c.28 0 .526.143.667.357c.037.052-.025.117-.083.088a1.3 1.3 0 0 0-.584-.139c-.216 0-.415.05-.584.139c-.058.03-.12-.034-.084-.088Z");
}

.su56_nrsk {
  stop-color: var(--svg-color--444570, #444570);
}

.sz02ezb7m {
  d: path("m17.618 22.582l.224-.716a.227.227 0 0 0-.22-.295h-.331a.228.228 0 0 0-.22.295l.225.716c.048.16.272.16.322 0");
}

.teq1wcc5y {
  stop-color: var(--svg-color--6b5755, #6B5755);
}

.tnqh9ccqf {
  stop-color: var(--svg-color--5a4545, #5A4545);
}

.tsmkxzbsq {
  stop-color: var(--svg-color--594541, #594541);
}

.tz-uiqujb {
  stop-color: var(--svg-color--432c2d, #432C2D);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uqe6fccna {
  stop-color: var(--svg-color--492f32, #492F32);
  stop-opacity: 0;
}

.v1g1kqbgg {
  fill: var(--svg-color--504e84, #504E84);
  d: path("m27.548 4.375l-1.633-.773v-1.29a.25.25 0 0 1 .25-.25h3.972c.151 0 .3.086.315.237c.026.281-.125.62-.6.951c-.542.352-1.699.844-2.304 1.125");
}

.v34cuvbln {
  stop-color: var(--svg-color--422830, #422830);
}

.v41ltixcj {
  stop-color: var(--svg-color--675250, #675250);
  stop-opacity: 0;
}

.v978--kqi {
  fill: var(--svg-color--432b2c, #432B2C);
  d: path("M14.82 29.85c-.296.03-.955.087-1.58.087c-.653 0-.73-.345-.731-.519c-.01-.115.056-.368.39-.465c.121-.035.26-.072.397-.108a.2.2 0 0 0 .15-.194v-6.628h2.04v7.129a.7.7 0 0 1-.564.686l.001.002l-.025.003z");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vxng6nb4k {
  stop-color: var(--svg-color--4e3135, #4E3135);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wpcm56j6f {
  d: path("M16.565 22.871c-.027-.036.03-.08.093-.127c.064-.048.111-.081.138-.045s-.003.103-.067.15c-.064.049-.137.058-.164.022");
}

.wrxtldewy {
  stop-color: var(--svg-color--444570, #444570);
  stop-opacity: 0;
}

.x34qmvpwc {
  width: 0.699px;
  height: 2.521px;
  fill: var(--svg-color--3f202f, #3F202F);
  rx: 0.349px;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x6cb79s7g {
  stop-color: var(--svg-color--442f30, #442F30);
}

.xa9-br0qr {
  stop-color: var(--svg-color--5f494a, #5F494A);
}

.xtbl79bad {
  width: 0.665px;
  height: 1.584px;
  fill: var(--svg-color--422830, #422830);
  rx: 0.332px;
}

.xvly769iz {
  stop-color: var(--svg-color--2b1218, #2B1218);
}

.xwu2ttbct {
  stroke: var(--svg-color--543e3e, #543E3E);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m26.55 4.229l-5.108 6");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.z1i56bbno {
  d: path("M16.537 22.95a.376.376 0 0 1-.362-.475h.726a.378.378 0 0 1-.364.475");
}

.ze_lg5i_b {
  cx: 15.448px;
  cy: 22.462px;
  r: 0.419px;
}

.zjrvq0-we {
  stop-color: var(--svg-color--4c3036, #4C3036);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
