<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihk0yAe)"><path fill="url(#ipruehb)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#icCG4Md)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#ivjAPce)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#iK9vjre)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#iLJREWr)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#iB6Xv7d)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#i50bQUI)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#iH2ZFcc)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#iBh7Tmb)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#iDUR0rd)" clip-rule="evenodd" class="oy76ftsnz"/><path fill="url(#ismFtec)" clip-rule="evenodd" class="oy76ftsnz"/></g><path fill="url(#iJ2Iz3d)" class="zj_pz5bwb"/><path fill="url(#ihEGoyb)" class="s3wacbc5g"/><path fill="url(#i1Nzymt)" class="s3wacbc5g"/><path fill="url(#i2jteAd)" class="i6w8lcbol"/><path fill="url(#iOcpATb)" class="i6w8lcbol"/><path fill="url(#iUuNqRE)" class="i6w8lcbol"/><path fill="url(#ib6YSVT)" class="i6w8lcbol"/><path fill="url(#if8WIAh)" class="wya3g2bmd"/><path fill="url(#in7f6ne)" class="wya3g2bmd"/><path fill="url(#iPv70Xc)" class="wya3g2bmd"/><path fill="url(#iwFsCdb)" class="wya3g2bmd"/><g filter="url(#ipGCkwe)"><path fill="url(#i0jUold)" class="j_cmqr47j"/></g><g filter="url(#iEmHsFc)"><path fill="url(#iWGDoWc)" class="tn6sd3bmv"/></g><g filter="url(#iIht70b)"><path fill="url(#iQskxRc)" class="rif685bkq"/></g><path fill="url(#iXh6y9k)" class="df3wracno"/><path fill="url(#icuB4jc)" class="df3wracno"/><path fill="url(#izI2Snf)" class="df3wracno"/><path fill="url(#iusIFhc)" class="df3wracno"/><path fill="url(#i0P8PUb)" class="df3wracno"/><path fill="url(#iMwJdHl)" class="c90z04b8d"/><path fill="url(#idz6EPb)" class="c90z04b8d"/><path fill="url(#iRxjVYg)" class="c90z04b8d"/><path fill="url(#iPoNt8M)" class="c90z04b8d"/><path fill="url(#i0RxSYg)" class="tn6sd3bmv"/><path fill="url(#iv6l9ce)" class="ykt8wq3aa"/><path fill="url(#iNVuJTd)" class="ykt8wq3aa"/><path fill="url(#iJ2Iz3d)" class="zj_pz5bwb"/><path fill="url(#ispai6d)" class="ccige11qy"/><path fill="url(#idfgd7u)" class="ccige11qy"/><path fill="url(#imVpg2c)" class="qgr_41bfc"/><path fill="url(#ino2a3v)" class="qgr_41bfc"/><path fill="url(#iw7ZvKb)" class="yvghywbvb"/><path fill="url(#iDuBnAL)" class="yvghywbvb"/><path fill="url(#iObQmbd)" class="yvghywbvb"/><g filter="url(#iJuGWxb)"><rect class="c5cwb6k_s"/><rect fill="url(#ipWECic)" class="vgtum5b-w"/><rect fill="url(#iwkRopb)" class="vgtum5b-w"/><rect fill="url(#iKC24Ld)" class="vgtum5b-w"/></g><path fill="url(#ifdccjr)" class="zrc3yuv7g"/><path fill="url(#iQ0TOue)" class="zrc3yuv7g"/><path fill="url(#iBHQfvb)" class="zrc3yuv7g"/><path fill="url(#izBkzme)" class="zrc3yuv7g"/><path fill="url(#i0mpV9c)" class="f5f2c6brp"/><path fill="url(#ifqAaMG)" class="out3l1bbv"/><g filter="url(#iiO0Aod)"><path fill="url(#iYB1Cld)" class="dy5jvsw2z"/><path fill="url(#iUFtUoc)" class="dy5jvsw2z"/><path fill="url(#itkchob)" class="dy5jvsw2z"/><path fill="url(#imiXuMc)" class="dy5jvsw2z"/><path fill="url(#izQDN0c)" class="dy5jvsw2z"/></g><path fill="url(#iWeyl4c)" class="dy5jvsw2z"/><g filter="url(#iHGXwge)"><path stroke="url(#iVToRdP)" class="qjt16ebmg"/></g><g filter="url(#iGt1Zfb)"><path stroke="url(#i9fDLne)" class="q-4nxsbsy"/></g><g filter="url(#i8ihRhc)"><path stroke="url(#iH05eHe)" class="x2qgolnse"/></g><path fill="url(#ifUv6hd)" class="jsdcepb_z"/><path fill="url(#iGDvLyc)" class="wnu1izbkk"/><g filter="url(#iBsY51c)"><path fill="url(#iEFvNdc)" class="r_v_1obnu"/></g><g filter="url(#iCNP6Sq)"><path fill="url(#ixRVvxb)" class="f1175abtm"/><path fill="url(#ifWa03f)" class="f1175abtm"/></g><g filter="url(#i7NHDOc)"><path class="ema3pzblp"/><path fill="url(#iMHpj9b)" class="tiydre_0w"/></g><g filter="url(#iaPuNkd)"><path class="atw1abc_z"/><path fill="url(#iy8o2rb)" class="z_9hvhzoz"/></g><g filter="url(#i0r3Ezc)"><path fill="url(#izev6Gb)" class="elajvybjj"/><path fill="url(#iKwH5Qd)" class="elajvybjj"/><path fill="url(#i9vJRid)" class="elajvybjj"/><path fill="url(#inJy4TR)" class="elajvybjj"/><path fill="url(#ilCHZhc)" class="elajvybjj"/><path fill="url(#i9ya0iv)" class="elajvybjj"/><path fill="url(#izNDBRc)" class="elajvybjj"/></g><path fill="url(#ins5rVc)" class="elajvybjj"/><path fill="url(#ihS4Voc)" class="elajvybjj"/><g filter="url(#i8RGStb)"><path class="eqw7cg9gk"/></g><g filter="url(#i9dimUx)"><path class="p3nc4t9hw"/><path fill="url(#ijl90gc)" class="ud-dkbcvw"/><path fill="url(#i260Ghb)" class="ud-dkbcvw"/><path fill="url(#iAnybub)" class="ud-dkbcvw"/><path fill="url(#iMnW9Wv)" class="ud-dkbcvw"/></g><path fill="url(#ipr3buq)" class="ud-dkbcvw"/><path fill="url(#iARBAKo)" class="ud-dkbcvw"/><path stroke="url(#i1eIzmc)" class="n5b32hvqr"/><g filter="url(#iOk7nEd)"><path class="m24xypbze"/></g><g filter="url(#iVpJWpd)"><path class="ye3o05b2l"/></g><g filter="url(#iYmkNUd)"><path class="z7aev8ltu"/></g><g filter="url(#iHdWnuc)"><path clip-rule="evenodd" class="jat5blo2a"/></g><path class="ybkyb3qwf"/><path fill="url(#iXNuhrc)" class="tl_l3ubow"/><path class="sp1a5wr6k"/><g filter="url(#itONibq)"><path class="kz3wbilvx"/><path fill="url(#isloVxU)" class="e4z3u0y4b"/></g><g filter="url(#inG5mLd)"><path fill="url(#iK4cRdd)" class="ljiuwcbei"/></g><path class="pmgpo6bvy"/><path fill="url(#iFmUzhc)" class="h039hekdt"/><path class="h0n56n9ch"/><g filter="url(#iwOu3oe)"><path fill="url(#iyIxizd)" class="zegj74b1m"/></g><g filter="url(#i4gjjmb)"><ellipse transform="rotate(-27.914 12.972 9.902)" class="wdl-pmb4k"/><ellipse fill="url(#igFQGAc)" transform="rotate(-27.914 12.972 9.902)" class="zvi6qsbmb"/></g><g filter="url(#idXgROb)"><path class="ywksd4arp"/></g><g filter="url(#i7dGQab)"><path class="nkk_etbes"/></g><g filter="url(#iE1ZtMF)"><path class="st_w76uxl"/><path fill="url(#iwY1vyb)" class="nl-p4lb_s"/></g><g filter="url(#icZenFe)"><path class="pcvr3bcqa"/><path fill="url(#iTWUXBd)" class="ehcmpxl2v"/><path fill="url(#iF9cskd)" class="ehcmpxl2v"/></g><g filter="url(#iC3f2hd)"><path stroke="url(#if1BEVb)" class="bicffibwt"/></g><g filter="url(#i1lwS3d)"><path class="vfd-vaczf"/></g><g filter="url(#imjkzOd)" class="z4n2hhy8u"><path fill="url(#iY3fZIe)" class="qweh1rb7c"/></g><g filter="url(#iKxQsed)"><path clip-rule="evenodd" class="fyibzfb4j"/></g><defs><radialGradient id="icCG4Md" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.124 13.096)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ivjAPce" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.308 13.364)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iK9vjre" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.618 8.023)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iLJREWr" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.053 7.488)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iB6Xv7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 11.906 2.536)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i50bQUI" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.674 6.71)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iH2ZFcc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 22.935 9.744)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iBh7Tmb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.355 7.956)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iDUR0rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.90444 -2.65026 2.0962 -.71536 20.158 7.31)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ismFtec" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.284 9.707)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ihEGoyb" cx="0" cy="0" r="1" gradientTransform="scale(3.29991 5.8125)rotate(90 .77 3.911)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="do28bmb5k"/><stop offset="1" class="egj-02bls"/></radialGradient><radialGradient id="i1Nzymt" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.261)" gradientUnits="userSpaceOnUse"><stop class="bfl4-fbqr"/><stop offset="1" class="frstvbc2m"/></radialGradient><radialGradient id="i2jteAd" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.497 14.533)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="ib6YSVT" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.355)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="if8WIAh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.23)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="in7f6ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.48)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iWGDoWc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.855)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iXh6y9k" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.636)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="icuB4jc" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.263 -.282)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="izI2Snf" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.257 14.353)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="iMwJdHl" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.057)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iRxjVYg" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.913)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="i0RxSYg" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.8 11.796)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iv6l9ce" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.824)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="ispai6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.41281 -3.18655 0 15.426 16.512)" gradientUnits="userSpaceOnUse"><stop class="pjmu-bbno"/><stop offset=".632" class="y_k_aubst"/></radialGradient><radialGradient id="idfgd7u" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.874)" gradientUnits="userSpaceOnUse"><stop class="yyk2ffbyt"/><stop offset="1" class="c42dpwbpe"/></radialGradient><radialGradient id="imVpg2c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25223 1.07928 -1.05974 -2.21144 28.021 23.88)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="ino2a3v" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.41)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iObQmbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.324)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="ipWECic" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.011)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iwkRopb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.862)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="iKC24Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.222)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="izBkzme" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.168)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iUFtUoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.238)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="itkchob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.532)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="imiXuMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.782)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="izQDN0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.134)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iWeyl4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.01752 -3.72384 0 27.668 24.916)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="ixRVvxb" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 22.93 -16.547)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="ifWa03f" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 20.496 8.914)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iMHpj9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 19.817 10.707)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iy8o2rb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 10.825 10.595)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="izev6Gb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.285 10.058)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iKwH5Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 18.677 11.42)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i9vJRid" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.046 17.387)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="inJy4TR" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 15.426 9.84)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="n1v90fbaj"/><stop offset="1" class="hytrnlbyi"/></radialGradient><radialGradient id="ilCHZhc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.045 6.732)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="i9ya0iv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 17.727 9.64)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="izNDBRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.35 9.41)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ins5rVc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 20.521 11.127)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="ihS4Voc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.24 4.06)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="ijl90gc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.21 11.992)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iMnW9Wv" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 15.97 12.204)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iARBAKo" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.1 8.255)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="iXNuhrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.608 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="isloVxU" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.38 10.082)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFmUzhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.244 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="igFQGAc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.508 -1.27)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwY1vyb" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.02 -3.67)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iTWUXBd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.829 6.785)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iF9cskd" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 15.636 3.04)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><linearGradient id="ipruehb" x1="20.119" x2="13.314" y1="3.642" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iJ2Iz3d" x1="8.23" x2="22.659" y1="15.241" y2="15.241" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iOcpATb" x1="11.239" x2="11.239" y1="30.355" y2="29.043" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iUuNqRE" x1="15.177" x2="14.208" y1="29.043" y2="29.043" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iPv70Xc" x1="19.74" x2="19.74" y1="30.355" y2="29.043" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iwFsCdb" x1="15.802" x2="16.505" y1="27.918" y2="27.918" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="i0jUold" x1="10.458" x2="12.677" y1="17.974" y2="24.662" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="iQskxRc" x1="20.633" x2="18.282" y1="19.025" y2="23.726" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iusIFhc" x1="18.958" x2="17.552" y1="24.043" y2="22.543" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="i0P8PUb" x1="17.146" x2="17.974" y1="18.824" y2="19.168" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="idz6EPb" x1="6.567" x2="6.567" y1="30.298" y2="29.164" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iPoNt8M" x1="8.38" x2="7.935" y1="29.332" y2="29.329" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="iNVuJTd" x1="22.753" x2="23.162" y1="27.605" y2="27.589" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="iw7ZvKb" x1="23.825" x2="26.529" y1="20.793" y2="20.793" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iDuBnAL" x1="26.529" x2="26.18" y1="20.777" y2="20.777" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="ifdccjr" x1="26.529" x2="25.177" y1="23.105" y2="23.105" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iQ0TOue" x1="26.529" x2="26.129" y1="23.253" y2="23.253" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="iBHQfvb" x1="23.696" x2="24.227" y1="23.253" y2="23.253" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="i0mpV9c" x1="24.782" x2="23.892" y1="21.746" y2="21.746" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="ifqAaMG" x1="24.782" x2="23.892" y1="23.527" y2="23.527" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iYB1Cld" x1="27.165" x2="23.137" y1="27.996" y2="27.996" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iVToRdP" x1="23.754" x2="25.463" y1="26.013" y2="26.013" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="i9fDLne" x1="23.676" x2="25.385" y1="27.318" y2="27.318" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iH05eHe" x1="23.754" x2="25.463" y1="28.623" y2="28.623" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="ifUv6hd" x1="8.261" x2="22.637" y1="15.222" y2="15.222" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGDvLyc" x1="8.261" x2="22.637" y1="15.191" y2="15.191" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iEFvNdc" x1="9.131" x2="12.09" y1="10.682" y2="10.682" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="i260Ghb" x1="14.487" x2="15.426" y1="12.065" y2="12.065" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iAnybub" x1="15.426" x2="15.426" y1="12.864" y2="12.253" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="ipr3buq" x1="15.504" x2="15.504" y1="12.838" y2="12.698" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="i1eIzmc" x1="14.361" x2="14.822" y1="14.135" y2="13.423" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iK4cRdd" x1="18.386" x2="18.072" y1="10.052" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyIxizd" x1="13.987" x2="13.674" y1="10.052" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="if1BEVb" x1="12.534" x2="13.079" y1="4.397" y2="5.67" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iY3fZIe" x1="10.588" x2="22.177" y1="9.672" y2="9.672" gradientUnits="userSpaceOnUse"><stop class="z473rkg5k"/><stop offset=".115" class="f-zxjbc7n"/><stop offset=".257" class="f-zxjbc7n"/><stop offset=".917" class="l7b4ixb5j"/></linearGradient><filter id="ihk0yAe" width="15.268" height="15.768" x="7.917" y="1.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="ipGCkwe" width="7.023" height="11.703" x="8.372" y="15.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".375"/></filter><filter id="iEmHsFc" width="5.673" height="10.453" x="9.475" y="15.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="iIht70b" width="6.388" height="10.529" x="15.682" y="16.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".375"/></filter><filter id="iJuGWxb" width="4.008" height=".781" x="23.173" y="18.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="iiO0Aod" width="4.468" height="5.556" x="23.137" y="24.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="iHGXwge" width="2.097" height=".3" x="23.604" y="25.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".05"/></filter><filter id="iGt1Zfb" width="2.097" height=".3" x="23.526" y="27.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".05"/></filter><filter id="i8ihRhc" width="2.097" height=".3" x="23.604" y="28.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".05"/></filter><filter id="iBsY51c" width="3.368" height="3.218" x="9.131" y="8.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="iCNP6Sq" width="3.218" height="3.468" x="18.644" y="8.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="i7NHDOc" width="3.148" height="3.148" x="18.679" y="9.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".25"/></filter><filter id="iaPuNkd" width="2.948" height="2.948" x="9.285" y="9.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".2"/></filter><filter id="i0r3Ezc" width="10.191" height="11.277" x="10.33" y="5.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="i8RGStb" width="2.877" height="3.682" x="13.825" y="9.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".25"/></filter><filter id="i9dimUx" width="2.377" height="3.182" x="14.237" y="9.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".125"/></filter><filter id="iOk7nEd" width="3.001" height="1.285" x="16.368" y="9.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="iVpJWpd" width="3.001" height="1.285" x="11.482" y="9.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="iYmkNUd" width="2.453" height="1.091" x="11.617" y="7.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="iHdWnuc" width="2.453" height="1.091" x="17.035" y="7.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="itONibq" width=".787" height=".696" x="16.873" y="9.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".05"/></filter><filter id="inG5mLd" width=".891" height=".913" x="17.713" y="9.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".1"/></filter><filter id="iwOu3oe" width=".986" height="1.04" x="13.271" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".1"/></filter><filter id="i4gjjmb" width=".913" height=".705" x="12.516" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".05"/></filter><filter id="idXgROb" width="2.261" height=".978" x="17.065" y="7.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".1"/></filter><filter id="i7dGQab" width="2.261" height=".978" x="11.613" y="7.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".1"/></filter><filter id="iE1ZtMF" width="4.212" height="4.513" x="9.171" y="3.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/><feGaussianBlur result="effect2_foregroundBlur_4002_2179" stdDeviation=".15"/></filter><filter id="icZenFe" width="8.767" height="5.782" x="12.255" y="2.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/><feGaussianBlur result="effect2_foregroundBlur_4002_2179" stdDeviation=".125"/></filter><filter id="iC3f2hd" width="1.145" height="2.31" x="12.234" y="3.753" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".1"/></filter><filter id="i1lwS3d" width="6.427" height="3.372" x="14.844" y="4.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2179" stdDeviation=".375"/></filter><filter id="imjkzOd" width="10.729" height="5.624" x="10.061" y="6.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/></filter><filter id="iKxQsed" width="11.479" height="6.324" x="9.611" y="5.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.498039 0 0 0 0 0.690196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2179"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.741176 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2179" result="effect2_innerShadow_4002_2179"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-scientist-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.atw1abc_z {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M10.76 11.67a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bfl4-fbqr {
  stop-color: var(--svg-color--5f4786, #5F4786);
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.bicffibwt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.534 4.053c.024.243.235 1.157.545 1.71");
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c42dpwbpe {
  stop-color: var(--svg-color--da9890, #DA9890);
  stop-opacity: 0;
}

.c5cwb6k_s {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.621px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.c90z04b8d {
  d: path("M8.226 29.933v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.ccige11qy {
  d: path("M15.426 18.563a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
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

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.df3wracno {
  d: path("m21.37 17.057l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687l-4.732 4.808a.2.2 0 0 1-.343-.14v-3.381a2 2 0 0 1 .175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.dhui3nlqd {
  stop-color: var(--svg-color--d6baf6, #D6BAF6);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.do28bmb5k {
  stop-color: var(--svg-color--755b9f, #755B9F);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.dy5jvsw2z {
  d: path("M23.137 25.259a.73.73 0 0 1 .726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e4z3u0y4b {
  d: path("M17.544 9.71c.064.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.39-.05");
}

.egj-02bls {
  stop-color: var(--svg-color--482f73, #482F73);
}

.ehcmpxl2v {
  d: path("M14.822 2.804c-1.132-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.573-.175 1.744.542 1.878.889c0-3.933-3.345-4.671-5.922-5.24z");
}

.elajvybjj {
  d: path("M10.338 9.332h.013l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.05-.02q.028-.012.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .46-.05a3.86 3.86 0 0 0 3.19 1.672h3.22c.18 0 1.082.088 1.136 1.333l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684s-4.86-1.882-4.983-4.684z");
}

.ema3pzblp {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.253 11.67a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.eqw7cg9gk {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.033 10.51l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.494-.376-.613 0");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f-zxjbc7n {
  stop-color: var(--svg-color--8ac5a2, #8AC5A2);
}

.f1175abtm {
  d: path("M20.253 12.204a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.f5f2c6brp {
  d: path("M23.825 21.98v-.469h.805a.234.234 0 0 1 0 .469z");
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.foy77stiz {
  stop-color: var(--svg-color--9f98a7, #9F98A7);
}

.frstvbc2m {
  stop-color: var(--svg-color--5f4786, #5F4786);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fyibzfb4j {
  fill: var(--svg-color--9b94a2, #9B94A2);
  fill-rule: evenodd;
  d: path("M9.761 9.115c.012-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.341c-.045-.066-.09-.076-.112-.076s-.067.01-.112.075a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.002a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34a.74.74 0 0 1 .609.34v.002a2.46 2.46 0 0 0 2.114 1.077c1.248-.045 2.31-1.134 2.328-2.382a2.41 2.41 0 0 0-2.407-2.432h-5.275c-1.336 0-2.437 1.07-2.447 2.407");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h039hekdt {
  d: path("M13.242 9.521a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.h0n56n9ch {
  fill: var(--svg-color--000, #000);
  d: path("M13.753 10.414a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.235");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hytrnlbyi {
  stop-color: var(--svg-color--c58497, #C58497);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i6w8lcbol {
  d: path("M11.114 16.226a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.519z");
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j_cmqr47j {
  d: path("m9.255 17.754l-.13 1.733a.6.6 0 0 0 .493.636l.48.084a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jat5blo2a {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.157 8.36l-.138.23za.268.268 0 0 1-.275.46l-.005-.003l-.022-.012l-.091-.046a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.073-.092a.268.268 0 1 1-.093-.528c.513-.09.989 0 1.328.109a3.3 3.3 0 0 1 .56.238l.009.006z");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jsdcepb_z {
  d: path("M15.8 15.192c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kz3wbilvx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.544 9.71c.064.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.39-.05");
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7b4ixb5j {
  stop-color: var(--svg-color--b2d5c0, #B2D5C0);
  stop-opacity: 0.63;
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

.ljiuwcbei {
  d: path("M18.405 10.296a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.m24xypbze {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.568 10.026c.265-.467.669-.836 1.537-.836c.38 0 .747.106 1.073.37c.269.216.233.494.025.598l-.556.318c-.652-.21-1.373-.24-2.08-.45");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1v90fbaj {
  stop-color: var(--svg-color--cf959d, #CF959D);
  stop-opacity: 0;
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n5b32hvqr {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.028 13.118a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.332 0a.2.2 0 0 0-.02-.25a.205.205 0 0 0-.248-.041c-.404.215-.88.339-1.398.339c-.513 0-.995-.124-1.399-.34Z");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nkk_etbes {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.574 8.222c-.322-.078-1.124-.039-1.66.345");
}

.nl-p4lb_s {
  d: path("M10.356 4.607c.566-.6 1.637-.6 2.131-.511l.396 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.11-2.38.845-3.16");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o77zymbyt {
  stop-color: var(--svg-color--a588b8, #A588B8);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.out3l1bbv {
  d: path("M23.825 23.761v-.468h.805a.234.234 0 1 1 0 .468z");
}

.oy76ftsnz {
  fill-rule: evenodd;
  d: path("M22.61 12.005c.213-.435.325-.921.325-1.427c0-.467-.096-.906-.269-1.306h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.454-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.456.233l-.085.001A3.3 3.3 0 0 0 8.99 6.975v.01a3.24 3.24 0 0 1-.526 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.455M10.35 9.332h-.011l1.198 2.356c.123 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.135-3.197c-.054-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.189-1.673a.264.264 0 0 0-.462.051l-.082.194a2.3 2.3 0 0 1-1.24 1.255q-.027.012-.052.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.p3nc4t9hw {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.043 10.372l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pcvr3bcqa {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M14.822 2.804c-1.132-.25-2.15.88-2.267 1.3c1.052 3.544 3.713 3.35 6.34 3.058c1.573-.175 1.744.542 1.878.889c0-3.933-3.345-4.671-5.922-5.24z");
}

.pjmu-bbno {
  stop-color: var(--svg-color--ca8995, #CA8995);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmgpo6bvy {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.035 9.249c-.653 0-1.205.45-1.355 1.059a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.q-4nxsbsy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.24h1.797");
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qgr_41bfc {
  d: path("M26.434 22.903c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.qjt16ebmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.935h1.797");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qweh1rb7c {
  d: path("M18.083 6.41h-5.275c-1.497 0-2.737 1.2-2.747 2.706a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.269 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v_1obnu {
  d: path("M10.74 12.204a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rif685bkq {
  d: path("m21.202 18.196l.116 1.534a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.075.22l.554.611a.44.44 0 0 1-.013.607l-4.188 4.255a.177.177 0 0 1-.303-.124v-2.992c0-.25.053-.496.155-.724l2.306-5.136c.822.264 1.599.64 2.31 1.111");
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s3wacbc5g {
  d: path("M15.466 15.293c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sp1a5wr6k {
  fill: var(--svg-color--000, #000);
  d: path("M17.099 10.414a.51.51 0 0 1 .51-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.06-.235");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.st_w76uxl {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.356 4.607c.566-.6 1.637-.6 2.131-.511l.396 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.11-2.38.845-3.16");
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tiydre_0w {
  d: path("M20.253 11.67a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tl_l3ubow {
  d: path("M17.61 9.521a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.tn6sd3bmv {
  d: path("m9.608 17.057l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.381a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ud-dkbcvw {
  d: path("m15.043 10.372l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6bhjtbbk {
  stop-color: var(--svg-color--a8a1ad, #A8A1AD);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vfd-vaczf {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.832 6.414l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.396 1.899 1.872a3.15 3.15 0 0 0-2.69-.769");
}

.vgtum5b-w {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.621px;
  rx: 0.391px;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.wdl-pmb4k {
  cx: 12.972px;
  cy: 9.902px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wnu1izbkk {
  d: path("M15.47 15.192h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.wya3g2bmd {
  d: path("M19.865 16.226a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.519z");
}

.x2qgolnse {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.544h1.797");
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y_k_aubst {
  stop-color: var(--svg-color--dba1a5, #DBA1A5);
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.ybkyb3qwf {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.817 9.25c.653 0 1.204.45 1.355 1.058a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271c.125-.64.69-1.128 1.37-1.128");
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.ye3o05b2l {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.284 10.026c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.106-1.072.37c-.27.216-.233.494-.025.598l.556.318c.652-.21 1.373-.24 2.079-.45");
}

.ykt8wq3aa {
  d: path("M22.753 29.933v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yvghywbvb {
  d: path("M23.825 19.402h2.703v5.938h-2.703z");
}

.ywksd4arp {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.365 8.222c.323-.078 1.125-.039 1.66.345");
}

.yyk2ffbyt {
  stop-color: var(--svg-color--da9890, #DA9890);
}

.z_9hvhzoz {
  d: path("M10.76 11.67a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.148");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z473rkg5k {
  stop-color: var(--svg-color--b2d5c0, #B2D5C0);
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.z7aev8ltu {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.028 8.817l-.004.003a.268.268 0 0 1-.276-.46l.001-.001l.003-.002l.01-.006a2 2 0 0 1 .148-.076a3 3 0 0 1 .41-.162c.34-.109.816-.2 1.329-.11a.268.268 0 0 1-.094.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.193");
}

.zegj74b1m {
  d: path("M14.057 10.309c0-.289-.235-.481-.298-.54l-.288.28l.177.361z");
}

.zj_pz5bwb {
  d: path("M15.466 15.243h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zqbntluns {
  stop-color: var(--svg-color--746e77, #746E77);
}

.zrc3yuv7g {
  d: path("M26.529 21.168v4.171h-2.704v-4.171z");
}

.zt127j5os {
  stop-color: var(--svg-color--ddd8e2, #DDD8E2);
  stop-opacity: 0;
}

.zvi6qsbmb {
  cx: 12.972px;
  cy: 9.902px;
  rx: 0.39px;
  ry: 0.197px;
}

</style>
