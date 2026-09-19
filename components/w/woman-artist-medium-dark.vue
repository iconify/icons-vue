<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9siZDc)"><path fill="url(#ib2QXPb)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#icefFpb)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#iwFORAc)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#iA3dFiH)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#i9Hwo5d)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#iK2YVlK)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#iFQ7ghe)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#iBz6OmU)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#iXfVjzd)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#i8hpkkb)" clip-rule="evenodd" class="p07xrrbwq"/><path fill="url(#iFaajfy)" clip-rule="evenodd" class="p07xrrbwq"/></g><path fill="url(#iHzmtfe)" class="vbuc_sdez"/><path fill="url(#inA3Tpe)" class="vbuc_sdez"/><path fill="url(#i6KXFTY)" class="vbuc_sdez"/><path fill="url(#i04jDnj)" class="vbuc_sdez"/><g filter="url(#iPF6FOc)"><path clip-rule="evenodd" class="cvzy-mbfm"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#iSO0cDr)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#ijHbhAb)"><path fill="url(#iZYJJTd)" class="rqxxjhbor"/><path fill="url(#iYcv9Wc)" class="rqxxjhbor"/></g><g filter="url(#idoQoHe)"><path fill="url(#iCgYo9c)" class="r1d1qpblj"/><path fill="url(#iNSLv7d)" class="r1d1qpblj"/><path fill="url(#i8efCLe)" class="r1d1qpblj"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#irqWt7c)"><path fill="url(#iIo36rp)" class="c2bk9yb6a"/><path fill="url(#ignAelv)" class="c2bk9yb6a"/></g><path fill="url(#iqkeVzb)" class="b8wkgccyf"/><path fill="url(#ib6zMLd)" class="b8wkgccyf"/><g filter="url(#iIA8Rbb)"><path fill="url(#izcCUib)" class="uj-94poim"/></g><g filter="url(#is1oJzb)"><path class="oh_l9db2x"/></g><g filter="url(#iSP1frc)"><path class="teu3yl5ky"/></g><g filter="url(#itIkxod)"><path class="waw2uhbiy"/></g><g filter="url(#icLk5hu)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#i3H3gPd)"><path fill="url(#iV1Av9c)" class="yx08hybsl"/></g><g filter="url(#iCIqDAb)"><path fill="url(#iO8TsTc)" class="hvyevjb_p"/></g><path fill="url(#i4gM3yb)" class="hvyevjb_p"/><path fill="url(#iK4s60b)" class="jhj9frbew"/><path fill="url(#ib9Hitc)" class="jhj9frbew"/><path fill="url(#iTfdAvb)" class="vfzn0su_w"/><path fill="url(#iTkYgvd)" class="vfzn0su_w"/><path fill="url(#iqMfzad)" class="vfzn0su_w"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iw1p9ce)" class="s80w1fafw"/><g filter="url(#i3exYZc)"><path fill="url(#i1FSYJc)" class="o7yoj0s6u"/><path fill="url(#iZLdWle)" class="o7yoj0s6u"/><path fill="url(#iZaoaBd)" class="o7yoj0s6u"/><path fill="url(#izMYsjd)" class="o7yoj0s6u"/></g><path fill="url(#ieEgdTd)" class="fbdpw4j2k"/><g filter="url(#iLPxl6c)"><path fill="url(#iSbgAfc)" class="i9gy75kqp"/><path fill="url(#ibRVbPt)" class="i9gy75kqp"/><path fill="url(#iR3m9Xd)" class="i9gy75kqp"/><path fill="url(#ixbEKEd)" class="i9gy75kqp"/></g><g filter="url(#itwHnde)"><path fill="url(#i929CYc)" class="qppq5ybfo"/><path fill="url(#iILW5qO)" class="qppq5ybfo"/><path fill="url(#iBokQme)" class="qppq5ybfo"/><path fill="url(#iNISImd)" class="qppq5ybfo"/><path fill="url(#iCmIxte)" class="qppq5ybfo"/></g><g filter="url(#iSMP1ge)"><path stroke="url(#iX7P55F)" class="ct65j078y"/></g><g filter="url(#iTqzgee)"><path stroke="url(#ihsaQCd)" class="ze5nteb_r"/></g><g filter="url(#iHRlIgb)"><path stroke="url(#i3Vf8mb)" class="jz78atb4u"/></g><g filter="url(#iYthEEa)"><path fill="url(#inKqw3S)" class="f0h--sbru"/><path fill="url(#i3SDUyb)" class="f0h--sbru"/></g><g filter="url(#ifS7qwe)"><path stroke="url(#ifRPnZd)" class="z304cabpx"/></g><path fill="url(#iY9HAAc)" class="ge21ot55e"/><path fill="url(#iTrUkge)" class="h-1dj5qtj"/><g filter="url(#iMfH3lb)"><path stroke="url(#iLeHoBc)" class="vfggmllpb"/></g><g filter="url(#ioETZJT)"><path fill="url(#ilyVu5b)" class="cwp-36b8i"/></g><g filter="url(#iI3DBpb)"><path fill="url(#iGV7I1A)" class="qxv7yfbid"/><path fill="url(#iKMMnSc)" class="qxv7yfbid"/></g><g filter="url(#iDFHEMe)"><path class="u9dz2d52g"/><path fill="url(#iLT0q1d)" class="o-yw38kdw"/></g><g filter="url(#i4wjghb)"><path class="q_1nt5b-m"/><path fill="url(#ipoVWle)" class="s-d9s-q8p"/></g><g filter="url(#ifNQvwc)"><path fill="url(#i0nAisb)" class="b4ppyhbeb"/><path fill="url(#iZkNI5c)" class="b4ppyhbeb"/><path fill="url(#ikKI5ue)" class="b4ppyhbeb"/><path fill="url(#iIYuHqd)" class="b4ppyhbeb"/><path fill="url(#iaBaqpc)" class="b4ppyhbeb"/><path fill="url(#i7yv00E)" class="b4ppyhbeb"/><path fill="url(#iBisc6b)" class="b4ppyhbeb"/><path fill="url(#if0SFdd)" class="b4ppyhbeb"/></g><path fill="url(#iIf247c)" class="b4ppyhbeb"/><path fill="url(#iKbSLKb)" class="b4ppyhbeb"/><path fill="url(#ilNRUPc)" class="b4ppyhbeb"/><g filter="url(#i5uB9rd)"><path class="dh55xebqe"/></g><g filter="url(#ihn4swc)"><path class="esrnr63bg"/><path fill="url(#iv6T1Hc)" class="r52clnqnq"/><path fill="url(#idUvVUb)" class="r52clnqnq"/><path fill="url(#icCE8Jd)" class="r52clnqnq"/><path fill="url(#iScIgfT)" class="r52clnqnq"/></g><path fill="url(#iQOP9Rb)" class="r52clnqnq"/><path fill="url(#iQz3kqe)" class="r52clnqnq"/><path stroke="url(#ik8yOGb)" class="mnu2otn4f"/><g filter="url(#i3lT2xb)"><path class="cmxz2bc_u"/></g><g filter="url(#imaEulQ)"><path class="o9yul0q5w"/></g><g filter="url(#i3hdBod)"><path class="k8-cv7ymm"/></g><g filter="url(#iPqJcqb)"><path clip-rule="evenodd" class="kty0vsvue"/></g><path class="msq2krcmz"/><path fill="url(#i1D4vyb)" class="x5zldhc4i"/><path class="cu0ckn7fn"/><g filter="url(#iGZyj0b)"><path class="dcez0yllb"/><path fill="url(#ieAiQld)" class="slu-4bgvl"/></g><g filter="url(#issyv5b)"><path fill="url(#iBK2AFe)" class="c3x_amb3i"/></g><path class="sspaeirju"/><path fill="url(#iGfcdyb)" class="w58fkm82c"/><path class="svrc61bac"/><g filter="url(#i73xFBb)"><path fill="url(#iH4M60d)" class="n33kr0b_k"/></g><g filter="url(#iP40ibb)"><ellipse transform="rotate(-27.914 13.736 10.269)" class="gpmxoobeg"/><ellipse fill="url(#ineGMWI)" transform="rotate(-27.914 13.736 10.269)" class="jl5lrnj8e"/></g><g filter="url(#is3gxbd)"><path class="sau3ajb5n"/></g><g filter="url(#ijiv1md)"><path class="s-nbsobwa"/></g><g filter="url(#ixOVi2d)"><path class="xxsjp-b7l"/><path fill="url(#ikdY9ke)" class="asvtvor4b"/></g><g filter="url(#igiPKxe)"><path class="ld2ijfp2p"/><path fill="url(#ic16ZyW)" class="mzth9rkss"/><path fill="url(#i5GAGtK)" class="mzth9rkss"/></g><g filter="url(#iMfH3lb)"><path stroke="url(#iLeHoBc)" class="vfggmllpb"/></g><path fill="url(#iXiXb4d)" class="tpv18l7lf"/><path fill="url(#iLkxb5d)" class="tpv18l7lf"/><path fill="url(#iCultsb)" class="tpv18l7lf"/><g filter="url(#iTVHxYb)"><path fill="url(#iwfm65c)" class="ansdxpmor"/></g><g filter="url(#iHA7Sec)"><path fill="url(#in6AZkm)" class="ok43c2qsk"/></g><defs><radialGradient id="icefFpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.888 13.462)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iwFORAc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 13.072 13.73)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iA3dFiH" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.91 8.395)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i9Hwo5d" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.332 7.886)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iK2YVlK" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 3.932 11.938)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iFQ7ghe" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.98 7.052)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iBz6OmU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.699 10.11)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iXfVjzd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.715 8.186)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i8hpkkb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.207 -3.645)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iFaajfy" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 10.048 10.074)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iHzmtfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.975)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="i6KXFTY" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.975)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="iYcv9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.422 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iV1Av9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.783)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="iK4s60b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59797 1.31329 -1.29023 -1.56991 28.701 23.652)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="ib9Hitc" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 28.466 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibRVbPt" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.595)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="iILW5qO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.656 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iBokQme" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.656 26.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iNISImd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.656 27.824)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iCmIxte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.656 29.175)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="inKqw3S" cx="0" cy="0" r="1" gradientTransform="rotate(138.439 5.875 11.76)scale(2.57895 1.90476)" gradientUnits="userSpaceOnUse"><stop class="ujsn-3s1u"/><stop offset="1" class="bg01_ib1f"/></radialGradient><radialGradient id="i3SDUyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .75 -2.28629 0 16.143 16.598)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="e8jd9xkck"/><stop offset="1" class="ytueivx8a"/></radialGradient><radialGradient id="iGV7I1A" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.229 11.4)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iKMMnSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.26 9.28)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iLT0q1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.58 11.074)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="ipoVWle" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.794 5.48)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="i0nAisb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 19.049 10.424)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iZkNI5c" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.894 7.548)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="ikKI5ue" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 14.027 16.931)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iIYuHqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.72279 -10.993 0 15.928 9.421)" gradientUnits="userSpaceOnUse"><stop offset=".762" class="kbau0p37l"/><stop offset=".921" class="msj6cib4r"/><stop offset="1" class="y00xmr1wl"/></radialGradient><radialGradient id="iaBaqpc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.41 6.952)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="i7yv00E" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.49 10.006)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iBisc6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 14.113 9.777)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="if0SFdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.573 7.69)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iIf247c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.285 11.493)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iKbSLKb" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.434 2.54)scale(1.52213 1.61741)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="ilNRUPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.5625 1.85526 2.0779 12.153 16.153)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iv6T1Hc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.974 12.22)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iScIgfT" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.734 12.432)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iQz3kqe" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.447 8.488)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="i1D4vyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.372 10.364)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ieAiQld" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.143 10.449)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGfcdyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 14.007 10.364)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ineGMWI" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.07 -1.462)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikdY9ke" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.688 -4.081)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ic16ZyW" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.095 7.208)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="i5GAGtK" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.4 3.406)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iLkxb5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iwfm65c" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="in6AZkm" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.377 3.233)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="i9siZDc" width="15.268" height="15.768" x="8.68" y="1.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="iPF6FOc" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".75"/></filter><filter id="iSO0cDr" width="8.987" height="5.737" x="11.649" y="14.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".2"/></filter><filter id="ijHbhAb" width="2.812" height="4.17" x="13.354" y="19.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="idoQoHe" width="2.762" height="4.17" x="16.118" y="19.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="irqWt7c" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="iIA8Rbb" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2389" result="effect2_innerShadow_4002_2389"/></filter><filter id="is1oJzb" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".075"/></filter><filter id="iSP1frc" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".075"/></filter><filter id="itIkxod" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".075"/></filter><filter id="icLk5hu" width="2.58" height="2.68" x="7.143" y="22.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2389" result="effect2_innerShadow_4002_2389"/></filter><filter id="i3H3gPd" width="2.58" height="2.68" x="10.143" y="25.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2389" result="effect2_innerShadow_4002_2389"/></filter><filter id="iCIqDAb" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2389" result="effect2_innerShadow_4002_2389"/></filter><filter id="i3exYZc" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="iLPxl6c" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="itwHnde" width="4.846" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="iSMP1ge" width="2.097" height=".3" x="24.375" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".05"/></filter><filter id="iTqzgee" width="2.097" height=".3" x="24.297" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".05"/></filter><filter id="iHRlIgb" width="2.097" height=".3" x="24.375" y="28.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".05"/></filter><filter id="iYthEEa" width="3.859" height="4.694" x="14.213" y="13.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.180392 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="ifS7qwe" width="1.145" height="2.31" x="12.975" y="4.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".125"/></filter><filter id="iMfH3lb" width="1.145" height="2.31" x="12.998" y="4.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".1"/></filter><filter id="ioETZJT" width="3.368" height="3.218" x="9.895" y="9.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="iI3DBpb" width="3.218" height="3.468" x="19.408" y="9.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="iDFHEMe" width="3.148" height="3.148" x="19.443" y="9.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".25"/></filter><filter id="i4wjghb" width="2.648" height="2.648" x="10.199" y="9.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".125"/></filter><filter id="ifNQvwc" width="10.191" height="11.027" x="11.094" y="6.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="i5uB9rd" width="2.877" height="3.682" x="14.588" y="9.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".25"/></filter><filter id="ihn4swc" width="2.377" height="3.182" x="15.001" y="10.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".125"/></filter><filter id="i3lT2xb" width="3.001" height="1.285" x="17.131" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="imaEulQ" width="3.001" height="1.285" x="12.246" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="i3hdBod" width="2.453" height="1.091" x="12.381" y="8.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="iPqJcqb" width="2.453" height="1.091" x="17.799" y="8.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/></filter><filter id="iGZyj0b" width=".787" height=".696" x="17.637" y="9.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".05"/></filter><filter id="issyv5b" width=".891" height=".913" x="18.477" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".1"/></filter><filter id="i73xFBb" width=".986" height="1.04" x="14.034" y="9.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".1"/></filter><filter id="iP40ibb" width=".913" height=".704" x="13.28" y="9.917" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".05"/></filter><filter id="is3gxbd" width="2.261" height=".978" x="17.829" y="8.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".1"/></filter><filter id="ijiv1md" width="2.261" height=".978" x="12.377" y="8.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".1"/></filter><filter id="ixOVi2d" width="4.312" height="4.613" x="9.835" y="4.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/><feGaussianBlur result="effect2_foregroundBlur_4002_2389" stdDeviation=".2"/></filter><filter id="igiPKxe" width="8.767" height="5.782" x="13.019" y="2.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2389"/><feGaussianBlur result="effect2_foregroundBlur_4002_2389" stdDeviation=".125"/></filter><filter id="iTVHxYb" width="9.346" height="5.558" x="14.326" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".5"/></filter><filter id="iHA7Sec" width="7.084" height="4.956" x="8.009" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2389" stdDeviation=".75"/></filter><linearGradient id="ib2QXPb" x1="20.883" x2="14.078" y1="4.009" y2="16.613" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="iNSLv7d" x1="16.549" x2="17.449" y1="19.059" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iw1p9ce" x1="26.353" x2="26.353" y1="20.725" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="izMYsjd" x1="26.502" x2="26.502" y1="20.725" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="i929CYc" x1="28.386" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iX7P55F" x1="24.525" x2="26.234" y1="26.03" y2="26.03" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ihsaQCd" x1="24.447" x2="26.156" y1="27.335" y2="27.335" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i3Vf8mb" x1="24.525" x2="26.234" y1="28.64" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ifRPnZd" x1="13.275" x2="13.82" y1="4.763" y2="6.037" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iY9HAAc" x1="9.005" x2="23.381" y1="15.771" y2="15.771" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iTrUkge" x1="9.005" x2="23.381" y1="15.741" y2="15.741" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iLeHoBc" x1="13.298" x2="13.843" y1="4.763" y2="6.037" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="ilyVu5b" x1="9.946" x2="11.186" y1="11.049" y2="11.049" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="idUvVUb" x1="15.251" x2="16.189" y1="12.293" y2="12.293" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="icCE8Jd" x1="16.189" x2="16.189" y1="13.092" y2="12.482" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iQOP9Rb" x1="16.268" x2="16.268" y1="13.066" y2="12.926" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="ik8yOGb" x1="15.125" x2="15.586" y1="14.502" y2="13.789" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iBK2AFe" x1="19.149" x2="18.836" y1="10.418" y2="10.612" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iH4M60d" x1="14.751" x2="14.437" y1="10.418" y2="10.612" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXiXb4d" x1="15.975" x2="16.813" y1="2.025" y2="6.975" gradientUnits="userSpaceOnUse"><stop class="nblx7ib8n"/><stop offset="1" class="h7is5ynaf"/></linearGradient><linearGradient id="iCultsb" x1="17.532" x2="17.532" y1="6.928" y2="6.6" gradientUnits="userSpaceOnUse"><stop class="hj8-3eb_v"/><stop offset="1" class="zofh5ufwh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-artist-medium-dark" /></template>
<style>
.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.acw_xab5u {
  stop-color: var(--svg-color--ed577d, #ED577D);
  stop-opacity: 0;
}

.af9b0l-ho {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ansdxpmor {
  d: path("M20.307 2.79c2.008.772 2.24 2.384 2.365 3.36c-3.464-.784-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.asvtvor4b {
  d: path("M11.12 4.973c.566-.599 1.637-.6 2.131-.51l.396 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.99 1.955-2.704 2.145c-.148-1.491.11-2.38.845-3.16");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b4ppyhbeb {
  d: path("M11.102 9.699h.012l-.01-.265l-.01-.307c.02-.948.574-1.316.81-1.438l.051-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.081-.193a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685c-2.672 0-4.86-1.882-4.983-4.685z");
}

.b8wkgccyf {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.533-4.61-2.954c-2.718.333-4.203 3.217-3.156 6.123z");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.bg01_ib1f {
  stop-color: var(--svg-color--6e3547, #6E3547);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c2bk9yb6a {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.44");
}

.c3x_amb3i {
  d: path("M19.169 10.662a.84.84 0 0 0-.232-.462l-.26.285l.117.228z");
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
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

.cmxz2bc_u {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.332 10.393c.265-.467.668-.836 1.537-.836c.38 0 .747.105 1.073.369c.268.217.232.495.024.6l-.556.317c-.651-.211-1.372-.24-2.079-.45");
}

.codu-dcmv {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.ct65j078y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 25.952h1.797");
}

.cu0ckn7fn {
  fill: var(--svg-color--000, #000);
  d: path("M17.862 10.78a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cvzy-mbfm {
  fill: var(--svg-color--b693a1, #B693A1);
  fill-rule: evenodd;
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.425-1.683-2.58-3.759-2.58s-3.758 1.155-3.758 2.58c0 .979.795 1.83 1.967 2.267c-.389.436-.404.98-.404 1.486l-.014.924c-.002.176.152.312.323.266c.381-.1.909-.315 1.264-.706c.378-.415.565-.814.622-1.433c.058.62.245 1.018.622 1.433c.356.391.883.605 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.cwp-36b8i {
  d: path("M11.504 12.57a1.61 1.61 0 1 0 0-3.217a1.61 1.61 0 0 0 0 3.218");
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dcez0yllb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.308 10.076c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.dh55xebqe {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.797 10.739l-.684 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.494-.377-.613 0");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.e8jd9xkck {
  stop-color: var(--svg-color--7c3759, #7C3759);
}

.ejom4oo7z {
  stop-color: var(--svg-color--d6a87f, #D6A87F);
}

.ekxbkpvzc {
  d: path("M5.143 26.475c-.02-3.41 1.582-6.47 4-8.5v11.98l-3.98.02z");
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.el-cg1bcl {
  stop-color: var(--svg-color--499da3, #499DA3);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.esrnr63bg {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.807 10.6l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.f0h--sbru {
  d: path("M14.213 13.777h3.86v3.094c0 .829-.82 1.5-1.65 1.5h-.464c-1.082 0-1.746-.671-1.746-1.5z");
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fbdpw4j2k {
  d: path("m25.169 16.58l.685-.092c.322 0 .735.47.735.793c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.058.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.169.102-.19");
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

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ge21ot55e {
  d: path("M16.544 15.742c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.gpmxoobeg {
  cx: 13.736px;
  cy: 10.269px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-1dj5qtj {
  d: path("M16.214 15.742h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.h7is5ynaf {
  stop-color: var(--svg-color--3f334f, #3F334F);
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hj8-3eb_v {
  stop-color: var(--svg-color--481b64, #481B64);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hvyevjb_p {
  d: path("M7.383 29.105a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i9gy75kqp {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.075c-1.248.082-2.375.649-2.978 1.739a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.365.87-.828c0-.053-.01-.107-.02-.161v-.01c-.162-.7-.054-1.29.279-1.882a.33.33 0 0 0-.075-.387");
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.izb4o5hjh {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
  stop-opacity: 0;
}

.j_c7fcbhg {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
}

.j-4y6njnd {
  stop-color: var(--svg-color--41225a, #41225A);
}

.j-p-7tbjt {
  stop-color: var(--svg-color--5eccf3, #5ECCF3);
}

.j0piksb8i {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jhj9frbew {
  d: path("M27.734 23.019a.97.97 0 0 1 .967.967V26.2h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jl5lrnj8e {
  cx: 13.736px;
  cy: 10.269px;
  rx: 0.39px;
  ry: 0.197px;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.js7kctros {
  stop-color: var(--svg-color--97769c, #97769C);
  stop-opacity: 0;
}

.jujuy5bla {
  stop-color: var(--svg-color--8e5e5c, #8E5E5C);
}

.juq22w2kb {
  stop-color: var(--svg-color--ab95b9, #AB95B9);
}

.jvqqj3hdm {
  stop-color: var(--svg-color--c01b54, #C01B54);
}

.jyboxmbnp {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
}

.jz78atb4u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 28.562h1.797");
}

.k8-cv7ymm {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.792 9.184l-.005.002a.268.268 0 0 1-.275-.46h.001l.003-.002l.01-.006a2 2 0 0 1 .148-.077c.099-.047.24-.107.41-.161c.34-.109.815-.2 1.329-.11a.268.268 0 0 1-.094.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.193");
}

.kbau0p37l {
  stop-color: var(--svg-color--824263, #824263);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kfex23bvh {
  cx: 16.143px;
  cy: 17.314px;
  rx: 4.489px;
  ry: 3.08px;
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kty0vsvue {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.921 8.726l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.058a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.529c.513-.09.989.001 1.329.11a3.3 3.3 0 0 1 .558.238l.01.006l.002.001z");
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7qllmb5o {
  stop-color: var(--svg-color--afa1a1, #AFA1A1);
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.ld2ijfp2p {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.586 3.171c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.921-5.24z");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
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

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m9kxmpbyp {
  stop-color: var(--svg-color--603a3e, #603A3E);
}

.mbdolbbcq {
  stop-color: var(--svg-color--ff5aaa, #FF5AAA);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mnu2otn4f {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.856 13.775a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.041a2.96 2.96 0 0 1-1.399.34c-.512 0-.994-.124-1.398-.34a.204.204 0 0 0-.247.044a.196.196 0 0 0-.021.247m3.333 0l-.042-.027zm0 0a1.982 1.982 0 0 1-3.333 0m0 0l.042-.027m-.042.027l.042-.027m0 0a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.422.345c-.52 0-1.01-.125-1.421-.345c-.14-.073-.292.09-.203.22Z");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.msj6cib4r {
  stop-color: var(--svg-color--824263, #824263);
}

.msq2krcmz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.58 9.616c.654 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.127");
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.mzth9rkss {
  d: path("M15.586 3.171c-1.133-.25-2.15.88-2.267 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.921-5.24z");
}

.n2f566bzz {
  stop-color: var(--svg-color--66606e, #66606E);
  stop-opacity: 0;
}

.n33kr0b_k {
  d: path("M14.82 10.675c0-.288-.234-.48-.297-.539l-.289.28l.178.36z");
}

.n39vpub1b {
  cx: 16.142px;
  cy: 17.066px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  rx: 3.844px;
  ry: 2.219px;
}

.n4l67hb-g {
  stop-color: var(--svg-color--ffcdab, #FFCDAB);
}

.nblx7ib8n {
  stop-color: var(--svg-color--352b40, #352B40);
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.o-yw38kdw {
  d: path("M21.017 12.036a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o7yoj0s6u {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.114a11.5 11.5 0 0 0-.432-1.876h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.112z");
}

.o9yul0q5w {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.048 10.393c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.6l.556.317c.652-.211 1.372-.24 2.079-.45");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.ok43c2qsk {
  d: path("M13.015 4.726c-.973-.093-2.504.103-3.147.213c-.174.135-.48.54-.31 1.08c.17.542.574.651.754.638c3.302-.637 3.92-1.815 2.703-1.93");
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

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.p07xrrbwq {
  fill-rule: evenodd;
  d: path("M23.375 12.371c.212-.435.324-.92.324-1.427c0-.467-.097-.905-.269-1.305h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.681 1.377a.56.56 0 0 1-.456.232q-.043 0-.085.002a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.456M11.115 9.7h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.05l-.083.194a2.3 2.3 0 0 1-1.24 1.255q-.027.013-.052.02c-.236.123-.79.49-.81 1.44l.01.306z");
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

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q_1nt5b-m {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.523 12.036a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qmqo746eg {
  stop-color: var(--svg-color--e0ad88, #E0AD88);
}

.qn-z6_0fu {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
  stop-opacity: 0;
}

.qob7fubko {
  stop-color: var(--svg-color--d42045, #D42045);
}

.qppq5ybfo {
  d: path("M24.005 25.3c0-.401.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qxv7yfbid {
  d: path("M21.017 12.57a1.61 1.61 0 1 0 0-3.217a1.61 1.61 0 0 0 0 3.218");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r1d1qpblj {
  d: path("M18.221 19.957c-.824-.79-1.717-.937-2.058-.89c-.133 1.792.011 2.527.722 3.308c.425.467 1.055.723 1.51.843c.204.054.388-.107.385-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.r52clnqnq {
  d: path("m15.807 10.6l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rqxxjhbor {
  d: path("M14.064 19.957c.824-.79 1.717-.937 2.058-.89c.133 1.792-.012 2.527-.723 3.308c-.424.467-1.054.723-1.51.843c-.203.054-.387-.107-.384-.318c.004-.362.011-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.s-d9s-q8p {
  d: path("M11.523 12.036a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.s-nbsobwa {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.338 8.589c-.322-.078-1.125-.04-1.66.344");
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.sau3ajb5n {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.129 8.589c.323-.078 1.125-.04 1.66.344");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.slu-4bgvl {
  d: path("M18.308 10.076c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sspaeirju {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.799 9.616c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.svrc61bac {
  fill: var(--svg-color--000, #000);
  d: path("M14.516 10.78a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.ta7eky02w {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
  stop-opacity: 0;
}

.teu3yl5ky {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M11.32 28.314a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.tm2bmw9uh {
  stop-color: var(--svg-color--4cc6ef, #4CC6EF);
}

.tpv18l7lf {
  d: path("M9.007 5.835c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.738.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H10.264c-.685 0-1.257-.429-1.257-1.139");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.u9dz2d52g {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M21.017 12.036a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.uj-94poim {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.977c-2.718.336-4.203 3.243-3.156 6.172z");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ujsn-3s1u {
  stop-color: var(--svg-color--865053, #865053);
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.vbuc_sdez {
  d: path("M9.143 17.99a10.96 10.96 0 0 1 7-2.515c2.658 0 5.097.943 7 2.514v11.986h-14z");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vfggmllpb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.298 4.42c.024.243.235 1.156.545 1.71");
}

.vfzn0su_w {
  d: path("M23.143 29.975v-12c2.44 2.023 4 5.078 4 8.494v3.506z");
}

.vn0ta5bom {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
}

.vnvkvjbds {
  stop-color: var(--svg-color--dd929a, #DD929A);
  stop-opacity: 0;
}

.vq38zyg1v {
  stop-color: var(--svg-color--c6a0e4, #C6A0E4);
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.w58fkm82c {
  d: path("M14.005 9.887a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
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

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x5zldhc4i {
  d: path("M18.374 9.887a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xxsjp-b7l {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M11.12 4.973c.566-.599 1.637-.6 2.131-.51l.396 1.29c-.253-.039-.478.05-.668.235c-.448 1.26-1.99 1.955-2.704 2.145c-.148-1.491.11-2.38.845-3.16");
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y00xmr1wl {
  stop-color: var(--svg-color--833965, #833965);
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ytueivx8a {
  stop-color: var(--svg-color--7c3759, #7C3759);
  stop-opacity: 0;
}

.yx08hybsl {
  d: path("M11.383 28.263a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z304cabpx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.275 4.42c.024.243.235 1.156.545 1.71");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.ze5nteb_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.447 27.257h1.797");
}

.zofh5ufwh {
  stop-color: var(--svg-color--481b64, #481B64);
  stop-opacity: 0;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
