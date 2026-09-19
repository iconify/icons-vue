<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#svgIDa)" class="d2kvgvbvc"><path fill="url(#svgIDb)" class="pkgup_r3x"/><path fill="url(#svgIDc)" class="pkgup_r3x"/><path fill="url(#svgIDd)" class="pkgup_r3x"/><path fill="url(#svgIDe)" class="pkgup_r3x"/><path fill="url(#svgIDf)" class="pkgup_r3x"/><path fill="url(#svgIDg)" class="pkgup_r3x"/><path fill="url(#svgIDh)" class="pkgup_r3x"/><path fill="url(#svgIDi)" class="pkgup_r3x"/><path fill="url(#svgIDj)" class="pkgup_r3x"/><path fill="url(#svgIDk)" class="pkgup_r3x"/><path fill="url(#svgIDl)" class="pkgup_r3x"/><path fill="url(#svgIDm)" class="pkgup_r3x"/></g><path fill="url(#svgIDn)" class="m13u431kg"/><path fill="url(#svgIDo)" class="m13u431kg"/><g filter="url(#svgIDp)"><path class="wta2hpbbu"/></g><g filter="url(#svgIDq)"><path class="zn9l18bel"/></g><path fill="url(#svgIDr)" class="xbx983bqi"/><path fill="url(#svgIDs)" class="xbx983bqi"/><path fill="url(#svgIDt)" class="wp-jxgbtg"/><path fill="url(#svgIDu)" class="wp-jxgbtg"/><circle class="v2km0iban"/><g filter="url(#svgIDv)"><path clip-rule="evenodd" class="zu171j-5k"/></g><circle fill="url(#svgIDw)" transform="matrix(-1 0 0 1 12.14 16.739)" class="kr_eiac3t"/><g clip-rule="evenodd" filter="url(#svgIDx)" class="d2kvgvbvc"><path class="kt4yl3aye"/><path fill="url(#svgIDy)" class="s7_ij4e9o"/></g><g filter="url(#svgIDz)"><path stroke="url(#svgIDA)" class="z_-rptbza"/></g><g filter="url(#svgIDB)"><path class="s9yxi39gy"/></g><path fill="url(#svgIDC)" class="zkik3tf0n"/><path fill="url(#svgIDD)" class="zkik3tf0n"/><path fill="url(#svgIDE)" class="zkik3tf0n"/><path fill="url(#svgIDF)" class="zkik3tf0n"/><path fill="url(#svgIDG)" class="zkik3tf0n"/><path fill="url(#svgIDH)" class="oaoygtbmw"/><g filter="url(#svgIDI)"><path class="hj3gllh6o"/></g><path fill="url(#svgIDJ)" class="o7s685biz"/><path fill="url(#svgIDK)" class="ppzi198mm"/><g filter="url(#svgIDL)"><path fill="url(#svgIDM)" class="w1_fhgbib"/></g><g filter="url(#svgIDN)"><path fill="url(#svgIDO)" class="ouz5otbck"/><path fill="url(#svgIDP)" class="ouz5otbck"/></g><g filter="url(#svgIDQ)"><path class="uelhvmb6u"/><path fill="url(#svgIDR)" class="m8w64fj6m"/></g><g filter="url(#svgIDS)"><path class="sy0zbq_3i"/><path fill="url(#svgIDT)" class="aufaspb6t"/></g><path fill="url(#svgIDU)" class="u7lq--uob"/><path fill="url(#svgIDV)" class="u7lq--uob"/><path fill="url(#svgIDW)" class="u7lq--uob"/><path fill="url(#svgIDX)" class="u7lq--uob"/><path fill="url(#svgIDY)" class="u7lq--uob"/><path fill="url(#svgIDZ)" class="u7lq--uob"/><path fill="url(#svgIDaa)" class="u7lq--uob"/><path fill="url(#svgIDab)" class="u7lq--uob"/><g filter="url(#svgIDac)"><path class="cneei5bfx"/></g><g filter="url(#svgIDad)"><path class="kr3uvebrb"/><path fill="url(#svgIDae)" class="eueah-bko"/><path fill="url(#svgIDaf)" class="eueah-bko"/><path fill="url(#svgIDag)" class="eueah-bko"/><path fill="url(#svgIDah)" class="eueah-bko"/></g><g filter="url(#svgIDai)"><path stroke="url(#svgIDaj)" class="c6t9q9t0p"/></g><path class="ij6e_flvx"/><g filter="url(#svgIDak)"><path class="zj5_ndbyi"/></g><g filter="url(#svgIDal)"><path class="z7ij1iwfj"/></g><g filter="url(#svgIDam)"><path class="bkq2_fbzi"/></g><g filter="url(#svgIDan)"><path clip-rule="evenodd" class="u93mv04rn"/></g><path class="t9gn0gubf"/><path fill="url(#svgIDao)" class="bexy-42mj"/><path class="i8vat4bhf"/><g filter="url(#svgIDap)"><path class="o9p0hdcko"/><path fill="url(#svgIDaq)" class="m5z9y92ou"/></g><g filter="url(#svgIDar)"><path fill="url(#svgIDas)" class="xm1uw9wfi"/></g><path class="ntd7jh7ht"/><path fill="url(#svgIDat)" class="hbrsypbww"/><path class="bv3t6_blq"/><g filter="url(#svgIDau)"><path fill="url(#svgIDav)" class="i2k_4ucjp"/></g><g filter="url(#svgIDaw)" transform="rotate(-27.914 7.75 7.341)"><ellipse class="pqc0jpzvo"/><ellipse fill="url(#svgIDax)" class="ookmcab6n"/></g><g filter="url(#svgIDay)"><path class="e0rhdacll"/><path fill="url(#svgIDaz)" class="nnhpnuu4a"/><path fill="url(#svgIDaA)" class="nnhpnuu4a"/></g><g filter="url(#svgIDaB)"><path stroke="url(#svgIDaC)" class="ydfbc88-u"/></g><g filter="url(#svgIDaD)"><path class="lzae809fx"/></g><g filter="url(#svgIDaE)"><path class="e-c-ph2vh"/></g><g filter="url(#svgIDaF)"><path class="mddk40bcp"/></g><g filter="url(#svgIDaG)"><path fill="url(#svgIDaH)" class="ubd-76htt"/></g><g clip-rule="evenodd" filter="url(#svgIDaI)" class="d2kvgvbvc"><path fill="url(#svgIDaJ)" class="yd4xnabcc"/><path fill="url(#svgIDaK)" class="yd4xnabcc"/><path fill="url(#svgIDaL)" class="yd4xnabcc"/><path fill="url(#svgIDaM)" class="yd4xnabcc"/><path fill="url(#svgIDaN)" class="yd4xnabcc"/><path fill="url(#svgIDaO)" class="yd4xnabcc"/><path fill="url(#svgIDaP)" class="yd4xnabcc"/><path fill="url(#svgIDaQ)" class="yd4xnabcc"/><path fill="url(#svgIDaR)" class="yd4xnabcc"/><path fill="url(#svgIDaS)" class="yd4xnabcc"/><path fill="url(#svgIDaT)" class="yd4xnabcc"/><path fill="url(#svgIDaU)" class="yd4xnabcc"/></g><path fill="url(#svgIDaV)" class="rk548sxih"/><path fill="url(#svgIDaW)" class="rk548sxih"/><g filter="url(#svgIDaX)"><path class="dv5g3pabb"/></g><g filter="url(#svgIDaY)"><path class="qr08jwbig"/></g><path fill="url(#svgIDaZ)" class="g1-cakgjb"/><path fill="url(#svgIDba)" class="g1-cakgjb"/><path fill="url(#svgIDbb)" class="arrvtbcvm"/><path fill="url(#svgIDbc)" class="arrvtbcvm"/><circle class="f5qs1xbvv"/><g filter="url(#svgIDbd)"><path clip-rule="evenodd" class="rvhaf89mo"/></g><circle fill="url(#svgIDbe)" transform="matrix(-1 0 0 1 25.185 16.739)" class="kr_eiac3t"/><g clip-rule="evenodd" filter="url(#svgIDbf)" class="d2kvgvbvc"><path class="sednhij2q"/><path fill="url(#svgIDbg)" class="ingmib41c"/></g><g filter="url(#svgIDbh)"><path stroke="url(#svgIDbi)" class="dc77xq39a"/></g><g filter="url(#svgIDbj)"><path class="e-189exfc"/></g><path fill="url(#svgIDbk)" class="q7uwbs60e"/><path fill="url(#svgIDbl)" class="q7uwbs60e"/><path fill="url(#svgIDbm)" class="q7uwbs60e"/><path fill="url(#svgIDbn)" class="q7uwbs60e"/><path fill="url(#svgIDbo)" class="q7uwbs60e"/><path fill="url(#svgIDbp)" class="gx9n5e2by"/><g filter="url(#svgIDbq)"><path class="ru-mspmfv"/></g><path fill="url(#svgIDbr)" class="yxaejacmd"/><path fill="url(#svgIDbs)" class="zndunbc5i"/><g filter="url(#svgIDbt)"><path fill="url(#svgIDbu)" class="smqp5cbjs"/></g><g filter="url(#svgIDbv)"><path fill="url(#svgIDbw)" class="o4iu37bjz"/><path fill="url(#svgIDbx)" class="o4iu37bjz"/></g><g filter="url(#svgIDby)"><path class="a9009k51m"/><path fill="url(#svgIDbz)" class="hsda0o_vl"/></g><g filter="url(#svgIDbA)"><path class="nhtv2g6tr"/><path fill="url(#svgIDbB)" class="iib6ombtc"/></g><path fill="url(#svgIDbC)" class="tn_6-_-2a"/><path fill="url(#svgIDbD)" class="tn_6-_-2a"/><path fill="url(#svgIDbE)" class="tn_6-_-2a"/><path fill="url(#svgIDbF)" class="tn_6-_-2a"/><path fill="url(#svgIDbG)" class="tn_6-_-2a"/><path fill="url(#svgIDbH)" class="tn_6-_-2a"/><path fill="url(#svgIDbI)" class="tn_6-_-2a"/><path fill="url(#svgIDbJ)" class="tn_6-_-2a"/><g filter="url(#svgIDbK)"><path class="vximj4nkt"/></g><g filter="url(#svgIDbL)"><path class="n9y5xgysv"/><path fill="url(#svgIDbM)" class="ti3edsf0r"/><path fill="url(#svgIDbN)" class="ti3edsf0r"/><path fill="url(#svgIDbO)" class="ti3edsf0r"/><path fill="url(#svgIDbP)" class="ti3edsf0r"/></g><g filter="url(#svgIDbQ)"><path stroke="url(#svgIDbR)" class="qday-ub6b"/></g><path class="oth45pbbt"/><g filter="url(#svgIDbS)"><path class="y03ns2b1m"/></g><g filter="url(#svgIDbT)"><path class="v2e773bpd"/></g><g filter="url(#svgIDbU)"><path class="t3yukht3a"/></g><g filter="url(#svgIDbV)"><path clip-rule="evenodd" class="zu4ctv27h"/></g><path class="nvt9xwzxq"/><path fill="url(#svgIDbW)" class="q0yhywtwv"/><path class="lrjaftbst"/><g filter="url(#svgIDbX)"><path class="su9i6n-7v"/><path fill="url(#svgIDbY)" class="eufyi6bln"/></g><g filter="url(#svgIDbZ)"><path fill="url(#svgIDca)" class="duap00bnv"/></g><path class="tkqj2jbsv"/><path fill="url(#svgIDcb)" class="gk4kp-bki"/><path class="linjvvhnq"/><g filter="url(#svgIDcc)"><path fill="url(#svgIDcd)" class="akziahbxg"/></g><g filter="url(#svgIDce)" transform="rotate(-27.914 20.796 7.341)"><ellipse class="uwuyphubg"/><ellipse fill="url(#svgIDcf)" class="fjru2dbrb"/></g><g filter="url(#svgIDcg)"><path class="n_n7ypvgo"/><path fill="url(#svgIDch)" class="btd7yfb7z"/><path fill="url(#svgIDci)" class="btd7yfb7z"/></g><g filter="url(#svgIDcj)"><path stroke="url(#svgIDck)" class="rxrgjio9j"/></g><g filter="url(#svgIDcl)"><path class="fo8l5tbiu"/></g><g filter="url(#svgIDcm)"><path class="e4l_esb9l"/></g><g filter="url(#svgIDcn)"><path class="j_f9hxb4x"/></g><g filter="url(#svgIDco)"><path fill="url(#svgIDcp)" class="s22h3gbmb"/></g><defs><radialGradient id="svgIDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25808 1.95009 -2.43605 -.3224 8.672 8.708)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 2.385 5.552) scale(1.4874 1.95433)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="svgIDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5592 .73128 -.56153 -.4294 6.73 7.733)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="matrix(-.55205 .90334 -.63632 -.38887 6.922 6.866)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(.5879 1.11843 -1.55255 .81609 7.295 4.19)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="matrix(-.61653 .61657 -.86165 -.8616 11.296 5.08)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="rotate(163.778 5.488 4.493) scale(.8213 1.71274)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 5.34 5.092) scale(1.2415 1.58148)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="svgIDk" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 7.642 -.756) scale(1.19781 .9474)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="svgIDl" cx="0" cy="0" r="1" gradientTransform="matrix(.64328 .06748 -.10933 1.0423 6.174 7.258)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="svgIDm" cx="0" cy="0" r="1" gradientTransform="matrix(-.3731 1.19185 -1.09865 -.34392 6.392 5.937)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="svgIDr" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDs" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.585 21.054) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.204 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDu" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.495 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="yrxal2b8w"/><stop offset="1" class="iks-j-9-l"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="rotate(157.797 6.31 8.29) scale(1.65389 2.1298)" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset="1" class="izaac2bev"/></radialGradient><radialGradient id="svgIDA" cx="0" cy="0" r="1" gradientTransform="rotate(-155.71 8.768 5.254) scale(3.483 4.40307)" gradientUnits="userSpaceOnUse"><stop class="ev6-__b2a"/><stop offset="1" class="rsfgarwma"/></radialGradient><radialGradient id="svgIDC" cx="0" cy="0" r="1" gradientTransform="matrix(-.31576 -4.42702 2.3084 -.16465 9.068 20.29)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09808 -2.34457 .73972 -.34645 9.856 19.727)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="rotate(140.925 3.46 7.595) scale(2.85608 2.68117)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDG" cx="0" cy="0" r="1" gradientTransform="matrix(.40121 -2.33727 .9853 .16914 7.85 19.552)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63032 -2.125 .51315 8.334 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="u0gzasb1f"/><stop offset=".902" class="mtb7t9jlr"/></radialGradient><radialGradient id="svgIDO" cx="0" cy="0" r="1" gradientTransform="matrix(1.06466 -.48394 .59087 1.2999 10.529 7.825)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(.5628 .31546 -.08918 .15911 10.97 6.919)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.64584 -.04804 .03755 .50486 10.68 7.686)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="svgIDT" cx="0" cy="0" r="1" gradientTransform="matrix(-.5162 0 0 -.40722 6.833 7.638)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="svgIDU" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 4.199 4.804) scale(3.06334 4.10023)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="svgIDV" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 3.913 4.968) scale(.96497 .67199)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="matrix(.45917 -1.48684 1.88653 .5826 7.868 10.309)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="svgIDX" cx="0" cy="0" r="1" gradientTransform="matrix(-.34307 2.9086 -2.92419 -.34491 9.031 7.475)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.8089 -2.82395 0 8.689 7.574)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9538 .57967 -.99802 -5.08555 9.575 8.148)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49223 .6041 0 9.785 7.229)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="svgIDab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56141 .64341 0 7.913 7.13)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="svgIDae" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 7.845 .426) scale(.89575 .27606)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="svgIDah" cx="0" cy="0" r="1" gradientTransform="matrix(-.33338 0 0 -.0932 9.034 8.267)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="svgIDao" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34703 -.55199 0 9.734 7.382)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(-.09896 -.12752 .17557 -.13625 9.635 7.419)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDat" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34703 -.552 0 7.868 7.382)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDax" cx="0" cy="0" r="1" gradientTransform="matrix(-.0033 -.21081 .2534 -.00397 7.744 7.476)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaz" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 3.474 5.147) scale(2.08432 3.40774)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="svgIDaA" cx="0" cy="0" r="1" gradientTransform="matrix(-.08997 .5848 -1.25817 -.19356 8.89 4.406)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="svgIDaK" cx="0" cy="0" r="1" gradientTransform="matrix(-.25808 1.95009 -2.43605 -.3224 21.717 8.708)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="svgIDaL" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 8.908 7.546) scale(1.4874 1.95433)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="svgIDaM" cx="0" cy="0" r="1" gradientTransform="matrix(-.5592 .73128 -.56153 -.4294 19.773 7.733)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="svgIDaN" cx="0" cy="0" r="1" gradientTransform="matrix(-.55205 .90334 -.63632 -.38887 19.968 6.865)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="svgIDaO" cx="0" cy="0" r="1" gradientTransform="matrix(.5879 1.11843 -1.55255 .81609 20.34 4.19)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="svgIDaP" cx="0" cy="0" r="1" gradientTransform="matrix(-.61653 .61657 -.86165 -.8616 24.34 5.08)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="rotate(163.778 12.01 5.422) scale(.8213 1.71274)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11.862 5.895) scale(1.2415 1.58148)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.164 -5.422) scale(1.19781 .9474)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(.64328 .06748 -.10933 1.0423 19.219 7.258)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="matrix(-.3731 1.19185 -1.09865 -.34392 19.437 5.937)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDba" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.062 34.625) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.248 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDbe" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="yrxal2b8w"/><stop offset="1" class="iks-j-9-l"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="rotate(157.797 12.832 9.57) scale(1.65389 2.1298)" gradientUnits="userSpaceOnUse"><stop class="kibsqob-j"/><stop offset="1" class="izaac2bev"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01563 -1.31249 1.6165 -3.71413 27.631 13.675)" gradientUnits="userSpaceOnUse"><stop class="ev6-__b2a"/><stop offset="1" class="rsfgarwma"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(-.31576 -4.42702 2.3084 -.16465 22.113 20.29)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09808 -2.34457 .73972 -.34645 22.9 19.727)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="rotate(140.925 9.982 9.91) scale(2.85608 2.68117)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="matrix(.40121 -2.33727 .9853 .16914 20.895 19.552)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63032 -2.125 .51315 21.38 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="u0gzasb1f"/><stop offset=".902" class="mtb7t9jlr"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(1.06466 -.48394 .59087 1.2999 23.574 7.825)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="svgIDbx" cx="0" cy="0" r="1" gradientTransform="matrix(.5628 .31546 -.08918 .15911 24.015 6.919)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="svgIDbz" cx="0" cy="0" r="1" gradientTransform="matrix(.64584 -.04804 .03755 .50486 23.724 7.686)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="svgIDbB" cx="0" cy="0" r="1" gradientTransform="matrix(-.5162 0 0 -.40722 19.878 7.638)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="svgIDbC" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 10.722 6.235) scale(3.06334 4.10023)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="svgIDbD" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 10.435 6.443) scale(.96497 .67199)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(.45917 -1.48684 1.88653 .5826 20.914 10.309)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="svgIDbF" cx="0" cy="0" r="1" gradientTransform="matrix(-.34307 2.9086 -2.92419 -.34491 22.077 7.474)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="svgIDbG" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.8089 -2.82395 0 21.734 7.574)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9538 .57967 -.99802 -5.08555 22.62 8.148)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49223 .6041 0 22.83 7.229)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56141 .64341 0 20.958 7.13)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="svgIDbM" cx="0" cy="0" r="1" gradientTransform="matrix(-.19485 -.8743 .26945 -.06005 22.181 8.176)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(-.33338 0 0 -.0932 22.079 8.267)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="svgIDbW" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34703 -.55199 0 22.78 7.382)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDbY" cx="0" cy="0" r="1" gradientTransform="matrix(-.09896 -.12752 .17557 -.13625 22.681 7.418)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34703 -.552 0 20.913 7.382)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDcf" cx="0" cy="0" r="1" gradientTransform="matrix(-.0033 -.21081 .2534 -.00397 20.79 7.476)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDch" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 9.996 9.248) scale(2.08432 3.40774)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="svgIDci" cx="0" cy="0" r="1" gradientTransform="matrix(-.08997 .5848 -1.25817 -.19356 21.936 4.406)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="svgIDa" width="6.674" height="7.174" x="5.589" y="3.24" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDp" width="7.308" height="11.757" x="9.296" y="18.276" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.121569 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDq" width="5.615" height="11.172" x="10.355" y="17.769" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".25"/></filter><filter id="svgIDv" width="5.896" height="7.11" x="2.751" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDx" width="5.996" height="6.96" x="9.267" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.105882 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDz" width="3.592" height="3.267" x="11.31" y="11.197" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".2"/></filter><filter id="svgIDB" width="8.805" height="9.609" x="4.665" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDI" width="2.793" height="3.034" x="3.321" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".2"/></filter><filter id="svgIDL" width="1.527" height="1.377" x="6.109" y="6.949" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDN" width="1.377" height="1.627" x="10.177" y="6.699" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDQ" width="1.919" height="1.919" x="9.906" y="6.678" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".25"/></filter><filter id="svgIDS" width="1.419" height="1.419" x="6.095" y="6.928" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".125"/></filter><filter id="svgIDac" width="1.803" height="2.147" x="7.83" y="6.922" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".25"/></filter><filter id="svgIDad" width=".903" height="1.247" x="8.35" y="7.312" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".025"/></filter><filter id="svgIDai" width="1.813" height=".882" x="7.895" y="8.528" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".05"/></filter><filter id="svgIDak" width="1.398" height=".55" x="9.089" y="7.037" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDal" width="1.398" height=".55" x="7.114" y="7.037" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDam" width="1.164" height=".581" x="7.172" y="6.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDan" width="1.164" height=".581" x="9.489" y="6.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDap" width=".45" height=".412" x="9.363" y="7.137" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".05"/></filter><filter id="svgIDar" width=".611" height=".62" x="9.665" y="7.112" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".1"/></filter><filter id="svgIDau" width=".65" height=".673" x="7.764" y="7.085" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".1"/></filter><filter id="svgIDaw" width=".504" height=".415" x="7.499" y="7.134" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".05"/></filter><filter id="svgIDay" width="3.915" height="2.559" x="7.273" y="4.19" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feGaussianBlur result="effect2_foregroundBlur_4002_707" stdDeviation=".05"/></filter><filter id="svgIDaB" width=".833" height="1.331" x="7.264" y="4.539" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".1"/></filter><filter id="svgIDaD" width="2.608" height="1.301" x="8.623" y="5.128" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".125"/></filter><filter id="svgIDaE" width="1.73" height="2.911" x="6.683" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDaF" width="1.73" height="2.911" x="9.394" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDaG" width="4.792" height="2.36" x="6.658" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDaI" width="6.674" height="7.174" x="18.634" y="3.24" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDaX" width="7.308" height="11.757" x="22.341" y="18.276" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.121569 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDaY" width="5.615" height="11.172" x="23.401" y="17.769" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".25"/></filter><filter id="svgIDbd" width="5.896" height="7.11" x="15.796" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.176471 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDbf" width="5.996" height="6.96" x="22.312" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.105882 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDbh" width="3.465" height="3.08" x="24.481" y="11.384" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".2"/></filter><filter id="svgIDbj" width="8.805" height="9.609" x="17.71" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDbq" width="2.793" height="3.034" x="16.366" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".2"/></filter><filter id="svgIDbt" width="1.527" height="1.377" x="19.153" y="6.949" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDbv" width="1.377" height="1.627" x="23.223" y="6.699" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDby" width="1.919" height="1.919" x="22.951" y="6.678" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".25"/></filter><filter id="svgIDbA" width="1.419" height="1.419" x="19.14" y="6.928" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".125"/></filter><filter id="svgIDbK" width="1.803" height="2.147" x="20.875" y="6.922" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".25"/></filter><filter id="svgIDbL" width=".903" height="1.247" x="21.395" y="7.312" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".025"/></filter><filter id="svgIDbQ" width="1.813" height=".882" x="20.94" y="8.528" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".05"/></filter><filter id="svgIDbS" width="1.398" height=".55" x="22.135" y="7.037" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDbT" width="1.398" height=".55" x="20.159" y="7.037" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDbU" width="1.164" height=".581" x="20.217" y="6.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDbV" width="1.164" height=".581" x="22.534" y="6.314" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/></filter><filter id="svgIDbX" width=".45" height=".412" x="22.408" y="7.137" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".05"/></filter><filter id="svgIDbZ" width=".611" height=".62" x="22.71" y="7.112" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".1"/></filter><filter id="svgIDcc" width=".65" height=".673" x="20.81" y="7.085" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".1"/></filter><filter id="svgIDce" width=".504" height=".415" x="20.544" y="7.134" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".05"/></filter><filter id="svgIDcg" width="3.915" height="2.559" x="20.318" y="4.19" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feGaussianBlur result="effect2_foregroundBlur_4002_707" stdDeviation=".05"/></filter><filter id="svgIDcj" width=".833" height="1.331" x="20.309" y="4.539" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".1"/></filter><filter id="svgIDcl" width="2.608" height="1.301" x="21.668" y="5.128" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_707" stdDeviation=".125"/></filter><filter id="svgIDcm" width="1.73" height="2.911" x="19.728" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDcn" width="1.73" height="2.911" x="22.439" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><filter id="svgIDco" width="4.792" height="2.36" x="19.703" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_707"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_707" result="effect2_innerShadow_4002_707"/></filter><linearGradient id="svgIDb" x1="10.808" x2="7.898" y1="4.664" y2="10.055" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="svgIDn" x1="5.915" x2="8.034" y1="24.13" y2="24.269" gradientUnits="userSpaceOnUse"><stop class="lenvnubyg"/><stop offset="1" class="jufkgjxmt"/></linearGradient><linearGradient id="svgIDo" x1="5.807" x2="6.354" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="vnco_-oam"/><stop offset="1" class="ily885bgj"/></linearGradient><linearGradient id="svgIDD" x1="5.752" x2="6.341" y1="18.036" y2="18.022" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDJ" x1="5.736" x2="11.87" y1="9.695" y2="9.695" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDK" x1="5.721" x2="11.883" y1="9.682" y2="9.682" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDM" x1="6.109" x2="7.374" y1="7.675" y2="7.675" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="svgIDaf" x1="8.4" x2="8.801" y1="8.207" y2="8.207" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="svgIDag" x1="8.801" x2="8.801" y1="8.549" y2="8.288" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="svgIDaj" x1="8.346" x2="8.543" y1="9.152" y2="8.847" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="svgIDas" x1="10.067" x2="9.933" y1="7.406" y2="7.488" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDav" x1="8.185" x2="8.051" y1="7.405" y2="7.487" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDaC" x1="7.564" x2="7.797" y1="4.986" y2="5.531" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="svgIDaH" x1="10.697" x2="7.198" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaJ" x1="23.853" x2="20.942" y1="4.664" y2="10.055" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="svgIDaV" x1="18.96" x2="21.079" y1="24.13" y2="24.269" gradientUnits="userSpaceOnUse"><stop class="lenvnubyg"/><stop offset="1" class="jufkgjxmt"/></linearGradient><linearGradient id="svgIDaW" x1="18.852" x2="19.399" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="vnco_-oam"/><stop offset="1" class="ily885bgj"/></linearGradient><linearGradient id="svgIDbl" x1="18.797" x2="19.386" y1="18.036" y2="18.022" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDbr" x1="18.78" x2="24.915" y1="9.695" y2="9.695" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDbs" x1="18.766" x2="24.928" y1="9.682" y2="9.682" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDbu" x1="19.153" x2="20.419" y1="7.675" y2="7.675" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="svgIDbN" x1="21.445" x2="21.846" y1="8.207" y2="8.207" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="svgIDbO" x1="21.846" x2="21.846" y1="8.549" y2="8.288" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="svgIDbR" x1="21.391" x2="21.588" y1="9.152" y2="8.847" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="svgIDca" x1="23.113" x2="22.978" y1="7.406" y2="7.488" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDcd" x1="21.23" x2="21.096" y1="7.405" y2="7.487" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDck" x1="20.609" x2="20.842" y1="4.986" y2="5.531" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="svgIDcp" x1="23.743" x2="20.243" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-bunny-ears-dark" /></template>
<style>
.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a9009k51m {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M23.91 8.097a.46.46 0 1 0 0-.919a.46.46 0 0 0 0 .919Z");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.akziahbxg {
  d: path("M21.26 7.514c0-.123-.1-.205-.127-.23l-.123.12l.075.154l.175-.044Z");
}

.arrvtbcvm {
  d: path("M28.675 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.aufaspb6t {
  d: path("M6.805 8.097a.46.46 0 1 0 0-.919a.46.46 0 0 0 0 .919Z");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.bexy-42mj {
  d: path("M9.735 7.178a.382.382 0 0 1 .368.482h-.737a.383.383 0 0 1 .37-.482Z");
}

.bkq2_fbzi {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m7.348 6.877l-.002.001a.115.115 0 0 1-.118-.196l.002-.002l.004-.002l.014-.008l.05-.025a1.4 1.4 0 0 1 .175-.069a1.2 1.2 0 0 1 .568-.047a.115.115 0 0 1-.04.226a.971.971 0 0 0-.459.04a1.17 1.17 0 0 0-.185.077l-.01.005Z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.btd7yfb7z {
  d: path("M21.588 4.305c-.485-.107-.92.377-.97.556c.45 1.516 1.588 1.433 2.712 1.308c.673-.074.746.232.803.38c0-1.682-1.43-1.998-2.533-2.241l-.012-.003Z");
}

.bv3t6_blq {
  fill: var(--svg-color--000, #000);
  d: path("M8.085 7.56a.218.218 0 0 0-.218-.219a.218.218 0 0 0-.195.32h.387a.217.217 0 0 0 .026-.1Z");
}

.c6t9q9t0p {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.8 8.883c-.222 0-.431-.054-.607-.147c-.06-.032-.125.038-.087.093a.826.826 0 0 0 1.39 0c.038-.058-.027-.125-.087-.093a1.288 1.288 0 0 1-.608.147Z");
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

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneei5bfx {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m8.633 7.542l-.292.727a.23.23 0 0 0 .222.3H8.9a.231.231 0 0 0 .222-.3l-.227-.727c-.049-.16-.211-.16-.262 0Z");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dc77xq39a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.006 11.91l1.847 1.027c.193.1.578.44.569 1.002");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.duap00bnv {
  d: path("M23.12 7.51a.36.36 0 0 0-.098-.198l-.112.122l.05.098l.16-.022Z");
}

.dv5g3pabb {
  fill: var(--svg-color--442a2e, #442A2E);
  d: path("m25.169 18.276l-2.828.954l4.334 9.27a2.64 2.64 0 0 0 2.398 1.533c.121 0 .206-.12.166-.234l-4.07-11.523Z");
}

.e-189exfc {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M18.96 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.129-1.14v-5.566Z");
}

.e-c-ph2vh {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.273c.222.71.522 1.166.645 1.305l.632-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0rhdacll {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M8.543 4.305c-.485-.107-.92.377-.97.556c.45 1.516 1.588 1.433 2.712 1.308c.672-.074.745.232.803.38c0-1.682-1.43-1.998-2.533-2.241l-.012-.003Z");
}

.e4l_esb9l {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.981 3.273c.222.71.522 1.166.645 1.305l.633-.242c-.013-.183-.096-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.eueah-bko {
  d: path("m8.637 7.483l-.227.727a.23.23 0 0 0 .223.3h.336c.158 0 .27-.152.223-.3l-.227-.727c-.05-.16-.276-.16-.328 0Z");
}

.eufyi6bln {
  d: path("M22.752 7.26c.027.035-.03.08-.095.128c-.064.048-.112.082-.139.046c-.027-.037.003-.105.068-.153c.064-.048.138-.058.166-.022Z");
}

.ev6-__b2a {
  stop-color: var(--svg-color--5c4a49, #5C4A49);
}

.f5qs1xbvv {
  cx: 18.559px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--2d151b, #2D151B);
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fjru2dbrb {
  cx: 20.796px;
  cy: 7.341px;
  rx: 0.166px;
  ry: 0.084px;
}

.fo8l5tbiu {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m22.875 5.85l-.61.111a.294.294 0 1 1-.053-.583h1.002c.592 0 .788.596.812.8a1.346 1.346 0 0 0-1.15-.329Z");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1-cakgjb {
  d: path("m20.928 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gk4kp-bki {
  d: path("M20.912 7.178a.382.382 0 0 0-.368.482h.737a.384.384 0 0 0-.37-.482Z");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gx9n5e2by {
  d: path("M22.364 9.992c.23.043.451.113.66.208l-.927 1.57a.25.25 0 0 1-.435.005l-.979-1.593c.17-.074.347-.133.531-.173l1.15-.017Z");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hbrsypbww {
  d: path("M7.867 7.178a.382.382 0 0 0-.368.482h.737a.384.384 0 0 0-.37-.482Z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hj3gllh6o {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.917c-.088.073-.193.29.094.57a70.94 70.94 0 0 0 1.555 1.415");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hsda0o_vl {
  d: path("M23.91 8.097a.46.46 0 1 0 0-.919a.46.46 0 0 0 0 .919Z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i2k_4ucjp {
  d: path("M8.215 7.514c0-.123-.1-.205-.127-.23l-.124.12l.076.154l.175-.044Z");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.i8vat4bhf {
  fill: var(--svg-color--000, #000);
  d: path("M9.516 7.56a.22.22 0 0 1 .22-.219a.218.218 0 0 1 .193.32h-.386a.198.198 0 0 1-.027-.1Z");
}

.iib6ombtc {
  d: path("M19.85 8.097a.46.46 0 1 0 0-.919a.46.46 0 0 0 0 .919Z");
}

.ij6e_flvx {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M8.8 8.883c-.222 0-.431-.054-.607-.147c-.06-.032-.125.038-.087.093a.826.826 0 0 0 1.39 0c.038-.058-.027-.125-.087-.093a1.288 1.288 0 0 1-.608.147Z");
}

.iks-j-9-l {
  stop-color: var(--svg-color--382032, #382032);
}

.ily885bgj {
  stop-color: var(--svg-color--55423e, #55423E);
  stop-opacity: 0;
}

.ingmib41c {
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.izaac2bev {
  stop-color: var(--svg-color--6a5654, #6A5654);
  stop-opacity: 0;
}

.j_f9hxb4x {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.817 3.273c-.222.71-.523 1.166-.645 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.211.086.356.403.079 1.29Z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jufkgjxmt {
  stop-color: var(--svg-color--533a3b, #533A3B);
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kibsqob-j {
  stop-color: var(--svg-color--6a5654, #6A5654);
}

.kr_eiac3t {
  r: 0.766px;
}

.kr3uvebrb {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m8.637 7.483l-.227.727a.23.23 0 0 0 .223.3h.336c.158 0 .27-.152.223-.3l-.227-.727c-.05-.16-.276-.16-.328 0Z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kt4yl3aye {
  fill: var(--svg-color--432a2f, #432A2F);
  d: path("M9.369 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.09.308Z");
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lenvnubyg {
  stop-color: var(--svg-color--3d2728, #3D2728);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.linjvvhnq {
  fill: var(--svg-color--000, #000);
  d: path("M21.13 7.56a.218.218 0 0 0-.218-.219a.218.218 0 0 0-.194.32h.387a.217.217 0 0 0 .026-.1Z");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lrjaftbst {
  fill: var(--svg-color--000, #000);
  d: path("M22.562 7.56c0-.121.097-.219.218-.219a.218.218 0 0 1 .195.32h-.387a.197.197 0 0 1-.026-.1Z");
}

.lzae809fx {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m9.83 5.85l-.61.111a.294.294 0 1 1-.053-.583h1.001c.592 0 .788.596.812.8a1.346 1.346 0 0 0-1.15-.329Z");
}

.m13u431kg {
  d: path("m5.915 18.183l3.154 1.125l-1.22 9.141a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V18.183Z");
}

.m5z9y92ou {
  d: path("M9.706 7.26c.027.035-.03.08-.094.128s-.112.082-.14.046c-.027-.037.004-.105.068-.153c.065-.048.139-.058.166-.022Z");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m8w64fj6m {
  d: path("M10.866 8.097a.46.46 0 1 0 0-.919a.46.46 0 0 0 0 .919Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mddk40bcp {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.273c-.222.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29Z");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mtb7t9jlr {
  stop-color: var(--svg-color--4c3534, #4C3534);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n_n7ypvgo {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M21.588 4.305c-.485-.107-.92.377-.97.556c.45 1.516 1.588 1.433 2.712 1.308c.673-.074.746.232.803.38c0-1.682-1.43-1.998-2.533-2.241l-.012-.003Z");
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.n9y5xgysv {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m21.682 7.483l-.227.727a.23.23 0 0 0 .223.3h.336c.158 0 .27-.152.223-.3l-.227-.727c-.05-.16-.277-.16-.328 0Z");
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nhtv2g6tr {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M19.85 8.097a.46.46 0 1 0 0-.919a.46.46 0 0 0 0 .919Z");
}

.nnhpnuu4a {
  d: path("M8.543 4.305c-.485-.107-.92.377-.97.556c.45 1.516 1.588 1.433 2.712 1.308c.672-.074.745.232.803.38c0-1.682-1.43-1.998-2.533-2.241l-.012-.003Z");
}

.ntd7jh7ht {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.778 7.062a.597.597 0 0 0-.58.453a.117.117 0 0 0 .115.146h.955a.1.1 0 0 0 .097-.117a.6.6 0 0 0-.587-.482Z");
}

.nvt9xwzxq {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.869 7.062c.28 0 .515.192.58.453a.117.117 0 0 1-.115.146h-.955a.098.098 0 0 1-.097-.117a.598.598 0 0 1 .587-.482Z");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o4iu37bjz {
  d: path("M23.91 8.326a.688.688 0 1 0 0-1.377a.688.688 0 0 0 0 1.377Z");
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7s685biz {
  d: path("M8.953 9.682Z");
}

.o9p0hdcko {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.706 7.26c.027.035-.03.08-.094.128s-.112.082-.14.046c-.027-.037.004-.105.068-.153c.065-.048.139-.058.166-.022Z");
}

.oaoygtbmw {
  d: path("M9.319 9.992c.23.043.451.113.659.208l-.926 1.57a.25.25 0 0 1-.435.005l-.98-1.593c.17-.074.348-.133.532-.173l1.15-.017Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ookmcab6n {
  cx: 7.751px;
  cy: 7.341px;
  rx: 0.166px;
  ry: 0.084px;
}

.oth45pbbt {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M21.846 8.883c-.223 0-.432-.054-.608-.147c-.06-.032-.125.038-.087.093a.826.826 0 0 0 1.39 0c.038-.058-.027-.125-.087-.093a1.288 1.288 0 0 1-.608.147Z");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ouz5otbck {
  d: path("M10.866 8.326a.688.688 0 1 0 0-1.377a.688.688 0 0 0 0 1.377Z");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkgup_r3x {
  d: path("M11.874 8.24a1.401 1.401 0 0 0 .024-1.169h.002a1.364 1.364 0 0 0-.12-.219h-.001a1.386 1.386 0 0 1-.225-.758v-.005a1.41 1.41 0 0 0-1.411-1.41a.23.23 0 0 1-.195-.1a1.414 1.414 0 0 0-2.294 0a.242.242 0 0 1-.195.1h-.036a1.411 1.411 0 0 0-1.375 1.41v.005c0 .268-.078.532-.225.757l-.001.002a1.411 1.411 0 0 0-.094 1.388a.22.22 0 0 1 0 .194a1.374 1.374 0 0 0 1.238 1.978h3.67a1.374 1.374 0 0 0 1.238-1.978a.22.22 0 0 1 0-.194ZM6.63 7.099h-.005l.513 1.007c.052 1.199.52 0 1.663 0s1.64 1.334 1.694.136l.485-1.368c-.023-.532-.408-.57-.486-.57H9.117a1.652 1.652 0 0 1-1.364-.715a.113.113 0 0 0-.197.021l-.035.083a.986.986 0 0 1-.553.546c-.101.052-.338.21-.347.615l.005.131l.004.114Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppzi198mm {
  d: path("M8.811 9.682h-.017c.043 0 .082 0 .125.005c-.035-.005-.073-.005-.108-.005Z");
}

.pqc0jpzvo {
  cx: 7.751px;
  cy: 7.341px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.166px;
  ry: 0.084px;
}

.q0yhywtwv {
  d: path("M22.78 7.178a.382.382 0 0 1 .368.482h-.738a.383.383 0 0 1 .37-.482Z");
}

.q7uwbs60e {
  d: path("M18.96 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.129-1.14v-5.566Z");
}

.qday-ub6b {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.846 8.883c-.223 0-.432-.054-.608-.147c-.06-.032-.125.038-.087.093a.826.826 0 0 0 1.39 0c.038-.058-.027-.125-.087-.093a1.288 1.288 0 0 1-.608.147Z");
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qr08jwbig {
  fill: var(--svg-color--655251, #655251);
  d: path("m23.9 18.571l.824-.302l3.792 10.172h-.758L23.9 18.57Z");
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

.rk548sxih {
  d: path("m18.96 18.183l3.154 1.125l-1.22 9.141a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V18.183Z");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rsfgarwma {
  stop-color: var(--svg-color--5c4a49, #5C4A49);
  stop-opacity: 0;
}

.ru-mspmfv {
  stroke: var(--svg-color--5c4a49, #5C4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.986 13.917c-.089.073-.194.29.093.57a70.98 70.98 0 0 0 1.555 1.415");
}

.rvhaf89mo {
  fill: var(--svg-color--462f33, #462F33);
  fill-rule: evenodd;
  d: path("M21.44 10.716a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.rxrgjio9j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M20.61 4.84c.01.103.1.494.232.73");
}

.s22h3gbmb {
  d: path("M24.093 5.75c.019.097-.101.145-.167.071c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.s7_ij4e9o {
  d: path("M9.369 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.09.308Z");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.s9yxi39gy {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M5.915 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.129-1.14v-5.566Z");
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sednhij2q {
  fill: var(--svg-color--432a2f, #432A2F);
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.smqp5cbjs {
  d: path("M19.842 8.326a.688.688 0 1 0 0-1.377a.688.688 0 0 0 0 1.377Z");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.su9i6n-7v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.752 7.26c.027.035-.03.08-.095.128c-.064.048-.112.082-.139.046c-.027-.037.003-.105.068-.153c.064-.048.138-.058.166-.022Z");
}

.sy0zbq_3i {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M6.805 8.097a.46.46 0 1 0 0-.919a.46.46 0 0 0 0 .919Z");
}

.t3yukht3a {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m20.393 6.877l-.002.001a.115.115 0 0 1-.118-.196l.002-.002l.004-.002l.014-.008l.05-.025a1.3 1.3 0 0 1 .175-.069a1.2 1.2 0 0 1 .568-.047a.115.115 0 0 1-.04.226a.97.97 0 0 0-.458.04a1.172 1.172 0 0 0-.186.077l-.01.005Z");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t9gn0gubf {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.824 7.062c.279 0 .515.192.58.453a.117.117 0 0 1-.115.146h-.955a.098.098 0 0 1-.097-.117a.598.598 0 0 1 .587-.482Z");
}

.ti3edsf0r {
  d: path("m21.682 7.483l-.227.727a.23.23 0 0 0 .223.3h.336c.158 0 .27-.152.223-.3l-.227-.727c-.05-.16-.277-.16-.328 0Z");
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tkqj2jbsv {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.823 7.062a.597.597 0 0 0-.58.453a.117.117 0 0 0 .115.146h.955a.1.1 0 0 0 .097-.117a.6.6 0 0 0-.587-.482Z");
}

.tn_6-_-2a {
  d: path("M19.67 7.097h.005l-.004-.113l-.004-.131c.008-.406.245-.563.346-.615a.302.302 0 0 0 .022-.009l.022-.009a.986.986 0 0 0 .509-.528l.035-.083a.113.113 0 0 1 .197-.022c.307.45.82.716 1.365.716h1.377c.077 0 .463.038.486.57l-.051 1.314c-.053 1.2-.989 2.004-2.132 2.004c-1.142 0-2.078-.805-2.131-2.004l-.042-1.09Z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u0gzasb1f {
  stop-color: var(--svg-color--231011, #231011);
}

.u7lq--uob {
  d: path("M6.625 7.097h.005l-.004-.113l-.005-.131c.009-.406.246-.563.347-.615a.301.301 0 0 0 .022-.009l.022-.009a.986.986 0 0 0 .508-.528l.036-.083a.113.113 0 0 1 .197-.022c.307.45.82.716 1.364.716h1.377c.077 0 .463.038.486.57l-.05 1.314c-.053 1.2-.99 2.004-2.132 2.004c-1.143 0-2.079-.805-2.132-2.004l-.041-1.09Z");
}

.u93mv04rn {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m10.397 6.682l-.059.098l.059-.098a.115.115 0 0 1-.118.196h-.002a.454.454 0 0 0-.048-.026a1.172 1.172 0 0 0-.147-.057a.97.97 0 0 0-.458-.04a.115.115 0 1 1-.04-.226a1.2 1.2 0 0 1 .568.047a1.397 1.397 0 0 1 .225.094l.014.008l.004.002l.001.001h.001Z");
}

.ubd-76htt {
  d: path("M11.048 5.75c.018.097-.102.145-.167.071c-.453-.513-1.132-1.01-2.023-1.01c-.838 0-1.553.532-2.033 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.uelhvmb6u {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M10.866 8.097a.46.46 0 1 0 0-.919a.46.46 0 0 0 0 .919Z");
}

.uwuyphubg {
  cx: 20.796px;
  cy: 7.341px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.166px;
  ry: 0.084px;
}

.v2e773bpd {
  fill: var(--svg-color--272528, #272528);
  d: path("M21.358 7.394c-.114-.2-.287-.357-.658-.357a.709.709 0 0 0-.459.157c-.115.093-.1.212-.01.257l.237.136c.28-.09.587-.103.89-.193Z");
}

.v2km0iban {
  cx: 5.514px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--2d151b, #2D151B);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vnco_-oam {
  stop-color: var(--svg-color--55423e, #55423E);
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vximj4nkt {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m21.678 7.542l-.292.727a.23.23 0 0 0 .222.3h.337a.233.233 0 0 0 .223-.3l-.228-.727c-.049-.16-.21-.16-.262 0Z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w1_fhgbib {
  d: path("M6.797 8.326a.688.688 0 1 0 0-1.377a.688.688 0 0 0 0 1.377Z");
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wp-jxgbtg {
  d: path("M15.63 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234l-.564-1.607Z");
}

.wta2hpbbu {
  fill: var(--svg-color--442a2e, #442A2E);
  d: path("m12.124 18.276l-2.828.954l4.334 9.27a2.64 2.64 0 0 0 2.397 1.533c.122 0 .207-.12.167-.234l-4.07-11.523Z");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xbx983bqi {
  d: path("m7.883 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
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

.xm1uw9wfi {
  d: path("M10.075 7.51a.36.36 0 0 0-.099-.198l-.111.122l.05.098l.16-.022Z");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y03ns2b1m {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M22.335 7.394c.113-.2.286-.357.657-.357a.71.71 0 0 1 .459.157c.115.093.1.212.01.257l-.237.136c-.28-.09-.587-.103-.89-.193Z");
}

.yd4xnabcc {
  d: path("M24.92 8.24c.09-.185.138-.393.138-.61c0-.2-.041-.387-.115-.558h.002a1.364 1.364 0 0 0-.12-.22h-.001a1.386 1.386 0 0 1-.225-.758v-.005a1.41 1.41 0 0 0-1.411-1.41a.23.23 0 0 1-.195-.1a1.414 1.414 0 0 0-2.294 0a.242.242 0 0 1-.195.1h-.037a1.411 1.411 0 0 0-1.374 1.41v.005c0 .268-.078.532-.225.757l-.001.002a1.412 1.412 0 0 0-.095 1.388a.22.22 0 0 1 0 .194a1.374 1.374 0 0 0 1.238 1.978h3.671a1.374 1.374 0 0 0 1.238-1.978a.22.22 0 0 1 0-.194Zm-5.245-1.142h-.005l.512 1.007c.053 1.199.521 0 1.664 0c1.142 0 1.64 1.334 1.694.136l.485-1.368c-.023-.532-.409-.57-.485-.57h-1.378a1.652 1.652 0 0 1-1.364-.715a.113.113 0 0 0-.197.021l-.035.083a.986.986 0 0 1-.531.537l-.022.009c-.101.052-.338.21-.347.615l.005.131l.004.114Z");
}

.ydfbc88-u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.564 4.84c.01.103.1.494.233.73");
}

.yrxal2b8w {
  stop-color: var(--svg-color--4c3735, #4C3735);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxaejacmd {
  d: path("M21.998 9.682Z");
}

.z_-rptbza {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m11.835 11.722l1.972 1.215c.194.1.579.44.57 1.002");
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z7ij1iwfj {
  fill: var(--svg-color--272528, #272528);
  d: path("M8.313 7.394c-.114-.2-.286-.357-.658-.357a.709.709 0 0 0-.459.157c-.115.093-.1.212-.01.257l.237.136c.28-.09.588-.103.89-.193Z");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zj5_ndbyi {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M9.29 7.394c.113-.2.286-.357.657-.357a.71.71 0 0 1 .459.157c.115.093.1.212.01.257l-.237.136c-.28-.09-.588-.103-.89-.193Z");
}

.zkik3tf0n {
  d: path("M5.915 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.129-1.14v-5.566Z");
}

.zn9l18bel {
  fill: var(--svg-color--655251, #655251);
  d: path("m10.855 18.571l.823-.302L15.47 28.44h-.758l-3.857-9.87Z");
}

.zndunbc5i {
  d: path("M21.857 9.682h-.017c.042 0 .08 0 .124.005c-.034-.005-.073-.005-.107-.005Z");
}

.zu171j-5k {
  fill: var(--svg-color--462f33, #462F33);
  fill-rule: evenodd;
  d: path("M8.395 10.716a.8.8 0 0 1-.307 1.088L4.56 13.782a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.856-2.148.347-2.917l3.575-2.015a.8.8 0 0 1 1.088.308Z");
}

.zu4ctv27h {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m23.442 6.682l-.059.098l.06-.098a.115.115 0 0 1-.119.196h-.002a.454.454 0 0 0-.048-.026a1.172 1.172 0 0 0-.146-.057a.971.971 0 0 0-.459-.04a.115.115 0 0 1-.04-.226a1.2 1.2 0 0 1 .568.047a1.406 1.406 0 0 1 .225.094l.014.008l.004.002l.001.001h.001Z");
}

</style>
