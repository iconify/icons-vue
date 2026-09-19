<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i0eMgUI)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#iOjek6c)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#i8IhE7b)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#ia0ozfc)" transform="rotate(-27.486 7.735 6.851)" class="psru50bbi"/><path fill="url(#imdZvZc)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iev7Igb)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iJSh9Rd)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#icTlMSc)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#iTiyvsz)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#iSlBHOb)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#iL1SVfL)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#i6eHjnx)" class="g4offrb0h"/><path fill="url(#ihrMxQQ)" class="g4offrb0h"/><path fill="url(#igYlFZb)" class="nm-q8ebbk"/><path fill="url(#iA39zBd)" class="nm-q8ebbk"/><path fill="url(#icomEIe)" class="z0ggixb3q"/><path fill="url(#iKUvYXc)" class="z0ggixb3q"/><path fill="url(#i2lb2vb)" class="tzfcre5-h"/><path fill="url(#irtIY9Z)" class="tzfcre5-h"/><circle fill="url(#ihUH0Ge)" class="gknucfb8h"/><circle fill="url(#igSWh8b)" class="gknucfb8h"/><path fill="url(#iuoWORd)" class="y0nqeezxq"/><path fill="url(#i1gUcVd)" class="y0nqeezxq"/><path fill="url(#i2g6S5b)" class="l2at7otgu"/><path fill="url(#itN5bFe)" class="l2at7otgu"/><path fill="url(#ilQeege)" class="ufmuzl7ni"/><path fill="url(#iBbOMSb)" class="ufmuzl7ni"/><path fill="url(#ivMLBmb)" class="rh3jx3c9i"/><path fill="url(#inblcIb)" class="rh3jx3c9i"/><circle fill="url(#ibvUIjc)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><circle fill="url(#iLZeLcY)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#ibI8Blv)"><path fill="url(#ilmwlid)" class="em3ofwhyw"/><path fill="url(#iSuCE7b)" class="em3ofwhyw"/><path fill="url(#iTnerGc)" class="em3ofwhyw"/></g><g filter="url(#iRk2Cge)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#if22bAS)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#iI5Gupd)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#ixRkPXc)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><g filter="url(#iLINmoc)"><path fill="url(#i9g91Cd)" class="uv_bhvydh"/></g><g filter="url(#i8TvHvc)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#izyWHoe)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#i5xlPve)"><path fill="url(#iHOi0qc)" class="nvirpp9bq"/></g><g filter="url(#iwwj1we)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#i7gzkne)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><g filter="url(#iJkJwjc)"><path fill="url(#i8Xs0Cc)" class="mfhw-cvum"/></g><g filter="url(#iFOh8Jb)"><path clip-rule="evenodd" class="tg3fv6avj"/></g><path fill="url(#ijV5Sdd)" class="gvfevcqpg"/><path fill="url(#iUPN9ac)" class="q7vdqbb4c"/><g filter="url(#i6PV7Me)"><path class="xlad93b9t"/></g><g filter="url(#i6VWZjb)"><path class="r-oyu5b8v"/></g><g filter="url(#iFjUQFe)"><path fill="url(#iTB0QPe)" class="dnbq4ebyf"/></g><path fill="url(#iWtPo5c)" class="dnbq4ebyf"/><g filter="url(#ileJ8Rc)"><path class="qgzrq6s7b"/></g><g filter="url(#it1Xlwb)"><path class="lfvh6excd"/><path fill="url(#i7Nh1he)" class="xqlmcqpgn"/><path fill="url(#iYjOpXb)" class="xqlmcqpgn"/><path fill="url(#iZkngde)" class="xqlmcqpgn"/><path fill="url(#i3AP9Md)" class="xqlmcqpgn"/></g><path class="o9ter0bul"/><g filter="url(#ihSnnNd)"><path class="osi4yuzdy"/></g><g filter="url(#iUvy8eb)"><path class="oc_k7t9qm"/></g><path class="htetulbac"/><path fill="url(#i5gdcgd)" class="s82syyb3h"/><path class="gi51crbds"/><g filter="url(#iCWTH5h)"><path class="wt9m7jb6x"/><path fill="url(#iBDcR5j)" class="jdxil9bxw"/></g><g filter="url(#iYtdjyd)"><path fill="url(#imQtvqe)" class="o362xebvo"/></g><path class="zego_e0ep"/><path fill="url(#ijXvI1d)" class="rzpk10v1x"/><path class="ob4g158sh"/><g filter="url(#i5eeNjb)"><path fill="url(#icutPKM)" class="vo95dqqbo"/></g><g filter="url(#iQ0uAke)"><ellipse transform="rotate(-27.914 14.91 12.913)" class="ul9vuv_zk"/><ellipse fill="url(#i6pkpmd)" transform="rotate(-27.914 14.91 12.913)" class="k0jsg8cwq"/></g><g filter="url(#ibolFrd)"><path fill="url(#iFo4TdG)" class="ghtn8n6_t"/></g><g filter="url(#iqTxOyd)"><path class="e6fmk4imt"/><path fill="url(#iZVSAdc)" class="hy-mjmv4h"/><path fill="url(#itMe7Ge)" class="hy-mjmv4h"/></g><path class="u58t-8ibg"/><g filter="url(#ienW4re)"><path class="o5-hg7bth"/></g><path class="erjr7x4iz"/><g filter="url(#iTg5kjk)"><path class="g3ay3zbfb"/></g><defs><radialGradient id="i0eMgUI" cx="0" cy="0" r="1" gradientTransform="matrix(-.00154 4.75464 -1.08171 -.00035 9.816 10.929)" gradientUnits="userSpaceOnUse"><stop class="qc5umhbsx"/><stop offset="1" class="ps5p_xb2b"/></radialGradient><radialGradient id="i8IhE7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.04 7.769)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tuvsor_7r"/><stop offset="1" class="s_t4keb-b"/></radialGradient><radialGradient id="ia0ozfc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.362 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="dlijzhe6z"/><stop offset="1" class="rcswokzqh"/></radialGradient><radialGradient id="imdZvZc" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -1.122 2.973)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="xz64_6yvi"/><stop offset="1" class="y8dp0hbvk"/></radialGradient><radialGradient id="iJSh9Rd" cx="0" cy="0" r="1" gradientTransform="rotate(127.793 1.116 1.093)scale(1.67845 1.54056)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="suv_43jhc"/><stop offset="1" class="lqtoipbqj"/></radialGradient><radialGradient id="icTlMSc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="ghoayzsjh"/><stop offset="1" class="iglonxb_v"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="i6eHjnx" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="ihrMxQQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.083 6.282)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="igYlFZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="iA39zBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 8.777 6.312)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="icomEIe" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.03 3.12)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="iKUvYXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.179 6.32)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="i2lb2vb" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.687 3.116)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="irtIY9Z" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.496 6.362)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="ihUH0Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-.39453 .51953 -.51953 -.39453 10.781 6.84)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="cvatkobbr"/><stop offset=".91" class="ydv5mwxxd"/></radialGradient><radialGradient id="igSWh8b" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 3.627 6.223)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="op745bcjt"/><stop offset="1" class="n5tde31zi"/></radialGradient><radialGradient id="iuoWORd" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.218 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="i1gUcVd" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.237 10.362)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="i2g6S5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.543 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="itN5bFe" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.834 10.393)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="ilQeege" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.124 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="iBbOMSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.093 6.198)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="ivMLBmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 22.826 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="inblcIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 22.792 6.229)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="ibvUIjc" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="bmte3bbwj"/><stop offset=".91" class="wvhi0ab5z"/></radialGradient><radialGradient id="iLZeLcY" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 .276 .232)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="kk6l23w0e"/><stop offset="1" class="sh5_80x3i"/></radialGradient><radialGradient id="ilmwlid" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="cg05ombch"/><stop offset="1" class="i25jr6cdh"/></radialGradient><radialGradient id="iSuCE7b" cx="0" cy="0" r="1" gradientTransform="rotate(77.286 -1.694 16.51)scale(3.83375 5.43507)" gradientUnits="userSpaceOnUse"><stop offset=".102" class="v8rezjblq"/><stop offset="1" class="u1b9dcc6t"/></radialGradient><radialGradient id="iTnerGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="yyr7j8rnv"/><stop offset="1" class="ymbigdcyd"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="ijV5Sdd" cx="0" cy="0" r="1" gradientTransform="rotate(176.801 6.748 6.633)scale(.70031 .84071)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="l9p2s2boj"/><stop offset="1" class="va_t2og-p"/></radialGradient><radialGradient id="iUPN9ac" cx="0" cy="0" r="1" gradientTransform="rotate(102.937 4.264 13.615)scale(1.11341 1.65485)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="xb1y9tlks"/><stop offset=".234" class="g6uqlkbei"/></radialGradient><radialGradient id="iTB0QPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65883 0 0 -2.57517 17.212 13.492)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="wa7kkxbvr"/><stop offset="1" class="u3cxmmb4z"/></radialGradient><radialGradient id="iWtPo5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00002 3.52409 -4.33659 -.00002 16.032 12.106)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="h9hto5bbh"/><stop offset="1" class="gebiq326t"/></radialGradient><radialGradient id="i7Nh1he" cx="0" cy="0" r="1" gradientTransform="matrix(-.2082 -.93415 .2879 -.06416 16.39 13.773)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i3AP9Md" cx="0" cy="0" r="1" gradientTransform="matrix(-.3562 0 0 -.09958 16.281 13.87)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i5gdcgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4167 -.66104 0 17.03 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="eijss2b4a"/><stop offset=".787" class="mj--szbch"/></radialGradient><radialGradient id="iBDcR5j" cx="0" cy="0" r="1" gradientTransform="matrix(-.10567 -.13617 .18747 -.14547 16.925 12.996)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijXvI1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4167 -.66104 0 15.034 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="eijss2b4a"/><stop offset=".787" class="mj--szbch"/></radialGradient><radialGradient id="i6pkpmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00352 -.2251 .27059 -.00424 14.903 13.057)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFo4TdG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12349 1.33892 -.5517 -.46294 14.767 10.028)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iZVSAdc" cx="0" cy="0" r="1" gradientTransform="matrix(.95313 -1.40625 3.25016 2.20289 16.48 11.117)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="rctvpnbah"/><stop offset=".915" class="v9s5mbb1x"/></radialGradient><radialGradient id="itMe7Ge" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 0 0 .82813 16.893 10.825)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="v9s5mbb1x"/><stop offset="1" class="rctvpnbah"/></radialGradient><filter id="iTiyvsz" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="iSlBHOb" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="iL1SVfL" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".125"/></filter><filter id="ibI8Blv" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="iRk2Cge" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="if22bAS" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="iI5Gupd" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="ixRkPXc" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="iLINmoc" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.313726 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23312" result="effect2_innerShadow_3987_23312"/></filter><filter id="i8TvHvc" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="izyWHoe" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="i5xlPve" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.313726 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23312" result="effect2_innerShadow_3987_23312"/></filter><filter id="iwwj1we" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="i7gzkne" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="iJkJwjc" width=".636" height=".646" x="16.916" y="12.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".1"/></filter><filter id="iFOh8Jb" width="6.864" height="7.364" x="12.601" y="8.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0666667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="i6PV7Me" width="1.282" height="1.282" x="17.598" y="12.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".075"/></filter><filter id="i6VWZjb" width="1.282" height="1.282" x="13.259" y="12.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".075"/></filter><filter id="iFjUQFe" width="4.807" height="4.999" x="13.704" y="10.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.360784 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="ileJ8Rc" width="1.358" height="1.726" x="15.279" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".125"/></filter><filter id="it1Xlwb" width="1.058" height="1.426" x="15.503" y="12.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".05"/></filter><filter id="ihSnnNd" width="1.48" height=".587" x="16.354" y="12.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="iUvy8eb" width="1.48" height=".587" x="14.23" y="12.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23312"/></filter><filter id="iCWTH5h" width=".367" height=".326" x="16.69" y="12.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".025"/></filter><filter id="iYtdjyd" width=".323" height=".333" x="17.119" y="12.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".025"/></filter><filter id="i5eeNjb" width=".367" height=".392" x="15.089" y="12.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".025"/></filter><filter id="iQ0uAke" width=".425" height=".33" x="14.698" y="12.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".025"/></filter><filter id="ibolFrd" width="2.179" height="2.284" x="13.013" y="9.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".125"/></filter><filter id="iqTxOyd" width="4.346" height="3.237" x="14.393" y="8.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".075"/></filter><filter id="ienW4re" width="1.024" height=".375" x="16.78" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".025"/></filter><filter id="iTg5kjk" width="1.024" height=".375" x="14.26" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23312" stdDeviation=".025"/></filter><linearGradient id="iOjek6c" x1="7.163" x2="8.284" y1="7.95" y2="8.096" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ord38lb5d"/><stop offset="1" class="lagcd8brb"/></linearGradient><linearGradient id="iev7Igb" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="pdrq0-vxx"/><stop offset="1" class="tldk1ryzb"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="i9g91Cd" x1="11.874" x2="9.452" y1="25.825" y2="25.825" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ykol_yz-a"/><stop offset="1" class="d19y5jbcp"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iHOi0qc" x1="23.141" x2="20.749" y1="25.206" y2="25.206" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ykol_yz-a"/><stop offset="1" class="d19y5jbcp"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="i8Xs0Cc" x1="17.343" x2="17.192" y1="13.014" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYjOpXb" x1="15.603" x2="16.032" y1="13.806" y2="13.806" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iZkngde" x1="16.032" x2="16.032" y1="14.171" y2="13.892" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="imQtvqe" x1="17.384" x2="17.241" y1="12.981" y2="13.069" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icutPKM" x1="15.374" x2="15.231" y1="12.981" y2="13.069" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-lifting-weights-medium-dark" /></template>
<style>
.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.bmte3bbwj {
  stop-color: var(--svg-color--75574d, #75574D);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.cg05ombch {
  stop-color: var(--svg-color--886fd9, #886FD9);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cvatkobbr {
  stop-color: var(--svg-color--826255, #826255);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d19y5jbcp {
  stop-color: var(--svg-color--855958, #855958);
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d9_0_ybyb {
  stop-color: var(--svg-color--8e7570, #8E7570);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dlijzhe6z {
  stop-color: var(--svg-color--623c31, #623C31);
}

.dnbq4ebyf {
  d: path("M13.707 12.487h.006l-.005-.121l-.004-.14c.009-.434.262-.601.37-.657l.023-.01l.024-.009c.243-.112.44-.308.543-.564l.038-.13a.12.12 0 0 1 .21-.022c.329.48.877.776 1.458.776h1.472c.082 0 .495.069.519.637l-.053 1.243c-.057 1.28-1.057 2.14-2.278 2.14c-1.22 0-2.221-.86-2.277-2.14z");
}

.e4y-1lbum {
  r: 0.398px;
}

.e6fmk4imt {
  fill: var(--svg-color--331d25, #331D25);
  d: path("M15.684 9.098c-.78 0-1.083.677-1.141.884c.762 1.788 1.763 1.536 3.229 1.536c.781 0 .751.346.817.518c-.215-2.004-1.375-2.938-2.905-2.938");
}

.eijss2b4a {
  stop-color: var(--svg-color--8b6259, #8B6259);
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.erjr7x4iz {
  stroke: var(--svg-color--342727, #342727);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.184 12.161a1.3 1.3 0 0 0-.824-.167");
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.ft5dv1b6b {
  fill: none;
}

.fzjqedceo {
  d: path("M24.992 29.53v.376H20.36v-1.914h2.352c.383.377 1.215.73 1.836.941c.398.169.445.442.445.597");
}

.g3ay3zbfb {
  stroke: var(--svg-color--3f3235, #3F3235);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.184 12.161a1.3 1.3 0 0 0-.824-.167");
}

.g4offrb0h {
  d: path("M7.5 5.71a.399.399 0 1 1 .797-.034v.46a.38.38 0 0 1-.758.032z");
}

.g5fg-5cgy {
  d: path("M28.852 4.402a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.g6uqlkbei {
  stop-color: var(--svg-color--7e555b, #7E555B);
}

.gebiq326t {
  stop-color: var(--svg-color--753c73, #753C73);
}

.ghoayzsjh {
  stop-color: var(--svg-color--754c3c, #754C3C);
}

.ghtn8n6_t {
  d: path("M13.835 10.207c.284-.252.694-.255.923-.214l.184.59a.36.36 0 0 0-.31.107c-.208.576-1.02.98-1.352 1.067c-.07-.682.065-1.113.555-1.55");
}

.gi51crbds {
  fill: var(--svg-color--000, #000);
  d: path("M16.797 13.146c0-.13.103-.233.233-.233a.232.232 0 0 1 .207.34h-.413a.2.2 0 0 1-.027-.107");
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.gvfevcqpg {
  d: path("M13.89 13.593a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.h9hto5bbh {
  stop-color: var(--svg-color--7b475f, #7B475F);
  stop-opacity: 0;
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hg2aihb7u {
  stop-color: var(--svg-color--6a3f41, #6A3F41);
}

.htetulbac {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.125 12.615a.64.64 0 0 1 .62.483a.126.126 0 0 1-.123.156h-1.02a.105.105 0 0 1-.104-.124a.64.64 0 0 1 .627-.515");
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.hy-mjmv4h {
  d: path("M15.684 9.098c-.78 0-1.083.677-1.141.884c.762 1.788 1.763 1.536 3.229 1.536c.781 0 .751.346.817.518c-.215-2.004-1.375-2.938-2.905-2.938");
}

.i25jr6cdh {
  stop-color: var(--svg-color--694cb1, #694CB1);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.iglonxb_v {
  stop-color: var(--svg-color--754c3c, #754C3C);
  stop-opacity: 0;
}

.ijj045bhz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.398 6.406H29.43");
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jdxil9bxw {
  d: path("M17 12.825c.029.04-.032.086-.1.138c-.07.051-.12.088-.15.049s.004-.112.072-.164c.07-.051.149-.061.178-.023");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jpyi06dtg {
  stop-color: var(--svg-color--8e7570, #8E7570);
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.k0jsg8cwq {
  cx: 14.91px;
  cy: 12.913px;
  rx: 0.178px;
  ry: 0.09px;
}

.kk6l23w0e {
  stop-color: var(--svg-color--886f6a, #886F6A);
}

.kv3enpo0a {
  d: path("M23.516 21.066a1.988 1.988 0 0 0-3.977 0v1.686c0 .193.157.35.35.35h3.277a.35.35 0 0 0 .35-.35z");
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l2at7otgu {
  d: path("M23.823 5.627a.422.422 0 1 0-.843-.033v.584a.4.4 0 0 0 .798.031z");
}

.l9p2s2boj {
  stop-color: var(--svg-color--6c494e, #6C494E);
}

.lagcd8brb {
  stop-color: var(--svg-color--562f3a, #562F3A);
  stop-opacity: 0;
}

.lfvh6excd {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.858 13.033l-.243.777c-.05.16.069.32.238.32h.359a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.173-.295-.173-.35 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqtoipbqj {
  stop-color: var(--svg-color--68423f, #68423F);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.mfhw-cvum {
  d: path("M17.352 13.13a.4.4 0 0 0-.11-.221l-.126.136l.057.11z");
}

.mj--szbch {
  stop-color: var(--svg-color--875b54, #875B54);
}

.n5tde31zi {
  stop-color: var(--svg-color--947870, #947870);
  stop-opacity: 0;
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.nvirpp9bq {
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.o362xebvo {
  d: path("M17.392 13.092a.4.4 0 0 0-.105-.21l-.118.13l.053.103z");
}

.o5-hg7bth {
  stroke: var(--svg-color--3f3235, #3F3235);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.88 12.161c.117-.066.386-.211.824-.167");
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.o9ter0bul {
  fill: var(--svg-color--88004e, #88004E);
  d: path("M16.022 14.572c-.238 0-.462-.057-.65-.157c-.064-.033-.133.04-.093.1a.883.883 0 0 0 1.485 0c.04-.062-.028-.133-.093-.1c-.188.1-.409.157-.65.157");
}

.ob4g158sh {
  fill: var(--svg-color--000, #000);
  d: path("M15.267 13.146a.23.23 0 0 0-.233-.233a.232.232 0 0 0-.208.34h.413a.23.23 0 0 0 .028-.107");
}

.ob61f_0qn {
  stop-color: var(--svg-color--886b66, #886B66);
}

.oc_k7t9qm {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.51 12.97c-.12-.214-.305-.382-.702-.382a.76.76 0 0 0-.49.168c-.123.1-.107.227-.012.274l.255.145c.297-.096.627-.11.95-.205");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op745bcjt {
  stop-color: var(--svg-color--947870, #947870);
}

.ord38lb5d {
  stop-color: var(--svg-color--49252f, #49252F);
}

.osi4yuzdy {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.554 12.97c.122-.214.306-.382.703-.382c.174 0 .341.048.49.168c.123.1.107.227.011.274l-.254.145c-.298-.096-.627-.11-.95-.205");
}

.pdrq0-vxx {
  stop-color: var(--svg-color--46212d, #46212D);
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.ps5p_xb2b {
  stop-color: var(--svg-color--7c4f4e, #7C4F4E);
}

.psru50bbi {
  d: path("M7.735 6.851h2.46v7.269h-2.46z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q1wg51bmi {
  d: path("M16 25.93c-2.363 0-4.203-.72-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q7vdqbb4c {
  d: path("M18.238 13.593a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qc5umhbsx {
  stop-color: var(--svg-color--9e7970, #9E7970);
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qgzrq6s7b {
  fill: var(--svg-color--7c4453, #7C4453);
  d: path("m15.853 13.096l-.312.777c-.05.16.069.32.238.32h.359a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.172-.225-.172-.28 0");
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.r-oyu5b8v {
  fill: var(--svg-color--603c3f, #603C3F);
  d: path("M13.9 13.349a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rcswokzqh {
  stop-color: var(--svg-color--623c31, #623C31);
  stop-opacity: 0;
}

.rctvpnbah {
  stop-color: var(--svg-color--423138, #423138);
  stop-opacity: 0;
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.rzpk10v1x {
  d: path("M15.034 12.739a.407.407 0 0 0-.393.515h.787a.41.41 0 0 0-.394-.515");
}

.s_t4keb-b {
  stop-color: var(--svg-color--795a5b, #795A5B);
  stop-opacity: 0;
}

.s0g9yis6b {
  stop-color: var(--svg-color--62383a, #62383A);
}

.s82syyb3h {
  d: path("M17.03 12.739a.407.407 0 0 1 .393.515h-.787a.41.41 0 0 1 .394-.515");
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.sh5_80x3i {
  stop-color: var(--svg-color--886f6a, #886F6A);
  stop-opacity: 0;
}

.suv_43jhc {
  stop-color: var(--svg-color--532a2a, #532A2A);
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tg3fv6avj {
  fill: var(--svg-color--2c212a, #2C212A);
  fill-rule: evenodd;
  d: path("M19.316 13.183a1.5 1.5 0 0 0 .025-1.249h.003a1.5 1.5 0 0 0-.129-.234a1.5 1.5 0 0 1-.241-.81v-.004c0-.833-.675-1.508-1.508-1.508a.25.25 0 0 1-.208-.106a1.51 1.51 0 0 0-2.451 0a.26.26 0 0 1-.208.106h-.04a1.51 1.51 0 0 0-1.468 1.508v.004c0 .287-.083.57-.24.81l-.002.001a1.51 1.51 0 0 0-.1 1.483a.24.24 0 0 1 0 .209a1.47 1.47 0 0 0 1.323 2.114h3.921a1.47 1.47 0 0 0 1.323-2.114a.24.24 0 0 1 0-.209m-5.603-.886l.542.742c.057 1.28.556 0 1.777 0s1.754 1.425 1.81.144l.52-.937c-.025-.57-.438-.61-.52-.61H16.37c-.58 0-1.13-.284-1.457-.764a.12.12 0 0 0-.211.024l-.038.088c-.256.716-.968.867-.951 1.313");
}

.tldk1ryzb {
  stop-color: var(--svg-color--613e45, #613E45);
  stop-opacity: 0;
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tox4m5q8h {
  stop-color: var(--svg-color--816457, #816457);
}

.tphhgybtp {
  d: path("M26.922 2.894a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.tuvsor_7r {
  stop-color: var(--svg-color--5a2e30, #5A2E30);
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tzfcre5-h {
  d: path("M8.876 5.588a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.823.015z");
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u1b9dcc6t {
  stop-color: var(--svg-color--624ba3, #624BA3);
  stop-opacity: 0;
}

.u3cxmmb4z {
  stop-color: var(--svg-color--7a4d53, #7A4D53);
}

.u58t-8ibg {
  stroke: var(--svg-color--342727, #342727);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.88 12.161c.117-.066.386-.211.824-.167");
}

.u6_y93pge {
  d: path("M8.516 21.066a1.988 1.988 0 1 1 3.976 0v1.686a.35.35 0 0 1-.35.35H8.866a.35.35 0 0 1-.35-.35z");
}

.ufmuzl7ni {
  d: path("M22.392 5.626a.401.401 0 1 0-.803-.014v.575a.391.391 0 0 0 .783.013z");
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.ujo-xtz9c {
  stop-color: var(--svg-color--82665a, #82665A);
}

.ul9vuv_zk {
  cx: 14.91px;
  cy: 12.913px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.178px;
  ry: 0.09px;
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.uv_bhvydh {
  d: path("m9.404 28.878l-.513-5.894h3.218l-.533 5.966z");
}

.uywq_y1iv {
  width: 27.875px;
  height: 1.025px;
  x: 2.063px;
  y: 5.975px;
  rx: 0.2px;
}

.v8rezjblq {
  stop-color: var(--svg-color--402b83, #402B83);
}

.v9s5mbb1x {
  stop-color: var(--svg-color--423138, #423138);
}

.va_t2og-p {
  stop-color: var(--svg-color--3b282c, #3B282C);
}

.vo95dqqbo {
  d: path("M15.406 13.098c0-.131-.107-.219-.136-.246l-.131.128l.08.164z");
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.wa7kkxbvr {
  stop-color: var(--svg-color--9b6d61, #9B6D61);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wt9m7jb6x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17 12.825c.029.04-.032.086-.1.138c-.07.051-.12.088-.15.049s.004-.112.072-.164c.07-.051.149-.061.178-.023");
}

.wvhi0ab5z {
  stop-color: var(--svg-color--6d3e45, #6D3E45);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x9t-2zb_r {
  d: path("M3.11 4.402a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.xb1y9tlks {
  stop-color: var(--svg-color--91746d, #91746D);
}

.xlad93b9t {
  fill: var(--svg-color--7c5450, #7C5450);
  d: path("M18.239 13.349a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.xqlmcqpgn {
  d: path("m15.858 13.033l-.243.777c-.05.16.069.32.238.32h.359a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.173-.295-.173-.35 0");
}

.xr8cplx4f {
  stop-color: var(--svg-color--886b66, #886B66);
  stop-opacity: 0;
}

.xz64_6yvi {
  stop-color: var(--svg-color--845e5b, #845E5B);
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.y8dp0hbvk {
  stop-color: var(--svg-color--815651, #815651);
}

.ydv5mwxxd {
  stop-color: var(--svg-color--683842, #683842);
}

.ykol_yz-a {
  stop-color: var(--svg-color--9d6f6b, #9D6F6B);
}

.ymbigdcyd {
  stop-color: var(--svg-color--8263c1, #8263C1);
  stop-opacity: 0;
}

.yyr7j8rnv {
  stop-color: var(--svg-color--5a3e9b, #5A3E9B);
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zego_e0ep {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.94 12.615a.64.64 0 0 0-.62.483c-.02.08.04.156.123.156h1.02c.064 0 .116-.06.103-.124a.64.64 0 0 0-.627-.515");
}

</style>
