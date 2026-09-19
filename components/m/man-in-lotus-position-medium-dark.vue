<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i2B084d)" clip-rule="evenodd" class="y4mwd1bkm"/><path fill="url(#iR0mKWd)" clip-rule="evenodd" class="rdws5abmr"/><g filter="url(#i4R3o4r)"><path fill="url(#ikaW3EK)" class="ayf_0ac_e"/><path fill="url(#iv0XUac)" class="ayf_0ac_e"/></g><path fill="url(#ie9mQjc)" class="n5bh3rbpi"/><path fill="url(#i7oHMle)" class="n5bh3rbpi"/><g filter="url(#ibGHmYQ)"><path class="mb6emvl-w"/></g><path fill="url(#iyXixie)" class="kt3l5zbkg"/><path fill="url(#i7ikXJe)" class="kt3l5zbkg"/><path fill="url(#i29oqne)" class="u_-l4nigi"/><path fill="url(#i5tGS2d)" class="u_-l4nigi"/><path fill="url(#iEC0VzV)" class="u_-l4nigi"/><path fill="url(#isLizxd)" class="h3ryqpb5c"/><path fill="url(#iXOs4ie)" class="h3ryqpb5c"/><path fill="url(#idT07lC)" class="h3ryqpb5c"/><path class="yvq2fpben"/><path fill="url(#iBn2sib)" class="ao0j51bbd"/><path fill="url(#igA15hd)" class="ao0j51bbd"/><path fill="url(#idETd5b)" class="ao0j51bbd"/><g filter="url(#iOK4XYc)"><path class="c8ua0_dop"/><path fill="url(#iGFe9Gb)" class="ifpl6ybzj"/><path fill="url(#iwc2NVc)" class="ifpl6ybzj"/><path fill="url(#i3XftSc)" class="ifpl6ybzj"/></g><g filter="url(#iSPyVRd)"><path fill="url(#inCCwUc)" class="usytz5beo"/></g><path fill="url(#ivCaO8b)" class="kgi5hcc7r"/><path fill="url(#isP2xWd)" class="kgi5hcc7r"/><g filter="url(#iD6xqGc)"><path fill="url(#ikiKFvd)" class="a9xl-ibwm"/><path fill="url(#i2Vclfd)" class="a9xl-ibwm"/></g><path fill="url(#iaLdVZu)" class="a9xl-ibwm"/><path clip-rule="evenodd" class="q_mhuob6r"/><path fill="url(#iAkrPOb)" clip-rule="evenodd" class="ntdx2vbfn"/><path clip-rule="evenodd" class="dodmiac3i"/><path fill="url(#is178he)" clip-rule="evenodd" class="n8fmpbc6x"/><path clip-rule="evenodd" class="psr8zvxxq"/><path fill="url(#iHur8ZY)" clip-rule="evenodd" class="xhp-7db0c"/><path clip-rule="evenodd" class="iu836jppc"/><path fill="url(#iXxjsrR)" clip-rule="evenodd" class="af35w8x4b"/><path clip-rule="evenodd" class="jh45d3v4x"/><path fill="url(#i10Eklc)" clip-rule="evenodd" class="rw_gd1bje"/><path clip-rule="evenodd" class="jd2r4hb6j"/><path fill="url(#i7HxqFd)" clip-rule="evenodd" class="ip9j-lbln"/><path clip-rule="evenodd" class="o-6cv1fhy"/><path fill="url(#ikD3dGb)" clip-rule="evenodd" class="ebmu0looz"/><path fill="url(#i78hAQc)" clip-rule="evenodd" class="ybnd2o6or"/><path fill="url(#iZ67Rue)" clip-rule="evenodd" class="ybnd2o6or"/><g filter="url(#igkaWcb)"><path class="kzh2qubat"/></g><g filter="url(#ihDD4Yc)"><path class="lqaxw_boi"/></g><g filter="url(#iib5BFf)"><path class="rftfblbbu"/></g><g filter="url(#iUbkWic)"><path class="ktp9-quqg"/></g><g filter="url(#iyNOUBJ)"><path class="j-k11ibbx"/></g><g filter="url(#iVsgcAb)"><path class="ydx8zzb-s"/></g><g filter="url(#ipAd6Ne)"><path class="lb4q4qx8j"/></g><g filter="url(#ieyye1d)"><path class="ir55m1boa"/></g><g filter="url(#iwPPTVb)"><circle fill="url(#iVHjY3d)" class="ypfzj4hjr"/></g><g filter="url(#ivwz2ab)"><circle fill="url(#iCwYaOc)" class="tbru6-b6h"/></g><g filter="url(#i5Wmydd)"><circle fill="url(#isBcb6G)" class="d42ciobst"/><circle fill="url(#iDKbTbS)" class="d42ciobst"/></g><g filter="url(#iHyM6Jc)"><circle class="pap7mydzq"/><circle fill="url(#iW52Wvd)" class="e2ftv_b9f"/><circle fill="url(#iqBubZb)" class="e2ftv_b9f"/></g><g filter="url(#iq8zPfc)"><path fill="url(#itW1b2b)" class="eejimub8z"/><path fill="url(#iBE61nd)" class="eejimub8z"/><path fill="url(#iuuh5sd)" class="eejimub8z"/></g><path fill="url(#iitdbue)" class="zd7wcdy4b"/><path fill="url(#iRQaric)" class="zd7wcdy4b"/><path fill="url(#iy4394c)" class="zd7wcdy4b"/><g filter="url(#iE7iQzc)"><path fill="url(#i7pnrQc)" class="km5yizosj"/></g><g filter="url(#ijzEkxb)"><path class="j7uh2cc6t"/><path fill="url(#iXWYjod)" class="kox-udncr"/><path fill="url(#isjtAVy)" class="kox-udncr"/><path fill="url(#iqQONZh)" class="kox-udncr"/><path fill="url(#ispt0xc)" class="kox-udncr"/></g><g filter="url(#iFKFXAe)"><path class="nta0f4b5m"/></g><g filter="url(#i3BSi9c)"><path class="trmbhibmm"/><path fill="url(#ihiQHpe)" class="ad4v1hj8p"/><path fill="url(#iGZicPb)" class="ad4v1hj8p"/><path fill="url(#iQEtBte)" class="ad4v1hj8p"/><path fill="url(#i16VCGd)" class="ad4v1hj8p"/></g><path stroke="url(#if25R3c)" class="q_9t6in6j"/><g filter="url(#ipifTdm)"><path class="f663mxu3g"/><path fill="url(#iT9d7Ec)" class="j_zh3ub8l"/></g><g filter="url(#ijWuTtc)"><path class="m6h9exbka"/><path fill="url(#iEBCRNb)" class="d3fz2pbbw"/></g><g filter="url(#idmBfbe)"><path stroke="url(#iDp4mEd)" class="hsn2di3tf"/></g><g filter="url(#ivvVrSc)"><path stroke="url(#il1kUyb)" class="kp1b3mexn"/></g><g filter="url(#ieTiq2o)"><path stroke="url(#i2Jczsb)" class="vaunz91tl"/></g><path class="dnt3-fblq"/><g filter="url(#iLQfh0d)"><path class="s0z-5jb0k"/></g><path class="xdror4b0t"/><g filter="url(#iq8LT7d)"><path class="rb1z-kj5e"/></g><defs><radialGradient id="i2B084d" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.364 13.101)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="e8kivk_8j"/><stop offset="1" class="el8j_lmyj"/></radialGradient><radialGradient id="iR0mKWd" cx="0" cy="0" r="1" gradientTransform="matrix(.23438 .67187 -1.35614 .47307 26.835 22.481)" gradientUnits="userSpaceOnUse"><stop class="e8kivk_8j"/><stop offset="1" class="el8j_lmyj"/></radialGradient><radialGradient id="ikaW3EK" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.216)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="hhctjoo7s"/><stop offset="1" class="uuwoulbxc"/></radialGradient><radialGradient id="iv0XUac" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.89 31.634)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="sg0n-eqag"/><stop offset="1" class="r65q887vt"/></radialGradient><radialGradient id="ie9mQjc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.56)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="qww_2wbks"/><stop offset="1" class="ojtt1ubdv"/></radialGradient><radialGradient id="i7oHMle" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="k7blc57pd"/><stop offset="1" class="gn_p8e8sd"/></radialGradient><radialGradient id="iyXixie" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.892)" gradientUnits="userSpaceOnUse"><stop class="qux0lkedt"/><stop offset="1" class="uxc3_1big"/></radialGradient><radialGradient id="i7ikXJe" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.767)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="q7352-9kv"/><stop offset="1" class="arw8-l5dn"/></radialGradient><radialGradient id="i29oqne" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.122)" gradientUnits="userSpaceOnUse"><stop class="g06b8fbvn"/><stop offset="1" class="q05jf29-x"/></radialGradient><radialGradient id="isLizxd" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.848)" gradientUnits="userSpaceOnUse"><stop class="hxe1-qbdv"/><stop offset="1" class="gvgzd5bho"/></radialGradient><radialGradient id="igA15hd" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.158 23.523)" gradientUnits="userSpaceOnUse"><stop class="osj_oacvf"/><stop offset="1" class="m_3-9ebgy"/></radialGradient><radialGradient id="idETd5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20.028)" gradientUnits="userSpaceOnUse"><stop class="o0g94xb_k"/><stop offset="1" class="lfzrz9u2y"/></radialGradient><radialGradient id="iwc2NVc" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.242 7.545)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="to3b9rbvd"/><stop offset="1" class="d10de8bzv"/></radialGradient><radialGradient id="i3XftSc" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.122)" gradientUnits="userSpaceOnUse"><stop class="lgzeshbhm"/><stop offset="1" class="b1hmbi0gc"/></radialGradient><radialGradient id="inCCwUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.122)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="ivCaO8b" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.075 2.413)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="e2jk3lbzi"/><stop offset="1" class="l1gvkpboh"/></radialGradient><radialGradient id="isP2xWd" cx="0" cy="0" r="1" gradientTransform="rotate(108.939 3.722 10.252)scale(3.36993 3.80066)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="rgcbzi4wz"/><stop offset="1" class="es0ucmbxo"/></radialGradient><radialGradient id="ikiKFvd" cx="0" cy="0" r="1" gradientTransform="matrix(.5 8.04173 -7.73502 .48093 17.689 13.31)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="afioo-bwu"/><stop offset="1" class="h1j0-fblz"/></radialGradient><radialGradient id="i2Vclfd" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.572 10.766)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="bakt0qbwy"/><stop offset="1" class="ltpsj2n6q"/></radialGradient><radialGradient id="iaLdVZu" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.84)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="rx6_xs15m"/><stop offset="1" class="keibw1bxy"/><stop offset="1" class="z321yabtz"/></radialGradient><radialGradient id="iAkrPOb" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.075)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="whcdqwb8b"/><stop offset=".958" class="e575psbmi"/></radialGradient><radialGradient id="is178he" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.075)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="w84n4ouwr"/><stop offset="1" class="oyrzqh62n"/></radialGradient><radialGradient id="iHur8ZY" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.7)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="whcdqwb8b"/><stop offset=".958" class="e575psbmi"/></radialGradient><radialGradient id="iXxjsrR" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.7)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="w84n4ouwr"/><stop offset="1" class="oyrzqh62n"/></radialGradient><radialGradient id="i10Eklc" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.254)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="whcdqwb8b"/><stop offset=".958" class="e575psbmi"/></radialGradient><radialGradient id="i7HxqFd" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.72 24.127)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="w84n4ouwr"/><stop offset="1" class="oyrzqh62n"/></radialGradient><radialGradient id="ikD3dGb" cx="0" cy="0" r="1" gradientTransform="matrix(.10014 1.0686 -3.5818 .33567 5.935 24.44)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="r1i2lobcl"/><stop offset="1" class="x4fpn9o2k"/></radialGradient><radialGradient id="iZ67Rue" cx="0" cy="0" r="1" gradientTransform="matrix(-.10014 1.0686 -3.5818 -.33567 26.065 24.44)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="w84n4ouwr"/><stop offset="1" class="oyrzqh62n"/></radialGradient><radialGradient id="iVHjY3d" cx="0" cy="0" r="1" gradientTransform="matrix(1.11106 0 0 1.94437 11.942 7.64)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iDKbTbS" cx="0" cy="0" r="1" gradientTransform="matrix(.52341 -.38113 .435 .59741 19.258 7.473)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iW52Wvd" cx="0" cy="0" r="1" gradientTransform="matrix(.51997 -.95637 .55977 .30434 18.996 8.16)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iqBubZb" cx="0" cy="0" r="1" gradientTransform="matrix(.16416 .1625 -.20948 .21163 19.023 7.64)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iBE61nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82756 1.01853 0 17.49 6.836)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iuuh5sd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.87 1.08192 0 14.605 6.92)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iy4394c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.60105 -7.60312 0 15.815 6.518)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="iXWYjod" cx="0" cy="0" r="1" gradientTransform="matrix(.50513 -1.87194 .90134 .24322 18.756 5.041)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="isjtAVy" cx="0" cy="0" r="1" gradientTransform="matrix(2.42164 .22286 -.11983 1.3021 17.717 3.927)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iqQONZh" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.06314 -1.64651 0 16.005 2.195)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="ispt0xc" cx="0" cy="0" r="1" gradientTransform="matrix(1.94622 -1.42624 2.23445 3.04908 11.923 6.512)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="i16VCGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .12466 -.40052 0 16.213 8.658)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iT9d7Ec" cx="0" cy="0" r="1" gradientTransform="matrix(.06597 -.38195 1.12997 .19516 17.552 6.321)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iEBCRNb" cx="0" cy="0" r="1" gradientTransform="matrix(.06597 -.38195 1.13003 .19519 14.293 6.321)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><filter id="i4R3o4r" width="9.729" height="6.156" x="17.627" y="21.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.282353 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.262745 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23990" result="effect2_innerShadow_3987_23990"/></filter><filter id="ibGHmYQ" width="17.213" height="7.995" x="5.751" y="21.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.270588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.282353 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23990" result="effect2_innerShadow_3987_23990"/></filter><filter id="iOK4XYc" width="7.621" height="12.797" x="19.836" y="11.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.188235 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="iSPyVRd" width="8.502" height="3.19" x="11.869" y="21.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="iD6xqGc" width="8.289" height="10.271" x="11.888" y="11.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.556863 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="igkaWcb" width="1.684" height="1.255" x="5.351" y="24.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="ihDD4Yc" width="1.684" height="1.255" x="24.965" y="24.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="iib5BFf" width="2.04" height="1.095" x="4.237" y="23.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="iUbkWic" width="2.04" height="1.095" x="25.723" y="23.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="iyNOUBJ" width="2.223" height=".888" x="3.593" y="23.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="iVsgcAb" width="2.223" height=".888" x="26.184" y="23.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="ipAd6Ne" width="2.031" height=".566" x="3.653" y="22.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="ieyye1d" width="2.031" height=".566" x="26.317" y="22.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="iwPPTVb" width="2.314" height="2.114" x="11.942" y="6.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="ivwz2ab" width="2.26" height="2.26" x="11.87" y="6.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".25"/></filter><filter id="i5Wmydd" width="2.364" height="2.364" x="17.966" y="6.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="iHyM6Jc" width="2.26" height="2.26" x="17.893" y="6.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".25"/></filter><filter id="iq8zPfc" width="6.568" height="7.765" x="12.74" y="4.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="iE7iQzc" width="6.688" height="5.942" x="14.113" y="2.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation="1"/></filter><filter id="ijzEkxb" width="7.979" height="5.243" x="12.016" y="2.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="iFKFXAe" width="2.614" height="3.198" x="14.547" y="6.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".375"/></filter><filter id="i3BSi9c" width="1.488" height="1.998" x="15.262" y="7.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".075"/></filter><filter id="ipifTdm" width="1.978" height="1.333" x="16.754" y="5.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="ijWuTtc" width="1.978" height="1.333" x="13.495" y="5.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23990"/></filter><filter id="idmBfbe" width="2.421" height="1.523" x="16.432" y="5.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".25"/></filter><filter id="ivvVrSc" width="2.47" height="1.559" x="13.127" y="5.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".25"/></filter><filter id="ieTiq2o" width=".913" height="1.712" x="12.597" y="4.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".125"/></filter><filter id="iLQfh0d" width="1.628" height=".644" x="13.82" y="7.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".05"/></filter><filter id="iq8LT7d" width="1.628" height=".644" x="16.609" y="7.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23990" stdDeviation=".05"/></filter><linearGradient id="i5tGS2d" x1="21.525" x2="21.525" y1="21.06" y2="22.216" gradientUnits="userSpaceOnUse"><stop class="y69ibv-do"/><stop offset="1" class="yw5dd8t_v"/></linearGradient><linearGradient id="iEC0VzV" x1="18.658" x2="19.892" y1="24.344" y2="24.747" gradientUnits="userSpaceOnUse"><stop offset=".106" class="h3px5kbzs"/><stop offset="1" class="gjk5l0f7i"/></linearGradient><linearGradient id="iXOs4ie" x1="10.822" x2="10.822" y1="21.06" y2="22.216" gradientUnits="userSpaceOnUse"><stop class="x3bti8ber"/><stop offset="1" class="hbhny8bey"/></linearGradient><linearGradient id="idT07lC" x1="13.689" x2="12.455" y1="24.344" y2="24.747" gradientUnits="userSpaceOnUse"><stop offset=".106" class="x3bti8ber"/><stop offset="1" class="hbhny8bey"/></linearGradient><linearGradient id="iBn2sib" x1="12.24" x2="10.033" y1="20.665" y2="20.474" gradientUnits="userSpaceOnUse"><stop offset=".184" class="jq5vnpb6e"/><stop offset="1" class="wa0r83b7o"/></linearGradient><linearGradient id="iGFe9Gb" x1="19.835" x2="22.042" y1="20.665" y2="20.474" gradientUnits="userSpaceOnUse"><stop offset=".184" class="psa8qnbsw"/><stop offset="1" class="piww_ebpc"/></linearGradient><linearGradient id="i78hAQc" x1="26.794" x2="24.919" y1="25.174" y2="24.08" gradientUnits="userSpaceOnUse"><stop class="uj_eajbrd"/><stop offset="1" class="v4t97l5et"/></linearGradient><linearGradient id="iCwYaOc" x1="13" x2="12.594" y1="7.817" y2="7.817" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="isBcb6G" x1="19.711" x2="19.192" y1="6.95" y2="8.556" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="itW1b2b" x1="18.561" x2="13.726" y1="7.888" y2="8.608" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iitdbue" x1="12.589" x2="13.78" y1="9.594" y2="9.552" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iRQaric" x1="19.085" x2="18.417" y1="9.064" y2="9" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="i7pnrQc" x1="15.669" x2="20.825" y1="5.998" y2="4.152" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="ihiQHpe" x1="15.459" x2="16.053" y1="8.305" y2="8.305" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iGZicPb" x1="16.6" x2="15.95" y1="8.509" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iQEtBte" x1="16.129" x2="16.129" y1="8.979" y2="8.616" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="if25R3c" x1="15.349" x2="15.624" y1="10.002" y2="9.566" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iDp4mEd" x1="17.887" x2="17.621" y1="5.889" y2="5.345" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="il1kUyb" x1="14.529" x2="13.776" y1="5.808" y2="5.492" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i2Jczsb" x1="13.054" x2="13.054" y1="4.532" y2="5.898" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-lotus-position-medium-dark" /></template>
<style>
.a9xl-ibwm {
  d: path("M18.892 11.181v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.723a6.5 6.5 0 0 0-1.27.896v9.275h8.289v-9.275c-.198-.2-.662-.56-1.285-.895");
}

.ad4v1hj8p {
  d: path("m15.764 7.46l-.337 1.076a.34.34 0 0 0 .33.443h.498a.342.342 0 0 0 .33-.443l-.337-1.076c-.072-.238-.409-.238-.484 0");
}

.af35w8x4b {
  fill-rule: evenodd;
  d: path("M26.175 23.553a.4.4 0 0 0 .18.537c.754.374 1.51.448 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.365a.4.4 0 0 0-.537.18");
}

.afioo-bwu {
  stop-color: var(--svg-color--53adfc, #53ADFC);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.ao0j51bbd {
  d: path("M9.755 16.109c.22-1.859 1.605-3.58 2.152-4.042l.332.315v7.277c-.25.651-.719 1.329-1.125 1.651c0 0-.867.815-4.171 3.304c-1.325-.184-2.095-1.093-2.074-1.703c.875-.5 3.37-2.968 4.011-3.606c.537-.535.64-1.215.875-3.196");
}

.arw8-l5dn {
  stop-color: var(--svg-color--875f5a, #875F5A);
  stop-opacity: 0;
}

.ayf_0ac_e {
  d: path("M17.627 27.966h4.244c2.93 0 4.28-1.917 4.484-2.828l-2.531-2.329l-3.62 1.422l-2.578.11z");
}

.b1hmbi0gc {
  stop-color: var(--svg-color--9a766b, #9A766B);
  stop-opacity: 0;
}

.bakt0qbwy {
  stop-color: var(--svg-color--3482d0, #3482D0);
  stop-opacity: 0;
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c8ua0_dop {
  fill: var(--svg-color--824c3e, #824C3E);
  d: path("M22.32 16.109c-.22-1.859-1.605-3.58-2.152-4.042l-.332.315v7.277c.25.651.719 1.329 1.125 1.651c0 0 .867.815 4.172 3.304c1.325-.184 2.094-1.093 2.073-1.703c-.874-.5-3.37-2.968-4.01-3.606c-.538-.535-.641-1.215-.876-3.196");
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d10de8bzv {
  stop-color: var(--svg-color--83574a, #83574A);
  stop-opacity: 0;
}

.d3fz2pbbw {
  d: path("m13.616 5.919l.001-.002l.003-.002l.008-.006a1 1 0 0 1 .098-.068a1.6 1.6 0 0 1 .266-.134c.227-.09.551-.162.945-.1a.338.338 0 1 1-.106.668a1.12 1.12 0 0 0-.746.138l-.04.028a.338.338 0 0 1-.43-.522");
}

.d42ciobst {
  cx: 19.023px;
  cy: 7.641px;
  r: 1.057px;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dnt3-fblq {
  stroke: var(--svg-color--070506, #070506);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.332a.81.81 0 0 0 .672.343c.297 0 .591-.229.656-.343");
}

.dodmiac3i {
  fill: var(--svg-color--7d4d41, #7D4D41);
  fill-rule: evenodd;
  d: path("M26.304 23.075a.4.4 0 0 0 .265.5c.536.164 1.099.146 1.367.137l.124-.003a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.008-.656.017-1.045-.102a.4.4 0 0 0-.5.265");
}

.e2ftv_b9f {
  cx: 19.023px;
  cy: 7.641px;
  r: 0.63px;
}

.e2jk3lbzi {
  stop-color: var(--svg-color--97746b, #97746B);
}

.e575psbmi {
  stop-color: var(--svg-color--80504e, #80504E);
}

.e8kivk_8j {
  stop-color: var(--svg-color--825a4a, #825A4A);
}

.ebmu0looz {
  fill-rule: evenodd;
  d: path("M6.818 24.2c.14.171.272.304.101.444c-.565.464-.934.651-1.193.783l-.072.037a.4.4 0 1 1-.367-.712l.074-.037c.243-.124.552-.28 1.051-.69c.17-.14.266.004.406.175");
}

.eejimub8z {
  d: path("m12.777 7.253l.03.001s-.033-.54-.067-.912c0-.169.068-.371.204-.472l.101-.102a.67.67 0 0 0 .238-.54v-.54a.33.33 0 0 1 .272-.338c.407-.101 1.256-.27 2.479-.27s2.072.169 2.48.27a.36.36 0 0 1 .27.338v.54c0 .203.103.405.239.54c.317.223.298.346.271.608c-.034.338-.068.912-.068.912h.012l-.169 2.506c-.101 1.12-.982 1.901-2.032 1.901h-2.033c-1.084 0-1.93-.78-2.032-1.901z");
}

.el8j_lmyj {
  stop-color: var(--svg-color--835a4d, #835A4D);
}

.es0ucmbxo {
  stop-color: var(--svg-color--704e43, #704E43);
  stop-opacity: 0;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f663mxu3g {
  fill: var(--svg-color--352827, #352827);
  d: path("m18.36 5.919l-.002-.002l-.002-.002l-.008-.006a1 1 0 0 0-.098-.068a1.6 1.6 0 0 0-.266-.134a1.8 1.8 0 0 0-.945-.1a.338.338 0 1 0 .106.668a1.12 1.12 0 0 1 .746.138l.04.028a.338.338 0 0 0 .43-.522");
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g06b8fbvn {
  stop-color: var(--svg-color--6a4e48, #6A4E48);
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gjk5l0f7i {
  stop-color: var(--svg-color--593440, #593440);
  stop-opacity: 0;
}

.gn_p8e8sd {
  stop-color: var(--svg-color--926c6a, #926C6A);
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gvgzd5bho {
  stop-color: var(--svg-color--603b3a, #603B3A);
}

.h1j0-fblz {
  stop-color: var(--svg-color--3181d9, #3181D9);
}

.h3px5kbzs {
  stop-color: var(--svg-color--593440, #593440);
}

.h3ryqpb5c {
  d: path("M13.83 21.351H7.814v2.693c2.531.351 6.016.297 6.016.297z");
}

.hbhny8bey {
  stop-color: var(--svg-color--4e2b29, #4E2B29);
  stop-opacity: 0;
}

.hhctjoo7s {
  stop-color: var(--svg-color--815e58, #815E58);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hsn2di3tf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.057 5.827c.272-.047.803-.034 1.17.252");
}

.hxe1-qbdv {
  stop-color: var(--svg-color--80645d, #80645D);
}

.ifpl6ybzj {
  d: path("M22.32 16.109c-.22-1.859-1.605-3.58-2.152-4.042l-.332.315v7.277c.25.651.719 1.329 1.125 1.651c0 0 .867.815 4.172 3.304c1.325-.184 2.094-1.093 2.073-1.703c-.874-.5-3.37-2.968-4.01-3.606c-.538-.535-.641-1.215-.876-3.196");
}

.ip9j-lbln {
  fill-rule: evenodd;
  d: path("M25.902 23.975a.4.4 0 0 0 .043.564c.34.29.628.456.903.55c.254.085.478.1.655.113q.02 0 .037.003a.4.4 0 1 0 .057-.798l-.018-.002a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.157-.64-.399a.4.4 0 0 0-.564.044");
}

.ir55m1boa {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.294c-.398 0-.893.047-1.58-.11");
}

.iu836jppc {
  fill: var(--svg-color--7d4d41, #7D4D41);
  fill-rule: evenodd;
  d: path("M26.175 23.553a.4.4 0 0 0 .18.537c.754.374 1.51.448 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.365a.4.4 0 0 0-.537.18");
}

.j_zh3ub8l {
  d: path("m18.36 5.919l-.002-.002l-.002-.002l-.008-.006a1 1 0 0 0-.098-.068a1.6 1.6 0 0 0-.266-.134a1.8 1.8 0 0 0-.945-.1a.338.338 0 1 0 .106.668a1.12 1.12 0 0 1 .746.138l.04.028a.338.338 0 0 0 .43-.522");
}

.j-k11ibbx {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.044c.398 0 1.015-.055 1.773-.438");
}

.j7uh2cc6t {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m19.056 3.54l.272.135c.476.236.747.776.645 1.35L19.6 6.95c-.034.199-.165.333-.362.338h-.012s.034-.574.068-.912c.028-.274-.02-.358-.272-.608a.8.8 0 0 1-.237-.54v-.54a.36.36 0 0 0-.272-.338c-.408-.101-1.257-.27-2.48-.27c-1.222 0-2.07.169-2.478.27a.33.33 0 0 0-.272.338v.54a.67.67 0 0 1-.238.54l-.102.102c-.136.1-.203.303-.203.472c.034.372.067.912.067.912l-.03-.001a.4.4 0 0 1-.377-.337l-.374-1.924c-.067-.54.204-1.08.68-1.317l.271-.135c.17-.102.34-.237.51-.372l.611-.641a1.24 1.24 0 0 1 1.393-.203c.34.101.713.101 1.052 0a1.53 1.53 0 0 1 1.495.338l.509.506c.136.169.306.27.51.372");
}

.jd2r4hb6j {
  fill: var(--svg-color--7d4d41, #7D4D41);
  fill-rule: evenodd;
  d: path("M25.902 23.975a.4.4 0 0 0 .043.564c.34.29.628.456.903.55c.254.085.478.1.655.113q.02 0 .037.003a.4.4 0 1 0 .057-.798l-.018-.002a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.157-.64-.399a.4.4 0 0 0-.564.044");
}

.jh45d3v4x {
  fill: var(--svg-color--856054, #856054);
  fill-rule: evenodd;
  d: path("M6.099 23.975a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.55a2.5 2.5 0 0 1-.655.113q-.02 0-.037.003a.4.4 0 1 1-.039-.8c.19-.013.32-.023.475-.075s.356-.157.639-.399a.4.4 0 0 1 .564.044");
}

.jq5vnpb6e {
  stop-color: var(--svg-color--652e27, #652E27);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k7blc57pd {
  stop-color: var(--svg-color--926c6a, #926C6A);
  stop-opacity: 0;
}

.keibw1bxy {
  stop-color: var(--svg-color--398dce, #398DCE);
  stop-opacity: 0;
}

.kgi5hcc7r {
  d: path("M18.892 11.181v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.723c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.374 2.82.785");
}

.km5yizosj {
  d: path("m18.515 4.08l-1.948.65a.663.663 0 0 0 .297 1.286l1.937-.26z");
}

.kox-udncr {
  d: path("m19.056 3.54l.272.135c.476.236.747.776.645 1.35L19.6 6.95c-.034.199-.165.333-.362.338h-.012s.034-.574.068-.912c.028-.274-.02-.358-.272-.608a.8.8 0 0 1-.237-.54v-.54a.36.36 0 0 0-.272-.338c-.408-.101-1.257-.27-2.48-.27c-1.222 0-2.07.169-2.478.27a.33.33 0 0 0-.272.338v.54a.67.67 0 0 1-.238.54l-.102.102c-.136.1-.203.303-.203.472c.034.372.067.912.067.912l-.03-.001a.4.4 0 0 1-.377-.337l-.374-1.924c-.067-.54.204-1.08.68-1.317l.271-.135c.17-.102.34-.237.51-.372l.611-.641a1.24 1.24 0 0 1 1.393-.203c.34.101.713.101 1.052 0a1.53 1.53 0 0 1 1.495.338l.509.506c.136.169.306.27.51.372");
}

.kp1b3mexn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.752 6.156c.208-.184.66-.376 1.22-.287");
}

.kt3l5zbkg {
  d: path("M10.236 27.966c-2.93 0-4.281-1.917-4.485-2.828l2.532-2.329l3.453 1.446l8.18.086c.426 0 .804.268.944.67c.407 1.17.96 2.764 1.032 3.002c.11.359.25 1.453-.875 1.765c-.78.217-1.523-.937-2.11-1.812z");
}

.ktp9-quqg {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.774c-.41-.066-1.204-.312-1.59-.644");
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzh2qubat {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.083a15 15 0 0 0 1.234-.805");
}

.l1gvkpboh {
  stop-color: var(--svg-color--7b5449, #7B5449);
}

.lb4q4qx8j {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.294c.398 0 .893.047 1.58-.11");
}

.lfzrz9u2y {
  stop-color: var(--svg-color--4f1d19, #4F1D19);
  stop-opacity: 0;
}

.lgzeshbhm {
  stop-color: var(--svg-color--9a766b, #9A766B);
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lqaxw_boi {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.083a15 15 0 0 1-1.234-.805");
}

.ltpsj2n6q {
  stop-color: var(--svg-color--3c515d, #3C515D);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m_3-9ebgy {
  stop-color: var(--svg-color--8e6757, #8E6757);
  stop-opacity: 0;
}

.m6h9exbka {
  fill: var(--svg-color--352827, #352827);
  d: path("m13.616 5.919l.001-.002l.003-.002l.008-.006a1 1 0 0 1 .098-.068a1.6 1.6 0 0 1 .266-.134c.227-.09.551-.162.945-.1a.338.338 0 1 1-.106.668a1.12 1.12 0 0 0-.746.138l-.04.028a.338.338 0 0 1-.43-.522");
}

.mb6emvl-w {
  fill: var(--svg-color--8b604f, #8B604F);
  d: path("M10.236 27.966c-2.93 0-4.281-1.917-4.485-2.828l2.532-2.329l3.453 1.446l8.18.086c.426 0 .804.268.944.67c.407 1.17.96 2.764 1.032 3.002c.11.359.25 1.453-.875 1.765c-.78.217-1.523-.937-2.11-1.812z");
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.n5bh3rbpi {
  d: path("M13.22 24.34h-1.429a1 1 0 0 0-.943.67c-.408 1.171-.96 2.765-1.032 3.003c-.11.359-.25 1.453.875 1.765c.757.21 1.48-.87 2.057-1.734l.052-.078h.42z");
}

.n8fmpbc6x {
  fill-rule: evenodd;
  d: path("M26.304 23.075a.4.4 0 0 0 .265.5c.536.164 1.099.146 1.367.137l.124-.003a.4.4 0 0 0 .018-.8a5 5 0 0 0-.23.003c-.286.008-.656.017-1.045-.102a.4.4 0 0 0-.5.265");
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nta0f4b5m {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.831 7.564l-.52 1.076c-.064.22.09.442.31.442h.466c.22 0 .374-.224.31-.442l-.316-1.076c-.068-.239-.18-.239-.25 0");
}

.ntdx2vbfn {
  fill-rule: evenodd;
  d: path("M5.697 23.075a.4.4 0 0 1-.266.5c-.536.164-1.099.146-1.367.137l-.124-.003a.4.4 0 0 1-.018-.8l.23.003c.286.008.656.017 1.045-.102a.4.4 0 0 1 .5.265");
}

.o-6cv1fhy {
  fill: var(--svg-color--865f53, #865F53);
  fill-rule: evenodd;
  d: path("M6.818 24.2c.14.171.272.304.101.444c-.565.464-.934.651-1.193.783l-.072.037a.4.4 0 1 1-.367-.712l.074-.037c.243-.124.552-.28 1.051-.69c.17-.14.266.004.406.175");
}

.o0g94xb_k {
  stop-color: var(--svg-color--4f1d19, #4F1D19);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.ojtt1ubdv {
  stop-color: var(--svg-color--764060, #764060);
}

.osj_oacvf {
  stop-color: var(--svg-color--9a766d, #9A766D);
}

.oyrzqh62n {
  stop-color: var(--svg-color--6f423d, #6F423D);
}

.pap7mydzq {
  cx: 19.023px;
  cy: 7.641px;
  r: 0.63px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.piww_ebpc {
  stop-color: var(--svg-color--672b23, #672B23);
  stop-opacity: 0;
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.psa8qnbsw {
  stop-color: var(--svg-color--672b23, #672B23);
}

.psr8zvxxq {
  fill: var(--svg-color--856054, #856054);
  fill-rule: evenodd;
  d: path("M5.825 23.553a.4.4 0 0 1-.18.537a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8c.226 0 .852-.06 1.466-.365a.4.4 0 0 1 .537.18");
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q_9t6in6j {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.152 9.37c.246.129.54.203.853.203c.317 0 .608-.074.854-.203a.15.15 0 0 1 .175.029a.14.14 0 0 1 .015.176m-1.897-.205l1.856.177m-1.856-.177h-.001a.15.15 0 0 0-.175.03a.14.14 0 0 0-.014.175m.19-.205l-.149.177m2.046.028l-.041-.028m.041.028l-.041-.028m.041.028a1.25 1.25 0 0 1-1.044.557c-.438 0-.822-.222-1.043-.557m2.046-.028a1.2 1.2 0 0 1-1.003.535a1.2 1.2 0 0 1-1.002-.535m-.041.028l.041-.028m-.041.028l.041-.028");
}

.q_mhuob6r {
  fill: var(--svg-color--856054, #856054);
  fill-rule: evenodd;
  d: path("M5.697 23.075a.4.4 0 0 1-.266.5c-.536.164-1.099.146-1.367.137l-.124-.003a.4.4 0 0 1-.018-.8l.23.003c.286.008.656.017 1.045-.102a.4.4 0 0 1 .5.265");
}

.q05jf29-x {
  stop-color: var(--svg-color--5b3938, #5B3938);
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q7352-9kv {
  stop-color: var(--svg-color--9f776f, #9F776F);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qux0lkedt {
  stop-color: var(--svg-color--98736d, #98736D);
}

.qww_2wbks {
  stop-color: var(--svg-color--804c5e, #804C5E);
}

.r1i2lobcl {
  stop-color: var(--svg-color--844e66, #844E66);
  stop-opacity: 0;
}

.r65q887vt {
  stop-color: var(--svg-color--714a44, #714A44);
  stop-opacity: 0;
}

.rb1z-kj5e {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.332a.81.81 0 0 0 .671.343c.297 0 .591-.229.656-.343");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rdws5abmr {
  fill-rule: evenodd;
  d: path("M25.316 22.985a.5.5 0 0 0 .5.5c.632 0 1.257-.193 1.5-.268l.04-.012a.5.5 0 1 0-.322-.947c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.rftfblbbu {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.774c.41-.066 1.204-.312 1.59-.644");
}

.rgcbzi4wz {
  stop-color: var(--svg-color--613b31, #613B31);
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rw_gd1bje {
  fill-rule: evenodd;
  d: path("M6.099 23.975a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.55a2.5 2.5 0 0 1-.655.113q-.02 0-.037.003a.4.4 0 1 1-.039-.8c.19-.013.32-.023.475-.075s.356-.157.639-.399a.4.4 0 0 1 .564.044");
}

.rx6_xs15m {
  stop-color: var(--svg-color--3d84ae, #3D84AE);
}

.s0z-5jb0k {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.332a.81.81 0 0 0 .672.343c.297 0 .591-.229.656-.343");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sg0n-eqag {
  stop-color: var(--svg-color--5c322e, #5C322E);
}

.tbru6-b6h {
  cx: 13px;
  cy: 7.641px;
  r: 0.63px;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.to3b9rbvd {
  stop-color: var(--svg-color--9a756c, #9A756C);
}

.trmbhibmm {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.764 7.46l-.337 1.076a.34.34 0 0 0 .33.443h.498a.342.342 0 0 0 .33-.443l-.337-1.076c-.072-.238-.409-.238-.484 0");
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u_-l4nigi {
  d: path("M18.517 21.351h6.016v2.693c-2.532.351-6.016.297-6.016.297z");
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uj_eajbrd {
  stop-color: var(--svg-color--7d4d41, #7D4D41);
}

.usytz5beo {
  d: path("m13.447 24.34l-1.578-2.989h8.301l-1.551 2.99z");
}

.uuwoulbxc {
  stop-color: var(--svg-color--7e544c, #7E544C);
}

.uxc3_1big {
  stop-color: var(--svg-color--98736d, #98736D);
  stop-opacity: 0;
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v4t97l5et {
  stop-color: var(--svg-color--65362f, #65362F);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vaunz91tl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.136 4.595v.568c-.005.094-.045.305-.164.394");
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w84n4ouwr {
  stop-color: var(--svg-color--6f423d, #6F423D);
  stop-opacity: 0;
}

.wa0r83b7o {
  stop-color: var(--svg-color--652e27, #652E27);
  stop-opacity: 0;
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whcdqwb8b {
  stop-color: var(--svg-color--80504e, #80504E);
  stop-opacity: 0;
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.x3bti8ber {
  stop-color: var(--svg-color--4e2b29, #4E2B29);
}

.x4fpn9o2k {
  stop-color: var(--svg-color--844e66, #844E66);
}

.xdror4b0t {
  stroke: var(--svg-color--070506, #070506);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.332a.81.81 0 0 0 .671.343c.297 0 .591-.229.656-.343");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xhp-7db0c {
  fill-rule: evenodd;
  d: path("M5.825 23.553a.4.4 0 0 1-.18.537a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8c.226 0 .852-.06 1.466-.365a.4.4 0 0 1 .537.18");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y4mwd1bkm {
  fill-rule: evenodd;
  d: path("M6.76 22.985a.5.5 0 0 1-.5.5c-.632 0-1.257-.193-1.501-.268l-.04-.012a.5.5 0 1 1 .322-.947c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.y69ibv-do {
  stop-color: var(--svg-color--552b23, #552B23);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ybnd2o6or {
  fill-rule: evenodd;
  d: path("M25.182 24.2c-.14.171-.272.304-.101.444c.565.464.934.651 1.193.783l.072.037a.4.4 0 1 0 .367-.712l-.074-.037c-.243-.124-.552-.28-1.051-.69c-.17-.14-.266.004-.406.175");
}

.ydx8zzb-s {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.044a3.8 3.8 0 0 1-1.773-.438");
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ypfzj4hjr {
  cx: 12.999px;
  cy: 7.641px;
  r: 1.057px;
}

.yvq2fpben {
  fill: var(--svg-color--7f5344, #7F5344);
  d: path("M9.755 16.109c.22-1.859 1.605-3.58 2.152-4.042l.332.315v7.277c-.25.651-.719 1.329-1.125 1.651c0 0-.867.815-4.171 3.304c-1.325-.184-2.095-1.093-2.074-1.703c.875-.5 3.37-2.968 4.011-3.606c.537-.535.64-1.215.875-3.196");
}

.yw5dd8t_v {
  stop-color: var(--svg-color--552b23, #552B23);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z321yabtz {
  stop-color: var(--svg-color--d3612e, #D3612E);
  stop-opacity: 0;
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zd7wcdy4b {
  d: path("M12.74 6.342c0-.169.068-.371.204-.472l.101-.102a.67.67 0 0 0 .238-.54v-.54a.33.33 0 0 1 .272-.338c.407-.101 1.256-.27 2.479-.27s2.072.169 2.48.27a.36.36 0 0 1 .27.338v.54c0 .203.103.405.239.54c.317.223.298.346.271.608c-.034.338-.068.912-.068.912h.012l-.169 2.506c-.101 1.12-.982 1.901-2.032 1.901h-2.033c-1.084 0-1.93-.78-2.032-1.901c-.089-1.15-.127-2.304-.232-3.452");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

</style>
