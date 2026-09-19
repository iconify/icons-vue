<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iodgHEb)"><path fill="url(#iFEAkTd)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#ijDuJ5c)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#iUCwBme)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#iBvmJsd)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#iO5ROSc)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#ikBANDd)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#ilhqjGe)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#inIMdNd)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#irpNuSc)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#ibaHi4d)" clip-rule="evenodd" class="fs9onubla"/><path fill="url(#izjH6Xd)" clip-rule="evenodd" class="fs9onubla"/></g><rect fill="url(#iyxHoIm)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#iOyJ3Db)"><path class="l4f1npbvr"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#ilNhZPe)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#iBudtuC)" class="b1yazzwzl"/><path fill="url(#iN4T3vz)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#ifrQf5c)"><path fill="url(#ikclHuc)" class="ga-j-qbpm"/><path fill="url(#iqSctJd)" class="ga-j-qbpm"/><path fill="url(#iZVep2c)" class="ga-j-qbpm"/></g><g filter="url(#itnojub)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#iJ79xLd)" class="qexsyge6i"/><path fill="url(#iCXpP7L)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iFpRgrc)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#i0SFjJO)"><path fill="url(#i55AUOe)" class="dc-w_nb2z"/><path fill="url(#i136FHe)" class="dc-w_nb2z"/></g><g filter="url(#imfFihd)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#i6CAbqc)"><path fill="url(#imE0utb)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="b39b9ipgf"/><path fill="url(#iwDZzcX)" class="eikeckbha"/><path fill="url(#iX11RWb)" class="eikeckbha"/><path clip-rule="evenodd" class="iv-u_b8_r"/><path fill="url(#iB67Ffd)" clip-rule="evenodd" class="x99s9tbej"/><path clip-rule="evenodd" class="onfgb5bvd"/><path fill="url(#i0it2pc)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="rf25mcqqf"/><path fill="url(#iVfNrub)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="fc917gbph"/><path fill="url(#ir79Rte)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#isC8Bze)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#ilDCNvN)"><path class="tmtee3wvy"/><path fill="url(#iQBvayU)" class="p3ru7q3ze"/></g><path fill="url(#i3EK4rb)" class="p3ru7q3ze"/><path fill="url(#i0KbY9c)" clip-rule="evenodd" class="y_4pajl7d"/><g filter="url(#iceqeqh)"><path class="mqd1-3r2u"/></g><g filter="url(#igNyBFz)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><g filter="url(#iCePrEc)"><path fill="url(#iTq8DLc)" class="w7i-mnc1w"/></g><g filter="url(#iFMmURc)"><path fill="url(#i9b0Jde)" class="htgi_9ynt"/><path fill="url(#i67XhNb)" class="htgi_9ynt"/></g><g filter="url(#ibHTeCd)"><path class="xnhmgtb4v"/><path fill="url(#iAjOpbD)" class="za4q5931x"/></g><g filter="url(#iB1wUqd)"><path class="l9sedbbgz"/><path fill="url(#iByfaXb)" class="awz-49rkh"/></g><g filter="url(#i2qe3Td)"><path fill="url(#i3zcIVc)" class="eiwjo5bgy"/><path fill="url(#itVsued)" class="eiwjo5bgy"/><path fill="url(#i8GFzqc)" class="eiwjo5bgy"/><path fill="url(#inmFfBc)" class="eiwjo5bgy"/><path fill="url(#iCHb0fd)" class="eiwjo5bgy"/><path fill="url(#iLCb2Rd)" class="eiwjo5bgy"/><path fill="url(#iihQvje)" class="eiwjo5bgy"/></g><path fill="url(#iby6RTc)" class="eiwjo5bgy"/><path fill="url(#iNZIvzI)" class="eiwjo5bgy"/><g filter="url(#ivWrIEc)"><path class="vdxi4tb1n"/></g><g filter="url(#iI8df9d)"><path class="ttc09ac2m"/><path fill="url(#ixNFkFb)" class="x_0va9b6r"/><path fill="url(#i5pho2d)" class="x_0va9b6r"/><path fill="url(#iBssYqc)" class="x_0va9b6r"/><path fill="url(#iOolTFd)" class="x_0va9b6r"/></g><g filter="url(#iwMtkDd)"><path stroke="url(#iMesCgd)" class="hss_kmoqc"/></g><path class="dqo8dqb7t"/><g filter="url(#imnKKOc)"><path class="qip0gxafn"/></g><g filter="url(#izT5gsd)"><path class="ngj-91f4z"/></g><g filter="url(#ijJe7od)"><path class="i8abrhump"/></g><g filter="url(#ifDe93b)"><path clip-rule="evenodd" class="gug6nq90d"/></g><path class="z93iw6sik"/><path fill="url(#iESJx6b)" class="o-zx5tgee"/><path class="t_lsdxbeo"/><g filter="url(#ifocYDt)"><path class="xl9p39bpy"/><path fill="url(#iYiDk6T)" class="rc4cqmd1y"/></g><g filter="url(#i28Y5Ad)"><path fill="url(#iUCcnyc)" class="b24nyubzn"/></g><path class="rp58g3bju"/><path fill="url(#i2b7CJc)" class="o266gvb-m"/><path class="m_p65hrmz"/><g filter="url(#ivdIfGd)"><path fill="url(#iHT6AQc)" class="a1qou1bcx"/></g><g filter="url(#iHPotnb)"><ellipse transform="rotate(-27.914 11.766 5.736)" class="l4-oj3bqy"/><ellipse fill="url(#iM0aCIb)" transform="rotate(-27.914 11.766 5.736)" class="ijpnedbmt"/></g><g filter="url(#iZFoE6c)"><path class="hgf77-wwh"/></g><g filter="url(#iRkWQWb)"><path class="kl-0efb1i"/></g><g filter="url(#ihcPYEd)"><path class="tfa_5nb_n"/><path fill="url(#i4tWPOb)" class="csiv6mb3v"/><path fill="url(#itkXpqb)" class="csiv6mb3v"/></g><g filter="url(#i1DjlBb)"><path class="zh-mcpham"/></g><g filter="url(#ilZYcwe)"><path class="rfjmiv-1j"/></g><defs><radialGradient id="ijDuJ5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.27911 2.10896 -2.63452 -.34867 12.762 7.214)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iUCwBme" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.608 5.42)scale(1.60858 2.11355)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iBvmJsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60477 .79086 -.60727 -.46438 10.66 6.159)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iO5ROSc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.97 5.658)scale(1.14492 .8065)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ikBANDd" cx="0" cy="0" r="1" gradientTransform="matrix(.63579 1.20955 -1.67903 .88257 11.273 2.329)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ilhqjGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.66676 .6668 -.93185 -.93179 15.6 3.29)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="inIMdNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.85285 .24813 -.51745 -1.77852 16.375 5.662)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="irpNuSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30255 .32566 -.41484 -1.65926 16.095 7.244)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ibaHi4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.41838 -1.22597 .96967 -.33091 15.09 4.537)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="izjH6Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.69569 .07297 -.11824 1.12722 10.06 5.646)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iyxHoIm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="of6eoebwa"/><stop offset="1" class="hhvxh5bcs"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="iBudtuC" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="btsp6rbtk"/><stop offset="1" class="qk70xkspj"/></radialGradient><radialGradient id="iN4T3vz" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="s515o6bjz"/><stop offset="1" class="mid6c9bnp"/></radialGradient><radialGradient id="ikclHuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="b1kvifv3j"/><stop offset="1" class="w__bqyylv"/></radialGradient><radialGradient id="iqSctJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iZVep2c" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iJ79xLd" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="e085m5ymq"/><stop offset="1" class="c_xsycbdz"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="i55AUOe" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uwn_p0-dn"/><stop offset="1" class="sa6pubcic"/></radialGradient><radialGradient id="imE0utb" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="lk1-k5bve"/><stop offset="1" class="biy3jzpmj"/></radialGradient><radialGradient id="iwDZzcX" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="w_rrm9a7q"/><stop offset="1" class="nkhjpg89n"/><stop offset="1" class="d7rccub7n"/></radialGradient><radialGradient id="iX11RWb" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".67" class="oxnqswb1g"/><stop offset="1" class="ycl44mqxw"/></radialGradient><radialGradient id="iB67Ffd" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="i0it2pc" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="iVfNrub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="ir79Rte" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="zvhlj4t4z"/><stop offset="1" class="i1mrv7bgu"/></radialGradient><radialGradient id="isC8Bze" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="k_ltadprl"/><stop offset="1" class="tsvq44-rv"/></radialGradient><radialGradient id="i3EK4rb" cx="0" cy="0" r="1" gradientTransform="rotate(106.912 4.941 9.22)scale(3.20093 4.86981)" gradientUnits="userSpaceOnUse"><stop class="env4r_bwx"/><stop offset="1" class="spg8_pgop"/></radialGradient><radialGradient id="i0KbY9c" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="yvgme-ued"/><stop offset="1" class="t405zhbew"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="i9b0Jde" cx="0" cy="0" r="1" gradientTransform="matrix(.84513 -.94205 1.1502 1.03187 14.987 6.508)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="i67XhNb" cx="0" cy="0" r="1" gradientTransform="rotate(29.271 -2.484 31.831)scale(.69774 .19726)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="iAjOpbD" cx="0" cy="0" r="1" gradientTransform="matrix(.69845 -.05195 .04061 .546 14.932 6.108)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iByfaXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.55825 0 0 -.4404 10.773 6.056)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="i3zcIVc" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.474 4.465)scale(3.31291 4.43427)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="itVsued" cx="0" cy="0" r="1" gradientTransform="rotate(172.574 6.994 3.686)scale(1.61462 1.78226)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i8GFzqc" cx="0" cy="0" r="1" gradientTransform="matrix(.60477 -1.7523 2.22334 .76735 11.8 9.198)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="inmFfBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.11072 -3.60078 0 12.9 5.707)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="vrhnsgvqh"/><stop offset="1" class="iuch0hb0l"/></radialGradient><radialGradient id="iCHb0fd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.19445 .6269 -1.07933 -5.49985 13.738 6.609)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iLCb2Rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.53233 .65331 0 13.965 5.614)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iihQvje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60715 .69583 0 11.94 5.509)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iby6RTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59455 0 0 -2.98162 15.258 6.302)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="iNZIvzI" cx="0" cy="0" r="1" gradientTransform="matrix(.60714 1.85034 -3.2235 1.05771 11.89 3.033)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="ixNFkFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21073 -.94553 .2914 -.06494 13.264 6.639)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iOolTFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.36054 0 0 -.1008 13.153 6.736)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iESJx6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3753 -.59696 0 13.91 5.78)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iYiDk6T" cx="0" cy="0" r="1" gradientTransform="matrix(-.10728 -.13825 .19033 -.1477 13.803 5.82)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2b7CJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3753 -.59696 0 11.892 5.78)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iM0aCIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00358 -.22854 .27473 -.0043 11.759 5.882)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4tWPOb" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.14 5.529)scale(2.25413 3.68536)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="itkXpqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0973 .63244 -1.36067 -.20933 12.998 2.562)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iodgHEb" width="7.197" height="7.697" x="9.427" y="1.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="iOyJ3Db" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.552941 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="ilNhZPe" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="ifrQf5c" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.341176 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="itnojub" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="iFpRgrc" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="i0SFjJO" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="imfFihd" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="i6CAbqc" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.603922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.45098 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23236" result="effect2_innerShadow_3987_23236"/></filter><filter id="ilDCNvN" width="8.236" height="9.786" x="11.582" y="7.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.262745 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23236" result="effect2_innerShadow_3987_23236"/></filter><filter id="iceqeqh" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".25"/></filter><filter id="igNyBFz" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="iCePrEc" width="1.639" height="1.489" x="9.989" y="5.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="iFMmURc" width="1.489" height="1.739" x="14.39" y="5.062" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="ibHTeCd" width="1.994" height="1.994" x="14.137" y="5.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".25"/></filter><filter id="iB1wUqd" width="1.794" height="1.794" x="9.845" y="5.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".2"/></filter><filter id="i2qe3Td" width="4.714" height="5.431" x="10.544" y="3.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="ivWrIEc" width="1.868" height="2.241" x="11.892" y="5.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".25"/></filter><filter id="iI8df9d" width="1.068" height="1.441" x="12.367" y="5.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".05"/></filter><filter id="iwMtkDd" width="1.928" height=".921" x="11.937" y="7.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".05"/></filter><filter id="imnKKOc" width="1.496" height=".595" x="13.229" y="5.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="izT5gsd" width="1.496" height=".595" x="11.077" y="5.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="ijJe7od" width="1.242" height=".612" x="11.139" y="4.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="ifDe93b" width="1.242" height=".612" x="13.645" y="4.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><filter id="ifocYDt" width=".471" height=".43" x="13.517" y="5.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".05"/></filter><filter id="i28Y5Ad" width=".627" height=".637" x="13.852" y="5.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".1"/></filter><filter id="ivdIfGd" width=".671" height=".696" x="11.797" y="5.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".1"/></filter><filter id="iHPotnb" width=".53" height=".433" x="11.501" y="5.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".05"/></filter><filter id="iZFoE6c" width="1.068" height=".475" x="13.648" y="4.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".05"/></filter><filter id="iRkWQWb" width="1.068" height=".475" x="11.126" y="4.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".05"/></filter><filter id="ihcPYEd" width="4.251" height="2.793" x="11.273" y="2.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/><feGaussianBlur result="effect2_foregroundBlur_3987_23236" stdDeviation=".075"/></filter><filter id="i1DjlBb" width="2.779" height="1.366" x="12.729" y="3.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23236" stdDeviation=".125"/></filter><filter id="ilZYcwe" width="1.556" height=".709" x="11.037" y="3.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.345098 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23236"/></filter><linearGradient id="iFEAkTd" x1="15.072" x2="11.924" y1="2.84" y2="8.671" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iCXpP7L" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="q2zf-acki"/><stop offset="1" class="wrgoaxbaa"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="i136FHe" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ivbdbpjuw"/><stop offset="1" class="zovioqy4e"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iQBvayU" x1="18.384" x2="14.604" y1="15.165" y2="16.372" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uov-5vb3w"/><stop offset="1" class="mzo6olgul"/></linearGradient><linearGradient id="iTq8DLc" x1="9.989" x2="11.358" y1="6.097" y2="6.097" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="i5pho2d" x1="12.467" x2="12.901" y1="6.672" y2="6.672" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iBssYqc" x1="12.901" x2="12.901" y1="7.042" y2="6.76" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iMesCgd" x1="12.409" x2="12.622" y1="7.694" y2="7.365" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="iUCcnyc" x1="14.27" x2="14.125" y1="5.805" y2="5.895" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHT6AQc" x1="12.236" x2="12.091" y1="5.805" y2="5.895" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bouncing-ball-light" /></template>
<style>
.a1qou1bcx {
  d: path("M12.268 5.924c0-.133-.109-.222-.138-.25l-.133.13l.082.167z");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.awz-49rkh {
  d: path("M10.742 6.553a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.b1kvifv3j {
  stop-color: var(--svg-color--8668c7, #8668C7);
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

.b24nyubzn {
  d: path("M14.28 5.918a.4.4 0 0 0-.108-.214l-.12.132l.054.106z");
}

.b39b9ipgf {
  fill: var(--svg-color--ffddc4, #FFDDC4);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.biy3jzpmj {
  stop-color: var(--svg-color--daa490, #DAA490);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.btsp6rbtk {
  stop-color: var(--svg-color--fec8b8, #FEC8B8);
}

.c_xsycbdz {
  stop-color: var(--svg-color--e2ac91, #E2AC91);
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
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

.csiv6mb3v {
  d: path("M12.622 2.453c-.524-.116-.995.407-1.049.6c.487 1.64 1.718 1.55 2.933 1.416c.727-.081.806.25.868.41c0-1.819-1.547-2.16-2.739-2.423z");
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d7rccub7n {
  stop-color: var(--svg-color--d08776, #D08776);
  stop-opacity: 0;
}

.dc-w_nb2z {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.255");
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.dqo8dqb7t {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M12.901 7.403a1.4 1.4 0 0 1-.658-.16c-.065-.033-.134.042-.094.102a.894.894 0 0 0 1.504 0c.04-.062-.03-.135-.094-.101a1.4 1.4 0 0 1-.658.16");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e085m5ymq {
  stop-color: var(--svg-color--f3beac, #F3BEAC);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.eiwjo5bgy {
  d: path("M10.548 5.472h.005l-.004-.122l-.005-.142c.01-.439.265-.609.375-.665l.023-.01l.024-.01c.247-.113.446-.31.55-.57l.038-.09a.122.122 0 0 1 .214-.024c.332.487.887.774 1.475.774h1.49c.083 0 .5.04.525.617l-.055 1.421c-.057 1.297-1.07 2.167-2.305 2.167s-2.248-.87-2.305-2.167z");
}

.env4r_bwx {
  stop-color: var(--svg-color--966bb1, #966BB1);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.fc917gbph {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.fs9onubla {
  fill-rule: evenodd;
  d: path("M16.225 6.709a1.52 1.52 0 0 0 .026-1.264h.002a1.5 1.5 0 0 0-.13-.238l-.001-.001a1.5 1.5 0 0 1-.244-.82v-.004c0-.843-.683-1.526-1.526-1.526a.25.25 0 0 1-.21-.108a1.53 1.53 0 0 0-2.482 0a.26.26 0 0 1-.21.108h-.04a1.526 1.526 0 0 0-1.486 1.526v.005c0 .29-.085.575-.244.819v.002a1.53 1.53 0 0 0-.103 1.5a.24.24 0 0 1 0 .211a1.486 1.486 0 0 0 1.339 2.14h3.97a1.486 1.486 0 0 0 1.339-2.14a.24.24 0 0 1 0-.21m-5.672-1.237h-.005l.554 1.09c.057 1.296.563 0 1.799 0s1.774 1.443 1.832.147l.525-1.48c-.025-.575-.442-.616-.525-.616h-1.49a1.79 1.79 0 0 1-1.475-.774a.122.122 0 0 0-.214.024l-.038.09a1.07 1.07 0 0 1-.574.58l-.023.01c-.11.056-.366.226-.375.665l.005.142z");
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.ga-j-qbpm {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.06c.12-.109.433-.272.71-.06c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gug6nq90d {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m14.627 5.022l-.064.107za.124.124 0 0 1-.127.213h-.002l-.01-.006l-.043-.022a1 1 0 0 0-.158-.062a1.05 1.05 0 0 0-.496-.043a.124.124 0 0 1-.043-.244c.237-.042.457 0 .614.05a1.5 1.5 0 0 1 .259.11l.004.003z");
}

.hgf77-wwh {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.798 4.959c.15-.036.52-.018.768.16");
}

.hhvxh5bcs {
  stop-color: var(--svg-color--cb766a, #CB766A);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hss_kmoqc {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.901 7.403a1.4 1.4 0 0 1-.658-.16c-.065-.033-.134.042-.094.102a.894.894 0 0 0 1.504 0c.04-.062-.03-.135-.094-.101a1.4 1.4 0 0 1-.658.16Z");
}

.htgi_9ynt {
  d: path("M15.134 6.8a.744.744 0 1 0 0-1.488a.744.744 0 0 0 0 1.489");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i1mrv7bgu {
  stop-color: var(--svg-color--df968d, #DF968D);
  stop-opacity: 0;
}

.i8abrhump {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.33 5.234l-.003.001a.124.124 0 0 1-.127-.213h.002l.004-.003l.015-.009l.054-.027c.045-.022.11-.05.19-.075c.157-.05.377-.092.614-.05a.124.124 0 0 1-.043.244a1.05 1.05 0 0 0-.496.043a1.3 1.3 0 0 0-.2.084z");
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.ijpnedbmt {
  cx: 11.766px;
  cy: 5.736px;
  rx: 0.18px;
  ry: 0.091px;
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iuch0hb0l {
  stop-color: var(--svg-color--b4807e, #B4807E);
}

.iv-u_b8_r {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.ivbdbpjuw {
  stop-color: var(--svg-color--614a93, #614A93);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.jfk78yx3r {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.k_ltadprl {
  stop-color: var(--svg-color--ffcebb, #FFCEBB);
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kl-0efb1i {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.045 4.959a1.1 1.1 0 0 0-.769.16");
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l4-oj3bqy {
  cx: 11.766px;
  cy: 5.736px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.18px;
  ry: 0.091px;
}

.l4f1npbvr {
  fill: var(--svg-color--ffcaaf, #FFCAAF);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9sedbbgz {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M10.742 6.553a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk1-k5bve {
  stop-color: var(--svg-color--f3bda8, #F3BDA8);
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m_p65hrmz {
  fill: var(--svg-color--000, #000);
  d: path("M12.127 5.972a.235.235 0 0 0-.236-.236a.235.235 0 0 0-.21.345h.418a.23.23 0 0 0 .028-.109");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mid6c9bnp {
  stop-color: var(--svg-color--bc818e, #BC818E);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mqd1-3r2u {
  fill: var(--svg-color--ffdec5, #FFDEC5);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzo6olgul {
  stop-color: var(--svg-color--8568c5, #8568C5);
  stop-opacity: 0;
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.ngj-91f4z {
  fill: var(--svg-color--272528, #272528);
  d: path("M12.373 5.793c-.123-.216-.31-.386-.711-.386a.77.77 0 0 0-.497.17c-.124.1-.107.23-.011.278L11.41 6c.302-.097.635-.11.962-.208");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nkhjpg89n {
  stop-color: var(--svg-color--cd8f76, #CD8F76);
  stop-opacity: 0;
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o-zx5tgee {
  d: path("M13.911 5.56a.413.413 0 0 1 .398.521h-.797a.414.414 0 0 1 .4-.522");
}

.o266gvb-m {
  d: path("M11.89 5.56a.413.413 0 0 0-.397.521h.797a.416.416 0 0 0-.4-.522");
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
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

.onfgb5bvd {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
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

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.q2zf-acki {
  stop-color: var(--svg-color--c28895, #C28895);
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qip0gxafn {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M13.43 5.793c.122-.216.309-.386.71-.386c.176 0 .346.049.497.17c.124.1.107.23.011.278L14.391 6c-.302-.097-.635-.11-.962-.208");
}

.qk70xkspj {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rc4cqmd1y {
  d: path("M13.881 5.647c.03.04-.032.087-.102.14c-.07.052-.122.089-.151.05c-.03-.04.003-.114.073-.167c.07-.052.15-.062.18-.023");
}

.rf25mcqqf {
  fill: var(--svg-color--fac6ad, #FAC6AD);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.rfjmiv-1j {
  fill: var(--svg-color--9f97a6, #9F97A6);
  d: path("M12.593 4.496h-1.556c.214-.12.386-.305.48-.54l.04-.092a.124.124 0 0 1 .216-.024c.204.3.492.525.82.656");
}

.rp58g3bju {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.795 5.434a.646.646 0 0 0-.627.49c-.02.08.042.157.124.157h1.032c.066 0 .118-.06.105-.125a.65.65 0 0 0-.634-.522");
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.s515o6bjz {
  stop-color: var(--svg-color--bc818e, #BC818E);
  stop-opacity: 0;
}

.sa6pubcic {
  stop-color: var(--svg-color--8466c4, #8466C4);
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

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.spg8_pgop {
  stop-color: var(--svg-color--966bb1, #966BB1);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t_lsdxbeo {
  fill: var(--svg-color--000, #000);
  d: path("M13.675 5.972c0-.13.105-.236.236-.236a.235.235 0 0 1 .21.345h-.418a.2.2 0 0 1-.028-.109");
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

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tfa_5nb_n {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M12.622 2.453c-.524-.116-.995.407-1.049.6c.487 1.64 1.718 1.55 2.933 1.416c.727-.081.806.25.868.41c0-1.819-1.547-2.16-2.739-2.423z");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tmtee3wvy {
  fill: var(--svg-color--876cc6, #876CC6);
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tsvq44-rv {
  stop-color: var(--svg-color--fdc9b0, #FDC9B0);
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.ttc09ac2m {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m12.724 5.89l-.246.786a.25.25 0 0 0 .241.323h.364a.25.25 0 0 0 .24-.323l-.245-.787c-.053-.174-.299-.174-.354 0");
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uov-5vb3w {
  stop-color: var(--svg-color--9782d0, #9782D0);
}

.uwn_p0-dn {
  stop-color: var(--svg-color--8366c4, #8366C4);
}

.v_thlccbr {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
  stop-opacity: 0;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vdxi4tb1n {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m12.72 5.953l-.317.787a.25.25 0 0 0 .241.323h.364a.25.25 0 0 0 .24-.323l-.245-.787c-.053-.174-.228-.174-.284 0");
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vrhnsgvqh {
  stop-color: var(--svg-color--cd9897, #CD9897);
  stop-opacity: 0;
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w__bqyylv {
  stop-color: var(--svg-color--8768cb, #8768CB);
}

.w_rrm9a7q {
  stop-color: var(--svg-color--d08776, #D08776);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.w7i-mnc1w {
  d: path("M10.734 6.8a.744.744 0 1 0 0-1.488a.744.744 0 0 0 0 1.489");
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wrgoaxbaa {
  stop-color: var(--svg-color--f2bdaa, #F2BDAA);
  stop-opacity: 0;
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x_0va9b6r {
  d: path("m12.724 5.89l-.246.786a.25.25 0 0 0 .241.323h.364a.25.25 0 0 0 .24-.323l-.245-.787c-.053-.174-.299-.174-.354 0");
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9p39bpy {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.881 5.647c.03.04-.032.087-.102.14c-.07.052-.122.089-.151.05c-.03-.04.003-.114.073-.167c.07-.052.15-.062.18-.023");
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xnhmgtb4v {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M15.134 6.553a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.ycl44mqxw {
  stop-color: var(--svg-color--f6b7a5, #F6B7A5);
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yvgme-ued {
  stop-color: var(--svg-color--f3c2a5, #F3C2A5);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z93iw6sik {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.007 5.434c.302 0 .557.208.627.49a.127.127 0 0 1-.124.157h-1.032a.106.106 0 0 1-.105-.125a.65.65 0 0 1 .634-.522");
}

.za4q5931x {
  d: path("M15.134 6.553a.497.497 0 1 0 0-.993a.497.497 0 0 0 0 .993");
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zh-mcpham {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m14.014 4.122l-.66.122a.318.318 0 1 1-.057-.632h1.083c.64 0 .852.646.878.866a1.46 1.46 0 0 0-1.244-.356");
}

.zovioqy4e {
  stop-color: var(--svg-color--614a93, #614A93);
  stop-opacity: 0;
}

.zvhlj4t4z {
  stop-color: var(--svg-color--df968d, #DF968D);
}

</style>
