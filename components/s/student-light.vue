<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bevfv5kqa"/><path fill="url(#il7lKLc)" class="f-zri6bjh"/><path fill="url(#iW3ezjv)" class="f-zri6bjh"/><path fill="url(#iCXSqte)" class="tct0zob3r"/><path fill="url(#iSGsUvb)" class="tct0zob3r"/><path fill="url(#il6f8id)" class="tct0zob3r"/><path fill="url(#iYEAYDd)" class="tct0zob3r"/><path fill="url(#issWafd)" class="tct0zob3r"/><path fill="url(#iFsyc0g)" class="tct0zob3r"/><g filter="url(#iqIhVcb)"><path class="ofecofbve"/></g><path fill="url(#iJeErGb)" class="zi1d-yb6p"/><path fill="url(#i46u6hd)" class="zi1d-yb6p"/><path fill="url(#iaUaDib)" class="zi1d-yb6p"/><path fill="url(#isxOM5p)" class="lincvjbcr"/><path fill="url(#iyORuOS)" class="lincvjbcr"/><path fill="url(#iCz2QCb)" class="tmc43ibfa"/><path fill="url(#iAlt1lf)" class="tmc43ibfa"/><g filter="url(#iEAqCAb)"><path stroke="url(#iCcwxCe)" class="jp_cikcwt"/></g><path fill="url(#ikaneie)" class="ale6avb2w"/><path fill="url(#iatfXxe)" class="ale6avb2w"/><path fill="url(#itz1Vme)" class="ale6avb2w"/><path fill="url(#ifKi4Nd)" class="ale6avb2w"/><path fill="url(#idypxXc)" class="ale6avb2w"/><path fill="url(#i0dWUje)" class="ecao01bgn"/><path fill="url(#iy20hXd)" class="ecao01bgn"/><path fill="url(#iaN6sOc)" class="ecao01bgn"/><path fill="url(#i7Knznd)" class="cb5n4zbnr"/><path fill="url(#iL1AGYc)" class="cb5n4zbnr"/><g filter="url(#issnlie)"><path fill="url(#iTMEo7d)" class="xgi4edb4w"/><path fill="url(#iTMEo7d)" class="w9mft0urs"/><path fill="url(#iTMEo7d)" class="kna2v6epf"/></g><g filter="url(#i29gtUb)"><path class="xs2jpzdzd"/></g><g filter="url(#iufuAfa)"><path class="rdd_rzeni"/></g><g filter="url(#iomYW6d)"><path class="geadx-col"/></g><path fill="url(#i84Chqb)" class="kgxb51byf"/><path fill="url(#id7mVvH)" class="n4yhn7q1t"/><g filter="url(#i5FCxRc)"><path fill="url(#iuCAize)" class="gwzh-zi1f"/></g><path fill="url(#iaLc0ec)" class="gwzh-zi1f"/><path fill="url(#ioePp0d)" class="gwzh-zi1f"/><path fill="url(#iaYEIhc)" class="gwzh-zi1f"/><path fill="url(#iUCCTib)" class="gwzh-zi1f"/><path fill="url(#iZW0BOd)" class="gwzh-zi1f"/><path fill="url(#iKWpq5d)" class="gwzh-zi1f"/><path fill="url(#ipOVrue)" class="gwzh-zi1f"/><path fill="url(#iNIkNXc)" class="gwzh-zi1f"/><g filter="url(#iPDPcIb)"><path class="qknmspvjt"/></g><g filter="url(#idHjBPF)"><path class="ke9g9eh4y"/><path fill="url(#iQajOkI)" class="w7fpycjuk"/><path fill="url(#iU2R5BC)" class="w7fpycjuk"/><path fill="url(#iSJBIqc)" class="w7fpycjuk"/><path fill="url(#ikOuXYd)" class="w7fpycjuk"/><path fill="url(#iEdYwdd)" class="w7fpycjuk"/></g><g filter="url(#iQBbxec)"><path stroke="url(#i6YcGvd)" class="de2jubc1h"/></g><path fill="url(#iWZC3bS)" class="e52z6kcxf"/><g filter="url(#iZQwQ8d)"><path fill="url(#i9xJuGd)" class="xtrc7ig_b"/><path fill="url(#iGeuesb)" class="xtrc7ig_b"/><path fill="url(#iVUY6yP)" class="xtrc7ig_b"/><path fill="url(#i7FCX1d)" class="xtrc7ig_b"/><path fill="url(#ivGOKQc)" class="xtrc7ig_b"/></g><g filter="url(#iSQlvUc)"><path class="c7kh6abtl"/></g><g filter="url(#iCAhz9R)"><path class="nnz6t4b0o"/></g><g filter="url(#itC6wWd)"><path class="di_2a_bwq"/><path fill="url(#igWhdMc)" class="ilsn2ifgb"/><path fill="url(#imc3XRc)" class="ilsn2ifgb"/></g><g filter="url(#isDlsne)"><path class="qhspllbye"/><path fill="url(#i57Py6d)" class="nseljabpx"/><path fill="url(#iqR0GTc)" class="nseljabpx"/><path fill="url(#ijaXL3d)" class="nseljabpx"/></g><path class="op6kxd3yy"/><path fill="url(#i12ak9c)" class="rnzzdsbne"/><path class="b0gjcszed"/><g filter="url(#iPwklAd)"><path class="b2gvc8bfz"/><path fill="url(#iQ2jQSc)" class="w2ola16qo"/></g><g filter="url(#iWFgtYb)"><path fill="url(#ifoipcd)" class="fo-idgb5p"/></g><path class="moh04tbtd"/><path fill="url(#i6YpobX)" class="idgmbjb4s"/><path class="bnqbt0jwn"/><g filter="url(#ilWN05d)"><path fill="url(#imuTrab)" class="ac1ghbb5c"/></g><g filter="url(#iCU1CMe)"><ellipse transform="rotate(-27.914 13.777 9.775)" class="imzqgwkvu"/><ellipse fill="url(#ig75lLb)" transform="rotate(-27.914 13.777 9.775)" class="ilag76bzc"/></g><path fill="url(#iwmPzNd)" class="bnovknbjh"/><path fill="url(#iGex08c)" class="bnovknbjh"/><path fill="url(#iaixUCb)" class="bnovknbjh"/><path fill="url(#iCSGo7V)" class="bnovknbjh"/><path fill="url(#i7DnnXc)" class="qr_-d9bmj"/><path fill="url(#ihc5RFd)" class="qr_-d9bmj"/><g filter="url(#iVFJasc)"><path fill="url(#i2sYKpd)" class="nudvne1xf"/></g><g filter="url(#iwRrtiX)"><path fill="url(#i4DPKid)" class="cj021cbrp"/></g><g filter="url(#iudI59d)"><path class="n1v8vjb0t"/></g><g filter="url(#iRe2mYc)"><path class="s-wg5gbrx"/></g><g filter="url(#iE3VNGd)"><path fill="url(#i323JHc)" class="p69vqy-6r"/><path fill="url(#igWQ4Pe)" class="p69vqy-6r"/></g><path fill="url(#i9aYweb)" class="m3w3mu5nz"/><path fill="url(#iA8batd)" class="m3w3mu5nz"/><path fill="url(#iYR2abe)" class="m3w3mu5nz"/><defs><radialGradient id="il7lKLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.592 23.114)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iW3ezjv" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.998 21.458)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iCXSqte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 15.8584 0 16.298 21.349)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="x3t2hmtbe"/><stop offset="1" class="x4e9_o_2d"/></radialGradient><radialGradient id="iSGsUvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.29 16.896)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="il6f8id" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.873 15.552)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iYEAYDd" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.623 15.318)" gradientUnits="userSpaceOnUse"><stop offset=".939" class="xuw5xge2n"/><stop offset=".971" class="pwa-xfb8m"/></radialGradient><radialGradient id="issWafd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.29 23.614)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iFsyc0g" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.40625 -5.25876 0 16.29 16.063)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="i8onqub3d"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iJeErGb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.594 18.22)" gradientUnits="userSpaceOnUse"><stop class="maef1bbsj"/><stop offset="1" class="ws5zlibzm"/><stop offset="1" class="rchayobux"/></radialGradient><radialGradient id="i46u6hd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.276 16.985)" gradientUnits="userSpaceOnUse"><stop class="dr7jm_b-p"/><stop offset="1" class="eths-3bvt"/></radialGradient><radialGradient id="iaUaDib" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.276 14.544)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="im04-mb9w"/><stop offset="1" class="wg5q2jt7g"/></radialGradient><radialGradient id="iyORuOS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.865 11.668)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="iCz2QCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.123 12.04)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="iAlt1lf" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.785 12.431)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="itz1Vme" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.257 8.551)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ifKi4Nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.623 16.896)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="yl8yg_b1a"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="idypxXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.623 13.107)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="i0dWUje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.295 29.995)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iy20hXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.06 29.995)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="i7Knznd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.402 29.995)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iL1AGYc" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.35 23.157)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="i84Chqb" cx="0" cy="0" r="1" gradientTransform="matrix(.76245 2.0564 -2.44285 .90573 21.116 11.764)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="id7mVvH" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -34.905 39.07)scale(1.57592 4.86181)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iuCAize" cx="0" cy="0" r="1" gradientTransform="matrix(-5.32329 0 0 -9.41684 19.134 10.805)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="ioePp0d" cx="0" cy="0" r="1" gradientTransform="scale(10.7392 12.9682)rotate(90 .6 .971)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="b7s_9m73d"/><stop offset=".981" class="ixz611wvi"/></radialGradient><radialGradient id="iaYEIhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16931 1.44703 0 18.767 9.468)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iUCCTib" cx="0" cy="0" r="1" gradientTransform="matrix(.004 -1.11425 1.21257 .00436 13.933 9.516)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iZW0BOd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.65108 .5461 -1.39501 -22.09921 19.77 11.811)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iKWpq5d" cx="0" cy="0" r="1" gradientTransform="matrix(3.15498 -3.3376 1.2218 1.15494 10.708 6.401)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="ipOVrue" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.756 8.154)scale(3.43048 2.83214)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iNIkNXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.35737 -6.02695 0 15.65 4.522)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="o0ba6bclk"/><stop offset="1" class="ocb114bkm"/></radialGradient><radialGradient id="iU2R5BC" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24856 -.78119 0 16.75 12.19)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="ikOuXYd" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 7.167 7.647)scale(1.70396 2.73839)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iWZC3bS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.7339 2.95264 0 16.275 14.41)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iGeuesb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.56524 9.01608 0 10.95 7.86)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iVUY6yP" cx="0" cy="0" r="1" gradientTransform="matrix(.11612 -2.5584 4.533 .20575 21.225 9.194)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i7FCX1d" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.648 -1.66)scale(2.87483 2.11027)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="ivGOKQc" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.62 14.309)scale(1.76215 4.08032)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="igWhdMc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24131 0 0 -.83184 16.534 3.483)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="imc3XRc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.174 -6)scale(6.13664 6.79876)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i57Py6d" cx="0" cy="0" r="1" gradientTransform="matrix(3.11422 0 0 1.21761 19.752 4.273)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iqR0GTc" cx="0" cy="0" r="1" gradientTransform="matrix(2.72763 -2.59876 4.75766 4.99359 18.957 7.366)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="ijaXL3d" cx="0" cy="0" r="1" gradientTransform="matrix(3.30751 .3866 -.16186 1.3848 18.055 5.863)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i12ak9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8257 -1.31337 0 18.497 9.872)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iQ2jQSc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.571 .506)scale(.38519 .53032)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6YpobX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82574 -1.31344 0 14.053 9.872)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ig75lLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00788 -.5031 .60475 -.00947 13.762 10.096)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGex08c" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 3.97 18.776)scale(2.3722 2.26326)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iaixUCb" cx="0" cy="0" r="1" gradientTransform="matrix(.80216 -1.10084 .92272 .67237 21.345 10.441)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iCSGo7V" cx="0" cy="0" r="1" gradientTransform="matrix(.59771 -1.57873 2.1094 .79863 21.461 10.617)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="ihc5RFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64261 -.2007 .21544 -1.76327 11.27 10.542)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="i2sYKpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.93272 .1601 -.19646 -1.1445 11.27 10.541)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="i323JHc" cx="0" cy="0" r="1" gradientTransform="rotate(-100.732 11.9 -4.871)scale(3.6749 8.45124)" gradientUnits="userSpaceOnUse"><stop class="c3tjvjbdr"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="igWQ4Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.99817 -7.31619 0 16.238 2.866)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iA8batd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.03 2.396)" gradientUnits="userSpaceOnUse"><stop class="h02irqbsf"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iYR2abe" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.06 3.021)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="iqIhVcb" width="5.32" height="9.564" x="13.616" y="9.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".2"/></filter><filter id="iEAqCAb" width=".65" height="8.268" x="24.401" y="3.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".125"/></filter><filter id="issnlie" width="8.964" height="6.734" x="11.808" y="23.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".075"/></filter><filter id="i29gtUb" width="5.842" height="3.536" x="16.952" y="3.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".5"/></filter><filter id="iufuAfa" width="5.842" height="3.536" x="16.952" y="3.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".5"/></filter><filter id="iomYW6d" width="5.96" height="3.583" x="17.098" y="3.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".5"/></filter><filter id="i5FCxRc" width="11.407" height="12.767" x="11.12" y="4.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1594"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1594" result="effect2_innerShadow_4002_1594"/></filter><filter id="iPDPcIb" width="3.779" height="4.953" x="14.242" y="8.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".5"/></filter><filter id="idHjBPF" width="2.312" height="3.353" x="15.12" y="9.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".1"/></filter><filter id="iQBbxec" width="3.777" height="1.592" x="14.387" y="13.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".05"/></filter><filter id="iZQwQ8d" width="13.108" height="8.112" x="9.722" y="1.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1594"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1594" result="effect2_innerShadow_4002_1594"/></filter><filter id="iSQlvUc" width="2.38" height="1.209" x="17.894" y="7.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1594"/></filter><filter id="iCAhz9R" width="2.38" height="1.193" x="12.541" y="7.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1594"/></filter><filter id="itC6wWd" width="7.195" height="6.592" x="9.838" y="2.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1594"/><feGaussianBlur result="effect2_foregroundBlur_4002_1594" stdDeviation=".25"/></filter><filter id="isDlsne" width="6.973" height="6.337" x="15.863" y="2.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".25"/></filter><filter id="iPwklAd" width=".798" height=".705" x="17.752" y="9.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".05"/></filter><filter id="iWFgtYb" width=".899" height=".921" x="18.609" y="9.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".1"/></filter><filter id="ilWN05d" width=".997" height="1.052" x="14.085" y="9.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".1"/></filter><filter id="iCU1CMe" width=".926" height=".714" x="13.314" y="9.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".05"/></filter><filter id="iVFJasc" width="1.344" height="2.413" x="10.088" y="9.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".125"/></filter><filter id="iwRrtiX" width="1.964" height="2.938" x="20.873" y="9.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".25"/></filter><filter id="iudI59d" width="2.335" height="1.067" x="12.516" y="7.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".125"/></filter><filter id="iRe2mYc" width="2.335" height="1.067" x="17.892" y="7.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1594" stdDeviation=".125"/></filter><filter id="iE3VNGd" width="12.586" height="3.001" x="9.977" y="3.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1594"/></filter><linearGradient id="isxOM5p" x1="23.98" x2="25.166" y1="8.942" y2="8.942" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="iCcwxCe" x1="25.226" x2="25.226" y1="3.709" y2="11.476" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="ikaneie" x1="25.774" x2="23.455" y1="14.806" y2="14.806" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iatfXxe" x1="23.406" x2="24.469" y1="14.603" y2="14.728" gradientUnits="userSpaceOnUse"><stop class="nnh5vk6mb"/><stop offset="1" class="boxqtwbke"/></linearGradient><linearGradient id="iaN6sOc" x1="9.205" x2="8.779" y1="28.064" y2="28.064" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iTMEo7d" x1="16.29" x2="16.29" y1="29.864" y2="23.431" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iaLc0ec" x1="21.527" x2="17.095" y1="12.521" y2="12.521" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iQajOkI" x1="17.129" x2="16.276" y1="11.492" y2="11.528" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iSJBIqc" x1="16.276" x2="16.276" y1="12.652" y2="12.179" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iEdYwdd" x1="16.276" x2="16.276" y1="9.767" y2="10.454" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="i6YcGvd" x1="15.052" x2="15.376" y1="14.252" y2="13.402" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="i9xJuGd" x1="23.253" x2="11.428" y1="5.039" y2="5.039" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ifoipcd" x1="19.288" x2="18.97" y1="9.927" y2="10.123" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imuTrab" x1="14.811" x2="14.492" y1="9.927" y2="10.124" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwmPzNd" x1="22.83" x2="21.601" y1="9.955" y2="12.171" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="i7DnnXc" x1="10.319" x2="11.804" y1="10.671" y2="10.542" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="i4DPKid" x1="21.855" x2="21.855" y1="9.577" y2="11.515" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="i9aYweb" x1="18.06" x2="16.779" y1="3.958" y2="-.417" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:student-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.ac1ghbb5c {
  d: path("M14.882 10.189c0-.294-.239-.49-.303-.55l-.294.285l.18.368z");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.ale6avb2w {
  d: path("m23.77 13.605l-.517 2.239a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b0gjcszed {
  fill: var(--svg-color--000, #000);
  d: path("M17.979 10.295c0-.289.231-.52.52-.52a.518.518 0 0 1 .463.76h-.921a.47.47 0 0 1-.062-.24");
}

.b2gvc8bfz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.433 9.579c.064.086-.071.192-.225.307s-.268.196-.333.11c-.064-.087.008-.25.162-.366s.33-.138.396-.051");
}

.b7s_9m73d {
  stop-color: var(--svg-color--be8689, #BE8689);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bevfv5kqa {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.295 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.bnovknbjh {
  d: path("M21.288 12.17q.102-1.624.188-3.249a1.639 1.639 0 0 1-.188 3.25");
}

.bnqbt0jwn {
  fill: var(--svg-color--000, #000);
  d: path("M14.571 10.295a.52.52 0 0 0-.52-.52a.518.518 0 0 0-.462.76h.92a.5.5 0 0 0 .062-.24");
}

.boxqtwbke {
  stop-color: var(--svg-color--fbb229, #FBB229);
  stop-opacity: 0;
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c3tjvjbdr {
  stop-color: var(--svg-color--534d5a, #534D5A);
}

.c7kh6abtl {
  fill: var(--svg-color--202020, #202020);
  d: path("M20.077 7.771a1.9 1.9 0 0 0-.7-.419c-.31-.097-.698-.123-1.235-.058a.282.282 0 0 0 .068.56c.49-.06.79-.028.997.037c.202.064.338.167.498.306a.283.283 0 0 0 .372-.426");
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cb5n4zbnr {
  d: path("M23.52 29.995V18.21a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.cj021cbrp {
  d: path("M21.373 11.515q.06-.969.113-1.938a.973.973 0 0 1-.113 1.938");
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

.de2jubc1h {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.9 13.354h-.001a.23.23 0 0 0-.275.047a.214.214 0 0 0-.023.274c.355.537.972.894 1.674.894c.703 0 1.32-.357 1.675-.895a.22.22 0 0 0-.024-.275a.23.23 0 0 0-.274-.046a3 3 0 0 1-1.377.327a3 3 0 0 1-1.376-.326Z");
}

.di_2a_bwq {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.512 5.087l-.067-.139a.68.68 0 0 0-.627-.426h-1.296c-1.88 0-3.402 1.54-3.402 3.44v.28c-.346-.263-.782-.818-.782-1.718c0-1.091.796-1.643 1.304-1.995c.143-.099.264-.182.337-.258l.101-.106c.356-.378.99-1.05 2.098-1.344a5.6 5.6 0 0 1 1.55-.168c.472.013.806.42.806.894v1.527z");
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dr7jm_b-p {
  stop-color: var(--svg-color--b0797e, #B0797E);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e52z6kcxf {
  d: path("M16.275 13.755a3.06 3.06 0 0 1-1.41-.335c-.14-.07-.29.086-.202.213c.341.517.935.861 1.612.861s1.272-.344 1.613-.861c.087-.132-.062-.284-.202-.213a3.05 3.05 0 0 1-1.41.335");
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

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.eths-3bvt {
  stop-color: var(--svg-color--b0797e, #B0797E);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f-zri6bjh {
  d: path("M16.295 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fo-idgb5p {
  d: path("M19.308 10.175a.85.85 0 0 0-.235-.47l-.264.29l.119.231z");
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.geadx-col {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.794 5.105h-2.188a.508.508 0 1 1 .081-1.01c.568.09 1.322.216 1.827.34c1.141.284 1.456.84 1.544 1.236a1.6 1.6 0 0 0-1.264-.566");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gwzh-zi1f {
  d: path("M11.363 13.62a3.99 3.99 0 0 0 3.956 3.469h1.921a3.99 3.99 0 0 0 3.957-3.468c.12-1.918.24-3.829.33-5.746a1.476 1.476 0 0 0-1.404-1.458h-1.426a2.47 2.47 0 0 1-2.252-1.47a.68.68 0 0 0-.627-.425h-1.296c-1.88 0-3.402 1.54-3.402 3.44c0 1.895.118 3.76.243 5.659");
}

.h02irqbsf {
  stop-color: var(--svg-color--6a6273, #6A6273);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
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

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i8onqub3d {
  stop-color: var(--svg-color--170919, #170919);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.idgmbjb4s {
  d: path("M14.051 9.386a.908.908 0 0 0-.875 1.148h1.755a1 1 0 0 0 .033-.24a.915.915 0 0 0-.913-.908");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ilag76bzc {
  cx: 13.777px;
  cy: 9.775px;
  rx: 0.397px;
  ry: 0.201px;
}

.ilsn2ifgb {
  d: path("m16.512 5.087l-.067-.139a.68.68 0 0 0-.627-.426h-1.296c-1.88 0-3.402 1.54-3.402 3.44v.28c-.346-.263-.782-.818-.782-1.718c0-1.091.796-1.643 1.304-1.995c.143-.099.264-.182.337-.258l.101-.106c.356-.378.99-1.05 2.098-1.344a5.6 5.6 0 0 1 1.55-.168c.472.013.806.42.806.894v1.527z");
}

.im04-mb9w {
  stop-color: var(--svg-color--b5836a, #B5836A);
  stop-opacity: 0;
}

.imzqgwkvu {
  cx: 13.777px;
  cy: 9.775px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.ixz611wvi {
  stop-color: var(--svg-color--a56f76, #A56F76);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jp_cikcwt {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.726 3.709v7.767");
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.ke9g9eh4y {
  fill: var(--svg-color--deab9d, #DEAB9D);
  d: path("m15.886 10.078l-.541 1.872c-.11.385.155.77.53.77h.8c.376 0 .641-.391.531-.77l-.541-1.872c-.116-.415-.657-.415-.779 0");
}

.kgxb51byf {
  d: path("M21.226 12.078a1.67 1.67 0 0 0 .92-.314v.948c0 .91-.541 1.72-1.365 2.056q.262-.556.352-1.202z");
}

.kna2v6epf {
  d: path("M19.93 23.771c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lincvjbcr {
  d: path("M25.023 11.668V2.805h-.8v8.863z");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.m3w3mu5nz {
  d: path("M24.233 3.605H8.263c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.maef1bbsj {
  stop-color: var(--svg-color--cd9e8e, #CD9E8E);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.moh04tbtd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.84 9.11c-.664 0-1.226.458-1.379 1.078a.28.28 0 0 0 .273.347h2.272c.144 0 .26-.132.231-.277a1.43 1.43 0 0 0-1.396-1.148");
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n1v8vjb0t {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.84 7.945c.262-.188.914-.518 1.685-.388");
}

.n4yhn7q1t {
  d: path("M11.325 12.078a1.67 1.67 0 0 1-.92-.314v.948c0 .91.541 1.72 1.365 2.056a4.2 4.2 0 0 1-.352-1.202z");
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nnh5vk6mb {
  stop-color: var(--svg-color--bd9130, #BD9130);
}

.nnz6t4b0o {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.802 7.66a2.82 2.82 0 0 1 1.77-.366a.282.282 0 1 1-.067.56a2.26 2.26 0 0 0-1.413.29a1 1 0 0 0-.093.062l-.003.002a.282.282 0 0 1-.346-.447z");
}

.nseljabpx {
  d: path("m21.583 8.413l-.03-.642c-.01-.778-.653-1.42-1.43-1.452h-1.426c-.905 0-1.73-.495-2.163-1.283c0 0-.065-.15-.13-.405c-.249-.972.677-1.713 1.663-1.525c.998.192 2.142.527 2.986 1.077c1.776 1.159 1.465 3.247.53 4.23");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nudvne1xf {
  d: path("M11.097 9.585a.973.973 0 0 0 .085 1.913a80 80 0 0 1-.085-1.913");
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o0ba6bclk {
  stop-color: var(--svg-color--bf8679, #BF8679);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.ocb114bkm {
  stop-color: var(--svg-color--bf8679, #BF8679);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofecofbve {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.996 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.389 1.78-2.586v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.586Z");
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.op6kxd3yy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.71 9.11c.665 0 1.227.458 1.38 1.078a.28.28 0 0 1-.273.347h-2.272a.234.234 0 0 1-.231-.277A1.42 1.42 0 0 1 18.71 9.11");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p69vqy-6r {
  d: path("m9.977 5.228l1.21-1.973l10.258-.109l1.117 2.02c-4.664 1.609-10.496.796-12.585.062");
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

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pwa-xfb8m {
  stop-color: var(--svg-color--655f6b, #655F6B);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qhspllbye {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.583 8.413l-.03-.642c-.01-.778-.653-1.42-1.43-1.452h-1.426c-.905 0-1.73-.495-2.163-1.283c0 0-.065-.15-.13-.405c-.249-.972.677-1.713 1.663-1.525c.998.192 2.142.527 2.986 1.077c1.776 1.159 1.465 3.247.53 4.23");
}

.qknmspvjt {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.867 10.272l-.602 1.872c-.103.385.144.77.493.77h.745c.35 0 .596-.391.494-.77l-.504-1.872c-.108-.415-.513-.415-.626 0");
}

.qr_-d9bmj {
  d: path("M11.139 8.912a1.65 1.65 0 0 0-1.417 1.623c0 .875.685 1.59 1.548 1.636a79 79 0 0 1-.131-3.259");
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

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rchayobux {
  stop-color: var(--svg-color--b78273, #B78273);
}

.rdd_rzeni {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.568 5.058h-2.123a.492.492 0 1 1 .078-.98c.551.087 1.283.21 1.773.33c1.107.275 1.413.814 1.498 1.199a1.54 1.54 0 0 0-1.226-.55");
}

.rnzzdsbne {
  d: path("M18.499 9.386a.908.908 0 0 1 .875 1.148H17.62a.912.912 0 0 1 .88-1.148");
}

.s-wg5gbrx {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.902 7.898c-.262-.188-.914-.518-1.685-.388");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tct0zob3r {
  d: path("M23.311 18.094a.24.24 0 0 0-.059-.29c-1.856-1.602-4.346-2.486-6.954-2.486s-5.113.893-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.613 7.03 4.613s5.73-2.014 7.013-4.614");
}

.tmc43ibfa {
  d: path("M24.223 11.644a.837.837 0 1 0 .8 0z");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
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

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w2ola16qo {
  d: path("M18.433 9.579c.064.086-.071.192-.225.307s-.268.196-.333.11c-.064-.087.008-.25.162-.366s.33-.138.396-.051");
}

.w7fpycjuk {
  d: path("m15.886 10.078l-.541 1.872c-.11.385.155.77.53.77h.8c.376 0 .641-.391.531-.77l-.541-1.872c-.116-.415-.657-.415-.779 0");
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.w9mft0urs {
  d: path("M15.944 23.771c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.wg5q2jt7g {
  stop-color: var(--svg-color--b5836a, #B5836A);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.ws5zlibzm {
  stop-color: var(--svg-color--a56d67, #A56D67);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x3t2hmtbe {
  stop-color: var(--svg-color--46404e, #46404E);
}

.x4e9_o_2d {
  stop-color: var(--svg-color--3a3142, #3A3142);
}

.xgi4edb4w {
  d: path("M11.958 23.771c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xs2jpzdzd {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.568 5.12h-2.123a.492.492 0 1 1 .078-.98c.551.088 1.283.21 1.773.332c1.107.274 1.413.813 1.498 1.198a1.54 1.54 0 0 0-1.226-.55");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xtrc7ig_b {
  d: path("M21.219 4.041c.524.18.994.546 1.29 1.07a2.41 2.41 0 0 1-.107 2.573a1.6 1.6 0 0 0-.276.89v1.21a1.8 1.8 0 0 0-.68-.273l.08-1.636a1.476 1.476 0 0 0-1.403-1.458h-1.426a2.47 2.47 0 0 1-2.252-1.47a.68.68 0 0 0-.627-.425h-1.296c-1.88 0-3.402 1.54-3.402 3.44l.03 1.566a1.74 1.74 0 0 0-.732.269V8.574a1.6 1.6 0 0 0-.276-.89a2.43 2.43 0 0 1-.146-2.49a2.4 2.4 0 0 1 1.324-1.147a2.73 2.73 0 0 0 1.41-1.13c.42-.673 1.154-.732 2.002-.732c.33 0 .643.07.934.19c.39.17.827.17 1.215 0c.287-.12.6-.19.93-.19c.858 0 1.615.076 2.03.764c.314.519.805.896 1.378 1.092");
}

.xuw5xge2n {
  stop-color: var(--svg-color--655f6b, #655F6B);
  stop-opacity: 0;
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
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

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zi1d-yb6p {
  d: path("M15.996 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.389 1.78-2.586v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.586");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
