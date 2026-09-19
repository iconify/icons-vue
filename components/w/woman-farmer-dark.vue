<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iOOx61b)" class="s5u5n3uga"/><path fill="url(#iN1LNNe)" class="orgagwc6f"/><path fill="url(#i1fQoHc)" class="orgagwc6f"/><g filter="url(#iDJ2YyO)"><path fill="url(#iBk8Ytd)" class="il0ne-blx"/><path fill="url(#iajsMGb)" class="il0ne-blx"/><path fill="url(#i7tIlVc)" class="il0ne-blx"/></g><g filter="url(#i9Bzqpc)"><path fill="url(#iylUfxd)" class="rsy33bcvg"/><path fill="url(#it8cqWw)" class="rsy33bcvg"/></g><g filter="url(#i4V9snc)"><path fill="url(#iEwrR1d)" class="m0229f9ub"/><path fill="url(#iSsELmi)" class="m0229f9ub"/><path fill="url(#iJhZbNe)" class="m0229f9ub"/></g><path class="xef0asb0e"/><path fill="url(#iYyvmid)" class="jsvx11bfo"/><path fill="url(#iX1oKSd)" class="fczuqnb-f"/><path fill="url(#i3Q97pd)" class="fczuqnb-f"/><path fill="url(#iuRo1Hb)" class="czvb3pcge"/><path fill="url(#iVxWFLd)" class="czvb3pcge"/><g filter="url(#iL45KAe)"><path fill="url(#iBfU4fu)" class="wfyrgzbul"/><path fill="url(#iekLMae)" class="wfyrgzbul"/><path fill="url(#iVQgDNd)" class="wfyrgzbul"/></g><path fill="url(#ikCB4Qb)" class="wfyrgzbul"/><path fill="url(#iQvfl8b)" class="wfyrgzbul"/><path fill="url(#iamAcrc)" class="s-6nccc6b"/><path fill="url(#idtC4cd)" class="rkz79qbai"/><path fill="url(#izTK9RF)" class="dtlh2rbzn"/><path fill="url(#iJoodxe)" class="dtlh2rbzn"/><path fill="url(#i44g1vd)" class="dtlh2rbzn"/><path fill="url(#ipzx8Fc)" class="dtlh2rbzn"/><path fill="url(#izYXi5d)" class="dtlh2rbzn"/><g filter="url(#iZSMmYc)"><path class="ye4fst04c"/></g><g filter="url(#it5gKNd)"><path fill="url(#i1YDhod)" class="tjidt244a"/></g><path fill="url(#i4jlZBw)" class="k4228ccdd"/><path fill="url(#iYippzd)" class="k4228ccdd"/><path fill="url(#iHPokje)" class="k926-qmtm"/><path fill="url(#iS6OFpe)" class="k926-qmtm"/><path fill="url(#iXbpW4c)" class="uksji80jn"/><path fill="url(#ibm40wc)" class="uksji80jn"/><path fill="url(#iKewWrp)" class="uksji80jn"/><g filter="url(#if9jtib)"><path fill="url(#i4cMnfb)" class="z9jip3bmj"/><path fill="url(#ioDaFQb)" class="z9jip3bmj"/><path fill="url(#iREZKom)" class="z9jip3bmj"/><path fill="url(#iaTfJDd)" class="z9jip3bmj"/><path fill="url(#iya9H8d)" class="z9jip3bmj"/></g><g filter="url(#iH8hoXc)"><path stroke="url(#i0iYawc)" class="pfc_pmbyf"/></g><g filter="url(#iqDrKFb)"><path stroke="url(#ilGWpIb)" class="ohwoq2oew"/></g><g filter="url(#ij6ceQb)"><path stroke="url(#iIt88iU)" class="e92d_8btk"/></g><g filter="url(#i6DGDab)"><path fill="url(#iQIfGPb)" class="ejv89abvn"/><path fill="url(#ixnFxhe)" class="ejv89abvn"/></g><path fill="url(#iras6ge)" class="zybyg0bhb"/><path fill="url(#ix1wTGc)" class="zybyg0bhb"/><path fill="url(#ilENXzc)" class="zybyg0bhb"/><path fill="url(#iEDDOsd)" class="zybyg0bhb"/><g filter="url(#iiNPbzc)"><path fill="url(#i68hKrZ)" class="b6hcm7htr"/></g><g filter="url(#iYpLbLp)"><path fill="url(#iPPfeib)" class="bfwlxiojl"/></g><g filter="url(#itbysgd)"><path fill="url(#iRlu9Qb)" class="dollalbrw"/></g><path fill="url(#ij20MHb)" class="cgcgm4b2g"/><path fill="url(#iGGNqac)" class="cgcgm4b2g"/><path fill="url(#iNzLsYd)" class="cgcgm4b2g"/><path fill="url(#ir92FZR)" class="cgcgm4b2g"/><g filter="url(#iXfkq4c)"><path stroke="url(#iGCR53d)" class="f6nr-db5g"/></g><path class="wox7jpdoy"/><g filter="url(#iAG2r6d)"><path class="wshud2bbh"/><path fill="url(#iqgavTc)" class="qzqvrt_vg"/><path fill="url(#i2mTo1c)" class="qzqvrt_vg"/><path fill="url(#itrwhjc)" class="qzqvrt_vg"/><path fill="url(#i3F0Lvc)" class="qzqvrt_vg"/><path fill="url(#iyGClbd)" class="qzqvrt_vg"/></g><g filter="url(#i5cNnJe)"><path class="c93nmcmgn"/><path fill="url(#i43UeZb)" class="euhgmbb6c"/><path fill="url(#i699LJb)" class="euhgmbb6c"/><path fill="url(#i4MCe1c)" class="euhgmbb6c"/><path fill="url(#iTAlNNb)" class="euhgmbb6c"/><path fill="url(#ifGalXi)" class="euhgmbb6c"/><path fill="url(#iK9pq0v)" class="euhgmbb6c"/></g><g filter="url(#iHsFNsb)"><path class="l6a8ijbda"/></g><g filter="url(#iUpminc)"><path class="bkq68w2iz"/></g><g filter="url(#ioUOicb)"><path class="n68hknr5p"/></g><g filter="url(#icFNu9b)"><path class="ov6bqegoe"/></g><path class="pj_ifb3co"/><path fill="url(#i4uD2Hb)" class="yjs-mabtr"/><path class="gogld2b5i"/><g filter="url(#iECGz9c)"><path class="baw9f51yc"/><path fill="url(#iBV1Fcb)" class="goe-kzizj"/></g><g filter="url(#iSHQn0n)"><path fill="url(#iFHfsab)" class="z13m-02be"/></g><path class="z1au5gx5t"/><path fill="url(#itAASje)" class="l4an7ueku"/><path class="hy21rybwg"/><g filter="url(#iZGFfzO)"><path fill="url(#iedKKLe)" class="sfnrybc4v"/></g><g filter="url(#i72FcNS)"><ellipse transform="rotate(-27.914 13.635 10.008)" class="f2azchbek"/><ellipse fill="url(#iNdDLkD)" transform="rotate(-27.914 13.635 10.008)" class="of44kubsp"/></g><g filter="url(#iB9hZAe)"><path class="f9838hogy"/></g><g filter="url(#impuPQb)"><path class="qruo7srzx"/></g><g filter="url(#iL58RUb)"><path fill="url(#ibgAPkc)" class="n-8ovyb_a"/></g><g filter="url(#iTiMT3c)"><path class="snrf6qg2y"/></g><defs><radialGradient id="iOOx61b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.843 3.96)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iN1LNNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.718 5.122)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="iajsMGb" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.623 3.909)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="i7tIlVc" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 -4.6875 9.21336 .85992 17.552 8.833)" gradientUnits="userSpaceOnUse"><stop class="qv86iobue"/><stop offset="1" class="b2_83-3sv"/></radialGradient><radialGradient id="iylUfxd" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -6.4375 7.87502 2.0261 19.52 16.372)" gradientUnits="userSpaceOnUse"><stop class="vz8fcrkfe"/><stop offset="1" class="rbuuvqb-n"/></radialGradient><radialGradient id="it8cqWw" cx="0" cy="0" r="1" gradientTransform="matrix(2.76562 -.56252 .27297 1.34206 22.084 11.146)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iSsELmi" cx="0" cy="0" r="1" gradientTransform="rotate(106.741 2.02 7.437)scale(6.18397 1.94761)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="qxarokbzg"/><stop offset="1" class="jn8004cwc"/></radialGradient><radialGradient id="iJhZbNe" cx="0" cy="0" r="1" gradientTransform="rotate(-46.106 17.009 -8.618)scale(2.86211 1.6392)" gradientUnits="userSpaceOnUse"><stop class="cwohembfi"/><stop offset="1" class="ml-iambtc"/></radialGradient><radialGradient id="iYyvmid" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.954 16.285)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="i3Q97pd" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.812 25.247)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iVxWFLd" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.985 24.71)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="du4i2cruh"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="iBfU4fu" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16.024 16.153)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iVQgDNd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.17 19.551)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iQvfl8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.418 15.97)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iamAcrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.945 19.652)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="idtC4cd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09482 -5.3522 0 16.633 16.575)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="rifopebvv"/><stop offset="1" class="r8q177bio"/></radialGradient><radialGradient id="iJoodxe" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.543 11.788)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="izYXi5d" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.965 18.81)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="i4jlZBw" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7453 1.74043 -2.1505 -2.15651 27.89 23.393)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iYippzd" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .3134 .41161 27.553 23.618)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iS6OFpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.138 24.77)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iXbpW4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.161 21.59)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="ibm40wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.663 21.973)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="ioDaFQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.916 25.285)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iREZKom" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.916 26.579)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iaTfJDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.916 27.829)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iya9H8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.916 29.18)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ixnFxhe" cx="0" cy="0" r="1" gradientTransform="rotate(112.706 2.607 9.259)scale(2.26326 4.1415)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="ix1wTGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.38065 2.6461 -4.25445 2.21983 18.555 10.253)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="ilENXzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.67404 -1.09021 .87798 1.34816 19.322 10.802)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iEDDOsd" cx="0" cy="0" r="1" gradientTransform="rotate(-77.205 17.513 -7.36)scale(2.35536 2.06611)" gradientUnits="userSpaceOnUse"><stop offset=".745" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iPPfeib" cx="0" cy="0" r="1" gradientTransform="rotate(175.67 6.095 5.691)scale(2.38199 .47431)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iRlu9Qb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 2.63281 -4.19257 -9.35552 19.052 9.614)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="pq2t7lb5q"/><stop offset="1" class="r7p-9e6zz"/></radialGradient><radialGradient id="ij20MHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.87488 -8.98026 0 16.032 7.75)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="glxj2ubln"/><stop offset="1" class="fufqzdy6h"/></radialGradient><radialGradient id="iGGNqac" cx="0" cy="0" r="1" gradientTransform="matrix(1.39286 -.8314 .61148 1.02443 18.159 9.73)" gradientUnits="userSpaceOnUse"><stop class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iNzLsYd" cx="0" cy="0" r="1" gradientTransform="rotate(-118.968 9.71 .716)scale(1.38223 1.08515)" gradientUnits="userSpaceOnUse"><stop class="zvgvpp5en"/><stop offset="1" class="v1drycn3a"/></radialGradient><radialGradient id="ir92FZR" cx="0" cy="0" r="1" gradientTransform="rotate(138.871 4.877 5.656)scale(5.89127 2.1072)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="d0hwgbeaa"/><stop offset="1" class="y5jjb-bdd"/></radialGradient><radialGradient id="i2mTo1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21614 -.73448 0 16.291 12.473)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="i3F0Lvc" cx="0" cy="0" r="1" gradientTransform="rotate(157.021 6.985 7.651)scale(1.58183 2.41168)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i699LJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21614 -.73448 0 16.519 12.247)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iTAlNNb" cx="0" cy="0" r="1" gradientTransform="rotate(157.021 7.122 7.561)scale(1.58183 2.41168)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i4uD2Hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.17 10.104)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iBV1Fcb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.465 .7)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itAASje" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.906 10.104)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iNdDLkD" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.62 10.323)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="i1fQoHc" x1="15.944" x2="15.944" y1="4.01" y2="4.063" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iBk8Ytd" x1="16.025" x2="16.025" y1="4.809" y2="14.841" gradientUnits="userSpaceOnUse"><stop class="ucqwk0s3c"/><stop offset=".837" class="b9k-3ybvb"/></linearGradient><linearGradient id="iEwrR1d" x1="11.547" x2="11.547" y1="6.996" y2="17.731" gradientUnits="userSpaceOnUse"><stop class="x5dyrqz_l"/><stop offset="1" class="xuadj21pj"/></linearGradient><linearGradient id="iX1oKSd" x1="8.965" x2="5.374" y1="28.434" y2="28.434" gradientUnits="userSpaceOnUse"><stop class="rhalidc9f"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iuRo1Hb" x1="26.527" x2="22.985" y1="22.864" y2="29.17" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iekLMae" x1="20.024" x2="19.09" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="ikCB4Qb" x1="12.024" x2="12.358" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="izTK9RF" x1="17.187" x2="15.239" y1="29.122" y2="19.958" gradientUnits="userSpaceOnUse"><stop class="ym265mvaz"/><stop offset="1" class="k0c3dfbas"/></linearGradient><linearGradient id="i44g1vd" x1="23.038" x2="22.812" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="ipzx8Fc" x1="8.965" x2="9.089" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="i1YDhod" x1="13.812" x2="20.343" y1="28.341" y2="28.341" gradientUnits="userSpaceOnUse"><stop class="tbsuik4az"/><stop offset="1" class="mkeehnh5k"/></linearGradient><linearGradient id="iHPokje" x1="25.635" x2="25.635" y1="21.591" y2="24.77" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="iKewWrp" x1="25.663" x2="25.663" y1="22.294" y2="21.7" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="i4cMnfb" x1="27.507" x2="23.479" y1="28.043" y2="28.043" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="i0iYawc" x1="23.999" x2="25.708" y1="26.036" y2="26.036" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="ilGWpIb" x1="23.921" x2="25.63" y1="27.341" y2="27.341" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iIt88iU" x1="23.999" x2="25.708" y1="28.645" y2="28.645" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iQIfGPb" x1="10.914" x2="13.921" y1="11.034" y2="10.481" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iras6ge" x1="22.42" x2="21.714" y1="10.32" y2="13.004" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="i68hKrZ" x1="20.811" x2="20.811" y1="9.832" y2="11.98" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iGCR53d" x1="14.505" x2="15.146" y1="13.762" y2="13.212" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iqgavTc" x1="16.648" x2="15.845" y1="11.866" y2="11.902" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="itrwhjc" x1="15.845" x2="15.845" y1="12.874" y2="12.463" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iyGClbd" x1="15.845" x2="15.845" y1="10.258" y2="10.963" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="i43UeZb" x1="16.875" x2="16.073" y1="11.639" y2="11.675" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="i4MCe1c" x1="16.072" x2="16.072" y1="12.648" y2="12.236" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="ifGalXi" x1="16.072" x2="16.072" y1="10.032" y2="10.737" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iK9pq0v" x1="16.224" x2="16.239" y1="12.911" y2="12.02" gradientUnits="userSpaceOnUse"><stop offset=".26" class="akcgmbbow"/><stop offset="1" class="g9iuw_a0v"/></linearGradient><linearGradient id="iFHfsab" x1="18.947" x2="18.634" y1="10.158" y2="10.351" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iedKKLe" x1="14.65" x2="14.336" y1="10.158" y2="10.351" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibgAPkc" x1="19.502" x2="16.377" y1="6.973" y2="8.52" gradientUnits="userSpaceOnUse"><stop class="urzuj9che"/><stop offset="1" class="ev34ly_6u"/></linearGradient><filter id="iDJ2YyO" width="20.537" height="10.328" x="5.506" y="4.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1802" result="effect2_innerShadow_4002_1802"/></filter><filter id="i9Bzqpc" width="9.49" height="10.956" x="14.059" y="6.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0156863 0 0 0 0 0.0431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="i4V9snc" width="6.144" height="10.985" x="8.6" y="6.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.164706 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1802" result="effect2_innerShadow_4002_1802"/></filter><filter id="iL45KAe" width="8" height="6.44" x="12.024" y="15.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="iZSMmYc" width="8.45" height="4.612" x="11.755" y="25.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".125"/></filter><filter id="it5gKNd" width="8.05" height="4.28" x="11.905" y="25.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="if9jtib" width="4.468" height="5.556" x="23.479" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="iH8hoXc" width="2.097" height=".3" x="23.849" y="25.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".05"/></filter><filter id="iqDrKFb" width="2.097" height=".3" x="23.771" y="27.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".05"/></filter><filter id="ij6ceQb" width="2.097" height=".3" x="23.849" y="28.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".05"/></filter><filter id="i6DGDab" width="3.318" height="3.218" x="9.672" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.227451 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="iiNPbzc" width="3.148" height="3.148" x="19.237" y="9.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".25"/></filter><filter id="iYpLbLp" width="2.648" height="2.648" x="9.976" y="9.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".125"/></filter><filter id="itbysgd" width="10.425" height="9.709" x="11.12" y="6.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.394898 0 0 0 0 0.296564 0 0 0 0 0.281814 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="iXfkq4c" width="3.685" height="1.517" x="14.197" y="13.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".05"/></filter><filter id="iAG2r6d" width="2.197" height="2.968" x="14.746" y="10.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".1"/></filter><filter id="i5cNnJe" width="2.197" height="2.968" x="14.974" y="9.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".1"/></filter><filter id="iHsFNsb" width="2.247" height="1.019" x="12.273" y="7.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="iUpminc" width="2.237" height="1.009" x="17.599" y="7.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0823529 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="ioUOicb" width="3.001" height="1.285" x="17.13" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="icFNu9b" width="3.001" height="1.285" x="12.145" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/></filter><filter id="iECGz9c" width=".786" height=".696" x="17.435" y="9.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".05"/></filter><filter id="iSHQn0n" width=".891" height=".913" x="18.275" y="9.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".1"/></filter><filter id="iZGFfzO" width=".986" height="1.04" x="13.933" y="9.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".1"/></filter><filter id="i72FcNS" width=".912" height=".704" x="13.178" y="9.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".05"/></filter><filter id="iB9hZAe" width="2.132" height=".75" x="17.685" y="8.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".075"/></filter><filter id="impuPQb" width="2.132" height=".75" x="12.327" y="8.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".075"/></filter><filter id="iL58RUb" width="5.819" height=".998" x="15.695" y="6.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1802" stdDeviation=".075"/></filter><filter id="iTiMT3c" width="7.625" height="9.853" x="21.878" y="10.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1802"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1802" result="effect2_innerShadow_4002_1802"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1802" result="effect3_innerShadow_4002_1802"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-farmer-dark" /></template>
<style>
.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.akcgmbbow {
  stop-color: var(--svg-color--332024, #332024);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b2_83-3sv {
  stop-color: var(--svg-color--492522, #492522);
  stop-opacity: 0;
}

.b6hcm7htr {
  d: path("M20.811 11.98a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.baw9f51yc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.106 9.816c.063.085-.07.189-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.bfwlxiojl {
  d: path("M11.3 11.98a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.bkq68w2iz {
  fill: var(--svg-color--130e18, #130E18);
  d: path("M19.578 8.875a.24.24 0 0 1-.135-.038c-.01 0-.731-.414-1.53-.26a.26.26 0 0 1-.308-.212a.26.26 0 0 1 .211-.308c.992-.183 1.858.308 1.887.327c.125.077.174.241.096.366a.24.24 0 0 1-.221.125");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.c93nmcmgn {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.699 10.406l-.5 1.627a.518.518 0 0 0 .5.674h.75a.526.526 0 0 0 .501-.674l-.5-1.627c-.135-.356-.645-.356-.751 0");
}

.cgcgm4b2g {
  d: path("M19.368 7.998H16.75c-1.38 0-2.044-.559-2.629-1.083c0 0-.86.042-1.258.101c-.215.234-.444.53-.977.886c-.231.116-.756.527-.766 1.46l.064 2.594c.106 2.801 2.262 4.669 4.88 4.669c2.619 0 4.765-1.868 4.88-4.67V9.454c0-1.34-1.393-1.455-1.576-1.455");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cwohembfi {
  stop-color: var(--svg-color--040102, #040102);
}

.czvb3pcge {
  d: path("M22.985 29.98V18.01h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.d0hwgbeaa {
  stop-color: var(--svg-color--210d11, #210D11);
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dollalbrw {
  d: path("M19.368 7.998H16.75c-1.38 0-2.044-.559-2.629-1.083c0 0-.927.042-1.258.101c-.215.234-.444.53-.977.886c-.231.116-.756.527-.766 1.46l.064 2.594c.106 2.801 2.262 4.669 4.88 4.669c2.619 0 4.765-1.868 4.88-4.67V9.454c0-1.34-1.393-1.455-1.576-1.455");
}

.dtlh2rbzn {
  d: path("M22.985 18.04c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.du4i2cruh {
  stop-color: var(--svg-color--2aaa64, #2AAA64);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e92d_8btk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24 28.567h1.796");
}

.ejv89abvn {
  d: path("M11.281 12.515a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.euhgmbb6c {
  d: path("m15.699 10.406l-.5 1.627a.518.518 0 0 0 .5.674h.75a.526.526 0 0 0 .501-.674l-.5-1.627c-.135-.356-.645-.356-.751 0");
}

.ev34ly_6u {
  stop-color: var(--svg-color--4c4649, #4C4649);
  stop-opacity: 0;
}

.f2azchbek {
  cx: 13.635px;
  cy: 10.008px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.f6nr-db5g {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.38 13.472a1.97 1.97 0 0 0 1.66.899c.7 0 1.303-.356 1.659-.899a.2.2 0 0 0-.024-.248a.21.21 0 0 0-.243-.045c-.407.208-.89.331-1.392.331c-.512 0-.985-.123-1.392-.33a.2.2 0 0 0-.244.04a.2.2 0 0 0-.024.252Z");
}

.f9838hogy {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.885 8.26c.237-.1 1.324 0 1.732.312");
}

.fczuqnb-f {
  d: path("M8.965 29.98V18.01h-.007a10.95 10.95 0 0 0-3.993 8.47v3.5z");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fufqzdy6h {
  stop-color: var(--svg-color--291519, #291519);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g9iuw_a0v {
  stop-color: var(--svg-color--332024, #332024);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glxj2ubln {
  stop-color: var(--svg-color--362328, #362328);
  stop-opacity: 0;
}

.goe-kzizj {
  d: path("M18.106 9.816c.063.085-.07.189-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.gogld2b5i {
  fill: var(--svg-color--000, #000);
  d: path("M17.66 10.52a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
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

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hy21rybwg {
  fill: var(--svg-color--000, #000);
  d: path("M14.415 10.52a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.il0ne-blx {
  d: path("M11.588 4.81c-.849.03-2.678.228-4.102 1.335C6.25 7.108 6.01 8.262 6.01 9.231v.477c-.094 1.781 1.445 4.93 6.883 4.93h6.263c5.438 0 6.977-3.149 6.883-4.93V9.23c0-.969-.239-2.123-1.476-3.086c-1.424-1.107-3.253-1.304-4.102-1.336z");
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
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

.jn8004cwc {
  stop-color: var(--svg-color--423735, #423735);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jsvx11bfo {
  d: path("M15.955 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.k0c3dfbas {
  stop-color: var(--svg-color--309edd, #309EDD);
}

.k4228ccdd {
  d: path("M26.797 23.12c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.k926-qmtm {
  d: path("M26.138 21.77h-1v3h1z");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l4an7ueku {
  d: path("M13.904 9.627a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.l6a8ijbda {
  fill: var(--svg-color--130e18, #130E18);
  d: path("M12.541 8.875a.26.26 0 0 1-.23-.134a.27.27 0 0 1 .095-.366c.039-.02.896-.51 1.897-.327c.144.028.24.163.212.308c-.03.154-.164.25-.308.221c-.809-.144-1.531.26-1.531.26a.24.24 0 0 1-.135.038");
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

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m0229f9ub {
  d: path("M10.526 7.55c.977-.499 2.223-.544 2.649-.554l-.514 4.653l1.833 4.33l-2.608 1.752c-3.585-.735-3.348-3.564-3.137-4.355c.221-.831.028-1.02-.086-1.788c-.272-1.833.329-3.255 1.863-4.038");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
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

.n-8ovyb_a {
  d: path("M19.431 7.09c1.238.057 1.562.239 1.933.454c-.31-.151-1.345-.375-2.776-.063c-1.432.313-2.425.172-2.743.063l.141-.57c1.5.453 1.898.046 3.445.117");
}

.n68hknr5p {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M17.13 10.132c.265-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.269.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.08-.45");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of44kubsp {
  cx: 13.635px;
  cy: 10.008px;
  rx: 0.389px;
  ry: 0.197px;
}

.ohwoq2oew {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.921 27.263h1.797");
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.orgagwc6f {
  d: path("m10.125 5.55l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.ov6bqegoe {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M14.947 10.132c-.266-.466-.67-.835-1.538-.835c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.599l.556.317c.652-.21 1.372-.239 2.079-.45");
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pfc_pmbyf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24 25.958h1.796");
}

.pj_ifb3co {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.379 9.355c.653 0 1.204.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.128 1.37-1.128");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq2t7lb5q {
  stop-color: var(--svg-color--543a37, #543A37);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qruo7srzx {
  stroke: var(--svg-color--545154, #545154);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.26 8.26c-.238-.1-1.325 0-1.733.312");
}

.qv86iobue {
  stop-color: var(--svg-color--492522, #492522);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxarokbzg {
  stop-color: var(--svg-color--423735, #423735);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.qzqvrt_vg {
  d: path("m15.472 10.632l-.501 1.627a.518.518 0 0 0 .5.674h.751a.527.527 0 0 0 .501-.674l-.5-1.627c-.135-.356-.646-.356-.751 0");
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r7p-9e6zz {
  stop-color: var(--svg-color--352528, #352528);
}

.r8q177bio {
  stop-color: var(--svg-color--211211, #211211);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rbuuvqb-n {
  stop-color: var(--svg-color--1e1723, #1E1723);
}

.rhalidc9f {
  stop-color: var(--svg-color--3d935b, #3D935B);
}

.rifopebvv {
  stop-color: var(--svg-color--332022, #332022);
}

.rkz79qbai {
  d: path("M15.955 18.67c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.rsy33bcvg {
  d: path("M16.86 8.013c-1.715 0-2.525-.732-2.8-1.098c.835.027 2.456 0 4.583 0c2.659 0 4.35 1.048 4.703 2.971c.257 1.647-.242 2.689-.12 3.172c.12.484.563 1.763-.283 3.012c-.677.999-2.108 1.55-2.739 1.701h-2.185v-1.853c2.366-.725 2.319-3 2.37-3.212c.05-.212.421-1.94.297-3.337c-.096-1.072-.788-1.325-1.299-1.302c-.204 0-1.004-.054-2.527-.054");
}

.s-6nccc6b {
  d: path("m16.875 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.s5u5n3uga {
  d: path("M21.945 5.91h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.sfnrybc4v {
  d: path("M14.72 10.414c0-.288-.235-.48-.299-.538l-.288.279l.178.36z");
}

.snrf6qg2y {
  fill: var(--svg-color--b8b1c0, #B8B1C0);
  d: path("M22.78 11.044a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.602-.601");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.tbsuik4az {
  stop-color: var(--svg-color--36a9f3, #36A9F3);
}

.tjidt244a {
  d: path("M19.445 25.81h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.ucqwk0s3c {
  stop-color: var(--svg-color--5b3739, #5B3739);
}

.uksji80jn {
  d: path("M24.901 19.989h1.524v1.734a.25.25 0 0 1-.25.25H25.15a.25.25 0 0 1-.25-.25z");
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.urzuj9che {
  stop-color: var(--svg-color--4c4649, #4C4649);
}

.v1drycn3a {
  stop-color: var(--svg-color--392627, #392627);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vz8fcrkfe {
  stop-color: var(--svg-color--131720, #131720);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wfyrgzbul {
  d: path("m12.989 21.473l3.035-2.123l2.988 2.084c.42.325 1.012.465 1.012-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.595.823.965.563");
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wox7jpdoy {
  fill: var(--svg-color--2a0119, #2A0119);
  d: path("M16.04 13.56a3.1 3.1 0 0 1-1.415-.337c-.135-.077-.29.087-.203.222c.347.53.934.876 1.618.876a1.92 1.92 0 0 0 1.617-.876c.087-.135-.067-.289-.202-.222a3.1 3.1 0 0 1-1.415.337");
}

.wshud2bbh {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.472 10.632l-.501 1.627a.518.518 0 0 0 .5.674h.751a.527.527 0 0 0 .501-.674l-.5-1.627c-.135-.356-.646-.356-.751 0");
}

.x5dyrqz_l {
  stop-color: var(--svg-color--1f171b, #1F171B);
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xef0asb0e {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.955 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xuadj21pj {
  stop-color: var(--svg-color--18111b, #18111B);
}

.y5jjb-bdd {
  stop-color: var(--svg-color--210d11, #210D11);
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

.ye4fst04c {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.445 25.81h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.yjs-mabtr {
  d: path("M18.172 9.627a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.ym265mvaz {
  stop-color: var(--svg-color--2d5ca0, #2D5CA0);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.z13m-02be {
  d: path("M18.966 10.402a.84.84 0 0 0-.23-.463l-.26.286l.117.227z");
}

.z1au5gx5t {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.697 9.355c-.653 0-1.204.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.z9jip3bmj {
  d: path("M23.479 25.306a.73.73 0 0 1 .727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zjnvspbhz {
  stop-color: var(--svg-color--28659f, #28659F);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zvgvpp5en {
  stop-color: var(--svg-color--392627, #392627);
}

.zybyg0bhb {
  d: path("M20.811 12.515a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
