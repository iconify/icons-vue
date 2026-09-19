<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i5DHQWN)"><path fill="url(#itmQLCe)" class="wxyv0wdsu"/></g><path fill="url(#ii5su7d)" class="g_4twtygr"/><path fill="url(#ias5dbb)" class="g_4twtygr"/><path fill="url(#iK3EgBb)" class="g_4twtygr"/><g filter="url(#iEP2Wxd)"><path stroke="url(#iB4bxce)" class="ghazelbak"/></g><g filter="url(#iFeuJzb)"><path fill="url(#iz9T9tc)" class="dyohud76n"/><path fill="url(#iztQKHe)" class="dyohud76n"/><path fill="url(#i6SaUXc)" class="dyohud76n"/></g><path fill="url(#iFI394c)" class="dcd-_dbuf"/><path fill="url(#i7uvnlc)" class="dcd-_dbuf"/><path fill="url(#iSTGFPe)" class="dcd-_dbuf"/><path fill="url(#im5jKee)" class="jeq1ehfie"/><path fill="url(#ikWBhLU)" class="jeq1ehfie"/><path fill="url(#ie7NHCd)" class="jeq1ehfie"/><path fill="url(#iITrxGd)" class="scfwrvpyt"/><path fill="url(#iu6xNxb)" class="scfwrvpyt"/><path fill="url(#ielxZLc)" class="c1vp4vb9v"/><g filter="url(#iZSkhec)"><path fill="url(#ibtUrKb)" class="f6iqo0uxc"/><path fill="url(#ivnDH2n)" class="f6iqo0uxc"/><path fill="url(#izmNZkb)" class="f6iqo0uxc"/><path fill="url(#iuMOOod)" class="f6iqo0uxc"/></g><g filter="url(#iwwtR2d)"><path fill="url(#iU98tmP)" class="yez5xuaez"/><path fill="url(#iqElwIe)" class="yez5xuaez"/><path fill="url(#ip1ZRVS)" class="yez5xuaez"/><path fill="url(#ivrcbmG)" class="yez5xuaez"/></g><path fill="url(#iyNxszc)" class="wy_1bzklb"/><g filter="url(#i59qYuc)"><path fill="url(#ipKyHPj)" class="bo19xjbxf"/><path fill="url(#imWU9ub)" class="bo19xjbxf"/></g><g filter="url(#iP55AKd)"><path fill="url(#inAtrvd)" class="qh4cj-bzx"/></g><path fill="url(#ikSKZZb)" class="upqd-mb8f"/><path clip-rule="evenodd" class="sf5a9or-k"/><path fill="url(#i9bqxuc)" clip-rule="evenodd" class="pwoqj7b-i"/><g filter="url(#itVgEBb)"><path fill="url(#ibMC3be)" class="tx8zphbjg"/><path fill="url(#iCjaqgd)" class="tx8zphbjg"/><path fill="url(#iQaPDme)" class="tx8zphbjg"/><path fill="url(#iDORSHV)" class="tx8zphbjg"/><path fill="url(#iw6Tx4X)" class="tx8zphbjg"/></g><g filter="url(#icTn5kb)"><path fill="url(#itMHp2d)" class="rgbpayb4r"/><path fill="url(#iWDJVQc)" class="rgbpayb4r"/><path fill="url(#iFHEIUd)" class="rgbpayb4r"/><path fill="url(#i6qzuUb)" class="rgbpayb4r"/><path fill="url(#ijYQWJd)" class="rgbpayb4r"/></g><path fill="url(#iSilWDb)" class="p6_wkpbgg"/><path fill="url(#ilaXOtc)" class="enkk5hp0q"/><g filter="url(#i1pXNmd)"><path stroke="url(#ijkCG0c)" class="ftauhbbbu"/></g><g filter="url(#iupPcje)"><path stroke="url(#iwEKOpb)" class="cctkm_bfn"/></g><g filter="url(#inJbCge)"><path stroke="url(#ivQIRgd)" class="pd7tuhb7r"/></g><g filter="url(#i5Ardgb)"><path stroke="url(#ixytWOb)" class="dincvfsjc"/></g><g filter="url(#iRisifd)"><path stroke="url(#iwHeyxe)" class="kj_qkabkk"/></g><g filter="url(#is20Zzd)"><path stroke="url(#i1PCAEp)" class="mqp55hb8m"/></g><path fill="url(#ieLWGhe)" class="hjkt_qaxp"/><path fill="url(#inSpDXc)" class="yldjwvbde"/><g filter="url(#ijeRKEd)"><path fill="url(#ixxJtmd)" class="y0_-ccbls"/><path fill="url(#i3vAIQd)" class="y0_-ccbls"/></g><path fill="url(#iydxg5d)" class="y0_-ccbls"/><path fill="url(#iEobh1b)" class="y0_-ccbls"/><path fill="url(#iLNKuMe)" class="y0_-ccbls"/><path fill="url(#iJ6dQyd)" class="y0_-ccbls"/><path fill="url(#igo8LKd)" class="y0_-ccbls"/><path fill="url(#iB7rDsT)" class="y0_-ccbls"/><path fill="url(#is0aE0c)" class="y0_-ccbls"/><g filter="url(#i5eBdhe)"><path class="rxom98b9a"/></g><g filter="url(#iTeBLOe)"><path class="npqz14brf"/><path fill="url(#iJ12CJz)" class="tjew41unp"/><path fill="url(#iYKlTdd)" class="tjew41unp"/><path fill="url(#i46596b)" class="tjew41unp"/><path fill="url(#imAhLme)" class="tjew41unp"/><path fill="url(#iy3LhEc)" class="tjew41unp"/></g><path fill="url(#iBNuohe)" class="tjew41unp"/><path fill="url(#iC7tFmb)" class="tjew41unp"/><g filter="url(#ifpZppe)"><path stroke="url(#iVor7Ds)" class="jl9r0cbox"/></g><path fill="url(#isNEhQe)" class="kst27wbry"/><g filter="url(#iPGBzXS)"><path fill="url(#iBWZkMb)" class="aoqe_ob0o"/><path fill="url(#iSLvWzb)" class="aoqe_ob0o"/><path fill="url(#iQadHPb)" class="aoqe_ob0o"/><path fill="url(#iagIUpc)" class="aoqe_ob0o"/><path fill="url(#ioTvREe)" class="aoqe_ob0o"/></g><g filter="url(#iNitIRj)"><path class="uo5n0hbpd"/></g><g filter="url(#iFP4qia)"><path class="wb48l8bax"/></g><g filter="url(#iV2d3Nc)"><path class="vlabv4blh"/><path fill="url(#iH69I2S)" class="hl491q5kv"/><path fill="url(#i8URase)" class="hl491q5kv"/></g><g filter="url(#iOjhasd)"><path class="axxgl4maj"/><path fill="url(#iu9t2Tc)" class="o1e1fbczi"/><path fill="url(#iRqifZc)" class="o1e1fbczi"/></g><path class="q7o4abbcz"/><path fill="url(#iroLcWd)" class="flb2_3bcn"/><path class="tnf4f2yph"/><g filter="url(#irxSylL)"><path class="htx_zobiw"/><path fill="url(#iolY8Dd)" class="jfdsvcc3i"/></g><g filter="url(#izhCWUc)"><path fill="url(#iGWba9c)" class="pso4j-j2f"/></g><path class="d2hwt11ib"/><path fill="url(#iyXTZOd)" class="e2wfisbyq"/><path class="womu5m2tb"/><g filter="url(#iirszEe)"><path fill="url(#inoKDkc)" class="q90x45tih"/></g><g filter="url(#i23wxie)"><ellipse transform="rotate(-27.914 13.626 9.862)" class="yihl2c0za"/><ellipse fill="url(#iIiLSxc)" transform="rotate(-27.914 13.626 9.862)" class="wapquzb_l"/></g><path fill="url(#irVnVmb)" class="q9svv-b6p"/><path fill="url(#idAUDGc)" class="q9svv-b6p"/><path fill="url(#ieEzREc)" class="q9svv-b6p"/><path fill="url(#iffM8wu)" class="q9svv-b6p"/><path fill="url(#icNp8pb)" class="wpp4l1brp"/><path fill="url(#i1BuAre)" class="wpp4l1brp"/><g filter="url(#iypcfad)"><path fill="url(#ihdtsDc)" class="z8zmupd2e"/></g><g filter="url(#iKJZ1Jb)"><path fill="url(#ibfNLLc)" class="ftvjsmnii"/></g><g filter="url(#iGpS2hb)"><path class="qv6mecccf"/></g><g filter="url(#ij30N2b)"><path class="azer_kdla"/></g><g filter="url(#i9ZZgkc)"><path class="komt4s4ni"/></g><g filter="url(#iBT17Yc)"><path fill="url(#ifIcSwe)" class="xi5qspoau"/><path fill="url(#ipFaLmi)" class="xi5qspoau"/></g><defs><radialGradient id="ias5dbb" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 26.988 6.878)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iK3EgBb" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.563 25.425)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="i6SaUXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.004 4.26)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="iFI394c" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16 15.894)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="i7uvnlc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.656 20.425)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iSTGFPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.718 19.02)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="im5jKee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 26.994 28.175)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="iu6xNxb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.458 29.723)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="ielxZLc" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 11.7969 15.188 20.237)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="ivnDH2n" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.23 19.384)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="izmNZkb" cx="0" cy="0" r="1" gradientTransform="rotate(-125.283 15.112 5.107)scale(1.63656 .29806)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="iuMOOod" cx="0" cy="0" r="1" gradientTransform="rotate(69.677 -2.804 21.111)scale(.94974 1.77776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iqElwIe" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.516 20.3)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="ivrcbmG" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 1 -1.87182 -.87742 14.031 16.409)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iyNxszc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.34375 -2.06 0 16.004 17.175)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="asdb3w9he"/><stop offset="1" class="zxm3y0btp"/></radialGradient><radialGradient id="ipKyHPj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.637 23.711)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="hkmqqzaeo"/><stop offset="1" class="vo92-0bqu"/></radialGradient><radialGradient id="imWU9ub" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.779 23.43)" gradientUnits="userSpaceOnUse"><stop class="wpeyy_b3b"/><stop offset="1" class="cs9siac0p"/></radialGradient><radialGradient id="inAtrvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.094 23.953)" gradientUnits="userSpaceOnUse"><stop class="jgy_mt60r"/><stop offset="1" class="esaylh6lg"/></radialGradient><radialGradient id="iCjaqgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.188 25.305)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="0" class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iQaPDme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.203 26.586)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iDORSHV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.25 27.868)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iw6Tx4X" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.32 29.227)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iWDJVQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.25 25.305)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="iFHEIUd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.188 26.586)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="i6qzuUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.094 27.868)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="ijYQWJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.953 29.227)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="ieLWGhe" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.925 20.88)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="inSpDXc" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 10.023 12.306)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="ixxJtmd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.887 10.874)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i3vAIQd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.59 8.166)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iEobh1b" cx="0" cy="0" r="1" gradientTransform="scale(10.9173 13.1832)rotate(90 .56 .917)" gradientUnits="userSpaceOnUse"><stop offset=".724" class="shd9u3byd"/><stop offset="1" class="go8nmeuel"/></radialGradient><radialGradient id="iLNKuMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.526 9.562)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iJ6dQyd" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.71 -2.11)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="igo8LKd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.512 11.863)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iB7rDsT" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.287 8.141)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="is0aE0c" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.19 13.822)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iYKlTdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.545 12.235)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="imAhLme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.662 11.666)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iC7tFmb" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.977 8.995)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="p1yo_4s7a"/><stop offset="1" class="a1wau6blr"/></radialGradient><radialGradient id="isNEhQe" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 15.588 14.498)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iSLvWzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.85 7.982)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iQadHPb" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.332 -6.31)scale(2.51513 4.45632)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iagIUpc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.186 3.016)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="ioTvREe" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 15.174 1.424)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iH69I2S" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.333 3.683)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i8URase" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.242 -5.847)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iu9t2Tc" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 18.713 7.497)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iRqifZc" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 17.827 6.02)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iroLcWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.261 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iolY8Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.033 10.042)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iyXTZOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.897 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iIiLSxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.61 10.178)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idAUDGc" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.697 9.973)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="ieEzREc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.057 10.517)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iffM8wu" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.171 10.69)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="i1BuAre" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.164 10.613)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="ihdtsDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.164 10.615)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="ipFaLmi" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.375 9.94)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><linearGradient id="itmQLCe" x1="11.819" x2="31.261" y1="4.549" y2="22.785" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="ii5su7d" x1="30.063" x2="9.125" y1="13.237" y2="13.237" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iB4bxce" x1="13.438" x2="31.25" y1="3.49" y2="24.302" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="iz9T9tc" x1="-4.906" x2="28.906" y1="25.581" y2="25.581" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iztQKHe" x1="3.094" x2="3.094" y1="5.143" y2="23.581" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="ikWBhLU" x1="25.174" x2="25.174" y1="30.394" y2="26.578" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="ie7NHCd" x1="22.406" x2="23.219" y1="29.206" y2="29.19" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iITrxGd" x1="7.134" x2="9.529" y1="28.087" y2="28.087" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="ibtUrKb" x1="18.054" x2="20.851" y1="18.315" y2="18.315" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iU98tmP" x1="13.944" x2="11.147" y1="18.315" y2="18.315" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="ip1ZRVS" x1="12.109" x2="12.672" y1="16.878" y2="17.096" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="ikSKZZb" x1="21.844" x2="17.469" y1="24.737" y2="24.737" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="i9bqxuc" x1="10.314" x2="10.742" y1="23.519" y2="23.519" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="ibMC3be" x1="12.5" x2="8.563" y1="27.956" y2="27.956" gradientUnits="userSpaceOnUse"><stop class="y7rb0nbsx"/><stop offset="1" class="j4pe32lse"/></linearGradient><linearGradient id="itMHp2d" x1="22.469" x2="18.654" y1="27.55" y2="27.55" gradientUnits="userSpaceOnUse"><stop class="c1fnikbua"/><stop offset=".807" class="y9fu8v2us"/></linearGradient><linearGradient id="iSilWDb" x1="10.781" x2="21.654" y1="21.893" y2="21.893" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="ilaXOtc" x1="16.401" x2="16.401" y1="20.956" y2="22.128" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="ijkCG0c" x1="19.023" x2="20.852" y1="26.058" y2="26.058" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="iwEKOpb" x1="12.932" x2="10.734" y1="26.058" y2="26.058" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="ivQIRgd" x1="19.023" x2="20.852" y1="27.323" y2="27.323" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="ixytWOb" x1="12.932" x2="10.734" y1="27.323" y2="27.323" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="iwHeyxe" x1="19.023" x2="20.852" y1="28.589" y2="28.589" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="i1PCAEp" x1="12.932" x2="10.734" y1="28.589" y2="28.589" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="iydxg5d" x1="21.236" x2="18.707" y1="12.56" y2="12.56" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iJ12CJz" x1="16.917" x2="16.079" y1="11.549" y2="11.584" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="i46596b" x1="16.079" x2="16.079" y1="12.689" y2="12.224" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iy3LhEc" x1="16.079" x2="16.079" y1="9.983" y2="10.53" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iBNuohe" x1="16.495" x2="16.495" y1="12.826" y2="12.634" gradientUnits="userSpaceOnUse"><stop class="a1wau6blr"/><stop offset="1" class="p1yo_4s7a"/></linearGradient><linearGradient id="iVor7Ds" x1="14.877" x2="15.196" y1="14.259" y2="13.425" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iBWZkMb" x1="22.931" x2="11.319" y1="5.212" y2="5.212" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iGWba9c" x1="19.039" x2="18.725" y1="10.012" y2="10.206" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inoKDkc" x1="14.641" x2="14.327" y1="10.012" y2="10.205" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irVnVmb" x1="22.515" x2="21.309" y1="10.039" y2="12.216" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="icNp8pb" x1="10.229" x2="11.688" y1="10.743" y2="10.616" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="ibfNLLc" x1="21.495" x2="21.495" y1="9.657" y2="11.561" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="ifIcSwe" x1="16.08" x2="16.08" y1="8.836" y2="12.618" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient><filter id="i5DHQWN" width="27.98" height="21.09" x="2.004" y="3.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="iEP2Wxd" width="27.413" height="20.785" x="2.669" y="3.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".2"/></filter><filter id="iFeuJzb" width="27.91" height="20.96" x="2.004" y="3.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="iZSkhec" width="2.797" height="14.04" x="18.054" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="iwwtR2d" width="2.797" height="14.04" x="11.147" y="15.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="i59qYuc" width="2.1" height="3.39" x="20.948" y="23.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.478431 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="iP55AKd" width="2.1" height="3.29" x="8.951" y="23.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.368627 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="itVgEBb" width="4.793" height="5.391" x="8.951" y="24.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.380392 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="icTn5kb" width="4.793" height="5.591" x="18.454" y="24.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.196078 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1658" result="effect2_innerShadow_4002_1658"/></filter><filter id="i1pXNmd" width="2.222" height=".3" x="18.873" y="25.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="iupPcje" width="2.222" height=".3" x="10.861" y="25.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="inJbCge" width="2.222" height=".3" x="18.873" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="i5Ardgb" width="2.222" height=".3" x="10.861" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="iRisifd" width="2.222" height=".3" x="18.873" y="28.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="is20Zzd" width="2.222" height=".3" x="10.861" y="28.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="ijeRKEd" width="11.22" height="12.542" x="11.016" y="4.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1658" result="effect2_innerShadow_4002_1658"/></filter><filter id="i5eBdhe" width="3.747" height="4.9" x="14.064" y="9.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".5"/></filter><filter id="iTeBLOe" width="2.277" height="3.3" x="14.941" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".1"/></filter><filter id="ifpZppe" width="3.718" height="1.573" x="14.22" y="13.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="iPGBzXS" width="12.873" height="8.356" x="9.643" y="1.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1658" result="effect2_innerShadow_4002_1658"/></filter><filter id="iNitIRj" width="2.339" height="1.19" x="17.668" y="7.191" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="iFP4qia" width="2.339" height="1.176" x="12.412" y="7.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/></filter><filter id="iV2d3Nc" width="6.584" height="5.992" x="9.998" y="2.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/><feGaussianBlur result="effect2_foregroundBlur_4002_1658" stdDeviation=".125"/></filter><filter id="iOjhasd" width="6.319" height="5.711" x="15.92" y="3.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".125"/></filter><filter id="irxSylL" width=".787" height=".696" x="17.527" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="izhCWUc" width=".891" height=".913" x="18.367" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".1"/></filter><filter id="iirszEe" width=".986" height="1.04" x="13.924" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".1"/></filter><filter id="i23wxie" width=".913" height=".705" x="13.169" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".05"/></filter><filter id="iypcfad" width="1.329" height="2.379" x="9.998" y="9.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".125"/></filter><filter id="iKJZ1Jb" width="1.947" height="2.903" x="20.522" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".25"/></filter><filter id="iGpS2hb" width="2.405" height="1.16" x="12.331" y="7.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".125"/></filter><filter id="ij30N2b" width="2.405" height="1.16" x="17.61" y="7.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".125"/></filter><filter id="i9ZZgkc" width="5.266" height="3.005" x="16.959" y="3.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1658" stdDeviation=".375"/></filter><filter id="iBT17Yc" width="10.29" height="4.16" x="10.884" y="8.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1658"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1658" result="effect2_innerShadow_4002_1658"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:teacher-medium-dark" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a1wau6blr {
  stop-color: var(--svg-color--6d3945, #6D3945);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.aoqe_ob0o {
  d: path("M20.934 4.232c.514.177.976.536 1.268 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.078-1.606a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.446a2.35 2.35 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.193 0c.282-.118.59-.188.913-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.asdb3w9he {
  stop-color: var(--svg-color--533, #533);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.axxgl4maj {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.292 8.526l-.03-.632c-.01-.763-.64-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.672-1.706 1.65-1.488c.94.209 2.005.558 2.816 1.087c1.744 1.138 1.531 3.12.613 4.086");
}

.azer_kdla {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.64 8.02c-.257-.185-.897-.51-1.655-.382");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bo19xjbxf {
  d: path("M22.048 23.048c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c1fnikbua {
  stop-color: var(--svg-color--997266, #997266);
}

.c1vp4vb9v {
  d: path("M18.054 16.76h-4.11v13.18h4.11z");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cctkm_bfn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 25.98h-1.921");
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr9drwbam {
  stop-color: var(--svg-color--9a7469, #9A7469);
  stop-opacity: 0;
}

.cs9siac0p {
  stop-color: var(--svg-color--9c7c74, #9C7C74);
  stop-opacity: 0;
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.d2hwt11ib {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.688 9.21c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.dcd-_dbuf {
  d: path("M16.004 15.44c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dincvfsjc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 27.245h-1.921");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dyohud76n {
  d: path("M28.994 23.93H3.004V4.94l-.92-.68c-.05.09-.08.2-.08.3V24.3c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e2wfisbyq {
  d: path("M13.895 9.481a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.enkk5hp0q {
  d: path("M11.147 21.432c0-.384.312-.695.696-.695h9.811v1.39h-9.811a.695.695 0 0 1-.696-.695");
}

.eo578gbro {
  stop-color: var(--svg-color--9c7b74, #9C7B74);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.esaylh6lg {
  stop-color: var(--svg-color--684844, #684844);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.f6iqo0uxc {
  d: path("m19.344 16l1.36 2.929c.09.19-.05.41-.26.41l-.963-.266c-.422-.105-.437.277-.277.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V16z");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.flb2_3bcn {
  d: path("M18.263 9.481a.892.892 0 0 1 .86 1.128H17.4a.896.896 0 0 1 .864-1.128");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.ft5dv1b6b {
  fill: none;
}

.ftauhbbbu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 25.98h1.922");
}

.ftvjsmnii {
  d: path("M21.022 11.56q.059-.95.11-1.903a.955.955 0 0 1-.11 1.904");
}

.g_4twtygr {
  d: path("M3.004 23.93V4.94h25.99v18.99z");
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.ghazelbak {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.219 4.334H29.43a.1.1 0 0 1 .1.1v19.585");
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.go8nmeuel {
  stop-color: var(--svg-color--542e2b, #542E2B);
}

.gom2jbmdj {
  stop-color: var(--svg-color--643037, #643037);
  stop-opacity: 0;
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjkt_qaxp {
  d: path("M20.94 12.124c.336-.01.65-.124.905-.308v.93c0 .894-.532 1.69-1.34 2.02q.257-.546.345-1.18z");
}

.hkmqqzaeo {
  stop-color: var(--svg-color--8b625a, #8B625A);
}

.hl491q5kv {
  d: path("m16.312 5.259l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.098.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.893v1.484z");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.htx_zobiw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.198 9.67c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.j4pe32lse {
  stop-color: var(--svg-color--744c4b, #744C4B);
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jeq1ehfie {
  d: path("M22.674 29.94V17.696a10.98 10.98 0 0 1 4.32 8.744v3.5z");
}

.jfdsvcc3i {
  d: path("M18.198 9.67c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.jgy_mt60r {
  stop-color: var(--svg-color--512a20, #512A20);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jl9r0cbox {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.728 13.376a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.297-.352 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.35.32c-.497 0-.962-.117-1.352-.32Z");
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kj_qkabkk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 28.51h1.922");
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kn1yo7csr {
  stop-color: var(--svg-color--643037, #643037);
}

.komt4s4ni {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.272 5.214h-2.08a.483.483 0 1 1 .076-.96c.54.085 1.257.205 1.737.324c1.086.27 1.386.798 1.47 1.175a1.51 1.51 0 0 0-1.203-.539");
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.kst27wbry {
  d: path("M16.08 13.771c-.508 0-.985-.12-1.386-.328c-.137-.07-.285.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.583-.846c.087-.13-.06-.28-.197-.21c-.401.21-.873.329-1.386.329");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mqp55hb8m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.932 28.51h-1.921");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.npqz14brf {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.697 10.16l-.532 1.838c-.108.378.152.757.521.757h.786c.37 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.o1e1fbczi {
  d: path("m21.292 8.526l-.03-.632c-.01-.763-.64-1.393-1.405-1.425h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.672-1.706 1.65-1.488c.94.209 2.005.558 2.816 1.087c1.744 1.138 1.531 3.12.613 4.086");
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.oh-_iua0g {
  stop-color: var(--svg-color--7a4f45, #7A4F45);
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.owl7p83et {
  stop-color: var(--svg-color--7a4f45, #7A4F45);
  stop-opacity: 0;
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p1yo_4s7a {
  stop-color: var(--svg-color--6d3945, #6D3945);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p6_wkpbgg {
  d: path("M21.654 22.925v-2.286c0-.388-.36-.699-.81-.699h-8.658c-1.042 0-1.872.73-1.872 1.622c0 .752.61 1.363 1.363 1.363z");
}

.pd7tuhb7r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.023 27.245h1.922");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pso4j-j2f {
  d: path("M19.058 10.256a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.pwoqj7b-i {
  fill-rule: evenodd;
  d: path("M12.408 29.94v-8.406h-2.094v8.406z");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q7o4abbcz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.47 9.21c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.q90x45tih {
  d: path("M14.71 10.269c0-.289-.234-.48-.297-.539l-.289.279l.178.361z");
}

.q9svv-b6p {
  d: path("M21.001 12.216q.1-1.597.185-3.192A1.61 1.61 0 0 1 21 12.216");
}

.qh4cj-bzx {
  d: path("M9.95 23.04c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qv6mecccf {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.706 8.065c.257-.184.898-.508 1.655-.38");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rgbpayb4r {
  d: path("M18.655 25.31a.81.81 0 0 0 .302.667a.8.8 0 0 0-.302.637c0 .267.115.503.302.636a.8.8 0 0 0-.302.637c0 .267.115.503.302.636a.84.84 0 0 0-.302.668c.009.42.32.75.684.75h2.935c.427 0 .774-.401.774-.894v-3.604c0-.493-.347-.893-.774-.893h-2.842c-.475 0-.77.39-.777.76");
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.rxom98b9a {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.678 10.356l-.591 1.838c-.101.378.141.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.838c-.106-.408-.504-.408-.615 0");
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.scfwrvpyt {
  d: path("M9.294 29.94V17.696a10.98 10.98 0 0 0-4.32 8.744v3.5z");
}

.sf5a9or-k {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.408 29.94v-8.406h-2.094v8.406z");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.shd9u3byd {
  stop-color: var(--svg-color--6d4346, #6D4346);
  stop-opacity: 0;
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tjew41unp {
  d: path("m15.697 10.16l-.532 1.838c-.108.378.152.757.521.757h.786c.37 0 .63-.384.52-.757l-.53-1.838c-.114-.407-.646-.407-.765 0");
}

.tnf4f2yph {
  fill: var(--svg-color--000, #000);
  d: path("M17.752 10.374c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tx8zphbjg {
  d: path("M13.344 25.31a.81.81 0 0 1-.303.667a.8.8 0 0 1 .303.637a.77.77 0 0 1-.303.636a.8.8 0 0 1 .303.637a.77.77 0 0 1-.303.636c.187.144.303.39.303.668c-.01.42-.32.75-.685.75H9.724c-.426 0-.773-.401-.773-.894v-3.604c0-.493.347-.893.773-.893h2.842c.475 0 .77.39.778.76");
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u9ogn5shy {
  stop-color: var(--svg-color--967973, #967973);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ud7n83bkt {
  stop-color: var(--svg-color--815f55, #815F55);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uo5n0hbpd {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.812 7.895a1.85 1.85 0 0 0-.687-.412c-.305-.095-.686-.121-1.213-.057a.277.277 0 0 0 .067.551c.482-.059.776-.028.979.035c.198.063.332.164.49.301a.277.277 0 0 0 .364-.418");
}

.upqd-mb8f {
  d: path("M10.314 21.82v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vlabv4blh {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.312 5.259l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.805-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.098.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.893v1.484z");
}

.vo92-0bqu {
  stop-color: var(--svg-color--724838, #724838);
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wapquzb_l {
  cx: 13.626px;
  cy: 9.862px;
  rx: 0.39px;
  ry: 0.197px;
}

.wb48l8bax {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.668 7.786a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.067.55a2.22 2.22 0 0 0-1.387.286a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.439z");
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.womu5m2tb {
  fill: var(--svg-color--000, #000);
  d: path("M14.406 10.374a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wpeyy_b3b {
  stop-color: var(--svg-color--9c7c74, #9C7C74);
}

.wpp4l1brp {
  d: path("M11.035 9.011a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.56 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.wxyv0wdsu {
  d: path("M29.374 24.93H2.624c-.34 0-.62-.28-.62-.62V4.56c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62V24.3a.61.61 0 0 1-.61.63");
}

.wy_1bzklb {
  d: path("M16.004 18.61c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xi5qspoau {
  d: path("M20.834 8.43h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91V9.37c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.y0_-ccbls {
  d: path("M11.254 13.64a3.916 3.916 0 0 0 3.886 3.405h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.237-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.556");
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7rb0nbsx {
  stop-color: var(--svg-color--895b5e, #895B5E);
}

.y9fu8v2us {
  stop-color: var(--svg-color--6f4446, #6F4446);
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.yez5xuaez {
  d: path("m12.654 16l-1.36 2.929c-.09.19.05.41.26.41l.964-.266c.422-.105.436.277.276.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V16z");
}

.yihl2c0za {
  cx: 13.626px;
  cy: 9.862px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.yldjwvbde {
  d: path("M11.218 12.124a1.64 1.64 0 0 1-.905-.308v.93c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z8zmupd2e {
  d: path("M10.994 9.676a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zxm3y0btp {
  stop-color: var(--svg-color--3e201c, #3E201C);
}

</style>
