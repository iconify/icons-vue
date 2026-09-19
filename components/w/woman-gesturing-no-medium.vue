<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHOnuzc)"><path fill="url(#iBo66jb)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#i36Rpdd)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#idoc3xe)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iqWYWTb)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iZFAVJc)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#irOwDHe)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iu0Y8CF)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iD43fte)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iE7xYwe)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#ipceuqb)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#i7ZjZYl)" clip-rule="evenodd" class="g-fa2m3lw"/><path fill="url(#iyUfkEX)" clip-rule="evenodd" class="g-fa2m3lw"/></g><g filter="url(#iMsdQHx)"><path fill="url(#iC7LROb)" class="ylwpyxpit"/></g><path fill="url(#iCvinMC)" class="ylwpyxpit"/><g filter="url(#iYj0YPs)"><path fill="url(#i4Rfatd)" class="f11-aub0q"/><path fill="url(#iB70k5d)" class="f11-aub0q"/></g><g filter="url(#iPJWpub)"><path class="zpyf39lse"/><path fill="url(#i9nW6ib)" class="p6zaajppg"/></g><g filter="url(#iCT0Jqe)"><path class="aysl7_bmb"/><path fill="url(#ingKAld)" class="f007bp1ul"/></g><g filter="url(#iqD7MAc)"><path fill="url(#igJByge)" class="jzqa5_bif"/><path fill="url(#i9xq3ob)" class="jzqa5_bif"/><path fill="url(#isqXM0d)" class="jzqa5_bif"/><path fill="url(#irA61Hc)" class="jzqa5_bif"/><path fill="url(#ivd5uuc)" class="jzqa5_bif"/><path fill="url(#iFeLSpc)" class="jzqa5_bif"/><path fill="url(#iRSEYle)" class="jzqa5_bif"/><path fill="url(#i89XIWZ)" class="jzqa5_bif"/><path fill="url(#io0GKsc)" class="jzqa5_bif"/></g><path fill="url(#i8AElTc)" class="jzqa5_bif"/><path fill="url(#iG5GAKb)" class="jzqa5_bif"/><g filter="url(#iDKZLbd)"><path class="wmzaqbbiq"/></g><g filter="url(#iKf5uBj)"><path class="tpx2idbcg"/><path fill="url(#i9Oq1wc)" class="h83wnob_l"/><path fill="url(#ieM53Hc)" class="h83wnob_l"/><path fill="url(#idxIZsa)" class="h83wnob_l"/><path fill="url(#iP4WvYb)" class="h83wnob_l"/></g><path fill="url(#iIHUlDe)" class="h83wnob_l"/><path fill="url(#i1ZvRnc)" class="h83wnob_l"/><g filter="url(#iLsh0Oe)"><path class="iey1lvbkg"/></g><g filter="url(#iyhLMXp)"><path class="odn0o4b9a"/></g><path class="iwsk8qbgx"/><path fill="url(#i7QDFVd)" class="gv89kb92a"/><path class="uefdqc9nj"/><g filter="url(#icILPGd)"><path class="h1g0vw0qt"/><path fill="url(#iLUUCoI)" class="crtuyac6r"/></g><g filter="url(#iOvTKab)"><path fill="url(#iUu6Eue)" class="va-go5bwh"/></g><path class="o0ok5qkkx"/><path fill="url(#i4D75Gb)" class="sr0h1d87b"/><path class="wz-k625dm"/><g filter="url(#iKHnrBe)"><path fill="url(#iBXPAcU)" class="kx0iqc05r"/></g><g filter="url(#inro7Ne)"><ellipse transform="rotate(-27.914 12.899 11.9)" class="g_9po2pxb"/><ellipse fill="url(#is6fTtb)" transform="rotate(-27.914 12.899 11.9)" class="cyaokcc9k"/></g><g filter="url(#iO6125c)"><path class="xb5i_mkiv"/><path fill="url(#ik5xvyr)" class="m4ujcac-m"/><path fill="url(#ife407b)" class="m4ujcac-m"/></g><g filter="url(#iKsy8xd)"><path class="wn6-p9z7k"/><path fill="url(#iBF3veb)" class="mvim7ccql"/><path fill="url(#iHcwKgE)" class="mvim7ccql"/></g><g filter="url(#ivUAXTd)"><path stroke="url(#ippxbac)" class="kog8wrbvt"/></g><g filter="url(#iEgEfye)"><path class="pd58wexwn"/></g><g filter="url(#imEzK4b)"><path class="tf337wi0l"/></g><g filter="url(#imqUDKc)"><path class="dh-41cb-m"/></g><g filter="url(#ivIi8vd)"><path class="o4dsycb9t"/></g><g filter="url(#iTAFW2c)"><path class="emxa9acvd"/></g><path class="w5_sjm6sw"/><path fill="url(#imX5tuc)" class="blkufcbkz"/><path fill="url(#iklKFhd)" class="blkufcbkz"/><path fill="url(#iF26lYJ)" class="blkufcbkz"/><path fill="url(#ibkOc1D)" class="m_uqd5bep"/><path fill="url(#iMTbu0a)" class="f15z0sb-m"/><path fill="url(#iuFoQfc)" class="f15z0sb-m"/><path fill="url(#iNJVqsc)" class="f15z0sb-m"/><path fill="url(#iZQduEe)" class="f15z0sb-m"/><path fill="url(#iitk95b)" class="f15z0sb-m"/><path fill="url(#iV4RBve)" class="f15z0sb-m"/><path fill="url(#ikX8Wzd)" class="f15z0sb-m"/><path fill="url(#iWHd6np)" class="mxno9qm9q"/><path fill="url(#iMRBetc)" class="mxno9qm9q"/><path fill="url(#i7tVwed)" class="yk_uyhgen"/><path fill="url(#ifcYKSc)" class="yk_uyhgen"/><path fill="url(#iNr6HFe)" class="yk_uyhgen"/><path fill="url(#i0mjutc)" class="yk_uyhgen"/><path fill="url(#i95B4Td)" class="d074i_boa"/><path fill="url(#i13MQTU)" class="d074i_boa"/><path fill="url(#izoOTXc)" class="d074i_boa"/><path fill="url(#iisGW0d)" class="grxl85bvp"/><path fill="url(#iS0Iaty)" class="grxl85bvp"/><path fill="url(#iqFq8Ko)" class="pmce5gb2r"/><path fill="url(#iPBTYGe)" class="pmce5gb2r"/><path fill="url(#iTitP3d)" class="pmce5gb2r"/><path fill="url(#iPA6PUc)" class="pmce5gb2r"/><g filter="url(#ictN57d)"><path fill="url(#i7pyA3c)" class="thixcfbik"/><path fill="url(#iI9j9Zd)" class="thixcfbik"/></g><path fill="url(#ivXLhHb)" class="thixcfbik"/><g filter="url(#igKl3Yb)"><path fill="url(#i73yXId)" class="kv5z55b-o"/></g><defs><radialGradient id="i36Rpdd" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .828 14.8)scale(5.79283 7.23642)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="idoc3xe" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.546 9.974)scale(4.38021 5.75526)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iqWYWTb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.719 8.969)scale(2.71103 2.0817)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iZFAVJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62572 2.66023 -1.8739 -1.14518 10.457 10.496)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="irOwDHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.73125 3.29364 -4.57208 2.40325 11.555 2.621)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iu0Y8CF" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.583 7.453)scale(2.56774 3.58838)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iD43fte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32233 .67562 -1.40896 -4.84304 25.448 11.7)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iE7xYwe" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11.358 9.523)scale(3.65605 4.65727)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="ipceuqb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.063 -3.534)scale(3.52739 2.78996)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="i7ZjZYl" cx="0" cy="0" r="1" gradientTransform="matrix(1.89438 .1987 -.32196 3.06944 8.252 11.654)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iyUfkEX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05563 -4.66599 1.68405 -.381 22.428 10.834)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iCvinMC" cx="0" cy="0" r="1" gradientTransform="matrix(-.82342 -1.51591 1.71774 -.93304 9.592 14.8)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="i4Rfatd" cx="0" cy="0" r="1" gradientTransform="matrix(3.13528 -1.42513 1.74002 3.82804 21.078 13.325)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iB70k5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.52014 0 0 .6545 22.218 10.623)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="i9nW6ib" cx="0" cy="0" r="1" gradientTransform="matrix(1.9019 -.14147 .1106 1.48676 21.52 12.914)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="ingKAld" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.097 6.386)scale(1.33012)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="igJByge" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.468 8.197)scale(9.02114 12.0746)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="i9xq3ob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.74634 1.20848 -.84156 -1.91251 18.471 13.17)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="isqXM0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.62385 -4.94828 6.27844 2.06036 13.266 20.292)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="irA61Hc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61822 9.28749 -11.6092 -2.02275 17.277 11.57)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ndb61xwjr"/><stop offset="1" class="l57p2o49o"/></radialGradient><radialGradient id="ivd5uuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.89626 -7.93854 0 15.66 12.586)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="i-c7amj6z"/><stop offset="1" class="nmcs74byh"/></radialGradient><radialGradient id="iFeLSpc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.44 8.026)scale(8.86449 15.2619)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iRSEYle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44954 1.77899 0 18.888 11.568)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="i89XIWZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65328 1.89477 0 13.373 11.28)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="io0GKsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09608 4.0645 -3.25227 -.87704 17.731 8.65)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="i8AElTc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61898 0 0 -8.11903 22.407 13.442)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iG5GAKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.80406 7.42285 0 13.984 20.292)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="x-jwoabzw"/><stop offset="1" class="xses_zbmw"/></radialGradient><radialGradient id="i9Oq1wc" cx="0" cy="0" r="1" gradientTransform="matrix(-.57381 -2.5747 .7935 -.17684 16.977 14.357)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iP4WvYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.98176 0 0 -.27447 16.675 14.624)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="i1ZvRnc" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.08 9.491)scale(2.09509 2.51797)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="i7QDFVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02196 -1.62554 0 18.738 12.02)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iLUUCoI" cx="0" cy="0" r="1" gradientTransform="matrix(-.29213 -.37645 .51828 -.4022 18.45 12.127)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4D75Gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.02196 -1.62555 0 13.24 12.02)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="is6fTtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00974 -.62233 .74807 -.01171 12.88 12.296)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ik5xvyr" cx="0" cy="0" r="1" gradientTransform="matrix(1.58969 -3.47082 1.77558 .81324 8.862 9.35)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="ife407b" cx="0" cy="0" r="1" gradientTransform="rotate(-59.802 12.562 -5.518)scale(2.87874 1.54549)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="iBF3veb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.32 7.178)scale(6.13805 10.0354)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iHcwKgE" cx="0" cy="0" r="1" gradientTransform="matrix(-.26494 1.72216 -3.70514 -.57001 16.253 3.256)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="imX5tuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.562 30.373)" gradientUnits="userSpaceOnUse"><stop class="gfj1348zm"/><stop offset=".714" class="vqiy7zq_f"/></radialGradient><radialGradient id="iklKFhd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.407)" gradientUnits="userSpaceOnUse"><stop class="uatqp3rks"/><stop offset="1" class="oln0s8bds"/></radialGradient><radialGradient id="iF26lYJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.189)" gradientUnits="userSpaceOnUse"><stop class="leds28lfi"/><stop offset="1" class="x0hvtbbrr"/></radialGradient><radialGradient id="ibkOc1D" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.345 17.211)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="xjoxl1baz"/><stop offset="1" class="xm7oxtb8r"/></radialGradient><radialGradient id="iMTbu0a" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 14.913 18.627)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="fupnc-bzv"/><stop offset="1" class="h4nid6imp"/></radialGradient><radialGradient id="iuFoQfc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 2.06252 -1.29855 -3.22666 31 24.171)" gradientUnits="userSpaceOnUse"><stop class="qomb6ec0x"/><stop offset="1" class="ha79_8bui"/></radialGradient><radialGradient id="iNJVqsc" cx="0" cy="0" r="1" gradientTransform="rotate(116.107 1.618 13.268)scale(4.96085 7.77144)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="vxxihotpt"/><stop offset="1" class="amuq4_bzy"/></radialGradient><radialGradient id="iitk95b" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.39 -3.09)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="fjifp0bsg"/><stop offset="1" class="wn5ytjbyn"/></radialGradient><radialGradient id="ikX8Wzd" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -3 .29081 .6725 18.155 24.451)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="zlawngbku"/><stop offset="1" class="oc_o5xbok"/></radialGradient><radialGradient id="iWHd6np" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.405 17.78)" gradientUnits="userSpaceOnUse"><stop class="y0cud7bhd"/><stop offset="1" class="irfgqiu-v"/></radialGradient><radialGradient id="i7tVwed" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y0d2ypbdf"/><stop offset="1" class="tmdmcl4vt"/></radialGradient><radialGradient id="i95B4Td" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.43)" gradientUnits="userSpaceOnUse"><stop class="gi9rlrtiz"/><stop offset=".615" class="v4bxf0bxm"/></radialGradient><radialGradient id="iisGW0d" cx="0" cy="0" r="1" gradientTransform="rotate(25.705 -36.997 15.768)scale(1.9602 2.66792)" gradientUnits="userSpaceOnUse"><stop class="o6yqkabjh"/><stop offset=".697" class="iuvvk27wi"/></radialGradient><radialGradient id="iS0Iaty" cx="0" cy="0" r="1" gradientTransform="matrix(-.8664 .26697 -.4987 -1.61843 4.82 17.168)" gradientUnits="userSpaceOnUse"><stop class="e-dsjlbgb"/><stop offset="1" class="e4hi5lpxu"/></radialGradient><radialGradient id="iqFq8Ko" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.291 6.337)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="il1-__z0c"/><stop offset="1" class="bw58smb4a"/></radialGradient><radialGradient id="iPBTYGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.162 13.19)" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="egju40ogk"/></radialGradient><radialGradient id="iPA6PUc" cx="0" cy="0" r="1" gradientTransform="rotate(-25.641 56.237 -44.01)scale(2.59977 2.78402)" gradientUnits="userSpaceOnUse"><stop class="c64g55i6x"/><stop offset="1" class="ej8zfjbhh"/></radialGradient><radialGradient id="iI9j9Zd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.25)" gradientUnits="userSpaceOnUse"><stop class="jdjo_xq8q"/><stop offset="1" class="s3mfozy-p"/></radialGradient><radialGradient id="ivXLhHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.00475 -.26214 .85754 3.28688 4.382 18.154)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="mhzmsi1xs"/><stop offset="1" class="wbpqeub1g"/></radialGradient><filter id="iHOnuzc" width="19.167" height="19.667" x="6.53" y="1.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="iMsdQHx" width="4.204" height="4.054" x="8.06" y="10.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="iYj0YPs" width="4.054" height="4.304" x="20.043" y="10.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="iPJWpub" width="3.706" height="3.706" x="20.217" y="10.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".25"/></filter><filter id="iCT0Jqe" width="3.406" height="3.406" x="8.408" y="11.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".175"/></filter><filter id="iqD7MAc" width="12.837" height="14.101" x="9.571" y="6.592" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="iDKZLbd" width="3.365" height="4.378" x="14.102" y="11.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".25"/></filter><filter id="iKf5uBj" width="2.865" height="3.878" x="14.557" y="11.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".125"/></filter><filter id="iLsh0Oe" width="3.729" height="1.619" x="17.228" y="11.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="iyhLMXp" width="3.729" height="1.619" x="11.022" y="11.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="icILPGd" width=".939" height=".825" x="17.839" y="11.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".05"/></filter><filter id="iOvTKab" width="1.019" height="1.047" x="18.923" y="11.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".1"/></filter><filter id="iKHnrBe" width="1.139" height="1.206" x="13.326" y="11.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".1"/></filter><filter id="inro7Ne" width="1.098" height=".835" x="12.35" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".05"/></filter><filter id="iO6125c" width="5.198" height="5.578" x="8.089" y="4.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/><feGaussianBlur result="effect2_foregroundBlur_3987_24801" stdDeviation=".2"/></filter><filter id="iKsy8xd" width="10.901" height="7.153" x="12.073" y="2.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/><feGaussianBlur result="effect2_foregroundBlur_3987_24801" stdDeviation=".125"/></filter><filter id="ivUAXTd" width="1.286" height="2.754" x="12.047" y="4.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".1"/></filter><filter id="iEgEfye" width="8.206" height="4.358" x="15.201" y="5.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".5"/></filter><filter id="imEzK4b" width="2.984" height="1.44" x="11.376" y="8.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="imqUDKc" width="2.984" height="1.44" x="17.939" y="8.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="ivIi8vd" width="2.617" height="1.134" x="11.536" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".1"/></filter><filter id="iTAFW2c" width="2.617" height="1.134" x="17.946" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".1"/></filter><filter id="ictN57d" width="7.3" height="8.016" x="2" y="12.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.356863 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24801"/></filter><filter id="igKl3Yb" width="5.538" height="5.423" x="24.197" y="13.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24801" stdDeviation=".2"/></filter><linearGradient id="iBo66jb" x1="21.901" x2="14.173" y1="4.015" y2="17.569" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iC7LROb" x1="8.06" x2="10.4" y1="12.882" y2="12.882" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="ieM53Hc" x1="14.807" x2="15.989" y1="14.449" y2="14.449" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="idxIZsa" x1="15.989" x2="15.989" y1="15.34" y2="14.55" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iIHUlDe" x1="16.088" x2="16.088" y1="15.423" y2="15.247" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="iUu6Eue" x1="19.718" x2="19.322" y1="12.088" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBXPAcU" x1="14.177" x2="13.782" y1="12.088" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ippxbac" x1="12.073" x2="12.69" y1="4.015" y2="5.609" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="iZQduEe" x1="9.156" x2="10.486" y1="18.47" y2="19.093" gradientUnits="userSpaceOnUse"><stop class="x0-05wb5o"/><stop offset="1" class="b_wdx7bxu"/></linearGradient><linearGradient id="iV4RBve" x1="17.482" x2="17.906" y1="26.675" y2="25.72" gradientUnits="userSpaceOnUse"><stop class="jbvrfolcv"/><stop offset=".46" class="byl3sfbil"/></linearGradient><linearGradient id="iMRBetc" x1="24.108" x2="23.968" y1="18.281" y2="18.347" gradientUnits="userSpaceOnUse"><stop class="zb0hqnb-l"/><stop offset="1" class="sqzs4ozft"/></linearGradient><linearGradient id="ifcYKSc" x1="14.945" x2="14.231" y1="27.114" y2="25.507" gradientUnits="userSpaceOnUse"><stop class="na3bqccxs"/><stop offset="1" class="tndlebqua"/></linearGradient><linearGradient id="iNr6HFe" x1="22.968" x2="21.812" y1="18.64" y2="19.203" gradientUnits="userSpaceOnUse"><stop class="fp2c12bya"/><stop offset="1" class="xyqac8gqa"/></linearGradient><linearGradient id="i0mjutc" x1="3.231" x2="6.517" y1="28.257" y2="26.65" gradientUnits="userSpaceOnUse"><stop class="m_3r9vbdq"/><stop offset="1" class="iioqnhb4d"/></linearGradient><linearGradient id="i13MQTU" x1="27.52" x2="26.84" y1="19.626" y2="18.064" gradientUnits="userSpaceOnUse"><stop class="u8owb3akc"/><stop offset="1" class="yutka0byn"/></linearGradient><linearGradient id="izoOTXc" x1="26.75" x2="27.494" y1="17.361" y2="18.12" gradientUnits="userSpaceOnUse"><stop offset=".353" class="r80e5wbfg"/><stop offset="1" class="n7xbqubtn"/></linearGradient><linearGradient id="iTitP3d" x1="25.489" x2="25.997" y1="14.252" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="beeyfebmi"/><stop offset="1" class="uhgt8fd7p"/></linearGradient><linearGradient id="i7pyA3c" x1="8" x2="5.5" y1="15.72" y2="19.486" gradientUnits="userSpaceOnUse"><stop offset=".206" class="g9lwhpb_s"/><stop offset="1" class="f96e_t8ap"/></linearGradient><linearGradient id="i73yXId" x1="29.217" x2="24.074" y1="14.816" y2="17.683" gradientUnits="userSpaceOnUse"><stop class="ffwswni4j"/><stop offset="1" class="zcueg9l3v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-no-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.amuq4_bzy {
  stop-color: var(--svg-color--9771d7, #9771D7);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.aysl7_bmb {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M10.111 14.125a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b_wdx7bxu {
  stop-color: var(--svg-color--62429a, #62429A);
  stop-opacity: 0;
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.beeyfebmi {
  stop-color: var(--svg-color--8e6d54, #8E6D54);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.blkufcbkz {
  d: path("M25.5 29.97h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.bw58smb4a {
  stop-color: var(--svg-color--a17a65, #A17A65);
}

.byl3sfbil {
  stop-color: var(--svg-color--684c9e, #684C9E);
  stop-opacity: 0;
}

.c64g55i6x {
  stop-color: var(--svg-color--a9656c, #A9656C);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crtuyac6r {
  d: path("M18.657 11.657c.08.107-.087.238-.277.38s-.332.242-.412.135s.01-.309.2-.451s.41-.171.49-.064");
}

.cyaokcc9k {
  cx: 12.899px;
  cy: 11.9px;
  rx: 0.491px;
  ry: 0.248px;
}

.d074i_boa {
  d: path("M24.75 19.773a.885.885 0 0 1 .35-1.203l2.609-1.428a.899.899 0 1 1 .856 1.581l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.dh-41cb-m {
  fill: var(--svg-color--432a28, #432A28);
  d: path("M20.711 10.154a.35.35 0 0 0-.25-.426l-2.086-.543a.349.349 0 0 0-.175.675l2.086.543a.35.35 0 0 0 .425-.25");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e-dsjlbgb {
  stop-color: var(--svg-color--6b4237, #6B4237);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4hi5lpxu {
  stop-color: var(--svg-color--6b4237, #6B4237);
  stop-opacity: 0;
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.egju40ogk {
  stop-color: var(--svg-color--cca68c, #CCA68C);
  stop-opacity: 0;
}

.ej8zfjbhh {
  stop-color: var(--svg-color--a9656c, #A9656C);
  stop-opacity: 0;
}

.emxa9acvd {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.263 9.973l-2.017-.533");
}

.f007bp1ul {
  d: path("M10.111 14.125a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.f11-aub0q {
  d: path("M22.07 14.8a2.027 2.027 0 1 0 0-4.054a2.027 2.027 0 0 0 0 4.053");
}

.f15z0sb-m {
  d: path("m11.56 16.068l15.407 7.178a3.53 3.53 0 0 1 1.7 4.687a3.52 3.52 0 0 1-4.679 1.704L8.581 22.45a1.003 1.003 0 0 1-.483-1.341l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.f96e_t8ap {
  stop-color: var(--svg-color--8f575b, #8F575B);
}

.ffwswni4j {
  stop-color: var(--svg-color--c29a88, #C29A88);
}

.fjifp0bsg {
  stop-color: var(--svg-color--745b8c, #745B8C);
}

.fp2c12bya {
  stop-color: var(--svg-color--a680df, #A680DF);
}

.ft5dv1b6b {
  fill: none;
}

.fupnc-bzv {
  stop-color: var(--svg-color--8066bd, #8066BD);
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g_9po2pxb {
  cx: 12.899px;
  cy: 11.9px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.491px;
  ry: 0.248px;
}

.g-fa2m3lw {
  fill-rule: evenodd;
  d: path("M25.04 14.548a4.1 4.1 0 0 0 .408-1.797c0-.589-.121-1.141-.339-1.645h.007a4 4 0 0 0-.354-.646l-.003-.004a4.1 4.1 0 0 1-.663-2.23v-.013a4.156 4.156 0 0 0-4.155-4.156a.68.68 0 0 1-.574-.293A4.16 4.16 0 0 0 15.99 2.03c-1.39 0-2.626.688-3.378 1.734a.71.71 0 0 1-.574.293l-.107.001a4.156 4.156 0 0 0-4.048 4.155v.012c0 .79-.23 1.568-.663 2.231l-.003.005a4.16 4.16 0 0 0-.278 4.087c.09.178.09.395 0 .574a4.1 4.1 0 0 0-.408 1.772a4.05 4.05 0 0 0 4.054 4.053h10.81a4.05 4.05 0 0 0 4.054-4.053c0-.638-.153-1.237-.408-1.772a.65.65 0 0 1 0-.574M9.597 11.182H9.58l1.51 2.967c.155 3.53 1.533 0 4.898 0s4.832 3.93 4.988.399l1.43-4.027c-.067-1.568-1.204-1.678-1.43-1.678H16.92a4.87 4.87 0 0 1-4.018-2.108a.332.332 0 0 0-.58.064l-.104.244A2.9 2.9 0 0 1 10.72 8.6q-.03.01-.064.025l-.065.026c-.297.154-.994.617-1.02 1.812l.013.386z");
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g9lwhpb_s {
  stop-color: var(--svg-color--bb9373, #BB9373);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gfj1348zm {
  stop-color: var(--svg-color--6547af, #6547AF);
}

.gi9rlrtiz {
  stop-color: var(--svg-color--cca58e, #CCA58E);
}

.grxl85bvp {
  d: path("M7.246 19.743a.885.885 0 0 0-.351-1.203l-2.553-1.398a.899.899 0 1 0-.855 1.581l2.565 1.374a.885.885 0 0 0 1.194-.354");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gv89kb92a {
  d: path("M18.74 11.42a1.124 1.124 0 0 1 1.084 1.42h-2.172a1.13 1.13 0 0 1 1.088-1.42");
}

.h1g0vw0qt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.657 11.657c.08.107-.087.238-.277.38s-.332.242-.412.135s.01-.309.2-.451s.41-.171.49-.064");
}

.h4nid6imp {
  stop-color: var(--svg-color--593b97, #593B97);
}

.h83wnob_l {
  d: path("m15.508 12.317l-.67 2.142a.68.68 0 0 0 .656.88h.99a.68.68 0 0 0 .656-.88l-.67-2.142c-.143-.474-.812-.474-.962 0");
}

.ha79_8bui {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
  stop-opacity: 0;
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i-c7amj6z {
  stop-color: var(--svg-color--9f6394, #9F6394);
  stop-opacity: 0;
}

.iey1lvbkg {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.428 12.056c.334-.588.842-1.053 1.936-1.053c.48 0 .941.133 1.352.464c.338.274.293.624.03.755l-.7.4c-.82-.265-1.729-.301-2.618-.566");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iioqnhb4d {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0;
}

.il1-__z0c {
  stop-color: var(--svg-color--a37f67, #A37F67);
}

.irfgqiu-v {
  stop-color: var(--svg-color--58448e, #58448E);
}

.iuvvk27wi {
  stop-color: var(--svg-color--874f5d, #874F5D);
}

.iwsk8qbgx {
  fill: var(--svg-color--fff, #fff);
  d: path("M19 11.077a1.76 1.76 0 0 1 1.707 1.334a.345.345 0 0 1-.337.429h-2.81a.29.29 0 0 1-.286-.342A1.76 1.76 0 0 1 19 11.077");
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jbvrfolcv {
  stop-color: var(--svg-color--684c9e, #684C9E);
}

.jdjo_xq8q {
  stop-color: var(--svg-color--c49a85, #C49A85);
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jzqa5_bif {
  d: path("M9.581 11.182h.016l-.013-.334l-.013-.386c.026-1.195.723-1.658 1.02-1.812l.065-.026q.034-.015.064-.025a2.9 2.9 0 0 0 1.499-1.556l.103-.244a.332.332 0 0 1 .581-.064a4.87 4.87 0 0 0 4.018 2.108h4.056c.226 0 1.363.11 1.43 1.678l-.15 3.87c-.155 3.53-2.911 5.901-6.276 5.901s-6.122-2.37-6.277-5.9z");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kog8wrbvt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.347 4.532c.03.306.296 1.457.686 2.153");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kv5z55b-o {
  d: path("M26.691 15.593c.527-.847 1.795-1.665 2.462-1.988a.13.13 0 0 1 .153.034a.132.132 0 0 1-.034.196c-2.06 1.273-1.875 1.785-2.645 3.097c-.354.605-1.176 1.113-1.556 1.284l-.474-.899c.53-.28 1.463-.711 2.094-1.724");
}

.kx0iqc05r {
  d: path("M14.265 12.411c0-.363-.296-.605-.375-.678l-.364.351l.224.455z");
}

.l57p2o49o {
  stop-color: var(--svg-color--97577d, #97577D);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.leds28lfi {
  stop-color: var(--svg-color--785e96, #785E96);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m_3r9vbdq {
  stop-color: var(--svg-color--604c85, #604C85);
  stop-opacity: 0.939;
}

.m_uqd5bep {
  d: path("m6.81 20.54l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.m4ujcac-m {
  d: path("M9.604 5.23c.712-.756 2.06-.757 2.684-.644l.498 1.626c-.318-.05-.372-.002-.61.23c-.174 1.377-1.734 2.213-3.637 2.768c-.187-1.88.137-2.998 1.065-3.98");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhzmsi1xs {
  stop-color: var(--svg-color--996f67, #996F67);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mvim7ccql {
  d: path("M15.23 2.959c-1.428-.315-2.709 1.108-2.857 1.636c1.325 4.466 4.677 4.221 7.987 3.853c1.98-.22 2.195.683 2.364 1.12c0-4.954-4.212-5.884-7.459-6.601z");
}

.mxno9qm9q {
  d: path("m25.19 20.54l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.n7xbqubtn {
  stop-color: var(--svg-color--8c644c, #8C644C);
  stop-opacity: 0;
}

.na3bqccxs {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
}

.ndb61xwjr {
  stop-color: var(--svg-color--97577d, #97577D);
  stop-opacity: 0;
}

.nmcs74byh {
  stop-color: var(--svg-color--9f6394, #9F6394);
}

.o0ok5qkkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.977 11.077a1.76 1.76 0 0 0-1.706 1.334a.344.344 0 0 0 .337.429h2.81a.29.29 0 0 0 .287-.342a1.765 1.765 0 0 0-1.728-1.421");
}

.o4dsycb9t {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 9.973l2.017-.533");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o6yqkabjh {
  stop-color: var(--svg-color--9b7667, #9B7667);
}

.oc_o5xbok {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odn0o4b9a {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.55 12.056c-.334-.588-.842-1.053-1.936-1.053c-.479 0-.94.133-1.351.464c-.339.274-.293.624-.031.755l.7.4c.821-.265 1.73-.301 2.619-.566");
}

.oln0s8bds {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
  stop-opacity: 0;
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p6zaajppg {
  d: path("M22.07 14.125a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

.pd58wexwn {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m19.02 7.506l-1.795.33a.867.867 0 1 1-.158-1.72h2.949c1.744 0 2.32 1.758 2.392 2.359a3.96 3.96 0 0 0-3.388-.97");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmce5gb2r {
  d: path("m23 16.04l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qomb6ec0x {
  stop-color: var(--svg-color--8e7cc9, #8E7CC9);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r80e5wbfg {
  stop-color: var(--svg-color--8c644c, #8C644C);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.s3mfozy-p {
  stop-color: var(--svg-color--c49a85, #C49A85);
  stop-opacity: 0;
}

.sqzs4ozft {
  stop-color: var(--svg-color--8071aa, #8071AA);
  stop-opacity: 0;
}

.sr0h1d87b {
  d: path("M13.238 11.42a1.124 1.124 0 0 0-1.083 1.42h2.171a1.2 1.2 0 0 0 .041-.296a1.13 1.13 0 0 0-1.13-1.125");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tf337wi0l {
  fill: var(--svg-color--432a28, #432A28);
  d: path("M11.388 10.154a.35.35 0 0 1 .25-.426l2.086-.543a.349.349 0 0 1 .175.675l-2.086.543a.35.35 0 0 1-.425-.25");
}

.thixcfbik {
  d: path("m9 16.04l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.tmdmcl4vt {
  stop-color: var(--svg-color--69569a, #69569A);
}

.tndlebqua {
  stop-color: var(--svg-color--6a44b0, #6A44B0);
  stop-opacity: 0;
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tpx2idbcg {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.508 12.317l-.67 2.142a.68.68 0 0 0 .656.88h.99a.68.68 0 0 0 .656-.88l-.67-2.142c-.143-.474-.812-.474-.962 0");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.u8owb3akc {
  stop-color: var(--svg-color--a86e75, #A86E75);
}

.uatqp3rks {
  stop-color: var(--svg-color--9f7dda, #9F7DDA);
}

.uefdqc9nj {
  fill: var(--svg-color--000, #000);
  d: path("M18.096 12.544c0-.358.287-.644.644-.644a.64.64 0 0 1 .572.94h-1.139a.6.6 0 0 1-.077-.296");
}

.uhgt8fd7p {
  stop-color: var(--svg-color--8e6d54, #8E6D54);
  stop-opacity: 0;
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v4bxf0bxm {
  stop-color: var(--svg-color--b89377, #B89377);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.va-go5bwh {
  d: path("M19.741 12.396a1.06 1.06 0 0 0-.291-.583l-.327.359l.147.287z");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vqiy7zq_f {
  stop-color: var(--svg-color--53329c, #53329C);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vxxihotpt {
  stop-color: var(--svg-color--9771d7, #9771D7);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5_sjm6sw {
  fill: var(--svg-color--86004d, #86004D);
  d: path("M15.989 19.42c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.689-1.433 1.538s.642 1.537 1.433 1.537");
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wbpqeub1g {
  stop-color: var(--svg-color--996f67, #996F67);
  stop-opacity: 0;
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wmzaqbbiq {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.495 12.492l-.861 2.141a.68.68 0 0 0 .655.881h.99a.68.68 0 0 0 .657-.88l-.67-2.142c-.143-.475-.621-.475-.771 0");
}

.wn5ytjbyn {
  stop-color: var(--svg-color--745b8c, #745B8C);
  stop-opacity: 0;
}

.wn6-p9z7k {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.23 2.959c-1.428-.315-2.709 1.108-2.857 1.636c1.325 4.466 4.677 4.221 7.987 3.853c1.98-.22 2.195.683 2.364 1.12c0-4.954-4.212-5.884-7.459-6.601z");
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wz-k625dm {
  fill: var(--svg-color--000, #000);
  d: path("M13.882 12.544a.64.64 0 0 0-.644-.644a.64.64 0 0 0-.572.94h1.14a.64.64 0 0 0 .076-.296");
}

.x-jwoabzw {
  stop-color: var(--svg-color--74524f, #74524F);
}

.x0-05wb5o {
  stop-color: var(--svg-color--62429a, #62429A);
}

.x0hvtbbrr {
  stop-color: var(--svg-color--785e96, #785E96);
  stop-opacity: 0;
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xb5i_mkiv {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M9.604 5.23c.712-.756 2.06-.757 2.684-.644l.498 1.626c-.318-.05-.372-.002-.61.23c-.174 1.377-1.734 2.213-3.637 2.768c-.187-1.88.137-2.998 1.065-3.98");
}

.xjoxl1baz {
  stop-color: var(--svg-color--76679f, #76679F);
}

.xm7oxtb8r {
  stop-color: var(--svg-color--433169, #433169);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xses_zbmw {
  stop-color: var(--svg-color--74524f, #74524F);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xyqac8gqa {
  stop-color: var(--svg-color--a680df, #A680DF);
  stop-opacity: 0;
}

.y0cud7bhd {
  stop-color: var(--svg-color--705f9f, #705F9F);
}

.y0d2ypbdf {
  stop-color: var(--svg-color--8b64ce, #8B64CE);
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yk_uyhgen {
  d: path("M20.44 16.069L5.033 23.24a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.706l15.407-7.183c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.ylwpyxpit {
  d: path("M10.087 14.8a2.027 2.027 0 1 0 0-4.055a2.027 2.027 0 0 0 0 4.054");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yutka0byn {
  stop-color: var(--svg-color--a86e75, #A86E75);
  stop-opacity: 0;
}

.zb0hqnb-l {
  stop-color: var(--svg-color--8071aa, #8071AA);
}

.zcueg9l3v {
  stop-color: var(--svg-color--c29a88, #C29A88);
  stop-opacity: 0;
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zlawngbku {
  stop-color: var(--svg-color--5d3ca0, #5D3CA0);
}

.zpyf39lse {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M22.07 14.125a1.353 1.353 0 1 0 0-2.706a1.353 1.353 0 0 0 0 2.706");
}

</style>
