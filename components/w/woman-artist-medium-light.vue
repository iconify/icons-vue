<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isOCKxc)"><path fill="url(#i2erYkc)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#iEtnYcb)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#iJDsSHc)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#iZjE0Ac)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#ia9QIhd)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#ihkNmQR)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#i58RCZd)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#imL4YSc)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#iJPalad)" clip-rule="evenodd" class="f6vaurbjp"/><path fill="url(#iJqihhe)" clip-rule="evenodd" class="f6vaurbjp"/></g><path fill="url(#iHzmtfe)" class="vbuc_sdez"/><path fill="url(#inA3Tpe)" class="vbuc_sdez"/><path fill="url(#i6KXFTY)" class="vbuc_sdez"/><path fill="url(#i04jDnj)" class="vbuc_sdez"/><g filter="url(#iUnPxUb)"><path clip-rule="evenodd" class="cvzy-mbfm"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#iPH71Ib)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#iVZAneH)"><path fill="url(#iZYJJTd)" class="dqgu8t6sf"/><path fill="url(#in5HY3d)" class="dqgu8t6sf"/></g><g filter="url(#iK6zICb)"><path fill="url(#iCgYo9c)" class="kj7yu4cxe"/><path fill="url(#izKufic)" class="kj7yu4cxe"/><path fill="url(#i8efCLe)" class="kj7yu4cxe"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#iTefnZc)"><path fill="url(#iIo36rp)" class="c2bk9yb6a"/><path fill="url(#ignAelv)" class="c2bk9yb6a"/></g><path fill="url(#iqkeVzb)" class="b8wkgccyf"/><path fill="url(#ib6zMLd)" class="b8wkgccyf"/><g filter="url(#i8sPsMe)"><path fill="url(#izcCUib)" class="uj-94poim"/></g><g filter="url(#iEhGqUb)"><path class="oh_l9db2x"/></g><g filter="url(#ioObW8b)"><path class="teu3yl5ky"/></g><g filter="url(#i7NRaUM)"><path class="waw2uhbiy"/></g><g filter="url(#iwuZvgc)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#iC7Dlpc)"><path fill="url(#iV1Av9c)" class="yx08hybsl"/></g><g filter="url(#il49kwc)"><path fill="url(#iO8TsTc)" class="hvyevjb_p"/></g><path fill="url(#i4gM3yb)" class="hvyevjb_p"/><path fill="url(#iZ7bhMd)" class="hfzp6f8qe"/><path fill="url(#imiIHpc)" class="hfzp6f8qe"/><path fill="url(#iTfdAvb)" class="vfzn0su_w"/><path fill="url(#iTkYgvd)" class="vfzn0su_w"/><path fill="url(#iqMfzad)" class="vfzn0su_w"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iw1p9ce)" class="s80w1fafw"/><g filter="url(#iYHat4b)"><path fill="url(#i1FSYJc)" class="o7yoj0s6u"/><path fill="url(#iZLdWle)" class="o7yoj0s6u"/><path fill="url(#iZaoaBd)" class="o7yoj0s6u"/><path fill="url(#izMYsjd)" class="o7yoj0s6u"/></g><path fill="url(#ieEgdTd)" class="d2y5bebri"/><g filter="url(#iADfZke)"><path fill="url(#iSbgAfc)" class="n_y6p8b5d"/><path fill="url(#ibiMAze)" class="n_y6p8b5d"/><path fill="url(#i4Ff9tu)" class="n_y6p8b5d"/><path fill="url(#ixbEKEd)" class="n_y6p8b5d"/></g><g filter="url(#i1NQMBb)"><path fill="url(#iSUOq4d)" class="qppq5ybfo"/><path fill="url(#iMKyiCb)" class="qppq5ybfo"/><path fill="url(#iqjonuc)" class="qppq5ybfo"/><path fill="url(#iXj5Yfb)" class="qppq5ybfo"/><path fill="url(#ioyKhxe)" class="qppq5ybfo"/></g><g filter="url(#ioq3ACe)"><path stroke="url(#i6AMKhc)" class="ct65j078y"/></g><g filter="url(#ioJxZDe)"><path stroke="url(#iWhXobb)" class="ze5nteb_r"/></g><g filter="url(#iB14SYd)"><path stroke="url(#izVZxIb)" class="jz78atb4u"/></g><g filter="url(#iin9Y6d)"><path fill="url(#iPoFNTb)" class="j0kpihu0z"/><path fill="url(#irMtWec)" class="j0kpihu0z"/></g><path fill="url(#iY9HAAc)" class="ge21ot55e"/><path fill="url(#iTrUkge)" class="h-1dj5qtj"/><g filter="url(#i0pESJR)"><path fill="url(#i07cd7w)" class="g2eglgbrp"/></g><g filter="url(#irGT8Qc)"><path fill="url(#igGHxle)" class="p717knbwi"/><path fill="url(#i00tl0d)" class="p717knbwi"/></g><g filter="url(#iWsCpXJ)"><path class="i57ba-bku"/><path fill="url(#iBvq9He)" class="codnw0btf"/></g><g filter="url(#ikHjtqB)"><path class="rdmv99d9g"/><path fill="url(#iO8UQzc)" class="zetkf7bcl"/></g><g filter="url(#iA5WNvS)"><path fill="url(#iRTLN9p)" class="wig7w8bbb"/><path fill="url(#iWaNVdd)" class="wig7w8bbb"/><path fill="url(#iy93B5c)" class="wig7w8bbb"/><path fill="url(#icN7dYc)" class="wig7w8bbb"/><path fill="url(#iCSVgVc)" class="wig7w8bbb"/><path fill="url(#iraLvcb)" class="wig7w8bbb"/><path fill="url(#iAxFyqb)" class="wig7w8bbb"/></g><path fill="url(#iFAL2Gc)" class="uaxfwirbj"/><path fill="url(#ipBqJub)" class="uaxfwirbj"/><g filter="url(#ir7RTBe)"><path class="gi6g7ch9s"/></g><g filter="url(#i0LXImF)"><path class="nahyo0b6p"/><path fill="url(#iZw6srb)" class="utmespb7f"/><path fill="url(#iq3Z1Tb)" class="utmespb7f"/><path fill="url(#isuSrEe)" class="utmespb7f"/></g><path fill="url(#iZ8qBuc)" class="utmespb7f"/><path fill="url(#ijnpq9c)" class="utmespb7f"/><path stroke="url(#iSdz8Le)" class="ya4ltpbbw"/><g filter="url(#i1zxaRb)"><path class="psj_4kbpb"/></g><g filter="url(#iMud6Ud)"><path class="enx3m3bqe"/></g><g filter="url(#ipd39Bd)"><path class="ciz16sbbk"/></g><g filter="url(#iIZm3xc)"><path clip-rule="evenodd" class="wgk8d-b6o"/></g><path class="smq8uccvh"/><path fill="url(#iyQSjrc)" class="dr_fk9b-q"/><path class="lo1e0dkdv"/><g filter="url(#imkZEic)"><path class="glra2ybwu"/><path fill="url(#iYi2i8b)" class="urlz13_nx"/></g><g filter="url(#imKl6Tb)"><path fill="url(#iY467re)" class="zrzrn4ewq"/></g><path class="pn6srrrig"/><path fill="url(#iAP4Ggc)" class="grr7xmbed"/><path class="efvxagg0z"/><g filter="url(#iVyIWud)"><path fill="url(#iYyIu6b)" class="s_fkyyriu"/></g><g filter="url(#iX3Gq9c)"><ellipse transform="rotate(-27.914 13.736 10.37)" class="pr51ldkyz"/><ellipse fill="url(#igUTXlc)" transform="rotate(-27.914 13.736 10.37)" class="b60s00byr"/></g><g filter="url(#iHWRTbe)"><path class="gr5j-eb8u"/></g><g filter="url(#iHt5dnc)"><path class="hn6rf3bxr"/></g><g filter="url(#iz5Qcrb)"><path fill="url(#i6ugz7d)" class="retif0bee"/><path fill="url(#iADBYHe)" class="retif0bee"/></g><g filter="url(#iCP0pwd)"><path fill="url(#iaOtAkb)" class="ltzpfz2jy"/><path fill="url(#ihtkaqd)" class="ltzpfz2jy"/><path fill="url(#iWDvRIc)" class="ltzpfz2jy"/></g><g filter="url(#irzwwkF)"><path stroke="url(#i1zBAGd)" class="f320fubee"/></g><path fill="url(#iXiXb4d)" class="tpv18l7lf"/><path fill="url(#iLkxb5d)" class="tpv18l7lf"/><path fill="url(#iCultsb)" class="tpv18l7lf"/><g filter="url(#i9JNZqc)"><path fill="url(#iwfm65c)" class="ansdxpmor"/></g><g filter="url(#iNhEeLc)"><path fill="url(#in6AZkm)" class="ok43c2qsk"/></g><defs><radialGradient id="iEtnYcb" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.882 16.883)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iJDsSHc" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.191 11.94)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iZjE0Ac" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.166 9.156)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="ia9QIhd" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.738 8.593)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="ihkNmQR" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.48 4.242)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="i58RCZd" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 12.351 3.49)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="imL4YSc" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.674 7.43)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iJPalad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.698 10.212)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iJqihhe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.43 12.995)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iHzmtfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.975)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="i6KXFTY" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.975)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="in5HY3d" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.421 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iV1Av9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.783)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="iZ7bhMd" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.869 16.305)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="j1n1ygxtd"/><stop offset="1" class="mdv9qbyfi"/></radialGradient><radialGradient id="imiIHpc" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 28.466 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="jt362mrmb"/><stop offset="1" class="yfkzyxbts"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibiMAze" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.594)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="i4Ff9tu" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.611)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="iMKyiCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.656 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iqjonuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.656 26.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iXj5Yfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.656 27.824)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ioyKhxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.656 29.175)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iPoFNTb" cx="0" cy="0" r="1" gradientTransform="rotate(138.439 5.875 11.759)scale(2.57895 1.90476)" gradientUnits="userSpaceOnUse"><stop class="sv486sbdz"/><stop offset="1" class="gol6j1bef"/></radialGradient><radialGradient id="irMtWec" cx="0" cy="0" r="1" gradientTransform="matrix(0 .75 -2.28629 0 16.143 16.597)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="hy6u5wycq"/><stop offset="1" class="dlrmvbc9h"/></radialGradient><radialGradient id="igGHxle" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.23 11.503)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="i00tl0d" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 21.252 9.282)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iBvq9He" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.959 -52.398)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iO8UQzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.523 11.064)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iRTLN9p" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 19.049 10.526)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iWaNVdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 18.09 11.223)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iy93B5c" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 14.01 17.309)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="icN7dYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.02521 -8.49258 0 16.19 10.239)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="m340xmbug"/><stop offset=".912" class="sm66mwbyu"/><stop offset="1" class="ht0s1ib6z"/></radialGradient><radialGradient id="iCSVgVc" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.983 6.993)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iraLvcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.49 10.108)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iAxFyqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.271 10.195)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iFAL2Gc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.285 11.595)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="ipBqJub" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.69 5.02)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iZw6srb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.974 12.322)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="ijnpq9c" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.321 8.622)scale(1.57489 2.10944)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iyQSjrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.372 10.466)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iYi2i8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.143 10.55)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAP4Ggc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 14.007 10.466)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="igUTXlc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.12 -1.411)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6ugz7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 10.232 4.815)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iADBYHe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.474 5.05)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iaOtAkb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 18.1 3.139)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="ihtkaqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.503 4.312)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iWDvRIc" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.616 -.253)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iLkxb5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iwfm65c" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="in6AZkm" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.377 3.233)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="isOCKxc" width="15.268" height="15.768" x="8.68" y="1.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="iUnPxUb" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".75"/></filter><filter id="iPH71Ib" width="8.987" height="5.737" x="11.649" y="14.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".2"/></filter><filter id="iVZAneH" width="2.812" height="4.17" x="13.354" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="iK6zICb" width="2.762" height="4.17" x="16.118" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="iTefnZc" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="i8sPsMe" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2395" result="effect2_innerShadow_4002_2395"/></filter><filter id="iEhGqUb" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".075"/></filter><filter id="ioObW8b" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".075"/></filter><filter id="i7NRaUM" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".075"/></filter><filter id="iwuZvgc" width="2.58" height="2.68" x="7.143" y="22.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2395" result="effect2_innerShadow_4002_2395"/></filter><filter id="iC7Dlpc" width="2.58" height="2.68" x="10.143" y="25.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2395" result="effect2_innerShadow_4002_2395"/></filter><filter id="il49kwc" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2395" result="effect2_innerShadow_4002_2395"/></filter><filter id="iYHat4b" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="iADfZke" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="i1NQMBb" width="4.846" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.486275 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="ioq3ACe" width="2.097" height=".3" x="24.375" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".05"/></filter><filter id="ioJxZDe" width="2.097" height=".3" x="24.297" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".05"/></filter><filter id="iB14SYd" width="2.097" height=".3" x="24.375" y="28.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".05"/></filter><filter id="iin9Y6d" width="3.859" height="4.694" x="14.213" y="13.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.380392 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="i0pESJR" width="3.368" height="3.468" x="9.895" y="9.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="irGT8Qc" width="3.218" height="3.468" x="19.408" y="9.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="iWsCpXJ" width="3.148" height="3.148" x="19.443" y="9.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".25"/></filter><filter id="ikHjtqB" width="2.948" height="2.948" x="10.049" y="9.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".2"/></filter><filter id="iA5WNvS" width="10.191" height="10.977" x="11.094" y="6.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="ir7RTBe" width="2.877" height="3.682" x="14.589" y="10.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".25"/></filter><filter id="i0LXImF" width="2.377" height="3.182" x="15.001" y="10.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".125"/></filter><filter id="i1zxaRb" width="3.001" height="1.285" x="17.132" y="9.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="iMud6Ud" width="3.001" height="1.285" x="12.246" y="9.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="ipd39Bd" width="2.453" height="1.091" x="12.381" y="8.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="iIZm3xc" width="2.453" height="1.091" x="17.799" y="8.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2395"/></filter><filter id="imkZEic" width=".787" height=".696" x="17.637" y="10.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".05"/></filter><filter id="imKl6Tb" width=".891" height=".913" x="18.477" y="10.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".1"/></filter><filter id="iVyIWud" width=".986" height="1.04" x="14.034" y="10.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".1"/></filter><filter id="iX3Gq9c" width=".913" height=".704" x="13.28" y="10.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".05"/></filter><filter id="iHWRTbe" width="2.661" height="1.378" x="17.629" y="8.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".2"/></filter><filter id="iHt5dnc" width="2.661" height="1.378" x="12.177" y="8.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".2"/></filter><filter id="iz5Qcrb" width="4.287" height="5.25" x="9.93" y="4.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".25"/></filter><filter id="iCP0pwd" width="8.914" height="5.78" x="12.872" y="2.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".125"/></filter><filter id="irzwwkF" width="1.145" height="2.31" x="12.998" y="4.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".1"/></filter><filter id="i9JNZqc" width="9.346" height="5.558" x="14.326" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".5"/></filter><filter id="iNhEeLc" width="7.084" height="4.956" x="8.009" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2395" stdDeviation=".75"/></filter><linearGradient id="i2erYkc" x1="20.883" x2="14.078" y1="4.111" y2="16.715" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="izKufic" x1="16.549" x2="17.449" y1="19.058" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iw1p9ce" x1="26.353" x2="26.353" y1="20.725" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="izMYsjd" x1="26.502" x2="26.502" y1="20.725" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="iSUOq4d" x1="28.386" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop offset=".146" class="yrzi8mt9l"/><stop offset=".861" class="sib0ikb9x"/></linearGradient><linearGradient id="i6AMKhc" x1="24.525" x2="26.234" y1="26.03" y2="26.03" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iWhXobb" x1="24.447" x2="26.156" y1="27.335" y2="27.335" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="izVZxIb" x1="24.525" x2="26.234" y1="28.64" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iY9HAAc" x1="9.005" x2="23.381" y1="15.771" y2="15.771" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iTrUkge" x1="9.005" x2="23.381" y1="15.741" y2="15.741" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i07cd7w" x1="9.895" x2="12.854" y1="11.151" y2="11.151" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iq3Z1Tb" x1="15.143" x2="15.998" y1="12.339" y2="12.444" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="isuSrEe" x1="16.189" x2="16.189" y1="13.194" y2="12.584" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iZ8qBuc" x1="16.268" x2="16.268" y1="13.168" y2="13.028" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="iSdz8Le" x1="15.46" x2="15.913" y1="14.671" y2="13.799" gradientUnits="userSpaceOnUse"><stop class="p72mjibid"/><stop offset="1" class="i8oqbqplx"/></linearGradient><linearGradient id="iY467re" x1="19.149" x2="18.836" y1="10.52" y2="10.714" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYyIu6b" x1="14.751" x2="14.437" y1="10.52" y2="10.714" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1zBAGd" x1="13.298" x2="13.843" y1="4.865" y2="6.139" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iXiXb4d" x1="15.975" x2="16.813" y1="2.025" y2="6.975" gradientUnits="userSpaceOnUse"><stop class="nblx7ib8n"/><stop offset="1" class="h7is5ynaf"/></linearGradient><linearGradient id="iCultsb" x1="17.532" x2="17.532" y1="6.928" y2="6.6" gradientUnits="userSpaceOnUse"><stop class="hj8-3eb_v"/><stop offset="1" class="zofh5ufwh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-artist-medium-light" /></template>
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

.ansdxpmor {
  d: path("M20.307 2.79c2.008.772 2.24 2.384 2.365 3.36c-3.464-.784-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b60s00byr {
  cx: 13.736px;
  cy: 10.371px;
  rx: 0.39px;
  ry: 0.197px;
}

.b8wkgccyf {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.533-4.61-2.954c-2.718.333-4.203 3.217-3.156 6.123z");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.c2bk9yb6a {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.44");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
}

.ciz16sbbk {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.792 9.286l-.005.002a.268.268 0 0 1-.275-.46h.001l.003-.002l.01-.006a2 2 0 0 1 .148-.077c.099-.047.24-.107.41-.161c.34-.109.815-.2 1.329-.11a.268.268 0 0 1-.094.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.193");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.codnw0btf {
  d: path("M21.017 12.138a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.codu-dcmv {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.ct65j078y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 25.952h1.797");
}

.cvzy-mbfm {
  fill: var(--svg-color--b693a1, #B693A1);
  fill-rule: evenodd;
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.425-1.683-2.58-3.759-2.58s-3.758 1.155-3.758 2.58c0 .979.795 1.83 1.967 2.267c-.389.436-.404.98-.404 1.486l-.014.924c-.002.176.152.312.323.266c.381-.1.909-.315 1.264-.706c.378-.415.565-.814.622-1.433c.058.62.245 1.018.622 1.433c.356.391.883.605 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d2y5bebri {
  d: path("m25.169 16.58l.685-.093c.322 0 .735.472.735.794c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.058.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.17.102-.19");
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dlrmvbc9h {
  stop-color: var(--svg-color--c66a7d, #C66A7D);
  stop-opacity: 0;
}

.dqgu8t6sf {
  d: path("M14.064 19.957c.824-.79 1.717-.938 2.058-.89c.133 1.792-.012 2.526-.723 3.308c-.424.466-1.054.723-1.51.843c-.203.054-.387-.107-.384-.318c.004-.362.011-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.dr_fk9b-q {
  d: path("M18.374 9.99a.892.892 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.efvxagg0z {
  fill: var(--svg-color--000, #000);
  d: path("M14.517 10.882a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.ejom4oo7z {
  stop-color: var(--svg-color--d6a87f, #D6A87F);
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.ekxbkpvzc {
  d: path("M5.143 26.475c-.02-3.41 1.582-6.47 4-8.5v11.98l-3.98.02z");
}

.el-cg1bcl {
  stop-color: var(--svg-color--499da3, #499DA3);
}

.enx3m3bqe {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.048 10.494c-.266-.466-.67-.835-1.538-.835c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.f320fubee {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.298 4.522c.024.243.235 1.156.545 1.71");
}

.f6vaurbjp {
  fill-rule: evenodd;
  d: path("M23.375 12.473c.212-.435.323-.92.323-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.681 1.377a.56.56 0 0 1-.456.232q-.043 0-.085.002a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.526 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 3.218-3.219c0-.506-.12-.981-.323-1.406a.52.52 0 0 1 0-.456m-12.26-2.672h-.013l1.199 2.355c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.05l-.083.195a2.3 2.3 0 0 1-1.24 1.254q-.027.013-.052.02c-.236.123-.79.49-.81 1.44l.01.306z");
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g2eglgbrp {
  d: path("M11.504 12.673a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.ge21ot55e {
  d: path("M16.544 15.742c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gi6g7ch9s {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.797 10.84l-.684 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.376-.494-.376-.613 0");
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.glra2ybwu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.308 10.178c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.gol6j1bef {
  stop-color: var(--svg-color--ce737b, #CE737B);
}

.gr5j-eb8u {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.129 8.691c.323-.078 1.125-.04 1.66.344");
}

.grr7xmbed {
  d: path("M14.005 9.99a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
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

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hfzp6f8qe {
  d: path("M27.734 23.018a.97.97 0 0 1 .967.967V26.2h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hj8-3eb_v {
  stop-color: var(--svg-color--481b64, #481B64);
}

.hn6rf3bxr {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.338 8.691c-.322-.078-1.124-.04-1.66.344");
}

.ht0s1ib6z {
  stop-color: var(--svg-color--c36880, #C36880);
}

.hvyevjb_p {
  d: path("M7.383 29.105a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hy6u5wycq {
  stop-color: var(--svg-color--c66a7d, #C66A7D);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i57ba-bku {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M21.017 12.138a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.i8oqbqplx {
  stop-color: var(--svg-color--dca4a0, #DCA4A0);
  stop-opacity: 0;
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
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

.j0kpihu0z {
  d: path("M14.213 13.777h3.86v3.094c0 .828-.82 1.5-1.65 1.5h-.464c-1.082 0-1.746-.672-1.746-1.5z");
}

.j0piksb8i {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
}

.j1n1ygxtd {
  stop-color: var(--svg-color--e3ac86, #E3AC86);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.js7kctros {
  stop-color: var(--svg-color--97769c, #97769C);
  stop-opacity: 0;
}

.jt362mrmb {
  stop-color: var(--svg-color--f8c7a5, #F8C7A5);
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

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kfex23bvh {
  cx: 16.143px;
  cy: 17.314px;
  rx: 4.489px;
  ry: 3.08px;
}

.kj7yu4cxe {
  d: path("M18.221 19.957c-.824-.79-1.717-.938-2.058-.89c-.133 1.792.011 2.526.722 3.308c.425.466 1.055.723 1.51.843c.204.054.388-.107.385-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l7qllmb5o {
  stop-color: var(--svg-color--afa1a1, #AFA1A1);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo1e0dkdv {
  fill: var(--svg-color--000, #000);
  d: path("M17.862 10.882a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.ltzpfz2jy {
  d: path("M15.586 3.273c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.276 6.537 2.984c1.573-.175 1.743.542 1.877.888c-.435-4.056-3.369-4.676-5.95-5.246");
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.m340xmbug {
  stop-color: var(--svg-color--c77e8a, #C77E8A);
  stop-opacity: 0;
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

.mdv9qbyfi {
  stop-color: var(--svg-color--d69368, #D69368);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.n_y6p8b5d {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.076c-1.248.083-2.375.65-2.978 1.74a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.366.87-.828c0-.054-.01-.107-.02-.161v-.011c-.162-.699-.054-1.29.279-1.881a.33.33 0 0 0-.075-.388");
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

.nahyo0b6p {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.807 10.702l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.nblx7ib8n {
  stop-color: var(--svg-color--352b40, #352B40);
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.o7yoj0s6u {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.114a11.5 11.5 0 0 0-.432-1.876h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.112z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.ok43c2qsk {
  d: path("M13.015 4.726c-.973-.093-2.504.103-3.147.213c-.174.135-.48.54-.31 1.08c.17.542.574.651.754.638c3.302-.637 3.92-1.815 2.703-1.93");
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.p717knbwi {
  d: path("M21.017 12.673a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.p72mjibid {
  stop-color: var(--svg-color--dca4a0, #DCA4A0);
}

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn6srrrig {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.799 9.718c-.654 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.pr51ldkyz {
  cx: 13.736px;
  cy: 10.371px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.psj_4kbpb {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.332 10.494c.265-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.556.317c-.651-.21-1.372-.239-2.078-.45");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
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

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.rdmv99d9g {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.523 12.138a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.retif0bee {
  d: path("M11.295 5.05c.621-.553 1.517-.559 2.02-.47l.402 1.291c-.257-.04-.486.05-.678.235c-.453 1.676-2.163 1.424-2.498 2.682c-.15-1.492-.318-2.783.754-3.738");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.s_fkyyriu {
  d: path("M14.82 10.777c0-.288-.234-.48-.297-.539l-.289.28l.178.36z");
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sib0ikb9x {
  stop-color: var(--svg-color--dca48b, #DCA48B);
}

.sm66mwbyu {
  stop-color: var(--svg-color--c77e8a, #C77E8A);
}

.smq8uccvh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.58 9.718c.654 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.272c.126-.64.69-1.127 1.372-1.127");
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sv486sbdz {
  stop-color: var(--svg-color--e39886, #E39886);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
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

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.uaxfwirbj {
  d: path("M11.102 9.8h.012l-.01-.264l-.01-.306c.02-.95.574-1.317.81-1.44l.051-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.234l.081-.194a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685c-2.672 0-4.86-1.882-4.983-4.685z");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
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

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urlz13_nx {
  d: path("M18.308 10.178c.063.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.utmespb7f {
  d: path("m15.807 10.702l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
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

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wgk8d-b6o {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.921 8.828l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.058a3 3 0 0 0-.343-.135A2.3 2.3 0 0 0 18.113 9a.268.268 0 1 1-.093-.529c.513-.09.989.001 1.329.11a3.3 3.3 0 0 1 .558.238l.01.006l.002.001z");
}

.wig7w8bbb {
  d: path("m11.104 9.536l-.01-.306c.02-.95.574-1.317.81-1.44l.051-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.234l.081-.194a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.189 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685c-2.672 0-4.86-1.882-4.983-4.685z");
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.ya4ltpbbw {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.792 13.586c.403.216.885.34 1.397.34a2.96 2.96 0 0 0 1.399-.34a.205.205 0 0 1 .247.041c.058.062.08.16.021.25m-3.065-.29l3.023.263m-3.023-.264a.204.204 0 0 0-.247.044a.196.196 0 0 0-.02.247m.268-.29l-.227.263m3.291.027l-.042-.027m.042.027l-.042-.027m.042.027a1.982 1.982 0 0 1-3.333 0m3.291-.027a1.932 1.932 0 0 1-3.25 0m-.04.027l.04-.027m-.04.027h-.001l.042-.027");
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.yfkzyxbts {
  stop-color: var(--svg-color--f8c7a5, #F8C7A5);
  stop-opacity: 0;
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yrzi8mt9l {
  stop-color: var(--svg-color--fdc6a0, #FDC6A0);
}

.yx08hybsl {
  d: path("M11.383 28.263a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.ze5nteb_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.447 27.257h1.797");
}

.zetkf7bcl {
  d: path("M11.523 12.138a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.zofh5ufwh {
  stop-color: var(--svg-color--481b64, #481B64);
  stop-opacity: 0;
}

.zrzrn4ewq {
  d: path("M19.169 10.765a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
