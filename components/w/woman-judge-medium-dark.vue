<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIMNISe)"><path fill="url(#iUuYQle)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#iiBqgZd)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#ib2UvHb)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#iQxSoGe)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#i9Qv0WM)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#iyCKDnb)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#iSiHQpc)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#ilLp4vd)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#iD5VBAc)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#iZDyflz)" clip-rule="evenodd" class="b4gt5sboj"/><path fill="url(#i4bWNlc)" clip-rule="evenodd" class="b4gt5sboj"/></g><path fill="url(#icTrJOe)" class="olf-9cbgt"/><path fill="url(#iWhMVxc)" class="olf-9cbgt"/><path fill="url(#iStwEmb)" class="olf-9cbgt"/><path fill="url(#iyxzxod)" class="olf-9cbgt"/><path fill="url(#iqk0Y4b)" class="fcoe71bgv"/><path fill="url(#iayMOcp)" class="fcoe71bgv"/><path fill="url(#iGimbrb)" class="fcoe71bgv"/><path fill="url(#iQtvW8d)" class="fcoe71bgv"/><path fill="url(#iGPdcSc)" class="b7jjow0yx"/><path fill="url(#imfs2tc)" class="b7jjow0yx"/><path fill="url(#iGBKTmd)" class="xlnno-coc"/><path fill="url(#isGvHLc)" class="xlnno-coc"/><path fill="url(#i7hpFDe)" class="xlnno-coc"/><path fill="url(#iD7YjYd)" class="qalwy2bpt"/><path fill="url(#i6Dsrxm)" class="qalwy2bpt"/><path fill="url(#idaR3Ui)" class="bbgkx8bvh"/><path fill="url(#ie2PeNd)" class="bbgkx8bvh"/><g filter="url(#i4SRsDd)"><path fill="url(#iIzq3xc)" class="x5fafo5qc"/><path fill="url(#iNa2gQb)" class="x5fafo5qc"/><path fill="url(#i0d4Jid)" class="x5fafo5qc"/><path fill="url(#i16T1jb)" class="x5fafo5qc"/><path fill="url(#ipz0KWd)" class="x5fafo5qc"/></g><rect fill="url(#iCq3yfc)" class="xjy99rb3q"/><rect fill="url(#i3K8uec)" class="xjy99rb3q"/><g filter="url(#ibX9e3b)"><path fill="url(#iYNmAMh)" class="prl8x6_4w"/></g><g filter="url(#iRVFdKd)"><path fill="url(#ilgJlCe)" class="t_l0wx9dl"/></g><g filter="url(#itTcFZd)"><path fill="url(#ihNOIKV)" class="q2osvdbre"/></g><g filter="url(#iFa6pee)"><path stroke="url(#ijxXVtb)" class="q5yeu-b1p"/></g><g filter="url(#i6znafc)"><path stroke="url(#iLZih8c)" class="pxo5bdc1v"/></g><g filter="url(#iJ2nz6j)"><path stroke="url(#ien8Xbb)" class="lun049bff"/></g><g filter="url(#irjiHzc)"><path fill="url(#ifnsKPR)" class="n3d1_dber"/><path fill="url(#icEfi7c)" class="n3d1_dber"/></g><path fill="url(#i93KQHe)" class="kfvwr2w6p"/><path fill="url(#iTt9JZo)" class="kfvwr2w6p"/><path fill="url(#ihEx2Nc)" class="kfvwr2w6p"/><path fill="url(#ijnVqLd)" class="kfvwr2w6p"/><path fill="url(#iYKacxu)" class="kfvwr2w6p"/><path fill="url(#iOOo06d)" class="d0-xa4bll"/><path fill="url(#i7ZwxIc)" class="d0-xa4bll"/><path fill="url(#iXvaGwd)" class="d0-xa4bll"/><path fill="url(#iocEKnF)" class="d0-xa4bll"/><path fill="url(#i3nHSJb)" class="x_jkj26oo"/><path fill="url(#i58X3rP)" class="x_jkj26oo"/><path fill="url(#ixUhefd)" class="x_jkj26oo"/><path fill="url(#iYNhL0c)" class="h6ivz3boi"/><path fill="url(#ip2SpRd)" class="x8kc--mhp"/><g filter="url(#iYT3xPW)"><path fill="url(#iDv59GZ)" class="th42qvbso"/></g><g filter="url(#i7ORK5b)"><path fill="url(#iPs47Qd)" class="v56xnabcb"/><path fill="url(#ixzzdXb)" class="v56xnabcb"/></g><g filter="url(#iPUcwpb)"><path class="t06oal3yn"/><path fill="url(#iHdGftL)" class="lx4qxw5-n"/></g><g filter="url(#iFj2pdt)"><path class="r8m_i0zdd"/><path fill="url(#i6F7FPd)" class="fktlxunnw"/></g><g filter="url(#i17r5Qd)"><path fill="url(#iYL17Dd)" class="kesmzwhfm"/><path fill="url(#ir4Imqe)" class="kesmzwhfm"/><path fill="url(#iQ4ABhb)" class="kesmzwhfm"/><path fill="url(#iVLZ5qc)" class="kesmzwhfm"/><path fill="url(#i1FCy2g)" class="kesmzwhfm"/><path fill="url(#iMhpzsb)" class="kesmzwhfm"/><path fill="url(#ih62aEb)" class="kesmzwhfm"/><path fill="url(#idk9gnb)" class="kesmzwhfm"/></g><path fill="url(#idQ9oLk)" class="kesmzwhfm"/><path fill="url(#inqC87c)" class="kesmzwhfm"/><path fill="url(#i9E5W0d)" class="kesmzwhfm"/><path fill="url(#i6E16ne)" class="kesmzwhfm"/><g filter="url(#inw6aic)"><path class="p31r0mbhk"/></g><g filter="url(#iLJoP1d)"><path class="vhx4jvufb"/><path fill="url(#isAy1kb)" class="zk7h_31lk"/><path fill="url(#iFtOiwe)" class="zk7h_31lk"/><path fill="url(#ivN5UIb)" class="zk7h_31lk"/><path fill="url(#i9AI3Lb)" class="zk7h_31lk"/></g><path fill="url(#iUocusb)" class="zk7h_31lk"/><path fill="url(#iZBSTtb)" class="zk7h_31lk"/><path stroke="url(#iVK0Vnd)" class="ug1eosbhl"/><g filter="url(#ie1p54a)"><path class="z9ss052hg"/></g><g filter="url(#i7Kltne)"><path class="w2sz6hb3d"/></g><g filter="url(#iAEFKFd)"><path class="z2xrkvjoz"/></g><g filter="url(#itPsHtb)"><path clip-rule="evenodd" class="gijd9bbsd"/></g><path class="un34wfbre"/><path fill="url(#i9Uqrle)" class="bfy2_2lhv"/><path class="snj4bjjoh"/><g filter="url(#iBtxA6c)"><path class="rljcijb1h"/><path fill="url(#irXtzDd)" class="vgr-0tb7u"/></g><g filter="url(#iGziMPc)"><path fill="url(#idUevLc)" class="ipra_kbri"/></g><path class="d9984peev"/><path fill="url(#i2J1nPe)" class="ika1ayqjm"/><path class="sw-ac--zu"/><g filter="url(#iAk4hyb)"><path fill="url(#iopbutd)" class="q_3qtvbrf"/></g><g filter="url(#iC2Zsfb)"><ellipse transform="rotate(-27.914 13.712 10.019)" class="gfp9cz2iu"/><ellipse fill="url(#i6IclBY)" transform="rotate(-27.914 13.712 10.019)" class="c-vjnvb1a"/></g><g filter="url(#iTlO4Wd)"><path class="x6tnopl6b"/></g><g filter="url(#iOhnzge)"><path class="kpah2kl8a"/></g><g filter="url(#iqmy1Hc)"><path class="k7id9ub6q"/><path fill="url(#i6xJusd)" class="nck15zcrc"/></g><g filter="url(#iuWNEWW)"><path class="z97wghb4w"/><path fill="url(#ibpsNgA)" class="zcmisj9fx"/><path fill="url(#iakdpHe)" class="zcmisj9fx"/></g><g filter="url(#id9V1Fe)"><path stroke="url(#icjmnpd)" class="rot6pmd1l"/></g><g filter="url(#ilLjMnb)"><path class="tqqfi4bmv"/></g><defs><radialGradient id="iiBqgZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.865 13.212)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ib2UvHb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 13.048 13.48)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iQxSoGe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.96 8.264)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i9Qv0WM" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.39 7.754)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iyCKDnb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.127 11.793)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iSiHQpc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 10.02 6.922)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ilLp4vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.675 9.86)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iD5VBAc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.718 8.06)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iZDyflz" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.105 -3.762)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i4bWNlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 10.024 9.824)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iyxzxod" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.45313 -5.35592 0 16.17 16.68)" gradientUnits="userSpaceOnUse"><stop class="u4dm99tvf"/><stop offset="1" class="pzxsbj1yt"/></radialGradient><radialGradient id="iqk0Y4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 5.095 29.956)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iayMOcp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.943 29.956)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iGimbrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.943 23.007)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iGPdcSc" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.079 4.481)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="imfs2tc" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.225 23.11)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iGBKTmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82081 -2.84518 0 16.94 16.233)" gradientUnits="userSpaceOnUse"><stop class="ig14nderp"/><stop offset="1" class="tcdzfs0as"/></radialGradient><radialGradient id="isGvHLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.42297 -2.45165 0 16.17 15.145)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="ispcapbgm"/><stop offset=".975" class="c5reugbnm"/></radialGradient><radialGradient id="i7hpFDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -.53125 0 14.86 15.99)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="ox076faqk"/><stop offset="1" class="zqgbv4b6r"/></radialGradient><radialGradient id="iD7YjYd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57562 1.29893 -1.2769 -1.54888 27.918 23.516)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="i6Dsrxm" cx="0" cy="0" r="1" gradientTransform="matrix(.75156 -.57402 .30002 .3928 27.685 23.365)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="idaR3Ui" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.271 24.24)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="iNa2gQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.037 25.26)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i0d4Jid" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.037 26.555)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i16T1jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.037 27.805)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ipz0KWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.037 29.157)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iCq3yfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.717 21.417)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="ifnsKPR" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.3125 12.819 0 16.151 23.362)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="rr16fpbgs"/><stop offset="1" class="gvd3e3nnk"/></radialGradient><radialGradient id="icEfi7c" cx="0" cy="0" r="1" gradientTransform="rotate(-94.385 20.534 4.352)scale(10.6778 18.1021)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="p3kckzh8s"/><stop offset="1" class="nqv_-mmyu"/></radialGradient><radialGradient id="ihEx2Nc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.87 17.349)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="iocEKnF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.584 17.175)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="ixUhefd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.35 17.425)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="iPs47Qd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.205 11.15)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ixzzdXb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.236 9.03)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iHdGftL" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.557 10.824)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="i6F7FPd" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.782 5.356)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iYL17Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 19.025 10.174)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="ir4Imqe" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.909 7.42)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iQ4ABhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 14.004 16.681)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iVLZ5qc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 17.189 9.758)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="i1FCy2g" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.41 6.826)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iMhpzsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.467 9.756)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="ih62aEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 14.09 9.527)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="idk9gnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.549 7.44)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="idQ9oLk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.261 11.243)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="inqC87c" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.352 2.423)scale(1.52213 1.61741)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="i9E5W0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.5625 1.85526 2.0779 12.13 15.903)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="i6E16ne" cx="0" cy="0" r="1" gradientTransform="matrix(1.376 5.592 -5.23934 1.28923 13.4 4.27)" gradientUnits="userSpaceOnUse"><stop class="kk6q72bdf"/><stop offset="1" class="m8c8ve3xs"/></radialGradient><radialGradient id="isAy1kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.95 11.969)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i9AI3Lb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.71 12.181)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iZBSTtb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.474 8.36)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="i9Uqrle" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.348 10.114)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="irXtzDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.12 10.198)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2J1nPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.984 10.114)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i6IclBY" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.935 -1.575)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6xJusd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.48 -4.188)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ibpsNgA" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.162 7.076)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iakdpHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.376 3.157)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><linearGradient id="iUuYQle" x1="20.859" x2="14.054" y1="3.759" y2="16.363" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="icTrJOe" x1="16.172" x2="16.172" y1="15.497" y2="30.381" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="iWhMVxc" x1="23.599" x2="21.068" y1="26.55" y2="26.581" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="iStwEmb" x1="8.627" x2="10.843" y1="26.365" y2="26.365" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="iQtvW8d" x1="9.091" x2="8.656" y1="28.022" y2="28.022" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="ie2PeNd" x1="25.634" x2="25.662" y1="21.952" y2="22.308" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iIzq3xc" x1="27.628" x2="23.6" y1="28.019" y2="28.019" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="i3K8uec" x1="25.644" x2="25.644" y1="20.769" y2="21.23" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iYNmAMh" x1="17.222" x2="17.222" y1="29.559" y2="22.883" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ilgJlCe" x1="13.215" x2="13.215" y1="29.559" y2="22.883" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ihNOIKV" x1="21.209" x2="21.209" y1="29.559" y2="22.883" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ijxXVtb" x1="24.123" x2="25.832" y1="26.026" y2="26.026" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iLZih8c" x1="24.045" x2="25.754" y1="27.331" y2="27.331" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ien8Xbb" x1="24.123" x2="25.832" y1="28.636" y2="28.636" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i93KQHe" x1="27.912" x2="24.537" y1="20.675" y2="20.3" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="iTt9JZo" x1="25.633" x2="25.633" y1="20.94" y2="20.425" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="ijnVqLd" x1="25.633" x2="25.633" y1="16.795" y2="17.425" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iYKacxu" x1="23.335" x2="24.077" y1="19.142" y2="19.142" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="iOOo06d" x1="23.506" x2="22.209" y1="18.926" y2="18.926" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="i7ZwxIc" x1="23.756" x2="23.365" y1="19.206" y2="19.206" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iXvaGwd" x1="22.96" x2="22.96" y1="21.037" y2="20.374" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="i3nHSJb" x1="29.207" x2="27.587" y1="19.373" y2="19.373" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="i58X3rP" x1="28.506" x2="28.506" y1="21.011" y2="20.487" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iYNhL0c" x1="9" x2="23.376" y1="15.521" y2="15.521" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ip2SpRd" x1="9" x2="23.376" y1="15.491" y2="15.491" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iDv59GZ" x1="9.922" x2="11.162" y1="10.799" y2="10.799" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iFtOiwe" x1="15.227" x2="16.166" y1="12.043" y2="12.043" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="ivN5UIb" x1="16.166" x2="16.166" y1="12.842" y2="12.231" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iUocusb" x1="16.244" x2="16.244" y1="12.816" y2="12.676" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iVK0Vnd" x1="15.101" x2="15.562" y1="14.252" y2="13.539" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="idUevLc" x1="19.126" x2="18.812" y1="10.168" y2="10.361" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iopbutd" x1="14.727" x2="14.414" y1="10.168" y2="10.362" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icjmnpd" x1="13.274" x2="13.819" y1="4.513" y2="5.787" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><filter id="iIMNISe" width="15.268" height="15.768" x="8.657" y="1.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="i4SRsDd" width="4.468" height="5.556" x="23.6" y="24.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="ibX9e3b" width="1.192" height="6.826" x="15.589" y="23.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".125"/></filter><filter id="iRVFdKd" width="1.192" height="6.826" x="11.583" y="23.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".125"/></filter><filter id="itTcFZd" width="1.192" height="6.826" x="19.576" y="23.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".125"/></filter><filter id="iFa6pee" width="2.097" height=".3" x="23.973" y="25.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".05"/></filter><filter id="i6znafc" width="2.097" height=".3" x="23.895" y="27.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".05"/></filter><filter id="iJ2nz6j" width="2.097" height=".3" x="23.973" y="28.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".05"/></filter><filter id="irjiHzc" width="12.911" height="8.522" x="9.695" y="15.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.756863 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="iYT3xPW" width="3.368" height="3.218" x="9.871" y="9.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="i7ORK5b" width="3.218" height="3.468" x="19.384" y="8.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="iPUcwpb" width="3.148" height="3.148" x="19.419" y="9.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".25"/></filter><filter id="iFj2pdt" width="2.648" height="2.648" x="10.175" y="9.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".125"/></filter><filter id="i17r5Qd" width="10.191" height="11.127" x="11.07" y="5.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="inw6aic" width="2.877" height="3.682" x="14.565" y="9.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".25"/></filter><filter id="iLJoP1d" width="2.377" height="3.182" x="14.977" y="9.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".125"/></filter><filter id="ie1p54a" width="3.001" height="1.285" x="17.108" y="9.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="i7Kltne" width="3.001" height="1.285" x="12.223" y="9.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="iAEFKFd" width="2.453" height="1.091" x="12.358" y="7.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="itPsHtb" width="2.453" height="1.091" x="17.775" y="7.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/></filter><filter id="iBtxA6c" width=".787" height=".696" x="17.614" y="9.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".05"/></filter><filter id="iGziMPc" width=".891" height=".913" x="18.454" y="9.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".1"/></filter><filter id="iAk4hyb" width=".986" height="1.04" x="14.011" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".1"/></filter><filter id="iC2Zsfb" width=".913" height=".705" x="13.256" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".05"/></filter><filter id="iTlO4Wd" width="2.661" height="1.378" x="17.605" y="7.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".2"/></filter><filter id="iOhnzge" width="2.661" height="1.378" x="12.154" y="7.805" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".2"/></filter><filter id="iqmy1Hc" width="4.312" height="4.613" x="9.811" y="3.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/><feGaussianBlur result="effect2_foregroundBlur_4002_1732" stdDeviation=".2"/></filter><filter id="iuWNEWW" width="8.767" height="5.782" x="12.995" y="2.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1732"/><feGaussianBlur result="effect2_foregroundBlur_4002_1732" stdDeviation=".125"/></filter><filter id="id9V1Fe" width="1.145" height="2.31" x="12.975" y="3.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".1"/></filter><filter id="ilLjMnb" width="6.927" height="3.872" x="15.334" y="4.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1732" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-judge-medium-dark" /></template>
<style>
.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b4gt5sboj {
  fill-rule: evenodd;
  d: path("M23.351 12.121c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.456.232l-.085.002A3.3 3.3 0 0 0 9.73 7.092v.01a3.24 3.24 0 0 1-.526 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.122-.981-.324-1.406a.52.52 0 0 1 0-.456M11.091 9.45h-.012l1.198 2.355c.123 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.461.05l-.082.194c-.226.562-.657.99-1.19 1.235l-.051.02l-.052.02c-.235.123-.79.49-.81 1.44l.01.306z");
}

.b7jjow0yx {
  d: path("M23.398 29.956v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bbgkx8bvh {
  d: path("M24.879 21.027v6.426h1.51v-6.426z");
}

.bfy2_2lhv {
  d: path("M18.35 9.637a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c-vjnvb1a {
  cx: 13.712px;
  cy: 10.019px;
  rx: 0.39px;
  ry: 0.197px;
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c5reugbnm {
  stop-color: var(--svg-color--5a3124, #5A3124);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d0-xa4bll {
  d: path("M23.178 16.911h-.613a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h.613a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.d9984peev {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.775 9.365c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.fcoe71bgv {
  d: path("M8.943 29.956v-11.8c-2.356 2.01-3.848 4.986-3.848 8.31v3.49z");
}

.fktlxunnw {
  d: path("M11.5 11.785a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gfp9cz2iu {
  cx: 13.712px;
  cy: 10.019px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.gijd9bbsd {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.897 8.476l-.138.23za.268.268 0 0 1-.275.46l-.005-.002l-.022-.013l-.09-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.512-.09.988 0 1.328.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gvd3e3nnk {
  stop-color: var(--svg-color--bdb2af, #BDB2AF);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.h6ivz3boi {
  d: path("M16.54 15.492c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ig14nderp {
  stop-color: var(--svg-color--7b5653, #7B5653);
}

.ika1ayqjm {
  d: path("M13.982 9.637a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.ipra_kbri {
  d: path("M19.145 10.412a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.ispcapbgm {
  stop-color: var(--svg-color--5a3124, #5A3124);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.k7id9ub6q {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M11.097 4.723c.565-.6 1.636-.6 2.13-.51l.396 1.29c-.253-.04-.478.05-.667.235c-.449 1.26-1.99 1.955-2.704 2.145c-.149-1.492.108-2.38.845-3.16");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kesmzwhfm {
  d: path("M11.079 9.449h.012l-.01-.265l-.01-.307c.02-.948.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.193a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.081.087 1.135 1.332l-.119 3.073c-.123 2.803-2.311 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.kfvwr2w6p {
  d: path("M27.083 16.911h-2.901a.505.505 0 0 0-.504.504v3.022c0 .272.222.503.504.503h2.901a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kk6q72bdf {
  stop-color: var(--svg-color--4d2727, #4D2727);
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kpah2kl8a {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.314 8.339c-.322-.079-1.124-.04-1.66.344");
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lun049bff {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.123 28.558h1.797");
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lx4qxw5-n {
  d: path("M20.993 11.785a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.m8c8ve3xs {
  stop-color: var(--svg-color--4d2727, #4D2727);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n3d1_dber {
  d: path("M13.237 16.035a.196.196 0 0 0-.221-.176c-1.073.163-1.98.713-2.909 1.244c-.195.111-.357.285-.392.507q-.02.122-.02.248c0 .6.333 1.12.825 1.39c.056.03.075.104.04.158a1.582 1.582 0 0 0 1.419 2.43a.114.114 0 0 1 .119.121l-.004.112a1.582 1.582 0 0 0 2.498 1.29a.114.114 0 0 1 .166.038a1.582 1.582 0 0 0 2.786 0a.114.114 0 0 1 .166-.038a1.582 1.582 0 0 0 2.495-1.401a.114.114 0 0 1 .118-.121l.084.002a1.582 1.582 0 0 0 1.335-2.433a.113.113 0 0 1 .04-.159a1.58 1.58 0 0 0 .805-1.637c-.035-.222-.197-.396-.392-.507c-.928-.53-1.836-1.081-2.909-1.244a.196.196 0 0 0-.221.176c-.19 1.636-1.06 3.258-2.914 3.268c-1.854-.01-2.725-1.632-2.914-3.268");
}

.nck15zcrc {
  d: path("M11.097 4.723c.565-.6 1.636-.6 2.13-.51l.396 1.29c-.253-.04-.478.05-.667.235c-.449 1.26-1.99 1.955-2.704 2.145c-.149-1.492.108-2.38.845-3.16");
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nqv_-mmyu {
  stop-color: var(--svg-color--5f5c5d, #5F5C5D);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olf-9cbgt {
  d: path("M16.094 15.675c-6.115 0-10.999 4.728-10.999 10.79v3.491h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-5.037-10.791-11.151-10.791");
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ox076faqk {
  stop-color: var(--svg-color--6e504f, #6E504F);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p31r0mbhk {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.773 10.489l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.p3kckzh8s {
  stop-color: var(--svg-color--9b999b, #9B999B);
  stop-opacity: 0;
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prl8x6_4w {
  d: path("M15.839 23.5h.692v6.326h-.692z");
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxo5bdc1v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.045 27.253h1.797");
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.pzxsbj1yt {
  stop-color: var(--svg-color--1a121e, #1A121E);
  stop-opacity: 0;
}

.q_3qtvbrf {
  d: path("M14.797 10.425c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.q2osvdbre {
  d: path("M19.826 23.5h.692v6.326h-.692z");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q5yeu-b1p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.123 25.948h1.797");
}

.qalwy2bpt {
  d: path("M26.959 22.889c.531 0 .959.427.959.959v2.188H26.01v-2.188a.94.94 0 0 1 .948-.96");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.r8m_i0zdd {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.5 11.785a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rljcijb1h {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.284 9.826c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.246.159-.359c.15-.112.325-.135.388-.05");
}

.rot6pmd1l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.275 4.17c.023.242.234 1.156.544 1.71");
}

.rr16fpbgs {
  stop-color: var(--svg-color--ddd3e4, #DDD3E4);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.snj4bjjoh {
  fill: var(--svg-color--000, #000);
  d: path("M17.839 10.53c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746H17.9a.46.46 0 0 1-.061-.235");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sw-ac--zu {
  fill: var(--svg-color--000, #000);
  d: path("M14.493 10.53a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t_l0wx9dl {
  d: path("M11.833 23.5h.692v6.326h-.692z");
}

.t06oal3yn {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.993 11.785a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tcdzfs0as {
  stop-color: var(--svg-color--704539, #704539);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.th42qvbso {
  d: path("M11.48 12.32a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.tqqfi4bmv {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m18.572 6.53l-1.425.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u4dm99tvf {
  stop-color: var(--svg-color--1a121e, #1A121E);
}

.ug1eosbhl {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.832 13.525a.2.2 0 0 0-.02-.25a.205.205 0 0 0-.248-.041c-.404.216-.88.34-1.398.34a3 3 0 0 1-1.398-.34a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.247m3.332 0l-.041-.027zm0 0a1.982 1.982 0 0 1-3.333 0m0 0l.042-.027m-.042.027l.042-.027m0 0a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345c-.52 0-1.01-.125-1.422-.345c-.14-.073-.291.09-.203.22Z");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.un34wfbre {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.557 9.365c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.128 1.37-1.128");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.v56xnabcb {
  d: path("M20.993 12.32a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vgr-0tb7u {
  d: path("M18.284 9.826c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.246.159-.359c.15-.112.325-.135.388-.05");
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vhx4jvufb {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.783 10.35l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.w2sz6hb3d {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.024 10.142c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.105-1.073.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x_jkj26oo {
  d: path("M28.704 16.911h-.614a.505.505 0 0 0-.503.504v3.022c0 .272.221.503.503.503h.613a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.x5fafo5qc {
  d: path("M23.6 25.282a.73.73 0 0 1 .726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.x6tnopl6b {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.105 8.339c.323-.079 1.125-.04 1.661.344");
}

.x8kc--mhp {
  d: path("M16.21 15.492h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.xjy99rb3q {
  width: 2.773px;
  height: 1.082px;
  x: 24.257px;
  y: 20.94px;
  rx: 0.541px;
}

.xlnno-coc {
  d: path("M16.17 18.504a2.07 2.07 0 0 1-2.075-2.075v-2.578a2.07 2.07 0 0 1 2.075-2.065c1.149 0 2.075.926 2.075 2.075v2.578a2.083 2.083 0 0 1-2.075 2.065");
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z2xrkvjoz {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.768 8.934l-.004.002a.268.268 0 0 1-.276-.46h.002l.002-.003l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.194");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z97wghb4w {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.562 2.92c-1.132-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.744.542 1.878.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.z9ss052hg {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.308 10.142c.265-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.269.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.08-.45");
}

.zcmisj9fx {
  d: path("M15.562 2.92c-1.132-.25-2.15.88-2.267 1.3c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.744.542 1.878.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.zk7h_31lk {
  d: path("m15.783 10.35l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zqgbv4b6r {
  stop-color: var(--svg-color--6e504f, #6E504F);
  stop-opacity: 0;
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
