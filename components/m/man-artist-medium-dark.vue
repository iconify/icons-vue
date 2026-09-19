<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHzmtfe)" class="vbuc_sdez"/><path fill="url(#inA3Tpe)" class="vbuc_sdez"/><path fill="url(#i6KXFTY)" class="vbuc_sdez"/><path fill="url(#i04jDnj)" class="vbuc_sdez"/><g filter="url(#iEsjFhL)"><path class="x4zektleg"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#ixzuGyd)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#iisZ6cb)"><path fill="url(#iZYJJTd)" class="rqxxjhbor"/><path fill="url(#iYcv9Wc)" class="rqxxjhbor"/></g><g filter="url(#ihUBdYb)"><path fill="url(#iCgYo9c)" class="r1d1qpblj"/><path fill="url(#iNSLv7d)" class="r1d1qpblj"/><path fill="url(#i8efCLe)" class="r1d1qpblj"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#iZLroYb)"><path fill="url(#iIo36rp)" class="c2bk9yb6a"/><path fill="url(#ignAelv)" class="c2bk9yb6a"/></g><path fill="url(#iqkeVzb)" class="b8wkgccyf"/><path fill="url(#ib6zMLd)" class="b8wkgccyf"/><g filter="url(#i1aRYgV)"><path fill="url(#izcCUib)" class="uj-94poim"/></g><g filter="url(#igoLi4d)"><path class="oh_l9db2x"/></g><g filter="url(#iQZ6xtd)"><path class="teu3yl5ky"/></g><g filter="url(#imZH5zc)"><path class="waw2uhbiy"/></g><g filter="url(#i4FrAWc)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#iMaS9Zd)"><path fill="url(#iV1Av9c)" class="yx08hybsl"/></g><g filter="url(#iiJZgxc)"><path fill="url(#iO8TsTc)" class="hvyevjb_p"/></g><path fill="url(#i4gM3yb)" class="hvyevjb_p"/><g filter="url(#ivF2Hhe)"><path fill="url(#ivW3tMd)" class="h36ax9_yz"/></g><path fill="url(#iK4s60b)" class="jhj9frbew"/><path fill="url(#ib9Hitc)" class="jhj9frbew"/><path fill="url(#iTfdAvb)" class="vfzn0su_w"/><path fill="url(#iTkYgvd)" class="vfzn0su_w"/><path fill="url(#iqMfzad)" class="vfzn0su_w"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iw1p9ce)" class="s80w1fafw"/><g filter="url(#i38vyXc)"><path fill="url(#i1FSYJc)" class="o7yoj0s6u"/><path fill="url(#iZLdWle)" class="o7yoj0s6u"/><path fill="url(#iZaoaBd)" class="o7yoj0s6u"/><path fill="url(#izMYsjd)" class="o7yoj0s6u"/></g><path fill="url(#ieEgdTd)" class="fbdpw4j2k"/><g filter="url(#iQ3CoZd)"><path fill="url(#iSbgAfc)" class="i9gy75kqp"/><path fill="url(#ibRVbPt)" class="i9gy75kqp"/><path fill="url(#iR3m9Xd)" class="i9gy75kqp"/><path fill="url(#ixbEKEd)" class="i9gy75kqp"/></g><g filter="url(#iEzPRXc)"><path fill="url(#i929CYc)" class="qppq5ybfo"/><path fill="url(#iILW5qO)" class="qppq5ybfo"/><path fill="url(#iBokQme)" class="qppq5ybfo"/><path fill="url(#iNISImd)" class="qppq5ybfo"/><path fill="url(#iCmIxte)" class="qppq5ybfo"/></g><g filter="url(#iris13y)"><path stroke="url(#iX7P55F)" class="ct65j078y"/></g><g filter="url(#iz3Stwc)"><path stroke="url(#ihsaQCd)" class="ze5nteb_r"/></g><g filter="url(#ifHTj9b)"><path stroke="url(#i3Vf8mb)" class="jz78atb4u"/></g><g filter="url(#i80Gytc)"><circle fill="url(#iGKf98b)" class="egv5tlxsw"/></g><g filter="url(#iQ1bzee)"><circle fill="url(#i1snZKc)" class="qui-_oqca"/></g><g filter="url(#ivVLqnb)"><circle fill="url(#iy01ZVb)" class="ir2xjwb1t"/><circle fill="url(#iqnaYOi)" class="ir2xjwb1t"/></g><g filter="url(#i6SR0tc)"><circle class="su2b_6bqt"/><circle fill="url(#iTaSdKc)" class="x_aemnb-y"/><circle fill="url(#ie0l8Db)" class="x_aemnb-y"/></g><g filter="url(#iVeMVxd)"><path fill="url(#iMhkXkU)" class="m4nm8bcwe"/></g><path fill="url(#iR8ioVf)" class="xg_wmrxtr"/><g filter="url(#iHZ10qd)"><path fill="url(#iMUenLb)" class="j184o3bxy"/><path fill="url(#iuxLF5F)" class="j184o3bxy"/><path fill="url(#isxkVgd)" class="j184o3bxy"/></g><path fill="url(#iq8mSjX)" class="j184o3bxy"/><path fill="url(#i1Utitd)" class="j184o3bxy"/><path fill="url(#iyK2ITc)" class="j184o3bxy"/><path fill="url(#iw5AIfe)" class="j184o3bxy"/><path fill="url(#iqxYRMe)" class="j184o3bxy"/><g filter="url(#ij8lmab)"><path fill="url(#igCHcpf)" class="z5guv0bai"/></g><g filter="url(#iz0ptvc)"><path class="ia8695bif"/></g><g filter="url(#ij8lj4b)"><path class="uogoi3ujg"/><path fill="url(#iQ8Cs4D)" class="e2g9evb1w"/><path fill="url(#iA6sqqc)" class="e2g9evb1w"/><path fill="url(#ifzes5d)" class="e2g9evb1w"/><path fill="url(#igqsBYb)" class="e2g9evb1w"/></g><path fill="url(#iPe6vne)" class="e2g9evb1w"/><path stroke="url(#i9iElNc)" class="usvtvzbyr"/><g filter="url(#i1faojb)"><path class="mcql_eiav"/><path fill="url(#imLQLZs)" class="kvj9yyb7r"/></g><g filter="url(#iLVUoZb)"><path class="ljlltpb2v"/><path fill="url(#iT8lxAd)" class="c4tjdqbln"/></g><path class="oehpcebgh"/><path fill="url(#imgu3Ud)" class="w6z2wibej"/><path class="b_88t9boz"/><g filter="url(#i3KGvie)"><path class="ex00rfbvi"/><path fill="url(#ibahIJc)" class="e5r7ctb5l"/></g><g filter="url(#iEk1nQd)"><path fill="url(#ijAHH6d)" class="dpz9ajbsg"/></g><path class="yo0o_ccav"/><path fill="url(#iS4sOHd)" class="grvk_zl7v"/><path class="ds-pvtb6p"/><g filter="url(#isjELnc)"><path fill="url(#iBk7rXb)" class="f8vg37b5a"/></g><g filter="url(#iKSkBNb)"><ellipse transform="rotate(-27.914 13.652 9.878)" class="y92d2fb8p"/><ellipse fill="url(#iJt1W1T)" transform="rotate(-27.914 13.652 9.878)" class="dk3-oebid"/></g><g filter="url(#iqMpPZc)"><path stroke="url(#iDeOgHc)" class="vnb-vub6z"/></g><g filter="url(#iJ6RCQP)"><path stroke="url(#i3SjhAc)" class="wnzx68uqt"/></g><path class="mk9cbeb_z"/><path fill="url(#iLkxb5d)" class="tpv18l7lf"/><g filter="url(#iX8T9Kb)"><path fill="url(#iwfm65c)" class="ansdxpmor"/></g><g filter="url(#iObuHid)"><path fill="url(#in6AZkm)" class="ok43c2qsk"/></g><defs><radialGradient id="iHzmtfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.975)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="i6KXFTY" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.975)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="iYcv9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.422 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iV1Av9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.783)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="ivW3tMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42193 -3.27267 0 16.143 17.096)" gradientUnits="userSpaceOnUse"><stop offset=".395" class="skdvgyl5e"/><stop offset="1" class="id0p6ebfb"/></radialGradient><radialGradient id="iK4s60b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59797 1.31329 -1.29023 -1.56991 28.701 23.652)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="ib9Hitc" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 28.466 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibRVbPt" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.595)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="iILW5qO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.656 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iBokQme" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.656 26.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iNISImd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.656 27.824)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iCmIxte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.656 29.175)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iGKf98b" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.686 10.657)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iqnaYOi" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.252 10.392)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iTaSdKc" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.838 11.479)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="ie0l8Db" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.88 10.657)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iMhkXkU" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.59375 -.72995 0 21.234 6.957)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="nfcjmccxh"/><stop offset="1" class="zkxwptb2v"/></radialGradient><radialGradient id="iR8ioVf" cx="0" cy="0" r="1" gradientTransform="matrix(.125 2.15625 -.9303 .05393 11.362 8.894)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="sa7b0q5hl"/><stop offset="1" class="okv9i9k3u"/></radialGradient><radialGradient id="iuxLF5F" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.458 9.384)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="isxkVgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.895 9.518)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iyK2ITc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40625 -11.4065 0 16.136 8.903)" gradientUnits="userSpaceOnUse"><stop offset=".665" class="rko8b-bmk"/><stop offset=".885" class="ddlaug5pl"/><stop offset=".993" class="k66yh30bl"/></radialGradient><radialGradient id="iw5AIfe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59272 -.54454 .34504 1.64283 10.295 17.478)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="igqsBYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.437 12.265)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="imLQLZs" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.78641 .30854 18.555 8.57)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iT8lxAd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.79 -3.672)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="imgu3Ud" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.29 9.974)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ibahIJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18.062 10.058)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iS4sOHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.923 9.974)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iJt1W1T" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.836 -1.616)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLkxb5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iwfm65c" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="in6AZkm" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.377 3.233)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="iEsjFhL" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".75"/></filter><filter id="ixzuGyd" width="8.987" height="5.737" x="11.649" y="14.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".2"/></filter><filter id="iisZ6cb" width="2.812" height="4.17" x="13.354" y="19.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="ihUBdYb" width="2.762" height="4.17" x="16.118" y="19.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="iZLroYb" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="i1aRYgV" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2390" result="effect2_innerShadow_4002_2390"/></filter><filter id="igoLi4d" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".075"/></filter><filter id="iQZ6xtd" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".075"/></filter><filter id="imZH5zc" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".075"/></filter><filter id="i4FrAWc" width="2.58" height="2.68" x="7.143" y="22.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2390" result="effect2_innerShadow_4002_2390"/></filter><filter id="iMaS9Zd" width="2.58" height="2.68" x="10.143" y="25.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2390" result="effect2_innerShadow_4002_2390"/></filter><filter id="iiJZgxc" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2390" result="effect2_innerShadow_4002_2390"/></filter><filter id="ivF2Hhe" width="3.818" height="6.2" x="14.233" y="12.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.12549 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="i38vyXc" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="iQ3CoZd" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="iEzPRXc" width="4.846" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="iris13y" width="2.097" height=".3" x="24.375" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".05"/></filter><filter id="iz3Stwc" width="2.097" height=".3" x="24.297" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".05"/></filter><filter id="ifHTj9b" width="2.097" height=".3" x="24.375" y="28.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".05"/></filter><filter id="i80Gytc" width="3.542" height="3.342" x="9.686" y="8.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="iQ1bzee" width="2.992" height="2.992" x="9.861" y="9.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".25"/></filter><filter id="ivVLqnb" width="3.592" height="3.592" x="19.208" y="8.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="i6SR0tc" width="2.992" height="2.992" x="19.384" y="9.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".25"/></filter><filter id="iVeMVxd" width="2.025" height="4.023" x="20.504" y="6.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="iHZ10qd" width="10.378" height="12.189" x="10.947" y="5.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="ij8lmab" width="8.25" height="7.07" x="14.28" y="3.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation="1"/></filter><filter id="iz0ptvc" width="3.262" height="4.184" x="14.239" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".375"/></filter><filter id="ij8lj4b" width="2.379" height="3.184" x="14.92" y="9.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".125"/></filter><filter id="i1faojb" width="2.982" height="1.874" x="17.293" y="7.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="iLVUoZb" width="2.982" height="1.874" x="12.14" y="7.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2390"/></filter><filter id="i3KGvie" width=".787" height=".697" x="17.556" y="9.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".05"/></filter><filter id="iEk1nQd" width=".892" height=".914" x="18.396" y="9.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".1"/></filter><filter id="isjELnc" width=".987" height="1.041" x="13.95" y="9.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".1"/></filter><filter id="iKSkBNb" width=".914" height=".705" x="13.195" y="9.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".05"/></filter><filter id="iqMpPZc" width="2.451" height="1.031" x="17.472" y="7.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".1"/></filter><filter id="iJ6RCQP" width="2.579" height="1.139" x="12.222" y="7.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".1"/></filter><filter id="iX8T9Kb" width="9.346" height="5.558" x="14.326" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".5"/></filter><filter id="iObuHid" width="7.084" height="4.956" x="8.009" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2390" stdDeviation=".75"/></filter><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="iNSLv7d" x1="16.549" x2="17.449" y1="19.059" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iw1p9ce" x1="26.353" x2="26.353" y1="20.725" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="izMYsjd" x1="26.502" x2="26.502" y1="20.725" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="i929CYc" x1="28.386" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iX7P55F" x1="24.525" x2="26.234" y1="26.03" y2="26.03" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ihsaQCd" x1="24.447" x2="26.156" y1="27.335" y2="27.335" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i3Vf8mb" x1="24.525" x2="26.234" y1="28.64" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i1snZKc" x1="11.357" x2="10.716" y1="10.936" y2="10.936" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iy01ZVb" x1="21.967" x2="21.147" y1="9.564" y2="12.103" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iMUenLb" x1="20.149" x2="12.505" y1="11.047" y2="12.186" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iq8mSjX" x1="8.534" x2="10.416" y1="13.613" y2="13.545" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="i1Utitd" x1="18.799" x2="17.743" y1="12.774" y2="12.673" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iqxYRMe" x1="16.136" x2="16.136" y1="6.809" y2="7.278" gradientUnits="userSpaceOnUse"><stop class="o6mjfcken"/><stop offset="1" class="byo_06b2a"/></linearGradient><linearGradient id="igCHcpf" x1="15.577" x2="23.729" y1="8.059" y2="5.141" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iQ8Cs4D" x1="15.245" x2="16.184" y1="11.707" y2="11.707" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iA6sqqc" x1="17.049" x2="16.022" y1="12.029" y2="12.015" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="ifzes5d" x1="16.304" x2="16.304" y1="12.772" y2="12.199" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iPe6vne" x1="16.235" x2="16.235" y1="12.814" y2="12.646" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="i9iElNc" x1="15.072" x2="15.507" y1="14.389" y2="13.701" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ijAHH6d" x1="19.069" x2="18.755" y1="10.028" y2="10.222" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBk7rXb" x1="14.668" x2="14.354" y1="10.028" y2="10.222" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDeOgHc" x1="19.085" x2="18.664" y1="7.886" y2="7.027" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i3SjhAc" x1="13.775" x2="12.585" y1="7.759" y2="7.259" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-artist-medium-dark" /></template>
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

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.ansdxpmor {
  d: path("M20.307 2.79c2.008.772 2.24 2.384 2.365 3.36c-3.464-.784-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.b_88t9boz {
  fill: var(--svg-color--000, #000);
  d: path("M17.781 10.39a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.061-.235");
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b8wkgccyf {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.533-4.61-2.954c-2.718.333-4.203 3.217-3.156 6.123z");
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.byo_06b2a {
  stop-color: var(--svg-color--7a463e, #7A463E);
  stop-opacity: 0;
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c2bk9yb6a {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.44");
}

.c4tjdqbln {
  d: path("M12.332 7.934h.002l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.242-.14.42-.211c.36-.142.873-.257 1.495-.159a.534.534 0 0 1-.167 1.056a1.77 1.77 0 0 0-.935.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.825");
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.codu-dcmv {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
  stop-opacity: 0;
}

.ct65j078y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 25.952h1.797");
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.ddlaug5pl {
  stop-color: var(--svg-color--7d485c, #7D485C);
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dk3-oebid {
  cx: 13.652px;
  cy: 9.878px;
  rx: 0.39px;
  ry: 0.197px;
}

.dpz9ajbsg {
  d: path("M19.088 10.272a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.ds-pvtb6p {
  fill: var(--svg-color--000, #000);
  d: path("M14.433 10.39a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.235");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2g9evb1w {
  d: path("m15.727 10.371l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.378-.647-.378-.766 0");
}

.e5r7ctb5l {
  d: path("M18.227 9.686c.063.085-.07.188-.22.301c-.152.114-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.136.389-.05");
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.egv5tlxsw {
  cx: 11.357px;
  cy: 10.657px;
  r: 1.671px;
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

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.ex00rfbvi {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.227 9.686c.063.085-.07.188-.22.301c-.152.114-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.136.389-.05");
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.f8vg37b5a {
  d: path("M14.737 10.285c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fbdpw4j2k {
  d: path("m25.169 16.58l.685-.092c.322 0 .735.47.735.793c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.058.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.169.102-.19");
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.grvk_zl7v {
  d: path("M13.921 9.497a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h36ax9_yz {
  d: path("M16.142 18.394c-1.05 0-1.908-.507-1.908-1.291V14.41c0-1.11.858-2.017 1.908-2.017s1.91.907 1.91 2.017v2.692c0 .796-.86 1.29-1.91 1.29");
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hvyevjb_p {
  d: path("M7.383 29.105a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.i9gy75kqp {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.075c-1.248.082-2.375.649-2.978 1.739a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.365.87-.828c0-.053-.01-.107-.02-.161v-.01c-.162-.7-.054-1.29.279-1.882a.33.33 0 0 0-.075-.387");
}

.ia8695bif {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.834 10.535l-.821 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.489-.7l-.499-1.7c-.107-.377-.283-.377-.395 0");
}

.id0p6ebfb {
  stop-color: var(--svg-color--6d3251, #6D3251);
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.ir2xjwb1t {
  cx: 20.879px;
  cy: 10.657px;
  r: 1.671px;
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

.j184o3bxy {
  d: path("m11.005 10.044l.049.001s-.054-.854-.107-1.441c0-.267.107-.587.322-.748l.16-.16c.27-.213.377-.534.377-.854v-.854a.52.52 0 0 1 .43-.534c.643-.16 1.986-.427 3.918-.427s3.276.267 3.92.427c.215.054.43.267.43.534v.854c0 .32.16.64.375.854c.464.461.471.546.43.961c-.054.534-.108 1.442-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.213 3.005h-3.213c-1.714 0-3.053-1.234-3.214-3.005z");
}

.jhj9frbew {
  d: path("M27.734 23.019a.97.97 0 0 1 .967.967V26.2h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
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

.k66yh30bl {
  stop-color: var(--svg-color--863971, #863971);
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

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.kvj9yyb7r {
  d: path("M19.833 7.934h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.84 2.84 0 0 0-1.494-.159a.534.534 0 1 0 .166 1.056c.399-.063.717.01.935.096a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .679-.825");
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
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

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljlltpb2v {
  fill: var(--svg-color--352827, #352827);
  d: path("M12.332 7.934h.002l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.242-.14.42-.211c.36-.142.873-.257 1.495-.159a.534.534 0 0 1-.167 1.056a1.77 1.77 0 0 0-.935.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.825");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.m4nm8bcwe {
  d: path("M20.504 6.073v.769c0 .32.15.652.366.865c.4.395.481.512.437.945c-.045.45-.083.975-.116 1.444a.62.62 0 0 0 .61-.531l.594-3.043q.04-.228.033-.45z");
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

.mcql_eiav {
  fill: var(--svg-color--352827, #352827);
  d: path("M19.833 7.934h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.84 2.84 0 0 0-1.494-.159a.534.534 0 1 0 .166 1.056c.399-.063.717.01.935.096a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .679-.825");
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mk9cbeb_z {
  fill: var(--svg-color--352b40, #352B40);
  d: path("M9.007 5.835c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.738.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H10.264c-.685 0-1.257-.429-1.257-1.139");
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.n2f566bzz {
  stop-color: var(--svg-color--66606e, #66606E);
  stop-opacity: 0;
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

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nfcjmccxh {
  stop-color: var(--svg-color--3f3c3d, #3F3C3D);
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o6mjfcken {
  stop-color: var(--svg-color--7a463e, #7A463E);
}

.o7yoj0s6u {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.114a11.5 11.5 0 0 0-.432-1.876h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.112z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oehpcebgh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.5 9.225c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.272A1.4 1.4 0 0 1 18.5 9.225");
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.ok43c2qsk {
  d: path("M13.015 4.726c-.973-.093-2.504.103-3.147.213c-.174.135-.48.54-.31 1.08c.17.542.574.651.754.638c3.302-.637 3.92-1.815 2.703-1.93");
}

.okv9i9k3u {
  stop-color: var(--svg-color--2e2c2d, #2E2C2D);
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
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

.qui-_oqca {
  cx: 11.357px;
  cy: 10.657px;
  r: 0.996px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r1d1qpblj {
  d: path("M18.221 19.957c-.824-.79-1.717-.937-2.058-.89c-.133 1.792.011 2.527.722 3.308c.425.467 1.055.723 1.51.843c.204.054.388-.107.385-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rqxxjhbor {
  d: path("M14.064 19.957c.824-.79 1.717-.937 2.058-.89c.133 1.792-.012 2.527-.723 3.308c-.424.467-1.054.723-1.51.843c-.203.054-.387-.107-.384-.318c.004-.362.011-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.sa7b0q5hl {
  stop-color: var(--svg-color--211121, #211121);
}

.skdvgyl5e {
  stop-color: var(--svg-color--7c3954, #7C3954);
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.su2b_6bqt {
  cx: 20.88px;
  cy: 10.657px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
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

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.uj-94poim {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.977c-2.718.336-4.203 3.243-3.156 6.172z");
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
}

.uogoi3ujg {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.727 10.371l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.378-.647-.378-.766 0");
}

.usvtvzbyr {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.746 13.417c.394.205.863.323 1.364.323c.505 0 .969-.118 1.363-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.989-.28l2.948.253m-2.948-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.221.253m3.21.028l-.041-.028m.042.028l-.042-.028m.042.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028c-.335.508-.92.847-1.584.847c-.666 0-1.25-.339-1.585-.847m-.041.028l.041-.028m-.041.028l.041-.028");
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vbuc_sdez {
  d: path("M9.143 17.99a10.96 10.96 0 0 1 7-2.515c2.658 0 5.097.943 7 2.514v11.986h-14z");
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vfzn0su_w {
  d: path("M23.143 29.975v-12c2.44 2.023 4 5.078 4 8.494v3.506z");
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vn0ta5bom {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
}

.vnb-vub6z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.772 7.79c.43-.076 1.27-.054 1.85.398");
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

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w6z2wibej {
  d: path("M18.293 9.497a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wnzx68uqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.547 8.309c.328-.29 1.043-.595 1.93-.453");
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.x_aemnb-y {
  cx: 20.88px;
  cy: 10.657px;
  r: 0.996px;
}

.x4zektleg {
  fill: var(--svg-color--b693a1, #B693A1);
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.425-1.683-2.58-3.759-2.58s-3.758 1.155-3.758 2.58c0 .979.795 1.83 1.967 2.267c-.389.436-.404.98-.404 1.486l-.014.924c-.002.176.152.312.323.266c.381-.1.909-.315 1.264-.706c.378-.415.565-.814.622-1.433c.058.62.245 1.018.622 1.433c.356.391.883.605 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xg_wmrxtr {
  d: path("M9.878 6.073q-.012.196.012.395l.59 3.043a.634.634 0 0 0 .596.532c-.013-.196-.024-.539-.035-.841c-.01-.271-.018-.51-.024-.584c0-.267.108-.602.323-.762l.16-.16c.27-.213.377-.534.377-.854v-.77z");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.y92d2fb8p {
  cx: 13.652px;
  cy: 9.878px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yo0o_ccav {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.714 9.225c-.653 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.13");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.yx08hybsl {
  d: path("M11.383 28.263a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z5guv0bai {
  d: path("m20.077 5.027l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
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

.zkxwptb2v {
  stop-color: var(--svg-color--343132, #343132);
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
