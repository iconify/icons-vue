<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iwOInEx)"><path class="pk84u7jjf"/><path fill="url(#iYUPgCn)" class="pn5jbtt9h"/></g><path fill="url(#ibC1qLe)" class="pn5jbtt9h"/><path fill="url(#iIAQn6c)" class="pn5jbtt9h"/><path fill="url(#i1wcfOb)" class="pn5jbtt9h"/><path fill="url(#id94ewd)" class="pn5jbtt9h"/><g filter="url(#irD6IHd)"><path class="y79whbcii"/><path fill="url(#iTH78cb)" class="z0pxpnkbw"/></g><path class="fugdzyb1o"/><path fill="url(#iTIjaLd)" class="hr107sbjg"/><path fill="url(#ioDmBkd)" class="sgu32ab0w"/><path fill="url(#ijic07z)" class="sf2boes3b"/><path fill="url(#isyGmte)" class="sf2boes3b"/><g filter="url(#it8ssbd)"><path fill="url(#icOIhCe)" class="lbpgcfbob"/><path fill="url(#i0RjV5w)" class="lbpgcfbob"/></g><g filter="url(#icCJK9b)"><circle fill="url(#ilkWDkd)" class="dkktn1hof"/></g><g filter="url(#i1lUuPb)"><circle fill="url(#iR7ViFc)" class="uh8iu31tc"/></g><g filter="url(#iY3Pkbe)"><circle fill="url(#iVwnzxc)" class="a5a4koq8x"/></g><rect fill="url(#iWebikb)" transform="rotate(26.595 20.662 12.81)" class="toe447tsm"/><g filter="url(#ifBPpse)"><path fill="url(#icaasDe)" class="qd_9svrfx"/></g><path class="dldw44uej"/><g filter="url(#iIttDDd)"><path class="h6yh2f-1k"/><path fill="url(#i0iwDkM)" class="xzkoa2bwe"/><path fill="url(#iarHTYb)" class="xzkoa2bwe"/></g><g filter="url(#i0Tk5Je)"><path fill="url(#icNrbRb)" class="cjqtkw6wk"/><path fill="url(#imXSdsc)" class="cjqtkw6wk"/><path fill="url(#iDDq3Lc)" class="cjqtkw6wk"/></g><path fill="url(#im3rfBd)" class="cjqtkw6wk"/><path fill="url(#iXkTdtt)" class="llo96eq-p"/><path fill="url(#iN5DvHb)" class="llo96eq-p"/><path clip-rule="evenodd" class="n-63dkbfe"/><path fill="url(#ibw8yfe)" clip-rule="evenodd" class="y-2lu0bml"/><path clip-rule="evenodd" class="qe-ha1b7i"/><path fill="url(#i7JGUkc)" clip-rule="evenodd" class="xy8jbrbcm"/><path clip-rule="evenodd" class="iwur3y2uz"/><path fill="url(#iyLPjHb)" clip-rule="evenodd" class="ngpy26t4k"/><path clip-rule="evenodd" class="vurnokzna"/><path fill="url(#iyiSuIb)" clip-rule="evenodd" class="wvwy8egxn"/><path class="ekge1hb-m"/><path fill="url(#iCdksNe)" class="lalq_3f3j"/><g filter="url(#ieiGQid)"><path fill="url(#iR6HFdd)" class="r8fjj8bcd"/></g><g filter="url(#iOWzZSd)"><path fill="url(#ijAEood)" class="siwrhab8g"/></g><g filter="url(#iQmJLAd)"><path stroke="url(#iBLtKxd)" class="j6zxuhbzj"/></g><g filter="url(#io95XOb)"><circle fill="url(#i4a8sOe)" class="uiakhkvls"/></g><circle fill="url(#iNTqFGd)" class="uiakhkvls"/><g filter="url(#iTZxLHc)"><circle fill="url(#iSBpuDb)" class="vn476zbcv"/></g><g filter="url(#iR2OuZd)"><circle fill="url(#iJ5lztd)" class="f3zvxvb6o"/><circle fill="url(#i6qmAkb)" class="f3zvxvb6o"/></g><g filter="url(#iIupXab)"><circle class="bs019nbgl"/><circle fill="url(#ixGNzkc)" class="flwxwqbou"/><circle fill="url(#iZIgmZc)" class="flwxwqbou"/></g><g filter="url(#i47cYsR)"><path fill="url(#iF9PIhc)" class="gwjk-obhk"/><path fill="url(#i2vS3Qd)" class="gwjk-obhk"/><path fill="url(#iOCQRpd)" class="gwjk-obhk"/></g><path fill="url(#iBq1Wjc)" class="da7vpjbxw"/><path fill="url(#iJ0QLCb)" class="da7vpjbxw"/><path fill="url(#iReUfJb)" class="da7vpjbxw"/><g filter="url(#iTdbvle)"><path fill="url(#i5lEcHc)" class="rrqfdbb_i"/></g><g filter="url(#iTspQNc)"><path class="x8t9mcbvp"/><path fill="url(#iWdWDss)" class="n5083tm6w"/><path fill="url(#igW3qoe)" class="n5083tm6w"/><path fill="url(#i6bBsbd)" class="n5083tm6w"/><path fill="url(#iX672Zb)" class="n5083tm6w"/></g><g filter="url(#ipOHl4b)"><path class="r-qqqqbyj"/></g><g filter="url(#ipiOCPc)"><path class="yq2gz16ay"/><path fill="url(#imtyDxe)" class="bvxs0d4kw"/><path fill="url(#iJXP2OW)" class="bvxs0d4kw"/><path fill="url(#iEh0dub)" class="bvxs0d4kw"/><path fill="url(#iOhxfOe)" class="bvxs0d4kw"/></g><path stroke="url(#iQnirrd)" class="fnt3yacsv"/><g filter="url(#in9CZpd)"><path class="g0ot2wk8b"/><path fill="url(#iEToOuH)" class="f5zbcqbfg"/></g><g filter="url(#iRtparc)"><path class="oiy5ljb5q"/><path fill="url(#id5l0he)" class="o09v1ibsc"/></g><path class="detz4ob-c"/><path fill="url(#iqwZTjd)" class="jki-qw2mt"/><path class="p-d7sqbgf"/><g filter="url(#iquB8Ub)"><path class="yt1ay9nnj"/><path fill="url(#iGKbvWc)" class="ni5zb4boq"/></g><g filter="url(#iWicZjc)"><path fill="url(#iqw0y2b)" class="yx-2ufqaz"/></g><path class="qdnb_qbiy"/><path fill="url(#i3CxRke)" class="m52_bcc9m"/><path class="q2o782xwr"/><g filter="url(#ivn8m6d)"><path fill="url(#i2fNGgz)" class="xicqgpbmz"/></g><g filter="url(#i6MIs4d)"><ellipse transform="rotate(-27.914 13.089 5.692)" class="cgiafib7q"/><ellipse fill="url(#iao5dec)" transform="rotate(-27.914 13.089 5.692)" class="lgn6_uc-y"/></g><g filter="url(#idFzgwe)"><path stroke="url(#i2M7jVc)" class="bgsgg_b5s"/></g><g filter="url(#i6OK7Lc)"><path stroke="url(#i1lX91d)" class="kwt8dvuee"/></g><g filter="url(#iR11kxe)"><path stroke="url(#iA1FHjb)" class="hnez6kbcb"/></g><defs><radialGradient id="ibC1qLe" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.77)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="i1wcfOb" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.926)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="id94ewd" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.77)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iTH78cb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.17 25.208)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iTIjaLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.76 25.141)" gradientUnits="userSpaceOnUse"><stop class="gsejooqnz"/><stop offset="1" class="of4__9yml"/></radialGradient><radialGradient id="isyGmte" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.473)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="i0RjV5w" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.742 2.818)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="ilkWDkd" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.215 11.138)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iR7ViFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.556)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iVwnzxc" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.168 9.172)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iWebikb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.108)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="eb_ebqvii"/><stop offset="1" class="wqensyb5w"/></radialGradient><radialGradient id="icaasDe" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.2 10.925)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="xtqzqnbwf"/><stop offset="1" class="god345nqf"/></radialGradient><radialGradient id="i0iwDkM" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.926 6.717)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="jioe1_9gu"/><stop offset="1" class="t5lf5ccyt"/></radialGradient><radialGradient id="iarHTYb" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.335 10.553)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="fqeviqb2e"/><stop offset="1" class="to9zfdmjz"/></radialGradient><radialGradient id="imXSdsc" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.426)" gradientUnits="userSpaceOnUse"><stop class="lj0l7tb9r"/><stop offset="1" class="zrzxj2epv"/></radialGradient><radialGradient id="iDDq3Lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.606)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="vgauzicqp"/><stop offset="1" class="r0iiaeguw"/></radialGradient><radialGradient id="im3rfBd" cx="0" cy="0" r="1" gradientTransform="matrix(1.38038 -.82813 3.08645 5.14471 17.339 21.238)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="t502ec3cr"/><stop offset="1" class="oipf0m4co"/></radialGradient><radialGradient id="iN5DvHb" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -.93464 2.0447 18.61 10.753)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="g99cn0bet"/><stop offset="1" class="gq1i90b_a"/><stop offset="1" class="airol1bay"/></radialGradient><radialGradient id="ibw8yfe" cx="0" cy="0" r="1" gradientTransform="rotate(-139.897 5.2 5.918)scale(1.34825 1.69882)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="i7JGUkc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24388 -.94214 1.33264 -1.75944 5.77 14.69)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iyLPjHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23007 -1.01775 1.46904 -1.7755 5.598 15.256)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iyiSuIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 -.89062 1.29178 -1.51843 5.802 15.488)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iCdksNe" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.78)" gradientUnits="userSpaceOnUse"><stop class="pzzto25mw"/><stop offset="1" class="pfxo1bxwi"/></radialGradient><radialGradient id="iR6HFdd" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.508 15.402)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="i4a8sOe" cx="0" cy="0" r="1" gradientTransform="matrix(.77665 0 0 1.35914 11.335 6.037)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iNTqFGd" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 7.801 .244)scale(.73322)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="i6qmAkb" cx="0" cy="0" r="1" gradientTransform="matrix(.36587 -.26641 .30407 .4176 16.45 5.92)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="ixGNzkc" cx="0" cy="0" r="1" gradientTransform="matrix(.36347 -.66851 .39128 .21274 16.266 6.4)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iZIgmZc" cx="0" cy="0" r="1" gradientTransform="rotate(44.706 .802 22.818)scale(.16146 .20815)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="i2vS3Qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57847 .71197 0 15.214 5.474)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iOCQRpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60814 .75627 0 13.197 5.533)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iReUfJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.68591 -4.56845 0 14.119 5.358)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset=".884" class="fkee40m0y"/><stop offset="1" class="an_-aznlj"/></radialGradient><radialGradient id="iWdWDss" cx="0" cy="0" r="1" gradientTransform="matrix(.35309 -1.3085 .48523 .13094 16.1 4.22)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="igW3qoe" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -29.78 169.11)scale(1.69991 .91403)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="i6bBsbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .74315 -1.15093 0 14.175 2.23)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iX672Zb" cx="0" cy="0" r="1" gradientTransform="matrix(1.36043 -.99696 1.56191 2.13135 11.321 5.248)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iOhxfOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08714 -.27997 0 14.32 6.748)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iEToOuH" cx="0" cy="0" r="1" gradientTransform="matrix(.04611 -.26699 .78986 .13642 15.257 5.114)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="id5l0he" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 9.526 -5.149)scale(.27094 .8016)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iqwZTjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35898 -.571 0 15.14 5.735)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iGKbvWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10262 -.13223 .18206 -.14128 15.039 5.772)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3CxRke" cx="0" cy="0" r="1" gradientTransform="matrix(0 .359 -.57103 0 13.209 5.735)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iao5dec" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 9.412 -3.524)scale(.21864 .26282)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iwOInEx" width="23.977" height="13.398" x="6.016" y="16.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="irD6IHd" width="20.681" height="10.082" x="6.11" y="20.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".75"/></filter><filter id="it8ssbd" width="24.344" height="8.644" x="2.007" y="21.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="icCJK9b" width="2.686" height="2.686" x="24.571" y="13.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="i1lUuPb" width="2.186" height="2.186" x="27.821" y="11.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="iY3Pkbe" width="1.928" height="1.928" x="25.946" y="9.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="ifBPpse" width="2.857" height="2.898" x="20.532" y="12.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.34902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="iIttDDd" width="5.571" height="6.952" x="7.773" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.396078 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="i0Tk5Je" width="14.97" height="18.153" x="8.427" y="7.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.537255 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="ieiGQid" width="17.737" height="14.8" x="13.579" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation="1"/></filter><filter id="iOWzZSd" width="6.506" height="14.75" x="14.572" y="7.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".375"/></filter><filter id="iQmJLAd" width="5.506" height="5.421" x="17.991" y="7.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".3"/></filter><filter id="io95XOb" width="1.678" height="1.478" x="11.335" y="5.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="iTZxLHc" width="1.881" height="1.881" x="11.134" y="5.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".25"/></filter><filter id="iR2OuZd" width="1.728" height="1.728" x="15.546" y="5.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="iIupXab" width="1.881" height="1.881" x="15.344" y="5.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".25"/></filter><filter id="i47cYsR" width="4.591" height="5.373" x="11.893" y="3.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="iTdbvle" width="3.879" height="3.357" x="13.251" y="2.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".5"/></filter><filter id="iTspQNc" width="5.577" height="3.66" x="11.387" y="2.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="ipOHl4b" width="2.279" height="2.687" x="12.93" y="5.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".375"/></filter><filter id="ipiOCPc" width="1.031" height="1.387" x="13.66" y="5.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".05"/></filter><filter id="in9CZpd" width="1.458" height="1.052" x="14.699" y="4.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="iRtparc" width="1.458" height="1.052" x="12.42" y="4.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22999"/></filter><filter id="iquB8Ub" width=".46" height=".42" x="14.759" y="5.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".05"/></filter><filter id="iWicZjc" width=".617" height=".627" x="15.075" y="5.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".1"/></filter><filter id="ivn8m6d" width=".659" height=".683" x="13.109" y="5.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".1"/></filter><filter id="i6MIs4d" width=".516" height=".423" x="12.831" y="5.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".05"/></filter><filter id="idFzgwe" width="1.219" height=".591" x="14.71" y="4.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".075"/></filter><filter id="i6OK7Lc" width="1.253" height=".616" x="12.4" y="4.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".075"/></filter><filter id="iR11kxe" width=".864" height="1.422" x="11.68" y="3.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22999" stdDeviation=".125"/></filter><linearGradient id="iYUPgCn" x1="7.172" x2="16.735" y1="29.364" y2="29.364" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iIAQn6c" x1="16.86" x2="16.766" y1="30.27" y2="28.645" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="ioDmBkd" x1="21.172" x2="19.469" y1="21.926" y2="23.012" gradientUnits="userSpaceOnUse"><stop class="szw4sibdg"/><stop offset="1" class="k794rrb7o"/></linearGradient><linearGradient id="ijic07z" x1="22.095" x2="23.329" y1="24.832" y2="26.114" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="icOIhCe" x1="5.891" x2="25.735" y1="29.239" y2="22.332" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="icNrbRb" x1="15.777" x2="15.777" y1="7.606" y2="25.567" gradientUnits="userSpaceOnUse"><stop class="nxcp0hivj"/><stop offset="1" class="p79aa0p9z"/></linearGradient><linearGradient id="iXkTdtt" x1="23.651" x2="16.517" y1="12.502" y2="8.549" gradientUnits="userSpaceOnUse"><stop class="y60usm6nn"/><stop offset=".91" class="u6gia-bos"/></linearGradient><linearGradient id="ijAEood" x1="17.826" x2="20.269" y1="8.16" y2="21.397" gradientUnits="userSpaceOnUse"><stop class="yrtrc6n_d"/><stop offset="1" class="kkuk5w_fi"/></linearGradient><linearGradient id="iBLtKxd" x1="22.438" x2="18.766" y1="11.879" y2="7.989" gradientUnits="userSpaceOnUse"><stop class="tgz_9qxcq"/><stop offset="1" class="zvqcq9hxr"/></linearGradient><linearGradient id="iSBpuDb" x1="12.074" x2="11.791" y1="6.16" y2="6.16" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iJ5lztd" x1="16.765" x2="16.403" y1="5.553" y2="6.676" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iF9PIhc" x1="15.962" x2="12.582" y1="6.209" y2="6.713" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iBq1Wjc" x1="11.787" x2="12.62" y1="7.402" y2="7.372" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iJ0QLCb" x1="16.353" x2="15.861" y1="7.03" y2="6.987" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="i5lEcHc" x1="13.94" x2="17.544" y1="4.888" y2="3.598" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="imtyDxe" x1="13.793" x2="14.208" y1="6.501" y2="6.501" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iJXP2OW" x1="14.591" x2="14.137" y1="6.643" y2="6.637" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iEh0dub" x1="14.261" x2="14.261" y1="6.972" y2="6.718" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iQnirrd" x1="13.716" x2="13.909" y1="7.687" y2="7.383" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iqw0y2b" x1="15.484" x2="15.345" y1="5.759" y2="5.844" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2fNGgz" x1="13.538" x2="13.399" y1="5.759" y2="5.844" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2M7jVc" x1="15.491" x2="15.305" y1="4.812" y2="4.432" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i1lX91d" x1="13.143" x2="12.617" y1="4.755" y2="4.534" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iA1FHjb" x1="12.112" x2="12.112" y1="3.864" y2="4.818" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-surfing-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a5a4koq8x {
  cx: 26.86px;
  cy: 10.727px;
  r: 0.914px;
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.ajhe7ybyb {
  stop-color: var(--svg-color--9b686d, #9B686D);
}

.an_-aznlj {
  stop-color: var(--svg-color--7c5267, #7C5267);
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bgsgg_b5s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.91 4.769c.19-.033.562-.024.819.176");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bs019nbgl {
  cx: 16.285px;
  cy: 6.037px;
  r: 0.44px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.bvxs0d4kw {
  d: path("m14.006 5.91l-.235.753a.24.24 0 0 0 .23.309h.348a.24.24 0 0 0 .23-.31l-.234-.752c-.05-.166-.286-.166-.339 0");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.cgiafib7q {
  cx: 13.089px;
  cy: 5.692px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.cjqtkw6wk {
  d: path("M12.759 11.653c-.432-1.716.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.258c1.354 1.047 1.622 2.799 1.589 3.592a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.273-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.513 1.212 3.52c.546 1.484-.11 2.952.375 4.484c.377 1.191 1.203 2.418 1.636 2.92a.04.04 0 0 1-.013.063l-1.834.852a.04.04 0 0 1-.048-.01c-1.848-2.158-2.5-3.826-2.562-3.99s-.23-.53-.574-.53c-.275 0-.59.35-.809.73l-4.667 7.137a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.057c.21-.5.181-.917.14-1.086c-.03-.13-.218-.711-.585-2.172");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.da7vpjbxw {
  d: path("M11.893 5.129c0-.118.047-.26.142-.33l.071-.071a.47.47 0 0 0 .167-.378v-.378a.23.23 0 0 1 .19-.236c.284-.07.878-.189 1.732-.189c.855 0 1.448.118 1.733.19c.095.023.19.117.19.235v.378a.56.56 0 0 0 .166.378c.223.155.209.24.19.424c-.023.236-.047.638-.047.638h.008l-.118 1.752c-.07.783-.687 1.329-1.42 1.329h-1.421c-.758 0-1.35-.546-1.421-1.33c-.062-.803-.089-1.61-.162-2.412");
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.detz4ob-c {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.232 5.403c.29 0 .533.2.6.469c.02.077-.04.15-.119.15h-.987a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .606-.499");
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dkktn1hof {
  cx: 25.864px;
  cy: 14.762px;
  r: 1.293px;
}

.dldw44uej {
  fill: var(--svg-color--aa846a, #AA846A);
  d: path("M7.602 12.776h.594c-.106.669.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.256.977-.3 1.258-.29");
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eb_ebqvii {
  stop-color: var(--svg-color--94625a, #94625A);
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.ekge1hb-m {
  fill: var(--svg-color--aa846a, #AA846A);
  d: path("M6.126 14.887c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f3zvxvb6o {
  cx: 16.284px;
  cy: 6.037px;
  r: 0.739px;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f5zbcqbfg {
  d: path("M15.822 4.833v-.001l-.003-.002l-.005-.004l-.069-.048a1.25 1.25 0 0 0-.846-.163a.236.236 0 1 0 .074.467a.78.78 0 0 1 .522.097l.024.016l.003.003a.236.236 0 0 0 .3-.365");
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fkee40m0y {
  stop-color: var(--svg-color--8f5d78, #8F5D78);
}

.flwxwqbou {
  cx: 16.285px;
  cy: 6.037px;
  r: 0.44px;
}

.fnt3yacsv {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.918 7.397a.11.11 0 0 0-.013-.142a.12.12 0 0 0-.14-.023c-.17.089-.37.14-.59.14a1.3 1.3 0 0 1-.59-.14a.12.12 0 0 0-.14.024a.11.11 0 0 0-.012.141m1.485 0l-.042-.028zm0 0a.89.89 0 0 1-.742.396a.89.89 0 0 1-.743-.396m0 0l.042-.028m-.042.028l.042-.028m0 0a.84.84 0 0 0 .7.374c.295 0 .553-.15.701-.374c.038-.057-.027-.123-.087-.092a1.3 1.3 0 0 1-.614.145a1.3 1.3 0 0 1-.613-.145c-.06-.031-.125.037-.087.092Z");
}

.fqeviqb2e {
  stop-color: var(--svg-color--1154b9, #1154B9);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fugdzyb1o {
  fill: var(--svg-color--ab7f67, #AB7F67);
  d: path("m7.305 27.348l1.172-2.39l1.766.304v1.04z");
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g0ot2wk8b {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M15.822 4.833v-.001l-.003-.002l-.005-.004l-.069-.048a1.25 1.25 0 0 0-.846-.163a.236.236 0 1 0 .074.467a.78.78 0 0 1 .522.097l.024.016l.003.003a.236.236 0 0 0 .3-.365");
}

.g99cn0bet {
  stop-color: var(--svg-color--2965ce, #2965CE);
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.god345nqf {
  stop-color: var(--svg-color--a1706f, #A1706F);
}

.gq1i90b_a {
  stop-color: var(--svg-color--2965ce, #2965CE);
  stop-opacity: 0;
}

.gsejooqnz {
  stop-color: var(--svg-color--ba917f, #BA917F);
}

.gwjk-obhk {
  d: path("m11.919 5.765l.021.001s-.024-.378-.047-.637c0-.118.047-.26.142-.33l.071-.071a.47.47 0 0 0 .167-.378v-.378a.23.23 0 0 1 .19-.236c.284-.07.878-.189 1.732-.189c.855 0 1.448.118 1.733.19c.095.023.19.117.19.235v.378a.56.56 0 0 0 .166.378c.223.155.209.24.19.424c-.023.236-.047.638-.047.638h.008l-.118 1.752c-.07.783-.687 1.329-1.42 1.329h-1.421c-.758 0-1.35-.546-1.421-1.33z");
}

.h6yh2f-1k {
  fill: var(--svg-color--3086d6, #3086D6);
  d: path("M10.684 11.696c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.032c.3-.028 1.148-.11 2.5-.72c1.679-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hnez6kbcb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.17 3.907v.398c-.004.065-.032.212-.115.275");
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hr107sbjg {
  d: path("m7.305 27.348l1.172-2.39l1.766.304v1.04z");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.iwur3y2uz {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.25 14.667q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.129.165-.253.27-.354a2.5 2.5 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.37a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j6zxuhbzj {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.286c1.209-.021 3.782.828 4.104 4");
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jioe1_9gu {
  stop-color: var(--svg-color--5391be, #5391BE);
}

.jki-qw2mt {
  d: path("M15.14 5.524a.395.395 0 0 1 .381.499h-.763a.396.396 0 0 1 .382-.499");
}

.k794rrb7o {
  stop-color: var(--svg-color--82574c, #82574C);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kkuk5w_fi {
  stop-color: var(--svg-color--6096e0, #6096E0);
}

.kwt8dvuee {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.6 4.998c.145-.128.461-.262.853-.2");
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lalq_3f3j {
  d: path("M6.126 14.887c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.lbpgcfbob {
  d: path("M24.458 21.262L2.29 28.951a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.099 1.156-.156c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.001c.094-.25.047-1.032-.5-1.454c-.437-.337-1.105-.184-1.355-.07");
}

.lgn6_uc-y {
  cx: 13.089px;
  cy: 5.692px;
  rx: 0.172px;
  ry: 0.087px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0l7tb9r {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
}

.llo96eq-p {
  d: path("M17.568 10.277a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.545-1.589-3.592c-1.381-1.07-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.671");
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m52_bcc9m {
  d: path("M13.208 5.524a.395.395 0 0 0-.38.499h.762a.398.398 0 0 0-.382-.499");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-63dkbfe {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M7.127 13.544c-.941-.284-1.295.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n5083tm6w {
  d: path("m16.308 3.17l.19.094a.87.87 0 0 1 .451.944l-.261 1.346c-.023.139-.115.232-.253.236h-.008s.024-.401.047-.638c.02-.191-.014-.25-.19-.424a.56.56 0 0 1-.166-.378v-.378a.255.255 0 0 0-.19-.236a7.3 7.3 0 0 0-1.733-.189c-.854 0-1.448.118-1.733.19a.23.23 0 0 0-.19.235v.378a.47.47 0 0 1-.166.378l-.071.07c-.095.071-.142.213-.142.33c.023.26.047.638.047.638h-.022a.28.28 0 0 1-.263-.236l-.26-1.345a.9.9 0 0 1 .474-.92l.19-.095c.119-.071.237-.165.356-.26l.427-.448a.87.87 0 0 1 .973-.142c.238.07.499.07.736 0c.357-.118.76-.024 1.045.236l.356.354a1 1 0 0 0 .356.26");
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.ngpy26t4k {
  fill-rule: evenodd;
  d: path("M5.25 14.667q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.129.165-.253.27-.354a2.5 2.5 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.37a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.ni5zb4boq {
  d: path("M15.112 5.607c.028.038-.03.084-.098.134c-.067.05-.116.085-.144.047c-.028-.037.003-.108.07-.158s.144-.06.172-.023");
}

.nxcp0hivj {
  stop-color: var(--svg-color--3794e2, #3794E2);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o09v1ibsc {
  d: path("M12.505 4.833v-.001l.003-.002l.005-.004l.069-.048a1.25 1.25 0 0 1 .846-.163a.236.236 0 0 1-.074.467a.78.78 0 0 0-.522.097l-.027.019a.236.236 0 0 1-.3-.365");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.of4__9yml {
  stop-color: var(--svg-color--ba917f, #BA917F);
  stop-opacity: 0;
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.oipf0m4co {
  stop-color: var(--svg-color--4861ab, #4861AB);
  stop-opacity: 0;
}

.oiy5ljb5q {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M12.505 4.833v-.001l.003-.002l.005-.004l.069-.048a1.25 1.25 0 0 1 .846-.163a.236.236 0 0 1-.074.467a.78.78 0 0 0-.522.097l-.027.019a.236.236 0 0 1-.3-.365");
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.omf6kkb4j {
  stop-color: var(--svg-color--9b686d, #9B686D);
  stop-opacity: 0;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.p-d7sqbgf {
  fill: var(--svg-color--000, #000);
  d: path("M14.915 5.919c0-.126.1-.226.226-.226a.225.225 0 0 1 .2.33h-.4a.2.2 0 0 1-.026-.104");
}

.p79aa0p9z {
  stop-color: var(--svg-color--3066bf, #3066BF);
}

.pfxo1bxwi {
  stop-color: var(--svg-color--bd9484, #BD9484);
  stop-opacity: 0;
}

.pk84u7jjf {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.748H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn5jbtt9h {
  d: path("M19.75 29.748H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.pzzto25mw {
  stop-color: var(--svg-color--bd9484, #BD9484);
}

.q2o782xwr {
  fill: var(--svg-color--000, #000);
  d: path("M13.434 5.919c0-.126-.1-.227-.226-.227a.225.225 0 0 0-.201.33h.4a.2.2 0 0 0 .027-.103");
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qd_9svrfx {
  d: path("M20.68 13.849c.256-.588.373-1.22.399-1.462l2.047.024c.046.268-.04.583-.079.703c.088.322.037.687 0 .829c-.054.225-.178.713-.238.86c-.074.183-.183.246-.348.23a.4.4 0 0 1-.148-.043a.3.3 0 0 0-.23-.018a.43.43 0 0 1-.227.018a.43.43 0 0 1-.204-.112a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.085.007-.183.002-.235-.042c-.098-.082-.219-.175.031-.746");
}

.qdnb_qbiy {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.116 5.403a.62.62 0 0 0-.6.469c-.019.077.04.15.12.15h.987a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.607-.499");
}

.qe-ha1b7i {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.404 14.139s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r-qqqqbyj {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m14.054 5.983l-.363.752c-.045.154.063.31.216.31h.326c.153 0 .26-.158.216-.31l-.22-.752c-.048-.167-.126-.167-.175 0");
}

.r0iiaeguw {
  stop-color: var(--svg-color--3168c8, #3168C8);
  stop-opacity: 0;
}

.r8fjj8bcd {
  d: path("M26.485 24.332c.981-2.278.626-3.886.055-5.013c-.474-.936-.003-1.662 1.018-1.421c.737.174 1.364.694 1.54 1.431c.721 3.025-.313 6.182-3.582 7.816c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.723 10.906-4.282");
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rrqfdbb_i {
  d: path("m15.93 3.547l-1.362.454a.463.463 0 0 0 .208.9l1.354-.182z");
}

.sf2boes3b {
  d: path("m23.469 25.327l-.422-1.143l-2.351.536l2.225 1.1a.396.396 0 0 0 .547-.493");
}

.sgu32ab0w {
  d: path("M19.837 23.012a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.siwrhab8g {
  d: path("M16.782 13.45c-.65-1.28-1.166-3.185-1.443-4.423a.714.714 0 0 1 .588-.856c.447-.075.855.271.91.722c.205 1.698.95 3.373 1.445 4.682c.578 1.531.312 1.062.234 3.515c-.057 1.782 1.266 3.25 1.813 4.11l-.407.21c-.609-.827-2.203-2.945-2.203-4.85c0-1.792.063-1.141-.937-3.11");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.szw4sibdg {
  stop-color: var(--svg-color--c5a18a, #C5A18A);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t502ec3cr {
  stop-color: var(--svg-color--4861ab, #4861AB);
}

.t5lf5ccyt {
  stop-color: var(--svg-color--5391be, #5391BE);
  stop-opacity: 0;
}

.tgz_9qxcq {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
}

.to9zfdmjz {
  stop-color: var(--svg-color--1154b9, #1154B9);
  stop-opacity: 0;
}

.toe447tsm {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.809px;
  rx: 0.299px;
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.u6gia-bos {
  stop-color: var(--svg-color--418dd5, #418DD5);
}

.uh8iu31tc {
  cx: 28.864px;
  cy: 12.813px;
  r: 1.043px;
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.uiakhkvls {
  cx: 12.074px;
  cy: 6.037px;
  r: 0.739px;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vgauzicqp {
  stop-color: var(--svg-color--3168c8, #3168C8);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vn476zbcv {
  cx: 12.074px;
  cy: 6.037px;
  r: 0.44px;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vurnokzna {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.611 14.945a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14c-.09.053-.163.111-.215.164a.5.5 0 0 0-.074.089");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.wqensyb5w {
  stop-color: var(--svg-color--8d5050, #8D5050);
}

.wvwy8egxn {
  fill-rule: evenodd;
  d: path("M5.611 14.945a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14c-.09.053-.163.111-.215.164a.5.5 0 0 0-.074.089");
}

.x8t9mcbvp {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m16.308 3.17l.19.094a.87.87 0 0 1 .451.944l-.261 1.346c-.023.139-.115.232-.253.236h-.008s.024-.401.047-.638c.02-.191-.014-.25-.19-.424a.56.56 0 0 1-.166-.378v-.378a.255.255 0 0 0-.19-.236a7.3 7.3 0 0 0-1.733-.189c-.854 0-1.448.118-1.733.19a.23.23 0 0 0-.19.235v.378a.47.47 0 0 1-.166.378l-.071.07c-.095.071-.142.213-.142.33c.023.26.047.638.047.638h-.022a.28.28 0 0 1-.263-.236l-.26-1.345a.9.9 0 0 1 .474-.92l.19-.095c.119-.071.237-.165.356-.26l.427-.448a.87.87 0 0 1 .973-.142c.238.07.499.07.736 0c.357-.118.76-.024 1.045.236l.356.354a1 1 0 0 0 .356.26");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xicqgpbmz {
  d: path("M13.569 5.872c0-.127-.104-.212-.132-.238l-.128.123l.079.16z");
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xtqzqnbwf {
  stop-color: var(--svg-color--c9a38e, #C9A38E);
}

.xy8jbrbcm {
  fill-rule: evenodd;
  d: path("M5.404 14.139s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.xzkoa2bwe {
  d: path("M10.684 11.696c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.032c.3-.028 1.148-.11 2.5-.72c1.679-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.y-2lu0bml {
  fill-rule: evenodd;
  d: path("M7.127 13.544c-.941-.284-1.295.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y60usm6nn {
  stop-color: var(--svg-color--46a5ef, #46A5EF);
}

.y79whbcii {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("m21.985 27.333l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.yq2gz16ay {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m14.006 5.91l-.235.753a.24.24 0 0 0 .23.309h.348a.24.24 0 0 0 .23-.31l-.234-.752c-.05-.166-.286-.166-.339 0");
}

.yrtrc6n_d {
  stop-color: var(--svg-color--54acfa, #54ACFA);
}

.yt1ay9nnj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.112 5.607c.028.038-.03.084-.098.134c-.067.05-.116.085-.144.047c-.028-.037.003-.108.07-.158s.144-.06.172-.023");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yx-2ufqaz {
  d: path("M15.492 5.867a.37.37 0 0 0-.102-.205l-.115.126l.052.101z");
}

.z0pxpnkbw {
  d: path("m21.985 27.333l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zrzxj2epv {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
  stop-opacity: 0;
}

.zvqcq9hxr {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
  stop-opacity: 0;
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
