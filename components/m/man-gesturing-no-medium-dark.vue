<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iUFJvQe)"><circle fill="url(#irpnO0c)" class="w8l-sqdgg"/></g><g filter="url(#iMDi8Rc)"><circle fill="url(#irF2Zxd)" class="ju9_if7ms"/></g><g filter="url(#ioAOdtb)"><circle fill="url(#iwwh99b)" class="zmv_7hb2s"/><circle fill="url(#i6oV4ke)" class="zmv_7hb2s"/></g><g filter="url(#ilc3Opc)"><circle class="tfzo59d4z"/><circle fill="url(#igVGhAc)" class="xfh2-qzxa"/><circle fill="url(#it2ONmc)" class="xfh2-qzxa"/></g><g filter="url(#ipBi9pc)"><path fill="url(#ilfhX4d)" class="ebi1hiyto"/><path fill="url(#irJMoUl)" class="ebi1hiyto"/><path fill="url(#iDlcCMc)" class="ebi1hiyto"/></g><path fill="url(#iiDfiOd)" class="tw2wpq-yc"/><path fill="url(#iJ1SeJe)" class="tw2wpq-yc"/><path fill="url(#iZ5Lvpc)" class="tw2wpq-yc"/><path fill="url(#ij0veyc)" class="tw2wpq-yc"/><path fill="url(#iGCAP5d)" class="tw2wpq-yc"/><g filter="url(#i7ZEffb)"><path fill="url(#idYhDzK)" class="f9w3ozb6m"/></g><g filter="url(#ic6HUze)"><path class="jyvzb55ot"/><path fill="url(#iajJpJc)" class="uqve2xycv"/><path fill="url(#i1tCwLb)" class="uqve2xycv"/><path fill="url(#ixaFCyd)" class="uqve2xycv"/><path fill="url(#iuiXcje)" class="uqve2xycv"/></g><g filter="url(#iJnkORc)"><path class="jafrrlcuv"/></g><g filter="url(#i1VLZqe)"><path class="di-rk30zo"/><path fill="url(#izo2l0v)" class="zv7v3hber"/><path fill="url(#iuuqO6c)" class="zv7v3hber"/><path fill="url(#izzBWHO)" class="zv7v3hber"/><path fill="url(#iynIjIk)" class="zv7v3hber"/></g><path fill="url(#i8AQSWb)" class="zv7v3hber"/><path class="wy3pbiouc"/><path fill="url(#igNzEAv)" class="lzk0i3bwh"/><path class="vlixws18p"/><g filter="url(#ilt9woe)"><path class="lo9pekb6g"/><path fill="url(#iPUXQ1c)" class="qp6m8bcoh"/></g><g filter="url(#i7lcuna)"><path fill="url(#iE5kIvA)" class="idic3tbmx"/></g><path class="iyx22sb9r"/><path fill="url(#iTAYQ4v)" class="i139ewoef"/><path class="z5qepe3br"/><g filter="url(#iLwjAOc)"><path fill="url(#irjc2Rc)" class="gm7a-nbkx"/></g><g filter="url(#iWqJqNb)"><ellipse transform="rotate(-27.914 12.8 11.953)" class="ql8nr6veo"/><ellipse fill="url(#ifRPxoc)" transform="rotate(-27.914 12.8 11.953)" class="pn1b9mm5r"/></g><g filter="url(#iiLnvxd)"><path stroke="url(#iPLuGPc)" class="ea5v_130k"/></g><path class="m4lq5dbsw"/><path fill="url(#iIkC8Hc)" class="vdbpvroyq"/><path fill="url(#iGigNPe)" class="vdbpvroyq"/><path fill="url(#ileIKXd)" class="vdbpvroyq"/><path fill="url(#iyZPTre)" class="jus79jbyy"/><path fill="url(#iRlZgYc)" class="jidy2xu-t"/><path fill="url(#iWkgQJe)" class="jidy2xu-t"/><path fill="url(#iYcpe6b)" class="jidy2xu-t"/><path fill="url(#iBOUt9d)" class="jidy2xu-t"/><path fill="url(#iLbTnge)" class="jidy2xu-t"/><path fill="url(#iFWGNob)" class="jidy2xu-t"/><path fill="url(#i6sN0hc)" class="jidy2xu-t"/><path fill="url(#iYD891c)" class="uritxubxy"/><path fill="url(#iUQEvTy)" class="va-dzqbbo"/><path fill="url(#iFlSOTb)" class="va-dzqbbo"/><path fill="url(#iEGCFWd)" class="va-dzqbbo"/><path fill="url(#i08Un9c)" class="va-dzqbbo"/><path fill="url(#itrBxAd)" class="va-dzqbbo"/><path fill="url(#iGzeGEd)" class="wymjbgbqv"/><path fill="url(#iGbGAGb)" class="wymjbgbqv"/><path fill="url(#iBaeXBc)" class="wymjbgbqv"/><path fill="url(#ie95AYP)" class="yuv68hbvz"/><path fill="url(#iOvHQXd)" class="yuv68hbvz"/><path fill="url(#iLpPYab)" class="exo5v8bwa"/><path fill="url(#ibcJFUc)" class="exo5v8bwa"/><path fill="url(#inW0BKc)" class="exo5v8bwa"/><path fill="url(#iLuRAzV)" class="exo5v8bwa"/><g filter="url(#iCerGre)"><path fill="url(#ivbteqe)" class="rnhytm_ty"/><path fill="url(#iAGHLOb)" class="rnhytm_ty"/></g><path fill="url(#iJIqeHe)" class="rnhytm_ty"/><g filter="url(#iFrjYod)"><path clip-rule="evenodd" class="bpmv5u7-x"/></g><g filter="url(#izHlwMb)"><path class="zv5d5z9ye"/></g><g filter="url(#iHmQ7ie)"><path clip-rule="evenodd" class="r2c43rbig"/></g><g filter="url(#iVnje7d)"><path class="m2cm06bfn"/></g><g filter="url(#iSVNAYW)"><path fill="url(#iLDMoCd)" class="pnxj8pb1l"/></g><defs><radialGradient id="irpnO0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.27915 0 0 3.98853 7.654 13.242)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="i6oV4ke" cx="0" cy="0" r="1" gradientTransform="matrix(1.07369 -.78181 .89233 1.22547 22.661 12.898)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="igVGhAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.06662 -1.96182 1.14826 .6243 22.124 14.309)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="it2ONmc" cx="0" cy="0" r="1" gradientTransform="matrix(.33675 .33333 -.42972 .43412 22.178 13.242)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="irJMoUl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69758 2.08933 0 19.036 11.59)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iDlcCMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.78464 2.21936 0 13.116 11.765)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iZ5Lvpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6208 -14.4171 0 15.597 10.938)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="expufxtqh"/><stop offset="1" class="cpvcnac5k"/></radialGradient><radialGradient id="iGCAP5d" cx="0" cy="0" r="1" gradientTransform="matrix(.48546 -5.2361 6.68944 .6202 13.036 18.72)" gradientUnits="userSpaceOnUse"><stop class="gh8vo29ry"/><stop offset="1" class="ziu9nybix"/></radialGradient><radialGradient id="iajJpJc" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 15.98 -10.167)scale(3.97728 1.4749)" gradientUnits="userSpaceOnUse"><stop class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="i1tCwLb" cx="0" cy="0" r="1" gradientTransform="matrix(4.96754 .45715 -.2458 2.67101 19.5 5.624)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="ixaFCyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.18084 -3.37751 0 15.989 2.071)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iuiXcje" cx="0" cy="0" r="1" gradientTransform="matrix(3.99232 -2.92567 4.58356 6.25465 7.613 10.926)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iynIjIk" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25572 -.82159 0 16.413 14.774)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="igNzEAv" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05346 -1.67565 0 18.818 12.077)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iPUXQ1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.30114 -.38805 .53426 -.41459 18.522 12.185)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTAYQ4v" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05352 -1.67574 0 13.152 12.077)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ifRPxoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64155 .77117 -.01207 12.78 12.362)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIkC8Hc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.562 30.332)" gradientUnits="userSpaceOnUse"><stop class="mebiusz6j"/><stop offset=".714" class="tzc2eqbez"/></radialGradient><radialGradient id="iGigNPe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.366)" gradientUnits="userSpaceOnUse"><stop class="tkk3fh7lv"/><stop offset="1" class="wltqj-b_b"/></radialGradient><radialGradient id="ileIKXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.148)" gradientUnits="userSpaceOnUse"><stop class="stmwvtbwq"/><stop offset="1" class="mbu8hk88e"/></radialGradient><radialGradient id="iyZPTre" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.345 17.17)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="lht-5qo7r"/><stop offset="1" class="c83rl0b_v"/></radialGradient><radialGradient id="iRlZgYc" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 14.913 18.585)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="a7qi3ibbq"/><stop offset="1" class="isu90b6vd"/></radialGradient><radialGradient id="iWkgQJe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.80476 2.04336 -1.52855 -3.59423 29 24.832)" gradientUnits="userSpaceOnUse"><stop class="bpjtw3boo"/><stop offset="1" class="g_enp1bol"/></radialGradient><radialGradient id="iYcpe6b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07575 5.3158 -8.32749 -3.25178 14.245 17.613)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="avgknr4aj"/><stop offset="1" class="xp9lv-a7q"/></radialGradient><radialGradient id="iLbTnge" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.318 -3.11)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="pe78akl1z"/><stop offset="1" class="epnh4ac5k"/></radialGradient><radialGradient id="i6sN0hc" cx="0" cy="0" r="1" gradientTransform="matrix(8.43038 -3.42291 .46766 1.15182 16.663 24.833)" gradientUnits="userSpaceOnUse"><stop offset=".314" class="mzcr1bvpw"/><stop offset="1" class="ms91oy-xv"/></radialGradient><radialGradient id="iYD891c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.405 17.738)" gradientUnits="userSpaceOnUse"><stop class="h3jyzg19k"/><stop offset="1" class="fo5-hs3pv"/></radialGradient><radialGradient id="iUQEvTy" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.804)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a6fx42bik"/><stop offset="1" class="lrp5mrmlg"/></radialGradient><radialGradient id="iGzeGEd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.39)" gradientUnits="userSpaceOnUse"><stop class="qyctpef7w"/><stop offset=".615" class="cskv_pboi"/></radialGradient><radialGradient id="ie95AYP" cx="0" cy="0" r="1" gradientTransform="rotate(25.705 -36.907 15.748)scale(1.9602 2.66792)" gradientUnits="userSpaceOnUse"><stop class="t0phas2np"/><stop offset=".697" class="f1gbiwx_q"/></radialGradient><radialGradient id="iOvHQXd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8664 .26697 -.4987 -1.61843 4.82 17.128)" gradientUnits="userSpaceOnUse"><stop class="w_6w3opsv"/><stop offset="1" class="u9mvxzbci"/></radialGradient><radialGradient id="iLpPYab" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.288 6.317)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="g4wyz37uu"/><stop offset="1" class="xjh-ixbfp"/></radialGradient><radialGradient id="ibcJFUc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.16 13.148)" gradientUnits="userSpaceOnUse"><stop class="d-by8cbiw"/><stop offset="1" class="hqjfx29jv"/></radialGradient><radialGradient id="iLuRAzV" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 -1.125 1.20473 2.50986 24.583 19.96)" gradientUnits="userSpaceOnUse"><stop class="ma1u1iuqv"/><stop offset="1" class="rizivib-o"/></radialGradient><radialGradient id="iAGHLOb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.209)" gradientUnits="userSpaceOnUse"><stop class="whmlezbbn"/><stop offset="1" class="r8d20-6qp"/></radialGradient><radialGradient id="iJIqeHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.00475 -.26214 .85754 3.28688 4.382 18.113)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="bwst52bsk"/><stop offset="1" class="br5e4xb7k"/></radialGradient><linearGradient id="irF2Zxd" x1="9.822" x2="8.99" y1="13.604" y2="13.604" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iwwh99b" x1="23.589" x2="22.526" y1="11.825" y2="15.119" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="ilfhX4d" x1="21.23" x2="11.312" y1="13.748" y2="15.226" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iiDfiOd" x1="8.981" x2="11.424" y1="17.25" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iJ1SeJe" x1="22.306" x2="20.935" y1="16.161" y2="16.031" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="ij0veyc" x1="16.026" x2="16.026" y1="20.363" y2="21.726" gradientUnits="userSpaceOnUse"><stop offset=".533" class="m8c2yi15h"/><stop offset="1" class="vbfhreb6b"/></linearGradient><linearGradient id="idYhDzK" x1="15.298" x2="25.875" y1="9.872" y2="6.085" gradientUnits="userSpaceOnUse"><stop class="y3qu8-b1b"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="izo2l0v" x1="14.866" x2="16.085" y1="14.049" y2="14.049" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iuuqO6c" x1="17.207" x2="15.875" y1="14.468" y2="14.449" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="izzBWHO" x1="16.241" x2="16.241" y1="15.432" y2="14.688" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="i8AQSWb" x1="16.152" x2="16.152" y1="15.487" y2="15.269" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iE5kIvA" x1="19.829" x2="19.421" y1="12.147" y2="12.398" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irjc2Rc" x1="14.118" x2="13.71" y1="12.147" y2="12.398" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPLuGPc" x1="9.934" x2="9.934" y1="6.865" y2="9.667" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="iBOUt9d" x1="9.156" x2="10.486" y1="18.429" y2="19.052" gradientUnits="userSpaceOnUse"><stop class="y6shzzc0m"/><stop offset="1" class="gvfnv53tr"/></linearGradient><linearGradient id="iFWGNob" x1="17.482" x2="17.906" y1="26.634" y2="25.679" gradientUnits="userSpaceOnUse"><stop class="oo6zkeb_e"/><stop offset=".46" class="bw5w8zblw"/></linearGradient><linearGradient id="iFlSOTb" x1="15.132" x2="14.231" y1="27.489" y2="25.466" gradientUnits="userSpaceOnUse"><stop offset=".205" class="boish7bqf"/><stop offset="1" class="dalry_j2d"/></linearGradient><linearGradient id="iEGCFWd" x1="10.345" x2="11.438" y1="19.38" y2="21.911" gradientUnits="userSpaceOnUse"><stop class="m8jyzebhe"/><stop offset="1" class="h7od31b_t"/></linearGradient><linearGradient id="i08Un9c" x1="22.827" x2="21.613" y1="18.74" y2="19.303" gradientUnits="userSpaceOnUse"><stop class="r_-h96bdp"/><stop offset="1" class="tvrmq9s8w"/></linearGradient><linearGradient id="itrBxAd" x1="3.231" x2="6.517" y1="28.216" y2="26.609" gradientUnits="userSpaceOnUse"><stop class="vxp4qyb9c"/><stop offset="1" class="amr862j1l"/></linearGradient><linearGradient id="iGbGAGb" x1="28.085" x2="27.547" y1="19.435" y2="18.604" gradientUnits="userSpaceOnUse"><stop offset=".198" class="y5l4vob7e"/><stop offset="1" class="yemvrmxbd"/></linearGradient><linearGradient id="iBaeXBc" x1="26.75" x2="27.494" y1="17.319" y2="18.079" gradientUnits="userSpaceOnUse"><stop offset=".353" class="vhav-abny"/><stop offset="1" class="m754bqf9r"/></linearGradient><linearGradient id="inW0BKc" x1="25.489" x2="25.997" y1="14.21" y2="15.11" gradientUnits="userSpaceOnUse"><stop class="sghkjcc6n"/><stop offset="1" class="n39i5izax"/></linearGradient><linearGradient id="ivbteqe" x1="8" x2="5.5" y1="15.679" y2="19.445" gradientUnits="userSpaceOnUse"><stop offset=".206" class="inmwvkbzn"/><stop offset="1" class="myckyxb_u"/></linearGradient><linearGradient id="iLDMoCd" x1="29.179" x2="24.036" y1="14.775" y2="17.642" gradientUnits="userSpaceOnUse"><stop class="hdh7eybjd"/><stop offset="1" class="d3plm5x9f"/></linearGradient><filter id="iUFJvQe" width="4.536" height="4.336" x="7.654" y="11.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24799"/></filter><filter id="iMDi8Rc" width="3.584" height="3.584" x="8.03" y="11.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".25"/></filter><filter id="ioAOdtb" width="4.586" height="4.586" x="20.009" y="10.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24799"/></filter><filter id="ilc3Opc" width="3.584" height="3.584" x="20.386" y="11.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".25"/></filter><filter id="ipBi9pc" width="13.473" height="15.871" x="9.29" y="5.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24799"/></filter><filter id="i7ZEffb" width="9.515" height="7.983" x="14.209" y="3.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation="1"/></filter><filter id="ic6HUze" width="16.366" height="10.947" x="7.805" y="1.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24799"/></filter><filter id="iJnkORc" width="3.786" height="4.982" x="13.785" y="11.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".375"/></filter><filter id="i1VLZqe" width="2.938" height="3.982" x="14.52" y="11.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".125"/></filter><filter id="ilt9woe" width=".962" height=".844" x="17.895" y="11.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".05"/></filter><filter id="i7lcuna" width="1.038" height="1.067" x="19.015" y="11.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".1"/></filter><filter id="iLwjAOc" width="1.161" height="1.231" x="13.247" y="11.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".1"/></filter><filter id="iWqJqNb" width="1.126" height=".855" x="12.237" y="11.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".05"/></filter><filter id="iiLnvxd" width="1.085" height="2.723" x="9.391" y="6.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".125"/></filter><filter id="iCerGre" width="7.3" height="8.016" x="2" y="12.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.290196 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24799"/></filter><filter id="iFrjYod" width="3.594" height="2.063" x="11.046" y="8.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0862745 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24799"/></filter><filter id="izHlwMb" width="3.094" height="1.313" x="11.296" y="9.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".125"/></filter><filter id="iHmQ7ie" width="3.594" height="2.063" x="17.523" y="8.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0862745 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24799"/></filter><filter id="iVnje7d" width="3.094" height="1.313" x="17.773" y="9.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".125"/></filter><filter id="iSVNAYW" width="5.538" height="5.423" x="24.159" y="13.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24799" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-no-medium-dark" /></template>
<style>
.a6fx42bik {
  stop-color: var(--svg-color--1fa4f0, #1FA4F0);
}

.a7qi3ibbq {
  stop-color: var(--svg-color--32a6f9, #32A6F9);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.amr862j1l {
  stop-color: var(--svg-color--3869b0, #3869B0);
  stop-opacity: 0;
}

.avgknr4aj {
  stop-color: var(--svg-color--28bbff, #28BBFF);
}

.boish7bqf {
  stop-color: var(--svg-color--0d7edf, #0D7EDF);
}

.bpjtw3boo {
  stop-color: var(--svg-color--47bbff, #47BBFF);
}

.bpmv5u7-x {
  fill: var(--svg-color--352725, #352725);
  fill-rule: evenodd;
  d: path("M14.623 9.405a.625.625 0 0 1-.462.753l-2.344.563a.625.625 0 1 1-.292-1.216l2.344-.562a.625.625 0 0 1 .754.462");
}

.br5e4xb7k {
  stop-color: var(--svg-color--805c58, #805C58);
  stop-opacity: 0;
}

.bw5w8zblw {
  stop-color: var(--svg-color--4466c2, #4466C2);
  stop-opacity: 0;
}

.bwst52bsk {
  stop-color: var(--svg-color--805c58, #805C58);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c83rl0b_v {
  stop-color: var(--svg-color--1f5491, #1F5491);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvcnac5k {
  stop-color: var(--svg-color--7d4371, #7D4371);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cskv_pboi {
  stop-color: var(--svg-color--794f40, #794F40);
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d-by8cbiw {
  stop-color: var(--svg-color--9d7d73, #9D7D73);
}

.d3plm5x9f {
  stop-color: var(--svg-color--9c7b72, #9C7B72);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dalry_j2d {
  stop-color: var(--svg-color--0d7edf, #0D7EDF);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.di-rk30zo {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.492 12.317l-.69 2.207a.7.7 0 0 0 .676.908h1.021a.702.702 0 0 0 .676-.908l-.69-2.207c-.148-.49-.838-.49-.993 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ea5v_130k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.102 6.993V8.16c-.01.193-.092.625-.336.808");
}

.ebi1hiyto {
  d: path("m9.365 12.446l.064.003s-.07-1.109-.14-1.87c0-.347.14-.763.419-.97l.209-.208c.348-.277.487-.693.487-1.108V7.184c0-.346.21-.623.557-.692c.836-.208 2.578-.555 5.086-.555s4.25.347 5.086.555c.278.069.557.346.557.692v1.109c0 .415.209.83.487 1.108c.653.457.612.708.558 1.247c-.07.692-.14 1.87-.14 1.87h.024l-.345 5.14c-.209 2.299-2.015 3.9-4.17 3.9h-4.17c-2.223 0-3.96-1.601-4.169-3.9z");
}

.epnh4ac5k {
  stop-color: var(--svg-color--527faa, #527FAA);
  stop-opacity: 0;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.exo5v8bwa {
  d: path("m23 15.999l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.expufxtqh {
  stop-color: var(--svg-color--7d4371, #7D4371);
  stop-opacity: 0;
}

.f1gbiwx_q {
  stop-color: var(--svg-color--6a3849, #6A3849);
}

.f9w3ozb6m {
  d: path("M21.136 5.937L17.14 7.27a1.36 1.36 0 0 0 .611 2.638l3.974-.532z");
}

.fo5-hs3pv {
  stop-color: var(--svg-color--1474c2, #1474C2);
}

.ft5dv1b6b {
  fill: none;
}

.g_enp1bol {
  stop-color: var(--svg-color--309ff1, #309FF1);
  stop-opacity: 0;
}

.g4wyz37uu {
  stop-color: var(--svg-color--8f655e, #8F655E);
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gh8vo29ry {
  stop-color: var(--svg-color--5d4842, #5D4842);
}

.gm7a-nbkx {
  d: path("M14.208 12.48c0-.374-.305-.624-.387-.7l-.374.363l.23.469z");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gvfnv53tr {
  stop-color: var(--svg-color--047fc0, #047FC0);
  stop-opacity: 0;
}

.h3jyzg19k {
  stop-color: var(--svg-color--288dcd, #288DCD);
}

.h7od31b_t {
  stop-color: var(--svg-color--1481b9, #1481B9);
  stop-opacity: 0;
}

.hdh7eybjd {
  stop-color: var(--svg-color--9c7b72, #9C7B72);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hqjfx29jv {
  stop-color: var(--svg-color--9d7d73, #9D7D73);
  stop-opacity: 0;
}

.i139ewoef {
  d: path("M13.15 11.457a1.16 1.16 0 0 0-1.117 1.465h2.238q.041-.148.042-.306a1.167 1.167 0 0 0-1.164-1.159");
}

.idic3tbmx {
  d: path("M19.853 12.464a1.1 1.1 0 0 0-.3-.601l-.338.37l.153.297z");
}

.inmwvkbzn {
  stop-color: var(--svg-color--916a5a, #916A5A);
}

.isu90b6vd {
  stop-color: var(--svg-color--1b73d2, #1B73D2);
}

.iyx22sb9r {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.88 11.105c-.847 0-1.564.584-1.759 1.374a.356.356 0 0 0 .348.443h2.897a.3.3 0 0 0 .295-.353a1.82 1.82 0 0 0-1.78-1.465");
}

.jafrrlcuv {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.631 12.529l-1.065 2.207c-.132.454.184.908.633.908h.958c.449 0 .766-.461.634-.908l-.647-2.207c-.139-.49-.368-.49-.513 0");
}

.jidy2xu-t {
  d: path("m11.56 16.027l15.407 7.178a3.53 3.53 0 0 1 1.7 4.687a3.52 3.52 0 0 1-4.679 1.704L8.581 22.408a1 1 0 0 1-.483-1.34l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.ju9_if7ms {
  cx: 9.822px;
  cy: 13.242px;
  r: 1.292px;
}

.jus79jbyy {
  d: path("m6.81 20.499l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.jyvzb55ot {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m22.247 4.83l.558.276c.975.485 1.532 1.593 1.323 2.77l-.766 3.95c-.068.407-.338.681-.743.692h-.023s.07-1.178.139-1.87c.056-.563-.042-.734-.557-1.247c-.28-.277-.488-.693-.488-1.108V7.184c0-.346-.279-.623-.557-.692c-.836-.208-2.578-.555-5.086-.555s-4.25.347-5.086.555c-.348.069-.557.346-.557.692v1.109c0 .415-.14.83-.487 1.108l-.21.208c-.278.207-.417.623-.417.97c.07.761.139 1.87.139 1.87q-.033 0-.064-.003a.82.82 0 0 1-.772-.69l-.766-3.948c-.14-1.109.418-2.217 1.393-2.702l.557-.277c.349-.208.697-.485 1.045-.762l1.254-1.316c.766-.693 1.881-.9 2.856-.415a3.8 3.8 0 0 0 2.16 0c1.045-.347 2.23-.07 3.065.692l1.045 1.04c.279.346.627.553 1.045.761");
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lht-5qo7r {
  stop-color: var(--svg-color--3592c8, #3592C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lo9pekb6g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.736 11.702c.082.11-.09.245-.286.392c-.197.147-.342.25-.425.14s.01-.32.206-.466s.422-.176.505-.066");
}

.lrp5mrmlg {
  stop-color: var(--svg-color--1892ed, #1892ED);
}

.lzk0i3bwh {
  d: path("M18.821 11.457a1.16 1.16 0 0 1 1.117 1.465h-2.239q-.04-.149-.042-.306c0-.637.521-1.159 1.164-1.159");
}

.m2cm06bfn {
  stroke: var(--svg-color--473d3d, #473D3D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m20.491 9.95l-2.343-.563");
}

.m4lq5dbsw {
  fill: var(--svg-color--86004e, #86004E);
  d: path("M15.989 19.38c.791 0 1.433-.69 1.433-1.538c0-.85-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.642 1.537 1.433 1.537");
}

.m754bqf9r {
  stop-color: var(--svg-color--734a39, #734A39);
  stop-opacity: 0;
}

.m8c2yi15h {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
  stop-opacity: 0;
}

.m8jyzebhe {
  stop-color: var(--svg-color--1481b9, #1481B9);
}

.ma1u1iuqv {
  stop-color: var(--svg-color--7e4a51, #7E4A51);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbu8hk88e {
  stop-color: var(--svg-color--3b7ea8, #3B7EA8);
  stop-opacity: 0;
}

.mebiusz6j {
  stop-color: var(--svg-color--1f70c6, #1F70C6);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.ms91oy-xv {
  stop-color: var(--svg-color--1a62c7, #1A62C7);
  stop-opacity: 0;
}

.myckyxb_u {
  stop-color: var(--svg-color--713e45, #713E45);
}

.mzcr1bvpw {
  stop-color: var(--svg-color--1a62c7, #1A62C7);
}

.n39i5izax {
  stop-color: var(--svg-color--704b3d, #704B3D);
  stop-opacity: 0;
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oo6zkeb_e {
  stop-color: var(--svg-color--4466c2, #4466C2);
}

.pe78akl1z {
  stop-color: var(--svg-color--527faa, #527FAA);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn1b9mm5r {
  cx: 12.8px;
  cy: 11.953px;
  rx: 0.506px;
  ry: 0.256px;
}

.pnxj8pb1l {
  d: path("M26.653 15.551c.527-.846 1.795-1.664 2.462-1.987a.13.13 0 0 1 .152.034a.132.132 0 0 1-.033.196c-2.06 1.273-1.875 1.784-2.645 3.097c-.355.604-1.177 1.112-1.557 1.284l-.473-.899c.53-.28 1.462-.711 2.094-1.725");
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.ql8nr6veo {
  cx: 12.8px;
  cy: 11.953px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.qp6m8bcoh {
  d: path("M18.736 11.702c.082.11-.09.245-.286.392c-.197.147-.342.25-.425.14s.01-.32.206-.466s.422-.176.505-.066");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyctpef7w {
  stop-color: var(--svg-color--9a7b71, #9A7B71);
}

.r_-h96bdp {
  stop-color: var(--svg-color--46c3ff, #46C3FF);
}

.r2c43rbig {
  fill: var(--svg-color--352725, #352725);
  fill-rule: evenodd;
  d: path("M17.54 9.405a.625.625 0 0 0 .462.753l2.344.563a.625.625 0 1 0 .291-1.216l-2.344-.562a.625.625 0 0 0-.753.462");
}

.r8d20-6qp {
  stop-color: var(--svg-color--8d6d68, #8D6D68);
  stop-opacity: 0;
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rizivib-o {
  stop-color: var(--svg-color--7e4a51, #7E4A51);
  stop-opacity: 0;
}

.rnhytm_ty {
  d: path("m9 15.999l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sghkjcc6n {
  stop-color: var(--svg-color--704b3d, #704B3D);
}

.stmwvtbwq {
  stop-color: var(--svg-color--3b7ea8, #3B7EA8);
}

.t0phas2np {
  stop-color: var(--svg-color--694641, #694641);
}

.tfzo59d4z {
  cx: 22.178px;
  cy: 13.242px;
  r: 1.292px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tkk3fh7lv {
  stop-color: var(--svg-color--3fc3ff, #3FC3FF);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tvrmq9s8w {
  stop-color: var(--svg-color--46c3ff, #46C3FF);
  stop-opacity: 0;
}

.tw2wpq-yc {
  d: path("M9.29 10.578c0-.346.139-.762.418-.97l.209-.207c.348-.277.487-.693.487-1.108V7.184c0-.346.21-.623.557-.692c.836-.208 2.578-.555 5.086-.555s4.25.347 5.086.555c.278.069.557.346.557.692v1.109c0 .415.209.83.487 1.108c.653.457.612.708.558 1.247c-.07.692-.14 1.87-.14 1.87h.024l-.345 5.14c-.209 2.299-2.015 3.9-4.17 3.9h-4.17c-2.223 0-3.96-1.601-4.169-3.9c-.18-2.359-.26-4.725-.475-7.08");
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.tzc2eqbez {
  stop-color: var(--svg-color--075ab5, #075AB5);
}

.u9mvxzbci {
  stop-color: var(--svg-color--592f28, #592F28);
  stop-opacity: 0;
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uqve2xycv {
  d: path("m22.247 4.83l.558.276c.975.485 1.532 1.593 1.323 2.77l-.766 3.95c-.068.407-.338.681-.743.692h-.023s.07-1.178.139-1.87c.056-.563-.042-.734-.557-1.247c-.28-.277-.488-.693-.488-1.108V7.184c0-.346-.279-.623-.557-.692c-.836-.208-2.578-.555-5.086-.555s-4.25.347-5.086.555c-.348.069-.557.346-.557.692v1.109c0 .415-.14.83-.487 1.108l-.21.208c-.278.207-.417.623-.417.97c.07.761.139 1.87.139 1.87q-.033 0-.064-.003a.82.82 0 0 1-.772-.69l-.766-3.948c-.14-1.109.418-2.217 1.393-2.702l.557-.277c.349-.208.697-.485 1.045-.762l1.254-1.316c.766-.693 1.881-.9 2.856-.415a3.8 3.8 0 0 0 2.16 0c1.045-.347 2.23-.07 3.065.692l1.045 1.04c.279.346.627.553 1.045.761");
}

.uritxubxy {
  d: path("m25.19 20.499l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.va-dzqbbo {
  d: path("M20.44 16.027L5.033 23.2a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.706l15.407-7.183c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.vbfhreb6b {
  stop-color: var(--svg-color--8e5b8e, #8E5B8E);
}

.vdbpvroyq {
  d: path("M25.5 29.929h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.vhav-abny {
  stop-color: var(--svg-color--734a39, #734A39);
}

.vlixws18p {
  fill: var(--svg-color--000, #000);
  d: path("M18.158 12.616a.66.66 0 0 1 .663-.663a.66.66 0 0 1 .59.969h-1.175a.6.6 0 0 1-.079-.306");
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vxp4qyb9c {
  stop-color: var(--svg-color--3869b0, #3869B0);
}

.w_6w3opsv {
  stop-color: var(--svg-color--592f28, #592F28);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w8l-sqdgg {
  cx: 9.822px;
  cy: 13.242px;
  r: 2.168px;
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whmlezbbn {
  stop-color: var(--svg-color--8d6d68, #8D6D68);
}

.wltqj-b_b {
  stop-color: var(--svg-color--3fc3ff, #3FC3FF);
  stop-opacity: 0;
}

.wy3pbiouc {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.09 11.105c.848 0 1.564.584 1.759 1.374a.356.356 0 0 1-.348.443h-2.897a.3.3 0 0 1-.295-.353a1.815 1.815 0 0 1 1.78-1.465");
}

.wymjbgbqv {
  d: path("M24.75 19.732a.885.885 0 0 1 .35-1.203l2.61-1.429a.899.899 0 1 1 .856 1.581l-2.622 1.404a.885.885 0 0 1-1.193-.354");
}

.xfh2-qzxa {
  cx: 22.178px;
  cy: 13.242px;
  r: 1.292px;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xp9lv-a7q {
  stop-color: var(--svg-color--28bbff, #28BBFF);
  stop-opacity: 0;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3qu8-b1b {
  stop-color: var(--svg-color--a27b71, #A27B71);
}

.y5l4vob7e {
  stop-color: var(--svg-color--7e4a52, #7E4A52);
}

.y6shzzc0m {
  stop-color: var(--svg-color--047fc0, #047FC0);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yemvrmxbd {
  stop-color: var(--svg-color--7e4a52, #7E4A52);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yuv68hbvz {
  d: path("M7.246 19.702a.885.885 0 0 0-.351-1.204l-2.553-1.397a.899.899 0 1 0-.855 1.58l2.565 1.374a.885.885 0 0 0 1.194-.353");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z5qepe3br {
  fill: var(--svg-color--000, #000);
  d: path("M13.813 12.616a.66.66 0 0 0-.664-.663a.66.66 0 0 0-.59.969h1.175a.66.66 0 0 0 .079-.306");
}

.ziu9nybix {
  stop-color: var(--svg-color--5d4842, #5D4842);
  stop-opacity: 0;
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zmv_7hb2s {
  cx: 22.178px;
  cy: 13.242px;
  r: 2.168px;
}

.zv5d5z9ye {
  stroke: var(--svg-color--473d3d, #473D3D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m11.671 9.95l2.344-.563");
}

.zv7v3hber {
  d: path("m15.492 12.317l-.69 2.207a.7.7 0 0 0 .676.908h1.021a.702.702 0 0 0 .676-.908l-.69-2.207c-.148-.49-.838-.49-.993 0");
}

</style>
