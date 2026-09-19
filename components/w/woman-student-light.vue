<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#icy0Hrb)"><path fill="url(#iZZArSs)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#iDIlBJd)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#iSwyb3d)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#iSlzVcc)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#ierhwvb)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#i8nY7Me)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#iFUYbrd)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#iH7oVBb)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#iKYLKFd)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#it7snLc)" clip-rule="evenodd" class="fazo79y1d"/><path fill="url(#ioiIHdb)" clip-rule="evenodd" class="fazo79y1d"/></g><path class="g__oa5l3d"/><path fill="url(#iSPdzGd)" class="l1b_ykqwm"/><path fill="url(#iMqaFxd)" class="l1b_ykqwm"/><path fill="url(#iOLQ0Ae)" class="lh1fp-bfl"/><path fill="url(#iAlUQ0d)" class="lh1fp-bfl"/><path fill="url(#iMWOxWd)" class="lh1fp-bfl"/><path fill="url(#iu0Uajb)" class="lh1fp-bfl"/><path fill="url(#ippXI7T)" class="lh1fp-bfl"/><path fill="url(#iPvGJPd)" class="lh1fp-bfl"/><g filter="url(#iunidTj)"><path class="y0fyr11lr"/></g><path fill="url(#iSnaX5d)" class="oqcyx-pxj"/><path fill="url(#iN86MTb)" class="oqcyx-pxj"/><path fill="url(#ix7U9VE)" class="oqcyx-pxj"/><path fill="url(#ikWuuse)" class="gpc4yrb7i"/><path fill="url(#iocagAM)" class="gpc4yrb7i"/><path fill="url(#i9dwJbe)" class="gxwpur07r"/><path fill="url(#imXPORd)" class="gxwpur07r"/><g filter="url(#iLGabYd)"><path stroke="url(#iQpIg5d)" class="fnn_de3je"/></g><path fill="url(#iSKr12j)" class="s53oupr5r"/><path fill="url(#iumF7fe)" class="s53oupr5r"/><path fill="url(#ibt3KXw)" class="s53oupr5r"/><path fill="url(#i6uk8Cb)" class="s53oupr5r"/><path fill="url(#ipEXO5j)" class="s53oupr5r"/><path fill="url(#iirDFZc)" class="adkfdz3se"/><path fill="url(#igkTTDe)" class="adkfdz3se"/><path fill="url(#iJX92de)" class="adkfdz3se"/><path fill="url(#iFKYQxb)" class="fkztt5_bm"/><path fill="url(#iQOksyC)" class="fkztt5_bm"/><g filter="url(#ipMOfeb)"><path fill="url(#i9QAGrc)" class="i4iijtb6t"/><path fill="url(#i9QAGrc)" class="ubca08giz"/><path fill="url(#i9QAGrc)" class="w1el8fpbw"/></g><g filter="url(#iXiNpdd)"><path stroke="url(#is5EBGe)" class="okjx4cc9g"/></g><g filter="url(#ix22T9d)"><path stroke="url(#iTMlndc)" class="i6f0s4anz"/></g><g filter="url(#ikaMQib)"><path fill="url(#iYJAFDc)" class="kq2_9z4sy"/></g><g filter="url(#iAVg6Vd)"><path fill="url(#iB0dhFc)" class="fctbxdbkp"/><path fill="url(#iLwqB0c)" class="fctbxdbkp"/></g><g filter="url(#is3hJpe)"><path class="tcqmupono"/><path fill="url(#i3eitld)" class="dd623lbkq"/></g><g filter="url(#iozqAqe)"><path class="oyxuzsbfw"/><path fill="url(#i5ftyrc)" class="ib_bw2b6s"/></g><g filter="url(#i7ssokf)"><path fill="url(#iXvyqpd)" class="kjz2e8cdo"/><path fill="url(#iWzQzgd)" class="kjz2e8cdo"/><path fill="url(#iZTAAuc)" class="kjz2e8cdo"/><path fill="url(#ipld4ac)" class="kjz2e8cdo"/><path fill="url(#iKWMgAd)" class="kjz2e8cdo"/><path fill="url(#ioY73Ud)" class="kjz2e8cdo"/><path fill="url(#iTNCFJe)" class="kjz2e8cdo"/></g><path fill="url(#ioKIhJd)" class="kjz2e8cdo"/><g filter="url(#iCOgxgb)"><path class="tpa_7gc4o"/></g><g filter="url(#iVTpDpb)"><path class="bgw3tsh9h"/><path fill="url(#iHDpc9d)" class="q4orv5bgf"/><path fill="url(#iUcWsqw)" class="q4orv5bgf"/><path fill="url(#iHH1ZGc)" class="q4orv5bgf"/><path fill="url(#iHf565c)" class="q4orv5bgf"/></g><path fill="url(#i5E3oLe)" class="q4orv5bgf"/><path fill="url(#icxxQYd)" class="q4orv5bgf"/><path stroke="url(#ikqlxbd)" class="fvih82-2q"/><g filter="url(#iDSzKBe)"><path class="d62ldbbdo"/></g><g filter="url(#i7SgN2d)"><path class="jzpt3-b4e"/></g><g filter="url(#imhVNzc)"><path class="ex3tzjleh"/></g><g filter="url(#i6GlBJe)"><path clip-rule="evenodd" class="oa3p9obmm"/></g><path class="pexi-5b4t"/><path fill="url(#iZHm3fe)" class="jkr4gtbta"/><path class="ui-1n3w8x"/><g filter="url(#irYDFxc)"><path class="w7bbnubeb"/><path fill="url(#i3tZlpb)" class="z4fw54bck"/></g><g filter="url(#iIsGWEe)"><path fill="url(#iyz3A3b)" class="u70nn1c0c"/></g><path class="qcw327btg"/><path fill="url(#iy6UnOd)" class="yhjwj0bei"/><path class="t4q2azbyh"/><g filter="url(#iwfaKEb)"><path fill="url(#i1s8aIb)" class="ojn14kl9l"/></g><g filter="url(#iokwOtb)"><ellipse transform="rotate(-27.914 13.849 10.221)" class="bfe-uebjo"/><ellipse fill="url(#iI5Yuud)" transform="rotate(-27.914 13.849 10.221)" class="r8-kyzbyh"/></g><g filter="url(#itUhO0b)"><path class="m0qu293vc"/></g><g filter="url(#iJJkDQb)"><path class="egl2wq3mb"/></g><g filter="url(#iIGdnJe)"><path class="fwcim9btg"/><path fill="url(#if4DX7b)" class="dk3ll9h8e"/></g><g filter="url(#i8W5Rcd)"><path class="h8fxrlbnc"/><path fill="url(#iUQ0mub)" class="htk4pdbvh"/><path fill="url(#ilyPXDc)" class="htk4pdbvh"/></g><g filter="url(#ix22T9d)"><path stroke="url(#iXeTbdc)" class="i6f0s4anz"/></g><g filter="url(#iem8HEd)"><path class="rraukbbto"/></g><g filter="url(#iSR7ZPU)"><path fill="url(#i18iKEL)" class="tgltk6byz"/><path fill="url(#iu6zoec)" class="tgltk6byz"/></g><path fill="url(#iJVoxlb)" class="awf64etot"/><path fill="url(#iMx7uHd)" class="awf64etot"/><path fill="url(#iBTSjDT)" class="awf64etot"/><defs><radialGradient id="iDIlBJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6327 4.78072 -5.97209 -.79038 16.105 13.57)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iSwyb3d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02318 2.03885 -2.67889 -3.97221 13.152 13.851)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iSlzVcc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.909 8.392)scale(2.25688 1.73297)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ierhwvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35338 2.21459 -1.55998 -.95334 11.816 9.053)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i8nY7Me" cx="0" cy="0" r="1" gradientTransform="matrix(1.44125 2.74188 -3.80615 2.00067 12.73 2.497)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iFUYbrd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51145 1.51156 -2.11238 -2.11223 22.538 4.676)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iH7oVBb" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.431 6.759)scale(2.01344 4.19888)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iKYLKFd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.992 8.277)scale(3.04359 3.87708)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="it7snLc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.375 -3.897)scale(2.93648 2.32259)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ioiIHdb" cx="0" cy="0" r="1" gradientTransform="matrix(1.57703 .16542 -.26803 2.55525 9.98 10.017)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iSPdzGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.737 23.114)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iMqaFxd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.143 21.458)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iOLQ0Ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.443 21.349)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iAlUQ0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.435 16.896)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iMWOxWd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.018 15.552)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iu0Uajb" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.768 15.317)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="ippXI7T" cx="0" cy="0" r="1" gradientTransform="rotate(-80.136 21.1 2.745)scale(9.65407 14.837)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iPvGJPd" cx="0" cy="0" r="1" gradientTransform="rotate(91.544 .347 14.336)scale(4.63875 7.3062)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="q8_1e9bvu"/><stop offset="1" class="bh-nd0_an"/></radialGradient><radialGradient id="iSnaX5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.739 18.22)" gradientUnits="userSpaceOnUse"><stop class="maef1bbsj"/><stop offset="1" class="ws5zlibzm"/><stop offset="1" class="rchayobux"/></radialGradient><radialGradient id="iN86MTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.421 16.985)" gradientUnits="userSpaceOnUse"><stop class="dr7jm_b-p"/><stop offset="1" class="eths-3bvt"/></radialGradient><radialGradient id="ix7U9VE" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.421 14.544)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="im04-mb9w"/><stop offset="1" class="wg5q2jt7g"/></radialGradient><radialGradient id="iocagAM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.01 11.668)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="i9dwJbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.268 12.04)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="imXPORd" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.93 12.43)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iumF7fe" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.33 8.558)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ibt3KXw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.768 13.107)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="ipEXO5j" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.768 16.896)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iirDFZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.44 29.995)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="igkTTDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.206 29.995)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iFKYQxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.547 29.995)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iQOksyC" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.497 23.157)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iB0dhFc" cx="0" cy="0" r="1" gradientTransform="matrix(1.9158 -2.1355 2.60735 2.3391 21.15 11.97)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iLwqB0c" cx="0" cy="0" r="1" gradientTransform="matrix(1.37972 .77335 -.21864 .39007 21.738 9.185)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i3eitld" cx="0" cy="0" r="1" gradientTransform="matrix(1.5833 -.11777 .09207 1.2377 21.026 11.066)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="i5ftyrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26548 0 0 -.99831 11.597 10.948)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iXvyqpd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.81975 3.14482 -4.20928 -9.12812 19.42 10.384)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iWzQzgd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62943 .47306 -.52217 -4.00624 19.831 11.812)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iZTAAuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.37093 -3.97222 5.04 1.73945 13.926 18.07)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="ipld4ac" cx="0" cy="0" r="1" gradientTransform="rotate(97.761 3.89 12.689)scale(7.05834 8.17029)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="pvarcdbuv"/><stop offset="1" class="nc5tcfbln"/></radialGradient><radialGradient id="iKWMgAd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.567 6.99)scale(7.37951 12.7052)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="ioY73Ud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20672 1.48097 0 18.835 9.945)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iTNCFJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37632 1.57736 0 14.244 9.706)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ioKIhJd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34777 0 0 -6.75892 21.765 11.505)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iHDpc9d" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 13.54 -.778)scale(2.19597 .67678)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iHf565c" cx="0" cy="0" r="1" gradientTransform="matrix(-.8173 0 0 -.22849 16.993 12.49)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="icxxQYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43787 .98715 -1.1864 -1.7281 16.817 11.865)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="iZHm3fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85076 -1.35323 0 18.71 10.322)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i3tZlpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.2432 -.31339 .43145 -.33481 18.47 10.41)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iy6UnOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85076 -1.35323 0 14.133 10.322)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iI5Yuud" cx="0" cy="0" r="1" gradientTransform="matrix(-.00811 -.51808 .62275 -.00975 13.833 10.551)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="if4DX7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.32338 -2.88938 1.47814 .677 10.488 8.098)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iUQ0mub" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21463 4.60494 -7.5288 -3.62078 18.425 2.638)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ilyPXDc" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 7.023 8.651)scale(1.45053 3.12074)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="i18iKEL" cx="0" cy="0" r="1" gradientTransform="matrix(-.6722 -3.65216 4.02251 -.74037 18.968 5.944)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iu6zoec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02116 -7.18676 0 16.352 2.862)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iMx7uHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.174 2.396)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iBTSjDT" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.205 3.02)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="icy0Hrb" width="15.998" height="16.498" x="8.547" y="1.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><filter id="iunidTj" width="5.32" height="9.564" x="13.761" y="9.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".2"/></filter><filter id="iLGabYd" width=".65" height="8.268" x="24.546" y="3.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".125"/></filter><filter id="ipMOfeb" width="8.964" height="6.734" x="11.953" y="23.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".075"/></filter><filter id="iXiNpdd" width="1.172" height="2.394" x="13.087" y="3.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".125"/></filter><filter id="ix22T9d" width="1.171" height="2.393" x="13.089" y="3.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".1"/></filter><filter id="ikaMQib" width="3.525" height="3.375" x="9.821" y="9.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><filter id="iAVg6Vd" width="3.375" height="3.625" x="19.796" y="9.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><filter id="is3hJpe" width="3.253" height="3.253" x="19.857" y="9.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".25"/></filter><filter id="iozqAqe" width="3.053" height="3.053" x="10.002" y="9.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".2"/></filter><filter id="i7ssokf" width="10.686" height="11.505" x="11.078" y="5.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><filter id="iCOgxgb" width="2.969" height="3.812" x="14.767" y="9.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".25"/></filter><filter id="iVTpDpb" width="2.469" height="3.312" x="15.187" y="10.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".125"/></filter><filter id="iDSzKBe" width="3.138" height="1.348" x="17.419" y="9.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><filter id="i7SgN2d" width="3.138" height="1.348" x="12.286" y="9.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><filter id="imhVNzc" width="2.562" height="1.134" x="12.428" y="7.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><filter id="i6GlBJe" width="2.562" height="1.134" x="18.109" y="7.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><filter id="irYDFxc" width=".815" height=".721" x="17.945" y="9.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".05"/></filter><filter id="iIsGWEe" width=".915" height=".938" x="18.83" y="9.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".1"/></filter><filter id="iwfaKEb" width="1.015" height="1.071" x="14.171" y="9.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".1"/></filter><filter id="iokwOtb" width=".948" height=".729" x="13.375" y="9.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".05"/></filter><filter id="itUhO0b" width="2.342" height=".996" x="18.155" y="8.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".1"/></filter><filter id="iJJkDQb" width="2.342" height=".996" x="12.438" y="8.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".1"/></filter><filter id="iIGdnJe" width="4.378" height="4.694" x="9.877" y="3.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/><feGaussianBlur result="effect2_foregroundBlur_4002_1595" stdDeviation=".15"/></filter><filter id="i8W5Rcd" width="9.167" height="6.039" x="13.111" y="2.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/><feGaussianBlur result="effect2_foregroundBlur_4002_1595" stdDeviation=".125"/></filter><filter id="iem8HEd" width="7.167" height="3.963" x="15.598" y="4.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1595" stdDeviation=".5"/></filter><filter id="iSR7ZPU" width="12.363" height="3.035" x="10.201" y="3.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1595"/></filter><linearGradient id="iZZArSs" x1="21.343" x2="14.207" y1="3.657" y2="16.874" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ikWuuse" x1="24.125" x2="25.311" y1="8.942" y2="8.942" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="iQpIg5d" x1="25.371" x2="25.371" y1="3.708" y2="11.476" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iSKr12j" x1="25.919" x2="23.6" y1="14.806" y2="14.806" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="i6uk8Cb" x1="23.719" x2="24.594" y1="14.485" y2="14.665" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="iJX92de" x1="9.35" x2="8.924" y1="28.064" y2="28.064" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="i9QAGrc" x1="16.435" x2="16.435" y1="29.864" y2="23.431" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="is5EBGe" x1="13.387" x2="13.959" y1="4.446" y2="5.783" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iTMlndc" x1="13.389" x2="13.961" y1="4.448" y2="5.784" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iYJAFDc" x1="9.821" x2="12.924" y1="11.039" y2="11.039" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iUcWsqw" x1="15.437" x2="16.421" y1="12.344" y2="12.344" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iHH1ZGc" x1="16.421" x2="16.421" y1="13.182" y2="12.542" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="i5E3oLe" x1="16.503" x2="16.503" y1="13.154" y2="13.008" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="ikqlxbd" x1="15.305" x2="15.789" y1="14.66" y2="13.913" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iyz3A3b" x1="19.525" x2="19.196" y1="10.378" y2="10.581" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1s8aIb" x1="14.913" x2="14.584" y1="10.378" y2="10.581" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXeTbdc" x1="13.389" x2="13.961" y1="4.448" y2="5.784" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iJVoxlb" x1="18.205" x2="16.924" y1="3.958" y2="-.417" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-student-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.adkfdz3se {
  d: path("M9.206 29.995V18.209a10.97 10.97 0 0 0-3.766 8.286v3.5z");
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.awf64etot {
  d: path("M24.378 3.605H8.408c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bfe-uebjo {
  cx: 13.849px;
  cy: 10.221px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
}

.bgw3tsh9h {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m16.02 10.57l-.557 1.782a.565.565 0 0 0 .546.733h.825c.386 0 .66-.372.546-.733l-.558-1.783c-.12-.395-.676-.395-.802 0");
}

.bh-nd0_an {
  stop-color: var(--svg-color--1c0e20, #1C0E20);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
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

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d62ldbbdo {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.619 10.351c.278-.49.701-.876 1.612-.876c.399 0 .783.11 1.125.386c.282.228.244.52.026.629l-.583.333c-.684-.221-1.44-.251-2.18-.472");
}

.dd623lbkq {
  d: path("M21.483 12.074a1.126 1.126 0 1 0 0-2.252a1.126 1.126 0 0 0 0 2.252");
}

.dk3ll9h8e {
  d: path("M11.106 4.668c.593-.628 1.716-.63 2.234-.535l.415 1.353c-.265-.041-.501.053-.7.246c-.47 1.322-2.086 2.05-2.835 2.25c-.156-1.564.114-2.496.886-3.314");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dr7jm_b-p {
  stop-color: var(--svg-color--b0797e, #B0797E);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
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

.egl2wq3mb {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.48 8.46c-.338-.082-1.18-.041-1.742.36");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.eths-3bvt {
  stop-color: var(--svg-color--b0797e, #B0797E);
  stop-opacity: 0;
}

.ex3tzjleh {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.859 9.084l-.005.002a.281.281 0 0 1-.29-.482h.001l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .155-.08c.103-.05.25-.113.43-.17a2.94 2.94 0 0 1 1.393-.114a.281.281 0 0 1-.098.553a2.4 2.4 0 0 0-1.124.097a3 3 0 0 0-.477.203");
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fazo79y1d {
  fill-rule: evenodd;
  d: path("M23.956 12.426a3.4 3.4 0 0 0 .34-1.496c0-.49-.101-.95-.282-1.37h.006a3.4 3.4 0 0 0-.295-.537l-.003-.004a3.4 3.4 0 0 1-.551-1.857v-.01a3.46 3.46 0 0 0-3.46-3.46a.57.57 0 0 1-.477-.244a3.47 3.47 0 0 0-2.813-1.443a3.47 3.47 0 0 0-2.812 1.443a.6.6 0 0 1-.477.244l-.09.001a3.46 3.46 0 0 0-3.37 3.459v.01c0 .658-.191 1.306-.552 1.857l-.002.004a3.46 3.46 0 0 0-.231 3.403a.54.54 0 0 1 0 .477a3.4 3.4 0 0 0-.34 1.476a3.37 3.37 0 0 0 3.375 3.374h8.999a3.37 3.37 0 0 0 3.375-3.374a3.4 3.4 0 0 0-.34-1.476a.54.54 0 0 1 0-.477M11.1 9.624h-.013l1.257 2.47c.13 2.938 1.276 0 4.077 0s4.023 3.27 4.152.332l1.192-3.353c-.057-1.305-1.003-1.397-1.192-1.397h-3.376a4.05 4.05 0 0 1-3.344-1.754a.277.277 0 0 0-.484.053l-.086.203a2.42 2.42 0 0 1-1.248 1.295q-.025.008-.053.021l-.054.022c-.248.128-.828.513-.85 1.508l.011.321z");
}

.fctbxdbkp {
  d: path("M21.483 12.635a1.687 1.687 0 1 0 0-3.374a1.687 1.687 0 0 0 0 3.374");
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fkztt5_bm {
  d: path("M23.665 29.995V18.209a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.fnn_de3je {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.871 3.709v7.767");
}

.ft5dv1b6b {
  fill: none;
}

.fvih82-2q {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.954 13.595c.424.226.93.356 1.467.356a3.1 3.1 0 0 0 1.468-.356a.21.21 0 0 1 .256.043c.06.064.082.166.022.259m-3.213-.302l3.171.274m-3.17-.274h-.001a.21.21 0 0 0-.257.045a.2.2 0 0 0-.021.257m.278-.302l-.236.274m3.449.028l-.042-.028m.042.028l-.042-.028m.042.028a2.076 2.076 0 0 1-3.491 0m3.449-.028a2.026 2.026 0 0 1-3.407 0m-.042.028l.042-.028m-.042.028l.042-.028");
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fwcim9btg {
  fill: var(--svg-color--232121, #232121);
  d: path("M11.106 4.668c.593-.628 1.716-.63 2.234-.535l.415 1.353c-.265-.041-.501.053-.7.246c-.47 1.322-2.086 2.05-2.835 2.25c-.156-1.564.114-2.496.886-3.314");
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g__oa5l3d {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.44 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gpc4yrb7i {
  d: path("M25.168 11.668V2.805h-.8v8.863z");
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gxwpur07r {
  d: path("M24.368 11.644a.838.838 0 1 0 .8 0z");
}

.h8fxrlbnc {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.789 2.778c-1.188-.262-2.254.923-2.377 1.362c1.102 3.718 3.893 3.514 6.648 3.208c1.649-.183 1.828.568 1.968.932c0-4.124-3.506-4.899-6.21-5.495z");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.htk4pdbvh {
  d: path("M15.789 2.778c-1.188-.262-2.254.923-2.377 1.362c1.102 3.718 3.893 3.514 6.648 3.208c1.649-.183 1.828.568 1.968.932c0-4.124-3.506-4.899-6.21-5.495z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i4iijtb6t {
  d: path("M12.103 23.771c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.i6f0s4anz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.39 4.088c.024.255.246 1.213.57 1.793");
}

.ib_bw2b6s {
  d: path("M11.528 12.074a1.126 1.126 0 1 0 0-2.252a1.126 1.126 0 0 0 0 2.252");
}

.im04-mb9w {
  stop-color: var(--svg-color--b5836a, #B5836A);
  stop-opacity: 0;
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jkr4gtbta {
  d: path("M18.712 9.822a.936.936 0 0 1 .901 1.182h-1.808a.94.94 0 0 1 .906-1.183");
}

.jzpt3-b4e {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.224 10.351c-.278-.49-.701-.876-1.612-.876c-.399 0-.783.11-1.125.386c-.282.228-.244.52-.026.629l.583.333c.684-.221 1.44-.251 2.18-.472");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kjz2e8cdo {
  d: path("M11.087 9.624h.013l-.011-.279l-.01-.32c.02-.996.601-1.38.849-1.51q.025-.008.053-.02l.054-.022a2.42 2.42 0 0 0 1.248-1.295l.086-.203a.277.277 0 0 1 .484-.053a4.05 4.05 0 0 0 3.344 1.754h3.377c.188 0 1.134.092 1.19 1.397l-.124 3.223c-.13 2.939-2.424 4.912-5.225 4.912c-2.802 0-5.097-1.973-5.226-4.912z");
}

.kq2_9z4sy {
  d: path("M11.508 12.635a1.687 1.687 0 1 0 0-3.375a1.687 1.687 0 0 0 0 3.375");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l1b_ykqwm {
  d: path("M16.44 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lh1fp-bfl {
  d: path("M23.456 18.094a.24.24 0 0 0-.059-.29c-1.856-1.602-4.346-2.486-6.954-2.486s-5.113.893-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.613 7.03 4.613s5.73-2.014 7.013-4.614");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.m0qu293vc {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.455 8.46c.338-.082 1.18-.041 1.742.36");
}

.maef1bbsj {
  stop-color: var(--svg-color--cd9e8e, #CD9E8E);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.nc5tcfbln {
  stop-color: var(--svg-color--b47896, #B47896);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.oa3p9obmm {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m20.334 8.604l-.144.241za.281.281 0 0 1-.288.482l-.006-.002a1 1 0 0 0-.118-.062a3 3 0 0 0-.36-.141a2.4 2.4 0 0 0-1.123-.097a.281.281 0 1 1-.098-.553c.538-.095 1.037 0 1.393.114a3.4 3.4 0 0 1 .586.25l.01.006z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojn14kl9l {
  d: path("M14.986 10.647c0-.302-.246-.504-.312-.565l-.303.293l.186.379z");
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.okjx4cc9g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.387 4.086c.024.255.246 1.213.572 1.794");
}

.oqcyx-pxj {
  d: path("M16.141 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oyxuzsbfw {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.528 12.074a1.126 1.126 0 1 0 0-2.252a1.126 1.126 0 0 0 0 2.252");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pexi-5b4t {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.929 9.536c.684 0 1.263.473 1.42 1.11a.287.287 0 0 1-.28.358h-2.34a.24.24 0 0 1-.238-.285a1.466 1.466 0 0 1 1.438-1.183");
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

.pvarcdbuv {
  stop-color: var(--svg-color--b47896, #B47896);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q4orv5bgf {
  d: path("m16.02 10.57l-.557 1.782a.565.565 0 0 0 .546.733h.825c.386 0 .66-.372.546-.733l-.558-1.783c-.12-.395-.676-.395-.802 0");
}

.q8_1e9bvu {
  stop-color: var(--svg-color--1c0e20, #1C0E20);
}

.qcw327btg {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.914 9.536c-.685 0-1.263.473-1.42 1.11a.287.287 0 0 0 .28.358h2.34a.24.24 0 0 0 .238-.285a1.47 1.47 0 0 0-1.438-1.183");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r8-kyzbyh {
  cx: 13.849px;
  cy: 10.221px;
  rx: 0.409px;
  ry: 0.207px;
}

.rchayobux {
  stop-color: var(--svg-color--b78273, #B78273);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rraukbbto {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.945 6.564l-1.495.275a.722.722 0 1 1-.131-1.432h2.454c1.452 0 1.933 1.463 1.992 1.963a3.3 3.3 0 0 0-2.82-.806");
}

.s53oupr5r {
  d: path("m23.914 13.605l-.516 2.239a.45.45 0 0 0 .445.55h1.863a.45.45 0 0 0 .43-.556l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t4q2azbyh {
  fill: var(--svg-color--000, #000);
  d: path("M14.667 10.757a.534.534 0 0 0-.536-.536a.534.534 0 0 0-.476.783h.948a.5.5 0 0 0 .064-.247");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tcqmupono {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M21.483 12.074a1.126 1.126 0 1 0 0-2.252a1.126 1.126 0 0 0 0 2.252");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tgltk6byz {
  d: path("m10.202 5.247l1.253-1.992l9.75-.11l1.36 2.063c-4.664 1.61-10.274.773-12.364.04");
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tpa_7gc4o {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m16.01 10.714l-.717 1.783a.565.565 0 0 0 .546.733h.824c.387 0 .66-.372.546-.733l-.557-1.783c-.12-.395-.517-.395-.642 0");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u70nn1c0c {
  d: path("M19.545 10.634a.9.9 0 0 0-.243-.485l-.272.299l.123.24z");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ubca08giz {
  d: path("M16.09 23.771c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.692z");
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.ui-1n3w8x {
  fill: var(--svg-color--000, #000);
  d: path("M18.176 10.757c0-.298.238-.536.536-.536a.534.534 0 0 1 .476.783h-.948a.5.5 0 0 1-.064-.247");
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w1el8fpbw {
  d: path("M20.076 23.771c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.691z");
}

.w7bbnubeb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.643 10.02c.066.088-.073.197-.231.316c-.159.118-.276.201-.343.112s.008-.257.166-.376c.159-.118.341-.142.408-.053");
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wg5q2jt7g {
  stop-color: var(--svg-color--b5836a, #B5836A);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.ws5zlibzm {
  stop-color: var(--svg-color--a56d67, #A56D67);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y0fyr11lr {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.141 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587Z");
}

.yhjwj0bei {
  d: path("M14.131 9.822a.936.936 0 0 0-.902 1.182h1.808a1 1 0 0 0 .034-.247a.94.94 0 0 0-.94-.935");
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

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z4fw54bck {
  d: path("M18.643 10.02c.066.088-.073.197-.231.316c-.159.118-.276.201-.343.112s.008-.257.166-.376c.159-.118.341-.142.408-.053");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

</style>
