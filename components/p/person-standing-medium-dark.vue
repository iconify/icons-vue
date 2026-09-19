<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="f2f8y2bye"/><path class="mkrizlbsk"/><g filter="url(#ifXzzzb)"><path class="vxc5s_bai"/><path fill="url(#iHMC62b)" class="z23533p_d"/></g><path class="l_aygfawn"/><path fill="url(#iQMDitc)" class="bg_y89dup"/><path fill="url(#izkG4Ic)" class="bg_y89dup"/><path class="re73b6xet"/><path fill="url(#iSKzZDe)" class="zzl9q_jda"/><path fill="url(#iYGcJKd)" class="zzl9q_jda"/><path fill="url(#i2bDogb)" class="zzl9q_jda"/><g filter="url(#imoN3Ld)"><path class="m_7n9dy5d"/></g><path class="qes_hkbxf"/><path fill="url(#iwpA6bd)" class="osx_cvdvg"/><path fill="url(#izQrBVc)" class="osx_cvdvg"/><g filter="url(#iSxFavb)"><path class="vjpr3ob1d"/></g><path fill="url(#ibWngWb)" class="dq46or42q"/><path fill="url(#iVrANId)" class="dq46or42q"/><path fill="url(#in1TjYd)" class="dq46or42q"/><path fill="url(#i36tcdc)" class="dq46or42q"/><g filter="url(#ibKpkwd)"><path fill="url(#iglQ6Fe)" class="io8qqi52v"/><path fill="url(#iotG6Zb)" class="io8qqi52v"/></g><path fill="url(#ijTOHEc)" class="ck6qoaboh"/><g filter="url(#iXmyxvc)"><path class="utjcgnnio"/></g><path fill="url(#iB6Yhfe)" class="tfe_aug3p"/><path fill="url(#iVcvQqc)" class="tfe_aug3p"/><g filter="url(#ixwOuNj)"><path class="jxrw3o5te"/></g><path fill="url(#iRbhuVH)" class="b8lr97w5y"/><path fill="url(#iwYJnLd)" class="zmoflnhgm"/><g filter="url(#iXnxyhb)"><path fill="url(#ibnAbPc)" class="rr9h-xcpt"/><path fill="url(#ipUmNBd)" class="rr9h-xcpt"/></g><path fill="url(#iDq6Mbe)" class="rr9h-xcpt"/><path fill="url(#iRbxXBe)" class="rr9h-xcpt"/><path fill="url(#iLto9ab)" class="rr9h-xcpt"/><path fill="url(#igsSjEb)" class="rr9h-xcpt"/><path fill="url(#iAx7CMb)" class="rr9h-xcpt"/><path fill="url(#iv7JYZi)" class="rr9h-xcpt"/><path fill="url(#i6AFPSc)" class="rr9h-xcpt"/><g filter="url(#icSzqAb)"><path class="a2h7exfgq"/></g><g filter="url(#i3Zcq8c)"><path class="gnk562b4c"/><path fill="url(#iy2hZBb)" class="gnkev6mug"/><path fill="url(#iDhlvTc)" class="gnkev6mug"/><path fill="url(#iIKmAEc)" class="gnkev6mug"/><path fill="url(#idhHejb)" class="gnkev6mug"/><path fill="url(#i6O3Tlb)" class="gnkev6mug"/></g><g filter="url(#iLbMB8a)"><path stroke="url(#iVDRyMe)" class="xb3grpq8z"/></g><path fill="url(#iojFzse)" class="zmwvj69un"/><g filter="url(#i0qt1Ke)"><path fill="url(#iP8c8OC)" class="ochsfqbqa"/><path fill="url(#i9XCcWd)" class="ochsfqbqa"/><path fill="url(#isHd16D)" class="ochsfqbqa"/><path fill="url(#iKLOc7c)" class="ochsfqbqa"/><path fill="url(#i50m0Me)" class="ochsfqbqa"/></g><g filter="url(#ikqOP9c)"><path class="msg66cbuc"/></g><g filter="url(#icq8zlb)"><path class="d2ckuvtgb"/></g><g filter="url(#iC3CDMc)"><path class="wk0xacdsc"/><path fill="url(#iqsgUBd)" class="qn28_pozx"/><path fill="url(#iuBpQie)" class="qn28_pozx"/></g><g filter="url(#ibgd1FJ)"><path class="moy5ghv8o"/><path fill="url(#ighqlIc)" class="y0yuz4bps"/><path fill="url(#idfTYqb)" class="y0yuz4bps"/></g><path class="bca6h3crt"/><path fill="url(#iHF4nOe)" class="ltpbs0btu"/><path class="ug0o70dol"/><g filter="url(#iQqNJtd)"><path class="mt6kztu9a"/><path fill="url(#iVC6TMd)" class="lgf7m9lol"/></g><g filter="url(#iRMePbb)"><path fill="url(#i0YieUc)" class="fiqf-vbvi"/></g><path class="bn9csrb_g"/><path fill="url(#iQ2hVkd)" class="gz9jp_byg"/><path class="hb9auub6r"/><g filter="url(#iuJomFb)"><path fill="url(#iBX24Jb)" class="opik0i52p"/></g><g filter="url(#ipL0Bue)"><ellipse transform="rotate(-27.914 14.899 5.455)" class="tqgsrbmpz"/><ellipse fill="url(#inVuysb)" transform="rotate(-27.914 14.899 5.455)" class="s2118m3wh"/></g><path fill="url(#iYNb44d)" class="hgrr3mz7l"/><path fill="url(#iI2NHFQ)" class="hgrr3mz7l"/><path fill="url(#ihIpxie)" class="hgrr3mz7l"/><path fill="url(#ioLC9bd)" class="hgrr3mz7l"/><path fill="url(#iCZDyHu)" class="l7ofdmb1v"/><path fill="url(#ijde60c)" class="l7ofdmb1v"/><g filter="url(#igRHbAd)"><path fill="url(#iBku4oU)" class="urz-1qguo"/></g><g filter="url(#iHpI9Qc)"><path fill="url(#i2AKhbe)" class="i1f5ne5hf"/></g><g filter="url(#iRi9Hbc)"><path class="g_ff25aes"/></g><g filter="url(#imWAT3c)"><path class="zyo2feblp"/></g><g filter="url(#iBOKTxK)"><path class="i369cebot"/></g><defs><radialGradient id="iHMC62b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="v_ft29bcw"/><stop offset="1" class="zhgg7cc0u"/></radialGradient><radialGradient id="iQMDitc" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.63)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="xsr8v7bqw"/><stop offset="1" class="shh_g2b0q"/></radialGradient><radialGradient id="izkG4Ic" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 -.5625 .3991 .13026 19.319 19.025)" gradientUnits="userSpaceOnUse"><stop class="gd7pfsb0f"/><stop offset="1" class="liuzkqkjj"/></radialGradient><radialGradient id="iSKzZDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98267 0 0 -3.09375 13.513 12.523)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="cn77rwbmc"/><stop offset="1" class="y2mxoh-zc"/></radialGradient><radialGradient id="iYGcJKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.832)" gradientUnits="userSpaceOnUse"><stop class="y4_ytjb3b"/><stop offset="1" class="wysngjbll"/></radialGradient><radialGradient id="iwpA6bd" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.3125 1.2963 3.62963 18.794 11.976)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="l7g1kibqg"/><stop offset="1" class="d_gvw4b_b"/></radialGradient><radialGradient id="iVrANId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 18.101)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="in1TjYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.076 28.465)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="i36tcdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.554)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iotG6Zb" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.427 8.227)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="mdbsecb0y"/><stop offset="1" class="y-nukfwnq"/></radialGradient><radialGradient id="ijTOHEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.42712 .66406 -.8419 1.8093 15.444 8.873)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="s-8y-dbxo"/><stop offset="1" class="r1-m4ub1q"/></radialGradient><radialGradient id="iVcvQqc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.414)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="iRbhuVH" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 4.517 16.198)scale(.96684 1.14853)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iwYJnLd" cx="0" cy="0" r="1" gradientTransform="matrix(.66276 .2083 -.6426 2.04466 13.281 6.552)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="ibnAbPc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34669 0 0 -4.15128 17.26 5.91)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="ipUmNBd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.509 6.656)scale(1.51228 1.24851)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iRbxXBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.03228 -1.20313 5.83755 -.15663 15.991 8.884)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="iLto9ab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51548 .6379 0 17.099 5.32)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="igsSjEb" cx="0" cy="0" r="1" gradientTransform="matrix(.00176 -.4912 .53454 .00192 14.967 5.34)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iAx7CMb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8137 .24074 -.61497 -9.7421 17.54 6.353)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iv7JYZi" cx="0" cy="0" r="1" gradientTransform="matrix(1.51982 -1.30916 .3867 .44893 12.951 4.682)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="i6AFPSc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.15 10.716)scale(1.12599 .45011)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iDhlvTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10957 -.34437 0 16.21 6.52)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="idhHejb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68282 .31307 -.50312 -1.09734 16.262 6.264)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iojFzse" cx="0" cy="0" r="1" gradientTransform="matrix(.97945 -.48153 1.9373 3.9406 15.78 7.536)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i9XCcWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.57169 3.97461 0 13.652 4.611)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="isHd16D" cx="0" cy="0" r="1" gradientTransform="matrix(.0512 -1.12784 1.99831 .0907 18.182 5.2)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iKLOc7c" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 9.278 -1.48)scale(1.26733 .93028)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="i50m0Me" cx="0" cy="0" r="1" gradientTransform="rotate(60.726 6.374 14.142)scale(.6166 1.42777)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iqsgUBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.98805 0 0 -.3667 16.114 2.681)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iuBpQie" cx="0" cy="0" r="1" gradientTransform="matrix(1.44458 -2.28726 2.53405 1.60045 13.562 4.45)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ighqlIc" cx="0" cy="0" r="1" gradientTransform="rotate(-43.614 14.081 -19.275)scale(1.66082 3.04053)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="idfTYqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.45807 .17042 -.07135 .61047 16.785 3.73)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iHF4nOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36419 -.57928 0 16.98 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iVC6TMd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 9.794 -1.365)scale(.16981 .23378)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQ2hVkd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3642 -.57931 0 15.02 5.498)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="inVuysb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00347 -.22179 .2666 -.00417 14.892 5.596)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iI2NHFQ" cx="0" cy="0" r="1" gradientTransform="matrix(.28214 1.00697 -.96073 .26918 18.072 5.504)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="ihIpxie" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 14.768 -15.05)scale(.60046 .50331)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="ioLC9bd" cx="0" cy="0" r="1" gradientTransform="matrix(.2635 -.69596 .9299 .35206 18.286 5.826)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="ijde60c" cx="0" cy="0" r="1" gradientTransform="matrix(-.74436 0 0 -.83119 13.793 5.792)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iBku4oU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4114 .07062 -.0724 -.4218 13.794 5.793)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="ifXzzzb" width="2.311" height="8.028" x="11.403" y="12.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.407843 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/></filter><filter id="imoN3Ld" width="1.464" height="6.913" x="19.164" y="11.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".25"/></filter><filter id="iSxFavb" width="6.169" height="12.453" x="13.016" y="16.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/></filter><filter id="ibKpkwd" width="6.417" height="7.594" x="12.941" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.415686 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/></filter><filter id="iXmyxvc" width="3.316" height="1.848" x="12.434" y="28.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/></filter><filter id="ixwOuNj" width="6.594" height="13.766" x="12.841" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".5"/></filter><filter id="iXnxyhb" width="5.588" height="5.74" x="13.727" y="3.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_173" result="effect2_innerShadow_4002_173"/></filter><filter id="icSzqAb" width="2.784" height="3.302" x="14.544" y="4.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".5"/></filter><filter id="i3Zcq8c" width="1.043" height="1.502" x="15.479" y="5.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".05"/></filter><filter id="iLbMB8a" width="1.745" height=".782" x="15.128" y="6.904" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".05"/></filter><filter id="i0qt1Ke" width="5.778" height="4.027" x="13.111" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_173" result="effect2_innerShadow_4002_173"/></filter><filter id="ikqOP9c" width="1.105" height=".645" x="16.713" y="4.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/></filter><filter id="icq8zlb" width="1.105" height=".638" x="14.354" y="4.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/></filter><filter id="iC3CDMc" width="2.981" height="2.645" x="13.283" y="2.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_173"/><feGaussianBlur result="effect2_foregroundBlur_4002_173" stdDeviation=".05"/></filter><filter id="ibgd1FJ" width="2.739" height="2.495" x="16.014" y="2.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".05"/></filter><filter id="iQqNJtd" width=".463" height=".423" x="16.595" y="5.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".05"/></filter><filter id="iRMePbb" width=".62" height=".63" x="16.917" y="5.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".1"/></filter><filter id="iuJomFb" width=".663" height=".687" x="14.922" y="5.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".1"/></filter><filter id="ipL0Bue" width=".52" height=".427" x="14.639" y="5.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".05"/></filter><filter id="igRHbAd" width=".872" height="1.344" x="13.133" y="5.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".125"/></filter><filter id="iHpI9Qc" width="1.425" height="1.854" x="17.719" y="4.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".25"/></filter><filter id="iRi9Hbc" width="1.043" height=".484" x="14.336" y="4.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".05"/></filter><filter id="imWAT3c" width="1.043" height=".484" x="16.706" y="4.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".05"/></filter><filter id="iBOKTxK" width="2.09" height="1.076" x="16.531" y="2.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_173" stdDeviation=".1"/></filter><linearGradient id="i2bDogb" x1="12.466" x2="12.466" y1="12.781" y2="12.304" gradientUnits="userSpaceOnUse"><stop class="mea8vgbzb"/><stop offset="1" class="x8_6e5b0q"/></linearGradient><linearGradient id="izQrBVc" x1="19.747" x2="19.747" y1="12.867" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="kidhsabwy"/><stop offset="1" class="i08i0qbub"/></linearGradient><linearGradient id="ibWngWb" x1="16" x2="16" y1="16.011" y2="16.445" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="iglQ6Fe" x1="16" x2="16" y1="9.101" y2="16.062" gradientUnits="userSpaceOnUse"><stop class="hrtvttbtf"/><stop offset="1" class="nua72fb5w"/></linearGradient><linearGradient id="iB6Yhfe" x1="18.247" x2="16.5" y1="29.726" y2="29.523" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="iDq6Mbe" x1="18.315" x2="17.18" y1="6.666" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iy2hZBb" x1="16.376" x2="16" y1="6.212" y2="6.228" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iIKmAEc" x1="16" x2="16" y1="6.724" y2="6.515" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="i6O3Tlb" x1="16" x2="16" y1="5.509" y2="5.755" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iVDRyMe" x1="15.461" x2="15.604" y1="7.429" y2="7.054" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iP8c8OC" x1="19.076" x2="13.863" y1="3.367" y2="3.367" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="i0YieUc" x1="17.329" x2="17.188" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBX24Jb" x1="15.354" x2="15.214" y1="5.522" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYNb44d" x1="18.889" x2="18.347" y1="5.534" y2="6.511" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iCZDyHu" x1="13.374" x2="14.029" y1="5.85" y2="5.793" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="i2AKhbe" x1="18.431" x2="18.431" y1="5.363" y2="6.217" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-standing-medium-dark" /></template>
<style>
.a2h7exfgq {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.82 5.676l-.265.826c-.046.17.063.34.217.34h.329c.154 0 .262-.173.217-.34l-.222-.826c-.047-.182-.226-.182-.276 0");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b8lr97w5y {
  d: path("M18.182 6.47a.74.74 0 0 0 .406-.138v.418c0 .4-.239.758-.602.906q.116-.245.156-.53z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bca6h3crt {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.073 5.162c.293 0 .541.202.609.475a.123.123 0 0 1-.12.153H16.56a.103.103 0 0 1-.102-.122a.63.63 0 0 1 .615-.506");
}

.bg_y89dup {
  d: path("M19.888 20.44c.938-1.981.769-6.258.487-7.823h-1.672c.072 2.425-.155 5.253-.293 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.bn9csrb_g {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.927 5.162a.63.63 0 0 0-.608.475c-.02.078.04.153.12.153h1.001a.103.103 0 0 0 .102-.122a.63.63 0 0 0-.615-.506");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ck6qoaboh {
  d: path("M15.129 7.375h1.742v1.351a.871.871 0 0 1-1.742 0z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn77rwbmc {
  stop-color: var(--svg-color--f16440, #F16440);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.d_gvw4b_b {
  stop-color: var(--svg-color--ff391e, #FF391E);
  stop-opacity: 0;
}

.d2ckuvtgb {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M14.469 4.523a1.25 1.25 0 0 1 .78-.161a.124.124 0 0 1-.03.247a1 1 0 0 0-.656.149l-.007.005l-.002.001a.125.125 0 0 1-.152-.197z");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dq46or42q {
  d: path("m13.016 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f2f8y2bye {
  fill: var(--svg-color--5f323e, #5F323E);
  d: path("M12.668 19.16a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.114a.32.32 0 0 0-.074-.3a9 9 0 0 1-.355-.344");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fiqf-vbvi {
  d: path("M17.337 5.632a.4.4 0 0 0-.104-.208l-.116.128l.052.103z");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.g_ff25aes {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.486 4.648a1.04 1.04 0 0 1 .743-.17");
}

.gd7pfsb0f {
  stop-color: var(--svg-color--713b4b, #713B4B);
}

.gnk562b4c {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.828 5.589l-.238.825c-.049.17.068.34.234.34h.353c.165 0 .282-.173.233-.34l-.238-.825c-.051-.183-.29-.183-.344 0");
}

.gnkev6mug {
  d: path("m15.828 5.589l-.238.825c-.049.17.068.34.234.34h.353c.165 0 .282-.173.233-.34l-.238-.825c-.051-.183-.29-.183-.344 0");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.gz9jp_byg {
  d: path("M15.02 5.284a.4.4 0 0 0-.386.506h.774a.403.403 0 0 0-.388-.506");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hb9auub6r {
  fill: var(--svg-color--000, #000);
  d: path("M15.25 5.685a.23.23 0 0 0-.23-.23a.228.228 0 0 0-.204.335h.406a.2.2 0 0 0 .027-.105");
}

.hgrr3mz7l {
  d: path("M18.21 6.511q.044-.717.082-1.432a.723.723 0 0 1-.083 1.432");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hrtvttbtf {
  stop-color: var(--svg-color--ff7325, #FF7325);
}

.i08i0qbub {
  stop-color: var(--svg-color--ff381e, #FF381E);
  stop-opacity: 0;
}

.i1f5ne5hf {
  d: path("m18.219 6.217l.05-.854a.429.429 0 0 1-.05.854");
}

.i369cebot {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M17.882 3.369h-.934a.217.217 0 1 1 .035-.432c.242.039.564.093.78.146c.487.12.621.358.659.527a.68.68 0 0 0-.54-.241");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.io8qqi52v {
  d: path("M12.942 11.527a3.059 3.059 0 1 1 6.117 0v4.441a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jxrw3o5te {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("m13.84 16.382l.47 11.766h.812v-10.61h2.203v10.61h.672l.438-11.766z");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kidhsabwy {
  stop-color: var(--svg-color--ff381e, #FF381E);
}

.l_aygfawn {
  fill: var(--svg-color--89625b, #89625B);
  d: path("M19.888 20.44c.938-1.981.769-6.258.487-7.823h-1.672c.072 2.425-.155 5.253-.293 6.522a.29.29 0 0 0 .554.15l.117-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.201c-.062.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l7g1kibqg {
  stop-color: var(--svg-color--ff391e, #FF391E);
}

.l7ofdmb1v {
  d: path("M13.736 5.073a.722.722 0 0 0 .058 1.439q-.046-.72-.058-1.44");
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lgf7m9lol {
  d: path("M16.951 5.369c.029.038-.031.084-.099.135c-.068.05-.118.086-.147.048s.004-.11.072-.16s.145-.062.174-.023");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.liuzkqkjj {
  stop-color: var(--svg-color--713b4b, #713B4B);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.ltpbs0btu {
  d: path("M16.98 5.284a.4.4 0 0 1 .386.506h-.773a.402.402 0 0 1 .388-.506");
}

.m_7n9dy5d {
  stroke: var(--svg-color--976b64, #976B64);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.813 12.498c.125 1 .3 3.575 0 5.875");
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdbsecb0y {
  stop-color: var(--svg-color--ff863c, #FF863C);
}

.mea8vgbzb {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
}

.mkrizlbsk {
  fill: var(--svg-color--6d4147, #6D4147);
  d: path("M19.333 19.16a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.114a.32.32 0 0 1 .074-.3a9 9 0 0 0 .356-.344");
}

.moy5ghv8o {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m18.34 4.855l-.013-.283a.66.66 0 0 0-.631-.64h-.629c-.398 0-.762-.218-.953-.566c0 0 .324-.929.857-.793c.376.097.778.242 1.094.448c.783.51.687 1.4.275 1.834");
}

.msg66cbuc {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M17.676 4.572a.8.8 0 0 0-.31-.185c-.136-.043-.307-.054-.543-.025a.124.124 0 1 0 .03.247c.216-.027.348-.013.44.016a.6.6 0 0 1 .219.135a.124.124 0 1 0 .163-.188");
}

.mt6kztu9a {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.951 5.369c.029.038-.031.084-.099.135c-.068.05-.118.086-.147.048s.004-.11.072-.16s.145-.062.174-.023");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nua72fb5w {
  stop-color: var(--svg-color--ff4c2e, #FF4C2E);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.ochsfqbqa {
  d: path("M18.18 2.927a1.064 1.064 0 0 1 .521 1.606a.7.7 0 0 0-.122.393v.533a.8.8 0 0 0-.3-.12l.036-.721a.65.65 0 0 0-.62-.643h-.628c-.428 0-.816-.253-.992-.648a.3.3 0 0 0-.277-.188h-.571c-.828 0-1.5.68-1.5 1.517l.014.69a.8.8 0 0 0-.323.119v-.54a.7.7 0 0 0-.122-.392a1.07 1.07 0 0 1-.064-1.098c.13-.248.343-.42.583-.505a1.2 1.2 0 0 0 .622-.499a1.044 1.044 0 0 1 1.297-.409a.67.67 0 0 0 .536 0a1.044 1.044 0 0 1 1.302.424c.138.229.355.395.607.481");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.opik0i52p {
  d: path("M15.386 5.637c0-.129-.106-.215-.134-.241l-.13.125l.08.162z");
}

.osx_cvdvg {
  d: path("M20.468 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.933a.1.1 0 0 0 .097-.12");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.qes_hkbxf {
  fill: var(--svg-color--ff7a43, #FF7A43);
  d: path("M20.468 12.66c-.487-2.253-1.629-3.333-3.03-3.828v3.949h2.933a.1.1 0 0 0 .097-.12");
}

.qn28_pozx {
  d: path("m16.104 3.389l-.03-.062a.3.3 0 0 0-.276-.188h-.57c-.83 0-1.5.68-1.5 1.517v.124c-.153-.117-.345-.362-.345-.758c0-.481.35-.724.574-.88c.064-.043.117-.08.149-.113l.045-.047c.156-.167.436-.463.924-.593q.116-.03.231-.047c.468-.07.808.348.808.821v.22z");
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r1-m4ub1q {
  stop-color: var(--svg-color--985e4f, #985E4F);
}

.re73b6xet {
  fill: var(--svg-color--ff4326, #FF4326);
  d: path("M11.533 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.63a.1.1 0 0 1-.097-.12");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rr9h-xcpt {
  d: path("M13.834 7.15a1.76 1.76 0 0 0 1.744 1.53h.847c.883 0 1.629-.653 1.744-1.53c.053-.845.107-1.687.146-2.532a.65.65 0 0 0-.62-.643h-.628c-.428 0-.816-.253-.992-.648a.3.3 0 0 0-.276-.188h-.572c-.828 0-1.5.68-1.5 1.517c0 .835.052 1.657.107 2.494");
}

.s-8y-dbxo {
  stop-color: var(--svg-color--7e4653, #7E4653);
}

.s2118m3wh {
  cx: 14.899px;
  cy: 5.455px;
  rx: 0.175px;
  ry: 0.089px;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.shh_g2b0q {
  stop-color: var(--svg-color--874d4c, #874D4C);
  stop-opacity: 0;
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tfe_aug3p {
  d: path("M19.567 29.82v.242H16.5v-1.598h1.992c.102.368.575.754.817.915c.186.123.258.3.258.44");
}

.tqgsrbmpz {
  cx: 14.899px;
  cy: 5.455px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.175px;
  ry: 0.089px;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.ug0o70dol {
  fill: var(--svg-color--000, #000);
  d: path("M16.751 5.685c0-.128.102-.23.23-.23a.23.23 0 0 1 .203.335h-.406a.2.2 0 0 1-.027-.105");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.urz-1qguo {
  d: path("M13.717 5.371a.429.429 0 0 0 .038.844a35 35 0 0 1-.038-.844");
}

.utjcgnnio {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.82v.242H15.5v-1.598h-1.992c-.102.368-.574.754-.816.915a.54.54 0 0 0-.258.44");
}

.v_ft29bcw {
  stop-color: var(--svg-color--592631, #592631);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vjpr3ob1d {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.016 16.011l.484 12.454h2l.238-9.524c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.524h2l.485-12.454z");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vxc5s_bai {
  fill: var(--svg-color--774f4e, #774F4E);
  d: path("M12.112 20.44c-.938-1.981-.769-6.258-.487-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wk0xacdsc {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.104 3.389l-.03-.062a.3.3 0 0 0-.276-.188h-.57c-.83 0-1.5.68-1.5 1.517v.124c-.153-.117-.345-.362-.345-.758c0-.481.35-.724.574-.88c.064-.043.117-.08.149-.113l.045-.047c.156-.167.436-.463.924-.593q.116-.03.231-.047c.468-.07.808.348.808.821v.22z");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wysngjbll {
  stop-color: var(--svg-color--de5d25, #DE5D25);
  stop-opacity: 0;
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.x8_6e5b0q {
  stop-color: var(--svg-color--fb2d18, #FB2D18);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xb3grpq8z {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.127.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094A1.34 1.34 0 0 1 16 7.21Z");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xsr8v7bqw {
  stop-color: var(--svg-color--6c3537, #6C3537);
}

.y-nukfwnq {
  stop-color: var(--svg-color--ff863c, #FF863C);
  stop-opacity: 0;
}

.y0yuz4bps {
  d: path("m18.34 4.855l-.013-.283a.66.66 0 0 0-.631-.64h-.629c-.398 0-.762-.218-.953-.566c0 0 .324-.929.857-.793c.376.097.778.242 1.094.448c.783.51.687 1.4.275 1.834");
}

.y2mxoh-zc {
  stop-color: var(--svg-color--f16440, #F16440);
}

.y4_ytjb3b {
  stop-color: var(--svg-color--de5d25, #DE5D25);
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z23533p_d {
  d: path("M12.112 20.44c-.938-1.981-.769-6.258-.487-7.823h1.672c-.072 2.425.039 5.243.177 6.511c.012.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.262a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.201c.062.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.zhgg7cc0u {
  stop-color: var(--svg-color--6f353a, #6F353A);
  stop-opacity: 0;
}

.zmoflnhgm {
  d: path("M13.818 6.47a.74.74 0 0 1-.406-.138v.418c0 .4.239.758.602.906a1.8 1.8 0 0 1-.156-.53z");
}

.zmwvj69un {
  d: path("M16 7.21c-.228 0-.442-.054-.622-.148c-.061-.031-.127.038-.089.094a.85.85 0 0 0 .711.38a.85.85 0 0 0 .71-.38c.04-.058-.027-.125-.088-.094A1.34 1.34 0 0 1 16 7.21");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zyo2feblp {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.599 4.628a1.04 1.04 0 0 0-.744-.171");
}

.zzl9q_jda {
  d: path("M11.533 12.66c.486-2.253 1.628-3.333 3.03-3.828v3.949H11.63a.1.1 0 0 1-.097-.12");
}

</style>
