<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#im0wb4T)" class="m1i1rlbvk"/><g filter="url(#i00EpUd)"><path class="u7j5qywzc"/></g><path class="duc38e2qw"/><path fill="url(#iCoINWb)" class="zqss5obsp"/><path fill="url(#i6jO4ud)" class="zqss5obsp"/><path fill="url(#iwtLm3r)" class="zqss5obsp"/><path fill="url(#iRlvw5c)" class="zqss5obsp"/><path class="t4w_5-bef"/><path fill="url(#iDWGLzD)" class="xn6dhjjio"/><path fill="url(#if8dKTc)" class="xn6dhjjio"/><path fill="url(#i8g26lb)" class="xn6dhjjio"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#i1B5pTu)" class="biuac8r4x"/><path fill="url(#iJIw8ya)" class="biuac8r4x"/><path fill="url(#iMAz4Pe)" class="dvr2s59yl"/><path fill="url(#ichclXc)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="sp6_o9bxd"/><path fill="url(#iIvEVud)" class="sp6_o9bxd"/><path fill="url(#iXRw9pd)" class="sp6_o9bxd"/><path fill="url(#iz9xh1o)" class="sp6_o9bxd"/><path fill="url(#ixge7fe)" class="sp6_o9bxd"/><g filter="url(#i6d38Ce)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#icYUYSd)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#immgUlt)"><path fill="url(#inGms0b)" class="ylvkxrbeo"/></g><g filter="url(#isFAmqd)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#i9sxEsb)" class="u1e8ikbzb"/></g><g filter="url(#iZjOE7L)"><path class="z5g21op2e"/></g><g filter="url(#iSc8wed)"><path fill="url(#iQd872d)" class="pimvl5kot"/><path fill="url(#iipuEzc)" class="pimvl5kot"/><path fill="url(#iWBmgqc)" class="pimvl5kot"/><path fill="url(#i6x8ozd)" class="pimvl5kot"/><path fill="url(#imAhg8S)" class="pimvl5kot"/></g><g filter="url(#iJORHGc)"><path stroke="url(#iG8XaEd)" class="cjq4b16bn"/></g><g filter="url(#iGUqD5c)"><path stroke="url(#iFdCNsV)" class="luyfkt2yj"/></g><g filter="url(#iL0NZce)"><path stroke="url(#iGY2LRb)" class="eqaszhbhb"/></g><path fill="url(#iVfIfvd)" class="m7poo2bdt"/><path fill="url(#iO9lCDc)" class="mpronac9o"/><path fill="url(#ikm0bce)" class="m1bmf7bwd"/><path fill="url(#ijYyEgW)" class="hd9jrsbix"/><g filter="url(#iBkcSWS)"><path fill="url(#iNMARgb)" class="f28dyxb1r"/></g><path fill="url(#iEQbyUc)" class="f28dyxb1r"/><path fill="url(#ik6z91d)" class="f28dyxb1r"/><path fill="url(#iDCkv6n)" class="f28dyxb1r"/><path fill="url(#iAY2xCd)" class="f28dyxb1r"/><path fill="url(#iyUG1lb)" class="f28dyxb1r"/><path fill="url(#iWvvSQK)" class="f28dyxb1r"/><path fill="url(#itpzUxc)" class="f28dyxb1r"/><path fill="url(#iqrOd1d)" class="f28dyxb1r"/><path fill="url(#iKg3vib)" class="f28dyxb1r"/><g filter="url(#iUrU2Kd)"><path class="ma-8ykb0j"/></g><g filter="url(#i9gR5zc)"><path fill="url(#iLtwzjd)" class="a4dd47e4l"/><path fill="url(#iPt3chc)" class="a4dd47e4l"/><path fill="url(#i3vQ5re)" class="a4dd47e4l"/><path fill="url(#i6qFc8b)" class="a4dd47e4l"/></g><g filter="url(#iZaopRc)"><path stroke="url(#iUQYbje)" class="wf_2ozdeb"/></g><path fill="url(#iuKeQvo)" class="c-0y0ptbl"/><g filter="url(#iEyvRde)"><path class="bevpg3b-z"/></g><g filter="url(#iLvEShb)"><path class="mu6aibc0m"/></g><path class="bf9wsnb4o"/><path fill="url(#iNWOfKc)" class="yjgdfou9y"/><path class="l8ydu8ovp"/><g filter="url(#iHpwnxx)"><path class="hyu_pk75c"/><path fill="url(#i74OSoe)" class="yki4hgu4x"/></g><g filter="url(#iZEom1T)"><path fill="url(#igV450d)" class="cequiv0oc"/></g><path class="y5rny24rq"/><path fill="url(#itBvyjb)" class="ovatj8b3t"/><path class="c3rq2cbcz"/><g filter="url(#i84ylsc)"><path fill="url(#iojykTd)" class="gi1hchbto"/></g><g filter="url(#ivZ7Qpb)"><ellipse transform="rotate(-27.914 13.252 9.788)" class="ln0qifcsn"/><ellipse fill="url(#iTYxVNe)" transform="rotate(-27.914 13.252 9.788)" class="aihz0dbka"/></g><path fill="url(#iPdU1Bd)" class="cfb5rthwq"/><path fill="url(#iHNm6he)" class="cfb5rthwq"/><path fill="url(#ihSjVLe)" class="cfb5rthwq"/><path fill="url(#ih4mmqd)" class="b_r_zsp3t"/><path fill="url(#i1yjVfQ)" class="b_r_zsp3t"/><g filter="url(#iRSAusp)"><path class="rpf48bcvn"/></g><g filter="url(#irc7ftb)"><path class="t8l5yktkb"/></g><g filter="url(#iPAWBzc)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#iJukHPb)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="iwtLm3r" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.998 12.054)scale(1.81196 3.24827)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="wnf6rgd_w"/><stop offset="1" class="r3cifybsp"/></radialGradient><radialGradient id="iRlvw5c" cx="0" cy="0" r="1" gradientTransform="rotate(147.269 4.65 10.005)scale(2.65864 2.62008)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="f-d4mvczx"/><stop offset="1" class="bwphqzbzj"/></radialGradient><radialGradient id="i8g26lb" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="cdn41be_i"/><stop offset="1" class="tziry6b6t"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="iMAz4Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 27.592 23.749)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="ichclXc" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="ixge7fe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.554 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="inGms0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.83984 -3.92188 0 15.76 16.836)" gradientUnits="userSpaceOnUse"><stop class="x2ga0ib0s"/><stop offset="1" class="n9upexuhw"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="i9sxEsb" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.838)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="iipuEzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iWBmgqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="i6x8ozd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="imAhg8S" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ikm0bce" cx="0" cy="0" r="1" gradientTransform="rotate(75.254 2.613 19.14)scale(2.8752 3.41552)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="isy8u3b-w"/><stop offset="1" class="ulo0skb3n"/></radialGradient><radialGradient id="ijYyEgW" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.648 12.231)" gradientUnits="userSpaceOnUse"><stop offset=".076" class="ejuirjdrv"/><stop offset="1" class="pnnonnt5s"/></radialGradient><radialGradient id="iNMARgb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26686 0 0 -9.24801 18.537 10.8)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="ik6z91d" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.9986 -10.8435 0 16.214 4.63)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="r324_0iwv"/><stop offset="1" class="yknua-bzt"/></radialGradient><radialGradient id="iDCkv6n" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3409 1.67175 0 18.173 9.68)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iAY2xCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0585 -1.1034 1.20967 -.06414 13.453 9.543)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iyUG1lb" cx="0" cy="0" r="1" gradientTransform="matrix(1.21582 0 0 6.13397 10.79 11.185)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iWvvSQK" cx="0" cy="0" r="1" gradientTransform="matrix(2.63428 -3.65397 .8296 .59809 9.811 7.799)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="itpzUxc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.355 13.654 1.29)scale(10.5276 11.6738)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iqrOd1d" cx="0" cy="0" r="1" gradientTransform="matrix(2.06013 .72073 -.42986 1.22872 17.68 5.419)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iKg3vib" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.51527 -6.90778 0 15.755 6.982)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="ah-1ebp0g"/><stop offset="1" class="dcdf1l8mu"/></radialGradient><radialGradient id="iUQYbje" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.313 -5.396)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="c1d5sgupt"/><stop offset="1" class="zj9picbxt"/></radialGradient><radialGradient id="iuKeQvo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.705 14.34)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iNWOfKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.887 9.884)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i74OSoe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.27 .66)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="itBvyjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.523 9.884)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iTYxVNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.236 10.103)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHNm6he" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.323 9.897)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="ihSjVLe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.683 10.442)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i1yjVfQ" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.778 4.878)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><linearGradient id="im0wb4T" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="d__di5b1k"/><stop offset="1" class="ldn_ouzqy"/></linearGradient><linearGradient id="iCoINWb" x1="14.633" x2="13.72" y1="19.957" y2="18.965" gradientUnits="userSpaceOnUse"><stop class="aq4-jj3gx"/><stop offset="1" class="f5q4vk1vk"/></linearGradient><linearGradient id="i6jO4ud" x1="11.535" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="ovaf-b7lk"/></linearGradient><linearGradient id="iDWGLzD" x1="19.938" x2="18.313" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="k3d1ulbgd"/></linearGradient><linearGradient id="if8dKTc" x1="17" x2="17.938" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="i1B5pTu" x1="23.473" x2="23.473" y1="29.782" y2="23.532" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iQd872d" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="iG8XaEd" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iFdCNsV" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iGY2LRb" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iVfIfvd" x1="10.534" x2="10.534" y1="7.783" y2="9.875" gradientUnits="userSpaceOnUse"><stop class="yyf5_sbtz"/><stop offset="1" class="x-_vdabdz"/></linearGradient><linearGradient id="iO9lCDc" x1="20.876" x2="20.876" y1="7.611" y2="9.173" gradientUnits="userSpaceOnUse"><stop class="x6rvzacks"/><stop offset="1" class="qw7p3db1b"/></linearGradient><linearGradient id="iEQbyUc" x1="20.904" x2="16.518" y1="12.485" y2="12.485" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iLtwzjd" x1="15.705" x2="16.56" y1="11.629" y2="11.629" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iPt3chc" x1="14.632" x2="15.706" y1="11.473" y2="11.532" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="i3vQ5re" x1="15.705" x2="15.705" y1="12.027" y2="12.879" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="i6qFc8b" x1="15.705" x2="15.705" y1="9.78" y2="10.638" gradientUnits="userSpaceOnUse"><stop class="bda5lvb8d"/><stop offset="1" class="lwum25b_j"/></linearGradient><linearGradient id="igV450d" x1="18.665" x2="18.351" y1="9.938" y2="10.131" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iojykTd" x1="14.267" x2="13.953" y1="9.938" y2="10.131" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPdU1Bd" x1="22.141" x2="20.934" y1="9.965" y2="12.141" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ih4mmqd" x1="9.855" x2="11.313" y1="10.668" y2="10.541" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><filter id="i00EpUd" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".5"/></filter><filter id="i6d38Ce" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1956"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1956" result="shape"/></filter><filter id="icYUYSd" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/></filter><filter id="immgUlt" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.392157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/></filter><filter id="isFAmqd" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/></filter><filter id="iZjOE7L" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".325"/></filter><filter id="iSc8wed" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/></filter><filter id="iJORHGc" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".05"/></filter><filter id="iGUqD5c" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".05"/></filter><filter id="iL0NZce" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".05"/></filter><filter id="iBkcSWS" width="11.047" height="12.542" x="10.607" y="4.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1956" result="effect2_innerShadow_4002_1956"/></filter><filter id="iUrU2Kd" width="3.877" height="4.9" x="13.559" y="8.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".5"/></filter><filter id="i9gR5zc" width="2.077" height="3.1" x="14.666" y="9.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".05"/></filter><filter id="iZaopRc" width="3.718" height="1.573" x="13.846" y="13.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".05"/></filter><filter id="iEyvRde" width="2.339" height="1.19" x="17.294" y="7.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.243137 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/></filter><filter id="iLvEShb" width="2.339" height="1.176" x="12.038" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.243137 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/></filter><filter id="iHpwnxx" width=".787" height=".696" x="17.153" y="9.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".05"/></filter><filter id="iZEom1T" width=".891" height=".913" x="17.993" y="9.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".1"/></filter><filter id="i84ylsc" width=".986" height="1.04" x="13.55" y="9.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".1"/></filter><filter id="ivZ7Qpb" width=".913" height=".705" x="12.795" y="9.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".05"/></filter><filter id="iRSAusp" width="1.329" height="2.379" x="9.672" y="9.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".125"/></filter><filter id="irc7ftb" width="1.447" height="2.403" x="20.417" y="9.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1956" stdDeviation=".125"/></filter><filter id="iPAWBzc" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/></filter><filter id="iJukHPb" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1956"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mechanic-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a4dd47e4l {
  d: path("m15.323 10.085l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.ah-1ebp0g {
  stop-color: var(--svg-color--9f7283, #9F7283);
}

.aihz0dbka {
  cx: 13.252px;
  cy: 9.788px;
  rx: 0.39px;
  ry: 0.197px;
}

.aq4-jj3gx {
  stop-color: var(--svg-color--f1d5ff, #F1D5FF);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.b_r_zsp3t {
  d: path("M10.65 8.941a1.61 1.61 0 0 0 .14 3.2a78 78 0 0 1-.14-3.2");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bda5lvb8d {
  stop-color: var(--svg-color--ca9687, #CA9687);
}

.bevpg3b-z {
  fill: var(--svg-color--653e30, #653E30);
  d: path("M19.438 8.085a1.85 1.85 0 0 0-.688-.412c-.304-.096-.685-.121-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.028.979.036c.198.063.332.164.49.3a.277.277 0 0 0 .364-.417");
}

.bf9wsnb4o {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.096 9.135c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.biuac8r4x {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.401-1.54-6.44-3.96-8.457");
}

.bwphqzbzj {
  stop-color: var(--svg-color--e298b3, #E298B3);
  stop-opacity: 0;
}

.c-0y0ptbl {
  d: path("M15.705 13.697c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845s1.248-.338 1.583-.846c.087-.13-.06-.279-.198-.209a3 3 0 0 1-1.385.329");
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c1d5sgupt {
  stop-color: var(--svg-color--d39c8f, #D39C8F);
}

.c3rq2cbcz {
  fill: var(--svg-color--000, #000);
  d: path("M14.032 10.3a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cdn41be_i {
  stop-color: var(--svg-color--e49da8, #E49DA8);
}

.cequiv0oc {
  d: path("M18.684 10.182a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.cfb5rthwq {
  d: path("M20.627 12.14c.065-1.063.129-2.126.184-3.19a1.61 1.61 0 0 1-.184 3.19");
}

.cjq4b16bn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 25.992H25.3");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d__di5b1k {
  stop-color: var(--svg-color--d2c4ec, #D2C4EC);
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.dcdf1l8mu {
  stop-color: var(--svg-color--b28080, #B28080);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.duc38e2qw {
  fill: var(--svg-color--ffe9ff, #FFE9FF);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ejuirjdrv {
  stop-color: var(--svg-color--f3bc92, #F3BC92);
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.f-d4mvczx {
  stop-color: var(--svg-color--e298b3, #E298B3);
}

.f28dyxb1r {
  d: path("M10.88 13.565a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.278-4.388.366-6.27c-.011-.767-.657-.772-1.421-.805h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.376.799-3.376 2.666c0 1.86.15 4.405.273 6.27");
}

.f5q4vk1vk {
  stop-color: var(--svg-color--f1d5ff, #F1D5FF);
  stop-opacity: 0;
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.gi1hchbto {
  d: path("M14.336 10.194c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hd9jrsbix {
  d: path("M10.844 12.05a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.hyu_pk75c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.823 9.595c.064.085-.069.19-.22.302c-.151.113-.263.193-.327.108s.008-.246.159-.359c.15-.113.325-.136.388-.05");
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

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.isy8u3b-w {
  stop-color: var(--svg-color--ffdead, #FFDEAD);
}

.k3d1ulbgd {
  stop-color: var(--svg-color--fee6ff, #FEE6FF);
  stop-opacity: 0;
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l8ydu8ovp {
  fill: var(--svg-color--000, #000);
  d: path("M17.378 10.3a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.ldn_ouzqy {
  stop-color: var(--svg-color--c6c4d3, #C6C4D3);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln0qifcsn {
  cx: 13.252px;
  cy: 9.788px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.lwum25b_j {
  stop-color: var(--svg-color--ca9687, #CA9687);
  stop-opacity: 0;
}

.m1bmf7bwd {
  d: path("M20.566 12.05c.335-.011.65-.125.905-.309v.931c0 .893-.532 1.689-1.341 2.02a4.1 4.1 0 0 0 .346-1.18z");
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m7poo2bdt {
  d: path("m10.189 7.196l.825.071v2.608h-.96z");
}

.ma-8ykb0j {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.219 10.281l-.635 1.838c-.109.379.152.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.542-.407-.661 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mpronac9o {
  d: path("M20.396 7.267h.96v2.608h-.96z");
}

.mu6aibc0m {
  fill: var(--svg-color--653e30, #653E30);
  d: path("M12.294 7.968a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.n9upexuhw {
  stop-color: var(--svg-color--d09290, #D09290);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
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

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.ovaf-b7lk {
  stop-color: var(--svg-color--ffeaff, #FFEAFF);
  stop-opacity: 0;
}

.ovatj8b3t {
  d: path("M13.52 9.407a.893.893 0 0 0-.86 1.127h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.pimvl5kot {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnnonnt5s {
  stop-color: var(--svg-color--e29f81, #E29F81);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw7p3db1b {
  stop-color: var(--svg-color--f9dba2, #F9DBA2);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.r324_0iwv {
  stop-color: var(--svg-color--c8898a, #C8898A);
  stop-opacity: 0;
}

.r3cifybsp {
  stop-color: var(--svg-color--edc3c1, #EDC3C1);
  stop-opacity: 0;
}

.rpf48bcvn {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.668 9.602a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.sp6_o9bxd {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.102-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t4w_5-bef {
  fill: var(--svg-color--ffe3f6, #FFE3F6);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.t8l5yktkb {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.667 11.49q.057-.952.11-1.904a.955.955 0 0 1-.11 1.904");
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.tziry6b6t {
  stop-color: var(--svg-color--e49da8, #E49DA8);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.u7j5qywzc {
  fill: var(--svg-color--b1a1bf, #B1A1BF);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.ulo0skb3n {
  stop-color: var(--svg-color--e4a284, #E4A284);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.wf_2ozdeb {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.354 13.302c.39.203.855.32 1.35.32a2.9 2.9 0 0 0 1.352-.32a.23.23 0 0 1 .271.044a.214.214 0 0 1 .024.272m-2.997-.316l2.934.275m-2.934-.275a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271m.295-.317l-.232.275m3.229.041l-.063-.04m.063.04l-.063-.04m.063.04c-.349.528-.956.88-1.646.88s-1.297-.351-1.646-.879m3.23-.042a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.584-.846m-.062.042l.063-.042m-.063.042l.063-.042");
}

.wnf6rgd_w {
  stop-color: var(--svg-color--edc3c1, #EDC3C1);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x-_vdabdz {
  stop-color: var(--svg-color--e3b782, #E3B782);
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x2ga0ib0s {
  stop-color: var(--svg-color--d58c96, #D58C96);
}

.x6rvzacks {
  stop-color: var(--svg-color--fff5ba, #FFF5BA);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xn6dhjjio {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y5rny24rq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.314 9.135c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yjgdfou9y {
  d: path("M17.889 9.407a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.yki4hgu4x {
  d: path("M17.823 9.595c.064.085-.069.19-.22.302c-.151.113-.263.193-.327.108s.008-.246.159-.359c.15-.113.325-.136.388-.05");
}

.yknua-bzt {
  stop-color: var(--svg-color--c0758f, #C0758F);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ylvkxrbeo {
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.921c-.356 1.237-1.494 1.738-2.012 1.84");
}

.yyf5_sbtz {
  stop-color: var(--svg-color--f4ca9a, #F4CA9A);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.zj9picbxt {
  stop-color: var(--svg-color--d39c8f, #D39C8F);
  stop-opacity: 0;
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
