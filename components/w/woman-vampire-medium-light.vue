<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iaRabKb)" class="m3g7jifsb"/><g filter="url(#iVTEwid)"><path fill="url(#iWOga8t)" class="ijj2d--ei"/><path fill="url(#ifyYYJe)" class="ijj2d--ei"/></g><path fill="url(#iXy5jvb)" class="z1-l5rb6a"/><g filter="url(#iYacWle)"><path fill="url(#iUmWwmb)" class="q_b_2yanx"/></g><path fill="url(#iZpsCSc)" class="bb3dqobne"/><path fill="url(#iNpZHgb)" class="bb3dqobne"/><path fill="url(#iT68Ewe)" class="bb3dqobne"/><path fill="url(#iPNAhPd)" class="bb3dqobne"/><path fill="url(#ieWFgbd)" class="bb3dqobne"/><path fill="url(#iTzcjGc)" class="bb3dqobne"/><path fill="url(#iHSq4gd)" class="bb3dqobne"/><path fill="url(#iQIjVUE)" class="bb3dqobne"/><path fill="url(#iisJMDd)" class="o8kmu9buj"/><path fill="url(#isgcfne)" class="o8kmu9buj"/><path fill="url(#iqCJkcc)" class="qyhpqhglr"/><path fill="url(#i8g7aCc)" class="qyhpqhglr"/><path fill="url(#iqViIse)" class="qyhpqhglr"/><path fill="url(#iuEO38c)" class="efy7qjbsu"/><path fill="url(#iuWe9FH)" class="efy7qjbsu"/><path fill="url(#iHk3RIe)" class="efy7qjbsu"/><g filter="url(#i4V5kGe)"><path class="nve42acoy"/></g><g filter="url(#iO5Nvhb)"><path class="hce_18q6o"/></g><g filter="url(#isjNVnb)"><path fill="url(#i4eo8tb)" class="anpbisbwb"/></g><g filter="url(#it3zPyi)"><path fill="url(#iInzbub)" class="m90vejb5b"/><path fill="url(#iSkJxod)" class="m90vejb5b"/><path fill="url(#iQ11Jee)" class="m90vejb5b"/></g><path clip-rule="evenodd" class="h8s89g9gk"/><path fill="url(#idw5OAB)" clip-rule="evenodd" class="mc20n3b_e"/><path clip-rule="evenodd" class="m9-oww5el"/><path fill="url(#i7izNJb)" clip-rule="evenodd" class="koudtg7gm"/><g filter="url(#iVNCA5m)"><path class="k3hfnzbtk"/><path fill="url(#iDGCCUd)" class="qo4g78b0t"/><path fill="url(#irFtIKb)" class="qo4g78b0t"/><path fill="url(#iwv6Cvd)" class="qo4g78b0t"/><path fill="url(#i2lA3ue)" class="qo4g78b0t"/><path fill="url(#iUjOghe)" class="qo4g78b0t"/><path fill="url(#iE4E3db)" class="qo4g78b0t"/><path fill="url(#i6yStzc)" class="qo4g78b0t"/><path fill="url(#iv45Kdc)" class="qo4g78b0t"/><path fill="url(#iAylete)" class="qo4g78b0t"/><path fill="url(#iXZeXqc)" class="qo4g78b0t"/></g><g filter="url(#idxhOOd)"><path stroke="url(#imcR1tb)" class="xdq44cozz"/></g><path class="uh1r5-eki"/><path fill="url(#iCHvGUY)" class="lu5rrvbhf"/><path fill="url(#iYEG0Yd)" class="no5fe9bfr"/><path fill="url(#iBf6y4j)" clip-rule="evenodd" class="rbtgpsbuo"/><path fill="url(#iRfqIud)" clip-rule="evenodd" class="t6y7fjbra"/><g filter="url(#iPeCoPe)"><path stroke="url(#i8cW9nd)" class="t_qv4acvq"/></g><g filter="url(#iyb2Jtd)"><path stroke="url(#iAIOAke)" class="u0smf3bxj"/></g><g filter="url(#iD9tYMd)"><path class="it5dptb7w"/></g><g filter="url(#idYSdRd)"><path class="qrlwuxb9d"/><path fill="url(#iX9Difb)" class="eeorzu2ah"/><path fill="url(#i918Zbc)" class="eeorzu2ah"/><path fill="url(#imZEY5b)" class="eeorzu2ah"/><path fill="url(#isopBse)" class="eeorzu2ah"/></g><g filter="url(#ijgmX7k)"><path class="c7u255soc"/></g><g filter="url(#iFjnIvd)"><path class="zfvh726_h"/></g><path class="mwkd6jbbm"/><path fill="url(#iDGSrob)" class="sjtimycjx"/><path class="bx3e5sinj"/><g filter="url(#i2gz8Sb)"><path class="vwjyd4bap"/><path fill="url(#i1Z6L7q)" class="boe_7q6ks"/></g><g filter="url(#i5n78Uc)"><path fill="url(#ilm68Qc)" class="puuq9pi8k"/></g><path class="l1ztl-b4c"/><path fill="url(#ijUcYXl)" class="pk2bzfncs"/><path class="cvofkc-hn"/><g filter="url(#iFVjJQd)"><path fill="url(#iiNlMKc)" class="uesx31k4u"/></g><g filter="url(#i76YdCY)"><ellipse transform="rotate(-27.914 13.508 9.933)" class="hjnhewbog"/><ellipse fill="url(#i4iqotb)" transform="rotate(-27.914 13.508 9.933)" class="o718qtjwr"/></g><path fill="url(#iTAhmeh)" class="urpxrxoti"/><path fill="url(#iyfhQjd)" class="urpxrxoti"/><path fill="url(#ic9rhne)" class="urpxrxoti"/><path fill="url(#iTPUcZc)" class="urpxrxoti"/><path fill="url(#itLUkCc)" class="urpxrxoti"/><path fill="url(#iMrbkCd)" class="urpxrxoti"/><path fill="url(#iNzBmAb)" class="zex36v3bk"/><path fill="url(#itA4pRc)" class="zex36v3bk"/><path fill="url(#ixSqlHd)" class="nxg98fh1m"/><path fill="url(#iCDNBld)" class="nxg98fh1m"/><path fill="url(#ifDK50c)" class="nxg98fh1m"/><g filter="url(#i5FGPgb)"><path fill="url(#irlyrle)" class="gmt4i2zwn"/><path fill="url(#iBK1ige)" class="gmt4i2zwn"/></g><g filter="url(#iGd3IiP)"><path class="wxnd6bcfd"/></g><g filter="url(#iljOoOc)"><path class="rtt68oe7x"/></g><g filter="url(#iQidqib)"><path fill="url(#iGFGpEs)" class="svmd8bcdt"/><path fill="url(#ijHxtHe)" class="svmd8bcdt"/></g><g filter="url(#iPiiK5b)"><path class="phfreac8m"/></g><defs><radialGradient id="iaRabKb" cx="0" cy="0" r="1" gradientTransform="matrix(3.93792 -7.29125 14.315 7.73138 20.553 16.724)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="1" class="gdsiwyiyr"/></radialGradient><radialGradient id="iWOga8t" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92122 7.06151 -2.22108 -.91882 27.573 12.2)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jpxim8b1x"/><stop offset="1" class="n52c8qgao"/></radialGradient><radialGradient id="ifyYYJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 4.15626 -.42744 -.1607 27.323 12.668)" gradientUnits="userSpaceOnUse"><stop class="fg6i_oqme"/><stop offset="1" class="ih2ibv29b"/></radialGradient><radialGradient id="iXy5jvb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58397 -6.61442 12.98618 -8.99977 12.493 17)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="0" class="pxp9rxlhv"/><stop offset="1" class="e06hnni3m"/></radialGradient><radialGradient id="iNpZHgb" cx="0" cy="0" r="1" gradientTransform="rotate(-118.874 16.512 8.465)scale(12.4902 33.343)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="f6lcb9bkn"/><stop offset="1" class="jtbt9y0gz"/></radialGradient><radialGradient id="iT68Ewe" cx="0" cy="0" r="1" gradientTransform="rotate(-65.133 29.203 1.591)scale(12.2618 28.8332)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="r21k1wzrc"/><stop offset="1" class="b2cn2_uce"/></radialGradient><radialGradient id="iPNAhPd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71875 0 0 -14.5625 23.292 23.293)" gradientUnits="userSpaceOnUse"><stop class="odfe47amh"/><stop offset="1" class="carxtabzu"/></radialGradient><radialGradient id="ieWFgbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6875 -.22656 0 19.206 16.7)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="z8m-hreok"/><stop offset="1" class="ehu1o5vid"/></radialGradient><radialGradient id="iTzcjGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 3.5 -5.72433 -1.89104 12.667 16.324)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="a75cnrb-k"/><stop offset="1" class="ri_i1lblj"/></radialGradient><radialGradient id="iisJMDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6045 2.48458 0 23.855 29.918)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="vbb18ixfb"/><stop offset="1" class="p5bq_2b9f"/></radialGradient><radialGradient id="isgcfne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5781 .52466 0 23.11 29.918)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l0d7sccpf"/><stop offset="1" class="r3f5xvbmj"/></radialGradient><radialGradient id="iqCJkcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.2188 2.95614 0 7.292 29.918)" gradientUnits="userSpaceOnUse"><stop class="oj4dw6cda"/><stop offset="1" class="jsbpdr4yj"/></radialGradient><radialGradient id="i8g7aCc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21875 0 0 -14.5625 8.542 29.45)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ihp7x-bon"/><stop offset="1" class="n-3c_rb8h"/></radialGradient><radialGradient id="iInzbub" cx="0" cy="0" r="1" gradientTransform="rotate(58.107 -6.989 21.605)scale(4.25865 6.21727)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="xksrntfob"/><stop offset="1" class="pu1_ubb-e"/></radialGradient><radialGradient id="iSkJxod" cx="0" cy="0" r="1" gradientTransform="matrix(.37499 3.45575 -7.05506 .76555 14.729 14.186)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="jzwike70j"/><stop offset="1" class="gbck5ebgo"/></radialGradient><radialGradient id="iQ11Jee" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92056 -2.6343 0 15.948 16.268)" gradientUnits="userSpaceOnUse"><stop class="uxwciubxp"/><stop offset="1" class="kqp3z9b3n"/></radialGradient><radialGradient id="iDGCCUd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21875 0 0 -10.5283 20.636 9.327)" gradientUnits="userSpaceOnUse"><stop class="u4h9r6bxj"/><stop offset="1" class="fym6gdx5j"/></radialGradient><radialGradient id="irFtIKb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.11337 0 0 -3.34571 18.44 10.746)" gradientUnits="userSpaceOnUse"><stop class="gq-sz9ukb"/><stop offset="1" class="hmoievk4a"/></radialGradient><radialGradient id="iwv6Cvd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52032 7.04982 -11.97186 -4.27995 16.552 9.516)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="zpmsocvsf"/><stop offset=".907" class="atjaarbcl"/></radialGradient><radialGradient id="i2lA3ue" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13673 1.44566 0 18.313 9.516)" gradientUnits="userSpaceOnUse"><stop class="z73kgo_nb"/><stop offset="1" class="h-nemwmov"/></radialGradient><radialGradient id="iUjOghe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.10055 1.27175 0 13.802 9.448)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="shek1db6a"/><stop offset="1" class="aeshud4vv"/></radialGradient><radialGradient id="iE4E3db" cx="0" cy="0" r="1" gradientTransform="matrix(6 4.15626 -4.71296 6.80366 14.76 10.152)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="it9n31bck"/><stop offset="1" class="k1vqrwiqk"/></radialGradient><radialGradient id="i6yStzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6421 6.24238 0 15.939 16.566)" gradientUnits="userSpaceOnUse"><stop class="i-bxpzbdt"/><stop offset="1" class="kg-bhlb8k"/></radialGradient><radialGradient id="iv45Kdc" cx="0" cy="0" r="1" gradientTransform="matrix(4.47861 -2.29745 1.24356 2.42418 18.11 7.403)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="ugx07vw4f"/><stop offset="1" class="jrlre3lqh"/></radialGradient><radialGradient id="iAylete" cx="0" cy="0" r="1" gradientTransform="matrix(7.71594 -5.60324 8.28843 11.41358 13.354 11.59)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="fxkn4ibqw"/><stop offset="1" class="aj-atf4eu"/></radialGradient><radialGradient id="iXZeXqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .45313 -3.23249 0 15.939 7.152)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="eled5bggb"/><stop offset="1" class="f4b-xytlt"/></radialGradient><radialGradient id="iX9Difb" cx="0" cy="0" r="1" gradientTransform="matrix(-.59375 -2.4375 1.13177 -.27569 16.719 12.299)" gradientUnits="userSpaceOnUse"><stop class="p-sgdu4ak"/><stop offset="1" class="vt1whxbul"/></radialGradient><radialGradient id="iDGSrob" cx="0" cy="0" r="1" gradientTransform="rotate(-117.266 12.22 -.396)scale(.57126 .90459)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="i1Z6L7q" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.919 10.114)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="ijUcYXl" cx="0" cy="0" r="1" gradientTransform="matrix(-.26172 -.50781 .80412 -.41444 13.804 10.285)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="i4iqotb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.791 -1.518)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="iTAhmeh" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.8889 -10.4212 0 15.902 5.765)" gradientUnits="userSpaceOnUse"><stop class="b8534puqy"/><stop offset="1" class="rx5ge3bmv"/></radialGradient><radialGradient id="ic9rhne" cx="0" cy="0" r="1" gradientTransform="rotate(-131.126 13.319 2.704)scale(14.0638 15.8054)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="zvajyol-k"/><stop offset=".977" class="ccjw6lk0v"/></radialGradient><radialGradient id="itLUkCc" cx="0" cy="0" r="1" gradientTransform="matrix(9.31272 -7.64112 15.98385 19.48053 12.108 12.502)" gradientUnits="userSpaceOnUse"><stop offset=".915" class="e9awv8b_o"/><stop offset="1" class="xi4bd6b8m"/></radialGradient><radialGradient id="itA4pRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.28219 .4722 -2.42671 -1.45017 10.478 8.341)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="ul1ykr67h"/><stop offset="1" class="qud2n6bek"/></radialGradient><radialGradient id="iCDNBld" cx="0" cy="0" r="1" gradientTransform="matrix(-.95888 1.1121 -.24664 -.21266 23.152 7.76)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="ejovpob_c"/><stop offset="1" class="xjqy35bej"/></radialGradient><radialGradient id="irlyrle" cx="0" cy="0" r="1" gradientTransform="rotate(-132.082 7.734 2.707)scale(2.41247 2.17677)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="bibse5b_g"/><stop offset="1" class="rztrcvo8m"/></radialGradient><radialGradient id="iBK1ige" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18123 .63382 -1.16713 -2.17513 11.01 9.75)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="btshlgevp"/><stop offset="1" class="x1znl4bef"/></radialGradient><radialGradient id="iGFGpEs" cx="0" cy="0" r="1" gradientTransform="matrix(1.59772 -1.40625 .53061 .60286 20.98 10.293)" gradientUnits="userSpaceOnUse"><stop class="d_gvhtbnl"/><stop offset="1" class="h2_sf6loz"/></radialGradient><radialGradient id="ijHxtHe" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.0625 .1101 1.101 20.86 10.7)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="pvf5rxbtj"/><stop offset="1" class="ux38s3d-q"/></radialGradient><linearGradient id="iUmWwmb" x1="5.54" x2="8.862" y1="11.955" y2="18.323" gradientUnits="userSpaceOnUse"><stop class="imlbmc2sy"/><stop offset="1" class="h7wwwp44w"/></linearGradient><linearGradient id="iZpsCSc" x1="15.935" x2="15.935" y1="15.543" y2="29.918" gradientUnits="userSpaceOnUse"><stop class="plsegxa8t"/><stop offset="1" class="dbg8b7bda"/></linearGradient><linearGradient id="iHSq4gd" x1="8.661" x2="8.938" y1="29.918" y2="29.918" gradientUnits="userSpaceOnUse"><stop class="rq6u1obxj"/><stop offset="1" class="yomd27bxe"/></linearGradient><linearGradient id="iQIjVUE" x1="23.206" x2="22.776" y1="29.918" y2="29.918" gradientUnits="userSpaceOnUse"><stop offset=".136" class="i0lopbdha"/><stop offset="1" class="w11i7m31i"/></linearGradient><linearGradient id="iqViIse" x1="8.759" x2="7.511" y1="28.73" y2="28.73" gradientUnits="userSpaceOnUse"><stop class="k6ta6mb-r"/><stop offset="1" class="drixk4bdm"/></linearGradient><linearGradient id="iuEO38c" x1="15.939" x2="15.939" y1="20.887" y2="29.918" gradientUnits="userSpaceOnUse"><stop class="zajm34fcf"/><stop offset="1" class="puh_1hb6q"/></linearGradient><linearGradient id="iuWe9FH" x1="15.939" x2="15.939" y1="29.918" y2="27.262" gradientUnits="userSpaceOnUse"><stop class="ou_12nqfl"/><stop offset="1" class="ypzxpcc2j"/></linearGradient><linearGradient id="iHk3RIe" x1="19.542" x2="17.698" y1="28.73" y2="28.73" gradientUnits="userSpaceOnUse"><stop offset=".119" class="zxxizob4i"/><stop offset="1" class="u7u0nyv_w"/></linearGradient><linearGradient id="i4eo8tb" x1="15.935" x2="15.935" y1="17.75" y2="25.779" gradientUnits="userSpaceOnUse"><stop class="gmn9ea1yo"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="idw5OAB" x1="16.35" x2="16.479" y1="19.066" y2="19.676" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="i7izNJb" x1="15.546" x2="15.417" y1="19.066" y2="19.676" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="imcR1tb" x1="15.948" x2="15.948" y1="14.66" y2="14.238" gradientUnits="userSpaceOnUse"><stop class="gyw_1gbuz"/><stop offset="1" class="v4717ih9a"/></linearGradient><linearGradient id="iCHvGUY" x1="17.479" x2="16.94" y1="13.848" y2="14.09" gradientUnits="userSpaceOnUse"><stop class="h4n1x2_nx"/><stop offset="1" class="kbidwf4gr"/></linearGradient><linearGradient id="iYEG0Yd" x1="14.969" x2="14.516" y1="14.09" y2="14.017" gradientUnits="userSpaceOnUse"><stop class="ftqk6c0fk"/><stop offset="1" class="seh9j6z3x"/></linearGradient><linearGradient id="iBf6y4j" x1="12.448" x2="14.433" y1="8.67" y2="7.971" gradientUnits="userSpaceOnUse"><stop class="bq_0jebkw"/><stop offset="1" class="kjjvcb6je"/><stop offset="1" class="wasds5b8d"/></linearGradient><linearGradient id="iRfqIud" x1="19.43" x2="17.445" y1="8.67" y2="7.971" gradientUnits="userSpaceOnUse"><stop class="bq_0jebkw"/><stop offset="1" class="kjjvcb6je"/><stop offset="1" class="wasds5b8d"/></linearGradient><linearGradient id="i8cW9nd" x1="14.057" x2="12.174" y1="7.998" y2="8.369" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></linearGradient><linearGradient id="iAIOAke" x1="19.347" x2="17.323" y1="8.152" y2="7.918" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></linearGradient><linearGradient id="i918Zbc" x1="14.893" x2="15.967" y1="11.71" y2="11.774" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="imZEY5b" x1="15.966" x2="15.966" y1="12.223" y2="13.011" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="isopBse" x1="15.966" x2="15.966" y1="10.143" y2="10.531" gradientUnits="userSpaceOnUse"><stop class="isd7-25wt"/><stop offset="1" class="v_z7nenim"/></linearGradient><linearGradient id="ilm68Qc" x1="18.886" x2="18.63" y1="10.09" y2="10.255" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iiNlMKc" x1="14.524" x2="14.21" y1="10.083" y2="10.276" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iyfhQjd" x1="8.929" x2="9.979" y1="14.202" y2="14.202" gradientUnits="userSpaceOnUse"><stop class="ccjw6lk0v"/><stop offset="1" class="zvajyol-k"/></linearGradient><linearGradient id="iTPUcZc" x1="17.761" x2="17.761" y1="16.827" y2="15.374" gradientUnits="userSpaceOnUse"><stop offset=".131" class="c4ey9j8wv"/><stop offset="1" class="uabjeu-1v"/></linearGradient><linearGradient id="iMrbkCd" x1="23.104" x2="22.261" y1="14.858" y2="14.858" gradientUnits="userSpaceOnUse"><stop class="g7xtertqj"/><stop offset="1" class="eovkc4nhj"/></linearGradient><linearGradient id="iNzBmAb" x1="9.052" x2="11.366" y1="10.454" y2="9.532" gradientUnits="userSpaceOnUse"><stop class="ofh3qnb3e"/><stop offset="1" class="r6iczhnfi"/></linearGradient><linearGradient id="ixSqlHd" x1="21.483" x2="22.383" y1="8.378" y2="11.008" gradientUnits="userSpaceOnUse"><stop class="bj0dakbmi"/><stop offset=".581" class="vyye_881d"/></linearGradient><linearGradient id="ifDK50c" x1="21.784" x2="22.055" y1="8.123" y2="8.528" gradientUnits="userSpaceOnUse"><stop class="hz1t2nbtp"/><stop offset="1" class="zkst1sbgc"/></linearGradient><filter id="iVTEwid" width="4.802" height="8.2" x="22.301" y="11.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1227"/></filter><filter id="iYacWle" width="4.902" height="8.4" x="5.146" y="10.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.321569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1227"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1227" result="effect2_innerShadow_4002_1227"/></filter><filter id="i4V5kGe" width="6.968" height="4.815" x="12.464" y="15.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".25"/></filter><filter id="iO5Nvhb" width="6.431" height="9.028" x="12.527" y="17.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".25"/></filter><filter id="isjNVnb" width="5.531" height="8.006" x="13.22" y="17.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.705882 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1227"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.670588 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1227" result="effect2_innerShadow_4002_1227"/></filter><filter id="it3zPyi" width="6.43" height="4.559" x="12.733" y="15.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.835294 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1227"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.733333 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1227" result="effect2_innerShadow_4002_1227"/></filter><filter id="iVNCA5m" width="11.013" height="14.6" x="10.808" y="2.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.623529 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1227"/></filter><filter id="idxhOOd" width="3.566" height="1.546" x="14.165" y="13.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".05"/></filter><filter id="iPeCoPe" width="2.177" height=".868" x="12.199" y="7.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".075"/></filter><filter id="iyb2Jtd" width="2.177" height=".868" x="17.467" y="7.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".075"/></filter><filter id="iD9tYMd" width="3.762" height="4.684" x="13.846" y="9.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".5"/></filter><filter id="idYSdRd" width="2.079" height="2.884" x="14.927" y="10.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".05"/></filter><filter id="ijgmX7k" width="3.001" height="1.285" x="16.908" y="9.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1227"/></filter><filter id="iFjnIvd" width="3.001" height="1.285" x="12.023" y="9.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1227"/></filter><filter id="i2gz8Sb" width=".787" height=".697" x="17.413" y="9.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".05"/></filter><filter id="i5n78Uc" width=".892" height=".914" x="18.253" y="9.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".1"/></filter><filter id="iFVjJQd" width=".987" height="1.041" x="13.807" y="9.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".1"/></filter><filter id="i76YdCY" width=".914" height=".705" x="13.052" y="9.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".05"/></filter><filter id="i5FGPgb" width="2.017" height="3.595" x="9.092" y="8.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".1"/></filter><filter id="iGd3IiP" width="6.998" height="4.138" x="15.057" y="3.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".5"/></filter><filter id="iljOoOc" width="3.359" height="2.93" x="10.717" y="4.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".25"/></filter><filter id="iQidqib" width="2.098" height="3.68" x="20.73" y="8.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".125"/></filter><filter id="iPiiK5b" width="5.928" height="1.395" x="13.023" y="2.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1227" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-vampire-medium-light" /></template>
<style>
.a75cnrb-k {
  stop-color: var(--svg-color--47374c, #47374C);
}

.aeshud4vv {
  stop-color: var(--svg-color--c5897c, #C5897C);
  stop-opacity: 0;
}

.aj-atf4eu {
  stop-color: var(--svg-color--83604b, #83604B);
}

.anpbisbwb {
  d: path("m14.084 19.496l-.859 5.24a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.027l.706.514a1.1 1.1 0 0 0 1.294 0l.706-.514a.51.51 0 0 1 .553-.027l.202.118a.402.402 0 0 0 .602-.409l-.857-5.234c-.81-.505-1.856-1.28-1.856-1.28s-1.106.796-1.848 1.274");
}

.atjaarbcl {
  stop-color: var(--svg-color--bf7a89, #BF7A89);
}

.b2cn2_uce {
  stop-color: var(--svg-color--60506b, #60506B);
}

.b8534puqy {
  stop-color: var(--svg-color--222, #222);
}

.bb3dqobne {
  d: path("M15.935 15.543c-6.04 0-10.937 5.1-10.937 11.14v3.235h21.875v-3.235c0-6.04-4.897-11.14-10.938-11.14");
}

.bibse5b_g {
  stop-color: var(--svg-color--b37861, #B37861);
}

.bj0dakbmi {
  stop-color: var(--svg-color--cb9b7d, #CB9B7D);
}

.boe_7q6ks {
  d: path("M18.084 9.74c.063.085-.07.19-.221.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.36c.15-.112.325-.135.389-.05");
}

.bq_0jebkw {
  stop-color: var(--svg-color--281c22, #281C22);
}

.btshlgevp {
  stop-color: var(--svg-color--c08775, #C08775);
  stop-opacity: 0;
}

.bx3e5sinj {
  fill: var(--svg-color--000, #000);
  d: path("M17.638 10.445a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.c4ey9j8wv {
  stop-color: var(--svg-color--54205d, #54205D);
}

.c7u255soc {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.108 10.057c.266-.467.67-.836 1.538-.836c.38 0 .746.106 1.072.369c.27.217.233.495.025.6l-.556.317c-.652-.211-1.373-.24-2.079-.45");
}

.carxtabzu {
  stop-color: var(--svg-color--604f70, #604F70);
  stop-opacity: 0;
}

.ccjw6lk0v {
  stop-color: var(--svg-color--4f4f4f, #4F4F4F);
}

.cvofkc-hn {
  fill: var(--svg-color--000, #000);
  d: path("M14.29 10.445a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.d_gvhtbnl {
  stop-color: var(--svg-color--dba489, #DBA489);
}

.dbg8b7bda {
  stop-color: var(--svg-color--553d71, #553D71);
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.e06hnni3m {
  stop-color: var(--svg-color--e73665, #E73665);
}

.e9awv8b_o {
  stop-color: var(--svg-color--565656, #565656);
  stop-opacity: 0;
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eeorzu2ah {
  d: path("m15.584 10.426l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.efy7qjbsu {
  d: path("M12.733 29.918V16.026a10.7 10.7 0 0 1 3.183-.483a10.7 10.7 0 0 1 3.229.497v13.878z");
}

.ehu1o5vid {
  stop-color: var(--svg-color--47304f, #47304F);
  stop-opacity: 0;
}

.ejovpob_c {
  stop-color: var(--svg-color--e2b89e, #E2B89E);
}

.eled5bggb {
  stop-color: var(--svg-color--c48a75, #C48A75);
}

.eovkc4nhj {
  stop-color: var(--svg-color--303030, #303030);
  stop-opacity: 0;
}

.f1lm8sbjk {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
}

.f4b-xytlt {
  stop-color: var(--svg-color--c48a75, #C48A75);
  stop-opacity: 0;
}

.f6lcb9bkn {
  stop-color: var(--svg-color--56475f, #56475F);
  stop-opacity: 0;
}

.fg6i_oqme {
  stop-color: var(--svg-color--574b64, #574B64);
}

.ft5dv1b6b {
  fill: none;
}

.ftqk6c0fk {
  stop-color: var(--svg-color--d1c8d8, #D1C8D8);
}

.fxkn4ibqw {
  stop-color: var(--svg-color--9b6d4a, #9B6D4A);
  stop-opacity: 0;
}

.fym6gdx5j {
  stop-color: var(--svg-color--f6c29d, #F6C29D);
  stop-opacity: 0;
}

.g7xtertqj {
  stop-color: var(--svg-color--303030, #303030);
}

.gbck5ebgo {
  stop-color: var(--svg-color--a99494, #A99494);
  stop-opacity: 0;
}

.gdsiwyiyr {
  stop-color: var(--svg-color--e82e5c, #E82E5C);
}

.gmn9ea1yo {
  stop-color: var(--svg-color--f4dff7, #F4DFF7);
}

.gmt4i2zwn {
  d: path("m10.778 9.293l.13 2.374c-1.075-.865-1.497-2.123-1.614-2.948c-.028-.2.19-.318.356-.203z");
}

.gq-sz9ukb {
  stop-color: var(--svg-color--fac39b, #FAC39B);
}

.gyw_1gbuz {
  stop-color: var(--svg-color--ce9588, #CE9588);
}

.h-nemwmov {
  stop-color: var(--svg-color--e7a98e, #E7A98E);
  stop-opacity: 0;
}

.h1sgipbfm {
  stop-color: var(--svg-color--d82535, #D82535);
}

.h2_sf6loz {
  stop-color: var(--svg-color--d29c84, #D29C84);
}

.h4n1x2_nx {
  stop-color: var(--svg-color--e6deec, #E6DEEC);
}

.h7wwwp44w {
  stop-color: var(--svg-color--302736, #302736);
}

.h8s89g9gk {
  fill: var(--svg-color--decee7, #DECEE7);
  fill-rule: evenodd;
  d: path("M16.458 19.068a.125.125 0 0 1 .141.106l.649 4.672a.125.125 0 1 1-.248.034l-.648-4.671a.125.125 0 0 1 .106-.142");
}

.hce_18q6o {
  fill: var(--svg-color--c91a3b, #C91A3B);
  d: path("m14.177 17.871l-1.144 6.986a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.027l.705.514a1.1 1.1 0 0 0 1.295 0l.706-.514a.51.51 0 0 1 .553-.027l.202.118a.402.402 0 0 0 .602-.41l-1.145-6.985z");
}

.hjnhewbog {
  cx: 13.508px;
  cy: 9.933px;
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.39px;
  ry: 0.197px;
}

.hl4dixbko {
  stop-color: var(--svg-color--ff6d74, #FF6D74);
}

.hmoievk4a {
  stop-color: var(--svg-color--fac39b, #FAC39B);
  stop-opacity: 0;
}

.hz1t2nbtp {
  stop-color: var(--svg-color--b28566, #B28566);
}

.i-bxpzbdt {
  stop-color: var(--svg-color--c7849f, #C7849F);
}

.i0lopbdha {
  stop-color: var(--svg-color--4a2f65, #4A2F65);
}

.ih2ibv29b {
  stop-color: var(--svg-color--574b64, #574B64);
  stop-opacity: 0;
}

.ihp7x-bon {
  stop-color: var(--svg-color--655578, #655578);
  stop-opacity: 0;
}

.ijj2d--ei {
  d: path("M25.979 11.06q.253.222.5.456c.431.412.616 1.02.48 1.601c-.462 1.965-1.584 4.65-3.62 6.144l-1.038-.695c2.587-1.72 3.696-4.97 3.678-7.505");
}

.imlbmc2sy {
  stop-color: var(--svg-color--554961, #554961);
}

.isd7-25wt {
  stop-color: var(--svg-color--e0a892, #E0A892);
}

.it5dptb7w {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.69 10.59l-.82 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.378-.283-.378-.395 0");
}

.it9n31bck {
  stop-color: var(--svg-color--d1a08d, #D1A08D);
  stop-opacity: 0;
}

.jpxim8b1x {
  stop-color: var(--svg-color--534263, #534263);
}

.jrlre3lqh {
  stop-color: var(--svg-color--e9b396, #E9B396);
  stop-opacity: 0;
}

.jsbpdr4yj {
  stop-color: var(--svg-color--483859, #483859);
}

.jtbt9y0gz {
  stop-color: var(--svg-color--56475f, #56475F);
}

.jzwike70j {
  stop-color: var(--svg-color--a99494, #A99494);
}

.k1vqrwiqk {
  stop-color: var(--svg-color--d1a08d, #D1A08D);
}

.k3hfnzbtk {
  fill: var(--svg-color--c78d7d, #C78D7D);
  d: path("M10.808 7.549a5 5 0 0 1 5.033-5.082l.262.001A5 5 0 0 1 21.07 7.58l-.092 4.098a5 5 0 0 1-4.999 4.888h-.103a5 5 0 0 1-4.999-4.917z");
}

.k6ta6mb-r {
  stop-color: var(--svg-color--423153, #423153);
}

.kbidwf4gr {
  stop-color: var(--svg-color--d3cadb, #D3CADB);
}

.kg-bhlb8k {
  stop-color: var(--svg-color--c7849f, #C7849F);
  stop-opacity: 0;
}

.kjjvcb6je {
  stop-color: var(--svg-color--301d1b, #301D1B);
}

.koudtg7gm {
  fill-rule: evenodd;
  d: path("M15.438 19.068a.125.125 0 0 0-.141.106l-.649 4.672a.125.125 0 1 0 .248.034l.648-4.671a.125.125 0 0 0-.106-.142");
}

.kqp3z9b3n {
  stop-color: var(--svg-color--9c8ea7, #9C8EA7);
  stop-opacity: 0;
}

.l0d7sccpf {
  stop-color: var(--svg-color--48335e, #48335E);
}

.l1ztl-b4c {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.57 9.28c-.653 0-1.205.45-1.355 1.059a.274.274 0 0 0 .268.341h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.129");
}

.lft-zacfy {
  stop-color: var(--svg-color--ff242f, #FF242F);
}

.lu5rrvbhf {
  d: path("m17.154 14.574l-.396-.894a3.2 3.2 0 0 0 .623-.264c.102-.057.248.044.218.157l-.257.986a.1.1 0 0 1-.188.015");
}

.m3g7jifsb {
  d: path("M26.478 11.516c-2.243-2.144-5.051-3.377-6.334-3.817l-4.062 12.313h5.89c2.916-1.118 4.43-4.529 4.986-6.895a1.68 1.68 0 0 0-.48-1.601");
}

.m9-oww5el {
  fill: var(--svg-color--decee8, #DECEE8);
  fill-rule: evenodd;
  d: path("M15.438 19.068a.125.125 0 0 0-.141.106l-.649 4.672a.125.125 0 1 0 .248.034l.648-4.671a.125.125 0 0 0-.106-.142");
}

.m90vejb5b {
  d: path("M12.733 19.648v-3.844h6.43v3.736c0 .413-.233.618-.777.355c-.739-.355-2.454-1.655-2.454-1.655s-1.93 1.42-2.402 1.636c-.471.214-.797.185-.797-.228");
}

.map3_rs3n {
  stop-color: var(--svg-color--4e4649, #4E4649);
}

.mc20n3b_e {
  fill-rule: evenodd;
  d: path("M16.458 19.068a.125.125 0 0 1 .141.106l.649 4.672a.125.125 0 1 1-.248.034l-.648-4.671a.125.125 0 0 1 .106-.142");
}

.mwkd6jbbm {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.356 9.28c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.n-3c_rb8h {
  stop-color: var(--svg-color--655777, #655777);
}

.n52c8qgao {
  stop-color: var(--svg-color--3d3743, #3D3743);
}

.no5fe9bfr {
  d: path("m14.735 14.574l.396-.894a3.2 3.2 0 0 1-.623-.264c-.103-.057-.249.044-.22.157l.258.986a.1.1 0 0 0 .189.015");
}

.nve42acoy {
  fill: var(--svg-color--bb172a, #BB172A);
  d: path("M12.964 19.8v-3.485h5.968v3.387c0 .375-.216.56-.721.323c-.686-.322-2.277-1.501-2.277-1.501s-1.793 1.288-2.23 1.483c-.438.194-.74.168-.74-.207");
}

.nxg98fh1m {
  d: path("M20.921 12.21c.472-.2 1.01-.665 1.574-1.769c.538-1.024.67-1.886.656-2.527c-.005-.237-.247-.36-.46-.258c-.583.279-1.178.626-1.66.938l-.07 3.084q-.006.27-.04.533");
}

.o718qtjwr {
  cx: 13.508px;
  cy: 9.933px;
  rx: 0.39px;
  ry: 0.197px;
}

.o8kmu9buj {
  d: path("M23.11 18.313v11.605h3.763v-3.235c0-3.294-1.457-6.31-3.762-8.37");
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.odfe47amh {
  stop-color: var(--svg-color--746784, #746784);
}

.ofh3qnb3e {
  stop-color: var(--svg-color--c18677, #C18677);
}

.oj4dw6cda {
  stop-color: var(--svg-color--543e6e, #543E6E);
}

.ou_12nqfl {
  stop-color: var(--svg-color--f73397, #F73397);
}

.ozza9wbzj {
  stop-color: var(--svg-color--ff136b, #FF136B);
}

.p-sgdu4ak {
  stop-color: var(--svg-color--f2bfa4, #F2BFA4);
}

.p5bq_2b9f {
  stop-color: var(--svg-color--605075, #605075);
}

.p71wtvbay {
  stop-color: var(--svg-color--f3e0ff, #F3E0FF);
}

.phfreac8m {
  fill: var(--svg-color--474747, #474747);
  d: path("M13.323 3.202c.906-.27 3.367-.508 5.328 0c-.96-.648-3.054-1.406-5.328 0");
}

.pk2bzfncs {
  d: path("M13.778 9.551a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.plsegxa8t {
  stop-color: var(--svg-color--503d5d, #503D5D);
}

.pu1_ubb-e {
  stop-color: var(--svg-color--eae1f3, #EAE1F3);
}

.puh_1hb6q {
  stop-color: var(--svg-color--ff3779, #FF3779);
}

.puuq9pi8k {
  d: path("M18.945 10.327a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.pvf5rxbtj {
  stop-color: var(--svg-color--dfaa8c, #DFAA8C);
}

.pxp9rxlhv {
  stop-color: var(--svg-color--e33e4b, #E33E4B);
}

.q_b_2yanx {
  d: path("M6.27 11.06q-.255.222-.5.456a1.68 1.68 0 0 0-.48 1.601c.461 1.965 1.584 4.65 3.62 6.144l1.038-.695c-2.588-1.72-3.696-4.97-3.678-7.505");
}

.qhxuaybfw {
  stop-color: var(--svg-color--dfcfe8, #DFCFE8);
  stop-opacity: 0;
}

.qo4g78b0t {
  d: path("M10.808 7.549a5 5 0 0 1 5.033-5.082l.262.001A5 5 0 0 1 21.07 7.58l-.092 4.098a5 5 0 0 1-4.999 4.888h-.103a5 5 0 0 1-4.999-4.917z");
}

.qrlwuxb9d {
  fill: var(--svg-color--dfa98a, #DFA98A);
  d: path("m15.584 10.426l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.qud2n6bek {
  stop-color: var(--svg-color--9d6448, #9D6448);
  stop-opacity: 0;
}

.qyhpqhglr {
  d: path("M8.76 18.313v11.605H4.997v-3.235c0-3.294 1.456-6.31 3.761-8.37");
}

.r21k1wzrc {
  stop-color: var(--svg-color--60506b, #60506B);
  stop-opacity: 0;
}

.r3f5xvbmj {
  stop-color: var(--svg-color--48335e, #48335E);
  stop-opacity: 0;
}

.r6iczhnfi {
  stop-color: var(--svg-color--ad7b61, #AD7B61);
}

.rbtgpsbuo {
  fill-rule: evenodd;
  d: path("M14.137 8.28c-.716-.134-1.345.18-1.569.342a.25.25 0 1 1-.294-.404c.292-.212 1.059-.597 1.955-.43a.25.25 0 1 1-.092.491");
}

.ri_i1lblj {
  stop-color: var(--svg-color--47374c, #47374C);
  stop-opacity: 0;
}

.rq6u1obxj {
  stop-color: var(--svg-color--453455, #453455);
}

.rtt68oe7x {
  fill: var(--svg-color--434343, #434343);
  d: path("M11.936 5.609c-.081-.495-.513-.545-.719-.508c.868-.576 1.54.177 1.54.914c0 .589.547.787.82.812h-.6a.98.98 0 0 1-.968-.798c-.025-.137-.05-.28-.073-.42");
}

.rx5ge3bmv {
  stop-color: var(--svg-color--1c1b1b, #1C1B1B);
}

.rztrcvo8m {
  stop-color: var(--svg-color--b47c70, #B47C70);
}

.seh9j6z3x {
  stop-color: var(--svg-color--c7becf, #C7BECF);
}

.shek1db6a {
  stop-color: var(--svg-color--c5897c, #C5897C);
}

.sjtimycjx {
  d: path("M18.15 9.552a.893.893 0 0 1 .86 1.128h-1.726a.897.897 0 0 1 .865-1.129");
}

.svmd8bcdt {
  d: path("M20.98 11.651c.04-.698.002-1.485.05-2.326l1.19-.81c.166-.114.384.005.355.204c-.116.82-.533 2.068-1.595 2.932");
}

.t_qv4acvq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.424 8.416c.224-.18.93-.5 1.727-.398");
}

.t6y7fjbra {
  fill-rule: evenodd;
  d: path("M17.74 8.28c.717-.134 1.346.18 1.57.342a.25.25 0 0 0 .294-.404c-.292-.212-1.059-.597-1.955-.43a.25.25 0 0 0 .091.491");
}

.u0smf3bxj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.419 8.416c-.224-.18-.93-.5-1.727-.398");
}

.u4h9r6bxj {
  stop-color: var(--svg-color--f6c29d, #F6C29D);
}

.u7u0nyv_w {
  stop-color: var(--svg-color--dd2864, #DD2864);
  stop-opacity: 0;
}

.uabjeu-1v {
  stop-color: var(--svg-color--54205d, #54205D);
  stop-opacity: 0;
}

.uesx31k4u {
  d: path("M14.594 10.34c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.ugx07vw4f {
  stop-color: var(--svg-color--e9b396, #E9B396);
}

.uh1r5-eki {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M14.513 13.418a2.94 2.94 0 0 0 2.87 0c.077-.042.169.023.143.106c-.26.85-.993 1.027-1.578 1.027s-1.318-.176-1.578-1.027c-.026-.083.066-.148.143-.106");
}

.ul1ykr67h {
  stop-color: var(--svg-color--9d6448, #9D6448);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.urpxrxoti {
  d: path("M15.902 2.082a6.973 6.973 0 0 0-6.973 6.973v6.349c0 .69.56 1.25 1.25 1.25h1.027c.676-.336 1.38-.597 2.125-.785a5.02 5.02 0 0 1-2.457-4.22l-.059-4.107c0-.504.194-1.215.545-1.702c.09-.126.268-.066.295.087q.045.257.094.504c.109.562.597.893 1.166.908l.042.002l.04.002a52 52 0 0 0 5.92 0L19 7.339c.567-.015 1.012-.345 1.12-.908q.048-.247.094-.504c.027-.153.252-.213.342-.087c.242.337.393.794.482 1.198q.022.269.017.542l-.092 4.098a5 5 0 0 1-2.452 4.191a10.7 10.7 0 0 1 2.114.785h1c.69 0 1.25-.56 1.25-1.25V9.055a6.973 6.973 0 0 0-6.973-6.973");
}

.uw1qucxdm {
  stop-color: var(--svg-color--d2bdd8, #D2BDD8);
}

.ux38s3d-q {
  stop-color: var(--svg-color--dfaa8c, #DFAA8C);
  stop-opacity: 0;
}

.uxwciubxp {
  stop-color: var(--svg-color--776484, #776484);
}

.v_z7nenim {
  stop-color: var(--svg-color--e0a892, #E0A892);
  stop-opacity: 0;
}

.v4717ih9a {
  stop-color: var(--svg-color--ce9588, #CE9588);
  stop-opacity: 0;
}

.vbb18ixfb {
  stop-color: var(--svg-color--6b5a80, #6B5A80);
}

.vo8nxhb-a {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
  stop-opacity: 0;
}

.vt1whxbul {
  stop-color: var(--svg-color--f2bfa4, #F2BFA4);
  stop-opacity: 0;
}

.vwjyd4bap {
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M18.084 9.74c.063.085-.07.19-.221.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.36c.15-.112.325-.135.389-.05");
}

.vyye_881d {
  stop-color: var(--svg-color--d6a18c, #D6A18C);
}

.w11i7m31i {
  stop-color: var(--svg-color--665579, #665579);
  stop-opacity: 0;
}

.wasds5b8d {
  stop-color: var(--svg-color--1f1216, #1F1216);
}

.wxnd6bcfd {
  fill: var(--svg-color--4a4a4a, #4A4A4A);
  d: path("M18.69 6.296h-1.952a.682.682 0 0 1 0-1.363h1.213c.22 0 .418-.118.562-.282c.359-.406.782-.554 1.36-.471c.566.08.994.677 1.182.904c-.168-.117-.699-.547-.985-.227c-.151.17-.388.583-.584.951a.91.91 0 0 1-.797.488");
}

.x1znl4bef {
  stop-color: var(--svg-color--c08775, #C08775);
}

.xdq44cozz {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.513 13.418a2.94 2.94 0 0 0 2.87 0c.077-.042.169.023.143.106c-.26.85-.993 1.027-1.578 1.027s-1.318-.176-1.578-1.027c-.026-.083.066-.148.143-.106Z");
}

.xi4bd6b8m {
  stop-color: var(--svg-color--565656, #565656);
}

.xjqy35bej {
  stop-color: var(--svg-color--e2b89e, #E2B89E);
  stop-opacity: 0;
}

.xksrntfob {
  stop-color: var(--svg-color--b3a9bc, #B3A9BC);
}

.xn_fidfol {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
  stop-opacity: 0;
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.ymkmd4kjm {
  stop-color: var(--svg-color--4e4649, #4E4649);
  stop-opacity: 0;
}

.yomd27bxe {
  stop-color: var(--svg-color--453455, #453455);
  stop-opacity: 0;
}

.ypzxpcc2j {
  stop-color: var(--svg-color--f73397, #F73397);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z1-l5rb6a {
  d: path("M5.77 11.516c2.243-2.144 5.052-3.377 6.334-3.817l4.063 12.313h-5.891c-2.916-1.118-4.43-4.529-4.986-6.895a1.68 1.68 0 0 1 .48-1.601");
}

.z73kgo_nb {
  stop-color: var(--svg-color--e7a98e, #E7A98E);
}

.z8m-hreok {
  stop-color: var(--svg-color--47304f, #47304F);
}

.zajm34fcf {
  stop-color: var(--svg-color--e32d3d, #E32D3D);
}

.zex36v3bk {
  d: path("M10.826 8.632a15 15 0 0 0-1.717-.976c-.213-.102-.456.021-.46.258c-.014.64.118 1.503.656 2.527c.58 1.136 1.133 1.595 1.614 1.787a5 5 0 0 1-.043-.58z");
}

.zfvh726_h {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.824 10.057c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.369c-.269.217-.233.495-.025.6l.556.317c.652-.211 1.373-.24 2.08-.45");
}

.zkst1sbgc {
  stop-color: var(--svg-color--b28566, #B28566);
  stop-opacity: 0;
}

.zpmsocvsf {
  stop-color: var(--svg-color--c2847f, #C2847F);
  stop-opacity: 0;
}

.zvajyol-k {
  stop-color: var(--svg-color--4f4f4f, #4F4F4F);
  stop-opacity: 0;
}

.zxxizob4i {
  stop-color: var(--svg-color--c52133, #C52133);
}

</style>
