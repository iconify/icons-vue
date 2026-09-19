<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hz94g6b_c"/><path fill="url(#iKVFAwd)" class="j4en6db6n"/><path fill="url(#is7Ppbe)" class="j4en6db6n"/><path fill="url(#i7wRKgI)" class="bnco9qkiy"/><path fill="url(#iAxxKCc)" class="bnco9qkiy"/><path fill="url(#iVVcLRF)" class="bnco9qkiy"/><path fill="url(#iixesKc)" class="bnco9qkiy"/><path fill="url(#iUcCFNd)" class="bnco9qkiy"/><path fill="url(#ibn1XFS)" class="bnco9qkiy"/><g filter="url(#irYYwKc)"><path class="o28d1mb5b"/></g><path fill="url(#ir4RiHd)" class="p0uazivnq"/><path fill="url(#iSR2Eqc)" class="p0uazivnq"/><path fill="url(#iENookQ)" class="p0uazivnq"/><path fill="url(#iqiZzCe)" class="srh6f0bdo"/><path fill="url(#iKiYKBe)" class="srh6f0bdo"/><path fill="url(#iJPfKbb)" class="j6jlvoyxn"/><path fill="url(#i8j9lMb)" class="j6jlvoyxn"/><g filter="url(#ivToN0b)"><path stroke="url(#iY5Vg3Z)" class="f5z4hbbta"/></g><path fill="url(#iLnBP2d)" class="v3dn5qbxz"/><path fill="url(#i7UzBzb)" class="v3dn5qbxz"/><path fill="url(#inepqOc)" class="v3dn5qbxz"/><path fill="url(#iVmco5d)" class="v3dn5qbxz"/><path fill="url(#iilX30c)" class="v3dn5qbxz"/><path fill="url(#iYewBkw)" class="k1nrq-b0r"/><path fill="url(#itVEOvb)" class="k1nrq-b0r"/><path fill="url(#iZam77d)" class="k1nrq-b0r"/><path fill="url(#it5qvTc)" class="mcieo-bmu"/><path fill="url(#i3B04Ne)" class="mcieo-bmu"/><g filter="url(#i504tPe)"><path fill="url(#iN8V0WS)" class="mncnzu0gf"/><path fill="url(#iN8V0WS)" class="ngokvxj-f"/><path fill="url(#iN8V0WS)" class="zetzp0vmo"/></g><g filter="url(#idUGEQL)"><circle fill="url(#i9hY9Le)" class="vpv96wbod"/></g><g filter="url(#i7giRAd)"><circle fill="url(#iWYdasD)" class="ed1yx_btv"/></g><g filter="url(#iW8nrOb)"><circle fill="url(#i9NoRTb)" class="t7pyqfr7j"/><circle fill="url(#ihSaGte)" class="t7pyqfr7j"/></g><g filter="url(#ienZBFc)"><circle class="vhol5yblb"/><circle fill="url(#i6L2acd)" class="r72kq1vnm"/><circle fill="url(#iANydBb)" class="r72kq1vnm"/></g><g filter="url(#ieGSCWu)"><path fill="url(#iDcRqyc)" class="ltzewobth"/><path fill="url(#igJ1PTj)" class="ltzewobth"/><path fill="url(#iAamgwe)" class="ltzewobth"/><path fill="url(#imy27Rc)" class="ltzewobth"/><path fill="url(#ioQXZQb)" class="ltzewobth"/><path fill="url(#iqfA5Dc)" class="ltzewobth"/></g><g filter="url(#iuREcCF)"><path class="f-7tomxwv"/><path fill="url(#ii5fqBe)" class="q1bzoib_u"/><path fill="url(#iPr5JGb)" class="q1bzoib_u"/><path fill="url(#iEtk0gA)" class="q1bzoib_u"/><path fill="url(#iwwnh2c)" class="q1bzoib_u"/><path fill="url(#iH8UGhb)" class="q1bzoib_u"/></g><path fill="url(#iKEKRTu)" class="q1bzoib_u"/><path fill="url(#i3rYo9s)" class="q1bzoib_u"/><g filter="url(#ieLFkCw)"><path class="ioc_rfocq"/></g><g filter="url(#im05ZDd)"><path class="ho8ocib6i"/><path fill="url(#iSfxPGc)" class="nie6_abxt"/><path fill="url(#iDh1VBc)" class="nie6_abxt"/><path fill="url(#i2xZkNb)" class="nie6_abxt"/></g><path fill="url(#iu75edc)" class="nie6_abxt"/><path stroke="url(#iHmaQVD)" class="cg6jk9bgb"/><g filter="url(#iK8jkcb)"><path class="rztl4kb9y"/></g><g filter="url(#i3bPZPb)"><path class="vywwzlbha"/></g><path class="vfhx5qbgf"/><path fill="url(#i6ho0io)" class="vqcq5_liq"/><path class="v7zls1bga"/><g filter="url(#i7jKHpc)"><path class="saw75ubnw"/><path fill="url(#iJbluXc)" class="eahtdcbss"/></g><g filter="url(#iZOdeNd)"><path fill="url(#iumaQfj)" class="g9pdkgm1k"/></g><path class="djg41y0cy"/><path fill="url(#iOGubYc)" class="sbmfu45lf"/><path class="z734mzb2t"/><g filter="url(#iBtgNOb)"><path fill="url(#iQL6u0z)" class="eia3v2wie"/></g><g filter="url(#iMkyRod)"><ellipse transform="rotate(-27.914 13.997 9.865)" class="r7-b7wb6k"/><ellipse fill="url(#i4SZEBd)" transform="rotate(-27.914 13.997 9.865)" class="g33qegbha"/></g><g filter="url(#iZN7TIe)"><path class="sntswj96l"/></g><g filter="url(#iCbTApe)"><path class="on6m7rb5p"/></g><g filter="url(#iAerJfe)"><path fill="url(#id16fLd)" class="dfrzfnapl"/><path fill="url(#iwoKyJc)" class="dfrzfnapl"/></g><path fill="url(#iTYveNc)" class="c7bfsab8q"/><path fill="url(#iHwqNCc)" class="c7bfsab8q"/><path fill="url(#iXcSAKd)" class="c7bfsab8q"/><defs><radialGradient id="iKVFAwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.782 23.092)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="is7Ppbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.188 21.435)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="i7wRKgI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.488 21.326)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iAxxKCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.48 16.873)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iVVcLRF" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.063 15.53)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iixesKc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.813 15.294)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="iUcCFNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.48 23.592)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="ibn1XFS" cx="0" cy="0" r="1" gradientTransform="rotate(85.281 -.108 15.999)scale(4.21461 7.75523)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="w7sh5cjwf"/><stop offset="1" class="ddl9sxmqm"/></radialGradient><radialGradient id="ir4RiHd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.784 18.197)" gradientUnits="userSpaceOnUse"><stop class="dn_8aox9x"/><stop offset="1" class="ws5zlibzm"/></radialGradient><radialGradient id="iSR2Eqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.466 16.962)" gradientUnits="userSpaceOnUse"><stop class="etclelb-u"/><stop offset="1" class="syayv9bph"/></radialGradient><radialGradient id="iENookQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.466 14.52)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="f8avqachq"/><stop offset="1" class="k-u3pqb_i"/></radialGradient><radialGradient id="iKiYKBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.055 11.645)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="iJPfKbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.313 12.016)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="i8j9lMb" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.976 12.408)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="i7UzBzb" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.353 8.549)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="inepqOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.813 13.084)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="iilX30c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.813 16.873)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iYewBkw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.485 29.972)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="itVEOvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.25 29.972)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="it5qvTc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.592 29.972)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="i3B04Ne" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.542 23.133)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="i9hY9Le" cx="0" cy="0" r="1" gradientTransform="matrix(1.76825 0 0 3.09445 10.005 10.649)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="ihSaGte" cx="0" cy="0" r="1" gradientTransform="matrix(.833 -.60656 .6923 .95077 21.648 10.382)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="i6L2acd" cx="0" cy="0" r="1" gradientTransform="matrix(.82752 -1.52205 .89086 .48435 21.231 11.477)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iANydBb" cx="0" cy="0" r="1" gradientTransform="matrix(.26127 .25862 -.33339 .3368 21.274 10.648)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="igJ1PTj" cx="0" cy="0" r="1" gradientTransform="rotate(96.041 5.257 11.878)scale(10.6631 10.1876)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="mx6r32s2r"/><stop offset=".835" class="a-e0cj8zq"/><stop offset="1" class="j61mf2btk"/></radialGradient><radialGradient id="imy27Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31705 1.62098 0 18.835 9.368)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="ioQXZQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40147 1.74286 0 14.242 9.334)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iqfA5Dc" cx="0" cy="0" r="1" gradientTransform="matrix(.15637 2.52964 -7.1841 .4441 16.344 4.705)" gradientUnits="userSpaceOnUse"><stop offset=".514" class="u5-qxxbev"/><stop offset="1" class="bjxhdkbfc"/></radialGradient><radialGradient id="ii5fqBe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46281 4.4631 -7.5899 -5.88882 20.192 2.877)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iEtk0gA" cx="0" cy="0" r="1" gradientTransform="matrix(-.06733 -1.87567 .92118 -.03307 12.246 7.167)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iwwnh2c" cx="0" cy="0" r="1" gradientTransform="matrix(.86569 -1.98148 1.61605 .70604 20.73 8.9)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iH8UGhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.00036 1.24126 -1.09594 .88324 15.69 1.982)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iKEKRTu" cx="0" cy="0" r="1" gradientTransform="rotate(76.961 7.339 11.792)scale(.81006 1.33174)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="i3rYo9s" cx="0" cy="0" r="1" gradientTransform="matrix(.73103 .90416 -2.02591 1.63798 12.093 3.724)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i6ho0io" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91004 -1.07682 0 18.667 10.298)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iJbluXc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.678 .509)scale(.38069 .52412)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOGubYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91009 -1.07687 0 14.27 10.298)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4SZEBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00778 -.49723 .59768 -.00936 13.981 10.182)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="id16fLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6666 -3.56716 3.98507 -.7447 19.009 5.857)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iwoKyJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.97411 -7.12707 0 16.415 2.847)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iHwqNCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.22 2.373)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iXcSAKd" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.25 2.998)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><linearGradient id="iqiZzCe" x1="24.17" x2="25.356" y1="8.919" y2="8.919" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="iY5Vg3Z" x1="25.416" x2="25.416" y1="3.686" y2="11.453" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iLnBP2d" x1="25.965" x2="23.645" y1="14.784" y2="14.784" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iVmco5d" x1="23.764" x2="24.639" y1="14.463" y2="14.642" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="iZam77d" x1="9.395" x2="8.969" y1="28.041" y2="28.041" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iN8V0WS" x1="16.48" x2="16.48" y1="29.842" y2="23.408" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iWYdasD" x1="11.687" x2="11.042" y1="10.93" y2="10.93" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="i9NoRTb" x1="22.368" x2="21.543" y1="9.549" y2="12.105" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iDcRqyc" x1="20.538" x2="12.843" y1="11.042" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iAamgwe" x1="11.034" x2="13.364" y1="13.758" y2="13.454" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iPr5JGb" x1="11.573" x2="14.497" y1="10.38" y2="5.186" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iSfxPGc" x1="15.6" x2="16.546" y1="11.706" y2="11.706" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iDh1VBc" x1="17.417" x2="16.383" y1="12.031" y2="12.016" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="i2xZkNb" x1="16.667" x2="16.667" y1="12.779" y2="12.201" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iu75edc" x1="16.598" x2="16.598" y1="12.821" y2="12.652" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="iHmaQVD" x1="15.426" x2="15.864" y1="14.406" y2="13.713" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iumaQfj" x1="19.45" x2="19.134" y1="10.016" y2="10.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQL6u0z" x1="15.019" x2="14.703" y1="10.016" y2="10.21" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTYveNc" x1="18.25" x2="16.969" y1="3.936" y2="-.439" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient><filter id="irYYwKc" width="5.32" height="9.565" x="13.806" y="9.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".2"/></filter><filter id="ivToN0b" width=".65" height="8.268" x="24.591" y="3.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".125"/></filter><filter id="i504tPe" width="8.964" height="6.734" x="11.998" y="23.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".075"/></filter><filter id="idUGEQL" width="3.564" height="3.364" x="10.005" y="8.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1593"/></filter><filter id="i7giRAd" width="3.005" height="3.005" x="10.185" y="9.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".25"/></filter><filter id="iW8nrOb" width="3.614" height="3.614" x="19.591" y="8.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1593"/></filter><filter id="ienZBFc" width="3.005" height="3.005" x="19.77" y="9.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".25"/></filter><filter id="ieGSCWu" width="10.453" height="12.37" x="11.274" y="4.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1593"/></filter><filter id="iuREcCF" width="12.698" height="8.605" x="10.122" y="1.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1593"/></filter><filter id="ieLFkCw" width="3.273" height="4.202" x="14.594" y="9.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".375"/></filter><filter id="im05ZDd" width="2.391" height="3.202" x="15.276" y="9.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".125"/></filter><filter id="iK8jkcb" width="3" height="1.884" x="17.662" y="6.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.258824 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1593"/></filter><filter id="i3bPZPb" width="3.001" height="1.884" x="12.475" y="6.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.258824 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1593"/></filter><filter id="i7jKHpc" width=".791" height=".7" x="17.928" y="9.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".05"/></filter><filter id="iZOdeNd" width=".894" height=".917" x="18.775" y="9.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".1"/></filter><filter id="iBtgNOb" width=".99" height="1.044" x="14.299" y="9.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".1"/></filter><filter id="iMkyRod" width=".918" height=".708" x="13.538" y="9.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".05"/></filter><filter id="iZN7TIe" width="2.564" height="1.134" x="17.794" y="7.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".125"/></filter><filter id="iCbTApe" width="2.642" height="1.192" x="12.535" y="7.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1593" stdDeviation=".125"/></filter><filter id="iAerJfe" width="12.135" height="2.935" x="10.406" y="3.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1593"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-student-medium-light" /></template>
<style>
.a-e0cj8zq {
  stop-color: var(--svg-color--ba7e80, #BA7E80);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bjxhdkbfc {
  stop-color: var(--svg-color--a46f5d, #A46F5D);
  stop-opacity: 0;
}

.bnco9qkiy {
  d: path("M23.5 18.072a.24.24 0 0 0-.058-.29c-1.856-1.603-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.015 7.013-4.614");
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.c7bfsab8q {
  d: path("M24.423 3.582H8.453c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.cg6jk9bgb {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.099 13.428c.396.206.869.325 1.372.325a2.96 2.96 0 0 0 1.373-.325a.204.204 0 0 1 .243.04a.19.19 0 0 1 .02.242m-3.008-.282l2.967.254m-2.967-.254a.204.204 0 0 0-.244.041a.19.19 0 0 0-.02.242m.264-.283l-.223.254m3.232.028l-.042-.028m.042.028l-.042-.028m.042.028c-.346.525-.95.875-1.637.875s-1.29-.35-1.636-.875m3.231-.028a1.91 1.91 0 0 1-1.595.853c-.67 0-1.257-.341-1.595-.853m-.041.028v.001l.041-.029m-.041.028l.041-.028");
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

.ddl9sxmqm {
  stop-color: var(--svg-color--1c1026, #1C1026);
  stop-opacity: 0;
}

.dfrzfnapl {
  d: path("M10.406 5.106L11.5 3.232l9.845-.109l1.196 1.974c-4.664 1.609-10.045.744-12.135.01");
}

.djg41y0cy {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.06 9.208c-.658 0-1.214.453-1.365 1.066a.276.276 0 0 0 .27.344h2.248a.23.23 0 0 0 .228-.274a1.41 1.41 0 0 0-1.381-1.136");
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dn_8aox9x {
  stop-color: var(--svg-color--bd8a7b, #BD8A7B);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.eahtdcbss {
  d: path("M18.602 9.672c.064.085-.07.19-.222.304s-.265.193-.329.108s.008-.247.16-.361s.327-.137.391-.051");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ed1yx_btv {
  cx: 11.687px;
  cy: 10.649px;
  r: 1.003px;
}

.eia3v2wie {
  d: path("M15.09 10.274c0-.29-.237-.484-.3-.542l-.291.28l.179.364z");
}

.etclelb-u {
  stop-color: var(--svg-color--a76b71, #A76B71);
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f-7tomxwv {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m21.327 4.122l.432.215c.757.376 1.19 1.236 1.027 2.15l-.594 3.063c-.053.316-.263.53-.577.537h-.018s.054-.913.108-1.45c.044-.437-.032-.57-.432-.968c-.216-.215-.379-.537-.379-.86v-.86c0-.268-.216-.483-.432-.537c-.649-.161-2-.43-3.945-.43c-1.946 0-3.297.269-3.946.43a.524.524 0 0 0-.432.537v.86c0 .323-.108.645-.379.86l-.162.161c-.216.161-.324.484-.324.753c.054.59.108 1.45.108 1.45l-.05-.001a.64.64 0 0 1-.599-.536l-.594-3.063c-.108-.86.324-1.72 1.08-2.096l.433-.215c.27-.161.54-.376.81-.591l.974-1.021c.594-.538 1.459-.699 2.216-.323c.54.162 1.135.162 1.675 0c.81-.268 1.73-.053 2.378.538l.811.806c.216.269.487.43.81.591");
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f5z4hbbta {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.916 3.686v7.767");
}

.f8avqachq {
  stop-color: var(--svg-color--a57050, #A57050);
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

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g33qegbha {
  cx: 13.997px;
  cy: 9.865px;
  rx: 0.392px;
  ry: 0.198px;
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.g9pdkgm1k {
  d: path("M19.47 10.262a.85.85 0 0 0-.234-.466l-.261.287l.118.23z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.ho8ocib6i {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m16.086 10.362l-.535 1.712a.543.543 0 0 0 .524.705h.792a.545.545 0 0 0 .525-.705l-.536-1.712c-.114-.38-.65-.38-.77 0");
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.hz94g6b_c {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.485 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.ioc_rfocq {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m16.194 10.526l-.827 1.713c-.102.352.144.704.492.704h.743c.348 0 .594-.357.492-.704l-.502-1.713c-.108-.38-.285-.38-.398 0");
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j4en6db6n {
  d: path("M16.485 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.j61mf2btk {
  stop-color: var(--svg-color--9b7287, #9B7287);
}

.j6jlvoyxn {
  d: path("M24.413 11.621a.837.837 0 1 0 .8 0z");
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k-u3pqb_i {
  stop-color: var(--svg-color--a57050, #A57050);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k1nrq-b0r {
  d: path("M9.25 29.972V18.186a10.97 10.97 0 0 0-3.765 8.286v3.5z");
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.ltzewobth {
  d: path("m11.333 10.032l.049.002s-.054-.86-.108-1.451c0-.27.108-.592.324-.753l.162-.161c.27-.215.379-.537.379-.86v-.86c0-.268.162-.483.432-.537c.649-.161 2-.43 3.946-.43c1.945 0 3.297.269 3.945.43c.216.054.433.269.433.537v.86c0 .323.162.645.378.86c.506.354.474.55.432.967a46 46 0 0 0-.108 1.451h.018l-.267 3.989c-.162 1.783-1.564 3.026-3.235 3.026h-3.235c-1.725 0-3.073-1.243-3.235-3.026z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcieo-bmu {
  d: path("M23.71 29.972V18.186a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.mncnzu0gf {
  d: path("M12.148 23.749c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.mx6r32s2r {
  stop-color: var(--svg-color--d19984, #D19984);
  stop-opacity: 0;
}

.ngokvxj-f {
  d: path("M16.134 23.749c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.nie6_abxt {
  d: path("m16.086 10.362l-.535 1.712a.543.543 0 0 0 .524.705h.792a.545.545 0 0 0 .525-.705l-.536-1.712c-.114-.38-.65-.38-.77 0");
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o28d1mb5b {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.186 18.842c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.586v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.586Z");
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.on6m7rb5p {
  stroke: var(--svg-color--8f633b, #8F633B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.885 8.285c.33-.291 1.05-.598 1.942-.456");
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p0uazivnq {
  d: path("M16.186 18.842c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.586v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.586");
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.q1bzoib_u {
  d: path("m21.327 4.122l.432.215c.757.376 1.19 1.236 1.027 2.15l-.594 3.063c-.053.316-.263.53-.577.537h-.018s.054-.913.108-1.45c.044-.437-.032-.57-.432-.968c-.216-.215-.379-.537-.379-.86v-.86c0-.268-.216-.483-.432-.537c-.649-.161-2-.43-3.945-.43c-1.946 0-3.297.269-3.946.43a.524.524 0 0 0-.432.537v.86c0 .323-.108.645-.379.86l-.162.161c-.216.161-.324.484-.324.753c.054.59.108 1.45.108 1.45l-.05-.001a.64.64 0 0 1-.599-.536l-.594-3.063c-.108-.86.324-1.72 1.08-2.096l.433-.215c.27-.161.54-.376.81-.591l.974-1.021c.594-.538 1.459-.699 2.216-.323c.54.162 1.135.162 1.675 0c.81-.268 1.73-.053 2.378.538l.811.806c.216.269.487.43.81.591");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r7-b7wb6k {
  cx: 13.997px;
  cy: 9.865px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.392px;
  ry: 0.198px;
}

.r72kq1vnm {
  cx: 21.273px;
  cy: 10.649px;
  r: 1.003px;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.rztl4kb9y {
  fill: var(--svg-color--8c5c2d, #8C5C2D);
  d: path("M20.22 7.908h-.002l-.002-.002l-.005-.004l-.012-.01a2 2 0 0 0-.156-.108a2.6 2.6 0 0 0-.423-.212a2.86 2.86 0 0 0-1.504-.16a.538.538 0 0 0 .168 1.063c.4-.063.722.01.941.097a1.5 1.5 0 0 1 .31.167a.538.538 0 0 0 .684-.83");
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.saw75ubnw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.602 9.672c.064.085-.07.19-.222.304s-.265.193-.329.108s.008-.247.16-.361s.327-.137.391-.051");
}

.sbmfu45lf {
  d: path("M14.269 9.481a.9.9 0 0 0-.867 1.137h1.737a1 1 0 0 0 .033-.238a.905.905 0 0 0-.904-.899");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sntswj96l {
  stroke: var(--svg-color--8f633b, #8F633B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.145 7.763c.433-.076 1.278-.054 1.863.4");
}

.srh6f0bdo {
  d: path("M25.213 11.645V2.782h-.8v8.863z");
}

.syayv9bph {
  stop-color: var(--svg-color--a76b71, #A76B71);
  stop-opacity: 0;
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t7pyqfr7j {
  cx: 21.273px;
  cy: 10.649px;
  r: 1.682px;
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u5-qxxbev {
  stop-color: var(--svg-color--a46f5d, #A46F5D);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
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

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v3dn5qbxz {
  d: path("m23.96 13.582l-.517 2.239a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7zls1bga {
  fill: var(--svg-color--000, #000);
  d: path("M18.154 10.38c0-.285.229-.514.515-.514a.513.513 0 0 1 .457.752h-.91a.47.47 0 0 1-.062-.237");
}

.vfhx5qbgf {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.877 9.208c.658 0 1.214.453 1.365 1.066a.276.276 0 0 1-.27.343h-2.247a.232.232 0 0 1-.23-.273a1.41 1.41 0 0 1 1.382-1.136");
}

.vhol5yblb {
  cx: 21.273px;
  cy: 10.649px;
  r: 1.003px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vpv96wbod {
  cx: 11.687px;
  cy: 10.649px;
  r: 1.682px;
}

.vqcq5_liq {
  d: path("M18.669 9.481a.9.9 0 0 1 .866 1.136h-1.737a.903.903 0 0 1 .87-1.136");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vywwzlbha {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m12.669 7.909l.002-.002l.001-.001l.005-.004l.012-.01l.036-.027q.045-.033.12-.08c.1-.064.243-.142.423-.213a2.86 2.86 0 0 1 1.504-.16a.538.538 0 0 1-.168 1.063a1.8 1.8 0 0 0-.94.097a1.5 1.5 0 0 0-.311.167a.538.538 0 0 1-.684-.83");
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
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

.ws5zlibzm {
  stop-color: var(--svg-color--a56d67, #A56D67);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.z734mzb2t {
  fill: var(--svg-color--000, #000);
  d: path("M14.783 10.38a.513.513 0 0 0-.515-.514a.513.513 0 0 0-.457.752h.911a.5.5 0 0 0 .061-.237");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zetzp0vmo {
  d: path("M20.12 23.749c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

</style>
