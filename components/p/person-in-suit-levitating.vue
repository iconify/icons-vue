<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixyCdPd)" class="l85o48s_p"/><path fill="url(#ipBbTGH)" class="l85o48s_p"/><path fill="url(#iIyOFjc)" class="l85o48s_p"/><g filter="url(#iNpboKc)"><rect fill="url(#ixnJbfc)" class="ur0q6myog"/></g><path fill="url(#iXqpbyd)" class="lk8agc7qm"/><path fill="url(#iXWIt6d)" class="zeh3-9btv"/><path fill="url(#iY37LHt)" class="zeh3-9btv"/><path fill="url(#ia3x7od)" class="zeh3-9btv"/><g filter="url(#iobD1UL)"><rect fill="url(#iSIUFTL)" class="yxue5zb_q"/></g><path fill="url(#i0kPruz)" class="fo6x_v8nn"/><path fill="url(#iWiEGpP)" class="uzk4yv-3b"/><path fill="url(#iEfJITd)" class="kn7lfdclf"/><g filter="url(#iTqEPuc)"><circle fill="url(#ia4yq7l)" class="r2a89zbrg"/></g><g filter="url(#iBdraFd)"><circle fill="url(#iVJqaxA)" class="d99syqb2c"/></g><g filter="url(#iMlPmac)"><path fill="url(#imaTwVZ)" class="daj1ojzgg"/></g><path fill="url(#iJ1Q57d)" class="dkfctnzly"/><path fill="url(#i0Bw0rc)" class="dkfctnzly"/><g filter="url(#ighUwwd)"><path fill="url(#iCTKHfc)" class="x4ypq9i6l"/></g><g filter="url(#i04mPtc)"><path fill="url(#iPHp5tb)" class="n9tffqbrf"/></g><path fill="url(#ih81Ivu)" class="hoi7opb6j"/><path fill="url(#iumXoIx)" class="hoi7opb6j"/><path fill="url(#ihBt0me)" class="e_sl96bsv"/><path class="p8wqmd2zh"/><path fill="url(#iq3YQjd)" class="e7gjqi8ys"/><path fill="url(#iFbiIhd)" class="e7gjqi8ys"/><path fill="url(#iWPIBPc)" class="e7gjqi8ys"/><path fill="url(#ixPjA3d)" class="e7gjqi8ys"/><path fill="url(#i1nK1Ab)" class="sxosrgbtb"/><path fill="url(#ioeMb7c)" class="sxosrgbtb"/><path fill="url(#i29Je3b)" class="sxosrgbtb"/><rect fill="url(#irMylcd)" class="ere_8bytc"/><rect fill="url(#ikkikLd)" class="ere_8bytc"/><g filter="url(#ilPuHEe)"><path class="yjdgn6b_j"/></g><path fill="url(#i6orjQS)" class="c8j7g1b0o"/><path fill="url(#iqrAZpr)" class="q9y0fcvnp"/><path fill="url(#icF06hd)" class="q9y0fcvnp"/><g filter="url(#izKLmEa)"><path fill="url(#iEiVZXY)" class="idp7zgk6d"/></g><circle fill="url(#iBujREb)" class="bu_r-xb9o"/><g filter="url(#iqr7kjd)"><path fill="url(#izP9I8c)" class="awz0q-bcr"/></g><g filter="url(#ivVZLdc)"><path class="hj_i5ubih"/><path fill="url(#i8Yzdid)" class="fvdgv9b0e"/></g><circle fill="url(#iDbrdhe)" class="xdk4w7bjh"/><g filter="url(#iyNozZc)"><circle fill="url(#iqCAmtc)" class="k9cr8rb3u"/></g><g filter="url(#i0qbkIb)"><circle fill="url(#i7VLlHo)" class="hhkrbqb1q"/></g><g filter="url(#iX3nZ6c)"><circle class="z67jedbbr"/><circle fill="url(#ivSuifK)" class="cihrumz2d"/><circle fill="url(#i3cqLOd)" class="cihrumz2d"/></g><path fill="url(#itS52ed)" class="fu1kwvbzw"/><path fill="url(#iVPMiJc)" class="fu1kwvbzw"/><path fill="url(#i1eLPae)" class="fu1kwvbzw"/><g filter="url(#i1cVpgc)"><path fill="url(#i4E2UBd)" class="w-3cr34sa"/></g><g filter="url(#iMYEmdw)"><path fill="url(#iKFPPTd)" class="qowwj230w"/></g><path fill="url(#igJ7Woe)" class="a_5l2kb-s"/><path class="lnay1fcot"/><g clip-rule="evenodd" filter="url(#iMIRSOO)" class="d2kvgvbvc"><path class="vvnqwub4r"/><path fill="url(#i9xa39c)" class="st6hfibfp"/></g><g filter="url(#izCvmoe)"><path clip-rule="evenodd" class="zv83v_bcv"/></g><g filter="url(#iPuHBDc)"><path fill="url(#icjbRdd)" class="atpwef94h"/></g><g filter="url(#iwF25ic)"><path class="aylk1bs8c"/><path fill="url(#iOpUbTk)" class="ve43lhu_q"/></g><g filter="url(#iQZQkbd)"><path class="j08lkhbcq"/><path fill="url(#ivmhtze)" class="rkj830b-m"/></g><path class="uifxklqza"/><path fill="url(#ieR84QX)" class="dy0-oub5j"/><path fill="url(#iQOuxPc)" class="dy0-oub5j"/><path fill="url(#iykAPRb)" class="pgoxgbbvl"/><path fill="url(#iSAhnmr)" class="pgoxgbbvl"/><path fill="url(#ie3iZzn)" class="pgoxgbbvl"/><rect fill="url(#id4cUyb)" class="yxc9ybbdr"/><rect fill="url(#iH9VxWd)" class="yxc9ybbdr"/><rect fill="url(#izXHRhc)" class="yxc9ybbdr"/><g filter="url(#iL5LHSA)"><path fill="url(#ix5Blhs)" class="oxq_1loir"/></g><g filter="url(#iFM23ie)"><path fill="url(#iVxoKjb)" class="q77rl012p"/></g><defs><radialGradient id="iWiEGpP" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93665 0 0 -14.2152 18.198 10.65)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="nwzbg7kjd"/><stop offset="1" class="ff1no10hm"/></radialGradient><radialGradient id="ia4yq7l" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .33985 -.31868 -.36629 15.348 12.754)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="g23oo4bgx"/><stop offset=".844" class="ccf_1kkne"/></radialGradient><radialGradient id="iVJqaxA" cx="0" cy="0" r="1" gradientTransform="matrix(-.39062 .33985 -.31868 -.36629 15.349 13.998)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="g23oo4bgx"/><stop offset=".844" class="ccf_1kkne"/></radialGradient><radialGradient id="imaTwVZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.40625 -1.70424 0 12.93 11.462)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="xn9w1abgm"/><stop offset="1" class="glqr6tbiu"/></radialGradient><radialGradient id="iJ1Q57d" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.84375 -.87152 0 19.07 8.587)" gradientUnits="userSpaceOnUse"><stop class="wb950ymmz"/><stop offset="1" class="horgfru7v"/></radialGradient><radialGradient id="iCTKHfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.79687 -1.45313 0 19.356 15.853)" gradientUnits="userSpaceOnUse"><stop class="lvi8nmbhj"/><stop offset="1" class="vczrvlbbh"/></radialGradient><radialGradient id="iPHp5tb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24304 0 0 -1.64063 13.8 16.024)" gradientUnits="userSpaceOnUse"><stop offset=".067" class="c4zuphbey"/><stop offset="1" class="y9ylhyjkb"/></radialGradient><radialGradient id="ih81Ivu" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.71484 1.28125 0 19.137 15.505)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="g9x2u_bdo"/><stop offset="1" class="xq-_dvbek"/></radialGradient><radialGradient id="ihBt0me" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6836 1.05764 0 13.332 15.505)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="c7v7pcmer"/><stop offset="1" class="zqw5laobm"/></radialGradient><radialGradient id="iWPIBPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 0 0 2.48437 13.543 15.54)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="n219yccxp"/><stop offset="1" class="gxi_vjppo"/></radialGradient><radialGradient id="ioeMb7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.90625 0 0 -2.3925 18.387 15.946)" gradientUnits="userSpaceOnUse"><stop offset=".02" class="t4dh35myh"/><stop offset="1" class="i7ndys8gs"/></radialGradient><radialGradient id="irMylcd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.85938 0 0 -1.14453 18.824 29.435)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="i-78nbbad"/><stop offset="1" class="s6odk1prq"/></radialGradient><radialGradient id="i6orjQS" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4961 -.48047 0 15.992 8.696)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="c9neslb2j"/><stop offset="1" class="f46cj4b8l"/></radialGradient><radialGradient id="iqrAZpr" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.789 -.58488 0 16.212 9.193)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="acs5nir-x"/><stop offset="1" class="h6piqgbzt"/></radialGradient><radialGradient id="iEiVZXY" cx="0" cy="0" r="1" gradientTransform="rotate(-134.885 10.21 1.053)scale(2.08132 2.97709)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="n5kv48x3v"/><stop offset="1" class="t8ohmc0fu"/></radialGradient><radialGradient id="iBujREb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7002 -.71152 .94265 -.92766 16.468 8.135)" gradientUnits="userSpaceOnUse"><stop class="o7-vrmbvg"/><stop offset="1" class="e_mvkligi"/></radialGradient><radialGradient id="izP9I8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01563 .26563 -.73569 -2.81287 15.45 10.118)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="njqqz6bzb"/><stop offset="1" class="dml7oebfc"/></radialGradient><radialGradient id="i8Yzdid" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 .13484 -.29968 2.50018 16.746 9.655)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="qo83b0bvk"/><stop offset="1" class="tw5tjbb2o"/></radialGradient><radialGradient id="iDbrdhe" cx="0" cy="0" r="1" gradientTransform="matrix(.65284 0 0 1.14248 13.61 5.355)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ivSuifK" cx="0" cy="0" r="1" gradientTransform="matrix(.30552 -.56194 .3289 .17882 17.755 5.66)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="i3cqLOd" cx="0" cy="0" r="1" gradientTransform="rotate(44.706 2.373 24.283)scale(.13572 .17497)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="itS52ed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72253 -.01563 .02168 -2.38854 17.938 6.446)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="eksmwwbms"/><stop offset="1" class="e4487pbsf"/></radialGradient><radialGradient id="iVPMiJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20702 2.35254 -3.52834 -.31049 16.215 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="d2iy96bbj"/><stop offset=".987" class="owa7czdbk"/></radialGradient><radialGradient id="i4E2UBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.74219 1.50988 0 13.992 5.11)" gradientUnits="userSpaceOnUse"><stop class="hp8joq9cc"/><stop offset="1" class="g4assg31z"/></radialGradient><radialGradient id="iKFPPTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 -.16406 .41142 -1.3322 18.207 4.79)" gradientUnits="userSpaceOnUse"><stop class="sa0syexyw"/><stop offset="1" class="mm4i4_zhz"/></radialGradient><radialGradient id="igJ7Woe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.79867 .47559 0 15.997 5.886)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="rutxg0bgb"/><stop offset="1" class="yd1ukgyzh"/></radialGradient><radialGradient id="i9xa39c" cx="0" cy="0" r="1" gradientTransform="matrix(-.40003 -.20312 .11015 -.21693 17.435 4.5)" gradientUnits="userSpaceOnUse"><stop class="ughf7bc6g"/><stop offset="1" class="k9hymybji"/></radialGradient><radialGradient id="iOpUbTk" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.13281 -.2467 0 15.773 4.946)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="g5xdx-p6a"/><stop offset="1" class="e3gx51wtu"/></radialGradient><radialGradient id="ivmhtze" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.13281 -.2467 0 17.594 4.946)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="g5xdx-p6a"/><stop offset="1" class="e3gx51wtu"/></radialGradient><radialGradient id="ieR84QX" cx="0" cy="0" r="1" gradientTransform="rotate(143.094 8.168 4.254)scale(2.51094 1.14233)" gradientUnits="userSpaceOnUse"><stop class="aj_tw3j1o"/><stop offset=".77" class="s3_x2f0ah"/></radialGradient><radialGradient id="iQOuxPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.85157 -1.43359 1.14859 -.68228 15.129 3.544)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="b3u0jug2t"/><stop offset="1" class="uay8mzbfc"/></radialGradient><radialGradient id="iykAPRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29687 2.45313 0 16.98 3.9)" gradientUnits="userSpaceOnUse"><stop class="tboymoxmd"/><stop offset="1" class="n6sxbw5zw"/></radialGradient><radialGradient id="iSAhnmr" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90259 0 0 -.10938 18.008 3.247)" gradientUnits="userSpaceOnUse"><stop class="i8extwu4m"/><stop offset="1" class="esdd1ct8r"/></radialGradient><radialGradient id="ie3iZzn" cx="0" cy="0" r="1" gradientTransform="matrix(.48438 -1.09375 2.42414 1.07355 14.332 4.118)" gradientUnits="userSpaceOnUse"><stop class="sfyf3vb1f"/><stop offset="1" class="nn4_9sbfl"/></radialGradient><radialGradient id="id4cUyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77344 3.42187 0 17.34 4.532)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="gind88bhl"/><stop offset="1" class="ck-8zfmjj"/></radialGradient><linearGradient id="ixyCdPd" x1="15.193" x2="15.193" y1="25.493" y2="28.04" gradientUnits="userSpaceOnUse"><stop class="sfy4td0pz"/><stop offset="1" class="nbnm83bni"/></linearGradient><linearGradient id="ipBbTGH" x1="14.301" x2="14.645" y1="25.899" y2="25.899" gradientUnits="userSpaceOnUse"><stop class="bc6yq6ueq"/><stop offset="1" class="ra0evbbul"/></linearGradient><linearGradient id="iIyOFjc" x1="15.193" x2="15.193" y1="24.845" y2="25.587" gradientUnits="userSpaceOnUse"><stop class="wp-tbrcxl"/><stop offset="1" class="ajiye6oer"/></linearGradient><linearGradient id="ixnJbfc" x1="15.461" x2="15.461" y1="24.524" y2="27.556" gradientUnits="userSpaceOnUse"><stop offset=".196" class="u7ziimuel"/><stop offset="1" class="unygv2b0a"/></linearGradient><linearGradient id="iXqpbyd" x1="15.199" x2="15.199" y1="24.79" y2="27.009" gradientUnits="userSpaceOnUse"><stop class="jq11z6_uy"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="iXWIt6d" x1="16.807" x2="16.807" y1="25.493" y2="28.04" gradientUnits="userSpaceOnUse"><stop class="sfy4td0pz"/><stop offset="1" class="nbnm83bni"/></linearGradient><linearGradient id="iY37LHt" x1="15.914" x2="16.258" y1="25.899" y2="25.899" gradientUnits="userSpaceOnUse"><stop class="aqr6t6bpr"/><stop offset="1" class="j6it256gw"/></linearGradient><linearGradient id="ia3x7od" x1="16.807" x2="16.807" y1="24.845" y2="25.587" gradientUnits="userSpaceOnUse"><stop class="wp-tbrcxl"/><stop offset="1" class="ajiye6oer"/></linearGradient><linearGradient id="iSIUFTL" x1="17.051" x2="17.051" y1="24.524" y2="27.556" gradientUnits="userSpaceOnUse"><stop offset=".196" class="u7ziimuel"/><stop offset="1" class="unygv2b0a"/></linearGradient><linearGradient id="i0kPruz" x1="16.813" x2="16.813" y1="24.79" y2="27.009" gradientUnits="userSpaceOnUse"><stop class="jq11z6_uy"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="iEfJITd" x1="16.047" x2="16.047" y1="8.384" y2="10.759" gradientUnits="userSpaceOnUse"><stop class="krs2oef1o"/><stop offset="1" class="iwbnrv_7v"/></linearGradient><linearGradient id="i0Bw0rc" x1="17.912" x2="18.864" y1="12.068" y2="12.068" gradientUnits="userSpaceOnUse"><stop class="hzpn9-n5u"/><stop offset="1" class="c-948sbmo"/></linearGradient><linearGradient id="iumXoIx" x1="19.535" x2="19.215" y1="14.931" y2="15.345" gradientUnits="userSpaceOnUse"><stop offset=".265" class="chx2sabhv"/><stop offset="1" class="kralbibvz"/></linearGradient><linearGradient id="iq3YQjd" x1="14.901" x2="14.901" y1="15.54" y2="22.399" gradientUnits="userSpaceOnUse"><stop class="qj-kypbtd"/><stop offset="1" class="lp1xml6ym"/></linearGradient><linearGradient id="iFbiIhd" x1="13.802" x2="14.418" y1="20.806" y2="20.806" gradientUnits="userSpaceOnUse"><stop class="p7a95-bzg"/><stop offset="1" class="j7b797_jr"/></linearGradient><linearGradient id="ixPjA3d" x1="16" x2="15.371" y1="18.29" y2="18.29" gradientUnits="userSpaceOnUse"><stop class="lxo6977ad"/><stop offset="1" class="ui0e-xb0n"/></linearGradient><linearGradient id="i1nK1Ab" x1="17.099" x2="17.099" y1="15.54" y2="24.923" gradientUnits="userSpaceOnUse"><stop class="v1nhr4b7v"/><stop offset="1" class="wgnseactl"/></linearGradient><linearGradient id="i29Je3b" x1="15.793" x2="16.84" y1="20.79" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="kmu00qb0d"/><stop offset="1" class="pfcwbwb-a"/></linearGradient><linearGradient id="ikkikLd" x1="16.004" x2="16.004" y1="30.056" y2="29.212" gradientUnits="userSpaceOnUse"><stop offset=".083" class="zr5tarbij"/><stop offset="1" class="jhgdrfbkn"/></linearGradient><linearGradient id="icF06hd" x1="15.582" x2="15.801" y1="10.149" y2="10.157" gradientUnits="userSpaceOnUse"><stop class="erljhfniy"/><stop offset="1" class="dyhqpo0im"/></linearGradient><linearGradient id="iqCAmtc" x1="14.231" x2="13.993" y1="5.459" y2="5.459" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="i7VLlHo" x1="18.293" x2="17.77" y1="4.884" y2="5.976" gradientUnits="userSpaceOnUse"><stop class="aa1yoduhc"/><stop offset="1" class="fbplmbrjk"/></linearGradient><linearGradient id="i1eLPae" x1="16.008" x2="16.008" y1="4.306" y2="5.103" gradientUnits="userSpaceOnUse"><stop class="qcwrlzblk"/><stop offset="1" class="mr1zqhbdw"/></linearGradient><linearGradient id="icjbRdd" x1="16.001" x2="16.001" y1="4.74" y2="6.106" gradientUnits="userSpaceOnUse"><stop class="uizhbqnqd"/><stop offset="1" class="rosr-ik5x"/></linearGradient><linearGradient id="iH9VxWd" x1="16.496" x2="16.496" y1="4.376" y2="4.243" gradientUnits="userSpaceOnUse"><stop class="zo99rm8ts"/><stop offset="1" class="qo_ozxf1o"/></linearGradient><linearGradient id="izXHRhc" x1="16.785" x2="16.785" y1="3.853" y2="3.985" gradientUnits="userSpaceOnUse"><stop offset=".464" class="x6e43ob7y"/><stop offset="1" class="p2ms6zbbw"/></linearGradient><linearGradient id="ix5Blhs" x1="15.794" x2="15.794" y1="24.728" y2="15.728" gradientUnits="userSpaceOnUse"><stop class="koq2unbkt"/><stop offset="1" class="uj-vi6bqm"/></linearGradient><linearGradient id="iVxoKjb" x1="18.029" x2="18.029" y1="24.728" y2="15.728" gradientUnits="userSpaceOnUse"><stop class="koq2unbkt"/><stop offset="1" class="uj-vi6bqm"/></linearGradient><filter id="iNpboKc" width="1.017" height="3.431" x="14.952" y="24.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_678" stdDeviation=".1"/></filter><filter id="iobD1UL" width="1.025" height="3.431" x="16.538" y="24.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_678" stdDeviation=".1"/></filter><filter id="iTqEPuc" width=".808" height=".808" x="14.637" y="12.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.164706 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_678"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_678" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_678"/></filter><filter id="iBdraFd" width=".808" height=".808" x="14.637" y="13.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.164706 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_678"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_678" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy=".02"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_678"/></filter><filter id="iMlPmac" width="1.993" height="7.488" x="12.059" y="7.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.313726 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="ighUwwd" width="1.343" height="2.384" x="18.198" y="14.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.564706 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="i04mPtc" width="1.243" height="2.484" x="12.559" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.478431 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="ilPuHEe" width="2.609" height="1.975" x="14.632" y="7.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_678" stdDeviation=".125"/></filter><filter id="izKLmEa" width="2.109" height="1.525" x="14.946" y="7.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.721569 0 0 0 0 0.611765 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="iqr7kjd" width="2.082" height="5.1" x="14.019" y="7.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.12549 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="ivVZLdc" width="2.232" height="5.1" x="15.9" y="7.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.168627 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.152941 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_678" result="effect2_innerShadow_4002_678"/></filter><filter id="iyNozZc" width="1.74" height="1.74" x="13.361" y="4.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_678" stdDeviation=".25"/></filter><filter id="i0qbkIb" width="1.342" height="1.342" x="17.149" y="4.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="iX3nZ6c" width="1.74" height="1.74" x="16.9" y="4.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_678" stdDeviation=".25"/></filter><filter id="i1cVpgc" width=".541" height=".892" x="13.697" y="4.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.356863 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="iMYEmdw" width=".521" height=".894" x="17.798" y="4.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.407843 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="iMIRSOO" width="1.018" height=".57" x="16.467" y="4.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.184314 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="izCvmoe" width=".968" height=".62" x="14.559" y="4.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.176471 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="iPuHBDc" width="3.598" height="1.366" x="14.202" y="4.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="iwF25ic" width="1.455" height="1.26" x="14.418" y="4.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.105882 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="iQZQkbd" width="1.455" height="1.26" x="16.238" y="4.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.105882 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_678"/></filter><filter id="iL5LHSA" width="2.284" height="10.3" x="13.987" y="15.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_678" stdDeviation=".325"/></filter><filter id="iFM23ie" width="2.284" height="10.3" x="16.221" y="15.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_678" stdDeviation=".325"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-suit-levitating" /></template>
<style>
.a_5l2kb-s {
  d: path("m15.855 5.198l-.198.669c-.04.137.057.274.194.274h.292c.137 0 .234-.14.194-.274l-.198-.669a.147.147 0 0 0-.284 0");
}

.aa1yoduhc {
  stop-color: var(--svg-color--ffca44, #FFCA44);
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

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
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

.c4zuphbey {
  stop-color: var(--svg-color--dca73b, #DCA73B);
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

.cihrumz2d {
  cx: 17.77px;
  cy: 5.355px;
  r: 0.37px;
}

.ck-8zfmjj {
  stop-color: var(--svg-color--3a2e46, #3A2E46);
}

.d2iy96bbj {
  stop-color: var(--svg-color--eb9538, #EB9538);
  stop-opacity: 0;
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

.e_mvkligi {
  stop-color: var(--svg-color--d48a3c, #D48A3C);
}

.e_sl96bsv {
  d: path("M12.559 15.505h1.243v-.48h-1.243z");
}

.e3gx51wtu {
  stop-color: var(--svg-color--5b496d, #5B496D);
  stop-opacity: 0;
}

.e4487pbsf {
  stop-color: var(--svg-color--f19f2f, #F19F2F);
}

.e7gjqi8ys {
  d: path("M13.802 15.54H16v9.383h-2.198z");
}

.eksmwwbms {
  stop-color: var(--svg-color--ffd836, #FFD836);
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

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f46cj4b8l {
  stop-color: var(--svg-color--43295a, #43295A);
}

.fbplmbrjk {
  stop-color: var(--svg-color--f7b937, #F7B937);
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

.g4assg31z {
  stop-color: var(--svg-color--d87732, #D87732);
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

.hp8joq9cc {
  stop-color: var(--svg-color--d3823e, #D3823E);
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

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.k9cr8rb3u {
  cx: 14.231px;
  cy: 5.355px;
  r: 0.37px;
}

.k9hymybji {
  stop-color: var(--svg-color--b36658, #B36658);
  stop-opacity: 0;
}

.kmu00qb0d {
  stop-color: var(--svg-color--2c183c, #2C183C);
}

.kn7lfdclf {
  d: path("M14.91 10.134v-2.89h2.274v2.89c-.182 1.169-.878 1.83-1.204 2.015c-.756-.48-1.028-1.544-1.07-2.015");
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

.lnay1fcot {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.997 6.52c-.189 0-.366-.045-.515-.123c-.051-.026-.106.032-.074.078a.7.7 0 0 0 .59.315a.7.7 0 0 0 .588-.315c.032-.048-.023-.104-.074-.078a1.1 1.1 0 0 1-.515.122");
}

.lp1xml6ym {
  stop-color: var(--svg-color--543873, #543873);
}

.lvi8nmbhj {
  stop-color: var(--svg-color--ffd23f, #FFD23F);
}

.lxo6977ad {
  stop-color: var(--svg-color--362549, #362549);
}

.mm4i4_zhz {
  stop-color: var(--svg-color--fe922e, #FE922E);
}

.mr1zqhbdw {
  stop-color: var(--svg-color--dc8b29, #DC8B29);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n219yccxp {
  stop-color: var(--svg-color--3e2031, #3E2031);
}

.n5kv48x3v {
  stop-color: var(--svg-color--f1d9ff, #F1D9FF);
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

.o7-vrmbvg {
  stop-color: var(--svg-color--e8a540, #E8A540);
}

.owa7czdbk {
  stop-color: var(--svg-color--dd886a, #DD886A);
}

.oxq_1loir {
  d: path("M14.637 15.728h.984v9h-.984z");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
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

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
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

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q77rl012p {
  d: path("M16.871 15.728h.984v9h-.984z");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.q9y0fcvnp {
  d: path("M15.426 11.673c.095-.965.261-1.828.36-2.48h.433l.006.039c.174 1.08.298 1.844.341 2.441l-.554.476z");
}

.qcwrlzblk {
  stop-color: var(--svg-color--dc8b29, #DC8B29);
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

.qowwj230w {
  d: path("M17.895 5.17c.049-.005.133-.038.201-.154c.08-.135.148-.55.173-.741h-.471c.154.116.147.188.133.327l-.001.01l-.009.148a6 6 0 0 1-.025.388z");
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

.rkj830b-m {
  d: path("M17.594 5.11a.25.25 0 0 0-.25-.25h-.806a.3.3 0 0 0-.3.3v.36a.5.5 0 0 0 .5.5h.356a.5.5 0 0 0 .5-.5z");
}

.rosr-ik5x {
  stop-color: var(--svg-color--39294a, #39294A);
}

.rutxg0bgb {
  stop-color: var(--svg-color--eea833, #EEA833);
}

.s3_x2f0ah {
  stop-color: var(--svg-color--52495e, #52495E);
  stop-opacity: 0;
}

.s6odk1prq {
  stop-color: var(--svg-color--96929b, #96929B);
}

.sa0syexyw {
  stop-color: var(--svg-color--fcac34, #FCAC34);
}

.sfy4td0pz {
  stop-color: var(--svg-color--4a3d5b, #4A3D5B);
}

.sfyf3vb1f {
  stop-color: var(--svg-color--453752, #453752);
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

.t8ohmc0fu {
  stop-color: var(--svg-color--b287ab, #B287AB);
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

.ughf7bc6g {
  stop-color: var(--svg-color--b36658, #B36658);
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

.vczrvlbbh {
  stop-color: var(--svg-color--da9d21, #DA9D21);
}

.ve43lhu_q {
  d: path("M14.418 5.11a.25.25 0 0 1 .25-.25h.805a.3.3 0 0 1 .3.3v.36a.5.5 0 0 1-.5.5h-.355a.5.5 0 0 1-.5-.5z");
}

.vvnqwub4r {
  fill: var(--svg-color--a53a43, #A53A43);
  d: path("M16.66 4.535c.267-.025.439.08.48.118a.176.176 0 0 0 .239-.259c-.114-.105-.384-.244-.752-.21a.176.176 0 0 0 .032.35");
}

.w-3cr34sa {
  d: path("M14.078 4.592c0 .086.012.419.022.535l.003.04c-.05-.01-.123-.048-.183-.15c-.08-.136-.149-.551-.173-.742h.49l-.039.04c-.08.059-.12.178-.12.277");
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

.x4ypq9i6l {
  d: path("M18.199 15.025h1.242v.99c0 .687-.718 1.119-1.242 1.244z");
}

.x6e43ob7y {
  stop-color: var(--svg-color--4a3d57, #4A3D57);
}

.xdk4w7bjh {
  cx: 14.231px;
  cy: 5.355px;
  r: 0.621px;
}

.xn9w1abgm {
  stop-color: var(--svg-color--423255, #423255);
}

.xq-_dvbek {
  stop-color: var(--svg-color--bfa3d9, #BFA3D9);
}

.y9ylhyjkb {
  stop-color: var(--svg-color--c4994f, #C4994F);
}

.yd1ukgyzh {
  stop-color: var(--svg-color--db9014, #DB9014);
}

.yjdgn6b_j {
  fill: var(--svg-color--a389b4, #A389B4);
  d: path("M14.882 7.718c0 .342.019.948.479 1.414c.088.089.23.078.31-.02c.081-.1.177-.232.257-.374a.01.01 0 0 1 .017 0c.08.142.176.274.258.375a.21.21 0 0 0 .31.019c.46-.466.478-1.072.478-1.414z");
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

.z67jedbbr {
  cx: 17.77px;
  cy: 5.355px;
  r: 0.37px;
  fill: var(--svg-color--ffbf34, #FFBF34);
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

.zv83v_bcv {
  fill: var(--svg-color--974037, #974037);
  fill-rule: evenodd;
  d: path("M15.335 4.535c-.268-.025-.44.08-.481.118a.176.176 0 0 1-.238-.259c.114-.105.383-.244.752-.21a.176.176 0 0 1-.033.35");
}

</style>
