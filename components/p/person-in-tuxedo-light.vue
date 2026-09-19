<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDFerFe)" class="fgk-5hbhi"/><path fill="url(#i0bnV8d)" class="fgk-5hbhi"/><path fill="url(#iKSChfb)" class="fgk-5hbhi"/><path fill="url(#iOgV9Cc)" class="fgk-5hbhi"/><path fill="url(#iREYwin)" class="fgk-5hbhi"/><path fill="url(#iZenc8c)" class="jockr5brf"/><path fill="url(#iKXZx0b)" class="jockr5brf"/><g filter="url(#ikLKrFX)"><path fill="url(#i1gRHJc)" class="hkh85bbeh"/><path fill="url(#iOyX0na)" class="hkh85bbeh"/></g><path fill="url(#i1fkYzc)" class="k8ix0jbxx"/><g filter="url(#i4lB3Ob)"><path fill="url(#iviLTSb)" class="mj9a-09qg"/><path fill="url(#iLbvW7l)" class="mj9a-09qg"/></g><g filter="url(#iVoftNb)"><path class="ow2sicbjy"/></g><path fill="url(#ivWFWhb)" class="r66it6rvi"/><path fill="url(#ikgV5Dc)" class="r66it6rvi"/><path fill="url(#iuTRW6b)" class="r66it6rvi"/><path fill="url(#iRSaCgd)" class="r66it6rvi"/><path fill="url(#i5AU1ke)" class="x3n8sshto"/><path fill="url(#iCIUKvd)" class="x3n8sshto"/><path fill="url(#iG0bM9I)" class="x3n8sshto"/><path fill="url(#iqxFvob)" class="x3n8sshto"/><g filter="url(#iBta20d)"><path fill="url(#iWg0yye)" class="o4j6k38-e"/></g><g filter="url(#iOZMiNc)"><path fill="url(#imi6qCe)" class="rnafodbyg"/></g><path fill="url(#igjxDfb)" class="rnafodbyg"/><path fill="url(#i6QxIpL)" class="rnafodbyg"/><path fill="url(#iZVvX9d)" class="rnafodbyg"/><g filter="url(#iL2RVKs)"><path class="c3yl_4bph"/></g><g filter="url(#iyM5wOd)"><circle class="dr-k41b2k"/></g><g filter="url(#ixQFNwc)"><circle class="uy8ok031y"/></g><g filter="url(#iXqCAfc)"><circle fill="url(#iu4bQzc)" class="smrxvvbzr"/></g><g filter="url(#iBLGbBd)"><circle fill="url(#i1xsAGY)" class="cnk20mb3o"/></g><rect fill="url(#iCRMJgP)" class="cydfracdw"/><rect fill="url(#iWGvSsc)" class="cydfracdw"/><rect fill="url(#i4nVo8k)" class="cydfracdw"/><rect fill="url(#i7msYob)" class="cydfracdw"/><rect fill="url(#ihsrrwe)" class="cydfracdw"/><rect fill="url(#il8a3pw)" class="cydfracdw"/><g filter="url(#in7ATmb)"><path fill="url(#iHrAMlb)" class="zipbdebnb"/></g><path fill="url(#iDvp61c)" class="zipbdebnb"/><g filter="url(#ia9mUpd)"><path class="t7vx_s46x"/><path fill="url(#i0fii8l)" class="d5_vr-a5y"/><path fill="url(#i2xtQ7c)" class="d5_vr-a5y"/><path fill="url(#iQbtvjb)" class="d5_vr-a5y"/></g><g filter="url(#itk9bnb)"><circle fill="url(#in03t1b)" class="x5prydbjk"/><circle fill="url(#iHjr1Ec)" class="x5prydbjk"/></g><path fill="url(#iFsrBme)" class="o9yfg-bot"/><path fill="url(#iyztPMh)" class="ekeafib5p"/><g filter="url(#iqLLnOc)"><path fill="url(#iUt7qob)" class="ap80l3dzf"/></g><path fill="url(#ifTLKAc)" class="ap80l3dzf"/><path fill="url(#iqxeVId)" class="ap80l3dzf"/><path fill="url(#iKo5Icw)" class="ap80l3dzf"/><path fill="url(#ipQIXej)" class="ap80l3dzf"/><path fill="url(#iN95Mge)" class="ap80l3dzf"/><path fill="url(#iMQILPb)" class="ap80l3dzf"/><path fill="url(#it0Lsjc)" class="ap80l3dzf"/><g filter="url(#itZvsHb)"><path class="e0tqdtb5g"/></g><g filter="url(#iiBxe3b)"><path class="dl7-adbyx"/><path fill="url(#iNzEHNc)" class="wtm3bmtop"/><path fill="url(#iwkV3jb)" class="wtm3bmtop"/><path fill="url(#iQFUP3t)" class="wtm3bmtop"/><path fill="url(#iWBtnrb)" class="wtm3bmtop"/></g><g filter="url(#ipncWPc)"><path fill="url(#idni7Tb)" class="ucpll26jf"/></g><g filter="url(#ioYuapZ)"><path stroke="url(#i9vyaCd)" class="ohy9e7bld"/></g><path fill="url(#iwxkKdb)" class="vosoddbqj"/><g filter="url(#iANcF4b)"><path fill="url(#iTwSjzb)" class="mgaf8je6n"/><path fill="url(#ik0Wyae)" class="mgaf8je6n"/><path fill="url(#iT3nWmb)" class="mgaf8je6n"/><path fill="url(#iNJacfe)" class="mgaf8je6n"/><path fill="url(#i18iWfU)" class="mgaf8je6n"/></g><g filter="url(#iL9YNFd)"><path class="yuf1bh9ca"/></g><g filter="url(#iddTSqc)"><path class="dj62epb6i"/></g><g filter="url(#iBw2WXc)"><path class="c0xflp5eq"/><path fill="url(#ifiyKye)" class="jlwk53b4u"/><path fill="url(#iteFaxe)" class="jlwk53b4u"/></g><g filter="url(#iIyquLE)"><path class="hcpmthcmx"/><path fill="url(#ics4RPd)" class="hqbcz7bea"/><path fill="url(#iWBwYrO)" class="hqbcz7bea"/><path fill="url(#inIh6ve)" class="hqbcz7bea"/></g><path class="gwtjipbww"/><path fill="url(#ib0c1vd)" class="pknbobctv"/><path class="uazsvlbfo"/><g filter="url(#iKNsmHb)"><path class="vg7jlbcfm"/><path fill="url(#inrSUec)" class="yf575zhfr"/></g><g filter="url(#isDhp8c)"><path fill="url(#ih4IEfb)" class="wzyqdc7qh"/></g><path class="j3wct1b6v"/><path fill="url(#i7Eoz1b)" class="tnrknebzc"/><path class="ifaoigxbp"/><g filter="url(#iahhgxd)"><path fill="url(#ip4g1wc)" class="q8s6r6dsw"/></g><g filter="url(#iK805Bb)"><ellipse transform="rotate(-27.914 13.594 9.923)" class="mzu8nv6ac"/><ellipse fill="url(#ial8N1b)" transform="rotate(-27.914 13.594 9.923)" class="k7k6u_23v"/></g><path fill="url(#iO6O6Ae)" class="fwftsobon"/><path fill="url(#iVnGGsb)" class="fwftsobon"/><path fill="url(#iQA3gHc)" class="fwftsobon"/><path fill="url(#i0BtsMH)" class="fwftsobon"/><path fill="url(#i7fZIbd)" class="dhlq63bxv"/><path fill="url(#iq8qytd)" class="dhlq63bxv"/><g filter="url(#i0WVtwa)"><path fill="url(#ibysauc)" class="jc1dn7boz"/></g><g filter="url(#idUOYpd)"><path fill="url(#i2QkNjb)" class="bmsobzbkx"/></g><g filter="url(#iBPBhpb)"><path class="hcz1trbdm"/></g><g filter="url(#ipEyo4b)"><path class="q9254d18m"/></g><defs><radialGradient id="iDFerFe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.315)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="i0bnV8d" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.77 10.813)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="iKSChfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.226)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iZenc8c" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.241 2.61)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iKXZx0b" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.127)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="i1gRHJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.382)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="i1fkYzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.538)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iviLTSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.508)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iLbvW7l" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.349 13.025)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="ikgV5Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.104 8.356)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="iuTRW6b" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.648)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iCIUKvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.742)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iG0bM9I" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.383)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="imi6qCe" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.075 11.856)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="igjxDfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.264)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="i6QxIpL" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.322)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iZVvX9d" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.659 20.617)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iu4bQzc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.875 16.044)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i1xsAGY" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.493 14.54)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iWGvSsc" cx="0" cy="0" r="1" gradientTransform="matrix(.75 1.28125 -.67469 .39494 14.204 17.66)" gradientUnits="userSpaceOnUse"><stop class="m8qj67bxn"/><stop offset="1" class="lurh12x1h"/></radialGradient><radialGradient id="i4nVo8k" cx="0" cy="0" r="1" gradientTransform="matrix(-.9475 1.63953 -.43892 -.25365 17.949 17.306)" gradientUnits="userSpaceOnUse"><stop class="q4e4b80yr"/><stop offset="1" class="b39zhf_zv"/></radialGradient><radialGradient id="i7msYob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42187 .2344 -.06955 -.71857 15.923 16.831)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="h1w9f41ug"/><stop offset="1" class="wupw8ebgu"/></radialGradient><radialGradient id="ihsrrwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 -.57813 .21434 -.3302 15.47 18.374)" gradientUnits="userSpaceOnUse"><stop class="fd31sgblt"/><stop offset="1" class="i20artbwr"/></radialGradient><radialGradient id="il8a3pw" cx="0" cy="0" r="1" gradientTransform="matrix(.79688 -.5 .2051 .32688 16.736 18.393)" gradientUnits="userSpaceOnUse"><stop class="lhk6elbnr"/><stop offset="1" class="gq_8cv3su"/></radialGradient><radialGradient id="iHrAMlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.73)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iDvp61c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.105)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="i2xtQ7c" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.438 6.855)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iQbtvjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.96)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="in03t1b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.375 12.583)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iHjr1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="iFsrBme" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.866 20.886)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iyztPMh" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 9.99 12.367)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iUt7qob" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22784 0 0 -9.248 18.855 10.935)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iqxeVId" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.3417 -11.4214 0 16.095 4.764)" gradientUnits="userSpaceOnUse"><stop offset=".833" class="w3jr8iqjv"/><stop offset=".992" class="vut4jab5a"/></radialGradient><radialGradient id="iKo5Icw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.495 9.622)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="ipQIXej" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 13.747 9.668)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iN95Mge" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 19.48 11.923)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iMQILPb" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 10.58 6.61)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="it0Lsjc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 18.475 5.956)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iwkV3jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.514 12.296)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iWBtnrb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.63 11.726)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iwxkKdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 16.047 14.474)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="ik0Wyae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50132 8.85443 0 10.818 8.043)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iT3nWmb" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.348 -6.263)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iNJacfe" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.537 -1.479)scale(2.82328 2.07243)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="i18iWfU" cx="0" cy="0" r="1" gradientTransform="matrix(.90512 1.475 -3.41539 2.09582 15.142 1.484)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="ifiyKye" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20112 0 0 -.81692 16.3 3.743)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iteFaxe" cx="0" cy="0" r="1" gradientTransform="matrix(3.21816 -5.09543 5.64521 3.5654 10.617 7.686)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ics4RPd" cx="0" cy="0" r="1" gradientTransform="matrix(3.05838 0 0 1.19577 19.462 4.52)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iWBwYrO" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90405 18.681 7.558)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="inIh6ve" cx="0" cy="0" r="1" gradientTransform="matrix(3.2482 .37966 -.15896 1.35996 17.795 6.081)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ib0c1vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.23 10.018)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="inrSUec" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.475 .643)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i7Eoz1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.866 10.018)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ial8N1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.579 10.238)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVnGGsb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 20.665 10.032)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iQA3gHc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 21.025 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="i0BtsMH" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.14 10.75)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iq8qytd" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.89 5)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="ibysauc" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 11.134 10.675)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><filter id="ikLKrFX" width="4.081" height="11.683" x="5.07" y="18.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/></filter><filter id="i4lB3Ob" width="5.909" height="14.117" x="12.858" y="15.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/></filter><filter id="iVoftNb" width="7.13" height="5.229" x="12.285" y="16.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".3"/></filter><filter id="iBta20d" width="7.239" height="14.645" x="9.195" y="15.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".5"/></filter><filter id="iOZMiNc" width="5.917" height="14.31" x="10.326" y="15.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3335" result="effect2_innerShadow_4002_3335"/></filter><filter id="iL2RVKs" width="6.504" height="14.261" x="15.345" y="15.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3335" result="effect2_innerShadow_4002_3335"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3335" result="effect3_innerShadow_4002_3335"/></filter><filter id="iyM5wOd" width="2" height="2" x="14.731" y="24.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".25"/></filter><filter id="ixQFNwc" width="2" height="2" x="14.731" y="21.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".25"/></filter><filter id="iXqCAfc" width="1.05" height="1.05" x="15.504" y="25.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/></filter><filter id="iBLGbBd" width="1.05" height="1.05" x="15.504" y="22.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/></filter><filter id="in7ATmb" width="2.465" height="2.95" x="16.029" y="17.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3335" result="effect2_innerShadow_4002_3335"/></filter><filter id="ia9mUpd" width="2.365" height="2.9" x="13.731" y="17.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/></filter><filter id="itk9bnb" width="1.717" height="1.717" x="15.204" y="17.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/></filter><filter id="iqLLnOc" width="11.22" height="12.542" x="10.984" y="4.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3335" result="effect2_innerShadow_4002_3335"/></filter><filter id="itZvsHb" width="3.747" height="4.9" x="14.032" y="9.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".5"/></filter><filter id="iiBxe3b" width="2.277" height="3.3" x="14.909" y="9.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".1"/></filter><filter id="ipncWPc" width="2.277" height="3.3" x="14.874" y="9.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".1"/></filter><filter id="ioYuapZ" width="3.718" height="1.573" x="14.188" y="13.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".05"/></filter><filter id="iANcF4b" width="12.873" height="8.356" x="9.611" y="1.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3335" result="effect2_innerShadow_4002_3335"/></filter><filter id="iL9YNFd" width="2.339" height="1.19" x="17.637" y="7.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/></filter><filter id="iddTSqc" width="2.339" height="1.176" x="12.38" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/></filter><filter id="iBw2WXc" width="6.734" height="5.992" x="9.967" y="2.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3335"/><feGaussianBlur result="effect2_foregroundBlur_4002_3335" stdDeviation=".125"/></filter><filter id="iIyquLE" width="6.361" height="5.736" x="15.889" y="3.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".125"/></filter><filter id="iKNsmHb" width=".787" height=".696" x="17.495" y="9.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".05"/></filter><filter id="isDhp8c" width=".891" height=".913" x="18.335" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".1"/></filter><filter id="iahhgxd" width=".986" height="1.04" x="13.893" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".1"/></filter><filter id="iK805Bb" width=".913" height=".705" x="13.137" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".05"/></filter><filter id="i0WVtwa" width="1.329" height="2.379" x="9.967" y="9.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".125"/></filter><filter id="idUOYpd" width="1.947" height="2.903" x="20.553" y="9.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".25"/></filter><filter id="iBPBhpb" width="2.405" height="1.16" x="12.299" y="7.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".125"/></filter><filter id="ipEyo4b" width="2.405" height="1.16" x="17.578" y="7.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3335" stdDeviation=".125"/></filter><linearGradient id="iOgV9Cc" x1="23.131" x2="22.971" y1="29.906" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iREYwin" x1="8.858" x2="9.061" y1="29.906" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iOyX0na" x1="9.19" x2="7.596" y1="29.912" y2="29.912" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="ivWFWhb" x1="14.705" x2="13.268" y1="19.976" y2="16.851" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="iRSaCgd" x1="15.518" x2="15.209" y1="20.054" y2="19.937" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i5AU1ke" x1="16.799" x2="18.471" y1="19.992" y2="17.117" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iqxFvob" x1="16.486" x2="16.713" y1="19.793" y2="19.703" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iWg0yye" x1="12.815" x2="12.815" y1="16.773" y2="29.418" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="iCRMJgP" x1="17.033" x2="14.649" y1="18.383" y2="17.814" gradientUnits="userSpaceOnUse"><stop class="x2gp7fbxb"/><stop offset="1" class="zxzw1vbws"/></linearGradient><linearGradient id="i0fii8l" x1="15.205" x2="14.838" y1="19.429" y2="18.976" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="ifTLKAc" x1="21.205" x2="16.852" y1="12.62" y2="12.62" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iNzEHNc" x1="16.886" x2="16.047" y1="11.61" y2="11.645" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iQFUP3t" x1="16.047" x2="16.047" y1="12.749" y2="12.284" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="idni7Tb" x1="16.012" x2="16.012" y1="9.728" y2="11.434" gradientUnits="userSpaceOnUse"><stop class="mnakovbzb"/><stop offset="1" class="qh2f6oblr"/></linearGradient><linearGradient id="i9vyaCd" x1="14.846" x2="15.164" y1="14.32" y2="13.485" gradientUnits="userSpaceOnUse"><stop class="j8ap3obqe"/><stop offset="1" class="r5nd0wbje"/></linearGradient><linearGradient id="iTwSjzb" x1="22.899" x2="11.287" y1="5.272" y2="5.272" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ih4IEfb" x1="19.008" x2="18.694" y1="10.072" y2="10.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ip4g1wc" x1="14.609" x2="14.296" y1="10.072" y2="10.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iO6O6Ae" x1="22.484" x2="21.277" y1="10.099" y2="12.275" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="i7fZIbd" x1="10.198" x2="11.656" y1="10.803" y2="10.676" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="i2QkNjb" x1="21.526" x2="21.526" y1="9.728" y2="11.632" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-tuxedo-light" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ap80l3dzf {
  d: path("M11.223 13.7a3.916 3.916 0 0 0 3.885 3.406h1.887A3.916 3.916 0 0 0 20.88 13.7c.118-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.117 3.691.239 5.557");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b39zhf_zv {
  stop-color: var(--svg-color--c29281, #C29281);
  stop-opacity: 0;
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bmsobzbkx {
  d: path("M21.053 11.632q.059-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c0xflp5eq {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.28 5.32l-.066-.138a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38v.274c-.34-.258-.767-.804-.767-1.687c0-1.072.781-1.614 1.28-1.96c.14-.097.259-.18.33-.253q.046-.046.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.c3yl_4bph {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.543c.031-1.094-.595-1.537-.887-1.626l-.668-.07v5.815c0 3.874-1.388 6.264-2.648 8.09c-.062.09.047.2.139.138c2.976-2.036 4.851-4.005 5.196-9.228a.203.203 0 0 0-.188-.215c-.321-.02-.607-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.022-1.66.05-2.632");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cnk20mb3o {
  cx: 16.004px;
  cy: 22.567px;
  r: 0.5px;
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cydfracdw {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.281px;
  rx: 1.938px;
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d5_vr-a5y {
  d: path("m14.133 17.475l1.813 1.251l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dhlq63bxv {
  d: path("M11.003 9.075a1.62 1.62 0 0 0-1.392 1.594c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.2");
}

.dj62epb6i {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.637 7.846a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.286a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.dl7-adbyx {
  fill: var(--svg-color--f2bda5, #F2BDA5);
  d: path("m15.665 10.22l-.531 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.dr-k41b2k {
  cx: 15.731px;
  cy: 25.848px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0tqdtb5g {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.646 10.41l-.59 1.839c-.102.378.14.756.484.756h.731c.344 0 .586-.384.485-.756l-.495-1.838c-.106-.408-.504-.408-.615 0");
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.ekeafib5p {
  d: path("M11.186 12.185a1.64 1.64 0 0 1-.905-.309v.931c0 .893.533 1.689 1.341 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fd31sgblt {
  stop-color: var(--svg-color--a05d67, #A05D67);
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fgk-5hbhi {
  d: path("M5.07 26.41c0-5.797 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.823 10.5 10.62v3.496H5.07z");
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwftsobon {
  d: path("M20.97 12.276q.1-1.597.184-3.192a1.61 1.61 0 0 1-.185 3.191");
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gq_8cv3su {
  stop-color: var(--svg-color--a8686e, #A8686E);
  stop-opacity: 0;
}

.gwtjipbww {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.439 9.27c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.h1w9f41ug {
  stop-color: var(--svg-color--af6a76, #AF6A76);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hcpmthcmx {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.26 8.586l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.367c-.256-.97.67-1.713 1.655-1.522c.974.189 2.083.517 2.902 1.052c1.745 1.138 1.44 3.188.521 4.154");
}

.hcz1trbdm {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.674 8.126c.257-.185.898-.509 1.655-.382");
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hkh85bbeh {
  d: path("M8.901 18.23a10.69 10.69 0 0 0-3.831 8.184v3.498H8.9z");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hqbcz7bea {
  d: path("m21.26 8.586l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.367c-.256-.97.67-1.713 1.655-1.522c.974.189 2.083.517 2.902 1.052c1.745 1.138 1.44 3.188.521 4.154");
}

.i20artbwr {
  stop-color: var(--svg-color--a05d67, #A05D67);
  stop-opacity: 0;
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ifaoigxbp {
  fill: var(--svg-color--000, #000);
  d: path("M14.375 10.434a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j3wct1b6v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.656 9.27c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34H14.8a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.j8ap3obqe {
  stop-color: var(--svg-color--f4bcad, #F4BCAD);
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jc1dn7boz {
  d: path("M10.962 9.736a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jlwk53b4u {
  d: path("m16.28 5.32l-.066-.138a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38v.274c-.34-.258-.767-.804-.767-1.687c0-1.072.781-1.614 1.28-1.96c.14-.097.259-.18.33-.253q.046-.046.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.012.806.42.806.893v1.485z");
}

.jockr5brf {
  d: path("M23.099 18.23a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k7k6u_23v {
  cx: 13.594px;
  cy: 9.923px;
  rx: 0.39px;
  ry: 0.197px;
}

.k8ix0jbxx {
  d: path("M8.901 18.23a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhk6elbnr {
  stop-color: var(--svg-color--a8686e, #A8686E);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lurh12x1h {
  stop-color: var(--svg-color--bd8176, #BD8176);
  stop-opacity: 0;
}

.m8qj67bxn {
  stop-color: var(--svg-color--bd8176, #BD8176);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgaf8je6n {
  d: path("M20.902 4.292a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.607a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.513-3.342 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.143-2.446a2.35 2.35 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.187.912-.187c.843 0 1.58.456 1.989 1.131c.307.51.79.88 1.352 1.073");
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mj9a-09qg {
  d: path("M18.767 16.057a10.3 10.3 0 0 0-2.337-.268h-.86q-1.194.002-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mnakovbzb {
  stop-color: var(--svg-color--e7baa7, #E7BAA7);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mzu8nv6ac {
  cx: 13.594px;
  cy: 9.923px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o4j6k38-e {
  d: path("M11.242 18.34c-.03-1.01.55-1.42.819-1.502l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.083-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.187.187 0 0 1 .174-.198c.297-.019.56-.044.747-.06a.19.19 0 0 0 .171-.192c-.01-.53-.02-1.532-.046-2.43");
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.o9yfg-bot {
  d: path("M20.909 12.185a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.02q.256-.547.345-1.18z");
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohy9e7bld {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.697 13.436h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045c-.39.204-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ow2sicbjy {
  fill: var(--svg-color--9c80b1, #9C80B1);
  d: path("M12.889 16.68c-.037.825.18 2.637 1.367 3.872c.255.265.715.18.863-.13l.73-1.434l.731 1.435c.149.308.609.394.863.129c1.186-1.235 1.404-3.047 1.368-3.872z");
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pknbobctv {
  d: path("M18.232 9.541a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q4e4b80yr {
  stop-color: var(--svg-color--c29281, #C29281);
}

.q8s6r6dsw {
  d: path("M14.679 10.33c0-.29-.235-.482-.298-.54l-.289.28l.178.36z");
}

.q9254d18m {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.608 8.08c-.257-.185-.897-.51-1.655-.382");
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qh2f6oblr {
  stop-color: var(--svg-color--e7baa7, #E7BAA7);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r5nd0wbje {
  stop-color: var(--svg-color--f4bcad, #F4BCAD);
  stop-opacity: 0;
}

.r66it6rvi {
  d: path("M14.41 20.277c-1.185-1.235-1.403-3.046-1.367-3.871h2.969l.035 2.223l-.773 1.52c-.148.308-.608.393-.863.128");
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rnafodbyg {
  d: path("M11.709 17.543c-.032-1.094.595-1.537.886-1.626l.668-.07v5.815c0 3.874 1.453 6.262 2.712 8.088c.063.09-.047.2-.138.138c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.66-.05-2.632");
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.smrxvvbzr {
  cx: 16.004px;
  cy: 25.575px;
  r: 0.5px;
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t7vx_s46x {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.475l1.813 1.251l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tnrknebzc {
  d: path("M13.863 9.541a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.uazsvlbfo {
  fill: var(--svg-color--000, #000);
  d: path("M17.72 10.434a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.ucpll26jf {
  d: path("m15.63 10.034l-.531 1.838c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uy8ok031y {
  cx: 15.731px;
  cy: 22.7px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vg7jlbcfm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.166 9.73c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vosoddbqj {
  d: path("M16.047 13.831c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.vut4jab5a {
  stop-color: var(--svg-color--b3758b, #B3758B);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w3jr8iqjv {
  stop-color: var(--svg-color--d8a29c, #D8A29C);
  stop-opacity: 0;
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wtm3bmtop {
  d: path("m15.665 10.22l-.531 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.wupw8ebgu {
  stop-color: var(--svg-color--af6a76, #AF6A76);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.wzyqdc7qh {
  d: path("M19.027 10.317a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x2gp7fbxb {
  stop-color: var(--svg-color--c99294, #C99294);
}

.x3n8sshto {
  d: path("M17.598 20.277c1.186-1.235 1.404-3.046 1.367-3.871h-2.968l-.036 2.223l.774 1.52c.148.308.608.393.863.128");
}

.x5prydbjk {
  cx: 16.012px;
  cy: 18.695px;
  r: 0.809px;
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yf575zhfr {
  d: path("M18.166 9.73c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yuf1bh9ca {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.78 7.955a1.85 1.85 0 0 0-.687-.412c-.305-.095-.686-.121-1.213-.057a.277.277 0 1 0 .068.551c.48-.059.775-.028.978.036c.198.062.333.163.49.3a.277.277 0 1 0 .364-.418");
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zipbdebnb {
  d: path("m17.892 17.475l-1.813 1.251l1.795 1.258a.246.246 0 0 0 .388-.187c.041-.79.041-1.569.008-2.143a.239.239 0 0 0-.378-.18");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zxzw1vbws {
  stop-color: var(--svg-color--bb7e83, #BB7E83);
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
