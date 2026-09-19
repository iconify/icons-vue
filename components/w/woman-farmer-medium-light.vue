<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iMzr8Zd)" class="fsnnbdcfe"/><path fill="url(#iQdGiad)" class="d1arfcbut"/><path fill="url(#i0Z24jc)" class="d1arfcbut"/><g filter="url(#i3n4XUb)"><path fill="url(#iReX8pe)" class="i1290c2zl"/><path fill="url(#iz9FX7M)" class="i1290c2zl"/><path fill="url(#iDTohEb)" class="i1290c2zl"/></g><g filter="url(#ibwHHwc)"><path fill="url(#ioiEXYc)" class="y07m6mfvj"/><path fill="url(#ioV8qRd)" class="y07m6mfvj"/><path fill="url(#i1sAgCc)" class="y07m6mfvj"/><path fill="url(#i98ocwc)" class="y07m6mfvj"/><path fill="url(#iNOZedd)" class="y07m6mfvj"/><path fill="url(#i3K01Cb)" class="y07m6mfvj"/><path fill="url(#iqJwENc)" class="y07m6mfvj"/></g><g filter="url(#i0WvogH)"><path fill="url(#ibSD8Db)" class="mf3zo5b1e"/><path fill="url(#i16sTSZ)" class="mf3zo5b1e"/><path fill="url(#iazHLOe)" class="mf3zo5b1e"/></g><path class="xrivcun2x"/><path fill="url(#iVXPpNc)" class="dmtmz4xal"/><path fill="url(#iqsG0Tc)" class="u2jzghb0f"/><path fill="url(#iIaz0rd)" class="u2jzghb0f"/><path fill="url(#i1cqrYc)" class="b5304xbix"/><path fill="url(#iXAy6Td)" class="b5304xbix"/><g filter="url(#ivZXbwb)"><path fill="url(#iBNIHQc)" class="d5wflkcdd"/><path fill="url(#iKWwQee)" class="d5wflkcdd"/><path fill="url(#iiPEuOd)" class="d5wflkcdd"/></g><path fill="url(#ieQw2Fb)" class="d5wflkcdd"/><path fill="url(#iHalbpc)" class="d5wflkcdd"/><path fill="url(#iglaLxd)" class="so0-adpoi"/><path fill="url(#isrVRkb)" class="m-20ekbez"/><path fill="url(#il0goRc)" class="m-20ekbez"/><path fill="url(#ilTkvld)" class="t4uxi4aoc"/><path fill="url(#ixEsY3b)" class="t4uxi4aoc"/><path fill="url(#i08ZY1c)" class="t4uxi4aoc"/><path fill="url(#iEwrXHT)" class="t4uxi4aoc"/><path fill="url(#iUXfjPb)" class="t4uxi4aoc"/><g filter="url(#iJPjaPb)"><path class="pmtu-2b2c"/></g><g filter="url(#iFtAV2d)"><path fill="url(#iUkwvsd)" class="abnfjfb5e"/></g><path fill="url(#izeXXLd)" class="p_yky7bis"/><path fill="url(#iBR6pVd)" class="p_yky7bis"/><path fill="url(#iDYLDpb)" class="zrxkrlbav"/><path fill="url(#in4tiRb)" class="zrxkrlbav"/><path fill="url(#i6nVgSb)" class="v9wjut-4v"/><path fill="url(#inyiHRc)" class="v9wjut-4v"/><path fill="url(#iVmyOIb)" class="v9wjut-4v"/><g filter="url(#iK0W3sc)"><path fill="url(#i7HPYHe)" class="sd9c-fbkr"/><path fill="url(#iFU4IcJ)" class="sd9c-fbkr"/><path fill="url(#iXXhxBc)" class="sd9c-fbkr"/><path fill="url(#iXkWPEb)" class="sd9c-fbkr"/><path fill="url(#iaisMqb)" class="sd9c-fbkr"/></g><g filter="url(#ig9QZte)"><path stroke="url(#idQAoKd)" class="nvlq9acrd"/></g><g filter="url(#iSEbRUc)"><path stroke="url(#isCAxdd)" class="vna2ibb7k"/></g><g filter="url(#iVOF33d)"><path stroke="url(#iyOPeMe)" class="ff168e97d"/></g><g filter="url(#iTuYQCb)"><path class="yj-6f9mpx"/><path fill="url(#i5Sb9ps)" class="jgz1d1aen"/></g><path fill="url(#iO4i5cK)" class="xrj2fccly"/><path fill="url(#i3Xce3d)" class="xrj2fccly"/><g filter="url(#iSL02fe)"><path fill="url(#iJMDbbc)" class="h2xe8w0lf"/></g><g filter="url(#ita4sbb)"><path fill="url(#ix3hLee)" class="godv_wbky"/></g><g filter="url(#iLfTOHc)"><path fill="url(#iJPjbCe)" class="wo94ae_mc"/></g><path fill="url(#imtfzwc)" class="awpq5xb7o"/><path fill="url(#ipsA6dc)" class="awpq5xb7o"/><path fill="url(#iaiHL7a)" class="awpq5xb7o"/><path fill="url(#iDAzOnd)" class="awpq5xb7o"/><g filter="url(#igQmwlc)"><path stroke="url(#ikvnWJb)" class="i98oq1bjn"/></g><path class="nb0uxlbbr"/><g filter="url(#ioftQMc)"><path class="alkf4hbhb"/></g><g filter="url(#iK9GmzU)"><path fill="url(#i5xI8lc)" class="wx01rzb1e"/><path fill="url(#iLRXV9d)" class="wx01rzb1e"/><path fill="url(#iwgZRzt)" class="wx01rzb1e"/><path fill="url(#i8bt5cc)" class="wx01rzb1e"/></g><g filter="url(#iRDhgFd)"><path class="m0t-bch6p"/></g><g filter="url(#iDrlrhb)"><path class="e8zebnbzy"/></g><g filter="url(#iYHhjAe)"><path class="xpisf4boh"/></g><g filter="url(#iWGugnd)"><path class="d9ztq286r"/></g><path class="uo18484tu"/><path fill="url(#ic388WZ)" class="ond-7eb6m"/><path class="lylhjcbsc"/><g filter="url(#iAY9lHc)"><path class="zpf-u8b9p"/><path fill="url(#i2oO1od)" class="v5jj39vcw"/></g><g filter="url(#iiWinbv)"><path fill="url(#ikv6sAd)" class="pmv5qcbom"/></g><path class="ze7bzacvq"/><path fill="url(#ilb6x4H)" class="t_31og6pi"/><path class="amoz-i41w"/><g filter="url(#iLJfRuc)"><path fill="url(#iGhMvBe)" class="mdpge5l7r"/></g><g filter="url(#iexo9Ed)"><ellipse transform="rotate(-27.914 13.664 10.109)" class="zfgua8bse"/><ellipse fill="url(#iKnrjEd)" transform="rotate(-27.914 13.664 10.109)" class="qcvf_-_gy"/></g><g filter="url(#ieW7MDc)"><path class="out0qacdi"/></g><g filter="url(#iIcK65c)"><path class="nn2b826ls"/></g><g filter="url(#ixpUk5m)"><path class="k8kf2pb0x"/></g><defs><radialGradient id="iMzr8Zd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.872 4.06)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iQdGiad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.747 5.222)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="iz9FX7M" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.67 3.95)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="iDTohEb" cx="0" cy="0" r="1" gradientTransform="matrix(6.90227 -3.56704 2.32702 4.50282 16.054 10.235)" gradientUnits="userSpaceOnUse"><stop offset=".209" class="s0qpik8kr"/><stop offset="1" class="y2pqqr5ks"/></radialGradient><radialGradient id="ioiEXYc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -6.4375 7.87502 2.0261 19.55 16.472)" gradientUnits="userSpaceOnUse"><stop class="ahe2t8bco"/><stop offset="1" class="oanbt7b6a"/></radialGradient><radialGradient id="ioV8qRd" cx="0" cy="0" r="1" gradientTransform="rotate(162.817 11.178 7.524)scale(3.49996 5.18036)" gradientUnits="userSpaceOnUse"><stop class="q_a5dub1w"/><stop offset="1" class="rt66rv9cg"/></radialGradient><radialGradient id="i1sAgCc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 1.40625 -3.88891 .17284 18.05 6.66)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="jh9ja5b7q"/><stop offset="1" class="ku4kpqbmg"/></radialGradient><radialGradient id="i98ocwc" cx="0" cy="0" r="1" gradientTransform="matrix(4.4973 2.41674 -1.48516 2.76372 20.008 7.016)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xfcvcfb8g"/><stop offset="1" class="mzjyinh0q"/></radialGradient><radialGradient id="iNOZedd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.32298 -1.3938 1.17894 -1.96489 20.027 9.823)" gradientUnits="userSpaceOnUse"><stop offset=".606" class="i-_-t9bvj"/><stop offset="1" class="sb1_-hunr"/></radialGradient><radialGradient id="i3K01Cb" cx="0" cy="0" r="1" gradientTransform="matrix(1.7283 -1.82122 .56344 .5347 20.677 10.659)" gradientUnits="userSpaceOnUse"><stop class="pydf9n8yd"/><stop offset="1" class="jzdvr_ble"/></radialGradient><radialGradient id="iqJwENc" cx="0" cy="0" r="1" gradientTransform="matrix(1.98438 -1.20313 1.63663 2.69938 18.018 15.988)" gradientUnits="userSpaceOnUse"><stop offset=".199" class="z9b1rwbil"/><stop offset="1" class="cutimk8wc"/></radialGradient><radialGradient id="i16sTSZ" cx="0" cy="0" r="1" gradientTransform="rotate(-148.431 7.01 3.243)scale(1.52213 2.93248)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="g7_6rccki"/><stop offset="1" class="otv7w_6yn"/></radialGradient><radialGradient id="iazHLOe" cx="0" cy="0" r="1" gradientTransform="rotate(-134.433 9.922 5.172)scale(4.46383 5.21203)" gradientUnits="userSpaceOnUse"><stop class="wxpgqm_ol"/><stop offset="1" class="w4444fbqw"/></radialGradient><radialGradient id="iVXPpNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.983 16.385)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iIaz0rd" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.84 25.347)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iXAy6Td" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 23.014 24.81)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="du4i2cruh"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="iBNIHQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16.053 16.253)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iiPEuOd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.199 19.652)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iHalbpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.447 16.07)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iglaLxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.974 19.752)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="isrVRkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87968 -1.90863 0 15.974 16.88)" gradientUnits="userSpaceOnUse"><stop class="ztiay3bsr"/><stop offset="1" class="d4abicb0m"/></radialGradient><radialGradient id="il0goRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.28845 -2.56488 0 15.974 15.42)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="xcfgjsbuv"/><stop offset="1" class="h3ackr9-s"/></radialGradient><radialGradient id="ixEsY3b" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.546 11.841)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iUXfjPb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.994 18.91)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="izeXXLd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 28.173 23.869)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iBR6pVd" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.583 23.717)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="in4tiRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.167 24.87)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="i6nVgSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.19 21.69)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="inyiHRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.692 22.074)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="iFU4IcJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.945 25.385)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iXXhxBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.945 26.68)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iXkWPEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.945 27.93)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iaisMqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.945 29.28)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i5Sb9ps" cx="0" cy="0" r="1" gradientTransform="matrix(-.96352 -1.32485 1.2944 -.94137 11.648 12.464)" gradientUnits="userSpaceOnUse"><stop class="wc81wbc4w"/><stop offset="1" class="r1r_vbb7o"/></radialGradient><radialGradient id="i3Xce3d" cx="0" cy="0" r="1" gradientTransform="rotate(-51.009 23.742 -15.95)scale(1.62706)" gradientUnits="userSpaceOnUse"><stop class="vl2cjyt3c"/><stop offset="1" class="bx_7xxbew"/></radialGradient><radialGradient id="iJMDbbc" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 5.151 15.715)scale(1.02956)" gradientUnits="userSpaceOnUse"><stop class="bg0uvkbxl"/><stop offset=".912" class="npel8zblz"/></radialGradient><radialGradient id="ix3hLee" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40683 0 0 -2.0812 11.54 11.186)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="yyk4p6yip"/><stop offset="1" class="e3i87pb5c"/></radialGradient><radialGradient id="iJPjbCe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 2.63281 -4.19257 -9.35552 19.08 9.714)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="n2yd31bih"/><stop offset="1" class="lcgnd193a"/></radialGradient><radialGradient id="imtfzwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.87488 -8.98026 0 16.061 7.85)" gradientUnits="userSpaceOnUse"><stop offset=".647" class="e8ndc2bke"/><stop offset=".968" class="mqusi1blo"/></radialGradient><radialGradient id="ipsA6dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.39286 -.8314 .61148 1.02443 18.188 9.83)" gradientUnits="userSpaceOnUse"><stop class="fodpy1bos"/><stop offset="1" class="mq5kei56j"/></radialGradient><radialGradient id="iaiHL7a" cx="0" cy="0" r="1" gradientTransform="rotate(-118.968 9.753 .757)scale(1.38223 1.08515)" gradientUnits="userSpaceOnUse"><stop class="hkz9qob2x"/><stop offset="1" class="fqny3zkwg"/></radialGradient><radialGradient id="iDAzOnd" cx="0" cy="0" r="1" gradientTransform="rotate(-32.425 18.576 -15.96)scale(3.77353 1.31237)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="il0ta7bbm"/><stop offset="1" class="j85ngrbqo"/></radialGradient><radialGradient id="ic388WZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.199 10.205)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i2oO1od" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.504 .744)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilb6x4H" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.935 10.205)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iKnrjEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.649 10.424)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i3n4XUb" width="20.537" height="10.328" x="5.535" y="4.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1811" result="effect2_innerShadow_4002_1811"/></filter><filter id="ibwHHwc" width="9.49" height="10.956" x="14.088" y="6.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.686275 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="i0WvogH" width="5.894" height="10.985" x="8.629" y="6.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.745098 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="ivZXbwb" width="8" height="6.44" x="12.053" y="15.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="iJPjaPb" width="8.45" height="4.612" x="11.784" y="25.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".125"/></filter><filter id="iFtAV2d" width="8.05" height="4.28" x="11.934" y="25.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="iK0W3sc" width="4.468" height="5.556" x="23.508" y="24.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="ig9QZte" width="2.097" height=".3" x="23.878" y="25.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".05"/></filter><filter id="iSEbRUc" width="2.097" height=".3" x="23.8" y="27.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".05"/></filter><filter id="iVOF33d" width="2.097" height=".3" x="23.965" y="28.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".05"/></filter><filter id="iTuYQCb" width="3.318" height="3.218" x="9.701" y="9.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="iSL02fe" width="2.648" height="2.648" x="19.516" y="9.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".125"/></filter><filter id="ita4sbb" width="2.648" height="2.648" x="10.005" y="9.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".125"/></filter><filter id="iLfTOHc" width="10.425" height="9.709" x="11.149" y="7.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.619608 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="igQmwlc" width="3.685" height="1.517" x="14.226" y="13.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".05"/></filter><filter id="ioftQMc" width="3.797" height="4.568" x="13.976" y="9.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".5"/></filter><filter id="iK9GmzU" width="1.997" height="2.768" x="15.103" y="10.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".05"/></filter><filter id="iRDhgFd" width="2.247" height="1.019" x="12.302" y="7.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="iDrlrhb" width="2.237" height="1.009" x="17.628" y="7.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="iYHhjAe" width="3.001" height="1.285" x="17.159" y="9.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="iWGugnd" width="3.001" height="1.285" x="12.174" y="9.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/></filter><filter id="iAY9lHc" width=".786" height=".696" x="17.464" y="9.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".05"/></filter><filter id="iiWinbv" width=".891" height=".913" x="18.304" y="9.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".1"/></filter><filter id="iLJfRuc" width=".986" height="1.04" x="13.962" y="9.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".1"/></filter><filter id="iexo9Ed" width=".912" height=".704" x="13.207" y="9.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".05"/></filter><filter id="ieW7MDc" width="2.132" height=".75" x="17.714" y="8.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".075"/></filter><filter id="iIcK65c" width="2.132" height=".75" x="12.356" y="8.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1811" stdDeviation=".075"/></filter><filter id="ixpUk5m" width="7.625" height="9.853" x="21.907" y="10.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1811"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1811" result="effect2_innerShadow_4002_1811"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1811" result="effect3_innerShadow_4002_1811"/></filter><linearGradient id="i0Z24jc" x1="15.973" x2="15.973" y1="4.11" y2="4.164" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iReX8pe" x1="16.054" x2="16.054" y1="4.91" y2="14.941" gradientUnits="userSpaceOnUse"><stop class="do1aj8bav"/><stop offset=".842" class="w-37x5bhe"/></linearGradient><linearGradient id="ibSD8Db" x1="11.576" x2="11.576" y1="7.096" y2="17.831" gradientUnits="userSpaceOnUse"><stop class="q37id_bqw"/><stop offset="1" class="urghzbcgb"/></linearGradient><linearGradient id="iqsG0Tc" x1="8.994" x2="5.403" y1="28.535" y2="28.535" gradientUnits="userSpaceOnUse"><stop class="rhalidc9f"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="i1cqrYc" x1="26.556" x2="23.014" y1="22.965" y2="29.271" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iKWwQee" x1="20.053" x2="19.119" y1="18.597" y2="18.597" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="ieQw2Fb" x1="12.053" x2="12.387" y1="18.597" y2="18.597" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="ilTkvld" x1="17.216" x2="15.268" y1="29.222" y2="20.058" gradientUnits="userSpaceOnUse"><stop class="ym265mvaz"/><stop offset="1" class="k0c3dfbas"/></linearGradient><linearGradient id="i08ZY1c" x1="23.067" x2="22.841" y1="29.753" y2="29.753" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="iEwrXHT" x1="8.994" x2="9.118" y1="29.753" y2="29.753" gradientUnits="userSpaceOnUse"><stop class="zjnvspbhz"/><stop offset="1" class="mo7a9nshu"/></linearGradient><linearGradient id="iUkwvsd" x1="13.841" x2="20.372" y1="28.441" y2="28.441" gradientUnits="userSpaceOnUse"><stop class="tbsuik4az"/><stop offset="1" class="mkeehnh5k"/></linearGradient><linearGradient id="iDYLDpb" x1="25.664" x2="25.664" y1="21.691" y2="24.87" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="iVmyOIb" x1="25.692" x2="25.692" y1="22.394" y2="21.8" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="i7HPYHe" x1="27.536" x2="23.508" y1="28.143" y2="28.143" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="nfkkf0b1d"/></linearGradient><linearGradient id="idQAoKd" x1="24.028" x2="25.737" y1="26.136" y2="26.136" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="isCAxdd" x1="23.95" x2="25.659" y1="27.441" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iyOPeMe" x1="24.115" x2="25.824" y1="28.652" y2="28.652" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iO4i5cK" x1="21.906" x2="20.84" y1="10.206" y2="12.615" gradientUnits="userSpaceOnUse"><stop class="xfxz_xbmx"/><stop offset="1" class="cegy3obbl"/></linearGradient><linearGradient id="ikvnWJb" x1="14.842" x2="15.179" y1="14.173" y2="13.308" gradientUnits="userSpaceOnUse"><stop class="hq16hab0i"/><stop offset="1" class="iokwoek-x"/></linearGradient><linearGradient id="i5xI8lc" x1="16.101" x2="16.92" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iLRXV9d" x1="15.074" x2="16.102" y1="11.739" y2="11.8" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iwgZRzt" x1="16.101" x2="16.101" y1="12.229" y2="12.984" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="i8bt5cc" x1="16.101" x2="16.101" y1="10.239" y2="10.611" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ikv6sAd" x1="18.976" x2="18.663" y1="10.258" y2="10.451" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGhMvBe" x1="14.679" x2="14.365" y1="10.258" y2="10.452" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-farmer-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.abnfjfb5e {
  d: path("M19.474 25.91h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.ahe2t8bco {
  stop-color: var(--svg-color--cbba80, #CBBA80);
}

.alkf4hbhb {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.5 10.733l-.5 1.626a.518.518 0 0 0 .5.674h.751a.526.526 0 0 0 .5-.674l-.5-1.626c-.134-.357-.645-.357-.75 0");
}

.amoz-i41w {
  fill: var(--svg-color--000, #000);
  d: path("M14.444 10.62a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.awpq5xb7o {
  d: path("M19.397 8.098H16.78c-1.38 0-2.045-.559-2.629-1.082c0 0-.86.041-1.258.1c-.215.234-.444.531-.977.887c-.231.115-.756.526-.766 1.46l.064 2.593c.106 2.801 2.262 4.669 4.88 4.669c2.619 0 4.765-1.868 4.88-4.669V9.553c0-1.339-1.393-1.455-1.576-1.455");
}

.b5304xbix {
  d: path("M23.014 30.08V18.11h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bg0uvkbxl {
  stop-color: var(--svg-color--dba889, #DBA889);
}

.bx_7xxbew {
  stop-color: var(--svg-color--cc9981, #CC9981);
  stop-opacity: 0;
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.cegy3obbl {
  stop-color: var(--svg-color--d9a385, #D9A385);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cutimk8wc {
  stop-color: var(--svg-color--ac9e63, #AC9E63);
  stop-opacity: 0;
}

.d1arfcbut {
  d: path("m10.154 5.65l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.d4abicb0m {
  stop-color: var(--svg-color--b48574, #B48574);
}

.d5wflkcdd {
  d: path("m13.018 21.574l3.035-2.124l2.988 2.085c.42.324 1.012.465 1.012-.355v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.691c0 .953.595.823.964.563");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.d9ztq286r {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M14.976 10.233c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.599l.556.317c.652-.21 1.372-.239 2.079-.45");
}

.dmtmz4xal {
  d: path("M15.984 15.6c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.do1aj8bav {
  stop-color: var(--svg-color--6e4648, #6E4648);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.du4i2cruh {
  stop-color: var(--svg-color--2aaa64, #2AAA64);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e3i87pb5c {
  stop-color: var(--svg-color--bd826e, #BD826E);
}

.e8ndc2bke {
  stop-color: var(--svg-color--be8782, #BE8782);
  stop-opacity: 0;
}

.e8zebnbzy {
  fill: var(--svg-color--8c5829, #8C5829);
  d: path("M19.607 8.976a.24.24 0 0 1-.135-.039c-.01 0-.731-.414-1.53-.26a.26.26 0 0 1-.308-.212a.26.26 0 0 1 .211-.308c.992-.182 1.858.308 1.887.328c.125.077.174.24.096.366a.24.24 0 0 1-.221.125");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.ff168e97d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.115 28.574h1.797");
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.fodpy1bos {
  stop-color: var(--svg-color--e2a68b, #E2A68B);
}

.fqny3zkwg {
  stop-color: var(--svg-color--c58a7c, #C58A7C);
  stop-opacity: 0;
}

.fsnnbdcfe {
  d: path("M21.974 6.01h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.ft5dv1b6b {
  fill: none;
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.g7_6rccki {
  stop-color: var(--svg-color--c4986a, #C4986A);
}

.godv_wbky {
  d: path("M11.33 12.08a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h2xe8w0lf {
  d: path("M20.84 12.08a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.h3ackr9-s {
  stop-color: var(--svg-color--805333, #805333);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hkz9qob2x {
  stop-color: var(--svg-color--c58a7c, #C58A7C);
}

.hq16hab0i {
  stop-color: var(--svg-color--cf9a8c, #CF9A8C);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.i-_-t9bvj {
  stop-color: var(--svg-color--dcb47b, #DCB47B);
}

.i1290c2zl {
  d: path("M11.617 4.91c-.849.03-2.678.228-4.102 1.336c-1.237.962-1.476 2.117-1.476 3.086v.476c-.094 1.781 1.445 4.93 6.883 4.93h6.263c5.438 0 6.977-3.149 6.883-4.93v-.476c0-.97-.239-2.124-1.476-3.086c-1.424-1.108-3.253-1.305-4.102-1.336z");
}

.i98oq1bjn {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.41 13.572c.355.543.957.899 1.659.899c.7 0 1.303-.356 1.659-.899a.2.2 0 0 0-.024-.248a.21.21 0 0 0-.243-.045a3.1 3.1 0 0 1-1.392.331c-.512 0-.985-.123-1.392-.33a.2.2 0 0 0-.244.04a.2.2 0 0 0-.024.252Z");
}

.il0ta7bbm {
  stop-color: var(--svg-color--b5795f, #B5795F);
}

.iokwoek-x {
  stop-color: var(--svg-color--cf9a8c, #CF9A8C);
  stop-opacity: 0;
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.j85ngrbqo {
  stop-color: var(--svg-color--b5795f, #B5795F);
  stop-opacity: 0;
}

.jgz1d1aen {
  d: path("M11.31 12.615a1.609 1.609 0 1 0 0-3.218a1.609 1.609 0 0 0 0 3.218");
}

.jh9ja5b7q {
  stop-color: var(--svg-color--edd0ab, #EDD0AB);
}

.jzdvr_ble {
  stop-color: var(--svg-color--d2ac6f, #D2AC6F);
  stop-opacity: 0;
}

.k0c3dfbas {
  stop-color: var(--svg-color--309edd, #309EDD);
}

.k8kf2pb0x {
  fill: var(--svg-color--b8b1c0, #B8B1C0);
  d: path("M22.809 11.144a.6.6 0 0 0-.602.602v6.851a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.851a.602.602 0 0 0-1.203 0v4.449a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 1 1-1.758 0v-4.45a.6.6 0 0 0-.602-.601");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.ku4kpqbmg {
  stop-color: var(--svg-color--edd0ab, #EDD0AB);
  stop-opacity: 0;
}

.lcgnd193a {
  stop-color: var(--svg-color--c89080, #C89080);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmnxagbed {
  stop-color: var(--svg-color--89829d, #89829D);
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lylhjcbsc {
  fill: var(--svg-color--000, #000);
  d: path("M17.69 10.62c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m-20ekbez {
  d: path("M15.974 18.76c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.m0t-bch6p {
  fill: var(--svg-color--8c5829, #8C5829);
  d: path("M12.57 8.976a.26.26 0 0 1-.23-.135a.27.27 0 0 1 .095-.366c.039-.02.896-.51 1.897-.327c.144.029.24.163.212.308c-.03.154-.164.25-.308.221c-.809-.144-1.531.26-1.531.26a.24.24 0 0 1-.135.039");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdpge5l7r {
  d: path("M14.748 10.515c0-.288-.234-.48-.297-.538l-.289.278l.178.361z");
}

.mf3zo5b1e {
  d: path("M10.555 7.65c.977-.498 2.222-.544 2.649-.554l-.514 4.653l1.833 4.33l-2.608 1.752c-3.585-.735-3.348-3.564-3.137-4.355c.221-.83.028-1.02-.086-1.788c-.272-1.832.329-3.255 1.863-4.038");
}

.mkeehnh5k {
  stop-color: var(--svg-color--319ce4, #319CE4);
}

.mo7a9nshu {
  stop-color: var(--svg-color--28659f, #28659F);
  stop-opacity: 0;
}

.mq5kei56j {
  stop-color: var(--svg-color--e2a68b, #E2A68B);
  stop-opacity: 0;
}

.mqusi1blo {
  stop-color: var(--svg-color--a67166, #A67166);
}

.mzjyinh0q {
  stop-color: var(--svg-color--ead4a6, #EAD4A6);
  stop-opacity: 0;
}

.n2yd31bih {
  stop-color: var(--svg-color--f7c09a, #F7C09A);
}

.nb0uxlbbr {
  fill: var(--svg-color--89004f, #89004F);
  d: path("M16.069 13.66a3.1 3.1 0 0 1-1.415-.337c-.135-.077-.29.087-.203.222c.347.53.934.876 1.618.876a1.92 1.92 0 0 0 1.617-.876c.087-.135-.067-.289-.202-.222a3.1 3.1 0 0 1-1.415.337");
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nfkkf0b1d {
  stop-color: var(--svg-color--c4907c, #C4907C);
}

.nn2b826ls {
  stroke: var(--svg-color--a26d45, #A26D45);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.288 8.36c-.237-.1-1.324 0-1.732.312");
}

.npel8zblz {
  stop-color: var(--svg-color--d6a080, #D6A080);
}

.nvlq9acrd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.028 26.058h1.797");
}

.oanbt7b6a {
  stop-color: var(--svg-color--f1d7aa, #F1D7AA);
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ond-7eb6m {
  d: path("M18.2 9.728a.892.892 0 0 1 .86 1.127h-1.723a.896.896 0 0 1 .864-1.128");
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.otv7w_6yn {
  stop-color: var(--svg-color--c4986a, #C4986A);
  stop-opacity: 0;
}

.out0qacdi {
  stroke: var(--svg-color--a26d45, #A26D45);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.914 8.36c.237-.1 1.324 0 1.732.312");
}

.p_yky7bis {
  d: path("M26.826 23.22c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmtu-2b2c {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.474 25.91h-6.94c-.28 0-.5.217-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.pmv5qcbom {
  d: path("M18.995 10.502a.84.84 0 0 0-.23-.462l-.26.285l.117.228z");
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.pydf9n8yd {
  stop-color: var(--svg-color--d2ac6f, #D2AC6F);
}

.q_a5dub1w {
  stop-color: var(--svg-color--ffefba, #FFEFBA);
}

.q37id_bqw {
  stop-color: var(--svg-color--d9b394, #D9B394);
}

.qcvf_-_gy {
  cx: 13.664px;
  cy: 10.109px;
  rx: 0.389px;
  ry: 0.197px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r1r_vbb7o {
  stop-color: var(--svg-color--bf8271, #BF8271);
  stop-opacity: 0;
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rhalidc9f {
  stop-color: var(--svg-color--3d935b, #3D935B);
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.rt66rv9cg {
  stop-color: var(--svg-color--ffefba, #FFEFBA);
  stop-opacity: 0;
}

.s0qpik8kr {
  stop-color: var(--svg-color--4c2524, #4C2524);
}

.sb1_-hunr {
  stop-color: var(--svg-color--dcb47b, #DCB47B);
  stop-opacity: 0;
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sd9c-fbkr {
  d: path("M23.508 25.406c0-.401.325-.732.727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.so0-adpoi {
  d: path("m16.904 19.79l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.t_31og6pi {
  d: path("M13.933 9.728a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.t4uxi4aoc {
  d: path("M23.014 18.14c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.tbsuik4az {
  stop-color: var(--svg-color--36a9f3, #36A9F3);
}

.u2jzghb0f {
  d: path("M8.994 30.08V18.11h-.007a10.95 10.95 0 0 0-3.993 8.47v3.5z");
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.uo18484tu {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.408 9.456c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.urghzbcgb {
  stop-color: var(--svg-color--ba9971, #BA9971);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v5jj39vcw {
  d: path("M18.135 9.916c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.v9wjut-4v {
  d: path("M24.93 20.09h1.524v1.734a.25.25 0 0 1-.25.25H25.18a.25.25 0 0 1-.25-.25z");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vl2cjyt3c {
  stop-color: var(--svg-color--cc9981, #CC9981);
}

.vna2ibb7k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.95 27.363h1.797");
}

.w-37x5bhe {
  stop-color: var(--svg-color--7c5351, #7C5351);
}

.w4444fbqw {
  stop-color: var(--svg-color--cc9f7f, #CC9F7F);
  stop-opacity: 0;
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wc81wbc4w {
  stop-color: var(--svg-color--bf8271, #BF8271);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wo94ae_mc {
  d: path("M19.397 8.098H16.78c-1.38 0-2.045-.559-2.629-1.082c0 0-.927.041-1.258.1c-.215.234-.444.531-.977.887c-.231.115-.756.526-.766 1.46l.064 2.593c.106 2.801 2.262 4.669 4.88 4.669c2.619 0 4.765-1.868 4.88-4.669V9.553c0-1.339-1.393-1.455-1.576-1.455");
}

.wx01rzb1e {
  d: path("m15.728 10.506l-.5 1.627a.518.518 0 0 0 .5.674h.75a.526.526 0 0 0 .501-.674l-.5-1.627c-.135-.356-.645-.356-.751 0");
}

.wxpgqm_ol {
  stop-color: var(--svg-color--977f52, #977F52);
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xcfgjsbuv {
  stop-color: var(--svg-color--805333, #805333);
  stop-opacity: 0;
}

.xfcvcfb8g {
  stop-color: var(--svg-color--ead4a6, #EAD4A6);
}

.xfxz_xbmx {
  stop-color: var(--svg-color--dcaf93, #DCAF93);
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xpisf4boh {
  fill: var(--svg-color--1d1b1f, #1D1B1F);
  d: path("M17.159 10.233c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.08-.45");
}

.xrivcun2x {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.984 15.6c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.xrj2fccly {
  d: path("M20.84 12.615a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y07m6mfvj {
  d: path("M16.89 8.113c-1.716 0-2.526-.731-2.802-1.097c.836.026 2.457 0 4.584 0c2.659 0 4.35 1.047 4.703 2.97c.257 1.647-.242 2.69-.12 3.173c.12.483.563 1.762-.283 3.01c-.677 1-2.108 1.552-2.739 1.703h-2.185v-1.853c2.366-.725 2.319-3.001 2.37-3.213c.05-.211.421-1.94.297-3.336c-.096-1.073-.788-1.326-1.299-1.302c-.204 0-1.004-.055-2.526-.055");
}

.y2pqqr5ks {
  stop-color: var(--svg-color--4c2524, #4C2524);
  stop-opacity: 0;
}

.y9bk_9fsc {
  stop-color: var(--svg-color--85808c, #85808C);
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yj-6f9mpx {
  fill: var(--svg-color--c08675, #C08675);
  d: path("M11.31 12.615a1.609 1.609 0 1 0 0-3.218a1.609 1.609 0 0 0 0 3.218");
}

.ym265mvaz {
  stop-color: var(--svg-color--2d5ca0, #2D5CA0);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yyk4p6yip {
  stop-color: var(--svg-color--b67862, #B67862);
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z9b1rwbil {
  stop-color: var(--svg-color--ac9e63, #AC9E63);
}

.ze7bzacvq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.726 9.456c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.zfgua8bse {
  cx: 13.664px;
  cy: 10.109px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
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

.zpf-u8b9p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.135 9.916c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.zrxkrlbav {
  d: path("M26.167 21.87h-1v3h1z");
}

.ztiay3bsr {
  stop-color: var(--svg-color--aa7876, #AA7876);
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

</style>
