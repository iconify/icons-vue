<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ipxqfNb)" class="c5pyn6kwp"/><path fill="url(#ixtGmqe)" class="c5pyn6kwp"/><path fill="url(#iu4BL0y)" class="c5pyn6kwp"/><path fill="url(#i6kQckA)" class="c5pyn6kwp"/><path fill="url(#ivcbSbu)" class="d42a8nbyx"/><path fill="url(#imxslwc)" class="d42a8nbyx"/><path fill="url(#iCIPAvc)" class="sy7gbya4q"/><path fill="url(#ib2sn4d)" class="sy7gbya4q"/><g filter="url(#i4m42Pe)"><path fill="url(#i6aJFZY)" class="cd8uxyblt"/><path fill="url(#izDA0dI)" class="cd8uxyblt"/></g><g filter="url(#iJXkQOd)"><path class="v7lobvb0w"/><path fill="url(#i4dkT0d)" class="blsopp2mg"/><path fill="url(#izjH7xz)" class="blsopp2mg"/></g><g filter="url(#ifHtJSb)"><ellipse transform="rotate(-40.534 9.937 22.243)" class="si-u7d6wp"/></g><ellipse fill="url(#iuxxmBb)" transform="rotate(-40.534 9.886 22.154)" class="fvifkjh5i"/><g filter="url(#i4klz1d)"><ellipse transform="scale(-1 1)rotate(-35.343 23.849 45.555)" class="n11xmqb_x"/></g><ellipse fill="url(#imtwsXc)" transform="scale(-1 1)rotate(-40.534 18.954 40.982)" class="tto44ccna"/><g filter="url(#iC7o3sd)"><rect fill="url(#i1U54LR)" class="qyeoy6a8h"/><rect fill="url(#iZgh3lf)" class="qyeoy6a8h"/><rect fill="url(#izJ86Ne)" class="qyeoy6a8h"/></g><rect fill="url(#ifOw8lB)" class="gx_0zqbtq"/><path fill="url(#iYKVIWb)" class="g4mvl20po"/><path fill="url(#iDWpPDG)" class="g4mvl20po"/><g filter="url(#iYIJfHb)"><circle class="wfn54lnxd"/></g><g filter="url(#iYrgOxb)"><circle class="a1tpsrb8u"/></g><circle fill="url(#iYFehJc)" class="sx6q1cbyi"/><circle fill="url(#iO6rBqd)" class="cad66eb8i"/><g filter="url(#iYxTUnd)"><circle fill="url(#iekohHc)" class="lh4xl0bxs"/></g><circle fill="url(#iILiadc)" class="lh4xl0bxs"/><g filter="url(#ibduEpe)"><circle fill="url(#iN9Kcec)" class="l9th14n1d"/></g><g filter="url(#iwXw5Ld)"><circle fill="url(#ivxuRWc)" class="hw65bgp2j"/><circle fill="url(#ik2QEae)" class="hw65bgp2j"/></g><g filter="url(#i2Szpfd)"><circle class="imp0-jbzq"/><circle fill="url(#itF0Byb)" class="wn02wrbvt"/><circle fill="url(#ioJALEc)" class="wn02wrbvt"/></g><g filter="url(#iSUD67c)"><path fill="url(#iKsp0Tm)" class="lyn55lmhm"/><path fill="url(#iGSFeie)" class="lyn55lmhm"/><path fill="url(#itdoSBb)" class="lyn55lmhm"/><path fill="url(#igZ4Aac)" class="lyn55lmhm"/><path fill="url(#iEMaqyd)" class="lyn55lmhm"/></g><g filter="url(#iG88Z3B)"><path class="s36e0-b_e"/><path fill="url(#isvsGJe)" class="m68ylvspc"/><path fill="url(#ifepKFc)" class="m68ylvspc"/><path fill="url(#ifiLxpc)" class="m68ylvspc"/><path fill="url(#iAp9ZKe)" class="m68ylvspc"/></g><g filter="url(#izNQrBM)"><path class="f817-g_rw"/></g><g filter="url(#i2EXFgB)"><path class="hh53gdc4l"/><path fill="url(#i6Rg7ld)" class="o08v7cb5v"/><path fill="url(#iRLjuHc)" class="o08v7cb5v"/><path fill="url(#itCPxKe)" class="o08v7cb5v"/><path fill="url(#ircZloc)" class="o08v7cb5v"/></g><g filter="url(#icn1CWc)"><path fill="url(#iOkoTWd)" class="cwuef7bmx"/></g><g filter="url(#iURGvhv)"><path stroke="url(#iWND1gd)" class="z_hxycc8e"/></g><path stroke="url(#iWND1gd)" class="fjwb7eblc"/><path class="i02jz1bnq"/><path fill="url(#i2NGHCe)" class="ihl-fzbcv"/><path class="l_fnucc9q"/><g filter="url(#is9l64Z)"><path class="gvhd_9huw"/><path fill="url(#iHejvCl)" class="j5rytg2vr"/></g><g filter="url(#itjJsNb)"><path fill="url(#i4yskZd)" class="tcmn0bb7c"/></g><path class="u2yl_lbks"/><path fill="url(#izOlAAc)" class="z8ztl_bzw"/><path class="brnauob5m"/><g filter="url(#idt4LEd)"><path fill="url(#iT4dx9b)" class="pfkypgbdb"/></g><g filter="url(#iv2KTIz)"><ellipse transform="rotate(-27.914 13.536 14.484)" class="erwrlcchs"/><ellipse fill="url(#i1dS4ke)" transform="rotate(-27.914 13.536 14.484)" class="fdcc15cyn"/></g><g filter="url(#i50FBdb)"><path fill="url(#il1AcPe)" class="gw4u-ub3u"/><path fill="url(#is0vYcc)" class="gw4u-ub3u"/></g><path fill="url(#iWLVOVc)" class="gw4u-ub3u"/><path fill="url(#i2pBBLt)" class="gw4u-ub3u"/><path fill="url(#isYcgqc)" class="gw4u-ub3u"/><g filter="url(#i5fDw4X)"><path fill="url(#iU1wwRb)" class="sfe148-0e"/><path fill="url(#iqjjYJa)" class="sfe148-0e"/><path fill="url(#iyBJvOb)" class="sfe148-0e"/></g><defs><radialGradient id="ipxqfNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71875 -19.3424 0 16 26.99)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="u2-vnsrzx"/><stop offset="1" class="u25v0cb4e"/></radialGradient><radialGradient id="ixtGmqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 0 0 -8.81836 22.928 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="hztqsacfn"/><stop offset="1" class="g15tcgc_e"/></radialGradient><radialGradient id="ivcbSbu" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 -8.07812 2.82155 .68765 6.74 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="y6ictpbdv"/><stop offset="1" class="exer9ybqp"/></radialGradient><radialGradient id="iCIPAvc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.449 24.978 4.727)scale(7.55662 1.96679)" gradientUnits="userSpaceOnUse"><stop class="z2ubpb-up"/><stop offset="1" class="icppbwd3b"/></radialGradient><radialGradient id="ib2sn4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.366 .65507 0 22.942 29.911)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="p9dhe0cfb"/><stop offset="1" class="m7r_2tbtp"/></radialGradient><radialGradient id="i6aJFZY" cx="0" cy="0" r="1" gradientTransform="matrix(1.35937 1.64062 -3.29137 2.72714 9.71 21.208)" gradientUnits="userSpaceOnUse"><stop class="tuvqdtb4j"/><stop offset="1" class="mw-6yhbvl"/></radialGradient><radialGradient id="izDA0dI" cx="0" cy="0" r="1" gradientTransform="matrix(1.78125 1.85937 -.47826 .45816 8.381 22.458)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="aok9j0bwd"/><stop offset="1" class="ul3ws4blr"/></radialGradient><radialGradient id="i4dkT0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 .25 -.73637 3.86594 19.569 21.146)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="wcylmi-4x"/><stop offset="1" class="lcybi9bke"/></radialGradient><radialGradient id="izjH7xz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 1.09375 -.16383 -.18256 23.498 22.2)" gradientUnits="userSpaceOnUse"><stop class="dwh48tz1p"/><stop offset="1" class="b5_53rm9x"/></radialGradient><radialGradient id="iuxxmBb" cx="0" cy="0" r="1" gradientTransform="rotate(-169.136 6.388 10.772)scale(1.64141 .91814)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="k5s0mt74t"/><stop offset="1" class="hfobxebps"/></radialGradient><radialGradient id="imtwsXc" cx="0" cy="0" r="1" gradientTransform="matrix(.678 .80592 -1.4278 1.20118 .1 .257)" gradientUnits="userSpaceOnUse"><stop class="w_-x-cc4i"/><stop offset="1" class="xbkp5vbln"/></radialGradient><radialGradient id="i1U54LR" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68749 -3.76563 4.9287 -3.51755 18.1 23.911)" gradientUnits="userSpaceOnUse"><stop class="mg6vw6bqp"/><stop offset="1" class="f_x1tcb5s"/></radialGradient><radialGradient id="iZgh3lf" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 0 0 -.91123 15.538 23.763)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="w_5lucbuv"/><stop offset="1" class="x_olikxjr"/></radialGradient><radialGradient id="izJ86Ne" cx="0" cy="0" r="1" gradientTransform="rotate(112.38 -.17 15.586)scale(1.14905 2.6882)" gradientUnits="userSpaceOnUse"><stop class="ay981bbmw"/><stop offset="1" class="co8373ibr"/></radialGradient><radialGradient id="ifOw8lB" cx="0" cy="0" r="1" gradientTransform="rotate(51.989 -14.741 27.087)scale(1.72534 2.83656)" gradientUnits="userSpaceOnUse"><stop class="ujpokubdf"/><stop offset="1" class="op1k02bbd"/></radialGradient><radialGradient id="iYFehJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 25.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iO6rBqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 .59375 -.75915 -.91896 17.85 28.161)" gradientUnits="userSpaceOnUse"><stop class="x2r0w67qw"/><stop offset="1" class="e2y-fbcxj"/></radialGradient><radialGradient id="iekohHc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.574 15.262)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iILiadc" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 10.03 5.538)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="ik2QEae" cx="0" cy="0" r="1" gradientTransform="matrix(.82664 -.60191 .687 .9435 21.128 14.996)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="itF0Byb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.715 16.083)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="ioJALEc" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -8.179 32.868)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iKsp0Tm" cx="0" cy="0" r="1" gradientTransform="rotate(179.1 9.729 8.832)scale(6.0722 6.32398)" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset=".96" class="ixdockwro"/></radialGradient><radialGradient id="iGSFeie" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.21875 -10.5193 0 16.02 14.231)" gradientUnits="userSpaceOnUse"><stop offset=".823" class="nn0q-1ypw"/><stop offset="1" class="ax1l5lbnm"/></radialGradient><radialGradient id="itdoSBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.337 13.99)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="igZ4Aac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.78 14.125)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="isvsGJe" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 17.425 -7.664)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="ifepKFc" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -93 207.71)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="ifiLxpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.94 6.661)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iAp9ZKe" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.492 13.479)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="ircZloc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.319 16.869)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="i2NGHCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.17 14.58)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iHejvCl" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.942 14.664)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izOlAAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.807 14.58)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1dS4ke" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.045 .744)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWLVOVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.3535 18.2706 0 15.953 14.155)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="guwslmx9m"/><stop offset="1" class="csva0fh9x"/></radialGradient><radialGradient id="i2pBBLt" cx="0" cy="0" r="1" gradientTransform="rotate(-179.736 10.798 2.33)scale(6.78132 1.9151)" gradientUnits="userSpaceOnUse"><stop class="ak4i8vy1v"/><stop offset="1" class="d0nv29baz"/></radialGradient><radialGradient id="iyBJvOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46875 -.51569 0 21.381 16.27)" gradientUnits="userSpaceOnUse"><stop class="qqll8tbvj"/><stop offset="1" class="i1pxvjzop"/></radialGradient><filter id="i4m42Pe" width="4.755" height="3.491" x="8.464" y="20.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/></filter><filter id="iJXkQOd" width="4.705" height="3.591" x="18.753" y="19.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.0666667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2845" result="effect2_innerShadow_4002_2845"/></filter><filter id="ifHtJSb" width="2.189" height="2.153" x="8.842" y="21.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".25"/></filter><filter id="i4klz1d" width="1.692" height="1.595" x="21.111" y="21.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".125"/></filter><filter id="iC7o3sd" width="7.744" height="9.694" x="12.072" y="14.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2845" result="effect2_innerShadow_4002_2845"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.172549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2845" result="effect3_innerShadow_4002_2845"/></filter><filter id="iYIJfHb" width="2.09" height="2.09" x="16.395" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".25"/></filter><filter id="iYrgOxb" width="2.09" height="2.09" x="16.395" y="27.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".25"/></filter><filter id="iYxTUnd" width="3.539" height="3.339" x="9.574" y="13.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/></filter><filter id="ibduEpe" width="2.99" height="2.99" x="9.749" y="13.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".25"/></filter><filter id="iwXw5Ld" width="3.589" height="3.589" x="19.087" y="13.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/></filter><filter id="i2Szpfd" width="2.99" height="2.99" x="19.261" y="13.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".25"/></filter><filter id="iSUD67c" width="10.973" height="12.627" x="10.234" y="9.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.65" dy="-.65"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.262745 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.294118 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2845" result="effect2_innerShadow_4002_2845"/></filter><filter id="iG88Z3B" width="12.601" height="8.543" x="9.64" y="6.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/></filter><filter id="izNQrBM" width="3.26" height="4.181" x="14.122" y="14.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".375"/></filter><filter id="i2EXFgB" width="2.377" height="3.181" x="14.803" y="14.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".125"/></filter><filter id="icn1CWc" width="2.377" height="3.181" x="14.803" y="14.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".125"/></filter><filter id="iURGvhv" width="3.617" height="1.472" x="14.183" y="17.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".05"/></filter><filter id="is9l64Z" width=".787" height=".696" x="17.436" y="14.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".05"/></filter><filter id="itjJsNb" width=".891" height=".913" x="18.276" y="14.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".1"/></filter><filter id="idt4LEd" width=".986" height="1.04" x="13.834" y="14.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".1"/></filter><filter id="iv2KTIz" width=".913" height=".704" x="13.08" y="14.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2845" stdDeviation=".05"/></filter><filter id="i50FBdb" width="13.655" height="12.317" x="9.076" y="1.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.203922 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/></filter><filter id="i5fDw4X" width="10.882" height="7.996" x="10.499" y="14.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.635294 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2845"/></filter><linearGradient id="iu4BL0y" x1="9.026" x2="9.233" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="g-00mbcgn"/><stop offset="1" class="tvzw53atw"/></linearGradient><linearGradient id="i6kQckA" x1="22.975" x2="22.827" y1="29.911" y2="29.911" gradientUnits="userSpaceOnUse"><stop offset=".118" class="yacpd-mqw"/><stop offset="1" class="m2jbcqdpu"/></linearGradient><linearGradient id="imxslwc" x1="9.397" x2="8.084" y1="29.739" y2="29.739" gradientUnits="userSpaceOnUse"><stop class="s2ol_bbam"/><stop offset="1" class="hm-si4p_s"/></linearGradient><linearGradient id="iYKVIWb" x1="15.984" x2="15.984" y1="23.197" y2="29.911" gradientUnits="userSpaceOnUse"><stop class="ty59qw5cn"/><stop offset="1" class="jwfvhhlnv"/></linearGradient><linearGradient id="iDWpPDG" x1="16.479" x2="16.147" y1="27.271" y2="27.271" gradientUnits="userSpaceOnUse"><stop class="z_332kbzw"/><stop offset="1" class="v6fzn4zbl"/></linearGradient><linearGradient id="iN9Kcec" x1="11.244" x2="10.603" y1="15.541" y2="15.541" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="ivxuRWc" x1="21.843" x2="21.024" y1="14.17" y2="16.706" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iEMaqyd" x1="16.02" x2="16.02" y1="14.044" y2="15.137" gradientUnits="userSpaceOnUse"><stop class="cceit3nrw"/><stop offset="1" class="pm9me4b9m"/></linearGradient><linearGradient id="i6Rg7ld" x1="15.127" x2="16.065" y1="16.311" y2="16.311" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iRLjuHc" x1="16.93" x2="15.904" y1="16.633" y2="16.619" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="itCPxKe" x1="16.186" x2="16.186" y1="17.375" y2="16.803" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iOkoTWd" x1="15.991" x2="16.282" y1="14.531" y2="16.177" gradientUnits="userSpaceOnUse"><stop class="yq-cuzaub"/><stop offset="1" class="k4qwmtixx"/></linearGradient><linearGradient id="iWND1gd" x1="14.954" x2="15.389" y1="18.99" y2="18.303" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="i4yskZd" x1="18.948" x2="18.634" y1="14.634" y2="14.827" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iT4dx9b" x1="14.551" x2="14.237" y1="14.634" y2="14.827" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="il1AcPe" x1="19.866" x2="12.584" y1="11.708" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="j8rdzr3lb"/><stop offset=".554" class="h5foydtlz"/><stop offset="1" class="roy3-sbpo"/></linearGradient><linearGradient id="is0vYcc" x1="9.709" x2="12.428" y1="11.989" y2="11.989" gradientUnits="userSpaceOnUse"><stop class="bamb_e30h"/><stop offset="1" class="szoje-bkc"/></linearGradient><linearGradient id="isYcgqc" x1="16.538" x2="16.538" y1="14.155" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="ip1t-iw4f"/><stop offset="1" class="l0ic_xblz"/></linearGradient><linearGradient id="iU1wwRb" x1="21.116" x2="15.022" y1="18.489" y2="18.489" gradientUnits="userSpaceOnUse"><stop class="it4bksbcb"/><stop offset="1" class="twe7w31pl"/></linearGradient><linearGradient id="iqjjYJa" x1="15.941" x2="15.941" y1="13.927" y2="16.029" gradientUnits="userSpaceOnUse"><stop class="x-67tmbrg"/><stop offset="1" class="bkz397hyg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-guard-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a1tpsrb8u {
  cx: 17.439px;
  cy: 28.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.ak4i8vy1v {
  stop-color: var(--svg-color--686070, #686070);
}

.aok9j0bwd {
  stop-color: var(--svg-color--4b4551, #4B4551);
}

.ax1l5lbnm {
  stop-color: var(--svg-color--a26381, #A26381);
}

.ay981bbmw {
  stop-color: var(--svg-color--452139, #452139);
}

.b5_53rm9x {
  stop-color: var(--svg-color--5e5864, #5E5864);
  stop-opacity: 0;
}

.bamb_e30h {
  stop-color: var(--svg-color--4d4c50, #4D4C50);
}

.bkz397hyg {
  stop-color: var(--svg-color--c7aed9, #C7AED9);
  stop-opacity: 0;
}

.blsopp2mg {
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.brnauob5m {
  fill: var(--svg-color--000, #000);
  d: path("M14.316 14.995a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.904a.5.5 0 0 0 .061-.235");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c5pyn6kwp {
  d: path("M5.428 29.911h21.144c-.19-5.356-4.591-9.64-9.994-9.64h-1.156c-5.403 0-9.805 4.284-9.994 9.64");
}

.cad66eb8i {
  cx: 17.494px;
  cy: 28.374px;
  r: 0.545px;
}

.cceit3nrw {
  stop-color: var(--svg-color--7f4c55, #7F4C55);
}

.cd8uxyblt {
  d: path("M11.926 20.161c-1.363.418-2.538 1.308-3.179 1.936a.46.46 0 0 0 .011.659l.65.649a.523.523 0 0 0 .705.02a12.3 12.3 0 0 1 3.106-1.857z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.co8373ibr {
  stop-color: var(--svg-color--452139, #452139);
  stop-opacity: 0;
}

.csva0fh9x {
  stop-color: var(--svg-color--403947, #403947);
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cwuef7bmx {
  d: path("m15.61 14.813l-.532 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.d0nv29baz {
  stop-color: var(--svg-color--686070, #686070);
  stop-opacity: 0;
}

.d42a8nbyx {
  d: path("M9.058 29.911h-3.63a9.98 9.98 0 0 1 3.63-7.355z");
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dwh48tz1p {
  stop-color: var(--svg-color--5e5864, #5E5864);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2y-fbcxj {
  stop-color: var(--svg-color--fca239, #FCA239);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.erwrlcchs {
  cx: 13.536px;
  cy: 14.484px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.exer9ybqp {
  stop-color: var(--svg-color--b13b50, #B13B50);
}

.f_x1tcb5s {
  stop-color: var(--svg-color--482949, #482949);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f817-g_rw {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.716 15.14l-.82 1.7c-.102.35.142.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.699c-.107-.377-.283-.377-.395 0");
}

.fdcc15cyn {
  cx: 13.536px;
  cy: 14.484px;
  rx: 0.389px;
  ry: 0.197px;
}

.fjwb7eblc {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.63 18.02v-.001h-.001a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24c.344.52.943.867 1.624.867s1.281-.347 1.625-.868a.19.19 0 0 0-.021-.241a.2.2 0 0 0-.241-.04a2.94 2.94 0 0 1-1.363.323c-.5 0-.968-.118-1.362-.323Z");
}

.ft5dv1b6b {
  fill: none;
}

.fvifkjh5i {
  cx: 9.886px;
  cy: 22.154px;
  rx: 0.641px;
  ry: 0.524px;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g-00mbcgn {
  stop-color: var(--svg-color--c2254a, #C2254A);
}

.g15tcgc_e {
  stop-color: var(--svg-color--ff6085, #FF6085);
  stop-opacity: 0;
}

.g4mvl20po {
  d: path("M15.49 23.203v6.708h.989v-6.714a2 2 0 0 1-.409.042h-.203q-.194 0-.377-.036");
}

.guwslmx9m {
  stop-color: var(--svg-color--403947, #403947);
  stop-opacity: 0;
}

.gvhd_9huw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.106 14.292c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.388-.05");
}

.gw4u-ub3u {
  d: path("M10.31 14.155c-.278-.016-.842-.08-1.054-.728c-.11-.37.082-.779.143-.91l.004-.008l.02-.04c.061-.121.152-.298-.02-.578c-.193-.313-.375-.615-.045-1.257c.207-.405.093-.652-.032-.875c-.183-.327-.166-.604 0-.938c.07-.143.173-.275.173-.472c0-.198-.07-.335-.141-.474c-.074-.143-.148-.289-.148-.504c0-.23.084-.398.161-.554c.066-.133.128-.257.128-.402c0-.129-.06-.24-.125-.364c-.094-.178-.201-.38-.164-.69c.071-.59.537-.787.756-.879l.02-.008c.21-.089.364-.163.452-.58c.046-.215.132-.502.293-.663a1.06 1.06 0 0 1 .791-.3c.257.007.535-.03.752-.254c.217-.225.458-.413.699-.453s.471.014.725.144c.281.145.567.07.705-.035c.34-.262.718-.32 1.158-.141c.18.072.295.112.394.112c.098 0 .214-.04.393-.112c.44-.18.819-.12 1.159.141a.68.68 0 0 0 .704.035c.254-.13.484-.184.725-.144s.483.228.7.453s.494.261.75.253a1.06 1.06 0 0 1 .793.301c.16.161.246.448.292.663c.088.417.243.491.452.58l.02.008c.219.092.685.288.756.878c.038.31-.07.513-.164.69c-.065.124-.125.236-.125.365c0 .145.062.269.128.402c.078.156.161.324.161.554c0 .215-.074.36-.147.504a.94.94 0 0 0-.105.466c0 .528.496.742.176 1.422c-.125.223-.324.455-.117.86c.33.641.193.955 0 1.268c-.171.28-.081.457-.02.577l.02.041l.005.009c.06.13.252.54.142.909c-.212.649-.775.712-1.054.728z");
}

.gx_0zqbtq {
  width: 4.141px;
  height: 5.141px;
  x: 13.898px;
  y: 18.099px;
  rx: 1.969px;
}

.h5foydtlz {
  stop-color: var(--svg-color--4b3c5b, #4B3C5B);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hfobxebps {
  stop-color: var(--svg-color--dcb144, #DCB144);
}

.hh53gdc4l {
  fill: var(--svg-color--986c65, #986C65);
  d: path("m15.61 14.977l-.532 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.hm-si4p_s {
  stop-color: var(--svg-color--c9345b, #C9345B);
  stop-opacity: 0;
}

.hw65bgp2j {
  cx: 20.756px;
  cy: 15.262px;
  r: 1.669px;
}

.hztqsacfn {
  stop-color: var(--svg-color--ff6085, #FF6085);
}

.i02jz1bnq {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.379 13.831c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.i1pxvjzop {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
  stop-opacity: 0;
}

.icppbwd3b {
  stop-color: var(--svg-color--e34c67, #E34C67);
}

.ihl-fzbcv {
  d: path("M18.172 14.103a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.imp0-jbzq {
  cx: 20.756px;
  cy: 15.262px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.ip1t-iw4f {
  stop-color: var(--svg-color--462659, #462659);
}

.it4bksbcb {
  stop-color: var(--svg-color--dfc6ed, #DFC6ED);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j5rytg2vr {
  d: path("M18.106 14.292c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.388-.05");
}

.j8rdzr3lb {
  stop-color: var(--svg-color--5d536a, #5D536A);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jwfvhhlnv {
  stop-color: var(--svg-color--d8bbeb, #D8BBEB);
}

.k4qwmtixx {
  stop-color: var(--svg-color--8b5d5e, #8B5D5E);
  stop-opacity: 0;
}

.k5s0mt74t {
  stop-color: var(--svg-color--cc981a, #CC981A);
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.l_fnucc9q {
  fill: var(--svg-color--000, #000);
  d: path("M17.661 14.995c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.061-.235");
}

.l0ic_xblz {
  stop-color: var(--svg-color--462659, #462659);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9th14n1d {
  cx: 11.244px;
  cy: 15.262px;
  r: 0.995px;
}

.lcybi9bke {
  stop-color: var(--svg-color--513f4e, #513F4E);
  stop-opacity: 0;
}

.lh4xl0bxs {
  cx: 11.244px;
  cy: 15.262px;
  r: 1.669px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lyn55lmhm {
  d: path("M10.892 14.65h.049s-.054-.852-.107-1.439c0-.267.107-.587.321-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.266.429.533v.853c0 .32.16.64.375.853c.502.352.47.546.43.96c-.055.534-.108 1.44-.108 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.m2jbcqdpu {
  stop-color: var(--svg-color--fc356b, #FC356B);
  stop-opacity: 0;
}

.m68ylvspc {
  d: path("m20.759 8.785l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.106.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.595-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.43-.213c.267-.16.536-.374.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.m7r_2tbtp {
  stop-color: var(--svg-color--ee5076, #EE5076);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg6vw6bqp {
  stop-color: var(--svg-color--5d4364, #5D4364);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mw-6yhbvl {
  stop-color: var(--svg-color--382834, #382834);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n11xmqb_x {
  fill: var(--svg-color--3e3138, #3E3138);
  rx: 0.641px;
  ry: 0.494px;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nn0q-1ypw {
  stop-color: var(--svg-color--a26381, #A26381);
  stop-opacity: 0;
}

.o08v7cb5v {
  d: path("m15.61 14.977l-.532 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op1k02bbd {
  stop-color: var(--svg-color--ac7879, #AC7879);
}

.p9dhe0cfb {
  stop-color: var(--svg-color--e11c59, #E11C59);
}

.pfkypgbdb {
  d: path("M14.62 14.89c0-.288-.234-.48-.297-.538l-.289.279l.178.36z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm9me4b9m {
  stop-color: var(--svg-color--7f4c55, #7F4C55);
  stop-opacity: 0;
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qqll8tbvj {
  stop-color: var(--svg-color--f6dcf7, #F6DCF7);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qyeoy6a8h {
  width: 7.594px;
  height: 9.594px;
  x: 12.172px;
  y: 14.927px;
  rx: 3.797px;
}

.roy3-sbpo {
  stop-color: var(--svg-color--393341, #393341);
}

.s2ol_bbam {
  stop-color: var(--svg-color--ac394e, #AC394E);
}

.s36e0-b_e {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m20.759 8.785l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.106.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.595-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.43-.213c.267-.16.536-.374.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.sfe148-0e {
  d: path("m10.5 14.156l.12 3.518c.082 2.424 2.07 4.378 4.497 4.378h1.677c2.44 0 4.436-1.976 4.498-4.416l.09-3.48h-.909l-.12 3.48c-.049 1.898-1.661 3.486-3.56 3.486h-1.676c-1.887 0-3.489-1.597-3.553-3.482l-.09-3.485z");
}

.si-u7d6wp {
  cx: 9.937px;
  cy: 22.243px;
  fill: var(--svg-color--321f22, #321F22);
  rx: 0.641px;
  ry: 0.524px;
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

.sx6q1cbyi {
  cx: 17.494px;
  cy: 25.374px;
  r: 0.545px;
}

.sy7gbya4q {
  d: path("M22.942 29.911h3.63a9.98 9.98 0 0 0-3.63-7.355z");
}

.szoje-bkc {
  stop-color: var(--svg-color--393341, #393341);
  stop-opacity: 0;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.tcmn0bb7c {
  d: path("M18.967 14.878a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tto44ccna {
  rx: 0.641px;
  ry: 0.524px;
}

.tuvqdtb4j {
  stop-color: var(--svg-color--454048, #454048);
}

.tvzw53atw {
  stop-color: var(--svg-color--c2254a, #C2254A);
  stop-opacity: 0;
}

.twe7w31pl {
  stop-color: var(--svg-color--c9b0d8, #C9B0D8);
}

.ty59qw5cn {
  stop-color: var(--svg-color--dbb8dd, #DBB8DD);
}

.u2-vnsrzx {
  stop-color: var(--svg-color--f73c71, #F73C71);
}

.u25v0cb4e {
  stop-color: var(--svg-color--d6274f, #D6274F);
}

.u2yl_lbks {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.598 13.831c-.653 0-1.204.45-1.354 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.ujpokubdf {
  stop-color: var(--svg-color--955268, #955268);
}

.ul3ws4blr {
  stop-color: var(--svg-color--4b4551, #4B4551);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v6fzn4zbl {
  stop-color: var(--svg-color--eacceb, #EACCEB);
  stop-opacity: 0;
}

.v7lobvb0w {
  fill: var(--svg-color--554b59, #554B59);
  d: path("M20.046 20.161c1.364.418 2.538 1.308 3.179 1.936a.46.46 0 0 1-.011.659l-.65.649a.523.523 0 0 1-.704.02a12.3 12.3 0 0 0-3.107-1.857z");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.w_-x-cc4i {
  stop-color: var(--svg-color--ffff50, #FFFF50);
}

.w_5lucbuv {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.wcylmi-4x {
  stop-color: var(--svg-color--513f4e, #513F4E);
}

.wfn54lnxd {
  cx: 17.439px;
  cy: 25.445px;
  r: 0.545px;
  fill: var(--svg-color--f6265e, #F6265E);
}

.wn02wrbvt {
  cx: 20.756px;
  cy: 15.262px;
  r: 0.995px;
}

.x_olikxjr {
  stop-color: var(--svg-color--4a2e4f, #4A2E4F);
  stop-opacity: 0;
}

.x-67tmbrg {
  stop-color: var(--svg-color--b593cf, #B593CF);
}

.x2r0w67qw {
  stop-color: var(--svg-color--fff153, #FFF153);
}

.xbkp5vbln {
  stop-color: var(--svg-color--f6cf1c, #F6CF1C);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.y6ictpbdv {
  stop-color: var(--svg-color--e43669, #E43669);
}

.yacpd-mqw {
  stop-color: var(--svg-color--fc356b, #FC356B);
}

.yq-cuzaub {
  stop-color: var(--svg-color--8b5d5e, #8B5D5E);
}

.z_332kbzw {
  stop-color: var(--svg-color--eacceb, #EACCEB);
}

.z_hxycc8e {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.991 18.392c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.846c.086-.129-.06-.278-.198-.209c-.4.21-.872.329-1.385.329Z");
}

.z2ubpb-up {
  stop-color: var(--svg-color--ff5c85, #FF5C85);
}

.z8ztl_bzw {
  d: path("M13.805 14.103a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

</style>
