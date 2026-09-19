<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#izMTNqe)" class="jqcbrf9li"/><path fill="url(#ihzC2we)" class="dsi2inb8v"/><path fill="url(#iCRuZhd)" class="dsi2inb8v"/><g filter="url(#iqmmrfQ)"><path fill="url(#i3gmAsO)" class="cc5b8vnxd"/><path fill="url(#izj8Blu)" class="cc5b8vnxd"/><path fill="url(#i6IjZme)" class="cc5b8vnxd"/></g><g filter="url(#inElDDb)"><path fill="url(#iyM47ac)" class="dwuos217j"/><path fill="url(#i36w9gb)" class="dwuos217j"/><path fill="url(#iRX4vLS)" class="dwuos217j"/><path fill="url(#i6PuDyy)" class="dwuos217j"/><path fill="url(#iOUvLMe)" class="dwuos217j"/></g><g filter="url(#iELzRec)"><path fill="url(#ihZuPJb)" class="lhthhtb2z"/><path fill="url(#iuSnhsZ)" class="lhthhtb2z"/><path fill="url(#iv5g9vR)" class="lhthhtb2z"/></g><path class="xfquj6nkp"/><path fill="url(#iCj09kL)" class="be-up2bjx"/><path fill="url(#izg9xie)" class="e8ia3ebja"/><path fill="url(#iyGJawe)" class="e8ia3ebja"/><path fill="url(#iGPZA5d)" class="l8icb7t0i"/><path fill="url(#i8NSNwe)" class="l8icb7t0i"/><g filter="url(#ih15xqe)"><path fill="url(#iiUJTHd)" class="kv2984bfs"/><path fill="url(#ikEYCnc)" class="kv2984bfs"/><path fill="url(#is2lB7b)" class="kv2984bfs"/></g><path fill="url(#iDIARCc)" class="kv2984bfs"/><path fill="url(#iPPwled)" class="kv2984bfs"/><path fill="url(#iGEVozc)" class="pqlpjewwk"/><path fill="url(#iEYRUVn)" class="ik3joab5j"/><path fill="url(#iTiauoc)" class="jd5g49btv"/><path fill="url(#iJn6ike)" class="jd5g49btv"/><path fill="url(#iFTK9Yc)" class="jd5g49btv"/><path fill="url(#ihWqyqb)" class="jd5g49btv"/><path fill="url(#i9guIDb)" class="jd5g49btv"/><g filter="url(#imbGPbd)"><path class="v4kni3bwi"/></g><g filter="url(#ihlUX1p)"><path fill="url(#iLin7gc)" class="goochubox"/></g><path fill="url(#ieJROKd)" class="rd2jrq76f"/><path fill="url(#iz9Y4dD)" class="rd2jrq76f"/><path fill="url(#iIlYcYd)" class="yxputb6kg"/><path fill="url(#iihtZPb)" class="yxputb6kg"/><path fill="url(#iHMTsBb)" class="vbv0a2bxk"/><path fill="url(#ip2VI0O)" class="vbv0a2bxk"/><path fill="url(#iZ5ae7b)" class="vbv0a2bxk"/><g filter="url(#iQb4ftA)"><path fill="url(#izOfkte)" class="rjonldykw"/><path fill="url(#iWAuamd)" class="rjonldykw"/><path fill="url(#ii5N9Sd)" class="rjonldykw"/><path fill="url(#iuuYayd)" class="rjonldykw"/><path fill="url(#i30G2Qd)" class="rjonldykw"/></g><g filter="url(#iflnyNb)"><path stroke="url(#iuBa2Ae)" class="c_ww_7b4b"/></g><g filter="url(#ilJqNze)"><path stroke="url(#iOP83zP)" class="sdokkqbwq"/></g><g filter="url(#iIZiMFe)"><path stroke="url(#iuxxcXd)" class="oc5y0ybdc"/></g><g filter="url(#i71wyse)"><path class="al1_robkh"/><path fill="url(#iMW1vpc)" class="x7hzg3b7x"/></g><path fill="url(#iWrM7he)" class="f7fn5uban"/><path fill="url(#iM1oOEc)" class="f7fn5uban"/><path fill="url(#i5H63kg)" class="f7fn5uban"/><path fill="url(#im1dy6b)" class="f7fn5uban"/><g filter="url(#ivo4yie)"><path fill="url(#iXekkxb)" class="w-7byvu1x"/></g><g filter="url(#iczBTWb)"><path fill="url(#ipUZszb)" class="zf04g1mlk"/></g><g filter="url(#iDw2fLe)"><path fill="url(#ilV8smc)" class="wncb0q9bf"/></g><path fill="url(#i5ztLre)" class="g4idkobuv"/><path fill="url(#iQO5AJe)" class="g4idkobuv"/><path fill="url(#i5XPncc)" class="g4idkobuv"/><path fill="url(#iECettc)" class="g4idkobuv"/><g filter="url(#i81cSic)"><path stroke="url(#iWyim2L)" class="ohxmlmbya"/></g><path class="jipz52bok"/><g filter="url(#iAHKxSb)"><path class="qo_elpbnc"/></g><g filter="url(#isnllrb)"><path class="nfxn4rbyq"/><path fill="url(#iTQ1pdb)" class="uxevksnsv"/><path fill="url(#i67Lwne)" class="uxevksnsv"/><path fill="url(#ifIisLQ)" class="uxevksnsv"/><path fill="url(#i9TUCyb)" class="uxevksnsv"/><path fill="url(#ilLVDFd)" class="uxevksnsv"/></g><g filter="url(#iVnCZLd)"><path class="o88ka16yn"/></g><g filter="url(#i8jjhWc)"><path class="tuhylrixb"/></g><g filter="url(#iwPZUWd)"><path class="sc8z6oj_p"/></g><g filter="url(#iqNcSte)"><path class="wbdj7kzwl"/></g><path class="h1yk5xb4a"/><path fill="url(#iKku7ld)" class="vox3wk1ej"/><path class="iupknglmc"/><g filter="url(#ipjgqdc)"><path class="kt0seabrb"/><path fill="url(#iICjuRP)" class="aa5o8st2v"/></g><g filter="url(#iaxSz6d)"><path fill="url(#ic0Xeub)" class="l__q92bqi"/></g><path class="njas120ku"/><path fill="url(#ipgRdSb)" class="d1gkzfw0s"/><path class="d57dhij5w"/><g filter="url(#iEcIrKw)"><path fill="url(#iPPU3ye)" class="zswzavb2t"/></g><g filter="url(#i414t8j)"><ellipse transform="rotate(-27.914 13.678 10.009)" class="txfleqmhl"/><ellipse fill="url(#i3CB3gd)" transform="rotate(-27.914 13.678 10.009)" class="u-1eq1zzi"/></g><g filter="url(#ifEdtHc)"><path class="jsjgmfbfc"/></g><g filter="url(#iIDHcbb)"><path class="zbjaxacud"/></g><g filter="url(#izp7nrt)"><path fill="url(#ivO8QUd)" class="hnvgafcqc"/></g><g filter="url(#ih2fkyc)"><path class="l1a6r2b8n"/></g><defs><radialGradient id="izMTNqe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.886 3.96)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="ihzC2we" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.761 5.122)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="izj8Blu" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.645 3.895)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="i6IjZme" cx="0" cy="0" r="1" gradientTransform="matrix(6.90227 -3.56704 2.32702 4.50282 16.068 10.135)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="s0qpik8kr"/><stop offset="1" class="y2pqqr5ks"/></radialGradient><radialGradient id="iyM47ac" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -6.4375 7.87502 2.0261 19.564 16.372)" gradientUnits="userSpaceOnUse"><stop class="zroppc2op"/><stop offset="1" class="ebxhbcbuh"/></radialGradient><radialGradient id="i36w9gb" cx="0" cy="0" r="1" gradientTransform="matrix(2.76563 -.5625 .27296 1.34206 22.126 11.145)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iRX4vLS" cx="0" cy="0" r="1" gradientTransform="rotate(132.337 9.834 9.022)scale(1.9024 4.92695)" gradientUnits="userSpaceOnUse"><stop class="vbc_7bc2p"/><stop offset="1" class="qgz810hkg"/></radialGradient><radialGradient id="i6PuDyy" cx="0" cy="0" r="1" gradientTransform="matrix(2.04688 -.9375 .81666 1.78304 20.501 10.33)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="g1dhpdv7c"/><stop offset="1" class="o6r_rkb1r"/></radialGradient><radialGradient id="iOUvLMe" cx="0" cy="0" r="1" gradientTransform="matrix(.86794 -1.4047 2.34017 1.44596 19.872 9.103)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="f042gyb-i"/><stop offset="1" class="l60xc51hv"/></radialGradient><radialGradient id="iuSnhsZ" cx="0" cy="0" r="1" gradientTransform="rotate(106.741 2.041 7.453)scale(6.18397 1.94761)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="dnemlj_ra"/><stop offset="1" class="z9wmabgke"/></radialGradient><radialGradient id="iv5g9vR" cx="0" cy="0" r="1" gradientTransform="matrix(1.29688 -2.61824 1.49953 .74275 11.47 9.614)" gradientUnits="userSpaceOnUse"><stop class="l3on1wbgp"/><stop offset="1" class="cw3233bfw"/></radialGradient><radialGradient id="iCj09kL" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.998 16.285)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iyGJawe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.855 25.247)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="i8NSNwe" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 23.028 24.71)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="du4i2cruh"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="iiUJTHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16.068 16.153)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="is2lB7b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.213 19.551)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iPPwled" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.461 15.97)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iGEVozc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.988 19.652)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iEYRUVn" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.17861 -3.0911 0 15.99 16.267)" gradientUnits="userSpaceOnUse"><stop class="weo1_s1xr"/><stop offset=".442" class="x75-tty8m"/><stop offset=".836" class="uwr0-qq-p"/></radialGradient><radialGradient id="iJn6ike" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.565 11.793)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="i9guIDb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 9.008 18.81)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="ieJROKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 28.187 23.769)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iz9Y4dD" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.596 23.617)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iihtZPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.181 24.77)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iHMTsBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.205 21.59)" gradientUnits="userSpaceOnUse"><stop class="f1e16d8dl"/><stop offset="1" class="r_2nh8m3w"/><stop offset="1" class="pe7ydabrg"/></radialGradient><radialGradient id="ip2VI0O" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.706 21.973)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="ajwv7ubbs"/><stop offset="1" class="ljk-gfbyr"/></radialGradient><radialGradient id="iWAuamd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.96 25.285)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ii5N9Sd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.96 26.579)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iuuYayd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.96 27.829)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i30G2Qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.96 29.18)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iMW1vpc" cx="0" cy="0" r="1" gradientTransform="rotate(-114.07 9.53 2.648)scale(1.66841)" gradientUnits="userSpaceOnUse"><stop class="jqq5_cbzl"/><stop offset="1" class="e4q48c0eh"/></radialGradient><radialGradient id="iM1oOEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.67404 -1.09021 .87798 1.34816 19.365 10.802)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i5H63kg" cx="0" cy="0" r="1" gradientTransform="rotate(-68.083 18.255 -9.443)scale(2.22877 3.03159)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="sxoyafbbn"/><stop offset=".972" class="tri7bg95c"/></radialGradient><radialGradient id="im1dy6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.37308 -1.50024 1.28607 1.17706 20.96 12.406)" gradientUnits="userSpaceOnUse"><stop class="qrtt6bb6h"/><stop offset="1" class="jyn3bzb2d"/></radialGradient><radialGradient id="iXekkxb" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 5.207 15.672)scale(1.02956)" gradientUnits="userSpaceOnUse"><stop class="zqtv86tqc"/><stop offset=".912" class="d1kj1wnus"/></radialGradient><radialGradient id="ipUZszb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40683 0 0 -2.0812 11.554 11.086)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="prkeaabuo"/><stop offset="1" class="r445c2j1q"/></radialGradient><radialGradient id="ilV8smc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 2.63281 -4.19257 -9.35552 19.095 9.614)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="kyvssj0ct"/><stop offset="1" class="nhkw4cr8v"/></radialGradient><radialGradient id="i5ztLre" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.87488 -8.98026 0 16.076 7.75)" gradientUnits="userSpaceOnUse"><stop offset=".647" class="mr_bc65ug"/><stop offset=".992" class="cwaed_jfg"/></radialGradient><radialGradient id="iQO5AJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.39286 -.8314 .61148 1.02443 18.202 9.73)" gradientUnits="userSpaceOnUse"><stop class="dc0uryb4x"/><stop offset="1" class="fr9__cbkr"/></radialGradient><radialGradient id="i5XPncc" cx="0" cy="0" r="1" gradientTransform="rotate(-118.968 9.731 .703)scale(1.38223 1.08515)" gradientUnits="userSpaceOnUse"><stop class="pp5j2acwp"/><stop offset="1" class="mctecbc6l"/></radialGradient><radialGradient id="iECettc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59961 -1.9098 .6642 .9041 11.86 7.36)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="rg0_uu2ot"/><stop offset="1" class="bb21aubxa"/></radialGradient><radialGradient id="i67Lwne" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21614 -.73448 0 16.562 12.247)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="i9TUCyb" cx="0" cy="0" r="1" gradientTransform="rotate(157.707 7.18 7.514)scale(1.75081 2.66556)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iKku7ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.213 10.104)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iICjuRP" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.487 .69)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipgRdSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.95 10.104)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i3CB3gd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.663 10.323)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iqmmrfQ" width="20.537" height="10.328" x="5.549" y="4.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1808" result="effect2_innerShadow_4002_1808"/></filter><filter id="inElDDb" width="9.49" height="10.956" x="14.103" y="6.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.141176 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="iELzRec" width="6.144" height="10.985" x="8.643" y="6.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.156863 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.211765 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1808" result="effect2_innerShadow_4002_1808"/></filter><filter id="ih15xqe" width="8" height="6.44" x="12.068" y="15.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="imbGPbd" width="8.45" height="4.612" x="11.798" y="25.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".125"/></filter><filter id="ihlUX1p" width="8.05" height="4.28" x="11.948" y="25.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="iQb4ftA" width="4.468" height="5.556" x="23.522" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="iflnyNb" width="2.097" height=".3" x="23.893" y="25.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".05"/></filter><filter id="ilJqNze" width="2.097" height=".3" x="23.814" y="27.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".05"/></filter><filter id="iIZiMFe" width="2.097" height=".3" x="23.893" y="28.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".05"/></filter><filter id="i71wyse" width="3.318" height="3.218" x="9.716" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.439216 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="ivo4yie" width="2.848" height="2.848" x="19.431" y="9.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".175"/></filter><filter id="iczBTWb" width="2.648" height="2.648" x="10.02" y="9.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".125"/></filter><filter id="iDw2fLe" width="10.425" height="9.709" x="11.164" y="6.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.61585 0 0 0 0 0.470285 0 0 0 0 0.429229 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="i81cSic" width="3.685" height="1.517" x="14.241" y="13.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".05"/></filter><filter id="iAHKxSb" width="3.797" height="4.568" x="13.99" y="9.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".5"/></filter><filter id="isnllrb" width="2.197" height="2.968" x="15.017" y="9.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".1"/></filter><filter id="iVnCZLd" width="2.247" height="1.019" x="12.317" y="7.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.137255 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="i8jjhWc" width="2.237" height="1.009" x="17.643" y="7.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.137255 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="iwPZUWd" width="3.001" height="1.285" x="17.173" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="iqNcSte" width="3.001" height="1.285" x="12.189" y="9.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/></filter><filter id="ipjgqdc" width=".786" height=".696" x="17.479" y="9.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".05"/></filter><filter id="iaxSz6d" width=".891" height=".913" x="18.319" y="9.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".1"/></filter><filter id="iEcIrKw" width=".986" height="1.04" x="13.977" y="9.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".1"/></filter><filter id="i414t8j" width=".912" height=".704" x="13.222" y="9.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".05"/></filter><filter id="ifEdtHc" width="2.132" height=".75" x="17.729" y="8.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".075"/></filter><filter id="iIDHcbb" width="2.132" height=".75" x="12.37" y="8.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".075"/></filter><filter id="izp7nrt" width="5.819" height=".998" x="15.739" y="6.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1808" stdDeviation=".075"/></filter><filter id="ih2fkyc" width="7.625" height="9.853" x="21.921" y="10.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.478431 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1808"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1808" result="effect2_innerShadow_4002_1808"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1808" result="effect3_innerShadow_4002_1808"/></filter><linearGradient id="iCRuZhd" x1="15.988" x2="15.988" y1="4.01" y2="4.063" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="i3gmAsO" x1="16.068" x2="16.068" y1="4.809" y2="14.841" gradientUnits="userSpaceOnUse"><stop class="q09ymmbwb"/><stop offset=".842" class="jpvx63ldj"/></linearGradient><linearGradient id="ihZuPJb" x1="11.59" x2="11.59" y1="6.996" y2="17.731" gradientUnits="userSpaceOnUse"><stop offset=".279" class="pnt5bacec"/><stop offset="1" class="j2aks9bvf"/></linearGradient><linearGradient id="izg9xie" x1="9.008" x2="5.418" y1="28.434" y2="28.434" gradientUnits="userSpaceOnUse"><stop class="rhalidc9f"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iGPZA5d" x1="26.571" x2="23.028" y1="22.864" y2="29.17" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="ikEYCnc" x1="20.068" x2="19.133" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="iDIARCc" x1="12.068" x2="12.402" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iTiauoc" x1="17.23" x2="15.283" y1="29.122" y2="19.958" gradientUnits="userSpaceOnUse"><stop class="ym265mvaz"/><stop offset="1" class="k0c3dfbas"/></linearGradient><linearGradient id="iFTK9Yc" x1="23.082" x2="22.855" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="ihWqyqb" x1="9.008" x2="9.132" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="iLin7gc" x1="13.855" x2="20.386" y1="28.341" y2="28.341" gradientUnits="userSpaceOnUse"><stop class="tbsuik4az"/><stop offset="1" class="mkeehnh5k"/></linearGradient><linearGradient id="iIlYcYd" x1="25.678" x2="25.678" y1="21.591" y2="24.77" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="iZ5ae7b" x1="25.706" x2="25.706" y1="22.294" y2="21.7" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="izOfkte" x1="27.55" x2="23.522" y1="28.043" y2="28.043" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="iuBa2Ae" x1="24.043" x2="25.752" y1="26.036" y2="26.036" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iOP83zP" x1="23.964" x2="25.674" y1="27.341" y2="27.341" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iuxxcXd" x1="24.043" x2="25.752" y1="28.645" y2="28.645" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iWrM7he" x1="22.156" x2="22.57" y1="9.725" y2="11.909" gradientUnits="userSpaceOnUse"><stop class="rozhtxbew"/><stop offset="1" class="wdid2qbjr"/></linearGradient><linearGradient id="iWyim2L" x1="14.857" x2="15.193" y1="14.073" y2="13.208" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iTQ1pdb" x1="16.918" x2="16.116" y1="11.639" y2="11.675" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="ifIisLQ" x1="16.116" x2="16.116" y1="12.648" y2="12.236" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ilLVDFd" x1="16.116" x2="16.116" y1="10.253" y2="10.737" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="ic0Xeub" x1="18.991" x2="18.677" y1="10.158" y2="10.351" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPPU3ye" x1="14.693" x2="14.38" y1="10.158" y2="10.351" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivO8QUd" x1="19.545" x2="16.42" y1="6.974" y2="8.521" gradientUnits="userSpaceOnUse"><stop class="x0ovgdcqw"/><stop offset="1" class="gf-sfkrdk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-farmer-medium" /></template>
<style>
.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.aa5o8st2v {
  d: path("M18.149 9.816c.063.085-.07.189-.22.301c-.151.113-.263.193-.327.108c-.063-.085.008-.245.159-.358c.15-.113.324-.136.388-.05");
}

.ajwv7ubbs {
  stop-color: var(--svg-color--92879d, #92879D);
  stop-opacity: 0;
}

.al1_robkh {
  fill: var(--svg-color--8a6160, #8A6160);
  d: path("M11.325 12.515a1.609 1.609 0 1 0 0-3.218a1.609 1.609 0 0 0 0 3.218");
}

.bb21aubxa {
  stop-color: var(--svg-color--5a3137, #5A3137);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.be-up2bjx {
  d: path("M15.998 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.c_ww_7b4b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.043 25.958h1.796");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.cc5b8vnxd {
  d: path("M11.632 4.81c-.85.03-2.678.228-4.102 1.335c-1.238.963-1.477 2.117-1.477 3.086v.477c-.093 1.781 1.446 4.93 6.883 4.93H19.2c5.437 0 6.976-3.149 6.883-4.93V9.23c0-.969-.24-2.123-1.477-3.086c-1.423-1.107-3.252-1.304-4.101-1.336z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cw3233bfw {
  stop-color: var(--svg-color--2b141b, #2B141B);
  stop-opacity: 0;
}

.cwaed_jfg {
  stop-color: var(--svg-color--774e52, #774E52);
}

.d1gkzfw0s {
  d: path("M13.948 9.627a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.d1kj1wnus {
  stop-color: var(--svg-color--a47562, #A47562);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d57dhij5w {
  fill: var(--svg-color--000, #000);
  d: path("M14.459 10.52a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.dc0uryb4x {
  stop-color: var(--svg-color--ab7a70, #AB7A70);
}

.dnemlj_ra {
  stop-color: var(--svg-color--573e3c, #573E3C);
}

.dsi2inb8v {
  d: path("m10.168 5.55l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.du4i2cruh {
  stop-color: var(--svg-color--2aaa64, #2AAA64);
}

.dwuos217j {
  d: path("M16.904 8.013c-1.715 0-2.526-.732-2.801-1.098c.836.027 2.457 0 4.583 0c2.66 0 4.351 1.048 4.704 2.971c.256 1.647-.242 2.689-.121 3.172c.12.484.564 1.763-.282 3.012c-.677.999-2.108 1.55-2.74 1.701h-2.185v-1.853c2.367-.725 2.32-3 2.37-3.212s.422-1.94.297-3.337c-.096-1.072-.788-1.325-1.298-1.302c-.205 0-1.004-.054-2.527-.054");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e4q48c0eh {
  stop-color: var(--svg-color--81545e, #81545E);
  stop-opacity: 0;
}

.e8ia3ebja {
  d: path("M9.008 29.98V18.01h-.006a10.95 10.95 0 0 0-3.994 8.47v3.5z");
}

.ebxhbcbuh {
  stop-color: var(--svg-color--4f3234, #4F3234);
}

.f042gyb-i {
  stop-color: var(--svg-color--402227, #402227);
}

.f1e16d8dl {
  stop-color: var(--svg-color--cbc1d6, #CBC1D6);
}

.f7fn5uban {
  d: path("M20.855 12.515a1.609 1.609 0 1 0 0-3.218a1.609 1.609 0 0 0 0 3.218");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.fr9__cbkr {
  stop-color: var(--svg-color--ab7a70, #AB7A70);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1dhpdv7c {
  stop-color: var(--svg-color--311c1e, #311C1E);
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g4idkobuv {
  d: path("M19.412 7.998h-2.619c-1.38 0-2.044-.559-2.628-1.083c0 0-.86.042-1.259.101c-.215.234-.443.53-.977.886c-.23.116-.756.527-.765 1.46l.063 2.594c.106 2.801 2.262 4.669 4.88 4.669c2.62 0 4.766-1.868 4.881-4.67V9.454c0-1.34-1.393-1.455-1.576-1.455");
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gf-sfkrdk {
  stop-color: var(--svg-color--6b4d4b, #6B4D4B);
  stop-opacity: 0;
}

.goochubox {
  d: path("M19.488 25.81h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h1yk5xb4a {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.422 9.355c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
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

.hnvgafcqc {
  d: path("M19.475 7.09c1.237.057 1.561.24 1.933.454c-.31-.151-1.346-.375-2.777-.063c-1.431.313-2.424.172-2.742.063l.14-.57c1.5.453 1.899.047 3.446.117");
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ik3joab5j {
  d: path("M15.988 18.66c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.iupknglmc {
  fill: var(--svg-color--000, #000);
  d: path("M17.704 10.52c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j2aks9bvf {
  stop-color: var(--svg-color--2a1822, #2A1822);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.jd5g49btv {
  d: path("M23.028 18.04c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.jipz52bok {
  fill: var(--svg-color--87024e, #87024E);
  d: path("M16.083 13.56a3.1 3.1 0 0 1-1.415-.337c-.135-.077-.289.087-.202.222c.347.53.934.876 1.617.876c.684 0 1.27-.347 1.617-.876c.087-.135-.067-.289-.202-.222a3.1 3.1 0 0 1-1.415.337");
}

.jpvx63ldj {
  stop-color: var(--svg-color--734b50, #734B50);
}

.jqcbrf9li {
  d: path("M21.988 5.91h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.jqq5_cbzl {
  stop-color: var(--svg-color--81545e, #81545E);
}

.jsjgmfbfc {
  stroke: var(--svg-color--5a4343, #5A4343);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.929 8.26c.236-.1 1.324 0 1.732.312");
}

.jyn3bzb2d {
  stop-color: var(--svg-color--9a716b, #9A716B);
  stop-opacity: 0;
}

.k0c3dfbas {
  stop-color: var(--svg-color--309edd, #309EDD);
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kt0seabrb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.149 9.816c.063.085-.07.189-.22.301c-.151.113-.263.193-.327.108c-.063-.085.008-.245.159-.358c.15-.113.324-.136.388-.05");
}

.kv2984bfs {
  d: path("m13.032 21.473l3.036-2.123l2.987 2.084c.421.325 1.013.465 1.013-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.594.823.964.563");
}

.kyvssj0ct {
  stop-color: var(--svg-color--bf9477, #BF9477);
}

.l__q92bqi {
  d: path("M19.01 10.402a.84.84 0 0 0-.231-.463l-.26.286l.117.227z");
}

.l1a6r2b8n {
  fill: var(--svg-color--bfb2cd, #BFB2CD);
  d: path("M22.823 11.044a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.6.6 0 0 0-.601-.601");
}

.l3on1wbgp {
  stop-color: var(--svg-color--2b141b, #2B141B);
}

.l60xc51hv {
  stop-color: var(--svg-color--402227, #402227);
  stop-opacity: 0;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l8icb7t0i {
  d: path("M23.028 29.98V18.01h.007a10.95 10.95 0 0 1 3.993 8.47v3.5z");
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhthhtb2z {
  d: path("M10.57 7.55c.976-.499 2.222-.544 2.648-.554l-.513 4.653l1.832 4.33l-2.608 1.752c-3.585-.735-3.348-3.564-3.137-4.355c.222-.831.028-1.02-.085-1.788c-.272-1.833.329-3.255 1.863-4.038");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljk-gfbyr {
  stop-color: var(--svg-color--92879d, #92879D);
}

.lmnxagbed {
  stop-color: var(--svg-color--89829d, #89829D);
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mctecbc6l {
  stop-color: var(--svg-color--905f65, #905F65);
  stop-opacity: 0;
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mkeehnh5k {
  stop-color: var(--svg-color--319ce4, #319CE4);
}

.mo7a9nshu {
  stop-color: var(--svg-color--28659f, #28659F);
  stop-opacity: 0;
}

.mr_bc65ug {
  stop-color: var(--svg-color--91636c, #91636C);
  stop-opacity: 0;
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nfxn4rbyq {
  fill: var(--svg-color--9e7169, #9E7169);
  d: path("m15.742 10.406l-.5 1.627a.518.518 0 0 0 .5.674h.751a.526.526 0 0 0 .5-.674l-.5-1.627c-.135-.356-.645-.356-.75 0");
}

.nhkw4cr8v {
  stop-color: var(--svg-color--956965, #956965);
}

.njas120ku {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.74 9.355c-.652 0-1.204.45-1.354 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.o6r_rkb1r {
  stop-color: var(--svg-color--311c1e, #311C1E);
  stop-opacity: 0;
}

.o88ka16yn {
  fill: var(--svg-color--482f2d, #482F2D);
  d: path("M12.585 8.875a.26.26 0 0 1-.231-.134a.27.27 0 0 1 .096-.366c.039-.02.895-.51 1.896-.327a.26.26 0 0 1 .212.308c-.029.154-.163.25-.308.221c-.809-.144-1.53.26-1.53.26a.24.24 0 0 1-.135.038");
}

.oc5y0ybdc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.043 28.567h1.796");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohxmlmbya {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.424 13.472c.355.543.958.899 1.66.899c.7 0 1.303-.356 1.658-.899a.2.2 0 0 0-.023-.248a.21.21 0 0 0-.243-.045a3.1 3.1 0 0 1-1.393.331c-.511 0-.984-.123-1.391-.33a.2.2 0 0 0-.245.04a.2.2 0 0 0-.023.252Z");
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.pe7ydabrg {
  stop-color: var(--svg-color--aa9ab9, #AA9AB9);
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnt5bacec {
  stop-color: var(--svg-color--4a2a38, #4A2A38);
}

.pp5j2acwp {
  stop-color: var(--svg-color--905f65, #905F65);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.pqlpjewwk {
  d: path("m16.918 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.prkeaabuo {
  stop-color: var(--svg-color--734b49, #734B49);
}

.q09ymmbwb {
  stop-color: var(--svg-color--66404e, #66404E);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qgz810hkg {
  stop-color: var(--svg-color--694b4a, #694B4A);
  stop-opacity: 0;
}

.qo_elpbnc {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.515 10.632l-.5 1.627a.518.518 0 0 0 .5.674h.75a.526.526 0 0 0 .501-.674l-.5-1.627c-.135-.356-.645-.356-.751 0");
}

.qrtt6bb6h {
  stop-color: var(--svg-color--9a716b, #9A716B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r445c2j1q {
  stop-color: var(--svg-color--845b5a, #845B5A);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rd2jrq76f {
  d: path("M26.84 23.12c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.rg0_uu2ot {
  stop-color: var(--svg-color--5a3137, #5A3137);
}

.rhalidc9f {
  stop-color: var(--svg-color--3d935b, #3D935B);
}

.rjonldykw {
  d: path("M23.522 25.306c0-.402.326-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rozhtxbew {
  stop-color: var(--svg-color--c19e89, #C19E89);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s0qpik8kr {
  stop-color: var(--svg-color--4c2524, #4C2524);
}

.sc8z6oj_p {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M17.173 10.132c.266-.466.67-.835 1.538-.835c.38 0 .747.105 1.073.369c.268.217.232.495.024.599l-.556.317c-.652-.21-1.372-.239-2.079-.45");
}

.sdokkqbwq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.964 27.263h1.797");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.tbsuik4az {
  stop-color: var(--svg-color--36a9f3, #36A9F3);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tuhylrixb {
  fill: var(--svg-color--482f2d, #482F2D);
  d: path("M19.622 8.875a.24.24 0 0 1-.135-.038c-.01 0-.732-.414-1.53-.26a.26.26 0 0 1-.309-.212a.26.26 0 0 1 .212-.308c.991-.183 1.858.308 1.887.327a.27.27 0 0 1 .096.366a.24.24 0 0 1-.221.125");
}

.txfleqmhl {
  cx: 13.678px;
  cy: 10.009px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.u-1eq1zzi {
  cx: 13.678px;
  cy: 10.009px;
  rx: 0.389px;
  ry: 0.197px;
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uwr0-qq-p {
  stop-color: var(--svg-color--412d24, #412D24);
}

.uxevksnsv {
  d: path("m15.742 10.406l-.5 1.627a.518.518 0 0 0 .5.674h.751a.526.526 0 0 0 .5-.674l-.5-1.627c-.135-.356-.645-.356-.75 0");
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v4kni3bwi {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.488 25.81h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vbc_7bc2p {
  stop-color: var(--svg-color--694b4a, #694B4A);
}

.vbv0a2bxk {
  d: path("M24.945 19.989h1.523v1.734a.25.25 0 0 1-.25.25h-1.023a.25.25 0 0 1-.25-.25z");
}

.vox3wk1ej {
  d: path("M18.215 9.627a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-7byvu1x {
  d: path("M20.855 11.98a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wbdj7kzwl {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M14.99 10.132c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.wdid2qbjr {
  stop-color: var(--svg-color--a97e72, #A97E72);
}

.weo1_s1xr {
  stop-color: var(--svg-color--855965, #855965);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wncb0q9bf {
  d: path("M19.412 7.998h-2.619c-1.38 0-2.044-.559-2.628-1.083c0 0-.927.042-1.259.101c-.215.234-.443.53-.977.886c-.23.116-.756.527-.765 1.46l.063 2.594c.106 2.801 2.262 4.669 4.88 4.669c2.62 0 4.766-1.868 4.881-4.67V9.454c0-1.34-1.393-1.455-1.576-1.455");
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.x0ovgdcqw {
  stop-color: var(--svg-color--6b4d4b, #6B4D4B);
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.x75-tty8m {
  stop-color: var(--svg-color--8f6864, #8F6864);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.x7hzg3b7x {
  d: path("M11.325 12.515a1.609 1.609 0 1 0 0-3.218a1.609 1.609 0 0 0 0 3.218");
}

.xfquj6nkp {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.998 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y2pqqr5ks {
  stop-color: var(--svg-color--4c2524, #4C2524);
  stop-opacity: 0;
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.ym265mvaz {
  stop-color: var(--svg-color--2d5ca0, #2D5CA0);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yxputb6kg {
  d: path("M26.181 21.77h-1v3h1z");
}

.z9wmabgke {
  stop-color: var(--svg-color--573e3c, #573E3C);
  stop-opacity: 0;
}

.zbjaxacud {
  stroke: var(--svg-color--5a4343, #5A4343);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.303 8.26c-.237-.1-1.325 0-1.733.312");
}

.zf04g1mlk {
  d: path("M11.344 11.98a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zjnvspbhz {
  stop-color: var(--svg-color--28659f, #28659F);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zqtv86tqc {
  stop-color: var(--svg-color--b08975, #B08975);
}

.zroppc2op {
  stop-color: var(--svg-color--312822, #312822);
}

.zswzavb2t {
  d: path("M14.763 10.414c0-.288-.235-.48-.298-.538l-.288.279l.177.36z");
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

</style>
