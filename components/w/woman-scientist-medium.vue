<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4jr7Qc)"><path fill="url(#i2urXYd)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#io40ped)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#iYQncEd)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#iG3KeRK)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#iqDkLjc)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#ihQtKTY)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#i0gWO8c)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#iPDi2VL)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#i71KKIc)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#i8lyC7d)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#it8FCnd)" clip-rule="evenodd" class="wmbnj2bxj"/><path fill="url(#iZ2rNRb)" clip-rule="evenodd" class="wmbnj2bxj"/></g><path fill="url(#iJ2Iz3d)" class="zj_pz5bwb"/><path fill="url(#ihEGoyb)" class="s3wacbc5g"/><path fill="url(#i1Nzymt)" class="s3wacbc5g"/><path fill="url(#i2jteAd)" class="c_ev0q_fe"/><path fill="url(#iOcpATb)" class="c_ev0q_fe"/><path fill="url(#iUuNqRE)" class="c_ev0q_fe"/><path fill="url(#ib6YSVT)" class="c_ev0q_fe"/><path fill="url(#if8WIAh)" class="l41d1tbgo"/><path fill="url(#in7f6ne)" class="l41d1tbgo"/><path fill="url(#iPv70Xc)" class="l41d1tbgo"/><path fill="url(#iwFsCdb)" class="l41d1tbgo"/><g filter="url(#iDmNHid)"><path fill="url(#i0jUold)" class="j_cmqr47j"/></g><g filter="url(#i4tawxb)"><path fill="url(#iWGDoWc)" class="tn6sd3bmv"/></g><g filter="url(#iKlbmHd)"><path fill="url(#iQskxRc)" class="rif685bkq"/></g><path fill="url(#iXh6y9k)" class="df3wracno"/><path fill="url(#icuB4jc)" class="df3wracno"/><path fill="url(#izI2Snf)" class="df3wracno"/><path fill="url(#iusIFhc)" class="df3wracno"/><path fill="url(#i0P8PUb)" class="df3wracno"/><path fill="url(#iMwJdHl)" class="c90z04b8d"/><path fill="url(#idz6EPb)" class="c90z04b8d"/><path fill="url(#iRxjVYg)" class="c90z04b8d"/><path fill="url(#iPoNt8M)" class="c90z04b8d"/><path fill="url(#i0RxSYg)" class="tn6sd3bmv"/><path fill="url(#iv6l9ce)" class="ykt8wq3aa"/><path fill="url(#iNVuJTd)" class="ykt8wq3aa"/><path fill="url(#iJ2Iz3d)" class="zj_pz5bwb"/><g filter="url(#iDIRuJe)"><path fill="url(#iHvHPqd)" class="ccige11qy"/><path fill="url(#iG6MZ3g)" class="ccige11qy"/></g><path fill="url(#iyajhbe)" class="qgr_41bfc"/><path fill="url(#ipzEUoc)" class="qgr_41bfc"/><path fill="url(#iw7ZvKb)" class="yvghywbvb"/><path fill="url(#iDuBnAL)" class="yvghywbvb"/><path fill="url(#iObQmbd)" class="yvghywbvb"/><g filter="url(#iT1Roid)"><rect class="c5cwb6k_s"/><rect fill="url(#ipWECic)" class="vgtum5b-w"/><rect fill="url(#iwkRopb)" class="vgtum5b-w"/><rect fill="url(#iKC24Ld)" class="vgtum5b-w"/></g><path fill="url(#ifdccjr)" class="zrc3yuv7g"/><path fill="url(#iQ0TOue)" class="zrc3yuv7g"/><path fill="url(#iBHQfvb)" class="zrc3yuv7g"/><path fill="url(#izBkzme)" class="zrc3yuv7g"/><path fill="url(#i0mpV9c)" class="f5f2c6brp"/><path fill="url(#ifqAaMG)" class="out3l1bbv"/><g filter="url(#iOUGqQc)"><path fill="url(#i5BjAbL)" class="ryd497v6k"/><path fill="url(#i8U2Vtb)" class="ryd497v6k"/><path fill="url(#iofiSVi)" class="ryd497v6k"/><path fill="url(#iVFjPrc)" class="ryd497v6k"/><path fill="url(#i4sEm2c)" class="ryd497v6k"/></g><g filter="url(#iWRUtne)"><path stroke="url(#ifMnYZs)" class="qjt16ebmg"/></g><g filter="url(#inzm1kf)"><path stroke="url(#i9Z5q9b)" class="q-4nxsbsy"/></g><g filter="url(#itxrRNb)"><path stroke="url(#iJ8ZNyc)" class="x2qgolnse"/></g><path fill="url(#ifUv6hd)" class="jsdcepb_z"/><path fill="url(#iGDvLyc)" class="wnu1izbkk"/><g filter="url(#iLlQLuc)"><path fill="url(#iBOMwbe)" class="j8t6g3bhi"/></g><path fill="url(#iYRsPkd)" class="j8t6g3bhi"/><g filter="url(#iZLZ4uc)"><path fill="url(#iqRsX1c)" class="mcniv-j4i"/><path fill="url(#itSCgnd)" class="mcniv-j4i"/></g><g filter="url(#io8oT5T)"><path class="lguxr4_am"/><path fill="url(#iVBfhTd)" class="cr9men0um"/></g><g filter="url(#ikXqb1c)"><path class="yv-i8ss1z"/><path fill="url(#icSbujB)" class="ktn4_vb9n"/></g><g filter="url(#im1xP5T)"><path fill="url(#iO7HuOb)" class="nqlop1boy"/><path fill="url(#iGV13dV)" class="nqlop1boy"/><path fill="url(#iGRsnxc)" class="nqlop1boy"/><path fill="url(#ianG50b)" class="nqlop1boy"/><path fill="url(#iCzFhac)" class="nqlop1boy"/><path fill="url(#iJvkIeb)" class="nqlop1boy"/><path fill="url(#ieLznvd)" class="nqlop1boy"/><path fill="url(#iEK4ktc)" class="nqlop1boy"/></g><path fill="url(#iaWNCHb)" class="nqlop1boy"/><g filter="url(#is9ZVPd)"><path class="be8zxackb"/></g><g filter="url(#iMVPCQP)"><path class="xngdzm8vt"/><path fill="url(#iGetc1b)" class="edg2r54vx"/><path fill="url(#iNpy8re)" class="edg2r54vx"/><path fill="url(#ihzVhAb)" class="edg2r54vx"/><path fill="url(#isCPQUb)" class="edg2r54vx"/></g><path fill="url(#ip3Aopc)" class="edg2r54vx"/><path fill="url(#iNpLCme)" class="edg2r54vx"/><path stroke="url(#iJycsAm)" class="laeihzb1c"/><g filter="url(#iUkuktd)"><path class="ea51mjonn"/></g><g filter="url(#i0sIBNe)"><path class="xzlzp1b8g"/></g><g filter="url(#itvkgad)"><path class="bef17t_3x"/></g><g filter="url(#iTxLO4c)"><path clip-rule="evenodd" class="zzyag9b7i"/></g><path class="j-r8h2jid"/><path fill="url(#i8aY3Ph)" class="lpmntqveh"/><path class="n9xbx_eri"/><g filter="url(#i8yd0Wc)"><path class="wz6su-bfc"/><path fill="url(#i8B0F7d)" class="k1ofhim6h"/></g><g filter="url(#iJUnJme)"><path fill="url(#inetsPZ)" class="b92e6t3qh"/></g><path class="ud5tgpbel"/><path fill="url(#ihtTZkc)" class="bfjdpmblm"/><path class="mhqcou54m"/><g filter="url(#iSQg82d)"><path fill="url(#iURjNoe)" class="mz6me4bgx"/></g><g filter="url(#iUdGTAc)"><ellipse transform="rotate(-27.914 12.992 9.902)" class="y7hkmkbrv"/><ellipse fill="url(#iCgpiie)" transform="rotate(-27.914 12.992 9.902)" class="c5vqwcbfw"/></g><g filter="url(#in37nue)"><path class="agmv86b0w"/></g><g filter="url(#iidTggs)"><path class="ge8573boc"/></g><g filter="url(#iFh6lGe)"><path class="ab8h_irtj"/><path fill="url(#ipz9jpb)" class="pn_ui08uz"/><path fill="url(#imjZspb)" class="pn_ui08uz"/></g><g filter="url(#iOqEGOd)"><path class="y7orfnsjv"/><path fill="url(#i4ZBdYd)" class="alzmjkbgl"/><path fill="url(#i1lR8Md)" class="alzmjkbgl"/></g><g filter="url(#ii0Ljjc)"><path stroke="url(#ieXobDb)" class="fkj5oxbba"/></g><g filter="url(#iPlF1Rb)"><path class="jsjicce4p"/></g><path fill="url(#i4zyhzc)" class="q9qyt5bec"/><g filter="url(#i1885jc)"><path clip-rule="evenodd" class="lnpdvvblo"/></g><defs><radialGradient id="io40ped" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.145 13.096)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iYQncEd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.328 13.364)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iG3KeRK" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.628 8.028)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iqDkLjc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.063 7.494)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="ihQtKTY" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 3.864 11.14)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i0gWO8c" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.684 6.715)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iPDi2VL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 22.955 9.744)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="i71KKIc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.365 7.957)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="i8lyC7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 20.178 7.31)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="it8FCnd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.304 9.707)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iZ2rNRb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 13.897 -3.685)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="ihEGoyb" cx="0" cy="0" r="1" gradientTransform="scale(3.29991 5.8125)rotate(90 .77 3.911)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="do28bmb5k"/><stop offset="1" class="egj-02bls"/></radialGradient><radialGradient id="i1Nzymt" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.261)" gradientUnits="userSpaceOnUse"><stop class="bfl4-fbqr"/><stop offset="1" class="frstvbc2m"/></radialGradient><radialGradient id="i2jteAd" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.497 14.533)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="ib6YSVT" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.355)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="if8WIAh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.23)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="in7f6ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.48)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iWGDoWc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.855)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iXh6y9k" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.636)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="icuB4jc" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.263 -.282)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="izI2Snf" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.257 14.353)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="iMwJdHl" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.057)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iRxjVYg" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.913)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="i0RxSYg" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.8 11.796)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iv6l9ce" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.824)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iHvHPqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41281 -3.18655 0 15.426 16.512)" gradientUnits="userSpaceOnUse"><stop class="ph_moylrd"/><stop offset=".632" class="gknvw6bil"/></radialGradient><radialGradient id="iG6MZ3g" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.874)" gradientUnits="userSpaceOnUse"><stop class="pgp6pr__x"/><stop offset="1" class="lehkj4qja"/></radialGradient><radialGradient id="iyajhbe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03943 1.39355 -1.36898 -2.00347 27.808 23.565)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="ipzEUoc" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.41)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iObQmbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.324)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="ipWECic" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.011)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iwkRopb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.862)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="iKC24Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.222)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="izBkzme" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.168)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="i8U2Vtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.238)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iofiSVi" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.532)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iVFjPrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.782)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i4sEm2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.134)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iYRsPkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 10.367 12.204)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iqRsX1c" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.485 11.034)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="itSCgnd" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 20.39 8.889)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iVBfhTd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 19.837 10.707)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="icSbujB" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.422 5.298)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iO7HuOb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.049 7.037)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iGV13dV" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.561 7.287)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iGRsnxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.284 16.565)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="ianG50b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.6523 -9.56528 0 15.184 9.362)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="hdogj2h5i"/><stop offset="1" class="aebydul1g"/></radialGradient><radialGradient id="iCzFhac" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.055 6.733)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iJvkIeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 17.747 9.64)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="ieLznvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.37 9.41)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iEK4ktc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 16.83 7.323)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iaWNCHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 20.541 11.127)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iGetc1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.23 11.853)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="isCPQUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 15.99 12.065)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iNpLCme" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.132 8.19)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="i8aY3Ph" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.628 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i8B0F7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.4 10.082)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihtTZkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.264 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iCgpiie" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.518 -1.28)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipz9jpb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.03 -3.686)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="imjZspb" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 11.495 6.897)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="i4ZBdYd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.839 6.791)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="i1lR8Md" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 15.656 3.04)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><linearGradient id="i2urXYd" x1="20.139" x2="14.004" y1="3.642" y2="14.403" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iJ2Iz3d" x1="8.23" x2="22.659" y1="15.241" y2="15.241" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iOcpATb" x1="11.239" x2="11.239" y1="30.355" y2="29.043" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iUuNqRE" x1="15.177" x2="14.208" y1="29.043" y2="29.043" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iPv70Xc" x1="19.74" x2="19.74" y1="30.355" y2="29.043" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iwFsCdb" x1="15.802" x2="16.505" y1="27.918" y2="27.918" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="i0jUold" x1="10.458" x2="12.677" y1="17.974" y2="24.662" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="iQskxRc" x1="20.633" x2="18.282" y1="19.025" y2="23.726" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iusIFhc" x1="18.958" x2="17.552" y1="24.043" y2="22.543" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="i0P8PUb" x1="17.146" x2="17.974" y1="18.824" y2="19.168" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="idz6EPb" x1="6.567" x2="6.567" y1="30.298" y2="29.164" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iPoNt8M" x1="8.38" x2="7.935" y1="29.332" y2="29.329" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="iNVuJTd" x1="22.753" x2="23.162" y1="27.605" y2="27.589" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="iw7ZvKb" x1="23.825" x2="26.529" y1="20.793" y2="20.793" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iDuBnAL" x1="26.529" x2="26.18" y1="20.777" y2="20.777" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="ifdccjr" x1="26.529" x2="25.177" y1="23.105" y2="23.105" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iQ0TOue" x1="26.529" x2="26.129" y1="23.253" y2="23.253" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="iBHQfvb" x1="23.696" x2="24.227" y1="23.253" y2="23.253" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="i0mpV9c" x1="24.782" x2="23.892" y1="21.746" y2="21.746" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="ifqAaMG" x1="24.782" x2="23.892" y1="23.527" y2="23.527" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="i5BjAbL" x1="27.165" x2="23.137" y1="27.995" y2="27.995" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="ifMnYZs" x1="23.754" x2="25.463" y1="26.013" y2="26.013" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i9Z5q9b" x1="23.676" x2="25.385" y1="27.318" y2="27.318" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iJ8ZNyc" x1="23.754" x2="25.463" y1="28.623" y2="28.623" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ifUv6hd" x1="8.261" x2="22.637" y1="15.222" y2="15.222" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGDvLyc" x1="8.261" x2="22.637" y1="15.191" y2="15.191" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iBOMwbe" x1="9.151" x2="11.008" y1="10.682" y2="10.682" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iNpy8re" x1="14.507" x2="15.446" y1="11.926" y2="11.926" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="ihzVhAb" x1="15.446" x2="15.446" y1="12.633" y2="12.006" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="ip3Aopc" x1="15.524" x2="15.524" y1="12.699" y2="12.56" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="iJycsAm" x1="14.382" x2="14.842" y1="14.135" y2="13.423" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="inetsPZ" x1="18.406" x2="18.092" y1="10.052" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iURjNoe" x1="14.008" x2="13.694" y1="10.052" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ieXobDb" x1="12.337" x2="12.827" y1="3.643" y2="4.908" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="i4zyhzc" x1="10.917" x2="22.177" y1="9.672" y2="9.672" gradientUnits="userSpaceOnUse"><stop class="pxdyn0bka"/><stop offset=".099" class="fy-71g_sr"/><stop offset=".374" class="fy-71g_sr"/><stop offset="1" class="t5bid5bsq"/></linearGradient><filter id="i4jr7Qc" width="15.268" height="15.768" x="7.937" y="1.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="iDmNHid" width="7.023" height="11.703" x="8.372" y="15.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".375"/></filter><filter id="i4tawxb" width="5.673" height="10.453" x="9.475" y="15.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="iKlbmHd" width="6.388" height="10.529" x="15.682" y="16.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".375"/></filter><filter id="iDIRuJe" width="4.32" height="3.6" x="13.316" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.235294 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="iT1Roid" width="4.008" height=".781" x="23.173" y="18.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="iOUGqQc" width="4.468" height="5.556" x="23.137" y="24.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="iWRUtne" width="2.097" height=".3" x="23.604" y="25.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".05"/></filter><filter id="inzm1kf" width="2.097" height=".3" x="23.526" y="27.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".05"/></filter><filter id="itxrRNb" width="2.097" height=".3" x="23.604" y="28.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".05"/></filter><filter id="iLlQLuc" width="3.368" height="3.218" x="9.151" y="8.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="iZLZ4uc" width="3.218" height="3.468" x="18.664" y="8.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="io8oT5T" width="3.148" height="3.148" x="18.699" y="9.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".25"/></filter><filter id="ikXqb1c" width="2.848" height="2.848" x="9.355" y="9.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".175"/></filter><filter id="im1xP5T" width="10.191" height="11.127" x="10.351" y="5.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="is9ZVPd" width="2.877" height="3.682" x="13.845" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".25"/></filter><filter id="iMVPCQP" width="2.377" height="3.182" x="14.257" y="9.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".125"/></filter><filter id="iUkuktd" width="3.001" height="1.285" x="16.388" y="9.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="i0sIBNe" width="3.001" height="1.285" x="11.503" y="9.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="itvkgad" width="2.453" height="1.091" x="11.638" y="7.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="iTxLO4c" width="2.453" height="1.091" x="17.055" y="7.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/></filter><filter id="i8yd0Wc" width=".787" height=".696" x="16.894" y="9.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".05"/></filter><filter id="iJUnJme" width=".891" height=".913" x="17.734" y="9.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".1"/></filter><filter id="iSQg82d" width=".986" height="1.04" x="13.291" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".1"/></filter><filter id="iUdGTAc" width=".913" height=".705" x="12.536" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".05"/></filter><filter id="in37nue" width="2.261" height=".978" x="17.085" y="7.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".1"/></filter><filter id="iidTggs" width="2.261" height=".978" x="11.634" y="7.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".1"/></filter><filter id="iFh6lGe" width="4.312" height="4.613" x="9.091" y="3.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/><feGaussianBlur result="effect2_foregroundBlur_4002_2173" stdDeviation=".2"/></filter><filter id="iOqEGOd" width="8.767" height="5.782" x="12.276" y="2.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/><feGaussianBlur result="effect2_foregroundBlur_4002_2173" stdDeviation=".125"/></filter><filter id="ii0Ljjc" width="1.145" height="2.31" x="12.255" y="3.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".1"/></filter><filter id="iPlF1Rb" width="6.427" height="3.372" x="14.864" y="4.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2173" stdDeviation=".375"/></filter><filter id="i1885jc" width="11.479" height="6.324" x="9.611" y="5.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.498039 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2173"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.741176 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2173" result="effect2_innerShadow_4002_2173"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-scientist-medium" /></template>
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

.ab8h_irtj {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.377 4.607c.565-.6 1.636-.6 2.13-.511l.396 1.29c-.253-.039-.295-.001-.485.183c-.137 1.093-1.376 1.757-2.886 2.198c-.149-1.492.109-2.38.845-3.16");
}

.aebydul1g {
  stop-color: var(--svg-color--9a5a7b, #9A5A7B);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.agmv86b0w {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.385 8.222c.323-.078 1.125-.039 1.661.345");
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.alzmjkbgl {
  d: path("M14.843 2.804c-1.133-.25-2.15.88-2.267 1.3c1.051 3.544 3.713 3.35 6.34 3.058c1.572-.175 1.743.542 1.877.889c0-3.933-3.344-4.671-5.922-5.24z");
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

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.b92e6t3qh {
  d: path("M18.425 10.296a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.be8zxackb {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.053 10.372l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.bef17t_3x {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.048 8.817l-.004.003a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.009-.006a2 2 0 0 1 .148-.076a3 3 0 0 1 .41-.162c.34-.109.816-.2 1.329-.11a.268.268 0 1 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.181z");
}

.bfjdpmblm {
  d: path("M13.262 9.521a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.bfl4-fbqr {
  stop-color: var(--svg-color--5f4786, #5F4786);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c_ev0q_fe {
  d: path("M11.114 16.226a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c5cwb6k_s {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.621px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.c5vqwcbfw {
  cx: 12.992px;
  cy: 9.902px;
  rx: 0.39px;
  ry: 0.197px;
}

.c90z04b8d {
  d: path("M8.226 29.933v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.ccige11qy {
  d: path("M15.426 18.563a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
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

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.cr9men0um {
  d: path("M20.273 11.67a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.df3wracno {
  d: path("m21.37 17.057l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687l-4.732 4.808a.2.2 0 0 1-.343-.14v-3.381a2 2 0 0 1 .175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.dhui3nlqd {
  stop-color: var(--svg-color--d6baf6, #D6BAF6);
}

.do28bmb5k {
  stop-color: var(--svg-color--755b9f, #755B9F);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.ea51mjonn {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M16.588 10.026c.265-.467.669-.836 1.537-.836c.38 0 .747.106 1.073.37c.269.216.233.494.025.598l-.556.318c-.652-.21-1.373-.24-2.08-.45");
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.edg2r54vx {
  d: path("m15.064 10.234l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.egj-02bls {
  stop-color: var(--svg-color--482f73, #482F73);
}

.f5f2c6brp {
  d: path("M23.825 21.98v-.469h.805a.234.234 0 0 1 0 .469z");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fkj5oxbba {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.555 4.053c.023.243.234 1.157.544 1.71");
}

.foy77stiz {
  stop-color: var(--svg-color--9f98a7, #9F98A7);
}

.frstvbc2m {
  stop-color: var(--svg-color--5f4786, #5F4786);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fy-71g_sr {
  stop-color: var(--svg-color--50a193, #50A193);
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.ge8573boc {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.594 8.222c-.322-.078-1.124-.039-1.66.345");
}

.gknvw6bil {
  stop-color: var(--svg-color--a5776e, #A5776E);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hdogj2h5i {
  stop-color: var(--svg-color--9f6778, #9F6778);
  stop-opacity: 0;
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
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

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_cmqr47j {
  d: path("m9.255 17.754l-.13 1.733a.6.6 0 0 0 .493.636l.48.084a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j-r8h2jid {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.837 9.249c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j8t6g3bhi {
  d: path("M10.76 12.204a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jsdcepb_z {
  d: path("M15.8 15.192c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.jsjicce4p {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m17.852 6.414l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.396 1.9 1.872a3.15 3.15 0 0 0-2.69-.769");
}

.k1ofhim6h {
  d: path("M17.564 9.71c.064.085-.069.188-.22.301s-.263.193-.327.108s.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktn4_vb9n {
  d: path("M10.78 11.67a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.l41d1tbgo {
  d: path("M19.865 16.226a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
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

.laeihzb1c {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.113 13.409a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.247-.041c-.404.215-.88.339-1.398.339a3 3 0 0 1-1.398-.34a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.248m3.333 0l-.042-.028l.042.027Zm0 0a1.982 1.982 0 0 1-3.333 0m0 0l.041-.028m-.041.028l.041-.028m0 0a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.292-.204-.22c-.41.22-.895.346-1.421.346c-.52 0-1.01-.126-1.422-.345c-.14-.073-.291.089-.203.22Z");
}

.lehkj4qja {
  stop-color: var(--svg-color--925f61, #925F61);
  stop-opacity: 0;
}

.lguxr4_am {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.273 11.67a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lnpdvvblo {
  fill: var(--svg-color--9b94a2, #9B94A2);
  fill-rule: evenodd;
  d: path("M9.761 9.114c.012-1.676 1.389-3.005 3.047-3.005h5.275A3.01 3.01 0 0 1 21.09 9.15c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.609.34v.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.lpmntqveh {
  d: path("M17.63 9.521a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcniv-j4i {
  d: path("M20.273 12.204a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mhqcou54m {
  fill: var(--svg-color--000, #000);
  d: path("M13.773 10.413a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.745h.905a.5.5 0 0 0 .06-.235");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mz6me4bgx {
  d: path("M14.077 10.309c0-.289-.234-.481-.298-.54l-.288.28l.177.361z");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.n9xbx_eri {
  fill: var(--svg-color--000, #000);
  d: path("M17.119 10.413c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.745h-.904a.46.46 0 0 1-.061-.235");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nqlop1boy {
  d: path("M10.359 9.332h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439q.023-.008.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.135 1.333l-.118 3.073c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o77zymbyt {
  stop-color: var(--svg-color--a588b8, #A588B8);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.out3l1bbv {
  d: path("M23.825 23.761v-.468h.805a.234.234 0 1 1 0 .468z");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pgp6pr__x {
  stop-color: var(--svg-color--925f61, #925F61);
}

.ph_moylrd {
  stop-color: var(--svg-color--945771, #945771);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn_ui08uz {
  d: path("M10.377 4.607c.565-.6 1.636-.6 2.13-.511l.396 1.29c-.253-.039-.295-.001-.485.183c-.137 1.093-1.376 1.757-2.886 2.198c-.149-1.492.109-2.38.845-3.16");
}

.pxdyn0bka {
  stop-color: var(--svg-color--87bfb5, #87BFB5);
}

.q-4nxsbsy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.24h1.797");
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q9qyt5bec {
  d: path("M18.083 6.41h-5.275c-1.497 0-2.737 1.2-2.747 2.706a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.269 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.qgr_41bfc {
  d: path("M26.434 22.903c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qjt16ebmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.935h1.797");
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rif685bkq {
  d: path("m21.202 18.196l.116 1.534a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.075.22l.554.611a.44.44 0 0 1-.013.607l-4.188 4.255a.177.177 0 0 1-.303-.124v-2.992c0-.25.053-.496.155-.724l2.306-5.136c.822.264 1.599.64 2.31 1.111");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.ryd497v6k {
  d: path("M23.137 25.259a.73.73 0 0 1 .726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.s3wacbc5g {
  d: path("M15.466 15.293c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t5bid5bsq {
  stop-color: var(--svg-color--a9ff93, #A9FF93);
  stop-opacity: 0.5;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tn6sd3bmv {
  d: path("m9.608 17.057l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.381a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
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

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ud5tgpbel {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.055 9.249c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v6bhjtbbk {
  stop-color: var(--svg-color--a8a1ad, #A8A1AD);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.vgtum5b-w {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.621px;
  rx: 0.391px;
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
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

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wmbnj2bxj {
  fill-rule: evenodd;
  d: path("M22.631 12.005c.213-.435.324-.921.324-1.427c0-.467-.096-.906-.269-1.306h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.215 3.298v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.012l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.292 1.275c-.236.123-.79.49-.81 1.439l.01.306z");
}

.wnu1izbkk {
  d: path("M15.47 15.192h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wz6su-bfc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.564 9.71c.064.085-.069.188-.22.301s-.263.193-.327.108s.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.x2qgolnse {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.544h1.797");
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xngdzm8vt {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.064 10.234l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.646-.377-.766 0");
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
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

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.xzlzp1b8g {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.304 10.026c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.37c-.269.216-.233.494-.025.598l.556.318c.652-.21 1.373-.24 2.079-.45");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y7hkmkbrv {
  cx: 12.992px;
  cy: 9.902px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.y7orfnsjv {
  fill: var(--svg-color--553836, #553836);
  d: path("M14.843 2.804c-1.133-.25-2.15.88-2.267 1.3c1.051 3.544 3.713 3.35 6.34 3.058c1.572-.175 1.743.542 1.877.889c0-3.933-3.344-4.671-5.922-5.24z");
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ykt8wq3aa {
  d: path("M22.753 29.933v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yv-i8ss1z {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M10.78 11.67a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.yvghywbvb {
  d: path("M23.825 19.402h2.703v5.938h-2.703z");
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zj_pz5bwb {
  d: path("M15.466 15.243h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zqbntluns {
  stop-color: var(--svg-color--746e77, #746E77);
}

.zrc3yuv7g {
  d: path("M26.529 21.168v4.171h-2.704v-4.171z");
}

.zt127j5os {
  stop-color: var(--svg-color--ddd8e2, #DDD8E2);
  stop-opacity: 0;
}

.zzyag9b7i {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.177 8.36l-.137.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.109a3.3 3.3 0 0 1 .558.238l.01.006z");
}

</style>
