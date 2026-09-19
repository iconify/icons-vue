<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNfQNHd)"><path class="pqpxg6gcd"/><path fill="url(#iUhI09c)" class="z-thopeux"/><path fill="url(#ihWU4vd)" class="z-thopeux"/></g><g filter="url(#idDmqYP)"><path class="j9cj5qbuy"/><path fill="url(#iz6GOIb)" class="z-thopeux"/><path fill="url(#iOivUbb)" class="z-thopeux"/></g><g filter="url(#iHDOhGe)"><path class="mcb3mdbmq"/><path fill="url(#ibuxX9V)" class="z-thopeux"/></g><g filter="url(#ikW0jie)"><path class="nihdl4b3y"/><path fill="url(#imc1MXd)" class="z-thopeux"/><path fill="url(#iROJcPd)" class="z-thopeux"/></g><g filter="url(#ihzmacc)"><path class="xq8p_qumq"/><path fill="url(#iyBw2jc)" class="z-thopeux"/><path fill="url(#i5Xkmze)" class="z-thopeux"/></g><g filter="url(#iH9euue)"><path class="j--tlacac"/><path fill="url(#iYZvCxd)" class="b4mo-29ij"/><path fill="url(#iJwxMPe)" class="b4mo-29ij"/></g><path class="ik39jqbsn"/><path fill="url(#iTsW5Nc)" class="z77zzmbkv"/><path fill="url(#iQcA7En)" class="z77zzmbkv"/><path fill="url(#iOfjqcd)" class="z77zzmbkv"/><path fill="url(#isgVVHd)" class="z77zzmbkv"/><path fill="url(#ibiEGBb)" class="z77zzmbkv"/><path class="uf8v-8bxn"/><path fill="url(#iP6UBmc)" class="wifu-cbwd"/><path fill="url(#ihNLNpd)" class="wifu-cbwd"/><path fill="url(#iER4OWb)" class="wifu-cbwd"/><path class="h68lkf1_a"/><path fill="url(#izBzNGe)" class="ps0fa7bxo"/><path fill="url(#ie411je)" class="ps0fa7bxo"/><path fill="url(#i8cymIQ)" class="ps0fa7bxo"/><path fill="url(#i8aYqre)" class="gr7x_rwbv"/><path fill="url(#iUn8IAz)" class="gr7x_rwbv"/><path fill="url(#iTXMv8b)" class="gr7x_rwbv"/><path fill="url(#ixwetQd)" class="gr7x_rwbv"/><path fill="url(#iLSaoWb)" class="gr7x_rwbv"/><path fill="url(#i5Lj3Yc)" class="gr7x_rwbv"/><path fill="url(#i82dLZi)" class="gr7x_rwbv"/><g filter="url(#iWtQnHe)"><path fill="url(#i2yDo0c)" class="a7a1m8boe"/></g><g filter="url(#iz4FDMb)"><path fill="url(#ivXyFxp)" class="jz8djgftu"/></g><g filter="url(#ioSe0ic)"><path fill="url(#iCWbHoe)" class="u3yytvbgg"/><path fill="url(#iuKX0Uc)" class="u3yytvbgg"/><path fill="url(#i6bZPzd)" class="u3yytvbgg"/><path fill="url(#icEs3vd)" class="u3yytvbgg"/><path fill="url(#iAGCnhe)" class="u3yytvbgg"/></g><path fill="url(#ibYEbXc)" class="xbdij97tt"/><path fill="url(#iSI1pQe)" class="xbdij97tt"/><path fill="url(#i12D23b)" class="xbdij97tt"/><path fill="url(#iAQmG5V)" class="xbdij97tt"/><g filter="url(#ifTScgb)"><path fill="url(#iaoILVy)" class="ci4cb1xgu"/></g><g filter="url(#iv3lXSb)"><path fill="url(#iXmaopd)" class="gq_evtgpi"/></g><g filter="url(#iU88QWV)"><path fill="url(#iakErhb)" class="peclnma7n"/></g><g filter="url(#is7opjd)"><path fill="url(#ibc7VAe)" class="zhwrqyb9y"/><path fill="url(#i00iwFA)" class="zhwrqyb9y"/></g><path fill="url(#i6GLopc)" class="da96dzbnj"/><path fill="url(#iGE0NUb)" class="da96dzbnj"/><g filter="url(#iicfauc)"><path class="bm_9q5x_x"/></g><g filter="url(#irnMHmd)"><path class="pnmhoebug"/></g><g filter="url(#i6d9lCc)"><path fill="url(#iyavIQe)" class="c27hakbuc"/><path fill="url(#iR90U6u)" class="c27hakbuc"/><path fill="url(#iqaJ9ye)" class="c27hakbuc"/><path fill="url(#ivTJxQb)" class="c27hakbuc"/><path fill="url(#in42Sgd)" class="c27hakbuc"/><path fill="url(#iMwngab)" class="c27hakbuc"/></g><path fill="url(#irzXOZg)" class="c27hakbuc"/><path fill="url(#is1RgNb)" class="c27hakbuc"/><path fill="url(#iobaHWd)" class="c27hakbuc"/><g filter="url(#iuoX1Rc)"><path class="e2tgz4b_p"/></g><g filter="url(#iZ5OctJ)"><path class="b6c6q1bjp"/><path fill="url(#ibFu8ad)" class="y59bi164p"/><path fill="url(#ii5x2od)" class="y59bi164p"/></g><g filter="url(#iiOHiVb)"><path stroke="url(#i0En4Ob)" class="u9wqsy2sp"/></g><path class="t34bfozye"/><path class="a6tzm1b6f"/><path fill="url(#iP8FdEd)" class="qeihuuzsw"/><path class="qttrphznb"/><g filter="url(#i637DxS)"><path class="c9cv27cck"/><path fill="url(#iszcHob)" class="ktl4e9bya"/></g><g filter="url(#impCXHp)"><path fill="url(#int20Xd)" class="cy93w4u1k"/></g><path class="oi6nokbyq"/><path fill="url(#ilstd7d)" class="y2vknabsu"/><path class="ikmt3oi5p"/><g filter="url(#iw8zfcd)"><path fill="url(#iMuXX6c)" class="h_v8t2rlx"/></g><g filter="url(#iM8UAqd)"><ellipse transform="rotate(-27.914 13.547 9.956)" class="ebys0kbgr"/><ellipse fill="url(#igxaqOe)" transform="rotate(-27.914 13.547 9.956)" class="zy43xh0vl"/></g><g filter="url(#izTgLEc)"><path stroke="url(#i9437oe)" class="apbgrhb_o"/></g><g filter="url(#i01mWZd)"><path class="f2w6uabgk"/></g><g filter="url(#i5JYYle)"><path class="w07xbth0r"/></g><g filter="url(#iTznUgb)"><path class="ok0d_xbkj"/></g><g filter="url(#iwZCV3b)"><path class="oflv90bjk"/></g><path fill="url(#iBhnmad)" class="cr9_z1bft"/><path fill="url(#iiHC3vd)" class="cr9_z1bft"/><path fill="url(#iYRNRLf)" class="cr9_z1bft"/><path fill="url(#iw8OL8b)" class="cr9_z1bft"/><g filter="url(#i4B8Nne)"><path fill="url(#i3jbBVc)" class="hii9ovp1o"/><path fill="url(#iGP28Je)" class="hii9ovp1o"/></g><g filter="url(#id3jQtb)"><path fill="url(#iXXwG9a)" class="d1ruefb7x"/><path fill="url(#iVKj7uc)" class="d1ruefb7x"/></g><path fill="url(#ilaJEee)" class="qylf6wbub"/><path fill="url(#iHRCiSc)" class="qylf6wbub"/><path fill="url(#iqWdVTd)" class="qylf6wbub"/><path fill="url(#imnlytb)" class="qylf6wbub"/><path fill="url(#i4PCG6d)" class="qylf6wbub"/><path fill="url(#iQPybpd)" class="qylf6wbub"/><path fill="url(#iRJILpP)" class="e_avwpn4q"/><defs><radialGradient id="iUhI09c" cx="0" cy="0" r="1" gradientTransform="rotate(119.999 8.37 12.873)scale(3.50014 9.06684)" gradientUnits="userSpaceOnUse"><stop class="jtnx86cjw"/><stop offset="1" class="ekl-imb0v"/></radialGradient><radialGradient id="ihWU4vd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 15.123)" gradientUnits="userSpaceOnUse"><stop class="yap4pcbws"/><stop offset="1" class="b0havcbgv"/></radialGradient><radialGradient id="iz6GOIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59143 1.98438 -5.14037 -4.12248 23.705 12.06)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="cva0eccxo"/><stop offset="1" class="yvvekm_dy"/></radialGradient><radialGradient id="iOivUbb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 15.123)" gradientUnits="userSpaceOnUse"><stop class="lp4if9b4k"/><stop offset="1" class="ofalufbug"/><stop offset="1" class="xilj489kn"/></radialGradient><radialGradient id="ibuxX9V" cx="0" cy="0" r="1" gradientTransform="rotate(134.256 9.246 11.762)scale(1.70162 4.86497)" gradientUnits="userSpaceOnUse"><stop class="jia0zn94s"/><stop offset="1" class="gabhccily"/></radialGradient><radialGradient id="imc1MXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59143 1.98438 -5.14037 -4.12248 23.705 12.06)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="g34co-bjj"/><stop offset="1" class="j0iym8bez"/></radialGradient><radialGradient id="iROJcPd" cx="0" cy="0" r="1" gradientTransform="rotate(10.063 -70.522 122.48)scale(1.6639 4.72832)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="r-p883bfh"/><stop offset="1" class="jnmw52bvm"/></radialGradient><radialGradient id="iyBw2jc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59143 1.98438 -5.14037 -4.12248 23.705 12.06)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="mrawv2bkv"/><stop offset="1" class="n437wwntr"/></radialGradient><radialGradient id="i5Xkmze" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 -.625 1.0554 3.06064 20.142 15.123)" gradientUnits="userSpaceOnUse"><stop class="fv4al1b2g"/><stop offset="1" class="ofalufbug"/></radialGradient><radialGradient id="iYZvCxd" cx="0" cy="0" r="1" gradientTransform="rotate(-98.799 12.543 4.647)scale(3.20061 3.97853)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ovi8m4ysy"/><stop offset="1" class="c7ltk09yg"/></radialGradient><radialGradient id="iJwxMPe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.39063 .57888 -1.52227 -6.28657 12.111 14.59)" gradientUnits="userSpaceOnUse"><stop class="ok95vkw1c"/><stop offset="1" class="k8vvgib0z"/></radialGradient><radialGradient id="iQcA7En" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -11.6596 23.142 20.841)" gradientUnits="userSpaceOnUse"><stop class="nadkffb-q"/><stop offset="1" class="g8_ztm4ee"/></radialGradient><radialGradient id="iOfjqcd" cx="0" cy="0" r="1" gradientTransform="rotate(-110.347 20.531 5.262)scale(3.59496 4.80694)" gradientUnits="userSpaceOnUse"><stop class="n7-3g8b6a"/><stop offset="1" class="vn8pvc5iu"/></radialGradient><radialGradient id="isgVVHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.51484 .49425 -5.62821 -5.8627 15.745 29.022)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="pa8e75o9n"/><stop offset="1" class="yngnm5bdn"/></radialGradient><radialGradient id="iP6UBmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59707 0 0 -12.1778 9.033 30.094)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="xfqn-nbow"/><stop offset="1" class="mv5v-89yi"/></radialGradient><radialGradient id="ihNLNpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69302 6.8777 -1.92029 -.4727 6.992 23.216)" gradientUnits="userSpaceOnUse"><stop class="tk0xf0bde"/><stop offset="1" class="d64kkcbzy"/></radialGradient><radialGradient id="izBzNGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 -10.40629 1.71323 -.26753 25.58 28.529)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="ybfplbczy"/><stop offset="1" class="y7tt4qbej"/></radialGradient><radialGradient id="i8cymIQ" cx="0" cy="0" r="1" gradientTransform="matrix(.49206 0 0 10.875 23.088 26.623)" gradientUnits="userSpaceOnUse"><stop class="f6wdi7zjk"/><stop offset="1" class="mdqyvu4ex"/></radialGradient><radialGradient id="iTXMv8b" cx="0" cy="0" r="1" gradientTransform="matrix(1.43994 -1.46875 8.18973 8.02909 15.736 29.935)" gradientUnits="userSpaceOnUse"><stop class="c11fd2rff"/><stop offset="1" class="qfs6aobhn"/></radialGradient><radialGradient id="ixwetQd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.42 17.282 11.452)scale(18.1601 26.3733)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="pc9y3hbhd"/><stop offset="1" class="vhxxajp3a"/></radialGradient><radialGradient id="iLSaoWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.53125 -8.40625 0 15.986 18.31)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="w4q7dg2ti"/><stop offset="1" class="ro5kwtkrd"/></radialGradient><radialGradient id="i2yDo0c" cx="0" cy="0" r="1" gradientTransform="rotate(97.64 -1.695 18.198)scale(3.08805 1.1998)" gradientUnits="userSpaceOnUse"><stop class="xnfwhubut"/><stop offset="1" class="nd_uzdbib"/></radialGradient><radialGradient id="ivXyFxp" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.63279 -.8125 0 16.517 22.685)" gradientUnits="userSpaceOnUse"><stop class="kna63ccqu"/><stop offset="1" class="yg8va_99z"/></radialGradient><radialGradient id="iCWbHoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.22354 13.8281 0 16 21.287)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="g9gcawu6z"/><stop offset="1" class="hpb-k7b_o"/></radialGradient><radialGradient id="iuKX0Uc" cx="0" cy="0" r="1" gradientTransform="rotate(153.453 7.604 9.74)scale(9.41646 14.488)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="ngc6h6bst"/><stop offset="1" class="o5llqtbdv"/></radialGradient><radialGradient id="i6bZPzd" cx="0" cy="0" r="1" gradientTransform="matrix(6.05257 5.9867 -7.0398 7.11726 14.455 14.53)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="s1jm76o_g"/><stop offset="1" class="a0ve6ibhs"/></radialGradient><radialGradient id="icEs3vd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.94665 -1.47583 .92553 -2.47504 13.644 16.072)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="u9m-38uic"/><stop offset="1" class="dgp6vzbgz"/></radialGradient><radialGradient id="iAGCnhe" cx="0" cy="0" r="1" gradientTransform="rotate(120.992 5.816 12.626)scale(7.05716 2.39887)" gradientUnits="userSpaceOnUse"><stop offset=".447" class="pf0n6ab7v"/><stop offset="1" class="xu2rljbva"/></radialGradient><radialGradient id="ibYEbXc" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 -4.22173 3.11001 1.6575 16.142 20.563)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="gnhb80bte"/><stop offset="1" class="csoeneffd"/></radialGradient><radialGradient id="iSI1pQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.4375 -2.83801 0 15.98 16.654)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="w_g3s13ar"/><stop offset="1" class="h51_dbc-u"/></radialGradient><radialGradient id="i12D23b" cx="0" cy="0" r="1" gradientTransform="matrix(2.3573 2.11087 -1.5527 1.73398 12.848 16.341)" gradientUnits="userSpaceOnUse"><stop class="a6fqwgytn"/><stop offset="1" class="r95smjb9e"/></radialGradient><radialGradient id="iXmaopd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4697 -1.59165 3.40232 3.14166 8.65 11.062)" gradientUnits="userSpaceOnUse"><stop class="kfvg-ibgk"/><stop offset="1" class="tu1u92deh"/></radialGradient><radialGradient id="ibc7VAe" cx="0" cy="0" r="1" gradientTransform="rotate(36.966 -5.48 37.15)scale(1.58514 3.3249)" gradientUnits="userSpaceOnUse"><stop offset=".42" class="e_w7q4bzg"/><stop offset="1" class="ql319_bzl"/></radialGradient><radialGradient id="i00iwFA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3993 -1.03573 3.6547 -4.9376 22.801 11.702)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="g0zuqlb2x"/><stop offset="1" class="w13wmz2qy"/></radialGradient><radialGradient id="i6GLopc" cx="0" cy="0" r="1" gradientTransform="rotate(-143.844 7.348 4.223)scale(3.06704 1.99268)" gradientUnits="userSpaceOnUse"><stop class="j5muupbkd"/><stop offset="1" class="gjlmj_buv"/></radialGradient><radialGradient id="iGE0NUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.65395 -1.20896 4.23858 5.79872 8.829 11.771)" gradientUnits="userSpaceOnUse"><stop offset=".659" class="o0_au1boj"/><stop offset=".837" class="myk922b4n"/></radialGradient><radialGradient id="iyavIQe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.08924 0 0 -8.4155 18.651 11.572)" gradientUnits="userSpaceOnUse"><stop class="ns5sv0buf"/><stop offset=".697" class="why1gym5a"/></radialGradient><radialGradient id="iR90U6u" cx="0" cy="0" r="1" gradientTransform="rotate(-123.877 9.592 1.34)scale(1.14297 1.22408)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="wul7c-b4h"/><stop offset="1" class="poi0tmb7g"/></radialGradient><radialGradient id="iqaJ9ye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.10473 1.36069 0 18.313 9.952)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="uwlo_lrjf"/><stop offset="1" class="khsdh5btp"/></radialGradient><radialGradient id="ivTJxQb" cx="0" cy="0" r="1" gradientTransform="rotate(121.203 6.897 8.81)scale(2.45067 1.84691)" gradientUnits="userSpaceOnUse"><stop class="yk6rc6bdo"/><stop offset="1" class="lmkkm5bue"/></radialGradient><radialGradient id="in42Sgd" cx="0" cy="0" r="1" gradientTransform="rotate(75.536 3.332 12.816)scale(2.60356 7.90832)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="tyvpz8bad"/><stop offset="1" class="q610egb7t"/></radialGradient><radialGradient id="irzXOZg" cx="0" cy="0" r="1" gradientTransform="matrix(.5527 -4.65058 16.9388 2.01311 15.404 17.016)" gradientUnits="userSpaceOnUse"><stop offset=".086" class="l47b6ebvd"/><stop offset="1" class="ysw8prt7q"/></radialGradient><radialGradient id="is1RgNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.62482 -10.2065 0 15.957 10.39)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="gig05tbvp"/><stop offset="1" class="wkxq4g5kj"/></radialGradient><radialGradient id="i0En4Ob" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 -.625 1.875 .98437 14.614 14.31)" gradientUnits="userSpaceOnUse"><stop class="plcv9bbgt"/><stop offset="1" class="ehc1wgbxk"/></radialGradient><radialGradient id="iP8FdEd" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 6.732 9.582)scale(1.10543 1.21398)" gradientUnits="userSpaceOnUse"><stop class="gvj3_fmrq"/><stop offset="1" class="cap0zjbhu"/></radialGradient><radialGradient id="iszcHob" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.459 .671)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilstd7d" cx="0" cy="0" r="1" gradientTransform="rotate(127.812 4.55 8.513)scale(1.10548 1.21404)" gradientUnits="userSpaceOnUse"><stop class="gvj3_fmrq"/><stop offset="1" class="cap0zjbhu"/></radialGradient><radialGradient id="igxaqOe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.53 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBhnmad" cx="0" cy="0" r="1" gradientTransform="rotate(117.277 8.224 7.024)scale(5.59037 9.77256)" gradientUnits="userSpaceOnUse"><stop class="kiv74wb2h"/><stop offset="1" class="z0iql0b7g"/></radialGradient><radialGradient id="iiHC3vd" cx="0" cy="0" r="1" gradientTransform="rotate(77.064 7.715 14.653)scale(3.76819 1.45448)" gradientUnits="userSpaceOnUse"><stop class="jiddj6b6s"/><stop offset="1" class="sehfhem7y"/></radialGradient><radialGradient id="iYRNRLf" cx="0" cy="0" r="1" gradientTransform="matrix(2.40579 .10802 -.24206 5.39134 9.146 7.597)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="zm33vvbpb"/><stop offset="1" class="nc9cy1gbz"/></radialGradient><radialGradient id="iw8OL8b" cx="0" cy="0" r="1" gradientTransform="rotate(109.616 4.569 5.918)scale(4.28106 1.6355)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="pt7ynj-7s"/><stop offset="1" class="zssv1vu-c"/></radialGradient><radialGradient id="iGP28Je" cx="0" cy="0" r="1" gradientTransform="rotate(174.358 7.95 2.635)scale(4.60936 3.17873)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="yo4_wwpln"/><stop offset="1" class="fnjjkvb8k"/></radialGradient><radialGradient id="iXXwG9a" cx="0" cy="0" r="1" gradientTransform="matrix(3.46793 .19046 -.05313 .96742 19.002 4.707)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="ptpp24bic"/><stop offset="1" class="g-hvquhzr"/></radialGradient><radialGradient id="iVKj7uc" cx="0" cy="0" r="1" gradientTransform="matrix(.97843 -1.5241 5.30456 3.40535 18.958 5.485)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="s0qsib-ln"/><stop offset="1" class="i5bggbceb"/></radialGradient><radialGradient id="imnlytb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09375 0 0 -.60938 21.767 6.234)" gradientUnits="userSpaceOnUse"><stop class="ekarirbxr"/><stop offset="1" class="n81djoa0z"/></radialGradient><radialGradient id="i4PCG6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .54688 -8.71875 0 11.174 5.702)" gradientUnits="userSpaceOnUse"><stop offset=".257" class="b4qr-wvfv"/><stop offset="1" class="yyik5z8lx"/></radialGradient><radialGradient id="iQPybpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .92969 -.45312 0 15.228 5.921)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="h6i96qjvc"/><stop offset="1" class="d31bklhyx"/></radialGradient><radialGradient id="iRJILpP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.90625 2.05457 0 15.978 7.5)" gradientUnits="userSpaceOnUse"><stop class="rkzp1hbvm"/><stop offset="1" class="j5zu11bke"/></radialGradient><filter id="iNfQNHd" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.827451 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.807843 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1377" result="effect2_innerShadow_4002_1377"/></filter><filter id="idDmqYP" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.219608 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.215686 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1377" result="effect2_innerShadow_4002_1377"/></filter><filter id="iHDOhGe" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.270588 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.282353 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1377" result="effect2_innerShadow_4002_1377"/></filter><filter id="ikW0jie" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.94902 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1377" result="effect2_innerShadow_4002_1377"/></filter><filter id="ihzmacc" width="7.408" height="7.009" x="17.877" y="11.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.278431 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.235294 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1377" result="effect2_innerShadow_4002_1377"/></filter><filter id="iH9euue" width="7.258" height="6.609" x="6.975" y="11.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.227451 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/></filter><filter id="iWtQnHe" width="2.581" height="5.008" x="14.415" y="20.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".25"/></filter><filter id="iz4FDMb" width="1.681" height="4.108" x="15.197" y="21.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/></filter><filter id="ioSe0ic" width="13.169" height="6.924" x="9.415" y="14.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/></filter><filter id="ifTScgb" width="4.058" height="5.011" x="20.39" y="8.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.619608 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/></filter><filter id="iv3lXSb" width="4.258" height="5.211" x="7.452" y="8.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.392157 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.658824 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1377" result="effect2_innerShadow_4002_1377"/></filter><filter id="iU88QWV" width="3.614" height="3.845" x="20.514" y="9.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".1"/></filter><filter id="is7opjd" width="3.274" height="3.37" x="20.512" y="9.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".05"/></filter><filter id="iicfauc" width="3.972" height="2.892" x="20.383" y="8.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".075"/></filter><filter id="irnMHmd" width="3.202" height="2.498" x="8.089" y="9.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".05"/></filter><filter id="i6d9lCc" width="10.987" height="10.888" x="10.713" y="6.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.682353 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/></filter><filter id="iuoX1Rc" width="2.687" height="3.9" x="14.354" y="9.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".25"/></filter><filter id="iZ5OctJ" width="2.077" height="3.1" x="15.061" y="9.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.65098 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/></filter><filter id="iiOHiVb" width="3.668" height="1.523" x="14.166" y="13.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".075"/></filter><filter id="i637DxS" width=".787" height=".696" x="17.448" y="9.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".05"/></filter><filter id="impCXHp" width=".891" height=".913" x="18.287" y="9.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".1"/></filter><filter id="iw8zfcd" width=".986" height="1.04" x="13.845" y="9.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".1"/></filter><filter id="iM8UAqd" width=".913" height=".705" x="13.09" y="9.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".05"/></filter><filter id="izTgLEc" width="2.916" height="3.003" x="13.723" y="18.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".125"/></filter><filter id="i01mWZd" width="2.863" height="1.636" x="12.052" y="7.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.101961 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/></filter><filter id="i5JYYle" width="2.563" height="1.336" x="12.078" y="7.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".15"/></filter><filter id="iTznUgb" width="2.891" height="1.641" x="17.244" y="7.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.101961 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1377"/></filter><filter id="iwZCV3b" width="2.591" height="1.341" x="17.316" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".15"/></filter><filter id="i4B8Nne" width="6.417" height="5.694" x="9.953" y="2.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".125"/></filter><filter id="id3jQtb" width="6.176" height="5.689" x="15.87" y="2.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1377" stdDeviation=".125"/></filter><linearGradient id="iTsW5Nc" x1="15.049" x2="15.049" y1="30.094" y2="20.685" gradientUnits="userSpaceOnUse"><stop offset=".04" class="wogh8-v4o"/><stop offset="1" class="dt3zaebva"/></linearGradient><linearGradient id="ibiEGBb" x1="23.291" x2="22.822" y1="26.669" y2="26.669" gradientUnits="userSpaceOnUse"><stop offset=".327" class="iy0z3721s"/><stop offset="1" class="mm4k6y1ti"/></linearGradient><linearGradient id="iER4OWb" x1="8.912" x2="8.912" y1="30.094" y2="21.279" gradientUnits="userSpaceOnUse"><stop class="ycfa7kt7e"/><stop offset="1" class="kwgh1rbji"/></linearGradient><linearGradient id="ie411je" x1="24.142" x2="26.611" y1="29.466" y2="21.56" gradientUnits="userSpaceOnUse"><stop offset=".116" class="ht2yhibat"/><stop offset="1" class="p8cmnpbrm"/></linearGradient><linearGradient id="i8aYqre" x1="12.517" x2="22.705" y1="21.435" y2="31.091" gradientUnits="userSpaceOnUse"><stop class="te0saggyn"/><stop offset="1" class="wsy42fbgm"/></linearGradient><linearGradient id="iUn8IAz" x1="26.895" x2="21.238" y1="31.06" y2="26.873" gradientUnits="userSpaceOnUse"><stop class="gbkgrm1fg"/><stop offset="1" class="gb051imgb"/></linearGradient><linearGradient id="i5Lj3Yc" x1="15.015" x2="15.229" y1="28.829" y2="28.625" gradientUnits="userSpaceOnUse"><stop class="p8z5r2h1v"/><stop offset="1" class="nstnghbkd"/></linearGradient><linearGradient id="i82dLZi" x1="19.002" x2="18.65" y1="22.138" y2="22.498" gradientUnits="userSpaceOnUse"><stop class="i-kbbcb4w"/><stop offset="1" class="k1jzsjbfs"/></linearGradient><linearGradient id="iAQmG5V" x1="17.642" x2="17.221" y1="18.748" y2="18.452" gradientUnits="userSpaceOnUse"><stop class="e6cu90bdx"/><stop offset="1" class="o8pucipdw"/></linearGradient><linearGradient id="iaoILVy" x1="22.369" x2="22.369" y1="8.607" y2="13.518" gradientUnits="userSpaceOnUse"><stop class="st7ui8b-i"/><stop offset="1" class="k3vunibah"/></linearGradient><linearGradient id="iakErhb" x1="21.817" x2="23.407" y1="12.441" y2="9.413" gradientUnits="userSpaceOnUse"><stop offset=".667" class="yfcig1bqm"/><stop offset="1" class="l8ohao8ua"/></linearGradient><linearGradient id="iMwngab" x1="21.381" x2="19.771" y1="11.921" y2="11.853" gradientUnits="userSpaceOnUse"><stop offset=".267" class="c3yg3qbng"/><stop offset="1" class="bh1gqswfc"/></linearGradient><linearGradient id="iobaHWd" x1="15.957" x2="15.957" y1="6.816" y2="7.754" gradientUnits="userSpaceOnUse"><stop class="gufw3faob"/><stop offset="1" class="kyv9z1e5d"/></linearGradient><linearGradient id="ibFu8ad" x1="16.848" x2="15.233" y1="11.591" y2="11.734" gradientUnits="userSpaceOnUse"><stop offset=".117" class="a7vfdrbiy"/><stop offset=".685" class="x6mjr8bji"/></linearGradient><linearGradient id="ii5x2od" x1="15.832" x2="15.832" y1="12.847" y2="12.224" gradientUnits="userSpaceOnUse"><stop offset=".072" class="qqhnf6bwq"/><stop offset="1" class="wrr4h5buo"/></linearGradient><linearGradient id="int20Xd" x1="18.96" x2="18.646" y1="10.105" y2="10.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMuXX6c" x1="14.562" x2="14.248" y1="10.105" y2="10.299" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9437oe" x1="15.861" x2="14.049" y1="20.654" y2="18.17" gradientUnits="userSpaceOnUse"><stop class="qd6na2-uz"/><stop offset="1" class="syu7jn24l"/></linearGradient><linearGradient id="i3jbBVc" x1="12.346" x2="13.018" y1="6.522" y2="3.132" gradientUnits="userSpaceOnUse"><stop class="d2a8zqasd"/><stop offset="1" class="aeqmmkbom"/></linearGradient><linearGradient id="ilaJEee" x1="15.58" x2="17.299" y1="6.407" y2="6.407" gradientUnits="userSpaceOnUse"><stop class="z5duhrbsp"/><stop offset="1" class="qjga9kbjc"/></linearGradient><linearGradient id="iHRCiSc" x1="15.644" x2="15.644" y1="7.064" y2="6.407" gradientUnits="userSpaceOnUse"><stop class="i817agb_c"/><stop offset="1" class="tp-3hccxn"/></linearGradient><linearGradient id="iqWdVTd" x1="15.969" x2="15.969" y1="5.491" y2="6.077" gradientUnits="userSpaceOnUse"><stop class="p59cvi4fc"/><stop offset="1" class="nr_-dacny"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-elf-light" /></template>
<style>
.a0ve6ibhs {
  stop-color: var(--svg-color--9f6c64, #9F6C64);
}

.a6fqwgytn {
  stop-color: var(--svg-color--955944, #955944);
}

.a6tzm1b6f {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.39 9.302c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.128 1.37-1.128");
}

.a7a1m8boe {
  d: path("M15.706 21.287c.263.221.79.924.79 1.906c0 1.053-.358 1.647-.702 2.06a.115.115 0 0 1-.177 0c-.343-.413-.702-1.007-.702-2.06c0-.982.527-1.685.79-1.906");
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.aeqmmkbom {
  stop-color: var(--svg-color--181018, #181018);
  stop-opacity: 0;
}

.apbgrhb_o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m14.049 18.591l1.562 2.188c.12.125.428.3.703 0");
}

.b0havcbgv {
  stop-color: var(--svg-color--dc8d16, #DC8D16);
  stop-opacity: 0;
}

.b4mo-29ij {
  d: path("M8.381 12.88c.735-.625 1.279-1.255 1.368-1.594h4.234v3.281l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.023c-.359-1.281.188-2.11 1.297-2.992");
}

.b4qr-wvfv {
  stop-color: var(--svg-color--949393, #949393);
}

.b6c6q1bjp {
  fill: var(--svg-color--ecb9a0, #ECB9A0);
  d: path("m15.618 10.253l-.532 1.838c-.109.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.bh1gqswfc {
  stop-color: var(--svg-color--ffdac0, #FFDAC0);
  stop-opacity: 0;
}

.bm_9q5x_x {
  fill: var(--svg-color--ffd8bf, #FFD8BF);
  d: path("M20.955 10.248c.05.083.177.232.289.164c.14-.086.977-1.008 2.438-1.5c.323-.09.467.112.511.26c-.028-.062-.111-.138-.308-.143c-.32-.008-1.938.64-3.352 2.453z");
}

.c11fd2rff {
  stop-color: var(--svg-color--995a60, #995A60);
}

.c27hakbuc {
  d: path("M11.65 6.128c-.19.25-.68 1.16-.857 1.557c-.117.184-.073.534-.062.711l.258 5.257c.073 2.122 1.397 3.363 3.409 3.363h3.142c2.033 0 3.317-1.305 3.372-3.35l.28-5.14c.011-.178.031-.79-.086-.974c-.177-.397-.629-1.173-.819-1.424z");
}

.c3yg3qbng {
  stop-color: var(--svg-color--ffd4b9, #FFD4B9);
}

.c7ltk09yg {
  stop-color: var(--svg-color--151f0e, #151F0E);
  stop-opacity: 0;
}

.c9cv27cck {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.763c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.389-.051");
}

.cap0zjbhu {
  stop-color: var(--svg-color--684a43, #684A43);
}

.ci4cb1xgu {
  d: path("M23.527 8.63c-1.524.44-2.582 1.437-2.928 1.89l-.21 2.95c.4.018.94.243 1.935-.466c1.164-1.042 1.72-2.577 1.999-3.546a.67.67 0 0 0-.136-.615a.64.64 0 0 0-.66-.213");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr9_z1bft {
  d: path("M10.09 9.373v-.375a2.2 2.2 0 0 0-.18-.711a3 3 0 0 0-.126-.23c-.215-.363-.537-.909-.398-1.864c.157-1.077.802-1.476 1.371-1.83q.082-.05.16-.1c.131-.083.254-.154.37-.222c.418-.244.758-.443 1.13-.98c.477-.688 1.36-1.298 2.423-1.126l.159.03c.506.092.734.134.919.134c.23 0 .56-.05 1.18-.164c1.062-.172 1.945.438 2.421 1.125c.373.538.713.737 1.131.981q.174.1.37.222q.078.05.16.1c.569.354 1.214.753 1.37 1.83c.14.955-.182 1.5-.397 1.864c-.05.086-.095.161-.126.23a2.2 2.2 0 0 0-.18.71v.417c-.286.19-.533.385-.735.566c.02-.465.063-1.215.08-1.451c.023-.336.015-.617-.173-.953c-.086-.154-.288-.423-.478-.675c-.14-.187-.274-.365-.35-.481h-8.554c-.178.273-.57.887-.72 1.156c-.187.336-.195.617-.171.953c.016.227.044.917.062 1.381a6.4 6.4 0 0 0-.718-.537");
}

.csoeneffd {
  stop-color: var(--svg-color--d3998b, #D3998B);
}

.cva0eccxo {
  stop-color: var(--svg-color--41393b, #41393B);
}

.cy93w4u1k {
  d: path("M18.979 10.35a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.d1ruefb7x {
  d: path("M21.792 6.64c-.054.825-.365 1.33-.502 1.44c.022-.222-.35-.714-.583-1.02s-.253-.415-.462-.42h-1.19c-.903 0-1.917-.141-2.551-1.086s-.373-1.883 0-2.297s1.074-.54 1.581-.047c.507.492.917.414 1.999.89c1.081.477 1.775 1.508 1.707 2.54");
}

.d2a8zqasd {
  stop-color: var(--svg-color--181018, #181018);
}

.d31bklhyx {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
  stop-opacity: 0;
}

.d64kkcbzy {
  stop-color: var(--svg-color--49a1ec, #49A1EC);
  stop-opacity: 0;
}

.da96dzbnj {
  d: path("M11.387 12.016c-.904-1.684-2.446-2.402-3.074-2.56c.598 1.662 1.19 2.452 1.6 2.81c.44.384 1.057.369 1.293.355z");
}

.dgp6vzbgz {
  stop-color: var(--svg-color--613528, #613528);
  stop-opacity: 0;
}

.dt3zaebva {
  stop-color: var(--svg-color--3a84e4, #3A84E4);
  stop-opacity: 0;
}

.e_avwpn4q {
  d: path("M15.906 4.38a.103.103 0 0 1 .144 0c.269.256.694.87.694 1.701c0 .974-.346 1.524-.679 1.907a.115.115 0 0 1-.174 0c-.332-.383-.678-.933-.678-1.907c0-.83.425-1.445.693-1.702");
}

.e_w7q4bzg {
  stop-color: var(--svg-color--e9bdad, #E9BDAD);
}

.e2tgz4b_p {
  fill: var(--svg-color--cc8f8d, #CC8F8D);
  d: path("m15.447 10.449l-.57 1.838c-.098.378.136.756.467.756h.707c.331 0 .565-.384.468-.756l-.478-1.838c-.102-.408-.487-.408-.594 0");
}

.e6cu90bdx {
  stop-color: var(--svg-color--cb917b, #CB917B);
}

.ebys0kbgr {
  cx: 13.547px;
  cy: 9.956px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ehc1wgbxk {
  stop-color: var(--svg-color--d8a28e, #D8A28E);
  stop-opacity: 0;
}

.ekarirbxr {
  stop-color: var(--svg-color--ede5f4, #EDE5F4);
}

.ekl-imb0v {
  stop-color: var(--svg-color--ffc737, #FFC737);
  stop-opacity: 0;
}

.f2w6uabgk {
  stroke: var(--svg-color--060506, #060506);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M12.528 8.305c.217-.171.831-.519 1.662-.418");
}

.f6wdi7zjk {
  stop-color: var(--svg-color--187ed9, #187ED9);
}

.fnjjkvb8k {
  stop-color: var(--svg-color--494446, #494446);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv4al1b2g {
  stop-color: var(--svg-color--120a0c, #120A0C);
}

.g-hvquhzr {
  stop-color: var(--svg-color--4e494a, #4E494A);
  stop-opacity: 0;
}

.g0zuqlb2x {
  stop-color: var(--svg-color--e0b19c, #E0B19C);
  stop-opacity: 0;
}

.g34co-bjj {
  stop-color: var(--svg-color--fff1bb, #FFF1BB);
}

.g8_ztm4ee {
  stop-color: var(--svg-color--56b5ff, #56B5FF);
  stop-opacity: 0;
}

.g9gcawu6z {
  stop-color: var(--svg-color--9f6561, #9F6561);
}

.gabhccily {
  stop-color: var(--svg-color--544442, #544442);
  stop-opacity: 0;
}

.gb051imgb {
  stop-color: var(--svg-color--b78174, #B78174);
  stop-opacity: 0;
}

.gbkgrm1fg {
  stop-color: var(--svg-color--b78174, #B78174);
}

.gig05tbvp {
  stop-color: var(--svg-color--d59c9e, #D59C9E);
  stop-opacity: 0;
}

.gjlmj_buv {
  stop-color: var(--svg-color--bb8c82, #BB8C82);
}

.gnhb80bte {
  stop-color: var(--svg-color--e7b1a1, #E7B1A1);
}

.gq_evtgpi {
  d: path("M8.473 8.63c1.524.44 2.582 1.437 2.928 1.89l.209 2.95c-.399.018-.94.243-1.934-.466c-1.165-1.042-1.72-2.577-1.999-3.546a.67.67 0 0 1 .135-.615a.64.64 0 0 1 .66-.213");
}

.gr7x_rwbv {
  d: path("M16.274 30.094L7.053 20.5a10.95 10.95 0 0 1 5.854-4.208L26.69 30.094z");
}

.gufw3faob {
  stop-color: var(--svg-color--b2827a, #B2827A);
}

.gvj3_fmrq {
  stop-color: var(--svg-color--7b5649, #7B5649);
}

.h_v8t2rlx {
  d: path("M14.631 10.362c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.h51_dbc-u {
  stop-color: var(--svg-color--c07974, #C07974);
  stop-opacity: 0;
}

.h68lkf1_a {
  fill: var(--svg-color--51b9ff, #51B9FF);
  d: path("M23.088 18.457a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.h6i96qjvc {
  stop-color: var(--svg-color--9d9ea7, #9D9EA7);
}

.hii9ovp1o {
  d: path("M10.208 6.64c.056.825.291 1.336.435 1.445c-.024-.221.271-.55.463-.892c.218-.39.406-.548.625-.553c.075 0 .609-.024 1.365 0c1.484.046 1.937-.149 2.601-1.094c.665-.945.44-1.875.05-2.29a1.174 1.174 0 0 0-1.656-.046c-.531.492-.961.414-2.094.89s-1.86 1.508-1.79 2.54");
}

.hpb-k7b_o {
  stop-color: var(--svg-color--6b3f38, #6B3F38);
}

.ht2yhibat {
  stop-color: var(--svg-color--4e7ece, #4E7ECE);
}

.i-kbbcb4w {
  stop-color: var(--svg-color--906550, #906550);
}

.i5bggbceb {
  stop-color: var(--svg-color--4f494b, #4F494B);
}

.i817agb_c {
  stop-color: var(--svg-color--9777b8, #9777B8);
}

.ik39jqbsn {
  fill: var(--svg-color--3f9ef2, #3F9EF2);
  d: path("M5.071 26.776c0-6.036 4.893-10.928 10.929-10.928s10.929 4.892 10.929 10.928v3.318H5.07z");
}

.ikmt3oi5p {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.467a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.235");
}

.iy0z3721s {
  stop-color: var(--svg-color--288ce5, #288CE5);
}

.j--tlacac {
  fill: var(--svg-color--18121b, #18121B);
  d: path("M8.381 12.88c.735-.625 1.279-1.255 1.368-1.594h4.234v3.281l-3.313 3.328c-2.469-.082-3.322-1.084-3.586-2.023c-.359-1.281.188-2.11 1.297-2.992");
}

.j0iym8bez {
  stop-color: var(--svg-color--ffdbac, #FFDBAC);
  stop-opacity: 0;
}

.j5muupbkd {
  stop-color: var(--svg-color--bc887e, #BC887E);
}

.j5zu11bke {
  stop-color: var(--svg-color--c2ffff, #C2FFFF);
}

.j9cj5qbuy {
  fill: var(--svg-color--231622, #231622);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.jia0zn94s {
  stop-color: var(--svg-color--544442, #544442);
}

.jiddj6b6s {
  stop-color: var(--svg-color--555152, #555152);
}

.jnmw52bvm {
  stop-color: var(--svg-color--f2c192, #F2C192);
  stop-opacity: 0;
}

.jtnx86cjw {
  stop-color: var(--svg-color--ffc737, #FFC737);
}

.jz8djgftu {
  d: path("M15.988 21.248c.264.22.79.924.79 1.906c0 1.053-.358 1.647-.701 2.06a.115.115 0 0 1-.178 0c-.343-.413-.702-1.007-.702-2.06c0-.982.528-1.685.791-1.906");
}

.k1jzsjbfs {
  stop-color: var(--svg-color--7f4b4c, #7F4B4C);
  stop-opacity: 0;
}

.k3vunibah {
  stop-color: var(--svg-color--e4b5a0, #E4B5A0);
}

.k8vvgib0z {
  stop-color: var(--svg-color--160e18, #160E18);
  stop-opacity: 0;
}

.kfvg-ibgk {
  stop-color: var(--svg-color--cc9a8d, #CC9A8D);
}

.khsdh5btp {
  stop-color: var(--svg-color--fabeaa, #FABEAA);
  stop-opacity: 0;
}

.kiv74wb2h {
  stop-color: var(--svg-color--3a3134, #3A3134);
}

.kna63ccqu {
  stop-color: var(--svg-color--fffbb9, #FFFBB9);
}

.ktl4e9bya {
  d: path("M18.118 9.763c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.326-.136.389-.051");
}

.kwgh1rbji {
  stop-color: var(--svg-color--3a7edd, #3A7EDD);
  stop-opacity: 0;
}

.kyv9z1e5d {
  stop-color: var(--svg-color--d9a492, #D9A492);
  stop-opacity: 0;
}

.l47b6ebvd {
  stop-color: var(--svg-color--d49e99, #D49E99);
}

.l8ohao8ua {
  stop-color: var(--svg-color--ffdac2, #FFDAC2);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmkkm5bue {
  stop-color: var(--svg-color--eab6a5, #EAB6A5);
  stop-opacity: 0;
}

.lp4if9b4k {
  stop-color: var(--svg-color--180c11, #180C11);
}

.mcb3mdbmq {
  fill: var(--svg-color--432f32, #432F32);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.mdqyvu4ex {
  stop-color: var(--svg-color--187ed9, #187ED9);
  stop-opacity: 0;
}

.mm4k6y1ti {
  stop-color: var(--svg-color--54adff, #54ADFF);
  stop-opacity: 0;
}

.mrawv2bkv {
  stop-color: var(--svg-color--494646, #494646);
}

.mv5v-89yi {
  stop-color: var(--svg-color--1f62c6, #1F62C6);
  stop-opacity: 0;
}

.myk922b4n {
  stop-color: var(--svg-color--bb887f, #BB887F);
}

.n437wwntr {
  stop-color: var(--svg-color--494646, #494646);
  stop-opacity: 0;
}

.n7-3g8b6a {
  stop-color: var(--svg-color--519df1, #519DF1);
}

.n81djoa0z {
  stop-color: var(--svg-color--cfc9e2, #CFC9E2);
  stop-opacity: 0;
}

.nadkffb-q {
  stop-color: var(--svg-color--56b5ff, #56B5FF);
}

.nc9cy1gbz {
  stop-color: var(--svg-color--403735, #403735);
  stop-opacity: 0;
}

.nd_uzdbib {
  stop-color: var(--svg-color--7f4a45, #7F4A45);
}

.ngc6h6bst {
  stop-color: var(--svg-color--8d625b, #8D625B);
  stop-opacity: 0;
}

.nihdl4b3y {
  fill: var(--svg-color--ffcfa1, #FFCFA1);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.nr_-dacny {
  stop-color: var(--svg-color--a29b98, #A29B98);
  stop-opacity: 0;
}

.ns5sv0buf {
  stop-color: var(--svg-color--ffdbbf, #FFDBBF);
}

.nstnghbkd {
  stop-color: var(--svg-color--975a60, #975A60);
  stop-opacity: 0;
}

.o0_au1boj {
  stop-color: var(--svg-color--bb887f, #BB887F);
  stop-opacity: 0;
}

.o5llqtbdv {
  stop-color: var(--svg-color--8d625b, #8D625B);
}

.o8pucipdw {
  stop-color: var(--svg-color--d49d8a, #D49D8A);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofalufbug {
  stop-color: var(--svg-color--120a0c, #120A0C);
  stop-opacity: 0;
}

.oflv90bjk {
  stroke: var(--svg-color--302f30, #302F30);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.457 8.235c-.218-.171-.86-.524-1.691-.423");
}

.oi6nokbyq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.302c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.ok0d_xbkj {
  stroke: var(--svg-color--060506, #060506);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M19.41 8.305c-.218-.171-.86-.523-1.69-.422");
}

.ok95vkw1c {
  stop-color: var(--svg-color--160e18, #160E18);
}

.ovi8m4ysy {
  stop-color: var(--svg-color--151f0e, #151F0E);
}

.p59cvi4fc {
  stop-color: var(--svg-color--a29b98, #A29B98);
}

.p8cmnpbrm {
  stop-color: var(--svg-color--4990e8, #4990E8);
  stop-opacity: 0;
}

.p8z5r2h1v {
  stop-color: var(--svg-color--8a575a, #8A575A);
}

.pa8e75o9n {
  stop-color: var(--svg-color--2d5fc4, #2D5FC4);
}

.pc9y3hbhd {
  stop-color: var(--svg-color--6e4641, #6E4641);
  stop-opacity: 0;
}

.peclnma7n {
  d: path("M20.714 12.383c.904-1.683 2.585-2.677 3.214-2.835c-.599 1.663-1.33 2.727-1.74 3.085c-.44.384-1.057.369-1.293.355z");
}

.pf0n6ab7v {
  stop-color: var(--svg-color--55302a, #55302A);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plcv9bbgt {
  stop-color: var(--svg-color--d8a28e, #D8A28E);
}

.pnmhoebug {
  stroke: var(--svg-color--ce9787, #CE9787);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M8.264 9.285c.656.281 1.844.836 2.851 2.149");
}

.poi0tmb7g {
  stop-color: var(--svg-color--cd978b, #CD978B);
  stop-opacity: 0;
}

.pqpxg6gcd {
  fill: var(--svg-color--ffa52a, #FFA52A);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.ps0fa7bxo {
  d: path("M23.088 18.457a10.9 10.9 0 0 1 3.84 8.319v3.318h-3.84z");
}

.pt7ynj-7s {
  stop-color: var(--svg-color--4c4a4b, #4C4A4B);
}

.ptpp24bic {
  stop-color: var(--svg-color--4e494a, #4E494A);
}

.q610egb7t {
  stop-color: var(--svg-color--c89188, #C89188);
  stop-opacity: 0;
}

.qd6na2-uz {
  stop-color: var(--svg-color--b1736a, #B1736A);
}

.qeihuuzsw {
  d: path("M18.184 9.574a.893.893 0 0 1 .86 1.128H17.32a.896.896 0 0 1 .864-1.128");
}

.qfs6aobhn {
  stop-color: var(--svg-color--a85d71, #A85D71);
  stop-opacity: 0;
}

.qjga9kbjc {
  stop-color: var(--svg-color--cdc7e1, #CDC7E1);
}

.ql319_bzl {
  stop-color: var(--svg-color--f1c2af, #F1C2AF);
}

.qqhnf6bwq {
  stop-color: var(--svg-color--e1a498, #E1A498);
}

.qttrphznb {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.467a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.qylf6wbub {
  d: path("M8.85 6.407a.53.53 0 0 1 .529-.529h13.18a.53.53 0 0 1 0 1.059H9.378a.53.53 0 0 1-.53-.53");
}

.r-p883bfh {
  stop-color: var(--svg-color--e3b482, #E3B482);
}

.r95smjb9e {
  stop-color: var(--svg-color--bc806d, #BC806D);
  stop-opacity: 0;
}

.rkzp1hbvm {
  stop-color: var(--svg-color--6fe9ff, #6FE9FF);
}

.ro5kwtkrd {
  stop-color: var(--svg-color--824d4f, #824D4F);
  stop-opacity: 0;
}

.s0qsib-ln {
  stop-color: var(--svg-color--4f494b, #4F494B);
  stop-opacity: 0;
}

.s1jm76o_g {
  stop-color: var(--svg-color--8b5548, #8B5548);
  stop-opacity: 0;
}

.sehfhem7y {
  stop-color: var(--svg-color--555152, #555152);
  stop-opacity: 0;
}

.st7ui8b-i {
  stop-color: var(--svg-color--f2c7b2, #F2C7B2);
}

.syu7jn24l {
  stop-color: var(--svg-color--b1736a, #B1736A);
  stop-opacity: 0;
}

.t34bfozye {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M16 13.864c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.te0saggyn {
  stop-color: var(--svg-color--7d4d4c, #7D4D4C);
}

.tk0xf0bde {
  stop-color: var(--svg-color--49a1ec, #49A1EC);
}

.tp-3hccxn {
  stop-color: var(--svg-color--9777b8, #9777B8);
  stop-opacity: 0;
}

.tu1u92deh {
  stop-color: var(--svg-color--bb8e82, #BB8E82);
}

.tyvpz8bad {
  stop-color: var(--svg-color--c89188, #C89188);
}

.u3yytvbgg {
  d: path("M12.12 14.779c-.82-.07-1.718.055-2.327 1.11c-.61.96-.793 3.254 1.914 4.5c1.443.663 3.695.898 4.293.898c.633 0 2.85-.235 4.293-.899c2.707-1.245 2.523-3.539 1.914-4.5c-.61-1.054-1.508-1.18-2.328-1.11l-3.88.14z");
}

.u9m-38uic {
  stop-color: var(--svg-color--4c200c, #4C200C);
}

.u9wqsy2sp {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16 13.864c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846s1.248-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33Z");
}

.uf8v-8bxn {
  fill: var(--svg-color--459be2, #459BE2);
  d: path("M8.912 18.457a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.uwlo_lrjf {
  stop-color: var(--svg-color--fabeaa, #FABEAA);
}

.vhxxajp3a {
  stop-color: var(--svg-color--6e4641, #6E4641);
}

.vn8pvc5iu {
  stop-color: var(--svg-color--519df1, #519DF1);
  stop-opacity: 0;
}

.w_g3s13ar {
  stop-color: var(--svg-color--c07974, #C07974);
}

.w07xbth0r {
  stroke: var(--svg-color--302f30, #302F30);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M12.528 8.305c.217-.171.831-.519 1.662-.418");
}

.w13wmz2qy {
  stop-color: var(--svg-color--e0b19c, #E0B19C);
}

.w4q7dg2ti {
  stop-color: var(--svg-color--411d19, #411D19);
}

.why1gym5a {
  stop-color: var(--svg-color--dba592, #DBA592);
}

.wifu-cbwd {
  d: path("M8.912 18.457a10.9 10.9 0 0 0-3.84 8.319v3.318h3.84z");
}

.wkxq4g5kj {
  stop-color: var(--svg-color--ba7384, #BA7384);
}

.wogh8-v4o {
  stop-color: var(--svg-color--3f70d2, #3F70D2);
}

.wrr4h5buo {
  stop-color: var(--svg-color--f1bda6, #F1BDA6);
  stop-opacity: 0;
}

.wsy42fbgm {
  stop-color: var(--svg-color--ae706a, #AE706A);
}

.wul7c-b4h {
  stop-color: var(--svg-color--d49b91, #D49B91);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.xbdij97tt {
  d: path("m15.719 20.408l-2.871-4.067h6.265l-2.863 4.067c-.164.215-.395.2-.531 0");
}

.xfqn-nbow {
  stop-color: var(--svg-color--1f62c6, #1F62C6);
}

.xilj489kn {
  stop-color: var(--svg-color--180c11, #180C11);
  stop-opacity: 0;
}

.xnfwhubut {
  stop-color: var(--svg-color--6f403b, #6F403B);
}

.xq8p_qumq {
  fill: var(--svg-color--1d1620, #1D1620);
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.xu2rljbva {
  stop-color: var(--svg-color--55302a, #55302A);
  stop-opacity: 0;
}

.y2vknabsu {
  d: path("M13.816 9.574a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.y59bi164p {
  d: path("m15.618 10.253l-.532 1.838c-.109.378.152.756.52.756h.787c.369 0 .63-.383.52-.756l-.53-1.838c-.115-.407-.646-.407-.765 0");
}

.y7tt4qbej {
  stop-color: var(--svg-color--5bb5ff, #5BB5FF);
  stop-opacity: 0;
}

.yap4pcbws {
  stop-color: var(--svg-color--dc8d16, #DC8D16);
}

.ybfplbczy {
  stop-color: var(--svg-color--76c1ff, #76C1FF);
}

.ycfa7kt7e {
  stop-color: var(--svg-color--3a66c5, #3A66C5);
}

.yfcig1bqm {
  stop-color: var(--svg-color--ffdac2, #FFDAC2);
}

.yg8va_99z {
  stop-color: var(--svg-color--eddda3, #EDDDA3);
}

.yk6rc6bdo {
  stop-color: var(--svg-color--eab6a5, #EAB6A5);
}

.yngnm5bdn {
  stop-color: var(--svg-color--2d5fc4, #2D5FC4);
  stop-opacity: 0;
}

.yo4_wwpln {
  stop-color: var(--svg-color--494446, #494446);
}

.ysw8prt7q {
  stop-color: var(--svg-color--d49e99, #D49E99);
  stop-opacity: 0;
}

.yvvekm_dy {
  stop-color: var(--svg-color--41393b, #41393B);
  stop-opacity: 0;
}

.yyik5z8lx {
  stop-color: var(--svg-color--949393, #949393);
  stop-opacity: 0;
}

.z-thopeux {
  d: path("M23.879 13.076c-.735-.625-1.279-1.255-1.368-1.594h-4.234v3.281l3.313 3.328c2.469-.082 3.322-1.084 3.585-2.023c.36-1.281-.187-2.11-1.296-2.992");
}

.z0iql0b7g {
  stop-color: var(--svg-color--170e10, #170E10);
}

.z5duhrbsp {
  stop-color: var(--svg-color--aba5ae, #ABA5AE);
}

.z77zzmbkv {
  d: path("M5.071 26.776c0-6.036 4.893-10.928 10.929-10.928s10.929 4.892 10.929 10.928v3.318H5.07z");
}

.zhwrqyb9y {
  d: path("M20.612 12.016c.905-1.684 2.446-2.402 3.075-2.56c-.598 1.662-1.19 2.452-1.6 2.81c-.44.384-1.057.369-1.294.355z");
}

.zm33vvbpb {
  stop-color: var(--svg-color--403735, #403735);
}

.zssv1vu-c {
  stop-color: var(--svg-color--4c4a4b, #4C4A4B);
  stop-opacity: 0;
}

.zy43xh0vl {
  cx: 13.547px;
  cy: 9.956px;
  rx: 0.39px;
  ry: 0.197px;
}

</style>
