<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuXvbMe)"><path fill="url(#iC1oNij)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#iRcF8Gc)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#iv0dTNc)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#iCyUzjd)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#ivSRHUb)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#iMHxduc)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#i3WdYoc)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#iB3HTXT)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#i84DoXb)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#iiDkNhb)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#iChNtUb)" clip-rule="evenodd" class="jssopz0kt"/><path fill="url(#iaiqlFc)" clip-rule="evenodd" class="jssopz0kt"/></g><rect fill="url(#iGKrojZ)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#i6D9s0c)"><path class="snq5xhi6c"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#ijndqpE)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#ih4xptb)" class="b1yazzwzl"/><path fill="url(#iN28qhb)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#iOlQRPr)"><path fill="url(#ikclHuc)" class="ga-j-qbpm"/><path fill="url(#iqSctJd)" class="ga-j-qbpm"/><path fill="url(#iZVep2c)" class="ga-j-qbpm"/></g><g filter="url(#iFNsSVC)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#iA0XN4g)" class="qexsyge6i"/><path fill="url(#is6z78C)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iSesIBc)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#iM54zqb)"><path fill="url(#i55AUOe)" class="dc-w_nb2z"/><path fill="url(#i136FHe)" class="dc-w_nb2z"/></g><g filter="url(#ilRG41d)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#iy7BSLc)"><path fill="url(#if2UIRn)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="stz6elb6u"/><path fill="url(#iCqAaCc)" class="eikeckbha"/><path fill="url(#iTEnVmd)" class="eikeckbha"/><path clip-rule="evenodd" class="qc5t8db-b"/><path fill="url(#i6NSaLc)" clip-rule="evenodd" class="x99s9tbej"/><path clip-rule="evenodd" class="x5036tbci"/><path fill="url(#iegrDeg)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="h8mf77buf"/><path fill="url(#iI5xoGs)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="n89_5nb9r"/><path fill="url(#iiMj71d)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#i0vUcqd)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#iLfl5ac)"><path class="tmtee3wvy"/><path fill="url(#iQBvayU)" class="p3ru7q3ze"/></g><path fill="url(#i3EK4rb)" class="p3ru7q3ze"/><path fill="url(#iGUHBdd)" clip-rule="evenodd" class="y_4pajl7d"/><g filter="url(#iuKjaxd)"><path class="rudj2xgsn"/></g><g filter="url(#iDnXP4c)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><g filter="url(#ibTKLyG)"><path fill="url(#iEroUvc)" class="jlkvfe52v"/></g><path fill="url(#ijsIzob)" class="jlkvfe52v"/><g filter="url(#i85PMNd)"><path fill="url(#ip9HXqb)" class="jlocb73il"/><path fill="url(#iwLqVRC)" class="jlocb73il"/></g><g filter="url(#iu2U0Hd)"><path class="xbqa9ohdr"/><path fill="url(#iEOxuRd)" class="x79jvhp6u"/></g><g filter="url(#iYCS5wc)"><path class="as3742b3x"/><path fill="url(#i0DOM1b)" class="g-f9k9b2p"/></g><g filter="url(#iqtyvke)"><path fill="url(#inhyh4b)" class="ujdb81b3r"/><path fill="url(#i1dKJCc)" class="ujdb81b3r"/><path fill="url(#i0i2SMe)" class="ujdb81b3r"/><path fill="url(#i5lojee)" class="ujdb81b3r"/><path fill="url(#iHdw5Nn)" class="ujdb81b3r"/><path fill="url(#iLNjM8b)" class="ujdb81b3r"/><path fill="url(#imo8Zoc)" class="ujdb81b3r"/><path fill="url(#i4L8Yme)" class="ujdb81b3r"/></g><path fill="url(#iGKrd3n)" class="ujdb81b3r"/><g filter="url(#i5SVfHc)"><path class="ot1m02b_g"/></g><g filter="url(#iItttVb)"><path class="de421_bcp"/><path fill="url(#iNV3isc)" class="fl_kheu2n"/><path fill="url(#ioAQ5sc)" class="fl_kheu2n"/><path fill="url(#ixtB39b)" class="fl_kheu2n"/><path fill="url(#iYb29Ke)" class="fl_kheu2n"/></g><g filter="url(#ibhmepd)"><path stroke="url(#ieg1LCO)" class="ga1pm_08j"/></g><path class="ncwjxzb-n"/><g filter="url(#iysBDjc)"><path class="fyjsfe3ru"/></g><g filter="url(#i6LrSYc)"><path class="tgp791olo"/></g><g filter="url(#i1ASFzd)"><path class="rbw352bgp"/></g><g filter="url(#i904xIc)"><path clip-rule="evenodd" class="s9c_s9bsq"/></g><path class="gmzf7juyw"/><path fill="url(#iwFtg6b)" class="cfoy7qzgi"/><path class="vhcjckh5p"/><g filter="url(#ihYrOdb)"><path class="gohpl1bvz"/><path fill="url(#iFDCe6c)" class="hbuwmac3d"/></g><g filter="url(#iKGEILe)"><path fill="url(#iKpxTvc)" class="bhz3q68sw"/></g><path class="up_l-ccup"/><path fill="url(#ilwSpNE)" class="hefragy-q"/><path class="g5k8ascqf"/><g filter="url(#i4SWB2b)"><path fill="url(#iL98SHb)" class="kx3ezibzu"/></g><g filter="url(#ia2Mi7b)"><ellipse transform="rotate(-27.914 11.808 5.692)" class="g-d40iz0h"/><ellipse fill="url(#iYFyxfd)" transform="rotate(-27.914 11.808 5.692)" class="s3hm2xbwi"/></g><g filter="url(#iZ5l5Pe)"><path class="sy7nw-bdj"/></g><g filter="url(#ikixdsd)"><path class="vrir20ids"/></g><g filter="url(#i3cmqZd)"><path class="vwey1bbjd"/><path fill="url(#iCAV9pc)" class="lg51uhbjp"/><path fill="url(#iuLtplt)" class="lg51uhbjp"/></g><g filter="url(#ir6yq3b)"><path class="ztrd4680v"/><path fill="url(#i66yZGc)" class="xq1qejy-l"/><path fill="url(#iDq4P1c)" class="xq1qejy-l"/></g><g filter="url(#iwXHVfd)"><path class="yxyxyjh2u"/></g><g filter="url(#ilwxjYb)"><path class="bt6l40b-x"/></g><defs><radialGradient id="iRcF8Gc" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 3.262 9.18)scale(2.10124 2.62487)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iv0dTNc" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.64 5.395)scale(1.58884 2.08761)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iCyUzjd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 3.848 5.702)scale(.98338 .75509)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="ivSRHUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5897 .96495 -.67972 -.4154 10.923 5.183)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iMHxduc" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 3.735 10.533)scale(1.3497 1.87359)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i3WdYoc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 7.119 4.868)scale(.9314 1.30162)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iB3HTXT" cx="0" cy="0" r="1" gradientTransform="rotate(163.778 7.78 3.975)scale(.87731 1.82954)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="i84DoXb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 7.6 4.58)scale(1.32616 1.68934)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iiDkNhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.41324 -1.21092 .95777 -.32685 15.091 4.507)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iChNtUb" cx="0" cy="0" r="1" gradientTransform="matrix(.68715 .07208 -.11679 1.11338 10.123 5.602)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iaiqlFc" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 9.752 -3.446)scale(1.73527 .62629)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iGKrojZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="cu-ecjbbc"/><stop offset="1" class="qb2q8bclu"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="ih4xptb" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="illubsb_v"/><stop offset="1" class="guxv2rb-g"/></radialGradient><radialGradient id="iN28qhb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="xs_h82bcz"/><stop offset="1" class="q7m_lo14i"/></radialGradient><radialGradient id="ikclHuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="b1kvifv3j"/><stop offset="1" class="w__bqyylv"/></radialGradient><radialGradient id="iqSctJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iZVep2c" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iA0XN4g" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="akiqkcbyd"/><stop offset="1" class="pydwqlfbr"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="i55AUOe" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uwn_p0-dn"/><stop offset="1" class="sa6pubcic"/></radialGradient><radialGradient id="if2UIRn" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="diezlkbrv"/><stop offset="1" class="qrb0sjbdn"/></radialGradient><radialGradient id="iCqAaCc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="mf5e09ark"/><stop offset="1" class="kqsf2kvhx"/></radialGradient><radialGradient id="iTEnVmd" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="lakgv5bqc"/><stop offset=".945" class="p3cy4lbfc"/></radialGradient><radialGradient id="i6NSaLc" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iegrDeg" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iI5xoGs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iiMj71d" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="i0vUcqd" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="nm4xmabvr"/><stop offset="1" class="b4mlr_y9s"/></radialGradient><radialGradient id="i3EK4rb" cx="0" cy="0" r="1" gradientTransform="rotate(106.912 4.941 9.22)scale(3.20093 4.86981)" gradientUnits="userSpaceOnUse"><stop class="env4r_bwx"/><stop offset="1" class="spg8_pgop"/></radialGradient><radialGradient id="iGUHBdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="wloocxb2w"/><stop offset="1" class="g8dpdlbxs"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="ijsIzob" cx="0" cy="0" r="1" gradientTransform="matrix(-.29868 -.54987 .62308 -.33844 10.609 6.743)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="ip9HXqb" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 21.72 -31)scale(1.24924 1.52526)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iwLqVRC" cx="0" cy="0" r="1" gradientTransform="matrix(.5514 0 0 .2374 15.188 5.228)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iEOxuRd" cx="0" cy="0" r="1" gradientTransform="matrix(.68988 -.05132 .04012 .5393 14.936 6.06)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i0DOM1b" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.413 3.004)scale(.48248)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="inhyh4b" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.485 4.443)scale(3.27225 4.37985)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="i1dKJCc" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 6.268 4.53)scale(1.08836 .75792)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="i0i2SMe" cx="0" cy="0" r="1" gradientTransform="matrix(.58902 -1.7949 2.27739 .74736 11.941 8.736)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i5lojee" cx="0" cy="0" r="1" gradientTransform="rotate(99.884 4.356 8.418)scale(3.41961 4.27448)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="iHdw5Nn" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 6.56 3.945)scale(3.21543 5.53598)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iLNjM8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.5258 .6453 0 13.98 5.571)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="imo8Zoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.5997 .6873 0 11.98 5.467)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="i4L8Yme" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 5.052 7.45)scale(1.52699 1.22184)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iGKrd3n" cx="0" cy="0" r="1" gradientTransform="matrix(-.58725 0 0 -2.94502 15.257 6.251)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iNV3isc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20814 -.93392 .28783 -.06415 13.287 6.583)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iYb29Ke" cx="0" cy="0" r="1" gradientTransform="matrix(-.35611 0 0 -.09956 13.178 6.68)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iwFtg6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3707 -.58963 0 13.926 5.735)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iFDCe6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.10596 -.13655 .188 -.14589 13.822 5.774)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilwSpNE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3707 -.58964 0 11.932 5.735)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iYFyxfd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 8.773 -2.891)scale(.22577 .27138)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCAV9pc" cx="0" cy="0" r="1" gradientTransform="matrix(.57663 -1.25897 .64406 .29499 10.344 4.766)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="iuLtplt" cx="0" cy="0" r="1" gradientTransform="matrix(.52523 -.9025 .48452 .28197 11.124 4.318)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="i66yZGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.96496 2.00648 -3.28048 -1.57766 13.802 2.387)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iDq4P1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.0961 .62468 -1.34397 -.20676 13.025 2.556)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="iuXvbMe" width="7.112" height="7.612" x="9.498" y="1.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="i6D9s0c" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.341176 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="ijndqpE" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="iOlQRPr" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.341176 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="iFNsSVC" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="iSesIBc" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="iM54zqb" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="ilRG41d" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="iy7BSLc" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.419608 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23230" result="effect2_innerShadow_3987_23230"/></filter><filter id="iLfl5ac" width="8.236" height="9.786" x="11.582" y="7.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.262745 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23230" result="effect2_innerShadow_3987_23230"/></filter><filter id="iuKjaxd" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".25"/></filter><filter id="iDnXP4c" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="ibTKLyG" width="1.62" height="1.47" x="10.053" y="5.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="i85PMNd" width="1.47" height="1.72" x="14.399" y="5.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="iu2U0Hd" width="1.982" height="1.982" x="14.144" y="5.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".25"/></filter><filter id="iYCS5wc" width="1.682" height="1.682" x="9.956" y="5.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".175"/></filter><filter id="iqtyvke" width="4.656" height="5.07" x="10.601" y="3.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="i5SVfHc" width="1.858" height="2.225" x="11.926" y="5.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".25"/></filter><filter id="iItttVb" width="1.058" height="1.425" x="12.4" y="5.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".05"/></filter><filter id="ibhmepd" width="1.909" height=".915" x="11.975" y="6.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".05"/></filter><filter id="iysBDjc" width="1.48" height=".587" x="13.251" y="5.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="i6LrSYc" width="1.48" height=".587" x="11.127" y="5.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="i1ASFzd" width="1.229" height=".607" x="11.189" y="4.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="i904xIc" width="1.229" height=".607" x="13.664" y="4.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><filter id="ihYrOdb" width=".468" height=".427" x="13.536" y="5.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".05"/></filter><filter id="iKGEILe" width=".624" height=".635" x="13.866" y="5.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".1"/></filter><filter id="i4SWB2b" width=".668" height=".693" x="11.836" y="5.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".1"/></filter><filter id="ia2Mi7b" width=".526" height=".43" x="11.545" y="5.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".05"/></filter><filter id="iZ5l5Pe" width="1.059" height=".473" x="13.665" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".05"/></filter><filter id="ikixdsd" width="1.059" height=".473" x="11.174" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".05"/></filter><filter id="i3cmqZd" width="2.309" height="2.447" x="9.959" y="2.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/><feGaussianBlur result="effect2_foregroundBlur_3987_23230" stdDeviation=".125"/></filter><filter id="ir6yq3b" width="4.205" height="2.763" x="11.318" y="2.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/><feGaussianBlur result="effect2_foregroundBlur_3987_23230" stdDeviation=".075"/></filter><filter id="iwXHVfd" width="2.751" height="1.355" x="12.756" y="3.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23230" stdDeviation=".125"/></filter><filter id="ilwxjYb" width="1.518" height=".691" x="11.081" y="3.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.345098 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23230"/></filter><linearGradient id="iC1oNij" x1="15.073" x2="12.271" y1="2.831" y2="7.748" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="is6z78C" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="va2m8brjv"/><stop offset="1" class="f3-q9vb4v"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="i136FHe" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ivbdbpjuw"/><stop offset="1" class="zovioqy4e"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iQBvayU" x1="18.384" x2="14.604" y1="15.165" y2="16.372" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uov-5vb3w"/><stop offset="1" class="mzo6olgul"/></linearGradient><linearGradient id="iEroUvc" x1="10.053" x2="10.902" y1="6.048" y2="6.048" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="ioAQ5sc" x1="12.5" x2="12.929" y1="6.616" y2="6.616" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="ixtB39b" x1="12.929" x2="12.929" y1="6.939" y2="6.653" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="ieg1LCO" x1="12.443" x2="12.653" y1="7.626" y2="7.3" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iKpxTvc" x1="14.282" x2="14.138" y1="5.76" y2="5.848" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iL98SHb" x1="12.272" x2="12.129" y1="5.76" y2="5.848" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bouncing-ball-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.akiqkcbyd {
  stop-color: var(--svg-color--af8173, #AF8173);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.as3742b3x {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M10.797 6.499a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b1kvifv3j {
  stop-color: var(--svg-color--8668c7, #8668C7);
}

.b1yazzwzl {
  d: path("m11 20.604l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.646 1.008-1.82");
}

.b1ysgbbus {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.469px;
  rx: 0.33px;
}

.b4mlr_y9s {
  stop-color: var(--svg-color--b08971, #B08971);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bhz3q68sw {
  d: path("M14.29 5.871a.4.4 0 0 0-.105-.211l-.12.13l.054.105z");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bt6l40b-x {
  fill: var(--svg-color--9f97a6, #9F97A6);
  d: path("M12.598 4.45h-1.517a1.05 1.05 0 0 0 .469-.528l.037-.089a.12.12 0 0 1 .212-.023c.199.292.48.512.8.64");
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.cfoy7qzgi {
  d: path("M13.927 5.517a.408.408 0 0 1 .393.516h-.788a.41.41 0 0 1 .395-.515");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.dc-w_nb2z {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.255");
}

.de421_bcp {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m12.754 5.843l-.242.777c-.05.16.069.32.237.32h.36a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.172-.295-.172-.35 0");
}

.diezlkbrv {
  stop-color: var(--svg-color--9b7264, #9B7264);
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.env4r_bwx {
  stop-color: var(--svg-color--966bb1, #966BB1);
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f3-q9vb4v {
  stop-color: var(--svg-color--ad7c77, #AD7C77);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fl_kheu2n {
  d: path("m12.754 5.843l-.242.777c-.05.16.069.32.237.32h.36a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.172-.295-.172-.35 0");
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.fyjsfe3ru {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M13.45 5.748c.122-.213.307-.382.703-.382c.174 0 .342.049.49.169c.123.1.107.226.012.274l-.254.145c-.298-.097-.627-.11-.95-.206");
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g-d40iz0h {
  cx: 11.808px;
  cy: 5.692px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.178px;
  ry: 0.09px;
}

.g-f9k9b2p {
  d: path("M10.797 6.499a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g5k8ascqf {
  fill: var(--svg-color--000, #000);
  d: path("M12.165 5.925a.233.233 0 0 0-.234-.233a.233.233 0 0 0-.207.34h.413a.23.23 0 0 0 .028-.107");
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.g8dpdlbxs {
  stop-color: var(--svg-color--a7836a, #A7836A);
  stop-opacity: 0;
}

.ga-j-qbpm {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.06c.12-.109.433-.272.71-.06c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.ga1pm_08j {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.93 7.338c-.239 0-.463-.057-.65-.157c-.065-.033-.134.04-.093.1a.883.883 0 0 0 1.484 0c.04-.062-.028-.133-.092-.1c-.188.1-.41.157-.65.157Z");
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.gmzf7juyw {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.021 5.393a.64.64 0 0 1 .62.484a.126.126 0 0 1-.123.156h-1.02a.105.105 0 0 1-.103-.125a.64.64 0 0 1 .626-.515");
}

.gohpl1bvz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.897 5.604c.029.038-.032.086-.1.137c-.07.052-.121.088-.15.05c-.03-.04.003-.113.072-.164c.07-.052.149-.062.178-.023");
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.guxv2rb-g {
  stop-color: var(--svg-color--8d6353, #8D6353);
}

.h8mf77buf {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.hbuwmac3d {
  d: path("M13.897 5.604c.029.038-.032.086-.1.137c-.07.052-.121.088-.15.05c-.03-.04.003-.113.072-.164c.07-.052.149-.062.178-.023");
}

.hefragy-q {
  d: path("M11.931 5.517a.408.408 0 0 0-.393.516h.788a.41.41 0 0 0-.395-.515");
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.illubsb_v {
  stop-color: var(--svg-color--bd8b7f, #BD8B7F);
}

.ivbdbpjuw {
  stop-color: var(--svg-color--614a93, #614A93);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.jfk78yx3r {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
}

.jlkvfe52v {
  d: path("M10.788 6.743a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.jlocb73il {
  d: path("M15.135 6.743a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jssopz0kt {
  fill-rule: evenodd;
  d: path("M16.212 6.652a1.5 1.5 0 0 0 .025-1.248h.003a1.5 1.5 0 0 0-.129-.235v-.001a1.5 1.5 0 0 1-.241-.81v-.004c0-.832-.675-1.507-1.507-1.507a.25.25 0 0 1-.209-.107a1.51 1.51 0 0 0-2.45 0a.26.26 0 0 1-.208.107h-.04a1.51 1.51 0 0 0-1.468 1.507v.005c0 .286-.083.568-.24.809l-.001.002a1.51 1.51 0 0 0-.1 1.482a.24.24 0 0 1 0 .208a1.468 1.468 0 0 0 1.322 2.113h3.92a1.468 1.468 0 0 0 1.323-2.113a.24.24 0 0 1 0-.208m-5.602-1.22h-.005l.547 1.075c.057 1.28.557 0 1.777 0s1.753 1.426 1.81.145l.518-1.46c-.024-.57-.437-.61-.519-.61h-1.471c-.581 0-1.13-.284-1.457-.764a.12.12 0 0 0-.211.023l-.037.089c-.104.256-.3.452-.544.564l-.023.01l-.024.009c-.108.056-.36.224-.37.657l.005.14z");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.kqsf2kvhx {
  stop-color: var(--svg-color--996d5c, #996D5C);
  stop-opacity: 0;
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kx3ezibzu {
  d: path("M12.304 5.877c0-.132-.107-.22-.136-.246l-.132.127l.08.166z");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lakgv5bqc {
  stop-color: var(--svg-color--b38970, #B38970);
  stop-opacity: 0;
}

.lg51uhbjp {
  d: path("M10.613 3.272c.259-.274.748-.274.974-.233l.18.59c-.115-.019-.134-.001-.221.083c-.063.5-.629.802-1.319 1.004c-.068-.682.05-1.088.386-1.444");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mf5e09ark {
  stop-color: var(--svg-color--7e4944, #7E4944);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.mzo6olgul {
  stop-color: var(--svg-color--8568c5, #8568C5);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n89_5nb9r {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.ncwjxzb-n {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M12.93 7.338c-.239 0-.463-.057-.65-.157c-.065-.033-.134.04-.093.1a.883.883 0 0 0 1.484 0c.04-.062-.028-.133-.092-.1c-.188.1-.41.157-.65.157");
}

.nm4xmabvr {
  stop-color: var(--svg-color--c09989, #C09989);
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of70meq1k {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.ot1m02b_g {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m12.75 5.906l-.312.777c-.05.16.069.32.237.32h.36a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.172-.226-.172-.28 0");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p3cy4lbfc {
  stop-color: var(--svg-color--b38970, #B38970);
}

.p3ru7q3ze {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.pydwqlfbr {
  stop-color: var(--svg-color--9c7460, #9C7460);
}

.q7m_lo14i {
  stop-color: var(--svg-color--925971, #925971);
}

.qb2q8bclu {
  stop-color: var(--svg-color--8a494a, #8A494A);
}

.qc5t8db-b {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qpbv0c39t {
  stop-color: var(--svg-color--9c5c64, #9C5C64);
}

.qrb0sjbdn {
  stop-color: var(--svg-color--8b6757, #8B6757);
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rbw352bgp {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m11.377 5.196l-.002.001a.123.123 0 0 1-.126-.21l.002-.001l.004-.003l.015-.008l.053-.027a2 2 0 0 1 .187-.074c.155-.05.373-.091.607-.05a.122.122 0 1 1-.043.242c-.182-.033-.357 0-.49.042a1.3 1.3 0 0 0-.197.082z");
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rudj2xgsn {
  fill: var(--svg-color--c8a08c, #C8A08C);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s3hm2xbwi {
  cx: 11.808px;
  cy: 5.692px;
  rx: 0.178px;
  ry: 0.09px;
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.s9c_s9bsq {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m14.634 4.987l-.063.105za.123.123 0 0 1-.126.21l-.002-.001l-.01-.006l-.042-.02a1 1 0 0 0-.156-.062a1.04 1.04 0 0 0-.49-.042a.123.123 0 1 1-.042-.242c.234-.041.451 0 .607.05a1.5 1.5 0 0 1 .24.1l.015.01l.004.002z");
}

.sa6pubcic {
  stop-color: var(--svg-color--8466c4, #8466C4);
}

.sa73rem9k {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sepv3nkwr {
  d: path("M5.527 16.647c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.snq5xhi6c {
  fill: var(--svg-color--b38c70, #B38C70);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.spg8_pgop {
  stop-color: var(--svg-color--966bb1, #966BB1);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.stz6elb6u {
  fill: var(--svg-color--caa18d, #CAA18D);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.sy7nw-bdj {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.815 4.924c.148-.036.514-.018.76.157");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tgp791olo {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M12.407 5.748c-.121-.213-.305-.382-.702-.382a.76.76 0 0 0-.49.169c-.123.1-.107.226-.012.274l.255.145c.297-.097.627-.11.95-.206");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tmtee3wvy {
  fill: var(--svg-color--876cc6, #876CC6);
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ujdb81b3r {
  d: path("M10.605 5.431h.005l-.004-.121l-.005-.14c.01-.433.262-.601.37-.657l.024-.01l.023-.009c.244-.112.44-.307.543-.564l.038-.088a.12.12 0 0 1 .21-.024c.329.48.877.765 1.458.765h1.471c.082 0 .495.04.52.608l-.055 1.405c-.056 1.28-1.056 2.14-2.277 2.14c-1.22 0-2.22-.86-2.277-2.14z");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uov-5vb3w {
  stop-color: var(--svg-color--9782d0, #9782D0);
}

.up_l-ccup {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.837 5.393a.64.64 0 0 0-.62.484c-.02.08.041.156.123.156h1.02c.064 0 .116-.06.103-.125a.64.64 0 0 0-.626-.515");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.uwn_p0-dn {
  stop-color: var(--svg-color--8366c4, #8366C4);
}

.v_thlccbr {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.va2m8brjv {
  stop-color: var(--svg-color--9a6183, #9A6183);
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vhcjckh5p {
  fill: var(--svg-color--000, #000);
  d: path("M13.694 5.925c0-.13.103-.233.233-.233a.233.233 0 0 1 .208.34h-.414a.2.2 0 0 1-.027-.107");
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vrir20ids {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.083 4.924a1.1 1.1 0 0 0-.759.157");
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vwey1bbjd {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.613 3.272c.259-.274.748-.274.974-.233l.18.59c-.115-.019-.134-.001-.221.083c-.063.5-.629.802-1.319 1.004c-.068-.682.05-1.088.386-1.444");
}

.w__bqyylv {
  stop-color: var(--svg-color--8768cb, #8768CB);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wloocxb2w {
  stop-color: var(--svg-color--a7836a, #A7836A);
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x5036tbci {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x79jvhp6u {
  d: path("M15.135 6.499a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.xbqa9ohdr {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M15.135 6.499a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xjnuavuoc {
  stop-color: var(--svg-color--9c5c64, #9C5C64);
  stop-opacity: 0;
}

.xq1qejy-l {
  d: path("M12.653 2.449c-.517-.115-.982.402-1.035.593c.48 1.62 1.696 1.531 2.896 1.398c.719-.08.797.247.858.406c0-1.797-1.528-2.135-2.706-2.395z");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs_h82bcz {
  stop-color: var(--svg-color--925971, #925971);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yxyxyjh2u {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m14.029 4.098l-.652.12a.314.314 0 1 1-.057-.624h1.07c.632 0 .842.637.867.855a1.44 1.44 0 0 0-1.228-.351");
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zovioqy4e {
  stop-color: var(--svg-color--614a93, #614A93);
  stop-opacity: 0;
}

.ztrd4680v {
  fill: var(--svg-color--553836, #553836);
  d: path("M12.653 2.449c-.517-.115-.982.402-1.035.593c.48 1.62 1.696 1.531 2.896 1.398c.719-.08.797.247.858.406c0-1.797-1.528-2.135-2.706-2.395z");
}

</style>
