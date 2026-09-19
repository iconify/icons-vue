<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="vai46_bde"/><path fill="url(#i92Q0mw)" class="lkd95yuyr"/><path fill="url(#iq2bodd)" class="lkd95yuyr"/><path fill="url(#iIFz9Ne)" class="au3py2bea"/><path fill="url(#inZp2Oc)" class="au3py2bea"/><path fill="url(#io97iTb)" class="au3py2bea"/><path fill="url(#iHA7Ngj)" class="au3py2bea"/><path fill="url(#iq8bgqb)" class="au3py2bea"/><path fill="url(#ibUqvad)" class="au3py2bea"/><g filter="url(#iDkUHrd)"><path class="tjxcwv8mh"/></g><path fill="url(#iImNd0d)" class="s3ews0cqj"/><path fill="url(#iUolcae)" class="s3ews0cqj"/><path fill="url(#imvqmoe)" class="s3ews0cqj"/><path fill="url(#igeBrNe)" class="vhib3iu3p"/><path fill="url(#i2ShBxd)" class="vhib3iu3p"/><path fill="url(#ipKWlme)" class="k5ve7td8d"/><path fill="url(#in5yhYd)" class="k5ve7td8d"/><g filter="url(#iYezXmc)"><path stroke="url(#ib5deMc)" class="w9zmiabgt"/></g><path fill="url(#iGRF7tR)" class="tu6ignzdo"/><path fill="url(#iU9ydqe)" class="tu6ignzdo"/><path fill="url(#iqHkQSc)" class="tu6ignzdo"/><path fill="url(#i7L8iFd)" class="tu6ignzdo"/><path fill="url(#i3yxLnT)" class="tu6ignzdo"/><path fill="url(#iKP6Iub)" class="hbscdacub"/><path fill="url(#iYbJFoe)" class="hbscdacub"/><path fill="url(#iPQs2ed)" class="hbscdacub"/><path fill="url(#i7A5v7X)" class="sttm0mbfx"/><path fill="url(#iivKYNd)" class="sttm0mbfx"/><g filter="url(#im00Lee)"><path fill="url(#isSYQFb)" class="z5zayrb1o"/><path fill="url(#isSYQFb)" class="ubc799zut"/><path fill="url(#isSYQFb)" class="nz3l4hs6l"/></g><g filter="url(#iM3nPLc)"><path class="yez1pt8pd"/></g><g filter="url(#iibHOCe)"><path class="weis3abfl"/></g><path fill="url(#iNWpJ9c)" class="gq2825bto"/><path fill="url(#iTRc5mw)" class="x9wzjkbfu"/><g filter="url(#iGuJyBe)"><path fill="url(#i8Rj6uc)" class="x7t2nnbqp"/><path fill="url(#iwYEvIe)" class="x7t2nnbqp"/></g><path fill="url(#iMXZk2D)" class="x7t2nnbqp"/><path fill="url(#iE7bOde)" class="x7t2nnbqp"/><path fill="url(#iUh65xX)" class="x7t2nnbqp"/><path fill="url(#iAifwIe)" class="x7t2nnbqp"/><path fill="url(#iPDFvBJ)" class="x7t2nnbqp"/><path fill="url(#iKJLyzG)" class="x7t2nnbqp"/><path fill="url(#ixgZygp)" class="x7t2nnbqp"/><path fill="url(#iOF1Xvb)" class="x7t2nnbqp"/><path fill="url(#i6Q8Kfd)" class="x7t2nnbqp"/><g filter="url(#itthdad)"><path class="veqcaqbvq"/></g><g filter="url(#iGPX9ae)"><path class="qr0nodbun"/><path fill="url(#i0zFIXc)" class="wumqwib3u"/><path fill="url(#iMsUZue)" class="wumqwib3u"/><path fill="url(#iy9jPUc)" class="wumqwib3u"/><path fill="url(#iiHmbNc)" class="wumqwib3u"/><path fill="url(#ilKkU7d)" class="wumqwib3u"/></g><path fill="url(#ieaZQLp)" class="wumqwib3u"/><path fill="url(#iib8xub)" class="wumqwib3u"/><g filter="url(#iaXd1cP)"><path stroke="url(#iUkKgub)" class="ow8bg8bvv"/></g><path fill="url(#iS5uPYd)" class="apogbmb5r"/><g filter="url(#iv3qnte)"><path fill="url(#iLmiaSc)" class="w-d413hfu"/></g><path fill="url(#i8UJopn)" class="rpq55kdsa"/><path fill="url(#inSgKKc)" class="rpq55kdsa"/><path fill="url(#iipoOEe)" class="rpq55kdsa"/><g filter="url(#iOBRN0d)"><path class="molfgqvxr"/></g><g filter="url(#iL5UWPb)"><path class="gdpvs4blu"/></g><g filter="url(#idzSNue)"><path class="j91gxe29x"/><path fill="url(#iCQdNGe)" class="pj6yzdztp"/><path fill="url(#iL0rLAe)" class="pj6yzdztp"/></g><g filter="url(#iSJBH5d)"><path class="uv5g9-bso"/><path fill="url(#iv9LBJd)" class="n42tlqo_k"/><path fill="url(#iRB2STb)" class="n42tlqo_k"/><path fill="url(#ioSfsYc)" class="n42tlqo_k"/></g><path class="hhwntnzgh"/><path fill="url(#iqMD1Jc)" class="ld84frhbv"/><path class="r7-96vbcr"/><g filter="url(#ivdA1Nb)"><path class="nor_ckbjp"/><path fill="url(#igHurNv)" class="lik-xvb7s"/></g><g filter="url(#i3Ybfwe)"><path fill="url(#i1FP7Hb)" class="n_ea-bxmy"/></g><path class="jav-vab9r"/><path fill="url(#i4MRpQc)" class="ihgtubcjx"/><path class="u3_gxq7hu"/><g filter="url(#iGlLSDf)"><path fill="url(#iUj3Nwc)" class="nenwa96lf"/></g><g filter="url(#i0lN1ip)"><ellipse transform="rotate(-27.914 13.778 9.823)" class="cr713nssa"/><ellipse fill="url(#ikJTb3c)" transform="rotate(-27.914 13.778 9.823)" class="j9clow-yo"/></g><path fill="url(#ii4rv3c)" class="vwouutbnm"/><path fill="url(#iDLQcRb)" class="vwouutbnm"/><path fill="url(#inyGjvU)" class="vwouutbnm"/><path fill="url(#iqsFIZb)" class="vwouutbnm"/><path fill="url(#iZyzbiY)" class="jkw5a3bfj"/><path fill="url(#iX7IcCe)" class="jkw5a3bfj"/><g filter="url(#iGvImWb)"><path fill="url(#i98b8Wb)" class="rt_xtl8sl"/></g><g filter="url(#iOrqvYt)"><path fill="url(#ieW2dmc)" class="an7tl2bef"/></g><g filter="url(#iZjOMXd)"><path class="v02pn_3_k"/></g><g filter="url(#iOk9Brb)"><path class="sr_atcc8w"/></g><g filter="url(#iXdD44j)"><path class="jcgqco81x"/></g><g filter="url(#iAIKfob)"><path fill="url(#i1tgyzb)" class="xn6n1tbvx"/><path fill="url(#i5EwYtb)" class="xn6n1tbvx"/></g><path fill="url(#irCNp2c)" class="q6pfddbhp"/><path fill="url(#iRLWNSc)" class="q6pfddbhp"/><path fill="url(#i8wo01H)" class="q6pfddbhp"/><defs><radialGradient id="i92Q0mw" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.592 23.122)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iq2bodd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.998 21.466)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iIFz9Ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 15.8584 0 16.298 21.356)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="x3t2hmtbe"/><stop offset="1" class="x4e9_o_2d"/></radialGradient><radialGradient id="inZp2Oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.29 16.903)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="io97iTb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.873 15.56)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iHA7Ngj" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.623 15.324)" gradientUnits="userSpaceOnUse"><stop offset=".939" class="xuw5xge2n"/><stop offset=".971" class="pwa-xfb8m"/></radialGradient><radialGradient id="iq8bgqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.29 23.622)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="ibUqvad" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.40625 -5.25876 0 16.29 16.07)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="i8onqub3d"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iImNd0d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.594 18.227)" gradientUnits="userSpaceOnUse"><stop class="xoj0cjj5j"/><stop offset="1" class="gietximnj"/></radialGradient><radialGradient id="iUolcae" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.276 16.992)" gradientUnits="userSpaceOnUse"><stop class="ktrl6_0jb"/><stop offset="1" class="ki0_-eiqi"/></radialGradient><radialGradient id="imvqmoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.276 14.55)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="v71br5-3y"/><stop offset="1" class="eqeqhqb5o"/></radialGradient><radialGradient id="i2ShBxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.865 11.675)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="ipKWlme" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.123 12.047)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="in5yhYd" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.785 12.438)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iqHkQSc" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.257 8.555)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="i7L8iFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.623 16.903)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="yl8yg_b1a"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="i3yxLnT" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.623 13.114)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="iKP6Iub" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.295 30.003)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iYbJFoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.06 30.003)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="i7A5v7X" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.402 30.003)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iivKYNd" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.352 23.163)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iNWpJ9c" cx="0" cy="0" r="1" gradientTransform="matrix(.76676 2.06805 -2.45668 .91085 21.157 11.824)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iTRc5mw" cx="0" cy="0" r="1" gradientTransform="matrix(1.51193 .47517 -1.46594 4.6644 10.088 12.326)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="i8Rj6uc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.81805 0 0 -8.52308 19.165 10.86)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iwYEvIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78503 2.9522 -2.43729 -1.47369 18.775 5.761)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iE7bOde" cx="0" cy="0" r="1" gradientTransform="rotate(96.022 6.515 10.977)scale(11.9419 9.88935)" gradientUnits="userSpaceOnUse"><stop offset=".763" class="inz1oriuw"/><stop offset="1" class="png8a7b0k"/></radialGradient><radialGradient id="iUh65xX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17593 1.45522 0 18.796 9.515)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iAifwIe" cx="0" cy="0" r="1" gradientTransform="matrix(.00402 -1.12056 1.21943 .00438 13.934 9.563)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iPDFvBJ" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.715 6.248)scale(8.71738 22.2685)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iKJLyzG" cx="0" cy="0" r="1" gradientTransform="matrix(3.46712 -2.98652 .88217 1.02413 9.335 8.06)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="ixgZygp" cx="0" cy="0" r="1" gradientTransform="matrix(-.2403 2.55743 -1.0223 -.09606 21.968 7.872)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iOF1Xvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89252 -1.71339 0 14.02 10.352)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i6Q8Kfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.53144 -6.47198 0 15.66 4.54)" gradientUnits="userSpaceOnUse"><stop offset=".634" class="uez29prwg"/><stop offset="1" class="clcv9zbch"/></radialGradient><radialGradient id="iMsUZue" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24997 -.7856 0 16.767 12.253)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iiHmbNc" cx="0" cy="0" r="1" gradientTransform="rotate(156.092 7.208 7.622)scale(1.89533 3.04594)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iib8xub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31304 1.25297 -1.80834 -1.89503 16.733 11.373)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iS5uPYd" cx="0" cy="0" r="1" gradientTransform="matrix(2.2344 -1.0985 4.41953 8.98955 15.787 14.57)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i8UJopn" cx="0" cy="0" r="1" gradientTransform="matrix(2.8065 -7.3213 10.38886 3.9824 10.445 8.889)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="inSgKKc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55582 -6.71118 9.5231 -2.20769 22.099 8.95)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iipoOEe" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.239 -3.915)scale(2.70175 3.18947)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iCQdNGe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.254 0 0 -.83655 16.55 3.495)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iL0rLAe" cx="0" cy="0" r="1" gradientTransform="matrix(3.2955 -5.21781 5.7808 3.65108 10.73 7.533)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iv9LBJd" cx="0" cy="0" r="1" gradientTransform="matrix(3.59964 -2.89801 4.4913 5.57866 18.255 6.113)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iRB2STb" cx="0" cy="0" r="1" gradientTransform="matrix(3.02993 -2.71183 4.96467 5.54703 18.987 7.401)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="ioSfsYc" cx="0" cy="0" r="1" gradientTransform="matrix(3.30274 .74152 -.31046 1.3828 18.102 5.536)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iqMD1Jc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8308 -1.32149 0 18.524 9.922)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="igHurNv" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.596 .525)scale(.38737 .53333)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4MRpQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83085 -1.32156 0 14.056 9.921)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ikJTb3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00792 -.50595 .60817 -.00952 13.762 10.146)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDLQcRb" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 3.958 18.826)scale(2.38563 2.27607)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="inyGjvU" cx="0" cy="0" r="1" gradientTransform="matrix(.8067 -1.10707 .92794 .67618 21.388 10.493)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iqsFIZb" cx="0" cy="0" r="1" gradientTransform="matrix(.6011 -1.58766 2.12134 .80315 21.504 10.67)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iX7IcCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69808 0 0 -1.89616 11.257 10.592)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i98b8Wb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9385 .1611 -.16517 -.96225 11.258 10.595)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="i1tgyzb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.732 11.902 -4.868)scale(3.6749 8.45124)" gradientUnits="userSpaceOnUse"><stop class="c3tjvjbdr"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="i5EwYtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.99817 -7.31619 0 16.238 2.873)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iRLWNSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.03 2.403)" gradientUnits="userSpaceOnUse"><stop class="h02irqbsf"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="i8wo01H" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.06 3.028)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="iDkUHrd" width="5.32" height="9.565" x="13.616" y="9.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".2"/></filter><filter id="iYezXmc" width=".65" height="8.268" x="24.401" y="3.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".125"/></filter><filter id="im00Lee" width="8.964" height="6.734" x="11.808" y="23.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".075"/></filter><filter id="iM3nPLc" width="5.842" height="3.536" x="16.952" y="3.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".5"/></filter><filter id="iibHOCe" width="5.842" height="3.536" x="16.952" y="3.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".5"/></filter><filter id="iGuJyBe" width="11.466" height="12.738" x="11.105" y="4.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1588"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1588" result="effect2_innerShadow_4002_1588"/></filter><filter id="itthdad" width="3.789" height="4.97" x="14.25" y="9.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".5"/></filter><filter id="iGPX9ae" width="2.322" height="3.37" x="15.129" y="9.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".1"/></filter><filter id="iaXd1cP" width="3.796" height="1.598" x="14.392" y="13.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".05"/></filter><filter id="iv3qnte" width="13.182" height="8.21" x="9.699" y="1.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1588"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1588" result="effect2_innerShadow_4002_1588"/></filter><filter id="iOBRN0d" width="2.393" height="1.214" x="17.917" y="7.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1588"/></filter><filter id="iL5UWPb" width="2.393" height="1.199" x="12.535" y="7.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1588"/></filter><filter id="idzSNue" width="6.731" height="6.124" x="10.069" y="2.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1588"/><feGaussianBlur result="effect2_foregroundBlur_4002_1588" stdDeviation=".125"/></filter><filter id="iSJBH5d" width="7.259" height="6.118" x="16.127" y="2.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1588"/><feGaussianBlur result="effect2_foregroundBlur_4002_1588" stdDeviation=".125"/></filter><filter id="ivdA1Nb" width=".801" height=".708" x="17.775" y="9.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".05"/></filter><filter id="i3Ybfwe" width=".903" height=".926" x="18.637" y="9.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".1"/></filter><filter id="iGlLSDf" width="1" height="1.056" x="14.088" y="9.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".1"/></filter><filter id="i0lN1ip" width=".93" height=".717" x="13.313" y="9.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".05"/></filter><filter id="iGvImWb" width="1.349" height="2.424" x="10.069" y="9.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".125"/></filter><filter id="iOrqvYt" width="1.825" height="2.8" x="20.962" y="9.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".25"/></filter><filter id="iZjOMXd" width="2.445" height="1.17" x="12.461" y="7.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".125"/></filter><filter id="iOk9Brb" width="2.445" height="1.17" x="17.905" y="7.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".125"/></filter><filter id="iXdD44j" width="5.96" height="3.583" x="17.098" y="3.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1588" stdDeviation=".5"/></filter><filter id="iAIKfob" width="12.586" height="3.001" x="9.977" y="3.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1588"/></filter><linearGradient id="igeBrNe" x1="23.98" x2="25.166" y1="8.949" y2="8.949" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="ib5deMc" x1="25.226" x2="25.226" y1="3.716" y2="11.483" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iGRF7tR" x1="25.774" x2="23.455" y1="14.814" y2="14.814" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iU9ydqe" x1="23.406" x2="24.469" y1="14.61" y2="14.735" gradientUnits="userSpaceOnUse"><stop class="nnh5vk6mb"/><stop offset="1" class="boxqtwbke"/></linearGradient><linearGradient id="iPQs2ed" x1="9.205" x2="8.779" y1="28.071" y2="28.071" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="isSYQFb" x1="16.29" x2="16.29" y1="29.872" y2="23.438" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iMXZk2D" x1="21.571" x2="18.981" y1="12.585" y2="12.585" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="i0zFIXc" x1="17.148" x2="16.29" y1="11.551" y2="11.586" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iy9jPUc" x1="16.29" x2="16.29" y1="12.717" y2="12.241" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ilKkU7d" x1="16.29" x2="16.29" y1="9.947" y2="10.507" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="ieaZQLp" x1="16.716" x2="16.716" y1="12.858" y2="12.661" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="iUkKgub" x1="15.059" x2="15.386" y1="14.326" y2="13.471" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iLmiaSc" x1="23.307" x2="11.415" y1="5.061" y2="5.061" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="i1FP7Hb" x1="19.321" x2="19" y1="9.976" y2="10.174" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUj3Nwc" x1="14.817" x2="14.496" y1="9.976" y2="10.174" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ii4rv3c" x1="22.881" x2="21.645" y1="10.004" y2="12.233" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iZyzbiY" x1="10.3" x2="11.793" y1="10.725" y2="10.594" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="ieW2dmc" x1="21.874" x2="21.874" y1="9.688" y2="11.488" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="irCNp2c" x1="18.06" x2="16.779" y1="3.965" y2="-.41" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:student-medium" /></template>
<style>
.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.an7tl2bef {
  d: path("M21.462 11.488q.05-.9.096-1.8c.41.055.729.435.729.896c0 .496-.369.9-.825.904");
}

.apogbmb5r {
  d: path("M16.29 13.826a3.1 3.1 0 0 1-1.419-.337c-.14-.071-.29.087-.202.214c.342.52.94.867 1.62.867c.682 0 1.28-.347 1.622-.867c.089-.132-.062-.285-.202-.214c-.41.214-.894.337-1.42.337");
}

.au3py2bea {
  d: path("M23.311 18.101a.24.24 0 0 0-.059-.29c-1.856-1.602-4.346-2.486-6.954-2.486s-5.113.893-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.613 7.03 4.613s5.73-2.014 7.013-4.614");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.boxqtwbke {
  stop-color: var(--svg-color--fbb229, #FBB229);
  stop-opacity: 0;
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c3tjvjbdr {
  stop-color: var(--svg-color--534d5a, #534D5A);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clcv9zbch {
  stop-color: var(--svg-color--72474e, #72474E);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.cr713nssa {
  cx: 13.778px;
  cy: 9.823px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.399px;
  ry: 0.202px;
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
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

.eqeqhqb5o {
  stop-color: var(--svg-color--5f4132, #5F4132);
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
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

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gdpvs4blu {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.797 7.696a2.84 2.84 0 0 1 1.78-.368a.284.284 0 0 1-.068.564a2.27 2.27 0 0 0-1.42.292a1 1 0 0 0-.094.061l-.003.002a.284.284 0 0 1-.348-.449z");
}

.gietximnj {
  stop-color: var(--svg-color--7e5059, #7E5059);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gq2825bto {
  d: path("M21.268 12.14a1.7 1.7 0 0 0 .926-.316v.953c0 .915-.545 1.73-1.373 2.068q.263-.559.354-1.209z");
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h02irqbsf {
  stop-color: var(--svg-color--6a6273, #6A6273);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbscdacub {
  d: path("M9.06 30.003V18.216a10.97 10.97 0 0 0-3.765 8.287v3.5z");
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hhwntnzgh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.738 9.155a1.43 1.43 0 0 1 1.388 1.084a.28.28 0 0 1-.274.349h-2.285a.236.236 0 0 1-.233-.278a1.43 1.43 0 0 1 1.404-1.155");
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i8onqub3d {
  stop-color: var(--svg-color--170919, #170919);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ihgtubcjx {
  d: path("M14.054 9.433a.914.914 0 0 0-.881 1.155h1.765a1 1 0 0 0 .034-.241a.92.92 0 0 0-.918-.914");
}

.inz1oriuw {
  stop-color: var(--svg-color--90596b, #90596B);
  stop-opacity: 0;
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j91gxe29x {
  fill: var(--svg-color--533634, #533634);
  d: path("M16.528 5.109a3 3 0 0 1-.068-.14a.68.68 0 0 0-.63-.429h-1.303c-1.89 0-3.422 1.55-3.422 3.46v.282c-.348-.265-.786-.823-.786-1.728c0-1.098.8-1.652 1.311-2.006c.144-.1.265-.184.339-.26l.102-.107c.358-.38.995-1.056 2.11-1.352a5.6 5.6 0 0 1 1.562-.168c.473.013.806.421.806.894v1.54z");
}

.j9clow-yo {
  cx: 13.778px;
  cy: 9.823px;
  rx: 0.399px;
  ry: 0.202px;
}

.jav-vab9r {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.842 9.154a1.43 1.43 0 0 0-1.388 1.085a.28.28 0 0 0 .274.348h2.285a.236.236 0 0 0 .233-.278a1.435 1.435 0 0 0-1.404-1.155");
}

.jcgqco81x {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.794 5.112h-2.188a.508.508 0 1 1 .081-1.01c.568.09 1.322.216 1.827.341c1.141.283 1.456.839 1.544 1.235a1.6 1.6 0 0 0-1.264-.566");
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jkw5a3bfj {
  d: path("M11.125 8.951c-.8.113-1.426.805-1.426 1.637c0 .88.69 1.598 1.558 1.645a80 80 0 0 1-.132-3.282");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.k5ve7td8d {
  d: path("M24.223 11.651a.837.837 0 1 0 .8 0z");
}

.ki0_-eiqi {
  stop-color: var(--svg-color--804d60, #804D60);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.ktrl6_0jb {
  stop-color: var(--svg-color--804d60, #804D60);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.ld84frhbv {
  d: path("M18.527 9.433a.914.914 0 0 1 .88 1.155h-1.765a.918.918 0 0 1 .885-1.155");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lik-xvb7s {
  d: path("M18.46 9.626c.064.087-.072.193-.226.309s-.27.197-.335.11s.008-.252.162-.367c.155-.116.333-.14.398-.052");
}

.lkd95yuyr {
  d: path("M16.295 15.502c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.molfgqvxr {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M20.113 7.808c-.18-.156-.389-.322-.704-.421c-.312-.098-.702-.125-1.242-.059a.284.284 0 1 0 .069.564c.493-.06.794-.029 1.002.037c.203.063.34.167.502.307a.284.284 0 1 0 .373-.428");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n_ea-bxmy {
  d: path("M19.34 10.226a.86.86 0 0 0-.236-.474l-.267.292l.12.234z");
}

.n42tlqo_k {
  d: path("M21.628 8.454V7.77c-.011-.781-.687-1.388-1.47-1.42h-1.433a2.48 2.48 0 0 1-2.175-1.29s-.067-.156-.133-.418c-.247-.973.68-1.713 1.664-1.526c1.007.192 2.162.53 3.013 1.085c1.787 1.165 1.474 3.265.534 4.254");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nenwa96lf {
  d: path("M14.889 10.24c0-.296-.24-.493-.306-.553l-.295.286l.182.37z");
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nnh5vk6mb {
  stop-color: var(--svg-color--bd9130, #BD9130);
}

.nor_ckbjp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.46 9.626c.064.087-.072.193-.226.309s-.27.197-.335.11s.008-.252.162-.367c.155-.116.333-.14.398-.052");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.nz3l4hs6l {
  d: path("M19.93 23.779c0-.189.155-.341.346-.341s.346.152.346.34v6.094h-.691z");
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.ow8bg8bvv {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.906 13.423c.4.208.876.328 1.384.328c.513 0 .985-.12 1.384-.328a.23.23 0 0 1 .276.045c.065.068.09.178.024.277m-3.068-.322l3.005.28m-3.005-.28a.23.23 0 0 0-.276.047a.215.215 0 0 0-.024.275m.3-.322l-.237.28m3.305.042l-.063-.042m.063.042l-.063-.042m.063.042c-.357.54-.977.9-1.684.9c-.706 0-1.327-.36-1.684-.9m3.305-.042c-.343.52-.94.867-1.621.867a1.94 1.94 0 0 1-1.621-.867m-.063.042v.001l.063-.043m-.063.042l.063-.042");
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.pj6yzdztp {
  d: path("M16.528 5.109a3 3 0 0 1-.068-.14a.68.68 0 0 0-.63-.429h-1.303c-1.89 0-3.422 1.55-3.422 3.46v.282c-.348-.265-.786-.823-.786-1.728c0-1.098.8-1.652 1.311-2.006c.144-.1.265-.184.339-.26l.102-.107c.358-.38.995-1.056 2.11-1.352a5.6 5.6 0 0 1 1.562-.168c.473.013.806.421.806.894v1.54z");
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.png8a7b0k {
  stop-color: var(--svg-color--784757, #784757);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pwa-xfb8m {
  stop-color: var(--svg-color--655f6b, #655F6B);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q6pfddbhp {
  d: path("M24.233 3.612H8.263c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qr0nodbun {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.898 10.128l-.544 1.882c-.11.387.156.775.533.775h.805c.378 0 .645-.393.534-.775l-.545-1.882c-.116-.417-.66-.417-.783 0");
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r7-96vbcr {
  fill: var(--svg-color--000, #000);
  d: path("M18.003 10.347c0-.291.233-.524.524-.524a.52.52 0 0 1 .465.765h-.927a.5.5 0 0 1-.062-.241");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rpq55kdsa {
  d: path("M21.262 4.057c.526.181.999.55 1.298 1.076c.478.84.407 1.846-.11 2.587a1.6 1.6 0 0 0-.276.896v1.216a1.8 1.8 0 0 0-.683-.274l.08-1.645a1.484 1.484 0 0 0-1.412-1.467h-1.434A2.48 2.48 0 0 1 16.46 4.97a.68.68 0 0 0-.63-.429h-1.303c-1.89 0-3.422 1.55-3.422 3.46l.032 1.575c-.26.038-.532.125-.738.27v-1.23c0-.318-.098-.63-.277-.895a2.45 2.45 0 0 1-.146-2.504a2.4 2.4 0 0 1 1.33-1.154a2.75 2.75 0 0 0 1.418-1.137c.423-.675 1.167-.698 2.02-.698c.331 0 .646.071.94.192c.39.17.83.17 1.222 0c.288-.121.603-.192.934-.192c.863 0 1.618.04 2.037.731c.315.522.809.901 1.385 1.099");
}

.rt_xtl8sl {
  d: path("M11.082 9.632a.979.979 0 0 0 .086 1.925a79 79 0 0 1-.086-1.925");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s3ews0cqj {
  d: path("M15.996 18.872c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.389 1.78-2.586v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.586");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sr_atcc8w {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.975 7.926c-.264-.188-.92-.52-1.695-.39");
}

.sttm0mbfx {
  d: path("M23.52 30.003V18.216a10.97 10.97 0 0 1 3.765 8.287v3.5z");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tjxcwv8mh {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.996 18.872c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.389 1.78-2.586v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.586Z");
}

.tu6ignzdo {
  d: path("m23.77 13.613l-.517 2.238a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.239a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.u3_gxq7hu {
  fill: var(--svg-color--000, #000);
  d: path("M14.577 10.347a.52.52 0 0 0-.524-.524a.52.52 0 0 0-.465.765h.927a.5.5 0 0 0 .062-.241");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ubc799zut {
  d: path("M15.944 23.779c0-.189.155-.341.346-.341s.346.152.346.34v6.094h-.692z");
}

.uez29prwg {
  stop-color: var(--svg-color--72474e, #72474E);
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uv5g9-bso {
  fill: var(--svg-color--563936, #563936);
  d: path("M21.628 8.454V7.77c-.011-.781-.687-1.388-1.47-1.42h-1.433a2.48 2.48 0 0 1-2.175-1.29s-.067-.156-.133-.418c-.247-.973.68-1.713 1.664-1.526c1.007.192 2.162.53 3.013 1.085c1.787 1.165 1.474 3.265.534 4.254");
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v02pn_3_k {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.836 7.983c.263-.189.919-.52 1.695-.39");
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v71br5-3y {
  stop-color: var(--svg-color--5f4132, #5F4132);
  stop-opacity: 0;
}

.vai46_bde {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.295 15.502c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.veqcaqbvq {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.879 10.328l-.605 1.883c-.103.387.145.774.496.774h.75c.35 0 .599-.393.495-.774l-.506-1.883c-.109-.417-.516-.417-.63 0");
}

.vhib3iu3p {
  d: path("M25.023 11.675V2.813h-.8v8.862z");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vwouutbnm {
  d: path("M21.33 12.233q.103-1.634.19-3.268a1.648 1.648 0 0 1-.19 3.268");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w-d413hfu {
  d: path("M21.262 4.057c.526.182.999.55 1.298 1.077c.478.84.407 1.845-.11 2.587a1.6 1.6 0 0 0-.276.895v1.217a1.8 1.8 0 0 0-.683-.275l.08-1.645a1.484 1.484 0 0 0-1.412-1.466h-1.434a2.48 2.48 0 0 1-2.265-1.478a.68.68 0 0 0-.63-.428h-1.303c-1.89 0-3.422 1.549-3.422 3.46l.032 1.574c-.26.038-.532.125-.738.27V8.616a1.6 1.6 0 0 0-.277-.895a2.45 2.45 0 0 1-.146-2.505a2.4 2.4 0 0 1 1.33-1.153a2.75 2.75 0 0 0 1.418-1.137c.423-.676 1.167-.79 2.02-.79c.331 0 .646.07.94.191c.39.17.83.17 1.222 0c.288-.12.603-.192.934-.192c.863 0 1.618.132 2.037.824c.315.522.809.9 1.385 1.098");
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.w9zmiabgt {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.726 3.716v7.767");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.weis3abfl {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.568 5.065h-2.123a.492.492 0 1 1 .078-.981c.551.088 1.283.21 1.773.332c1.107.274 1.413.813 1.498 1.198a1.54 1.54 0 0 0-1.226-.55");
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wumqwib3u {
  d: path("m15.898 10.128l-.544 1.882c-.11.387.156.775.533.775h.805c.378 0 .645-.393.534-.775l-.545-1.882c-.116-.417-.66-.417-.783 0");
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x3t2hmtbe {
  stop-color: var(--svg-color--46404e, #46404E);
}

.x4e9_o_2d {
  stop-color: var(--svg-color--3a3142, #3A3142);
}

.x7t2nnbqp {
  d: path("M11.35 13.691a4.01 4.01 0 0 0 3.978 3.488h1.932a4.01 4.01 0 0 0 3.98-3.488c.12-1.929.241-3.85.331-5.778a1.484 1.484 0 0 0-1.412-1.467h-1.434A2.48 2.48 0 0 1 16.46 4.97a.68.68 0 0 0-.63-.428h-1.303c-1.89 0-3.422 1.548-3.422 3.46c0 1.905.12 3.78.244 5.69");
}

.x9wzjkbfu {
  d: path("M11.312 12.14a1.7 1.7 0 0 1-.926-.316v.953c0 .915.545 1.73 1.373 2.068a4.2 4.2 0 0 1-.354-1.209z");
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xn6n1tbvx {
  d: path("m9.977 5.235l1.21-1.973l10.258-.11l1.117 2.02c-4.664 1.61-10.496.797-12.585.063");
}

.xoj0cjj5j {
  stop-color: var(--svg-color--976c65, #976C65);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xuw5xge2n {
  stop-color: var(--svg-color--655f6b, #655F6B);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yez1pt8pd {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.568 5.128h-2.123a.492.492 0 1 1 .078-.98c.551.087 1.283.21 1.773.331c1.107.275 1.413.814 1.498 1.198a1.54 1.54 0 0 0-1.226-.549");
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

.z5zayrb1o {
  d: path("M11.958 23.779c0-.189.155-.341.346-.341s.345.152.345.34v6.094h-.691z");
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
