<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qui6h_biv"/><path fill="url(#iQLOele)" class="hkkwgkxub"/><path fill="url(#iQ27Foe)" class="hkkwgkxub"/><path fill="url(#ibwQ2Pc)" class="x2vx4ybjt"/><path fill="url(#iHfFkYP)" class="x2vx4ybjt"/><path fill="url(#iImggpd)" class="x2vx4ybjt"/><path fill="url(#i5Z55lc)" class="x2vx4ybjt"/><path fill="url(#i9gM5Vd)" class="x2vx4ybjt"/><path fill="url(#i0SvKTt)" class="x2vx4ybjt"/><path fill="url(#ik6Yoqe)" class="n3lq6m3qk"/><path fill="url(#ipgDwib)" class="n3lq6m3qk"/><path fill="url(#iOpIlMe)" class="ldufidzyv"/><path fill="url(#it9jIdd)" class="ldufidzyv"/><path fill="url(#iAorkie)" class="c3b7deb_q"/><g filter="url(#iiSDx9c)"><path fill="url(#i3lRVhd)" class="mks5crg_d"/></g><path fill="url(#iN3YMje)" class="mks5crg_d"/><path fill="url(#iwaszcb)" class="mks5crg_d"/><path fill="url(#iMXobke)" class="mks5crg_d"/><path fill="url(#i9bO6lb)" class="mks5crg_d"/><path fill="url(#iZSHJPc)" class="mks5crg_d"/><g filter="url(#ib1Il8b)"><path class="jys_tgd7b"/></g><g filter="url(#ic5Rdeb)"><path fill="url(#isiovtb)" class="jdg2u3byg"/><path fill="url(#isLQIZc)" class="jdg2u3byg"/><path fill="url(#ix46NZc)" class="jdg2u3byg"/><path fill="url(#izyfsoc)" class="jdg2u3byg"/></g><g filter="url(#iMpqUKd)"><path stroke="url(#ifHxNLb)" class="gse9acb7f"/></g><path fill="url(#i8RG6je)" class="p0ke-0p9y"/><g filter="url(#iiaeGSb)"><path fill="url(#inwZ20b)" class="xn50snbbk"/><path fill="url(#iFQjEAb)" class="xn50snbbk"/><path fill="url(#iBhanna)" class="xn50snbbk"/><path fill="url(#ixuGG5d)" class="xn50snbbk"/><path fill="url(#iNVredc)" class="xn50snbbk"/></g><g filter="url(#iuP6dUb)"><path class="x8x3dbmbt"/></g><g filter="url(#iO4rWac)"><path class="b1w7q0b_w"/></g><g filter="url(#i5l0F3H)"><path fill="url(#i8vymSc)" class="ez95-cc-o"/><path fill="url(#iGRn4Wx)" class="ez95-cc-o"/></g><g filter="url(#iy9OfZd)"><path fill="url(#i3v8jqc)" class="v4hvvpbgn"/><path fill="url(#iuHcf2b)" class="v4hvvpbgn"/><path fill="url(#iSPKw0b)" class="v4hvvpbgn"/><path fill="url(#i0iBiue)" class="v4hvvpbgn"/><path fill="url(#icPXK3d)" class="v4hvvpbgn"/></g><path class="rdj8d6o7x"/><path fill="url(#iz1Uq2S)" class="m_89wckow"/><path class="c1aggobjx"/><g filter="url(#iC2Hx2d)"><path class="rt48t0bgn"/><path fill="url(#iUZ8AKX)" class="t_epc_b-d"/></g><g filter="url(#i6yUDLR)"><path fill="url(#iwdPafL)" class="ikav40p4r"/></g><path class="fxv7ykbcc"/><path fill="url(#i2x0ipG)" class="cjwb4bckb"/><path class="cfyazibxw"/><g filter="url(#i8UYtUc)"><path fill="url(#iydW2Tb)" class="gh2kxqbnj"/></g><g filter="url(#iNQjO0c)"><ellipse transform="rotate(-27.914 13.779 9.642)" class="sexqttmhr"/><ellipse fill="url(#i97Zjld)" transform="rotate(-27.914 13.779 9.642)" class="iisp_bcpr"/></g><path fill="url(#iPpL2cd)" class="w1h6a0b-x"/><path fill="url(#iMwizBe)" class="w1h6a0b-x"/><path fill="url(#ifYD4eZ)" class="w1h6a0b-x"/><path fill="url(#itODmke)" class="rre24kbuj"/><path fill="url(#iOATIsc)" class="rre24kbuj"/><g filter="url(#ibPt9Yd)"><path class="d25cpubgq"/></g><g filter="url(#ip0xFXC)"><path class="p5u44weng"/></g><g filter="url(#iPljEwb)"><path class="x734fm5pg"/></g><g filter="url(#iDhhypo)"><path class="x4h0c4bpz"/></g><path fill="url(#iIRu25b)" class="fv-3ufbos"/><path fill="url(#iATgibd)" class="fv-3ufbos"/><path fill="url(#i3jXNrY)" class="zvr5tcchi"/><path fill="url(#i8xARzc)" class="dpg_1ulbz"/><path fill="url(#i0b56Ad)" class="dpg_1ulbz"/><path fill="url(#iOLfYNb)" class="dpg_1ulbz"/><path fill="url(#iOnfpDc)" class="qcavuxunw"/><path fill="url(#iC56D0c)" class="qcavuxunw"/><g filter="url(#iMOaSTb)"><path stroke="url(#ijXDZId)" class="rez4e-blr"/></g><path fill="url(#i1ea2Sb)" class="rm1znbbdc"/><path fill="url(#iExJcmb)" class="rm1znbbdc"/><path fill="url(#iPAVYwd)" class="rm1znbbdc"/><path fill="url(#inSBY0b)" class="rm1znbbdc"/><path fill="url(#i64GGbl)" class="n4l0poy4k"/><path fill="url(#iBNL5zb)" class="n4l0poy4k"/><path fill="url(#iqVyr9d)" class="n4l0poy4k"/><path fill="url(#iRBAEse)" class="kqeo-nh-c"/><path fill="url(#iM1r1Cc)" class="kqeo-nh-c"/><g filter="url(#i3dw7pc)"><path fill="url(#izFnkad)" class="w2h_g0b9y"/><path fill="url(#izFnkad)" class="t7jecreih"/><path fill="url(#izFnkad)" class="hs3j5u8xb"/></g><defs><radialGradient id="iQLOele" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.592 23)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iQ27Foe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.998 21.344)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="ibwQ2Pc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.298 21.234)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iHfFkYP" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.29 16.781)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iImggpd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.873 15.438)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="i5Z55lc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.623 15.203)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="i9gM5Vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.29 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="i0SvKTt" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.85937 -5.04205 0 16.29 15.203)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="ik6Yoqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8757 3.74264 -4.44596 -1.04025 21.814 11.602)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="ipgDwib" cx="0" cy="0" r="1" gradientTransform="matrix(.29446 .40381 -.34305 .25015 21.065 11.871)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iOpIlMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3382 3.93857 -1.79026 .60827 10.672 11.72)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="it9jIdd" cx="0" cy="0" r="1" gradientTransform="matrix(.3197 1.00114 -.87821 .28044 11.336 11.713)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iAorkie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01563 -1 2.11378 -2.1468 17.686 18.266)" gradientUnits="userSpaceOnUse"><stop class="luy9ddyqx"/><stop offset="1" class="ag8mkc7iw"/></radialGradient><radialGradient id="i3lRVhd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24967 0 0 -9.28661 19.062 10.658)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iN3YMje" cx="0" cy="0" r="1" gradientTransform="rotate(94.715 4.648 11.789)scale(9.12463 10.4581)" gradientUnits="userSpaceOnUse"><stop offset=".623" class="scr4aerft"/><stop offset=".979" class="nq5-af5uw"/></radialGradient><radialGradient id="iwaszcb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40419 6.1274 -2.25268 -.1486 21.42 10.426)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iMXobke" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41976 1.70932 0 14.143 9.472)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="i9bO6lb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.54165 1.99957 0 18.742 9.059)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iZSHJPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.48238 -6.34654 0 15.625 4.46)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="eeltujtez"/><stop offset="1" class="t621q03gd"/></radialGradient><radialGradient id="ifHxNLb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.47 -5.916)scale(.71306 2.07501)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="i8RG6je" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72374 2.91181 0 16.243 14.212)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iFQjEAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.74284 10.1752 0 10.992 9.07)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iBhanna" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.64781 6.46321 0 21.124 9.07)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="ixuGG5d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.12366 -1.44683 .77053 -2.19612 20.366 2.766)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iNVredc" cx="0" cy="0" r="1" gradientTransform="matrix(.9089 1.48115 -3.42965 2.10457 15.334 1.167)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="i8vymSc" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 8.02 2.75)scale(4.06403 1.13112)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iGRn4Wx" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.103 -6.09)scale(6.05177 6.70474)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="i3v8jqc" cx="0" cy="0" r="1" gradientTransform="matrix(3.39992 .80417 -.44975 1.90147 19.878 3.78)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iuHcf2b" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.117 -1.959)scale(4.29968 2.3979)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iSPKw0b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31282 -2.21148 1.58399 -.94032 20.77 8.103)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="i0iBiue" cx="0" cy="0" r="1" gradientTransform="matrix(-4.81845 1.156 -1.24969 -5.20893 21.057 3.664)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="icPXK3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.11782 .38533 -1.76169 -.53867 19.71 3.538)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iz1Uq2S" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81444 -1.29547 0 18.434 9.738)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iUZ8AKX" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.507 .453)scale(.3793 .5222)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2x0ipG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81449 -1.29553 0 14.051 9.737)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i97Zjld" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.783 -1.796)scale(.49546 .59557)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMwizBe" cx="0" cy="0" r="1" gradientTransform="matrix(.63117 2.25264 -2.14919 .60219 20.88 9.752)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ifYD4eZ" cx="0" cy="0" r="1" gradientTransform="matrix(.79106 -1.08562 .90996 .66307 21.243 10.299)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iOATIsc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.408 9.457)scale(2.12551 2.08958)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iATgibd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.865 11.553)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="i3jXNrY" cx="0" cy="0" r="1" gradientTransform="rotate(-102.428 11.948 -4.65)scale(3.92058 20.9164)" gradientUnits="userSpaceOnUse"><stop class="pok8-dbcp"/><stop offset="1" class="x49zttk2i"/></radialGradient><radialGradient id="i0b56Ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.03 2.281)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iOLfYNb" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.06 2.906)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><radialGradient id="iOnfpDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.123 11.925)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="iC56D0c" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.785 12.316)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iExJcmb" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.262 8.494)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iPAVYwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.623 16.781)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="inSBY0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.623 12.992)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="i64GGbl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.295 29.88)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iBNL5zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.06 29.88)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iRBAEse" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.402 29.88)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iM1r1Cc" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.35 23.042)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><filter id="iiSDx9c" width="10.763" height="12.593" x="11.159" y="4.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1579"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1579" result="effect2_innerShadow_4002_1579"/></filter><filter id="ib1Il8b" width="3.885" height="4.911" x="14.092" y="8.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".5"/></filter><filter id="ic5Rdeb" width="2.085" height="3.111" x="15.2" y="9.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".05"/></filter><filter id="iMpqUKd" width="3.732" height="1.577" x="14.377" y="12.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".05"/></filter><filter id="iiaeGSb" width="12.926" height="8.217" x="9.78" y="1.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1579"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1579" result="effect2_innerShadow_4002_1579"/></filter><filter id="iuP6dUb" width="2.347" height="1.194" x="17.839" y="6.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1579"/></filter><filter id="iO4rWac" width="2.348" height="1.179" x="12.56" y="6.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1579"/></filter><filter id="i5l0F3H" width="6.61" height="6.015" x="10.138" y="2.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".125"/></filter><filter id="iy9OfZd" width="6.387" height="5.759" x="16.083" y="2.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".125"/></filter><filter id="iC2Hx2d" width=".788" height=".698" x="17.697" y="9.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".05"/></filter><filter id="i6yUDLR" width=".892" height=".914" x="18.541" y="9.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".1"/></filter><filter id="i8UYtUc" width=".987" height="1.041" x="14.08" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".1"/></filter><filter id="iNQjO0c" width=".915" height=".706" x="13.321" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".05"/></filter><filter id="ibPt9Yd" width="1.332" height="2.387" x="10.186" y="9.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".125"/></filter><filter id="ip0xFXC" width="1.45" height="2.411" x="20.976" y="9.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".125"/></filter><filter id="iPljEwb" width="2.412" height="1.162" x="12.48" y="7.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".125"/></filter><filter id="iDhhypo" width="2.412" height="1.162" x="17.783" y="7.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".125"/></filter><filter id="iMOaSTb" width=".65" height="8.268" x="24.401" y="3.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".125"/></filter><filter id="i3dw7pc" width="8.964" height="6.734" x="11.808" y="23.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1579" stdDeviation=".075"/></filter><linearGradient id="isiovtb" x1="16.243" x2="17.101" y1="11.489" y2="11.489" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="isLQIZc" x1="15.166" x2="16.244" y1="11.333" y2="11.393" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="ix46NZc" x1="16.243" x2="16.243" y1="11.889" y2="12.745" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="izyfsoc" x1="16.243" x2="16.243" y1="9.633" y2="10.054" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="inwZ20b" x1="21.629" x2="11.463" y1="4.971" y2="4.971" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iwdPafL" x1="19.214" x2="18.9" y1="9.791" y2="9.985" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iydW2Tb" x1="14.797" x2="14.483" y1="9.791" y2="9.984" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPpL2cd" x1="22.706" x2="21.495" y1="9.819" y2="12.004" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="itODmke" x1="10.369" x2="11.833" y1="10.526" y2="10.398" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iIRu25b" x1="23.98" x2="25.166" y1="8.827" y2="8.827" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="i8xARzc" x1="18.061" x2="16.779" y1="3.844" y2="-.531" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient><linearGradient id="ijXDZId" x1="25.226" x2="25.226" y1="3.594" y2="11.362" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="i1ea2Sb" x1="25.774" x2="23.455" y1="14.692" y2="14.692" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iqVyr9d" x1="9.205" x2="8.779" y1="27.949" y2="27.949" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="izFnkad" x1="16.29" x2="16.29" y1="29.75" y2="23.316" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:student" /></template>
<style>
.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.ag8mkc7iw {
  stop-color: var(--svg-color--cf7b39, #CF7B39);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.b1w7q0b_w {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.818 7.556a2.8 2.8 0 0 1 1.746-.36a.278.278 0 1 1-.068.552a2.23 2.23 0 0 0-1.392.286a1 1 0 0 0-.092.06l-.003.002a.279.279 0 0 1-.341-.44z");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c1aggobjx {
  fill: var(--svg-color--000, #000);
  d: path("M17.923 10.154a.51.51 0 0 1 .513-.512a.51.51 0 0 1 .455.748h-.907a.46.46 0 0 1-.061-.236");
}

.c3b7deb_q {
  d: path("M15.996 18.75c.063.044.17.08.28.085a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.764 1.89 1.78 2.587");
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.cfyazibxw {
  fill: var(--svg-color--000, #000);
  d: path("M14.562 10.154a.51.51 0 0 0-.513-.512a.51.51 0 0 0-.456.748h.908a.5.5 0 0 0 .06-.236");
}

.cjwb4bckb {
  d: path("M14.05 9.258a.896.896 0 0 0-.864 1.132h1.73a1 1 0 0 0 .033-.236a.9.9 0 0 0-.9-.896");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d25cpubgq {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M11.184 9.455a.96.96 0 0 0 .084 1.886a78 78 0 0 1-.084-1.886");
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dpg_1ulbz {
  d: path("M24.233 3.49H8.263c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eeltujtez {
  stop-color: var(--svg-color--e28222, #E28222);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.ez95-cc-o {
  d: path("m16.476 5.018l-.066-.137a.67.67 0 0 0-.618-.42h-1.278c-1.854 0-3.355 1.519-3.355 3.393v.276c-.342-.26-.771-.807-.771-1.694c0-1.077.785-1.62 1.285-1.968c.142-.098.26-.18.332-.254l.1-.105c.351-.373.977-1.036 2.069-1.326a5.5 5.5 0 0 1 1.517-.165c.473.011.806.42.806.892v1.495z");
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.ft5dv1b6b {
  fill: none;
}

.fv-3ufbos {
  d: path("M25.023 11.553V2.69h-.8v8.863z");
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.fxv7ykbcc {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.842 8.986c-.656 0-1.21.452-1.36 1.063a.275.275 0 0 0 .268.342h2.24c.143 0 .256-.13.228-.273a1.41 1.41 0 0 0-1.376-1.132");
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gh2kxqbnj {
  d: path("M14.867 10.048c0-.289-.235-.482-.299-.54l-.288.28l.177.362z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gse9acb7f {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.886 13.17c.392.204.859.321 1.357.321c.503 0 .965-.117 1.356-.32l.001-.001a.23.23 0 0 1 .271.044a.215.215 0 0 1 .024.274m-3.009-.318l2.947.276m-2.947-.276a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.271m.295-.318l-.233.276m3.242.042l-.062-.042m.062.042l-.062-.042m.062.042c-.35.53-.959.883-1.652.883a1.98 1.98 0 0 1-1.652-.883m3.242-.042c-.337.51-.923.85-1.59.85a1.9 1.9 0 0 1-1.59-.85m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.hkkwgkxub {
  d: path("M16.295 15.38c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hs3j5u8xb {
  d: path("M19.93 23.657c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.iisp_bcpr {
  cx: 13.779px;
  cy: 9.642px;
  rx: 0.391px;
  ry: 0.198px;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ikav40p4r {
  d: path("M19.233 10.036a.84.84 0 0 0-.232-.464l-.26.286l.117.228z");
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.jdg2u3byg {
  d: path("m15.859 9.94l-.534 1.845c-.109.38.153.76.523.76h.79c.37 0 .63-.386.522-.76l-.534-1.845c-.114-.409-.648-.409-.767 0");
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jys_tgd7b {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.755 10.137l-.638 1.845c-.109.38.152.76.523.76h.79c.37 0 .63-.386.522-.76l-.534-1.845c-.114-.41-.544-.41-.663 0");
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kqeo-nh-c {
  d: path("M23.52 29.88V18.095a10.97 10.97 0 0 1 3.765 8.287v3.5z");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.ldufidzyv {
  d: path("M11.36 11.913a1.65 1.65 0 0 1-.907-.31v.935a2.18 2.18 0 0 0 1.346 2.026a4.1 4.1 0 0 1-.347-1.184z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.luy9ddyqx {
  stop-color: var(--svg-color--d89d21, #D89D21);
}

.m_89wckow {
  d: path("M18.436 9.259a.896.896 0 0 1 .863 1.132h-1.73a.9.9 0 0 1 .867-1.132");
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mks5crg_d {
  d: path("M11.398 13.434a3.93 3.93 0 0 0 3.902 3.42h1.894a3.93 3.93 0 0 0 3.902-3.42c.119-1.891.238-3.775.326-5.666a1.455 1.455 0 0 0-1.385-1.438H18.63a2.43 2.43 0 0 1-2.22-1.45a.67.67 0 0 0-.618-.42h-1.278c-1.854 0-3.355 1.519-3.355 3.393c0 1.869.116 3.707.239 5.58");
}

.n3lq6m3qk {
  d: path("M21.125 11.912c.336-.011.652-.125.908-.31v.935a2.18 2.18 0 0 1-1.346 2.026q.257-.547.347-1.184z");
}

.n4l0poy4k {
  d: path("M9.06 29.88V18.095a10.97 10.97 0 0 0-3.765 8.287v3.5z");
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nq5-af5uw {
  stop-color: var(--svg-color--c56b42, #C56B42);
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p0ke-0p9y {
  d: path("M16.243 13.566c-.51 0-.989-.12-1.391-.33c-.138-.07-.286.085-.2.21c.337.51.923.85 1.59.85a1.9 1.9 0 0 0 1.59-.85c.087-.13-.06-.28-.198-.21a3 3 0 0 1-1.391.33");
}

.p5u44weng {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M21.226 11.35q.059-.956.11-1.911a.96.96 0 0 1-.11 1.91");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pok8-dbcp {
  stop-color: var(--svg-color--534d5b, #534D5B);
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qcavuxunw {
  d: path("M24.223 11.53a.837.837 0 1 0 .8 0z");
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qui6h_biv {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.295 15.38c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rdj8d6o7x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.643 8.986c.656 0 1.21.452 1.36 1.063a.275.275 0 0 1-.268.342h-2.24a.23.23 0 0 1-.228-.273a1.4 1.4 0 0 1 1.376-1.132");
}

.rez4e-blr {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.726 3.594v7.768");
}

.rm1znbbdc {
  d: path("m23.77 13.49l-.517 2.24a.45.45 0 0 0 .445.55h1.863a.45.45 0 0 0 .43-.557l-.542-2.239a.5.5 0 0 0-.485-.381h-.707a.5.5 0 0 0-.488.388");
}

.rre24kbuj {
  d: path("M11.168 8.792a1.616 1.616 0 0 0 .139 3.213a78 78 0 0 1-.14-3.214");
}

.rt48t0bgn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.37 9.448c.063.086-.07.19-.222.303c-.151.113-.264.193-.328.107c-.063-.085.008-.246.16-.359c.15-.113.325-.136.39-.05");
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.scr4aerft {
  stop-color: var(--svg-color--fba036, #FBA036);
  stop-opacity: 0;
}

.sexqttmhr {
  cx: 13.779px;
  cy: 9.642px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.391px;
  ry: 0.198px;
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t_epc_b-d {
  d: path("M18.37 9.448c.063.086-.07.19-.222.303c-.151.113-.264.193-.328.107c-.063-.085.008-.246.16-.359c.15-.113.325-.136.39-.05");
}

.t621q03gd {
  stop-color: var(--svg-color--e28222, #E28222);
  stop-opacity: 0;
}

.t7jecreih {
  d: path("M15.944 23.657c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v4hvvpbgn {
  d: path("m21.477 8.405l-.029-.634c-.01-.767-.644-1.4-1.411-1.432H18.63a2.43 2.43 0 0 1-2.133-1.264s-.06-.14-.122-.377c-.255-.97.672-1.713 1.657-1.522c.98.19 2.096.519 2.921 1.057c1.752 1.143 1.445 3.202.523 4.172");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.w1h6a0b-x {
  d: path("M21.186 12.004q.1-1.602.185-3.204a1.616 1.616 0 0 1-.185 3.204");
}

.w2h_g0b9y {
  d: path("M11.958 23.657c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x2vx4ybjt {
  d: path("M23.311 17.98a.24.24 0 0 0-.059-.29c-1.856-1.603-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.015 7.013-4.614");
}

.x49zttk2i {
  stop-color: var(--svg-color--2b2135, #2B2135);
}

.x4h0c4bpz {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.82 7.791c-.258-.185-.901-.51-1.662-.383");
}

.x734fm5pg {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.856 7.837c.258-.185.9-.511 1.661-.383");
}

.x8x3dbmbt {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.99 7.666a1.9 1.9 0 0 0-.69-.413c-.305-.097-.687-.122-1.217-.058a.278.278 0 1 0 .068.553c.483-.06.779-.028.982.036c.2.062.334.164.492.301a.278.278 0 1 0 .366-.42");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xn50snbbk {
  d: path("M21.118 3.987c.517.178.98.539 1.273 1.056c.469.824.4 1.81-.107 2.537a1.57 1.57 0 0 0-.271.877V9.65a1.75 1.75 0 0 0-.67-.269l.079-1.613a1.455 1.455 0 0 0-1.385-1.438H18.63a2.43 2.43 0 0 1-2.221-1.449a.67.67 0 0 0-.618-.42h-1.278c-1.854 0-3.355 1.519-3.355 3.393l.03 1.544a1.7 1.7 0 0 0-.723.265V8.457c0-.312-.096-.619-.271-.877a2.4 2.4 0 0 1-.144-2.456a2.35 2.35 0 0 1 1.304-1.132a2.7 2.7 0 0 0 1.39-1.114c.416-.663 1.146-.933 1.982-.933c.325 0 .634.07.921.189c.384.167.815.167 1.199 0c.282-.119.59-.189.916-.189c.846 0 1.587.286 1.997.965a2.53 2.53 0 0 0 1.358 1.077");
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

.zvr5tcchi {
  d: path("M10.057 5.133L11.31 3.14l9.75-.11l1.36 2.063c-4.664 1.61-10.274.773-12.364.039");
}

</style>
