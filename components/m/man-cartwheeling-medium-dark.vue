<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iEScWPc)" transform="rotate(-180 25.404 27.272)" class="uib5ptygi"/><g filter="url(#iKmVjoc)"><rect transform="scale(-1 1)rotate(44.184 -43.275 -19.634)" class="s_txeqb5u"/><rect fill="url(#iCAMPGd)" transform="scale(-1 1)rotate(44.184 -43.275 -19.634)" class="j6w3anb3u"/></g><g filter="url(#iyA31Kb)"><rect transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="qzk34pbjf"/><rect fill="url(#ivhuhgb)" transform="scale(-1 1)rotate(44.184 -43.885 -19.45)" class="b_028jvwm"/></g><g filter="url(#iibyTrd)"><rect transform="scale(-1 1)rotate(44.184 -44.184 -18.961)" class="r96i785dr"/><rect fill="url(#iX8Qwud)" transform="scale(-1 1)rotate(44.184 -44.184 -18.961)" class="hebxnubow"/></g><g filter="url(#ifzWymb)"><rect transform="scale(-1 1)rotate(44.184 -44.651 -18.254)" class="h91tgxbdh"/></g><path fill="url(#id8fUTd)" transform="rotate(135.816 26.633 25.336)" class="d7t5c3bcg"/><path fill="url(#iDqQddd)" transform="rotate(135.816 26.633 25.336)" class="d7t5c3bcg"/><path fill="url(#iaz4Zxj)" transform="rotate(-180 18.655 20.195)" class="gr0xwfbsq"/><rect fill="url(#i9rlPqj)" transform="rotate(-180 13.888 29.188)" class="lxwna7htg"/><path class="na5ps0b6u"/><path fill="url(#ixq2wMc)" class="kx-bcespw"/><path fill="url(#i9aGk3K)" class="kx-bcespw"/><path fill="url(#i6s7Fre)" class="kx-bcespw"/><path fill="url(#iFT1ARc)" class="kx-bcespw"/><g filter="url(#iUxRjWb)"><path fill="url(#ixTfUec)" class="m546nebir"/><path fill="url(#iSzRw8b)" class="m546nebir"/><path fill="url(#icfMATg)" class="m546nebir"/><path fill="url(#i4acwCe)" class="m546nebir"/><path fill="url(#iZcOVBb)" class="m546nebir"/></g><path class="equhh1t5g"/><path fill="url(#iNgO3ue)" class="li6veqsxp"/><path fill="url(#i5V8ece)" class="li6veqsxp"/><path fill="url(#isr2aip)" class="li6veqsxp"/><g filter="url(#iqjNo0b)"><path class="caog4u2we"/></g><g filter="url(#icU82id)"><path class="v1g1kqbgg"/><path fill="url(#iU7laze)" class="a6h5ccbnr"/></g><path fill="url(#ilxSKgd)" class="a6h5ccbnr"/><path fill="url(#iMhVatp)" class="a6h5ccbnr"/><g filter="url(#iVtA8Me)" class="n52mgrb1s"><path class="mt_0cpx2h"/></g><path fill="url(#iqIEnAK)" class="nv7x83egt"/><path fill="url(#iAk3Tac)" class="nv7x83egt"/><path fill="url(#iimnBpB)" class="nv7x83egt"/><g filter="url(#iIa4bDb)"><path class="qm9kvjbbx"/><path fill="url(#iuxv2xc)" class="znagombkh"/><path fill="url(#ihiEgZR)" class="znagombkh"/></g><circle transform="rotate(-180 19.459 22.447)" class="o1qljk8ih"/><circle fill="url(#iBEL3de)" transform="rotate(-180 19.459 22.447)" class="jmqoa7beg"/><g filter="url(#iActVmc)"><circle transform="rotate(-180 19.458 22.447)" class="emxgosifs"/></g><circle fill="url(#iWnOM0b)" transform="rotate(-180 15.447 22.447)" class="jmj4yzb8d"/><g filter="url(#iVx2ZVd)"><circle transform="rotate(-180 15.447 22.447)" class="bxoiu5bus"/></g><path fill="url(#iQnnZpb)" class="fh46qfkzu"/><path fill="url(#i1PNBdE)" class="fh46qfkzu"/><path fill="url(#ivE2Vpe)" class="fh46qfkzu"/><path fill="url(#ijvwFZc)" class="fh46qfkzu"/><g filter="url(#iGxXfBb)"><path fill="url(#ifErokc)" class="gun13-b-l"/></g><g filter="url(#i3Z1ngd)"><path class="uipvgs40m"/><path fill="url(#i3Z4Kce)" class="qb80pcc1k"/><path fill="url(#it7l3Ne)" class="qb80pcc1k"/></g><g filter="url(#iahXSsd)"><path fill="url(#iEI5jze)" class="ddhy2b65m"/><path fill="url(#ieWIZqc)" class="ddhy2b65m"/></g><path class="yhnzr0bpw"/><path class="y-_otsbxx"/><path class="z399-vbiq"/><path fill="url(#iTIcr0b)" class="dotuh9bef"/><path class="wzq5d1gmc"/><g filter="url(#iuLyYLc)"><path class="lgjuvnbhi"/><path fill="url(#iyW7eAd)" class="t8a7styqg"/></g><g filter="url(#iR3flUc)"><path fill="url(#iDdO32j)" class="lhxavd33y"/></g><path class="az7cnskom"/><path fill="url(#iAN1SxC)" class="qqc_3qb_f"/><path class="atsylmdpa"/><g filter="url(#icJSGOP)"><path fill="url(#iA9QPXc)" class="umqxld3tj"/></g><g filter="url(#i03xJHd)"><ellipse transform="rotate(152.086 18.492 22.774)" class="md7ne1b7k"/><ellipse fill="url(#iaEaMIe)" transform="rotate(152.086 18.492 22.774)" class="emj-kwbhr"/></g><g filter="url(#i6ZeXjc)"><path class="cusk6jb7f"/></g><g filter="url(#icBt6xd)"><path class="w7g1j2ber"/></g><g filter="url(#ixa6gvd)"><path stroke="url(#it7oiQd)" class="rg-wm7esh"/></g><defs><radialGradient id="iaz4Zxj" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .61719 -.75071 1.4064 19.293 20.633)" gradientUnits="userSpaceOnUse"><stop class="h2ug0z0zy"/><stop offset="1" class="nqe9_3xqo"/></radialGradient><radialGradient id="i9rlPqj" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .17335 -.34548 -.77853 15.085 29.47)" gradientUnits="userSpaceOnUse"><stop class="w3mc4qk1n"/><stop offset="1" class="ol2abdblh"/></radialGradient><radialGradient id="ixq2wMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48865 0 0 -3.771 15.486 28)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="k2wpap9_u"/><stop offset="1" class="de3gtwbql"/></radialGradient><radialGradient id="i9aGk3K" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91895 0 0 -4.67725 15.658 24.031)" gradientUnits="userSpaceOnUse"><stop offset=".414" class="bltptbchx"/><stop offset="1" class="ghbrfbb8g"/></radialGradient><radialGradient id="i6s7Fre" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1 3.83881 0 14.07 30.031)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="bbk20sbrs"/><stop offset="1" class="s8mikn8pw"/></radialGradient><radialGradient id="iFT1ARc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.76709 .3344 0 13.63 25.98)" gradientUnits="userSpaceOnUse"><stop class="v3a4xqbpf"/><stop offset="1" class="br6wf4dup"/></radialGradient><radialGradient id="ixTfUec" cx="0" cy="0" r="1" gradientTransform="matrix(-4.96875 0 0 -7.09375 20.718 18.344)" gradientUnits="userSpaceOnUse"><stop class="jk0wsqyqs"/><stop offset="1" class="d490xxnbe"/></radialGradient><radialGradient id="iSzRw8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 1.5 -.78696 .59022 20.655 19.25)" gradientUnits="userSpaceOnUse"><stop class="ht2yfkjwb"/><stop offset="1" class="bamjsvb8t"/></radialGradient><radialGradient id="icfMATg" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 -.9375 2.63274 2.01844 19.593 21.5)" gradientUnits="userSpaceOnUse"><stop class="h5k7xu51c"/><stop offset="1" class="ot3t6hbfc"/></radialGradient><radialGradient id="iZcOVBb" cx="0" cy="0" r="1" gradientTransform="rotate(-142.918 11.854 7.775)scale(1.68439 3.3263)" gradientUnits="userSpaceOnUse"><stop class="kcvv1loqd"/><stop offset="1" class="ngyzvbbds"/></radialGradient><radialGradient id="i5V8ece" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 0 0 -4.625 13.051 12.49)" gradientUnits="userSpaceOnUse"><stop class="e_oa-tb8l"/><stop offset="1" class="bo50hoaxz"/></radialGradient><radialGradient id="iU7laze" cx="0" cy="0" r="1" gradientTransform="rotate(132.58 14.64 7.66)scale(1.57029 1.5193)" gradientUnits="userSpaceOnUse"><stop class="qp90otrnq"/><stop offset="1" class="jbzjrkbhk"/></radialGradient><radialGradient id="iimnBpB" cx="0" cy="0" r="1" gradientTransform="rotate(78.283 -5.952 8.098)scale(2.15427 6.77116)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="bef5gkb7g"/><stop offset="1" class="c62vuxxso"/></radialGradient><radialGradient id="iBEL3de" cx="0" cy="0" r="1" gradientTransform="rotate(133.39 5.428 15.471)scale(1.37053 1.79926)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="flq8uy9_y"/><stop offset=".887" class="r66150hyt"/></radialGradient><radialGradient id="iWnOM0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.72703 0 0 .91697 14.516 22.447)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="z2p55f_ys"/><stop offset="1" class="wnz4hcbxb"/></radialGradient><radialGradient id="iQnnZpb" cx="0" cy="0" r="1" gradientTransform="rotate(59.94 -9.031 24.526)scale(5.81313 5.01362)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="yi2txbcnj"/><stop offset="1" class="kchp3yc8t"/></radialGradient><radialGradient id="i1PNBdE" cx="0" cy="0" r="1" gradientTransform="rotate(150.21 6.887 12.637)scale(2.48457 1.07315)" gradientUnits="userSpaceOnUse"><stop class="tgvr64d-a"/><stop offset="1" class="gid_9j_gv"/></radialGradient><radialGradient id="ivE2Vpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92188 -.9624 0 18.407 23.01)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ycpj7-guj"/><stop offset="1" class="jo18rcc6m"/></radialGradient><radialGradient id="ijvwFZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83361 -.91553 0 18.36 22.552)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="u7cuylb3v"/><stop offset="1" class="ecem-_b0c"/></radialGradient><radialGradient id="i3Z4Kce" cx="0" cy="0" r="1" gradientTransform="matrix(1.95312 .4974 -.77925 3.0599 14.36 23.88)" gradientUnits="userSpaceOnUse"><stop offset=".474" class="fkzsdxa9m"/><stop offset="1" class="bo-lpsbis"/></radialGradient><radialGradient id="it7l3Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 0 0 -.76563 18.891 24.74)" gradientUnits="userSpaceOnUse"><stop class="zi_08jbhu"/><stop offset="1" class="ewzoyqbwo"/></radialGradient><radialGradient id="ieWIZqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47859 0 0 -.14492 17.77 21.7)" gradientUnits="userSpaceOnUse"><stop class="rgikgeffu"/><stop offset="1" class="oskiey9pw"/></radialGradient><radialGradient id="iTIcr0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.34198 .54395 0 16.538 22.734)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iyW7eAd" cx="0" cy="0" r="1" gradientTransform="matrix(.09775 .12597 -.17343 .13458 16.634 22.699)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAN1SxC" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.342 .54398 0 18.378 22.734)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iaEaMIe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 20.519 2.355)scale(.20829 .25036)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iKmVjoc" width="2.064" height="2.201" x="25.478" y="24.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="iyA31Kb" width="2.069" height="2.206" x="25.515" y="25.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="iibyTrd" width="1.801" height="1.929" x="25.239" y="25.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="ifzWymb" width="1.405" height="1.524" x="24.915" y="26.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.45098 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="iUxRjWb" width="8.77" height="8.383" x="13.223" y="13.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.647059 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="iqjNo0b" width="6.829" height="7.242" x="20.747" y="3.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.317647 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="icU82id" width="4.79" height="2.813" x="25.665" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="iVtA8Me" width="5.938" height="6.795" x="21.027" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".15"/></filter><filter id="iIa4bDb" width="10.596" height="6.162" x="12.56" y="8.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="iActVmc" width="1.039" height="1.039" x="18.939" y="21.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".05"/></filter><filter id="iVx2ZVd" width="1.039" height="1.039" x="14.928" y="21.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".05"/></filter><filter id="iGxXfBb" width="2.99" height="2.493" x="14.58" y="22.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".3"/></filter><filter id="i3Z1ngd" width="5.313" height="3.491" x="14.8" y="22.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0784314 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23559"/></filter><filter id="iahXSsd" width=".991" height="1.33" x="16.961" y="21.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".05"/></filter><filter id="iuLyYLc" width=".447" height=".409" x="16.458" y="22.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".05"/></filter><filter id="iR3flUc" width=".607" height=".616" x="16.002" y="22.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".1"/></filter><filter id="icJSGOP" width=".647" height=".67" x="17.835" y="22.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".1"/></filter><filter id="i03xJHd" width=".501" height=".413" x="18.242" y="22.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".05"/></filter><filter id="i6ZeXjc" width="1.08" height=".482" x="15.827" y="23.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".05"/></filter><filter id="icBt6xd" width="1.113" height=".506" x="17.995" y="23.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".05"/></filter><filter id="ixa6gvd" width=".859" height="1.391" x="18.993" y="23.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23559" stdDeviation=".125"/></filter><linearGradient id="iEScWPc" x1="26.276" x2="25.725" y1="27.951" y2="27.951" gradientUnits="userSpaceOnUse"><stop class="r2_7pkbmo"/><stop offset="1" class="wcwoqrbaq"/></linearGradient><linearGradient id="iCAMPGd" x1=".146" x2=".125" y1=".968" y2="1.327" gradientUnits="userSpaceOnUse"><stop offset=".115" class="jbqcexb-p"/><stop offset="1" class="b2el6qblq"/></linearGradient><linearGradient id="ivhuhgb" x1=".201" x2=".188" y1=".545" y2="1.014" gradientUnits="userSpaceOnUse"><stop offset=".255" class="jbqcexb-p"/><stop offset="1" class="le3x4zbvz"/></linearGradient><linearGradient id="iX8Qwud" x1=".211" x2=".203" y1=".458" y2=".853" gradientUnits="userSpaceOnUse"><stop offset=".255" class="jbqcexb-p"/><stop offset="1" class="le3x4zbvz"/></linearGradient><linearGradient id="id8fUTd" x1="26.892" x2="29.141" y1="28.145" y2="28.432" gradientUnits="userSpaceOnUse"><stop offset=".144" class="y3cw3wbjk"/><stop offset=".951" class="umwffwbyy"/></linearGradient><linearGradient id="iDqQddd" x1="28.792" x2="28" y1="28.767" y2="28.757" gradientUnits="userSpaceOnUse"><stop class="ry8hkacaj"/><stop offset="1" class="qfa7lcbwg"/></linearGradient><linearGradient id="i4acwCe" x1="14.03" x2="18.843" y1="13.438" y2="15.094" gradientUnits="userSpaceOnUse"><stop offset=".288" class="gesenab-k"/><stop offset="1" class="kscf9stoz"/></linearGradient><linearGradient id="iNgO3ue" x1="8.962" x2="8.962" y1="14.039" y2="12.521" gradientUnits="userSpaceOnUse"><stop class="kkx5bsbxf"/><stop offset="1" class="ywea8pb6g"/></linearGradient><linearGradient id="isr2aip" x1="8.114" x2="8.192" y1="11.833" y2="12.349" gradientUnits="userSpaceOnUse"><stop class="iwyc2pgqn"/><stop offset="1" class="w9a9hvbwq"/></linearGradient><linearGradient id="ilxSKgd" x1="27.436" x2="27.436" y1="2.063" y2="2.211" gradientUnits="userSpaceOnUse"><stop class="su56_nrsk"/><stop offset="1" class="wrxtldewy"/></linearGradient><linearGradient id="iMhVatp" x1="25.915" x2="26.592" y1="2.531" y2="2.531" gradientUnits="userSpaceOnUse"><stop class="gt57qko1f"/><stop offset="1" class="mak5wnjve"/></linearGradient><linearGradient id="iqIEnAK" x1="5.468" x2="4.811" y1="11.812" y2="12.391" gradientUnits="userSpaceOnUse"><stop class="d3k6isbnm"/><stop offset="1" class="mi7m9xbsl"/></linearGradient><linearGradient id="iAk3Tac" x1="3.1" x2="3.257" y1="12.578" y2="12.766" gradientUnits="userSpaceOnUse"><stop offset=".07" class="kfgxjwb7e"/><stop offset="1" class="gzc8sbczu"/></linearGradient><linearGradient id="iuxv2xc" x1="12.876" x2="13.345" y1="14.469" y2="11.781" gradientUnits="userSpaceOnUse"><stop offset=".264" class="kswhxtfcb"/><stop offset="1" class="cj3zw_ajv"/></linearGradient><linearGradient id="ihiEgZR" x1="21.72" x2="20.845" y1="12.875" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="a3l5-0b9h"/><stop offset="1" class="b3vardzds"/></linearGradient><linearGradient id="ifErokc" x1="16.637" x2="13.005" y1="23.706" y2="24.957" gradientUnits="userSpaceOnUse"><stop class="tj1m2brjg"/><stop offset="1" class="xb2x7cb8e"/></linearGradient><linearGradient id="iEI5jze" x1="17.757" x2="17.22" y1="22.121" y2="22.121" gradientUnits="userSpaceOnUse"><stop class="qafkwysiq"/><stop offset="1" class="ryt3g_bya"/></linearGradient><linearGradient id="iDdO32j" x1="16.21" x2="16.342" y1="22.711" y2="22.63" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iA9QPXc" x1="18.064" x2="18.196" y1="22.711" y2="22.63" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="it7oiQd" x1="19.422" x2="19.422" y1="24.517" y2="23.607" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-cartwheeling-medium-dark" /></template>
<style>
.a3l5-0b9h {
  stop-color: var(--svg-color--9d94a4, #9D94A4);
}

.a6h5ccbnr {
  d: path("m27.548 4.375l-1.633-.773v-1.29a.25.25 0 0 1 .25-.25h3.972c.151 0 .3.086.315.237c.026.281-.125.62-.6.951c-.542.352-1.699.844-2.304 1.125");
}

.atsylmdpa {
  fill: var(--svg-color--000, #000);
  d: path("M18.163 22.559c0 .12.096.215.215.215a.215.215 0 0 0 .192-.314h-.381a.2.2 0 0 0-.026.099");
}

.az7cnskom {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.466 23.05c.275 0 .508-.19.57-.447a.116.116 0 0 0-.112-.143h-.94a.097.097 0 0 0-.096.114a.59.59 0 0 0 .578.476");
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

.bamjsvb8t {
  stop-color: var(--svg-color--50c7ff, #50C7FF);
  stop-opacity: 0;
}

.bbk20sbrs {
  stop-color: var(--svg-color--81466d, #81466D);
}

.bef5gkb7g {
  stop-color: var(--svg-color--403178, #403178);
  stop-opacity: 0;
}

.bltptbchx {
  stop-color: var(--svg-color--64353e, #64353E);
}

.bo-lpsbis {
  stop-color: var(--svg-color--463a38, #463A38);
  stop-opacity: 0;
}

.bo50hoaxz {
  stop-color: var(--svg-color--714652, #714652);
  stop-opacity: 0;
}

.br6wf4dup {
  stop-color: var(--svg-color--8f685e, #8F685E);
  stop-opacity: 0;
}

.bxoiu5bus {
  cx: 15.447px;
  cy: 22.447px;
  r: 0.419px;
  fill: var(--svg-color--60393c, #60393C);
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

.cusk6jb7f {
  stroke: var(--svg-color--43373a, #43373A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.757 23.654c-.182.032-.535.023-.78-.168");
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

.ddhy2b65m {
  d: path("m17.618 22.567l.224-.717a.227.227 0 0 0-.22-.295h-.331a.228.228 0 0 0-.22.295l.224.717c.048.159.272.159.323 0");
}

.de3gtwbql {
  stop-color: var(--svg-color--926b68, #926B68);
  stop-opacity: 0;
}

.dotuh9bef {
  d: path("M16.537 22.935a.376.376 0 0 1-.362-.475h.726a.378.378 0 0 1-.364.475");
}

.e_oa-tb8l {
  stop-color: var(--svg-color--714652, #714652);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecem-_b0c {
  stop-color: var(--svg-color--915c5e, #915C5E);
  stop-opacity: 0;
}

.emj-kwbhr {
  cx: 18.492px;
  cy: 22.774px;
  rx: 0.164px;
  ry: 0.083px;
}

.emxgosifs {
  cx: 19.458px;
  cy: 22.447px;
  r: 0.419px;
  fill: var(--svg-color--7d5a54, #7D5A54);
}

.equhh1t5g {
  fill: var(--svg-color--856053, #856053);
  d: path("m12.767 14.04l-7.61-.142l.625-1.57l6.844-.984z");
}

.ewzoyqbwo {
  stop-color: var(--svg-color--43373c, #43373C);
  stop-opacity: 0;
}

.fh46qfkzu {
  d: path("M19.607 22.705h-.02s.022.359.045.606c0 .113-.046.248-.136.315l-.068.068a.45.45 0 0 0-.158.36v.36a.22.22 0 0 1-.181.224a7 7 0 0 1-1.651.18c-.814 0-1.38-.113-1.65-.18a.24.24 0 0 1-.182-.225v-.36a.53.53 0 0 0-.158-.36c-.212-.148-.199-.23-.181-.404c.023-.225.045-.607.045-.607h-.007l.112-1.67c.067-.745.654-1.265 1.353-1.265h1.354c.722 0 1.286.52 1.353 1.266z");
}

.fkzsdxa9m {
  stop-color: var(--svg-color--463a38, #463A38);
}

.flq8uy9_y {
  stop-color: var(--svg-color--93716a, #93716A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gesenab-k {
  stop-color: var(--svg-color--3280d1, #3280D1);
}

.ghbrfbb8g {
  stop-color: var(--svg-color--744c4e, #744C4E);
  stop-opacity: 0;
}

.gid_9j_gv {
  stop-color: var(--svg-color--92695b, #92695B);
  stop-opacity: 0;
}

.gr0xwfbsq {
  d: path("M18.655 20.195h2.326v1.781h-2.326z");
}

.gt57qko1f {
  stop-color: var(--svg-color--5f5e7a, #5F5E7A);
}

.gun13-b-l {
  d: path("m15.37 24.818l1.298-.433a.442.442 0 0 0-.198-.856l-1.29.173z");
}

.gzc8sbczu {
  stop-color: var(--svg-color--424272, #424272);
  stop-opacity: 0;
}

.h2ug0z0zy {
  stop-color: var(--svg-color--75524a, #75524A);
}

.h5k7xu51c {
  stop-color: var(--svg-color--487fd0, #487FD0);
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

.ht2yfkjwb {
  stop-color: var(--svg-color--5dd2ff, #5DD2FF);
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

.jk0wsqyqs {
  stop-color: var(--svg-color--4cbfff, #4CBFFF);
}

.jmj4yzb8d {
  cx: 15.447px;
  cy: 22.447px;
  r: 0.704px;
}

.jmqoa7beg {
  cx: 19.459px;
  cy: 22.447px;
  r: 0.704px;
}

.jo18rcc6m {
  stop-color: var(--svg-color--a27c73, #A27C73);
  stop-opacity: 0;
}

.k2wpap9_u {
  stop-color: var(--svg-color--926b68, #926B68);
}

.kchp3yc8t {
  stop-color: var(--svg-color--85545e, #85545E);
}

.kcvv1loqd {
  stop-color: var(--svg-color--2874ab, #2874AB);
}

.kfgxjwb7e {
  stop-color: var(--svg-color--424272, #424272);
}

.kkx5bsbxf {
  stop-color: var(--svg-color--804b71, #804B71);
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

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.le3x4zbvz {
  stop-color: var(--svg-color--8c6564, #8C6564);
  stop-opacity: 0;
}

.lgjuvnbhi {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.565 22.856c-.027-.036.03-.08.093-.128c.064-.047.11-.08.138-.045c.027.036-.003.104-.067.151c-.064.048-.137.057-.164.022");
}

.lhxavd33y {
  d: path("M16.202 22.608c.014.098.07.171.098.195l.11-.12l-.05-.096z");
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

.md7ne1b7k {
  cx: 18.492px;
  cy: 22.774px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.164px;
  ry: 0.083px;
}

.mi7m9xbsl {
  stop-color: var(--svg-color--514f87, #514F87);
}

.mt_0cpx2h {
  stroke: var(--svg-color--896661, #896661);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m26.551 4.229l-5.11 6");
}

.n52mgrb1s {
  opacity: var(--svg-opacity--0-4, 0.4);
}

.na5ps0b6u {
  fill: var(--svg-color--86595c, #86595C);
  d: path("M14.82 29.85c-.296.03-.955.087-1.58.087c-.653 0-.73-.345-.731-.519c-.01-.115.056-.368.39-.465c.121-.035.26-.072.397-.108a.2.2 0 0 0 .15-.194v-6.628h2.04v7.129a.7.7 0 0 1-.564.686l.001.002l-.025.003z");
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ngyzvbbds {
  stop-color: var(--svg-color--3293c7, #3293C7);
  stop-opacity: 0;
}

.nqe9_3xqo {
  stop-color: var(--svg-color--714a3d, #714A3D);
}

.nv7x83egt {
  d: path("M4.698 11.294a.25.25 0 0 1 .346.027l.875.984l-.734 1.59l-1.176.335c-.305.1-1.059.303-1.637.325a.89.89 0 0 1-.778-.37c-.092-.123-.047-.291.072-.389z");
}

.o1qljk8ih {
  cx: 19.459px;
  cy: 22.447px;
  r: 0.704px;
  fill: var(--svg-color--815754, #815754);
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

.ot3t6hbfc {
  stop-color: var(--svg-color--34a4e5, #34A4E5);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.qafkwysiq {
  stop-color: var(--svg-color--8b5961, #8B5961);
}

.qb80pcc1k {
  d: path("m15.425 25.178l-.18-.09a.83.83 0 0 1-.43-.9l.248-1.282c.022-.132.11-.221.241-.224h.008s-.022.382-.045.607c-.018.182.013.238.18.404a.53.53 0 0 1 .16.36v.36c0 .112.09.202.18.225c.271.067.837.18 1.65.18c.815 0 1.38-.113 1.652-.18a.22.22 0 0 0 .18-.225v-.36c0-.135.046-.27.159-.36l.068-.067c.09-.068.136-.202.136-.315a27 27 0 0 1-.046-.607h.02a.27.27 0 0 1 .252.225l.248 1.282a.86.86 0 0 1-.452.877l-.18.09c-.114.067-.227.157-.34.247l-.407.427a.83.83 0 0 1-.927.135a1.24 1.24 0 0 0-.701 0c-.34.112-.724.023-.995-.225l-.34-.337a.95.95 0 0 0-.339-.248");
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

.qqc_3qb_f {
  d: path("M18.378 22.935a.376.376 0 0 0 .363-.475h-.727a.38.38 0 0 0 .364.475");
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

.rg-wm7esh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.368 24.475v-.378c.003-.063.03-.203.109-.263");
}

.rgikgeffu {
  stop-color: var(--svg-color--a87f75, #A87F75);
}

.ry8hkacaj {
  stop-color: var(--svg-color--743e50, #743E50);
}

.ryt3g_bya {
  stop-color: var(--svg-color--7b4d51, #7B4D51);
}

.s_txeqb5u {
  width: 0.684px;
  height: 2.521px;
  fill: var(--svg-color--947266, #947266);
  rx: 0.342px;
}

.s8mikn8pw {
  stop-color: var(--svg-color--85575e, #85575E);
  stop-opacity: 0;
}

.su56_nrsk {
  stop-color: var(--svg-color--444570, #444570);
}

.t8a7styqg {
  d: path("M16.565 22.856c-.027-.036.03-.08.093-.128c.064-.047.11-.08.138-.045c.027.036-.003.104-.067.151c-.064.048-.137.057-.164.022");
}

.tgvr64d-a {
  stop-color: var(--svg-color--a88173, #A88173);
}

.tj1m2brjg {
  stop-color: var(--svg-color--8b665e, #8B665E);
}

.u7cuylb3v {
  stop-color: var(--svg-color--915c5e, #915C5E);
}

.uib5ptygi {
  width: 0.809px;
  height: 1.648px;
  x: 25.404px;
  y: 27.272px;
  rx: 0.404px;
}

.uipvgs40m {
  fill: var(--svg-color--2f0e31, #2F0E31);
  d: path("m15.425 25.178l-.18-.09a.83.83 0 0 1-.43-.9l.248-1.282c.022-.132.11-.221.241-.224h.008s-.022.382-.045.607c-.018.182.013.238.18.404a.53.53 0 0 1 .16.36v.36c0 .112.09.202.18.225c.271.067.837.18 1.65.18c.815 0 1.38-.113 1.652-.18a.22.22 0 0 0 .18-.225v-.36c0-.135.046-.27.159-.36l.068-.067c.09-.068.136-.202.136-.315a27 27 0 0 1-.046-.607h.02a.27.27 0 0 1 .252.225l.248 1.282a.86.86 0 0 1-.452.877l-.18.09c-.114.067-.227.157-.34.247l-.407.427a.83.83 0 0 1-.927.135a1.24 1.24 0 0 0-.701 0c-.34.112-.724.023-.995-.225l-.34-.337a.95.95 0 0 0-.339-.248");
}

.umqxld3tj {
  d: path("M18.035 22.603c0 .122.099.203.125.227l.122-.117l-.075-.152z");
}

.umwffwbyy {
  stop-color: var(--svg-color--82505a, #82505A);
}

.v1g1kqbgg {
  fill: var(--svg-color--504e84, #504E84);
  d: path("m27.548 4.375l-1.633-.773v-1.29a.25.25 0 0 1 .25-.25h3.972c.151 0 .3.086.315.237c.026.281-.125.62-.6.951c-.542.352-1.699.844-2.304 1.125");
}

.v3a4xqbpf {
  stop-color: var(--svg-color--8f685e, #8F685E);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w3mc4qk1n {
  stop-color: var(--svg-color--815c51, #815C51);
}

.w7g1j2ber {
  stroke: var(--svg-color--43373a, #43373A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.957 23.436c-.138.122-.439.25-.812.19");
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

.wrxtldewy {
  stop-color: var(--svg-color--444570, #444570);
  stop-opacity: 0;
}

.wzq5d1gmc {
  fill: var(--svg-color--000, #000);
  d: path("M16.753 22.559c0 .12-.096.215-.216.215a.214.214 0 0 1-.191-.314h.381q.026.044.026.099");
}

.xb2x7cb8e {
  stop-color: var(--svg-color--8b665e, #8B665E);
  stop-opacity: 0;
}

.y-_otsbxx {
  fill: var(--svg-color--342625, #342625);
  d: path("M15.889 23.593v.001l.003.002l.005.004l.015.011q.018.015.05.034a1.2 1.2 0 0 0 .806.156a.225.225 0 1 0-.07-.445a.74.74 0 0 1-.497-.092l-.023-.016l-.004-.002a.225.225 0 0 0-.285.347m3.159 0v.001l-.003.002l-.005.004a.4.4 0 0 1-.065.045a1.2 1.2 0 0 1-.806.156a.225.225 0 0 1 .07-.445a.74.74 0 0 0 .497-.092l.023-.016l.004-.002a.225.225 0 0 1 .286.347");
}

.y3cw3wbjk {
  stop-color: var(--svg-color--9f7c73, #9F7C73);
}

.ycpj7-guj {
  stop-color: var(--svg-color--a27c73, #A27C73);
}

.yhnzr0bpw {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M17.457 21.127c.214 0 .415.05.584.139c.058.029.12-.036.083-.089a.8.8 0 0 0-.667-.356a.8.8 0 0 0-.668.356c-.036.055.026.118.084.088a1.26 1.26 0 0 1 .584-.138");
}

.yi2txbcnj {
  stop-color: var(--svg-color--7f594d, #7F594D);
}

.ywea8pb6g {
  stop-color: var(--svg-color--855c5a, #855C5A);
  stop-opacity: 0;
}

.z2p55f_ys {
  stop-color: var(--svg-color--6c4447, #6C4447);
}

.z399-vbiq {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.45 23.05a.59.59 0 0 1-.571-.447a.116.116 0 0 1 .113-.143h.94c.06 0 .108.055.096.114a.59.59 0 0 1-.578.476");
}

.zi_08jbhu {
  stop-color: var(--svg-color--43373c, #43373C);
}

.znagombkh {
  d: path("m20.615 14.064l2.542-3.495L20.783 8.4c-.14.134-.505.492-.84.85c-1.188 1.15-2.767 1.43-3.776 1.58l-3.607.495v2.737z");
}

</style>
