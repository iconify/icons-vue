<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iyxHoIm)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#ixpOhLd)"><path class="l4f1npbvr"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#iuFfqqb)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#iBudtuC)" class="b1yazzwzl"/><path fill="url(#iN4T3vz)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#iHaYQWb)"><path fill="url(#iiLGrnb)" class="ga-j-qbpm"/><path fill="url(#irBCE5b)" class="ga-j-qbpm"/><path fill="url(#iOuH9yc)" class="ga-j-qbpm"/></g><g filter="url(#iahRv3c)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#iJ79xLd)" class="qexsyge6i"/><path fill="url(#iCXpP7L)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iMSrRBe)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#ibqhxxe)"><path fill="url(#iTF2f9h)" class="dc-w_nb2z"/><path fill="url(#iDFUiOc)" class="dc-w_nb2z"/></g><g filter="url(#iizF7zc)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#ipwFt6d)"><path fill="url(#imE0utb)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="b39b9ipgf"/><path fill="url(#iwDZzcX)" class="eikeckbha"/><path fill="url(#iX11RWb)" class="eikeckbha"/><path clip-rule="evenodd" class="iv-u_b8_r"/><path fill="url(#iB67Ffd)" clip-rule="evenodd" class="x99s9tbej"/><path clip-rule="evenodd" class="onfgb5bvd"/><path fill="url(#i0it2pc)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="rf25mcqqf"/><path fill="url(#iVfNrub)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="fc917gbph"/><path fill="url(#ir79Rte)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#isC8Bze)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#iNU2oqd)"><path fill="url(#i40rhfb)" class="p3ru7q3ze"/><path fill="url(#iBXH0lc)" class="p3ru7q3ze"/></g><path fill="url(#iPJ2hNc)" class="p3ru7q3ze"/><path fill="url(#i0KbY9c)" clip-rule="evenodd" class="y_4pajl7d"/><g filter="url(#i3bYDpb)"><path class="mqd1-3r2u"/></g><g filter="url(#i9kfs6d)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><path fill="url(#iErCiib)" class="m1374cwws"/><path fill="url(#iiNs8ED)" class="tbhq75bkh"/><g filter="url(#iAcrCnM)"><path fill="url(#ivtBMFG)" class="xbjozlwrq"/></g><path fill="url(#iwd8NUu)" class="xbjozlwrq"/><path fill="url(#iaU1CCc)" class="xbjozlwrq"/><path fill="url(#igb3QBe)" class="xbjozlwrq"/><path fill="url(#ijXp9tE)" class="xbjozlwrq"/><path fill="url(#io3gcZb)" class="xbjozlwrq"/><path fill="url(#ioob61n)" class="xbjozlwrq"/><g filter="url(#i29sWEc)"><path class="b6kupkfos"/></g><g filter="url(#iU4GA9F)"><path class="vzjr9rb9z"/><path fill="url(#iZX9CVd)" class="wq4nczbox"/><path fill="url(#iTjh9fb)" class="wq4nczbox"/><path fill="url(#iL4KQWX)" class="wq4nczbox"/><path fill="url(#ifDycne)" class="wq4nczbox"/><path fill="url(#i8pnNrw)" class="wq4nczbox"/></g><g filter="url(#iOuha0D)"><path stroke="url(#i1xl8hc)" class="nic6sf48x"/></g><path fill="url(#i4MzdRb)" class="stje8nbmb"/><g filter="url(#iCumBWb)"><path fill="url(#i5BCnhb)" class="viwbfhbpy"/><path fill="url(#iwxa91c)" class="viwbfhbpy"/><path fill="url(#iY4Irxc)" class="viwbfhbpy"/><path fill="url(#isMZ8Lb)" class="viwbfhbpy"/><path fill="url(#i5C1IlD)" class="viwbfhbpy"/></g><g filter="url(#iNFUUTq)"><path class="wwp80dwsp"/></g><g filter="url(#iSqIlmU)"><path class="nbdsgmaen"/></g><g filter="url(#iAZ6Iab)"><path class="i_popxbaa"/><path fill="url(#iHQSWnd)" class="px9__nhfl"/><path fill="url(#i2v27vc)" class="px9__nhfl"/></g><g filter="url(#ivEoTyb)"><path class="es5h1m40k"/><path fill="url(#iTUeLqb)" class="lx-ketbdw"/><path fill="url(#iIR8zpb)" class="lx-ketbdw"/><path fill="url(#isoQngd)" class="lx-ketbdw"/></g><path class="i4eag_h6w"/><path fill="url(#idDAtkb)" class="m16m72bww"/><path class="fdffwdbab"/><g filter="url(#ihfOhRw)"><path class="ii6fr1rbu"/><path fill="url(#i3og4Ey)" class="f0_1nsb-q"/></g><g filter="url(#iVqhZrQ)"><path fill="url(#iQr0aAb)" class="zzt6h9b-z"/></g><path class="i4b_5vipz"/><path fill="url(#iDc6CUb)" class="hh3_3ybfc"/><path class="yqt-vz_5s"/><g filter="url(#izVrPRR)"><path fill="url(#iSiBMBY)" class="yywvj6t9y"/></g><g filter="url(#iZ8e56b)"><ellipse transform="rotate(-27.914 11.75 5.656)" class="a_35neb1u"/><ellipse fill="url(#iq6uQEb)" transform="rotate(-27.914 11.75 5.656)" class="fr6pqwbmg"/></g><path fill="url(#iNga8xd)" class="vg0e6gb0k"/><path fill="url(#ixPC2Hd)" class="vg0e6gb0k"/><path fill="url(#iCdc0Ce)" class="vg0e6gb0k"/><path fill="url(#igLXWgH)" class="vg0e6gb0k"/><path fill="url(#iaYfVVd)" class="t6lbukqpf"/><path fill="url(#iLOyY0d)" class="t6lbukqpf"/><g filter="url(#i4zyGce)"><path fill="url(#i3iH0tc)" class="et58ovbgs"/></g><g filter="url(#ibeGxRd)"><path fill="url(#iHlXa7i)" class="qzdds6bgw"/></g><path fill="url(#iHeMwGe)" class="uurl49hsa"/><path fill="url(#iZEwVfe)" class="uurl49hsa"/><path fill="url(#iqsxbAc)" class="uurl49hsa"/><path fill="url(#ijbP34W)" class="uurl49hsa"/><defs><radialGradient id="iyxHoIm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="of6eoebwa"/><stop offset="1" class="hhvxh5bcs"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="iBudtuC" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="btsp6rbtk"/><stop offset="1" class="qk70xkspj"/></radialGradient><radialGradient id="iN4T3vz" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="s515o6bjz"/><stop offset="1" class="mid6c9bnp"/></radialGradient><radialGradient id="iiLGrnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="gr7jnieaq"/><stop offset="1" class="fni059bsf"/></radialGradient><radialGradient id="irBCE5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="r24pfmh2j"/><stop offset="1" class="jat2c8bpf"/></radialGradient><radialGradient id="iOuH9yc" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="yzedoqb0u"/><stop offset="1" class="f4147fa0n"/></radialGradient><radialGradient id="iJ79xLd" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="e085m5ymq"/><stop offset="1" class="c_xsycbdz"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iTF2f9h" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="l277r0b8m"/><stop offset="1" class="m1km_jo3a"/></radialGradient><radialGradient id="imE0utb" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="lk1-k5bve"/><stop offset="1" class="biy3jzpmj"/></radialGradient><radialGradient id="iwDZzcX" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="w_rrm9a7q"/><stop offset="1" class="nkhjpg89n"/><stop offset="1" class="d7rccub7n"/></radialGradient><radialGradient id="iX11RWb" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="oxnqswb1g"/><stop offset="1" class="ycl44mqxw"/></radialGradient><radialGradient id="iB67Ffd" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="i0it2pc" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="iVfNrub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="ir79Rte" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="isC8Bze" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="k_ltadprl"/><stop offset="1" class="tsvq44-rv"/></radialGradient><radialGradient id="i40rhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.479)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="j--7hbfuf"/><stop offset=".81" class="zozrgybxd"/></radialGradient><radialGradient id="iBXH0lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8437 -6.87502 1.8572 -.49805 18.024 16.393)" gradientUnits="userSpaceOnUse"><stop class="wsjf7pm3j"/><stop offset="1" class="u1162e6xa"/></radialGradient><radialGradient id="iPJ2hNc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.271 8.996)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="x0hdn9b5y"/><stop offset="1" class="eziwjdbdq"/></radialGradient><radialGradient id="i0KbY9c" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="yvgme-ued"/><stop offset="1" class="t405zhbew"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="iErCiib" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 2.806 14.056)scale(.97423 1.15731)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iiNs8ED" cx="0" cy="0" r="1" gradientTransform="matrix(.66782 .20989 -.64751 2.06027 10.12 6.76)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="ivtBMFG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36462 0 0 -4.183 14.13 6.113)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iaU1CCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.45148 5.7751 -4.78248 -.37388 13.575 3.438)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="www4dfogh"/><stop offset="1" class="c0317ln8x"/></radialGradient><radialGradient id="igb3QBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51941 .64277 0 13.967 5.52)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="ijXp9tE" cx="0" cy="0" r="1" gradientTransform="matrix(.00178 -.49496 .53863 .00193 11.82 5.54)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="io3gcZb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 7.103 3.507)scale(3.85049 9.83608)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="ioob61n" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 5.89 5.866)scale(1.52383 1.25805)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iTjh9fb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11041 -.347 0 13.07 6.729)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="ifDycne" cx="0" cy="0" r="1" gradientTransform="matrix(-.68803 .31546 -.50697 -1.10573 13.123 6.471)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="i4MzdRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.326 1.31158 0 12.86 7.714)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iwxa91c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.58369 4.00498 0 10.495 4.805)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iY4Irxc" cx="0" cy="0" r="1" gradientTransform="matrix(.05158 -1.13646 2.01358 .0914 15.058 5.398)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="isMZ8Lb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06693 -.70172 .5151 -.78318 14.717 2.559)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="i5C1IlD" cx="0" cy="0" r="1" gradientTransform="matrix(.4094 .66716 -1.54481 .94796 12.45 1.838)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iHQSWnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.9956 0 0 -.3695 12.975 2.86)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i2v27vc" cx="0" cy="0" r="1" gradientTransform="matrix(1.45564 -2.30473 2.5534 1.6127 10.403 4.643)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iTUeLqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38335 0 0 .54087 14.404 3.212)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="iIR8zpb" cx="0" cy="0" r="1" gradientTransform="rotate(-43.614 12.756 -15.266)scale(1.67351 3.06376)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="isoQngd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4692 .17173 -.0719 .61513 13.65 3.918)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="idDAtkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36697 -.5837 0 13.847 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i3og4Ey" cx="0" cy="0" r="1" gradientTransform="matrix(-.1049 -.13518 .1861 -.14442 13.744 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDc6CUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36699 -.58374 0 11.873 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iq6uQEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22348 .26863 -.0042 11.743 5.798)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixPC2Hd" cx="0" cy="0" r="1" gradientTransform="matrix(.2843 1.01466 -.96807 .27125 14.948 5.705)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iCdc0Ce" cx="0" cy="0" r="1" gradientTransform="matrix(.35632 -.489 .40988 .29867 15.111 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="igLXWgH" cx="0" cy="0" r="1" gradientTransform="matrix(.2655 -.70128 .937 .35475 15.163 6.03)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iLOyY0d" cx="0" cy="0" r="1" gradientTransform="rotate(-173.035 5.5 2.674)scale(.73508 .78908)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="i3iH0tc" cx="0" cy="0" r="1" gradientTransform="rotate(170.258 5.063 3.451)scale(.4206 .51609)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iHeMwGe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.415 3.733)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="ijbP34W" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.243 3.202)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><filter id="ixpOhLd" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.552941 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="iuFfqqb" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="iHaYQWb" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.32549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="iahRv3c" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="iMSrRBe" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="ibqhxxe" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.231373 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="iizF7zc" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="ipwFt6d" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.603922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.45098 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23235" result="effect2_innerShadow_3987_23235"/></filter><filter id="iNU2oqd" width="7.636" height="9.986" x="11.582" y="7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.215686 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="i3bYDpb" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".25"/></filter><filter id="i9kfs6d" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="iAcrCnM" width="5.623" height="5.782" x="10.57" y="3.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23235" result="effect2_innerShadow_3987_23235"/></filter><filter id="i29sWEc" width="2.79" height="3.312" x="11.401" y="4.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".5"/></filter><filter id="iU4GA9F" width=".949" height="1.412" x="12.385" y="5.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".025"/></filter><filter id="iOuha0D" width="1.956" height=".985" x="11.882" y="7.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".05"/></filter><filter id="iCumBWb" width="5.822" height="4.054" x="9.949" y="1.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23235" result="effect2_innerShadow_3987_23235"/></filter><filter id="iNFUUTq" width="1.113" height=".648" x="13.579" y="4.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="iSqIlmU" width="1.113" height=".641" x="11.201" y="4.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/></filter><filter id="iAZ6Iab" width="3.252" height="2.765" x="10.123" y="2.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23235"/><feGaussianBlur result="effect2_foregroundBlur_3987_23235" stdDeviation=".05"/></filter><filter id="ivEoTyb" width="2.777" height="2.53" x="12.875" y="2.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".05"/></filter><filter id="ihfOhRw" width=".465" height=".424" x="13.46" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".05"/></filter><filter id="iVqhZrQ" width=".622" height=".632" x="13.785" y="5.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".1"/></filter><filter id="izVrPRR" width=".665" height=".69" x="11.776" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".1"/></filter><filter id="iZ8e56b" width=".523" height=".428" x="11.489" y="5.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".05"/></filter><filter id="i4zyGce" width=".875" height="1.35" x="9.973" y="5.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".125"/></filter><filter id="ibeGxRd" width="1.428" height="1.861" x="14.624" y="5.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23235" stdDeviation=".25"/></filter><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iCXpP7L" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="q2zf-acki"/><stop offset="1" class="wrgoaxbaa"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iDFUiOc" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="g7p406nqv"/><stop offset="1" class="r52adsb8o"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iwd8NUu" x1="15.193" x2="13.224" y1="6.876" y2="6.876" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iZX9CVd" x1="13.239" x2="12.86" y1="6.419" y2="6.434" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iL4KQWX" x1="12.86" x2="12.86" y1="6.934" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i8pnNrw" x1="12.86" x2="12.86" y1="5.652" y2="5.958" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="i1xl8hc" x1="12.316" x2="12.46" y1="7.644" y2="7.267" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="i5BCnhb" x1="15.959" x2="10.707" y1="3.552" y2="3.552" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iQr0aAb" x1="14.199" x2="14.057" y1="5.723" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSiBMBY" x1="12.21" x2="12.068" y1="5.723" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNga8xd" x1="15.771" x2="15.225" y1="5.735" y2="6.72" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iaYfVVd" x1="10.214" x2="10.873" y1="6.054" y2="5.996" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iHlXa7i" x1="15.338" x2="15.338" y1="5.568" y2="6.428" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="iZEwVfe" x1="9.797" x2="13.508" y1="3.92" y2="3.92" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iqsxbAc" x1="13.571" x2="13.571" y1="4.264" y2="4.147" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bouncing-ball-light" /></template>
<style>
.a_35neb1u {
  cx: 11.75px;
  cy: 5.656px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
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

.b39b9ipgf {
  fill: var(--svg-color--ffddc4, #FFDDC4);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.b6kupkfos {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m12.678 5.876l-.267.832c-.045.17.064.342.22.342h.33c.155 0 .265-.174.22-.342l-.224-.832c-.048-.184-.228-.184-.279 0");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.biy3jzpmj {
  stop-color: var(--svg-color--daa490, #DAA490);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.btsp6rbtk {
  stop-color: var(--svg-color--fec8b8, #FEC8B8);
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c_xsycbdz {
  stop-color: var(--svg-color--e2ac91, #E2AC91);
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c0317ln8x {
  stop-color: var(--svg-color--c9747e, #C9747E);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d7rccub7n {
  stop-color: var(--svg-color--d08776, #D08776);
  stop-opacity: 0;
}

.dc-w_nb2z {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.255");
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e085m5ymq {
  stop-color: var(--svg-color--f3beac, #F3BEAC);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
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

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.es5h1m40k {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m15.218 5.05l-.014-.285a.664.664 0 0 0-.635-.644h-.634c-.402 0-.768-.22-.96-.57c0 0 .326-.94.866-.819c.395.09.818.229 1.141.44c.79.515.651 1.442.236 1.879");
}

.et58ovbgs {
  d: path("M10.56 5.571a.432.432 0 0 0 .037.85a36 36 0 0 1-.037-.85");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
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

.f0_1nsb-q {
  d: path("M13.818 5.568c.029.039-.031.086-.1.137c-.068.05-.119.087-.148.048s.004-.11.072-.162c.069-.05.147-.061.176-.023");
}

.f4147fa0n {
  stop-color: var(--svg-color--ff7447, #FF7447);
  stop-opacity: 0;
}

.fc917gbph {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdffwdbab {
  fill: var(--svg-color--000, #000);
  d: path("M13.617 5.887a.23.23 0 0 1 .23-.231a.23.23 0 0 1 .206.337h-.409a.2.2 0 0 1-.027-.106");
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fni059bsf {
  stop-color: var(--svg-color--ff6b3f, #FF6B3F);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.fr6pqwbmg {
  cx: 11.75px;
  cy: 5.656px;
  rx: 0.176px;
  ry: 0.089px;
}

.ft5dv1b6b {
  fill: none;
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
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

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
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

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hh3_3ybfc {
  d: path("M11.872 5.483a.404.404 0 0 0-.389.51h.78a.406.406 0 0 0-.39-.51");
}

.hhvxh5bcs {
  stop-color: var(--svg-color--cb766a, #CB766A);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.i_popxbaa {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m12.965 3.573l-.03-.062a.3.3 0 0 0-.278-.189h-.576A1.52 1.52 0 0 0 10.57 4.85v.125c-.154-.117-.348-.364-.348-.763c0-.485.354-.73.58-.887c.063-.044.117-.08.15-.114l.044-.048c.158-.167.44-.466.932-.597q.12-.03.239-.048c.468-.07.808.349.808.822v.227z");
}

.i1mrv7bgu {
  stop-color: var(--svg-color--df968d, #DF968D);
  stop-opacity: 0;
}

.i4b_5vipz {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.779 5.36a.63.63 0 0 0-.613.48c-.02.078.04.153.12.153h1.01a.104.104 0 0 0 .103-.123a.634.634 0 0 0-.62-.51");
}

.i4eag_h6w {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.941 5.36c.296 0 .545.204.613.48a.124.124 0 0 1-.12.153h-1.01a.104.104 0 0 1-.103-.123a.63.63 0 0 1 .62-.51");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ii6fr1rbu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.818 5.568c.029.039-.031.086-.1.137c-.068.05-.119.087-.148.048s.004-.11.072-.162c.069-.05.147-.061.176-.023");
}

.iv-u_b8_r {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j--7hbfuf {
  stop-color: var(--svg-color--ff9128, #FF9128);
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

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jat2c8bpf {
  stop-color: var(--svg-color--ff7049, #FF7049);
  stop-opacity: 0;
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.k_ltadprl {
  stop-color: var(--svg-color--ffcebb, #FFCEBB);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
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

.l277r0b8m {
  stop-color: var(--svg-color--ff6836, #FF6836);
}

.l4f1npbvr {
  fill: var(--svg-color--ffcaaf, #FFCAAF);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk1-k5bve {
  stop-color: var(--svg-color--f3bda8, #F3BDA8);
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.lx-ketbdw {
  d: path("m15.218 5.05l-.014-.285a.664.664 0 0 0-.635-.644h-.634c-.402 0-.768-.22-.96-.57c0 0 .326-.94.866-.819c.395.09.818.229 1.141.44c.79.515.651 1.442.236 1.879");
}

.m1374cwws {
  d: path("M15.059 6.679a.74.74 0 0 0 .409-.14v.421a.98.98 0 0 1-.607.913q.116-.246.157-.533z");
}

.m16m72bww {
  d: path("M13.848 5.483a.404.404 0 0 1 .389.51h-.78a.405.405 0 0 1 .39-.51");
}

.m1km_jo3a {
  stop-color: var(--svg-color--ff5a36, #FF5A36);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mid6c9bnp {
  stop-color: var(--svg-color--bc818e, #BC818E);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mqd1-3r2u {
  fill: var(--svg-color--ffdec5, #FFDEC5);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.nbdsgmaen {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.317 4.716q.062-.038.173-.085c.149-.058.36-.108.614-.077a.125.125 0 1 1-.031.249a1 1 0 0 0-.661.15l-.008.006a.125.125 0 0 1-.155-.198z");
}

.nic6sf48x {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.638 7.41a.14.14 0 0 0-.015-.174a.144.144 0 0 0-.17-.028h-.001c-.17.09-.372.14-.592.14c-.218 0-.422-.05-.592-.14a.144.144 0 0 0-.172.03a.14.14 0 0 0-.015.173m1.557 0l-.062-.042zm0 0a.93.93 0 0 1-.778.416a.93.93 0 0 1-.779-.416m0 0l.001.001l.062-.043m-.063.042l.063-.042m0 0c.151.23.415.383.716.383c.3 0 .564-.153.716-.383c.039-.058-.028-.126-.09-.094a1.35 1.35 0 0 1-.626.148a1.36 1.36 0 0 1-.627-.148c-.062-.032-.128.038-.09.094Z");
}

.nkhjpg89n {
  stop-color: var(--svg-color--cd8f76, #CD8F76);
  stop-opacity: 0;
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of6eoebwa {
  stop-color: var(--svg-color--da9885, #DA9885);
}

.of70meq1k {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.onfgb5bvd {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oxnqswb1g {
  stop-color: var(--svg-color--f6b7a5, #F6B7A5);
  stop-opacity: 0;
}

.p3ru7q3ze {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.px9__nhfl {
  d: path("m12.965 3.573l-.03-.062a.3.3 0 0 0-.278-.189h-.576A1.52 1.52 0 0 0 10.57 4.85v.125c-.154-.117-.348-.364-.348-.763c0-.485.354-.73.58-.887c.063-.044.117-.08.15-.114l.044-.048c.158-.167.44-.466.932-.597q.12-.03.239-.048c.468-.07.808.349.808.822v.227z");
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q2zf-acki {
  stop-color: var(--svg-color--c28895, #C28895);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qk70xkspj {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzdds6bgw {
  d: path("m15.124 6.428l.05-.86a.432.432 0 0 1-.05.86");
}

.r24pfmh2j {
  stop-color: var(--svg-color--ff7049, #FF7049);
}

.r52adsb8o {
  stop-color: var(--svg-color--d0431b, #D0431B);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rf25mcqqf {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
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

.s515o6bjz {
  stop-color: var(--svg-color--bc818e, #BC818E);
  stop-opacity: 0;
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

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.stje8nbmb {
  d: path("M12.86 7.423a1.36 1.36 0 0 1-.627-.148c-.062-.032-.128.038-.09.094c.152.23.416.383.717.383c.3 0 .564-.153.716-.383c.039-.058-.028-.126-.09-.094a1.35 1.35 0 0 1-.626.148");
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t405zhbew {
  stop-color: var(--svg-color--f3c2a5, #F3C2A5);
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

.t6lbukqpf {
  d: path("M10.578 5.272a.728.728 0 0 0 .058 1.448a35 35 0 0 1-.058-1.448");
}

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.tbhq75bkh {
  d: path("M10.661 6.679a.74.74 0 0 1-.41-.14v.421c0 .404.242.764.607.913a1.9 1.9 0 0 1-.156-.533z");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tsvq44-rv {
  stop-color: var(--svg-color--fdc9b0, #FDC9B0);
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
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

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.uurl49hsa {
  d: path("M9.797 3.302a.1.1 0 0 1 .1-.1h5.926a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.897a.1.1 0 0 1-.1-.1z");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.vg0e6gb0k {
  d: path("M15.086 6.72q.046-.722.083-1.444a.728.728 0 0 1-.083 1.444");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.viwbfhbpy {
  d: path("M15.056 3.109c.233.08.441.242.573.475c.211.371.18.815-.048 1.143a.7.7 0 0 0-.122.395v.538a.8.8 0 0 0-.302-.122l.036-.726a.656.656 0 0 0-.624-.648h-.634c-.431 0-.822-.255-1-.653a.3.3 0 0 0-.278-.189h-.576a1.52 1.52 0 0 0-1.511 1.529l.014.695a.8.8 0 0 0-.326.12v-.544a.7.7 0 0 0-.122-.395a1.08 1.08 0 0 1-.065-1.107a1.06 1.06 0 0 1 .588-.509c.258-.092.48-.267.626-.502a1.05 1.05 0 0 1 1.307-.413a.67.67 0 0 0 .54 0a1.05 1.05 0 0 1 1.312.427c.14.23.357.398.612.486");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.vzjr9rb9z {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m12.687 5.79l-.24.832c-.05.17.068.342.235.342h.356c.167 0 .284-.174.235-.342l-.24-.832c-.052-.184-.292-.184-.346 0");
}

.w_rrm9a7q {
  stop-color: var(--svg-color--d08776, #D08776);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wq4nczbox {
  d: path("m12.687 5.79l-.24.832c-.05.17.068.342.235.342h.356c.167 0 .284-.174.235-.342l-.24-.832c-.052-.184-.292-.184-.346 0");
}

.wrgoaxbaa {
  stop-color: var(--svg-color--f2bdaa, #F2BDAA);
  stop-opacity: 0;
}

.wsjf7pm3j {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
}

.wwp80dwsp {
  fill: var(--svg-color--202020, #202020);
  d: path("M14.548 4.765a.8.8 0 0 0-.31-.186c-.138-.043-.31-.055-.549-.025a.125.125 0 0 0 .03.249c.218-.027.351-.013.443.016c.09.028.15.074.222.136a.125.125 0 1 0 .164-.19");
}

.www4dfogh {
  stop-color: var(--svg-color--d69b93, #D69B93);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x0hdn9b5y {
  stop-color: var(--svg-color--ffa61d, #FFA61D);
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.xbjozlwrq {
  d: path("M10.678 7.364a1.77 1.77 0 0 0 1.757 1.54h.853a1.77 1.77 0 0 0 1.758-1.54c.053-.852.107-1.7.147-2.552a.656.656 0 0 0-.624-.648h-.634c-.431 0-.822-.255-1-.653a.3.3 0 0 0-.278-.189h-.576A1.52 1.52 0 0 0 10.57 4.85c0 .842.052 1.67.107 2.514");
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.ycl44mqxw {
  stop-color: var(--svg-color--f6b7a5, #F6B7A5);
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yqt-vz_5s {
  fill: var(--svg-color--000, #000);
  d: path("M12.103 5.887a.23.23 0 0 0-.231-.231a.23.23 0 0 0-.206.337h.41a.23.23 0 0 0 .027-.106");
}

.yvgme-ued {
  stop-color: var(--svg-color--f3c2a5, #F3C2A5);
}

.yywvj6t9y {
  d: path("M12.24 5.84c0-.131-.105-.218-.134-.244l-.13.126l.08.163z");
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.yzedoqb0u {
  stop-color: var(--svg-color--ff7447, #FF7447);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zozrgybxd {
  stop-color: var(--svg-color--ed5722, #ED5722);
}

.zvhlj4t4z {
  stop-color: var(--svg-color--df968d, #DF968D);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzt6h9b-z {
  d: path("M14.207 5.834a.4.4 0 0 0-.104-.21l-.118.13l.053.103z");
}

</style>
