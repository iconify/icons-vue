<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ifInvEb)"><path fill="url(#itLHXWQ)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#iHE5Nne)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#iaH5GZb)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#iZAPvpc)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#ir5cUsb)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#io7Ivcb)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#iVvN26d)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#iDODqfe)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#ieHBu4A)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#iWe5Bab)" clip-rule="evenodd" class="q4bvuacwl"/><path fill="url(#iWG12Sb)" clip-rule="evenodd" class="q4bvuacwl"/></g><path class="mpnicg68t"/><path fill="url(#i8jye2A)" class="ltpgi1b3n"/><path fill="url(#iCB6AON)" class="ltpgi1b3n"/><path fill="url(#ifMzlUd)" class="ltpgi1b3n"/><path fill="url(#iEqEkEe)" class="ltpgi1b3n"/><path fill="url(#i1SCTre)" class="ltpgi1b3n"/><path class="jlbrx4biw"/><path fill="url(#iN4Qgsl)" class="qwk8jd8rk"/><path fill="url(#iZnVhIc)" class="qwk8jd8rk"/><path fill="url(#ixyeT4i)" class="qwk8jd8rk"/><g filter="url(#isifM1d)"><path class="x26zj-beb"/></g><path fill="url(#i5h1Ryb)" class="wrxl7l2vi"/><path fill="url(#iEINJJc)" class="wrxl7l2vi"/><path fill="url(#ip7dVEc)" class="wrxl7l2vi"/><path fill="url(#iW5oHAb)" class="nokva0_ko"/><path fill="url(#i43VwXd)" class="nokva0_ko"/><g filter="url(#isfuxwc)"><path fill="url(#iLsR3Rc)" class="reevoabuq"/></g><path fill="url(#i63Ilcb)" class="sbpp9o8rc"/><path fill="url(#iihedSb)" class="sbpp9o8rc"/><path fill="url(#iKktGjd)" class="sbpp9o8rc"/><path fill="url(#i9bX55c)" class="irxwa8bfq"/><path fill="url(#iSwKzwe)" class="irxwa8bfq"/><path fill="url(#i9Nz6Jl)" class="irxwa8bfq"/><path fill="url(#ij8PNMe)" class="irxwa8bfq"/><path fill="url(#iIipaHv)" class="irxwa8bfq"/><path class="yw1tuybcd"/><path fill="url(#iLnu67h)" class="rh8f80bwj"/><path fill="url(#imd7Yde)" class="rh8f80bwj"/><path fill="url(#i681Uub)" class="rh8f80bwj"/><path fill="url(#iG2o2zd)" class="rh8f80bwj"/><path fill="url(#isJUaBc)" class="rh8f80bwj"/><g filter="url(#iJQ1cVb)"><path fill="url(#i1f94zb)" class="j9rthhk5r"/><path fill="url(#iM3BIMe)" class="j9rthhk5r"/><path fill="url(#iA7Jkfc)" class="j9rthhk5r"/><path fill="url(#im6Ax1d)" class="j9rthhk5r"/><path fill="url(#izJYOqc)" class="j9rthhk5r"/></g><g filter="url(#iAge2xR)"><path fill="url(#iYqH3eb)" class="e7235obbu"/><path fill="url(#iaiKDdc)" class="e7235obbu"/><path fill="url(#i8ep4zE)" class="e7235obbu"/><path fill="url(#iPij2KA)" class="e7235obbu"/></g><g filter="url(#i2s7Nhd)"><path fill="url(#ic0Ybke)" class="sxg58elsr"/><path fill="url(#i67JdDe)" class="sxg58elsr"/></g><rect fill="url(#iUp4j5b)" class="eq8halb1x"/><rect fill="url(#iLgsQsb)" class="eq8halb1x"/><rect fill="url(#iJihimb)" class="eq8halb1x"/><rect fill="url(#iGWgpdo)" class="eq8halb1x"/><g filter="url(#i1hyMFc)"><circle class="bzlygpkrz"/></g><circle fill="url(#iWrF1Id)" class="c8av-0bva"/><circle fill="url(#iZszzcd)" class="c8av-0bva"/><g filter="url(#isomDgd)"><path fill="url(#igoVnFd)" clip-rule="evenodd" class="p2antrbgp"/></g><rect fill="url(#inuFH0G)" transform="rotate(-30 25.512 15.976)" class="ypecylbhv"/><g filter="url(#igDZhse)"><path fill="url(#ilZFn0d)" class="ptbhqi4dg"/><path fill="url(#iMXmAmE)" class="ptbhqi4dg"/><path fill="url(#irIMZ7d)" class="ptbhqi4dg"/><path fill="url(#iB9gv3c)" class="ptbhqi4dg"/><path fill="url(#i86ofvB)" class="ptbhqi4dg"/></g><g filter="url(#i0l7ARc)"><path stroke="url(#iTFMTfe)" class="g1ts8rbhr"/></g><g filter="url(#iH1gMkc)"><path stroke="url(#iHa20jb)" class="y3lkl1bfj"/></g><g filter="url(#iUodKUd)"><path stroke="url(#iRpSthb)" class="dhh3zrbil"/></g><path fill="url(#isrJq9d)" class="wduyq1bmf"/><path fill="url(#ihCpCSc)" class="wduyq1bmf"/><g filter="url(#iypVFNe)"><path fill="url(#iU8Ldwb)" class="mwu5fjm9v"/></g><g filter="url(#izcxbzx)"><path fill="url(#iRoU1Oe)" class="q9pf9lbcj"/></g><g filter="url(#iWxf4Ce)"><path class="y2lrowbud"/><path fill="url(#iaddDod)" class="decb2lbry"/></g><g filter="url(#iaKpgGc)"><path class="o5ad759kb"/><path fill="url(#i9iqyZb)" class="cv5t4-buk"/></g><g filter="url(#ioBBIQc)"><path fill="url(#iyoAFEe)" class="zu8416bzx"/></g><path fill="url(#ixKBmrb)" class="zu8416bzx"/><path fill="url(#iDrwcWP)" class="zu8416bzx"/><g filter="url(#iWaUFYY)"><path class="ffnh_hxcr"/></g><g filter="url(#i5MSscb)"><path class="ysandfbcu"/><path fill="url(#iNzJW8d)" class="b7viv_bef"/></g><g filter="url(#iDzCOzc)"><path fill="url(#iL6D6Ie)" class="weq0bnteu"/></g><g filter="url(#ixC3Cxd)"><path stroke="url(#ifi735d)" class="crnoxacta"/></g><path class="vea0clbby"/><g filter="url(#ip4dpHm)"><path class="g0xw53kvr"/></g><g filter="url(#iBOgiuR)"><path class="yozffmb-l"/></g><path class="p1mfgxbsu"/><path fill="url(#iY0Jfgb)" class="biwnp-bcc"/><path class="h5n54ibbe"/><g filter="url(#idDFedc)"><path class="g4wn_sjvu"/><path fill="url(#ivhlPLe)" class="lxv984brl"/></g><g filter="url(#iE7sjxb)"><path fill="url(#iPvyPId)" class="eem0spb7j"/></g><path class="m2hq0i1hp"/><path fill="url(#i9bUNje)" class="mx2d4ybrx"/><path class="requbosym"/><g filter="url(#iA046Ke)"><path fill="url(#iczcfub)" class="llu5qibjy"/></g><g filter="url(#i3fHsqe)"><ellipse transform="rotate(-27.914 12.05 12.06)" class="cw8zywb1w"/><ellipse fill="url(#iISX7wd)" transform="rotate(-27.914 12.05 12.06)" class="h7o1qummw"/></g><g filter="url(#iZRcMhd)"><path fill="url(#ids4Eqc)" class="k1r2winen"/></g><path fill="url(#igd3zKJ)" class="k1r2winen"/><path fill="url(#iIjxoHc)" class="k1r2winen"/><g filter="url(#iJYHuab)"><path fill="url(#iBpB1Dd)" class="ok93gu4lo"/></g><path fill="url(#iNh5sjb)" class="yxjznfyld"/><path fill="url(#igxmgjd)" class="yxjznfyld"/><path fill="url(#ivHBRfe)" class="yxjznfyld"/><path fill="url(#iuWK5Hd)" class="yxjznfyld"/><defs><radialGradient id="iHE5Nne" cx="0" cy="0" r="1" gradientTransform="scale(3.06497 5.08736)rotate(90 .1 3.043)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iaH5GZb" cx="0" cy="0" r="1" gradientTransform="rotate(127.617 1.421 8.783)scale(2.32053 2.25311)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iZAPvpc" cx="0" cy="0" r="1" gradientTransform="rotate(100.537 .706 9.24)scale(2.91888 3.03947)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="ir5cUsb" cx="0" cy="0" r="1" gradientTransform="matrix(1.25064 2.41324 -4.59716 2.38243 11.042 4.475)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="io7Ivcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26285 1.37768 -1.92528 -1.76482 21.127 6.093)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iVvN26d" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.88 7.509)scale(2.19193 4.76935)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iDODqfe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.352 9.52 -2.184)scale(1.56897 .51441)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="ieHBu4A" cx="0" cy="0" r="1" gradientTransform="matrix(.1765 -2.85922 1.23512 .07624 20.358 11.03)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="woq2rfbwf"/><stop offset="1" class="f4ewe7hfz"/></radialGradient><radialGradient id="iWe5Bab" cx="0" cy="0" r="1" gradientTransform="rotate(-16.858 71.854 -48.338)scale(3.65153 3.89005)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="ob3xgsbot"/><stop offset="1" class="tajwfg0rw"/></radialGradient><radialGradient id="iWG12Sb" cx="0" cy="0" r="1" gradientTransform="rotate(-135.352 10.37 6.89)scale(4.06858 4.33434)" gradientUnits="userSpaceOnUse"><stop class="hqkefpd1n"/><stop offset="1" class="hdvububbc"/></radialGradient><radialGradient id="i8jye2A" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.811)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="iCB6AON" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.44 11.475)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="iEqEkEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.155)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="i1SCTre" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.412 66.251)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="iZnVhIc" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .546 18.005)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="ixyeT4i" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.634 20.886)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i5h1Ryb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.92)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="iEINJJc" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.544 12.697)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="ip7dVEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.92)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iW5oHAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.467)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="i43VwXd" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.92)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="iLsR3Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.86 22.653)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="i63Ilcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.78)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="i9bX55c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.968)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="i9Nz6Jl" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.195 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ij8PNMe" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.134 8.128)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iIipaHv" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.05 20.861)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iLnu67h" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.468)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="i681Uub" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.37 20.582)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iG2o2zd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.574)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="isJUaBc" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.7 20.86)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iA7Jkfc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.397 8.282)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="izJYOqc" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.314 21.252)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="i8ep4zE" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.249)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iPij2KA" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.982)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="ic0Ybke" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 7.115 19.738)scale(2.05934 1.65405)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset=".828" class="gtmq6ja1j"/></radialGradient><radialGradient id="i67JdDe" cx="0" cy="0" r="1" gradientTransform="matrix(.46055 -.4563 .48587 .4904 26.88 24.064)" gradientUnits="userSpaceOnUse"><stop class="xcc0mcchc"/><stop offset="1" class="lyxdnwxxe"/></radialGradient><radialGradient id="iJihimb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.225)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iGWgpdo" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.264)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iWrF1Id" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.248)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="iZszzcd" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.728)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="inuFH0G" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.117)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="iMXmAmE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57872 2.60975 -2.15908 -1.3061 27.845 24.019)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="irIMZ7d" cx="0" cy="0" r="1" gradientTransform="matrix(2.52448 0 0 .50881 23.335 25.521)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iB9gv3c" cx="0" cy="0" r="1" gradientTransform="matrix(2.83004 0 0 .5704 23.131 26.97)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="i86ofvB" cx="0" cy="0" r="1" gradientTransform="matrix(2.96797 0 0 .3582 23.028 28.353)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="isrJq9d" cx="0" cy="0" r="1" gradientTransform="matrix(3.5772 2.43801 -2.82968 4.1519 13.467 18.507)" gradientUnits="userSpaceOnUse"><stop class="yqu9yb9hr"/><stop offset=".433" class="dv7jwx2tc"/><stop offset=".66" class="dv7jwx2tc"/><stop offset="1" class="bi2cxr-1d"/></radialGradient><radialGradient id="ihCpCSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.19175 -2.84686 0 14.851 18.729)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="t89u59asd"/><stop offset="1" class="p5rcclgbc"/></radialGradient><radialGradient id="iRoU1Oe" cx="0" cy="0" r="1" gradientTransform="matrix(2.84143 -1.29156 1.57694 3.46926 19.463 13.473)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iaddDod" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 47.04 -49.506)scale(1.48928)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="i9iqyZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22618 0 0 -1.17291 9.524 12.972)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iyoAFEe" cx="0" cy="0" r="1" gradientTransform="rotate(168.938 9.641 8.156)scale(8.14325 13.6948)" gradientUnits="userSpaceOnUse"><stop class="xoq3wtioq"/><stop offset="1" class="w5b0bt39m"/></radialGradient><radialGradient id="ixKBmrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.93333 -9.48559 0 14.851 12.534)" gradientUnits="userSpaceOnUse"><stop offset=".59" class="m-6hhlb4r"/><stop offset="1" class="elzis2kqe"/></radialGradient><radialGradient id="iDrwcWP" cx="0" cy="0" r="1" gradientTransform="rotate(83.751 1.158 13.533)scale(3.37543 9.1523)" gradientUnits="userSpaceOnUse"><stop class="ojnx5stie"/><stop offset="1" class="abli2mb8o"/></radialGradient><radialGradient id="iNzJW8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.37501 -1.78125 1.29491 -.27262 15.653 14.218)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="z2r3m2sip"/><stop offset="1" class="hw8nn1bnh"/></radialGradient><radialGradient id="iY0Jfgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21036 1.79535 0 17.342 12.912)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="unk25xbmq"/><stop offset="1" class="rink4olzh"/></radialGradient><radialGradient id="ivhlPLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.26442 -.34074 .46911 -.36404 17.08 12.266)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9bUNje" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21036 1.79536 0 12.36 12.912)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="unk25xbmq"/><stop offset="1" class="rink4olzh"/></radialGradient><radialGradient id="iISX7wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00882 -.5626 .67686 -.0106 12.033 12.42)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ids4Eqc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.093)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><radialGradient id="igd3zKJ" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.124)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="iIjxoHc" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.076)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iNh5sjb" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.608)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><filter id="ifInvEb" width="17.394" height="16.343" x="6.279" y="3.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.411765 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="isifM1d" width="7.346" height="5.139" x="11.201" y="19.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".25"/></filter><filter id="isfuxwc" width="3.106" height="2.966" x="13.406" y="21.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="iJQ1cVb" width="8.299" height="13.046" x="5.292" y="16.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="iAge2xR" width="8.299" height="13.046" x="16.153" y="16.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="i2s7Nhd" width="2.761" height="3.973" x="26.147" y="21.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="i1hyMFc" width="6.656" height="6.656" x="22.367" y="13.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".125"/></filter><filter id="isomDgd" width="7.206" height="7.206" x="22.067" y="13.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="igDZhse" width="5.427" height="6.052" x="23.131" y="23.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.513726 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="i0l7ARc" width="2.212" height=".25" x="23.574" y="25.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".05"/></filter><filter id="iH1gMkc" width="2.212" height=".25" x="23.489" y="26.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".05"/></filter><filter id="iUodKUd" width="2.212" height=".25" x="23.574" y="28.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".05"/></filter><filter id="iypVFNe" width="3.774" height="3.674" x="7.665" y="11.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="izcxbzx" width="3.674" height="3.924" x="18.525" y="10.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="iWxf4Ce" width="3.452" height="3.452" x="18.636" y="11.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".25"/></filter><filter id="iaKpgGc" width="2.952" height="2.952" x="8.048" y="11.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".125"/></filter><filter id="ioBBIQc" width="12.384" height="12.417" x="9.035" y="7.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.603922 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="iWaUFYY" width="3.143" height="4.061" x="13.094" y="11.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".25"/></filter><filter id="i5MSscb" width="2.643" height="3.561" x="13.53" y="11.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.824136 0 0 0 0 0.46236 0 0 0 0 0.134858 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/><feGaussianBlur result="effect2_foregroundBlur_4002_2748" stdDeviation=".125"/></filter><filter id="iDzCOzc" width="2.643" height="3.561" x="13.53" y="11.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".125"/></filter><filter id="ixC3Cxd" width="4.17" height="1.685" x="12.766" y="15.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".05"/></filter><filter id="ip4dpHm" width="3.398" height="1.467" x="16.155" y="11.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="iBOgiuR" width="3.398" height="1.467" x="10.35" y="11.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="idDFedc" width=".869" height=".766" x="16.518" y="11.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".05"/></filter><filter id="iE7sjxb" width=".96" height=".986" x="17.491" y="11.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".1"/></filter><filter id="iA046Ke" width="1.068" height="1.13" x="12.42" y="11.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".1"/></filter><filter id="i3fHsqe" width="1.013" height=".775" x="11.543" y="11.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2748" stdDeviation=".05"/></filter><filter id="iZRcMhd" width="12.369" height="3.947" x="8.798" y="2.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/></filter><filter id="iJYHuab" width="19.912" height="4.003" x="4.915" y="7.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2748"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2748" result="effect2_innerShadow_4002_2748"/></filter><linearGradient id="itLHXWQ" x1="21.06" x2="11.942" y1="12.301" y2="20.061" gradientUnits="userSpaceOnUse"><stop class="mudxz8mau"/><stop offset="1" class="s6i5trbdr"/></linearGradient><linearGradient id="ifMzlUd" x1="6.988" x2="7.195" y1="29.405" y2="29.405" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="iN4Qgsl" x1="16.981" x2="14.895" y1="28.547" y2="28.121" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="iihedSb" x1="13.726" x2="14.226" y1="26.764" y2="26.811" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="iKktGjd" x1="16.414" x2="15.153" y1="29.068" y2="29.121" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="iSwKzwe" x1="11.675" x2="12.612" y1="21.648" y2="21.467" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="imd7Yde" x1="18.074" x2="17.137" y1="21.648" y2="21.467" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="i1f94zb" x1="12.219" x2="9.392" y1="26.168" y2="26.805" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iM3BIMe" x1="9.392" x2="11.086" y1="16.975" y2="22.374" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="im6Ax1d" x1="12.268" x2="12.268" y1="29.921" y2="24.698" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="iYqH3eb" x1="18.023" x2="21.304" y1="29.124" y2="16.975" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iaiKDdc" x1="17" x2="17.152" y1="26.538" y2="26.569" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iUp4j5b" x1="26.981" x2="24.992" y1="21.78" y2="21.78" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iLgsQsb" x1="26.335" x2="26.335" y1="25.468" y2="22.561" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="igoVnFd" x1="28.179" x2="23.367" y1="14.342" y2="19.78" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="ilZFn0d" x1="28.258" x2="23.131" y1="27.805" y2="27.805" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".755" class="xwbtobibq"/></linearGradient><linearGradient id="iTFMTfe" x1="25.534" x2="23.529" y1="25.53" y2="25.53" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iHa20jb" x1="25.448" x2="23.444" y1="26.954" y2="26.954" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iRpSthb" x1="25.534" x2="23.529" y1="28.378" y2="28.378" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iU8Ldwb" x1="7.665" x2="11.043" y1="13.072" y2="13.072" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iL6D6Ie" x1="14.851" x2="15.061" y1="11.909" y2="13.016" gradientUnits="userSpaceOnUse"><stop class="vyjm-cbue"/><stop offset="1" class="moq9h7bqy"/></linearGradient><linearGradient id="ifi735d" x1="14.019" x2="14.536" y1="17.141" y2="16.146" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iPvyPId" x1="18.23" x2="17.872" y1="12.231" y2="12.451" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iczcfub" x1="13.209" x2="12.851" y1="12.231" y2="12.451" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBpB1Dd" x1="23.304" x2="6.367" y1="9.436" y2="9.752" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="igxmgjd" x1="8.554" x2="9.992" y1="6.876" y2="7.061" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="ivHBRfe" x1="15.46" x2="15.46" y1="7.928" y2="7.725" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="iuWK5Hd" x1="15.507" x2="15.507" y1="5.846" y2="5.983" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-detective" /></template>
<style>
.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.abli2mb8o {
  stop-color: var(--svg-color--dd7d28, #DD7D28);
  stop-opacity: 0;
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.b7viv_bef {
  d: path("m14.415 12.383l-.607 1.94c-.124.4.173.8.594.8h.898a.618.618 0 0 0 .594-.8l-.606-1.94c-.13-.43-.737-.43-.873 0");
}

.bc2ld5biv {
  stop-color: var(--svg-color--46446d, #46446D);
}

.bcp6zybsw {
  stop-color: var(--svg-color--7c707d, #7C707D);
}

.bi2cxr-1d {
  stop-color: var(--svg-color--e7b83d, #E7B83D);
}

.biwnp-bcc {
  d: path("M17.344 11.625a1.018 1.018 0 0 1 .982 1.287h-1.968a1.022 1.022 0 0 1 .986-1.287");
}

.bpzzcwljp {
  stop-color: var(--svg-color--5b537a, #5B537A);
}

.bslse1b3i {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
}

.bt46k-bry {
  stop-color: var(--svg-color--810937, #810937);
}

.bzlygpkrz {
  cx: 25.695px;
  cy: 17.093px;
  r: 3.078px;
  fill: var(--svg-color--3e2657, #3E2657);
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
}

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
}

.c8av-0bva {
  cx: 25.695px;
  cy: 17.093px;
  r: 2.984px;
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cjc9cqblk {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crnoxacta {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.851 16.347a3.46 3.46 0 0 1-1.623-.393c-.16-.084-.332.101-.231.25a2.205 2.205 0 0 0 3.709 0c.101-.155-.071-.334-.232-.25c-.47.25-1.022.393-1.623.393Z");
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.cv5t4-buk {
  d: path("M9.524 14.198a1.226 1.226 0 1 0 0-2.452a1.226 1.226 0 0 0 0 2.452");
}

.cw8zywb1w {
  cx: 12.05px;
  cy: 12.061px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.444px;
  ry: 0.225px;
}

.cw9lwsb0z {
  stop-color: var(--svg-color--4f4376, #4F4376);
  stop-opacity: 0;
}

.d-k16gi6m {
  stop-color: var(--svg-color--b6376a, #B6376A);
  stop-opacity: 0;
}

.d1xnqxb5m {
  stop-color: var(--svg-color--573a60, #573A60);
  stop-opacity: 0;
}

.damj_nbgh {
  stop-color: var(--svg-color--7577a1, #7577A1);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.decb2lbry {
  d: path("M20.362 14.198a1.226 1.226 0 1 0 0-2.452a1.226 1.226 0 0 0 0 2.452");
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dhh3zrbil {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.7 28.378h1.96");
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dv7jwx2tc {
  stop-color: var(--svg-color--df8c27, #DF8C27);
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e7235obbu {
  d: path("m18.996 16.975l-2.743 12.946h1.797c1.401-2.334 4.288-7.147 4.625-7.735c.422-.734.219-.906.14-1.031c-.077-.125-.374-.36-.671-.469c-.237-.087-.328-.203-.344-.25c-.057-.068-.069-.3.344-.687s1.307-1.068 1.703-1.36c.234-.187.652-.61.602-.984c-.05-.375-.651-.435-.766-.43z");
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.eem0spb7j {
  d: path("M18.252 12.51a.96.96 0 0 0-.264-.528l-.297.325l.134.26z");
}

.elzis2kqe {
  stop-color: var(--svg-color--c8752b, #C8752B);
}

.eq8halb1x {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.225px;
  rx: 1.286px;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f4ewe7hfz {
  stop-color: var(--svg-color--ea8915, #EA8915);
  stop-opacity: 0;
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
}

.ffnh_hxcr {
  fill: var(--svg-color--eb8b2a, #EB8B2A);
  d: path("m14.403 12.541l-.78 1.941c-.124.4.173.799.594.799h.898a.618.618 0 0 0 .594-.799l-.607-1.94c-.13-.43-.563-.43-.699 0");
}

.fisd__bqs {
  stop-color: var(--svg-color--ce3657, #CE3657);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fjaxvnbiy {
  stop-color: var(--svg-color--4c3156, #4C3156);
  stop-opacity: 0;
}

.fk1gregde {
  stop-color: var(--svg-color--57497f, #57497F);
  stop-opacity: 0;
}

.foejprbbc {
  stop-color: var(--svg-color--767290, #767290);
}

.fpxhxfble {
  stop-color: var(--svg-color--5c4b6c, #5C4B6C);
}

.ft5dv1b6b {
  fill: none;
}

.g0xw53kvr {
  fill: var(--svg-color--291720, #291720);
  d: path("M16.155 12.202c.303-.533.764-.954 1.755-.954c.434 0 .853.12 1.225.421c.307.248.265.566.028.684l-.635.363c-.744-.24-1.567-.273-2.373-.514");
}

.g1ts8rbhr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.7 25.53h1.96");
}

.g4wn_sjvu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.269 11.841c.072.097-.08.215-.252.344s-.3.22-.372.123s.008-.28.18-.41c.173-.128.371-.154.444-.057");
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
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

.h5n54ibbe {
  fill: var(--svg-color--000, #000);
  d: path("M16.76 12.644a.58.58 0 0 1 .584-.583a.58.58 0 0 1 .519.851H16.83a.53.53 0 0 1-.07-.268");
}

.h7o1qummw {
  cx: 12.05px;
  cy: 12.061px;
  rx: 0.444px;
  ry: 0.225px;
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hdvububbc {
  stop-color: var(--svg-color--945b0e, #945B0E);
  stop-opacity: 0;
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hqkefpd1n {
  stop-color: var(--svg-color--945b0e, #945B0E);
}

.hw8nn1bnh {
  stop-color: var(--svg-color--ffb938, #FFB938);
  stop-opacity: 0;
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.id09adcid {
  stop-color: var(--svg-color--ffe047, #FFE047);
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.irxwa8bfq {
  d: path("m11.972 22.725l-.806-3.758l2.026-.624l1.692 3.113v.433l-1.96 1.782c-.097.083-.327.214-.477.07s-.357-.504-.475-1.016");
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.j9rthhk5r {
  d: path("m10.75 16.975l2.742 12.946h-1.797a1567 1567 0 0 1-4.625-7.735c-.422-.734-.219-.906-.14-1.031s.374-.36.671-.469c.238-.087.328-.203.344-.25c.057-.068.069-.3-.344-.687c-.412-.388-1.307-1.068-1.703-1.36c-.234-.187-.651-.61-.601-.984c.05-.375.65-.435.765-.43z");
}

.jlbrx4biw {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.494 29.924l-2.328-10.956h3.731l4.128.093l-2.281 10.863z");
}

.k1r2winen {
  d: path("M8.804 5.741a.1.1 0 0 0 .094.133h11.92a.1.1 0 0 0 .094-.133a86 86 0 0 0-.639-1.789c-.469-1.25-1.637-1.875-2.297-1.875c-.735-.017-1.259.318-1.65.567q-.103.065-.194.12c-.578.344-.808.399-1.277.399c-.37 0-.761-.148-1.183-.367a5 5 0 0 1-.248-.142c-.436-.26-1.078-.642-1.905-.526c-.956.134-1.66.93-2.097 1.945c-.158.366-.386.997-.618 1.668");
}

.k1zgefb2d {
  stop-color: var(--svg-color--605a74, #605A74);
}

.k5i52n_gm {
  stop-color: var(--svg-color--2683c8, #2683C8);
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kpssiabxl {
  stop-color: var(--svg-color--5c5178, #5C5178);
  stop-opacity: 0;
}

.kte-0sm3k {
  stop-color: var(--svg-color--cfbdc9, #CFBDC9);
  stop-opacity: 0;
}

.kvzrrwynu {
  stop-color: var(--svg-color--6a5e90, #6A5E90);
}

.l9k3lrq7u {
  stop-color: var(--svg-color--d1c0d6, #D1C0D6);
}

.la8vvmbhh {
  stop-color: var(--svg-color--ad254b, #AD254B);
  stop-opacity: 0;
}

.lcqew7b7f {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
  stop-opacity: 0;
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.ld92_g1my {
  stop-color: var(--svg-color--7f81b2, #7F81B2);
}

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llu5qibjy {
  d: path("M13.288 12.524c0-.33-.267-.548-.34-.615l-.328.318l.202.412z");
}

.ltpgi1b3n {
  d: path("M2.727 29.92H27.01c-.399-6.367-5.682-11.408-12.142-11.408S3.125 23.552 2.727 29.92");
}

.lxv984brl {
  d: path("M17.269 11.841c.072.097-.08.215-.252.344s-.3.22-.372.123s.008-.28.18-.41c.173-.128.371-.154.444-.057");
}

.lyxdnwxxe {
  stop-color: var(--svg-color--efa20d, #EFA20D);
  stop-opacity: 0;
}

.m-6hhlb4r {
  stop-color: var(--svg-color--ee9339, #EE9339);
  stop-opacity: 0;
}

.m2hq0i1hp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.122 11.315c-.746 0-1.376.514-1.547 1.209a.314.314 0 0 0 .306.389h2.547a.263.263 0 0 0 .259-.31a1.6 1.6 0 0 0-1.565-1.288");
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.moq9h7bqy {
  stop-color: var(--svg-color--e48a2a, #E48A2A);
  stop-opacity: 0;
}

.mpnicg68t {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.92H27.01c-.399-6.367-5.682-11.408-12.142-11.408S3.125 23.552 2.727 29.92");
}

.mudxz8mau {
  stop-color: var(--svg-color--ffbe35, #FFBE35);
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
}

.mwu5fjm9v {
  d: path("M9.502 14.81a1.837 1.837 0 1 0 0-3.674a1.837 1.837 0 0 0 0 3.673");
}

.mx2d4ybrx {
  d: path("M12.358 11.625a1.018 1.018 0 0 0-.982 1.287h1.968q.036-.131.037-.268a1.025 1.025 0 0 0-1.023-1.019");
}

.mx64gfpes {
  stop-color: var(--svg-color--6a6385, #6A6385);
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nig76no1i {
  stop-color: var(--svg-color--4e4270, #4E4270);
  stop-opacity: 0;
}

.njrd_tayg {
  stop-color: var(--svg-color--573a60, #573A60);
}

.nokva0_ko {
  d: path("M22.727 29.92h4.296a12.16 12.16 0 0 0-4.296-8.537z");
}

.nw6o4wclj {
  stop-color: var(--svg-color--624c7f, #624C7F);
}

.nzffxlbem {
  stop-color: var(--svg-color--4f456a, #4F456A);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o5ad759kb {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M9.524 14.198a1.226 1.226 0 1 0 0-2.452a1.226 1.226 0 0 0 0 2.452");
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.ob3xgsbot {
  stop-color: var(--svg-color--915712, #915712);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ojnx5stie {
  stop-color: var(--svg-color--dd7d28, #DD7D28);
}

.ok93gu4lo {
  d: path("M6.386 7.878c-.26-.016-.991.034-1.316.36c-.358.357-.055 1.073.508 1.651c.539.555 2.335 1.739 5.18 1.739h8.167c2.873 0 4.689-1.184 5.234-1.739c.568-.578.874-1.294.513-1.652c-.329-.325-1.067-.375-1.33-.36z");
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.p1mfgxbsu {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.58 11.315c.747 0 1.376.514 1.548 1.209a.313.313 0 0 1-.306.389h-2.547a.263.263 0 0 1-.26-.31a1.596 1.596 0 0 1 1.566-1.288");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p2antrbgp {
  fill-rule: evenodd;
  d: path("M25.695 20.67a3.578 3.578 0 1 0 0-7.155a3.578 3.578 0 0 0 0 7.156m0-.593a2.984 2.984 0 1 0 0-5.969a2.984 2.984 0 0 0 0 5.969");
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p5rcclgbc {
  stop-color: var(--svg-color--cf7a2e, #CF7A2E);
  stop-opacity: 0;
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ptbhqi4dg {
  d: path("M23.132 24.818c0-.438.355-.8.793-.8h3.023c.724 0 1.31.587 1.31 1.31v3.501c0 .603-.488 1.092-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.517a.802.802 0 0 1 0-1.434a.802.802 0 0 1 0-1.435a.8.8 0 0 1-.445-.717");
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q0u2bl4sa {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
  stop-opacity: 0;
}

.q4bvuacwl {
  fill-rule: evenodd;
  d: path("M23.054 14.261a3.7 3.7 0 0 0 .37-1.629c0-.533-.11-1.034-.307-1.49h.006a3.7 3.7 0 0 0-.321-.586l-.003-.003a3.7 3.7 0 0 1-.6-2.022v-.012c-2.822 0-3.78-4.551-7.348-4.551c-3.962 0-3.77 3.375-7.348 4.551v.012c0 .716-.207 1.421-.6 2.022l-.003.004a3.77 3.77 0 0 0-.251 3.704c.08.162.08.358 0 .52a3.7 3.7 0 0 0-.37 1.606a3.67 3.67 0 0 0 3.674 3.674h9.797a3.67 3.67 0 0 0 3.673-3.674c0-.578-.138-1.12-.37-1.606a.59.59 0 0 1 0-.52m-13.996-3.05h-.014l1.368 2.688c.14 3.2 1.39 0 4.439 0s4.38 3.561 4.52.362l-.284-3.12c-.06-1.42.49-2.05.284-2.05h-3.676a4.41 4.41 0 0 1-3.64-1.91a.301.301 0 0 0-.527.058l-.094.22a2.63 2.63 0 0 1-1.358 1.41l-.058.024l-.059.023c-.27.14-.901.559-.925 1.642l.012.35z");
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.q9pf9lbcj {
  d: path("M20.362 14.809a1.837 1.837 0 1 0 0-3.674a1.837 1.837 0 0 0 0 3.674");
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qwk8jd8rk {
  d: path("m13.494 29.924l-2.328-10.956h3.731l4.128.093l-2.281 10.863z");
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.reevoabuq {
  d: path("m14.098 24.348l-.692-1.334l1.453-1.351l1.453 1.351l-.662 1.331a.15.15 0 0 1-.134.084h-1.285a.15.15 0 0 1-.133-.081");
}

.requbosym {
  fill: var(--svg-color--000, #000);
  d: path("M12.94 12.644a.58.58 0 0 0-.582-.583a.58.58 0 0 0-.519.851h1.032a.6.6 0 0 0 .07-.268");
}

.rh8f80bwj {
  d: path("m17.77 22.745l.814-3.777l-1.758-.579l-1.961 3.063v.437l1.96 1.782c.097.083.327.214.477.07s.35-.484.467-.996");
}

.rink4olzh {
  stop-color: var(--svg-color--64352f, #64352F);
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.s6i5trbdr {
  stop-color: var(--svg-color--cd761a, #CD761A);
}

.sbpp9o8rc {
  d: path("m13.289 29.92l.854-5.407a.1.1 0 0 1 .098-.085h1.247a.1.1 0 0 1 .099.085l.827 5.408z");
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxg58elsr {
  d: path("M27.203 22.327c.58 0 1.055.475 1.055 1.056V25.8h-2.111v-2.417a1.065 1.065 0 0 1 1.056-1.056");
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.t89u59asd {
  stop-color: var(--svg-color--cf7a2e, #CF7A2E);
}

.tajwfg0rw {
  stop-color: var(--svg-color--915712, #915712);
  stop-opacity: 0;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.thvbr9biq {
  stop-color: var(--svg-color--27a8e3, #27A8E3);
}

.tnc_xbdtt {
  stop-color: var(--svg-color--202d61, #202D61);
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.unk25xbmq {
  stop-color: var(--svg-color--7a4646, #7A4646);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vea0clbby {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M14.851 16.347a3.46 3.46 0 0 1-1.623-.393c-.16-.084-.332.101-.231.25a2.205 2.205 0 0 0 3.709 0c.101-.155-.071-.334-.232-.25c-.47.25-1.022.393-1.623.393");
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.vyjm-cbue {
  stop-color: var(--svg-color--e48a2a, #E48A2A);
}

.w5b0bt39m {
  stop-color: var(--svg-color--ef952a, #EF952A);
}

.wduyq1bmf {
  d: path("M12.658 18.729v.653c0 .66.19 1.401 2.193 2.274c2.003-.873 2.194-1.614 2.194-2.274v-.653z");
}

.weq0bnteu {
  d: path("m14.415 12.232l-.607 1.94c-.124.4.173.799.594.799h.898a.618.618 0 0 0 .594-.799l-.606-1.94c-.13-.43-.737-.43-.873 0");
}

.woq2rfbwf {
  stop-color: var(--svg-color--ea8915, #EA8915);
}

.wrxl7l2vi {
  d: path("M7.023 29.92H2.727a12.16 12.16 0 0 1 4.296-8.537z");
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x26zj-beb {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.701 19.666l.69 3.215c.1.438.278.746.406.87c.129.122.326.01.408-.061l1.67-1.516l1.669 1.516c.082.071.28.183.408.06s.299-.414.399-.852l.697-3.232h-1.584l-1.59 2.116l-1.588-2.116z");
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.xcc0mcchc {
  stop-color: var(--svg-color--efa20d, #EFA20D);
}

.xoq3wtioq {
  stop-color: var(--svg-color--ffcb2e, #FFCB2E);
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.xwbtobibq {
  stop-color: var(--svg-color--ffae37, #FFAE37);
}

.y2lrowbud {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.362 14.198a1.226 1.226 0 1 0 0-2.452a1.226 1.226 0 0 0 0 2.452");
}

.y3lkl1bfj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.614 26.954h1.962");
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yozffmb-l {
  fill: var(--svg-color--291720, #291720);
  d: path("M13.548 12.202c-.303-.533-.764-.954-1.755-.954c-.434 0-.853.12-1.225.421c-.307.248-.266.566-.028.684l.635.363c.744-.24 1.567-.273 2.373-.514");
}

.ypecylbhv {
  width: 1.769px;
  height: 2.205px;
  x: 25.512px;
  y: 15.976px;
  rx: 0.885px;
}

.yqu9yb9hr {
  stop-color: var(--svg-color--b97b22, #B97B22);
}

.ysandfbcu {
  fill: var(--svg-color--ec971c, #EC971C);
  d: path("m14.415 12.383l-.607 1.94c-.124.4.173.8.594.8h.898a.618.618 0 0 0 .594-.8l-.606-1.94c-.13-.43-.737-.43-.873 0");
}

.yw1tuybcd {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.745l.814-3.777h-1.852l-1.867 2.484v.437l1.96 1.782c.097.083.327.214.477.07s.35-.484.467-.996");
}

.yxjznfyld {
  d: path("M8.126 7.746a.1.1 0 0 0 .095.132h13.287a.1.1 0 0 0 .094-.133l-.192-.559l-.429-1.245a.1.1 0 0 0-.095-.067H8.83a.1.1 0 0 0-.095.067c-.19.554-.38 1.12-.531 1.575z");
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.z2r3m2sip {
  stop-color: var(--svg-color--ffb938, #FFB938);
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zu8416bzx {
  d: path("M9.044 11.21h.014l-.012-.302l-.011-.35c.023-1.083.655-1.502.924-1.642l.059-.023q.03-.014.058-.024a2.63 2.63 0 0 0 1.358-1.409l.094-.221a.301.301 0 0 1 .527-.058a4.41 4.41 0 0 0 3.64 1.91h3.677c.205 0 1.235.1 1.296 1.52l-.135 3.509c-.141 3.199-2.64 5.347-5.69 5.347c-3.049 0-5.547-2.148-5.688-5.347z");
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
