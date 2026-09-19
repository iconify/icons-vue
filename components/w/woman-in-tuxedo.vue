<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#it7GtWd)"><path fill="url(#i4vDijd)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#igNQaDd)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#icgLOHB)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#iTb8fze)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#iYYuixd)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#iPGuGVb)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#i6bQgnd)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#iN7HEAb)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#iYfYwSc)" clip-rule="evenodd" class="l79g3_q8r"/></g><path fill="url(#i2ZH5Me)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#iyIfY3d)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#iS0Gn1e)" clip-rule="evenodd" class="l79g3_q8r"/><path fill="url(#i5i4ZKc)" class="i05iocb4q"/><path fill="url(#i0tbtac)" class="i05iocb4q"/><path fill="url(#iodHtJd)" class="i05iocb4q"/><path fill="url(#ioARCxd)" class="i05iocb4q"/><path fill="url(#iIGTF3A)" class="i05iocb4q"/><path fill="url(#iqDd4Id)" class="y90vs2b5r"/><path fill="url(#ijnIOOd)" class="y90vs2b5r"/><g filter="url(#iM9lNmn)"><path fill="url(#ir5Fksb)" class="l4v_prl5j"/><path fill="url(#iZm2gPe)" class="l4v_prl5j"/></g><path fill="url(#i7upeiA)" class="lz8mhtb-l"/><g filter="url(#iGV2dDd)"><path fill="url(#iSiD7Td)" class="konrsab1i"/><path fill="url(#i4rK4Gc)" class="konrsab1i"/></g><g filter="url(#iwyoEZc)"><path clip-rule="evenodd" class="a4l-32baa"/></g><path fill="url(#iWK2cbc)" class="dl6g9_kqy"/><path fill="url(#i0odcpZ)" class="dl6g9_kqy"/><path fill="url(#ibhq81b)" class="dl6g9_kqy"/><path fill="url(#ixg2elc)" class="dl6g9_kqy"/><path fill="url(#iKUzjhd)" class="b4l0e5n-v"/><path fill="url(#i5flXbc)" class="b4l0e5n-v"/><path fill="url(#ii91pWk)" class="b4l0e5n-v"/><path fill="url(#ieJeZPb)" class="b4l0e5n-v"/><g filter="url(#ir7U2yb)"><path fill="url(#iMSgFGb)" class="fzniv18pp"/></g><g filter="url(#i8ro7BE)"><path fill="url(#irccVNd)" class="udg19xb4u"/></g><path fill="url(#i1n1rhe)" class="udg19xb4u"/><path fill="url(#i2PAgOc)" class="udg19xb4u"/><path fill="url(#iOHBn5b)" class="udg19xb4u"/><g filter="url(#iY5BYvn)"><path class="hbggewb8s"/></g><g filter="url(#ii5Wqib)"><circle class="sdq_xvxgz"/></g><g filter="url(#iuPCp6Z)"><circle class="nw6gm2x_y"/></g><g filter="url(#iheHdwb)"><circle fill="url(#iWRbPEN)" class="af_597hlr"/></g><g filter="url(#i8teead)"><circle fill="url(#ipBqC7g)" class="k24c38bex"/></g><rect fill="url(#i39c9ze)" class="a_1c8ebbm"/><rect fill="url(#i7wFQbd)" class="a_1c8ebbm"/><rect fill="url(#iQiGbgd)" class="a_1c8ebbm"/><rect fill="url(#iQmcwoo)" class="a_1c8ebbm"/><rect fill="url(#irPe1xM)" class="a_1c8ebbm"/><g filter="url(#iKia7Lb)"><path fill="url(#ijMCGab)" class="a_q7bzbvy"/></g><path fill="url(#igJuweL)" class="a_q7bzbvy"/><g filter="url(#iA3cNQb)"><path class="mihtq2baw"/><path fill="url(#ifBU5bc)" class="yxq7o1but"/><path fill="url(#iQSRzhc)" class="yxq7o1but"/><path fill="url(#iOt5rBc)" class="yxq7o1but"/></g><g filter="url(#iMcg93S)"><circle fill="url(#igFTDte)" class="lvxmtuw0d"/><circle fill="url(#ipicOac)" class="lvxmtuw0d"/></g><g filter="url(#izUtQNb)"><path fill="url(#iNo66ad)" class="vakyesjxt"/></g><g filter="url(#izZJ5ze)"><path fill="url(#ijXq7gb)" class="kpkfhbcqt"/></g><g filter="url(#iKm3ASb)"><path class="aogbk3bnc"/><path fill="url(#iL6yYtc)" class="hk1tjhb3n"/></g><g filter="url(#iaqXh2b)"><path class="akyiodbem"/><path fill="url(#ib3hMBb)" class="giy8nbbeg"/></g><g filter="url(#iJ4gKXc)"><path fill="url(#ipL8Jbb)" class="d4s99bb9k"/><path fill="url(#iJy2wxb)" class="d4s99bb9k"/><path fill="url(#i5R4EFe)" class="d4s99bb9k"/><path fill="url(#ivFU8xe)" class="d4s99bb9k"/><path fill="url(#ixszRjh)" class="d4s99bb9k"/><path fill="url(#i9ZcH8e)" class="d4s99bb9k"/><path fill="url(#ip6A66d)" class="d4s99bb9k"/></g><path fill="url(#iUltixb)" class="d4s99bb9k"/><g filter="url(#i0yI1Ib)"><path class="jnu_kjbik"/></g><g filter="url(#is9mxwc)"><path fill="url(#iDL6ARc)" class="fho213byd"/><path fill="url(#iixtkCS)" class="fho213byd"/><path fill="url(#iDhVw6E)" class="fho213byd"/><path fill="url(#iI8hXZd)" class="fho213byd"/></g><g filter="url(#iYXsIhc)"><path stroke="url(#i2lSLOd)" class="a-ode2e4f"/></g><path class="ru-v66bfm"/><g filter="url(#icJYfNd)"><path class="svk_nnbgw"/></g><g filter="url(#iPP1DOc)"><path class="bqbtyru4r"/></g><g filter="url(#icAqaod)"><path class="x8nc6nbsj"/></g><g filter="url(#ix4KqBe)"><path clip-rule="evenodd" class="cuhgmgbdd"/></g><path class="jds94kk2q"/><path fill="url(#i6ufqBb)" class="w30z7opiv"/><path class="mqzxx36cv"/><g filter="url(#ia5vqbb)"><path class="kfijucblt"/><path fill="url(#ir1om2b)" class="la3dubb6m"/></g><g filter="url(#iegINDh)"><path fill="url(#iJVBsne)" class="omy-qpbkf"/></g><path class="p8x14zbnk"/><path fill="url(#ikeHskc)" class="jbyw46wmx"/><path class="bl64p8vem"/><g filter="url(#irTPQLb)"><path fill="url(#iPyx66b)" class="ez7avhbjq"/></g><g filter="url(#ijwZmhd)"><ellipse transform="rotate(-27.914 13.641 9.89)" class="v4f-6nbua"/><ellipse fill="url(#ix05Nhd)" transform="rotate(-27.914 13.641 9.89)" class="nzfx5cglb"/></g><g filter="url(#iwViv6b)"><path class="ldtl0hlos"/></g><g filter="url(#i9CGuxd)"><path class="iy96rk8eb"/></g><g filter="url(#iTv0dJc)"><path fill="url(#inoBJqM)" class="f8v-uiwnz"/><path fill="url(#inJixZd)" class="f8v-uiwnz"/></g><g filter="url(#iMUKwuc)"><path fill="url(#iMJIvPe)" class="tlrlcmzrj"/><path fill="url(#i7XgpSd)" class="tlrlcmzrj"/><path fill="url(#igj6W4d)" class="tlrlcmzrj"/></g><g filter="url(#iuj74Cy)"><path stroke="url(#isGDt9c)" class="tanxzdbxx"/></g><defs><radialGradient id="igNQaDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.523 12.62)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="icgLOHB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.184 10.903)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iTb8fze" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.775 8.467)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iYYuixd" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.567 12.2)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iPGuGVb" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.733 7.168)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="i6bQgnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.604 9.731)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iN7HEAb" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.641 4.064)scale(4.66215 6.69539)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iYfYwSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.39 5.914)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="i2ZH5Me" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5 -14.9257 0 16.095 7.04)" gradientUnits="userSpaceOnUse"><stop offset=".815" class="wueiihd6h"/><stop offset=".976" class="m7lodbb-w"/></radialGradient><radialGradient id="iyIfY3d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.34375 1.09375 -.8497 -2.59764 13.482 16.197)" gradientUnits="userSpaceOnUse"><stop class="xvy570_kd"/><stop offset="1" class="el3lqfbdv"/></radialGradient><radialGradient id="iS0Gn1e" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 .34375 -.24265 2.02942 18.17 16.322)" gradientUnits="userSpaceOnUse"><stop class="shmyaibpb"/><stop offset="1" class="tqwml4b9z"/></radialGradient><radialGradient id="i5i4ZKc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.348)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="i0tbtac" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.762 10.829)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="iodHtJd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.259)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iqDd4Id" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.258 2.626)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="ijnIOOd" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.16)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="ir5Fksb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.416)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="i7upeiA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.572)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iSiD7Td" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.54)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="i4rK4Gc" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.338 13.041)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="i0odcpZ" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.108 8.373)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="ibhq81b" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.68)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="i5flXbc" cx="0" cy="0" r="1" gradientTransform="rotate(16.487 -55.065 68.488)scale(1.44847 6.30545)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="ii91pWk" cx="0" cy="0" r="1" gradientTransform="matrix(-.2731 .4204 -1.76025 -1.14347 17.274 19.21)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="irccVNd" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.074 11.872)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="i1n1rhe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91837 1.77673 -4.30254 -2.22394 13.135 16.346)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="i2PAgOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.92462 -.4885 0 11.747 16.404)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iOHBn5b" cx="0" cy="0" r="1" gradientTransform="rotate(86.901 -5.587 15.967)scale(1.69986 .36274)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iWRbPEN" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.868 16.06)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="ipBqC7g" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.487 14.556)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iQiGbgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87502 1.95908 -1.56576 -1.49857 18.315 16.588)" gradientUnits="userSpaceOnUse"><stop class="wdszzbb5h"/><stop offset="1" class="y20wtkswp"/></radialGradient><radialGradient id="iQmcwoo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.28906 1.23511 0 16.012 18.814)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="t7038hnbe"/><stop offset="1" class="f_qid_ozs"/></radialGradient><radialGradient id="irPe1xM" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 -1.46874 .6453 -1.20823 15.263 18.634)" gradientUnits="userSpaceOnUse"><stop class="yj4a76owm"/><stop offset="1" class="xbn905b4c"/></radialGradient><radialGradient id="ijMCGab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.763)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="igJuweL" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.138)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="iQSRzhc" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.444 6.871)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iOt5rBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.993)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="igFTDte" cx="0" cy="0" r="1" gradientTransform="matrix(-.63803 .63171 -.63171 -.63803 16.337 18.48)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="ipicOac" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.353)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="ijXq7gb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.135 11.022)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iL6yYtc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.568 -52.375)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ib3hMBb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.429 10.583)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="ipL8Jbb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.375 7.102)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iJy2wxb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.995 10.742)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="i5R4EFe" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.914 16.828)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="ivFU8xe" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.833 9.561)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="ixszRjh" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.722 11.701)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i9ZcH8e" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.396 9.626)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="ip6A66d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.177 9.714)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iUltixb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.19 11.114)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iixtkCS" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.88 11.84)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="i6ufqBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.277 9.986)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ir1om2b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.49 .615)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikeHskc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.913 9.986)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ix05Nhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.626 10.204)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="inoBJqM" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.835 4.966)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="inJixZd" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.95 4.21)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iMJIvPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.886 2.457)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="i7XgpSd" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.901 8.876)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="igj6W4d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.245 9.342)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="it7GtWd" width="15.268" height="15.268" x="8.586" y="1.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="iM9lNmn" width="4.081" height="11.683" x="5.07" y="18.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="iGV2dDd" width="5.909" height="14.117" x="12.858" y="15.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="iwyoEZc" width="7.13" height="5.229" x="12.285" y="16.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".3"/></filter><filter id="ir7U2yb" width="7.239" height="14.645" x="9.195" y="15.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".5"/></filter><filter id="i8ro7BE" width="5.917" height="14.259" x="10.326" y="15.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3321" result="effect2_innerShadow_4002_3321"/></filter><filter id="iY5BYvn" width="6.567" height="14.209" x="15.297" y="15.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3321" result="effect2_innerShadow_4002_3321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3321" result="effect3_innerShadow_4002_3321"/></filter><filter id="ii5Wqib" width="2" height="2" x="14.731" y="24.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".25"/></filter><filter id="iuPCp6Z" width="2" height="2" x="14.731" y="21.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".25"/></filter><filter id="iheHdwb" width="1.05" height="1.05" x="15.504" y="25.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="i8teead" width="1.05" height="1.05" x="15.504" y="22.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="iKia7Lb" width="2.465" height="2.95" x="16.029" y="17.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3321" result="effect2_innerShadow_4002_3321"/></filter><filter id="iA3cNQb" width="2.365" height="2.9" x="13.731" y="17.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="iMcg93S" width="1.717" height="1.717" x="15.204" y="17.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="izUtQNb" width="3.318" height="3.218" x="9.8" y="8.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="izZJ5ze" width="3.218" height="3.468" x="19.313" y="8.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="iKm3ASb" width="3.148" height="3.148" x="19.348" y="9.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".25"/></filter><filter id="iaqXh2b" width="2.648" height="2.648" x="10.104" y="9.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".125"/></filter><filter id="iJ4gKXc" width="10.191" height="11.277" x="10.999" y="5.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="i0yI1Ib" width="2.877" height="3.682" x="14.494" y="9.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".25"/></filter><filter id="is9mxwc" width="2.377" height="3.182" x="14.906" y="9.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".125"/></filter><filter id="iYXsIhc" width="3.702" height="1.526" x="14.244" y="12.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".05"/></filter><filter id="icJYfNd" width="3.001" height="1.285" x="17.037" y="9.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="iPP1DOc" width="3.001" height="1.285" x="12.152" y="9.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="icAqaod" width="2.453" height="1.091" x="12.287" y="7.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="ix4KqBe" width="2.453" height="1.091" x="17.704" y="7.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3321"/></filter><filter id="ia5vqbb" width=".786" height=".696" x="17.543" y="9.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".05"/></filter><filter id="iegINDh" width=".891" height=".913" x="18.383" y="9.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".1"/></filter><filter id="irTPQLb" width=".986" height="1.04" x="13.94" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".1"/></filter><filter id="ijwZmhd" width=".912" height=".704" x="13.185" y="9.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".05"/></filter><filter id="iwViv6b" width="2.261" height=".978" x="17.735" y="7.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".1"/></filter><filter id="i9CGuxd" width="2.261" height=".978" x="12.283" y="7.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".1"/></filter><filter id="iTv0dJc" width="4.985" height="5.214" x="9.387" y="3.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".375"/></filter><filter id="iMUKwuc" width="8.914" height="5.78" x="12.778" y="2.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".125"/></filter><filter id="iuj74Cy" width="1.145" height="2.31" x="12.904" y="3.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3321" stdDeviation=".125"/></filter><linearGradient id="i4vDijd" x1="20.788" x2="13.547" y1="3.63" y2="17.073" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="ioARCxd" x1="23.131" x2="22.971" y1="29.939" y2="29.939" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iIGTF3A" x1="8.858" x2="9.061" y1="29.939" y2="29.939" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iZm2gPe" x1="9.19" x2="7.596" y1="29.945" y2="29.945" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="iWK2cbc" x1="14.705" x2="13.268" y1="20.009" y2="16.884" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="dpuybmbgp"/></linearGradient><linearGradient id="ixg2elc" x1="15.518" x2="15.209" y1="20.087" y2="19.97" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="iKUzjhd" x1="16.798" x2="18.955" y1="19.938" y2="16.839" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="syt8fxg1a"/></linearGradient><linearGradient id="ieJeZPb" x1="16.486" x2="16.722" y1="19.7" y2="19.621" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iMSgFGb" x1="12.815" x2="12.815" y1="16.806" y2="29.451" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="i39c9ze" x1="17.576" x2="14.433" y1="18.478" y2="18.096" gradientUnits="userSpaceOnUse"><stop class="qpq6uwwfm"/><stop offset="1" class="q44v-8b6o"/></linearGradient><linearGradient id="i7wFQbd" x1="13.482" x2="15.169" y1="17.415" y2="17.415" gradientUnits="userSpaceOnUse"><stop class="ac_vgwbyo"/><stop offset="1" class="ssmwmespp"/></linearGradient><linearGradient id="ifBU5bc" x1="15.205" x2="14.838" y1="19.462" y2="19.009" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iNo66ad" x1="9.8" x2="12.759" y1="10.67" y2="10.67" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iDL6ARc" x1="16.095" x2="16.095" y1="12.62" y2="9.939" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iDhVw6E" x1="15.049" x2="15.903" y1="11.858" y2="11.963" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iI8hXZd" x1="16.095" x2="16.095" y1="12.713" y2="12.102" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="i2lSLOd" x1="15.366" x2="15.819" y1="14.189" y2="13.318" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iJVBsne" x1="19.055" x2="18.741" y1="10.039" y2="10.232" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPyx66b" x1="14.656" x2="14.343" y1="10.039" y2="10.232" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isGDt9c" x1="13.204" x2="13.748" y1="4.384" y2="5.658" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-tuxedo" /></template>
<style>
.a_1c8ebbm {
  width: 3.875px;
  height: 6.133px;
  x: 14.075px;
  y: 12.681px;
  rx: 1.938px;
}

.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a_q7bzbvy {
  d: path("m17.892 17.508l-1.813 1.25l1.795 1.26c.159.11.378.006.388-.188c.041-.791.041-1.57.008-2.144a.239.239 0 0 0-.378-.178");
}

.a-ode2e4f {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.095 13.494c-.52 0-1.01-.125-1.421-.345c-.141-.073-.292.089-.204.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.a4l-32baa {
  fill: var(--svg-color--9c80b1, #9C80B1);
  fill-rule: evenodd;
  d: path("M12.889 16.713c-.037.825.18 2.636 1.367 3.871c.255.266.715.18.863-.129l.73-1.435l.731 1.435c.149.309.608.395.863.13c1.186-1.236 1.404-3.047 1.368-3.872z");
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ac_vgwbyo {
  stop-color: var(--svg-color--b77c25, #B77C25);
}

.af_597hlr {
  cx: 16.004px;
  cy: 25.608px;
  r: 0.5px;
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.akyiodbem {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.429 11.657a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.aogbk3bnc {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.922 11.657a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b4l0e5n-v {
  d: path("M17.598 20.31c1.186-1.235 1.368-4.254 1.368-4.254c-.681-.36-1.548-.406-1.548-.406l-1.421.789l-.036 2.222l.774 1.52c.148.308.608.394.863.129");
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bl64p8vem {
  fill: var(--svg-color--000, #000);
  d: path("M14.422 10.401a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.bqbtyru4r {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.953 10.014c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cuhgmgbdd {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.827 8.347l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d4s99bb9k {
  d: path("M11.008 9.32h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.803-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.881-4.983-4.684z");
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dl6g9_kqy {
  d: path("M14.41 20.31c-1.185-1.235-1.367-4.254-1.367-4.254c.681-.36 1.548-.406 1.548-.406l1.421.789l.035 2.222l-.773 1.52c-.148.308-.608.394-.863.129");
}

.dpuybmbgp {
  stop-color: var(--svg-color--9b7388, #9B7388);
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.el3lqfbdv {
  stop-color: var(--svg-color--dd7620, #DD7620);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.ez7avhbjq {
  d: path("M14.726 10.295c0-.288-.235-.48-.298-.538l-.288.279l.177.36z");
}

.f_qid_ozs {
  stop-color: var(--svg-color--b37006, #B37006);
  stop-opacity: 0;
}

.f8v-uiwnz {
  d: path("M11.2 4.569c.622-.554 1.518-.56 2.02-.47l.403 1.29c-.257-.038-.486.051-.679.236c-.456 1.26-2.023 1.955-2.749 2.145c-.15-1.492-.067-2.246 1.006-3.201");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fho213byd {
  d: path("m15.713 10.221l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fzniv18pp {
  d: path("M11.242 18.373c-.03-1.011.55-1.42.819-1.502l.617-.065v5.372c0 3.575.239 4.663 2.733 7.121l.011.015c.047.082-.05.176-.132.12c-2.75-1.881-4.776-3.355-5.094-8.18a.187.187 0 0 1 .174-.198c.297-.02.56-.044.747-.061a.19.19 0 0 0 .171-.191c-.01-.53-.02-1.532-.046-2.431");
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.giy8nbbeg {
  d: path("M11.429 11.657a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hbggewb8s {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.332 17.576c0-1.278-.933-1.774-1.555-1.618v5.737c0 3.874-1.452 6.262-2.711 8.087c-.063.092.047.202.138.14c2.976-2.037 4.915-4.004 5.26-9.227a.203.203 0 0 0-.188-.215c-.321-.02-.606-.047-.809-.066a.204.204 0 0 1-.185-.207c.011-.574.023-1.658.05-2.631");
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hk1tjhb3n {
  d: path("M20.922 11.657a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.i05iocb4q {
  d: path("M5.07 26.442c0-5.796 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.824 10.5 10.62v3.497H5.07z");
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.iy96rk8eb {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.244 8.21c-.323-.079-1.125-.04-1.661.344");
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jbyw46wmx {
  d: path("M13.91 9.509a.893.893 0 0 0-.86 1.127h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.jds94kk2q {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.486 9.237c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.371-1.127");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jnu_kjbik {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.702 10.36l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.k24c38bex {
  cx: 16.004px;
  cy: 22.6px;
  r: 0.5px;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.kfijucblt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.213 9.697c.063.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.158-.358s.325-.136.389-.05");
}

.konrsab1i {
  d: path("M18.767 16.09a10.3 10.3 0 0 0-2.337-.268h-.86a10.3 10.3 0 0 0-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kpkfhbcqt {
  d: path("M20.922 12.192a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.l4v_prl5j {
  d: path("M8.901 18.263a10.69 10.69 0 0 0-3.831 8.185v3.497H8.9z");
}

.l79g3_q8r {
  fill-rule: evenodd;
  d: path("M23.28 11.992c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.456M11.02 9.32h-.012l1.199 2.355c.123 2.803 1.217 0 3.888 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.955-1.332-1.135-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195A2.3 2.3 0 0 1 11.86 7.29l-.051.02c-.236.122-.79.49-.81 1.439l.01.306z");
}

.la3dubb6m {
  d: path("M18.213 9.697c.063.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.158-.358s.325-.136.389-.05");
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.ldtl0hlos {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.035 8.21c.322-.079 1.124-.04 1.66.344");
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvxmtuw0d {
  cx: 16.012px;
  cy: 18.728px;
  r: 0.809px;
}

.lz8mhtb-l {
  d: path("M8.901 18.263a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m7lodbb-w {
  stop-color: var(--svg-color--5e3a14, #5E3A14);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mihtq2baw {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.508l1.813 1.25l-1.795 1.26a.246.246 0 0 1-.389-.188c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.178");
}

.mqzxx36cv {
  fill: var(--svg-color--000, #000);
  d: path("M17.768 10.401a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nw6gm2x_y {
  cx: 15.731px;
  cy: 22.733px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.nzfx5cglb {
  cx: 13.641px;
  cy: 9.89px;
  rx: 0.389px;
  ry: 0.197px;
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.omy-qpbkf {
  d: path("M19.074 10.283a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.p8x14zbnk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.704 9.237c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q44v-8b6o {
  stop-color: var(--svg-color--d58718, #D58718);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qpq6uwwfm {
  stop-color: var(--svg-color--efae2a, #EFAE2A);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.ru-v66bfm {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.095 13.494c-.52 0-1.01-.125-1.421-.345c-.141-.073-.292.089-.204.22a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.sdq_xvxgz {
  cx: 15.731px;
  cy: 25.881px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.shmyaibpb {
  stop-color: var(--svg-color--9d620c, #9D620C);
}

.ssmwmespp {
  stop-color: var(--svg-color--b77c25, #B77C25);
  stop-opacity: 0;
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.svk_nnbgw {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.237 10.014c.266-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.syt8fxg1a {
  stop-color: var(--svg-color--ddc5cf, #DDC5CF);
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.t7038hnbe {
  stop-color: var(--svg-color--b37006, #B37006);
}

.tanxzdbxx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.204 4.04c.023.244.234 1.157.544 1.71");
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tlrlcmzrj {
  d: path("M15.492 2.792c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.276 6.537 2.984c1.572-.175 1.743.542 1.877.888c-.436-4.056-3.37-4.676-5.95-5.246");
}

.tqwml4b9z {
  stop-color: var(--svg-color--9d620c, #9D620C);
  stop-opacity: 0;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.udg19xb4u {
  d: path("M11.709 17.576c0-1.278.933-1.774 1.554-1.618v5.737c0 3.874 1.453 6.262 2.712 8.087c.063.092-.047.202-.138.14c-2.977-2.037-4.916-4.004-5.26-9.227a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.207c-.011-.574-.023-1.658-.05-2.631");
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v4f-6nbua {
  cx: 13.641px;
  cy: 9.89px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vakyesjxt {
  d: path("M11.41 12.192a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w30z7opiv {
  d: path("M18.28 9.509a.892.892 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wdszzbb5h {
  stop-color: var(--svg-color--e1a61f, #E1A61F);
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wueiihd6h {
  stop-color: var(--svg-color--c8671e, #C8671E);
  stop-opacity: 0;
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x8nc6nbsj {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.697 8.805l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 0 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.194");
}

.xbn905b4c {
  stop-color: var(--svg-color--ae6d14, #AE6D14);
  stop-opacity: 0;
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xvy570_kd {
  stop-color: var(--svg-color--773703, #773703);
}

.y20wtkswp {
  stop-color: var(--svg-color--e1a61f, #E1A61F);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.y90vs2b5r {
  d: path("M23.099 18.263a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yj4a76owm {
  stop-color: var(--svg-color--ae6d14, #AE6D14);
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yxq7o1but {
  d: path("m14.133 17.508l1.813 1.25l-1.795 1.26a.246.246 0 0 1-.389-.188c-.04-.791-.04-1.57-.007-2.144a.239.239 0 0 1 .378-.178");
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

</style>
