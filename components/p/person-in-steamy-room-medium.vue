<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iOokUYv)" class="r_bcr-ntk"/><circle fill="url(#ig6gRjd)" class="r_bcr-ntk"/><circle fill="url(#ifqCFkS)" class="iksuiqrgf"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.368)" class="n5l_opbqq"/><path fill="url(#i4UUWGe)" class="w8e9izb-y"/><path fill="url(#iFqMHgd)" class="w8e9izb-y"/><path fill="url(#iS6d3Rd)" class="w8e9izb-y"/><path fill="url(#i7GTaad)" class="rgs-6fbpw"/><path fill="url(#iU0xveW)" class="rgs-6fbpw"/><path class="lr6p412xr"/><path fill="url(#iJvbFZb)" class="gt-y46nru"/><path fill="url(#iMrfvye)" class="gt-y46nru"/><path fill="url(#ip742Bh)" class="gt-y46nru"/><path fill="url(#izyBClb)" class="gt-y46nru"/><path fill="url(#irX7roe)" class="gt-y46nru"/><path fill="url(#iB984Kc)" class="gt-y46nru"/><path class="dk0gm-byq"/><path fill="url(#i1Dor5L)" class="s6ufut5ul"/><path fill="url(#iv6Yn7W)" class="s6ufut5ul"/><path fill="url(#i4wIgAd)" class="s6ufut5ul"/><g filter="url(#iwfzppb)"><path fill="url(#iDsaIEc)" class="uygoe8bue"/><path fill="url(#iOQCPTc)" class="uygoe8bue"/><path fill="url(#iw7Dn2S)" class="uygoe8bue"/></g><path class="wkmk90b2p"/><g filter="url(#i6NfQ5g)"><path class="f2ocbl9zr"/></g><path fill="url(#iqFAAEd)" class="gl1a3jbde"/><path fill="url(#iDV47ve)" class="hmw-mjbkr"/><g filter="url(#ilS8U0d)"><path fill="url(#i9M5oLd)" class="epaghdc0t"/><path fill="url(#ihtSjdb)" class="epaghdc0t"/></g><path fill="url(#iGhIIIc)" class="epaghdc0t"/><path fill="url(#ijcNBmb)" class="epaghdc0t"/><path fill="url(#i4sP0Wr)" class="epaghdc0t"/><path fill="url(#iwxDFFb)" class="epaghdc0t"/><path fill="url(#iwAX7RT)" class="epaghdc0t"/><path fill="url(#i24FRsW)" class="epaghdc0t"/><path fill="url(#id95hzR)" class="epaghdc0t"/><path fill="url(#iM8zizb)" class="epaghdc0t"/><g filter="url(#iMsBxRb)"><path class="rd74zdb3c"/></g><g filter="url(#iP0B4gF)"><path class="njqb132eq"/><path fill="url(#i8pn5HN)" class="tgex-ob-h"/><path fill="url(#ifQqmAG)" class="tgex-ob-h"/><path fill="url(#iesUOZd)" class="tgex-ob-h"/><path fill="url(#iWPCyOe)" class="tgex-ob-h"/><path fill="url(#iVr4vHj)" class="tgex-ob-h"/></g><path fill="url(#iQRNDpe)" class="tgex-ob-h"/><path fill="url(#ijYrMuG)" class="tgex-ob-h"/><g filter="url(#io8o5Be)"><path stroke="url(#i6bk53b)" class="e0fn1k-pa"/></g><path fill="url(#iUvovMb)" class="ynk0bfbpf"/><g filter="url(#iXmSmXL)"><path fill="url(#i1hUSkd)" class="dg137t4cd"/></g><path fill="url(#iHtVvHc)" class="dg137t4cd"/><path fill="url(#iZuz0vL)" class="dg137t4cd"/><path fill="url(#ieJEWde)" class="dg137t4cd"/><g filter="url(#iVmecqZ)"><path class="spnbbobfl"/></g><g filter="url(#iHzpi9W)"><path class="kb1fxpbfw"/></g><g filter="url(#ixO3YFe)"><path class="fqhi7bcqx"/><path fill="url(#i0kcDnd)" class="bnw25vlzu"/><path fill="url(#io7AIFe)" class="bnw25vlzu"/></g><g filter="url(#iRawyBW)"><path class="w82swe3sw"/><path fill="url(#i1I7JZA)" class="uf6ynwk4b"/><path fill="url(#iGljwje)" class="uf6ynwk4b"/><path fill="url(#i8nGezd)" class="uf6ynwk4b"/></g><path class="i8o1iacxv"/><path fill="url(#iPbhIpv)" class="f7fam02nn"/><path class="rt8f9chvu"/><g filter="url(#ieWS2XO)"><path class="uwipchbui"/><path fill="url(#iflAAfc)" class="jne7u7bpd"/></g><g filter="url(#inE0Kde)"><path fill="url(#i5BynNe)" class="r-vpu7toc"/></g><path class="rl6zs7yhb"/><path fill="url(#iRornKb)" class="qdnqv10ox"/><path class="ge5nr6cth"/><g filter="url(#igwgR6b)"><path fill="url(#iWsLcyv)" class="uny96bcfc"/></g><g filter="url(#iEJRnUb)"><ellipse transform="rotate(-27.914 13.4 9.981)" class="hrqpq4_5o"/><ellipse fill="url(#iB7g49P)" transform="rotate(-27.914 13.4 9.981)" class="a57mrebnw"/></g><path fill="url(#ixYsyhe)" class="ofax10bwa"/><path fill="url(#ij8MRoc)" class="ofax10bwa"/><path fill="url(#iy54n7d)" class="ofax10bwa"/><path fill="url(#ieOqgkc)" class="ofax10bwa"/><path fill="url(#imcRQsd)" class="i72-7-vuk"/><path fill="url(#izO6Qnx)" class="i72-7-vuk"/><g filter="url(#igZvrub)"><path fill="url(#iCQHOHe)" class="gi6_xeb7a"/></g><g filter="url(#izKnvpd)"><path fill="url(#ikx3Z7H)" class="vytk550vf"/></g><g filter="url(#ilp0Nze)"><path class="db8dllnoa"/></g><g filter="url(#i5TObQb)"><path class="nkhjjib0d"/></g><g filter="url(#i5WNhac)"><path class="v9nf3osdu"/></g><defs><radialGradient id="iOokUYv" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.33)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="ig6gRjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.83)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="ifqCFkS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.268)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="i4UUWGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.58)" gradientUnits="userSpaceOnUse"><stop class="yf3t3eb5f"/><stop offset="1" class="a66gbwbzh"/></radialGradient><radialGradient id="i7GTaad" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.32)" gradientUnits="userSpaceOnUse"><stop class="pbkzvtx_w"/><stop offset="1" class="ykdcls_lk"/></radialGradient><radialGradient id="iJvbFZb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.392)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="k3qin7bzy"/><stop offset="1" class="x3axlob0n"/></radialGradient><radialGradient id="ip742Bh" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.962)" gradientUnits="userSpaceOnUse"><stop class="z2ddyab4m"/><stop offset="1" class="cqgvl433q"/></radialGradient><radialGradient id="irX7roe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.58)" gradientUnits="userSpaceOnUse"><stop class="h3e5alaje"/><stop offset="1" class="u4bo2-o9a"/></radialGradient><radialGradient id="iB984Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.515)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="gyulks50m"/><stop offset="1" class="atms-xm-n"/></radialGradient><radialGradient id="iv6Yn7W" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".374" class="k-y64ibbx"/><stop offset="1" class="pjzr3aclu"/></radialGradient><radialGradient id="i4wIgAd" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.49 18.294)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="bc2qs9bhj"/><stop offset="1" class="ktoycacxm"/></radialGradient><radialGradient id="iOQCPTc" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.75 -2.19025 2.26847 13.158 17.204)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="e9j5vvbvj"/><stop offset="1" class="l0nudab1i"/></radialGradient><radialGradient id="iw7Dn2S" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.01211 -.76307 0 16.64 16.221)" gradientUnits="userSpaceOnUse"><stop class="lj_bse8ns"/><stop offset="1" class="ma74w36yx"/></radialGradient><radialGradient id="iqFAAEd" cx="0" cy="0" r="1" gradientTransform="matrix(.75836 2.0454 -2.42979 .90088 20.7 11.96)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iDV47ve" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -35.714 38)scale(1.56749 4.83582)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="i9M5oLd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.76531 0 0 -8.42979 18.728 11.006)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="ihtSjdb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.49 8.154)scale(3.41215 2.817)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="ijcNBmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03532 12.58268 -10.41999 -.85737 17.486 5.017)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="i4sP0Wr" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16306 1.43929 0 18.363 9.677)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iwxDFFb" cx="0" cy="0" r="1" gradientTransform="matrix(.00398 -1.1083 1.2061 .00433 13.555 9.724)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iwAX7RT" cx="0" cy="0" r="1" gradientTransform="matrix(-8.60483 .54318 -1.38755 -21.98105 19.361 12.007)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i24FRsW" cx="0" cy="0" r="1" gradientTransform="matrix(3.42916 -2.95384 .87251 1.01292 9.006 8.238)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="id95hzR" cx="0" cy="0" r="1" gradientTransform="matrix(-.23766 2.52943 -1.01112 -.095 21.5 8.052)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iM8zizb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88275 -1.69464 0 13.64 10.505)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="ifQqmAG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24723 -.77701 0 16.357 12.384)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iWPCyOe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71374 .75971 -1.22091 -2.75411 16.474 11.807)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="ijYrMuG" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.855 9.026)scale(1.79507 2.59072)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iUvovMb" cx="0" cy="0" r="1" gradientTransform="matrix(2.20994 -1.08647 4.37114 8.89113 15.387 14.676)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iHtVvHc" cx="0" cy="0" r="1" gradientTransform="matrix(2.77572 -7.24119 10.27516 3.93871 10.104 9.058)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iZuz0vL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53879 -6.63772 9.41887 -2.18352 21.63 9.118)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="ieJEWde" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.086 -3.667)scale(2.67218 3.15456)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="i0kcDnd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.22933 0 0 -.82739 16.141 3.723)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="io7AIFe" cx="0" cy="0" r="1" gradientTransform="matrix(3.2594 -5.16072 5.71755 3.61108 10.384 7.716)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="i1I7JZA" cx="0" cy="0" r="1" gradientTransform="matrix(3.56024 -2.8663 4.44214 5.5176 17.828 6.311)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iGljwje" cx="0" cy="0" r="1" gradientTransform="matrix(2.99677 -2.68215 4.91032 5.48632 18.552 7.585)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="i8nGezd" cx="0" cy="0" r="1" gradientTransform="matrix(3.2666 .7334 -.30706 1.36766 17.677 5.741)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iPbhIpv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82171 -1.30703 0 18.094 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iflAAfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23489 -.30269 .41673 -.32339 17.863 10.164)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRornKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82176 -1.3071 0 13.675 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iB7g49P" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.762 -1.438)scale(.50048 .60159)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ij8MRoc" cx="0" cy="0" r="1" gradientTransform="matrix(.6366 2.27202 -2.16768 .60737 20.561 10.092)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iy54n7d" cx="0" cy="0" r="1" gradientTransform="matrix(.79788 -1.09496 .9178 .66878 20.926 10.644)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="ieOqgkc" cx="0" cy="0" r="1" gradientTransform="matrix(.59452 -1.57028 2.09812 .79436 21.041 10.819)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="izO6Qnx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6795 0 0 -1.8754 10.906 10.742)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iCQHOHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.92822 .15933 -.16336 -.95172 10.907 10.744)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="iwfzppb" width="6.906" height="10.938" x="12.293" y="16.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.329412 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_785"/></filter><filter id="i6NfQ5g" width="3.076" height="1.977" x="15.252" y="17.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".3"/></filter><filter id="ilS8U0d" width="11.351" height="12.6" x="10.756" y="4.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_785"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_785" result="effect2_innerShadow_4002_785"/></filter><filter id="iMsBxRb" width="3.769" height="4.937" x="13.856" y="9.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".5"/></filter><filter id="iP0B4gF" width="2.301" height="3.337" x="14.734" y="9.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".1"/></filter><filter id="io8o5Be" width="3.76" height="1.587" x="14.005" y="13.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".05"/></filter><filter id="iXmSmXL" width="13.038" height="8.457" x="9.365" y="1.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_785"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_785" result="effect2_innerShadow_4002_785"/></filter><filter id="iVmecqZ" width="2.368" height="1.203" x="17.494" y="7.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_785"/></filter><filter id="iHzpi9W" width="2.368" height="1.188" x="12.17" y="7.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_785"/></filter><filter id="ixO3YFe" width="6.662" height="6.062" x="9.729" y="2.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_785"/><feGaussianBlur result="effect2_foregroundBlur_4002_785" stdDeviation=".125"/></filter><filter id="iRawyBW" width="7.19" height="6.056" x="15.723" y="2.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_785"/><feGaussianBlur result="effect2_foregroundBlur_4002_785" stdDeviation=".125"/></filter><filter id="ieWS2XO" width=".794" height=".703" x="17.352" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".05"/></filter><filter id="inE0Kde" width=".898" height=".92" x="18.204" y="9.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".1"/></filter><filter id="igwgR6b" width=".994" height="1.048" x="13.704" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".1"/></filter><filter id="iEJRnUb" width=".922" height=".711" x="12.939" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".05"/></filter><filter id="igZvrub" width="1.34" height="2.403" x="9.729" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".125"/></filter><filter id="izKnvpd" width="1.816" height="2.78" x="20.499" y="9.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".25"/></filter><filter id="ilp0Nze" width="2.426" height="1.166" x="12.093" y="7.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".125"/></filter><filter id="i5TObQb" width="2.426" height="1.166" x="17.477" y="7.315" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".125"/></filter><filter id="i5WNhac" width="5.417" height="3.066" x="16.923" y="3.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_785" stdDeviation=".375"/></filter><linearGradient id="iFqMHgd" x1="24.158" x2="24.189" y1="30.329" y2="26.673" gradientUnits="userSpaceOnUse"><stop offset=".078" class="npfrbd3jd"/><stop offset="1" class="w_5-rbc1a"/></linearGradient><linearGradient id="iS6d3Rd" x1="18.12" x2="19.472" y1="27.765" y2="28.151" gradientUnits="userSpaceOnUse"><stop class="p5jt_ib0l"/><stop offset="1" class="hw19_ybat"/></linearGradient><linearGradient id="iU0xveW" x1="13.658" x2="12.158" y1="28.736" y2="29.267" gradientUnits="userSpaceOnUse"><stop class="h65uoi6pi"/><stop offset="1" class="g04ogacjt"/></linearGradient><linearGradient id="iMrfvye" x1="12.315" x2="13.69" y1="27.392" y2="26.829" gradientUnits="userSpaceOnUse"><stop offset=".223" class="d05zivoho"/><stop offset="1" class="ue2ywxbfs"/></linearGradient><linearGradient id="izyBClb" x1="15.627" x2="14.221" y1="30.173" y2="29.486" gradientUnits="userSpaceOnUse"><stop offset=".208" class="cu8bl7b6w"/><stop offset="1" class="bkwavzmor"/></linearGradient><linearGradient id="i1Dor5L" x1="16.002" x2="18.033" y1="24.829" y2="25.736" gradientUnits="userSpaceOnUse"><stop class="ego3-fbwo"/><stop offset="1" class="up5p4s41k"/></linearGradient><linearGradient id="iDsaIEc" x1="16.366" x2="16.366" y1="25.145" y2="15.619" gradientUnits="userSpaceOnUse"><stop class="on-ymlb8c"/><stop offset="1" class="czjae1pgq"/></linearGradient><linearGradient id="iGhIIIc" x1="21.108" x2="18.546" y1="12.713" y2="12.713" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="i8pn5HN" x1="16.733" x2="15.884" y1="11.69" y2="11.725" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iesUOZd" x1="15.884" x2="15.884" y1="12.844" y2="12.373" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iVr4vHj" x1="15.884" x2="15.884" y1="10.104" y2="10.657" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="iQRNDpe" x1="16.305" x2="16.305" y1="12.983" y2="12.788" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="i6bk53b" x1="14.667" x2="14.99" y1="14.435" y2="13.589" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="i1hUSkd" x1="22.824" x2="11.063" y1="5.271" y2="5.271" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="i5BynNe" x1="18.882" x2="18.564" y1="10.133" y2="10.329" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWsLcyv" x1="14.428" x2="14.11" y1="10.133" y2="10.329" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixYsyhe" x1="22.403" x2="21.181" y1="10.16" y2="12.364" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="imcRQsd" x1="9.96" x2="11.437" y1="10.873" y2="10.744" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="ikx3Z7H" x1="21.407" x2="21.407" y1="9.847" y2="11.628" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-steamy-room-medium" /></template>
<style>
.a57mrebnw {
  cx: 13.4px;
  cy: 9.981px;
  rx: 0.395px;
  ry: 0.2px;
}

.a66gbwbzh {
  stop-color: var(--svg-color--f65c3e, #F65C3E);
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.atms-xm-n {
  stop-color: var(--svg-color--9e2625, #9E2625);
  stop-opacity: 0;
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc2qs9bhj {
  stop-color: var(--svg-color--ff7347, #FF7347);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bkwavzmor {
  stop-color: var(--svg-color--dd5022, #DD5022);
  stop-opacity: 0;
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.bnw25vlzu {
  d: path("M16.12 5.319a2 2 0 0 1-.067-.139a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.423v.278c-.344-.262-.777-.814-.777-1.709c0-1.086.792-1.634 1.297-1.984c.142-.1.262-.182.335-.257l.1-.106c.354-.375.985-1.044 2.087-1.337a5.5 5.5 0 0 1 1.537-.167c.473.013.806.42.806.894v1.514z");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqgvl433q {
  stop-color: var(--svg-color--f47246, #F47246);
  stop-opacity: 0;
}

.cu8bl7b6w {
  stop-color: var(--svg-color--dd5022, #DD5022);
}

.czjae1pgq {
  stop-color: var(--svg-color--a77c63, #A77C63);
}

.d05zivoho {
  stop-color: var(--svg-color--e45c36, #E45C36);
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.db8dllnoa {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.468 8.161c.26-.186.909-.515 1.676-.386");
}

.dg137t4cd {
  d: path("M20.801 4.278c.521.18.989.544 1.284 1.065a2.4 2.4 0 0 1-.107 2.559a1.6 1.6 0 0 0-.274.885V9.99a1.8 1.8 0 0 0-.676-.271l.08-1.627a1.47 1.47 0 0 0-1.397-1.45h-1.418a2.45 2.45 0 0 1-2.24-1.462a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.423l.031 1.557a1.7 1.7 0 0 0-.73.267V8.787a1.6 1.6 0 0 0-.273-.885a2.42 2.42 0 0 1-.145-2.477a2.37 2.37 0 0 1 1.316-1.141a2.7 2.7 0 0 0 1.402-1.125a2.355 2.355 0 0 1 2.928-.923a1.5 1.5 0 0 0 1.208 0c.285-.12.597-.19.924-.19c.854 0 1.6.461 2.014 1.146c.312.516.8.89 1.37 1.086");
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dk0gm-byq {
  fill: var(--svg-color--ec551b, #EC551B);
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0fn1k-pa {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.516 13.54c.395.207.866.325 1.368.325c.508 0 .974-.118 1.369-.324a.23.23 0 0 1 .274.044a.215.215 0 0 1 .023.275m-3.034-.32l2.972.279m-2.972-.278a.23.23 0 0 0-.274.047a.214.214 0 0 0-.024.273m.298-.32l-.235.278m3.27.041l-.063-.041m.063.041l-.063-.041m.063.041c-.353.535-.967.89-1.667.89a2 2 0 0 1-1.665-.889m3.269-.042c-.34.514-.93.857-1.604.857a1.92 1.92 0 0 1-1.603-.857m-.062.042l.062-.042m-.062.042l.062-.042");
}

.e9j5vvbvj {
  stop-color: var(--svg-color--72372a, #72372A);
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.ego3-fbwo {
  stop-color: var(--svg-color--ce3b1b, #CE3B1B);
}

.epaghdc0t {
  d: path("M10.998 13.807a3.966 3.966 0 0 0 3.935 3.45h1.91a3.966 3.966 0 0 0 3.936-3.45c.12-1.908.24-3.808.329-5.715a1.47 1.47 0 0 0-1.397-1.45h-1.418a2.45 2.45 0 0 1-2.24-1.462a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.423c0 1.884.118 3.738.242 5.628");
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f2ocbl9zr {
  stroke: var(--svg-color--be937f, #BE937F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.152 18.338c.19.027.71.032 1.275-.163");
}

.f7fam02nn {
  d: path("M18.097 9.595a.904.904 0 0 1 .87 1.142h-1.746a.907.907 0 0 1 .875-1.142");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fqhi7bcqx {
  fill: var(--svg-color--533634, #533634);
  d: path("M16.12 5.319a2 2 0 0 1-.067-.139a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.423v.278c-.344-.262-.777-.814-.777-1.709c0-1.086.792-1.634 1.297-1.984c.142-.1.262-.182.335-.257l.1-.106c.354-.375.985-1.044 2.087-1.337a5.5 5.5 0 0 1 1.537-.167c.473.013.806.42.806.894v1.514z");
}

.ft5dv1b6b {
  fill: none;
}

.g04ogacjt {
  stop-color: var(--svg-color--d63c26, #D63C26);
  stop-opacity: 0;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.ge5nr6cth {
  fill: var(--svg-color--000, #000);
  d: path("M14.19 10.499a.516.516 0 0 0-.518-.518a.516.516 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.238");
}

.gi6_xeb7a {
  d: path("M10.734 9.792a.968.968 0 0 0 .084 1.904a79 79 0 0 1-.084-1.904");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gl1a3jbde {
  d: path("M20.808 12.272c.34-.01.657-.126.916-.312v.943a2.2 2.2 0 0 1-1.358 2.044q.26-.552.35-1.195z");
}

.gt-y46nru {
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gyulks50m {
  stop-color: var(--svg-color--9e2625, #9E2625);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h3e5alaje {
  stop-color: var(--svg-color--c03005, #C03005);
}

.h65uoi6pi {
  stop-color: var(--svg-color--d63c26, #D63C26);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hmw-mjbkr {
  d: path("M10.96 12.272a1.66 1.66 0 0 1-.916-.312v.943a2.2 2.2 0 0 0 1.358 2.044a4.1 4.1 0 0 1-.35-1.195z");
}

.hrqpq4_5o {
  cx: 13.4px;
  cy: 9.981px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.hw19_ybat {
  stop-color: var(--svg-color--e04438, #E04438);
  stop-opacity: 0;
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i72-7-vuk {
  d: path("M10.775 9.119a1.644 1.644 0 0 0-1.41 1.618c0 .87.682 1.581 1.54 1.628a79 79 0 0 1-.13-3.246");
}

.i8o1iacxv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.306 9.32c.662 0 1.22.456 1.372 1.072a.278.278 0 0 1-.27.345h-2.26a.233.233 0 0 1-.23-.275a1.416 1.416 0 0 1 1.388-1.142");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.iksuiqrgf {
  cx: 8.275px;
  cy: 23.368px;
  r: 6.305px;
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jne7u7bpd {
  d: path("M18.03 9.786c.064.086-.07.191-.223.306s-.267.195-.331.109c-.065-.087.007-.25.16-.364s.33-.137.394-.05");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k-y64ibbx {
  stop-color: var(--svg-color--99201f, #99201F);
}

.k3qin7bzy {
  stop-color: var(--svg-color--b22307, #B22307);
}

.kb1fxpbfw {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.43 7.878a2.8 2.8 0 0 1 1.761-.364a.28.28 0 0 1-.068.558a2.25 2.25 0 0 0-1.405.288q-.052.031-.076.049l-.017.012l-.003.002a.28.28 0 0 1-.344-.444z");
}

.ktoycacxm {
  stop-color: var(--svg-color--f6682e, #F6682E);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l0nudab1i {
  stop-color: var(--svg-color--865144, #865144);
  stop-opacity: 0;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj_bse8ns {
  stop-color: var(--svg-color--a3776e, #A3776E);
}

.lr6p412xr {
  fill: var(--svg-color--ed561d, #ED561D);
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.ma74w36yx {
  stop-color: var(--svg-color--b68a79, #B68A79);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n5l_opbqq {
  r: 6.305px;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.njqb132eq {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.497 10.283l-.538 1.861c-.11.383.154.766.527.766h.796c.374 0 .638-.389.528-.766l-.538-1.861c-.116-.413-.654-.413-.775 0");
}

.nkhjjib0d {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.529 8.105c-.26-.187-.91-.515-1.677-.386");
}

.npfrbd3jd {
  stop-color: var(--svg-color--dd3537, #DD3537);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofax10bwa {
  d: path("M20.87 12.364q.1-1.616.186-3.232a1.63 1.63 0 0 1-.187 3.232");
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.on-ymlb8c {
  stop-color: var(--svg-color--b2806f, #B2806F);
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

.p5jt_ib0l {
  stop-color: var(--svg-color--e04438, #E04438);
}

.pbkzvtx_w {
  stop-color: var(--svg-color--e06d3d, #E06D3D);
}

.pjzr3aclu {
  stop-color: var(--svg-color--d03d1c, #D03D1C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qdnqv10ox {
  d: path("M13.673 9.595a.904.904 0 0 0-.872 1.142h1.747a1 1 0 0 0 .033-.238a.91.91 0 0 0-.909-.904");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qnar36wle {
  r: 4.086px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_bcr-ntk {
  cx: 10.674px;
  cy: 16.165px;
  r: 4.086px;
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r-vpu7toc {
  d: path("M18.901 10.38a.85.85 0 0 0-.234-.469l-.263.29l.119.23z");
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.rd74zdb3c {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.478 10.48l-.599 1.863c-.102.383.144.766.491.766h.741c.348 0 .593-.39.49-.766l-.5-1.862c-.107-.413-.51-.413-.623 0");
}

.rgs-6fbpw {
  d: path("M5.096 29.939c0-7.961 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.rl6zs7yhb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.463 9.32c-.662 0-1.22.456-1.372 1.072a.278.278 0 0 0 .27.345h2.26a.233.233 0 0 0 .23-.275a1.42 1.42 0 0 0-1.388-1.142");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rt8f9chvu {
  fill: var(--svg-color--000, #000);
  d: path("M17.579 10.5c0-.289.23-.519.517-.519a.516.516 0 0 1 .46.756h-.916a.47.47 0 0 1-.061-.238");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s6ufut5ul {
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.spnbbobfl {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.665 7.988a1.9 1.9 0 0 0-.696-.416c-.308-.097-.694-.123-1.228-.058a.28.28 0 0 0 .068.558c.487-.06.786-.029.991.036c.2.063.337.165.496.304a.28.28 0 1 0 .369-.424");
}

.tgex-ob-h {
  d: path("m15.497 10.283l-.538 1.861c-.11.383.154.766.527.766h.796c.374 0 .638-.389.528-.766l-.538-1.861c-.116-.413-.654-.413-.775 0");
}

.u4bo2-o9a {
  stop-color: var(--svg-color--d84f1a, #D84F1A);
  stop-opacity: 0;
}

.ue2ywxbfs {
  stop-color: var(--svg-color--e45c36, #E45C36);
  stop-opacity: 0;
}

.uf6ynwk4b {
  d: path("m21.164 8.627l-.03-.64c-.01-.772-.65-1.41-1.423-1.443h-1.418c-.9 0-1.721-.492-2.151-1.276c0 0-.063-.146-.127-.394c-.251-.971.675-1.713 1.66-1.524c.991.19 2.125.524 2.961 1.07c1.767 1.152 1.458 3.23.528 4.207");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.uny96bcfc {
  d: path("M14.498 10.393c0-.292-.237-.487-.302-.546l-.292.283l.18.366z");
}

.up5p4s41k {
  stop-color: var(--svg-color--e64812, #E64812);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uwipchbui {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.03 9.786c.064.086-.07.191-.223.306s-.267.195-.331.109c-.065-.087.007-.25.16-.364s.33-.137.394-.05");
}

.uygoe8bue {
  d: path("M14.01 16.517h4v.887c.01.175.045.374.152.53a.8.8 0 0 0 .445.333l.465.164c.076.068.22.478.04.984c-.181.505-2.043 5.51-3.094 8.02v.02l-.005-.01q0 .004-.004.01v-.02c-1.052-2.51-3.186-7.515-3.366-8.02c-.182-.506-.076-.87 0-.937l.68-.192c.218-.062.373-.14.515-.347c.113-.166.158-.39.172-.572z");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.v9nf3osdu {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.34 5.322h-2.165a.502.502 0 1 1 .08-1c.562.09 1.307.214 1.807.338c1.129.28 1.44.83 1.528 1.221a1.57 1.57 0 0 0-1.25-.56");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vytk550vf {
  d: path("M21 11.628q.049-.89.095-1.78c.406.054.72.43.72.886c0 .49-.364.89-.816.894");
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w_5-rbc1a {
  stop-color: var(--svg-color--dd3537, #DD3537);
  stop-opacity: 0;
}

.w82swe3sw {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.164 8.627l-.03-.64c-.01-.772-.65-1.41-1.423-1.443h-1.418c-.9 0-1.721-.492-2.151-1.276c0 0-.063-.146-.127-.394c-.251-.971.675-1.713 1.66-1.524c.991.19 2.125.524 2.961 1.07c1.767 1.152 1.458 3.23.528 4.207");
}

.w8e9izb-y {
  d: path("M26.947 29.939c0-7.961-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wkmk90b2p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 24.017h3.298a5.94 5.94 0 0 1 5.937 5.937H1.971zm28.06 0h-3.298a5.94 5.94 0 0 0-5.937 5.937h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x3axlob0n {
  stop-color: var(--svg-color--e24c14, #E24C14);
  stop-opacity: 0;
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
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

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yf3t3eb5f {
  stop-color: var(--svg-color--ff8244, #FF8244);
}

.ykdcls_lk {
  stop-color: var(--svg-color--dd3d3d, #DD3D3D);
}

.ynk0bfbpf {
  d: path("M15.884 13.94c-.514 0-.997-.121-1.403-.333c-.139-.07-.288.086-.2.212c.339.514.93.857 1.603.857c.674 0 1.265-.343 1.604-.857c.087-.131-.062-.282-.2-.212a3 3 0 0 1-1.404.333");
}

.z2ddyab4m {
  stop-color: var(--svg-color--f47246, #F47246);
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
