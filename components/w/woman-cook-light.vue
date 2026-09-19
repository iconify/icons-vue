<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iaUgyAd)"><path fill="url(#iJnbTwb)" class="y24-vkbxu"/><path fill="url(#idEwGIb)" class="y24-vkbxu"/><path fill="url(#iUf81tD)" class="y24-vkbxu"/><path fill="url(#i6fiE5b)" class="y24-vkbxu"/><path fill="url(#ifYEuYd)" class="y24-vkbxu"/></g><g filter="url(#ipzIe9c)"><path fill="url(#iq2lYMm)" class="aa24lzhrl"/><path fill="url(#ipQcfkb)" class="aa24lzhrl"/></g><g filter="url(#iljUyOd)"><path fill="url(#ib0mRec)" class="j0ps6nvlv"/></g><g filter="url(#iyScbGc)"><path class="kbfsu5g-s"/></g><g filter="url(#i8fOYib)"><path class="lum4j-j2u"/><path fill="url(#i1uTs2d)" class="vdg1_vfpt"/></g><path class="zu-galbrx"/><path fill="url(#iLmL0AV)" class="qa91z0bhj"/><path fill="url(#ilZk6zb)" class="z75iesbgx"/><path fill="url(#isvZBGd)" class="z75iesbgx"/><path fill="url(#itBtopd)" class="eykyay15h"/><path fill="url(#iu4qsCh)" class="eykyay15h"/><path fill="url(#id8oCee)" class="eykyay15h"/><path fill="url(#i0S3hse)" class="eykyay15h"/><g filter="url(#iQA1Fad)"><path fill="url(#iSSMFHl)" class="s_1n4rb1u"/><path fill="url(#i5tTSod)" class="s_1n4rb1u"/></g><path fill="url(#iNq8HKe)" class="s_1n4rb1u"/><path fill="url(#iYuSKed)" class="s_1n4rb1u"/><g filter="url(#itgaprb)"><path fill="url(#izJWrWb)" class="zzbaevt2c"/></g><path fill="url(#i3szKUo)" class="fzc_bdcjb"/><path fill="url(#iwVHLcc)" class="fzc_bdcjb"/><g filter="url(#iYwpD7d)"><path class="s4d6j7b7p"/></g><g filter="url(#i8i5yvC)"><path class="yiwn4_bdv"/></g><g filter="url(#issEhNc)"><path class="xauyjcckd"/></g><g filter="url(#iXseTbd)"><path fill="url(#i3vUpCc)" class="jn1ik_bct"/></g><g filter="url(#iMpYs2d)"><path fill="url(#iZFOzIe)" class="d7puktbmy"/></g><g filter="url(#iqvM49b)"><path fill="url(#iJKvoqc)" class="hd20xvb3l"/></g><path fill="url(#iV6hQDc)" class="fi-xuqber"/><path fill="url(#iymTYEe)" class="fi-xuqber"/><path fill="url(#iGMFk3d)" class="b3bslduol"/><path fill="url(#i2Pbfue)" class="b3bslduol"/><path fill="url(#ivK0e0b)" class="b3bslduol"/><path fill="url(#ik4WMRc)" class="zs8rr9bpw"/><path fill="url(#i69URve)" class="zs8rr9bpw"/><path fill="url(#i7MVeec)" class="zs8rr9bpw"/><path fill="url(#iUcxMCe)" class="zs8rr9bpw"/><g filter="url(#iZQ08uc)"><path fill="url(#iGNbrac)" class="ew3-w3ohh"/></g><g filter="url(#itDZexe)"><path class="li84xjbbs"/><path fill="url(#iDWr8kd)" class="elromo-up"/></g><g filter="url(#iEluNie)"><ellipse fill="url(#iJU5a3d)" class="o7lclgw6d"/></g><g filter="url(#iTWXYqb)"><path fill="url(#iJL2URb)" class="q2tim8bhp"/><path fill="url(#i1dclve)" class="q2tim8bhp"/><path fill="url(#i2L2jxe)" class="q2tim8bhp"/><path fill="url(#iQ9v7Sc)" class="q2tim8bhp"/><path fill="url(#im7ntpd)" class="q2tim8bhp"/></g><path fill="url(#iJjNUto)" class="q2tim8bhp"/><g filter="url(#iWa87Me)"><path stroke="url(#i2sLPnd)" class="in19etb1c"/></g><g filter="url(#iOTrAje)"><path stroke="url(#iKpDKHb)" class="r2xqv839x"/></g><g filter="url(#i8y1b9b)"><path stroke="url(#i0bvyib)" class="kxeosqc-h"/></g><g filter="url(#i49v60d)"><path fill="url(#i0b1Amc)" class="b5--a89ix"/><path fill="url(#iySfqSB)" class="b5--a89ix"/><path fill="url(#iYg3Y0b)" class="b5--a89ix"/><path fill="url(#iN5r79b)" class="b5--a89ix"/><path fill="url(#iEbk7gd)" class="b5--a89ix"/><path fill="url(#ixugRCe)" class="b5--a89ix"/><path fill="url(#i5VqYke)" class="b5--a89ix"/></g><path fill="url(#ihCA5Rw)" class="b5--a89ix"/><path fill="url(#iYWcpbd)" class="b5--a89ix"/><path fill="url(#i0O3oob)" class="b5--a89ix"/><g filter="url(#iPRKi7d)"><path class="uohixqbkv"/></g><g filter="url(#iMHvUMb)"><path class="au5_neo1k"/><path fill="url(#izd2Qvc)" class="pvaqnwbug"/><path fill="url(#izoIYDT)" class="pvaqnwbug"/><path fill="url(#iAtV7Ub)" class="pvaqnwbug"/><path fill="url(#iXtAW7c)" class="pvaqnwbug"/></g><path stroke="url(#ibqRG1i)" class="o8i5tyo6h"/><g filter="url(#ii0t5Ed)"><path class="l97x9nxki"/></g><g filter="url(#iFyfXzc)"><path class="ze352u2px"/></g><g filter="url(#iO7rxPb)"><path class="cttowni_l"/></g><g filter="url(#ilIuL5c)"><path class="imzv_hbah"/></g><g filter="url(#iojmmud)"><path fill="url(#ir8A6Fc)" class="z46q0-jev"/><path fill="url(#iOF8Ddd)" class="z46q0-jev"/><path fill="url(#iLmSXEc)" class="z46q0-jev"/></g><path fill="url(#ikzUvvd)" class="o_dy4cctk"/><path fill="url(#iKKjorc)" class="o_dy4cctk"/><g filter="url(#i2bRiHc)"><path fill="url(#i81RRuc)" class="txy846j_u"/></g><g filter="url(#iVx9Jpd)"><path fill="url(#i0OFHZd)" class="er1lz4bqk"/></g><g filter="url(#iZc4NJc)"><path fill="url(#itcsnSN)" class="d3so7-bzn"/></g><g filter="url(#i0LDTfb)"><path class="m9a6yfj-g"/></g><g filter="url(#iivc7pe)"><path class="dh53m4b-h"/></g><path class="c484l0bau"/><path fill="url(#imwvGqe)" class="okyhtm__h"/><path class="mtbd7jb1u"/><g filter="url(#i8kdRBb)"><path class="cmm4esboy"/><path fill="url(#i7GGeqe)" class="lrdvsibwx"/></g><g filter="url(#in4OQ1c)"><path fill="url(#iV5RPUx)" class="cv_2ldbfl"/></g><path class="grjae5nbo"/><path fill="url(#iUY5Zsd)" class="p-uvmjboo"/><path class="wowq8qbva"/><g filter="url(#is322Zd)"><path fill="url(#in84Cqb)" class="vz20cubfv"/></g><g filter="url(#i6OaYWy)"><ellipse transform="rotate(-27.914 13.651 9.99)" class="a9ytwe1ac"/><ellipse fill="url(#iIboSuM)" transform="rotate(-27.914 13.651 9.99)" class="u2ledhn4b"/></g><defs><radialGradient id="idEwGIb" cx="0" cy="0" r="1" gradientTransform="rotate(140.889 3.873 5.344)scale(4.24611 1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="yd_laccri"/><stop offset="1" class="dmf0acl5m"/></radialGradient><radialGradient id="iUf81tD" cx="0" cy="0" r="1" gradientTransform="matrix(2.11985 0 0 3.47579 20.286 7.724)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="w9txrw6kc"/><stop offset="1" class="h-4ghpb7u"/></radialGradient><radialGradient id="i6fiE5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90841 -5.85233 0 14.832 12.68)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="dc6jrkblm"/><stop offset="1" class="oy6n6fbyn"/></radialGradient><radialGradient id="ifYEuYd" cx="0" cy="0" r="1" gradientTransform="rotate(117.05 7.896 13.582)scale(2.23819 1.04512)" gradientUnits="userSpaceOnUse"><stop class="jsa0_reur"/><stop offset="1" class="j1xr6ccfb"/></radialGradient><radialGradient id="iq2lYMm" cx="0" cy="0" r="1" gradientTransform="matrix(.85975 -2.01949 1.7878 .76112 21.634 11.6)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="ipQcfkb" cx="0" cy="0" r="1" gradientTransform="matrix(.61918 .73134 -.23906 .2024 21.898 8.965)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i1uTs2d" cx="0" cy="0" r="1" gradientTransform="matrix(.66527 -.09951 .15385 1.02855 21.347 10.724)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iLmL0AV" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.513 58.665)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="isvZBGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 24.142 30.21)" gradientUnits="userSpaceOnUse"><stop class="kz1-kyj0l"/><stop offset="1" class="d9a-s9bqe"/></radialGradient><radialGradient id="id8oCee" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.583 30.713)" gradientUnits="userSpaceOnUse"><stop class="tb19eccqx"/><stop offset="1" class="b3_m6tbiu"/></radialGradient><radialGradient id="i0S3hse" cx="0" cy="0" r="1" gradientTransform="matrix(-4.94559 0 0 -18.6532 9.67 29.424)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="blny5fbqc"/><stop offset="1" class="ql78zhb7e"/></radialGradient><radialGradient id="iSSMFHl" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 21.184 19.685)" gradientUnits="userSpaceOnUse"><stop class="m6lhrcc1m"/><stop offset="1" class="hm5-ozbqx"/></radialGradient><radialGradient id="i5tTSod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.848 32.457)" gradientUnits="userSpaceOnUse"><stop class="fg0e2bc1h"/><stop offset="1" class="qk3h5tshn"/></radialGradient><radialGradient id="iNq8HKe" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.276 16.329)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="i3szKUo" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 9.222 10.147)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iwVHLcc" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.831 8.65)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="arr7-5bxc"/><stop offset="1" class="mejh1wbdq"/></radialGradient><radialGradient id="iV6hQDc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13534 1.02198 -1.00268 -2.09502 28.617 23.99)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="iymTYEe" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 27.844 23.545)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iGMFk3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 15.317 19.291)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="i2Pbfue" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.677 18.166)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="ivK0e0b" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.787 20.463)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="ik4WMRc" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.654 18.582)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="i7MVeec" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 16.207 18.885)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="iUcxMCe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 19.145 21.291)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="iDWr8kd" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.925 11.3)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="via-_dbpm"/><stop offset="1" class="bt1_2zb2r"/></radialGradient><radialGradient id="iJU5a3d" cx="0" cy="0" r="1" gradientTransform="matrix(2.27907 0 0 3.27907 24.876 17.9)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="uelaalb7d"/><stop offset=".746" class="i5m4wsx9z"/></radialGradient><radialGradient id="i1dclve" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.199 25.282)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i2L2jxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.199 26.577)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iQ9v7Sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.199 27.827)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="im7ntpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.199 29.178)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iJjNUto" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 0 0 -6.625 28.938 27.655)" gradientUnits="userSpaceOnUse"><stop class="ae5vg5b9k"/><stop offset="1" class="vma3fs41g"/></radialGradient><radialGradient id="i0b1Amc" cx="0" cy="0" r="1" gradientTransform="rotate(155.407 8.463 7.08)scale(7.36936 9.81575)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iySfqSB" cx="0" cy="0" r="1" gradientTransform="rotate(172.628 9.388 6.323)scale(3.59587 3.94056)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iYg3Y0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.34704 -3.87384 4.94418 1.71923 13.706 17.49)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iN5r79b" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.87695 -9.84607 0 16.159 9.774)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="s6s8s0_ew"/><stop offset="1" class="xqxkuobqn"/></radialGradient><radialGradient id="iEbk7gd" cx="0" cy="0" r="1" gradientTransform="rotate(168.978 8.444 6.752)scale(7.24885 12.394)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="ixugRCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17683 1.45515 0 18.53 9.568)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="i5VqYke" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34224 1.54986 0 14.02 9.334)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ihCA5Rw" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32427 0 0 -6.59153 21.409 11.089)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iYWcpbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.35228 4.0906 -7.16936 2.37007 13.907 3.861)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="i0O3oob" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.46875 -8.78357 0 16.159 7.123)" gradientUnits="userSpaceOnUse"><stop class="rbgr_ib3q"/><stop offset="1" class="ro1b8p4mm"/></radialGradient><radialGradient id="izd2Qvc" cx="0" cy="0" r="1" gradientTransform="rotate(-101.645 13.303 -.92)scale(2.25681 .64762)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iXtAW7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.23563 16.65 12.152)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="ir8A6Fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.989 6.057)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ozh-gwb3b"/><stop offset="1" class="rq63c9eso"/></radialGradient><radialGradient id="iOF8Ddd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.801 2.9)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="iLmSXEc" cx="0" cy="0" r="1" gradientTransform="matrix(2.67803 0 0 3.53252 8.765 4.002)" gradientUnits="userSpaceOnUse"><stop class="cxaqe9bxy"/><stop offset="1" class="p0efopw-a"/></radialGradient><radialGradient id="ikzUvvd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.75 8.9809 -.10205 19.27 7.111)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="ox62rwbrf"/><stop offset="1" class="g4wbwbcoe"/></radialGradient><radialGradient id="imwvGqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.286 10.085)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i7GGeqe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.52 .663)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUY5Zsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.922 10.086)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iIboSuM" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.636 10.304)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iaUgyAd" width="15.95" height="13.5" x="7.784" y="4.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.101961 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.337255 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1887" result="effect2_innerShadow_4002_1887"/></filter><filter id="ipzIe9c" width="1.514" height="3.441" x="21.026" y="8.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="iljUyOd" width="1.671" height="3.2" x="9.668" y="9.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="iyScbGc" width="1.629" height="2.679" x="9.922" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".2"/></filter><filter id="i8fOYib" width="1.947" height="2.903" x="20.566" y="9.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".25"/></filter><filter id="iQA1Fad" width="14.3" height="12.3" x="8.829" y="18.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="itgaprb" width="6.538" height="5.771" x="12.472" y="16.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".325"/></filter><filter id="iYwpD7d" width="2.5" height="2.5" x="18.92" y="27.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".25"/></filter><filter id="i8i5yvC" width="2.5" height="2.5" x="18.92" y="23.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".25"/></filter><filter id="issEhNc" width="2.5" height="2.5" x="18.92" y="19.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".25"/></filter><filter id="iXseTbd" width="1.7" height="1.7" x="19.59" y="27.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1887" result="effect2_innerShadow_4002_1887"/></filter><filter id="iMpYs2d" width="1.7" height="1.7" x="19.59" y="23.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1887" result="effect2_innerShadow_4002_1887"/></filter><filter id="iqvM49b" width="1.7" height="1.7" x="19.59" y="20.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1887" result="effect2_innerShadow_4002_1887"/></filter><filter id="iZQ08uc" width="2.238" height="1.809" x="14.98" y="17.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1887" result="effect2_innerShadow_4002_1887"/></filter><filter id="itDZexe" width="5.047" height="11.336" x="23.532" y="14.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.521569 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="iEluNie" width="3.672" height="4.703" x="23.995" y="15.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.647059 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/><feGaussianBlur result="effect2_foregroundBlur_4002_1887" stdDeviation=".05"/></filter><filter id="iTWXYqb" width="4.468" height="5.556" x="23.762" y="24.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="iWa87Me" width="2.097" height=".3" x="24.132" y="25.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".05"/></filter><filter id="iOTrAje" width="2.097" height=".3" x="24.053" y="27.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".05"/></filter><filter id="i8y1b9b" width="2.097" height=".3" x="24.132" y="28.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".05"/></filter><filter id="i49v60d" width="10.5" height="11.523" x="10.909" y="5.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="iPRKi7d" width="2.877" height="3.9" x="14.459" y="9.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".25"/></filter><filter id="iMHvUMb" width="2.377" height="3.4" x="14.916" y="9.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".125"/></filter><filter id="ii0t5Ed" width="2.439" height="1.19" x="17.694" y="7.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="iFyfXzc" width="2.439" height="1.176" x="12.437" y="7.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="iO7rxPb" width="2.255" height=".979" x="12.431" y="7.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".1"/></filter><filter id="ilIuL5c" width="2.255" height=".987" x="17.71" y="7.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".1"/></filter><filter id="iojmmud" width="14.779" height="5.543" x="8.765" y="2.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="i2bRiHc" width=".675" height="2.047" x="13.012" y="3.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".05"/></filter><filter id="iVx9Jpd" width=".675" height="2.047" x="18.6" y="3.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".05"/></filter><filter id="iZc4NJc" width=".98" height="2.537" x="15.669" y="3.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".1"/></filter><filter id="i0LDTfb" width="2.611" height="1.227" x="17.394" y="9.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="iivc7pe" width="2.611" height="1.227" x="12.206" y="9.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1887"/></filter><filter id="i8kdRBb" width=".787" height=".696" x="17.552" y="9.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".05"/></filter><filter id="in4OQ1c" width=".891" height=".913" x="18.392" y="9.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".1"/></filter><filter id="is322Zd" width=".986" height="1.04" x="13.949" y="9.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".1"/></filter><filter id="i6OaYWy" width=".913" height=".705" x="13.194" y="9.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1887" stdDeviation=".05"/></filter><linearGradient id="iJnbTwb" x1="22.488" x2="15.005" y1="6.496" y2="18.694" gradientUnits="userSpaceOnUse"><stop class="cd2w3_-kd"/><stop offset=".862" class="cl0gv76ti"/></linearGradient><linearGradient id="ib0mRec" x1="9.668" x2="12.031" y1="10.714" y2="10.714" gradientUnits="userSpaceOnUse"><stop offset=".246" class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="ilZk6zb" x1="23.287" x2="26.53" y1="25.875" y2="25.875" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="itBtopd" x1="8.27" x2="8.27" y1="30.994" y2="16.932" gradientUnits="userSpaceOnUse"><stop class="l0qpfdqgo"/><stop offset="1" class="i1-orb7ke"/></linearGradient><linearGradient id="iu4qsCh" x1="9.129" x2="8.551" y1="26.619" y2="26.619" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iYuSKed" x1="9.129" x2="13.066" y1="27.206" y2="27.206" gradientUnits="userSpaceOnUse"><stop class="fj7z_vbcj"/><stop offset="1" class="zab3c9ypw"/></linearGradient><linearGradient id="izJWrWb" x1="16.738" x2="13.777" y1="22.125" y2="18.741" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="i3vUpCc" x1="20.958" x2="19.689" y1="27.639" y2="29.046" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iZFOzIe" x1="20.958" x2="19.689" y1="23.999" y2="25.405" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iJKvoqc" x1="20.958" x2="19.689" y1="20.369" y2="21.776" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="i69URve" x1="16.833" x2="17.817" y1="17.994" y2="19.166" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="iGNbrac" x1="16.348" x2="16.348" y1="18.885" y2="17.446" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="iJL2URb" x1="27.79" x2="23.762" y1="28.04" y2="28.04" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="i2sLPnd" x1="24.282" x2="25.991" y1="26.033" y2="26.033" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iKpDKHb" x1="24.203" x2="25.913" y1="27.338" y2="27.338" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i0bvyib" x1="24.282" x2="25.991" y1="28.643" y2="28.643" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="izoIYDT" x1="15.166" x2="16.104" y1="12.002" y2="12.002" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iAtV7Ub" x1="16.104" x2="16.104" y1="12.866" y2="12.206" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="ibqRG1i" x1="15.067" x2="15.502" y1="14.382" y2="13.694" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iKKjorc" x1="16.739" x2="16.739" y1="7.776" y2="7.088" gradientUnits="userSpaceOnUse"><stop class="gjkvqmbnm"/><stop offset="1" class="f1s8bobxq"/></linearGradient><linearGradient id="i81RRuc" x1="13.485" x2="12.907" y1="5.628" y2="5.53" gradientUnits="userSpaceOnUse"><stop offset=".297" class="u7axe2baw"/><stop offset="1" class="dv8o3t25w"/></linearGradient><linearGradient id="i0OFHZd" x1="19.127" x2="18.494" y1="5.437" y2="5.53" gradientUnits="userSpaceOnUse"><stop offset=".246" class="ahul9kboj"/><stop offset="1" class="ongktybvd"/></linearGradient><linearGradient id="itcsnSN" x1="16.448" x2="16.448" y1="5.773" y2="3.745" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ztvu2mbem"/><stop offset="1" class="bm3jemb-u"/></linearGradient><linearGradient id="iV5RPUx" x1="19.064" x2="18.751" y1="10.14" y2="10.333" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="in84Cqb" x1="14.666" x2="14.352" y1="10.139" y2="10.333" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-cook-light" /></template>
<style>
.a9ytwe1ac {
  cx: 13.651px;
  cy: 9.99px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.aa24lzhrl {
  d: path("M21.026 12.227q.1-1.596.185-3.19a1.61 1.61 0 0 1-.185 3.19");
}

.ae5vg5b9k {
  stop-color: var(--svg-color--ffdac1, #FFDAC1);
}

.ahul9kboj {
  stop-color: var(--svg-color--a499b2, #A499B2);
}

.arr7-5bxc {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au5_neo1k {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.722 10.172l-.531 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b3_m6tbiu {
  stop-color: var(--svg-color--b8a4be, #B8A4BE);
  stop-opacity: 0;
}

.b3bslduol {
  d: path("M13.917 18.691c.67-.924 1.704-1.194 2.096-1.245c.206.83.308 2.667-.683 3.564c-.635.574-1.078.722-1.67.786c-.164.018-.27-.164-.222-.321c.03-.101.051-.22.053-.366c.01-.634-.109-1.68.426-2.418");
}

.b5--a89ix {
  d: path("M20.194 7.304H16.88c-1.314 0-2.508-.594-3.244-1.657a.272.272 0 0 0-.478.05l-.08.194a2.34 2.34 0 0 1-1.234 1.238a.4.4 0 0 1-.11.048c-.248.117-.816.488-.825 1.453l.139 3.235c.12 2.865 2.379 4.786 5.115 4.786c2.738 0 4.997-1.92 5.116-4.786l.13-3.08c-.02-1.354-1.026-1.48-1.215-1.48");
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.blny5fbqc {
  stop-color: var(--svg-color--dfc3c4, #DFC3C4);
  stop-opacity: 0;
}

.bm3jemb-u {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
  stop-opacity: 0;
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bt1_2zb2r {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
  stop-opacity: 0;
}

.c484l0bau {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.496 9.337c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.cd2w3_-kd {
  stop-color: var(--svg-color--2f1d25, #2F1D25);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl0gv76ti {
  stop-color: var(--svg-color--1a0e1c, #1A0E1C);
}

.cmm4esboy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.223 9.797c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.cttowni_l {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.731 8.335c.257-.17.898-.47 1.655-.352");
}

.cv_2ldbfl {
  d: path("M19.083 10.384a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.cxaqe9bxy {
  stop-color: var(--svg-color--e7d1cd, #E7D1CD);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d3so7-bzn {
  d: path("M15.869 3.745h.58v2.137h-.58z");
}

.d7puktbmy {
  d: path("M20.44 25.247a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9a-s9bqe {
  stop-color: var(--svg-color--a191a5, #A191A5);
  stop-opacity: 0;
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dc6jrkblm {
  stop-color: var(--svg-color--160c19, #160C19);
}

.dh53m4b-h {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M13.598 9.272c.766.039 1.1.422 1.219.613l-2.012.46c-.14.009-.484-.085-.562-.245a.31.31 0 0 1 .05-.363c.176-.204.675-.497 1.305-.465");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dmf0acl5m {
  stop-color: var(--svg-color--565252, #565252);
  stop-opacity: 0;
}

.dv8o3t25w {
  stop-color: var(--svg-color--9183a0, #9183A0);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.elromo-up {
  d: path("M26.509 21.18c0-.405.26-.757.568-1.02c.605-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.568.615.568 1.02v5.057h1.406z");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.er1lz4bqk {
  d: path("m18.7 5.882l.474-1.847v1.847z");
}

.ew3-w3ohh {
  d: path("M15.442 17.565c.19-.063.44-.119.707-.119s.517.056.707.12a.39.39 0 0 1 .254.45c-.092.486-.269.8-.463.989a.5.5 0 0 1-.268.13c-.109.02-.337.032-.476 0a.43.43 0 0 1-.252-.13c-.194-.189-.371-.503-.464-.99a.39.39 0 0 1 .255-.45");
}

.eykyay15h {
  d: path("M9.13 17.98a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f1s8bobxq {
  stop-color: var(--svg-color--9482a1, #9482A1);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.fg0e2bc1h {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
}

.fi-xuqber {
  d: path("M27.112 23.064a.97.97 0 0 1 .967.967v2.215h-1.934V24.03a.976.976 0 0 1 .967-.967");
}

.fj7z_vbcj {
  stop-color: var(--svg-color--958d9d, #958D9D);
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fzc_bdcjb {
  d: path("M23.539 18.362H8.69a10.94 10.94 0 0 1 7.42-2.885c3.483 0 5.152.812 7.429 2.885");
}

.g4wbwbcoe {
  stop-color: var(--svg-color--a79da9, #A79DA9);
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gjkvqmbnm {
  stop-color: var(--svg-color--9482a1, #9482A1);
}

.grjae5nbo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.714 9.337c-.654 0-1.205.45-1.356 1.059c-.044.174.09.34.268.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.h-4ghpb7u {
  stop-color: var(--svg-color--150a0d, #150A0D);
  stop-opacity: 0;
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hd20xvb3l {
  d: path("M20.44 21.617a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.hm5-ozbqx {
  stop-color: var(--svg-color--cfc5da, #CFC5DA);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i1-orb7ke {
  stop-color: var(--svg-color--c3b7c1, #C3B7C1);
}

.i5m4wsx9z {
  stop-color: var(--svg-color--d68e4a, #D68E4A);
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.imzv_hbah {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.665 8.299c-.282-.274-.897-.47-1.655-.352");
}

.in19etb1c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.282 25.955h1.796");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j0ps6nvlv {
  d: path("M11.05 9.028a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j1xr6ccfb {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
  stop-opacity: 0;
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.jn1ik_bct {
  d: path("M21.19 28.138a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kbfsu5g-s {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.067 9.689a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.kxeosqc-h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.282 28.565h1.796");
}

.kz1-kyj0l {
  stop-color: var(--svg-color--a191a5, #A191A5);
}

.l0qpfdqgo {
  stop-color: var(--svg-color--baa6bf, #BAA6BF);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l97x9nxki {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.837 8.171a1.85 1.85 0 0 0-.687-.411c-.304-.096-.685-.122-1.213-.057a.277.277 0 0 0 .068.55c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li84xjbbs {
  fill: var(--svg-color--e1a474, #E1A474);
  d: path("M26.509 21.18c0-.405.26-.757.568-1.02c.605-.517 1.002-1.392 1.002-2.384c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.568.615.568 1.02v5.057h1.406z");
}

.lrdvsibwx {
  d: path("M18.223 9.797c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.lum4j-j2u {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M21.066 11.576q.059-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.m6lhrcc1m {
  stop-color: var(--svg-color--e1d7df, #E1D7DF);
}

.m9a6yfj-g {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M18.613 9.272c-.766.039-1.099.422-1.219.613l2.012.46c.14.009.484-.085.563-.245a.31.31 0 0 0-.051-.363c-.176-.204-.674-.497-1.305-.465");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mejh1wbdq {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
  stop-opacity: 0;
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.mtbd7jb1u {
  fill: var(--svg-color--000, #000);
  d: path("M17.777 10.501a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o_dy4cctk {
  d: path("M22.185 5.932H10.132a.2.2 0 0 1 .028.102v1.051c0 .249.201.45.45.45h11.099a.45.45 0 0 0 .45-.45V6.03a.2.2 0 0 1 .026-.098");
}

.o7lclgw6d {
  cx: 25.806px;
  cy: 17.721px;
  rx: 1.711px;
  ry: 2.227px;
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.o8i5tyo6h {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.742 13.41c.394.206.863.323 1.362.323a2.94 2.94 0 0 0 1.363-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.241m-2.987-.28l2.946.253m-2.946-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.208.027l-.042-.027m.042.027l-.042-.027m.042.027a1.94 1.94 0 0 1-1.626.869c-.681 0-1.28-.347-1.624-.868m3.208-.028a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.okyhtm__h {
  d: path("M18.289 9.609a.892.892 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.ongktybvd {
  stop-color: var(--svg-color--a499b2, #A499B2);
  stop-opacity: 0;
}

.ox62rwbrf {
  stop-color: var(--svg-color--e1dbe8, #E1DBE8);
}

.oy6n6fbyn {
  stop-color: var(--svg-color--160c19, #160C19);
  stop-opacity: 0;
}

.ozh-gwb3b {
  stop-color: var(--svg-color--ab96ac, #AB96AC);
}

.p-uvmjboo {
  d: path("M13.92 9.609a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.p0efopw-a {
  stop-color: var(--svg-color--b8a5ca, #B8A5CA);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvaqnwbug {
  d: path("m15.722 10.172l-.531 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.q2tim8bhp {
  d: path("M23.762 25.303c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.388a.735.735 0 0 1 0-1.315a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qa91z0bhj {
  d: path("M16.11 15.477c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.501c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qk3h5tshn {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
  stop-opacity: 0;
}

.ql78zhb7e {
  stop-color: var(--svg-color--dfc3c4, #DFC3C4);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r2xqv839x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.204 27.26H26");
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.rbgr_ib3q {
  stop-color: var(--svg-color--d49a8e, #D49A8E);
}

.ro1b8p4mm {
  stop-color: var(--svg-color--d49a8e, #D49A8E);
  stop-opacity: 0;
}

.rq63c9eso {
  stop-color: var(--svg-color--c8bdc7, #C8BDC7);
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.s_1n4rb1u {
  d: path("M9.13 18.007h10.052c2.176 0 3.947 1.796 3.947 4.004v7.996h-14z");
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s4d6j7b7p {
  fill: var(--svg-color--c4abda, #C4ABDA);
  d: path("M20.92 28.282a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.s6s8s0_ew {
  stop-color: var(--svg-color--cf9593, #CF9593);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.tb19eccqx {
  stop-color: var(--svg-color--b8a4be, #B8A4BE);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.txy846j_u {
  d: path("m13.587 5.882l-.475-1.847v1.847z");
}

.u2ledhn4b {
  cx: 13.651px;
  cy: 9.99px;
  rx: 0.39px;
  ry: 0.197px;
}

.u7axe2baw {
  stop-color: var(--svg-color--9183a0, #9183A0);
}

.uelaalb7d {
  stop-color: var(--svg-color--da9766, #DA9766);
}

.uohixqbkv {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.618 10.368l-.635 1.838c-.108.378.152.756.52.756h.787c.37 0 .63-.384.52-.756l-.53-1.838c-.114-.408-.542-.408-.662 0");
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdg1_vfpt {
  d: path("M21.066 11.576q.059-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.via-_dbpm {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
}

.vma3fs41g {
  stop-color: var(--svg-color--ffdac1, #FFDAC1);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vz20cubfv {
  d: path("M14.736 10.396c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w9txrw6kc {
  stop-color: var(--svg-color--150a0d, #150A0D);
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wowq8qbva {
  fill: var(--svg-color--000, #000);
  d: path("M14.432 10.501a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.xauyjcckd {
  fill: var(--svg-color--c1a0c0, #C1A0C0);
  d: path("M20.17 21.762a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xqxkuobqn {
  stop-color: var(--svg-color--c47068, #C47068);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y24-vkbxu {
  d: path("M23.584 10.754c0-.71-.207-1.361-.562-1.912c-.545-.846-1.488-1.2-1.488-1.861v-.01c0-.921-.138-1.762-.493-2.382H10.724c-.305.62-.394 1.461-.394 2.382v.01c0 .66-1.203 1.127-1.685 1.861a3.5 3.5 0 0 0-.561 1.912c0 .54.118 1.04.335 1.5a.6.6 0 0 1 0 .481a3.4 3.4 0 0 0-.335 1.481c0 1.862 1.488 3.373 3.32 3.373h8.859c1.833 0 3.32-1.511 3.32-3.373c0-.53-.118-1.03-.334-1.48a.58.58 0 0 1 0-.481a3.5 3.5 0 0 0 .335-1.501");
}

.yd_laccri {
  stop-color: var(--svg-color--565252, #565252);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.yiwn4_bdv {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M20.17 25.392a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z46q0-jev {
  d: path("M10.699 2.092a1.933 1.933 0 0 0-.682 3.744a.215.215 0 0 1 .143.197v1.052c0 .248.201.45.45.45h11.099a.45.45 0 0 0 .45-.45V6.03c0-.089.059-.166.142-.197a1.934 1.934 0 0 0-.69-3.74z");
}

.z75iesbgx {
  d: path("M23.13 30.007h4v-3.501c0-3.422-1.554-6.482-4-8.499z");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zab3c9ypw {
  stop-color: var(--svg-color--a8a0af, #A8A0AF);
  stop-opacity: 0;
}

.ze352u2px {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.694 8.055a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.zs8rr9bpw {
  d: path("M18.312 18.691c-.67-.924-1.704-1.194-2.096-1.245c-.205.83-.308 2.667.684 3.564c.635.574 1.077.722 1.67.786c.163.018.268-.164.221-.321a1.3 1.3 0 0 1-.053-.366c-.01-.634.109-1.68-.426-2.418");
}

.ztvu2mbem {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
}

.zu-galbrx {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M16.11 15.477c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.501c0-3.422-1.554-6.482-4-8.499v.013a10.92 10.92 0 0 0-7.02-2.543");
}

.zzbaevt2c {
  d: path("M15.843 17.503c-.385.032-1.405.252-2.103 1.142c-.469.6-.498 1.44-.52 2.069q-.004.177-.013.326a1.4 1.4 0 0 1-.07.363c-.054.154.04.341.2.331c.58-.036 1.018-.162 1.664-.705c.492-.413.742-1.062.85-1.716c.044.661.23 1.332.678 1.792c.59.604 1.013.773 1.587.866c.158.026.27-.151.231-.31a1.4 1.4 0 0 1-.034-.368q.007-.151.019-.326c.04-.628.095-1.467-.313-2.11c-.607-.955-1.6-1.274-1.98-1.344a5 5 0 0 0-.127.582a5 5 0 0 0-.07-.592");
}

</style>
