<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bevfv5kqa"/><path fill="url(#il7lKLc)" class="f-zri6bjh"/><path fill="url(#iW3ezjv)" class="f-zri6bjh"/><path fill="url(#iCXSqte)" class="f__9j_9_e"/><path fill="url(#ieVwk2c)" class="f__9j_9_e"/><path fill="url(#il6f8id)" class="f__9j_9_e"/><path fill="url(#iTpnNxc)" class="f__9j_9_e"/><path fill="url(#issWafd)" class="f__9j_9_e"/><path fill="url(#ifLEGSd)" class="f__9j_9_e"/><g filter="url(#ikCMC7b)"><path class="jqtoh3u7m"/></g><path fill="url(#i8jYZdc)" class="py694yfhp"/><path fill="url(#isxOM5p)" class="lincvjbcr"/><path fill="url(#iyORuOS)" class="lincvjbcr"/><path fill="url(#iCz2QCb)" class="enkgnbc3v"/><path fill="url(#iQiEEbg)" class="enkgnbc3v"/><g filter="url(#iWbMg8d)"><path stroke="url(#ijC9E3c)" class="jp_cikcwt"/></g><path fill="url(#ikaneie)" class="nf5c-bcfg"/><path fill="url(#iOajgKb)" class="nf5c-bcfg"/><path fill="url(#ioc7Dkc)" class="nf5c-bcfg"/><path fill="url(#igjq4Bd)" class="nf5c-bcfg"/><path fill="url(#i9JrxNb)" class="nf5c-bcfg"/><path fill="url(#i0dWUje)" class="ecao01bgn"/><path fill="url(#iy20hXd)" class="ecao01bgn"/><path fill="url(#iaN6sOc)" class="ecao01bgn"/><path fill="url(#i7Knznd)" class="cb5n4zbnr"/><path fill="url(#iL1AGYc)" class="cb5n4zbnr"/><g filter="url(#iPNkBhc)"><path fill="url(#iTMEo7d)" class="xgi4edb4w"/><path fill="url(#iTMEo7d)" class="w9mft0urs"/><path fill="url(#iTMEo7d)" class="kna2v6epf"/></g><path fill="url(#idF5Esb)" class="bb4ekeb8f"/><path fill="url(#iHzFALe)" class="yv1lsr29z"/><g filter="url(#iqNXXSd)"><path fill="url(#iZvW1mY)" class="v-lgd2shh"/></g><path fill="url(#iVAkv8g)" class="v-lgd2shh"/><path fill="url(#i3nWNee)" class="v-lgd2shh"/><path fill="url(#iBhO8fe)" class="v-lgd2shh"/><path fill="url(#i6gj2TY)" class="v-lgd2shh"/><path fill="url(#il3gKae)" class="v-lgd2shh"/><path fill="url(#ihaBDXb)" class="v-lgd2shh"/><path fill="url(#ixfBInd)" class="v-lgd2shh"/><path fill="url(#i0pA9hd)" class="v-lgd2shh"/><path fill="url(#iPXb56d)" class="v-lgd2shh"/><g filter="url(#iOa6wfe)"><path class="m4nqgzb4s"/></g><g filter="url(#iFlaqeb)"><path class="vma-jccep"/><path fill="url(#ilvdK8d)" class="sijhs0p7u"/><path fill="url(#iBA91Oe)" class="sijhs0p7u"/><path fill="url(#iGH5Wdc)" class="sijhs0p7u"/><path fill="url(#iVW3ezc)" class="sijhs0p7u"/><path fill="url(#ijsk4Sc)" class="sijhs0p7u"/></g><g filter="url(#iNENIVc)"><path stroke="url(#ikcSV7c)" class="qexz1bccf"/></g><path fill="url(#ixKzAIb)" class="axzg-ebdr"/><g filter="url(#itFtHKc)"><path fill="url(#iJHKUid)" class="xud4sna1e"/><path fill="url(#iAFuVYb)" class="xud4sna1e"/><path fill="url(#izDpCGc)" class="xud4sna1e"/><path fill="url(#iPJ0Bgb)" class="xud4sna1e"/><path fill="url(#iXp4vLc)" class="xud4sna1e"/></g><g filter="url(#iasG0td)"><path class="y3tg7-iqo"/></g><g filter="url(#ibhyi3b)"><path class="kc50k7g2g"/></g><g filter="url(#iBYai7b)"><path class="cd8tkrb3l"/><path fill="url(#ifmGgAe)" class="y5tai6bvg"/><path fill="url(#if9DUle)" class="y5tai6bvg"/></g><g filter="url(#iSNRSxF)"><path class="wq1729b8j"/><path fill="url(#ijZOrKb)" class="x_834_31y"/></g><path class="t3ao3kwso"/><path fill="url(#iU7Y07c)" class="sdf_4ut8h"/><path class="uaqfy8bjj"/><g filter="url(#iUuSGdb)"><path class="ic7o6y_ui"/><path fill="url(#i9Js56I)" class="mvdx7rbmf"/></g><g filter="url(#iWVo8sd)"><path fill="url(#iDIaZmc)" class="wmsnfnb2d"/></g><path class="qio3z_1sa"/><path fill="url(#il13AOd)" class="jobrpk3-g"/><path class="vwr4k2bur"/><g filter="url(#iYq4IZb)"><path fill="url(#iuCGgxb)" class="n7_rqhqtz"/></g><g filter="url(#iYIFYOt)"><ellipse transform="rotate(-27.914 13.787 9.8)" class="ol6uh1m-f"/><ellipse fill="url(#ioFG9Vc)" transform="rotate(-27.914 13.787 9.8)" class="rcma9du_f"/></g><path fill="url(#iLoOh2b)" class="l119f_b3a"/><path fill="url(#isG3DAd)" class="l119f_b3a"/><path fill="url(#iROiPlc)" class="l119f_b3a"/><path fill="url(#iKRE72b)" class="l119f_b3a"/><path fill="url(#iZ7e5ic)" class="d7mr3f46j"/><path fill="url(#im0Tczd)" class="d7mr3f46j"/><g filter="url(#isH8mxd)"><path fill="url(#iUzVccd)" class="risafibjz"/></g><g filter="url(#iRkxJCc)"><path fill="url(#iiaFIGb)" class="t64f_zb4c"/></g><g filter="url(#iGJh7Wb)"><path class="web_sjb4c"/></g><g filter="url(#iOkGlhb)"><path class="tf-w6nr7g"/></g><g filter="url(#i22psse)"><path class="wfvemhb9j"/></g><g filter="url(#iK8Dfmd)"><path fill="url(#i8riDQc)" class="ufecrmb8z"/><path fill="url(#igWQ4Pe)" class="ufecrmb8z"/></g><path fill="url(#i9aYweb)" class="m3w3mu5nz"/><path fill="url(#iA8batd)" class="m3w3mu5nz"/><path fill="url(#iwLUd5s)" class="m3w3mu5nz"/><defs><radialGradient id="il7lKLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.592 23.114)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iW3ezjv" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.998 21.458)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iCXSqte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 15.8584 0 16.298 21.349)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="x3t2hmtbe"/><stop offset="1" class="x4e9_o_2d"/></radialGradient><radialGradient id="ieVwk2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.29 16.895)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="il6f8id" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.873 15.552)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iTpnNxc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.623 15.317)" gradientUnits="userSpaceOnUse"><stop offset=".939" class="xuw5xge2n"/><stop offset=".971" class="pwa-xfb8m"/></radialGradient><radialGradient id="issWafd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.29 23.614)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="ifLEGSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.85937 -5.04205 0 16.29 15.317)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i8jYZdc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.677 10.453 7.348)scale(2.69928 5.70569)" gradientUnits="userSpaceOnUse"><stop class="smyr16b9u"/><stop offset="1" class="l-xm7ybzq"/></radialGradient><radialGradient id="iyORuOS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.865 11.668)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="iCz2QCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.123 12.04)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="iQiEEbg" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.785 12.43)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="ioc7Dkc" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.257 8.55)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="igjq4Bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.623 16.895)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="yl8yg_b1a"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="i9JrxNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.623 13.106)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="i0dWUje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.295 29.995)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iy20hXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.06 29.995)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="i7Knznd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.402 29.995)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iL1AGYc" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.35 23.157)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="idF5Esb" cx="0" cy="0" r="1" gradientTransform="matrix(.76393 2.0604 -2.4476 .90749 21.14 11.793)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iHzFALe" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -35 39.094)scale(1.57898 4.87127)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iZvW1mY" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33365 0 0 -9.43517 19.155 10.832)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="i3nWNee" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04291 12.67487 -10.49633 -.86366 17.904 4.799)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="tp6f6fbae"/><stop offset="1" class="vj4k8-jab"/></radialGradient><radialGradient id="iBhO8fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17159 1.44984 0 18.787 9.492)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="i6gj2TY" cx="0" cy="0" r="1" gradientTransform="matrix(.00401 -1.11642 1.21493 .00436 13.943 9.54)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="il3gKae" cx="0" cy="0" r="1" gradientTransform="matrix(-8.66792 .54716 -1.39772 -22.14213 19.792 11.84)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="ihaBDXb" cx="0" cy="0" r="1" gradientTransform="matrix(4.15543 -2.70187 .98908 1.52118 10.712 6.42)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="ixfBInd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2394 2.54798 -1.01853 -.0957 21.947 7.855)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="i0pA9hd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.761 8.168)scale(3.43716 2.83765)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iPXb56d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.52209 -6.44806 0 15.662 4.536)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="xtf-7zbtn"/><stop offset="1" class="th4w0lbjs"/></radialGradient><radialGradient id="iBA91Oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24904 -.7827 0 16.766 12.22)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iVW3ezc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55193 .71154 -1.1435 -2.49407 16.884 11.64)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="ixKzAIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73532 2.95839 0 16.29 14.443)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iAFuVYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.57218 9.03363 0 10.955 7.881)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="izDpCGc" cx="0" cy="0" r="1" gradientTransform="matrix(.11635 -2.5634 4.54181 .20615 21.25 9.218)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iPJ0Bgb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40657 -1.5828 1.16186 -1.76655 20.48 2.815)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iXp4vLc" cx="0" cy="0" r="1" gradientTransform="matrix(.92343 1.50484 -3.48452 2.13823 15.367 1.19)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="ifmGgAe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24567 0 0 -.83346 16.549 3.495)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="if9DUle" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.194 -5.993)scale(6.14858 6.81199)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ijZOrKb" cx="0" cy="0" r="1" gradientTransform="matrix(3.31395 .38734 -.16217 1.38748 18.073 5.88)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iU7Y07c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82774 -1.31661 0 18.516 9.897)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9Js56I" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.586 .514)scale(.38594 .53136)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="il13AOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82778 -1.31668 0 14.064 9.897)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ioFG9Vc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.868 -1.718)scale(.50414 .60601)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isG3DAd" cx="0" cy="0" r="1" gradientTransform="matrix(.64127 2.28867 -2.18357 .61182 21.001 9.912)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iROiPlc" cx="0" cy="0" r="1" gradientTransform="matrix(.80372 -1.10298 .92452 .67368 21.369 10.467)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iKRE72b" cx="0" cy="0" r="1" gradientTransform="matrix(.59888 -1.5818 2.1135 .80018 21.485 10.643)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="im0Tczd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.323 9.522)scale(2.15952 2.123)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iUzVccd" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 5.188 5.764)scale(.9487 .41843)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="i8riDQc" cx="0" cy="0" r="1" gradientTransform="rotate(-100.732 11.899 -4.871)scale(3.6749 8.45124)" gradientUnits="userSpaceOnUse"><stop class="c3tjvjbdr"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="igWQ4Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.99817 -7.31619 0 16.238 2.866)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iA8batd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.03 2.396)" gradientUnits="userSpaceOnUse"><stop class="h02irqbsf"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iwLUd5s" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.06 3.02)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="ikCMC7b" width="5.32" height="9.565" x="13.616" y="9.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".2"/></filter><filter id="iWbMg8d" width=".65" height="8.268" x="24.401" y="3.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".125"/></filter><filter id="iPNkBhc" width="8.964" height="6.734" x="11.808" y="23.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".075"/></filter><filter id="iqNXXSd" width="11.427" height="12.791" x="11.124" y="4.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1582"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1582" result="effect2_innerShadow_4002_1582"/></filter><filter id="iOa6wfe" width="3.782" height="4.959" x="14.254" y="8.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".5"/></filter><filter id="iFlaqeb" width="2.315" height="3.359" x="15.133" y="9.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".1"/></filter><filter id="iNENIVc" width="3.784" height="1.595" x="14.398" y="13.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".05"/></filter><filter id="itFtHKc" width="13.133" height="8.27" x="9.723" y="1.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1582"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1582" result="effect2_innerShadow_4002_1582"/></filter><filter id="iasG0td" width="2.384" height="1.21" x="17.912" y="7.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1582"/></filter><filter id="ibhyi3b" width="2.384" height="1.196" x="12.549" y="7.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1582"/></filter><filter id="iBYai7b" width="7.207" height="6.603" x="9.841" y="2.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1582"/><feGaussianBlur result="effect2_foregroundBlur_4002_1582" stdDeviation=".25"/></filter><filter id="iSNRSxF" width="6.986" height="6.347" x="15.877" y="2.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1582"/><feGaussianBlur result="effect2_foregroundBlur_4002_1582" stdDeviation=".25"/></filter><filter id="iUuSGdb" width=".799" height=".706" x="17.769" y="9.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".05"/></filter><filter id="iWVo8sd" width=".901" height=".924" x="18.628" y="9.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".1"/></filter><filter id="iYq4IZb" width=".998" height="1.053" x="14.095" y="9.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".1"/></filter><filter id="iYIFYOt" width=".928" height=".715" x="13.323" y="9.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".05"/></filter><filter id="isH8mxd" width="1.346" height="2.417" x="10.091" y="9.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".125"/></filter><filter id="iRkxJCc" width="1.966" height="2.942" x="20.833" y="9.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".25"/></filter><filter id="iGJh7Wb" width="2.439" height="1.168" x="12.474" y="7.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".125"/></filter><filter id="iOkGlhb" width="2.439" height="1.168" x="17.86" y="7.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".125"/></filter><filter id="i22psse" width="5.842" height="3.536" x="16.952" y="3.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1582" stdDeviation=".5"/></filter><filter id="iK8Dfmd" width="12.586" height="3.001" x="9.977" y="3.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1582"/></filter><linearGradient id="isxOM5p" x1="23.98" x2="25.166" y1="8.942" y2="8.942" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="ijC9E3c" x1="25.226" x2="25.226" y1="3.708" y2="11.476" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="ikaneie" x1="25.774" x2="23.455" y1="14.806" y2="14.806" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iOajgKb" x1="23.406" x2="24.469" y1="14.602" y2="14.727" gradientUnits="userSpaceOnUse"><stop class="nnh5vk6mb"/><stop offset="1" class="boxqtwbke"/></linearGradient><linearGradient id="iaN6sOc" x1="9.205" x2="8.779" y1="28.064" y2="28.064" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iTMEo7d" x1="16.29" x2="16.29" y1="29.864" y2="23.431" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iVAkv8g" x1="21.552" x2="17.111" y1="12.551" y2="12.551" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="ilvdK8d" x1="17.145" x2="16.29" y1="11.521" y2="11.556" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iGH5Wdc" x1="16.29" x2="16.29" y1="12.683" y2="12.209" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="ijsk4Sc" x1="16.29" x2="16.29" y1="9.669" y2="10.481" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="ikcSV7c" x1="15.064" x2="15.389" y1="14.286" y2="13.434" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iJHKUid" x1="23.281" x2="11.433" y1="5.055" y2="5.055" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iDIaZmc" x1="19.31" x2="18.99" y1="9.952" y2="10.149" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuCGgxb" x1="14.823" x2="14.503" y1="9.952" y2="10.15" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLoOh2b" x1="22.857" x2="21.625" y1="9.98" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iZ7e5ic" x1="10.322" x2="11.81" y1="10.698" y2="10.568" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iiaFIGb" x1="21.816" x2="21.816" y1="9.59" y2="11.532" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="i9aYweb" x1="18.06" x2="16.779" y1="3.958" y2="-.417" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:student-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.axzg-ebdr {
  d: path("M16.29 13.787a3.1 3.1 0 0 1-1.413-.335c-.14-.07-.29.087-.202.213c.341.518.937.864 1.615.864s1.274-.346 1.616-.864c.088-.132-.063-.284-.202-.213a3.05 3.05 0 0 1-1.414.335");
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.bb4ekeb8f {
  d: path("M21.25 12.107c.342-.01.662-.127.923-.314v.95c0 .91-.543 1.722-1.368 2.06q.261-.557.353-1.205z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bevfv5kqa {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.295 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.boxqtwbke {
  stop-color: var(--svg-color--fbb229, #FBB229);
  stop-opacity: 0;
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.c3tjvjbdr {
  stop-color: var(--svg-color--534d5a, #534D5A);
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cb5n4zbnr {
  d: path("M23.52 29.995V18.21a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.cd8tkrb3l {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M16.527 5.103a3 3 0 0 1-.067-.14a.68.68 0 0 0-.628-.427h-1.299c-1.883 0-3.409 1.544-3.409 3.448v.28c-.347-.263-.783-.82-.783-1.721c0-1.094.798-1.647 1.306-2c.144-.099.265-.182.338-.258l.101-.107c.357-.378.992-1.052 2.102-1.346a5.6 5.6 0 0 1 1.554-.168c.473.012.806.42.806.894v1.531z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d7mr3f46j {
  d: path("M11.134 8.936a1.642 1.642 0 0 0 .141 3.264a80 80 0 0 1-.141-3.264");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ecao01bgn {
  d: path("M9.06 29.995V18.21a10.97 10.97 0 0 0-3.765 8.286v3.5z");
}

.enkgnbc3v {
  d: path("M24.223 11.644a.838.838 0 1 0 .8 0z");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f__9j_9_e {
  d: path("M23.311 18.094a.24.24 0 0 0-.059-.29c-1.856-1.602-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.014 7.013-4.614");
}

.f-zri6bjh {
  d: path("M16.295 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.h02irqbsf {
  stop-color: var(--svg-color--6a6273, #6A6273);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ic7o6y_ui {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.451 9.603c.065.087-.07.192-.224.308c-.155.115-.269.196-.334.11s.008-.251.162-.366c.154-.116.332-.139.396-.052");
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jobrpk3-g {
  d: path("M14.062 9.41a.91.91 0 0 0-.877 1.151h1.758a1 1 0 0 0 .034-.24a.917.917 0 0 0-.915-.91");
}

.jp_cikcwt {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.726 3.709v7.767");
}

.jqtoh3u7m {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.996 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587Z");
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kc50k7g2g {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.81 7.68a2.83 2.83 0 0 1 1.774-.367a.283.283 0 1 1-.069.563a2.26 2.26 0 0 0-1.414.29q-.052.032-.077.05l-.017.011l-.003.003a.283.283 0 0 1-.346-.448z");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kna2v6epf {
  d: path("M19.93 23.771c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l-xm7ybzq {
  stop-color: var(--svg-color--2a1418, #2A1418);
}

.l119f_b3a {
  d: path("M21.312 12.2q.102-1.627.188-3.256a1.642 1.642 0 0 1-.189 3.256");
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lincvjbcr {
  d: path("M25.023 11.668V2.805h-.8v8.863z");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m3w3mu5nz {
  d: path("M24.233 3.605H8.263c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.m4nqgzb4s {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.88 10.303l-.602 1.875c-.103.386.144.772.494.772h.746c.35 0 .598-.392.495-.772l-.505-1.875c-.108-.416-.514-.416-.627 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mvdx7rbmf {
  d: path("M18.451 9.603c.065.087-.07.192-.224.308c-.155.115-.269.196-.334.11s.008-.251.162-.366c.154-.116.332-.139.396-.052");
}

.n7_rqhqtz {
  d: path("M14.894 10.214c0-.294-.24-.49-.304-.55l-.294.285l.18.369z");
}

.nf5c-bcfg {
  d: path("m23.77 13.605l-.517 2.238a.45.45 0 0 0 .445.552h1.863a.45.45 0 0 0 .43-.557l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nnh5vk6mb {
  stop-color: var(--svg-color--bd9130, #BD9130);
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.ol6uh1m-f {
  cx: 13.787px;
  cy: 9.8px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.201px;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
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

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pwa-xfb8m {
  stop-color: var(--svg-color--655f6b, #655F6B);
}

.py694yfhp {
  d: path("M15.996 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587");
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qexz1bccf {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.911 13.386c.398.207.873.326 1.38.326c.51 0 .98-.119 1.378-.326a.23.23 0 0 1 .275.045c.065.068.09.177.024.276m-3.057-.321l2.995.28m-2.995-.28a.23.23 0 0 0-.275.047a.215.215 0 0 0-.023.274m.298-.321l-.236.28m3.293.04v.001l-.062-.042m.062.042l-.062-.042m.062.042a2 2 0 0 1-1.678.896a2 2 0 0 1-1.677-.896m3.293-.042a1.93 1.93 0 0 1-1.616.864a1.93 1.93 0 0 1-1.615-.864m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.qio3z_1sa {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.85 9.133c-.665 0-1.228.46-1.381 1.08a.28.28 0 0 0 .273.348h2.276c.145 0 .26-.132.232-.277a1.43 1.43 0 0 0-1.4-1.15");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rcma9du_f {
  cx: 13.787px;
  cy: 9.8px;
  rx: 0.398px;
  ry: 0.201px;
}

.risafibjz {
  d: path("M11.102 9.61a.975.975 0 0 0 .085 1.917a80 80 0 0 1-.085-1.918");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sdf_4ut8h {
  d: path("M18.518 9.41a.91.91 0 0 1 .878 1.151h-1.76a.914.914 0 0 1 .881-1.15");
}

.sijhs0p7u {
  d: path("m15.9 10.103l-.542 1.876c-.11.386.155.771.531.771h.802c.377 0 .642-.392.531-.771l-.542-1.876c-.116-.415-.658-.415-.78 0");
}

.smyr16b9u {
  stop-color: var(--svg-color--3b2426, #3B2426);
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t3ao3kwso {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.73 9.133c.666 0 1.229.46 1.382 1.08a.28.28 0 0 1-.273.348h-2.277a.235.235 0 0 1-.232-.277a1.426 1.426 0 0 1 1.4-1.15");
}

.t64f_zb4c {
  d: path("M21.333 11.532q.06-.97.113-1.942a.975.975 0 0 1-.113 1.942");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tf-w6nr7g {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.923 7.919c-.262-.188-.915-.519-1.688-.389");
}

.th4w0lbjs {
  stop-color: var(--svg-color--2a161c, #2A161C);
  stop-opacity: 0;
}

.tp6f6fbae {
  stop-color: var(--svg-color--2d1720, #2D1720);
  stop-opacity: 0;
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.uaqfy8bjj {
  fill: var(--svg-color--000, #000);
  d: path("M17.997 10.321a.52.52 0 0 1 .521-.521a.52.52 0 0 1 .464.761h-.923a.5.5 0 0 1-.062-.24");
}

.ufecrmb8z {
  d: path("m9.977 5.228l1.21-1.973l10.258-.11l1.117 2.02c-4.664 1.61-10.496.797-12.585.063");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
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

.v-lgd2shh {
  d: path("M11.368 13.653a3.995 3.995 0 0 0 3.964 3.475h1.925a3.995 3.995 0 0 0 3.964-3.475c.12-1.922.241-3.836.33-5.757a1.48 1.48 0 0 0-1.406-1.461h-1.429a2.47 2.47 0 0 1-2.256-1.472a.68.68 0 0 0-.628-.427h-1.299c-1.883 0-3.409 1.543-3.409 3.448c0 1.898.119 3.766.243 5.669");
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vj4k8-jab {
  stop-color: var(--svg-color--2d1720, #2D1720);
}

.vma-jccep {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.9 10.103l-.542 1.876c-.11.386.155.771.531.771h.802c.377 0 .642-.392.531-.771l-.542-1.876c-.116-.415-.658-.415-.78 0");
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vwr4k2bur {
  fill: var(--svg-color--000, #000);
  d: path("M14.583 10.321a.52.52 0 0 0-.521-.521a.52.52 0 0 0-.464.761h.923a.5.5 0 0 0 .062-.24");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.w9mft0urs {
  d: path("M15.944 23.771c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.web_sjb4c {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.849 7.966c.262-.188.915-.519 1.688-.389");
}

.wfvemhb9j {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.568 5.12h-2.123a.492.492 0 1 1 .078-.98c.551.087 1.283.21 1.773.331c1.107.275 1.413.814 1.498 1.198a1.54 1.54 0 0 0-1.226-.549");
}

.wmsnfnb2d {
  d: path("M19.33 10.201a.86.86 0 0 0-.237-.472l-.265.291l.12.233z");
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wq1729b8j {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.608 8.436l-.03-.644c-.01-.78-.654-1.422-1.433-1.455h-1.429a2.47 2.47 0 0 1-2.167-1.285s-.065-.152-.131-.41c-.248-.972.678-1.713 1.663-1.524c1.002.191 2.15.528 2.996 1.08c1.78 1.16 1.468 3.252.531 4.238");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x_834_31y {
  d: path("m21.608 8.436l-.03-.644c-.01-.78-.654-1.422-1.433-1.455h-1.429a2.47 2.47 0 0 1-2.167-1.285s-.065-.152-.131-.41c-.248-.972.678-1.713 1.663-1.524c1.002.191 2.15.528 2.996 1.08c1.78 1.16 1.468 3.252.531 4.238");
}

.x3t2hmtbe {
  stop-color: var(--svg-color--46404e, #46404E);
}

.x4e9_o_2d {
  stop-color: var(--svg-color--3a3142, #3A3142);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xgi4edb4w {
  d: path("M11.958 23.771c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xtf-7zbtn {
  stop-color: var(--svg-color--2a161c, #2A161C);
}

.xud4sna1e {
  d: path("M21.243 4.055c.525.18.996.547 1.293 1.072a2.42 2.42 0 0 1-.108 2.578a1.6 1.6 0 0 0-.276.892v1.212a1.8 1.8 0 0 0-.68-.274l.08-1.639a1.48 1.48 0 0 0-1.407-1.46h-1.429a2.47 2.47 0 0 1-2.256-1.473a.68.68 0 0 0-.628-.427h-1.299c-1.883 0-3.409 1.544-3.409 3.448l.032 1.568c-.26.038-.53.125-.735.27V8.596c0-.318-.098-.63-.276-.892a2.44 2.44 0 0 1-.146-2.496a2.4 2.4 0 0 1 1.326-1.149a2.74 2.74 0 0 0 1.412-1.132c.422-.673 1.163-.876 2.013-.876c.33 0 .644.07.936.191c.39.17.828.17 1.217 0a2.4 2.4 0 0 1 .931-.191c.86 0 1.613.219 2.03.908c.313.52.805.898 1.38 1.095");
}

.xuw5xge2n {
  stop-color: var(--svg-color--655f6b, #655F6B);
  stop-opacity: 0;
}

.y3tg7-iqo {
  fill: var(--svg-color--202020, #202020);
  d: path("M20.099 7.792c-.18-.156-.387-.32-.702-.42c-.31-.097-.699-.124-1.237-.058a.283.283 0 1 0 .069.562c.49-.06.791-.03.998.036c.203.064.34.167.5.307a.283.283 0 0 0 .372-.427");
}

.y5tai6bvg {
  d: path("M16.527 5.103a3 3 0 0 1-.067-.14a.68.68 0 0 0-.628-.427h-1.299c-1.883 0-3.409 1.544-3.409 3.448v.28c-.347-.263-.783-.82-.783-1.721c0-1.094.798-1.647 1.306-2c.144-.099.265-.182.338-.258l.101-.107c.357-.378.992-1.052 2.102-1.346a5.6 5.6 0 0 1 1.554-.168c.473.012.806.42.806.894v1.531z");
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yl8yg_b1a {
  stop-color: var(--svg-color--9b6733, #9B6733);
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yv1lsr29z {
  d: path("M11.33 12.107a1.7 1.7 0 0 1-.922-.314v.95c0 .91.543 1.722 1.368 2.06a4.2 4.2 0 0 1-.353-1.205z");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
