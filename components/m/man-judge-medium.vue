<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iptLbQb)" class="fe7ey10cb"/><path fill="url(#ihkEkHc)" class="fe7ey10cb"/><path fill="url(#iAWOLnw)" class="fe7ey10cb"/><path fill="url(#iUcWc7b)" class="yt6usyo0t"/><path fill="url(#iBT8Wwe)" class="yt6usyo0t"/><path fill="url(#iOhtJde)" class="yt6usyo0t"/><path fill="url(#itIO6Le)" class="yt6usyo0t"/><path fill="url(#iUtOrDb)" class="oom8p78ok"/><path fill="url(#ilXrsyb)" class="oom8p78ok"/><g filter="url(#il9aXcb)"><path fill="url(#ihdB6dC)" class="ldj9zjbke"/><path fill="url(#isT1HTc)" class="ldj9zjbke"/><path fill="url(#iWvIvoM)" class="ldj9zjbke"/></g><path fill="url(#iQWbhGb)" class="u1va93bkz"/><path fill="url(#ivokJ0v)" class="mhnhygrfn"/><path fill="url(#ik3UXAc)" class="e2rk3t8js"/><path fill="url(#i7hLnqe)" class="e2rk3t8js"/><path fill="url(#iW9eGjd)" class="e2rk3t8js"/><path fill="url(#izMMDlb)" class="q-sonkokk"/><path fill="url(#inl01rb)" class="q-sonkokk"/><path fill="url(#iQZoggd)" class="vrwffv4hi"/><path fill="url(#iW52i4b)" class="vrwffv4hi"/><path fill="url(#isXtg0F)" class="vrwffv4hi"/><path fill="url(#iMtHhwc)" class="vrwffv4hi"/><path fill="url(#igJaigd)" class="vrwffv4hi"/><path fill="url(#ibfXrfd)" class="eum5e4b5f"/><path fill="url(#iJpFxnd)" class="eum5e4b5f"/><path fill="url(#i0TWlBd)" class="eum5e4b5f"/><path fill="url(#i3B9Axb)" class="eum5e4b5f"/><path fill="url(#igmBWDq)" class="kpu9a_8ce"/><path fill="url(#i4fSIfr)" class="kpu9a_8ce"/><path fill="url(#ionJ2fc)" class="kpu9a_8ce"/><path fill="url(#iV1QwJb)" class="lvesrqb9a"/><path fill="url(#iMNlxic)" class="lvesrqb9a"/><g filter="url(#ioOTGAi)"><path fill="url(#iC5SxOL)" class="w9_g90b5u"/><path fill="url(#ixd03Vd)" class="w9_g90b5u"/><path fill="url(#ifX11hb)" class="w9_g90b5u"/><path fill="url(#i0Hx7hQ)" class="w9_g90b5u"/><path fill="url(#i9KllEO)" class="w9_g90b5u"/></g><rect fill="url(#ippXfWd)" class="f2-smwbax"/><rect fill="url(#icqNSRM)" class="f2-smwbax"/><g filter="url(#iGQXyjx)"><path fill="url(#iJ9jBHb)" class="b7mmd8bqc"/></g><g filter="url(#iADxb1c)"><path fill="url(#iZ5iRic)" class="bk_6pd1-r"/></g><g filter="url(#iUWBP6b)"><path fill="url(#iwrBVTc)" class="bp6i11nuo"/></g><g filter="url(#izwy2NV)"><path stroke="url(#ihzEPre)" class="vnr120b3q"/></g><g filter="url(#i7RBCgd)"><path stroke="url(#iF4P5pd)" class="xe4k3zwst"/></g><g filter="url(#iXuFfbe)"><path stroke="url(#idIQFrG)" class="yamz36b0i"/></g><g filter="url(#ijejjid)"><circle fill="url(#isjry6w)" class="r6dp_cbht"/></g><circle fill="url(#i0hmqst)" class="r6dp_cbht"/><g filter="url(#ipvidXt)"><circle fill="url(#i2I4guc)" class="zhlxc8b-x"/></g><g filter="url(#iOgmE2d)"><circle fill="url(#ismkwjd)" class="jo54m1qyb"/><circle fill="url(#i0onrLe)" class="jo54m1qyb"/></g><g filter="url(#ikJblDi)"><circle class="xbvc23b_u"/><circle fill="url(#iOo6Ife)" class="ou6l5dbar"/><circle fill="url(#iRljLnb)" class="ou6l5dbar"/></g><g filter="url(#inDqnlI)"><path fill="url(#ivef64b)" class="l87gp5bsn"/><path fill="url(#iihzIic)" class="l87gp5bsn"/><path fill="url(#i1vOmvc)" class="l87gp5bsn"/></g><path fill="url(#if2vu9d)" class="sarouvmig"/><path fill="url(#iclpBte)" class="sarouvmig"/><path fill="url(#i9RgKdc)" class="sarouvmig"/><g filter="url(#iadbNsM)"><path fill="url(#iwLUkeb)" class="tqgyvxbzf"/></g><g filter="url(#ixFnDfb)"><path class="djth4eb9k"/><path fill="url(#iifJk9d)" class="upcs6pbzp"/><path fill="url(#ivLy18R)" class="upcs6pbzp"/><path fill="url(#irqHQRc)" class="upcs6pbzp"/><path fill="url(#iFSXyOc)" class="upcs6pbzp"/></g><g filter="url(#iFBAhwb)"><path class="q1--n1bgc"/></g><g filter="url(#ipAvyhb)"><path class="cq4p1nbrv"/><path fill="url(#iNtFgTc)" class="kkop3dbua"/><path fill="url(#iZFyBUE)" class="kkop3dbua"/><path fill="url(#iRlIwQd)" class="kkop3dbua"/><path fill="url(#iDHEFqe)" class="kkop3dbua"/></g><path fill="url(#i8gHTsc)" class="kkop3dbua"/><path stroke="url(#i0ulSee)" class="trls78bxa"/><g filter="url(#iSSFYPc)"><path class="uz61l_bnc"/><path fill="url(#iEGTrad)" class="a8azo9bze"/></g><g filter="url(#iAElJUZ)"><path class="e8zclvbbp"/><path fill="url(#i113vce)" class="d3cnbnwvr"/></g><path class="tuqg5s_bv"/><path fill="url(#izsXxic)" class="fvy6mst5i"/><path class="lv5ad6bvv"/><g filter="url(#iCZvujU)"><path class="arqe7dm1i"/><path fill="url(#iVh3VIb)" class="rccst4yfc"/></g><g filter="url(#iJednNd)"><path fill="url(#imYekme)" class="w2wwdsb2r"/></g><path class="tu8-hdcwl"/><path fill="url(#iD1Kvcc)" class="a58oekzfj"/><path class="znxrtdbhh"/><g filter="url(#ir4zsQd)"><path fill="url(#iU5oCJb)" class="vmo-gwbbs"/></g><g filter="url(#i67I2uc)"><ellipse transform="rotate(-27.914 13.405 9.754)" class="r_p1vfbct"/><ellipse fill="url(#ihiQhdM)" transform="rotate(-27.914 13.405 9.754)" class="zk59__6eb"/></g><g filter="url(#imSowee)"><path stroke="url(#irRGlNb)" class="nasenab6o"/></g><g filter="url(#imz48wI)"><path stroke="url(#iA4Yjmc)" class="ax9thudfz"/></g><g filter="url(#iba01oY)"><path stroke="url(#ie7ytub)" class="p2_09-bse"/></g><defs><radialGradient id="iUcWc7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 4.778 29.98)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iBT8Wwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.627 29.98)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iOhtJde" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.627 23.03)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iUtOrDb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 24.93 4.624)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ilXrsyb" cx="0" cy="0" r="1" gradientTransform="matrix(.55555 12.0481 -1.01912 .047 22.909 23.133)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="isT1HTc" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 15.869 14.792)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="iWvIvoM" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 15.869 16.37)" gradientUnits="userSpaceOnUse"><stop class="qbrho_b3d"/><stop offset="1" class="jxn3-wb7y"/></radialGradient><radialGradient id="ivokJ0v" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 15.856 18.48)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="ik3UXAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.27137 -3.54923 0 16.629 16.442)" gradientUnits="userSpaceOnUse"><stop class="ecajbi3pj"/><stop offset="1" class="q4rmn6avz"/></radialGradient><radialGradient id="i7hLnqe" cx="0" cy="0" r="1" gradientTransform="scale(2.62391 4.73374)rotate(90 1.4 4.644)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="nii50obtj"/><stop offset=".923" class="dx_3m0biy"/></radialGradient><radialGradient id="iW9eGjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -.53125 0 14.548 16.2)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="nlxjfwb-j"/><stop offset="1" class="i7l4kj-sx"/></radialGradient><radialGradient id="izMMDlb" cx="0" cy="0" r="1" gradientTransform="rotate(145.605 10.324 16.09)scale(2.31047 2.27126)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="inl01rb" cx="0" cy="0" r="1" gradientTransform="rotate(-37.372 48.262 -28.767)scale(.9457 .72531)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="isXtg0F" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.554 17.372)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="i3B9Axb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.267 17.198)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="ionJ2fc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.033 17.448)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="iV1QwJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 25.955 24.264)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="ixd03Vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.723 25.284)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ifX11hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.723 26.579)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i0Hx7hQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.723 27.829)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i9KllEO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.723 29.18)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ippXfWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.4 21.44)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="isjry6w" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.443 10.532)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="i0hmqst" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.733 3.207)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="i0onrLe" cx="0" cy="0" r="1" gradientTransform="matrix(.82664 -.60191 .687 .9435 20.997 10.267)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iOo6Ife" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.584 11.353)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iRljLnb" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.493 30.343)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iihzIic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.206 9.26)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="i1vOmvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.648 9.395)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="i9RgKdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.32774 -10.3217 0 15.732 8.999)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ksbjoubur"/><stop offset=".969" class="s9dhzkwff"/></radialGradient><radialGradient id="iifJk9d" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.297 -9.977)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="ivLy18R" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -41.533 204.47)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="irqHQRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.86 1.931)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iFSXyOc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.412 8.75)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iDHEFqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.187 12.138)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iEGTrad" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 18.303 8.448)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i113vce" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.594 -3.587)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="izsXxic" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.039 9.85)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVh3VIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.81 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iD1Kvcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.676 9.85)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ihiQhdM" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.651 -1.556)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iptLbQb" x1="15.855" x2="15.855" y1="15.521" y2="30.405" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="ihkEkHc" x1="23.283" x2="20.752" y1="26.573" y2="26.605" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="iAWOLnw" x1="8.311" x2="10.527" y1="26.389" y2="26.389" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="itIO6Le" x1="8.774" x2="8.339" y1="28.046" y2="28.046" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="ihdB6dC" x1="22.595" x2="16.72" y1="18.48" y2="18.48" gradientUnits="userSpaceOnUse"><stop class="l4epxabbu"/><stop offset="1" class="mjg0akbde"/></linearGradient><linearGradient id="iQWbhGb" x1="16.986" x2="15.689" y1="19.058" y2="19.98" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="iQZoggd" x1="27.595" x2="24.22" y1="20.698" y2="20.323" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="iW52i4b" x1="25.316" x2="25.316" y1="20.964" y2="20.448" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iMtHhwc" x1="25.316" x2="25.316" y1="16.818" y2="17.449" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="igJaigd" x1="23.019" x2="23.76" y1="19.166" y2="19.166" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="ibfXrfd" x1="23.189" x2="21.892" y1="18.949" y2="18.949" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="iJpFxnd" x1="23.439" x2="23.049" y1="19.23" y2="19.23" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="i0TWlBd" x1="22.644" x2="22.644" y1="21.06" y2="20.397" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="igmBWDq" x1="28.89" x2="27.27" y1="19.397" y2="19.397" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="i4fSIfr" x1="28.189" x2="28.189" y1="21.034" y2="20.511" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iMNlxic" x1="25.317" x2="25.345" y1="21.976" y2="22.331" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iC5SxOL" x1="27.314" x2="23.286" y1="28.042" y2="28.042" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="icqNSRM" x1="25.328" x2="25.328" y1="20.792" y2="21.253" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iJ9jBHb" x1="16.905" x2="16.905" y1="29.583" y2="22.906" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iZ5iRic" x1="12.899" x2="12.899" y1="29.583" y2="22.906" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iwrBVTc" x1="20.892" x2="20.892" y1="29.583" y2="22.906" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ihzEPre" x1="23.806" x2="25.516" y1="26.05" y2="26.05" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iF4P5pd" x1="23.728" x2="25.438" y1="27.355" y2="27.355" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="idIQFrG" x1="23.806" x2="25.516" y1="28.659" y2="28.659" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i2I4guc" x1="11.113" x2="10.472" y1="10.811" y2="10.811" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="ismkwjd" x1="21.711" x2="20.893" y1="9.44" y2="11.976" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="ivef64b" x1="19.896" x2="12.259" y1="10.921" y2="12.059" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="if2vu9d" x1="10.465" x2="12.346" y1="13.617" y2="13.55" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iclpBte" x1="20.78" x2="19.668" y1="12.776" y2="12.679" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iwLUkeb" x1="15.329" x2="23.472" y1="7.937" y2="5.021" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iNtFgTc" x1="14.996" x2="15.934" y1="11.581" y2="11.581" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iZFyBUE" x1="16.798" x2="15.773" y1="11.903" y2="11.888" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iRlIwQd" x1="16.055" x2="16.055" y1="12.645" y2="12.072" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="i8gHTsc" x1="15.986" x2="15.986" y1="12.687" y2="12.52" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="i0ulSee" x1="14.823" x2="15.258" y1="14.26" y2="13.573" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="imYekme" x1="18.817" x2="18.503" y1="9.904" y2="10.097" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iU5oCJb" x1="14.42" x2="14.106" y1="9.904" y2="10.097" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irRGlNb" x1="18.832" x2="18.412" y1="7.764" y2="6.906" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iA4Yjmc" x1="13.528" x2="12.339" y1="7.637" y2="7.138" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ie7ytub" x1="11.198" x2="11.198" y1="5.622" y2="7.779" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><filter id="il9aXcb" width="14.254" height="7.618" x="8.842" y="15.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1736"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1736" result="effect2_innerShadow_4002_1736"/></filter><filter id="ioOTGAi" width="4.468" height="5.556" x="23.286" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1736"/></filter><filter id="iGQXyjx" width="1.192" height="6.826" x="15.273" y="23.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".125"/></filter><filter id="iADxb1c" width="1.192" height="6.826" x="11.266" y="23.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".125"/></filter><filter id="iUWBP6b" width="1.192" height="6.826" x="19.259" y="23.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".125"/></filter><filter id="izwy2NV" width="2.097" height=".3" x="23.656" y="25.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".05"/></filter><filter id="i7RBCgd" width="2.097" height=".3" x="23.578" y="27.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".05"/></filter><filter id="iXuFfbe" width="2.097" height=".3" x="23.656" y="28.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".05"/></filter><filter id="ijejjid" width="3.539" height="3.339" x="9.443" y="8.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1736"/></filter><filter id="ipvidXt" width="2.99" height="2.99" x="9.618" y="9.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".25"/></filter><filter id="iOgmE2d" width="3.589" height="3.589" x="18.956" y="8.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1736"/></filter><filter id="ikJblDi" width="2.99" height="2.99" x="19.13" y="9.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".25"/></filter><filter id="inDqnlI" width="10.373" height="12.177" x="10.702" y="4.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1736"/></filter><filter id="iadbNsM" width="8.246" height="7.066" x="14.03" y="2.908" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation="1"/></filter><filter id="ixFnDfb" width="12.601" height="8.543" x="9.56" y="1.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1736"/></filter><filter id="iFBAhwb" width="3.26" height="4.181" x="13.991" y="9.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".375"/></filter><filter id="ipAvyhb" width="2.377" height="3.181" x="14.672" y="9.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".125"/></filter><filter id="iSSFYPc" width="2.979" height="1.873" x="17.042" y="6.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1736"/></filter><filter id="iAElJUZ" width="2.98" height="1.873" x="11.895" y="6.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1736"/></filter><filter id="iCZvujU" width=".787" height=".696" x="17.305" y="9.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".05"/></filter><filter id="iJednNd" width=".891" height=".913" x="18.145" y="9.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".1"/></filter><filter id="ir4zsQd" width=".986" height="1.04" x="13.703" y="9.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".1"/></filter><filter id="i67I2uc" width=".913" height=".704" x="12.948" y="9.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".05"/></filter><filter id="imSowee" width="3.099" height="1.681" x="16.895" y="7.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".25"/></filter><filter id="imz48wI" width="3.177" height="1.738" x="11.677" y="7.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".25"/></filter><filter id="iba01oY" width="1.008" height="2.269" x="10.694" y="5.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1736" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-judge-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a58oekzfj {
  d: path("M13.674 9.373a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.a8azo9bze {
  d: path("M19.58 7.812h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .166 1.054c.398-.062.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.arqe7dm1i {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.975 9.562c.064.085-.07.188-.22.301c-.151.113-.263.193-.327.108s.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.ax9thudfz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.302 8.186c.327-.29 1.041-.594 1.927-.452");
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b7mmd8bqc {
  d: path("M15.523 23.523h.692v6.326h-.692z");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bk_6pd1-r {
  d: path("M11.516 23.523h.692v6.326h-.692z");
}

.bp6i11nuo {
  d: path("M19.509 23.523h.692v6.326h-.692z");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cq4p1nbrv {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.478 10.247l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d3cnbnwvr {
  d: path("M12.087 7.813v-.001h.001l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 1 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.3.16l-.008.005a.534.534 0 0 1-.68-.823");
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.djth4eb9k {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m20.679 4.055l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.43-.96a1.25 1.25 0 0 1-.374-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.dx_3m0biy {
  stop-color: var(--svg-color--5a3527, #5A3527);
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e2rk3t8js {
  d: path("M15.859 18.714a2.07 2.07 0 0 1-2.075-2.075v-2.58a2.07 2.07 0 0 1 2.075-2.064c1.148 0 2.075.927 2.075 2.075v2.579a2.083 2.083 0 0 1-2.075 2.065");
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e8zclvbbp {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M12.087 7.813v-.001h.001l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 1 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.3.16l-.008.005a.534.534 0 0 1-.68-.823");
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ecajbi3pj {
  stop-color: var(--svg-color--98686e, #98686E);
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.eum5e4b5f {
  d: path("M22.861 16.935h-.613a.505.505 0 0 0-.504.504v3.021c0 .272.222.504.504.504h.613a.505.505 0 0 0 .504-.504v-3.02a.51.51 0 0 0-.504-.504");
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f2-smwbax {
  width: 2.773px;
  height: 1.082px;
  x: 23.941px;
  y: 20.964px;
  rx: 0.541px;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fe7ey10cb {
  d: path("M15.859 15.52c-6.115 0-11.08 4.907-11.08 10.97v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-4.956-10.97-11.07-10.97");
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fvy6mst5i {
  d: path("M18.04 9.373a.892.892 0 0 1 .86 1.127h-1.723a.896.896 0 0 1 .864-1.127");
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.i7l4kj-sx {
  stop-color: var(--svg-color--937268, #937268);
  stop-opacity: 0;
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jo54m1qyb {
  cx: 20.625px;
  cy: 10.532px;
  r: 1.669px;
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jxn3-wb7y {
  stop-color: var(--svg-color--3b2321, #3B2321);
  stop-opacity: 0;
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kkop3dbua {
  d: path("m15.478 10.247l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.kpu9a_8ce {
  d: path("M28.387 16.935h-.613a.505.505 0 0 0-.504.504v3.021c0 .272.222.504.504.504h.613a.505.505 0 0 0 .503-.504v-3.02a.51.51 0 0 0-.503-.504");
}

.ksbjoubur {
  stop-color: var(--svg-color--95616c, #95616C);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l4epxabbu {
  stop-color: var(--svg-color--564d5b, #564D5B);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l87gp5bsn {
  d: path("M10.76 9.92h.05s-.054-.852-.108-1.439c0-.267.108-.587.322-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.272.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.ldj9zjbke {
  d: path("M8.93 17.848c1.974-1.646 4.385-2.423 6.939-2.423c2.553 0 4.965.777 6.94 2.423a.24.24 0 0 1 .06.296c-1.354 2.69-3.772 4.65-7 4.65s-5.646-1.96-7.001-4.65a.24.24 0 0 1 .061-.296");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lv5ad6bvv {
  fill: var(--svg-color--000, #000);
  d: path("M17.53 10.265c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.lvesrqb9a {
  d: path("M24.562 21.05v6.427h1.511V21.05z");
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mhnhygrfn {
  d: path("m16.65 19.862l.136-.121a3.5 3.5 0 0 0 1.148-2.549v-1.964h-4.15l-.006 1.912c0 .051.004.147 0 .2c.045.916.46 1.784 1.144 2.401l.16.143l.666-1.01a.13.13 0 0 1 .221 0z");
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mjg0akbde {
  stop-color: var(--svg-color--433945, #433945);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nasenab6o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.52 7.668c.43-.076 1.27-.054 1.85.397");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.nii50obtj {
  stop-color: var(--svg-color--5a3527, #5A3527);
  stop-opacity: 0;
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nlxjfwb-j {
  stop-color: var(--svg-color--937268, #937268);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.oom8p78ok {
  d: path("M23.08 29.98V18.179c2.357 2.01 3.85 4.987 3.85 8.31v2.49a1 1 0 0 1-1 1z");
}

.ou6l5dbar {
  cx: 20.625px;
  cy: 10.532px;
  r: 0.995px;
}

.p2_09-bse {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.328 5.721v.897c-.008.149-.07.481-.258.622");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.q-sonkokk {
  d: path("M26.642 22.913c.532 0 .959.427.959.958v2.189h-1.907v-2.19a.94.94 0 0 1 .948-.958");
}

.q1--n1bgc {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.585 10.41l-.82 1.7c-.102.349.142.698.487.698h.738c.345 0 .59-.354.488-.699l-.499-1.7c-.106-.376-.282-.376-.394 0");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q4rmn6avz {
  stop-color: var(--svg-color--9d736b, #9D736B);
}

.qbrho_b3d {
  stop-color: var(--svg-color--3b2321, #3B2321);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r_p1vfbct {
  cx: 13.405px;
  cy: 9.754px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.r6dp_cbht {
  cx: 11.113px;
  cy: 10.532px;
  r: 1.669px;
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rccst4yfc {
  d: path("M17.975 9.562c.064.085-.07.188-.22.301c-.151.113-.263.193-.327.108s.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s9dhzkwff {
  stop-color: var(--svg-color--865058, #865058);
}

.sarouvmig {
  d: path("M10.702 8.481c0-.267.108-.587.322-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.272.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003c-.14-1.816-.2-3.638-.367-5.451");
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tqgyvxbzf {
  d: path("m19.823 4.908l-3.077 1.026a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.trls78bxa {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.498 13.289a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24c.344.52.942.868 1.624.868s1.28-.347 1.625-.868a.19.19 0 0 0-.021-.242a.2.2 0 0 0-.242-.04a2.94 2.94 0 0 1-1.362.323c-.5 0-.968-.117-1.362-.322Z");
}

.tu8-hdcwl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.467 9.101c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.tuqg5s_bv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.248 9.101c.652 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.u1va93bkz {
  d: path("m16.786 19.741l-.655.584a.416.416 0 0 1-.554 0l-.655-.584a3.47 3.47 0 0 1-1.148-2.569V14.06a2.085 2.085 0 0 1 2.085-2.065c1.148 0 2.075.927 2.075 2.075v3.113a3.5 3.5 0 0 1-1.149 2.558");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.upcs6pbzp {
  d: path("m20.679 4.055l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.044-.433-.032-.565-.43-.96a1.25 1.25 0 0 1-.374-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.533 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.663 0c.804-.267 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.uz61l_bnc {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M19.58 7.812h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .166 1.054c.398-.062.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vmo-gwbbs {
  d: path("M14.49 10.16c0-.288-.235-.48-.299-.538l-.288.279l.178.36z");
}

.vnr120b3q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.806 25.972h1.797");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vrwffv4hi {
  d: path("M26.766 16.935h-2.9a.505.505 0 0 0-.504.504v3.021c0 .272.221.504.503.504h2.901a.505.505 0 0 0 .504-.504v-3.02a.51.51 0 0 0-.504-.504");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w2wwdsb2r {
  d: path("M18.836 10.148a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.w9_g90b5u {
  d: path("M23.286 25.305c0-.4.325-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.407-.657");
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xbvc23b_u {
  cx: 20.625px;
  cy: 10.532px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.xe4k3zwst {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.728 27.277h1.797");
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.yamz36b0i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.806 28.581h1.797");
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.yt6usyo0t {
  d: path("M8.627 29.98V18.179c-2.356 2.01-3.849 4.987-3.849 8.31v3.49z");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zhlxc8b-x {
  cx: 11.113px;
  cy: 10.532px;
  r: 0.995px;
}

.zk59__6eb {
  cx: 13.405px;
  cy: 9.754px;
  rx: 0.389px;
  ry: 0.197px;
}

.znxrtdbhh {
  fill: var(--svg-color--000, #000);
  d: path("M14.185 10.265a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.236");
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
