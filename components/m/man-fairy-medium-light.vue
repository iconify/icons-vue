<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i42aOqb)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iTiDOUc)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iFHDcdd)"><path fill="url(#i5I72Pc)" class="pb1pwib-r"/><path fill="url(#iX1BTZW)" class="pb1pwib-r"/></g><g filter="url(#iyKIrvc)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#iMLAdRb)"><path class="t6m6gnbiw"/></g><g filter="url(#ihfvwHb)"><path class="yn_cprukr"/></g><g filter="url(#iFFjWod)"><path class="y3su9tbbh"/></g><g filter="url(#iJXYjCj)"><path class="a48brs4te"/></g><g filter="url(#i0zLAYd)"><rect class="r9m8_svvg"/><rect fill="url(#iVtR9se)" class="nl4f7twra"/></g><g filter="url(#iUuzo3b)"><path fill="url(#ioitlCc)" class="t16p7zajb"/></g><path fill="url(#i5Ao9Gd)" class="t16p7zajb"/><path fill="url(#i8KfH3d)" class="t16p7zajb"/><path fill="url(#iEdEbnd)" class="t16p7zajb"/><path class="ls3dj269w"/><path fill="url(#iGgZmQl)" class="usyhe_b6f"/><path fill="url(#iVakvLc)" class="usyhe_b6f"/><path fill="url(#i3gy0Bb)" class="usyhe_b6f"/><path fill="url(#iuPT4Kc)" class="usyhe_b6f"/><path fill="url(#iHyYx2b)" class="usyhe_b6f"/><path class="e593k4bfv"/><path fill="url(#i7QnpSd)" class="xhtzkfsjn"/><path fill="url(#iJU4nte)" class="xhtzkfsjn"/><path fill="url(#iXN23Fe)" class="fwk98bb0c"/><path fill="url(#iZZHFob)" class="fwk98bb0c"/><path fill="url(#ipeBQ4W)" class="fwk98bb0c"/><path fill="url(#i9gr8ye)" class="fwk98bb0c"/><path fill="url(#iR15onA)" class="hxm_1sbuv"/><path fill="url(#iDv7Hjb)" class="hxm_1sbuv"/><g filter="url(#ipKgWOe)"><path class="itxwdgbfi"/><path fill="url(#i9oHjLb)" class="ajsjeuojy"/><path fill="url(#i4dGyFe)" class="ajsjeuojy"/></g><path fill="url(#i582tNc)" class="ajsjeuojy"/><path fill="url(#iFc3g8a)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#iRTRGab)" class="z30kudb-o"/><g filter="url(#iltuBkc)"><path class="ryg6lupnq"/><path fill="url(#isMzgCc)" class="uu9c01xwt"/><path fill="url(#i8nGM4b)" class="uu9c01xwt"/></g><g filter="url(#idNNPRI)"><path class="a82m64rdy"/><path fill="url(#iF2AuEd)" class="re9d71n0d"/><path fill="url(#ibLg2rc)" class="re9d71n0d"/></g><g filter="url(#iHL8Xie)"><path class="aad0dq7pt"/></g><path fill="url(#iibaBhb)" class="ot6al4ozs"/><path fill="url(#iyoQqAI)" class="ot6al4ozs"/><path fill="url(#ife8frc)" class="ot6al4ozs"/><path fill="url(#igL6tRj)" class="ot6al4ozs"/><path fill="url(#igfTLWf)" class="ot6al4ozs"/><path fill="url(#ilcSyhe)" class="ot6al4ozs"/><path fill="url(#ipUxtZd)" class="ot6al4ozs"/><path fill="url(#iFIvgLd)" class="gdfj27b8p"/><path fill="url(#ix6pMBc)" class="gdfj27b8p"/><g filter="url(#icYy4Oc)"><path stroke="url(#i779sXb)" class="saunobcmg"/></g><g filter="url(#iUaiBeb)"><path stroke="url(#iLaN8ob)" class="ikgkim2qs"/></g><g filter="url(#iqzy6Kd)"><path stroke="url(#i80JVOe)" class="zh46g387g"/></g><g filter="url(#iWB0lbl)"><circle fill="url(#ibQv1Je)" class="l-fe1bcgi"/></g><g filter="url(#ihuLqPe)"><circle fill="url(#izCYhYb)" class="d_f4xp3-a"/></g><g filter="url(#ia3lkGe)"><circle fill="url(#iDsTTTb)" class="s104-_bfp"/><circle fill="url(#iIsYa6c)" class="s104-_bfp"/></g><g filter="url(#ixnHhdd)"><circle class="gac22abyi"/><circle fill="url(#iX36jLc)" class="irft1t0mc"/><circle fill="url(#ii2Y4kd)" class="irft1t0mc"/></g><g filter="url(#iAMnhhb)"><path fill="url(#iEj5i1d)" class="h5tvtwd-v"/><path fill="url(#iDXkwQb)" class="h5tvtwd-v"/><path fill="url(#ics0VBd)" class="h5tvtwd-v"/><path fill="url(#ipAoXhc)" class="h5tvtwd-v"/><path fill="url(#iFXC66d)" class="h5tvtwd-v"/></g><g filter="url(#iA6G9xc)"><path class="luj3j-bkc"/><path fill="url(#iLApLcv)" class="s2dg7xxyl"/><path fill="url(#iooBLyf)" class="s2dg7xxyl"/><path fill="url(#iGp8Myb)" class="s2dg7xxyl"/><path fill="url(#ijOTGfc)" class="s2dg7xxyl"/><path fill="url(#igfgFnb)" class="s2dg7xxyl"/></g><path fill="url(#ir8x1hd)" class="s2dg7xxyl"/><path fill="url(#i2diWke)" class="s2dg7xxyl"/><g filter="url(#i1i8zmb)"><path class="udoen0bpu"/></g><g filter="url(#iQQvdRd)"><path class="d66avuhaq"/><path fill="url(#i4taz0d)" class="u16ahzmuw"/><path fill="url(#izDQhBb)" class="u16ahzmuw"/><path fill="url(#iT8sf6d)" class="u16ahzmuw"/></g><path stroke="url(#iwnVqnd)" class="pxkdoebyw"/><g filter="url(#iH8EJRb)"><path class="kycw-yqih"/></g><g filter="url(#ieduzZb)"><path class="i_nzxh5fq"/></g><path class="t3b-m7bch"/><path fill="url(#iycWkgc)" class="vxsr-abqz"/><path class="ygodmjpra"/><g filter="url(#i5GDH9b)"><path class="s5yaq9nxj"/><path fill="url(#ixVC2Sb)" class="rv2ir0b2w"/></g><g filter="url(#iGkY81c)"><path fill="url(#iaxdjPc)" class="agt527bqj"/></g><path class="ctn38t5gc"/><path fill="url(#i3pf8Yb)" class="in6levbzf"/><path class="on0_opbcf"/><g filter="url(#ilBHoce)"><path fill="url(#iLwE7rb)" class="oswr96lht"/></g><g filter="url(#iUOH5re)"><ellipse transform="rotate(-27.914 14.894 7.598)" class="jkjcg6pqd"/><ellipse fill="url(#iQUNDvc)" transform="rotate(-27.914 14.894 7.598)" class="j1kcmjb-c"/></g><g filter="url(#ipVFbse)"><path stroke="url(#iTo895b)" class="gq7fm2bhe"/></g><g filter="url(#iL7hQGs)"><path stroke="url(#iDon6Nd)" class="z7v7wpmwi"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="i5Ao9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.216 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iVakvLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68754 -5.0625 2.53124 -.34377 16.78 21.98)" gradientUnits="userSpaceOnUse"><stop class="uvyxh01-z"/><stop offset="1" class="u2p7zvbzn"/></radialGradient><radialGradient id="i3gy0Bb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.125 15.9 2.484)scale(.88884 .66004)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="kcor2lvvo"/><stop offset="1" class="t0dfidbsh"/></radialGradient><radialGradient id="iHyYx2b" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 -4.56052 .72812 .03493 14.75 21.79)" gradientUnits="userSpaceOnUse"><stop class="ywk-_ln5y"/><stop offset="1" class="quxai4aum"/></radialGradient><radialGradient id="ipeBQ4W" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.09375 -.85026 -.073 15.348 26.277)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="k6zy9n07l"/><stop offset="1" class="m22s2i1fh"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="i4dGyFe" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.80469 -.96535 .25074 19.32 20.568)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="s-dztxv8u"/><stop offset="1" class="wm2hnkwbm"/></radialGradient><radialGradient id="i582tNc" cx="0" cy="0" r="1" gradientTransform="matrix(.71094 .34759 -.96823 1.98037 16.606 23.744)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="dvlr87bav"/><stop offset="1" class="h2aikfbxt"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iRTRGab" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="md09g_bwr"/><stop offset="1" class="vudwjbw9p"/></radialGradient><radialGradient id="isMzgCc" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.875 -1.302)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="n6c_0ja6r"/><stop offset="1" class="sxlwo8bvv"/></radialGradient><radialGradient id="i8nGM4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.94747 2.72 -.8954 -.3119 13.593 13.469)" gradientUnits="userSpaceOnUse"><stop class="p77zblbaj"/><stop offset="1" class="gvz69mboo"/></radialGradient><radialGradient id="iF2AuEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="z1f5d8bxu"/><stop offset="1" class="s8gxoccyp"/></radialGradient><radialGradient id="ibLg2rc" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="t_55psbku"/><stop offset="1" class="bwfo2x8_b"/></radialGradient><radialGradient id="ife8frc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92712 .2574 -.06658 -.49847 15.184 10.717)" gradientUnits="userSpaceOnUse"><stop class="ptfvfcbrt"/><stop offset="1" class="c9v8_hpvm"/></radialGradient><radialGradient id="igL6tRj" cx="0" cy="0" r="1" gradientTransform="rotate(142.326 7.14 8.85)scale(1.55953 .89404)" gradientUnits="userSpaceOnUse"><stop class="y39x50mqx"/><stop offset="1" class="gmn2w47zp"/></radialGradient><radialGradient id="igfTLWf" cx="0" cy="0" r="1" gradientTransform="matrix(1.67188 0 0 .4274 16.833 10.717)" gradientUnits="userSpaceOnUse"><stop class="nkm4r8_8f"/><stop offset="1" class="e2kf81bwk"/></radialGradient><radialGradient id="iFIvgLd" cx="0" cy="0" r="1" gradientTransform="rotate(62.33 -1.095 17.766)scale(1.17765 2.48248)" gradientUnits="userSpaceOnUse"><stop class="q_i4prb1m"/><stop offset="1" class="osml3-ahx"/></radialGradient><radialGradient id="ix6pMBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95899 .51766 -.25276 -.46825 16.987 10.665)" gradientUnits="userSpaceOnUse"><stop class="sb6wk2byh"/><stop offset="1" class="oh250pbjd"/></radialGradient><radialGradient id="ibQv1Je" cx="0" cy="0" r="1" gradientTransform="matrix(.76217 0 0 1.3338 13.173 7.936)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iIsYa6c" cx="0" cy="0" r="1" gradientTransform="matrix(.35905 -.26144 .2984 .40981 18.192 7.821)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iX36jLc" cx="0" cy="0" r="1" gradientTransform="matrix(.35669 -.65605 .38399 .20877 18.012 8.293)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="ii2Y4kd" cx="0" cy="0" r="1" gradientTransform="matrix(.11261 .11147 -.1437 .14517 18.03 7.936)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iDXkwQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.63424 -5.66522 0 16.165 6.485)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset=".941" class="cu6ku4-xh"/></radialGradient><radialGradient id="ipAoXhc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56769 .69869 0 16.98 7.384)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iFXC66d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60408 .75122 0 15 7.37)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iLApLcv" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 7.659 6.595)scale(2.43486 4.14069)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iGp8Myb" cx="0" cy="0" r="1" gradientTransform="matrix(-.02902 -.80847 .39705 -.01425 14.14 6.435)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="ijOTGfc" cx="0" cy="0" r="1" gradientTransform="matrix(.37314 -.85408 .69656 .30432 17.796 7.182)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="igfgFnb" cx="0" cy="0" r="1" gradientTransform="matrix(.43118 .53502 -.47238 .3807 15.624 4.2)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="ir8x1hd" cx="0" cy="0" r="1" gradientTransform="matrix(.07878 .34016 -.55922 .1295 16.263 4.2)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="i2diWke" cx="0" cy="0" r="1" gradientTransform="matrix(.3151 .38972 -.87322 .70601 14.073 4.951)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="iycWkgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39226 -.46414 0 16.907 7.785)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ixVC2Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1007 -.12977 .17866 -.13864 16.808 7.676)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3pf8Yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39227 -.46416 0 15.012 7.785)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iQUNDvc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.251 -3.46)scale(.21457 .25791)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="i5I72Pc" x1="8.528" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="iVtR9se" x1="22.919" x2="22.549" y1="5.345" y2="6.132" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="iGgZmQl" x1="13.264" x2="15.031" y1="19.026" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="i7ccoc8qs"/><stop offset="1" class="waah2bcle"/></linearGradient><linearGradient id="iuPT4Kc" x1="19.343" x2="17.937" y1="18.573" y2="19.026" gradientUnits="userSpaceOnUse"><stop class="hnwux9dcc"/><stop offset="1" class="xsno6rw2t"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iXN23Fe" x1="15.288" x2="13.817" y1="25.263" y2="25.263" gradientUnits="userSpaceOnUse"><stop offset=".267" class="gvrh5ob2r"/><stop offset=".945" class="zx2ao6bwg"/></linearGradient><linearGradient id="iZZHFob" x1="15.46" x2="14.96" y1="26.669" y2="26.638" gradientUnits="userSpaceOnUse"><stop class="ff90ucc6c"/><stop offset="1" class="a5twm1ncx"/></linearGradient><linearGradient id="i9gr8ye" x1="13.261" x2="13.692" y1="25.667" y2="25.667" gradientUnits="userSpaceOnUse"><stop class="p5rcrxbls"/><stop offset="1" class="w4_s79ciy"/></linearGradient><linearGradient id="iR15onA" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="htqsm-l2e"/><stop offset=".159" class="zd1r_u8ze"/><stop offset=".453" class="x09-01b7i"/><stop offset="1" class="s_f01nb2h"/></linearGradient><linearGradient id="i9oHjLb" x1="18.825" x2="18.351" y1="24.378" y2="24.091" gradientUnits="userSpaceOnUse"><stop class="rr5fu4pew"/><stop offset="1" class="u39dyibqi"/></linearGradient><linearGradient id="iFc3g8a" x1="15.749" x2="17.116" y1="25.981" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="ilfb1o36w"/><stop offset="1" class="q6qjg9bpc"/></linearGradient><linearGradient id="iibaBhb" x1="16.019" x2="16.019" y1="10.717" y2="15.553" gradientUnits="userSpaceOnUse"><stop class="rlgwf126s"/><stop offset="1" class="l-4shobes"/></linearGradient><linearGradient id="iyoQqAI" x1="13.257" x2="15.446" y1="14.749" y2="14.749" gradientUnits="userSpaceOnUse"><stop offset=".01" class="jv6lqw6zm"/><stop offset="1" class="r3o1jnbex"/></linearGradient><linearGradient id="ilcSyhe" x1="18.583" x2="16.583" y1="15.238" y2="15.238" gradientUnits="userSpaceOnUse"><stop class="xxjj5obiq"/><stop offset="1" class="teavi7b3d"/></linearGradient><linearGradient id="ipUxtZd" x1="18.895" x2="18.442" y1="15.553" y2="15.553" gradientUnits="userSpaceOnUse"><stop class="ma_coc6av"/><stop offset="1" class="g9j7gtogb"/></linearGradient><linearGradient id="i779sXb" x1="22.63" x2="20.036" y1="11.605" y2="13.448" gradientUnits="userSpaceOnUse"><stop offset=".453" class="bi_gnlatu"/><stop offset="1" class="qqsiimfct"/></linearGradient><linearGradient id="iLaN8ob" x1="22.059" x2="21.755" y1="8.558" y2="10.249" gradientUnits="userSpaceOnUse"><stop class="opdu08blf"/><stop offset="1" class="t02y35b0p"/></linearGradient><linearGradient id="i80JVOe" x1="23.07" x2="22.804" y1="8.935" y2="9.896" gradientUnits="userSpaceOnUse"><stop class="opdu08blf"/><stop offset="1" class="t02y35b0p"/></linearGradient><linearGradient id="izCYhYb" x1="13.898" x2="13.62" y1="8.057" y2="8.057" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iDsTTTb" x1="18.502" x2="18.146" y1="7.462" y2="8.564" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iEj5i1d" x1="17.713" x2="14.396" y1="8.105" y2="8.599" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ics0VBd" x1="13.617" x2="14.621" y1="9.276" y2="9.145" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iooBLyf" x1="13.849" x2="15.11" y1="7.82" y2="5.581" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="i4taz0d" x1="15.585" x2="15.993" y1="8.392" y2="8.392" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="izDQhBb" x1="16.368" x2="15.922" y1="8.532" y2="8.525" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iT8sf6d" x1="16.045" x2="16.045" y1="8.854" y2="8.605" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iwnVqnd" x1="15.51" x2="15.699" y1="9.555" y2="9.257" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iaxdjPc" x1="17.244" x2="17.108" y1="7.663" y2="7.747" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLwE7rb" x1="15.335" x2="15.198" y1="7.663" y2="7.747" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTo895b" x1="17.251" x2="17.069" y1="6.734" y2="6.361" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iDon6Nd" x1="14.947" x2="14.431" y1="6.678" y2="6.462" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><filter id="i42aOqb" width="7.335" height="7.371" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1155" result="effect2_innerShadow_4002_1155"/></filter><filter id="iTiDOUc" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1155" result="effect2_innerShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1155" result="effect3_innerShadow_4002_1155"/></filter><filter id="iFHDcdd" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1155" result="effect2_innerShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1155" result="effect3_innerShadow_4002_1155"/></filter><filter id="iyKIrvc" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="iMLAdRb" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1155" result="effect2_dropShadow_4002_1155"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1155" result="shape"/></filter><filter id="ihfvwHb" width="6.45" height="6.548" x="9.619" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1155" result="effect2_dropShadow_4002_1155"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1155" result="shape"/></filter><filter id="iFFjWod" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1155" result="effect2_dropShadow_4002_1155"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1155" result="shape"/></filter><filter id="iJXYjCj" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1155" result="effect2_dropShadow_4002_1155"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1155" result="shape"/></filter><filter id="i0zLAYd" width="1.003" height="4.833" x="22.341" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="iUuzo3b" width="4.084" height="3.799" x="20.732" y="2.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="ipKgWOe" width="5.091" height="7.247" x="15.749" y="20.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.54902 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="iltuBkc" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.505882 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.454902 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1155" result="effect2_innerShadow_4002_1155"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.6 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1155" result="effect3_innerShadow_4002_1155"/></filter><filter id="idNNPRI" width="1.692" height="1.561" x="6.723" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.537255 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="iHL8Xie" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.466667 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="icYy4Oc" width="4.609" height="5.161" x="19.13" y="9.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".25"/></filter><filter id="iUaiBeb" width="1.248" height="2.077" x="21.759" y="8.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".1"/></filter><filter id="iqzy6Kd" width=".822" height="1.445" x="22.798" y="8.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".1"/></filter><filter id="iWB0lbl" width="1.65" height="1.45" x="13.173" y="7.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="ihuLqPe" width="1.864" height="1.864" x="12.966" y="7.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".25"/></filter><filter id="ia3lkGe" width="1.7" height="1.7" x="17.305" y="6.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="ixnHhdd" width="1.864" height="1.864" x="17.098" y="7.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".25"/></filter><filter id="iAMnhhb" width="4.505" height="5.274" x="13.72" y="5.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="iA6G9xc" width="5.473" height="3.993" x="13.224" y="3.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="i1i8zmb" width="2.264" height="2.664" x="14.725" y="7.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".375"/></filter><filter id="iQQvdRd" width=".915" height="1.264" x="15.503" y="7.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".025"/></filter><filter id="iH8EJRb" width="1.436" height="1.04" x="16.474" y="6.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="ieduzZb" width="1.436" height="1.04" x="14.238" y="6.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1155"/></filter><filter id="i5GDH9b" width=".455" height=".416" x="16.531" y="7.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".05"/></filter><filter id="iGkY81c" width=".613" height=".623" x="16.839" y="7.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".1"/></filter><filter id="ilBHoce" width=".655" height=".678" x="14.91" y="7.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".1"/></filter><filter id="iUOH5re" width=".51" height=".419" x="14.639" y="7.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".05"/></filter><filter id="ipVFbse" width="1.253" height=".637" x="16.456" y="6.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".075"/></filter><filter id="iL7hQGs" width="1.287" height=".662" x="14.19" y="6.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1155" stdDeviation=".075"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-fairy-medium-light" /></template>
<style>
.a48brs4te {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 1 1-.282-.312l4.235-3.836z");
}

.a5twm1ncx {
  stop-color: var(--svg-color--dea386, #DEA386);
  stop-opacity: 0;
}

.a82m64rdy {
  fill: var(--svg-color--daa788, #DAA788);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.128c.1.102.144.418-.094.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.aad0dq7pt {
  fill: var(--svg-color--dfa286, #DFA286);
  d: path("m21.499 12.27l-3.145-1.206l-.136 2.175l3.578 1.368c.185.083.651.2 1.039 0s.515-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0V8.51a.404.404 0 0 0-.805-.035c-.013.162-.03.366-.047.6c-.038.494.276.836.437.961z");
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.agt527bqj {
  d: path("M17.253 7.77a.37.37 0 0 0-.1-.202l-.114.124l.051.1z");
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ajsjeuojy {
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bi_gnlatu {
  stop-color: var(--svg-color--f6c1a2, #F6C1A2);
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bwfo2x8_b {
  stop-color: var(--svg-color--e0aa8f, #E0AA8F);
}

.c9v8_hpvm {
  stop-color: var(--svg-color--3f76a9, #3F76A9);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctn38t5gc {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.921 7.315a.61.61 0 0 0-.588.46a.12.12 0 0 0 .116.147h.969a.1.1 0 0 0 .099-.118a.61.61 0 0 0-.596-.49");
}

.cu6ku4-xh {
  stop-color: var(--svg-color--b97a7e, #B97A7E);
}

.d_f4xp3-a {
  cx: 13.898px;
  cy: 7.936px;
  r: 0.432px;
}

.d66avuhaq {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.794 7.812l-.23.738a.234.234 0 0 0 .226.304h.341c.16 0 .273-.154.226-.304l-.23-.738c-.05-.163-.28-.163-.333 0");
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dvlr87bav {
  stop-color: var(--svg-color--b88067, #B88067);
}

.e2kf81bwk {
  stop-color: var(--svg-color--4794c5, #4794C5);
  stop-opacity: 0;
}

.e593k4bfv {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.ff90ucc6c {
  stop-color: var(--svg-color--dea386, #DEA386);
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.ft5dv1b6b {
  fill: none;
}

.fwk98bb0c {
  d: path("m13.318 29.589l-.057-7.861l2.32.062l-.439 7.053a.47.47 0 0 1-.215.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.g9j7gtogb {
  stop-color: var(--svg-color--4db5ff, #4DB5FF);
  stop-opacity: 0;
}

.gac22abyi {
  cx: 18.03px;
  cy: 7.936px;
  r: 0.432px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.gdfj27b8p {
  d: path("M15.07 10.486v.349a.24.24 0 0 0 .065.157c.134.147.326.443.456.87c.06.195.232.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.456-.87a.24.24 0 0 0 .066-.157v-.35z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gmn2w47zp {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
  stop-opacity: 0;
}

.gq7fm2bhe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.682 6.692c.186-.033.55-.023.803.173");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gvrh5ob2r {
  stop-color: var(--svg-color--f4bba1, #F4BBA1);
}

.gvz69mboo {
  stop-color: var(--svg-color--ac596b, #AC596B);
  stop-opacity: 0;
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h2aikfbxt {
  stop-color: var(--svg-color--c6846b, #C6846B);
  stop-opacity: 0;
}

.h5tvtwd-v {
  d: path("M13.745 7.67h.022s-.024-.37-.047-.625c0-.116.047-.255.14-.324l.07-.07a.46.46 0 0 0 .163-.37v-.37c0-.117.07-.21.186-.232a7 7 0 0 1 1.7-.186c.84 0 1.422.116 1.701.186a.25.25 0 0 1 .187.231v.37c0 .14.07.279.163.371c.218.153.204.237.186.417a20 20 0 0 0-.046.626h.008l-.116 1.719c-.07.768-.674 1.304-1.394 1.304h-1.394c-.744 0-1.325-.536-1.395-1.304z");
}

.hnwux9dcc {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.htqsm-l2e {
  stop-color: var(--svg-color--664e86, #664E86);
}

.hxm_1sbuv {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231c.348-.125.845-.33 1.287-.603a.47.47 0 0 0 .216-.373l.054-.894z");
}

.i_nzxh5fq {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M14.321 6.755v-.001l.003-.002l.005-.004l.067-.047a1.23 1.23 0 0 1 .83-.16a.232.232 0 1 1-.072.458a.77.77 0 0 0-.512.095l-.023.016l-.004.003a.232.232 0 0 1-.295-.358");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i7ccoc8qs {
  stop-color: var(--svg-color--3968ab, #3968AB);
}

.ikgkim2qs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.06 8.558v.505a1 1 0 0 0 .433.824l.215.147");
}

.ilfb1o36w {
  stop-color: var(--svg-color--352b41, #352B41);
}

.in6levbzf {
  d: path("M15.01 7.433a.388.388 0 0 0-.373.49h.75a.39.39 0 0 0-.375-.49");
}

.irft1t0mc {
  cx: 18.03px;
  cy: 7.936px;
  r: 0.432px;
}

.itxwdgbfi {
  fill: var(--svg-color--e7ae99, #E7AE99);
  d: path("m17.672 21.275l-.082-.227l2.33-.48c.022.062.095.292.22.71c.125.42-.01.774-.094.899l-3.27 5.344c-.07.116-.232.128-.31.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.j1kcmjb-c {
  cx: 14.894px;
  cy: 7.598px;
  rx: 0.169px;
  ry: 0.086px;
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.jkjcg6pqd {
  cx: 14.894px;
  cy: 7.598px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.086px;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jv6lqw6zm {
  stop-color: var(--svg-color--4f6fa1, #4F6FA1);
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k6zy9n07l {
  stop-color: var(--svg-color--a87973, #A87973);
}

.kcor2lvvo {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kycw-yqih {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m17.576 6.755l-.002-.001l-.002-.002l-.005-.004l-.067-.047a1.23 1.23 0 0 0-.83-.16a.232.232 0 0 0 .072.458a.77.77 0 0 1 .512.095l.024.016l.003.003a.232.232 0 0 0 .295-.358");
}

.l-4shobes {
  stop-color: var(--svg-color--358dea, #358DEA);
}

.l-fe1bcgi {
  cx: 13.898px;
  cy: 7.936px;
  r: 0.725px;
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls3dj269w {
  fill: var(--svg-color--3c8aea, #3C8AEA);
  d: path("M13.264 21.733V16.26l5.528.056c0 .348.063.666.09.765l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.luj3j-bkc {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m18.053 5.123l.187.092a.854.854 0 0 1 .442.927l-.256 1.32c-.023.137-.113.228-.248.232h-.008s.023-.394.046-.626c.02-.188-.014-.245-.186-.417a.55.55 0 0 1-.163-.37v-.37a.25.25 0 0 0-.187-.232a7 7 0 0 0-1.7-.186c-.839 0-1.421.116-1.7.186a.226.226 0 0 0-.187.231v.37a.46.46 0 0 1-.163.371l-.07.07c-.093.07-.14.208-.14.324c.023.255.047.626.047.626l-.022-.001a.275.275 0 0 1-.258-.231l-.256-1.32a.89.89 0 0 1 .466-.904l.186-.092c.117-.07.233-.163.35-.255l.419-.44a.85.85 0 0 1 .955-.14c.233.07.49.07.722 0a1.05 1.05 0 0 1 1.025.232l.35.348c.093.116.21.185.35.255");
}

.m22s2i1fh {
  stop-color: var(--svg-color--d7a18a, #D7A18A);
  stop-opacity: 0;
}

.ma_coc6av {
  stop-color: var(--svg-color--51a3e8, #51A3E8);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md09g_bwr {
  stop-color: var(--svg-color--dc9f87, #DC9F87);
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n6c_0ja6r {
  stop-color: var(--svg-color--bc826b, #BC826B);
  stop-opacity: 0;
}

.nkm4r8_8f {
  stop-color: var(--svg-color--4780ac, #4780AC);
}

.nl4f7twra {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  rx: 0.352px;
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh250pbjd {
  stop-color: var(--svg-color--df9e84, #DF9E84);
  stop-opacity: 0;
}

.on0_opbcf {
  fill: var(--svg-color--000, #000);
  d: path("M15.233 7.82a.22.22 0 0 0-.222-.222a.22.22 0 0 0-.197.324h.392a.2.2 0 0 0 .027-.102");
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.opdu08blf {
  stop-color: var(--svg-color--d5a38f, #D5A38F);
}

.osml3-ahx {
  stop-color: var(--svg-color--e1a891, #E1A891);
}

.oswr96lht {
  d: path("M15.365 7.775c0-.125-.102-.209-.13-.234l-.125.12l.077.158z");
}

.ot6al4ozs {
  d: path("M16.006 10.718c-.438.015-1.42.083-1.985.163c-.721.101-.764.71-.764.992v3.68h5.524v-3.68c0-.281-.043-.89-.764-.992a25 25 0 0 0-1.985-.163z");
}

.p5rcrxbls {
  stop-color: var(--svg-color--e1a58b, #E1A58B);
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p77zblbaj {
  stop-color: var(--svg-color--ac596b, #AC596B);
}

.pb1pwib-r {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .005-4.88a3.454 3.454 0 0 1 4.881-.006l1.19 1.19c.337.337.601.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.ptfvfcbrt {
  stop-color: var(--svg-color--435e8c, #435E8C);
}

.pxkdoebyw {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.69 9.271a.11.11 0 0 0-.013-.14a.12.12 0 0 0-.138-.023a1.25 1.25 0 0 1-.579.137c-.212 0-.412-.05-.578-.137a.12.12 0 0 0-.139.024a.11.11 0 0 0-.012.14m1.458 0l-.041-.028l.041.027Zm0 0a.87.87 0 0 1-.729.389a.87.87 0 0 1-.729-.39m0 0v.001l.042-.028m-.042.027l.042-.027m0 0c.145.22.399.367.687.367a.82.82 0 0 0 .688-.367c.037-.057-.027-.121-.086-.091a1.3 1.3 0 0 1-.602.142a1.3 1.3 0 0 1-.601-.142c-.06-.03-.124.037-.086.09Z");
}

.q_i4prb1m {
  stop-color: var(--svg-color--d08a70, #D08A70);
}

.q6qjg9bpc {
  stop-color: var(--svg-color--64468a, #64468A);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qqsiimfct {
  stop-color: var(--svg-color--f6c1a2, #F6C1A2);
  stop-opacity: 0;
}

.quxai4aum {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r3o1jnbex {
  stop-color: var(--svg-color--3391ee, #3391EE);
  stop-opacity: 0;
}

.r9m8_svvg {
  width: 0.703px;
  height: 4.633px;
  x: 22.341px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.352px;
}

.re9d71n0d {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.638-.217.724-.128c.1.102.144.418-.094.695c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.013-.561.257-.764");
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rlgwf126s {
  stop-color: var(--svg-color--43abff, #43ABFF);
}

.rr5fu4pew {
  stop-color: var(--svg-color--dba697, #DBA697);
}

.rv2ir0b2w {
  d: path("M16.879 7.515c.028.037-.03.082-.096.13c-.065.05-.114.084-.142.047s.004-.106.07-.155c.065-.05.14-.06.168-.022");
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.ryg6lupnq {
  fill: var(--svg-color--e1ab90, #E1AB90);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s_f01nb2h {
  stop-color: var(--svg-color--4b3866, #4B3866);
}

.s-dztxv8u {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
}

.s104-_bfp {
  cx: 18.03px;
  cy: 7.936px;
  r: 0.725px;
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s2dg7xxyl {
  d: path("m18.053 5.123l.187.092a.854.854 0 0 1 .442.927l-.256 1.32c-.023.137-.113.228-.248.232h-.008s.023-.394.046-.626c.02-.188-.014-.245-.186-.417a.55.55 0 0 1-.163-.37v-.37a.25.25 0 0 0-.187-.232a7 7 0 0 0-1.7-.186c-.839 0-1.421.116-1.7.186a.226.226 0 0 0-.187.231v.37a.46.46 0 0 1-.163.371l-.07.07c-.093.07-.14.208-.14.324c.023.255.047.626.047.626l-.022-.001a.275.275 0 0 1-.258-.231l-.256-1.32a.89.89 0 0 1 .466-.904l.186-.092c.117-.07.233-.163.35-.255l.419-.44a.85.85 0 0 1 .955-.14c.233.07.49.07.722 0a1.05 1.05 0 0 1 1.025.232l.35.348c.093.116.21.185.35.255");
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s5yaq9nxj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.879 7.515c.028.037-.03.082-.096.13c-.065.05-.114.084-.142.047s.004-.106.07-.155c.065-.05.14-.06.168-.022");
}

.s8gxoccyp {
  stop-color: var(--svg-color--edba9f, #EDBA9F);
  stop-opacity: 0;
}

.saunobcmg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.88 12.667l2.672 1.045a.1.1 0 0 0 .136-.085l.301-3.57");
}

.sb6wk2byh {
  stop-color: var(--svg-color--df9e84, #DF9E84);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sxlwo8bvv {
  stop-color: var(--svg-color--bc826b, #BC826B);
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t_55psbku {
  stop-color: var(--svg-color--e0aa8f, #E0AA8F);
  stop-opacity: 0;
}

.t02y35b0p {
  stop-color: var(--svg-color--d5a38f, #D5A38F);
  stop-opacity: 0;
}

.t0dfidbsh {
  stop-color: var(--svg-color--3f63e1, #3F63E1);
  stop-opacity: 0;
}

.t16p7zajb {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .128.376l-.734.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.32.237l-.863-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.t3b-m7bch {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.998 7.315c.283 0 .523.195.588.46a.12.12 0 0 1-.116.147h-.97a.1.1 0 0 1-.098-.118c.055-.278.3-.49.595-.49");
}

.t6m6gnbiw {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 0 0-.284.31l1.82 1.668l-.84.085a.21.21 0 0 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.teavi7b3d {
  stop-color: var(--svg-color--3b9bf4, #3B9BF4);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u16ahzmuw {
  d: path("m15.794 7.812l-.23.738a.234.234 0 0 0 .226.304h.341c.16 0 .273-.154.226-.304l-.23-.738c-.05-.163-.28-.163-.333 0");
}

.u2p7zvbzn {
  stop-color: var(--svg-color--2851b6, #2851B6);
  stop-opacity: 0;
}

.u39dyibqi {
  stop-color: var(--svg-color--dba697, #DBA697);
  stop-opacity: 0;
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.udoen0bpu {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.84 7.883l-.355.738c-.045.152.061.304.212.304h.32c.15 0 .256-.154.212-.304l-.217-.738c-.046-.164-.123-.164-.171 0");
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.usyhe_b6f {
  d: path("M13.264 21.733V16.26l5.528.056c0 .348.063.666.09.765l1.042 3.486l-2.33.484l-.864-2.223c-.133-.336-.286-.64-.505-.64c-.25 0-.356.391-.361.59l-.279 3.011z");
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uu9c01xwt {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.561c.558-1.026 1.462-1.373 2.887-1.33c1.256.038 2.117-.52 2.39-.805c.566-.52 1.744-1.609 1.938-1.796");
}

.uvyxh01-z {
  stop-color: var(--svg-color--2851b6, #2851B6);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vudwjbw9p {
  stop-color: var(--svg-color--b5737a, #B5737A);
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.vxsr-abqz {
  d: path("M16.908 7.433a.388.388 0 0 1 .373.49h-.749a.39.39 0 0 1 .375-.49");
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w4_s79ciy {
  stop-color: var(--svg-color--e1a58b, #E1A58B);
  stop-opacity: 0;
}

.waah2bcle {
  stop-color: var(--svg-color--3968ab, #3968AB);
  stop-opacity: 0;
}

.wm2hnkwbm {
  stop-color: var(--svg-color--ffceac, #FFCEAC);
  stop-opacity: 0;
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x09-01b7i {
  stop-color: var(--svg-color--634689, #634689);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.xhtzkfsjn {
  d: path("M13.267 16.349v-.82h5.525v.82c-2.337.148-4.276.062-5.525 0");
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xsno6rw2t {
  stop-color: var(--svg-color--57a7fb, #57A7FB);
  stop-opacity: 0;
}

.xxjj5obiq {
  stop-color: var(--svg-color--4db6ff, #4DB6FF);
}

.y39x50mqx {
  stop-color: var(--svg-color--56c3ff, #56C3FF);
}

.y3su9tbbh {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .284.31l-1.82 1.668l.84.085a.21.21 0 0 1-.043.418l-1.21-.124l-.955.875a.21.21 0 1 1-.284-.31z");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ygodmjpra {
  fill: var(--svg-color--000, #000);
  d: path("M16.686 7.82a.22.22 0 0 1 .222-.222a.22.22 0 0 1 .197.324h-.393a.2.2 0 0 1-.026-.102");
}

.yn_cprukr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.025-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .283-.312l-4.235-3.836z");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.ywk-_ln5y {
  stop-color: var(--svg-color--4b90ea, #4B90EA);
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z1f5d8bxu {
  stop-color: var(--svg-color--edba9f, #EDBA9F);
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z7v7wpmwi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.415 6.917c.142-.125.452-.258.837-.196");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zd1r_u8ze {
  stop-color: var(--svg-color--6a4e8f, #6A4E8F);
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zh46g387g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M23.32 8.935v.258a.9.9 0 0 1-.25.617v0");
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zx2ao6bwg {
  stop-color: var(--svg-color--d79c86, #D79C86);
}

</style>
