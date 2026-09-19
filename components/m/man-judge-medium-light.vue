<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixIXOvc)" class="zqh9u0bvn"/><path fill="url(#iH5a7Nd)" class="zqh9u0bvn"/><path fill="url(#i0Pfx5b)" class="zqh9u0bvn"/><path fill="url(#iFACFxc)" class="ir5t06xzs"/><path fill="url(#iSVxpkX)" class="ir5t06xzs"/><path fill="url(#i7sxgWd)" class="ir5t06xzs"/><path fill="url(#iXaeDdd)" class="ir5t06xzs"/><path fill="url(#iBqz0SQ)" class="jnrp4gb9d"/><path fill="url(#ihn3jpd)" class="jnrp4gb9d"/><g filter="url(#ihmX3hc)"><path fill="url(#itgSrse)" class="t51fbub9r"/><path fill="url(#iQqZisH)" class="t51fbub9r"/><path fill="url(#iNTfvod)" class="t51fbub9r"/></g><path fill="url(#iAyOR8b)" class="tpwf47bly"/><path fill="url(#iau7XHV)" class="dzco6q47d"/><path fill="url(#i5BhIFz)" class="u6uy3xxgn"/><path fill="url(#ifr67nd)" class="u6uy3xxgn"/><path fill="url(#iIfGHKr)" class="u6uy3xxgn"/><path fill="url(#iv6fhlA)" class="wsvayfbjf"/><path fill="url(#iajsRGe)" class="wsvayfbjf"/><path fill="url(#io9p1ke)" class="lucudlboi"/><path fill="url(#i8RY69b)" class="lucudlboi"/><path fill="url(#iyBA8Mb)" class="lucudlboi"/><path fill="url(#i0C0h8d)" class="lucudlboi"/><path fill="url(#iy1BGje)" class="lucudlboi"/><path fill="url(#idjKr5c)" class="qsmwpgbvv"/><path fill="url(#iX0NFWn)" class="qsmwpgbvv"/><path fill="url(#iVRKzzc)" class="qsmwpgbvv"/><path fill="url(#ibg7ZPQ)" class="qsmwpgbvv"/><path fill="url(#iSZ561c)" class="c00utebtq"/><path fill="url(#il1kMAF)" class="c00utebtq"/><path fill="url(#iOK5k3d)" class="c00utebtq"/><path fill="url(#ivfBSSc)" class="v2925ibxf"/><path fill="url(#i75QuTb)" class="v2925ibxf"/><g filter="url(#ilP5Rmd)"><path fill="url(#iJOhnbd)" class="l1qvqlbmp"/><path fill="url(#id5ozYc)" class="l1qvqlbmp"/><path fill="url(#iT7FXYd)" class="l1qvqlbmp"/><path fill="url(#i5dMq2b)" class="l1qvqlbmp"/><path fill="url(#ix1q8Rb)" class="l1qvqlbmp"/></g><rect fill="url(#ichoAMb)" class="au2wdyb2q"/><rect fill="url(#iQqybDb)" class="au2wdyb2q"/><g filter="url(#iiD6g7b)"><path fill="url(#iezOoed)" class="t3a5w7teu"/></g><g filter="url(#izmQI7b)"><path fill="url(#iVI265c)" class="k6ea535mx"/></g><g filter="url(#iljgxrc)"><path fill="url(#iXSTjOe)" class="p8nckz2ep"/></g><g filter="url(#iwBBx8c)"><path stroke="url(#irMaFpb)" class="ikar2hbcm"/></g><g filter="url(#iqKiv5K)"><path stroke="url(#ixqcDMb)" class="af73w6bmc"/></g><g filter="url(#ipdbDLu)"><path stroke="url(#ibbYXOd)" class="sx4z4gbch"/></g><g filter="url(#iou8T1c)"><circle fill="url(#it4AbZo)" class="wnz7x-n-y"/></g><g filter="url(#i3iKGhd)"><circle fill="url(#iKwAMYb)" class="h-bu5lvdf"/></g><g filter="url(#i8t2k2d)"><circle fill="url(#ilAxYId)" class="pku3s0tow"/><circle fill="url(#iVMmIFc)" class="pku3s0tow"/></g><g filter="url(#i23zDDe)"><circle class="f06hl_2iy"/><circle fill="url(#iwLEGHe)" class="xg6qthb4r"/><circle fill="url(#ii9Gi7c)" class="xg6qthb4r"/></g><g filter="url(#iEepb5c)"><path fill="url(#iydxuxw)" class="i1ooihbai"/><path fill="url(#iYiLBCc)" class="i1ooihbai"/><path fill="url(#ihh6EMb)" class="i1ooihbai"/><path fill="url(#igjiJed)" class="i1ooihbai"/><path fill="url(#iV1iIwd)" class="i1ooihbai"/></g><g filter="url(#iWyMDDb)"><path class="d7dp5accs"/><path fill="url(#ix0AFHd)" class="ak_hun-vd"/><path fill="url(#iU2EENc)" class="ak_hun-vd"/><path fill="url(#iDwLiNd)" class="ak_hun-vd"/><path fill="url(#i9UE8hU)" class="ak_hun-vd"/><path fill="url(#iFhTkfe)" class="ak_hun-vd"/></g><path fill="url(#iPf7ptb)" class="ak_hun-vd"/><path fill="url(#iLNleAb)" class="ak_hun-vd"/><g filter="url(#iPmQuYd)"><path class="n80bo-2ac"/></g><g filter="url(#idZIKdb)"><path class="obegqub4r"/><path fill="url(#iJRNN3N)" class="lfj8_pywr"/><path fill="url(#ijSJqbr)" class="lfj8_pywr"/><path fill="url(#iUTc7ed)" class="lfj8_pywr"/></g><path fill="url(#iP7VuXd)" class="lfj8_pywr"/><path stroke="url(#ih5Sq5d)" class="scucmuhbt"/><g filter="url(#icyL71T)"><path class="hqxlks2ww"/></g><g filter="url(#i6zd36b)"><path class="s5avg2bcr"/></g><path class="chd-rkp-s"/><path fill="url(#iXE9Myd)" class="c78v41bsw"/><path class="hubgrncvu"/><g filter="url(#iW1BPye)"><path class="n56qbsbcc"/><path fill="url(#iN7gsPe)" class="i-jyhz3wh"/></g><g filter="url(#ihDM6tc)"><path fill="url(#ina6z0b)" class="l2d_snbdh"/></g><path class="krhbc7uau"/><path fill="url(#iZELOFb)" class="d-n6gibxd"/><path class="tkaw2ctqa"/><g filter="url(#iiDtp2p)"><path fill="url(#i0ud7de)" class="alk7kbbxz"/></g><g filter="url(#ijBCWDd)"><ellipse transform="rotate(-27.914 13.385 9.878)" class="d1knebbrk"/><ellipse fill="url(#iMVXVtd)" transform="rotate(-27.914 13.385 9.878)" class="bsswevb3z"/></g><g filter="url(#iqAUocD)"><path stroke="url(#iycnQvA)" class="o2pnm969x"/></g><g filter="url(#iXEZt0d)"><path stroke="url(#ih8s5Qb)" class="ck6unzbfn"/></g><defs><radialGradient id="iFACFxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 4.778 30)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iSVxpkX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.627 30)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="i7sxgWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.627 23.05)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iBqz0SQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92413 -10.2056 2.9218 -.55086 25.005 30)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ihn3jpd" cx="0" cy="0" r="1" gradientTransform="matrix(.55555 12.0481 -1.01912 .047 22.909 23.153)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iQqZisH" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 15.869 14.812)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="iNTfvod" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 15.869 16.39)" gradientUnits="userSpaceOnUse"><stop class="qbrho_b3d"/><stop offset="1" class="jxn3-wb7y"/></radialGradient><radialGradient id="iau7XHV" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 15.856 18.5)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="i5BhIFz" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.27137 -3.54923 0 16.629 16.462)" gradientUnits="userSpaceOnUse"><stop class="j4fq87b3w"/><stop offset="1" class="jxgb44stn"/></radialGradient><radialGradient id="ifr67nd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.4661 -2.44965 0 15.859 15.374)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukg1xnbxa"/><stop offset=".923" class="f-lk6hbga"/></radialGradient><radialGradient id="iIfGHKr" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -.53125 0 14.548 16.219)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="h-8qjbcjs"/><stop offset="1" class="wgyur5thp"/></radialGradient><radialGradient id="iv6fhlA" cx="0" cy="0" r="1" gradientTransform="rotate(145.605 10.321 16.1)scale(2.31047 2.27126)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iajsRGe" cx="0" cy="0" r="1" gradientTransform="rotate(-37.372 48.291 -28.757)scale(.9457 .72531)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iyBA8Mb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.554 17.392)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="ibg7ZPQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.267 17.218)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="iOK5k3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.033 17.468)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="ivfBSSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 25.955 24.284)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="id5ozYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.723 25.304)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iT7FXYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.723 26.599)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i5dMq2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.723 27.849)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ix1q8Rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.723 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ichoAMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.4 21.46)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="it4AbZo" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.424 10.656)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iVMmIFc" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 20.977 10.39)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iwLEGHe" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.564 11.477)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="ii9Gi7c" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.605 10.656)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iYiLBCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.6693 -10.1935 0 16.311 7.314)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="igjiJed" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 18.186 9.384)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iV1iIwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.629 9.35)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="ix0AFHd" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.045 6.255)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iDwLiNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 11.647 7.2)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i9UE8hU" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 20.067 8.919)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="iFhTkfe" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 15.066 2.055)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iPf7ptb" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 16.535 2.055)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iLNleAb" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 11.495 3.783)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iXE9Myd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 18.02 10.307)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iN7gsPe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.359 .672)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZELOFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 13.656 10.307)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iMVXVtd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.702 -1.485)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ixIXOvc" x1="15.855" x2="15.855" y1="15.54" y2="30.425" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="iH5a7Nd" x1="23.283" x2="20.752" y1="26.593" y2="26.625" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="i0Pfx5b" x1="8.311" x2="10.527" y1="26.409" y2="26.409" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="iXaeDdd" x1="8.774" x2="8.339" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="itgSrse" x1="22.595" x2="16.72" y1="18.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="l4epxabbu"/><stop offset="1" class="mjg0akbde"/></linearGradient><linearGradient id="iAyOR8b" x1="16.986" x2="15.689" y1="19.078" y2="20" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="io9p1ke" x1="27.595" x2="24.22" y1="20.718" y2="20.343" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="i8RY69b" x1="25.316" x2="25.316" y1="20.984" y2="20.468" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="i0C0h8d" x1="25.316" x2="25.316" y1="16.838" y2="17.469" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iy1BGje" x1="23.019" x2="23.76" y1="19.185" y2="19.185" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="idjKr5c" x1="23.189" x2="21.892" y1="18.969" y2="18.969" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="iX0NFWn" x1="23.439" x2="23.049" y1="19.25" y2="19.25" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iVRKzzc" x1="22.644" x2="22.644" y1="21.08" y2="20.417" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="iSZ561c" x1="28.89" x2="27.27" y1="19.417" y2="19.417" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="il1kMAF" x1="28.189" x2="28.189" y1="21.054" y2="20.531" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="i75QuTb" x1="25.317" x2="25.345" y1="21.996" y2="22.351" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iJOhnbd" x1="27.314" x2="23.286" y1="28.062" y2="28.062" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="nfkkf0b1d"/></linearGradient><linearGradient id="iQqybDb" x1="25.328" x2="25.328" y1="20.812" y2="21.273" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iezOoed" x1="16.905" x2="16.905" y1="29.603" y2="22.926" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iVI265c" x1="12.899" x2="12.899" y1="29.603" y2="22.926" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iXSTjOe" x1="20.892" x2="20.892" y1="29.603" y2="22.926" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="irMaFpb" x1="23.806" x2="25.516" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="ixqcDMb" x1="23.728" x2="25.438" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="ibbYXOd" x1="23.806" x2="25.516" y1="28.679" y2="28.679" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iKwAMYb" x1="11.093" x2="10.452" y1="10.934" y2="10.934" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="ilAxYId" x1="21.692" x2="20.873" y1="9.564" y2="12.1" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iydxuxw" x1="19.876" x2="12.24" y1="11.045" y2="12.183" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ihh6EMb" x1="10.445" x2="12.757" y1="13.741" y2="13.439" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iU2EENc" x1="10.98" x2="13.882" y1="10.389" y2="5.234" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iJRNN3N" x1="14.976" x2="15.914" y1="11.704" y2="11.704" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="ijSJqbr" x1="16.779" x2="15.753" y1="12.027" y2="12.012" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iUTc7ed" x1="16.035" x2="16.035" y1="12.769" y2="12.196" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iP7VuXd" x1="15.966" x2="15.966" y1="12.811" y2="12.643" gradientUnits="userSpaceOnUse"><stop class="e14d05bbo"/><stop offset="1" class="jt8p4rb1c"/></linearGradient><linearGradient id="ih5Sq5d" x1="14.803" x2="15.238" y1="14.384" y2="13.696" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="ina6z0b" x1="18.797" x2="18.483" y1="10.028" y2="10.221" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0ud7de" x1="14.4" x2="14.086" y1="10.028" y2="10.221" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iycnQvA" x1="18.813" x2="18.392" y1="7.888" y2="7.03" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="ih8s5Qb" x1="13.508" x2="12.319" y1="7.76" y2="7.262" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><filter id="ihmX3hc" width="14.254" height="7.618" x="8.842" y="15.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1739"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1739" result="effect2_innerShadow_4002_1739"/></filter><filter id="ilP5Rmd" width="4.468" height="5.556" x="23.286" y="24.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1739"/></filter><filter id="iiD6g7b" width="1.192" height="6.826" x="15.273" y="23.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".125"/></filter><filter id="izmQI7b" width="1.192" height="6.826" x="11.266" y="23.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".125"/></filter><filter id="iljgxrc" width="1.192" height="6.826" x="19.259" y="23.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".125"/></filter><filter id="iwBBx8c" width="2.097" height=".3" x="23.656" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".05"/></filter><filter id="iqKiv5K" width="2.097" height=".3" x="23.578" y="27.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".05"/></filter><filter id="ipdbDLu" width="2.097" height=".3" x="23.656" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".05"/></filter><filter id="iou8T1c" width="3.539" height="3.339" x="9.424" y="8.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1739"/></filter><filter id="i3iKGhd" width="2.99" height="2.99" x="9.598" y="9.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".25"/></filter><filter id="i8t2k2d" width="3.589" height="3.589" x="18.936" y="8.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1739"/></filter><filter id="i23zDDe" width="2.99" height="2.99" x="19.11" y="9.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".25"/></filter><filter id="iEepb5c" width="10.373" height="12.177" x="10.683" y="5.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1739"/></filter><filter id="iWyMDDb" width="12.601" height="8.543" x="9.54" y="1.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1739"/></filter><filter id="iPmQuYd" width="3.26" height="4.181" x="13.972" y="9.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".375"/></filter><filter id="idZIKdb" width="2.377" height="3.181" x="14.652" y="9.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".125"/></filter><filter id="icyL71T" width="2.979" height="1.873" x="17.023" y="7.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1739"/></filter><filter id="i6zd36b" width="2.98" height="1.873" x="11.875" y="7.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1739"/></filter><filter id="iW1BPye" width=".787" height=".696" x="17.285" y="9.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".05"/></filter><filter id="ihDM6tc" width=".891" height=".913" x="18.125" y="9.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".1"/></filter><filter id="iiDtp2p" width=".986" height="1.04" x="13.683" y="9.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".1"/></filter><filter id="ijBCWDd" width=".913" height=".704" x="12.929" y="9.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".05"/></filter><filter id="iqAUocD" width="3.099" height="1.681" x="16.876" y="7.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".25"/></filter><filter id="iXEZt0d" width="3.177" height="1.738" x="11.657" y="7.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1739" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-judge-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.af73w6bmc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.728 27.296h1.797");
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ak_hun-vd {
  d: path("m20.659 4.178l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.907.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.271.266-3.915.426a.52.52 0 0 0-.429.534v.853c0 .32-.107.64-.376.853l-.16.16c-.215.16-.322.48-.322.747c.053.586.107 1.44.107 1.44q-.025 0-.049-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.108-.853.321-1.706 1.072-2.08l.43-.213c.267-.16.536-.373.804-.586l.965-1.013c.59-.534 1.448-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.586");
}

.alk7kbbxz {
  d: path("M14.47 10.284c0-.288-.235-.48-.298-.538l-.289.278l.178.362z");
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.au2wdyb2q {
  width: 2.773px;
  height: 1.082px;
  x: 23.941px;
  y: 20.984px;
  rx: 0.541px;
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bsswevb3z {
  cx: 13.385px;
  cy: 9.878px;
  rx: 0.389px;
  ry: 0.197px;
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c00utebtq {
  d: path("M28.387 16.955h-.613a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h.613a.505.505 0 0 0 .503-.504v-3.022a.51.51 0 0 0-.503-.503");
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c78v41bsw {
  d: path("M18.021 9.497a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.chd-rkp-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.228 9.225c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.ck6unzbfn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.282 8.31c.327-.29 1.041-.594 1.927-.453");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d-n6gibxd {
  d: path("M13.654 9.497a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.d1knebbrk {
  cx: 13.385px;
  cy: 9.878px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.d7dp5accs {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m20.659 4.178l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.907.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.271.266-3.915.426a.52.52 0 0 0-.429.534v.853c0 .32-.107.64-.376.853l-.16.16c-.215.16-.322.48-.322.747c.053.586.107 1.44.107 1.44q-.025 0-.049-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.108-.853.321-1.706 1.072-2.08l.43-.213c.267-.16.536-.373.804-.586l.965-1.013c.59-.534 1.448-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.586");
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dzco6q47d {
  d: path("m16.65 19.882l.136-.121a3.5 3.5 0 0 0 1.148-2.549v-1.964h-4.15l-.006 1.912c0 .051.004.146 0 .2a3.47 3.47 0 0 0 1.144 2.4l.16.144l.666-1.01a.13.13 0 0 1 .221 0z");
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e14d05bbo {
  stop-color: var(--svg-color--c27b77, #C27B77);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f-lk6hbga {
  stop-color: var(--svg-color--a86f4a, #A86F4A);
}

.f06hl_2iy {
  cx: 20.605px;
  cy: 10.656px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.ft5dv1b6b {
  fill: none;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h-8qjbcjs {
  stop-color: var(--svg-color--bf8c7c, #BF8C7C);
}

.h-bu5lvdf {
  cx: 11.093px;
  cy: 10.656px;
  r: 0.995px;
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hqxlks2ww {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m19.56 7.936l-.002-.001l-.002-.001l-.004-.004l-.012-.01a2 2 0 0 0-.155-.107a2.5 2.5 0 0 0-.42-.21a2.83 2.83 0 0 0-1.492-.16a.534.534 0 1 0 .166 1.055c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .679-.824");
}

.hubgrncvu {
  fill: var(--svg-color--000, #000);
  d: path("M17.51 10.39c0-.285.227-.512.511-.512a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.i-jyhz3wh {
  d: path("M17.956 9.686c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.i1ooihbai {
  d: path("m10.741 10.043l.05.002s-.055-.854-.108-1.44c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853c0-.267.16-.48.43-.534c.643-.16 1.984-.426 3.914-.426s3.272.266 3.916.426c.214.054.429.267.429.534v.853c0 .32.16.64.375.853c.502.352.471.545.43.96a46 46 0 0 0-.108 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003z");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ikar2hbcm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.806 25.992h1.797");
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.ir5t06xzs {
  d: path("M8.627 30V18.198c-2.356 2.01-3.849 4.986-3.849 8.31V30z");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j4fq87b3w {
  stop-color: var(--svg-color--c2877e, #C2877E);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jnrp4gb9d {
  d: path("M23.08 30V18.198c2.357 2.01 3.85 4.986 3.85 8.31V29a1 1 0 0 1-1 1z");
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jt8p4rb1c {
  stop-color: var(--svg-color--c27b77, #C27B77);
  stop-opacity: 0;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jxgb44stn {
  stop-color: var(--svg-color--c68c7e, #C68C7E);
}

.jxn3-wb7y {
  stop-color: var(--svg-color--3b2321, #3B2321);
  stop-opacity: 0;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k6ea535mx {
  d: path("M11.516 23.543h.692v6.326h-.692z");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.krhbc7uau {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.448 9.225c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l1qvqlbmp {
  d: path("M23.286 25.325c0-.401.325-.732.727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.l2d_snbdh {
  d: path("M18.816 10.272a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.l4epxabbu {
  stop-color: var(--svg-color--564d5b, #564D5B);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lfj8_pywr {
  d: path("m15.458 10.37l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lucudlboi {
  d: path("M26.766 16.955h-2.9a.505.505 0 0 0-.504.503v3.022c0 .272.221.504.503.504h2.901a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.503");
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjg0akbde {
  stop-color: var(--svg-color--433945, #433945);
}

.n56qbsbcc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.956 9.686c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.n80bo-2ac {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.565 10.534l-.82 1.699c-.102.35.142.7.488.7h.737c.346 0 .59-.356.488-.7l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.nfkkf0b1d {
  stop-color: var(--svg-color--c4907c, #C4907C);
}

.o2pnm969x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.5 7.792c.43-.076 1.27-.054 1.85.397");
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

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.obegqub4r {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.458 10.37l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.p8nckz2ep {
  d: path("M19.509 23.543h.692v6.326h-.692z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pku3s0tow {
  cx: 20.605px;
  cy: 10.656px;
  r: 1.669px;
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
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

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qbrho_b3d {
  stop-color: var(--svg-color--3b2321, #3B2321);
}

.qsmwpgbvv {
  d: path("M22.861 16.955h-.613a.505.505 0 0 0-.504.503v3.022c0 .272.222.504.504.504h.613a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.503");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s5avg2bcr {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m12.067 7.936l.002-.001l.002-.001l.004-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.16a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.824");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.scucmuhbt {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.479 13.413c.393.205.862.322 1.361.322c.505 0 .969-.117 1.362-.322a.2.2 0 0 1 .242.04a.185.185 0 0 1 .02.24m-2.985-.28l2.944.253m-2.944-.253h-.001a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.263-.281l-.221.253m3.207.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.625.869c-.681 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.582-.846m-.042.028l.042-.028m-.042.028l.042-.028");
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.sx4z4gbch {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.806 28.601h1.797");
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t3a5w7teu {
  d: path("M15.523 23.543h.692v6.326h-.692z");
}

.t51fbub9r {
  d: path("M8.93 17.868c1.974-1.647 4.385-2.423 6.939-2.423c2.553 0 4.965.776 6.94 2.423a.24.24 0 0 1 .06.295c-1.354 2.691-3.772 4.65-7 4.65s-5.646-1.959-7.001-4.65a.24.24 0 0 1 .061-.295");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tkaw2ctqa {
  fill: var(--svg-color--000, #000);
  d: path("M14.165 10.389a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.tpwf47bly {
  d: path("m16.786 19.76l-.655.585a.416.416 0 0 1-.554 0l-.655-.584a3.47 3.47 0 0 1-1.148-2.569V14.08a2.085 2.085 0 0 1 2.085-2.065c1.148 0 2.075.926 2.075 2.075v3.112a3.5 3.5 0 0 1-1.149 2.559");
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u6uy3xxgn {
  d: path("M15.859 18.733a2.07 2.07 0 0 1-2.075-2.075V14.08a2.07 2.07 0 0 1 2.075-2.065c1.148 0 2.075.926 2.075 2.075v2.578a2.083 2.083 0 0 1-2.075 2.065");
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ukg1xnbxa {
  stop-color: var(--svg-color--a86f4a, #A86F4A);
  stop-opacity: 0;
}

.upbi0xbpg {
  stop-color: var(--svg-color--9f6e75, #9F6E75);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v2925ibxf {
  d: path("M24.562 21.07v6.427h1.511V21.07z");
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wgyur5thp {
  stop-color: var(--svg-color--bf8c7c, #BF8C7C);
  stop-opacity: 0;
}

.wnz7x-n-y {
  cx: 11.093px;
  cy: 10.656px;
  r: 1.669px;
}

.wsvayfbjf {
  d: path("M26.642 22.933c.532 0 .959.427.959.958v2.189h-1.907v-2.19a.94.94 0 0 1 .948-.958");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.xg6qthb4r {
  cx: 20.605px;
  cy: 10.656px;
  r: 0.995px;
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zqh9u0bvn {
  d: path("M15.859 15.54c-6.115 0-11.08 4.907-11.08 10.97V30h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.064-4.956-10.97-11.07-10.97");
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
