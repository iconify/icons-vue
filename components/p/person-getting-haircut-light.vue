<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i7EfFab)" class="xvnn9-gsy"/><path fill="url(#iiDcsLd)" class="xvnn9-gsy"/><path fill="url(#iNehdOe)" class="xvnn9-gsy"/><path fill="url(#iwmeRDE)" class="xvnn9-gsy"/><path fill="url(#iv0deVd)" class="odzn7sx-f"/><path fill="url(#ijoOoZb)" class="odzn7sx-f"/><path class="g_fm20xoc"/><path fill="url(#i4swUbe)" class="zh3rcwbvd"/><path fill="url(#iADENae)" class="zh3rcwbvd"/><path class="r1d1-cbgc"/><path fill="url(#iY0K1Ub)" class="h0e5jkbtm"/><path fill="url(#igUt8Xc)" class="h0e5jkbtm"/><path fill="url(#iMWtsPd)" class="h7mx9gbgv"/><path fill="url(#imVdNmc)" class="co2a3_79n"/><g filter="url(#izNAWEd)"><path fill="url(#i68D1Ld)" class="xpuj8nb6z"/></g><path fill="url(#iqLmNIe)" class="xpuj8nb6z"/><path fill="url(#iqCfezb)" class="xpuj8nb6z"/><path fill="url(#iDzmpNK)" class="xpuj8nb6z"/><path fill="url(#iVMVdFb)" class="xpuj8nb6z"/><path fill="url(#ifHoqde)" class="xpuj8nb6z"/><path fill="url(#iXfSr2c)" class="xpuj8nb6z"/><path fill="url(#ilmxiBe)" class="xpuj8nb6z"/><g filter="url(#iMW32Pe)"><path class="mmwdmikue"/></g><g filter="url(#iGWqgNd)"><path class="sfosyrttf"/><path fill="url(#i9fFsrb)" class="yyv7cinjz"/><path fill="url(#i9xtrNd)" class="yyv7cinjz"/><path fill="url(#iBmBase)" class="yyv7cinjz"/><path fill="url(#ipvTgGb)" class="yyv7cinjz"/></g><g filter="url(#ij03Bbc)"><path stroke="url(#ilSMtsd)" class="fm_6hbcmq"/></g><path fill="url(#idZUWuc)" class="u99k-3bnq"/><g filter="url(#iUfZ2ad)"><path fill="url(#ifG3RUc)" class="or9yo249n"/><path fill="url(#iS4Zc8c)" class="or9yo249n"/><path fill="url(#i3vpzBd)" class="or9yo249n"/><path fill="url(#iwiNmjt)" class="or9yo249n"/><path fill="url(#irrnUob)" class="or9yo249n"/></g><g filter="url(#i78JZ4d)"><path class="udfywo6yp"/></g><g filter="url(#ibqdy1K)"><path class="egno2bpmk"/></g><g filter="url(#iAGbUad)"><path class="jwltybqvo"/><path fill="url(#ijkFnbb)" class="qa5okcb8l"/><path fill="url(#i4vpJYc)" class="qa5okcb8l"/></g><g filter="url(#iD2eQBd)"><path class="gulah3bht"/><path fill="url(#iFjWRxc)" class="hjflrhblb"/><path fill="url(#ikya6Ce)" class="hjflrhblb"/><path fill="url(#iSbIb5d)" class="hjflrhblb"/></g><path class="bkg5o6b7c"/><path fill="url(#iIOqPfe)" class="ogjr3ybit"/><path class="fwn1d6ban"/><g filter="url(#iqopu8b)"><path class="znhmkobyt"/><path fill="url(#iRsiBsc)" class="o9ca1rbly"/></g><g filter="url(#iwngkAQ)"><path fill="url(#i2D5t5b)" class="l5ppblbex"/></g><path class="y_mry0b1e"/><path fill="url(#id4MHDc)" class="ff53v339c"/><path class="ry1017__c"/><g filter="url(#ivEAYll)"><path fill="url(#i81oKie)" class="wcfe57b7x"/></g><g filter="url(#ifQHs5d)"><ellipse transform="rotate(-27.914 12.039 12.908)" class="onr58y6_z"/><ellipse fill="url(#iOxOTcc)" transform="rotate(-27.914 12.039 12.908)" class="ga_27lv1i"/></g><path fill="url(#i8J5kie)" class="fh1utccao"/><path fill="url(#iZ7asPH)" class="fh1utccao"/><path fill="url(#i9JnMdd)" class="fh1utccao"/><path fill="url(#iOoRgNd)" class="fh1utccao"/><path fill="url(#inPiOBd)" class="wd7wq2_2f"/><path fill="url(#i2oFOub)" class="wd7wq2_2f"/><g filter="url(#iLXY7Yd)"><path fill="url(#iWvqZ3c)" class="nnz3nxkjl"/></g><g filter="url(#iKFbiXc)"><path fill="url(#iH0TpQb)" class="srsnk8qqe"/></g><g filter="url(#iRaXFXc)"><path class="kb5k24bhi"/></g><g filter="url(#i7WXDcL)"><path class="c_xo3on6n"/></g><g filter="url(#i4ACFBb)"><path class="n23w61b-j"/></g><g filter="url(#iAFOTpg)"><path class="eoka5cbsn"/></g><g filter="url(#iKo7Cwb)"><path class="v_7f99bff"/></g><g filter="url(#iW44u2d)"><path fill="url(#iW2dKOf)" class="nn3k-5bvh"/><path fill="url(#iQHnbHb)" class="nn3k-5bvh"/><path fill="url(#iKrCERd)" class="nn3k-5bvh"/></g><path fill="url(#ir5gcee)" class="j6v3i5pfv"/><path fill="url(#iiENLMb)" class="j6v3i5pfv"/><path fill="url(#i4Ek4Ac)" class="fyh3hfbdq"/><path fill="url(#iohM4Rd)" class="fyh3hfbdq"/><g filter="url(#ibC9Uic)"><circle fill="url(#iR8uxMd)" class="ml7_kyb_s"/><circle fill="url(#iciclAV)" class="ml7_kyb_s"/><circle fill="url(#i25jirB)" class="ml7_kyb_s"/></g><g filter="url(#i7O3HUd)"><path fill="url(#iuQa4db)" clip-rule="evenodd" class="na5lzp-1y"/></g><path fill="url(#iBn56Eu)" clip-rule="evenodd" class="na5lzp-1y"/><g filter="url(#i24dqBA)"><path fill="url(#iRkMwnb)" clip-rule="evenodd" class="bxwbp5nxx"/></g><g filter="url(#izU7KSd)"><circle stroke="url(#i2ZxCdd)" class="qxi3ubc1y"/></g><g filter="url(#iG66O4d)"><circle stroke="url(#iikDITb)" class="yxquu-boe"/></g><g filter="url(#izzrQSY)"><circle stroke="url(#inK2vrF)" class="nc_p_d7jz"/></g><g filter="url(#iqGy2JI)"><circle stroke="url(#izjDbZd)" class="rhs6usbmd"/></g><defs><radialGradient id="i7EfFab" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.193 14.225)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="qwzbgbcpc"/><stop offset="1" class="yrgygrb-x"/></radialGradient><radialGradient id="iiDcsLd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.382 30.528)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="znj-7lelt"/><stop offset="1" class="w53rld2zh"/></radialGradient><radialGradient id="iNehdOe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.23463 3.91089 -1.18367 -3.09762 12.577 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u-ogyggtr"/><stop offset="1" class="tr4934b7k"/></radialGradient><radialGradient id="iwmeRDE" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.46 30.023)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="pujgjpbud"/><stop offset="1" class="dstba7uva"/></radialGradient><radialGradient id="iv0deVd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.49 29.244)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="teikdvrbz"/><stop offset="1" class="v5czltblq"/></radialGradient><radialGradient id="ijoOoZb" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.49 30.023)" gradientUnits="userSpaceOnUse"><stop class="gbso5obkm"/><stop offset="1" class="x7u0pvbam"/></radialGradient><radialGradient id="i4swUbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.224 30.023)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="ajnorac8k"/><stop offset="1" class="o0jyspbad"/></radialGradient><radialGradient id="iADENae" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -16.6933 7.224 30.023)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="w5_5qkbkk"/><stop offset="1" class="h6pm4_bbg"/></radialGradient><radialGradient id="iY0K1Ub" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.614 19.658)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="m_vu07idg"/><stop offset="1" class="l_wlfwdgx"/><stop offset="1" class="r50sm143n"/></radialGradient><radialGradient id="igUt8Xc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14587 1.92234 -.8326 -.92942 16.683 20.892)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="l4o3wabtp"/><stop offset="1" class="mp7ghebge"/></radialGradient><radialGradient id="iMWtsPd" cx="0" cy="0" r="1" gradientTransform="matrix(.76238 2.05624 -2.44265 .90565 19.377 14.897)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="imVdNmc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5033 .47246 -1.45758 4.63776 8.37 15.396)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="i68D1Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-5.32286 0 0 -9.41608 17.396 13.939)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iqCfezb" cx="0" cy="0" r="1" gradientTransform="scale(10.9826 13.262)rotate(90 .4 .978)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="www4dfogh"/><stop offset="1" class="c0317ln8x"/></radialGradient><radialGradient id="iDzmpNK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16922 1.44691 0 17.029 12.602)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iVMVdFb" cx="0" cy="0" r="1" gradientTransform="matrix(.004 -1.11416 1.21247 .00436 12.195 12.65)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="ifHoqde" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.78 7.757)scale(8.6676 22.1414)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iXfSr2c" cx="0" cy="0" r="1" gradientTransform="matrix(3.15472 -3.33733 1.2217 1.15485 8.97 9.535)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="ilmxiBe" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 6.003 9.23)scale(3.43021 2.83191)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="i9xtrNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24854 -.78112 0 15.012 15.324)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="idZUWuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73383 2.9524 0 14.537 17.542)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iS4Zc8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.56495 9.01536 0 9.212 10.994)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i3vpzBd" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 16.193 -4.031)scale(2.56084 4.5373)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iwiNmjt" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4017 -1.5796 1.1595 -1.76297 18.718 5.938)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="irrnUob" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 2.951 14.323)scale(1.76201 4.07999)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="ijkFnbb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24113 0 0 -.83177 14.795 6.617)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i4vpJYc" cx="0" cy="0" r="1" gradientTransform="matrix(3.27665 -5.18804 5.74781 3.6302 9.008 10.63)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iFjWRxc" cx="0" cy="0" r="1" gradientTransform="matrix(3.11397 0 0 1.21751 18.013 7.408)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="ikya6Ce" cx="0" cy="0" r="1" gradientTransform="matrix(2.7274 -2.59855 4.75729 4.99318 17.219 10.5)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iSbIb5d" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -69.076 144.572)scale(3.32976 1.39411)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iIOqPfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82606 -1.31395 0 16.759 13.006)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iRsiBsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23613 -.30429 .41894 -.3251 16.526 13.092)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="id4MHDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8261 -1.31401 0 12.315 13.006)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iOxOTcc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.524 .696)scale(.50312 .60478)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZ7asPH" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 1.035 19.195)scale(2.37201 2.26308)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="i9JnMdd" cx="0" cy="0" r="1" gradientTransform="matrix(.8021 -1.10075 .92265 .67232 19.606 13.575)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iOoRgNd" cx="0" cy="0" r="1" gradientTransform="matrix(.59766 -1.5786 2.10922 .79856 19.722 13.75)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="i2oFOub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64249 -.20068 .21542 -1.76313 9.532 13.675)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iWvqZ3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.93314 .16016 -.19652 -1.145 9.533 13.676)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iQHnbHb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3158 .70045 -.2958 -.13336 23.327 5.34)" gradientUnits="userSpaceOnUse"><stop offset=".012" class="v2ozkbcky"/><stop offset="1" class="dox6m7bdf"/></radialGradient><radialGradient id="iKrCERd" cx="0" cy="0" r="1" gradientTransform="matrix(3.46255 0 0 1.7869 17.268 7.465)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iR8uxMd" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.666 8.014)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iciclAV" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.68 8.014)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="i25jirB" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.455 7.576)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="iuQa4db" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.483 10.763)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iRkMwnb" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.63 8.94)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="izNAWEd" width="11.406" height="12.766" x="9.382" y="7.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_36" result="effect2_innerShadow_4002_36"/></filter><filter id="iMW32Pe" width="3.778" height="4.953" x="12.503" y="12.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".5"/></filter><filter id="iGWqgNd" width="2.111" height="3.153" x="13.481" y="12.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".05"/></filter><filter id="ij03Bbc" width="3.777" height="1.592" x="12.649" y="16.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".05"/></filter><filter id="iUfZ2ad" width="13.107" height="8.499" x="7.984" y="4.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_36" result="effect2_innerShadow_4002_36"/></filter><filter id="i78JZ4d" width="2.38" height="1.208" x="16.155" y="10.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/></filter><filter id="ibqdy1K" width="2.38" height="1.193" x="10.803" y="10.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/></filter><filter id="iAGbUad" width="6.845" height="6.092" x="8.35" y="5.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/><feGaussianBlur result="effect2_foregroundBlur_4002_36" stdDeviation=".125"/></filter><filter id="iD2eQBd" width="6.473" height="5.836" x="14.375" y="5.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".125"/></filter><filter id="iqopu8b" width=".798" height=".705" x="16.013" y="12.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".05"/></filter><filter id="iwngkAQ" width=".9" height=".923" x="16.87" y="12.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".1"/></filter><filter id="ivEAYll" width=".997" height="1.052" x="12.347" y="12.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".1"/></filter><filter id="ifQHs5d" width=".926" height=".714" x="11.576" y="12.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".05"/></filter><filter id="iLXY7Yd" width="1.344" height="2.413" x="8.35" y="12.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".125"/></filter><filter id="iKFbiXc" width="1.964" height="2.938" x="19.134" y="12.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".25"/></filter><filter id="iRaXFXc" width="2.435" height="1.168" x="10.727" y="10.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".125"/></filter><filter id="i7WXDcL" width="2.435" height="1.168" x="16.103" y="10.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".125"/></filter><filter id="i4ACFBb" width="5.442" height="3.076" x="15.587" y="6.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".375"/></filter><filter id="iAFOTpg" width="5.314" height="3.025" x="15.437" y="6.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".375"/></filter><filter id="iKo7Cwb" width="5.314" height="3.025" x="15.437" y="6.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".375"/></filter><filter id="iW44u2d" width="9.255" height="4.594" x="14.6" y="5.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0745098 0 0 0 0 0.0235294 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/></filter><filter id="ibC9Uic" width=".726" height=".726" x="23.512" y="7.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/></filter><filter id="i7O3HUd" width="3.834" height="4.387" x="21.054" y="8.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_36" result="effect2_innerShadow_4002_36"/></filter><filter id="i24dqBA" width="4.283" height="3.734" x="24.252" y="6.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_36"/></filter><filter id="izU7KSd" width="3.843" height="3.843" x="24.723" y="6.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".1"/></filter><filter id="iG66O4d" width="2.734" height="2.734" x="25.278" y="7.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".1"/></filter><filter id="izzrQSY" width="2.734" height="2.734" x="21.629" y="9.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".1"/></filter><filter id="iqGy2JI" width="3.805" height="3.805" x="21.093" y="8.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_36" stdDeviation=".1"/></filter><linearGradient id="iqLmNIe" x1="19.788" x2="15.356" y1="15.655" y2="15.655" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="i9fFsrb" x1="15.493" x2="14.537" y1="14.645" y2="14.661" gradientUnits="userSpaceOnUse"><stop class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iBmBase" x1="14.537" x2="14.537" y1="15.786" y2="15.312" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="ipvTgGb" x1="14.537" x2="14.537" y1="12.9" y2="13.588" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="ilSMtsd" x1="13.313" x2="13.638" y1="17.385" y2="16.535" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="ifG3RUc" x1="21.514" x2="9.69" y1="8.173" y2="8.173" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="i2D5t5b" x1="17.551" x2="17.231" y1="13.061" y2="13.258" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i81oKie" x1="13.073" x2="12.753" y1="13.061" y2="13.258" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8J5kie" x1="21.09" x2="19.861" y1="13.088" y2="15.304" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="inPiOBd" x1="8.581" x2="10.066" y1="13.805" y2="13.675" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iH0TpQb" x1="20.115" x2="20.115" y1="12.71" y2="14.648" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="iW2dKOf" x1="23.605" x2="17.302" y1="5.645" y2="9.329" gradientUnits="userSpaceOnUse"><stop class="r-a4upbdn"/><stop offset="1" class="q-kinsb7r"/></linearGradient><linearGradient id="ir5gcee" x1="25.035" x2="23.843" y1="5.716" y2="5.371" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iiENLMb" x1="23.887" x2="23.961" y1="7.209" y2="6.92" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="i4Ek4Ac" x1="22.973" x2="23.238" y1="8.065" y2="6.768" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iohM4Rd" x1="24.384" x2="24.186" y1="8.147" y2="8.091" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="iBn56Eu" x1="23.723" x2="23.664" y1="8.237" y2="8.463" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="i2ZxCdd" x1="24.973" x2="28.163" y1="8.839" y2="7.367" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="iikDITb" x1="25.528" x2="27.66" y1="8.717" y2="7.733" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="inK2vrF" x1="21.879" x2="24.011" y1="10.731" y2="9.746" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="izjDbZd" x1="24.648" x2="22.996" y1="9.943" y2="10.484" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-haircut-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.ajnorac8k {
  stop-color: var(--svg-color--e36750, #E36750);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bkg5o6b7c {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.972 12.244c.665 0 1.226.458 1.38 1.078a.28.28 0 0 1-.274.347h-2.271a.234.234 0 0 1-.232-.277a1.42 1.42 0 0 1 1.397-1.149");
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.bxwbp5nxx {
  fill-rule: evenodd;
  d: path("M24.543 7.322a.1.1 0 0 1 .123-.07l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.094a.1.1 0 0 1-.07-.122zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c_xo3on6n {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.163 11.032c-.262-.188-.914-.518-1.685-.389");
}

.c0317ln8x {
  stop-color: var(--svg-color--c9747e, #C9747E);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.co2a3_79n {
  d: path("M9.587 15.211a1.67 1.67 0 0 1-.92-.314v.948c0 .91.541 1.72 1.364 2.056a4.2 4.2 0 0 1-.352-1.202z");
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
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

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.egno2bpmk {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.064 10.794a2.82 2.82 0 0 1 1.77-.366a.282.282 0 1 1-.068.56a2.26 2.26 0 0 0-1.412.29a1 1 0 0 0-.093.061l-.003.002a.282.282 0 0 1-.345-.446z");
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.eoka5cbsn {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M18.784 8.159h-2.108a.489.489 0 1 1 .078-.974c.547.087 1.273.209 1.76.33c1.099.272 1.402.807 1.487 1.189a1.53 1.53 0 0 0-1.217-.545");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.ff53v339c {
  d: path("M12.313 12.52a.91.91 0 0 0-.875 1.148h1.755a1 1 0 0 0 .033-.24a.915.915 0 0 0-.913-.908");
}

.fh1utccao {
  d: path("M19.548 15.304q.102-1.625.188-3.25a1.639 1.639 0 0 1-.188 3.25");
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fm_6hbcmq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.161 16.487c.397.207.87.326 1.376.326c.51 0 .979-.119 1.376-.326a.23.23 0 0 1 .275.045c.065.068.09.177.024.276m-3.05-.32l2.987.278m-2.988-.279a.23.23 0 0 0-.275.047a.215.215 0 0 0-.023.274m.298-.32l-.236.278m3.287.042l-.063-.042m.063.042l-.063-.042m.063.042a2 2 0 0 1-1.675.895c-.703 0-1.32-.358-1.674-.895m3.286-.042a1.93 1.93 0 0 1-1.612.862a1.93 1.93 0 0 1-1.612-.862m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.ft5dv1b6b {
  fill: none;
}

.fwn1d6ban {
  fill: var(--svg-color--000, #000);
  d: path("M16.24 13.429c0-.29.232-.52.52-.52a.518.518 0 0 1 .463.76h-.92a.47.47 0 0 1-.062-.24");
}

.fyh3hfbdq {
  d: path("m19.78 5.888l5.42 1.536l-.338 1.189L20.55 7.39a1.15 1.15 0 0 1-.793-1.42z");
}

.g_fm20xoc {
  fill: var(--svg-color--ff4f19, #FF4F19);
  d: path("M7.224 21.493c-2.273 1.964-3.71 4.85-3.71 8.067v.463h3.71z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.ga_27lv1i {
  cx: 12.039px;
  cy: 12.908px;
  rx: 0.397px;
  ry: 0.201px;
}

.gbso5obkm {
  stop-color: var(--svg-color--ff5130, #FF5130);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gulah3bht {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m19.845 11.547l-.03-.643c-.01-.777-.653-1.418-1.43-1.45h-1.427c-.905 0-1.73-.496-2.162-1.283c0 0-.065-.15-.13-.406c-.249-.972.677-1.713 1.662-1.524c.999.191 2.143.526 2.986 1.077c1.776 1.158 1.466 3.246.53 4.23");
}

.h0e5jkbtm {
  d: path("M12.545 18.643h3.984v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.h6pm4_bbg {
  stop-color: var(--svg-color--ff6640, #FF6640);
  stop-opacity: 0;
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.h7mx9gbgv {
  d: path("M19.487 15.211a1.67 1.67 0 0 0 .92-.314v.948c0 .91-.541 1.72-1.365 2.056a4.2 4.2 0 0 0 .352-1.202z");
}

.hjflrhblb {
  d: path("m19.845 11.547l-.03-.643c-.01-.777-.653-1.418-1.43-1.45h-1.427c-.905 0-1.73-.496-2.162-1.283c0 0-.065-.15-.13-.406c-.249-.972.677-1.713 1.662-1.524c.999.191 2.143.526 2.986 1.077c1.776 1.158 1.466 3.246.53 4.23");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6v3i5pfv {
  d: path("M24.428 3.31L23.04 8.143l1.187.344l1.071-3.729a1.15 1.15 0 0 0-.784-1.421z");
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jwltybqvo {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M14.774 8.221a3 3 0 0 1-.068-.14a.68.68 0 0 0-.626-.425h-1.296c-1.88 0-3.402 1.54-3.402 3.44v.28c-.346-.263-.782-.819-.782-1.718c0-1.091.796-1.643 1.304-1.995c.143-.1.263-.183.336-.258l.102-.106c.356-.378.99-1.05 2.097-1.344a5.6 5.6 0 0 1 1.55-.168c.473.013.806.42.806.894v1.526z");
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kb5k24bhi {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.102 11.079c.262-.188.914-.518 1.686-.389");
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l_wlfwdgx {
  stop-color: var(--svg-color--cc6e65, #CC6E65);
  stop-opacity: 0;
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l4o3wabtp {
  stop-color: var(--svg-color--ffb7a8, #FFB7A8);
}

.l5ppblbex {
  d: path("M17.57 13.31a.86.86 0 0 0-.235-.472l-.265.29l.12.233z");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m_vu07idg {
  stop-color: var(--svg-color--e08380, #E08380);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.ml7_kyb_s {
  cx: 23.825px;
  cy: 7.667px;
  r: 0.313px;
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mmwdmikue {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m14.128 13.405l-.601 1.872c-.103.385.144.77.493.77h.745c.35 0 .596-.39.493-.77l-.503-1.872c-.108-.414-.514-.414-.627 0");
}

.mp7ghebge {
  stop-color: var(--svg-color--ffb7a8, #FFB7A8);
  stop-opacity: 0;
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n23w61b-j {
  fill: var(--svg-color--725050, #725050);
  d: path("M19.021 8.228h-2.178a.505.505 0 1 1 .08-1.006c.566.09 1.316.215 1.819.34c1.136.282 1.45.835 1.538 1.23a1.59 1.59 0 0 0-1.259-.564");
}

.na5lzp-1y {
  fill-rule: evenodd;
  d: path("M23.099 8.11a.1.1 0 0 0-.124.067l-.104.357a.22.22 0 0 1-.174.149a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.101-.349a.1.1 0 0 0-.068-.124zm.74 2.39a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.nc_p_d7jz {
  cx: 22.996px;
  cy: 10.484px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.nn3k-5bvh {
  d: path("M18.542 9.582c3.492-.378 4.732-2.142 4.995-3.103c.055-.17.121-.602 0-.957c-.098-.286-.437-.348-.594.066c-.367.89-1.172 1.305-2.039 1.453s-1.656.227-3.062-.398c-1.004-.447-1.578-.61-2.18-.407s-1.362.87-.94 1.877c.376.898 1.219 1.75 3.82 1.469");
}

.nnz3nxkjl {
  d: path("M9.36 12.719a.973.973 0 0 0 .084 1.913a79 79 0 0 1-.085-1.913");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0jyspbad {
  stop-color: var(--svg-color--e36750, #E36750);
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.o9ca1rbly {
  d: path("M16.694 12.712c.065.087-.07.193-.224.308s-.268.196-.333.109s.007-.25.161-.365s.331-.138.396-.052");
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odzn7sx-f {
  d: path("M21.49 30.023h3.71v-.463c0-3.217-1.437-6.103-3.71-8.067z");
}

.ogjr3ybit {
  d: path("M16.76 12.52a.91.91 0 0 1 .876 1.149h-1.755a.912.912 0 0 1 .88-1.148");
}

.onr58y6_z {
  cx: 12.039px;
  cy: 12.908px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.or9yo249n {
  d: path("M19.48 7.175c.524.18.994.546 1.29 1.07a2.41 2.41 0 0 1-.107 2.573a1.6 1.6 0 0 0-.276.89v1.21a1.8 1.8 0 0 0-.68-.273l.08-1.636a1.476 1.476 0 0 0-1.403-1.458h-1.426a2.47 2.47 0 0 1-2.252-1.47a.68.68 0 0 0-.626-.425h-1.296c-1.88 0-3.402 1.54-3.402 3.44l.03 1.566a1.74 1.74 0 0 0-.732.268v-1.222c0-.317-.098-.628-.276-.89a2.43 2.43 0 0 1-.146-2.49A2.4 2.4 0 0 1 9.582 7.18a2.73 2.73 0 0 0 1.409-1.13a2.37 2.37 0 0 1 2.943-.93c.389.17.826.17 1.215 0a2.366 2.366 0 0 1 2.954.962c.313.519.805.896 1.377 1.092");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pujgjpbud {
  stop-color: var(--svg-color--ff7543, #FF7543);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q-kinsb7r {
  stop-color: var(--svg-color--211025, #211025);
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.qa5okcb8l {
  d: path("M14.774 8.221a3 3 0 0 1-.068-.14a.68.68 0 0 0-.626-.425h-1.296c-1.88 0-3.402 1.54-3.402 3.44v.28c-.346-.263-.782-.819-.782-1.718c0-1.091.796-1.643 1.304-1.995c.143-.1.263-.183.336-.258l.102-.106c.356-.378.99-1.05 2.097-1.344a5.6 5.6 0 0 1 1.55-.168c.473.013.806.42.806.894v1.526z");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwzbgbcpc {
  stop-color: var(--svg-color--ff702c, #FF702C);
}

.qxi3ubc1y {
  cx: 26.645px;
  cy: 8.471px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.r-a4upbdn {
  stop-color: var(--svg-color--211420, #211420);
}

.r1d1-cbgc {
  fill: var(--svg-color--fba89d, #FBA89D);
  d: path("M12.545 18.643h3.984v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.r50sm143n {
  stop-color: var(--svg-color--e08380, #E08380);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rhs6usbmd {
  cx: 22.996px;
  cy: 10.484px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.ry1017__c {
  fill: var(--svg-color--000, #000);
  d: path("M12.834 13.429c0-.29-.232-.52-.52-.52a.518.518 0 0 0-.463.76h.92a.5.5 0 0 0 .063-.24");
}

.sfosyrttf {
  fill: var(--svg-color--eab3a4, #EAB3A4);
  d: path("m14.148 13.211l-.541 1.872c-.11.385.154.77.53.77h.8c.376 0 .64-.391.53-.77l-.54-1.872c-.117-.415-.658-.415-.78 0");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.srsnk8qqe {
  d: path("M19.634 14.648q.059-.968.112-1.938a.973.973 0 0 1-.112 1.938");
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

.teikdvrbz {
  stop-color: var(--svg-color--ff7646, #FF7646);
}

.tr4934b7k {
  stop-color: var(--svg-color--ff5915, #FF5915);
  stop-opacity: 0;
}

.u-ogyggtr {
  stop-color: var(--svg-color--e73f04, #E73F04);
}

.u99k-3bnq {
  d: path("M14.537 16.888a3.06 3.06 0 0 1-1.41-.334c-.14-.071-.29.086-.202.212c.34.517.935.862 1.612.862s1.271-.345 1.612-.862c.088-.131-.062-.283-.201-.212a3.04 3.04 0 0 1-1.411.334");
}

.udfywo6yp {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.338 10.905a1.9 1.9 0 0 0-.7-.419c-.31-.097-.698-.124-1.235-.058a.282.282 0 1 0 .069.56c.49-.06.79-.028.996.037c.202.063.338.166.499.306a.282.282 0 1 0 .37-.426");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.v_7f99bff {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M18.784 8.221h-2.108a.489.489 0 1 1 .078-.973c.547.087 1.273.208 1.76.33c1.099.272 1.402.807 1.487 1.189a1.53 1.53 0 0 0-1.217-.546");
}

.v2ozkbcky {
  stop-color: var(--svg-color--474244, #474244);
}

.v5czltblq {
  stop-color: var(--svg-color--ff6635, #FF6635);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
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

.wcfe57b7x {
  d: path("M13.144 13.322c0-.293-.24-.49-.304-.548l-.293.284l.18.367z");
}

.wd7wq2_2f {
  d: path("M9.401 12.046a1.65 1.65 0 0 0-1.417 1.623c0 .874.685 1.589 1.548 1.636a79 79 0 0 1-.131-3.26");
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.www4dfogh {
  stop-color: var(--svg-color--d69b93, #D69B93);
  stop-opacity: 0;
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x7u0pvbam {
  stop-color: var(--svg-color--ff5130, #FF5130);
  stop-opacity: 0;
}

.xpuj8nb6z {
  d: path("M9.624 16.754a3.99 3.99 0 0 0 3.957 3.468h1.92a3.99 3.99 0 0 0 3.957-3.468c.12-1.918.24-3.828.33-5.745a1.476 1.476 0 0 0-1.404-1.458h-1.426a2.47 2.47 0 0 1-2.252-1.47a.68.68 0 0 0-.626-.425h-1.296c-1.88 0-3.402 1.54-3.402 3.44c0 1.895.118 3.759.242 5.658");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xvnn9-gsy {
  d: path("M3.515 29.56c0-5.916 4.854-10.711 10.842-10.711s10.842 4.795 10.842 10.71v.464H3.515z");
}

.y_mry0b1e {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.103 12.244c-.665 0-1.227.458-1.38 1.078a.28.28 0 0 0 .272.347h2.272c.145 0 .26-.133.232-.277a1.43 1.43 0 0 0-1.397-1.149");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yrgygrb-x {
  stop-color: var(--svg-color--ff521f, #FF521F);
}

.yxquu-boe {
  cx: 26.645px;
  cy: 8.47px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.yyv7cinjz {
  d: path("m14.148 13.211l-.541 1.872c-.11.385.154.77.53.77h.8c.376 0 .64-.391.53-.77l-.54-1.872c-.117-.415-.658-.415-.78 0");
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

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zh3rcwbvd {
  d: path("M7.224 21.493c-2.273 1.964-3.71 4.85-3.71 8.067v.463h3.71z");
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.znhmkobyt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.694 12.712c.065.087-.07.193-.224.308s-.268.196-.333.109s.007-.25.161-.365s.331-.138.396-.052");
}

.znj-7lelt {
  stop-color: var(--svg-color--e65d38, #E65D38);
  stop-opacity: 0;
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
