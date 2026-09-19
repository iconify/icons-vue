<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixyCdPd)" class="l85o48s_p"/><path fill="url(#ipBbTGH)" class="l85o48s_p"/><path fill="url(#iIyOFjc)" class="l85o48s_p"/><g filter="url(#iPUCzTd)"><rect fill="url(#ixnJbfc)" class="ur0q6myog"/></g><path fill="url(#iXqpbyd)" class="lk8agc7qm"/><path fill="url(#iXWIt6d)" class="zeh3-9btv"/><path fill="url(#iY37LHt)" class="zeh3-9btv"/><path fill="url(#ia3x7od)" class="zeh3-9btv"/><g filter="url(#iRmGsYd)"><rect fill="url(#iSIUFTL)" class="yxue5zb_q"/></g><path fill="url(#i0kPruz)" class="fo6x_v8nn"/><path fill="url(#iWiEGpP)" class="w-kg8ibqe"/><path fill="url(#iEfJITd)" class="ysd9y5b6j"/><g filter="url(#iri6SQb)"><circle fill="url(#ia4yq7l)" class="r2a89zbrg"/></g><g filter="url(#iViTOhc)"><circle fill="url(#iVJqaxA)" class="d99syqb2c"/></g><g filter="url(#iH0doxc)"><path fill="url(#imaTwVZ)" class="tuctcebum"/></g><path fill="url(#iJ1Q57d)" class="ukar1r8no"/><path fill="url(#i0Bw0rc)" class="ukar1r8no"/><g filter="url(#i66n9je)"><path fill="url(#iy4mQBB)" class="jpyjveb4m"/></g><g filter="url(#ie9mfoe)"><path fill="url(#iLgOPJS)" class="jirbqdbwc"/></g><path fill="url(#ih81Ivu)" class="hoi7opb6j"/><path fill="url(#iumXoIx)" class="hoi7opb6j"/><path fill="url(#ihBt0me)" class="e_sl96bsv"/><path class="p8wqmd2zh"/><path fill="url(#iq3YQjd)" class="e7gjqi8ys"/><path fill="url(#iFbiIhd)" class="e7gjqi8ys"/><path fill="url(#iWPIBPc)" class="e7gjqi8ys"/><path fill="url(#ixPjA3d)" class="e7gjqi8ys"/><path fill="url(#i1nK1Ab)" class="sxosrgbtb"/><path fill="url(#ioeMb7c)" class="sxosrgbtb"/><path fill="url(#i29Je3b)" class="sxosrgbtb"/><rect fill="url(#irMylcd)" class="ere_8bytc"/><rect fill="url(#ikkikLd)" class="ere_8bytc"/><g filter="url(#ijOOHPd)"><path class="yjdgn6b_j"/></g><path fill="url(#i6orjQS)" class="m1vkpy93k"/><path fill="url(#iGJKOpd)" class="z4yf8urbu"/><path fill="url(#icF06hd)" class="z4yf8urbu"/><g filter="url(#iQMfwLb)"><path fill="url(#iqquihd)" class="qo540acvo"/></g><circle fill="url(#ika0Zcc)" class="bu_r-xb9o"/><g filter="url(#ikNRcNb)"><path fill="url(#izP9I8c)" class="c8mc5lb3q"/></g><g filter="url(#igYqjQr)"><path class="y4t29_brm"/><path fill="url(#i8Yzdid)" class="va_og8bjg"/></g><circle class="k1ssry61t"/><g filter="url(#iLS8D4c)"><circle class="u2qx5z-_o"/></g><g filter="url(#i2K3XMc)"><circle fill="url(#ifepIqe)" class="hhkrbqb1q"/></g><g filter="url(#iGuboSc)"><circle class="sxkmmlbsf"/></g><path fill="url(#iB6CUHc)" class="u6oqnmb2f"/><path fill="url(#ijrTyUc)" class="u6oqnmb2f"/><path fill="url(#i6qdoMe)" class="u6oqnmb2f"/><path fill="url(#icINr8d)" class="u6oqnmb2f"/><path fill="url(#iqXRE8b)" class="u6oqnmb2f"/><g filter="url(#iE4Yerj)"><path class="qtj9wrb5x"/></g><g filter="url(#iJgylwO)"><path class="gt-u0ibhu"/></g><g filter="url(#iGZN14d)"><path class="hc0ur6bxm"/></g><path fill="url(#iPcHUgR)" class="s8chfwbjn"/><path stroke="url(#i0nRj2v)" class="rdoim-7up"/><g clip-rule="evenodd" filter="url(#iwh0hAd)" class="d2kvgvbvc"><path class="n32gwe1dv"/><path fill="url(#ilwk4Gb)" class="xdhhnfb5a"/></g><g clip-rule="evenodd" filter="url(#iWuB0vc)" class="d2kvgvbvc"><path class="yz-34ac1v"/><path fill="url(#iGkzCNJ)" class="sn3c2m2px"/></g><g filter="url(#iIfeKPd)"><path fill="url(#icjbRdd)" class="u7iotewrx"/></g><g filter="url(#iTrQVdb)"><path class="aylk1bs8c"/><path fill="url(#iOpUbTk)" class="ve43lhu_q"/></g><g filter="url(#i7mLfsd)"><path class="j08lkhbcq"/><path fill="url(#ivmhtze)" class="rkj830b-m"/></g><path class="iy-h2pb7y"/><path fill="url(#ieR84QX)" class="awuuptbvb"/><path fill="url(#iQOuxPc)" class="awuuptbvb"/><path fill="url(#iykAPRb)" class="pgoxgbbvl"/><path fill="url(#iSAhnmr)" class="pgoxgbbvl"/><path fill="url(#ie3iZzn)" class="pgoxgbbvl"/><rect fill="url(#id4cUyb)" class="v02cndbaa"/><rect fill="url(#iH9VxWd)" class="v02cndbaa"/><rect fill="url(#izXHRhc)" class="v02cndbaa"/><g filter="url(#ib6KYRi)"><path fill="url(#iziq8cd)" class="ou9__5b0t"/></g><g filter="url(#iy1Oout)"><path fill="url(#ivtoXld)" class="n3ye58bzq"/></g><defs><radialGradient id="iWiEGpP" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93665 0 0 -14.2152 18.198 10.65)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="nwzbg7kjd"/><stop offset="1" class="ff1no10hm"/></radialGradient><radialGradient id="ia4yq7l" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .33985 -.31868 -.36629 15.348 12.754)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="g23oo4bgx"/><stop offset=".844" class="ccf_1kkne"/></radialGradient><radialGradient id="iVJqaxA" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .33985 -.31868 -.36629 15.349 13.998)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="g23oo4bgx"/><stop offset=".844" class="ccf_1kkne"/></radialGradient><radialGradient id="imaTwVZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.40625 -1.70424 0 12.93 11.462)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="xn9w1abgm"/><stop offset="1" class="glqr6tbiu"/></radialGradient><radialGradient id="iJ1Q57d" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.84375 -.87152 0 19.07 8.587)" gradientUnits="userSpaceOnUse"><stop class="wb950ymmz"/><stop offset="1" class="horgfru7v"/></radialGradient><radialGradient id="iy4mQBB" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.79687 -1.45313 0 19.356 15.852)" gradientUnits="userSpaceOnUse"><stop class="a6n1f6vew"/><stop offset=".759" class="yg7pzjrrr"/></radialGradient><radialGradient id="iLgOPJS" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24304 0 0 -1.64063 13.8 16.024)" gradientUnits="userSpaceOnUse"><stop offset=".067" class="um82sc42n"/><stop offset="1" class="s_-wxsbqy"/></radialGradient><radialGradient id="ih81Ivu" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.71484 1.28125 0 19.137 15.505)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="g9x2u_bdo"/><stop offset="1" class="xq-_dvbek"/></radialGradient><radialGradient id="ihBt0me" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6836 1.05764 0 13.332 15.505)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="c7v7pcmer"/><stop offset="1" class="zqw5laobm"/></radialGradient><radialGradient id="iWPIBPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 0 0 2.48437 13.543 15.54)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="n219yccxp"/><stop offset="1" class="gxi_vjppo"/></radialGradient><radialGradient id="ioeMb7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.90625 0 0 -2.3925 18.387 15.946)" gradientUnits="userSpaceOnUse"><stop offset=".02" class="t4dh35myh"/><stop offset="1" class="i7ndys8gs"/></radialGradient><radialGradient id="irMylcd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.85938 0 0 -1.14453 18.824 29.435)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="i-78nbbad"/><stop offset="1" class="s6odk1prq"/></radialGradient><radialGradient id="i6orjQS" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4961 -.48047 0 15.992 8.696)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="c9neslb2j"/><stop offset="1" class="f46cj4b8l"/></radialGradient><radialGradient id="iGJKOpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.789 -.58488 0 16.212 9.192)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="acs5nir-x"/><stop offset="1" class="h6piqgbzt"/></radialGradient><radialGradient id="iqquihd" cx="0" cy="0" r="1" gradientTransform="rotate(-134.885 10.21 1.053)scale(2.08132 2.97709)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="nikzy_-cb"/><stop offset="1" class="mqkt3cb4f"/></radialGradient><radialGradient id="ika0Zcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7002 -.71152 .94265 -.92766 16.468 8.135)" gradientUnits="userSpaceOnUse"><stop class="hksqhb7pw"/><stop offset="1" class="e28-fobpy"/></radialGradient><radialGradient id="izP9I8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01563 .26563 -.73569 -2.81287 15.45 10.118)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="njqqz6bzb"/><stop offset="1" class="dml7oebfc"/></radialGradient><radialGradient id="i8Yzdid" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 .13484 -.29968 2.50018 16.746 9.655)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="qo83b0bvk"/><stop offset="1" class="tw5tjbb2o"/></radialGradient><radialGradient id="ifepIqe" cx="0" cy="0" r="1" gradientTransform="rotate(116.086 7.597 8.171)scale(1.15268)" gradientUnits="userSpaceOnUse"><stop class="b3efjmbny"/><stop offset="1" class="oe76mfbgt"/></radialGradient><radialGradient id="iB6CUHc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.44189 0 0 -3.38604 17.938 6.446)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="b2wqlhblw"/><stop offset="1" class="vv-msqb-k"/></radialGradient><radialGradient id="icINr8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.4585 -3.68725 0 16.008 5.394)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="a9aeho70f"/><stop offset="1" class="xfuivvcjb"/></radialGradient><radialGradient id="iqXRE8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.24169 2.39385 0 16.008 7.737)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="fn53uibcx"/><stop offset="1" class="egfdaabnx"/></radialGradient><radialGradient id="iPcHUgR" cx="0" cy="0" r="1" gradientTransform="matrix(-.14063 -.0586 .06333 -.152 16.16 5.882)" gradientUnits="userSpaceOnUse"><stop class="dvemdccmr"/><stop offset="1" class="womn98bvo"/></radialGradient><radialGradient id="i0nRj2v" cx="0" cy="0" r="1" gradientTransform="matrix(.1211 -.20312 .60938 .36328 15.472 6.675)" gradientUnits="userSpaceOnUse"><stop class="mh0y9xb1s"/><stop offset="1" class="mhjnt-b0p"/></radialGradient><radialGradient id="ilwk4Gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40003 -.20312 .11015 -.21693 17.435 4.5)" gradientUnits="userSpaceOnUse"><stop class="jf48uxb1h"/><stop offset="1" class="smyp-yriu"/></radialGradient><radialGradient id="iGkzCNJ" cx="0" cy="0" r="1" gradientTransform="matrix(.40002 -.20313 .11015 .21692 14.56 4.501)" gradientUnits="userSpaceOnUse"><stop class="yil8tobop"/><stop offset="1" class="gxoxaab9w"/></radialGradient><radialGradient id="iOpUbTk" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.13281 -.2467 0 15.773 4.946)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="g5xdx-p6a"/><stop offset="1" class="e3gx51wtu"/></radialGradient><radialGradient id="ivmhtze" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.13281 -.2467 0 17.594 4.946)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="g5xdx-p6a"/><stop offset="1" class="e3gx51wtu"/></radialGradient><radialGradient id="ieR84QX" cx="0" cy="0" r="1" gradientTransform="rotate(143.094 8.168 4.254)scale(2.51094 1.14233)" gradientUnits="userSpaceOnUse"><stop class="aj_tw3j1o"/><stop offset=".77" class="s3_x2f0ah"/></radialGradient><radialGradient id="iQOuxPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.85157 -1.43359 1.14859 -.68228 15.129 3.544)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="b3u0jug2t"/><stop offset="1" class="uay8mzbfc"/></radialGradient><radialGradient id="iykAPRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29687 2.45313 0 16.98 3.9)" gradientUnits="userSpaceOnUse"><stop class="tboymoxmd"/><stop offset="1" class="n6sxbw5zw"/></radialGradient><radialGradient id="iSAhnmr" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90259 0 0 -.10938 18.008 3.247)" gradientUnits="userSpaceOnUse"><stop class="i8extwu4m"/><stop offset="1" class="esdd1ct8r"/></radialGradient><radialGradient id="ie3iZzn" cx="0" cy="0" r="1" gradientTransform="matrix(.48438 -1.09375 2.42414 1.07355 14.332 4.118)" gradientUnits="userSpaceOnUse"><stop class="sfyf3vb1f"/><stop offset="1" class="nn4_9sbfl"/></radialGradient><radialGradient id="id4cUyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77344 3.42187 0 17.34 4.532)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="gind88bhl"/><stop offset="1" class="ck-8zfmjj"/></radialGradient><linearGradient id="ixyCdPd" x1="15.193" x2="15.193" y1="25.493" y2="28.04" gradientUnits="userSpaceOnUse"><stop class="sfy4td0pz"/><stop offset="1" class="nbnm83bni"/></linearGradient><linearGradient id="ipBbTGH" x1="14.301" x2="14.645" y1="25.899" y2="25.899" gradientUnits="userSpaceOnUse"><stop class="bc6yq6ueq"/><stop offset="1" class="ra0evbbul"/></linearGradient><linearGradient id="iIyOFjc" x1="15.193" x2="15.193" y1="24.845" y2="25.587" gradientUnits="userSpaceOnUse"><stop class="wp-tbrcxl"/><stop offset="1" class="ajiye6oer"/></linearGradient><linearGradient id="ixnJbfc" x1="15.461" x2="15.461" y1="24.524" y2="27.556" gradientUnits="userSpaceOnUse"><stop offset=".196" class="u7ziimuel"/><stop offset="1" class="unygv2b0a"/></linearGradient><linearGradient id="iXqpbyd" x1="15.199" x2="15.199" y1="24.79" y2="27.009" gradientUnits="userSpaceOnUse"><stop class="jq11z6_uy"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="iXWIt6d" x1="16.807" x2="16.807" y1="25.493" y2="28.04" gradientUnits="userSpaceOnUse"><stop class="sfy4td0pz"/><stop offset="1" class="nbnm83bni"/></linearGradient><linearGradient id="iY37LHt" x1="15.914" x2="16.258" y1="25.899" y2="25.899" gradientUnits="userSpaceOnUse"><stop class="aqr6t6bpr"/><stop offset="1" class="j6it256gw"/></linearGradient><linearGradient id="ia3x7od" x1="16.807" x2="16.807" y1="24.845" y2="25.587" gradientUnits="userSpaceOnUse"><stop class="wp-tbrcxl"/><stop offset="1" class="ajiye6oer"/></linearGradient><linearGradient id="iSIUFTL" x1="17.051" x2="17.051" y1="24.524" y2="27.556" gradientUnits="userSpaceOnUse"><stop offset=".196" class="u7ziimuel"/><stop offset="1" class="unygv2b0a"/></linearGradient><linearGradient id="i0kPruz" x1="16.813" x2="16.813" y1="24.79" y2="27.009" gradientUnits="userSpaceOnUse"><stop class="jq11z6_uy"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="iEfJITd" x1="16.047" x2="16.047" y1="8.384" y2="10.759" gradientUnits="userSpaceOnUse"><stop class="krs2oef1o"/><stop offset="1" class="iwbnrv_7v"/></linearGradient><linearGradient id="i0Bw0rc" x1="17.912" x2="18.864" y1="12.068" y2="12.068" gradientUnits="userSpaceOnUse"><stop class="hzpn9-n5u"/><stop offset="1" class="c-948sbmo"/></linearGradient><linearGradient id="iumXoIx" x1="19.535" x2="19.215" y1="14.931" y2="15.345" gradientUnits="userSpaceOnUse"><stop offset=".265" class="chx2sabhv"/><stop offset="1" class="kralbibvz"/></linearGradient><linearGradient id="iq3YQjd" x1="14.901" x2="14.901" y1="15.54" y2="22.399" gradientUnits="userSpaceOnUse"><stop class="qj-kypbtd"/><stop offset="1" class="lp1xml6ym"/></linearGradient><linearGradient id="iFbiIhd" x1="13.802" x2="14.418" y1="20.806" y2="20.806" gradientUnits="userSpaceOnUse"><stop class="p7a95-bzg"/><stop offset="1" class="j7b797_jr"/></linearGradient><linearGradient id="ixPjA3d" x1="16" x2="15.371" y1="18.29" y2="18.29" gradientUnits="userSpaceOnUse"><stop class="lxo6977ad"/><stop offset="1" class="ui0e-xb0n"/></linearGradient><linearGradient id="i1nK1Ab" x1="17.099" x2="17.099" y1="15.54" y2="24.923" gradientUnits="userSpaceOnUse"><stop class="v1nhr4b7v"/><stop offset="1" class="wgnseactl"/></linearGradient><linearGradient id="i29Je3b" x1="15.793" x2="16.84" y1="20.79" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="kmu00qb0d"/><stop offset="1" class="pfcwbwb-a"/></linearGradient><linearGradient id="ikkikLd" x1="16.004" x2="16.004" y1="30.056" y2="29.212" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zr5tarbij"/><stop offset="1" class="jhgdrfbkn"/></linearGradient><linearGradient id="icF06hd" x1="15.582" x2="15.801" y1="10.149" y2="10.157" gradientUnits="userSpaceOnUse"><stop class="erljhfniy"/><stop offset="1" class="dyhqpo0im"/></linearGradient><linearGradient id="ijrTyUc" x1="16.008" x2="16.008" y1="4.306" y2="5.103" gradientUnits="userSpaceOnUse"><stop class="ic68lzjvk"/><stop offset="1" class="ftgtvbsod"/></linearGradient><linearGradient id="i6qdoMe" x1="14.214" x2="15.027" y1="6.144" y2="6.097" gradientUnits="userSpaceOnUse"><stop offset=".214" class="odz75hbaa"/><stop offset="1" class="lu2tmpbtt"/></linearGradient><linearGradient id="icjbRdd" x1="16.001" x2="16.001" y1="4.74" y2="6.106" gradientUnits="userSpaceOnUse"><stop class="uizhbqnqd"/><stop offset="1" class="rosr-ik5x"/></linearGradient><linearGradient id="iH9VxWd" x1="16.496" x2="16.496" y1="4.376" y2="4.243" gradientUnits="userSpaceOnUse"><stop class="zo99rm8ts"/><stop offset="1" class="qo_ozxf1o"/></linearGradient><linearGradient id="izXHRhc" x1="16.785" x2="16.785" y1="3.853" y2="3.985" gradientUnits="userSpaceOnUse"><stop offset=".464" class="x6e43ob7y"/><stop offset="1" class="p2ms6zbbw"/></linearGradient><linearGradient id="iziq8cd" x1="15.794" x2="15.794" y1="24.727" y2="15.727" gradientUnits="userSpaceOnUse"><stop class="koq2unbkt"/><stop offset="1" class="uj-vi6bqm"/></linearGradient><linearGradient id="ivtoXld" x1="18.029" x2="18.029" y1="24.727" y2="15.727" gradientUnits="userSpaceOnUse"><stop class="koq2unbkt"/><stop offset="1" class="uj-vi6bqm"/></linearGradient><filter id="iPUCzTd" width="1.017" height="3.431" x="14.952" y="24.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_681" stdDeviation=".1"/></filter><filter id="iRmGsYd" width="1.025" height="3.431" x="16.538" y="24.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_681" stdDeviation=".1"/></filter><filter id="iri6SQb" width=".808" height=".808" x="14.637" y="12.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.164706 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_681"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_681" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_681"/></filter><filter id="iViTOhc" width=".808" height=".808" x="14.637" y="13.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.164706 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_681"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_681" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_681"/></filter><filter id="iH0doxc" width="1.993" height="7.488" x="12.059" y="7.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.313726 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="i66n9je" width="1.343" height="2.384" x="18.198" y="14.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.372549 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="ie9mfoe" width="1.243" height="2.484" x="12.559" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.34902 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="ijOOHPd" width="2.609" height="1.975" x="14.632" y="7.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_681" stdDeviation=".125"/></filter><filter id="iQMfwLb" width="2.109" height="1.525" x="14.946" y="7.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.596078 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="ikNRcNb" width="2.082" height="5.1" x="14.019" y="7.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.12549 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="igYqjQr" width="2.232" height="5.1" x="15.9" y="7.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.168627 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.152941 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_681" result="effect2_innerShadow_4002_681"/></filter><filter id="iLS8D4c" width="1.244" height="1.244" x="13.615" y="4.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_681" stdDeviation=".1"/></filter><filter id="i2K3XMc" width="1.342" height="1.342" x="17.149" y="4.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.419608 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="iGuboSc" width="1.178" height="1.178" x="17.181" y="4.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_681" stdDeviation=".075"/></filter><filter id="iE4Yerj" width=".541" height=".892" x="13.697" y="4.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.0705882 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="iJgylwO" width=".521" height=".894" x="17.798" y="4.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.0901961 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="iGZN14d" width="1.289" height="1.691" x="15.353" y="4.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_681" stdDeviation=".125"/></filter><filter id="iwh0hAd" width="1.018" height=".57" x="16.467" y="4.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.0980392 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="iWuB0vc" width="1.018" height=".57" x="14.559" y="4.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.109804 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="iIfeKPd" width="3.598" height="1.366" x="14.202" y="4.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="iTrQVdb" width="1.455" height="1.26" x="14.418" y="4.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.105882 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="i7mLfsd" width="1.455" height="1.26" x="16.238" y="4.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.105882 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_681"/></filter><filter id="ib6KYRi" width="2.284" height="10.3" x="13.987" y="15.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_681" stdDeviation=".325"/></filter><filter id="iy1Oout" width="2.284" height="10.3" x="16.221" y="15.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_681" stdDeviation=".325"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-suit-levitating-medium" /></template>
<style>
.a6n1f6vew {
  stop-color: var(--svg-color--c49887, #C49887);
}

.a9aeho70f {
  stop-color: var(--svg-color--9d6874, #9D6874);
  stop-opacity: 0;
}

.acs5nir-x {
  stop-color: var(--svg-color--63477d, #63477D);
}

.aj_tw3j1o {
  stop-color: var(--svg-color--675d72, #675D72);
}

.ajiye6oer {
  stop-color: var(--svg-color--422f57, #422F57);
  stop-opacity: 0;
}

.aqr6t6bpr {
  stop-color: var(--svg-color--311943, #311943);
}

.awuuptbvb {
  d: path("M14.083 3.357v-.461c-.012-.193.108-.636.526-.774c.383-.144.694-.002.963.12c.155.07.296.134.428.134c.133 0 .274-.064.429-.134c.27-.122.58-.264.963-.12c.418.138.538.581.526.774v.46z");
}

.aylk1bs8c {
  fill: var(--svg-color--4b3561, #4B3561);
  d: path("M14.418 5.11a.25.25 0 0 1 .25-.25h.805a.3.3 0 0 1 .3.3v.36a.5.5 0 0 1-.5.5h-.355a.5.5 0 0 1-.5-.5z");
}

.b2wqlhblw {
  stop-color: var(--svg-color--c2987f, #C2987F);
}

.b3efjmbny {
  stop-color: var(--svg-color--ba9a88, #BA9A88);
}

.b3u0jug2t {
  stop-color: var(--svg-color--362c40, #362C40);
}

.bc6yq6ueq {
  stop-color: var(--svg-color--685f73, #685F73);
}

.bu_r-xb9o {
  cx: 16px;
  cy: 7.423px;
  r: 0.77px;
}

.c-948sbmo {
  stop-color: var(--svg-color--50445d, #50445D);
  stop-opacity: 0;
}

.c7v7pcmer {
  stop-color: var(--svg-color--dac0f3, #DAC0F3);
}

.c8mc5lb3q {
  d: path("M14.983 9.27V7.46l-.423-.305c-.12.117-.134.4-.13.53l.032 1.033l-.352.03a.1.1 0 0 0-.09.105c.085 1.196.41 1.864.831 2.41c.289.373.827.75 1.123.89c.02.01.035-.013.02-.03c-.842-.924-1.024-2.244-1.011-2.852");
}

.c9neslb2j {
  stop-color: var(--svg-color--534063, #534063);
}

.ccf_1kkne {
  stop-color: var(--svg-color--31273b, #31273B);
}

.chx2sabhv {
  stop-color: var(--svg-color--b4a3c5, #B4A3C5);
}

.ck-8zfmjj {
  stop-color: var(--svg-color--3a2e46, #3A2E46);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d99syqb2c {
  cx: 15.141px;
  cy: 14.157px;
  r: 0.254px;
}

.dml7oebfc {
  stop-color: var(--svg-color--37303e, #37303E);
}

.dvemdccmr {
  stop-color: var(--svg-color--a2807a, #A2807A);
}

.dyhqpo0im {
  stop-color: var(--svg-color--412c57, #412C57);
  stop-opacity: 0;
}

.e_sl96bsv {
  d: path("M12.559 15.505h1.243v-.48h-1.243z");
}

.e28-fobpy {
  stop-color: var(--svg-color--955b70, #955B70);
}

.e3gx51wtu {
  stop-color: var(--svg-color--5b496d, #5B496D);
  stop-opacity: 0;
}

.e7gjqi8ys {
  d: path("M13.802 15.54H16v9.383h-2.198z");
}

.egfdaabnx {
  stop-color: var(--svg-color--9c647f, #9C647F);
  stop-opacity: 0;
}

.ere_8bytc {
  width: 6.25px;
  height: 1.008px;
  x: 12.879px;
  y: 28.931px;
  rx: 0.504px;
}

.erljhfniy {
  stop-color: var(--svg-color--412c57, #412C57);
}

.esdd1ct8r {
  stop-color: var(--svg-color--634c7c, #634C7C);
  stop-opacity: 0;
}

.f46cj4b8l {
  stop-color: var(--svg-color--43295a, #43295A);
}

.ff1no10hm {
  stop-color: var(--svg-color--48325f, #48325F);
}

.fn53uibcx {
  stop-color: var(--svg-color--9c6188, #9C6188);
}

.fo6x_v8nn {
  d: path("M16.39 24.79h.844v1.797a.422.422 0 0 1-.843 0z");
}

.ft5dv1b6b {
  fill: none;
}

.ftgtvbsod {
  stop-color: var(--svg-color--915f68, #915F68);
  stop-opacity: 0;
}

.g23oo4bgx {
  stop-color: var(--svg-color--4e4a54, #4E4A54);
}

.g5xdx-p6a {
  stop-color: var(--svg-color--5b496d, #5B496D);
}

.g9x2u_bdo {
  stop-color: var(--svg-color--ffefff, #FFEFFF);
}

.gind88bhl {
  stop-color: var(--svg-color--584e64, #584E64);
}

.glqr6tbiu {
  stop-color: var(--svg-color--332c38, #332C38);
}

.gt-u0ibhu {
  fill: var(--svg-color--37272d, #37272D);
  d: path("M17.895 5.17c.049-.005.133-.038.201-.154c.08-.135.148-.55.173-.741h-.471c.154.116.147.187.133.327l-.001.01l-.009.148a6 6 0 0 1-.025.387z");
}

.gxi_vjppo {
  stop-color: var(--svg-color--3e2031, #3E2031);
  stop-opacity: 0;
}

.gxoxaab9w {
  stop-color: var(--svg-color--452c34, #452C34);
  stop-opacity: 0;
}

.h6piqgbzt {
  stop-color: var(--svg-color--473559, #473559);
}

.hc0ur6bxm {
  fill: var(--svg-color--8f655d, #8F655D);
  d: path("m15.837 5.144l-.224.755c-.045.155.064.31.219.31h.33c.155 0 .265-.157.22-.31l-.224-.755a.166.166 0 0 0-.322 0");
}

.hhkrbqb1q {
  cx: 17.77px;
  cy: 5.355px;
  r: 0.621px;
}

.hksqhb7pw {
  stop-color: var(--svg-color--a87979, #A87979);
}

.hoi7opb6j {
  d: path("M19.442 15.505h-1.244v-.48h1.244z");
}

.horgfru7v {
  stop-color: var(--svg-color--5b4b6d, #5B4B6D);
}

.hzpn9-n5u {
  stop-color: var(--svg-color--50445d, #50445D);
}

.i-78nbbad {
  stop-color: var(--svg-color--dbcfe8, #DBCFE8);
}

.i7ndys8gs {
  stop-color: var(--svg-color--402339, #402339);
  stop-opacity: 0;
}

.i8extwu4m {
  stop-color: var(--svg-color--74608b, #74608B);
}

.ic68lzjvk {
  stop-color: var(--svg-color--86515a, #86515A);
}

.iwbnrv_7v {
  stop-color: var(--svg-color--c1add3, #C1ADD3);
}

.iy-h2pb7y {
  fill: var(--svg-color--4b3f57, #4B3F57);
  d: path("M14.083 3.357v-.461c-.012-.193.108-.636.526-.774c.383-.144.694-.002.963.12c.155.07.296.134.428.134c.133 0 .274-.064.429-.134c.27-.122.58-.264.963-.12c.418.138.538.581.526.774v.46z");
}

.j08lkhbcq {
  fill: var(--svg-color--4b3561, #4B3561);
  d: path("M17.594 5.11a.25.25 0 0 0-.25-.25h-.806a.3.3 0 0 0-.3.3v.36a.5.5 0 0 0 .5.5h.356a.5.5 0 0 0 .5-.5z");
}

.j6it256gw {
  stop-color: var(--svg-color--4c3f5d, #4C3F5D);
  stop-opacity: 0;
}

.j7b797_jr {
  stop-color: var(--svg-color--473857, #473857);
  stop-opacity: 0;
}

.jf48uxb1h {
  stop-color: var(--svg-color--594343, #594343);
}

.jhgdrfbkn {
  stop-color: var(--svg-color--a189b8, #A189B8);
  stop-opacity: 0;
}

.jirbqdbwc {
  d: path("M13.802 15.024h-1.243v.992c0 .686.719 1.118 1.243 1.243z");
}

.jpyjveb4m {
  d: path("M18.199 15.024h1.242v.992c0 .686-.718 1.118-1.242 1.243z");
}

.jq11z6_uy {
  stop-color: var(--svg-color--b998d9, #B998D9);
}

.k1ssry61t {
  cx: 14.231px;
  cy: 5.355px;
  r: 0.621px;
  fill: var(--svg-color--7c564f, #7C564F);
}

.kmu00qb0d {
  stop-color: var(--svg-color--2c183c, #2C183C);
}

.koq2unbkt {
  stop-color: var(--svg-color--675087, #675087);
}

.kralbibvz {
  stop-color: var(--svg-color--e7d4fa, #E7D4FA);
  stop-opacity: 0;
}

.krs2oef1o {
  stop-color: var(--svg-color--b59fc5, #B59FC5);
}

.l85o48s_p {
  d: path("M14.387 24.728H16v2.505a.807.807 0 1 1-1.613 0z");
}

.lk8agc7qm {
  d: path("M14.777 24.79h.844v1.797a.422.422 0 0 1-.844 0z");
}

.lp1xml6ym {
  stop-color: var(--svg-color--543873, #543873);
}

.lu2tmpbtt {
  stop-color: var(--svg-color--8a615c, #8A615C);
  stop-opacity: 0;
}

.lxo6977ad {
  stop-color: var(--svg-color--362549, #362549);
}

.m1vkpy93k {
  d: path("M15.787 9.192a2.4 2.4 0 0 1-.36-.656h1.13a3.2 3.2 0 0 1-.332.656z");
}

.mh0y9xb1s {
  stop-color: var(--svg-color--816361, #816361);
}

.mhjnt-b0p {
  stop-color: var(--svg-color--816361, #816361);
  stop-opacity: 0;
}

.mqkt3cb4f {
  stop-color: var(--svg-color--927fa2, #927FA2);
}

.n219yccxp {
  stop-color: var(--svg-color--3e2031, #3E2031);
}

.n32gwe1dv {
  fill: var(--svg-color--3e2132, #3E2132);
  d: path("M16.66 4.535c.267-.025.439.08.48.118a.176.176 0 0 0 .239-.259c-.114-.105-.384-.243-.752-.209a.176.176 0 0 0 .032.35");
}

.n3ye58bzq {
  d: path("M16.871 15.727h.984v9h-.984z");
}

.n6sxbw5zw {
  stop-color: var(--svg-color--53386c, #53386C);
}

.nbnm83bni {
  stop-color: var(--svg-color--6a3f95, #6A3F95);
}

.nikzy_-cb {
  stop-color: var(--svg-color--e5d6f4, #E5D6F4);
}

.njqqz6bzb {
  stop-color: var(--svg-color--4d4852, #4D4852);
}

.nn4_9sbfl {
  stop-color: var(--svg-color--453752, #453752);
  stop-opacity: 0;
}

.nwzbg7kjd {
  stop-color: var(--svg-color--64517b, #64517B);
}

.odz75hbaa {
  stop-color: var(--svg-color--916d61, #916D61);
}

.oe76mfbgt {
  stop-color: var(--svg-color--aa7d75, #AA7D75);
}

.ou9__5b0t {
  d: path("M14.637 15.727h.984v9h-.984z");
}

.p2ms6zbbw {
  stop-color: var(--svg-color--4a3d57, #4A3D57);
  stop-opacity: 0;
}

.p71wtvbay {
  stop-color: var(--svg-color--f3e0ff, #F3E0FF);
}

.p7a95-bzg {
  stop-color: var(--svg-color--595163, #595163);
}

.p8wqmd2zh {
  fill: var(--svg-color--5e4e73, #5E4E73);
  d: path("M13.802 15.54H16v9.383h-2.198z");
}

.pfcwbwb-a {
  stop-color: var(--svg-color--3e2353, #3E2353);
  stop-opacity: 0;
}

.pgoxgbbvl {
  d: path("M13.993 3.347a.1.1 0 0 1 .1-.1h3.815a.1.1 0 0 1 .1.1V3.9h-4.015z");
}

.qj-kypbtd {
  stop-color: var(--svg-color--423053, #423053);
}

.qo_ozxf1o {
  stop-color: var(--svg-color--4a295c, #4A295C);
  stop-opacity: 0;
}

.qo540acvo {
  d: path("M14.946 7.556c0 .342.019.948.479 1.413c.088.09.23.079.31-.018c.081-.101.177-.233.257-.375a.01.01 0 0 1 .017 0c.08.142.176.274.258.375a.207.207 0 0 0 .31.018c.459-.465.478-1.071.478-1.413z");
}

.qo83b0bvk {
  stop-color: var(--svg-color--55525a, #55525A);
  stop-opacity: 0;
}

.qtj9wrb5x {
  fill: var(--svg-color--4a3a39, #4A3A39);
  d: path("M14.078 4.592c0 .086.012.418.022.535l.003.04c-.05-.01-.123-.048-.183-.15c-.08-.136-.149-.551-.173-.742h.49l-.039.04c-.08.059-.12.178-.12.277");
}

.r2a89zbrg {
  cx: 15.141px;
  cy: 12.915px;
  r: 0.254px;
}

.ra0evbbul {
  stop-color: var(--svg-color--685f73, #685F73);
  stop-opacity: 0;
}

.rdoim-7up {
  fill: var(--svg-color--87004d, #87004D);
  stroke-width: var(--svg-stroke-width--0-04px, 0.04px);
  d: path("M15.491 6.38c.146.076.32.12.506.12c.188 0 .36-.044.506-.12a.08.08 0 0 1 .092.014zm0 0a.08.08 0 0 0-.092.015m.092-.016l-.092.016m1.187.08c.032-.048-.023-.104-.074-.078a1.1 1.1 0 0 1-.515.122c-.189 0-.366-.044-.515-.122l-.074.078m1.178 0a.7.7 0 0 1-.589.315a.7.7 0 0 1-.589-.315m1.178 0l.017.011zm-1.178 0l-.016.011m.016-.011l-.016.011m.007-.09a.07.07 0 0 0-.007.09m.007-.09l-.007.09");
}

.rkj830b-m {
  d: path("M17.594 5.11a.25.25 0 0 0-.25-.25h-.806a.3.3 0 0 0-.3.3v.36a.5.5 0 0 0 .5.5h.356a.5.5 0 0 0 .5-.5z");
}

.rosr-ik5x {
  stop-color: var(--svg-color--39294a, #39294A);
}

.s_-wxsbqy {
  stop-color: var(--svg-color--96726d, #96726D);
}

.s3_x2f0ah {
  stop-color: var(--svg-color--52495e, #52495E);
  stop-opacity: 0;
}

.s6odk1prq {
  stop-color: var(--svg-color--96929b, #96929B);
}

.s8chfwbjn {
  d: path("m15.855 5.198l-.198.668c-.04.138.057.275.194.275h.292c.137 0 .234-.14.194-.275l-.198-.668a.147.147 0 0 0-.284 0");
}

.sfy4td0pz {
  stop-color: var(--svg-color--4a3d5b, #4A3D5B);
}

.sfyf3vb1f {
  stop-color: var(--svg-color--453752, #453752);
}

.smyp-yriu {
  stop-color: var(--svg-color--594343, #594343);
  stop-opacity: 0;
}

.sn3c2m2px {
  d: path("M15.335 4.535c-.268-.025-.44.08-.481.118a.176.176 0 0 1-.238-.259c.114-.105.383-.243.752-.209a.176.176 0 0 1-.033.35");
}

.sxkmmlbsf {
  cx: 17.77px;
  cy: 5.355px;
  r: 0.439px;
  fill: var(--svg-color--a17368, #A17368);
}

.sxosrgbtb {
  d: path("M16 15.54h2.198v9.383H16z");
}

.t4dh35myh {
  stop-color: var(--svg-color--402339, #402339);
}

.tboymoxmd {
  stop-color: var(--svg-color--6c5785, #6C5785);
}

.tuctcebum {
  d: path("M12.059 10.704c0-1.737 1.117-2.808 1.743-3.168v7.488h-1.743z");
}

.tw5tjbb2o {
  stop-color: var(--svg-color--55525a, #55525A);
}

.u2qx5z-_o {
  cx: 14.238px;
  cy: 5.355px;
  r: 0.422px;
  fill: var(--svg-color--7a4b4d, #7A4B4D);
}

.u6oqnmb2f {
  d: path("M14.1 5.127c-.01-.116-.022-.45-.022-.535c0-.1.04-.218.12-.278l.06-.06c.1-.079.14-.198.14-.317V3.62c0-.1.06-.179.16-.199c.239-.06.738-.158 1.456-.158s1.217.099 1.457.158c.08.02.16.1.16.199v.317c0 .12.06.238.139.318c.187.13.175.203.16.357c-.005.048-.02.444-.034.536l-.098 1.472c-.06.658-.578 1.117-1.195 1.117H15.41c-.637 0-1.135-.459-1.194-1.117z");
}

.u7iotewrx {
  d: path("M14.302 4.74a.1.1 0 0 0-.1.1v.099a.1.1 0 0 0 .1.1h.008v.467a.6.6 0 0 0 .6.6h.36a.6.6 0 0 0 .6-.6v-.208c.003-.062.039-.196.13-.196c.093 0 .128.134.13.196v.208a.6.6 0 0 0 .6.6h.36a.6.6 0 0 0 .6-.6v-.467h.01a.1.1 0 0 0 .1-.1v-.1a.1.1 0 0 0-.1-.1h-1.176a.5.5 0 0 0-.358.152l-.004.004c-.069.062-.12.072-.161.073c-.042-.001-.093-.01-.162-.073l-.004-.004a.5.5 0 0 0-.358-.151z");
}

.u7ziimuel {
  stop-color: var(--svg-color--544568, #544568);
}

.uay8mzbfc {
  stop-color: var(--svg-color--362c40, #362C40);
  stop-opacity: 0;
}

.ui0e-xb0n {
  stop-color: var(--svg-color--362549, #362549);
  stop-opacity: 0;
}

.uizhbqnqd {
  stop-color: var(--svg-color--4b345e, #4B345E);
}

.uj-vi6bqm {
  stop-color: var(--svg-color--594c6c, #594C6C);
}

.ukar1r8no {
  d: path("M19.941 10.704c0-1.737-1.156-2.75-1.743-3.164v7.484h1.743z");
}

.um82sc42n {
  stop-color: var(--svg-color--a77e7d, #A77E7D);
}

.unygv2b0a {
  stop-color: var(--svg-color--675086, #675086);
}

.ur0q6myog {
  width: 0.617px;
  height: 3.031px;
  x: 15.152px;
  y: 24.524px;
  rx: 0.309px;
}

.v02cndbaa {
  width: 5.305px;
  height: 0.445px;
  x: 13.34px;
  y: 3.899px;
  rx: 0.1px;
}

.v1nhr4b7v {
  stop-color: var(--svg-color--47345c, #47345C);
}

.va_og8bjg {
  d: path("M17.018 9.27V7.46l.422-.305c.12.117.135.4.13.53l-.03 1.033l.35.03a.1.1 0 0 1 .092.105c-.086 1.196-.41 1.864-.832 2.41c-.29.373-.828.75-1.123.89c-.02.01-.035-.013-.021-.03c.842-.924 1.024-2.244 1.012-2.852");
}

.ve43lhu_q {
  d: path("M14.418 5.11a.25.25 0 0 1 .25-.25h.805a.3.3 0 0 1 .3.3v.36a.5.5 0 0 1-.5.5h-.355a.5.5 0 0 1-.5-.5z");
}

.vv-msqb-k {
  stop-color: var(--svg-color--8b625d, #8B625D);
}

.w-kg8ibqe {
  d: path("M13.802 7.54c.251-.162 1.103-.621 1.378-.7h1.75c.641.313 1.138.585 1.268.7v8h-4.396z");
}

.wb950ymmz {
  stop-color: var(--svg-color--675c73, #675C73);
}

.wgnseactl {
  stop-color: var(--svg-color--543675, #543675);
}

.womn98bvo {
  stop-color: var(--svg-color--926c63, #926C63);
}

.wp-tbrcxl {
  stop-color: var(--svg-color--2d163c, #2D163C);
}

.x6e43ob7y {
  stop-color: var(--svg-color--4a3d57, #4A3D57);
}

.xdhhnfb5a {
  d: path("M16.66 4.535c.267-.025.439.08.48.118a.176.176 0 0 0 .239-.259c-.114-.105-.384-.243-.752-.209a.176.176 0 0 0 .032.35");
}

.xfuivvcjb {
  stop-color: var(--svg-color--93567e, #93567E);
}

.xn9w1abgm {
  stop-color: var(--svg-color--423255, #423255);
}

.xq-_dvbek {
  stop-color: var(--svg-color--bfa3d9, #BFA3D9);
}

.y4t29_brm {
  fill: var(--svg-color--41374b, #41374B);
  d: path("M17.018 9.27V7.46l.422-.305c.12.117.135.4.13.53l-.03 1.033l.35.03a.1.1 0 0 1 .092.105c-.086 1.196-.41 1.864-.832 2.41c-.29.373-.828.75-1.123.89c-.02.01-.035-.013-.021-.03c.842-.924 1.024-2.244 1.012-2.852");
}

.yg7pzjrrr {
  stop-color: var(--svg-color--956363, #956363);
}

.yil8tobop {
  stop-color: var(--svg-color--452c34, #452C34);
}

.yjdgn6b_j {
  fill: var(--svg-color--a389b4, #A389B4);
  d: path("M14.882 7.718c0 .342.019.948.479 1.414c.088.089.23.078.31-.02c.081-.1.177-.232.257-.374a.01.01 0 0 1 .017 0c.08.142.176.274.258.375a.21.21 0 0 0 .31.019c.46-.466.478-1.072.478-1.414z");
}

.ysd9y5b6j {
  d: path("M14.91 10.134v-2.89h2.274v2.89c-.182 1.168-.878 1.83-1.204 2.015c-.756-.48-1.028-1.544-1.07-2.015");
}

.yxue5zb_q {
  width: 0.625px;
  height: 3.031px;
  x: 16.738px;
  y: 24.524px;
  rx: 0.313px;
}

.yz-34ac1v {
  fill: var(--svg-color--3b2330, #3B2330);
  d: path("M15.335 4.535c-.268-.025-.44.08-.481.118a.176.176 0 0 1-.238-.259c.114-.105.383-.243.752-.209a.176.176 0 0 1-.033.35");
}

.z4yf8urbu {
  d: path("M15.426 11.673c.095-.965.261-1.828.36-2.48h.433l.006.039c.174 1.08.298 1.844.341 2.44l-.554.477z");
}

.zeh3-9btv {
  d: path("M16 24.728h1.613v2.505a.807.807 0 0 1-1.613 0z");
}

.zo99rm8ts {
  stop-color: var(--svg-color--4a295c, #4A295C);
}

.zqw5laobm {
  stop-color: var(--svg-color--aa92c2, #AA92C2);
}

.zr5tarbij {
  stop-color: var(--svg-color--a870d4, #A870D4);
}

</style>
