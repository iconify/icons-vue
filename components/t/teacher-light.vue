<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ilIH5zb)"><path fill="url(#ihm4Dnb)" class="k-m4isb6w"/></g><path fill="url(#iqdSD9Z)" class="zmw1qtb_r"/><path fill="url(#imwGFwb)" class="zmw1qtb_r"/><path fill="url(#idjIz7m)" class="zmw1qtb_r"/><g filter="url(#igrYVre)"><path stroke="url(#i2HGrEe)" class="vj9zlebew"/></g><g filter="url(#iU59dJe)"><path fill="url(#i28o8Pc)" class="xb6dt1xvv"/><path fill="url(#iej4Qpe)" class="xb6dt1xvv"/><path fill="url(#iBP5Q7c)" class="xb6dt1xvv"/></g><path fill="url(#ic7dWyd)" class="i1vg8bb9g"/><path fill="url(#i9lcdVc)" class="i1vg8bb9g"/><path fill="url(#iJSfG6b)" class="i1vg8bb9g"/><path fill="url(#iSbBxQb)" class="lj8q10b_x"/><path fill="url(#iqjwY6c)" class="lj8q10b_x"/><path fill="url(#i1xMH9b)" class="lj8q10b_x"/><path fill="url(#irlsuOc)" class="ny7bx-bsc"/><path fill="url(#i4yO6Qb)" class="ny7bx-bsc"/><path fill="url(#i9rh6Xd)" class="m52qiab0d"/><g filter="url(#iJHWiTm)"><path fill="url(#icqZPee)" class="gey85t6-q"/><path fill="url(#iEtGJYd)" class="gey85t6-q"/><path fill="url(#iC0JqRG)" class="gey85t6-q"/><path fill="url(#iV74exb)" class="gey85t6-q"/></g><g filter="url(#i2cfBqd)"><path fill="url(#i7jEZbb)" class="gprnkk-tp"/><path fill="url(#iV9Lkpc)" class="gprnkk-tp"/><path fill="url(#iZCzgse)" class="gprnkk-tp"/><path fill="url(#igYt98c)" class="gprnkk-tp"/></g><path fill="url(#ipuHZqe)" class="o-cmqab0a"/><g filter="url(#iChouWd)"><path fill="url(#i7bZ66a)" class="jkgpjaces"/><path fill="url(#i10lSyb)" class="jkgpjaces"/></g><g filter="url(#iWO2YAe)"><path fill="url(#iDNlp7d)" class="tgdtlzb0v"/></g><path fill="url(#i6Z86fb)" class="etmel4bjk"/><path clip-rule="evenodd" class="rksxibbzh"/><path fill="url(#igcdiBc)" clip-rule="evenodd" class="hacus_bfw"/><g filter="url(#iCqVgHd)"><path fill="url(#i95DBnd)" class="f-7_jnw-j"/><path fill="url(#iuS7g7b)" class="f-7_jnw-j"/><path fill="url(#i0OCTfc)" class="f-7_jnw-j"/><path fill="url(#iEl1GYd)" class="f-7_jnw-j"/><path fill="url(#iDPMkib)" class="f-7_jnw-j"/><path fill="url(#iIEPLJc)" class="f-7_jnw-j"/></g><g filter="url(#iMSnIXb)"><path fill="url(#i2UlxiW)" class="ekekh-b5z"/><path fill="url(#iLuNsld)" class="ekekh-b5z"/><path fill="url(#i4KNPmb)" class="ekekh-b5z"/><path fill="url(#icHSFbc)" class="ekekh-b5z"/><path fill="url(#iilKYUc)" class="ekekh-b5z"/></g><path fill="url(#iv0n0cA)" class="wchtn57td"/><path fill="url(#i7ryUsc)" class="dbqapzqvh"/><g filter="url(#iOmTR0b)"><path stroke="url(#irxFwPb)" class="kyahc60lg"/></g><g filter="url(#iBPzzjd)"><path stroke="url(#i13Eudd)" class="qf_uz6njq"/></g><g filter="url(#ibdKRrb)"><path stroke="url(#iiuqItd)" class="fos-u_bfq"/></g><g filter="url(#i0Xa2Ga)"><path stroke="url(#iX0Z5Ab)" class="yuu8kcc_x"/></g><g filter="url(#iVrJmEb)"><path stroke="url(#ioKkHod)" class="knignw1ns"/></g><g filter="url(#i3oUUvb)"><path stroke="url(#iwrRUPe)" class="eqlr_ly_k"/></g><path fill="url(#iRbJhfH)" class="t28omabpg"/><path fill="url(#icYayTb)" class="iegvepiks"/><g filter="url(#iJ7xhLe)"><path fill="url(#i4NTPMe)" class="iu8-hccbx"/></g><path fill="url(#igRrQQc)" class="iu8-hccbx"/><path fill="url(#iVQ5h8D)" class="iu8-hccbx"/><path fill="url(#i8NcWab)" class="iu8-hccbx"/><path fill="url(#iUTxGhc)" class="iu8-hccbx"/><path fill="url(#iWdVwhe)" class="iu8-hccbx"/><path fill="url(#iN4jRBc)" class="iu8-hccbx"/><path fill="url(#ikuhVjD)" class="iu8-hccbx"/><g filter="url(#ieR7vBh)"><path class="agmbz-z1k"/></g><g filter="url(#iIIqJvb)"><path class="zdw3afb3i"/><path fill="url(#iEuZ1Cd)" class="r2q-qsb2s"/><path fill="url(#i8jfpkc)" class="r2q-qsb2s"/><path fill="url(#iJrkSwe)" class="r2q-qsb2s"/><path fill="url(#iWFPTrc)" class="r2q-qsb2s"/><path fill="url(#iMUlzTc)" class="r2q-qsb2s"/></g><g filter="url(#iNjILNe)"><path stroke="url(#iVIh5Ub)" class="x_12rbcdb"/></g><path fill="url(#iUQcUvb)" class="qwk5x9x8p"/><g filter="url(#ikm9Jdc)"><path fill="url(#iRknpwc)" class="fg04y6bgv"/><path fill="url(#i1xoeEz)" class="fg04y6bgv"/><path fill="url(#iBYQAib)" class="fg04y6bgv"/><path fill="url(#icDwfTd)" class="fg04y6bgv"/><path fill="url(#iH2xqRb)" class="fg04y6bgv"/></g><g filter="url(#iU0GoDc)"><path class="ajrpo2--p"/></g><g filter="url(#i8c1Mce)"><path class="d999zxakv"/></g><g filter="url(#i6PMXYp)"><path class="l744lab9l"/><path fill="url(#igBChFb)" class="tj-jaj65b"/><path fill="url(#ivHJIrc)" class="tj-jaj65b"/></g><g filter="url(#iLBkT2b)"><path class="s1_97mbut"/><path fill="url(#iv0jXje)" class="wwyjhcxnm"/><path fill="url(#i84RArE)" class="wwyjhcxnm"/><path fill="url(#iJtynpe)" class="wwyjhcxnm"/></g><path class="ubuzgrbob"/><path fill="url(#ixOUu4b)" class="hbqhkwbcz"/><path class="vzunvnbry"/><g filter="url(#iDESjUb)"><path class="uvmhk0bmh"/><path fill="url(#iCLv39d)" class="lktr5qzgz"/></g><g filter="url(#iiFQBvb)"><path fill="url(#iWcBYab)" class="tajd1vkfa"/></g><path class="yf8vi24ig"/><path fill="url(#ikChBQq)" class="k_g9djn1p"/><path class="z9w-bqicw"/><g filter="url(#iS7IdYI)"><path fill="url(#iy0fwjc)" class="t0lnes_fi"/></g><g filter="url(#iYiSwQe)"><ellipse transform="rotate(-27.914 13.53 9.962)" class="kxlulv4rd"/><ellipse fill="url(#i6ApxFc)" transform="rotate(-27.914 13.53 9.962)" class="x277rabxz"/></g><path fill="url(#iy9lHFd)" class="tr05fx9rw"/><path fill="url(#iW8JzGd)" class="tr05fx9rw"/><path fill="url(#iznJTpc)" class="tr05fx9rw"/><path fill="url(#ikuTyzp)" class="tr05fx9rw"/><path fill="url(#iPrPCHb)" class="xiczs7bxi"/><path fill="url(#iJxXqMW)" class="xiczs7bxi"/><g filter="url(#inbesvG)"><path fill="url(#ipsiWed)" class="s3vt39sjx"/></g><g filter="url(#i34TgUb)"><path fill="url(#iHmHCSd)" class="h0ilfydva"/></g><g filter="url(#isOwqIo)"><path class="z04prdb0c"/></g><g filter="url(#ixDjYcc)"><path class="jibt8xb_c"/></g><g filter="url(#iMi7Mre)"><path fill="url(#ia3XjFj)" class="ppaludbau"/><path fill="url(#iBhGC3B)" class="ppaludbau"/></g><defs><radialGradient id="imwGFwb" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.054 6.913)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="idjIz7m" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.563 25.496)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="iBP5Q7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.004 4.332)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="ic7dWyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16 15.965)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="i9lcdVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.656 20.496)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iJSfG6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.72 19.091)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="iSbBxQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 26.994 28.246)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="i4yO6Qb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.458 29.795)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="i9rh6Xd" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.188 20.308)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="iEtGJYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.231 19.455)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="iC0JqRG" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.13 5.143)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="iV74exb" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.855 21.147)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iV9Lkpc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.516 20.37)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="igYt98c" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.031 16.48)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="ipuHZqe" cx="0" cy="0" r="1" gradientTransform="scale(2.05629 2.81101)rotate(90 .824 6.96)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="g67o2_phx"/><stop offset="1" class="nnb3_mk0j"/></radialGradient><radialGradient id="i7bZ66a" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.637 23.782)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="p4dnf-6nl"/><stop offset="1" class="hi3h5mb3p"/></radialGradient><radialGradient id="i10lSyb" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.779 23.501)" gradientUnits="userSpaceOnUse"><stop class="rcibyxbcc"/><stop offset="1" class="xcsexhsni"/></radialGradient><radialGradient id="iDNlp7d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.094 24.024)" gradientUnits="userSpaceOnUse"><stop class="esia20bko"/><stop offset="1" class="pycm_h7mj"/></radialGradient><radialGradient id="iuS7g7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.188 25.376)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="i0OCTfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.203 26.657)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="iEl1GYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.25 27.939)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="iDPMkib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.32 29.298)" gradientUnits="userSpaceOnUse"><stop class="pn577vz6t"/><stop offset="1" class="a1g7dradx"/></radialGradient><radialGradient id="iLuNsld" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.25 25.376)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="i4KNPmb" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.188 26.657)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="icHSFbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.094 27.939)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="iilKYUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.953 29.298)" gradientUnits="userSpaceOnUse"><stop class="djg-vfjkd"/><stop offset="1" class="jtdjejbjn"/></radialGradient><radialGradient id="iRbJhfH" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.806 20.86)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="icYayTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 9.928 12.405)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="i4NTPMe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22784 0 0 -9.248 18.792 10.974)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iVQ5h8D" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0253 -10.7865 0 16.568 4.803)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="njce4seef"/><stop offset="1" class="tuaq6yb1a"/></radialGradient><radialGradient id="i8NcWab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.431 9.66)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iUTxGhc" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 13.684 9.707)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iWdVwhe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 19.417 11.962)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iN4jRBc" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 10.517 6.649)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="ikuhVjD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 18.411 5.995)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="i8jfpkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.45 12.334)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iWFPTrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.567 11.765)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iUQcUvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 15.984 14.513)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="i1xoeEz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50132 8.85443 0 10.755 8.081)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iBYQAib" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.336 -6.21)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="icDwfTd" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.512 -1.45)scale(2.82328 2.07243)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iH2xqRb" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 15.08 1.523)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="igBChFb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20112 0 0 -.81692 16.238 3.782)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ivHJIrc" cx="0" cy="0" r="1" gradientTransform="matrix(3.21816 -5.09543 5.64521 3.5654 10.553 7.725)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iv0jXje" cx="0" cy="0" r="1" gradientTransform="matrix(3.05838 0 0 1.19577 19.398 4.559)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="i84RArE" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90405 18.618 7.596)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iJtynpe" cx="0" cy="0" r="1" gradientTransform="matrix(3.2482 .37966 -.15896 1.35996 17.732 6.12)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ixOUu4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.166 10.058)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iCLv39d" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.453 .678)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikChBQq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.802 10.058)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i6ApxFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.516 10.276)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iW8JzGd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 20.602 10.071)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iznJTpc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.962 10.616)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="ikuTyzp" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.076 10.789)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iJxXqMW" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.86 5.02)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="ipsiWed" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 11.07 10.717)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iBhGC3B" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.375 10.011)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="ihm4Dnb" x1="11.819" x2="31.261" y1="4.62" y2="22.856" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="iqdSD9Z" x1="30.063" x2="9.125" y1="13.308" y2="13.308" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="i2HGrEe" x1="13.438" x2="31.25" y1="3.561" y2="24.373" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="i28o8Pc" x1="-4.906" x2="28.906" y1="25.652" y2="25.652" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iej4Qpe" x1="3.094" x2="3.094" y1="5.215" y2="23.652" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iqjwY6c" x1="25.174" x2="25.174" y1="30.466" y2="26.649" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="i1xMH9b" x1="22.406" x2="23.219" y1="29.277" y2="29.262" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="irlsuOc" x1="7.134" x2="9.529" y1="28.159" y2="28.159" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="icqZPee" x1="18.054" x2="20.851" y1="18.386" y2="18.386" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="i7jEZbb" x1="13.944" x2="11.147" y1="18.386" y2="18.386" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iZCzgse" x1="12.109" x2="12.672" y1="16.949" y2="17.168" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="i6Z86fb" x1="21.844" x2="17.469" y1="24.808" y2="24.808" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="igcdiBc" x1="10.314" x2="10.742" y1="23.59" y2="23.59" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="i95DBnd" x1="12.863" x2="8.562" y1="28.027" y2="28.027" gradientUnits="userSpaceOnUse"><stop class="z-u-gxbip"/><stop offset=".716" class="ru_e7vq8a"/></linearGradient><linearGradient id="iIEPLJc" x1="11.063" x2="11.063" y1="30.281" y2="29.203" gradientUnits="userSpaceOnUse"><stop class="qgefhk3_g"/><stop offset="1" class="fz4o7ndqt"/></linearGradient><linearGradient id="i2UlxiW" x1="22.469" x2="18.654" y1="27.621" y2="27.621" gradientUnits="userSpaceOnUse"><stop class="tug0m0bta"/><stop offset=".807" class="t9hl_kbdf"/></linearGradient><linearGradient id="iv0n0cA" x1="10.781" x2="21.654" y1="21.965" y2="21.965" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="i7ryUsc" x1="16.401" x2="16.401" y1="21.027" y2="22.199" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="irxFwPb" x1="19.023" x2="20.852" y1="26.129" y2="26.129" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="i13Eudd" x1="12.932" x2="10.734" y1="26.129" y2="26.129" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="iiuqItd" x1="19.023" x2="20.852" y1="27.394" y2="27.394" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="iX0Z5Ab" x1="12.932" x2="10.734" y1="27.394" y2="27.394" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="ioKkHod" x1="19.023" x2="20.852" y1="28.66" y2="28.66" gradientUnits="userSpaceOnUse"><stop class="e_ivvgb2p"/><stop offset="1" class="ccj4ms20h"/></linearGradient><linearGradient id="iwrRUPe" x1="12.932" x2="10.734" y1="28.66" y2="28.66" gradientUnits="userSpaceOnUse"><stop class="xiz-7cblr"/><stop offset="1" class="n1yz-o_0e"/><stop offset="1" class="d33s3sdpm"/></linearGradient><linearGradient id="igRrQQc" x1="21.142" x2="16.789" y1="12.659" y2="12.659" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iEuZ1Cd" x1="16.822" x2="15.984" y1="11.649" y2="11.683" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iJrkSwe" x1="15.984" x2="15.984" y1="12.788" y2="12.323" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iMUlzTc" x1="15.984" x2="15.984" y1="9.954" y2="10.629" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="iVIh5Ub" x1="14.782" x2="15.101" y1="14.359" y2="13.524" gradientUnits="userSpaceOnUse"><stop class="jj-rw_lkt"/><stop offset="1" class="hngfrubmu"/></linearGradient><linearGradient id="iRknpwc" x1="22.836" x2="11.224" y1="5.311" y2="5.311" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iWcBYab" x1="18.944" x2="18.631" y1="10.111" y2="10.305" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iy0fwjc" x1="14.546" x2="14.232" y1="10.111" y2="10.305" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iy9lHFd" x1="22.421" x2="21.214" y1="10.138" y2="12.315" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iPrPCHb" x1="10.134" x2="11.593" y1="10.842" y2="10.715" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iHmHCSd" x1="21.463" x2="21.463" y1="9.767" y2="11.671" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="ia3XjFj" x1="16.08" x2="16.08" y1="8.907" y2="12.689" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient><filter id="ilIH5zb" width="27.98" height="21.09" x="2.004" y="4.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="igrYVre" width="27.413" height="20.785" x="2.669" y="3.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".2"/></filter><filter id="iU59dJe" width="27.91" height="20.96" x="2.004" y="4.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="iJHWiTm" width="2.797" height="14.04" x="18.054" y="15.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="i2cfBqd" width="2.797" height="14.04" x="11.147" y="15.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="iChouWd" width="2.1" height="3.39" x="20.948" y="23.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.803922 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="iWO2YAe" width="2.1" height="3.29" x="8.951" y="23.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.670588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="iCqVgHd" width="4.793" height="5.391" x="8.951" y="24.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.670588 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="iMSnIXb" width="4.793" height="5.591" x="18.454" y="24.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.490196 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.796078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1667" result="effect2_innerShadow_4002_1667"/></filter><filter id="iOmTR0b" width="2.222" height=".3" x="18.873" y="25.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="iBPzzjd" width="2.222" height=".3" x="10.861" y="25.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="ibdKRrb" width="2.222" height=".3" x="18.873" y="27.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="i0Xa2Ga" width="2.222" height=".3" x="10.861" y="27.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="iVrJmEb" width="2.222" height=".3" x="18.873" y="28.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="i3oUUvb" width="2.222" height=".3" x="10.861" y="28.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="iJ7xhLe" width="11.22" height="12.542" x="10.921" y="4.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1667" result="effect2_innerShadow_4002_1667"/></filter><filter id="ieR7vBh" width="3.747" height="4.9" x="13.969" y="9.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".5"/></filter><filter id="iIIqJvb" width="2.277" height="3.3" x="14.845" y="9.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".1"/></filter><filter id="iNjILNe" width="3.718" height="1.573" x="14.125" y="13.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="ikm9Jdc" width="12.873" height="8.356" x="9.548" y="1.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1667" result="effect2_innerShadow_4002_1667"/></filter><filter id="iU0GoDc" width="2.339" height="1.19" x="17.573" y="7.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="i8c1Mce" width="2.339" height="1.176" x="12.317" y="7.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/></filter><filter id="i6PMXYp" width="6.734" height="5.992" x="9.903" y="2.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/><feGaussianBlur result="effect2_foregroundBlur_4002_1667" stdDeviation=".125"/></filter><filter id="iLBkT2b" width="6.361" height="5.736" x="15.825" y="3.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".125"/></filter><filter id="iDESjUb" width=".787" height=".696" x="17.432" y="9.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="iiFQBvb" width=".891" height=".913" x="18.272" y="9.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".1"/></filter><filter id="iS7IdYI" width=".986" height="1.04" x="13.829" y="9.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".1"/></filter><filter id="iYiSwQe" width=".913" height=".705" x="13.074" y="9.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".05"/></filter><filter id="inbesvG" width="1.329" height="2.379" x="9.903" y="9.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".125"/></filter><filter id="i34TgUb" width="1.947" height="2.903" x="20.49" y="9.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".25"/></filter><filter id="isOwqIo" width="2.405" height="1.16" x="12.236" y="7.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".125"/></filter><filter id="ixDjYcc" width="2.405" height="1.16" x="17.515" y="7.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1667" stdDeviation=".125"/></filter><filter id="iMi7Mre" width="10.29" height="4.16" x="10.884" y="8.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1667"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1667" result="effect2_innerShadow_4002_1667"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:teacher-light" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a1g7dradx {
  stop-color: var(--svg-color--f2c6bb, #F2C6BB);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.agmbz-z1k {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.583 10.45l-.591 1.838c-.101.378.141.757.484.757h.732c.343 0 .585-.384.485-.757l-.495-1.838c-.106-.407-.504-.407-.615 0");
}

.ajrpo2--p {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.717 7.994a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 0 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
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

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ccj4ms20h {
  stop-color: var(--svg-color--b6736c, #B6736C);
  stop-opacity: 0;
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d33s3sdpm {
  stop-color: var(--svg-color--e4af9d, #E4AF9D);
  stop-opacity: 0;
}

.d999zxakv {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.573 7.885a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.dbqapzqvh {
  d: path("M11.147 21.504c0-.384.312-.696.696-.696h9.811V22.2h-9.811a.695.695 0 0 1-.696-.695");
}

.djg-vfjkd {
  stop-color: var(--svg-color--ffd6c4, #FFD6C4);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e_ivvgb2p {
  stop-color: var(--svg-color--b6736c, #B6736C);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.ekekh-b5z {
  d: path("M18.655 25.38a.81.81 0 0 0 .302.668a.8.8 0 0 0-.302.637c0 .267.115.503.302.636a.8.8 0 0 0-.302.637c0 .267.115.503.302.637a.84.84 0 0 0-.302.667c.009.42.32.75.684.75h2.935c.427 0 .774-.401.774-.894v-3.604c0-.493-.347-.893-.774-.893h-2.842c-.475 0-.77.39-.777.76");
}

.eqlr_ly_k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 28.582h-1.921");
}

.esia20bko {
  stop-color: var(--svg-color--b88165, #B88165);
}

.etmel4bjk {
  d: path("M10.314 21.892v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f-7_jnw-j {
  d: path("M13.344 25.38a.81.81 0 0 1-.303.668a.8.8 0 0 1 .303.637a.77.77 0 0 1-.303.636a.8.8 0 0 1 .303.637a.77.77 0 0 1-.303.637c.187.143.303.39.303.667c-.01.42-.32.75-.685.75H9.724c-.427 0-.773-.401-.773-.894v-3.604c0-.493.346-.893.773-.893h2.842c.475 0 .77.39.778.76");
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fg04y6bgv {
  d: path("M20.839 4.33a2.33 2.33 0 0 1 1.268 1.052A2.37 2.37 0 0 1 22 7.908a1.56 1.56 0 0 0-.27.875V9.97a1.7 1.7 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.383-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.844 0 1.581.456 1.99 1.132c.307.51.79.88 1.352 1.073");
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fos-u_bfq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 27.316h1.922");
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.fz4o7ndqt {
  stop-color: var(--svg-color--c38792, #C38792);
  stop-opacity: 0;
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g67o2_phx {
  stop-color: var(--svg-color--a87366, #A87366);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gey85t6-q {
  d: path("M19.344 16.072L20.704 19c.09.19-.05.41-.26.41l-.963-.265c-.422-.106-.437.276-.277.436l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87v-13.94z");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gprnkk-tp {
  d: path("M12.654 16.072L11.294 19c-.09.19.05.41.26.41l.964-.265c.422-.106.436.276.276.436l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87v-13.94z");
}

.h0ilfydva {
  d: path("M20.99 11.67q.058-.95.11-1.903a.956.956 0 0 1-.11 1.904");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hacus_bfw {
  fill-rule: evenodd;
  d: path("M12.408 30.012v-8.407h-2.094v8.407z");
}

.hbqhkwbcz {
  d: path("M18.168 9.58a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.hi3h5mb3p {
  stop-color: var(--svg-color--dda88b, #DDA88B);
}

.hngfrubmu {
  stop-color: var(--svg-color--ecbcae, #ECBCAE);
  stop-opacity: 0;
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.i1vg8bb9g {
  d: path("M16.004 15.512c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iegvepiks {
  d: path("M11.123 12.224a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.341 2.019a4.1 4.1 0 0 1-.346-1.18z");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.iu8-hccbx {
  d: path("M11.16 13.739a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.885-3.406c.118-1.884.237-3.76.325-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.34 1.513-3.34 3.38c0 1.86.115 3.69.237 5.556");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jibt8xb_c {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.545 8.119c-.257-.185-.897-.509-1.655-.382");
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jj-rw_lkt {
  stop-color: var(--svg-color--ecbcae, #ECBCAE);
}

.jkgpjaces {
  d: path("M22.048 23.12c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jtdjejbjn {
  stop-color: var(--svg-color--ffd6c4, #FFD6C4);
  stop-opacity: 0;
}

.k_g9djn1p {
  d: path("M13.8 9.58a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k-m4isb6w {
  d: path("M29.374 25.002H2.624c-.34 0-.62-.28-.62-.62V4.631c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.knignw1ns {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 28.582h1.922");
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kxlulv4rd {
  cx: 13.531px;
  cy: 9.962px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.kyahc60lg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 26.05h1.922");
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l744lab9l {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.217 5.358l-.066-.137a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.lj8q10b_x {
  d: path("M22.674 30.012V17.767a10.98 10.98 0 0 1 4.32 8.745v3.5z");
}

.lktr5qzgz {
  d: path("M18.103 9.77c.063.084-.07.188-.22.3c-.152.114-.264.193-.328.108c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.m52qiab0d {
  d: path("M18.054 16.832h-4.11v13.18h4.11z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n1yz-o_0e {
  stop-color: var(--svg-color--d29c80, #D29C80);
  stop-opacity: 0;
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.njce4seef {
  stop-color: var(--svg-color--bc847a, #BC847A);
  stop-opacity: 0;
}

.nnb3_mk0j {
  stop-color: var(--svg-color--875841, #875841);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.ny7bx-bsc {
  d: path("M9.294 30.012V17.767a10.98 10.98 0 0 0-4.32 8.745v3.5z");
}

.o-cmqab0a {
  d: path("M16.004 18.682c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p4dnf-6nl {
  stop-color: var(--svg-color--e9bda6, #E9BDA6);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn577vz6t {
  stop-color: var(--svg-color--f2c6bb, #F2C6BB);
}

.ppaludbau {
  d: path("M20.834 8.501h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.pycm_h7mj {
  stop-color: var(--svg-color--cd9a86, #CD9A86);
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qf_uz6njq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 26.05h-1.921");
}

.qgefhk3_g {
  stop-color: var(--svg-color--c38792, #C38792);
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwk5x9x8p {
  d: path("M15.984 13.87c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.085-.198.209c.335.508.918.846 1.583.846s1.249-.338 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.r2q-qsb2s {
  d: path("m15.602 10.259l-.532 1.838c-.108.379.152.757.521.757h.786c.37 0 .63-.384.521-.757l-.532-1.838c-.113-.407-.645-.407-.764 0");
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rcibyxbcc {
  stop-color: var(--svg-color--fcd2bc, #FCD2BC);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rksxibbzh {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.408 30.012v-8.407h-2.094v8.407z");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ru_e7vq8a {
  stop-color: var(--svg-color--d4a093, #D4A093);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s1_97mbut {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.197 8.625l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.52 4.154");
}

.s3vt39sjx {
  d: path("M10.899 9.775a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0lnes_fi {
  d: path("M14.616 10.368c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t28omabpg {
  d: path("M20.845 12.224a1.64 1.64 0 0 0 .905-.309v.931c0 .893-.532 1.689-1.34 2.019q.256-.546.345-1.18z");
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t9hl_kbdf {
  stop-color: var(--svg-color--d19890, #D19890);
}

.tajd1vkfa {
  d: path("M18.963 10.356a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.tgdtlzb0v {
  d: path("M9.95 23.112c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.tj-jaj65b {
  d: path("m16.217 5.358l-.066-.137a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.tr05fx9rw {
  d: path("M20.906 12.315q.1-1.596.185-3.192a1.61 1.61 0 0 1-.185 3.192");
}

.tuaq6yb1a {
  stop-color: var(--svg-color--a36f64, #A36F64);
}

.tug0m0bta {
  stop-color: var(--svg-color--ffd7c3, #FFD7C3);
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ubuzgrbob {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.375 9.309c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uvmhk0bmh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.103 9.77c.063.084-.07.188-.22.3c-.152.114-.264.193-.328.108c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vj9zlebew {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.219 4.405H29.43a.1.1 0 0 1 .1.1V24.09");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vzunvnbry {
  fill: var(--svg-color--000, #000);
  d: path("M17.657 10.473c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wchtn57td {
  d: path("M21.654 22.996V20.71c0-.388-.36-.698-.81-.698h-8.658c-1.042 0-1.872.73-1.872 1.621c0 .753.61 1.363 1.363 1.363z");
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wwyjhcxnm {
  d: path("m21.197 8.625l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.973.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.52 4.154");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x_12rbcdb {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.633 13.475a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.001c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.352-.32Z");
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x277rabxz {
  cx: 13.531px;
  cy: 9.962px;
  rx: 0.39px;
  ry: 0.197px;
}

.xb6dt1xvv {
  d: path("M28.994 24.002H3.004V5.012l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.xcsexhsni {
  stop-color: var(--svg-color--fcd2bc, #FCD2BC);
  stop-opacity: 0;
}

.xiczs7bxi {
  d: path("M10.94 9.115a1.62 1.62 0 0 0-1.392 1.593c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.2");
}

.xiz-7cblr {
  stop-color: var(--svg-color--e4af9d, #E4AF9D);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.yf8vi24ig {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.593 9.309c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yuu8kcc_x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 27.316h-1.921");
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z-u-gxbip {
  stop-color: var(--svg-color--eab9ad, #EAB9AD);
}

.z04prdb0c {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.61 8.165c.258-.185.898-.509 1.656-.381");
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z9w-bqicw {
  fill: var(--svg-color--000, #000);
  d: path("M14.311 10.473a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.zdw3afb3i {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.602 10.259l-.532 1.838c-.108.379.152.757.521.757h.786c.37 0 .63-.384.521-.757l-.532-1.838c-.113-.407-.645-.407-.764 0");
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zmw1qtb_r {
  d: path("M3.004 24.002V5.012h25.99v18.99z");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
