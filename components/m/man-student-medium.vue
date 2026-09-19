<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="kq9rnrb1y"/><path fill="url(#i5FgXQo)" class="ylq-9xbsk"/><path fill="url(#iry8tAv)" class="ylq-9xbsk"/><path fill="url(#ia6dLpc)" class="qu_og0b4w"/><path fill="url(#iVPnhob)" class="qu_og0b4w"/><path fill="url(#i0s8t7b)" class="qu_og0b4w"/><path fill="url(#i0e8Rdc)" class="qu_og0b4w"/><path fill="url(#iOxGnwd)" class="qu_og0b4w"/><path fill="url(#iiZCrQe)" class="qu_og0b4w"/><g filter="url(#i92EUle)"><path class="f8-tfybhp"/></g><path fill="url(#iUjnR0c)" class="st-ygmbqk"/><path fill="url(#i1N3dSb)" class="st-ygmbqk"/><path fill="url(#iImMLkc)" class="st-ygmbqk"/><path fill="url(#i4G84fe)" class="a9-i-1b7m"/><path fill="url(#iC3d1bb)" class="a9-i-1b7m"/><path fill="url(#ij2D0lc)" class="h8rlmxrrc"/><path fill="url(#i0Maiqc)" class="h8rlmxrrc"/><g filter="url(#izA6AFd)"><path stroke="url(#iSEEPIb)" class="y7thkbc9e"/></g><path fill="url(#iI97UMj)" class="za-84qfuc"/><path fill="url(#iRQ75ne)" class="za-84qfuc"/><path fill="url(#ibswwHb)" class="za-84qfuc"/><path fill="url(#i4FB7ce)" class="za-84qfuc"/><path fill="url(#irD8G9y)" class="za-84qfuc"/><path fill="url(#iEbI4Cc)" class="os3dnjboc"/><path fill="url(#iK7jxLc)" class="os3dnjboc"/><path fill="url(#ioZb2Mc)" class="os3dnjboc"/><path fill="url(#ihTnUxb)" class="wuqvatbew"/><path fill="url(#ieLDuXd)" class="wuqvatbew"/><g filter="url(#ia9pJGb)"><path fill="url(#irT8bOq)" class="kt53_909h"/><path fill="url(#irT8bOq)" class="ln3oh6mtg"/><path fill="url(#irT8bOq)" class="z1l6akwvg"/></g><g filter="url(#iwqHa0p)"><path stroke="url(#ida1YFh)" class="xg087bcwi"/></g><g filter="url(#i10otKV)"><circle fill="url(#iOUo27c)" class="tj8ynil5j"/></g><circle fill="url(#ikuoFCb)" class="tj8ynil5j"/><g filter="url(#i3ISW4d)"><circle fill="url(#ieIHVBb)" class="hwuv-qb3t"/></g><g filter="url(#iQJmgbd)"><circle fill="url(#iMCWkqd)" class="p6urogbph"/><circle fill="url(#ixwGILg)" class="p6urogbph"/></g><g filter="url(#iJ6fuae)"><circle class="o2vra3nob"/><circle fill="url(#i6glHud)" class="d5411-3fs"/><circle fill="url(#iMpbDJS)" class="d5411-3fs"/></g><g filter="url(#i7arird)"><path fill="url(#i4Ob7bj)" class="qpbz1tm0e"/><path fill="url(#iR7ZGvS)" class="qpbz1tm0e"/><path fill="url(#iiJV5qd)" class="qpbz1tm0e"/></g><path fill="url(#i2IXyZc)" class="n46dutfae"/><path fill="url(#iNdbpjb)" class="n46dutfae"/><path fill="url(#iUiHWyb)" class="n46dutfae"/><path fill="url(#ieZTuib)" class="n46dutfae"/><g filter="url(#iVLWDHc)"><path fill="url(#iVosv7b)" class="ifb9cibao"/></g><g filter="url(#ixpxved)"><path class="x0tysyb0j"/><path fill="url(#isbNVZd)" class="y9g1bf03w"/><path fill="url(#i095j3c)" class="y9g1bf03w"/><path fill="url(#iNd3uSd)" class="y9g1bf03w"/><path fill="url(#iWqUYTb)" class="y9g1bf03w"/></g><g filter="url(#iabJllb)"><path class="zu488vbar"/></g><g filter="url(#iuWF7gc)"><path class="ck12214qz"/><path fill="url(#io6PnFe)" class="u3utplk2m"/><path fill="url(#iFVGTZb)" class="u3utplk2m"/><path fill="url(#iJC7cuh)" class="u3utplk2m"/><path fill="url(#iM8h6cc)" class="u3utplk2m"/></g><path fill="url(#il6VBqc)" class="u3utplk2m"/><path stroke="url(#iqRW1gb)" class="tjnsz_b-l"/><g filter="url(#i6SCGPe)"><path class="qck74xynw"/><path fill="url(#iujSeDJ)" class="bv6v-1a6q"/></g><g filter="url(#iIQrClc)"><path class="w1j6vvb-r"/><path fill="url(#i5xFeGe)" class="jd0mxzhan"/></g><path class="r3shmzbzi"/><path fill="url(#iHlbsue)" class="gc-o28bep"/><path class="t0aew3aav"/><g filter="url(#ik8GLXc)"><path class="dppapmbwa"/><path fill="url(#iYy6Rjk)" class="egb7eob-l"/></g><g filter="url(#iclYTFb)"><path fill="url(#ie0sIOe)" class="yw0v0vbbz"/></g><path class="yspk7ck4c"/><path fill="url(#izREosd)" class="s9xrztnxa"/><path class="o1dyx2b2l"/><g filter="url(#i2ZIbjd)"><path fill="url(#i6Bzwyc)" class="mp8i1xdwf"/></g><g filter="url(#ib8S4Qb)"><ellipse transform="rotate(-27.914 13.946 9.876)" class="kchpb0bup"/><ellipse fill="url(#ikEAyYc)" transform="rotate(-27.914 13.946 9.876)" class="ms46ibcex"/></g><g filter="url(#iQ0IaKd)"><path stroke="url(#iefCX0c)" class="fxjbc1bsq"/></g><g filter="url(#iKBGdAd)"><path stroke="url(#i5SZDJd)" class="fz9yohbmn"/></g><g filter="url(#i0Qimqd)"><path stroke="url(#i1nuSFc)" class="o_a4hlu8r"/></g><g filter="url(#it98nnc)"><path fill="url(#iTZ4Wpc)" class="a0im4vbwh"/><path fill="url(#iFwpqTb)" class="a0im4vbwh"/></g><path fill="url(#i65FOPd)" class="nf4r7t_ne"/><path fill="url(#iwy5aJc)" class="nf4r7t_ne"/><path fill="url(#itW3kBD)" class="nf4r7t_ne"/><defs><radialGradient id="i5FgXQo" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.782 23.113)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iry8tAv" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.188 21.457)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="ia6dLpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.488 21.348)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iVPnhob" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.48 16.895)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="i0s8t7b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.063 15.55)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="i0e8Rdc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.813 15.316)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="iOxGnwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.48 23.613)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iiZCrQe" cx="0" cy="0" r="1" gradientTransform="rotate(85.281 -.12 16.01)scale(4.21461 7.75523)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="w7sh5cjwf"/><stop offset="1" class="ddl9sxmqm"/></radialGradient><radialGradient id="iUjnR0c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.784 18.218)" gradientUnits="userSpaceOnUse"><stop class="xoj0cjj5j"/><stop offset="1" class="gietximnj"/></radialGradient><radialGradient id="i1N3dSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.466 16.984)" gradientUnits="userSpaceOnUse"><stop class="ktrl6_0jb"/><stop offset="1" class="ki0_-eiqi"/></radialGradient><radialGradient id="iImMLkc" cx="0" cy="0" r="1" gradientTransform="scale(4.26182 4.5407)rotate(90 .33 3.533)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="v71br5-3y"/><stop offset="1" class="eqeqhqb5o"/></radialGradient><radialGradient id="iC3d1bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.055 11.667)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="ij2D0lc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.313 12.038)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="i0Maiqc" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.976 12.43)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iRQ75ne" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.352 8.56)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ibswwHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.813 13.106)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="irD8G9y" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.813 16.895)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iEbI4Cc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.485 29.994)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iK7jxLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.25 29.994)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="ihTnUxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.592 29.994)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ieLDuXd" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.541 23.155)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iOUo27c" cx="0" cy="0" r="1" gradientTransform="matrix(1.77103 0 0 3.09932 9.948 10.66)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="ikuoFCb" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 9.031 3.144)scale(1.67201)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="ixwGILg" cx="0" cy="0" r="1" gradientTransform="matrix(.83432 -.60752 .6934 .95227 21.61 10.394)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i6glHud" cx="0" cy="0" r="1" gradientTransform="matrix(.82883 -1.52445 .89227 .48512 21.192 11.49)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iMpbDJS" cx="0" cy="0" r="1" gradientTransform="matrix(.26168 .25902 -.33391 .33734 21.233 10.66)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iR7ZGvS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31912 1.62354 0 18.792 9.377)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iiJV5qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.38677 1.72457 0 14.192 9.513)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iUiHWyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40518 -10.4177 0 16.295 9.113)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="l8ndgrbku"/><stop offset="1" class="rn6l6ybvm"/></radialGradient><radialGradient id="ieZTuib" cx="0" cy="0" r="1" gradientTransform="matrix(.15662 2.53363 -7.19543 .4448 16.297 4.707)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="e321gbctj"/><stop offset="1" class="t3xo2c7rr"/></radialGradient><radialGradient id="isbNVZd" cx="0" cy="0" r="1" gradientTransform="matrix(.80517 -2.98386 1.10651 .29858 20.81 6.517)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="i095j3c" cx="0" cy="0" r="1" gradientTransform="matrix(3.86008 .35522 -.191 2.07554 19.152 4.74)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iNd3uSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.69465 -2.62453 0 16.424 1.98)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iWqUYTb" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 18.5 -10.723)scale(3.8461 6.02558)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iM8h6cc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19871 -.63842 0 16.754 12.282)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iujSeDJ" cx="0" cy="0" r="1" gradientTransform="matrix(.10515 -.60883 1.80116 .31109 18.89 8.557)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i5xFeGe" cx="0" cy="0" r="1" gradientTransform="matrix(.10516 -.60883 1.80126 .31112 13.694 8.557)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iHlbsue" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8186 -1.30208 0 18.623 9.973)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iYy6Rjk" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 11.66 .525)scale(.38169 .52548)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izREosd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81865 -1.30215 0 14.22 9.973)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ikEAyYc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.983 -1.76)scale(.49858 .59932)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTZ4Wpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6666 -3.56716 3.98507 -.7447 19.009 5.878)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iFwpqTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.97411 -7.12707 0 16.415 2.868)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iwy5aJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.22 2.395)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="itW3kBD" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.25 3.02)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><linearGradient id="i4G84fe" x1="24.17" x2="25.356" y1="8.941" y2="8.941" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="iSEEPIb" x1="25.416" x2="25.416" y1="3.708" y2="11.475" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iI97UMj" x1="25.965" x2="23.645" y1="14.806" y2="14.806" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="i4FB7ce" x1="23.764" x2="24.639" y1="14.485" y2="14.664" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="ioZb2Mc" x1="9.395" x2="8.969" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="irT8bOq" x1="16.48" x2="16.48" y1="29.863" y2="23.43" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="ida1YFh" x1="13.432" x2="14.004" y1="4.445" y2="5.782" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="ieIHVBb" x1="11.633" x2="10.986" y1="10.942" y2="10.942" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iMCWkqd" x1="22.33" x2="21.504" y1="9.559" y2="12.119" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="i4Ob7bj" x1="20.497" x2="12.79" y1="11.054" y2="12.202" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="i2IXyZc" x1="10.979" x2="12.877" y1="13.775" y2="13.707" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iNdbpjb" x1="21.39" x2="20.268" y1="12.925" y2="12.828" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iVosv7b" x1="16.19" x2="24.409" y1="8.676" y2="5.734" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="io6PnFe" x1="15.552" x2="16.499" y1="11.719" y2="11.719" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iFVGTZb" x1="17.371" x2="16.336" y1="12.045" y2="12.03" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iJC7cuh" x1="16.621" x2="16.621" y1="12.794" y2="12.216" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="il6VBqc" x1="16.551" x2="16.551" y1="12.836" y2="12.667" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iqRW1gb" x1="15.378" x2="15.817" y1="14.424" y2="13.73" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ie0sIOe" x1="19.408" x2="19.092" y1="10.027" y2="10.222" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6Bzwyc" x1="14.97" x2="14.654" y1="10.027" y2="10.222" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iefCX0c" x1="19.424" x2="19" y1="7.868" y2="7.001" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i5SZDJd" x1="14.07" x2="12.87" y1="7.739" y2="7.235" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i1nuSFc" x1="11.719" x2="11.719" y1="5.706" y2="7.882" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="i65FOPd" x1="18.25" x2="16.969" y1="3.957" y2="-.418" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient><filter id="i92EUle" width="5.32" height="9.565" x="13.806" y="9.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".2"/></filter><filter id="izA6AFd" width=".65" height="8.268" x="24.591" y="3.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".125"/></filter><filter id="ia9pJGb" width="8.964" height="6.734" x="11.998" y="23.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".075"/></filter><filter id="iwqHa0p" width="1.172" height="2.394" x="13.132" y="3.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".125"/></filter><filter id="i10otKV" width="3.57" height="3.37" x="9.948" y="8.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1590"/></filter><filter id="i3ISW4d" width="3.008" height="3.008" x="10.128" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".25"/></filter><filter id="iQJmgbd" width="3.62" height="3.62" x="19.549" y="8.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1590"/></filter><filter id="iJ6fuae" width="3.008" height="3.008" x="19.729" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".25"/></filter><filter id="i7arird" width="10.469" height="12.239" x="11.219" y="4.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1590"/></filter><filter id="iVLWDHc" width="8.285" height="7.095" x="14.898" y="3.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation="1"/></filter><filter id="ixpxved" width="12.718" height="8.542" x="10.065" y="1.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1590"/></filter><filter id="iabJllb" width="3.276" height="4.206" x="14.545" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".375"/></filter><filter id="iuWF7gc" width="2.394" height="3.206" x="15.227" y="9.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".125"/></filter><filter id="i6SCGPe" width="3.005" height="1.886" x="17.617" y="6.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1590"/></filter><filter id="iIQrClc" width="3.005" height="1.886" x="12.422" y="6.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1590"/></filter><filter id="ik8GLXc" width=".792" height=".701" x="17.883" y="9.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".05"/></filter><filter id="iclYTFb" width=".896" height=".918" x="18.732" y="9.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".1"/></filter><filter id="i2ZIbjd" width=".992" height="1.046" x="14.249" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".1"/></filter><filter id="ib8S4Qb" width=".919" height=".709" x="13.486" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".05"/></filter><filter id="iQ0IaKd" width="3.367" height="1.935" x="17.35" y="6.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".25"/></filter><filter id="iKBGdAd" width="3.445" height="1.993" x="12.082" y="7.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".25"/></filter><filter id="i0Qimqd" width="1.01" height="2.283" x="11.214" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1590" stdDeviation=".125"/></filter><filter id="it98nnc" width="12.214" height="2.931" x="10.327" y="3.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1590"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-student-medium" /></template>
<style>
.a0im4vbwh {
  d: path("m10.327 5.118l1.174-1.864l9.844-.11l1.196 1.974c-4.664 1.61-10.124.734-12.214 0");
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a9-i-1b7m {
  d: path("M25.213 11.667V2.804h-.8v8.863z");
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bv6v-1a6q {
  d: path("m20.178 7.916l-.001-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.156-.108a2.6 2.6 0 0 0-.424-.213a2.86 2.86 0 0 0-1.506-.16a.539.539 0 0 0 .168 1.065c.402-.064.723.01.942.097a1.5 1.5 0 0 1 .311.167a.539.539 0 0 0 .685-.831");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.ck12214qz {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m16.039 10.373l-.537 1.715a.544.544 0 0 0 .525.706h.794a.546.546 0 0 0 .525-.706l-.536-1.715c-.115-.38-.651-.38-.771 0");
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

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d5411-3fs {
  cx: 21.233px;
  cy: 10.661px;
  r: 1.004px;
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.ddl9sxmqm {
  stop-color: var(--svg-color--1c1026, #1C1026);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dppapmbwa {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.56 9.682c.063.085-.07.19-.223.304s-.266.194-.33.108c-.064-.085.007-.247.16-.361c.152-.114.328-.137.392-.052");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e321gbctj {
  stop-color: var(--svg-color--6f4646, #6F4646);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.egb7eob-l {
  d: path("M18.56 9.682c.063.085-.07.19-.223.304s-.266.194-.33.108c-.064-.085.007-.247.16-.361c.152-.114.328-.137.392-.052");
}

.eqeqhqb5o {
  stop-color: var(--svg-color--5f4132, #5F4132);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f8-tfybhp {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.186 18.864c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587Z");
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.fxjbc1bsq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M18.1 7.77c.434-.076 1.28-.054 1.867.401");
}

.fz9yohbmn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.833 8.293c.33-.292 1.05-.599 1.944-.457");
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gc-o28bep {
  d: path("M18.625 9.491a.9.9 0 0 1 .868 1.138h-1.74a.904.904 0 0 1 .872-1.138");
}

.gietximnj {
  stop-color: var(--svg-color--7e5059, #7E5059);
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.h8rlmxrrc {
  d: path("M24.413 11.643a.837.837 0 1 0 .8 0z");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hwuv-qb3t {
  cx: 11.633px;
  cy: 10.661px;
  r: 1.004px;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.ifb9cibao {
  d: path("M20.727 5.62L17.62 6.654a1.057 1.057 0 0 0 .474 2.05l3.088-.414z");
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.jd0mxzhan {
  d: path("m12.616 7.916l.001-.001l.002-.002l.005-.004l.012-.01a2 2 0 0 1 .156-.108c.1-.063.243-.141.424-.213a2.86 2.86 0 0 1 1.506-.16a.539.539 0 0 1-.168 1.065a1.8 1.8 0 0 0-.942.097a1.5 1.5 0 0 0-.311.167a.539.539 0 0 1-.685-.831");
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kchpb0bup {
  cx: 13.946px;
  cy: 9.876px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.393px;
  ry: 0.199px;
}

.ki0_-eiqi {
  stop-color: var(--svg-color--804d60, #804D60);
  stop-opacity: 0;
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.kq9rnrb1y {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.485 15.494c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kt53_909h {
  d: path("M12.148 23.77c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.ktrl6_0jb {
  stop-color: var(--svg-color--804d60, #804D60);
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l8ndgrbku {
  stop-color: var(--svg-color--9f6b75, #9F6B75);
  stop-opacity: 0;
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln3oh6mtg {
  d: path("M16.134 23.77c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mp8i1xdwf {
  d: path("M15.04 10.286c0-.291-.236-.485-.3-.544l-.291.282l.18.364z");
}

.ms46ibcex {
  cx: 13.946px;
  cy: 9.876px;
  rx: 0.393px;
  ry: 0.199px;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n46dutfae {
  d: path("M11.219 8.59c0-.268.108-.591.324-.753l.163-.161c.27-.216.379-.539.379-.862v-.86c0-.27.162-.485.433-.539c.65-.162 2.003-.43 3.952-.43s3.302.268 3.951.43c.217.054.433.27.433.538v.861c0 .323.163.646.38.862c.506.355.474.55.432.969a47 47 0 0 0-.108 1.453h.018l-.268 3.994c-.162 1.786-1.566 3.031-3.24 3.031h-3.24c-1.728 0-3.078-1.245-3.24-3.03c-.14-1.834-.202-3.672-.37-5.502");
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nf4r7t_ne {
  d: path("M24.423 3.604H8.453c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o_a4hlu8r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.85 5.805v.906c-.008.15-.071.485-.26.628");
}

.o1dyx2b2l {
  fill: var(--svg-color--000, #000);
  d: path("M14.734 10.392a.514.514 0 0 0-.516-.516a.514.514 0 0 0-.459.753h.913a.5.5 0 0 0 .062-.237");
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o2vra3nob {
  cx: 21.233px;
  cy: 10.661px;
  r: 1.004px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.os3dnjboc {
  d: path("M9.25 29.994V18.208a10.97 10.97 0 0 0-3.765 8.286v3.5z");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p6urogbph {
  cx: 21.233px;
  cy: 10.661px;
  r: 1.685px;
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

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qck74xynw {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m20.178 7.916l-.001-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.156-.108a2.6 2.6 0 0 0-.424-.213a2.86 2.86 0 0 0-1.506-.16a.539.539 0 0 0 .168 1.065c.402-.064.723.01.942.097a1.5 1.5 0 0 1 .311.167a.539.539 0 0 0 .685-.831");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qpbz1tm0e {
  d: path("m11.277 10.042l.05.002s-.054-.861-.108-1.453c0-.27.108-.592.324-.754l.163-.161c.27-.216.379-.539.379-.862v-.86c0-.27.162-.485.433-.539c.65-.162 2.003-.43 3.952-.43s3.302.268 3.951.43c.217.054.433.27.433.538v.861c0 .323.163.646.38.862c.506.355.474.55.432.969a47 47 0 0 0-.108 1.453h.018l-.268 3.994c-.162 1.786-1.566 3.031-3.24 3.031h-3.24c-1.728 0-3.078-1.245-3.24-3.03z");
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qu_og0b4w {
  d: path("M23.5 18.093a.24.24 0 0 0-.058-.29c-1.856-1.602-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.014 7.013-4.614");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r3shmzbzi {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.834 9.217a1.41 1.41 0 0 1 1.367 1.068a.277.277 0 0 1-.27.344H17.68a.232.232 0 0 1-.23-.274a1.41 1.41 0 0 1 1.384-1.138");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rn6l6ybvm {
  stop-color: var(--svg-color--7a4858, #7A4858);
}

.s9xrztnxa {
  d: path("M14.218 9.491a.9.9 0 0 0-.868 1.138h1.74a1 1 0 0 0 .033-.237a.907.907 0 0 0-.905-.9");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.st-ygmbqk {
  d: path("M16.186 18.864c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587");
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t0aew3aav {
  fill: var(--svg-color--000, #000);
  d: path("M18.11 10.392c0-.287.229-.516.515-.516a.514.514 0 0 1 .459.753h-.913a.47.47 0 0 1-.061-.237");
}

.t3xo2c7rr {
  stop-color: var(--svg-color--6f4646, #6F4646);
  stop-opacity: 0;
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tj8ynil5j {
  cx: 11.633px;
  cy: 10.661px;
  r: 1.685px;
}

.tjnsz_b-l {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.05 13.444c.396.207.87.325 1.374.325c.51 0 .978-.118 1.375-.325a.205.205 0 0 1 .243.04a.19.19 0 0 1 .021.243m-3.014-.283l2.973.255m-2.973-.255a.204.204 0 0 0-.243.042a.19.19 0 0 0-.02.241m.263-.283l-.222.255m3.236.028l-.041-.028m.041.028l-.041-.028m.041.028a1.96 1.96 0 0 1-1.639.876a1.96 1.96 0 0 1-1.639-.876m3.237-.028a1.91 1.91 0 0 1-1.598.854a1.91 1.91 0 0 1-1.597-.854m-.042.028l.042-.028m-.042.028l.042-.028");
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.u3utplk2m {
  d: path("m16.039 10.373l-.537 1.715a.544.544 0 0 0 .525.706h.794a.546.546 0 0 0 .525-.706l-.536-1.715c-.115-.38-.651-.38-.771 0");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v71br5-3y {
  stop-color: var(--svg-color--5f4132, #5F4132);
  stop-opacity: 0;
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w1j6vvb-r {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m12.616 7.916l.001-.001l.002-.002l.005-.004l.012-.01a2 2 0 0 1 .156-.108c.1-.063.243-.141.424-.213a2.86 2.86 0 0 1 1.506-.16a.539.539 0 0 1-.168 1.065a1.8 1.8 0 0 0-.942.097a1.5 1.5 0 0 0-.311.167a.539.539 0 0 1-.685-.831");
}

.w7sh5cjwf {
  stop-color: var(--svg-color--1c1026, #1C1026);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wuqvatbew {
  d: path("M23.71 29.994V18.208a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.x0tysyb0j {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m21.288 4.123l.433.216c.757.376 1.19 1.238 1.028 2.153l-.595 3.068c-.053.317-.263.53-.578.538h-.018s.054-.915.108-1.453c.044-.437-.032-.57-.433-.97c-.216-.215-.379-.537-.379-.86v-.862c0-.269-.216-.484-.433-.538c-.65-.161-2.003-.43-3.951-.43c-1.95 0-3.303.269-3.952.43a.525.525 0 0 0-.433.538v.862c0 .322-.109.645-.38.86l-.162.162c-.216.162-.324.485-.324.754c.054.592.108 1.453.108 1.453l-.05-.002a.64.64 0 0 1-.6-.536l-.595-3.068c-.109-.861.325-1.723 1.082-2.1l.434-.215c.27-.161.54-.376.811-.592l.975-1.022c.595-.539 1.461-.584 2.22-.207c.54.162 1.136.045 1.678-.116c.812-.27 1.732-.054 2.381.538l.813.807c.216.27.487.43.812.592");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xg087bcwi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.432 4.084c.024.256.246 1.214.572 1.795");
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xoj0cjj5j {
  stop-color: var(--svg-color--976c65, #976C65);
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.y7thkbc9e {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.916 3.708v7.767");
}

.y9g1bf03w {
  d: path("m21.288 4.123l.433.216c.757.376 1.19 1.238 1.028 2.153l-.595 3.068c-.053.317-.263.53-.578.538h-.018s.054-.915.108-1.453c.044-.437-.032-.57-.433-.97c-.216-.215-.379-.537-.379-.86v-.862c0-.269-.216-.484-.433-.538c-.65-.161-2.003-.43-3.951-.43c-1.95 0-3.303.269-3.952.43a.525.525 0 0 0-.433.538v.862c0 .322-.109.645-.38.86l-.162.162c-.216.162-.324.485-.324.754c.054.592.108 1.453.108 1.453l-.05-.002a.64.64 0 0 1-.6-.536l-.595-3.068c-.109-.861.325-1.723 1.082-2.1l.434-.215c.27-.161.54-.376.811-.592l.975-1.022c.595-.539 1.461-.584 2.22-.207c.54.162 1.136.045 1.678-.116c.812-.27 1.732-.054 2.381.538l.813.807c.216.27.487.43.812.592");
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ylq-9xbsk {
  d: path("M16.485 15.494c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.yspk7ck4c {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.01 9.217a1.41 1.41 0 0 0-1.368 1.068a.277.277 0 0 0 .27.344h2.252a.232.232 0 0 0 .229-.274a1.414 1.414 0 0 0-1.384-1.138");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yw0v0vbbz {
  d: path("M19.427 10.273a.85.85 0 0 0-.233-.467l-.262.288l.118.23z");
}

.z1l6akwvg {
  d: path("M20.12 23.77c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.za-84qfuc {
  d: path("m23.96 13.604l-.517 2.239a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.zu488vbar {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m16.146 10.537l-.828 1.716c-.102.352.144.705.493.705h.744c.349 0 .595-.358.493-.705l-.503-1.716c-.108-.38-.286-.38-.399 0");
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
