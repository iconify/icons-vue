<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#inpr3XX)" class="xhfi2bchw"/><path fill="url(#icMYfae)" class="xhfi2bchw"/><path fill="url(#iC9d4Fc)" class="xhfi2bchw"/><path fill="url(#iaKbSFc)" class="xhfi2bchw"/><path fill="url(#ifFsvnb)" class="xhfi2bchw"/><path fill="url(#iU0zVNz)" class="xhfi2bchw"/><path fill="url(#i9gb1Nd)" class="xhfi2bchw"/><path fill="url(#iNZLvce)" class="xhfi2bchw"/><path fill="url(#ihXn1tj)" class="xhfi2bchw"/><path fill="url(#i0OCvZd)" class="xhfi2bchw"/><path fill="url(#iW7ue6b)" class="xhfi2bchw"/><path fill="url(#ikSxOKb)" class="lvhlipbcn"/><path fill="url(#iwK1Awd)" class="lvhlipbcn"/><path class="v464v-byy"/><path fill="url(#iEMmtzd)" class="bo6t5uoqn"/><path fill="url(#inpUZxo)" class="bo6t5uoqn"/><path fill="url(#iudkqNs)" class="ahuyesbzw"/><path fill="url(#iFWvNwd)" class="ahuyesbzw"/><path fill="url(#i3v54qU)" class="ahuyesbzw"/><path fill="url(#ii5aY1b)" class="ahuyesbzw"/><path fill="url(#iwIFhlc)" class="bo6t5uoqn"/><path fill="url(#iN18Nvb)" class="sqok2nb6k"/><path fill="url(#iMUxmCc)" class="sqok2nb6k"/><g filter="url(#iRPTWnb)"><path stroke="url(#iOzHyyc)" class="hdwjo0b_s"/></g><g filter="url(#iuFNGse)"><path stroke="url(#iJx8kEL)" class="sagpcsbuz"/></g><g filter="url(#ixTnH7b)"><path stroke="url(#ipQzLke)" class="d0trwkb9r"/></g><g filter="url(#iOpq7Vc)"><path stroke="url(#ih1zr3H)" class="huew6ibyl"/></g><g filter="url(#i16FwSd)"><path stroke="url(#i0NdE2c)" class="x2di_yb4v"/></g><g filter="url(#iSr5xke)"><path stroke="url(#iiNB1bc)" class="sqbaubcdg"/></g><g filter="url(#inOdfhC)"><path stroke="url(#iKhLdZb)" class="k8sjt8bhr"/></g><g filter="url(#irrArad)"><path stroke="url(#iFVR7Mb)" class="taxaeh_ti"/></g><g filter="url(#i3rwtPe)"><path stroke="url(#iMXxZRo)" class="v_9t1abnj"/></g><g filter="url(#iugf0Be)"><path stroke="url(#ipeie5d)" class="v5qxzgbhb"/></g><g filter="url(#ikH8vnd)"><path stroke="url(#i4MFk7b)" class="a5zbgho-l"/></g><path fill="url(#i4mp8ae)" class="h195g1fyn"/><path fill="url(#iQEQvCI)" class="utl9bkbgg"/><g filter="url(#ifG4i1c)"><path fill="url(#iOcSgnc)" class="tb7s17bnz"/><path fill="url(#iyLecSp)" class="tb7s17bnz"/></g><path fill="url(#i26MJSd)" class="tb7s17bnz"/><path fill="url(#imKXhnb)" class="tb7s17bnz"/><path fill="url(#iagZKlb)" class="tb7s17bnz"/><path fill="url(#idYtkxA)" class="tb7s17bnz"/><path fill="url(#iMEwjUb)" class="tb7s17bnz"/><path fill="url(#i3PvLZb)" class="tb7s17bnz"/><path fill="url(#ijcmiOc)" class="tb7s17bnz"/><path fill="url(#iBXH7Ld)" class="tb7s17bnz"/><g filter="url(#iTB4NLG)"><path class="j9seiccox"/></g><g filter="url(#iuXUDSd)"><path class="wwhpuyv6h"/><path fill="url(#iFKpujb)" class="n3ywyofxa"/><path fill="url(#i7gjJqd)" class="n3ywyofxa"/><path fill="url(#ie384Bb)" class="n3ywyofxa"/><path fill="url(#i5wO3ge)" class="n3ywyofxa"/><path fill="url(#inFoMCc)" class="n3ywyofxa"/></g><path fill="url(#ia3EIXT)" class="n3ywyofxa"/><path fill="url(#i9yR3uc)" class="n3ywyofxa"/><g filter="url(#ig15d9c)"><path stroke="url(#isYXEbd)" class="tf_datbeu"/></g><path fill="url(#iLFzmPe)" class="dfm6_kbwi"/><g filter="url(#iXSudOL)"><path fill="url(#ic4Xr5c)" class="qy040r_9h"/></g><path fill="url(#ik1vOod)" class="qy040r_9h"/><path fill="url(#i9XLRoc)" class="qy040r_9h"/><path fill="url(#iWmSA6b)" class="qy040r_9h"/><g filter="url(#iwgUZjc)"><path class="lyn31cv5k"/></g><g filter="url(#irEQmIe)"><path class="ulaau23tp"/></g><g filter="url(#iK5202c)"><path class="ayzpbrb0j"/><path fill="url(#iVTAyqd)" class="eakj5994q"/><path fill="url(#iWJtEdb)" class="eakj5994q"/></g><g filter="url(#i6YI0wj)"><path class="y4b2vhoje"/><path fill="url(#iKjMWyc)" class="pqhb10bsd"/><path fill="url(#imfA1Nd)" class="pqhb10bsd"/><path fill="url(#ikaoNPe)" class="pqhb10bsd"/></g><path class="mz5dt6b2t"/><path fill="url(#i5JUVNc)" class="apl4g7z7j"/><path class="ysdl-nbld"/><g filter="url(#ibIRd7d)"><path class="zdnxfcblz"/><path fill="url(#iOaDwLd)" class="i-5nkkbze"/></g><g filter="url(#iitmXbd)"><path fill="url(#iAzp9ie)" class="uuaw3bblr"/></g><path class="noh-lsb2k"/><path fill="url(#iKKmrDd)" class="wvudz1buv"/><path class="m9ambcb1f"/><g filter="url(#iHkg4gc)"><path fill="url(#iZFw5yK)" class="tado7838v"/></g><g filter="url(#iSKEPvd)"><ellipse transform="rotate(-27.914 16.109 12.952)" class="flv9kibjx"/><ellipse fill="url(#iYMarmc)" transform="rotate(-27.914 16.109 12.952)" class="h7y0qfmyd"/></g><path fill="url(#i7bR6Mc)" class="rn15rw1rx"/><path fill="url(#idjJaCb)" class="rn15rw1rx"/><path fill="url(#iAq3hAb)" class="rn15rw1rx"/><path fill="url(#iSlMtre)" class="rn15rw1rx"/><path fill="url(#iAUgBsb)" class="arhuoxthx"/><path fill="url(#i8hcgxb)" class="arhuoxthx"/><g filter="url(#iiXZome)"><path fill="url(#i1KkAPe)" class="bikfv86uz"/></g><g filter="url(#i1BaR3b)"><path fill="url(#iCD908J)" class="ghcnbvbks"/></g><g filter="url(#i9t0TSc)"><path class="e8-60tbca"/></g><g filter="url(#iyTmn2b)"><path class="ytohzbchu"/></g><g filter="url(#i1RGGLe)"><path class="hm6v1m56v"/></g><defs><radialGradient id="inpr3XX" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 5.87 11.832)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="pr1c_plua"/><stop offset="1" class="qdtuxcc3i"/></radialGradient><radialGradient id="icMYfae" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 2.789 7.295)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="h0kcnqbkf"/><stop offset="1" class="kybxapb2q"/></radialGradient><radialGradient id="iaKbSFc" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.596 5.02)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="ifFsvnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.243 3.856)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="iU0zVNz" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 8.213 3.09)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="i9gb1Nd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 9.712 3.45)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="iNZLvce" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 7.785 2.422)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="ihXn1tj" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.594 3.913)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="i0OCvZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 3.97 4.237)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="iW7ue6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09125 1.09125 -.85394 -.85394 12.007 6.719)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="iEMmtzd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.71543 2.79839 -2.98394 -9.29332 26.183 27.15)" gradientUnits="userSpaceOnUse"><stop class="ip469ff8c"/><stop offset="1" class="v0q_-i93u"/></radialGradient><radialGradient id="inpUZxo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.66619 0 10.916 29.949)" gradientUnits="userSpaceOnUse"><stop class="xjv40os-m"/><stop offset="1" class="yrxkt-bta"/></radialGradient><radialGradient id="iFWvNwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 2.979 12.949)" gradientUnits="userSpaceOnUse"><stop class="ya78f26qa"/><stop offset="1" class="jfma4ebms"/></radialGradient><radialGradient id="i3v54qU" cx="0" cy="0" r="1" gradientTransform="matrix(-7.94466 -1.83797 .619 -2.67566 16.993 21.251)" gradientUnits="userSpaceOnUse"><stop class="q2kyq2xrt"/><stop offset="1" class="wogt4ot2h"/></radialGradient><radialGradient id="iwIFhlc" cx="0" cy="0" r="1" gradientTransform="rotate(101.634 -.19 15.867)scale(4.33914 9.98002)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="l24x8zb-x"/><stop offset="1" class="chnw0fb8n"/></radialGradient><radialGradient id="iMUxmCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92844 -2.47995 0 19.011 21.136)" gradientUnits="userSpaceOnUse"><stop class="ta-g5n7qo"/><stop offset="1" class="kyf2fxbmx"/></radialGradient><radialGradient id="i4mp8ae" cx="0" cy="0" r="1" gradientTransform="matrix(.88576 2.38902 -2.83797 1.05222 24.635 15.263)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iQEQvCI" cx="0" cy="0" r="1" gradientTransform="matrix(1.7466 .54892 -1.69346 5.38834 11.847 15.842)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iOcSgnc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.56584 0 0 -9.84591 22.332 14.15)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iyLecSp" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 8.612 10.3)scale(3.98535 3.29023)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="imKXhnb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20925 14.69643 -12.17037 -1.0014 20.882 7.154)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="iagZKlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.35845 1.68108 0 21.906 12.596)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="idYtkxA" cx="0" cy="0" r="1" gradientTransform="matrix(.00465 -1.29448 1.4087 .00506 16.29 12.651)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iMEwjUb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 11.295 8.023)scale(10.0704 25.7247)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i3PvLZb" cx="0" cy="0" r="1" gradientTransform="matrix(4.00524 -3.45004 1.01909 1.18308 10.977 10.916)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="ijcmiOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2776 2.95435 -1.18098 -.11097 25.571 10.7)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iBXH7Ld" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03105 -1.97932 0 16.39 13.563)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i7gjJqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .28876 -.90754 0 19.563 15.759)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="i5wO3ge" cx="0" cy="0" r="1" gradientTransform="rotate(156.092 8.253 9.628)scale(2.18949 3.51869)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="i9yR3uc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51683 1.44744 -2.089 -2.18915 19.523 14.743)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iLFzmPe" cx="0" cy="0" r="1" gradientTransform="matrix(2.58118 -1.26898 5.10546 10.38476 18.43 18.435)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ik1vOod" cx="0" cy="0" r="1" gradientTransform="rotate(-69.027 14.763 -2.978)scale(9.05771 12.8528)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="i9XLRoc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79729 -7.75279 11.00115 -2.55034 25.721 11.943)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iWmSA6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33913 -2.8192 3.32812 -1.58088 22.831 6.868)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iVTAyqd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.60383 0 0 -.96638 19.311 5.642)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iWJtEdb" cx="0" cy="0" r="1" gradientTransform="matrix(3.80699 -6.02764 6.678 4.21775 12.587 10.305)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iKjMWyc" cx="0" cy="0" r="1" gradientTransform="matrix(4.15832 -3.3478 5.18837 6.4445 21.28 8.666)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="imfA1Nd" cx="0" cy="0" r="1" gradientTransform="matrix(3.5002 -3.13272 5.73521 6.40795 22.127 10.154)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="ikaoNPe" cx="0" cy="0" r="1" gradientTransform="matrix(3.81534 .85663 -.35866 1.59741 21.106 8)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="i5JUVNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .95975 -1.5266 0 21.592 13.065)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iOaDwLd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.885 1.36)scale(.4475 .61609)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKKmrDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9598 -1.52667 0 16.43 13.065)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iYMarmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00915 -.58448 .70257 -.011 16.091 13.325)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idjJaCb" cx="0" cy="0" r="1" gradientTransform="matrix(.74355 2.65369 -2.53182 .7094 24.474 13.082)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iAq3hAb" cx="0" cy="0" r="1" gradientTransform="matrix(.9319 -1.2789 1.07197 .78113 24.9 13.726)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iSlMtre" cx="0" cy="0" r="1" gradientTransform="matrix(.6944 -1.83408 2.45058 .9278 25.035 13.93)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="i8hcgxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96164 0 0 -2.19045 13.196 13.84)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i1KkAPe" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 6.01 7.484)scale(1.10001 1.12785)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><linearGradient id="iC9d4Fc" x1="6.354" x2="6.354" y1="12.493" y2="10.79" gradientUnits="userSpaceOnUse"><stop class="sy2nhlbqj"/><stop offset="1" class="o6qx6mc1p"/></linearGradient><linearGradient id="ikSxOKb" x1="4.197" x2="8.572" y1="12.511" y2="12.511" gradientUnits="userSpaceOnUse"><stop class="zmcsd8b9p"/><stop offset=".743" class="zdo6gqojl"/></linearGradient><linearGradient id="iwK1Awd" x1="6.467" x2="6.467" y1="11.925" y2="12.183" gradientUnits="userSpaceOnUse"><stop class="p4ezwj49r"/><stop offset="1" class="q3td6tqwm"/></linearGradient><linearGradient id="iudkqNs" x1="9.464" x2="11.42" y1="26.617" y2="20.332" gradientUnits="userSpaceOnUse"><stop class="b05_udben"/><stop offset="1" class="a91fxs_hx"/></linearGradient><linearGradient id="ii5aY1b" x1="13.703" x2="13.313" y1="24.393" y2="23.784" gradientUnits="userSpaceOnUse"><stop offset=".312" class="b2wdmyb-l"/><stop offset="1" class="pmtca2xis"/></linearGradient><linearGradient id="iN18Nvb" x1="17.281" x2="20.688" y1="21.034" y2="23.949" gradientUnits="userSpaceOnUse"><stop class="tiw8muhjk"/><stop offset="1" class="z7_258bha"/></linearGradient><linearGradient id="iOzHyyc" x1="7.01" x2="12.76" y1="15.23" y2="23.511" gradientUnits="userSpaceOnUse"><stop class="gokcfhb1a"/><stop offset="1" class="sq9q63bos"/></linearGradient><linearGradient id="iJx8kEL" x1="4.844" x2="3.892" y1="5.187" y2="6.972" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="ipQzLke" x1="6.264" x2="4.963" y1="4.757" y2="5.737" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="ih1zr3H" x1="8.023" x2="7.641" y1="5.357" y2="6.922" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="i0NdE2c" x1="3.609" x2="4.029" y1="5.299" y2="7.906" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="iiNB1bc" x1="4.754" x2="4.966" y1="4.426" y2="7.549" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="iKhLdZb" x1="6.903" x2="8.006" y1="3.669" y2="7.346" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="iFVR7Mb" x1="7.858" x2="8.174" y1="4.619" y2="8.05" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="iMXxZRo" x1="4.904" x2="3.812" y1="7.166" y2="7.098" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="ipeie5d" x1="6.176" x2="5.612" y1="6.994" y2="6.853" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="i4MFk7b" x1="7.677" x2="6.874" y1="6.808" y2="6.594" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="i26MJSd" x1="25.112" x2="22.12" y1="16.143" y2="16.143" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iFKpujb" x1="20.003" x2="19.011" y1="14.947" y2="14.989" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="ie384Bb" x1="19.011" x2="19.011" y1="16.295" y2="15.745" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="inFoMCc" x1="19.011" x2="19.011" y1="13.095" y2="13.742" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="ia3EIXT" x1="19.503" x2="19.503" y1="16.458" y2="16.23" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="isYXEbd" x1="17.59" x2="17.966" y1="18.153" y2="17.166" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="ic4Xr5c" x1="27.117" x2="13.38" y1="7.45" y2="7.45" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iAzp9ie" x1="22.513" x2="22.142" y1="13.129" y2="13.358" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZFw5yK" x1="17.31" x2="16.939" y1="13.129" y2="13.358" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7bR6Mc" x1="26.625" x2="25.197" y1="13.161" y2="15.735" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iAUgBsb" x1="12.091" x2="13.816" y1="13.994" y2="13.843" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iCD908J" x1="25.462" x2="25.462" y1="12.795" y2="14.875" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><filter id="iRPTWnb" width="9.217" height="12.757" x="5.354" y="12.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".75"/></filter><filter id="iuFNGse" width=".423" height="2.22" x="4.45" y="5.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".05"/></filter><filter id="ixTnH7b" width=".345" height="2.572" x="6.005" y="4.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".05"/></filter><filter id="iOpq7Vc" width=".509" height="1.681" x="7.482" y="5.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".05"/></filter><filter id="i16FwSd" width="1.556" height="3.487" x="3.316" y="4.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".2"/></filter><filter id="iSr5xke" width="1.2" height="3.889" x="5.002" y="3.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".2"/></filter><filter id="inOdfhC" width="1.488" height="4.773" x="6.549" y="2.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".2"/></filter><filter id="irrArad" width="2.002" height="4.299" x="7.952" y="3.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".2"/></filter><filter id="i3rwtPe" width="1.413" height="1.358" x="3.606" y="6.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".1"/></filter><filter id="iugf0Be" width="1.118" height=".999" x="5.255" y="6.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".1"/></filter><filter id="ikH8vnd" width="1.312" height="1.023" x="6.52" y="6.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".1"/></filter><filter id="ifG4i1c" width="13.09" height="14.8" x="13.022" y="6.849" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3868" result="effect2_innerShadow_4002_3868"/></filter><filter id="iTB4NLG" width="4.066" height="5.431" x="16.81" y="12.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".5"/></filter><filter id="iuXUDSd" width="2.621" height="3.831" x="17.701" y="12.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".1"/></filter><filter id="ig15d9c" width="4.307" height="1.769" x="16.858" y="16.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".05"/></filter><filter id="iXSudOL" width="15.228" height="9.794" x="11.397" y="3.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3868" result="effect2_innerShadow_4002_3868"/></filter><filter id="iwgUZjc" width="2.748" height="1.372" x="20.891" y="9.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3868"/></filter><filter id="irEQmIe" width="2.748" height="1.354" x="14.673" y="9.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3868"/></filter><filter id="iK5202c" width="8.198" height="7.497" x="11.614" y="4.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3868"/><feGaussianBlur result="effect2_foregroundBlur_4002_3868" stdDeviation=".25"/></filter><filter id="i6YI0wj" width="8.48" height="7.241" x="18.573" y="4.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3868"/><feGaussianBlur result="effect2_foregroundBlur_4002_3868" stdDeviation=".25"/></filter><filter id="ibIRd7d" width=".894" height=".787" x="20.742" y="12.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".05"/></filter><filter id="iitmXbd" width=".981" height="1.007" x="21.754" y="12.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".1"/></filter><filter id="iHkg4gc" width="1.094" height="1.157" x="16.498" y="12.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".1"/></filter><filter id="iSKEPvd" width="1.044" height=".797" x="15.587" y="12.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".05"/></filter><filter id="iiXZome" width="1.481" height="2.723" x="11.864" y="12.481" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".125"/></filter><filter id="i1BaR3b" width="1.953" height="3.079" x="24.485" y="12.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".25"/></filter><filter id="i9t0TSc" width="2.708" height="1.235" x="14.646" y="9.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".125"/></filter><filter id="iyTmn2b" width="2.708" height="1.235" x="20.935" y="9.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".125"/></filter><filter id="i1RGGLe" width="6.575" height="3.829" x="20.1" y="5.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3868" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-raising-hand-medium" /></template>
<style>
.a53shnb1b {
  stop-color: var(--svg-color--724736, #724736);
}

.a5zbgho-l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.532 6.814c-.13.165-.5.36-.712.423");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.a91fxs_hx {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
  stop-opacity: 0;
}

.ahuyesbzw {
  d: path("m18.37 21.058l-7.875 5.246a.66.66 0 0 0-.4-.48l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.936-1.014h4.129c.52 0 .935.461.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.apl4g7z7j {
  d: path("M21.595 12.5a1.056 1.056 0 0 1 1.017 1.335h-2.04a1.06 1.06 0 0 1 1.022-1.334");
}

.arhuoxthx {
  d: path("M13.044 11.945a1.92 1.92 0 0 0-1.647 1.89c0 1.016.797 1.846 1.8 1.9a93 93 0 0 1-.153-3.79");
}

.ayzpbrb0j {
  fill: var(--svg-color--533634, #533634);
  d: path("M19.286 7.506a3 3 0 0 1-.078-.162a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.953 1.79-3.953 3.998v.325c-.402-.306-.908-.952-.908-1.997c0-1.268.925-1.908 1.515-2.317c.167-.116.306-.213.391-.3l.118-.124c.414-.438 1.15-1.22 2.437-1.561a6.6 6.6 0 0 1 1.932-.19c.472.021.805.43.805.902V7.49z");
}

.b05_udben {
  stop-color: var(--svg-color--ff4b54, #FF4B54);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b2wdmyb-l {
  stop-color: var(--svg-color--ff611d, #FF611D);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bikfv86uz {
  d: path("M12.995 12.731a1.13 1.13 0 0 0 .099 2.223a92 92 0 0 1-.099-2.223");
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bo6t5uoqn {
  d: path("M20.038 20.949h.973c2.5 0 7.5 3.5 7.5 9h-18v-3.5a.67.67 0 0 0-.416-.625l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.936-1.014h4.129c.52 0 .935.461.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.chnw0fb8n {
  stop-color: var(--svg-color--b64318, #B64318);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d0trwkb9r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.213 4.754l-.07 2.296");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dfm6_kbwi {
  d: path("M19.011 17.576c-.6 0-1.164-.142-1.639-.389c-.162-.082-.336.1-.234.247a2.24 2.24 0 0 0 1.873 1.001c.787 0 1.477-.4 1.873-1c.102-.154-.072-.33-.234-.248a3.54 3.54 0 0 1-1.639.389");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e8-60tbca {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.02 10.826c.305-.218 1.063-.602 1.959-.451");
}

.eakj5994q {
  d: path("M19.286 7.506a3 3 0 0 1-.078-.162a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.953 1.79-3.953 3.998v.325c-.402-.306-.908-.952-.908-1.997c0-1.268.925-1.908 1.515-2.317c.167-.116.306-.213.391-.3l.118-.124c.414-.438 1.15-1.22 2.437-1.561a6.6 6.6 0 0 1 1.932-.19c.472.021.805.43.805.902V7.49z");
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.flv9kibjx {
  cx: 16.109px;
  cy: 12.952px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.461px;
  ry: 0.233px;
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.ghcnbvbks {
  d: path("M24.985 14.875q.06-1.04.112-2.08c.474.065.842.504.842 1.036c0 .573-.426 1.039-.954 1.044");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gokcfhb1a {
  stop-color: var(--svg-color--ff7636, #FF7636);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h0kcnqbkf {
  stop-color: var(--svg-color--814f57, #814F57);
}

.h195g1fyn {
  d: path("M24.762 15.628a1.94 1.94 0 0 0 1.07-.365v1.1a2.57 2.57 0 0 1-1.586 2.39q.303-.646.409-1.397z");
}

.h7y0qfmyd {
  cx: 16.109px;
  cy: 12.952px;
  rx: 0.461px;
  ry: 0.233px;
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hdwjo0b_s {
  d: path("M7.354 13.605v6.017a2 2 0 0 0 1.38 1.902l4.182 1.362");
}

.hm6v1m56v {
  fill: var(--svg-color--725050, #725050);
  d: path("M24.215 7.51h-2.529a.589.589 0 1 1 .094-1.168c.656.104 1.527.25 2.11.395c1.32.327 1.683.969 1.785 1.426a1.84 1.84 0 0 0-1.46-.654");
}

.hsqf8hwha {
  stop-color: var(--svg-color--724736, #724736);
  stop-opacity: 0;
}

.huew6ibyl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m7.854 5.355l-.235 1.406");
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i-5nkkbze {
  d: path("M21.517 12.724c.076.1-.082.223-.26.357c-.18.134-.312.228-.387.127c-.075-.1.009-.29.187-.424c.18-.134.385-.16.46-.06");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ik287t08j {
  stop-color: var(--svg-color--c09a87, #C09A87);
  stop-opacity: 0;
}

.ip469ff8c {
  stop-color: var(--svg-color--ff8045, #FF8045);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9seiccox {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m18.536 13.535l-.699 2.175c-.119.447.168.895.573.895h.866c.406 0 .692-.455.573-.895l-.585-2.175c-.125-.482-.596-.482-.728 0");
}

.jfma4ebms {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k8sjt8bhr {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.438 2.955L7.148 6.9");
}

.krd2fabda {
  stop-color: var(--svg-color--b7927f, #B7927F);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kybxapb2q {
  stop-color: var(--svg-color--8e675e, #8E675E);
  stop-opacity: 0;
}

.kyf2fxbmx {
  stop-color: var(--svg-color--894d5b, #894D5B);
  stop-opacity: 0;
}

.l24x8zb-x {
  stop-color: var(--svg-color--b64318, #B64318);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lejfwxzry {
  stop-color: var(--svg-color--c8a48a, #C8A48A);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnx1w7b3f {
  stop-color: var(--svg-color--9c745d, #9C745D);
  stop-opacity: 0;
}

.lvhlipbcn {
  d: path("M4.361 12.125c0-.11.09-.2.2-.2h3.811c.11 0 .2.09.2.2v1.714h-4.21z");
}

.lyn31cv5k {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M23.427 10.624c-.207-.18-.448-.372-.813-.487c-.36-.113-.811-.143-1.435-.067a.328.328 0 0 0 .08.651c.57-.07.918-.033 1.158.042c.234.074.393.194.579.356a.328.328 0 1 0 .43-.495");
}

.m9ambcb1f {
  fill: var(--svg-color--000, #000);
  d: path("M17.032 13.557a.6.6 0 0 0-.604-.605a.602.602 0 0 0-.538.883h1.07a.6.6 0 0 0 .072-.278");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.mz5dt6b2t {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.84 12.18a1.65 1.65 0 0 1 1.602 1.252a.324.324 0 0 1-.316.403h-2.64a.272.272 0 0 1-.268-.322a1.65 1.65 0 0 1 1.622-1.334");
}

.n3ywyofxa {
  d: path("m18.559 13.304l-.629 2.174c-.128.448.18.895.616.895h.93c.437 0 .745-.454.616-.895l-.628-2.174c-.135-.482-.764-.482-.905 0");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.noh-lsb2k {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.183 12.18c-.773 0-1.425.532-1.603 1.252a.324.324 0 0 0 .317.403h2.64a.272.272 0 0 0 .268-.322a1.66 1.66 0 0 0-1.622-1.334");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o6qx6mc1p {
  stop-color: var(--svg-color--7f4a33, #7F4A33);
  stop-opacity: 0;
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p4ezwj49r {
  stop-color: var(--svg-color--dd6422, #DD6422);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmtca2xis {
  stop-color: var(--svg-color--ff611d, #FF611D);
  stop-opacity: 0;
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.pqhb10bsd {
  d: path("m25.177 11.37l-.034-.746c-.013-.903-.759-1.649-1.663-1.687h-1.656a2.86 2.86 0 0 1-2.512-1.49s-.124-.285-.214-.748c-.192-.984.727-1.716 1.715-1.545c1.22.212 2.689.611 3.748 1.302c2.064 1.346 1.703 3.772.616 4.914");
}

.pr1c_plua {
  stop-color: var(--svg-color--a97f72, #A97F72);
}

.px0vdqe0d {
  stop-color: var(--svg-color--c09a87, #C09A87);
}

.q2kyq2xrt {
  stop-color: var(--svg-color--d93f13, #D93F13);
}

.q3td6tqwm {
  stop-color: var(--svg-color--dd6422, #DD6422);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qdtuxcc3i {
  stop-color: var(--svg-color--9e7963, #9E7963);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qy040r_9h {
  d: path("M24.754 6.29a2.75 2.75 0 0 1 1.5 1.244c.552.971.47 2.132-.126 2.989c-.207.305-.32.666-.32 1.034v1.406a2.1 2.1 0 0 0-.789-.318l.093-1.9a1.715 1.715 0 0 0-1.631-1.694h-1.657a2.87 2.87 0 0 1-2.616-1.707a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.998l.036 1.818c-.3.044-.614.145-.852.312v-1.42c0-.368-.113-.73-.32-1.034a2.83 2.83 0 0 1-.17-2.893a2.77 2.77 0 0 1 1.538-1.333a3.17 3.17 0 0 0 1.637-1.313a2.75 2.75 0 0 1 3.42-1.079c.451.197.96.197 1.411 0a2.8 2.8 0 0 1 1.08-.222c.997 0 1.87.54 2.352 1.339c.364.603.935 1.04 1.6 1.269");
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rn15rw1rx {
  d: path("M24.834 15.735q.117-1.887.218-3.775a1.904 1.904 0 0 1-.218 3.775");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.sagpcsbuz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.588 5.183l.148 1.946");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sq9q63bos {
  stop-color: var(--svg-color--ff7636, #FF7636);
  stop-opacity: 0;
}

.sqbaubcdg {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.602 3.867v3.088");
}

.sqok2nb6k {
  d: path("M19.011 23.949c-1.268 0-2.296-.986-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.214-1.028 2.2-2.296 2.2");
}

.sy2nhlbqj {
  stop-color: var(--svg-color--7f4a33, #7F4A33);
}

.t6ahfk42q {
  stop-color: var(--svg-color--9c745d, #9C745D);
}

.ta-g5n7qo {
  stop-color: var(--svg-color--894d5b, #894D5B);
}

.tado7838v {
  d: path("M17.392 13.433c0-.342-.277-.569-.352-.638l-.341.33l.21.428z");
}

.taxaeh_ti {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.36 4.002L8.546 7.41");
}

.tb7s17bnz {
  d: path("M13.304 17.42a4.63 4.63 0 0 0 4.596 4.029h2.232a4.63 4.63 0 0 0 4.596-4.03c.14-2.228.28-4.447.384-6.674a1.715 1.715 0 0 0-1.631-1.694h-1.657a2.87 2.87 0 0 1-2.616-1.707a.79.79 0 0 0-.728-.495h-1.506c-2.183 0-3.952 1.79-3.952 3.998c0 2.2.137 4.366.281 6.573");
}

.tf_datbeu {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.407 17.12a3.5 3.5 0 0 0 1.604.38c.595 0 1.141-.138 1.604-.38h.001a.26.26 0 0 1 .304.05a.24.24 0 0 1 .027.306l-.063-.042a2.24 2.24 0 0 1-1.873 1.001a2.24 2.24 0 0 1-1.873-1zm0 0a.26.26 0 0 0-.305.053a.24.24 0 0 0-.026.303z");
}

.tiw8muhjk {
  stop-color: var(--svg-color--834b53, #834B53);
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ulaau23tp {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M14.976 10.495a3.28 3.28 0 0 1 2.057-.425a.328.328 0 0 1-.08.651a2.62 2.62 0 0 0-1.64.337q-.06.037-.089.057l-.02.014l-.003.002a.328.328 0 0 1-.401-.518z");
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.utl9bkbgg {
  d: path("M13.26 15.628a1.94 1.94 0 0 1-1.07-.365v1.1a2.57 2.57 0 0 0 1.587 2.39a4.8 4.8 0 0 1-.41-1.397z");
}

.uuaw3bblr {
  d: path("M22.535 13.418a1 1 0 0 0-.273-.548l-.308.338l.139.27z");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v_9t1abnj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.906 7.971c.11-.062.617-.379.813-.758");
}

.v0q_-i93u {
  stop-color: var(--svg-color--ff8045, #FF8045);
  stop-opacity: 0;
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v464v-byy {
  fill: var(--svg-color--ff611d, #FF611D);
  d: path("M20.038 20.949h.973c2.5 0 7.5 3.5 7.5 9h-18v-3.5a.67.67 0 0 0-.416-.625l-3.084-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.288c0-.563.425-1.014.936-1.014h4.129c.52 0 .935.461.935 1.014v3.986c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.v5qxzgbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.073 7.005c-.13.165-.332.3-.518.4");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wogt4ot2h {
  stop-color: var(--svg-color--d93f13, #D93F13);
  stop-opacity: 0;
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.wvudz1buv {
  d: path("M16.428 12.5a1.056 1.056 0 0 0-1.018 1.335h2.04q.037-.135.038-.278a1.063 1.063 0 0 0-1.06-1.056");
}

.ww76qh22b {
  stop-color: var(--svg-color--c8a48a, #C8A48A);
}

.wwhpuyv6h {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m18.559 13.304l-.629 2.174c-.128.448.18.895.616.895h.93c.437 0 .745-.454.616-.895l-.628-2.174c-.135-.482-.764-.482-.905 0");
}

.x2di_yb4v {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.914 4.823l.36 2.632");
}

.xgo-prp7n {
  stop-color: var(--svg-color--b7927f, #B7927F);
}

.xhfi2bchw {
  d: path("M3.291 9.196c-.125-1.922-.281-2.958-.328-3.64c-.035-.513.024-1.067.711-1.192c.598-.074.883.452.906.66c-.002-.2 0-.68 0-.804c0-.211.008-.977.86-.977c.601 0 .816.587.8.863c.01-.101.023-.413.036-.707c.018-.433.251-.989.945-.976c.598.039.793.613.766.976l-.118 1.867c.024-.187.103-.664.278-1.34c.175-.674.701-.72.957-.683c.326.046.88.36.648 1.273c-.275 1.157-.462 2.645-.527 3.286c.324-.133.642-.413 1.002-.788c.359-.375.886-.383 1.183-.16c.34.293.522.967.12 1.37c-.463.424-2.13 2.404-2.957 3.394c-.23.292-.997.875-2.235.875c-2.203-.094-2.941-1.676-3.047-3.297");
}

.xjv40os-m {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y4b2vhoje {
  fill: var(--svg-color--563936, #563936);
  d: path("m25.177 11.37l-.034-.746c-.013-.903-.759-1.649-1.663-1.687h-1.656a2.86 2.86 0 0 1-2.512-1.49s-.124-.285-.214-.748c-.192-.984.727-1.716 1.715-1.545c1.22.212 2.689.611 3.748 1.302c2.064 1.346 1.703 3.772.616 4.914");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.ya78f26qa {
  stop-color: var(--svg-color--ff7c1f, #FF7C1F);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yrxkt-bta {
  stop-color: var(--svg-color--ff6e45, #FF6E45);
  stop-opacity: 0;
}

.ysdl-nbld {
  fill: var(--svg-color--000, #000);
  d: path("M20.99 13.557c0-.336.269-.605.605-.605a.602.602 0 0 1 .537.883h-1.07a.55.55 0 0 1-.072-.278");
}

.ytohzbchu {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.268 10.76c-.304-.217-1.062-.601-1.958-.45");
}

.z7_258bha {
  stop-color: var(--svg-color--bf8b77, #BF8B77);
}

.zdnxfcblz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.517 12.724c.076.1-.082.223-.26.357c-.18.134-.312.228-.387.127c-.075-.1.009-.29.187-.424c.18-.134.385-.16.46-.06");
}

.zdo6gqojl {
  stop-color: var(--svg-color--d64d18, #D64D18);
}

.zmcsd8b9p {
  stop-color: var(--svg-color--e6724b, #E6724B);
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
