<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iTJgSmk)" transform="rotate(-180 25.404 27.272)" class="uib5ptygi"/><g filter="url(#icVjLde)"><rect transform="scale(-1 1)rotate(44.184 -43.275 -19.634)" class="m1lhgybcq"/><rect fill="url(#i1V7HGd)" transform="scale(-1 1)rotate(44.184 -43.275 -19.634)" class="j6w3anb3u"/></g><g filter="url(#i2P8Nhc)"><rect transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="qzk34pbjf"/><rect fill="url(#ivhuhgb)" transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="b_028jvwm"/></g><g filter="url(#iNcCFoe)"><rect transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="g1x3feakc"/><rect fill="url(#iGMX5Qd)" transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="b_028jvwm"/></g><g filter="url(#iAIcJXb)"><rect transform="scale(-1 1)rotate(44.184 -44.184 -18.961)" class="y1s6k-s_j"/><rect fill="url(#ij2vdrb)" transform="scale(-1 1)rotate(44.184 -44.184 -18.961)" class="hebxnubow"/></g><g filter="url(#iD9fNNc)"><rect transform="scale(-1 1)rotate(44.184 -44.651 -18.254)" class="mjq3nac3p"/></g><path fill="url(#iIcHDqc)" transform="rotate(135.816 26.633 25.336)" class="d7t5c3bcg"/><path fill="url(#i2CCi4b)" transform="rotate(135.816 26.633 25.336)" class="d7t5c3bcg"/><path fill="url(#ilDfu2d)" transform="rotate(-180 18.655 20.195)" class="gr0xwfbsq"/><rect fill="url(#iFG1gwe)" transform="rotate(-180 13.888 29.188)" class="lxwna7htg"/><path class="p-vlvd2fc"/><path fill="url(#iEcNnCe)" class="kx-bcespw"/><path fill="url(#iI4Uxdc)" class="kx-bcespw"/><path fill="url(#iSDyUOd)" class="kx-bcespw"/><path fill="url(#iFpAIDe)" class="kx-bcespw"/><g filter="url(#i7D7zge)"><path fill="url(#ixTfUec)" class="m546nebir"/><path fill="url(#iSzRw8b)" class="m546nebir"/><path fill="url(#icfMATg)" class="m546nebir"/><path fill="url(#i4acwCe)" class="m546nebir"/><path fill="url(#iZcOVBb)" class="m546nebir"/></g><path class="ga3uz0zmk"/><path fill="url(#idfIiWc)" class="li6veqsxp"/><path fill="url(#icCUqRd)" class="li6veqsxp"/><path fill="url(#iJvjhqL)" class="li6veqsxp"/><g filter="url(#iQVEZgM)"><path class="m6xg0iv-q"/></g><g filter="url(#i522pjd)"><path class="v1g1kqbgg"/><path fill="url(#iU7laze)" class="a6h5ccbnr"/></g><path fill="url(#ilxSKgd)" class="a6h5ccbnr"/><path fill="url(#iMhVatp)" class="a6h5ccbnr"/><g filter="url(#iRsUX3c)" class="n52mgrb1s"><path class="lyb5hkpdy"/></g><path fill="url(#iFAQRBf)" class="gjxr99ebn"/><path fill="url(#iAk3Tac)" class="gjxr99ebn"/><path fill="url(#iimnBpB)" class="gjxr99ebn"/><g filter="url(#i4cjpWc)"><path class="qm9kvjbbx"/><path fill="url(#iuxv2xc)" class="znagombkh"/><path fill="url(#ihiEgZR)" class="znagombkh"/></g><circle fill="url(#i6qnhpb)" transform="rotate(-180 19.459 22.457)" class="ivpdgybcg"/><g filter="url(#idlWqJb)"><circle transform="rotate(-180 19.458 22.457)" class="f49ru9mwd"/></g><circle fill="url(#iIJfMqc)" transform="rotate(-180 15.447 22.457)" class="nzwnzr7pk"/><g filter="url(#i5gTZtc)"><circle transform="rotate(-180 15.447 22.457)" class="v9pgtobbi"/></g><path fill="url(#iIAVdgb)" class="p7em5jbop"/><path fill="url(#imL8lpb)" class="p7em5jbop"/><path fill="url(#iMB7j2d)" class="p7em5jbop"/><path fill="url(#ip0vi6H)" class="p7em5jbop"/><path fill="url(#imHeUlb)" class="p7em5jbop"/><path fill="url(#i3KntJT)" class="p7em5jbop"/><g filter="url(#iPpTUqt)"><path class="qh_qstsih"/></g><g filter="url(#iBw5Yjc)"><path fill="url(#idv6R7d)" class="ble7gfbfv"/><path fill="url(#iemyitb)" class="ble7gfbfv"/><path fill="url(#imQvJqy)" class="ble7gfbfv"/></g><g filter="url(#inFxPwz)"><path fill="url(#iozR42b)" class="ezd15ek3s"/><path fill="url(#i3jYsdf)" class="ezd15ek3s"/></g><g filter="url(#irknRRG)"><path stroke="url(#i0M5Lhb)" class="er2rr_b4h"/></g><path class="kcmccsc_b"/><path class="b3dyhnb4w"/><path class="jc75hebpr"/><path fill="url(#i6SbPdd)" class="gwz1odbjl"/><path class="r6kqrwbmf"/><g filter="url(#imzWVsb)"><path class="l7yrcsbze"/><path fill="url(#iilzsec)" class="jxgtkcvqr"/></g><g filter="url(#iMjACxV)"><path fill="url(#iRjly7d)" class="rlkalhngp"/></g><path class="g-3azabpg"/><path fill="url(#iQFYBTc)" class="pnplx593l"/><path class="zodshii5h"/><g filter="url(#iH2T28c)"><path fill="url(#ibjGqbd)" class="a1wz-2bsd"/></g><g filter="url(#itfoWgb)"><ellipse transform="rotate(152.086 18.492 22.785)" class="b8w4g35pc"/><ellipse fill="url(#iTKZ2Jb)" transform="rotate(152.086 18.492 22.785)" class="su_pwqb0p"/></g><g filter="url(#i0FpbBW)"><path class="e4ht33bpe"/></g><g filter="url(#i53SRVd)"><path class="f5w68ubum"/></g><defs><radialGradient id="ilDfu2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.27734 1.55369 0 19.818 21.637)" gradientUnits="userSpaceOnUse"><stop offset=".376" class="w1hx-werx"/><stop offset="1" class="z_xcu_b7l"/></radialGradient><radialGradient id="iFG1gwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .17335 -.34548 -.77853 15.085 29.47)" gradientUnits="userSpaceOnUse"><stop class="doysnhfra"/><stop offset="1" class="oscuplh_u"/></radialGradient><radialGradient id="iEcNnCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48865 0 0 -3.771 15.486 28)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="af3iipb7l"/><stop offset="1" class="u1qs0bcso"/></radialGradient><radialGradient id="iI4Uxdc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91895 0 0 -4.67725 15.658 24.031)" gradientUnits="userSpaceOnUse"><stop offset=".414" class="luz57ccqc"/><stop offset="1" class="h2z1-164y"/></radialGradient><radialGradient id="iSDyUOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1 3.83881 0 14.07 30.031)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="m6im0jbte"/><stop offset="1" class="b8yz9bczm"/></radialGradient><radialGradient id="iFpAIDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.76709 .3344 0 13.63 25.98)" gradientUnits="userSpaceOnUse"><stop class="g2y28drll"/><stop offset="1" class="pzo1rmbpv"/></radialGradient><radialGradient id="ixTfUec" cx="0" cy="0" r="1" gradientTransform="matrix(-4.96875 0 0 -7.09375 20.718 18.344)" gradientUnits="userSpaceOnUse"><stop class="jk0wsqyqs"/><stop offset="1" class="d490xxnbe"/></radialGradient><radialGradient id="iSzRw8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 1.5 -.78696 .59022 20.655 19.25)" gradientUnits="userSpaceOnUse"><stop class="ht2yfkjwb"/><stop offset="1" class="bamjsvb8t"/></radialGradient><radialGradient id="icfMATg" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 -.9375 2.63274 2.01844 19.593 21.5)" gradientUnits="userSpaceOnUse"><stop class="h5k7xu51c"/><stop offset="1" class="ot3t6hbfc"/></radialGradient><radialGradient id="iZcOVBb" cx="0" cy="0" r="1" gradientTransform="rotate(-142.918 11.854 7.775)scale(1.68439 3.3263)" gradientUnits="userSpaceOnUse"><stop class="kcvv1loqd"/><stop offset="1" class="ngyzvbbds"/></radialGradient><radialGradient id="icCUqRd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 0 0 -4.625 13.051 12.49)" gradientUnits="userSpaceOnUse"><stop class="h-8qjbcjs"/><stop offset="1" class="dt5mbtt9q"/></radialGradient><radialGradient id="iU7laze" cx="0" cy="0" r="1" gradientTransform="rotate(132.58 14.64 7.66)scale(1.57029 1.5193)" gradientUnits="userSpaceOnUse"><stop class="qp90otrnq"/><stop offset="1" class="jbzjrkbhk"/></radialGradient><radialGradient id="iimnBpB" cx="0" cy="0" r="1" gradientTransform="rotate(78.283 -5.952 8.098)scale(2.15427 6.77116)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="bef5gkb7g"/><stop offset="1" class="c62vuxxso"/></radialGradient><radialGradient id="i6qnhpb" cx="0" cy="0" r="1" gradientTransform="matrix(.375 -.24959 .24959 .375 18.933 22.706)" gradientUnits="userSpaceOnUse"><stop class="ymrvqvuhk"/><stop offset="1" class="i1tglqbbv"/></radialGradient><radialGradient id="iIJfMqc" cx="0" cy="0" r="1" gradientTransform="matrix(1.72703 0 0 1.03774 14.516 22.457)" gradientUnits="userSpaceOnUse"><stop offset=".871" class="h3fjxrb3x"/><stop offset="1" class="tb1jhtb8l"/></radialGradient><radialGradient id="iIAVdgb" cx="0" cy="0" r="1" gradientTransform="rotate(59.94 -9.04 24.531)scale(5.81313 5.01362)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="z13dp2ohj"/><stop offset="1" class="thozw0bur"/></radialGradient><radialGradient id="imL8lpb" cx="0" cy="0" r="1" gradientTransform="rotate(150.21 6.885 12.642)scale(2.48457 1.07315)" gradientUnits="userSpaceOnUse"><stop class="bhz2sgb0b"/><stop offset="1" class="i6xzgnbvo"/></radialGradient><radialGradient id="iMB7j2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92188 -.9624 0 18.407 23.02)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="i9i7w6byf"/><stop offset="1" class="phweo5b4d"/></radialGradient><radialGradient id="ip0vi6H" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83361 -.91553 0 18.36 22.562)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="as64zyjca"/><stop offset="1" class="plu4nhehf"/></radialGradient><radialGradient id="imHeUlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.22154 6.55447 0 17.445 24.828)" gradientUnits="userSpaceOnUse"><stop class="xot457bvg"/><stop offset="1" class="bvx6ww5kn"/></radialGradient><radialGradient id="i3KntJT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.41199 9.70332 0 17.445 23.17)" gradientUnits="userSpaceOnUse"><stop offset=".907" class="v2b10k5bd"/><stop offset="1" class="y_k4s4ber"/></radialGradient><radialGradient id="idv6R7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1572 8.77576 0 17.457 26.083)" gradientUnits="userSpaceOnUse"><stop class="j1jfcebla"/><stop offset=".29" class="quyrl8b2j"/></radialGradient><radialGradient id="iemyitb" cx="0" cy="0" r="1" gradientTransform="matrix(1.95312 .4974 -.77925 3.0599 14.36 23.89)" gradientUnits="userSpaceOnUse"><stop offset=".474" class="ktzs-abxm"/><stop offset="1" class="f-v3r2bzo"/></radialGradient><radialGradient id="imQvJqy" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1106 .31016 -.1357 -.92338 18.891 24.75)" gradientUnits="userSpaceOnUse"><stop class="af37fl8_e"/><stop offset="1" class="bpitud03n"/></radialGradient><radialGradient id="i3jYsdf" cx="0" cy="0" r="1" gradientTransform="matrix(-.47859 0 0 -.14492 17.77 21.71)" gradientUnits="userSpaceOnUse"><stop class="qazm7n4dy"/><stop offset="1" class="b-vvinijr"/></radialGradient><radialGradient id="i6SbPdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34198 .54395 0 16.538 22.744)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iilzsec" cx="0" cy="0" r="1" gradientTransform="matrix(.09775 .12597 -.17343 .13458 16.634 22.71)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQFYBTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.342 .54398 0 18.378 22.744)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iTKZ2Jb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 20.524 2.36)scale(.20829 .25036)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="icVjLde" width="2.064" height="2.201" x="25.478" y="24.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.709804 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="i2P8Nhc" width="2.069" height="2.206" x="25.515" y="25.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="iNcCFoe" width="2.069" height="2.206" x="25.515" y="25.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.709804 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="iAIcJXb" width="1.801" height="1.929" x="25.239" y="25.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.709804 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="iD9fNNc" width="1.405" height="1.524" x="24.915" y="26.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.690196 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="i7D7zge" width="8.77" height="8.383" x="13.223" y="13.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.647059 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="iQVEZgM" width="7.329" height="7.242" x="20.747" y="3.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.580392 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="i522pjd" width="4.79" height="2.813" x="25.665" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="iRsUX3c" width="5.938" height="6.795" x="21.027" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".15"/></filter><filter id="i4cjpWc" width="10.596" height="6.162" x="12.56" y="8.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="idlWqJb" width="1.039" height="1.039" x="18.939" y="21.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".05"/></filter><filter id="i5gTZtc" width="1.039" height="1.039" x="14.928" y="21.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".05"/></filter><filter id="iPpTUqt" width="2.99" height="2.493" x="14.58" y="22.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".3"/></filter><filter id="iBw5Yjc" width="5.313" height="3.491" x="14.8" y="22.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.768627 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23565"/></filter><filter id="inFxPwz" width=".991" height="1.33" x="16.961" y="21.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".05"/></filter><filter id="irknRRG" width="2.157" height="1.252" x="16.378" y="20.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".1"/></filter><filter id="imzWVsb" width=".447" height=".409" x="16.458" y="22.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".05"/></filter><filter id="iMjACxV" width=".607" height=".616" x="16.002" y="22.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".1"/></filter><filter id="iH2T28c" width=".647" height=".67" x="17.835" y="22.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".1"/></filter><filter id="itfoWgb" width=".501" height=".413" x="18.242" y="22.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".05"/></filter><filter id="i0FpbBW" width="1.08" height=".482" x="15.827" y="23.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".05"/></filter><filter id="i53SRVd" width="1.113" height=".506" x="17.995" y="23.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23565" stdDeviation=".05"/></filter><linearGradient id="iTJgSmk" x1="26.276" x2="25.725" y1="27.951" y2="27.951" gradientUnits="userSpaceOnUse"><stop class="yfo8mbafu"/><stop offset="1" class="odx_qpbix"/></linearGradient><linearGradient id="i1V7HGd" x1=".196" x2=".225" y1=".545" y2="1.154" gradientUnits="userSpaceOnUse"><stop offset=".202" class="gxpb7nbxb"/><stop offset="1" class="s5e5y9bme"/></linearGradient><linearGradient id="ivhuhgb" x1=".201" x2=".188" y1=".545" y2="1.014" gradientUnits="userSpaceOnUse"><stop offset=".255" class="jbqcexb-p"/><stop offset="1" class="le3x4zbvz"/></linearGradient><linearGradient id="iGMX5Qd" x1=".201" x2=".229" y1=".545" y2="1.154" gradientUnits="userSpaceOnUse"><stop offset=".202" class="gxpb7nbxb"/><stop offset="1" class="s5e5y9bme"/></linearGradient><linearGradient id="ij2vdrb" x1=".211" x2=".23" y1=".458" y2=".971" gradientUnits="userSpaceOnUse"><stop offset=".202" class="gxpb7nbxb"/><stop offset="1" class="s5e5y9bme"/></linearGradient><linearGradient id="iIcHDqc" x1="26.515" x2="29.141" y1="28.219" y2="28.432" gradientUnits="userSpaceOnUse"><stop offset=".144" class="xprlfobqo"/><stop offset="1" class="mvtg61z_l"/></linearGradient><linearGradient id="i2CCi4b" x1="29.042" x2="27.833" y1="28.758" y2="28.672" gradientUnits="userSpaceOnUse"><stop class="otqbr1aet"/><stop offset="1" class="zidg67b5j"/></linearGradient><linearGradient id="i4acwCe" x1="14.03" x2="18.843" y1="13.438" y2="15.094" gradientUnits="userSpaceOnUse"><stop offset=".288" class="gesenab-k"/><stop offset="1" class="kscf9stoz"/></linearGradient><linearGradient id="idfIiWc" x1="8.962" x2="8.962" y1="14.039" y2="12.521" gradientUnits="userSpaceOnUse"><stop class="nby3hzz_p"/><stop offset="1" class="qa5zo59bk"/></linearGradient><linearGradient id="iJvjhqL" x1="8.114" x2="8.192" y1="11.833" y2="12.349" gradientUnits="userSpaceOnUse"><stop class="uuem7raxu"/><stop offset="1" class="mnvbp908z"/></linearGradient><linearGradient id="ilxSKgd" x1="27.436" x2="27.436" y1="2.063" y2="2.211" gradientUnits="userSpaceOnUse"><stop class="su56_nrsk"/><stop offset="1" class="wrxtldewy"/></linearGradient><linearGradient id="iMhVatp" x1="25.915" x2="26.592" y1="2.531" y2="2.531" gradientUnits="userSpaceOnUse"><stop class="gt57qko1f"/><stop offset="1" class="mak5wnjve"/></linearGradient><linearGradient id="iFAQRBf" x1="5.468" x2="4.811" y1="11.813" y2="12.391" gradientUnits="userSpaceOnUse"><stop class="d3k6isbnm"/><stop offset="1" class="mi7m9xbsl"/></linearGradient><linearGradient id="iAk3Tac" x1="3.1" x2="3.257" y1="12.578" y2="12.766" gradientUnits="userSpaceOnUse"><stop offset=".07" class="kfgxjwb7e"/><stop offset="1" class="gzc8sbczu"/></linearGradient><linearGradient id="iuxv2xc" x1="12.876" x2="13.345" y1="14.469" y2="11.781" gradientUnits="userSpaceOnUse"><stop offset=".264" class="kswhxtfcb"/><stop offset="1" class="cj3zw_ajv"/></linearGradient><linearGradient id="ihiEgZR" x1="21.72" x2="20.845" y1="12.875" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="a3l5-0b9h"/><stop offset="1" class="b3vardzds"/></linearGradient><linearGradient id="iozR42b" x1="17.757" x2="17.22" y1="22.131" y2="22.131" gradientUnits="userSpaceOnUse"><stop class="rtexe3k4n"/><stop offset="1" class="d-j1vhb3x"/></linearGradient><linearGradient id="i0M5Lhb" x1="18.135" x2="17.75" y1="20.831" y2="21.192" gradientUnits="userSpaceOnUse"><stop class="w_ut_9kmd"/><stop offset="1" class="o-dz8077k"/></linearGradient><linearGradient id="iRjly7d" x1="16.21" x2="16.342" y1="22.722" y2="22.64" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibjGqbd" x1="18.064" x2="18.196" y1="22.722" y2="22.64" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-cartwheeling-medium-light" /></template>
<style>
.a1wz-2bsd {
  d: path("M18.035 22.614c0 .121.099.202.125.227l.122-.118l-.075-.152z");
}

.a3l5-0b9h {
  stop-color: var(--svg-color--9d94a4, #9D94A4);
}

.a6h5ccbnr {
  d: path("m27.548 4.375l-1.633-.773v-1.29a.25.25 0 0 1 .25-.25h3.972c.151 0 .3.086.315.237c.026.281-.125.62-.6.951c-.542.352-1.699.844-2.304 1.125");
}

.af37fl8_e {
  stop-color: var(--svg-color--ffe8bd, #FFE8BD);
}

.af3iipb7l {
  stop-color: var(--svg-color--e9b39f, #E9B39F);
}

.as64zyjca {
  stop-color: var(--svg-color--edab95, #EDAB95);
}

.b_028jvwm {
  width: 0.699px;
  height: 2.521px;
  rx: 0.349px;
}

.b-vvinijr {
  stop-color: var(--svg-color--eab690, #EAB690);
  stop-opacity: 0;
}

.b3dyhnb4w {
  fill: var(--svg-color--945e31, #945E31);
  d: path("m15.889 23.604l.003.002l.005.004l.015.012l.05.034a1.2 1.2 0 0 0 .806.156a.225.225 0 1 0-.07-.445a.74.74 0 0 1-.497-.093l-.023-.015l-.004-.003a.225.225 0 0 0-.285.348m3.159 0l-.003.002l-.005.004a.4.4 0 0 1-.065.046a1.2 1.2 0 0 1-.806.156a.225.225 0 0 1 .07-.445a.74.74 0 0 0 .497-.093l.023-.015l.004-.003a.225.225 0 0 1 .286.348");
}

.b3vardzds {
  stop-color: var(--svg-color--9d94a4, #9D94A4);
  stop-opacity: 0;
}

.b8w4g35pc {
  cx: 18.492px;
  cy: 22.785px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.164px;
  ry: 0.083px;
}

.b8yz9bczm {
  stop-color: var(--svg-color--d89a94, #D89A94);
  stop-opacity: 0;
}

.bamjsvb8t {
  stop-color: var(--svg-color--50c7ff, #50C7FF);
  stop-opacity: 0;
}

.bef5gkb7g {
  stop-color: var(--svg-color--403178, #403178);
  stop-opacity: 0;
}

.bhz2sgb0b {
  stop-color: var(--svg-color--ffd1aa, #FFD1AA);
}

.ble7gfbfv {
  d: path("m15.425 25.188l-.18-.09a.83.83 0 0 1-.43-.9l.248-1.281c.022-.133.11-.222.241-.225h.008s-.022.382-.045.607c-.018.183.013.239.18.405a.53.53 0 0 1 .16.36v.36c0 .112.09.202.18.224c.271.068.837.18 1.65.18c.815 0 1.38-.112 1.652-.18a.22.22 0 0 0 .18-.224v-.36c0-.135.046-.27.159-.36l.068-.067c.09-.068.136-.203.136-.315a27 27 0 0 1-.046-.607h.02c.127.009.23.096.252.224l.248 1.282a.86.86 0 0 1-.452.877l-.18.09c-.114.067-.227.157-.34.247l-.407.428a.83.83 0 0 1-.927.134a1.24 1.24 0 0 0-.701 0c-.34.113-.724.023-.995-.224l-.34-.338a.95.95 0 0 0-.339-.247");
}

.bpitud03n {
  stop-color: var(--svg-color--ffe8bd, #FFE8BD);
  stop-opacity: 0;
}

.bvx6ww5kn {
  stop-color: var(--svg-color--dc9d91, #DC9D91);
  stop-opacity: 0;
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

.d-j1vhb3x {
  stop-color: var(--svg-color--dba483, #DBA483);
}

.d3k6isbnm {
  stop-color: var(--svg-color--686897, #686897);
}

.d490xxnbe {
  stop-color: var(--svg-color--33a2f1, #33A2F1);
}

.d7t5c3bcg {
  d: path("M26.633 25.336h2.014v7.07h-2.014z");
}

.doysnhfra {
  stop-color: var(--svg-color--e2a788, #E2A788);
}

.dt5mbtt9q {
  stop-color: var(--svg-color--d2a38f, #D2A38F);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4ht33bpe {
  stroke: var(--svg-color--9e683f, #9E683F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.757 23.665c-.182.031-.535.022-.78-.168");
}

.er2rr_b4h {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m16.79 21.188l-.084-.056a.16.16 0 0 0 .018.2a.165.165 0 0 0 .194.033h.001a1.16 1.16 0 0 1 .538-.128c.198 0 .383.047.537.127h.001c.074.038.15.014.195-.033a.16.16 0 0 0 .017-.2a.9.9 0 0 0-.75-.4a.9.9 0 0 0-.751.402zm0 0a.8.8 0 0 1 .667-.357c.28 0 .526.143.667.357c.037.052-.025.117-.083.088a1.3 1.3 0 0 0-.584-.139c-.216 0-.415.05-.584.139c-.058.03-.12-.034-.084-.088Z");
}

.ezd15ek3s {
  d: path("m17.618 22.577l.224-.716a.227.227 0 0 0-.22-.295h-.331a.228.228 0 0 0-.22.295l.224.716c.048.159.272.159.323 0");
}

.f-v3r2bzo {
  stop-color: var(--svg-color--ffcda2, #FFCDA2);
  stop-opacity: 0;
}

.f49ru9mwd {
  cx: 19.458px;
  cy: 22.457px;
  r: 0.419px;
  fill: var(--svg-color--dfa37e, #DFA37E);
}

.f5w68ubum {
  stroke: var(--svg-color--9e683f, #9E683F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.957 23.446c-.138.122-.439.25-.812.19");
}

.ft5dv1b6b {
  fill: none;
}

.g-3azabpg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.466 23.06c.275 0 .508-.19.57-.446a.116.116 0 0 0-.112-.144h-.94a.097.097 0 0 0-.096.115a.59.59 0 0 0 .578.475");
}

.g1x3feakc {
  width: 0.699px;
  height: 2.521px;
  fill: var(--svg-color--d6998c, #D6998C);
  rx: 0.349px;
}

.g2y28drll {
  stop-color: var(--svg-color--ecb094, #ECB094);
}

.ga3uz0zmk {
  fill: var(--svg-color--deaf8d, #DEAF8D);
  d: path("m12.767 14.04l-7.61-.142l.625-1.57l6.844-.984z");
}

.gesenab-k {
  stop-color: var(--svg-color--3280d1, #3280D1);
}

.gjxr99ebn {
  d: path("M4.698 11.294a.25.25 0 0 1 .346.027l.875.984l-.734 1.59l-1.176.336c-.305.099-1.059.302-1.637.324a.89.89 0 0 1-.778-.37c-.092-.123-.047-.29.072-.389z");
}

.gr0xwfbsq {
  d: path("M18.655 20.195h2.326v1.781h-2.326z");
}

.gt57qko1f {
  stop-color: var(--svg-color--5f5e7a, #5F5E7A);
}

.gwz1odbjl {
  d: path("M16.537 22.946a.376.376 0 0 1-.362-.476h.726a.378.378 0 0 1-.364.475");
}

.gxpb7nbxb {
  stop-color: var(--svg-color--f4c1a4, #F4C1A4);
}

.gzc8sbczu {
  stop-color: var(--svg-color--424272, #424272);
  stop-opacity: 0;
}

.h-8qjbcjs {
  stop-color: var(--svg-color--bf8c7c, #BF8C7C);
}

.h2z1-164y {
  stop-color: var(--svg-color--cf9183, #CF9183);
  stop-opacity: 0;
}

.h3fjxrb3x {
  stop-color: var(--svg-color--c98972, #C98972);
}

.h5k7xu51c {
  stop-color: var(--svg-color--487fd0, #487FD0);
}

.hebxnubow {
  width: 0.737px;
  height: 2.121px;
  rx: 0.368px;
}

.ht2yfkjwb {
  stop-color: var(--svg-color--5dd2ff, #5DD2FF);
}

.i1tglqbbv {
  stop-color: var(--svg-color--e6b593, #E6B593);
}

.i6xzgnbvo {
  stop-color: var(--svg-color--ffcba8, #FFCBA8);
  stop-opacity: 0;
}

.i9i7w6byf {
  stop-color: var(--svg-color--ffc89f, #FFC89F);
}

.ivpdgybcg {
  cx: 19.459px;
  cy: 22.457px;
  r: 0.704px;
}

.j1jfcebla {
  stop-color: var(--svg-color--ddafa9, #DDAFA9);
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

.jc75hebpr {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.45 23.06a.59.59 0 0 1-.571-.446a.116.116 0 0 1 .113-.144h.94c.06 0 .108.055.096.115a.59.59 0 0 1-.578.475");
}

.jk0wsqyqs {
  stop-color: var(--svg-color--4cbfff, #4CBFFF);
}

.jxgtkcvqr {
  d: path("M16.565 22.866c-.027-.036.03-.08.093-.127c.064-.048.11-.081.138-.045c.027.036-.003.103-.067.15c-.064.048-.137.058-.164.022");
}

.kcmccsc_b {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M17.457 21.137c.214 0 .415.05.584.139c.058.03.12-.036.083-.088a.8.8 0 0 0-.667-.357a.8.8 0 0 0-.668.357c-.036.054.026.117.084.088a1.26 1.26 0 0 1 .584-.139");
}

.kcvv1loqd {
  stop-color: var(--svg-color--2874ab, #2874AB);
}

.kfgxjwb7e {
  stop-color: var(--svg-color--424272, #424272);
}

.kscf9stoz {
  stop-color: var(--svg-color--309fea, #309FEA);
  stop-opacity: 0;
}

.kswhxtfcb {
  stop-color: var(--svg-color--836591, #836591);
}

.ktzs-abxm {
  stop-color: var(--svg-color--ffcda2, #FFCDA2);
}

.kx-bcespw {
  d: path("M14.82 29.85c-.296.03-.955.087-1.58.087c-.653 0-.73-.345-.731-.519c-.01-.115.056-.368.39-.465c.121-.035.26-.072.397-.108a.2.2 0 0 0 .15-.194v-6.628h2.04v7.129a.7.7 0 0 1-.564.686l.001.002l-.025.003z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7yrcsbze {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.565 22.866c-.027-.036.03-.08.093-.127c.064-.048.11-.081.138-.045c.027.036-.003.103-.067.15c-.064.048-.137.058-.164.022");
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

.luz57ccqc {
  stop-color: var(--svg-color--c3816a, #C3816A);
}

.lxwna7htg {
  width: 1.121px;
  height: 0.563px;
  x: 13.888px;
  y: 29.188px;
  rx: 0.281px;
}

.lyb5hkpdy {
  stroke: var(--svg-color--dbad95, #DBAD95);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m26.551 4.229l-5.11 6");
}

.m1lhgybcq {
  width: 0.684px;
  height: 2.521px;
  fill: var(--svg-color--d6998c, #D6998C);
  rx: 0.342px;
}

.m546nebir {
  d: path("M20.693 18.206c.526.664 1.057 1.569 1.3 2.278l-1.578 1.43l-1.82-1.43l-.826-1.669a.3.3 0 0 0-.534-.006l-1.695 3.214h-2.117c.084-1.569.551-3.03.88-3.75c.07-.15.112-.313.112-.48v-4.152h6.188v4.309c0 .093.032.183.09.256");
}

.m6im0jbte {
  stop-color: var(--svg-color--c37d93, #C37D93);
}

.m6xg0iv-q {
  fill: var(--svg-color--d9a893, #D9A893);
  d: path("m23.118 10.59l4.458-6.244l-1.635-.748l-5.194 4.836z");
}

.mak5wnjve {
  stop-color: var(--svg-color--41406b, #41406B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mi7m9xbsl {
  stop-color: var(--svg-color--514f87, #514F87);
}

.mjq3nac3p {
  width: 0.665px;
  height: 1.584px;
  fill: var(--svg-color--d99d8e, #D99D8E);
  rx: 0.332px;
}

.mnvbp908z {
  stop-color: var(--svg-color--dcae8c, #DCAE8C);
  stop-opacity: 0;
}

.mvtg61z_l {
  stop-color: var(--svg-color--dc9b8a, #DC9B8A);
}

.n52mgrb1s {
  opacity: var(--svg-opacity--0-4, 0.4);
}

.nby3hzz_p {
  stop-color: var(--svg-color--b8797f, #B8797F);
}

.ngyzvbbds {
  stop-color: var(--svg-color--3293c7, #3293C7);
  stop-opacity: 0;
}

.nzwnzr7pk {
  cx: 15.447px;
  cy: 22.457px;
  r: 0.704px;
}

.o-dz8077k {
  stop-color: var(--svg-color--f0b294, #F0B294);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odx_qpbix {
  stop-color: var(--svg-color--c98579, #C98579);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.ot3t6hbfc {
  stop-color: var(--svg-color--34a4e5, #34A4E5);
  stop-opacity: 0;
}

.otqbr1aet {
  stop-color: var(--svg-color--cf8880, #CF8880);
}

.p-vlvd2fc {
  fill: var(--svg-color--dca08b, #DCA08B);
  d: path("M14.82 29.85c-.296.03-.955.087-1.58.087c-.653 0-.73-.345-.731-.519c-.01-.115.056-.368.39-.465c.121-.035.26-.072.397-.108a.2.2 0 0 0 .15-.194v-6.628h2.04v7.129a.7.7 0 0 1-.564.686l.001.002l-.025.003z");
}

.p7em5jbop {
  d: path("M19.607 22.715h-.02s.022.36.045.607c0 .112-.046.247-.136.314l-.068.068a.45.45 0 0 0-.158.36v.36a.22.22 0 0 1-.181.224c-.271.068-.837.18-1.651.18s-1.38-.112-1.65-.18a.24.24 0 0 1-.182-.225v-.36a.53.53 0 0 0-.158-.36c-.212-.148-.199-.23-.181-.404c.023-.225.045-.607.045-.607h-.007l.112-1.669c.067-.746.654-1.266 1.353-1.266h1.354c.722 0 1.286.52 1.353 1.266z");
}

.phweo5b4d {
  stop-color: var(--svg-color--ffc89f, #FFC89F);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plu4nhehf {
  stop-color: var(--svg-color--edab95, #EDAB95);
  stop-opacity: 0;
}

.pnplx593l {
  d: path("M18.378 22.946a.376.376 0 0 0 .363-.476h-.727a.38.38 0 0 0 .364.475");
}

.pzo1rmbpv {
  stop-color: var(--svg-color--ecb094, #ECB094);
  stop-opacity: 0;
}

.qa5zo59bk {
  stop-color: var(--svg-color--dba391, #DBA391);
  stop-opacity: 0;
}

.qazm7n4dy {
  stop-color: var(--svg-color--ffd1ad, #FFD1AD);
}

.qh_qstsih {
  fill: var(--svg-color--e7ab8e, #E7AB8E);
  d: path("m15.37 24.828l1.298-.432a.442.442 0 0 0-.198-.857l-1.29.173z");
}

.qm9kvjbbx {
  fill: var(--svg-color--a59dae, #A59DAE);
  d: path("m20.615 14.064l2.542-3.495L20.783 8.4c-.14.134-.505.492-.84.85c-1.188 1.15-2.767 1.43-3.776 1.58l-3.607.495v2.737z");
}

.qp90otrnq {
  stop-color: var(--svg-color--686995, #686995);
}

.quyrl8b2j {
  stop-color: var(--svg-color--fac9a2, #FAC9A2);
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

.r6kqrwbmf {
  fill: var(--svg-color--000, #000);
  d: path("M16.753 22.57a.215.215 0 0 1-.216.215a.215.215 0 0 1-.191-.315h.381q.026.045.026.1");
}

.rlkalhngp {
  d: path("M16.202 22.619a.35.35 0 0 0 .098.195l.11-.12l-.05-.096z");
}

.rtexe3k4n {
  stop-color: var(--svg-color--e0a394, #E0A394);
}

.s5e5y9bme {
  stop-color: var(--svg-color--e3ac95, #E3AC95);
  stop-opacity: 0;
}

.su_pwqb0p {
  cx: 18.492px;
  cy: 22.785px;
  rx: 0.164px;
  ry: 0.083px;
}

.su56_nrsk {
  stop-color: var(--svg-color--444570, #444570);
}

.tb1jhtb8l {
  stop-color: var(--svg-color--d89d88, #D89D88);
}

.thozw0bur {
  stop-color: var(--svg-color--f6bb9f, #F6BB9F);
}

.u1qs0bcso {
  stop-color: var(--svg-color--dda18c, #DDA18C);
  stop-opacity: 0;
}

.uib5ptygi {
  width: 0.809px;
  height: 1.648px;
  x: 25.404px;
  y: 27.272px;
  rx: 0.404px;
}

.uuem7raxu {
  stop-color: var(--svg-color--c1997b, #C1997B);
}

.v1g1kqbgg {
  fill: var(--svg-color--504e84, #504E84);
  d: path("m27.548 4.375l-1.633-.773v-1.29a.25.25 0 0 1 .25-.25h3.972c.151 0 .3.086.315.237c.026.281-.125.62-.6.951c-.542.352-1.699.844-2.304 1.125");
}

.v2b10k5bd {
  stop-color: var(--svg-color--d9b196, #D9B196);
  stop-opacity: 0;
}

.v9pgtobbi {
  cx: 15.447px;
  cy: 22.457px;
  r: 0.419px;
  fill: var(--svg-color--c07e5e, #C07E5E);
}

.w_ut_9kmd {
  stop-color: var(--svg-color--f0b294, #F0B294);
}

.w1hx-werx {
  stop-color: var(--svg-color--cc997f, #CC997F);
}

.wrxtldewy {
  stop-color: var(--svg-color--444570, #444570);
  stop-opacity: 0;
}

.xot457bvg {
  stop-color: var(--svg-color--dc9d91, #DC9D91);
}

.xprlfobqo {
  stop-color: var(--svg-color--f8c8a9, #F8C8A9);
}

.y_k4s4ber {
  stop-color: var(--svg-color--d9b196, #D9B196);
}

.y1s6k-s_j {
  width: 0.737px;
  height: 2.121px;
  fill: var(--svg-color--d6998c, #D6998C);
  rx: 0.368px;
}

.yfo8mbafu {
  stop-color: var(--svg-color--dc9c8a, #DC9C8A);
}

.ymrvqvuhk {
  stop-color: var(--svg-color--edba9d, #EDBA9D);
}

.z_xcu_b7l {
  stop-color: var(--svg-color--d39e7c, #D39E7C);
}

.z13dp2ohj {
  stop-color: var(--svg-color--e1ac8b, #E1AC8B);
}

.zidg67b5j {
  stop-color: var(--svg-color--d89382, #D89382);
  stop-opacity: 0;
}

.znagombkh {
  d: path("m20.615 14.064l2.542-3.495L20.783 8.4c-.14.134-.505.492-.84.85c-1.188 1.15-2.767 1.43-3.776 1.58l-3.607.495v2.737z");
}

.zodshii5h {
  fill: var(--svg-color--000, #000);
  d: path("M18.163 22.57c0 .119.096.215.215.215a.215.215 0 0 0 .192-.315h-.381a.2.2 0 0 0-.026.1");
}

</style>
