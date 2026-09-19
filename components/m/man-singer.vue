<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iCWTmWd)"><path class="vqqyf1ezs"/><path fill="url(#iOxiyrc)" class="j_621bcjm"/></g><path fill="url(#iXi4h4d)" class="spqd6sdrt"/><path fill="url(#iJBiQcc)" class="spqd6sdrt"/><path fill="url(#iGN16Le)" class="i_4hbvwfo"/><path fill="url(#iW5zceH)" class="i_4hbvwfo"/><path fill="url(#i1xqcWd)" class="rfjfa1bja"/><path fill="url(#ihH5Y8d)" class="rfjfa1bja"/><path fill="url(#iDCLUxb)" class="rfjfa1bja"/><path fill="url(#inQ1xid)" class="rfjfa1bja"/><path fill="url(#ihlfaxd)" class="gbrz2vbln"/><path fill="url(#iQ77aIe)" class="gbrz2vbln"/><path fill="url(#iRlfsKb)" class="gbrz2vbln"/><path fill="url(#iXnoj3F)" class="gbrz2vbln"/><path fill="url(#iDKi8Cd)" class="gbrz2vbln"/><path fill="url(#iKgU0Dd)" class="gbrz2vbln"/><path fill="url(#iehXMEc)" class="z5k3hykxe"/><path fill="url(#ish2ETd)" class="za8u66qzh"/><path fill="url(#iwal7Wd)" class="dyuf14bun"/><path fill="url(#i6NKlqe)" class="p7feigaop"/><path fill="url(#iaJBOje)" class="p7feigaop"/><path fill="url(#i8Wj3Pe)" class="p7feigaop"/><path fill="url(#iPsnyBb)" class="c7_k1-b_e"/><path fill="url(#iBnpcTb)" class="c7_k1-b_e"/><path fill="url(#ilyYmyb)" class="b92digbbh"/><path fill="url(#iI5bO4U)" class="b92digbbh"/><path fill="url(#ipdtiEc)" class="b92digbbh"/><path fill="url(#imWeJIm)" class="b92digbbh"/><g filter="url(#iq1T53D)"><path fill="url(#iGo4Fgc)" class="h99oc_bkr"/><path fill="url(#isdXOJb)" class="h99oc_bkr"/><path fill="url(#iZlwCGc)" class="h99oc_bkr"/></g><path fill="url(#ilLNYkc)" class="mit5e8b-p"/><path fill="url(#iiSktQc)" class="mit5e8b-p"/><path fill="url(#ipKHGgg)" class="mit5e8b-p"/><g filter="url(#ibt98Ud)"><path fill="url(#iXKqR8d)" class="y0shchp6a"/></g><g filter="url(#iQPYI8c)"><circle fill="url(#i6ZdLPk)" class="wukxw4q3o"/></g><g filter="url(#i19f1hd)"><path fill="url(#iUC0JJb)" class="od5poibgd"/><path fill="url(#inD2Nxc)" class="od5poibgd"/><path fill="url(#i7glo2t)" class="od5poibgd"/><path fill="url(#i9c87oc)" class="od5poibgd"/><path fill="url(#iKXy61b)" class="od5poibgd"/></g><g filter="url(#ijWB2Cc)"><path stroke="url(#ivOQ3Qx)" class="c888u_swh"/></g><g filter="url(#iYmGG0b)"><path stroke="url(#iu0nhpe)" class="g9f514h7r"/></g><g filter="url(#i8NeFLf)"><path stroke="url(#iRtbhGb)" class="lwjto15zk"/></g><circle fill="url(#iF9hR0c)" class="hron7-jrb"/><g filter="url(#iUR7wbD)"><circle fill="url(#imnUHWb)" class="po5k0_b-j"/></g><g filter="url(#i2iLMWd)"><circle fill="url(#ip7Kejc)" class="aj1t2oboj"/><circle fill="url(#ic0q3fc)" class="aj1t2oboj"/></g><g filter="url(#iKH7oib)"><circle class="eqde1ummf"/><circle fill="url(#i9LJbFb)" class="pig8d1kob"/><circle fill="url(#il3Zacd)" class="pig8d1kob"/></g><path fill="url(#iRp4w2d)" class="pp291w7ri"/><path fill="url(#iXyKLPe)" class="pp291w7ri"/><path fill="url(#ioYvoXb)" class="pp291w7ri"/><path fill="url(#i6hfJ8S)" class="pp291w7ri"/><path fill="url(#iUbb3md)" class="pp291w7ri"/><path fill="url(#iaGGRfb)" class="pp291w7ri"/><g filter="url(#ioIyqvl)"><path class="g1_qv6ooq"/><path fill="url(#iQ4Sebe)" class="ooudlucgc"/><path fill="url(#ipOH4mb)" class="ooudlucgc"/><path fill="url(#iar4bFb)" class="ooudlucgc"/><path fill="url(#icwTNnd)" class="ooudlucgc"/><path fill="url(#i13V0me)" class="ooudlucgc"/><path fill="url(#iy7w2ae)" class="ooudlucgc"/></g><path fill="url(#iqibdJb)" class="ooudlucgc"/><path fill="url(#iYbZo9d)" class="ooudlucgc"/><path fill="url(#iFfUave)" class="ooudlucgc"/><g filter="url(#i8jduTL)"><path class="yvhebp9nr"/></g><g filter="url(#iIROWac)"><path class="m0qsh7i3v"/><path fill="url(#i4CzjTd)" class="p3-t9eb_f"/><path fill="url(#ilYFZRb)" class="p3-t9eb_f"/><path fill="url(#iuHIGMy)" class="p3-t9eb_f"/></g><path fill="url(#iRQR9uc)" class="p3-t9eb_f"/><path fill="url(#is7Tn2c)" clip-rule="evenodd" class="jyzygw7bt"/><path fill="url(#iSNCfTb)" clip-rule="evenodd" class="jyzygw7bt"/><g filter="url(#iLse3fo)"><path stroke="url(#i0B43Ke)" class="oqz6wfbzx"/></g><path class="rks-1vyeu"/><path class="aj8q0obiy"/><path fill="url(#iHKkBGq)" class="jwayjobjw"/><path class="r7o4--bwd"/><g filter="url(#iC01Wld)"><path class="otn9tqb3c"/><path fill="url(#ilhWCZb)" class="rg_zdtz3i"/></g><g filter="url(#ic78ZLd)"><path fill="url(#iU88Fcb)" class="x65qbiboo"/></g><path class="rdti6hbah"/><path fill="url(#i0RPiHf)" class="sid-44bbw"/><path class="t8-h6jsbg"/><g filter="url(#itRh06b)"><path fill="url(#i0TxYBd)" class="a2zk7kmkp"/></g><g filter="url(#iTOMJ9c)"><ellipse transform="rotate(-27.914 12.631 11.967)" class="b82r2qmhy"/><ellipse fill="url(#iZi2hyc)" transform="rotate(-27.914 12.631 11.967)" class="e2rmi5b2a"/></g><g filter="url(#iOTCJVd)"><path fill="url(#iNXFHiX)" clip-rule="evenodd" class="ygbzbr4js"/></g><g filter="url(#iYxBz7b)"><path class="votimdvat"/></g><g filter="url(#i9zwhAK)"><path fill="url(#iokpjBb)" clip-rule="evenodd" class="nk2zv_s_d"/></g><g filter="url(#ibLZAKd)"><path class="frn-pubwg"/></g><defs><radialGradient id="iXi4h4d" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 26.172)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="iGN16Le" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.473 19.825)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="iDCLUxb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 18.453)" gradientUnits="userSpaceOnUse"><stop class="m4vk7-mbl"/><stop offset="1" class="esw1hmivn"/></radialGradient><radialGradient id="iQ77aIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55616 -6.67822 .6506 -.1516 13.25 29.074)" gradientUnits="userSpaceOnUse"><stop class="o4j1rvu5g"/><stop offset="1" class="yp-hr1bpr"/></radialGradient><radialGradient id="iKgU0Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17874 .81494 -1.02635 -2.74392 12.187 18.338)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="k910dfb4a"/><stop offset="1" class="vm-pj7b0c"/></radialGradient><radialGradient id="i6NKlqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.106 20.82)" gradientUnits="userSpaceOnUse"><stop class="gwxe3pb8f"/><stop offset=".766" class="t0h--bk_d"/></radialGradient><radialGradient id="iaJBOje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.763)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="sbrbvfbik"/><stop offset=".937" class="omgy1jbfi"/></radialGradient><radialGradient id="iPsnyBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.25267 -.93725 1.10778 1.48058 26.804 23.197)" gradientUnits="userSpaceOnUse"><stop class="xcnvxobld"/><stop offset="1" class="k7fvrbbpb"/></radialGradient><radialGradient id="iBnpcTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81108 .73899 -.74364 -.8162 28.02 21.782)" gradientUnits="userSpaceOnUse"><stop class="u7id6gble"/><stop offset="1" class="ydn9dmb6d"/></radialGradient><radialGradient id="iI5bO4U" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.222 12.36)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="ipdtiEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.768)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="imWeJIm" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 17.126)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="isdXOJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 17.517)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iXKqR8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 21.388)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="i6ZdLPk" cx="0" cy="0" r="1" gradientTransform="rotate(43.152 -16.483 26.834)scale(2.9724 3.56688)" gradientUnits="userSpaceOnUse"><stop class="ijcmcsb6h"/><stop offset=".865" class="p354_vbhd"/></radialGradient><radialGradient id="inD2Nxc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62488 2.62025 -2.19236 -1.35953 28.346 23.148)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="i7glo2t" cx="0" cy="0" r="1" gradientTransform="matrix(2.59834 0 0 .51085 23.704 24.656)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><radialGradient id="i9c87oc" cx="0" cy="0" r="1" gradientTransform="matrix(2.91284 0 0 .57269 23.495 26.11)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><radialGradient id="iKXy61b" cx="0" cy="0" r="1" gradientTransform="matrix(3.0548 0 0 .35964 23.388 27.499)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="pzho1txaw"/><stop offset="1" class="r-w7u-p-k"/></radialGradient><radialGradient id="iF9hR0c" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.665 12.746)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ic0q3fc" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.231 12.48)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="i9LJbFb" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 19.817 13.568)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="il3Zacd" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 19.86 12.746)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="ioYvoXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.00203 -9.92656 0 15.58 11.153)" gradientUnits="userSpaceOnUse"><stop offset=".666" class="mfzl6wbzn"/><stop offset=".985" class="celc_92fg"/></radialGradient><radialGradient id="i6hfJ8S" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 17.437 11.473)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iUbb3md" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 12.875 11.44)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iQ4Sebe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43986 4.43352 -7.5396 -5.84979 18.785 5.026)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iar4bFb" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.624 -.439)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="icwTNnd" cx="0" cy="0" r="1" gradientTransform="matrix(.85996 -1.96834 1.60534 .70136 19.32 11.007)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="i13V0me" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.23303 -1.08867 .87739 14.313 4.136)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iy7w2ae" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -3.03851 1.04984 .50181 19.281 8.523)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iqibdJb" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 1.01586 -1.67013 .42978 15.784 4.136)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iYbZo9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.60044 -3.3305 2.30572 10.703 5.398)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iFfUave" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21429 3.2501 -4.0668 -9.02713 16.243 8.378)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="is7Tn2c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15622 3.87502 -2.80434 -2.28415 14.93 10.013)" gradientUnits="userSpaceOnUse"><stop class="mon_o44bn"/><stop offset="1" class="k27wcn7av"/></radialGradient><radialGradient id="i0B43Ke" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 15.004 16.762)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iHKkBGq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 17.27 12.397)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ilhWCZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.041 12.146)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0RPiHf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 12.902 12.397)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iZi2hyc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.354 -.069)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNXFHiX" cx="0" cy="0" r="1" gradientTransform="matrix(.19698 -.81253 1.78256 .43214 17.543 10.544)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iokpjBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.19698 -.81253 1.78256 -.43214 12.636 10.545)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><linearGradient id="iOxiyrc" x1="16.901" x2="15.504" y1="26.693" y2="26.39" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iJBiQcc" x1="7.199" x2="6.027" y1="26.492" y2="26.492" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iW5zceH" x1="23.128" x2="23.77" y1="26.578" y2="26.547" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="i1xqcWd" x1="22.77" x2="18.395" y1="16.563" y2="29.073" gradientUnits="userSpaceOnUse"><stop class="c08ew-b0i"/><stop offset="1" class="exuz4sbao"/></linearGradient><linearGradient id="ihH5Y8d" x1="16.824" x2="17.53" y1="27.063" y2="27.158" gradientUnits="userSpaceOnUse"><stop class="q5z4iwf2u"/><stop offset="1" class="t7ud1ab5b"/></linearGradient><linearGradient id="inQ1xid" x1="20.787" x2="20.787" y1="16.563" y2="17.662" gradientUnits="userSpaceOnUse"><stop offset=".457" class="tffk3lifv"/><stop offset="1" class="e4yz8gz4u"/></linearGradient><linearGradient id="ihlfaxd" x1="7.895" x2="11.895" y1="18.203" y2="29.453" gradientUnits="userSpaceOnUse"><stop class="m3gjwjbhl"/><stop offset="1" class="c9zswtx-n"/></linearGradient><linearGradient id="iRlfsKb" x1="8.365" x2="9.063" y1="16.309" y2="19.873" gradientUnits="userSpaceOnUse"><stop class="s434a46or"/><stop offset="1" class="qrv_44bpu"/></linearGradient><linearGradient id="iXnoj3F" x1="7.895" x2="8.309" y1="23.14" y2="22.937" gradientUnits="userSpaceOnUse"><stop class="bwk0n7bpz"/><stop offset="1" class="oinrtsbml"/></linearGradient><linearGradient id="iDKi8Cd" x1="13.739" x2="13.328" y1="28.768" y2="28.855" gradientUnits="userSpaceOnUse"><stop class="ifhx39w3y"/><stop offset="1" class="tmbtljdgb"/></linearGradient><linearGradient id="iehXMEc" x1="23.395" x2="21.614" y1="26.609" y2="26.609" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="ish2ETd" x1="8.114" x2="10.395" y1="28.422" y2="27.265" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="iwal7Wd" x1="15.111" x2="15.111" y1="17.963" y2="29.067" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8Wj3Pe" x1="17.916" x2="16.316" y1="22.62" y2="22.377" gradientUnits="userSpaceOnUse"><stop offset=".061" class="ko-tlzp-g"/><stop offset="1" class="hk3yvnfuu"/></linearGradient><linearGradient id="ilyYmyb" x1="25.739" x2="25.739" y1="16.259" y2="20.316" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="iGo4Fgc" x1="25.933" x2="25.792" y1="17.195" y2="18.398" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iZlwCGc" x1="23.236" x2="23.363" y1="17.132" y2="17.568" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="ilLNYkc" x1="26.936" x2="24.648" y1="21.702" y2="21.702" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iiSktQc" x1="24.466" x2="24.847" y1="21.544" y2="21.516" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="ipKHGgg" x1="27.084" x2="26.822" y1="21.416" y2="21.392" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="iUC0JJb" x1="28.021" x2="23.495" y1="26.949" y2="26.949" gradientUnits="userSpaceOnUse"><stop class="kwbcosrfm"/><stop offset=".861" class="rfqu9yc3v"/></linearGradient><linearGradient id="ivOQ3Qx" x1="25.63" x2="23.568" y1="24.669" y2="24.669" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><linearGradient id="iu0nhpe" x1="25.63" x2="23.568" y1="26.11" y2="26.11" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><linearGradient id="iRtbhGb" x1="25.63" x2="23.568" y1="27.541" y2="27.541" gradientUnits="userSpaceOnUse"><stop class="qebm4hycr"/><stop offset="1" class="b9b7yqeyc"/></linearGradient><linearGradient id="imnUHWb" x1="10.336" x2="9.695" y1="13.025" y2="13.025" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="ip7Kejc" x1="20.946" x2="20.127" y1="11.653" y2="14.192" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iRp4w2d" x1="19.128" x2="11.485" y1="13.136" y2="14.275" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iXyKLPe" x1="9.688" x2="12.002" y1="15.834" y2="15.532" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iaGGRfb" x1="15.604" x2="15.604" y1="19.206" y2="18.925" gradientUnits="userSpaceOnUse"><stop class="r1mb9pb8s"/><stop offset="1" class="d4w9rrbto"/></linearGradient><linearGradient id="ipOH4mb" x1="10.223" x2="13.128" y1="12.479" y2="7.319" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="i4CzjTd" x1="14.224" x2="15.163" y1="13.795" y2="13.795" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="ilYFZRb" x1="16.028" x2="15.001" y1="14.118" y2="14.104" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iuHIGMy" x1="15.283" x2="15.283" y1="14.861" y2="14.288" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iRQR9uc" x1="15.214" x2="15.214" y1="14.903" y2="14.735" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="iSNCfTb" x1="14" x2="14.078" y1="7.011" y2="8.245" gradientUnits="userSpaceOnUse"><stop class="npzd0rb6d"/><stop offset="1" class="q2sj4_bau"/></linearGradient><linearGradient id="iU88Fcb" x1="18.048" x2="17.734" y1="12.117" y2="12.31" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0TxYBd" x1="13.647" x2="13.333" y1="12.117" y2="12.31" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><filter id="iCWTmWd" width="5.513" height="4.74" x="12.848" y="24.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2311"/></filter><filter id="iq1T53D" width="6.102" height="1.228" x="22.791" y="17.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2311"/></filter><filter id="ibt98Ud" width="1.075" height="1.075" x="25.198" y="21.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2311"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2311" result="effect2_innerShadow_4002_2311"/></filter><filter id="iQPYI8c" width="5.813" height="5.813" x="12.243" y="15.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".25"/></filter><filter id="i19f1hd" width="5.519" height="6.076" x="23.128" y="22.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2311"/></filter><filter id="ijWB2Cc" width="2.269" height=".25" x="23.617" y="24.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".05"/></filter><filter id="iYmGG0b" width="2.269" height=".25" x="23.617" y="25.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".05"/></filter><filter id="i8NeFLf" width="2.269" height=".25" x="23.617" y="27.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".05"/></filter><filter id="iUR7wbD" width="2.992" height="2.992" x="8.84" y="11.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".25"/></filter><filter id="i2iLMWd" width="3.592" height="3.592" x="18.188" y="10.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2311"/></filter><filter id="iKH7oib" width="2.992" height="2.992" x="18.363" y="11.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".25"/></filter><filter id="ioIyqvl" width="12.614" height="8.301" x="8.782" y="3.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2311"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2311" result="effect2_innerShadow_4002_2311"/></filter><filter id="i8jduTL" width="3.262" height="4.184" x="13.219" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".375"/></filter><filter id="iIROWac" width="2.379" height="3.184" x="13.899" y="11.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".125"/></filter><filter id="iLse3fo" width="3.621" height="1.474" x="13.278" y="15.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".05"/></filter><filter id="iC01Wld" width=".787" height=".697" x="16.535" y="11.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".05"/></filter><filter id="ic78ZLd" width=".892" height=".914" x="17.376" y="11.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".1"/></filter><filter id="itRh06b" width=".987" height="1.041" x="12.93" y="11.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".1"/></filter><filter id="iTOMJ9c" width=".914" height=".705" x="12.174" y="11.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".05"/></filter><filter id="iOTCJVd" width="2.604" height="1.648" x="16.354" y="9.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2311"/></filter><filter id="iYxBz7b" width="2.709" height="1.503" x="16.301" y="9.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".2"/></filter><filter id="i9zwhAK" width="2.604" height="1.648" x="11.22" y="9.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2311"/></filter><filter id="ibLZAKd" width="2.709" height="1.503" x="11.168" y="9.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2311" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-singer" /></template>
<style>
.a2zk7kmkp {
  d: path("M13.716 12.374c0-.289-.234-.481-.298-.54l-.288.28l.177.361z");
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.aj1t2oboj {
  cx: 19.859px;
  cy: 12.746px;
  r: 1.671px;
}

.aj8q0obiy {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.479 11.314c.653 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.b82r2qmhy {
  cx: 12.631px;
  cy: 11.967px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.b92digbbh {
  d: path("M25.766 20.262a2.498 2.498 0 1 0 0-4.997a2.498 2.498 0 0 0 0 4.997");
}

.b9b7yqeyc {
  stop-color: var(--svg-color--d58628, #D58628);
}

.bwk0n7bpz {
  stop-color: var(--svg-color--3e8ed5, #3E8ED5);
}

.c08ew-b0i {
  stop-color: var(--svg-color--2ca9dd, #2CA9DD);
}

.c7_k1-b_e {
  d: path("M27.277 21.388c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.c888u_swh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.742 24.669h2.02");
}

.c9zswtx-n {
  stop-color: var(--svg-color--3073d6, #3073D6);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.celc_92fg {
  stop-color: var(--svg-color--e2844f, #E2844F);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d4w9rrbto {
  stop-color: var(--svg-color--e28369, #E28369);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dyuf14bun {
  d: path("M15.118 17.963c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e2rmi5b2a {
  cx: 12.631px;
  cy: 11.967px;
  rx: 0.39px;
  ry: 0.197px;
}

.e4yz8gz4u {
  stop-color: var(--svg-color--2ea1dc, #2EA1DC);
  stop-opacity: 0;
}

.eqde1ummf {
  cx: 19.859px;
  cy: 12.746px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.esw1hmivn {
  stop-color: var(--svg-color--2796d4, #2796D4);
  stop-opacity: 0;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.exuz4sbao {
  stop-color: var(--svg-color--3069c9, #3069C9);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.frn-pubwg {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.693 10.397c.209-.193.803-.52 1.658-.44");
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.g1_qv6ooq {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m19.912 6.262l.43.214c.751.373 1.18 1.227 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.533c.035-.504.069-1.317.082-1.445c.043-.434-.025-.562-.422-.957c-.215-.213-.376-.534-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.323.495-.323.762c.014.156.035 1.052.06 1.426a.634.634 0 0 1-.596-.533l-.59-3.042c-.108-.855.321-1.709 1.073-2.082c1.015-.445 1.385-1.12 2.201-1.816c.591-.533 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.053 2.363.534l.805.8c.215.268.483.428.805.588");
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g9f514h7r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.742 26.11h2.02");
}

.gbrz2vbln {
  d: path("M5.405 17.084h6.086l2.248 11.989h-2.79l-5.88-11.529c-.086-.125-.07-.46.336-.46");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.gwxe3pb8f {
  stop-color: var(--svg-color--ffc033, #FFC033);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.h99oc_bkr {
  d: path("m28.214 17.103l-4.844-.02a.57.57 0 0 0-.58.579c0 .325.255.579.58.579l4.844.02a.57.57 0 0 0 .578-.579a.585.585 0 0 0-.578-.579");
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hk3yvnfuu {
  stop-color: var(--svg-color--fbb231, #FBB231);
  stop-opacity: 0;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hron7-jrb {
  cx: 10.336px;
  cy: 12.746px;
  r: 1.671px;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i_4hbvwfo {
  d: path("M27.018 29.063c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.ifhx39w3y {
  stop-color: var(--svg-color--3469bc, #3469BC);
}

.ijcmcsb6h {
  stop-color: var(--svg-color--e58421, #E58421);
}

.j_621bcjm {
  d: path("M12.848 24.323v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.jwayjobjw {
  d: path("M17.272 11.586a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.jyzygw7bt {
  fill-rule: evenodd;
  d: path("M15.067 7.116c-.9.003-1.67.064-2.298.143l-2.11 6.215h1.808l-.507 2.687l3.687-5.132h-1.883z");
}

.k27wcn7av {
  stop-color: var(--svg-color--ec375e, #EC375E);
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k7fvrbbpb {
  stop-color: var(--svg-color--ffd033, #FFD033);
}

.k910dfb4a {
  stop-color: var(--svg-color--2c649b, #2C649B);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.ko-tlzp-g {
  stop-color: var(--svg-color--ce6f07, #CE6F07);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.kwbcosrfm {
  stop-color: var(--svg-color--ffe432, #FFE432);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lwjto15zk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.742 27.54h2.02");
}

.m0qsh7i3v {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m14.706 12.46l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.378-.646-.378-.765 0");
}

.m3gjwjbhl {
  stop-color: var(--svg-color--258ec6, #258EC6);
}

.m4vk7-mbl {
  stop-color: var(--svg-color--40a8ea, #40A8EA);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mfzl6wbzn {
  stop-color: var(--svg-color--f59b3c, #F59B3C);
  stop-opacity: 0;
}

.mit5e8b-p {
  d: path("M25.726 26.903a.784.784 0 0 1-.782-.711l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.mon_o44bn {
  stop-color: var(--svg-color--ff2d8d, #FF2D8D);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.nk2zv_s_d {
  fill-rule: evenodd;
  d: path("M13.307 10.538c-.72-.067-1.182.214-1.294.317a.473.473 0 1 1-.64-.695c.306-.283 1.032-.656 2.022-.563a.473.473 0 1 1-.088.941");
}

.npzd0rb6d {
  stop-color: var(--svg-color--ff1a66, #FF1A66);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o4j1rvu5g {
  stop-color: var(--svg-color--3778d0, #3778D0);
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od5poibgd {
  d: path("M23.128 23.95a.81.81 0 0 1 .816-.802h3.054c.745 0 1.349.588 1.349 1.315v3.514c0 .605-.503 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.314.187-.59.458-.72a.8.8 0 0 1-.457-.72a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.721c0-.314.186-.589.457-.72a.8.8 0 0 1-.457-.72");
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.oinrtsbml {
  stop-color: var(--svg-color--2a85ce, #2A85CE);
  stop-opacity: 0;
}

.omgy1jbfi {
  stop-color: var(--svg-color--cf731b, #CF731B);
}

.ooudlucgc {
  d: path("m19.912 6.262l.43.214c.751.373 1.18 1.227 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.533c.035-.504.069-1.317.082-1.445c.043-.434-.025-.562-.422-.957c-.215-.213-.376-.534-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.323.495-.323.762c.014.156.035 1.052.06 1.426a.634.634 0 0 1-.596-.533l-.59-3.042c-.108-.855.321-1.709 1.073-2.082c1.015-.445 1.385-1.12 2.201-1.816c.591-.533 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.805-.267 1.718-.053 2.363.534l.805.8c.215.268.483.428.805.588");
}

.oqz6wfbzx {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.089 15.879c-.508 0-.985-.12-1.387-.329c-.137-.07-.284.085-.198.21c.335.507.92.846 1.585.846s1.25-.339 1.584-.847c.087-.13-.06-.279-.198-.209c-.401.21-.873.329-1.386.329Z");
}

.otn9tqb3c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.206 11.775c.064.085-.07.188-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p3-t9eb_f {
  d: path("m14.706 12.46l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.378-.646-.378-.765 0");
}

.p354_vbhd {
  stop-color: var(--svg-color--f29719, #F29719);
}

.p7feigaop {
  d: path("M15.118 16.876c-1.16 0-2.487.208-3.567.58l1.29 6.873c.72.325 1.497.434 2.317.434c.77 0 1.51-.074 2.19-.352l1.313-6.955c-1.05-.383-2.384-.58-3.544-.58");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pig8d1kob {
  cx: 19.859px;
  cy: 12.746px;
  r: 0.996px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po5k0_b-j {
  cx: 10.336px;
  cy: 12.746px;
  r: 0.996px;
}

.pp291w7ri {
  d: path("M9.984 12.132a30 30 0 0 1-.058-1.44c0-.266.107-.587.322-.747l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.053.429.267.429.534v.854c0 .32.16.64.376.854c.502.352.47.546.43.961c-.014.129-.055 1.196-.09 1.441l-.266 3.963c-.16 1.77-1.553 3.005-3.214 3.005h-3.213c-1.714 0-3.053-1.234-3.213-3.006z");
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.pzho1txaw {
  stop-color: var(--svg-color--ee9829, #EE9829);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q2sj4_bau {
  stop-color: var(--svg-color--ff165e, #FF165E);
  stop-opacity: 0;
}

.q5z4iwf2u {
  stop-color: var(--svg-color--3466b9, #3466B9);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qebm4hycr {
  stop-color: var(--svg-color--d58628, #D58628);
  stop-opacity: 0;
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qrv_44bpu {
  stop-color: var(--svg-color--2987cc, #2987CC);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-w7u-p-k {
  stop-color: var(--svg-color--ee9829, #EE9829);
  stop-opacity: 0;
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r1mb9pb8s {
  stop-color: var(--svg-color--e28369, #E28369);
}

.r7o4--bwd {
  fill: var(--svg-color--000, #000);
  d: path("M16.76 12.479a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.235");
}

.rdti6hbah {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.694 11.314c-.654 0-1.206.45-1.357 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.373-1.128");
}

.rfjfa1bja {
  d: path("M24.313 17.076h-5.58l-2.274 11.997h3.149l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.rfqu9yc3v {
  stop-color: var(--svg-color--f5a32b, #F5A32B);
}

.rg_zdtz3i {
  d: path("M17.206 11.775c.064.085-.07.188-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rks-1vyeu {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.089 15.879c-.508 0-.985-.12-1.387-.329c-.137-.07-.284.085-.198.21c.335.507.92.846 1.585.846s1.25-.339 1.584-.847c.087-.13-.06-.279-.198-.209c-.401.21-.873.329-1.386.329");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s434a46or {
  stop-color: var(--svg-color--3a90be, #3A90BE);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sbrbvfbik {
  stop-color: var(--svg-color--cf731b, #CF731B);
  stop-opacity: 0;
}

.sid-44bbw {
  d: path("M12.9 11.586a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .033-.235a.9.9 0 0 0-.898-.893");
}

.spqd6sdrt {
  d: path("M7.078 29.063v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.t0h--bk_d {
  stop-color: var(--svg-color--f0972b, #F0972B);
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t7ud1ab5b {
  stop-color: var(--svg-color--3073cd, #3073CD);
  stop-opacity: 0;
}

.t8-h6jsbg {
  fill: var(--svg-color--000, #000);
  d: path("M13.412 12.479a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.235");
}

.tffk3lifv {
  stop-color: var(--svg-color--3ca6cf, #3CA6CF);
}

.tmbtljdgb {
  stop-color: var(--svg-color--2e7fd1, #2E7FD1);
  stop-opacity: 0;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u7id6gble {
  stop-color: var(--svg-color--ffe945, #FFE945);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vm-pj7b0c {
  stop-color: var(--svg-color--288acb, #288ACB);
  stop-opacity: 0;
}

.votimdvat {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.485 10.397c-.21-.193-.803-.52-1.659-.44");
}

.vqqyf1ezs {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 24.323v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wukxw4q3o {
  cx: 15.149px;
  cy: 18.323px;
  r: 2.406px;
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x65qbiboo {
  d: path("M18.067 12.361a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xcnvxobld {
  stop-color: var(--svg-color--f5a511, #F5A511);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.y0shchp6a {
  d: path("M25.736 22.19a.487.487 0 1 0 0-.974a.487.487 0 0 0 0 .975");
}

.ydn9dmb6d {
  stop-color: var(--svg-color--ffe945, #FFE945);
  stop-opacity: 0;
}

.ygbzbr4js {
  fill-rule: evenodd;
  d: path("M16.87 10.538c.72-.067 1.183.214 1.295.317a.473.473 0 1 0 .64-.695c-.306-.283-1.032-.656-2.023-.563a.473.473 0 1 0 .088.941");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yp-hr1bpr {
  stop-color: var(--svg-color--3778d0, #3778D0);
  stop-opacity: 0;
}

.yvhebp9nr {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.813 12.624l-.821 1.7c-.102.35.142.7.489.7h.738c.346 0 .59-.355.488-.7l-.499-1.7c-.107-.377-.283-.377-.395 0");
}

.z5k3hykxe {
  d: path("M23.128 29.063v-7.268l-3.52 7.268z");
}

.za8u66qzh {
  d: path("M7.078 29.063h3.87l-3.87-7.596z");
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
