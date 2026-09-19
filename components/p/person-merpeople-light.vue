<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inAoLFe)"><path class="td6euhb6l"/></g><path fill="url(#itsSeme)" class="i6tnjcu8m"/><g filter="url(#iPdjb4b)"><path fill="url(#icQ8Rgb)" class="if2-x0_3s"/></g><path class="rwh2s_4_v"/><path fill="url(#itUu57r)" class="r_cv6ppfn"/><path fill="url(#ijfyQBe)" class="r_cv6ppfn"/><path fill="url(#i6yXgFw)" class="r_cv6ppfn"/><g filter="url(#iJQ79iT)"><path fill="url(#itZ0Srg)" class="bb2fbgrpu"/></g><g filter="url(#ie01Tcb)"><path class="yk4r1ybxd"/><path fill="url(#iexmzpb)" class="gejm97-ji"/><path fill="url(#iJN5VDD)" class="gejm97-ji"/><path fill="url(#iZo0w8d)" class="gejm97-ji"/></g><g filter="url(#i4duytd)"><path class="so-vzri7t"/><path fill="url(#iXgJ6Pd)" class="yr50mjbls"/><path fill="url(#i6ISRKb)" class="yr50mjbls"/></g><g filter="url(#izoxJ4Q)"><path fill="url(#i5hBc1c)" class="uwupv_ztt"/><path fill="url(#iskeGDX)" class="uwupv_ztt"/></g><path fill="url(#iYcj16d)" class="uwupv_ztt"/><path fill="url(#iZqERtb)" class="uwupv_ztt"/><g filter="url(#iv2Rkby)"><path class="qq8y08i1v"/><path fill="url(#ihuc6Oc)" class="lrtdxszpp"/></g><g filter="url(#iN5WxUb)"><path stroke="url(#iFIIACe)" class="bxy95rb0r"/></g><g filter="url(#ia0pEud)"><path stroke="url(#i7u1svb)" class="tf5rpdjwu"/></g><g filter="url(#imy82fb)"><path stroke="url(#iUCaIqe)" class="w-8ib2bba"/></g><g filter="url(#iqrBWMd)"><path stroke="url(#ib73wnu)" class="lk8uk6bqv"/></g><g filter="url(#idqAfZb)"><path class="zkv-t1bbq"/></g><g filter="url(#iMQ7sdQ)"><path stroke="url(#iemvRMb)" class="w-3uv5bmy"/></g><g filter="url(#ivh2h9F)"><path stroke="url(#iVq0d5V)" class="ry_er4bde"/></g><path fill="url(#i3RuBfb)" class="sr3b7ccow"/><path fill="url(#iVISUte)" class="gv6mn6b1l"/><g filter="url(#iGYjSsb)"><path fill="url(#i6cxcOd)" class="z68enctpn"/></g><path fill="url(#io8Cp8c)" class="z68enctpn"/><path fill="url(#iZyUWMd)" class="z68enctpn"/><path fill="url(#ieMZW9d)" class="z68enctpn"/><path fill="url(#inbBBhd)" class="z68enctpn"/><path fill="url(#iypopHb)" class="z68enctpn"/><path fill="url(#ialUmre)" class="z68enctpn"/><path fill="url(#iOy2glc)" class="z68enctpn"/><g filter="url(#iBhhQvc)"><path class="oj4p0xbcu"/></g><g filter="url(#igL4Vjb)"><path class="h39qs2bdc"/><path fill="url(#iBttaQb)" class="c52b9egiw"/><path fill="url(#ivYsoYc)" class="c52b9egiw"/><path fill="url(#icSIk5b)" class="c52b9egiw"/><path fill="url(#ilOJfkr)" class="c52b9egiw"/><path fill="url(#ivACdRc)" class="c52b9egiw"/></g><path fill="url(#iwTdC5b)" class="b9vg0s1uh"/><g filter="url(#ivLNAnc)"><path fill="url(#i12fVWb)" class="p0vh6_8oj"/><path fill="url(#iS9djre)" class="p0vh6_8oj"/><path fill="url(#iIX5oAe)" class="p0vh6_8oj"/><path fill="url(#i8Q4nle)" class="p0vh6_8oj"/><path fill="url(#iiKLvQe)" class="p0vh6_8oj"/></g><g filter="url(#ijQDEOd)"><path class="tjs3mxdap"/></g><g filter="url(#iZUL7mc)"><path class="awfpp-3qr"/></g><g filter="url(#iuGeVFd)"><path class="g906eacpp"/><path fill="url(#iGZDZtd)" class="glvmfs77h"/><path fill="url(#izOfJjb)" class="glvmfs77h"/></g><g filter="url(#it5LqEc)"><path class="o1o8fjb5d"/><path fill="url(#iZkzVoc)" class="vm-_3abon"/><path fill="url(#i1fN3kd)" class="vm-_3abon"/><path fill="url(#iCXGp2b)" class="vm-_3abon"/></g><path class="geedh9bvt"/><path fill="url(#izOktfd)" class="jppowlbfw"/><path class="xggiw4btv"/><g filter="url(#ipZWCJd)"><path class="w56t05b1o"/><path fill="url(#ikTHwze)" class="c0eouzbpy"/></g><g filter="url(#i6znLcb)"><path fill="url(#ixyGkfl)" class="e8kldcmkw"/></g><path class="hahaolefz"/><path fill="url(#iuaMrod)" class="ggum98baz"/><path class="bga96_bnr"/><g filter="url(#i3q0cEd)"><path fill="url(#i9KksKb)" class="tghgar6wi"/></g><g filter="url(#i9Jmegd)"><ellipse transform="rotate(-27.914 16.106 6.57)" class="gfrv1jtdi"/><ellipse fill="url(#iThqfOc)" transform="rotate(-27.914 16.106 6.57)" class="s_vs1kbww"/></g><path fill="url(#iVu2Bzd)" class="osb6p5bii"/><path fill="url(#inXR3be)" class="osb6p5bii"/><path fill="url(#ielSFvd)" class="osb6p5bii"/><path fill="url(#iZmtn2c)" class="osb6p5bii"/><path fill="url(#iE1hYOe)" class="l_2tb3bub"/><path fill="url(#iEJleSd)" class="l_2tb3bub"/><g filter="url(#iQUGS0W)"><path fill="url(#ibpoEzd)" class="ye27a6avl"/></g><g filter="url(#iEqkfed)"><path fill="url(#i2GrpXc)" class="qti3hfbnx"/></g><defs><radialGradient id="itsSeme" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.822 -23.113)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="icQ8Rgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.617)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="ijfyQBe" cx="0" cy="0" r="1" gradientTransform="matrix(.82293 -.97657 .81738 .68878 6.74 17.01)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="t33371etg"/><stop offset="1" class="rtl5rdb5z"/><stop offset="1" class="bjatx4b1r"/></radialGradient><radialGradient id="i6yXgFw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8737 -1.06183 0 7.227 16.494)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="duqocmbtl"/><stop offset="1" class="idh4njbua"/></radialGradient><radialGradient id="iJN5VDD" cx="0" cy="0" r="1" gradientTransform="matrix(.88953 2.91279 -1.06086 .32398 23.622 10.366)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="a8wtrgabv"/><stop offset="1" class="rb8xsab7w"/></radialGradient><radialGradient id="iZo0w8d" cx="0" cy="0" r="1" gradientTransform="matrix(.53214 0 0 2.90625 23.327 8.716)" gradientUnits="userSpaceOnUse"><stop class="jleiqdg7d"/><stop offset="1" class="ss6kf5hyw"/></radialGradient><radialGradient id="iXgJ6Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57032 .46875 -.2011 -.24468 25.71 7.406)" gradientUnits="userSpaceOnUse"><stop class="othzxvbxc"/><stop offset="1" class="evkljqb4p"/></radialGradient><radialGradient id="i6ISRKb" cx="0" cy="0" r="1" gradientTransform="rotate(-140.258 14.327 -.219)scale(.90426 .73334)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="cpfm5rbrk"/><stop offset="1" class="w7zfnqfut"/></radialGradient><radialGradient id="i5hBc1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.46875 -5.71107 0 19.177 12.742)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="dw0qvsbps"/><stop offset="1" class="yafg_whjr"/></radialGradient><radialGradient id="iskeGDX" cx="0" cy="0" r="1" gradientTransform="rotate(58.499 -1.805 23.135)scale(1.85402 1.92266)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="pygktylau"/><stop offset="1" class="dqd47gnac"/></radialGradient><radialGradient id="iZqERtb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.00003 -7.0781 9.3879 -5.30536 19.333 16.96)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="gv9be6ybc"/><stop offset="1" class="nqt5hcbes"/></radialGradient><radialGradient id="ihuc6Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.47103 2.30187 -1.86833 -2.81728 17.116 9.537)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="w7c-tt7cs"/><stop offset="1" class="a9_7dobbq"/></radialGradient><radialGradient id="i3RuBfb" cx="0" cy="0" r="1" gradientTransform="matrix(.43002 1.1598 -1.37777 .51083 20.244 7.691)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iVISUte" cx="0" cy="0" r="1" gradientTransform="matrix(.84793 .2665 -.82214 2.6159 14.037 7.973)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="i6cxcOd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00234 0 0 -5.3111 19.127 7.15)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iZyUWMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.26151 -5.18528 0 17.85 4.826)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="qcba1ryxr"/><stop offset=".961" class="fhx-y7b1d"/></radialGradient><radialGradient id="ieMZW9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6595 .81612 0 18.92 6.397)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="inbBBhd" cx="0" cy="0" r="1" gradientTransform="matrix(.00226 -.62844 .6839 .00246 16.194 6.423)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iypopHb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.621 4.166)scale(4.88893 12.4888)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="ialUmre" cx="0" cy="0" r="1" gradientTransform="matrix(1.7794 -1.8824 .6891 .65139 14.375 4.667)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="iOy2glc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 8.244 7.477)scale(1.93479 1.59733)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="ivYsoYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .14019 -.44059 0 17.782 7.932)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="ilOJfkr" cx="0" cy="0" r="1" gradientTransform="matrix(-.87359 .40053 -.64369 -1.40393 17.848 7.603)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iwTdC5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.41392 1.66529 0 17.514 9.183)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iS9djre" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.0108 5.08508 0 14.511 5.49)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iIX5oAe" cx="0" cy="0" r="1" gradientTransform="matrix(.0655 -1.44294 2.55662 .11604 20.306 6.242)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i8Q4nle" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35467 -.89097 .65401 -.9944 19.873 2.638)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iiKLvQe" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.958 16.046)scale(.99385 2.30131)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iGZDZtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2641 0 0 -.46916 17.66 3.02)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="izOfJjb" cx="0" cy="0" r="1" gradientTransform="matrix(1.84818 -2.9263 3.24204 2.0476 14.396 5.284)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iZkzVoc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75642 0 0 .68673 19.475 3.466)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="i1fN3kd" cx="0" cy="0" r="1" gradientTransform="matrix(1.53838 -1.4657 2.68333 2.81638 19.027 5.21)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iCXGp2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.86544 .21805 -.0913 .78102 18.52 4.363)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="izOktfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46594 -.74113 0 18.768 6.624)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ikTHwze" cx="0" cy="0" r="1" gradientTransform="matrix(-.13319 -.17163 .2363 -.18337 18.637 6.673)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuaMrod" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46596 -.74116 0 16.262 6.624)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iThqfOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00444 -.28376 .34108 -.00534 16.096 6.75)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="inXR3be" cx="0" cy="0" r="1" gradientTransform="matrix(.36097 1.2883 -1.22914 .3444 20.167 6.632)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="ielSFvd" cx="0" cy="0" r="1" gradientTransform="matrix(.45242 -.62087 .52042 .37922 20.374 6.945)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iZmtn2c" cx="0" cy="0" r="1" gradientTransform="matrix(.33711 -.8904 1.1897 .45043 20.44 7.044)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iEJleSd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92644 -.1132 .1215 -.99448 14.692 7.002)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="ibpoEzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.52633 .09035 -.11086 -.64584 14.692 7.002)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><filter id="inAoLFe" width="16.97" height="13.626" x="7.639" y="16.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1302" result="effect2_innerShadow_4002_1302"/></filter><filter id="iPdjb4b" width="8.803" height="12.453" x="15.083" y="15.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".5"/></filter><filter id="iJQ79iT" width="9.329" height="6.572" x="5.433" y="10.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.631373 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1302" result="effect2_innerShadow_4002_1302"/></filter><filter id="ie01Tcb" width="5.98" height="8.393" x="20.337" y="7.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.513726 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/></filter><filter id="i4duytd" width="1.41" height="1.949" x="24.485" y="7.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.627451 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/></filter><filter id="izoxJ4Q" width="6.555" height="7.624" x="14.255" y="10.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.470588 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/></filter><filter id="iv2Rkby" width="4.212" height="3.197" x="15.358" y="10.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.6 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/></filter><filter id="iN5WxUb" width="11.112" height="3.615" x="10.829" y="25.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".2"/></filter><filter id="ia0pEud" width="3.297" height="3.17" x="8.245" y="23.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".2"/></filter><filter id="imy82fb" width="3.085" height="3.032" x="11.506" y="23.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".2"/></filter><filter id="iqrBWMd" width="4.07" height="2.867" x="20.64" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".25"/></filter><filter id="idqAfZb" width="1.994" height="6.666" x="24.456" y="8.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".2"/></filter><filter id="iMQ7sdQ" width="2.251" height="3.579" x="23.392" y="7.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".2"/></filter><filter id="ivh2h9F" width="6.781" height="4.219" x="7.807" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".25"/></filter><filter id="iGYjSsb" width="6.87" height="7.288" x="14.607" y="3.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1302" result="effect2_innerShadow_4002_1302"/></filter><filter id="iBhhQvc" width="3.003" height="3.666" x="15.932" y="5.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".5"/></filter><filter id="igL4Vjb" width="1.178" height="1.766" x="16.926" y="6.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".025"/></filter><filter id="ivLNAnc" width="7.393" height="5.012" x="13.818" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1302" result="effect2_innerShadow_4002_1302"/></filter><filter id="ijQDEOd" width="1.386" height=".769" x="18.427" y="4.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/></filter><filter id="iZUL7mc" width="1.386" height=".76" x="15.409" y="4.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/></filter><filter id="iuGeVFd" width="3.994" height="3.446" x="14.066" y="2.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1302"/><feGaussianBlur result="effect2_foregroundBlur_4002_1302" stdDeviation=".05"/></filter><filter id="it5LqEc" width="3.473" height="3.158" x="17.561" y="2.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".05"/></filter><filter id="ipZWCJd" width=".537" height=".485" x="18.304" y="6.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".05"/></filter><filter id="i6znLcb" width=".682" height=".695" x="18.743" y="6.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".1"/></filter><filter id="i3q0cEd" width=".737" height=".768" x="16.192" y="6.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".1"/></filter><filter id="i9Jmegd" width=".61" height=".49" x="15.801" y="6.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".05"/></filter><filter id="iQUGS0W" width=".976" height="1.579" x="13.916" y="6.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".125"/></filter><filter id="iEqkfed" width="1.544" height="2.093" x="19.89" y="5.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1302" stdDeviation=".25"/></filter><linearGradient id="itUu57r" x1="6.74" x2="7.001" y1="16.863" y2="16.863" gradientUnits="userSpaceOnUse"><stop class="n_rrf5c9b"/><stop offset="1" class="sc-ixwf5u"/></linearGradient><linearGradient id="itZ0Srg" x1="10.656" x2="11.312" y1="14.335" y2="16.773" gradientUnits="userSpaceOnUse"><stop class="usg16obsd"/><stop offset="1" class="m_70hebjx"/></linearGradient><linearGradient id="iexmzpb" x1="22.218" x2="22.984" y1="14.335" y2="12.945" gradientUnits="userSpaceOnUse"><stop class="zcfme9b2u"/><stop offset="1" class="ozmzmdbmh"/></linearGradient><linearGradient id="iYcj16d" x1="13.802" x2="15.755" y1="16.085" y2="16.085" gradientUnits="userSpaceOnUse"><stop class="x8wsft-hb"/><stop offset="1" class="m0mihob_v"/></linearGradient><linearGradient id="iFIIACe" x1="11.768" x2="20.875" y1="27.015" y2="28.857" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="i7u1svb" x1="10.518" x2="8.203" y1="25.807" y2="25.435" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUCaIqe" x1="14.013" x2="13.482" y1="24.145" y2="26.255" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ib73wnu" x1="24.406" x2="22.549" y1="14.21" y2="15.252" gradientUnits="userSpaceOnUse"><stop offset=".358" class="ywzroibeu"/><stop offset="1" class="cl8aicb8x"/></linearGradient><linearGradient id="iemvRMb" x1="24.517" x2="24.517" y1="7.765" y2="10.144" gradientUnits="userSpaceOnUse"><stop offset=".355" class="c770b9b5t"/><stop offset="1" class="kdih-nphy"/></linearGradient><linearGradient id="iVq0d5V" x1="13.839" x2="13.674" y1="13.023" y2="17.912" gradientUnits="userSpaceOnUse"><stop class="vjc3blqru"/><stop offset="1" class="pbxwl2bes"/></linearGradient><linearGradient id="io8Cp8c" x1="20.477" x2="17.977" y1="8.119" y2="8.119" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iBttaQb" x1="18.338" x2="17.515" y1="7.398" y2="7.558" gradientUnits="userSpaceOnUse"><stop class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="icSIk5b" x1="17.515" x2="17.515" y1="8.192" y2="7.925" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="ivACdRc" x1="17.515" x2="17.515" y1="6.565" y2="6.953" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="i12fVWb" x1="21.45" x2="14.781" y1="3.899" y2="3.899" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ixyGkfl" x1="19.215" x2="19.034" y1="6.655" y2="6.766" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9KksKb" x1="16.689" x2="16.509" y1="6.655" y2="6.766" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVu2Bzd" x1="21.211" x2="20.518" y1="6.671" y2="7.921" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iE1hYOe" x1="14.155" x2="14.993" y1="7.075" y2="7.002" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="i2GrpXc" x1="20.661" x2="20.661" y1="6.457" y2="7.55" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-merpeople-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a8wtrgabv {
  stop-color: var(--svg-color--e19e8b, #E19E8B);
}

.a9_7dobbq {
  stop-color: var(--svg-color--c98368, #C98368);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.awfpp-3qr {
  fill: var(--svg-color--202020, #202020);
  d: path("M15.556 5.377a1.6 1.6 0 0 1 .999-.206a.16.16 0 1 1-.04.316a1.27 1.27 0 0 0-.839.19l-.01.008a.16.16 0 0 1-.196-.251z");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b9vg0s1uh {
  d: path("M17.514 8.814c-.291 0-.565-.069-.795-.189c-.079-.04-.163.049-.114.12c.192.292.528.486.91.486c.381 0 .716-.194.909-.486c.05-.074-.035-.16-.114-.12c-.23.12-.501.189-.796.189");
}

.bb2fbgrpu {
  d: path("m6.569 15.067l-.755.857a.526.526 0 0 0 .776.71l.554-.583a.384.384 0 0 1 .476-.065l.018.01a.1.1 0 0 1 .019.155l-.317.316a.528.528 0 0 0 .716.774l.557-.479a.2.2 0 0 1 .13-.048h1.765a2.5 2.5 0 0 0 1.64-.613l2.365-2.055v-3.25c-.257.025-.59.285-.723.418l-3.247 3.04a.5.5 0 0 1-.284.132l-3.068.355a.98.98 0 0 0-.622.326");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bga96_bnr {
  fill: var(--svg-color--000, #000);
  d: path("M16.554 6.863a.29.29 0 0 0-.294-.294a.292.292 0 0 0-.26.429h.519a.3.3 0 0 0 .035-.135");
}

.bjatx4b1r {
  stop-color: var(--svg-color--c67e65, #C67E65);
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.bxy95rb0r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.909c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.317-.517 4.469-2.414");
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c0eouzbpy {
  d: path("M18.731 6.459c.037.049-.04.108-.126.173c-.087.065-.152.11-.188.062c-.037-.05.004-.141.091-.206s.187-.078.223-.03");
}

.c52b9egiw {
  d: path("m17.295 6.74l-.305 1.056c-.062.217.087.434.299.434h.451c.212 0 .362-.22.3-.434l-.306-1.056c-.065-.234-.37-.234-.439 0");
}

.c770b9b5t {
  stop-color: var(--svg-color--fdd0b9, #FDD0B9);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl8aicb8x {
  stop-color: var(--svg-color--fac9b2, #FAC9B2);
  stop-opacity: 0;
}

.cpfm5rbrk {
  stop-color: var(--svg-color--de9e80, #DE9E80);
}

.dqd47gnac {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
  stop-opacity: 0;
}

.duqocmbtl {
  stop-color: var(--svg-color--c1858a, #C1858A);
  stop-opacity: 0;
}

.dw0qvsbps {
  stop-color: var(--svg-color--ff8738, #FF8738);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e8kldcmkw {
  d: path("M19.226 6.795a.5.5 0 0 0-.133-.265l-.15.163l.068.132z");
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.evkljqb4p {
  stop-color: var(--svg-color--f8ccb5, #F8CCB5);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fhx-y7b1d {
  stop-color: var(--svg-color--c78584, #C78584);
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.g906eacpp {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m17.648 3.925l-.038-.078a.38.38 0 0 0-.353-.24h-.731a1.93 1.93 0 0 0-1.92 1.94v.158c-.194-.149-.44-.462-.44-.97c0-.615.449-.926.735-1.124c.081-.056.15-.103.19-.146l.058-.06c.2-.213.558-.592 1.182-.758a3 3 0 0 1 .521-.086c.472-.036.808.376.808.85v.507z");
}

.geedh9bvt {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.888 6.194c.375 0 .691.259.778.608a.157.157 0 0 1-.154.196h-1.281a.132.132 0 0 1-.13-.156a.8.8 0 0 1 .787-.648");
}

.gejm97-ji {
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.gfrv1jtdi {
  cx: 16.106px;
  cy: 6.569px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.224px;
  ry: 0.113px;
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.ggum98baz {
  d: path("M16.26 6.35a.513.513 0 0 0-.494.648h.99a.516.516 0 0 0-.496-.648");
}

.glvmfs77h {
  d: path("m17.648 3.925l-.038-.078a.38.38 0 0 0-.353-.24h-.731a1.93 1.93 0 0 0-1.92 1.94v.158c-.194-.149-.44-.462-.44-.97c0-.615.449-.926.735-1.124c.081-.056.15-.103.19-.146l.058-.06c.2-.213.558-.592 1.182-.758a3 3 0 0 1 .521-.086c.472-.036.808.376.808.85v.507z");
}

.gv6mn6b1l {
  d: path("M14.723 7.868a.94.94 0 0 1-.52-.177v.535c0 .513.306.97.77 1.16a2.4 2.4 0 0 1-.198-.678z");
}

.gv9be6ybc {
  stop-color: var(--svg-color--e15c10, #E15C10);
  stop-opacity: 0;
}

.h39qs2bdc {
  fill: var(--svg-color--dea899, #DEA899);
  d: path("m17.295 6.74l-.305 1.056c-.062.217.087.434.299.434h.451c.212 0 .362-.22.3-.434l-.306-1.056c-.065-.234-.37-.234-.439 0");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hahaolefz {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.142 6.194a.8.8 0 0 0-.779.608c-.025.1.052.196.154.196H16.8a.132.132 0 0 0 .13-.156a.805.805 0 0 0-.787-.648");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i6tnjcu8m {
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.idh4njbua {
  stop-color: var(--svg-color--c1858a, #C1858A);
}

.if2-x0_3s {
  d: path("M21.317 26.71c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jleiqdg7d {
  stop-color: var(--svg-color--d59a75, #D59A75);
}

.jppowlbfw {
  d: path("M18.769 6.35a.513.513 0 0 1 .494.648h-.99a.515.515 0 0 1 .496-.648");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kdih-nphy {
  stop-color: var(--svg-color--fdd0b9, #FDD0B9);
  stop-opacity: 0;
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l_2tb3bub {
  d: path("M14.618 6.083a.924.924 0 0 0 .074 1.838a45 45 0 0 1-.074-1.838");
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk8uk6bqv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.39 12.46l2.57 1.367");
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lrtdxszpp {
  d: path("M19.57 10.487c-1.778-.422-3.256-.227-4.111.002l.002.015v.778a2.054 2.054 0 1 0 4.107 0v-.778z");
}

.m_70hebjx {
  stop-color: var(--svg-color--e0aba2, #E0ABA2);
}

.m0mihob_v {
  stop-color: var(--svg-color--fb711e, #FB711E);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n_rrf5c9b {
  stop-color: var(--svg-color--efb29e, #EFB29E);
}

.nqt5hcbes {
  stop-color: var(--svg-color--e15c10, #E15C10);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o1o8fjb5d {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m20.508 5.801l-.017-.362a.844.844 0 0 0-.806-.819h-.805c-.51 0-.976-.279-1.22-.723c0 0 .414-1.194 1.1-1.04c.502.113 1.039.29 1.45.559c1.001.653.826 1.83.298 2.385");
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

.oj4p0xbcu {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m17.284 6.85l-.34 1.055c-.057.218.082.435.28.435h.42c.196 0 .336-.22.278-.435l-.285-1.055c-.06-.234-.289-.234-.353 0");
}

.osb6p5bii {
  d: path("M20.341 7.92q.058-.915.106-1.832a.924.924 0 0 1-.106 1.833");
}

.othzxvbxc {
  stop-color: var(--svg-color--f8ccb5, #F8CCB5);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ozmzmdbmh {
  stop-color: var(--svg-color--cc948d, #CC948D);
  stop-opacity: 0;
}

.p0vh6_8oj {
  d: path("M20.303 3.336c.295.101.56.308.728.603a1.36 1.36 0 0 1-.061 1.451a.9.9 0 0 0-.155.502v.683a1 1 0 0 0-.384-.154l.046-.923a.83.83 0 0 0-.793-.822h-.804a1.39 1.39 0 0 1-1.27-.829a.38.38 0 0 0-.353-.24h-.731a1.93 1.93 0 0 0-1.92 1.94l.018.883a1 1 0 0 0-.413.152v-.69a.9.9 0 0 0-.155-.502a1.37 1.37 0 0 1-.083-1.404c.168-.318.439-.54.747-.647a1.54 1.54 0 0 0 .795-.638a1.336 1.336 0 0 1 1.66-.523a.86.86 0 0 0 .685 0a1.335 1.335 0 0 1 1.666.542c.177.292.454.505.777.616");
}

.pbxwl2bes {
  stop-color: var(--svg-color--eab4a3, #EAB4A3);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.pygktylau {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.qcba1ryxr {
  stop-color: var(--svg-color--dfa9a2, #DFA9A2);
  stop-opacity: 0;
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qq8y08i1v {
  fill: var(--svg-color--fac0ab, #FAC0AB);
  d: path("M19.57 10.487c-1.778-.422-3.256-.227-4.111.002l.002.015v.778a2.054 2.054 0 1 0 4.107 0v-.778z");
}

.qti3hfbnx {
  d: path("M20.39 7.55q.033-.546.063-1.093a.549.549 0 0 1-.063 1.093");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_cv6ppfn {
  d: path("M6.74 16.107a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rb8xsab7w {
  stop-color: var(--svg-color--e19e8b, #E19E8B);
  stop-opacity: 0;
}

.rtl5rdb5z {
  stop-color: var(--svg-color--ad674f, #AD674F);
}

.rwh2s_4_v {
  fill: var(--svg-color--d59280, #D59280);
  d: path("M6.74 16.107a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.ry_er4bde {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m13.839 13.023l-2.97 2.719H8.558");
}

.s_vs1kbww {
  cx: 16.106px;
  cy: 6.569px;
  rx: 0.224px;
  ry: 0.113px;
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.sc-ixwf5u {
  stop-color: var(--svg-color--d59280, #D59280);
  stop-opacity: 0;
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.so-vzri7t {
  fill: var(--svg-color--ecbfa5, #ECBFA5);
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.sr3b7ccow {
  d: path("M20.306 7.868a.94.94 0 0 0 .52-.177v.535c0 .513-.306.97-.77 1.16a2.4 2.4 0 0 0 .198-.678z");
}

.ss6kf5hyw {
  stop-color: var(--svg-color--d59a75, #D59A75);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t33371etg {
  stop-color: var(--svg-color--c67e65, #C67E65);
  stop-opacity: 0;
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.td6euhb6l {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.tf5rpdjwu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.473c.41.162 1.402.784 2.096 1.97");
}

.tghgar6wi {
  d: path("M16.729 6.802c0-.165-.135-.276-.171-.309l-.166.16l.102.208z");
}

.tjs3mxdap {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.658 5.44a1.05 1.05 0 0 0-.395-.237c-.174-.055-.393-.07-.696-.033a.16.16 0 0 0 .039.316c.276-.033.445-.016.562.02c.114.037.19.095.281.173a.16.16 0 0 0 .21-.24");
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.usg16obsd {
  stop-color: var(--svg-color--eebda5, #EEBDA5);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uwupv_ztt {
  d: path("M14.255 10.891c0-.039.022-.074.058-.09c.2-.089.63-.262 1.09-.346a.05.05 0 0 1 .058.049v.778a2.054 2.054 0 1 0 4.107 0v-.778a.05.05 0 0 1 .058-.05c.462.085.92.259 1.125.348c.036.015.058.05.058.09v6.386a.6.6 0 0 1-.6.6h-5.354a.6.6 0 0 1-.6-.6z");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vjc3blqru {
  stop-color: var(--svg-color--eab4a3, #EAB4A3);
}

.vm-_3abon {
  d: path("m20.508 5.801l-.017-.362a.844.844 0 0 0-.806-.819h-.805c-.51 0-.976-.279-1.22-.723c0 0 .414-1.194 1.1-1.04c.502.113 1.039.29 1.45.559c1.001.653.826 1.83.298 2.385");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.w-3uv5bmy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M23.992 7.765v1.121a.5.5 0 0 0 .146.354l.904.904");
}

.w-8ib2bba {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.991 23.955c-.307.353-1.133 1.1-1.885 1.832");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w56t05b1o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.731 6.459c.037.049-.04.108-.126.173c-.087.065-.152.11-.188.062c-.037-.05.004-.141.091-.206s.187-.078.223-.03");
}

.w7c-tt7cs {
  stop-color: var(--svg-color--ba7159, #BA7159);
}

.w7zfnqfut {
  stop-color: var(--svg-color--de9e80, #DE9E80);
  stop-opacity: 0;
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x8wsft-hb {
  stop-color: var(--svg-color--db6229, #DB6229);
}

.xggiw4btv {
  fill: var(--svg-color--000, #000);
  d: path("M18.475 6.863c0-.163.13-.294.294-.294a.292.292 0 0 1 .26.429h-.519a.3.3 0 0 1-.035-.135");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yafg_whjr {
  stop-color: var(--svg-color--eb6820, #EB6820);
}

.ye27a6avl {
  d: path("M14.594 6.462a.549.549 0 0 0 .048 1.08q-.03-.54-.048-1.08");
}

.yk4r1ybxd {
  fill: var(--svg-color--fcc8ab, #FCC8AB);
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yr50mjbls {
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.ywzroibeu {
  stop-color: var(--svg-color--fac9b2, #FAC9B2);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z68enctpn {
  d: path("M14.744 8.739a2.25 2.25 0 0 0 2.231 1.956h1.084c1.13 0 2.084-.835 2.231-1.956c.068-1.082.136-2.16.187-3.24a.83.83 0 0 0-.793-.823h-.804a1.39 1.39 0 0 1-1.27-.829a.38.38 0 0 0-.353-.24h-.731a1.93 1.93 0 0 0-1.92 1.94c0 1.069.068 2.12.138 3.192");
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zcfme9b2u {
  stop-color: var(--svg-color--cc948d, #CC948D);
}

.zkv-t1bbq {
  stroke: var(--svg-color--ffcfb8, #FFCFB8);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M25.156 14.007v-3.781l.594-.406V8.742");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
