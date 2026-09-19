<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iiFEcXb)" clip-rule="evenodd" class="tv41nebaf"/><path fill="url(#iALeSad)" clip-rule="evenodd" class="t2uxtx_ya"/><g filter="url(#iLgGAJe)"><path fill="url(#i6ucWWc)" class="ufs3b81ci"/><path fill="url(#iCwdjPc)" class="ufs3b81ci"/></g><path fill="url(#iqgHXuc)" class="j_m47xbqb"/><path fill="url(#iVs0ptc)" class="j_m47xbqb"/><g filter="url(#iqZiDTd)"><path class="t-_6tzcpa"/></g><path fill="url(#iqNjaEc)" class="g4-rnpbiv"/><path fill="url(#iThywBd)" class="g4-rnpbiv"/><path fill="url(#idfxACe)" class="qxv17obmu"/><path fill="url(#isUbT6b)" class="qxv17obmu"/><path fill="url(#iBWuPqc)" class="qxv17obmu"/><path fill="url(#iLbr7Sb)" class="qhpil-b3e"/><path fill="url(#iTnTIGe)" class="qhpil-b3e"/><path fill="url(#iC9Y0Gc)" class="qhpil-b3e"/><path class="fpvljrbim"/><path fill="url(#ibEjBCd)" class="s386_46_x"/><path fill="url(#ibzhVWd)" class="s386_46_x"/><path fill="url(#iS46Coe)" class="s386_46_x"/><g filter="url(#ig32sbA)"><path class="i9cgj7g1s"/><path fill="url(#i1QOigd)" class="vcvz10bee"/><path fill="url(#ivUZRZQ)" class="vcvz10bee"/><path fill="url(#iNTvdNe)" class="vcvz10bee"/></g><g filter="url(#iDxpXmb)"><path fill="url(#itRDtdd)" class="ufa4e1bue"/></g><path fill="url(#iaHeeWc)" class="wtx0-zb9b"/><path fill="url(#iLUYhsd)" class="wtx0-zb9b"/><g filter="url(#iBVvJ7d)"><path fill="url(#irc1RSb)" class="e72vc5glc"/><path fill="url(#iRGWRhb)" class="e72vc5glc"/></g><path fill="url(#iXZL3iU)" class="e72vc5glc"/><path clip-rule="evenodd" class="ttit7sbwx"/><path fill="url(#i78Qyac)" clip-rule="evenodd" class="x81pqcclg"/><path clip-rule="evenodd" class="vat8zbb1h"/><path fill="url(#iyFuXyd)" clip-rule="evenodd" class="tej0dgbcx"/><path clip-rule="evenodd" class="z2_7lnp1p"/><path fill="url(#ibHJEZc)" clip-rule="evenodd" class="au2cdjbqa"/><path clip-rule="evenodd" class="hikihhbgc"/><path fill="url(#i7bcDzd)" clip-rule="evenodd" class="j873t3pix"/><path clip-rule="evenodd" class="njoad_bkl"/><path fill="url(#i595LEd)" clip-rule="evenodd" class="qb45jbc1d"/><path clip-rule="evenodd" class="rv50jfbso"/><path fill="url(#ie4bhgh)" clip-rule="evenodd" class="a57epkiey"/><path clip-rule="evenodd" class="dzzs3_bwg"/><path fill="url(#irOah5X)" clip-rule="evenodd" class="onaimccwi"/><g filter="url(#iIesiOc)"><path class="s4y_htbex"/></g><g filter="url(#iMdgLMI)"><path class="fn3z_sbxx"/></g><g filter="url(#i1TLWBQ)"><path class="y8dgjevrz"/></g><g filter="url(#iAKssBd)"><path class="mkk0k-byc"/></g><g filter="url(#iix8M2t)"><path class="znfzn6b4i"/></g><g filter="url(#iRPmpFV)"><path class="rm-es7b9q"/></g><g filter="url(#iwaq1jc)"><path class="w0_6atbzj"/></g><g filter="url(#igglkrw)"><path class="p5j2ywblw"/></g><path fill="url(#ipaLKtW)" class="y8h5-ibcw"/><path fill="url(#iANea9P)" class="pa78cvbvm"/><g filter="url(#iZXAYYc)"><path fill="url(#ivky8ad)" class="emeocgbpj"/></g><path fill="url(#io3GUPo)" class="emeocgbpj"/><path fill="url(#iQfxGrd)" class="emeocgbpj"/><path fill="url(#iaZrSXN)" class="emeocgbpj"/><path fill="url(#i4OEl3C)" class="emeocgbpj"/><path fill="url(#ixEGlFe)" class="emeocgbpj"/><path fill="url(#iLPk8pd)" class="emeocgbpj"/><path fill="url(#iCtUOpc)" class="emeocgbpj"/><path fill="url(#iAzEJdd)" class="emeocgbpj"/><path fill="url(#iOGPfid)" class="emeocgbpj"/><g filter="url(#iRXhLEb)"><path class="xbk_ospgb"/></g><g filter="url(#iYjGioc)"><path class="pkq92ktmj"/><path fill="url(#iei33nY)" class="i6inoib7r"/><path fill="url(#iiSkxgd)" class="i6inoib7r"/><path fill="url(#i93rOcM)" class="i6inoib7r"/><path fill="url(#iIjwOdd)" class="i6inoib7r"/><path fill="url(#i9VwJjc)" class="i6inoib7r"/></g><g filter="url(#iLsuobe)"><path stroke="url(#ix641oc)" class="wjiz1pa3n"/></g><path fill="url(#intEfrX)" class="c1w6ajyam"/><g filter="url(#iHuoazc)"><path fill="url(#iPpI0Je)" class="xxeo3cl2n"/><path fill="url(#iQwRBmc)" class="xxeo3cl2n"/><path fill="url(#iwI0onc)" class="xxeo3cl2n"/><path fill="url(#iJJjIzc)" class="xxeo3cl2n"/><path fill="url(#iEgw9Md)" class="xxeo3cl2n"/></g><g filter="url(#idL6ADe)"><path class="z2zeoomhh"/></g><g filter="url(#i3TQ09c)"><path class="i70ybeqwy"/></g><g filter="url(#io3643b)"><path class="e6hpzy_el"/><path fill="url(#iD1Pieu)" class="cf2tclj6v"/><path fill="url(#igIgOYc)" class="cf2tclj6v"/></g><g filter="url(#iESfGqd)"><path class="twl0g-bsl"/><path fill="url(#iHTMbLe)" class="g8rhdpbdt"/></g><path fill="url(#iCTUHCd)" class="i1pdukfxy"/><path fill="url(#iSK8eFc)" class="i1pdukfxy"/><path fill="url(#ijyGKNd)" class="i1pdukfxy"/><path fill="url(#iSyy7Xb)" class="i1pdukfxy"/><path fill="url(#iUm0Skd)" class="xbeiecc_v"/><path fill="url(#i9FXtdd)" class="xbeiecc_v"/><g filter="url(#iyNbxfb)"><path fill="url(#iY1HoLd)" class="gvi5igtdh"/></g><g filter="url(#ithXMoc)"><path fill="url(#iPINHMp)" class="y3ixjxb0y"/></g><g filter="url(#iqzZobC)"><path class="i1mpky9sl"/></g><g filter="url(#ixKXE9J)"><path class="a3qlmcb4m"/></g><g filter="url(#iTLSFKe)"><path class="uesodzbqv"/></g><path class="hss_x8b0z"/><g filter="url(#i6gQAWc)"><path class="wd5n0p1ub"/></g><path class="iap9bjb7s"/><g filter="url(#iqbzLqb)"><path class="b2v39zblc"/></g><defs><radialGradient id="iiFEcXb" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.438 13.206)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="fznz2mbxx"/><stop offset="1" class="hnjuf644p"/></radialGradient><radialGradient id="iALeSad" cx="0" cy="0" r="1" gradientTransform="matrix(.23438 .67187 -1.35614 .47307 26.835 22.69)" gradientUnits="userSpaceOnUse"><stop class="fznz2mbxx"/><stop offset="1" class="hnjuf644p"/></radialGradient><radialGradient id="i6ucWWc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.424)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="zhfkvgbxb"/><stop offset="1" class="uq-h9hb8w"/></radialGradient><radialGradient id="iCwdjPc" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -7.058 31.738)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="u24mgdcov"/><stop offset="1" class="rwyr8xb2b"/></radialGradient><radialGradient id="iqgHXuc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.768)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="hfnjpubec"/><stop offset="1" class="t0fy-bbwc"/></radialGradient><radialGradient id="iVs0ptc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.409)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="k-fq99sbh"/><stop offset="1" class="phf6igbvb"/></radialGradient><radialGradient id="iqNjaEc" cx="0" cy="0" r="1" gradientTransform="rotate(165.069 8.953 14.565)scale(1.45539 2.44377)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="mwtukgbbz"/><stop offset="1" class="fozz65l2p"/></radialGradient><radialGradient id="iThywBd" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 -1.5 3.43224 4.2188 6.044 26.706)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="lg8towb3y"/><stop offset="1" class="pdvw2hfdl"/></radialGradient><radialGradient id="idfxACe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.33)" gradientUnits="userSpaceOnUse"><stop class="us72pebsg"/><stop offset="1" class="hx5ihzb7y"/></radialGradient><radialGradient id="iLbr7Sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="uwa_e26-a"/><stop offset="1" class="hx5ihzb7y"/></radialGradient><radialGradient id="ibzhVWd" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.158 23.732)" gradientUnits="userSpaceOnUse"><stop class="w-l5r38ro"/><stop offset="1" class="lehanccnj"/></radialGradient><radialGradient id="iS46Coe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20.237)" gradientUnits="userSpaceOnUse"><stop class="pc6ft5bqj"/><stop offset="1" class="crrluq_8b"/></radialGradient><radialGradient id="ivUZRZQ" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.277 7.65)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="uo439xb-e"/><stop offset="1" class="wsizjkbjw"/></radialGradient><radialGradient id="iNTvdNe" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.33)" gradientUnits="userSpaceOnUse"><stop class="ept1d-nvv"/><stop offset="1" class="iu4sfzbng"/></radialGradient><radialGradient id="itRDtdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.33)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="iaHeeWc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.125 2.517)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="pk5i2pb0j"/><stop offset="1" class="d-f_cevwl"/></radialGradient><radialGradient id="iLUYhsd" cx="0" cy="0" r="1" gradientTransform="rotate(108.939 3.647 10.356)scale(3.36993 3.80066)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="rsji3yblh"/><stop offset="1" class="ddt4h9ktn"/></radialGradient><radialGradient id="irc1RSb" cx="0" cy="0" r="1" gradientTransform="rotate(86.442 1.652 16.17)scale(8.05726 7.74996)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="ydcxvabaw"/><stop offset="1" class="hekp_gbnf"/></radialGradient><radialGradient id="iRGWRhb" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.536 10.87)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="ksocwfbza"/><stop offset="1" class="ecaf6kbqo"/></radialGradient><radialGradient id="iXZL3iU" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 12.05)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="bmu4g5dxl"/><stop offset="1" class="z321yabtz"/></radialGradient><radialGradient id="i78Qyac" cx="0" cy="0" r="1" gradientTransform="matrix(.04721 .75606 -4.208 .26278 4.575 23.17)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="iyFuXyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0472 .75606 -4.20801 -.26276 27.424 23.17)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="ibHJEZc" cx="0" cy="0" r="1" gradientTransform="matrix(.05288 .98594 -4.7173 .25299 4.591 23.76)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="i7bcDzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05288 .98594 -4.7173 -.25299 27.409 23.76)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="i595LEd" cx="0" cy="0" r="1" gradientTransform="matrix(.00011 .90392 -3.36918 .00041 5.113 24.51)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="ie4bhgh" cx="0" cy="0" r="1" gradientTransform="matrix(-.00011 .90392 -3.36917 -.00041 26.887 24.51)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="ipaLKtW" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 3.666 17.708)scale(1.34834 1.60173)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iANea9P" cx="0" cy="0" r="1" gradientTransform="matrix(.92428 .29048 -.89616 2.85146 12.228 8.421)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="ivky8ad" cx="0" cy="0" r="1" gradientTransform="matrix(-3.27268 0 0 -5.78933 17.777 7.525)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iQfxGrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.63995 7.7772 -6.44046 -.52996 17.01 3.823)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iaZrSXN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.71888 .88961 0 17.551 6.703)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="i4OEl3C" cx="0" cy="0" r="1" gradientTransform="matrix(.00246 -.68503 .74548 .00268 14.58 6.732)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="ixEGlFe" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.956 4.358)scale(5.32914 13.6133)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iLPk8pd" cx="0" cy="0" r="1" gradientTransform="matrix(2.54973 -1.65785 .60689 .93338 12.597 4.818)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iCtUOpc" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.15 11.722)scale(1.5703 .62772)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iAzEJdd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09123 1.80475 -1.48997 -.9009 17.539 4.408)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iiSkxgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .15281 -.48026 0 16.312 8.377)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iIjwOdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.95225 .4366 -.70165 -1.53034 16.384 8.02)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="intEfrX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.45119 1.81524 0 16.02 9.74)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iQwRBmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.19186 5.54295 0 12.746 5.715)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iwI0onc" cx="0" cy="0" r="1" gradientTransform="matrix(.0714 -1.57287 2.78682 .12649 19.062 6.535)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iJJjIzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47665 -.9712 .7129 -1.08393 18.59 2.606)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iEgw9Md" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.289 14.61)scale(1.08334 2.50852)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iD1Pieu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37792 0 0 -.5114 16.178 3.023)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="igIgOYc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 11.291 -8.702)scale(3.77271 4.17978)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iHTMbLe" cx="0" cy="0" r="1" gradientTransform="matrix(2.0334 .23767 -.0995 .85135 17.114 4.487)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iSK8eFc" cx="0" cy="0" r="1" gradientTransform="matrix(.39348 1.4043 -1.33982 .3754 18.91 6.96)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="ijyGKNd" cx="0" cy="0" r="1" gradientTransform="matrix(.49316 -.67678 .56727 .41336 19.136 7.301)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iSyy7Xb" cx="0" cy="0" r="1" gradientTransform="matrix(.36746 -.97058 1.29683 .49098 19.207 7.41)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="i9FXtdd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 3.463 8.754)scale(1.32506 1.30265)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iY1HoLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57372 .09848 -.04344 -.25304 12.943 7.363)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="iLgGAJe" width="9.729" height="6.156" x="17.627" y="22.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.184314 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.156863 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23985" result="effect2_innerShadow_3987_23985"/></filter><filter id="iqZiDTd" width="17.213" height="7.995" x="5.751" y="22.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23985" result="effect2_innerShadow_3987_23985"/></filter><filter id="ig32sbA" width="7.621" height="12.797" x="19.836" y="12.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0666667 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/></filter><filter id="iDxpXmb" width="8.502" height="3.19" x="11.869" y="21.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/></filter><filter id="iBVvJ7d" width="8.289" height="10.271" x="11.888" y="11.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.423529 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/></filter><filter id="iIesiOc" width="1.684" height="1.255" x="5.351" y="24.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".075"/></filter><filter id="iMdgLMI" width="1.684" height="1.255" x="24.965" y="24.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".075"/></filter><filter id="i1TLWBQ" width="2.04" height="1.095" x="4.237" y="24.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".075"/></filter><filter id="iAKssBd" width="2.04" height="1.095" x="25.723" y="24.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".075"/></filter><filter id="iix8M2t" width="2.223" height=".888" x="3.593" y="23.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".075"/></filter><filter id="iRPmpFV" width="2.223" height=".888" x="26.184" y="23.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".075"/></filter><filter id="iwaq1jc" width="2.031" height=".566" x="3.653" y="23.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".075"/></filter><filter id="igglkrw" width="2.031" height=".566" x="26.317" y="23.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".075"/></filter><filter id="iZXAYYc" width="7.398" height="7.926" x="12.85" y="3.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23985" result="effect2_innerShadow_3987_23985"/></filter><filter id="iRXhLEb" width="3.093" height="3.815" x="14.384" y="6.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".5"/></filter><filter id="iYjGioc" width="1.375" height="2.015" x="15.332" y="6.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".05"/></filter><filter id="iLsuobe" width="2.515" height="1.172" x="14.762" y="8.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".05"/></filter><filter id="iHuoazc" width="8.058" height="5.418" x="11.99" y="1.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23985" result="effect2_innerShadow_3987_23985"/></filter><filter id="idL6ADe" width="1.502" height=".82" x="17.015" y="5.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/></filter><filter id="i3TQ09c" width="1.502" height=".811" x="13.724" y="5.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/></filter><filter id="io3643b" width="4.459" height="3.933" x="12.119" y="2.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/><feGaussianBlur result="effect2_foregroundBlur_3987_23985" stdDeviation=".125"/></filter><filter id="iESfGqd" width="4.067" height="3.724" x="15.929" y="2.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23985"/><feGaussianBlur result="effect2_foregroundBlur_3987_23985" stdDeviation=".125"/></filter><filter id="iyNbxfb" width="1.019" height="1.676" x="12.119" y="6.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".125"/></filter><filter id="ithXMoc" width="1.593" height="2.192" x="18.614" y="6.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".25"/></filter><filter id="iqzZobC" width="1.786" height="1.007" x="13.533" y="5.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".125"/></filter><filter id="ixKXE9J" width="1.786" height="1.007" x="16.837" y="5.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".125"/></filter><filter id="iTLSFKe" width="3.857" height="2.442" x="16.29" y="2.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".375"/></filter><filter id="i6gQAWc" width="1.628" height=".644" x="13.82" y="6.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".05"/></filter><filter id="iqbzLqb" width="1.628" height=".644" x="16.609" y="6.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23985" stdDeviation=".05"/></filter><linearGradient id="isUbT6b" x1="21.525" x2="21.525" y1="21.268" y2="22.424" gradientUnits="userSpaceOnUse"><stop class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iBWuPqc" x1="18.658" x2="19.892" y1="24.552" y2="24.956" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iTnTIGe" x1="10.822" x2="10.822" y1="21.268" y2="22.424" gradientUnits="userSpaceOnUse"><stop class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iC9Y0Gc" x1="13.689" x2="12.455" y1="24.552" y2="24.956" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="ibEjBCd" x1="12.24" x2="10.033" y1="20.873" y2="20.683" gradientUnits="userSpaceOnUse"><stop offset=".184" class="w3geznflg"/><stop offset="1" class="o-0p8ab1g"/></linearGradient><linearGradient id="i1QOigd" x1="19.835" x2="22.042" y1="20.873" y2="20.683" gradientUnits="userSpaceOnUse"><stop offset=".184" class="e5bi16n_y"/><stop offset="1" class="n9h2xzfye"/></linearGradient><linearGradient id="irOah5X" x1="26.513" x2="24.888" y1="25.44" y2="24.177" gradientUnits="userSpaceOnUse"><stop offset=".455" class="fznz2mbxx"/><stop offset="1" class="b04py3bjk"/></linearGradient><linearGradient id="io3GUPo" x1="19.248" x2="16.523" y1="8.58" y2="8.58" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iOGPfid" x1="16.049" x2="16.049" y1="11.439" y2="11.038" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iei33nY" x1="16.544" x2="16.02" y1="7.948" y2="7.969" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="i93rOcM" x1="16.02" x2="16.02" y1="8.661" y2="8.37" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="i9VwJjc" x1="16.02" x2="16.02" y1="6.811" y2="7.31" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="ix641oc" x1="15.267" x2="15.467" y1="9.644" y2="9.122" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iPpI0Je" x1="20.309" x2="13.04" y1="3.98" y2="3.98" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iCTUHCd" x1="20.049" x2="19.293" y1="7.002" y2="8.365" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iUm0Skd" x1="12.357" x2="13.27" y1="7.443" y2="7.363" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iPINHMp" x1="19.41" x2="19.41" y1="6.763" y2="7.955" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-lotus-position-dark" /></template>
<style>
.a3qlmcb4m {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.249 5.738a1.45 1.45 0 0 0-1.037-.239");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a57epkiey {
  fill-rule: evenodd;
  d: path("M25.902 24.184a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.113l.037.003a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.053-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.au2cdjbqa {
  fill-rule: evenodd;
  d: path("M5.825 23.762a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8c.226 0 .852-.06 1.466-.364a.4.4 0 0 1 .537.18");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b04py3bjk {
  stop-color: var(--svg-color--301f1d, #301F1D);
}

.b2v39zblc {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.01a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bmu4g5dxl {
  stop-color: var(--svg-color--c56d32, #C56D32);
}

.c1w6ajyam {
  d: path("M16.02 9.339c-.318 0-.617-.075-.868-.206c-.086-.044-.178.053-.124.13c.21.318.575.53.992.53c.416 0 .781-.212.99-.53c.055-.08-.037-.174-.123-.13c-.251.13-.547.206-.867.206");
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
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

.cf2tclj6v {
  d: path("m16.165 4.01l-.042-.086a.42.42 0 0 0-.385-.262h-.797a2.103 2.103 0 0 0-2.091 2.116v.172c-.213-.162-.48-.504-.48-1.057c0-.67.489-1.01.8-1.226c.089-.061.163-.113.208-.159l.062-.065c.219-.232.609-.646 1.29-.827c.217-.058.437-.087.64-.098c.472-.027.808.384.808.857v.626z");
}

.crrluq_8b {
  stop-color: var(--svg-color--2b0c0a, #2B0C0A);
  stop-opacity: 0;
}

.d-f_cevwl {
  stop-color: var(--svg-color--4a3532, #4A3532);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.ddt4h9ktn {
  stop-color: var(--svg-color--432e2c, #432E2C);
  stop-opacity: 0;
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dzzs3_bwg {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M6.818 24.409c.14.17.272.303.101.443c-.565.464-.934.651-1.193.783l-.072.037a.4.4 0 1 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.e5bi16n_y {
  stop-color: var(--svg-color--2f0c0a, #2F0C0A);
}

.e6hpzy_el {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.165 4.01l-.042-.086a.42.42 0 0 0-.385-.262h-.797a2.103 2.103 0 0 0-2.091 2.116v.172c-.213-.162-.48-.504-.48-1.057c0-.67.489-1.01.8-1.226c.089-.061.163-.113.208-.159l.062-.065c.219-.232.609-.646 1.29-.827c.217-.058.437-.087.64-.098c.472-.027.808.384.808.857v.626z");
}

.e72vc5glc {
  d: path("M18.892 11.39v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.56-1.285-.894");
}

.ecaf6kbqo {
  stop-color: var(--svg-color--cc3a05, #CC3A05);
}

.emeocgbpj {
  d: path("M12.999 9.256a2.45 2.45 0 0 0 2.432 2.132h1.181c1.232 0 2.272-.91 2.433-2.132c.074-1.18.148-2.354.203-3.532a.907.907 0 0 0-.864-.897h-.876a1.52 1.52 0 0 1-1.385-.903a.42.42 0 0 0-.385-.262h-.797a2.103 2.103 0 0 0-2.091 2.116c0 1.164.072 2.31.149 3.478");
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ept1d-nvv {
  stop-color: var(--svg-color--655351, #655351);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fn3z_sbxx {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.291c-.25-.145-.847-.51-1.234-.804");
}

.fozz65l2p {
  stop-color: var(--svg-color--625250, #625250);
  stop-opacity: 0;
}

.fpvljrbim {
  fill: var(--svg-color--47312f, #47312F);
  d: path("M9.755 16.317c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.651-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.704c.875-.499 3.37-2.968 4.011-3.605c.537-.535.64-1.215.875-3.197");
}

.ft5dv1b6b {
  fill: none;
}

.fznz2mbxx {
  stop-color: var(--svg-color--4b322f, #4B322F);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g4-rnpbiv {
  d: path("M10.236 28.174c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.17.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.g8rhdpbdt {
  d: path("m19.283 6.055l-.019-.395a.92.92 0 0 0-.88-.893h-.876a1.52 1.52 0 0 1-1.33-.788s.451-1.302 1.2-1.133c.546.123 1.131.316 1.579.608c1.092.713.9 1.996.326 2.6");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gvi5igtdh {
  d: path("M12.836 6.775a.598.598 0 0 0 .052 1.176q-.033-.588-.052-1.176");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.hekp_gbnf {
  stop-color: var(--svg-color--f74d05, #F74D05);
}

.hfnjpubec {
  stop-color: var(--svg-color--3c2826, #3C2826);
}

.hikihhbgc {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M26.175 23.762a.4.4 0 0 0 .18.536c.754.374 1.51.448 1.823.448a.4.4 0 0 0 0-.8c-.226 0-.852-.06-1.466-.364a.4.4 0 0 0-.537.18");
}

.hnjuf644p {
  stop-color: var(--svg-color--402723, #402723);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hss_x8b0z {
  stroke: var(--svg-color--070506, #070506);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.01a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.hx5ihzb7y {
  stop-color: var(--svg-color--251513, #251513);
}

.i1mpky9sl {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.908 5.767a1.45 1.45 0 0 1 1.036-.239");
}

.i1pdukfxy {
  d: path("M19.1 8.365q.063-1 .116-1.998a1.008 1.008 0 0 1-.115 1.998");
}

.i6inoib7r {
  d: path("m15.78 7.078l-.332 1.15c-.068.237.095.474.326.474h.492c.23 0 .394-.24.326-.473l-.333-1.151c-.071-.255-.404-.255-.479 0");
}

.i70ybeqwy {
  fill: var(--svg-color--202020, #202020);
  d: path("M13.884 5.592a1.74 1.74 0 0 1 1.088-.225a.174.174 0 0 1-.042.344a1.4 1.4 0 0 0-.915.209l-.01.007l-.002.001a.174.174 0 0 1-.212-.274z");
}

.i9cgj7g1s {
  fill: var(--svg-color--4d261f, #4D261F);
  d: path("M22.32 16.317c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.651.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.704c-.874-.499-3.37-2.968-4.01-3.605c-.538-.535-.641-1.215-.876-3.197");
}

.iap9bjb7s {
  stroke: var(--svg-color--070506, #070506);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.01a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iu4sfzbng {
  stop-color: var(--svg-color--543b37, #543B37);
  stop-opacity: 0;
}

.j_m47xbqb {
  d: path("M13.22 24.55h-1.429a1 1 0 0 0-.943.67c-.408 1.17-.96 2.764-1.032 3.001c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j873t3pix {
  fill-rule: evenodd;
  d: path("M26.175 23.762a.4.4 0 0 0 .18.536c.754.374 1.51.448 1.823.448a.4.4 0 0 0 0-.8c-.226 0-.852-.06-1.466-.364a.4.4 0 0 0-.537.18");
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k-fq99sbh {
  stop-color: var(--svg-color--62514e, #62514E);
  stop-opacity: 0;
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.khd1c0n-i {
  stop-color: var(--svg-color--351916, #351916);
  stop-opacity: 0;
}

.ksocwfbza {
  stop-color: var(--svg-color--ee5422, #EE5422);
  stop-opacity: 0;
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lehanccnj {
  stop-color: var(--svg-color--512d27, #512D27);
  stop-opacity: 0;
}

.lg8towb3y {
  stop-color: var(--svg-color--634f4b, #634F4B);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mkk0k-byc {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.983c-.41-.067-1.204-.313-1.59-.645");
}

.mwtukgbbz {
  stop-color: var(--svg-color--625250, #625250);
}

.n55l0rxro {
  stop-color: var(--svg-color--351916, #351916);
}

.n9h2xzfye {
  stop-color: var(--svg-color--2f0c0a, #2F0C0A);
  stop-opacity: 0;
}

.njoad_bkl {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M6.099 24.184a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.113l-.037.003a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.o-0p8ab1g {
  stop-color: var(--svg-color--391816, #391816);
  stop-opacity: 0;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.onaimccwi {
  fill-rule: evenodd;
  d: path("M25.182 24.409c-.14.17-.272.303-.101.443c.565.464.934.651 1.193.783l.072.037a.4.4 0 0 0 .367-.711l-.074-.038a5 5 0 0 1-1.051-.69c-.17-.14-.266.005-.406.176");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p5j2ywblw {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.502c-.398 0-.893.047-1.58-.109");
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pa78cvbvm {
  d: path("M12.976 8.308a1.03 1.03 0 0 1-.566-.194v.583c0 .56.333 1.057.84 1.264a2.6 2.6 0 0 1-.217-.739z");
}

.pc6ft5bqj {
  stop-color: var(--svg-color--2b0c0a, #2B0C0A);
}

.pdvw2hfdl {
  stop-color: var(--svg-color--634f4b, #634F4B);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.phf6igbvb {
  stop-color: var(--svg-color--62514e, #62514E);
}

.pk5i2pb0j {
  stop-color: var(--svg-color--62514f, #62514F);
}

.pkq92ktmj {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.78 7.078l-.332 1.15c-.068.237.095.474.326.474h.492c.23 0 .394-.24.326-.473l-.333-1.151c-.071-.255-.404-.255-.479 0");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qb45jbc1d {
  fill-rule: evenodd;
  d: path("M6.099 24.184a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.113l-.037.003a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qhpil-b3e {
  d: path("M13.83 21.56H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qxv17obmu {
  d: path("M18.517 21.56h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rm-es7b9q {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.252a3.8 3.8 0 0 1-1.773-.437");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rsji3yblh {
  stop-color: var(--svg-color--291715, #291715);
}

.rv50jfbso {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M25.902 24.184a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.113l.037.003a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.053-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.rwyr8xb2b {
  stop-color: var(--svg-color--261413, #261413);
  stop-opacity: 0;
}

.s386_46_x {
  d: path("M9.755 16.317c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.651-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.704c.875-.499 3.37-2.968 4.011-3.605c.537-.535.64-1.215.875-3.197");
}

.s4y_htbex {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.291c.25-.145.847-.51 1.234-.804");
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t-_6tzcpa {
  fill: var(--svg-color--492e29, #492E29);
  d: path("M10.236 28.174c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.17.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.t0fy-bbwc {
  stop-color: var(--svg-color--2c1e1e, #2C1E1E);
}

.t2uxtx_ya {
  fill-rule: evenodd;
  d: path("M25.316 23.194a.5.5 0 0 0 .5.5c.632 0 1.257-.193 1.5-.268l.04-.012a.5.5 0 1 0-.322-.948c-.246.075-.743.228-1.218.228a.5.5 0 0 0-.5.5");
}

.tej0dgbcx {
  fill-rule: evenodd;
  d: path("M26.304 23.284a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.ttit7sbwx {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M5.697 23.284a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.tv41nebaf {
  fill-rule: evenodd;
  d: path("M6.76 23.194a.5.5 0 0 1-.5.5c-.632 0-1.257-.193-1.501-.268l-.04-.012a.5.5 0 1 1 .322-.948c.246.075.743.228 1.219.228a.5.5 0 0 1 .5.5");
}

.twl0g-bsl {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m19.283 6.055l-.019-.395a.92.92 0 0 0-.88-.893h-.876a1.52 1.52 0 0 1-1.33-.788s.451-1.302 1.2-1.133c.546.123 1.131.316 1.579.608c1.092.713.9 1.996.326 2.6");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u24mgdcov {
  stop-color: var(--svg-color--261413, #261413);
}

.uc5_bsbkt {
  stop-color: var(--svg-color--281816, #281816);
}

.uesodzbqv {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M18.644 4.02h-1.302a.302.302 0 1 1 .048-.601a15 15 0 0 1 1.087.203c.68.169.867.5.92.736a.95.95 0 0 0-.753-.337");
}

.ufa4e1bue {
  d: path("m13.447 24.55l-1.578-2.99h8.301l-1.551 2.99z");
}

.ufs3b81ci {
  d: path("M17.627 28.174h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uo439xb-e {
  stop-color: var(--svg-color--60514f, #60514F);
}

.uq-h9hb8w {
  stop-color: var(--svg-color--3f2623, #3F2623);
}

.us72pebsg {
  stop-color: var(--svg-color--3d2b2d, #3D2B2D);
}

.uwa_e26-a {
  stop-color: var(--svg-color--594d4c, #594D4C);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vat8zbb1h {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M26.304 23.284a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.vcvz10bee {
  d: path("M22.32 16.317c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.651.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.704c-.874-.499-3.37-2.968-4.01-3.605c-.538-.535-.641-1.215-.876-3.197");
}

.w-l5r38ro {
  stop-color: var(--svg-color--64514f, #64514F);
}

.w0_6atbzj {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.502c.398 0 .893.047 1.58-.109");
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

.w3geznflg {
  stop-color: var(--svg-color--391816, #391816);
}

.wd5n0p1ub {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.01a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.wjiz1pa3n {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.187 9.066c.24.125.526.198.833.198c.309 0 .592-.073.832-.198a.17.17 0 0 1 .203.034a.16.16 0 0 1 .018.205m-1.886-.239l1.824.198m-1.824-.198a.17.17 0 0 0-.203.035a.16.16 0 0 0-.018.205m.22-.24l-.158.198m2.045.041l-.062-.041m.062.041l-.062-.041m.062.041a1.26 1.26 0 0 1-1.053.563a1.26 1.26 0 0 1-1.054-.562m2.045-.042c-.21.317-.575.53-.991.53s-.782-.213-.992-.53m-.062.042l.062-.042m-.062.042l.062-.042");
}

.wsizjkbjw {
  stop-color: var(--svg-color--502822, #502822);
}

.wtx0-zb9b {
  d: path("M18.892 11.39v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x81pqcclg {
  fill-rule: evenodd;
  d: path("M5.697 23.284a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.xbeiecc_v {
  d: path("M12.856 6.362a1.008 1.008 0 0 0 .086 2.003a49 49 0 0 1-.086-2.003");
}

.xbk_ospgb {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.768 7.2l-.37 1.151c-.063.237.089.474.303.474h.459c.214 0 .366-.24.303-.474l-.31-1.15c-.066-.256-.315-.256-.385 0");
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xxeo3cl2n {
  d: path("M19.059 3.367a1.482 1.482 0 0 1 .727 2.239a1 1 0 0 0-.17.548v.743a1.1 1.1 0 0 0-.417-.168l.049-1.005a.907.907 0 0 0-.863-.897h-.877a1.52 1.52 0 0 1-1.384-.903a.42.42 0 0 0-.386-.262h-.796a2.103 2.103 0 0 0-2.092 2.116l.019.962a1.1 1.1 0 0 0-.45.165v-.751a1 1 0 0 0-.17-.548a1.5 1.5 0 0 1-.09-1.53c.183-.347.478-.588.814-.706c.358-.128.664-.37.866-.695a1.456 1.456 0 0 1 1.81-.57a.93.93 0 0 0 .747 0a1.45 1.45 0 0 1 .57-.118c.529 0 .99.285 1.246.708c.192.32.495.55.847.672");
}

.y3ixjxb0y {
  d: path("M19.114 7.955q.036-.596.069-1.192a.598.598 0 0 1-.07 1.192");
}

.y8dgjevrz {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.983c.41-.067 1.204-.313 1.59-.645");
}

.y8h5-ibcw {
  d: path("M19.063 8.308c.21-.007.406-.078.566-.194v.583a1.36 1.36 0 0 1-.84 1.264q.161-.341.217-.739z");
}

.ydcxvabaw {
  stop-color: var(--svg-color--ff7d3c, #FF7D3C);
}

.z2_7lnp1p {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M5.825 23.762a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8c.226 0 .852-.06 1.466-.364a.4.4 0 0 1 .537.18");
}

.z2i7gkbiq {
  stop-color: var(--svg-color--281816, #281816);
  stop-opacity: 0;
}

.z2zeoomhh {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.357 5.66a1.2 1.2 0 0 0-.43-.258c-.191-.06-.43-.076-.76-.035a.174.174 0 1 0 .042.344c.302-.037.486-.017.613.023a.8.8 0 0 1 .307.188a.174.174 0 1 0 .228-.262");
}

.z321yabtz {
  stop-color: var(--svg-color--d3612e, #D3612E);
  stop-opacity: 0;
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zhfkvgbxb {
  stop-color: var(--svg-color--4b3b39, #4B3B39);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.znfzn6b4i {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.252a3.8 3.8 0 0 0 1.773-.437");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
