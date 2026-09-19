<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irzI4mc)" class="y-o5p6bpn"/><path fill="url(#iir4fsd)" class="y-o5p6bpn"/><path fill="url(#i5ZoAHd)" class="y-o5p6bpn"/><path fill="url(#igssg6d)" class="y-o5p6bpn"/><path fill="url(#ifEMKFe)" class="ggzlihlor"/><path fill="url(#ihQQXyD)" class="ggzlihlor"/><path class="lacol7bps"/><path fill="url(#iYij1de)" class="js0e0qbag"/><path fill="url(#idFzlNx)" class="js0e0qbag"/><path class="oym0skb9x"/><path fill="url(#iEImbSZ)" class="tlyjusqzz"/><path fill="url(#inQ4rld)" class="tlyjusqzz"/><path fill="url(#i1EE6ye)" class="ki99hylgc"/><path fill="url(#iOmA89d)" class="m1hk54bnq"/><path fill="url(#iq1BDyX)" class="m1hk54bnq"/><path fill="url(#iOmA89d)" class="m1hk54bnq"/><path fill="url(#iq1BDyX)" class="m1hk54bnq"/><g filter="url(#ipyNLne)"><path fill="url(#iUW0hkd)" class="fp7c4zu0r"/></g><path fill="url(#i1GGqGc)" class="fp7c4zu0r"/><path fill="url(#iKc1mlb)" class="fp7c4zu0r"/><path fill="url(#inXGAUd)" class="fp7c4zu0r"/><path fill="url(#iPApzmd)" class="fp7c4zu0r"/><path fill="url(#iaHk3Xc)" class="fp7c4zu0r"/><path fill="url(#iPymL2d)" class="fp7c4zu0r"/><path fill="url(#iNiWnce)" class="fp7c4zu0r"/><path fill="url(#i8SSfvb)" class="fp7c4zu0r"/><g filter="url(#igM5qGe)"><path class="jlq_p2brb"/></g><g filter="url(#ixx5Wzd)"><path fill="url(#iqyJr6E)" class="pht10wb5i"/><path fill="url(#iezrVAe)" class="pht10wb5i"/><path fill="url(#iQdHbNc)" class="pht10wb5i"/><path fill="url(#iKHjcQb)" class="pht10wb5i"/></g><g filter="url(#ipE976c)"><path stroke="url(#i7xCW4b)" class="bq2mlybyd"/></g><path fill="url(#ihFHi7d)" class="kfre_ubbh"/><g filter="url(#ivNd5re)"><path fill="url(#iF2UOQb)" class="l76v0-9wk"/><path fill="url(#iYpoAPb)" class="l76v0-9wk"/><path fill="url(#ibCnj6W)" class="l76v0-9wk"/><path fill="url(#infRffb)" class="l76v0-9wk"/><path fill="url(#iM1Ru0c)" class="l76v0-9wk"/></g><g filter="url(#iOnxgne)"><path class="hxpts4zco"/></g><g filter="url(#itEsVbd)"><path class="pd3a0bc6s"/></g><g filter="url(#iiYp8Ac)"><path fill="url(#it8Pmle)" class="m3u3iglxu"/><path fill="url(#i9KOgkX)" class="m3u3iglxu"/></g><g filter="url(#ibAfcHT)"><path fill="url(#iEbuVme)" class="vh9zwtwqa"/><path fill="url(#iesSWFb)" class="vh9zwtwqa"/><path fill="url(#i6DbjxK)" class="vh9zwtwqa"/><path fill="url(#iAt7w4d)" class="vh9zwtwqa"/><path fill="url(#ilu3gHb)" class="vh9zwtwqa"/><path fill="url(#iGPKycd)" class="vh9zwtwqa"/></g><path class="fbvd9vbmq"/><path fill="url(#inKIvcd)" class="ycbt89bxo"/><path class="zm0bsjbqb"/><g filter="url(#iaOiiwd)"><path class="dzmi_b3_v"/><path fill="url(#i8YB7kd)" class="wegh9_3yk"/></g><g filter="url(#iExJ1tb)"><path fill="url(#iLTcwac)" class="qt7350b0s"/></g><path class="ux60bccjo"/><path fill="url(#idNZnrd)" class="fvp_1nnek"/><path class="una4vtb0y"/><g filter="url(#i7oCocd)"><path fill="url(#iBiCwEd)" class="mhjilwb8a"/></g><g filter="url(#iOEfose)"><ellipse transform="rotate(-27.914 12.036 13)" class="ir0b_t7nn"/><ellipse fill="url(#iGvDzjc)" transform="rotate(-27.914 12.036 13)" class="u0d-dhxgi"/></g><path fill="url(#ii7Xxkl)" class="klnizqwjo"/><path fill="url(#izfTeMe)" class="klnizqwjo"/><path fill="url(#irNeZ0c)" class="klnizqwjo"/><path fill="url(#idbLXac)" class="c9tl7rbst"/><path fill="url(#ih75Hpc)" class="c9tl7rbst"/><g filter="url(#i7r4b9c)"><path class="gva7ylb9d"/></g><g filter="url(#i19gM6c)"><path class="qsxul6bnr"/></g><g filter="url(#iCWxSMm)"><path class="y4kcid6mo"/></g><g filter="url(#iaLv5Zv)"><path class="q8unxxbmu"/></g><g filter="url(#irl7Hjb)"><path class="iqa86_72l"/></g><g filter="url(#ivvonEh)"><path class="mxbyf3u7w"/></g><g filter="url(#iedIbJP)"><path class="uxibt3hvl"/></g><g filter="url(#iigJHuc)"><path fill="url(#iKTLkIc)" class="hnx58gblt"/><path fill="url(#iTfypac)" class="hnx58gblt"/><path fill="url(#ihKmkCV)" class="hnx58gblt"/></g><path fill="url(#i8nXvAe)" class="c52ehsdcd"/><path fill="url(#i7cS8ne)" class="c52ehsdcd"/><path fill="url(#ink7s8w)" class="w_w_ohb4f"/><path fill="url(#ia0ETfV)" class="w_w_ohb4f"/><g filter="url(#iEQDqhd)"><circle fill="url(#ia0p4Xc)" class="zwzxoibnp"/><circle fill="url(#icsnRpb)" class="zwzxoibnp"/><circle fill="url(#iuCkp6d)" class="zwzxoibnp"/></g><g filter="url(#iIXd5if)"><path fill="url(#iC6U2Fb)" clip-rule="evenodd" class="atd0tsbal"/></g><path fill="url(#i95mwxj)" clip-rule="evenodd" class="atd0tsbal"/><g filter="url(#iVkpeAe)"><path fill="url(#i2maeop)" clip-rule="evenodd" class="e5kfpbo2f"/></g><g filter="url(#iLM9Hqe)"><circle stroke="url(#iXwbpeC)" class="bjo5_sb_h"/></g><g filter="url(#iVlS1Jc)"><circle stroke="url(#iZWkerc)" class="gzb8gdbwo"/></g><g filter="url(#iYg2Rxe)"><circle stroke="url(#iGNMIfd)" class="cyoymob6p"/></g><g filter="url(#iO2jfrb)"><circle stroke="url(#iWgywee)" class="v_d8_hqvn"/></g><defs><radialGradient id="irzI4mc" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.184 14.266)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="qwzbgbcpc"/><stop offset="1" class="yrgygrb-x"/></radialGradient><radialGradient id="iir4fsd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90627 -10.81244 15.55864 -11.37678 17.382 30.61)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="znj-7lelt"/><stop offset="1" class="w53rld2zh"/></radialGradient><radialGradient id="i5ZoAHd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.23463 3.91089 -1.18367 -3.09762 12.577 19.224)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="u-ogyggtr"/><stop offset="1" class="tr4934b7k"/></radialGradient><radialGradient id="igssg6d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.46 30.105)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="pujgjpbud"/><stop offset="1" class="dstba7uva"/></radialGradient><radialGradient id="ifEMKFe" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.49 29.326)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="teikdvrbz"/><stop offset="1" class="v5czltblq"/></radialGradient><radialGradient id="ihQQXyD" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.49 30.105)" gradientUnits="userSpaceOnUse"><stop class="gbso5obkm"/><stop offset="1" class="x7u0pvbam"/></radialGradient><radialGradient id="iYij1de" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.224 30.105)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="ajnorac8k"/><stop offset="1" class="o0jyspbad"/></radialGradient><radialGradient id="idFzlNx" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -16.6933 7.224 30.105)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="w5_5qkbkk"/><stop offset="1" class="h6pm4_bbg"/></radialGradient><radialGradient id="iEImbSZ" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.614 19.74)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="jrdmuq-mr"/><stop offset="1" class="l_wlfwdgx"/></radialGradient><radialGradient id="inQ4rld" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14587 1.92234 -.8326 -.92942 16.683 20.974)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="d46pibtsi"/><stop offset="1" class="xchzl1brv"/></radialGradient><radialGradient id="i1EE6ye" cx="0" cy="0" r="1" gradientTransform="matrix(-.62118 3.60309 -4.28019 -.7379 20.102 14.822)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iOmA89d" cx="0" cy="0" r="1" gradientTransform="matrix(1.2986 2.73387 -1.24267 .59028 8.88 15.11)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iq1BDyX" cx="0" cy="0" r="1" gradientTransform="matrix(.18278 1.2168 -1.0674 .16034 9.698 14.902)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iUW0hkd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.32935 0 0 -9.42757 17.4 14.031)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iKc1mlb" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 12.78126 -15.25095 .0373 15.058 8.07)" gradientUnits="userSpaceOnUse"><stop offset=".729" class="x9cttbb4e"/><stop offset="1" class="e-vdye8jq"/></radialGradient><radialGradient id="inXGAUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36694 1.69159 0 17.032 12.889)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iPApzmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0592 -1.12482 1.22407 -.06441 12.255 12.75)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iaHk3Xc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23024 0 0 6.25306 9.561 14.423)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iPymL2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.66553 -3.7249 .8437 .60374 8.57 10.972)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iNiWnce" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 14.388 3.398)scale(10.7278 11.817)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="i8SSfvb" cx="0" cy="0" r="1" gradientTransform="matrix(2.08457 .73475 -.44077 1.25052 16.533 8.546)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i7xCW4b" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 21.53 -2.733)scale(.72388 2.10652)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="ihFHi7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73473 2.95601 0 14.537 17.64)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iYpoAPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.70318 6.56131 0 9.206 12.418)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ibCnj6W" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.70318 6.56131 0 19.492 12.418)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="infRffb" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 9.916 1.285)scale(3.54779 1.88943)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iM1Ru0c" cx="0" cy="0" r="1" gradientTransform="matrix(.92268 1.50363 -3.4817 2.1365 13.614 4.397)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="it8Pmle" cx="0" cy="0" r="1" gradientTransform="matrix(-3.88082 1.40024 -.38972 -1.08012 14.796 5.867)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i9KOgkX" cx="0" cy="0" r="1" gradientTransform="matrix(3.28069 -5.19435 5.7548 3.63466 9 10.719)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iEbuVme" cx="0" cy="0" r="1" gradientTransform="matrix(3.45152 .81637 -.45657 1.93033 18.228 7.05)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iesSWFb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.19032 -3.7756 2.10563 -1.22153 19.766 11.744)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="i6DbjxK" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 12.822 .273)scale(2.61084 1.87003)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iAt7w4d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.89158 1.17355 -1.26866 -5.288 19.424 6.931)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="ilu3gHb" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 6.511 10.082)scale(.40906 1.87015)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iGPKycd" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 7.234 8.409)scale(4.33401 11.1762)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="inKIvcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82707 -1.31555 0 16.762 13.097)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8YB7kd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23642 -.30466 .41945 -.3255 16.53 13.183)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idNZnrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82711 -1.31562 0 12.313 13.097)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iGvDzjc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.567 .743)scale(.50374 .60551)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izfTeMe" cx="0" cy="0" r="1" gradientTransform="matrix(.64073 2.28683 -2.18182 .61131 19.244 13.111)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="irNeZ0c" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 23.24 -12.445)scale(1.36365 1.14301)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="ih75Hpc" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.264 6.537)scale(1.7257 1.69652)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iTfypac" cx="0" cy="0" r="1" gradientTransform="matrix(-.31067 .66453 -.28734 -.13433 23.331 5.419)" gradientUnits="userSpaceOnUse"><stop offset=".012" class="ojbdj8bth"/><stop offset="1" class="mbespsb6a"/></radialGradient><radialGradient id="ihKmkCV" cx="0" cy="0" r="1" gradientTransform="matrix(4.5625 .72639 -.36152 2.27072 17.277 6.82)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="e518x9bmh"/><stop offset="1" class="d8kb-3bwg"/></radialGradient><radialGradient id="ia0p4Xc" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.652 8.055)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="icsnRpb" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.68 8.095)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="iuCkp6d" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.455 7.657)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="iC6U2Fb" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.483 10.845)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="i2maeop" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.63 9.021)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="ipyNLne" width="11.169" height="12.781" x="9.375" y="7.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_33"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_33" result="effect2_innerShadow_4002_33"/></filter><filter id="igM5qGe" width="3.788" height="4.878" x="12.369" y="12.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".5"/></filter><filter id="ixx5Wzd" width="2.114" height="3.156" x="13.48" y="12.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".05"/></filter><filter id="ipE976c" width="3.781" height="1.594" x="12.647" y="16.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".05"/></filter><filter id="ivNd5re" width="13.123" height="8.509" x="7.976" y="4.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_33"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_33" result="effect2_innerShadow_4002_33"/></filter><filter id="iOnxgne" width="2.382" height="1.21" x="16.157" y="10.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_33"/></filter><filter id="itEsVbd" width="2.382" height="1.195" x="10.799" y="10.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_33"/></filter><filter id="iiYp8Ac" width="6.702" height="6.098" x="8.343" y="5.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".125"/></filter><filter id="ibAfcHT" width="6.481" height="5.843" x="14.374" y="6.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".125"/></filter><filter id="iaOiiwd" width=".798" height=".706" x="16.015" y="12.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".05"/></filter><filter id="iExJ1tb" width=".901" height=".923" x="16.873" y="12.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".1"/></filter><filter id="i7oCocd" width=".998" height="1.053" x="12.344" y="12.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".1"/></filter><filter id="iOEfose" width=".927" height=".714" x="11.573" y="12.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".05"/></filter><filter id="i7r4b9c" width="1.345" height="2.416" x="8.392" y="12.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".125"/></filter><filter id="i19gM6c" width="1.465" height="2.44" x="19.345" y="12.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".125"/></filter><filter id="iCWxSMm" width="2.437" height="1.168" x="10.723" y="10.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".125"/></filter><filter id="iaLv5Zv" width="2.437" height="1.168" x="16.105" y="10.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".125"/></filter><filter id="irl7Hjb" width="5.442" height="3.076" x="15.587" y="6.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".375"/></filter><filter id="ivvonEh" width="5.314" height="3.025" x="15.437" y="6.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".375"/></filter><filter id="iedIbJP" width="5.314" height="3.025" x="15.437" y="6.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".375"/></filter><filter id="iigJHuc" width="9.255" height="4.594" x="14.6" y="5.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.701961 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_33"/></filter><filter id="iEQDqhd" width=".726" height=".726" x="23.512" y="7.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_33"/></filter><filter id="iIXd5if" width="3.834" height="4.387" x="21.054" y="8.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_33"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_33" result="effect2_innerShadow_4002_33"/></filter><filter id="iVkpeAe" width="4.283" height="3.734" x="24.252" y="6.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_33"/></filter><filter id="iLM9Hqe" width="3.843" height="3.843" x="24.723" y="6.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".1"/></filter><filter id="iVlS1Jc" width="2.734" height="2.734" x="25.278" y="7.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".1"/></filter><filter id="iYg2Rxe" width="2.734" height="2.734" x="21.629" y="9.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".1"/></filter><filter id="iO2jfrb" width="3.805" height="3.805" x="21.093" y="8.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_33" stdDeviation=".1"/></filter><linearGradient id="i1GGqGc" x1="19.794" x2="15.357" y1="15.749" y2="15.749" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iqyJr6E" x1="14.537" x2="15.409" y1="14.876" y2="14.876" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iezrVAe" x1="13.444" x2="14.539" y1="14.717" y2="14.778" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iQdHbNc" x1="14.537" x2="14.537" y1="15.283" y2="16.151" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iKHjcQb" x1="14.537" x2="14.537" y1="12.991" y2="13.419" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iF2UOQb" x1="20.005" x2="9.684" y1="8.259" y2="8.259" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iLTcwac" x1="17.555" x2="17.235" y1="13.152" y2="13.349" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBiCwEd" x1="13.071" x2="12.751" y1="13.152" y2="13.349" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ii7Xxkl" x1="21.098" x2="19.868" y1="13.18" y2="15.398" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="idbLXac" x1="8.574" x2="10.06" y1="13.897" y2="13.767" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="iKTLkIc" x1="23.605" x2="17.521" y1="5.708" y2="9.396" gradientUnits="userSpaceOnUse"><stop class="fbwe79-ni"/><stop offset="1" class="u749y_xhl"/></linearGradient><linearGradient id="i8nXvAe" x1="25.035" x2="23.843" y1="5.797" y2="5.453" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="i7cS8ne" x1="23.887" x2="23.961" y1="7.291" y2="7.001" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="ink7s8w" x1="22.973" x2="23.238" y1="8.146" y2="6.849" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="ia0ETfV" x1="24.384" x2="24.186" y1="8.228" y2="8.172" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="i95mwxj" x1="23.723" x2="23.664" y1="8.318" y2="8.545" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="iXwbpeC" x1="24.973" x2="28.163" y1="8.92" y2="7.448" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="iZWkerc" x1="25.528" x2="27.66" y1="8.798" y2="7.814" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="iGNMIfd" x1="21.879" x2="24.011" y1="10.812" y2="9.828" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="iWgywee" x1="24.648" x2="22.996" y1="10.025" y2="10.566" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-haircut-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.ajnorac8k {
  stop-color: var(--svg-color--e36750, #E36750);
  stop-opacity: 0;
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.atd0tsbal {
  fill-rule: evenodd;
  d: path("M23.099 8.19a.1.1 0 0 0-.124.069l-.104.357a.22.22 0 0 1-.174.148a1.842 1.842 0 1 0 1.514.433a.21.21 0 0 1-.068-.22l.101-.348a.1.1 0 0 0-.068-.124zm.74 2.392a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.bjo5_sb_h {
  cx: 26.645px;
  cy: 8.552px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.bq2mlybyd {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.16 16.583h-.001a.23.23 0 0 0-.275.047a.215.215 0 0 0-.023.274c.355.538.973.896 1.676.896c.704 0 1.322-.358 1.677-.896a.22.22 0 0 0-.024-.276a.23.23 0 0 0-.275-.046a3 3 0 0 1-1.378.327c-.506 0-.98-.119-1.378-.326Z");
}

.c52ehsdcd {
  d: path("M24.428 3.392L23.04 8.223l1.187.345l1.071-3.73a1.15 1.15 0 0 0-.784-1.421z");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.c9tl7rbst {
  d: path("M9.385 12.136a1.64 1.64 0 0 0 .141 3.262a80 80 0 0 1-.141-3.262");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cyoymob6p {
  cx: 22.996px;
  cy: 10.566px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d46pibtsi {
  stop-color: var(--svg-color--f7a48a, #F7A48A);
}

.d8kb-3bwg {
  stop-color: var(--svg-color--fffbc0, #FFFBC0);
  stop-opacity: 0;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dstba7uva {
  stop-color: var(--svg-color--ff7543, #FF7543);
  stop-opacity: 0;
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.dzmi_b3_v {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.697 12.803c.065.087-.071.193-.225.308s-.268.196-.333.11s.007-.251.161-.366s.332-.139.397-.052");
}

.e-vdye8jq {
  stop-color: var(--svg-color--d06a6d, #D06A6D);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e518x9bmh {
  stop-color: var(--svg-color--fffbc0, #FFFBC0);
}

.e5kfpbo2f {
  fill-rule: evenodd;
  d: path("M24.543 7.404a.1.1 0 0 1 .123-.071l.36.095a.22.22 0 0 0 .216-.072a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.172l-.351-.093a.1.1 0 0 1-.07-.123zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.444");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fbvd9vbmq {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.975 12.334c.665 0 1.228.459 1.38 1.08a.28.28 0 0 1-.272.347h-2.275a.235.235 0 0 1-.231-.277a1.425 1.425 0 0 1 1.397-1.15");
}

.fbwe79-ni {
  stop-color: var(--svg-color--e4bb90, #E4BB90);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.fp7c4zu0r {
  d: path("M9.618 16.85a3.99 3.99 0 0 0 3.961 3.472h1.924a3.99 3.99 0 0 0 3.96-3.472c.121-1.92.242-3.833.331-5.752a1.48 1.48 0 0 0-1.405-1.46H16.96a2.47 2.47 0 0 1-2.254-1.471a.68.68 0 0 0-.628-.427h-1.297c-1.882 0-3.407 1.542-3.407 3.445c0 1.897.119 3.763.243 5.665");
}

.ft5dv1b6b {
  fill: none;
}

.fvp_1nnek {
  d: path("M12.31 12.61a.91.91 0 0 0-.876 1.15h1.758a1 1 0 0 0 .033-.24a.916.916 0 0 0-.914-.91");
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gbso5obkm {
  stop-color: var(--svg-color--ff5130, #FF5130);
}

.ggzlihlor {
  d: path("M21.49 30.105h3.71v-.464c0-3.217-1.437-6.103-3.71-8.066z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gva7ylb9d {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M9.402 12.81a.974.974 0 0 0 .085 1.916a80 80 0 0 1-.085-1.916");
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.gzb8gdbwo {
  cx: 26.645px;
  cy: 8.552px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h6pm4_bbg {
  stop-color: var(--svg-color--ff6640, #FF6640);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hnx58gblt {
  d: path("M18.542 9.663c3.492-.377 4.732-2.142 4.995-3.103c.055-.17.121-.602 0-.957c-.098-.285-.437-.348-.594.066c-.367.891-1.172 1.305-2.039 1.454c-.867.148-1.656.226-3.062-.399c-1.004-.446-1.578-.61-2.18-.406s-1.362.869-.94 1.877c.376.898 1.219 1.75 3.82 1.468");
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hxpts4zco {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M18.343 10.994c-.18-.156-.387-.32-.701-.42c-.31-.097-.699-.124-1.236-.058a.283.283 0 0 0 .068.561c.49-.06.791-.028.998.037c.202.063.339.166.5.306a.283.283 0 0 0 .37-.426");
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iqa86_72l {
  fill: var(--svg-color--725050, #725050);
  d: path("M19.021 8.31h-2.178a.505.505 0 1 1 .08-1.007c.566.09 1.316.216 1.819.34c1.136.282 1.45.835 1.538 1.23a1.59 1.59 0 0 0-1.259-.564");
}

.ir0b_t7nn {
  cx: 12.036px;
  cy: 13px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.397px;
  ry: 0.201px;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jlq_p2brb {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m14.098 13.689l-.706 1.687c-.103.386.145.771.497.771h.749c.351 0 .599-.391.496-.77l-.507-1.875c-.108-.415-.415-.229-.53.186");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jrdmuq-mr {
  stop-color: var(--svg-color--cc6e65, #CC6E65);
}

.js0e0qbag {
  d: path("M7.224 21.575c-2.273 1.963-3.71 4.849-3.71 8.066v.464h3.71z");
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.kfre_ubbh {
  d: path("M14.537 16.984a3.06 3.06 0 0 1-1.412-.335c-.14-.07-.29.086-.202.213a1.93 1.93 0 0 0 1.614.863a1.93 1.93 0 0 0 1.614-.863c.088-.132-.062-.284-.202-.213c-.408.213-.89.335-1.412.335");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.ki99hylgc {
  d: path("M19.493 15.305c.341-.01.661-.127.922-.314v.949c0 .91-.543 1.721-1.367 2.058a4.2 4.2 0 0 0 .352-1.203z");
}

.klnizqwjo {
  d: path("M19.554 15.398q.103-1.627.189-3.253a1.64 1.64 0 0 1-.189 3.253");
}

.l_wlfwdgx {
  stop-color: var(--svg-color--cc6e65, #CC6E65);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l76v0-9wk {
  d: path("M19.486 7.26c.524.18.995.546 1.292 1.071a2.42 2.42 0 0 1-.108 2.575a1.6 1.6 0 0 0-.276.892v1.21a1.8 1.8 0 0 0-.68-.273l.08-1.637a1.48 1.48 0 0 0-1.406-1.46h-1.427a2.47 2.47 0 0 1-2.255-1.471a.68.68 0 0 0-.627-.427h-1.297c-1.882 0-3.407 1.542-3.407 3.445l.032 1.567c-.26.038-.53.125-.735.27v-1.224a1.6 1.6 0 0 0-.275-.892a2.44 2.44 0 0 1-.146-2.493a2.4 2.4 0 0 1 1.324-1.148a2.73 2.73 0 0 0 1.412-1.132a2.37 2.37 0 0 1 2.946-.93c.39.17.828.17 1.217 0a2.37 2.37 0 0 1 2.957.963c.314.52.806.896 1.379 1.093");
}

.lacol7bps {
  fill: var(--svg-color--ff4f19, #FF4F19);
  d: path("M7.224 21.575c-2.273 1.963-3.71 4.849-3.71 8.066v.464h3.71z");
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m1hk54bnq {
  d: path("M9.581 15.305a1.67 1.67 0 0 1-.922-.314v.949c0 .91.543 1.721 1.367 2.058a4.2 4.2 0 0 1-.352-1.203z");
}

.m3u3iglxu {
  d: path("M14.774 8.307a3 3 0 0 1-.067-.14a.68.68 0 0 0-.628-.426h-1.297c-1.882 0-3.406 1.541-3.406 3.444v.28c-.347-.263-.783-.82-.783-1.72c0-1.092.797-1.645 1.305-1.997c.144-.1.264-.183.337-.258l.102-.107c.356-.378.991-1.051 2.1-1.346a5.6 5.6 0 0 1 1.552-.167c.473.012.806.42.806.893v1.53z");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbespsb6a {
  stop-color: var(--svg-color--f9d8a8, #F9D8A8);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhjilwb8a {
  d: path("M13.142 13.414c0-.294-.24-.49-.304-.55l-.294.285l.181.368z");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mxbyf3u7w {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M18.784 8.24h-2.108a.489.489 0 1 1 .078-.973c.547.087 1.273.208 1.76.329c1.099.272 1.402.808 1.487 1.19a1.53 1.53 0 0 0-1.217-.546");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o0jyspbad {
  stop-color: var(--svg-color--e36750, #E36750);
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ojbdj8bth {
  stop-color: var(--svg-color--f9d8a8, #F9D8A8);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oym0skb9x {
  fill: var(--svg-color--e49382, #E49382);
  d: path("M12.545 18.724h3.984v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pd3a0bc6s {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M11.06 10.883a2.83 2.83 0 0 1 1.773-.366a.283.283 0 0 1-.069.56a2.26 2.26 0 0 0-1.414.29q-.052.032-.076.05l-.017.012l-.003.002a.283.283 0 0 1-.346-.447z");
}

.pht10wb5i {
  d: path("m14.147 13.303l-.541 1.874c-.11.385.154.77.53.77h.802c.376 0 .641-.39.53-.77l-.541-1.874c-.116-.416-.658-.416-.78 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pujgjpbud {
  stop-color: var(--svg-color--ff7543, #FF7543);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q8unxxbmu {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.167 11.12c-.262-.187-.915-.518-1.687-.388");
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qsxul6bnr {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M19.595 14.735q.06-.97.113-1.94a.974.974 0 0 1-.113 1.94");
}

.qt7350b0s {
  d: path("M17.574 13.4a.86.86 0 0 0-.236-.47l-.265.29l.12.233z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwzbgbcpc {
  stop-color: var(--svg-color--ff702c, #FF702C);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.teikdvrbz {
  stop-color: var(--svg-color--ff7646, #FF7646);
}

.tlyjusqzz {
  d: path("M12.545 18.724h3.984v1.383c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tr4934b7k {
  stop-color: var(--svg-color--ff5915, #FF5915);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u-ogyggtr {
  stop-color: var(--svg-color--e73f04, #E73F04);
}

.u0d-dhxgi {
  cx: 12.036px;
  cy: 13px;
  rx: 0.397px;
  ry: 0.201px;
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u749y_xhl {
  stop-color: var(--svg-color--ffdeb4, #FFDEB4);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.una4vtb0y {
  fill: var(--svg-color--000, #000);
  d: path("M12.832 13.52a.52.52 0 0 0-.521-.52a.52.52 0 0 0-.464.76h.923a.5.5 0 0 0 .062-.24");
}

.ux60bccjo {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.1 12.334c-.666 0-1.229.459-1.381 1.08a.28.28 0 0 0 .273.347h2.274c.145 0 .26-.133.232-.278a1.43 1.43 0 0 0-1.398-1.15");
}

.uxibt3hvl {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M18.784 8.303h-2.108a.489.489 0 1 1 .078-.974c.547.087 1.273.209 1.76.33c1.099.272 1.402.807 1.487 1.189a1.53 1.53 0 0 0-1.217-.545");
}

.v_d8_hqvn {
  cx: 22.996px;
  cy: 10.566px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v5czltblq {
  stop-color: var(--svg-color--ff6635, #FF6635);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vh9zwtwqa {
  d: path("m19.85 11.744l-.029-.643c-.01-.779-.654-1.42-1.433-1.453h-1.427a2.47 2.47 0 0 1-2.165-1.285s-.065-.15-.13-.408c-.249-.972.677-1.713 1.662-1.524c1 .191 2.147.527 2.992 1.078c1.778 1.16 1.467 3.25.53 4.235");
}

.w_w_ohb4f {
  d: path("m19.78 5.97l5.42 1.535l-.338 1.189l-4.313-1.223a1.15 1.15 0 0 1-.793-1.42z");
}

.w5_5qkbkk {
  stop-color: var(--svg-color--ff6640, #FF6640);
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.w53rld2zh {
  stop-color: var(--svg-color--e65d38, #E65D38);
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wegh9_3yk {
  d: path("M16.697 12.803c.065.087-.071.193-.225.308s-.268.196-.333.11s.007-.251.161-.366s.332-.139.397-.052");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x7u0pvbam {
  stop-color: var(--svg-color--ff5130, #FF5130);
  stop-opacity: 0;
}

.x9cttbb4e {
  stop-color: var(--svg-color--c5817f, #C5817F);
  stop-opacity: 0;
}

.xchzl1brv {
  stop-color: var(--svg-color--f7a48a, #F7A48A);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y-o5p6bpn {
  d: path("M3.515 29.641c0-5.915 4.854-10.71 10.842-10.71s10.842 4.795 10.842 10.71v.464H3.515z");
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y4kcid6mo {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.098 11.168c.262-.188.915-.519 1.688-.389");
}

.ycbt89bxo {
  d: path("M16.764 12.611a.91.91 0 0 1 .876 1.15h-1.757a.913.913 0 0 1 .88-1.15");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yrgygrb-x {
  stop-color: var(--svg-color--ff521f, #FF521F);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zm0bsjbqb {
  fill: var(--svg-color--000, #000);
  d: path("M16.242 13.52c0-.289.232-.52.521-.52a.52.52 0 0 1 .464.76h-.922a.47.47 0 0 1-.063-.24");
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znj-7lelt {
  stop-color: var(--svg-color--e65d38, #E65D38);
  stop-opacity: 0;
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zwzxoibnp {
  cx: 23.825px;
  cy: 7.748px;
  r: 0.313px;
}

</style>
