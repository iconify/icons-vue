<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#idY1NOc)" class="u2c1s-bxw"/><path fill="url(#ic5elDc)" class="o4vr40baf"/><path fill="url(#iIV9Gce)" class="o4vr40baf"/><g filter="url(#ifwPSKe)"><path fill="url(#iXfi1Wj)" class="aykd0o_jp"/><path fill="url(#iEBOSCA)" class="aykd0o_jp"/></g><path class="qbgz35bzv"/><path fill="url(#igh1rnT)" class="l4pn8lb1x"/><path fill="url(#iGvpcdJ)" class="vsa1kss6t"/><path fill="url(#iNClo1d)" class="vsa1kss6t"/><path fill="url(#iupIQDN)" class="yhh4ofd4k"/><path fill="url(#iiZ7ASh)" class="yhh4ofd4k"/><g filter="url(#iY3DwCK)"><path fill="url(#i7FxBLL)" class="mwg3cubiz"/><path fill="url(#iliMnLb)" class="mwg3cubiz"/><path fill="url(#i34qkXd)" class="mwg3cubiz"/></g><path fill="url(#img9TcU)" class="mwg3cubiz"/><path fill="url(#iwwzFJe)" class="mwg3cubiz"/><path fill="url(#iXfVx9b)" class="n2kxvdreg"/><path fill="url(#io6tO6c)" class="s9qqxfquy"/><path fill="url(#iYOw8he)" class="s9qqxfquy"/><g filter="url(#icmEtCb)"><path class="jgnhnrbnn"/><path fill="url(#iARgEhd)" class="yvjrxccgr"/></g><g filter="url(#isVifMe)"><path fill="url(#iTnKf7b)" class="j5uok4b4y"/></g><path fill="url(#iC6blsd)" class="l_7340byb"/><path fill="url(#ivKVHOR)" class="l_7340byb"/><g filter="url(#iKAvDLT)"><path fill="url(#i1yLmIc)" class="lwwg_6bee"/></g><path fill="url(#icGCZ7b)" class="wpfophm-a"/><path fill="url(#iuXXMlb)" class="wpfophm-a"/><path fill="url(#iWFmGHb)" class="rfy0m2bqt"/><path fill="url(#ip6g0Le)" class="c30axybib"/><path fill="url(#iL601yb)" class="c30axybib"/><path fill="url(#iNl8X9d)" class="c30axybib"/><path fill="url(#itjQXNJ)" class="c30axybib"/><path fill="url(#ijEX0Yd)" class="c30axybib"/><g filter="url(#iWHs2Bb)"><path class="v0fgrdmwe"/></g><g filter="url(#itjIUgb)"><path fill="url(#iWF1LMb)" class="e8p-d1bsh"/></g><g filter="url(#iUcuH8c)"><path fill="url(#iY4C80d)" class="v4i99-8yk"/></g><path fill="url(#iemd7lb)" class="v4i99-8yk"/><path fill="url(#i34CwMb)" class="v4i99-8yk"/><path fill="url(#iawKrHc)" class="v4i99-8yk"/><path fill="url(#iZPHKsG)" class="v4i99-8yk"/><g filter="url(#iJ8zvme)"><path class="s04hhyilv"/></g><g filter="url(#iTkHoQN)"><path class="mnus8s-ig"/><path fill="url(#ilIq4Dd)" class="vv2pjr99s"/><path fill="url(#i2NIHmb)" class="vv2pjr99s"/><path fill="url(#iQ5pRMi)" class="vv2pjr99s"/><path fill="url(#i8vF2pc)" class="vv2pjr99s"/><path fill="url(#itVK0te)" class="vv2pjr99s"/></g><g filter="url(#ilBGOeb)"><path stroke="url(#idqkpGb)" class="f0jvz71gp"/></g><path class="sddxoj3pl"/><path fill="url(#im99OMe)" class="szj0on_us"/><path fill="url(#ihV0Usb)" class="szj0on_us"/><path fill="url(#iLtLKCd)" class="bo0hllbsr"/><path fill="url(#icp5sOc)" class="bo0hllbsr"/><path fill="url(#i3sIZPd)" class="lfkx8fbxd"/><path fill="url(#iM96rNe)" class="lfkx8fbxd"/><path fill="url(#i2QYVjb)" class="lfkx8fbxd"/><g filter="url(#ivkl3xc)"><path class="mzw4fybdm"/></g><path class="oeyonmbaf"/><path fill="url(#iLKaEpL)" class="xgh9w-b7r"/><path class="cfx5jhbrb"/><g filter="url(#i6uVVKe)"><path class="nz0052iet"/><path fill="url(#ip1vhab)" class="v6gtvtu6m"/></g><g filter="url(#i0tlp8s)"><path fill="url(#ifK0wfD)" class="re4_t4kfi"/></g><path class="yea69orbb"/><path fill="url(#iScrrRd)" class="k2g9ghb8b"/><path class="g_jsgepxt"/><g filter="url(#icxD0oe)"><path fill="url(#iZtU3Gb)" class="lg02bl6eh"/></g><g filter="url(#iPtE00a)"><ellipse transform="rotate(-27.914 13.51 9.895)" class="zg5_mkbdg"/><ellipse fill="url(#iO36rNb)" transform="rotate(-27.914 13.51 9.895)" class="qqarjpbxn"/></g><g filter="url(#itzEirc)"><path fill="url(#ii2yZuc)" class="c4o9i3oxt"/><path fill="url(#i2DjJom)" class="c4o9i3oxt"/><path fill="url(#iIBtCdb)" class="c4o9i3oxt"/><path fill="url(#iIb23Ge)" class="c4o9i3oxt"/><path fill="url(#iPFNYfS)" class="c4o9i3oxt"/></g><g filter="url(#iFrW6Mb)"><path stroke="url(#iw44eFd)" class="flqkiabjb"/></g><g filter="url(#iuAwe1c)"><path stroke="url(#itr8zVz)" class="ew2j-0-9a"/></g><g filter="url(#inttRqc)"><path stroke="url(#iCdVKhc)" class="nm8m6ccmy"/></g><g filter="url(#ipcBT4b)"><path clip-rule="evenodd" class="k6k2nrb_g"/></g><g filter="url(#iMnuNWc)"><path clip-rule="evenodd" class="udh7vik5k"/></g><g filter="url(#igIPPxP)"><path class="jll7tfk4f"/></g><g filter="url(#isfTcGe)"><path class="i6uu1db5d"/></g><defs><radialGradient id="idY1NOc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.818 3.982)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="ic5elDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.693 5.144)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="iEBOSCA" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.618 3.928)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="igh1rnT" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.93 16.307)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iNClo1d" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.787 25.27)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iiZ7ASh" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.96 24.732)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="i7FxBLL" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16 16.176)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="i34qkXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.145 19.574)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iwwzFJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.393 15.992)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iXfVx9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.92 19.674)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="io6tO6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87968 -1.90863 0 15.93 16.813)" gradientUnits="userSpaceOnUse"><stop class="s7aakmgnr"/><stop offset="1" class="l212nr2yp"/></radialGradient><radialGradient id="iYOw8he" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.50225 -2.55179 0 15.93 15.352)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="az3jcdmty"/><stop offset=".944" class="z48shob3w"/></radialGradient><radialGradient id="iARgEhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.99999 -1.375 1.3434 -.977 11.38 12.126)" gradientUnits="userSpaceOnUse"><stop class="en-2vgkms"/><stop offset="1" class="vvdbjrbwx"/></radialGradient><radialGradient id="iTnKf7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46687 0 0 -2.17002 11.25 10.8)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="ebnsn321w"/><stop offset="1" class="quk3dgi1t"/></radialGradient><radialGradient id="ivKVHOR" cx="0" cy="0" r="1" gradientTransform="rotate(-51.009 23.387 -16.11)scale(1.68866)" gradientUnits="userSpaceOnUse"><stop class="guri77_rx"/><stop offset="1" class="jvouqxrlb"/></radialGradient><radialGradient id="i1yLmIc" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 5.34 15.515)scale(1.11515)" gradientUnits="userSpaceOnUse"><stop class="f4dh4oqdr"/><stop offset=".912" class="uspdh30af"/></radialGradient><radialGradient id="icGCZ7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.03903 -.98438 2.30834 2.43648 20.4 8.472)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="rb2mtukpy"/><stop offset=".879" class="u4h3exu9c"/></radialGradient><radialGradient id="iuXXMlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.97272 .98047 -.09594 .19302 19.898 7.172)" gradientUnits="userSpaceOnUse"><stop class="qf5kn-bed"/><stop offset="1" class="gir6ssbjp"/></radialGradient><radialGradient id="iWFmGHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1641 -.71876 .94072 -1.52358 11.602 8.8)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="fuhh3957a"/><stop offset=".94" class="tsc202y0r"/></radialGradient><radialGradient id="iL601yb" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.528 11.796)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="ijEX0Yd" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.94 18.832)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iY4C80d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9544 1.19435 -2.01845 -10.06296 19.451 10.404)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="d45qhhb2k"/><stop offset="1" class="zmlcnx4wm"/></radialGradient><radialGradient id="iemd7lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13592 1.13266 0 14.095 9.676)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="lxwdhqbih"/><stop offset="1" class="gczjqeobw"/></radialGradient><radialGradient id="i34CwMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.04388 1.15848 0 18.427 9.48)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b9-vno8aa"/><stop offset="1" class="gczjqeobw"/></radialGradient><radialGradient id="iawKrHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.73704 -10.9444 0 16 8.481)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="asnyj72hm"/><stop offset="1" class="ppasf06ij"/></radialGradient><radialGradient id="iZPHKsG" cx="0" cy="0" r="1" gradientTransform="rotate(137.827 8.073 6.853)scale(3.58407 2.1419)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="r5erk965r"/><stop offset="1" class="dfix_n5sh"/></radialGradient><radialGradient id="i2NIHmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22684 -.76458 0 16.465 12.26)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="i8vF2pc" cx="0" cy="0" r="1" gradientTransform="rotate(156.852 7.09 7.563)scale(1.64873 2.52797)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="im99OMe" cx="0" cy="0" r="1" gradientTransform="rotate(154.424 11.43 15.264)scale(2.44794 2.40172)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="ihV0Usb" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.529 23.64)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="icp5sOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.113 24.793)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="i3sIZPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.137 21.613)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="iM96rNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.638 21.996)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="iLKaEpL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 18.214 9.992)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ip1vhab" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.982 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iScrrRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 13.786 9.992)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iO36rNb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 13.495 10.215)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2DjJom" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.892 25.307)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iIBtCdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.892 26.602)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iIb23Ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.892 27.852)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iPFNYfS" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.892 29.203)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><filter id="ifwPSKe" width="20.537" height="10.328" x="5.481" y="4.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1815" result="effect2_innerShadow_4002_1815"/></filter><filter id="iY3DwCK" width="8" height="6.44" x="12" y="15.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/></filter><filter id="icmEtCb" width="3.44" height="3.34" x="9.36" y="8.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.643137 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/></filter><filter id="isVifMe" width="2.74" height="2.74" x="9.66" y="9.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".125"/></filter><filter id="iKAvDLT" width="2.827" height="2.827" x="19.407" y="9.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".125"/></filter><filter id="iWHs2Bb" width="8.45" height="4.612" x="11.73" y="25.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".125"/></filter><filter id="itjIUgb" width="8.05" height="4.28" x="11.88" y="25.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/></filter><filter id="iUcuH8c" width="10.66" height="10.004" x="10.92" y="7.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.666667 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/></filter><filter id="iJ8zvme" width="3.871" height="4.695" x="13.872" y="9.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".5"/></filter><filter id="iTkHoQN" width="2.271" height="3.095" x="14.865" y="9.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".1"/></filter><filter id="ilBGOeb" width="3.833" height="1.572" x="14.023" y="13.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".05"/></filter><filter id="ivkl3xc" width="7.625" height="9.853" x="21.853" y="10.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1815" result="effect2_innerShadow_4002_1815"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1815" result="effect3_innerShadow_4002_1815"/></filter><filter id="i6uVVKe" width=".795" height=".703" x="17.47" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".05"/></filter><filter id="i0tlp8s" width=".898" height=".921" x="18.324" y="9.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".1"/></filter><filter id="icxD0oe" width=".995" height="1.05" x="13.816" y="9.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".1"/></filter><filter id="iPtE00a" width=".923" height=".712" x="13.049" y="9.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".05"/></filter><filter id="itzEirc" width="4.468" height="5.556" x="23.454" y="24.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/></filter><filter id="iFrW6Mb" width="2.097" height=".3" x="23.825" y="25.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".05"/></filter><filter id="iuAwe1c" width="2.097" height=".3" x="23.747" y="27.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".05"/></filter><filter id="inttRqc" width="2.097" height=".3" x="23.825" y="28.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".05"/></filter><filter id="ipcBT4b" width="2.573" height="1.468" x="12.133" y="7.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0784314 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/></filter><filter id="iMnuNWc" width="2.573" height="1.468" x="17.293" y="7.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0784314 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1815"/></filter><filter id="igIPPxP" width="2.123" height=".868" x="17.56" y="7.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".075"/></filter><filter id="isfTcGe" width="2.123" height=".868" x="12.3" y="7.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1815" stdDeviation=".075"/></filter><linearGradient id="iIV9Gce" x1="15.92" x2="15.92" y1="4.032" y2="4.086" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iXfi1Wj" x1="16" x2="16" y1="4.832" y2="14.863" gradientUnits="userSpaceOnUse"><stop class="oo41sab8r"/><stop offset="1" class="agm2n63aw"/></linearGradient><linearGradient id="iGvpcdJ" x1="8.94" x2="5.35" y1="28.457" y2="28.457" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iupIQDN" x1="26.503" x2="22.96" y1="22.887" y2="29.193" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iliMnLb" x1="20" x2="19.066" y1="18.519" y2="18.519" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="img9TcU" x1="12" x2="12.334" y1="18.519" y2="18.519" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iC6blsd" x1="21.926" x2="20.82" y1="9.782" y2="12.283" gradientUnits="userSpaceOnUse"><stop class="vgzo13b2o"/><stop offset="1" class="ccj7rwekm"/></linearGradient><linearGradient id="ip6g0Le" x1="17.162" x2="15.95" y1="29.145" y2="22.02" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="iNl8X9d" x1="23.014" x2="22.787" y1="29.676" y2="29.676" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="itjQXNJ" x1="8.94" x2="9.064" y1="29.676" y2="29.676" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iWF1LMb" x1="13.787" x2="20.318" y1="28.363" y2="28.363" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="ilIq4Dd" x1="16.835" x2="16" y1="11.623" y2="11.66" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iQ5pRMi" x1="16" x2="16" y1="12.681" y2="12.249" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="itVK0te" x1="16" x2="16" y1="10.048" y2="10.675" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="idqkpGb" x1="14.658" x2="15.011" y1="14.243" y2="13.337" gradientUnits="userSpaceOnUse"><stop class="okk0ysbjc"/><stop offset="1" class="qtrrqsbgu"/></linearGradient><linearGradient id="iLtLKCd" x1="25.61" x2="25.61" y1="21.613" y2="24.793" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="i2QYVjb" x1="25.638" x2="25.638" y1="22.316" y2="21.723" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="ifK0wfD" x1="19.003" x2="18.685" y1="10.047" y2="10.243" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZtU3Gb" x1="14.541" x2="14.223" y1="10.047" y2="10.243" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ii2yZuc" x1="27.483" x2="23.454" y1="28.065" y2="28.065" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iw44eFd" x1="23.975" x2="25.684" y1="26.059" y2="26.059" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="itr8zVz" x1="23.896" x2="25.606" y1="27.378" y2="27.378" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iCdVKhc" x1="23.975" x2="25.684" y1="28.668" y2="28.668" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-farmer-light" /></template>
<style>
.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.agm2n63aw {
  stop-color: var(--svg-color--7a564f, #7A564F);
}

.asnyj72hm {
  stop-color: var(--svg-color--cd9899, #CD9899);
  stop-opacity: 0;
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.aykd0o_jp {
  d: path("M11.564 4.832c-.85.031-2.678.229-4.102 1.336c-1.238.962-1.477 2.117-1.477 3.086v.476c-.093 1.782 1.446 4.93 6.883 4.93h6.264c5.437 0 6.976-3.148 6.883-4.93v-.476c0-.969-.24-2.124-1.477-3.086c-1.423-1.107-3.252-1.305-4.101-1.336z");
}

.az3jcdmty {
  stop-color: var(--svg-color--906549, #906549);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b9-vno8aa {
  stop-color: var(--svg-color--f5bda7, #F5BDA7);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bo0hllbsr {
  d: path("M26.113 21.793h-1v3h1z");
}

.c30axybib {
  d: path("M22.96 18.063c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.c4o9i3oxt {
  d: path("M23.455 25.328c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.407-.657");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.ccj7rwekm {
  stop-color: var(--svg-color--e9b69f, #E9B69F);
}

.cfx5jhbrb {
  fill: var(--svg-color--000, #000);
  d: path("M17.697 10.414c0-.288.23-.519.519-.519a.516.516 0 0 1 .46.758h-.917a.47.47 0 0 1-.062-.24");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d45qhhb2k {
  stop-color: var(--svg-color--fdd3b9, #FDD3B9);
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.dfix_n5sh {
  stop-color: var(--svg-color--e8bcac, #E8BCAC);
  stop-opacity: 0;
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e8p-d1bsh {
  d: path("M19.42 25.833h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.ebnsn321w {
  stop-color: var(--svg-color--c68976, #C68976);
}

.en-2vgkms {
  stop-color: var(--svg-color--d09480, #D09480);
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.ew2j-0-9a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.897 27.3h1.796");
}

.f0jvz71gp {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.484 13.309c-.199-.106-.392.12-.276.3v.001a2.07 2.07 0 0 0 1.732.943a2.07 2.07 0 0 0 1.732-.943a.2.2 0 0 0-.024-.256a.21.21 0 0 0-.25-.046h-.002a3.1 3.1 0 0 1-1.456.355a3.1 3.1 0 0 1-1.456-.354Z");
}

.f4dh4oqdr {
  stop-color: var(--svg-color--efbba2, #EFBBA2);
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.flqkiabjb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.975 25.98h1.796");
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.fuhh3957a {
  stop-color: var(--svg-color--0d030b, #0D030B);
}

.g_jsgepxt {
  fill: var(--svg-color--000, #000);
  d: path("M14.303 10.414a.516.516 0 0 0-.519-.519a.516.516 0 0 0-.461.758h.918a.5.5 0 0 0 .062-.24");
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.gczjqeobw {
  stop-color: var(--svg-color--f5bda7, #F5BDA7);
  stop-opacity: 0;
}

.gir6ssbjp {
  stop-color: var(--svg-color--3b3538, #3B3538);
  stop-opacity: 0;
}

.guri77_rx {
  stop-color: var(--svg-color--e4b39c, #E4B39C);
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.i6uu1db5d {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.5 8.265s.6-.581 1.723-.448");
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.j5uok4b4y {
  d: path("M11.03 11.733a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.jgnhnrbnn {
  fill: var(--svg-color--cd9684, #CD9684);
  d: path("M11.03 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.jll7tfk4f {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.483 8.265s-.6-.581-1.723-.448");
}

.jvouqxrlb {
  stop-color: var(--svg-color--e4b39c, #E4B39C);
  stop-opacity: 0;
}

.k2g9ghb8b {
  d: path("M13.784 9.508a.906.906 0 0 0-.873 1.145h1.75a1 1 0 0 0 .033-.24a.91.91 0 0 0-.91-.905");
}

.k6k2nrb_g {
  fill: var(--svg-color--2c1c28, #2C1C28);
  fill-rule: evenodd;
  d: path("M12.85 8.69a.425.425 0 0 1-.587-.614l.296.306l-.296-.306l.001-.001l.002-.002l.004-.003l.01-.01a1 1 0 0 1 .144-.114a2.3 2.3 0 0 1 .403-.227a2.85 2.85 0 0 1 1.505-.207a.425.425 0 0 1-.1.844a2 2 0 0 0-1.06.14a1.5 1.5 0 0 0-.312.187z");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.l_7340byb {
  d: path("M20.82 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.l212nr2yp {
  stop-color: var(--svg-color--bb9282, #BB9282);
}

.l4pn8lb1x {
  d: path("M15.93 15.523c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.lfkx8fbxd {
  d: path("M24.877 20.012H26.4v1.734a.25.25 0 0 1-.25.25h-1.023a.25.25 0 0 1-.25-.25z");
}

.lg02bl6eh {
  d: path("M14.611 10.307c0-.292-.238-.487-.302-.546l-.292.283l.18.366z");
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmnxagbed {
  stop-color: var(--svg-color--89829d, #89829D);
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lwwg_6bee {
  d: path("M20.82 11.776a1.163 1.163 0 1 0 0-2.327a1.163 1.163 0 0 0 0 2.327");
}

.lxwdhqbih {
  stop-color: var(--svg-color--d59d92, #D59D92);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnus8s-ig {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.62 10.333l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mwg3cubiz {
  d: path("M12.964 21.496L16 19.373l2.987 2.084c.421.324 1.013.465 1.013-.355v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.691c0 .954.594.823.964.563");
}

.mzw4fybdm {
  fill: var(--svg-color--c0b8c5, #C0B8C5);
  d: path("M22.755 11.066a.6.6 0 0 0-.602.602v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.757 0v-4.45a.6.6 0 0 0-.602-.602");
}

.n2kxvdreg {
  d: path("m16.85 19.713l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nm8m6ccmy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.975 28.59h1.796");
}

.nz0052iet {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.15 9.7c.064.086-.071.191-.224.306s-.267.195-.332.109c-.064-.086.008-.25.16-.364c.154-.114.33-.137.395-.051");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o4vr40baf {
  d: path("m10.1 5.572l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeyonmbaf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.426 9.233c.663 0 1.222.457 1.375 1.074a.278.278 0 0 1-.272.346h-2.264a.234.234 0 0 1-.23-.276c.127-.65.7-1.144 1.391-1.144");
}

.okk0ysbjc {
  stop-color: var(--svg-color--e1ada2, #E1ADA2);
}

.oo41sab8r {
  stop-color: var(--svg-color--693f3f, #693F3F);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppasf06ij {
  stop-color: var(--svg-color--ae8586, #AE8586);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qbgz35bzv {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.93 15.523c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.qf5kn-bed {
  stop-color: var(--svg-color--3b3538, #3B3538);
}

.qqarjpbxn {
  cx: 13.511px;
  cy: 9.895px;
  rx: 0.395px;
  ry: 0.2px;
}

.qtrrqsbgu {
  stop-color: var(--svg-color--e1ada2, #E1ADA2);
  stop-opacity: 0;
}

.quk3dgi1t {
  stop-color: var(--svg-color--cd9282, #CD9282);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r5erk965r {
  stop-color: var(--svg-color--e8bcac, #E8BCAC);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rb2mtukpy {
  stop-color: var(--svg-color--10080c, #10080C);
}

.re4_t4kfi {
  d: path("M19.022 10.295a.85.85 0 0 0-.234-.47l-.264.29l.119.231z");
}

.rfy0m2bqt {
  d: path("M10.508 7.743c.418-.64 1.996-.738 2.566-.738l-1.726 3.18h-.53c-.177 0-.35-.076-.433-.231c-.285-.528-.438-1.466.123-2.21");
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.s04hhyilv {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.427 10.558l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.s7aakmgnr {
  stop-color: var(--svg-color--b58885, #B58885);
}

.s9qqxfquy {
  d: path("M15.93 18.693c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.sddxoj3pl {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.94 13.713c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.szj0on_us {
  d: path("M26.772 23.143c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tsc202y0r {
  stop-color: var(--svg-color--3f3532, #3F3532);
}

.u2c1s-bxw {
  d: path("M21.92 5.932h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.u4h3exu9c {
  stop-color: var(--svg-color--2a2627, #2A2627);
}

.udh7vik5k {
  fill: var(--svg-color--2c1c28, #2C1C28);
  fill-rule: evenodd;
  d: path("M19.15 8.69a.425.425 0 0 0 .587-.614c-.493.51 0 0 0 0l-.001-.001l-.002-.002l-.004-.003l-.01-.01a1 1 0 0 0-.144-.114a2.3 2.3 0 0 0-.403-.227a2.85 2.85 0 0 0-1.505-.207a.425.425 0 0 0 .1.844c.477-.057.831.039 1.06.14a1.5 1.5 0 0 1 .312.187z");
}

.uspdh30af {
  stop-color: var(--svg-color--e4af95, #E4AF95);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v0fgrdmwe {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.42 25.833h-6.94a.49.49 0 0 0-.5.491v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.v4i99-8yk {
  d: path("M19.082 7.005h-6.168c-1.127 0-2.086 1.008-1.987 2.125l.184 4.942c.168 1.71 1.532 2.937 3.193 2.937h3.394c1.661 0 3.026-1.226 3.194-2.937l.187-5.04c.04-1.078-.91-2.027-1.997-2.027");
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6gtvtu6m {
  d: path("M18.15 9.7c.064.086-.071.191-.224.306s-.267.195-.332.109c-.064-.086.008-.25.16-.364c.154-.114.33-.137.395-.051");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vgzo13b2o {
  stop-color: var(--svg-color--edc0ab, #EDC0AB);
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vsa1kss6t {
  d: path("M8.94 30.003v-11.97h-.006a10.95 10.95 0 0 0-3.994 8.47v3.5z");
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.vv2pjr99s {
  d: path("m15.62 10.333l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.vvdbjrbwx {
  stop-color: var(--svg-color--d09480, #D09480);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wpfophm-a {
  d: path("M21.492 7.743c-.418-.64-1.996-.738-2.566-.738l1.726 3.18h.53c.177 0 .35-.076.433-.231c.286-.528.438-1.466-.123-2.21");
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xgh9w-b7r {
  d: path("M18.216 9.508a.905.905 0 0 1 .872 1.145H17.34a.91.91 0 0 1 .877-1.144");
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.y9bk_9fsc {
  stop-color: var(--svg-color--85808c, #85808C);
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.yea69orbb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.574 9.233c-.662 0-1.222.457-1.375 1.074a.278.278 0 0 0 .272.346h2.264c.144 0 .26-.132.23-.276a1.42 1.42 0 0 0-1.39-1.144");
}

.yhh4ofd4k {
  d: path("M22.96 30.003v-11.97h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yvjrxccgr {
  d: path("M11.03 12.283a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.z48shob3w {
  stop-color: var(--svg-color--906549, #906549);
}

.zg5_mkbdg {
  cx: 13.511px;
  cy: 9.895px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zmlcnx4wm {
  stop-color: var(--svg-color--d49f93, #D49F93);
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
