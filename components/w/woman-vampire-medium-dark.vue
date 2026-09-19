<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iaRabKb)" class="m3g7jifsb"/><g filter="url(#iqPOVKd)"><path fill="url(#iWOga8t)" class="ijj2d--ei"/><path fill="url(#ifyYYJe)" class="ijj2d--ei"/></g><path fill="url(#iXy5jvb)" class="z1-l5rb6a"/><g filter="url(#iODtkLc)"><path fill="url(#iUmWwmb)" class="q_b_2yanx"/></g><path fill="url(#iZpsCSc)" class="bb3dqobne"/><path fill="url(#iNpZHgb)" class="bb3dqobne"/><path fill="url(#iT68Ewe)" class="bb3dqobne"/><path fill="url(#iPNAhPd)" class="bb3dqobne"/><path fill="url(#ieWFgbd)" class="bb3dqobne"/><path fill="url(#iTzcjGc)" class="bb3dqobne"/><path fill="url(#iHSq4gd)" class="bb3dqobne"/><path fill="url(#iQIjVUE)" class="bb3dqobne"/><path fill="url(#iisJMDd)" class="o8kmu9buj"/><path fill="url(#isgcfne)" class="o8kmu9buj"/><path fill="url(#iqCJkcc)" class="qyhpqhglr"/><path fill="url(#i8g7aCc)" class="qyhpqhglr"/><path fill="url(#iqViIse)" class="qyhpqhglr"/><path fill="url(#iuEO38c)" class="efy7qjbsu"/><path fill="url(#iuWe9FH)" class="efy7qjbsu"/><path fill="url(#iHk3RIe)" class="efy7qjbsu"/><g filter="url(#iPyy9Cb)"><path class="nve42acoy"/></g><g filter="url(#iLwdCXd)"><path class="hce_18q6o"/></g><g filter="url(#i9lsj9b)"><path fill="url(#i4eo8tb)" class="anpbisbwb"/></g><g filter="url(#i7Kc5CY)"><path fill="url(#iInzbub)" class="m90vejb5b"/><path fill="url(#iSkJxod)" class="m90vejb5b"/><path fill="url(#iuMKg1b)" class="m90vejb5b"/></g><path clip-rule="evenodd" class="h8s89g9gk"/><path fill="url(#idw5OAB)" clip-rule="evenodd" class="mc20n3b_e"/><path clip-rule="evenodd" class="m9-oww5el"/><path fill="url(#i7izNJb)" clip-rule="evenodd" class="koudtg7gm"/><g filter="url(#iW1hDLS)"><path class="t0nshbc4e"/><path fill="url(#ih9ypmb)" class="qo4g78b0t"/><path fill="url(#iPjqcdb)" class="qo4g78b0t"/><path fill="url(#iH4VUkL)" class="qo4g78b0t"/><path fill="url(#iQw0MRp)" class="qo4g78b0t"/><path fill="url(#ie84JOd)" class="qo4g78b0t"/><path fill="url(#isSuHnb)" class="qo4g78b0t"/><path fill="url(#i4Eaj4d)" class="qo4g78b0t"/><path fill="url(#iqtzcIc)" class="qo4g78b0t"/><path fill="url(#iaPKKvd)" class="qo4g78b0t"/><path fill="url(#iLWKzmc)" class="qo4g78b0t"/></g><g filter="url(#iCuNlHd)"><path stroke="url(#igIGMXc)" class="xdq44cozz"/></g><path class="svsf1gaao"/><path fill="url(#iCHvGUY)" class="lu5rrvbhf"/><path fill="url(#iYEG0Yd)" class="no5fe9bfr"/><path fill="url(#iBf6y4j)" clip-rule="evenodd" class="rbtgpsbuo"/><path fill="url(#iRfqIud)" clip-rule="evenodd" class="t6y7fjbra"/><g filter="url(#iE3A5jd)"><path stroke="url(#i8cW9nd)" class="t_qv4acvq"/></g><g filter="url(#igYgNev)"><path stroke="url(#iAIOAke)" class="u0smf3bxj"/></g><g filter="url(#ii65G0V)"><path class="pm06dk2ab"/></g><g filter="url(#iEw7h3c)"><path class="a22pcob0d"/><path fill="url(#iR27o2d)" class="eeorzu2ah"/><path fill="url(#iCr5pLb)" class="eeorzu2ah"/><path fill="url(#i4bzsSc)" class="eeorzu2ah"/><path fill="url(#iVSxlwb)" class="eeorzu2ah"/><path fill="url(#iWWi5Pb)" class="eeorzu2ah"/></g><g filter="url(#iweFLeu)"><path class="c7u255soc"/></g><g filter="url(#iGOqKtb)"><path class="zfvh726_h"/></g><path class="kna8kmbak"/><path fill="url(#iDGSrob)" class="sjtimycjx"/><path class="bx3e5sinj"/><g filter="url(#ihTuwgq)"><path class="vwjyd4bap"/><path fill="url(#i1Z6L7q)" class="boe_7q6ks"/></g><g filter="url(#iTpfJcc)"><path fill="url(#ilm68Qc)" class="puuq9pi8k"/></g><path class="l1ztl-b4c"/><path fill="url(#ijUcYXl)" class="pk2bzfncs"/><path class="cvofkc-hn"/><g filter="url(#iUhFCze)"><path fill="url(#iiNlMKc)" class="uesx31k4u"/></g><g filter="url(#i5cvKrd)"><ellipse transform="rotate(-27.914 13.508 9.933)" class="hjnhewbog"/><ellipse fill="url(#i4iqotb)" transform="rotate(-27.914 13.508 9.933)" class="o718qtjwr"/></g><path fill="url(#iTAhmeh)" class="urpxrxoti"/><path fill="url(#iyfhQjd)" class="urpxrxoti"/><path fill="url(#ic9rhne)" class="urpxrxoti"/><path fill="url(#iTPUcZc)" class="urpxrxoti"/><path fill="url(#itLUkCc)" class="urpxrxoti"/><path fill="url(#iMrbkCd)" class="urpxrxoti"/><path fill="url(#iflgDGI)" class="zex36v3bk"/><path fill="url(#iSbxL6d)" class="zex36v3bk"/><path fill="url(#iQRQihb)" class="nxg98fh1m"/><path fill="url(#ihF5oEM)" class="nxg98fh1m"/><path fill="url(#i4TB3ub)" class="nxg98fh1m"/><g filter="url(#i2wWkbx)"><path fill="url(#ipnyCzb)" class="gmt4i2zwn"/><path fill="url(#ig9Ttlb)" class="gmt4i2zwn"/></g><g filter="url(#id8hkzc)"><path class="wxnd6bcfd"/></g><g filter="url(#isyl05X)"><path class="rtt68oe7x"/></g><g filter="url(#iiH2ztb)"><path fill="url(#iy8IjKb)" class="svmd8bcdt"/><path fill="url(#iMKGsLb)" class="svmd8bcdt"/></g><g filter="url(#iluJIKd)"><path class="phfreac8m"/></g><defs><radialGradient id="iaRabKb" cx="0" cy="0" r="1" gradientTransform="matrix(3.93792 -7.29125 14.315 7.73138 20.553 16.724)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="1" class="gdsiwyiyr"/></radialGradient><radialGradient id="iWOga8t" cx="0" cy="0" r="1" gradientTransform="matrix(-2.92122 7.06151 -2.22108 -.91882 27.573 12.2)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="jpxim8b1x"/><stop offset="1" class="n52c8qgao"/></radialGradient><radialGradient id="ifyYYJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56248 4.15626 -.42744 -.1607 27.323 12.668)" gradientUnits="userSpaceOnUse"><stop class="fg6i_oqme"/><stop offset="1" class="ih2ibv29b"/></radialGradient><radialGradient id="iXy5jvb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.58397 -6.61442 12.98618 -8.99977 12.493 17)" gradientUnits="userSpaceOnUse"><stop class="h1sgipbfm"/><stop offset="0" class="pxp9rxlhv"/><stop offset="1" class="e06hnni3m"/></radialGradient><radialGradient id="iNpZHgb" cx="0" cy="0" r="1" gradientTransform="rotate(-118.874 16.512 8.465)scale(12.4902 33.343)" gradientUnits="userSpaceOnUse"><stop offset=".87" class="f6lcb9bkn"/><stop offset="1" class="jtbt9y0gz"/></radialGradient><radialGradient id="iT68Ewe" cx="0" cy="0" r="1" gradientTransform="rotate(-65.133 29.203 1.591)scale(12.2618 28.8332)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="r21k1wzrc"/><stop offset="1" class="b2cn2_uce"/></radialGradient><radialGradient id="iPNAhPd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.71875 0 0 -14.5625 23.292 23.293)" gradientUnits="userSpaceOnUse"><stop class="odfe47amh"/><stop offset="1" class="carxtabzu"/></radialGradient><radialGradient id="ieWFgbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.6875 -.22656 0 19.206 16.7)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="z8m-hreok"/><stop offset="1" class="ehu1o5vid"/></radialGradient><radialGradient id="iTzcjGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15623 3.5 -5.72433 -1.89104 12.667 16.324)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="a75cnrb-k"/><stop offset="1" class="ri_i1lblj"/></radialGradient><radialGradient id="iisJMDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.6045 2.48458 0 23.855 29.918)" gradientUnits="userSpaceOnUse"><stop offset=".467" class="vbb18ixfb"/><stop offset="1" class="p5bq_2b9f"/></radialGradient><radialGradient id="isgcfne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5781 .52466 0 23.11 29.918)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="l0d7sccpf"/><stop offset="1" class="r3f5xvbmj"/></radialGradient><radialGradient id="iqCJkcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.2188 2.95614 0 7.292 29.918)" gradientUnits="userSpaceOnUse"><stop class="oj4dw6cda"/><stop offset="1" class="jsbpdr4yj"/></radialGradient><radialGradient id="i8g7aCc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21875 0 0 -14.5625 8.542 29.45)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="ihp7x-bon"/><stop offset="1" class="n-3c_rb8h"/></radialGradient><radialGradient id="iInzbub" cx="0" cy="0" r="1" gradientTransform="rotate(58.107 -6.989 21.605)scale(4.25865 6.21727)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="xksrntfob"/><stop offset="1" class="pu1_ubb-e"/></radialGradient><radialGradient id="iSkJxod" cx="0" cy="0" r="1" gradientTransform="matrix(.37499 3.45575 -7.05506 .76555 14.729 14.186)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="jzwike70j"/><stop offset="1" class="gbck5ebgo"/></radialGradient><radialGradient id="iuMKg1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92056 -2.6343 0 15.948 16.268)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="uxwciubxp"/><stop offset="1" class="kqp3z9b3n"/></radialGradient><radialGradient id="ih9ypmb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.375 0 0 -8.22059 20.636 9.327)" gradientUnits="userSpaceOnUse"><stop class="u1xe1ac8d"/><stop offset="1" class="jbgxtdigq"/></radialGradient><radialGradient id="iPjqcdb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.11337 0 0 -3.34571 18.44 10.746)" gradientUnits="userSpaceOnUse"><stop class="r413jew7l"/><stop offset="1" class="p4zxjdbuk"/></radialGradient><radialGradient id="iH4VUkL" cx="0" cy="0" r="1" gradientTransform="rotate(110.396 4.778 10.714)scale(7.03871 7.54908)" gradientUnits="userSpaceOnUse"><stop offset=".641" class="trybmkb5r"/><stop offset=".907" class="jedlegbwh"/></radialGradient><radialGradient id="iQw0MRp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13673 1.44566 0 18.313 9.516)" gradientUnits="userSpaceOnUse"><stop class="n4t-p5ftj"/><stop offset="1" class="h-uaesb5h"/></radialGradient><radialGradient id="ie84JOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.10055 1.27175 0 13.802 9.448)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="poqupx1-h"/><stop offset="1" class="q_-i2n06o"/></radialGradient><radialGradient id="isSuHnb" cx="0" cy="0" r="1" gradientTransform="matrix(6 4.15626 -4.71296 6.80366 14.76 10.152)" gradientUnits="userSpaceOnUse"><stop offset=".874" class="xj-gubybt"/><stop offset="1" class="hh6luxbpp"/></radialGradient><radialGradient id="i4Eaj4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.06171 10.3217 0 15.939 16.566)" gradientUnits="userSpaceOnUse"><stop class="pf4dk2bmi"/><stop offset="1" class="argi_pbpj"/></radialGradient><radialGradient id="iqtzcIc" cx="0" cy="0" r="1" gradientTransform="matrix(4.47861 -2.29745 1.24356 2.42418 18.11 7.403)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="j0bkjo9lk"/><stop offset="1" class="mf0blib1m"/></radialGradient><radialGradient id="iaPKKvd" cx="0" cy="0" r="1" gradientTransform="matrix(7.375 -5.4375 8.04331 10.90932 13.354 11.59)" gradientUnits="userSpaceOnUse"><stop offset=".966" class="olfta5bse"/><stop offset="1" class="x180dfzcy"/></radialGradient><radialGradient id="iLWKzmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .45313 -3.23249 0 15.939 7.152)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="gcrpkvb6d"/><stop offset="1" class="a3x3-i3qc"/></radialGradient><radialGradient id="iCr5pLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2259 -.76773 0 16.433 12.346)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iVSxlwb" cx="0" cy="0" r="1" gradientTransform="rotate(157.024 7.073 7.591)scale(1.6534 2.5206)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iDGSrob" cx="0" cy="0" r="1" gradientTransform="rotate(-117.266 12.22 -.396)scale(.57126 .90459)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="i1Z6L7q" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.919 10.114)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="ijUcYXl" cx="0" cy="0" r="1" gradientTransform="matrix(-.26172 -.50781 .80412 -.41444 13.804 10.285)" gradientUnits="userSpaceOnUse"><stop offset=".426" class="ozza9wbzj"/><stop offset="1" class="lft-zacfy"/></radialGradient><radialGradient id="i4iqotb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.791 -1.518)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="xn_fidfol"/><stop offset="1" class="f1lm8sbjk"/></radialGradient><radialGradient id="iTAhmeh" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.8889 -10.4212 0 15.902 5.765)" gradientUnits="userSpaceOnUse"><stop class="b8534puqy"/><stop offset="1" class="rx5ge3bmv"/></radialGradient><radialGradient id="ic9rhne" cx="0" cy="0" r="1" gradientTransform="rotate(-131.126 13.319 2.704)scale(14.0638 15.8054)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="zvajyol-k"/><stop offset=".977" class="ccjw6lk0v"/></radialGradient><radialGradient id="itLUkCc" cx="0" cy="0" r="1" gradientTransform="matrix(9.31272 -7.64112 15.98385 19.48053 12.108 12.502)" gradientUnits="userSpaceOnUse"><stop offset=".915" class="e9awv8b_o"/><stop offset="1" class="xi4bd6b8m"/></radialGradient><radialGradient id="iSbxL6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.28219 .4722 -2.42671 -1.45017 10.478 8.341)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="zar60tfds"/><stop offset="1" class="zcyi13bvi"/></radialGradient><radialGradient id="ihF5oEM" cx="0" cy="0" r="1" gradientTransform="matrix(-.95888 1.1121 -.24664 -.21266 23.152 7.76)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="oye8lqbkv"/><stop offset="1" class="n5t1ewtyv"/></radialGradient><radialGradient id="ipnyCzb" cx="0" cy="0" r="1" gradientTransform="rotate(-132.082 7.734 2.707)scale(2.41247 2.17677)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="k3bbh1b2g"/><stop offset="1" class="xu87aibcb"/></radialGradient><radialGradient id="ig9Ttlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18123 .63382 -1.16713 -2.17513 11.01 9.75)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="azamzibei"/><stop offset="1" class="m8g2io15v"/></radialGradient><radialGradient id="iy8IjKb" cx="0" cy="0" r="1" gradientTransform="rotate(-41.353 24.127 -22.65)scale(2.12844 .90479)" gradientUnits="userSpaceOnUse"><stop class="nvpfuqb-a"/><stop offset="1" class="skcf9z1zl"/></radialGradient><radialGradient id="iMKGsLb" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.0625 .1101 1.101 20.86 10.7)" gradientUnits="userSpaceOnUse"><stop offset=".119" class="nnhn70ftf"/><stop offset="1" class="i8gko0bpu"/></radialGradient><linearGradient id="iUmWwmb" x1="5.54" x2="8.862" y1="11.955" y2="18.323" gradientUnits="userSpaceOnUse"><stop class="imlbmc2sy"/><stop offset="1" class="h7wwwp44w"/></linearGradient><linearGradient id="iZpsCSc" x1="15.935" x2="15.935" y1="15.543" y2="29.918" gradientUnits="userSpaceOnUse"><stop class="plsegxa8t"/><stop offset="1" class="dbg8b7bda"/></linearGradient><linearGradient id="iHSq4gd" x1="8.661" x2="8.938" y1="29.918" y2="29.918" gradientUnits="userSpaceOnUse"><stop class="rq6u1obxj"/><stop offset="1" class="yomd27bxe"/></linearGradient><linearGradient id="iQIjVUE" x1="23.206" x2="22.776" y1="29.918" y2="29.918" gradientUnits="userSpaceOnUse"><stop offset=".136" class="i0lopbdha"/><stop offset="1" class="w11i7m31i"/></linearGradient><linearGradient id="iqViIse" x1="8.759" x2="7.511" y1="28.73" y2="28.73" gradientUnits="userSpaceOnUse"><stop class="k6ta6mb-r"/><stop offset="1" class="drixk4bdm"/></linearGradient><linearGradient id="iuEO38c" x1="15.939" x2="15.939" y1="20.887" y2="29.918" gradientUnits="userSpaceOnUse"><stop class="zajm34fcf"/><stop offset="1" class="puh_1hb6q"/></linearGradient><linearGradient id="iuWe9FH" x1="15.939" x2="15.939" y1="29.918" y2="27.262" gradientUnits="userSpaceOnUse"><stop class="ou_12nqfl"/><stop offset="1" class="ypzxpcc2j"/></linearGradient><linearGradient id="iHk3RIe" x1="19.542" x2="17.698" y1="28.73" y2="28.73" gradientUnits="userSpaceOnUse"><stop offset=".119" class="zxxizob4i"/><stop offset="1" class="u7u0nyv_w"/></linearGradient><linearGradient id="i4eo8tb" x1="15.935" x2="15.935" y1="17.75" y2="25.779" gradientUnits="userSpaceOnUse"><stop class="gmn9ea1yo"/><stop offset="1" class="p71wtvbay"/></linearGradient><linearGradient id="idw5OAB" x1="16.35" x2="16.479" y1="19.066" y2="19.676" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="i7izNJb" x1="15.546" x2="15.417" y1="19.066" y2="19.676" gradientUnits="userSpaceOnUse"><stop class="uw1qucxdm"/><stop offset="1" class="qhxuaybfw"/></linearGradient><linearGradient id="igIGMXc" x1="15.948" x2="15.948" y1="14.66" y2="14.238" gradientUnits="userSpaceOnUse"><stop class="k0tankcbh"/><stop offset="1" class="ri19dgbsk"/></linearGradient><linearGradient id="iCHvGUY" x1="17.479" x2="16.94" y1="13.848" y2="14.09" gradientUnits="userSpaceOnUse"><stop class="h4n1x2_nx"/><stop offset="1" class="kbidwf4gr"/></linearGradient><linearGradient id="iYEG0Yd" x1="14.969" x2="14.516" y1="14.09" y2="14.017" gradientUnits="userSpaceOnUse"><stop class="ftqk6c0fk"/><stop offset="1" class="seh9j6z3x"/></linearGradient><linearGradient id="iBf6y4j" x1="12.448" x2="14.433" y1="8.67" y2="7.971" gradientUnits="userSpaceOnUse"><stop class="bq_0jebkw"/><stop offset="1" class="kjjvcb6je"/><stop offset="1" class="wasds5b8d"/></linearGradient><linearGradient id="iRfqIud" x1="19.43" x2="17.445" y1="8.67" y2="7.971" gradientUnits="userSpaceOnUse"><stop class="bq_0jebkw"/><stop offset="1" class="kjjvcb6je"/><stop offset="1" class="wasds5b8d"/></linearGradient><linearGradient id="i8cW9nd" x1="14.057" x2="12.174" y1="7.998" y2="8.369" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></linearGradient><linearGradient id="iAIOAke" x1="19.347" x2="17.323" y1="8.152" y2="7.918" gradientUnits="userSpaceOnUse"><stop class="map3_rs3n"/><stop offset="1" class="ymkmd4kjm"/></linearGradient><linearGradient id="iR27o2d" x1="16.905" x2="15.87" y1="11.73" y2="11.784" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="i4bzsSc" x1="15.966" x2="15.966" y1="12.766" y2="12.336" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iWWi5Pb" x1="15.966" x2="15.966" y1="10.263" y2="10.768" gradientUnits="userSpaceOnUse"><stop class="i5etcbh5r"/><stop offset="1" class="kyqssj_6u"/></linearGradient><linearGradient id="ilm68Qc" x1="18.886" x2="18.63" y1="10.09" y2="10.255" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iiNlMKc" x1="14.524" x2="14.21" y1="10.083" y2="10.276" gradientUnits="userSpaceOnUse"><stop class="hl4dixbko"/><stop offset="1" class="vo8nxhb-a"/></linearGradient><linearGradient id="iyfhQjd" x1="8.929" x2="9.979" y1="14.202" y2="14.202" gradientUnits="userSpaceOnUse"><stop class="ccjw6lk0v"/><stop offset="1" class="zvajyol-k"/></linearGradient><linearGradient id="iTPUcZc" x1="17.761" x2="17.761" y1="16.827" y2="15.374" gradientUnits="userSpaceOnUse"><stop offset=".131" class="c4ey9j8wv"/><stop offset="1" class="uabjeu-1v"/></linearGradient><linearGradient id="iMrbkCd" x1="23.104" x2="22.261" y1="14.858" y2="14.858" gradientUnits="userSpaceOnUse"><stop class="g7xtertqj"/><stop offset="1" class="eovkc4nhj"/></linearGradient><linearGradient id="iflgDGI" x1="9.052" x2="11.366" y1="10.454" y2="9.532" gradientUnits="userSpaceOnUse"><stop class="hldlhts-f"/><stop offset="1" class="g2u36d4kg"/></linearGradient><linearGradient id="iQRQihb" x1="21.483" x2="22.383" y1="8.378" y2="11.008" gradientUnits="userSpaceOnUse"><stop class="f5t1fub_l"/><stop offset="1" class="kcoeg77gv"/></linearGradient><linearGradient id="i4TB3ub" x1="21.784" x2="22.055" y1="8.123" y2="8.528" gradientUnits="userSpaceOnUse"><stop class="bgirfjbcd"/><stop offset="1" class="f3w7r3b-t"/></linearGradient><filter id="iqPOVKd" width="4.802" height="8.2" x="22.301" y="11.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1221"/></filter><filter id="iODtkLc" width="4.902" height="8.4" x="5.146" y="10.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.321569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1221"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.32549 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1221" result="effect2_innerShadow_4002_1221"/></filter><filter id="iPyy9Cb" width="6.968" height="4.815" x="12.464" y="15.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".25"/></filter><filter id="iLwdCXd" width="6.431" height="9.028" x="12.527" y="17.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".25"/></filter><filter id="i9lsj9b" width="5.531" height="8.006" x="13.22" y="17.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.705882 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1221"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.670588 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1221" result="effect2_innerShadow_4002_1221"/></filter><filter id="i7Kc5CY" width="6.43" height="4.559" x="12.733" y="15.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.835294 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1221"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.733333 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1221" result="effect2_innerShadow_4002_1221"/></filter><filter id="iW1hDLS" width="11.013" height="14.3" x="10.808" y="2.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.34902 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1221"/></filter><filter id="iCuNlHd" width="3.566" height="1.546" x="14.165" y="13.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".05"/></filter><filter id="iE3A5jd" width="2.177" height=".868" x="12.199" y="7.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".075"/></filter><filter id="igYgNev" width="2.177" height=".868" x="17.467" y="7.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".075"/></filter><filter id="ii65G0V" width="3.262" height="4.184" x="14.096" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".375"/></filter><filter id="iEw7h3c" width="2.279" height="3.084" x="14.827" y="9.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".1"/></filter><filter id="iweFLeu" width="3.001" height="1.285" x="16.908" y="9.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1221"/></filter><filter id="iGOqKtb" width="3.001" height="1.285" x="12.023" y="9.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1221"/></filter><filter id="ihTuwgq" width=".787" height=".697" x="17.413" y="9.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".05"/></filter><filter id="iTpfJcc" width=".892" height=".914" x="18.253" y="9.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".1"/></filter><filter id="iUhFCze" width=".987" height="1.041" x="13.807" y="9.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".1"/></filter><filter id="i5cvKrd" width=".914" height=".705" x="13.052" y="9.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".05"/></filter><filter id="i2wWkbx" width="2.017" height="3.595" x="9.092" y="8.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".1"/></filter><filter id="id8hkzc" width="6.998" height="4.138" x="15.057" y="3.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".5"/></filter><filter id="isyl05X" width="3.359" height="2.93" x="10.717" y="4.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".25"/></filter><filter id="iiH2ztb" width="1.798" height="3.38" x="20.88" y="8.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".05"/></filter><filter id="iluJIKd" width="5.928" height="1.395" x="13.023" y="2.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1221" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-vampire-medium-dark" /></template>
<style>
.a22pcob0d {
  fill: var(--svg-color--754d4d, #754D4D);
  d: path("m15.584 10.426l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.a3x3-i3qc {
  stop-color: var(--svg-color--724446, #724446);
  stop-opacity: 0;
}

.a75cnrb-k {
  stop-color: var(--svg-color--47374c, #47374C);
}

.anpbisbwb {
  d: path("m14.084 19.496l-.859 5.24a.402.402 0 0 0 .602.409l.201-.118a.51.51 0 0 1 .554.027l.706.514a1.1 1.1 0 0 0 1.294 0l.706-.514a.51.51 0 0 1 .553-.027l.202.118a.402.402 0 0 0 .602-.409l-.857-5.234c-.81-.505-1.856-1.28-1.856-1.28s-1.106.796-1.848 1.274");
}

.argi_pbpj {
  stop-color: var(--svg-color--754a51, #754A51);
  stop-opacity: 0;
}

.azamzibei {
  stop-color: var(--svg-color--6d4d4c, #6D4D4C);
  stop-opacity: 0;
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

.bgirfjbcd {
  stop-color: var(--svg-color--6c4639, #6C4639);
}

.boe_7q6ks {
  d: path("M18.084 9.74c.063.085-.07.19-.221.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.36c.15-.112.325-.135.389-.05");
}

.bq_0jebkw {
  stop-color: var(--svg-color--281c22, #281C22);
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

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.cvofkc-hn {
  fill: var(--svg-color--000, #000);
  d: path("M14.29 10.445a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
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

.eovkc4nhj {
  stop-color: var(--svg-color--303030, #303030);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.f1lm8sbjk {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
}

.f3w7r3b-t {
  stop-color: var(--svg-color--6c4639, #6C4639);
  stop-opacity: 0;
}

.f5t1fub_l {
  stop-color: var(--svg-color--7f5d51, #7F5D51);
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

.g2u36d4kg {
  stop-color: var(--svg-color--664642, #664642);
}

.g7xtertqj {
  stop-color: var(--svg-color--303030, #303030);
}

.gbck5ebgo {
  stop-color: var(--svg-color--a99494, #A99494);
  stop-opacity: 0;
}

.gcrpkvb6d {
  stop-color: var(--svg-color--724446, #724446);
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

.h-uaesb5h {
  stop-color: var(--svg-color--8a5856, #8A5856);
  stop-opacity: 0;
}

.h1sgipbfm {
  stop-color: var(--svg-color--d82535, #D82535);
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

.hh6luxbpp {
  stop-color: var(--svg-color--855e5c, #855E5C);
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

.hldlhts-f {
  stop-color: var(--svg-color--6b4648, #6B4648);
}

.i0lopbdha {
  stop-color: var(--svg-color--4a2f65, #4A2F65);
}

.i5etcbh5r {
  stop-color: var(--svg-color--845b55, #845B55);
}

.i8gko0bpu {
  stop-color: var(--svg-color--907068, #907068);
  stop-opacity: 0;
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

.j0bkjo9lk {
  stop-color: var(--svg-color--956d63, #956D63);
}

.jbgxtdigq {
  stop-color: var(--svg-color--996f61, #996F61);
  stop-opacity: 0;
}

.jedlegbwh {
  stop-color: var(--svg-color--743f59, #743F59);
}

.jpxim8b1x {
  stop-color: var(--svg-color--534263, #534263);
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

.k0tankcbh {
  stop-color: var(--svg-color--7f585b, #7F585B);
}

.k3bbh1b2g {
  stop-color: var(--svg-color--5c3838, #5C3838);
}

.k6ta6mb-r {
  stop-color: var(--svg-color--423153, #423153);
}

.kbidwf4gr {
  stop-color: var(--svg-color--d3cadb, #D3CADB);
}

.kcoeg77gv {
  stop-color: var(--svg-color--825b59, #825B59);
}

.kjjvcb6je {
  stop-color: var(--svg-color--301d1b, #301D1B);
}

.kna8kmbak {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.356 9.28c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.koudtg7gm {
  fill-rule: evenodd;
  d: path("M15.438 19.068a.125.125 0 0 0-.141.106l-.649 4.672a.125.125 0 1 0 .248.034l.648-4.671a.125.125 0 0 0-.106-.142");
}

.kqp3z9b3n {
  stop-color: var(--svg-color--9c8ea7, #9C8EA7);
  stop-opacity: 0;
}

.kyqssj_6u {
  stop-color: var(--svg-color--845b55, #845B55);
  stop-opacity: 0;
}

.l0d7sccpf {
  stop-color: var(--svg-color--48335e, #48335E);
}

.l1ztl-b4c {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.57 9.28c-.653 0-1.205.45-1.355 1.059a.274.274 0 0 0 .268.341h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.129");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
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

.m8g2io15v {
  stop-color: var(--svg-color--6d4d4c, #6D4D4C);
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

.mf0blib1m {
  stop-color: var(--svg-color--956d63, #956D63);
  stop-opacity: 0;
}

.n-3c_rb8h {
  stop-color: var(--svg-color--655777, #655777);
}

.n4t-p5ftj {
  stop-color: var(--svg-color--8a5856, #8A5856);
}

.n52c8qgao {
  stop-color: var(--svg-color--3d3743, #3D3743);
}

.n5t1ewtyv {
  stop-color: var(--svg-color--957971, #957971);
  stop-opacity: 0;
}

.nnhn70ftf {
  stop-color: var(--svg-color--907068, #907068);
}

.no5fe9bfr {
  d: path("m14.735 14.574l.396-.894a3.2 3.2 0 0 1-.623-.264c-.103-.057-.249.044-.22.157l.258.986a.1.1 0 0 0 .189.015");
}

.nve42acoy {
  fill: var(--svg-color--bb172a, #BB172A);
  d: path("M12.964 19.8v-3.485h5.968v3.387c0 .375-.216.56-.721.323c-.686-.322-2.277-1.501-2.277-1.501s-1.793 1.288-2.23 1.483c-.438.194-.74.168-.74-.207");
}

.nvpfuqb-a {
  stop-color: var(--svg-color--805a56, #805A56);
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

.odfe47amh {
  stop-color: var(--svg-color--746784, #746784);
}

.oj4dw6cda {
  stop-color: var(--svg-color--543e6e, #543E6E);
}

.olfta5bse {
  stop-color: var(--svg-color--764c3d, #764C3D);
  stop-opacity: 0;
}

.ou_12nqfl {
  stop-color: var(--svg-color--f73397, #F73397);
}

.oye8lqbkv {
  stop-color: var(--svg-color--957971, #957971);
}

.ozza9wbzj {
  stop-color: var(--svg-color--ff136b, #FF136B);
}

.p4zxjdbuk {
  stop-color: var(--svg-color--996e5f, #996E5F);
  stop-opacity: 0;
}

.p5bq_2b9f {
  stop-color: var(--svg-color--605075, #605075);
}

.p71wtvbay {
  stop-color: var(--svg-color--f3e0ff, #F3E0FF);
}

.pf4dk2bmi {
  stop-color: var(--svg-color--8c5884, #8C5884);
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

.pm06dk2ab {
  fill: var(--svg-color--724047, #724047);
  d: path("m15.69 10.59l-.82 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.378-.283-.378-.395 0");
}

.poqupx1-h {
  stop-color: var(--svg-color--6f424b, #6F424B);
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

.pxp9rxlhv {
  stop-color: var(--svg-color--e33e4b, #E33E4B);
}

.q_-i2n06o {
  stop-color: var(--svg-color--6f424b, #6F424B);
  stop-opacity: 0;
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

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
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

.r413jew7l {
  stop-color: var(--svg-color--996e5f, #996E5F);
}

.rbtgpsbuo {
  fill-rule: evenodd;
  d: path("M14.137 8.28c-.716-.134-1.345.18-1.569.342a.25.25 0 1 1-.294-.404c.292-.212 1.059-.597 1.955-.43a.25.25 0 1 1-.092.491");
}

.ri_i1lblj {
  stop-color: var(--svg-color--47374c, #47374C);
  stop-opacity: 0;
}

.ri19dgbsk {
  stop-color: var(--svg-color--7f585b, #7F585B);
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

.seh9j6z3x {
  stop-color: var(--svg-color--c7becf, #C7BECF);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sjtimycjx {
  d: path("M18.15 9.552a.893.893 0 0 1 .86 1.128h-1.726a.897.897 0 0 1 .865-1.129");
}

.skcf9z1zl {
  stop-color: var(--svg-color--7d5457, #7D5457);
}

.svmd8bcdt {
  d: path("M20.98 11.651c.04-.698.002-1.485.05-2.326l1.19-.81c.166-.114.384.005.355.204c-.116.82-.533 2.068-1.595 2.932");
}

.svsf1gaao {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M14.513 13.418a2.94 2.94 0 0 0 2.87 0c.077-.042.169.023.143.106c-.26.85-.993 1.027-1.578 1.027s-1.318-.176-1.578-1.027c-.026-.083.066-.148.143-.106");
}

.t_qv4acvq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.424 8.416c.224-.18.93-.5 1.727-.398");
}

.t0nshbc4e {
  fill: var(--svg-color--734b4c, #734B4C);
  d: path("M10.808 7.549a5 5 0 0 1 5.033-5.082l.262.001A5 5 0 0 1 21.07 7.58l-.092 4.098a5 5 0 0 1-4.999 4.888h-.103a5 5 0 0 1-4.999-4.917z");
}

.t6y7fjbra {
  fill-rule: evenodd;
  d: path("M17.74 8.28c.717-.134 1.346.18 1.57.342a.25.25 0 0 0 .294-.404c-.292-.212-1.059-.597-1.955-.43a.25.25 0 0 0 .091.491");
}

.trybmkb5r {
  stop-color: var(--svg-color--744652, #744652);
  stop-opacity: 0;
}

.u0smf3bxj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.419 8.416c-.224-.18-.93-.5-1.727-.398");
}

.u1xe1ac8d {
  stop-color: var(--svg-color--996f61, #996F61);
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

.urpxrxoti {
  d: path("M15.902 2.082a6.973 6.973 0 0 0-6.973 6.973v6.349c0 .69.56 1.25 1.25 1.25h1.027c.676-.336 1.38-.597 2.125-.785a5.02 5.02 0 0 1-2.457-4.22l-.059-4.107c0-.504.194-1.215.545-1.702c.09-.126.268-.066.295.087q.045.257.094.504c.109.562.597.893 1.166.908l.042.002l.04.002a52 52 0 0 0 5.92 0L19 7.339c.567-.015 1.012-.345 1.12-.908q.048-.247.094-.504c.027-.153.252-.213.342-.087c.242.337.393.794.482 1.198q.022.269.017.542l-.092 4.098a5 5 0 0 1-2.452 4.191a10.7 10.7 0 0 1 2.114.785h1c.69 0 1.25-.56 1.25-1.25V9.055a6.973 6.973 0 0 0-6.973-6.973");
}

.uw1qucxdm {
  stop-color: var(--svg-color--d2bdd8, #D2BDD8);
}

.uxwciubxp {
  stop-color: var(--svg-color--776484, #776484);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vbb18ixfb {
  stop-color: var(--svg-color--6b5a80, #6B5A80);
}

.vo8nxhb-a {
  stop-color: var(--svg-color--e5e5e5, #E5E5E5);
  stop-opacity: 0;
}

.vwjyd4bap {
  fill: var(--svg-color--ff809e, #FF809E);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M18.084 9.74c.063.085-.07.19-.221.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.36c.15-.112.325-.135.389-.05");
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

.x180dfzcy {
  stop-color: var(--svg-color--764c3d, #764C3D);
}

.xdq44cozz {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.513 13.418a2.94 2.94 0 0 0 2.87 0c.077-.042.169.023.143.106c-.26.85-.993 1.027-1.578 1.027s-1.318-.176-1.578-1.027c-.026-.083.066-.148.143-.106Z");
}

.xi4bd6b8m {
  stop-color: var(--svg-color--565656, #565656);
}

.xj-gubybt {
  stop-color: var(--svg-color--855e5c, #855E5C);
  stop-opacity: 0;
}

.xksrntfob {
  stop-color: var(--svg-color--b3a9bc, #B3A9BC);
}

.xn_fidfol {
  stop-color: var(--svg-color--ffc2c8, #FFC2C8);
  stop-opacity: 0;
}

.xu87aibcb {
  stop-color: var(--svg-color--623d4c, #623D4C);
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

.z1-l5rb6a {
  d: path("M5.77 11.516c2.243-2.144 5.052-3.377 6.334-3.817l4.063 12.313h-5.891c-2.916-1.118-4.43-4.529-4.986-6.895a1.68 1.68 0 0 1 .48-1.601");
}

.z8m-hreok {
  stop-color: var(--svg-color--47304f, #47304F);
}

.zajm34fcf {
  stop-color: var(--svg-color--e32d3d, #E32D3D);
}

.zar60tfds {
  stop-color: var(--svg-color--53302b, #53302B);
}

.zcyi13bvi {
  stop-color: var(--svg-color--53302b, #53302B);
  stop-opacity: 0;
}

.zex36v3bk {
  d: path("M10.826 8.632a15 15 0 0 0-1.717-.976c-.213-.102-.456.021-.46.258c-.014.64.118 1.503.656 2.527c.58 1.136 1.133 1.595 1.614 1.787a5 5 0 0 1-.043-.58z");
}

.zfvh726_h {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.824 10.057c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.369c-.269.217-.233.495-.025.6l.556.317c.652-.211 1.373-.24 2.08-.45");
}

.zvajyol-k {
  stop-color: var(--svg-color--4f4f4f, #4F4F4F);
  stop-opacity: 0;
}

.zxxizob4i {
  stop-color: var(--svg-color--c52133, #C52133);
}

</style>
