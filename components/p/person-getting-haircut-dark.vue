<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZtNsKA)" class="vapbcpbae"/><path fill="url(#iPKHYvc)" class="vapbcpbae"/><path fill="url(#iENrg4u)" class="vapbcpbae"/><path fill="url(#iRulEdd)" class="vapbcpbae"/><path fill="url(#i636yxA)" class="j83tpkb3z"/><path fill="url(#inLi7ub)" class="j83tpkb3z"/><path class="ykpa4isdi"/><path fill="url(#iiOTm5c)" class="ut61vkhxw"/><path fill="url(#i33eekb)" class="ut61vkhxw"/><path class="p81f9xhcp"/><path fill="url(#iRILXqb)" class="vl14jccol"/><path fill="url(#ifvhCKc)" class="vl14jccol"/><path fill="url(#iW5P7jb)" class="g4l9w_bsz"/><path fill="url(#i2H7tIe)" class="py7uwbbbb"/><g filter="url(#ivmXL3b)"><path fill="url(#iYrGXjn)" class="zp_2h52ml"/></g><path fill="url(#iqiSeIx)" class="zp_2h52ml"/><path fill="url(#i1hrLPb)" class="zp_2h52ml"/><path fill="url(#i76gDbd)" class="zp_2h52ml"/><path fill="url(#imQMpRb)" class="zp_2h52ml"/><path fill="url(#iGhZyhe)" class="zp_2h52ml"/><path fill="url(#izuZjyb)" class="zp_2h52ml"/><path fill="url(#iBoFDnb)" class="zp_2h52ml"/><path fill="url(#iaeL0Xb)" class="zp_2h52ml"/><path fill="url(#imJ8iGS)" class="zp_2h52ml"/><path fill="url(#igTMzTc)" class="zp_2h52ml"/><g filter="url(#i3HxYSc)"><path class="cuox0dngs"/></g><g filter="url(#igtynAd)"><path class="t4p1l-b3o"/><path fill="url(#i9AooYc)" class="g_5nkeb-d"/><path fill="url(#iPw422d)" class="g_5nkeb-d"/><path fill="url(#iJICoNc)" class="g_5nkeb-d"/><path fill="url(#i1HqLUb)" class="g_5nkeb-d"/><path fill="url(#in9r9bd)" class="g_5nkeb-d"/></g><g filter="url(#iZ8Lx9b)"><path stroke="url(#iaZDVgb)" class="yddio5msw"/></g><path fill="url(#iKZNo6b)" class="aj3h4-bsc"/><g filter="url(#iWdbjHe)"><path fill="url(#ix3E5hb)" class="x6wz5bbma"/><path fill="url(#iYy59Id)" class="x6wz5bbma"/><path fill="url(#iKqZaib)" class="x6wz5bbma"/><path fill="url(#iyJ3cCd)" class="x6wz5bbma"/><path fill="url(#i1KhLpe)" class="x6wz5bbma"/></g><g filter="url(#iSEZySc)"><path class="cg5anmb9c"/></g><g filter="url(#ipMWdhW)"><path class="l42ezl-gd"/></g><g filter="url(#irWr1Tb)"><path class="ixmppmk3z"/><path fill="url(#iHCEsAb)" class="t-nk7us5w"/><path fill="url(#iEDgYxt)" class="t-nk7us5w"/></g><g filter="url(#iNvvTod)"><path class="vw6_2zslm"/><path fill="url(#i3Y4Mtd)" class="rr8g--b-q"/></g><path class="lj-v8l4pe"/><path fill="url(#iF5ho2p)" class="m1rmp0oap"/><path class="xxka4-9zg"/><g filter="url(#ivTsFUc)"><path class="cwcwwzkru"/><path fill="url(#iKY51id)" class="hzb19_b3h"/></g><g filter="url(#iMkfiac)"><path fill="url(#igrmmne)" class="gui8k__nc"/></g><path class="wi69wtboh"/><path fill="url(#iqyzPfd)" class="sg789vijm"/><path class="mi5o36bnp"/><g filter="url(#itb2DOR)"><path fill="url(#iRoTNfe)" class="jie_37bnb"/></g><g filter="url(#iixPIWc)"><ellipse transform="rotate(-27.914 12.052 12.77)" class="kod256bgn"/><ellipse fill="url(#ibyza1c)" transform="rotate(-27.914 12.052 12.77)" class="xy9g5-bnr"/></g><path fill="url(#ihAO9le)" class="ret09nwna"/><path fill="url(#iX8cPde)" class="ret09nwna"/><path fill="url(#i56htfd)" class="ret09nwna"/><path fill="url(#iGTew2o)" class="ret09nwna"/><path fill="url(#ix21Hme)" class="ls_vzv0xi"/><path fill="url(#ivrHhDe)" class="ls_vzv0xi"/><g filter="url(#iX8Y3Bb)"><path fill="url(#i0IHkbc)" class="x9_y-0bid"/></g><g filter="url(#iFqcomb)"><path fill="url(#i50NR0d)" class="h4xnlccdt"/></g><g filter="url(#iLnU4iT)"><path class="ovn3mr6zc"/></g><g filter="url(#iYXHexd)"><path class="q6mnm31uh"/></g><g filter="url(#iqNHUEd)"><path class="p96i1te6i"/></g><g filter="url(#iHDkvQb)"><path fill="url(#iCahVOb)" class="dflejvbqt"/><path fill="url(#ioRmajb)" class="dflejvbqt"/><path fill="url(#iuqXSmc)" class="dflejvbqt"/></g><path fill="url(#iKzGVPb)" class="dflejvbqt"/><path fill="url(#iypihWz)" class="blrx8nbbq"/><path fill="url(#iTCVotb)" class="blrx8nbbq"/><path fill="url(#iaab2qd)" class="fbxobibbw"/><path fill="url(#iYe8ync)" class="fbxobibbw"/><g filter="url(#iWHDren)"><circle fill="url(#iE83aDo)" class="lfebp9b7f"/><circle fill="url(#iDuBIRN)" class="lfebp9b7f"/><circle fill="url(#im1L1Jd)" class="lfebp9b7f"/></g><g filter="url(#iH8DZVb)"><path fill="url(#iuariLM)" clip-rule="evenodd" class="jh82fxjmq"/></g><path fill="url(#iFr5q9b)" clip-rule="evenodd" class="jh82fxjmq"/><g filter="url(#iRS3q4c)"><path fill="url(#i9KvywP)" clip-rule="evenodd" class="nmbsstbpb"/></g><g filter="url(#iG9i2jb)"><circle stroke="url(#im2Biye)" class="fls6-uyso"/></g><g filter="url(#igtqYAe)"><circle stroke="url(#itgHzob)" class="cbto_2nhv"/></g><g filter="url(#imlS5Hc)"><circle stroke="url(#imRB78b)" class="ywa5-blxg"/></g><g filter="url(#iCBKYzJ)"><circle stroke="url(#innb8He)" class="xbpaa8b7o"/></g><defs><radialGradient id="iZtNsKA" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.204 14.176)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="qwzbgbcpc"/><stop offset="1" class="yrgygrb-x"/></radialGradient><radialGradient id="iPKHYvc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.382 30.43)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="znj-7lelt"/><stop offset="1" class="w53rld2zh"/></radialGradient><radialGradient id="iENrg4u" cx="0" cy="0" r="1" gradientTransform="matrix(-10.23463 3.91089 -1.18367 -3.09762 12.577 19.046)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u-ogyggtr"/><stop offset="1" class="tr4934b7k"/></radialGradient><radialGradient id="iRulEdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.46 29.926)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="pujgjpbud"/><stop offset="1" class="dstba7uva"/></radialGradient><radialGradient id="i636yxA" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.49 29.147)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="teikdvrbz"/><stop offset="1" class="v5czltblq"/></radialGradient><radialGradient id="inLi7ub" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.49 29.926)" gradientUnits="userSpaceOnUse"><stop class="gbso5obkm"/><stop offset="1" class="x7u0pvbam"/></radialGradient><radialGradient id="iiOTm5c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.224 29.926)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="ajnorac8k"/><stop offset="1" class="o0jyspbad"/></radialGradient><radialGradient id="i33eekb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -16.6933 7.224 29.926)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="w5_5qkbkk"/><stop offset="1" class="h6pm4_bbg"/></radialGradient><radialGradient id="iRILXqb" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.614 19.561)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="h7kx9ybqo"/><stop offset="1" class="rt4768g0a"/></radialGradient><radialGradient id="ifvhCKc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14587 1.92234 -.8326 -.92942 16.683 20.795)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="yyndohvfc"/><stop offset="1" class="psfd0x9sk"/></radialGradient><radialGradient id="iW5P7jb" cx="0" cy="0" r="1" gradientTransform="matrix(.75838 2.04543 -2.42982 .9009 19.351 14.748)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="i2H7tIe" cx="0" cy="0" r="1" gradientTransform="matrix(1.4954 .46998 -1.4499 4.6134 8.403 15.244)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iYrGXjn" cx="0" cy="0" r="1" gradientTransform="matrix(-5.29489 0 0 -9.36661 17.38 13.794)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="i1hrLPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03533 12.58278 -10.42009 -.85738 16.139 7.805)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset="1" class="hwuook6nv"/></radialGradient><radialGradient id="i76gDbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16308 1.43931 0 17.015 12.464)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="imQMpRb" cx="0" cy="0" r="1" gradientTransform="matrix(.00398 -1.10831 1.2061 .00434 12.207 12.511)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iGhZyhe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.60493 .54319 -1.38756 -21.98125 18.014 14.795)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="izuZjyb" cx="0" cy="0" r="1" gradientTransform="matrix(4.12523 -2.68225 .9819 1.51012 9 9.413)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iBoFDnb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 5.142 14.594)scale(2.5406 1.01559)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iaeL0Xb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.03 9.168)scale(3.41218 2.81703)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="igTMzTc" cx="0" cy="0" r="1" gradientTransform="rotate(125.538 5.928 8.79)scale(2.15058 1.61657)" gradientUnits="userSpaceOnUse"><stop class="a133zui4g"/><stop offset="1" class="e10ayxp8t"/></radialGradient><radialGradient id="iPw422d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24723 -.77702 0 15.01 15.172)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="i1HqLUb" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 5.97 8.949)scale(1.69487 2.72379)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iKZNo6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72998 2.93689 0 14.537 17.379)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iYy59Id" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.54622 8.96799 0 9.24 10.865)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iKqZaib" cx="0" cy="0" r="1" gradientTransform="matrix(.1155 -2.54476 4.50882 .20465 19.46 12.192)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iyJ3cCd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38908 -1.5713 1.15341 -1.7537 18.696 5.835)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="i1KhLpe" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 3.038 14.28)scale(1.75275 4.05855)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iHCEsAb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.22935 0 0 -.8274 14.794 6.51)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iEDgYxt" cx="0" cy="0" r="1" gradientTransform="matrix(3.25944 -5.16078 5.71761 3.61112 9.037 10.504)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i3Y4Mtd" cx="0" cy="0" r="1" gradientTransform="matrix(3.28987 .38453 -.161 1.3774 16.307 8.878)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iF5ho2p" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82172 -1.30704 0 16.747 12.866)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iKY51id" cx="0" cy="0" r="1" gradientTransform="matrix(-.2349 -.3027 .41673 -.32339 16.517 12.951)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqyzPfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82176 -1.30711 0 12.327 12.866)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibyza1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00784 -.50042 .60152 -.00942 12.037 13.088)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iX8cPde" cx="0" cy="0" r="1" gradientTransform="matrix(.63659 2.27204 -2.16771 .60736 19.214 12.88)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="i56htfd" cx="0" cy="0" r="1" gradientTransform="matrix(.79788 -1.09496 .9178 .66879 19.579 13.432)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iGTew2o" cx="0" cy="0" r="1" gradientTransform="matrix(.59452 -1.5703 2.09814 .79437 19.694 13.607)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="ivrHhDe" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.752 10.303)scale(2.14382 2.10758)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="i0IHkbc" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 4.203 7.173)scale(.94181 .41539)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="ioRmajb" cx="0" cy="0" r="1" gradientTransform="matrix(-.31067 .66453 -.28734 -.13433 23.331 5.24)" gradientUnits="userSpaceOnUse"><stop offset=".012" class="v2ozkbcky"/><stop offset="1" class="dox6m7bdf"/></radialGradient><radialGradient id="iuqXSmc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 0 0 1.69526 17.37 7.256)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iKzGVPb" cx="0" cy="0" r="1" gradientTransform="rotate(-110.771 12.088 -1.466)scale(3.83324 9.66691)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="g52jnubae"/><stop offset="1" class="pnsb-499x"/></radialGradient><radialGradient id="iE83aDo" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.683 7.966)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iDuBIRN" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.68 7.917)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="im1L1Jd" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.455 7.478)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="iuariLM" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.483 10.666)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="i9KvywP" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.63 8.842)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="ivmXL3b" width="11.351" height="12.7" x="9.409" y="7.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_24" result="effect2_innerShadow_4002_24"/></filter><filter id="i3HxYSc" width="3.769" height="4.937" x="12.509" y="11.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".5"/></filter><filter id="igtynAd" width="2.101" height="3.137" x="13.486" y="12.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".05"/></filter><filter id="iZ8Lx9b" width="3.76" height="1.587" x="12.657" y="16.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".05"/></filter><filter id="iWdbjHe" width="13.038" height="8.457" x="8.018" y="4.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_24" result="effect2_innerShadow_4002_24"/></filter><filter id="iSEZySc" width="2.368" height="1.203" x="16.147" y="10.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/></filter><filter id="ipMWdhW" width="2.368" height="1.188" x="10.823" y="10.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/></filter><filter id="irWr1Tb" width="6.812" height="6.062" x="8.381" y="5.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/><feGaussianBlur result="effect2_foregroundBlur_4002_24" stdDeviation=".125"/></filter><filter id="iNvvTod" width="6.44" height="5.806" x="14.376" y="5.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/><feGaussianBlur result="effect2_foregroundBlur_4002_24" stdDeviation=".125"/></filter><filter id="ivTsFUc" width=".794" height=".703" x="16.005" y="12.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".05"/></filter><filter id="iMkfiac" width=".898" height=".92" x="16.857" y="12.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".1"/></filter><filter id="itb2DOR" width=".994" height="1.048" x="12.357" y="12.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".1"/></filter><filter id="iixPIWc" width=".922" height=".711" x="11.591" y="12.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".05"/></filter><filter id="iX8Y3Bb" width="1.34" height="2.404" x="8.381" y="12.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".125"/></filter><filter id="iFqcomb" width="1.959" height="2.928" x="19.044" y="12.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".25"/></filter><filter id="iLnU4iT" width="2.426" height="1.166" x="10.746" y="10.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".125"/></filter><filter id="iYXHexd" width="2.426" height="1.166" x="16.092" y="10.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".125"/></filter><filter id="iqNHUEd" width="5.314" height="3.025" x="15.437" y="6.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".375"/></filter><filter id="iHDkvQb" width="9.109" height="4.371" x="14.746" y="4.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/></filter><filter id="iWHDren" width=".726" height=".726" x="23.512" y="7.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/></filter><filter id="iH8DZVb" width="3.834" height="4.387" x="21.054" y="7.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_24" result="effect2_innerShadow_4002_24"/></filter><filter id="iRS3q4c" width="4.283" height="3.734" x="24.252" y="6.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_24"/></filter><filter id="iG9i2jb" width="3.843" height="3.843" x="24.723" y="6.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".1"/></filter><filter id="igtqYAe" width="2.734" height="2.734" x="25.278" y="7.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".1"/></filter><filter id="imlS5Hc" width="2.734" height="2.734" x="21.629" y="9.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".1"/></filter><filter id="iCBKYzJ" width="3.805" height="3.805" x="21.093" y="8.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_24" stdDeviation=".1"/></filter><linearGradient id="iqiSeIx" x1="19.76" x2="15.352" y1="15.501" y2="15.501" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="imJ8iGS" x1="14.584" x2="14.584" y1="20.126" y2="19.478" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="i9AooYc" x1="15.386" x2="14.537" y1="14.478" y2="14.513" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iJICoNc" x1="14.537" x2="14.537" y1="15.631" y2="15.161" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="in9r9bd" x1="14.537" x2="14.537" y1="12.639" y2="13.445" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iaZDVgb" x1="13.32" x2="13.642" y1="17.222" y2="16.377" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="ix3E5hb" x1="21.477" x2="9.716" y1="8.059" y2="8.059" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="igrmmne" x1="17.535" x2="17.217" y1="12.921" y2="13.117" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRoTNfe" x1="13.081" x2="12.763" y1="12.921" y2="13.117" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihAO9le" x1="21.056" x2="19.834" y1="12.948" y2="15.152" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="ix21Hme" x1="8.612" x2="10.089" y1="13.661" y2="13.532" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="i50NR0d" x1="20.023" x2="20.023" y1="12.562" y2="14.489" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iCahVOb" x1="23.605" x2="17.52" y1="5.53" y2="9.217" gradientUnits="userSpaceOnUse"><stop class="r-a4upbdn"/><stop offset="1" class="q-kinsb7r"/></linearGradient><linearGradient id="iypihWz" x1="25.035" x2="23.843" y1="5.619" y2="5.274" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iTCVotb" x1="23.887" x2="23.961" y1="7.112" y2="6.823" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iaab2qd" x1="22.973" x2="23.238" y1="7.967" y2="6.671" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iYe8ync" x1="24.384" x2="24.186" y1="8.049" y2="7.994" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="iFr5q9b" x1="23.723" x2="23.664" y1="8.139" y2="8.366" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="im2Biye" x1="24.973" x2="28.163" y1="8.742" y2="7.269" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="itgHzob" x1="25.528" x2="27.66" y1="8.62" y2="7.635" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="imRB78b" x1="21.879" x2="24.011" y1="10.633" y2="9.649" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="innb8He" x1="24.648" x2="22.996" y1="9.846" y2="10.387" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-haircut-dark" /></template>
<style>
.a133zui4g {
  stop-color: var(--svg-color--574747, #574747);
}

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

.aj3h4-bsc {
  d: path("M14.537 16.728c-.514 0-.997-.121-1.403-.333c-.139-.07-.288.086-.2.212c.339.514.93.857 1.603.857s1.264-.343 1.604-.857c.087-.131-.062-.282-.2-.212a3 3 0 0 1-1.404.333");
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.ajnorac8k {
  stop-color: var(--svg-color--e36750, #E36750);
  stop-opacity: 0;
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.blrx8nbbq {
  d: path("M24.428 3.213L23.04 8.044l1.187.345l1.071-3.729a1.15 1.15 0 0 0-.784-1.422z");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
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

.cbto_2nhv {
  cx: 26.645px;
  cy: 8.373px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.cg5anmb9c {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.318 10.776a1.9 1.9 0 0 0-.696-.416c-.309-.097-.695-.123-1.229-.058a.28.28 0 0 0 .069.558c.487-.06.786-.03.99.036c.202.063.338.165.497.304a.28.28 0 1 0 .369-.424");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cuox0dngs {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m14.13 13.269l-.598 1.861c-.102.383.143.766.49.766h.742c.347 0 .593-.388.49-.766l-.5-1.861c-.108-.413-.511-.413-.623 0");
}

.cwcwwzkru {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.683 12.574c.064.086-.07.191-.224.306c-.153.114-.266.195-.33.108c-.065-.086.007-.248.16-.363s.33-.137.394-.05");
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dflejvbqt {
  d: path("M18.614 9.249c3.492-.378 4.66-1.907 4.922-2.868c.055-.17.122-.601 0-.957c-.097-.285-.437-.347-.593.067c-.367.89-1.172 1.304-2.04 1.453c-.866.148-1.655.226-3.062-.399c-1.004-.446-1.578-.609-2.18-.406c-.601.203-1.195.86-.773 1.867c.376.898 1.125 1.524 3.726 1.243");
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dox6m7bdf {
  stop-color: var(--svg-color--474244, #474244);
  stop-opacity: 0;
}

.dstba7uva {
  stop-color: var(--svg-color--ff7543, #FF7543);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e10ayxp8t {
  stop-color: var(--svg-color--4f3738, #4F3738);
  stop-opacity: 0;
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fbxobibbw {
  d: path("m19.78 5.79l5.42 1.537l-.338 1.188l-4.313-1.222a1.15 1.15 0 0 1-.793-1.42z");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fls6-uyso {
  cx: 26.645px;
  cy: 8.373px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ft5dv1b6b {
  fill: none;
}

.g_5nkeb-d {
  d: path("m14.15 13.07l-.538 1.862c-.11.383.153.766.527.766h.796c.374 0 .637-.389.528-.766l-.539-1.862c-.115-.412-.653-.412-.774 0");
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g4l9w_bsz {
  d: path("M19.46 15.06c.34-.01.658-.126.917-.312v.943a2.2 2.2 0 0 1-1.358 2.044q.259-.552.35-1.195z");
}

.g52jnubae {
  stop-color: var(--svg-color--3a3338, #3A3338);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gbso5obkm {
  stop-color: var(--svg-color--ff5130, #FF5130);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gui8k__nc {
  d: path("M17.554 13.168a.85.85 0 0 0-.234-.469l-.263.29l.118.23z");
}

.h4xnlccdt {
  d: path("M19.544 14.49q.058-.965.111-1.928a.968.968 0 0 1-.111 1.927");
}

.h6pm4_bbg {
  stop-color: var(--svg-color--ff6640, #FF6640);
  stop-opacity: 0;
}

.h7kx9ybqo {
  stop-color: var(--svg-color--3a161b, #3A161B);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hwuook6nv {
  stop-color: var(--svg-color--5d201d, #5D201D);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.hzb19_b3h {
  d: path("M16.683 12.574c.064.086-.07.191-.224.306c-.153.114-.266.195-.33.108c-.065-.086.007-.248.16-.363s.33-.137.394-.05");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ixmppmk3z {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m14.772 8.107l-.067-.139a.67.67 0 0 0-.623-.424h-1.289c-1.87 0-3.384 1.532-3.384 3.423v.278c-.345-.262-.778-.814-.778-1.71c0-1.085.792-1.633 1.297-1.983c.143-.1.262-.182.335-.257l.101-.106c.354-.376.985-1.045 2.086-1.337a5.5 5.5 0 0 1 1.538-.167c.472.012.806.42.806.893v1.515z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.j83tpkb3z {
  d: path("M21.49 29.926h3.71v-.463c0-3.218-1.437-6.103-3.71-8.067z");
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jh82fxjmq {
  fill-rule: evenodd;
  d: path("M23.099 8.012a.1.1 0 0 0-.124.068l-.104.357a.22.22 0 0 1-.174.148a1.842 1.842 0 1 0 1.514.434a.21.21 0 0 1-.068-.22l.101-.349a.1.1 0 0 0-.068-.124zm.74 2.391a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.jie_37bnb {
  d: path("M13.151 13.18c0-.291-.238-.486-.302-.545l-.292.283l.18.365z");
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
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

.kod256bgn {
  cx: 12.052px;
  cy: 12.769px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
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

.l42ezl-gd {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.082 10.666a2.8 2.8 0 0 1 1.761-.364a.28.28 0 0 1-.068.557a2.25 2.25 0 0 0-1.404.289a1 1 0 0 0-.093.06l-.003.002a.28.28 0 0 1-.344-.444z");
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lfebp9b7f {
  cx: 23.825px;
  cy: 7.569px;
  r: 0.313px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj-v8l4pe {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.959 12.108c.661 0 1.22.456 1.372 1.072a.278.278 0 0 1-.271.345H15.8a.233.233 0 0 1-.23-.275a1.416 1.416 0 0 1 1.389-1.142");
}

.ls_vzv0xi {
  d: path("M9.418 11.912a1.63 1.63 0 0 0 .14 3.24a79 79 0 0 1-.14-3.24");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m1rmp0oap {
  d: path("M16.75 12.383a.904.904 0 0 1 .87 1.142h-1.746a.907.907 0 0 1 .875-1.142");
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mi5o36bnp {
  fill: var(--svg-color--000, #000);
  d: path("M12.843 13.287a.516.516 0 0 0-.518-.518a.516.516 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.238");
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.nmbsstbpb {
  fill-rule: evenodd;
  d: path("M24.543 7.225a.1.1 0 0 1 .123-.071l.36.095a.21.21 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.093a.1.1 0 0 1-.07-.123zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.444");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o0jyspbad {
  stop-color: var(--svg-color--e36750, #E36750);
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovn3mr6zc {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.12 10.95c.26-.188.91-.516 1.677-.387");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p81f9xhcp {
  fill: var(--svg-color--422227, #422227);
  d: path("M12.545 18.545h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.712-1.992-1.813z");
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p96i1te6i {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M18.784 8.124h-2.108a.489.489 0 1 1 .078-.973c.547.087 1.273.208 1.76.329c1.099.272 1.402.808 1.487 1.19a1.53 1.53 0 0 0-1.217-.546");
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnsb-499x {
  stop-color: var(--svg-color--3a3338, #3A3338);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psfd0x9sk {
  stop-color: var(--svg-color--43242d, #43242D);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pujgjpbud {
  stop-color: var(--svg-color--ff7543, #FF7543);
}

.py7uwbbbb {
  d: path("M9.613 15.06a1.66 1.66 0 0 1-.916-.312v.943a2.2 2.2 0 0 0 1.358 2.044a4.1 4.1 0 0 1-.35-1.195z");
}

.q-kinsb7r {
  stop-color: var(--svg-color--211025, #211025);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q6mnm31uh {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.144 10.903c-.26-.187-.91-.516-1.677-.387");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwzbgbcpc {
  stop-color: var(--svg-color--ff702c, #FF702C);
}

.r-a4upbdn {
  stop-color: var(--svg-color--211420, #211420);
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.ret09nwna {
  d: path("M19.522 15.152q.101-1.616.187-3.232a1.63 1.63 0 0 1-.187 3.232");
}

.rr8g--b-q {
  d: path("m19.816 11.415l-.03-.639c-.01-.773-.649-1.411-1.422-1.444h-1.419c-.9 0-1.72-.492-2.15-1.276c0 0-.064-.145-.128-.394c-.25-.971.676-1.713 1.66-1.524c.992.191 2.125.524 2.962 1.07c1.767 1.152 1.457 3.23.527 4.207");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.rt4768g0a {
  stop-color: var(--svg-color--3a161b, #3A161B);
  stop-opacity: 0;
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sg789vijm {
  d: path("M12.325 12.383a.904.904 0 0 0-.871 1.142H13.2a1 1 0 0 0 .033-.238a.91.91 0 0 0-.908-.904");
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t-nk7us5w {
  d: path("m14.772 8.107l-.067-.139a.67.67 0 0 0-.623-.424h-1.289c-1.87 0-3.384 1.532-3.384 3.423v.278c-.345-.262-.778-.814-.778-1.71c0-1.085.792-1.633 1.297-1.983c.143-.1.262-.182.335-.257l.101-.106c.354-.376.985-1.045 2.086-1.337a5.5 5.5 0 0 1 1.538-.167c.472.012.806.42.806.893v1.515z");
}

.t4p1l-b3o {
  fill: var(--svg-color--402929, #402929);
  d: path("m14.15 13.07l-.538 1.862c-.11.383.153.766.527.766h.796c.374 0 .637-.389.528-.766l-.539-1.862c-.115-.412-.653-.412-.774 0");
}

.teikdvrbz {
  stop-color: var(--svg-color--ff7646, #FF7646);
}

.tr4934b7k {
  stop-color: var(--svg-color--ff5915, #FF5915);
  stop-opacity: 0;
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u-ogyggtr {
  stop-color: var(--svg-color--e73f04, #E73F04);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ut61vkhxw {
  d: path("M7.224 21.396c-2.273 1.964-3.71 4.85-3.71 8.066v.464h3.71z");
}

.v2ozkbcky {
  stop-color: var(--svg-color--474244, #474244);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v5czltblq {
  stop-color: var(--svg-color--ff6635, #FF6635);
}

.vapbcpbae {
  d: path("M3.515 29.462c0-5.915 4.854-10.71 10.842-10.71s10.842 4.795 10.842 10.71v.464H3.515z");
}

.vl14jccol {
  d: path("M12.545 18.545h3.984v1.383c0 1.1-.892 1.813-1.992 1.813s-1.992-.712-1.992-1.813z");
}

.vw6_2zslm {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m19.816 11.415l-.03-.639c-.01-.773-.649-1.411-1.422-1.444h-1.419c-.9 0-1.72-.492-2.15-1.276c0 0-.064-.145-.128-.394c-.25-.971.676-1.713 1.66-1.524c.992.191 2.125.524 2.962 1.07c1.767 1.152 1.457 3.23.527 4.207");
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

.w5_5qkbkk {
  stop-color: var(--svg-color--ff6640, #FF6640);
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.w53rld2zh {
  stop-color: var(--svg-color--e65d38, #E65D38);
}

.wi69wtboh {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.116 12.108c-.662 0-1.22.456-1.373 1.072a.278.278 0 0 0 .271.345h2.26a.233.233 0 0 0 .23-.275a1.42 1.42 0 0 0-1.388-1.142");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x6wz5bbma {
  d: path("M19.454 7.066c.521.18.988.543 1.284 1.065a2.4 2.4 0 0 1-.107 2.559a1.6 1.6 0 0 0-.274.885v1.203a1.8 1.8 0 0 0-.676-.271l.08-1.627a1.47 1.47 0 0 0-1.397-1.45h-1.419a2.46 2.46 0 0 1-2.24-1.462a.67.67 0 0 0-.623-.424h-1.289c-1.87 0-3.384 1.532-3.384 3.423l.03 1.557a1.7 1.7 0 0 0-.729.267v-1.216a1.6 1.6 0 0 0-.274-.885a2.42 2.42 0 0 1-.145-2.478c.296-.56.774-.95 1.317-1.14a2.7 2.7 0 0 0 1.402-1.125a2.355 2.355 0 0 1 2.927-.923a1.5 1.5 0 0 0 1.209 0c.285-.12.596-.19.924-.19c.854 0 1.6.461 2.014 1.146c.312.516.8.89 1.37 1.086");
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x7u0pvbam {
  stop-color: var(--svg-color--ff5130, #FF5130);
  stop-opacity: 0;
}

.x9_y-0bid {
  d: path("M9.386 12.58a.968.968 0 0 0 .085 1.904a79 79 0 0 1-.085-1.904");
}

.xbpaa8b7o {
  cx: 22.996px;
  cy: 10.387px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xxka4-9zg {
  fill: var(--svg-color--000, #000);
  d: path("M16.231 13.287c0-.288.23-.518.518-.518a.516.516 0 0 1 .46.756h-.916a.47.47 0 0 1-.062-.238");
}

.xy9g5-bnr {
  cx: 12.052px;
  cy: 12.769px;
  rx: 0.395px;
  ry: 0.2px;
}

.yddio5msw {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.168 16.329a3 3 0 0 0 1.369.324c.507 0 .973-.118 1.368-.324h.001a.23.23 0 0 1 .273.044c.065.068.09.177.024.275m-3.035-.32l2.973.279m-2.973-.278a.23.23 0 0 0-.274.047a.214.214 0 0 0-.023.273m.297-.32l-.235.278m3.27.041l-.062-.041m.062.041l-.062-.041m.062.041c-.353.535-.967.89-1.666.89a2 2 0 0 1-1.666-.89m3.27-.041c-.34.514-.93.857-1.604.857a1.92 1.92 0 0 1-1.604-.857m-.062.042l.062-.042m-.062.042l.062-.042");
}

.ykpa4isdi {
  fill: var(--svg-color--ff4f19, #FF4F19);
  d: path("M7.224 21.396c-2.273 1.964-3.71 4.85-3.71 8.066v.464h3.71z");
}

.yrgygrb-x {
  stop-color: var(--svg-color--ff521f, #FF521F);
}

.ywa5-blxg {
  cx: 22.996px;
  cy: 10.387px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.yyndohvfc {
  stop-color: var(--svg-color--5d322d, #5D322D);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.znj-7lelt {
  stop-color: var(--svg-color--e65d38, #E65D38);
  stop-opacity: 0;
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zp_2h52ml {
  d: path("M9.65 16.595a3.966 3.966 0 0 0 3.936 3.45h1.91a3.966 3.966 0 0 0 3.936-3.45c.12-1.908.24-3.808.328-5.715a1.47 1.47 0 0 0-1.397-1.45h-1.418a2.45 2.45 0 0 1-2.24-1.462a.67.67 0 0 0-.623-.424h-1.29c-1.868 0-3.383 1.532-3.383 3.423c0 1.884.117 3.738.241 5.628");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
