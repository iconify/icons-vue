<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRA0n0b)"><path fill="url(#izjUkoe)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#iF7WxFe)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#iyCbR0b)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#ido6NFe)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#iZ0Pcyd)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#ihToLxc)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#ilu7xib)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#iphZPnM)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#iZPqgXj)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#irLm8xc)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#ijpXqfQ)" clip-rule="evenodd" class="jo2jtobzf"/><path fill="url(#i6Tz2Cc)" clip-rule="evenodd" class="jo2jtobzf"/></g><path fill="url(#iQiRM2d)" class="zbs2xvbkg"/><path fill="url(#inA3Tpe)" class="zbs2xvbkg"/><path fill="url(#iP1im0c)" class="zbs2xvbkg"/><path fill="url(#i04jDnj)" class="zbs2xvbkg"/><g filter="url(#iOWGZJn)"><path clip-rule="evenodd" class="z22rj_0ie"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#iWgC3vu)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#ihgaZob)"><path fill="url(#iZYJJTd)" class="fawsh83wa"/><path fill="url(#in5HY3d)" class="fawsh83wa"/></g><g filter="url(#idxtG1c)"><path fill="url(#iCgYo9c)" class="qs7c013mg"/><path fill="url(#izKufic)" class="qs7c013mg"/><path fill="url(#i8efCLe)" class="qs7c013mg"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#in51ipd)"><path fill="url(#iIo36rp)" class="pepvmtr_g"/><path fill="url(#ignAelv)" class="pepvmtr_g"/></g><path fill="url(#iqkeVzb)" class="l29svp3cg"/><path fill="url(#ib6zMLd)" class="l29svp3cg"/><g filter="url(#itpvyXb)"><path fill="url(#izcCUib)" class="vx8yiwdcw"/></g><g filter="url(#iVwKUWb)"><path class="oh_l9db2x"/></g><g filter="url(#iWjQSXd)"><path class="teu3yl5ky"/></g><g filter="url(#iRi8wDb)"><path class="waw2uhbiy"/></g><g filter="url(#iJJffzb)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#iddPkqd)"><path fill="url(#iyQIgyc)" class="k1aaqobwu"/></g><g filter="url(#iudEynd)"><path fill="url(#iO8TsTc)" class="i20220bfm"/></g><path fill="url(#i4gM3yb)" class="i20220bfm"/><path fill="url(#i5sdV9b)" class="hfzp6f8qe"/><path fill="url(#ipDnGwe)" class="hfzp6f8qe"/><path fill="url(#iTfdAvb)" class="kb0m86bqf"/><path fill="url(#iTkYgvd)" class="kb0m86bqf"/><path fill="url(#iqMfzad)" class="kb0m86bqf"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iMs2ZOe)" class="s80w1fafw"/><g filter="url(#iV2oDwe)"><path fill="url(#i1FSYJc)" class="iouks0fsc"/><path fill="url(#iZLdWle)" class="iouks0fsc"/><path fill="url(#iZaoaBd)" class="iouks0fsc"/><path fill="url(#iP3rqkj)" class="iouks0fsc"/></g><path fill="url(#ieEgdTd)" class="yf6m5abnn"/><g filter="url(#i5djkDd)"><path fill="url(#iSbgAfc)" class="uhuv92bap"/><path fill="url(#ibiMAze)" class="uhuv92bap"/><path fill="url(#iR3m9Xd)" class="uhuv92bap"/><path fill="url(#ixbEKEd)" class="uhuv92bap"/></g><g filter="url(#iXGj7nd)"><path fill="url(#iZhxhxc)" class="m2-b5ia7e"/><path fill="url(#i7IXbwv)" class="m2-b5ia7e"/><path fill="url(#iKkzrpi)" class="m2-b5ia7e"/><path fill="url(#ibg8boe)" class="m2-b5ia7e"/><path fill="url(#iLHHOUb)" class="m2-b5ia7e"/></g><g filter="url(#iGlOLqe)"><path stroke="url(#iLqYavd)" class="ct65j078y"/></g><g filter="url(#ioR8OUd)"><path stroke="url(#i1gnNXd)" class="ze5nteb_r"/></g><g filter="url(#iGHBwXT)"><path stroke="url(#ipiokXd)" class="jz78atb4u"/></g><g filter="url(#i1NFgle)"><path fill="url(#iy2WWbc)" class="j0kpihu0z"/><path fill="url(#iARC5my)" class="j0kpihu0z"/></g><path fill="url(#iY9HAAc)" class="ge21ot55e"/><path fill="url(#iTrUkge)" class="h-1dj5qtj"/><g filter="url(#ioInKvP)"><path fill="url(#ip9NV3d)" class="ne5ts4kcm"/></g><path fill="url(#iCUFE6b)" class="ne5ts4kcm"/><g filter="url(#iT8Wpkd)"><path fill="url(#ijYkr4c)" class="b2r-vm7ra"/><path fill="url(#imsWtNb)" class="b2r-vm7ra"/></g><g filter="url(#iuhOeze)"><path class="eypyd4khh"/><path fill="url(#iogu8Lc)" class="agdkiqm-x"/></g><g filter="url(#iB69gnd)"><path class="msyr2fbgk"/><path fill="url(#ijlcZDc)" class="shh9e5bqh"/></g><g filter="url(#iyqcy8b)"><path fill="url(#ieTp4eG)" class="wy0j3edwx"/><path fill="url(#iivBiPc)" class="wy0j3edwx"/><path fill="url(#igF6gkC)" class="wy0j3edwx"/><path fill="url(#ixGozGc)" class="wy0j3edwx"/><path fill="url(#ictL6rQ)" class="wy0j3edwx"/><path fill="url(#iaH8npb)" class="wy0j3edwx"/><path fill="url(#i6gqKod)" class="wy0j3edwx"/><path fill="url(#iNr3aPc)" class="wy0j3edwx"/></g><path fill="url(#icaQlRu)" class="wy0j3edwx"/><g filter="url(#ilAYOMc)"><path class="vd8iz2b9c"/></g><g filter="url(#iVi1hvo)"><path class="loqu9pbrh"/><path fill="url(#idX2cMc)" class="hv50u6v_v"/><path fill="url(#i9uobxd)" class="hv50u6v_v"/><path fill="url(#inSNGAe)" class="hv50u6v_v"/><path fill="url(#iydzMmb)" class="hv50u6v_v"/></g><path fill="url(#iZukJ9c)" class="hv50u6v_v"/><path fill="url(#ibLza5c)" class="hv50u6v_v"/><path stroke="url(#iEGMGKb)" class="ty5728mzb"/><g filter="url(#iL0N40d)"><path class="rjwu13j7f"/></g><g filter="url(#iXHRXJf)"><path class="p9ugcubei"/></g><g filter="url(#iIBLAyb)"><path class="hlwveacxj"/></g><g filter="url(#iVLSo3c)"><path clip-rule="evenodd" class="p95cpcbrg"/></g><path class="o6lv47jpi"/><path fill="url(#i0t3DQc)" class="pgj3lob2t"/><path class="e6nebcdfe"/><g filter="url(#ieFpEad)"><path class="fkm9njb4p"/><path fill="url(#iGkjQac)" class="ev-6i5blq"/></g><g filter="url(#iKju8rc)"><path fill="url(#iMn5bVd)" class="l058mzdpc"/></g><path class="iiwesrb4t"/><path fill="url(#i9RIvHd)" class="gzmoq7brp"/><path class="a2j8vubtv"/><g filter="url(#iJPXK6b)"><path fill="url(#iRFikbc)" class="b8u4e-dfp"/></g><g filter="url(#ie6YYdt)"><ellipse transform="rotate(-27.914 13.69 10.37)" class="aibropbyw"/><ellipse fill="url(#iIdd8Fe)" transform="rotate(-27.914 13.69 10.37)" class="sisqyrrfe"/></g><g filter="url(#iFoymud)"><path class="wji54lblo"/></g><g filter="url(#iEZAQ2b)"><path class="wp0ip0rky"/></g><g filter="url(#icAXoAd)"><path class="a3s61ds0e"/><path fill="url(#ibfCkPc)" class="kvbiwh4ak"/><path fill="url(#i0wlfkc)" class="kvbiwh4ak"/></g><g filter="url(#iVfrPJb)"><path class="zoo1_2fod"/><path fill="url(#i3Ch1XR)" class="ybcbxfbyv"/><path fill="url(#iLnQ5Lc)" class="ybcbxfbyv"/></g><g filter="url(#i94lJ8u)"><path stroke="url(#inkcKfd)" class="ld7e_pbkj"/></g><g filter="url(#iEwCUBx)"><path stroke="url(#ifRPnZd)" class="z304cabpx"/></g><g filter="url(#ijWcqUc)"><path stroke="url(#iLeHoBc)" class="vfggmllpb"/></g><g filter="url(#ijWcqUc)"><path stroke="url(#iLeHoBc)" class="vfggmllpb"/></g><path fill="url(#i50kCAd)" class="tpv18l7lf"/><path fill="url(#iLkxb5d)" class="tpv18l7lf"/><path fill="url(#i7616Eh)" class="tpv18l7lf"/><g filter="url(#ifHnNdJ)"><path fill="url(#iwfm65c)" class="s3g09k5mk"/></g><g filter="url(#iYAs0Gc)"><path fill="url(#in6AZkm)" class="a3lgdnbbr"/></g><defs><radialGradient id="iF7WxFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.842 13.565)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iyCbR0b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 13.025 13.833)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="ido6NFe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.861 8.434)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iZ0Pcyd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.28 7.924)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="ihToLxc" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 3.824 11.95)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="ilu7xib" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.935 7.093)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iphZPnM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.652 10.212)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iZPqgXj" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.685 8.235)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="irLm8xc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.22 -3.578)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="ijpXqfQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 10 10.176)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="i6Tz2Cc" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.433 -3.73)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iQiRM2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.974)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="iP1im0c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.974)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="in5HY3d" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.421 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iyQIgyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.784)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="i5sdV9b" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.869 16.305)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="ipDnGwe" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 28.466 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibiMAze" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.594)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="i7IXbwv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.656 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iKkzrpi" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.656 26.573)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ibg8boe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.656 27.823)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iLHHOUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.656 29.175)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iy2WWbc" cx="0" cy="0" r="1" gradientTransform="rotate(138.439 5.875 11.759)scale(2.57895 1.90476)" gradientUnits="userSpaceOnUse"><stop class="dfas76pad"/><stop offset="1" class="zgmzxub1k"/></radialGradient><radialGradient id="iARC5my" cx="0" cy="0" r="1" gradientTransform="matrix(0 .75 -2.28629 0 16.143 16.598)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="xxm9j80um"/><stop offset="1" class="ytueivx8a"/><stop offset="1" class="wm-qik9og"/></radialGradient><radialGradient id="iCUFE6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 11.064 12.673)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="ijYkr4c" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.182 11.503)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="imsWtNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 21.087 9.357)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iogu8Lc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.534 11.176)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="ijlcZDc" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.77 5.532)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="ieTp4eG" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.346 7.348)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iivBiPc" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.86 7.595)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="igF6gkC" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.98 17.034)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="ixGozGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.34375 -11.3394 0 15.88 10.082)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="k3ge6n0nq"/><stop offset=".894" class="m8x8bsblw"/><stop offset=".97" class="nxxjl6inl"/></radialGradient><radialGradient id="ictL6rQ" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.38 7.001)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iaH8npb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.444 10.108)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="i6gqKod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 14.066 9.88)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iNr3aPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.526 7.792)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="icaQlRu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.238 11.595)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="idX2cMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.928 12.322)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iydzMmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.687 12.534)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="ibLza5c" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.408 8.532)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="i0t3DQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.325 10.466)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iGkjQac" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 18.096 10.55)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9RIvHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.96 10.467)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iIdd8Fe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.097 -1.388)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibfCkPc" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.744 -3.994)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="i0wlfkc" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 12.192 7.366)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="i3Ch1XR" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.04 7.245)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iLnQ5Lc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.354 3.508)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="iLkxb5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iwfm65c" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="in6AZkm" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.377 3.233)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="iRA0n0b" width="15.268" height="15.768" x="8.634" y="1.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="iOWGZJn" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".75"/></filter><filter id="iWgC3vu" width="8.987" height="5.737" x="11.649" y="14.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".2"/></filter><filter id="ihgaZob" width="2.812" height="4.17" x="13.354" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="idxtG1c" width="2.762" height="4.17" x="16.118" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="in51ipd" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="itpvyXb" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2392" result="effect2_innerShadow_4002_2392"/></filter><filter id="iVwKUWb" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".075"/></filter><filter id="iWjQSXd" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".075"/></filter><filter id="iRi8wDb" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".075"/></filter><filter id="iJJffzb" width="2.58" height="2.68" x="7.143" y="22.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2392" result="effect2_innerShadow_4002_2392"/></filter><filter id="iddPkqd" width="2.58" height="2.68" x="10.143" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2392" result="effect2_innerShadow_4002_2392"/></filter><filter id="iudEynd" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2392" result="effect2_innerShadow_4002_2392"/></filter><filter id="iV2oDwe" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="i5djkDd" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="iXGj7nd" width="4.846" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.352941 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="iGlOLqe" width="2.097" height=".3" x="24.375" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".05"/></filter><filter id="ioR8OUd" width="2.097" height=".3" x="24.297" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".05"/></filter><filter id="iGHBwXT" width="2.097" height=".3" x="24.375" y="28.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".05"/></filter><filter id="i1NFgle" width="3.859" height="4.694" x="14.213" y="13.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.192157 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="ioInKvP" width="3.368" height="3.218" x="9.848" y="9.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="iT8Wpkd" width="3.218" height="3.468" x="19.361" y="9.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="iuhOeze" width="3.148" height="3.148" x="19.396" y="9.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".25"/></filter><filter id="iB69gnd" width="2.848" height="2.848" x="10.052" y="9.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".175"/></filter><filter id="iyqcy8b" width="10.191" height="10.977" x="11.047" y="6.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="ilAYOMc" width="2.877" height="3.682" x="14.542" y="10.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".25"/></filter><filter id="iVi1hvo" width="2.377" height="3.182" x="14.954" y="10.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".125"/></filter><filter id="iL0N40d" width="3.001" height="1.285" x="17.085" y="9.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="iXHRXJf" width="3.001" height="1.285" x="12.199" y="9.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="iIBLAyb" width="2.453" height="1.091" x="12.335" y="8.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="iVLSo3c" width="2.453" height="1.091" x="17.752" y="8.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/></filter><filter id="ieFpEad" width=".787" height=".696" x="17.59" y="10.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".05"/></filter><filter id="iKju8rc" width=".891" height=".913" x="18.43" y="10.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".1"/></filter><filter id="iJPXK6b" width=".986" height="1.04" x="13.988" y="10.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".1"/></filter><filter id="ie6YYdt" width=".913" height=".704" x="13.233" y="10.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".05"/></filter><filter id="iFoymud" width="2.261" height=".978" x="17.782" y="8.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".1"/></filter><filter id="iEZAQ2b" width="2.261" height=".978" x="12.33" y="8.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".1"/></filter><filter id="icAXoAd" width="4.312" height="4.613" x="9.788" y="4.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/><feGaussianBlur result="effect2_foregroundBlur_4002_2392" stdDeviation=".2"/></filter><filter id="iVfrPJb" width="8.767" height="5.782" x="12.972" y="2.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2392"/><feGaussianBlur result="effect2_foregroundBlur_4002_2392" stdDeviation=".125"/></filter><filter id="i94lJ8u" width="1.145" height="2.31" x="12.951" y="4.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".1"/></filter><filter id="iEwCUBx" width="1.145" height="2.31" x="12.975" y="4.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".125"/></filter><filter id="ijWcqUc" width="1.145" height="2.31" x="12.998" y="4.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".1"/></filter><filter id="ifHnNdJ" width="9.346" height="5.558" x="14.326" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".5"/></filter><filter id="iYAs0Gc" width="7.084" height="4.956" x="8.009" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2392" stdDeviation=".75"/></filter><linearGradient id="izjUkoe" x1="20.836" x2="14.701" y1="4.111" y2="14.872" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="izKufic" x1="16.549" x2="17.449" y1="19.058" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iMs2ZOe" x1="26.353" x2="26.353" y1="20.724" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="iP3rqkj" x1="26.502" x2="26.502" y1="20.724" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="iZhxhxc" x1="28.386" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="a87gyab7w"/></linearGradient><linearGradient id="iLqYavd" x1="24.525" x2="26.234" y1="26.03" y2="26.03" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i1gnNXd" x1="24.447" x2="26.156" y1="27.335" y2="27.335" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ipiokXd" x1="24.525" x2="26.234" y1="28.64" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iY9HAAc" x1="9.005" x2="23.381" y1="15.771" y2="15.771" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iTrUkge" x1="9.005" x2="23.381" y1="15.741" y2="15.741" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ip9NV3d" x1="9.848" x2="11.705" y1="11.151" y2="11.151" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i9uobxd" x1="15.204" x2="16.143" y1="12.395" y2="12.395" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="inSNGAe" x1="16.143" x2="16.143" y1="13.102" y2="12.475" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iZukJ9c" x1="16.221" x2="16.221" y1="13.168" y2="13.028" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="iEGMGKb" x1="15.078" x2="15.539" y1="14.604" y2="13.891" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iMn5bVd" x1="19.103" x2="18.789" y1="10.52" y2="10.714" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRFikbc" x1="14.704" x2="14.391" y1="10.521" y2="10.714" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inkcKfd" x1="13.034" x2="13.524" y1="4.111" y2="5.376" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="ifRPnZd" x1="13.275" x2="13.82" y1="4.763" y2="6.037" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iLeHoBc" x1="13.298" x2="13.843" y1="4.763" y2="6.037" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="i50kCAd" x1="15.975" x2="16.813" y1="2.025" y2="6.974" gradientUnits="userSpaceOnUse"><stop class="nblx7ib8n"/><stop offset="1" class="h7is5ynaf"/></linearGradient><linearGradient id="i7616Eh" x1="17.532" x2="17.532" y1="6.928" y2="6.599" gradientUnits="userSpaceOnUse"><stop class="hj8-3eb_v"/><stop offset="1" class="zofh5ufwh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-artist-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a2j8vubtv {
  fill: var(--svg-color--000, #000);
  d: path("M14.47 10.882a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.a3lgdnbbr {
  d: path("M13.015 4.726c-.973-.093-2.504.103-3.147.212c-.174.136-.48.541-.31 1.082c.17.54.574.65.754.637c3.302-.637 3.92-1.815 2.703-1.931");
}

.a3s61ds0e {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M11.074 5.075c.565-.599 1.636-.6 2.13-.51l.396 1.29c-.253-.039-.295-.001-.485.183c-.138 1.093-1.376 1.757-2.886 2.197c-.149-1.491.108-2.38.845-3.16");
}

.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.a87gyab7w {
  stop-color: var(--svg-color--a57c6f, #A57C6F);
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.acw_xab5u {
  stop-color: var(--svg-color--ed577d, #ED577D);
  stop-opacity: 0;
}

.af9b0l-ho {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
}

.agdkiqm-x {
  d: path("M20.97 12.138a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.aibropbyw {
  cx: 13.689px;
  cy: 10.371px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b2r-vm7ra {
  d: path("M20.97 12.673a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.b8u4e-dfp {
  d: path("M14.774 10.777c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
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

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.dfas76pad {
  stop-color: var(--svg-color--b97b72, #B97B72);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6nebcdfe {
  fill: var(--svg-color--000, #000);
  d: path("M17.816 10.882c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
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

.ev-6i5blq {
  d: path("M18.261 10.178c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.eypyd4khh {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.97 12.138a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
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

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fkm9njb4p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.261 10.178c.064.085-.07.189-.22.302c-.152.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.ge21ot55e {
  d: path("M16.544 15.742c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gzmoq7brp {
  d: path("M13.959 9.99a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
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

.hfzp6f8qe {
  d: path("M27.734 23.018a.97.97 0 0 1 .967.967V26.2h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.hj8-3eb_v {
  stop-color: var(--svg-color--481b64, #481B64);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hlwveacxj {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.745 9.286l-.004.002a.268.268 0 0 1-.276-.46h.001l.003-.002l.01-.006a2 2 0 0 1 .148-.077c.099-.047.24-.107.41-.161c.34-.109.815-.2 1.329-.11a.268.268 0 1 1-.094.529a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.455.194");
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hv50u6v_v {
  d: path("m15.76 10.703l-.531 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i20220bfm {
  d: path("M7.383 29.104a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iiwesrb4t {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.752 9.718c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.iouks0fsc {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.115c-.099-.66-.234-1.26-.432-1.875h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.111z");
}

.izb4o5hjh {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
  stop-opacity: 0;
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_c7fcbhg {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
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

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jo2jtobzf {
  fill-rule: evenodd;
  d: path("M23.328 12.473c.212-.435.324-.92.324-1.427c0-.467-.097-.905-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.681 1.376a.56.56 0 0 1-.456.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.526 1.77l-.002.005a3.3 3.3 0 0 0-.22 3.244c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.581a3.213 3.213 0 0 0 2.895-4.625a.52.52 0 0 1 0-.456m-12.26-2.672h-.013l1.2 2.355c.122 2.803 1.216 0 3.887 0s3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.46.05l-.083.195a2.3 2.3 0 0 1-1.24 1.255l-.052.02c-.236.122-.79.49-.81 1.439l.01.306z");
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

.k1aaqobwu {
  d: path("M11.383 28.264a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k3ge6n0nq {
  stop-color: var(--svg-color--a06079, #A06079);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
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

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.kvbiwh4ak {
  d: path("M11.074 5.075c.565-.599 1.636-.6 2.13-.51l.396 1.29c-.253-.039-.295-.001-.485.183c-.138 1.093-1.376 1.757-2.886 2.197c-.149-1.491.108-2.38.845-3.16");
}

.l058mzdpc {
  d: path("M19.122 10.764a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l29svp3cg {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.532-4.61-2.954c-2.718.334-4.203 3.217-3.156 6.123z");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
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

.ld7e_pbkj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.251 4.522c.024.243.235 1.156.545 1.71");
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.loqu9pbrh {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.76 10.703l-.531 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m2-b5ia7e {
  d: path("M24.005 25.3c0-.401.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.m8x8bsblw {
  stop-color: var(--svg-color--a06079, #A06079);
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

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.msyr2fbgk {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.476 12.138a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
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

.nblx7ib8n {
  stop-color: var(--svg-color--352b40, #352B40);
}

.ne5ts4kcm {
  d: path("M11.457 12.673a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.nxxjl6inl {
  stop-color: var(--svg-color--a4537b, #A4537B);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o6lv47jpi {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.534 9.718c.653 0 1.204.45 1.355 1.058a.274.274 0 0 1-.268.341H17.39a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.37-1.127");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p95cpcbrg {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.874 8.828l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.091a.268.268 0 0 1-.093-.529c.513-.09.989.001 1.329.11a3.3 3.3 0 0 1 .558.238l.01.006l.002.001z");
}

.p9ugcubei {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M15 10.495c-.265-.467-.668-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.599l.556.317c.652-.21 1.372-.239 2.079-.45");
}

.pepvmtr_g {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.441");
}

.pgj3lob2t {
  d: path("M18.327 9.99a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
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

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
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

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
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

.rjwu13j7f {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.285 10.495c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.556.317c-.651-.21-1.372-.239-2.078-.45");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s3g09k5mk {
  d: path("M20.307 2.79c2.008.772 2.24 2.384 2.365 3.36c-3.464-.783-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.shh9e5bqh {
  d: path("M11.476 12.138a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.sisqyrrfe {
  cx: 13.689px;
  cy: 10.371px;
  rx: 0.39px;
  ry: 0.197px;
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
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

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tpv18l7lf {
  d: path("M9.007 5.835c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.738.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H10.264c-.685 0-1.257-.429-1.257-1.139");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.ty5728mzb {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.81 13.877a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.247-.04c-.404.215-.88.338-1.399.338c-.512 0-.994-.123-1.397-.339h-.001a.204.204 0 0 0-.247.044a.196.196 0 0 0-.02.247m3.332 0l-.042-.027zm0 0a1.982 1.982 0 0 1-3.333 0m0 0v.001l.042-.028m-.042.027l.042-.027m0 0a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.895.345-1.422.345a3 3 0 0 1-1.421-.344c-.14-.074-.292.088-.203.219Z");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.uhuv92bap {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.076c-1.248.083-2.375.65-2.978 1.74a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.366.87-.828c0-.054-.01-.107-.02-.161v-.01c-.162-.7-.054-1.291.279-1.882a.33.33 0 0 0-.075-.387");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vd8iz2b9c {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.75 10.84l-.684 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.376-.494-.376-.613 0");
}

.vfggmllpb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.298 4.42c.024.243.235 1.156.545 1.71");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
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

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vx8yiwdcw {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.976c-2.718.336-4.203 3.242-3.156 6.171z");
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wji54lblo {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.082 8.691c.323-.079 1.125-.04 1.66.344");
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wm-qik9og {
  stop-color: var(--svg-color--9d4e70, #9D4E70);
  stop-opacity: 0;
}

.wp0ip0rky {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.291 8.691c-.322-.079-1.125-.04-1.66.344");
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.wy0j3edwx {
  d: path("M11.055 9.801h.013l-.01-.265l-.01-.306c.02-.95.573-1.317.81-1.439l.05-.02q.028-.013.052-.02a2.3 2.3 0 0 0 1.19-1.235l.081-.194a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.081.087 1.135 1.332l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xxm9j80um {
  stop-color: var(--svg-color--9d4e70, #9D4E70);
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.ybcbxfbyv {
  d: path("M15.54 3.273c-1.133-.25-2.15.88-2.268 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.878.888c0-3.933-3.345-4.67-5.922-5.24z");
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.yf6m5abnn {
  d: path("m25.169 16.58l.685-.093c.322 0 .735.472.735.794c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.059.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.17.102-.19");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.ytueivx8a {
  stop-color: var(--svg-color--7c3759, #7C3759);
  stop-opacity: 0;
}

.z22rj_0ie {
  fill: var(--svg-color--b693a1, #B693A1);
  fill-rule: evenodd;
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.424-1.683-2.579-3.759-2.579s-3.758 1.155-3.758 2.579c0 .979.795 1.83 1.967 2.267c-.389.437-.404.981-.404 1.486l-.014.924c-.002.177.152.312.323.267c.381-.101.909-.316 1.264-.707c.378-.414.565-.813.622-1.433c.058.62.245 1.019.622 1.433c.356.391.883.606 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
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

.zbs2xvbkg {
  d: path("M9.143 17.989a10.96 10.96 0 0 1 7-2.514c2.658 0 5.097.943 7 2.514v11.985h-14z");
}

.ze5nteb_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.447 27.257h1.797");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zgmzxub1k {
  stop-color: var(--svg-color--9b5264, #9B5264);
}

.zofh5ufwh {
  stop-color: var(--svg-color--481b64, #481B64);
  stop-opacity: 0;
}

.zoo1_2fod {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.54 3.273c-1.133-.25-2.15.88-2.268 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.878.888c0-3.933-3.345-4.67-5.922-5.24z");
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
