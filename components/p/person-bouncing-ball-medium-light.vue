<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ioO1Xyd)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#iRmhXVd)"><path class="xxqudjj-y"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#iCcOrWc)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#i2gKk8d)" class="b1yazzwzl"/><path fill="url(#iIZMWQc)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="nxl2wtijb"/><path fill="url(#idv3syc)" class="nxl2wtijb"/><g filter="url(#iKsv1jw)"><path fill="url(#iiLGrnb)" class="ga-j-qbpm"/><path fill="url(#irBCE5b)" class="ga-j-qbpm"/><path fill="url(#iOuH9yc)" class="ga-j-qbpm"/></g><g filter="url(#iHBjH7b)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#iZc20Px)" class="qexsyge6i"/><path fill="url(#iej9nhc)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iXL0OBb)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#iYCnvld)"><path fill="url(#iTF2f9h)" class="dc-w_nb2z"/><path fill="url(#iDFUiOc)" class="dc-w_nb2z"/></g><g filter="url(#iom8Ndb)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#iQPfKGd)"><path fill="url(#iZtTfDK)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="vbvrfobce"/><path fill="url(#iQQbCsb)" class="eikeckbha"/><path fill="url(#iGf68cb)" class="eikeckbha"/><path clip-rule="evenodd" class="tvcoyjbyb"/><path fill="url(#io1fx8c)" clip-rule="evenodd" class="sip24gb4a"/><path clip-rule="evenodd" class="k_iut18hr"/><path fill="url(#izu3Vgb)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="dqw0fkb-l"/><path fill="url(#iJzj0vG)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="aygv8cbzz"/><path fill="url(#ihT2fJB)" clip-rule="evenodd" class="tc1alx-sf"/><path fill="url(#iDFK9rc)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#iAGCh7c)"><path fill="url(#i40rhfb)" class="p3ru7q3ze"/><path fill="url(#iBXH0lc)" class="p3ru7q3ze"/></g><path fill="url(#iPJ2hNc)" class="p3ru7q3ze"/><path fill="url(#iOz2tNb)" clip-rule="evenodd" class="y_4pajl7d"/><g filter="url(#iXZsbJd)"><path class="mj9q84mzn"/></g><g filter="url(#iJW7ByY)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><path fill="url(#iEpAFpd)" class="pfe1e3bxx"/><path fill="url(#iafOEib)" class="b1leyur1k"/><path fill="url(#iuqnrKx)" class="b1leyur1k"/><path fill="url(#iafOEib)" class="b1leyur1k"/><path fill="url(#iuqnrKx)" class="b1leyur1k"/><g filter="url(#iutFJEe)"><path fill="url(#i8NMHhc)" class="jukc9ab2p"/></g><path fill="url(#iIp5vbo)" class="jukc9ab2p"/><path fill="url(#iFsJjab)" class="jukc9ab2p"/><path fill="url(#iu1EHwc)" class="jukc9ab2p"/><path fill="url(#ileB2Rb)" class="jukc9ab2p"/><path fill="url(#iIj6l4c)" class="jukc9ab2p"/><path fill="url(#iR4rhqd)" class="jukc9ab2p"/><path fill="url(#iNggWwe)" class="jukc9ab2p"/><path fill="url(#ibYitqX)" class="jukc9ab2p"/><g filter="url(#iFGnS0c)"><path class="hzv8p_djr"/></g><g filter="url(#iJji0oe)"><path fill="url(#i7tuGsg)" class="gvqqg5djy"/><path fill="url(#i6VKPrb)" class="gvqqg5djy"/><path fill="url(#i6h4Zje)" class="gvqqg5djy"/><path fill="url(#i1LQolb)" class="gvqqg5djy"/></g><g filter="url(#ibhMZ8c)"><path stroke="url(#iHlJQ0b)" class="myhljebwm"/></g><path fill="url(#ijzbZPc)" class="le5u_zbkc"/><g filter="url(#iPbxEAy)"><path fill="url(#ikYClQc)" class="j0lqffb7b"/><path fill="url(#i5NLXSg)" class="j0lqffb7b"/><path fill="url(#i11uv6T)" class="j0lqffb7b"/><path fill="url(#iWMcWTd)" class="j0lqffb7b"/><path fill="url(#i6UDUpe)" class="j0lqffb7b"/></g><g filter="url(#ijTtt5d)"><path class="clacizeak"/></g><g filter="url(#iOGDpub)"><path class="vfcm6ebog"/></g><g filter="url(#i3l1SDl)"><path fill="url(#iazoVTc)" class="ebaacj6_i"/><path fill="url(#i2wNlVb)" class="ebaacj6_i"/></g><g filter="url(#inLG25b)"><path fill="url(#idO3y5d)" class="qe-n0bb5q"/><path fill="url(#iyxJced)" class="qe-n0bb5q"/><path fill="url(#iEPgaoc)" class="qe-n0bb5q"/><path fill="url(#iyCkcNe)" class="qe-n0bb5q"/><path fill="url(#i7tb2Vc)" class="qe-n0bb5q"/><path fill="url(#iwqcYcb)" class="qe-n0bb5q"/></g><path class="k53nzx_zw"/><path fill="url(#itSScJb)" class="ypvlk6o_x"/><path class="sljtuacoa"/><g filter="url(#ipSKWXU)"><path class="ayw4iubmm"/><path fill="url(#i4SFxCR)" class="tye7z2bwh"/></g><g filter="url(#iqzEJ8b)"><path fill="url(#ijmrkci)" class="s7yaegr1t"/></g><path class="bi865fbvn"/><path fill="url(#iryW3AB)" class="datd5qofy"/><path class="r2g7d-bcs"/><g filter="url(#iIkEgdc)"><path fill="url(#iCpwTed)" class="m5muxpb2r"/></g><g filter="url(#izIxNoe)"><ellipse transform="rotate(-27.914 11.752 5.656)" class="f9uy_hc2j"/><ellipse fill="url(#iW0Z87d)" transform="rotate(-27.914 11.752 5.656)" class="lcweve5cb"/></g><path fill="url(#iUSmhnb)" class="uvtkghs4l"/><path fill="url(#iFzy1Be)" class="uvtkghs4l"/><path fill="url(#iwQobgc)" class="uvtkghs4l"/><path fill="url(#iQuElTd)" class="jlsi1lmwv"/><path fill="url(#iTmTfsb)" class="jlsi1lmwv"/><g filter="url(#ik1uTod)"><path class="u01sscctk"/></g><g filter="url(#iVDc08E)"><path class="jnlns0b9v"/></g><path fill="url(#iHkxsld)" class="o3qnlo65u"/><path fill="url(#i6AW3Kc)" class="o3qnlo65u"/><path fill="url(#i16Hd7N)" class="o3qnlo65u"/><path fill="url(#iOChnTd)" class="o3qnlo65u"/><defs><radialGradient id="ioO1Xyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="jove3dblx"/><stop offset="1" class="azrq8dbhb"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="i2gKk8d" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="caco6ntri"/><stop offset="1" class="dgkitw09n"/></radialGradient><radialGradient id="iIZMWQc" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="t469b3jak"/><stop offset="1" class="qvoq5opiz"/></radialGradient><radialGradient id="iiLGrnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="gr7jnieaq"/><stop offset="1" class="fni059bsf"/></radialGradient><radialGradient id="irBCE5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="r24pfmh2j"/><stop offset="1" class="jat2c8bpf"/></radialGradient><radialGradient id="iOuH9yc" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="yzedoqb0u"/><stop offset="1" class="f4147fa0n"/></radialGradient><radialGradient id="iZc20Px" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="gckwtd8pq"/><stop offset="1" class="sg_-x3gmw"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iTF2f9h" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="l277r0b8m"/><stop offset="1" class="m1km_jo3a"/></radialGradient><radialGradient id="iZtTfDK" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="idtxb7bhf"/><stop offset="1" class="fl8n3u57c"/></radialGradient><radialGradient id="iQQbCsb" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="krme1767b"/><stop offset="1" class="nkhjpg89n"/></radialGradient><radialGradient id="iGf68cb" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="zxq4xrt3q"/><stop offset="1" class="suc174tfe"/></radialGradient><radialGradient id="io1fx8c" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="izu3Vgb" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="iJzj0vG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="ihT2fJB" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="bq_62abtc"/><stop offset="1" class="uwcvcu_5g"/></radialGradient><radialGradient id="iDFK9rc" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="tjlv9x_9r"/><stop offset="1" class="z13dp2ohj"/></radialGradient><radialGradient id="i40rhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.479)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="j--7hbfuf"/><stop offset=".81" class="zozrgybxd"/></radialGradient><radialGradient id="iBXH0lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8437 -6.87502 1.8572 -.49805 18.024 16.393)" gradientUnits="userSpaceOnUse"><stop class="wsjf7pm3j"/><stop offset="1" class="u1162e6xa"/></radialGradient><radialGradient id="iPJ2hNc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.271 8.996)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="x0hdn9b5y"/><stop offset="1" class="eziwjdbdq"/></radialGradient><radialGradient id="iOz2tNb" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="k1ssgpxxp"/><stop offset="1" class="dcaablbea"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="iEpAFpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.27562 1.59869 -1.89911 -.3274 15.331 6.464)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iafOEib" cx="0" cy="0" r="1" gradientTransform="matrix(.5762 1.21302 -.55137 .2619 10.352 6.592)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iuqnrKx" cx="0" cy="0" r="1" gradientTransform="matrix(.0811 .5399 -.4736 .07114 10.715 6.5)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="i8NMHhc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36463 0 0 -4.18301 14.132 6.113)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iFsJjab" cx="0" cy="0" r="1" gradientTransform="matrix(-.51699 5.86335 -4.85555 -.42813 13.577 3.438)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="iu1EHwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60651 .75056 0 13.969 5.606)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ileB2Rb" cx="0" cy="0" r="1" gradientTransform="matrix(-.02626 -.49908 .54312 -.02858 11.85 5.545)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iIj6l4c" cx="0" cy="0" r="1" gradientTransform="matrix(.54586 0 0 2.77448 10.654 6.287)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iR4rhqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.1827 -1.65274 .37435 .26788 10.215 4.756)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iNggWwe" cx="0" cy="0" r="1" gradientTransform="rotate(-103.259 9.545 -1.087)scale(4.75992 5.2432)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="ibYitqX" cx="0" cy="0" r="1" gradientTransform="matrix(.92493 .326 -.19557 .55485 13.748 3.68)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="iHlJQ0b" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 12.663 -6.74)scale(.32119 .93465)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="ijzbZPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.326 1.31158 0 12.862 7.714)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i5NLXSg" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6431 2.91125 0 10.497 5.398)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="i11uv6T" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6431 2.91125 0 15.06 5.398)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iWMcWTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47078 -.56102 .29878 -.7833 14.72 2.559)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="i6UDUpe" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 4.584 12.045)scale(.78276 1.81249)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iazoVTc" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 6.27 2.38)scale(1.83058 .50949)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i2wNlVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.45564 -2.30473 2.5534 1.6127 10.406 4.644)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="idO3y5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.53144 .36222 -.20258 .85649 14.5 3.016)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iyxJced" cx="0" cy="0" r="1" gradientTransform="matrix(-.97184 -1.67523 .93427 -.542 15.182 5.099)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iEPgaoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59134 -.99613 .71348 -.42355 14.9 4.963)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iyCkcNe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1704 .5207 -.5629 -2.34628 15.03 2.963)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="i7tb2Vc" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 6.137 6.79)scale(.1815 .82978)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iwqcYcb" cx="0" cy="0" r="1" gradientTransform="matrix(-.90217 1.69824 -4.37928 -2.32644 14.422 2.535)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="itSScJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36697 -.5837 0 13.849 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4SFxCR" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 8.278 -.498)scale(.17111 .23556)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iryW3AB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36699 -.58374 0 11.875 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iW0Z87d" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22348 .26863 -.0042 11.745 5.798)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFzy1Be" cx="0" cy="0" r="1" gradientTransform="matrix(.2843 1.01466 -.96807 .27125 14.95 5.705)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="iwQobgc" cx="0" cy="0" r="1" gradientTransform="matrix(.35633 -.489 .40988 .29867 15.114 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iTmTfsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75763 -.1108 .10892 -.74482 10.639 5.996)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="iHkxsld" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.438 3.733)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="iOChnTd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.266 3.202)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><filter id="iRmhXVd" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.447059 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iCcOrWc" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iKsv1jw" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.32549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iHBjH7b" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iXL0OBb" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iYCnvld" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.231373 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iom8Ndb" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iQPfKGd" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.466667 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.364706 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23232" result="effect2_innerShadow_3987_23232"/></filter><filter id="iAGCh7c" width="7.636" height="9.986" x="11.582" y="7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.215686 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iXZsbJd" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".25"/></filter><filter id="iJW7ByY" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iutFJEe" width="5.373" height="5.782" x="10.572" y="3.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23232" result="effect2_innerShadow_3987_23232"/></filter><filter id="iFGnS0c" width="2.794" height="3.277" x="11.344" y="4.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".5"/></filter><filter id="iJji0oe" width="1.049" height="1.512" x="12.338" y="5.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".05"/></filter><filter id="ibhMZ8c" width="1.956" height=".985" x="11.884" y="7.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".05"/></filter><filter id="iPbxEAy" width="5.822" height="4.054" x="9.951" y="1.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23232" result="effect2_innerShadow_3987_23232"/></filter><filter id="ijTtt5d" width="1.113" height=".648" x="13.581" y="4.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="iOGDpub" width="1.113" height=".641" x="11.203" y="4.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23232"/></filter><filter id="i3l1SDl" width="2.952" height="2.665" x="10.125" y="2.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".05"/></filter><filter id="inLG25b" width="2.877" height="2.63" x="12.827" y="2.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".075"/></filter><filter id="ipSKWXU" width=".465" height=".424" x="13.462" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".05"/></filter><filter id="iqzEJ8b" width=".622" height=".632" x="13.787" y="5.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".1"/></filter><filter id="iIkEgdc" width=".665" height=".69" x="11.778" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".1"/></filter><filter id="izIxNoe" width=".523" height=".428" x="11.491" y="5.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".05"/></filter><filter id="ik1uTod" width=".875" height="1.35" x="9.996" y="5.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".125"/></filter><filter id="iVDc08E" width=".928" height="1.361" x="14.856" y="5.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23232" stdDeviation=".125"/></filter><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iej9nhc" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="s6dne5bmb"/><stop offset="1" class="mur73_bqp"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iDFUiOc" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="g7p406nqv"/><stop offset="1" class="r52adsb8o"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iIp5vbo" x1="15.195" x2="13.226" y1="6.876" y2="6.876" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="i7tuGsg" x1="12.862" x2="13.249" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="i6VKPrb" x1="12.377" x2="12.863" y1="6.418" y2="6.445" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="i6h4Zje" x1="12.862" x2="12.862" y1="6.669" y2="7.054" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="i1LQolb" x1="12.862" x2="12.862" y1="5.652" y2="5.842" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ikYClQc" x1="15.288" x2="10.709" y1="3.552" y2="3.552" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="ijmrkci" x1="14.201" x2="14.059" y1="5.723" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCpwTed" x1="12.212" x2="12.07" y1="5.723" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUSmhnb" x1="15.773" x2="15.227" y1="5.735" y2="6.72" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iQuElTd" x1="10.216" x2="10.876" y1="6.054" y2="5.996" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="i6AW3Kc" x1="9.821" x2="13.532" y1="3.92" y2="3.92" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="i16Hd7N" x1="13.594" x2="13.594" y1="4.264" y2="4.147" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bouncing-ball-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.aygv8cbzz {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.083-1.136.337-1.209.514a.415.415 0 0 1-.768-.314c.211-.516.904-1.148 2.065-1.025a.415.415 0 1 1-.088.825");
}

.ayw4iubmm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.82 5.568c.029.039-.031.086-.1.137c-.068.051-.119.087-.147.049c-.03-.039.003-.112.071-.163c.069-.05.147-.061.176-.023");
}

.azrq8dbhb {
  stop-color: var(--svg-color--b86660, #B86660);
}

.b1leyur1k {
  d: path("M10.663 6.679a.74.74 0 0 1-.409-.14v.421c0 .404.24.764.607.913a1.9 1.9 0 0 1-.157-.533z");
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

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bi865fbvn {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.78 5.36a.63.63 0 0 0-.612.48c-.02.078.04.153.121.153h1.01a.104.104 0 0 0 .102-.123a.634.634 0 0 0-.62-.51");
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bq_62abtc {
  stop-color: var(--svg-color--c9786e, #C9786E);
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.caco6ntri {
  stop-color: var(--svg-color--edb29a, #EDB29A);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clacizeak {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M14.55 4.765a.8.8 0 0 0-.31-.186c-.138-.043-.31-.055-.549-.025a.125.125 0 0 0 .03.249c.218-.027.352-.013.443.016c.09.028.15.074.222.136a.125.125 0 1 0 .165-.19");
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.datd5qofy {
  d: path("M11.874 5.483a.404.404 0 0 0-.389.51h.78a.406.406 0 0 0-.39-.51");
}

.dc-w_nb2z {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.255");
}

.dcaablbea {
  stop-color: var(--svg-color--ddac86, #DDAC86);
  stop-opacity: 0;
}

.dgkitw09n {
  stop-color: var(--svg-color--c2886c, #C2886C);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dqw0fkb-l {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.ebaacj6_i {
  d: path("m12.967 3.573l-.03-.062a.3.3 0 0 0-.278-.189h-.576a1.52 1.52 0 0 0-1.511 1.529v.124c-.154-.117-.347-.364-.347-.763c0-.485.353-.73.579-.887c.063-.044.117-.08.15-.114l.044-.047c.159-.168.44-.467.932-.598q.12-.03.24-.048c.467-.069.807.349.807.822v.227z");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.eziwjdbdq {
  stop-color: var(--svg-color--ff8524, #FF8524);
  stop-opacity: 0;
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f4147fa0n {
  stop-color: var(--svg-color--ff7447, #FF7447);
  stop-opacity: 0;
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f9uy_hc2j {
  cx: 11.752px;
  cy: 5.656px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.fl8n3u57c {
  stop-color: var(--svg-color--c48b6f, #C48B6F);
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

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.g7p406nqv {
  stop-color: var(--svg-color--d0431b, #D0431B);
}

.ga-j-qbpm {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.06c.12-.109.433-.272.71-.06c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.gckwtd8pq {
  stop-color: var(--svg-color--e3ab8f, #E3AB8F);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gr7jnieaq {
  stop-color: var(--svg-color--ff6b38, #FF6B38);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gvqqg5djy {
  d: path("m12.69 5.79l-.241.832c-.05.17.069.342.235.342h.356c.167 0 .285-.174.236-.342l-.24-.832c-.052-.184-.293-.184-.347 0");
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.hzv8p_djr {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m12.667 5.961l-.313.75c-.046.17.064.341.22.341h.333c.155 0 .265-.173.22-.342l-.225-.831c-.048-.185-.184-.102-.235.082");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.idtxb7bhf {
  stop-color: var(--svg-color--dfa98a, #DFA98A);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.j--7hbfuf {
  stop-color: var(--svg-color--ff9128, #FF9128);
}

.j0lqffb7b {
  d: path("M15.058 3.109a1.072 1.072 0 0 1 .525 1.618a.7.7 0 0 0-.122.395v.538a.8.8 0 0 0-.302-.122l.036-.726a.656.656 0 0 0-.624-.648h-.633c-.432 0-.823-.255-1-.653a.3.3 0 0 0-.279-.189h-.576a1.52 1.52 0 0 0-1.511 1.529l.014.695a.8.8 0 0 0-.326.12v-.544a.7.7 0 0 0-.122-.395a1.08 1.08 0 0 1-.065-1.106a1.06 1.06 0 0 1 .588-.51c.259-.092.48-.267.626-.502a1.05 1.05 0 0 1 1.307-.413a.67.67 0 0 0 .54 0a1.05 1.05 0 0 1 1.312.427c.14.23.358.398.612.486");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.jat2c8bpf {
  stop-color: var(--svg-color--ff7049, #FF7049);
  stop-opacity: 0;
}

.jlsi1lmwv {
  d: path("M10.576 5.273a.728.728 0 0 0 .063 1.447a35 35 0 0 1-.063-1.447");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jnlns0b9v {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M15.106 6.425q.027-.43.05-.86a.432.432 0 0 1-.05.86");
}

.jove3dblx {
  stop-color: var(--svg-color--c48770, #C48770);
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

.k_iut18hr {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.k1ssgpxxp {
  stop-color: var(--svg-color--ddac86, #DDAC86);
}

.k53nzx_zw {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.944 5.36c.295 0 .544.204.612.48a.124.124 0 0 1-.12.153h-1.01a.104.104 0 0 1-.103-.123a.63.63 0 0 1 .62-.51");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.krme1767b {
  stop-color: var(--svg-color--b56e59, #B56E59);
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.l277r0b8m {
  stop-color: var(--svg-color--ff6836, #FF6836);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
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

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
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

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mj9q84mzn {
  fill: var(--svg-color--fac6a5, #FAC6A5);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mur73_bqp {
  stop-color: var(--svg-color--d89d91, #D89D91);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.myhljebwm {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.27 7.208c.17.09.374.14.592.14c.22 0 .422-.05.592-.14a.144.144 0 0 1 .171.028a.14.14 0 0 1 .016.175m-1.371-.203l1.308.161m-1.308-.16a.144.144 0 0 0-.172.029a.14.14 0 0 0-.014.173m.186-.203l-.124.161m1.495.042l-.063-.042m.063.042l-.063-.042m.063.042a.93.93 0 0 1-.779.416a.93.93 0 0 1-.778-.416m1.494-.042a.86.86 0 0 1-.716.383a.86.86 0 0 1-.716-.383m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nkhjpg89n {
  stop-color: var(--svg-color--cd8f76, #CD8F76);
  stop-opacity: 0;
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.nxl2wtijb {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.97c.176-.462.47-1.25.755-2.04z");
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o3qnlo65u {
  d: path("M9.82 3.302a.1.1 0 0 1 .1-.1h5.926a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.92a.1.1 0 0 1-.1-.1z");
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
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

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qe-n0bb5q {
  d: path("m15.22 5.099l-.013-.286a.664.664 0 0 0-.636-.645h-.633c-.402 0-.769-.22-.961-.57c0 0 .326-.94.866-.818c.395.089.818.229 1.141.44c.79.514.651 1.442.236 1.879");
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvoq5opiz {
  stop-color: var(--svg-color--b37381, #B37381);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
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

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.s6dne5bmb {
  stop-color: var(--svg-color--ba7b8a, #BA7B8A);
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

.sepv3nkwr {
  d: path("M5.527 16.647c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.sg_-x3gmw {
  stop-color: var(--svg-color--ce9878, #CE9878);
}

.sip24gb4a {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.09-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.813 2.135-.656a.415.415 0 0 1-.14.818");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.sljtuacoa {
  fill: var(--svg-color--000, #000);
  d: path("M13.619 5.887a.23.23 0 0 1 .231-.231a.23.23 0 0 1 .206.337h-.41a.2.2 0 0 1-.027-.106");
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.suc174tfe {
  stop-color: var(--svg-color--ebaf94, #EBAF94);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t469b3jak {
  stop-color: var(--svg-color--b37381, #B37381);
  stop-opacity: 0;
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

.tc1alx-sf {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.083-1.136.337-1.209.514a.415.415 0 0 1-.768-.314c.211-.516.904-1.148 2.065-1.025a.415.415 0 1 1-.088.825");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tjlv9x_9r {
  stop-color: var(--svg-color--f1bda3, #F1BDA3);
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.tvcoyjbyb {
  fill: var(--svg-color--e8b491, #E8B491);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.09-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.813 2.135-.656a.415.415 0 0 1-.14.818");
}

.tye7z2bwh {
  d: path("M13.82 5.568c.029.039-.031.086-.1.137c-.068.051-.119.087-.147.049c-.03-.039.003-.112.071-.163c.069-.05.147-.061.176-.023");
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u01sscctk {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.584 5.572a.432.432 0 0 0 .037.85a36 36 0 0 1-.037-.85");
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u1162e6xa {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
  stop-opacity: 0;
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.uvtkghs4l {
  d: path("M15.088 6.72q.046-.722.084-1.444a.728.728 0 0 1-.084 1.444");
}

.uwcvcu_5g {
  stop-color: var(--svg-color--c9786e, #C9786E);
  stop-opacity: 0;
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.vbvrfobce {
  fill: var(--svg-color--ffc9a7, #FFC9A7);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.vfcm6ebog {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M11.32 4.716q.061-.038.173-.085c.148-.058.36-.108.613-.077a.125.125 0 1 1-.03.249a1 1 0 0 0-.662.15l-.008.006a.125.125 0 0 1-.154-.198z");
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wsjf7pm3j {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x0hdn9b5y {
  stop-color: var(--svg-color--ffa61d, #FFA61D);
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.xxqudjj-y {
  fill: var(--svg-color--edb791, #EDB791);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.384c-.125.311-.24.6-.288.8c-.06.258.098.434.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.148c.082.021.14.016.22.009q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.038.367-.234c.035-.108.08-.297.121-.476c.098-.416.25-.821.25-1.254a4.95 4.95 0 0 0 .121-2.461c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.942-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.ypvlk6o_x {
  d: path("M13.85 5.483a.404.404 0 0 1 .389.51h-.78a.405.405 0 0 1 .39-.51");
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.yzedoqb0u {
  stop-color: var(--svg-color--ff7447, #FF7447);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z13dp2ohj {
  stop-color: var(--svg-color--e1ac8b, #E1AC8B);
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zozrgybxd {
  stop-color: var(--svg-color--ed5722, #ED5722);
}

.zxq4xrt3q {
  stop-color: var(--svg-color--ebaf94, #EBAF94);
  stop-opacity: 0;
}

</style>
