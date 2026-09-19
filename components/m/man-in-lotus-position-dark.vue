<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iiFEcXb)" clip-rule="evenodd" class="tv41nebaf"/><path fill="url(#iALeSad)" clip-rule="evenodd" class="t2uxtx_ya"/><g filter="url(#i1wHLYb)"><path fill="url(#i6ucWWc)" class="ufs3b81ci"/><path fill="url(#iCwdjPc)" class="ufs3b81ci"/></g><path fill="url(#iqgHXuc)" class="j_m47xbqb"/><path fill="url(#iVs0ptc)" class="j_m47xbqb"/><g filter="url(#iGv9Jtb)"><path class="t-_6tzcpa"/></g><path fill="url(#iqNjaEc)" class="g4-rnpbiv"/><path fill="url(#iThywBd)" class="g4-rnpbiv"/><path fill="url(#idfxACe)" class="qxv17obmu"/><path fill="url(#isUbT6b)" class="qxv17obmu"/><path fill="url(#iBWuPqc)" class="qxv17obmu"/><path fill="url(#iLbr7Sb)" class="qhpil-b3e"/><path fill="url(#iTnTIGe)" class="qhpil-b3e"/><path fill="url(#iC9Y0Gc)" class="qhpil-b3e"/><path class="fpvljrbim"/><path fill="url(#ibEjBCd)" class="s386_46_x"/><path fill="url(#ibzhVWd)" class="s386_46_x"/><path fill="url(#iS46Coe)" class="s386_46_x"/><g filter="url(#ishFJmc)"><path class="i9cgj7g1s"/><path fill="url(#i1QOigd)" class="vcvz10bee"/><path fill="url(#ivUZRZQ)" class="vcvz10bee"/><path fill="url(#iNTvdNe)" class="vcvz10bee"/></g><g filter="url(#iHeN56C)"><path fill="url(#itRDtdd)" class="ufa4e1bue"/></g><path fill="url(#iaHeeWc)" class="wtx0-zb9b"/><path fill="url(#iLUYhsd)" class="wtx0-zb9b"/><g filter="url(#ijADBhc)"><path fill="url(#iajOLTd)" class="e72vc5glc"/><path fill="url(#i4fSfMd)" class="e72vc5glc"/></g><path fill="url(#iSEOc4C)" class="e72vc5glc"/><path clip-rule="evenodd" class="ttit7sbwx"/><path fill="url(#i78Qyac)" clip-rule="evenodd" class="x81pqcclg"/><path clip-rule="evenodd" class="vat8zbb1h"/><path fill="url(#iyFuXyd)" clip-rule="evenodd" class="tej0dgbcx"/><path clip-rule="evenodd" class="z2_7lnp1p"/><path fill="url(#ibHJEZc)" clip-rule="evenodd" class="au2cdjbqa"/><path clip-rule="evenodd" class="hikihhbgc"/><path fill="url(#i7bcDzd)" clip-rule="evenodd" class="j873t3pix"/><path clip-rule="evenodd" class="njoad_bkl"/><path fill="url(#i595LEd)" clip-rule="evenodd" class="qb45jbc1d"/><path clip-rule="evenodd" class="rv50jfbso"/><path fill="url(#ie4bhgh)" clip-rule="evenodd" class="a57epkiey"/><path clip-rule="evenodd" class="dzzs3_bwg"/><path fill="url(#irOah5X)" clip-rule="evenodd" class="onaimccwi"/><g filter="url(#i44gJNd)"><path class="s4y_htbex"/></g><g filter="url(#iITkToe)"><path class="fn3z_sbxx"/></g><g filter="url(#iIfhsct)"><path class="y8dgjevrz"/></g><g filter="url(#iESD3ub)"><path class="mkk0k-byc"/></g><g filter="url(#iICTPHw)"><path class="znfzn6b4i"/></g><g filter="url(#ij22wdb)"><path class="rm-es7b9q"/></g><g filter="url(#ikTJztc)"><path class="w0_6atbzj"/></g><g filter="url(#i6i1w4c)"><path class="p5j2ywblw"/></g><g filter="url(#iGcHmEK)"><circle fill="url(#iIh8p8Q)" class="pmwpwjbcd"/></g><g filter="url(#iSe4xGp)"><circle fill="url(#ii33GEe)" class="at1qw5b4i"/></g><g filter="url(#iUspm7p)"><circle fill="url(#i8PAqBf)" class="ltu6qk3sw"/><circle fill="url(#iBmHZYc)" class="ltu6qk3sw"/></g><g filter="url(#i31W6jb)"><circle class="rhyhzvq2c"/><circle fill="url(#im7mQUs)" class="mxxvki8iv"/><circle fill="url(#iYwHxkb)" class="mxxvki8iv"/></g><g filter="url(#imZv6xe)"><path fill="url(#icmp8Dd)" class="vr111b3hw"/><path fill="url(#iYr9vPc)" class="vr111b3hw"/><path fill="url(#iDoRx2d)" class="vr111b3hw"/><path fill="url(#iIWjo3w)" class="vr111b3hw"/><path fill="url(#ingN5Ku)" class="vr111b3hw"/><path fill="url(#ig9V3Ed)" class="vr111b3hw"/></g><g filter="url(#iL7bAgc)"><path fill="url(#iWI9cob)" class="oyl2pbcaf"/></g><g filter="url(#isLa4Ec)"><path class="vd3_8lo3u"/><path fill="url(#iU4m5pd)" class="ahdfc9bvs"/><path fill="url(#i5m0ycc)" class="ahdfc9bvs"/><path fill="url(#ipYEKke)" class="ahdfc9bvs"/><path fill="url(#ihsKlUw)" class="ahdfc9bvs"/></g><g filter="url(#iJEERuP)"><path class="otxey-b4h"/></g><g filter="url(#idpBqse)"><path class="gfswv02mg"/><path fill="url(#ip59mEd)" class="hb3e6irsp"/><path fill="url(#iKiLkWd)" class="hb3e6irsp"/><path fill="url(#i0RTieb)" class="hb3e6irsp"/><path fill="url(#iyN1W5b)" class="hb3e6irsp"/></g><path fill="url(#iCaX27o)" class="hb3e6irsp"/><path stroke="url(#i7tVppe)" class="kn73ixb2p"/><g filter="url(#iZV05Ee)"><path class="t_lyt9btm"/></g><g filter="url(#iWAaovc)"><path class="x7f4i0bbo"/></g><g filter="url(#izB9uLv)"><path stroke="url(#i2TNTbb)" class="onbt7cb6a"/></g><g filter="url(#igUiHKd)"><path stroke="url(#iEyueVc)" class="ql0bmtmgm"/></g><g filter="url(#i1p72Rd)"><path stroke="url(#iY0YZrb)" class="fr4oj_g5z"/></g><path class="hss_x8b0z"/><g filter="url(#i8TBLVb)"><path class="wd5n0p1ub"/></g><path class="iap9bjb7s"/><g filter="url(#inHFjHb)"><path class="b2v39zblc"/></g><defs><radialGradient id="iiFEcXb" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.438 13.206)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="fznz2mbxx"/><stop offset="1" class="hnjuf644p"/></radialGradient><radialGradient id="iALeSad" cx="0" cy="0" r="1" gradientTransform="matrix(.23438 .67187 -1.35614 .47307 26.835 22.69)" gradientUnits="userSpaceOnUse"><stop class="fznz2mbxx"/><stop offset="1" class="hnjuf644p"/></radialGradient><radialGradient id="i6ucWWc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.424)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="zhfkvgbxb"/><stop offset="1" class="uq-h9hb8w"/></radialGradient><radialGradient id="iCwdjPc" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -7.058 31.738)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="u24mgdcov"/><stop offset="1" class="rwyr8xb2b"/></radialGradient><radialGradient id="iqgHXuc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.768)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="hfnjpubec"/><stop offset="1" class="t0fy-bbwc"/></radialGradient><radialGradient id="iVs0ptc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.409)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="k-fq99sbh"/><stop offset="1" class="phf6igbvb"/></radialGradient><radialGradient id="iqNjaEc" cx="0" cy="0" r="1" gradientTransform="rotate(165.069 8.953 14.565)scale(1.45539 2.44377)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="mwtukgbbz"/><stop offset="1" class="fozz65l2p"/></radialGradient><radialGradient id="iThywBd" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 -1.5 3.43224 4.2188 6.044 26.706)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="lg8towb3y"/><stop offset="1" class="pdvw2hfdl"/></radialGradient><radialGradient id="idfxACe" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.33)" gradientUnits="userSpaceOnUse"><stop class="us72pebsg"/><stop offset="1" class="hx5ihzb7y"/></radialGradient><radialGradient id="iLbr7Sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="uwa_e26-a"/><stop offset="1" class="hx5ihzb7y"/></radialGradient><radialGradient id="ibzhVWd" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.158 23.732)" gradientUnits="userSpaceOnUse"><stop class="w-l5r38ro"/><stop offset="1" class="lehanccnj"/></radialGradient><radialGradient id="iS46Coe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20.237)" gradientUnits="userSpaceOnUse"><stop class="pc6ft5bqj"/><stop offset="1" class="crrluq_8b"/></radialGradient><radialGradient id="ivUZRZQ" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.277 7.65)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="uo439xb-e"/><stop offset="1" class="wsizjkbjw"/></radialGradient><radialGradient id="iNTvdNe" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.33)" gradientUnits="userSpaceOnUse"><stop class="ept1d-nvv"/><stop offset="1" class="iu4sfzbng"/></radialGradient><radialGradient id="itRDtdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.33)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="iaHeeWc" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.125 2.517)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="pk5i2pb0j"/><stop offset="1" class="d-f_cevwl"/></radialGradient><radialGradient id="iLUYhsd" cx="0" cy="0" r="1" gradientTransform="rotate(108.939 3.647 10.356)scale(3.36993 3.80066)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="rsji3yblh"/><stop offset="1" class="ddt4h9ktn"/></radialGradient><radialGradient id="iajOLTd" cx="0" cy="0" r="1" gradientTransform="rotate(86.442 1.652 16.17)scale(8.05726 7.74996)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="afioo-bwu"/><stop offset="1" class="h1j0-fblz"/></radialGradient><radialGradient id="i4fSfMd" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.536 10.87)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="bakt0qbwy"/><stop offset="1" class="ltpsj2n6q"/></radialGradient><radialGradient id="iSEOc4C" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 12.05)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="rx6_xs15m"/><stop offset="1" class="keibw1bxy"/><stop offset="1" class="z321yabtz"/></radialGradient><radialGradient id="i78Qyac" cx="0" cy="0" r="1" gradientTransform="matrix(.04721 .75606 -4.208 .26278 4.575 23.17)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="iyFuXyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0472 .75606 -4.20801 -.26276 27.424 23.17)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="ibHJEZc" cx="0" cy="0" r="1" gradientTransform="matrix(.05288 .98594 -4.7173 .25299 4.591 23.76)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="i7bcDzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05288 .98594 -4.7173 -.25299 27.409 23.76)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="i595LEd" cx="0" cy="0" r="1" gradientTransform="matrix(.00011 .90392 -3.36918 .00041 5.113 24.51)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="ie4bhgh" cx="0" cy="0" r="1" gradientTransform="matrix(-.00011 .90392 -3.36917 -.00041 26.887 24.51)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="khd1c0n-i"/><stop offset=".968" class="n55l0rxro"/></radialGradient><radialGradient id="iIh8p8Q" cx="0" cy="0" r="1" gradientTransform="matrix(1.11107 0 0 1.94437 11.951 7.433)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iBmHZYc" cx="0" cy="0" r="1" gradientTransform="matrix(.52341 -.38113 .435 .59741 19.267 7.265)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="im7mQUs" cx="0" cy="0" r="1" gradientTransform="matrix(.51997 -.95637 .55977 .30434 19.005 7.952)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iYwHxkb" cx="0" cy="0" r="1" gradientTransform="matrix(.16416 .1625 -.20948 .21163 19.031 7.432)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iDoRx2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.49852 -6.1065 0 15.823 7.306)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iIWjo3w" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82756 1.01853 0 17.5 6.627)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="ingN5Ku" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.8806 1.09511 0 14.613 6.606)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="ig9V3Ed" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 10.033 4.551)scale(1.85059 1.08734)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iU4m5pd" cx="0" cy="0" r="1" gradientTransform="matrix(.50513 -1.87194 .69417 .18732 18.765 4.833)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="i5m0ycc" cx="0" cy="0" r="1" gradientTransform="matrix(2.42164 .22286 -.11983 1.3021 17.725 3.719)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ipYEKke" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.06314 -1.64651 0 16.014 1.987)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="ihsKlUw" cx="0" cy="0" r="1" gradientTransform="matrix(1.94622 -1.42624 2.23445 3.04908 11.93 6.303)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iyN1W5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .12466 -.40052 0 16.221 8.45)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><filter id="i1wHLYb" width="9.729" height="6.156" x="17.627" y="22.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.184314 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.156863 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23987" result="effect2_innerShadow_3987_23987"/></filter><filter id="iGv9Jtb" width="17.213" height="7.995" x="5.751" y="22.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23987" result="effect2_innerShadow_3987_23987"/></filter><filter id="ishFJmc" width="7.621" height="12.797" x="19.836" y="12.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0666667 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="iHeN56C" width="8.502" height="3.19" x="11.869" y="21.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="ijADBhc" width="8.289" height="10.271" x="11.888" y="11.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.556863 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="i44gJNd" width="1.684" height="1.255" x="5.351" y="24.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".075"/></filter><filter id="iITkToe" width="1.684" height="1.255" x="24.965" y="24.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".075"/></filter><filter id="iIfhsct" width="2.04" height="1.095" x="4.237" y="24.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".075"/></filter><filter id="iESD3ub" width="2.04" height="1.095" x="25.723" y="24.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".075"/></filter><filter id="iICTPHw" width="2.223" height=".888" x="3.593" y="23.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".075"/></filter><filter id="ij22wdb" width="2.223" height=".888" x="26.184" y="23.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".075"/></filter><filter id="ikTJztc" width="2.031" height=".566" x="3.653" y="23.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".075"/></filter><filter id="i6i1w4c" width="2.031" height=".566" x="26.317" y="23.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".075"/></filter><filter id="iGcHmEK" width="2.314" height="2.114" x="11.951" y="6.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="iSe4xGp" width="2.26" height="2.26" x="11.878" y="6.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".25"/></filter><filter id="iUspm7p" width="2.364" height="2.364" x="17.975" y="6.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="i31W6jb" width="2.26" height="2.26" x="17.901" y="6.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".25"/></filter><filter id="imZv6xe" width="6.568" height="7.765" x="12.748" y="3.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="iL7bAgc" width="4.688" height="3.942" x="15.122" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".5"/></filter><filter id="isLa4Ec" width="7.979" height="5.243" x="12.024" y="1.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="iJEERuP" width="2.614" height="3.198" x="14.556" y="6.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".375"/></filter><filter id="idpBqse" width="1.688" height="2.198" x="15.17" y="6.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".125"/></filter><filter id="iZV05Ee" width="1.978" height="1.333" x="16.763" y="4.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="iWAaovc" width="1.978" height="1.333" x="13.503" y="4.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23987"/></filter><filter id="izB9uLv" width="2.021" height="1.123" x="16.64" y="5.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".15"/></filter><filter id="igUiHKd" width="2.07" height="1.159" x="13.336" y="5.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".15"/></filter><filter id="i1p72Rd" width=".913" height="1.712" x="12.605" y="4.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".125"/></filter><filter id="i8TBLVb" width="1.628" height=".644" x="13.82" y="6.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".05"/></filter><filter id="inHFjHb" width="1.628" height=".644" x="16.609" y="6.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23987" stdDeviation=".05"/></filter><linearGradient id="isUbT6b" x1="21.525" x2="21.525" y1="21.268" y2="22.424" gradientUnits="userSpaceOnUse"><stop class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iBWuPqc" x1="18.658" x2="19.892" y1="24.552" y2="24.956" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iTnTIGe" x1="10.822" x2="10.822" y1="21.268" y2="22.424" gradientUnits="userSpaceOnUse"><stop class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="iC9Y0Gc" x1="13.689" x2="12.455" y1="24.552" y2="24.956" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uc5_bsbkt"/><stop offset="1" class="z2i7gkbiq"/></linearGradient><linearGradient id="ibEjBCd" x1="12.24" x2="10.033" y1="20.873" y2="20.683" gradientUnits="userSpaceOnUse"><stop offset=".184" class="w3geznflg"/><stop offset="1" class="o-0p8ab1g"/></linearGradient><linearGradient id="i1QOigd" x1="19.835" x2="22.042" y1="20.873" y2="20.683" gradientUnits="userSpaceOnUse"><stop offset=".184" class="e5bi16n_y"/><stop offset="1" class="n9h2xzfye"/></linearGradient><linearGradient id="irOah5X" x1="26.513" x2="24.888" y1="25.44" y2="24.177" gradientUnits="userSpaceOnUse"><stop offset=".455" class="fznz2mbxx"/><stop offset="1" class="b04py3bjk"/></linearGradient><linearGradient id="ii33GEe" x1="13.008" x2="12.602" y1="7.609" y2="7.609" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="i8PAqBf" x1="19.72" x2="19.201" y1="6.741" y2="8.347" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="icmp8Dd" x1="18.569" x2="13.734" y1="7.679" y2="8.4" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iYr9vPc" x1="12.598" x2="14.032" y1="9.386" y2="9.296" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iWI9cob" x1="16.622" x2="22.077" y1="5.541" y2="3.663" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="ip59mEd" x1="15.467" x2="16.061" y1="8.096" y2="8.096" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iKiLkWd" x1="16.608" x2="15.959" y1="8.301" y2="8.291" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="i0RTieb" x1="16.137" x2="16.137" y1="8.771" y2="8.408" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iCaX27o" x1="16.094" x2="16.094" y1="8.797" y2="8.691" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="i7tVppe" x1="15.357" x2="15.633" y1="9.793" y2="9.358" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="i2TNTbb" x1="17.896" x2="17.63" y1="5.68" y2="5.136" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iEyueVc" x1="14.537" x2="13.784" y1="5.599" y2="5.283" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iY0YZrb" x1="13.062" x2="13.062" y1="4.324" y2="5.689" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-lotus-position-dark" /></template>
<style>
.a57epkiey {
  fill-rule: evenodd;
  d: path("M25.902 24.184a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.113l.037.003a.4.4 0 1 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.053-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.afioo-bwu {
  stop-color: var(--svg-color--53adfc, #53ADFC);
}

.ahdfc9bvs {
  d: path("m19.065 3.331l.271.135c.476.237.748.777.646 1.351l-.374 1.925c-.033.198-.165.332-.362.337h-.011s.033-.574.067-.911c.028-.275-.02-.358-.271-.608a.8.8 0 0 1-.238-.54v-.54a.36.36 0 0 0-.272-.338c-.407-.102-1.256-.27-2.479-.27s-2.072.168-2.479.27a.33.33 0 0 0-.272.337v.54a.67.67 0 0 1-.237.54l-.102.102c-.136.101-.204.304-.204.473c.034.371.068.912.068.912l-.031-.001a.4.4 0 0 1-.377-.337l-.373-1.925c-.068-.54.204-1.08.679-1.317l.272-.135c.17-.101.34-.236.51-.371l.61-.642a1.24 1.24 0 0 1 1.393-.202c.34.1.713.1 1.053 0a1.53 1.53 0 0 1 1.494.337l.51.507c.135.169.305.27.509.371");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.at1qw5b4i {
  cx: 13.008px;
  cy: 7.432px;
  r: 0.63px;
}

.au2cdjbqa {
  fill-rule: evenodd;
  d: path("M5.825 23.762a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8c.226 0 .852-.06 1.466-.364a.4.4 0 0 1 .537.18");
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
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

.bakt0qbwy {
  stop-color: var(--svg-color--3482d0, #3482D0);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.crrluq_8b {
  stop-color: var(--svg-color--2b0c0a, #2B0C0A);
  stop-opacity: 0;
}

.d-f_cevwl {
  stop-color: var(--svg-color--4a3532, #4A3532);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.ddt4h9ktn {
  stop-color: var(--svg-color--432e2c, #432E2C);
  stop-opacity: 0;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dzzs3_bwg {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M6.818 24.409c.14.17.272.303.101.443c-.565.464-.934.651-1.193.783l-.072.037a.4.4 0 1 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.e5bi16n_y {
  stop-color: var(--svg-color--2f0c0a, #2F0C0A);
}

.e72vc5glc {
  d: path("M18.892 11.39v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.56-1.285-.894");
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ept1d-nvv {
  stop-color: var(--svg-color--655351, #655351);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fn3z_sbxx {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.291c-.25-.145-.847-.51-1.234-.804");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fozz65l2p {
  stop-color: var(--svg-color--625250, #625250);
  stop-opacity: 0;
}

.fpvljrbim {
  fill: var(--svg-color--47312f, #47312F);
  d: path("M9.755 16.317c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.651-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.704c.875-.499 3.37-2.968 4.011-3.605c.537-.535.64-1.215.875-3.197");
}

.fr4oj_g5z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.144 4.386v.569c-.005.094-.045.304-.164.393");
}

.ft5dv1b6b {
  fill: none;
}

.fznz2mbxx {
  stop-color: var(--svg-color--4b322f, #4B322F);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g4-rnpbiv {
  d: path("M10.236 28.174c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.17.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.gfswv02mg {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.772 7.252l-.336 1.076a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443l-.337-1.076c-.072-.239-.408-.239-.484 0");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.h1j0-fblz {
  stop-color: var(--svg-color--3181d9, #3181D9);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hb3e6irsp {
  d: path("m15.772 7.252l-.336 1.076a.34.34 0 0 0 .33.443h.497a.342.342 0 0 0 .33-.443l-.337-1.076c-.072-.239-.408-.239-.484 0");
}

.hfnjpubec {
  stop-color: var(--svg-color--3c2826, #3C2826);
}

.hikihhbgc {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M26.175 23.762a.4.4 0 0 0 .18.536c.754.374 1.51.448 1.823.448a.4.4 0 0 0 0-.8c-.226 0-.852-.06-1.466-.364a.4.4 0 0 0-.537.18");
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

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
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

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.iu4sfzbng {
  stop-color: var(--svg-color--543b37, #543B37);
  stop-opacity: 0;
}

.j_m47xbqb {
  d: path("M13.22 24.55h-1.429a1 1 0 0 0-.943.67c-.408 1.17-.96 2.764-1.032 3.001c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j873t3pix {
  fill-rule: evenodd;
  d: path("M26.175 23.762a.4.4 0 0 0 .18.536c.754.374 1.51.448 1.823.448a.4.4 0 0 0 0-.8c-.226 0-.852-.06-1.466-.364a.4.4 0 0 0-.537.18");
}

.k-fq99sbh {
  stop-color: var(--svg-color--62514e, #62514E);
  stop-opacity: 0;
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.keibw1bxy {
  stop-color: var(--svg-color--398dce, #398DCE);
  stop-opacity: 0;
}

.khd1c0n-i {
  stop-color: var(--svg-color--351916, #351916);
  stop-opacity: 0;
}

.kn73ixb2p {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.16 9.162c.246.128.54.202.854.202c.316 0 .607-.074.854-.202a.15.15 0 0 1 .174.028a.14.14 0 0 1 .016.176m-1.898-.204l1.856.177m-1.856-.177a.15.15 0 0 0-.175.03a.14.14 0 0 0-.015.175m.19-.205l-.149.177m2.047.027l-.042-.027m.042.027l-.042-.027m.042.027a1.25 1.25 0 0 1-1.044.558a1.25 1.25 0 0 1-1.044-.557m2.046-.028a1.2 1.2 0 0 1-1.002.535c-.421 0-.79-.214-1.003-.535m-.041.028l.041-.028m-.041.028l.041-.028");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lehanccnj {
  stop-color: var(--svg-color--512d27, #512D27);
  stop-opacity: 0;
}

.lg8towb3y {
  stop-color: var(--svg-color--634f4b, #634F4B);
}

.ltpsj2n6q {
  stop-color: var(--svg-color--3c515d, #3C515D);
}

.ltu6qk3sw {
  cx: 19.032px;
  cy: 7.433px;
  r: 1.057px;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
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

.mxxvki8iv {
  cx: 19.031px;
  cy: 7.432px;
  r: 0.63px;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n55l0rxro {
  stop-color: var(--svg-color--351916, #351916);
}

.n9h2xzfye {
  stop-color: var(--svg-color--2f0c0a, #2F0C0A);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.njoad_bkl {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M6.099 24.184a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.113l-.037.003a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-0p8ab1g {
  stop-color: var(--svg-color--391816, #391816);
  stop-opacity: 0;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.onaimccwi {
  fill-rule: evenodd;
  d: path("M25.182 24.409c-.14.17-.272.303-.101.443c.565.464.934.651 1.193.783l.072.037a.4.4 0 0 0 .367-.711l-.074-.038a5 5 0 0 1-1.051-.69c-.17-.14-.266.005-.406.176");
}

.onbt7cb6a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.065 5.619c.273-.048.804-.034 1.171.252");
}

.otxey-b4h {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.84 7.355l-.52 1.076c-.064.222.09.443.31.443h.466c.22 0 .374-.225.31-.443l-.316-1.076c-.068-.238-.18-.238-.25 0");
}

.oyl2pbcaf {
  d: path("m18.524 3.871l-1.949.65a.663.663 0 0 0 .298 1.286l1.937-.26z");
}

.p5j2ywblw {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.502c-.398 0-.893.047-1.58-.109");
}

.pc6ft5bqj {
  stop-color: var(--svg-color--2b0c0a, #2B0C0A);
}

.pdvw2hfdl {
  stop-color: var(--svg-color--634f4b, #634F4B);
  stop-opacity: 0;
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.phf6igbvb {
  stop-color: var(--svg-color--62514e, #62514E);
}

.pk5i2pb0j {
  stop-color: var(--svg-color--62514f, #62514F);
}

.pmwpwjbcd {
  cx: 13.008px;
  cy: 7.433px;
  r: 1.057px;
}

.qb45jbc1d {
  fill-rule: evenodd;
  d: path("M6.099 24.184a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.113l-.037.003a.4.4 0 1 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075c.155-.053.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qhpil-b3e {
  d: path("M13.83 21.56H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.ql0bmtmgm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.76 5.947c.208-.183.66-.376 1.22-.286");
}

.qxv17obmu {
  d: path("M18.517 21.56h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.rhyhzvq2c {
  cx: 19.031px;
  cy: 7.432px;
  r: 0.63px;
  fill: var(--svg-color--463133, #463133);
}

.rm-es7b9q {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.252a3.8 3.8 0 0 1-1.773-.437");
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

.rx6_xs15m {
  stop-color: var(--svg-color--3d84ae, #3D84AE);
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

.t_lyt9btm {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M18.37 5.71h-.002v-.001l-.004-.003l-.007-.006a1 1 0 0 0-.098-.068a1.6 1.6 0 0 0-.266-.133a1.8 1.8 0 0 0-.945-.1a.338.338 0 0 0 .105.667a1.12 1.12 0 0 1 .747.14l.04.026a.338.338 0 0 0 .43-.522");
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

.tej0dgbcx {
  fill-rule: evenodd;
  d: path("M26.304 23.284a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
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

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ufa4e1bue {
  d: path("m13.447 24.55l-1.578-2.99h8.301l-1.551 2.99z");
}

.ufs3b81ci {
  d: path("M17.627 28.174h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
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

.vat8zbb1h {
  fill: var(--svg-color--4b322f, #4B322F);
  fill-rule: evenodd;
  d: path("M26.304 23.284a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136l.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.003c-.286.007-.656.017-1.045-.103a.4.4 0 0 0-.5.266");
}

.vcvz10bee {
  d: path("M22.32 16.317c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.651.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.704c-.874-.499-3.37-2.968-4.01-3.605c-.538-.535-.641-1.215-.876-3.197");
}

.vd3_8lo3u {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m19.065 3.331l.271.135c.476.237.748.777.646 1.351l-.374 1.925c-.033.198-.165.332-.362.337h-.011s.033-.574.067-.911c.028-.275-.02-.358-.271-.608a.8.8 0 0 1-.238-.54v-.54a.36.36 0 0 0-.272-.338c-.407-.102-1.256-.27-2.479-.27s-2.072.168-2.479.27a.33.33 0 0 0-.272.337v.54a.67.67 0 0 1-.237.54l-.102.102c-.136.101-.204.304-.204.473c.034.371.068.912.068.912l-.031-.001a.4.4 0 0 1-.377-.337l-.373-1.925c-.068-.54.204-1.08.679-1.317l.272-.135c.17-.101.34-.236.51-.371l.61-.642a1.24 1.24 0 0 1 1.393-.202c.34.1.713.1 1.053 0a1.53 1.53 0 0 1 1.494.337l.51.507c.135.169.305.27.509.371");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vr111b3hw {
  d: path("M12.785 7.045h.031s-.034-.54-.068-.911c0-.169.068-.372.204-.473l.102-.101a.67.67 0 0 0 .237-.54v-.54a.33.33 0 0 1 .272-.338c.408-.102 1.257-.27 2.48-.27c1.222 0 2.07.168 2.478.27a.36.36 0 0 1 .272.337v.54a.8.8 0 0 0 .238.54c.318.224.298.346.271.609c-.033.337-.067.911-.067.911h.011l-.168 2.506c-.102 1.12-.983 1.902-2.033 1.902h-2.033c-1.084 0-1.93-.781-2.032-1.902z");
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

.wd5n0p1ub {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.01a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wsizjkbjw {
  stop-color: var(--svg-color--502822, #502822);
}

.wtx0-zb9b {
  d: path("M18.892 11.39v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.417 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x7f4i0bbo {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m13.625 5.71l.002-.001l.003-.003l.007-.006a1 1 0 0 1 .098-.068a1.8 1.8 0 0 1 1.21-.234a.338.338 0 1 1-.104.668a1.12 1.12 0 0 0-.747.14l-.04.026a.338.338 0 0 1-.43-.521");
}

.x81pqcclg {
  fill-rule: evenodd;
  d: path("M5.697 23.284a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136l-.124-.002a.4.4 0 0 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.103a.4.4 0 0 1 .5.266");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y8dgjevrz {
  stroke: var(--svg-color--614f4d, #614F4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.983c.41-.067 1.204-.313 1.59-.645");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
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

.z321yabtz {
  stop-color: var(--svg-color--d3612e, #D3612E);
  stop-opacity: 0;
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

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
