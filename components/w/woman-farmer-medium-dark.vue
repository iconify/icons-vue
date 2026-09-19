<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVhPJAe)" class="vgp13acjv"/><path fill="url(#i4JfwIc)" class="nk7t055te"/><path fill="url(#i5Fz1Sc)" class="nk7t055te"/><g filter="url(#iD08Kzd)"><path fill="url(#i1KfOGb)" class="jg01emb5z"/><path fill="url(#igWgnga)" class="jg01emb5z"/><path fill="url(#i6Nz10r)" class="jg01emb5z"/></g><g filter="url(#iDksaOb)"><path fill="url(#it7BDpu)" class="yqw0ksymq"/><path fill="url(#iVJ7owb)" class="yqw0ksymq"/></g><g filter="url(#ihXu9ed)"><path fill="url(#iVcIGQd)" class="wz_thqquj"/><path fill="url(#itAthTc)" class="wz_thqquj"/><path fill="url(#iBf8Krb)" class="wz_thqquj"/></g><path class="gh2mqqpxx"/><path fill="url(#iwe3Kmg)" class="vgpxufbov"/><path fill="url(#ig8UJub)" class="htleo0b8f"/><path fill="url(#irkBd2S)" class="htleo0b8f"/><path fill="url(#iohZU6U)" class="jn__lcbtq"/><path fill="url(#iI0suuc)" class="jn__lcbtq"/><g filter="url(#iRdbeFe)"><path fill="url(#iEd7PBb)" class="risgjy0xf"/><path fill="url(#ix63ool)" class="risgjy0xf"/><path fill="url(#iHKsbKd)" class="risgjy0xf"/></g><path fill="url(#irvIgke)" class="risgjy0xf"/><path fill="url(#ii5rdMe)" class="risgjy0xf"/><path fill="url(#iBVm5Oc)" class="jajqy7bqo"/><path fill="url(#iHNRTSd)" class="nneq2rysz"/><path fill="url(#iPF4bxe)" class="rasdvcb-u"/><path fill="url(#iYMPmte)" class="rasdvcb-u"/><path fill="url(#i7oBJ0c)" class="rasdvcb-u"/><path fill="url(#i4Ooe1b)" class="rasdvcb-u"/><path fill="url(#iPwnLId)" class="rasdvcb-u"/><g filter="url(#iNmphvb)"><path class="d_w9f7bcu"/></g><g filter="url(#iwKWRrt)"><path fill="url(#iSGLwOc)" class="cqigqok-i"/></g><path fill="url(#iBPgZnb)" class="a31rudczw"/><path fill="url(#iYPwXti)" class="a31rudczw"/><path fill="url(#ieWxald)" class="alxj77bkd"/><path fill="url(#iaLpsKc)" class="alxj77bkd"/><path fill="url(#ipg7Qcd)" class="cay1xob0i"/><path fill="url(#ilUhkXb)" class="cay1xob0i"/><path fill="url(#i8WcJ1c)" class="cay1xob0i"/><g filter="url(#iomo7Ad)"><path fill="url(#iapiRse)" class="hpa881k4v"/><path fill="url(#ix3GZDb)" class="hpa881k4v"/><path fill="url(#ie6bY2c)" class="hpa881k4v"/><path fill="url(#iT2RD9a)" class="hpa881k4v"/><path fill="url(#iJ35bFo)" class="hpa881k4v"/></g><g filter="url(#idMcRNb)"><path stroke="url(#iwFbRvc)" class="iw54wql7s"/></g><g filter="url(#i4Xt7Vc)"><path stroke="url(#itYAqxb)" class="gkf0rpt_t"/></g><g filter="url(#iaPBqbd)"><path stroke="url(#i0kMxKe)" class="w-8ymjbbv"/></g><path fill="url(#iPN8jLd)" class="xv6j7ob6j"/><path fill="url(#i8WklFb)" class="xv6j7ob6j"/><path fill="url(#iuuGMsb)" class="p4u53gbmi"/><path fill="url(#iTRhG4b)" class="p4u53gbmi"/><path fill="url(#i1bTwoo)" class="p4u53gbmi"/><path fill="url(#i8IgZXf)" class="p4u53gbmi"/><g filter="url(#iRz4voH)"><path fill="url(#iBm9aLu)" class="xwy01jf2w"/></g><g filter="url(#ibLSmSb)"><path fill="url(#iakciQb)" class="h_6xz8bmh"/></g><g filter="url(#iR7wMTc)"><path fill="url(#iI89qWc)" class="gg-nmfbcu"/></g><path fill="url(#i1mDVEe)" class="ka0e4ibgs"/><path fill="url(#iurBd4e)" class="ka0e4ibgs"/><path fill="url(#i7jKRkO)" class="ka0e4ibgs"/><path fill="url(#iXYMHQc)" class="ka0e4ibgs"/><g filter="url(#iXRh68d)"><path stroke="url(#iSQLXDc)" class="xss6_obrr"/></g><path class="vixbh71iy"/><g filter="url(#ihyiQHv)"><path class="q8qwb5a8l"/></g><g filter="url(#ihg54VX)"><path class="gwmfmw92u"/><path fill="url(#iQ1Ghdd)" class="tll_r-d4n"/><path fill="url(#iGZYUDc)" class="tll_r-d4n"/><path fill="url(#irFyH9b)" class="tll_r-d4n"/><path fill="url(#ie8k28b)" class="tll_r-d4n"/><path fill="url(#izvilvd)" class="tll_r-d4n"/></g><g filter="url(#iEIJ0Qc)"><path class="b6r84f9ej"/></g><g filter="url(#id8uW9c)"><path class="vzbqbfpvs"/></g><g filter="url(#i0zeMqc)"><path class="qaj0ubdsz"/></g><g filter="url(#iZ8KV2d)"><path class="pq7aqs9uc"/></g><path class="yulcvlb7w"/><path fill="url(#id8RKnd)" class="wrh5gf7sp"/><path class="k53ajib4z"/><g filter="url(#iD7pKNJ)"><path class="hco52q6ov"/><path fill="url(#iu4jHKe)" class="v-a9gpbbb"/></g><g filter="url(#i7Fgp0c)"><path fill="url(#i0rc9Lb)" class="a2y3-in1d"/></g><path class="rai0zqn2p"/><path fill="url(#ioP90mc)" class="b-m00outt"/><path class="rv46g1-_t"/><g filter="url(#iUfr2Fd)"><path fill="url(#iBolUUc)" class="l-dl4ub-f"/></g><g filter="url(#iOcWrkd)"><ellipse transform="rotate(-27.914 13.678 9.999)" class="zud63o6bh"/><ellipse fill="url(#iF8jxPd)" transform="rotate(-27.914 13.678 9.999)" class="v2mqqvb8m"/></g><g filter="url(#iDuCXic)"><path class="gw92q-74l"/></g><g filter="url(#iD2Ir4m)"><path class="h24qorb_i"/></g><g filter="url(#iAr5B6b)"><path fill="url(#ijEw2Vb)" class="f1d4-238i"/></g><g filter="url(#iNh3Jbb)"><path class="cz1ep8brj"/></g><defs><radialGradient id="iVhPJAe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.886 3.95)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="i4JfwIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.761 5.112)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="igWgnga" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.642 3.89)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="i6Nz10r" cx="0" cy="0" r="1" gradientTransform="matrix(5.40207 -4.875 3.36264 3.7262 16.068 10.125)" gradientUnits="userSpaceOnUse"><stop class="s0qpik8kr"/><stop offset="1" class="y2pqqr5ks"/></radialGradient><radialGradient id="it7BDpu" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -6.4375 7.87502 2.0261 19.564 16.362)" gradientUnits="userSpaceOnUse"><stop class="vz8fcrkfe"/><stop offset="1" class="rbuuvqb-n"/></radialGradient><radialGradient id="iVJ7owb" cx="0" cy="0" r="1" gradientTransform="matrix(2.76563 -.5625 .27296 1.34206 22.126 11.136)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="itAthTc" cx="0" cy="0" r="1" gradientTransform="rotate(106.741 2.045 7.448)scale(6.18397 1.94761)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="qxarokbzg"/><stop offset="1" class="jn8004cwc"/></radialGradient><radialGradient id="iBf8Krb" cx="0" cy="0" r="1" gradientTransform="rotate(-46.106 17.02 -8.674)scale(2.86211 1.6392)" gradientUnits="userSpaceOnUse"><stop class="cwohembfi"/><stop offset="1" class="ml-iambtc"/></radialGradient><radialGradient id="iwe3Kmg" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.998 16.275)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="irkBd2S" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.855 25.237)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iI0suuc" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 23.028 24.7)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="du4i2cruh"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="iEd7PBb" cx="0" cy="0" r="1" gradientTransform="scale(3.73669 5.49005)rotate(90 .68 3.62)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iHKsbKd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.213 19.542)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="ii5rdMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.461 15.96)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iBVm5Oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.988 19.642)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iHNRTSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.2121 -3.45057 0 15.986 16.23)" gradientUnits="userSpaceOnUse"><stop class="o-v48ln2d"/><stop offset=".453" class="zh1uzn9mk"/><stop offset=".898" class="cmxshaccl"/></radialGradient><radialGradient id="iYMPmte" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.566 11.788)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iPwnLId" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 9.008 18.8)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iBPgZnb" cx="0" cy="0" r="1" gradientTransform="rotate(140.585 9.664 16.869)scale(2.13884 2.10129)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="iYPwXti" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .3134 .41161 27.597 23.608)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iaLpsKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.181 24.76)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="ipg7Qcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.205 21.581)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="ilUhkXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.706 21.964)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="ix3GZDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.96 25.275)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ie6bY2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.96 26.57)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iT2RD9a" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.96 27.82)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iJ35bFo" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.96 29.17)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i8WklFb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50891 0 0 -2.43976 12.934 10.896)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="srn41o2oz"/><stop offset=".972" class="dfc36bbxx"/></radialGradient><radialGradient id="iTRhG4b" cx="0" cy="0" r="1" gradientTransform="rotate(58.678 .188 21.667)scale(3.02098 4.85718)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="i1bTwoo" cx="0" cy="0" r="1" gradientTransform="matrix(1.67404 -1.09021 .87798 1.34816 19.365 10.792)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i8IgZXf" cx="0" cy="0" r="1" gradientTransform="matrix(1.24738 -1.56349 3.07552 2.4537 19.607 10.966)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iakciQb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3752 .17984 -.08325 -1.09945 12.645 10.896)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iI89qWc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 2.63281 -4.19257 -9.35552 19.095 9.604)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="g4fbw0x4u"/><stop offset="1" class="unjk-_bvf"/></radialGradient><radialGradient id="i1mDVEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.87488 -8.98026 0 16.076 7.74)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="p83w8pblc"/><stop offset="1" class="q0lvpmb3p"/></radialGradient><radialGradient id="iurBd4e" cx="0" cy="0" r="1" gradientTransform="matrix(1.39286 -.8314 .61148 1.02443 18.202 9.72)" gradientUnits="userSpaceOnUse"><stop class="zu3-ihdlo"/><stop offset="1" class="kmnl2yo_y"/></radialGradient><radialGradient id="i7jKRkO" cx="0" cy="0" r="1" gradientTransform="rotate(-118.968 9.728 .698)scale(1.38223 1.08515)" gradientUnits="userSpaceOnUse"><stop class="n3eomub5r"/><stop offset="1" class="x3em5kbsd"/></radialGradient><radialGradient id="iXYMHQc" cx="0" cy="0" r="1" gradientTransform="matrix(3.06437 -2.57641 .74788 .88953 11.396 8.018)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="m_e25s40e"/><stop offset="1" class="z000vd5kc"/></radialGradient><radialGradient id="iGZYUDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21614 -.73448 0 16.562 12.237)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="ie8k28b" cx="0" cy="0" r="1" gradientTransform="rotate(157.021 7.144 7.56)scale(1.58183 2.41168)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="id8RKnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.213 10.095)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iu4jHKe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.485 .685)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ioP90mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.95 10.095)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iF8jxPd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.663 10.314)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iD08Kzd" width="20.537" height="10.328" x="5.549" y="4.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1805" result="effect2_innerShadow_4002_1805"/></filter><filter id="iDksaOb" width="9.49" height="10.956" x="14.103" y="6.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0156863 0 0 0 0 0.0431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="ihXu9ed" width="6.144" height="10.985" x="8.643" y="6.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.164706 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1805" result="effect2_innerShadow_4002_1805"/></filter><filter id="iRdbeFe" width="8" height="6.44" x="12.068" y="15.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="iNmphvb" width="8.45" height="4.612" x="11.798" y="25.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".125"/></filter><filter id="iwKWRrt" width="8.05" height="4.28" x="11.948" y="25.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="iomo7Ad" width="4.468" height="5.556" x="23.522" y="24.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="idMcRNb" width="2.097" height=".3" x="23.893" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".05"/></filter><filter id="i4Xt7Vc" width="2.097" height=".3" x="23.814" y="27.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".05"/></filter><filter id="iaPBqbd" width="2.097" height=".3" x="23.893" y="28.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".05"/></filter><filter id="iRz4voH" width="3.148" height="3.148" x="19.281" y="9.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".25"/></filter><filter id="ibLSmSb" width="2.648" height="2.648" x="10.02" y="9.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".125"/></filter><filter id="iR7wMTc" width="10.425" height="9.709" x="11.164" y="6.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545016 0 0 0 0 0.393721 0 0 0 0 0.368505 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="iXRh68d" width="3.685" height="1.517" x="14.241" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".05"/></filter><filter id="ihyiQHv" width="3.797" height="4.568" x="13.99" y="9.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".5"/></filter><filter id="ihg54VX" width="2.197" height="2.968" x="15.017" y="9.929" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".1"/></filter><filter id="iEIJ0Qc" width="2.247" height="1.019" x="12.317" y="7.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="id8uW9c" width="2.237" height="1.009" x="17.643" y="7.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="i0zeMqc" width="3.001" height="1.285" x="17.173" y="9.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="iZ8KV2d" width="3.001" height="1.285" x="12.189" y="9.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/></filter><filter id="iD7pKNJ" width=".786" height=".696" x="17.479" y="9.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".05"/></filter><filter id="i7Fgp0c" width=".891" height=".913" x="18.319" y="9.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".1"/></filter><filter id="iUfr2Fd" width=".986" height="1.04" x="13.977" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".1"/></filter><filter id="iOcWrkd" width=".912" height=".704" x="13.222" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".05"/></filter><filter id="iDuCXic" width="2.132" height=".75" x="17.729" y="8.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".075"/></filter><filter id="iD2Ir4m" width="2.132" height=".75" x="12.37" y="8.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".075"/></filter><filter id="iAr5B6b" width="5.819" height=".998" x="15.739" y="6.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1805" stdDeviation=".075"/></filter><filter id="iNh3Jbb" width="7.625" height="9.853" x="21.921" y="10.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1805"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1805" result="effect2_innerShadow_4002_1805"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1805" result="effect3_innerShadow_4002_1805"/></filter><linearGradient id="i5Fz1Sc" x1="15.988" x2="15.988" y1="4" y2="4.054" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="i1KfOGb" x1="16.068" x2="16.068" y1="4.8" y2="14.831" gradientUnits="userSpaceOnUse"><stop class="q09ymmbwb"/><stop offset=".842" class="jpvx63ldj"/></linearGradient><linearGradient id="iVcIGQd" x1="11.59" x2="11.59" y1="6.986" y2="17.721" gradientUnits="userSpaceOnUse"><stop class="x5dyrqz_l"/><stop offset="1" class="xuadj21pj"/></linearGradient><linearGradient id="ig8UJub" x1="9.008" x2="5.418" y1="28.425" y2="28.425" gradientUnits="userSpaceOnUse"><stop class="rhalidc9f"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iohZU6U" x1="26.571" x2="23.028" y1="22.854" y2="29.16" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="ix63ool" x1="20.068" x2="19.133" y1="18.487" y2="18.487" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="irvIgke" x1="12.068" x2="12.402" y1="18.487" y2="18.487" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iPF4bxe" x1="17.23" x2="15.283" y1="29.112" y2="19.948" gradientUnits="userSpaceOnUse"><stop class="ym265mvaz"/><stop offset="1" class="k0c3dfbas"/></linearGradient><linearGradient id="i7oBJ0c" x1="23.082" x2="22.855" y1="29.643" y2="29.643" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="i4Ooe1b" x1="9.008" x2="9.132" y1="29.643" y2="29.643" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="iSGLwOc" x1="13.855" x2="20.386" y1="28.331" y2="28.331" gradientUnits="userSpaceOnUse"><stop class="tbsuik4az"/><stop offset="1" class="mkeehnh5k"/></linearGradient><linearGradient id="ieWxald" x1="25.678" x2="25.678" y1="21.581" y2="24.76" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="i8WcJ1c" x1="25.706" x2="25.706" y1="22.284" y2="21.69" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="iapiRse" x1="27.55" x2="23.522" y1="28.033" y2="28.033" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iwFbRvc" x1="24.043" x2="25.752" y1="26.026" y2="26.026" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="itYAqxb" x1="23.964" x2="25.674" y1="27.331" y2="27.331" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i0kMxKe" x1="24.043" x2="25.752" y1="28.636" y2="28.636" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iPN8jLd" x1="10.957" x2="13.964" y1="11.027" y2="10.473" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iuuGMsb" x1="22.464" x2="21.758" y1="10.311" y2="12.994" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iBm9aLu" x1="20.855" x2="20.855" y1="9.822" y2="11.97" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iSQLXDc" x1="14.857" x2="15.193" y1="14.063" y2="13.198" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iQ1Ghdd" x1="16.918" x2="16.116" y1="11.63" y2="11.666" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="irFyH9b" x1="16.116" x2="16.116" y1="12.639" y2="12.227" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="izvilvd" x1="16.116" x2="16.116" y1="10.243" y2="10.727" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="i0rc9Lb" x1="18.991" x2="18.677" y1="10.148" y2="10.341" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBolUUc" x1="14.693" x2="14.38" y1="10.148" y2="10.341" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijEw2Vb" x1="19.545" x2="16.42" y1="6.964" y2="8.511" gradientUnits="userSpaceOnUse"><stop class="urzuj9che"/><stop offset="1" class="ev34ly_6u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-farmer-medium-dark" /></template>
<style>
.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.a2y3-in1d {
  d: path("M19.01 10.392a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.a31rudczw {
  d: path("M26.84 23.11c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.alxj77bkd {
  d: path("M26.181 21.76h-1v3h1z");
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.b-m00outt {
  d: path("M13.948 9.618a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.b6r84f9ej {
  fill: var(--svg-color--130e18, #130E18);
  d: path("M12.585 8.866a.26.26 0 0 1-.231-.135a.27.27 0 0 1 .096-.366c.039-.02.895-.51 1.896-.327a.26.26 0 0 1 .212.308c-.029.154-.163.25-.308.221c-.809-.144-1.53.26-1.53.26a.24.24 0 0 1-.135.039");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.cay1xob0i {
  d: path("M24.945 19.98h1.523v1.734a.25.25 0 0 1-.25.25h-1.023a.25.25 0 0 1-.25-.25z");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmxshaccl {
  stop-color: var(--svg-color--41221c, #41221C);
}

.cqigqok-i {
  d: path("M19.488 25.8h-6.94c-.28 0-.5.22-.5.5v3.68h7.95V26.3a.517.517 0 0 0-.51-.5");
}

.cwohembfi {
  stop-color: var(--svg-color--040102, #040102);
}

.cz1ep8brj {
  fill: var(--svg-color--b8b1c0, #B8B1C0);
  d: path("M22.823 11.034a.6.6 0 0 0-.602.602v6.851a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.851a.602.602 0 0 0-1.203 0v4.449a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.601-.6");
}

.d_w9f7bcu {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.488 25.8h-6.94c-.28 0-.5.217-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.du4i2cruh {
  stop-color: var(--svg-color--2aaa64, #2AAA64);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.ev34ly_6u {
  stop-color: var(--svg-color--4c4649, #4C4649);
  stop-opacity: 0;
}

.f1d4-238i {
  d: path("M19.475 7.081c1.237.056 1.561.238 1.933.453c-.31-.15-1.346-.375-2.777-.062c-1.431.312-2.424.172-2.742.062l.14-.57c1.5.453 1.899.047 3.446.117");
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g4fbw0x4u {
  stop-color: var(--svg-color--946858, #946858);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gg-nmfbcu {
  d: path("M19.412 7.988h-2.619c-1.38 0-2.044-.559-2.628-1.082c0 0-.927.04-1.259.1c-.215.234-.443.531-.977.886c-.23.116-.756.527-.765 1.46l.063 2.594c.106 2.801 2.262 4.669 4.88 4.669c2.62 0 4.766-1.868 4.881-4.669V9.443c0-1.34-1.393-1.455-1.576-1.455");
}

.gh2mqqpxx {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.998 15.49c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.gkf0rpt_t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.964 27.253h1.797");
}

.gw92q-74l {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.929 8.25c.236-.1 1.324 0 1.732.312");
}

.gwmfmw92u {
  fill: var(--svg-color--795147, #795147);
  d: path("m15.742 10.396l-.5 1.627a.518.518 0 0 0 .5.674h.751a.526.526 0 0 0 .5-.674l-.5-1.627c-.135-.356-.645-.356-.75 0");
}

.h_6xz8bmh {
  d: path("M11.344 11.97a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.h24qorb_i {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.303 8.25c-.237-.1-1.325 0-1.733.312");
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hco52q6ov {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.149 9.807c.063.085-.07.188-.22.301c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.324-.135.388-.05");
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hpa881k4v {
  d: path("M23.522 25.296c0-.401.326-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.htleo0b8f {
  d: path("M9.008 29.97V18h-.006a10.95 10.95 0 0 0-3.994 8.47v3.5z");
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.iw54wql7s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.043 25.948h1.796");
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.jajqy7bqo {
  d: path("m16.918 19.68l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.jg01emb5z {
  d: path("M11.632 4.8c-.85.031-2.678.229-4.102 1.336c-1.238.962-1.477 2.117-1.477 3.086v.476c-.093 1.781 1.446 4.93 6.883 4.93H19.2c5.437 0 6.976-3.149 6.883-4.93v-.476c0-.97-.24-2.124-1.477-3.086c-1.423-1.107-3.252-1.305-4.101-1.336z");
}

.jn__lcbtq {
  d: path("M23.028 29.97V18h.007a10.95 10.95 0 0 1 3.993 8.47v3.5z");
}

.jn8004cwc {
  stop-color: var(--svg-color--423735, #423735);
  stop-opacity: 0;
}

.jpvx63ldj {
  stop-color: var(--svg-color--734b50, #734B50);
}

.k0c3dfbas {
  stop-color: var(--svg-color--309edd, #309EDD);
}

.k53ajib4z {
  fill: var(--svg-color--000, #000);
  d: path("M17.704 10.51c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.ka0e4ibgs {
  d: path("M19.412 7.988h-2.619c-1.38 0-2.044-.559-2.628-1.082c0 0-.86.04-1.259.1c-.215.234-.443.531-.977.886c-.23.116-.756.527-.765 1.46l.063 2.594c.106 2.801 2.262 4.669 4.88 4.669c2.62 0 4.766-1.868 4.881-4.669V9.443c0-1.34-1.393-1.455-1.576-1.455");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kmnl2yo_y {
  stop-color: var(--svg-color--865651, #865651);
  stop-opacity: 0;
}

.l-dl4ub-f {
  d: path("M14.763 10.405c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
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

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m_e25s40e {
  stop-color: var(--svg-color--552a2b, #552A2B);
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

.mkeehnh5k {
  stop-color: var(--svg-color--319ce4, #319CE4);
}

.ml-iambtc {
  stop-color: var(--svg-color--040102, #040102);
  stop-opacity: 0;
}

.mo7a9nshu {
  stop-color: var(--svg-color--28659f, #28659F);
  stop-opacity: 0;
}

.n3eomub5r {
  stop-color: var(--svg-color--724650, #724650);
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nk7t055te {
  d: path("m10.168 5.54l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.nneq2rysz {
  d: path("M15.988 18.65c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.o-v48ln2d {
  stop-color: var(--svg-color--69424f, #69424F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.p4u53gbmi {
  d: path("M20.855 12.505a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.p83w8pblc {
  stop-color: var(--svg-color--754756, #754756);
  stop-opacity: 0;
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pq7aqs9uc {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M14.99 10.123c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.6l.556.316c.652-.21 1.373-.239 2.079-.45");
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q09ymmbwb {
  stop-color: var(--svg-color--66404e, #66404E);
}

.q0lvpmb3p {
  stop-color: var(--svg-color--5f373c, #5F373C);
}

.q8qwb5a8l {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.515 10.622l-.5 1.627a.518.518 0 0 0 .5.674h.75a.526.526 0 0 0 .501-.674l-.5-1.627c-.135-.356-.645-.356-.751 0");
}

.qaj0ubdsz {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M17.173 10.123c.266-.467.67-.836 1.538-.836c.38 0 .747.105 1.073.369c.268.217.232.495.024.6l-.556.316c-.652-.21-1.372-.239-2.079-.45");
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

.qxarokbzg {
  stop-color: var(--svg-color--423735, #423735);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rai0zqn2p {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.74 9.346c-.652 0-1.204.45-1.354 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.rasdvcb-u {
  d: path("M23.028 18.03c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.rbuuvqb-n {
  stop-color: var(--svg-color--1e1723, #1E1723);
}

.rhalidc9f {
  stop-color: var(--svg-color--3d935b, #3D935B);
}

.risgjy0xf {
  d: path("m13.032 21.464l3.036-2.124l2.987 2.085c.421.324 1.013.465 1.013-.355v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .953.594.823.964.563");
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.rv46g1-_t {
  fill: var(--svg-color--000, #000);
  d: path("M14.459 10.51a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.s0qpik8kr {
  stop-color: var(--svg-color--4c2524, #4C2524);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tbsuik4az {
  stop-color: var(--svg-color--36a9f3, #36A9F3);
}

.tll_r-d4n {
  d: path("m15.742 10.396l-.5 1.627a.518.518 0 0 0 .5.674h.751a.526.526 0 0 0 .5-.674l-.5-1.627c-.135-.356-.645-.356-.75 0");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.unjk-_bvf {
  stop-color: var(--svg-color--744b4b, #744B4B);
}

.urzuj9che {
  stop-color: var(--svg-color--4c4649, #4C4649);
}

.v-a9gpbbb {
  d: path("M18.149 9.807c.063.085-.07.188-.22.301c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.324-.135.388-.05");
}

.v2mqqvb8m {
  cx: 13.678px;
  cy: 9.999px;
  rx: 0.389px;
  ry: 0.197px;
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vgp13acjv {
  d: path("M21.988 5.9h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.vgpxufbov {
  d: path("M15.998 15.49c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.vixbh71iy {
  fill: var(--svg-color--87024e, #87024E);
  d: path("M16.083 13.55a3.1 3.1 0 0 1-1.415-.336c-.135-.077-.289.086-.202.221c.347.53.934.876 1.617.876c.684 0 1.27-.347 1.617-.876c.087-.135-.067-.289-.202-.221a3.1 3.1 0 0 1-1.415.336");
}

.vz8fcrkfe {
  stop-color: var(--svg-color--131720, #131720);
}

.vzbqbfpvs {
  fill: var(--svg-color--130e18, #130E18);
  d: path("M19.622 8.866a.24.24 0 0 1-.135-.039c-.01 0-.732-.414-1.53-.26a.26.26 0 0 1-.309-.211a.26.26 0 0 1 .212-.308c.991-.183 1.858.308 1.887.327c.125.077.173.24.096.366a.24.24 0 0 1-.221.125");
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-8ymjbbv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.043 28.558h1.796");
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
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

.wrh5gf7sp {
  d: path("M18.215 9.618a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.wz_thqquj {
  d: path("M10.57 7.54c.976-.499 2.222-.544 2.648-.554l-.513 4.653l1.832 4.33l-2.608 1.752c-3.585-.735-3.348-3.564-3.137-4.355c.222-.831.028-1.02-.085-1.788c-.272-1.833.329-3.255 1.863-4.038");
}

.x3em5kbsd {
  stop-color: var(--svg-color--724650, #724650);
  stop-opacity: 0;
}

.x5dyrqz_l {
  stop-color: var(--svg-color--1f171b, #1F171B);
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xss6_obrr {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.424 13.462c.355.543.958.899 1.66.899c.7 0 1.303-.356 1.658-.899a.2.2 0 0 0-.023-.248a.21.21 0 0 0-.243-.045a3.1 3.1 0 0 1-1.393.332a3.05 3.05 0 0 1-1.391-.331a.2.2 0 0 0-.245.04a.2.2 0 0 0-.023.252Z");
}

.xuadj21pj {
  stop-color: var(--svg-color--18111b, #18111B);
}

.xv6j7ob6j {
  d: path("M11.325 12.505a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.xwy01jf2w {
  d: path("M20.855 11.97a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.y2pqqr5ks {
  stop-color: var(--svg-color--4c2524, #4C2524);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
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

.ym265mvaz {
  stop-color: var(--svg-color--2d5ca0, #2D5CA0);
}

.yqw0ksymq {
  d: path("M16.904 8.003c-1.715 0-2.526-.732-2.801-1.097c.836.026 2.457 0 4.583 0c2.66 0 4.351 1.047 4.704 2.97c.256 1.647-.242 2.69-.121 3.173c.12.483.564 1.762-.282 3.01c-.677 1-2.108 1.552-2.74 1.703h-2.185v-1.853c2.367-.726 2.32-3.001 2.37-3.213c.05-.211.422-1.94.297-3.337c-.096-1.072-.788-1.325-1.298-1.302c-.205 0-1.004-.054-2.527-.054");
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yulcvlb7w {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.422 9.346c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.z000vd5kc {
  stop-color: var(--svg-color--552a2b, #552A2B);
  stop-opacity: 0;
}

.zh1uzn9mk {
  stop-color: var(--svg-color--6d484c, #6D484C);
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zjnvspbhz {
  stop-color: var(--svg-color--28659f, #28659F);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zu3-ihdlo {
  stop-color: var(--svg-color--865651, #865651);
}

.zud63o6bh {
  cx: 13.678px;
  cy: 9.999px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

</style>
