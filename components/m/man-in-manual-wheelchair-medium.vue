<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#in6Ds1w)"><path class="q-oba-brr"/><path fill="url(#iNmfREb)" class="qf4ahy-vb"/><path fill="url(#i9AvWQl)" class="qf4ahy-vb"/><path fill="url(#iYWcKuI)" class="qf4ahy-vb"/></g><g filter="url(#i92bVxc)"><path fill="url(#i7GZCDd)" class="yffybzb-u"/><path fill="url(#iXm4vMc)" class="yffybzb-u"/><path fill="url(#iFdTrdj)" class="yffybzb-u"/><path fill="url(#itFrbEd)" class="yffybzb-u"/><path fill="url(#i6xWYwr)" class="yffybzb-u"/></g><g filter="url(#iNXIzKd)"><path class="qsd3axbbu"/></g><circle fill="url(#icFwuKz)" class="oqud28aht"/><circle fill="url(#iaIfZPd)" class="oqud28aht"/><g filter="url(#irigmGU)"><circle fill="url(#iK3pobd)" class="kghoj5bgq"/><circle fill="url(#i9PRIpd)" class="kghoj5bgq"/></g><rect class="yqc1nab6c"/><rect fill="url(#iYNrKVp)" class="lpakydbqp"/><rect fill="url(#ir7XKfb)" class="lpakydbqp"/><rect fill="url(#iQteaNb)" class="lpakydbqp"/><rect fill="url(#iv4Xv7c)" class="lpakydbqp"/><rect fill="url(#ishWQrb)" class="lpakydbqp"/><rect fill="url(#irvpuYS)" class="lpakydbqp"/><rect fill="url(#ifetCbb)" transform="rotate(-65.334 8.206 26.16)" class="xtpbi7bij"/><rect fill="url(#i4ygUXd)" transform="rotate(-65.334 8.206 26.16)" class="xtpbi7bij"/><path fill="url(#iSzfUNb)" class="b4-e2-gbm"/><path fill="url(#i3ZfQnn)" class="b4-e2-gbm"/><path fill="url(#isLgIdG)" class="b4-e2-gbm"/><path fill="url(#izOppkc)" class="b4-e2-gbm"/><path fill="url(#iliZfZb)" class="b4-e2-gbm"/><path fill="url(#iryuQiM)" class="b4-e2-gbm"/><g filter="url(#iUOnJ6F)"><path fill="url(#iQjyiSc)" clip-rule="evenodd" class="njeo6cbnd"/><path fill="url(#i00NIXO)" clip-rule="evenodd" class="njeo6cbnd"/></g><path fill="url(#iuyhYqd)" class="y1et6wboe"/><path fill="url(#ienkrUc)" class="y1et6wboe"/><path fill="url(#iD5FQKe)" class="y1et6wboe"/><path fill="url(#iQLfhac)" transform="rotate(16.465 20.736 11.666)" class="o40m93beq"/><g filter="url(#iDrUwLr)"><rect transform="rotate(24.427 5.644 23.453)" class="m7iuc4dex"/></g><rect fill="url(#i4wGnvd)" transform="rotate(24.427 5.644 23.453)" class="neo9oheok"/><g filter="url(#i8ZTaCc)"><path fill="url(#ittFeTW)" clip-rule="evenodd" class="payld_buq"/><path fill="url(#ijP6x3b)" clip-rule="evenodd" class="payld_buq"/><path fill="url(#izR4HZV)" clip-rule="evenodd" class="payld_buq"/></g><path fill="url(#ilF0IOI)" clip-rule="evenodd" class="gsfrfdcjp"/><path fill="url(#ihJXsYb)" clip-rule="evenodd" class="gsfrfdcjp"/><path fill="url(#igEh1Zq)" clip-rule="evenodd" class="gsfrfdcjp"/><rect fill="url(#ifiIEPb)" class="xw1yd7b4m"/><rect fill="url(#iiJ7Fkb)" class="xw1yd7b4m"/><g filter="url(#iTFHnLm)"><circle fill="url(#ikrYubb)" class="h1h6sybze"/></g><g filter="url(#igUuaGc)"><path clip-rule="evenodd" class="cz7_9nb2b"/></g><path class="m3k2otbwn"/><path fill="url(#iTtjw9d)" class="h60n43lug"/><path fill="url(#iZP0FMb)" class="h60n43lug"/><path fill="url(#ihTqCRo)" class="h60n43lug"/><path fill="url(#iRaIvJc)" class="h60n43lug"/><path fill="url(#iX4redb)" class="h60n43lug"/><path fill="url(#ig8KYxb)" class="h60n43lug"/><g filter="url(#i1fYRgj)"><circle fill="url(#iA1gkoc)" class="gj-hl3bkk"/></g><g filter="url(#idaHSCe)"><circle stroke="url(#iBHvUpc)" class="p48ep98ev"/></g><g filter="url(#izANBdc)"><circle stroke="url(#i7w63Xb)" class="ntfqjmbes"/></g><g filter="url(#iTzdvOT)"><circle stroke="url(#izPT17c)" class="skauz3b-z"/></g><circle fill="url(#ibiECWd)" class="o3m9u-0ht"/><path class="ant0zfbgv"/><g filter="url(#iTTvIWd)"><path class="dz3jjibsm"/></g><path class="pi4kpq5me"/><path fill="url(#iu7Uo5b)" class="cg-nm3loh"/><path fill="url(#itRBkIp)" class="cg-nm3loh"/><path fill="url(#i9Vr1Kb)" class="cg-nm3loh"/><g filter="url(#iv1GqLe)"><path class="i6jhn-b9u"/></g><g filter="url(#i74TQcc)"><path stroke="url(#iOJx7Zc)" class="tkokf6bzo"/></g><g filter="url(#iRWpqHc)"><path class="kp0cak77e"/></g><path fill="url(#i79l6CD)" class="ig8ctma4l"/><path fill="url(#iSGG61b)" class="ig8ctma4l"/><g filter="url(#itNQdUH)"><path fill="url(#i5rXCDc)" class="n4_7m0orx"/><path fill="url(#iHmNurF)" class="n4_7m0orx"/><path fill="url(#iCXamkc)" class="n4_7m0orx"/><path fill="url(#iMp1cOc)" class="n4_7m0orx"/></g><g filter="url(#iPAOZQb)"><path fill="url(#ikFEmod)" class="psavlgbrw"/></g><g filter="url(#iKgw0cb)"><path fill="url(#iYQVIEo)" class="psavlgbrw"/><path fill="url(#iEbQobb)" class="psavlgbrw"/><path fill="url(#ipjiJkM)" class="psavlgbrw"/></g><path fill="url(#itraoec)" class="b1er568nz"/><path fill="url(#iAh9fze)" class="b1er568nz"/><path fill="url(#ixMhj3b)" class="b1er568nz"/><path clip-rule="evenodd" class="bywyjz54i"/><path class="pid-dwbgb"/><path fill="url(#iBJVsEc)" class="ttw3dlkrn"/><path fill="url(#ifuKfwd)" class="rdox36bsx"/><ellipse fill="url(#izFCO9d)" transform="rotate(13.114 13.36 5.665)" class="bdy3pmjtl"/><g filter="url(#iQCGo4b)"><path clip-rule="evenodd" class="yhxa1th6k"/></g><defs><radialGradient id="iYWcKuI" cx="0" cy="0" r="1" gradientTransform="matrix(.7395 -.04828 .083 1.2714 5.124 22.922)" gradientUnits="userSpaceOnUse"><stop class="bfwbq1bpl"/><stop offset="1" class="ktc-s82to"/></radialGradient><radialGradient id="iXm4vMc" cx="0" cy="0" r="1" gradientTransform="rotate(109.319 -1.8 14.158)scale(5.76196 2.25923)" gradientUnits="userSpaceOnUse"><stop class="y3ij90b8v"/><stop offset="1" class="qb3gn8bfr"/></radialGradient><radialGradient id="iFdTrdj" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 0 0 12.1563 10.997 17.04)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="yutdbcb6i"/><stop offset="1" class="sstiaym3o"/></radialGradient><radialGradient id="itFrbEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.46875 5.125 0 16.06 18.008)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="yu7wmpb_a"/><stop offset="1" class="zzc1m6bsl"/></radialGradient><radialGradient id="iaIfZPd" cx="0" cy="0" r="1" gradientTransform="matrix(1.48438 0 0 3.64062 9.31 28.399)" gradientUnits="userSpaceOnUse"><stop class="answrebhr"/><stop offset="1" class="fzo002mry"/></radialGradient><radialGradient id="iK3pobd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.80266 4.80004 0 11.728 29.65)" gradientUnits="userSpaceOnUse"><stop class="ja_znnx3a"/><stop offset="1" class="ildpa548e"/></radialGradient><radialGradient id="i9PRIpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71875 1.03125 0 11.529 28.102)" gradientUnits="userSpaceOnUse"><stop class="z-rtjcc0y"/><stop offset="1" class="vxrkdvuju"/></radialGradient><radialGradient id="ir7XKfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.11265 -.46567 0 12.349 24.188)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="iQteaNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9265 -.24601 0 11.107 23.374)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="iv4Xv7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.69196 .27569 0 11.107 28.55)" gradientUnits="userSpaceOnUse"><stop class="q6suc5ubz"/><stop offset="1" class="erfrsrblk"/></radialGradient><radialGradient id="ishWQrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.94902 .80452 0 11.728 29.04)" gradientUnits="userSpaceOnUse"><stop class="ku1djbbcg"/><stop offset="1" class="e3f4ywbbl"/></radialGradient><radialGradient id="irvpuYS" cx="0" cy="0" r="1" gradientTransform="rotate(38.089 -28.898 29.322)scale(1.46908 .76568)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n3h2abc_m"/><stop offset="1" class="rgr8nhbdi"/></radialGradient><radialGradient id="ifetCbb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.01534 -.13834 .02815 -1.0205 13.906 26.94)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="rs99u8bqf"/><stop offset="1" class="lvn5-ac9d"/></radialGradient><radialGradient id="iliZfZb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07812 -.4219 .60152 -2.96294 17.591 18.977)" gradientUnits="userSpaceOnUse"><stop class="tis1nnbrp"/><stop offset="1" class="t9-j-pbql"/></radialGradient><radialGradient id="iryuQiM" cx="0" cy="0" r="1" gradientTransform="matrix(-.82813 0 0 -2.43007 12.81 18.195)" gradientUnits="userSpaceOnUse"><stop class="r04agib6p"/><stop offset="1" class="mz7wlj55e"/></radialGradient><radialGradient id="iuyhYqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.73101 -.3013 .92669 5.32391 15.358 8.834)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="eitmobczl"/><stop offset="1" class="l5cg6c78h"/></radialGradient><radialGradient id="ienkrUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.08802 .88154 -.75069 -.07495 16.788 6.97)" gradientUnits="userSpaceOnUse"><stop class="ef2avdbrg"/><stop offset="1" class="ju9-v_r3z"/></radialGradient><radialGradient id="iQLfhac" cx="0" cy="0" r="1" gradientTransform="matrix(.06825 -4.12415 .84696 .01402 21.263 15.614)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="w-8ci9bkh"/><stop offset="1" class="dr65abcro"/></radialGradient><radialGradient id="i4wGnvd" cx="0" cy="0" r="1" gradientTransform="matrix(.59496 -.39035 .70458 1.0739 5.739 24.62)" gradientUnits="userSpaceOnUse"><stop class="vp5ble8bb"/><stop offset="1" class="g4u-v_bhx"/></radialGradient><radialGradient id="ihJXsYb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.582 22.271)scale(5.3418)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="lfwvarbqo"/><stop offset="1" class="z4for55kd"/></radialGradient><radialGradient id="igEh1Zq" cx="0" cy="0" r="1" gradientTransform="rotate(-137.525 18.01 9.371)scale(12.5412 9.73796)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="jz-3fab0l"/><stop offset="1" class="fiiks7b8f"/></radialGradient><radialGradient id="iiJ7Fkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 .39452 -.43395 -.94526 25.03 11.351)" gradientUnits="userSpaceOnUse"><stop class="roww1df0l"/><stop offset="1" class="ennuonbfb"/></radialGradient><radialGradient id="ikrYubb" cx="0" cy="0" r="1" gradientTransform="matrix(4.09375 -5.53125 9.86398 7.30045 18.841 26.633)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="z3yur8boj"/><stop offset="1" class="c9gtc1bjl"/></radialGradient><radialGradient id="iTtjw9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.74147 5.7617 -2.39656 -.30841 15.433 8.135)" gradientUnits="userSpaceOnUse"><stop class="ovq8r3b0g"/><stop offset="1" class="wga3dymuf"/></radialGradient><radialGradient id="ihTqCRo" cx="0" cy="0" r="1" gradientTransform="matrix(1.91582 4.38908 -1.67362 .73053 17.924 12.933)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="kzwpp2bio"/><stop offset="1" class="joghibbew"/></radialGradient><radialGradient id="iRaIvJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60922 1.60922 -4.29661 -4.29661 19.285 8.664)" gradientUnits="userSpaceOnUse"><stop class="c4wvmccpi"/><stop offset="1" class="r1m1gebgj"/></radialGradient><radialGradient id="iX4redb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52492 -.37857 .69348 -4.62528 18.921 15.438)" gradientUnits="userSpaceOnUse"><stop class="i2tq4ccny"/><stop offset="1" class="ex22_1bvq"/></radialGradient><radialGradient id="ig8KYxb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40622 -7.30308 5.14902 -1.6965 18.239 15.438)" gradientUnits="userSpaceOnUse"><stop offset=".883" class="hqgfyu_2h"/><stop offset="1" class="citi-bbgf"/></radialGradient><radialGradient id="ibiECWd" cx="0" cy="0" r="1" gradientTransform="rotate(-73.593 20.77 -2.73)scale(.73297)" gradientUnits="userSpaceOnUse"><stop class="odw8jmnks"/><stop offset="1" class="dqa0zuk3f"/></radialGradient><radialGradient id="i9Vr1Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 -2.96876 2.35369 -1.598 18.428 11.754)" gradientUnits="userSpaceOnUse"><stop offset=".88" class="q0vv05bce"/><stop offset="1" class="rihq7ul5p"/></radialGradient><radialGradient id="i79l6CD" cx="0" cy="0" r="1" gradientTransform="matrix(.46877 .14257 -.20125 .66168 12.473 6.73)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="iSGG61b" cx="0" cy="0" r="1" gradientTransform="matrix(-.15893 -.2367 .35522 -.2385 12.89 6.939)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="iHmNurF" cx="0" cy="0" r="1" gradientTransform="rotate(171.683 7.598 3.29)scale(.76417 .93167)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="iCXamkc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.496 9.488 -1.898)scale(4.69098 1.8227)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="iMp1cOc" cx="0" cy="0" r="1" gradientTransform="matrix(.0704 .34615 -.53983 .10979 13.767 5.862)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="ikFEmod" cx="0" cy="0" r="1" gradientTransform="rotate(126.231 7.69 5.627)scale(4.20099 4.76366)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="iYQVIEo" cx="0" cy="0" r="1" gradientTransform="rotate(126.231 7.69 5.627)scale(4.20099 4.76366)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="i2p5fqtly"/><stop offset="1" class="pw8a02b5q"/></radialGradient><radialGradient id="iEbQobb" cx="0" cy="0" r="1" gradientTransform="rotate(70.138 5.961 13.693)scale(2.45204 1.08323)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="ltxof3fvo"/><stop offset="1" class="nj0viubvx"/></radialGradient><radialGradient id="ipjiJkM" cx="0" cy="0" r="1" gradientTransform="matrix(1.31233 -.3534 .69352 2.57528 12.19 4.25)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="id9lp4hub"/><stop offset="1" class="fed4ggbgk"/></radialGradient><radialGradient id="itraoec" cx="0" cy="0" r="1" gradientTransform="matrix(.60582 -.31786 .15514 .2957 15.372 5.384)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="iAh9fze" cx="0" cy="0" r="1" gradientTransform="rotate(67.662 3.859 14.004)scale(1.08622 1.13189)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="iBJVsEc" cx="0" cy="0" r="1" gradientTransform="matrix(.242 -.04922 .09562 .47016 13.51 5.939)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ifuKfwd" cx="0" cy="0" r="1" gradientTransform="matrix(.22125 -.045 .09738 .4788 13.366 5.988)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iNmfREb" x1="9.114" x2="8.197" y1="24.354" y2="23.872" gradientUnits="userSpaceOnUse"><stop offset=".209" class="id-v9-mic"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="i9AvWQl" x1="7.875" x2="8.165" y1="24.692" y2="23.936" gradientUnits="userSpaceOnUse"><stop offset=".122" class="oqr4-mbfk"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="i7GZCDd" x1="9.904" x2="16.06" y1="20.602" y2="17.227" gradientUnits="userSpaceOnUse"><stop class="sa2yvrtdg"/><stop offset="1" class="bxntujdns"/></linearGradient><linearGradient id="i6xWYwr" x1="9.06" x2="9.966" y1="19.852" y2="19.914" gradientUnits="userSpaceOnUse"><stop class="d_4otnung"/><stop offset="1" class="gldbv0pab"/></linearGradient><linearGradient id="icFwuKz" x1="11.919" x2="11.919" y1="30.242" y2="26.676" gradientUnits="userSpaceOnUse"><stop class="uqxwa8ern"/><stop offset=".596" class="qx2qyypot"/></linearGradient><linearGradient id="iYNrKVp" x1="12.349" x2="11.612" y1="26.776" y2="26.776" gradientUnits="userSpaceOnUse"><stop class="g6i5vgbtc"/><stop offset="1" class="zuaxx5qad"/></linearGradient><linearGradient id="i4ygUXd" x1="11.901" x2="11.813" y1="27.741" y2="26.988" gradientUnits="userSpaceOnUse"><stop class="pyh7r6bag"/><stop offset="1" class="ym5c6ha3r"/></linearGradient><linearGradient id="iSzfUNb" x1="12.351" x2="17.259" y1="18.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="n0w_cmcuq"/><stop offset="1" class="cjqgdpbwq"/></linearGradient><linearGradient id="i3ZfQnn" x1="15.747" x2="15.747" y1="17.43" y2="17.774" gradientUnits="userSpaceOnUse"><stop class="xb91u7b-b"/><stop offset="1" class="us60yytqw"/></linearGradient><linearGradient id="isLgIdG" x1="14.826" x2="14.826" y1="19.274" y2="18.227" gradientUnits="userSpaceOnUse"><stop class="x8v8a_bhe"/><stop offset="1" class="g0aomjwhv"/></linearGradient><linearGradient id="izOppkc" x1="11.107" x2="11.341" y1="19.039" y2="19.039" gradientUnits="userSpaceOnUse"><stop class="xudiynxns"/><stop offset="1" class="h_vbtipyr"/></linearGradient><linearGradient id="iQjyiSc" x1="15.021" x2="15.021" y1="18.992" y2="26.524" gradientUnits="userSpaceOnUse"><stop class="yp_2y0bkd"/><stop offset="1" class="jli-mvbgu"/></linearGradient><linearGradient id="i00NIXO" x1="11.107" x2="11.529" y1="21.287" y2="21.287" gradientUnits="userSpaceOnUse"><stop class="ig81yhx8p"/><stop offset="1" class="sqtinbbgr"/></linearGradient><linearGradient id="iD5FQKe" x1="15.379" x2="15.597" y1="9.164" y2="9.078" gradientUnits="userSpaceOnUse"><stop class="a-mj2kbzz"/><stop offset="1" class="ikw2jw0zo"/></linearGradient><linearGradient id="ittFeTW" x1="13.357" x2="19.091" y1="19.258" y2="16.008" gradientUnits="userSpaceOnUse"><stop class="x3lzt0c-k"/><stop offset="1" class="cwu_shb3d"/></linearGradient><linearGradient id="ijP6x3b" x1="21.17" x2="20.147" y1="17.385" y2="17.385" gradientUnits="userSpaceOnUse"><stop class="ys8863_0j"/><stop offset="1" class="h0a-qhb0e"/></linearGradient><linearGradient id="izR4HZV" x1="16.738" x2="16.738" y1="15.925" y2="16.258" gradientUnits="userSpaceOnUse"><stop class="io62jp_6h"/><stop offset="1" class="rg3z6xbem"/></linearGradient><linearGradient id="ilF0IOI" x1="24.529" x2="16.435" y1="19.477" y2="28.539" gradientUnits="userSpaceOnUse"><stop class="v06h3pbnx"/><stop offset="1" class="lucd7-9cq"/></linearGradient><linearGradient id="ifiIEPb" x1="21.013" x2="24.896" y1="11.883" y2="11.883" gradientUnits="userSpaceOnUse"><stop class="o2t29rbsm"/><stop offset="1" class="laa0aab1b"/></linearGradient><linearGradient id="iZP0FMb" x1="15.776" x2="15.776" y1="15.438" y2="12.435" gradientUnits="userSpaceOnUse"><stop class="cbjhvs5nl"/><stop offset="1" class="o1xcpgznb"/></linearGradient><linearGradient id="iA1gkoc" x1="21.497" x2="20.013" y1="22.992" y2="24.99" gradientUnits="userSpaceOnUse"><stop class="zax-lz03d"/><stop offset="1" class="zg7ndleiu"/></linearGradient><linearGradient id="iBHvUpc" x1="21.662" x2="20.279" y1="22.828" y2="24.555" gradientUnits="userSpaceOnUse"><stop offset=".139" class="szqa4cczu"/><stop offset=".488" class="i2tkr35ot"/></linearGradient><linearGradient id="i7w63Xb" x1="24.294" x2="18.169" y1="20.289" y2="27.93" gradientUnits="userSpaceOnUse"><stop offset=".066" class="u245iqdps"/><stop offset=".257" class="rijqbwbix"/><stop offset=".803" class="rijqbwbix"/><stop offset=".945" class="br5egpbia"/></linearGradient><linearGradient id="izPT17c" x1="24.498" x2="17.123" y1="19.215" y2="28.528" gradientUnits="userSpaceOnUse"><stop class="bgt2mc6fp"/><stop offset=".294" class="j5rtt4bpo"/><stop offset=".801" class="x4ldqjsok"/></linearGradient><linearGradient id="iu7Uo5b" x1="16.584" x2="17.131" y1="11.321" y2="10.926" gradientUnits="userSpaceOnUse"><stop class="cqt98rbmz"/><stop offset="1" class="j-xtgpjdr"/></linearGradient><linearGradient id="itRBkIp" x1="18.875" x2="17.604" y1="10.189" y2="11.203" gradientUnits="userSpaceOnUse"><stop class="vgltnv9qo"/><stop offset="1" class="rymgambwn"/></linearGradient><linearGradient id="iOJx7Zc" x1="9.216" x2="4.169" y1="25.617" y2="23.383" gradientUnits="userSpaceOnUse"><stop class="tlllib2dn"/><stop offset="1" class="xrnpsubav"/></linearGradient><linearGradient id="i5rXCDc" x1="15.449" x2="12.943" y1="6.162" y2="6.83" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="ixMhj3b" x1="15.336" x2="15.469" y1="5.455" y2="5.439" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="izFCO9d" x1="13.296" x2="13.463" y1="5.631" y2="5.685" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="in6Ds1w" width="4.713" height="2.925" x="5.124" y="22.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="i92bVxc" width="10.328" height="8.578" x="8.637" y="15.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.501961 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="iNXIzKd" width="3.953" height="7.5" x="8.747" y="17.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_470" stdDeviation=".25"/></filter><filter id="irigmGU" width="3.602" height="3.602" x="9.927" y="26.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_470" stdDeviation=".125"/></filter><filter id="iUOnJ6F" width="7.828" height="7.731" x="11.107" y="18.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.0745098 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="iDrUwLr" width="4.543" height="3.256" x="5.279" y="23.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.360784 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="i8ZTaCc" width="8.506" height="4.313" x="12.56" y="15.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.270588 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="iTFHnLm" width="8.267" height="8.267" x="16.48" y="19.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.611765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="igUuaGc" width="9.68" height="9.83" x="15.849" y="18.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.4 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="i1fYRgj" width="3.273" height="3.273" x="18.952" y="22.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.678431 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_470"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_470" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.207843 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_470"/></filter><filter id="idaHSCe" width="2.245" height="2.245" x="19.566" y="22.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_470" stdDeviation=".05"/></filter><filter id="izANBdc" width="9.401" height="9.401" x="16.122" y="19.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_470" stdDeviation=".075"/></filter><filter id="iTzdvOT" width="12.217" height="12.217" x="14.674" y="17.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_470" stdDeviation=".15"/></filter><filter id="iTTvIWd" width="3.238" height="8.483" x="17.358" y="10.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.392157 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="iv1GqLe" width="4.025" height="1.2" x="20.891" y="11.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_470" stdDeviation=".225"/></filter><filter id="i74TQcc" width="4.231" height="2.622" x="5.585" y="23.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_470" stdDeviation=".2"/></filter><filter id="iRWpqHc" width="2.78" height="8.181" x="17.891" y="11.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_470" stdDeviation=".25"/></filter><filter id="itNQdUH" width="4.308" height="5.21" x="12.44" y="3.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.329412 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter><filter id="iPAOZQb" width="6.026" height="4.705" x="11.751" y="2.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_470" result="effect2_innerShadow_4002_470"/></filter><filter id="iKgw0cb" width="6.026" height="4.705" x="11.751" y="2.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.266667 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.137255 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_470" result="effect2_innerShadow_4002_470"/></filter><filter id="iQCGo4b" width="1.073" height=".555" x="12.997" y="4.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_470"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-manual-wheelchair-medium" /></template>
<style>
.a-mj2kbzz {
  stop-color: var(--svg-color--a67a6e, #A67A6E);
}

.a9m8t591o {
  stop-color: var(--svg-color--5f3b5c, #5F3B5C);
}

.answrebhr {
  stop-color: var(--svg-color--79747b, #79747B);
}

.ant0zfbgv {
  fill: var(--svg-color--447199, #447199);
  d: path("M17.689 12.473c.426-.11 1.248-.693 1.789-1.293c-.414.044-1.345.377-1.79 1.293");
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.b1er568nz {
  d: path("m15.395 6.186l-.083-1.312a.657.657 0 0 1 .083 1.312");
}

.b4-e2-gbm {
  d: path("M11.107 17.83a.4.4 0 0 1 .4-.4h8.881v2.508h-9.281z");
}

.bdy3pmjtl {
  cx: 13.36px;
  cy: 5.665px;
  rx: 0.058px;
  ry: 0.079px;
}

.bfwbq1bpl {
  stop-color: var(--svg-color--615f82, #615F82);
}

.bgt2mc6fp {
  stop-color: var(--svg-color--4e4558, #4E4558);
}

.br5egpbia {
  stop-color: var(--svg-color--96909f, #96909F);
}

.bxntujdns {
  stop-color: var(--svg-color--8c8181, #8C8181);
}

.bywyjz54i {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M14.13 6.861a.113.113 0 0 1 .031.157c-.169.25-.463.365-.558.395a.113.113 0 1 1-.068-.216c.082-.025.314-.12.439-.306a.113.113 0 0 1 .157-.03");
}

.c4wvmccpi {
  stop-color: var(--svg-color--53b5f3, #53B5F3);
}

.c9gtc1bjl {
  stop-color: var(--svg-color--c2b1db, #C2B1DB);
}

.cbjhvs5nl {
  stop-color: var(--svg-color--225993, #225993);
}

.cg-nm3loh {
  d: path("M16.181 10.36a1.11 1.11 0 1 1 1.814-1.283l1.483 2.107c-.871.48-1.793 1.289-1.793 1.289z");
}

.citi-bbgf {
  stop-color: var(--svg-color--517c98, #517C98);
}

.cjqgdpbwq {
  stop-color: var(--svg-color--4d3659, #4D3659);
}

.cqt98rbmz {
  stop-color: var(--svg-color--377ecc, #377ECC);
}

.cwu_shb3d {
  stop-color: var(--svg-color--bf223d, #BF223D);
}

.cz7_9nb2b {
  fill: var(--svg-color--8a7e97, #8A7E97);
  fill-rule: evenodd;
  d: path("M20.689 28.694a4.84 4.84 0 1 0 0-9.68a4.84 4.84 0 0 0 0 9.68m0-.782a4.059 4.059 0 1 0 0-8.117a4.059 4.059 0 0 0 0 8.117");
}

.d_4otnung {
  stop-color: var(--svg-color--948f93, #948F93);
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.dqa0zuk3f {
  stop-color: var(--svg-color--8e5d49, #8E5D49);
}

.dr65abcro {
  stop-color: var(--svg-color--b61f30, #B61F30);
}

.dz3jjibsm {
  fill: var(--svg-color--a87f6b, #A87F6B);
  d: path("m18.655 13.438l-1.026-1.344l1.418-1.133c.204.238.704.941 1.145 1.524c.451.595.448 1.382.352 1.734c-.232 1.052-.753 3.316-.922 3.953c-.211.797-.461.945-.938 1.055s-1.285-.313-1.223-.93c.028-.48.387-.695.645-1.484c.218-.872.512-2.274.642-2.99a.5.5 0 0 0-.094-.386");
}

.e3f4ywbbl {
  stop-color: var(--svg-color--64487f, #64487F);
  stop-opacity: 0;
}

.ef2avdbrg {
  stop-color: var(--svg-color--8e695b, #8E695B);
}

.eitmobczl {
  stop-color: var(--svg-color--9b6a61, #9B6A61);
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.ennuonbfb {
  stop-color: var(--svg-color--675a75, #675A75);
  stop-opacity: 0;
}

.erfrsrblk {
  stop-color: var(--svg-color--7a727f, #7A727F);
  stop-opacity: 0;
}

.ex22_1bvq {
  stop-color: var(--svg-color--2e61a0, #2E61A0);
  stop-opacity: 0;
}

.fed4ggbgk {
  stop-color: var(--svg-color--634d4a, #634D4A);
  stop-opacity: 0;
}

.fiiks7b8f {
  stop-color: var(--svg-color--301d2f, #301D2F);
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

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gj-hl3bkk {
  cx: 20.689px;
  cy: 23.854px;
  r: 1.137px;
}

.gldbv0pab {
  stop-color: var(--svg-color--948f93, #948F93);
  stop-opacity: 0;
}

.gsfrfdcjp {
  fill-rule: evenodd;
  d: path("M20.689 30.121a6.268 6.268 0 1 0 0-12.535a6.268 6.268 0 0 0 0 12.535m0-1.427a4.84 4.84 0 1 0 0-9.68a4.84 4.84 0 0 0 0 9.68");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h_vbtipyr {
  stop-color: var(--svg-color--5f5168, #5F5168);
  stop-opacity: 0;
}

.h0a-qhb0e {
  stop-color: var(--svg-color--e35373, #E35373);
  stop-opacity: 0;
}

.h1h6sybze {
  cx: 20.689px;
  cy: 23.854px;
  r: 4.059px;
}

.h60n43lug {
  d: path("M15.382 15.286c-.31-1.038-.936-3.994-.589-5.739c.438-1.445 1.743-1.46 2.375-1.39c.774.085 1.602.476 2.04 1.835c.453 1.25.58 4.081.632 5.446h-.875v-.152z");
}

.hqgfyu_2h {
  stop-color: var(--svg-color--517c98, #517C98);
  stop-opacity: 0;
}

.i2p5fqtly {
  stop-color: var(--svg-color--52343b, #52343B);
}

.i2tkr35ot {
  stop-color: var(--svg-color--524a5b, #524A5B);
  stop-opacity: 0;
}

.i2tq4ccny {
  stop-color: var(--svg-color--21436f, #21436F);
}

.i6jhn-b9u {
  stroke: var(--svg-color--4c3e59, #4C3E59);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.341 11.666h3.125");
}

.id-v9-mic {
  stop-color: var(--svg-color--342252, #342252);
}

.id9lp4hub {
  stop-color: var(--svg-color--634d4a, #634D4A);
}

.ig81yhx8p {
  stop-color: var(--svg-color--cd3945, #CD3945);
}

.ig8ctma4l {
  d: path("M12.653 6.29a.9.9 0 0 0 .146-.45l.159-.033l.203.997c-.166.16-.442.196-.56.03c-.101-.14-.089-.345.051-.543");
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ikw2jw0zo {
  stop-color: var(--svg-color--a67a6e, #A67A6E);
  stop-opacity: 0;
}

.ildpa548e {
  stop-color: var(--svg-color--3b3145, #3B3145);
}

.io62jp_6h {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
}

.j-xtgpjdr {
  stop-color: var(--svg-color--3e87e1, #3E87E1);
  stop-opacity: 0;
}

.j5rtt4bpo {
  stop-color: var(--svg-color--4e4558, #4E4558);
  stop-opacity: 0;
}

.ja_znnx3a {
  stop-color: var(--svg-color--423650, #423650);
}

.jli-mvbgu {
  stop-color: var(--svg-color--ca283c, #CA283C);
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.joghibbew {
  stop-color: var(--svg-color--2462c1, #2462C1);
  stop-opacity: 0;
}

.ju9-v_r3z {
  stop-color: var(--svg-color--8e695b, #8E695B);
  stop-opacity: 0;
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.jz-3fab0l {
  stop-color: var(--svg-color--301d2f, #301D2F);
  stop-opacity: 0;
}

.kghoj5bgq {
  cx: 11.728px;
  cy: 28.399px;
  r: 1.551px;
}

.kp0cak77e {
  stroke: var(--svg-color--bc9682, #BC9682);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m18.966 11.852l.84 1.272a.98.98 0 0 1 .146.733c-.222 1.099-.717 3.27-1.36 4.776");
}

.kpbiulbbs {
  stop-color: var(--svg-color--ffa629, #FFA629);
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.ktc-s82to {
  stop-color: var(--svg-color--615f82, #615F82);
  stop-opacity: 0;
}

.ku1djbbcg {
  stop-color: var(--svg-color--64487f, #64487F);
}

.kzwpp2bio {
  stop-color: var(--svg-color--2462c1, #2462C1);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.l5cg6c78h {
  stop-color: var(--svg-color--ba8f7c, #BA8F7C);
}

.laa0aab1b {
  stop-color: var(--svg-color--46295f, #46295F);
}

.lfwvarbqo {
  stop-color: var(--svg-color--1b1423, #1B1423);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.lpakydbqp {
  width: 1.242px;
  height: 6.695px;
  x: 11.107px;
  y: 22.344px;
  rx: 0.621px;
}

.ltxof3fvo {
  stop-color: var(--svg-color--624646, #624646);
}

.lucd7-9cq {
  stop-color: var(--svg-color--3d2c4c, #3D2C4C);
}

.lvn5-ac9d {
  stop-color: var(--svg-color--c62f3a, #C62F3A);
}

.m3k2otbwn {
  fill: var(--svg-color--3779c2, #3779C2);
  d: path("M15.382 15.286c-.31-1.038-.936-3.994-.589-5.739c.438-1.445 1.743-1.46 2.375-1.39c.774.085 1.602.476 2.04 1.835c.453 1.25.58 4.081.632 5.446h-.875v-.152z");
}

.m7iuc4dex {
  width: 4.847px;
  height: 1.452px;
  x: 5.644px;
  y: 23.453px;
  fill: var(--svg-color--7c767d, #7C767D);
  rx: 0.726px;
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

.n4_7m0orx {
  d: path("M12.677 5.396c-.11-.717.05-1.106.138-1.228l3.308-.672l.625 2.792c-.385 2.036-2.713 2.593-3.201 1.985c-.488-.61-.742-2.047-.87-2.877");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.neo9oheok {
  width: 4.847px;
  height: 1.452px;
  x: 5.644px;
  y: 23.453px;
  rx: 0.726px;
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nj0viubvx {
  stop-color: var(--svg-color--624646, #624646);
  stop-opacity: 0;
}

.njeo6cbnd {
  fill-rule: evenodd;
  d: path("M11.107 19.79c0-.484.337-.798.82-.798h7.008v7.532h-4.726a.895.895 0 0 1-.864-.686a1.86 1.86 0 0 0-.562-.925a1.86 1.86 0 0 0-.928-.462a.896.896 0 0 1-.748-.876zm1.5.452a.25.25 0 0 0-.25.25v2.489c0 .18.12.335.288.4c.35.136.682.338.977.606c.328.297.58.647.752 1.023c.07.155.22.264.39.264h2.92v-5.032z");
}

.ntfqjmbes {
  cx: 20.823px;
  cy: 23.72px;
  r: 4.476px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.o1xcpgznb {
  stop-color: var(--svg-color--2e6cb2, #2E6CB2);
  stop-opacity: 0;
}

.o2t29rbsm {
  stop-color: var(--svg-color--37213e, #37213E);
}

.o3m9u-0ht {
  cx: 17.858px;
  cy: 17.756px;
  r: 0.494px;
}

.o40m93beq {
  d: path("M20.736 11.666h1.162v5.449h-1.162z");
}

.odw8jmnks {
  stop-color: var(--svg-color--a17467, #A17467);
}

.oqr4-mbfk {
  stop-color: var(--svg-color--332156, #332156);
}

.oqud28aht {
  cx: 11.728px;
  cy: 28.399px;
  r: 1.723px;
}

.ovq8r3b0g {
  stop-color: var(--svg-color--4b9cd5, #4B9CD5);
}

.p48ep98ev {
  cx: 20.689px;
  cy: 23.854px;
  r: 0.973px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.payld_buq {
  fill-rule: evenodd;
  d: path("M14.486 17.075a.775.775 0 0 0-.776.775v2.388h-1a.15.15 0 0 1-.15-.15V17.85c0-1.063.862-1.925 1.926-1.925h6.18a.25.25 0 0 1 .25.25v2.75h-1.15v-1.85z");
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.pi4kpq5me {
  fill: var(--svg-color--3289e6, #3289E6);
  d: path("M16.181 10.36a1.11 1.11 0 1 1 1.814-1.283l1.483 2.107c-.871.48-1.793 1.289-1.793 1.289z");
}

.pid-dwbgb {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.269 6.009l.876-.179c-.07-.347-.324-.588-.566-.539c-.242.05-.38.37-.31.718");
}

.psavlgbrw {
  d: path("M13.108 4.614c-.582.118-.925-.154-1.037-.56c-.118-.582.3-.796.47-.85c.189-.06.26-.096.492-.341a.82.82 0 0 1 .789-.25c.144.035.441.007.636-.098c.325-.174.596-.225.904-.075c.214.104.35.076.572.031c.305-.062.591.022.816.13c.672.322.914 1.85.8 2.76c-.11.871-.504 1.051-.857 1.09c-.424.047-.594-.247-.71-.497c-.093-.2-.32-.665-.423-.873a.97.97 0 0 1-.591-.5c-.159-.325-.514-.293-.745-.223c-.14.043-.534.138-1.116.256");
}

.pw8a02b5q {
  stop-color: var(--svg-color--492b38, #492B38);
}

.pyh7r6bag {
  stop-color: var(--svg-color--980a27, #980A27);
}

.q-oba-brr {
  fill: var(--svg-color--4d4a7f, #4D4A7F);
  d: path("m6.547 22.336l2.094-.058l.996.824l-.796 1.8l-3.499-1.576c-.173-.078-.277-.274-.182-.44c.243-.42.749-.55 1.387-.55");
}

.q0vv05bce {
  stop-color: var(--svg-color--4098d6, #4098D6);
  stop-opacity: 0;
}

.q6suc5ubz {
  stop-color: var(--svg-color--7a727f, #7A727F);
}

.qb3gn8bfr {
  stop-color: var(--svg-color--8a7794, #8A7794);
  stop-opacity: 0;
}

.qf4ahy-vb {
  d: path("m6.547 22.336l2.094-.058l.996.824l-.796 1.8l-3.499-1.576c-.173-.078-.277-.274-.182-.44c.243-.42.749-.55 1.387-.55");
}

.qsd3axbbu {
  fill: var(--svg-color--553750, #553750);
  d: path("m9.247 24.086l1.922-6.5l1.032 1.75z");
}

.qx2qyypot {
  stop-color: var(--svg-color--2b1e2d, #2B1E2D);
}

.r04agib6p {
  stop-color: var(--svg-color--3f2245, #3F2245);
}

.r1m1gebgj {
  stop-color: var(--svg-color--53b5f3, #53B5F3);
  stop-opacity: 0;
}

.rdox36bsx {
  d: path("m13.632 5.934l-.01-.064c-.033-.165-.13-.284-.215-.266c-.086.017-.129.165-.095.329l.016.063z");
}

.rg3z6xbem {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
  stop-opacity: 0;
}

.rgr8nhbdi {
  stop-color: var(--svg-color--654970, #654970);
  stop-opacity: 0;
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rihq7ul5p {
  stop-color: var(--svg-color--5d95c4, #5D95C4);
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

.rymgambwn {
  stop-color: var(--svg-color--4baafc, #4BAAFC);
  stop-opacity: 0;
}

.s_nhb9bnh {
  stop-color: var(--svg-color--4e4b80, #4E4B80);
  stop-opacity: 0;
}

.sa2yvrtdg {
  stop-color: var(--svg-color--918697, #918697);
}

.skauz3b-z {
  cx: 20.783px;
  cy: 23.621px;
  r: 5.559px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.sqtinbbgr {
  stop-color: var(--svg-color--cd3945, #CD3945);
  stop-opacity: 0;
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

.t9-j-pbql {
  stop-color: var(--svg-color--2f1f36, #2F1F36);
  stop-opacity: 0;
}

.tis1nnbrp {
  stop-color: var(--svg-color--2f1f36, #2F1F36);
}

.tkokf6bzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m6.185 24.196l3.031 1.421");
}

.tlllib2dn {
  stop-color: var(--svg-color--a198a7, #A198A7);
}

.ttw3dlkrn {
  d: path("m13.805 5.899l-.001-.004c-.058-.283-.226-.488-.376-.458s-.224.285-.167.569l.001.003z");
}

.u245iqdps {
  stop-color: var(--svg-color--938c9b, #938C9B);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uqxwa8ern {
  stop-color: var(--svg-color--3c2053, #3C2053);
}

.us60yytqw {
  stop-color: var(--svg-color--3b223c, #3B223C);
  stop-opacity: 0;
}

.v06h3pbnx {
  stop-color: var(--svg-color--3f2c51, #3F2C51);
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vgltnv9qo {
  stop-color: var(--svg-color--51b6ff, #51B6FF);
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

.wga3dymuf {
  stop-color: var(--svg-color--4b9cd5, #4B9CD5);
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

.xrnpsubav {
  stop-color: var(--svg-color--a198a7, #A198A7);
  stop-opacity: 0;
}

.xtpbi7bij {
  width: 7.832px;
  height: 1.372px;
  x: 8.206px;
  y: 26.16px;
  rx: 0.686px;
}

.xudiynxns {
  stop-color: var(--svg-color--5f5168, #5F5168);
}

.xw1yd7b4m {
  width: 4.227px;
  height: 1.211px;
  x: 20.669px;
  y: 11.141px;
  rx: 0.605px;
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
}

.y1et6wboe {
  d: path("m14.77 7.482l1.75-.896l.753 2.258l-1.77.647z");
}

.y3ij90b8v {
  stop-color: var(--svg-color--8a7794, #8A7794);
}

.yffybzb-u {
  d: path("M11.91 15.281h7.055v3.157h-6.843L9.715 23.61l-1.078-1.33c.157-.796.594-3.054.961-4.835c.375-1.82 1.594-2.165 2.313-2.165");
}

.yhxa1th6k {
  fill: var(--svg-color--513a3c, #513A3C);
  fill-rule: evenodd;
  d: path("M13.788 5.128c-.143-.064-.328-.032-.451-.007a.2.2 0 0 1-.08-.392l.01-.002c.113-.023.415-.085.685.036a.2.2 0 1 1-.164.365");
}

.ym5c6ha3r {
  stop-color: var(--svg-color--980a27, #980A27);
  stop-opacity: 0;
}

.yp_2y0bkd {
  stop-color: var(--svg-color--d53155, #D53155);
}

.yqc1nab6c {
  width: 1.242px;
  height: 6.695px;
  x: 11.107px;
  y: 22.344px;
  fill: var(--svg-color--776a86, #776A86);
  rx: 0.621px;
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

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z-rtjcc0y {
  stop-color: var(--svg-color--31223f, #31223F);
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

.zuaxx5qad {
  stop-color: var(--svg-color--7f758d, #7F758D);
  stop-opacity: 0;
}

.zzc1m6bsl {
  stop-color: var(--svg-color--4b3d47, #4B3D47);
  stop-opacity: 0;
}

</style>
