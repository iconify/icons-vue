<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#igfxzXb)"><path fill="url(#iEYU9ps)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#igVGtsd)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#iWWx1Hb)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#iSNwavd)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#iNc9aVb)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#isrRRAe)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#iVTY8qd)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#iecNzso)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#iaui8pb)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#iCG9Prb)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#i1ZCxNq)" clip-rule="evenodd" class="drln0hs-j"/><path fill="url(#injd4Pb)" clip-rule="evenodd" class="drln0hs-j"/></g><g filter="url(#iEvS6Jd)"><path class="kf5ydzbkw"/><path fill="url(#ijkmK3c)" class="hw6w5_j-k"/></g><path fill="url(#inuVhoc)" class="zv5c_9bhk"/><path fill="url(#iR1RITc)" class="zv5c_9bhk"/><path fill="url(#ikfrscc)" class="eci3jacbw"/><path fill="url(#iSmH8Cd)" class="eci3jacbw"/><path fill="url(#iANN6AD)" class="ksylej4ab"/><path fill="url(#il9oWTc)" class="l2j9uceik"/><path fill="url(#iQN7nye)" class="l2j9uceik"/><path fill="url(#i0g9ELd)" class="l2j9uceik"/><path fill="url(#i4BU8qd)" class="l2j9uceik"/><path fill="url(#iDwn6Mc)" class="fw8nvig5g"/><path fill="url(#i37Jjkd)" class="fw8nvig5g"/><path fill="url(#ivW6UiV)" class="fw8nvig5g"/><path fill="url(#i0lSTRC)" class="jgezf_b9n"/><path fill="url(#i6bXNec)" class="jgezf_b9n"/><path fill="url(#iGEAApb)" class="juej_y2lu"/><path fill="url(#i4yiwcb)" class="juej_y2lu"/><path fill="url(#iwjIGlc)" class="juej_y2lu"/><g filter="url(#ihUze6S)"><path stroke="url(#iX2xRob)" class="b47p23b5p"/></g><path fill="url(#i3DJOYb)" class="j5o0fgbjo"/><path fill="url(#irvgCge)" class="j5o0fgbjo"/><path fill="url(#iAK3bOb)" class="j5o0fgbjo"/><path fill="url(#iV0EZyd)" class="j5o0fgbjo"/><path fill="url(#ijtL0bd)" class="ywl0znmqv"/><path fill="url(#ionhrOc)" class="ywl0znmqv"/><path fill="url(#iVR9mdQ)" class="mmgungb3m"/><path fill="url(#iInrlfc)" class="mmgungb3m"/><path fill="url(#i5MbPed)" class="mmgungb3m"/><path fill="url(#icKxB2c)" class="mmgungb3m"/><g filter="url(#i9O1wad)"><path fill="url(#inmRPMW)" class="j784d2bdi"/><path fill="url(#iDv2keZ)" class="j784d2bdi"/><path fill="url(#iLyFy7b)" class="j784d2bdi"/></g><path fill="url(#irS5kGd)" class="hso2r22lu"/><path fill="url(#i0FUNoc)" class="hso2r22lu"/><path fill="url(#iGJinme)" class="hso2r22lu"/><g filter="url(#i9VT90b)"><path fill="url(#iPeBEgd)" class="y55zg8_5g"/></g><g filter="url(#iw5Ys7b)"><path fill="url(#iHHGMqb)" class="vc5ycrsvv"/><path fill="url(#ibeLfzH)" class="vc5ycrsvv"/><path fill="url(#ixpiCNb)" class="vc5ycrsvv"/><path fill="url(#iUy91Wc)" class="vc5ycrsvv"/><path fill="url(#iaVOFJc)" class="vc5ycrsvv"/></g><g filter="url(#iGWKysd)"><path stroke="url(#iJfBqLb)" class="rbncc3b0e"/></g><g filter="url(#iGWoABd)"><path stroke="url(#iUCC3YB)" class="tzt1rlcao"/></g><g filter="url(#iqZmH8d)"><path stroke="url(#izwiYxc)" class="iw_bv4b1h"/></g><path fill="url(#iuBS74d)" class="pnoelxurb"/><path fill="url(#iGyWHzc)" class="gazjkfbup"/><g filter="url(#iZwVnLc)"><path fill="url(#iuvszPd)" class="ehim89zod"/></g><path fill="url(#ihA8P1d)" class="ehim89zod"/><g filter="url(#i2nNS2c)"><path fill="url(#iU1sxue)" class="qhvbqzb-j"/><path fill="url(#i9mtuGc)" class="qhvbqzb-j"/></g><g filter="url(#iN37HXN)"><path class="hiy6f90yg"/><path fill="url(#iCmcr2i)" class="p-9serbqv"/></g><g filter="url(#ieLOsSd)"><path class="wop-hj13h"/><path fill="url(#iUCkyPd)" class="hpdx1lb1g"/></g><g filter="url(#idgfuee)"><path fill="url(#i5pSg2b)" class="q4vanwbzs"/><path fill="url(#iRyjCiK)" class="q4vanwbzs"/><path fill="url(#idFzyjb)" class="q4vanwbzs"/><path fill="url(#i8bd3Cd)" class="q4vanwbzs"/><path fill="url(#iTs7pxd)" class="q4vanwbzs"/><path fill="url(#irPzZsd)" class="q4vanwbzs"/><path fill="url(#iO1nTOb)" class="q4vanwbzs"/><path fill="url(#iLwiihb)" class="q4vanwbzs"/></g><path fill="url(#iQrtxDb)" class="q4vanwbzs"/><g filter="url(#i1IBAgc)"><path class="gdd_34a7x"/></g><g filter="url(#i62sRie)"><path class="c9yxjf9bj"/><path fill="url(#i9hZBOd)" class="jyz8ycb-j"/><path fill="url(#iIedrfd)" class="jyz8ycb-j"/><path fill="url(#iNiCzze)" class="jyz8ycb-j"/><path fill="url(#imPddeb)" class="jyz8ycb-j"/></g><path fill="url(#iDl69Lb)" class="jyz8ycb-j"/><path fill="url(#iPpWkVd)" class="jyz8ycb-j"/><path fill="url(#itvE6Md)" class="f205oymgm"/><path fill="url(#ixxTHgK)" class="f205oymgm"/><path stroke="url(#iZmAisr)" class="atw3eobwe"/><g filter="url(#iHLvvzb)"><path class="lep_k7bgf"/></g><g filter="url(#iz5LbXc)"><path class="widk3bb5d"/></g><g filter="url(#iwzZ26c)"><path class="iciipzbwt"/></g><g filter="url(#icRBGLV)"><path clip-rule="evenodd" class="lejzsuv_v"/></g><path class="tz0v4441w"/><path fill="url(#iFeQQab)" class="srsjs-bss"/><path class="u9tg-ybip"/><g filter="url(#ietpKAe)"><path class="oaur33u4f"/><path fill="url(#iJTrWNd)" class="a2d_pab0z"/></g><g filter="url(#i08Zffc)"><path fill="url(#iWz11be)" class="buvgcsbki"/></g><path class="df38u1b8u"/><path fill="url(#i5o25Ac)" class="jxfsey0xt"/><path class="m7x4l9bxw"/><g filter="url(#itjluQe)"><path fill="url(#iTAGEdX)" class="cnlaksb1g"/></g><g filter="url(#i7a9PoC)"><ellipse transform="rotate(-27.914 12.57 11.223)" class="rzie_nblj"/><ellipse fill="url(#il0veWd)" transform="rotate(-27.914 12.57 11.223)" class="rni8po62e"/></g><g filter="url(#ieHTqKb)"><path class="xllgz0bdh"/></g><g filter="url(#iGRza4b)"><path class="z_ljadcwh"/></g><g filter="url(#izHCQhj)"><path class="jtj1ghazk"/><path fill="url(#iPH5L0b)" class="jfuwbm2eo"/><path fill="url(#iaCQHdH)" class="jfuwbm2eo"/></g><g filter="url(#iBLqriz)"><path class="rf8fggaar"/><path fill="url(#i4248Qb)" class="hwm57f3mf"/><path fill="url(#iiZnfQb)" class="hwm57f3mf"/></g><g filter="url(#i8qQpyd)"><path stroke="url(#iqRAUBb)" class="f-id-gbqv"/></g><g filter="url(#ig5RdJc)"><path class="yu9--7bxz"/></g><defs><radialGradient id="igVGtsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61764 4.66662 -5.82956 -.77156 14.773 14.491)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iWWx1Hb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95103 1.9902 -2.61496 -3.87742 11.891 14.766)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iSNwavd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33821 1.75 -1.34375 -1.02756 10.124 12.158)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iNc9aVb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.466 8.01)scale(2.53345 1.78459)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="isrRRAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.40685 2.67644 -3.71532 1.95293 11.48 3.683)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iVTY8qd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47538 1.47549 -2.06197 -2.06182 21.053 5.81)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iecNzso" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.596 7.152)scale(1.96539 4.09868)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iaui8pb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.179 8.643)scale(2.97095 3.78456)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iCG9Prb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92578 -2.71278 2.14566 -.73224 19.926 8.569)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="i1ZCxNq" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -100.976 89.59)scale(1.54784 2.50795)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="injd4Pb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.295 -2.938)scale(3.88746 1.40306)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="inuVhoc" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.896)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="ikfrscc" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.569 19.687)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="i4BU8qd" cx="0" cy="0" r="1" gradientTransform="rotate(44.502 -14.576 38.534)scale(2.54126 2.34764)" gradientUnits="userSpaceOnUse"><stop class="apsa9cl1l"/><stop offset="1" class="ji3tmwq8i"/></radialGradient><radialGradient id="ivW6UiV" cx="0" cy="0" r="1" gradientTransform="rotate(127.231 1.558 11.246)scale(5.01003 5.42155)" gradientUnits="userSpaceOnUse"><stop offset=".054" class="mi2y_fs0q"/><stop offset="1" class="l1asq8nfe"/></radialGradient><radialGradient id="iGEAApb" cx="0" cy="0" r="1" gradientTransform="scale(5.21858 8.19791)rotate(90 .16 2.733)" gradientUnits="userSpaceOnUse"><stop class="vfexudb6q"/><stop offset="1" class="kohbk3btw"/></radialGradient><radialGradient id="i4yiwcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.03341 12.2744 0 15.098 24.488)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="i2_pd6bhu"/><stop offset="1" class="pe1o3malr"/></radialGradient><radialGradient id="iX2xRob" cx="0" cy="0" r="1" gradientTransform="rotate(-134.697 12.303 6.617)scale(2.35978 2.2583)" gradientUnits="userSpaceOnUse"><stop class="e_icl-3dr"/><stop offset="1" class="oafxenbwr"/></radialGradient><radialGradient id="i3DJOYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.44554 -3.83658 0 15.098 17.603)" gradientUnits="userSpaceOnUse"><stop class="pme1odblf"/><stop offset=".736" class="mp6klcbao"/></radialGradient><radialGradient id="irvgCge" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.08555 -.86564 0 13.195 17.502)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="imjn8abun"/><stop offset="1" class="abtg-6b0t"/></radialGradient><radialGradient id="iAK3bOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.875 -.82178 0 17.267 17.44)" gradientUnits="userSpaceOnUse"><stop class="rz8p-zbgp"/><stop offset="1" class="wj2f-0bky"/></radialGradient><radialGradient id="iV0EZyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.38834 -3.72123 0 15.098 18.043)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="t0lxewect"/><stop offset="1" class="ir3mfrury"/></radialGradient><radialGradient id="ijtL0bd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1394 1.4599 -1.43346 -2.10066 28.718 21.806)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="ionhrOc" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.086 21.645)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iInrlfc" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.26 12.222)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="i5MbPed" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.493)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="icKxB2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.85)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="iDv2keZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 17.242)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iPeBEgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 21.113)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="ibeLfzH" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.651)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ixpiCNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 25.07)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iUy91Wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.44)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iaVOFJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.921)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ihA8P1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.66912 -1.23185 1.39585 -.7582 9.884 13.579)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iU1sxue" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 38.188 -38.168)scale(2.79862 3.41699)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="i9mtuGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23528 0 0 .53186 20.143 10.185)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iCmcr2i" cx="0" cy="0" r="1" gradientTransform="rotate(-4.254 171.958 -257.527)scale(1.54978 1.2115)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iUCkyPd" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.186 5.966)scale(1.08087)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="i5pSg2b" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.755 7.667)scale(7.3307 9.81201)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iRyjCiK" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23171 .98202 -.68387 -1.55413 17.1 12.256)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="idFzyjb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31956 -4.02104 5.10194 1.67428 12.869 18.043)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i8bd3Cd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.81395 -9.76734 0 15.071 10.76)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="u7b8drb3e"/><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="qgb51bb1e"/></radialGradient><radialGradient id="iTs7pxd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.06857 1.38718 -2.3883 -12.16987 16.935 13.153)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="irPzZsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17792 1.44563 0 17.438 10.953)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iO1nTOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34348 1.53971 0 12.957 10.72)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iLwiihb" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 4.962 10.61)scale(3.42085 2.73725)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iQrtxDb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3156 0 0 -6.59762 20.298 12.476)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="i9hZBOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.46629 -2.09223 .6448 -.1437 15.885 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="imPddeb" cx="0" cy="0" r="1" gradientTransform="matrix(-.79779 0 0 -.22304 15.64 13.436)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iPpWkVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40355 .9636 -1.1581 -1.68686 15.468 12.827)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="itvE6Md" cx="0" cy="0" r="1" gradientTransform="rotate(159.839 6.646 6.638)scale(6.89096 6.0187)" gradientUnits="userSpaceOnUse"><stop class="pw_9rdbbc"/><stop offset="1" class="w6le0vxed"/><stop offset="1" class="c-bi66bbs"/></radialGradient><radialGradient id="ixxTHgK" cx="0" cy="0" r="1" gradientTransform="rotate(131.12 5.026 6.904)scale(.66525 2.54787)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="ri6vfobjz"/><stop offset="1" class="vslufkb1d"/></radialGradient><radialGradient id="iFeQQab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32093 0 17.316 11.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iJTrWNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23739 -.3059 .42116 -.32683 17.082 11.407)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5o25Ac" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32094 0 12.849 11.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="il0veWd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.96 -.408)scale(.50578 .60796)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPH5L0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.2918 -2.82043 1.44286 .66085 9.29 9.15)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="iaCQHdH" cx="0" cy="0" r="1" gradientTransform="rotate(-59.802 12.602 -5.525)scale(2.3393 1.25588)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="i4248Qb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.318 7.266)scale(4.98786 8.15485)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iiZnfQb" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 5.848 8.66)scale(1.41591 3.04626)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><linearGradient id="iEYU9ps" x1="19.886" x2="13.607" y1="4.815" y2="15.829" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="ijkmK3c" x1="16.901" x2="15.504" y1="26.418" y2="26.115" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iR1RITc" x1="7.199" x2="6.027" y1="26.217" y2="26.217" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iSmH8Cd" x1="23.128" x2="23.77" y1="26.302" y2="26.271" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iANN6AD" x1="23.395" x2="21.614" y1="26.334" y2="26.334" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="il9oWTc" x1="22.77" x2="18.395" y1="16.288" y2="28.798" gradientUnits="userSpaceOnUse"><stop class="p3s97ubgt"/><stop offset="1" class="uhr48tggx"/></linearGradient><linearGradient id="iQN7nye" x1="17.486" x2="17.954" y1="23.056" y2="23.142" gradientUnits="userSpaceOnUse"><stop class="n-07uqbej"/><stop offset="1" class="k5vnjbbpd"/></linearGradient><linearGradient id="i0g9ELd" x1="23.501" x2="22.829" y1="20.642" y2="20.361" gradientUnits="userSpaceOnUse"><stop offset=".258" class="e6ztocy0u"/><stop offset="1" class="tjnac7b5i"/></linearGradient><linearGradient id="iDwn6Mc" x1="8.954" x2="11.895" y1="16.809" y2="29.178" gradientUnits="userSpaceOnUse"><stop class="yhs78-b2s"/><stop offset="1" class="ou99nli7g"/></linearGradient><linearGradient id="i37Jjkd" x1="13.408" x2="12.861" y1="25.876" y2="25.986" gradientUnits="userSpaceOnUse"><stop class="tyg1xhaog"/><stop offset="1" class="wn22vh-9z"/></linearGradient><linearGradient id="i0lSTRC" x1="8.114" x2="10.395" y1="28.146" y2="26.99" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="i6bXNec" x1="9.877" x2="9.013" y1="26.166" y2="26.68" gradientUnits="userSpaceOnUse"><stop class="a9i5gdgdq"/><stop offset="1" class="qrkl270nd"/></linearGradient><linearGradient id="iwjIGlc" x1="17.86" x2="16.54" y1="22.682" y2="22.523" gradientUnits="userSpaceOnUse"><stop offset=".061" class="vm7i39ooo"/><stop offset="1" class="o7seayucp"/></linearGradient><linearGradient id="iVR9mdQ" x1="25.739" x2="25.739" y1="15.984" y2="20.041" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="inmRPMW" x1="25.933" x2="25.792" y1="16.92" y2="18.124" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iLyFy7b" x1="23.236" x2="23.363" y1="16.857" y2="17.293" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="irS5kGd" x1="26.936" x2="24.648" y1="21.427" y2="21.427" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="i0FUNoc" x1="24.466" x2="24.847" y1="21.269" y2="21.241" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="iGJinme" x1="27.084" x2="26.822" y1="21.141" y2="21.117" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="iHHGMqb" x1="27.996" x2="23.128" y1="26.674" y2="26.674" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="iJfBqLb" x1="23.742" x2="25.663" y1="24.471" y2="24.471" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iUCC3YB" x1="23.742" x2="25.663" y1="25.913" y2="25.913" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="izwiYxc" x1="23.742" x2="25.663" y1="27.343" y2="27.343" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iuBS74d" x1="7.743" x2="22.458" y1="16.855" y2="16.855" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGyWHzc" x1="7.743" x2="22.458" y1="16.823" y2="16.823" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iuvszPd" x1="8.639" x2="10.54" y1="12.021" y2="12.021" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iIedrfd" x1="14.121" x2="15.082" y1="13.294" y2="13.294" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iNiCzze" x1="15.082" x2="15.082" y1="14.018" y2="13.376" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iDl69Lb" x1="15.162" x2="15.162" y1="14.085" y2="13.943" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="iZmAisr" x1="13.993" x2="14.464" y1="15.555" y2="14.826" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iWz11be" x1="18.112" x2="17.791" y1="11.376" y2="11.574" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTAGEdX" x1="13.61" x2="13.289" y1="11.376" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqRAUBb" x1="11.9" x2="12.402" y1="4.815" y2="6.11" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><filter id="igfxzXb" width="15.622" height="16.122" x="7.396" y="2.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="iEvS6Jd" width="5.513" height="4.74" x="12.848" y="24.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="ihUze6S" width="5.221" height="5.427" x="12.487" y="15.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".1"/></filter><filter id="i9O1wad" width="6.102" height="1.228" x="22.791" y="16.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="i9VT90b" width="1.075" height="1.075" x="25.198" y="20.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2319" result="effect2_innerShadow_4002_2319"/></filter><filter id="iw5Ys7b" width="5.369" height="6.076" x="23.128" y="22.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="iGWKysd" width="2.319" height=".3" x="23.592" y="24.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".05"/></filter><filter id="iGWoABd" width="2.319" height=".3" x="23.592" y="25.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".05"/></filter><filter id="iqZmH8d" width="2.319" height=".3" x="23.592" y="27.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".05"/></filter><filter id="iZwVnLc" width="3.444" height="3.294" x="8.639" y="10.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="i2nNS2c" width="3.294" height="3.544" x="18.376" y="10.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="iN37HXN" width="3.199" height="3.199" x="18.424" y="10.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".25"/></filter><filter id="ieLOsSd" width="2.899" height="2.899" x="8.856" y="10.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".175"/></filter><filter id="idgfuee" width="10.431" height="11.383" x="9.866" y="6.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="i1IBAgc" width="2.922" height="3.745" x="13.455" y="10.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".25"/></filter><filter id="i62sRie" width="2.422" height="3.245" x="13.871" y="11.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".125"/></filter><filter id="iHLvvzb" width="3.067" height="1.316" x="16.051" y="10.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="iz5LbXc" width="3.067" height="1.316" x="11.046" y="10.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="iwzZ26c" width="2.506" height="1.112" x="11.184" y="9.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="icRBGLV" width="2.506" height="1.112" x="16.729" y="9.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/></filter><filter id="ietpKAe" width=".801" height=".708" x="16.567" y="10.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".05"/></filter><filter id="i08Zffc" width=".903" height=".926" x="17.428" y="10.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".1"/></filter><filter id="itjluQe" width="1" height="1.055" x="12.881" y="10.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".1"/></filter><filter id="i7a9PoC" width=".93" height=".716" x="12.106" y="10.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".05"/></filter><filter id="ieHTqKb" width="2.15" height=".837" x="16.842" y="9.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".075"/></filter><filter id="iGRza4b" width="2.15" height=".837" x="11.262" y="9.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".075"/></filter><filter id="izHCQhj" width="4.392" height="4.701" x="8.587" y="4.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/><feGaussianBlur result="effect2_foregroundBlur_4002_2319" stdDeviation=".2"/></filter><filter id="iBLqriz" width="8.961" height="5.907" x="11.844" y="3.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2319"/><feGaussianBlur result="effect2_foregroundBlur_4002_2319" stdDeviation=".125"/></filter><filter id="i8qQpyd" width="1.158" height="2.35" x="11.823" y="4.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".1"/></filter><filter id="ig5RdJc" width="6.543" height="3.416" x="14.504" y="5.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2319" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-singer-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a2d_pab0z {
  d: path("M17.25 11.025c.066.088-.07.194-.225.31s-.27.196-.335.11c-.065-.088.008-.252.163-.368c.154-.115.332-.139.397-.052");
}

.a9i5gdgdq {
  stop-color: var(--svg-color--55447c, #55447C);
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.abtg-6b0t {
  stop-color: var(--svg-color--8d5e60, #8D5E60);
  stop-opacity: 0;
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.apsa9cl1l {
  stop-color: var(--svg-color--7955b5, #7955B5);
}

.atw3eobwe {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.65 14.515c.414.22.907.347 1.432.347c.53 0 1.018-.127 1.432-.347a.21.21 0 0 1 .251.042c.06.063.081.163.022.254m-3.137-.296l3.095.269m-3.095-.269a.21.21 0 0 0-.252.044a.2.2 0 0 0-.02.252m.272-.296l-.231.269m3.368.027l-.042-.027m.042.027l-.042-.027m.042.027a2.028 2.028 0 0 1-3.41 0m3.368-.027a1.978 1.978 0 0 1-3.326 0m-.042.027l.042-.027m-.042.027l.042-.027");
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b47p23b5p {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.812 15.654h4.571v2.8c0 1.262-1.023 1.977-2.285 1.977s-2.286-.715-2.286-1.978z");
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.buvgcsbki {
  d: path("M18.131 11.626a.86.86 0 0 0-.236-.474l-.267.292l.12.233z");
}

.c-bi66bbs {
  stop-color: var(--svg-color--c93859, #C93859);
}

.c9yxjf9bj {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m14.69 11.562l-.543 1.74a.552.552 0 0 0 .533.716h.804a.554.554 0 0 0 .533-.716l-.544-1.74c-.116-.385-.66-.385-.782 0");
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
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

.cnlaksb1g {
  d: path("M13.681 11.638c0-.295-.24-.492-.305-.551l-.295.285l.182.37z");
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.df38u1b8u {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.635 10.554a1.43 1.43 0 0 0-1.387 1.084a.28.28 0 0 0 .274.349h2.284a.236.236 0 0 0 .232-.278a1.434 1.434 0 0 0-1.403-1.155");
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.drln0hs-j {
  fill-rule: evenodd;
  d: path("M22.437 13.375a3.3 3.3 0 0 0 .331-1.461c0-.479-.098-.927-.275-1.336h.006a3.3 3.3 0 0 0-.288-.525l-.002-.004a3.3 3.3 0 0 1-.539-1.812v-.01a3.38 3.38 0 0 0-3.377-3.378a.55.55 0 0 1-.466-.238a3.38 3.38 0 0 0-2.745-1.409c-1.13 0-2.134.56-2.745 1.409a.58.58 0 0 1-.466.238l-.087.001a3.38 3.38 0 0 0-3.29 3.376v.01c0 .643-.187 1.275-.539 1.813l-.002.004a3.38 3.38 0 0 0-.226 3.321a.53.53 0 0 1 0 .467a3.34 3.34 0 0 0-.331 1.44a3.29 3.29 0 0 0 3.294 3.294h8.784a3.29 3.29 0 0 0 3.294-3.294a3.34 3.34 0 0 0-.331-1.44a.53.53 0 0 1 0-.466m-12.55-2.736h-.012l1.227 2.411c.126 2.869 1.245 0 3.98 0s3.927 3.193 4.053.324l1.163-3.272c-.055-1.274-.979-1.364-1.163-1.364H15.84a3.95 3.95 0 0 1-3.264-1.712a.27.27 0 0 0-.473.052l-.084.198a2.36 2.36 0 0 1-1.27 1.285q-.028.012-.052.02c-.242.126-.809.502-.83 1.473l.01.313z");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e_icl-3dr {
  stop-color: var(--svg-color--aa7e79, #AA7E79);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6ztocy0u {
  stop-color: var(--svg-color--876bc0, #876BC0);
}

.eci3jacbw {
  d: path("M27.018 28.787c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.ehim89zod {
  d: path("M10.286 13.579a1.647 1.647 0 1 0 0-3.294a1.647 1.647 0 0 0 0 3.294");
}

.f-id-gbqv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.123 5.235c.024.25.24 1.184.557 1.75");
}

.f205oymgm {
  d: path("M14.096 8.33a3.9 3.9 0 0 1-1.506-1.304a.27.27 0 0 0-.467.04l-1.906 5.61h1.895l-.522 2.921l3.92-5.504h-2.02z");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.fw8nvig5g {
  d: path("M5.405 16.81h5.256a1 1 0 0 1 .983.815l2.095 11.173h-2.79l-5.88-11.529c-.086-.125-.07-.46.336-.46");
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gazjkfbup {
  d: path("M15.123 16.824h-.041c.102 0 .194 0 .297.01c-.082-.01-.174-.01-.256-.01");
}

.gdd_34a7x {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m14.68 11.704l-.7 1.74a.552.552 0 0 0 .534.716h.804a.554.554 0 0 0 .533-.716l-.544-1.74c-.116-.386-.505-.386-.627 0");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hiy6f90yg {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.023 13.03a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.199");
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

.hpdx1lb1g {
  d: path("M10.306 13.03a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.199");
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hso2r22lu {
  d: path("M25.726 26.628a.784.784 0 0 1-.782-.711l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.hw6w5_j-k {
  d: path("M12.848 24.048v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.hwm57f3mf {
  d: path("M14.465 3.957c-1.16-.256-2.2.9-2.321 1.33c1.077 3.628 3.8 3.43 6.49 3.13c1.61-.178 1.784.555 1.921.91c0-4.025-3.423-4.781-6.061-5.364z");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i2_pd6bhu {
  stop-color: var(--svg-color--623f3d, #623F3D);
  stop-opacity: 0;
}

.iciipzbwt {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m11.604 10.112l-.004.002a.275.275 0 0 1-.283-.47l.001-.001h.001l.003-.003l.01-.005a2 2 0 0 1 .152-.079c.1-.048.244-.11.42-.165a2.9 2.9 0 0 1 1.359-.112a.274.274 0 1 1-.095.54c-.409-.071-.8 0-1.098.095a3 3 0 0 0-.444.185z");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.imjn8abun {
  stop-color: var(--svg-color--8d5e60, #8D5E60);
}

.ir3mfrury {
  stop-color: var(--svg-color--9e7269, #9E7269);
}

.iw_bv4b1h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 27.265h2.02");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j5o0fgbjo {
  d: path("M12.812 15.654h4.571v2.8c0 1.262-1.023 1.977-2.285 1.977s-2.286-.715-2.286-1.978z");
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j784d2bdi {
  d: path("m28.214 16.828l-4.844-.02a.57.57 0 0 0-.58.579c0 .325.255.579.58.579l4.844.02a.57.57 0 0 0 .578-.579a.585.585 0 0 0-.578-.579");
}

.jfuwbm2eo {
  d: path("M9.893 5.802c.58-.613 1.675-.614 2.182-.523L12.48 6.6c-.26-.04-.303-.001-.497.187c-.14 1.119-1.408 1.798-2.954 2.25c-.152-1.528.11-2.437.864-3.235");
}

.jgezf_b9n {
  d: path("M7.078 28.788h3.87l-3.87-7.596z");
}

.ji3tmwq8i {
  stop-color: var(--svg-color--7955b5, #7955B5);
  stop-opacity: 0;
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jtj1ghazk {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M9.893 5.802c.58-.613 1.675-.614 2.182-.523L12.48 6.6c-.26-.04-.303-.001-.497.187c-.14 1.119-1.408 1.798-2.954 2.25c-.152-1.528.11-2.437.864-3.235");
}

.juej_y2lu {
  d: path("M15.118 17.688c-1.16 0-2.298.171-3.378.491l1.098 5.869c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.jxfsey0xt {
  d: path("M12.847 10.832a.914.914 0 0 0-.88 1.154h1.764a1 1 0 0 0 .033-.24a.92.92 0 0 0-.917-.914");
}

.jyz8ycb-j {
  d: path("m14.69 11.562l-.543 1.74a.552.552 0 0 0 .533.716h.804a.554.554 0 0 0 .533-.716l-.544-1.74c-.116-.385-.66-.385-.782 0");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k5vnjbbpd {
  stop-color: var(--svg-color--845ebf, #845EBF);
  stop-opacity: 0;
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kf5ydzbkw {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 24.048v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.kohbk3btw {
  stop-color: var(--svg-color--724a49, #724A49);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ksylej4ab {
  d: path("M23.128 28.788v-7.303l-3.52 7.303z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l1asq8nfe {
  stop-color: var(--svg-color--815eb7, #815EB7);
  stop-opacity: 0;
}

.l2j9uceik {
  d: path("m24.313 16.801l-4.779.021a1 1 0 0 0-.978.816l-2.097 11.16h3.149l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lejzsuv_v {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m18.902 9.643l-.142.236za.275.275 0 0 1-.283.471l-.004-.003l-.022-.012l-.094-.047a3 3 0 0 0-.35-.138a2.3 2.3 0 0 0-1.098-.094a.275.275 0 0 1-.095-.541a2.9 2.9 0 0 1 1.36.112a3.4 3.4 0 0 1 .571.244l.01.005l.003.002z");
}

.lep_k7bgf {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M16.251 11.349c.272-.478.685-.855 1.574-.855c.389 0 .764.107 1.098.377c.275.222.238.507.025.614l-.57.324c-.666-.215-1.404-.244-2.127-.46");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m7x4l9bxw {
  fill: var(--svg-color--000, #000);
  d: path("M13.37 11.746a.52.52 0 0 0-.524-.523a.52.52 0 0 0-.465.764h.926a.5.5 0 0 0 .063-.241");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mi2y_fs0q {
  stop-color: var(--svg-color--6c3b70, #6C3B70);
}

.mmgungb3m {
  d: path("M25.766 19.986a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.mp6klcbao {
  stop-color: var(--svg-color--9b5d70, #9B5D70);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n-07uqbej {
  stop-color: var(--svg-color--8e5280, #8E5280);
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o7seayucp {
  stop-color: var(--svg-color--8b615d, #8B615D);
  stop-opacity: 0;
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.oafxenbwr {
  stop-color: var(--svg-color--aa7e79, #AA7E79);
  stop-opacity: 0;
}

.oaur33u4f {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.25 11.025c.066.088-.07.194-.225.31s-.27.196-.335.11c-.065-.088.008-.252.163-.368c.154-.115.332-.139.397-.052");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ou99nli7g {
  stop-color: var(--svg-color--9266df, #9266DF);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p-9serbqv {
  d: path("M20.023 13.03a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.199");
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p3s97ubgt {
  stop-color: var(--svg-color--8866b4, #8866B4);
}

.pe1o3malr {
  stop-color: var(--svg-color--623f3d, #623F3D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pme1odblf {
  stop-color: var(--svg-color--995a76, #995A76);
}

.pnoelxurb {
  d: path("M15.46 16.824c.257.01.523.03.789.051c-.266-.02-.522-.04-.788-.05");
}

.pw_9rdbbc {
  stop-color: var(--svg-color--f32f73, #F32F73);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q4vanwbzs {
  d: path("M9.875 10.64h.012l-.01-.272l-.01-.313c.02-.972.587-1.348.829-1.473l.052-.021q.029-.013.053-.02c.546-.252.986-.69 1.217-1.265l.084-.198a.27.27 0 0 1 .473-.052a3.95 3.95 0 0 0 3.264 1.713h3.296c.184 0 1.108.089 1.163 1.363l-.122 3.146c-.126 2.868-2.366 4.795-5.1 4.795c-2.735 0-4.975-1.927-5.101-4.795z");
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qgb51bb1e {
  stop-color: var(--svg-color--a1578e, #A1578E);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qhvbqzb-j {
  d: path("M20.023 13.579a1.647 1.647 0 1 0 0-3.294a1.647 1.647 0 0 0 0 3.294");
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qrkl270nd {
  stop-color: var(--svg-color--55447c, #55447C);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rbncc3b0e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.393h2.02");
}

.rf8fggaar {
  fill: var(--svg-color--553836, #553836);
  d: path("M14.465 3.957c-1.16-.256-2.2.9-2.321 1.33c1.077 3.628 3.8 3.43 6.49 3.13c1.61-.178 1.784.555 1.921.91c0-4.025-3.423-4.781-6.061-5.364z");
}

.ri6vfobjz {
  stop-color: var(--svg-color--860c4f, #860C4F);
}

.rni8po62e {
  cx: 12.571px;
  cy: 11.223px;
  rx: 0.399px;
  ry: 0.202px;
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.rz8p-zbgp {
  stop-color: var(--svg-color--a0716f, #A0716F);
}

.rzie_nblj {
  cx: 12.571px;
  cy: 11.223px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.399px;
  ry: 0.202px;
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.srsjs-bss {
  d: path("M17.318 10.832a.914.914 0 0 1 .88 1.154h-1.765a.917.917 0 0 1 .884-1.154");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t0lxewect {
  stop-color: var(--svg-color--9d5e72, #9D5E72);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tjnac7b5i {
  stop-color: var(--svg-color--8263bd, #8263BD);
  stop-opacity: 0;
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tyg1xhaog {
  stop-color: var(--svg-color--6e3c78, #6E3C78);
}

.tz0v4441w {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.53 10.554c.668 0 1.233.461 1.386 1.084a.28.28 0 0 1-.274.349H16.36a.236.236 0 0 1-.233-.278a1.43 1.43 0 0 1 1.403-1.155");
}

.tzt1rlcao {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.835h2.02");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7b8drb3e {
  stop-color: var(--svg-color--9d5f7a, #9D5F7A);
  stop-opacity: 0;
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.u9tg-ybip {
  fill: var(--svg-color--000, #000);
  d: path("M16.795 11.746a.52.52 0 0 1 .523-.523a.52.52 0 0 1 .465.764h-.926a.5.5 0 0 1-.062-.241");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uhr48tggx {
  stop-color: var(--svg-color--7f54c6, #7F54C6);
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vc5ycrsvv {
  d: path("M23.128 23.674a.81.81 0 0 1 .816-.802h3.054c.745 0 1.349.589 1.349 1.315v3.514a1.11 1.11 0 0 1-1.124 1.097h-3.28a.81.81 0 0 1-.816-.802c0-.315.187-.59.458-.72a.8.8 0 0 1-.457-.721c0-.314.186-.589.457-.72a.8.8 0 0 1-.457-.72a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.72");
}

.vfexudb6q {
  stop-color: var(--svg-color--ab7e73, #AB7E73);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vm7i39ooo {
  stop-color: var(--svg-color--6f454b, #6F454B);
}

.vslufkb1d {
  stop-color: var(--svg-color--860c4f, #860C4F);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w6le0vxed {
  stop-color: var(--svg-color--bc2f50, #BC2F50);
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.widk3bb5d {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M13.913 11.349c-.271-.478-.684-.855-1.573-.855c-.39 0-.765.107-1.098.377c-.276.222-.239.507-.026.614l.57.324c.667-.215 1.404-.244 2.127-.46");
}

.wj2f-0bky {
  stop-color: var(--svg-color--a0716f, #A0716F);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wn22vh-9z {
  stop-color: var(--svg-color--825db9, #825DB9);
  stop-opacity: 0;
}

.wop-hj13h {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M10.306 13.03a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.199");
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xllgz0bdh {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.067 9.503c.33-.08 1.151-.04 1.7.352");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y55zg8_5g {
  d: path("M25.736 21.916a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.yhs78-b2s {
  stop-color: var(--svg-color--7c5aad, #7C5AAD);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yu9--7bxz {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m17.545 7.652l-1.459.269a.704.704 0 1 1-.128-1.398h2.396c1.417 0 1.886 1.429 1.944 1.917a3.22 3.22 0 0 0-2.753-.788");
}

.ywl0znmqv {
  d: path("M27.277 21.112c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.z_ljadcwh {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.187 9.503c-.33-.08-1.151-.04-1.7.352");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zv5c_9bhk {
  d: path("M7.078 28.787v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
