<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i5fTJje)" class="ne66_lm1q"/><g clip-rule="evenodd" filter="url(#iSpSJDe)" class="d2kvgvbvc"><path fill="url(#iaEYyPe)" class="ncyg9ebdc"/><path fill="url(#iuPiZod)" class="ncyg9ebdc"/><path fill="url(#iaITejh)" class="ncyg9ebdc"/><path fill="url(#isXS1xd)" class="ncyg9ebdc"/><path fill="url(#i1ddgkd)" class="ncyg9ebdc"/><path fill="url(#ip2dCMe)" class="ncyg9ebdc"/><path fill="url(#isqhalb)" class="ncyg9ebdc"/><path fill="url(#ieqmtIe)" class="ncyg9ebdc"/><path fill="url(#iRPBQmu)" class="ncyg9ebdc"/><path fill="url(#icNClhb)" class="ncyg9ebdc"/><path fill="url(#i5jhrHd)" class="ncyg9ebdc"/><path fill="url(#iiI7UPb)" class="ncyg9ebdc"/></g><path fill="url(#iWyEhDb)" class="ul7b3bcbn"/><path fill="url(#iiFEcXb)" clip-rule="evenodd" class="tv41nebaf"/><path fill="url(#iALeSad)" clip-rule="evenodd" class="t2uxtx_ya"/><g filter="url(#icHdYSb)"><path fill="url(#i6ucWWc)" class="ufs3b81ci"/><path fill="url(#iCwdjPc)" class="ufs3b81ci"/></g><path fill="url(#iqgHXuc)" class="j_m47xbqb"/><path fill="url(#iVs0ptc)" class="j_m47xbqb"/><g filter="url(#ih10ftd)"><path class="t-_6tzcpa"/></g><path fill="url(#iqNjaEc)" class="g4-rnpbiv"/><path fill="url(#iThywBd)" class="g4-rnpbiv"/><path fill="url(#idfxACe)" class="qxv17obmu"/><path fill="url(#isUbT6b)" class="qxv17obmu"/><path fill="url(#iBWuPqc)" class="qxv17obmu"/><path fill="url(#iLbr7Sb)" class="qhpil-b3e"/><path fill="url(#iTnTIGe)" class="qhpil-b3e"/><path fill="url(#iC9Y0Gc)" class="qhpil-b3e"/><path class="fpvljrbim"/><path fill="url(#ibEjBCd)" class="s386_46_x"/><path fill="url(#ibzhVWd)" class="s386_46_x"/><path fill="url(#iS46Coe)" class="s386_46_x"/><g filter="url(#iL5UaBb)"><path class="i9cgj7g1s"/><path fill="url(#i1QOigd)" class="vcvz10bee"/><path fill="url(#ivUZRZQ)" class="vcvz10bee"/><path fill="url(#iNTvdNe)" class="vcvz10bee"/></g><g filter="url(#i0kqHyd)"><path fill="url(#itRDtdd)" class="ufa4e1bue"/></g><path fill="url(#iaHeeWc)" class="wtx0-zb9b"/><path fill="url(#i90tZDe)" class="wtx0-zb9b"/><path fill="url(#igIhd3Q)" class="e72vc5glc"/><path fill="url(#iPrxOGx)" class="e72vc5glc"/><path fill="url(#ih3lSMc)" class="e72vc5glc"/><path clip-rule="evenodd" class="ttit7sbwx"/><path fill="url(#i78Qyac)" clip-rule="evenodd" class="x81pqcclg"/><path clip-rule="evenodd" class="vat8zbb1h"/><path fill="url(#iyFuXyd)" clip-rule="evenodd" class="tej0dgbcx"/><path clip-rule="evenodd" class="z2_7lnp1p"/><path fill="url(#ibHJEZc)" clip-rule="evenodd" class="au2cdjbqa"/><path clip-rule="evenodd" class="hikihhbgc"/><path fill="url(#i7bcDzd)" clip-rule="evenodd" class="j873t3pix"/><path clip-rule="evenodd" class="njoad_bkl"/><path fill="url(#i595LEd)" clip-rule="evenodd" class="qb45jbc1d"/><path clip-rule="evenodd" class="rv50jfbso"/><path fill="url(#ie4bhgh)" clip-rule="evenodd" class="a57epkiey"/><path clip-rule="evenodd" class="dzzs3_bwg"/><path fill="url(#irOah5X)" clip-rule="evenodd" class="onaimccwi"/><g filter="url(#invbudb)"><path class="s4y_htbex"/></g><g filter="url(#iJGRGNt)"><path class="fn3z_sbxx"/></g><g filter="url(#i99aXte)"><path class="y8dgjevrz"/></g><g filter="url(#i3wHl7c)"><path class="mkk0k-byc"/></g><g filter="url(#iELjK8b)"><path class="znfzn6b4i"/></g><g filter="url(#idQkmYE)"><path class="rm-es7b9q"/></g><g filter="url(#i2k0OJb)"><path class="w0_6atbzj"/></g><g filter="url(#i4mln9c)"><path class="p5j2ywblw"/></g><g filter="url(#im1uDRd)"><path fill="url(#iIvXowq)" class="t4q8veb0u"/></g><g filter="url(#iYejd8C)"><path fill="url(#iUcVsEd)" class="yjgw3yb2o"/><path fill="url(#iBY5AFc)" class="yjgw3yb2o"/></g><g filter="url(#idLAsgc)"><path class="n1b6kobth"/><path fill="url(#iLC6kbd)" class="vfw12_bbv"/></g><g filter="url(#iW47E1b)"><path class="nkt8nb64z"/><path fill="url(#iwVlWAe)" class="ov239_aed"/></g><g filter="url(#iG72P0c)"><path fill="url(#iqPUD5c)" class="ndx237bfn"/><path fill="url(#ixxJXNc)" class="ndx237bfn"/><path fill="url(#idhS6yd)" class="ndx237bfn"/><path fill="url(#ixaqINe)" class="ndx237bfn"/><path fill="url(#i8yuXme)" class="ndx237bfn"/><path fill="url(#idq7bJc)" class="ndx237bfn"/><path fill="url(#idtxsLb)" class="ndx237bfn"/><path fill="url(#i2wP2IJ)" class="ndx237bfn"/></g><path fill="url(#iTJoEce)" class="ndx237bfn"/><path fill="url(#i90H0Ie)" class="ndx237bfn"/><g filter="url(#ieKep2b)"><path class="q8wvlzcog"/></g><g filter="url(#irjunEG)"><path class="n593-h0lp"/><path fill="url(#iN3Jloe)" class="dcqffcksb"/><path fill="url(#im7hPtc)" class="dcqffcksb"/><path fill="url(#imG0sUc)" class="dcqffcksb"/><path fill="url(#i78jcme)" class="dcqffcksb"/></g><g filter="url(#iWTSJRb)"><path stroke="url(#iRf9lWd)" class="yovzqmm0i"/></g><path class="m0tdfxbca"/><g filter="url(#iwytPbd)"><path class="k0aw04b2u"/></g><g filter="url(#iGqjH9c)"><path clip-rule="evenodd" class="unvqb29ij"/></g><g filter="url(#izxPPhe)"><path class="ibxqzabwf"/></g><g filter="url(#iydyRZc)"><path class="n5hu6ibdf"/></g><g filter="url(#iAMiFev)"><path class="t7jhibcvh"/><path fill="url(#iRlREOe)" class="t99n20blw"/><path fill="url(#ilUxd0d)" class="t99n20blw"/></g><g filter="url(#iiuXukW)"><path stroke="url(#iWwkXkd)" class="ofmqyon8k"/></g><g filter="url(#iS4SO8d)"><path class="d0o921bnx"/></g><path class="hss_x8b0z"/><g filter="url(#iRq0KGd)"><path class="wd5n0p1ub"/></g><path class="iap9bjb7s"/><g filter="url(#iU4Taxe)"><path class="b2v39zblc"/></g><defs><radialGradient id="iuPiZod" cx="0" cy="0" r="1" gradientTransform="matrix(-.3817 2.88392 -3.6026 -.47681 15.829 8.963)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iaITejh" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8237 1.22992 -1.61602 -2.3962 14.047 9.133)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="isXS1xd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 4.62 6.962)scale(1.36144 1.0454)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i1ddgkd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 4.871 6.832)scale(1.56564 1.10286)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ip2dCMe" cx="0" cy="0" r="1" gradientTransform="matrix(.86941 1.65402 -2.29603 1.20688 13.793 2.284)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="isqhalb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.11 5.881)scale(1.28948 1.80203)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ieqmtIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16624 .33929 -.70756 -2.4321 20.77 6.843)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iRPBQmu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7812 .44532 -.56727 -2.26897 20.388 9.006)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="icNClhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.57212 -1.67647 1.326 -.45252 19.013 5.303)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i5jhrHd" cx="0" cy="0" r="1" gradientTransform="matrix(.95133 .0998 -.16171 1.54143 12.136 6.82)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iiI7UPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.55175 1.76259 -1.62476 -.50861 12.457 4.866)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="iiFEcXb" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.438 13.206)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="fznz2mbxx"/><stop offset="1" class="hnjuf644p"/></radialGradient><radialGradient id="iALeSad" cx="0" cy="0" r="1" gradientTransform="matrix(.23438 .67187 -1.35614 .47307 26.835 22.69)" gradientUnits="userSpaceOnUse"><stop class="fznz2mbxx"/><stop offset="1" class="hnjuf644p"/></radialGradient><radialGradient id="i6ucWWc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.424)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="zhfkvgbxb"/><stop offset="1" class="uq-h9hb8w"/></radialGradient><radialGradient id="iCwdjPc" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -7.058 31.738)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="u24mgdcov"/><stop offset="1" class="rwyr8xb2b"/></radialGradient><radialGradient id="iqgHXuc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.768)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="hfnjpubec"/><stop offset="1" class="t0fy-bbwc"/></radialGradient><radialGradient id="iVs0ptc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.409)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="k-fq99sbh"/><stop offset="1" class="phf6igbvb"/></radialGradient><radialGradient id="iqNjaEc" cx="0" cy="0" r="1" gradientTransform="rotate(165.069 8.953 14.565)scale(1.45539 2.44377)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="mwtukgbbz"/><stop offset="1" class="fozz65l2p"/></radialGradient><radialGradient id="iThywBd" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 -1.5 3.43224 4.2188 6.044 26.706)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="lg8towb3y"/><stop offset="1" class="pdvw2hfdl"/></radialGradient><radialGradient id="idfxACe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.33)" gradientUnits="userSpaceOnUse"><stop class="us72pebsg"/><stop offset="1" class="hx5ihzb7y"/></radialGradient><radialGradient id="iLbr7Sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="uwa_e26-a"/><stop offset="1" class="hx5ihzb7y"/></radialGradient><radialGradient id="ibzhVWd" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.158 23.732)" gradientUnits="userSpaceOnUse"><stop class="w-l5r38ro"/><stop offset="1" class="lehanccnj"/></radialGradient><radialGradient id="iS46Coe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20.237)" gradientUnits="userSpaceOnUse"><stop class="pc6ft5bqj"/><stop offset="1" class="crrluq_8b"/></radialGradient><radialGradient id="ivUZRZQ" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.277 7.65)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="uo439xb-e"/><stop offset="1" class="wsizjkbjw"/></radialGradient><radialGradient id="iNTvdNe" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.33)" gradientUnits="userSpaceOnUse"><stop class="ept1d-nvv"/><stop offset="1" class="iu4sfzbng"/></radialGradient><radialGradient id="itRDtdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.33)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="iaHeeWc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.125 2.517)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="pk5i2pb0j"/><stop offset="1" class="d-f_cevwl"/></radialGradient><radialGradient id="i90tZDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6426 3.87499 -4.37028 -1.85255 15.175 9.58)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="rsji3yblh"/><stop offset="1" class="ddt4h9ktn"/></radialGradient><radialGradient id="igIhd3Q" cx="0" cy="0" r="1" gradientTransform="matrix(.48635 10.50004 -6.22624 .2884 17.69 13.519)" gradientUnits="userSpaceOnUse"><stop offset=".056" class="q9yk7oosj"/><stop offset="1" class="ddgxe2b5l"/></radialGradient><radialGradient id="iPrxOGx" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.536 10.87)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="xz9f7bbos"/><stop offset="1" class="auvxm7b4e"/></radialGradient><radialGradient id="ih3lSMc" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 12.05)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="gd3w__bkb"/><stop offset="1" class="gz75fzb0l"/></radialGradient><radialGradient id="i78Qyac" cx="0" cy="0" r="1" gradientTransform="matrix(.04721 .75606 -4.208 .26278 4.575 23.17)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="iyFuXyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0472 .75606 -4.20801 -.26276 27.424 23.17)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="ibHJEZc" cx="0" cy="0" r="1" gradientTransform="matrix(.05288 .98594 -4.7173 .25299 4.591 23.76)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="i7bcDzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05288 .98594 -4.7173 -.25299 27.409 23.76)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="i595LEd" cx="0" cy="0" r="1" gradientTransform="matrix(.00011 .90392 -3.36918 .00041 5.113 24.51)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="ie4bhgh" cx="0" cy="0" r="1" gradientTransform="matrix(-.00011 .90392 -3.36917 -.00041 26.887 24.51)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="iUcVsEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5745 -.71568 .87381 1.92238 18.575 7.66)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iBY5AFc" cx="0" cy="0" r="1" gradientTransform="matrix(.8323 .46652 -.1319 .2353 19.227 6.318)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iLC6kbd" cx="0" cy="0" r="1" gradientTransform="matrix(.9551 -.07105 .05554 .74663 18.798 7.452)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iwVlWAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7634 0 0 -.60222 13.109 7.381)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iqPUD5c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.11395 1.89708 -2.5392 -5.50645 17.828 7.041)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="ixxJXNc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2882 .61408 -.42763 -.89708 17.175 7.576)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="idhS6yd" cx="0" cy="0" r="1" gradientTransform="matrix(.67905 -2.19886 2.78993 .86158 14.64 11.332)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="ixaqINe" cx="0" cy="0" r="1" gradientTransform="matrix(-.50735 4.30146 -4.3245 -.51007 16.361 7.14)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="i8yuXme" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15401 -4.17626 0 15.854 7.288)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="idq7bJc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.187 4.902)scale(4.45162 7.66432)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="idtxsLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72794 .89338 0 17.475 6.777)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="i2wP2IJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.83025 .95153 0 14.706 6.632)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iTJoEce" cx="0" cy="0" r="1" gradientTransform="matrix(-.81303 0 0 -4.07726 19.243 7.718)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="i90H0Ie" cx="0" cy="0" r="1" gradientTransform="rotate(139.279 7.343 8.572)scale(1.52655 1.02313)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iN3Jloe" cx="0" cy="0" r="1" gradientTransform="matrix(-.28816 -1.29298 .39848 -.0888 16.516 8.177)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="i78jcme" cx="0" cy="0" r="1" gradientTransform="matrix(-.49302 0 0 -.13784 16.364 8.311)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iRlREOe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33595 2.77789 -4.54169 -2.1842 17.228 2.368)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ilUxd0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.13305 .86484 -1.86067 -.28625 16.152 2.602)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iSpSJDe" width="9.75" height="10.25" x="11.27" y="1.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/></filter><filter id="icHdYSb" width="9.729" height="6.156" x="17.627" y="22.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.184314 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.156863 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23986" result="effect2_innerShadow_3987_23986"/></filter><filter id="ih10ftd" width="17.213" height="7.995" x="5.751" y="22.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23986" result="effect2_innerShadow_3987_23986"/></filter><filter id="iL5UaBb" width="7.621" height="12.797" x="19.836" y="12.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0666667 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/></filter><filter id="i0kqHyd" width="8.502" height="3.19" x="11.869" y="21.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/></filter><filter id="invbudb" width="1.684" height="1.255" x="5.351" y="24.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="iJGRGNt" width="1.684" height="1.255" x="24.965" y="24.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="i99aXte" width="2.04" height="1.095" x="4.237" y="24.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="i3wHl7c" width="2.04" height="1.095" x="25.723" y="24.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="iELjK8b" width="2.223" height=".888" x="3.593" y="23.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="idQkmYE" width="2.223" height=".888" x="26.184" y="23.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="i2k0OJb" width="2.031" height=".566" x="3.653" y="23.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="i4mln9c" width="2.031" height=".566" x="26.317" y="23.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="im1uDRd" width="2.186" height="2.036" x="12.038" y="6.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/></filter><filter id="iYejd8C" width="2.036" height="2.286" x="18.056" y="6.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/></filter><filter id="idLAsgc" width="2.359" height="2.359" x="17.894" y="6.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".25"/></filter><filter id="iW47E1b" width="1.859" height="1.859" x="12.138" y="6.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".125"/></filter><filter id="iG72P0c" width="6.446" height="7.13" x="12.796" y="4.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/></filter><filter id="ieKep2b" width="2.188" height="2.696" x="14.823" y="6.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".25"/></filter><filter id="irjunEG" width="1.488" height="1.996" x="15.276" y="6.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="iWTSJRb" width="2.489" height="1.112" x="14.775" y="8.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".05"/></filter><filter id="iwytPbd" width="1.625" height=".764" x="13.611" y="5.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/></filter><filter id="iGqjH9c" width="1.625" height=".764" x="17.038" y="5.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/></filter><filter id="izxPPhe" width="1.501" height=".689" x="17.022" y="5.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="iydyRZc" width="1.501" height=".689" x="13.573" y="5.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".075"/></filter><filter id="iAMiFev" width="5.698" height="3.741" x="13.904" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23986"/><feGaussianBlur result="effect2_foregroundBlur_3987_23986" stdDeviation=".1"/></filter><filter id="iiuXukW" width=".945" height="1.681" x="13.891" y="2.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".1"/></filter><filter id="iS4SO8d" width="3.917" height="1.984" x="15.726" y="3.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".2"/></filter><filter id="iRq0KGd" width="1.628" height=".644" x="13.82" y="6.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".05"/></filter><filter id="iU4Taxe" width="1.628" height=".644" x="16.609" y="6.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23986" stdDeviation=".05"/></filter><linearGradient id="i5fTJje" x1="11.475" x2="20.569" y1="10.424" y2="10.424" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iaEYyPe" x1="18.988" x2="14.684" y1="2.983" y2="10.957" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iWyEhDb" x1="11.475" x2="20.569" y1="10.405" y2="10.405" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="isUbT6b" x1="21.525" x2="21.525" y1="21.268" y2="22.424" gradientUnits="userSpaceOnUse"><stop class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iBWuPqc" x1="18.658" x2="19.892" y1="24.552" y2="24.956" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iTnTIGe" x1="10.822" x2="10.822" y1="21.268" y2="22.424" gradientUnits="userSpaceOnUse"><stop class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iC9Y0Gc" x1="13.689" x2="12.455" y1="24.552" y2="24.956" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="ibEjBCd" x1="12.24" x2="10.033" y1="20.873" y2="20.683" gradientUnits="userSpaceOnUse"><stop offset=".184" class="w3geznflg"/><stop offset="1" class="o-0p8ab1g"/></linearGradient><linearGradient id="i1QOigd" x1="19.835" x2="22.042" y1="20.873" y2="20.683" gradientUnits="userSpaceOnUse"><stop offset=".184" class="e5bi16n_y"/><stop offset="1" class="n9h2xzfye"/></linearGradient><linearGradient id="irOah5X" x1="26.513" x2="24.888" y1="25.44" y2="24.177" gradientUnits="userSpaceOnUse"><stop offset=".455" class="fznz2mbxx"/><stop offset="1" class="b04py3bjk"/></linearGradient><linearGradient id="iIvXowq" x1="12.038" x2="13.91" y1="7.436" y2="7.436" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="im7hPtc" x1="15.426" x2="16.02" y1="8.223" y2="8.223" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="imG0sUc" x1="16.02" x2="16.02" y1="8.729" y2="8.343" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iRf9lWd" x1="15.347" x2="15.638" y1="9.621" y2="9.17" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iWwkXkd" x1="14.191" x2="14.536" y1="3.46" y2="4.266" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-lotus-position-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a57epkiey {
  fill-rule: evenodd;
  d: path("M25.902 24.184a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.113l.037.003a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.053-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.au2cdjbqa {
  fill-rule: evenodd;
  d: path("M5.825 23.762a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8c.226 0 .852-.06 1.466-.364a.4.4 0 0 1 .537.18");
}

.auvxm7b4e {
  stop-color: var(--svg-color--422d70, #422D70);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
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

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.crrluq_8b {
  stop-color: var(--svg-color--2b0c0a, #2B0C0A);
  stop-opacity: 0;
}

.d-f_cevwl {
  stop-color: var(--svg-color--4a3532, #4A3532);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d0o921bnx {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.542 4.737l-.902.166a.435.435 0 1 1-.079-.864h1.48c.876 0 1.166.883 1.202 1.184a1.99 1.99 0 0 0-1.701-.486");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dcqffcksb {
  d: path("m15.778 7.153l-.337 1.075a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443l-.337-1.075c-.072-.238-.408-.238-.483 0");
}

.ddgxe2b5l {
  stop-color: var(--svg-color--7455b7, #7455B7);
}

.ddt4h9ktn {
  stop-color: var(--svg-color--432e2c, #432E2C);
  stop-opacity: 0;
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dzzs3_bwg {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M6.818 24.409c.14.17.272.303.101.443c-.565.464-.934.651-1.193.783l-.072.037a.4.4 0 1 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e5bi16n_y {
  stop-color: var(--svg-color--2f0c0a, #2F0C0A);
}

.e72vc5glc {
  d: path("M18.892 11.39v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.56-1.285-.894");
}

.ept1d-nvv {
  stop-color: var(--svg-color--655351, #655351);
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
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

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
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

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g4-rnpbiv {
  d: path("M10.236 28.174c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.17.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gd3w__bkb {
  stop-color: var(--svg-color--785684, #785684);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gz75fzb0l {
  stop-color: var(--svg-color--735ea4, #735EA4);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hfnjpubec {
  stop-color: var(--svg-color--3c2826, #3C2826);
}

.hikihhbgc {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M26.175 23.762a.4.4 0 0 0 .18.536c.754.374 1.51.448 1.823.448a.4.4 0 0 0 0-.8c-.226 0-.852-.06-1.466-.364a.4.4 0 0 0-.537.18");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hnjuf644p {
  stop-color: var(--svg-color--402723, #402723);
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

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
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

.ibxqzabwf {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.247 5.88c.204-.05.711-.024 1.05.218");
}

.iu4sfzbng {
  stop-color: var(--svg-color--543b37, #543B37);
  stop-opacity: 0;
}

.j_m47xbqb {
  d: path("M13.22 24.55h-1.429a1 1 0 0 0-.943.67c-.408 1.17-.96 2.764-1.032 3.001c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j873t3pix {
  fill-rule: evenodd;
  d: path("M26.175 23.762a.4.4 0 0 0 .18.536c.754.374 1.51.448 1.823.448a.4.4 0 0 0 0-.8c-.226 0-.852-.06-1.466-.364a.4.4 0 0 0-.537.18");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.k-fq99sbh {
  stop-color: var(--svg-color--62514e, #62514E);
  stop-opacity: 0;
}

.k0aw04b2u {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m13.87 6.257l-.002.001a.17.17 0 0 1-.175-.29l.001-.001l.002-.001l.006-.004a1 1 0 0 1 .094-.048a2 2 0 0 1 .26-.103c.215-.068.515-.126.84-.069a.17.17 0 0 1-.06.334c-.252-.044-.494 0-.677.058a2 2 0 0 0-.275.115z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.khd1c0n-i {
  stop-color: var(--svg-color--351916, #351916);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.lehanccnj {
  stop-color: var(--svg-color--512d27, #512D27);
  stop-opacity: 0;
}

.lg8towb3y {
  stop-color: var(--svg-color--634f4b, #634F4B);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.m0tdfxbca {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.02 9.223c-.33 0-.639-.08-.9-.218c-.088-.046-.184.056-.128.139a1.222 1.222 0 0 0 2.056 0c.056-.086-.04-.185-.129-.139a1.9 1.9 0 0 1-.899.218");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
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

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1b6kobth {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M19.074 8.06a.68.68 0 1 0 0-1.358a.68.68 0 0 0 0 1.359");
}

.n55l0rxro {
  stop-color: var(--svg-color--351916, #351916);
}

.n593-h0lp {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.778 7.153l-.337 1.075a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443l-.337-1.075c-.072-.238-.408-.238-.483 0");
}

.n5hu6ibdf {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.849 5.88c-.204-.05-.712-.024-1.05.218");
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.n9h2xzfye {
  stop-color: var(--svg-color--2f0c0a, #2F0C0A);
  stop-opacity: 0;
}

.ncyg9ebdc {
  d: path("M20.565 8.273c.134-.275.204-.582.204-.903c0-.295-.06-.572-.17-.825h.004a2 2 0 0 0-.178-.325l-.001-.002a2.05 2.05 0 0 1-.333-1.12v-.006a2.087 2.087 0 0 0-2.087-2.087a.34.34 0 0 1-.288-.148a2.09 2.09 0 0 0-3.393 0a.36.36 0 0 1-.288.148h-.054a2.087 2.087 0 0 0-2.033 2.087v.006c0 .397-.115.787-.333 1.12l-.001.003a2.09 2.09 0 0 0-.14 2.052a.33.33 0 0 1 0 .288a2.033 2.033 0 0 0 1.83 2.926h5.43a2.033 2.033 0 0 0 1.83-2.926a.33.33 0 0 1 0-.288m-7.756-1.69h-.007l.758 1.49c.078 1.772.77 0 2.46 0s2.426 1.973 2.504.2l.719-2.022c-.034-.788-.605-.843-.719-.843h-2.037A2.44 2.44 0 0 1 14.47 4.35a.167.167 0 0 0-.292.032l-.052.122a1.46 1.46 0 0 1-.752.781l-.033.013l-.032.013c-.15.078-.5.31-.513.91l.007.194z");
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.ndx237bfn {
  d: path("M12.802 6.583h.007l-.006-.168l-.007-.194c.013-.6.364-.832.513-.91l.032-.013l.033-.013c.337-.155.61-.426.752-.78l.052-.123a.167.167 0 0 1 .292-.032a2.44 2.44 0 0 0 2.017 1.058h2.037c.114 0 .685.055.719.843l-.075 1.944c-.078 1.772-1.463 2.963-3.153 2.963s-3.074-1.19-3.152-2.963z");
}

.ne66_lm1q {
  d: path("M16.244 10.405q.239.01.487.032c-.164-.013-.322-.026-.487-.032");
}

.njoad_bkl {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M6.099 24.184a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.113l-.037.003a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.nkt8nb64z {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M13.068 8.06a.68.68 0 1 0 0-1.358a.68.68 0 0 0 0 1.359");
}

.o-0p8ab1g {
  stop-color: var(--svg-color--391816, #391816);
  stop-opacity: 0;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.ofmqyon8k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.19 3.243c.016.154.15.732.346 1.082");
}

.onaimccwi {
  fill-rule: evenodd;
  d: path("M25.182 24.409c-.14.17-.272.303-.101.443c.565.464.934.651 1.193.783l.072.037a.4.4 0 0 0 .367-.711l-.074-.038a5 5 0 0 1-1.051-.69c-.17-.14-.266.005-.406.176");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ov239_aed {
  d: path("M13.068 8.06a.68.68 0 1 0 0-1.358a.68.68 0 0 0 0 1.359");
}

.p5j2ywblw {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.502c-.398 0-.893.047-1.58-.109");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pc6ft5bqj {
  stop-color: var(--svg-color--2b0c0a, #2B0C0A);
}

.pdvw2hfdl {
  stop-color: var(--svg-color--634f4b, #634F4B);
  stop-opacity: 0;
}

.phf6igbvb {
  stop-color: var(--svg-color--62514e, #62514E);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pk5i2pb0j {
  stop-color: var(--svg-color--62514f, #62514F);
}

.q8wvlzcog {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.771 7.24l-.432 1.076a.34.34 0 0 0 .33.442h.497a.342.342 0 0 0 .329-.442l-.336-1.076c-.072-.238-.312-.238-.388 0");
}

.q9yk7oosj {
  stop-color: var(--svg-color--987fd3, #987FD3);
}

.qb45jbc1d {
  fill-rule: evenodd;
  d: path("M6.099 24.184a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.113l-.037.003a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qhpil-b3e {
  d: path("M13.83 21.56H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qxv17obmu {
  d: path("M18.517 21.56h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rm-es7b9q {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.252a3.8 3.8 0 0 1-1.773-.437");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
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

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
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

.t4q8veb0u {
  d: path("M13.056 8.4a1.018 1.018 0 1 0 0-2.037a1.018 1.018 0 0 0 0 2.036");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t7jhibcvh {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.638 2.453c-.717-.158-1.36.557-1.434.822c.665 2.242 2.348 2.12 4.01 1.935c.995-.11 1.103.343 1.188.562c0-2.488-2.116-2.955-3.746-3.315z");
}

.t99n20blw {
  d: path("M15.638 2.453c-.717-.158-1.36.557-1.434.822c.665 2.242 2.348 2.12 4.01 1.935c.995-.11 1.103.343 1.188.562c0-2.488-2.116-2.955-3.746-3.315z");
}

.tej0dgbcx {
  fill-rule: evenodd;
  d: path("M26.304 23.284a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
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

.u24mgdcov {
  stop-color: var(--svg-color--261413, #261413);
}

.uc5_bsbkt {
  stop-color: var(--svg-color--281816, #281816);
}

.ufa4e1bue {
  d: path("m13.447 24.55l-1.578-2.99h8.301l-1.551 2.99z");
}

.ufs3b81ci {
  d: path("M17.627 28.174h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.ul7b3bcbn {
  d: path("M16.036 10.405h-.026c.063 0 .12 0 .184.006c-.05-.006-.108-.006-.158-.006");
}

.unvqb29ij {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m18.38 5.967l-.087.146za.17.17 0 0 1-.174.291l-.003-.001l-.072-.037a2 2 0 0 0-.216-.086a1.44 1.44 0 0 0-.678-.058a.17.17 0 0 1-.06-.334c.325-.057.626 0 .841.07a2 2 0 0 1 .353.15l.006.004z");
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

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vat8zbb1h {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M26.304 23.284a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.vcvz10bee {
  d: path("M22.32 16.317c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.651.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.704c-.874-.499-3.37-2.968-4.01-3.605c-.538-.535-.641-1.215-.876-3.197");
}

.vfw12_bbv {
  d: path("M19.074 8.06a.68.68 0 1 0 0-1.358a.68.68 0 0 0 0 1.359");
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

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w3geznflg {
  stop-color: var(--svg-color--391816, #391816);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wd5n0p1ub {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.01a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wsizjkbjw {
  stop-color: var(--svg-color--502822, #502822);
}

.wtx0-zb9b {
  d: path("M18.892 11.39v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x81pqcclg {
  fill-rule: evenodd;
  d: path("M5.697 23.284a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xz9f7bbos {
  stop-color: var(--svg-color--644e9f, #644E9F);
  stop-opacity: 0;
}

.y8dgjevrz {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.983c.41-.067 1.204-.313 1.59-.645");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yjgw3yb2o {
  d: path("M19.074 8.4a1.018 1.018 0 1 0 0-2.037a1.018 1.018 0 0 0 0 2.036");
}

.yovzqmm0i {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.02 9.223c-.33 0-.639-.08-.9-.218c-.088-.046-.184.056-.128.139a1.222 1.222 0 0 0 2.056 0c.056-.086-.04-.185-.129-.139a1.9 1.9 0 0 1-.899.218Z");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
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

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zhfkvgbxb {
  stop-color: var(--svg-color--4b3b39, #4B3B39);
}

.znfzn6b4i {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.252a3.8 3.8 0 0 0 1.773-.437");
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
