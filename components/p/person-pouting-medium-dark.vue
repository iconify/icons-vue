<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQmSc7c)" class="i5nxp9bgj"/><path fill="url(#iDu1gVb)" class="i5nxp9bgj"/><path fill="url(#ilMRhiQ)" class="i5nxp9bgj"/><rect fill="url(#ixNLEhQ)" class="ot57_nbzj"/><rect fill="url(#iMCAqye)" class="ot57_nbzj"/><path fill="url(#imYXh8W)" class="fkj9vvbxm"/><path fill="url(#imEjkJT)" class="k-esgj2gs"/><path fill="url(#ioaakzd)" class="k-esgj2gs"/><g filter="url(#itMXNre)"><path fill="url(#i5i1S5c)" class="ld3sv1b8b"/></g><path fill="url(#ii3iG7b)" class="ld3sv1b8b"/><path fill="url(#ivddmjd)" class="ld3sv1b8b"/><path fill="url(#i9M00Wc)" class="ld3sv1b8b"/><g filter="url(#iaTyePb)"><path fill="url(#iYb07Wb)" class="sj7bu1fks"/></g><path fill="url(#i1CV4ce)" class="tanh7nbyf"/><path fill="url(#iHLehYb)" class="zfm2yqqte"/><g filter="url(#ieaUNyc)"><path fill="url(#ijvPf9c)" class="n4sd57brv"/><path fill="url(#irTicWd)" class="n4sd57brv"/></g><path fill="url(#ifBYehc)" class="n4sd57brv"/><path fill="url(#id11cCe)" class="n4sd57brv"/><path fill="url(#iMt3qML)" class="n4sd57brv"/><path fill="url(#ifhuCSb)" class="n4sd57brv"/><path fill="url(#iVUfwtb)" class="n4sd57brv"/><path fill="url(#iGjD2yV)" class="n4sd57brv"/><path fill="url(#ihdNTEe)" class="n4sd57brv"/><g filter="url(#ibTEFee)"><path class="mye0c5brn"/></g><g filter="url(#i21nLac)"><path class="rjrqbhezo"/><path fill="url(#ijnLnWd)" class="qap_t1v6s"/><path fill="url(#iNzOgmd)" class="qap_t1v6s"/><path fill="url(#io0NVae)" class="qap_t1v6s"/><path fill="url(#irZwsCb)" class="qap_t1v6s"/><path fill="url(#isFqlPH)" class="qap_t1v6s"/></g><path fill="url(#i864GFs)" class="qap_t1v6s"/><path fill="url(#il1LMDj)" class="qap_t1v6s"/><g filter="url(#ilijQgc)"><path fill="url(#i5GEsQb)" class="key8r8kqj"/><path fill="url(#iNFYUtd)" class="key8r8kqj"/><path fill="url(#i5k4gbd)" class="key8r8kqj"/><path fill="url(#ishwPXz)" class="key8r8kqj"/><path fill="url(#iWfT2UB)" class="key8r8kqj"/></g><g filter="url(#iOpm9Pd)"><path class="tk4-xpbod"/><path fill="url(#iVxc2jb)" class="g-vonnbhi"/><path fill="url(#i9J3L3u)" class="g-vonnbhi"/></g><g filter="url(#iGWDoRc)"><path class="ii5q3bbae"/><path fill="url(#iLeM0zb)" class="upij0642d"/><path fill="url(#i9R01Yc)" class="upij0642d"/><path fill="url(#iAqQN4c)" class="upij0642d"/></g><path class="kdrcxuatb"/><path fill="url(#ikMRKZb)" class="q-2ounb_c"/><path class="kr6y9ty4f"/><g filter="url(#iRUS6Ib)"><path class="dqjceqz_t"/><path fill="url(#ivnRJfb)" class="m_j_eubma"/></g><g filter="url(#iV0SDKc)"><path fill="url(#iWn6ilb)" class="vuflnfbnm"/></g><path class="foam1_bmd"/><path fill="url(#iYFobab)" class="lg77x-byc"/><path class="cyltomoiy"/><g filter="url(#ihZjm8d)"><path fill="url(#iJUvwTa)" class="ibd338bcg"/></g><g filter="url(#ijuGbJc)"><ellipse transform="rotate(-27.914 13.551 9.988)" class="j9ck9-bhk"/><ellipse fill="url(#ia2ANid)" transform="rotate(-27.914 13.551 9.988)" class="jom0gg3hr"/></g><path fill="url(#iavazfd)" class="zc_qo__1e"/><path fill="url(#ifglL6d)" class="zc_qo__1e"/><path fill="url(#ivkqcLc)" class="zc_qo__1e"/><path fill="url(#inrg7Ib)" class="zc_qo__1e"/><path fill="url(#iRCdmqb)" class="tglmfebpl"/><path fill="url(#iZvdmJb)" class="tglmfebpl"/><g filter="url(#ijBMxKm)"><path fill="url(#iScJVVY)" class="wn4wizbwn"/></g><g filter="url(#ifTkV3O)"><path fill="url(#iRwNq1v)" class="ngyr-zbpt"/></g><g filter="url(#igybnSY)"><path fill="url(#iVl6mid)" class="k_oqfsr5k"/><path fill="url(#iogk5vA)" class="k_oqfsr5k"/></g><path class="m3w5xac2d"/><path stroke="url(#iq3DE7b)" class="fy39rtb_q"/><path stroke="url(#iPzTp9c)" class="fy39rtb_q"/><g filter="url(#iXvTr1c)"><rect class="yn1lrlxug"/></g><g filter="url(#iUPU7pc)"><rect class="xn46ycucp"/></g><g filter="url(#iAzE8Pg)"><path stroke="url(#i54MTGe)" class="r189_c-ek"/></g><g filter="url(#i2P43tE)"><path stroke="url(#iBXkedb)" class="utwgdriop"/></g><defs><radialGradient id="iQmSc7c" cx="0" cy="0" r="1" gradientTransform="matrix(2.02197 9.09668 -14.16842 3.14929 14.022 14.778)" gradientUnits="userSpaceOnUse"><stop class="khj8zwb0j"/><stop offset=".674" class="dt2jwkbti"/></radialGradient><radialGradient id="iDu1gVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.71875 9.5625 0 21.73 24.5)" gradientUnits="userSpaceOnUse"><stop class="osixu2bon"/><stop offset="1" class="bh4gs6bci"/></radialGradient><radialGradient id="ixNLEhQ" cx="0" cy="0" r="1" gradientTransform="rotate(52.035 -9.156 24.419)scale(2.78619 3.42691)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="j6xccjbtl"/><stop offset="1" class="q3_ltc6vo"/></radialGradient><radialGradient id="iMCAqye" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 1 -1.28354 1.60442 13.918 16.813)" gradientUnits="userSpaceOnUse"><stop class="q9z2_uxsx"/><stop offset="1" class="o8q-rhbvy"/></radialGradient><radialGradient id="ioaakzd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -9.0144 10.168 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="pyz9maawt"/><stop offset="1" class="j5lcx07ey"/></radialGradient><radialGradient id="i5i1S5c" cx="0" cy="0" r="1" gradientTransform="matrix(14.39624 1.34674 -.46749 4.99726 16.71 25.03)" gradientUnits="userSpaceOnUse"><stop class="otv8n7txk"/><stop offset="1" class="hphvzuxpa"/></radialGradient><radialGradient id="ii3iG7b" cx="0" cy="0" r="1" gradientTransform="matrix(.70684 1.42914 -5.7496 2.8437 17.536 26.805)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="y9p-y_b-v"/><stop offset="1" class="dvmraqbnh"/></radialGradient><radialGradient id="ivddmjd" cx="0" cy="0" r="1" gradientTransform="rotate(166.054 12.147 14.1)scale(5.39674 1.22772)" gradientUnits="userSpaceOnUse"><stop class="ihcoeb3rx"/><stop offset="1" class="m93hs_b1c"/></radialGradient><radialGradient id="i9M00Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.255 12.805 9.629)scale(3.73328 6.83692)" gradientUnits="userSpaceOnUse"><stop class="mn_upyxfg"/><stop offset=".499" class="ogbu1db9j"/></radialGradient><radialGradient id="iYb07Wb" cx="0" cy="0" r="1" gradientTransform="matrix(.71233 3.34406 -18.37025 3.9131 16.143 24.719)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i0t26g9ku"/><stop offset="1" class="oknu-2bcc"/></radialGradient><radialGradient id="i1CV4ce" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.789 20.866)scale(2.146 2.54928)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iHLehYb" cx="0" cy="0" r="1" gradientTransform="matrix(1.47106 .46233 -1.42632 4.53833 9.961 12.423)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="ijvPf9c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.20873 0 0 -9.21419 18.793 10.997)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="irTicWd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.505 8.21)scale(3.35666 2.7712)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="id11cCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01849 12.37807 -10.25056 -.84343 17.571 5.105)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="axnqidyuu"/><stop offset="1" class="j7pnfkbxw"/></radialGradient><radialGradient id="iMt3qML" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14415 1.41589 0 18.434 9.689)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="ifhuCSb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.737 -2.009)scale(1.09028 1.18649)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iVUfwtb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46491 .53435 -1.36499 -21.62356 19.416 11.981)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iGjD2yV" cx="0" cy="0" r="1" gradientTransform="matrix(3.3734 -2.9058 .85832 .99644 9.229 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="ihdNTEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2338 2.4883 -.99468 -.09346 21.52 8.09)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iNzOgmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24321 -.76438 0 16.46 12.352)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="irZwsCb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51558 .69488 -1.11673 -2.43567 16.576 11.785)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="il1LMDj" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.91 9.038)scale(1.76588 2.5486)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="iNFYUtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.48852 8.82206 0 10.785 8.115)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i5k4gbd" cx="0" cy="0" r="1" gradientTransform="matrix(.11362 -2.50335 4.43545 .20132 20.838 9.42)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ishwPXz" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.517 -1.423)scale(2.81296 2.06486)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iWfT2UB" cx="0" cy="0" r="1" gradientTransform="matrix(.9018 1.4696 -3.4029 2.08815 15.094 1.58)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iVxc2jb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.19308 0 0 -.81394 16.248 3.831)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i9J3L3u" cx="0" cy="0" r="1" gradientTransform="matrix(3.2064 -5.0768 5.62458 3.55236 10.585 7.76)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iLeM0zb" cx="0" cy="0" r="1" gradientTransform="matrix(3.0472 0 0 1.1914 19.397 4.605)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="i9R01Yc" cx="0" cy="0" r="1" gradientTransform="matrix(2.66893 -2.54284 4.65529 4.88612 18.62 7.632)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iAqQN4c" cx="0" cy="0" r="1" gradientTransform="matrix(3.23634 .37827 -.15838 1.355 17.737 6.16)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ikMRKZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .80835 -1.28577 0 18.17 10.084)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ivnRJfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23107 -.29776 .40995 -.31813 17.942 10.168)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYFobab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8084 -1.28584 0 13.821 10.084)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ia2ANid" cx="0" cy="0" r="1" gradientTransform="matrix(-.0077 -.49228 .59174 -.00926 13.536 10.302)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifglL6d" cx="0" cy="0" r="1" gradientTransform="matrix(.62625 2.23507 -2.13243 .5975 20.596 10.098)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="ivkqcLc" cx="0" cy="0" r="1" gradientTransform="matrix(.7849 -1.07715 .90287 .6579 20.955 10.64)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="inrg7Ib" cx="0" cy="0" r="1" gradientTransform="matrix(.58485 -1.54475 2.064 .78144 21.069 10.812)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iZvdmJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65219 0 0 -1.8449 11.098 10.736)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iScJVVY" cx="0" cy="0" r="1" gradientTransform="matrix(-.91313 .15672 -.1607 -.93625 11.099 10.738)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iq3DE7b" cx="0" cy="0" r="1" gradientTransform="rotate(-67.758 19.007 -5.327)scale(.40861 .97456)" gradientUnits="userSpaceOnUse"><stop class="efy10hbxv"/><stop offset="1" class="yjfxrnmqp"/></radialGradient><radialGradient id="iPzTp9c" cx="0" cy="0" r="1" gradientTransform="matrix(.2201 -.23857 .1633 .15066 14.786 14.282)" gradientUnits="userSpaceOnUse"><stop class="efy10hbxv"/><stop offset="1" class="yjfxrnmqp"/></radialGradient><filter id="itMXNre" width="19.161" height="7.244" x="8.205" y="22.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.219608 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4632"/></filter><filter id="iaTyePb" width="19.009" height="7.177" x="5.218" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.262745 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4632"/></filter><filter id="ieaUNyc" width="11.183" height="12.496" x="10.951" y="4.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4632"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4632" result="effect2_innerShadow_13036_4632"/></filter><filter id="ibTEFee" width="3.74" height="4.889" x="13.984" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".5"/></filter><filter id="i21nLac" width="2.27" height="3.289" x="14.86" y="9.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".1"/></filter><filter id="ilijQgc" width="12.826" height="8.328" x="9.583" y="1.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4632"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4632" result="effect2_innerShadow_13036_4632"/></filter><filter id="iOpm9Pd" width="7.062" height="6.472" x="9.686" y="2.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4632"/><feGaussianBlur result="effect2_foregroundBlur_13036_4632" stdDeviation=".25"/></filter><filter id="iGWDoRc" width="6.783" height="6.162" x="15.587" y="2.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".25"/></filter><filter id="iRUS6Ib" width=".785" height=".695" x="17.438" y="9.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".05"/></filter><filter id="iV0SDKc" width=".889" height=".912" x="18.274" y="9.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".1"/></filter><filter id="ihZjm8d" width=".984" height="1.038" x="13.848" y="9.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".1"/></filter><filter id="ijuGbJc" width=".91" height=".703" x="13.096" y="9.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".05"/></filter><filter id="ijBMxKm" width="1.326" height="2.372" x="9.936" y="9.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".125"/></filter><filter id="ifTkV3O" width="1.943" height="2.896" x="20.42" y="9.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".25"/></filter><filter id="igybnSY" width="1.224" height=".712" x="15.43" y="14.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".05"/></filter><filter id="iXvTr1c" width="2.748" height=".641" x="12.459" y="8.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4632"/></filter><filter id="iUPU7pc" width="2.748" height=".641" x="16.977" y="8.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4632"/></filter><filter id="iAzE8Pg" width="2.77" height=".7" x="16.975" y="8.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".125"/></filter><filter id="i2P43tE" width="2.77" height=".7" x="12.48" y="8.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4632" stdDeviation=".125"/></filter><linearGradient id="ilMRhiQ" x1="17.426" x2="17.426" y1="30.545" y2="26.941" gradientUnits="userSpaceOnUse"><stop class="s9luuo8wr"/><stop offset="1" class="mw-dyzb9n"/></linearGradient><linearGradient id="imYXh8W" x1="22.967" x2="24.881" y1="22.656" y2="22.656" gradientUnits="userSpaceOnUse"><stop offset=".17" class="h-4-uqb4q"/><stop offset="1" class="k-xmaur5i"/></linearGradient><linearGradient id="imEjkJT" x1="8.98" x2="6.915" y1="23.5" y2="23.037" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ev32s2_gl"/><stop offset="1" class="p1zhkctql"/></linearGradient><linearGradient id="ifBYehc" x1="21.134" x2="18.614" y1="12.676" y2="12.676" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ijnLnWd" x1="16.831" x2="15.995" y1="11.669" y2="11.704" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="io0NVae" x1="15.995" x2="15.995" y1="12.804" y2="12.341" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="isFqlPH" x1="15.995" x2="15.995" y1="10.109" y2="10.653" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="i864GFs" x1="16.41" x2="16.41" y1="12.941" y2="12.749" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="i5GEsQb" x1="22.822" x2="11.252" y1="5.355" y2="5.355" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iWn6ilb" x1="18.945" x2="18.632" y1="10.137" y2="10.33" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJUvwTa" x1="14.563" x2="14.25" y1="10.137" y2="10.33" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iavazfd" x1="22.408" x2="21.206" y1="10.164" y2="12.333" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iRCdmqb" x1="10.167" x2="11.62" y1="10.866" y2="10.739" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iRwNq1v" x1="21.392" x2="21.392" y1="9.784" y2="11.68" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iVl6mid" x1="16.113" x2="15.386" y1="14.439" y2="14.706" gradientUnits="userSpaceOnUse"><stop class="jcmxh3b0z"/><stop offset="1" class="eudakpbxz"/></linearGradient><linearGradient id="iogk5vA" x1="16.089" x2="16.089" y1="15.009" y2="14.657" gradientUnits="userSpaceOnUse"><stop offset=".207" class="sb1cy_b0z"/><stop offset="1" class="vz_mmeqnb"/></linearGradient><linearGradient id="i54MTGe" x1="19.466" x2="16.648" y1="8.886" y2="8.886" gradientUnits="userSpaceOnUse"><stop offset=".333" class="bfhgpjbxp"/><stop offset="1" class="jz-x_6ndp"/></linearGradient><linearGradient id="iBXkedb" x1="14.971" x2="12.153" y1="8.886" y2="8.886" gradientUnits="userSpaceOnUse"><stop offset=".333" class="bfhgpjbxp"/><stop offset="1" class="jz-x_6ndp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-pouting-medium-dark" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.axnqidyuu {
  stop-color: var(--svg-color--804776, #804776);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bfhgpjbxp {
  stop-color: var(--svg-color--463c3b, #463C3B);
}

.bh4gs6bci {
  stop-color: var(--svg-color--ff6646, #FF6646);
  stop-opacity: 0;
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
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

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cyltomoiy {
  fill: var(--svg-color--000, #000);
  d: path("M14.329 10.498a.507.507 0 0 0-.51-.51a.507.507 0 0 0-.452.744h.901a.5.5 0 0 0 .06-.234");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dqjceqz_t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.106 9.796c.064.085-.069.188-.22.301c-.15.113-.262.192-.325.107s.007-.245.158-.357c.15-.113.324-.135.387-.05");
}

.dt2jwkbti {
  stop-color: var(--svg-color--fc4a2b, #FC4A2B);
}

.dvmraqbnh {
  stop-color: var(--svg-color--6a394c, #6A394C);
  stop-opacity: 0;
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

.efy10hbxv {
  stop-color: var(--svg-color--8c6864, #8C6864);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.eudakpbxz {
  stop-color: var(--svg-color--83605d, #83605D);
}

.ev32s2_gl {
  stop-color: var(--svg-color--ff5437, #FF5437);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fkj9vvbxm {
  d: path("M22.967 18.124a10.48 10.48 0 0 1 3.827 7.02l-3.827-.18z");
}

.foam1_bmd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.613 9.338c-.65 0-1.2.448-1.35 1.055a.273.273 0 0 0 .267.34h2.223a.23.23 0 0 0 .226-.272a1.396 1.396 0 0 0-1.366-1.123");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fy39rtb_q {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.14 14.283c.486-.334 1.208-.335 1.7 0a.279.279 0 0 0 .313-.46c-.68-.463-1.651-.464-2.328.001a.278.278 0 1 0 .315.46");
}

.g-vonnbhi {
  d: path("M16.227 5.401a2 2 0 0 1-.066-.136a.66.66 0 0 0-.613-.417H14.28c-1.839 0-3.33 1.507-3.33 3.367v.274c-.338-.258-.764-.801-.764-1.681c0-1.068.779-1.608 1.276-1.952c.14-.098.258-.18.33-.253l.098-.104c.349-.37.97-1.028 2.053-1.315a5.5 5.5 0 0 1 1.5-.165c.472.011.805.42.805.892v1.477z");
}

.h-4-uqb4q {
  stop-color: var(--svg-color--ff491d, #FF491D);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hphvzuxpa {
  stop-color: var(--svg-color--92635f, #92635F);
}

.i0t26g9ku {
  stop-color: var(--svg-color--997066, #997066);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i5nxp9bgj {
  d: path("m9.2 24.938l-3.906.183c.577-5.253 5.03-9.34 10.436-9.34h.625c5.415 0 9.872 4.099 10.44 9.362l-4.378-.206v5.188H9.2z");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibd338bcg {
  d: path("M14.632 10.393c0-.287-.234-.479-.297-.537l-.287.278l.176.36z");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ihcoeb3rx {
  stop-color: var(--svg-color--997263, #997263);
}

.ii5q3bbae {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.189 8.656l-.03-.629c-.01-.76-.638-1.388-1.4-1.42h-1.394a2.41 2.41 0 0 1-2.116-1.255s-.058-.133-.118-.36c-.258-.97.67-1.697 1.642-1.449c.925.236 1.968.615 2.773 1.14c1.738 1.134 1.558 3.011.643 3.973");
}

.j5lcx07ey {
  stop-color: var(--svg-color--e45b4e, #E45B4E);
}

.j6xccjbtl {
  stop-color: var(--svg-color--763c3c, #763C3C);
}

.j7pnfkbxw {
  stop-color: var(--svg-color--804776, #804776);
}

.j9ck9-bhk {
  cx: 13.551px;
  cy: 9.988px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.388px;
  ry: 0.196px;
}

.jcmxh3b0z {
  stop-color: var(--svg-color--784742, #784742);
}

.jom0gg3hr {
  cx: 13.551px;
  cy: 9.988px;
  rx: 0.388px;
  ry: 0.196px;
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jz-x_6ndp {
  stop-color: var(--svg-color--463c3b, #463C3B);
  stop-opacity: 0;
}

.k_oqfsr5k {
  d: path("M16.554 14.88a.512.512 0 0 0-1.024 0z");
}

.k-esgj2gs {
  d: path("m5.294 25.121l3.847-.16l.058.182h.031v-7.108a10.5 10.5 0 0 0-3.936 7.086");
}

.k-xmaur5i {
  stop-color: var(--svg-color--ff6747, #FF6747);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kdrcxuatb {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.378 9.338c.65 0 1.2.448 1.35 1.055a.273.273 0 0 1-.267.34h-2.223a.23.23 0 0 1-.226-.272a1.39 1.39 0 0 1 1.366-1.123");
}

.key8r8kqj {
  d: path("M20.832 4.378c.513.176.973.534 1.263 1.047a2.36 2.36 0 0 1-.105 2.518c-.175.256-.27.56-.27.87v1.184a1.7 1.7 0 0 0-.665-.267l.079-1.6a1.444 1.444 0 0 0-1.374-1.427h-1.395a2.41 2.41 0 0 1-2.204-1.438a.66.66 0 0 0-.613-.417H14.28c-1.84 0-3.33 1.507-3.33 3.367l.031 1.532a1.7 1.7 0 0 0-.717.262V8.814c0-.31-.095-.615-.27-.871a2.38 2.38 0 0 1-.143-2.437a2.34 2.34 0 0 1 1.295-1.123a2.67 2.67 0 0 0 1.38-1.106a2.32 2.32 0 0 1 2.88-.908c.38.165.808.165 1.188 0c.28-.118.587-.187.91-.187c.84 0 1.574.454 1.98 1.127a2.52 2.52 0 0 0 1.348 1.07");
}

.khj8zwb0j {
  stop-color: var(--svg-color--a72503, #A72503);
}

.kr6y9ty4f {
  fill: var(--svg-color--000, #000);
  d: path("M17.662 10.498c0-.283.227-.51.51-.51a.507.507 0 0 1 .452.744h-.901a.46.46 0 0 1-.06-.234");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.ld3sv1b8b {
  d: path("M26.417 28.719c.6-1.05.453-2.813.375-3.598l-3.938-.168c-.412.213-1.526.089-2.03 0l-8.898-1.406c-.617-.117-2.097-.232-2.774.133c-.765.412-1 1.192-.937 1.578c4.27 1.531 12.632 4.562 13.757 4.812c1.82.313 3.695-.039 4.445-1.351");
}

.lg77x-byc {
  d: path("M13.82 9.608a.89.89 0 0 0-.857 1.124h1.717a1 1 0 0 0 .033-.234a.895.895 0 0 0-.894-.89");
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m_j_eubma {
  d: path("M18.106 9.796c.064.085-.069.188-.22.301c-.15.113-.262.192-.325.107s.007-.245.158-.357c.15-.113.324-.135.387-.05");
}

.m3w5xac2d {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M15.14 14.283c.486-.334 1.208-.335 1.7 0a.279.279 0 0 0 .313-.46c-.68-.463-1.651-.464-2.328.001a.278.278 0 1 0 .315.46");
}

.m93hs_b1c {
  stop-color: var(--svg-color--997263, #997263);
  stop-opacity: 0;
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mn_upyxfg {
  stop-color: var(--svg-color--74584d, #74584D);
}

.mw-dyzb9n {
  stop-color: var(--svg-color--d73726, #D73726);
  stop-opacity: 0;
}

.mye0c5brn {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.595 10.48l-.588 1.831c-.1.377.14.754.482.754h.73c.341 0 .582-.383.482-.754l-.493-1.831c-.105-.406-.502-.406-.613 0");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n4sd57brv {
  d: path("M11.188 13.751a3.9 3.9 0 0 0 3.872 3.394h1.88a3.9 3.9 0 0 0 3.87-3.394c.118-1.876.237-3.746.324-5.621a1.444 1.444 0 0 0-1.374-1.427h-1.395a2.41 2.41 0 0 1-2.204-1.438a.66.66 0 0 0-.613-.417H14.28c-1.84 0-3.33 1.507-3.33 3.367c0 1.854.117 3.678.238 5.536");
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.ngyr-zbpt {
  d: path("M20.92 11.68q.059-.948.11-1.896a.952.952 0 0 1-.11 1.896");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o8q-rhbvy {
  stop-color: var(--svg-color--64332a, #64332A);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogbu1db9j {
  stop-color: var(--svg-color--74584d, #74584D);
  stop-opacity: 0;
}

.oknu-2bcc {
  stop-color: var(--svg-color--85505f, #85505F);
}

.osixu2bon {
  stop-color: var(--svg-color--ff6547, #FF6547);
}

.ot57_nbzj {
  width: 4.223px;
  height: 6.028px;
  x: 13.918px;
  y: 12.876px;
  rx: 2.111px;
}

.otv8n7txk {
  stop-color: var(--svg-color--8c655f, #8C655F);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p1zhkctql {
  stop-color: var(--svg-color--ff3a19, #FF3A19);
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

.pyz9maawt {
  stop-color: var(--svg-color--e45b4e, #E45B4E);
  stop-opacity: 0;
}

.q-2ounb_c {
  d: path("M18.172 9.608a.89.89 0 0 1 .856 1.124h-1.717a.893.893 0 0 1 .86-1.124");
}

.q3_ltc6vo {
  stop-color: var(--svg-color--8f5549, #8F5549);
}

.q9z2_uxsx {
  stop-color: var(--svg-color--64332a, #64332A);
}

.qap_t1v6s {
  d: path("m15.615 10.285l-.53 1.831c-.108.377.151.754.519.754h.783c.368 0 .627-.383.519-.754l-.53-1.832c-.113-.405-.643-.405-.761 0");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
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

.r189_c-ek {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.325 8.886h2.07");
}

.rjrqbhezo {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.615 10.285l-.53 1.831c-.108.377.151.754.519.754h.783c.368 0 .627-.383.519-.754l-.53-1.832c-.113-.405-.643-.405-.761 0");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s9luuo8wr {
  stop-color: var(--svg-color--d73726, #D73726);
}

.sb1cy_b0z {
  stop-color: var(--svg-color--82555b, #82555B);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sj7bu1fks {
  d: path("M5.668 28.719c-.6-1.05-.453-2.813-.375-3.598l3.937-.168c.413.213 1.527.089 2.032 0l9.672-1.562c.617-.118 1.448-.177 2.125.187c.728.392.7.965.642 1.352a.1.1 0 0 1-.064.078c-4.285 1.54-12.404 4.813-13.524 5.062c-1.82.313-3.695-.039-4.445-1.351");
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

.tanh7nbyf {
  d: path("M20.839 12.242c.334-.01.647-.124.901-.308v.928c0 .89-.53 1.683-1.336 2.012a4 4 0 0 0 .345-1.176z");
}

.tglmfebpl {
  d: path("M10.97 9.14a1.62 1.62 0 0 0-1.387 1.592c0 .856.67 1.555 1.515 1.6a78 78 0 0 1-.129-3.192");
}

.tk4-xpbod {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M16.227 5.401a2 2 0 0 1-.066-.136a.66.66 0 0 0-.613-.417H14.28c-1.839 0-3.33 1.507-3.33 3.367v.274c-.338-.258-.764-.801-.764-1.681c0-1.068.779-1.608 1.276-1.952c.14-.098.258-.18.33-.253l.098-.104c.349-.37.97-1.028 2.053-1.315a5.5 5.5 0 0 1 1.5-.165c.472.011.805.42.805.892v1.477z");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.upij0642d {
  d: path("m21.189 8.656l-.03-.629c-.01-.76-.638-1.388-1.4-1.42h-1.394a2.41 2.41 0 0 1-2.116-1.255s-.058-.133-.118-.36c-.258-.97.67-1.697 1.642-1.449c.925.236 1.968.615 2.773 1.14c1.738 1.134 1.558 3.011.643 3.973");
}

.utwgdriop {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.83 8.886h2.07");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vuflnfbnm {
  d: path("M18.964 10.38a.84.84 0 0 0-.231-.46l-.259.284l.117.227z");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vz_mmeqnb {
  stop-color: var(--svg-color--82555b, #82555B);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wn4wizbwn {
  d: path("M10.929 9.803a.952.952 0 0 0 .083 1.872a78 78 0 0 1-.083-1.872");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xn46ycucp {
  width: 2.648px;
  height: 0.541px;
  x: 16.977px;
  y: 8.662px;
  fill: var(--svg-color--2f1e1d, #2F1E1D);
  rx: 0.271px;
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y9p-y_b-v {
  stop-color: var(--svg-color--6a394c, #6A394C);
}

.yjfxrnmqp {
  stop-color: var(--svg-color--8c6864, #8C6864);
  stop-opacity: 0;
}

.yn1lrlxug {
  width: 2.648px;
  height: 0.541px;
  x: 12.459px;
  y: 8.662px;
  fill: var(--svg-color--2f1e1d, #2F1E1D);
  rx: 0.271px;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zc_qo__1e {
  d: path("M20.9 12.333q.099-1.59.183-3.18a1.604 1.604 0 0 1-.184 3.18");
}

.zfm2yqqte {
  d: path("M11.152 12.242a1.64 1.64 0 0 1-.901-.308v.928c0 .89.53 1.683 1.335 2.012a4 4 0 0 1-.344-1.176z");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
