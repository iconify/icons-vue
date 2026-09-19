<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipTLM5l)"><path fill="url(#ivtLrRb)" class="s0msj2bhb"/></g><path fill="url(#inX0Zgb)" class="u-aqhqb6h"/><path fill="url(#iOdQGdc)" class="u-aqhqb6h"/><path fill="url(#iQ1CMFc)" class="u-aqhqb6h"/><g filter="url(#im4fmKb)"><path stroke="url(#iBfQ7vd)" class="na7m58bfk"/></g><g filter="url(#irnahhe)"><path fill="url(#isx28Rb)" class="b87lf7bgc"/><path fill="url(#ikSiUzN)" class="b87lf7bgc"/><path fill="url(#irX8o2c)" class="b87lf7bgc"/></g><g filter="url(#iUWaZKd)"><path fill="url(#iQEnTFQ)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#iBiauqe)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#iPJO4Tc)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#iH7Tded)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#i0H6VAc)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#ibCNaBb)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#iKaKFyb)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#itdIbhc)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#ixoHMHd)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#ieXvaCc)" clip-rule="evenodd" class="jxgb-l3au"/><path fill="url(#i4c3gkd)" clip-rule="evenodd" class="jxgb-l3au"/></g><path fill="url(#i55MFDe)" class="zvr9x85bv"/><path fill="url(#i6YCJve)" class="zvr9x85bv"/><path fill="url(#igkrOuc)" class="zvr9x85bv"/><path fill="url(#iCYLN5d)" class="imhyssb0r"/><path fill="url(#ijNUtce)" class="imhyssb0r"/><path fill="url(#i7eiRCQ)" class="imhyssb0r"/><path fill="url(#izQuehc)" class="ei57c5neo"/><path fill="url(#i0yWNHb)" class="ei57c5neo"/><path fill="url(#iRcx2bc)" class="q1qzdin-x"/><g filter="url(#idCywce)"><path fill="url(#ivhS0Mc)" class="hl-fmab0h"/><path fill="url(#i4SFPld)" class="hl-fmab0h"/><path fill="url(#io78xVc)" class="hl-fmab0h"/><path fill="url(#imsXbUb)" class="hl-fmab0h"/></g><g filter="url(#iTb5mke)"><path fill="url(#iF4mJXa)" class="c6magac4y"/><path fill="url(#inr0qoc)" class="c6magac4y"/><path fill="url(#iWYbeAc)" class="c6magac4y"/><path fill="url(#iycY7fG)" class="c6magac4y"/></g><path fill="url(#iwuFY0b)" class="wpud2mb_p"/><g filter="url(#iE3E3ie)"><path fill="url(#iZjvf3b)" class="xjvebdcyn"/><path fill="url(#igkft1d)" class="xjvebdcyn"/></g><g filter="url(#iY62SlT)"><path fill="url(#iGfu3Cc)" class="jpq_dkbzf"/></g><path fill="url(#i8AOzjX)" class="juf3zkb2c"/><path clip-rule="evenodd" class="dzknzyhpx"/><path fill="url(#iWwXged)" clip-rule="evenodd" class="qkdlpxbzm"/><g filter="url(#iAf6Yzd)"><path fill="url(#iydzz9c)" class="ujeoxvv-i"/><path fill="url(#iPsTu2A)" class="ujeoxvv-i"/><path fill="url(#iARXdfc)" class="ujeoxvv-i"/><path fill="url(#iif4Lae)" class="ujeoxvv-i"/><path fill="url(#itrOSAb)" class="ujeoxvv-i"/></g><g filter="url(#ifCs91d)"><path fill="url(#iq2m47c)" class="s85b50mwh"/><path fill="url(#iBGl16P)" class="s85b50mwh"/><path fill="url(#ihjsdzh)" class="s85b50mwh"/><path fill="url(#ihLzeXy)" class="s85b50mwh"/><path fill="url(#izvGcfd)" class="s85b50mwh"/></g><path fill="url(#iLSJzjd)" class="jd5-gflla"/><path fill="url(#io4h0vb)" class="phdxp8s-u"/><g filter="url(#ijF41Td)"><path stroke="url(#iQetH0c)" class="dpicrc-fd"/></g><g filter="url(#iboIpbc)"><path stroke="url(#ikJ9fhb)" class="yfm3e8b8e"/></g><g filter="url(#i37lKEb)"><path stroke="url(#iQlsbNE)" class="xgyop8b4p"/></g><g filter="url(#iwm3Pne)"><path stroke="url(#i8ILMuc)" class="c5-_gr0ru"/></g><g filter="url(#iovNBGd)"><path stroke="url(#i21TZxc)" class="c0jwnxbqr"/></g><g filter="url(#iljRBJc)"><path stroke="url(#isAozxd)" class="ns1-y9bit"/></g><g filter="url(#i3WhYAb)"><path fill="url(#i06TBYd)" class="rzbdi_r-e"/></g><g filter="url(#iNXT5hb)"><path fill="url(#iSW10hc)" class="k3yhup92u"/><path fill="url(#ia5Eynb)" class="k3yhup92u"/></g><g filter="url(#iIKoSQc)"><path class="em-du1blu"/><path fill="url(#iuYcr5R)" class="qbh01rbob"/></g><g filter="url(#i3ZpCAm)"><path class="r1gp83b4g"/><path fill="url(#i9qxCXb)" class="a6bak5b_z"/></g><g filter="url(#iR7uaee)"><path fill="url(#iBZL7fR)" class="wnc9k4m5a"/><path fill="url(#itZi0Vb)" class="wnc9k4m5a"/><path fill="url(#i3Ncboc)" class="wnc9k4m5a"/><path fill="url(#imxGpjc)" class="wnc9k4m5a"/><path fill="url(#iWejpkT)" class="wnc9k4m5a"/><path fill="url(#icYdnmW)" class="wnc9k4m5a"/><path fill="url(#iAsmOAb)" class="wnc9k4m5a"/><path fill="url(#ioUmgAc)" class="wnc9k4m5a"/></g><path fill="url(#iNI874E)" class="wnc9k4m5a"/><path fill="url(#irpzyEe)" class="wnc9k4m5a"/><path fill="url(#iZL0pSc)" class="wnc9k4m5a"/><g filter="url(#i6as2od)"><path class="uhoem0bpa"/></g><g filter="url(#i7qrVmc)"><path class="llpp05cwb"/><path fill="url(#igVWbCc)" class="xlgofpbrt"/><path fill="url(#iHQooXi)" class="xlgofpbrt"/><path fill="url(#iI3pBec)" class="xlgofpbrt"/><path fill="url(#inaemwe)" class="xlgofpbrt"/></g><path fill="url(#i40lRxc)" class="xlgofpbrt"/><path fill="url(#iLg28Ti)" class="xlgofpbrt"/><path stroke="url(#iSnQlze)" class="sklvyriza"/><g filter="url(#iBDaf1Y)"><path class="vmd9ttl4n"/></g><g filter="url(#iYMzr6d)"><path class="nbqq-1b8f"/></g><g filter="url(#ijCmN3M)"><path class="kdhqs4bai"/></g><g filter="url(#i68eN7d)"><path clip-rule="evenodd" class="ke-6vubux"/></g><path class="avba2dppg"/><path fill="url(#i0LnVQc)" class="k3o8yr4tm"/><path class="x7se-rbeq"/><g filter="url(#iqO5tXd)"><path class="rk3ub_0wu"/><path fill="url(#i1C5rMe)" class="tbojtxbws"/></g><g filter="url(#iW5ki1d)"><path fill="url(#iiuDfNb)" class="b-v92n1ix"/></g><path class="z3_920cft"/><path fill="url(#iww7RRd)" class="bfz-gkb2h"/><path class="lmazyohix"/><g filter="url(#ieSOFhj)"><path fill="url(#iOLUx5b)" class="q-6-rea_l"/></g><g filter="url(#irZZ6hb)"><ellipse transform="rotate(-27.914 13.515 9.984)" class="uet7_on0c"/><ellipse fill="url(#iw8xT0T)" transform="rotate(-27.914 13.515 9.984)" class="onnu1nb9h"/></g><g filter="url(#iS7Jurd)"><path class="w68d8rf8l"/></g><g filter="url(#i8bAkfc)"><path class="s06kwwb4k"/></g><g filter="url(#i7lDiHe)"><path class="lj52tdi9f"/><path fill="url(#irhlCdB)" class="nnnjanulx"/></g><g filter="url(#i4KE6Td)"><path class="errnutb8q"/><path fill="url(#iS9kzjc)" class="e5h8_5b7g"/><path fill="url(#iYoTv8d)" class="e5h8_5b7g"/></g><g filter="url(#iPM7fre)"><path stroke="url(#iWr5ECD)" class="fbg88hbtx"/></g><g filter="url(#iJ65jBc)"><path class="si-p6m2-f"/></g><g filter="url(#ij6ZBTc)"><path fill="url(#ipC190c)" class="q6bzj5bpc"/><path fill="url(#iQTpXGe)" class="q6bzj5bpc"/></g><defs><radialGradient id="iOdQGdc" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 26.993 6.869)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iQ1CMFc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.572 25.425)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="irX8o2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.014 4.26)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="iBiauqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.668 13.177)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iPJO4Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.851 13.445)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iH7Tded" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.87 8.198)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i0H6VAc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.302 7.681)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ibCNaBb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.058 11.613)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iKaKFyb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.928 6.863)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="itdIbhc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.478 9.825)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ixoHMHd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.622 8.03)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ieXvaCc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.994 -3.71)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i4c3gkd" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.827 9.789)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i55MFDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.01 15.894)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="i6YCJve" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.666 20.425)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="igkrOuc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.728 19.02)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="iCYLN5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.004 28.175)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="i0yWNHb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.468 29.723)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iRcx2bc" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 12.4075 15.197 19.735)" gradientUnits="userSpaceOnUse"><stop class="fqkeoivtf"/><stop offset="1" class="avo9uebvh"/></radialGradient><radialGradient id="i4SFPld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.24 19.384)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="io78xVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.9453 -1.33595 .2433 -.17216 19.682 20.394)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="imsXbUb" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 1.23437 -2.31053 1.46236 17.563 15.625)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="inr0qoc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.525 20.3)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="iycY7fG" cx="0" cy="0" r="1" gradientTransform="rotate(115.498 2.118 12.38)scale(1.12522 2.1062)" gradientUnits="userSpaceOnUse"><stop offset=".211" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iwuFY0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.6875 -2.71875 0 16.438 17.469)" gradientUnits="userSpaceOnUse"><stop class="ghmblzgwj"/><stop offset=".546" class="d_290xb1n"/><stop offset="1" class="zxm3y0btp"/></radialGradient><radialGradient id="iZjvf3b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12893 1.05533 -1.5203 -1.62634 22.646 23.711)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="hkmqqzaeo"/><stop offset="1" class="vo92-0bqu"/></radialGradient><radialGradient id="igkft1d" cx="0" cy="0" r="1" gradientTransform="matrix(.61902 -.52682 .31382 .36874 22.788 23.43)" gradientUnits="userSpaceOnUse"><stop class="wpeyy_b3b"/><stop offset="1" class="cs9siac0p"/></radialGradient><radialGradient id="iGfu3Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 -.29687 .9302 -5.77708 11.103 23.953)" gradientUnits="userSpaceOnUse"><stop class="jgy_mt60r"/><stop offset="1" class="esaylh6lg"/></radialGradient><radialGradient id="iPsTu2A" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67187 0 0 -.65955 12.197 25.305)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="0" class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iARXdfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 0 0 -.60407 12.213 26.586)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iif4Lae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34375 0 0 -.5301 12.26 27.868)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="itrOSAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 0 0 -.59174 12.33 29.227)" gradientUnits="userSpaceOnUse"><stop class="u9ogn5shy"/><stop offset="1" class="ud7n83bkt"/></radialGradient><radialGradient id="iBGl16P" cx="0" cy="0" r="1" gradientTransform="matrix(1.70312 0 0 .67188 21.26 25.305)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="ihjsdzh" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 .64106 21.197 26.586)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="ihLzeXy" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 0 0 .6164 21.103 27.868)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="izvGcfd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4375 0 0 .56709 20.963 29.227)" gradientUnits="userSpaceOnUse"><stop class="eo578gbro"/><stop offset="1" class="cr9drwbam"/></radialGradient><radialGradient id="iSW10hc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.008 11.116)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ia5Eynb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.04 8.995)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iuYcr5R" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.36 10.789)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="i9qxCXb" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.684 5.338)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iBZL7fR" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.828 10.139)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="itZi0Vb" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.814 7.383)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="i3Ncboc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.807 16.646)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="imxGpjc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 16.992 9.723)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="iWejpkT" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.313 6.799)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="icYdnmW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.27 9.72)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iAsmOAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.892 9.492)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="ioUmgAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.352 7.404)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iNI874E" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.064 11.208)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="irpzyEe" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.244 2.46)scale(1.52213 1.61741)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="iZL0pSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.5625 1.85526 2.0779 11.932 15.868)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="igVWbCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.753 11.934)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="inaemwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.514 12.146)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iLg28Ti" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.381 8.311)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="i0LnVQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.15 10.08)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1C5rMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.923 10.164)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iww7RRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.787 10.08)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iw8xT0T" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49406 .59388 -.0093 13.5 10.3)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irhlCdB" cx="0" cy="0" r="1" gradientTransform="matrix(1.26205 -2.75541 1.4096 .64564 10.31 7.959)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iS9kzjc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.075 6.996)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iYoTv8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.178 3.121)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iQTpXGe" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.385 10.08)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><filter id="ipTLM5l" width="27.98" height="21.09" x="2.014" y="3.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="im4fmKb" width="27.413" height="20.785" x="2.678" y="3.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".2"/></filter><filter id="irnahhe" width="27.91" height="20.96" x="2.014" y="3.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iUWaZKd" width="15.268" height="15.768" x="8.46" y="1.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="idCywce" width="2.797" height="14.494" x="18.064" y="15.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iTb5mke" width="2.797" height="14.462" x="11.157" y="15.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iE3E3ie" width="2.1" height="3.39" x="20.957" y="23.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.478431 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iY62SlT" width="2.1" height="3.29" x="8.96" y="23.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.368627 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iAf6Yzd" width="4.793" height="5.391" x="8.96" y="24.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.380392 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="ifCs91d" width="4.793" height="5.591" x="18.464" y="24.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.196078 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1659" result="effect2_innerShadow_4002_1659"/></filter><filter id="ijF41Td" width="2.222" height=".3" x="18.883" y="25.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".05"/></filter><filter id="iboIpbc" width="2.222" height=".3" x="10.87" y="25.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".05"/></filter><filter id="i37lKEb" width="2.222" height=".3" x="18.883" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".05"/></filter><filter id="iwm3Pne" width="2.222" height=".3" x="10.87" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".05"/></filter><filter id="iovNBGd" width="2.222" height=".3" x="18.883" y="28.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".05"/></filter><filter id="iljRBJc" width="2.222" height=".3" x="10.87" y="28.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".05"/></filter><filter id="i3WhYAb" width="3.368" height="3.218" x="9.674" y="9.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iNXT5hb" width="3.218" height="3.468" x="19.187" y="8.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iIKoSQc" width="3.148" height="3.148" x="19.222" y="9.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".25"/></filter><filter id="i3ZpCAm" width="2.648" height="2.648" x="9.978" y="9.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".125"/></filter><filter id="iR7uaee" width="10.191" height="11.127" x="10.873" y="5.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="i6as2od" width="2.877" height="3.682" x="14.368" y="9.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".25"/></filter><filter id="i7qrVmc" width="2.377" height="3.182" x="14.78" y="9.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".125"/></filter><filter id="iBDaf1Y" width="3.001" height="1.285" x="16.911" y="9.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iYMzr6d" width="3.001" height="1.285" x="12.025" y="9.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="ijCmN3M" width="2.453" height="1.091" x="12.161" y="7.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="i68eN7d" width="2.453" height="1.091" x="17.578" y="7.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/></filter><filter id="iqO5tXd" width=".787" height=".696" x="17.417" y="9.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".05"/></filter><filter id="iW5ki1d" width=".891" height=".913" x="18.256" y="9.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".1"/></filter><filter id="ieSOFhj" width=".986" height="1.04" x="13.814" y="9.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".1"/></filter><filter id="irZZ6hb" width=".913" height=".705" x="13.059" y="9.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".05"/></filter><filter id="iS7Jurd" width="2.661" height="1.378" x="17.408" y="7.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".2"/></filter><filter id="i8bAkfc" width="2.661" height="1.378" x="11.957" y="7.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".2"/></filter><filter id="i7lDiHe" width="4.312" height="4.613" x="9.614" y="3.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/><feGaussianBlur result="effect2_foregroundBlur_4002_1659" stdDeviation=".2"/></filter><filter id="i4KE6Td" width="8.767" height="5.782" x="12.798" y="2.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/><feGaussianBlur result="effect2_foregroundBlur_4002_1659" stdDeviation=".125"/></filter><filter id="iPM7fre" width="1.145" height="2.31" x="12.777" y="3.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".1"/></filter><filter id="iJ65jBc" width="6.927" height="3.872" x="15.137" y="4.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1659" stdDeviation=".5"/></filter><filter id="ij6ZBTc" width="10.29" height="4.16" x="10.894" y="8.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.381221 0 0 0 0 0.2699 0 0 0 0 0.482422 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1659"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1659" result="effect2_innerShadow_4002_1659"/></filter><linearGradient id="ivtLrRb" x1="11.828" x2="31.271" y1="4.549" y2="22.785" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="inX0Zgb" x1="30.072" x2="9.135" y1="13.237" y2="13.237" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="iBfQ7vd" x1="13.447" x2="31.26" y1="3.49" y2="24.302" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="isx28Rb" x1="-4.897" x2="28.916" y1="25.581" y2="25.581" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="ikSiUzN" x1="3.103" x2="3.103" y1="5.143" y2="23.581" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iQEnTFQ" x1="20.662" x2="13.857" y1="3.724" y2="16.328" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="ijNUtce" x1="25.183" x2="25.183" y1="30.394" y2="26.578" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="i7eiRCQ" x1="22.416" x2="23.228" y1="29.206" y2="29.19" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="izQuehc" x1="7.144" x2="9.538" y1="28.087" y2="28.087" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="ivhS0Mc" x1="18.064" x2="20.86" y1="18.315" y2="18.315" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iF4mJXa" x1="13.954" x2="11.157" y1="18.315" y2="18.315" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iWYbeAc" x1="12.119" x2="12.681" y1="16.878" y2="17.097" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="i8AOzjX" x1="21.853" x2="17.478" y1="24.737" y2="24.737" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="iWwXged" x1="10.324" x2="10.752" y1="23.519" y2="23.519" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="iydzz9c" x1="12.51" x2="8.572" y1="27.956" y2="27.956" gradientUnits="userSpaceOnUse"><stop class="y7rb0nbsx"/><stop offset="1" class="j4pe32lse"/></linearGradient><linearGradient id="iq2m47c" x1="22.478" x2="18.664" y1="27.55" y2="27.55" gradientUnits="userSpaceOnUse"><stop class="c1fnikbua"/><stop offset=".807" class="y9fu8v2us"/></linearGradient><linearGradient id="iLSJzjd" x1="10.791" x2="21.664" y1="21.893" y2="21.893" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="io4h0vb" x1="16.41" x2="16.41" y1="20.956" y2="22.128" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="iQetH0c" x1="19.033" x2="20.861" y1="26.058" y2="26.058" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="ikJ9fhb" x1="12.942" x2="10.744" y1="26.058" y2="26.058" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="iQlsbNE" x1="19.033" x2="20.861" y1="27.323" y2="27.323" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="i8ILMuc" x1="12.942" x2="10.744" y1="27.323" y2="27.323" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="i21TZxc" x1="19.033" x2="20.861" y1="28.589" y2="28.589" gradientUnits="userSpaceOnUse"><stop class="kn1yo7csr"/><stop offset="1" class="gugba3b_v"/><stop offset="1" class="gom2jbmdj"/></linearGradient><linearGradient id="isAozxd" x1="12.942" x2="10.744" y1="28.589" y2="28.589" gradientUnits="userSpaceOnUse"><stop class="oh-_iua0g"/><stop offset="1" class="owl7p83et"/></linearGradient><linearGradient id="i06TBYd" x1="9.725" x2="10.966" y1="10.764" y2="10.764" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iHQooXi" x1="15.03" x2="15.969" y1="12.008" y2="12.008" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iI3pBec" x1="15.969" x2="15.969" y1="12.806" y2="12.196" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="i40lRxc" x1="16.047" x2="16.047" y1="12.78" y2="12.641" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iSnQlze" x1="14.904" x2="15.365" y1="14.216" y2="13.504" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iiuDfNb" x1="18.929" x2="18.615" y1="10.133" y2="10.326" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iOLUx5b" x1="14.53" x2="14.217" y1="10.133" y2="10.326" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWr5ECD" x1="13.078" x2="13.622" y1="4.478" y2="5.752" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="ipC190c" x1="16.089" x2="16.089" y1="8.976" y2="12.758" gradientUnits="userSpaceOnUse"><stop class="os93-qygj"/><stop offset="1" class="foz7ccc1o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-teacher-medium-dark" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a6bak5b_z {
  d: path("M11.302 11.75a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.149");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.avba2dppg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.36 9.33c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.272c.125-.64.69-1.127 1.37-1.127");
}

.avo9uebvh {
  stop-color: var(--svg-color--544b50, #544B50);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.b-v92n1ix {
  d: path("M18.948 10.377a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b87lf7bgc {
  d: path("M29.004 23.93H3.014V4.94l-.92-.68c-.05.09-.08.2-.08.3V24.3c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bfz-gkb2h {
  d: path("M13.785 9.602a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c0jwnxbqr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 28.51h1.922");
}

.c1fnikbua {
  stop-color: var(--svg-color--997266, #997266);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c5-_gr0ru {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 27.245H11.02");
}

.c6magac4y {
  d: path("m12.688 15.945l-1.384 2.984c-.09.19.05.41.26.41l.963-.266c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V15.578z");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
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

.cr9drwbam {
  stop-color: var(--svg-color--9a7469, #9A7469);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cs9siac0p {
  stop-color: var(--svg-color--9c7c74, #9C7C74);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d_290xb1n {
  stop-color: var(--svg-color--593731, #593731);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dpicrc-fd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 25.98h1.922");
}

.dzknzyhpx {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.418 29.94v-8.406h-2.094v8.406z");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e5h8_5b7g {
  d: path("M15.365 2.886c-1.132-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.744.542 1.878.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.ei57c5neo {
  d: path("M9.304 29.94V17.696a10.98 10.98 0 0 0-4.32 8.744v3.5z");
}

.em-du1blu {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.796 11.75a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.149");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eo578gbro {
  stop-color: var(--svg-color--9c7b74, #9C7B74);
}

.errnutb8q {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.365 2.886c-1.132-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.744.542 1.878.888c0-3.933-3.344-4.67-5.922-5.24z");
}

.esaylh6lg {
  stop-color: var(--svg-color--684844, #684844);
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.fbg88hbtx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.078 4.135c.023.243.234 1.156.544 1.71");
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.foz7ccc1o {
  stop-color: var(--svg-color--251732, #251732);
}

.fqkeoivtf {
  stop-color: var(--svg-color--aba5a8, #ABA5A8);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ghmblzgwj {
  stop-color: var(--svg-color--644640, #644640);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gom2jbmdj {
  stop-color: var(--svg-color--643037, #643037);
  stop-opacity: 0;
}

.gugba3b_v {
  stop-color: var(--svg-color--33141c, #33141C);
  stop-opacity: 0;
}

.hkmqqzaeo {
  stop-color: var(--svg-color--8b625a, #8B625A);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hl-fmab0h {
  d: path("m19.324 15.938l1.39 2.99c.09.19-.05.41-.26.41l-.964-.265c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.547z");
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.imhyssb0r {
  d: path("M22.684 29.94V17.696a10.98 10.98 0 0 1 4.32 8.744v3.5z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4pe32lse {
  stop-color: var(--svg-color--744c4b, #744C4B);
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jd5-gflla {
  d: path("M21.664 22.925v-2.286c0-.388-.36-.699-.81-.699h-8.659c-1.041 0-1.871.73-1.871 1.622c0 .752.61 1.363 1.363 1.363z");
}

.jgy_mt60r {
  stop-color: var(--svg-color--512a20, #512A20);
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jpq_dkbzf {
  d: path("M9.96 23.04c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.juf3zkb2c {
  d: path("M10.324 21.82v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.jxgb-l3au {
  fill-rule: evenodd;
  d: path("M23.154 12.086c.212-.435.324-.92.324-1.427c0-.467-.096-.906-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.456.232l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.772l-.002.003a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.455m-12.26-2.672h-.012l1.198 2.355c.123 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.053-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.189-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.19 1.235l-.051.02q-.028.013-.051.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k3o8yr4tm {
  d: path("M18.153 9.602a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.k3yhup92u {
  d: path("M20.796 12.286a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kdhqs4bai {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.571 8.899l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.009-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.109a.268.268 0 1 1-.094.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.194");
}

.ke-6vubux {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.7 8.441l-.138.23za.268.268 0 0 1-.275.46L19.42 8.9a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.094-.528c.514-.09.989.001 1.329.11a3.3 3.3 0 0 1 .558.238l.01.005z");
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kn1yo7csr {
  stop-color: var(--svg-color--643037, #643037);
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
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

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.lj52tdi9f {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.9 4.688c.565-.6 1.636-.6 2.13-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.261-1.989 1.956-2.703 2.146c-.149-1.492.109-2.38.845-3.16");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.llpp05cwb {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.586 10.315l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.lmazyohix {
  fill: var(--svg-color--000, #000);
  d: path("M14.296 10.495a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
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

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.na7m58bfk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.228 4.334h26.213a.1.1 0 0 1 .1.1v19.585");
}

.nbqq-1b8f {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.827 10.107c-.266-.467-.67-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.27.218-.233.496-.025.6l.556.317c.652-.21 1.373-.24 2.079-.45");
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nnnjanulx {
  d: path("M10.9 4.688c.565-.6 1.636-.6 2.13-.51l.396 1.29c-.253-.04-.478.05-.668.234c-.448 1.261-1.989 1.956-2.703 2.146c-.149-1.492.109-2.38.845-3.16");
}

.ns1-y9bit {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 28.51H11.02");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.oh-_iua0g {
  stop-color: var(--svg-color--7a4f45, #7A4F45);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.onnu1nb9h {
  cx: 13.515px;
  cy: 9.984px;
  rx: 0.39px;
  ry: 0.197px;
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.os93-qygj {
  stop-color: var(--svg-color--402857, #402857);
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.owl7p83et {
  stop-color: var(--svg-color--7a4f45, #7A4F45);
  stop-opacity: 0;
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.phdxp8s-u {
  d: path("M11.157 21.432c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q-6-rea_l {
  d: path("M14.6 10.39c0-.289-.234-.48-.298-.539l-.288.279l.177.361z");
}

.q1qzdin-x {
  d: path("M18.064 16.078h-4.11V29.94h4.11z");
}

.q6bzj5bpc {
  d: path("M20.844 8.57h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91V9.51c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65V9.8c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65V9.8c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.qbh01rbob {
  d: path("M20.796 11.75a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.149");
}

.qkdlpxbzm {
  fill-rule: evenodd;
  d: path("M12.418 29.94v-8.406h-2.094v8.406z");
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r1gp83b4g {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.302 11.75a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.149");
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rk3ub_0wu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.087 9.791c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.051");
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.rzbdi_r-e {
  d: path("M11.283 12.286a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.s06kwwb4k {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.117 8.304c-.322-.079-1.124-.04-1.66.344");
}

.s0msj2bhb {
  d: path("M29.384 24.93H2.634c-.34 0-.62-.28-.62-.62V4.56c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62V24.3a.61.61 0 0 1-.61.63");
}

.s85b50mwh {
  d: path("M18.664 25.31a.81.81 0 0 0 .303.667a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.8.8 0 0 0-.303.637c0 .267.116.503.303.636a.84.84 0 0 0-.303.668c.01.42.32.75.685.75h2.935c.426 0 .773-.401.773-.894v-3.604c0-.493-.347-.893-.773-.893h-2.842c-.475 0-.77.39-.778.76");
}

.si-p6m2-f {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m18.375 6.496l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sklvyriza {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.635 13.49a.2.2 0 0 0-.02-.25a.205.205 0 0 0-.248-.041c-.404.216-.88.339-1.398.339a3 3 0 0 1-1.398-.339a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248m3.332 0l-.042-.027zm0 0a1.982 1.982 0 0 1-3.333 0m0 0l.042-.027m-.042.027l.042-.027m0 0a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22a3 3 0 0 1-1.421.345c-.521 0-1.01-.125-1.422-.345c-.14-.073-.291.089-.203.22Z");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tbojtxbws {
  d: path("M18.087 9.791c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107s.007-.245.159-.358c.15-.113.325-.136.388-.051");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u-aqhqb6h {
  d: path("M3.014 23.93V4.94h25.99v18.99z");
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

.uet7_on0c {
  cx: 13.515px;
  cy: 9.984px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.uhoem0bpa {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.576 10.454l-.683 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.494-.376-.613 0");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ujeoxvv-i {
  d: path("M13.353 25.31a.81.81 0 0 1-.302.667a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636a.8.8 0 0 1 .302.637a.77.77 0 0 1-.302.636c.187.144.302.39.302.668c-.009.42-.32.75-.684.75H9.734c-.427 0-.774-.401-.774-.894v-3.604c0-.493.347-.893.774-.893h2.842c.475 0 .77.39.777.76");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
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

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vmd9ttl4n {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.11 10.107c.266-.467.67-.835 1.538-.835c.38 0 .747.105 1.073.368c.269.218.233.496.025.6l-.556.317c-.652-.21-1.373-.24-2.08-.45");
}

.vo92-0bqu {
  stop-color: var(--svg-color--724838, #724838);
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.w68d8rf8l {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.908 8.304c.323-.079 1.125-.04 1.661.344");
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wnc9k4m5a {
  d: path("M10.882 9.414h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.119 3.073c-.123 2.803-2.311 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.wpeyy_b3b {
  stop-color: var(--svg-color--9c7c74, #9C7C74);
}

.wpud2mb_p {
  d: path("M16.014 18.61c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
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

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.x7se-rbeq {
  fill: var(--svg-color--000, #000);
  d: path("M17.642 10.495c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xgyop8b4p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 27.245h1.922");
}

.xjvebdcyn {
  d: path("M22.057 23.048c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.xlgofpbrt {
  d: path("m15.586 10.315l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.766 0");
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y7rb0nbsx {
  stop-color: var(--svg-color--895b5e, #895B5E);
}

.y9fu8v2us {
  stop-color: var(--svg-color--6f4446, #6F4446);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yfm3e8b8e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 25.98H11.02");
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z3_920cft {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.578 9.33c-.653 0-1.205.45-1.355 1.06c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

.zvr9x85bv {
  d: path("M16.014 15.44c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.zxm3y0btp {
  stop-color: var(--svg-color--3e201c, #3E201C);
}

</style>
