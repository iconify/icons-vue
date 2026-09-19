<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSo21lb)"><path class="z0lvmp82d"/><path fill="url(#ioaZu4c)" class="gajflvy2u"/><path fill="url(#iYh3RWc)" class="gajflvy2u"/><path fill="url(#iwwLzTc)" class="gajflvy2u"/></g><g filter="url(#i5E9Xjc)"><path fill="url(#iQ0TARb)" class="hr_tvphim"/><path fill="url(#iYTCWde)" class="hr_tvphim"/><path fill="url(#iVjCSPe)" class="hr_tvphim"/><path fill="url(#i9GR5Yc)" class="hr_tvphim"/><path fill="url(#iwEblxc)" class="hr_tvphim"/></g><g filter="url(#iFvuUmC)"><path class="mle7sl8ks"/></g><circle fill="url(#iFwFjqe)" class="sl36r4bkw"/><circle fill="url(#iP9k27b)" class="sl36r4bkw"/><g filter="url(#iI8UYFd)"><circle fill="url(#iPcotfe)" class="m0eeoe78x"/><circle fill="url(#izATxGc)" class="m0eeoe78x"/></g><rect class="g6s8itb9r"/><rect fill="url(#iLbqgYd)" class="imqdecrjn"/><rect fill="url(#i7mEDId)" class="imqdecrjn"/><rect fill="url(#iE3DWZc)" class="imqdecrjn"/><rect fill="url(#iDHa43d)" class="imqdecrjn"/><rect fill="url(#ic5dZgc)" class="imqdecrjn"/><rect fill="url(#iOSAbRb)" class="imqdecrjn"/><rect fill="url(#isuPWxe)" transform="rotate(-65.334 8.206 26.152)" class="f8tap8bxm"/><rect fill="url(#ix3hTWc)" transform="rotate(-65.334 8.206 26.152)" class="f8tap8bxm"/><path fill="url(#iBEfFKe)" class="qb6tigb_q"/><path fill="url(#iOIukyb)" class="qb6tigb_q"/><path fill="url(#iRJmBRc)" class="qb6tigb_q"/><path fill="url(#iKpTPOd)" class="qb6tigb_q"/><path fill="url(#itevXgb)" class="qb6tigb_q"/><path fill="url(#iPNQg9c)" class="qb6tigb_q"/><g filter="url(#iqMgWvb)"><path fill="url(#i2Itcpd)" clip-rule="evenodd" class="plchgbb7u"/><path fill="url(#ic0omed)" clip-rule="evenodd" class="plchgbb7u"/></g><path fill="url(#iV1O8kc)" class="xx326qbfg"/><path fill="url(#i72vhxe)" class="xx326qbfg"/><path fill="url(#ilObFbe)" class="xx326qbfg"/><path fill="url(#iWz9kEw)" transform="rotate(16.465 20.736 11.659)" class="yc5oz8lws"/><g filter="url(#iWqLcPA)"><rect transform="rotate(24.427 5.644 23.445)" class="z_ue7__pa"/></g><rect fill="url(#id2j1fd)" transform="rotate(24.427 5.644 23.445)" class="w1vxk9vjl"/><g filter="url(#iaX2mRd)"><path fill="url(#i2NgJbc)" clip-rule="evenodd" class="qp48p8b-b"/><path fill="url(#ihVuLzb)" clip-rule="evenodd" class="qp48p8b-b"/><path fill="url(#ibtW70S)" clip-rule="evenodd" class="qp48p8b-b"/></g><path fill="url(#is15Gab)" clip-rule="evenodd" class="w1z7h-3do"/><path fill="url(#iCYlQYV)" clip-rule="evenodd" class="w1z7h-3do"/><path fill="url(#iuP9yXb)" clip-rule="evenodd" class="w1z7h-3do"/><rect fill="url(#iJ8Hiwd)" class="il80kqqaz"/><rect fill="url(#iknOKyb)" class="il80kqqaz"/><g filter="url(#iO4gnRJ)"><circle fill="url(#iIczNvc)" class="duh2_cb1g"/></g><g filter="url(#iVO9wxe)"><path clip-rule="evenodd" class="w8c0-qbso"/></g><path class="l2hjghxql"/><path fill="url(#iNGFOCe)" class="ja7250b2j"/><path fill="url(#iNgZCDc)" class="ja7250b2j"/><path fill="url(#i06R3Md)" class="ja7250b2j"/><g filter="url(#ig31cob)"><circle fill="url(#iiu8xld)" class="y-ecmf49q"/></g><g filter="url(#i0NX5Ee)"><circle stroke="url(#i88lcCf)" class="gf6pdh_6u"/></g><g filter="url(#icCUGgd)"><circle stroke="url(#iXPURCb)" class="lk-x1tbux"/></g><g filter="url(#iysJH2N)"><circle stroke="url(#izShr5b)" class="umq_hfbdq"/></g><circle fill="url(#ik8yEBe)" class="err_zmbut"/><path class="nsyby5bts"/><g filter="url(#iF4yj1U)"><path class="fcmye_39g"/></g><path fill="url(#iPE60se)" class="fk7o7rbxe"/><g filter="url(#iFJztqe)"><path fill="url(#ihJF6Ib)" class="gxz42mfas"/><path fill="url(#ikeXfLc)" class="gxz42mfas"/><path fill="url(#iQc18kc)" class="gxz42mfas"/><path fill="url(#ixrmO8c)" class="gxz42mfas"/></g><g filter="url(#iL6VPJb)"><path fill="url(#i9JRMJc)" class="oeytnrb8l"/><path fill="url(#iwRLrie)" class="oeytnrb8l"/><path fill="url(#ittL8Wd)" class="oeytnrb8l"/><path fill="url(#ioVbRli)" class="oeytnrb8l"/><path fill="url(#iFJGNcd)" class="oeytnrb8l"/></g><path fill="url(#iLTPzRb)" class="ogmjrqbhz"/><path fill="url(#itllyNd)" class="ogmjrqbhz"/><path clip-rule="evenodd" class="w6dy-su5q"/><path class="poxnejmkd"/><path fill="url(#iQLGXHe)" class="bhe8i4mgj"/><path fill="url(#iPqkcde)" class="bhe8i4mgj"/><path fill="url(#ixJ4jLb)" class="bhe8i4mgj"/><path fill="url(#i9kjcHc)" class="bhe8i4mgj"/><g filter="url(#iJ9jKFe)"><path clip-rule="evenodd" class="mnp_vbc6i"/></g><path class="mu7vrc9io"/><path fill="url(#iqYan0c)" class="wpgayijbr"/><path fill="url(#ignqM1c)" class="s2_38pb8q"/><ellipse fill="url(#i5BOS1b)" transform="rotate(13.128 13.432 5.763)" class="nu7p8_blk"/><g filter="url(#iq4mfFe)"><path class="v1h4bu_vp"/></g><g filter="url(#iE5xSge)"><path stroke="url(#ioeUCgH)" class="a9nytvbby"/></g><g filter="url(#iyAfefb)"><path stroke="url(#ircrhgc)" class="tz8tjvbjf"/></g><defs><radialGradient id="iwwLzTc" cx="0" cy="0" r="1" gradientTransform="matrix(.7395 -.04828 .083 1.2714 5.124 22.915)" gradientUnits="userSpaceOnUse"><stop class="bfwbq1bpl"/><stop offset="1" class="ktc-s82to"/></radialGradient><radialGradient id="iYTCWde" cx="0" cy="0" r="1" gradientTransform="rotate(109.319 -1.796 14.154)scale(5.76196 2.25923)" gradientUnits="userSpaceOnUse"><stop class="y3ij90b8v"/><stop offset="1" class="qb3gn8bfr"/></radialGradient><radialGradient id="iVjCSPe" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 0 0 12.1563 10.998 17.032)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="yutdbcb6i"/><stop offset="1" class="sstiaym3o"/></radialGradient><radialGradient id="i9GR5Yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.46875 5.125 0 16.06 18)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="yu7wmpb_a"/><stop offset="1" class="zzc1m6bsl"/></radialGradient><radialGradient id="iP9k27b" cx="0" cy="0" r="1" gradientTransform="matrix(1.48438 0 0 3.64062 9.31 28.391)" gradientUnits="userSpaceOnUse"><stop class="answrebhr"/><stop offset="1" class="fzo002mry"/></radialGradient><radialGradient id="iPcotfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.80266 4.80004 0 11.728 29.643)" gradientUnits="userSpaceOnUse"><stop class="ja_znnx3a"/><stop offset="1" class="ildpa548e"/></radialGradient><radialGradient id="izATxGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71875 1.03125 0 11.529 28.094)" gradientUnits="userSpaceOnUse"><stop class="z-rtjcc0y"/><stop offset="1" class="vxrkdvuju"/></radialGradient><radialGradient id="i7mEDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.11265 -.46567 0 12.35 24.18)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="iE3DWZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9265 -.24601 0 11.107 23.367)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="iDHa43d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.69196 .27569 0 11.107 28.542)" gradientUnits="userSpaceOnUse"><stop class="q6suc5ubz"/><stop offset="1" class="erfrsrblk"/></radialGradient><radialGradient id="ic5dZgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.94902 .80452 0 11.728 29.032)" gradientUnits="userSpaceOnUse"><stop class="ku1djbbcg"/><stop offset="1" class="e3f4ywbbl"/></radialGradient><radialGradient id="iOSAbRb" cx="0" cy="0" r="1" gradientTransform="rotate(38.089 -28.887 29.319)scale(1.46908 .76568)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n3h2abc_m"/><stop offset="1" class="rgr8nhbdi"/></radialGradient><radialGradient id="isuPWxe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.01534 -.13834 .02815 -1.0205 13.907 26.933)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="rs99u8bqf"/><stop offset="1" class="lvn5-ac9d"/></radialGradient><radialGradient id="itevXgb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07812 -.4219 .60152 -2.96294 17.591 18.97)" gradientUnits="userSpaceOnUse"><stop class="tis1nnbrp"/><stop offset="1" class="t9-j-pbql"/></radialGradient><radialGradient id="iPNQg9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.82813 0 0 -2.43007 12.81 18.188)" gradientUnits="userSpaceOnUse"><stop class="r04agib6p"/><stop offset="1" class="mz7wlj55e"/></radialGradient><radialGradient id="iV1O8kc" cx="0" cy="0" r="1" gradientTransform="matrix(1.73101 -.3013 .92668 5.32391 15.358 8.827)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="om366ybrp"/><stop offset="1" class="al52zb3wa"/></radialGradient><radialGradient id="i72vhxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.08802 .88154 -.75069 -.07495 16.788 6.963)" gradientUnits="userSpaceOnUse"><stop class="numeh5b7w"/><stop offset="1" class="yqah6ebzx"/></radialGradient><radialGradient id="iWz9kEw" cx="0" cy="0" r="1" gradientTransform="matrix(.06825 -4.12415 .84696 .01402 21.263 15.607)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="w-8ci9bkh"/><stop offset="1" class="dr65abcro"/></radialGradient><radialGradient id="id2j1fd" cx="0" cy="0" r="1" gradientTransform="matrix(.59496 -.39035 .70458 1.0739 5.739 24.613)" gradientUnits="userSpaceOnUse"><stop class="vp5ble8bb"/><stop offset="1" class="g4u-v_bhx"/></radialGradient><radialGradient id="iCYlQYV" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.579 22.268)scale(5.3418)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="lfwvarbqo"/><stop offset="1" class="z4for55kd"/></radialGradient><radialGradient id="iuP9yXb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.525 18.009 9.368)scale(12.5412 9.73796)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="jz-3fab0l"/><stop offset="1" class="fiiks7b8f"/></radialGradient><radialGradient id="iknOKyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 .39452 -.43395 -.94526 25.03 11.343)" gradientUnits="userSpaceOnUse"><stop class="roww1df0l"/><stop offset="1" class="ennuonbfb"/></radialGradient><radialGradient id="iIczNvc" cx="0" cy="0" r="1" gradientTransform="matrix(4.09375 -5.53125 9.86398 7.30045 18.841 26.625)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="z3yur8boj"/><stop offset="1" class="c9gtc1bjl"/></radialGradient><radialGradient id="iNGFOCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.81094 4.76329 -1.81631 .69054 18.03 12.551)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="dqwirq1wj"/><stop offset="1" class="o50-1mg1f"/></radialGradient><radialGradient id="i06R3Md" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60922 1.60922 -4.29661 -4.29661 19.286 8.657)" gradientUnits="userSpaceOnUse"><stop class="o-ce7bc5n"/><stop offset="1" class="skmvm0bcw"/></radialGradient><radialGradient id="ik8yEBe" cx="0" cy="0" r="1" gradientTransform="rotate(-73.593 20.764 -2.733)scale(.73297)" gradientUnits="userSpaceOnUse"><stop class="c-qoub4hl"/><stop offset="1" class="gmz24obej"/></radialGradient><radialGradient id="iPE60se" cx="0" cy="0" r="1" gradientTransform="matrix(.46986 .14303 -.2019 .66323 12.542 6.83)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="ikeXfLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7584 .11067 -.13492 -.92465 15.67 5.544)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iQc18kc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.482 9.566 -1.878)scale(4.7049 1.27543)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="ixrmO8c" cx="0" cy="0" r="1" gradientTransform="matrix(.07052 .3472 -.54146 .10998 13.84 5.96)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="i9JRMJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.81982 -2.1724 3.2918 2.75755 14.703 4.856)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="iwRLrie" cx="0" cy="0" r="1" gradientTransform="matrix(.92507 -.9977 1.5976 1.48131 12.384 3.927)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="ittL8Wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.44545 .22786 -.11054 -.21609 17.349 6.013)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="ioVbRli" cx="0" cy="0" r="1" gradientTransform="matrix(.76544 -.3507 .92714 2.02362 15.333 5.049)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="iFJGNcd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21527 2.21411 -1.51465 -1.51544 17.453 2.856)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="bc6qfubfl"/><stop offset="1" class="hj58w-1de"/></radialGradient><radialGradient id="iLTPzRb" cx="0" cy="0" r="1" gradientTransform="matrix(.60737 -.31847 .15544 .29645 15.367 5.497)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="ixJ4jLb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 -2.96876 2.35369 -1.598 18.435 11.75)" gradientUnits="userSpaceOnUse"><stop offset=".88" class="cod3s5bmi"/><stop offset="1" class="qu8oblblu"/></radialGradient><radialGradient id="iqYan0c" cx="0" cy="0" r="1" gradientTransform="matrix(.2436 -.04948 .09613 .47327 13.584 6.038)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ignqM1c" cx="0" cy="0" r="1" gradientTransform="matrix(.2223 -.04515 .09772 .48107 13.438 6.086)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ioaZu4c" x1="9.114" x2="8.197" y1="24.347" y2="23.864" gradientUnits="userSpaceOnUse"><stop offset=".209" class="id-v9-mic"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="iYh3RWc" x1="7.875" x2="8.165" y1="24.685" y2="23.928" gradientUnits="userSpaceOnUse"><stop offset=".122" class="oqr4-mbfk"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="iQ0TARb" x1="9.904" x2="16.06" y1="20.594" y2="17.219" gradientUnits="userSpaceOnUse"><stop class="sa2yvrtdg"/><stop offset="1" class="bxntujdns"/></linearGradient><linearGradient id="iwEblxc" x1="9.06" x2="9.966" y1="19.844" y2="19.907" gradientUnits="userSpaceOnUse"><stop class="d_4otnung"/><stop offset="1" class="gldbv0pab"/></linearGradient><linearGradient id="iFwFjqe" x1="11.919" x2="11.919" y1="30.235" y2="26.669" gradientUnits="userSpaceOnUse"><stop class="uqxwa8ern"/><stop offset=".596" class="qx2qyypot"/></linearGradient><linearGradient id="iLbqgYd" x1="12.349" x2="11.612" y1="26.768" y2="26.768" gradientUnits="userSpaceOnUse"><stop class="g6i5vgbtc"/><stop offset="1" class="zuaxx5qad"/></linearGradient><linearGradient id="ix3hTWc" x1="11.901" x2="11.813" y1="27.733" y2="26.98" gradientUnits="userSpaceOnUse"><stop class="pyh7r6bag"/><stop offset="1" class="ym5c6ha3r"/></linearGradient><linearGradient id="iBEfFKe" x1="12.351" x2="17.259" y1="18.492" y2="18.492" gradientUnits="userSpaceOnUse"><stop class="n0w_cmcuq"/><stop offset="1" class="cjqgdpbwq"/></linearGradient><linearGradient id="iOIukyb" x1="15.748" x2="15.748" y1="17.422" y2="17.766" gradientUnits="userSpaceOnUse"><stop class="xb91u7b-b"/><stop offset="1" class="us60yytqw"/></linearGradient><linearGradient id="iRJmBRc" x1="14.826" x2="14.826" y1="19.266" y2="18.219" gradientUnits="userSpaceOnUse"><stop class="x8v8a_bhe"/><stop offset="1" class="g0aomjwhv"/></linearGradient><linearGradient id="iKpTPOd" x1="11.107" x2="11.341" y1="19.032" y2="19.032" gradientUnits="userSpaceOnUse"><stop class="xudiynxns"/><stop offset="1" class="h_vbtipyr"/></linearGradient><linearGradient id="i2Itcpd" x1="15.021" x2="15.021" y1="18.985" y2="26.516" gradientUnits="userSpaceOnUse"><stop class="yp_2y0bkd"/><stop offset="1" class="jli-mvbgu"/></linearGradient><linearGradient id="ic0omed" x1="11.107" x2="11.529" y1="21.28" y2="21.28" gradientUnits="userSpaceOnUse"><stop class="ig81yhx8p"/><stop offset="1" class="sqtinbbgr"/></linearGradient><linearGradient id="ilObFbe" x1="15.38" x2="15.597" y1="9.156" y2="9.071" gradientUnits="userSpaceOnUse"><stop class="ndh-ggbqf"/><stop offset="1" class="naoj9jbij"/></linearGradient><linearGradient id="i2NgJbc" x1="13.357" x2="19.091" y1="19.251" y2="16.001" gradientUnits="userSpaceOnUse"><stop class="x3lzt0c-k"/><stop offset="1" class="cwu_shb3d"/></linearGradient><linearGradient id="ihVuLzb" x1="21.17" x2="20.147" y1="17.378" y2="17.378" gradientUnits="userSpaceOnUse"><stop class="ys8863_0j"/><stop offset="1" class="h0a-qhb0e"/></linearGradient><linearGradient id="ibtW70S" x1="16.738" x2="16.738" y1="15.918" y2="16.251" gradientUnits="userSpaceOnUse"><stop class="io62jp_6h"/><stop offset="1" class="rg3z6xbem"/></linearGradient><linearGradient id="is15Gab" x1="24.529" x2="16.435" y1="19.469" y2="28.532" gradientUnits="userSpaceOnUse"><stop class="v06h3pbnx"/><stop offset="1" class="lucd7-9cq"/></linearGradient><linearGradient id="iJ8Hiwd" x1="21.013" x2="24.896" y1="11.876" y2="11.876" gradientUnits="userSpaceOnUse"><stop class="o2t29rbsm"/><stop offset="1" class="laa0aab1b"/></linearGradient><linearGradient id="iNgZCDc" x1="15.777" x2="15.777" y1="15.43" y2="11.393" gradientUnits="userSpaceOnUse"><stop class="kqmyk7boa"/><stop offset="1" class="bspgbrb6c"/></linearGradient><linearGradient id="iiu8xld" x1="21.498" x2="20.013" y1="22.985" y2="24.983" gradientUnits="userSpaceOnUse"><stop class="zax-lz03d"/><stop offset="1" class="zg7ndleiu"/></linearGradient><linearGradient id="i88lcCf" x1="21.662" x2="20.279" y1="22.821" y2="24.547" gradientUnits="userSpaceOnUse"><stop offset=".139" class="szqa4cczu"/><stop offset=".488" class="i2tkr35ot"/></linearGradient><linearGradient id="iXPURCb" x1="24.294" x2="18.169" y1="20.282" y2="27.922" gradientUnits="userSpaceOnUse"><stop offset=".066" class="u245iqdps"/><stop offset=".257" class="rijqbwbix"/><stop offset=".803" class="rijqbwbix"/><stop offset=".945" class="br5egpbia"/></linearGradient><linearGradient id="izShr5b" x1="24.498" x2="17.123" y1="19.207" y2="28.521" gradientUnits="userSpaceOnUse"><stop class="bgt2mc6fp"/><stop offset=".294" class="j5rtt4bpo"/><stop offset=".801" class="x4ldqjsok"/></linearGradient><linearGradient id="ihJF6Ib" x1="15.527" x2="13.014" y1="6.26" y2="6.93" gradientUnits="userSpaceOnUse"><stop class="bmcblacal"/><stop offset="1" class="d0kv1cyul"/></linearGradient><linearGradient id="itllyNd" x1="15.348" x2="15.451" y1="5.562" y2="5.556" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="iQLGXHe" x1="16.591" x2="17.138" y1="11.317" y2="10.922" gradientUnits="userSpaceOnUse"><stop class="bjn-s4bel"/><stop offset="1" class="aprlu01bv"/></linearGradient><linearGradient id="iPqkcde" x1="18.882" x2="17.611" y1="10.186" y2="11.2" gradientUnits="userSpaceOnUse"><stop class="hcyruib3x"/><stop offset="1" class="ba065yvkm"/></linearGradient><linearGradient id="i9kjcHc" x1="18.482" x2="17.951" y1="12.297" y2="11.579" gradientUnits="userSpaceOnUse"><stop class="zn5fmlbvx"/><stop offset="1" class="t9-akpk6y"/></linearGradient><linearGradient id="i5BOS1b" x1="13.367" x2="13.537" y1="5.728" y2="5.783" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ioeUCgH" x1="9.216" x2="4.169" y1="25.61" y2="23.375" gradientUnits="userSpaceOnUse"><stop class="tlllib2dn"/><stop offset="1" class="xrnpsubav"/></linearGradient><linearGradient id="ircrhgc" x1="19.635" x2="19.31" y1="11.928" y2="18.625" gradientUnits="userSpaceOnUse"><stop class="o4lbhdh6k"/><stop offset="1" class="bu3azkbir"/></linearGradient><filter id="iSo21lb" width="4.713" height="2.925" x="5.124" y="22.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="i5E9Xjc" width="10.328" height="8.578" x="8.637" y="15.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.501961 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iFvuUmC" width="3.953" height="7.5" x="8.748" y="17.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_462" stdDeviation=".25"/></filter><filter id="iI8UYFd" width="3.602" height="3.602" x="9.927" y="26.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_462" stdDeviation=".125"/></filter><filter id="iqMgWvb" width="7.828" height="7.731" x="11.107" y="18.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.0745098 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iWqLcPA" width="4.543" height="3.256" x="5.279" y="23.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.360784 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iaX2mRd" width="8.506" height="4.313" x="12.56" y="15.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.270588 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iO4gnRJ" width="8.267" height="8.267" x="16.48" y="19.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.611765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iVO9wxe" width="9.68" height="9.83" x="15.849" y="18.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.4 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="ig31cob" width="3.273" height="3.273" x="18.952" y="22.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.678431 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_462"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_462" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.207843 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_462"/></filter><filter id="i0NX5Ee" width="2.245" height="2.245" x="19.566" y="22.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_462" stdDeviation=".05"/></filter><filter id="icCUGgd" width="9.402" height="9.402" x="16.122" y="19.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_462" stdDeviation=".075"/></filter><filter id="iysJH2N" width="12.217" height="12.217" x="14.674" y="17.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_462" stdDeviation=".15"/></filter><filter id="iF4yj1U" width="3.238" height="8.483" x="17.358" y="10.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.172549 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iFJztqe" width="4.32" height="5.224" x="12.51" y="3.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.172549 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iL6VPJb" width="5.336" height="4.75" x="12.346" y="2.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iJ9jKFe" width=".946" height=".439" x="13.135" y="4.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_462"/></filter><filter id="iq4mfFe" width="4.025" height="1.2" x="20.891" y="11.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_462" stdDeviation=".225"/></filter><filter id="iE5xSge" width="4.231" height="2.622" x="5.585" y="23.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_462" stdDeviation=".2"/></filter><filter id="iyAfefb" width="2.625" height="7.734" x="18.044" y="11.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_462" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-manual-wheelchair-dark" /></template>
<style>
.a9m8t591o {
  stop-color: var(--svg-color--5f3b5c, #5F3B5C);
}

.a9nytvbby {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m6.185 24.188l3.031 1.422");
}

.al52zb3wa {
  stop-color: var(--svg-color--5d4b4a, #5D4B4A);
}

.answrebhr {
  stop-color: var(--svg-color--79747b, #79747B);
}

.aprlu01bv {
  stop-color: var(--svg-color--e46821, #E46821);
  stop-opacity: 0;
}

.ba065yvkm {
  stop-color: var(--svg-color--ff973e, #FF973E);
  stop-opacity: 0;
}

.bc6qfubfl {
  stop-color: var(--svg-color--444043, #444043);
}

.bfwbq1bpl {
  stop-color: var(--svg-color--615f82, #615F82);
}

.bgt2mc6fp {
  stop-color: var(--svg-color--4e4558, #4E4558);
}

.bhe8i4mgj {
  d: path("M16.189 10.356a1.11 1.11 0 1 1 1.813-1.283l1.483 2.107c-.871.48-1.793 1.29-1.793 1.29z");
}

.bjn-s4bel {
  stop-color: var(--svg-color--e46821, #E46821);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.br5egpbia {
  stop-color: var(--svg-color--96909f, #96909F);
}

.bspgbrb6c {
  stop-color: var(--svg-color--da5b25, #DA5B25);
  stop-opacity: 0;
}

.bu3azkbir {
  stop-color: var(--svg-color--61504f, #61504F);
}

.bxntujdns {
  stop-color: var(--svg-color--8c8181, #8C8181);
}

.c-qoub4hl {
  stop-color: var(--svg-color--4a3736, #4A3736);
}

.c9gtc1bjl {
  stop-color: var(--svg-color--c2b1db, #C2B1DB);
}

.cjqgdpbwq {
  stop-color: var(--svg-color--4d3659, #4D3659);
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.cod3s5bmi {
  stop-color: var(--svg-color--eb8310, #EB8310);
  stop-opacity: 0;
}

.cwu_shb3d {
  stop-color: var(--svg-color--bf223d, #BF223D);
}

.d_4otnung {
  stop-color: var(--svg-color--948f93, #948F93);
}

.d0kv1cyul {
  stop-color: var(--svg-color--5b4542, #5B4542);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dqwirq1wj {
  stop-color: var(--svg-color--df5322, #DF5322);
}

.dr65abcro {
  stop-color: var(--svg-color--b61f30, #B61F30);
}

.duh2_cb1g {
  cx: 20.689px;
  cy: 23.846px;
  r: 4.059px;
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e3f4ywbbl {
  stop-color: var(--svg-color--64487f, #64487F);
  stop-opacity: 0;
}

.ennuonbfb {
  stop-color: var(--svg-color--675a75, #675A75);
  stop-opacity: 0;
}

.erfrsrblk {
  stop-color: var(--svg-color--7a727f, #7A727F);
  stop-opacity: 0;
}

.err_zmbut {
  cx: 17.858px;
  cy: 17.749px;
  r: 0.494px;
}

.f8tap8bxm {
  width: 7.832px;
  height: 1.372px;
  x: 8.206px;
  y: 26.152px;
  rx: 0.686px;
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
}

.fcmye_39g {
  fill: var(--svg-color--472f2c, #472F2C);
  d: path("m18.655 13.43l-1.025-1.344l1.418-1.132c.203.238.703.941 1.144 1.523c.452.595.448 1.383.352 1.734c-.232 1.053-.753 3.316-.922 3.954c-.211.797-.461.945-.938 1.054s-1.285-.312-1.222-.93c.027-.48.386-.695.644-1.484c.218-.871.512-2.274.642-2.99a.5.5 0 0 0-.093-.385");
}

.fiiks7b8f {
  stop-color: var(--svg-color--301d2f, #301D2F);
}

.fk7o7rbxe {
  d: path("M12.722 6.389a.9.9 0 0 0 .147-.453l.16-.032l.202 1c-.166.16-.443.196-.56.03c-.102-.142-.09-.347.051-.545");
}

.ft5dv1b6b {
  fill: none;
}

.fzo002mry {
  stop-color: var(--svg-color--79747b, #79747B);
  stop-opacity: 0;
}

.g0aomjwhv {
  stop-color: var(--svg-color--49344d, #49344D);
  stop-opacity: 0;
}

.g4u-v_bhx {
  stop-color: var(--svg-color--89828d, #89828D);
  stop-opacity: 0;
}

.g6i5vgbtc {
  stop-color: var(--svg-color--7f758d, #7F758D);
}

.g6s8itb9r {
  width: 1.242px;
  height: 6.695px;
  x: 11.107px;
  y: 22.337px;
  fill: var(--svg-color--776a86, #776A86);
  rx: 0.621px;
}

.gajflvy2u {
  d: path("m6.548 22.329l2.093-.059l.996.824l-.796 1.801l-3.498-1.576c-.174-.078-.278-.275-.182-.44c.242-.42.748-.55 1.387-.55");
}

.gf6pdh_6u {
  cx: 20.689px;
  cy: 23.846px;
  r: 0.973px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.gldbv0pab {
  stop-color: var(--svg-color--948f93, #948F93);
  stop-opacity: 0;
}

.gmz24obej {
  stop-color: var(--svg-color--3f1d1d, #3F1D1D);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gxz42mfas {
  d: path("M12.747 5.492c-.11-.72.05-1.11.139-1.232l3.317-.674l.627 2.8c-.387 2.043-2.722 2.602-3.211 1.99c-.49-.61-.744-2.052-.872-2.884");
}

.h_vbtipyr {
  stop-color: var(--svg-color--5f5168, #5F5168);
  stop-opacity: 0;
}

.h0a-qhb0e {
  stop-color: var(--svg-color--e35373, #E35373);
  stop-opacity: 0;
}

.hcyruib3x {
  stop-color: var(--svg-color--ff973e, #FF973E);
}

.hj58w-1de {
  stop-color: var(--svg-color--444043, #444043);
  stop-opacity: 0;
}

.hr_tvphim {
  d: path("M11.91 15.274h7.056v3.156h-6.844l-2.406 5.172l-1.079-1.328c.157-.797.594-3.055.961-4.836c.376-1.82 1.594-2.164 2.313-2.164");
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.i2tkr35ot {
  stop-color: var(--svg-color--524a5b, #524A5B);
  stop-opacity: 0;
}

.id-v9-mic {
  stop-color: var(--svg-color--342252, #342252);
}

.ig81yhx8p {
  stop-color: var(--svg-color--cd3945, #CD3945);
}

.il80kqqaz {
  width: 4.227px;
  height: 1.211px;
  x: 20.669px;
  y: 11.133px;
  rx: 0.605px;
}

.ildpa548e {
  stop-color: var(--svg-color--3b3145, #3B3145);
}

.imqdecrjn {
  width: 1.242px;
  height: 6.695px;
  x: 11.107px;
  y: 22.337px;
  rx: 0.621px;
}

.io62jp_6h {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
}

.j5rtt4bpo {
  stop-color: var(--svg-color--4e4558, #4E4558);
  stop-opacity: 0;
}

.ja_znnx3a {
  stop-color: var(--svg-color--423650, #423650);
}

.ja7250b2j {
  d: path("M15.382 15.278c-.31-1.037-.936-3.994-.588-5.738c.437-1.446 1.742-1.461 2.375-1.39c.773.085 1.601.476 2.039 1.835c.453 1.25.58 4.08.632 5.445h-.875v-.152z");
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jli-mvbgu {
  stop-color: var(--svg-color--ca283c, #CA283C);
}

.jz-3fab0l {
  stop-color: var(--svg-color--301d2f, #301D2F);
  stop-opacity: 0;
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.kqmyk7boa {
  stop-color: var(--svg-color--c43f0c, #C43F0C);
}

.ktc-s82to {
  stop-color: var(--svg-color--615f82, #615F82);
  stop-opacity: 0;
}

.ku1djbbcg {
  stop-color: var(--svg-color--64487f, #64487F);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l2hjghxql {
  fill: var(--svg-color--eb7f39, #EB7F39);
  d: path("M15.382 15.278c-.31-1.037-.936-3.994-.588-5.738c.437-1.446 1.742-1.461 2.375-1.39c.773.085 1.601.476 2.039 1.835c.453 1.25.58 4.08.632 5.445h-.875v-.152z");
}

.laa0aab1b {
  stop-color: var(--svg-color--46295f, #46295F);
}

.lfwvarbqo {
  stop-color: var(--svg-color--1b1423, #1B1423);
}

.lk-x1tbux {
  cx: 20.823px;
  cy: 23.712px;
  r: 4.476px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.lucd7-9cq {
  stop-color: var(--svg-color--3d2c4c, #3D2C4C);
}

.lvn5-ac9d {
  stop-color: var(--svg-color--c62f3a, #C62F3A);
}

.m0eeoe78x {
  cx: 11.728px;
  cy: 28.391px;
  r: 1.551px;
}

.mle7sl8ks {
  fill: var(--svg-color--553750, #553750);
  d: path("m9.248 24.079l1.921-6.5l1.032 1.75z");
}

.mnp_vbc6i {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M13.61 5.095a.7.7 0 0 0-.195.026a.136.136 0 0 1-.087-.258a1 1 0 0 1 .281-.04c.118 0 .26.018.394.08a.136.136 0 1 1-.115.247a.7.7 0 0 0-.278-.055");
}

.mu7vrc9io {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.34 6.106l.879-.179c-.07-.347-.325-.59-.567-.54c-.243.049-.382.37-.311.719");
}

.mz7wlj55e {
  stop-color: var(--svg-color--3f2245, #3F2245);
  stop-opacity: 0;
}

.n0w_cmcuq {
  stop-color: var(--svg-color--523c64, #523C64);
}

.n3h2abc_m {
  stop-color: var(--svg-color--654970, #654970);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.naoj9jbij {
  stop-color: var(--svg-color--544340, #544340);
  stop-opacity: 0;
}

.ndh-ggbqf {
  stop-color: var(--svg-color--544340, #544340);
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.nsyby5bts {
  fill: var(--svg-color--cb3c04, #CB3C04);
  d: path("M17.689 12.465c.426-.109 1.248-.693 1.789-1.293c-.414.045-1.345.378-1.789 1.293");
}

.nu7p8_blk {
  cx: 13.432px;
  cy: 5.763px;
  rx: 0.059px;
  ry: 0.08px;
}

.numeh5b7w {
  stop-color: var(--svg-color--443534, #443534);
}

.o-ce7bc5n {
  stop-color: var(--svg-color--ff9a3a, #FF9A3A);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o2t29rbsm {
  stop-color: var(--svg-color--37213e, #37213E);
}

.o4lbhdh6k {
  stop-color: var(--svg-color--614f4e, #614F4E);
}

.o50-1mg1f {
  stop-color: var(--svg-color--df5322, #DF5322);
  stop-opacity: 0;
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.oeytnrb8l {
  d: path("M12.379 3.399c.123-.476.598-.68.848-.717c.772-.113.93.13 1.592-.153c.7-.3 1.069-.33 1.41-.25l.006.001c.337.077 1.033.237 1.298 1.541c.244 1.201-.056 1.923-.217 2.192l.044.006c.22.033.35.234.318.455c-.028.189-.23.335-.519.348c-.33.014-.574.018-.766.02a.225.225 0 0 1-.221-.182l-.201-.989a.9.9 0 0 0-.574-.653c-.101-.428-.273-.6-.51-.66c-.391-.1-.485.008-1.347.13c-.914.128-1.315-.494-1.161-1.09");
}

.ogmjrqbhz {
  d: path("m15.39 6.3l-.082-1.315A.659.659 0 0 1 15.39 6.3");
}

.om366ybrp {
  stop-color: var(--svg-color--3d292a, #3D292A);
}

.oqr4-mbfk {
  stop-color: var(--svg-color--332156, #332156);
}

.plchgbb7u {
  fill-rule: evenodd;
  d: path("M11.107 19.782c0-.483.337-.797.82-.797h7.008v7.531H14.21a.895.895 0 0 1-.864-.686a1.86 1.86 0 0 0-.562-.924a1.87 1.87 0 0 0-.928-.462a.896.896 0 0 1-.748-.877zm1.5.453a.25.25 0 0 0-.25.25v2.488c0 .18.12.335.288.4c.35.136.682.339.977.607c.328.297.58.647.752 1.023c.07.154.22.263.39.263h2.921v-5.031z");
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.poxnejmkd {
  fill: var(--svg-color--f67624, #F67624);
  d: path("M16.189 10.356a1.11 1.11 0 1 1 1.813-1.283l1.483 2.107c-.871.48-1.793 1.29-1.793 1.29z");
}

.pyh7r6bag {
  stop-color: var(--svg-color--980a27, #980A27);
}

.q6suc5ubz {
  stop-color: var(--svg-color--7a727f, #7A727F);
}

.qb3gn8bfr {
  stop-color: var(--svg-color--8a7794, #8A7794);
  stop-opacity: 0;
}

.qb6tigb_q {
  d: path("M11.107 17.822a.4.4 0 0 1 .4-.4h8.881v2.508h-9.281z");
}

.qp48p8b-b {
  fill-rule: evenodd;
  d: path("M14.486 17.068a.775.775 0 0 0-.776.775v2.388h-1a.15.15 0 0 1-.15-.15v-2.238c0-1.063.862-1.925 1.926-1.925h6.18a.25.25 0 0 1 .25.25v2.749h-1.15v-1.85z");
}

.qu8oblblu {
  stop-color: var(--svg-color--eb8310, #EB8310);
}

.qx2qyypot {
  stop-color: var(--svg-color--2b1e2d, #2B1E2D);
}

.r04agib6p {
  stop-color: var(--svg-color--3f2245, #3F2245);
}

.rg3z6xbem {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
  stop-opacity: 0;
}

.rgr8nhbdi {
  stop-color: var(--svg-color--654970, #654970);
  stop-opacity: 0;
}

.rijqbwbix {
  stop-color: var(--svg-color--938c9b, #938C9B);
  stop-opacity: 0;
}

.roww1df0l {
  stop-color: var(--svg-color--675a75, #675A75);
}

.rs99u8bqf {
  stop-color: var(--svg-color--bb3161, #BB3161);
}

.s_nhb9bnh {
  stop-color: var(--svg-color--4e4b80, #4E4B80);
  stop-opacity: 0;
}

.s2_38pb8q {
  d: path("m13.705 6.032l-.01-.065c-.033-.165-.13-.284-.216-.267c-.086.018-.13.166-.096.33q.007.034.017.064z");
}

.sa2yvrtdg {
  stop-color: var(--svg-color--918697, #918697);
}

.skmvm0bcw {
  stop-color: var(--svg-color--ff9a3a, #FF9A3A);
  stop-opacity: 0;
}

.sl36r4bkw {
  cx: 11.728px;
  cy: 28.391px;
  r: 1.723px;
}

.sqtinbbgr {
  stop-color: var(--svg-color--cd3945, #CD3945);
  stop-opacity: 0;
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.sstiaym3o {
  stop-color: var(--svg-color--655558, #655558);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.szqa4cczu {
  stop-color: var(--svg-color--524a5b, #524A5B);
}

.t9-akpk6y {
  stop-color: var(--svg-color--f97f2a, #F97F2A);
  stop-opacity: 0;
}

.t9-j-pbql {
  stop-color: var(--svg-color--2f1f36, #2F1F36);
  stop-opacity: 0;
}

.tis1nnbrp {
  stop-color: var(--svg-color--2f1f36, #2F1F36);
}

.tlllib2dn {
  stop-color: var(--svg-color--a198a7, #A198A7);
}

.tz8tjvbjf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m18.966 11.844l.84 1.273a.96.96 0 0 1 .142.732a49 49 0 0 1-1.204 4.329");
}

.u245iqdps {
  stop-color: var(--svg-color--938c9b, #938C9B);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.umq_hfbdq {
  cx: 20.783px;
  cy: 23.614px;
  r: 5.559px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.uqxwa8ern {
  stop-color: var(--svg-color--3c2053, #3C2053);
}

.us60yytqw {
  stop-color: var(--svg-color--3b223c, #3B223C);
  stop-opacity: 0;
}

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v06h3pbnx {
  stop-color: var(--svg-color--3f2c51, #3F2C51);
}

.v1h4bu_vp {
  stroke: var(--svg-color--4c3e59, #4C3E59);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.341 11.659h3.125");
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vp5ble8bb {
  stop-color: var(--svg-color--89828d, #89828D);
}

.vxrkdvuju {
  stop-color: var(--svg-color--31223f, #31223F);
  stop-opacity: 0;
}

.w-8ci9bkh {
  stop-color: var(--svg-color--c8325e, #C8325E);
}

.w1vxk9vjl {
  width: 4.847px;
  height: 1.452px;
  x: 5.644px;
  y: 23.445px;
  rx: 0.726px;
}

.w1z7h-3do {
  fill-rule: evenodd;
  d: path("M20.689 30.114a6.267 6.267 0 1 0 0-12.535a6.267 6.267 0 0 0 0 12.535m0-1.428a4.84 4.84 0 1 0 0-9.68a4.84 4.84 0 0 0 0 9.68");
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.w6dy-su5q {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M14.204 6.961a.113.113 0 0 1 .03.158c-.169.25-.464.366-.56.395a.113.113 0 0 1-.067-.216c.082-.026.315-.121.44-.306a.113.113 0 0 1 .157-.03");
}

.w8c0-qbso {
  fill: var(--svg-color--8a7e97, #8A7E97);
  fill-rule: evenodd;
  d: path("M20.689 28.686a4.84 4.84 0 1 0 0-9.68a4.84 4.84 0 0 0 0 9.68m0-.781a4.059 4.059 0 1 0 0-8.117a4.059 4.059 0 0 0 0 8.117");
}

.wpgayijbr {
  d: path("M13.88 5.998v-.004c-.058-.285-.227-.492-.378-.461s-.227.287-.168.572v.004z");
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.x3lzt0c-k {
  stop-color: var(--svg-color--d52e59, #D52E59);
}

.x4ldqjsok {
  stop-color: var(--svg-color--484151, #484151);
}

.x8v8a_bhe {
  stop-color: var(--svg-color--49344d, #49344D);
}

.xb91u7b-b {
  stop-color: var(--svg-color--3b223c, #3B223C);
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xrnpsubav {
  stop-color: var(--svg-color--a198a7, #A198A7);
  stop-opacity: 0;
}

.xudiynxns {
  stop-color: var(--svg-color--5f5168, #5F5168);
}

.xx326qbfg {
  d: path("m14.77 7.475l1.75-.896l.753 2.258l-1.77.646z");
}

.y-ecmf49q {
  cx: 20.689px;
  cy: 23.846px;
  r: 1.137px;
}

.y3ij90b8v {
  stop-color: var(--svg-color--8a7794, #8A7794);
}

.yc5oz8lws {
  d: path("M20.736 11.659h1.162v5.449h-1.162z");
}

.ym5c6ha3r {
  stop-color: var(--svg-color--980a27, #980A27);
  stop-opacity: 0;
}

.yp_2y0bkd {
  stop-color: var(--svg-color--d53155, #D53155);
}

.yqah6ebzx {
  stop-color: var(--svg-color--443534, #443534);
  stop-opacity: 0;
}

.ys8863_0j {
  stop-color: var(--svg-color--e35373, #E35373);
}

.yu7wmpb_a {
  stop-color: var(--svg-color--4b3d47, #4B3D47);
}

.yutdbcb6i {
  stop-color: var(--svg-color--655558, #655558);
  stop-opacity: 0;
}

.z_ue7__pa {
  width: 4.847px;
  height: 1.452px;
  x: 5.644px;
  y: 23.445px;
  fill: var(--svg-color--7c767d, #7C767D);
  rx: 0.726px;
}

.z-rtjcc0y {
  stop-color: var(--svg-color--31223f, #31223F);
}

.z0lvmp82d {
  fill: var(--svg-color--4d4a7f, #4D4A7F);
  d: path("m6.548 22.329l2.093-.059l.996.824l-.796 1.801l-3.498-1.576c-.174-.078-.278-.275-.182-.44c.242-.42.748-.55 1.387-.55");
}

.z3yur8boj {
  stop-color: var(--svg-color--dccaee, #DCCAEE);
}

.z4for55kd {
  stop-color: var(--svg-color--1b1423, #1B1423);
  stop-opacity: 0;
}

.zax-lz03d {
  stop-color: var(--svg-color--463a52, #463A52);
}

.zg7ndleiu {
  stop-color: var(--svg-color--443850, #443850);
}

.zige1b1kr {
  stop-color: var(--svg-color--6e5c72, #6E5C72);
  stop-opacity: 0;
}

.zn5fmlbvx {
  stop-color: var(--svg-color--f45e26, #F45E26);
}

.zuaxx5qad {
  stop-color: var(--svg-color--7f758d, #7F758D);
  stop-opacity: 0;
}

.zzc1m6bsl {
  stop-color: var(--svg-color--4b3d47, #4B3D47);
  stop-opacity: 0;
}

</style>
