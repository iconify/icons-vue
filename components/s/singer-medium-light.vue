<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iF2WqUc)"><path class="jcqxl8b5s"/><path fill="url(#iXFlnfU)" class="lo-fmbbpb"/></g><path fill="url(#i3O6tsw)" class="ud57h_lxk"/><path fill="url(#iWeaGge)" class="ud57h_lxk"/><path fill="url(#i8ASabe)" class="i4c7gf1nk"/><path fill="url(#iBPwj9b)" class="i4c7gf1nk"/><path fill="url(#iA0fDPb)" class="g-2q6vgre"/><path fill="url(#iLIsCdb)" class="g-2q6vgre"/><path fill="url(#ic6GODe)" class="g-2q6vgre"/><path fill="url(#idgJIee)" class="g-2q6vgre"/><path fill="url(#iDyZIMe)" class="u0q_obb8r"/><path fill="url(#i9uzLSc)" class="u0q_obb8r"/><path fill="url(#ibclZGb)" class="u0q_obb8r"/><path fill="url(#iQ98CNC)" class="u0q_obb8r"/><path fill="url(#i5xJVwd)" class="u0q_obb8r"/><path fill="url(#iQx0jab)" class="w4q61yb8g"/><path fill="url(#ikloHad)" class="wiodrpp6l"/><path fill="url(#iFyhDHb)" class="cun4e9f-e"/><path fill="url(#iIUy4pe)" class="m9f_4xbpp"/><path fill="url(#i04aD5b)" class="m9f_4xbpp"/><path fill="url(#itAqvRc)" class="m9f_4xbpp"/><path fill="url(#iv6Ggpy)" class="hermhta_f"/><path fill="url(#ix0q1tb)" class="hermhta_f"/><path fill="url(#iI9zMWX)" class="afufpnb6s"/><path fill="url(#iCkmqGB)" class="afufpnb6s"/><path fill="url(#iSFmeKc)" class="afufpnb6s"/><path fill="url(#iZvUCMe)" class="afufpnb6s"/><g filter="url(#idiTDoe)"><path fill="url(#iJh6oKe)" class="rgp37jb6d"/><path fill="url(#ixrxomN)" class="rgp37jb6d"/><path fill="url(#imRN4ac)" class="rgp37jb6d"/></g><path fill="url(#ij3ewQb)" class="pej7ph77g"/><path fill="url(#iH4wEId)" class="pej7ph77g"/><path fill="url(#i7520Ab)" class="pej7ph77g"/><g filter="url(#io23bCe)"><path fill="url(#iqvqfsd)" class="flvbp4biy"/></g><g filter="url(#ic9PWpb)"><circle fill="url(#iV2P80b)" class="a6y6-g7uw"/></g><g filter="url(#iiklHqb)"><circle fill="url(#iyxkK2d)" class="tyj09bbmz"/></g><g filter="url(#iidCpQs)"><path fill="url(#i7E2VTd)" class="fk97krmxu"/><path fill="url(#iw4u0fe)" class="fk97krmxu"/><path fill="url(#i8SWTub)" class="fk97krmxu"/><path fill="url(#iJMZOEd)" class="fk97krmxu"/><path fill="url(#i8rKfpc)" class="fk97krmxu"/></g><path fill="url(#ijAJHNc)" class="fk97krmxu"/><g filter="url(#iafKgHd)"><path stroke="url(#iVufoFd)" class="d0mmm9b4e"/></g><g filter="url(#iknPTMr)"><path stroke="url(#iX7yrql)" class="t4qzv1a_c"/></g><g filter="url(#iYAB6oe)"><path stroke="url(#iwTMoQL)" class="gu_vetbpq"/></g><path fill="url(#iA8yXke)" class="rua3ie5oc"/><path fill="url(#ipv3Kme)" class="ke03wbpey"/><path fill="url(#isiIVbd)" class="ke03wbpey"/><path fill="url(#ipv3Kme)" class="ke03wbpey"/><path fill="url(#isiIVbd)" class="ke03wbpey"/><g filter="url(#i9chyJc)"><path fill="url(#ivxc8iC)" class="c-_aqkbog"/></g><path fill="url(#iofnrnT)" class="c-_aqkbog"/><path fill="url(#i6dY5Xb)" class="c-_aqkbog"/><path fill="url(#iHri4hb)" class="c-_aqkbog"/><path fill="url(#i1NJxnb)" class="c-_aqkbog"/><path fill="url(#iNWLxTb)" class="c-_aqkbog"/><path fill="url(#il8FCuc)" class="c-_aqkbog"/><path fill="url(#imeQ2kJ)" class="c-_aqkbog"/><path fill="url(#i2rYQ4d)" class="c-_aqkbog"/><g filter="url(#ii5IqVd)"><path class="pi7-9gb0y"/></g><g filter="url(#iLiuWGd)"><path fill="url(#ip0aqoR)" class="savumudgh"/><path fill="url(#iWSRNrW)" class="savumudgh"/><path fill="url(#i0cKOie)" class="savumudgh"/><path fill="url(#ie9s1lb)" class="savumudgh"/></g><path fill="url(#iYf4G3b)" class="savumudgh"/><path fill="url(#insIRpb)" class="savumudgh"/><path fill="url(#i7eNm5c)" class="nu2pufskf"/><path fill="url(#ib6Qk8c)" class="nu2pufskf"/><g filter="url(#iyhsFyb)"><path stroke="url(#iMhAA2c)" class="cfdbxbcxz"/></g><path fill="url(#iN1shpb)" class="j66pihcrc"/><g filter="url(#ieE0cvM)"><path fill="url(#iBayF0v)" class="sk6_ryb5x"/><path fill="url(#iVQh0ge)" class="sk6_ryb5x"/><path fill="url(#ieXMjmb)" class="sk6_ryb5x"/><path fill="url(#iXWEbVb)" class="sk6_ryb5x"/><path fill="url(#isCwmfc)" class="sk6_ryb5x"/></g><g filter="url(#itiyZQc)"><path class="hvpy_wbbn"/></g><g filter="url(#iIbEXhe)"><path class="ta6hmvbrg"/></g><g filter="url(#iCUvRsb)"><path fill="url(#i1uZ8ez)" class="cqq24abxx"/><path fill="url(#i2nq3Gw)" class="cqq24abxx"/></g><g filter="url(#iWRhpze)"><path fill="url(#i8qlhkJ)" class="s1o5hac8o"/><path fill="url(#if6YEgc)" class="s1o5hac8o"/><path fill="url(#inWNrhb)" class="s1o5hac8o"/><path fill="url(#iMuyyqc)" class="s1o5hac8o"/><path fill="url(#i1B9NDd)" class="s1o5hac8o"/><path fill="url(#iii988b)" class="s1o5hac8o"/></g><path class="u74twqbgj"/><path fill="url(#iJJOmKb)" class="an8w2cz7u"/><path class="l7kvrebdp"/><g filter="url(#iUUNxtd)"><path class="cnw4ucbrh"/><path fill="url(#idEcOKb)" class="pdp7s61vg"/></g><g filter="url(#iLCYSeb)"><path fill="url(#iAK5h5d)" class="m18w-hohx"/></g><path class="q-b7edbvw"/><path fill="url(#iel9Lab)" class="g0fbzpbju"/><path class="jwhqis_ra"/><g filter="url(#iLp9kXJ)"><path fill="url(#iXlHs5d)" class="t9uwhgb4l"/></g><g filter="url(#i2i4dhC)"><ellipse transform="rotate(-27.914 12.696 11.32)" class="guyqgqb-l"/><ellipse fill="url(#it5mr2c)" transform="rotate(-27.914 12.696 11.32)" class="pxgdi68-a"/></g><path fill="url(#iMpOHsd)" class="glz1dlbql"/><path fill="url(#ijLXnCb)" class="glz1dlbql"/><path fill="url(#ihQtmGK)" class="glz1dlbql"/><path fill="url(#ilJziqe)" class="ebel0iswy"/><path fill="url(#ihI9njb)" class="ebel0iswy"/><g filter="url(#ivohudb)"><path class="k_bvcfbcc"/></g><g filter="url(#i60HyNs)"><path class="m86r8t2qn"/></g><g filter="url(#i2UIyve)"><path class="teyf2ebbe"/></g><g filter="url(#imGSbAd)"><path class="zu2i0fbof"/></g><defs><radialGradient id="i3O6tsw" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.614)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="i8ASabe" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.667 19.546)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="ic6GODe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 17.896)" gradientUnits="userSpaceOnUse"><stop class="mnp72frot"/><stop offset="1" class="l4rg4-bid"/></radialGradient><radialGradient id="i9uzLSc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.597 18.161 8.93)scale(6.81742 .9881)" gradientUnits="userSpaceOnUse"><stop class="rzqjthgas"/><stop offset="1" class="ejynn6b3w"/></radialGradient><radialGradient id="iQ98CNC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80897 .6578 -1.95135 -5.36624 12.187 17.781)" gradientUnits="userSpaceOnUse"><stop class="i03-jcbks"/><stop offset="1" class="m27qtcbgg"/></radialGradient><radialGradient id="iIUy4pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.106 20.262)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="qlsp8sbaz"/><stop offset=".838" class="w422gwoow"/></radialGradient><radialGradient id="i04aD5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.206)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="k-23bl_xw"/><stop offset=".937" class="f6id_baiq"/></radialGradient><radialGradient id="iv6Ggpy" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1394 1.4599 -1.43346 -2.10066 28.718 21.524)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="ix0q1tb" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.086 21.363)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="iCkmqGB" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.3 12.08)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iSFmeKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.211)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iZvUCMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.569)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="ixrxomN" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 16.96)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iqvqfsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 20.831)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="iV2P80b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39063 -2.6875 6.04551 -3.1282 15.925 20.105)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="pz-_6uplk"/><stop offset="1" class="ixm2pmbhy"/></radialGradient><radialGradient id="iyxkK2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5843 -1.90116 0 15.15 18.44)" gradientUnits="userSpaceOnUse"><stop class="xu32dvb5s"/><stop offset="1" class="ohzrjbbgt"/></radialGradient><radialGradient id="iw4u0fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.37)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i8SWTub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 24.788)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iJMZOEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.158)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i8rKfpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.64)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ijAJHNc" cx="0" cy="0" r="1" gradientTransform="rotate(120.493 7.968 19.756)scale(6.49967 4.40837)" gradientUnits="userSpaceOnUse"><stop class="hsdt12m1i"/><stop offset="1" class="v1bt46wqv"/></radialGradient><radialGradient id="iA8yXke" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 20.608 13.107)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="ipv3Kme" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 9.601 13.39)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="isiIVbd" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -2.456 12.634)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="ivxc8iC" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 17.957 12.332)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="i6dY5Xb" cx="0" cy="0" r="1" gradientTransform="scale(10.5475 12.7367)rotate(90 .478 1)" gradientUnits="userSpaceOnUse"><stop offset=".665" class="ch1e8sb3a"/><stop offset=".933" class="dz_8pl7dq"/></radialGradient><radialGradient id="iHri4hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 17.597 11.211)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="i1NJxnb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.71 -.588)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iNWLxTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 10.269 12.716)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="il8FCuc" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 9.297 9.33)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="imeQ2kJ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 14.995 16.404)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="i2rYQ4d" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 17.107 6.95)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="insIRpb" cx="0" cy="0" r="1" gradientTransform="rotate(135.131 5.554 9.465)scale(2.59561 1.64977)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="i7eNm5c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.666 6.713)" gradientUnits="userSpaceOnUse"><stop class="jy25td8rp"/><stop offset="1" class="xftsofb3t"/></radialGradient><radialGradient id="ib6Qk8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.134 11.182)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="iMhAA2c" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 20.342 -4.157)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iN1shpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.15 15.87)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iVQh0ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 9.92 10.75)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="ieXMjmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 20.01 10.75)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iXWEbVb" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.04 .463)scale(3.48023 1.85345)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="isCwmfc" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 14.245 2.88)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="i1uZ8ez" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.324 3.508)scale(4.04714 1.12642)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i2nq3Gw" cx="0" cy="0" r="1" gradientTransform="matrix(3.2182 -5.09542 5.6452 3.56544 9.719 9.083)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="i8qlhkJ" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .80083 -.44788 1.89356 18.77 5.483)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="if6YEgc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.044 -.796)scale(4.28182 2.38794)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="inWNrhb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.57741 -.93641 19.658 9.788)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iMuyyqc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 19.943 5.367)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="i1B9NDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 18.602 5.241)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iii988b" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 7.971 7.8)scale(4.25147 10.9633)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iJJOmKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90336 -1.06892 0 17.332 11.749)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="idEcOKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 17.104 11.5)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iel9Lab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90341 -1.06897 0 12.968 11.749)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="it5mr2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 12.68 11.634)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijLXnCb" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 19.767 11.429)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="ihQtmGK" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.128 11.974)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="ihI9njb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.556 5.664)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><linearGradient id="iXFlnfU" x1="16.901" x2="15.504" y1="26.136" y2="25.833" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iWeaGge" x1="7.199" x2="6.027" y1="25.935" y2="25.935" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iBPwj9b" x1="23.128" x2="23.77" y1="26.021" y2="25.989" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iA0fDPb" x1="22.77" x2="18.395" y1="16.006" y2="28.516" gradientUnits="userSpaceOnUse"><stop class="qm8srpk6b"/><stop offset="1" class="knnk86b5x"/></linearGradient><linearGradient id="iLIsCdb" x1="16.824" x2="17.431" y1="26.506" y2="26.57" gradientUnits="userSpaceOnUse"><stop class="o_frn_b6l"/><stop offset="1" class="ohgvqyqas"/></linearGradient><linearGradient id="idgJIee" x1="20.787" x2="20.787" y1="16.006" y2="16.828" gradientUnits="userSpaceOnUse"><stop offset=".165" class="oy7fe6bjb"/><stop offset="1" class="ivc982b0q"/></linearGradient><linearGradient id="iDyZIMe" x1="7.895" x2="11.895" y1="17.646" y2="28.896" gradientUnits="userSpaceOnUse"><stop class="e55i1-bjj"/><stop offset="1" class="rqyrdfbps"/></linearGradient><linearGradient id="ibclZGb" x1="8.35" x2="9.063" y1="15.259" y2="19.316" gradientUnits="userSpaceOnUse"><stop class="agyv0c9kf"/><stop offset="1" class="vxg8xmb_d"/></linearGradient><linearGradient id="i5xJVwd" x1="7.895" x2="8.309" y1="22.583" y2="22.38" gradientUnits="userSpaceOnUse"><stop class="maqiohbml"/><stop offset="1" class="qndc1xila"/></linearGradient><linearGradient id="iQx0jab" x1="23.395" x2="21.614" y1="26.052" y2="26.052" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="ikloHad" x1="8.114" x2="10.395" y1="27.864" y2="26.708" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="iFyhDHb" x1="15.111" x2="15.111" y1="17.406" y2="28.51" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="itAqvRc" x1="17.886" x2="15.925" y1="22.096" y2="21.768" gradientUnits="userSpaceOnUse"><stop offset=".196" class="kgt9ojbtf"/><stop offset=".671" class="m1nlemiqb"/></linearGradient><linearGradient id="iI9zMWX" x1="25.739" x2="25.739" y1="15.702" y2="19.759" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="iJh6oKe" x1="25.933" x2="25.792" y1="16.638" y2="17.841" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="imRN4ac" x1="23.236" x2="23.363" y1="16.575" y2="17.011" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="ij3ewQb" x1="26.936" x2="24.648" y1="21.145" y2="21.145" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iH4wEId" x1="24.466" x2="24.847" y1="20.987" y2="20.959" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="i7520Ab" x1="27.084" x2="26.822" y1="20.859" y2="20.835" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="i7E2VTd" x1="27.996" x2="23.128" y1="26.392" y2="26.392" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="iVufoFd" x1="23.742" x2="25.663" y1="24.189" y2="24.189" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iX7yrql" x1="23.742" x2="25.663" y1="25.631" y2="25.631" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iwTMoQL" x1="23.742" x2="25.663" y1="27.061" y2="27.061" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iofnrnT" x1="20.307" x2="15.954" y1="14.017" y2="14.017" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="ip0aqoR" x1="15.15" x2="16.004" y1="13.16" y2="13.16" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iWSRNrW" x1="14.077" x2="15.151" y1="13.005" y2="13.064" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="i0cKOie" x1="15.15" x2="15.15" y1="13.559" y2="14.411" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="ie9s1lb" x1="15.15" x2="15.15" y1="11.311" y2="11.731" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iYf4G3b" x1="15.28" x2="15.28" y1="14.233" y2="14.174" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="iBayF0v" x1="20.513" x2="10.389" y1="6.669" y2="6.669" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iAK5h5d" x1="18.11" x2="17.796" y1="11.469" y2="11.662" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXlHs5d" x1="13.711" x2="13.398" y1="11.469" y2="11.662" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMpOHsd" x1="21.586" x2="20.379" y1="11.496" y2="13.672" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ilJziqe" x1="9.3" x2="10.758" y1="12.2" y2="12.073" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><filter id="iF2WqUc" width="5.513" height="4.74" x="12.848" y="23.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2321"/></filter><filter id="idiTDoe" width="6.102" height="1.228" x="22.791" y="16.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2321"/></filter><filter id="io23bCe" width="1.075" height="1.075" x="25.198" y="20.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2321" result="effect2_innerShadow_4002_2321"/></filter><filter id="ic9PWpb" width="5.967" height="5.967" x="12.166" y="14.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".125"/></filter><filter id="iiklHqb" width="5.612" height="5.612" x="12.343" y="14.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".2"/></filter><filter id="iidCpQs" width="5.369" height="6.076" x="23.128" y="22.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2321"/></filter><filter id="iafKgHd" width="2.319" height=".3" x="23.592" y="23.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".05"/></filter><filter id="iknPTMr" width="2.319" height=".3" x="23.592" y="25.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".05"/></filter><filter id="iYAB6oe" width="2.319" height=".3" x="23.592" y="26.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".05"/></filter><filter id="i9chyJc" width="10.97" height="12.542" x="10.086" y="6.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2321" result="effect2_innerShadow_4002_2321"/></filter><filter id="ii5IqVd" width="3.754" height="4.824" x="13.004" y="10.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".5"/></filter><filter id="iLiuWGd" width="2.077" height="3.1" x="14.111" y="11.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".05"/></filter><filter id="iyhsFyb" width="3.718" height="1.573" x="13.29" y="14.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".05"/></filter><filter id="ieE0cvM" width="12.873" height="8.357" x="8.713" y="2.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2321"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2321" result="effect2_innerShadow_4002_2321"/></filter><filter id="itiyZQc" width="2.339" height="1.19" x="16.739" y="8.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2321"/></filter><filter id="iIbEXhe" width="2.339" height="1.176" x="11.482" y="8.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2321"/></filter><filter id="iCUvRsb" width="6.584" height="5.992" x="9.069" y="4.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".125"/></filter><filter id="iWRhpze" width="6.362" height="5.736" x="14.991" y="4.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".125"/></filter><filter id="iUUNxtd" width=".787" height=".696" x="16.598" y="10.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".05"/></filter><filter id="iLCYSeb" width=".891" height=".913" x="17.437" y="11.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".1"/></filter><filter id="iLp9kXJ" width=".986" height="1.04" x="12.995" y="10.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".1"/></filter><filter id="i2i4dhC" width=".913" height=".705" x="12.24" y="10.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".05"/></filter><filter id="ivohudb" width="1.329" height="2.379" x="9.117" y="10.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".125"/></filter><filter id="i60HyNs" width="1.447" height="2.403" x="19.861" y="10.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".125"/></filter><filter id="i2UIyve" width="2.405" height="1.16" x="11.401" y="8.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".125"/></filter><filter id="imGSbAd" width="2.405" height="1.16" x="16.68" y="8.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2321" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:singer-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a6y6-g7uw {
  cx: 15.149px;
  cy: 17.656px;
  r: 2.734px;
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.afufpnb6s {
  d: path("M25.766 19.705a2.498 2.498 0 1 0 0-4.997a2.498 2.498 0 0 0 0 4.996");
}

.agyv0c9kf {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
}

.an8w2cz7u {
  d: path("M17.334 10.938a.893.893 0 0 1 .86 1.128H16.47a.896.896 0 0 1 .864-1.128");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.c-_aqkbog {
  d: path("M10.325 15.096a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.117 3.691.239 5.556");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.cfdbxbcxz {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.799 14.833a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044H16.5c-.39.203-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.ch1e8sb3a {
  stop-color: var(--svg-color--c8848a, #C8848A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnw4ucbrh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.268 11.127c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358c.151-.114.325-.136.39-.051");
}

.cqq24abxx {
  d: path("m15.382 6.716l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.805-.767-1.688c0-1.072.781-1.614 1.28-1.96c.14-.097.26-.179.33-.252l.1-.105c.35-.371.973-1.032 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.cun4e9f-e {
  d: path("M15.118 17.406c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.d0mmm9b4e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.111h2.02");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dz_8pl7dq {
  stop-color: var(--svg-color--bd6975, #BD6975);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e55i1-bjj {
  stop-color: var(--svg-color--e86b1f, #E86B1F);
}

.ebel0iswy {
  d: path("M10.096 10.473a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ejynn6b3w {
  stop-color: var(--svg-color--ef5945, #EF5945);
  stop-opacity: 0;
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6id_baiq {
  stop-color: var(--svg-color--bb6a4f, #BB6A4F);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.fk97krmxu {
  d: path("M23.128 23.393c0-.44.365-.803.816-.803h3.054c.745 0 1.349.59 1.349 1.316v3.514c0 .605-.503 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.315.187-.59.458-.72a.8.8 0 0 1-.457-.72a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.721c0-.314.186-.59.457-.72a.8.8 0 0 1-.457-.72");
}

.flvbp4biy {
  d: path("M25.736 21.634a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.g-2q6vgre {
  d: path("M24.313 16.52h-5.58l-2.274 11.996h3.149l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.g0fbzpbju {
  d: path("M12.966 10.938a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glz1dlbql {
  d: path("M20.071 13.672q.1-1.595.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.gu_vetbpq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 26.983h2.02");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.guyqgqb-l {
  cx: 12.696px;
  cy: 11.319px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hermhta_f {
  d: path("M27.277 20.83c.59 0 1.07.48 1.07 1.07v2.45h-2.14V21.9c0-.59.48-1.07 1.07-1.07");
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hsdt12m1i {
  stop-color: var(--svg-color--feca9f, #FECA9F);
}

.hvpy_wbbn {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M18.882 9.352a1.85 1.85 0 0 0-.687-.412c-.304-.095-.685-.121-1.213-.057a.277.277 0 0 0 .068.551c.481-.059.776-.028.978.036c.199.062.333.163.49.3a.277.277 0 1 0 .364-.418");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i03-jcbks {
  stop-color: var(--svg-color--d14708, #D14708);
}

.i4c7gf1nk {
  d: path("M27.018 28.506c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.ivc982b0q {
  stop-color: var(--svg-color--e48043, #E48043);
  stop-opacity: 0;
}

.ixm2pmbhy {
  stop-color: var(--svg-color--c0705f, #C0705F);
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j66pihcrc {
  d: path("M15.15 15.228c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.28-.198-.21a3 3 0 0 1-1.385.329");
}

.jcqxl8b5s {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 23.766v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jwhqis_ra {
  fill: var(--svg-color--000, #000);
  d: path("M13.477 11.83a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.jy25td8rp {
  stop-color: var(--svg-color--e82d86, #E82D86);
}

.k_bvcfbcc {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.112 11.134a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.k-23bl_xw {
  stop-color: var(--svg-color--bb6a4f, #BB6A4F);
  stop-opacity: 0;
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.ke03wbpey {
  d: path("M10.288 13.581a1.64 1.64 0 0 1-.904-.308v.93c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.kgt9ojbtf {
  stop-color: var(--svg-color--ae6047, #AE6047);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.knnk86b5x {
  stop-color: var(--svg-color--d53939, #D53939);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l4rg4-bid {
  stop-color: var(--svg-color--f6874a, #F6874A);
  stop-opacity: 0;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l7kvrebdp {
  fill: var(--svg-color--000, #000);
  d: path("M16.823 11.83c0-.283.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lo-fmbbpb {
  d: path("M12.848 23.766v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m18w-hohx {
  d: path("M18.129 11.713a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.m1nlemiqb {
  stop-color: var(--svg-color--c37b68, #C37B68);
  stop-opacity: 0;
}

.m27qtcbgg {
  stop-color: var(--svg-color--d14708, #D14708);
  stop-opacity: 0;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m86r8t2qn {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.112 13.021q.057-.951.11-1.903a.956.956 0 0 1-.11 1.903");
}

.m9f_4xbpp {
  d: path("M15.118 16.319c-1.16 0-2.487.208-3.567.58l1.29 6.873c.72.324 1.497.434 2.317.434c.77 0 1.51-.074 2.19-.352l1.313-6.956c-1.05-.382-2.384-.58-3.544-.58");
}

.maqiohbml {
  stop-color: var(--svg-color--ec7046, #EC7046);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mnp72frot {
  stop-color: var(--svg-color--f6874a, #F6874A);
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nu2pufskf {
  d: path("M15.103 6.298a.66.66 0 0 0-.402-.137h-1.273a3.3 3.3 0 0 0-.541.044l-2.248 6.618h1.809l-.508 2.688l3.687-5.133h-1.883z");
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.o_frn_b6l {
  stop-color: var(--svg-color--cc2820, #CC2820);
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ohgvqyqas {
  stop-color: var(--svg-color--cc2820, #CC2820);
  stop-opacity: 0;
}

.ohzrjbbgt {
  stop-color: var(--svg-color--d1867a, #D1867A);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oy7fe6bjb {
  stop-color: var(--svg-color--e48043, #E48043);
}

.pdp7s61vg {
  d: path("M17.268 11.127c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358c.151-.114.325-.136.39-.051");
}

.pej7ph77g {
  d: path("M25.726 26.346a.784.784 0 0 1-.782-.711l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.pi7-9gb0y {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m14.719 11.995l-.692 1.656c-.101.378.142.756.487.756h.734c.345 0 .588-.384.487-.756l-.497-1.838c-.106-.408-.408-.225-.52.182");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxgdi68-a {
  cx: 12.696px;
  cy: 11.319px;
  rx: 0.39px;
  ry: 0.197px;
}

.pz-_6uplk {
  stop-color: var(--svg-color--db9a86, #DB9A86);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q-b7edbvw {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.759 10.667c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qlsp8sbaz {
  stop-color: var(--svg-color--e3a28a, #E3A28A);
}

.qm8srpk6b {
  stop-color: var(--svg-color--f98026, #F98026);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qndc1xila {
  stop-color: var(--svg-color--ec7046, #EC7046);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.rgp37jb6d {
  d: path("m28.214 16.546l-4.844-.02a.57.57 0 0 0-.58.579c0 .325.255.578.58.578l4.844.02a.57.57 0 0 0 .578-.578a.585.585 0 0 0-.578-.579");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rqyrdfbps {
  stop-color: var(--svg-color--e22f38, #E22F38);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rua3ie5oc {
  d: path("M20.01 13.581c.336-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.34 2.02a4.1 4.1 0 0 0 .345-1.18z");
}

.rzqjthgas {
  stop-color: var(--svg-color--ef5945, #EF5945);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s1o5hac8o {
  d: path("m20.362 10.088l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.52c.974.188 2.082.516 2.902 1.05c1.745 1.139 1.44 3.19.521 4.155");
}

.savumudgh {
  d: path("m14.767 11.617l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sk6_ryb5x {
  d: path("M20.005 5.689c.514.177.975.536 1.267 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.031 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.589-.188.912-.188c.843 0 1.58.456 1.989 1.132c.308.51.79.88 1.352 1.073");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t4qzv1a_c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.553h2.02");
}

.t9uwhgb4l {
  d: path("M13.781 11.726c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.ta6hmvbrg {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M11.739 9.243a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.286a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.teyf2ebbe {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.776 9.523c.257-.185.898-.51 1.655-.382");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.tyj09bbmz {
  cx: 15.149px;
  cy: 17.765px;
  r: 2.406px;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u0q_obb8r {
  d: path("M5.405 16.527h6.086l2.248 11.989h-2.79l-5.88-11.529c-.086-.125-.07-.46.336-.46");
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.u74twqbgj {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.54 10.667c.654 0 1.206.45 1.356 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.128 1.37-1.128");
}

.ud57h_lxk {
  d: path("M7.078 28.505v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
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

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v1bt46wqv {
  stop-color: var(--svg-color--feca9f, #FECA9F);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vxg8xmb_d {
  stop-color: var(--svg-color--c46d3a, #C46D3A);
  stop-opacity: 0;
}

.w422gwoow {
  stop-color: var(--svg-color--ba6a59, #BA6A59);
}

.w4q61yb8g {
  d: path("M23.128 28.506v-7.268l-3.52 7.268z");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wiodrpp6l {
  d: path("M7.078 28.506h3.87l-3.87-7.596z");
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrhkd7bsy {
  stop-color: var(--svg-color--be2252, #BE2252);
  stop-opacity: 0;
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xftsofb3t {
  stop-color: var(--svg-color--d42552, #D42552);
}

.xu32dvb5s {
  stop-color: var(--svg-color--bf6d76, #BF6D76);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
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

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zu2i0fbof {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.71 9.476c-.256-.184-.897-.508-1.655-.381");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
