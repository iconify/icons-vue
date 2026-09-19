<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iSJybOe)" class="d2kvgvbvc"><path fill="url(#iJyJVCd)" class="d58xsy3oy"/><path fill="url(#ibISERd)" class="d58xsy3oy"/><path fill="url(#iXptHHb)" class="d58xsy3oy"/><path fill="url(#iPU55Nb)" class="d58xsy3oy"/><path fill="url(#iC9w9Ed)" class="d58xsy3oy"/><path fill="url(#i4kjgBd)" class="d58xsy3oy"/><path fill="url(#i3fEBec)" class="d58xsy3oy"/><path fill="url(#iV3ixne)" class="d58xsy3oy"/><path fill="url(#iCaeqrb)" class="d58xsy3oy"/><path fill="url(#iGoXKDe)" class="d58xsy3oy"/><path fill="url(#iAbhxBb)" class="d58xsy3oy"/></g><path fill="url(#iU1tCLc)" class="fxsu4iiay"/><path fill="url(#ioqbbPd)" class="fxsu4iiay"/><path fill="url(#iSDnwrt)" class="une0krbwe"/><g filter="url(#iVzzSMA)"><path fill="url(#iPbhX1d)" class="zg166u5-a"/></g><g filter="url(#idZVCGd)"><path fill="url(#iG7nZ3i)" class="aj78uq-5q"/><path fill="url(#iLuMZCe)" class="aj78uq-5q"/></g><g filter="url(#i1AmLpc)"><path class="mi5e6264f"/><path fill="url(#i9HjQoc)" class="twaszacdx"/></g><g filter="url(#iyxYUCo)"><path class="ubkqtlduz"/><path fill="url(#iM7Usfc)" class="a-uu4hs5r"/></g><g filter="url(#iDlzkVj)"><path fill="url(#ix7WB1b)" class="c0q9jps4g"/><path fill="url(#iqkJ03c)" class="c0q9jps4g"/><path fill="url(#i9h2bBe)" class="c0q9jps4g"/><path fill="url(#ixHayUb)" class="c0q9jps4g"/><path fill="url(#iCndaVd)" class="c0q9jps4g"/></g><path fill="url(#iTvUfue)" class="c0q9jps4g"/><path fill="url(#i8Gxpld)" class="c0q9jps4g"/><g filter="url(#iN5dSMb)"><path class="uw_u0er6j"/></g><g filter="url(#it61gre)"><path class="m3jjpz_7g"/><path fill="url(#imZQ3gb)" class="xlapwpzgi"/><path fill="url(#ikDPDKc)" class="xlapwpzgi"/><path fill="url(#iqqomty)" class="xlapwpzgi"/><path fill="url(#iWRIrHe)" class="xlapwpzgi"/></g><g filter="url(#iIdEV2c)"><path fill="url(#i0goVcd)" class="vq2eg9b6h"/></g><g filter="url(#iOb5Etd)"><path stroke="url(#izAW4Lb)" class="otnq_rtlo"/></g><path class="sf51a3xpg"/><g filter="url(#i5Q3ugc)"><path class="ze98a9f-u"/><path fill="url(#iRAJunc)" class="w73pusboq"/></g><g filter="url(#iuqD1Sc)"><path class="cuvo_fb6o"/><path fill="url(#ipT1PMe)" class="ucokjm2uw"/><path fill="url(#iLSC6qe)" class="ucokjm2uw"/></g><g filter="url(#iF4apKu)"><path stroke="url(#im8OzKc)" class="egltyfb-q"/></g><g filter="url(#iDvcvXc)"><path class="kesh4db7f"/></g><g filter="url(#iUaMHce)"><path fill="url(#itVq4fe)" class="du5ci-_rh"/></g><g filter="url(#iGUwkDk)"><path fill="url(#iAHIiEc)" class="imak732kd"/></g><path fill="url(#i2zmxgd)" class="zf9ki4bnc"/><path fill="url(#i4wBVsd)" class="anst1ac4w"/><g filter="url(#iHEft2c)" class="tryqaac1t"><path stroke="url(#itp0eBd)" class="xtm-pfbxr"/><path stroke="url(#inVmNce)" class="xtm-pfbxr"/></g><g filter="url(#iMqDQIq)" class="tryqaac1t"><path stroke="url(#izSOjUd)" class="nt5fzmb8q"/><path stroke="url(#iG0pz6d)" class="nt5fzmb8q"/></g><g filter="url(#iyUVPdd)"><path class="vfuzjlh-d"/></g><g filter="url(#iGwLHjb)"><path clip-rule="evenodd" class="pmr1_8bdo"/></g><g filter="url(#inAezsb)"><path class="ar9wcukgx"/></g><g filter="url(#ix3radc)"><path class="mc4jm6dwy"/></g><path class="wn4a04bkk"/><path fill="url(#iGQmXyb)" class="q46yrfr2x"/><path fill="url(#iufF2Yc)" class="q46yrfr2x"/><path fill="url(#iTcPI9d)" class="q46yrfr2x"/><path fill="url(#iNkgAIb)" class="q46yrfr2x"/><path fill="url(#iAz00Dd)" class="q46yrfr2x"/><path fill="url(#igtTWsd)" class="q46yrfr2x"/><path fill="url(#iT5wWad)" class="q46yrfr2x"/><g filter="url(#iGjNTBd)"><path fill="url(#i2dBhEA)" class="yizrp5b2e"/><path fill="url(#iQEzvHb)" class="yizrp5b2e"/><path fill="url(#iDq7mRd)" class="yizrp5b2e"/></g><path fill="url(#iIMlwbd)" class="sg4zs4eyj"/><g filter="url(#iqN86dc)"><path fill="url(#itxgntb)" class="tfmg_zb5t"/><path fill="url(#i8K2V2c)" class="tfmg_zb5t"/></g><g filter="url(#itMJfEb)"><path class="tkb3ykb9j"/><path fill="url(#iXalLEe)" class="c593kmb-k"/><path fill="url(#iCyr7rd)" class="c593kmb-k"/><path fill="url(#i2LXtzb)" class="c593kmb-k"/><path fill="url(#iuZqOOb)" class="c593kmb-k"/></g><path fill="url(#iAJW9jb)" class="x9dlezr0n"/><path fill="url(#ilNPVsv)" class="x9dlezr0n"/><path fill="url(#iKY6Lce)" class="j_8juzb3p"/><path fill="url(#izFKYJe)" class="j_8juzb3p"/><path fill="url(#iqNeDBe)" class="x7g1thl-m"/><path fill="url(#iwUgRCd)" class="x7g1thl-m"/><path fill="url(#i9deLeb)" class="x7g1thl-m"/><path fill="url(#ijvXkRc)" class="x7g1thl-m"/><path fill="url(#iwoMIue)" class="x7g1thl-m"/><path fill="url(#i3UYk1c)" class="iyrx-5b-q"/><path fill="url(#iYjThBb)" class="vglg0hb-r"/><path fill="url(#i3rChUb)" class="s4-2qbb9q"/><path fill="url(#iTuV3Nd)" class="s4-2qbb9q"/><path fill="url(#ij4qdEe)" class="s4-2qbb9q"/><g filter="url(#iSX3aHd)"><path stroke="url(#iEvukNe)" class="v8nmlpbcq"/></g><path fill="url(#iA9k5zd)" class="a5bz94bmk"/><path fill="url(#iqceAfb)" class="a5bz94bmk"/><path fill="url(#iWwnbFd)" class="hy7ph4b1h"/><g filter="url(#iTomZ3d)"><path fill="url(#innY4gd)" class="rmk4l137m"/><path fill="url(#iB1dG7d)" class="rmk4l137m"/><path fill="url(#in79Moe)" class="rmk4l137m"/></g><path fill="url(#ioYYvbc)" class="sio3occnv"/><path fill="url(#iKcRJkc)" class="sio3occnv"/><path fill="url(#iCnJGlc)" class="sio3occnv"/><path fill="url(#i8jBync)" class="sio3occnv"/><path fill="url(#iQokPGQ)" class="sio3occnv"/><path class="i1k9-mb6v"/><path fill="url(#ikbD1vd)" class="n1k1njwll"/><path fill="url(#iqKFvvb)" class="n1k1njwll"/><path class="rokigy3rw"/><path fill="url(#iEB6wKd)" class="t6yqlbfrw"/><path fill="url(#ikTYJzZ)" class="t6yqlbfrw"/><path fill="url(#iG8jCHz)" class="ejpxjdvfs"/><path fill="url(#ikA2krd)" class="ejpxjdvfs"/><path fill="url(#iAk9p9l)" class="ejpxjdvfs"/><path fill="url(#i3TL36A)" class="ejpxjdvfs"/><path fill="url(#iL7A1bc)" class="bwhixk1fa"/><path fill="url(#i4nVGqe)" class="bwhixk1fa"/><path fill="url(#iFI4KGc)" class="bwhixk1fa"/><path fill="url(#iSe2kcd)" class="bwhixk1fa"/><path fill="url(#iqyF38c)" class="v6xxjs_8m"/><path fill="url(#iHW1koH)" class="v6xxjs_8m"/><path fill="url(#ic2YlXd)" class="v6xxjs_8m"/><path fill="url(#ij9IWgb)" class="v6xxjs_8m"/><g filter="url(#iT0Jpje)"><path stroke="url(#iRSpnlc)" class="v3wv1bcim"/></g><g filter="url(#ibW7MAe)" class="mc2zb0bvp"><path class="vqe7jibyg"/></g><g filter="url(#iN2TbCd)" class="mc2zb0bvp"><path class="cexr9bcqk"/></g><defs><radialGradient id="ibISERd" cx="0" cy="0" r="1" gradientTransform="matrix(.22543 4.69329 -5.86287 .28161 14.753 13.432)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iXptHHb" cx="0" cy="0" r="1" gradientTransform="rotate(135.715 3.093 9.543)scale(3.55289 4.66822)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iPU55Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00228 1.95728 -1.50292 -.76961 9.77 11.97)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iC9w9Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.91201 2.35863 -1.66144 -.64243 9.855 9.848)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i4kjgBd" cx="0" cy="0" r="1" gradientTransform="matrix(1.85887 2.37775 -3.30069 2.5804 9.59 3.404)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i3fEBec" cx="0" cy="0" r="1" gradientTransform="rotate(124.709 8.694 6.967)scale(2.08276 2.91062)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iV3ixne" cx="0" cy="0" r="1" gradientTransform="rotate(153.49 9.98 6.909)scale(1.96179 4.09117)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iCaeqrb" cx="0" cy="0" r="1" gradientTransform="rotate(155.674 9.692 8.464)scale(2.96551 3.77762)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iGoXKDe" cx="0" cy="0" r="1" gradientTransform="rotate(-119.132 11.346 -2.162)scale(2.86115 2.263)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iAbhxBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.54065 -.11587 .18775 2.49631 8.263 11.092)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ioqbbPd" cx="0" cy="0" r="1" gradientTransform="matrix(2.19471 3.52472 -6.20084 3.86104 16.045 15.557)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="wcbvx-n_a"/><stop offset="1" class="sbx2zkbbn"/></radialGradient><radialGradient id="iG7nZ3i" cx="0" cy="0" r="1" gradientTransform="matrix(1.46499 -2.38068 2.9067 1.78868 19.31 11.02)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iLuMZCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.4573 .50127 -.14172 .412 19.39 8.248)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i9HjQoc" cx="0" cy="0" r="1" gradientTransform="rotate(-14.543 49.383 -69.5)scale(1.54694 1.20928)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iM7Usfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2132 .22023 -.17374 -.95706 9.974 11.702)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="ix7WB1b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.99065 4.20171 -5.62392 -8.01839 17.376 9.8)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iqkJ03c" cx="0" cy="0" r="1" gradientTransform="rotate(162.284 8.145 6.953)scale(3.56623 3.93649)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i9h2bBe" cx="0" cy="0" r="1" gradientTransform="matrix(.62299 -4.04667 5.13446 .79045 13.446 18.124)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="ixHayUb" cx="0" cy="0" r="1" gradientTransform="rotate(103.98 3.685 11.332)scale(7.1681 10.7309)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="xk7cvlbih"/><stop offset=".904" class="vxc8-2g3s"/></radialGradient><radialGradient id="iCndaVd" cx="0" cy="0" r="1" gradientTransform="rotate(158.608 7.21 7.437)scale(7.1902 12.3793)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iTvUfue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29207 .23455 -1.17626 -6.47963 19.819 10.467)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="i8Gxpld" cx="0" cy="0" r="1" gradientTransform="matrix(2.04942 3.78162 -6.58803 3.57034 11.21 4.69)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="imZQ3gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83096 -1.97168 .60766 -.2561 15.617 11.985)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iWRIrHe" cx="0" cy="0" r="1" gradientTransform="rotate(169.709 7.157 6.814)scale(.79633 .22263)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iRAJunc" cx="0" cy="0" r="1" gradientTransform="matrix(.76584 -3.0003 1.53488 .39179 8.416 9.163)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ipT1PMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32163 4.8001 -7.84788 -2.16078 15.074 2.547)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iLSC6qe" cx="0" cy="0" r="1" gradientTransform="matrix(.03806 1.4128 -3.03958 .08188 13.432 3.229)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="inVmNce" cx="0" cy="0" r="1" gradientTransform="matrix(-.11824 .20437 -.19738 -.1142 17.728 10.03)" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ql2-nbc9p"/><stop offset="1" class="ns3cxsbdp"/></radialGradient><radialGradient id="iG0pz6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.11824 .20437 -.19738 -.1142 13.437 10.752)" gradientUnits="userSpaceOnUse"><stop class="dwxodwo3m"/><stop offset="1" class="ql2-nbc9p"/><stop offset="1" class="ns3cxsbdp"/></radialGradient><radialGradient id="iTcPI9d" cx="0" cy="0" r="1" gradientTransform="matrix(.28711 3.40925 -4.12958 .34777 8.64 20.672)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="v442oubmz"/><stop offset="1" class="p_ew-572a"/></radialGradient><radialGradient id="iNkgAIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.39 19.39)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="m0rm-m-qv"/><stop offset="1" class="wi8a08bum"/></radialGradient><radialGradient id="iAz00Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.598 30.047)" gradientUnits="userSpaceOnUse"><stop class="wagk6dfaq"/><stop offset="1" class="hfzkti_ts"/></radialGradient><radialGradient id="iT5wWad" cx="0" cy="0" r="1" gradientTransform="matrix(.1168 1.84919 -2.9447 .18598 8.846 21.875)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="k5vtewq9k"/><stop offset="1" class="z1zjblq2q"/></radialGradient><radialGradient id="i2dBhEA" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 24.829)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iQEzvHb" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.872 10.169)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iDq7mRd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 25.766)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iIMlwbd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.271 22.877)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="itxgntb" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.055 12.746)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="i8K2V2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.547)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iXalLEe" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -37.895 40.456)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="xohjverxe"/><stop offset="1" class="sghoc4brb"/></radialGradient><radialGradient id="iCyr7rd" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.924 30.047)" gradientUnits="userSpaceOnUse"><stop class="hmgh32r7m"/><stop offset="1" class="ib26drc1k"/></radialGradient><radialGradient id="iuZqOOb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.265 28.985)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="at1_k3rsw"/><stop offset="1" class="frn5ss_le"/></radialGradient><radialGradient id="iAJW9jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02344 -.68462 0 19.607 28.067)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="rntqzsbvm"/><stop offset="1" class="kn6547brm"/></radialGradient><radialGradient id="izFKYJe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.5625 1.81252 -.47277 -2.23342 29.083 26.52)" gradientUnits="userSpaceOnUse"><stop class="o7yf4tl0b"/><stop offset="1" class="x9s6ceaht"/></radialGradient><radialGradient id="iqNeDBe" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.765 19.922)" gradientUnits="userSpaceOnUse"><stop class="h0nz-rbjw"/><stop offset="1" class="kfbnffbzx"/></radialGradient><radialGradient id="i9deLeb" cx="0" cy="0" r="1" gradientTransform="rotate(110.854 -2.821 13.061)scale(2.10677 2.16117)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="jz746dbzd"/><stop offset="1" class="dzs1febsk"/></radialGradient><radialGradient id="ijvXkRc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 20.895)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="cwu2h0blp"/><stop offset="1" class="f9-tluqmj"/></radialGradient><radialGradient id="iwoMIue" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.532)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yyn9swbvh"/><stop offset="1" class="pviihufyn"/></radialGradient><radialGradient id="ij4qdEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 15.027 18.539)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iEvukNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.064)" gradientUnits="userSpaceOnUse"><stop class="ut4bgvb0y"/><stop offset="1" class="gngaedcou"/></radialGradient><radialGradient id="iqceAfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 17.863)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iB1dG7d" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -34.764 34.279)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="iKcRJkc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.455 18.51)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="u2k5px3jq"/><stop offset="1" class="dmm5ewwwm"/></radialGradient><radialGradient id="iCnJGlc" cx="0" cy="0" r="1" gradientTransform="rotate(117.711 .075 11.58)scale(4.44066 1.93651)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="oh8on9brk"/><stop offset="1" class="f1r2vnb5a"/></radialGradient><radialGradient id="i8jBync" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.273 18.164)" gradientUnits="userSpaceOnUse"><stop class="n0p5sxbec"/><stop offset="1" class="q4weiw-ee"/></radialGradient><radialGradient id="iQokPGQ" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16051 9.008 20.688)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="z6zfulbza"/><stop offset="1" class="v3ok2mbfm"/></radialGradient><radialGradient id="ikbD1vd" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.72 17.572)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="tv0y_es3w"/><stop offset="1" class="b84ow2m2e"/></radialGradient><radialGradient id="iqKFvvb" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 5.262 9.84)scale(.78612 .35637)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="jj_i0ybwk"/></radialGradient><radialGradient id="iEB6wKd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.243 2.308)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="y-w2tsblc"/><stop offset="1" class="xdt63zb6q"/></radialGradient><radialGradient id="ikTYJzZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.814 17.57)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="c6e6dvbgn"/><stop offset="1" class="ph2kohtod"/></radialGradient><radialGradient id="iG8jCHz" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.143 18.821)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="b-w3yacim"/><stop offset="1" class="f9l-1bcqi"/></radialGradient><radialGradient id="ikA2krd" cx="0" cy="0" r="1" gradientTransform="matrix(2.29688 1.78687 -.45885 .58982 11.518 19.093)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="u9db7sbld"/><stop offset="1" class="cbv0v1bug"/></radialGradient><radialGradient id="iAk9p9l" cx="0" cy="0" r="1" gradientTransform="rotate(136.002 2.418 11.854)scale(.96996 1.97716)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="e9ied_q8k"/><stop offset="1" class="r3idh6bhh"/></radialGradient><radialGradient id="i3TL36A" cx="0" cy="0" r="1" gradientTransform="matrix(.48047 -.3496 .60677 .83392 8.94 18.9)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="urjmhobql"/><stop offset="1" class="lrbywkbvr"/></radialGradient><radialGradient id="iL7A1bc" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.869 21.517)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="i6m3xbfso"/><stop offset="1" class="ulc1d0bsf"/></radialGradient><radialGradient id="i4nVGqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.768 20.071)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="mql7c3hze"/><stop offset="1" class="m1_omrdxn"/></radialGradient><radialGradient id="iFI4KGc" cx="0" cy="0" r="1" gradientTransform="rotate(97.522 -3.679 14.482)scale(2.32995 4.84987)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="t5ovicbrp"/><stop offset=".962" class="i2e83jb8g"/></radialGradient><radialGradient id="iSe2kcd" cx="0" cy="0" r="1" gradientTransform="matrix(.54646 -.48802 1.62742 1.82231 7.87 20.834)" gradientUnits="userSpaceOnUse"><stop class="wdwsowbvt"/><stop offset="1" class="iy8y9zu4h"/></radialGradient><radialGradient id="iHW1koH" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 1.014 15.822)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="ic2YlXd" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .897 16.298)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="ij9IWgb" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.353 10.315)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iRSpnlc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 21.863)" gradientUnits="userSpaceOnUse"><stop class="zbwshaccu"/><stop offset="1" class="piz2rbc3b"/></radialGradient><linearGradient id="iJyJVCd" x1="18.049" x2="13.508" y1="3.017" y2="16.93" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iU1tCLc" x1="19.224" x2="12.336" y1="18.652" y2="30.328" gradientUnits="userSpaceOnUse"><stop class="q9xywcr7e"/><stop offset="1" class="jvlxembhy"/></linearGradient><linearGradient id="iSDnwrt" x1="14.777" x2="16.84" y1="17.178" y2="18.209" gradientUnits="userSpaceOnUse"><stop offset=".048" class="k3-33mbjc"/><stop offset="1" class="jcl8do7gv"/></linearGradient><linearGradient id="iPbhX1d" x1="8.287" x2="11.262" y1="12.099" y2="11.559" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="ikDPDKc" x1="13.899" x2="14.842" y1="12.372" y2="12.201" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iqqomty" x1="14.988" x2="14.877" y1="13.004" y2="12.39" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="i0goVcd" x1="14.426" x2="14.671" y1="10.123" y2="11.432" gradientUnits="userSpaceOnUse"><stop class="xaulv1bog"/><stop offset="1" class="th144cwik"/></linearGradient><linearGradient id="izAW4Lb" x1="14.175" x2="14.509" y1="14.616" y2="13.815" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="im8OzKc" x1="10.562" x2="11.342" y1="5.159" y2="6.34" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="itVq4fe" x1="13.126" x2="10.546" y1="10.179" y2="9.899" gradientUnits="userSpaceOnUse"><stop class="gbf1_y03d"/><stop offset="1" class="bmyc5db9w"/></linearGradient><linearGradient id="iAHIiEc" x1="17.678" x2="14.342" y1="9.67" y2="8.562" gradientUnits="userSpaceOnUse"><stop offset=".394" class="xpf_69b1t"/><stop offset="1" class="rf88abbhx"/><stop offset="1" class="sjjdjlu1h"/></linearGradient><linearGradient id="i2zmxgd" x1="16.421" x2="17.892" y1="11.089" y2="10.009" gradientUnits="userSpaceOnUse"><stop offset=".048" class="kpx6jhb5u"/><stop offset="1" class="wpapq1b-u"/></linearGradient><linearGradient id="i4wBVsd" x1="12.102" x2="13.579" y1="11.823" y2="10.745" gradientUnits="userSpaceOnUse"><stop offset=".048" class="kpx6jhb5u"/><stop offset="1" class="wpapq1b-u"/></linearGradient><linearGradient id="itp0eBd" x1="15.672" x2="17.908" y1="10.471" y2="10.627" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="izSOjUd" x1="11.382" x2="13.618" y1="11.194" y2="11.349" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="iGQmXyb" x1="9.109" x2="3.64" y1="26.36" y2="24.891" gradientUnits="userSpaceOnUse"><stop class="g1c-6jb6y"/><stop offset="1" class="hkdf97w8c"/></linearGradient><linearGradient id="iufF2Yc" x1="3.333" x2="5.328" y1="25.988" y2="26.641" gradientUnits="userSpaceOnUse"><stop class="da95trp0k"/><stop offset="1" class="feoz1vgta"/></linearGradient><linearGradient id="igtTWsd" x1="9.229" x2="8.836" y1="28.378" y2="28.253" gradientUnits="userSpaceOnUse"><stop class="rehc034in"/><stop offset="1" class="psvt8ubmu"/></linearGradient><linearGradient id="i2LXtzb" x1="18.227" x2="17.566" y1="26.322" y2="27.217" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pbsapybex"/><stop offset="1" class="vvwmaab9t"/></linearGradient><linearGradient id="ilNPVsv" x1="19.395" x2="19.395" y1="26.681" y2="27.52" gradientUnits="userSpaceOnUse"><stop class="y-ymn0bhn"/><stop offset="1" class="he69lvb0i"/></linearGradient><linearGradient id="iKY6Lce" x1="26.546" x2="26.984" y1="26.829" y2="30.547" gradientUnits="userSpaceOnUse"><stop class="tnk2b_bjh"/><stop offset="1" class="p40qzpbtf"/></linearGradient><linearGradient id="iwUgRCd" x1="5.833" x2="6.912" y1="19.801" y2="21.504" gradientUnits="userSpaceOnUse"><stop class="j4n7g28_w"/><stop offset="1" class="laie_nbgc"/></linearGradient><linearGradient id="i3UYk1c" x1="11.144" x2="10.997" y1="22.119" y2="19.476" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iYjThBb" x1="12.351" x2="11.964" y1="20.31" y2="18.328" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="i3rChUb" x1="15.095" x2="14.313" y1="18.126" y2="21.112" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iTuV3Nd" x1="14.222" x2="14.445" y1="21.332" y2="20.441" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iA9k5zd" x1="14.953" x2="13.828" y1="17.345" y2="21.673" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="iWwnbFd" x1="15.265" x2="14.156" y1="17.72" y2="17.36" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="innY4gd" x1="14.453" x2="13.223" y1="17.235" y2="21.985" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="in79Moe" x1="12.549" x2="12.768" y1="21.051" y2="19.973" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="ioYYvbc" x1="8.421" x2="8.964" y1="16.735" y2="21.235" gradientUnits="userSpaceOnUse"><stop class="fa6dpirps"/><stop offset="1" class="jplxqgtye"/></linearGradient><linearGradient id="iqyF38c" x1="16.521" x2="15.937" y1="18.61" y2="21.11" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><filter id="iSJybOe" width="16.056" height="16.739" x="6.993" y="1.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="iVzzSMA" width="3.439" height="3.289" x="8.245" y="10.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="idZVCGd" width="3.289" height="3.539" x="17.808" y="8.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="i1AmLpc" width="3.195" height="3.195" x="17.855" y="8.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".25"/></filter><filter id="iyxYUCo" width="2.995" height="2.995" x="8.411" y="10.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".2"/></filter><filter id="iDlzkVj" width="10.775" height="10.944" x="9.113" y="6.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="iN5dSMb" width="2.904" height="3.795" x="13.283" y="9.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".25"/></filter><filter id="it61gre" width="2.404" height="3.285" x="13.671" y="9.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".125"/></filter><filter id="iIdEV2c" width="2.404" height="3.285" x="13.615" y="9.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".125"/></filter><filter id="iOb5Etd" width="3.724" height="1.839" x="13.231" y="12.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".05"/></filter><filter id="i5Q3ugc" width="4.013" height="5.033" x="7.58" y="4.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/><feGaussianBlur result="effect2_foregroundBlur_4002_3545" stdDeviation=".15"/></filter><filter id="iuqD1Sc" width="9.531" height="4.771" x="10.229" y="2.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/><feGaussianBlur result="effect2_foregroundBlur_4002_3545" stdDeviation=".125"/></filter><filter id="iF4apKu" width="1.46" height="2.219" x="10.199" y="4.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".1"/></filter><filter id="iDvcvXc" width="6.681" height="3.354" x="13.169" y="4.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".375"/></filter><filter id="iUaMHce" width="3.783" height="2.916" x="10.388" y="8.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".3"/></filter><filter id="iGUwkDk" width="3.584" height="2.847" x="15.064" y="7.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".3"/></filter><filter id="iHEft2c" width="2.499" height="1.207" x="15.565" y="9.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".075"/></filter><filter id="iMqDQIq" width="2.499" height="1.207" x="11.275" y="10.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".075"/></filter><filter id="iyUVPdd" width="2.415" height="1.385" x="10.401" y="8.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="iGwLHjb" width="2.532" height=".902" x="15.478" y="7.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="inAezsb" width="2.332" height=".782" x="15.507" y="7.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".1"/></filter><filter id="ix3radc" width="2.207" height="1.251" x="10.399" y="8.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".1"/></filter><filter id="iGjNTBd" width="11.192" height="8.359" x="11.466" y="21.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="iqN86dc" width="7.407" height="8.444" x="19.048" y="18.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="itMJfEb" width="8.208" height="4.667" x="12.416" y="25.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="iSX3aHd" width="3.456" height="1.701" x="7.381" y="21.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".1"/></filter><filter id="iTomZ3d" width="4.309" height="4.662" x="11.043" y="16.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3545"/></filter><filter id="iT0Jpje" width="3.647" height="2.753" x="6.263" y="19.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".05"/></filter><filter id="ibW7MAe" width="2.634" height="2.141" x="16.374" y="25.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".125"/></filter><filter id="iN2TbCd" width="4.536" height="1" x="12.746" y="28.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3545" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-feeding-baby-light" /></template>
<style>
.a-uu4hs5r {
  d: path("M10.105 12.794a1.097 1.097 0 1 0-.392-2.16a1.097 1.097 0 0 0 .392 2.16");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a5bz94bmk {
  d: path("m11.939 16.082l3.172.884c.43.125.744.558.627.96l-.9 3.086c-.115.396-.532.606-1.024.473l-3.129-.883z");
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.aj78uq-5q {
  d: path("M19.746 11.6a1.644 1.644 0 1 0-.587-3.235a1.644 1.644 0 0 0 .587 3.235");
}

.anst1ac4w {
  d: path("M13.371 10.532c-.077.01-.134.057-.182.125a1.06 1.06 0 0 1-.71.49a1.02 1.02 0 0 1-.827-.212a.24.24 0 0 0-.211-.058a.256.256 0 0 0-.115.452c.336.278.787.413 1.248.326a1.53 1.53 0 0 0 1.066-.74c.105-.182-.058-.412-.269-.383");
}

.ar9wcukgx {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.807 8.194c.31-.138 1.123-.245 1.732.043");
}

.at1_k3rsw {
  stop-color: var(--svg-color--cf9085, #CF9085);
}

.b-w3yacim {
  stop-color: var(--svg-color--f1c0a9, #F1C0A9);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.b84ow2m2e {
  stop-color: var(--svg-color--d8ab96, #D8AB96);
  stop-opacity: 0;
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bmyc5db9w {
  stop-color: var(--svg-color--d59c8f, #D59C8F);
  stop-opacity: 0;
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bwhixk1fa {
  d: path("M8.857 20.977c-.315.22-.723.211-.906-.109c-.391-.948.72-1.58 1.5-1.598c1.167-.027 1.75.63 1.937 1.121c.188.493.227 1.477-.672 1.54c-.803.055-.847-.5-.98-.743c-.133-.242-.594-.41-.879-.21");
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c0q9jps4g {
  d: path("m9.255 10.521l.012-.002l-.058-.265l-.067-.306c-.152-.957.338-1.428.552-1.594l.048-.03l.048-.03a2.35 2.35 0 0 0 .97-1.458l.048-.21a.27.27 0 0 1 .454-.135a3.95 3.95 0 0 0 3.512 1.1l3.237-.587c.18-.033 1.104-.11 1.385 1.131l.441 3.111c.388 2.84-1.47 5.131-4.155 5.619s-5.229-1.005-5.864-3.8z");
}

.c593kmb-k {
  d: path("M17.18 25.73a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.176l-3.644.071a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.c6e6dvbgn {
  stop-color: var(--svg-color--fdd3be, #FDD3BE);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cbv0v1bug {
  stop-color: var(--svg-color--eab8a3, #EAB8A3);
  stop-opacity: 0;
}

.cexr9bcqk {
  stroke: var(--svg-color--eebdb1, #EEBDB1);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.144h3.536");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cuvo_fb6o {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M12.571 3.14c-1.184-.044-2 1.278-2.042 1.72c1.704 3.372 4.344 2.691 6.932 1.918c1.549-.462 1.851.227 2.05.55c-.718-3.953-4.215-4.085-6.91-4.186z");
}

.cwu2h0blp {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d58xsy3oy {
  d: path("M22.08 10.969c.134-.476.158-.985.065-1.494a3.35 3.35 0 0 0-.508-1.263l.005-.001a3.3 3.3 0 0 0-.376-.464l-.003-.003a3.3 3.3 0 0 1-.852-1.684l-.002-.01a3.37 3.37 0 0 0-3.918-2.715a.55.55 0 0 1-.5-.151a3.38 3.38 0 0 0-2.948-.894a3.38 3.38 0 0 0-2.445 1.873a.58.58 0 0 1-.415.317q-.043.007-.085.017a3.37 3.37 0 0 0-2.63 3.902l.002.01a3.3 3.3 0 0 1-.205 1.876l-.002.004a3.37 3.37 0 0 0 .37 3.302c.098.13.13.303.084.458a3.3 3.3 0 0 0-.069 1.474a3.283 3.283 0 0 0 3.822 2.647l8.628-1.566a3.283 3.283 0 0 0 2.647-3.822a3.3 3.3 0 0 0-.582-1.355a.53.53 0 0 1-.083-.458m-12.813-.45l-.012.003l1.635 2.15c.635 2.794 1.223-.223 3.909-.71c2.686-.488 4.426 2.435 4.038-.404l.559-3.422c-.281-1.241-1.204-1.165-1.385-1.132l-3.237.588a3.95 3.95 0 0 1-3.512-1.1a.27.27 0 0 0-.454.135l-.047.21a2.35 2.35 0 0 1-.97 1.458l-.049.03l-.048.03c-.214.166-.704.637-.551 1.594l.066.306z");
}

.da95trp0k {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dmm5ewwwm {
  stop-color: var(--svg-color--bf7875, #BF7875);
}

.du5ci-_rh {
  d: path("M10.988 9.354c1.32-.252 2.313.58 2.583 1.315c-1.357.2-1.975.13-2.395.355z");
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dzs1febsk {
  stop-color: var(--svg-color--6f409a, #6F409A);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e9ied_q8k {
  stop-color: var(--svg-color--d9a38b, #D9A38B);
}

.egltyfb-q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.5 4.813c.067.24.446 1.12.859 1.62");
}

.ejpxjdvfs {
  d: path("M8.521 18.528a.28.28 0 0 1 .133-.27c.981-.69 2.005-.304 2.383 0c.304.236 1 .79 1.363 1.082c.446.36.372.962.043 1.317c-.276.298-.751.24-.93.148l-2.097-1.312c-.055-.313-.235-.563-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f1r2vnb5a {
  stop-color: var(--svg-color--dead92, #DEAD92);
  stop-opacity: 0;
}

.f9-tluqmj {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
  stop-opacity: 0;
}

.f9l-1bcqi {
  stop-color: var(--svg-color--daa695, #DAA695);
}

.fa6dpirps {
  stop-color: var(--svg-color--dbaa8f, #DBAA8F);
}

.feoz1vgta {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
  stop-opacity: 0;
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.frn5ss_le {
  stop-color: var(--svg-color--cf9085, #CF9085);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fxsu4iiay {
  d: path("M7.155 30.047c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1c-6jb6y {
  stop-color: var(--svg-color--8a4fe4, #8A4FE4);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gbf1_y03d {
  stop-color: var(--svg-color--d59c8f, #D59C8F);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gngaedcou {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
  stop-opacity: 0;
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.h0nz-rbjw {
  stop-color: var(--svg-color--7f5499, #7F5499);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.he69lvb0i {
  stop-color: var(--svg-color--755994, #755994);
  stop-opacity: 0;
}

.hfzkti_ts {
  stop-color: var(--svg-color--8e5de1, #8E5DE1);
  stop-opacity: 0;
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkdf97w8c {
  stop-color: var(--svg-color--804ec1, #804EC1);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hmgh32r7m {
  stop-color: var(--svg-color--cc9098, #CC9098);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hy7ph4b1h {
  d: path("m14.826 17.146l-2.636-.735l-1.073 3.895l2.6.734c.408.11.755-.064.85-.394l.78-2.703c.123-.391-.164-.694-.521-.797");
}

.i1k9-mb6v {
  fill: var(--svg-color--eabba1, #EABBA1);
  d: path("M10.099 16.509c.356.125.482.33.515.453l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.i2e83jb8g {
  stop-color: var(--svg-color--c28485, #C28485);
}

.i6m3xbfso {
  stop-color: var(--svg-color--c58788, #C58788);
}

.ib26drc1k {
  stop-color: var(--svg-color--cc9098, #CC9098);
  stop-opacity: 0;
}

.imak732kd {
  d: path("M15.742 8.443c1-.314 2.306.226 2.306 1.56c-.646-.359-1.928-.498-2.384-.359z");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.iy8y9zu4h {
  stop-color: var(--svg-color--c68882, #C68882);
  stop-opacity: 0;
}

.iyrx-5b-q {
  d: path("m11.845 20.647l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.j_8juzb3p {
  d: path("M20.615 25.825c1.598-.23 4.567-.809 6.543-1.27c1.522-.263 2.641 1.203 2.641 2.781c0 1.372-1.022 2.237-1.747 2.618a.86.86 0 0 1-.403.093h-8.014v-3.086c0-.796.281-1 .98-1.136");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4n7g28_w {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
}

.jcl8do7gv {
  stop-color: var(--svg-color--d8b0ab, #D8B0AB);
}

.jj_i0ybwk {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplxqgtye {
  stop-color: var(--svg-color--c98e84, #C98E84);
}

.jvlxembhy {
  stop-color: var(--svg-color--7d49d2, #7D49D2);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.jz746dbzd {
  stop-color: var(--svg-color--6f409a, #6F409A);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k3-33mbjc {
  stop-color: var(--svg-color--a97581, #A97581);
}

.k5vtewq9k {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
}

.ka236wzgl {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kesh4db7f {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m16.256 6.22l-1.385.524a.703.703 0 1 1-.375-1.349l2.353-.427c1.392-.253 2.107 1.066 2.25 1.535a3.22 3.22 0 0 0-2.843-.282");
}

.kfbnffbzx {
  stop-color: var(--svg-color--7a45b3, #7A45B3);
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kn6547brm {
  stop-color: var(--svg-color--8259a4, #8259A4);
}

.kpx6jhb5u {
  stop-color: var(--svg-color--161312, #161312);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.laie_nbgc {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lrbywkbvr {
  stop-color: var(--svg-color--e0ae97, #E0AE97);
  stop-opacity: 0;
}

.m-leh6bjs {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
}

.m0rm-m-qv {
  stop-color: var(--svg-color--785191, #785191);
}

.m1_omrdxn {
  stop-color: var(--svg-color--fccfbe, #FCCFBE);
  stop-opacity: 0;
}

.m3jjpz_7g {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m14.149 10.57l-.224 1.805a.55.55 0 0 0 .651.608l.79-.143a.553.553 0 0 0 .396-.798l-.844-1.612c-.183-.358-.718-.261-.769.14");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mc4jm6dwy {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.305 8.816c-.338-.02-1.137.166-1.606.649");
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mi5e6264f {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M19.648 11.061a1.097 1.097 0 1 0-.392-2.16a1.097 1.097 0 0 0 .392 2.16");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mql7c3hze {
  stop-color: var(--svg-color--fccfbe, #FCCFBE);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n0p5sxbec {
  stop-color: var(--svg-color--dda891, #DDA891);
}

.n1k1njwll {
  d: path("M10.099 16.509c.356.125.482.33.515.453l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.nt5fzmb8q {
  d: path("M11.525 11.108c.125.117.497.338.981.286s.91-.522 1.018-.699");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o7yf4tl0b {
  stop-color: var(--svg-color--b087f9, #B087F9);
}

.oh8on9brk {
  stop-color: var(--svg-color--eebfa5, #EEBFA5);
}

.otnq_rtlo {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.13 13.79a3.1 3.1 0 0 1-1.491-.088c-.155-.047-.277.143-.164.258a1.974 1.974 0 0 0 3.266-.593c.064-.153-.116-.283-.244-.183c-.373.295-.838.51-1.366.606Z");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p_ew-572a {
  stop-color: var(--svg-color--8152c8, #8152C8);
  stop-opacity: 0;
}

.p40qzpbtf {
  stop-color: var(--svg-color--985ef1, #985EF1);
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbsapybex {
  stop-color: var(--svg-color--e4c0a9, #E4C0A9);
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.ph2kohtod {
  stop-color: var(--svg-color--ebbba3, #EBBBA3);
  stop-opacity: 0;
}

.piz2rbc3b {
  stop-color: var(--svg-color--875ab4, #875AB4);
  stop-opacity: 0;
}

.pmr1_8bdo {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m17.633 8.005l-.096.256za.274.274 0 0 1-.193.513l-.005-.002a1 1 0 0 0-.124-.038a3 3 0 0 0-.37-.073a2.3 2.3 0 0 0-1.093.103a.274.274 0 0 1-.19-.514a2.86 2.86 0 0 1 1.355-.133a3.3 3.3 0 0 1 .605.138l.01.004h.003z");
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.psvt8ubmu {
  stop-color: var(--svg-color--8356d1, #8356D1);
  stop-opacity: 0;
}

.pviihufyn {
  stop-color: var(--svg-color--784787, #784787);
  stop-opacity: 0;
}

.q46yrfr2x {
  d: path("m2.201 30.047l2.93-9.156c.351-1.414 2.07-2.104 3.65-1.614s2.49 2.333 2.006 3.692l-2.216 7.078z");
}

.q4weiw-ee {
  stop-color: var(--svg-color--dda891, #DDA891);
  stop-opacity: 0;
}

.q9xywcr7e {
  stop-color: var(--svg-color--9c6ed3, #9C6ED3);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.ql2-nbc9p {
  stop-color: var(--svg-color--9a6b40, #9A6B40);
  stop-opacity: 0;
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r3idh6bhh {
  stop-color: var(--svg-color--d9a38b, #D9A38B);
  stop-opacity: 0;
}

.rehc034in {
  stop-color: var(--svg-color--8356d1, #8356D1);
}

.rf88abbhx {
  stop-color: var(--svg-color--f1b493, #F1B493);
  stop-opacity: 0;
}

.rmk4l137m {
  d: path("m12.167 16.513l2.635.734c.357.104.645.406.521.797l-.779 2.704c-.096.329-.442.504-.851.394l-2.6-.734z");
}

.rntqzsbvm {
  stop-color: var(--svg-color--925cbe, #925CBE);
}

.rokigy3rw {
  fill: var(--svg-color--eabaa2, #EABAA2);
  d: path("M9.67 17.43c.243.25.33.527.343.633l.485.47l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.08c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.s4-2qbb9q {
  d: path("m14.546 17.929l.555.159a.15.15 0 0 1 .103.186l-.783 2.73a.15.15 0 0 1-.186.102l-.555-.16z");
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sbx2zkbbn {
  stop-color: var(--svg-color--89579c, #89579C);
  stop-opacity: 0;
}

.sf51a3xpg {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.13 13.79a3.1 3.1 0 0 1-1.491-.088c-.155-.047-.277.143-.164.258a1.974 1.974 0 0 0 3.266-.593c.064-.153-.116-.283-.244-.183c-.373.295-.838.51-1.366.606");
}

.sg4zs4eyj {
  d: path("M23.695 27.177a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.sghoc4brb {
  stop-color: var(--svg-color--ce9989, #CE9989);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.sio3occnv {
  d: path("M8.13 17.29c1.031-1.086 1.92-1.37 2.32-1.375l.797.867l-.93 3.516c-.179.315-.563.996-.695 1.152c-.164.195-.734.63-1.765.239c-.888-.338-1.15-.899-1.176-1.149c.234-1.167.649-2.358 1.45-3.25");
}

.sjjdjlu1h {
  stop-color: var(--svg-color--ffc9b1, #FFC9B1);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t5ovicbrp {
  stop-color: var(--svg-color--c28485, #C28485);
  stop-opacity: 0;
}

.t6yqlbfrw {
  d: path("M9.67 17.43c.243.25.33.527.343.633l.485.47l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.08c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tfmg_zb5t {
  d: path("M21.575 23.987a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.th144cwik {
  stop-color: var(--svg-color--eec1af, #EEC1AF);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tkb3ykb9j {
  fill: var(--svg-color--e1b0a4, #E1B0A4);
  d: path("M17.18 25.73a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.176l-3.644.071a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.tnk2b_bjh {
  stop-color: var(--svg-color--a078e0, #A078E0);
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tv0y_es3w {
  stop-color: var(--svg-color--d8ab96, #D8AB96);
}

.twaszacdx {
  d: path("M19.648 11.061a1.097 1.097 0 1 0-.392-2.16a1.097 1.097 0 0 0 .392 2.16");
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u2k5px3jq {
  stop-color: var(--svg-color--c38486, #C38486);
  stop-opacity: 0;
}

.u9db7sbld {
  stop-color: var(--svg-color--f5c8b4, #F5C8B4);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ubkqtlduz {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M10.105 12.794a1.097 1.097 0 1 0-.392-2.16a1.097 1.097 0 0 0 .392 2.16");
}

.ucokjm2uw {
  d: path("M12.571 3.14c-1.184-.044-2 1.278-2.042 1.72c1.704 3.372 4.344 2.691 6.932 1.918c1.549-.462 1.851.227 2.05.55c-.718-3.953-4.215-4.085-6.91-4.186z");
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.ulc1d0bsf {
  stop-color: var(--svg-color--e9b8a1, #E9B8A1);
}

.une0krbwe {
  d: path("M15.685 18.577c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.urjmhobql {
  stop-color: var(--svg-color--e0ae97, #E0AE97);
}

.ut4bgvb0y {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
}

.uw_u0er6j {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m14.164 10.71l-.377 1.834a.55.55 0 0 0 .651.608l.79-.143a.553.553 0 0 0 .396-.799l-.844-1.612c-.183-.357-.565-.288-.616.112");
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v3ok2mbfm {
  stop-color: var(--svg-color--c07e7e, #C07E7E);
  stop-opacity: 0;
}

.v3wv1bcim {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 19.798c-.206.432-.319 1.448.875 2.055c1.194.606 1.992.148 2.242-.157");
}

.v442oubmz {
  stop-color: var(--svg-color--7c4ca4, #7C4CA4);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6xxjs_8m {
  d: path("m15.454 20.813l.227.068a.5.5 0 0 0 .492-.12l.363-.352a.13.13 0 0 1 .128-.034l.315.084a.484.484 0 0 0 .253-.935l-.304-.083a.13.13 0 0 1-.097-.108l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.v8nmlpbcq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.08c.579.14 1.92.171 2.657-.829");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vfuzjlh-d {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m10.86 9.696l-.005.003a.274.274 0 0 1-.36-.412v-.001l.003-.002l.009-.008l.029-.024q.037-.03.106-.08c.09-.065.22-.151.383-.237a2.9 2.9 0 0 1 1.315-.353a.274.274 0 0 1 .003.548a2.3 2.3 0 0 0-1.061.289a3 3 0 0 0-.403.26z");
}

.vglg0hb-r {
  d: path("M10.565 18.617c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.vq2eg9b6h {
  d: path("m14.093 10.476l-.224 1.806a.55.55 0 0 0 .651.608l.79-.143a.553.553 0 0 0 .397-.798l-.845-1.612c-.183-.358-.717-.261-.769.14");
}

.vqe7jibyg {
  stroke: var(--svg-color--efc6b6, #EFC6B6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.338l1.634 1.14");
}

.vvwmaab9t {
  stop-color: var(--svg-color--e4c0a9, #E4C0A9);
  stop-opacity: 0;
}

.vxc8-2g3s {
  stop-color: var(--svg-color--9f6c83, #9F6C83);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w73pusboq {
  d: path("M8.41 5.768c.46-.706 1.536-.902 2.05-.902l.633 1.225c-.261.007-.472.138-.628.358c-.221 1.348-1.643 2.328-2.327 2.65c-.421-1.473-.325-2.413.273-3.331");
}

.wagk6dfaq {
  stop-color: var(--svg-color--966be0, #966BE0);
}

.wcbvx-n_a {
  stop-color: var(--svg-color--89579c, #89579C);
}

.wdwsowbvt {
  stop-color: var(--svg-color--c68882, #C68882);
}

.wi8a08bum {
  stop-color: var(--svg-color--785191, #785191);
  stop-opacity: 0;
}

.wn4a04bkk {
  fill: var(--svg-color--9c84d0, #9C84D0);
  d: path("m29.145 25.387l-4.94-6.05l-3.16 8.57z");
}

.wpapq1b-u {
  stop-color: var(--svg-color--161716, #161716);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x7g1thl-m {
  d: path("M10.214 21.734c-.284.88-1.448 1.292-2.6.921c-1.152-.372-1.793-1.178-1.573-2.266c.18-.888.884-1.75 2.738-1.24c1.153.372 1.719 1.705 1.435 2.585");
}

.x9dlezr0n {
  d: path("M18.998 26.83a.15.15 0 0 1 .15-.15h.643v3.368h-.793z");
}

.x9s6ceaht {
  stop-color: var(--svg-color--b087f9, #B087F9);
  stop-opacity: 0;
}

.xaulv1bog {
  stop-color: var(--svg-color--eec1af, #EEC1AF);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xdt63zb6q {
  stop-color: var(--svg-color--dba48c, #DBA48C);
  stop-opacity: 0;
}

.xk7cvlbih {
  stop-color: var(--svg-color--cc9e96, #CC9E96);
  stop-opacity: 0;
}

.xlapwpzgi {
  d: path("m14.149 10.57l-.224 1.805a.55.55 0 0 0 .651.608l.79-.143a.553.553 0 0 0 .396-.798l-.844-1.612c-.183-.358-.718-.261-.769.14");
}

.xohjverxe {
  stop-color: var(--svg-color--ce9989, #CE9989);
}

.xpf_69b1t {
  stop-color: var(--svg-color--ffc9b1, #FFC9B1);
}

.xtm-pfbxr {
  d: path("M15.815 10.385c.125.117.497.339.98.286c.484-.052.91-.521 1.019-.698");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y-w2tsblc {
  stop-color: var(--svg-color--dba48c, #DBA48C);
}

.y-ymn0bhn {
  stop-color: var(--svg-color--755994, #755994);
}

.yizrp5b2e {
  d: path("M21.835 24.067c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yyn9swbvh {
  stop-color: var(--svg-color--784787, #784787);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z1zjblq2q {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
  stop-opacity: 0;
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z6zfulbza {
  stop-color: var(--svg-color--c07e7e, #C07E7E);
}

.zbwshaccu {
  stop-color: var(--svg-color--875ab4, #875AB4);
}

.ze98a9f-u {
  fill: var(--svg-color--232121, #232121);
  d: path("M8.41 5.768c.46-.706 1.536-.902 2.05-.902l.633 1.225c-.261.007-.472.138-.628.358c-.221 1.348-1.643 2.328-2.327 2.65c-.421-1.473-.325-2.413.273-3.331");
}

.zf9ki4bnc {
  d: path("M17.69 9.809c-.077.01-.134.058-.182.125a1.06 1.06 0 0 1-.71.49a.97.97 0 0 1-.827-.221a.28.28 0 0 0-.21-.058a.256.256 0 0 0-.116.451c.336.279.787.413 1.248.327a1.53 1.53 0 0 0 1.066-.74c.106-.182-.058-.412-.269-.374");
}

.zg166u5-a {
  d: path("M10.183 13.335a1.644 1.644 0 1 0-.588-3.235a1.644 1.644 0 0 0 .588 3.235");
}

</style>
