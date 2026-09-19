<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iynhIuc)"><path fill="url(#iLrV16b)" clip-rule="evenodd" class="gdbrzxk9d"/><path fill="url(#i72Qvce)" clip-rule="evenodd" class="gdbrzxk9d"/><path fill="url(#iM1w4gu)" clip-rule="evenodd" class="gdbrzxk9d"/><path fill="url(#isZIB2d)" clip-rule="evenodd" class="gdbrzxk9d"/><path fill="url(#iKmE6Ad)" clip-rule="evenodd" class="gdbrzxk9d"/><path fill="url(#iI2qSye)" clip-rule="evenodd" class="gdbrzxk9d"/><path fill="url(#iGks7lb)" clip-rule="evenodd" class="gdbrzxk9d"/><path fill="url(#i1fgrad)" clip-rule="evenodd" class="gdbrzxk9d"/><path fill="url(#iR2nogd)" clip-rule="evenodd" class="gdbrzxk9d"/></g><path fill="url(#iQiRM2d)" class="zbs2xvbkg"/><path fill="url(#inA3Tpe)" class="zbs2xvbkg"/><path fill="url(#iP1im0c)" class="zbs2xvbkg"/><path fill="url(#i04jDnj)" class="zbs2xvbkg"/><g filter="url(#iVG4gjb)"><path clip-rule="evenodd" class="lskkwsben"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#ipTzw1d)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#iz3GDdc)"><path fill="url(#iZYJJTd)" class="tcwskybjq"/><path fill="url(#in5HY3d)" class="tcwskybjq"/></g><g filter="url(#i8a0o5b)"><path fill="url(#iCgYo9c)" class="eobvvhscd"/><path fill="url(#iH5QJMe)" class="eobvvhscd"/><path fill="url(#i8efCLe)" class="eobvvhscd"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#iX1h26G)"><path fill="url(#iV8l4jb)" class="d8tr4np7e"/><path fill="url(#ignAelv)" class="d8tr4np7e"/></g><path fill="url(#iqkeVzb)" class="l29svp3cg"/><path fill="url(#ib6zMLd)" class="l29svp3cg"/><g filter="url(#iEeVRGd)"><path fill="url(#izcCUib)" class="vx8yiwdcw"/></g><g filter="url(#iJ02tJb)"><path class="oh_l9db2x"/></g><g filter="url(#ita94te)"><path class="teu3yl5ky"/></g><g filter="url(#iMdl2ab)"><path class="waw2uhbiy"/></g><g filter="url(#ilEp2Gb)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#iULTQec)"><path fill="url(#iyQIgyc)" class="k1aaqobwu"/></g><g filter="url(#i5f0E8c)"><path fill="url(#iO8TsTc)" class="i20220bfm"/></g><path fill="url(#i4gM3yb)" class="i20220bfm"/><g filter="url(#iqsN4Rl)"><path fill="url(#iv4hPGe)" class="hfzp6f8qe"/><path fill="url(#iWUA3Je)" class="hfzp6f8qe"/></g><path fill="url(#iTfdAvb)" class="kb0m86bqf"/><path fill="url(#iTkYgvd)" class="kb0m86bqf"/><path fill="url(#iqMfzad)" class="kb0m86bqf"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iMs2ZOe)" class="s80w1fafw"/><g filter="url(#ic1s8dc)"><path fill="url(#i1FSYJc)" class="iouks0fsc"/><path fill="url(#iZLdWle)" class="iouks0fsc"/><path fill="url(#iZaoaBd)" class="iouks0fsc"/><path fill="url(#iP3rqkj)" class="iouks0fsc"/></g><path fill="url(#ieEgdTd)" class="yf6m5abnn"/><g filter="url(#ie7leDc)"><path fill="url(#iSbgAfc)" class="uhuv92bap"/><path fill="url(#ibiMAze)" class="uhuv92bap"/><path fill="url(#iR3m9Xd)" class="uhuv92bap"/><path fill="url(#ixbEKEd)" class="uhuv92bap"/></g><g filter="url(#iVRt0Ob)"><path fill="url(#iiRkkfe)" class="m2-b5ia7e"/><path fill="url(#i5v4V6M)" class="m2-b5ia7e"/><path fill="url(#iR520Bc)" class="m2-b5ia7e"/><path fill="url(#ibKTRtc)" class="m2-b5ia7e"/><path fill="url(#iIdqRcb)" class="m2-b5ia7e"/></g><g filter="url(#ihL1A8b)"><path stroke="url(#iUJybld)" class="m0d3s6x_z"/></g><g filter="url(#iCEcBsc)"><path stroke="url(#iL4BC4d)" class="w4boyzb-m"/></g><g filter="url(#iOiSQXR)"><path stroke="url(#ifAlXyK)" class="dx5j-abwb"/></g><g filter="url(#i8HmhzQ)"><path fill="url(#i494gne)" class="ok_z2gthf"/></g><g filter="url(#iWga8Kb)"><path fill="url(#igLLLzc)" class="z10nf5b0x"/></g><g filter="url(#ixH2C5c)"><path class="d-hfnb_qp"/><path fill="url(#iYWzQne)" class="trfzvobwc"/></g><g filter="url(#i7UWIgc)"><path class="l9ip31bgg"/><path fill="url(#iEiFyXd)" class="oj_bsrbnw"/></g><g filter="url(#iJHhfpM)"><path fill="url(#iS7jJ8c)" class="j0kpihu0z"/><path fill="url(#isDdvRJ)" class="j0kpihu0z"/></g><g filter="url(#i1a5fJe)"><path fill="url(#ise714d)" class="mj4747bqu"/><path fill="url(#i88VSqc)" class="mj4747bqu"/><path fill="url(#ihmDsnc)" class="mj4747bqu"/><path fill="url(#iyml84d)" class="mj4747bqu"/><path fill="url(#ifRu3ZS)" class="mj4747bqu"/><path fill="url(#iio3z8d)" class="mj4747bqu"/><path fill="url(#iU97Icb)" class="mj4747bqu"/></g><path fill="url(#iEVLhId)" class="mj4747bqu"/><path fill="url(#i6RhrLc)" class="mj4747bqu"/><g filter="url(#iDtq64D)"><path class="jlkl4kzzm"/></g><g filter="url(#iRIUZUb)"><path fill="url(#i9hm0hc)" class="z3h3hrbhy"/><path fill="url(#iTNbOye)" class="z3h3hrbhy"/><path fill="url(#ib64cFb)" class="z3h3hrbhy"/><path fill="url(#inYPCxH)" class="z3h3hrbhy"/></g><path fill="url(#ie4U0Mb)" class="z3h3hrbhy"/><path fill="url(#iRv3yBe)" class="z3h3hrbhy"/><path stroke="url(#iiV55Sc)" class="wsj1_vexu"/><g filter="url(#iCvtBEd)"><path class="yjq38q14u"/></g><g filter="url(#irEVqWc)"><path class="wbveepxnx"/></g><g filter="url(#iMyL0Rb)"><path class="nk0_xyhhj"/></g><g filter="url(#iyGSbkd)"><path clip-rule="evenodd" class="jtowb3d-i"/></g><path class="otdn8gzxh"/><path fill="url(#ipbIlSd)" class="k42zuzqpc"/><path class="aiwhyfksl"/><g filter="url(#ilPNNdp)"><path class="c6cgjcc2g"/><path fill="url(#iZdGcTc)" class="dmambbcfy"/></g><g filter="url(#iZC95ve)"><path fill="url(#ifRVuse)" class="u74t3gbrq"/></g><path class="k99hhddjb"/><path fill="url(#iC5e86d)" class="zq_mb-bmy"/><path class="j-w-e6gsl"/><g filter="url(#ihWP5ve)"><path fill="url(#iHkBc9b)" class="g9v1jcccw"/></g><g filter="url(#iXx9x0G)"><ellipse transform="rotate(-27.914 13.713 10.269)" class="tt-im31ul"/><ellipse fill="url(#iGot3Rd)" transform="rotate(-27.914 13.713 10.269)" class="seisrebkj"/></g><g filter="url(#ikh9Mdm)"><path class="fm7h-tbxq"/></g><g filter="url(#iXTsbic)"><path class="a-wnbtb0c"/></g><g filter="url(#irC3MHc)"><path fill="url(#ir1ftWd)" class="pjy8qub_k"/><path fill="url(#i6B9yod)" class="pjy8qub_k"/><path fill="url(#iDeicBe)" class="pjy8qub_k"/></g><g filter="url(#itgjbPe)"><path stroke="url(#ifRPnZd)" class="z304cabpx"/></g><path class="mk9cbeb_z"/><path fill="url(#iLkxb5d)" class="tpv18l7lf"/><g filter="url(#ian8Fic)"><path fill="url(#iwfm65c)" class="s3g09k5mk"/></g><g filter="url(#i0WGbYb)"><path fill="url(#in6AZkm)" class="a3lgdnbbr"/></g><defs><radialGradient id="i72Qvce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.595 12.995)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iM1w4gu" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.57099 -5.8032 0 16.166 13.088)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="isZIB2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.256 11.282)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iKmE6Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.847 8.846)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iI2qSye" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.291 12.45)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iGks7lb" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.685 7.373)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="i1fgrad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.676 10.11)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iR2nogd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.462 6.293)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iQiRM2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.974)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="iP1im0c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.974)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="in5HY3d" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.421 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iyQIgyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.784)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="iv4hPGe" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 7.151 20.213)scale(1.88642 1.51516)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset=".828" class="gtmq6ja1j"/></radialGradient><radialGradient id="iWUA3Je" cx="0" cy="0" r="1" gradientTransform="matrix(.42187 -.41797 .44508 .44923 27.44 24.61)" gradientUnits="userSpaceOnUse"><stop class="xcc0mcchc"/><stop offset="1" class="lyxdnwxxe"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibiMAze" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.594)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="i5v4V6M" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 28.323 24.568)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iR520Bc" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 24.191 25.945)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="ibKTRtc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 24.005 27.271)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iIdqRcb" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.91 28.538)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="igLLLzc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.206 11.4)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iYWzQne" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.663 -52.386)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iEiFyXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.5 10.962)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iS7jJ8c" cx="0" cy="0" r="1" gradientTransform="rotate(138.439 5.875 11.759)scale(2.57895 1.90476)" gradientUnits="userSpaceOnUse"><stop class="v5zv_59in"/><stop offset="1" class="f23vv_bdb"/></radialGradient><radialGradient id="isDdvRJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .75 -2.28629 0 16.143 16.598)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="ywiasud5x"/><stop offset="1" class="lc5uqnbos"/></radialGradient><radialGradient id="ise714d" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.37 7.3)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="i88VSqc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 18.067 11.122)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="ihmDsnc" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.988 17.208)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iyml84d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.905 9.94)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="mjocdnbmi"/><stop offset="1" class="wqbrdk8if"/></radialGradient><radialGradient id="ifRu3ZS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.794 12.08)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iio3z8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.468 10.006)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iU97Icb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.248 10.093)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iEVLhId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.262 11.493)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="i6RhrLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.7403 -7.25217 0 16.167 9.191)" gradientUnits="userSpaceOnUse"><stop offset=".977" class="hseetzb-f"/><stop offset="1" class="areue81yd"/></radialGradient><radialGradient id="iTNbOye" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.951 12.22)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iRv3yBe" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.326 8.568)scale(1.57489 2.10945)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="ipbIlSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.349 10.365)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iZdGcTc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.619 .787)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iC5e86d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.985 10.365)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iGot3Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.698 10.584)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ir1ftWd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.958 2.836)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="i6B9yod" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.794 9.093)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iDeicBe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.316 9.721)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="iLkxb5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iwfm65c" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="in6AZkm" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.377 3.233)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="iynhIuc" width="15.268" height="15.268" x="8.657" y="2.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="iVG4gjb" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".75"/></filter><filter id="ipTzw1d" width="8.987" height="5.737" x="11.649" y="14.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".2"/></filter><filter id="iz3GDdc" width="2.812" height="4.17" x="13.355" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="i8a0o5b" width="2.762" height="4.17" x="16.118" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="iX1h26G" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="iEeVRGd" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2383" result="effect2_innerShadow_4002_2383"/></filter><filter id="iJ02tJb" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".075"/></filter><filter id="ita94te" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".075"/></filter><filter id="iMdl2ab" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".075"/></filter><filter id="ilEp2Gb" width="2.58" height="2.68" x="7.143" y="22.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2383" result="effect2_innerShadow_4002_2383"/></filter><filter id="iULTQec" width="2.58" height="2.68" x="10.143" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2383" result="effect2_innerShadow_4002_2383"/></filter><filter id="i5f0E8c" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2383" result="effect2_innerShadow_4002_2383"/></filter><filter id="iqsN4Rl" width="2.584" height="3.682" x="26.767" y="22.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="ic1s8dc" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="ie7leDc" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="iVRt0Ob" width="4.996" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.513726 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="ihL1A8b" width="2.047" height=".25" x="24.4" y="25.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".05"/></filter><filter id="iCEcBsc" width="2.047" height=".25" x="24.322" y="27.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".05"/></filter><filter id="iOiSQXR" width="2.047" height=".25" x="24.4" y="28.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".05"/></filter><filter id="i8HmhzQ" width="3.318" height="3.218" x="9.872" y="9.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="iWga8Kb" width="3.218" height="3.468" x="19.385" y="9.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="ixH2C5c" width="3.148" height="3.148" x="19.42" y="9.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".25"/></filter><filter id="i7UWIgc" width="2.648" height="2.648" x="10.176" y="9.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".125"/></filter><filter id="iJHhfpM" width="3.859" height="4.694" x="14.213" y="13.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.388235 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="i1a5fJe" width="10.191" height="10.977" x="11.071" y="6.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="iDtq64D" width="2.877" height="3.682" x="14.566" y="9.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".25"/></filter><filter id="iRIUZUb" width="2.377" height="3.182" x="14.978" y="10.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".125"/></filter><filter id="iCvtBEd" width="3.001" height="1.285" x="17.109" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="irEVqWc" width="3.001" height="1.285" x="12.223" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="iMyL0Rb" width="2.453" height="1.091" x="12.358" y="8.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="iyGSbkd" width="2.453" height="1.091" x="17.776" y="8.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2383"/></filter><filter id="ilPNNdp" width=".786" height=".696" x="17.614" y="9.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".05"/></filter><filter id="iZC95ve" width=".891" height=".913" x="18.454" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".1"/></filter><filter id="ihWP5ve" width=".986" height="1.04" x="14.012" y="9.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".1"/></filter><filter id="iXx9x0G" width=".912" height=".704" x="13.257" y="9.917" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".05"/></filter><filter id="ikh9Mdm" width="2.261" height=".978" x="17.806" y="8.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".1"/></filter><filter id="iXTsbic" width="2.261" height=".978" x="12.354" y="8.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".1"/></filter><filter id="irC3MHc" width="8.914" height="5.78" x="12.849" y="2.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".125"/></filter><filter id="itgjbPe" width="1.145" height="2.31" x="12.975" y="4.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".125"/></filter><filter id="ian8Fic" width="9.346" height="5.558" x="14.326" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".5"/></filter><filter id="i0WGbYb" width="7.084" height="4.956" x="8.009" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2383" stdDeviation=".75"/></filter><linearGradient id="iLrV16b" x1="20.86" x2="13.618" y1="4.009" y2="17.452" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="iH5QJMe" x1="16.549" x2="17.45" y1="19.058" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iV8l4jb" x1="16.343" x2="16.343" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iMs2ZOe" x1="26.353" x2="26.353" y1="20.724" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="iP3rqkj" x1="26.502" x2="26.502" y1="20.724" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="iiRkkfe" x1="28.033" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="xwbtobibq"/></linearGradient><linearGradient id="iUJybld" x1="26.205" x2="24.369" y1="25.952" y2="25.952" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iL4BC4d" x1="26.127" x2="24.291" y1="27.257" y2="27.257" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="ifAlXyK" x1="26.205" x2="24.369" y1="28.562" y2="28.562" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="i494gne" x1="9.872" x2="12.831" y1="11.049" y2="11.049" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i9hm0hc" x1="16.167" x2="16.167" y1="13" y2="10.318" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ib64cFb" x1="15.12" x2="15.975" y1="12.238" y2="12.342" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="inYPCxH" x1="16.167" x2="16.167" y1="13.092" y2="12.482" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="ie4U0Mb" x1="16.245" x2="16.245" y1="13.066" y2="12.926" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iiV55Sc" x1="15.438" x2="15.89" y1="14.569" y2="13.697" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ifRVuse" x1="19.126" x2="18.813" y1="10.418" y2="10.611" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHkBc9b" x1="14.728" x2="14.415" y1="10.418" y2="10.611" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifRPnZd" x1="13.275" x2="13.82" y1="4.763" y2="6.037" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-artist" /></template>
<style>
.a-wnbtb0c {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.315 8.589c-.322-.079-1.124-.04-1.66.344");
}

.a3lgdnbbr {
  d: path("M13.015 4.726c-.973-.093-2.504.103-3.147.212c-.174.136-.48.541-.31 1.082c.17.54.574.65.754.637c3.302-.637 3.92-1.815 2.703-1.931");
}

.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.acw_xab5u {
  stop-color: var(--svg-color--ed577d, #ED577D);
  stop-opacity: 0;
}

.af9b0l-ho {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.aiwhyfksl {
  fill: var(--svg-color--000, #000);
  d: path("M17.84 10.78a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746H17.9a.46.46 0 0 1-.06-.235");
}

.areue81yd {
  stop-color: var(--svg-color--e67150, #E67150);
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.c6cgjcc2g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.285 10.077c.063.084-.07.188-.22.3c-.152.114-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
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

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.d-hfnb_qp {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.994 12.036a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.d8tr4np7e {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.608.426c-.121.005-.15.005-.27 0a.69.69 0 0 1-.608-.426a4 4 0 0 1-.222-.714c-.041-.19.05-.382.236-.441");
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dmambbcfy {
  d: path("M18.285 10.077c.063.084-.07.188-.22.3c-.152.114-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dx5j-abwb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.525 28.562h1.797");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.ejom4oo7z {
  stop-color: var(--svg-color--d6a87f, #D6A87F);
}

.ekxbkpvzc {
  d: path("M5.143 26.475c-.02-3.41 1.582-6.47 4-8.5v11.98l-3.98.02z");
}

.el-cg1bcl {
  stop-color: var(--svg-color--499da3, #499DA3);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eobvvhscd {
  d: path("M18.221 19.957c-.824-.79-1.717-.938-2.058-.89c-.133 1.792.011 2.527.723 3.308c.424.466 1.054.723 1.51.843c.203.054.387-.107.384-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f23vv_bdb {
  stop-color: var(--svg-color--ed8029, #ED8029);
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fm7h-tbxq {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.106 8.589c.323-.079 1.125-.04 1.661.344");
}

.ft5dv1b6b {
  fill: none;
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g9v1jcccw {
  d: path("M14.798 10.675c0-.289-.235-.48-.298-.539l-.288.279l.177.361z");
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gdbrzxk9d {
  fill-rule: evenodd;
  d: path("M23.352 12.371c.212-.435.324-.92.324-1.427c0-.467-.096-.905-.269-1.305h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.681 1.377a.56.56 0 0 1-.456.233h-.085a3.3 3.3 0 0 0-3.214 3.3v.01a3.24 3.24 0 0 1-.526 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 3.219-3.219c0-.506-.122-.981-.324-1.406a.51.51 0 0 1 0-.456M11.092 9.7h-.013l1.199 2.356c.123 2.802 1.217 0 3.888 0c2.672 0 3.837 3.119 3.96.316l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.05l-.083.195a2.3 2.3 0 0 1-1.19 1.234l-.05.02l-.052.021c-.236.122-.79.49-.81 1.439l.01.306z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gtmq6ja1j {
  stop-color: var(--svg-color--ffd235, #FFD235);
}

.gzbsswvik {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
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

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hseetzb-f {
  stop-color: var(--svg-color--e67150, #E67150);
  stop-opacity: 0;
}

.i20220bfm {
  d: path("M7.383 29.104a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.id09adcid {
  stop-color: var(--svg-color--ffe047, #FFE047);
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.iouks0fsc {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.115c-.099-.66-.234-1.26-.432-1.875h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.111z");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
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

.j-w-e6gsl {
  fill: var(--svg-color--000, #000);
  d: path("M14.494 10.78a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.j0kpihu0z {
  d: path("M14.213 13.777h3.86v3.094c0 .828-.82 1.5-1.65 1.5h-.464c-1.082 0-1.746-.672-1.746-1.5z");
}

.j0piksb8i {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jlkl4kzzm {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.774 10.739l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.494-.377-.613 0");
}

.js7kctros {
  stop-color: var(--svg-color--97769c, #97769C);
  stop-opacity: 0;
}

.jtowb3d-i {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.898 8.726l-.138.23za.268.268 0 0 1-.275.46l-.005-.002l-.022-.012q-.03-.017-.091-.047a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.09a.268.268 0 1 1-.093-.529c.513-.09.989.001 1.329.11a3.3 3.3 0 0 1 .558.238l.01.005l.002.002z");
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

.k1aaqobwu {
  d: path("M11.383 28.264a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.k42zuzqpc {
  d: path("M18.35 9.888a.892.892 0 0 1 .86 1.127h-1.723a.896.896 0 0 1 .864-1.128");
}

.k99hhddjb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.776 9.616c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.kb0m86bqf {
  d: path("M23.143 29.975v-12c2.44 2.023 4 5.078 4 8.494v3.505z");
}

.kfex23bvh {
  cx: 16.143px;
  cy: 17.314px;
  rx: 4.489px;
  ry: 3.08px;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l29svp3cg {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.532-4.61-2.954c-2.718.334-4.203 3.217-3.156 6.123z");
}

.l7qllmb5o {
  stop-color: var(--svg-color--afa1a1, #AFA1A1);
}

.l9ip31bgg {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.5 12.036a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.lc5uqnbos {
  stop-color: var(--svg-color--eb7643, #EB7643);
  stop-opacity: 0;
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lskkwsben {
  fill: var(--svg-color--b693a1, #B693A1);
  fill-rule: evenodd;
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.424-1.683-2.579-3.758-2.579s-3.76 1.155-3.76 2.579c0 .979.796 1.83 1.968 2.267c-.389.437-.404.981-.404 1.486c-.003.217-.01.62-.013.924c-.003.177.152.312.322.267c.382-.101.909-.316 1.264-.707c.378-.414.565-.813.623-1.433c.057.62.244 1.019.621 1.433c.356.391.883.606 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.lyxdnwxxe {
  stop-color: var(--svg-color--efa20d, #EFA20D);
  stop-opacity: 0;
}

.m0d3s6x_z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.525 25.952h1.797");
}

.m2-b5ia7e {
  d: path("M24.005 25.3c0-.401.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
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

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mj4747bqu {
  d: path("M11.08 9.699h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.439l.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.119 3.073c-.123 2.803-2.311 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.mjocdnbmi {
  stop-color: var(--svg-color--f3983e, #F3983E);
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

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.nk0_xyhhj {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.769 9.184l-.004.002a.268.268 0 0 1-.276-.46h.001l.003-.003l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.816-.2 1.329-.109a.268.268 0 1 1-.094.529a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.433.182z");
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.oj_bsrbnw {
  d: path("M11.5 12.036a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ok_z2gthf {
  d: path("M11.48 12.57a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.otdn8gzxh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.558 9.616c.653 0 1.204.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.231a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.372-1.127");
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pjy8qub_k {
  d: path("M15.563 3.17c-1.132-.25-2.346.956-2.464 1.375c1.542 3.62 3.91 3.276 6.537 2.984c1.573-.175 1.744.542 1.878.888c-.436-4.056-3.37-4.676-5.95-5.246");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q0u2bl4sa {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
  stop-opacity: 0;
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
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

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.s3g09k5mk {
  d: path("M20.307 2.79c2.008.772 2.24 2.384 2.365 3.36c-3.464-.783-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.seisrebkj {
  cx: 13.713px;
  cy: 10.269px;
  rx: 0.389px;
  ry: 0.197px;
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.ta7eky02w {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
  stop-opacity: 0;
}

.tcwskybjq {
  d: path("M14.064 19.957c.824-.79 1.717-.938 2.058-.89c.133 1.792-.011 2.527-.722 3.308c-.425.466-1.055.723-1.51.843c-.204.054-.388-.107-.385-.318c.004-.362.012-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.teu3yl5ky {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M11.32 28.314a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tm2bmw9uh {
  stop-color: var(--svg-color--4cc6ef, #4CC6EF);
}

.tpv18l7lf {
  d: path("M9.007 5.835c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.738.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H10.264c-.685 0-1.257-.429-1.257-1.139");
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.trfzvobwc {
  d: path("M20.994 12.036a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.tt-im31ul {
  cx: 13.713px;
  cy: 10.269px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u74t3gbrq {
  d: path("M19.145 10.662a.84.84 0 0 0-.23-.462l-.26.285l.117.228z");
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.uhuv92bap {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.076c-1.248.083-2.375.65-2.978 1.74a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.366.87-.828c0-.054-.01-.107-.02-.161v-.01c-.162-.7-.054-1.291.279-1.882a.33.33 0 0 0-.075-.387");
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.v5zv_59in {
  stop-color: var(--svg-color--ffac2a, #FFAC2A);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
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

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vx8yiwdcw {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.976c-2.718.336-4.203 3.242-3.156 6.171z");
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w4boyzb-m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.447 27.257h1.797");
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wbveepxnx {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.025 10.393c-.266-.467-.67-.836-1.538-.836c-.38 0-.746.105-1.072.369c-.27.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.wqbrdk8if {
  stop-color: var(--svg-color--e98848, #E98848);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wsj1_vexu {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.769 13.484a.205.205 0 0 0-.248.044a.196.196 0 0 0-.02.247a1.982 1.982 0 0 0 3.332 0a.2.2 0 0 0-.02-.25a.205.205 0 0 0-.248-.04c-.404.215-.88.338-1.398.338c-.513 0-.995-.123-1.398-.339Z");
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xcc0mcchc {
  stop-color: var(--svg-color--efa20d, #EFA20D);
}

.xwbtobibq {
  stop-color: var(--svg-color--ffae37, #FFAE37);
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yf6m5abnn {
  d: path("m25.169 16.58l.685-.093c.322 0 .735.472.735.794c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.059.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.17.102-.19");
}

.yjq38q14u {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.309 10.393c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.556.317c-.651-.21-1.372-.239-2.078-.45");
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.ywiasud5x {
  stop-color: var(--svg-color--eb7643, #EB7643);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z10nf5b0x {
  d: path("M20.994 12.57a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.219");
}

.z304cabpx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.275 4.42c.024.243.235 1.156.545 1.71");
}

.z3h3hrbhy {
  d: path("m15.784 10.6l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.zbs2xvbkg {
  d: path("M9.143 17.989a10.96 10.96 0 0 1 7-2.514c2.658 0 5.097.943 7 2.514v11.985h-14z");
}

.zq_mb-bmy {
  d: path("M13.983 9.888a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
