<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iGKrojZ)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#iZS399G)"><path class="snq5xhi6c"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#ioRy9VP)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#ih4xptb)" class="b1yazzwzl"/><path fill="url(#iN28qhb)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#irr73pd)"><path fill="url(#iiLGrnb)" class="ga-j-qbpm"/><path fill="url(#irBCE5b)" class="ga-j-qbpm"/><path fill="url(#iOuH9yc)" class="ga-j-qbpm"/></g><g filter="url(#i6t5YQc)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#iA0XN4g)" class="qexsyge6i"/><path fill="url(#is6z78C)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iwUiLey)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#icnamlb)"><path fill="url(#iTF2f9h)" class="dc-w_nb2z"/><path fill="url(#iDFUiOc)" class="dc-w_nb2z"/></g><g filter="url(#iUq0LLc)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#iKYB7Mb)"><path fill="url(#if2UIRn)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="stz6elb6u"/><path fill="url(#iCqAaCc)" class="eikeckbha"/><path fill="url(#iTEnVmd)" class="eikeckbha"/><path clip-rule="evenodd" class="qc5t8db-b"/><path fill="url(#i6NSaLc)" clip-rule="evenodd" class="x99s9tbej"/><path clip-rule="evenodd" class="x5036tbci"/><path fill="url(#iegrDeg)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="h8mf77buf"/><path fill="url(#iI5xoGs)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="n89_5nb9r"/><path fill="url(#iiMj71d)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#i0vUcqd)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#iZIvLpc)"><path fill="url(#i40rhfb)" class="p3ru7q3ze"/><path fill="url(#iBXH0lc)" class="p3ru7q3ze"/></g><path fill="url(#iPJ2hNc)" class="p3ru7q3ze"/><path fill="url(#iGUHBdd)" clip-rule="evenodd" class="y_4pajl7d"/><path fill="url(#iKek1Sd)" class="pfe1e3bxx"/><path fill="url(#ic1K2qU)" class="b1leyur1k"/><g filter="url(#iCYiYZd)"><path fill="url(#iQp4pkb)" class="jukc9ab2p"/><path fill="url(#iyrcCkx)" class="jukc9ab2p"/></g><path fill="url(#i1sqube)" class="jukc9ab2p"/><path fill="url(#iLG1rId)" class="jukc9ab2p"/><path fill="url(#iu7etId)" class="jukc9ab2p"/><path fill="url(#izKMIgx)" class="jukc9ab2p"/><path fill="url(#i3UaqkH)" class="jukc9ab2p"/><path fill="url(#iuNzLUd)" class="jukc9ab2p"/><path fill="url(#il5sX4w)" class="jukc9ab2p"/><path fill="url(#i0PLWFd)" class="jukc9ab2p"/><g filter="url(#iuHjItb)"><path class="oqxc6tnwn"/></g><g filter="url(#iQ7Qatb)"><path class="nqibcfbme"/><path fill="url(#ivDJOfd)" class="z59g3mb7k"/><path fill="url(#iSYWnWd)" class="z59g3mb7k"/><path fill="url(#i1nVsqb)" class="z59g3mb7k"/><path fill="url(#iVujh8d)" class="z59g3mb7k"/><path fill="url(#iL5M5Vb)" class="z59g3mb7k"/></g><g filter="url(#ithG1yc)"><path stroke="url(#iDN9IHT)" class="l4ngy4bui"/></g><path fill="url(#iNz1Pld)" class="le5u_zbkc"/><g filter="url(#iyM8UXd)"><path fill="url(#ilSk6sc)" class="j0lqffb7b"/></g><path fill="url(#iXuZ8He)" class="j0lqffb7b"/><path fill="url(#imCEaLe)" class="j0lqffb7b"/><path fill="url(#idc3kzd)" class="j0lqffb7b"/><g filter="url(#i8TliHc)"><path class="fkg8f4b2l"/></g><g filter="url(#ixel3th)"><path class="wrf38zb6e"/></g><g filter="url(#iPP5uPd)"><path class="ep76nybzz"/><path fill="url(#ihea9FT)" class="qje928kae"/><path fill="url(#iR1B9jb)" class="qje928kae"/></g><g filter="url(#iapQqSc)"><path class="l8ex01b1r"/><path fill="url(#iFH1ljc)" class="bxkb6ebdk"/><path fill="url(#i1ecsXb)" class="bxkb6ebdk"/><path fill="url(#iTDIgsc)" class="bxkb6ebdk"/></g><path class="k53nzx_zw"/><path fill="url(#iqD586E)" class="ypvlk6o_x"/><path class="sljtuacoa"/><g filter="url(#irszFad)"><path class="ayw4iubmm"/><path fill="url(#i4SFxCR)" class="tye7z2bwh"/></g><g filter="url(#i47n1Hd)"><path fill="url(#ijmrkci)" class="s7yaegr1t"/></g><path class="wtlevybbz"/><path fill="url(#i1D2gCv)" class="datd5qofy"/><path class="r2g7d-bcs"/><g filter="url(#iGnEWFe)"><path fill="url(#ivTuW1c)" class="m5muxpb2r"/></g><g filter="url(#iKJY5vc)"><ellipse transform="rotate(-27.914 11.752 5.656)" class="f9uy_hc2j"/><ellipse fill="url(#iW0Z87d)" transform="rotate(-27.914 11.752 5.656)" class="lcweve5cb"/></g><path fill="url(#iEBJxMd)" class="uvtkghs4l"/><path fill="url(#iOVb8MK)" class="uvtkghs4l"/><path fill="url(#iPeBjhd)" class="uvtkghs4l"/><path fill="url(#i0uNAld)" class="uvtkghs4l"/><path fill="url(#iyWooye)" class="kjpn7enys"/><path fill="url(#iOFtBrc)" class="kjpn7enys"/><g filter="url(#ilyv1xc)"><path fill="url(#i0MS4Vc)" class="m6-ttdbuq"/></g><g filter="url(#iSd7uke)"><path fill="url(#iUP2LLc)" class="j3n-h6b0j"/></g><g filter="url(#ihB3Dcm)"><path class="o72yxpb3j"/></g><path fill="url(#iUDE0ye)" class="dmwymqbmp"/><path fill="url(#ipkOA9c)" class="dmwymqbmp"/><path fill="url(#iy9n8Je)" class="dmwymqbmp"/><path fill="url(#isLzyyb)" class="dmwymqbmp"/><g filter="url(#i5uwSvc)"><path class="rudj2xgsn"/></g><g filter="url(#imNA7Id)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><defs><radialGradient id="iGKrojZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="cu-ecjbbc"/><stop offset="1" class="qb2q8bclu"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="ih4xptb" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="illubsb_v"/><stop offset="1" class="guxv2rb-g"/></radialGradient><radialGradient id="iN28qhb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="xs_h82bcz"/><stop offset="1" class="q7m_lo14i"/></radialGradient><radialGradient id="iiLGrnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="gr7jnieaq"/><stop offset="1" class="fni059bsf"/></radialGradient><radialGradient id="irBCE5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="r24pfmh2j"/><stop offset="1" class="jat2c8bpf"/></radialGradient><radialGradient id="iOuH9yc" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="yzedoqb0u"/><stop offset="1" class="f4147fa0n"/></radialGradient><radialGradient id="iA0XN4g" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="akiqkcbyd"/><stop offset="1" class="pydwqlfbr"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iTF2f9h" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="l277r0b8m"/><stop offset="1" class="m1km_jo3a"/></radialGradient><radialGradient id="if2UIRn" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="diezlkbrv"/><stop offset="1" class="qrb0sjbdn"/></radialGradient><radialGradient id="iCqAaCc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="mf5e09ark"/><stop offset="1" class="kqsf2kvhx"/></radialGradient><radialGradient id="iTEnVmd" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="lakgv5bqc"/><stop offset=".945" class="p3cy4lbfc"/></radialGradient><radialGradient id="i6NSaLc" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iegrDeg" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iI5xoGs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="iiMj71d" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="qpbv0c39t"/><stop offset="1" class="xjnuavuoc"/></radialGradient><radialGradient id="i0vUcqd" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="nm4xmabvr"/><stop offset="1" class="b4mlr_y9s"/></radialGradient><radialGradient id="i40rhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.479)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="j--7hbfuf"/><stop offset=".81" class="zozrgybxd"/></radialGradient><radialGradient id="iBXH0lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8437 -6.87502 1.8572 -.49805 18.024 16.393)" gradientUnits="userSpaceOnUse"><stop class="wsjf7pm3j"/><stop offset="1" class="u1162e6xa"/></radialGradient><radialGradient id="iPJ2hNc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.271 8.996)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="x0hdn9b5y"/><stop offset="1" class="eziwjdbdq"/></radialGradient><radialGradient id="iGUHBdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="wloocxb2w"/><stop offset="1" class="g8dpdlbxs"/></radialGradient><radialGradient id="iKek1Sd" cx="0" cy="0" r="1" gradientTransform="matrix(.33868 .91346 -1.08513 .40233 15.012 6.539)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="ic1K2qU" cx="0" cy="0" r="1" gradientTransform="matrix(.66783 .20989 -.64752 2.06028 10.123 6.76)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iQp4pkb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12815 0 0 -3.76468 14.132 6.113)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="iyrcCkx" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 5.891 5.867)scale(1.52384 1.25805)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iLG1rId" cx="0" cy="0" r="1" gradientTransform="matrix(-.46239 5.61933 -4.65347 -.38291 13.577 3.438)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="iu7etId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51941 .64278 0 13.969 5.52)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="izKMIgx" cx="0" cy="0" r="1" gradientTransform="matrix(.00178 -.49496 .53863 .00193 11.822 5.54)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="i3UaqkH" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 7.104 3.507)scale(3.8505 9.8361)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iuNzLUd" cx="0" cy="0" r="1" gradientTransform="matrix(1.53144 -1.31916 .38966 .45236 9.79 4.877)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="il5sX4w" cx="0" cy="0" r="1" gradientTransform="matrix(-.10614 1.12962 -.45156 -.04243 15.37 4.794)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i0PLWFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39423 -.75681 0 11.86 5.89)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iSYWnWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11041 -.347 0 13.073 6.729)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iVujh8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.76534 .33927 -.54524 -1.22999 13.126 6.471)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iNz1Pld" cx="0" cy="0" r="1" gradientTransform="matrix(.98694 -.4852 1.95212 3.97071 12.64 7.752)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iXuZ8He" cx="0" cy="0" r="1" gradientTransform="matrix(1.23962 -3.23386 4.58882 1.759 10.28 5.243)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="imCEaLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.68721 -2.96436 4.20639 -.97514 15.428 5.27)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="idc3kzd" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 8.214 -2.862)scale(1.19338 1.4088)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="ihea9FT" cx="0" cy="0" r="1" gradientTransform="matrix(-.9956 0 0 -.3695 12.977 2.86)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iR1B9jb" cx="0" cy="0" r="1" gradientTransform="matrix(1.45564 -2.30473 2.5534 1.6127 10.406 4.643)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iFH1ljc" cx="0" cy="0" r="1" gradientTransform="matrix(1.58997 -1.28006 1.98382 2.46412 13.73 4.017)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="i1ecsXb" cx="0" cy="0" r="1" gradientTransform="matrix(1.33834 -1.19783 2.19291 2.45014 14.053 4.585)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iTDIgsc" cx="0" cy="0" r="1" gradientTransform="matrix(1.45883 .32753 -.13713 .61079 13.663 3.762)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iqD586E" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36697 -.5837 0 13.849 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i4SFxCR" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 8.278 -.498)scale(.17111 .23556)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1D2gCv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36699 -.58374 0 11.875 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iW0Z87d" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22348 .26863 -.0042 11.745 5.798)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOVb8MK" cx="0" cy="0" r="1" gradientTransform="matrix(.2843 1.01466 -.96807 .27125 14.95 5.705)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iPeBjhd" cx="0" cy="0" r="1" gradientTransform="matrix(.35633 -.489 .40988 .29867 15.114 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="i0uNAld" cx="0" cy="0" r="1" gradientTransform="matrix(.2655 -.70128 .937 .35475 15.165 6.03)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iOFtBrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.75005 0 0 -.83754 10.639 5.995)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="i0MS4Vc" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 5.064 3.451)scale(.4206 .43124)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iUDE0ye" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.443 3.733)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="isLzyyb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.271 3.202)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><filter id="iZS399G" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.341176 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="ioRy9VP" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="irr73pd" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.32549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="i6t5YQc" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="iwUiLey" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="icnamlb" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.231373 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="iUq0LLc" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="iKYB7Mb" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.419608 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23229" result="effect2_innerShadow_3987_23229"/></filter><filter id="iZIvLpc" width="7.636" height="9.986" x="11.582" y="7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.215686 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="iCYiYZd" width="5.623" height="5.682" x="10.572" y="3.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23229" result="effect2_innerShadow_3987_23229"/></filter><filter id="iuHjItb" width="2.79" height="3.312" x="11.403" y="4.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".5"/></filter><filter id="iQ7Qatb" width=".949" height="1.412" x="12.387" y="5.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".025"/></filter><filter id="ithG1yc" width="1.756" height=".785" x="11.984" y="7.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".05"/></filter><filter id="iyM8UXd" width="5.822" height="4.054" x="9.951" y="1.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23229" result="effect2_innerShadow_3987_23229"/></filter><filter id="i8TliHc" width="1.113" height=".648" x="13.581" y="4.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="ixel3th" width="1.113" height=".641" x="11.203" y="4.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><filter id="iPP5uPd" width="2.952" height="2.665" x="10.125" y="2.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/><feGaussianBlur result="effect2_foregroundBlur_3987_23229" stdDeviation=".05"/></filter><filter id="iapQqSc" width="3.727" height="2.98" x="12.827" y="2.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/><feGaussianBlur result="effect2_foregroundBlur_3987_23229" stdDeviation=".075"/></filter><filter id="irszFad" width=".465" height=".424" x="13.462" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".05"/></filter><filter id="i47n1Hd" width=".622" height=".632" x="13.787" y="5.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".1"/></filter><filter id="iGnEWFe" width=".665" height=".69" x="11.778" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".1"/></filter><filter id="iKJY5vc" width=".523" height=".428" x="11.491" y="5.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".05"/></filter><filter id="ilyv1xc" width=".875" height="1.35" x="9.975" y="5.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".125"/></filter><filter id="iSd7uke" width="1.365" height="1.795" x="14.646" y="5.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".25"/></filter><filter id="ihB3Dcm" width="3.249" height="2.199" x="12.911" y="2.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".375"/></filter><filter id="i5uwSvc" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23229" stdDeviation=".25"/></filter><filter id="imNA7Id" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23229"/></filter><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="is6z78C" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="va2m8brjv"/><stop offset="1" class="f3-q9vb4v"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iDFUiOc" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="g7p406nqv"/><stop offset="1" class="r52adsb8o"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="i1sqube" x1="15.195" x2="14.051" y1="6.876" y2="6.876" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ivDJOfd" x1="13.241" x2="12.862" y1="6.419" y2="6.434" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i1nVsqb" x1="12.862" x2="12.862" y1="6.934" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iL5M5Vb" x1="12.862" x2="12.862" y1="5.71" y2="5.958" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iDN9IHT" x1="12.318" x2="12.462" y1="7.644" y2="7.267" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="ilSk6sc" x1="15.961" x2="10.709" y1="3.552" y2="3.552" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="ijmrkci" x1="14.201" x2="14.059" y1="5.723" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivTuW1c" x1="12.211" x2="12.069" y1="5.723" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEBJxMd" x1="15.773" x2="15.227" y1="5.735" y2="6.72" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iyWooye" x1="10.216" x2="10.876" y1="6.054" y2="5.996" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iUP2LLc" x1="15.329" x2="15.329" y1="5.596" y2="6.391" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="ipkOA9c" x1="9.826" x2="13.537" y1="3.92" y2="3.92" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iy9n8Je" x1="13.599" x2="13.599" y1="4.264" y2="4.147" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bouncing-ball-medium" /></template>
<style>
.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.akiqkcbyd {
  stop-color: var(--svg-color--af8173, #AF8173);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.ayw4iubmm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.82 5.568c.029.039-.031.086-.1.137c-.068.051-.119.087-.147.049c-.03-.039.003-.112.071-.163c.069-.05.147-.061.176-.023");
}

.b1leyur1k {
  d: path("M10.663 6.679a.74.74 0 0 1-.409-.14v.421c0 .404.24.764.607.913a1.9 1.9 0 0 1-.157-.533z");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b1yazzwzl {
  d: path("m11 20.604l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.646 1.008-1.82");
}

.b1ysgbbus {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.469px;
  rx: 0.33px;
}

.b4mlr_y9s {
  stop-color: var(--svg-color--b08971, #B08971);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bxkb6ebdk {
  d: path("m15.22 5.05l-.013-.285a.664.664 0 0 0-.636-.644h-.633c-.402 0-.769-.22-.961-.57c0 0 .326-.94.866-.819c.395.09.818.229 1.141.44c.79.515.651 1.442.236 1.879");
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.datd5qofy {
  d: path("M11.874 5.483a.404.404 0 0 0-.389.51h.78a.406.406 0 0 0-.39-.51");
}

.dc-w_nb2z {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.255");
}

.diezlkbrv {
  stop-color: var(--svg-color--9b7264, #9B7264);
}

.dmwymqbmp {
  d: path("M9.826 3.302a.1.1 0 0 1 .1-.1h5.925a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.926a.1.1 0 0 1-.1-.1z");
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.ep76nybzz {
  fill: var(--svg-color--533634, #533634);
  d: path("m12.967 3.573l-.03-.062a.3.3 0 0 0-.278-.189h-.576a1.52 1.52 0 0 0-1.511 1.528v.125c-.154-.117-.347-.364-.347-.763c0-.485.353-.73.579-.887c.063-.044.117-.08.15-.114l.044-.048c.159-.167.44-.466.932-.597q.12-.03.24-.048c.467-.07.807.349.807.822v.227z");
}

.eziwjdbdq {
  stop-color: var(--svg-color--ff8524, #FF8524);
  stop-opacity: 0;
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f3-q9vb4v {
  stop-color: var(--svg-color--ad7c77, #AD7C77);
  stop-opacity: 0;
}

.f4147fa0n {
  stop-color: var(--svg-color--ff7447, #FF7447);
  stop-opacity: 0;
}

.f9uy_hc2j {
  cx: 11.752px;
  cy: 5.656px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fkg8f4b2l {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M14.55 4.765a.8.8 0 0 0-.31-.186c-.138-.043-.31-.055-.55-.025a.125.125 0 1 0 .031.249c.218-.027.351-.013.443.016c.09.028.15.074.222.136a.125.125 0 0 0 .164-.19");
}

.fni059bsf {
  stop-color: var(--svg-color--ff6b3f, #FF6B3F);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.g7p406nqv {
  stop-color: var(--svg-color--d0431b, #D0431B);
}

.g8dpdlbxs {
  stop-color: var(--svg-color--a7836a, #A7836A);
  stop-opacity: 0;
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.ga-j-qbpm {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.06c.12-.109.433-.272.71-.06c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gr7jnieaq {
  stop-color: var(--svg-color--ff6b38, #FF6B38);
}

.guxv2rb-g {
  stop-color: var(--svg-color--8d6353, #8D6353);
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

.h8mf77buf {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.illubsb_v {
  stop-color: var(--svg-color--bd8b7f, #BD8B7F);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j--7hbfuf {
  stop-color: var(--svg-color--ff9128, #FF9128);
}

.j0lqffb7b {
  d: path("M15.058 3.109a1.072 1.072 0 0 1 .525 1.618a.7.7 0 0 0-.122.395v.538a.8.8 0 0 0-.302-.122l.036-.726a.656.656 0 0 0-.624-.648h-.633c-.432 0-.823-.255-1-.653a.3.3 0 0 0-.279-.189h-.576a1.52 1.52 0 0 0-1.511 1.529l.014.695a.8.8 0 0 0-.326.12v-.544a.7.7 0 0 0-.122-.395a1.08 1.08 0 0 1-.065-1.106a1.06 1.06 0 0 1 .588-.51c.259-.092.48-.267.626-.502a1.05 1.05 0 0 1 1.307-.413a.67.67 0 0 0 .54 0a1.05 1.05 0 0 1 1.312.427c.14.23.358.398.612.486");
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j3n-h6b0j {
  d: path("M15.146 6.39q.023-.397.043-.794c.181.024.322.192.322.396c0 .219-.163.397-.365.399");
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.jat2c8bpf {
  stop-color: var(--svg-color--ff7049, #FF7049);
  stop-opacity: 0;
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jukc9ab2p {
  d: path("M10.68 7.364a1.77 1.77 0 0 0 1.757 1.54h.854c.89 0 1.64-.657 1.757-1.54c.053-.852.107-1.7.147-2.552a.656.656 0 0 0-.624-.648h-.633c-.432 0-.823-.255-1-.653a.3.3 0 0 0-.279-.189h-.576a1.52 1.52 0 0 0-1.511 1.528c0 .842.053 1.67.108 2.514");
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k53nzx_zw {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.944 5.36c.295 0 .544.204.612.48a.124.124 0 0 1-.12.153h-1.01a.104.104 0 0 1-.103-.123a.63.63 0 0 1 .62-.51");
}

.kjpn7enys {
  d: path("M10.58 5.27a.728.728 0 0 0 .058 1.45q-.043-.724-.057-1.45");
}

.kqsf2kvhx {
  stop-color: var(--svg-color--996d5c, #996D5C);
  stop-opacity: 0;
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l277r0b8m {
  stop-color: var(--svg-color--ff6836, #FF6836);
}

.l4ngy4bui {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.862 7.423a1.36 1.36 0 0 1-.627-.148c-.062-.032-.128.038-.09.094c.152.23.416.383.717.383c.3 0 .565-.153.716-.383c.04-.058-.027-.126-.09-.094a1.35 1.35 0 0 1-.626.148Z");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l8ex01b1r {
  fill: var(--svg-color--563936, #563936);
  d: path("m15.22 5.05l-.013-.285a.664.664 0 0 0-.636-.644h-.633c-.402 0-.769-.22-.961-.57c0 0 .326-.94.866-.819c.395.09.818.229 1.141.44c.79.515.651 1.442.236 1.879");
}

.lakgv5bqc {
  stop-color: var(--svg-color--b38970, #B38970);
  stop-opacity: 0;
}

.lcweve5cb {
  cx: 11.752px;
  cy: 5.656px;
  rx: 0.176px;
  ry: 0.089px;
}

.le5u_zbkc {
  d: path("M12.862 7.423a1.36 1.36 0 0 1-.627-.148c-.062-.032-.128.038-.09.094c.152.23.416.383.717.383c.3 0 .565-.153.716-.383c.04-.058-.027-.126-.09-.094a1.35 1.35 0 0 1-.626.148");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m1km_jo3a {
  stop-color: var(--svg-color--ff5a36, #FF5A36);
}

.m5muxpb2r {
  d: path("M12.243 5.84c0-.131-.106-.218-.135-.244l-.13.126l.08.163z");
}

.m6-ttdbuq {
  d: path("M10.562 5.571a.432.432 0 0 0 .038.85a35 35 0 0 1-.038-.85");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mf5e09ark {
  stop-color: var(--svg-color--7e4944, #7E4944);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n89_5nb9r {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.nm4xmabvr {
  stop-color: var(--svg-color--c09989, #C09989);
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.nqibcfbme {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m12.689 5.79l-.24.832c-.05.17.068.342.235.342h.356c.167 0 .284-.174.235-.342l-.24-.832c-.052-.184-.292-.184-.346 0");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o72yxpb3j {
  fill: var(--svg-color--725050, #725050);
  d: path("M14.852 3.575h-.967a.224.224 0 1 1 .036-.447c.25.04.584.096.807.151c.504.125.643.37.682.546a.7.7 0 0 0-.559-.25");
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of70meq1k {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.oqxc6tnwn {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m12.68 5.879l-.267.831c-.046.171.064.342.22.342h.33c.155 0 .265-.174.22-.342l-.224-.831c-.048-.185-.228-.185-.279 0");
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

.p3cy4lbfc {
  stop-color: var(--svg-color--b38970, #B38970);
}

.p3ru7q3ze {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pfe1e3bxx {
  d: path("M15.06 6.679a.74.74 0 0 0 .41-.14v.421a.98.98 0 0 1-.607.913q.116-.246.157-.533z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.pydwqlfbr {
  stop-color: var(--svg-color--9c7460, #9C7460);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q7m_lo14i {
  stop-color: var(--svg-color--925971, #925971);
}

.qb2q8bclu {
  stop-color: var(--svg-color--8a494a, #8A494A);
}

.qc5t8db-b {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qje928kae {
  d: path("m12.967 3.573l-.03-.062a.3.3 0 0 0-.278-.189h-.576a1.52 1.52 0 0 0-1.511 1.528v.125c-.154-.117-.347-.364-.347-.763c0-.485.353-.73.579-.887c.063-.044.117-.08.15-.114l.044-.048c.159-.167.44-.466.932-.597q.12-.03.24-.048c.467-.07.807.349.807.822v.227z");
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qpbv0c39t {
  stop-color: var(--svg-color--9c5c64, #9C5C64);
}

.qrb0sjbdn {
  stop-color: var(--svg-color--8b6757, #8B6757);
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r24pfmh2j {
  stop-color: var(--svg-color--ff7049, #FF7049);
}

.r2g7d-bcs {
  fill: var(--svg-color--000, #000);
  d: path("M12.105 5.887a.23.23 0 0 0-.23-.231a.23.23 0 0 0-.206.337h.409a.23.23 0 0 0 .027-.106");
}

.r52adsb8o {
  stop-color: var(--svg-color--d0431b, #D0431B);
  stop-opacity: 0;
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rudj2xgsn {
  fill: var(--svg-color--c8a08c, #C8A08C);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.s7yaegr1t {
  d: path("M14.21 5.834a.4.4 0 0 0-.105-.21l-.118.13l.053.103z");
}

.sa73rem9k {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sepv3nkwr {
  d: path("M5.527 16.647c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sljtuacoa {
  fill: var(--svg-color--000, #000);
  d: path("M13.619 5.887a.23.23 0 0 1 .231-.231a.23.23 0 0 1 .206.337h-.41a.2.2 0 0 1-.027-.106");
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.snq5xhi6c {
  fill: var(--svg-color--b38c70, #B38C70);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.stz6elb6u {
  fill: var(--svg-color--caa18d, #CAA18D);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.tye7z2bwh {
  d: path("M13.82 5.568c.029.039-.031.086-.1.137c-.068.051-.119.087-.147.049c-.03-.039.003-.112.071-.163c.069-.05.147-.061.176-.023");
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.u1162e6xa {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.uvtkghs4l {
  d: path("M15.088 6.72q.046-.722.084-1.444a.728.728 0 0 1-.084 1.444");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.va2m8brjv {
  stop-color: var(--svg-color--9a6183, #9A6183);
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wloocxb2w {
  stop-color: var(--svg-color--a7836a, #A7836A);
}

.wrf38zb6e {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M11.32 4.716q.061-.038.173-.085c.148-.058.36-.108.613-.077a.125.125 0 1 1-.03.249a1 1 0 0 0-.662.15l-.008.006a.125.125 0 0 1-.154-.198z");
}

.wsjf7pm3j {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
}

.wtlevybbz {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.78 5.36a.63.63 0 0 0-.612.48c-.02.078.04.153.12.153h1.01a.104.104 0 0 0 .103-.123a.634.634 0 0 0-.62-.51");
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x0hdn9b5y {
  stop-color: var(--svg-color--ffa61d, #FFA61D);
}

.x5036tbci {
  fill: var(--svg-color--af8870, #AF8870);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xjnuavuoc {
  stop-color: var(--svg-color--9c5c64, #9C5C64);
  stop-opacity: 0;
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xs_h82bcz {
  stop-color: var(--svg-color--925971, #925971);
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

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.ypvlk6o_x {
  d: path("M13.85 5.483a.404.404 0 0 1 .389.51h-.78a.405.405 0 0 1 .39-.51");
}

.yzedoqb0u {
  stop-color: var(--svg-color--ff7447, #FF7447);
}

.z59g3mb7k {
  d: path("m12.689 5.79l-.24.832c-.05.17.068.342.235.342h.356c.167 0 .284-.174.235-.342l-.24-.832c-.052-.184-.292-.184-.346 0");
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zozrgybxd {
  stop-color: var(--svg-color--ed5722, #ED5722);
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
