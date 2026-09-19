<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEGGwpd)" class="kkb_itbhc"/><path fill="url(#iuAXzec)" class="kkb_itbhc"/><path fill="url(#iq534Dd)" class="dixgp5b2c"/><path fill="url(#ibUWNwd)" class="dixgp5b2c"/><path fill="url(#iLSmNXc)" class="dixgp5b2c"/><path fill="url(#ixKKiko)" class="zv2tyvbtc"/><path fill="url(#iqIvJAb)" class="zv2tyvbtc"/><path fill="url(#i59HMpb)" class="ui5t8ob3c"/><path fill="url(#ioFe7rc)" class="ui5t8ob3c"/><path fill="url(#iPeOANc)" class="ui5t8ob3c"/><path fill="url(#iDPM1Fd)" class="zhjfgetmo"/><path fill="url(#idGrQzb)" class="zhjfgetmo"/><path class="k6kn8iijv"/><path fill="url(#i1KV55d)" class="zn_-1ab3y"/><path fill="url(#is4Tk2d)" class="uzho3hgph"/><path fill="url(#i72FXBc)" class="uzho3hgph"/><path fill="url(#iOhUSec)" class="xz8pc7bdk"/><path fill="url(#iJRY4fb)" class="xz8pc7bdk"/><path fill="url(#iO7EKec)" class="uyn5z4bvn"/><path fill="url(#iGoycPc)" class="uyn5z4bvn"/><path fill="url(#iKLUfxe)" class="ti35gzbvb"/><path fill="url(#iXxhr9o)" class="ti35gzbvb"/><path fill="url(#i7rSp7b)" class="ti35gzbvb"/><g filter="url(#iwBO4Ob)"><ellipse class="as8s4rb-o"/></g><g filter="url(#iYmDE9b)"><circle fill="url(#iIVsDid)" class="oxb73lbcz"/></g><g filter="url(#ik9zpMd)"><circle fill="url(#iXv8Vre)" class="nsv-fjhly"/></g><g filter="url(#iy3leKc)"><circle fill="url(#i4hVKJI)" class="l0nz0lbnw"/><circle fill="url(#iRPuGJB)" class="l0nz0lbnw"/></g><g filter="url(#iokPkWO)"><circle class="ff8teybof"/><circle fill="url(#i6Q5tTa)" class="ks7udo_xj"/><circle fill="url(#ijEovab)" class="ks7udo_xj"/></g><path fill="url(#iwvsKLc)" class="c71e6bi8d"/><path fill="url(#iT8EgXc)" class="ioz_ulooi"/><path fill="url(#ii0E3Ac)" class="a6m47ibpi"/><path fill="url(#ikudnBb)" class="a6m47ibpi"/><path fill="url(#iG8Vk6b)" class="a6m47ibpi"/><path fill="url(#iGJucFc)" class="a6m47ibpi"/><path fill="url(#iT87mVc)" class="a6m47ibpi"/><path fill="url(#ikkQ0Yg)" class="a6m47ibpi"/><path fill="url(#iDQahFd)" class="a6m47ibpi"/><g filter="url(#iiRS4Mc)"><path class="y8qs1nbjl"/></g><g filter="url(#i9gNoAd)"><path class="aq24d98va"/><path fill="url(#i4UwlGb)" class="f5t2blntx"/><path fill="url(#ifY8edc)" class="f5t2blntx"/><path fill="url(#iJBSPMb)" class="f5t2blntx"/><path fill="url(#i1NBgRF)" class="f5t2blntx"/></g><g filter="url(#iQHa0sd)"><path fill="url(#i2WdVDn)" class="beb13wbrl"/></g><g filter="url(#i7u7j4b)"><path stroke="url(#iuL8yLe)" class="bduq4p90t"/></g><path class="n2xtji-kw"/><path class="pyk748bcz"/><path fill="url(#iLmev3n)" class="l6p_88n9q"/><path class="tqyae3b_g"/><g filter="url(#ifA3mzb)"><path class="cpqeh1q9n"/><path fill="url(#iTyuI2b)" class="uvtv25bpy"/></g><g filter="url(#iHFkxOb)"><path fill="url(#ivQ6Ope)" class="eb9b8vdna"/></g><path class="w1u1mub8z"/><path fill="url(#i827UVd)" class="xj01i8bxq"/><path class="n24j4sp_f"/><g filter="url(#iyRiber)"><path fill="url(#iCyO7De)" class="z4m-pvbac"/></g><g filter="url(#iP7iSCI)"><ellipse transform="rotate(-27.914 13.346 13.048)" class="zclrhwdpy"/><ellipse fill="url(#ijk6qWb)" transform="rotate(-27.914 13.346 13.048)" class="kt43_mv6f"/></g><path fill="url(#icYCTvd)" class="v737-kb8e"/><path fill="url(#i1gk2NX)" class="v737-kb8e"/><path fill="url(#i33Kzde)" class="v737-kb8e"/><path fill="url(#iOYFGrc)" class="v737-kb8e"/><path fill="url(#ii0WgBc)" class="v737-kb8e"/><path fill="url(#iY6OXhc)" class="v737-kb8e"/><path fill="url(#iudKbLd)" class="v737-kb8e"/><path fill="url(#iwqMSGd)" class="v737-kb8e"/><g filter="url(#iS3Gppe)"><path fill="url(#ityS7Me)" class="g1t2lzbov"/><path fill="url(#itwpfTc)" class="g1t2lzbov"/><path fill="url(#iHRIIYb)" class="g1t2lzbov"/><path fill="url(#ixGweCe)" class="g1t2lzbov"/></g><path fill="url(#ib2lrXd)" class="g2i6l-0tu"/><path fill="url(#iHJ6XLr)" class="g2i6l-0tu"/><path fill="url(#iP0gY5b)" class="g2i6l-0tu"/><path fill="url(#im5cwBe)" class="g2i6l-0tu"/><g filter="url(#iD8tGnc)"><ellipse class="jq7ez9q1u"/></g><defs><radialGradient id="iEGGwpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.25 -8.82215 0 16.011 16.61)" gradientUnits="userSpaceOnUse"><stop class="l9-nibb6i"/><stop offset="1" class="yfct4t52m"/></radialGradient><radialGradient id="iuAXzec" cx="0" cy="0" r="1" gradientTransform="matrix(-.9049 0 0 -8.83091 18.677 26.141)" gradientUnits="userSpaceOnUse"><stop class="b601vwbxd"/><stop offset="1" class="g__icmf-v"/></radialGradient><radialGradient id="iq534Dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.721 24.533)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="ibUWNwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.721 26.2)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="iLSmNXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.208 20.006)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="ixKKiko" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.042 20.235)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="iqIvJAb" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.279 27.354)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="ioFe7rc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.416 28.855)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="iPeOANc" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.341 29.9)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="iDPM1Fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.659 22.513)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="idGrQzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.659 27.907)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="i1KV55d" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.462 10.106)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="i72FXBc" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.24 25.33)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="iOhUSec" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.471 28.86)" gradientUnits="userSpaceOnUse"><stop class="fanogvbyi"/><stop offset="1" class="a0y7_lb_e"/></radialGradient><radialGradient id="iJRY4fb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.28125 0 0 -15.3733 9.022 29.673)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="mhpw6_ebm"/><stop offset="1" class="nh1zhnb8g"/></radialGradient><radialGradient id="iO7EKec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 -8.13268 2.48004 -.42883 25.677 29.9)" gradientUnits="userSpaceOnUse"><stop class="jlteq3ywp"/><stop offset="1" class="ud4d3yb8t"/></radialGradient><radialGradient id="iGoycPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .62514 0 23.659 29.9)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="kqqjbhbza"/><stop offset="1" class="g8lpdoqap"/></radialGradient><radialGradient id="iKLUfxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -4.86609 0 16.021 20.657)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="j6c345v2b"/><stop offset=".88" class="ofgai0yng"/></radialGradient><radialGradient id="iXxhr9o" cx="0" cy="0" r="1" gradientTransform="rotate(125.503 3.83 15.16)scale(3.01336 1.49475)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="apucomv8k"/><stop offset="1" class="u3la45b8i"/></radialGradient><radialGradient id="i7rSp7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.64062 -2.47522 0 16.021 20.236)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="d48qdibqs"/><stop offset=".945" class="ea0g_ebwb"/></radialGradient><radialGradient id="iIVsDid" cx="0" cy="0" r="1" gradientTransform="matrix(1.89812 0 0 3.32173 9.06 13.89)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iRPuGJB" cx="0" cy="0" r="1" gradientTransform="matrix(.8942 -.65111 .74316 1.0206 21.558 13.603)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="i6Q5tTa" cx="0" cy="0" r="1" gradientTransform="matrix(.8883 -1.63384 .9563 .51993 21.111 14.777)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="ijEovab" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -6.31 32.668)scale(.39462 .50871)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iwvsKLc" cx="0" cy="0" r="1" gradientTransform="matrix(.16294 1.43904 -.60098 .06805 10.379 12.14)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="l455clhzf"/><stop offset="1" class="o_6cpw3af"/></radialGradient><radialGradient id="iT8EgXc" cx="0" cy="0" r="1" gradientTransform="matrix(.68394 .16058 -.54394 2.31675 21.48 12.575)" gradientUnits="userSpaceOnUse"><stop class="b0rle0boe"/><stop offset=".933" class="ofjcs8bae"/></radialGradient><radialGradient id="ii0E3Ac" cx="0" cy="0" r="1" gradientTransform="rotate(172.349 9.436 8.235)scale(5.45711 6.33359)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="lq7mkdb_a"/><stop offset="1" class="k2wnz-bem"/></radialGradient><radialGradient id="ikudnBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.22548 -15.9803 0 16.033 11.807)" gradientUnits="userSpaceOnUse"><stop offset=".743" class="xk9d3sbtw"/><stop offset=".988" class="hzhy-pb2e"/></radialGradient><radialGradient id="iT87mVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41378 1.74004 0 18.54 12.514)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="ikkQ0Yg" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.50441 1.87087 0 13.61 12.478)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iDQahFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.23843 -6.697 0 16.033 12.072)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="bso1jk4sv"/><stop offset="1" class="e98hbdocf"/></radialGradient><radialGradient id="i1NBgRF" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21297 -.68424 0 16.355 15.627)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iLmev3n" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87735 -1.39552 0 18.358 13.152)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iTyuI2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.2508 -.32318 .44494 -.34528 18.111 13.243)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i827UVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8774 -1.39559 0 13.64 13.152)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijk6qWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00837 -.5343 .64224 -.01006 13.33 13.389)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icYCTvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5625 -2.88065 0 19.794 6.827)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="i1gk2NX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 12.044 9.89)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="i33Kzde" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.45 10.327)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iOYFGrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.388 6.499)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="ii0WgBc" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.513 2.733)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iY6OXhc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.95 9.733)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="iwqMSGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 11.17 10.124)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="iHRIIYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.67 9.89)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="ixGweCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.544 9.952)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="im5cwBe" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.909 8.966)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><linearGradient id="i59HMpb" x1="9.158" x2="9.158" y1="21.169" y2="29.899" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="is4Tk2d" x1="21.034" x2="21.034" y1="19.705" y2="29.899" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="iXv8Vre" x1="10.866" x2="10.173" y1="14.191" y2="14.191" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="i4hVKJI" x1="22.331" x2="21.446" y1="12.709" y2="15.452" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iG8Vk6b" x1="9.899" x2="13.531" y1="15.963" y2="16.086" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iGJucFc" x1="10.165" x2="12.2" y1="17.227" y2="17.154" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="i4UwlGb" x1="15.067" x2="16.082" y1="15.024" y2="15.024" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="ifY8edc" x1="17.274" x2="15.821" y1="15.22" y2="15.274" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iJBSPMb" x1="16.212" x2="16.212" y1="16.175" y2="15.556" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="i2WdVDn" x1="16.001" x2="16.001" y1="13.099" y2="14.434" gradientUnits="userSpaceOnUse"><stop class="lek9fzvkb"/><stop offset="1" class="hal-i3k0g"/></linearGradient><linearGradient id="iuL8yLe" x1="14.88" x2="15.35" y1="17.922" y2="17.179" gradientUnits="userSpaceOnUse"><stop class="vdw7embjs"/><stop offset=".663" class="yq56e7bel"/></linearGradient><linearGradient id="ivQ6Ope" x1="19.2" x2="18.86" y1="13.21" y2="13.419" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCyO7De" x1="14.444" x2="14.104" y1="13.21" y2="13.419" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iudKbLd" x1="9.982" x2="10.794" y1="9.265" y2="9.265" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="ityS7Me" x1="16.021" x2="16.021" y1="2.101" y2="10.528" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="itwpfTc" x1="16.021" x2="16.021" y1="2.101" y2="4.702" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="ib2lrXd" x1="21.997" x2="5.369" y1="11.273" y2="11.273" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="iHJ6XLr" x1="15.798" x2="15.798" y1="9.872" y2="10.186" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="iP0gY5b" x1="16.716" x2="16.716" y1="12.178" y2="10.926" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient><filter id="iwBO4Ob" width="8.369" height="2.215" x="15.115" y="9.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".375"/></filter><filter id="iYmDE9b" width="3.812" height="3.611" x="9.06" y="12.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2962"/></filter><filter id="ik9zpMd" width="3.152" height="3.152" x="9.29" y="12.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".25"/></filter><filter id="iy3leKc" width="3.862" height="3.861" x="19.35" y="11.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2962"/></filter><filter id="iokPkWO" width="3.152" height="3.152" x="19.58" y="12.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".25"/></filter><filter id="iiRS4Mc" width="3.404" height="4.4" x="14.041" y="12.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".375"/></filter><filter id="i9gNoAd" width="2.53" height="3.4" x="14.736" y="13.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".125"/></filter><filter id="iQHa0sd" width="2.53" height="3.4" x="14.736" y="12.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".125"/></filter><filter id="i7u7j4b" width="3.88" height="1.56" x="14.061" y="16.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".05"/></filter><filter id="ifA3mzb" width=".835" height=".737" x="17.573" y="12.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".05"/></filter><filter id="iHFkxOb" width=".931" height=".955" x="18.489" y="12.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".1"/></filter><filter id="iyRiber" width="1.034" height="1.092" x="13.685" y="12.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".1"/></filter><filter id="iP7iSCI" width=".971" height=".746" x="12.86" y="12.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".05"/></filter><filter id="iS3Gppe" width="5.791" height="8.428" x="13.126" y="2.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2962"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2962" result="effect2_innerShadow_4002_2962"/></filter><filter id="iD8tGnc" width="7.654" height="2.528" x="15.713" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2962" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-construction-worker-light" /></template>
<style>
.a0y7_lb_e {
  stop-color: var(--svg-color--469bc8, #469BC8);
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.a6m47ibpi {
  d: path("M10.423 11.67c0-.288.116-.634.348-.807l.174-.173c.29-.23.406-.577.406-.923v-.923c0-.288.174-.52.464-.577c.696-.173 2.147-.461 4.235-.461s3.54.288 4.236.461c.232.058.464.289.464.577v.923c0 .346.174.692.406.923c.543.38.51.59.464 1.038c-.195 1.938-.253 3.896-.384 5.84c-.174 1.913-1.678 3.247-3.472 3.247H14.29c-1.852 0-3.299-1.334-3.472-3.248c-.151-1.964-.217-3.935-.397-5.896");
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.apucomv8k {
  stop-color: var(--svg-color--f3a69a, #F3A69A);
}

.aq24d98va {
  fill: var(--svg-color--e0a89a, #E0A89A);
  d: path("m15.588 13.58l-.575 1.84a.583.583 0 0 0 .563.755h.85c.4 0 .681-.384.564-.756l-.575-1.838c-.123-.407-.698-.407-.827 0");
}

.as8s4rb-o {
  cx: 19.299px;
  cy: 10.826px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 3.435px;
  ry: 0.358px;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b0rle0boe {
  stop-color: var(--svg-color--190a1c, #190A1C);
}

.b601vwbxd {
  stop-color: var(--svg-color--3fb7ff, #3FB7FF);
}

.bduq4p90t {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.002 17.275a3.25 3.25 0 0 1-1.499-.355c-.148-.076-.307.091-.214.226c.362.549.994.914 1.713.914c.718 0 1.35-.365 1.712-.914c.093-.14-.066-.302-.214-.226a3.2 3.2 0 0 1-1.498.355Z");
}

.beb13wbrl {
  d: path("m15.588 13.404l-.575 1.838a.583.583 0 0 0 .563.757h.85c.4 0 .68-.384.564-.757l-.575-1.838c-.123-.407-.698-.407-.827 0");
}

.bso1jk4sv {
  stop-color: var(--svg-color--d28b83, #D28B83);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.c71e6bi8d {
  d: path("m10.558 13.38l-.078-1.332l-.844-.117c.026.084.117.368.27.824s.51.615.652.625");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpqeh1q9n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.29 12.84c.068.092-.075.204-.239.326s-.285.208-.353.116c-.07-.092.008-.265.171-.387c.163-.123.352-.147.42-.055");
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d48qdibqs {
  stop-color: var(--svg-color--d98e90, #D98E90);
  stop-opacity: 0;
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dixgp5b2c {
  d: path("M13.721 19.168c-.608.134-1.196.31-1.763.537V29.9h1.763z");
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.e98hbdocf {
  stop-color: var(--svg-color--d28b83, #D28B83);
  stop-opacity: 0;
}

.ea0g_ebwb {
  stop-color: var(--svg-color--d98e90, #D98E90);
}

.eb9b8vdna {
  d: path("M19.22 13.474a.9.9 0 0 0-.25-.5l-.281.308l.127.247z");
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.f5t2blntx {
  d: path("m15.588 13.58l-.575 1.84a.583.583 0 0 0 .563.755h.85c.4 0 .681-.384.564-.756l-.575-1.838c-.123-.407-.698-.407-.827 0");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fanogvbyi {
  stop-color: var(--svg-color--3baeff, #3BAEFF);
}

.ff8teybof {
  cx: 21.156px;
  cy: 13.889px;
  r: 1.076px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g__icmf-v {
  stop-color: var(--svg-color--3fb7ff, #3FB7FF);
  stop-opacity: 0;
}

.g1t2lzbov {
  d: path("M14.826 2.1h2.39c.829 0 1.5.603 1.5 1.633v6.796h-5.39V3.732c0-1.03.671-1.632 1.5-1.632");
}

.g2i6l-0tu {
  d: path("M22.477 9.872H9.883a1.153 1.153 0 1 0 0 2.307h12.594c.642 0 1.153-.521 1.153-1.154a1.147 1.147 0 0 0-1.153-1.153");
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.g8lpdoqap {
  stop-color: var(--svg-color--199dea, #199DEA);
  stop-opacity: 0;
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hal-i3k0g {
  stop-color: var(--svg-color--db9d8f, #DB9D8F);
  stop-opacity: 0;
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.htellnhxv {
  stop-color: var(--svg-color--ffcf4c, #FFCF4C);
}

.hzhy-pb2e {
  stop-color: var(--svg-color--b77a90, #B77A90);
}

.ioz_ulooi {
  d: path("m21.48 13.356l.043-1.308l.844-.117c-.026.084-.117.368-.27.824s-.475.591-.617.601");
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.j6c345v2b {
  stop-color: var(--svg-color--db898d, #DB898D);
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jlteq3ywp {
  stop-color: var(--svg-color--58d2ff, #58D2FF);
}

.jq7ez9q1u {
  cx: 19.54px;
  cy: 10.886px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 2.827px;
  ry: 0.264px;
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k2wnz-bem {
  stop-color: var(--svg-color--e0a99a, #E0A99A);
}

.k6kn8iijv {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.975 20.739v9.16h1.983V19.705c-.698.28-1.355.62-1.983 1.034");
}

.kkb_itbhc {
  d: path("M16.021 19.29c-.78 0-1.55.08-2.3.23V29.9h4.58V19.52c-.74-.15-1.5-.23-2.28-.23");
}

.kqqjbhbza {
  stop-color: var(--svg-color--199dea, #199DEA);
}

.ks7udo_xj {
  cx: 21.156px;
  cy: 13.889px;
  r: 1.076px;
}

.kt43_mv6f {
  cx: 13.346px;
  cy: 13.048px;
  rx: 0.421px;
  ry: 0.213px;
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l0nz0lbnw {
  cx: 21.156px;
  cy: 13.889px;
  r: 1.806px;
}

.l455clhzf {
  stop-color: var(--svg-color--130718, #130718);
}

.l6p_88n9q {
  d: path("M18.36 12.636a.965.965 0 0 1 .93 1.22h-1.864a.97.97 0 0 1 .934-1.22");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9-nibb6i {
  stop-color: var(--svg-color--3086e2, #3086E2);
}

.lek9fzvkb {
  stop-color: var(--svg-color--db9d8f, #DB9D8F);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lq7mkdb_a {
  stop-color: var(--svg-color--ffd8bb, #FFD8BB);
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mhpw6_ebm {
  stop-color: var(--svg-color--4188d0, #4188D0);
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.n24j4sp_f {
  fill: var(--svg-color--000, #000);
  d: path("M14.19 13.601a.55.55 0 0 0-.553-.553a.55.55 0 0 0-.491.807h.978a.55.55 0 0 0 .066-.254");
}

.n2xtji-kw {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M16.002 17.275a3.25 3.25 0 0 1-1.499-.355c-.148-.076-.307.091-.214.226c.362.549.994.914 1.713.914c.718 0 1.35-.365 1.712-.914c.093-.14-.066-.302-.214-.226a3.2 3.2 0 0 1-1.498.355");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nh1zhnb8g {
  stop-color: var(--svg-color--4188d0, #4188D0);
  stop-opacity: 0;
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
}

.nsv-fjhly {
  cx: 10.866px;
  cy: 13.889px;
  r: 1.076px;
}

.o_6cpw3af {
  stop-color: var(--svg-color--474241, #474241);
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o2jd-jggt {
  stop-color: var(--svg-color--ffce64, #FFCE64);
}

.o5ewjjbtz {
  stop-color: var(--svg-color--f9b14d, #F9B14D);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofgai0yng {
  stop-color: var(--svg-color--e19a9b, #E19A9B);
}

.ofjcs8bae {
  stop-color: var(--svg-color--4d4b4c, #4D4B4C);
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
}

.ououd5b1f {
  stop-color: var(--svg-color--f9cd2e, #F9CD2E);
}

.oxb73lbcz {
  cx: 10.866px;
  cy: 13.889px;
  r: 1.806px;
}

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.pyk748bcz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.584 12.342a1.51 1.51 0 0 1 1.465 1.145a.296.296 0 0 1-.289.368h-2.413a.25.25 0 0 1-.245-.294a1.51 1.51 0 0 1 1.482-1.22");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qo0y3qb-y {
  stop-color: var(--svg-color--f46d40, #F46D40);
}

.qq6id-bgn {
  stop-color: var(--svg-color--ffee61, #FFEE61);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.ti35gzbvb {
  d: path("M13.81 20.376c.06.76.585 2.281 2.211 2.281s2.151-1.52 2.211-2.281z");
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.tqyae3b_g {
  fill: var(--svg-color--000, #000);
  d: path("M17.808 13.601a.55.55 0 0 1 .552-.553a.55.55 0 0 1 .492.807h-.978a.5.5 0 0 1-.066-.254");
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.u3la45b8i {
  stop-color: var(--svg-color--f3a69a, #F3A69A);
  stop-opacity: 0;
}

.ud4d3yb8t {
  stop-color: var(--svg-color--54b9f0, #54B9F0);
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.ui5t8ob3c {
  d: path("M8.389 21.987a.15.15 0 0 0-.048.11v7.802h1.634v-9.16c-.56.37-1.092.79-1.586 1.248");
}

.uvtv25bpy {
  d: path("M18.29 12.84c.068.092-.075.204-.239.326s-.285.208-.353.116c-.07-.092.008-.265.171-.387c.163-.123.352-.147.42-.055");
}

.uyn5z4bvn {
  d: path("M27.399 29.9c-.14-.947-.34-1.882-.62-2.787a11.56 11.56 0 0 0-3.12-5.019V29.9z");
}

.uzho3hgph {
  d: path("M22.025 20.739v9.16h-1.983V19.705c.698.28 1.355.62 1.983 1.034");
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.v737-kb8e {
  d: path("M9.982 7.208a4.1 4.1 0 0 1 4.1-4.1h3.988a4.1 4.1 0 0 1 4.1 4.1V9.89H9.981z");
}

.vdw7embjs {
  stop-color: var(--svg-color--ebb3a7, #EBB3A7);
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.w1u1mub8z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.413 12.342a1.51 1.51 0 0 0-1.465 1.145a.296.296 0 0 0 .29.368h2.412c.154 0 .277-.14.246-.294a1.515 1.515 0 0 0-1.483-1.22");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xj01i8bxq {
  d: path("M13.637 12.636a.965.965 0 0 0-.93 1.22h1.864a1 1 0 0 0 .036-.255a.97.97 0 0 0-.97-.965");
}

.xk9d3sbtw {
  stop-color: var(--svg-color--cc9193, #CC9193);
  stop-opacity: 0;
}

.xmtd48u_j {
  stop-color: var(--svg-color--ff7955, #FF7955);
}

.xnbb4159v {
  stop-color: var(--svg-color--cc6e42, #CC6E42);
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.xz8pc7bdk {
  d: path("M4.601 29.9c.14-.947.34-1.882.62-2.787a11.56 11.56 0 0 1 3.12-5.019V29.9z");
}

.y8qs1nbjl {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.704 13.757l-.888 1.838c-.11.379.154.757.528.757h.798c.374 0 .638-.384.528-.757l-.54-1.838c-.115-.407-.305-.407-.426 0");
}

.yfct4t52m {
  stop-color: var(--svg-color--41baff, #41BAFF);
}

.yq56e7bel {
  stop-color: var(--svg-color--ebb3a7, #EBB3A7);
  stop-opacity: 0;
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z4m-pvbac {
  d: path("M14.519 13.487c0-.312-.254-.52-.322-.582l-.312.301l.192.391z");
}

.zclrhwdpy {
  cx: 13.346px;
  cy: 13.048px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.421px;
  ry: 0.213px;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zhjfgetmo {
  d: path("M23.659 22.032V29.9h-1.634v-9.16c.578.382 1.126.816 1.634 1.292");
}

.zn_-1ab3y {
  d: path("M9.975 20.739v9.16h1.983V19.705c-.698.28-1.355.62-1.983 1.034");
}

.zv2tyvbtc {
  d: path("M18.279 19.168c.608.134 1.195.31 1.763.537V29.9H18.28z");
}

</style>
