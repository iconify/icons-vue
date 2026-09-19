<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8MH5Jc)"><path class="d35-bks4u"/><path fill="url(#iv28HOd)" class="ssq6llb_r"/><path fill="url(#iByAyct)" class="ssq6llb_r"/><path fill="url(#icHU0Kb)" class="ssq6llb_r"/></g><g filter="url(#iYYIDKd)"><path fill="url(#iLOVNoe)" class="imupl_jnw"/><path fill="url(#i0zN0Ne)" class="imupl_jnw"/><path fill="url(#iiYrVxc)" class="imupl_jnw"/><path fill="url(#iaHvncd)" class="imupl_jnw"/><path fill="url(#iVFbbDe)" class="imupl_jnw"/></g><g filter="url(#iWM6L1P)"><path class="oq5jeihkk"/></g><circle fill="url(#iXMqNwc)" transform="matrix(-1 0 0 1 21.995 26.669)" class="fxt2czijw"/><circle fill="url(#iQwKHob)" transform="matrix(-1 0 0 1 21.995 26.669)" class="fxt2czijw"/><g filter="url(#iYLyjde)"><circle fill="url(#ioLCjBe)" transform="matrix(-1 0 0 1 21.823 26.84)" class="ydp5je9ep"/><circle fill="url(#imBPRuo)" transform="matrix(-1 0 0 1 21.823 26.84)" class="ydp5je9ep"/></g><rect transform="matrix(-1 0 0 1 20.893 22.336)" class="s4mm7wj7e"/><rect fill="url(#iEWySdO)" transform="matrix(-1 0 0 1 20.893 22.336)" class="vczf7ubhl"/><rect fill="url(#if1MlHd)" transform="matrix(-1 0 0 1 20.893 22.336)" class="vczf7ubhl"/><rect fill="url(#i7UH9Yb)" transform="matrix(-1 0 0 1 20.893 22.336)" class="vczf7ubhl"/><rect fill="url(#i7VVBrk)" transform="matrix(-1 0 0 1 20.893 22.336)" class="vczf7ubhl"/><rect fill="url(#iaSVYwi)" transform="matrix(-1 0 0 1 20.893 22.336)" class="vczf7ubhl"/><rect fill="url(#iSFHx9b)" transform="matrix(-1 0 0 1 20.893 22.336)" class="vczf7ubhl"/><rect fill="url(#iYNEAZz)" transform="scale(-1 1)rotate(-65.334 8.497 31.631)" class="j7vr7jxtp"/><rect fill="url(#i2GmAFd)" transform="scale(-1 1)rotate(-65.334 8.497 31.631)" class="j7vr7jxtp"/><path fill="url(#ixQFjee)" class="z_j7u9hhh"/><path fill="url(#iMgV9AN)" class="z_j7u9hhh"/><path fill="url(#iAsE2DN)" class="z_j7u9hhh"/><path fill="url(#iTLuOce)" class="z_j7u9hhh"/><path fill="url(#i2JpYge)" class="z_j7u9hhh"/><path fill="url(#i42l0vl)" class="z_j7u9hhh"/><g filter="url(#iLtyage)"><path fill="url(#idiVlyd)" clip-rule="evenodd" class="vn4ve8bnv"/><path fill="url(#it303yb)" clip-rule="evenodd" class="vn4ve8bnv"/></g><path fill="url(#iFpE7Td)" class="apnh-v-ri"/><path fill="url(#iJ28Fqc)" class="apnh-v-ri"/><path fill="url(#igpk4Db)" transform="scale(-1 1)rotate(16.465 -45.922 -33.096)" class="fbej3eerw"/><g filter="url(#i3jmZMd)"><rect transform="scale(-1 1)rotate(24.427 -67.334 -49.158)" class="mkf18fb1r"/></g><rect fill="url(#i6RqGqc)" transform="scale(-1 1)rotate(24.427 -67.334 -49.158)" class="kbsq_bcao"/><g filter="url(#iDsa9oc)"><path fill="url(#i4YHP4b)" clip-rule="evenodd" class="tymdmybae"/><path fill="url(#iKM5XOe)" clip-rule="evenodd" class="tymdmybae"/><path fill="url(#idka8lc)" clip-rule="evenodd" class="tymdmybae"/></g><path fill="url(#ipeRtLe)" clip-rule="evenodd" class="evsnckgmx"/><path fill="url(#ie4uhub)" clip-rule="evenodd" class="evsnckgmx"/><path fill="url(#i9cVCod)" clip-rule="evenodd" class="evsnckgmx"/><rect fill="url(#i5Zn9Cb)" transform="matrix(-1 0 0 1 11.33 11.133)" class="szzuw3bbf"/><rect fill="url(#iAXanqd)" transform="matrix(-1 0 0 1 11.33 11.133)" class="szzuw3bbf"/><g filter="url(#ivfwI4p)"><circle fill="url(#idPuoOc)" transform="matrix(-1 0 0 1 15.37 19.788)" class="gbejtwrll"/></g><g filter="url(#iCx5VJc)"><path clip-rule="evenodd" class="odqigybjo"/></g><path class="i2a03vbib"/><path fill="url(#iWbMWIb)" class="h4tqn0daj"/><path fill="url(#iXbdVWc)" class="h4tqn0daj"/><path fill="url(#iTICTAd)" class="h4tqn0daj"/><g filter="url(#ietRxPc)"><circle fill="url(#ix9EIYc)" transform="matrix(-1 0 0 1 12.448 22.71)" class="ynhlcccje"/></g><g filter="url(#iFCdsUc)"><circle stroke="url(#i8Lpy6d)" transform="matrix(-1 0 0 1 12.284 22.873)" class="v5no8zo2o"/></g><g filter="url(#iEEQ2Ed)"><circle stroke="url(#irdQ4jd)" transform="matrix(-1 0 0 1 15.653 19.237)" class="s6599442t"/></g><g filter="url(#iPrCTvd)"><circle stroke="url(#ieAH43d)" transform="matrix(-1 0 0 1 16.776 18.055)" class="ju5i36bgg"/></g><circle fill="url(#iDbaHXo)" transform="matrix(-1 0 0 1 14.636 17.254)" class="jptbwygwk"/><path class="kbaybjgmq"/><g filter="url(#iObMocc)"><path class="xh4f0ibsp"/></g><path fill="url(#ii7gOCd)" class="pf_krbj1g"/><g filter="url(#i7CHoUc)"><path fill="url(#i9M7Spe)" class="hxxynrvzg"/><path fill="url(#i5XW3Ld)" class="hxxynrvzg"/></g><g filter="url(#i4WVpwd)"><path class="d9l1hrbwo"/><path fill="url(#iSSBPpc)" class="ef__yg7wa"/><path fill="url(#iEp5APd)" class="ef__yg7wa"/><path fill="url(#iVlofjb)" class="ef__yg7wa"/><path fill="url(#iSMPPpb)" class="ef__yg7wa"/><path fill="url(#inTCXHK)" class="ef__yg7wa"/></g><path fill="url(#iQ4E1qb)" class="a5yv3uhzl"/><path clip-rule="evenodd" class="c6vj96b3r"/><path class="y-6i0-hmq"/><path fill="url(#iEIXn3d)" class="zasjgmbkf"/><path fill="url(#irZBPjf)" class="zasjgmbkf"/><path fill="url(#iLKjmlc)" class="zasjgmbkf"/><path fill="url(#i3Htwvb)" class="zasjgmbkf"/><g filter="url(#iZKYYSc)"><path clip-rule="evenodd" class="yzbswy0zw"/></g><path class="ogqx8dbts"/><path fill="url(#isBLd9d)" class="zaxhubwsx"/><path fill="url(#iI2EyQd)" class="pnxrglkvu"/><ellipse fill="url(#iicaIud)" transform="scale(-1 1)rotate(13.128 -33.945 -78.014)" class="iap3byr6y"/><g filter="url(#iMlVvkb)"><path class="zii5n2wvz"/></g><g filter="url(#i93dNMG)"><path stroke="url(#ii2TBse)" class="ry51-lb9x"/></g><g filter="url(#itfuwQS)"><path stroke="url(#iFkG9Nz)" class="ni21_wbqe"/></g><defs><radialGradient id="icHU0Kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7395 -.04827 .083 -1.2714 26.876 22.915)" gradientUnits="userSpaceOnUse"><stop class="bfwbq1bpl"/><stop offset="1" class="ktc-s82to"/></radialGradient><radialGradient id="i0zN0Ne" cx="0" cy="0" r="1" gradientTransform="rotate(70.681 -3.96 25.097)scale(5.76196 2.25923)" gradientUnits="userSpaceOnUse"><stop class="y3ij90b8v"/><stop offset="1" class="qb3gn8bfr"/></radialGradient><radialGradient id="iiYrVxc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5 0 0 -12.1563 21.002 17.032)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="do4f5ac_y"/><stop offset=".988" class="t_y0a1m1b"/></radialGradient><radialGradient id="iaHvncd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.46875 5.125 0 15.94 18)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="yu7wmpb_a"/><stop offset="1" class="zzc1m6bsl"/></radialGradient><radialGradient id="iQwKHob" cx="0" cy="0" r="1" gradientTransform="matrix(1.48438 0 0 3.64062 -.695 1.723)" gradientUnits="userSpaceOnUse"><stop class="answrebhr"/><stop offset="1" class="fzo002mry"/></radialGradient><radialGradient id="ioLCjBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.80266 4.80004 0 1.55 2.803)" gradientUnits="userSpaceOnUse"><stop class="ja_znnx3a"/><stop offset="1" class="ildpa548e"/></radialGradient><radialGradient id="imBPRuo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71875 1.03125 0 1.352 1.254)" gradientUnits="userSpaceOnUse"><stop class="z-rtjcc0y"/><stop offset="1" class="vxrkdvuju"/></radialGradient><radialGradient id="if1MlHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.11265 -.46567 0 1.242 1.844)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="i7UH9Yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9265 -.24601 0 0 1.03)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="i7VVBrk" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.69196 .27569 0 0 6.205)" gradientUnits="userSpaceOnUse"><stop class="q6suc5ubz"/><stop offset="1" class="erfrsrblk"/></radialGradient><radialGradient id="iaSVYwi" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.94902 .80452 0 .621 6.695)" gradientUnits="userSpaceOnUse"><stop class="ku1djbbcg"/><stop offset="1" class="e3f4ywbbl"/></radialGradient><radialGradient id="iSFHx9b" cx="0" cy="0" r="1" gradientTransform="rotate(38.089 -2.087 2.063)scale(1.46908 .76568)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n3h2abc_m"/><stop offset="1" class="rgr8nhbdi"/></radialGradient><radialGradient id="iYNEAZz" cx="0" cy="0" r="1" gradientTransform="matrix(-5.01535 -.13834 .02815 -1.0205 5.7 .78)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="rs99u8bqf"/><stop offset="1" class="lvn5-ac9d"/></radialGradient><radialGradient id="i2JpYge" cx="0" cy="0" r="1" gradientTransform="matrix(2.07812 -.42187 .6015 2.96294 14.409 18.97)" gradientUnits="userSpaceOnUse"><stop class="tis1nnbrp"/><stop offset="1" class="t9-j-pbql"/></radialGradient><radialGradient id="i42l0vl" cx="0" cy="0" r="1" gradientTransform="matrix(.82813 0 0 2.43007 19.19 18.188)" gradientUnits="userSpaceOnUse"><stop class="r04agib6p"/><stop offset="1" class="mz7wlj55e"/></radialGradient><radialGradient id="igpk4Db" cx="0" cy="0" r="1" gradientTransform="matrix(.06825 -4.12415 .84696 .01402 .527 3.948)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="w-8ci9bkh"/><stop offset="1" class="dr65abcro"/></radialGradient><radialGradient id="i6RqGqc" cx="0" cy="0" r="1" gradientTransform="matrix(.59496 -.39035 .70458 1.0739 .095 1.168)" gradientUnits="userSpaceOnUse"><stop class="vp5ble8bb"/><stop offset="1" class="g4u-v_bhx"/></radialGradient><radialGradient id="ie4uhub" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.268 17.579)scale(5.3418)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="lfwvarbqo"/><stop offset="1" class="z4for55kd"/></radialGradient><radialGradient id="i9cVCod" cx="0" cy="0" r="1" gradientTransform="matrix(9.24998 -8.46874 6.57579 7.1824 7.034 28.438)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="jz-3fab0l"/><stop offset="1" class="fiiks7b8f"/></radialGradient><radialGradient id="iAXanqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 .39452 -.43395 -.94526 4.36 .211)" gradientUnits="userSpaceOnUse"><stop class="roww1df0l"/><stop offset="1" class="ennuonbfb"/></radialGradient><radialGradient id="idPuoOc" cx="0" cy="0" r="1" gradientTransform="matrix(4.09375 -5.53125 9.86398 7.30045 2.21 6.838)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="z3yur8boj"/><stop offset="1" class="c9gtc1bjl"/></radialGradient><radialGradient id="iWbMWIb" cx="0" cy="0" r="1" gradientTransform="rotate(110.816 2.657 11.093)scale(5.09592 1.94315)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="dqwirq1wj"/><stop offset="1" class="o50-1mg1f"/></radialGradient><radialGradient id="iTICTAd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60922 1.60922 -4.29661 4.29661 12.715 8.657)" gradientUnits="userSpaceOnUse"><stop class="o-ce7bc5n"/><stop offset="1" class="skmvm0bcw"/></radialGradient><radialGradient id="iDbaHXo" cx="0" cy="0" r="1" gradientTransform="rotate(-73.593 .548 .247)scale(.73297)" gradientUnits="userSpaceOnUse"><stop class="eu_66ccav"/><stop offset="1" class="bvaidyi1c"/></radialGradient><radialGradient id="ii7gOCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.62956 .75788 -.9652 -.80178 19.643 6.275)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="i5XW3Ld" cx="0" cy="0" r="1" gradientTransform="matrix(.7584 .11066 -.13492 .92465 16.33 5.544)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iSSBPpc" cx="0" cy="0" r="1" gradientTransform="rotate(-123.021 9.648 -.878)scale(2.46887 3.60799)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="iEp5APd" cx="0" cy="0" r="1" gradientTransform="matrix(1.72795 1.17524 -1.64988 2.4258 15.051 3.224)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iVlofjb" cx="0" cy="0" r="1" gradientTransform="matrix(.76448 -.06163 .02866 .35549 14.515 6.08)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="iSMPPpb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53786 .61605 -.28444 .71005 16.748 2.31)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="inTCXHK" cx="0" cy="0" r="1" gradientTransform="rotate(148.3 9.285 4.127)scale(.63162 .9122)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="iQ4E1qb" cx="0" cy="0" r="1" gradientTransform="matrix(.23266 .91804 -1.49177 .37806 16.174 5.346)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iLKjmlc" cx="0" cy="0" r="1" gradientTransform="matrix(2.0156 -2.96876 2.35369 1.598 13.565 11.75)" gradientUnits="userSpaceOnUse"><stop offset=".88" class="cod3s5bmi"/><stop offset="1" class="qu8oblblu"/></radialGradient><radialGradient id="isBLd9d" cx="0" cy="0" r="1" gradientTransform="rotate(-168.519 9.511 2.093)scale(.24857 .48294)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iI2EyQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2223 -.04515 .09772 -.48107 18.562 6.086)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iFkG9Nz" cx="0" cy="0" r="1" gradientTransform="matrix(4.23438 6.76562 -1.43419 .89761 11.674 13.329)" gradientUnits="userSpaceOnUse"><stop offset=".471" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><linearGradient id="iv28HOd" x1="22.886" x2="23.803" y1="24.347" y2="23.864" gradientUnits="userSpaceOnUse"><stop offset=".209" class="id-v9-mic"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="iByAyct" x1="24.125" x2="23.835" y1="24.685" y2="23.928" gradientUnits="userSpaceOnUse"><stop offset=".122" class="oqr4-mbfk"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="iLOVNoe" x1="22.096" x2="15.94" y1="20.594" y2="17.219" gradientUnits="userSpaceOnUse"><stop class="sa2yvrtdg"/><stop offset="1" class="bxntujdns"/></linearGradient><linearGradient id="iVFbbDe" x1="22.94" x2="22.034" y1="19.844" y2="19.907" gradientUnits="userSpaceOnUse"><stop class="d_4otnung"/><stop offset="1" class="gldbv0pab"/></linearGradient><linearGradient id="iXMqNwc" x1="1.914" x2="1.914" y1="3.566" y2="0" gradientUnits="userSpaceOnUse"><stop class="uqxwa8ern"/><stop offset=".596" class="qx2qyypot"/></linearGradient><linearGradient id="iEWySdO" x1="1.242" x2=".505" y1="4.432" y2="4.432" gradientUnits="userSpaceOnUse"><stop class="g6i5vgbtc"/><stop offset="1" class="zuaxx5qad"/></linearGradient><linearGradient id="i2GmAFd" x1="3.696" x2="3.608" y1="1.581" y2=".828" gradientUnits="userSpaceOnUse"><stop class="pyh7r6bag"/><stop offset="1" class="ym5c6ha3r"/></linearGradient><linearGradient id="ixQFjee" x1="19.649" x2="14.741" y1="18.492" y2="18.492" gradientUnits="userSpaceOnUse"><stop class="n0w_cmcuq"/><stop offset="1" class="cjqgdpbwq"/></linearGradient><linearGradient id="iMgV9AN" x1="16.252" x2="16.252" y1="17.422" y2="17.766" gradientUnits="userSpaceOnUse"><stop class="xb91u7b-b"/><stop offset="1" class="us60yytqw"/></linearGradient><linearGradient id="iAsE2DN" x1="17.174" x2="17.174" y1="19.266" y2="18.219" gradientUnits="userSpaceOnUse"><stop class="x8v8a_bhe"/><stop offset="1" class="g0aomjwhv"/></linearGradient><linearGradient id="iTLuOce" x1="20.893" x2="20.659" y1="19.032" y2="19.032" gradientUnits="userSpaceOnUse"><stop class="xudiynxns"/><stop offset="1" class="h_vbtipyr"/></linearGradient><linearGradient id="idiVlyd" x1="16.979" x2="16.979" y1="18.985" y2="26.516" gradientUnits="userSpaceOnUse"><stop class="yp_2y0bkd"/><stop offset="1" class="jli-mvbgu"/></linearGradient><linearGradient id="it303yb" x1="20.893" x2="20.471" y1="21.28" y2="21.28" gradientUnits="userSpaceOnUse"><stop class="ig81yhx8p"/><stop offset="1" class="sqtinbbgr"/></linearGradient><linearGradient id="iFpE7Td" x1="15.416" x2="16.877" y1="7.977" y2="8.532" gradientUnits="userSpaceOnUse"><stop class="u47sg1bfj"/><stop offset="1" class="z1rceg10z"/></linearGradient><linearGradient id="iJ28Fqc" x1="15.221" x2="15.456" y1="6.704" y2="7.563" gradientUnits="userSpaceOnUse"><stop class="npqwxtb7g"/><stop offset="1" class="h8btxy_ix"/></linearGradient><linearGradient id="i4YHP4b" x1="18.643" x2="12.909" y1="19.25" y2="16" gradientUnits="userSpaceOnUse"><stop class="x3lzt0c-k"/><stop offset="1" class="cwu_shb3d"/></linearGradient><linearGradient id="iKM5XOe" x1="10.83" x2="11.853" y1="17.378" y2="17.378" gradientUnits="userSpaceOnUse"><stop class="ys8863_0j"/><stop offset="1" class="h0a-qhb0e"/></linearGradient><linearGradient id="idka8lc" x1="15.262" x2="15.262" y1="15.918" y2="16.251" gradientUnits="userSpaceOnUse"><stop class="io62jp_6h"/><stop offset="1" class="rg3z6xbem"/></linearGradient><linearGradient id="ipeRtLe" x1="7.471" x2="15.565" y1="19.469" y2="28.532" gradientUnits="userSpaceOnUse"><stop class="v06h3pbnx"/><stop offset="1" class="lucd7-9cq"/></linearGradient><linearGradient id="i5Zn9Cb" x1=".344" x2="4.227" y1=".742" y2=".742" gradientUnits="userSpaceOnUse"><stop class="o2t29rbsm"/><stop offset="1" class="laa0aab1b"/></linearGradient><linearGradient id="iXbdVWc" x1="16.224" x2="16.224" y1="15.43" y2="11.393" gradientUnits="userSpaceOnUse"><stop class="kqmyk7boa"/><stop offset="1" class="bspgbrb6c"/></linearGradient><linearGradient id="ix9EIYc" x1="1.945" x2=".461" y1=".275" y2="2.273" gradientUnits="userSpaceOnUse"><stop class="zax-lz03d"/><stop offset="1" class="zg7ndleiu"/></linearGradient><linearGradient id="i8Lpy6d" x1="1.945" x2=".563" y1="-.053" y2="1.674" gradientUnits="userSpaceOnUse"><stop offset=".139" class="szqa4cczu"/><stop offset=".488" class="i2tkr35ot"/></linearGradient><linearGradient id="irdQ4jd" x1="7.947" x2="1.822" y1="1.045" y2="8.686" gradientUnits="userSpaceOnUse"><stop offset=".066" class="u245iqdps"/><stop offset=".257" class="rijqbwbix"/><stop offset=".803" class="rijqbwbix"/><stop offset=".945" class="br5egpbia"/></linearGradient><linearGradient id="ieAH43d" x1="9.274" x2="1.899" y1="1.152" y2="10.466" gradientUnits="userSpaceOnUse"><stop class="bgt2mc6fp"/><stop offset=".294" class="j5rtt4bpo"/><stop offset=".801" class="x4ldqjsok"/></linearGradient><linearGradient id="i9M7Spe" x1="16.473" x2="18.986" y1="6.26" y2="6.93" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="iEIXn3d" x1="15.409" x2="14.862" y1="11.317" y2="10.922" gradientUnits="userSpaceOnUse"><stop class="bjn-s4bel"/><stop offset="1" class="aprlu01bv"/></linearGradient><linearGradient id="irZBPjf" x1="13.118" x2="14.389" y1="10.186" y2="11.2" gradientUnits="userSpaceOnUse"><stop class="hcyruib3x"/><stop offset="1" class="ba065yvkm"/></linearGradient><linearGradient id="i3Htwvb" x1="13.518" x2="14.049" y1="12.297" y2="11.579" gradientUnits="userSpaceOnUse"><stop class="zn5fmlbvx"/><stop offset="1" class="t9-akpk6y"/></linearGradient><linearGradient id="iicaIud" x1="-.006" x2=".164" y1=".045" y2=".101" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ii2TBse" x1="22.784" x2="27.831" y1="25.61" y2="23.375" gradientUnits="userSpaceOnUse"><stop class="tlllib2dn"/><stop offset="1" class="xrnpsubav"/></linearGradient><filter id="i8MH5Jc" width="4.713" height="2.925" x="22.363" y="22.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="iYYIDKd" width="10.328" height="8.578" x="13.034" y="15.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.431373 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="iWM6L1P" width="3.953" height="7.5" x="19.299" y="17.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7090" stdDeviation=".25"/></filter><filter id="iYLyjde" width="3.602" height="3.602" x="18.471" y="26.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7090" stdDeviation=".125"/></filter><filter id="iLtyage" width="7.828" height="7.731" x="13.065" y="18.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.0745098 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="i3jmZMd" width="4.543" height="3.256" x="22.178" y="23.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.360784 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="iDsa9oc" width="8.506" height="4.313" x="11.084" y="15.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.270588 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="ivfwI4p" width="8.267" height="8.267" x="7.102" y="19.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.611765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="iCx5VJc" width="9.68" height="9.83" x="6.471" y="18.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.4 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="ietRxPc" width="3.273" height="3.273" x="9.574" y="22.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.678431 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_2_7090"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_2_7090" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.207843 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_2_7090"/></filter><filter id="iFCdsUc" width="2.245" height="2.245" x="10.188" y="22.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7090" stdDeviation=".05"/></filter><filter id="iEEQ2Ed" width="9.401" height="9.401" x="6.476" y="19.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7090" stdDeviation=".075"/></filter><filter id="iPrCTvd" width="12.217" height="12.217" x="5.109" y="17.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7090" stdDeviation=".15"/></filter><filter id="iObMocc" width="3.238" height="8.483" x="11.304" y="10.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.545098 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="i7CHoUc" width="4.32" height="5.224" x="14.97" y="3.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.52549 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="i4WVpwd" width="5.336" height="4.75" x="14.317" y="2.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="iZKYYSc" width=".946" height=".439" x="17.818" y="4.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7090"/></filter><filter id="iMlVvkb" width="4.025" height="1.2" x="7.084" y="11.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7090" stdDeviation=".225"/></filter><filter id="i93dNMG" width="4.231" height="2.622" x="22.184" y="23.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7090" stdDeviation=".2"/></filter><filter id="itfuwQS" width="2.78" height="8.181" x="11.329" y="11.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7090" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-manual-wheelchair-facing-right" /></template>
<style>
.a5yv3uhzl {
  d: path("M16.528 6.289c.045.009.084-.026.087-.071l.071-1.132c.004-.055-.04-.104-.095-.098a.659.659 0 0 0-.063 1.3");
}

.a9m8t591o {
  stop-color: var(--svg-color--5f3b5c, #5F3B5C);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.answrebhr {
  stop-color: var(--svg-color--79747b, #79747B);
}

.apnh-v-ri {
  d: path("m17.23 7.475l-1.75-.896l-.753 2.258l1.77.646z");
}

.aprlu01bv {
  stop-color: var(--svg-color--e46821, #E46821);
  stop-opacity: 0;
}

.ba065yvkm {
  stop-color: var(--svg-color--ff973e, #FF973E);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bfwbq1bpl {
  stop-color: var(--svg-color--615f82, #615F82);
}

.bgt2mc6fp {
  stop-color: var(--svg-color--4e4558, #4E4558);
}

.bjn-s4bel {
  stop-color: var(--svg-color--e46821, #E46821);
}

.br5egpbia {
  stop-color: var(--svg-color--96909f, #96909F);
}

.bspgbrb6c {
  stop-color: var(--svg-color--da5b25, #DA5B25);
  stop-opacity: 0;
}

.bvaidyi1c {
  stop-color: var(--svg-color--d99215, #D99215);
}

.bxntujdns {
  stop-color: var(--svg-color--8c8181, #8C8181);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c6vj96b3r {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M17.796 6.961a.113.113 0 0 0-.03.158c.169.25.464.366.56.395a.113.113 0 0 0 .067-.216c-.082-.025-.315-.121-.44-.306a.113.113 0 0 0-.157-.03");
}

.c9gtc1bjl {
  stop-color: var(--svg-color--c2b1db, #C2B1DB);
}

.cjqgdpbwq {
  stop-color: var(--svg-color--4d3659, #4D3659);
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

.d35-bks4u {
  fill: var(--svg-color--4d4a7f, #4D4A7F);
  d: path("m25.453 22.329l-2.094-.059l-.996.824l.796 1.801l3.499-1.576c.173-.079.277-.275.181-.44c-.242-.42-.748-.55-1.386-.55");
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.d9l1hrbwo {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M19.622 3.399c-.124-.476-.6-.68-.849-.717c-.772-.114-.93.13-1.592-.153c-.7-.3-1.069-.33-1.41-.25h-.007c-.336.078-1.032.238-1.297 1.542c-.244 1.201.056 1.923.217 2.191l-.044.007c-.22.032-.35.234-.318.455c.028.189.23.335.519.348c.33.014.574.018.766.02c.107 0 .2-.076.221-.182l.201-.989a.9.9 0 0 1 .574-.653c.101-.428.273-.6.51-.66c.391-.1.485.008 1.347.13c.914.128 1.315-.494 1.162-1.09");
}

.do4f5ac_y {
  stop-color: var(--svg-color--765852, #765852);
  stop-opacity: 0;
}

.dqwirq1wj {
  stop-color: var(--svg-color--df5322, #DF5322);
}

.dr65abcro {
  stop-color: var(--svg-color--b61f30, #B61F30);
}

.e3f4ywbbl {
  stop-color: var(--svg-color--64487f, #64487F);
  stop-opacity: 0;
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.ef__yg7wa {
  d: path("M19.622 3.399c-.124-.476-.6-.68-.849-.717c-.772-.114-.93.13-1.592-.153c-.7-.3-1.069-.33-1.41-.25h-.007c-.336.078-1.032.238-1.297 1.542c-.244 1.201.056 1.923.217 2.191l-.044.007c-.22.032-.35.234-.318.455c.028.189.23.335.519.348c.33.014.574.018.766.02c.107 0 .2-.076.221-.182l.201-.989a.9.9 0 0 1 .574-.653c.101-.428.273-.6.51-.66c.391-.1.485.008 1.347.13c.914.128 1.315-.494 1.162-1.09");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.ennuonbfb {
  stop-color: var(--svg-color--675a75, #675A75);
  stop-opacity: 0;
}

.erfrsrblk {
  stop-color: var(--svg-color--7a727f, #7A727F);
  stop-opacity: 0;
}

.eu_66ccav {
  stop-color: var(--svg-color--e3a330, #E3A330);
}

.evsnckgmx {
  fill-rule: evenodd;
  d: path("M11.311 30.114a6.268 6.268 0 1 1 0-12.535a6.268 6.268 0 0 1 0 12.535m0-1.428a4.84 4.84 0 1 1 0-9.68a4.84 4.84 0 0 1 0 9.68");
}

.fbej3eerw {
  d: path("M0 0h1.162v5.449H0z");
}

.fiiks7b8f {
  stop-color: var(--svg-color--301d2f, #301D2F);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.fxt2czijw {
  cx: 1.723px;
  cy: 1.723px;
  r: 1.723px;
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

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.gbejtwrll {
  cx: 4.059px;
  cy: 4.059px;
  r: 4.059px;
}

.gldbv0pab {
  stop-color: var(--svg-color--948f93, #948F93);
  stop-opacity: 0;
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

.h4tqn0daj {
  d: path("M16.618 15.278c.31-1.037.936-3.994.588-5.738c-.437-1.446-1.742-1.461-2.374-1.391c-.774.086-1.602.477-2.04 1.836c-.453 1.25-.58 4.08-.632 5.445h.874v-.152z");
}

.h8btxy_ix {
  stop-color: var(--svg-color--dfa236, #DFA236);
  stop-opacity: 0;
}

.hcyruib3x {
  stop-color: var(--svg-color--ff973e, #FF973E);
}

.hxxynrvzg {
  d: path("M19.253 5.492c.11-.72-.05-1.11-.139-1.232l-3.317-.674l-.627 2.801c.387 2.042 2.722 2.6 3.211 1.99c.49-.611.744-2.053.872-2.885");
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.i2a03vbib {
  fill: var(--svg-color--eb7f39, #EB7F39);
  d: path("M16.618 15.278c.31-1.037.936-3.994.588-5.738c-.437-1.446-1.742-1.461-2.374-1.391c-.774.086-1.602.477-2.04 1.836c-.453 1.25-.58 4.08-.632 5.445h.874v-.152z");
}

.i2tkr35ot {
  stop-color: var(--svg-color--524a5b, #524A5B);
  stop-opacity: 0;
}

.iap3byr6y {
  cx: 0.059px;
  cy: 0.08px;
  rx: 0.059px;
  ry: 0.08px;
}

.id-v9-mic {
  stop-color: var(--svg-color--342252, #342252);
}

.ig81yhx8p {
  stop-color: var(--svg-color--cd3945, #CD3945);
}

.ildpa548e {
  stop-color: var(--svg-color--3b3145, #3B3145);
}

.imupl_jnw {
  d: path("M20.09 15.274h-7.056v3.156h6.844l2.406 5.172l1.079-1.328c-.157-.797-.594-3.055-.961-4.836c-.376-1.82-1.594-2.164-2.313-2.164");
}

.io62jp_6h {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
}

.j5rtt4bpo {
  stop-color: var(--svg-color--4e4558, #4E4558);
  stop-opacity: 0;
}

.j7vr7jxtp {
  width: 7.832px;
  height: 1.372px;
  rx: 0.686px;
}

.ja_znnx3a {
  stop-color: var(--svg-color--423650, #423650);
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.jli-mvbgu {
  stop-color: var(--svg-color--ca283c, #CA283C);
}

.jptbwygwk {
  cx: 0.494px;
  cy: 0.494px;
  r: 0.494px;
}

.ju5i36bgg {
  cx: 5.559px;
  cy: 5.559px;
  r: 5.559px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.jz-3fab0l {
  stop-color: var(--svg-color--301d2f, #301D2F);
  stop-opacity: 0;
}

.kbaybjgmq {
  fill: var(--svg-color--cb3c04, #CB3C04);
  d: path("M14.311 12.465c-.426-.109-1.248-.693-1.789-1.293c.414.045 1.345.378 1.789 1.293");
}

.kbsq_bcao {
  width: 4.847px;
  height: 1.452px;
  rx: 0.726px;
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
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

.laa0aab1b {
  stop-color: var(--svg-color--46295f, #46295F);
}

.lfwvarbqo {
  stop-color: var(--svg-color--1b1423, #1B1423);
}

.lucd7-9cq {
  stop-color: var(--svg-color--3d2c4c, #3D2C4C);
}

.lvn5-ac9d {
  stop-color: var(--svg-color--c62f3a, #C62F3A);
}

.mkf18fb1r {
  width: 4.847px;
  height: 1.452px;
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

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ni21_wbqe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m13.034 11.844l-.84 1.273a.98.98 0 0 0-.146.732c.221 1.1.717 3.27 1.36 4.776");
}

.npqwxtb7g {
  stop-color: var(--svg-color--dfa236, #DFA236);
}

.o-ce7bc5n {
  stop-color: var(--svg-color--ff9a3a, #FF9A3A);
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o2t29rbsm {
  stop-color: var(--svg-color--37213e, #37213E);
}

.o50-1mg1f {
  stop-color: var(--svg-color--df5322, #DF5322);
  stop-opacity: 0;
}

.odqigybjo {
  fill: var(--svg-color--8a7e97, #8A7E97);
  fill-rule: evenodd;
  d: path("M11.311 28.686a4.84 4.84 0 1 1 0-9.68a4.84 4.84 0 0 1 0 9.68m0-.781a4.059 4.059 0 1 1 0-8.117a4.059 4.059 0 0 1 0 8.117");
}

.ogqx8dbts {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.66 6.106l-.879-.179c.07-.348.325-.59.567-.54c.243.049.382.37.311.719");
}

.oq5jeihkk {
  fill: var(--svg-color--553750, #553750);
  d: path("m22.752 24.079l-1.921-6.5l-1.032 1.75z");
}

.oqr4-mbfk {
  stop-color: var(--svg-color--332156, #332156);
}

.pf_krbj1g {
  d: path("M19.278 6.389a.9.9 0 0 1-.147-.453l-.16-.032l-.202 1c.166.16.443.196.56.03c.102-.142.09-.347-.051-.545");
}

.pnxrglkvu {
  d: path("m18.295 6.032l.01-.065c.033-.165.13-.284.216-.267c.087.018.13.166.096.33l-.017.064z");
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

.qu8oblblu {
  stop-color: var(--svg-color--eb8310, #EB8310);
}

.qx2qyypot {
  stop-color: var(--svg-color--2b1e2d, #2B1E2D);
}

.r04agib6p {
  stop-color: var(--svg-color--3f2245, #3F2245);
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
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

.ry51-lb9x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m25.815 24.188l-3.031 1.422");
}

.s_nhb9bnh {
  stop-color: var(--svg-color--4e4b80, #4E4B80);
  stop-opacity: 0;
}

.s4mm7wj7e {
  width: 1.242px;
  height: 6.695px;
  fill: var(--svg-color--776a86, #776A86);
  rx: 0.621px;
}

.s6599442t {
  cx: 4.476px;
  cy: 4.476px;
  r: 4.476px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.sa2yvrtdg {
  stop-color: var(--svg-color--918697, #918697);
}

.skmvm0bcw {
  stop-color: var(--svg-color--ff9a3a, #FF9A3A);
  stop-opacity: 0;
}

.sqtinbbgr {
  stop-color: var(--svg-color--cd3945, #CD3945);
  stop-opacity: 0;
}

.ssq6llb_r {
  d: path("m25.453 22.329l-2.094-.059l-.996.824l.796 1.801l3.499-1.576c.173-.079.277-.275.181-.44c-.242-.42-.748-.55-1.386-.55");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.szqa4cczu {
  stop-color: var(--svg-color--524a5b, #524A5B);
}

.szzuw3bbf {
  width: 4.227px;
  height: 1.211px;
  rx: 0.605px;
}

.t_y0a1m1b {
  stop-color: var(--svg-color--765852, #765852);
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
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

.tymdmybae {
  fill-rule: evenodd;
  d: path("M17.514 17.068c.428 0 .776.347.776.775v2.388h1a.15.15 0 0 0 .15-.15v-2.238a1.925 1.925 0 0 0-1.926-1.925h-6.18a.25.25 0 0 0-.25.25v2.749h1.15v-1.85z");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u245iqdps {
  stop-color: var(--svg-color--938c9b, #938C9B);
}

.u47sg1bfj {
  stop-color: var(--svg-color--ffc23b, #FFC23B);
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

.v5no8zo2o {
  cx: 0.973px;
  cy: 0.973px;
  r: 0.973px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vczf7ubhl {
  width: 1.242px;
  height: 6.695px;
  rx: 0.621px;
}

.vn4ve8bnv {
  fill-rule: evenodd;
  d: path("M20.893 19.782c0-.483-.337-.797-.82-.797h-7.008v7.531h4.726a.895.895 0 0 0 .864-.686c.082-.33.269-.658.562-.924c.28-.254.606-.406.928-.462a.896.896 0 0 0 .748-.877zm-1.5.453a.25.25 0 0 1 .25.25v2.488c0 .18-.12.335-.288.4a3.2 3.2 0 0 0-.977.607c-.328.296-.58.647-.752 1.022a.44.44 0 0 1-.39.264h-2.921v-5.031z");
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

.xh4f0ibsp {
  fill: var(--svg-color--ffbe30, #FFBE30);
  d: path("m13.345 13.43l1.025-1.344l-1.418-1.132c-.203.238-.703.941-1.144 1.523c-.452.595-.448 1.383-.352 1.734c.232 1.053.753 3.316.922 3.954c.211.796.461.945.938 1.054s1.285-.312 1.222-.93c-.027-.48-.386-.695-.644-1.484a59 59 0 0 1-.643-2.99a.5.5 0 0 1 .094-.385");
}

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xrnpsubav {
  stop-color: var(--svg-color--a198a7, #A198A7);
  stop-opacity: 0;
}

.xudiynxns {
  stop-color: var(--svg-color--5f5168, #5F5168);
}

.y-6i0-hmq {
  fill: var(--svg-color--f67624, #F67624);
  d: path("M15.811 10.356a1.11 1.11 0 1 0-1.813-1.283l-1.483 2.107c.871.48 1.793 1.29 1.793 1.29z");
}

.y3ij90b8v {
  stop-color: var(--svg-color--8a7794, #8A7794);
}

.ydp5je9ep {
  cx: 1.551px;
  cy: 1.551px;
  r: 1.551px;
}

.ym5c6ha3r {
  stop-color: var(--svg-color--980a27, #980A27);
  stop-opacity: 0;
}

.ynhlcccje {
  cx: 1.137px;
  cy: 1.137px;
  r: 1.137px;
}

.yp_2y0bkd {
  stop-color: var(--svg-color--d53155, #D53155);
}

.ys8863_0j {
  stop-color: var(--svg-color--e35373, #E35373);
}

.yu7wmpb_a {
  stop-color: var(--svg-color--4b3d47, #4B3D47);
}

.yzbswy0zw {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M18.39 5.095a.7.7 0 0 1 .195.026a.136.136 0 1 0 .087-.258a1 1 0 0 0-.281-.04a.9.9 0 0 0-.394.08a.136.136 0 1 0 .115.247a.7.7 0 0 1 .278-.055");
}

.z_j7u9hhh {
  d: path("M20.893 17.822a.4.4 0 0 0-.4-.4h-8.881v2.508h9.281z");
}

.z-rtjcc0y {
  stop-color: var(--svg-color--31223f, #31223F);
}

.z1rceg10z {
  stop-color: var(--svg-color--e08e2e, #E08E2E);
}

.z3yur8boj {
  stop-color: var(--svg-color--dccaee, #DCCAEE);
}

.z4for55kd {
  stop-color: var(--svg-color--1b1423, #1B1423);
  stop-opacity: 0;
}

.zasjgmbkf {
  d: path("M15.811 10.356a1.11 1.11 0 1 0-1.813-1.283l-1.483 2.107c.871.48 1.793 1.29 1.793 1.29z");
}

.zax-lz03d {
  stop-color: var(--svg-color--463a52, #463A52);
}

.zaxhubwsx {
  d: path("M18.12 5.998v-.004c.058-.285.227-.492.378-.461s.226.287.168.572v.004z");
}

.zg7ndleiu {
  stop-color: var(--svg-color--443850, #443850);
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zige1b1kr {
  stop-color: var(--svg-color--6e5c72, #6E5C72);
  stop-opacity: 0;
}

.zii5n2wvz {
  stroke: var(--svg-color--4c3e59, #4C3E59);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M10.659 11.659H7.534");
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
