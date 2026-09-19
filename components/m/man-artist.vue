<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQiRM2d)" class="zbs2xvbkg"/><path fill="url(#inA3Tpe)" class="zbs2xvbkg"/><path fill="url(#iP1im0c)" class="zbs2xvbkg"/><path fill="url(#i04jDnj)" class="zbs2xvbkg"/><g filter="url(#iE7G4ae)"><path class="wwkh3zbvl"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#iUl1rfU)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#idvYpye)"><path fill="url(#iZYJJTd)" class="fawsh83wa"/><path fill="url(#in5HY3d)" class="fawsh83wa"/></g><g filter="url(#iYSrFoc)"><path fill="url(#iCgYo9c)" class="qs7c013mg"/><path fill="url(#izKufic)" class="qs7c013mg"/><path fill="url(#i8efCLe)" class="qs7c013mg"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#iOeNmKe)"><path fill="url(#iIo36rp)" class="pepvmtr_g"/><path fill="url(#ignAelv)" class="pepvmtr_g"/></g><path fill="url(#iqkeVzb)" class="l29svp3cg"/><path fill="url(#ib6zMLd)" class="l29svp3cg"/><g filter="url(#ivhJfxd)"><path fill="url(#izcCUib)" class="vx8yiwdcw"/></g><g filter="url(#ibkaI1o)"><path class="oh_l9db2x"/></g><g filter="url(#igBTnjd)"><path class="teu3yl5ky"/></g><g filter="url(#iRXJLqf)"><path class="waw2uhbiy"/></g><g filter="url(#iUMtSXc)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#iWwIy7c)"><path fill="url(#iyQIgyc)" class="k1aaqobwu"/></g><g filter="url(#i4eEAdj)"><path fill="url(#iO8TsTc)" class="i20220bfm"/></g><path fill="url(#i4gM3yb)" class="i20220bfm"/><path fill="url(#izj8wLc)" class="fomm8__lp"/><path fill="url(#iSAEEZc)" class="fomm8__lp"/><g filter="url(#ijhZYsb)"><path fill="url(#iv4hPGe)" class="hfzp6f8qe"/><path fill="url(#iWUA3Je)" class="hfzp6f8qe"/></g><path fill="url(#iTfdAvb)" class="kb0m86bqf"/><path fill="url(#iTkYgvd)" class="kb0m86bqf"/><path fill="url(#iqMfzad)" class="kb0m86bqf"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iMs2ZOe)" class="s80w1fafw"/><g filter="url(#iH9k0Od)"><path fill="url(#i1FSYJc)" class="iouks0fsc"/><path fill="url(#iZLdWle)" class="iouks0fsc"/><path fill="url(#iZaoaBd)" class="iouks0fsc"/><path fill="url(#iP3rqkj)" class="iouks0fsc"/></g><path fill="url(#ieEgdTd)" class="yf6m5abnn"/><g filter="url(#iCJnTte)"><path fill="url(#iSbgAfc)" class="uhuv92bap"/><path fill="url(#ibiMAze)" class="uhuv92bap"/><path fill="url(#iR3m9Xd)" class="uhuv92bap"/><path fill="url(#ixbEKEd)" class="uhuv92bap"/></g><g filter="url(#iAWzIhb)"><path fill="url(#iiRkkfe)" class="m2-b5ia7e"/><path fill="url(#i5v4V6M)" class="m2-b5ia7e"/><path fill="url(#iR520Bc)" class="m2-b5ia7e"/><path fill="url(#ibKTRtc)" class="m2-b5ia7e"/><path fill="url(#iIdqRcb)" class="m2-b5ia7e"/></g><g filter="url(#iUHfxOd)"><path stroke="url(#iUJybld)" class="m0d3s6x_z"/></g><g filter="url(#i7TBWyc)"><path stroke="url(#iL4BC4d)" class="w4boyzb-m"/></g><g filter="url(#i5fakve)"><path stroke="url(#ifAlXyK)" class="dx5j-abwb"/></g><circle fill="url(#iLYw3Gd)" class="yraxlebfz"/><g filter="url(#i0LkKTm)"><circle fill="url(#iTQMSDb)" class="o-7j6m7ef"/></g><g filter="url(#i4aKd3b)"><circle fill="url(#iKWrRBb)" class="wnui32bcq"/><circle fill="url(#iBM7t3d)" class="wnui32bcq"/></g><g filter="url(#iGNz4ab)"><circle class="joygt0b9v"/><circle fill="url(#iWW3FHr)" class="cyvqbbbfl"/><circle fill="url(#izjG13E)" class="cyvqbbbfl"/></g><path fill="url(#i0pFysd)" class="y25vf2b0q"/><path fill="url(#ibvBOFw)" class="y25vf2b0q"/><path fill="url(#i0u0NRa)" class="y25vf2b0q"/><path fill="url(#iGPrLid)" class="y25vf2b0q"/><path fill="url(#iP5C3cd)" class="y25vf2b0q"/><path fill="url(#iFlJfve)" class="y25vf2b0q"/><g filter="url(#itYLCte)"><path class="nq-qoxvcp"/></g><g filter="url(#iCY3CKd)"><path class="jy59mxbdf"/><path fill="url(#iaGgRBc)" class="hf8g6bcbv"/><path fill="url(#iWxXUIc)" class="hf8g6bcbv"/><path fill="url(#iEVJPYJ)" class="hf8g6bcbv"/></g><path fill="url(#ik9xdyd)" class="hf8g6bcbv"/><g filter="url(#ilydUyc)"><path stroke="url(#i83wdwb)" class="eyljfybem"/></g><path class="hu6doibrz"/><path class="n2c-64r5n"/><path fill="url(#ixq3HOe)" class="wnqlpqbzw"/><path class="af2-qb9bh"/><g filter="url(#i0a0ITc)"><path class="dzl2vxb3t"/><path fill="url(#ilM6yOc)" class="rq_si6b4y"/></g><g filter="url(#i12hndB)"><path fill="url(#i9uDugE)" class="c-6oblcgx"/></g><path class="yqjjaj6xj"/><path fill="url(#i4isxjh)" class="i_v7yqz-n"/><path class="vs-10bcrv"/><g filter="url(#iji5hKe)"><path fill="url(#iL1Cakc)" class="wxgmfgbgc"/></g><g filter="url(#ivOZ0vp)"><ellipse transform="rotate(-27.914 13.723 9.878)" class="we9c_ibih"/><ellipse fill="url(#iKP1VBF)" transform="rotate(-27.914 13.723 9.878)" class="imbe-6h8j"/></g><g filter="url(#ipv5Bdz)"><path fill="url(#iWqLTre)" clip-rule="evenodd" class="i-h2msbga"/></g><g filter="url(#iECVqzb)"><path class="d4-80i5ez"/></g><g filter="url(#i42SN1d)"><path fill="url(#iJCnLGc)" clip-rule="evenodd" class="vojt97b2p"/></g><g filter="url(#iKSGBGc)"><path class="z1tlh1brf"/></g><g filter="url(#ihOdBcc)"><path fill="url(#ix8M9kb)" class="w8pu7oqgu"/><path fill="url(#iAc782b)" class="w8pu7oqgu"/></g><path fill="url(#ijwtbAe)" class="ir0pz063d"/><path fill="url(#iNZgWOc)" class="ir0pz063d"/><path class="mk9cbeb_z"/><path fill="url(#iLkxb5d)" class="tpv18l7lf"/><g filter="url(#irmi2ZB)"><path fill="url(#iwfm65c)" class="s3g09k5mk"/></g><g filter="url(#iqUg17d)"><path fill="url(#in6AZkm)" class="a3lgdnbbr"/></g><defs><radialGradient id="iQiRM2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.974)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="iP1im0c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.974)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="in5HY3d" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.421 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iyQIgyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.784)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="izj8wLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42193 -3.27267 0 16.143 17.096)" gradientUnits="userSpaceOnUse"><stop offset=".395" class="a_iq15w2m"/><stop offset="1" class="vl4d3lbhw"/></radialGradient><radialGradient id="iSAEEZc" cx="0" cy="0" r="1" gradientTransform="matrix(3.94043 .98437 -.58167 2.32843 14.233 16.566)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="fp7gzobqh"/><stop offset=".952" class="r3gzp2rve"/></radialGradient><radialGradient id="iv4hPGe" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 7.151 20.213)scale(1.88642 1.51516)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset=".828" class="gtmq6ja1j"/></radialGradient><radialGradient id="iWUA3Je" cx="0" cy="0" r="1" gradientTransform="matrix(.42187 -.41797 .44508 .44923 27.44 24.61)" gradientUnits="userSpaceOnUse"><stop class="xcc0mcchc"/><stop offset="1" class="lyxdnwxxe"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibiMAze" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.594)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="i5v4V6M" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 28.323 24.568)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iR520Bc" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 24.191 25.945)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="ibKTRtc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 24.005 27.271)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iIdqRcb" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 23.91 28.538)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iLYw3Gd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.757 10.657)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iBM7t3d" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.323 10.392)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iWW3FHr" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.91 11.479)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="izjG13E" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.951 10.657)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="i0u0NRa" cx="0" cy="0" r="1" gradientTransform="scale(9.31504 8.15808)rotate(90 .34 1.45)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="wietpnb7v"/><stop offset="1" class="kcmf541da"/></radialGradient><radialGradient id="iP5C3cd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.529 9.384)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iFlJfve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.967 9.35)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="i83wdwb" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 16.096 14.673)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ixq3HOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 18.362 10.308)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ilM6yOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18.133 10.06)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4isxjh" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 13.994 10.308)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iKP1VBF" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.872 -1.65)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWqLTre" cx="0" cy="0" r="1" gradientTransform="matrix(.19698 -.81253 1.78256 .43214 18.634 8.455)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iJCnLGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.19698 -.81253 1.78256 -.43214 13.727 8.457)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="ix8M9kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.59375 -.72546 0 21.3 6.957)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="hhhm45baq"/><stop offset="1" class="ieyl9py5s"/></radialGradient><radialGradient id="iAc782b" cx="0" cy="0" r="1" gradientTransform="matrix(.96094 1.30102 -.82388 .60853 20.698 8.086)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="t1tb7n8-g"/><stop offset="1" class="u1fjg6bbb"/></radialGradient><radialGradient id="ijwtbAe" cx="0" cy="0" r="1" gradientTransform="matrix(.125 2.15625 -.9303 .05393 11.362 8.894)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="q6imb_bng"/><stop offset="1" class="b5vkxmrbt"/></radialGradient><radialGradient id="iNZgWOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65625 1.3125 0 11.753 7.644)" gradientUnits="userSpaceOnUse"><stop class="e1lnunasd"/><stop offset="1" class="iu6_60l-p"/></radialGradient><radialGradient id="iLkxb5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iwfm65c" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="in6AZkm" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.377 3.233)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="iE7G4ae" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".75"/></filter><filter id="iUl1rfU" width="8.987" height="5.737" x="11.649" y="14.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".2"/></filter><filter id="idvYpye" width="2.812" height="4.17" x="13.354" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iYSrFoc" width="2.762" height="4.17" x="16.118" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iOeNmKe" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="ivhJfxd" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2384" result="effect2_innerShadow_4002_2384"/></filter><filter id="ibkaI1o" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".075"/></filter><filter id="igBTnjd" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".075"/></filter><filter id="iRXJLqf" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".075"/></filter><filter id="iUMtSXc" width="2.58" height="2.68" x="7.143" y="22.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2384" result="effect2_innerShadow_4002_2384"/></filter><filter id="iWwIy7c" width="2.58" height="2.68" x="10.143" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2384" result="effect2_innerShadow_4002_2384"/></filter><filter id="i4eEAdj" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2384" result="effect2_innerShadow_4002_2384"/></filter><filter id="ijhZYsb" width="2.584" height="3.682" x="26.767" y="22.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iH9k0Od" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iCJnTte" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iAWzIhb" width="4.996" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.513726 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iUHfxOd" width="2.047" height=".25" x="24.4" y="25.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".05"/></filter><filter id="i7TBWyc" width="2.047" height=".25" x="24.322" y="27.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".05"/></filter><filter id="i5fakve" width="2.047" height=".25" x="24.4" y="28.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".05"/></filter><filter id="i0LkKTm" width="2.992" height="2.992" x="9.932" y="9.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".25"/></filter><filter id="i4aKd3b" width="3.592" height="3.592" x="19.279" y="8.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iGNz4ab" width="2.992" height="2.992" x="19.455" y="9.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".25"/></filter><filter id="itYLCte" width="3.262" height="4.184" x="14.311" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".375"/></filter><filter id="iCY3CKd" width="2.379" height="3.184" x="14.991" y="9.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".125"/></filter><filter id="ilydUyc" width="3.621" height="1.474" x="14.37" y="13.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".05"/></filter><filter id="i0a0ITc" width=".787" height=".697" x="17.627" y="9.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".05"/></filter><filter id="i12hndB" width=".892" height=".914" x="18.468" y="9.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".1"/></filter><filter id="iji5hKe" width=".987" height="1.041" x="14.022" y="9.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".1"/></filter><filter id="ivOZ0vp" width=".914" height=".705" x="13.266" y="9.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".05"/></filter><filter id="ipv5Bdz" width="2.604" height="1.648" x="17.445" y="7.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iECVqzb" width="2.459" height="1.252" x="17.518" y="7.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".15"/></filter><filter id="i42SN1d" width="2.604" height="1.648" x="12.312" y="7.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="iKSGBGc" width="2.509" height="1.302" x="12.359" y="7.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".15"/></filter><filter id="ihOdBcc" width="2.013" height="4.025" x="20.575" y="6.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.458824 0 0 0 0 0.0352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2384"/></filter><filter id="irmi2ZB" width="9.346" height="5.558" x="14.326" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".5"/></filter><filter id="iqUg17d" width="7.084" height="4.956" x="8.009" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2384" stdDeviation=".75"/></filter><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="izKufic" x1="16.549" x2="17.449" y1="19.058" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iMs2ZOe" x1="26.353" x2="26.353" y1="20.724" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="iP3rqkj" x1="26.502" x2="26.502" y1="20.724" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="iiRkkfe" x1="28.033" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="xwbtobibq"/></linearGradient><linearGradient id="iUJybld" x1="26.205" x2="24.369" y1="25.952" y2="25.952" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iL4BC4d" x1="26.127" x2="24.291" y1="27.257" y2="27.257" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="ifAlXyK" x1="26.205" x2="24.369" y1="28.562" y2="28.562" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iTQMSDb" x1="11.428" x2="10.787" y1="10.936" y2="10.936" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iKWrRBb" x1="22.038" x2="21.219" y1="9.564" y2="12.103" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i0pFysd" x1="20.22" x2="12.576" y1="11.047" y2="12.186" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="ibvBOFw" x1="10.78" x2="14.784" y1="13.745" y2="13.285" gradientUnits="userSpaceOnUse"><stop offset=".004" class="cr_u9odal"/><stop offset="1" class="ecoitqb9g"/></linearGradient><linearGradient id="iGPrLid" x1="16.672" x2="16.672" y1=".906" y2="17.176" gradientUnits="userSpaceOnUse"><stop offset=".973" class="xk_wczb0d"/><stop offset="1" class="vf1tc-b_w"/></linearGradient><linearGradient id="iaGgRBc" x1="15.316" x2="16.255" y1="11.706" y2="11.706" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iWxXUIc" x1="17.12" x2="16.093" y1="12.029" y2="12.014" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iEVJPYJ" x1="16.375" x2="16.375" y1="12.772" y2="12.199" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="ik9xdyd" x1="16.306" x2="16.306" y1="12.814" y2="12.646" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="i9uDugE" x1="19.14" x2="18.826" y1="10.028" y2="10.222" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iL1Cakc" x1="14.739" x2="14.425" y1="10.028" y2="10.222" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-artist" /></template>
<style>
.a_iq15w2m {
  stop-color: var(--svg-color--f98b29, #F98B29);
}

.a3lgdnbbr {
  d: path("M13.015 4.726c-.973-.093-2.504.103-3.147.212c-.174.136-.48.541-.31 1.082c.17.54.574.65.754.637c3.302-.637 3.92-1.815 2.703-1.931");
}

.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.acw_xab5u {
  stop-color: var(--svg-color--ed577d, #ED577D);
  stop-opacity: 0;
}

.af2-qb9bh {
  fill: var(--svg-color--000, #000);
  d: path("M17.852 10.39a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.235");
}

.af9b0l-ho {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b5vkxmrbt {
  stop-color: var(--svg-color--b56b24, #B56B24);
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.c-6oblcgx {
  d: path("M19.16 10.272a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
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

.cr_u9odal {
  stop-color: var(--svg-color--d38c27, #D38C27);
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.cyvqbbbfl {
  cx: 20.951px;
  cy: 10.657px;
  r: 0.996px;
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d4-80i5ez {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.577 8.308c-.21-.193-.803-.52-1.659-.44");
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dx5j-abwb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.525 28.562h1.797");
}

.dzl2vxb3t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.298 9.686c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.e1lnunasd {
  stop-color: var(--svg-color--e97a27, #E97A27);
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.ecoitqb9g {
  stop-color: var(--svg-color--d38c27, #D38C27);
  stop-opacity: 0;
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

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.eyljfybem {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.18 13.79a3 3 0 0 1-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.92.846 1.585.846s1.249-.339 1.584-.847c.087-.13-.06-.279-.198-.209c-.401.21-.873.329-1.386.329Z");
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.fawsh83wa {
  d: path("M14.064 19.957c.824-.79 1.717-.938 2.058-.89c.133 1.792-.012 2.527-.723 3.308c-.424.466-1.054.723-1.51.843c-.203.054-.387-.107-.384-.318c.004-.362.011-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fomm8__lp {
  d: path("M16.142 18.394c-1.05 0-1.908-.507-1.908-1.291V14.41c0-1.109.858-2.016 1.908-2.016s1.91.907 1.91 2.017v2.692c0 .796-.86 1.29-1.91 1.29");
}

.fp7gzobqh {
  stop-color: var(--svg-color--ba4810, #BA4810);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
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

.gtmq6ja1j {
  stop-color: var(--svg-color--ffd235, #FFD235);
}

.gzbsswvik {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hf8g6bcbv {
  d: path("m15.798 10.371l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.378-.646-.378-.765 0");
}

.hfzp6f8qe {
  d: path("M27.734 23.018a.97.97 0 0 1 .967.967V26.2h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.hhhm45baq {
  stop-color: var(--svg-color--ffc432, #FFC432);
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hu6doibrz {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.18 13.79a3 3 0 0 1-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.92.846 1.585.846s1.249-.339 1.584-.847c.087-.13-.06-.279-.198-.209c-.401.21-.873.329-1.386.329");
}

.i_v7yqz-n {
  d: path("M13.992 9.497a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .033-.235a.9.9 0 0 0-.898-.893");
}

.i-h2msbga {
  fill-rule: evenodd;
  d: path("M17.962 8.45c.72-.068 1.183.213 1.295.316a.473.473 0 1 0 .64-.695c-.306-.283-1.032-.656-2.023-.563a.473.473 0 1 0 .088.941");
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

.ieyl9py5s {
  stop-color: var(--svg-color--ffaa2a, #FFAA2A);
}

.imbe-6h8j {
  cx: 13.723px;
  cy: 9.878px;
  rx: 0.39px;
  ry: 0.197px;
}

.iouks0fsc {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.115c-.099-.66-.234-1.26-.432-1.875h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.111z");
}

.ir0pz063d {
  d: path("M9.878 6.073q-.012.196.012.395l.59 3.043a.634.634 0 0 0 .596.533c-.013-.197-.024-.54-.035-.842c-.01-.271-.018-.51-.024-.584c0-.267.108-.601.323-.762l.16-.16c.27-.213.377-.534.377-.854v-.77z");
}

.iu6_60l-p {
  stop-color: var(--svg-color--e97a27, #E97A27);
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

.j0piksb8i {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
}

.joygt0b9v {
  cx: 20.951px;
  cy: 10.657px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
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

.jy59mxbdf {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.798 10.371l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.378-.646-.378-.765 0");
}

.jyboxmbnp {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
}

.k1aaqobwu {
  d: path("M11.383 28.264a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kb0m86bqf {
  d: path("M23.143 29.975v-12c2.44 2.023 4 5.078 4 8.494v3.505z");
}

.kcmf541da {
  stop-color: var(--svg-color--e5814f, #E5814F);
}

.kfex23bvh {
  cx: 16.143px;
  cy: 17.314px;
  rx: 4.489px;
  ry: 3.08px;
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
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

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
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

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mk9cbeb_z {
  fill: var(--svg-color--352b40, #352B40);
  d: path("M9.007 5.835c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.738.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H10.264c-.685 0-1.257-.429-1.257-1.139");
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.n2c-64r5n {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.57 9.225c.654 0 1.206.45 1.357 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
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

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nq-qoxvcp {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.905 10.535l-.821 1.7c-.102.35.143.7.489.7h.737c.347 0 .59-.355.489-.7l-.499-1.7c-.107-.377-.283-.377-.395 0");
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.o-7j6m7ef {
  cx: 11.428px;
  cy: 10.657px;
  r: 0.996px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pepvmtr_g {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.441");
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

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q0u2bl4sa {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
  stop-opacity: 0;
}

.q6imb_bng {
  stop-color: var(--svg-color--e57329, #E57329);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
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

.qs7c013mg {
  d: path("M18.221 19.957c-.824-.79-1.717-.938-2.058-.89c-.133 1.792.011 2.527.722 3.308c.425.466 1.055.723 1.51.843c.204.054.388-.107.385-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3gzp2rve {
  stop-color: var(--svg-color--ba4810, #BA4810);
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rq_si6b4y {
  d: path("M18.298 9.686c.064.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s3g09k5mk {
  d: path("M20.307 2.79c2.008.772 2.24 2.384 2.365 3.36c-3.464-.783-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.t1tb7n8-g {
  stop-color: var(--svg-color--eb832a, #EB832A);
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

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.u1fjg6bbb {
  stop-color: var(--svg-color--eb832a, #EB832A);
  stop-opacity: 0;
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
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

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vf1tc-b_w {
  stop-color: var(--svg-color--e47468, #E47468);
}

.vl4d3lbhw {
  stop-color: var(--svg-color--e66d36, #E66D36);
}

.vn0ta5bom {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
}

.vnvkvjbds {
  stop-color: var(--svg-color--dd929a, #DD929A);
  stop-opacity: 0;
}

.vojt97b2p {
  fill-rule: evenodd;
  d: path("M14.4 8.45c-.721-.068-1.183.213-1.295.316a.473.473 0 0 1-.641-.695c.306-.283 1.032-.656 2.023-.563a.473.473 0 1 1-.088.941");
}

.vq38zyg1v {
  stop-color: var(--svg-color--c6a0e4, #C6A0E4);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vs-10bcrv {
  fill: var(--svg-color--000, #000);
  d: path("M14.504 10.39a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.235");
}

.vx8yiwdcw {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.976c-2.718.336-4.203 3.242-3.156 6.171z");
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.w4boyzb-m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M24.447 27.257h1.797");
}

.w8pu7oqgu {
  d: path("M20.575 6.073v.77c0 .32.16.64.375.853c.398.395.466.523.422.956a24 24 0 0 0-.027.488c-.015.301-.034.678-.054.958c.312-.008.52-.219.572-.533l.59-3.043a2 2 0 0 0 .033-.45z");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.we9c_ibih {
  cx: 13.723px;
  cy: 9.878px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.wietpnb7v {
  stop-color: var(--svg-color--ffb03a, #FFB03A);
  stop-opacity: 0;
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wnqlpqbzw {
  d: path("M18.364 9.497a.893.893 0 0 1 .86 1.128H17.5a.897.897 0 0 1 .865-1.128");
}

.wnui32bcq {
  cx: 20.951px;
  cy: 10.657px;
  r: 1.671px;
}

.wwkh3zbvl {
  fill: var(--svg-color--b693a1, #B693A1);
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.424-1.683-2.579-3.759-2.579s-3.758 1.155-3.758 2.579c0 .979.795 1.83 1.967 2.267c-.389.437-.404.981-.404 1.486l-.014.924c-.002.177.152.312.323.267c.381-.101.909-.316 1.264-.707c.378-.414.565-.813.622-1.433c.058.62.245 1.019.622 1.433c.356.391.883.606 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.wxgmfgbgc {
  d: path("M14.808 10.285c0-.289-.234-.481-.298-.54l-.288.28l.177.361z");
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xcc0mcchc {
  stop-color: var(--svg-color--efa20d, #EFA20D);
}

.xk_wczb0d {
  stop-color: var(--svg-color--e47468, #E47468);
  stop-opacity: 0;
}

.xwbtobibq {
  stop-color: var(--svg-color--ffae37, #FFAE37);
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y25vf2b0q {
  d: path("M11.076 10.043a30 30 0 0 1-.058-1.44c0-.266.107-.586.322-.747l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.053.429.267.429.534v.854c0 .32.16.64.376.854c.502.352.47.546.429.961c-.013.129-.054 1.196-.09 1.441l-.265 3.962c-.161 1.772-1.553 3.006-3.214 3.006h-3.213c-1.714 0-3.053-1.234-3.214-3.005z");
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.yf6m5abnn {
  d: path("m25.169 16.58l.685-.093c.322 0 .735.472.735.794c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.059.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.17.102-.19");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yqjjaj6xj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.785 9.225c-.653 0-1.205.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.373-1.128");
}

.yraxlebfz {
  cx: 11.428px;
  cy: 10.657px;
  r: 1.671px;
}

.z1tlh1brf {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.784 8.308c.21-.193.804-.52 1.66-.44");
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.zbs2xvbkg {
  d: path("M9.143 17.989a10.96 10.96 0 0 1 7-2.514c2.658 0 5.097.943 7 2.514v11.985h-14z");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
