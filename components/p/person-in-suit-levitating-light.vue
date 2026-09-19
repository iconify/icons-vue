<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixyCdPd)" class="l85o48s_p"/><path fill="url(#ipBbTGH)" class="l85o48s_p"/><path fill="url(#iIyOFjc)" class="l85o48s_p"/><g filter="url(#iixFvye)"><rect fill="url(#ixnJbfc)" class="ur0q6myog"/></g><path fill="url(#iXqpbyd)" class="lk8agc7qm"/><path fill="url(#iXWIt6d)" class="zeh3-9btv"/><path fill="url(#iY37LHt)" class="zeh3-9btv"/><path fill="url(#ia3x7od)" class="zeh3-9btv"/><g filter="url(#iCjOadc)"><rect fill="url(#iSIUFTL)" class="yxue5zb_q"/></g><path fill="url(#i0kPruz)" class="fo6x_v8nn"/><path fill="url(#iWiEGpP)" class="uzk4yv-3b"/><path fill="url(#iEfJITd)" class="kn7lfdclf"/><g filter="url(#ibmNnQd)"><circle fill="url(#ia4yq7l)" class="r2a89zbrg"/></g><g filter="url(#icQWfOe)"><circle fill="url(#iVJqaxA)" class="d99syqb2c"/></g><g filter="url(#izTgGBe)"><path fill="url(#imaTwVZ)" class="daj1ojzgg"/></g><path fill="url(#iJ1Q57d)" class="dkfctnzly"/><path fill="url(#i0Bw0rc)" class="dkfctnzly"/><g filter="url(#isqVJMc)"><path fill="url(#iTCk3hG)" class="x4ypq9i6l"/></g><g filter="url(#iVe1mge)"><path fill="url(#iQ8Wibb)" class="n9tffqbrf"/></g><path fill="url(#ih81Ivu)" class="hoi7opb6j"/><path fill="url(#iumXoIx)" class="hoi7opb6j"/><path fill="url(#ihBt0me)" class="e_sl96bsv"/><path class="p8wqmd2zh"/><path fill="url(#iq3YQjd)" class="e7gjqi8ys"/><path fill="url(#iFbiIhd)" class="e7gjqi8ys"/><path fill="url(#iWPIBPc)" class="e7gjqi8ys"/><path fill="url(#ixPjA3d)" class="e7gjqi8ys"/><path fill="url(#i1nK1Ab)" class="sxosrgbtb"/><path fill="url(#ioeMb7c)" class="sxosrgbtb"/><path fill="url(#i29Je3b)" class="sxosrgbtb"/><rect fill="url(#irMylcd)" class="ere_8bytc"/><rect fill="url(#ikkikLd)" class="ere_8bytc"/><g filter="url(#ivmJh3b)"><path class="yjdgn6b_j"/></g><path fill="url(#i6orjQS)" class="c8j7g1b0o"/><path fill="url(#iqrAZpr)" class="q9y0fcvnp"/><path fill="url(#icF06hd)" class="q9y0fcvnp"/><g filter="url(#iRkWhcc)"><path fill="url(#iqquihd)" class="idp7zgk6d"/></g><circle fill="url(#ix17tYd)" class="bu_r-xb9o"/><g filter="url(#iNFRo3B)"><path fill="url(#izP9I8c)" class="awz0q-bcr"/></g><g filter="url(#ieIg6Kc)"><path class="hj_i5ubih"/><path fill="url(#i8Yzdid)" class="fvdgv9b0e"/></g><circle class="qw8we5b2t"/><g filter="url(#i3Xjtlb)"><circle class="l0g_aibko"/></g><g filter="url(#idbyhPb)"><circle fill="url(#iGctdVG)" class="hhkrbqb1q"/></g><g filter="url(#iIz6sie)"><circle class="zam6hjbtm"/></g><path fill="url(#ilTF1xe)" class="fu1kwvbzw"/><path fill="url(#iawNRne)" class="fu1kwvbzw"/><path fill="url(#iJT6uhh)" class="fu1kwvbzw"/><path fill="url(#iBRUAeb)" class="fu1kwvbzw"/><g filter="url(#iqsxoFe)"><path class="pk5uj_bzz"/></g><g filter="url(#iTfS6Du)"><path class="uc43cmbtq"/></g><g filter="url(#ix302cc)"><path class="mzo8yibic"/></g><path fill="url(#ikblSkC)" class="a_5l2kb-s"/><path stroke="url(#i6wm7qM)" class="a4w9gbc0i"/><g clip-rule="evenodd" filter="url(#i8mR0Xd)" class="d2kvgvbvc"><path class="viqjlndaq"/><path fill="url(#iQKetbb)" class="st6hfibfp"/></g><g clip-rule="evenodd" filter="url(#iup1mwe)" class="d2kvgvbvc"><path class="idz4stjrc"/><path fill="url(#i7THwnd)" class="mqhnqonjf"/></g><g filter="url(#iCH4qIm)"><path fill="url(#icjbRdd)" class="atpwef94h"/></g><g filter="url(#iSBK9cb)"><path class="aylk1bs8c"/><path fill="url(#iOpUbTk)" class="ve43lhu_q"/></g><g filter="url(#i8CruOb)"><path class="j08lkhbcq"/><path fill="url(#ivmhtze)" class="rkj830b-m"/></g><path class="uifxklqza"/><path fill="url(#ieR84QX)" class="dy0-oub5j"/><path fill="url(#iQOuxPc)" class="dy0-oub5j"/><path fill="url(#iykAPRb)" class="pgoxgbbvl"/><path fill="url(#iSAhnmr)" class="pgoxgbbvl"/><path fill="url(#ie3iZzn)" class="pgoxgbbvl"/><rect fill="url(#id4cUyb)" class="yxc9ybbdr"/><rect fill="url(#iH9VxWd)" class="yxc9ybbdr"/><rect fill="url(#izXHRhc)" class="yxc9ybbdr"/><g filter="url(#irAk7Zc)"><path fill="url(#ix5Blhs)" class="oxq_1loir"/></g><g filter="url(#iVL1QLd)"><path fill="url(#iVxoKjb)" class="q77rl012p"/></g><defs><radialGradient id="iWiEGpP" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93665 0 0 -14.2152 18.198 10.65)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="nwzbg7kjd"/><stop offset="1" class="ff1no10hm"/></radialGradient><radialGradient id="ia4yq7l" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .33985 -.31868 -.36629 15.348 12.754)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="g23oo4bgx"/><stop offset=".844" class="ccf_1kkne"/></radialGradient><radialGradient id="iVJqaxA" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .33985 -.31868 -.36629 15.349 13.998)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="g23oo4bgx"/><stop offset=".844" class="ccf_1kkne"/></radialGradient><radialGradient id="imaTwVZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.40625 -1.70424 0 12.93 11.462)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="xn9w1abgm"/><stop offset="1" class="glqr6tbiu"/></radialGradient><radialGradient id="iJ1Q57d" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.84375 -.87152 0 19.07 8.587)" gradientUnits="userSpaceOnUse"><stop class="wb950ymmz"/><stop offset="1" class="horgfru7v"/></radialGradient><radialGradient id="iTCk3hG" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.79687 -1.45313 0 19.356 15.853)" gradientUnits="userSpaceOnUse"><stop class="pp2ogccdh"/><stop offset="1" class="jzb13vb7q"/></radialGradient><radialGradient id="iQ8Wibb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24304 0 0 -1.64063 13.8 16.024)" gradientUnits="userSpaceOnUse"><stop offset=".067" class="kvinama8f"/><stop offset="1" class="ugwrc-btt"/></radialGradient><radialGradient id="ih81Ivu" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.71484 1.28125 0 19.137 15.505)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="g9x2u_bdo"/><stop offset="1" class="xq-_dvbek"/></radialGradient><radialGradient id="ihBt0me" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6836 1.05764 0 13.332 15.505)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="c7v7pcmer"/><stop offset="1" class="zqw5laobm"/></radialGradient><radialGradient id="iWPIBPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 0 0 2.48437 13.543 15.54)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="n219yccxp"/><stop offset="1" class="gxi_vjppo"/></radialGradient><radialGradient id="ioeMb7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.90625 0 0 -2.3925 18.387 15.946)" gradientUnits="userSpaceOnUse"><stop offset=".02" class="t4dh35myh"/><stop offset="1" class="i7ndys8gs"/></radialGradient><radialGradient id="irMylcd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.85938 0 0 -1.14453 18.824 29.435)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="i-78nbbad"/><stop offset="1" class="s6odk1prq"/></radialGradient><radialGradient id="i6orjQS" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4961 -.48047 0 15.992 8.696)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="c9neslb2j"/><stop offset="1" class="f46cj4b8l"/></radialGradient><radialGradient id="iqrAZpr" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.789 -.58488 0 16.212 9.193)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="acs5nir-x"/><stop offset="1" class="h6piqgbzt"/></radialGradient><radialGradient id="iqquihd" cx="0" cy="0" r="1" gradientTransform="rotate(-134.885 10.21 1.053)scale(2.08132 2.97709)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="nikzy_-cb"/><stop offset="1" class="mqkt3cb4f"/></radialGradient><radialGradient id="ix17tYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7002 -.71152 .94265 -.92766 16.468 8.135)" gradientUnits="userSpaceOnUse"><stop class="vb338qb3m"/><stop offset="1" class="v70accxbz"/></radialGradient><radialGradient id="izP9I8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01563 .26563 -.73569 -2.81287 15.45 10.118)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="njqqz6bzb"/><stop offset="1" class="dml7oebfc"/></radialGradient><radialGradient id="i8Yzdid" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 .13484 -.29968 2.50018 16.746 9.655)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="qo83b0bvk"/><stop offset="1" class="tw5tjbb2o"/></radialGradient><radialGradient id="iGctdVG" cx="0" cy="0" r="1" gradientTransform="rotate(116.086 7.597 8.171)scale(1.15268)" gradientUnits="userSpaceOnUse"><stop class="ko6qqsh-q"/><stop offset="1" class="iu9mwtb4x"/></radialGradient><radialGradient id="ilTF1xe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72253 -.01563 .02168 -2.38854 17.938 6.446)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="v573aej4q"/><stop offset="1" class="rwnwb2y0z"/></radialGradient><radialGradient id="iBRUAeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.4585 -3.68725 0 16.008 5.394)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="kt3btxb2f"/><stop offset="1" class="eau8n1bgf"/></radialGradient><radialGradient id="ikblSkC" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 -.58594 .63242 -.19394 16.12 5.857)" gradientUnits="userSpaceOnUse"><stop class="b6yztfnii"/><stop offset="1" class="rfrnbzdiw"/></radialGradient><radialGradient id="i6wm7qM" cx="0" cy="0" r="1" gradientTransform="matrix(.1211 -.20312 .60938 .36328 15.472 6.675)" gradientUnits="userSpaceOnUse"><stop class="eu_-jrbby"/><stop offset="1" class="scav1gbft"/></radialGradient><radialGradient id="iQKetbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40003 -.20312 .11015 -.21693 17.435 4.5)" gradientUnits="userSpaceOnUse"><stop class="srk4qcc8w"/><stop offset="1" class="yneofwkkz"/></radialGradient><radialGradient id="i7THwnd" cx="0" cy="0" r="1" gradientTransform="matrix(.40002 -.20313 .11015 .21692 14.56 4.501)" gradientUnits="userSpaceOnUse"><stop class="srk4qcc8w"/><stop offset="1" class="yneofwkkz"/></radialGradient><radialGradient id="iOpUbTk" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.13281 -.2467 0 15.773 4.946)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="g5xdx-p6a"/><stop offset="1" class="e3gx51wtu"/></radialGradient><radialGradient id="ivmhtze" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.13281 -.2467 0 17.594 4.946)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="g5xdx-p6a"/><stop offset="1" class="e3gx51wtu"/></radialGradient><radialGradient id="ieR84QX" cx="0" cy="0" r="1" gradientTransform="rotate(143.094 8.168 4.254)scale(2.51094 1.14233)" gradientUnits="userSpaceOnUse"><stop class="aj_tw3j1o"/><stop offset=".77" class="s3_x2f0ah"/></radialGradient><radialGradient id="iQOuxPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.85157 -1.43359 1.14859 -.68228 15.129 3.544)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="b3u0jug2t"/><stop offset="1" class="uay8mzbfc"/></radialGradient><radialGradient id="iykAPRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29687 2.45313 0 16.98 3.9)" gradientUnits="userSpaceOnUse"><stop class="tboymoxmd"/><stop offset="1" class="n6sxbw5zw"/></radialGradient><radialGradient id="iSAhnmr" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90259 0 0 -.10938 18.008 3.247)" gradientUnits="userSpaceOnUse"><stop class="i8extwu4m"/><stop offset="1" class="esdd1ct8r"/></radialGradient><radialGradient id="ie3iZzn" cx="0" cy="0" r="1" gradientTransform="matrix(.48438 -1.09375 2.42414 1.07355 14.332 4.118)" gradientUnits="userSpaceOnUse"><stop class="sfyf3vb1f"/><stop offset="1" class="nn4_9sbfl"/></radialGradient><radialGradient id="id4cUyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77344 3.42187 0 17.34 4.532)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="gind88bhl"/><stop offset="1" class="ck-8zfmjj"/></radialGradient><linearGradient id="ixyCdPd" x1="15.193" x2="15.193" y1="25.493" y2="28.04" gradientUnits="userSpaceOnUse"><stop class="sfy4td0pz"/><stop offset="1" class="nbnm83bni"/></linearGradient><linearGradient id="ipBbTGH" x1="14.301" x2="14.645" y1="25.899" y2="25.899" gradientUnits="userSpaceOnUse"><stop class="bc6yq6ueq"/><stop offset="1" class="ra0evbbul"/></linearGradient><linearGradient id="iIyOFjc" x1="15.193" x2="15.193" y1="24.845" y2="25.587" gradientUnits="userSpaceOnUse"><stop class="wp-tbrcxl"/><stop offset="1" class="ajiye6oer"/></linearGradient><linearGradient id="ixnJbfc" x1="15.461" x2="15.461" y1="24.524" y2="27.556" gradientUnits="userSpaceOnUse"><stop offset=".196" class="u7ziimuel"/><stop offset="1" class="unygv2b0a"/></linearGradient><linearGradient id="iXqpbyd" x1="15.199" x2="15.199" y1="24.79" y2="27.009" gradientUnits="userSpaceOnUse"><stop class="jq11z6_uy"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="iXWIt6d" x1="16.807" x2="16.807" y1="25.493" y2="28.04" gradientUnits="userSpaceOnUse"><stop class="sfy4td0pz"/><stop offset="1" class="nbnm83bni"/></linearGradient><linearGradient id="iY37LHt" x1="15.914" x2="16.258" y1="25.899" y2="25.899" gradientUnits="userSpaceOnUse"><stop class="aqr6t6bpr"/><stop offset="1" class="j6it256gw"/></linearGradient><linearGradient id="ia3x7od" x1="16.807" x2="16.807" y1="24.845" y2="25.587" gradientUnits="userSpaceOnUse"><stop class="wp-tbrcxl"/><stop offset="1" class="ajiye6oer"/></linearGradient><linearGradient id="iSIUFTL" x1="17.051" x2="17.051" y1="24.524" y2="27.556" gradientUnits="userSpaceOnUse"><stop offset=".196" class="u7ziimuel"/><stop offset="1" class="unygv2b0a"/></linearGradient><linearGradient id="i0kPruz" x1="16.813" x2="16.813" y1="24.79" y2="27.009" gradientUnits="userSpaceOnUse"><stop class="jq11z6_uy"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="iEfJITd" x1="16.047" x2="16.047" y1="8.384" y2="10.759" gradientUnits="userSpaceOnUse"><stop class="krs2oef1o"/><stop offset="1" class="iwbnrv_7v"/></linearGradient><linearGradient id="i0Bw0rc" x1="17.912" x2="18.864" y1="12.068" y2="12.068" gradientUnits="userSpaceOnUse"><stop class="hzpn9-n5u"/><stop offset="1" class="c-948sbmo"/></linearGradient><linearGradient id="iumXoIx" x1="19.535" x2="19.215" y1="14.931" y2="15.345" gradientUnits="userSpaceOnUse"><stop offset=".265" class="chx2sabhv"/><stop offset="1" class="kralbibvz"/></linearGradient><linearGradient id="iq3YQjd" x1="14.901" x2="14.901" y1="15.54" y2="22.399" gradientUnits="userSpaceOnUse"><stop class="qj-kypbtd"/><stop offset="1" class="lp1xml6ym"/></linearGradient><linearGradient id="iFbiIhd" x1="13.802" x2="14.418" y1="20.806" y2="20.806" gradientUnits="userSpaceOnUse"><stop class="p7a95-bzg"/><stop offset="1" class="j7b797_jr"/></linearGradient><linearGradient id="ixPjA3d" x1="16" x2="15.371" y1="18.29" y2="18.29" gradientUnits="userSpaceOnUse"><stop class="lxo6977ad"/><stop offset="1" class="ui0e-xb0n"/></linearGradient><linearGradient id="i1nK1Ab" x1="17.099" x2="17.099" y1="15.54" y2="24.923" gradientUnits="userSpaceOnUse"><stop class="v1nhr4b7v"/><stop offset="1" class="wgnseactl"/></linearGradient><linearGradient id="i29Je3b" x1="15.793" x2="16.84" y1="20.79" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="kmu00qb0d"/><stop offset="1" class="pfcwbwb-a"/></linearGradient><linearGradient id="ikkikLd" x1="16.004" x2="16.004" y1="30.056" y2="29.212" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zr5tarbij"/><stop offset="1" class="jhgdrfbkn"/></linearGradient><linearGradient id="icF06hd" x1="15.582" x2="15.801" y1="10.149" y2="10.157" gradientUnits="userSpaceOnUse"><stop class="erljhfniy"/><stop offset="1" class="dyhqpo0im"/></linearGradient><linearGradient id="iawNRne" x1="16.008" x2="16.008" y1="4.306" y2="5.103" gradientUnits="userSpaceOnUse"><stop class="n0q0sdb1g"/><stop offset="1" class="nr1qzib_n"/></linearGradient><linearGradient id="iJT6uhh" x1="14.214" x2="15.027" y1="6.144" y2="6.097" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wvhx64bpw"/><stop offset="1" class="dgbqhpb-l"/></linearGradient><linearGradient id="icjbRdd" x1="16.001" x2="16.001" y1="4.74" y2="6.106" gradientUnits="userSpaceOnUse"><stop class="uizhbqnqd"/><stop offset="1" class="rosr-ik5x"/></linearGradient><linearGradient id="iH9VxWd" x1="16.496" x2="16.496" y1="4.376" y2="4.243" gradientUnits="userSpaceOnUse"><stop class="zo99rm8ts"/><stop offset="1" class="qo_ozxf1o"/></linearGradient><linearGradient id="izXHRhc" x1="16.785" x2="16.785" y1="3.853" y2="3.985" gradientUnits="userSpaceOnUse"><stop offset=".464" class="x6e43ob7y"/><stop offset="1" class="p2ms6zbbw"/></linearGradient><linearGradient id="ix5Blhs" x1="15.794" x2="15.794" y1="24.728" y2="15.728" gradientUnits="userSpaceOnUse"><stop class="koq2unbkt"/><stop offset="1" class="uj-vi6bqm"/></linearGradient><linearGradient id="iVxoKjb" x1="18.029" x2="18.029" y1="24.728" y2="15.728" gradientUnits="userSpaceOnUse"><stop class="koq2unbkt"/><stop offset="1" class="uj-vi6bqm"/></linearGradient><filter id="iixFvye" width="1.017" height="3.431" x="14.952" y="24.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_683" stdDeviation=".1"/></filter><filter id="iCjOadc" width="1.025" height="3.431" x="16.538" y="24.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_683" stdDeviation=".1"/></filter><filter id="ibmNnQd" width=".808" height=".808" x="14.637" y="12.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.164706 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_683"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_683" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_683"/></filter><filter id="icQWfOe" width=".808" height=".808" x="14.637" y="13.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.164706 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_683"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_683" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_683"/></filter><filter id="izTgGBe" width="1.993" height="7.488" x="12.059" y="7.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.313726 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="isqVJMc" width="1.343" height="2.384" x="18.198" y="14.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.552941 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="iVe1mge" width="1.243" height="2.484" x="12.559" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.501961 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="ivmJh3b" width="2.609" height="1.975" x="14.632" y="7.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_683" stdDeviation=".125"/></filter><filter id="iRkWhcc" width="2.109" height="1.525" x="14.946" y="7.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.596078 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="iNFRo3B" width="2.082" height="5.1" x="14.019" y="7.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.12549 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="ieIg6Kc" width="2.232" height="5.1" x="15.9" y="7.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.168627 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.152941 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_683" result="effect2_innerShadow_4002_683"/></filter><filter id="i3Xjtlb" width="1.244" height="1.244" x="13.615" y="4.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_683" stdDeviation=".1"/></filter><filter id="idbyhPb" width="1.342" height="1.342" x="17.149" y="4.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.65098 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="iIz6sie" width="1.178" height="1.178" x="17.181" y="4.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_683" stdDeviation=".075"/></filter><filter id="iqsxoFe" width=".541" height=".892" x="13.697" y="4.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.0196078 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="iTfS6Du" width=".521" height=".894" x="17.798" y="4.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0117647 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="ix302cc" width="1.289" height="1.691" x="15.353" y="4.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_683" stdDeviation=".125"/></filter><filter id="i8mR0Xd" width="1.018" height=".57" x="16.467" y="4.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0235294 0 0 0 0 0.0117647 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="iup1mwe" width="1.018" height=".57" x="14.559" y="4.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0235294 0 0 0 0 0.0117647 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="iCH4qIm" width="3.598" height="1.366" x="14.202" y="4.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="iSBK9cb" width="1.455" height="1.26" x="14.418" y="4.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.105882 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="i8CruOb" width="1.455" height="1.26" x="16.238" y="4.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.105882 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_683"/></filter><filter id="irAk7Zc" width="2.284" height="10.3" x="13.987" y="15.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_683" stdDeviation=".325"/></filter><filter id="iVL1QLd" width="2.284" height="10.3" x="16.221" y="15.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_683" stdDeviation=".325"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-suit-levitating-light" /></template>
<style>
.a_5l2kb-s {
  d: path("m15.855 5.198l-.198.669c-.04.137.057.274.194.274h.292c.137 0 .234-.14.194-.274l-.198-.669a.147.147 0 0 0-.284 0");
}

.a4w9gbc0i {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-04px, 0.04px);
  d: path("M15.491 6.38c.146.076.32.12.506.12c.188 0 .36-.044.506-.12a.08.08 0 0 1 .092.015zm0 0a.08.08 0 0 0-.092.015m.092-.015l-.092.015m1.187.08c.032-.048-.023-.104-.074-.078a1.1 1.1 0 0 1-.515.122c-.189 0-.366-.044-.515-.122l-.074.078m1.178 0a.7.7 0 0 1-.589.315a.7.7 0 0 1-.589-.315m1.178 0l.017.011zm-1.178 0l-.016.011m.016-.01l-.016.01m.007-.09a.07.07 0 0 0-.007.09m.007-.09l-.007.09");
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

.atpwef94h {
  d: path("M14.302 4.74a.1.1 0 0 0-.1.1v.099a.1.1 0 0 0 .1.1h.008v.467a.6.6 0 0 0 .6.6h.36a.6.6 0 0 0 .6-.6v-.208c.003-.062.039-.196.13-.196c.093 0 .128.134.13.196v.208a.6.6 0 0 0 .6.6h.36a.6.6 0 0 0 .6-.6V5.04h.01a.1.1 0 0 0 .1-.1v-.1a.1.1 0 0 0-.1-.1h-1.176a.5.5 0 0 0-.358.152l-.004.004c-.069.063-.12.072-.161.074c-.042-.002-.093-.011-.162-.074l-.004-.004a.5.5 0 0 0-.358-.151z");
}

.awz0q-bcr {
  d: path("M14.983 9.27V7.46l-.423-.305c-.12.117-.134.4-.13.53l.032 1.033l-.352.029a.1.1 0 0 0-.09.106c.085 1.196.41 1.863.831 2.41c.289.372.827.75 1.123.89c.02.01.035-.014.02-.03c-.842-.924-1.024-2.244-1.011-2.852");
}

.aylk1bs8c {
  fill: var(--svg-color--4b3561, #4B3561);
  d: path("M14.418 5.11a.25.25 0 0 1 .25-.25h.805a.3.3 0 0 1 .3.3v.36a.5.5 0 0 1-.5.5h-.355a.5.5 0 0 1-.5-.5z");
}

.b3u0jug2t {
  stop-color: var(--svg-color--362c40, #362C40);
}

.b6yztfnii {
  stop-color: var(--svg-color--ddaca5, #DDACA5);
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

.c8j7g1b0o {
  d: path("M15.787 9.193a2.4 2.4 0 0 1-.36-.657h1.13a3.2 3.2 0 0 1-.332.657z");
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

.daj1ojzgg {
  d: path("M12.059 10.704c0-1.737 1.117-2.808 1.743-3.168v7.489h-1.743z");
}

.dgbqhpb-l {
  stop-color: var(--svg-color--dfa792, #DFA792);
  stop-opacity: 0;
}

.dkfctnzly {
  d: path("M19.941 10.704c0-1.737-1.156-2.75-1.743-3.164v7.485h1.743z");
}

.dml7oebfc {
  stop-color: var(--svg-color--37303e, #37303E);
}

.dy0-oub5j {
  d: path("M14.083 3.356v-.46c-.012-.193.108-.636.526-.774c.383-.144.694-.003.963.12c.155.07.296.134.428.134c.133 0 .274-.064.429-.134c.27-.123.58-.264.963-.12c.418.138.538.58.526.774v.46z");
}

.dyhqpo0im {
  stop-color: var(--svg-color--412c57, #412C57);
  stop-opacity: 0;
}

.e_sl96bsv {
  d: path("M12.559 15.505h1.243v-.48h-1.243z");
}

.e3gx51wtu {
  stop-color: var(--svg-color--5b496d, #5B496D);
  stop-opacity: 0;
}

.e7gjqi8ys {
  d: path("M13.802 15.54H16v9.383h-2.198z");
}

.eau8n1bgf {
  stop-color: var(--svg-color--c38795, #C38795);
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

.eu_-jrbby {
  stop-color: var(--svg-color--e0b0a3, #E0B0A3);
}

.f46cj4b8l {
  stop-color: var(--svg-color--43295a, #43295A);
}

.ff1no10hm {
  stop-color: var(--svg-color--48325f, #48325F);
}

.fo6x_v8nn {
  d: path("M16.39 24.79h.844v1.797a.422.422 0 0 1-.843 0z");
}

.ft5dv1b6b {
  fill: none;
}

.fu1kwvbzw {
  d: path("M14.1 5.127c-.01-.116-.022-.45-.022-.535c0-.099.04-.218.12-.278l.06-.06a.39.39 0 0 0 .14-.317V3.62c0-.1.06-.179.16-.198c.239-.06.738-.16 1.456-.16s1.217.1 1.457.16c.08.02.16.099.16.198v.317c0 .12.06.239.139.318c.187.13.175.203.16.357c-.005.048-.02.444-.034.536l-.098 1.472c-.06.659-.578 1.117-1.195 1.117H15.41c-.637 0-1.135-.458-1.194-1.117z");
}

.fvdgv9b0e {
  d: path("M17.018 9.27V7.46l.422-.305c.12.117.135.4.13.53l-.03 1.033l.35.029a.1.1 0 0 1 .092.106c-.086 1.196-.41 1.863-.832 2.41c-.29.372-.828.75-1.123.89c-.02.01-.035-.014-.021-.03c.842-.924 1.024-2.244 1.012-2.852");
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

.gxi_vjppo {
  stop-color: var(--svg-color--3e2031, #3E2031);
  stop-opacity: 0;
}

.h6piqgbzt {
  stop-color: var(--svg-color--473559, #473559);
}

.hhkrbqb1q {
  cx: 17.77px;
  cy: 5.355px;
  r: 0.621px;
}

.hj_i5ubih {
  fill: var(--svg-color--41374b, #41374B);
  d: path("M17.018 9.27V7.46l.422-.305c.12.117.135.4.13.53l-.03 1.033l.35.029a.1.1 0 0 1 .092.106c-.086 1.196-.41 1.863-.832 2.41c-.29.372-.828.75-1.123.89c-.02.01-.035-.014-.021-.03c.842-.924 1.024-2.244 1.012-2.852");
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

.idp7zgk6d {
  d: path("M14.946 7.556c0 .342.019.948.479 1.414c.088.089.23.078.31-.02c.081-.1.177-.232.257-.374a.01.01 0 0 1 .017 0c.08.142.176.274.258.375a.21.21 0 0 0 .31.019c.459-.466.478-1.072.478-1.414z");
}

.idz4stjrc {
  fill: var(--svg-color--151119, #151119);
  d: path("M15.335 4.535c-.268-.025-.44.08-.481.118a.176.176 0 0 1-.238-.259c.114-.105.383-.244.752-.21a.176.176 0 0 1-.033.35");
}

.iu9mwtb4x {
  stop-color: var(--svg-color--e8b09e, #E8B09E);
}

.iwbnrv_7v {
  stop-color: var(--svg-color--c1add3, #C1ADD3);
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

.jhgdrfbkn {
  stop-color: var(--svg-color--a189b8, #A189B8);
  stop-opacity: 0;
}

.jq11z6_uy {
  stop-color: var(--svg-color--b998d9, #B998D9);
}

.jzb13vb7q {
  stop-color: var(--svg-color--dc9ca5, #DC9CA5);
}

.kmu00qb0d {
  stop-color: var(--svg-color--2c183c, #2C183C);
}

.kn7lfdclf {
  d: path("M14.91 10.134v-2.89h2.274v2.89c-.182 1.169-.878 1.83-1.204 2.015c-.756-.48-1.028-1.544-1.07-2.015");
}

.ko6qqsh-q {
  stop-color: var(--svg-color--f3c9b5, #F3C9B5);
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

.kt3btxb2f {
  stop-color: var(--svg-color--d09897, #D09897);
  stop-opacity: 0;
}

.kvinama8f {
  stop-color: var(--svg-color--e1a7b6, #E1A7B6);
}

.l0g_aibko {
  cx: 14.238px;
  cy: 5.355px;
  r: 0.422px;
  fill: var(--svg-color--c28571, #C28571);
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

.lxo6977ad {
  stop-color: var(--svg-color--362549, #362549);
}

.mqhnqonjf {
  d: path("M15.335 4.535c-.268-.025-.44.08-.481.118a.176.176 0 0 1-.238-.259c.114-.105.383-.244.752-.21a.176.176 0 0 1-.033.35");
}

.mqkt3cb4f {
  stop-color: var(--svg-color--927fa2, #927FA2);
}

.mzo8yibic {
  fill: var(--svg-color--c0857e, #C0857E);
  d: path("m15.837 5.144l-.224.755c-.045.156.064.31.219.31h.33c.155 0 .265-.157.22-.31l-.224-.755a.166.166 0 0 0-.322 0");
}

.n0q0sdb1g {
  stop-color: var(--svg-color--c7898a, #C7898A);
}

.n219yccxp {
  stop-color: var(--svg-color--3e2031, #3E2031);
}

.n6sxbw5zw {
  stop-color: var(--svg-color--53386c, #53386C);
}

.n9tffqbrf {
  d: path("M13.802 15.025h-1.243v.99c0 .687.719 1.119 1.243 1.244z");
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

.nr1qzib_n {
  stop-color: var(--svg-color--c7898a, #C7898A);
  stop-opacity: 0;
}

.nwzbg7kjd {
  stop-color: var(--svg-color--64517b, #64517B);
}

.oxq_1loir {
  d: path("M14.637 15.728h.984v9h-.984z");
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

.pk5uj_bzz {
  fill: var(--svg-color--222, #222);
  d: path("M14.078 4.592c0 .086.012.419.022.535l.003.04c-.05-.01-.123-.048-.183-.15c-.08-.136-.149-.551-.173-.742h.49l-.039.04c-.08.059-.12.178-.12.277");
}

.pp2ogccdh {
  stop-color: var(--svg-color--ffccc8, #FFCCC8);
}

.q77rl012p {
  d: path("M16.871 15.728h.984v9h-.984z");
}

.q9y0fcvnp {
  d: path("M15.426 11.673c.095-.965.261-1.828.36-2.48h.433l.006.039c.174 1.08.298 1.844.341 2.441l-.554.476z");
}

.qj-kypbtd {
  stop-color: var(--svg-color--423053, #423053);
}

.qo_ozxf1o {
  stop-color: var(--svg-color--4a295c, #4A295C);
  stop-opacity: 0;
}

.qo83b0bvk {
  stop-color: var(--svg-color--55525a, #55525A);
  stop-opacity: 0;
}

.qw8we5b2t {
  cx: 14.231px;
  cy: 5.355px;
  r: 0.621px;
  fill: var(--svg-color--c08c79, #C08C79);
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

.rfrnbzdiw {
  stop-color: var(--svg-color--c1847d, #C1847D);
}

.rkj830b-m {
  d: path("M17.594 5.11a.25.25 0 0 0-.25-.25h-.806a.3.3 0 0 0-.3.3v.36a.5.5 0 0 0 .5.5h.356a.5.5 0 0 0 .5-.5z");
}

.rosr-ik5x {
  stop-color: var(--svg-color--39294a, #39294A);
}

.rwnwb2y0z {
  stop-color: var(--svg-color--dfaaa1, #DFAAA1);
}

.s3_x2f0ah {
  stop-color: var(--svg-color--52495e, #52495E);
  stop-opacity: 0;
}

.s6odk1prq {
  stop-color: var(--svg-color--96929b, #96929B);
}

.scav1gbft {
  stop-color: var(--svg-color--e0b0a3, #E0B0A3);
  stop-opacity: 0;
}

.sfy4td0pz {
  stop-color: var(--svg-color--4a3d5b, #4A3D5B);
}

.sfyf3vb1f {
  stop-color: var(--svg-color--453752, #453752);
}

.srk4qcc8w {
  stop-color: var(--svg-color--2b2b2c, #2B2B2C);
}

.st6hfibfp {
  d: path("M16.66 4.535c.267-.025.439.08.48.118a.176.176 0 0 0 .239-.259c-.114-.105-.384-.244-.752-.21a.176.176 0 0 0 .032.35");
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

.tw5tjbb2o {
  stop-color: var(--svg-color--55525a, #55525A);
}

.u7ziimuel {
  stop-color: var(--svg-color--544568, #544568);
}

.uay8mzbfc {
  stop-color: var(--svg-color--362c40, #362C40);
  stop-opacity: 0;
}

.uc43cmbtq {
  fill: var(--svg-color--2e2d2e, #2E2D2E);
  d: path("M17.895 5.17c.049-.005.133-.038.201-.154c.08-.135.148-.55.173-.741h-.471c.154.116.147.188.133.327l-.001.01l-.009.148a6 6 0 0 1-.025.388z");
}

.ugwrc-btt {
  stop-color: var(--svg-color--cc969b, #CC969B);
}

.ui0e-xb0n {
  stop-color: var(--svg-color--362549, #362549);
  stop-opacity: 0;
}

.uifxklqza {
  fill: var(--svg-color--4b3f57, #4B3F57);
  d: path("M14.083 3.356v-.46c-.012-.193.108-.636.526-.774c.383-.144.694-.003.963.12c.155.07.296.134.428.134c.133 0 .274-.064.429-.134c.27-.123.58-.264.963-.12c.418.138.538.58.526.774v.46z");
}

.uizhbqnqd {
  stop-color: var(--svg-color--4b345e, #4B345E);
}

.uj-vi6bqm {
  stop-color: var(--svg-color--594c6c, #594C6C);
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

.uzk4yv-3b {
  d: path("M13.802 7.54c.251-.162 1.103-.62 1.378-.7h1.75c.641.313 1.138.586 1.268.7v8h-4.396z");
}

.v1nhr4b7v {
  stop-color: var(--svg-color--47345c, #47345C);
}

.v573aej4q {
  stop-color: var(--svg-color--ffd6bc, #FFD6BC);
}

.v70accxbz {
  stop-color: var(--svg-color--c98b91, #C98B91);
}

.vb338qb3m {
  stop-color: var(--svg-color--dfa7a4, #DFA7A4);
}

.ve43lhu_q {
  d: path("M14.418 5.11a.25.25 0 0 1 .25-.25h.805a.3.3 0 0 1 .3.3v.36a.5.5 0 0 1-.5.5h-.355a.5.5 0 0 1-.5-.5z");
}

.viqjlndaq {
  fill: var(--svg-color--151119, #151119);
  d: path("M16.66 4.535c.267-.025.439.08.48.118a.176.176 0 0 0 .239-.259c-.114-.105-.384-.244-.752-.21a.176.176 0 0 0 .032.35");
}

.wb950ymmz {
  stop-color: var(--svg-color--675c73, #675C73);
}

.wgnseactl {
  stop-color: var(--svg-color--543675, #543675);
}

.wp-tbrcxl {
  stop-color: var(--svg-color--2d163c, #2D163C);
}

.wvhx64bpw {
  stop-color: var(--svg-color--dfa792, #DFA792);
}

.x4ypq9i6l {
  d: path("M18.199 15.025h1.242v.99c0 .687-.718 1.119-1.242 1.244z");
}

.x6e43ob7y {
  stop-color: var(--svg-color--4a3d57, #4A3D57);
}

.xn9w1abgm {
  stop-color: var(--svg-color--423255, #423255);
}

.xq-_dvbek {
  stop-color: var(--svg-color--bfa3d9, #BFA3D9);
}

.yjdgn6b_j {
  fill: var(--svg-color--a389b4, #A389B4);
  d: path("M14.882 7.718c0 .342.019.948.479 1.414c.088.089.23.078.31-.02c.081-.1.177-.232.257-.374a.01.01 0 0 1 .017 0c.08.142.176.274.258.375a.21.21 0 0 0 .31.019c.46-.466.478-1.072.478-1.414z");
}

.yneofwkkz {
  stop-color: var(--svg-color--2b2b2c, #2B2B2C);
  stop-opacity: 0;
}

.yxc9ybbdr {
  width: 5.305px;
  height: 0.445px;
  x: 13.34px;
  y: 3.9px;
  rx: 0.1px;
}

.yxue5zb_q {
  width: 0.625px;
  height: 3.031px;
  x: 16.738px;
  y: 24.524px;
  rx: 0.313px;
}

.zam6hjbtm {
  cx: 17.77px;
  cy: 5.355px;
  r: 0.439px;
  fill: var(--svg-color--e4af96, #E4AF96);
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
